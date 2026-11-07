# <img src="https://capsule-render.vercel.app/api?type=waving&color=0:15162c,50:5344a9,100:ff8a7a&height=220&section=header&text=ZVARTZAFT&fontSize=68&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Building%20Afterglow%20%E2%80%A2%20Full-stack%20web%20development&descAlignY=58&descSize=17" alt="Zvartzaft — building Afterglow, full-stack web development" width="100%" />

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&pause=1100&color=AFA5FF&center=true&vCenter=true&width=650&lines=Thoughtful+interfaces.+Reliable+foundations.;One+community+platform%2C+from+database+to+browser.;Currently+building+Afterglow." alt="Thoughtful interfaces. Reliable foundations. Currently building Afterglow." />
  </a>
</p>

<p align="center">
  <a href="https://github.com/zvartzaft"><img src="https://img.shields.io/badge/GitHub-zvartzaft-171923?style=for-the-badge&logo=github&logoColor=white" alt="GitHub: zvartzaft" /></a>
  <a href="https://github.com/zvartzaft/afterglow-backend"><img src="https://img.shields.io/badge/Project-Afterglow-7658e8?style=for-the-badge&logo=dotnet&logoColor=white" alt="Afterglow project" /></a>
</p>

## ✨ The work in progress

**Afterglow** is a full-stack community platform, built across two repositories: a .NET backend and an Angular member-facing application. The project brings together member profiles, discovery, photo albums, diaries, invitations, and private messaging.

> 🚧 Afterglow is an early-stage development project. The backend is for development and synthetic data only—not production or real member data.

## 🧩 Explore the project

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/zvartzaft/afterglow-backend">⚙️ Afterglow Backend</a></h3>
      <p>Versioned API, separate administrator site, application and domain layers, PostgreSQL persistence, and automated tests.</p>
      <p>
        <img src="https://img.shields.io/badge/.NET-10-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET 10" />
        <img src="https://img.shields.io/badge/ASP.NET_Core-8A2BE2?style=flat-square&logo=dotnet&logoColor=white" alt="ASP.NET Core" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/zvartzaft/afterglow-frontend">🎨 Afterglow Frontend</a></h3>
      <p>Angular member experience with English and Swedish localization, profiles, diaries, photos, and conversations.</p>
      <p>
        <img src="https://img.shields.io/badge/Angular-22-DD0031?style=flat-square&logo=angular&logoColor=white" alt="Angular 22" />
        <img src="https://img.shields.io/badge/TypeScript-6-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript 6" />
        <img src="https://img.shields.io/badge/Transloco-i18n-6B4EFF?style=flat-square" alt="Transloco internationalization" />
        <img src="https://img.shields.io/badge/Vitest-tests-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest" />
      </p>
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://github.com/zvartzaft/afterglow-backend">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=zvartzaft&repo=afterglow-backend&theme=tokyonight&hide_border=true" alt="Afterglow backend repository card" />
  </a>
  <a href="https://github.com/zvartzaft/afterglow-frontend">
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=zvartzaft&repo=afterglow-frontend&theme=tokyonight&hide_border=true" alt="Afterglow frontend repository card" />
  </a>
</p>

## 🏗️ One platform, two applications

```mermaid
flowchart LR
    Member[Member] --> Web[Angular member app]
    Web -->|HTTPS / versioned API| API[ASP.NET Core API]
    API --> App[Application and domain]
    App --> DB[(PostgreSQL)]
    App --> Files[Image storage]
    Admin[Administrator] --> AdminApp[Separate MVC admin site]
    AdminApp --> App
```

## 🛠️ The toolkit

<p>
  <img src="https://img.shields.io/badge/C%23-68217A?style=for-the-badge&logo=csharp&logoColor=white" alt="C sharp" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" alt="Angular" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

<details>
  <summary>🔍 Peek at the project principles</summary>
  <br />
  <ul>
    <li><strong>Clear boundaries:</strong> separate member and administrator experiences, with layered backend responsibilities.</li>
    <li><strong>Careful account flows:</strong> antiforgery protection, rate limits, email verification, and explicit recovery flows.</li>
    <li><strong>Useful tests:</strong> unit, integration, and architecture tests on the backend, plus frontend unit tests.</li>
    <li><strong>Accessible to more members:</strong> English and Swedish UI with localized page and form feedback.</li>
  </ul>
</details>

## 📊 GitHub at a glance

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=zvartzaft&show_icons=true&rank_icon=github&theme=tokyonight&hide_border=true&include_all_commits=true" alt="GitHub statistics for zvartzaft" />
  <img height="165" src="https://streak-stats.demolab.com?user=zvartzaft&theme=tokyonight&hide_border=true" alt="GitHub contribution streak for zvartzaft" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=zvartzaft&theme=tokyo-night&hide_border=true&area=true" alt="GitHub contribution activity graph for zvartzaft" width="95%" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=zvartzaft&style=flat-square&color=7658e8&label=PROFILE+VISITS" alt="Profile visits" />
</p>

<p align="center">
  <sub>Made with curiosity, code, and a little afterglow. ✨</sub>
</p>