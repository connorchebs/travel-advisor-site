---
name: Horizon Ethos
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#45464d'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#191c1e'
  on-tertiary-container: '#818486'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#e0e3e5'
  tertiary-fixed-dim: '#c4c7c9'
  on-tertiary-fixed: '#191c1e'
  on-tertiary-fixed-variant: '#444749'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  section-gap: 80px
---

## Brand & Style

The design system is engineered for a premium travel advisory experience, balancing professional expertise with the emotional allure of discovery. The brand personality is **authoritative yet inviting**, positioning the service as a knowledgeable curator for sophisticated travelers.

The visual style follows a **Modern Corporate** aesthetic with a **Minimalist** foundation. It prioritizes clarity and high-end editorial layouts. By utilizing generous whitespace and structured content blocks, the UI evokes a sense of calm and organization, reassuring the user that their complex travel needs are in capable hands. High-quality imagery is treated as a core architectural element rather than an ornament, often spanning the full width of containers to provide "windows" into destinations.

## Colors

The palette is anchored by **Deep Navy** (`#0F172A`), providing a foundation of stability, trust, and luxury. **Teal Accents** (`#0D9488`) are used strategically for primary actions and to draw attention to travel highlights, offering a refreshing contrast that feels both modern and professional.

The background system relies on a **Soft Gray** (`#F8FAFC`) to define different content sections without the harshness of pure white, though white is used for primary cards and content surfaces to maintain a crisp, editorial feel. Text utilizes the primary navy for headings to ensure high legibility and a sophisticated tone, while the neutral slate gray is used for secondary body text.

## Typography

This design system employs a sophisticated typographic pairing:
- **Headings (Noto Serif):** Used to convey tradition, expertise, and the "storytelling" aspect of travel. Display sizes use tighter letter spacing for a premium editorial look.
- **Body & Interface (Plus Jakarta Sans):** A modern, soft sans-serif that ensures high readability across itineraries and logistical details. Its friendly curves balance the seriousness of the serif headings.

**Scale & Hierarchy:**
Use `display-lg` for hero sections. `label-md` should be used for small "category" tags or eyebrows above headings, always in uppercase with increased letter spacing to enhance the professional, curated feel.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is centered on "The Breathing Room"—ensuring that no two information blocks feel crowded.

- **Breakpoints:** Mobile (<768px), Tablet (768px - 1024px), Desktop (>1024px).
- **Sectioning:** Vertical spacing between major sections (`section-gap`) is intentionally large to prevent cognitive overload.
- **Alignment:** Content is generally centered in a max-width container, but imagery can occasionally "break the grid" and bleed to the edge of the screen to create a sense of immersion.

## Elevation & Depth

Depth is achieved through **Tonal Layering** and **Ambient Shadows**. 

1. **Surface Levels:** The base background is the soft tertiary gray. Interactive cards or content containers sit on top in pure white.
2. **Shadows:** Use extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 10px 30px -5px rgba(15, 23, 42, 0.05)`). The shadow color should always be a tinted version of the primary navy, never pure black, to keep the look organic and high-end.
3. **Interactions:** On hover, cards should subtly lift (shadow becomes slightly deeper) or scale (1.02x) to provide immediate, soft feedback without disrupting the professional tone.

## Shapes

The shape language is **Rounded (Level 2)**. 

- **Primary Radius (8px):** Applied to buttons, input fields, and standard cards.
- **Large Radius (16px - 24px):** Reserved for large image containers or prominent feature sections to soften the visual impact of high-contrast photography.
- **Consistency:** Avoid sharp corners entirely to maintain an approachable and safe brand feel. Buttons should never be fully pill-shaped; they should maintain a structured, professional rectangle with softened corners.

## Components

### Buttons
- **Primary:** Deep Navy background, White text. High-contrast and clear.
- **Secondary:** Teal border and text, transparent background. For exploratory actions.
- **Tertiary:** Text-only with a subtle underline or arrow icon for "Read More" links.

### Cards
- **Destination Cards:** Feature a high-resolution image with a 3:4 aspect ratio. Text overlays should be on a subtle gradient at the bottom or placed in a white container below the image.
- **Itinerary Cards:** Use soft gray borders or very light shadows to separate daily activities.

### Inputs & Fields
- Inputs should have a subtle gray background (`#F1F5F9`) that turns white with a Teal border upon focus. Labels are always `label-sm` positioned above the field.

### Specialized Components
- **Testimonial Slider:** Clean typography centered over a white card with a subtle quote icon in the primary navy.
- **Trust Badges:** Small, monochrome (Navy or Neutral) icons representing certifications or partner logos, placed in the footer or near conversion points.