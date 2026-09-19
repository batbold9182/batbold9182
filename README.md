<h1 align="center">Batbold Samdan</h1>

<p align="center">
  <strong>Fullstack Developer</strong> · Bachelor's student · Warsaw, Poland
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

4th-year Bachelor's student in Warsaw. I've independently designed, built and shipped four production-style fullstack applications — REST API design, real-time features, role-based auth — using Node.js, Express, React, React Native and MongoDB.

Applied security is where the extra hours go. In my own music-review app I found and closed an **unauthenticated account-takeover chain**: a public endpoint was returning password hashes *and* live password-reset tokens. I moved reset tokens to SHA-256 at rest and added proof-of-possession to session refresh.

🎯 **Currently looking for a junior or internship role in Warsaw.**


<div align="center">
  <img src="./assets/animation.gif" width="50%">
</div>
---

## Tech Stack

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![FAST-API](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
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
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Database & Tools**

![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Mongoose](https://img.shields.io/badge/Mongoose-880000?style=flat-square&logo=mongoose&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

**Currently learning**

![FAST-API](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Fullstack Open](https://img.shields.io/badge/Fullstack%20Open-000000?style=flat-square)

---

## Selected Projects

### 🎓 [Smart Campus System](https://github.com/batbold9182/Smart_Campus_Batbold) · `2024 – ongoing`

Cross-platform university management platform with admin, faculty and student dashboards.

`React Native (Expo)` `Node.js` `Express` `MongoDB` `Socket.io` `Zustand` `TanStack Query` `Cloudinary` `Sentry`

- Role-based access control with JWT auth, Nodemailer OTP password reset, and platform-aware token storage (SecureStore on native, AsyncStorage on web)
- Real-time chat over 3 Socket.io namespaces — live presence, cursor-paginated history, XSS sanitisation on inbound messages, per-user (5) / per-IP (20) connection caps
- Layered rate limiting keyed per surface — per-user on data routes, per-IP on auth, per-email on OTP — with explicit proxy-hop config so clients cannot forge `X-Forwarded-For` to evade the limits
- Cascade cleanup (deleting a course removes its assignments, submissions, grades and remote Cloudinary files), plus Sentry error tracking, Swagger/OpenAPI docs and fail-fast startup validation

### 🎵 [express — Music Review Social App](https://github.com/batbold9182/express) · `2025 – ongoing`

Rate music, build your taste. Reviews of tracks, albums and artists with a social feed.

[**Live demo**](https://express-bybatbold.vercel.app)

`React` `TypeScript` `Express 5` `MongoDB` `React Native` `Tailwind CSS` `bcrypt`

- TypeScript monorepo (npm workspaces) where one shared package feeds types, theming, validators and routing helpers to an Express 5 + MongoDB backend, a React + Vite web app, and a React Native (Expo) mobile app
- Spotify OAuth 2.0 for web and native, separating the app session token from the third-party credential so expired Spotify tokens refresh server-side instead of half-breaking the user's session
- Full review system over tracks/albums/artists with server-side filtered search, likes, threaded comments, follows, and notifications aggregated by upsert so N likes collapse into a single document
- 🔒 Found and closed an unauthenticated account-takeover chain (a public endpoint returning password hashes and live reset tokens), moved reset tokens to SHA-256 at rest, and added proof-of-possession to session refresh

### 💅 [Warsaw Beauty Salons](https://github.com/batbold9182/sumup) · `2026`

Salon discovery app over 257 real Warsaw salons. Built as the SumUp Accelerator take-home.

[**Live demo**](https://sumup-gray.vercel.app) · [API](https://sumup-4oxv.onrender.com)

`Express.js` `React` `TypeScript` `MongoDB` `Vercel` `Render`

- Populated the database via a Node.js script on Google Places API v1, bypassing the 60-result cap with 5 targeted queries and Set-based deduplication
- Cut Google Places API cost using the `X-Goog-FieldMask` header to request only the needed fields
- Prevented ReDoS attacks with a custom `escapeRegex()` sanitizer on all user search input before MongoDB queries
- Debounced client-side requests, filtering by district / rating / price level, and dark mode via `prefers-color-scheme`

### 📚 [The Library — Open Library App](https://github.com/batbold9182/task) · `2025`

Book discovery over the Open Library API, no framework.

[**Live demo**](https://simplebookcatalogue.vercel.app)

`Vanilla JS` `Open Library API` `CSS3` `localStorage`

- Book search by title/author using `URLSearchParams` with a normalized API response shape
- localStorage favorites with crash-safe try/catch JSON parsing and deduplication
- Custom XSS protection via `escapeHtml()` using DOM text nodes

---

## Also here

- [**Portfolio**](https://github.com/batbold9182/portfolio) — my personal site → [portfolio-batbold.vercel.app](https://portfolio-batbold.vercel.app)

---

## Education & Languages

**Vizja University Warsaw** — Bachelor's Degree, 4th year · `2021 – Present`

🇲🇳 Mongolian (native) · 🇬🇧 English (professional) · 🇵🇱 Polish (beginner)

---

<p align="center">
  <a href="mailto:batbold918273645@gmail.com">batbold918273645@gmail.com</a> · <a href="https://portfolio-batbold.vercel.app">portfolio-batbold.vercel.app</a>
</p>

<p align="center">
  <a href="mailto:batbold918273645@gmail.com">Leetcode Link</a> · <a href="https://leetcode.com/u/Stupidassni/"></a>
</p>
