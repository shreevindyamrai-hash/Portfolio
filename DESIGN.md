---
name: Obsidian Lumina
colors:
  surface: '#0f131d'
  surface-dim: '#0f131d'
  surface-bright: '#353944'
  surface-container-lowest: '#0a0e18'
  surface-container-low: '#171b26'
  surface-container: '#1c1f2a'
  surface-container-high: '#262a35'
  surface-container-highest: '#313540'
  on-surface: '#dfe2f1'
  on-surface-variant: '#cbc3d7'
  inverse-surface: '#dfe2f1'
  inverse-on-surface: '#2c303b'
  outline: '#958ea0'
  outline-variant: '#494454'
  surface-tint: '#d0bcff'
  primary: '#d0bcff'
  on-primary: '#3c0091'
  primary-container: '#a078ff'
  on-primary-container: '#340080'
  inverse-primary: '#6d3bd7'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#ffb0cd'
  on-tertiary: '#640039'
  tertiary-container: '#f751a1'
  on-tertiary-container: '#570032'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e9ddff'
  primary-fixed-dim: '#d0bcff'
  on-primary-fixed: '#23005c'
  on-primary-fixed-variant: '#5516be'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#ffd9e4'
  tertiary-fixed-dim: '#ffb0cd'
  on-tertiary-fixed: '#3e0022'
  on-tertiary-fixed-variant: '#8c0053'
  background: '#0f131d'
  on-background: '#dfe2f1'
  surface-variant: '#313540'
typography:
  display-hero:
    fontFamily: Outfit
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Outfit
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 46px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Outfit
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Outfit
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-mono-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 4rem
  margin-tablet: 2rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system establishes a cinematic, high-precision visual language tailored for a hybrid Data Analyst and Frontend Developer portfolio. It bridges analytical rigor with creative engineering by pairing deep cosmos-inspired surfaces, layered glassmorphic textures, and concentrated photonic accents.

### Visual Philosophy
- **Aesthetic Movement:** Cyber-minimalism merged with optical glassmorphism and ambient illumination.
- **Atmosphere:** Deep midnight space punctuated by controlled neon dispersion and micro-interactions.
- **Tone & Mood:** Authoritative, high-tech, razor-sharp, and architecturally deliberate.
- **Emotional Resonance:** Visitors should perceive engineering mastery, analytical clarity, and production-grade craftsmanship at a glance.

## Colors

The palette is engineered for pure dark-mode immersion, relying on high tonal contrast between abyssal backgrounds, translucent glass planes, and spectral lighting.

### Functional Tonal Hierarchy
- **Canvas Root:** Deep Midnight Abyss (`#060913`) anchoring the entire viewport.
- **Primary Canvas / Section Fill:** Midnight Navy (`#0B0F19`) providing base contrast for modules and layouts.
- **Elevated Surfaces:** Dark Glass base (`#131B2E`) with variable alpha opacity (60% to 80%) coupled with multi-layered specular reflections.
- **Primary Glow / Accent:** Electric Violet (`#8B5CF6`) and Royal Violet (`#7C3AED`) driving principal calls to action, focus halos, and dynamic keylines.
- **Secondary / Data Accent:** Neon Cyan (`#06B6D4`) and Electric Blue (`#3B82F6`) representing telemetry, analytical metrics, and algorithmic components.
- **Tertiary Pop:** Synthetic Magenta (`#EC4899`) applied sparingly for critical status updates, highlight anchors, and live project badges.
- **Typography Base:** Hyper-contrast Pure White (`#FFFFFF`) for primary headings; Slate Ice (`#CBD5E1`) and Muted Blue-Gray (`#94A3B8`) for high-density analytical text and descriptive labels.

## Typography

The typographical architecture unites geometric expression with technical legibility:

- **Headlines & Display:** Set in Outfit. Bold, wide tracking curves combined with tight negative letter-spacing for large hero units impart a forward-leaning, cinematic stance.
- **Editorial & Body:** Set in Plus Jakarta Sans. Its open apertures and balanced proportions ensure effortless scanning across technical write-ups and project case studies.
- **Data, Telemetry & Code Meta:** Set in JetBrains Mono. Delivers precise monospaced rhythm for execution stats, stack tags, system indicators, and data schemas.

### Gradient Header Styling
Headline text styles may use background clip gradients spanning `linear-gradient(135deg, #FFFFFF 30%, #A855F7 75%, #06B6D4 100%)` on primary section headers to reinforce the photonic theme.

## Layout & Spacing

The viewport implements a structured 12-column dynamic fluid grid on desktop (max container width: 1280px), transitioning to an 8-column configuration on tablet, and a 4-column layout on mobile devices.

