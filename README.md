# Spegeli's SkillForge Marketplace

![Collections](https://img.shields.io/badge/Collections-2-blue) ![Skills](https://img.shields.io/badge/Skills-13-22c55e) ![Agents](https://img.shields.io/badge/Agents-1-a855f7)

> This repository is managed by [SkillForge](http://localhost:3000) — do not edit by hand.

---

## 🚀 Installation

### Claude Code (CLI)

```
/plugin marketplace add Spegeli/skillforge-marketplace
```

### Claude Desktop App

```
https://github.com/Spegeli/skillforge-marketplace
```

In the app: **Customize → + Create plugin → Add marketplace → "Add from a repository"**, then paste this URL.

---

## 📦 Collections (2)

### [Audit / Review](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review) — 12 Skills

_A Collection of Skills for Audit / Review Websites_

**Install this collection**
- **CLI:** `/plugin install audit-review@skillforge-spegeli`
- **Desktop App:** Go to **Settings → Extensions**, search for `skillforge-spegeli` and install **audit-review**.

<details>
<summary>Show 12 skills</summary>

| Skill | Description |
|---|---|
| [`a11y-audit`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/a11y-audit) | Accessibility audit skill for scanning, fixing, and verifying WCAG 2.2 Level A and AA compliance across React, Next.js, Vue, Angular, Svelte, and plain HTML codebases. Use when auditing accessibility, fixing a11y violations, checking color contrast, generating compliance reports, or integrating accessibility checks into CI/CD pipelines. |
| [`aeo`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/aeo) | Answer Engine Optimization (AEO) skill — optimize content to be cited by AI language models (ChatGPT, Perplexity, Claude, Gemini, Mistral) as authoritative sources. Distinct from SEO — AEO optimizes for citation in LLM-generated responses, not search rankings. Use when planning content for AI-first search audiences, auditing existing content for E-E-A-T signals, tracking which pages get cited by which LLMs, or building a citation-friendly content strategy. Triggers — 'AEO audit', 'optimize for ChatGPT', 'get cited by Perplexity', 'LLM citation strategy', 'answer engine optimization', 'content for AI search', 'E-E-A-T audit'. Output is a markdown audit report (default) or JSON for pipeline integration. Stdlib-only Python tools. |
| [`ai-seo`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/ai-seo) | Optimize content to get cited by AI search engines — ChatGPT, Perplexity, Google AI Overviews, Claude, Gemini, Copilot. Use when you want your content to appear in AI-generated answers, not just ranked in blue links. Triggers: 'optimize for AI search', 'get cited by ChatGPT', 'AI Overviews', 'Perplexity citations', 'AI SEO', 'generative search', 'LLM visibility', 'GEO' (generative engine optimization). NOT for traditional SEO ranking (use seo-audit). NOT for content creation (use content-production). |
| [`api-design-reviewer`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/api-design-reviewer) | Comprehensive REST API design review with automated linting, breaking-change detection, and design scorecards. Catches inconsistent conventions, missing versioning, and design smells before APIs ship. Use when reviewing a PR that adds or changes API endpoints, auditing an existing API for v2 migration, or establishing API standards for a team. |
| [`code-reviewer`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/code-reviewer) | Code review automation for TypeScript, JavaScript, Python, Go, Swift, Kotlin, C\#, .NET, Java, C, C++, Rust, Ruby, PHP, and Dart/Flutter. Analyzes PRs for complexity and risk, checks code quality for SOLID violations and code smells, generates review reports. Use when reviewing pull requests, analyzing code quality, identifying issues, generating review checklists. |
| [`design-audit`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/design-audit) | Premium UI/UX design audit and refinement skill. Conducts systematic visual audits of existing apps and produces phased, implementation-ready design plans. Use this skill whenever the user asks to audit a UI, improve an app's visual design, make an interface feel more polished or premium, review design consistency, fix visual hierarchy, or refine spacing/typography/color. Also trigger when the user says "design review", "make it look better", "UI polish", "visual refinement", "design pass", "audit the design", or references making an app feel more professional. This skill is purely visual — it does not touch functionality, logic, or features. It elevates what exists. |
| [`react-performance`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/react-performance) | React and Next.js performance optimization patterns adapted from Vercel Engineering's React Best Practices (https://github.com/vercel-labs/agent-skills). Organizes 70+ rules across 8 priority categories — waterfalls, bundle size, server-side, client fetching, re-render, rendering, JS micro-perf, advanced. Use when writing, reviewing, or refactoring React/Next.js code for performance. |
| [`security-pen-testing`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/security-pen-testing) | Use when the user asks to perform security audits, penetration testing, vulnerability scanning, OWASP Top 10 checks, or offensive security assessments. Covers static analysis, dependency scanning, secret detection, API security testing, and pen test report generation. |
| [`senior-fullstack`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/senior-fullstack) | Fullstack development toolkit with project scaffolding for Next.js, FastAPI, MERN, and Django stacks, code quality analysis with security and complexity scoring, and stack selection guidance. Use when the user asks to "scaffold a new project", "create a Next.js app", "set up FastAPI with React", "analyze code quality", "audit my codebase", "what stack should I use", "generate project boilerplate", or mentions fullstack development, project setup, or tech stack comparison. |
| [`seo-audit`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/seo-audit) | When the user wants to audit, review, or diagnose SEO issues on their site. Also use when the user mentions "SEO audit," "technical SEO," "why am I not ranking," "SEO issues," "on-page SEO," "meta tags review," or "SEO health check." For building pages at scale to target keywords, see programmatic-seo. For adding structured data, see schema-markup. |
| [`site-architecture`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/site-architecture) | When the user wants to audit, redesign, or plan their website's structure, URL hierarchy, navigation design, or internal linking strategy. Use when the user mentions 'site architecture,' 'URL structure,' 'internal links,' 'site navigation,' 'breadcrumbs,' 'topic clusters,' 'hub pages,' 'orphan pages,' 'silo structure,' 'information architecture,' or 'website reorganization.' Also use when someone has SEO problems and the root cause is structural (not content or schema). NOT for content strategy decisions about what to write (use content-strategy) or for schema markup (use schema-markup). |
| [`web-design-guidelines`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/audit-review/skills/web-design-guidelines) | Review UI code for Web Interface Guidelines compliance. Use when asked to "review my UI", "check accessibility", "audit design", "review UX", or "check my site against best practices". |

</details>

---

### [Test](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/test) — 1 Skill · 1 Agent

_Test Collection_

**Install this collection**
- **CLI:** `/plugin install test@skillforge-spegeli`
- **Desktop App:** Go to **Settings → Extensions**, search for `skillforge-spegeli` and install **test**.

<details>
<summary>Show 1 skill</summary>

| Skill | Description |
|---|---|
| [`config-gc`](https://github.com/Spegeli/skillforge-marketplace/tree/main/plugins/test/skills/config-gc) | Garbage collection for your Claude Code configuration. Periodically scans ~/.claude (skills, memory, hooks, permissions, MCP servers, caches) for redundant, stale, orphaned, or low-value items, then walks the user through a confirm-each-deletion cleanup. Use when the user says "clean up my config", "config GC", "too many skills", "audit my setup", "my .claude is bloated", or asks for a periodic config review. |

</details>

<details>
<summary>Show 1 agent</summary>

| Agent | Description |
|---|---|
| [`enrichment-agent`](https://github.com/Spegeli/skillforge-marketplace/blob/main/plugins/test/agents/enrichment-agent.md) | Pulls detailed profile, company, and activity data for qualified leads. Enriches prospects with recent news, funding data, content interests, and mutual overlap. |

</details>

---

## ⚖️ Disclaimer & Credits

The skills and agents in this marketplace were **scanned and aggregated** by SkillForge.
Neither SkillForge nor the owner of this repository (`Spegeli`) is necessarily the original author of the bundled artifacts. **All credit belongs to the respective original authors.**

These artifacts are provided **"as is", without warranty of any kind**. Neither SkillForge nor the repository owner is liable for any damage, defect, data loss, or malfunction arising from their use. **Use at your own risk.**

---

_Last published: 2026-06-11 · [SkillForge](http://localhost:3000)_
