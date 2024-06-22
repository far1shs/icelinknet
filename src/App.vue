<template>
  <div>
    <a href="/" target="_blank">
      <img src="/logo.png" class="logo" />
    </a>
    <a href="https://hayfrp.org" target="_blank">
      <img src="/hayfrp.png" class="logo hay" />
    </a>
  </div>
  <h2>Ice Link Net 前 HayFrp</h2>

  <button type="button" @click="win.open('https://hayfrp.rivfox.com')">控制台</button> <button type="button" @click="win.open('https://hayfrp.org')">HayFrp</button>
</template>

<script setup lang="ts">
const win = window;
</script>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #B0C4DE);
}
.logo.hay:hover {
  filter: drop-shadow(0 0 2em	#FA8072);
}
</style>
