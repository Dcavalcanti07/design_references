# Prismic — Style Reference
> High-contrast digital canvas

**Theme:** light

Prismic embraces a high-contrast, functionally colorful aesthetic where sharp, modern sans-serif typography grounds an otherwise energetic palette. Neutrals provide a strong foundation for interface elements, while saturated blues, purples, and greens punctuate interactive states and draw attention to key elements. The system balances visual density with comfortable spacing, promoting a clear hierarchy and an approachable feel without sacrificing professionalism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#151515` | `--color-midnight-charcoal` | Page backgrounds, deep surface backgrounds, primary text, filled button backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Card surfaces, primary section backgrounds, inverted text, ghost button text |
| Ash Gray | `#505050` | `--color-ash-gray` | Muted text, secondary button text, subtle borders |
| Moonlight Gray | `#eeeeee` | `--color-moonlight-gray` | Hairline borders, subtle dividers, ghost button borders |
| Light Taupe | `#f7f7f7` | `--color-light-taupe` | Subtle background panels, light card surfaces |
| Sky Burst | `#59b5f8` | `--color-sky-burst` | Blue accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Deep Plum | `#8e44ec` | `--color-deep-plum` | Violet accent for outlined action borders, linked labels, and lightweight interactive emphasis. Do not promote it to the primary CTA color |
| Jade Glow | `#3bbb96` | `--color-jade-glow` | Green decorative accent for icons, marks, and small graphic details |
| Cool Mint | `#e8f8f3` | `--color-cool-mint` | Lightest background for accent cards, subtle highlights |
| Pale Peach | `#fef1e9` | `--color-pale-peach` | Light background for accent cards |
| Soft Lavender | `#f5e6ff` | `--color-soft-lavender` | Light background for accent cards |
| Powder Blue | `#e6f7fe` | `--color-powder-blue` | Light background for accent cards |
| Faded Lilac | `#e8c7ff` | `--color-faded-lilac` | Accent card backgrounds, subtle list item backgrounds |
| Icy Blue | `#c3eefe` | `--color-icy-blue` | Accent card backgrounds, subtle list item backgrounds |
| Warm Beige | `#fcdac4` | `--color-warm-beige` | Accent card borders |
| Delicate Green | `#d4f2e9` | `--color-delicate-green` | Accent card borders |

## Tokens — Typography

### copyFont — copyFont — detected in extracted data but not described by AI · `--font-copyfont`
- **Weights:** 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 22px
- **Line height:** 1, 1.14, 1.43, 1.45, 1.5, 1.56
- **Role:** copyFont — detected in extracted data but not described by AI

### Inter — General body text, navigation items, buttons, links, and list items. Text is usually compact but highly legible. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** normal
- **Role:** General body text, navigation items, buttons, links, and list items. Text is usually compact but highly legible.

### Inter — Headlines throughout the site, characterized by tighter tracking at larger sizes to maintain a sleek, modern appearance. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 
- **Sizes:** 
- **Line height:** 
- **Letter spacing:** -0.025em
- **Role:** Headlines throughout the site, characterized by tighter tracking at larger sizes to maintain a sleek, modern appearance.

### headingsFont — headingsFont — detected in extracted data but not described by AI · `--font-headingsfont`
- **Weights:** 500, 700
- **Sizes:** 16px, 18px, 22px, 28px, 32px, 40px, 56px
- **Line height:** 1.1, 1.13, 1.14, 1.27, 1.33, 1.38
- **Letter spacing:** -0.025
- **Role:** headingsFont — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.45 | — | `--text-subheading` |
| heading-sm | 22px | 1.14 | — | `--text-heading-sm` |
| heading | 28px | 1.27 | -0.7px | `--text-heading` |
| heading-lg | 32px | 1.13 | -0.8px | `--text-heading-lg` |
| display | 56px | 1.1 | -1.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| icons | 9999px |
| links | 2px |
| buttons | 8px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 32px
- **Card padding:** 40px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call-to-action button for initiating key actions.

