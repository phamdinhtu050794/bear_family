<template>
   <div class="contact-container">
        <div>
            <h3>We Are Your Go To Denver, Loveland, Northern Colorado Plumbing, Heating, and Cooling / HVAC Service</h3>
            <h2>Family Owned & Operated</h2>
            <h4>WE GUARANTEE OUR WORKMANSHIP & MATERIALS  <br>  LICENSED AND INSURED</h4>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Contact',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.contact-container{
  background-color: black;
}

h3, h4  {
  color: white;
}
h2{
  color: yellow;
}


</style>
