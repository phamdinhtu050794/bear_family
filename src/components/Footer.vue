<template>
  <div class="footer-container">
      <div class="ui-footer">
           <pre><h5> Home | </h5></pre> 
           <pre><h5> General Plumbing | </h5></pre> 
           <pre><h5> Residential Plumbing | </h5></pre> 
          <pre><h5> HVAC | </h5></pre> 
          <pre><h5> About Us | </h5></pre> 
          <pre><h5> Our News | </h5></pre> 
          <pre><h5> Our Testimonials | </h5></pre> 
          <pre><h5> Contact Us  </h5></pre>
      </div>
      <div>
          <h5>Copyright Bears Family P.H.C. © 2016. All Rights Reserved.</h5>
      </div>
      <div>
          <h5>Designed by Jsay Designs, LLC.</h5>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.footer-container{
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-color: yellow;
}
.ui-footer{
    display: flex;
    flex-direction: row;
    justify-content: center;
}

</style>