### Grid & Composition Rules
- **Desktop (1024px+):** 12-column grid, 1.5rem (`24px`) gutters, clamped side margins with an outer bounding container.
- **Tablet (768px – 1023px):** 8-column grid, 1.25rem (`20px`) gutters, 2rem (`32px`) lateral margins.
- **Mobile (320px – 767px):** 4-column layout, 1rem (`16px`) gutters, 1.25rem (`20px`) edge margins.
- **Section Cadence:** Vertical breathing room between portfolio chapters is governed by `space-3xl` (`96px`), preventing visual noise across complex interactive modules.

## Elevation & Depth

Visual hierarchy does not use drop shadows. Instead, depth is achieved through optical light refractions, luminous borders, and directional backdrops.

### Layer Stack Tiers
1. **Tier 0 (Root Ground):** `#060913` with subtle radial gradient light-leaks (`radial-gradient(ellipse at 50% -20%, rgba(139,92,246,0.15), transparent 70%)`).
2. **Tier 1 (Glass Panes & Cards):** Background `rgba(19, 27, 46, 0.65)`, backdrop filter blur of `20px`, accompanied by a primary light edge: `1px solid rgba(255, 255, 255, 0.08)`.
3. **Tier 2 (Interactive Hover / Focused Panels):** Background `rgba(19, 27, 46, 0.85)`, backdrop filter blur of `32px`, elevated keyline `1px solid rgba(99, 102, 241, 0.4)`. Outer illumination via radial glow: `box-shadow: 0 0 30px -5px rgba(139, 92, 246, 0.25), inset 0 1px 1px 0 rgba(255, 255, 255, 0.15)`.
4. **Tier 3 (Floating HUD Navigation & Modals):** Background `rgba(6, 9, 19, 0.80)`, backdrop filter blur of `24px`, micro-border `rgba(255, 255, 255, 0.12)`, anchored by a soft ambient shadow `0 20px 40px -15px rgba(0, 0, 0, 0.7)`.

## Shapes

The geometric framework follows a balanced curvature model (Radius Base: `0.5rem` / `8px`):

- **Micro Badges & Stack Tags:** Continuous full-pill radius (`9999px`) to offset card corners.
- **Cards, Preview Modules, Visual Displays:** `rounded-lg` (`1rem` / `16px`) to ensure softened glass silhouettes.
- **Interactive Buttons & Form Inputs:** Balanced curvature (`0.625rem` / `10px`) offering tactile affordance.
- **Persistent Floating Navigation Dock:** Pill-shaped (`9999px`) for a clean, floating hardware aesthetic.

## Components

### Buttons
- **Primary Action:** Solid violet-to-cyan subtle angle gradient (`linear-gradient(135deg, #8B5CF6 0%, #6366F1 100%)`) with white text, micro white top inset border (`inset 0 1px 0 rgba(255,255,255,0.3)`), and high-illumination hover transition.
- **Secondary / Ghost Glass:** `rgba(255,255,255,0.03)` surface with `1px solid rgba(255,255,255,0.12)` border. On hover, border shifts to `rgba(6, 182, 212, 0.5)` with text color transitioning to `#06B6D4`.

### Interactive 3D Tilt Cards & Project Showcase
- Built on `rgba(19, 27, 46, 0.7)` with `backdrop-filter: blur(24px)`.
- Cards implement an ambient corner radial gradient that tracks cursor movements across the surface.
- Bottom actions display integrated code repository links and live telemetry previews using monospaced micro-labels.

### Badges & Filter Chips
- Rendered in pill form using JetBrains Mono uppercase styling.
- Default: `rgba(255,255,255,0.04)` fill, `1px solid rgba(255,255,255,0.08)` border, text `#94A3B8`.
- Active / Live Indicator: `rgba(139, 92, 246, 0.15)` fill with glowing pulse dot (`#EC4899` or `#06B6D4`) and cyan/violet illuminated border.

### Floating HUD Navigation
- Suspended dock centered at the top or bottom of the viewport with fixed coordinates.
- Encased in dark frosted glass (`rgba(6, 9, 19, 0.75)`, blur: `20px`, border: `rgba(255, 255, 255, 0.1)`).
- Nav items display glowing pill backplates upon hover and active state selection.

### Form Inputs & Terminal Controls
- Inputs feature deep slate background wells (`#090D16`) with inset shadow and thin perimeter stroke (`rgba(255, 255, 255, 0.08)`).
- Focused State: Outer glow via `box-shadow: 0 0 0 2px rgba(139, 92, 246, 0.4)` with border shifting to `#8B5CF6`.
- Monospaced field helper annotations and validation tokens.

### Document & Data Preview Cards
- Metric callout blocks displaying oversized numerical statistics in Outfit Bold, accompanied by micro trend arrows in neon cyan/magenta and monospaced variable labels.