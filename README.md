<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Justin Yan | Homepage</title>
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Montserrat', sans-serif;
      background: #f7fafd;
      color: #222;
      margin: 0;
      padding: 0;
      display: flex;
      min-height: 100vh;
    }
    .sidebar {
      width: 280px;
      background: #fff;
      box-shadow: 2px 0 12px rgba(60,100,180,0.07), 0 2px 8px rgba(0,0,0,0.02);
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem 1rem;
    }
    .profile-img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      margin-bottom: 1.5rem;
      border: 2px solid #e3e8ef;
      background: #e3e8ef;
    }
    .sidebar h1 {
      font-size: 2rem;
      margin: 0.2rem 0 0.5rem 0;
    }
    .sidebar p {
      font-size: 1.1rem;
      margin: 0 0 1.5rem 0;
      color: #4b5e6b;
      text-align: center;
    }
    .nav-links {
      display: flex;
      flex-direction: column;
      gap: 0.7rem;
      width: 100%;
      margin-bottom: 2rem;
    }
    .nav-links a {
      color: #0077ff;
      text-decoration: none;
      font-weight: 500;
      font-size: 1rem;
      padding: 0.4rem 0.7rem;
      border-radius: 6px;
      transition: background 0.2s;
    }
    .nav-links a:hover {
      background: #f0f7ff;
    }
    .contact {
      margin-top: auto;
      font-size: 1rem;
      color: #5a6b7a;
      text-align: center;
    }
    .main-content {
      flex: 1;
      padding: 3rem 2rem;
      max-width: 820px;
      margin: 0 auto;
      background: #f7fafd;
    }
    .section {
      margin-bottom: 2.2rem;
    }
    .section h2 {
      font-size: 1.6rem;
      margin-bottom: 0.5rem;
      color: #0066cc;
      letter-spacing: 0.03em;
    }
    .section p, .section ul {
      font-size: 1.15rem;
      line-height: 1.7;
      color: #293d4e;
      margin-top: 0.3rem;
    }
    @media (max-width: 800px) {
      body {
        flex-direction: column;
      }
      .sidebar {
        width: 100%;
        flex-direction: row;
        justify-content: flex-start;
        padding: 1rem;
        border-radius: 0;
      }
      .profile-img {
        width: 80px;
        height: 80px;
        margin-bottom: 0;
        margin-right: 1rem;
      }
      .main-content {
        padding: 1.2rem 0.7rem;
      }
    }
  </style>
</head>
<body>
  <nav class="sidebar">
    <img src="https://avatars.githubusercontent.com/u/127672479?v=4" alt="Profile image" class="profile-img">
    <div>
      <h1>Justin Yan</h1>
      <p>Statistics Ph.D. student at University of Connecticut</p>
    </div>
    <div class="nav-links">
      <a href="#about">About</a>
       <a href="#education">Education</a>
      <a href="#interests">Interests</a>
      <a href="#contact">Contact</a>
    </div>
    <div class="contact" id="contact">
      <p>Email: <a href="ting-wei.yan@uconn.edu">Justin.Yan</a></p>
      <p>GitHub: <a href="https://github.com/Justin-JAJA" target="_blank">Justin</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/tingwei28/" target="_blank">Ting-Wei Yan </a></p>
    </div>
  </nav>
  <main class="main-content">
    <section class="section" id="about">
      <h2>About</h2>
      <p>
        Hi! I'm Justin Yan, or my mandarin name is Ting-Wei. Welcome to my personal homepage. I am a Statistics PhD student at UConn, holding a Master's degree in Statistics from the University of Cincinnati and a Bachelor's degree in Applied Mathematics from National Sun Yat-Sen University.
I am proficient in R, Python, and SAS, and have earned the SAS Certified Specialist: Advanced Programming certification. He can communicate effectively with experience of being an high school teacher at Newport high school, Newport, Kentucky. Also teaching experience as an adjunct lecturer and a graduate assistant at University of Cincinnati.
      </p>
       </section>
    <section class="section" id="education">
      <h2>Education</h2>
      <ul>
        <li>Ph.D. Statistics, University of Connecticut (2025 – )</li>
        <li>M.S. Statistics, University of Cincinnati( 08/2022– 05/2024)</li>
        <li>B.S. Applied Mathematics, National Sun-Yat Sen University (09/2016 - 06/2021)</li>
      </ul>
    </section>
    <section class="section" id="interests">
      <h2>Interests</h2>
      <ul>
        <li>Multiple imputation</li>
        <li>Data Visualization & Analysis</li>
        <li>Machine Learning & Deep Learning</li>
      </ul>
    </section>
    <section class="section" id="contact">
      <h2>Contact</h2>
      <p>If you wanted to connect feel free to contact email Email: <a href="ting-wei.yan@uconn.edu">ting-wei.yan</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/tingwei28/" target="_blank">Ting-Wei Yan </a></p>
    </section>
  </main>
</body>
</html>

© 2025 Justin Yan. All rights reserved.
