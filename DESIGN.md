---
name: Artisanal Hearth
colors:
  surface: '#fdf9f3'
  surface-dim: '#dddad4'
  surface-bright: '#fdf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3ed'
  surface-container: '#f1ede7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e6e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4d444b'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f4f0ea'
  outline: '#7e747c'
  outline-variant: '#cfc3cc'
  surface-tint: '#755377'
  primary: '#331736'
  on-primary: '#ffffff'
  primary-container: '#4a2c4d'
  on-primary-container: '#ba94bb'
  inverse-primary: '#e3b9e3'
  secondary: '#7d5700'
  on-secondary: '#ffffff'
  secondary-container: '#ffc55f'
  on-secondary-container: '#755100'
  tertiary: '#1b2500'
  on-tertiary: '#ffffff'
  tertiary-container: '#303b0f'
  on-tertiary-container: '#98a66f'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fe'
  primary-fixed-dim: '#e3b9e3'
  on-primary-fixed: '#2c1030'
  on-primary-fixed-variant: '#5b3c5e'
  secondary-fixed: '#ffdeaa'
  secondary-fixed-dim: '#f5bd58'
  on-secondary-fixed: '#271900'
  on-secondary-fixed-variant: '#5f4100'
  tertiary-fixed: '#dbe9ac'
  tertiary-fixed-dim: '#bfcd92'
  on-tertiary-fixed: '#161f00'
  on-tertiary-fixed-variant: '#404b1e'
  background: '#fdf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e6e2dc'
  surface-warm: '#FAF6F0'
  fig-deep: '#4A2C4D'
  amber-glow: '#D9A441'
  ink-black: '#221E1F'
typography:
  display-lg:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  price-tag:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: auto
  max-width-content: 800px
  section-gap: 64px
---

## Brand & Style

The design system is built to evoke the sensory experience of a neighborhood café—warmth, the aroma of roasting coffee, and the tactile nature of handmade goods. It strikes a balance between professional catering services and the intimate atmosphere of an independent shop. 

The aesthetic is **Artisanal Minimalism**. It prioritizes heavy whitespace and high-quality photography to let the products (coffee and baked goods) speak for themselves. By combining the rich tones of fig and amber with a warm, off-white foundation, the UI feels hospitable rather than clinical. The visual language is grounded and "plainspoken," avoiding unnecessary digital flourishes in favor of clear, centered layouts and structural integrity.

## Colors

The palette is rooted in organic, earthy tones. 

- **Primary (Deep Fig Purple):** Used for navigation, primary buttons, and critical brand moments. It provides a sophisticated alternative to standard black or navy.
- **Secondary (Warm Amber):** Reserved strictly for accents—such as icons, dietary markers (V, VG, GF), or hover states for text links. It must never be used for body text to ensure legibility.
- **Neutral (Warm Off-White):** This is the primary canvas. It reduces the harsh contrast of pure white, creating a "paper-like" feel that complements the artisanal theme.
- **Text (Near-Black):** Used for all body copy and secondary headers to maintain a grounded, professional readability.

## Typography

The typography strategy pairs a "characterful serif" with a "utilitarian sans-serif" to reflect the "Roasted here. Baked here." philosophy.

- **Headlines:** Uses a classic, refined serif to convey heritage and artisanal quality. Larger display sizes should utilize tighter letter-spacing for a modern editorial look.
- **Body:** A clean, neutral sans-serif ensures maximum readability for menu items and operational details like opening hours.
- **Hierarchy:** Ensure a clear distinction between menu categories (Headlines) and menu items (Body). Prices are treated with a slight weight increase and italics to stand out without being loud.

## Layout & Spacing

This design system follows a **Mobile-First, Single-Column focus**. 

- **Mobile:** All content lives in a single, centered column with generous side margins (20px) to prevent the UI from feeling cramped. Elements like menu groups and catering packages stack vertically.
- **Desktop:** For pages like Menu and Catering, a maximum of two columns is allowed to maintain the "intimate" feel and prevent line lengths from becoming unreadable.
- **The "Fold" Priority:** On the Home and Visit pages, critical information (address and hours) must be positioned at the top of the stack to ensure zero-scroll visibility on mobile devices.
- **Rhythm:** Use a base 4px unit for internal component spacing, while using larger 64px gaps between major sections to maintain the minimalist, airy aesthetic.

## Elevation & Depth

The design system avoids digital-heavy shadows in favor of **Tonal Layers** and **Physical Borders**.

- **Surfaces:** Depth is created by placing white or deep purple containers against the warm off-white background. 
- **Outlines:** Use very thin (1px) borders in the Deep Fig color for cards and input containers to suggest a "printed" or "menu-board" feel.
- **No Shadows:** Shadows are replaced by high-contrast flat colors. If a hover state is required, a slight color shift or the introduction of the Amber accent is preferred over a shadow.
- **Photography:** Images should be the primary source of depth, using shallow depth-of-field (bokeh) to make the products feel tangible and close.

## Shapes

The shape language is **Soft** but structured. 

- **Subtle Rounding:** A 0.25rem (4px) corner radius is applied to buttons and image containers. This "softens" the professional layout without making it feel overly playful or "bubbly."
- **Interactive Elements:** Buttons follow this soft-cornered rule. Circular shapes are only used for small functional icons or dietary markers (V, VG, GF) to differentiate them from actionable UI components.

## Components

- **Primary Buttons:** Solid Deep Fig Purple (#4A2C4D) backgrounds with white text. Use uppercase or semi-bold sans-serif. These are used only for the single primary CTA on each page (e.g., "Find us", "Order catering").
- **Secondary Links:** Text-only links in Deep Fig Purple with a subtle Amber (#D9A441) underline on hover.
- **Menu Lists:** Clean, left-aligned text with prices aligned to the right or placed immediately after the item name in a lighter weight.
- **Dietary Chips:** Small, circular or subtly rounded badges using the Amber accent for the border or icon to indicate V, VG, or GF.
- **Catering Cards:** Defined by a 1px Deep Fig border. On mobile, these stack; on desktop, they sit side-by-side. The price should be the most prominent element after the package title.
- **Input Fields (Contact):** Simple 1px borders, near-black labels, and the neutral background. No heavy styling—keep them "plainspoken."
- **Footer:** A full-width Deep Fig Purple block or a clean off-white section with a divider. It must contain the cafe details in a systematic, easy-to-read list.