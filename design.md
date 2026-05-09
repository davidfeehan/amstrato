---
name: Amstrato
version: 2.0.0
description: AI Fulfillment Platform — automating lead capture and order fulfillment for service businesses and e-commerce brands.

colors:
  primary-bg: "#060809"
  surface: "#0c1015"
  card: "#111820"
  border: "#1c2a35"
  accent-primary: "#c8ff57"
  accent-primary-dim: "#9acc3a"
  accent-secondary: "#9b59ff"
  accent-secondary-glow: "rgba(155,89,255,0.07)"
  white: "#eef2f6"
  text: "#8aa5b8"
  muted: "#4a6275"
  danger: "#9b59ff"

typography:
  display:
    fontFamily: "Bebas Neue"
    usage: "Hero headings, section titles, stats, logo, pricing numbers"
    letterSpacing: "0.02em to 0.08em"
    lineHeight: "0.88 to 0.95"
  body:
    fontFamily: "DM Sans"
    weights: [300, 400, 500, 600]
    usage: "All body copy, buttons, descriptions, UI labels"
  mono:
    fontFamily: "DM Mono"
    weights: [400, 500]
    usage: "Tags, labels, nav links, stats labels, code, timestamps"

typescale:
  hero-desktop: "clamp(56px, 10vw, 140px)"
  hero-mobile: "22vw"
  section-title-desktop: "clamp(36px, 5vw, 72px)"
  section-title-mobile: "18vw"
  cta-headline-mobile: "20vw"
  h3: "16px to 18px"
  h4: "15px to 17px"
  body: "14px to 18px"
  small: "12px to 13px"
  label: "10px to 12px"

spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "72px"
  4xl: "100px"
  section-desktop: "80px 48px"
  section-mobile: "60px 20px"

rounded:
  sm: "6px"
  md: "8px to 10px"
  lg: "12px to 14px"
  full: "9999px"

borders:
  default: "1px solid #1c2a35"
  hover: "1px solid rgba(200,255,87,0.3)"
  featured: "1px solid #9b59ff"
  top-accent-primary: "2px solid #c8ff57"
  top-accent-secondary: "2px solid #9b59ff"

animation:
  fadeUp: "opacity 0→1, translateY 20px→0, 0.8s ease, staggered delays"
  reveal: "IntersectionObserver, threshold 0.1, stagger 60ms"
  hover-card: "translateY(-4px), 0.2s ease"
  hover-btn: "opacity 0.88, translateY(-1px)"
  active-btn: "scale(0.97)"
  pulse: "scroll line opacity 0.4→1→0.4, 2s infinite"

components:
  button-primary:
    background: "#c8ff57"
    color: "#060809"
    padding: "14px 28px desktop / 18px 28px mobile"
    borderRadius: "8px"
    fontWeight: 600
    fontSize: "15px desktop / 17px mobile"
    tapHighlight: "transparent"
    touchAction: "manipulation"
  button-secondary:
    background: "transparent"
    color: "#eef2f6"
    border: "1px solid rgba(200,255,87,0.4)"
    borderRadius: "8px"
    hover: "border-color #9b59ff"
  nav:
    background: "rgba(6,8,9,0.95)"
    backdropFilter: "blur(20px)"
    borderBottom: "1px solid rgba(28,42,53,0.6)"
    padding: "16px 48px desktop / 14px 20px mobile"
    mobileNav: "hamburger icon → .mobile-menu.open overlay"
  card:
    background: "#111820"
    border: "1px solid #1c2a35"
    borderRadius: "10px to 14px"
    topAccentLime: "2px solid #c8ff57 (solution cards)"
    topAccentPurple: "2px solid #9b59ff (problem cards)"
    hoverBorder: "rgba(200,255,87,0.3)"
    hoverLift: "translateY(-4px)"
  section-tag:
    fontFamily: "DM Mono"
    fontSize: "10px to 12px"
    letterSpacing: "0.14em"
    color: "#9b59ff"
  stat:
    numFont: "Bebas Neue"
    numColor: "#9b59ff"
    labelFont: "DM Mono"
    labelColor: "#4a6275"
  input:
    background: "#111820"
    border: "1px solid #1c2a35"
    focusBorder: "#c8ff57"
    borderRadius: "8px"
    inputmode: "email"
    autocomplete: "email"
    touchAction: "manipulation"
    userSelect: "text"
  form:
    endpoint: "https://formspree.io/f/mnjwgrod"
    method: "AJAX fetch POST — no page redirect"
    successColor: "#c8ff57"
    replyTo: "contact@amstrato.com"
  calendly:
    link: "https://calendly.com/david-amstrato"
    eventType: "Free 30-Min AI Audit"

