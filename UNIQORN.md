# UNIQorn Marketing Skills

This fork keeps the original `coreyhaines31/marketingskills` library intact and adds a thin UNIQorn-specific orchestration layer on top.

The goal is to preserve upstream updates while making the library work better for a Malaysia-based Tarot, Akashic Record, crystal, workshop, and spiritual wellness business.

## Fork-specific skills

### `uniqorn-marketing-os`

The main router for UNIQorn marketing work. It decides which specialist marketing skills to combine and prevents generic SaaS assumptions from dominating local service, workshop, content, and spiritual wellness decisions.

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

It adds specific guardrails for Malaysian local search, English / Chinese search behavior, service-intent pages, workshop / event discovery, spiritual-wellness claims, and AI search.

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

If installing from inside an agent session, pass the agent explicitly when needed, for example:

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

Keep business-specific context in the UNIQorn project rather than hard-coding private operational information into this public skills repository.

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
```

Do not run every skill mechanically. The router should select only the capabilities needed for the task.

## SEO principle

SEO is a core acquisition system for UNIQorn.

Prioritize:

1. Commercial service pages
2. Local discovery
3. Clear site architecture and internal links
4. Search-intent content clusters
5. Technical SEO and structured data
6. AI search / citation readiness
7. Scaled SEO pages only when demand and uniqueness justify them

The goal is qualified discovery and conversion, not publishing volume for its own sake.

## Keeping the fork maintainable

The original skills remain unchanged whenever possible. Fork-specific behavior lives in new files so upstream changes can still be pulled with fewer conflicts.

When upstream adds or improves a specialist skill, update the routing in `uniqorn-marketing-os` or `uniqorn-seo` only when necessary.
