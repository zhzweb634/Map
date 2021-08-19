<template>
  <div id="app">
  <Map :provinces="a" end="北京"></Map>
  </div>
</template>

<script>
import Map from './components/Map'
export default {
  name: 'App',
  components: {
    Map
  },
  data(){
    return{
      a: [
        { 'name': '北京', 'value': 6 },
        { 'name': '湖南', 'value': 3 },
        { 'name': '广东', 'value': 2 },
        { 'name': '山西', 'value': 2 },
        { 'name': '上海', 'value': 1 },
        { 'name': '重庆', 'value': 1 },
        { 'name': '河北', 'value': 1 },
        { 'name': '陕西', 'value': 1 },
        { 'name': '山东', 'value': 0 },
        { 'name': '黑龙江', 'value': 0 },
        { 'name': '贵州', 'value': 0 }
      ]

    }
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
