<template>
  <div>
    <two-tag></two-tag>
    <five-tag></five-tag>
  </div>
</template>

<script>
import Two from './components/Two.vue'
import Five from './components/Five.vue'
export default {
  name: 'App',
  components: {
    'two-tag':Two,
    'five-tag':Five
  },
  created() {
     
  },
  mounted() {

  }
}
</script>

<style>

</style>
