<template>
    <div>
        <header class="border-b border-gray-100 bg-success">
            <div class="flex items-center justify-between h-10 mx-auto sm:px-6 lg:px-8">
                <div class="flex items-center">
                    <button
                        class="mr-2 navbar-toggler text-gray-200 border-0 hover:shadow-none hover:no-underline py-2 px-2.5 bg-transparent focus:outline-none focus:ring-0 focus:shadow-none focus:no-underline"
                        type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent1"
                        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="bars" class="w-6"
                            role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                            <path fill="currentColor"
                                d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z">
                            </path>
                        </svg>
                    </button>

                    <a href="" class="flex items-center text-center">
                        <h1 class="inline-block w-32 h-10 text-3xl text-white rounded-lg ">MYLogo</h1>
                    </a>
                </div>

                <div class="flex items-center justify-end flex-1">
                    <!-- <nav
                        class="hidden lg:uppercase lg:text-gray-500 lg:tracking-wide lg:font-bold lg:text-xs lg:space-x-4 lg:flex">
                        <a href="/about"
                            class="block h-16 leading-[4rem] border-b-4 border-transparent hover:text-red-700 hover:border-current">
                            Category 1
                        </a>

                        <a href="/news"
                            class="block h-16 leading-[4rem] border-b-4 border-transparent hover:text-red-700 hover:border-current">
                            Category 2
                        </a>

                        <a href="/products"
                            class="block h-16 leading-[4rem] border-b-4 border-transparent hover:text-red-700 hover:border-current">
                            Category 3
                        </a>

                        <a href="/contact"
                            class="block h-16 leading-[4rem] border-b-4 border-transparent hover:text-red-700 hover:border-current">
                            Category 4
                        </a>
                    </nav> -->

                    <div class="flex items-center ml-8">
                        <div class="flex items-center">
                            <!-- <span>
                                <a href="/cart" class="block p-6 border-b-4 border-transparent hover:border-red-700">
                                    <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor"
                                        xmlns="http://www.w3.org/2000/svg">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M16 11V7a4 4 0 00-8 0v4M5 9h14l1 12H4L5 9z" />
                                    </svg>

                                    <span class="sr-only">Cart</span>
                                </a>
                            </span> -->

                            <!-- <span>
                                <a href="/account" class="block p-6 border-b-4 border-transparent hover:border-red-700">
                                    <svg class="w-4 h-4" xmlns="http://www.w3.org/2000/svg" fill="none"
                                        viewBox="0 0 24 24" stroke="currentColor">
                                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                            d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                                    </svg>

                                    <span class="sr-only"> Account </span>
                                </a>
                            </span> -->


                            <span class="sm:block">
                                <NuxtLink href="/search" class="border-transparent btn btn-success">
                                    <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor"
                                        class="bi bi-search" viewBox="0 0 16 16">
                                        <path
                                            d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z" />
                                    </svg>
                                </NuxtLink>
                            </span>
                        </div>
                    </div>
                </div>
            </div>
        </header>
    </div>
</template>