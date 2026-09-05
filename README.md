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
A Skribbl.io-style drawing and guessing game, built for real-time chaos.
Socket.IO keeps everyone's canvas in sync on an HTML5 Canvas layer, and
the game logic handles timed rounds, rank-weighted scoring, and gradual
word-hint reveals. Rooms can be password-protected, and if someone's
connection drops mid-round, they can rejoin without losing their place.
There's also peer-to-peer video chat running alongside the game socket,
with JWT securing both the REST endpoints and the Socket.IO handshake.
`React` `TypeScript` `Node.js` `Express` `Socket.IO` `MongoDB`

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