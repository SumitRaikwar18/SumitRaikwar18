<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Sumit%20Raikwar&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=AI%20Builder%20%C2%B7%20Full-Stack%20Engineer&descAlignY=55&descSize=18" />

</div>

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=900&color=A78BFA&center=true&vCenter=true&width=760&lines=Building+AI+products+that+ship;Human-in-the-loop+%C2%B7+Agents+%C2%B7+Reliable+Workflows;TypeScript+%C2%B7+Next.js+%C2%B7+Supabase+%C2%B7+OpenRouter;From+idea+%E2%86%92+architecture+%E2%86%92+working+product" alt="Typing SVG" />

</div>

<br/>

<div align="center">

[![X](https://img.shields.io/badge/X%20%2F%20Twitter-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/sumit_raikwar18)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumitraikwar/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SumitRaikwar18)

</div>

---

## 👋 About Me

```yaml
name        : Sumit Raikwar
role        : AI Builder · Full-Stack Engineer
location    : India 🇮🇳

core        : TypeScript · Next.js · React · Supabase
ai          : AI Workflows · Human-in-the-loop · Tool Use · MCP
backend     : APIs · PostgreSQL · Structured Data · Reliable Workflows
secondary   : Stellar · Soroban · Rust · x402

building    : AI products and agent-driven software
status      : 🟢 Open to opportunities, collaborations & hackathons
```

I build AI products where the model is part of a **real software system** — with state, evidence, human review, failure handling, tools, and clear trust boundaries.

Right now, I'm especially interested in:

- 🤖 AI product engineering
- 🧠 Human-in-the-loop systems
- 🛠 Tool-using agents & MCP
- 🔎 Traceable AI workflows
- 🧪 Testing, reliability & failure recovery
- 🌐 Full-stack product development
- 💸 Programmable payments for agents

> **Build useful systems. Keep uncertainty visible. Ship the product.**

---

# 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🌊 Limnora

**Freshwater Evidence & Human Review Platform**

Built for the **OneAquaHealth IEEE Global Hackathon 2026**.

Limnora turns uncertain freshwater citizen observations into traceable evidence.

The image is screened independently without giving the model the observer's category first.

When the two interpretations disagree, Limnora doesn't silently choose a winner.

Instead, it keeps the disagreement visible and asks:

> **What evidence should we collect next?**

**Highlights**

- 📷 Independent image-first screening
- 👀 Observer vs model comparison
- 🧑‍🔬 Additive human review
- 🔁 Focused revisit questions
- 🗂 Reviewer Workbench
- 📄 Researcher evidence handoff
- 🔒 EXIF / metadata removal
- 🛡 Graceful AI failure handling

`Next.js` `TypeScript` `Supabase` `OpenRouter` `OpenStreetMap` `Sharp`

<br/>

[![Live](https://img.shields.io/badge/Live%20Demo-000000?style=flat-square&logo=vercel)](https://limnora.vercel.app)
[![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/SumitRaikwar18/Limnora)
[![Devpost](https://img.shields.io/badge/Devpost-003E54?style=flat-square)](https://devpost.com/software/limnora)

</td>

<td width="50%" valign="top">

### 💸 PayWall.ai

**Payment Infrastructure for AI Agents**

PayWall.ai adds programmable payments in front of HTTP APIs so software agents can pay for services per request.

```text
Agent
  ↓
API Request
  ↓
402 Payment Required
  ↓
Programmatic Payment
  ↓
Verified Settlement
  ↓
API Response
```

**Highlights**

- 🤖 MCP server for agent tools
- 🛠 `register_paywall`
- ⚡ `pay_and_fetch`
- 💳 x402 payment flow
- 🌐 Reverse API proxy
- 💵 Stellar USDC settlement
- 🔎 Transaction proof

`TypeScript` `Next.js` `MCP` `x402` `Stellar` `USDC`

<br/>

[![Repo](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github)](https://github.com/SumitRaikwar18/PayWall.ai)

</td>
</tr>
</table>

---

## ⚡ StreamPay

**Programmable USDC Payment Streams**

StreamPay is a Stellar + Soroban application for continuous USDC payment streams.

It supports escrowed funds, time-based earnings, withdrawals, fee accounting, wallet integration, and on-chain event tracking.

**Built with**

`Next.js` · `TypeScript` · `Rust` · `Soroban` · `Stellar` · `USDC`

**Highlights**

- USDC escrow
- Create / pause / resume / complete streams
- Recipient withdrawals
- Inter-contract fee accounting
- Multi-wallet support
- Soroban RPC events
- Frontend + smart-contract CI

[![Live](https://img.shields.io/badge/Live%20App-000000?style=flat-square&logo=vercel)](https://streampay-roan.vercel.app)
[![Repo](https://img.shields.io/badge/Repository-181717?style=flat-square&logo=github)](https://github.com/SumitRaikwar18/StreamPay)

---

# 🧠 What I Like Building

### Human-in-the-loop AI

I don't want uncertain model output to silently become the final answer.

I prefer workflows where evidence stays visible:

```text
User observation
       ↓
Independent model interpretation
       ↓
Compare evidence
       ↓
Human review
       ↓
Next action
```

Limnora is one example of this approach.

---

### 🤖 Tool-Using Agents

I'm interested in systems where AI can interact with real software instead of only producing text.

```text
Model
  ↓
Structured decision
  ↓
Tool / API
  ↓
External system
  ↓
Verified result
```

That includes:

- MCP
- API integrations
- structured actions
- external tools
- programmable payments
- verifiable execution

PayWall.ai explores this from the payments side.

---

### 🛡 Reliable AI Workflows

Real systems have failure modes.

```text
Model call fails
Provider rate-limits
Input is incomplete
Evidence conflicts
Tool execution fails
Network request times out
```

The application still needs to behave correctly.

I care about:

- failure recovery
- structured outputs
- preserving previous good state
- source-data integrity
- human review
- clear trust boundaries
- tests and verification

---

# 🛠 Tech Stack

<div align="center">

### 🤖 AI & Agent Systems

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

`OpenRouter` · `MCP` · `Tool Use` · `Structured Outputs` · `Human-in-the-loop`

<br/>

### 💻 Full Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

<br/>

### ⚡ AI Coding Tools

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge)
![OpenAI Codex](https://img.shields.io/badge/OpenAI%20Codex-000000?style=for-the-badge&logo=openai&logoColor=white)
![Cursor](https://img.shields.io/badge/Cursor-111111?style=for-the-badge)

**Claude Code · OpenAI Codex · Cursor**

<br/>

### 🔧 Developer Tools

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

<br/>

### ⛓️ Web3 — Additional Stack

![Stellar](https://img.shields.io/badge/Stellar-090020?style=for-the-badge&logo=stellar&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

`Soroban` · `USDC` · `x402`

</div>

---

# ⚙️ How I Build

```text
Problem
   ↓
Product workflow
   ↓
Architecture
   ↓
Trust boundaries
   ↓
AI / tool integration
   ↓
Failure handling
   ↓
Testing
   ↓
Deployment
```

I use tools like **Claude Code, OpenAI Codex and Cursor** to move faster during implementation.

But the engineering decisions still come down to:

```text
architecture
product decisions
state management
debugging
security boundaries
testing
trade-offs
```

---

# 🔬 Engineering Principles

```text
AI output ≠ verified fact

confidence ≠ correctness

automation ≠ authority

a failed model call ≠ lost user data
```

I like systems that make these distinctions visible instead of hiding them.

---

# 🎯 Current Focus

```text
             AI PRODUCTS
                  │
       ┌──────────┴──────────┐
       ▼                     ▼
 Human-in-the-loop      Tool-using agents
       │                     │
       ▼                     ▼
 Evidence & review      APIs · MCP · actions
       │                     │
       └──────────┬──────────┘
                  ▼
         Reliable workflows
                  │
                  ▼
             Ship 🚀
```

---

# 📊 GitHub Stats

<div align="center">

<img height="175em" src="https://github-readme-stats.vercel.app/api?username=SumitRaikwar18&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9" />

<img height="175em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SumitRaikwar18&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9" />

</div>

<br/>

<div align="center">

<img src="https://streak-stats.demolab.com/?user=SumitRaikwar18&theme=tokyonight&hide_border=true&background=0d1117&stroke=a78bfa&ring=a78bfa&fire=f59e0b&currStreakLabel=a78bfa" />

</div>

---

# 🧩 More on GitHub

<div align="center">

I also build smaller experiments and side projects while learning new tools and technologies.

<br/>

[![All Repositories](https://img.shields.io/badge/Explore%20All%20Repositories-181717?style=for-the-badge&logo=github)](https://github.com/SumitRaikwar18?tab=repositories)

</div>

---

# 🤝 Let's Build

<div align="center">

I'm interested in opportunities around

**AI Engineering · AI Products · Agent Systems · Full-Stack Engineering · Developer Infrastructure**

<br/>

If you're building something interesting, let's connect. 🚀

<br/>

[![DM on X](https://img.shields.io/badge/DM%20on%20X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/sumit_raikwar18)
[![Connect on LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sumitraikwar/)

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" />

</div>
