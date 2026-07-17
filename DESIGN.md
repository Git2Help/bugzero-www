---
version: alpha
name: BugZero IT Support Landing Page Template
description: A high-density, professional IT managed services landing page featuring a tech-forward aesthetic with glassmorphism, floating interface elements, and data-driven visual cues.
colors:
  primary: "#009EE0"
  secondary: "#D9E021"
  text-main: "#808080"
  text-heading: "#009EE0"
  text-muted: "#696969"
  surface-bg: "#FFFFFF"
  surface-alt: "#F9FAFB"
  border: "rgba(0, 158, 224, 0.3)"
typography:
  headings:
    family: "Futura Sd, Futura, Trebuchet MS, sans-serif"
    weight: 600
  body:
    family: "'Helvetica Neue', Helvetica, Arial, sans-serif"
    weight: 400
  mono:
    family: "'Geist Mono', monospace"
spacing:
  base: 4px
  container: 1280px
  section-gap: 80px
rounded:
  base: 12px
  card: 16px
  section: 24px
components:
  button-primary:
    bg: "{colors.primary}"
    text: "#FFFFFF"
    radius: 12px
  card-glass:
    bg: "rgba(255, 255, 255, 0.85)"
    backdrop-blur: "none"
    border: "{colors.border}"
    shadow: "multi-layered-elevation"
---

## Overview
The BugZero landing page conveys trust, proactive monitoring, and modern IT infrastructure management. The visual personality is "High-Tech Corporate Clean," characterized by a white-dominant palette accented by a vibrant cyan-blue and lime-yellow. The layout is dense but breathable, utilizing staggered "floating" dashboard-style cards to simulate a real-time monitoring interface. Motion is used to reinforce the concept of "active supervision" through gentle floating animations and pulse effects on status indicators.

