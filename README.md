# Agent Builders Club Build-a-thon

<p align="center">
  <strong>A practical AI build sprint for curious people, builders, and small teams.</strong>
</p>

<p align="center">
  Build something useful, strange, unfinished, or surprising—and leave with something you can show.
</p>

<p align="center">
  <a href="https://luma.com/o0jfobup"><img src="https://img.shields.io/badge/RSVP-Luma-6f42c1?style=for-the-badge" alt="RSVP on Luma"></a>
  <img src="https://img.shields.io/badge/Status-Live%20for%20participants-2ea44f?style=for-the-badge" alt="Live for participants">
  <img src="https://img.shields.io/badge/Teams-2%E2%80%934%20people-f59e0b?style=for-the-badge" alt="Teams of 2 to 4 people">
  <img src="https://img.shields.io/badge/Format-In--person-111827?style=for-the-badge" alt="In-person event">
</p>

<p align="center">
  <a href="https://github.com/Agent-Builders-Club/agent-builders-club-buildathon/commits/main"><img src="https://img.shields.io/github/last-commit/Agent-Builders-Club/agent-builders-club-buildathon?style=flat-square" alt="Last commit"></a>
  <a href="https://github.com/Agent-Builders-Club/agent-builders-club-buildathon/issues"><img src="https://img.shields.io/github/issues/Agent-Builders-Club/agent-builders-club-buildathon?style=flat-square" alt="Issues"></a>
  <a href="https://github.com/Agent-Builders-Club/agent-builders-club-buildathon/tree/main/projects"><img src="https://img.shields.io/badge/Projects-Submit%20your%20build-0ea5e9?style=flat-square" alt="Submit a project"></a>
</p>

## Event

| | Details |
|---|---|
| **When** | Wednesday, August 19, 2026 · 6:30–9:00 PM Central Time |
| **Where** | The Copper Wall, 1137 Burton Hill Rd, Fort Worth, TX 76114 |
| **RSVP** | [Register on Luma](https://luma.com/o0jfobup) |
| **Team size** | 2–4 people |
| **Format** | Choose or draw a prompt, build with a team, then give a short demo |

## Start here

| If you are… | Read this |
|---|---|
| **A participant** | [`EVENT-GUIDE.md`](EVENT-GUIDE.md) |
| **Looking for a prompt** | [`PROMPTS.md`](PROMPTS.md) |
| **Preparing your demo** | [`DEMO-GUIDE.md`](DEMO-GUIDE.md) |
| **Submitting a project** | [`CONTRIBUTING.md`](CONTRIBUTING.md) and [`projects/_template`](projects/_template) |

## What this is

The Agent Builders Club Build-a-thon is a focused, accessible evening for making things with AI.

You do **not** need:

- A polished startup idea
- Advanced engineering experience
- A finished product
- A large team
- A perfect demo

You can use code, no-code tools, AI agents, APIs, design tools, spreadsheets, or a combination. The important thing is to make a result that your team can explain and demonstrate.

A valid project might be:

- A working prototype
- A useful automation
- A small tool
- A compelling mockup
- A research workflow
- A new interface for an old problem
- A documented experiment
- A clear, honest failure that teaches the group something

## How the evening works

1. **Meet people and form teams** of 2–4.
2. **Choose or draw a prompt** from the prepared prompt bank.
3. **Swap prompts once** during the opening window, if your team wants to.
4. **Build a small, demonstrable result** with your team.
5. **Document the project** in its folder under [`projects/`](projects/).
6. **Give a short demo** before the evening ends.

The event is intentionally friendly to rough work. Reduce scope before you add complexity.

## Repository structure

```text
.
├── EVENT-GUIDE.md             # Participant guide and event format
├── PROMPTS.md                 # Prepared Build-a-thon prompts
├── DEMO-GUIDE.md              # Short demo format and preparation checklist
├── CONTRIBUTING.md            # Project submission rules
└── projects/
    ├── README.md              # Project folder instructions and index
    ├── _template/             # Copy this for a new project
    └── your-project-name/     # One folder per team project
```

## Submit a project

Create a project folder by copying the template:

```bash
cp -R projects/_template projects/your-project-name
```

Use a short, lowercase folder name with hyphens. For example:

```text
projects/local-business-helper/
projects/meeting-memory/
projects/chores-agent/
```

Your project README should include:

- Project name
- Team members or handles
- The prompt you worked from
- What you built
- How to view or run it
- Tools and services used
- Current status
- Known limitations
- What you would build next
- Sharing permission

Add prototypes, screenshots, demo notes, links, and source files inside the same project folder when useful.

## Demo expectations

Each team should aim for a short, clear demo:

1. **Problem:** Who is this for and what problem did you choose?
2. **Build:** Show the main experience, workflow, or experiment.
3. **Lesson:** What worked, surprised you, or failed?
4. **Next step:** What would you build with more time?

A live demo is great, but a screenshot, screen recording, mockup, or explanation is acceptable when the prototype is fragile. Be honest about what is real, mocked, unfinished, or broken.

See [`DEMO-GUIDE.md`](DEMO-GUIDE.md) for the full format.

## Prompt bank

The prompt bank contains **30 broad, beginner-friendly prompts** designed for a 90-minute build sprint. They cover practical workflows, community tools, research, accessibility, creative work, public data, and personal problems.

Read the complete list in [`PROMPTS.md`](PROMPTS.md). Teams may interpret a prompt unexpectedly and may swap once during the opening window.

## Project index

Projects will be added here after teams submit them and demo:

| Project | Team | Prompt | Status | Demo / Link |
|---|---|---|---|---|
| _Add projects here after demos_ |  |  |  |  |

## Public repository and safety

This repository is public from the start of the event. Only commit work your team is comfortable sharing publicly.

- Do not commit passwords, API keys, private keys, tokens, or credentials.
- Use `.env.example` for variable names only; never commit a real `.env` file.
- Do not commit personal data, private customer information, confidential work, or anything your team does not have permission to share.
- Do not use someone else’s code, images, or data without permission.
- Assume project code, screenshots, recordings, and participant names may be visible to the public.
- If your project is not ready to be public, keep the implementation local and submit a public-safe README, mockup, or demo summary instead.

## GitHub workflow

If you are comfortable with GitHub:

1. Create a branch.
2. Add your project folder.
3. Commit your work.
4. Open a pull request titled `Add: Project Name`.
5. Ask someone at the event for help if you get stuck.

If GitHub is unfamiliar, ask someone at the event where to place your files. The goal is to preserve the work—not create a complicated workflow during the sprint.

## Recognition

The event may give informal recognition for categories such as:

- Most useful
- Most surprising
- Best use of AI
- Best demo
- Best documented failure
- Most likely to become a real project

Recognition is intended to celebrate different kinds of work. The most polished software is not automatically the best project.

## Questions

Ask an organizer in person or [open an issue](https://github.com/Agent-Builders-Club/agent-builders-club-buildathon/issues) in this repository.

## About Agent Builders Club

[Agent Builders Club](https://agentbuildersclub.dev) is a DFW community for people building with AI—founders, developers, operators, creatives, curious beginners, and everyone in between.

**Born in DFW. Built for the world.**
