# Becklyn — Style Reference
> Inky canvas, stark white lines

**Theme:** dark

Becklyn employs a deep, inky canvas with stark white text, establishing a high-contrast foundation for a digital agency. Typography blends assertive, almost brutalist sans-serifs with classic serifs for accent, creating a mood of modern authority with a nod to traditional craft. Components are defined by sharp edges or subtle curves and ghost-like interactions, prioritizing functionality without heavy ornamentation. The visual system is rooted in a dark mode aesthetic, allowing a single vivid gradient accent to provide energetic punctuation against an otherwise monochrome backdrop.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#1a1a1a` | `--color-midnight-ink` | Primary page background, card base. This deep black serves as the foundational surface for the dark theme |
| Ghost White | `#ffffff` | `--color-ghost-white` | Primary text, interactive elements (links, buttons) against dark backgrounds, borders, and some light-themed card surfaces. Establishes high contrast |
| Charcoal Gray | `#3b3b3b` | `--color-charcoal-gray` | Secondary card surfaces, providing subtle elevation and differentiation from the main background |
| Steel Gray | `#606060` | `--color-steel-gray` | Muted text, subtle borders, and contextual information, suggesting secondary importance without losing visibility |
| Spectrum Burst | `linear-gradient(200deg, rgb(0, 78, 255) 0%, rgb(113, 9, 102) 75%, rgb(142, 46, 69) 100%)` | `--color-spectrum-burst` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |

## Tokens — Typography

### UniversalSans — Primary content typeface for most headings, body text, and interactive elements. Its modern, geometric feel provides a sharp and contemporary voice. · `--font-universalsans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 20px, 22px, 36px, 42px, 68px, 92px
- **Line height:** 1.00, 1.05, 1.15, 1.20
- **Letter spacing:** -0.0590em at 92px, -0.0430em at 68px, -0.0250em at 42px, -0.0240em at 36px, -0.0230em at 22px, -0.0140em at 20px, auto at 12px
- **Role:** Primary content typeface for most headings, body text, and interactive elements. Its modern, geometric feel provides a sharp and contemporary voice.

### Cambon — Decorative serif typeface used sparingly for impactful headlines and large display text, providing an elegant and authoritative counterpoint to the dominant sans-serif. · `--font-cambon`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 22px, 68px, 92px
- **Line height:** 1.00, 1.15
- **Letter spacing:** -0.0550em at 92px, -0.0180em at 68px, -0.0130em at 22px
- **Role:** Decorative serif typeface used sparingly for impactful headlines and large display text, providing an elegant and authoritative counterpoint to the dominant sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.15 | — | `--text-caption` |
| body | 20px | 1.2 | -0.28px | `--text-body` |
| subheading | 22px | 1.2 | -0.506px | `--text-subheading` |
| heading-sm | 36px | 1.2 | -0.9px | `--text-heading-sm` |
| heading | 42px | 1.2 | -1.008px | `--text-heading` |
| heading-lg | 68px | 1.05 | -2.924px | `--text-heading-lg` |
| display | 92px | 1 | -5.428px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px, 20px |
| subtle | 23px, 31px |
| buttons | 100px |

### Layout

- **Page max-width:** 503px
- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Ghost Navigation Link (Dark)
**Role:** Global navigation item

Text in Ghost White on a Midnight Ink background, no explicit padding, no specific border-radius. Relies on negative letter-spacing for large text.

### Ghost Navigation Link (Light)
**Role:** Footer navigation item

Text in Midnight Ink on a Ghost White background, no explicit padding, no specific border-radius. Used for light-themed footer links.

### Circular Toggle Button
**Role:** Interactive control or status indicator

Ghost White text on a Ghost White background with a 100px border-radius, creating a circular shape. No padding defined, implying content fills the circle.

### Information Card (Charcoal)
**Role:** Content container, feature display

