<template>
  <div class="body-container">
    <div class="body-center">
      <SlideShow></SlideShow>
      <Cleaning></Cleaning>
      <Call></Call>
      <hr>
      <Service></Service>
      <hr>
      <Contact></Contact>
      <Select></Select>
      </div>
  
  </div>
</template>

<script>
import SlideShow from '@/components/SlideShow.vue'
import Cleaning from '@/components/Cleaning.vue'
import Call from '@/components/Call.vue'
import Service from '@/components/Service.vue'
import Contact from '@/components/Contact.vue'
import Select from '@/components/Select.vue'

export default {
  name: "Body",
  components:{
      SlideShow,
      Cleaning,
      Call,
      Service,
      Contact,
      Select
  },
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

hr{
    color: white;
}

.body-center{
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 80%;
  padding: 10%;
  padding-top: 0%;
  padding-bottom: 0%;
}
hr{
  
  width: 100%;
}
</style>
