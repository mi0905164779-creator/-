---
name: Longjing Curated Guide
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#42493e'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#a23f00'
  on-secondary: '#ffffff'
  secondary-container: '#fc7127'
  on-secondary-container: '#5c2000'
  tertiary: '#3b3933'
  on-tertiary: '#ffffff'
  tertiary-container: '#525049'
  on-tertiary-container: '#c6c2ba'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#ffdbcd'
  secondary-fixed-dim: '#ffb595'
  on-secondary-fixed: '#351000'
  on-secondary-fixed-variant: '#7c2e00'
  tertiary-fixed: '#e7e2d9'
  tertiary-fixed-dim: '#cac6be'
  on-tertiary-fixed: '#1d1c16'
  on-tertiary-fixed-variant: '#494740'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display-lg:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Noto Serif
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
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
    lineHeight: '1.4'
    letterSpacing: 0.05em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
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
  margin-mobile: 16px
  margin-desktop: 40px
  stack-xs: 4px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
  stack-xl: 80px
---

## Brand & Style

This design system is built to evoke the serene, artisanal spirit of the Longjing district. The brand personality is that of a "Sophisticated Local Guide"—knowledgeable, calm, and deeply connected to the landscape. The target audience includes discerning travelers and culinary enthusiasts who value authenticity and high-quality experiences over mass-market tourism.

The visual style follows a **Modern Minimalist** approach with **Tactile/Organic** undertones. It prioritizes editorial-grade whitespace to allow photography of lush tea plantations and plated delicacies to breathe. The interface should feel like a high-end travel journal: intentional, structured, and premium. Interaction patterns should be fluid and gentle, avoiding aggressive transitions in favor of soft fades and subtle scaling that mirror the slow pace of a tea ceremony.

## Colors

The palette is derived directly from the Longjing landscape. The **Primary Green** represents the iconic tea leaves and rolling hills, used for key actions and brand emphasis. The **Secondary Sunset Orange** provides a warm, inviting contrast, mimicking the glow of golden hour over the district—ideal for highlights, ratings, and accents.

The background strategy utilizes a **Tertiary Cream** rather than pure white to soften the visual impact and provide an "earthy" feel. Neutrals are kept warm (using a dark charcoal with a hint of brown) to maintain harmony with the organic palette. Functional colors for success or error should be desaturated to ensure they do not clash with the curated aesthetic.

## Typography

This design system employs a sophisticated typographic pairing to balance tradition and modernity. **Noto Serif** is used for headlines and display text, providing a literary, authoritative tone that feels curated and timeless.

**Plus Jakarta Sans** handles all functional and body text. Its soft, open counters and contemporary geometric shapes offer high legibility while maintaining a friendly, approachable character. For labels and small metadata, use uppercase styling with increased letter spacing to create a sense of organized luxury. Ensure a high contrast ratio between the deep charcoal text and the cream backgrounds to optimize readability for users on the move.

## Layout & Spacing

The layout philosophy relies on a **Fixed Grid** system for large screens to maintain an editorial, magazine-like structure, transitioning to a fluid model for mobile devices. A 12-column grid provides the flexibility needed for diverse content types, from full-width immersive imagery to asymmetrical restaurant listings.

Spacing is governed by an 8px base unit. We use "generous breathing room" as a core principle; vertical stack spacing (stack-lg and stack-xl) should be used liberally between major sections to prevent the UI from feeling cluttered. Gutters are kept wide to reinforce the premium, unhurried brand feel.

## Elevation & Depth

To maintain the elegant and modern aesthetic, this design system avoids heavy, artificial shadows. Instead, it utilizes **Tonal Layers** and **Ambient Depth**. 

1.  **Surface Tiers:** Use subtle variations of the tertiary cream and off-white to separate content sections.
2.  **Shadows:** When depth is required (such as for floating action buttons or cards), use extremely soft, diffused shadows with a slight tint of the primary green or earth tones (#2D5A27 at 5-10% opacity). This ensures the "shadow" feels like a natural light obstruction in an outdoor environment.
3.  **Glassmorphism:** For navigation overlays and mobile headers, a high-density backdrop blur (20px+) with a semi-transparent cream tint can be used to maintain context of the lush photography behind the interface.

## Shapes

The shape language is defined by **Rounded** geometry (Level 2). This choice avoids the clinical feel of sharp corners while remaining more structured than fully pill-shaped elements. 

-   **Cards and Main Containers:** Use a 1rem (16px) radius to feel substantial and modern.
-   **Buttons and Small Inputs:** Use a 0.5rem (8px) radius for a crisp, functional appearance.
-   **Imagery:** Photos should typically follow the container radius, but "hero" images may occasionally use a unique top-only radius or organic mask to emphasize the natural landscape theme.

## Components

### Buttons
Primary buttons use the Forest Green background with White text, featuring a subtle scale-down effect on press. Secondary buttons use a "Ghost" style with a 1px border of the primary green. Tertiary buttons for low-priority actions use the Sunset Orange for text only.

### Cards
Restaurant and guide cards are the centerpiece. They should feature a large aspect-ratio image (3:2 or 4:5), a Noto Serif title, and a small Plus Jakarta Sans "category" label. The container should have a very subtle 1px border in a slightly darker cream to define its edges against the background.

### Chips & Tags
Used for cuisine types (e.g., "Tea-infused," "Farm-to-table"). These should be low-contrast: a pale sage background with deep green text, using the 0.5rem roundedness.

### Input Fields
Forms should feel "quiet." Use a bottom-border only or a very light fill with no heavy outlines. Focus states are indicated by the primary green color and a subtle label lift.

### Signature Components
-   **The "Taste Meter":** A custom rating component using a tea-leaf icon instead of stars, colored in the secondary sunset orange.
-   **Curated Collection List:** A horizontal scrolling list of high-quality imagery with overlapping text elements, mimicking a luxury travel magazine.
-   **Map Markers:** Custom pins using the primary green with a white center icon, styled with a soft ambient shadow to appear as if hovering over the landscape.