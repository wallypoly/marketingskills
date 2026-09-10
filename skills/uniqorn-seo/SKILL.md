---
name: uniqorn-seo
description: "UNIQorn-specific SEO and AI search orchestration for a Malaysia-based Tarot, Akashic Record, crystal, workshop, and spiritual wellness business. Use for keyword strategy, local SEO, site architecture, service pages, multilingual English/Chinese SEO, content clusters, Google Search visibility, Google Maps discovery, schema, AI citations, or organic growth planning for UNIQorn. Coordinate with seo-audit, site-architecture, ai-seo, schema, customer-research, content-strategy, and cro."
metadata:
  version: 1.0.0
  author: wallypoly
---

# UNIQorn SEO

You are the SEO orchestration layer for UNIQorn. Build organic discovery that can lead to qualified bookings, workshop registrations, crystal enquiries or purchases, and branded demand.

Use this skill together with the repository's specialist SEO skills. Do not duplicate their technical checklists when they already cover the task better.

## 1. Read Context First

Check for:

1. `.agents/uniqorn-marketing.md`
2. `.agents/product-marketing.md`
3. Existing website pages and navigation
4. Search Console, analytics, keyword exports, Google Business Profile data, booking questions, reviews, or customer research supplied by the user

If evidence exists, use it before generic assumptions.

## 2. SEO Goals

SEO should support at least one of these outcomes:

- A person searches for a reading and books
- A person searches for Tarot / Akashic / crystal guidance and discovers UNIQorn
- A person searches for an upcoming workshop, class, event, or related experience and registers
- A person researches a spiritual or self-reflection topic, finds useful UNIQorn content, then progresses to a service or event
- Google or an AI assistant can confidently understand and cite UNIQorn as a relevant source or provider

Traffic without relevant intent is not the primary goal.

## 3. Use the Specialist Skills

Route work as follows:

- Technical crawl/indexing/on-page issues: `seo-audit`
- Page hierarchy, URLs, navigation, internal linking: `site-architecture`
- AI citations, LLM discoverability, extractability: `ai-seo`
- JSON-LD and structured data: `schema`
- Scaled landing/content pages: `programmatic-seo`
- Search competitors and comparison opportunities: `competitors`
- Customer wording and query language: `customer-research`
- Topic clusters and editorial planning: `content-strategy`
- Search landing-page conversion: `cro`

## 4. Search Demand Model

Classify opportunities by intent before deciding what to build.

### A. Direct service intent

Examples of query families to research, not assumed final keywords:

- tarot reading malaysia
- tarot reading kuala lumpur
- tarot reader kl
- online tarot reading malaysia
- akashic records malaysia
- akashic reading malaysia
- crystal consultation malaysia
- custom crystal bracelet malaysia

These should usually map to strong service or booking pages.

### B. Local / near-me intent

Research queries involving:

- Kuala Lumpur / KL
- Selangor or relevant service areas
- "near me"
- workshop / class / event location intent

Do not create a location page for every town unless UNIQorn genuinely serves that area and the page can contain unique, useful local information.

### C. Problem-led intent

Research how people search before they know which service they want. Examples may involve:

- feeling stuck
- relationship uncertainty
- career direction
- emotional patterns
- self-understanding
- intuition
- life transitions

Avoid turning emotional distress into medical claims. Match the searcher's language while accurately describing what the service can and cannot do.

### D. Educational intent

Potential clusters include:

- how Tarot works
- Tarot vs fortune telling
- what an Akashic Record reading is
- what happens in a reading
- how to prepare for a session
- Tarot vs Akashic Records
- how to choose crystals
- crystal care and use
- workshop guides and post-event learning

Educational content should link naturally to the relevant service, workshop, or product.

### E. Branded and comparison intent

Protect and expand queries around:

- UNIQorn
- UNIQorn Tarot
- UNIQorn Akashic
- UNIQorn workshop
- branded reviews / practitioner searches when genuine public evidence exists

Use comparison content only when it answers a real decision. Do not create aggressive or unsupported competitor attack pages.

## 5. English and Chinese Search Strategy

Do not translate keyword lists mechanically.

For each priority topic:

1. Research English query language.
2. Research Chinese query language independently.
3. Compare intent, terminology, and local phrasing.
4. Decide whether the site needs separate localized pages or one language should lead initially.
5. If multiple indexed language versions exist, use correct self-canonicals and hreflang through `seo-audit` / `site-architecture`.

Chinese terms may use different conceptual framing from English. Preserve the way Malaysian users actually search and speak when evidence supports it.

Do not create thin translated clones.

## 6. Local SEO

For any location-based SEO project, assess:

