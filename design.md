---
name: Amstrato
version: 1.0.0
description: AI Fulfillment Platform — automating lead capture and order fulfillment for service businesses and e-commerce brands.

colors:
  primary: "#060809"
  surface: "#0c1015"
  card: "#111820"
  border: "#1c2a35"
  accent: "#f0a500"
  accent-dim: "#b87d00"
  accent-glow: "rgba(240,165,0,0.08)"
  white: "#eef2f6"
  text: "#8aa5b8"
  muted: "#4a6275"
  danger: "#ff4d6d"
  info: "#38bdf8"

typography:
  display:
    fontFamily: "Bebas Neue"
    usage: "Hero headings, section titles, stats, logo, nav logo"
    letterSpacing: "0.02em to 0.08em"
    lineHeight: "0.92 to 0.95"
  body:
    fontFamily: "DM Sans"
    weights: [300, 400, 500, 600]
    usage: "All body copy, buttons, descriptions, UI labels"
  mono:
    fontFamily: "DM Mono"
    weights: [400, 500]
    usage: "Tags, labels, nav links, stats labels, code, timestamps"

typescale:
  hero: "clamp(72px, 10vw, 140px)"
  h1: "clamp(42px, 6vw, 80px)"
  h2: "36px"
  h3: "18px to 20px"
  h4: "15px to 16px"
  body: "14px to 16px"
  small: "12px to 13px"
  label: "10px to 11px"

spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "72px"
  4xl: "100px"
  section: "100px 48px"

rounded:
  sm: "6px"
  md: "8px to 10px"
  lg: "12px to 14px"
  full: "9999px"

shadows:
  card: "none (border-based depth system)"
  hover: "translateY(-4px) on card hover"
  glow: "radial-gradient amber at key focal points"

borders:
  default: "1px solid #1c2a35"
  accent: "1px solid rgba(240,165,0,0.3) on hover"
  active: "1px solid rgba(240,165,0,0.4) on active/featured"
  top-accent: "2px solid #f0a500 (top border on cards)"
  top-danger: "2px solid #ff4d6d (top border on problem cards)"

animation:
  fadeUp: "opacity 0 to 1, translateY 24px to 0, duration 0.8s ease"
  stagger: "animation-delay increments of 0.15s for sequential elements"
  reveal: "IntersectionObserver scroll reveal, threshold 0.1"
  hover: "transition 0.2s ease on all interactive elements"
  cursor: "custom amber dot + ring, mix-blend-mode difference"

components:
  button-primary:
    background: "#f0a500"
    color: "#060809"
    padding: "16px 36px"
    borderRadius: "8px"
    fontWeight: 600
    fontSize: "15px"
    hover: "opacity 0.88, translateY(-1px)"
  button-secondary:
    background: "transparent"
    color: "#eef2f6"
    border: "1px solid #1c2a35"
    padding: "16px 36px"
    borderRadius: "8px"
    hover: "border-color #f0a500, translateY(-1px)"
  card:
    background: "#111820"
    border: "1px solid #1c2a35"
    borderRadius: "10px to 14px"
    topAccent: "2px solid #f0a500"
    hover: "border-color rgba(240,165,0,0.3)"
  nav:
    background: "rgba(6,8,9,0.9)"
    backdropFilter: "blur(20px)"
    borderBottom: "1px solid rgba(28,42,53,0.6)"
    height: "~64px"
    padding: "20px 48px"
  section-tag:
    fontFamily: "DM Mono"
    fontSize: "10px"
    letterSpacing: "0.14em"
    textTransform: "uppercase"
    color: "#f0a500"
  stat:
    numFont: "Bebas Neue"
    numSize: "42px"
    numColor: "#f0a500"
    labelFont: "DM Mono"
    labelSize: "10px"
    labelColor: "#4a6275"
  input:
    background: "#111820"
    border: "1px solid #1c2a35"
    borderRadius: "8px"
    color: "#eef2f6"
    focusBorder: "#f0a500"
    placeholder: "#4a6275"

layout:
  maxWidth: "1200px"
  sectionPadding: "100px 48px"
  mobilePadding: "72px 24px"
  gridGap: "16px to 24px"
  solutionGrid: "repeat(3, 1fr)"
  verticalsGrid: "1fr 1fr"
  pricingGrid: "repeat(3, 1fr)"
  mobileBreakpoint: "768px"
---

## Overview

Amstrato is an AI fulfillment platform for service businesses and e-commerce brands. The visual identity communicates **industrial precision meets AI sophistication** — dark, bold, and unapologetically premium. The brand never tries to look "techy" or generic. It commands attention through restraint and contrast.

