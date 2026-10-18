<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&height=240&color=gradient&text=Jo%C3%A3o%20Watanabe&fontColor=ffffff&fontSize=55&animation=fadeIn&desc=Developer%20%E2%80%A2%20Code%20reviewer%20in%20training%20%E2%80%A2%20AI-native%20workflow&descSize=18&descAlignY=64" />

<p align="center">
  <a href="https://github.com/joaowatanabe">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=2EA043&center=true&vCenter=true&width=640&lines=Laravel+by+day+%40+Coinpel;TypeScript+%2B+Node+on+the+side;Learning+to+read+code+before+writing+it;Orchestrating+AI+agents+%E2%80%94+Claude+%2B+Antigravity+%2B+Orca;DJ+%2F+producer+as+%40wabemusic" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/joaowatanabe"><img src="https://img.shields.io/badge/Open%20to-Remote%20%26%20International-0f6c2b?style=flat-square" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Pelotas%2C%20RS%20%E2%80%94%20Brazil-333333?style=flat-square" />
  <img src="https://img.shields.io/badge/Now-Clean%20Code%20%E2%86%92%20SOLID-2ea043?style=flat-square" />
  <img src="https://komarev.com/ghpvc/?username=joaowatanabe&style=flat-square&color=0f6c2b&label=profile+views" />
</p>

---

## 👋 About me

```ts
const joao = {
  role: "Software Development Intern @ Coinpel (since Jul 2026)",
  studying: "Systems Analysis & Development — SENAC Pelotas (3rd semester)",
  workingWith: ["Laravel", "PHP", "PostgreSQL", "Docker", "integrated systems"],
  buildingWith: ["TypeScript", "Node.js", "React", "Next.js", "NestJS"],
  aiWorkflow: ["Claude Code", "Antigravity", "Orca", "MCP servers"],
  alsoInto: ["self-hosting / homelab", "music production", "cars", "games"],
  languages: ["Portuguese (native)", "English (professional)"],
  motto: "One step every day.",
};
```

I'm a developer from **Pelotas, RS 🇧🇷**, interning at **[Coinpel](https://www.coinpel.com.br/)** (Pelotas Tech Park), where I work on **Laravel** systems that talk to each other across several internal products. I came in having never touched PHP, so most of my growth there is learning *why* the code is built the way it is, not only *what* it does.

My bet: **with AI writing more of the code, the edge is reading it, reviewing it and making good decisions.** So I write code with agents every day, and I train myself to review that code without them.

**Open to remote and international opportunities.**

---

## 🌱 What I'm learning right now

<table>
<tr>
<td width="50%" valign="top">

### 🎓 At SENAC — 3rd semester

| Course | What it's teaching me |
| --- | --- |
| **Algorithms & Data Structures I** | Python: lists, dicts, sets, data analysis with Plotly |
| **Software Engineering II** | Clean Code and code review reports |
| **Databases II** | Advanced SQL on PostgreSQL + NoSQL with **MongoDB** |
| **Networking Fundamentals** | OSI/TCP-IP, addressing, number bases |
| **Services & APIs** | REST APIs in TypeScript |

</td>
<td width="50%" valign="top">

### 💼 At Coinpel — on the job

- Laravel the right way: **services, repositories, DI**, Eloquent vs raw SQL
- Many systems sharing data — integrations, not just CRUD
- Local env with **Laravel Herd + Postgres.app**, new projects on **Docker Compose (Colima)**
- Testing endpoints with **Bruno**
- Reading other people's code in a real codebase, every day

</td>
</tr>
</table>

### 🧭 My study path (one at a time)

```
 ✅ Clean Code  ──▶  🔄 SOLID & OOP  ──▶  ⏳ Testing (Vitest / Jest)  ──▶  ⏳ Architecture & design systems
```

I practice by reviewing **my own old repos without AI first**, writing down what's wrong and why, and only then comparing with an AI review.

---

## 🤖 How I work with AI

I don't just "use ChatGPT". I run a small **multi-agent setup** on my machine, coordinated through **[Orca](https://github.com/stablyai/orca)**:

```mermaid
flowchart LR
    J([👤 João]) --> C
    subgraph Orca["🐋 Orca — terminals, worktrees & orchestration"]
        C["🧠 Claude Code<br/><sub>commander: code, complex tasks, review</sub>"]
        A["⚙️ Antigravity<br/><sub>executor: heavy, token-hungry tasks</sub>"]
        C -- "orders queue" --> A
        A -- "done / log" --> C
    end
    C <--> M["🔌 MCP servers<br/><sub>Notion · Google Drive · Chrome</sub>"]
    A --> H[("📁 Personal hub repo<br/><sub>shared memory & coordination</sub>")]
    C --> H
```

