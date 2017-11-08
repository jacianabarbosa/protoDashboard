<template>
  <div id="app">
    <appDashboardSetup></appDashboardSetup>
  </div>
</template>

<script>
  import DashboardSetup from './components/dashboardSetup.vue';
  export default {
    name: 'app',
    components: {
      appDashboardSetup: DashboardSetup
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
