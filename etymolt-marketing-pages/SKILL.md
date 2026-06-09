# etymolt-marketing-pages

> Composition patterns and SEO conventions for Etymolt marketing surfaces.

## When to use this skill

- Authoring a new landing page on etymolt.com.
- Composing a /vs/, /verify/, or /content/ page.
- Setting up SEO metadata, Open Graph tags, or `llms.txt` entries for a new page.

## The PublicPage.Root composition pattern

```tsx
<PublicPage.Root>
  <PublicPage.Hero>
    <Hero1Liner>The fact-check layer for LLM-generated names.</Hero1Liner>
    <HeroVerifyAffordance />  {/* the interactive verify input */}
  </PublicPage.Hero>

  <PublicPage.Section title="What we issue">
    {/* the 5 axes table */}
  </PublicPage.Section>

  <PublicPage.Section title="Bureau Model">
    {/* the verbatim disclaimer + framing */}
  </PublicPage.Section>

  <PublicPage.Footer>
    <BureauFooter />  {/* R12 cardinal rule */}
  </PublicPage.Footer>
</PublicPage.Root>
```

## SEO + OG metadata format

Every public page MUST set:

- `<title>` — ends with " · Etymolt".
- `<meta name="description">` — ≤155 chars, ends with the locked tagline if there's room.
- `<link rel="canonical">` — always the etymolt.com URL.
- `og:title`, `og:description`, `og:image` (1200×630), `og:url`, `og:type`.
- `twitter:card="summary_large_image"`.

## llms.txt + llms-full.txt

Every new docs page MUST be added to the docs `llms.txt` index. Every new article MUST be reachable via the canonical `/<slug>.md` sibling URL.

## Apply at code-write time

If you're an agent authoring a marketing page, use this composition skill rather than inventing a parallel layout. Consistency across surfaces is what makes Etymolt read as a brand, not a side project.
