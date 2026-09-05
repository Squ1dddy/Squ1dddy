<div align="center">

# Beau Bastock

<a href="https://insydsport.live">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=00B4D8&center=true&vCenter=true&width=620&lines=Cybersecurity+%C2%B7+Python+%C2%B7+TypeScript;Running+a+live+platform+for+70+teams;Bachelor+of+Cybersecurity+%28IDeA%29+at+UTS" alt="Cybersecurity, Python, TypeScript" />
</a>

<br/>

<img src="https://img.shields.io/badge/Sydney-Australia-00B4D8?style=flat-square" alt="Sydney, Australia" />
<img src="https://img.shields.io/badge/Year_12-Inner_Sydney_High-1B2A38?style=flat-square" alt="Year 12" />
<a href="https://www.uts.edu.au/for-students/admissions-entry/entry-schemes/engineering-and-information-technology-cadetship"><img src="https://img.shields.io/badge/Applying-UTS_Cybersecurity_(IDeA)-0F4C81?style=flat-square" alt="UTS IDeA" /></a>
<a href="https://insydsport.live"><img src="https://img.shields.io/badge/insydsport.live-online-2EA043?style=flat-square" alt="insydsport.live is online" /></a>

</div>

---

I'm a Year 12 student applying for the **Bachelor of Cybersecurity (IDeA)** at UTS. IDeA is the cadetship stream, so it comes with a paid industry role from first year. That's the part I want. I'd rather work on real systems while I study than wait three years to find out what the job is actually like.

The closest I've come so far is a tournament platform that about 70 teams and their spectators use during competition weeks. Software with users teaches you things assignments don't, mostly about what happens when it breaks.

<br/>

<div align="center">
  <a href="https://insydsport.live">
    <img src="https://raw.githubusercontent.com/Squ1dddy/insydsport/main/docs/home.png" width="78%" alt="insydsport.live home page showing the Year 12 grand final result" />
  </a>
  <br/>
  <sub><b>insydsport.live</b> · live scoring, bracket trees and an admin console for the Inner Sydney handball knockout</sub>
</div>

<br/>

## Projects

| | Project | What it is | Built with |
|:--:|---------|-----------|------------|
| 🏆 | **[insydsport](https://github.com/Squ1dddy/insydsport)**<br/><sub>🟢 [live](https://insydsport.live)</sub> | Tournament platform running a school handball competition. Live scoring, bracket trees, an admin console, and an offline score journal for when the school wifi drops out. RLS on every table, rate-limited admin login, fail-closed auth. | `Next.js 15` `React 19` `TypeScript` `Supabase` |
| 🔐 | **[unsecure-pwa-security-audit](https://github.com/Squ1dddy/unsecure-pwa-security-audit)** | Security assessment of a deliberately vulnerable Flask app. Five vulnerability classes found by manual review and testing, each patched, mapped to OWASP, and written up in a full report. | `Python` `Flask` `SQLite` `bcrypt` |
| 🚚 | **[bigtow-trailer-hire](https://github.com/Squ1dddy/bigtow-trailer-hire)** | Terminal trailer hire system. Order processing, cost calculation, customer lookup by surname, JSON persistence. | `Python` |
| 📚 | **[hsc-software-engineering](https://github.com/Squ1dddy/hsc-software-engineering)** | Coursework. A text RPG with a real class hierarchy, a console maths tutor, a Flask PWA and some early web work. | `Python` `Flask` `HTML/CSS` |

## How I work

The security decision I'm most pleased with is a small one. The admin login on insydsport reads its password from an environment variable and returns `false` when that variable is missing. If a deploy is misconfigured, the organiser gets locked out instead of the admin panel being wide open. The easy alternative, falling back to a default password, is how sites end up in breach writeups.

I also try to write down what I got wrong. The first ten commits of that project had **no Row Level Security**, which meant anyone who opened DevTools was holding a database key that could delete the entire tournament. It's fixed, and the README says so, because a portfolio that only lists wins isn't telling you much.

## Toolkit

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Frameworks and platforms**<br/>
![Next.js](https://img.shields.io/badge/Next.js-1B2A38?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-1B2A38?style=flat-square&logo=flask&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=black)

**Security**<br/>
![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-1B2A38?style=flat-square&logo=owasp&logoColor=white) ![Postgres RLS](https://img.shields.io/badge/Postgres_RLS-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![bcrypt](https://img.shields.io/badge/bcrypt-525252?style=flat-square) ![Manual code review](https://img.shields.io/badge/Manual_code_review-6E5494?style=flat-square)

## Certifications

| | Certification |
|:--:|---------------|
| ✅ | [IBM Cybersecurity Fundamentals](https://www.credly.com/badges/f6734584-1a92-45c9-9f51-967a01188640/public_url) · IBM SkillsBuild |
| ⏳ | [ISC2 Certified in Cybersecurity (CC)](https://www.isc2.org/certifications/cc) · in progress |

## Right now

- Year 12 HSC: Software Design and Development, Business Studies, Maths Advanced, Biology, English
- Working through the ISC2 CC material
- Maintaining insydsport between competition rounds

<div align="center">
<br/>

**[Repositories](https://github.com/Squ1dddy?tab=repositories)** · **[insydsport.live](https://insydsport.live)**

</div>
