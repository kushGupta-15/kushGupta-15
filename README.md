## Hey, I'm Kush 👋

I like building full-stack apps end to end: the auth, the payments, the
real-time bits, the database schema, all of it. Currently doing my B.Tech
in CSE at IIIT Una. Outside of code, I've solved 750+ DSA problems across
LeetCode and GFG, and I play competitive chess (FIDE-rated, national and
international events).

---

### Things I've built

**[Career-wave](https://github.com/kushGupta-15/career-wave)**
A job portal for companies and job seekers. Posting, searching, saving,
applying, the works. I skipped a separate API layer and built it entirely
on Next.js Server Actions. Data lives in PostgreSQL through Prisma, with
Google/GitHub login via NextAuth splitting users into company vs. seeker
flows. Paid postings go through Stripe (webhooks handle activation), and
Inngest quietly expires listings on schedule so I didn't need to run a
cron job for it. File uploads go through UploadThing, emails through
Resend, Zod handles input validation, and Arcjet blocks bots at the edge.
`Next.js` `TypeScript` `Prisma` `PostgreSQL` `NextAuth` `Stripe` `Inngest`

**[SketchBattle](https://github.com/kushGupta-15/sketchbattle)**
A Skribbl.io-style real-time drawing and guessing game, engineered for multiplayer fun and chaos. Features an interactive HTML5 Canvas with custom 4-way BFS flood fill, stroke undo history, and mid-round canvas sync so reconnecting players never lose their place or scores. The game engine powers custom room settings, difficulty tiers, speed-tiered rank scoring, Levenshtein distance near-miss typo alerts, and progressive letter hint reveals. Includes a zero-dependency Web Audio API sound synthesizer, peer-to-peer WebRTC video calling, a mobile-first responsive design with direct on-screen chat guessing, and full security hardening with bcrypt password hashing, sliding-window rate limiting, and 24-hour MongoDB TTL cleanup. Fully verified with a 15-test automated suite and automated GitHub Actions CI.
`React` `TypeScript` `Node.js` `Express` `Socket.IO` `WebRTC` `MongoDB` `Tailwind CSS` `GitHub Actions`

**[Streamify](https://github.com/kushGupta-15/streamify)**
A language-exchange platform for people to find practice partners and talk
live. JWT-secured REST APIs handle onboarding, profiles, and session
state, and there's a friend-request system that tracks pending/accepted
connections in MongoDB. Real-time messaging and video sessions run on the
Stream Chat and Stream Video SDKs, wrapped in a Tailwind + DaisyUI
frontend with theme switching.
`React` `JavaScript` `Stream Chat` `Stream Video` `Node.js` `MongoDB`

---

### What I work with

**Languages:** JavaScript, TypeScript, Python, C++
**Frontend:** React, Next.js, Tailwind CSS, Redux, Zustand
**Backend:** Node.js, Express, REST APIs, Socket.IO, JWT
**Databases:** PostgreSQL, MongoDB, SQL, Firebase
**Tools:** Git, Docker, AWS, Stripe, Inngest, Clerk

---

### Right now

Grinding through SWE interview prep, mostly system design and going back
over core DSA patterns instead of just chasing problem count.

---

[LinkedIn](https://linkedin.com/in/kush-gupta) | [Email](mailto:kushg1517@gmail.com) | [GitHub](https://github.com/kushGupta-15)
