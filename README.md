<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zeyad Abdelnaby's Profile</title>
  <style>
    /* Global styles */
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f9;
      color: #333;
      margin: 0;
      padding: 0;
    }

    h1, h3 {
      animation: fadeIn 2s ease-in-out;
    }

    p, ul {
      animation: slideIn 2s ease-out;
    }

    a img {
      transition: transform 0.3s ease;
    }

    a img:hover {
      transform: scale(1.2);
    }

    /* Keyframes for animations */
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes slideIn {
      from {
        transform: translateX(-100%);
        opacity: 0;
      }
      to {
        transform: translateX(0);
        opacity: 1;
      }
    }

    @keyframes scaleUp {
      from {
        transform: scale(0.8);
        opacity: 0;
      }
      to {
        transform: scale(1);
        opacity: 1;
      }
    }

    /* Motion graphics for icons and projects */
    .language-icon {
      width: 40px;
      height: 40px;
      animation: scaleUp 1.5s ease-out;
    }

    .project {
      animation: fadeIn 2s ease-in-out;
      margin-bottom: 15px;
    }

    /* Centered alignments */
    h1, h3, p {
      text-align: center;
    }

    .content {
      max-width: 800px;
      margin: 20px auto;
      padding: 20px;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .social-links a {
      margin: 0 10px;
    }

    .languages {
      display: flex;
      justify-content: center;
      gap: 10px;
      margin-top: 15px;
    }
  </style>
</head>
<body>
  <div class="content">
    <h1 style="color:blue;">Hello 👋, I'm Zeyad Abdelnaby</h1>
    <h3 style="color:blue;">Full-Stack Developer | Computer Science Graduate</h3>

    <p>🌱 <strong>Currently Exploring</strong>: Advanced features of <strong>.NET Core 8</strong>, real-time systems with <strong>SignalR</strong>, and front-end mastery using <strong>Vue.js 3</strong>.</p>
    <p>🖥️ <strong>Current Role</strong>: Full-Stack Developer @ <strong>Misk for Integrated Solutions</strong>.</p>
    <p>📚 <strong>Education</strong>: Bachelor’s in Computer Science, <strong>South Valley University (2020 - 2024)</strong>.</p>
    <p>💡 <strong>Achievements</strong>:
      <ul>
        <li>Co-founded <strong>ACPC SVU</strong>: Mentored 250+ students in competitive programming.</li>
        <li>Designed and implemented 200+ competitive programming problems.</li>
        <li>Participated in <strong>ECPC 2021 & 2022</strong>.</li>
      </ul>
    </p>
    <p>📄 <strong><a href="https://drive.google.com/file/d/1Hl9s03xowB7A-ns5x-0TxSanaCrRrqO2/view?usp=sharing" target="_blank">View My Resume</a></strong>.</p>
    <p>⚡ <strong>Fun Fact</strong>: Passionate about solving complex challenges and leveraging technology for real-world impact.</p>

    <h3>Connect with Me:</h3>
    <p class="social-links">
      <a href="https://linkedin.com/in/zeyad-abdelnaby" target="_blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" class="language-icon" />
      </a>
      <a href="https://github.com/zeyad-sudo" target="_blank">
        <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/github.svg" alt="GitHub" class="language-icon" />
      </a>
    </p>

    <h3>Languages and Tools:</h3>
    <div class="languages">
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" class="language-icon" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" class="language-icon" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" alt="Vue.js" class="language-icon" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="MySQL" class="language-icon" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original-wordmark.svg" alt="Git" class="language-icon" />
      <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt=".NET Core" class="language-icon" />
    </div>

    <h3>Highlighted Projects:</h3>
    <div class="project">
      <p><strong><a href="https://github.com/zeyad-sudo/MedicalSystem" target="_blank">Medical System</a></strong>: Developed a healthcare management platform for 500+ daily reservations. Integrated <strong>LLMs for tumor detection</strong> (95% accuracy) and diabetes predictions. Used <strong>.NET Core</strong> and <strong>MySQL</strong> for streamlined backend operations.</p>
    </div>
    <div class="project">
      <p><strong><a href="https://github.com/zeyad-sudo/Meeting-Management-System" target="_blank">Meeting Management System</a></strong>: Automated 85% of manual meeting processes, saving 25+ hours/month. Enhanced database efficiency and workflow automation.</p>
    </div>
    <div class="project">
      <p><strong><a href="https://github.com/zeyad-sudo/Facilities-Management-System" target="_blank">Facilities Management System</a></strong>: Designed a backend for license verification handling 500+ licenses/day. Integrated <strong>Windows Forms</strong> for robust user interactions.</p>
    </div>
  </div>
</body>
</html>
