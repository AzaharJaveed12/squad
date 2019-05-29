<template>
<footer>
    <p>
        {{copyRight}}
    </p>
</footer>
</template>


<script>
export default{
    data:function(){
        return{
            copyRight:"©copyRight 2019"
        }
    }
}
</script>


<style scoped>
footer{
    background-color:#222;
    padding:6px;
}
  p{
      color:lightgreen;
      text-align: center;
  }
</style>
