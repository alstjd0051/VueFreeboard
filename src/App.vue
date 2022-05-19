<template>
  <h1 @click="increase" >
    {{count}}
  </h1>
</template>

<script>
export default{
data() {
  return {
    count: 0
  }
},
  methods: {
    // app.vue안에 있는 script를 지칭하는 this
    increase() {
      this.count += 1
    }
  },
}
</script>

<style>
h1{
  font-size: 50px;
  color: royalblue;
  font-weight: 500;
}
</style>