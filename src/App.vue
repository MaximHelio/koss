<template>
  <MySpend></MySpend>
</template>
<script>
import MySpend from './pages/Spend/MySpend.vue'

export default {
  name: 'App',
  components: {
    MySpend: MySpend,
  }
}
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
