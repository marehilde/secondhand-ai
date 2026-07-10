---
name: Secondhand AI
description: An interactive explainer on the downstream effect of one person's AI use on everyone who receives, believes, and passes it on.
colors:
  clear-air: "#E9ECEA"
  smoke: "#22252B"
  ink: "#22252B"
  ink-secondary: "#4A4E4A"
  ink-muted: "#585C58"
  teal: "#5E8A86"
  deep-teal: "#3E6663"
  teal-on-dark: "#8FB0AB"
  pale-teal: "#C4D6D2"
  amber: "#C25A2B"
  dust: "#B79B6E"
  pale-dust: "#E7DDC8"
  warm-sand: "#E4D2AE"
  warm-white: "#F4EEE2"
  cream: "#F5EFE4"
  umber: "#3A2E20"
  terracotta: "#7A3A1E"
  pale-ink: "#F1F3F1"
typography:
  display:
    fontFamily: "Abril Fatface, Georgia, serif"
    fontSize: "clamp(2.5rem, 11vw, 8.75rem)"
    fontWeight: 400
    lineHeight: 0.95
    letterSpacing: "-0.01em"
  headline:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "clamp(1.5rem, 3.4vw, 3.25rem)"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Archivo, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 600
    lineHeight: 1.3
  body-emphasis:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "clamp(1.31rem, 2.8vw, 1.81rem)"
    fontWeight: 500
    lineHeight: 1.5
  body:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "Public Sans, system-ui, sans-serif"
    fontSize: "0.6875rem"
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: "0.2em"
rounded:
  pill: "100px"
  lg: "20px"
  md: "14px"
  sm: "12px"
  chip: "6px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "26px"
  lg: "44px"
  xl: "90px"
components:
  button-primary:
    backgroundColor: "{colors.deep-teal}"
    textColor: "{colors.warm-white}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  button-primary-hover:
    backgroundColor: "{colors.teal}"
  button-secondary:
    backgroundColor: "rgba(244,238,226,0.12)"
    textColor: "{colors.warm-white}"
    rounded: "{rounded.pill}"
    padding: "12px 24px"
  chip-stat:
    backgroundColor: "rgba(94,138,134,0.10)"
    textColor: "{colors.deep-teal}"
    rounded: "{rounded.pill}"
    padding: "6px 16px"
  card-solid:
    backgroundColor: "#FBFBFA"
    textColor: "{colors.ink}"
    rounded: "{rounded.md}"
    padding: "22px 24px"
  section-band-dark:
    backgroundColor: "{colors.umber}"
    textColor: "{colors.warm-white}"
    padding: "26px 24px"
  section-band-tint:
    backgroundColor: "{colors.pale-dust}"
    textColor: "{colors.ink}"
    padding: "26px 24px"
---

# Design System: Secondhand AI

## 1. Overview

**Creative North Star: "Ambient Haze"**

The whole system reads as clean, breathable air that a warm haze gradually creeps across — you only notice it when it thickens. The neutral **clear-air** ground is the default (calm, quiet, mostly empty of colour); **amber** is the heat that builds — urgency that accumulates rather than shouts; **teal** is the quiet recurring accent that carries the *beneficial* side of the story; and **dust** is the softer warm haze that ties the pages together. This directly serves the piece's argument: secondhand AI is two-sided (it can help and harm), its effects are invisible and hard to spot, and it carries a real urgency that is felt more than announced.

The signature moment is the **overview's scroll gradient**: the background begins as clear air and hazes into amber as the reader descends, so the urgency physically builds as the argument deepens. Elsewhere the same logic is expressed as flat coloured section bands (research pages) or a single quiet ground with colour carried in the type (the index, which also hosts the research paper-cards and the real-life examples gallery).

This is an editorial explainer, not a product: rigorous but approachable, warm and humane (it is about Alice and Bob, not about AI), quietly urgent rather than alarmist. It explicitly rejects the generic SaaS landing page (no hero-metric tiles, no gradient-clipped text, no eyebrow-on-every-section scaffolding), the paper-rendered-as-a-webpage look (research is staged as designed scenes and coloured bands, never pasted abstracts), and AI-panic clickbait (the two-sided help/harm framing stays measured — amber is warmth and urgency, never a red alarm).

