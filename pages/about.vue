<template>
  <div>
    <div class="container h-[50vh] flex items-center justify-center">
      <h1 class="text-center lg:text-2xl">Hello, this is the about page.</h1>
    </div>
    <div class="container h-[50vh] flex items-center justify-center">
      <NuxtLink
        class="px-8 py-1.5 font-body font-semibold transition-colors bg-indigo-500 rounded-full shadow-md text-gray-50 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-400 focus:ring-opacity-75"
        :to="{ path: '/', hash: '#contact' }"
        >Contact</NuxtLink
      >
    </div>
    <div class="container h-[50vh] flex items-center justify-center">
      <NuxtLink
        class="px-8 py-1.5 font-body font-semibold transition-colors bg-indigo-500 rounded-full shadow-md text-gray-50 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-400 focus:ring-opacity-75"
        :to="{ path: '/', hash: '#contact' }"
        >Contact</NuxtLink
      >
    </div>
    <div class="container h-[50vh] flex items-center justify-center">
      <NuxtLink
        class="px-8 py-1.5 font-body font-semibold transition-colors bg-indigo-500 rounded-full shadow-md text-gray-50 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-indigo-400 focus:ring-opacity-75"
        :to="{ path: '/', hash: '#contact' }"
        >Contact</NuxtLink
      >
    </div>
  </div>
</template>