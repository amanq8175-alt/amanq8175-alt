<div align="center">

<!-- ANIMATED BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Aman%20Qureshi&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Developer%20Aman%20%E2%80%94%20Frontend%20Architect&descAlignY=58&descSize=20&animation=fadeIn" width="100%" />

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&pause=1000&color=A78BFA&center=true&vCenter=true&width=600&lines=Senior+Frontend+Architect;React+%26+Next.js+Expert;Zustand+%26+TanStack+Query+Specialist;CS+Scholar+%40+Sindh+University" alt="Typing SVG" />
</a>

<br/>

<!-- PROFILE VIEWS & SOCIAL STATS -->
<p>
  <img src="https://komarev.com/ghpvc/?username=developer-aman&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS" />
  <img src="https://img.shields.io/badge/Experience-1%2B%20Year-7c3aed?style=for-the-badge&logo=lightning&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-22c55e?style=for-the-badge&logo=checkmark&logoColor=white" />
</p>

</div>

---

## `$ whoami`

```ts
const AmanQureshi = {
  alias       : "Developer Aman",
  role        : "Senior Frontend Architect",
  institution : "University of Sindh — Computer Science",
  experience  : "1+ Year Professional Frontend Engineering",
  location    : "Karachi, Sindh, Pakistan 🇵🇰",
  philosophy  : "CS-grade thinking. Production-grade execution.",
  currentFocus: ["Next.js 14 App Router", "TanStack Query v5", "Zustand Architecture"],
  openTo      : ["Freelance", "Remote Roles", "Open Source Collabs"],
};
```

---

## `$ cat about.md`

I am a **Computer Science student at Sindh University** who operates at a **master-level** in modern frontend engineering. My foundation in algorithms, data structures, and system design from academia directly informs the scalable, performant UIs I build in production.

I don't just write components — I architect **frontend systems**: designing state graphs before a single line of JSX, choosing the right server-state boundary, and engineering user experiences that feel instantaneous.

> **Bridging the gap between academic rigor and professional craftsmanship — one component at a time.**

---

## `$ ls skills/`

### ⚡ Frameworks & Core

<p>
  <img src="https://img.shields.io/badge/React_18-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Next.js_14-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript_ES2024-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
</p>

### 🧠 State & Server-State Management

<p>
  <img src="https://img.shields.io/badge/TanStack_Query_v5-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logo=zustand&logoColor=white" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
</p>

### 🎨 Styling & UI Systems

<p>
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Framer_Motion-0055FF?style=for-the-badge&logo=framer&logoColor=white" />
  <img src="https://img.shields.io/badge/Shadcn%2FUI-000000?style=for-the-badge&logo=shadcnui&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS_Modules-264DE4?style=for-the-badge&logo=css3&logoColor=white" />
</p>

### 🔧 Tooling & DevOps

<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" />
  <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white" />
</p>

---

## `$ cat projects/case-studies.md`

> [!IMPORTANT]
> ### 🛒 B2B E-Commerce Platform
> **Stack:** Next.js 14 · TypeScript · TanStack Query v5 · Zustand · Shadcn UI · Tailwind CSS
>
> A full-scale B2B e-commerce system engineered with a clean server-state/client-state boundary. TanStack Query manages all async data flows — paginated product listings, cart mutations with optimistic updates, and background refetching on window focus. Zustand handles the lightweight global UI state (drawer open states, active filters, selected vendor) without the Redux overhead. The architecture scales horizontally: adding a new resource requires zero rewiring of global state.
>
> **Key Engineering Decisions:**
> - `queryClient` prefetching on route transitions for zero-loading-state navigations
> - Zustand slices pattern for clean domain separation
> - Zod schema validation at the API boundary before data enters the query cache

> [!TIP]
> ### 🐦 Twitter Clone — Real-time Architecture
> **Stack:** React 18 · TypeScript · TanStack Query · Zustand · Framer Motion · Tailwind CSS
>
> A high-fidelity Twitter/X clone built with a focus on **real-time UX patterns** and **Optimistic UI**. Every like, repost, and reply updates the UI instantly before the server confirms — rolling back gracefully on error. Used TanStack Query's `onMutate` / `onError` / `onSettled` lifecycle to implement textbook optimistic updates. Framer Motion powers the micro-interactions: post appearing animations, like button springs, and smooth feed transitions.
>
> **Key Engineering Decisions:**
> - Infinite scroll with `useInfiniteQuery` and intersection observers
> - Shared Zustand store for auth state and modal management
> - Stale-while-revalidate strategy for the home feed

---

## `$ cat stats/dashboard.md`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=developer-aman&show_icons=true&theme=tokyonight&border_radius=12&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=7C3AED&text_color=C9D1D9&rank_icon=github" height="170" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=developer-aman&layout=compact&theme=tokyonight&border_radius=12&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=C9D1D9&langs_count=8" height="170" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=developer-aman&theme=tokyonight&border_radius=12&hide_border=true&background=0D1117&stroke=7C3AED&ring=A78BFA&fire=FF6B6B&currStreakLabel=A78BFA&sideLabels=A78BFA&dates=C9D1D9" height="170" />

