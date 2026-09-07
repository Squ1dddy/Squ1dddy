<div align="center">

# Beau Bastock

<a href="https://insydsport.live">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=00B4D8&center=true&vCenter=true&width=620&lines=Cybersecurity+%C2%B7+AI%2FML+%C2%B7+Python;Running+a+live+platform+for+70+teams;Building+software+people+actually+use" alt="Cybersecurity, Python, AI/ML" />
</a>

<br/>

<img src="https://img.shields.io/badge/Sydney-Australia-00B4D8?style=flat-square" alt="Sydney, Australia" />
<img src="https://img.shields.io/badge/Year_12-Inner_Sydney_High-1B2A38?style=flat-square" alt="Year 12" />
<img src="https://img.shields.io/badge/Focus-Cybersecurity_&_AI%2FML-0F4C81?style=flat-square" alt="Focus: cybersecurity and AI/ML" />
<a href="https://insydsport.live"><img src="https://img.shields.io/badge/insydsport.live-online-2EA043?style=flat-square" alt="insydsport.live is online" /></a>

</div>

---

I'm a Year 12 student heading towards a career in **cybersecurity and AI/ML**. What I want out of it is the work itself, early: I'd rather build and break real systems while I study than wait three years to find out what the job is actually like.

The closest I've come so far is a tournament platform that about 70 teams and their spectators use during competition weeks. Software with users teaches you things assignments don't, mostly about what happens when it breaks.

## Projects

Independent work, built outside class and still running.

