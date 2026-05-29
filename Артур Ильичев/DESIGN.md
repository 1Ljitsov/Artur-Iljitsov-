---
name: Artur Ilyichev Identity
colors:
  surface: '#fbf9f4'
  surface-dim: '#dbdad5'
  surface-bright: '#fbf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ee'
  surface-container: '#f0eee9'
  surface-container-high: '#eae8e3'
  surface-container-highest: '#e4e2dd'
  on-surface: '#1b1c19'
  on-surface-variant: '#4d4540'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f1ec'
  outline: '#7e756f'
  outline-variant: '#cfc4bd'
  surface-tint: '#635d5a'
  primary: '#181512'
  on-primary: '#ffffff'
  primary-container: '#2d2926'
  on-primary-container: '#96908b'
  inverse-primary: '#cdc5c0'
  secondary: '#775a19'
  on-secondary: '#ffffff'
  secondary-container: '#fed488'
  on-secondary-container: '#785a1a'
  tertiary: '#221202'
  on-tertiary: '#ffffff'
  tertiary-container: '#392612'
  on-tertiary-container: '#a98c71'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e9e1dc'
  primary-fixed-dim: '#cdc5c0'
  on-primary-fixed: '#1e1b18'
  on-primary-fixed-variant: '#4b4642'
  secondary-fixed: '#ffdea5'
  secondary-fixed-dim: '#e9c176'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4201'
  tertiary-fixed: '#fedcbe'
  tertiary-fixed-dim: '#e1c1a4'
  on-tertiary-fixed: '#291806'
  on-tertiary-fixed-variant: '#59422c'
  background: '#fbf9f4'
  on-background: '#1b1c19'
  surface-variant: '#e4e2dd'
typography:
  display-lg:
    fontFamily: ebGaramond
    fontSize: 64px
    fontWeight: '500'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: ebGaramond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: ebGaramond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: ebGaramond
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.7'
  body-md:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.15em
  headline-lg-mobile:
    fontFamily: ebGaramond
    fontSize: 36px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 32px
  margin-desktop: 80px
  margin-tablet: 40px
  margin-mobile: 20px
  stack-lg: 120px
  stack-md: 64px
  stack-sm: 32px
---

## Brand & Style

This design system is rooted in the "Quiet Luxury" aesthetic—a philosophy that prioritizes substance, heritage, and restraint over flashy trends. It evokes the atmosphere of a private conservatory or a high-end European atelier. The visual language is cinematic and editorial, treating the musician’s biography not as a digital resume, but as a curated monograph.

The style is **Expensive Minimalism**. It utilizes generous negative space to signify confidence and "breathing room." The interface should feel tactile, like high-quality vellum or letterpress paper, achieved through a sophisticated balance of warm neutrals and hairline-thin structural elements. There is a deliberate avoidance of fast-paced animations, opting instead for slow, purposeful transitions that reflect the tempo of classical music.

## Colors

The palette is a sophisticated "Ton-sur-Ton" (tone on tone) arrangement of warm neutrals and deep earth tones, punctuated by metallic accents.

*   **Primary (Graphite):** Used for primary headings and body text to ensure maximum legibility while appearing softer than pure black.
*   **Secondary (Subtle Gold):** A muted, non-metallic gold reserved for highlights, icons, and small interactive states to denote "excellence."
*   **Tertiary (Dark Brown):** Used for deep backgrounds or subtle borders to add warmth and vintage depth.
*   **Neutral (Milky White/Cream):** The primary background color. It should feel like aged paper, providing a soft contrast that reduces eye strain compared to clinical white.
*   **Warm Gray:** Used for secondary text and decorative lines, ensuring the hierarchy is maintained without cluttering the visual field.

## Typography

The typography pairing reflects the intersection of tradition and modernity. **EB Garamond** provides a timeless, scholarly authority for headings, while **Manrope** offers a clean, modern accessibility for functional text.

*   **Display & Headlines:** Use EB Garamond with tight tracking for a prestigious "Vogue-style" editorial look. High-level headers should utilize italic styles sparingly for emphasis on key quotes or dates.
*   **Body Text:** Manrope is set with generous line height (1.6x+) to ensure a relaxed reading experience.
*   **Navigation & Labels:** All-caps Manrope with increased letter spacing is the standard for navigation items, tags, and small metadata labels to create a sense of structure and "archival" labeling.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy to maintain the structured feel of a printed biography. 

*   **Grid:** A 12-column grid is used for desktop, with elements often centered or intentionally offset to create an asymmetrical, artistic flow. 
*   **Margins:** Generous outer margins (80px) are essential to the "luxury" feel, framing the content like a piece of art.
*   **Stacking:** We use a "Leapfrog" spacing rhythm. Section breaks use `stack-lg` (120px) to ensure no two content areas feel crowded. 
*   **Mobile Adaption:** On mobile, the grid collapses to 4 columns. Headlines scale down significantly (using `headline-lg-mobile`), and horizontal elements like the timeline reflow into vertical lists to maintain legibility.

## Elevation & Depth

To maintain a "Flat-Luxury" aesthetic, depth is achieved through **Tonal Layering** rather than heavy shadows.

*   **Surface Hierarchy:** The primary background is Milky White. Cards and containers use a slightly darker "Alabaster" or "Dark Beige" fill to define boundaries without hard lines.
*   **Shadows:** When used, shadows must be "Ambient." This means extremely low opacity (3-5%), a very large blur radius (40px+), and a color tint derived from the Dark Brown palette rather than pure gray. This mimics a soft light source hitting fine paper.
*   **Outlines:** Hairline borders (0.5px to 1px) in a subtle Graphite-to-Cream gradient are used for image frames and input fields, giving them a "sharp" professional finish.

## Shapes

The design system uses a **Soft (0.25rem)** roundedness. 

While "Old Money" aesthetics often lean into sharp corners, a micro-radius (4px) prevents the UI from feeling aggressive or dated. This slight softening suggests a premium, polished manufacturing quality—similar to the rounded edges of a high-end watch or a custom-bound book. 

*   **Standard Elements:** 4px radius.
*   **Images:** 4px radius to keep photos of Artur and his performances looking integrated into the "page."
*   **Specialty Elements:** Interactive chips or tags may use a pill-shape to distinguish them from structural cards.

## Components

*   **Buttons:** Primary buttons use a solid Graphite fill with Milky White text. Secondary buttons are "Ghost" style with a hairline Graphite border. Hover states should involve a subtle shift to the Gold accent or a slight expansion of the ambient shadow.
*   **Timeline:** The timeline uses a single horizontal (or vertical on mobile) Graphite line, only 1px thick. Milestones are represented by small, unfilled circles that fill with Gold upon scroll-interaction.
*   **Cards (Achievements/Gallery):** Cards have no visible background by default. They rely on the `label-caps` headers and `stack-sm` spacing to define their boundaries. Upon hover, a very subtle Milky White background may appear to "lift" the content.
*   **Input Fields:** Minimalist under-lines (border-bottom only) are preferred over full boxes to mimic signature lines on a document.
*   **Quotes:** Large Garamond Italic text, centered, with Gold-colored quotation marks that are twice the size of the text to serve as a graphic anchor.
*   **Navigation:** A "Sticky" header with a blur-behind (frosted glass effect) ensures navigation is always present without obstructing the cinematic photography of the site.