# GitHub Profile README Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Create a professional, balanced GitHub profile README for ngochuyk812 showcasing backend skills, featured projects, and a SaaS deploy platform in development.

**Architecture:** Single `profile/README.md` file using GitHub-hosted external services (readme-typing-svg, github-readme-stats, skill-icons, shields.io) for dynamic widgets. No build step — pure Markdown with embedded image URLs.

**Tech Stack:** Markdown, readme-typing-svg, github-readme-stats, github-readme-streak-stats, skill-icons (skillicons.dev), shields.io

---

## File Map

| File | Action | Purpose |
|---|---|---|
| `profile/README.md` | Create | GitHub profile README — copy to `ngochuyk812/ngochuyk812` repo root |

---

## Task 1: Create profile directory and README skeleton

**Files:**
- Create: `profile/README.md`

- [ ] **Step 1: Create the file with the full README content**

Create `profile/README.md` with this exact content:

```markdown
<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=4000&pause=1000&color=6AD3F7&center=true&vCenter=true&width=700&lines=Hi%2C+I'm+Nguyen+Ngoc+Huy+%F0%9F%91%8B;Backend+Developer;Microservices+Engineer;Cloud+Platform+Builder" alt="Typing SVG" />

<p>Backend developer with 2+ years of experience building scalable systems using <strong>.NET Core</strong>, <strong>Golang</strong>, and <strong>Microservices</strong> architecture.<br/>Currently building a <strong>SaaS cloud deploy platform</strong> to help developers ship projects faster.</p>

<p>
  📍 Ho Chi Minh City, Vietnam &nbsp;|&nbsp;
  📧 <a href="mailto:ngohuyk80169@gmail.com">ngohuyk80169@gmail.com</a> &nbsp;|&nbsp;
  💼 <a href="https://linkedin.com/in/ngochuyk8">LinkedIn</a>
</p>

</div>

---

## 🛠 Tech Stack

**Languages**

[![Languages](https://skillicons.dev/icons?i=cs,go,js&theme=dark)](https://skillicons.dev)

**Frameworks & Libraries**

[![Frameworks](https://skillicons.dev/icons?i=dotnet,react,nestjs&theme=dark)](https://skillicons.dev)

**Databases**

[![Databases](https://skillicons.dev/icons?i=mysql,mongodb,redis&theme=dark)](https://skillicons.dev)
&nbsp;![MSSQL](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoft-sql-server&logoColor=white)

**DevOps & Cloud**

[![DevOps](https://skillicons.dev/icons?i=docker,kubernetes,jenkins,nginx,kafka,git,github,aws&theme=dark)](https://skillicons.dev)
&nbsp;![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🏠 Real Estate Management System</h3>
      <p>High-performance platform for agencies, owners, and tenants — centralizing listings, lease management, payment automation, and maintenance coordination.</p>
      <p>
        <img src="https://img.shields.io/badge/Golang-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Microservices-000000?style=flat-square&logoColor=white"/>
        <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      </p>
      <a href="https://gitlab.com/bds4430521">View Source →</a>
    </td>
    <td width="50%" valign="top">
      <h3>🌐 Social Network</h3>
      <p>Full-featured social platform with real-time messaging, post interactions, media sharing, friend management, and lazy loading. AWS S3 for private image storage.</p>
      <p>
        <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
        <img src="https://img.shields.io/badge/ReactJS-61DAFB?style=flat-square&logo=react&logoColor=black"/>
        <img src="https://img.shields.io/badge/SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white"/>
        <img src="https://img.shields.io/badge/AWS_S3-FF9900?style=flat-square&logo=amazonaws&logoColor=white"/>
      </p>
      <a href="https://github.com/ngochuyk812/ft_social_network">View Source →</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>☁️ SaaS Cloud Deploy Platform</h3>
      <p>A self-hosted PaaS that lets developers deploy projects quickly with minimal configuration — like a personal Heroku/Railway powered by Kubernetes.</p>
      <p>
        <img src="https://img.shields.io/badge/Status-In_Development-orange?style=flat-square"/>
        <img src="https://img.shields.io/badge/Golang-00ADD8?style=flat-square&logo=go&logoColor=white"/>
        <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
      </p>
      <em>🔨 Currently building — stay tuned!</em>
    </td>
    <td width="50%"></td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ngochuyk812&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://streak-stats.demolab.com/?user=ngochuyk812&theme=tokyonight&hide_border=true" />
</div>
<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ngochuyk812&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />
</div>

---

<div align="center">
  <a href="mailto:ngohuyk80169@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://linkedin.com/in/ngochuyk8">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  &nbsp;
  <a href="https://github.com/ngochuyk812">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</div>
```

- [ ] **Step 2: Verify the file was created**

Run:
```bash
ls -la profile/README.md
wc -l profile/README.md
```
Expected: file exists, ~110+ lines

- [ ] **Step 3: Commit**

```bash
git add profile/README.md docs/superpowers/specs/2026-04-12-github-profile-design.md docs/superpowers/plans/2026-04-12-github-profile.md
git commit -m "feat: add professional GitHub profile README"
```

---

## Task 2: Deploy to GitHub special profile repository

**Prerequisite:** A public GitHub repository named exactly `ngochuyk812` must exist under the `ngochuyk812` account. If it doesn't exist, create it at https://github.com/new with the name `ngochuyk812`.

**Files:**
- Copy: `profile/README.md` → root of `ngochuyk812/ngochuyk812` repo

- [ ] **Step 1: Check if the profile repo already exists locally**

```bash
ls ~/
```

If a folder `ngochuyk812` exists as the special repo, skip to Step 3. Otherwise continue.

- [ ] **Step 2: Clone the profile repository**

```bash
cd ~
git clone https://github.com/ngochuyk812/ngochuyk812.git github-profile
cd github-profile
```

Expected: repo clones successfully

- [ ] **Step 3: Copy README into the profile repo**

```bash
cp /home/ngochuy/code/ngochuyk812/profile/README.md ~/github-profile/README.md
```

- [ ] **Step 4: Commit and push**

```bash
cd ~/github-profile
git add README.md
git commit -m "feat: update professional GitHub profile README"
git push origin main
```

Expected: push succeeds

- [ ] **Step 5: Verify live on GitHub**

Open `https://github.com/ngochuyk812` in a browser and confirm the profile README renders with:
- Typing animation header
- Tech stack icons (skill-icons grid)
- 3 project cards in the table
- 3 GitHub stats widgets
- Connect badges at the bottom

---

## Self-Review Notes

- All widget URLs use `ngochuyk812` as the username — correct
- SaaS project has no source link yet (project in-progress) — intentionally left as "coming soon"
- `streak-stats.demolab.com` is the canonical URL for DenverCoder9's streak stats service
- `skillicons.dev` icon keys used: `cs, go, js, dotnet, react, nestjs, mysql, mongodb, redis, docker, kubernetes, jenkins, nginx, kafka, git, github, aws` — all valid
- RabbitMQ and MSSQL use shields.io badges since skillicons.dev does not include them
