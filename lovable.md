# Lovable — Style Reference
> Shifting gradient nebula

**Theme:** light

Lovable’s design system conveys a dynamic, creative energy using a predominantly light theme accented by a striking, evolving gradient for hero sections and interactive prompts. Typography is clean and compact, emphasizing content clarity within a contained layout. UI elements are subtly refined with medium border radii and minimal, soft shadows, creating an approachable yet modern aesthetic. Color manifests as functional cues and atmospheric backdrops, rather than heavy branding.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fcfbf8` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, default icon fill |
| Text Primary | `#1c1c1c` | `--color-text-primary` | Primary text, navigation links, bold headings, primary icon fill |
| Border Light | `#eceae4` | `--color-border-light` | Subtle borders, dividers, subtle button outlines |
| Text Secondary | `#5f5f5d` | `--color-text-secondary` | Muted text, helper text, input placeholders, secondary icon fill |
| Text Ghost | `#2e2e2d` | `--color-text-ghost` | Ghost button text, subtle link text, tertiary icon fill |
| Accent Gradient | `linear-gradient(90deg, rgb(28, 28, 28) 0px, rgb(28, 28, 28) 33.33%, rgb(130, 188, 255) 40%, rgb(36, 131, 255) 45%, rgb(255, 102, 244) 50%, rgb(255, 48, 41) 55%, rgb(254, 123, 2) 60%, rgba(0, 0, 0, 0) 66.67%, rgba(0, 0, 0, 0))` | `--color-accent-gradient` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Text Callout | `#030303` | `--color-text-callout` | Key text highlights, button text on dark backgrounds |
| Focus Border | `#c5c4c2` | `--color-focus-border` | Medium-contrast borders, control outlines, and structural separators. Do not promote it to the primary CTA color |

## Tokens — Typography

