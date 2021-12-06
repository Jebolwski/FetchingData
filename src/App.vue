<template>
  <div>
    <Entrance/>
     <router-view/>
  </div>
 
</template>
<script>
import Entrance from "./views/Entrance.vue"
   export default{
    name:"App",
    components:{
      Entrance
    }
}
</script>
<style>

</style>
