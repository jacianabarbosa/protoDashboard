<template>
  <div id="app">
    <appDashboardSetup :selectedLayout="selectedLayout" @setSelectedLayout="changeSelectedLayout"></appDashboardSetup>
  </div>
</template>

<script>
  import DashboardSetup from './components/dashboardSetup.vue';
  export default {
    name: 'app',
    data() {
      return {
        selectedLayout: -1
      }
    },
    components: {
      appDashboardSetup: DashboardSetup
    },
    methods: {
      changeSelectedLayout(pos) {
        this.selectedLayout = pos;
      }
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
