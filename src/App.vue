<template>
  <main>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>

    <img src="./assets/vuejs.svg" alt="Vue.js Logo" />
    <img src="./assets/tailwindcss.svg" alt="Tailwind CSS Logo" />
  </main>
  <router-view />
</template>

<style lang="scss">
main {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
