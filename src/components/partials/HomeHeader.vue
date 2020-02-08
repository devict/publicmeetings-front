<template>
  <header>
    <nav>
      <a href="/">
        <img class="logo" src="../../assets/images/logo.svg" />
      </a>
      <!-- Not going with the hamburger menu button for now, switching back to simple links (Jacob.Jordan) -->

      <div class="menu-container">
        <ul class="menu">
          <a href="#"><li>Login</li></a>
          <a href="#"><li>Election Schedule</li></a>
          <a href="#"><li>Voter Registration</li></a>
        </ul>
      </div>
    </nav>
    <div class="call-to-action container">
      <h1>Local Meetings. Stay Informed.</h1>
      <p>Sign-up to receive alerts, set reminders, and more</p>
      <a href="/register" class="signup">Sign-Up</a>
    </div>
    <div class="shape"></div>
  </header>
</template>

<script>
export default {}
</script>

<style scoped>
header {
  color: #fff;
  position: relative;
  background: url('../../assets/images/courthouse.jpg');
  background-position: center;
  background-size: cover;
  height: 25rem;
  overflow: hidden;
  text-align: center;
}

.menu-container {
  display: flex;
}

ul.menu {
  list-style-type: none;
}

li.menu {
  color: #fff;
}
a {
  color: #fff;
}

.call-to-action {
  text-shadow: 2px 2px 2px rgba(0, 0, 0, 0.3);
  padding: 0 1rem;
}

.call-to-action h1 {
  font-size: calc(1.5rem + 2vw);
  font-weight: 900;
}

.call-to-action p {
  margin-top: 1rem;
  margin-bottom: 1.5rem;
  font-size: calc(1rem + 0.75vw);
  font-weight: 700;
}

.signup {
  display: inline-block;
  border: 2px solid #fff;
  border-radius: 0.25rem;
  color: #fff;
  font-weight: 600;
  letter-spacing: 0.1rem;
  text-transform: uppercase;
  text-decoration: none;
  padding: 0.75rem 3rem;
}

.shape {
  width: 200%;
  bottom: -90%;
  border-radius: 50%;
  position: absolute;
  height: 25rem;
  background: #fff;
  left: -50%;
}
</style>




