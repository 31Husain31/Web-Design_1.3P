<template>
    <footer class="amazing-footer">
      <div class="footer-content">
        <div class="footer-section">
          <h4>Get To Know Me Quickly :] </h4>
          <p>In addition to my technical expertise, I take immense pride in my ability to tackle complex problems head-on. 
            With a never-give-up mindset, I relish challenges and view them as opportunities for growth and innovation. I'm not just a solo performer; I thrive in a collaborative environment and consider myself a friendly and enthusiastic team player. Together, we can turn obstacles into stepping stones and create outstanding web solutions that exceed expectations. Let's connect and embark on a journey of web development excellence!</p>
        </div>
        <div class="footer-section">
          <h4>Quick Links</h4>
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Portfolio</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">Blog</a></li>
          </ul>
        </div>
        <div class="footer-section">
          <h4>Contact Info</h4>
          <p><i class="fas fa-map-marker-alt"></i> 221b BS, London</p>
          <p><i class="fas fa-phone"></i> +61 493292723</p>
          <p><i class="fas fa-envelope"></i> flamesofkindness@gmail.com</p>
        </div>
      </div>
      <div class="footer-bottom">
        <p>&copy; *** Husainuddin Mohammed's Resume ***</p>
      </div>
    </footer>
  </template>
  
  <script setup>
  // You can add any reactive properties or methods if needed.
  </script>
  
  <style scoped>
  .amazing-footer {
    background-color: #2c3e50;
    color: #09cafb;
    padding: 40px 0;
    font-family: 'Arial', sans-serif;
  }
  
  .footer-content {
    display: flex;
    justify-content: space-between;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  .footer-section {
    flex: 1;
    margin-right: 20px;
  }
  
  .footer-section:last-child {
    margin-right: 0;
  }
  
  .footer-section h4 {
    border-bottom: 2px solid #e74c3c;
    padding-bottom: 10px;
    margin-bottom: 20px;
  }
  
  .footer-section p, .footer-section li {
    margin-bottom: 10px;
  }
  
  .footer-section a {
    color: #00ccff;
    text-decoration: none;
    transition: color 0.3s;
  }
  
  .footer-section a:hover {
    color: #e74c3c;
  }
  
  .footer-bottom {
    text-align: center;
    margin-top: 40px;
    border-top: 1px solid #34495e;
    padding-top: 20px;
  }
  
  /* If you're using Font Awesome for icons */
  .fas {
    margin-right: 10px;
  }
  </style>
  