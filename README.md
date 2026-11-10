<!-- ===================== HEADER ===================== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=venom&color=0:7C3AED,50:6366F1,100:22D3EE&height=280&section=header&text=Omar%20Elmallah&fontSize=70&fontColor=ffffff&fontAlignY=36&animation=twinkling&desc=Full-Stack%20Developer%20%C3%97%20Machine%20Learning%20Engineer&descSize=22&descAlignY=58" alt="header" />

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=700&height=50&lines=Hi+there%2C+I'm+Omar+%F0%9F%91%8B;Full-Stack+Developer;Machine+Learning+Engineer;Next.js+%2B+FastAPI+%2B+PostgreSQL;Bridging+Web+%26+AI+%F0%9F%9A%80" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Omar404X0.Omar404X0&left_color=0D1117&right_color=7C3AED" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Cairo%2C_Egypt-22D3EE?style=for-the-badge&logo=googlemaps&logoColor=white&labelColor=0D1117" alt="Location" />
  <img src="https://img.shields.io/badge/Open_to-Remote_Internships-A78BFA?style=for-the-badge&labelColor=0D1117" alt="Open to work" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/omar-elmallah-a57266406"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn" /></a>
  <a href="mailto:elmallahomar24@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Gmail" /></a>
  <a href="https://electro-frontend-khaki.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-Electro-7C3AED?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" alt="Live Demo" /></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== ABOUT ===================== -->
## 👨‍💻 About Me

<table>
  <tr>
    <td width="60%" valign="top">

```python
class Omar:
    role      = ["Full-Stack Developer", "AI Student"]
    location  = "Cairo, Egypt"
    stack     = ["Next.js", "React", "FastAPI", "PostgreSQL"]
    building  = "Electro: e-commerce + AI shopping assistant"
    next_up   = "Product recommendation model on order data"
    learning  = ["MLOps", "Model deployment", "Redis"]
    open_to   = "Remote internships"
    ask_me    = ["Python", "JS/TS", "React", "Next.js", "SQL", "REST APIs"]
```

  </td>
    <td width="40%" valign="top">

🚀 **Full-Stack Developer** who ships real, deployed products

🧠 **AI student** focused on putting models inside production apps

🤝 **Let's collaborate on:** AI-powered web apps & production-ready interfaces

⚡ **Fun fact:** I fixed a checkout race condition with a single atomic SQL statement

  </td>
  </tr>
</table>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== FEATURED PROJECT ===================== -->
## ⚡ Featured Project: Electro

> **A deployed electronics store with a Gemini-powered assistant that answers only from the store's real catalog.**

| 🛍️ Customers | 🛠️ Admins | 🤖 AI Assistant |
|:--|:--|:--|
| Browse, search, manage cart and checkout | Manage products, users and orders | Grounded in live inventory, API key kept server-side |

**Highlights**

- 🛡️ **Race-condition-safe checkout** using one atomic SQL `UPDATE ... WHERE stock > 0`
- 🔐 **JWT auth** (1-hour expiry), bcrypt hashing, admin checks re-verified in the database
- 🤖 **AI shopping assistant** that never invents products
- 🌗 Dark/light themes, instant search (`Ctrl/⌘ + K`), fully responsive

### 🏗️ Architecture

