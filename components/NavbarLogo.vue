<template>
    <div class="">
        <nav class="bg-green-700 lg:bg-gray-200">
            <div class="flex items-center justify-between lg:h-28    mx-auto sm:px-6 lg:px-8">
                <div class="flex items-center">

                    <!-- Toggle -->
                    <button
                        class="lg:hidden block mr-2 navbar-toggler text-gray-200 border-0 hover:shadow-none hover:no-underline py-2 px-2.5 bg-transparent focus:outline-none focus:ring-0 focus:shadow-none focus:no-underline"
                        type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent1"
                        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                        <svg aria-hidden="true" focusable="false" data-prefix="fas" data-icon="bars" class="w-6"
                            role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
                            <path fill="currentColor"
                                d="M16 132h416c8.837 0 16-7.163 16-16V76c0-8.837-7.163-16-16-16H16C7.163 60 0 67.163 0 76v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16zm0 160h416c8.837 0 16-7.163 16-16v-40c0-8.837-7.163-16-16-16H16c-8.837 0-16 7.163-16 16v40c0 8.837 7.163 16 16 16z">
                            </path>
                        </svg>
                    </button>

                    <!-- Logo -->
                    <div class="flex flex-col justify-between gap-2">
                        <a href="/" class="block items-start text-start">
                            <h1
                                class="inline-block w-32 h-10 text-3xl lg:text-5xl text-gray-100 lg:text-gray-900 rounded-lg">
                                MYLogo</h1>
                        </a>
                        <div class="text-xs hidden lg:block my-2 items-start text-start">
                            <p>Last Updated: 08.20. Bangladesh Time. 23 June</p>
                        </div>
                    </div>
                </div>

                <!-- Search -->
                <div class="flex items-center justify-end flex-1 lg:hidden">
                    <div class="flex items-center ml-8">
                        <div class="flex items-center">
                            <span class="sm:block">
                                <NuxtLink href="/" class="border-transparent btn btn-success">
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

                <!-- AdSpaceLogo -->
                <div class="px-32 py-6 bg-gray-100 items-start justify-start hidden lg:block">
                    <p>adspace</p>
                </div>
            </div>
        </nav>
    </div>
</template>