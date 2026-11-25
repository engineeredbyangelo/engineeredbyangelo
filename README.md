# Hi, I’m Angelo 👋🏾

## AI-Native Developer · Coding Agents · Agentic Workflows

I design and ship production software by orchestrating coding agents as high-context engineering partners—not as black-box generators.
 
After 3.5+ years as an SDR selling AI and software solutions, I moved from selling software to building it. Since June 2025 I’ve been shipping real products while developing practical systems for working with coding agents at the code level.

I use Claude Code (primarily), Lovable (UI/UX only), and GitHub-native workflows to move from idea to reviewed, maintainable code.

Agents accelerate implementation, architecture exploration, testing, and edge-case discovery. I still own product direction, system design, security boundaries, code review, and what actually ships.

> Agents give me leverage. Judgment, permissions, context design, and shipping discipline are still the job.

---

## How I Orchestrate Coding Agents

My approach treats agents as controllable teammates with clear roles, constraints, and feedback loops rather than open-ended prompt surfaces.

- **Role separation**: Builder agents implement and fix; separate checker agents review diffs, enforce tests, and block regressions. They loop until lint and tests pass.
- **Context hygiene**: Prefer short, decision-focused briefs over compacting failed attempts. Dead ends stay out of the next session.
- **Permissions and hooks**: Instructions shape behavior; permissions and PreToolUse hooks enforce it. Deny rules and config blocks prevent agents from weakening tests or touching sensitive files.
- **Reviewable output**: Agents produce diffs a human will read. Large, multi-concern PRs get split. Generated code is inspected, hardened, and owned.
- **Skills and tooling discipline**: Start lean. Add skills or MCPs only after the same explanation is repeated. Knowing how to talk to the agent beats overloading it.
- **GitHub-native control**: Agent instructions (`CLAUDE.md`, `AGENTS.md`, rules files) are treated as versioned policy. Drift is managed through reviewable changes, not ad-hoc files.

This workflow is what lets me move fast on full-stack products while keeping the code reviewable and maintainable.

---

## What I’m Building

- Full-stack web apps and PWAs in React, Next.js, and TypeScript (Tailwind + shadcn/ui)
- Supabase-backed products: auth, Postgres, realtime, and the operational layer around them
- GitHub-native developer tools and policy-as-code systems for AI coding agents
- Internal tools and B2B workflow software that need clear ownership, auditability, and human review
- Fast MVPs structured so they can become durable product foundations

---

## Current Focus

Products and systems at the intersection of:

- Coding-agent orchestration: multi-agent loops, context management, permissions, hooks, and reviewable agent workflows
- Policy-as-code and governance for agent instructions across repositories
- B2B workflow software and internal operational tools
- Compliance-readiness and audit-oriented systems that stay human-reviewable
- AI-assisted product development where the code stays owned, tested, and maintainable

---

## Tech Stack

| Area | Technologies |
|---|---|
| **Frontend** | React, Next.js, TypeScript, Vite |
| **UI / Design Systems** | Tailwind CSS, shadcn/ui, Radix UI, Framer Motion |
| **Backend / Data** | Supabase, PostgreSQL, Firebase, Convex |
| **Authentication / Storage** | Supabase Auth, Supabase Storage |
| **Agent Workflows** | Claude Code (VS Code), builder/checker loops, permissions & hooks, context management |
| **Developer Tooling** | Git, GitHub, GitHub Apps, pull-request workflows, AGENTS.md / CLAUDE.md policy |
| **Mobile / Cross-Platform** | React Native, Expo |
| **Product / UX** | Figma, Mobbin, 21st.dev |

---

## Featured Builds

### 1. ContextOps
**Policy-as-code for AI coding agents.**

A GitHub-native control layer for the instructions coding agents use (`AGENTS.md`, `CLAUDE.md`, Copilot instructions, Cursor rules, etc.). Those files drift and become inconsistent at scale. ContextOps gives them a versioned, reviewable, repository-aware lifecycle.

> Define engineering policy once, validate it against repository-specific instructions, and ship changes through reviewable pull requests.

