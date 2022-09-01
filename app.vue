<template>
  <div>
    <Announcement />
    <div class="flex">
      <div class="flex-1 w-64 bg-white">
        <div class="flex lg:flex-row">

          <!-- Aside Left-->
          <div class="flex-initial hidden h-full px-2 py-2 bg-white md:px-2 w-96 2xl:block">
            <AdspaceAside />
            <AdspaceAside />
            <AdspaceAside />
          </div>

          <!-- Body -->
          <div class="flex-1 w-full h-full bg-white md:px-4">
            <NavbarLogo />
            <Navbar />
            <AdspaceBody />
            <NuxtPage />
          </div>

          <!-- Aside Right -->
          <div class="flex-initial hidden h-full px-2 py-2 bg-white md:px-2 w-96 2xl:block">
            <AdspaceAside />
            <AdspaceAside />
            <AdspaceAside />
          </div>

        </div>
      </div>
    </div>
  </div>
</template>
