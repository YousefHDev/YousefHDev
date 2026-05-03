<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Yousef Hesham | Backend Developer</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#0f172a;
      color:white;
      padding:40px;
      line-height:1.7;
    }

    .container{
      max-width:1000px;
      margin:auto;
    }

    .hero{
      text-align:center;
      margin-bottom:50px;
    }

    .hero h1{
      font-size:60px;
      color:#38bdf8;
      margin-bottom:10px;
    }

    .hero h2{
      font-size:28px;
      color:#cbd5e1;
      margin-bottom:20px;
    }

    .hero p{
      max-width:700px;
      margin:auto;
      color:#94a3b8;
      font-size:18px;
    }

    .section-title{
      font-size:32px;
      margin-bottom:25px;
      color:#38bdf8;
      border-left:5px solid #38bdf8;
      padding-left:15px;
    }

    .about{
      margin-bottom:50px;
    }

    .about p{
      color:#cbd5e1;
      font-size:18px;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:15px;
      margin-bottom:50px;
    }

    .skill{
      padding:12px 22px;
      border-radius:12px;
      border:2px solid;
      font-weight:bold;
      transition:0.3s;
      cursor:pointer;
    }

    .skill:hover{
      transform:translateY(-5px);
    }

    .blue{
      border-color:#38bdf8;
      color:#38bdf8;
    }

    .green{
      border-color:#22c55e;
      color:#22c55e;
    }

    .yellow{
      border-color:#eab308;
      color:#eab308;
    }

    .purple{
      border-color:#a855f7;
      color:#a855f7;
    }

    .red{
      border-color:#ef4444;
      color:#ef4444;
    }

    .projects{
      margin-bottom:50px;
    }

    .project-card{
      background:#1e293b;
      padding:25px;
      border-radius:16px;
      margin-bottom:20px;
      border:1px solid #334155;
    }

    .project-card h3{
      color:#38bdf8;
      margin-bottom:10px;
    }

    .project-card p{
      color:#cbd5e1;
    }

    .contact{
      margin-top:50px;
    }

    .contact a{
      display:block;
      width:fit-content;
      margin-bottom:15px;
      text-decoration:none;
      color:white;
      background:#1e293b;
      padding:15px 25px;
      border-radius:12px;
      transition:0.3s;
      border:1px solid #334155;
    }

    .contact a:hover{
      background:#38bdf8;
      color:#0f172a;
      transform:scale(1.05);
    }

    footer{
      margin-top:60px;
      text-align:center;
      color:#64748b;
    }

  </style>
</head>

<body>

  <div class="container">

    <section class="hero">
      <h1>Yousef Hesham</h1>
      <h2>Backend Developer 🚀</h2>

      <p>
        Passionate Backend Developer specialized in building scalable APIs,
        authentication systems, and modern web applications using Node.js
        and backend technologies.
      </p>
    </section>

    <section class="about">
      <h2 class="section-title">About Me</h2>

      <p>
        Computer Science graduate passionate about backend development,
        clean architecture, databases, and scalable systems.
        I enjoy building modern applications and continuously improving
        my software engineering skills.
      </p>
    </section>

    <section>
      <h2 class="section-title">Skills</h2>

      <div class="skills">

        <div class="skill blue">Node.js</div>
        <div class="skill green">Express.js</div>
        <div class="skill yellow">MongoDB</div>
        <div class="skill purple">MySQL</div>
        <div class="skill red">PostgreSQL</div>

        <div class="skill blue">JavaScript</div>
        <div class="skill green">TypeScript</div>
        <div class="skill yellow">REST APIs</div>
        <div class="skill purple">Authentication</div>
        <div class="skill red">JWT</div>

        <div class="skill blue">Git & GitHub</div>
        <div class="skill green">Docker</div>
        <div class="skill yellow">Postman</div>
        <div class="skill purple">Clean Architecture</div>
        <div class="skill red">Problem Solving</div>

      </div>
    </section>

    <section class="projects">
      <h2 class="section-title">Featured Project</h2>

      <div class="project-card">
        <h3>Job Search App</h3>

        <p>
          Full-featured backend system for a job search platform including
          authentication, authorization, Google OAuth, company management,
          job applications, admin dashboard, real-time notifications,
          and modular clean architecture.
        </p>
      </div>

    </section>

    <section class="contact">
      <h2 class="section-title">Contact With Me</h2>

      <a href="mailto:adhamh430@gmail.com">
        📧 adhamh430@gmail.com
      </a>

      <a href="https://linkedin.com/in/yousef-hesham-416863319" target="_blank">
        💼 LinkedIn Profile
      </a>

    </section>

    <footer>
      <p>© 2026 Yousef Hesham — Backend Developer</p>
    </footer>

  </div>

</body>
</html>