**Core capabilities:**
- Central policy management for agent instructions
- Repository-specific configuration and assignments
- Versioning, validation, and drift detection
- GitHub App integration with controlled access
- Reviewable diffs, pull-request workflows, and audit logs
- Fail-closed behavior on ambiguous or risky sync states

**Build approach:** Prototyped the control plane in Lovable, then moved into VS Code + Claude Code for GitHub App architecture, security testing, webhook handling, and edge-case hardening. The execution layer was built as tested, reviewable code.

**Stack:** React, TypeScript, Tailwind CSS, shadcn/ui, Supabase, GitHub App, GitHub API, webhooks  
**Focus:** AI governance, developer experience, policy-as-code, secure repository automation

---

### 2. AuditReady
**AI-assisted compliance-readiness software for growing SaaS teams.**

Turns scattered policies, evidence, and documentation into a structured readiness workflow for SOC 2, ISO 27001, and related frameworks. Outputs stay human-reviewable; the tool supports the first pass rather than replacing auditors or lawyers.

**What I built and worked through:**
- Compliance workflows for policies, controls, owners, tasks, and evidence
- AI-assisted document analysis and gap identification with structured findings
- Secure auth, document handling, and multi-step product flows
- Edge-case analysis and application hardening with Claude Code
- GitHub-synced workflow: rapid initial build in Lovable, then local refinement in VS Code / Claude Code

**Stack:** React, TypeScript, Vite, Tailwind CSS, shadcn/ui, Supabase  
**Focus:** Compliance operations, audit preparation, document intelligence, B2B SaaS

---

### 3. SpecMirror
**AI-powered product specification and PRD generation.**

Turns plain-language product briefs into structured technical specifications and PRDs. Designed to reduce the gap between an early concept and the documentation needed to build it well.

**Stack:** React, TypeScript, Vite, Tailwind CSS, shadcn/ui, Framer Motion, Supabase, encrypted sharing  
**Focus:** Product discovery, requirements clarity, product-to-engineering translation

---

### 4. Spark Platform
**Mobile-first micro-learning experience for people learning technology.**

Short, interactive lessons aimed at making technical concepts more accessible for self-directed learners.

**Stack:** React Native, Expo, TypeScript, Tailwind CSS, shadcn/ui, Supabase  
**Focus:** Mobile learning, gamification, accessible technical education

---

### 5. Astra Prototype One
**Scroll-driven product concept for a rugged tactical smartwatch.**

Exploratory product experience combining industrial design, terrain intelligence, biometrics, and high-performance interface storytelling.

**Stack:** React, TypeScript, Vite, Tailwind CSS, shadcn/ui, Framer Motion  
**Live:** [astraprototype.one](https://astraprototype.one/)  
**Focus:** Interactive storytelling, premium UI, motion design

---

## How I Work

**Agent-orchestrated, not agent-dependent.**  
I design the roles, constraints, and feedback loops. Agents implement and review inside those boundaries. I stay responsible for the systems that ship.

**Production-minded.**  
Interfaces are the start. I care about ownership, edge cases, permissions, test integrity, security boundaries, and whether a human can still understand and maintain the code.

**Sales-informed.**  
My SDR background keeps me focused on real customer problems, clear outcomes, and software that can actually be explained, adopted, and maintained.

**Iterative by default.**  
Ship a focused, testable version. Find the weaknesses. Harden it. Repeat. Learning happens in the code and in the agent loops, not in isolation.

---

## Currently Building and Exploring

- Multi-agent orchestration patterns (builder/checker, context hygiene, permission models)
- Secure GitHub App and webhook architecture for agent control planes
- Policy-as-code systems for coding-agent instructions
- Production-grade auth, authorization, and multi-tenancy
- Testing, debugging, and codebase-hardening practices with coding agents
- B2B SaaS and internal tools that need both speed and reviewability

---

## Let’s Connect

I’m building in public and exploring collaboration on AI-enabled software, developer workflow tools, agent orchestration systems, and B2B products.

[**X**](https://x.com/builtbyangelo) • [**LinkedIn**](https://linkedin.com/in/angeloapplewhite)
