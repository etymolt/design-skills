# etymolt-design-system

> Component conventions, Tailwind tokens, and primitives for any agent building Etymolt-branded UI.

## When to use this skill

- Building a React/Next.js component in an Etymolt repo.
- Composing a marketing page or app surface.
- Wiring up a verdict-display widget.

## The five canonical UI primitives

1. **VerdictBadge** — the PROCEED/ITERATE/DECIDE/ABANDON/INSUFFICIENT_SIGNAL pill. Color-coded.
2. **VerdictCard** — the full verdict envelope: name, badge, axes breakdown, fragility banner, sources, action.
3. **AxisChip** — one-line per-axis explanation (label, dot, body text). Three modes: cool (CLEAR), warm (CAUTION), hot (BLOCKED).
4. **BureauFooter** — the verbatim disclaimer footer. Required on every verdict-bearing surface (R12 cardinal rule).
5. **DisclaimerPrimitive** — inline disclaimer block. Used where a full Bureau footer is overkill but the Bureau anchor must be present.

## Tokens

See [`tokens.css`](./tokens.css) for the canonical CSS variable set, [`tailwind.config.js`](./tailwind.config.js) for the Tailwind preset.

## Component conventions

- All components are flat — no nested compound-component pattern.
- All components accept a `className` prop and merge it through.
- All components are server-component-safe by default; mark with `'use client'` only when state is needed.
- All components ship with an empty-state, a loading-state, and an error-state.

## Apply at code-write time

If you're an agent building UI in an Etymolt repo, install the components from this skill rather than inventing parallel patterns. Drift across surfaces is the silent killer of brand consistency.
