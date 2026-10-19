<h1 align="center">Batbold Samdan</h1>

<p align="center">
  <strong>Fullstack Developer</strong> · Computer Science Graduate · Warsaw, Poland
</p>

<p align="center">
  I build fullstack apps with Node.js, Express, React and MongoDB — then try to break them before someone else does.
</p>

<p align="center">
  <a href="https://portfolio-batbold.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="mailto:batbold918273645@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## About

Computer Science graduate (Vizja University Warsaw, 2026). I've independently designed and built four fullstack applications — REST API design, real-time features, role-based auth — using Node.js, Express, React, React Native and MongoDB.

Applied security is where the extra hours go. In my own music-review app I found and closed an **unauthenticated account-takeover chain**: a public endpoint was returning password hashes *and* live password-reset tokens. I moved reset tokens to SHA-256 at rest and added proof-of-possession to session refresh. A 250+ case Jest suite then caught NoSQL operator injection in login, password reset and comments.

🎯 **Currently looking for a junior or internship fullstack role in Warsaw.**

<div align="center">
  <img src="./assets/animation.gif" width="50%">
</div>

---

## Tech Stack

**Languages**

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-intermediate-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat-square&logo=fastapi&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![OAuth 2.0](https://img.shields.io/badge/OAuth%202.0-2F2F2F?style=flat-square)
![Nodemailer](https://img.shields.io/badge/Nodemailer-29B473?style=flat-square)
![Helmet.js](https://img.shields.io/badge/Helmet.js-000000?style=flat-square)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Data & Tools**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**Testing**

![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

**Currently learning**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Fullstack Open](https://img.shields.io/badge/Fullstack%20Open-000000?style=flat-square)

---

## Selected Projects

### 🎵 [Express — Music Review Social App](https://github.com/batbold9182/express) · `2025 – ongoing`

Rate music, build your taste. Reviews of tracks, albums and artists with a social feed.

[**Live demo**](https://express-bybatbold.vercel.app)

`TypeScript` `Express 5` `MongoDB` `React` `React Native (Expo)` `TanStack Query` `Tailwind CSS` `Jest`

- TypeScript monorepo (npm workspaces) where one shared package feeds types, theming, validators and routing helpers to an Express 5 + MongoDB backend, a React + Vite web app, and a React Native (Expo) mobile app
- Spotify OAuth 2.0 for web and native, separating the app session token from the third-party credential so expired Spotify tokens refresh server-side instead of half-breaking the user's session
- Full review system over tracks/albums/artists with server-side filtered search, likes, threaded comments, follows, and notifications aggregated by upsert so N likes collapse into a single document
- 🔒 Found and closed an unauthenticated account-takeover chain (a public endpoint returning password hashes and live reset tokens), moved reset tokens to SHA-256 at rest, and added proof-of-possession to session refresh
- 🧪 250+ case Jest suite (unit, integration and security; Supertest + in-memory MongoDB) that exposed NoSQL operator injection in login, password reset and comments — fixed with strict input type checks

### 🎓 [Smart Campus System](https://github.com/batbold9182/Smart_Campus_Batbold) · `2024 – 2026`

Cross-platform university management platform (iOS, Android, web) with admin, faculty and student dashboards.

`React Native (Expo)` `Node.js` `Express` `MongoDB` `Socket.io` `Zustand` `TanStack Query` `Cloudinary` `Sentry`

- Role-based access control with JWT auth, Nodemailer OTP password reset, and platform-aware token storage (SecureStore on native, AsyncStorage on web)
- Real-time chat over 3 Socket.io namespaces — live presence, cursor-paginated history, XSS sanitisation on inbound messages, per-user (5) / per-IP (20) connection caps
- Layered rate limiting keyed per surface — per-user on data routes, per-IP on auth, per-email on OTP — with explicit proxy-hop config so clients cannot forge `X-Forwarded-For` to evade the limits
- Cascade cleanup (deleting a course removes its assignments, submissions, grades and remote Cloudinary files), plus Sentry error tracking, Swagger/OpenAPI docs and fail-fast startup validation

### 💅 [Beauty Salon Finder](https://github.com/batbold9182/sumup) · `2026`

Salon discovery app over 257 real Warsaw salons. Built as the SumUp Accelerator take-home.

[**Live demo**](https://sumup-gray.vercel.app) · [API](https://sumup-4oxv.onrender.com)

`TypeScript` `Express.js` `React` `MongoDB` `Google Places API` `Vercel` `Render`

- Populated the database via a Node.js script on Google Places API v1, bypassing the 60-result cap with 5 targeted queries and Set-based deduplication
- Cut Google Places API cost using the `X-Goog-FieldMask` header to request only the needed fields
- Prevented ReDoS attacks with a custom `escapeRegex()` sanitizer on all user search input before MongoDB queries
- Debounced search, filtering by district / rating / price level, pagination, full CRUD, and dark mode via `prefers-color-scheme`

### 🎮 [Python Game Hub](https://github.com/batbold9182/python_games) · `2026 – ongoing`

Sign in, play small games, earn points. Built while learning Python.

`Python` `FastAPI` `SQL Server` `Pytest` `React` `TypeScript`

- JWT auth with bcrypt-hashed passwords, short-lived access tokens, and refresh tokens stored only as SHA-256 hashes (a database leak alone isn't a usable login), revoked on logout — covered by Pytest security tests
- Append-only points ledger schema in SQL Server; number-guessing game playable end to end, with chess and poker planned

### 📚 [The Library — Open Library App](https://github.com/batbold9182/task) · `2025`

Book discovery over the Open Library API, no framework.

[**Live demo**](https://simplebookcatalogue.vercel.app)

`Vanilla JS` `Open Library API` `CSS3` `localStorage`

- Book search by title/author using `URLSearchParams` with a normalized API response shape
- localStorage favorites with crash-safe try/catch JSON parsing and deduplication
- Custom XSS protection via `escapeHtml()` using DOM text nodes

---

## Also here

- [**BabyBata**](https://github.com/batbold9182/babybata) — AI assistant for my portfolio: Qwen2.5-0.5B fine-tuned with LoRA, grounded on a fact sheet so facts change without retraining → [🤗 Hugging Face](https://huggingface.co/BatboldSamdan/babybata2)
- [**Portfolio**](https://github.com/batbold9182/portfolio) — my personal site → [portfolio-batbold.vercel.app](https://portfolio-batbold.vercel.app)

---

## Education & Languages

**Vizja University Warsaw** — Bachelor's Degree in Computer Science · Graduated · `2021 – 2026`

🇲🇳 Mongolian (native) · 🇬🇧 English (professional) · 🇵🇱 Polish (beginner)

---

<p align="center">
  <a href="mailto:batbold918273645@gmail.com">batbold918273645@gmail.com</a> · <a href="https://portfolio-batbold.vercel.app">portfolio-batbold.vercel.app</a> · <a href="https://leetcode.com/u/Stupidassni/">LeetCode</a>
</p>
