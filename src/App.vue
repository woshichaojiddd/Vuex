<template>
  <div>
    <my-add></my-add>
    <p>-----------------------------</p>
    <my-sub></my-sub>
  </div>
</template>

<script>
// 引入子组件
import Add from './components/add.vue'
import Sub from './components/sub.vue'

export default {

  data () {
    return {
    }
  },

  methods: {},

  created () {
  },

  components: {
    'my-add': Add,
    'my-sub': Sub
  }
}
</script>

<style lang='less' scoped>

</style>
