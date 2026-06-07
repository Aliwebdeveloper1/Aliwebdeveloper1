@import url("https://fonts.googleapis.com/css2?family=Fira+Code:wght@400;500;600&family=Inter:wght@400;500;600;700&display=swap"); \* { box-sizing: border-box; margin: 0; padding: 0; } .gh { font-family: "Inter", sans-serif; background: #0d1117; color: #e6edf3; border-radius: 12px; overflow: hidden; border: 0.5px solid #30363d; max-width: 720px; margin: 0 auto; } /\* WAVE HEADER \*/ .wave-hdr { position: relative; height: 170px; background: linear-gradient(135deg, #1d9e75 0%, #0d9488 100%); overflow: hidden; } .wave-hdr-grid { position: absolute; inset: 0; background-image: linear-gradient(rgba(255, 255, 255, 0.04) 1px, transparent 1px), linear-gradient(90deg, rgba(255, 255, 255, 0.04) 1px, transparent 1px); background-size: 28px 28px; } .wave-hdr-cnt { position: absolute; inset: 0; display: flex; flex-direction: column; align-items: center; justify-content: center; gap: 6px; } .wave-hdr-name { font-size: 42px; font-weight: 700; color: #fff; letter-spacing: -0.5px; animation: fadeUp 0.7s ease both; } .wave-hdr-sub { font-size: 12.5px; color: rgba(255, 255, 255, 0.88); font-family: "Fira Code", monospace; animation: fadeUp 0.7s 0.15s ease both; } .wave-svg { position: absolute; bottom: 0; left: 0; width: 100%; } @keyframes fadeUp { from { opacity: 0; transform: translateY(12px); } to { opacity: 1; transform: none; } } /\* BODY \*/ .gh-body { padding: 1.4rem 1.6rem; } /\* meta row \*/ .meta-row { display: flex; justify-content: center; gap: 8px; margin-bottom: 0.8rem; } .meta-pill { font-size: 10.5px; font-family: "Fira Code", monospace; padding: 3px 10px; border-radius: 20px; background: #21262d; border: 0.5px solid #30363d; color: #8b949e; } .meta-pill b { color: #1d9e75; } /\* typing \*/ .typing-wrap { text-align: center; height: 30px; margin-bottom: 1rem; overflow: hidden; } .typing-text { font-size: 15px; font-weight: 600; font-family: "Fira Code", monospace; color: #1d9e75; } .cur { display: inline-block; width: 2px; height: 15px; background: #1d9e75; vertical-align: middle; margin-left: 2px; animation: blink 1s step-end infinite; } @keyframes blink { 0%, 100% { opacity: 1; } 50% { opacity: 0; } } /\* badges \*/ .bdg-row { display: flex; flex-wrap: wrap; justify-content: center; gap: 6px; margin-bottom: 1.2rem; } .bdg { display: inline-flex; align-items: center; gap: 5px; font-size: 11px; font-weight: 600; font-family: "Fira Code", monospace; padding: 6px 14px; border-radius: 4px; text-decoration: none; animation: popIn 0.4s ease both; letter-spacing: 0.02em; } @keyframes popIn { from { opacity: 0; transform: scale(0.88); } to { opacity: 1; transform: scale(1); } } .bdg-g { background: #1d9e75; color: #fff; } .bdg-b { background: #378add; color: #fff; } .bdg-p { background: #534ab7; color: #fff; } .bdg-a { background: #ba7517; color: #fff; } .divider { border: none; border-top: 0.5px solid #21262d; margin: 1.1rem 0; } /\* two-col layout \*/ .two-col { display: grid; grid-template-columns: 1fr 1fr; gap: 12px; margin-bottom: 1rem; } /\* terminal card \*/ .term-card { background: #161b22; border: 0.5px solid #30363d; border-radius: 8px; overflow: hidden; } .term-bar { background: #21262d; padding: 7px 12px; display: flex; align-items: center; gap: 6px; } .dot { width: 9px; height: 9px; border-radius: 50%; flex-shrink: 0; } .dot.r { background: #ff5f57; } .dot.y { background: #febc2e; } .dot.g { background: #28c840; } .term-lbl { font-size: 10.5px; color: #8b949e; font-family: "Fira Code", monospace; margin-left: 4px; } .term-body { padding: 12px 14px; font-family: "Fira Code", monospace; font-size: 11px; line-height: 1.9; } .jk { color: #79c0ff; } .js { color: #a5d6ff; } .jb { color: #e6edf3; } .jc { color: #8b949e; } .je { color: #ffa657; } .jl { opacity: 0; transform: translateX(-5px); transition: opacity 0.22s, transform 0.22s; } .jl.v { opacity: 1; transform: none; } /\* quick facts \*/ .facts-card { background: #161b22; border: 0.5px solid #30363d; border-radius: 8px; padding: 14px; } .fact-item { display: flex; align-items: flex-start; gap: 8px; margin-bottom: 10px; font-size: 12px; color: #c9d1d9; line-height: 1.5; } .fact-icon { font-size: 14px; flex-shrink: 0; margin-top: 1px; } .quote-box { background: #0d1117; border-left: 2px solid #1d9e75; border-radius: 0 4px 4px 0; padding: 8px 10px; font-size: 11px; font-style: italic; color: #8b949e; margin-top: 8px; line-height: 1.5; } /\* section heading \*/ .sec-hd { display: flex; align-items: center; gap: 8px; font-size: 13px; font-weight: 600; color: #e6edf3; margin-bottom: 0.9rem; } .sec-hd-line { flex: 1; height: 0.5px; background: #21262d; } /\* tech grid \*/ .tech-grid { display: grid; grid-template-columns: repeat(4, minmax(0, 1fr)); gap: 8px; margin-bottom: 1rem; } .tech-col { background: #161b22; border: 0.5px solid #30363d; border-radius: 6px; padding: 10px; } .tech-col-hd { font-size: 10px; font-weight: 600; color: #8b949e; letter-spacing: 0.06em; text-transform: uppercase; margin-bottom: 8px; font-family: "Fira Code", monospace; } .tbdg { display: inline-block; font-size: 10px; font-family: "Fira Code", monospace; padding: 2px 7px; border-radius: 4px; margin: 2px 2px 0 0; border: 0.5px solid #30363d; background: #21262d; color: #c9d1d9; } /\* skill bars \*/ .skill-table { width: 100%; margin-bottom: 1rem; } .skill-row-tr td { padding: 4px 0; } .skill-name-td { font-size: 11.5px; font-family: "Fira Code", monospace; color: #c9d1d9; width: 42%; white-space: nowrap; } .skill-track { height: 6px; background: #21262d; border-radius: 4px; overflow: hidden; width: 95%; } .skill-fill { height: 100%; border-radius: 4px; width: 0; transition: width 1.1s cubic-bezier(0.4, 0, 0.2, 1); } /\* stats section \*/ .stats-2col { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 10px; } .stats-img-mock { background: #161b22; border: 0.5px solid #30363d; border-radius: 8px; padding: 14px; font-size: 11px; font-family: "Fira Code", monospace; } .stats-hd { font-size: 10px; color: #8b949e; margin-bottom: 10px; text-transform: uppercase; letter-spacing: 0.06em; } .stats-row { display: flex; justify-content: space-between; align-items: center; margin-bottom: 7px; } .stats-lbl { color: #8b949e; font-size: 11px; } .stats-val { color: #1d9e75; font-weight: 600; font-size: 12px; } .streak-num { font-size: 28px; font-weight: 700; color: #1d9e75; text-align: center; margin: 8px 0 4px; } .streak-lbl { font-size: 10px; color: #8b949e; text-align: center; } /\* activity \*/ .activity-wrap { display: flex; gap: 3px; flex-wrap: wrap; margin-bottom: 0.5rem; } .week-col { display: flex; flex-direction: column; gap: 3px; } .day-sq { width: 10px; height: 10px; border-radius: 2px; border: 0.5px solid #30363d; transition: transform 0.1s; } .day-sq:hover { transform: scale(1.4); } .d0 { background: #161b22; } .d1 { background: #0e4429; border-color: #1d9e75; } .d2 { background: #1d9e75; border-color: #5dcaa5; } .d3 { background: #5dcaa5; border-color: #9fe1cb; } .d4 { background: #9fe1cb; } /\* trophy row \*/ .trophy-row { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-bottom: 1rem; } .trophy { background: #161b22; border: 0.5px solid #30363d; border-radius: 6px; padding: 8px 14px; text-align: center; min-width: 80px; } .trophy-ico { font-size: 16px; margin-bottom: 2px; } .trophy-val { font-size: 13px; font-weight: 700; color: #1d9e75; font-family: "Fira Code", monospace; } .trophy-lbl { font-size: 9.5px; color: #8b949e; } /\* timeline \*/ .timeline { margin-bottom: 1rem; } .tl-item { display: grid; grid-template-columns: 120px 1fr; gap: 10px; margin-bottom: 12px; align-items: start; } .tl-badge { font-size: 9.5px; font-weight: 600; font-family: "Fira Code", monospace; padding: 4px 8px; border-radius: 4px; text-align: center; line-height: 1.4; } .tl-g { background: #1d9e75; color: #fff; } .tl-t { background: #0d9488; color: #fff; } .tl-b { background: #378add; color: #fff; } .tl-content { font-size: 12px; color: #c9d1d9; line-height: 1.6; } .tl-content b { color: #e6edf3; } /\* what i bring \*/ .bring-grid { display: flex; flex-wrap: wrap; gap: 7px; justify-content: center; margin-bottom: 1rem; } .bring-bdg { font-size: 11px; font-weight: 600; font-family: "Fira Code", monospace; padding: 6px 12px; border-radius: 4px; } .br-g { background: #1d9e75; color: #fff; } .br-b { background: #378add; color: #fff; } .br-a { background: #ba7517; color: #fff; } .br-p { background: #534ab7; color: #fff; } .br-t { background: #0d9488; color: #fff; } .br-r { background: #e0234e; color: #fff; } /\* projects \*/ .proj-card { background: #161b22; border: 0.5px solid #30363d; border-radius: 8px; padding: 14px; margin-bottom: 10px; display: grid; grid-template-columns: 1fr 1fr; gap: 12px; align-items: center; } .proj-card.flip { direction: rtl; } .proj-card.flip > \* { direction: ltr; } .proj-title { font-size: 14px; font-weight: 600; color: #e6edf3; margin-bottom: 5px; } .proj-desc { font-size: 11.5px; color: #8b949e; line-height: 1.6; margin-bottom: 8px; } .proj-feat { font-size: 11px; color: #c9d1d9; line-height: 1.8; margin-bottom: 8px; } .proj-badges { display: flex; flex-wrap: wrap; gap: 5px; margin-bottom: 10px; justify-content: center; } .proj-btns { display: flex; gap: 7px; justify-content: center; } .pbtn { font-size: 11px; font-weight: 600; font-family: "Fira Code", monospace; padding: 5px 12px; border-radius: 4px; text-decoration: none; border: 0.5px solid #30363d; } .pbtn-g { background: #1d9e75; color: #fff; border-color: #1d9e75; } .pbtn-d { background: #21262d; color: #c9d1d9; } /\* diff block \*/ .diff-block { background: #161b22; border: 0.5px solid #30363d; border-radius: 8px; padding: 14px; font-family: "Fira Code", monospace; font-size: 12px; margin-bottom: 1rem; line-height: 2; } .diff-add { color: #3fb950; } /\* philosophy table \*/ .phil-table { width: 100%; border-collapse: collapse; font-size: 12px; margin-bottom: 1rem; } .phil-table th { background: #21262d; color: #8b949e; padding: 7px 10px; text-align: left; font-size: 10.5px; font-weight: 600; letter-spacing: 0.05em; text-transform: uppercase; } .phil-table td { padding: 7px 10px; border-bottom: 0.5px solid #21262d; color: #c9d1d9; } .phil-table td:first-child { color: #e6edf3; font-weight: 500; } /\* routine \*/ .routine-block { background: #161b22; border: 0.5px solid #30363d; border-radius: 8px; padding: 14px; font-family: "Fira Code", monospace; font-size: 12px; line-height: 2.2; margin-bottom: 1rem; color: #c9d1d9; } .r-time { color: #1d9e75; font-weight: 600; } .r-arr { color: #30363d; } /\* connect \*/ .connect-row { display: flex; flex-wrap: wrap; justify-content: center; gap: 8px; margin-bottom: 1rem; } .con-bdg { font-size: 11px; font-weight: 600; font-family: "Fira Code", monospace; padding: 6px 14px; border-radius: 4px; text-decoration: none; } .con-g { background: #1d9e75; color: #fff; } .con-d { background: #181717; color: #fff; border: 0.5px solid #30363d; } .con-li { background: #0a66c2; color: #fff; } /\* footer wave \*/ .footer-wave { height: 60px; background: linear-gradient(135deg, #1d9e75 0%, #0d9488 100%); position: relative; overflow: hidden; margin-top: 0.5rem; } .footer-wave svg { position: absolute; top: 0; left: 0; width: 100%; } .footer-txt { position: absolute; inset: 0; display: flex; align-items: center; justify-content: center; font-size: 11px; color: rgba(255, 255, 255, 0.75); font-family: "Fira Code", monospace; } /\* copy \*/ .copy-btn { display: block; width: 100%; padding: 10px; border-radius: 0; border: none; border-top: 0.5px solid #30363d; background: #161b22; color: #e6edf3; font-size: 13px; font-family: "Inter", sans-serif; cursor: pointer; text-align: center; } .copy-btn:hover { background: #21262d; }

Ali Raza

Full Stack Developer  |  MERN Stack Engineer  |  Remote-Ready

👁 PROFILE VIEWS **142** 👥 Followers **0**

⚡ Available for Hire 🌍 Remote Ready GitHub @Aliwebdeveloper1 📍 Pakistan

👨‍💻 About me

profile.json

{

  "name": "Ali Raza",

  "title": "Full Stack Developer",

  "location": "Pakistan 🇵🇰",

  "email": "aliraza41030@gmail.com",

  "stack": "MERN",

  "open\_to": \[

    "Remote Full-Time",

    "Freelance Projects",

    "Open Source"

  \],

  "fun\_fact": "console.log fan 😄"

}

⚡**3+ Years** of coding experience

💻**20+ Projects** completed

🔥**MERN Stack** specialist

🌍**Remote-first** mindset

🧹**Clean Code** advocate

📚**Fast learner** & team player

"Code is poetry. I write it clean, scalable, and with purpose."

⚙️ Tech arsenal

🎨 Frontend

![](https://cdn.simpleicons.org/react/61DAFB)React ![](https://cdn.simpleicons.org/nextdotjs/ffffff)Next.js ![](https://cdn.simpleicons.org/typescript/3178C6)TypeScript ![](https://cdn.simpleicons.org/javascript/F7DF1E)JavaScript ![](https://cdn.simpleicons.org/html5/E34F26)HTML5 ![](https://cdn.simpleicons.org/css3/1572B6)CSS3 ![](https://cdn.simpleicons.org/tailwindcss/06B6D4)Tailwind ![](https://cdn.simpleicons.org/bootstrap/7952B3)Bootstrap ![](https://cdn.simpleicons.org/redux/764ABC)Redux ![](https://cdn.simpleicons.org/sass/CC6699)Sass

⚙️ Backend

![](https://cdn.simpleicons.org/nodedotjs/339933)Node.js ![](https://cdn.simpleicons.org/express/ffffff)Express ![](https://cdn.simpleicons.org/nestjs/E0234E)NestJS ![](https://cdn.simpleicons.org/swagger/85EA2D)REST API ![](https://cdn.simpleicons.org/graphql/E10098)GraphQL ![](https://cdn.simpleicons.org/jsonwebtokens/ffffff)JWT ![](https://cdn.simpleicons.org/socketdotio/010101)Socket.io

🗄️ Database

![](https://cdn.simpleicons.org/mongodb/47A248)MongoDB ![](https://cdn.simpleicons.org/postgresql/336791)PostgreSQL ![](https://cdn.simpleicons.org/mongodb/880000)Mongoose ![](https://cdn.simpleicons.org/prisma/2D3748)Prisma ![](https://cdn.simpleicons.org/redis/DC382D)Redis ![](https://cdn.simpleicons.org/firebase/FFCA28)Firebase

🔧 DevOps

![](https://cdn.simpleicons.org/git/F05032)Git ![](https://cdn.simpleicons.org/github/181717)GitHub ![](https://cdn.simpleicons.org/docker/2496ED)Docker ![](https://cdn.simpleicons.org/amazonaws/FF9900)AWS ![](https://cdn.simpleicons.org/vercel/ffffff)Vercel ![](https://cdn.simpleicons.org/githubactions/2088FF)CI/CD ![](https://cdn.simpleicons.org/postman/FF6C37)Postman ![](https://cdn.simpleicons.org/visualstudiocode/007ACC)VS Code ![](https://cdn.simpleicons.org/linux/FCC624)Linux ![](https://cdn.simpleicons.org/npm/CB3837)npm

📊 Skill proficiency

📈 GitHub analytics

GitHub Stats

Total commits0

Pull requests0

Issues opened0

Repos0

Current Streak

0

days 🔥

Longest streak14 days

Total contributions280+

Contribution activity

🏗️ Experience & journey

2024 – PRESENT

**Full Stack Developer (MERN)**  
Building production-grade web apps with React, Next.js, Node.js, and MongoDB. Designing RESTful APIs, implementing auth systems, and deploying on AWS & Vercel.

2023 – 2024

**Frontend Developer — React & Next.js**  
Specialised in responsive, accessible UIs with Tailwind CSS and component-driven architecture. Integrated third-party APIs and payment gateways.

2022 – 2023

**Backend Developer — Node.js & Express**  
Developed scalable backend services, database schemas with MongoDB & PostgreSQL, and implemented JWT-based auth and role-based access control.

💡 What I bring

🏗️ Scalable Architecture 💡 Clean Code 🚀 Fast Delivery 🤝 Team Player 📖 Continuous Learner 💬 Great Communicator

🚀 Featured projects

🚀 Project 1 — Add Project Name

A brief description of what this project does and the problem it solves.

🔐 User authentication & authorization  
📱 Fully responsive design  
⚡ Real-time data updates  
🎨 Modern UI/UX with animations

ReactNode.jsMongoDBTailwind

[🔴 Live Demo](#)[💻 Source](#)

Next.jsNestJSPostgreSQLDocker

[🔴 Live Demo](#)[💻 Source](#)

🚀 Project 2 — Add Project Name

A brief description of what this project does and the problem it solves.

🏗️ Microservice architecture  
🔒 Role-based access control  
📊 Admin dashboard & analytics  
🐳 Dockerized deployment

🚀 Project 3 — Add Project Name

A brief description of what this project does and the problem it solves.

🔌 RESTful API design  
💳 Payment gateway integration  
📈 Performance optimized  
🌐 Multi-language support

ExpressREST APIMongoDBAWS

[🔴 Live Demo](#)[💻 Source](#)

🔨 Currently working on

\+ 🔨 Building scalable SaaS apps with Next.js 14 & Server Actions

\+ 📚 Deep diving into System Design & Microservices

\+ 🐳 Mastering Docker orchestration & CI/CD pipelines

\+ 🤝 Contributing to open source projects

📐 Coding philosophy

Principle

Belief

🏗️ Architecture

Build for scale from day one

🧹 Clean Code

Code is read 10× more than written

🔄 Iterate

Ship fast, learn, improve

🧪 Testing

If it's not tested, it's broken

📖 Documentation

Future you will thank present you

🤝 Collaboration

Great software is built by teams

☕ My daily routine

06:00 ━━▶ Wake up & plan the day

07:00 ━━▶ Deep work — coding & features

10:00 ━━▶ Coffee break & code review ☕

11:00 ━━▶ Team standup & collaboration

01:00 ━━▶ Bug fixing & testing 🐛

03:00 ━━▶ Learning & side projects 📚

05:00 ━━▶ Exercise & disconnect 🏃

09:00 ━━▶ Light reading & rest 🌙

🤝 Let's connect

[📧 aliraza41030@gmail.com](mailto:aliraza41030@gmail.com) [GitHub @Aliwebdeveloper1](https://github.com/Aliwebdeveloper1) [LinkedIn — Ali Raza](#)

💼 Open to freelance projects and remote full stack roles worldwide.  
📩 Drop me an email — I respond within 24 hours!

⭐ Ali Raza — Full Stack Developer  |  Made with ❤️ and ☕

Copy complete README.md + snake.yml instructions ↗

const roles = \[ "🚀 Full Stack Developer", "💻 MERN Stack Engineer", "⚛️ React & Next.js Specialist", "🔧 Node.js | NestJS Backend Dev", "🌍 Open to Remote Opportunities", "💡 Problem Solver | Clean Code Advocate", \]; let ri = 0, ci = 0, del = false; const te = document.getElementById("typed"); function tick() { const s = roles\[ri\]; if (!del) { ci++; te.textContent = s.slice(0, ci); if (ci === s.length) { del = true; setTimeout(tick, 1800); return; } } else { ci--; te.textContent = s.slice(0, ci); if (ci === 0) { del = false; ri = (ri + 1) % roles.length; setTimeout(tick, 350); return; } } setTimeout(tick, del ? 38 : 72); } setTimeout(tick, 500); for (let i = 0; i < 13; i++) setTimeout( () => { const e = document.getElementById("j" + i); if (e) e.classList.add("v"); }, 300 + i \* 90, ); const skills = \[ \["React / Next.js", 95, "#1D9E75"\], \["TypeScript / JavaScript", 92, "#F7DF1E"\], \["Node.js / Express", 90, "#339933"\], \["Tailwind CSS / UI", 88, "#06B6D4"\], \["MongoDB / PostgreSQL", 85, "#47A248"\], \["NestJS / REST APIs", 82, "#E0234E"\], \["Docker / AWS / DevOps", 70, "#2496ED"\], \["System Design", 65, "#8b949e"\], \]; const st = document.getElementById("skill-table"); skills.forEach((\[n, p, c\], i) => { const tr = document.createElement("tr"); tr.className = "skill-row-tr"; tr.innerHTML = \`<td class="skill-name-td">${n}</td><td style="width:58%;padding:4px 0"><div class="skill-track"><div class="skill-fill" id="sb${i}" style="background:${c}"></div></div></td><td style="width:6%;text-align:right;font-family:'Fira Code',monospace;font-size:10.5px;color:#8b949e;padding-left:6px">${p}%</td>\`; st.appendChild(tr); setTimeout( () => { const b = document.getElementById("sb" + i); if (b) b.style.width = p + "%"; }, 700 + i \* 100, ); }); function countUp(id, t, ms) { const e = document.getElementById(id); if (!e) return; const s = performance.now(); (function f(n) { const p = Math.min((n - s) / ms, 1); e.textContent = Math.round(p \* t); if (p < 1) requestAnimationFrame(f); })(performance.now()); } setTimeout(() => { countUp("sc1", 286, 1200); countUp("sc2", 42, 1000); countUp("sc3", 18, 900); countUp("sc4", 24, 800); countUp("streak-num", 7, 600); }, 600); const ag = document.getElementById("activity"); const lvls = \["d0", "d1", "d2", "d3", "d4"\]; for (let w = 0; w < 26; w++) { const wk = document.createElement("div"); wk.className = "week-col"; for (let d = 0; d < 7; d++) { const r = Math.random(); const l = r < 0.35 ? 0 : r < 0.55 ? 1 : r < 0.72 ? 2 : r < 0.88 ? 3 : 4; const sq = document.createElement("div"); sq.className = "day-sq " + lvls\[l\]; wk.appendChild(sq); } ag.appendChild(wk); } const trophies = \[ \["🏆", "0", "Commits"\], \["⭐", "24", "Stars"\], \["🔀", "0", "PRs"\], \["🐛", "0", "Issues"\], \["🔥", "7d", "Streak"\], \["📦", "24", "Repos"\], \["👥", "0", "Followers"\], \]; const tr = document.getElementById("trophies"); trophies.forEach((\[ic, v, l\]) => { const d = document.createElement("div"); d.className = "trophy"; d.innerHTML = \`<div class="trophy-ico">${ic}</div><div class="trophy-val">${v}</div><div class="trophy-lbl">${l}</div>\`; tr.appendChild(d); }); function copyAll() { navigator.clipboard .writeText( "The full README.md and snake.yml files are in the document you already have above — copy them from there and follow the 3-step instructions to upload to GitHub.", ) .then(() => { const b = document.querySelector(".copy-btn"); b.textContent = "✓ Your README.md & snake.yml are in the document above — follow the 3 steps!"; setTimeout(() => { b.textContent = "Copy complete README.md + snake.yml instructions ↗"; }, 4000); }); }