**Key Characteristics:**
- Clear-air neutral is the default ground; colour is used sparingly and deliberately
- One warm accent story (amber = heat/urgency, dust = softer warm haze) plus teal as the single recurring accent on every page
- The overview's live scroll gradient hazes clear-air → amber as you descend
- Research pages are flat coloured section bands (one per part of the study), each built from exactly three colours
- Coloured bands meet at straight, flat edges; the surfaces are kept clean of decorative dividers and line art

## 2. Colors

A restrained, mostly-neutral palette: a clear-air ground carries most surfaces, teal is the single accent, and amber + dust supply warmth. Dark is used sparingly.

### Primary
- **Clear air** (`#E9ECEA`): the default light ground for the index and the top of the overview.
- **Amber** (`#C25A2B`): heat and urgency — the bottom of the overview's scroll gradient, the "harm" side of stat comparisons, and the one word that needs to burn ("in the wild"). Used sparingly.
- **Smoke** (`#22252B`): the primary dark — dark text on light grounds, and the occasional dark section band.

### Secondary — Teal (the accent)
- **Teal** (`#5E8A86`): accent fills — arrows, nav dots, benefit markers.
- **Deep teal** (`#3E6663`): teal as legible TEXT on light grounds — links, eyebrows, source tags, small labels, primary-button fill.
- **Teal on dark** (`#8FB0AB`): teal that must read against a dark or amber band (e.g. the research contents rail).
- **Pale teal** (`#C4D6D2`): a light teal tint — the index "01" chapter block, callout boxes.

### Tertiary — Warmth
- **Dust** (`#B79B6E`): the softer warm haze; connector lines and warm mid-tones.
- **Pale dust** (`#E7DDC8`): a warm light tint — the index "03" chapter block, research tint bands.
- **Warm sand** (`#E4D2AE`): a deeper warm tint used in research trios.
- **Umber** (`#3A2E20`) / **Terracotta** (`#7A3A1E`): warm darks — the dark section band in the warm research trios.

### Neutral
- **Warm white** (`#F4EEE2`) / **Cream** (`#F5EFE4`): near-white warm surfaces — research neutral bands, modal panels, card fills.
- **Ink** (`#22252B`): primary body text on light. **Ink secondary** (`#4A4E4A`): supporting copy. **Ink muted** (`#585C58`): captions, fine print — darkened from the original `#6B6F6A` so it clears AA (≥4.5:1) as small text directly on the clear-air / gradient grounds. Never seat small text lighter than this on the bare gradient; body copy over the amber end sits on a solid card or uses dark ink.
- **Design tokens:** the cross-cutting palette is defined once as CSS custom properties in a `:root` block on the index and overview (`--ink`, `--ink-2`, `--ink-muted`, `--teal`, `--teal-deep`, `--teal-pale`, `--clear-air`, `--amber`, `--warm-white`, `--card`) and referenced via `var()`. Page-specific band/trio colours remain literal (they belong to one page); DESIGN.md stays the source of truth for the full palette.
- **Pale ink** (`#F1F3F1`): primary text on dark / amber grounds.
- Card surface off-white: `#FBFBFA` (solid light cards floating on the gradient).

### Named Rules
**The One Teal Rule.** Teal (`#5E8A86` / `#3E6663` / `#8FB0AB`) is the only accent that appears on every page. It always carries links, navigation, and the *beneficial* side of the two-sided story. If a new accent is wanted, ask whether teal already does the job.
**The Amber-Is-Heat Rule.** Amber (`#C25A2B`) means urgency, heat, or the harm side — never decoration. Dust is the calm warmth; amber is the warmth that's rising. Keep amber rare so it still reads as heat.
**The Quiet-Ground Rule.** Clear air is the default. Colour is added deliberately (a chapter block, a coloured band, a stat) — never wall-to-wall. If a page feels colour-heavy, pull a surface back to clear air.

## 3. Typography

**Display / Wordmark Font:** Abril Fatface (with Georgia, serif fallback)
**Heading Font:** Archivo (with system-ui, sans-serif fallback)
**Body / Emphasis / Label / UI Font:** Public Sans (with system-ui, sans-serif fallback)

