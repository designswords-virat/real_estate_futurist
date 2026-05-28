---
name: Aetheris Narrative
colors:
  surface: '#0e141a'
  surface-dim: '#0e141a'
  surface-bright: '#343a40'
  surface-container-lowest: '#090f14'
  surface-container-low: '#161c22'
  surface-container: '#1a2026'
  surface-container-high: '#242b31'
  surface-container-highest: '#2f353c'
  on-surface: '#dde3eb'
  on-surface-variant: '#bacac7'
  inverse-surface: '#dde3eb'
  inverse-on-surface: '#2b3137'
  outline: '#859492'
  outline-variant: '#3b4948'
  surface-tint: '#33dcd3'
  primary: '#ffffff'
  on-primary: '#003734'
  primary-container: '#5df9ef'
  on-primary-container: '#00716b'
  inverse-primary: '#006a65'
  secondary: '#a0caff'
  on-secondary: '#003259'
  secondary-container: '#3694ec'
  on-secondary-container: '#002b4e'
  tertiary: '#ffffff'
  on-tertiary: '#30009b'
  tertiary-container: '#e6deff'
  on-tertiary-container: '#6544e9'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#5df9ef'
  primary-fixed-dim: '#33dcd3'
  on-primary-fixed: '#00201e'
  on-primary-fixed-variant: '#00504c'
  secondary-fixed: '#d2e4ff'
  secondary-fixed-dim: '#a0caff'
  on-secondary-fixed: '#001c37'
  on-secondary-fixed-variant: '#00497e'
  tertiary-fixed: '#e6deff'
  tertiary-fixed-dim: '#c9beff'
  on-tertiary-fixed: '#1b0062'
  on-tertiary-fixed-variant: '#4617cb'
  background: '#0e141a'
  on-background: '#dde3eb'
  surface-variant: '#2f353c'
typography:
  display-xl:
    fontFamily: anybody
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 90px
    letterSpacing: 0.05em
  headline-lg:
    fontFamily: anybody
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: anybody
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  title-md:
    fontFamily: spaceGrotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: 0.1em
  body-lg:
    fontFamily: hankenGrotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: hankenGrotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-tech:
    fontFamily: spaceGrotesk
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
spacing:
  unit: 8px
  gutter: 32px
  margin-desktop: 64px
  margin-mobile: 24px
  container-max: 1440px
---

## Brand & Style

This design system is engineered for high-end architectural visualization and futuristic digital environments. The brand personality is **visionary, cinematic, and intellectually rigorous**, bridging the gap between physical structural design and high-fidelity sci-fi interfaces.

The visual style is **Futuristic Glassmorphism**. It utilizes deep, immersive voids contrasted against razor-sharp holographic elements. Every interface layer should feel like a projected glass pane, combining the weightlessness of light with the structural integrity of modern architecture. The emotional response is one of "calculated awe"—a feeling that the user is interacting with an intelligent, advanced operating system for the built environment.

## Colors

The palette is rooted in a "Deep Space" foundation to maximize the luminosity of accent colors.

- **Foundational Voids:** The background uses a pure Space Black (#050505) to provide infinite depth. Surfaces utilize Graphite Gray (#161616) at varying opacities to create the illusion of physical mass within a digital void.
- **Luminous Accents:** Neon Cyan and Electric Blue serve as the primary functional accents for active states and data visualization. Deep Violet is reserved for secondary highlights and depth-mapping glows.
- **Metallic Neutrals:** Metallic Silver (#BFC5CD) is the primary text color, providing a matte, technical feel that contrasts with the high-gloss UI elements.

## Typography

The typographic scale is designed for maximum impact and technical precision.

- **Headlines:** Use **Anybody** with expanded width and heavy weights. It provides the "Monumental" architectural feel required for cinematic storytelling.
- **Sub-headers & UI Labels:** **Space Grotesk** is used for technical data, navigation, and UI labels. Its geometric quirks reinforce the "sci-fi interface" aesthetic.
- **Body Copy:** **Hanken Grotesk** provides a clean, contemporary neo-grotesque foundation, ensuring high readability against dark, translucent backgrounds.

All headers should utilize wide letter-spacing (tracking) to mimic high-end architectural blueprints and gallery signage.

## Layout & Spacing

This design system employs a **Geometric Fluid Grid** based on an 8px square rhythm.

- **Desktop:** A 12-column grid with wide 32px gutters to allow the "glass" panels breathing room. Margins are generous (64px) to create an editorial, gallery-like feel.
- **Experimental Compositions:** Elements should frequently break the grid or overlap with heavy use of `z-index` to simulate a 3D interface environment. 
- **Adaptation:** On mobile, the grid collapses to 4 columns. Large "Display" type should scale aggressively (using the defined mobile alternatives) to ensure the cinematic impact remains on smaller viewports.

## Elevation & Depth

Depth is not communicated through traditional shadows, but through **Luminosity and Refraction**.

- **Glassmorphism:** All primary containers use a 10% to 20% opacity white fill with a heavy backdrop-blur (minimum 20px). 
- **Structural Outlines:** Instead of drop shadows, use 1px semi-transparent "inner-glow" borders (Hex #FFFFFF at 15% opacity). 
- **Ambient Glows:** Higher elevation levels are indicated by a "neon underglow" using the Primary Cyan or Tertiary Violet. These should be highly diffused (40px-80px blur) and low opacity (20%) to simulate light leaking from beneath a glass panel.

## Shapes

The shape language is **Precision-Architectural**. 

- **Primary Radius:** Use a "Sharp" (0px) setting for all primary structural elements, containers, and image masks to evoke a sense of technical drawing and structural rigidity.
- **Micro-interactions:** Small UI elements like buttons or tags may use a 45-degree "chamfered corner" (clipped corner) aesthetic rather than rounding to maintain the sci-fi industrial tone.
- **Dividers:** Use ultra-thin (0.5pt to 1pt) lines with gradient fades at the ends to simulate laser-etched dividers.

## Components

### Interactive Panels
Floating glass panels are the core container. They must feature a subtle top-left highlight and a 1px border. Background blur is mandatory to maintain legibility over cinematic background imagery.

### Buttons & Navigation
Buttons are "Holographic Triggers"—use transparent backgrounds with a solid 1px Cyan border. On hover, the button should fill with a low-opacity Cyan glow and the text should shift to Space Black.

### Project Cards
Cards for showcasing architecture should be edge-to-edge imagery with a glass overlay at the bottom 30%. Typography within cards should use the `label-tech` style for metadata (sq. footage, location, year).

### Input Fields
Inputs are minimalist underlines with a glowing "cursor" focus state. When active, the entire underline should pulse with an Electric Blue glow.

### Technical HUD
Add "Heads-Up Display" elements like coordinate tickers, spinning geometric loaders, and small monospaced data points in corners to reinforce the intelligent system narrative.