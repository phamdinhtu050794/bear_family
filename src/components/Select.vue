<template>
  <div class="select-container">
       <a href="#" ><img src="@/assets/plumbing5.jpg"  ></a>
       <a href="#" > <img src="@/assets/heating.jpg"  ></a>
       <a href="#" > <img src="@/assets/contact.jpg"  ></a>
  </div>
</template>

<script>
export default {
  name: 'Select',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.select-container{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    background-color: black;
}

</style>
