<template>
   <div class="call-container">
      <div class="phone">
        <h2>Northern Colorado: 970-901-5987 - - - - Greater Denver Area:
        303-515-1526</h2>
      </div>
      <div class="call-now">Call now, Same Day Service Available ( in most cases )</div>
    </div>
</template>

<script>
export default {
  name: 'Call',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.call-container{
    background-color: black;
}
.phone{
    color: yellow;
}
.call-now{
    color: white;
}


</style>
