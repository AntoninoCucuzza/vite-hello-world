<script >
import AppTitle from './/components/AppTitle.vue';
import Jumbotron from './components/jumbotron.vue';

export default {
  data() {
    return {
      message: 'hello Vite and Vue3!',
    }
  },
  components: {
    AppTitle,
    Jumbotron
  }
}
</script>

<template>
  <AppTitle />
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <h1>{{ message }}</h1>

  <Jumbotron />
</template>

<style >
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