- **Claude Code** is the coordinator: it writes code, takes on the hard problems, and reviews what the other agent delivers.
- **Antigravity** handles the simple but heavy work: extracting PDFs, cataloguing material, generating exercise banks.
- Both agents share a git repo that serves as long-term memory (an order queue plus a log), so either one can pick up where the other left off.
- **MCP servers** connect them to my Notion (study hub, journal, habits), Google Drive and browser. I also use custom **skills** and **graphify** knowledge graphs to turn notes and code into context.

---

## 🛠️ Tech Stack

**Languages & frameworks**

<p>
  <img src="https://skillicons.dev/icons?i=js,ts,python,php,react,nextjs,nodejs,nestjs,express,laravel,tailwind" />
</p>

**Data**

<p>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,prisma" />
</p>

**Tooling & environment**

<p>
  <img src="https://skillicons.dev/icons?i=git,github,docker,linux,bash,vscode,jest,vitest,postman,figma,notion" />
</p>

**AI, agents & daily tools**

<p>
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white" />
  <img src="https://img.shields.io/badge/Antigravity-4285F4?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/Orca-1f2937?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=modelcontextprotocol&logoColor=white" />
  <img src="https://img.shields.io/badge/Bruno-F4AA41?style=for-the-badge&logo=bruno&logoColor=black" />
  <img src="https://img.shields.io/badge/Laravel%20Herd-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/Colima-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/AdGuard%20Home-68BC71?style=for-the-badge&logo=adguard&logoColor=white" />
  <img src="https://img.shields.io/badge/Ableton%20Live-000000?style=for-the-badge" />
</p>

---

## 🚀 Projects & experiments

| Project | What it is | Stack |
| --- | --- | --- |
| 🏠 **Homelab on a TV Box** | An ARM64 Allwinner box running Linux/Termux 24/7 with **AdGuard Home** as DNS for the whole house: headless, boots on its own, blocks ads on every device | Linux · ARM64 · DNS |
| 🤖 **AI agent hub** | My personal "operating system": a git repo + Notion where Claude Code and Antigravity coordinate tasks, studies and routines | Claude Code · Orca · MCP |
| 🎧 **[analise-spotify-python](https://github.com/joaowatanabe/analise-spotify-python)** | Data structures assignment: analysis of the Spotify Tracks dataset with interactive charts | Python · Plotly |
| ✅ **[habit-tracker-laravel](https://github.com/joaowatanabe/habit-tracker-laravel)** | Habit tracker built to learn Laravel outside work | PHP · Laravel |
| 🎬 **[projeto-cinema-poo-senac](https://github.com/joaowatanabe/projeto-cinema-poo-senac)** | Cinema system modelled with OOP | TypeScript · Jest |
| ⏱️ **[chronos-pomodoro](https://github.com/joaowatanabe/chronos-pomodoro)** | Pomodoro timer | React · TypeScript |
| 🎨 **Portfolio (WIP)** | Built step by step as a learning exercise, aiming for Awwwards-level polish | Next.js · NestJS |

---

## 📊 GitHub Analytics

<div align="center">

<img height="170em" src="https://github-readme-stats-psi-topaz.vercel.app/api?username=joaowatanabe&show_icons=true&theme=merko&hide_border=true&include_all_commits=true&cache_seconds=86400"/>
<img height="170em" src="https://streak-stats.demolab.com?user=joaowatanabe&theme=merko&hide_border=true&cache_seconds=86400"/>

<img height="150em" src="https://github-readme-stats-psi-topaz.vercel.app/api/top-langs/?username=joaowatanabe&layout=compact&theme=merko&hide_border=true&langs_count=8&cache_seconds=86400"/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=joaowatanabe&theme=merko&hide_border=true&area=true" />

</div>

---

## 🎧 Beyond the code

I've been a **DJ and music producer** for years. I release and play as **[@wabemusic](https://instagram.com/wabemusic)**, and Ableton Live is as familiar to me as my editor. It's the same loop as engineering: build something, listen to it, cut what doesn't work, ship it.

Also into cars, games and traveling.

<p align="center">
  <img src="https://spotify-github-profile.kittinanx.com/api/view?uid=12142982263&cover_image=true&theme=default&show_offline=false&background_color=121212&interchange=false&bar_color=0f6c2b&bar_color_cover=false" />
</p>

---

## 📚 Education & Certifications

- 🎓 **Systems Analysis and Development**, SENAC Pelotas *(in progress, 3rd semester)*
- 🎓 **[Full Stack Development](https://cubos.academy/cursos/desenvolvimento-de-software-v2)**, Cubos Academy
- 📱 **Mobile Developer Bootcamp**, DIO
- 💻 **+Praticar** program (web fundamentals)

---

## 🌐 Let's talk

<div align="center">

<a href="https://www.linkedin.com/in/joaowatanabe"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="mailto:jvwatanabe@gmail.com"><img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=white"/></a>
<a href="https://instagram.com/wabemusic"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"/></a>
<a href="https://discordapp.com/users/wabezada"><img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white"/></a>

</div>

<p align="center"><i>"One step every day."</i></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&section=footer" />
