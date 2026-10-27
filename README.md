<!-- ═══════════════════════════════  HEADER  ═══════════════════════════════ -->
<div align="center">

<img src="./assets/header.svg" width="100%" alt="Oscar Peris Espejo — Gameplay Systems Programmer · Data & ETL Engineer"/>

<a href="https://github.com/BerserkurNokk21">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=20&duration=2800&pause=900&color=E4FF3C&center=true&vCenter=true&width=640&lines=%3E+gameplay+%26+systems+in+Unity+%2F+C%23;%3E+ETL+pipelines+%26+PostgreSQL+in+production;%3E+python+%C2%B7+fastapi+%C2%B7+linux;%3E+games+and+data%3A+same+discipline%2C+different+output" alt="Typing SVG" />
</a>

<p>
  <a href="https://www.linkedin.com/in/oscar-peris-espejo-386370360"><img src="https://img.shields.io/badge/LinkedIn-14161C?style=for-the-badge&logo=linkedin&logoColor=E4FF3C" alt="LinkedIn"/></a>
  <a href="https://portfolio-brown-alpha-5gusayizuc.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-14161C?style=for-the-badge&logo=vercel&logoColor=E4FF3C" alt="Portfolio"/></a>
  <a href="mailto:operisespejo@gmail.com"><img src="https://img.shields.io/badge/Email-E4FF3C?style=for-the-badge&logo=gmail&logoColor=0A0A0F" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Valencia,_Spain-14161C?style=for-the-badge&logo=googlemaps&logoColor=FF2E88" alt="Location"/>
</p>

</div>

<!-- ═══════════════════════════════  ABOUT  ═══════════════════════════════ -->

### `//` about_me

I build two kinds of systems: **games** and **data pipelines**. By day I run ETL and PostgreSQL infrastructure in production; the rest of the time I program gameplay and systems in **Unity/C#**. Different outputs, same problem underneath: keeping state correct when everything around it moves.

```python
class Oscar:
    def __init__(self):
        self.role      = ["Gameplay & Systems Programmer", "Data / ETL Engineer"]
        self.based_in  = "Valencia, Spain"
        self.education = [
            "BSc Videogame Design & Development — Florida Universitaria",
            "Higher Technician, Network Systems Administration (ASIR) — Tobalcaide",
        ]
        self.focus     = {
            "gamedev": ["gameplay systems", "combat & AI", "co-op / networking"],
            "backend": ["ETL", "data quality", "REST & WebSockets APIs"],
        }
        self.learning  = ["FastAPI", "AI fundamentals (IBM SkillsBuild)"]
        self.open_to   = ["gameplay/systems programming", "backend & data engineering"]

    def __str__(self):
        return "A game loop and a data pipeline share one enemy: state you can't trust."
```

<!-- ═══════════════════════════════  STACK  ═══════════════════════════════ -->

### `//` tech_stack

<p align="center">
  <kbd><b>Gamedev</b><br><br><img src="https://skillicons.dev/icons?i=unity,cs&theme=dark" height="40"/></kbd>&nbsp;
  <kbd><b>Backend</b><br><br><img src="https://skillicons.dev/icons?i=py,fastapi,dotnet&theme=dark" height="40"/></kbd>&nbsp;
  <kbd><b>Data</b><br><br><img src="https://skillicons.dev/icons?i=postgres,sqlite&theme=dark" height="40"/></kbd>&nbsp;
  <kbd><b>Mobile</b><br><br><img src="https://skillicons.dev/icons?i=flutter&theme=dark" height="40"/></kbd>&nbsp;
  <kbd><b>Ops & tools</b><br><br><img src="https://skillicons.dev/icons?i=linux,bash,git,github,rider,vscode&theme=dark" height="40"/></kbd>
</p>

<!-- ═══════════════════════════════  PROJECTS  ═══════════════════════════════ -->

### `//` active_processes

<table>
<tr>
<td width="50%" valign="top">

**Cael Cyberpunk** &nbsp;<img src="https://img.shields.io/badge/in_progress-E4FF3C?style=flat-square"/>

Solo action game focused on **systems programming**: combat built around telegraphed enemy archetypes, a multi-phase boss, and a hybrid scrap/loot economy feeding a node-based implant crafting system.

<sub>`Unity` · `C#` · `Gameplay systems` · `Enemy AI`</sub>

<!-- TODO: 🔗 repo · ▶️ itch.io · 🎞️ gameplay GIF -->

</td>
<td width="50%" valign="top">

**Crazy Coffee** &nbsp;<img src="https://img.shields.io/badge/prototyping-FF2E88?style=flat-square"/>

4-player chaotic co-op with ragdoll physics: run a coffee shop, hit the daily order quota, spend your cut on upgrades. I'm the **producer** and built the player controller and camera.

<sub>`Unity 6.3 LTS` · `URP` · `C#` · `Co-op` · `Team of 3`</sub>

<!-- TODO: 🔗 repo / devlog -->

</td>
</tr>
<tr>
<td width="50%" valign="top">

**TheCrew** &nbsp;<img src="https://img.shields.io/badge/in_progress-E4FF3C?style=flat-square"/>

