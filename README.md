<!DOCTYPE html>
<html>
<head>
  <style>
    body {
      background: #e0e0e0;
      font-family: "Helvetica", sans-serif;
      line-height: 1.4;
      padding: 20px;
    }

    .window {
      background: white;
      border: 2px solid black;
      border-radius: 5px;
      max-width: 800px;
      margin: 20px auto;
      box-shadow: 5px 5px 0 rgba(0,0,0,0.8);
    }

    .title-bar {
      background: black;
      color: white;
      padding: 5px 10px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      font-weight: bold;
    }

    .window-buttons {
      display: flex;
      gap: 5px;
    }

    .button {
      width: 12px;
      height: 12px;
      border: 1px solid white;
      border-radius: 50%;
    }

    .content {
      padding: 20px;
    }

    h1, h2, h3 {
      font-family: "Helvetica", sans-serif;
      margin: 0;
      padding: 5px 0;
    }

    .menu-bar {
      background: white;
      border-bottom: 2px solid black;
      padding: 5px 10px;
      display: flex;
      gap: 15px;
    }

    .menu-item {
      cursor: pointer;
      padding: 2px 5px;
    }

    .menu-item:hover {
      background: black;
      color: white;
    }

    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(50px, 1fr));
      gap: 10px;
      padding: 10px;
      border: 2px solid black;
      margin: 10px 0;
    }

    .skill-icon {
      width: 40px;
      height: 40px;
      filter: grayscale(100%);
    }

    details {
      border: 2px solid black;
      margin: 10px 0;
    }

    summary {
      background: white;
      padding: 5px 10px;
      cursor: pointer;
    }

    summary:hover {
      background: black;
      color: white;
    }

    .stats-box {
      border: 2px solid black;
      padding: 10px;
      margin: 10px 0;
    }

    .social-links {
      display: flex;
      gap: 10px;
      justify-content: center;
      margin-top: 20px;
    }

    .social-link {
      background: black;
      color: white;
      padding: 5px 10px;
      text-decoration: none;
      border: 2px solid black;
    }

    .social-link:hover {
      background: white;
      color: black;
    }
  </style>
</head>
<body>
  <div class="window">
    <div class="title-bar">
      <span>Finder - Anvesh Srivastava</span>
      <div class="window-buttons">
        <div class="button"></div>
        <div class="button"></div>
        <div class="button"></div>
      </div>
    </div>
    
    <div class="menu-bar">
      <span class="menu-item">File</span>
      <span class="menu-item">Edit</span>
      <span class="menu-item">View</span>
      <span class="menu-item">Special</span>
    </div>

    <div class="content">
      <h1>📁 Anvesh Srivastava</h1>
      <p>🎓 Final Year Student • Full Stack Developer</p>

      <div class="skills-grid">
        <img src="https://skillicons.dev/icons?i=java" class="skill-icon" />
        <img src="https://skillicons.dev/icons?i=spring" class="skill-icon" />
        <img src="https://skillicons.dev/icons?i=react" class="skill-icon" />
        <img src="https://skillicons.dev/icons?i=docker" class="skill-icon" />
        <img src="https://skillicons.dev/icons?i=aws" class="skill-icon" />
      </div>

      <details>
        <summary>💾 Coding Profiles</summary>
        <div class="stats-box">
          <img src="https://leetcard.jacoblin.cool/rookieanvesh?theme=light&font=Helvetica&ext=contest" width="100%" />
        </div>
      </details>

      <details>
        <summary>📂 Projects</summary>
        <div class="stats-box">
          <img src="https://github-readme-stats.vercel.app/api/pin/?username=rookieanvesh&repo=hotel-management&theme=graywhite" width="100%" />
        </div>
      </details>

      <details>
        <summary>📊 Statistics</summary>
        <div class="stats-box">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=rookieanvesh&theme=graywhite&hide_border=true" width="100%" />
        </div>
      </details>

      <div class="social-links">
        <a href="https://github.com/rookieanvesh" class="social-link">Portfolio</a>
        <a href="https://www.linkedin.com/in/anvesh-/" class="social-link">LinkedIn</a>
        <a href="mailto:srivastavaanvesh13@gmail.com" class="social-link">Email</a>
      </div>
    </div>
  </div>
</body>
</html>
