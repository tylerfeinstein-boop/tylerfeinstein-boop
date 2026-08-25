## Tyler Feinstein

**Full-Stack & AI Automation Developer**

I build software that runs real business operations. Most of my work starts the
same way: a process people are doing by hand, badly, at scale — and ends as a
system with a database behind it, tests around it, and an interface someone
actually uses on a job site.

Two of those have shipped. A field-operations platform that a kitchen remodeling
company now runs its jobs on, and a game released on Google Play. Alongside them:
an AI orchestration service in active development, a desktop tool in Rust, and an
asset build pipeline in Python.

Currently expanding my formal training through the IBM Full Stack Software
Developer and IBM Data Science professional certificate programs.

---

### What I build

- **Full-stack business applications** — relational schemas, row-level security,
  role-based access, offline-tolerant sync, and delivery to web, desktop and mobile
- **AI-enabled systems** — LLM integration behind provider interfaces, structured
  extraction from unstructured input, and deterministic fallbacks so the system
  is testable without an API key
- **Automation and tooling** — build pipelines, developer tools, and the scripts
  that remove repetitive work
- **Systems programming** — Rust for desktop applications that need OS-level
  input handling and real concurrency

---

### Shipped

**Project Hub** — *JavaScript · Supabase · Capacitor · Electron*
Field operations software for a countertop and cabinet remodeling company:
projects, scheduling with route zones, site measures, a sketch pad that exports
CAD-ready DXF, document packets and time-limited client sharing. One codebase
delivering a PWA, an Android app and a Windows desktop build. PostgreSQL with
row-level security and Supabase Edge Functions. **365 automated tests.**
*In production use — office staff, field crews and installers.*

**Castle Fling** — *JavaScript · Electron · Android*
A physics castle-defence game, **released to production on Google Play**. One
source tree packaged for the browser, a Windows portable executable and a native
Android WebView wrapper, with asset validation wired into the build. Went through
closed testing, open testing and full production review.

---

### In development

**Pro Granite AI Brain** — *TypeScript · Fastify · PostgreSQL/Supabase · Claude*
A central intelligence and orchestration layer for the same business. Ingests
phone calls, resolves callers against existing customer records, and coordinates
specialised agents. The interesting part is identity resolution: deciding whether
an inbound caller is someone you already know, using frozen normalization rules,
a trust model and ranked matching. **72 passing tests**, documented with
Architecture Decision Records.

---

### Also

**Silly Valley's Auto Clicker** — *Rust · Tauri · React · TypeScript*
A Windows desktop tool with a visual click-sequence builder, global hotkeys and
an overlay HUD. The Rust side separates `input`, `display` and `recording` into
per-platform implementations behind shared interfaces, with dedicated error types
and cooperative cancellation for playback. Built for a friend, delivered, and
complete.

**Blender Asset Pipeline** — *Python*
A staged, headless pipeline that builds game-ready 3D characters and props
procedurally — geometry, UVs, textures, rigging, an eighteen-action animation
set, LODs, export and automated verification. ~38,000 lines across 94 stages.
Re-running from any stage reproduces the asset deterministically. A hobby
project, and finished.

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
remain mine. The 437 tests across the two business systems exist because I
decided what needed proving, and they pass because I fixed what they caught.

---

### Current focus

Deepening my software engineering fundamentals through the IBM Full Stack
Software Developer certificate, and building data science capability through the
IBM Data Science certificate. Alongside that: adding CI pipelines to my existing
projects and getting more of my work publicly reachable.

Open to remote roles in full-stack development, Python development, and AI
application and automation engineering.
