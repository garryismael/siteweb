<template>
  <div class="body">
    <div class="main">  	
		<input type="checkbox" id="chk" aria-hidden="true">
			<div class="signup">
				<form>
					<label for="chk" aria-hidden="true">Sign up</label>
					<input type="text" name="txt" placeholder="User name" class="input">
					<input type="email" name="email" placeholder="Email" class="input">
					<input type="password" name="pswd" placeholder="Password" class="input">
					<button class="login-btn">Sign up</button>
				</form>
			</div>

			<div class="login">
				<form>
					<label for="chk" aria-hidden="true">Login</label>
					<input type="email" name="email" placeholder="Email" class="input">
					<input type="password" name="pswd" placeholder="Password" class="input">
					<button class="login-btn">Login</button>
				</form>
			</div>
	</div>
  </div>
</template>
<style scoped>
@import "./style/style.css";
</style>