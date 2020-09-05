<template>
  <div id="app">
    <Header />
    <Todo />
    <Footer />
  </div>
</template>

<script>
import Header from './layout/header.vue'
import Footer from './layout/footer.jsx'
import Todo from './components/todo.vue'
export default {
  name: 'App',
  components: {
    Header,
    Footer,
    Todo
  }
}
</script>

<style lang="stylus" scoped>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: #2c3e50;
  position: absolute;
  top: 0;
  left 0;
  right 0;
  bottom 0;
}
</style>
