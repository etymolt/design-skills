# Etymolt design-skills

> Etymolt's brand, design tokens, voice locks, and UI primitives — packaged as installable agent skills. Inspired by [resend/design-skills](https://github.com/resend/design-skills).

[![License: CC-BY-4.0](https://img.shields.io/badge/license-CC--BY--4.0-blue.svg)](./LICENSE)
[![npx skills](https://img.shields.io/badge/install-npx%20skills%20add%20etymolt%2Fdesign--skills-black.svg)](#install)

## What this is

Three things, packaged as skills you install once and any compatible coding agent picks up automatically:

```
.
├── etymolt-brand/
│   ├── SKILL.md           # voice locks, taglines, what we are / are NOT
│   ├── colors.md          # the paper-on-light palette + cyan attestation
│   ├── typography.md      # Inter Tight, Fraunces italic, JetBrains Mono
│   └── marks/             # SVG logos, light + dark variants
├── etymolt-design-system/
│   ├── SKILL.md           # component conventions
│   ├── tokens.css         # CSS variables
│   ├── tailwind.config.js # Tailwind preset
│   └── components/        # paste-ready component snippets
└── etymolt-marketing-pages/
    ├── SKILL.md           # page-composition recipes
    ├── PublicPage.tsx     # the composition pattern
    └── seo.md             # canonical SEO + OG metadata format
```

## Install

For [Anthropic Agent Skills](https://docs.anthropic.com/en/docs/agents/skills) — Claude Code, Claude Desktop, or any AGENTS.md-aware tool:

```bash
npx skills add etymolt/design-skills
```

The skill installer drops `etymolt-brand`, `etymolt-design-system`, and `etymolt-marketing-pages` into your repo's `.claude/skills/` directory. Compatible agents see them automatically.

## What each skill does

### `etymolt-brand`

The voice + brand asset bundle. When an agent is writing copy, the skill ensures:

- Tagline locked: *"The fact-check layer for LLM-generated names."*
- Closer locked: *"Naming, attested."*
- Three load-bearing concepts surfaced: Bureau Model · EVP/1 · the five axes
- No "robust", "comprehensive", "leverage", "AI-powered" — drift-blocked
- "verdict" not "result"; "axes" not "categories"; "clearance signal" not "legal advice"
- "Etymolt is NOT a name generator. Etymolt is NOT a law firm." surfaced when relevant

### `etymolt-design-system`

Tailwind tokens + component conventions. When an agent is building UI:

- Colors: paper `#FAF9F6`, ink `#111210`, attest cyan `#0891B2`, blocked red `#DC2626`, iterate amber `#D97706`, clear `#0891B2`.
- Type: Inter Tight (sans), Fraunces italic (display), JetBrains Mono (mono).
- Spacing: 4px base unit, 1.5× rhythm.
- Component primitives: VerdictCard, VerdictBadge, AxisChip, BureauFooter, DisclaimerPrimitive.

### `etymolt-marketing-pages`

Composition recipes for landing-page-style surfaces. The PublicPage.Root composition pattern + canonical SEO + OG metadata format.

## Why a skill, not a docs page

A docs page asks the human to remember to read it. A skill asks the agent to apply it at code-write time. Brand consistency that depends on memory drifts; brand consistency that's enforced by the toolchain holds.

## Roadmap

- [ ] `etymolt-verdict-renderer/` — the React component pattern for rendering an EVP/1 verdict on any consumer surface (the "as of" badge, the staleness banner, the per-axis breakdown).
- [ ] `etymolt-mcp-author/` — the recipe for authoring a new MCP server in the Etymolt house style.
- [ ] `etymolt-evp-author/` — the recipe for authoring a new EVP proposal against the protocol spec.

## License

[CC-BY-4.0](./LICENSE) for the design tokens, voice guidelines, and composition patterns. Trademarks (the Etymolt name and logo marks) are not licensed under CC-BY-4.0.

## Contact

`hello@etymolt.com`

## Naming, attested.
