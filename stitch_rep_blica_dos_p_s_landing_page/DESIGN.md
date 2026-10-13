---
name: Bahia Coastal Minimal
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#43474d'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#74777e'
  outline-variant: '#c4c6ce'
  surface-tint: '#49607c'
  primary: '#00162c'
  on-primary: '#ffffff'
  primary-container: '#122b44'
  on-primary-container: '#7b93b1'
  inverse-primary: '#b1c8e8'
  secondary: '#a33d23'
  on-secondary: '#ffffff'
  secondary-container: '#ff8162'
  on-secondary-container: '#731a04'
  tertiary: '#001914'
  on-tertiary: '#ffffff'
  tertiary-container: '#003028'
  on-tertiary-container: '#5a9d8e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b1c8e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#ffdad2'
  secondary-fixed-dim: '#ffb4a2'
  on-secondary-fixed: '#3c0700'
  on-secondary-fixed-variant: '#83260e'
  tertiary-fixed: '#abf0df'
  tertiary-fixed-dim: '#90d3c4'
  on-tertiary-fixed: '#00201b'
  on-tertiary-fixed-variant: '#005045'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  display-hero:
    fontFamily: Epilogue
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Epilogue
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Epilogue
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Epilogue
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Epilogue
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Epilogue
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
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
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-tag:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.06em
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The visual identity channels the luminous warmth, coastal ease, and cultural vibrancy of Salvador, Bahia, while maintaining the polished restraint of an accessible premium retail brand. 

The aesthetic sits at the intersection of **Contemporary Coastal Warmth** and **Airy Modern Retail**. It rejects clichéd tropical kitsch in favor of architectural elegance: generous breathing room, clean lines softened by gentle contours, high-end editorial product presentation, and rich sun-baked mineral tones. 

The experience must evoke the feeling of bare feet on warm sand followed by the shade of a breezy oceanfront veranda: effortless comfort, authentic welcome, barefoot sophistication, and uncompromising quality.

## Colors

The palette directly references the coastline and historic architecture of Salvador:

- **Deep Navy (`#122B44`)**: The primary brand anchor representing the deep Atlantic waters along the Bay of All Saints. Provides grounding contrast, trust, and premium structure. Used for primary text, structured buttons, and dominant headers.
- **Terracotta Coral (`#E76F51`)**: The vibrant accent reminiscent of colonial roof tiles, sunsets over Barra, and tropical warmth. Reserved for high-value interactive states, sale tags, cart additions, and seasonal callouts.
- **Palm Coastal Green (`#2A6F62`)**: The tertiary balance reflecting coastal resting vegetation, organic textures, and comfort benefits (e.g., orthopedic/natural line callouts).
- **Warm Sand Neutral (`#F8F5F0`)**: The default canvas surface, substituting harsh clinical white with a calm, tactile warmth that reduces glare on mobile screens.

Supporting sub-shades:
- `surface-subtle`: `#F3ECE1` for grouped sections, background tiers, and nested cards.
- `surface-border`: `#E5DCD0` for whisper-soft structural boundaries.
- `text-muted`: `#5E6D7E` for secondary descriptions and specifications.

## Typography

The pairing reconciles editorial confidence with high-conversion e-commerce clarity:

- **Epilogue** commands displays and section headers. Its geometric yet expressive rhythm brings an editorial, boutique warmth reminiscent of artisanal craft and tropical design magazines without compromising punch.
- **Plus Jakarta Sans** governs functional content, navigation, pricing, and filters. Its open counters and friendly curves ensure effortless legibility across dense footwear spec sheets, sizing tables, and mobile checkout flows.

## Layout & Spacing

The layout employs a responsive 12-column grid system (desktop) collapsing into 6 columns (tablet) and 4 columns (mobile), constrained within an optimal max content width of `1280px`.

- **Generous Voids**: Footwear imagery requires perimeter breathing room to highlight contour, leather grain, and sole textures. Card internal padding defaults to `space-lg` (`1.5rem`) on desktop and `space-md` (`1rem`) on compact displays.
- **Asymmetric Section Breaks**: Alternate sections between standard `neutral` (`#F8F5F0`) and `surface-subtle` (`#F3ECE1`) with vertical intervals of `space-xl` (`2.5rem`) to create effortless visual pacing without relying on hard divider lines.

