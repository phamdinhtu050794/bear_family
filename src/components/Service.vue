<template>
  <div class="service-container">
      <div class="up">
       <h3> Bears Family Plumbing, Heating, and Cooling is your go to plumbing,
        heating, and cooling service for the Denver, Loveland, Northern Colorado
        area. With 15 plus years experience in plumbing, heating, and cooling
        repairs we work diligently to establish our company as your trusted
        partner to help you with these needs.</h3>
      </div>
      <div class="down">
      <div>
        <ul>
          <h4>Here’s Some Of The Plumbing Services We Provide:</h4>
          
            <li>RESIDENTIAL</li>
            <li> LINE REPAIR / REPLACEMENT </li>
            <li>DRAIN LINE REPAIR / REPLACEMENT </li>
           <li> REPLACE OR REPAIR WATER HEATERS </li>
           <li> TANKLESS WATER HEATERS </li>
           <li> FIX WATER PRESSURE ISSUES </li>
           <li> FIX LEAKING PIPES </li>
           <li> FAUCET REPAIR &  REPLACEMENT </li> 
           <li> DRAIN CLEANING </li>
          <li>  BATH & KITCHEN REMODELS </li>
          
        </ul>
      </div>
      <div>
          <ul>
              <h4>Here’s Some Of The Heating and Cooling Services We Provide:</h4>
              <li>RESIDENTIAL</li>
              <li>FURNACE INSTALLATION, MAINTENANCE, & REPAIR</li>
              <li>AIR CONDITIONING INSTALLATION, MAINTENANCE, & REPAIR</li>
              <li>REMODELING AS NECESSARY FOR INSTALLATION AND SERVICE</li>
              <li>BOILER MAINTENANCE & REPAIR</li>
              <li>HEATING MAINTENANCE AGREEMENTS</li>
              <li>AIR CONDITIONING MAINTENANCE AGREEMENTS</li>
              <li>AIR CONDITIONING UNIT SALES</li>
              <li>HEATING UNIT SALES</li>
              <li>PARTS AND LABOR WARRANTIES</li>
          </ul>
      </div>
      </div>
      <div>
          <div> <i class="fab fa-facebook-square"></i></div>
          <div><i class="fab fa-google-plus-square"></i></div>
           <div></div>
          <div><i class="fab fa-yelp"></i></div>
      </div>
    </div>
</template>

<script>
export default {
  name: 'Service',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.service-container{
    background-color: black;
}
.down{
    color: white;
    display: flex;
    flex-direction: row;
    justify-content: center;
}
.up{
    color: yellow;
    display: flex;
    justify-content: center;
}
li{
    text-align: start;
}

</style>
