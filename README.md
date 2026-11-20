<p align="center">
  <a href="https://ws42.ca"><img src="logo.svg" alt="Workshop 42" width="120"></a>
</p>

<h1 align="center">Workshop 42</h1>

<p align="center"><strong>Make. Break. Create.</strong><br>
A real workshop in Ottawa and the online home for everything <a href="https://joshboyer.ca">Josh Boyer</a> builds: applied AI tools, websites, and 3D-printed things.</p>

<p align="center">
  <a href="https://ws42.ca">ws42.ca</a> ·
  <a href="https://ws42.ca/guardrails">guardrails</a> ·
  <a href="https://build.ws42.ca">Build</a> ·
  <a href="https://joshboyer.ca">joshboyer.ca</a> ·
  <a href="https://www.linkedin.com/in/joshboyerca">LinkedIn</a>
</p>

---

## 🛡️ guardrails

[![npm](https://img.shields.io/npm/v/@ws42ca/guardrails)](https://www.npmjs.com/package/@ws42ca/guardrails)
[![license](https://img.shields.io/npm/l/@ws42ca/guardrails)](https://www.npmjs.com/package/@ws42ca/guardrails)

AI coding agents optimise for a green build. Left alone, they delete the failing test, loosen the assertion, or invent a package that doesn't exist. **guardrails** blocks those shortcuts in CI and inside the agent's own editor.

- **Keeps tests honest:** blocks removed tests, loosened matchers and lowered thresholds, and new tests must fail on the base branch first.
- **Stops the agent at the source:** editor hooks for Claude Code, Codex, Gemini and Antigravity refuse edits to locked files.
- **Leaves a paper trail:** risky changes need a human approval label such as `guardrails:tests-removed-approved`.
- **One package:** a CLI, an MCP server, an agent skill and one config file per project.

```bash
npm i -D @ws42ca/guardrails
npx guardrails init
```

[Read the docs →](https://ws42.ca/guardrails)

## 🏗️ Workshop 42 Build

**[build.ws42.ca](https://build.ws42.ca)** turns a small business into a beautiful website. Tell it about your business, explore AI-guided designs, preview the result, then launch.

Client sites start from the public **[template](https://github.com/ws42-sites/template)**: Astro, Tailwind, Decap CMS and Netlify, with privacy pages, spam-protected forms and analytics ready to switch on.

## 💻 Built in code

| Project | What it is | Stack |
| --- | --- | --- |
| [Nexus](https://ws42.ca/blog/nexus.html) | An independent AI orchestration project, built to learn by building | React, TypeScript, Node.js, PostgreSQL |
| [Lowkey Parakeet](https://ws42.ca/blog/lowkey-parakeet.html) | Private voice-to-text using NVIDIA Parakeet models running on the device | Tauri, Rust, React |
| [Forage](https://goforage.ca/) | Household management: home upkeep, kitchen planning and shared coordination (beta) | React, Fastify, PostgreSQL |
| [Dayna's Pet Sitting](https://www.daynaspetsitting.com/) | A hand-built site for a friend's pet-care business | Gatsby, Sanity, GraphQL |

## 🖨️ Built in plastic

Sketch, print, test, adjust. Designs are shared on [MakerWorld](https://makerworld.com/en/@user_2931215427).

- **Thermafill**, a refill adapter for Thermacell fuel cartridges, and the workshop's biggest hobby win: 1.2k+ downloads and 4.8/5 from 80 print-profile ratings.
- **[Apex monitor riser](https://ws42.ca/blog/apex-monitor-riser.html)**, a wooden shelf on four printed legs.
- **[The Voyager](https://ws42.ca/blog/voyager.html)**, a small floating canoe toy.

**On the bench:** Fusion 360 · Bambu Lab printers · a 40 W Creality diode laser · LightBurn

---

<p align="center"><sub>Built in Ottawa, Canada 🇨🇦 · Notes on what worked and what didn't at <a href="https://ws42.ca">ws42.ca</a></sub></p>
