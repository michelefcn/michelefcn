# 👋 Hi, I'm Michele

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Inter&size=22&duration=3000&pause=1000&color=FFFFFF&center=true&vCenter=true&width=600&lines=Full+Stack+Developer;Backend+%26+Architecture+Focused;Clean+Code+Enthusiast;Problem+Solver" />
</p>

---

## 🚀 About me

💻 **Full Stack Developer** with a strong backend and infrastructure mindset.

* 🧠 Problem solver — I focus on *solutions that actually work in production*
* ⚙️ Deep interest in **architecture, performance and system design**
* 🧼 Clean code enthusiast (yes, formatting matters 😄)
* 🔐 Focus on reliability, security and long-term maintainability

---

## 🧰 Tech Stack

### Core Stack
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Inertia.js](https://img.shields.io/badge/Inertia.js-9553E9?style=flat&logo=inertia&logoColor=white)
![Vue 3](https://img.shields.io/badge/Vue%203-4FC08D?style=flat&logo=vue.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

### Ecommerce Platforms
![Magento 2](https://img.shields.io/badge/Magento%202-EE672F?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSI4MDBweCIgaGVpZ2h0PSI4MDBweCIgdmlld0JveD0iLTIzLjUgMCAzMDMgMzAzIiBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSJ4TWlkWU1pZCI+PHBhdGggZD0iTTE0NC44NTIgOTAuNjd2MTcyLjE5MmwtMTYuOTMzIDEwLjM0OS0xNi45NDYtMTAuNDA0VjkwLjgwM2wtNDMuODc4IDI3LjAxNnYxNDcuMjU1bDYwLjgyNCAzNy4yMTcgNjEuMzM5LTM3LjQ4MlYxMTcuNzI1TDE0NC44NTIgOTAuNjd6TTEyNy45MTkgMEwwIDc3LjUwMnYxNDcuMjc0bDMzLjIyMyAxOS41NzJWOTcuMDZsOTQuNzIyLTU3LjU5NiA5NC44MSA1Ny41MTIuMzkxLjIyMy0uMDQyIDE0Ni45MjlMMjU2IDIyNC43NzZWNzcuNTAyTDEyNy45MTkgMHoiIGZpbGw9IiNmZmZmZmYiLz48L3N2Zz4=&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat&logo=wordpress&logoColor=white)
![PrestaShop](https://img.shields.io/badge/PrestaShop-DF0067?style=flat&logo=prestashop&logoColor=white)
![Knockout.js](https://img.shields.io/badge/Knockout.js-CA1F1F?style=flat)

### Infrastructure & Runtime
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)

### Data & Analytics
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=flat&logo=googlebigquery&logoColor=white)

---

## 🧠 Deep Dive — Backend & Architecture

What I enjoy the most is designing systems that are:

* **Predictable under load**
* **Easy to debug**
* **Maintainable over time**
* **Data-consistent**

### My approach

* Separate concerns strictly (API / domain / infrastructure)
* Prefer **stateless services** when possible
* Use queues and async workflows to decouple heavy operations
* Design DB schemas with query patterns in mind (not just structure)
* Avoid over-engineering — but also avoid future pain

### Typical patterns I use

* REST APIs with clear boundaries
* Queue-based processing (jobs, events)
* Caching layers (Redis) to reduce DB pressure
* Data pipelines (BigQuery + scheduled queries)
* Reverse proxy + optimized Nginx configs
* Containerized environments (Docker)

---

## 🧱 Example Architecture (high-level)

```mermaid
flowchart LR

Client -->|HTTP| Nginx
Nginx --> App[Laravel App]

App -->|Cache| Redis
App -->|Search| Elastic[(Elasticsearch)]
App -->|DB| MySQL[(MySQL)]

App -->|Queue Jobs| Queue[Worker / Queue]
Queue --> MySQL

App -->|Data Export| BQ[(BigQuery)]
BQ -->|Analytics Queries| Dashboard[Frontend / BI]

Dashboard --> Client
```

---

## ⚡ Fun facts

* 🎾 Padel player
* 🖨️ 3D printing enthusiast
* 📺 Medical drama addicted (Grey’s Anatomy fan)

---

## 📫 Contact

* 🌐 https://michelefaccioni.it/
* 💼 https://linkedin.com/in/michele-faccioni
* 📧 [info@michelefaccioni.it](mailto:info@michelefaccioni.it)
* 📸 https://instagram.com/michele_faccioni

---

## 🧠 Philosophy

> Good code doesn’t need comments.
> It needs clarity.
