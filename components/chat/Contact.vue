<template>
    <div :class="{' hidden':!openContact,'block':openContact}"  class=" absolute  sm:relative  top-0 left-0 bg-white dark:bg-gray-800 sm:bg-transparent  z-50 sm:block sm:max-w-[16rem] lg:max-w-sm w-full h-full border-r dark:border-gray-500 ">
           <div class=" w-full flex justify-end px-4 pt-4">
            
              <button @click="openContact = !openContact" type="button" class="dark:border-gray-500 inline-flex sm:hidden items-center justify-center rounded-lg border h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="m9.75 9.75 4.5 4.5m0-4.5-4.5 4.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                        </svg>
               </button> 
           </div>
              <div class=" w-full relative py-4">
                <div class="  absolute  space-y-4  sm:h-[7.1rem] border-b-2 flex flex-col justify-between border-gray-200 dark:border-gray-500 left-0 w-full bg-white dark:bg-gray-800">
                   <div class=" w-full px-4 pt-2">
                     <button @click="AddNewChat" class=" w-full  bg-blue-500 text-white flex items-center hover:scale-x-105 duration-200 rounded-md justify-center py-2">
                        <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                           <path stroke-linecap="round" stroke-linejoin="round" d="M12 4.5v15m7.5-7.5h-15" />
                        </svg>
                        <span>Add new Chat</span>
                    </button>
                   </div>
                    <div class="flex items-center bg-white w-full  dark:bg-gray-800   px-3 py-2  ">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 stroke-slate-300 mr-5" fill="none"
                            viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                        </svg>
                        <input type="text"  placeholder="Search.."
                            class=" w-full outline-none placeholder:text-slate-300 dark:bg-gray-800 font-semibold dark:text-white">
                    </div>
            
                </div>
                </div>
                <div class="h-full max-h-full overflow-y-auto pb-[6rem] md:pb-[4rem] pt-28 sm:pt-[7.5rem]">

                    <div
                        v-for="(item,index,key) in sessions.slice().reverse()" :key="key"
                        @click="openChat(item)"
                        class="px-5 py-4   flex items-center bg-white dark:bg-gray-800 cursor-pointer  border-l-blue-500  dark:border-y-gray-500 border-t border-b dark:hover:bg-gray-700" :class="{'border-l-4':item == id}">
                        <img src="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dXNlcnN8ZW58MHwyfDB8fA%3D%3D&auto=format&fit=crop&w=500 "
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0 dark:text-gray-300 "> Mircel Jones</p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold dark:text-gray-500 " x-text="user.email">Ok, Thanks.</p>
                        </div>
                    </div>

           

                </div>
            </div>
</template>

<script setup>
import axios from "axios"

 const openContact = useOpenList()
 const config = useRuntimeConfig()
 const token = ref(null)
 const router = useRouter()
 const route = useRoute()
 const id = ref(null)
 const props = defineProps({
    sessions:{
        type:[Array,Object],
        default:[]
    }
 })

 const AddNewChat = () => {
     axios.get(config.public.API_URL + '/booking/session/',{
         headers: {
            Authorization: `Bearer ${token.value}`,
        },
     })
    .then((res) => {
        props.sessions.push(res.data.session_id)
        router.push(res.data.session_id)
        
    }).catch((error) => {
        loginRef.value.open = true
    })
 }
 
 const openChat = (item) => {
    router.push(item)
 }

 onMounted(() => {
    token.value = localStorage.getItem('access')
    id.value = route.params.id
    openContact.value = false
 })

 


</script>