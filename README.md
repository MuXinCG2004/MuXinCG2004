<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MuXinCG's Profile</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f8f9fa;
        }
        .container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 2px 15px rgba(0,0,0,0.1);
            padding: 30px;
            margin-bottom: 20px;
        }
        .header-img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 20px;
        }
        .section-title {
            color: #2c3e50;
            border-bottom: 3px solid #3498db;
            padding-bottom: 10px;
            margin-top: 30px;
        }
        .skills-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin: 20px 0;
        }
        .skill-item {
            background-color: #f1f8ff;
            padding: 15px;
            border-radius: 8px;
            transition: transform 0.3s;
        }
        .skill-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .stats-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        .stats-card {
            background-color: white;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
        }
        .quote-box {
            background-color: #f8f9fa;
            border-left: 4px solid #3498db;
            padding: 20px;
            margin: 20px 0;
            font-style: italic;
        }
        .fun-fact {
            background-color: #fff3cd;
            border: 1px solid #ffeaa7;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
        }
        .tech-icon {
            width: 50px;
            height: 50px;
            margin: 10px;
            transition: transform 0.3s;
        }
        .tech-icon:hover {
            transform: scale(1.1);
        }
        .tech-section {
            margin: 20px 0;
        }
        .profile-views {
            background-color: #6f42c1;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            display: inline-block;
            margin: 10px 0;
        }
        .snake-animation {
            width: 100%;
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Welcome Banner -->
        <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/others/Welcome.svg" alt="Welcome Banner" class="header-img">
        
        <!-- Typing Animation -->
        <div style="text-align: center; margin: 30px 0;">
            <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=435&lines=Hi%2C+I'm+MuXinCG.;I'm+a+full-stack+engineer.;I'm+also+a+student+at+SDU.;My+focus+is+AI+Agent+research.;Welcome+to+my+blog!)" alt="Typing Animation">
        </div>
        
        <!-- About Me Section -->
        <h2 class="section-title">About Me</h2>
        <div class="tech-section">
            <ul style="list-style-type: none; padding: 0;">
                <li style="margin: 10px 0; padding-left: 20px; position: relative;">
                    <strong>Development Experience:</strong> 3 years of experience in C/C++/Golang development, proficient in Python and Rust
                </li>
                <li style="margin: 10px 0; padding-left: 20px; position: relative;">
                    <strong>System Environment:</strong> Over 2 years of experience with Linux systems, familiar with Docker containerized deployment
                </li>
                <li style="margin: 10px 0; padding-left: 20px; position: relative;">
                    <strong>Education Background:</strong> Currently pursuing a Bachelor's degree in Computer Science and Technology at Shandong University
                </li>
                <li style="margin: 10px 0; padding-left: 20px; position: relative;">
                    <strong>Technical Interests:</strong> Algorithm optimization, open-source contributions
                </li>
            </ul>
        </div>
        
        <!-- Divider -->
        <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/others/colorful_line.gif" alt="Divider" style="width: 100%; margin: 20px 0;">
        
        <!-- My Skill Sets -->
        <h2 class="section-title">My Skill Sets</h2>
        
        <!-- Languages -->
        <h3>Languages</h3>
        <div class="skills-grid">
            <a href="https://en.cppreference.com/w/c" target="_blank">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" class="tech-icon">
            </a>
            <a href="https://en.cppreference.com/w/" target="_blank">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" class="tech-icon">
            </a>
            <a href="https://www.java.com/" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/languages/java.svg" alt="Java" class="tech-icon">
            </a>
            <a href="https://www.python.org/" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/languages/python.svg" alt="Python" class="tech-icon">
            </a>
            <a href="https://www.rust-lang.org/" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/languages/rust.svg" alt="Rust" class="tech-icon">
            </a>
        </div>
        
        <!-- Libraries -->
        <h3>Libraries</h3>
        <div class="skills-grid">
            <a href="https://nodejs.org/en" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/libraries/node.js.gif" alt="Node.js" class="tech-icon">
            </a>
        </div>
        
        <!-- Database -->
        <h3>Database</h3>
        <div class="skills-grid">
            <a href="https://www.mysql.com/" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/databases/mysql.svg" alt="MySQL" class="tech-icon">
            </a>
        </div>
        
        <!-- Tools -->
        <h3>Tools</h3>
        <div class="skills-grid">
            <a href="https://git-scm.com/" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/tools/Github.svg" alt="Git" class="tech-icon">
            </a>
            <a href="https://www.docker.com/" target="_blank">
                <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/tools/docker.svg" alt="Docker" class="tech-icon">
            </a>
            <a href="https://www.linux.org/" target="_blank">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" class="tech-icon">
            </a>
            <a href="https://code.visualstudio.com/" target="_blank">
                <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="VS Code" class="tech-icon">
            </a>
        </div>
        
        <!-- Divider -->
        <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/others/colorful_line.gif" alt="Divider" style="width: 100%; margin: 20px 0;">
        
        <!-- GitHub Stats -->
        <h2 class="section-title">My GitHub Stats</h2>
        
        <div style="text-align: center;">
            <div class="profile-views">
                PROFILE VIEWS: <span id="profile-views">0</span>
            </div>
        </div>
        
        <div class="stats-container">
            <div class="stats-card">
                <img src="https://gh-readme-profile.vercel.app/api?username=MuXinCG2004&theme=neon-dark&border_width=0&border_radius=15.2&hide_border=true" alt="GitHub Stats" style="width: 100%;">
            </div>
            <div class="stats-card">
                <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=MuXinCG2004&theme=2077" alt="Profile Details" style="width: 100%;">
            </div>
        </div>
        
        <!-- Snake Animation -->
        <div class="snake-animation">
            <img src="https://raw.githubusercontent.com/BEPb/BEPb/output/github-contribution-grid-snake.svg" alt="GitHub Contribution Snake" style="width: 100%;">
        </div>
        
        <!-- Random Dev Quote -->
        <div class="quote-box">
            <h3>Random Dev Quote</h3>
            <div id="quote-content">Loading quote...</div>
        </div>
        
        <!-- Fun Fact -->
        <div class="fun-fact">
            <h3>Fun Fact</h3>
            <p>"Code is like humor. When you have to explain it, it's bad." – Cory House</p>
        </div>
        
        <!-- Footer -->
        <img src="https://raw.githubusercontent.com/HighAmbition211/HighAmbition211/auxiliary/others/Finish.svg" alt="Finish Banner" class="header-img">
    </div>

    <script>
        // Simulate profile views counter
        document.addEventListener('DOMContentLoaded', function() {
            // Start counter animation
            let views = 0;
            const targetViews = Math.floor(Math.random() * 1000) + 500;
            const counter = document.getElementById('profile-views');
            const interval = setInterval(() => {
                views += Math.floor(Math.random() * 10) + 1;
                if (views >= targetViews) {
                    views = targetViews;
                    clearInterval(interval);
                }
                counter.textContent = views;
            }, 50);
            
            // Load random quote
            const quotes = [
                "First, solve the problem. Then, write the code. – John Johnson",
                "Any fool can write code that a computer can understand. Good programmers write code that humans can understand. – Martin Fowler",
                "Programming isn't about what you know; it's about what you can figure out. – Chris Pine",
                "The only way to learn a new programming language is by writing programs in it. – Dennis Ritchie",
                "Software is a great combination between artistry and engineering. – Bill Gates",
                "Make it work, make it right, make it fast. – Kent Beck"
            ];
            
            const randomQuote = quotes[Math.floor(Math.random() * quotes.length)];
            document.getElementById('quote-content').textContent = randomQuote;
        });
    </script>
</body>
</html>
