<template>
    <div>
        <h1>{{busval}}</h1>
    </div>
</template>
  
  <script>
  
//   import EventBus from '../../src/eventBus/eventBus'
  export default {
    name: 'App',
    components: {
      
    },
    data() {
        return {
            busval:''
        }
    },
    created() {
       this.emitter.on('I-am-child',(val)=>{
       console.log(val)
       this.busval=val
     })
    },
    mounted() {
    //    this.emitter.on('I-am-child',(val)=>{
    //    console.log(val)
    //    this.busval=val
    //  })
    }
  }
  </script>
  
  <style>
  
  </style>
  