<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Kavindu Sankalpa | GitHub Profile</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Segoe UI, sans-serif;
    }

    body{
      background:#0d1117;
      color:#c9d1d9;
      line-height:1.6;
    }

    .container{
      max-width:1000px;
      margin:auto;
      padding:40px 20px;
    }

    .hero{
      text-align:center;
      padding:60px 20px;
      border-bottom:1px solid #30363d;
    }

    .hero h1{
      font-size:50px;
      color:#58a6ff;
      margin-bottom:10px;
    }

    .hero h2{
      font-size:22px;
      color:#8b949e;
      font-weight:normal;
      margin-bottom:20px;
    }

    .hero p{
      max-width:700px;
      margin:auto;
      color:#c9d1d9;
    }

    .section{
      margin-top:50px;
    }

    .section h2{
      font-size:30px;
      margin-bottom:20px;
      color:#58a6ff;
      border-bottom:2px solid #30363d;
      padding-bottom:10px;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:15px;
    }

    .skill{
      background:#161b22;
      border:1px solid #30363d;
      padding:12px 20px;
      border-radius:8px;
      transition:0.3s;
    }

    .skill:hover{
      background:#21262d;
      transform:translateY(-3px);
    }

    .card{
      background:#161b22;
      border:1px solid #30363d;
      padding:25px;
      border-radius:12px;
      margin-bottom:20px;
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-5px);
      background:#1c2128;
    }

    .card h3{
      color:#58a6ff;
      margin-bottom:10px;
    }

    .contact a{
      display:inline-block;
      margin-right:15px;
      margin-top:10px;
      text-decoration:none;
      color:#58a6ff;
    }

    .footer{
      text-align:center;
      padding:40px 0;
      margin-top:60px;
      border-top:1px solid #30363d;
      color:#8b949e;
    }

    ul{
      padding-left:20px;
    }

    li{
      margin-bottom:10px;
    }

    .github-box{
      background:#161b22;
      border:1px solid #30363d;
      padding:25px;
      border-radius:12px;
      text-align:center;
      margin-top:30px;
    }

    .btn{
      display:inline-block;
      margin-top:15px;
      padding:12px 25px;
      background:#238636;
      color:white;
      text-decoration:none;
      border-radius:8px;
      transition:0.3s;
    }

    .btn:hover{
      background:#2ea043;
    }

  </style>
</head>
<body>

  <div class="container">

    <!-- HERO SECTION -->
    <section class="hero">
      <h1>Kavindu Sankalpa</h1>
      <h2>💻 Java & Web Developer</h2>

      <p>
        Passionate software developer interested in Web Development,
        Java programming, and modern technologies.
        I enjoy building creative projects and learning new skills every day.
      </p>

      <div class="contact">
        <a href="mailto:kavindusankalpa584@gmail.com">📧 Email</a>
        <a href="tel:+94760199586">📱 Phone</a>
        <a href="#">🌐 GitHub</a>
      </div>
    </section>

    <!-- ABOUT -->
    <section class="section">
      <h2>👨‍💻 About Me</h2>

      <div class="card">
        <p>
          I am a self-motivated and hardworking student from Sri Lanka.
          I have experience with Java, HTML, CSS, and JavaScript.
          I enjoy working on software and web development projects while improving my technical knowledge.
        </p>
      </div>
    </section>

    <!-- SKILLS -->
    <section class="section">
      <h2>⚡ Skills</h2>

      <div class="skills">
        <div class="skill">Java</div>
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">MS Office</div>
        <div class="skill">Leadership</div>
        <div class="skill">Teamwork</div>
        <div class="skill">Communication</div>
        <div class="skill">Creativity</div>
      </div>
    </section>

    <!-- EDUCATION -->
    <section class="section">
      <h2>🎓 Education</h2>

      <div class="card">
        <h3>G.C.E Ordinary Level Examination - 2020</h3>
        <p>Wijayawardhana Maha Vidyalaya, Kiriwaththuduwa</p>
        <p>A - 2 | B - 3 | C - 3</p>
      </div>

      <div class="card">
        <h3>G.C.E Advanced Level Examination - 2023</h3>
        <p>Lumbini College, Colombo</p>
        <p>Completed Grade 12 & Grade 13</p>
      </div>

      <div class="card">
        <h3>Diploma in Information & Digital Technology</h3>
        <p>BIET Campus (2025 - Present)</p>
      </div>
    </section>

    <!-- PROJECTS -->
    <section class="section">
      <h2>🚀 Projects</h2>

      <div class="card">
        <h3>Calculator App</h3>
        <p>
          Android calculator application developed using Kotlin and Android Studio.
        </p>
      </div>

      <div class="card">
        <h3>Stock Management System</h3>
        <p>
          OOP-based stock management software project for retail store management.
        </p>
      </div>
    </section>

    <!-- LANGUAGES -->
    <section class="section">
      <h2>🌍 Languages</h2>

      <div class="card">
        <ul>
          <li>Sinhala</li>
          <li>English</li>
        </ul>
      </div>
    </section>

    <!-- GITHUB -->
    <section class="section">
      <h2>🐙 GitHub Profile</h2>

      <div class="github-box">
        <h3>Check Out My GitHub Projects</h3>
        <p>
          Explore my repositories, coding projects, and development journey.
        </p>

        <a href="#" class="btn">Visit GitHub</a>
      </div>
    </section>

    <!-- FOOTER -->
    <footer class="footer">
      <p>© 2026 Kavindu Sankalpa | Built with HTML & CSS</p>
    </footer>

  </div>

</body>
</html>
