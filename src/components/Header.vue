<template>
  <div class="header-container">
      <div class="title"> 
          <h1>Bears Family</h1>
          <h3>Plumping, Heating, and Cooling</h3>
      </div>
      <div class="ui">
          <pre><h3> Home | </h3></pre> 
          <pre><h3> Plumping Service & Repair | </h3></pre> 
          <pre><h3> HVAC Service & Repair | </h3></pre> 
          <pre><h3> About Us | </h3></pre> 
          <pre><h3> Contact Us  </h3></pre>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header-container{
    display: flex;
    flex-direction: column;
    justify-content: center;

}
.ui{
    display: flex;
    flex-direction: row;
    justify-content: center;
    background-color: yellow;
}

// .ui h3{
//     font: 10px;
// }

</style>
