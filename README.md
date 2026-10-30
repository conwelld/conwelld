<div align="center">

# Dayton Conwell
### Computer Science @ Berea College · Operating Systems TA · Building AI tools for students

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dayton-conwell/)
[![Email](https://img.shields.io/badge/-Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:conwelld@berea.edu)
[![Rung](https://img.shields.io/badge/-Rung-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/conwelld/Rung)

</div>

<br>

### About Me

I'm a CS student at Berea College (class of 2028) and I love building software that helps the people around me. Lately that means AI tools for students learning to code.

- Built **Rung**, an AI mock coding interview tutor for Berea's CS courses
- Teaching Assistant for **Operating Systems**, after a year TA'ing **Software Design & Implementation**
- Spent summer 2026 as a Software Developer on Berea's **Student Software Development Team (SSDT)**, shipping to production Flask apps used across campus
- Research capstone on **Object-Relational Mapping**
- Officer in Berea's **NSBE** and **SHPE** chapters and a **ColorStack** member
- Looking for **Summer 2027 software engineering internships** and happy to relocate

<br>

### Featured Project: Rung

<div align="center">
  <a href="https://github.com/conwelld/Rung">
    <img src="https://github-readme-stats-conwelld.vercel.app/api/pin/?username=conwelld&repo=Rung&theme=tokyonight&hide_border=true" alt="Rung repo card" />
  </a>
</div>

A Socratic mock interview tutor built around Berea's real CS coding interviews. Students get 30 minutes on a problem from their course's own question bank while an AI proctor coaches them one hint at a time. It climbs a hint ladder instead of handing over the answer. When time's up it grades the session on the department's four rubric dimensions: Communication, Problem Solving, Technical Competency and Debugging.

- **Zero answer leaks** across a 177-case adversarial test suite on two models, plus zero leaks against 96 attacks from an automated red-teamer I built to try and break it
- Server-side phase gate, timer, quotas and rate limiting so students can't skip ahead or burn through API credits. A class-code login keeps outsiders out
- Rubric grader scores each transcript using measured hint depth as evidence, then purges the transcript
- 7-table Peewee schema with an N+1 equivalence test, 100+ offline automated tests and a credential scanner that fails the build if a secret slips in
- Cut projected API cost from **$1,505 to $155 per semester** for a 30-student class so the department could actually afford to run it
- Deployed on Vercel

`Python` `Flask` `Peewee` `Claude API` `Vercel`

<br>

### Teaching

**Operating Systems TA** (Fall 2026)
- Grade all student work, proctor exams and run TA hours for a 13-student section
- Wrote new assignments and revised course documents covering scheduling, free lists and memory allocation in C++
- Have taught the class and work with the other TAs to keep the course running smoothly

**Software Design & Implementation TA** (2025 to 2026)
- Tested using AI as a study partner for the course's coding interviews myself, then coached students to use it the same way. The class saw roughly a **40% increase in A's**
- Helped host hackathons and workshops on using AI in coursework
- Trained other TAs on responsible AI use and how to spot when it's being misused, and gave a talk on agentic AI to the TA team

<br>

### Production Work @ SSDT (Summer 2026)

Software Developer on a 14+ person Agile team maintaining campus web apps that serve **2,000+ students & faculty**, save the college **$100K+ a year** and cut **170+ hours** of manual work annually. Every change went through code review and a GitHub Actions CI pipeline that runs the full test suite across Python 3.10 to 3.14.

**Labor Status Form**
Contributed to the full-stack Flask app that runs student labor hiring on campus.
- Helped streamline a manual workflow for **1,400+ users**, cutting processing workload by **20%**
- Worked across the Peewee ORM data layer over MySQL and the Bootstrap front end

**CELTS (Center for Excellence in Learning through Service)**
Full-stack Flask app for Berea's service-learning center.
- Streamlined how staff add volunteers to service events and create new events
- Made program data easier to reach for the staff who rely on it

`Flask` `Peewee` `MySQL` `Bootstrap` `GitHub Actions` `Agile`

<br>

### Research

**Object-Relational Mapping (CS Research Capstone)**
How ORM frameworks translate object-oriented models into relational schemas and where that translation breaks down. Covers the tradeoffs in abstraction, SQL generation and application architecture, grounded in using Peewee in production code.
`Research` `Databases` `Software Architecture`

<br>

### How I Build

I build with AI coding agents every day. **Claude Code**, **Codex** and **Cursor** help me move fast, and I use the **Anthropic API** inside my own projects. Speed is only half of it though. I want to be able to explain every line and every framework choice in what I ship, which is why Rung has more tests than features. I also hold Anthropic's **Claude 101** certification.

![Claude Code](https://img.shields.io/badge/-Claude%20Code-D97757?style=flat-square&logo=claude&logoColor=white)
![Codex](https://img.shields.io/badge/-Codex-000000?style=flat-square)
![Cursor](https://img.shields.io/badge/-Cursor-000000?style=flat-square&logo=cursor&logoColor=white)
![Anthropic API](https://img.shields.io/badge/-Anthropic%20API-191919?style=flat-square&logo=anthropic&logoColor=white)

<br>

### Tech Stack

**Languages**  
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frameworks & Libraries**  
![Flask](https://img.shields.io/badge/-Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Peewee](https://img.shields.io/badge/-Peewee%20ORM-4B8BBE?style=flat-square)
![Jinja](https://img.shields.io/badge/-Jinja-B41717?style=flat-square&logo=jinja&logoColor=white)
![Bootstrap](https://img.shields.io/badge/-Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![jQuery](https://img.shields.io/badge/-jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)

**Databases**  
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Tools & Platforms**  
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/-Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/-Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)

<br>

### Currently Learning

`Embedded Systems` &nbsp;·&nbsp; `Machine Learning` &nbsp;·&nbsp; `AI Agents & Skills` &nbsp;·&nbsp; `Object-Relational Mapping`

Right now that means prototyping an ESP32-S3 pantry tracker that uses RFID and an OLED screen to build a grocery list and push it to my phone.

<br>

### Top Languages

<div align="center">
  <img height="165px" src="https://github-readme-stats-conwelld.vercel.app/api/top-langs/?username=conwelld&layout=compact&theme=tokyonight&hide_border=true" alt="Top languages" />
</div>

<br>

<div align="center">

Met me at **AfroTech 2026**? I'd love to keep the conversation going!

**Let's connect:** [LinkedIn](https://www.linkedin.com/in/dayton-conwell/) · [Email](mailto:conwelld@berea.edu)

</div>
