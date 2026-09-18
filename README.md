<div align="center">

```
██████╗ ██████╗  █████╗ ███╗   ██╗███████╗██╗  ██╗██╗   ██╗
██╔══██╗██╔══██╗██╔══██╗████╗  ██║██╔════╝██║  ██║██║   ██║
██████╔╝██████╔╝███████║██╔██╗ ██║███████╗███████║██║   ██║
██╔═══╝ ██╔══██╗██╔══██║██║╚██╗██║╚════██║██╔══██║██║   ██║
██║     ██║  ██║██║  ██║██║ ╚████║███████║██║  ██║╚██████╔╝
╚═╝     ╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝
```

### Fullstack and agentic AI · KIIT CSE '28

I build AI tools that people actually use. Some of them died on GitHub. Those were the experiments.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white&style=flat-square)](https://www.linkedin.com/in/pranshukumar23/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white&style=flat-square)](https://pranshukumar-portfolio.vercel.app)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?logo=instagram&logoColor=white&style=flat-square)](https://www.instagram.com/pranshu23x/)

</div>

---

## Projects

### Tokenops
`in production` · `sole engineer` · Acttrident

A security gateway that sits inline between coding agents like Claude Code and the LLM providers behind them. It screens prompt injection, catches leaked credentials, and blocks exfiltration through the agent's own outbound tool calls, all at **130ms p50 on 4 vCPU with no GPU**.

The most useful thing it has taught me: a guard can pass its entire test suite and still be completely broken. Ours scored ordinary Hindi, Arabic, Bengali and Tamil text at 0.93 to 0.99, the same range as real attacks. It had been blocking every user writing in those languages while its metrics looked perfectly clean. Nothing in the suite would ever have caught it, because the suite was in English. Script-based routing took benign traffic served from 5/9 to 7/9 languages with all 9 attacks still caught.

Also in there: byte-exact SSE parsing for the Anthropic Messages API, 221 Gitleaks credential rules ported to TypeScript at 0.020ms p50, and a red-team harness built on a deliberately compromised MCP server.

---

### Mutter
`in development`

Speak in whatever language you actually think in, code-switching and all, and get back clean English in the register you need. Professional, casual, work. Say it in Hindi mid-sentence and it still comes out as something you can send.

The interesting part isn't the transcription, it's that translation and tone are usually two lossy steps stacked on each other. Your voice gets flattened twice. Mutter is an attempt to do it in one pass and keep what you actually meant.

Not shipped yet. Building it now.

---

### [Relay](https://try-relay.vercel.app/)
`shipped` · **100,000+ npm downloads**

A CLI (`npx getrelay@latest`) that pulls from 55+ production-grade design templates and writes a `relay.md` blueprint. Point an AI coding assistant at that file and it scaffolds the whole site at 60 to 70% visual and structural accuracy. Days of work, minutes of waiting.

[Live](https://try-relay.vercel.app/) · [npm](https://www.npmjs.com/package/getrelay)

---

### [Voyage](https://try-voyage.vercel.app/)
`shipped` · **1000+ users across IITs, NITs and KIIT** · $0.0001 per search

Multi-agent job search built on CrewAI. Agents parse your resume, rank roles semantically across LinkedIn, Indeed and Naukri, and generate tailored LaTeX resumes that open straight in Overleaf. Job hunting goes from hours to under five minutes.

[Live](https://try-voyage.vercel.app/)

---

### [AskTabs](https://chromewebstore.google.com/search/AskTabs)
`shipped` · Chrome Web Store · HackHarvard 2025 · Gemini Hackathon winner

Chrome extension that searches and answers questions across 200+ open tabs in real time. Runs entirely client-side, nothing stored on a server. Compressing tab content through Chrome's native Summarizer API before any LLM call brings it down to $0.008 per search across 50 tabs.

[Chrome Web Store](https://chromewebstore.google.com/search/AskTabs)

---

### [RippleCode](https://ripplecode.site)
`shipped` · **250+ developers**

Turns an entire GitHub repo into LLM-readable XML context so you can chat with any codebase instead of paging through it.

[Live](https://ripplecode.site)

---

### Reflex
`built at ContextCon (Crustdata × YC)`

Multi-agent swarm for high-stakes decisions. A ReACT debate loop runs over live market signals from the Crustdata API, with agents arguing positions before anything gets recommended.

---

## Selected for

```
HackHarvard 2025                 Global student hackathon
Y Combinator Startup School      India cohort, 2026
ContextCon (Crustdata × YC)      Invite-only, top 100 builders in India
Gemini Hackathon                 Winner
Brandfolio Hackathon             1st place
```

---

## Stack

**Languages** · TypeScript, JavaScript, Python, C++

**AI and agents** · LangChain, LangGraph, CrewAI, Anthropic and OpenAI APIs, MCP, FAISS

**Backend** · Node.js, Express, FastAPI, SSE streaming, PostgreSQL, MongoDB, Redis, Supabase

**Frontend** · React, Next.js, Tailwind

**Infra** · AWS, Docker

---

## Contribution graph

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Pranshu23x/Pranshu23x/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Pranshu23x/Pranshu23x/output/github-snake.svg" />
  <img alt="github-snake" src="https://raw.githubusercontent.com/Pranshu23x/Pranshu23x/output/github-snake.svg?v=2" />
</picture>

---

<div align="center">

**Let's build something worth talking about.**

</div>
