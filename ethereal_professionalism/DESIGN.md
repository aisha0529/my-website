---
name: Ethereal Professionalism
colors:
  surface: '#fff8f3'
  surface-dim: '#e4d8cb'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fef2e4'
  surface-container: '#f8ecdf'
  surface-container-high: '#f2e6d9'
  surface-container-highest: '#ede1d4'
  on-surface: '#201b13'
  on-surface-variant: '#4d4353'
  inverse-surface: '#362f27'
  inverse-on-surface: '#fbefe2'
  outline: '#7e7384'
  outline-variant: '#cfc2d5'
  surface-tint: '#8333c6'
  primary: '#4c0080'
  on-primary: '#ffffff'
  primary-container: '#6a0dad'
  on-primary-container: '#d4a1ff'
  inverse-primary: '#dfb7ff'
  secondary: '#944930'
  on-secondary: '#ffffff'
  secondary-container: '#fe9d7f'
  on-secondary-container: '#77321c'
  tertiary: '#3d2d2b'
  on-tertiary: '#ffffff'
  tertiary-container: '#554341'
  on-tertiary-container: '#c9b0ae'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f1daff'
  primary-fixed-dim: '#dfb7ff'
  on-primary-fixed: '#2d004f'
  on-primary-fixed-variant: '#690bac'
  secondary-fixed: '#ffdbd0'
  secondary-fixed-dim: '#ffb59e'
  on-secondary-fixed: '#3a0b00'
  on-secondary-fixed-variant: '#76321c'
  tertiary-fixed: '#f7ddda'
  tertiary-fixed-dim: '#dac1be'
  on-tertiary-fixed: '#261817'
  on-tertiary-fixed-variant: '#544341'
  background: '#fff8f3'
  on-background: '#201b13'
  surface-variant: '#ede1d4'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
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
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  section-gap: 120px
---

## Brand & Style

The brand personality is a sophisticated intersection of warmth and technological precision. Designed for a personal portfolio, the aesthetic prioritizes a "human-centric professional" vibe, moving away from cold corporate structures toward a soft, editorial experience. 

The design style is **Minimalist Glassmorphism**. It utilizes the warmth of the sand background to ground the ethereal nature of the translucent layers. High-end typography and generous whitespace ensure the content remains the focal point, while glass effects provide a sense of depth and modernity without cluttering the visual field.

## Colors

This design system uses a palette that balances high-contrast authority with soft, inviting tones. 

*   **Primary (#6A0DAD):** A deep, royal purple used for calls to action, active states, and key brand identifiers. It represents professional wisdom and creativity.
*   **Secondary (#FF9E80):** A vibrant coral reserved specifically for headings and high-level typographic hierarchy to guide the eye.
*   **Tertiary (#FFE4E1):** A misty rose used for subtle accents, hover states, and "glass" tinting.
*   **Neutral (#F0E4D7):** The foundation sand color. This replaces standard whites to provide a more "tangible" and premium feel.

Text should generally use a darkened variation of the primary color or a deep charcoal for maximum legibility against the sand and peach elements.

## Typography

The typographic system relies on **Plus Jakarta Sans** for its modern, geometric, yet friendly personality. It is the primary engine for the "Professional" aspect of the brand. All headlines use the Secondary color (#FF9E80) to create a distinct visual anchor.

**Inter** is utilized for body copy and labels to maintain a "Systematic" and "Clean" look. Its neutral characteristic balances the expressive nature of the headlines. For mobile devices, headline sizes scale down aggressively to maintain readability and prevent awkward line breaks in narrow viewports.

## Layout & Spacing

This design system follows a **Fixed Grid** approach for desktop to maintain an editorial, magazine-like structure. 

*   **Desktop:** A 12-column grid with a maximum container width of 1200px. Gutters are kept at 24px to allow for breathing room between portfolio pieces.
*   **Mobile:** A 4-column fluid grid with 20px side margins. 
*   **Philosophy:** Vertical rhythm is driven by the 8px base unit. Section gaps are intentionally large (120px+) to reinforce the minimalist aesthetic and allow the "glass" components to breathe against the sand background.

## Elevation & Depth

Depth is achieved through **Glassmorphism** rather than traditional drop shadows. 

1.  **The Base Layer:** The #F0E4D7 background.
2.  **The Glass Layer:** Elements like cards and navigation bars use a semi-transparent white (rgba(255, 255, 255, 0.4)) with a `backdrop-filter: blur(12px)`.
3.  **The Stroke:** To define the edges of glass elements, a 1px solid border of a lighter sand or pure white with 20% opacity is used.
4.  **Interaction Depth:** Only upon hover do elements receive a soft, diffused shadow (Primary color at 10% opacity) to indicate interactivity.

## Shapes

The shape language is consistently **Rounded**. 

*   **Standard Components:** Buttons, input fields, and tags use a 0.5rem (8px) radius.
*   **Containers:** Portfolio cards and large glass sections use a 1rem (16px) radius to emphasize the "soft" and "modern" aesthetic.
*   **Visual Interest:** Occasionally, photography or featured sections may use an "organic" pill shape (3rem) to break the grid's rigidity.

## Components

### Buttons
Primary buttons use the #6A0DAD background with white text. They should have a subtle glass-like "shine" (a linear gradient from top-left) to match the overall style. Secondary buttons are "Ghost" style with a Primary color border and text.

### Glass Cards
The signature component. These containers house portfolio projects. They feature the backdrop blur and the secondary color (#FF9E80) for the project titles. On hover, the border opacity increases.

### Chips/Tags
Small, rounded labels for skills or categories. Use #FFE4E1 (Misty Rose) as the background with #6A0DAD text for high legibility and a sophisticated color mix.

### Input Fields
Minimalist underlines or very subtle glass containers. The focus state should transition the border color to the Primary purple.

### Navigation Bar
A fixed-top glass header. It should be highly transparent (20-30%) with a strong blur (20px) to allow the portfolio content to scroll beautifully beneath it.