<h1 align="center">Agents that can't do what you never allowed</h1>

<p align="center">
  <a href="https://www.npmjs.com/package/@proofable/sdk"><img src="https://img.shields.io/npm/v/%40proofable%2Fsdk?label=%40proofable%2Fsdk&color=98C0EF" alt="npm"></a>
  <a href="https://github.com/proofable/sdk/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-Apache--2.0-blue.svg" alt="Apache-2.0"></a>
  <a href="https://docs.proofable.me"><img src="https://img.shields.io/badge/docs-proofable.me-0369a1" alt="Docs"></a>
  <a href="https://discord.gg/cpNJVuq4UW"><img src="https://img.shields.io/badge/discord-community-5865F2?logo=discord&logoColor=white" alt="Discord"></a>
</p>

<p align="center">
  <a href="https://proofable.me">Website</a>
  |
  <a href="https://docs.proofable.me">Docs</a>
  |
  <a href="https://proofable.me/benchmarks">Benchmarks</a>
  |
  <a href="https://github.com/proofable/agent">Agent template</a>
  |
  <a href="https://codespaces.new/proofable/agent">Open in Codespaces</a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="images/terminal-dark.svg">
    <img src="images/terminal-light.svg" width="760" alt="An agent refunds an order it is allowed to, is stopped before running a command it was never given, and every receipt survives a forgery check">
  </picture>
</p>

You sign what an agent may do: its tools, its spend, its end date, and which steps wait for your yes. Every call is checked outside the agent before it runs, in any MCP client, so a hijacked agent still can't cross the line.

## Start in one command

Paste this into your coding agent:

```text
Set me up for Proofable. With a terminal, run `npx -y @proofable/sdk setup`. Otherwise fetch and follow https://raw.githubusercontent.com/proofable/mcp/main/skills/proofable-setup/SKILL.md
```

Or connect any MCP client to `https://mcp.proofable.me/mcp`. Then use your agents as usual: anything outside the permission is stopped, and anything marked for approval waits for you.

## What you get

- **Its own identity.** Every agent has an ID tied to the person or business it works for.
- **A permission instead of a key.** Tools, spend cap, expiry and approvals, checked before every call.
- **Keys it uses and never sees.** Credentials stay in a vault; the agent gets the result, never the secret.
- **Revoke once, stop everywhere.** One revoke stops every copy of the agent in every tool.
- **Receipts anyone can check.** Every action leaves a signed record that verifies offline.

## Results

| Benchmark | Result |
|---|---|
| **NVIDIA Live Agent Gauntlet** | #1 of 20 teams: 98.00 |
| **AgentDojo** (ETH Zurich, prompt injection) | Attacks that landed fell from 16.4% to 6.2% on the same model, with 87% of tasks still done |
| **PrecisionMemBench** (agent memory) | **77 of 77**, tied for first. Hindsight 66; Mem0 and Zep 9 |
| **AgentGovBench** (agent rules) | **48 of 48**. Best gateway 46; coding agents on their own 13 |
| **Hijacked agent** | **0 of 6** data-theft attempts got out, against 6 of 6 on an all-purpose key |
| **Forgery test** | **150 of 150** forged receipts caught |

Run the forgery test yourself, no account needed:

```bash
git clone --depth 1 https://github.com/proofable/docs
cd docs/public/evidence/checks && npm install && node tamper-check.mjs
```

Methods and raw results: [proofable.me/benchmarks](https://proofable.me/benchmarks)

Free to start with 500 credits a month. Make it Proofable.
