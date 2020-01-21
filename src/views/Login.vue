<template>
  <div>
    <div id="container">
    <GenericHeader />
    <div id="wholeform">
    <form>
      <h1>Log In</h1>
      <div id="form">
        <label>Username</label>
        <input class="own_line" type="text" placeholder="Username">
      </div>
      <div id="form">
        <label>Password</label>
        <input class="own_line" type="password" placeholder="Password" required>
      </div>
      <div class="flex login-options">
      <div class="flex checkbox">
            <input type="checkbox" name="remember-me">
            <label>Remember me</label>
         </div>
         <a href="#">Forgot password?</a>
      </div>


      <div id="buttons">
      <input id="Login" type="submit" value="Login">


      <input id="Signup" type="button" value="Sign up">
      </div>
    </form>
    </div>
  </div>
  </div>
</template>
<script>

import GenericHeader from '@/components/partials/GenericHeader'
export default {
  components: {
    GenericHeader
  }
}

</script>

<style scoped>
a {
  float: right;
  text-decoration: none;
}

#buttons {
  margin-top: 3em;
}
.own_line {
  display: block;
}
.checkbox {
  align-items: center;
}

.checkbox input {
  height: 1rem;
  margin-right: 4px;
}

#container {
  display: block;
  align: center;
  margin: 0 auto;
}


form {

  background: #FFFFFF;
  border: 1px solid #D4E3EA;
  box-sizing: border-box;
  display: inline-block;
  padding: 2em;
  margin: 2em;
  width: 335px;
  height: 314px;
  left: 29px;
  top: 260px;

}
#form {
  padding: 0.5em;

}
#form_bottom {
  display: flex;
  padding: 0.5em;
  margin: 0.5em;
}

.form_bottom_right {
  margin-left: 3em;
}
input {
  width: 100%;
  border: none;

}




#form label {
  font-size: 12px;
}

h1 {
  font-size: 120%;
}
#Login {
  align-items: center;
  background-color: #008CC8;
  border-radius: 2px;
  border-style: solid;
  border-width: 1px;
  color: #FFFFFF;
  display: flex;
  padding: 0.5em;
  float: left;
  font-family: Montserrat;
  font-weight: normal;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 15px;
  margin-right: 10px;
  text-align: center;
  width: 30%;

}

.login-options {
   align-items: center;
   justify-content: space-between;
   font-size: 0.8rem;
}

#Signup {
align-items: center;
background-color: #FFFFFF;
border-radius: 2px;
border-style: solid;
border-width: 1px;
color: #008CC8;
display: flex;
padding: 0.5em;
float: left;
font-size: 12px;
line-height: 15px;
margin-right: 10px;
text-align: center;
width: 30%;

}

::-webkit-input-placeholder {
  opacity: 0.5;
}

#wholeform {
  display: flex;
  justify-items: center;
}
</style>
