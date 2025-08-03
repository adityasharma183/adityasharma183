<!-- ───────────────────── Header ► Animated SVG with Pulse & Rotation ───────────────────── -->
<div align="center">
<svg width="200" height="200" viewBox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
  <defs>
    <radialGradient id="grad" fx="50%" fy="50%" r="60%">
      <stop offset="0%" stop-color="#00B4D8">
        <animate attributeName="stop-color"
                 values="#00B4D8;#90E0EF;#00B4D8"
                 dur="4s"
                 repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0077B6">
        <animate attributeName="stop-color"
                 values="#0077B6;#03045E;#0077B6"
                 dur="4s"
                 repeatCount="indefinite"/>
      </stop>
    </radialGradient>
  </defs>
  <g transform="translate(100,100)">
    <circle r="70" stroke="url(#grad)" stroke-width="8" fill="none" opacity="0.7">
      <animateTransform attributeName="transform"
                        type="rotate"
                        from="0"
                        to="360"
                        dur="8s"
                        repeatCount="indefinite"/>
    </circle>
    <circle r="40" stroke="#0077B6" stroke-opacity="0.8" stroke-width="4" fill="none">
      <animate attributeName="r"
               values="36;44;36"
               dur="1.6s"
               repeatCount="indefinite"/>
      <animate attributeName="stroke-opacity"
               values="0.3;1;0.3"
               dur="1.6s"
               repeatCount="indefinite"/>
    </circle>
    <text text-anchor="middle" dy="0.35em" fill="#03045E" font-size="36" font-family="sans-serif" font-weight="bold">AS</text>
  </g>
</svg>
</div>

<!-- ───────────────────── Animated Typing Lines (SVG + SMIL) ───────────────────── -->
<p align="center">
<svg xmlns="http://www.w3.org/2000/svg" width="400" height="90">
  <text x="50%" y="24" text-anchor="middle" fill="#03045E" font-size="20" font-family="sans-serif">
    <tspan id="line1" opacity="0">Working on AI‑based Resume‑Analyzer</tspan>
    <tspan id="line2" dy="1.4em" x="50%" opacity="0">Learning Three.js & Framer Motion</tspan>
    <tspan id="line3" dy="2.8em" x="50%" opacity="0">Ask about React · Node.js · MongoDB</tspan>
    <animate xlink:href="#line1"
             attributeName="opacity"
             values="0;1;1;0"
             keyTimes="0;0.2;0.7;1"
             dur="6s"
             begin="0s"
             repeatCount="indefinite"/>
    <animate xlink:href="#line2"
             attributeName="opacity"
             values="0;0;1;1;0;0"
             keyTimes="0;0.2;0.4;0.7;0.9;1"
             dur="6s"
             begin="0s"
             repeatCount="indefinite"/>
    <animate xlink:href="#line3"
             attributeName="opacity"
             values="0;0;0;1;1;0"
             keyTimes="0;0.3;0.5;0.8;0.9;1"
             dur="6s"
             begin="0s"
             repeatCount="indefinite"/>
  </text>
</svg>
</p>

---

## 🔍 AI‑Based Resume Analyzer  
ML-powered tool that analyzes and scores resumes instantly.  
**Visit Portfolio:** [adityasharma183‑portfolio.netlify.app](https://adityasharma183-portfolio.netlify.app/)

---

## 🌱 Learning  
- Three.js for browser-based 3D visuals  
- Framer Motion for smooth UI transitions and micro‑animations

---

## 🧰 Tech Stack  

```text
MERN  •  REST APIs  •  JWT  •  Tailwind CSS  •  Git  •  MongoDB  •  Three.js  •  Framer Motion

<p align="center"> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/express/express-original.svg" alt="Express" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/threejs/threejs-original.svg" alt="Three.js" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/motionui/motionui-plain.svg" alt="Framer Motion" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" width="40"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" alt="Tailwind CSS" width="40"/> </p>💬 Ask me about
React hooks & Redux · REST API design with Express & JWT · Database modelling with MongoDB · Browser animations with Three.js and Framer Motion

🌐 Where to Find Me
[![LinkedIn][linkedin-shield]][linkedin-url]
[![Instagram][instagram-shield]][instagram-url]
[![LeetCode][leetcode-shield]][leetcode-url]

⚡ Motto
“Stay curious. Keep building. Embrace the bugs — they make you better.”
