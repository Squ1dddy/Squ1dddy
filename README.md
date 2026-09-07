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

## How I work

Four habits that show up in everything here, and where to check them.

**I build for the failure, not the demo.** Traksy re-checks media consent at the moment a post goes out rather than trusting a queue, because a school that revokes consent after a post is scheduled has to be able to stop it. insydsport writes every score to the scoring phone before it touches the network, because a backup that lives in the same database is not a backup. Both exist because I assumed the happy path would not hold, and on school wifi it did not.

**I write down what I got wrong.** Every repository here has a section for what is still broken or what I would do differently: a service worker that never registers, a stats screen that counts the wrong games, a README that once described features the code never had. A portfolio that only lists wins isn't telling you much, and the habit transfers better than any one project does.

**I use AI heavily, and keep the judgement.** It writes code quickly. It does not decide what the code should do, and that distinction is most of the job. Knowing that a read-write database key in the browser is a hole, that admin auth should fail closed rather than fall back to a default, that a model drafting a newsletter about children should never be handed a roster — that part is mine to bring. Then I use AI to get there faster, and I check what comes back, because I am the one who has to defend it.

**I finish things and put them in front of people.** Two systems are deployed and running rather than sitting in a branch: one that about 70 teams and their spectators used through a live competition, one built for schools and demonstrable end to end. Software with users teaches you things assignments don't, mostly about what happens when it breaks.

## Toolkit

**Languages**<br/>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css&logoColor=white)

**Frameworks and platforms**<br/>
![Flask](https://img.shields.io/badge/Flask-1B2A38?style=flat-square&logo=flask&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=black) ![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=black)

**Security**<br/>
![OWASP Top 10](https://img.shields.io/badge/OWASP_Top_10-1B2A38?style=flat-square&logo=owasp&logoColor=white) ![bcrypt](https://img.shields.io/badge/bcrypt-525252?style=flat-square) ![Manual code review](https://img.shields.io/badge/Manual_code_review-6E5494?style=flat-square)

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
