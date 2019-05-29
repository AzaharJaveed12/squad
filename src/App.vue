<template>
  <div>
    <app-header/>
    <app-family/>
    <app-footers/>
  </div>
</template>




<script>
import Header from __dirname+'/components/Header.vue';
import Footeres from __dirname+'/components/footers.vue';
import family from __dirname+'/components/family.vue';
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
