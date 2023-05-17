<template>
	<div class="loginbox" style="color: black">
		<img alt="DFS Logo" src="../assets/logoD.png" width="150px" height="150px" class="logo">
		<h1>Login</h1>
		<form>
			<p>Username</p>
			<input type="text" placeholder="Enter username">
			<p>Password</p>
			<input type="password" placeholder="Enter password">
			<input type="submit" value="Login">
			<a href="#">Forgot Password?</a><br>
		</form>
	</div>
</template>

<script>
export default {
  name: 'Loginbox',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Montserrat&display=swap');
@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans&display=swap');

div{
	font-family: "Montserrat";
	margin-top: 40px;
}

.loginbox{
	width: 320px;
	height: 420px;
	background: #2DF381;
	color: #fff;
	top: 50%;
	left: 50%;
	position: absolute;
	transform: translate(-50%, -50%);
	box-sizing: border-box;
	border-radius: 5%;
}

.logo{
	width: 100px;
	height: 100px;
	border-radius: 20%;
	position: absolute;
	top: -50px;
	left: calc(50% - 50px);
}

h1{
	margin: 0;
	margin-top: 70px;
	padding: 0 0 10px;
	text-align: center;
	font-size: 20px;
}

.loginbox p{
	margin: 0;
	margin-left: 5px;
	padding: 0;
	font-weight: bold;
	font-size: 18px;
}
.loginbox input{
	width: 290px;
	margin-bottom: 20px;
	margin-left: 5px;
}
.loginbox input[type="text"], input[type="password"]{
	border: none;
	border-bottom: 1px solid black;
	background: transparent;
	outline: none;
	height: 40px;
	color: black;
	font-size: 15px;
	font-family: "IBM Plex Sans";
}
.loginbox input[type="submit"]{
	border: none;
	outline: none;
	height: 40px;
	background: #1A1E23;
	color: #fff;
	font-size: 18px;
	border-radius: 20px;
}
.loginbox input[type="submit"]:hover{
	cursor: pointer;
	background: #6722D6;
	color: #fff;
}
.loginbox a{
	text-decoration: none;
	font-size: 14px;
	line-height: 20px;
	color: black;
	margin-left: 5px;
}
.loginbox a:hover{
	color: white;
}
</style>