The design system is built on a **dark-first philosophy** — deep blacks and navies with a single amber (#f0a500) accent that owns every interactive moment on the page.

## Brand Personality

- **Disciplined** — Military-precision execution. Every element has a purpose.
- **Premium** — This is not a cheap agency. The design charges accordingly.
- **AI-native** — AI is embedded in the brand without screaming it.
- **Direct** — No fluff. No filler. Clients see the value immediately.
- **Elevated** — "Strato" means above. The brand always positions above the competition.

## Colors

**Primary (#060809):** The darkest background. Used for the main body, hero section, and footer. Never use as text color.

**Surface (#0c1015):** Slightly lighter background for alternating sections (problem, verticals, pricing). Creates depth without dramatic contrast.

**Card (#111820):** The standard card background. All interactive cards, pricing boxes, and feature modules sit on this.

**Border (#1c2a35):** The default border for all cards, inputs, and dividers. Subtle but structural.

**Accent (#f0a500):** Amber. **The sole interaction driver.** This color appears exclusively on:
- CTAs and primary buttons
- Section tags and labels
- Stat numbers and key data points
- Top accent borders on cards
- Hover state borders
- Cursor dot
- Logo accent letter
- Timeline dots

**Never use amber as a background fill on large surfaces.** Never use it decoratively. It earns its appearance by marking action or importance.

**Accent-dim (#b87d00):** Used for secondary amber states — result lines, subtle highlights.

**White (#eef2f6):** Primary text. Slightly warm off-white, never pure #ffffff.

**Text (#8aa5b8):** Body copy, descriptions, card paragraphs. Cool, readable, recessive.

**Muted (#4a6275):** Placeholder text, secondary labels, nav links (default state), footer copy.

**Danger (#ff4d6d):** Used exclusively for "problem" indicators — the top accent on problem cards, and the red text callout in problem section headings. Never used in CTAs.

## Typography

**Bebas Neue** is the display font. Used for all hero text, section headings, stats, the logo, and any large typographic moments. Always uppercase by nature. Letter-spacing 0.02em–0.08em depending on size. Line-height 0.92–0.95 for large display use.

**DM Sans** is the workhorse. All body copy, button labels, card descriptions, and UI text. Weights 300 (light body), 400 (regular), 500 (medium), 600 (strong CTAs). Never bold/700 in body context.

**DM Mono** is the precision signal. Used for: section tags, stat labels, nav links, timestamps, code snippets, any "technical metadata" moment. Always 10–11px, always letter-spaced 0.08–0.15em, always uppercase in label context.

**Font pairing rule:** Display headers in Bebas Neue → immediate sub-copy in DM Sans 300 weight → metadata/labels in DM Mono. This three-tier rhythm is consistent across every section.

## Spacing & Layout

Sections breathe at 100px vertical padding on desktop, 72px on mobile. This generosity signals premium.

Cards use 20–40px internal padding depending on size. Small feature cards (problem grid): 24px. Large feature cards (vertical, pricing): 36–40px.

Max content width is 1200px, centered. Full-bleed backgrounds, contained content.

Grid gaps: 12–16px for dense grids (problem cards), 20–24px for feature grids.

## Cards & Depth

Amstrato uses **border-based depth** — not shadows. All cards are defined by:
1. A subtle border (#1c2a35)
2. A slightly lighter background than the section (#111820 on #0c1015)
3. A 2px colored top accent (amber for solution, red for problem)
4. Border transitions to amber on hover

This creates a clean, legible hierarchy without drop shadows cluttering the dark theme.

## Animations & Motion

**Page load:** Hero elements animate in with staggered fadeUp (opacity + translateY 24px → 0). Delay increments: 0.2s, 0.35s, 0.5s, 0.65s, 0.8s.

**Scroll reveal:** All section content uses IntersectionObserver. Elements fade up on entering viewport. Stagger: 80ms between sibling elements.

**Hover states:** All interactive elements transition at 0.2s ease. Cards lift with translateY(-4px). Borders transition to amber. Buttons shift opacity or lift.

**Custom cursor:** Amber dot (10px) + ring (36px, 1px amber border). Uses mix-blend-mode: difference for visibility on all backgrounds. Ring lags behind cursor with lerp animation (0.12 factor) for premium feel.

**Rule:** Motion is purposeful. No spinning loaders, no bouncing elements, no decorative animations. Every motion communicates state change or guides attention.

## Component Patterns

**Section structure:** Tag (DM Mono, amber) → Title (Bebas Neue) → Sub-copy (DM Sans 300, text color) → Content grid. This pattern repeats on every section.

**Card structure:** Optional top accent (2px) → Number or icon → Heading → Body → Optional result/stat line (DM Mono, amber).

**Button hierarchy:** Primary (amber fill) → Secondary (border only) → Text link (nav links, footer links). Never more than one primary CTA per viewport.

**Pricing cards:** Standard border → Featured card gets amber border + subtle amber background gradient. "Most Popular" label in amber.

## Accessibility

- All amber on dark backgrounds meets WCAG AA contrast (minimum 4.5:1)
- Amber (#f0a500) on primary (#060809): contrast ratio ~9.8:1 — passes AAA
- White (#eef2f6) on card (#111820): contrast ratio ~12.3:1 — passes AAA
- Text (#8aa5b8) on primary (#060809): contrast ratio ~4.7:1 — passes AA
- Muted (#4a6275) on primary: contrast ratio ~2.9:1 — decorative use only, never body copy

## Voice & Tone in UI Copy

- **Headings:** All caps, declarative, punchy. "AUTOMATE YOUR PIPELINE." not "Automate your pipeline today"
- **Body:** Direct, no fluff. One idea per sentence. Active voice.
- **Labels:** Lowercase in sentence context, uppercase when used as tags/categories
- **CTAs:** Action verbs. "Book Free Audit" not "Learn More". "Get Started" not "Click Here"
- **Stats:** Numbers first, context second. "70% / Less manual work"

## What NOT To Do

- Never use purple, blue gradients, or generic "AI" aesthetics
- Never use Inter, Roboto, or system fonts
- Never use amber as a large fill area (header backgrounds, section fills)
- Never add drop shadows — use borders and background contrast instead
- Never center-align body copy blocks (only CTA sections)
- Never use more than 3 font weights in a single component
- Never add decorative animations — every motion must serve a function
- Never use more than one primary CTA per visible viewport
