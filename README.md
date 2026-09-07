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

I'm a Year 12 student heading towards a career in **cybersecurity and AI/ML**. What I want out of it is the work itself, early. I'd rather build and break real systems while I study than wait three years to find out what the job is actually like.

The closest I've come so far is a tournament platform that about 70 teams and their spectators use during competition weeks. Software with users teaches you things assignments don't, mostly about what happens when it breaks.

## Projects

Independent work, built outside class and still running.

| | Project | What it is | Built with |
|:--:|---|---|---|
| 🏫 | **[traksy](https://github.com/Squ1dddy/traksy-showcase)**<br/><sub>🟢 [live demo](https://traksy.netlify.app/demo)</sub> | School sport platform for NSW schools. A result logged on the sideline becomes an announcement, a newsletter item and a social post. | `Next.js` `TypeScript` `Supabase` `Claude API` |
| 🏆 | **[insydsport](https://github.com/Squ1dddy/insydsport)**<br/><sub>🟢 [live](https://insydsport.live)</sub> | Tournament platform for a school handball competition. Live scoring, bracket trees, admin console, offline score journal. | `Next.js` `React` `TypeScript` `Supabase` |

## HSC Software Engineering

In-class assessment tasks, each in its own repository. Newest first.

| | Project | What it is | Year |
|:--:|---|---|:--:|
| 🔐 | **[unsecure-pwa-security-audit](https://github.com/Squ1dddy/unsecure-pwa-security-audit)** | Five vulnerability classes found by hand, patched and mapped to OWASP, with a written report. | 12 |
| 🟩 | **[terminal-wordle](https://github.com/Squ1dddy/terminal-wordle)** | A term-long build. Duplicate-letter handling, two-player mode, CSV stats, test harness. | 12 |
| 🚚 | **[bigtow-trailer-hire](https://github.com/Squ1dddy/bigtow-trailer-hire)** | Trailer hire orders, pricing and customer lookup, saved to JSON. | 12 |
| 🌐 | **[car-catalogue-pwa](https://github.com/Squ1dddy/car-catalogue-pwa)** | Flask and SQLite. Two joined tables, debounced AJAX search, service worker and manifest. | 12 |
| ⚔️ | **[text-adventure-rpg](https://github.com/Squ1dddy/text-adventure-rpg)** | The object-oriented task. A locked door is a room that refuses entry, not an `if` statement. | 11 |
| 📐 | **[console-maths-tutor](https://github.com/Squ1dddy/console-maths-tutor)** | Pythagoras, areas, triangle classification and a quiz, with a unit test harness. | 11 |
| 🏐 | **[volleyball-website](https://github.com/Squ1dddy/volleyball-website)** | Hand-written HTML and CSS, no framework. Earliest work I've kept, for the record. | 10 |

## Skills, and where to check them

Every claim links to the thing that proves it. Traksy's source is private, so its rows point at the live product instead.

| Skill | Evidence | Proof |
|---|---|:--|
| **Postgres RLS, multi-tenancy** | RLS on every table across 29 migrations, so data is scoped by policy rather than by remembering a `WHERE` clause. | [traksy](https://github.com/Squ1dddy/traksy-showcase) · [`rls.sql`](https://github.com/Squ1dddy/insydsport/blob/main/supabase/rls.sql) |
| **Auth and abuse limits** | Admin login fails closed when the password variable is missing. Failed logins throttle on a rolling window. | [`admin-auth.ts`](https://github.com/Squ1dddy/insydsport/blob/main/lib/admin-auth.ts) · [`rate-limit.ts`](https://github.com/Squ1dddy/insydsport/blob/main/lib/rate-limit.ts) |
| **OWASP Top 10, applied** | Five vulnerability classes found by manual review and testing, each patched and mapped. | [repo](https://github.com/Squ1dddy/unsecure-pwa-security-audit) · [report](https://github.com/Squ1dddy/unsecure-pwa-security-audit/blob/main/security-assessment-report.pdf) |
| **SQL injection, both sides** | Broke it: an f-string login query where `hi' or '1'='1` walks straight in. Fixed it: parameterised search over a two-table join. | [broke](https://github.com/Squ1dddy/unsecure-pwa-security-audit/blob/main/user_management.py) · [fixed](https://github.com/Squ1dddy/car-catalogue-pwa/blob/main/database_manager.py) |
| **LLM APIs, with a boundary** | The model gets one truncated line, never a roster. Its prompt forbids inventing facts or adding names, is hardened against injection, and tests assert that. | [traksy](https://github.com/Squ1dddy/traksy-showcase) |
| **Privacy and accessibility** | Australian Privacy Principles 5, 8, 12 and 13. WCAG 2.1 AA is the target, with the open gaps written down rather than claimed closed. | [privacy](https://traksy.netlify.app/privacy) · [accessibility](https://traksy.netlify.app/accessibility) |
| **Designing for failure** | Every score is written to the scoring phone before the network sees it, because a backup in the same database is not a backup. | [`score-journal.ts`](https://github.com/Squ1dddy/insydsport/blob/main/lib/score-journal.ts) |
| **Object-oriented design** | Subclasses change behaviour rather than add fields, so the room decides whether you may enter. | [`item.py`](https://github.com/Squ1dddy/text-adventure-rpg/blob/main/item.py) · [`character.py`](https://github.com/Squ1dddy/text-adventure-rpg/blob/main/character.py) |
| **Testing** | Cases written for normal, boundary, faulty and abnormal input. 33 test files in Traksy. | [`harness.py`](https://github.com/Squ1dddy/terminal-wordle/blob/main/harness.py) · [`unit_test.py`](https://github.com/Squ1dddy/console-maths-tutor/blob/main/unit_test.py) |

## Toolkit

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Frameworks and platforms**<br/>
![Flask](https://img.shields.io/badge/Flask-1B2A38?style=flat-square&logo=flask&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=black)

## Certifications

| | Certification |
|:--:|---|
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
