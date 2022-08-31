<template>
    <div class="w-full">
        <div class="m-2">
            <h1 class="text-xl font-bold">Article 1. Lorem ipsum, dolor sit amet consectetur
                adipisicing elit. Reprehenderit voluptatibus consequatur quidem necessitatibus natus vel adipisci
                placeat, culpa ullam quibusdam praesentium ad accusantium velit libero aliquid. Facere officiis
                molestias ad!</h1>
        </div>
        <!-- For Single Page -->
        <!-- <div class="flex flex-col py-2 text-sm border-t border-b border-sky-700">
            <div>
                <p>By <span class="uppercase text-sky-500">John Doe</span> and <span class="uppercase text-sky-500">Mary
                        Jane</span> for <span class="uppercase text-sky-500">MyCompany</span></p>
            </div>
            <div>
                <p><span class="font-bold uppercase">Published</span>: 07:43 BST, 22 August 2022 | <span
                        class="font-bold uppercase">Updated</span>: 11:44 BST,
                    12 July
                    2022</p>
            </div>
        </div> -->
        <img src="https://api.lorem.space/image/album?w=600&h=300&hash=3u1cyqkv" alt=""
            class="object-cover w-full h-64 my-2 lg:h-full">
        <div class="m-2">
            <h6 class="text-sm">Article 1. Lorem ipsum, dolor sit amet consectetur
                adipisicing elit. Reprehenderit voluptatibus consequatur quidem necessitatibus natus vel adipisci
                placeat, culpa ullam quibusdam praesentium ad accusantium velit libero aliquid. Facere officiis
                molestias ad!</h6>
        </div>


        <div class="flex items-center justify-between space-x-4 lg:space-x-10">
            <div class="flex mx-2 space-x-1 lg:w-0 lg:flex-1">
                <span class="w-8 h-8 bg-sky-700"></span>
                <span class="w-8 h-8 bg-blue-500"></span>
                <span class="w-8 h-8 bg-green-500"></span>
                <span class="w-8 h-8 bg-red-500"></span>
                <span class="w-8 h-8 bg-cyan-500"></span>
            </div>

            <div class="flex flex-col items-center mx-2 font-bold lg:hidden">
                <h1>999</h1>
                <h1 class="text-xs">Shares</h1>
            </div>
        </div>
        <div>
            <button class="w-full p-2 px-32 m-2 text-sm font-medium bg-gray-200 border border-gray-400 rounded-sm"
                type="button">
                999 Comments
            </button>
        </div>
    </div>
</template>