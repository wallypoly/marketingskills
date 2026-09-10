# UNIQorn Marketing Skills

This fork keeps the original `coreyhaines31/marketingskills` library intact and adds a thin UNIQorn-specific orchestration layer on top.

The goal is to preserve upstream updates while making the library work better for a Malaysia-based Tarot, Akashic Record, crystal, workshop, spiritual, self-discovery, and experience-led business that is still refining its market fit.

## Core principle

UNIQorn's positioning is allowed to evolve.

The fork does not pre-decide that the brand should sound more mainstream, less mystical, more therapeutic, less spiritual, more premium, or more commercial. Those are market-fit variables to research, test, measure, and refine.

Language such as Tarot, Akashic Records, energy, manifestation, intuition, healing, universe, spiritual awakening, self-discovery, or emotional awareness should not be removed merely because it sounds niche or mystical. The agent should study how people actually search, respond, enquire, book, buy, return, and refer.

## Fork-specific skills

### `uniqorn-marketing-os`

The main router for UNIQorn marketing work. It decides which specialist marketing skills to combine and keeps recommendations grounded in current evidence and ongoing market-fit learning.

Use it for:

- Brand / positioning decisions
- Customer research
- SEO and website growth
- Content strategy
- Offers and pricing
- Website CRO
- Ads and creative
- Workshops and event marketing
- Analytics and attribution
- Market-fit experiments

### `uniqorn-seo`

The SEO orchestration layer for UNIQorn.

It coordinates:

- `seo-audit`
- `site-architecture`
- `ai-seo`
- `schema`
- `programmatic-seo`
- `competitors`
- `customer-research`
- `content-strategy`
- `cro`

It adds Malaysia local search, English / Chinese search behavior, service and event discovery, spiritual-category search, AI search, content clusters, and market-fit testing.

## Recommended install

Install the UNIQorn router and the specialist skills it depends on:

```bash
npx skills add wallypoly/marketingskills --skill \
  uniqorn-marketing-os \
  uniqorn-seo \
  product-marketing \
  customer-research \
  competitor-profiling \
  seo-audit \
  ai-seo \
  site-architecture \
  schema \
  programmatic-seo \
  competitors \
  content-strategy \
  copywriting \
  copy-editing \
  cro \
  offers \
  pricing \
  marketing-psychology \
  social \
  events \
  ads \
  ad-creative \
  analytics \
  attribution \
  lead-magnets \
  free-tools \
  referrals
```

To see everything available:

```bash
npx skills add wallypoly/marketingskills --list
```

If installing from inside an agent session, pass the agent explicitly when needed:

```bash
npx skills add wallypoly/marketingskills -a codex
```

or:

```bash
npx skills add wallypoly/marketingskills -a claude-code
```

## Recommended project context

Inside the actual UNIQorn website / business project, create:

```text
.agents/uniqorn-marketing.md
```

Start from:

```text
skills/uniqorn-marketing-os/references/context-template.md
```

Keep business-specific context in the actual UNIQorn project rather than hard-coding private operating information into this public skills repository.

## Suggested workflow

For broad UNIQorn growth work:

```text
uniqorn-marketing-os
  -> product-marketing / customer-research
  -> uniqorn-seo
       -> seo-audit
       -> site-architecture
       -> ai-seo
       -> schema
  -> offers / pricing
  -> cro
  -> content-strategy / social / events / ads
  -> analytics / attribution
  -> feed market learning back into context
```

Do not run every skill mechanically. The router should select only the capabilities needed for the task.

## SEO principle

SEO is a core acquisition and market-learning system for UNIQorn.

Possible priorities include:

1. Commercial service discovery
2. Local discovery
3. Clear site architecture and internal links
4. Search-intent content clusters
5. Technical SEO and structured data
6. AI search / citation readiness
7. Spiritual and self-discovery topic demand
8. English / Chinese search behavior
9. Market-fit experiments across different positioning language
10. Scaled SEO pages when demand and page quality justify them

The goal is to learn what the market responds to while building qualified discovery and conversion.

## Keeping the fork maintainable

The original skills remain unchanged whenever possible. Fork-specific behavior lives in new files so upstream changes can still be pulled with fewer conflicts.

When upstream adds or improves a specialist skill, update the routing in `uniqorn-marketing-os` or `uniqorn-seo` only when necessary.
