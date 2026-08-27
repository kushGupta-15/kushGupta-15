## Kush Gupta

I build full-stack web applications — auth flows, payment systems, real-time
sync, relational schema design.

B.Tech CSE @ IIIT Una · 750+ DSA problems solved (LeetCode, GFG) ·
FIDE-rated chess player (national & international tournaments)

---

### Projects

**[Career-wave](https://github.com/kushGupta-15/career-wave)**
Full-stack job portal — posting, search, saving, and applications, built on
Next.js Server Actions instead of a separate API layer. Relational schema
in PostgreSQL via Prisma, with role-based workflows for companies vs. job
seekers gated through NextAuth (Google/GitHub OAuth). Paid job postings run
through Stripe with webhook-driven activation; Inngest handles scheduled
expiration so listings drop automatically without a cron job. Upload
pipeline via UploadThing, transactional email via Resend, input validation
with Zod, and Arcjet for bot/abuse protection at the edge.
`Next.js` `TypeScript` `Prisma` `PostgreSQL` `NextAuth` `Stripe` `Inngest`

**[SketchBattle](https://github.com/kushGupta-15/sketchbattle)**
Real-time multiplayer drawing-and-guessing game, Skribbl.io-style. Socket.IO
keeps canvas state synchronized across all connected clients on an
interactive HTML5 Canvas layer. Game logic covers timed rounds,
rank-weighted scoring, progressive word-hint reveal, and password-protected
rooms, plus reconnection handling so a dropped client can rejoin mid-round
without losing state. Peer-to-peer video chat runs alongside the game
socket, with JWT auth enforced across both REST endpoints and the
Socket.IO handshake.
`React` `TypeScript` `Node.js` `Express` `Socket.IO` `MongoDB`

**[Streamify](https://github.com/kushGupta-15/streamify)**
Language-exchange platform connecting users for live practice. JWT-secured
REST APIs handle onboarding, profile updates, and session state; a
friend-request system tracks pending/accepted states through MongoDB
relational queries. Stream Chat and Stream Video SDKs are integrated for
real-time messaging and live video sessions, on a Tailwind + DaisyUI
frontend with theme support.
`React` `JavaScript` `Stream Chat` `Stream Video` `Node.js` `MongoDB`

---

### Stack

**Languages:** JavaScript · TypeScript · Python · C++
**Frontend:** React · Next.js · Tailwind CSS · Redux · Zustand
**Backend:** Node.js · Express · REST APIs · Socket.IO · JWT
**Databases:** PostgreSQL · MongoDB · SQL · Firebase
**Tools:** Git · Docker · AWS · Stripe · Inngest · Clerk

---

### Currently

Preparing for SWE interviews — deepening system design and revisiting core
DSA patterns beyond raw problem count.

---

[LinkedIn](https://linkedin.com/in/kush-gupta) ·
[Email](mailto:kushg1517@gmail.com) ·
[GitHub](https://github.com/kushGupta-15)