<p align="center">
  <img src="images/hero.webp" width="880" alt="An AI tool picks up your launch notes, rules and agents from your Proofable profile while your keys stay in the vault, and the same profile reaches every AI tool you use">
</p>

<h1 align="center">Every AI knows your work and follows your rules</h1>

<p align="center">
  One profile carries your context, agents, skills and keys into the tools you already use.<br>
  Every action is checked before it runs and leaves a receipt anyone can check.
</p>

<p align="center">
  <a href="https://proofable.me/proof/0x6e0c65367d27489d615263908a80e1f97e64684664a465dfc5120290af2ef2cf"><img src="https://img.shields.io/badge/proofable.me-verified_on_Proofable-2F5097?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MTIgNTEyIiByb2xlPSJpbWciIGFyaWEtbGFiZWw9IlByb29mYWJsZSBtYXJrIiBzaGFwZS1yZW5kZXJpbmc9Imdlb21ldHJpY1ByZWNpc2lvbiI+PHBhdGggZD0iTSA0MDAgMjU2IEEgMTg0IDE4NCAwIDEgMSAzMiAyNTYgQSAxODQgMTg0IDAgMSAxIDQwMCAyNTYgWiBNIDM2MyAyNTYgQSAxNDcgMTQ3IDAgMSAxIDY5IDI1NiBBIDE0NyAxNDcgMCAxIDEgMzYzIDI1NiBaIiBmaWxsPSIjRkZGRkZGIiBmaWxsLXJ1bGU9ImV2ZW5vZGQiLz48cGF0aCBkPSJNIDMzNi4yMiA4MC4xNyBBIDE4NCAxODQgMCAwIDEgMzM2LjIyIDQzMS44MyBBIDIxMyAyMTMgMCAwIDAgMzM2LjIyIDgwLjE3IFoiIGZpbGw9IiNGRkZGRkYiLz48L3N2Zz4=" alt="proofable.me verified on Proofable"></a>
  <a href="https://www.npmjs.com/package/@proofable/sdk"><img src="https://img.shields.io/npm/v/%40proofable%2Fsdk?label=%40proofable%2Fsdk&color=98C0EF" alt="npm"></a>
  <a href="https://discord.gg/cpNJVuq4UW"><img src="https://img.shields.io/badge/discord-community-5865F2?logo=discord&logoColor=white" alt="Discord"></a>
</p>

<p align="center">
  <a href="https://proofable.me/?ref=github">Website</a>
  |
  <a href="https://docs.proofable.me">Docs</a>
  |
  <a href="https://proofable.me/marketplace?ref=github">Marketplace</a>
  |
  <a href="https://proofable.me/benchmarks?ref=github">Benchmarks</a>
  |
  <a href="https://proofable.me/u/proofable">Our profile</a>
</p>

## Run every agent from one place

<p align="center">
  <a href="https://proofable.me/profile?tab=chat&ref=github"><img src="images/platform.png" width="880" alt="The Proofable dashboard with three agents and their runs, an activity feed, and a release waiting for your approval with Stop and Approve and run"></a>
</p>

Approve, stop or chat with any agent, and see every run and the work it is on.

## The same rules in your terminal

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="images/terminal-dark.svg">
    <img src="images/terminal-light.svg" width="760" alt="An agent refunds an order it is allowed to, is stopped before running a command it was never given, and every receipt survives a forgery check">
  </picture>
</p>

Allowed calls go through. Anything else stops before it runs.

## Start in one click

<a href="https://cursor.com/en/install-mcp?name=proofable&config=eyJ1cmwiOiJodHRwczovL21jcC5wcm9vZmFibGUubWUvbWNwIn0%3D"><img src="images/buttons/cursor.png" alt="Add to Cursor" height="44"></a>
<a href="https://vscode.dev/redirect/mcp/install?name=proofable&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.proofable.me%2Fmcp%22%7D"><img src="images/buttons/vscode.png" alt="Install in VS Code" height="44"></a>
<a href="https://insiders.vscode.dev/redirect/mcp/install?name=proofable&config=%7B%22type%22%3A%22http%22%2C%22url%22%3A%22https%3A%2F%2Fmcp.proofable.me%2Fmcp%22%7D&quality=insiders"><img src="images/buttons/vscode-insiders.png" alt="Install in VS Code Insiders" height="44"></a>
<a href="https://chatgpt.com/plugins/plugin_asdk_app_6ae65c2bac0881918812c63246c7e6c9"><img src="images/buttons/chatgpt.png" alt="Add to ChatGPT" height="44"></a>

Every AI tool on your machine, in one command. It finds Claude Code, Codex, Cursor and VS Code and adds Proofable to each:

```bash
npx -y @proofable/sdk setup
```

[Claude Code, Codex, Hermes and every other client](https://github.com/proofable/mcp#connect-in-one-click)

## What you get

- **Your work in every AI tool.** Notes, rules, agents and skills load from one profile, so you never explain them twice.
- **Only what is true now.** A new fact replaces the old one, so answers come out right at a fraction of the tokens.
- **Agents inside your rules.** Choose what each agent may do, cap its spend and set when its access ends. Irreversible actions wait for you, and one revoke stops it everywhere.
- **Keys they use and never see.** Credentials stay in a vault, bound to the agent that needs them.
- **A receipt for every action.** It checks offline in milliseconds, so the next agent trusts the work instead of redoing it.
- **Prove who you are once.** Reuse it in every app, gate your own app on it, and sell your agents and tools on the [marketplace](https://proofable.me/marketplace?ref=github).

## Results

| | Proofable | The usual way |
|---|---|---|
| Memory questions answered right ([PrecisionMemBench](https://proofable.me/benchmarks/memory?ref=github)) | **77 of 77** | Mem0 9 |
| Tokens to find the current rule | **43,169** | 479,623 searching every record |
| Rule scenarios held ([AgentGovBench](https://proofable.me/benchmarks/governance?ref=github)) | **48 of 48** | Best gateway 46 |
| Prompt injections that landed ([AgentDojo](https://proofable.me/benchmarks/security?ref=github)) | **6.2%**, with 87% of tasks done | 16.4% with no defense |
| Private data out of a hijacked agent | **0 of 6** | 6 of 6 on an all-purpose key |
| Forged receipts accepted | **0 of 150** | 150 of 150 by a format-only check |

Top score of 20 teams in NVIDIA's Live Agent Gauntlet, 98.00. [Every method and run](https://proofable.me/benchmarks?ref=github)

Try to forge a receipt yourself, no account needed:

```bash
git clone --depth 1 https://github.com/proofable/docs
cd docs/public/evidence/checks && npm install && node tamper-check.mjs
```

## Repositories

| Repository | What it is |
|---|---|
| [**mcp**](https://github.com/proofable/mcp) | The server every AI tool connects to, with one-click installs, plugins and setup skills |
| [**sdk**](https://github.com/proofable/sdk) | `@proofable/sdk` and the `proofable` CLI, plus the offline receipt checker |
| [**agent**](https://github.com/proofable/agent) | An agent template that works inside the rules you set |
| [**docs**](https://github.com/proofable/docs) | Docs, benchmark evidence and schemas |
| [**agent-gauntlet**](https://github.com/proofable/agent-gauntlet) | The submission that topped NVIDIA's Live Agent Gauntlet, receipts included |

Free to start with 500 credits a month. **[Start free](https://proofable.me/profile?tab=chat&ref=github)**

Make it Proofable.
