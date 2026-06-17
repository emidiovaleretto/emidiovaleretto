<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=44D62C&center=true&vCenter=true&random=false&width=600&lines=Hey+there%2C+I'm+Emidio+%F0%9F%91%8B;Backend+Engineer+%7C+Django+Specialist;Based+in+Dublin%2C+Ireland+%F0%9F%87%AE%F0%9F%87%AA;Virtual+Pilot+%E2%9C%88%EF%B8%8F+%7C+Bass+Player+%F0%9F%8E%B8" alt="Typing SVG" />
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/emidiovalereto/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://emidiovaleretto.dev/">
    <img src="https://img.shields.io/badge/Portfolio-44D62C?style=for-the-badge&logo=Google-Chrome&logoColor=black" />
  </a>
  <a href="mailto:emidio@valeretto.dev">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=emidiovaleretto&style=for-the-badge&color=44D62C&label=PROFILE+VIEWS" />
</p>

---

## 🧑‍💻 About Me

```python
from dataclasses import dataclass, field
from typing import List


@dataclass
class SoftwareEngineer:
    name: str = "Emidio Valeretto"
    location: str = "Dublin, Ireland 🇮🇪"
    role: str = "Backend Engineer"
    primary_stack: str = "Django REST Framework 🐍"

    languages: List[str] = field(default_factory=lambda: [
        "Python", "JavaScript", "TypeScript"
    ])

    technologies: dict = field(default_factory=lambda: {
        "backend":   ["Django", "Django REST Framework", "PostgreSQL", "Redis"],
        "frontend":  ["React Native", "Expo", "Tailwind CSS"],
        "devops":    ["Docker", "GitHub Actions", "AWS", "Nginx"],
        "testing":   ["pytest", "factory-boy", "pytest-django"],
    })

    currently_building: str = "simlog — a Flight Simulator companion app ✈️"
    hobbies: List[str] = field(default_factory=lambda: [
        "Microsoft Flight Simulator 2024 🛫",
        "Bass guitar 🎸",
        "Open source contributions 🌍",
    ])
    fun_fact: str = "I once diverted a transatlantic flight to JFK due to a fuel emergency... in a simulator. 😅"


me = SoftwareEngineer()
```

---

## 🚀 Tech Stack

### Core
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Django_REST-092E20?style=for-the-badge&logo=django&logoColor=ff1709" />
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white" />
</p>

### Mobile & Frontend
<p>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
</p>

### DevOps & Tools
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
</p>

### Testing
<p>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" />
  <img src="https://img.shields.io/badge/factory--boy-092E20?style=for-the-badge&logo=python&logoColor=white" />
</p>

---

## ✈️ Featured Project — simlog

> A companion app for Microsoft Flight Simulator 2024 — personal flight logbook, checklist manager and SimBrief integration.

<p>
  <a href="https://github.com/emidiovaleretto/simlog-api">
    <img src="https://img.shields.io/badge/simlog--api-092E20?style=for-the-badge&logo=django&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Status-In%20Development-44D62C?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Stack-Django_+_React_Native-3776AB?style=for-the-badge" />
</p>

```
✅ JWT Authentication        ✅ Flight Logbook CRUD
✅ SimBrief Integration      ✅ Checklist Manager
✅ 52 automated tests        ✅ CI/CD with GitHub Actions
🔄 React Native App          🔄 Deploy
```

---

## 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/emidiovaleretto">
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=emidiovaleretto&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true"/>
    <img height="180em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=emidiovaleretto&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&hide=jupyter%20notebook,tex,css,php"/>
  </a>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=emidiovaleretto&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=emidiovaleretto&theme=tokyonight&no-frame=true&row=1&column=7" />
</p>

---

## ⏱️ Weekly Coding Activity

<!--START_SECTION:waka-->

```python
From: 09 November 2021 - To: 15 June 2026

Total Time: 515 hrs 11 mins

Python        148 hrs 33 mins       >>>>>>>------------------   28.68 %
HTML          126 hrs 7 mins        >>>>>>-------------------   24.34 %
JavaScript    90 hrs 5 mins         >>>>---------------------   17.39 %
CSS           71 hrs 30 mins        >>>----------------------   13.80 %
Markdown      15 hrs 56 mins        >------------------------   03.08 %
TypeScript    13 hrs 19 mins        >------------------------   02.57 %
SCSS          8 hrs 6 mins          -------------------------   01.56 %
Text          5 hrs 46 mins         -------------------------   01.12 %
```

<!--END_SECTION:waka-->

---

## 🎸 Beyond the Code

- ✈️ **Virtual pilot** — Microsoft Flight Simulator 2024, flying the Airbus A320 family
- 🎸 **Bass player** — the low end is where the groove lives
- 🇮🇪 **Living in Dublin** — loving the craic (and the rain)
- 🌍 **Open source enthusiast** — if it helped you, drop a ⭐

---

<p align="center">
  <i>"First, solve the problem. Then, write the code." — John Johnson</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=44D62C&height=100&section=footer" />
</p>
