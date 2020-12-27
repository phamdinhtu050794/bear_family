<template>
  <div class="select-container">
        <img src="@/assets/select1.jpg" width="300" height="300" >
        <img src="@/assets/select2.png" width="300" height="300" >
        <img src="@/assets/select3.jpg" width="300" height="300" >
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
