<template>
  <div class="capitalize">
    <nav class="flex flex-row justify-between bg-gray-200 px-6 py-2 rounded-xl">
      <div class="flex flex-row space-x-4 font-semibold items-center">
        <a href="#">links</a>
        <a href="#">about</a>
      </div>
      <div>
        <nuxt-link class="text-2xl font-bold" to="#"> Brand Logo </nuxt-link>
      </div>
      <div class="flex flex-row space-x-4 font-semibold items-center">
        <a href="#">shop</a>
        <a href="#">services</a>
      </div>
    </nav>
  </div>
</template>