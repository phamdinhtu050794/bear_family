<template>
  <div class="body-container">

      <SlideShow></SlideShow>
      <Cleaning></Cleaning>
      <Call></Call>
      <hr>
      <Service></Service>
      <hr>
      <Contact></Contact>
      <Select></Select>
  
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
</style>
