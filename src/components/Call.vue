<template>
  <div class="call-container">
    <div class="phone">
      <h1>Northern Colorado:</h1>
      <h1 id="number">970-901-5987</h1>
      <h1 id="space">-------</h1>
      <h1>Greater Denver Area:</h1>
      <h1 id="number">303-515-1526</h1>
    </div>
    <br />

    <div class="call-now">
      Call now, Same Day Service Available ( in most cases )
    </div>
    <br />
    <br />
  </div>
</template>

<script>
export default {
  name: "Call",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.call-container {
  background-color: black;
}
.phone {
  display: flex;
  flex-direction: row;
  justify-content: center;
  color: yellow;
}

#number {
  color: white;
}
.call-now {
  color: white;
  font-size: 20px;
}
#space{
  color: black;
}
</style>
