<template>
  <div>
 <SummaryResult/>
</div>
</template>

<script>

import SummaryResult from './components/SummaryResult.vue';
export default {
  // eslint-disable-next-line
  name: 'App',
  components: {
    SummaryResult
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
  margin-top: 60px;
}
</style>
