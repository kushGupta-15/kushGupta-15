## Hey, I'm Kush 👋

I like building full-stack apps end to end: the auth, the payments, the
real-time bits, the database schema, all of it. Currently doing my B.Tech
in CSE at IIIT Una. Outside of code, I've solved 750+ DSA problems across
LeetCode and GFG, and I play competitive chess (FIDE-rated, national and
international events).

---

### Things I've built

**[Career-wave](https://github.com/kushGupta-15/career-wave)**
An AI-powered job board and recruiter ATS platform connecting hiring companies with job seekers. I skipped a separate REST API layer and built it end-to-end on Next.js 15 Server Actions and React Server Components. Data lives in Neon PostgreSQL via Prisma, with Google/GitHub login via NextAuth splitting users into recruiter vs. candidate workflows. Integrated Google Gemini 3.8 Flash to run real-time ATS resume compatibility analysis and live career search assistance. Employers publish tiered listings through Stripe Checkout (webhooks handle async activation), and Inngest serverless event workers quietly expire postings on schedule so I didn't need a cron job. Built a recruiter pipeline dashboard with in-browser PDF resume previews and candidate application withdrawal, backed by UploadThing file uploads, Resend transactional emails, Zod validation, and Arcjet edge bot shielding.
`Next.js 15` `TypeScript` `PostgreSQL` `Prisma` `Google Gemini` `Stripe` `Inngest` `Arcjet`

**[SketchBattle](https://github.com/kushGupta-15/sketchbattle)**
A Skribbl.io-style real-time drawing and guessing game, engineered for multiplayer fun and chaos. Features an interactive HTML5 Canvas with custom 4-way BFS flood fill, stroke undo history, and mid-round canvas sync so reconnecting players never lose their place or scores. The game engine powers custom room settings, difficulty tiers, speed-tiered rank scoring, Levenshtein distance near-miss typo alerts, and progressive letter hint reveals. Includes a zero-dependency Web Audio API sound synthesizer, peer-to-peer WebRTC video calling, a mobile-first responsive design with direct on-screen chat guessing, and full security hardening with bcrypt password hashing, sliding-window rate limiting, and 24-hour MongoDB TTL cleanup. Fully verified with a 15-test automated suite and automated GitHub Actions CI.
`React` `TypeScript` `Node.js` `Express` `Socket.IO` `WebRTC` `MongoDB` `Tailwind CSS` `GitHub Actions`

**[Streamify](https://github.com/kushGupta-15/Streamify)**
A full-stack language-exchange platform that connects learners through smart reciprocal compatibility matching (100% Perfect Exchange, Native Speaker, and Study Partner tiers). Features an integrated Google Gemini 3.8 Flash AI assistant in chat for instant translations with phonetics, grammar error checking, and contextual icebreakers. Backed by JWT httpOnly cookie authentication, rate limiting, and MongoDB compound indexes for high-throughput social queries. Real-time messaging and WebRTC video calling run on Stream Chat and Video SDKs with call-room authorization checks, Cloudinary media processing, and 32 dynamic DaisyUI themes.
`React 19` `Node.js` `Express` `MongoDB` `Google Gemini AI` `Stream Chat` `Stream Video` `Cloudinary` `Tailwind CSS` `DaisyUI` `Vitest`

---

### What I work with

**Languages:** JavaScript, TypeScript, Python, C++
**Frontend:** React, Next.js, Tailwind CSS, Redux, Zustand
**Backend:** Node.js, Express, REST APIs, Socket.IO, JWT
**Databases:** PostgreSQL, MongoDB, SQL, Firebase
**Tools:** Git, Docker, AWS, Stripe, Inngest, Clerk, Cloudinary

---

### Right now

Grinding through SWE interview prep, mostly system design and going back
over core DSA patterns instead of just chasing problem count.

---

[LinkedIn](https://linkedin.com/in/kush-gupta) | [Email](mailto:kushg1517@gmail.com) | [GitHub](https://github.com/kushGupta-15) | [Portfolio](https://kushgupta-15.github.io/)
