<template>
  <div class="grid grid-cols-2 gap-8">
    <p class="text-slate-500 w-full bg-orange-200 text-4xl p-4 text-center">
      {{ info }}
    </p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      info: "this is information about the page content",
    };
  },
};
</script>