| | Project | What it is | Built with |
|:--:|---------|-----------|------------|
| 🏫 | **[traksy-showcase](https://github.com/Squ1dddy/traksy-showcase)**<br/><sub>🟢 [live demo](https://traksy.netlify.app/demo)</sub> | School sport recognition platform for NSW schools. Log a result on the sideline and it becomes an announcement, a newsletter item and a social post. Postgres RLS multi-tenancy across 29 migrations, publishing gated on media consent at send time, and AI drafting fenced to a single truncated line. Source private, live demo public. | `Next.js` `TypeScript` `Supabase` `Claude API` |
| 🏆 | **[insydsport](https://github.com/Squ1dddy/insydsport)**<br/><sub>🟢 [live](https://insydsport.live)</sub> | Tournament platform running a school handball competition. Live scoring, bracket trees, an admin console, and an offline score journal for when the school wifi drops out. RLS on every table, rate-limited admin login, fail-closed auth. | `Next.js 15` `React 19` `TypeScript` `Supabase` |

## HSC Software Engineering

In-class assessment tasks from Software Engineering at Inner Sydney High School, each in its own repository. Newest first.

| | Project | What it is | Year |
|:--:|---------|-----------|:--:|
| 🔐 | **[unsecure-pwa-security-audit](https://github.com/Squ1dddy/unsecure-pwa-security-audit)** | Security assessment of a deliberately vulnerable Flask app. Five vulnerability classes found by manual review and testing, each patched, mapped to OWASP, and written up in a full report. | 12 |
| 🟩 | **[terminal-wordle](https://github.com/Squ1dddy/terminal-wordle)** | A term-long build. Six guesses, colour-coded tiles, a two-player mode and CSV-persisted stats. The guess checker handles duplicate letters in two passes, and a harness tests it against normal, boundary, faulty and abnormal input. | 12 |
| 🚚 | **[bigtow-trailer-hire](https://github.com/Squ1dddy/bigtow-trailer-hire)** | Terminal trailer hire system. Order processing, cost calculation, customer lookup by surname, JSON persistence. | 12 |
| 🌐 | **[car-catalogue-pwa](https://github.com/Squ1dddy/car-catalogue-pwa)** | The first project built around databases rather than the language. Flask and SQLite, two tables joined on a foreign key, debounced AJAX search over a JSON endpoint with parameterised queries, six sort routes, plus a service worker and manifest. | 12 |
| ⚔️ | **[text-adventure-rpg](https://github.com/Squ1dddy/text-adventure-rpg)** | The object-oriented task. `Item`, `Character` and `Room` base classes whose subclasses change behaviour rather than add fields, so a locked door is a room that refuses entry instead of an `if` statement. | 11 |
| 📐 | **[console-maths-tutor](https://github.com/Squ1dddy/console-maths-tutor)** | Terminal maths tutor. Pythagoras solver, area calculator, triangle classifier and a randomised quiz, with a unit test harness for the side-length logic. | 11 |
| 🏐 | **[volleyball-website](https://github.com/Squ1dddy/volleyball-website)** | Static single-page site, hand-written HTML and CSS with no framework. The earliest work I have kept, here for the record rather than as a showcase. | 10 |

## Skills, and where to check them

Every claim below links to the thing that proves it. Traksy's source is private, so its rows point at the live product and the case study instead.

| | Where to check it |
|---|---|
| **Postgres RLS and multi-tenancy** | [traksy](https://github.com/Squ1dddy/traksy-showcase) — RLS on every table across 29 migrations, so a school's data is scoped by policy rather than by remembering a `WHERE` clause · insydsport — [`supabase/rls.sql`](https://github.com/Squ1dddy/insydsport/blob/main/supabase/rls.sql) |
| **Auth, sessions and abuse limits** | insydsport — [`lib/admin-auth.ts`](https://github.com/Squ1dddy/insydsport/blob/main/lib/admin-auth.ts) fails closed when the password variable is missing, [`lib/rate-limit.ts`](https://github.com/Squ1dddy/insydsport/blob/main/lib/rate-limit.ts) throttles failed logins on a rolling window |
| **OWASP Top 10, applied** | [unsecure-pwa-security-audit](https://github.com/Squ1dddy/unsecure-pwa-security-audit) — five vulnerability classes found by manual review and testing, each patched and mapped, with a [written report](https://github.com/Squ1dddy/unsecure-pwa-security-audit/blob/main/security-assessment-report.pdf) |
| **SQL injection, both sides** | Broke it: [`user_management.py`](https://github.com/Squ1dddy/unsecure-pwa-security-audit/blob/main/user_management.py) — f-string login query, `hi' or '1'='1` walks straight in. Fixed it: [`database_manager.py`](https://github.com/Squ1dddy/car-catalogue-pwa/blob/main/database_manager.py) — parameterised search over a two-table join |
| **LLM APIs, with a boundary** | traksy — the model is handed one already-truncated line and never a roster; its system prompt forbids inventing facts and adding names, is hardened against injection through the input, and unit tests assert those constraints still exist |
| **Privacy and accessibility** | traksy — Australian Privacy Principles 5, 8, 12 and 13, with published [privacy](https://traksy.netlify.app/privacy) and [accessibility](https://traksy.netlify.app/accessibility) statements. WCAG 2.1 AA is the target and the gaps still open are written down rather than claimed closed |
| **Designing for failure** | insydsport — [`lib/score-journal.ts`](https://github.com/Squ1dddy/insydsport/blob/main/lib/score-journal.ts) writes every score to the scoring phone before the network sees it, because a backup in the same database is not a backup |
| **Object-oriented design** | [text-adventure-rpg](https://github.com/Squ1dddy/text-adventure-rpg) — [`item.py`](https://github.com/Squ1dddy/text-adventure-rpg/blob/main/item.py) and [`character.py`](https://github.com/Squ1dddy/text-adventure-rpg/blob/main/character.py), subclasses that change behaviour rather than add fields, so a locked door is a room that refuses entry |
| **Testing** | [`harness.py`](https://github.com/Squ1dddy/terminal-wordle/blob/main/harness.py) covers normal, boundary, faulty and abnormal input · [`unit_test.py`](https://github.com/Squ1dddy/console-maths-tutor/blob/main/unit_test.py) · traksy — 33 test files |

## Toolkit

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Frameworks and platforms**<br/>
![Flask](https://img.shields.io/badge/Flask-1B2A38?style=flat-square&logo=flask&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=black)

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
