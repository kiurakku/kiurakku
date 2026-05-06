<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f3a5f&height=150&section=header&text=kiurakku&fontSize=42&fontColor=58a6ff&desc=Cybersecurity%20%E2%80%94%20cloud%20%C2%B7%20vulns%20%C2%B7%20networks%20%C2%B7%20crypto%20%C2%B7%20binaries&descAlign=center&descSize=15&descColor=8b949e&animation=twinkling" alt="Header banner — nickname like Cloud9 title bar" width="100%" />
</div>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-kiurakku-181717?style=flat-square&logo=github)](https://github.com/kiurakku)
[![Telegram](https://img.shields.io/badge/Telegram-@SyntacticSugar-26A5E4?style=flat-square&logo=telegram&logoColor=white)](https://t.me/SyntacticSugar)
[![Email](https://img.shields.io/badge/Email-yanginero%40outlook.com-0078D4?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:yanginero@outlook.com)

[![Packages](https://img.shields.io/badge/Packages-kiurakku-1f6feb?style=flat-square&logo=github)](https://github.com/kiurakku?tab=packages)

</div>

### 📦 GitHub Packages

Публічні артефакти для лаб і hardening — див. [**вкладку Packages**](https://github.com/kiurakku?tab=packages) на профілі та репо [**security-lab-toolkit**](https://github.com/kiurakku/security-lab-toolkit):

| Тип | Що це | Як взяти |
|-----|--------|----------|
| **Container (GHCR)** | Легкий Alpine-shell для перевірок TLS/DNS/HTTP і Python `requests` | `docker pull ghcr.io/kiurakku/security-lab-toolkit:latest` |
| **npm** | `@kiurakku/http-security-headers` — базова мапа security headers для API | `npm install @kiurakku/http-security-headers` (registry GitHub Packages, див. README репо) |

### 🌱 Про мене

> 🔐 **Кібербезпека** — головний фокус: хмарна та інфраструктурна безпека, **reverse engineering / malware analysis**, моделювання загроз і **доказові ланцюги** (логи, телеметрія, нормалізація сигналів).
>
> Я не позиціоную себе як DevOps-інженера: інфраструктура та CI для мене — **місце застосування контролів і перевірки гіпотез атаки/захисту**, а не самоціль.
>
> **Мови, з якими найчастіше працюю:**  
> ![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
> ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
> ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
> ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
>
> **Зараз найбільше цікавить:** **безпека хмар** (GCP / GKE, IAM, конфігурації, мережева та контейнерна **поверхня атак** (attack surface)), **вразливості та misconfig** (CVE-контекст, політики, ескалація привілеїв), **мережі** (сегментація, egress/ingress, зловмисний і підозрілий трафік), **шифрування в інфраструктурі** (TLS, ключі, секрети, цілісність і доступність даних), плюс **статичний і динамічний аналіз бінарників** і відтворювані **security labs**, щоб перевіряти гіпотези атаки й захисту.

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&size=20&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=920&lines=Cybersecurity+%7C+Cloud+%26+Kubernetes+threat+modeling;Reverse+Engineering+%7C+Malware+analysis+%26+tooling;Detection+%7C+log+evidence+%26+defensive+automation" alt="Typing animation" />
</p>

### 🔭 Огляд

| GitHub stats | Streak |
| :---: | :---: |
| <img height="165" src="https://github-readme-stats.vercel.app/api?username=kiurakku&show_icons=true&theme=tokyonight&hide_border=true&hide_title=false&rank_icon=github" alt="GitHub stats" /> | <img height="165" src="https://github-readme-streak-stats.herokuapp.com/?user=kiurakku&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" alt="Contribution streak" /> |

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kiurakku&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top languages" />
</p>

### 🏆 GitHub Trophy

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=kiurakku&theme=onedark&column=7&no-frame=true&margin-w=10&margin-h=10" alt="GitHub trophies" />
</p>

### 🛠️ Стек (орієнтир) — 3 іконки

Іконки з **[skillicons.dev](https://skillicons.dev)** (векторні SVG через CDN, не скриншоти):

<p align="center">
  <img src="https://skillicons.dev/icons?i=gcp,jenkins,kubernetes&perline=3" alt="Google Cloud, Jenkins, Kubernetes — skillicons.dev" />
</p>

*GCP — хмарна безпека та hardening · Jenkins — CI/CD і перевірки в пайплайнах · Kubernetes — контейнерна поверхня атак, політики та runtime.*

---

### 🔎 Напрями роботи

- **Хмарна безпека та вразливості** — misconfig, IAM/WIF, мережеві політики в кластерах, сканування, журнали й ланцюг доказів до BigQuery/SIEM-логіки.
- **OWASP / API-ризики** — авторизація, BOLA/IDOR, сценарії зловживань.
- **Reverse engineering** — статичний/динамічний аналіз, crackme/лаби, власні інструменти під аналіз.
- **Детекція та «синя» сторона** — сигнали runtime, кореляція з інцидентами, відтворювані лабораторні сценарії.

*Актуальні репозиторії дивись у **Pinned** на профілі — тут без каталогу проєктів.*
