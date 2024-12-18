<template>
  <CardComp></CardComp>
  <CardComp>Card content</CardComp>
  <CardComp>
    <h2>Card content</h2>
  </CardComp>
  <CardComp>
    <img src="https://picsum.photos/200">
  </CardComp>
</template>

<script>
import CardComp from './components/CardComp.vue';


export default {
  name: 'App',
  components: {
    CardComp
  },
  data() {
    return {
      name: ''
    }
  },
  methods: {}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
