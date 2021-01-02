<template>
   <div class="slideshow-container">
    
        
    <img src="@/assets/img1.jpg">
    <br>

    <!-- <img :src='require(`../assets/${img2}`)' > -->
    
   </div>
  
  
</template>

<script>

export default {
  name: 'SlideShow',
  components:{
      
  },
  data: function() {
      return{
      img1:"@/assets/plumping1.jpg",
      img2: 'plumbing.jpg'
      }
  },
   
  
  props: {
    msg: String
  }
}
</script>



<style lang="scss" scoped>

</style>
