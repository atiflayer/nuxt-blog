<template>
    <div class="sticky inset-0 top-0 z-50 shadow-lg">
        <header>
            <!-- Navbar Logo -->
            <!-- <NavbarLogo /> -->

            <!-- OLD BACKUP -->
            <!-- Navbar Category -->
            <!-- <div class="lg:flex items-center justify-between w-full mx-auto h-11 hidden"> -->
            <!-- Tabs -->
            <!-- <nav class="w-full items-center justify-between space-x-6 text-sm font-medium bg-white lg:flex lg:flex-grow lg:w-0"> -->
            <!-- <ul class="flex text-center bg-white border-b border-gray-200">
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
                    </ul> -->
            <!-- </nav> -->

            <div class="lg:flex items-center justify-between w-full mx-auto h-11 hidden bg-white">
                <nav
                    class="w-full items-center justify-between space-x-6 text-sm font-medium bg-white lg:flex lg:flex-grow lg:w-0 mr-2">
                    <div class="nav nav-tabs bg-white " id="nav-tab" role="tablist">
                        <button class="nav-link active text-gray-600" id="nav-home-tab" data-bs-toggle="tab"
                            data-bs-target="#nav-home" type="button" role="tab" aria-controls="nav-home"
                            aria-selected="true">
                            Home
                        </button>
                        <button class="nav-link text-gray-600" id="nav-profile-tab" data-bs-toggle="tab"
                            data-bs-target="#nav-1" type="button" role="tab" aria-controls="nav-profile"
                            aria-selected="false">
                            Category 1
                        </button>
                        <button class="nav-link text-gray-600" id="nav-contact-tab" data-bs-toggle="tab"
                            data-bs-target="#nav-2" type="button" role="tab" aria-controls="nav-contact"
                            aria-selected="false">
                            Category 2
                        </button>
                        <button class="nav-link text-gray-600" id="nav-contact-tab" data-bs-toggle="tab"
                            data-bs-target="#nav-3" type="button" role="tab" aria-controls="nav-contact"
                            aria-selected="false">
                            Category 3
                        </button>
                        <button class="nav-link text-gray-600" id="nav-contact-tab" data-bs-toggle="tab"
                            data-bs-target="#nav-4" type="button" role="tab" aria-controls="nav-contact"
                            aria-selected="false">
                            Category 4
                        </button>
                        <button class="nav-link text-gray-600" id="nav-contact-tab" data-bs-toggle="tab"
                            data-bs-target="#nav-5" type="button" role="tab" aria-controls="nav-contact"
                            aria-selected="false">
                            Category 5
                        </button>
                    </div>

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

            <!-- NavbarSubCategory -->
            <div class="tab-content bg-white" id="nav-tabContent">
                <div class="tab-pane fade show active" id="nav-home" role="tabpanel" aria-labelledby="nav-home-tab">
                    <NavbarSubCategory />
                </div>
                <div class="tab-pane fade" id="nav-1" role="tabpanel" aria-labelledby="nav-profile-tab">
                    <NavbarSubCategory />
                </div>
                <div class="tab-pane fade" id="nav-2" role="tabpanel" aria-labelledby="nav-contact-tab">
                    <NavbarSubCategory />
                </div>
                <div class="tab-pane fade" id="nav-3" role="tabpanel" aria-labelledby="nav-contact-tab">
                    <NavbarSubCategory />
                </div>
                <div class="tab-pane fade" id="nav-4" role="tabpanel" aria-labelledby="nav-contact-tab">
                    <NavbarSubCategory />
                </div>
                <div class="tab-pane fade" id="nav-5" role="tabpanel" aria-labelledby="nav-contact-tab">
                    <NavbarSubCategory />
                </div>
            </div>
        </header>
    </div>
</template>