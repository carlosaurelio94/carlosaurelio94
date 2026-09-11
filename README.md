<div align="center">

<a href="https://carlos-aurelio-portfolio.vercel.app">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:6366F1,50:8B5CF6,100:EC4899&height=200&section=header&text=Carlos%20Rodr%C3%ADguez&fontSize=50&fontColor=ffffff&fontAlignY=38&desc=Backend%20Engineer%20%C2%B7%20Java%20%C2%B7%20Spring%20Boot%20%C2%B7%20PostgreSQL&descAlignY=60&descSize=16&animation=fadeIn" alt="header"/>
</a>

<a href="https://github.com/carlosaurelio94">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3500&pause=800&color=8B5CF6&center=true&vCenter=true&width=600&lines=Backend+Engineer+%E2%80%A2+Java+%E2%80%A2+Spring+Boot;3+years+running+~15+microservices+in+production;I+also+ship+complete+products+end-to-end;Open+to+remote+roles+%F0%9F%9A%80" alt="typing"/>
</a>

<br/>

<img src="https://komarev.com/ghpvc/?username=carlosaurelio94&label=Profile%20views&color=8B5CF6&style=flat" alt="views"/>
<a href="https://github.com/carlosaurelio94?tab=followers"><img src="https://img.shields.io/github/followers/carlosaurelio94?label=Followers&style=flat&color=8B5CF6" alt="followers"/></a>
<a href="https://carlos-aurelio-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-Live-success?style=flat&logo=vercel&logoColor=white" alt="portfolio"/></a>

</div>

---

## 🧑‍💻 About me

```java
public class Carlos {
    String  role     = "Backend Engineer";
    String  location = "🇦🇷 Buenos Aires — UTC-3, overlaps US business hours";
    String  core     = "Java · Spring Boot · Spring Data JPA · PostgreSQL · Docker";
    String  alsoDoes = "Next.js · Angular · TypeScript · Supabase · n8n";
    String  learning = "Java 21 · Spring Boot 3 · Testcontainers · AWS";
    String  seeking  = "💼 remote backend or full-stack roles";
}
```

For **3 years** I maintained and evolved the platform behind a private wine club's
e-commerce and logistics operation: a **Grails monolith and ~15 Spring Boot
microservices** on PostgreSQL, serving hundreds of active members. There I
**cut response times on critical endpoints by around 35%** through caching,
resolving N+1 queries and adding indexes.

Today I build and sell a **multi-tenant SaaS running in production** with its first
client, and I automate customer operations over the WhatsApp Cloud API with n8n
and LLM agents.

---

## 🛠️ Stack

<div align="center">

**Core — Backend**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Hibernate](https://img.shields.io/badge/JPA%20%2F%20Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

**Frontend & product**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)

**DevOps & automation**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)

</div>

---

