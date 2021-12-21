<template>
  <div class="container mx-auto font-mono">
    <h1 class="text-3xl mb-3 xl:text-left text-center">Search for images</h1>
    <div class="lg:grid lg:grid-cols-2">
      <label>
        <input
          type="text"
          placeholder="Enter your search term"
          class="w-full p-6 border border-blue-500 rounded-tr-2xl outline-none rounded-bl-2xl placeholder:text-xl text-xl"
          id="image-search"
        />
      </label>
      <button
        class="w-full mt-3 lg:mt-0 lg:ml-5 p-6 border border-blue-500 hover:bg-blue-500 hover:text-white transition-all text-xl text-blue-500"
      >
        Submit
      </button>
    </div>
  </div>
</template>

<script>
export default {
  title: "Demo site",
};
</script>
