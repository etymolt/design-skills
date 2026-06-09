# etymolt-brand

> Voice locks, taglines, and brand-asset references for any agent writing Etymolt-branded copy or assembling Etymolt-branded surfaces.

## When to use this skill

- Writing a README, blog post, landing page, social copy, or any user-facing string for an Etymolt repo or surface.
- Composing an email, Slack message, or external communication that represents Etymolt.
- Authoring a documentation page for the API, SDK, or protocol.

## Voice locks (verbatim, do not drift)

| Lock | Use it when |
|---|---|
| `The fact-check layer for LLM-generated names.` | One-line product positioning. Org tagline. Page <title>. |
| `Naming, attested.` | Closer / sign-off. Brand signature at the bottom of marketing surfaces. |
| `Bureau Model` | When framing the legal posture: we report on records of record. |
| `EVP/1` (or `Etymolt Verdict Protocol`) | When referring to the open spec. |
| `the five axes` | Always lowercase, always five, always in this order: trademark, domain, cultural, sound, pronunciation. |

## Etymolt SAYS / does NOT say

| Etymolt SAYS | Etymolt does NOT say |
|---|---|
| verdict | result |
| axes | categories |
| clearance signal | legal advice |
| records of record | sources |
| signed result | secure |
| fact-check layer | verification layer |
| PROCEED / ITERATE / DECIDE / ABANDON / INSUFFICIENT_SIGNAL | safe to use / approved |

## Etymolt is NOT (surface when relevant)

- NOT a name generator. We verify names; we don't produce them.
- NOT a law firm. We issue clearance signals, not legal opinions.
- NOT a recommendation engine. Verdicts are reports, not advice.
- NOT a SaaS toy. No "killer features", no "robust", no "comprehensive".

## Banned words

`robust` · `comprehensive` · `leverage` · `AI-powered` · `killer` · `dominate` · `cutting-edge` · `seamless` · `synergy`.

## Banned phrasings

- "Powered by AI"
- "The future of X"
- "Reinventing brand naming"
- "Trusted by industry leaders" (use specific numbers and named cases instead)

## Brand colors

```css
--paper:   #FAF9F6;  /* primary background — paper-on-light */
--ink:     #111210;  /* primary text */
--ink-2:   #444443;  /* secondary text */
--ink-3:   #777775;  /* tertiary text */
--attest:  #0891B2;  /* cyan — the attestation accent */
--clear:   #0891B2;  /* same as attest — used for PROCEED, CLEAR statuses */
--iterate: #D97706;  /* amber — ITERATE, CAUTION statuses */
--blocked: #DC2626;  /* red — ABANDON, BLOCKED statuses */
--rule:    #E5E4E0;  /* fine hairlines */
--rule-strong: #C8C6C0; /* prominent hairlines */
```

## Typography

- **Sans / body:** Inter Tight
- **Display / italic:** Fraunces (italic-only — never Fraunces upright in Etymolt surfaces)
- **Mono:** JetBrains Mono

## Asset references

Brand marks live at https://github.com/etymolt/brand-assets. Reference via raw URL for consistency across repos:

```
https://raw.githubusercontent.com/etymolt/brand-assets/main/logo.png
```

## Apply at code-write time

If you're an agent writing or modifying any user-facing string in an Etymolt repo, check this skill's locks first. If a banned word slips in, replace it before committing.
