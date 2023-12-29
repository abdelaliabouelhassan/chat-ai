<template>
   <div class=" w-full h-screen flex items-start dark:bg-gray-800 relative">
            <Contact  :sessions='sessions'/>
            <div class="flex-1 p:2 sm:p-6 justify-between flex flex-col h-full">
               <Header ref="HeaderRef" />
               <Messages v-if="id" />
                <div class=" w-full h-full flex" v-else>
                    <div class=" m-auto text-white text-2xl ">
                        Start New Conversation
                    </div>
             </div>
             </div>

            

             <Login ref="loginRef" />
        </div>
</template>



<script setup>
 import DarkMode from '@/components/UI/DarkMode.vue'
 import Header from '@/components/chat/Header.vue'
 import Contact from '@/components/chat/Contact.vue'
 import Messages  from '@/components/chat/Messages.vue'
 import Login from '@/components/Login.vue'
 import axios from 'axios'
 const config = useRuntimeConfig()
 const HeaderRef = ref(null)
 const loginRef = ref(false)
 const token = ref(null)
 const sessions = ref([])
 const id = ref(null)
  const router = useRouter()
 const route = useRoute()
 
 const checkLogin = () => {
    token.value = localStorage.getItem('access')
   if(!token){
      loginRef.value.open = true
   }
 }

 const loadSessions = () => {
     axios.get(config.public.API_URL + '/booking/session-details/',{
         headers: {
            Authorization: `Bearer ${token.value}`,
        },
     })
        .then((res) => {
            sessions.value = res.data.session_ids
          
        }).catch((error) => {
            loginRef.value.open = true
        })
 }

 onMounted(() => {
   id.value = route.params.id
   checkLogin()
   loadSessions()
   
 })
</script>