```mermaid
flowchart LR
    U([👤 User]) --> F["🎨 Next.js · TypeScript · Tailwind<br/><i>Vercel</i>"]
    F -->|REST + JWT| B["⚙️ FastAPI · SQLAlchemy<br/><i>Render</i>"]
    B --> D[("🗄️ PostgreSQL")]
    B -->|catalog context| G["🤖 Gemini"]
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,ts,tailwind,fastapi,postgres&theme=dark" alt="Electro stack" />
</p>

<p align="center">
  <a href="https://electro-frontend-khaki.vercel.app"><img src="https://img.shields.io/badge/🔗_Live_Demo-7C3AED?style=for-the-badge&labelColor=0D1117" alt="Live Demo" /></a>
  <a href="https://github.com/Omar404X0/Electro-Backend"><img src="https://img.shields.io/badge/💻_Backend_Repo-A78BFA?style=for-the-badge&logo=github&labelColor=0D1117" alt="Backend" /></a>
  <a href="https://github.com/Omar404X0/Electro-Frontend"><img src="https://img.shields.io/badge/💻_Frontend_Repo-22D3EE?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117" alt="Frontend" /></a>
  <a href="https://electro-backend-2dx5.onrender.com/docs"><img src="https://img.shields.io/badge/📘_API_Docs-009688?style=for-the-badge&logo=swagger&logoColor=white&labelColor=0D1117" alt="API Docs" /></a>
</p>

<p align="center"><sub>⏳ The API runs on a free tier, so the first request can take up to a minute to wake up.</sub></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== ROADMAP ===================== -->
## 🧭 Roadmap

| Goal | Status |
|:--|:--|
| Electro: full-stack store + AI assistant | ![Done](https://img.shields.io/badge/Shipped-22C55E?style=flat-square&labelColor=0D1117) |
| Product recommendation model (order data) | ![In progress](https://img.shields.io/badge/In_progress-F59E0B?style=flat-square&labelColor=0D1117) |
| Docker | ![Done](https://img.shields.io/badge/Done-22C55E?style=flat-square&labelColor=0D1117) |
| Database optimization with SQLAlchemy | ![Done](https://img.shields.io/badge/Done-22C55E?style=flat-square&labelColor=0D1117) |
| Redis (caching & fast data access) | ![Learning](https://img.shields.io/badge/Learning-A78BFA?style=flat-square&labelColor=0D1117) |
| MLOps & model deployment | ![Learning](https://img.shields.io/badge/Learning-A78BFA?style=flat-square&labelColor=0D1117) |

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== TECH STACK ===================== -->
## 💻 Tech Stack

<h3 align="center">🎨 Frontend</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,ts,js,html,css,tailwind&theme=dark" alt="Frontend" />
</p>

<h3 align="center">⚙️ Backend & APIs</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,fastapi&theme=dark" alt="Backend" /><br/>
  <img src="https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white&labelColor=0D1117" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white&labelColor=0D1117" alt="Pydantic" />
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white&labelColor=0D1117" alt="JWT" />
  <img src="https://img.shields.io/badge/REST_APIs-7C3AED?style=for-the-badge&logo=postman&logoColor=white&labelColor=0D1117" alt="REST APIs" />
</p>

<h3 align="center">🗄️ Databases</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,sqlite,mysql&theme=dark" alt="Databases" />
</p>

<h3 align="center">🧠 Data, ML & AI</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=pandas,numpy,sklearn&theme=dark" alt="ML" /><br/>
  <img src="https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white&labelColor=0D1117" alt="Gemini" />
</p>

<h3 align="center">🧰 Languages, DevOps & Tools</h3>
<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,docker,git,github,vercel,vscode&theme=dark" alt="Tools" /><br/>
  <img src="https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black&labelColor=0D1117" alt="Render" />
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== STATS ===================== -->
## 📊 GitHub Stats

<p align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=Omar404X0&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9&icon_color=22D3EE&ring_color=7C3AED" alt="GitHub Stats" />
  <img height="180" src="https://streak-stats.demolab.com/?user=Omar404X0&hide_border=true&background=0D1117&ring=7C3AED&fire=22D3EE&currStreakNum=A78BFA&sideNums=A78BFA&currStreakLabel=22D3EE&sideLabels=C9D1D9&dates=8B949E" alt="GitHub Streak" />
</p>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Omar404X0&hide_border=true&include_all_commits=true&count_private=true&layout=compact&langs_count=6&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9" alt="Top Languages" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Omar404X0&bg_color=0D1117&color=A78BFA&line=7C3AED&point=22D3EE&area=true&area_color=7C3AED&hide_border=true" alt="Activity Graph" />
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== SNAKE ===================== -->
## 🐍 Contribution Snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Omar404X0/Omar404X0/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Omar404X0/Omar404X0/output/github-snake.svg" />
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/Omar404X0/Omar404X0/output/github-snake-dark.svg" />
  </picture>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:7C3AED,100:22D3EE&height=3" alt="divider" />

<!-- ===================== TROPHIES ===================== -->
## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Omar404X0&theme=tokyonight&no-frame=true&no-bg=true&column=7" alt="Trophies" />
</p>

<!-- ===================== CONTACT ===================== -->
## 📫 Let's Build Something

<p align="center">
  <b>Open to remote internships and AI-powered web app collaborations.</b><br/><br/>
  <a href="mailto:elmallahomar24@gmail.com"><img src="https://img.shields.io/badge/Say_Hello-elmallahomar24@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/omar-elmallah-a57266406"><img src="https://img.shields.io/badge/Connect-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" alt="LinkedIn" /></a>
</p>

<!-- ===================== FOOTER ===================== -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:6366F1,100:22D3EE&height=140&section=footer&text=Thanks%20for%20stopping%20by!&fontSize=24&fontColor=ffffff&fontAlignY=70" alt="footer" />
