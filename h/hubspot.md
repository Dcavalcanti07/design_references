# HubSpot — Style Reference
> Warm,橙色效率

**Theme:** light

HubSpot's visual system evokes a reliable, professional ecosystem with a warm, energetic core. It combines a clean, spacious light theme with strong, structured typography. Muted background tones provide a subtle backdrop for card-based content, while a vibrant orange serves as the primary accent, signaling action and branding. The overall impression is one of clarity and approachable efficiency.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink Black | `#1f1f1f` | `--color-ink-black` | Primary text, deep neutrals for icons and borders, footer background to anchor the page |
| Canvas White | `#fcfcfa` | `--color-canvas-white` | Dominant page background, modal backgrounds, and interactive element fills |
| Frosted Gray | `#f8f5ee` | `--color-frosted-gray` | Muted text, subtle borders, and secondary background layers for visual separation |
| Midnight | `#000000` | `--color-midnight` | Icon fills, explicit dark text for contrast on lighter elements, and stark borders for outlined elements |
| Lead Gray | `#60605f` | `--color-lead-gray` | Muted captions, helper text, and de-emphasized UI labels. Do not promote it to the primary CTA color |
| Pale Ash | `#cacac8` | `--color-pale-ash` | Subtle background for list items or decorative accents, used sparingly |
| Marketing Orange | `#ff4800` | `--color-marketing-orange` | Primary call-to-action buttons, prominent brand icons, and interactive states |
| Accent Violet | `#0000c5` | `--color-accent-violet` | Used as a distinct accent for specific navigation items, creating visual emphasis |
| Sunset Gradient | `linear-gradient(257deg, rgba(251, 221, 208, 0.3) -32.4%, rgba(255, 165, 129, 0.3) -3.42%, rgba(255, 73, 0, 0.3) 23.87%, rgba(251, 223, 233, 0.3) 50.46%, rgba(253, 191, 219, 0.3) 79.15%, rgba(249, 57, 166, 0.3) 103.64%)` | `--color-sunset-gradient` | Soft, multi-hued background gradient for illustrative or decorative elements, creating a sense of depth and vibrancy |

## Tokens — Typography

### HubSpot Sans — General UI text, body copy, subheadings, and most interactive elements. Its range of weights supports hierarchy within compact UI components. · `--font-hubspot-sans`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 22px, 24px, 40px
- **Line height:** 1.10, 1.15, 1.42, 1.45, 1.56, 1.57, 1.60, 1.67, 1.75, 1.78, 2.40
- **Role:** General UI text, body copy, subheadings, and most interactive elements. Its range of weights supports hierarchy within compact UI components.

### HubSpot Serif Page Header Human — Hero page headers; its large size and distinct serif style create a strong visual statement for key messages. · `--font-hubspot-serif-page-header-human`
- **Substitute:** Merriweather
- **Weights:** 500
- **Sizes:** 80px
- **Line height:** 1.19
- **Letter spacing:** normal
- **Role:** Hero page headers; its large size and distinct serif style create a strong visual statement for key messages.

### HubSpot Serif — Section headings and prominent feature titles; provides a refined yet impactful presence for content blocks. · `--font-hubspot-serif`
- **Substitute:** Merriweather
- **Weights:** 500
- **Sizes:** 40px, 48px
- **Line height:** 1.10, 1.15
- **Letter spacing:** normal
- **Role:** Section headings and prominent feature titles; provides a refined yet impactful presence for content blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.75 | — | `--text-caption` |
| body-sm | 14px | 1.78 | — | `--text-body-sm` |
| body | 16px | 1.6 | — | `--text-body` |
| subheading | 18px | 1.67 | — | `--text-subheading` |
| heading-sm | 22px | 1.56 | — | `--text-heading-sm` |
| heading | 24px | 1.45 | — | `--text-heading` |
| heading-lg | 40px | 1.15 | — | `--text-heading-lg` |
| display | 80px | 1.19 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 4px |
| buttons | 8px |

