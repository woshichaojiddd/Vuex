<template>
  <div>
    <h5>当前count最新值: {{count}}</h5>
    <button>-1</button>
  </div>
</template>

<script>
import { mapState } from 'vuex'
export default {

  data () {
    return {
    }
  },

  methods: {},

  created () {
      
  },
  computed: {
      ...mapState(['count'])
  }

}
</script>

<style lang='less' scoped>

</style>