</div>

---

## `$ cat activity/graph.md`

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=developer-aman&theme=tokyo-night&bg_color=0D1117&color=A78BFA&line=7C3AED&point=FF6B6B&hide_border=true&radius=8" width="100%" />
</div>

---

## `$ cat contact/social.md`

<div align="center">

**Let's build something extraordinary.**

<p>
  <a href="https://linkedin.com/in/developer-aman">
    <img src="https://img.shields.io/badge/LinkedIn-Developer%20Aman-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  &nbsp;
  <a href="https://instagram.com/developer.aman">
    <img src="https://img.shields.io/badge/Instagram-@developer.aman-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
  &nbsp;
  <a href="mailto:amanqureshi.dev@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-amanqureshi.dev-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
</p>

<br/>

*"The best frontend engineers are system thinkers who happen to love CSS."*

</div>

---

<!-- FOOTER WAVE -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer&animation=fadeIn" width="100%" />

<div align="center">
  <sub>Crafted with precision by <strong>Developer Aman</strong> · Sindh University · Frontend Architect</sub>
</div>





<h1 align="center">👋 Hi, I'm Aman Qureshi</h1>

<h3 align="center"> Frontend Developer | 💻 React And Next.js  Enthusiast | </h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=24&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Hi+I'm+Aman+Qureshi;Frontend+Developer;I+build+modern+responsive+web+apps;React+%7C+JavaScript+%7C+Tailwind+CSS;Clean+UI+%7C+Smooth+UX+%7C+Modern+Design" />
</p>

<p align="center">
  <a href="#-connect-with-me">
    <img src="https://img.shields.io/badge/Status-Open%20To%20Work-success?style=for-the-badge&logo=github" />
  </a>
</p>

---

## 👨‍💻 About Me
Hello! I'm **Aman Qureshi**, a passionate **Frontend Developer** who loves turning complex problems into beautiful, intuitive, and high-performance web experiences. I don't just write code; I craft digital interfaces that feel premium.

- 🚀 **1+ Year of Experience** in the frontend ecosystem.
- 🎓 Education from **Sindh University**.
- 💡 Focused on **React**,  **Typescript**,**Next.js**, and **Tailwind CSS**.
- 🎯 Goal: To build products that bridge the gap between design and functionality.

---

## 🛠️ Technical Arsenal

### 💻 Languages & Logic
<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" />
</p>

### 🏗️ Frameworks & Libraries
<p align="left">
  <img src="https://img.shields.io/badge/React.js-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white" />
</p>

### 🔧 Tools & Design
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</p>


## ⚡ Current Learning & Goals
- 📚 Currently mastering **Advanced TypeScript** for more robust applications.
- 🏗️ Building **Full-Stack** knowledge by exploring Node.js and Databases.
- 🤝 Goal: Contribute to major **Open Source** projects in 2026.

---

---

## 🛠️ Tech Stack

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)


## 🛠️Skills

### 🌐 Languages

**HTML5, CSS3, JavaScript (ES6+), TypeScript**
Experienced in building responsive and accessible web interfaces using modern JavaScript and TypeScript.

### 🎨 Styling & UI

**TailwindCSS, Sass, SCSS, Bootstrap**
Strong experience in modern styling techniques, responsive layouts, Flexbox, Grid, and scalable CSS architecture.

### ⚛️ Frameworks

**React.js, Next.js**
Building component-based modern web applications with high performance, reusable UI components, and optimized rendering.

### 🧠 State Management

**Redux, Zustand**
Managing global state and application data efficiently in complex React applications.

### 🔄 Data Fetching

**TanStack Query (React Query)**
Handling server state, API data caching, background updates, and optimized data fetching.

### 🧩 UI Libraries

**Material UI, ShadCN UI**
Creating modern, accessible, and professional UI components for scalable applications.

### 🎞️ Animations

**Framer Motion**
Building smooth UI animations, page transitions, and interactive user experiences.


---

## 📊 GitHub Stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=amanq8175-alt&show_icons=true&theme=tokyonight)

---

## 🔥 GitHub Streak

---
![GitHub Streak](https://streak-stats.demolab.com?user=amanq8175-alt&theme=tokyonight)

---

## 📈 Top Languages

React.js

Next.js

TypeScript

TailwindCSS

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=amanq8175-alt&layout=compact&theme=tokyonight)

## 🤝 Connect With Me
<p align="left">
  <a href="https://www.linkedin.com/in/developer-aman-qureshi-8a62073ab/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="amanq8175@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.instagram.com/amanqureshi7263/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" /></a>
</p>
