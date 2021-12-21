<template>
  <div
    class="font-mono text-center container mx-auto my-32 lg:my-48 xl:my-50 2xl:my-96"
  >
    <h1 class="text-4xl">Just another site built with</h1>
    <div class="text-2xl mt-3">
      <a href="https://tailwindcss.com" target="_blank" class="text-blue-500">
        <img
          src="../assets/tailwindcss.svg"
          alt="Tailwind CSS"
          title="Tailwind CSS"
          class="w-10 inline ml-3"
        />
      </a>
      &
      <a href="https://v3.vuejs.org" target="_blank" class="text-green-500">
        <img
          src="../assets/vuejs.svg"
          alt="Vue 3"
          title="Vue 3"
          class="w-9 inline"
      /></a>
    </div>

    <router-link
      class="mt-5 inline-block text-white bg-blue-500 px-4 py-4 rounded-full hover:bg-blue-400 transition"
      to="/demo"
    >
      View the demo
    </router-link>
  </div>
</template>

<script>
export default {
  name: "HomeView",
  title: "Homepage",
};
</script>
