<h1 align="center">Hi, I'm Beau</h1>

<p align="center">
  <b>Year 12 · Sydney, Australia</b><br/>
  Cybersecurity and Python · Applying for the Bachelor of Cybersecurity (IDeA) cadetship at UTS
</p>

---

## About

I'm a Year 12 student at Inner Sydney High School, applying for the [Bachelor of Cybersecurity (IDeA)](https://www.uts.edu.au/for-students/admissions-entry/entry-schemes/engineering-and-information-technology-cadetship) at UTS. IDeA is the cadetship stream, so it comes with a paid industry role from first year. That is the part I actually want. I would rather be working on real systems while I study than wait three years to find out what the job is like.

The projects below are the closest I have come to that so far. One of them runs a school sports competition that about 70 teams and their spectators actually use, which has taught me more about handling failure than any assignment has.

## How I work

I like the parts of security that are decisions rather than tools. The one I am most pleased with is small: the admin login on my tournament site reads its password from an environment variable and returns `false` when that variable is missing. If a deploy is misconfigured, the organiser gets locked out instead of the admin panel being open to everyone. It would have been easier to fall back to a default password, and that is exactly how you end up in a breach writeup.

I also try to write down what I got wrong. The first ten commits of that project had no Row Level Security, which meant anyone who opened DevTools had a database key that could delete the whole tournament. The README says so.

## Projects

| Project | What it is | Stack |
|---------|-----------|-------|
| **[insydsport](https://github.com/Squ1dddy/insydsport)** · [live](https://insydsport.live) | Tournament platform running a school handball competition. Live scoring, bracket trees, an admin console, and an offline score journal for when the school wifi drops. RLS on every table, rate-limited admin login, fail-closed auth. | Next.js 15, React 19, TypeScript, Supabase, Tailwind |
| **[unsecure-pwa-security-audit](https://github.com/Squ1dddy/unsecure-pwa-security-audit)** | Security assessment of a deliberately vulnerable Flask PWA. Five vulnerability classes found by manual review and testing, each patched and mapped to OWASP, with a full written report. | Python, Flask, SQLite, bcrypt |
| **[bigtow-trailer-hire](https://github.com/Squ1dddy/bigtow-trailer-hire)** | Terminal trailer hire system with order processing, customer lookup and JSON persistence. | Python |
| **[hsc-software-engineering](https://github.com/Squ1dddy/hsc-software-engineering)** | Software Design and Development coursework. A text RPG with a real class hierarchy, a console maths tutor, a Flask PWA and early web work. | Python, Flask, HTML, CSS |

## Certifications

| Status | Certification |
|--------|--------------|
| Completed | [IBM Cybersecurity Fundamentals, IBM SkillsBuild](https://www.credly.com/badges/f6734584-1a92-45c9-9f51-967a01188640/public_url) |
| In progress | [ISC2 Certified in Cybersecurity (CC)](https://www.isc2.org/certifications/cc) |

## Currently

- Year 12 HSC: Software Design and Development, Business Studies, Maths Advanced, Biology, English
- Working through the ISC2 CC material
- Maintaining insydsport between competition rounds

## Tech

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,ts,js,react,nextjs,tailwind,supabase,flask,html,css,git,github,vscode" />
</p>

<p align="center">
  <a href="https://github.com/Squ1dddy?tab=repositories">Repositories</a> ·
  <a href="https://insydsport.live">insydsport.live</a>
</p>
