<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="flex flex-row">
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue " alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
  <div class="fixed bottom-10 right-4">
      <button class="learn-more add-btn">
        <span class="circle" aria-hidden="true">
        </span>
        <span class="button-text text-gray-700 dark:text-gray-100">Add Rule</span>
      </button>
    </div>
    <div class="fixed top-2 right-2 w-36 h-20">
      <div class="add-wrapper"><span>+</span><label for="">Add Rule</label></div>
    </div>
</template>

<style scoped lang="scss">
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
