## Tyler Feinstein

**Full-Stack & AI Automation Developer**

I build software that runs real business operations. Most of my work starts the
same way: a process that people are doing by hand, badly, at scale — and ends as
a system with a database behind it, tests around it, and a interface someone
actually uses on a job site.

That has meant a scheduling and field-operations platform, an orchestration
layer that turns phone calls into structured customer records, a desktop tool in
Rust, an asset build pipeline in Python, and a game shipped to Google Play.

Currently expanding my formal training through the IBM Full Stack Software
Developer and IBM Data Science professional certificate programs.

---

### What I build

- **Full-stack business applications** — relational schemas, row-level security,
  role-based access, offline-tolerant sync, and delivery to web, desktop and mobile
- **AI-enabled systems** — LLM integration behind provider interfaces, structured
  extraction from unstructured input, and deterministic fallbacks so the system
  is testable without an API key
- **Automation and tooling** — build pipelines, developer tools, and the
  scripts that remove repetitive work
- **Systems programming** — Rust for desktop applications that need OS-level
  input handling and real concurrency

---

### Featured work

**Pro Granite AI Brain** — *TypeScript · Fastify · PostgreSQL/Supabase · Claude*
A central intelligence and orchestration layer for a countertop and cabinet
business. Ingests phone calls, resolves callers against existing customer
records, and coordinates specialised agents. The interesting part is identity
resolution: deciding whether an inbound caller is someone you already know, using
frozen normalization rules, a trust model and ranked matching. 72 passing tests,
documented with Architecture Decision Records.

**Project Hub** — *JavaScript · Supabase · Capacitor · Electron*
The operations workspace the business actually runs on: projects, scheduling,
site measures, document packets and client sharing. One codebase delivering a
PWA, an Android app and a desktop build. PostgreSQL with row-level security
policies and Supabase Edge Functions. 365 passing tests covering sync races,
signed URLs, workflow integrity and address parsing.

**Blender Asset Pipeline** — *Python*
A staged, headless pipeline that builds game-ready 3D characters and props
procedurally — geometry, UVs, textures, rigging, an eighteen-action animation
set, LODs, export and automated verification. ~38,000 lines across 94 stages.
Re-running from any stage reproduces the asset deterministically, which makes
the build the source of truth instead of a hand-edited file.

**Silly Valley's Auto Clicker** — *Rust · Tauri · React · TypeScript*
A Windows desktop tool with input recording, global hotkeys and an overlay HUD.
The Rust side separates `input`, `display` and `recording` into per-platform
implementations behind shared interfaces, with dedicated error types and
cooperative cancellation for playback.

**Castle Fling** — *JavaScript · Electron · Android*
A physics castle-defence game shipped to Google Play production. One source
tree packaged for the browser, a Windows portable executable, and a native
Android WebView wrapper, with asset validation wired into the build.

---

### Technical stack

**Languages**
Python · TypeScript · JavaScript · Rust · SQL · C#

**Frontend**
React · Vite · Tailwind CSS · Progressive Web Apps

**Backend**
Node.js · Fastify · Supabase Edge Functions (Deno) · REST APIs · Zod

**Data**
PostgreSQL · Supabase · schema migrations · row-level security

**AI**
Anthropic Claude API · provider abstraction with deterministic fallback ·
structured extraction · AI-assisted development workflows

**Desktop & mobile**
Tauri · Electron · Capacitor · Android (Gradle)

**Engines**
Unity · Godot · Blender (`bpy`) scripting

**Practice**
Git · unit and integration testing (Vitest, `node:test`) · ESLint · Prettier ·
Architecture Decision Records

---

### On AI-assisted development

I use modern AI development tools — Claude Code among them — for research,
scaffolding, debugging and documentation. They make me considerably faster.

They do not make the decisions. Requirements, system design, data modelling,
integration choices, what gets tested, and whether the result is actually correct
remain mine. The 437 tests across the two systems above exist because I decided
what needed proving, and they pass because I fixed what they caught.

---

### Current focus

Deepening my software engineering fundamentals through the IBM Full Stack
Software Developer certificate, and building data science capability through the
IBM Data Science certificate. Alongside that: adding CI pipelines to my existing
projects, and getting more of my work deployed and publicly reachable rather
than running locally.

Open to remote roles in full-stack development, Python development, and AI
application and automation engineering.
