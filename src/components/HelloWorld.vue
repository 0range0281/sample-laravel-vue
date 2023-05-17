<template>
  <div class="wrapper">
    <div class="outerbox"></div>
    <div class="content">
      <div class="slogan">
        Fashion perfected. Just for you.
      </div>
      <div class="text">
        Coming soon...
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Averia+Serif+Libre:wght@700&display=swap');

.wrapper{
  background-image: url('~@/assets/bghome.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
  margin: auto;
  padding: 125px;
  border: 4px solid black;
}
.outerbox{
  background: rgba(103, 34, 214, 0.5);
  width: 1050px;
  height: 300px;
  position: absolute;
  mix-blend-mode: overlay;
  top: 178px;
  left: 96px;
}
.content{
  background: rgba(45, 243, 129, 0.8);
  height: 200px;
  padding: 30px;
}
.slogan{
  font-family: "Averia Serif Libre";
  font-size: 36px;
  letter-spacing: 2px;
  margin-top: 30px;
}
.text{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  font-size: 30px;
  margin-top: 50px;
}
</style>