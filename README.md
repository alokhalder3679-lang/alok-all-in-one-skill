# Alok All-in-One Skill

A single, self-contained **Master Skill (`SKILL.md`)** compiling **539 unique AI coding, design, engineering, security, and workflow skills** into one portable file with a categorized **Master Line-Range Index**.

Instead of managing hundreds of separate skill folders or losing skills to context-budget truncation, this repository gives your AI agent instant progressive access to all 539 skills from one file.

---

## Included Skill Library (539 Skills)

| Category | Skills | Highlights |
| :--- | ---: | :--- |
| **Standalone Custom Skills** | 9 | `figma-designer`, `impeccable`, `landing-page-design`, `reverse-engineer-anything`, `security-audit`, `rea-*` |
| **gstack Suite** | 63 | `office-hours`, `plan-ceo-review`, `plan-design-review`, `plan-eng-review`, `review`, `qa`, `browse`, `ship`, `retro`, `cso` |
| **Plugin: `ecc`** | 328 | Language patterns & testing (Python, TypeScript, Go, Rust, C++, Java, Kotlin, Swift, Dart), TDD, security, agentic engineering, RAG, DevOps |
| **Plugin: `vercel-plugin`** | 40 | Next.js, AI SDK, Vercel CLI, Workflow SDK, Sandbox, Flags, CDN Caching, Edge/Functions, Observability |
| **Plugin: `mattpocock-skills`** | 27 | `tdd`, `grilling`, `diagnosing-bugs`, `domain-modeling`, `write-a-skill`, `writing-for-agents`, `prototype`, `pr` |
| **Plugin: `emilkowalski-skills`** | 20 | UI animation, motion foundations, gestures, choreograph, spring physics, taste & design polish |
| **Plugin: `anthropics-skills`** | 19 | `frontend-design`, `mcp-builder`, `skill-creator`, `webapp-testing`, `pdf`, `docx`, `pptx`, `xlsx`, `canvas-design` |
| **Plugin: `jakubkrehel-skills`** | 16 | `better-interface`, `better-accessibility`, `better-colors`, `better-layout`, `better-motion`, `better-typography`, `better-ui`, `build-design` |
| **Plugin: `ui-ux-pro-max`** | 7 | `ui-ux-pro-max`, `design-system`, `brand`, `slides`, `banner-design`, `design`, `ui-styling` |
| **Plugin: `ponytail`** | 6 | `ponytail`, `ponytail-audit`, `ponytail-debt`, `ponytail-gain`, `ponytail-help`, `ponytail-review` |
| **Plugin: `supabase`** | 2 | `supabase`, `supabase-postgres-best-practices` |
| **Plugin: `hallmark`** | 1 | `hallmark` |
| **Plugin: `taste-skill`** | 1 | `design-taste-frontend` |

---

## Installation

### Option 1: Antigravity (Global Skill — Recommended)

Clone directly into your global Antigravity skills directory so it works across every project:

```bash
git clone https://github.com/alokhalder3679-lang/alok-all-in-one-skill.git ~/.gemini/config/skills/alok-all-in-one-skill
```

*(On Windows PowerShell:)*

```powershell
git clone https://github.com/alokhalder3679-lang/alok-all-in-one-skill.git "$HOME\.gemini\config\skills\alok-all-in-one-skill"
```

### Option 2: Project-Local (`.agents/skills/`)

Add to any individual repository so your team shares it automatically:

```bash
git clone https://github.com/alokhalder3679-lang/alok-all-in-one-skill.git .agents/skills/alok-all-in-one-skill
```

### Option 3: Direct Single-File Download

Download [`SKILL.md`](./SKILL.md) directly and place it inside an `alok-all-in-one-skill/` folder under your agent's skills directory.

---

## How It Works (Progressive Lookup)

`SKILL.md` is ~6.9 MB (~143,554 lines), so loading it all at once would overwhelm an LLM context window. Instead, the file is structured for **zero-bloat progressive lookup**:

1. **Quick Category Map (`L22-L39`):** Shows all 13 categories, skill counts, and exact line ranges.
2. **Master Skill Index (`L40-L645`):** Lists all 539 skills with one-line summaries and exact `Start-End` line numbers.
3. **Targeted Section Read:** Your AI agent reads only the index lines it needs and jumps directly to `L<start>-L<end>` to load the exact skill instructions.

---

## Credits & Upstream Sources

This compendium aggregates and indexes skills created by the community and open-source ecosystem, including:
- **gstack** (`garrytan/gstack`)
- **Everything Claude Code (`ecc`)**
- **Vercel Agent Skills / `vercel-plugin`**
- **Anthropic Skills (`anthropics-skills`)**
- **Matt Pocock Skills (`mattpocock-skills`)**
- **Emil Kowalski Skills (`emilkowalski-skills`)**
- **Jakub Krehel Skills (`jakubkrehel-skills`)**
- **UI/UX Pro Max**, **Supabase**, **Ponytail**, **Hallmark**, **Taste Skill**, **Impeccable**, **Figma Designer**, **Landing Page Design**, and **Reverse Engineer Anything (REA)**.

All credit for individual upstream skills belongs to their respective authors and repositories.
