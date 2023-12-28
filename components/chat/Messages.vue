<template>
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
                                <div class="group relative my-2.5 cursor-pointer">
                                    
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
                                    <div class="group relative cursor-pointer">
                                        
                                        <img src="https://flowbite.com/docs/images/blog/image-1.jpg" class="rounded-lg" />
                                    </div>
                                    <div class="group relative cursor-pointer">
                                    
                                        <img src="https://flowbite.com/docs/images/blog/image-2.jpg" class="rounded-lg" />
                                    </div>
                                    <div class="group relative cursor-pointer">
                                    
                                        <img src="https://flowbite.com/docs/images/blog/image-3.jpg" class="rounded-lg" />
                                    </div>
                                    <div class="group relative cursor-pointer">
                                        
                                        <img src="https://flowbite.com/docs/images/blog/image-1.jpg" class="rounded-lg" />
                                    </div>
                                </div>
                            
                            </div>
                        </div>
                        
                        </div>

                    

                        </div>
                    </div>


                    
                    
                
                </div>
</template>

<script setup>
 onMounted(() => {
    const el = document.getElementById('messages')
	el.scrollTop = el.scrollHeight
   })
</script>