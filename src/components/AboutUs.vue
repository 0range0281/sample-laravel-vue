<template>
    <div class="wrapper">
        <div class="textbox">
            <h1>{{ msg }}</h1>
            <div class="text">
                Fashion perfected. Just for you. <br> <br>

                DFS is a leading local casual wear brand worn by most influencers you see on social media. 
                The brand approaches fashion with on-trend, affordable, eco-friendly, and quality 
                merchandise, easily establishing itself as everyone’s go-to brand for fashion pieces that 
                allow them to express themselves and complement for who they are. <br>

                <br> With a vision to break barriers in the fashion scene, DFS takes the stand as 
                the authority on everyday fashion.
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'AboutUs',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Baloo+2&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Lexend:wght@500&display=swap');

.wrapper{
    background-image: url('~@/assets/aboutbg.jpg');
    background-size: cover;
	background-position: center;
	background-repeat: no-repeat;
	background-attachment: fixed;
    margin: auto;
    padding: 93px;
}
h1{
    font-family: "Lexend";
    font-size: 29px;
    text-align: center;
}
.textbox{
    background: rgba(26, 30, 35, 0.8);
    text-align: justify;
    padding: 15px;
    color: white;
}
.text{
    font-family: "Baloo 2";
    font-size: 20px;
}
</style>