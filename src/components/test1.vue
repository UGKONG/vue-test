<template>
  <h1>안녕하세요. 첫 번째 컴포넌트 입니다.</h1>
</template>

<script>
export default {
  data() {
    return {
      count: 0
    }
  },
  methods: {
    countUp() {
      this.count += 1;
    }
  }
}
</script>

<style>

</style>