<template>
  <div class="hero">
    <div class="hero-text">
      <h1>HI! I'M NAJMI <br />I'M A Programmer <br /></h1>
      <p>
        A Computer Science graduate with strong analytical and detail-oriented
        skills, experienced in manual testing, user story analysis, and feature
        documentation.
      </p>
      <a href="" class="btn">Get in Touch</a>
    </div>
    <div class="foto">
      <img src="../assets/img/background/pasfoto.png" alt="foto1" />
    </div>
  </div>
  <div class="span-1">
    <span></span>
  </div>
</template>

<style scoped>
.hero {
  height: auto;
  width: auto;
  display: flex;
  justify-content: space-between;
}

.hero .hero-text {
  margin-top: 180px;
  margin-left: 180px;
}

.hero .hero-text h1 {
  font-size: 45px;
  color: antiquewhite;
  margin-bottom: 10px;
}

.hero .hero-text p {
  margin-bottom: 25px;
  font-size: 150%;
  color: white;
}

.hero-text .btn {
  background-color: black;
  color: antiquewhite;
  text-decoration: none;
  padding: 10px 20px;
  border-radius: 6px;
  display: inline-block;
  transition: background 0.3s ease;
}

.foto img {
  margin-top: 100px;
  margin-right: 180px;
}

.span-1 span {
  display: block;
  height: 25px;
  background: linear-gradient(to left, rgb(95, 101, 86), rgba(173, 255, 47, 0));
  position: inline-block;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1);
}
</style>
