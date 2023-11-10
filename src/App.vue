<template>
  <HelloWorld />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
};
</script>

<style>
body,
html {
  margin: 0;
  padding: 0;
}

body {
  background-color: black;
}

main {
  background-color: transparent;
  width: 100%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
</style>
