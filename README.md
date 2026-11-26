<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/main/assets/header-dark.svg">
    <img alt="Jung Minkyu (정민규), developer across servers, the web and games" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/main/assets/header-light.svg" width="100%">
  </picture>
</p>

<p>
  <a href="https://jungminkyu.netlify.app/%EC%A0%95%EB%AF%BC%EA%B7%9C_%ED%8F%AC%ED%8A%B8%ED%8F%B4%EB%A6%AC%EC%98%A4.pdf"><img alt="Portfolio (PDF)" src="https://img.shields.io/badge/Portfolio-PDF-002968?style=flat-square&logo=adobeacrobatreader&logoColor=white"></a>
  <a href="https://leetcode.com/u/MKJung/"><img alt="LeetCode MKJung" src="https://img.shields.io/badge/LeetCode-MKJung-002968?style=flat-square&logo=leetcode&logoColor=white"></a>
  <a href="https://solved.ac/u/k5until30"><img alt="Baekjoon k5until30 on solved.ac" src="https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fminkyu-k530%2Fminkyu-k530%2Foutput%2Fboj.json&style=flat-square&cacheSeconds=21600"></a>
</p>

### Hi, I'm Minkyu.

I like building the whole thing: the screen, the server behind it, the database under it, and the cluster it runs on.

Lately that has meant a browser FPS, a server room simulator and a learning service for investing.

When a teammate gets stuck on an error, I want to be the person they ask first.

## What I care about

- **Servers that hold up.** Breaking things on purpose (outages, slow clients) to see what fails first.
- **Real time.** Game loops on a fixed tick, and live updates that never stall on one slow client.
- **The whole path.** React or three.js in front, Spring Boot and PostgreSQL behind, Docker and Kubernetes to ship it.

## Projects

<p>
  <img alt="Server Room Simulator" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/main/assets/shots/srs.webp" width="49%">
  <img alt="FinMATE home screen" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/main/assets/shots/finmate.webp" width="49%">
</p>

| Project | What it is |
| --- | --- |
| **Server Room Simulator** | A 3D server room game where you live through power and disk failures. The server runs every rule in a 100 ms tick, and cutting the worst tick from **537 ms to 28.7 ms** with 100 players kept it there. |
| **SKALA FPS** | A fast browser FPS on three.js with no build step, made as a team. |
| **[FinMATE](https://github.com/oh-my-finance/omf-frontend)** | A learning service for investing, from how the market works to derivatives. Profile grades come from a rule engine, not an LLM. |
| **tradingBot** | An ETF trading bot on a broker's Open API. Limit orders only, a daily loss stop and a kill switch. |
| **PlantGuard AI** | Failure prediction for semiconductor equipment, built with a team of four. Trained on eight machines, it warns early on machines it has never seen. |

<sub>Projects without a link are not public.</sub>

<details>
<summary><b>How the Server Room Simulator got under its tick budget</b></summary>
<br>

Under a 15-second load test with 100 players, the worst tick took 537 ms, five times the 100 ms budget. Sending updates to clients happened on the tick thread, so one slow client held up the whole game. Moving those sends off the tick thread brought the worst tick down to 28.7 ms, with no tick over budget.

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/main/assets/srs-chart-dark.svg">
    <img alt="Max tick time with 100 players: 537 ms before, 28.7 ms after moving sends off the tick thread" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/main/assets/srs-chart-light.svg" width="60%">
  </picture>
</p>

</details>

## Stack

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=java%2Cspring%2Cpostgres%2Credis%2Cdocker%2Ckubernetes%2Cgithubactions%2Cgcp%2Cprometheus%2Cpython%2Cts%2Creact%2Cthreejs%2Cgit&theme=dark">
    <img alt="Java, Spring, PostgreSQL, Redis, Docker, Kubernetes, GitHub Actions, GCP, Prometheus, Python, TypeScript, React, three.js, Git" src="https://skillicons.dev/icons?i=java%2Cspring%2Cpostgres%2Credis%2Cdocker%2Ckubernetes%2Cgithubactions%2Cgcp%2Cprometheus%2Cpython%2Cts%2Creact%2Cthreejs%2Cgit&theme=light">
  </picture>
</p>

## Activity

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/output/calendar-dark.svg">
    <img alt="Contributions in the last year" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/output/calendar-light.svg" width="100%">
  </picture>
</p>

<p>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/output/stats-dark.svg">
    <img alt="Activity in the last 12 months" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/output/stats-light.svg" width="49%">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/output/recent-dark.svg">
    <img alt="Recently pushed public repositories" src="https://raw.githubusercontent.com/minkyu-k530/minkyu-k530/output/recent-light.svg" width="49%">
  </picture>
</p>

## About

- **Now** SK AI Leader Academy (SKALA), AI, cloud and MSA, July to December 2026
- **School** Myongji University, B.S. in Applied Software, August 2026
- **Certifications** Engineer Information Processing, Big Data Analysis Engineer, SQLD, ADsP
- **Awards**
  - Excellence Award, Cultureland pre-mission, 3rd of 100 (2026)
  - Best Award, business model competition for TrustBuilder, 1st of 27 (2026)
  - Best Active Participant Award, MJ Major Mentors (2025)
  - Excellence Award, Korean Tutoring, as team leader (2024)

<br>

<sub>The activity cards are redrawn every night by <a href="https://github.com/minkyu-k530/minkyu-k530/blob/main/.github/workflows/profile.yml">a GitHub Actions workflow</a>.</sub>
