<p align="center">
  <img src="images/proofable-lockup-light-mode.svg#gh-light-mode-only" alt="Proofable" width="480">
  <img src="images/proofable-lockup-dark-mode.svg#gh-dark-mode-only" alt="Proofable" width="480">
</p>

<h1 align="center">Identity and governance for people and their agents</h1>

<p align="center">
  <a href="https://www.npmjs.com/package/@proofable/sdk"><img src="https://img.shields.io/npm/v/%40proofable%2Fsdk?label=%40proofable%2Fsdk&color=98C0EF" alt="npm"></a>
  <a href="https://www.npmjs.com/package/@proofable/mcp"><img src="https://img.shields.io/npm/v/%40proofable%2Fmcp?label=%40proofable%2Fmcp&color=98C0EF" alt="npm"></a>
  <a href="https://github.com/proofable/sdk/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-blue.svg" alt="Apache-2.0"></a>
  <a href="https://docs.proofable.me"><img src="https://img.shields.io/badge/docs-proofable.me-0369a1" alt="Docs"></a>
  <a href="https://discord.gg/cpNJVuq4UW"><img src="https://img.shields.io/badge/discord-community-5865F2?logo=discord&logoColor=white" alt="Discord"></a>
</p>

<p align="center">
  <a href="https://proofable.me">Website</a>
  |
  <a href="https://docs.proofable.me">Docs</a>
  |
  <a href="https://docs.proofable.me/benchmark">Benchmarks</a>
  |
  <a href="https://docs.proofable.me/mcp/setup">Install</a>
  |
  <a href="https://github.com/proofable/agent">Agent template</a>
</p>

⭐ *Help us reach more developers. Star [proofable/agent](https://github.com/proofable/agent).*

Proofable gives every agent you run across Claude Code, Cursor, Codex, ChatGPT and any MCP client its own identity and a permission you sign, checks every action against it outside the agent before it runs, and leaves a receipt anyone can verify offline.

**Agents that can't do what you never allowed.**

---

## Proofable Overview

Proofable is the authority layer your agents answer to. You sign what an agent may do: its tools, its spend, its end date, and which steps wait for your yes. Every call is decided outside the agent's process before it runs, so a fooled or hijacked agent still can't cross the line. Built for developers who let agents do real work and need to prove what they did.

**Key Capabilities:**

- **Its own identity** - every agent gets an ID tied to the person or business it works for
- **A permission instead of a key** - tools, spend cap, expiry and approvals, signed by the owner and checked before every call
- **Keys it uses and never sees** - credentials stay in a vault; the agent gets the result, never the secret
- **Revoke once, stop everywhere** - one revoke stops every copy of the agent in every tool
- **Receipts anyone can check** - every action is a signed record that verifies offline, without trusting us

---

## 🚀 Quick Start

### 1. Install Proofable

**Copy & paste setup prompt into your coding agent**

```text
Set me up for Proofable. With a terminal, run `npx -y @proofable/sdk setup`. Otherwise fetch and follow https://raw.githubusercontent.com/proofable/mcp/main/skills/proofable-setup/SKILL.md
```

Or connect any MCP client to `https://mcp.proofable.me/mcp`.

### 2. Use your agents normally

Your agents keep working in the tools you already use. Anything outside the permission is stopped before it runs, and anything you marked for approval waits for your yes.

### 3. Check the receipts

Every receipt verifies offline. Try to forge one:

```bash
git clone --depth 1 https://github.com/proofable/docs
cd docs/public/evidence/checks && npm install && node tamper-check.mjs
```

150 forgery attempts across ten kinds of tampering, 150 caught. No account needed.

---

Free to start with 500 credits a month. Make it Proofable.
