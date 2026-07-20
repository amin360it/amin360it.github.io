# Amin360IT Website — Features (Current Implementation)

## 1. Navigation
- [x] Fixed glassmorphism navbar with backdrop blur
- [x] Logo + site name with hover rotation
- [x] Desktop nav links with active section highlighting
- [x] Dark/light theme toggle with localStorage persistence
- [x] Off-canvas mobile menu with slide animation
- [x] CTA "Start Project" button with shimmer effect
- [x] Scroll progress bar at top

## 2. Preloader
- [x] Static hardcoded text ("Amin360IT" / "Software Solutions")
- [x] Pulse animation on logo icon
- [x] Spinning loader indicator
- [x] Waits for `window.onload` before hiding (400ms grace)
- [x] Max 4s fallback timeout
- [x] Fade transition out

## 3. Hero Section
- [x] Three.js particle system (800 particles, mouse parallax)
- [x] Animated gradient blob backgrounds (float animation)
- [x] Typewriter effect cycling: ENTERPRISE SYSTEMS, WEB APPLICATIONS, MOBILE APPS, DESKTOP SOFTWARE, CUSTOM SOLUTIONS
- [x] "Accepting New Clients for 2026" badge with ping indicator
- [x] Terminal-style command display
- [x] Two CTA buttons: "Explore Solutions" (shimmer) + "Watch Showreel"
- [x] Stats grid with counter animation (scroll-triggered)

## 4. About Section
- [x] Score cards: 50+ Projects, 30+ Clients, 7 Years Exp, 24/7 Support
- [x] Mission, Vision, Values cards
- [x] "Why Work With Me" list (5 items)
- [x] Core Capabilities tags (8 technologies)

## 5. Services Section
- [x] 7 tabbed service groups with Material Icons
- [x] Each service has: icon, title, description, feature highlights with checkmarks
- [x] Fade transition on tab switch
- [x] SVG wave dividers at section boundaries
- [x] Animated pulse-ring on section header icon

## 6. Tech Stack Marquee
- [x] Continuous horizontal scrolling marquee
- [x] 22+ tech logos with labels
- [x] Hover scale effect on individual items
- [x] Gradient fade masks on both edges

## 7. Portfolio Section
- [x] Filter by category: All, Web, App, Desktop, Enterprise
- [x] Transition-group slide-up animation on filter
- [x] Project cards with image, overlay, category badge, tech tags
- [x] Full-screen modal with: gallery screenshots, client info, duration, tech stack, UI/UX story, case study, testimonial, live demo/video links
- [x] Error fallback images for broken URLs
- [x] 10 projects across all categories

## 8. Process Section
- [x] 4-step vertical timeline: Discovery, Design, Development, Deployment
- [x] Hover highlight on active border
- [x] Background number watermark

## 9. Testimonials
- [x] 3 rotating testimonials with 5-second interval
- [x] Star rating (always 5 stars)
- [x] Avatar initials + name + role
- [x] Dot navigation with active width transition

## 10. Clients Section
- [x] 6 client cards with brand colors and icons
- [x] Float animation with staggered delays
- [x] Hover lift + shadow effect

## 11. Pricing Section
- [x] 3 tiers: Quick Fix ($50), Standard Project ($150), Enterprise Solution ($500+)
- [x] Featured plan highlighted with badge and elevated position
- [x] Feature lists with check icons
- [x] WhatsApp CTA buttons
- [x] Monthly availability limits

## 12. "Trusted By Innovators" Marquee
- [x] Duplicate marquee with glass pill-style tech items
- [x] Pause on hover
- [x] Gradient fade edges

## 13. Contact Section
- [x] Address, phone, email cards with glass style
- [x] Social media links (Facebook, LinkedIn, GitHub)
- [x] Contact form with name/email/subject/message fields
- [x] Web3Forms API integration
- [x] Loading state on submit with spinner
- [x] Toast notification system (success/error)
- [x] Newsletter signup with email input

## 14. Footer
- [x] Logo + description + social icons
- [x] Quick links (matching nav)
- [x] Services links
- [x] Newsletter signup
- [x] Copyright + Privacy Policy / Terms links

## 15. Theme Support
- [x] Dark mode (default)
- [x] Light mode with CSS custom properties
- [x] Smooth background/text color transitions
- [x] System preference: no (manual toggle only, persisted to localStorage)
- [x] Update Three.js particle color on theme switch

## 16. UI/UX Details
- [x] Custom cursor (dot + outline) on hover-capable devices
- [x] Noise texture overlay for grain effect
- [x] Glassmorphism cards with hover lift and glow
- [x] Ripple effect on buttons
- [x] Magnetic button effect
- [x] Reduced motion media query support
- [x] Custom scrollbar styling
- [x] Focus-visible outlines for accessibility
- [x] Print stylesheet hiding decorative elements
- [x] Autofill input styling for dark/light modes

## 17. Performance & Edge Cases
- [x] Lazy loading on images via `loading="lazy"`
- [x] Error fallback for broken images
- [x] Passive scroll listener for better scroll performance
- [x] Debounced cursor movement via requestAnimationFrame
- [x] Three.js disposed on unmount to prevent memory leaks
- [x] Toast auto-dismiss with timer
- [x] Scroll lock for modals/menus with stacking support
