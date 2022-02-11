<template>
  <nav class="flex flex-row justify-between">
    <p class="text-2xl font-sans font-bold capitalize">
      <nuxt-link to="/"> Pragmatik </nuxt-link>
    </p>
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
        { link: "navs", name: "navs" },
        { link: "heroes", name: "heroes" },
        { link: "cards", name: "cards" },
      ],
    };
  },
};
</script>