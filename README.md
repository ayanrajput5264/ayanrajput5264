<p align="center">
  <svg width="550" height="350" viewBox="0 0 700 500" xmlns="http://www.w3.org/2000/svg">
    <!-- Laptop Body -->
    <rect x="100" y="80" width="500" height="300" rx="15" fill="#1e1e1e" stroke="#888" stroke-width="4"/>
    <rect x="130" y="110" width="440" height="240" rx="8" fill="#0d0d0d"/>

    <!-- Screen Text Animation -->
    <text x="150" y="150" font-family="Consolas, monospace" font-size="20" fill="#00ff90">
      <tspan id="typing"></tspan>
    </text>

    <script type="text/ecmascript"><![CDATA[
      const text = [
        "Initializing Web3...",
        "Connecting to Blockchain...",
        "Loading Smart Contracts...",
        "Compiling Solidity...",
        "Deploying DApp...",
        "Success! 🎉"
      ];

      let line = 0, char = 0;
      const speed = 80; 
      const tspan = document.getElementById("typing");

      function typeWriter() {
        if (line < text.length) {
          if (char <= text[line].length) {
            tspan.textContent = text[line].slice(0, char++);
            setTimeout(typeWriter, speed);
          } else {
            char = 0;
            line++;
            tspan.textContent += "\n";
            setTimeout(typeWriter, 700);
          }
        }
      }

      typeWriter();
    ]]></script>
  </svg>
</p>o## Hi there 👋

<Hi 👋, I'm Ayan Rajput

Web Developer • Learner • Creator


---

<p align="center">
  <img src="rotating_demo.gif" width="250" />
</p>
---

🚀 About Me

🌱 I’m currently learning Web Development

⚡ Passion: Coding, Designing & Building Creative Projects

🎯 Goal: Become a Professional Developer



---

🛠️ Tech Stack

Frontend: HTML, CSS, JavaScript

Tools: VS Code, Git & GitHub

Learning: React, Backend Skills



---

🔗 Connect With Me

GitHub: Ayan-Rajput!--
**ayanrajput5264/ayarajput5264** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
