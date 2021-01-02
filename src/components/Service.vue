<template>
  <div class="service-container">
    <div class="up">
      <h2>
        Bears Family Plumbing, Heating, and Cooling is your go to plumbing,
        heating, and cooling service for the <a href="#" >Denver</a>, <a href="#">Loveland</a>, <a href="#">Northern Colorado</a>
        area. With 15 plus years experience in plumbing, heating, and cooling
        repairs we work diligently to establish our company as your trusted
        partner to help you with these needs.
      </h2>
    </div>
    <br>
    <br>
    <br>
    <div class="down">
      <div>
        <ul>
          <h3>Here’s Some Of The Plumbing Services We Provide:</h3>
          
          <link
            rel="stylesheet"
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
          />

          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i
            >RESIDENTIAL
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> LINE
            REPAIR / REPLACEMENT
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            DRAIN LINE REPAIR / REPLACEMENT
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            REPLACE OR REPAIR WATER HEATERS
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            TANKLESS WATER HEATERS
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> FIX
            WATER PRESSURE ISSUES
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> FIX
            LEAKING PIPES
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            FAUCET REPAIR & REPLACEMENT
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            DRAIN CLEANING
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> BATH
            & KITCHEN REMODELS
          </li>
        </ul>
      </div>
      <div>
        <ul>
          <h3>Here’s Some Of The Heating and Cooling Services We Provide:</h3>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            RESIDENTIAL
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            FURNACE INSTALLATION, MAINTENANCE, & REPAIR
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> AIR
            CONDITIONING INSTALLATION, MAINTENANCE, & REPAIR
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            REMODELING AS NECESSARY FOR INSTALLATION AND SERVICE
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            BOILER MAINTENANCE & REPAIR
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            HEATING MAINTENANCE AGREEMENTS
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> AIR
            CONDITIONING MAINTENANCE AGREEMENTS
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i> AIR
            CONDITIONING UNIT SALES
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            HEATING UNIT SALES
          </li>
          <li>
            <i class="fa fa-share" style="font-size: 15px; color: red"></i>
            PARTS AND LABOR WARRANTIES
          </li>
        </ul>
      </div>
    </div>
    <div class="icon">
      <link
        rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"
      />

      <!-- Add font awesome icons -->
      <a href="#"><img src="@/assets/ggg.png" width="100" height="100" alt=""></a>
      <a href="#"><img src="@/assets/fb.png" width="100" height="100" alt=""></a>
      <a href="#"><img src="@/assets/iconbss.png" alt=""></a>
      <a href="#"><img src="@/assets/yelp.png" width="70" height="70" alt=""></a>
    </div>
  </div>
</template>

<script >
export default {
  name: "Service",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.service-container {
  background-color: black;
}
.down {
  color: white;
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.up {
  color: yellow;
  display: flex;
  justify-content: center;
}
li {
  text-align: start;
}
.icon {
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
}
.fa {
  padding: 20px;
  font-size: 30px;
  width: 50px;
  text-align: center;
  text-decoration: none;
}

/* Add a hover effect if you want */
.fa:hover {
  opacity: 0.7;
}

/* Set a specific color for each brand */

/* Facebook */
.fa-facebook {
  background: #3b5998;
  color: white;
}

/* Twitter */
.fa-google {
  background: #55acee;
  color: white;
}
.fa-yelp {
  background-color: red;
  color: white;
}
ul {
  list-style: none;
  line-height: 0%;
  
}
.up a{
  color: blue;
  //    color: #FFFFFF;
  text-decoration: none;
}
.up a:hover{
  color: red;
}
</style>
