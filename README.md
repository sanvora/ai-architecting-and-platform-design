# OsseoCore CDAO Simulation

An interactive, AI-powered strategy simulation where you play the newly appointed Chief Data & AI Officer of a real-feeling medtech company — and every decision you make has consequences.

---

## What Is This?

This is a **role-playing simulation** for professionals who want to practice the hardest parts of enterprise AI and data leadership: not the technical architecture, but the *organizational reality* that surrounds it.

You are dropped into Day 1 at **OsseoCore Technologies** — a fictional orthopedic medtech company mid-separation from its parent conglomerate, Helix MedGroup. Your mandate is to build the company's entire data, analytics, AI, and automation capability from scratch. You have a 90-day window before the analyst day presentation. You have 30 people to manage, persuade, or outmaneuver. And you have an organization that didn't ask for a CDAO.

This isn't a tutorial. There is no hand-holding. The simulation rewards people who ask the right questions, build the right relationships, and make defensible decisions under ambiguity.

---

## The Scenario

**OsseoCore Technologies** is spinning off from Helix MedGroup to become the world's largest standalone orthopedics company. The carve-out is live. The TSA clock is ticking. And your predecessor left no documentation.

You inherit:
- 8 strategic workstreams ranging from data platform architecture to AI use case delivery to regulatory compliance
- 30 stakeholders across the C-suite, your direct reports, the working team, and external partners — each with their own agenda, their own concerns, and their own way of working
- Three persistent organizational tensions that run through every conversation and every decision
- A CEO who wants bold AI commitments. A CFO who wants cost models. A CTO who doesn't think you should exist.

Your job is to thread all of it.

---

## The Interactive Platform

The simulation runs inside a purpose-built web application — a dark-themed, animated canvas that makes the organizational map feel alive.

**The Canvas** shows every person and every workstream as a connected network. Relationships have status. Workstreams have health. Everything is visible at once.

**The Meeting Room** is where the work happens. Drag personas into the room, start a conversation, and Claude steps into their character. Each person has a detailed profile — their background, their priorities, their blind spots, their communication style. They stay in character. They push back. They have opinions about each other.

**The Guided Mode** walks you through 5 phases, 15 missions, and 54 tasks. Each task comes with a lesson, a deliverable, and an AI evaluator that scores your work and gives specific feedback. Your XP accumulates. Your certificates stack up. Your stakeholder relationships shift based on how you engage.

**The Explorer Mode** lets you roam freely — run any conversation, switch any layout, investigate any relationship without a mission structure guiding you.

---

## Features Worth Knowing

**30 fully-realized personas.** Each one is backed by a detailed character file covering their background, what they care about, what they're afraid of, and how they communicate. When you're in a meeting with Derek Wollf, you'll know you're in a meeting with Derek Wollf.

**Relationship drift.** How you engage with people matters. Conversations move the dial. Some people shift quickly; others have been in their position for twenty years and don't move at all. The status dot on each persona updates. The canvas reflects it.

**Live deliverable tools.** Build stakeholder matrices, draw architecture diagrams in Mermaid or SysML, write strategy documents — all inside the simulation. Submit your work and get scored by AI on clarity, completeness, and strategic soundness.

**Delegate to your team.** You don't have to do everything yourself. Assign tasks to the people on your team within their responsibilities and they'll produce output you can incorporate into your deliverables.

**Eight layout modes.** Visualize your organization by reporting hierarchy, workstream membership, personality profile, relationship tension, or function. Or pin your own custom arrangement.

**Everything is connected.** Workstream health affects stakeholder mood. Stakeholder conversations affect deliverable quality. The canvas tracks it all.

---

## The Eight Workstreams

| # | Codename | Focus |
|---|---|---|
| 1 | **COMPASS** | Enterprise Data Strategy & Roadmap |
| 2 | **LAKEBED** | Modern Data Platform / Data Lakehouse |
| 3 | **SYNAPSE** | AI & Machine Learning Capabilities |
| 4 | **STREAMLINE** | Intelligent Automation |
| 5 | **INSIGHT** | Advanced Analytics & Business Intelligence |
| 6 | **GUARDIAN** | Data Governance & Compliance |
| 7 | **ACADEMY** | Data & AI Talent Strategy |
| 8 | **GENESIS** | Separation / Carve-out Data Architecture |

Each workstream has stakeholder dependencies, design decisions, and a final deliverable that gets reviewed and approved — or not.

---

## Who This Is For

- Data and AI leaders who want to stress-test their thinking in a low-stakes environment
- Professionals preparing for a CDAO, CDO, or VP-level role in a complex organization
- Teams who want a shared simulation exercise for leadership development
- Anyone who thinks they know how to navigate organizational politics around AI — and wants to find out

---

## Getting Started

### Prerequisites
- Node.js 18+
- An Anthropic API key

### Run Locally

```bash
cd frontend
npm install
```

Create a `.env.local` file:
```
ANTHROPIC_API_KEY=your_key_here
```

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

---

## What You Won't Find Here

A walkthrough. A solution guide. The "right" answers to the stakeholder conflicts. The simulation is designed to be ambiguous in the same ways real organizations are ambiguous. Some tensions don't resolve cleanly. Some people won't come around no matter what you do. Some decisions will look good until they don't.

That's the point.

---

## Tech Stack

- **Next.js 16** (App Router, Turbopack)
- **React Flow** — interactive canvas
- **Zustand** — simulation state
- **Claude (Anthropic)** — persona roleplay, deliverable scoring, delegation outputs
- **Tailwind CSS v4** — dark theme UI
- **GSAP** — animations
- **Mermaid** — live diagram rendering

---

*OsseoCore Technologies is a fictional company. Any resemblance to real organizations is coincidental. All personas are invented for simulation purposes.*