## 🚀 Featured projects

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3 align="center">🌱 Bocha — multi-company commercial admin SaaS</h3>
      <p align="center">
        <a href="https://boviverourbano.vercel.app">
          <img src="https://img.shields.io/badge/In%20production-Live-success?logo=vercel&logoColor=white" alt="live"/>
        </a>
        <a href="https://github.com/carlosaurelio94/bocha">
          <img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="code"/>
        </a>
      </p>
      <p align="center">
        Clients, quotes, suppliers and invoices for small businesses, with self-service
        signup, a free tier, per-module roles and permissions, and per-company branding.
        <b>Multi-company from day one:</b> isolation does not rely on the UI filtering
        correctly — it is enforced by <b>Row Level Security</b> in PostgreSQL, which rejects
        any read or write outside the connected user's company. Costlier upfront than one
        instance per client, but retrofitting it against live production data would have
        been far worse. Running in production with its first client.
      </p>
      <p align="center"><sub><b>Stack:</b> Next.js · TypeScript · Supabase · PostgreSQL · Spring Boot</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🥃 Liquoría</h3>
      <p align="center">
        <a href="https://licoreria-virtual.vercel.app">
          <img src="https://img.shields.io/badge/Demo-Live-success?logo=vercel&logoColor=white" alt="live"/>
        </a>
        <a href="https://github.com/carlosaurelio94/licoreria-virtual">
          <img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="code"/>
        </a>
      </p>
      <p>Curated spirits catalog with an LLM recommender bot, an interactive origin map and ES/EN i18n.</p>
      <p><sub><b>Stack:</b> Next.js 16 · TypeScript · Tailwind</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🏦 Homebanking</h3>
      <p align="center">
        <a href="https://github.com/carlosaurelio94/homebanking">
          <img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="code"/>
        </a>
        <img src="https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white" alt="java"/>
      </p>
      <p>Full-stack home banking API: Spring Security auth, transfers, cards, loans and PDF statements.</p>
      <p><sub><b>Stack:</b> Java · Spring Boot · JPA</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📅 Agenda App</h3>
      <p align="center">
        <a href="https://agenda-app-vivero-2026.vercel.app">
          <img src="https://img.shields.io/badge/Demo-Live-success?logo=vercel&logoColor=white" alt="live"/>
        </a>
        <a href="https://github.com/carlosaurelio94/agenda_app">
          <img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="code"/>
        </a>
      </p>
      <p>Scheduling app for a real client, with WhatsApp alerts driven by a node-cron job.</p>
      <p><sub><b>Stack:</b> Angular 17 · RxJS · Supabase · Express</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📊 Chartly</h3>
      <p align="center">
        <a href="https://desempleo-inky.vercel.app">
          <img src="https://img.shields.io/badge/In%20production-Live-success?logo=vercel&logoColor=white" alt="live"/>
        </a>
        <a href="https://github.com/carlosaurelio94/chartly">
          <img src="https://img.shields.io/badge/Code-GitHub-181717?logo=github&logoColor=white" alt="code"/>
        </a>
      </p>
      <p>Finance, shift and scheduling PWA for gig delivery workers: computes real hourly earnings and the daily target. <b>Minute-resolution push</b>, with the scheduler living inside Postgres (pg_cron + pg_net).</p>
      <p><sub><b>Stack:</b> Next.js · TypeScript · Supabase · pg_cron</sub></p>
    </td>
  </tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<a href="https://github.com/carlosaurelio94">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=carlosaurelio94&show_icons=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=8B5CF6&icon_color=EC4899&text_color=C9D1D9" alt="stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=carlosaurelio94&layout=compact&hide_border=true&bg_color=0D1117&title_color=8B5CF6&text_color=C9D1D9&langs_count=8" alt="languages"/>
</a>

<br/>

<a href="https://github.com/carlosaurelio94">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=carlosaurelio94&hide_border=true&background=0D1117&stroke=8B5CF6&ring=EC4899&fire=EC4899&currStreakLabel=8B5CF6&sideLabels=C9D1D9&currStreakNum=C9D1D9&sideNums=C9D1D9&dates=C9D1D9" alt="streak"/>
</a>

<br/>

<a href="https://github.com/ryo-ma/github-profile-trophy">
  <img src="https://github-profile-trophy.vercel.app/?username=carlosaurelio94&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7" alt="trophies"/>
</a>

</div>

---

## 🐍 Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/carlosaurelio94/carlosaurelio94/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/carlosaurelio94/carlosaurelio94/output/github-snake.svg" />
  <img alt="snake eating contributions" src="https://raw.githubusercontent.com/carlosaurelio94/carlosaurelio94/output/github-snake.svg" />
</picture>

</div>

---

## 📫 Get in touch

<div align="center">

<a href="https://www.linkedin.com/in/carlos-aurelio-rodriguez">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin"/>
</a>
<a href="mailto:carlosarc10@gmail.com">
  <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="email"/>
</a>
<a href="https://carlos-aurelio-portfolio.vercel.app">
  <img src="https://img.shields.io/badge/Portfolio-8B5CF6?style=for-the-badge&logo=vercel&logoColor=white" alt="portfolio"/>
</a>

<br/><br/>

<b>Open to remote backend and full-stack roles.</b><br/>
<sub>Buenos Aires, Argentina · UTC-3 · overlaps US business hours</sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:EC4899,50:8B5CF6,100:6366F1&height=100&section=footer&animation=fadeIn" width="100%" alt="footer"/>

<sub>⭐ <i>If any of these are useful to you, a star goes a long way.</i></sub>

</div>



