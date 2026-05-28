---
name: Academic Excellence
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#5c3f40'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#906f6f'
  outline-variant: '#e5bdbd'
  surface-tint: '#be0035'
  primary: '#ad002f'
  on-primary: '#ffffff'
  primary-container: '#d71440'
  on-primary-container: '#ffecec'
  inverse-primary: '#ffb3b5'
  secondary: '#565991'
  on-secondary: '#ffffff'
  secondary-container: '#bcbffe'
  on-secondary-container: '#484c82'
  tertiary: '#006059'
  on-tertiary: '#ffffff'
  tertiary-container: '#007b72'
  on-tertiary-container: '#b3fff5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b5'
  on-primary-fixed: '#40000b'
  on-primary-fixed-variant: '#920026'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bfc2ff'
  on-secondary-fixed: '#11144a'
  on-secondary-fixed-variant: '#3e4278'
  tertiary-fixed: '#96f3e7'
  tertiary-fixed-dim: '#79d6cb'
  on-tertiary-fixed: '#00201d'
  on-tertiary-fixed-variant: '#00504a'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e5e2e1'
  heritage-red: '#D71440'
  deep-navy: '#181B50'
  ink-black: '#222222'
  pure-white: '#FFFFFF'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Hanken Grotesk
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
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system embodies a prestigious, global academic institution that balances a rich heritage with forward-thinking innovation. The brand personality is authoritative yet accessible, intellectual, and highly organized. 

The chosen design style is **Corporate / Modern** with a lean toward **Minimalism**. It prioritizes clarity, structured information hierarchy, and generous whitespace to ensure that complex academic content remains digestible. The aesthetic is \"clean-tech academic\"—utilizing sharp precision, a rigorous grid, and a high-contrast palette to evoke trust and excellence.

## Colors
The color strategy is anchored by the signature \"Heritage Red\" and \"Deep Navy.\" 

- **Primary (Heritage Red):** Used for key calls to action, active states, and brand-defining accents. It commands attention and represents energy.
- **Secondary (Deep Navy):** Used for headers, navigation backgrounds, and primary text containers to provide a grounded, stable foundation.
- **Neutral (Ink Black):** Reserved for body text and high-contrast typography to ensure WCAG AA accessibility standards.
- **Backgrounds:** Primarily use \"Pure White\" to maintain a clean, academic feel, with very light neutral-grey tints used sparingly for section differentiation.

## Typography
The typography system uses a pairing of **Hanken Grotesk** for headlines and **Inter** for body text. 

- **Hanken Grotesk** provides a sharp, contemporary feel for titles, echoing technical precision.
- **Inter** is utilized for its exceptional legibility in data-heavy and long-form academic content.
- Use tight letter-spacing for large display type and generous line-heights (1.5x+) for body text to improve reading endurance. 
- Editorial content should prioritize \"Body LG\" for better readability on desktop environments.

## Layout & Spacing
The design system employs a **Fixed Grid** model for desktop to maintain formal structure, transitioning to a **Fluid Grid** for mobile devices.

- **Grid:** A 12-column grid is standard for desktop (1280px max width). Elements should align strictly to column edges to reinforce the \"organized\" brand pillar.
- **Rhythm:** An 8px linear scale governs all padding and margins. 
- **Desktop:** Use 64px margins to allow content to breathe.
- **Mobile:** Scale down to a 4-column grid with 20px margins. Vertical rhythm is tightened to reduce excessive scrolling in informational layouts.

## Elevation & Depth
To maintain a professional and flat academic aesthetic, the system avoids heavy, blurred shadows. Depth is conveyed through:

- **Tonal Layers:** Using slight variations in background color (e.g., a very light grey surface container against a white background) to create hierarchy.
- **Low-Contrast Outlines:** Subtle 1px borders in a light grey (`#E5E5E5`) are preferred over shadows for cards and input fields.
- **Interactive Elevation:** Only apply \"Ambient Shadows\" (low opacity, 4-8% alpha) on hover states for interactive cards to provide tactile feedback without cluttering the visual field.

## Shapes
The shape language is **Soft (0.25rem)**. 

This minimal rounding provides a modern touch while maintaining the \"serious\" and \"structured\" nature of a university. 
- **Standard UI elements** (Inputs, Buttons): 4px (0.25rem) radius.
- **Large containers** (Cards, Modals): 8px (0.5rem) radius.
- **Icons:** Should follow a consistent 2px stroke weight with slight terminal rounding to match the typography.

## Components
- **Buttons:** Primary buttons are solid Deep Navy or Heritage Red with white text. Use the \"Soft\" radius. Secondary buttons use a Deep Navy outline with a transparent background.
- **Chips:** Used for academic tags or departments. These should have a subtle background fill (5% opacity of the secondary color) and no border.
- **Input Fields:** Maintain a 1px solid border. Focus states should use a 2px Heritage Red border for high visibility.
- **Cards:** White background with a 1px light-grey outline. On hover, apply a very soft ambient shadow and a subtle vertical shift (-2px).
- **Navigation:** The top navigation should be clean, using Deep Navy for the primary bar or a stark white with Deep Navy text for secondary utility links.
- **Lists:** Use custom bullet points in Heritage Red to tie the list items back to the brand identity.
