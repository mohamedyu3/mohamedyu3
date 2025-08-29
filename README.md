# 👋 Hi, I'm **Mohamed Yousry Shabaan**

**Senior PHP/Laravel Tech Lead** • **Microservices & ZATCA e‑Invoicing** • **DevOps‑curious**
Egypt · Open to freelance/remote

<p align="center">
  <a href="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square" target="_blank"><img alt="profile views" src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&style=flat-square" /></a>
  <img alt="followers" src="https://img.shields.io/github/followers/YOUR_USERNAME?label=Followers&style=flat-square" />
  <img alt="stars" src="https://img.shields.io/github/stars/YOUR_USERNAME?affiliations=OWNER,ORGANIZATION_MEMBER&style=flat-square" />
  <!-- Optional: Country rank badge (requires you to appear on committers.top) -->
  <!-- <img alt="rank" src="https://aktive.kerolloz.dev/egypt/YOUR_USERNAME?label=Ranked%20in%20Egypt&rnkPrefix=Rank%20" /> -->
</p>

---

### 🧭 Summary

* Tech Lead with **10+ years** building large‑scale government & enterprise systems in **Saudi Arabia** & **Egypt**.
* Specialized in **Laravel 10/11/12**, **ZATCA Phase‑2** (QR, signatures, compliance/clearance), and **microservices**.
* Comfortable with **Docker/K8s**, **NGINX**, **Redis/RabbitMQ**, **MySQL/PostgreSQL**, and **CI/CD (GitHub Actions)**.
* Passionate about maintainability, performance, and clean architecture.

### 🚀 Featured Projects

* **Saudi Film Platform – Ministry of Culture** — Unified platform managing the filmmaking process.
  👉 [http://sfc.hwadi.com.sa/](http://sfc.hwadi.com.sa/)
* **DAEM – Ministry of Investment** — AI‑powered strategic planning & intelligence.
  👉 [http://spi\_demo.nextecontech.ai](http://spi_demo.nextecontech.ai)
* **Online Conference Platform (VR)** — Virtual events with immersive experiences.
  👉 [https://me-events.me/ar](https://me-events.me/ar)
* **PlayIT Games App** — Mobile gaming app integrated with telecom operators (50K+ downloads).
* **ZATCA Integrations (Phase‑2)** — Standard & simplified e‑invoices, QR/stamps, CSID renewal automations.

### 🧰 Tech Stack

<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white" />
</p>

### 📊 GitHub Analytics

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-streak-stats.herokuapp.com?user=YOUR_USERNAME" />
</p>
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&langs_count=10" />
</p>
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github-compact" />
</p>

<!-- 🏆 Optional trophies -->

<!-- <p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&margin-w=8&margin-h=8&column=6" />
</p> -->

### 🐍 Fun Zone

Add this line after you set up the workflow below 👇

```md
![snake animation](https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg)
```

### 📫 Connect

* Email: **[your.email@example.com](mailto:your.email@example.com)**
* Portfolio / CV: [https://mohamed-yousry.cvforjob.com](https://mohamed-yousry.cvforjob.com)
* LinkedIn: [https://www.linkedin.com/in/YOUR\_LINKEDIN/](https://www.linkedin.com/in/YOUR_LINKEDIN/)

---

<details>
<summary>🇪🇬 النسخة العربية</summary>

**محمد يسري شعبان** — **تقني نظم / قائد فريق Laravel** متخصص في **الفوترة الإلكترونية ZATCA (المرحلة الثانية)** و**هندسة الميكروسيرفيس**، مع خبرة واسعة في **Docker/Kubernetes** و**CI/CD**.
أهم المشاريع: منصة التصوير السينمائي (وزارة الثقافة)، منصة DAEM (وزارة الاستثمار)، منصة المؤتمرات الافتراضية، وتكاملات ZATCA الكاملة (توقيع، QR، تصديق/تفويض).

</details>

---

## ⚙️ Setup — make this your profile README

1. **Create the special repo**: make a new public repository **named exactly** `YOUR_USERNAME`. Initialize with a `README.md`.
2. Replace all `YOUR_USERNAME` & contact links in this file, then paste it into that repo's `README.md`.
3. (Optional) **Pin repos** from your profile ➜ *Customize your pins*.

### 🐍 Bonus — contribution “snake” workflow

Create `.github/workflows/snake.yml` in the same repo with:

```yaml
name: Generate snake 🐍

on:
  schedule:
    - cron: "0 0 * * *"   # daily
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake SVGs
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

      - name: Publish to "output" branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

> After the first run, the image will be available at:
> `https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-contribution-grid-snake.svg`

### 🔎 Notes

* If the stats images rate‑limit, deploy your own instance of `github-readme-stats` (Vercel) or try later.
* For the **country rank** badge, you must appear on [https://committers.top/egypt.html](https://committers.top/egypt.html) first.
* Prefer keeping sections short; point to repos for deep dives.

---

*If this template helps, ⭐ star your favorite repos!*
