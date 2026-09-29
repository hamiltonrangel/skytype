---
name: Retro-Futuristic Arcade
colors:
  surface: '#170d2c'
  surface-dim: '#170d2c'
  surface-bright: '#3e3455'
  surface-container-lowest: '#120827'
  surface-container-low: '#201635'
  surface-container: '#241a39'
  surface-container-high: '#2f2444'
  surface-container-highest: '#3a2f50'
  on-surface: '#eaddff'
  on-surface-variant: '#cbc4cd'
  inverse-surface: '#eaddff'
  inverse-on-surface: '#352b4b'
  outline: '#958f97'
  outline-variant: '#49454c'
  surface-tint: '#d1c0e2'
  primary: '#d1c0e2'
  on-primary: '#372b46'
  primary-container: '#0f051d'
  on-primary-container: '#827392'
  inverse-primary: '#665976'
  secondary: '#ffb1c5'
  on-secondary: '#65002f'
  secondary-container: '#e30071'
  on-secondary-container: '#fffbff'
  tertiary: '#00dbe9'
  on-tertiary: '#00363a'
  tertiary-container: '#000c0e'
  on-tertiary-container: '#00868f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#eedcff'
  primary-fixed-dim: '#d1c0e2'
  on-primary-fixed: '#211630'
  on-primary-fixed-variant: '#4e415d'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#ffb1c5'
  on-secondary-fixed: '#3f001b'
  on-secondary-fixed-variant: '#8f0045'
  tertiary-fixed: '#7df4ff'
  tertiary-fixed-dim: '#00dbe9'
  on-tertiary-fixed: '#002022'
  on-tertiary-fixed-variant: '#004f54'
  background: '#170d2c'
  on-background: '#eaddff'
  surface-variant: '#3a2f50'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: JetBrains Mono
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Space Grotesk
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  margin: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels a modern arcade minimal aesthetic, blending nostalgic retro-futuristic HUD elements with clean, contemporary minimalism. The brand personality is electric, precise, and immersive. 

### Target Audience
Gamers, digital creators, and enthusiasts of synthwave and cyber-aesthetic interfaces who demand high performance wrapped in striking visual design.

### Emotional Response
Evokes a sense of high-energy focus, sleek technological wonder, and the thrill of the arcade floor filtered through a refined, minimalist lens.

### Design Style
A hybrid of **Retro / Vaporwave** and **Minimalism**. The interface relies on deep twilight dark backgrounds, glowing sunset gradients, and sharp, vibrant neon accents for immediate typing feedback and active states, all anchored by generous whitespace and structural grid alignment.

## Colors

The color palette is built on a foundation of deep twilight void tones, energized by warm sunset gradients and electric neon feedback vectors.

- **Primary (`#0F051D`):** The deep space-black void serving as the primary canvas background.
- **Secondary (`#FF2A85`):** Hot magenta neon for critical alerts, primary interactive actions, and passionate highlights.
- **Tertiary (`#00F0FF`):** Cyan laser neon reserved for active typing feedback, data readouts, and focal HUD reticles.
- **Neutral (`#1A102F`):** Deep purple-slate for surface cards, container layers, and subtle framing.
- **Gradients:** Sunset sky gradients transition smoothly from deep violet (`#2B0B3A`) to electric coral (`#FF5E62`) across primary hero containers and header bands.

## Typography

Typography bridges futuristic utility with geometric punch. `Space Grotesk` drives all headings and structural labels with its wide, sci-fi geometric stance, while `JetBrains Mono` commands the body text and interactive data fields, reinforcing the terminal-like arcade feedback loop.

### Scaling & Responsiveness
Headlines scale down gracefully on mobile viewports (e.g., `headline-xl` collapses to 36px) to maintain rigid structural boundaries without text wrapping awkwardly inside HUD frames.

## Layout & Spacing

The layout relies on a precise, strict 12-column fluid grid system engineered for dashboard-style HUD displays and immersive arcade views. 

- **Gutters & Margins:** Standardized 1.5rem gutters maintain crisp separation between modular HUD panels, while 2rem outer canvas margins ensure the interface never bleeds against screen edges.
- **Rhythm:** The spacing scale operates on a clean 4px/8px modular base, ensuring precise alignment of data readouts, borders, and interactive target zones.
- **Breakpoints:** Adapt fluidly across Mobile (< 768px, single-column reflow with stacked HUD elements), Tablet (768px - 1024px, 2-column modular split), and Desktop (> 1024px, full 12-column command center grid).

## Elevation & Depth

Elevation is achieved through a hybrid of **Tonal layers** and **Ambient neon shadows** rather than harsh black drops. 

- **Surface Tiers:** Base surfaces sit at the deepest void level (`#0F051D`), with interactive panels rising on neutral containers (`#1A102F`).
- **Glow Mechanics:** Depth and focus are communicated via low-opacity, wide-radius colored glows (using cyan `#00F0FF` and magenta `#FF2A85` tints) that emanate from active elements, simulating glowing CRT phosphors and futuristic HUD projections.
- **Borders:** Thin, high-contrast 1px outlines in neon cyan or translucent white define structural hit-boxes, maintaining a razor-sharp minimalist edge.

## Shapes

The shape language is strictly controlled with low roundedness (`1` setting, yielding 0.25rem corner radii for base elements, scaling to 0.5rem for large containers). 

This subtle rounding softens the otherwise aggressive retro-futuristic geometry, preventing accidental visual stabs while preserving the crisp, engineered precision of arcade machine bezels and digital readouts. Pill shapes are reserved exclusively for status badges and live typing feedback pills.

## Components

Every component functions as a modular HUD module, combining minimalist containers with high-impact neon feedback loops.

### Buttons
- **Primary:** Solid sunset gradient background with sharp 1px cyan borders. On hover and active states, they emit an intense cyan glow (`#00F0FF`) with high-contrast dark text.
- **Secondary:** Ghost style with transparent fill, 1px neutral border, and hot magenta text that shifts to a solid magenta background on interaction.

### Chips & Badges
- Compact pill-shaped containers (`rounded-xl`) utilizing semi-transparent neutral backgrounds with a 1px neon border. Used for telemetry tags, high scores, and active filter states.

### Lists
- Monospace data lists featuring alternating subtle background zebra striping (`#1A102F` at 40% opacity) separated by 1px dotted horizontal rules. Items highlight with a left-edge cyan accent bar on hover.

### Checkboxes & Radio Buttons
- Custom geometric shapes: Checkboxes use sharp squares that fill with an electric checkmark; radios use concentric glowing circles that pulse on selection.

### Input Fields
- Styled as terminal input lines. Deep neutral background, 1px border that shifts from neutral slate to vibrant cyan (`#00F0FF`) upon focus, accompanied by real-time neon typing feedback carets.

### Cards
- Modular HUD panels featuring clipped top-right corners (via clip-path or subtle radius), thin 1px glowing borders, and optional sunset gradient header accents.

### Specialized Components
- **HUD Reticles:** Decorative corner targeting brackets that frame active workspace modules.
- **Score Ticker:** Monospace rolling digit displays with phosphor bloom effects for real-time metrics.