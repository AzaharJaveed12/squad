<template>
  <div>
    <app-header/>
    <app-family/>
    <app-footers/>
  </div>
</template>




<script>
import Header from './components/Header.vue';
import Footeres from './components/footers.vue';
import family from './components/family.vue';
 export default {
  components:{
    'app-header':Header,
    'app-footers':Footeres,
    'app-family':family
  },
  data(){
    return {
     
}
}
}
</script>

<style >


</style>
