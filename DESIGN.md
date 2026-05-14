---
name: Mesón Andaluz Visual Identity
colors:
  surface: '#fff9eb'
  surface-dim: '#e0dac7'
  surface-bright: '#fff9eb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#faf3e0'
  surface-container: '#f4eedb'
  surface-container-high: '#efe8d5'
  surface-container-highest: '#e9e2d0'
  on-surface: '#1e1c10'
  on-surface-variant: '#59413d'
  inverse-surface: '#333024'
  inverse-on-surface: '#f7f0de'
  outline: '#8d706c'
  outline-variant: '#e1bfb9'
  surface-tint: '#b02d21'
  primary: '#9e2016'
  on-primary: '#ffffff'
  primary-container: '#c0392b'
  on-primary-container: '#ffe5e1'
  inverse-primary: '#ffb4a9'
  secondary: '#735c00'
  on-secondary: '#ffffff'
  secondary-container: '#fed33e'
  on-secondary-container: '#725b00'
  tertiary: '#8f3329'
  on-tertiary: '#ffffff'
  tertiary-container: '#af4a3f'
  on-tertiary-container: '#ffe5e2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#410000'
  on-primary-fixed-variant: '#8e130c'
  secondary-fixed: '#ffe085'
  secondary-fixed-dim: '#ecc22c'
  on-secondary-fixed: '#231b00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#ffdad5'
  tertiary-fixed-dim: '#ffb4a9'
  on-tertiary-fixed: '#410001'
  on-tertiary-fixed-variant: '#80281f'
  background: '#fff9eb'
  on-background: '#1e1c10'
  surface-variant: '#e9e2d0'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
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
  unit: 8px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
This design system captures the soulful essence of Andalusia, blending rustic heritage with modern elegance. The visual direction is a "Rustic-Modern" interpretation of Spanish hospitality, evoking the warmth of a sun-drenched courtyard and the refined intimacy of a late-night bodega. 

The aesthetic leverages high-quality typography and organic textures to create an emotional response of comfort, authenticity, and culinary excellence. We avoid the clichés of traditional tourism by focusing on tactile surfaces, sophisticated color harmonies, and a spacious layout that allows the photography of the cuisine to remain the centerpiece.

## Colors
The palette is rooted in the natural landscapes of Southern Spain. 

- **Primary (Terracotta):** Used for key brand moments, primary calls to action, and structural accents. It evokes the fired clay of Spanish rooftops.
- **Secondary (Gold):** Reserved for highlights, ornamental details, and interactive states. It represents the warmth of the sun and the richness of olive oil.
- **Tertiary (Wine Red):** Used for deep emphasis, footer backgrounds, or specialized text to provide depth and contrast.
- **Neutral (Cream & Off-white):** These form the "canvas." Instead of pure white, we use these hues to create a softer, more inviting reading environment that feels like aged paper or stucco walls.

## Typography
The typography pairing establishes a clear hierarchy between tradition and modernity. 

- **Playfair Display:** Our serif typeface used for all high-level headings. It provides a literary, authoritative, and elegant feel. For Display sizes, use tighter letter spacing to enhance the dramatic high-contrast strokes of the letterforms.
- **Plus Jakarta Sans:** Our sans-serif workhorse for body copy and UI elements. Its soft, rounded terminals echo the friendly nature of the brand while ensuring high legibility on digital menus and booking flows.
- **Styling Note:** Use Title Case for headlines to maintain a formal, upscale tone. Labels should utilize slight tracking (letter-spacing) and uppercase styling for a sophisticated navigational feel.

## Layout & Spacing
The layout follows a fluid 12-column grid system for desktop and a single-column flow for mobile. 

- **Generous White Space:** To reflect an "elegant" brand, we intentionally over-index on vertical padding between sections (80px–120px) to give the content room to breathe.
- **Asymmetry:** Occasionally break the grid with offset images or overlapping text elements to mimic the organic growth of traditional Spanish architecture.
- **Breakpoints:** 
  - Mobile: < 600px (Margins: 20px)
  - Tablet: 600px - 1024px (Margins: 40px)
  - Desktop: > 1024px (Max-width container)

## Elevation & Depth
Depth in this design system is achieved through subtle, naturalistic layering rather than aggressive shadows.

- **Tonal Layers:** Use the Neutral (Cream) for the primary background and Off-white for cards or secondary sections to create a gentle "step-up" in hierarchy.
- **Ambient Shadows:** For interactive cards and buttons, use very soft, diffused shadows with a slight Terracotta tint (#C0392B at 5-8% opacity) rather than grey. This maintains the "warm" visual temperature of the UI.
- **Background Texture:** Apply a subtle grain or "stucco" SVG filter to the main background to eliminate the clinical feel of flat digital surfaces. 
- **Z-Index Strategy:** Floating action buttons (like "Book a Table") should sit at the highest elevation with a slightly more pronounced shadow to encourage conversion.

## Shapes
The shape language is refined and softened.

- **Standard Radius:** 0.5rem (8px) is the baseline for most cards and containers.
- **Buttons:** Use a slightly higher roundedness (12px or fully pill-shaped for secondary buttons) to make them feel more approachable.
- **Iconography:** Icons should feature rounded caps and corners. Use a 2px stroke weight to maintain an "etched" look that complements the serif typography.
- **Decorative Elements:** Incorporate "Azulejo" (Spanish tile) patterns as background masks or border dividers. These should be geometric but softened at the edges.

## Components
- **Buttons:** The primary button is a solid Terracotta block with white text. On hover, it transitions to Wine Red with a subtle lift. The secondary button is an "outlined" Gold style with a slight background shimmer on hover.
- **Cards:** Food items are presented in cards with 0.5rem rounded corners, a thin cream border, and a soft ambient shadow. Images should have a slight "zoom" animation on hover.
- **Menu Lists:** Use a clean, dotted-line connector between the dish name (Serif) and the price (Sans-serif) to evoke traditional printed menus.
- **Inputs:** Form fields for reservations use a "bottom-border only" style with a Cream background, making them feel more like a guestbook than a technical form.
- **Thematic Icons:** Custom iconography for Paella, Tapas, and Wine should be illustrated in a monoline style with Gold or Terracotta strokes.
- **Motifs:** Use an "Olive Branch" SVG as a decorative divider (HR) or a subtle corner ornament on high-elevation cards.