**Character:** A focused three-role system built to put the weight of attention on the title. **Abril Fatface** — a heavy, high-contrast Didone display — is used for one thing only: the "Secondhand AI" wordmark, where its dramatic thick/thin strokes make the title command the whole fold. **Archivo** — a confident grotesque built for headlines and data — carries every heading and study title with newsroom urgency and crisp legibility. **Public Sans** — a clean public-information sans — carries body copy, the emphasis/pull-quote paragraphs, labels, navigation, and all UI chrome. The urgency lives in the display title and the grotesque headings; the body stays quiet so the title dominates. This replaces the earlier calmer Spectral serif system (which underplayed the topic's urgency), and before that the all-sans Space Grotesk / Sora / Manrope set. A `Font Picker.dc.html` tool remains in the project as an exploration surface; the three families above are what ships.

### Hierarchy
- **Display** (Abril Fatface 400, uppercase, letter-spacing -0.01em): the "Secondhand AI" wordmark only, with the "hand" syllable in amber. It is the deliberate exception to the usual ~96px display ceiling — the wordmark is meant to dominate the fold. On the **overview hero** it sits on one line (`clamp(2.5rem, 11vw, 8.75rem)` ≈ up to 140px, `white-space:nowrap`); on the **index** header it's a step smaller (`clamp(3rem, 10vw, 7.5rem)` ≈ up to 120px). `vw`-scaled so the single line never overflows on narrow screens.
- **Headline** (Archivo 700–800, `clamp(1.5rem, 3.4vw, 3.5rem)`, letter-spacing -0.01em): section headings and study titles — study titles are title-case (not uppercase) so long titles read as editorial headlines.
- **Title** (Archivo 600–700, ~16–18px): card titles (research paper-cards, example cards).
- **Body-Emphasis** (Public Sans 500, `clamp(1.31rem, 2.8vw, 1.81rem)`): held-thought pull quotes and key findings — one or two per section, never the default.
- **Body** (Public Sans 400, ~15–16px, line-height 1.6): paragraph copy; cap width ~46–65ch.
- **Label** (Public Sans 500, ~11px, letter-spacing 0.2em, uppercase): eyebrows, nav labels, button micro-copy.

### Named Rules
**The Title-Owns-the-Fold Rule.** Abril Fatface is reserved for the "Secondhand AI" wordmark alone — its whole job is to make the title command attention. Never use it for headings, body, or UI; its power is its rarity.
**The Quiet-Support Rule.** Headings are Archivo, everything else Public Sans. The title only reads as commanding because the fonts around it stay understated — never pair the display title with another loud face.
**The Emphasis-Is-Earned Rule.** Public Sans body-emphasis (medium weight, larger size) is used sparingly — one or two held-thought moments per section, never as the default paragraph style.

## 4. Elevation

A flat, print-like system. Section structure comes from flat coloured bands meeting at straight edges, not shadows. Where something must lift off the ground — a floating content card over the gradient, or a modal — it becomes a solid light surface (`#FBFBFA` / `#F4EEE2`) with a hairline border and, for the modal, a single soft shadow. There is no decorative glassmorphism.

### Shadow Vocabulary
- **Card hairline** (`border: 1px solid rgba(34,37,43,0.12)` on `#FBFBFA`): the resting state for content cards floating over the overview gradient — no shadow, just a solid light fill and a hairline so text stays legible over any part of the gradient.
- **Feature card** (`box-shadow: 0 20px 60px rgba(0,0,0,0.25)`): reserved for the single most important callout on a section (e.g. "Why it matters").
- **Modal** (`box-shadow: 0 30px 80px rgba(10,20,35,0.4)`, backdrop `rgba(34,37,43,0.45)` + `backdrop-filter: blur`): the deepest shadow, modal panels only.
- **Small artifact** (`box-shadow: 0 4px 10px rgba(20,18,50,0.3)`): tiny document icons in the scroll-scene diagrams.

### Named Rules
**The Flat-Band Rule.** Section backgrounds are flat (a solid colour, or the live gradient) and never carry a shadow. Anything that looks lifted is a solid light card sitting on top.
**The Legible-Card Rule.** Any content card over the amber-transitioning gradient must be a solid light surface with dark text — never a translucent tint — so it stays readable regardless of the gradient behind it.

## 5. Components

Warm and considered: nothing snaps or bounces; hovers brighten or lift gently.

### Buttons
- **Shape:** fully pill (`border-radius: 100px`), always.
- **Primary:** deep-teal fill (`#3E6663`), warm-white text (`#F4EEE2`), padding `12px 24px`; hover brightens to teal (`#5E8A86`). (On a deep-teal *band*, e.g. the teal research trio, the primary flips to a smoke `#22252B` fill so it still contrasts.)
- **Secondary (outline):** translucent warm-white fill (`rgba(244,238,226,0.12)`), `1px` warm-white border, warm-white text — for a "PDF"/secondary action beside a primary.

### Chips / Labels
- **Stat chip:** pill, `rgba(94,138,134,0.10)` fill, `1px solid rgba(62,102,99,0.35)` border, deep-teal text — the one-line stat callouts (on amber lower sections, flip to `rgba(255,255,255,0.14)` fill / pale-ink text).
- **Numbered marker:** used only for real ordered sequences (the three modes, the study procedure steps) — a solid dark circle with pale text.

### Cards / Containers
- **Corner style:** 12–14px for content cards, 18–20px for the modal.
- **Background:** solid `#FBFBFA` (over the gradient) or `#F4EEE2` (modal); research inner cards use a slightly deeper tint of their band.
- **Border:** `1px solid rgba(34,37,43,0.12)` hairline.
- **Internal padding:** 18–24px cards, 32–36px modal.

### Navigation — Contents Rail
- A fixed vertical dot rail (right edge) — one dot per section; the active dot grows and its label fades in. Dots/labels are **teal** (`#8FB0AB` where they must read over dark/amber bands). This is the primary in-page nav; there is no top nav bar. Every non-index page also carries a fixed **"← Back to index"** pill (top-left) linking to `Landing.dc.html`.

### Modal
- Warm-white panel (`#F4EEE2`), `border-radius: 18px`, deepest shadow, dark backdrop with blur. Circular close button, teal labels, a pale-teal callout box, dark text throughout.

### Signature Components
- **Coloured section bands (research pages):** each part of a study (Title · Summary · Procedure · Results · Key findings · Implications) is a full-width flat band, text directly on the colour (no boxes), built from exactly three colours — one dark, one light tint, one whiteish neutral — in the fixed order dark → neutral → tint → neutral → tint → dark. Each of the four studies uses its own trio (see below). Bands meet at straight edges (no dividers). Each part carries a section header (Procedure · Results · Key findings · Implications) in the heading font (Archivo); the header font is reserved for those headers and the paper title only — stat numbers, step titles, list numerals and the implications statement are all body (Public Sans), and there are no small descriptive kickers above the headers.
- **The scroll gradient (overview):** a fixed background that interpolates clear-air → amber with scroll position, driven in JS; content floats over it on solid light cards.
- **The people-and-bots web (overview background):** a procedural canvas layer behind the content. Small **person** glyphs (head + shoulders) and **bot** glyphs (antenna + bulb, side ears, eyes, mouth) are joined by lines. **People outnumber bots (~4:1). No two bots ever link directly; people may cluster in small groups of two or three, but any wider reach happens *through* a bot** (a union-find caps people-only clusters at three). So the influence travels via people and their bots, never bot-to-bot. It starts sparse near the hero (only in the side margins, central reading column kept clear) and grows denser and wider as you scroll down, spreading toward the centre. Crucially, link reach and connections-per-node **increase with depth**, so the separate top clusters merge into a single **interconnected web** toward the bottom. The ink fades to near-invisible as it descends — the network is everywhere but you can barely see it, mirroring how secondhand-AI effects become invisible downstream. Drawn in `#22252B` at scroll-depth-based alpha, `pointer-events:none`, behind the solid content cards. The **index** reuses the same glyphs and connection rules as the final interconnected web, but airier (wider spacing, longer links) and **weighted toward the sides** so the centre stays clear behind the wordmark — while a light scatter through the middle keeps it a **single connected web**. The node field is generated slightly **beyond the header's edges**, so links crossing the border are clipped and appear to continue off-frame (it shouldn't look "stuck" inside the box). It stays contained to the header (a header-scoped canvas that fills the hero, fades over its lower edge, and does not extend into the sections below).
- **The transmission scene:** the scroll-driven Alice → AI → Bob diagram (avatars, dashed AI node, falling artifact, fan-out arrows), recoloured to read dark-on-light with teal arrows.
- **Paper-card research grid (index):** the four studies are shown as warm-white, paper-shaped cards (a folded-corner "dog-ear" via a CSS border triangle, subtle lift on hover) in a responsive grid, each linking to its research page. The **real-life examples gallery** (masonry cards + a click-to-open modal) is embedded on the same index page rather than living on a separate page — so the index is the one interactive hub.

