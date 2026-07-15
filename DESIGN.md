# Design

Visual system for the NeuroRewire site. Derived from the app's canonical tokens (app repo `docs/design-tokens.md`); the app is the reference, the site inherits.

## Theme

Drenched: the surface IS the app's dusk-to-dawn gradient. The page scrolls through the session's phases: near-black dusk (#131024 → #181430), rewire violet (#2c2260 → #4a3670), evidence dawn (#5a3d6e → #b06a5f), done light (#c97f63 → #f0c9a2). Text is warm ink (#f5eede) on dark phases and flips to doneInk (#3a2418) on the light footer phase. Never pure black or white.

## Color

- dusk1 #181430, dusk2 #241d4e, mid1 #2c2260, mid2 #4a3670, dawn1 #5a3d6e, dawn2 #b06a5f, light1 #c97f63, light2 #f0c9a2, chooseTop #131024
- ink #f5eede (dim = 65% alpha), doneInk #3a2418 (dim = 65%)
- peach #e8a87c (accent, CTAs, the strike-through color), onPeach #2a1a10
- sage #9bd4c0 (evidence/privacy accents), sageDark #3d6e5c on light
- hairlines: ink at 16%; input/panel fills: black at 18%, white at 6%

## Typography

- Display/serif voice: `"Iowan Old Style", Georgia, "Times New Roman", serif` (system stacks only; no font CDNs, ever). Matches the app's serif display.
- Body: system sans stack.
- Fluid display sizes via clamp(); scale ratio ≥ 1.3. Body max 68ch.
- The signature move: an italic, peach-struck old line followed by a large upright serif replacement line.

## Motion

- Breathing-orb ambience: slow radial pulse, 10 to 14 s cycle, ease-in-out, subtle scale only.
- Entrance: single staggered fade-up on the hero lines (0.7 s, ease-out quart). Nothing else animates on scroll.
- All motion disabled under `prefers-reduced-motion`.

## Components

- Buttons: pill (999px radius); primary = peach fill with onPeach text; quiet links are underlined ink-dim.
- Device frames: dark bezel (#0c0a18, ~12px padding, outer radius 52 / inner 40, hairline border) around real app screenshots.
- Rules: 1px full-width hairlines for section rhythm. Side-stripe accents, gradient text, and glassmorphism are banned.
- Cards only where genuinely needed; the five-step journey is an open list with a progress-segment rail, not a card grid.
