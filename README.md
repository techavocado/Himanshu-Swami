<div align="center">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Himanshu+Swami+%F0%9F%91%8B;Full+Stack+Web+Developer;CS+Student+%7C+Builder+%7C+Problem+Solver;Open+to+Internships+%26+Research+Opportunities" alt="Typing SVG" />
</div>
<div align="center">
<img src="https://komarev.com/ghpvc/?username=techavocado&style=flat-square&color=6366f1" alt="Profile views" />
&nbsp;
<a href="https://github.com/techavocado?tab=followers">
  <img src="https://img.shields.io/github/followers/techavocado?style=flat-square&color=6366f1" alt="Followers" />
</a>
&nbsp;
<img src="https://img.shields.io/badge/Open%20to-Internships-success?style=flat-square" />
</div>
 
## 👨‍💻 About Me
 
I'm a Computer Science undergraduate who builds **full-stack web applications** from scratch — designing database schemas, writing RESTful APIs, and crafting responsive frontends that work well on every device.
 
I care about the engineering decisions behind what I build, not just that it runs.
 
- 🔨 **StayVista** — a production-grade vacation rental platform (Airbnb-style) with MVC architecture, Cloudinary image hosting, MapTiler geocoded maps, Passport.js auth, and MongoDB-backed sessions
- ⛅ **Weather Dashboard** — a real-time weather analytics app with OpenWeatherMap API, Chart.js visualizations (temperature trends, wind bar charts, UV donut, AQI breakdown), and a React + Express full-stack setup deployed on Render
- 🌱 Exploring system design, scalable architecture, and data engineering with Python
- 🎯 Looking for internship and research project opportunities in software engineering
- 🏫 **B.Tech, Computer Science and Engineering — [Your College Name]**
- 📫 **[your.email@example.com]**
---
 
## 🛠️ Tech Stack
 
**Languages**
 
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
 
**Frontend**
 
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=flat-square&logo=bootstrap&logoColor=white)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)
 
**Backend**
 
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
 
**Databases**
 
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=flat-square&logo=mysql&logoColor=white)
 
**Data & Libraries**
 
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
 
**Tools & Platforms**
 
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=flat-square&logo=visual-studio-code&logoColor=white)
 
---
 
## 🚀 Featured Projects
 
### 🏨 StayVista — Vacation Rental Platform
 
> Node.js · Express 5 · MongoDB Atlas · Passport.js · Cloudinary · MapTiler · Bootstrap 5 · EJS
 
A full-stack property booking platform built with the MVC pattern. Users can list, discover, and review stays. Owners get full CRUD control over their listings; guests can search by location and leave star-rated reviews.
 
**What's under the hood:**
- Geocoded property locations stored as GeoJSON Points, rendered on interactive MapTiler maps
- Cloud image upload pipeline via Multer + Cloudinary with automatic fallback
- Session-based authentication with Passport.js and MongoDB-backed session persistence (`connect-mongo`)
- Server-side validation with Joi schemas; client-side with Bootstrap's constraint API
- Role-based authorization middleware (`isOwner`, `isLoggedIn`) protecting all write routes
- Cascading deletes — removing a listing cleans up all associated reviews atomically
- Mobile-first responsive design with a custom glassmorphism navbar and swipeable filter carousel
[![StayVista Repo](https://img.shields.io/badge/View_Repo-6366f1?style=flat-square&logo=github&logoColor=white)](https://github.com/techavocado/stayvista-app)
[![Live Demo](https://stayvista-xruc.onrender.com/)](#)
 
---
 
### ⛅ Weather Dashboard — Real-Time Analytics App
 
> React 19 · Vite · Node.js · Express · Chart.js · OpenWeatherMap API · Open-Meteo API
 
A full-stack weather analytics dashboard with a React frontend and a dedicated Express backend deployed on Render. Fetches real-time data from multiple weather APIs and renders it across purpose-built chart components.
 
**What's under the hood:**
- 5 interactive Chart.js visualizations: temperature line chart, wind speed bar chart, UV index donut, AQI pollutant breakdown (log scale), hourly forecast overlay
- Multi-API data pipeline: OpenWeatherMap (current weather, forecast, AQI), Open-Meteo (UV index, daily temps), geocoding via both providers
- Expandable overlay system — clicking any stat card opens a full detail view with deeper charts and hourly breakdowns
- Celsius / Fahrenheit toggle, trending city quick-search, animated temperature icons that change based on actual temperature range
- CORS-enabled Express backend proxying all API keys; deployed on Render with environment variable management
- Fully responsive — iOS bottom-sheet style overlay on mobile, 2-column grid for stat cards
[![Weather Dashboard Repo](https://img.shields.io/badge/View_Repo-6366f1?style=flat-square&logo=github&logoColor=white)](https://github.com/techavocado/weather-dashboard)
[![Live Demo](https://img.shields.io/badge/Live_Demo-46E3B7?style=flat-square&logo=render&logoColor=black)](https://weather-dashboard-sage-pi.vercel.app/)
 
---
 
## 📊 GitHub Stats
 
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=techavocado&show_icons=true&theme=default&hide_border=true&count_private=true&title_color=6366f1&icon_color=6366f1" height="150" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=techavocado&layout=compact&theme=default&hide_border=true&title_color=6366f1" height="150" />
</div>
<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=techavocado&theme=default&hide_border=true&ring=6366f1&fire=6366f1&currStreakLabel=6366f1" height="150" />
</div>
---
 
## 🌱 Currently Learning
 
- System design fundamentals — database indexing, caching, load balancing
- TypeScript for safer, more scalable JavaScript codebases
- Docker and containerization for reproducible deployments
- React Query and state management patterns at scale
---
 
## 🎯 Goals
 
- Contribute to open source projects in the web tooling / backend ecosystem
- Secure a software engineering internship where I can work on real production systems
- Build a data engineering side project combining Python (Pandas, NumPy) with a web frontend
---
 
## 🤝 Connect
 
<a href="https://www.linkedin.com/in/himanshu-swami-179bba360?utm_source=share_via&utm_content=profile&utm_medium=member_android">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" />
</a>
&nbsp;
<a href="mailto:himanshuswami770@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" />
</a>
&nbsp;
<a href="https://github.com/techavocado">
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
</a>
---
 
<div align="center">
  <i>Open to internship and research project opportunities in software engineering and full-stack development.</i>
</div>
