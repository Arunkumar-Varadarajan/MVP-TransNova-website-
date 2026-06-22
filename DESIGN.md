---
name: Horizon Bound
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#43474f'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#737780'
  outline-variant: '#c3c6d1'
  surface-tint: '#3a5f94'
  primary: '#001e40'
  on-primary: '#ffffff'
  primary-container: '#003366'
  on-primary-container: '#799dd6'
  inverse-primary: '#a7c8ff'
  secondary: '#8d4f11'
  on-secondary: '#ffffff'
  secondary-container: '#feac67'
  on-secondary-container: '#773e00'
  tertiary: '#1e2010'
  on-tertiary: '#ffffff'
  tertiary-container: '#333524'
  on-tertiary-container: '#9d9e88'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a7c8ff'
  on-primary-fixed: '#001b3c'
  on-primary-fixed-variant: '#1f477b'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#e4e4cc'
  tertiary-fixed-dim: '#c8c8b0'
  on-tertiary-fixed: '#1b1d0e'
  on-tertiary-fixed-variant: '#474836'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

## Brand & Style

The design system is engineered to evoke the spirit of discovery while maintaining the structured reliability of a premium travel agency. The brand personality is **Inspirational, Expert, and Seamless**. It targets affluent travelers and adventure seekers who value both aesthetic beauty and functional clarity.

The visual style is a hybrid of **Modern Minimalism** and **Editorial Elegance**. It utilizes expansive whitespace to let high-quality travel photography breathe, paired with sophisticated layering and subtle glassmorphic elements to suggest depth and movement. The emotional response should be one of "aspirational calm"—the feeling of a perfectly planned journey.

## Colors

This design system employs a palette inspired by natural coastal landscapes to ground the user in the travel experience.

- **Primary (Deep Ocean Blue):** Used for core branding, navigation backgrounds, and primary calls to action. It conveys trust and depth.
- **Secondary (Sunset Orange):** An accent color used sparingly for high-priority interactions, notifications, or "Book Now" highlights. It provides a warm, energetic contrast to the blue.
- **Tertiary (Sandy Neutral):** Used for section backgrounds and card containers to soften the interface and prevent the starkness of pure white.
- **Neutral (Ink):** A near-black for maximum legibility in typography and iconography.

Functional colors (Success, Warning, Error) should be desaturated to maintain the sophisticated tonal balance of the primary palette.

## Typography

The typography strategy relies on a high-contrast pairing:
- **Headings:** Use **Noto Serif**. This font brings a literary, authoritative feel to the design, reminiscent of high-end travel magazines. Large display sizes should use tighter letter spacing to feel more cohesive.
- **Body & Interface:** Use **Plus Jakarta Sans**. Its soft, rounded terminals complement the serif's sharpness while ensuring exceptional readability for long-form descriptions and technical booking details.

Hierarchy is established through significant scale shifts. Use `label-caps` for eyebrow text above headlines to provide context without cluttering the visual path.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

- **The Hero Pattern:** Employs a full-bleed or large-container layout with a centered or left-aligned typographic stack. Content is often overlaid on high-resolution imagery using a gradient scrim (30% opacity Primary Color to transparent).
- **Rhythm:** A 8px base unit drives all spacing. Section gaps are intentionally large (120px+) to emphasize the premium, unhurried nature of the brand.
- **Search Filters:** Implemented as a horizontal "floating" bar that breaks the boundary between the hero section and the following content, creating a sense of physical layering.

## Elevation & Depth

Depth in this design system is created through **Tonal Layering** and **Soft Ambient Shadows**.

- **Level 0 (Base):** Sandy Neutral background.
- **Level 1 (Cards):** White surfaces with a very soft, diffused shadow (0px 4px 20px rgba(0, 51, 102, 0.08)).
- **Level 2 (Interactive/Floating):** Elements like the search bar or hover-state cards use a slightly more pronounced shadow and a 1px border in a lighter tint of the Primary color (10% opacity) to define edges without adding visual weight.
- **Glassmorphism:** Navigation bars and image overlays utilize a backdrop blur (12px) with a 60% white tint to maintain legibility while showcasing the photography beneath.

## Shapes

The shape language is **Rounded**, reflecting the fluidity of travel and the softness of natural landscapes. 

- **Standard Elements:** Buttons, input fields, and small tags use `rounded` (0.5rem).
- **Containers:** Destination cards and image containers use `rounded-lg` (1rem) to create a friendly, modern framing for photography.
- **Special Elements:** Feature icons and selection chips may use `rounded-xl` (1.5rem) or pill-shapes to differentiate them from functional inputs.

## Components

- **Buttons:** 
    - *Primary:* Deep Ocean Blue background, white text. Bold weight.
    - *Secondary:* Ghost style with 2px Sandy Neutral border or Sunset Orange for conversion-critical actions.
- **Destination Cards:** Vertical orientation with an aspect ratio of 4:5 for imagery. Titles use `headline-sm` with a subtle location icon. Price points are highlighted using the Primary color in a bold weight.
- **Search Filters:** Integrated units with segmented controls for "Flight," "Hotel," and "Package." Inputs should use minimal borders, relying on background tone to define the hit area.
- **Lists:** Travel itineraries should use custom bullet points (small circles in Sunset Orange) to guide the eye through the timeline.
- **Chips:** Used for category filtering (e.g., "Beach," "Mountain," "City Break") with a light Sandy Neutral fill that transitions to Deep Ocean Blue on selection.
- **Hero Section:** Must include a high-contrast text block and a prominent Search Filter bar that overlaps the bottom edge of the hero image.