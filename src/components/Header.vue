<template>
  <header class="header-container">
    
    <div class="img"></div>
    <div class="title-txt">
        <h1>Welcome to Acme Web Solutions</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci eum error earum soluta voluptatum nisi
          laboriosam eos saepe asperiores dolorum.</p>
      </div>
    <div class="btn-Link">
      <a href="#">Read More</a>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
   margin: 0;
   padding: 0;
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1.1em;
    text-align: center;
}
.img {
  position: absolute;
  background: #333 url("https://static.pexels.com/photos/248515/pexels-photo-248515.png");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100%;
  height: 450px;
  z-index: -1;
  opacity: 0.8;

}
.title-txt > h1{
  color: white;
  font-size: 35px;
  padding-top: 100px;
  padding-bottom: 25px;
  text-align: center;
}
.title-txt > p{
text-align: center;
color: white;
padding-bottom: 40px;
}

a{
  text-decoration: none;
  border: 1px solid white;
  color: white;
  padding: 15px 20px 20px 20px ;
  background-color: #333;
  text-align: center;
}



</style>
