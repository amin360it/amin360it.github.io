# Amin360IT — Site Plan

## Site Identity

| Field | Value |
|-------|-------|
| Name | Amin360IT |
| Subtitle | Software Solutions |
| Owner | Aminur Rashid |
| Title | Software Developer |
| Tagline | Software, Web Development & Digital Solutions |
| Domain | https://amin360it.com |

## Page Architecture (Single Page)

| Order | Section | ID | Component |
|-------|---------|----|-----------|
| 1 | Preloader | — | Full-screen overlay, static text, spinner, fades on window.load |
| 2 | Navbar | `#navbar` | Fixed glass bar, 7 links, theme toggle, mobile off-canvas |
| 3 | Hero | `#home` | Full viewport, particles canvas, blobs, typewriter, CTAs, 4 stats |
| 4 | Scroll Indicator | — | Bouncing pill with gradient transition |
| 5 | About | `#about` | 4 score cards, mission/vision/values, why-me list, 8 capability tags |
| 6 | Services | `#services` | 7 tab groups, SVG wave dividers, 3 cards per tab |
| 7 | Tech Marquee | — | 22 icons, horizontal scroll, gradient fade edges |
| 8 | Portfolio | `#portfolio` | 5 category filters, 10 project cards, modal with case studies |
| 9 | Process | `#process` | 4-step timeline: Discovery → Design → Development → Deployment |
| 10 | Testimonials | — | 3-slide carousel, 5s auto-rotate, dot nav |
| 11 | Clients | — | 6 logo cards, brand colors, float animation |
| 12 | Pricing | `#pricing` | 3 tiers: $50 / $150 / $500+, featured highlight |
| 13 | Marquee 2 | — | Duplicate tech marquee, glass pill style, dark bg |
| 14 | Contact | `#contact` | Form (Web3Forms), address, phone, email, social, newsletter |
| 15 | Footer | — | Logo, quick links, services, newsletter, copyright |
| 16 | Project Modal | teleport | Full overlay with gallery, case study, testimonial |
| 17 | Video Modal | teleport | YouTube embed overlay |
| 18 | Toast | fixed | Slide-in notification, auto-dismiss 4s |

## Navigation

```
[Logo] Home | About | Services | Work | Process | Pricing | Contact [🌙] [Start Project]
```

## External Dependencies

| Resource | Version | Source |
|----------|---------|--------|
| Vue 3 | — | unpkg CDN (ESM) |
| Tailwind CSS | — | CDN (config via script) |
| Three.js | r128 | cdnjs |
| AOS | 2.3.1 | unpkg (CSS + JS) |
| Font Awesome | 6.4.0 | cdnjs |
| Material Icons | — | Google Fonts |
| Plus Jakarta Sans | — | Google Fonts |
| JetBrains Mono | — | Google Fonts |
| Web3Forms | — | api.web3forms.com |

## Design Tokens

| Token | Value |
|-------|-------|
| Primary colors | Blue #3b82f6, Violet #8b5cf6, Pink #ec4899 |
| Container max | 1280px |
| Section spacing | 100px (desktop), 70px (mobile) |
| Card padding | 28px (desktop), 20px (mobile) |
| Border radius | sm: 0.5rem, md: 0.75rem, lg: 1rem, xl: 1.25rem, 2xl: 1.5rem |
| Theme | Dark default, light toggle, localStorage persistence |
| CSS variables | ~30 custom properties for bg/text/border/glass/input per theme |

## Technical Architecture

- **Framework:** Vue 3 Composition API (no build step, CDN-only)
- **Styling:** Tailwind utility classes + inline `<style>` with CSS vars
- **Animations:** AOS scroll triggers, CSS @keyframes, Three.js WebGL
- **Theme:** Class-based (`<html class="dark|light">`), toggles CSS variable sets
- **Loader:** `ref(true)` → waits for `window.onload` + 400ms, 4s max fallback
- **Scroll lock:** Counter-based stacking for modal/menu prevention
