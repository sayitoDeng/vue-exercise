<template>
  <section id="real-app">
      <input 
        type="text"
        class="add-input"
        autofocus="autofocus"
        placeholder="TODO"
        @keyup.enter="addTodo"
      >
  </section>
</template>

<script>
export default {
  name: '',
  data () {
    return {
      
    };
  },
  methods: {
      addTodo(){

      }
  }
}
</script>

<style lang='stylus' scoped>
#real-app{
    width 600px
    margin 0 auto
    box-shadow 0 0 5px #666
}
.add-input{
    position relative
    margin 0
    width 100%
    font-size 24px
    font-weight inherit 
    font-family inherit 
    line-height 1.4em
    outline none 
    color inherit 
    padding 6px
    border 1px solid #999
    box-sizing border-box
    font-smoothing:antialiased
    padding 16px 16px 16px 60px
    box-shadow inset 0 -2px 1px rgba(0,0,0,0.4)

}
</style>