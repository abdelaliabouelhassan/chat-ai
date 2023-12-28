<template>
    <div :class="{' hidden':!openContact,'block':openContact}"  class=" absolute sm:relative  top-0 left-0 bg-white dark:bg-gray-800 sm:bg-transparent  z-50 sm:block sm:max-w-[16rem] lg:max-w-sm w-full h-full border-r dark:border-gray-500 ">
           <div class=" w-full flex justify-end p-4">
         
              <button @click="openContact = !openContact" type="button" class="dark:border-gray-500 inline-flex sm:hidden items-center justify-center rounded-lg border h-10 w-10 transition duration-500 ease-in-out text-gray-500 hover:bg-gray-300 focus:outline-none">
                          <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
                            <path stroke-linecap="round" stroke-linejoin="round" d="m9.75 9.75 4.5 4.5m0-4.5-4.5 4.5M21 12a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                        </svg>
               </button> 
           </div>
              <div class=" w-full relative">
                <div class="  absolute top-0 h-10 sm:h-[7.1rem] border-b-2 border-gray-200 dark:border-gray-500 left-0 w-full bg-white dark:bg-gray-800">
                    <div class="flex items-center bg-white w-full  dark:bg-gray-800 absolute bottom-2 px-3 py-2  ">
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
                <div class="h-full max-h-full overflow-y-auto pb-5 pt-14 sm:pt-[7.5rem]">

                    <div
                        class="px-5 py-4   flex items-center   cursor-pointer border-l-4 border-l-transparent hover:bg-slate-100 dark:hover:bg-gray-700">
                        <img src="https://images.unsplash.com/photo-1628157588553-5eeea00af15c?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MTZ8fHVzZXJzfGVufDB8MnwwfHw%3D&auto=format&fit=crop&w=500"
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 dark:text-gray-300 m-0 p-0">Yaroslav Zubkp
                            </p>
                            <p class="text-xs text-slate-400 dark:text-gray-500 -mt-0.5 font-semibold" x-text="user.email">is is long ipsum
                                avaliable...</p>
                        </div>
                    </div>

                

                    <div
                        class="px-5 py-4   flex items-center bg-white dark:bg-gray-900 cursor-pointer border-l-4 border-l-blue-500  dark:border-y-gray-500 border-t border-b dark:hover:bg-gray-700">
                        <img src="https://images.unsplash.com/photo-1570295999919-56ceb5ecca61?crop=entropy&cs=tinysrgb&fm=jpg&ixlib=rb-1.2.1&q=60&raw_url=true&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MXx8dXNlcnN8ZW58MHwyfDB8fA%3D%3D&auto=format&fit=crop&w=500 "
                            class="h-12 w-12 border-2 border-white rounded-full" alt="">
                        <div class="ml-4">
                            <p x-text="user.name" class="text-md font-semibold text-slate-600 m-0 p-0 dark:text-gray-300 "> Mircel Jones</p>
                            <p class="text-xs text-slate-400 -mt-0.5 font-semibold dark:text-gray-500 " x-text="user.email">Ok, Thanks.</p>
                        </div>
                    </div>

               

                 

                    <!-- else -->


                </div>
            </div>
</template>

<script setup>
 const openContact = useOpenList()
</script>