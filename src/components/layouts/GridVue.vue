<template>

  <div :class="'col s' + tamanho">
    <slot></slot>
  </div>


</template>

<script>
export default {
  name: 'GridVue',
  props:['tamanho'],
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
