# Product

## Register

brand

## Users

People carrying a repetitive inner criticism (an old boss's line, a parent's verdict, the cringe loop) who want a private, non-clinical daily practice to quiet it. They arrive from the App Store listing, a friend's link, or a social post: skeptical of wellness fluff, protective of their inner life, often browsing on a phone in the evening. The job: understand what the practice is, feel that it is safe and serious, and decide to download.

## Product Purpose

Marketing and legal home for the NeuroRewire app, a free daily practice for rewiring negative self-talk (5-phase session: choose, breathe, rewire with bilateral stimulation, evidence, done). The site must convey the mechanic in seconds, carry the privacy promise credibly (zero data collection is verifiable: the site itself has no scripts or trackers), and host the store-required privacy/terms/disclaimer pages. Success: a visitor feels understood and installs the app; a store reviewer finds every legal page.

## Brand Personality

Calm, warm, literary. A quiet evening ritual in type: dusk-to-dawn color, serif voice, unhurried pacing. Confident without selling hard; the tone of a good hardcover, not a pitch deck. (Confirmed by Melissa 2026-07-15.)

## Anti-references

- Generic SaaS landing pages: gradient CTA buttons, icon card grids, fake testimonials, "trusted by" logos, hero-metric templates.
- Clinical or medical presentation: nothing that reads as a healthcare provider, therapy service, or claims to treat anything (this is also a legal requirement; see the app repo's CLAUDE.md law on medical claims).
- Grounded, not mystical: the practice is framed in memory-research terms, never crystals-and-chakras wellness aesthetics.

## Design Principles

1. **The page is a session.** The scroll mirrors the app's ritual: it begins in dusk and ends in dawn light, the way a session does. The site demonstrates the product's feeling rather than describing it.
2. **The mechanic lives in the type.** The product's core move (an old line struck through, a new line spoken over it) is typographic. Show it in the headline, not in an illustration.
3. **Privacy is a feature you can inspect.** The site carries zero scripts, zero cookies, zero external requests, and says so. The proof is view-source.
4. **Literary calm over conversion pressure.** No urgency, no popups, no countdown. One quiet invitation to download, made twice at most.
5. **Identity preservation.** Palette, serif voice, and motion timings come from the app's design tokens (app repo `docs/design-tokens.md`). The site never invents a second brand.

## Accessibility & Inclusion

- Honor `prefers-reduced-motion`: the breathing-orb ambience and reveal animations become static.
- Contrast: ink-on-dusk and doneInk-on-light pairings must hold WCAG AA for body text; dim text reserved for large or secondary copy.
- Semantic landmarks and alt text written in the brand voice; the site must read well in a screen reader as a narrative.
- System font stacks only (no font CDNs), which also upholds the no-external-requests promise.
