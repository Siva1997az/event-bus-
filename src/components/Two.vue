<template>
    <div></div>
  </template>
  
  <script>
  
//   import EventBus from '../../src/eventBus/eventBus'
  export default {
    name: 'App',
    components: {
      
    },
    mounted() {
        this.emitter.emit('I-am-child',500)
    },
    created() {
        // this.emitter.emit('I-am-child',100)
    }
  }
  </script>
  
  <style>
  
  </style>
  