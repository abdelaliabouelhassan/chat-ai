<template>
  <div>
  
        <div class=" w-full h-screen flex items-start">
            <div class=" hidden sm:block sm:max-w-[16rem] lg:max-w-sm w-full h-full border-r ">
              <div class=" w-full relative">
                <div class="  absolute top-0 h-[7.1rem] border-b-2 border-gray-200 left-0 w-full bg-white">
                    <div class="flex items-center bg-white w-full  absolute bottom-2 px-3 py-2  ">
                        <svg xmlns="http://www.w3.org/2000/svg" class="h-5 stroke-slate-300 mr-5" fill="none"
                            viewBox="0 0 24 24" stroke="currentColor" stroke-width="3">
                            <path stroke-linecap="round" stroke-linejoin="round"
                                d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                        </svg>
                        <input type="text"  placeholder="Search.."
                            class=" w-full outline-none placeholder:text-slate-300 font-semibold">
                    </div>
            
                </div>
                </div>
                <div class="h-full max-h-full overflow-y-auto pb-5 pt-[7.5rem]">

                    <div
                        class="px-5 py-4   flex items-center   cursor-pointer border-l-4 border-l-transparent hover:bg-slate-100">
                        <img src="https://images.unsplash.com/photo-1628157588553-5eeea00af15c?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fHVzZXJzfGVufDB8MnwwfHw%3D&auto=format&fit=crop&w=500"
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0">Yaroslav Zubkp
                            </p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold" x-text="user.email">is is long ipsum
                                avaliable...</p>
                        </div>
                    </div>

                    <div
                        class="px-5 py-4   flex items-center   cursor-pointer border-l-4 border-l-transparent hover:bg-slate-100">
                        <img src="https://images.unsplash.com/photo-1499887142886-791eca5918cd?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTV8fHVzZXJzfGVufDB8MnwwfHw%3D&auto=format&fit=crop&w=500 "
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0"> Alison Alison
                            </p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold" x-text="user.email">Hello</p>
                        </div>
                    </div>

                    <div
                        class="px-5 py-4   flex items-center bg-white cursor-pointer border-l-4 border-l-blue-500 border-t border-b">
                        <img src="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dXNlcnN8ZW58MHwyfDB8fA%3D%3D&auto=format&fit=crop&w=500 "
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0"> Mircel Jones</p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold" x-text="user.email">Ok, Thanks.</p>
                        </div>
                    </div>

                    <div
                        class="px-5 py-4   flex items-center   cursor-pointer border-l-4 border-l-transparent hover:bg-slate-100">
                        <img src="https://images.unsplash.com/photo-1633332755192-727a05c4013d?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8dXNlcnN8ZW58MHwyfDB8fA%3D%3D&auto=format&fit=crop&w=500"
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0">Uran Poland</p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold" x-text="user.email">We own hidden
                                lake..</p>
                        </div>
                    </div>

                    <div
                        class="px-5 py-4   flex items-center   cursor-pointer border-l-4 border-l-transparent hover:bg-slate-100">
                        <img src="https://images.unsplash.com/photo-1628157588553-5eeea00af15c?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fHVzZXJzfGVufDB8MnwwfHw%3D&auto=format&fit=crop&w=500"
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0">Yaroslav Zubkp
                            </p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold" x-text="user.email">is is long ipsum
                                avaliable...</p>
                        </div>
                    </div>

                    <div 
                        class="px-5 py-4   flex items-center   cursor-pointer border-l-4 border-l-transparent hover:bg-slate-100">
                        <img src="https://images.unsplash.com/photo-1499887142886-791eca5918cd?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTV8fHVzZXJzfGVufDB8MnwwfHw%3D&auto=format&fit=crop&w=500 "
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0"> Alison Alison
                            </p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold" x-text="user.email">Hello</p>
                        </div>
                    </div>

                 

                    <!-- else -->


                </div>
            </div>
            <div class="flex-1 p:2 sm:p-6 justify-between flex flex-col h-full">
                <div class="flex sm:items-center justify-between px-4 sm:px-0 py-3 border-b-2 border-gray-200">
                    <div class="relative flex items-center space-x-4">
                        <div class="relative">
                            <span class="absolute text-green-500 right-0 bottom-0">
                            <svg width="20" height="20">
                                <circle cx="8" cy="8" r="8" fill="currentColor"></circle>
                            </svg>
                            </span>
                        <img src="https://images.unsplash.com/photo-1549078642-b2ba4bda0cdb?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=144" alt="" class="w-10 sm:w-16 h-10 sm:h-16 rounded-full">
                        </div>
                        <div class="flex flex-col leading-tight">
                            <div class="text-2xl mt-1 flex items-center">
                            <span class="text-gray-700 mr-3">Anderson Vanhron</span>
                            </div>
                            <span class="text-lg text-gray-600">Junior Developer</span>
                        </div>
                    </div>
                    <div class="flex items-center space-x-2">
                        <!-- <button type="button" class="inline-flex items-center justify-center rounded-lg border h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path>
                            </svg>
                        </button>
                        <button type="button" class="inline-flex items-center justify-center rounded-lg border h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4.318 6.318a4.5 4.5 0 000 6.364L12 20.364l7.682-7.682a4.5 4.5 0 00-6.364-6.364L12 7.636l-1.318-1.318a4.5 4.5 0 00-6.364 0z"></path>
                            </svg>
                        </button> -->
                        <button type="button" class="inline-flex items-center justify-center rounded-lg border h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M12 3v2.25m6.364.386-1.591 1.591M21 12h-2.25m-.386 6.364-1.591-1.591M12 18.75V21m-4.773-4.227-1.591 1.591M5.25 12H3m4.227-4.773L5.636 5.636M15.75 12a3.75 3.75 0 1 1-7.5 0 3.75 3.75 0 0 1 7.5 0Z" />
                          </svg>
                          <!-- <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="M21.752 15.002A9.72 9.72 0 0 1 18 15.75c-5.385 0-9.75-4.365-9.75-9.75 0-1.33.266-2.597.748-3.752A9.753 9.753 0 0 0 3 11.25C3 16.635 7.365 21 12.75 21a9.753 9.753 0 0 0 9.002-5.998Z" />
                          </svg> -->


                        </button>
                    </div>
                </div>
                <div id="messages" class="flex h-full flex-col space-y-4 p-3 overflow-y-auto scrollbar-thumb-blue scrollbar-thumb-rounded scrollbar-track-blue-lighter scrollbar-w-2 scrolling-touch">
                    
                    <div class="chat-message">
                        <div class="flex items-end justify-end">
                            <div class="flex flex-col space-y-2 text-xs max-w-xs mx-2 order-1 items-end">
                                <div><span class="px-4 py-2 rounded-lg inline-block rounded-br-none bg-blue-600 text-white ">Your error message says permission denied, npm global installs must be given root privileges.</span></div>
                            </div>
                            <img src="https://images.unsplash.com/photo-1590031905470-a1a1feacbb0b?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=144" alt="My profile" class="w-6 h-6 rounded-full order-2">
                        </div>
                        </div>
                    
                        
                    
                        <div class="chat-message">
                        <div class="flex items-end">
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
                            <div class="flex flex-col gap-1">
                                <div class="flex flex-col w-full max-w-[326px] leading-1.5 p-4 border-gray-200 bg-gray-300  rounded-e-xl rounded-es-xl dark:bg-gray-700">
                                <div class="flex items-center space-x-2 rtl:space-x-reverse mb-2">
                                    <span class="text-sm font-semibold text-gray-600 dark:text-white">Bonnie Green</span>
                                    <span class="text-sm font-normal text-gray-500 dark:text-gray-400">11:46</span>
                                </div>
                                <p class="text-sm font-normal text-gray-600 dark:text-white">This is the new office </p>
                                <div class="group relative my-2.5">
                                    
                                    <img src="https://flowbite.com/docs/images/blog/image-2.jpg" class="rounded-lg" />
                                </div>
                                <!-- <span class="text-sm font-normal text-gray-500 dark:text-gray-400">Delivered</span> -->
                                </div>
                            </div>
                        </div>

                        </div>
                    </div>

                        <div class="chat-message">
                        <div class="flex items-end">

                        <div class="flex items-start gap-2.5">
                            <img class="w-8 h-8 rounded-full" src="https://images.unsplash.com/photo-1549078642-b2ba4bda0cdb?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=facearea&amp;facepad=3&amp;w=144&amp;h=14" alt="Jese image">
                        <div class="flex flex-col gap-1">
                            <div class="flex flex-col w-full max-w-[326px] leading-1.5 p-4 border-gray-200 bg-gray-300 rounded-e-xl rounded-es-xl dark:bg-gray-700">
                                <div class="flex items-center space-x-2 rtl:space-x-reverse mb-2">
                                    <span class="text-sm font-semibold text-gray-600 dark:text-white">Bonnie Green</span>
                                    <span class="text-sm font-normal text-gray-500 dark:text-gray-400">11:46</span>
                                </div>
                                <p class="text-sm font-normal text-gray-600 dark:text-white">This is the new office </p>
                                <div class="grid gap-4 grid-cols-2 my-2.5">
                                    <div class="group relative">
                                        
                                        <img src="https://flowbite.com/docs/images/blog/image-1.jpg" class="rounded-lg" />
                                    </div>
                                    <div class="group relative">
                                    
                                        <img src="https://flowbite.com/docs/images/blog/image-2.jpg" class="rounded-lg" />
                                    </div>
                                    <div class="group relative">
                                    
                                        <img src="https://flowbite.com/docs/images/blog/image-3.jpg" class="rounded-lg" />
                                    </div>
                                    <div class="group relative">
                                        
                                        <img src="https://flowbite.com/docs/images/blog/image-1.jpg" class="rounded-lg" />
                                    </div>
                                </div>
                            
                            </div>
                        </div>
                        
                        </div>

                    

                        </div>
                    </div>


                    
                    
                
                </div>
                <div class="border-t-2 border-gray-200 px-4 pt-4 mb-2 sm:mb-0">
                    <div class="relative flex">
                        <!-- <span class="absolute inset-y-0 flex items-center">
                            <button type="button" class="inline-flex items-center justify-center rounded-full h-12 w-12 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" class="h-6 w-6 text-gray-600">
                                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 11a7 7 0 01-7 7m0 0a7 7 0 01-7-7m7 7v4m0 0H8m4 0h4m-4-8a3 3 0 01-3-3V5a3 3 0 116 0v6a3 3 0 01-3 3z"></path>
                            </svg>
                            </button>
                        </span> -->
                        <input type="text" placeholder="Write your message!" class="w-full focus:outline-none focus:placeholder-gray-400 text-gray-600 placeholder-gray-600 pl-4 bg-gray-200 rounded-md py-3">
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
                            <button type="button" class="inline-flex items-center justify-center rounded-lg px-4 py-3 transition duration-500 ease-in-out text-white bg-blue-500 hover:bg-blue-400 focus:outline-none">
                            <span class="font-bold">Send</span>
                            <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="currentColor" class="h-6 w-6 ml-2 transform rotate-90">
                                <path d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.429A1 1 0 009 15.571V11a1 1 0 112 0v4.571a1 1 0 00.725.962l5 1.428a1 1 0 001.17-1.408l-7-14z"></path>
                            </svg>
                            </button>
                        </div>
                    </div>
                </div>
             </div>
        </div>

  </div>
</template>



<style>
.scrollbar-w-2::-webkit-scrollbar {
  width: 0.25rem;
  height: 0.25rem;
}

.scrollbar-track-blue-lighter::-webkit-scrollbar-track {
  --bg-opacity: 1;
  background-color: #f7fafc;
  background-color: rgba(247, 250, 252, var(--bg-opacity));
}

.scrollbar-thumb-blue::-webkit-scrollbar-thumb {
  --bg-opacity: 1;
  background-color: #edf2f7;
  background-color: rgba(237, 242, 247, var(--bg-opacity));
}

.scrollbar-thumb-rounded::-webkit-scrollbar-thumb {
  border-radius: 0.25rem;
}
</style>

<script setup>
	 onMounted(() => {
    const el = document.getElementById('messages')
	el.scrollTop = el.scrollHeight
   })
</script>