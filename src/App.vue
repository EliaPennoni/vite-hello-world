<script>
import JumbotronApp from './components/JumbotronApp.vue';
export default {
  setup() {
    
    return {
      message:'Hello world'
    }
    
  },
  components: {
    JumbotronApp
  }
}
</script>

<template>
  <div>
    <h1>{{ message }}</h1>
    <jumbotronApp/>
    
  </div>
  
</template>

<style scoped>

</style>
