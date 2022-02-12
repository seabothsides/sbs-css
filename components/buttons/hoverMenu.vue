<template>
  <div>
    <div class="group bg-red-300 flex flex-row space-x-2 h-6 w-8">
      <div id="trigger">trigger</div>
      <div class="opacity-0 z-30 group-hover:opacity-100 duration-200">
        <ul>
          <li>links</li>
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
#trigger:hover + #result {
  display: block;
}
</style>