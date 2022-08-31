<template>
    <div class="py-2">
        <header class="">
            <div class="flex items-center justify-between h-12 max-w-screen-xl px-4 mx-auto">
                <!-- <div class="flex justify-end flex-grow w-0 lg:hidden">
                    <button class="p-2 text-gray-500 bg-gray-100 rounded-full" type="button">
                        <svg class="w-5 h-5" fill="currentColor" viewbox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                            <path clip-rule="evenodd"
                                d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z"
                                fill-rule="evenodd"></path>
                        </svg>
                    </button>
                </div> -->

                <nav
                    class="items-center justify-between hidden space-x-6 text-sm font-medium lg:flex lg:flex-grow lg:w-0">
                    <!-- <a class="text-gray-900" href="">About</a>
                    <a class="text-gray-900" href="">Blog</a>
                    <a class="text-gray-900" href="">Projects</a>
                    <a class="text-gray-900" href="">Contact</a> -->

                    <ul class="flex text-center border-b border-gray-200">
                        <li class="flex-grow">
                            <a class="relative block p-3 text-sm font-medium bg-white border-t border-l border-r border-gray-200"
                                href="">
                                <span class="absolute inset-x-0 w-full h-px bg-white -bottom-px"></span>
                                Home
                            </a>
                        </li>

                        <li class="flex-grow">
                            <a class="block p-3 text-sm font-medium text-gray-500" href=""> Category 1 </a>
                        </li>

                        <li class="flex-grow">
                            <a class="block p-3 text-sm font-medium text-gray-500" href=""> Category 2 </a>
                        </li>

                        <li class="flex-grow">
                            <a class="block p-3 text-sm font-medium text-gray-500" href=""> Category 3 </a>
                        </li>
                        <li class="flex-grow">
                            <a class="block p-3 text-sm font-medium text-gray-500" href=""> Category 3 </a>
                        </li>
                        <li class="flex-grow">
                            <a class="block p-3 text-sm font-medium text-gray-500" href=""> Category 3 </a>
                        </li>
                    </ul>

                </nav>

                <div class="items-center hidden space-x-2 lg:flex">
                    <a class="px-4 py-2 text-sm font-medium text-gray-600 bg-gray-100 rounded-lg" href="">
                        Log in
                    </a>
                    <a class="px-4 py-2 text-sm font-medium text-white bg-blue-600 rounded-lg" href="">
                        Sign up
                    </a>
                </div>
            </div>
        </header>
    </div>
</template>