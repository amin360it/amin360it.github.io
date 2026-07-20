# Amin360IT — Features

## Preloader
- [x] Fixed fullscreen overlay with backdrop blur
- [x] Static site name + subtitle (no Vue dependency)
- [x] Pulsing icon with spinning loader
- [x] Hides on `window.onload` + 400ms grace period
- [x] 4-second max fallback timeout
- [x] Fade-out CSS transition

## Navigation
- [x] Fixed top bar with glassmorphism
- [x] Active section highlighting on scroll
- [x] Logo hover rotation animation
- [x] Site name + subtitle in nav
- [x] Dark/light theme toggle (sun/moon icon swap)
- [x] "Start Project" CTA with shimmer effect
- [x] Off-canvas mobile menu (80vw max, slide-in)
- [x] Mobile menu includes contact info + social links
- [x] Gradient scroll progress bar

## Hero
- [x] Three.js WebGL particle system (800 points, mouse parallax)
- [x] 3 animated gradient blobs (float keyframes, staggered)
- [x] Dark gradient overlay
- [x] "Accepting New Clients" badge with ping/pulse
- [x] Typewriter cycling 5 phrases with cursor blink
- [x] Terminal-style code display
- [x] 2 CTA buttons: primary (shimmer) + secondary (glass)
- [x] Stats counter animation (ease-out cubic, + suffix)

## About
- [x] 4 score cards with counter animation
- [x] Mission / Vision / Values glass cards
- [x] 5-item "Why Work With Me" list with check icons
- [x] 8 colored capability tag badges

## Services
- [x] SVG wave dividers (multi-layer, responsive)
- [x] 7 tabbed groups with Material Icons
- [x] Active tab: gradient background + shadow
- [x] Fade transition between tab content
- [x] 3 cards per group in responsive grid
- [x] Each card: hover lift, gradient icon (shifts on hover), title, description, 6 feature highlights
- [x] AOS stagger animations

## Tech Stack Marquee
- [x] Continuous horizontal scroll (45s linear)
- [x] 22 tech items with brand-color icons
- [x] Hover scale effect (1.15x)
- [x] Gradient fade masks on edges
- [x] Duplicated content for seamless loop

## Portfolio
- [x] 5 category filter buttons with active state
- [x] Transition-group slide-up on filter change
- [x] 10 project cards with overlay + gradient
- [x] Image zoom on hover (1.1x)
- [x] Broken image SVG fallback
- [x] Full-screen modal: gallery thumbnails, tech stack grid, UI/UX story, case study, description, testimonial, live/video links
- [x] Scroll lock when modal open

## Process
- [x] 4-step vertical timeline with connector line
- [x] Hover: border color shifts to violet
- [x] Large translucent step number watermark

## Testimonials
- [x] 3 testimonials auto-rotating every 5s
- [x] 5-star rating display
- [x] Avatar initial circle + name + role
- [x] Dot navigation (active dot widens on selection)
- [x] Fade transition between slides

## Clients
- [x] 6 cards with distinct brand colors
- [x] Industry-specific FontAwesome icons
- [x] Staggered float animation (0.2s delay each)
- [x] Hover lift + scale + shadow

## Pricing
- [x] 3 tiers with feature lists
- [x] Featured plan: elevated, gradient bg, "Popular" badge
- [x] Monthly availability limits shown
- [x] WhatsApp CTA buttons

## Contact
- [x] 3 info cards: address, phone, email
- [x] Social follow links (4 platforms)
- [x] Full form: name, email, subject, message
- [x] Web3Forms API integration
- [x] Loading spinner on submit
- [x] Success/error toast notifications
- [x] Newsletter email input with subscribe

## Footer
- [x] Logo + tagline + description
- [x] Social icons (4 platforms)
- [x] Quick links + services links
- [x] Newsletter signup
- [x] Copyright + privacy/terms links

## Theme
- [x] Dark mode (default)
- [x] Light mode via CSS custom properties swap
- [x] Smooth 0.4s transition on all color properties
- [x] LocalStorage persistence
- [x] Three.js particle color updates on switch
- [x] Scrollbar color adapts to theme

## UI/UX
- [x] Custom cursor (dot + ring outline) on hover devices only
- [x] Noise texture overlay (SVG filter, 1.5% opacity)
- [x] Glassmorphism cards with border glow on hover
- [x] Button ripple effect
- [x] Shimmer animation on primary buttons
- [x] Reduced motion media query (kills all animation)
- [x] Print stylesheet (hides decor, white bg)
- [x] Focus-visible outlines (violet, 2px)
- [x] Custom scrollbar (thin, themed)
- [x] Autofill input styling for both themes
- [x] Gradient text animation (duotone, warm variants)
- [x] Typography scale: 6 heading + 3 body sizes

## Performance
- [x] `loading="lazy"` on all images
- [x] Image error fallback via `@error`
- [x] Passive scroll event listener
- [x] `requestAnimationFrame` throttled cursor
- [x] Three.js dispose on unmount (geometry, material, renderer)
- [x] Pixel ratio capped at 2 for WebGL

## Accessibility
- [x] ARIA labels on icon-only buttons
- [x] Semantic section IDs
- [x] Focus-visible outlines
- [x] Image alt texts
- [x] Reduced motion support
- [x] Role attributes on cursor elements

## SEO
- [x] Meta description
- [x] Robots index/follow
- [x] Open Graph (title, description, type, url)
- [x] Twitter card
- [x] JSON-LD Person schema
- [x] Semantic HTML landmarks