Live-map convoy app for a car crew: invite-code crews, real-time positions over WebSockets, and saved meetups (route, duration, participants). Backend written from scratch in Python.

<sub>`FastAPI` · `PostgreSQL` · `WebSockets` · `Flutter`</sub>

<!-- TODO: 🔗 repo -->

</td>
<td width="50%" valign="top">

**dataops-ecoservice** &nbsp;<img src="https://img.shields.io/badge/designing-8A8F98?style=flat-square"/>

Data-quality service that audits client databases, flags inconsistent or malformed records and checks ETL integrity, adding LLM-based fuzzy matching on top of classic validation rules.

<sub>`Python` · `pandas` · `PostgreSQL` · `LLM APIs`</sub>

<!-- TODO: 🔗 repo -->

</td>
</tr>
</table>

<!--
  When a repo is public, swap its TODO for a pinned card (replace REPO_NAME):
  <a href="https://github.com/BerserkurNokk21/REPO_NAME"><img src="https://github-readme-stats-iota-weld-78.vercel.app/api/pin/?username=BerserkurNokk21&repo=REPO_NAME&hide_border=true&bg_color=0A0A0F&title_color=E4FF3C&icon_color=E4FF3C&text_color=F4F6EE"/></a>
-->

<!-- ═══════════════════════════════  EXPERIENCE  ═══════════════════════════════ -->

### `//` experience_log

**Database Technician & ETL Developer** · [Winfra](https://www.winfra.es/) · *Oct 2020 — present*

```diff
+ ETL processing time          -38%   redesigned transformation & loading jobs
+ Data loss in integrations    -30%   validation & consistency checks
+ Recovery time after failure  ~1h    restore procedures for production DBs
+ Incident resolution          +25%   across enterprise data infrastructure
```

<sub>Data transformations in **.NET / C#** and **Python** · **PostgreSQL** on **Linux** servers</sub>

<!-- ═══════════════════════════════  CERTS  ═══════════════════════════════ -->

### `//` certifications

<p>
  <a href="https://www.freecodecamp.org/certification/berserkurnokk/python-v9"><img src="https://img.shields.io/badge/Python_Developer-freeCodeCamp-14161C?style=flat-square&logo=freecodecamp&logoColor=E4FF3C&labelColor=0A0A0F"/></a>
  <a href="https://www.hackerrank.com/certificates/2880dc0e391a"><img src="https://img.shields.io/badge/SQL_(Basic)-HackerRank-14161C?style=flat-square&logo=hackerrank&logoColor=E4FF3C&labelColor=0A0A0F"/></a>
  <a href="https://www.hackerrank.com/certificates/iframe/79fd391765be"><img src="https://img.shields.io/badge/SQL_(Intermediate)-HackerRank-14161C?style=flat-square&logo=hackerrank&logoColor=E4FF3C&labelColor=0A0A0F"/></a>
  <img src="https://img.shields.io/badge/AI_Fundamentals-IBM_SkillsBuild_·_in_progress-14161C?style=flat-square&logo=ibm&logoColor=8A8F98&labelColor=0A0A0F"/>
</p>

<!-- ═══════════════════════════════  ACTIVITY  ═══════════════════════════════ -->

### `//` activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=BerserkurNokk21&bg_color=0A0A0F&color=8A8F98&title_color=E4FF3C&line=E4FF3C&point=FF2E88&area=true&area_color=E4FF3C&hide_border=true&radius=0" width="100%" alt="Contribution graph"/>

<img src="https://raw.githubusercontent.com/BerserkurNokk21/BerserkurNokk21/output/github-snake-dark.svg" width="100%" alt="Contribution snake"/>

</div>

<details>
<summary><b>// more_stats</b></summary>
<br/>
<div align="center">

<img src="https://github-readme-stats-iota-weld-78.vercel.app/api?username=BerserkurNokk21&show_icons=true&hide_border=true&bg_color=0A0A0F&title_color=E4FF3C&icon_color=E4FF3C&text_color=F4F6EE&border_radius=0" height="165"/>
<img src="https://github-readme-stats-iota-weld-78.vercel.app/api/top-langs/?username=BerserkurNokk21&layout=compact&hide_border=true&bg_color=0A0A0F&title_color=E4FF3C&text_color=F4F6EE&border_radius=0" height="165"/>

<img src="https://streak-stats.demolab.com/?user=BerserkurNokk21&hide_border=true&border_radius=0&background=0A0A0F&ring=E4FF3C&fire=FF2E88&currStreakNum=F4F6EE&currStreakLabel=E4FF3C&sideNums=F4F6EE&sideLabels=8A8F98&dates=8A8F98&stroke=262A1A"/>

</div>
</details>

<!-- ═══════════════════════════════  FOOTER  ═══════════════════════════════ -->

<div align="center">
<br/>
<sub>Open to <b>gameplay/systems programming</b> and <b>backend & data engineering</b> roles — <a href="mailto:operisespejo@gmail.com">let's talk</a>.</sub>

<img src="./assets/footer.svg" width="100%" alt=""/>
</div>
