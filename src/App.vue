<script setup>
import HelloWorld from './components/HelloWorld.vue';
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <div class="wrap">
    <div>ヘッダー</div>
    <main class="main">メイン</main>
    <div>フッター</div>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style>
.wrap {
  display: flex;
  flex-direction: column;
  align-items:center;
  min-height: 100vh;
  width: 370px;
  margin: 0 auto;
  font-family: sans-serif;
}

.main {
  flex:1;
  width: 100%;
}
</style>