Background: Midnight Charcoal (#151515), Text: Canvas White (#ffffff), Padding: 12px vertical, 24px horizontal, Radius: 8px, Font: Inter weight 500, 16px.

### Ghost Button
**Role:** Secondary calls-to-action, or less emphasized actions.

Background: transparent, Text: Canvas White (#ffffff) or Ash Gray (#505050), Border: 1px transparent, Radius: 0px or 8px depending on context, Padding: 0px or 16px vertical depends on context, no horizontal padding.

### Navigation Link
**Role:** Primary navigation items in the header and footer.

Text: Midnight Charcoal (#000000) or Canvas White (#ffffff), Font: Inter weight 500, 16px. Underline on hover.

### Branded Accordion Card
**Role:** Informational cards presenting features or testimonials, often with a unique accent background.

Backgrounds: Soft Lavender (#f5e6ff), Cool Mint (#e8f8f3), Pale Peach (#fef1e9), or Powder Blue (#e6f7fe). Radius: 12px. Padding: 40px all sides. No shadow, flat surface.

### Outlined Accent Button
**Role:** Action buttons emphasizing connection to specific brand colors.

Background: transparent, Text: Deep Plum (#8e44ec) or Sky Burst (#59b5f8), Border: 1px currentColor, Radius: 8px. Font: Inter weight 500, 16px. Padding: 12px vertical, 24px horizontal.

## Do's and Don'ts

### Do
- Prioritize Midnight Charcoal (#151515) for all primary text and dark backgrounds and Canvas White (#ffffff) for light backgrounds and inverted text to maintain high contrast.
- Use Inter font family exclusively, applying a negative letter-spacing of -0.025em for all headings to create a distinctive, sleek appearance.
- Apply a consistent border-radius of 8px for buttons and 12px for cards, reserving 9999px for small circular accents like icons.
- Utilize Sky Burst (#59b5f8), Deep Plum (#8e44ec), and Jade Glow (#3bbb96) sparingly as functional accents for interactive elements, icons, and significant headings.
- Maintain comfortable spacing: 32px for section gaps, 40px for card interior padding, and 16px for vertical spacing between elements within sections.
- Structure pages within a 1280px max-width container, ensuring content is centered and never spans the full viewport unless explicitly designed as a full-bleed hero.
- Employ the light accent background colors like Soft Lavender (#f5e6ff) or Cool Mint (#e8f8f3) for cards or highlighted sections to add visual interest without heavy reliance on shadows.

### Don't
- Do not use highly saturated colors for large background areas or extensive body text; reserve them for accents and interactive elements.
- Avoid generic border-radii; adhere strictly to 2px for links, 8px for buttons, 12px for cards, and 9999px for icons.
- Do not introduce additional font families; maintain consistency with the Inter font for all typographic elements.
- Refrain from heavy drop shadows or elaborate elevation effects; surfaces are predominantly flat, and dimension comes from color contrast and varying background tints.
- Do not vary letter-spacing for body text; only use the specified negative tracking for headlines.
- Avoid dense, information-heavy layouts; ensure ample negative space using the defined element, card, and section gaps for a comfortable user experience.
- Do not default to standard black for all text; differentiate with Ash Gray (#505050) for muted or secondary text.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background, base for content sections |
| 2 | Light Taupe | `#f7f7f7` | Subtle background for alternating sections or elevated content blocks |
| 3 | Accent Card Backgrounds | `#fff` | Specialized cards and testimonials, using hues like #f5e6ff, #e8f8f3, #fef1e9, #e6f7fe for thematic grouping |
| 4 | Midnight Charcoal Deep | `#151515` | Overlapping dark sections, footer, or focused informational panels |

## Imagery

The site primarily uses flat, outlined, geometric illustrations in brand colors (Sky Burst, Deep Plum, Jade Glow) which have a clean, technical feel. These abstract shapes often have connecting lines, suggesting flow and data. Product screenshots are minimal, focused, and integrated subtly. Icons are either outlined or solid, simple, and monochromatic or tinted with brand colors. Imagery serves an explanatory and decorative role, suggesting functionality and process rather than showcasing product UIs or lifestyle photography. Image density is moderate, used to break up text and add visual interest rather than dominate the layout.

## Layout

The page layout follows a centered, max-width (1280px) container model with the exception of the hero section which is mostly full-bleed. The hero features a large, centered headline over a dark background with illustrative abstract graphics in the corners, immediately establishing the brand's visual identity. Vertical rhythm is established through consistent section gaps (32px), often alternating between a Canvas White background and a slightly darker Midnight Charcoal or Light Taupe. Content sections frequently use two-column layouts, often with text on one side and a visual element or card on the other, sometimes alternating. A grid of accent-colored cards is used for testimonials. Navigation is a sticky top bar, with prominent buttons and links.

## Agent Prompt Guide

primary action: #151515 (filled action)
Create a Primary Action Button: #151515 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a testimonial card on a Canvas White background: Background Soft Lavender (#f5e6ff). Text 'This is a great product.' using Inter, 16px, weight 500, #151515. Subtext 'User Name, Company' using Inter, 14px, weight 500, #505050. Radius 12px, padding 40px all sides.

Create a dark feature panel: Background Midnight Charcoal (#151515). Heading 'Developers: Create a custom page builder' using Inter, 28px, weight 700. Accent color Deep Plum (#8e44ec) for 'Developers:'. Body text 'Use our developer tool...' using Inter, 16px, weight 500, #ffffff. Outlined Accent Button 'Explore your Prismic Journey' using Deep Plum as border and text color, 8px radius, 12px vertical padding, 24px horizontal padding.

## Similar Brands

- **Sanity.io** — Shares a high-contrast dark theme alongside vibrant accent colors for UI elements and a technical, modular aesthetic.
- **Vercel** — Exhibits a similar modern, development-focused design with restrained use of accent colors on a largely monochrome background and crisp typography.
- **Linear** — Features a strong emphasis on functional minimalism, precise typography with subtle letter-spacing, and a limited, purposeful color palette for interactive elements.
- **Supabase** — Uses dark backgrounds, bright accent colors, and geometric illustrations to convey a modern developer-tool aesthetic.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #151515;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #505050;
  --color-moonlight-gray: #eeeeee;
  --color-light-taupe: #f7f7f7;
  --color-sky-burst: #59b5f8;
  --color-deep-plum: #8e44ec;
  --color-jade-glow: #3bbb96;
  --color-cool-mint: #e8f8f3;
  --color-pale-peach: #fef1e9;
  --color-soft-lavender: #f5e6ff;
  --color-powder-blue: #e6f7fe;
  --color-faded-lilac: #e8c7ff;
  --color-icy-blue: #c3eefe;
  --color-warm-beige: #fcdac4;
  --color-delicate-green: #d4f2e9;

  /* Typography — Font Families */
  --font-copyfont: 'copyFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-headingsfont: 'headingsFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.14;
  --text-heading: 28px;
  --leading-heading: 1.27;
  --tracking-heading: -0.7px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.8px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.4px;

  /* Typography — Weights */
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 32px;
  --card-padding: 40px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-icons: 9999px;
  --radius-links: 2px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-light-taupe: #f7f7f7;
  --surface-accent-card-backgrounds: #fff;
  --surface-midnight-charcoal-deep: #151515;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #151515;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #505050;
  --color-moonlight-gray: #eeeeee;
  --color-light-taupe: #f7f7f7;
  --color-sky-burst: #59b5f8;
  --color-deep-plum: #8e44ec;
  --color-jade-glow: #3bbb96;
  --color-cool-mint: #e8f8f3;
  --color-pale-peach: #fef1e9;
  --color-soft-lavender: #f5e6ff;
  --color-powder-blue: #e6f7fe;
  --color-faded-lilac: #e8c7ff;
  --color-icy-blue: #c3eefe;
  --color-warm-beige: #fcdac4;
  --color-delicate-green: #d4f2e9;

  /* Typography */
  --font-copyfont: 'copyFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-headingsfont: 'headingsFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.45;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.14;
  --text-heading: 28px;
  --leading-heading: 1.27;
  --tracking-heading: -0.7px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.8px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.4px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;
}
```
