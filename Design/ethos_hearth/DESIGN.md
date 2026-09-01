---
name: Ethos & Hearth
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#464742'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#777871'
  outline-variant: '#c7c7bf'
  surface-tint: '#5e5e5b'
  primary: '#5e5e5b'
  on-primary: '#ffffff'
  primary-container: '#f9f7f2'
  on-primary-container: '#71716d'
  inverse-primary: '#c8c6c2'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#805533'
  on-tertiary: '#ffffff'
  tertiary-container: '#fff5f0'
  on-tertiary-container: '#956744'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e4e2dd'
  primary-fixed-dim: '#c8c6c2'
  on-primary-fixed: '#1b1c19'
  on-primary-fixed-variant: '#474744'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#f4bb92'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#653d1e'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg:
    fontFamily: Playfair Display
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
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  button-serif:
    fontFamily: Playfair Display
    fontSize: 16px
    fontWeight: '600'
    lineHeight: '1.0'
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
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  section-gap: 120px
---

## Brand & Style
The design system is rooted in "Modern Bengali Heritage"—a blend of traditional warmth and contemporary editorial precision. It targets a discerning audience seeking craftsmanship and longevity. 

The aesthetic style is **Minimalist Editorial**. It prioritizes high-quality photography, intentional negative space, and a rhythmic balance between heavy-weighted typography and delicate structural lines. The emotional goal is to evoke a sense of "quiet luxury" and "home sanctuary," moving away from the frantic energy of typical e-commerce toward the paced, thoughtful experience of a high-end lifestyle magazine.

## Colors
The palette is inspired by natural materials and architectural interiors.
- **Background (Base):** Use Warm Ivory (#F9F7F2) for the majority of the UI surfaces to reduce eye strain and provide a softer contrast than pure white.
- **Typography & Interaction:** Rich Charcoal (#1A1A1A) is used for all primary text, icons, and high-emphasis UI elements like primary buttons.
- **Natural Accents:** Use Oak (#8B5E3C) for secondary actions or highlighting craftsmanship details. Earthy Clay (#D4A373) serves as a functional color for notifications, price highlights, or subtle hover states.
- **Dividers:** Use the 1px Neutral (#E5E5E5) for all structural lines to maintain a crisp, organized appearance without adding visual weight.

## Typography
This design system employs a high-contrast typographic pairing.
- **Headlines:** Playfair Display is used for all display and headline roles. It should be typeset with tight letter-spacing for large sizes to emphasize its elegant serifs.
- **Body & UI:** Inter is used for all functional text, descriptions, and metadata. It provides a technical, clean counterpoint to the organic nature of the serif.
- **Special Roles:** Use "label-caps" for small metadata like category tags or "New Arrival" badges. The "button-serif" style is used exclusively for secondary buttons to provide an artisanal touch.

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop, centered within a 1440px container. 
- **Rhythm:** Use an 8px base unit. 
- **Margins:** Generous margins are essential. Use 80px horizontal margins on desktop to allow the content to breathe. 
- **Section Gaps:** Vertical spacing between major sections should be 120px to 160px to maintain the editorial feel.
- **Mobile:** Transition to a 4-column fluid grid with 20px margins. Reduce vertical section gaps to 64px.

## Elevation & Depth
This design system avoids traditional shadows in favor of **Tonal Layering and Thin Outlines**. 
- **Surfaces:** Depth is created by placing Ivory surfaces (#F9F7F2) on top of slightly darker Neutral (#E5E5E5) backgrounds for full-bleed sections, or vice versa.
- **Outlines:** Instead of shadows, use 1px solid borders (#E5E5E5) to define card boundaries. 
- **Focus:** Upon interaction (hover), a subtle, extremely diffused shadow may be used (0px 4px 20px rgba(0,0,0, 0.04)) to indicate lift without breaking the flat editorial aesthetic.

## Shapes
The shape language is "Soft Rectilinear." 
- **Image Containers:** Use 16px to 24px radius for all product and lifestyle imagery to soften the overall aesthetic and evoke the curves of furniture.
- **UI Elements:** Buttons and input fields use a consistent 8px (rounded-lg) radius. 
- **Strict Rule:** Avoid pill-shaped elements (fully rounded corners) as they appear too casual/SaaS-like for this brand's premium positioning.

## Components
- **Primary Button:** Solid Charcoal (#1A1A1A) background with White text. Rectangular with 8px corners. 
- **Secondary Button:** 1px Charcoal border, transparent background. Text is Playfair Display Italic to emphasize the artisanal brand voice.
- **Product Cards:** No background fill or shadow. Use generous padding (24px) between the image and the product name. Typography is left-aligned.
- **Category Cards:** Large-scale imagery with an 80% opacity charcoal overlay for text legibility. The title should be centered in Playfair Display (Display-LG size).
- **Input Fields:** 1px borders (#E5E5E5). On focus, the border changes to Charcoal (#1A1A1A). Labels are always in Inter (Label-caps) positioned above the field.
- **Chips/Badges:** Small, rectangular tags with 4px corners. Use Earthy Clay (#D4A373) for stock status and Walnut (#5D4037) for limited editions.