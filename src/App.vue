<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <hr />
  <h1>카운트 {{ count }}</h1>
  <button @click="btnClick"></button>
  <Test />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import Test from './components/test1.vue';

export default {
  name: 'App',
  data() {
    return{
      count: 0,
    }
  },
  components: {
    HelloWorld,
    Test
  },
  methods: {
    btnClick() {
      this.count += 1;
    }
  }
}
</script>

<style scoped>

</style>