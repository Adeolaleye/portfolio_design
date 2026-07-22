---
name: Tech-Luxe Portfolio
colors:
  surface: '#10141a'
  surface-dim: '#10141a'
  surface-bright: '#353940'
  surface-container-lowest: '#0a0e14'
  surface-container-low: '#181c22'
  surface-container: '#1c2026'
  surface-container-high: '#262a31'
  surface-container-highest: '#31353c'
  on-surface: '#dfe2eb'
  on-surface-variant: '#c7c4d7'
  inverse-surface: '#dfe2eb'
  inverse-on-surface: '#2d3137'
  outline: '#908fa0'
  outline-variant: '#464554'
  surface-tint: '#c0c1ff'
  primary: '#c0c1ff'
  on-primary: '#1000a9'
  primary-container: '#8083ff'
  on-primary-container: '#0d0096'
  inverse-primary: '#494bd6'
  secondary: '#ffb95f'
  on-secondary: '#472a00'
  secondary-container: '#ee9800'
  on-secondary-container: '#5b3800'
  tertiary: '#ffb783'
  on-tertiary: '#4f2500'
  tertiary-container: '#d97721'
  on-tertiary-container: '#452000'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e1e0ff'
  primary-fixed-dim: '#c0c1ff'
  on-primary-fixed: '#07006c'
  on-primary-fixed-variant: '#2f2ebe'
  secondary-fixed: '#ffddb8'
  secondary-fixed-dim: '#ffb95f'
  on-secondary-fixed: '#2a1700'
  on-secondary-fixed-variant: '#653e00'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#ffb783'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#703700'
  background: '#10141a'
  on-background: '#dfe2eb'
  surface-variant: '#31353c'
  slate-surface: '#1E293B'
  glass-border: rgba(255, 255, 255, 0.1)
  text-muted: '#94A3B8'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: '1.2'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The design system is engineered for a senior AI Product Manager, balancing technical authority with high-fidelity luxury. The brand personality is "Intelligent Minimalism"—it communicates complex AI concepts through a lens of clarity, precision, and executive-level polish.

The visual style is **Corporate / Modern** with a **Minimalist** foundation. It prioritizes significant whitespace to allow "room for thought," using thin borders and subtle gradients to define structure rather than heavy shadows. The aesthetic avoids the clutter of traditional tech dashboards, opting instead for a refined, gallery-like presentation of work that feels both innovative and deeply reliable.

## Colors

The palette is rooted in a "Deep Midnight" environment, creating a high-contrast backdrop that makes content feel luminous. 

- **Primary (Electric Indigo):** Used for interactive elements, focus states, and primary CTAs. It represents the "energy" of AI.
- **Secondary (Amber/Gold):** Used sparingly as a "success" or "highlight" accent, providing a warm, premium contrast to the cool-toned primary colors.
- **Neutral (Midnight & Slate):** The foundational colors for backgrounds and surfaces. Layering is achieved by transitioning from `#0A0E14` (base) to `#1E293B` (containers).

All gradients should be subtle, transitioning from the primary indigo to a slightly more transparent or darker variant to maintain a "glow" effect without becoming neon or overwhelming.

## Typography

Typography is used to establish a clear information hierarchy. **Plus Jakarta Sans** provides a modern, geometric feel for headings that looks premium at large scales. **Inter** is utilized for body text to ensure maximum readability and a neutral, professional tone.

**JetBrains Mono** is introduced for labels, metadata, and "tech" details (like AI model parameters or dates), reinforcing the technical background of the PM. 

Headlines should use tight letter-spacing to feel more cohesive, while labels should be tracked out for a technical, "schematic" appearance.

## Layout & Spacing

This design system uses a **fixed grid** layout for desktop (12 columns) and a **fluid grid** for mobile. 

The "Luxe" feel is achieved through exaggerated vertical spacing. Section gaps are generous (`120px`) to prevent cognitive overload. Content containers should be centered with a maximum width of `1200px` to maintain a comfortable line length for case studies. 

On mobile, margins reduce to `20px` and the 12-column grid collapses into a single column, with section spacing reduced to `64px` to maintain momentum.

## Elevation & Depth

Depth is articulated through **Tonal Layers** and **Low-Contrast Outlines**. Instead of traditional drop shadows, this design system uses "Surface Stacking":

1.  **Level 0 (Background):** Pure `#0A0E14`.
2.  **Level 1 (Cards/Sections):** `#1E293B` with a `1px` solid border using `rgba(255, 255, 255, 0.1)`.
3.  **Level 2 (Active/Hover):** A subtle backdrop blur (12px) combined with a primary color "inner glow" or a slightly brighter border.

Shadows, if used at all, should be extremely soft and tinted with the primary indigo, appearing more like a "glow" from beneath the element than a shadow cast by an external light source.

## Shapes

The shape language is **Soft (Level 1)**. Elements like buttons and cards use a `0.25rem` (4px) base radius. This creates a precise, architectural feel that is modern without feeling "bubbly" or overly consumer-facing. 

Large-scale components like hero image containers may use `rounded-lg` (8px) to soften the layout slightly, but the overall system should lean toward sharp, clean lines to emphasize professional rigor.

## Components

### Buttons
Primary buttons use a solid Electric Indigo background with white text. Hover states should feature a subtle "glow" using a `0px 0px 15px rgba(99, 102, 241, 0.4)` box shadow. Secondary buttons are "ghost" style with a 1px border and no fill.

### Input Fields
Inputs are dark-themed with `#1E293B` backgrounds. On focus, the border transitions from the default muted slate to a solid Electric Indigo, accompanied by a 2px outer glow.

### Cards
Cards are the primary container for case studies. They must feature a subtle gradient border or a semi-transparent background to evoke a "glass" effect. All cards should have a consistent internal padding of `32px`.

### Chips / Tags
Used for "Skills" or "Tools." These should use the **label-caps** typography style. They feature a dark indigo background with a 1px primary-colored border.

### Progress Indicators
For AI "status" or project completion, use thin, linear bars. Avoid circular charts. Use the primary indigo for the progress fill and the amber accent for "critical milestones."