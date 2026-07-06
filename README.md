<div align="center">



# Sakthivel S V
**Full-Stack Developer · Computer Vision · Applied Security**

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1200&color=2F81F7&background=0D1117&center=true&vCenter=true&width=650&lines=Full-Stack+Developer+%26+Computer+Vision+Engineer;Building+real-time+ADAS+pipelines+with+YOLOv8+and+OpenCV;RAG+search%2C+OSINT+tooling%2C+clean+APIs)](https://git.io/typing-svg)

<br/>

[![GitHub](https://img.shields.io/badge/github-SpoodermanCodes-2f81f7?style=flat-square&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/SpoodermanCodes)
[![Gmail](https://img.shields.io/badge/email-svsakthivel716%40gmail.com-2f81f7?style=flat-square&logo=gmail&logoColor=white&labelColor=0d1117)](mailto:svsakthivel716@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-connect-2f81f7?style=flat-square&logo=linkedin&logoColor=white&labelColor=0d1117)](https://linkedin.com/)
![Views](https://komarev.com/ghpvc/?username=SpoodermanCodes&style=flat-square&color=2f81f7&labelColor=0d1117&label=views)

</div>
<br/>

---

### `01` — init

```yaml
name:       Sakthivel S V
handle:     "@SpoodermanCodes"
location:   Coimbatore, India
education:  B.Tech IT @ Coimbatore Institute of Technology — CGPA 8.39/10 (6th sem)
focus:      Full-Stack Development · Computer Vision · Applied Security
building:   Real-time perception systems, RAG-powered apps, OSINT tooling
fun_fact:   "Still in undergrad, already shipping production-grade demos."
```

---

### `02` — arsenal

<div align="center">

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=java,py,c,cs,ts,js,html,css&theme=dark" />

<br/><br/>

**Frameworks & Runtime**
<br/>
<img src="https://skillicons.dev/icons?i=react,nextjs,nodejs,express,unity&theme=dark" />

<br/><br/>

**Data & Infrastructure**
<br/>
<img src="https://skillicons.dev/icons?i=postgres,mongodb,mysql,redis,firebase,docker,git,github&theme=dark" />

</div>

---

### `03` — pipeline

The shape of my flagship project — a real-time ADAS stack where multiple perception modules feed a single fusion controller before anything reaches the driver.

```mermaid
flowchart LR
    A["Camera Feed — 1080p"] --> B{{"Perception Modules"}}
    B --> C["Lane Detection\nHough Transform"]
    B --> D["YOLOv8 Object Tracking\nCentroid Matching"]
    B --> E["CNN Traffic Sign\nRecognition"]
    C --> F["Sensor Fusion Controller\nEMA-smoothed telemetry"]
    D --> F
    E --> F
    F --> G["Live HUD Overlay"]
    F --> H["Proximity Audio Warning"]
    F --> I["Lane-Keeping Steering Cmd"]

    classDef core fill:#0d1117,stroke:#2f81f7,color:#fff,stroke-width:2px
    class B,F core
```

96.2% lane detection accuracy at 34 FPS · 95.8% tracking precision at 29ms/frame · ±0.58m distance error · ±0.24s TTC error.

---

### `04` — projects

<table>
<tr>
<td width="33%" valign="top">

**🚗 ADAS Real-Time Pipeline**
<br/>
<sub>Python · YOLOv8 · OpenCV · PyTorch</sub>

Lane detection, object tracking, sign recognition, and TTC forecasting fused into live HUD overlays and steering commands.

[![Repo](https://img.shields.io/badge/repo-adas--driver--assistance--system-2f81f7?style=flat-square&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/SpoodermanCodes/adas-driver-assistance-system)

</td>
<td width="33%" valign="top">

**🔎 OSINT Intelligence Framework**
<br/>
<sub>TypeScript · Node.js · Playwright · Express</sub>

Multi-source identity aggregation across 11 public sources with Levenshtein-based clustering and Redis-backed caching (87% hit rate).

[![Repo](https://img.shields.io/badge/repo-osint--eye-2f81f7?style=flat-square&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/SpoodermanCodes/osint-eye)

</td>
<td width="33%" valign="top">

**🖥️ GPU E-Commerce Store**
<br/>
<sub>Next.js · PostgreSQL · pgvector · OpenAI</sub>

Semantic vector search across 100+ GPU/CPU/motherboard listings with RAG-driven recommendations and a 96 Lighthouse score.

[![Repo](https://img.shields.io/badge/repo-duncan-2f81f7?style=flat-square&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/SpoodermanCodes/duncan)

</td>
</tr>
</table>

<div align="center">
<sub>Also shipped: <a href="https://github.com/SpoodermanCodes/2d-archive">2d-archive</a> — a retro arcade platform (Snake, Pong, Tetris, Flappy Bird, Space Invaders) with real-time 1v1 multiplayer · <a href="https://github.com/SpoodermanCodes/rural-health-connect">rural-health-connect</a> — a 3-portal rural healthcare system with AI-powered monitoring</sub>
</div>

---

### `05` — tools & infrastructure

<div align="center">

<table>
<tr>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=docker&theme=dark" width="36" height="36" alt="Docker"/><br/><sub>Docker</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=postgres&theme=dark" width="36" height="36" alt="PostgreSQL"/><br/><sub>PostgreSQL</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=mongodb&theme=dark" width="36" height="36" alt="MongoDB"/><br/><sub>MongoDB</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=mysql&theme=dark" width="36" height="36" alt="MySQL"/><br/><sub>MySQL</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=redis&theme=dark" width="36" height="36" alt="Redis"/><br/><sub>Redis</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=firebase&theme=dark" width="36" height="36" alt="Firebase"/><br/><sub>Firebase</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=git&theme=dark" width="36" height="36" alt="Git"/><br/><sub>Git</sub></td>
<td align="center" width="80"><img src="https://skillicons.dev/icons?i=unity&theme=dark" width="36" height="36" alt="Unity"/><br/><sub>Unity</sub></td>
</tr>
</table>

</div>

---

### `06` — security & interests

<div align="center">

**Security Tools** <sub>(familiar with)</sub>
<br/>
<img src="https://img.shields.io/badge/Nmap-2f81f7?style=for-the-badge&logo=nmap&logoColor=white" />
<img src="https://img.shields.io/badge/Metasploit-1f6feb?style=for-the-badge&logo=metasploit&logoColor=white" />
<img src="https://img.shields.io/badge/Wireshark-1158c7?style=for-the-badge&logo=wireshark&logoColor=white" />
<img src="https://img.shields.io/badge/Burp_Suite-0d3f91?style=for-the-badge&logo=burpsuite&logoColor=white" />

<br/><br/>

**Areas of Interest**
<br/>
<img src="https://img.shields.io/badge/Backend_Architecture-2f81f7?style=for-the-badge&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Computer_Vision-1f6feb?style=for-the-badge&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Penetration_Testing-1158c7?style=for-the-badge&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Digital_Forensics-0d3f91?style=for-the-badge&labelColor=0d1117" />
<img src="https://img.shields.io/badge/Game_Dev_(Unity)-133a70?style=for-the-badge&labelColor=0d1117" />

</div>

---

### `07` — achievements

| | |
|---|---|
| 🏆 **Smart India Hackathon** | 1st place (2025) · 3rd place (2024) — combined ₹6,500 prize pool |
| 🌐 **AstroNova Symposium** | Volunteer web developer — built the official site for this national-level college tech symposium |

---

### `08` — connect

<div align="center">

[![GitHub](https://img.shields.io/badge/github-SpoodermanCodes-2f81f7?style=for-the-badge&logo=github&logoColor=white&labelColor=0d1117)](https://github.com/SpoodermanCodes)
[![Gmail](https://img.shields.io/badge/gmail-svsakthivel716-2f81f7?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117)](mailto:svsakthivel716@gmail.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-connect-2f81f7?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117)](https://linkedin.com/)

<sub>Open to conversations about full-stack systems, computer vision, and security-minded engineering.</sub>
<br/>
<sub>© Sakthivel S V — building in public, breaking things responsibly.</sub>

</div>

---

### `09` — github stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=SpoodermanCodes&count_private=true&show_icons=true&hide_border=true&theme=default&title_color=2f81f7&icon_color=2f81f7&text_color=8b949e&bg_color=0d1117&ring_color=2f81f7&include_all_commits=true&card_width=440" height="165" alt="GitHub Stats"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SpoodermanCodes&layout=compact&hide_border=true&theme=default&title_color=2f81f7&text_color=8b949e&bg_color=0d1117&langs_count=8&card_width=440" height="165" alt="Top Languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=SpoodermanCodes&hide_border=true&background=0d1117&stroke=1f2937&ring=2f81f7&fire=2f81f7&currStreakLabel=2f81f7&sideLabels=8b949e&dates=6e7681&currStreakNum=e6edf3&sideNums=8b949e" height="130" alt="Streak Stats"/>

</div>