## Elevation & Depth

To sustain an organic, sunlit atmosphere, elevation avoids sterile gray drop shadows in favor of **ambient, warm-tinted light diffusion**:

- **Ground Level (Base Canvas)**: Flat `#F8F5F0` background.
- **Level 1 (Product Cards & Content Containers)**: Elevated via subtle contrast against sand background with an ultra-soft amber-marine ambient shadow: `0 4px 20px -2px rgba(18, 43, 68, 0.05)`.
- **Level 2 (Hover States, Quick-View & Dropdowns)**: Lifted using `0 12px 32px -4px rgba(18, 43, 68, 0.09)`.
- **Level 3 (Cart Drawers & Modals)**: Floated with `0 24px 48px -8px rgba(18, 43, 68, 0.16)`, paired with a tinted backdrop scrim (`rgba(18, 43, 68, 0.40)`) with `backdrop-filter: blur(4px)`.
- **Structural Outlines**: When borders are needed for form fields or disabled elements, apply `1px solid #E5DCD0` to preserve the tactile feel of raw cotton and woven raffia.

## Shapes

The interface embraces organic curvature without feeling juvenile:

- **Tokens**: `rounded-md` (`0.5rem` / `8px`) for standard inputs, small buttons, and tags. `rounded-lg` (`1rem` / `16px`) for product cards, promotional banners, and filter sheets. `rounded-xl` (`1.5rem` / `24px`) for hero display vessels and modal containers.
- **Pill Exception**: Size selector pills, active filter chips, and primary CTA buttons use full pill radii (`9999px`) to echo the rounded contours of straps, soles, and smooth beach stones.

## Components

### Buttons
- **Primary ("Adicionar à Sacola")**: Solid Deep Navy (`#122B44`) fill with clean white typography (`#FFFFFF`). Full pill shape, padding `14px 28px`. Hover lifts to `#1B3E61` with subtle ambient shadow.
- **Accent ("Comprar Agora")**: Terracotta Coral (`#E76F51`) background, white text. Reserved for decisive conversion actions. Hover shifts to `#D94A38`.
- **Secondary / Outline**: Transparent fill, 1.5px solid border in `#122B44`, text `#122B44`. Hover fills with `#F3ECE1`.

### Product Cards
- **Container**: Crisp sand/white surface (`#FFFFFF` or `#FCFAF7`), `rounded-lg` (16px), bordered in `1px solid #EFE8DE`.
- **Visual Staging**: Footwear photography placed on a neutral `#F4EFE6` pedestal background with subtle perspective shadow.
- **Badge Overlay**: Floating pill tags in upper corners. "Feito na Bahia" or "Linha Couro" in Palm Green (`#2A6F62` with `#EAF3F0` background); discount tags in Terracotta (`#E76F51` with `#FDEEEB` background).

### Sizing Chips & Selectors
- **Footwear Size Tiles (34, 35, 36...)**: Rounded square tiles (`44x44px`), `rounded-md` (8px). 
- **Default State**: Surface `#FFFFFF`, border `1px solid #E5DCD0`, text `#122B44`.
- **Selected State**: Deep Navy (`#122B44`) fill, white text, zero border.
- **Out of Stock**: Faded text `#B0BAC4`, diagonal strike-through, surface `#F3ECE1`.

### Input Fields
- **Search & Checkout Fields**: Height `48px`, background `#FFFFFF`, border `1.5px solid #E5DCD0`, text in `#122B44`, placeholder in `#8C9BA8`. Focus state introduces a crisp `#122B44` border and an ambient terracotta glow (`rgba(231, 111, 81, 0.15)`).

### Footwear Spec & Material Badges
- **Comfort & Sole Indicators**: Compact horizontal badges with dual-tone treatment (e.g., "Palmilha Anatômica", "Solado Antiderrapante") styled in `label-tag` typography with Palm Green icons (`#2A6F62`) over muted sage backdrops.