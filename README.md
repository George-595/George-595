<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./banner-strata.png" />
    <source media="(prefers-color-scheme: light)" srcset="./banner-strata-light.png" />
    <img src="./banner-strata.png" width="100%" alt="George Allan — Agentic Engineer at NCS. Building the harnesses teams ship with." />
  </picture>
</div>

<p align="center"><b>Choices beat talent. Shipping beats credentials.</b></p>

<div align="center">
  <a href="https://ncs.agency/"><img src="https://img.shields.io/badge/NCS-ncs.agency-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="NCS website" /></a>
  <a href="https://www.linkedin.com/in/george-allan-3479a0237"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</div>

## About Me

I'm an **agentic engineer** at **NCS**, an AI-first engineering consultancy. I build the harnesses, skills and orchestration that let a whole engineering team ship with AI agents, and I got here without a CS degree.

I studied **Geology** at Southampton and taught myself to code the long way round: PineScript trading bots, then Python, then a weekend app that turned muddy, handwritten borehole logs into structured `.ags` data with an AI handwriting model. That's when it clicked: the thing I built on weekends for free was the thing I should be paid to do on a Monday.

<table>
  <tr>
    <td width="50%" valign="top">
      <b>What I'm About</b>
      <ul>
        <li>Agents are only as good as their harness</li>
        <li>Secure, correct code over quick hacks</li>
        <li>Understanding the <em>why</em> behind every decision</li>
        <li>Shipping &mdash; done beats perfect</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <b>The Roundabout Path</b>
      <ul>
        <li>BSc Geology &mdash; University of Southampton</li>
        <li>Geotechnical Engineer &mdash; Ian Farmer Associates (RSK)</li>
        <li>Associate Software Engineer &mdash; NCS, specialising in agentic &amp; harness engineering</li>
      </ul>
    </td>
  </tr>
</table>

## What I've Built

### 🐝 Hive — *multi-agent orchestration for Claude Code*

I designed and built Hive, a multi-agent orchestration system that's been adopted across the company. Hive splits a batch of work into independent jobs and runs each one in its own Claude Code session, so engineers direct the work instead of babysitting one chat at a time.

- **Token-efficient by design:** keeps each waiting agent's prompt cache warm, so it doesn't pay for a full cache rebuild when it picks back up
- **Resource-aware:** manages CPU load so running many agents doesn't grind a dev machine to a halt
- **Adopted company-wide:** it started as my own workflow and became the default way of building

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/hive-architecture.png" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/hive-architecture-light.png" />
  <img src="./assets/hive-architecture.png" width="100%" alt="Hive architecture: inputs from you, Slack and Teams, tickets and nightly CI flow into the Hive orchestrator, which splits work into jobs, routes each to a model, schedules against machine resources and runs Claude Code workers in their own git worktrees, producing pull requests, a live panel, a Build Room dashboard, and spoken and Slack updates." />
</picture>

### Quore Geotechnical — *instant, client-ready site intelligence*

The product that turned me from a geotechnical engineer into a software engineer. Borehole logs came back from site mud-smeared and half-illegible, and someone retyped them by hand into HoleBASE / OpenGround, which took hours per site. With Quore you snap a photo of the notes, an **AI handwriting model** extracts the data, and the app exports standards-compliant **`.ags`** files straight into the industry databases.

<a href="https://quoresoftware.com/quore-geotechnical"><img src="https://img.shields.io/badge/Website-quoresoftware.com-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Quore Geotechnical website" /></a>

### Furniture Friends — *AI inventory management for a local charity*

A pro-bono build for **Furniture Friends**, a Datchworth charity that finds new homes for donated furniture. It replaced their manual stock-keeping with an **AI-powered inventory system**, so volunteers can see what's come in, what's available and where it's gone without wrestling a spreadsheet.

<a href="https://www.datchworth.com/furniture-friends/"><img src="https://img.shields.io/badge/Website-datchworth.com-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Furniture Friends charity website" /></a>

<!--
## Writing
Uncomment once the first post is up — notes on building agent harnesses.
- [Post title](https://link) — one-line summary
-->

## Stack

**Languages** — TypeScript · JavaScript · Python · Bash<br>
**Runtime** — Node.js · React · Next.js<br>
**Data & infra** — PostgreSQL · Docker · Turborepo<br>
**Agentic** — Claude Code · skills & sub-agents · prompt caching<br>
**Workflow** — Git · pnpm · Warp · Obsidian · Wispr Flow
