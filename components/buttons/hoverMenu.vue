<template>
  <div>
    <div id="trigger" class="bg-red-300 flex inline-block space-x-2 h-6 w-min">
      <div>trigger</div>
      <div
        id="result"
        class="opacity z-30 group-hover:opacity-100 duration-200"
      >
        <ul>
          <li class="hover:bg-gray-300">links</li>
          <li>links</li>
          <li>links</li>
          <li>links</li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
#result {
  display: none;
}
#trigger:hover #result {
  display: block;
}
</style>