### Research trios (one per study)
- **Harm to Learning (PNAS):** umber `#3A2E20` · pale dust `#E7DDC8` · warm white `#F4EEE2`
- **Workslop (HBR):** terracotta `#7A3A1E` · warm sand `#E4D2AE` · cream `#F5EFE4`
- **Persuasiveness (Nature Human Behaviour):** smoke `#22252B` · warm sand `#E4D2AE` · warm white `#F4EEE2`
- **Opinionated AI (CHI):** deep teal `#3E6663` · pale dust `#E7DDC8` · warm white `#F3F1EA`

### Motion
Motion is quiet and earned — nothing snaps, bounces, or elastic-overshoots; entrances ease out (`cubic-bezier(.2,.7,.2,1)`) and hovers only brighten or lift gently. Restraint is the rule: the overview is already scroll-choreographed (the scroll gradient, the people-and-bots canvas, the Alice→AI→Bob transmission scenes, the horizontal three-modes strip, the dot rail), so the other pages stay deliberately lighter.
- **Entrance reveal (all pages):** section content rises in once (`opacity 0→1`, `translateY(24px)→0`, ~0.7s) as it enters view, via a single IntersectionObserver that unobserves after firing. The "from" state is applied by JS only — the raw HTML always holds the final state, so nothing ships blank if a reveal never fires. This is a per-section settle, **not** a fade on every child; it never becomes the whole-page fade-in reflex.
- **Findings figure assembles (research pages):** the one signature moment. When a study's **Results** band scrolls into view, its mini bar-charts grow from the baseline (`scaleY 0→1`, staggered ~90ms) and any numeric figure counts up from zero (~1s, ease-out, decimals and `+`/`−`/`%` preserved). Word-only figures (e.g. "Shift", "≈ human") don't count — only their bars grow.
- **Modals:** backdrop fades (`mfade`, ~0.22s), panel lifts in (`mpop`: fade + `translateY(12px)` + `scale(.985)→1`, ~0.32s).
- **The index web stays instant** — it draws in place, not as an assembling animation.
- **Reduced motion is honoured on every page:** a `prefers-reduced-motion: reduce` media query collapses all animation/transition durations, and the JS skips the hide-then-reveal and figure choreography entirely (content shows in its final state), so reduced-motion users never wait on — or lose — content.

