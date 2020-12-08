<template>
  <div>
    <h4>当前最新count值为：{{count}}</h4>
    <button>-</button>
  </div>
</template>

<script>
import { mapState } from 'vuex'

export default {
  computed: {
    ...mapState(['count'])
  }
}
</script>

<style>

</style>
