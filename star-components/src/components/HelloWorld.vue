<template>
 <div>
   <star :size='48' :score='4.5'></star>
 </div>
</template>

<script>
import Star from './star'
 export default {
   data () {
     return {

     }
   },
   components: {
    Star,
   }
 }
</script>

<style lang='scss' scoped>

 
</style>
