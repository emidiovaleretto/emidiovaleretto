<h1 align="center">Hi <img src="https://raw.githubusercontent.com/nixin72/nixin72/master/wave.gif" alt="Waving hand animated gif" height="45" width="45" /> I'm Emidio</h1>
<h3 align="center">A passionate technophile always seeking new knowledge in this wonderful field.</h3>

<div align="center">

[![Linkedin: emidio](https://img.shields.io/badge/-emidio-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/emidiovalereto/)](https://www.linkedin.com/in/emidiovalereto/)
![GitHub followers](https://img.shields.io/github/followers/emidiovaleretto?label=Follow&style=social)
[![My Portfolio](https://img.shields.io/badge/Website-46a2f1.svg?&style=flat-square&logo=Google-Chrome&logoColor=white&link=https://emidiovaleretto.dev/)](https://emidiovaleretto.dev/)
![Visitor Count](https://visitor-badge.laobi.icu/badge?page_id=emidiovaleretto.emidiovaleretto)
![Waka Readme](https://github.com/emidiovaleretto/emidiovaleretto/workflows/Waka%20Readme/badge.svg)

</div>

<p align="center">
  <img height="50%" width="auto" src ="https://github-readme-stats.vercel.app/api?username=emidiovaleretto&show_icons=true&count_private=true&theme=darcula&hide_border=true&hide=issues,contribs&bg_color=00000000">
  <img height="50%" width="auto" src ="https://github-readme-stats.vercel.app/api/top-langs/?username=emidiovaleretto&layout=compact&hide_border=true&theme=darcula&bg_color=00000000&langs_count=6&hide=jupyter%20notebook,tex,css,php&exclude_repo=Pacman-AI">
  <img src ="https://github-readme-streak-stats.herokuapp.com?user=emidiovaleretto&theme=darcula&hide_border=true&background=FFFFFF00">
</p>

## 🙋‍♂️ About Me

- 🔭 I’m currently working on **freelance projects and open-source contributions**
- 👯 I’m looking to collaborate on **Open Source Projects**
- ⚡ Fun fact **I like to play the bass guitar to soothe my soul.**

## 🚀 A little more about me...

``` python
from random import choice
from pprint import pprint


class SoftwareEngineer:
    def __init__(self):
        self._pronouns = ["He", "Him"]
        self._code = ["JavaScript", "Python", "Java", "Kotlin"]
        self._ask_me_about = ["dadhood", "web dev", "tech", "app dev", "bass"]
        self._technologies = {
            "frameworks": {
                    "back_end": ["Django", "Django Rest Framework"],
                    "front_end": ["Tailwindcss"]
            },
            "back_end": {"js": ["Node"]},
            "mobile_app": {"native": ["Android Development"]},
            "dev_ops": ["AWS", "Docker🐳", "Azure", "Nginx"],
            "databases": ["PostgreSQL", "MySql", "SQLite"],
        }
        self._architecture = ["Serverless Architecture", "Progressive web applications", "Single page applications"]
        self._current_focus = "No Focus point at this time"
        self._fun_fact = self.generate_random_joke()

    @property
    def properties(self):
        return {
            "pronouns": self._pronouns,
            "code": self._code,
            "ask_me_about": self._ask_me_about,
            "technologies": self._technologies,
            "architecture": self._architecture,
            "current_focus": self._current_focus,
            "fun_fact": self._fun_fact
        }

    def generate_random_joke(self):
        jokes = [
            "Why do programmers prefer dark mode? Because light attracts bugs.",
            "Why do developers prefer to code in their underwear? Because it's a byte-sized problem.",
            "What do you call a programmer who doesn't know how to code? A manager."
        ]
        return choice(jokes)


me = SoftwareEngineer()
pprint(me.properties)
```

<!--START_SECTION:waka-->

```python
From: 09 November 2021 - To: 07 June 2025

Total Time: 479 hrs 42 mins

Python        138 hrs 23 mins >>>>>>>------------------   28.68 %
HTML          114 hrs 44 mins >>>>>>-------------------   23.78 %
JavaScript    89 hrs 27 mins  >>>>>--------------------   18.54 %
CSS           70 hrs 55 mins  >>>>---------------------   14.70 %
Markdown      11 hrs 56 mins  >------------------------   02.47 %
TypeScript    9 hrs 29 mins   -------------------------   01.97 %
SCSS          8 hrs 6 mins    -------------------------   01.68 %
Text          5 hrs 26 mins   -------------------------   01.13 %
```

<!--END_SECTION:waka-->

## 📝 Contribution Guidelines
If you want to contribute, please follow these guidelines:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
