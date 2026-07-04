---
name: Vivid Horizon
colors:
  surface: '#f9f9ff'
  surface-dim: '#d4daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e8eeff'
  surface-container-high: '#e3e8f9'
  surface-container-highest: '#dde2f3'
  on-surface: '#161c27'
  on-surface-variant: '#3b4949'
  inverse-surface: '#2a303d'
  inverse-on-surface: '#ecf0ff'
  outline: '#6b7a7a'
  outline-variant: '#bac9c9'
  surface-tint: '#00696b'
  primary: '#00696b'
  on-primary: '#ffffff'
  primary-container: '#00ced1'
  on-primary-container: '#005354'
  inverse-primary: '#2ddbde'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fd8b00'
  on-secondary-container: '#603100'
  tertiary: '#006d3d'
  on-tertiary: '#ffffff'
  tertiary-container: '#71cc92'
  on-tertiary-container: '#00552f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#5af8fb'
  primary-fixed-dim: '#2ddbde'
  on-primary-fixed: '#002020'
  on-primary-fixed-variant: '#004f51'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#9af6b8'
  tertiary-fixed-dim: '#7ed99e'
  on-tertiary-fixed: '#00210f'
  on-tertiary-fixed-variant: '#00522d'
  background: '#f9f9ff'
  on-background: '#161c27'
  surface-variant: '#dde2f3'
typography:
  display-lg:
    fontFamily: anybody
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: 0.04em
  display-lg-mobile:
    fontFamily: anybody
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: anybody
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: anybody
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: 0.01em
  headline-md:
    fontFamily: anybody
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  body-lg:
    fontFamily: plusJakartaSans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: plusJakartaSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  label-md:
    fontFamily: plusJakartaSans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: plusJakartaSans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1440px
  gutter-desktop: 32px
  gutter-mobile: 16px
  margin-desktop: 80px
  margin-mobile: 24px
  section-gap: 120px
---

## Brand & Style

This design system embodies the spirit of high-end, high-energy global exploration. It is designed for a premium travel agency that prioritizes discovery, luxury, and momentum. The visual language balances the "expensive" feel of luxury editorial layouts with the vibrant energy of tropical destinations.

The aesthetic follows a **Modern Minimalism** approach enriched with **Glassmorphism** and high-fidelity depth. Large, immersive imagery is the primary driver of the experience, supported by generous whitespace that allows content to breathe. The emotional response should be one of "aspirational excitement"—clean, professional, and undeniably forward-moving. Motion should be fluid and purposeful, mimicking the transition of travel itself.

## Colors

The palette is inspired by the natural transitions of a tropical day: the midday Caribbean sea, a sunset horizon, and lush coastal flora. 

- **Primary (Aqua Blue):** Used for primary actions, progress indicators, and key brand highlights. It represents clarity and the ocean.
- **Secondary (Sunset Orange):** A high-energy accent for CTAs, notifications, and "Book Now" moments. It provides a warm contrast to the cooler primary tones.
- **Tertiary (Palm Green):** Used for secondary features, success states, and eco-tourism labeling.
- **Neutral/Surface:** In light mode, we use pure whites and cool grays. In dark mode, we shift to a deep navy (#0A192F) rather than pure black to maintain a "midnight sea" depth. 

Accent glows in dark mode should use a 20% opacity blur of the primary or secondary colors to simulate tropical bioluminescence.

## Typography

The typography strategy relies on the high-energy, variable nature of **Anybody** for cinematic impact. Headings should utilize wide tracking and bold weights to evoke the feeling of a premium travel magazine or film credits.

**Plus Jakarta Sans** serves as the body face, chosen for its friendly yet modern geometric proportions which ensure high legibility during the booking flow. For "Display" and "Headline" levels, use uppercase transformations sparingly to maintain the "expensive" editorial aesthetic. Ensure that wide tracking in headlines is reduced as the screen size shrinks to maintain readability on mobile devices.

## Layout & Spacing

This design system utilizes a **Fluid Grid** model built on an 8px base unit. The layout philosophy is centered on "The Horizon"—emphasizing horizontal expansiveness.

- **Desktop:** A 12-column grid with wide 80px margins and 32px gutters. This creates the "expensive" whitespace required for premium positioning.
- **Tablet:** 8-column grid with 40px margins.
- **Mobile:** 4-column grid with 24px margins.

Vertical rhythm is intentionally loose. Section gaps should be aggressive (120px+) to ensure that users focus on one destination or offer at a time. Content reflow should prioritize large, edge-to-edge media cards that break the grid slightly to create a sense of scale.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and **Glassmorphism**. Surfaces do not simply sit on top of each other; they float within an environment.

1.  **Level 0 (Base):** Pure white or deep navy.
2.  **Level 1 (Cards):** Subtle, extra-diffused shadows (Offset: 0, 8px, Blur: 30px, Opacity: 4%) with a thin 1px neutral border.
3.  **Level 2 (Modals/Overlays):** Glassmorphism with a `backdrop-filter: blur(20px)` and a 10% white semi-transparent background.
4.  **Floating Elements:** Interactive elements (like "Book" buttons) use a tinted shadow based on the button color to create a "glow" effect, suggesting energy and interaction.

## Shapes

The shape language is **Rounded**, reflecting the soft edges of nature and the approachability of a luxury service. Standard UI elements (cards, inputs) use a 0.5rem (8px) radius. Larger display elements or hero image containers should use `rounded-xl` (1.5rem / 24px) to create a distinct, frame-like appearance for travel photography.

## Components

### Buttons
Primary buttons use a heavy weight of the secondary color (#FF8C00) to ensure they pop against the aqua/white backgrounds. They should have a subtle hover lift effect. Secondary buttons should be ghost-style with a primary-colored border.

### Chips & Badges
Used for destination categories (e.g., "Beach", "Alpine"). These use high-saturation backgrounds with low-opacity (15%) to allow the color to be present without overwhelming the text.

### Cards
Travel destination cards are the hero component. They must feature a high-aspect-ratio image, a "Glass" header for the price or rating, and use the `rounded-xl` shape. The transition on hover should involve a slight image scale-up (1.05x) and an intensified ambient shadow.

### Input Fields
Inputs are clean with a 1px bottom border in light mode, or a fully enclosed soft-gray box with 0.5rem rounding. On focus, the border transitions to the Primary Aqua Blue with a soft outer glow.

### Destination Progress / Timeline
A custom vertical or horizontal line component using the Primary color to track a multi-day itinerary, utilizing small "sun" icons as nodes to tie back to the brand energy.