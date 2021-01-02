<template>
  <div class="header-container">
    <div class="title">
      <h1>Bears Family</h1>
      <h3>Plumping, Heating, and Cooling</h3>
    </div>
    <div class="ui">
      <div class="dropdown">
        <h3><a href="#">Home | </a></h3> 
      </div>
      <div class="dropdown">
        <h3><a href="#">Plumping Service & Repair |</a></h3>
        <ul class="dropdown-content">
          <li><a href="#">Residentials</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <h3><a href="#">HVAC Service & Repair | </a></h3>
      </div>
      <div class="dropdown">
        <h3><a href="#"> About Us |</a></h3>
        <ul class="dropdown-content">
          <li><a href="#">Our Company Bio</a></li>
          <li><a href="#">Our Testimonials</a></li>
          <li><a href="#">Our News</a></li>
        </ul>
      </div>
      <div class="dropdown">
        <h3><a href="#">Contact Us</a></h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.header-container {
  display: flex;
  flex-direction: column;
  justify-content: center;
}


.title h1, h3{
  color: rgb(230, 226, 23);
  
}
.title h1{
  font-family: cursive;
  text-shadow: 4px 4px 6px rgb(230, 226, 23);
}
.ui {
  display: flex;
  flex-direction: row;
  justify-content: center;
  height: 40px;
   background: linear-gradient(yellow, rgb(153, 148, 148) 80%);
}
.ui h3 {
  border: 2px;
  border-radius: 0px;
  
  // padding: 10px;
  margin: 10px;
  
  
}

.dropdown {
  position: relative;
  display: inline-block;
}



.dropdown-content {
  display: none;
  position: absolute;
  background-color: rgb(184, 177, 177);
  //   min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  padding: 12px 16px;
  z-index: 1;
  width: 150px;
  height: auto;
  top: 50%;
  border-radius: 0px;
}

.dropdown:hover .dropdown-content {
  display: block;
}
a {
  font-size: 16px;
  color: black;
  //    color: #FFFFFF;
  text-decoration: none;
}
.more {
  display: flex;
  justify-content: center;
  align-items: center;
  border: 2px;
  border-radius: 25px;
  padding: 10px;
  background-color: red;
  width: 100px;
  height: 30px;
  margin-bottom: 10px;
}
.dropdown-content li {
  text-align: left;
}
</style>
html {
  height: 100%;
}
body {
  overflow: hidden;
  margin: 0;
  padding: 0;
  background: rgba(206,188,155,1);
  background: -moz-linear-gradient(-45deg, rgba(206,188,155,1) 0%, rgba(85,63,50,1) 51%, rgba(42,31,25,1) 100%);
  background: -webkit-gradient(left top, right bottom, color-stop(0%, rgba(206,188,155,1)), color-stop(51%, rgba(85,63,50,1)), color-stop(100%, rgba(42,31,25,1)));
  background: -webkit-linear-gradient(-45deg, rgba(206,188,155,1) 0%, rgba(85,63,50,1) 51%, rgba(42,31,25,1) 100%);
  background: -o-linear-gradient(-45deg, rgba(206,188,155,1) 0%, rgba(85,63,50,1) 51%, rgba(42,31,25,1) 100%);
  background: -ms-linear-gradient(-45deg, rgba(206,188,155,1) 0%, rgba(85,63,50,1) 51%, rgba(42,31,25,1) 100%);
  background: linear-gradient(135deg, rgba(206,188,155,1) 0%, rgba(85,63,50,1) 51%, rgba(42,31,25,1) 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#cebc9b', endColorstr='#2a1f19', GradientType=1 );
}
h1 {
  width: 100%;
  margin: 0 auto 0 auto;
  font-family: 'Lato', sans-serif;
  line-height: 280px;
  font-size: 10rem;
  padding: 80px 50px;
  text-align: center;
  text-rendering: optimizeLegibility;
}
h1::before {
  content:"";
  width: 100%;
  height: 750px;
  position: absolute;
  top: -200px;
  left: 10px;
  transform: rotate(55deg);
  background: rgba(206,188,155,.7);
  background: -moz-linear-gradient(left, rgba(206,188,155,.7) 0%, rgba(42,31,25,0) 65%);
  background: -webkit-gradient(left top, right top, color-stop(0%, rgba(206,188,155,.7)), color-stop(65%, rgba(42,31,25,0)));
  background: -webkit-linear-gradient(left, rgba(206,188,155,.7) 0%, rgba(42,31,25,0) 65%);
  background: -o-linear-gradient(left, rgba(206,188,155,.7) 0%, rgba(42,31,25,0) 65%);
  background: -ms-linear-gradient(left, rgba(206,188,155,.7) 0%, rgba(42,31,25,0) 65%);
  background: linear-gradient(to right, rgba(206,188,155,.7) 0%, rgba(42,31,25,0) 65%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#cebc9b', endColorstr='#2a1f19', GradientType=0.7 ); );
}
#text3d {
    color: #70869d;
    text-shadow:
      -1px -1px 1px #efede3,
      0px 1px 0 #2e2e2e,
      0px 2px 0 #2c2c2c,
      0px 3px 0 #2a2a2a,
      0px 4px 0 #282828,
      0px 5px 0 #262626,
      0px 6px 0 #242424,
      0px 7px 0 #222,
      0px 8px 0 #202020,
      0px 9px 0 #1e1e1e,
      0px 10px 0 #1c1c1c,
      0px 11px 0 #1a1a1a,
      0px 12px 0 #181818,
      0px 13px 0 #161616,
      0px 14px 0 #141414,
      0px 15px 0 #121212,
      2px 20px 5px rgba(0, 0, 0, 0.9),
      5px 23px 5px rgba(0, 0, 0, 0.3),
      8px 27px 8px rgba(0, 0, 0, 0.5),
      8px 28px 35px rgba(0, 0, 0, 0.9);

 }