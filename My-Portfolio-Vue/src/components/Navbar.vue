<template>
  <header class="navbar">
    <div class="logo">
      <img src="../assets/img/background/anr.png" alt="logoANR" />
    </div>
    <div class="navbar-text">
      <ul>
        <li><a href="">Home</a></li>
        <li><a href="">About Me</a></li>
        <li><a href="">Project</a></li>
        <li><a href="">Skill</a></li>
        <li><a href="">Contact</a></li>
      </ul>
    </div>
  </header>
</template>

<style scoped>
.navbar {
  justify-content: center;
  background-color: grey;
  position: fixed;
  display: flex;
  width: 100%;
  border-radius: 0px 0px 10px 10px;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1);
}

.navbar .logo img {
  padding: 5px;
  width: 35px;
  height: 35px;
}

.navbar ul {
  display: flex;
  gap: 50px;
}

.navbar li {
  display: inline-block;
}

.navbar a {
  text-decoration: none;
  font-size: 15px;
  color: antiquewhite;
}

.navbar a:hover {
  color: black;
}
</style>
