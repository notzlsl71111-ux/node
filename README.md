<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio ของวงศ์กร</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <!-- Navbar -->
  <nav>
    <h1>Wongsakone Portfolio</h1>
    <ul>
      <li><a href="#home">หน้าแรก</a></li>
      <li><a href="#about">เกี่ยวกับฉัน</a></li>
      <li><a href="#portfolio">ผลงาน</a></li>
      <li><a href="#contact">ติดต่อ</a></li>
    </ul>
  </nav>

  <!-- Home -->
  <header id="home">
    <h2>สวัสดีครับ, ผมคือ วงศ์กร</h2>
    <p>นักพัฒนาเว็บไซต์ | นักออกแบบ | ผู้ชอบสร้างสรรค์สิ่งใหม่</p>
  </header>

  <!-- About -->
  <section id="about">
    <h2 class="section-title">🙋‍♂️ เกี่ยวกับฉัน</h2>
    <div class="about">
      <img src="images/profile.jpg" alt="profile">
      <div class="about-text">
        <p>สวัสดีครับ! ผมคือ วงศ์กร นักพัฒนาเว็บไซต์ที่มีความหลงใหลในการสร้างเว็บสวย ใช้งานง่าย และตอบโจทย์ธุรกิจจริง ๆ</p>
        <p>มีประสบการณ์ในการทำงานกับ HTML, CSS, JavaScript, และ Frameworks อย่าง React, Node.js และอื่น ๆ</p>
        <p>ผมชอบเรียนรู้เทคโนโลยีใหม่ ๆ และพัฒนาไอเดียให้กลายเป็นสิ่งที่จับต้องได้ 🚀</p>
      </div>
    </div>
  </section>

  <!-- Portfolio -->
  <section id="portfolio">
    <h2 class="section-title">💼 ผลงานของฉัน</h2>
    <div class="portfolio">
      <div class="card">
        <img src="images/project1.jpg" alt="Project 1">
        <h3>เว็บไซต์ร้านกาแฟ</h3>
      </div>
      <div class="card">
        <img src="images/project2.jpg" alt="Project 2">
        <h3>ระบบจองคิวออนไลน์</h3>
      </div>
      <div class="card">
        <img src="images/project3.jpg" alt="Project 3">
        <h3>เว็บรีวิวเกม</h3>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2 class="section-title">📞 ติดต่อฉัน</h2>
    <div class="contact">
      <p>สามารถติดต่อได้ทาง:</p>
      <a href="mailto:Cown238@gmail.com">อีเมล</a>
      <a href="https://www.instagram.com/wongsakonez" target="_blank">Instagram</a>
      <a href="https://www.facebook.com/wongsakonez" target="_blank">Facebook</a>
      <a href="https://wskonersc.info" target="_blank">เว็บไซต์: wskonersc.info</a>
    </div>

    <!-- Contact Form -->
    <form action="https://formspree.io/f/mayvkyve" method="POST">
      <input type="text" name="name" placeholder="ชื่อของคุณ" required>
      <input type="email" name="email" placeholder="อีเมลของคุณ" required>
      <textarea name="message" placeholder="ข้อความ" rows="5" required></textarea>
      <button type="submit">ส่งข้อความ</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>©️ 2025 สงวนลิขสิทธิ์โดย วงศ์กร</p>
  </footer>

</body>
</html>