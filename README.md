<div align="center">
  
  <!-- Enhanced CSS Styling with Advanced Effects -->
  <style>
    .profile-container {
      background: linear-gradient(45deg, #000428, #004e92, #000428);
      border-radius: 15px;
      padding: 20px;
      margin: 10px;
      box-shadow: 0 0 30px rgba(0, 217, 255, 0.3);
      animation: glow 2s ease-in-out infinite alternate;
      position: relative;
      overflow: hidden;
    }
    
    .profile-container::before {
      content: '';
      position: absolute;
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      background: linear-gradient(45deg, #00ff00, #00ffff, #ff00ff, #ffff00, #00ff00);
      border-radius: 15px;
      z-index: -1;
      animation: rainbow-border 3s linear infinite;
    }
    
    .neon-border {
      border: 2px solid #00ff00;
      border-radius: 15px;
      box-shadow: 
        0 0 5px #00ff00,
        0 0 10px #00ff00,
        0 0 15px #00ff00,
        0 0 20px #00ff00,
        inset 0 0 5px #00ff00;
      animation: neon-pulse 1.5s infinite alternate;
      position: relative;
      background: rgba(0, 0, 0, 0.1);
      backdrop-filter: blur(10px);
    }
    
    .tech-badge {
      transition: all 0.3s ease;
      border-radius: 8px;
      margin: 5px;
      cursor: pointer;
      filter: brightness(1);
    }
    
    .tech-badge:hover {
      transform: translateY(-8px) scale(1.1) rotate(2deg);
      box-shadow: 0 15px 25px rgba(0, 255, 255, 0.4);
      filter: brightness(1.2) contrast(1.1);
      z-index: 10;
    }
    
    .floating {
      animation: float 3s ease-in-out infinite;
    }
    
    .gradient-text {
      background: linear-gradient(45deg, #00ff00, #00ffff, #ff00ff, #ffff00);
      background-size: 400% 400%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      font-weight: bold;
      animation: rainbow-text 3s ease infinite;
      text-shadow: 0 0 10px rgba(0, 255, 255, 0.5);
    }
    
    .tech-container {
      padding: 15px;
      margin: 10px 0;
      border-radius: 10px;
      background: linear-gradient(135deg, rgba(0, 255, 255, 0.1), rgba(255, 0, 255, 0.1));
      backdrop-filter: blur(5px);
    }
    
    .sparkle {
      position: relative;
      overflow: hidden;
    }
    
    .sparkle::before {
      content: '';
      position: absolute;
      top: 0;
      left: -100%;
      width: 100%;
      height: 100%;
      background: linear-gradient(90deg, transparent, rgba(255, 255, 255, 0.2), transparent);
      animation: sparkle 2s infinite;
    }
    
    @keyframes glow {
      from { 
        box-shadow: 0 0 20px rgba(0, 217, 255, 0.3), 0 0 40px rgba(0, 217, 255, 0.1); 
      }
      to { 
        box-shadow: 0 0 40px rgba(0, 217, 255, 0.6), 0 0 60px rgba(0, 217, 255, 0.3); 
      }
    }
    
    @keyframes neon-pulse {
      0% { 
        border-color: #00ff00; 
        box-shadow: 0 0 5px #00ff00, 0 0 10px #00ff00, 0 0 15px #00ff00; 
      }
      50% { 
        border-color: #00ffff; 
        box-shadow: 0 0 10px #00ffff, 0 0 20px #00ffff, 0 0 30px #00ffff; 
      }
      100% { 
        border-color: #ff00ff; 
        box-shadow: 0 0 5px #ff00ff, 0 0 10px #ff00ff, 0 0 15px #ff00ff; 
      }
    }
    
    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      33% { transform: translateY(-10px); }
      66% { transform: translateY(-5px); }
    }
    
    @keyframes rainbow-text {
      0%, 100% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
    }
    
    @keyframes rainbow-border {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    @keyframes sparkle {
      0% { left: -100%; }
      100% { left: 100%; }
    }
    
    @keyframes typewriter {
      0% { width: 0; }
      100% { width: 100%; }
    }
    
    /* Responsive Design */
    @media (max-width: 768px) {
      .profile-container {
        margin: 5px;
        padding: 15px;
      }
      
      .tech-badge {
        margin: 3px;
        transform: scale(0.9);
      }
      
      .neon-border {
        padding: 15px;
        margin: 10px;
      }
    }
    
    /* Dark mode optimizations */
    @media (prefers-color-scheme: dark) {
      .profile-container {
        background: linear-gradient(45deg, #0a0a0a, #1a1a2e, #16213e);
      }
    }
  </style>

  <!-- Animated Wave with Enhanced Gradient -->
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Welcome%20to%20my%20Digital%20Universe&fontSize=38&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Where%20Code%20Meets%20Creativity&descSize=16&descColor=00ff00&descAlignY=60"/>

  <!-- Enhanced Animated Header with Multiple Effects -->
  <div class="profile-container floating">
    <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=35&duration=2500&pause=500&color=00D9FF&background=0D1117&center=true&vCenter=true&multiline=true&width=850&height=120&lines=Hi+👋%2C+I'm+P.R.P.S.Kalhara;💻+Full+Stack+Developer;🚀+Open+Source+Enthusiast;🎯+Problem+Solver+%26+Innovator" alt="Typing SVG" />
  </div>
  
  <!-- Enhanced Animated About Me Section -->
<div class="neon-border" style="margin: 20px auto; padding: 20px; background: linear-gradient(135deg, #0D1117, #1a1a2e, #16213e);">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3"/>

  ## 🚀 <span class="gradient-text">About Me</span>

  <table>
    <tr>
      <td width="60%">
        <div class="floating">
          
          - 👨‍💻 **All of my projects are available at** [GitHub](https://github.com/Kalharapasan)

          - 🎓 **Currently studying** Software Engineering

          - 🌱 **Currently learning** Cloud Technologies & DevOps

          - 💬 **Ask me about** Full Stack Development, Mobile Apps, and Open Source

          - 📧 **How to reach me** kalharap84@gmail.com

          - ⚡ **Fun fact** I love exploring new technologies and building innovative solutions!

          <br/>

          <!-- Achievement Badges -->
          <div align="center">
            <img src="https://img.shields.io/badge/🏆-Problem%20Solver-gold?style=for-the-badge&labelColor=black&color=gold" alt="Problem Solver" />
            <img src="https://img.shields.io/badge/🎯-Goal%20Oriented-blue?style=for-the-badge&labelColor=black&color=blue" alt="Goal Oriented" />
            <img src="https://img.shields.io/badge/💡-Innovation%20Driven-purple?style=for-the-badge&labelColor=black&color=purple" alt="Innovation Driven" />
          </div>
          
        </div>
      </td>
      <td width="40%" align="center">
        <div class="floating">
          <img alt="Coding" width="300" src="https://media.giphy.com/media/L1R1tvI9svkIWwpVYr/giphy.gif" style="border-radius: 15px; box-shadow: 0 0 20px rgba(0, 217, 255, 0.5);">
        </div>
      </td>
    </tr>
  </table>
</div>
  
  <!-- Matrix Rain Effect -->
  <div align="center">
    <img src="https://capsule-render.vercel.app/api?type=matrix&color=0:00ff00,100:008f11&height=200&section=header&text=LOADING...&fontSize=30&fontColor=ffffff&animation=fadeIn&fontAlignY=50&desc=Initializing%20Developer%20Mode&descAlignY=70&descSize=15"/>
  </div>

</div>

<br/>

<!-- Side-by-Side Animated Coding GIFs -->
<div align="center">
  <table>
    <tr>
      <td align="center">
        <img alt="Matrix Code Rain" width="350" src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif">
        <br/>
        <sub><b>Matrix Code Rain</b></sub>
      </td>
      <td align="center">
        <img alt="Hacker Typing" width="350" src="https://media.giphy.com/media/ZVik7pBtu9dNS/giphy.gif">
        <br/>
        <sub><b>Developer in Action</b></sub>
      </td>
    </tr>
  </table>
</div>

<br/>

<!-- Enhanced Profile Views with Animated Badges and Interactive Effects -->
<div align="center" class="profile-container">
  <div class="floating" style="display: inline-block;">
    <img src="https://komarev.com/ghpvc/?username=kalharapasan&label=Profile%20Views&color=blueviolet&style=for-the-badge&logo=eye" alt="profile views" class="tech-badge" />
  </div>
  <div class="floating" style="display: inline-block; animation-delay: 0.2s;">
    <img src="https://img.shields.io/github/followers/kalharapasan?label=Followers&style=for-the-badge&color=blue&logo=github" alt="followers" class="tech-badge" />
  </div>
  <div class="floating" style="display: inline-block; animation-delay: 0.4s;">
    <img src="https://img.shields.io/github/stars/kalharapasan?label=Total%20Stars&style=for-the-badge&color=yellow&logo=star" alt="stars" class="tech-badge" />
  </div>
  <div class="floating" style="display: inline-block; animation-delay: 0.6s;">
    <img src="https://img.shields.io/badge/Status-Available%20for%20Work-brightgreen?style=for-the-badge&logo=checkmarx" alt="status" class="tech-badge" />
  </div>
</div>

<!-- Animated Text Banners -->
<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=18&duration=2000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&width=600&height=80&lines=🚀+Building+the+future+with+code;💡+Turning+ideas+into+reality;🌟+Always+learning%2C+always+growing" alt="Animated Banner" />
</div>

<br/>

<!-- Enhanced Trophies with Animation -->
<div align="center">
  <a href="https://github.com/ryo-ma/github-profile-trophy">
    <img src="https://github-profile-trophy.vercel.app/?username=kalharapasan&theme=algolia&no-frame=true&no-bg=true&margin-w=4&column=7" alt="kalharapasan" />
  </a>
</div>

<br/>



## 📊 GitHub Analytics

<!-- Dynamic Stats with Animated Charts -->
<div align="center">
  <table>
    <tr>
      <!-- Left side - Animated Top Languages -->
      <td>
        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=kalharapasan&show_icons=true&locale=en&layout=compact&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00ff00&icon_color=00ff00&text_color=ffffff&border_radius=15" alt="Top Languages" />
      </td>
      <!-- Right side - Enhanced GitHub Stats -->
      <td>
        <img src="https://github-readme-stats.vercel.app/api?username=kalharapasan&show_icons=true&locale=en&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00ff00&icon_color=00ff00&text_color=ffffff&count_private=true&include_all_commits=true&border_radius=15" alt="GitHub Stats" />
      </td>
    </tr>
  </table>
</div>

<!-- 3D Contribution Calendar -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/wakatime?username=kalharapasan&theme=chartreuse-dark&hide_border=true&bg_color=0D1117&title_color=00ff00&text_color=ffffff" alt="Coding Time" />
</div>

<br/>

<!-- Enhanced GitHub Streak Stats with Working URLs -->
<div align="center">
  <img src="https://streak-stats.demolab.com?user=kalharapasan&theme=dark&hide_border=true&background=0D1117&stroke=00ff00&ring=ff6600&fire=ff6600&currStreakLabel=00ff00&sideNums=ffffff&currStreakNum=ffffff&sideLabels=ffffff&dates=ffffff&border_radius=15" alt="GitHub Streak Stats" />
</div>

<!-- Working Real-time Coding Activity -->
<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kalharapasan&theme=github_dark" alt="Profile Summary" />
</div>

<br/>



<!-- Enhanced Social Connect Section with Interactive Elements -->
<div class="neon-border" style="margin: 30px auto; padding: 25px; background: linear-gradient(135deg, #0D1117, #1a1a2e, #16213e);">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3"/>

  ## 🌐 <span class="gradient-text">Let's Connect & Collaborate</span>

  <div align="center" class="floating">
    
    <!-- Enhanced Social Badges with Hover Effects -->
    <a href="https://www.linkedin.com/in/pasan-kalhara/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&animation=pulse" alt="LinkedIn" class="tech-badge" />
    </a>
    <a href="https://github.com/Kalharapasan" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" class="tech-badge" />
    </a>
    <a href="mailto:kalharap84@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" class="tech-badge" />
    </a>
    
    <br/><br/>
    
    <!-- Additional Contact Methods -->
    <img src="https://img.shields.io/badge/💬-Let's%20Chat-success?style=for-the-badge&labelColor=black&color=success" alt="Let's Chat" class="tech-badge" />
    <img src="https://img.shields.io/badge/🚀-Hire%20Me-important?style=for-the-badge&labelColor=black&color=important" alt="Hire Me" class="tech-badge" />
    <img src="https://img.shields.io/badge/📝-Portfolio-blue?style=for-the-badge&labelColor=black&color=blue" alt="Portfolio" class="tech-badge" />
    
  </div>
</div>

<br/>

<!-- Tech Stack with Enhanced Visuals and Interactive Elements -->
<div class="neon-border" style="margin: 20px auto; padding: 25px; background: linear-gradient(135deg, #0D1117, #1a1a2e, #16213e);">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=3"/>

  ## 🛠️ <span class="gradient-text">Tech Arsenal</span>

  ### 💻 Programming Languages
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C" class="tech-badge" />
    <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" class="tech-badge" />
    <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" class="tech-badge" />
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" class="tech-badge" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" class="tech-badge" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" class="tech-badge" />
    <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" class="tech-badge" />
    <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" class="tech-badge" />
    
  </div>

  ### 🌐 Web Development
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" class="tech-badge" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" class="tech-badge" />
    <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" class="tech-badge" />
    <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" alt="Vue.js" class="tech-badge" />
    <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="TailwindCSS" class="tech-badge" />
    
  </div>

  ### ⚙️ Backend & Frameworks
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" class="tech-badge" />
    <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" class="tech-badge" />
    <img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white" alt="NestJS" class="tech-badge" />
    <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django" class="tech-badge" />
    <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" class="tech-badge" />
    <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring" class="tech-badge" />
    
  </div>

  ### 🗄️ Databases
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" class="tech-badge" />
    <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" class="tech-badge" />
    <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB" class="tech-badge" />
    <img src="https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white" alt="SQLServer" class="tech-badge" />
    <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB" class="tech-badge" />
    <img src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite" class="tech-badge" />
    
  </div>

  ### 📱 Mobile Development
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" class="tech-badge" />
    <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart" class="tech-badge" />
    <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" class="tech-badge" />
    <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android" class="tech-badge" />
    
  </div>

  ### ☁️ Cloud & DevOps
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS" class="tech-badge" />
    <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" class="tech-badge" />
    <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" class="tech-badge" />
    
  </div>

  ### 🛠️ Tools & Others
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" class="tech-badge" />
    <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" class="tech-badge" />
    <img src="https://img.shields.io/badge/GNU%20Bash-4EAA25?style=for-the-badge&logo=GNU%20Bash&logoColor=white" alt="Bash" class="tech-badge" />
    <img src="https://img.shields.io/badge/Qt-41CD52?style=for-the-badge&logo=qt&logoColor=white" alt="Qt" class="tech-badge" />
    <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" alt="Arduino" class="tech-badge" />
    
  </div>

  ### 🎨 Design Tools
  <div align="center" class="tech-container">
    
    <img src="https://img.shields.io/badge/Adobe%20Illustrator-FF9A00?style=for-the-badge&logo=adobe%20illustrator&logoColor=white" alt="Adobe Illustrator" class="tech-badge" />
    <img src="https://img.shields.io/badge/Adobe%20Photoshop-31A8FF?style=for-the-badge&logo=Adobe%20Photoshop&logoColor=black" alt="Adobe Photoshop" class="tech-badge" />
    
  </div>
</div>

<br/>

<!-- Enhanced Activity Graph with Neon Effects -->
<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=6,11,20&height=2"/>

## 📈 Contribution Heatmap

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kalharapasan&bg_color=000000&color=00ff00&line=00ff41&point=ff6600&area=true&hide_border=true&custom_title=💚%20Contribution%20Activity" alt="GitHub Activity Graph" />
</div>

<!-- Working GitHub Stats -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=kalharapasan&repo=kalharapasan&theme=dark&bg_color=000000&title_color=00ff00&icon_color=00ff00&text_color=ffffff&border_color=00ff00" alt="Pinned Repo" />
</div>

<!-- Simple Working Streak Counter -->
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=kalharapasan&theme=dark&background=000000&stroke=00ff00&ring=ff6600&fire=ff6600&currStreakLabel=00ff00" alt="Simple Streak Stats" />
</div>

<br/>

<!-- Enhanced Animated Footer with Particle Effect and Interactive Elements -->
<div class="profile-container" style="margin-top: 40px;">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=180&section=footer&text=Thanks%20for%20visiting!&fontSize=32&fontColor=00ff00&animation=blinking&fontAlignY=65&desc=Keep%20coding%2C%20keep%20growing!&descSize=16&descColor=ffffff&descAlignY=95"/>

  <div align="center" class="floating">
    
    <!-- Enhanced Animated Text -->
    <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=22&duration=2500&pause=1000&color=00FF00&center=true&vCenter=true&width=600&height=60&lines=✨+Made+with+❤️+and+lots+of+☕;🚀+Always+ready+for+new+challenges!;💻+Let's+build+something+amazing+together!;🌟+Innovation+never+stops!" alt="Footer Animation" />
    
    <br/><br/>
    
    <div class="gradient-text" style="font-size: 18px; margin: 20px 0;">
      <strong>⚡ Powered by Passion & Coffee ⚡</strong>
    </div>
    
    <!-- Enhanced Badge Section -->
    <div class="floating" style="margin: 20px 0;">
      <img src="https://forthebadge.com/images/badges/built-with-love.svg" alt="Built with Love" class="tech-badge">
      <img src="https://forthebadge.com/images/badges/powered-by-coffee.svg" alt="Powered by Coffee" class="tech-badge">
      <img src="https://forthebadge.com/images/badges/made-with-markdown.svg" alt="Made with Markdown" class="tech-badge">
    </div>
    
    <!-- Visitor Counter with Enhanced Styling -->
    <div class="neon-border" style="display: inline-block; padding: 15px; margin: 20px 0; background: linear-gradient(45deg, #000428, #004e92);">
      <img src="https://profile-counter.glitch.me/kalharapasan/count.svg" alt="Visitor Counter" style="filter: drop-shadow(0 0 10px #00ff00);" />
    </div>
    
    <!-- Additional Interactive Elements -->
    <div style="margin-top: 30px;">
      <img src="https://img.shields.io/badge/💼-Open%20for%20Opportunities-success?style=for-the-badge&labelColor=black&color=success" alt="Open for Opportunities" class="tech-badge" />
      <img src="https://img.shields.io/badge/🤝-Collaboration%20Ready-blue?style=for-the-badge&labelColor=black&color=blue" alt="Collaboration Ready" class="tech-badge" />
      <img src="https://img.shields.io/badge/📚-Continuous%20Learner-orange?style=for-the-badge&labelColor=black&color=orange" alt="Continuous Learner" class="tech-badge" />
    </div>
    
  </div>
</div>

<!-- Matrix-style footer -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=matrix&color=0:008f11,100:00ff41&height=100&section=footer&animation=fadeIn"/>
</div>