## 6. Do's and Don'ts

### Do:
- **Do** keep clear air as the default ground and add colour deliberately — a chapter block, a coloured band, a single stat.
- **Do** keep teal (`#5E8A86`/`#3E6663`/`#8FB0AB`) as the one accent on every page, carrying links, nav, and the beneficial side of the story.
- **Do** use amber (`#C25A2B`) only for heat, urgency, or the harm side — and keep it rare so it still reads as heat.
- **Do** build research pages as flat coloured bands from exactly three colours (dark / light tint / whiteish neutral) in the fixed order, text directly on the colour.
- **Do** run the overview background as a clear-air → amber scroll gradient, with content on solid light cards so it stays legible.
- **Do** give every non-index page a "← Back to index" link, and provide a `prefers-reduced-motion` fallback for the scroll-driven scenes.

### Don't:
- **Don't** introduce a generic SaaS landing-page look — no hero-metric tiles, no gradient-clipped text, no tiny uppercase eyebrow stacked above every section, no identical icon-plus-heading card grids.
- **Don't** let the site read like an academic PDF — research findings are staged as coloured bands and designed scenes, never pasted abstracts.
- **Don't** tip into AI-panic clickbait — there is no red alarm colour; amber is warmth that rises, not danger.
- **Don't** put dark text on the amber lower sections or light-grey text on light grounds — use pale-ink on dark/amber, and solid light cards with dark text elsewhere.
- **Don't** use more than three band colours on a single research page.
- **Don't** use Abril Fatface for anything but the "Secondhand AI" wordmark, or add a fourth family — the system is Abril Fatface (wordmark) + Archivo (headings) + Public Sans (everything else), and the title's power depends on that display face staying rare.
- **Don't** add numbered section markers as decoration — reserve them for the two real sequences (the three modes, the study procedure steps).
