<template>
  <div class="w-full min-h-screen py-8 px-4 bg-gray-950">

    <section class="max-w-screen-sm mx-auto">
      <div class="flex justify-between">
        <h1 class="text-gray-200 font-bold">Symmetry Engineering Firm.</h1>
        <Icon name="line-md:moon-alt-loop" style="color: gold; font-size: 24px;" />
      </div>
      <p class="mt-2 mx-2 text-gray-400 ">Active in an array of engineering fields including computer software and
        hardware, electrical and mechanical systems, with a strong emphasis on science and mathematics. To contact us,
        fill the <NuxtLink to="/form" class="border-b-2 border-white text-gray-300">form</NuxtLink> and we'll be in
        touch.</p>
    </section>



    <header class="max-w-screen-sm mx-auto mt-8 px-4 py-2 text-white flex justify-between bg-gray-800 rounded-full shadow-md">
      <div class="flex gap-4">
        <NuxtLink to="/" class="text-white hover:text-teal-400" active-class="text-teal-400 dark:text-teal-400">
          <Icon name="material-symbols:home-rounded" style="font-size: 24px;"/>
        </NuxtLink>
        <NuxtLink to="/projects" class="text-white hover:text-teal-400" active-class="text-teal-400 dark:text-teal-400">
          <Icon name="material-symbols:business-center" style="font-size: 24px;" />
        </NuxtLink>
        <NuxtLink to="/experiments" class="text-white hover:text-teal-400" active-class="text-teal-400 dark:text-teal-400">
          <Icon name="fluent-emoji-high-contrast:magic-wand" style="font-size: 24px;" />
        </NuxtLink>
        <NuxtLink to="/articles" class="text-white hover:text-teal-400" active-class="text-teal-400 dark:text-teal-400">
          <Icon name="material-symbols:article" style="font-size: 24px;" />
        </NuxtLink>
        <NuxtLink to="/bookmarks" class="text-white hover:text-teal-400" active-class="text-teal-400 dark:text-teal-400">
          <Icon name="material-symbols:bookmark-add" style="font-size: 24px;" />
        </NuxtLink>
      </div>
      <div>
        <NuxtLink to="/login" class="text-white hover:text-teal-400" active-class="text-teal-400 dark:text-teal-400">
          <Icon name="material-symbols:login" style="font-size: 24px;" />
        </NuxtLink>
      </div>
    </header>

    <main>
      <slot />
    </main>

  </div>
</template>