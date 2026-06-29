---
name: The64 Design System
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#534345'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#857275'
  outline-variant: '#d8c1c4'
  surface-tint: '#8f4857'
  primary: '#3f0819'
  on-primary: '#ffffff'
  primary-container: '#5a1e2d'
  on-primary-container: '#d68393'
  inverse-primary: '#ffb2bf'
  secondary: '#5f5e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2dc'
  on-secondary-container: '#656460'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9de'
  primary-fixed-dim: '#ffb2bf'
  on-primary-fixed: '#3b0616'
  on-primary-fixed-variant: '#733140'
  secondary-fixed: '#e5e2dc'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c18'
  on-secondary-fixed-variant: '#474743'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
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
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system embodies the intellectual rigor and historical prestige of chess through a lens of modern luxury. It targets a sophisticated audience that values both tradition and digital-native elegance.

The visual style is **Academic Minimalism** infused with **Glassmorphism**. It balances the weight of a traditional library with the airy, translucent qualities of high-end modern interfaces. The UI should evoke a sense of calm focus, precision, and timelessness. 
- **Minimalism:** Use expansive white space to denote premium quality.
- **Glassmorphism:** Employed strategically on cards and overlays to represent the "transparency" of logic and clear thinking.
- **Tactile Details:** Subtle use of grain or parchment-like textures in the background to bridge the gap between physical chess sets and digital learning.

## Colors
The palette is rooted in classical academia and luxury.
- **Primary (Bordeaux Velvet - #5A1E2D):** Used for primary actions, accents, and expressing authority. It represents the deep wood and felt of a premium chessboard.
- **Secondary/Background (Ivory Whisper - #F8F5EF):** The primary canvas color. It is warmer and more sophisticated than pure white, reducing eye strain during long study sessions.
- **Neutral (Charcoal - #2F2F2F):** Used for primary text and iconography to ensure high legibility against the Ivory background.
- **Tertiary (Gold Leaf - #D4AF37):** Used sparingly for achievement icons, mastery levels, or "Grandmaster" status indicators to reinforce the premium nature of the academy.

## Typography
The typographic hierarchy creates a "Grandmaster" aesthetic. 
- **Headings:** Playfair Display provides a literary, authoritative feel. Large display type should use tighter letter-spacing to feel more editorial.
- **Body:** Inter provides a clean, functional contrast, ensuring that complex chess notation and instructional text are perfectly legible.
- **Labels:** Use Inter in uppercase with slight tracking to provide a modern, navigational feel that contrasts against the serif headers.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy on desktop to maintain the centered, focused feel of a study room. 
- **Desktop:** 12-column grid with a 1280px max-width. Use generous 64px outer margins to create an "island" effect for the content.
- **Rhythm:** An 8px linear scale (8, 16, 24, 32, 48, 64, 80). 
- **Composition:** Avoid clutter. Use asymmetrical layouts for "Lesson Grids" where the primary board is large (8-9 columns) and the notation/sidebar is secondary (3-4 columns).

## Elevation & Depth
This design system uses **Layered Glassmorphism** to create hierarchy without the heaviness of traditional shadows.
- **Base:** The Ivory Whisper background remains flat.
- **Surface (Cards):** Semi-transparent white (#FFFFFF at 40-60% opacity) with a 20px Backdrop Blur.
- **Borders:** Subtle 1px solid borders using a low-opacity Charcoal (#2F2F2F at 10%) to define shapes within the glass effect.
- **Shadows:** Only used on active elements or top-level modals. Shadows should be very soft, using the Primary color (Bordeaux) at 5% opacity to create a "warm" lift rather than a gray drop shadow.

## Shapes
The shape language is sophisticated and approachable. 
- **Primary Radius:** 16px (1rem) for cards and main containers to soften the intellectual rigor and make the academy feel welcoming.
- **Secondary Radius:** 8px (0.5rem) for buttons and input fields.
- **Interactive Elements:** Selection indicators on the chessboard should remain sharp (0px) to respect the geometry of the game, while UI containers surrounding the board use the system's roundedness.

## Components
- **Buttons:** Primary buttons are solid Bordeaux Velvet with white text. Hover states should transition to a slightly deeper shade or add a subtle Gold Leaf border. Use "ghost" buttons (transparent with Bordeaux text) for secondary actions.
- **Glass Cards:** Used for lesson modules. They must include a subtle internal glow (top-left inner shadow in white) to enhance the glass effect.
- **Lesson Grids:** Use high-contrast thumbnails. Titles should be in Playfair Display.
- **Navigation:** A minimal top bar. Use the primary logo on the left and uppercase labels on the right. The navigation bar should have a glass effect with a bottom border when scrolling.
- **Chessboard Elements:** The board should use Ivory and a muted Bordeaux-tinted wood texture for the squares. The "Active Square" indicator should be a subtle Gold Leaf highlight.
- **Chips/Badges:** Small, rounded-full pill shapes used for "Difficulty" (Beginner, Intermediate, Master) with low-saturation background tints.