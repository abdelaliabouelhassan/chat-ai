<template>
     <div id="messages" class="flex h-full flex-col space-y-4 p-3 overflow-y-auto scrollbar-thumb-blue scrollbar-thumb-rounded scrollbar-track-blue-lighter scrollbar-w-2 scrolling-touch">
                    
                    <!-- user message add 'justify-end'  -->
                    <div class="chat-message">
                        <div class="flex items-end justify-end"> <!-- add it here -->
                            <div class="flex flex-col space-y-2 text-xs max-w-xs mx-2 order-1 items-end">
                                <div><span class="px-4 py-2 rounded-lg inline-block rounded-br-none bg-blue-600 text-white ">Your error message says permission denied, npm global installs must be given root privileges.</span></div>
                            </div>
                            <img src="https://images.unsplash.com/photo-1590031905470-a1a1feacbb0b?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=144" alt="My profile" class="w-6 h-6 rounded-full order-2">
                        </div>
                    </div>       

                      <!-- gpt message remove 'justify-end'  -->
                    <div class="chat-message">
                    <div class="flex items-end">   <!--  remove 'justify-end'  -->
                        <div class="flex items-start gap-2.5">
                            <img class="w-8 h-8 rounded-full" src="https://images.unsplash.com/photo-1549078642-b2ba4bda0cdb?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=14" alt="Jese image">
                            <div class="flex flex-col w-full max-w-[320px] leading-1.5 p-4 border-gray-200   bg-gray-300  rounded-e-xl rounded-es-xl dark:bg-gray-700">
                                <div class="flex items-center space-x-2 rtl:space-x-reverse">
                                    <span class="text-sm font-semibold text-gray-600 dark:text-white">Bonnie Green</span>
                                    <span class="text-sm font-normal text-gray-500 dark:text-gray-400">11:46</span>
                                </div>
                                <p class="text-sm font-normal py-2.5 text-gray-600 dark:text-white">That's awesome. I think our users will really appreciate the improvements.</p>
                                <!-- <span class="text-sm font-normal text-gray-500 dark:text-gray-400">Delivered</span> -->
                            </div>
                            </div>
                    </div>     
                    </div>
                     <div class="chat-message">
                        <div class="flex items-end">
                            <div class="flex items-start gap-2.5">
                                <img class="w-8 h-8 rounded-full" src="https://images.unsplash.com/photo-1549078642-b2ba4bda0cdb?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=14" alt="Jese image">
                                <div class="flex flex-col w-full  space-y-4 leading-1.5 p-4 border-gray-200   bg-gray-300  rounded-e-xl rounded-es-xl dark:bg-gray-700">
                                    <div class="flex items-center space-x-2 rtl:space-x-reverse">
                                        <span class="text-sm font-semibold text-gray-600 dark:text-white">Bonnie Green</span>
                                        <span class="text-sm font-normal text-gray-500 dark:text-gray-400">11:46</span>
                                    </div>
                                 

                                    <div class="relative max-w-xs md:max-w-3xl overflow-x-auto  sm:rounded-lg">
                                        <table class="w-full text-sm text-left rtl:text-right text-gray-500 dark:text-gray-400">
                                            <thead class="text-xs text-gray-700 uppercase bg-gray-50 dark:bg-gray-700 dark:text-gray-400">
                                                <tr>
                                                    <th scope="col" class="px-6 py-3">
                                                        Name
                                                    </th>
                                                    <th scope="col" class="px-6 py-3">
                                                        Title
                                                    </th>
                                                    <th scope="col" class="px-6 py-3">
                                                        Rate
                                                    </th>
                                                    <th scope="col" class="px-6 py-3">
                                                        description
                                                    </th>
                                                    <th scope="col" class="px-6 py-3">
                                                        Action
                                                    </th>
                                                </tr>
                                            </thead>
                                            <tbody>
                                                <tr class="odd:bg-white odd:dark:bg-gray-900 even:bg-gray-50 even:dark:bg-gray-800 border-b dark:border-gray-700">
                                                    <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                                        Hotel 1
                                                    </th>
                                                    <td class="px-6 py-4">
                                                        Silver
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        10
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sunt quis d
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">View</a>
                                                    </td>
                                                </tr>
                                                 <tr class="odd:bg-white odd:dark:bg-gray-900 even:bg-gray-50 even:dark:bg-gray-800 border-b dark:border-gray-700">
                                                    <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                                        Hotel 2
                                                    </th>
                                                    <td class="px-6 py-4">
                                                        Silver
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        8
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sunt quis d
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">View</a>
                                                    </td>
                                                </tr>
                                                   <tr class="odd:bg-white odd:dark:bg-gray-900 even:bg-gray-50 even:dark:bg-gray-800 border-b dark:border-gray-700">
                                                    <th scope="row" class="px-6 py-4 font-medium text-gray-900 whitespace-nowrap dark:text-white">
                                                        Hotel 3
                                                    </th>
                                                    <td class="px-6 py-4">
                                                        Silver
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        9
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Sunt quis d
                                                    </td>
                                                    <td class="px-6 py-4">
                                                        <a href="#" class="font-medium text-blue-600 dark:text-blue-500 hover:underline">View</a>
                                                    </td>
                                                </tr>
                                            </tbody>
                                        </table>
                                    </div>

                                    <!-- <span class="text-sm font-normal text-gray-500 dark:text-gray-400">Delivered</span> -->
                                </div>
                                </div>
                        </div>     
                     </div>
        
                
    </div>
          <!-- Input  -->
                <div class="border-t-2 border-gray-200 dark:border-gray-500 px-4 pt-4 mb-2 sm:mb-0">
                    <div class="relative flex">
                        <!-- <span class="absolute inset-y-0 flex items-center">
                            <button type="button" class="inline-flex items-center justify-center rounded-full h-12 w-12 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-gray-600">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z"></path>
                            </svg>
                            </button>
                        </span> -->
                        <input @keyup.enter="Send" v-model="message" type="text" placeholder="Write your message!" class="w-full focus:outline-none focus:placeholder-gray-400 text-gray-600 placeholder-gray-600 pl-4 bg-gray-200 dark:bg-gray-700 dark:text-white dark:placeholder-gray-300 rounded-md py-3">
                        <div class="absolute right-0 items-center inset-y-0 hidden sm:flex">
                            <!-- <button type="button" class="inline-flex items-center justify-center rounded-full h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-gray-600">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"></path>
                            </svg>
                            </button>
                            <button type="button" class="inline-flex items-center justify-center rounded-full h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-gray-600">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z"></path>
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z"></path>
                            </svg>
                            </button>
                            <button type="button" class="inline-flex items-center justify-center rounded-full h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-gray-600">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
                            </svg>
                            </button> -->
                            <button @click="Send" type="button" class="inline-flex items-center justify-center rounded-lg px-4 py-3 transition duration-500 ease-in-out text-white bg-blue-500 hover:bg-blue-400 focus:outline-none">
                            <span class="font-bold">Send</span>
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="h-6 w-6 ml-2 transform rotate-90">
                                <path d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"></path>
                            </svg>
                            </button>
                        </div>
                    </div>
                </div>
</template>

<script setup>
import axios from "axios"
 
const config = useRuntimeConfig()
const message = ref('')
const token = ref(null)
const router = useRouter()
const route = useRoute()
const id = ref(null)


const Send = () => {
    
}

const loadMessages = () => {
     axios.get(config.public.API_URL + '/booking/gpt/' + id.value,{
         headers: {
            Authorization: `Bearer ${token.value}`,
        },
     })
    .then((res) => {
        console.log(res)
      
        
    }).catch((error) => {
        loginRef.value.open = true
    })
}


 onMounted(() => {
     id.value = route.params.id
    token.value = localStorage.getItem('access')
    const el = document.getElementById('messages')
	el.scrollTop = el.scrollHeight
    loadMessages()
   })
</script>