<div align="center">
  <img src="https://raw.githubusercontent.com/Ammar-1993/Ammar-1993/main/images/hellocoders_rounded.gif" alt="Hello Coders" width="38%" />

  <h1>Hi there, I'm Eng. Ammar Al-Najjar 👋</h1>

  <a href="https://readme-typing-svg.herokuapp.com/demo/">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=FF2D20&center=true&vCenter=true&width=650&lines=Senior+Full-Stack+Software+Engineer;Laravel+12+%2B+Next.js+14+Specialist;Architecting+Scalable+Real-Time+Systems;Deepening+Cloud+Architecture+%26+DevOps" alt="Typing SVG" />
  </a>

  <p>
    <b>Full-Stack Systems Architect with 5+ years building distributed production platforms.</b><br>
    Specializing in decoupled monorepos, real-time communication (WebRTC/Agora), and AI-driven automation.<br>
    <i>B.Sc. in Software Engineering (Very Good) • Authenticated by Mosadaqa Platform (KSA)</i>
  </p>

  <p>
    <a href="https://github.com/Ammar-1993/Ammar-1993/commits?author=Ammar-1993"><img src="https://img.shields.io/badge/last%20commit-today-20232a?style=for-the-badge&logo=git&logoColor=white" alt="Last Commit"></a>
    <a href="https://github.com/Ammar-1993?tab=followers"><img src="https://img.shields.io/github/followers/Ammar-1993?style=for-the-badge&logo=github&color=orange&label=Followers" alt="Followers"></a>
    <img src="https://komarev.com/ghpvc/?username=Ammar-1993&style=for-the-badge&color=blueviolet&label=PROFILE+VIEWS" alt="Profile Views">
  </p>

  <p>
    <a href="https://www.linkedin.com/in/ammar-al-najjar-0b7b941b6/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
    <a href="mailto:ammaralnggar@gmail.com"><img src="https://img.shields.io/badge/Email-ammaralnggar@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
    <a href="https://ammar1993.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit_My_Site-3E7FFF?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"></a>
    <a href="https://wa.me/967714294340"><img src="https://img.shields.io/badge/WhatsApp-+967714294340-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>
  </p>
</div>

---

## 🧐 Executive Profile & Engineering Impact

I bridge the gap between complex business requirements and high-performance technical architecture. Rather than just writing code, I focus on system reliability, database query optimization, and defensive engineering.

### 🌟 Key Engineering Benchmarks:
- 🎓 **Real-Time Scalability:** Architected **[Taj-Platform](https://api.taj-edu.online/)** to seamlessly support **200+ concurrent live virtual classrooms** with **<100ms latency** by decoupling media traffic from the backend API.
- ⚖️ **High-Engagement & Optimization:** Developed and open-sourced **[LawProSystem](https://github.com/Ammar-1993/lawprosystem)** (my #1 most active community repo ⭐ 9 Stars, 🍴 2 Forks), achieving a **40% database query optimization** through advanced Laravel Eloquent indexing and eager loading.
- 🧩 **Shared-Kernel Micro-Architecture:** Designed **[Jobs-Platform](https://hireme-platform.online/)** across a multi-repository ecosystem with AI-powered resume analysis and automated feedback loops.

> **🔧 Current Engineering Focus:** Containerizing and modernizing LawProSystem's dev environment (**WSL2 + Docker + Architecture Refactoring**) while deepening **Cloud DevOps** and **Distributed Systems Design**.

---

## 🚀 Flagship Architecture — Taj-Platform

An Arabic-first, RTL e-learning marketplace built as a highly decoupled monorepo. The Next.js 14 frontend communicates with the Laravel 12 API over REST, while the virtual classroom (live video, screen sharing, and interactive whiteboard) connects **directly browser-to-provider** through Agora and Netless—keeping the backend API server completely free of heavy media traffic.

```mermaid
graph LR
    FE[Next.js Frontend]

    subgraph Live["🎓 Live Classroom — Direct Connections"]
        RTC[Agora RTC]
        RTM[Agora RTM]
        WB[Netless Whiteboard]
    end

    subgraph BE["⚙️ Laravel Backend"]
        API[REST API v1]
        ADMIN[Filament Admin]
        QUEUE[Queue Worker]
    end

    DB[(MySQL)]
    PAY[Moyasar]
    MON[Sentry]

    FE -->|REST| API
    FE <--> RTC
    FE <--> RTM
    FE <--> WB
    API --> DB
    ADMIN --> DB
    API --> QUEUE
    QUEUE --> WB
    API --> PAY
    API -.-> MON
    FE -.-> MON

```

---

### 💻 Tech Stack

<div align="center">

| **Languages** | **Frontend** | **Backend** | **Database & Cloud** | **Real-Time** | **Tools** |
|:---:|:---:|:---:|:---:|:---:|:---:|
| ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) <br> ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) <br> ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) <br> ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) <br> ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) | ![Laravel](https://img.shields.io/badge/laravel-%23FF2D20.svg?style=for-the-badge&logo=laravel&logoColor=white) <br> ![Node.js](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) <br> ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) | ![MySQL](https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white) <br> ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) <br> ![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) | ![Agora](https://img.shields.io/badge/Agora%20RTC-099DFD?style=for-the-badge&logo=webrtc&logoColor=white) <br> ![WebSockets](https://img.shields.io/badge/WebSockets-black?style=for-the-badge&logo=socketdotio&logoColor=white) | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) <br> ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) <br> ![VS Code](https://img.shields.io/badge/VS%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white) |

</div>

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-tawny-six-84.vercel.app/api?username=Ammar-1993&show_icons=true&theme=react&hide_border=true&count_private=true&cache_seconds=21600" alt="Ammar's GitHub Stats" />
</p>

<p align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://my-streak-stats-red.vercel.app?user=Ammar-1993&theme=react&hide_border=true&v=2" alt="Ammar's GitHub Streak" />
  </a>
</p>

<p align="center">
  <img src="https://github-readme-stats-tawny-six-84.vercel.app/api/top-langs/?username=Ammar-1993&layout=compact&theme=react&hide_border=true&hide=html,css&cache_seconds=21600" alt="Top Languages" />
</p>

---

### 🛠 Selected Projects

| Project | Description | Tech Stack |
|:--- |:--- |:--- |
| **[TajPlatform](https://github.com/Ammar-1993/Taj-Platform)** | Arabic-first e-learning marketplace: live classrooms, whiteboard, role-based access | Laravel 12, Next.js 14, Agora RTC |
| **[JobsPlatform](https://github.com/Ammar-1993/job-app)** | Recruitment system split into a shared-kernel architecture | Laravel 12, MySQL, Tailwind CSS, OpenAI |
| **[LawProSystem](https://github.com/Ammar-1993/lawprosystem)** | Law-firm management: cases, clients, tasks & reports — my top community-engagement repo | Laravel, MySQL, JS |
| **[FaceCryptCloud](https://github.com/Ammar-1993/Face-Crypt-Cloud-Arabic)** | Secure cloud storage gated by facial-recognition authentication | Python, OpenCV, Cloud |

> [!TIP]
> Check out my [Portfolio](https://ammar1993.vercel.app/) for live demos!

---

<div align="center">
  <sub>All rights reserved © 2026 Engineer Ammar Al-Najjar</sub>
</div>
