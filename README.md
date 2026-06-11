# Hi, I'm Nishant Kumar 👋
### Computer Science Undergraduate | Full-Stack Developer | IoT Enthusiast | Defence Technology Explorer

---

## 👨‍💻 Profile Summary

I am a highly driven **Computer Science Undergraduate** at **KL University** specializing in **Artificial Intelligence & Machine Learning**. I have a strong passion for designing scalable backend systems, developing responsive interactive frontends, and building hardware-level IoT/embedded solutions.

* 🎓 **B.Tech CSE** at KL University, Vaddeswaram
* 💻 **Full-Stack Development** using React, Spring Boot, and modern CSS systems
* ☕ **Backend Architecture** focusing on REST APIs, JWT authentication, and RBAC
* 📡 **IoT & Embedded Systems** flashing firmware onto ESP32 and Arduino boards
* 🏛 **Defence Technology Explorer** fascinated by aerospace & military tech innovation
* 🚀 **Product Building Mindset** focused on shipping functional, polished solutions

---

## 🛠 Skills & Profile Badges

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/python-%233776AB.svg?style=for-the-badge&logo=python&logoColor=white)
![MySQL](https://img.shields.io/badge/mysql-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![IoT](https://img.shields.io/badge/IoT-Smart%20Systems-%2300b4d8.svg?style=for-the-badge&logo=arduino&logoColor=white)
![AI/ML](https://img.shields.io/badge/AI%20%2F%20ML-Intelligence-%23a855f7.svg?style=for-the-badge&logo=micro-soft&logoColor=white)

---

## 🚀 Project Overview: Neo-Brutalist Portfolio

> [!NOTE]
> This repository houses my personal portfolio site — a custom-crafted playground built entirely using vanilla **HTML**, **CSS**, and **JavaScript** (no heavy frameworks, no bloated dependencies). 

### 💡 The Problem
Standard developer portfolios look identical: rounded corners, smooth pastel gradients, minimalist gray grids, and cookie-cutter templates. They lack distinct personality and fail to show a strong mastery of front-end engineering fundamentals.

### 🎯 Purpose of the Project
To construct a highly memorable, high-impact personal landing page that stands out to technical recruiters. It serves as a visual showcase of my engineering projects, skills, certifications, and interest areas using a customized **Neo-Brutalist Scrapbook** design language.

### 🌟 Real-World Impact
Demonstrates raw front-end performance, custom animation engineering (custom 3D transforms, gravity-based falling physics), interactive map controllers, and a retro retro-terminal mode that runs an embedded game.

---

## ✨ Key Features

* **🎨 Responsive Neo-Brutalist Design**: Thick black borders (`4px solid`), flat offset shadows, high-contrast HSL-curated color palettes, and playful scrapbook details.
* **🗺 Interactive Project Map**: Embedded Leaflet.js coordinate map showing project hotspots. Clicking timeline entries triggers map fly-to marker animations.
* **📖 3D Book-Flip Timeline**: Interactive "Projects Journey" section that starts as a closed treasure map and dynamically flips open like a book page as the user scrolls.
* **⚡ Interactive Retro Terminal**: Access a retro command-line terminal featuring horizontal/vertical panes, theme switches (Dracula, Nord, Solarized), and an embedded Snake game powered by p5.js.
* **🛸 Scroll-Driven Highlights**: Highlights and markup lines dynamically animate left-to-right as they enter the viewport, simulating a highlighter pen.
* **📲 Tactile Discord Clipboard Copy**: A customized Discord card that copies `og_nishantjod_47792` to the clipboard on-click, showing `"Copied!"` visual feedback.

---

## 🏗 Portfolio Architecture

The application is completely static, optimized for high-speed page loads and visual responsiveness.

```mermaid
graph TD
    User([Visitor / Recruiter]) --> Navbar{Navigation}
    
    %% Main Sections
    Navbar --> Hero[Hero Section]
    Navbar --> About[About Section]
    Navbar --> Projects[Projects Journey & Interactive Map]
    Navbar --> Skills[Skills & CS Fundamentals]
    Navbar --> Certs[Certifications Showcase]
    Navbar --> Contact[Get In Touch Grid]
    
    %% Interactive Elements
    Hero --> MatrixText[Matrix Scrambler Text]
    Hero --> PhysicsIcons[Gravity-based Falling SVGs]
    Projects --> BookFlip[3D Book-page Flip Animation]
    BookFlip --> MapControl[Leaflet.js Map]
    MapControl --> FlyToCoord[Fly-to Marker Coords]
    Contact --> DiscordClick[Discord Card Copy Clipboard]
    
    %% Subpages
    Navbar --> Terminal[Interactive Retro Terminal Mode]
    Terminal --> SnakeGame[p5.js Embedded Snake Game]
    Terminal --> CmdHistory[Command Line Interpreter]
    Terminal --> ColorThemes[Theme Switcher]
```

---

## 🛠 Tech Stack

### Frontend
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23F7DF1E.svg?style=flat&logo=javascript&logoColor=black)

### Libraries & Fonts
* **Leaflet.js** — Interactive map engine
* **p5.js** — Snake game rendering in retro terminal
* **Font Awesome** — Typography and brand icons
* **Google Fonts** — Space Grotesk, Space Mono, Caveat

### Deployment
![GitHub Pages](https://img.shields.io/badge/github%20pages-%23121011.svg?style=flat&logo=github&logoColor=white)

---

## 📸 Screenshots

<p align="center">
  <em>Interactive Portfolio Interface Showcase</em>
</p>

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│   [ HERO SECTION ] - Animated Photo, Falling SVGs, Matrix Intro  │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   [ ABOUT ME ] - Highlighter Animation & Custom Profiles        │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   [ TIMELINE & MAP ] - 3D Book Flip Page & Leaflet.js Mapping    │
│                                                                 │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│   [ CERTIFICATIONS ] - Custom Tally Badges & Credential Grid     │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
```

---

## 👨‍💻 About the Developer

**Nishant Kumar**
B.Tech CS Student with deep interests in full-stack engineering, firmware development, and geopolitical strategy.

### Emojis/Interests:
* 🏛 **Defence Technology** & Military hardware
* 🚁 **Aerospace & Military Innovation**
* 🤖 **Artificial Intelligence** & Backend AI
* 🌐 **Full-Stack Development** & System Design
* 📡 **IoT & Embedded Systems** (Arduino/ESP32)
* 🌍 **Geopolitics** & International Relations
* 📰 **World Affairs & Current Events**
* 🚀 **Startups & Product Building**

---

## 🤝 Connect With Me

Let's collaborate or discuss software engineering roles!

* 💼 **LinkedIn**: [Nishant Kumar](https://www.linkedin.com/in/nishant-kumar-a166a3305)
* 💻 **GitHub**: [@NISHANT-187](https://github.com/NISHANT-187)
* 🍳 **CodeChef**: [@kl2400033286](https://www.codechef.com/users/kl2400033286)
* 📧 **Email**: [nishant1872005@gmail.com](mailto:nishant1872005@gmail.com)
* 💬 **Discord**: `og_nishantjod_47792` (Display: `OG_NishantJOD`)

---

## 📊 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NISHANT-187&show_icons=true&theme=radical" alt="Nishant's GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NISHANT-187&layout=compact&theme=radical" alt="Top Languages" />
</p>

---

## 📌 Project Status

* **Status**: Completed / Active Maintenance
* **Future Enhancements**:
  - Integrate a custom physics simulation sandbox on the home page.
  - Expand terminal command capabilities with automated file downloads.
  - Deeper local map integration with customized Stamen raster maps.

---

## 📄 License

This project is **proprietary**. All rights reserved. You may browse the source code for inspiration, but copying, modifying, or redistributing any part of it without written permission is not allowed. See the [LICENSE](LICENSE) file for details.