### Layout

- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Call-to-action button for initiating primary user flows.

Filled with Marketing Orange (#ff4800), white text (#ffffff), 8px border-radius, with 16px vertical and 40px horizontal padding.

### Ghost Button (Text Link)
**Role:** Secondary action or navigational link mimicking button behavior.

Transparent background (rgba(0, 0, 0, 0)), Ink Black text (#1f1f1f), 0px border-radius. Padding varies.

### Default Card
**Role:** Container for grouped content, features, or product listings.

Canvas White background (#ffffff), 16px border-radius, no visible shadow, with 32px horizontal and 24-32px vertical padding.

### Badge Pill
**Role:** Small informational tag, often for categorization or status.

Canvas White background (#ffffff), Ink Black text (#1f1f1f), a rounded 16px border-radius, and 16px padding on all sides.

### Tag Badge
**Role:** Smaller, more compact informational tag.

Canvas White background (#ffffff), Ink Black text (#1f1f1f), a subtle 4px border-radius, and 4px vertical, 8px horizontal padding.

### Navigation Link
**Role:** Interactive text link within navigation menus.

Ink Black text (#1f1f1f) on a transparent background, 8px border-radius, with variable padding typically 8px (v) and 16px (h).

## Do's and Don'ts

### Do
- Always use Marketing Orange (#ff4800) for primary call-to-action buttons, ensuring a consistent visual cue for interaction.
- Apply a 16px border-radius to all content cards and larger badge elements to maintain a soft, approachable aesthetic.
- Utilize Ink Black (#1f1f1f) for main body text and prominent headings to optimize readability against light backgrounds.
- Employ HubSpot Serif Page Header Human at 80px, weight 500 for hero section headlines to create impactful, authoritative messaging.
- Maintain a clear visual hierarchy by using Canvas White (#fcfcfa) as the dominant background color for content areas, contrasting it with the footer's Ink Black (#1f1f1f).
- Separate content sections with ample vertical spacing, defaulting to a 24px section gap for comfortable visual rhythm.
- When outlining interactive elements, use Ink Black (#1f1f1f) for borders to create subtle definitions without heavy shadows.

### Don't
- Do not introduce new saturated primary colors; only Marketing Orange (#ff4800) and Accent Violet (#0000c5) serve chromatic roles.
- Avoid using harsh shadows; rely on clear background separation or subtle borders for element distinction instead.
- Do not deviate from the specified typographic hierarchy; specific serif and sans-serif fonts have designated roles for headlines and body text.
- Do not use generic gray buttons; if an action is not primary, use a ghost button style with Ink Black text on a transparent background.
- Do not use less than 8px border-radius for buttons; 8px is the minimum for interactive elements.
- Avoid dense, information-heavy blocks without sufficient padding; ensure cards have at least 32px horizontal and 24px vertical padding.
- Do not place body text directly on a highly saturated background; always ensure a high contrast ratio against Canvas White (#fcfcfa) or similar light neutrals, typically using Ink Black (#1f1f1f).

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#fcfcfa` | Base page background for most content areas, creating a bright and airy feel. |
| 2 | Default Card | `#ffffff` | Primary surface for grouping related content within cards, slightly lighter than Canvas White for subtle elevation. |
| 3 | Ink Black Footer | `#1f1f1f` | Deep, grounding background for the footer section, providing a strong visual anchor at the bottom of the page. |

## Imagery

The site uses a mix of real-world photography and abstract, colorful 3D illustrations. Photography tends to be lifestyle-oriented, often featuring groups of people collaborating in professional but relaxed settings, generally with natural lighting and unmasked, soft edges. Illustrations are abstract, dimensional, and vibrant, using a multi-hued gradient palette. Icons are primarily outlined or flat filled in black or Marketing Orange, maintaining a clean, utilitarian style. Imagery functions decoratively to set a mood and illustrate concepts rather than showcase product UIs directly. Density and placement vary, with a large hero image followed by blocks of text-dominant content, punctuated by smaller abstract visuals.

## Layout

The page primarily uses a max-width contained layout, though the hero section spans full-bleed with content centered over a background image. The hero features a large, centered headline followed by a centered text block and two prominent action buttons. Subsequent sections alternate between text-left/image-right compositions and 2-column or 3-column card grids, maintaining consistent vertical spacing. There are no strong visual dividers between sections; instead, the layout relies on shifts in content type and negative space. Navigation is composed of a sticky top bar with product dropdowns and right-aligned utility links.

## Agent Prompt Guide

Quick Color Reference: 
text: #1f1f1f
background: #fcfcfa
border: #1f1f1f
accent: #ff4800
primary action: #ff4800 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ff4800 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a content card: Canvas White (#ffffff) background, 16px radius, 32px horizontal and 24px vertical padding. Headline: HubSpot Serif weight 500 at 40px, Ink Black (#1f1f1f). Body text: HubSpot Sans weight 400 at 16px, Ink Black (#1f1f1f).
3. Create a secondary ghost button: 'Learn more', transparent background, Ink Black (#1f1f1f) text, 8px radius, HubSpot Sans weight 400 at 16px.

## Similar Brands

- **Salesforce** — Both use a clear, structured layout with a prominent brand color for CTAs on a predominantly light background.
- **Zendesk** — Similar approach to clean, card-based content presentation and a single strong accent color highlighting key interactions.
- **Mailchimp** — Employs an energetic, warm brand color (yellow/orange) to bring personality to a professional, information-dense interface, coupled with custom serif headlines.
- **monday.com** — Shares a modern, light UI with distinct color accents for different functional elements, used sparingly on a clean canvas.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink-black: #1f1f1f;
  --color-canvas-white: #fcfcfa;
  --color-frosted-gray: #f8f5ee;
  --color-midnight: #000000;
  --color-lead-gray: #60605f;
  --color-pale-ash: #cacac8;
  --color-marketing-orange: #ff4800;
  --color-accent-violet: #0000c5;
  --color-sunset-gradient: #ff4900;
  --gradient-sunset-gradient: linear-gradient(257deg, rgba(251, 221, 208, 0.3) -32.4%, rgba(255, 165, 129, 0.3) -3.42%, rgba(255, 73, 0, 0.3) 23.87%, rgba(251, 223, 233, 0.3) 50.46%, rgba(253, 191, 219, 0.3) 79.15%, rgba(249, 57, 166, 0.3) 103.64%);

  /* Typography — Font Families */
  --font-hubspot-sans: 'HubSpot Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hubspot-serif-page-header-human: 'HubSpot Serif Page Header Human', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-hubspot-serif: 'HubSpot Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.75;
  --text-body-sm: 14px;
  --leading-body-sm: 1.78;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.67;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.56;
  --text-heading: 24px;
  --leading-heading: 1.45;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --text-display: 80px;
  --leading-display: 1.19;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 4px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-canvas-white: #fcfcfa;
  --surface-default-card: #ffffff;
  --surface-ink-black-footer: #1f1f1f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink-black: #1f1f1f;
  --color-canvas-white: #fcfcfa;
  --color-frosted-gray: #f8f5ee;
  --color-midnight: #000000;
  --color-lead-gray: #60605f;
  --color-pale-ash: #cacac8;
  --color-marketing-orange: #ff4800;
  --color-accent-violet: #0000c5;
  --color-sunset-gradient: #ff4900;

  /* Typography */
  --font-hubspot-sans: 'HubSpot Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hubspot-serif-page-header-human: 'HubSpot Serif Page Header Human', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-hubspot-serif: 'HubSpot Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.75;
  --text-body-sm: 14px;
  --leading-body-sm: 1.78;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-subheading: 18px;
  --leading-subheading: 1.67;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.56;
  --text-heading: 24px;
  --leading-heading: 1.45;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --text-display: 80px;
  --leading-display: 1.19;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
}
```