## Colors
- **Primary Blue (#009EE0)**: Used for brand identity, primary headings, and call-to-action buttons. Represents stability and professional IT services.
- **Accent Lime (#D9E021)**: Used sparingly for high-visibility highlights, status markers, and small decorative dots to represent energy and attention.
- **Neutral Grays**: Backgrounds use `#FFFFFF` and `#F9FAFB`. Text scales from `#808080` (main body) down to `#696969` (detailed descriptions).
- **Glass Materials**: Backgrounds for cards use `rgba(255, 255, 255, 0.85)` to create a layered depth effect against the underlying mesh gradients.

## Typography
- **Primary Headings**: Utilizes a geometric sans-serif stack (Futura Sd) with tight tracking and leading (`0.95`). Titles are large (up to 72px) and high-impact.
- **Body Copy**: Standard Helvetica Neue stack for maximum legibility in technical descriptions.
- **Interface Text**: Small, uppercase or semibold labels (12px-14px) used for metadata and status badges.

## Layout
- **Grid System**: 12-column grid for the hero and main sections.
- **Max Width**: 1280px (`max-w-7xl`) centered with responsive padding (16px to 32px).
- **Asymmetry**: High use of overlapping elements and absolute positioning in the hero section to create an interface "HUD" feel.
- **Sectioning**: Distinct rounded blocks (24px - 32px radius) with subtle borders separate major content areas.

## Elevation & Depth
- **Heavy Shadows**: Use of complex multi-stop box shadows to simulate soft, large-scale elevation (e.g., `shadow-[0_100px_80px_rgba(0,0,0,0.12)]`).
- **Layering**: A fixed background blur layer with 5% opacity blue wash sits behind a relative content shell.
- **Depth Cues**: radial-gradients (cyan and lime) with 3xl blurs are positioned in corners to create environmental glow.

## Shapes
- **Radii**: Consistent use of `rounded-2xl` (16px) for cards and `rounded-3xl` (24px) for large containers.
- **Pills**: Buttons and high-level badges use `rounded-full` for a friendly, modern tech aesthetic.
- **Masks**: The central hero image is masked into a perfect circle with a pulse-glow effect.

## Components
- **Navigation Bar**: A sticky, floating island component with `bg-white/90`, backdrop blur, and a cyan border. Includes a primary CTA and a client portal button.
- **Floating Info Cards**: Interactive modules featuring Lucide icons, status bars (gradients), and micro-charts (simulated by background images).
- **Metrics Grid**: A 3-column row of cards with large numerical data and hover-state color shifts.
- **Feature Articles**: Grid-based blocks with rounded-xl icon containers (`bg-secondary/30`) and descriptive typography.
- **Trust Block**: A high-contrast blue section (`bg-primary`) with glass-morphic testimonial cards and yellow star ratings.

## Page Sections
### Navigation
Sticky header with brand logo (left), center-aligned links (Expertises, Pourquoi, Méthode, Témoignages), and right-aligned CTA group. Employs `backdrop-filter: blur` and a subtle 30% primary border.

### Hero Section
A dual-column layout. Left side features a high-impact heading ("Moins de bugs, plus de business") and a multi-badge status line. Right side features a circular infrastructure image surrounded by four floating "HUD" cards representing Security, Support, Cloud Management, and Peace of Mind. Includes a "Metrics Strip" at the bottom showing intervention times and uptime.

### Expertise Grid
A split layout with a vertical heading on the left and a 2x2 grid of service cards on the right. Features a subtle "shimmer" background animation using thin horizontal/vertical lines with pulse effects.

### Process (Comment ça marche)
A horizontal ordered list showing three steps (Audit, Plan d'action, Suivi). Each step is a card with a Lucide icon in a tinted lime-yellow square.

### Testimonials
A full-width blue container with centered headings. Testimonials are displayed as dark-glass cards with yellow icon accents and white text.

### Final CTA & Footer
A simple, centered section for conversion, followed by a clean white footer with copyright info and logo.

## Motion & Interaction
- **Entrance Animations**: Fade-in-up, slide-in-left, and slide-in-right sequences with staggered delays (0.2s - 1.2s).
- **Ambient Motion**: Continuous 6-second translateY loops (`animate-float`) applied to hero cards to simulate a floating interface.
- **Pulse Effects**: Status rings and HUD glows use `glowPulse` and `ringPulse` animations.
- **Hover States**: Components scale by 1.05 and shift translateY -4px on hover, often accompanied by intensified shadows and color transitions.

## Do's and Don'ts
- **Do**: Use 30% opacity primary borders on all white containers.
- **Do**: Maintain the 0.95 line height on large headings.
- **Don't**: Use solid black text; stick to the gray scale defined in the color palette.
- **Don't**: Remove the backdrop blur from floating components, as it is essential for the depth model.

## Accessibility
- **Contrast**: High contrast ratios on primary CTAs (White on #009EE0).
- **Visual Cues**: Icons accompany all major feature blocks to provide non-textual context.
- **Structure**: Semantic header/main/section/footer tags used throughout.

## Assets
1. logo.png - Main brand identity
2. https://images.unsplash.com/photo-1558494949-ef010cbdcc31?auto=format&fit=crop&w=1200&q=80 - Hero infrastructure image
3. https://images.unsplash.com/photo-1531297484001-80022131f5a1?auto=format&fit=crop&w=300&q=80 - Cloud management thumbnail
4. https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/43264853-9376-44aa-a398-a62652895fe8_800w.jpg - Security card visualization
5. https://hoirqrkdgbmvpwutwuwj.supabase.co/storage/v1/object/public/assets/assets/4c9c7ae0-20fa-44c9-9d55-cc98205e554c_800w.jpg - Serenity card visualization

### Exported Codebase Asset Inventory
1. embed: https://fonts.googleapis.com
   Context: index.html: markup attribute; index.html: absolute url literal
2. embed: https://fonts.gstatic.com
   Context: index.html: markup attribute; index.html: absolute url literal
3. embed: https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
4. other: https://cdn.jsdelivr.net/npm/tailwindcss@3.4.1/lib/index.min.js
   Context: index.html: markup attribute; index.html: absolute url literal
5. other: https://cdn.jsdelivr.net/npm/chart.js@4.4.1/dist/chart.umd.min.js
   Context: index.html: markup attribute; index.html: absolute url literal
6. other: https://unpkg.com/lucide@latest/dist/umd/lucide.js
   Context: index.html: markup attribute; index.html: absolute url literal
7. other: https://cdn.tailwindcss.com
   Context: index.html: markup attribute; index.html: absolute url literal
8. embed: https://fonts.googleapis.com/css2?family=Geist:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
9. embed: https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
10. embed: https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
11. embed: https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
12. embed: https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700;900&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
13. embed: https://fonts.googleapis.com/css2?family=Instrument+Serif:wght@400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
14. embed: https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700;900&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
15. embed: https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
16. embed: https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
17. embed: https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700;800&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
18. embed: https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
19. embed: https://fonts.googleapis.com/css2?family=Work+Sans:wght@300;400;500;600;700;800&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
20. embed: https://fonts.googleapis.com/css2?family=PT+Serif:wght@400;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
21. embed: https://fonts.googleapis.com/css2?family=Geist+Mono:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
22. embed: https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
23. embed: https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
24. embed: https://fonts.googleapis.com/css2?family=Nunito:wght@300;400;500;600;700;800&display=swap
   Context: index.html: markup attribute; index.html: absolute url literal
25. other: /contact
   Context: index.html: markup attribute
26. other: http://www.w3.org/2000/svg
   Context: index.html: absolute url literal
