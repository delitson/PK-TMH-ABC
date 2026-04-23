---
name: Serene Clinical Glass
colors:
  surface: '#f6fafb'
  surface-dim: '#d7dbdb'
  surface-bright: '#f6fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f5'
  surface-container: '#ebeeef'
  surface-container-high: '#e5e9e9'
  surface-container-highest: '#dfe3e4'
  on-surface: '#181c1d'
  on-surface-variant: '#3e494a'
  inverse-surface: '#2d3132'
  inverse-on-surface: '#eef1f2'
  outline: '#6e797b'
  outline-variant: '#bdc8ca'
  surface-tint: '#006874'
  primary: '#00636e'
  on-primary: '#ffffff'
  primary-container: '#087e8b'
  on-primary-container: '#eafcff'
  inverse-primary: '#79d4e2'
  secondary: '#006b5c'
  on-secondary: '#ffffff'
  secondary-container: '#56f8db'
  on-secondary-container: '#007060'
  tertiary: '#864b15'
  on-tertiary: '#ffffff'
  tertiary-container: '#a3632c'
  on-tertiary-container: '#fff7f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#96f0ff'
  primary-fixed-dim: '#79d4e2'
  on-primary-fixed: '#001f24'
  on-primary-fixed-variant: '#004f57'
  secondary-fixed: '#5afbde'
  secondary-fixed-dim: '#2fdec2'
  on-secondary-fixed: '#00201b'
  on-secondary-fixed-variant: '#005045'
  tertiary-fixed: '#ffdcc4'
  tertiary-fixed-dim: '#ffb77f'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3902'
  background: '#f6fafb'
  on-background: '#181c1d'
  surface-variant: '#dfe3e4'
typography:
  h1:
    fontFamily: Manrope
    fontSize: 36px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Manrope
    fontSize: 30px
    fontWeight: '700'
    lineHeight: '1.25'
  h3:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
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
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  section-padding: 5rem
  bento-gap: 1.5rem
  container-max: 80rem
  inner-padding: 2rem
---

## Brand & Style
The brand personality is professional, sophisticated, and deeply reassuring, targeting health-conscious individuals seeking premium medical care. The UI evokes a sense of "clinical transparency" through a refined mix of **Modern Corporate** and **Glassmorphism**. 

The aesthetic leverages soft, aurora-like background meshes and translucent surfaces to reduce the clinical coldness typically associated with healthcare. It prioritizes clarity and trust, using high-quality imagery and a balanced, airy layout that feels both high-tech and human-centric.

## Colors
The palette is built on a foundation of "Medical Teals" and "Clean Whites." 
- **Primary & Secondary:** Deep teal and bright mint represent hygiene, health, and vitality.
- **CTA Gold:** A specific accent color (#F0A500) is reserved exclusively for primary actions (Booking, Confirming) to provide high-contrast "wayfinding" against the cool-toned background.
- **Glass Surfaces:** Backgrounds utilize a trio of gradients (Teal, Mint, and White) to create an "Aurora Mesh" effect, providing depth without visual noise.

## Typography
The system uses **Manrope** for headlines to project a modern, sturdy, and trustworthy image. **Inter** is used for body copy and UI labels for maximum legibility. 
- **Hierarchy:** Dramatic scale differences between H1 and body text create a clear content focal point.
- **Styling:** Italicized medium weights are used for subtitles to add a professional, academic touch (e.g., "Ear Nose Throat Clinic"). 
- **Labels:** Small caps with increased letter spacing are used for metadata and form labels to provide a structured, "documented" feel.

## Layout & Spacing
The layout follows a **Fixed Grid** approach for desktop, centering content within a 1280px (80rem) max-width container. 
- **Bento Grid:** Services and gallery sections utilize a "Bento Box" mosaic, creating a rhythmic, organized structure that allows for varied content density.
- **Rhythm:** Generous vertical section padding (5rem) ensures each service area feels distinct and uncrowded, reflecting the calm atmosphere of the clinic.
- **Floating Elements:** Key UI components (like the hero booking bar) break the standard flow by overlapping sections, creating a layered, 3D sense of space.

## Elevation & Depth
Depth is achieved through **Glassmorphism** and **Tactile "Clay" effects**.
- **The Glass Card:** The primary container style uses `backdrop-filter: blur(20px)`, a semi-transparent white background, and a thin `1.5px` white border. This mimics the look of high-end medical glass partitions.
- **Claymorphism:** Icons are housed in "Clay" circles—white backgrounds with subtle dual inner shadows (one dark for depth, one light for highlight) to make them appear physical and touchable.
- **Shadows:** Standard shadows are rarely used; instead, `0 8px 32px` shadows with a primary color tint (`#087E8B` at 8% opacity) provide a soft, ambient lift.

## Shapes
The shape language is dominated by high-radius curves and pills. 
- **Containers:** Large cards use 1.5rem to 2rem corner radii.
- **Feature Shapes:** Special elements like the doctor's portrait use asymmetric radii (e.g., `40px`) or slight rotations (`rotate-3`) to create a more dynamic, less rigid visual field.
- **Pills:** All buttons and small status chips use a "Full" (pill-shaped) radius to reinforce a friendly, safe, and approachable clinical environment.

## Components
- **Buttons:** 
  - *Primary (CTA):* Gold background, no border, white text, bold weight.
  - *Secondary:* White background, 2px primary border, primary text.
  - *Interaction:* All buttons should translate -2px on hover with a subtle glow shadow.
- **Input Fields:** 
  - Glass-style: `bg-white/40` with no border and `rounded-xl`. Focus states should use a primary color ring.
- **Bento Cards:** 
  - Rectangular or square containers with glass effects. Icons within cards should always use the "Clay" style.
- **Status Chips:** 
  - Small, pill-shaped markers used for ratings (Google 4.9) or opening hours. Use secondary container colors for "positive" statuses.
- **Floating Action Buttons (FAB):** 
  - Circular buttons in the bottom-right corner for quick access to Zalo or Booking, using high-visibility brand colors.