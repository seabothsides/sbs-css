<template>
  <nav class="flex flex-row justify-between">
    <p class="text-2xl font-sans font-bold capitalize">Pragmatik</p>
    <nuxtLink
      class="
        transition
        ease-in-out
        duration-200
        text-lg
        font-semibold
        capitalize
        hover:text-xl hover:text-blue-300
      "
      v-for="link in links"
      :to="{ name: link.link }"
      :key="link.id"
    >
      {{ link.name }}
    </nuxtLink>
  </nav>
</template>

<script>
export default {
  data() {
    return {
      links: [
        { link: "index", name: "home" },
        { link: "blog", name: "blog" },
        { link: "info", name: "about" },
        { link: "store", name: "store" },
      ],
    };
  },
};
</script>