### Camera Plain Variable — The primary typeface for all text content. Its variable nature allows for precise weight control, delivering compact, high-density information without feeling cluttered. The slight negative letter-spacing (-0.0250em) throughout reinforces this compact aesthetic. · `--font-camera-plain-variable`
- **Substitute:** Inter, Arial, sans-serif
- **Weights:** 400, 480, 600
- **Sizes:** 12px, 14px, 15px, 16px, 18px, 20px, 36px, 48px, 60px
- **Line height:** 1.00, 1.10, 1.25, 1.38, 1.50, 1.60
- **Letter spacing:** -0.0250em
- **OpenType features:** `"liga" 0`
- **Role:** The primary typeface for all text content. Its variable nature allows for precise weight control, delivering compact, high-density information without feeling cluttered. The slight negative letter-spacing (-0.0250em) throughout reinforces this compact aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.3px | `--text-caption` |
| body | 16px | 1.5 | -0.4px | `--text-body` |
| subheading | 20px | 1.38 | -0.5px | `--text-subheading` |
| heading | 36px | 1.25 | -0.9px | `--text-heading` |
| display | 60px | 1.1 | -1.5px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 73 | 73px | `--spacing-73` |
| 80 | 80px | `--spacing-80` |
| 144 | 144px | `--spacing-144` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 12px |
| buttons | 8px |
| inputField | 28px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.08) 0px 0.5px 0px 0px inset, rgba(0, 0, 0...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-3` |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 32px
- **Card padding:** 20px
- **Element gap:** 6px

## Components

### Primary Navigation Link
**Role:** Top navigation items and footer links that guide users through the site structure.

Text Primary (#1c1c1c), Camera Plain Variable, weight 400 at 16px, line height 1.5. Uses Border Light (#eceae4) as a subtle bottom border hint on hover. Padding is 6px left/right, 4px top/bottom.

### Ghost Header Button
**Role:** Call to action buttons in the header, encouraging login or getting started.

Background transparent, Text Primary (#1c1c1c), Camera Plain Variable, weight 400 at 16px, line height 1.5. Subtle border of Border Light (#eceae4). Default radius of 9999px. Padding of 4px top/bottom, 6px left/right. Examples: 'Log in', 'Get started'.

### Pill Accent Button
**Role:** Small, informational buttons or tags with a rounded 'pill' shape.

Text Primary (#1c1c1c), on rgba(0, 0, 0, 0) background with Border Light (#eceae4) border. Uses 9999px border-radius, 6px top/bottom, 10px left/right padding.  Example: 'New Try the Lovable mobile app'.

### Hero Input Field
**Role:** Prominent text input for primary action on the hero section.

Canvas White (#fcfbf8) background, Text Secondary (#5f5f5d) for placeholder. Camera Plain Variable, weight 400 at 18px. Features a 28px border-radius. Padding 24px top/bottom, 24px left/right. Subtle inset shadow on interaction: rgba(0,0,0,0.08) 0px 0.5px inset, rgba(0,0,0,0.16) 0px -0.5px inset, rgb(0,0,0) 0px 0px 0px 0.5px inset, rgba(255,255,255,0.24) 0px 1px inset, rgba(255,255,255,0.16) 0px -1px inset, rgba(0,0,0,0.12) 0px 2px 2px -1px, rgba(0,0,0,0.12) 0px 4px 4px -2px.

### Feature Card
**Role:** Displays featured content or product examples in a grid layout.

Canvas White (#fcfbf8) background with 16px border-radius. Padding is 24px top/bottom for content, with no horizontal padding internally. Examples: 'Personal portfolio', 'Lovable slides'.

### Content Block Card
**Role:** Container for descriptive content, like feature explanations or testimonials.

Canvas White (#fcfbf8) background with a large 24px border-radius. Internal padding is 24px top/bottom, 20px left/right. No shadow, creating a flat, embedded surface appearance.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#fcfbf8) for backgrounds and main surfaces, maintaining a bright, open aesthetic.
- Use Text Primary (#1c1c1c) for all primary text content and main navigational elements.
- Apply Camera Plain Variable with a global letter-spacing of -0.0250em for a compact typographic feel.
- Always use a 9999px border-radius for 'pill' shaped buttons and tags.
- Reserve the Accent Gradient for hero sections or significant atmospheric backgrounds to highlight key content.
- Maintain a clear visual hierarchy by differentiating text sizes and weights, making key information bold without sacrificing the compact feel.
- Use a default element spacing of 6px to create consistent but dense information blocks.

### Don't
- Avoid applying strong box-shadows; prefer minimal elevation with soft inset shadows or no shadows to maintain a flat, modern surface design.
- Do not introduce new saturated accent colors outside of the defined Accent Gradient, as the system relies on a predominantly neutral palette.
- Refrain from using excessively large padding or margins that break the compact information density of the layout.
- Do not deviate from the specified border radii; 16px for cards, 8px for buttons, and 28px for prominent input fields are design signatures.
- Avoid decorative imagery that competes with the subtle UI; visuals should support content without overwhelming it.
- Do not use generic system fonts; always implement Camera Plain Variable for brand consistency.
- Avoid heavy borders; prefer the subtle Border Light (#eceae4) or no border to keep elements lightweight.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Base | `#fcfbf8` | Dominant background for the entire page, providing a bright, clean foundation. Used for main content areas and default surfaces. |
| 1 | Card Surface | `#fcfbf8` | Used for content cards and elevated blocks, maintaining the Canvas Base color but distinguished by border-radius and subtle shadowing or padding. |
| 2 | Input / Interactive Surface | `#fcfbf8` | Applied to input fields and interactive elements. Shares the Canvas Base color, but interaction is visually indicated through distinct border-radii, focus states, and subtle inset shadows. |

## Elevation

- **Input Field:** `rgba(0, 0, 0, 0.08) 0px 0.5px 0px 0px inset, rgba(0, 0, 0, 0.16) 0px -0.5px 0px 0px inset, rgb(0, 0, 0) 0px 0px 0px 0.5px inset, rgba(255, 255, 255, 0.24) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.16) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.12) 0px 2px 2px -1px, rgba(0, 0, 0, 0.12) 0px 4px 4px -2px`
- **Hovered Card:** `oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px`

## Imagery

Imagery primarily consists of contained product screenshots and template previews, often presented within rounded rectangles. There's also use of abstract gradients as backgrounds. Photography is absent from the core UI, deferring to the colorful 'Accent Gradient' for visual flair. Icons are minimal, either filled or outlined, appearing primarily in a monochromatic Text Primary or Text Secondary color, without multicolor applications.

## Layout

The page primarily follows a max-width contained layout set at 1280px, with content centered. The hero section, however, breaks this pattern by featuring a full-bleed, vibrant gradient background with a centered headline and interactive input field. Subsequent sections typically alternate between a clear Canvas White (#fcfbf8) background and slightly off-white (Canvas White equivalent as the main page canvas). Content is arranged in flexible patterns, including centered text stacks, and multi-column grids for feature lists (e.g., text adjacent to a blank area) and template showcases (3-column card grid). Vertical spacing between sections is generally consistent with a 32px section gap.

## Agent Prompt Guide

Quick Color Reference:
text: #1c1c1c
background: #fcfbf8
border: #eceae4
accent: #1f55f1
primary action: no distinct CTA color

Example Component Prompts:
1. Create a header with 'Log in' and 'Get started' ghost buttons. Both buttons should have Text Primary (#1c1c1c) text, a transparent background, 9999px radius, 4px vertical and 6px horizontal padding, and a subtle Border Light (#eceae4) border.
2. Design a hero section headline: 'Build something Lovable' in Text Primary (#1c1c1c), Camera Plain Variable, weight 600, 60px size, line height 1.1, letter-spacing -1.5px. Below it, a sub-headline: 'Create apps and websites by chatting with AI' in Text Primary (#1c1c1c), Camera Plain Variable, weight 400, 20px size, line height 1.38, letter-spacing -0.5px. The background should be the Accent Gradient (#1f55f1).
3. Create a prominent interactive input field: 'Ask Lovable to create a blog about...' using Canvas White (#fcfbf8) background, Text Secondary (#5f5f5d) placeholder, Camera Plain Variable, weight 400, 18px size, 28px border-radius, with 24px padding on all sides. Include the prescribed inset shadow.
4. Design a 'Pill Accent Button': 'New Try the Lovable mobile app' with Text Primary (#1c1c1c), Camera Plain Variable, weight 400 at 16px, background transparent, a Border Light (#eceae4) border, and 9999px border-radius with 6px vertical and 10px horizontal padding.

## Similar Brands

- **Framer** — Shares a modern, bright UI with a focus on interactive elements and subtle distinctions between surface levels.
- **Vercel** — Uses a similar approach to clean, minimal typography, compact layouts, and a very light theme, relying on subtle shadows and borders for depth.
- **Linear** — Exhibits a refined, functional aesthetic with high information density, precise typography, and limited, deliberate color accents.
- **Raycast** — Employs a simple, clear visual style with a strong focus on text readability, subtle interactive elements, and a predominantly light, achromatic color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fcfbf8;
  --color-text-primary: #1c1c1c;
  --color-border-light: #eceae4;
  --color-text-secondary: #5f5f5d;
  --color-text-ghost: #2e2e2d;
  --color-accent-gradient: #1f55f1;
  --gradient-accent-gradient: linear-gradient(90deg, rgb(28, 28, 28) 0px, rgb(28, 28, 28) 33.33%, rgb(130, 188, 255) 40%, rgb(36, 131, 255) 45%, rgb(255, 102, 244) 50%, rgb(255, 48, 41) 55%, rgb(254, 123, 2) 60%, rgba(0, 0, 0, 0) 66.67%, rgba(0, 0, 0, 0));
  --color-text-callout: #030303;
  --color-focus-border: #c5c4c2;

  /* Typography — Font Families */
  --font-camera-plain-variable: 'Camera Plain Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.3px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.4px;
  --text-subheading: 20px;
  --leading-subheading: 1.38;
  --tracking-subheading: -0.5px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: -0.9px;
  --text-display: 60px;
  --leading-display: 1.1;
  --tracking-display: -1.5px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w480: 480;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-73: 73px;
  --spacing-80: 80px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 32px;
  --card-padding: 20px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 12px;
  --radius-buttons: 8px;
  --radius-inputfield: 28px;

  /* Shadows */
  --shadow-subtle: oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.08) 0px 0.5px 0px 0px inset, rgba(0, 0, 0, 0.16) 0px -0.5px 0px 0px inset, rgb(0, 0, 0) 0px 0px 0px 0.5px inset, rgba(255, 255, 255, 0.24) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.16) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.12) 0px 2px 2px -1px, rgba(0, 0, 0, 0.12) 0px 4px 4px -2px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;

  /* Surfaces */
  --surface-canvas-base: #fcfbf8;
  --surface-card-surface: #fcfbf8;
  --surface-input-interactive-surface: #fcfbf8;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fcfbf8;
  --color-text-primary: #1c1c1c;
  --color-border-light: #eceae4;
  --color-text-secondary: #5f5f5d;
  --color-text-ghost: #2e2e2d;
  --color-accent-gradient: #1f55f1;
  --color-text-callout: #030303;
  --color-focus-border: #c5c4c2;

  /* Typography */
  --font-camera-plain-variable: 'Camera Plain Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.3px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.4px;
  --text-subheading: 20px;
  --leading-subheading: 1.38;
  --tracking-subheading: -0.5px;
  --text-heading: 36px;
  --leading-heading: 1.25;
  --tracking-heading: -0.9px;
  --text-display: 60px;
  --leading-display: 1.1;
  --tracking-display: -1.5px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-73: 73px;
  --spacing-80: 80px;
  --spacing-144: 144px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;

  /* Shadows */
  --shadow-subtle: oklab(0 0 0 / 0.08) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.08) 0px 0.5px 0px 0px inset, rgba(0, 0, 0, 0.16) 0px -0.5px 0px 0px inset, rgb(0, 0, 0) 0px 0px 0px 0.5px inset, rgba(255, 255, 255, 0.24) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.16) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.12) 0px 2px 2px -1px, rgba(0, 0, 0, 0.12) 0px 4px 4px -2px;
  --shadow-subtle-3: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
}
```
