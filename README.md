### Hi, I'm Sören 👋

I bring AI to where the work happens. By day I'm a Key Account Manager in the commercial team of a B2B SaaS company and the person colleagues come to for AI: I take processes apart, build agents for the parts worth automating, and teach the team to build their own. On the side I co-founded **PEPE SPLITS**, a royalty-accounting SaaS for the music industry, where I'm managing director and product lead. Tickets, test plans, content and most of the day-to-day run through agents I built myself.

I'm not an engineer. Everything below was built by someone who knows the business, in close sparring with AI and with engineering where it mattered.

**How I work**
- **Enable, don't gatekeep.** Two internal AI workshops later, my commercial team builds its own agents and subagents. The goal is fewer requests landing on my desk, not more.
- **Safe by default.** Agents draft, humans send. No customer data leaves the company, untrusted input is treated as data and never as instructions, and anything important needs an approval.
- **Scripts before models.** If a routine can run as a plain script, it does. One model call where judgement is needed, code for the rest.
- **Prove it, then hand it over.** Prototype fast with AI, show it's worth real engineering, then build it to last together.

---

#### 🧠 [shared-brain](https://github.com/soeren90/shared-brain): one brain, many bodies
A plain-Markdown store of memory, skills and agent definitions that all my agents read from, kept in sync across machines and designed around the security risks of agents that read untrusted content all day. The hub of everything else here.

#### 🤖 [hermes-agent](https://github.com/soeren90/hermes-agent): an always-on agent I built and ran on my own server
Ran product management around the clock: turned a chat message, a voice note or a screenshot into a well-formed ticket, kept the backlog honest, and handled routines like a morning briefing, mail triage and deadline checks. Sandboxed, watched and restarted automatically. Narrow on purpose: it drafts, I decide. In autumn 2026 I moved this work to Claude Code running locally, because an always-online server holding credentials is a bigger attack surface than an agent that runs under my control.

#### 🎩 [larry](https://github.com/soeren90/larry): how I design multi-agent systems
A conductor agent delegating to narrow specialists, backed by a Markdown memory vault, scheduled automations and a human-gated learning loop.

#### 🎵 [song-finance](https://github.com/soeren90/song-finance): a prototype that reached production
An AI-built Python model for valuing songs and catalogues. I built it to prove the idea; an engineering team then rebuilt it for production.

---

*Sanitized showcases: the architecture and the operating model, without customer or internal detail. Shared for reference, not reuse.*