Background Charcoal Gray (#3b3b3b), with 10px border-radius. No explicit padding mentioned, suggesting content handles its own spacing internally.

### Information Card (Midnight)
**Role:** Prominent content container

Background Midnight Ink (#1a1a1a), with 20px border-radius and 20px top padding. Used for more prominent or larger content blocks.

### System Notification Popup
**Role:** Temporary information or cookie consent

This appears as a Charcoal Gray (#3b3b3b) card with a 10px border-radius. It likely uses 20px padding for its content, ensuring comfortable spacing.

### Primary Action Button (Gradient)
**Role:** Main call to action, interactive button

A filled button with the Spectrum Burst gradient (linear-gradient(200deg, rgb(0, 78, 255) 0%, rgb(113, 9, 102) 75%, rgb(142, 46, 69) 100%)) as its background. Text color is Ghost White. It uses a 10px border-radius and has a generous padding appropriate for interaction.

## Do's and Don'ts

### Do
- Prioritize a dark aesthetic with a Midnight Ink (#1a1a1a) background for most surfaces and Ghost White (#ffffff) for primary text and interactive elements.
- Use UniversalSans for all body text, UI elements, and most headlines, primarily at weight 400 for clarity and a modern feel.
- Reserve Cambon for high-impact display headlines (68px or 92px) to add a touch of classic elegance against the modern sans-serif majority.
- Apply negative letter-spacing aggressively on larger text sizes (e.g., -0.0590em at 92px) to ensure titles feel tight and impactful.
- Employ Charcoal Gray (#3b3b3b) as a subtle background for elevated cards or secondary content blocks, providing minimal surface differentiation.
- Use 100px border-radius for all button-like interactive elements to create a distinct pill or circular shape.
- Introduce the Spectrum Burst gradient (linear-gradient(...) #004eff) as a deliberate accent for primary calls-to-action or critical highlights against the dark monochrome. Use it sparingly.

### Don't
- Avoid using bright, saturated colors universally; restrict them to the Spectrum Burst gradient for accent.
- Do not use generic box-shadows or heavy elevation; surfaces should primarily differentiate through background color shifts.
- Avoid mixed-case headings unless Cambon is specifically used for a decorative effect; otherwise, maintain clear typographic hierarchy with UniversalSans.
- Do not deviate from the established letter-spacing values, especially for headlines, as it defines a key part of the typographic personality.
- Avoid complex border styles or heavy strokes; the design favors minimal borders (if any) or very thin outlines in Ghost White.
- Do not use Ghost White as a background color unless for specific, small, and contained elements like the footer on some pages, where it acts as a rare inversion of the dominant dark theme.
- Do not apply large, standard padding to interactive ghost buttons; they are designed to be visually lightweight and contextually driven by text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Canvas | `#1a1a1a` | Base page background, darkest surface layer. |
| 1 | Charcoal Card | `#3b3b3b` | Elevated card backgrounds, slightly lighter than the canvas to provide subtle depth. |

## Imagery

Imagery is minimal, primarily focusing on abstract graphics or subtle, full-bleed backgrounds where visible. When present, product or concept visuals are handled with a dark aesthetic, often blending into the background. Icons, when visible, appear as simple outlines in Ghost White. The density is text-dominant, with ample breathing room, pushing imagery to a supporting, atmospheric role rather than a direct content showcase. There is no evidence of photography, illustrations, or 3D renders. The aesthetic is pure UI and typography driven.

## Layout

The page uses a contained layout within a maximum width of 503px, centered within the full viewport. The hero section often features a large, dark background with centered, prominent Cambon typography. Sections flow vertically with comfortable spacing (40px section gap), and content is primarily displayed in stacked, clear blocks, often anchored by large headings. There are instances of 2-column card grids for features. Navigation is primarily a minimal top-bar and a bottom-fixed navigation bar, both using ghost-style links.

## Agent Prompt Guide

### Quick Color Reference
text: #ffffff
background: #1a1a1a
border: #ffffff
accent: #004eff
primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a Hero Section: Background Midnight Ink (#1a1a1a). Centered headline 'Wir transformieren Ideen in Experiences.' using Cambon 92px, Ghost White (#ffffff), letter-spacing -5.428px.
2. Design an Information Card: Charcoal Gray (#3b3b3b) background, 10px border-radius, with 20px padding. Inside, use UniversalSans 20px (#ffffff) for a title and UniversalSans 12px (#606060) for a caption, separated by 10px vertical space.
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
4. Create a Ghost Navigation Link: Ghost White (#ffffff) text using UniversalSans 22px, no background, no borders, with letter-spacing -0.506px.
5. Design a prominent content block: Midnight Ink (#1a1a1a) background, 20px border-radius, with 20px top padding. Use UniversalSans 42px (#ffffff) for main text, -1.008px letter-spacing.

## Similar Brands

- **Linear** — Dark UI with strong typographic hierarchy, high contrast, and minimal use of accent colors.
- **Supabase** — Dominant dark theme, sharp edges balanced with subtle radii, and a high-tech, developer-centric feel.
- **Vercel** — Focus on high-contrast text and a clean, almost brutalist typography, operating within a largely dark mode context.
- **Figma (dark mode)** — Dark surface treatments and highly legible text against them, with accent colors used functionally and sparingly.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #1a1a1a;
  --color-ghost-white: #ffffff;
  --color-charcoal-gray: #3b3b3b;
  --color-steel-gray: #606060;
  --color-spectrum-burst: #004eff;
  --gradient-spectrum-burst: linear-gradient(200deg, rgb(0, 78, 255) 0%, rgb(113, 9, 102) 75%, rgb(142, 46, 69) 100%);

  /* Typography — Font Families */
  --font-universalsans: 'UniversalSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cambon: 'Cambon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.15;
  --text-body: 20px;
  --leading-body: 1.2;
  --tracking-body: -0.28px;
  --text-subheading: 22px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.506px;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.9px;
  --text-heading: 42px;
  --leading-heading: 1.2;
  --tracking-heading: -1.008px;
  --text-heading-lg: 68px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -2.924px;
  --text-display: 92px;
  --leading-display: 1;
  --tracking-display: -5.428px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 503px;
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-2xl-2: 23px;
  --radius-3xl: 31px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 10px, 20px;
  --radius-subtle: 23px, 31px;
  --radius-buttons: 100px;

  /* Surfaces */
  --surface-midnight-canvas: #1a1a1a;
  --surface-charcoal-card: #3b3b3b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #1a1a1a;
  --color-ghost-white: #ffffff;
  --color-charcoal-gray: #3b3b3b;
  --color-steel-gray: #606060;
  --color-spectrum-burst: #004eff;

  /* Typography */
  --font-universalsans: 'UniversalSans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-cambon: 'Cambon', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.15;
  --text-body: 20px;
  --leading-body: 1.2;
  --tracking-body: -0.28px;
  --text-subheading: 22px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.506px;
  --text-heading-sm: 36px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.9px;
  --text-heading: 42px;
  --leading-heading: 1.2;
  --tracking-heading: -1.008px;
  --text-heading-lg: 68px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -2.924px;
  --text-display: 92px;
  --leading-display: 1;
  --tracking-display: -5.428px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-2xl-2: 23px;
  --radius-3xl: 31px;
  --radius-full: 100px;
}
```
