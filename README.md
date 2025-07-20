<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Krishna Verma | Portfolio</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <link href="https://unpkg.com/aos@2.3.4/dist/aos.css" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #0f172a, #1e293b);
      color: #f8fafc;
    }

    nav {
      background-color: #0f172a;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px 40px;
      position: sticky;
      top: 0;
      z-index: 100;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
    }

    nav h1 {
      color: #38bdf8;
      font-size: 26px;
      font-weight: 700;
    }

    nav ul {
      display: flex;
      flex-direction: row;
      gap: 25px;
      list-style: none;
      margin-top: 10px;
    }

    nav ul li a {
      color: #f8fafc;
      text-decoration: none;
      padding: 8px 16px;
      border-radius: 6px;
      font-weight: 500;
      transition: all 0.3s ease;
    }

    nav ul li a:hover {
      box-shadow: 0 0 10px #38bdf8, 0 0 20px #38bdf8;
      background-color: rgba(56, 189, 248, 0.1);
    }

    header {
      height: 100vh;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 0 20px;
      background: linear-gradient(to bottom, #1e293b, #0f172a);
    }

    .profile-pic {
      width: 160px;
      height: 160px;
      object-fit: cover;
      border-radius: 50%;
      border: 4px solid #38bdf8;
      box-shadow: 0 0 25px rgba(56, 189, 248, 0.6);
      margin-bottom: 20px;
      transition: all 0.4s ease;
    }

    .profile-pic:hover {
      transform: scale(1.05);
      box-shadow: 0 0 40px rgba(56, 189, 248, 1);
    }

    header h2 {
      font-size: 42px;
      color: #38bdf8;
    }

    header p {
      font-size: 20px;
      color: #cbd5e1;
      margin-top: 10px;
    }

    section {
      padding: 80px 20px;
      max-width: 900px;
      margin: auto;
      transition: all 0.4s ease;
    }

    section:hover {
      background-color: rgba(255, 255, 255, 0.02);
      box-shadow: 0 0 30px rgba(56, 189, 248, 0.2);
      border-radius: 12px;
    }

    h3 {
      font-size: 28px;
      margin-bottom: 20px;
      color: #38bdf8;
      border-left: 6px solid #38bdf8;
      padding-left: 10px;
    }

    ul {
      padding-left: 20px;
    }

    li {
      margin-bottom: 10px;
      line-height: 1.6;
    }

    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #38bdf8;
      color: #0f172a;
      border: none;
      border-radius: 6px;
      font-weight: bold;
      text-decoration: none;
      transition: 0.3s;
      box-shadow: 0 0 10px #38bdf8;
    }

    .btn:hover {
      transform: scale(1.05);
      box-shadow: 0 0 15px #38bdf8, 0 0 25px #38bdf8;
    }

    .skill {
      margin-bottom: 25px;
    }

    .skill label {
      font-weight: 600;
      display: block;
      margin-bottom: 8px;
    }

    .progress {
      width: 100%;
      background-color: #334155;
      border-radius: 20px;
      overflow: hidden;
      height: 24px;
      box-shadow: inset 0 0 5px #000;
    }

    .bar {
      height: 100%;
      background: linear-gradient(to right, #38bdf8, #0ea5e9);
      text-align: right;
      padding-right: 10px;
      color: #fff;
      font-weight: bold;
      line-height: 24px;
      border-radius: 20px 0 0 20px;
      box-shadow: 0 0 10px #38bdf8;
      transition: width 1s ease-in-out, box-shadow 0.3s ease-in-out;
      cursor: pointer;
    }

    .bar.glow {
      box-shadow: 0 0 25px #38bdf8, 0 0 50px #38bdf8;
    }

    footer {
      text-align: center;
      padding: 30px;
      background-color: #0f172a;
      color: #94a3b8;
      margin-top: 50px;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <h1>Krishna Verma</h1>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Hero Section -->
  <header>
    <img src="https://uploads.onecompiler.io/43eyxmztr/43krmqs8s/Capture.PNG" alt="Krishna's Photo" class="profile-pic">
    <h2>Hi, I'm Krishna</h2>
    <p>BCA Student • Full Stack Learner • Future Developer</p>
  </header>

  <!-- About Section -->
  <section id="about">
    <h3>About Me</h3>
    <p>
      I am a dedicated and confident BCA 2nd-year student with strong leadership and communication skills.
      I have 1 year of experience as a Team Leader at Maersk and 4 months as a Front Desk Executive in a hospital, which helped me develop professionalism, multitasking, and client-handling abilities.
      I am passionate about technology, learning new skills, and contributing to a growing organization.
    </p>
  </section>

  <!-- Experience Section -->
  <section id="experience">
    <h3>Experience</h3>
    <ul>
      <li><strong>Maersk – Team Leader (2024–2025):</strong> Led a dynamic team to meet project goals under strict deadlines. Handled task delegation, performance reporting, and conflict resolution while strengthening leadership, decision-making, and time management skills.</li>
      <li><strong>Neel Eye Hospital – Front Desk Executive (2025–Present):</strong> Managed patient interaction, OPD scheduling, and daily hospital operations. Improved data handling efficiency and supported digital campaigns that boosted outreach and patient engagement.</li>
    </ul>
  </section>

  <!-- Education Section -->
  <section id="education">
    <h3>Education</h3>
    <ul>
      <li><strong>12th (PCM) – PCM Inter College, Kannauj:</strong> Completed with science stream (Physics, Chemistry, Mathematics).</li>
      <li><strong>BCA – DPG Degree College, Gurugram:</strong> Currently pursuing Bachelor of Computer Applications with strong interest in full stack development.</li>
    </ul>
  </section>

  <!-- Skills Section -->
  <section id="skills">
    <h3>Skills</h3>
    <div class="skill">
      <label>HTML</label>
      <div class="progress"><div class="bar" style="width: 75%;">75%</div></div>
    </div>
    <div class="skill">
      <label>CSS</label>
      <div class="progress"><div class="bar" style="width: 55%;">55%</div></div>
    </div>
    <div class="skill">
      <label>Excel</label>
      <div class="progress"><div class="bar" style="width: 87%;">87%</div></div>
    </div>
    <div class="skill">
      <label>Marketing</label>
      <div class="progress"><div class="bar" style="width: 90%;">90%</div></div>
    </div>
    <div class="skill">
      <label>Python</label>
      <div class="progress"><div class="bar" style="width: 70%;">70%</div></div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h3>Contact</h3>
    <p><strong>Email:</strong> kv322006@gmail.com</p>
    <p><strong>Phone:</strong> +91 7404511624</p>
    <p><strong>Location:</strong> Kannauj, Uttar Pradesh (209733) India</p>
    
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Krishna Verma Portfolio. Built with 💙 using HTML + CSS.
  </footer>

  <!-- Script for skill bar glow -->
  <script>
    const bars = document.querySelectorAll('.bar');
    bars.forEach(bar => {
      bar.addEventListener('click', () => {
        bar.classList.add('glow');
        setTimeout(() => {
          bar.classList.remove('glow');
        }, 2000);
      });
    });
  </script>

</body>
</html>