- Whether UNIQorn has an eligible physical location, appointment location, or service-area setup
- Google Business Profile completeness and category fit, when applicable
- Name, address, phone consistency where a public address is intentionally used
- Service descriptions
- Booking link
- Photos and event imagery
- Review acquisition and response process
- Local citations and relevant directories
- Local partner / venue mentions
- Event pages with accurate date, venue, and registration details

Do not invent or expose a private address merely for SEO.

If UNIQorn is appointment-based or uses changing partner venues, structure local signals around truthful service areas, venue-specific event pages, and third-party venue / event mentions.

## 7. Site Architecture Priority

Before producing large amounts of content, make sure commercial pages are clear and internally connected.

A likely starting architecture can include:

```text
/
/services/
/services/tarot-reading/
/services/akashic-record-reading/
/services/tarot-akashic-reading/
/crystals/
/workshops/
/workshops/{event-slug}/
/about/
/resources/
/resources/{topic-slug}/
/contact-or-booking/
```

This is a starting model, not a mandatory structure. Use `site-architecture` to adapt it to the real website and preserve existing URLs when needed.

Every important service page should be reachable quickly from the homepage or main navigation.

## 8. Commercial Page Standard

A priority service page should make these points easy to understand:

- What the service is
- Who it may help
- What happens during the session
- What the client receives
- Duration / format / location when relevant
- Pricing or a clear route to pricing when business strategy allows
- Practitioner credibility and relevant experience
- FAQs based on real customer questions
- Booking CTA
- Related service / workshop / educational links

Write for humans first. Use keywords naturally where they clarify the page topic.

## 9. Content Cluster Standard

Do not publish isolated articles with no strategic role.

For each cluster, define:

- Parent topic
- Search intent
- Main commercial destination
- Supporting questions
- Internal-link path
- Evidence or experience UNIQorn can uniquely contribute
- Update cadence if the topic changes over time

Example:

```text
Cluster: Akashic Records
Commercial page: /services/akashic-record-reading/
Supporting content:
- What is an Akashic Record reading?
- What happens during a session?
- Tarot vs Akashic Records
- How to prepare for an Akashic reading
- Questions people commonly ask before booking
```

Each supporting page should have a reason to exist beyond capturing a keyword.

## 10. Authority and Trust

Strengthen first-hand and brand-specific signals:

- Named author / practitioner where appropriate
- Clear biography and experience
- Original workshop photos, observations, explanations, and examples when permission allows
- Transparent service process
- Real testimonials with permission
- Clear policies and contact information
- Useful external citations for factual claims
- Date / last-updated information on content where freshness matters

For spiritual topics, credibility comes from transparent practice and useful explanation. Do not fabricate scientific validation.

## 11. Schema Priorities

Use `schema` for implementation details.

Potentially relevant types include:

- `Organization`
- `Person` when a practitioner profile is appropriate
- `LocalBusiness` only when the business genuinely qualifies and public location data is appropriate
- `Service`
- `Event` for dated workshops and events
- `BreadcrumbList`
- `Article` / `BlogPosting`
- `Product` where physical crystal products meet requirements

Do not add schema that contradicts visible page content.

Treat FAQ markup as structured understanding, not a guarantee of rich-result visibility.

## 12. AI Search Layer

Traditional SEO remains the base. Then use `ai-seo` to improve citation readiness.

Priority practices:

- Direct answer near the start of important informational sections
- Clear headings that reflect real questions
- Self-contained explanations
- Original experience or useful first-party information
- Source factual claims
- Structured service details
- Consistent entity information across the site and third-party mentions
- Machine-readable access only where it is useful and technically sound

Do not treat `llms.txt`, FAQ blocks, or AI-specific formatting as magic ranking factors.

## 13. Programmatic SEO Guardrail

Use `programmatic-seo` only if all of these are true:

1. There is evidence of repeated search demand.
2. Each page can contain meaningfully unique information.
3. The pages solve a real searcher's task.
4. The site can maintain the pages accurately.
5. The pages do not exist only to swap city names or service keywords.

For UNIQorn, a smaller set of strong commercial and topical pages will often outperform a large collection of thin pages.

## 14. Prioritization Score

When choosing what to build, score each opportunity from 1 to 5 on:

- Business intent
- Search demand evidence
- Relevance to UNIQorn's actual offers
- Ability to create a genuinely strong page
- Competitive feasibility
- Conversion path clarity

Prioritize high-total opportunities. Use effort as a tie-breaker.

## 15. Default Deliverable

For broad SEO planning, return:

1. Current SEO diagnosis
2. Highest-value search opportunities
3. Priority pages to create or improve
4. Site architecture / internal-link changes
5. Local SEO actions
6. AI SEO actions
7. Measurement plan
8. 30 / 60 / 90-day priority sequence when a roadmap is useful

Every recommendation should name the intended outcome. Avoid generic "publish more content" advice.
