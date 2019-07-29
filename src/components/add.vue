<template>
  <div>
    <h5>当前count最新值: {{$store.state.count}}</h5>
    <button>+1</button>
  </div>
</template>

<script>
export default {

  data () {
    return {
    }
  },

  methods: {},

  created () {
    // 获取stroe.js中的值
    console.log(this.$store.state.count);
    
  }
}
</script>

<style lang='less' scoped>

</style>
