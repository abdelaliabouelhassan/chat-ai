<template>
   <div class=" w-full h-screen flex items-start dark:bg-gray-800 relative">
            <Contact  />
            <div class="flex-1 p:2 sm:p-6 justify-between flex flex-col h-full">
               <Header ref="HeaderRef" />
               <Messages />
               <Input />
             </div>
        </div>
</template>



<script setup>
 import DarkMode from '@/components/UI/DarkMode.vue'
 import Header from '@/components/chat/Header.vue'
 import Contact from '@/components/chat/Contact.vue'
 import Messages  from '@/components/chat/Messages.vue'
 import Input from '@/components/chat/Input.vue'

 const HeaderRef = ref(null)
</script>


