<template>
  <div id="app">
  <student/>
  <School/>
  </div>
</template>

<script>
import student from './components/student.vue'
import School from './components/School.vue'
export default {
  name: 'App',
  components: {
  student,
  School
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
