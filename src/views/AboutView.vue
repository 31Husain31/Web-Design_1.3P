<template>
  <section class="about-me-page">
    <div class="profile-image">
      <img src="../assets/images/me.png" alt="Husain" class="hover-effect">
    </div>
    <div class="about-content">
      <h1>About Me</h1>
      <p>
        Hello! I'm Husain, an enthusiastic web developer with over 2 years of experience in crafting dynamic and responsive websites. My passion lies in creating innovative web solutions using a wide array of technologies, including React, Vue.js, and Node.js.
      </p>
      <p>
        I earning my degree in Bachelor of Information Technology from Deakin University, where I am honing my skills and knowledge in the world of web development. Since then, I've had the privilege of learning with a diverse range of peers and teachers with little experience in regards to companies as well, delivering top-notch web solutions that meet their unique needs and challenges.
        One of my most exciting accomplishments was building an entire game project from the ground up, showcasing my ability to bring creative ideas to life in the digital realm. I thrive on solving complex technical hurdles, turning them into opportunities for innovation.

      </p>
      <p>
        Outside of the web development world, I have a deep passion for exploration. You'll often find me hiking through scenic trails, getting lost in the pages of tech blogs, and seeking out new and exciting coffee shops to satisfy my caffeine cravings.
        I'm always eager to take on new challenges and contribute my expertise to exciting projects. If you're interested in collaborating or have any questions, please don't hesitate to reach out. Let's turn your ideas into reality!
      </p>
      <button class="download-btn">Download My Resume</button>
      <p>
        Thank you for visiting my portfolio. If you'd like to collaborate or just chat, feel free to <a href="mailto:flamesofkindness@example.com">reach out</a>!
      </p>
    </div>
  </section>
</template>

<script setup>
// You can add any reactive properties or methods if needed.
</script>

<style scoped>
.about-me-page {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 40px 0;
  font-family: 'Arial', sans-serif;
  max-width: 1200px;
  margin: 0 auto;
  background-color: #f4f4f4;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-image {
  flex: 1;
  padding-right: 3px;
}

.profile-image img.hover-effect {
  max-width: 100%;
  border-radius: 50%;
  transition: transform 0.3s, box-shadow 0.3s;
}

.profile-image img.hover-effect:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
}

.about-content {
  flex: 2;
  background-color: #fff;
  padding: 20px;
  border-radius: 10px;
}

.about-content h1 {
  font-size: 2.5em;
  margin-bottom: 20px;
}

.about-content p {
  margin-bottom: 20px;
  line-height: 1.6;
}

.about-content a {
  color: #e74c3c;
  text-decoration: none;
  transition: color 0.3s;
}

.about-content a:hover {
  color: #c0392b;
}

.download-btn {
  display: inline-block;
  background-color: #0b00de;
  color: #fff;
  padding: 10px 20px;
  border-radius: 5px;
  border: none;
  cursor: pointer;
  transition: background-color 0.3s;
}

.download-btn:hover {
  background-color: #c0392b;
}
</style>
