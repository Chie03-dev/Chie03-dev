<p align="center">
  <img src="banner.svg" alt="Alchie, Android and Front-end Developer" width="100%" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Chie03-dev&label=Profile%20Views&color=36BCF7&style=flat" alt="profile views" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=flat" alt="open to work" />
  <img src="https://img.shields.io/badge/BSCS-Andres%20Bonifacio%20College%20'26-7F52FF?style=flat" alt="education" />
</p>

---

### About

BS Computer Science graduate (Andres Bonifacio College, 2026). I build practical software: offline-first mobile apps, LAN-based classroom tools, polished front-end showcases, and barangay information systems for a startup in the Philippines.

I'm also into computer hardware. I build and troubleshoot PCs on the side, so if the code breaks, there's a decent chance I can fix the machine running it too.

**Currently looking for my first full-time role in Android or front-end development.**

---

### Tech stack

<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=kotlin,java,ts,js,html,css,py,react,nextjs,tailwind,electron,nodejs,androidstudio,sqlite,cloudflare,git,linux,windows&perline=9" alt="Tech stack" />
  </a>
</p>

---

### Projects

#### BizPalm Mobile

[Repository](https://github.com/Chie03-dev/BizPalm-Mobile) | v1.0.0

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Room-SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/github/stars/Chie03-dev/BizPalm-Mobile?style=flat-square&color=36BCF7" />
</p>

An **offline-first POS and inventory app** for small retail stores, sari-sari stores and pharmacies. It runs without an internet connection, so a store keeps working when the signal doesn't.

- **Stack:** Kotlin, Java, Room, MVVM, CameraX, ML Kit, MPAndroidChart, iText
- **Highlights:** works fully offline, inventory and sales tracking, charts and PDF reports
- **My role:** front-end UI, database connections, and CRUD functionality
- **Screenshots:** see the [app gallery in the repo](https://github.com/Chie03-dev/BizPalm-Mobile#readme)

---

#### Barangay Resident Portal

[Live demo](https://barangay.myappmcb.workers.dev)

<p>
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" />
</p>

A resident-facing portal for barangay services: document requests, incident reporting, request tracking and an officials directory. Built as a **front-end showcase** (all data is mocked) with a glassmorphic design system, Framer Motion transitions and a mobile layout with a floating nav dock.

- **Stack:** Next.js 15, React 19, TypeScript (strict), Tailwind CSS v4, Framer Motion, deployed to Cloudflare Workers through OpenNext
- **Highlights:** cinematic login with a 3D tilt card, bento dashboard with an SVG barangay map and community calendar, four-step document request flow, request timeline with a pick-up pass, three-tier officials org chart
- **Details:** dark mode by default with no theme flash, full `prefers-reduced-motion` support, and no web fonts downloaded (served assets total about 55 KB)
- **Try it:** sign in with any email and password

---

#### Quiz LAN System

A classroom quiz system that runs entirely on the local network. No cloud, no CDNs, no internet needed. It is split into two apps that talk over WebSocket.

**Quiz Instructor (desktop)** | [Repository](https://github.com/Chie03-dev/Quiz)

<p>
  <img src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white" />
</p>

A Windows Electron app that starts a WebSocket server on the classroom network, shows a 4-digit session PIN and a QR code, and lists the students who join.

- Kick students, restart sessions, and restore a student's identity with a device token if their phone reconnects
- Heartbeat tracking marks a student as disconnected after 10 seconds of silence
- One-click Windows firewall setup that verifies the rules by reading the firewall back, instead of trusting an exit code
- Discovery over mDNS, with the QR code carrying the raw address so joining never depends on it
- Protocol checks that run against a real server, plus UI checks that click the real window

**Quiz Student App (Android)**

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white" />
  <img src="https://img.shields.io/badge/Material_3-757575?style=flat-square&logo=materialdesign&logoColor=white" />
  <img src="https://img.shields.io/badge/Android_8.0+-3DDC84?style=flat-square&logo=android&logoColor=white" />
</p>

An offline, LAN-only Android client for the instructor app, built with Kotlin and Jetpack Compose.

- Connects over an OkHttp WebSocket, with service discovery through NsdManager (mDNS) or QR code scanning (CameraX and ML Kit)
- Supports eight question types: MCQ, True/False, Identification, Fill-in, Enumeration, Problem, Matching and Connect
- All interactive UI stays inside the composition, so the app never loses window focus or triggers a pause
- Robust state restoration and queue management

---

#### Also built

- **Barangay information systems** for a startup in the Philippines
- **Inventory and school management tools** that went beyond class assignments

---

### GitHub stats

<table align="center">
  <tr>
    <td><img src="https://github-readme-stats.vercel.app/api?username=Chie03-dev&show_icons=true&theme=tokyonight&hide_border=true&hide_rank=true" alt="GitHub Stats" /></td>
    <td><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Chie03-dev&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" /></td>
  </tr>
</table>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Chie03-dev&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <a href="https://octoprofile.vercel.app/?username=Chie03-dev">
    <img src="https://img.shields.io/badge/View%20my%20Octoprofile-36BCF7?style=for-the-badge&logo=github&logoColor=white" alt="Octoprofile" />
  </a>
</p>

---

### Get in touch

<p align="left">
  <a href="mailto:alchieandilab2003@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="http://www.linkedin.com/in/alchieandilab">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