layout:
  maxWidth: "1200px"
  breakpoints:
    tablet: "1024px"
    mobile: "768px"
    small: "380px"
  grids:
    solution: "repeat(3,1fr) → 1fr mobile"
    verticals: "1fr 1fr → 1fr mobile"
    pricing: "repeat(3,1fr) → 1fr mobile"
    problem: "1fr 1fr (both desktop and mobile)"

---

## Overview

Amstrato is an AI fulfillment platform for service businesses and e-commerce brands. The visual identity communicates **industrial precision meets AI sophistication** — dark, bold, and unapologetically premium.

## Two-Color Accent System

**Primary — Electric Lime (#c8ff57):**
CTAs, buttons, logo accent letter (A), hero em text, solution card top borders, step dots, pricing checkmarks, featured pricing card border. The action color. Never decorative.

**Secondary — Electric Purple (#9b59ff):**
Section tags, stat numbers, hero glow, scroll line, result text on solution cards, featured vertical card borders/glow, feature item arrows, step numbers, CTA glow, problem card top borders, danger/error states. The highlight color.

## Brand Personality

- **Disciplined** — Military-precision execution. Every element has a purpose.
- **Premium** — This is not a cheap agency. The design charges accordingly.
- **AI-native** — AI is embedded in the brand without screaming it.
- **Direct** — No fluff. No filler. Clients see the value immediately.
- **Elevated** — "Strato" means above. The brand always positions above the competition.

## Typography Rules

**Bebas Neue** — Always for display/hero/stats. Always uppercase by nature. Line-height 0.88–0.95 at large sizes.

**DM Sans** — Body copy, buttons, card text. Weights 300 (light body) → 600 (strong CTAs). Never 700.

**DM Mono** — Section tags, stat labels, nav links (default), any "technical metadata." Always small (10–12px), letter-spaced, uppercase in label context.

**Pairing rule:** Bebas Neue heading → DM Sans 300 sub-copy → DM Mono label. This three-tier rhythm is consistent across every section.

## Responsive Rules

**Mobile (<768px):**
- Hamburger menu replaces nav links
- Hero H1 = 22vw (fills screen edge to edge)
- Section titles = 18vw
- CTA headline = 20vw
- All buttons full-width, stacked vertically
- All grids collapse to single column

**Mobile-First Requirements:**
- `touch-action: manipulation` on all buttons/inputs (removes 300ms delay)
- `-webkit-tap-highlight-color: transparent` on all buttons
- `inputmode="email"` on email inputs
- Form submissions via AJAX fetch — never redirect to third-party pages
- CTA section `::before` glow must have `pointer-events: none; z-index: 0`
- All CTA content must have `position: relative; z-index: 1`
- No custom cursor on any device

## Cards & Depth

Border-based depth system — no drop shadows ever.
1. Default border: `1px solid #1c2a35`
2. Background slightly lighter than parent section
3. 2px top accent (lime = solution/positive, purple = problem/danger)
4. Hover: border transitions to `rgba(200,255,87,0.3)` + lift `translateY(-4px)`

## What NOT To Do

- Never use amber, orange, or blue gradients
- Never use Inter, Roboto, Arial, or system fonts
- Never use lime as a large background fill on sections
- Never add drop shadows — use borders and background contrast
- Never center-align body copy blocks (only CTA sections are centered)
- Never place more than one primary CTA per visible viewport
- Never use a custom cursor on mobile
- Never redirect form submissions to third-party pages
- Never use localStorage in Claude artifacts
- Never add decorative animations — every motion serves a function
