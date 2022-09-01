<template>
    <div class="sticky inset-0 top-0 z-50">
        <header>
            <!-- Navbar Logo -->
            <div>
                <nav class="bg-green-700 lg:bg-gray-200">
                    <div class="flex items-center justify-between lg:h-28    mx-auto sm:px-6 lg:px-8">
                        <div class="flex items-center">

                            <!-- Toggle -->
                            <button
                                class="lg:hidden block mr-2 navbar-toggler text-gray-200 border-0 hover:shadow-none hover:no-underline py-2 px-2.5 bg-transparent focus:outline-none focus:ring-0 focus:shadow-none focus:no-underline"
                                type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent1"
                                aria-controls="navbarSupportedContent" aria-expanded="false"
                                aria-label="Toggle navigation">
                                <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="bars" class="w-6"
                                    role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                                    <path fill="currentColor"
                                        d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z">
                                    </path>
                                </svg>
                            </button>

                            <!-- Logo -->
                            <div class="flex flex-col">
                                <a href="" class="flex items-center text-center">
                                    <h1
                                        class="inline-block w-32 h-10 text-3xl lg:text-5xl text-gray-100 lg:text-gray-900 rounded-lg">
                                        MYLogo</h1>
                                </a>
                                <div class="text-xs hidden lg:flex my-2 items-center text-center">
                                    <p>Hello</p>
                                </div>
                            </div>
                        </div>

                        <!-- Search -->
                        <div class="flex items-center justify-end flex-1 lg:hidden">
                            <div class="flex items-center ml-8">
                                <div class="flex items-center">
                                    <span class="sm:block">
                                        <NuxtLink href="/" class="border-transparent btn btn-success">
                                            <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16"
                                                fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                                                <path
                                                    d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                                            </svg>
                                        </NuxtLink>
                                    </span>
                                </div>
                            </div>
                        </div>

                        <!-- AdSpaceLogo -->
                        <div class="px-32 py-6 bg-gray-100 items-start justify-start hidden lg:block">
                            <p>adspace</p>
                        </div>
                    </div>
                </nav>
            </div>

            <!-- Navbar Category -->
            <div class="lg:flex items-center justify-between w-full mx-auto h-11 hidden">
                <!-- Tabs -->
                <nav
                    class="w-full items-center justify-between space-x-6 text-sm font-medium bg-white lg:flex lg:flex-grow lg:w-0">
                    <ul class="flex text-center bg-white border-b border-gray-200">
                        <li class="flex-grow">
                            <a class="relative block px-4 py-3 text-sm font-medium bg-white border-t border-l border-r border-gray-200"
                                href="">
                                <span class="absolute inset-x-0 w-full h-px bg-white -bottom-px"></span>
                                Home
                            </a>
                        </li>
                        <li class="flex-grow">
                            <a class="block px-4 py-3 text-sm font-medium text-gray-500" href=""> Category 1 </a>
                        </li>

                        <li class="flex-grow">
                            <a class="block px-4 py-3 text-sm font-medium text-gray-500" href=""> Category 2 </a>
                        </li>

                        <li class="flex-grow">
                            <a class="block px-4 py-3 text-sm font-medium text-gray-500" href=""> Category 3 </a>
                        </li>
                        <li class="flex-grow">
                            <a class="block px-4 py-3 text-sm font-medium text-gray-500" href=""> Category 4 </a>
                        </li>
                        <li class="flex-grow">
                            <a class="block px-4 py-3 text-sm font-medium text-gray-500" href=""> Category 5 </a>
                        </li>
                    </ul>

                    <!-- Auth -->
                    <div class="items-center hidden space-x-2 lg:flex">
                        <a class="px-4 py-2 text-sm font-medium text-gray-600 bg-gray-100" href="">
                            Log in
                        </a>
                        <a class="px-4 py-2 text-sm font-medium text-white bg-slate-600" href="">
                            Sign up
                        </a>
                    </div>
                </nav>
            </div>

            <!-- Navbar SubCategory -->
            <div class="lg:flex items-center justify-between w-full mx-auto h-10 hidden">
                <nav
                    class="border border-gray-200 lg:flex hidden items-center justify-between w-full text-gray-500 bg-white hover:text-gray-700 focus:text-gray-700 navbar-expand-lg navbar-light">
                    <div class="flex flex-wrap items-center justify-between w-full px-6">
                        <div class="items-center flex-grow collapse navbar-collapse" id="navbarSupportedContent">
                            <ul class="text-xs flex flex-col pl-0 mr-auto navbar-nav list-style-none">
                                <li class="p-2 nav-item border-r border-gray-200">
                                    <a class="p-0 text-gray-500 nav-link hover:text-gray-700 focus:text-gray-700"
                                        href="#">Sub-Category 1</a>
                                </li>
                                <li class="p-2 nav-item border-r border-gray-200">
                                    <a class="p-0 text-gray-500 nav-link hover:text-gray-700 focus:text-gray-700"
                                        href="#">Sub-Category 2</a>
                                </li>
                                <li class="p-2 nav-item border-r border-gray-200">
                                    <a class="p-0 text-gray-500 nav-link hover:text-gray-700 focus:text-gray-700"
                                        href="#">Sub-Category 3</a>
                                </li>
                                <li class="p-2 nav-item border-r border-gray-200">
                                    <a class="p-0 text-gray-500 nav-link hover:text-gray-700 focus:text-gray-700"
                                        href="#">Sub-Category 4</a>
                                </li>
                                <li class="p-2 nav-item border-r border-gray-200">
                                    <a class="p-0 text-gray-500 nav-link hover:text-gray-700 focus:text-gray-700"
                                        href="#">Sub-Category 5</a>
                                </li>
                                <li class="p-2 nav-item border-r border-gray-200">
                                    <a class="p-0 text-gray-500 nav-link hover:text-gray-700 focus:text-gray-700"
                                        href="#">Sub-Category 6</a>
                                </li>
                            </ul>
                        </div>
                    </div>
                </nav>
            </div>
        </header>
    </div>
</template>