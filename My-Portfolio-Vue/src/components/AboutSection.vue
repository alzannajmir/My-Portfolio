<template>
  <div class="about-container">
    <div class="about-image">
      <img src="../assets/img/background/pasduduk.png" alt="Foto Profil" />
    </div>
    <div class="about-content">
      <!-- <p class="about-badge">ABOUT ME</p> -->
      <h1>
        I AM AVAILABLE FOR <br />
        <span class="highlight">Software Tester</span>
      </h1>
      <p class="about-desc">
        A Computer Science graduate with a strong foundation in analytical
        thinking and attention to detail, experienced in conducting manual
        testing, analyzing user stories, and creating clear and comprehensive
        feature documentation. Proficient in Agile methodologies and effective
        cross-functional collaboration with development teams to ensure product
        quality. Demonstrates the ability to identify bugs systematically,
        design efficient test scenarios, and contribute to improving overall
        software performance. Passionate about ensuring seamless user
        experiences and continuously enhancing testing processes to support
        reliable and scalable software delivery.
      </p>
      <div class="about-stats">
        <div class="stat-box">
          <h2>3+</h2>
          <p>Experience</p>
        </div>
        <div class="stat-box">
          <h2>8+</h2>
          <p>Certificate</p>
        </div>
        <div class="stat-box">
          <h2>5+</h2>
          <p>Skill</p>
        </div>
      </div>
      <!-- <a href="#contact" class="btn-contact">GET IN TOUCH →</a> -->
    </div>
  </div>
  <div class="span-2">
    <span></span>
  </div>
</template>

<style scoped>
.about-section {
  color: antiquewhite;
  padding: 100px 80px;
  display: flex;
  justify-content: center;
  align-items: center;
}

.about-container {
  display: flex;
  align-items: center;
  justify-content: space-between;
  max-width: 1100px;
  gap: 60px;
}

.about-image img {
  width: 350px;
  border-radius: 20px;
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.4);
}

.about-content {
  flex: 1;
}

.about-badge {
  background-color: #083f75;
  display: inline-block;
  padding: 6px 14px;
  border-radius: 20px;
  font-size: 12px;
  letter-spacing: 1px;
  margin-bottom: 10px;
  font-size: 2em;
  margin-bottom: 40px;
  position: relative;
}

.about-content h1 {
  font-size: 34px;
  line-height: 1.4;
  font-weight: 700;
  margin-bottom: 20px;
}

.about-content .highlight {
  color: black;
}

.about-desc {
  color: antiquewhite;
  font-size: 15px;
  line-height: 1.8;
  margin-bottom: 30px;
}

.about-stats {
  display: flex;
  gap: 30px;
  margin-bottom: 40px;
}

.stat-box {
  background-color: rgba(255, 255, 255, 0.05);
  padding: 20px 25px;
  border-radius: 10px;
  text-align: center;
  transition: transform 0.3s ease;
}

.stat-box:hover {
  transform: translateY(-5px);
}

.stat-box h2 {
  color: antiquewhite;
  font-size: 28px;
  margin-bottom: 5px;
}

.stat-box p {
  color: black;
  font-size: 14px;
}

.span-2 span {
  display: block;
  height: 25px;
  background: linear-gradient(
    to right,
    rgb(95, 101, 86),
    rgba(173, 255, 47, 0)
  );
  position: inline-block;
  box-shadow: 0 3px 6px rgba(0, 0, 0, 0.1);
}
</style>
