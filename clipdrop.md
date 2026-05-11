# Clipdrop — Style Reference
> High-contrast digital canvas

**Theme:** light

Clipdrop employs a crisp, functional visual style with a preference for minimalist UI and high-contrast typography. The design emphasizes clarity and directness through a predominantly achromatic palette, punctuated by a vivid blue for primary actions and a warm orange for secondary states or brand emphasis. Components are lightweight with defined borders and soft, rounded corners, conveying a sense of approachability and digital precision. The layout is structured and spacious, allowing content and product visuals to take center stage.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, prominent elevated surfaces, button text |
| Ash Gray | `#ededed` | `--color-ash-gray` | Subtle surface accents, borders, ghost button backgrounds, subtle hover states |
| Graphite Black | `#000000` | `--color-graphite-black` | Primary headings, most body text, high-contrast UI elements |
| Charcoal | `#2d2d2d` | `--color-charcoal` | Secondary headings, darker text for contrast in specific contexts |
| Slate Steel | `#404040` | `--color-slate-steel` | Muted body text, descriptive labels, icon fills |
| Silver Mist | `#767676` | `--color-silver-mist` | Helper text, subordinate information, low-emphasis text fields |
| Medium Gray | `#8f8f8f` | `--color-medium-gray` | Card backgrounds behind content, default placeholders |
| Subtle Blue | `#c9d7f5` | `--color-subtle-blue` | Subtle background washes, light button states |
| Midnight Ink | `#171717` | `--color-midnight-ink` | Hover states for text, dark icons |
| Cerulean Blue | `#1c60f6` | `--color-cerulean-blue` | Primary action buttons, active indicators, brand accent for interaction |
| Jasper Orange | `#fa4028` | `--color-jasper-orange` | Orange action color for filled buttons, selected navigation states, and focused conversion moments |
| Deep Plum | `#24355c` | `--color-deep-plum` | Icon fills, text within certain buttons, for a deeper brand accent |

## Tokens — Typography

### Primary — General body text, navigation elements, form labels, and smaller UI text. The varied weights provide hierarchy within compact elements. · `--font-primary`
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 20px
- **Line height:** 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** General body text, navigation elements, form labels, and smaller UI text. The varied weights provide hierarchy within compact elements.

### SecondaryFont — Large display headings for hero sections and prominent textual branding. The tight letter-spacing at large sizes creates a polished, impactful look. · `--font-secondaryfont`
- **Weights:** 400
- **Sizes:** 60px, 96px
- **Line height:** 1.10
- **Letter spacing:** -0.0200em
- **Role:** Large display headings for hero sections and prominent textual branding. The tight letter-spacing at large sizes creates a polished, impactful look.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| body-lg | 20px | 1.4 | — | `--text-body-lg` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| pills | 9999px |
| buttons | 12px |
| default | 16px |

### Layout

- **Section gap:** 64px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Call to action button

Filled with Cerulean Blue (#1c60f6), white text, 12px border-radius, with 12px vertical and 20px horizontal padding. Prominently signals the most important user actions.

### Secondary Filled Button
**Role:** Call to action button

Filled with Jasper Orange (#fa4028), white text, 12px border-radius, with 12px vertical and 20px horizontal padding. Used for alternative or secondary calls to action.

### Ghost Button
**Role:** Subtle action button

Transparent background, Charcoal text (#2d2d2d), with a 12px border-radius and 12px vertical and 20px horizontal padding. For less prominent actions or navigation.

### Soft Gray Button
**Role:** Neutral action button

Filled with Ash Gray (#ededed), Charcoal text (#2d2d2d), 12px border-radius, with 12px vertical and 20px horizontal padding. Used for tertiary actions or filter controls.

### Image Card
**Role:** Content container for media

Background color Medium Gray (#8f8f8f) or a subtle 35% transparent Dark Gray, 16px border-radius, no internal padding, and no shadow. Used to showcase images or tools with visual content.

### Pill Button
**Role:** Tag or category button

Used particularly within navigation. Features a 9999px border-radius creating a pill shape, with text styled by the 'Primary' font at appropriate sizes and weights.

### Accordion Item
**Role:** Expandable content block

Uses a 1px solid Ash Gray (#ededed) border and a 16px border-radius. Features Slate Steel (#404040) text and an element gap of 8px within, facilitating clear content separation.

## Do's and Don'ts

### Do
- Prioritize Graphite Black (#000000) for all primary headline and body text to ensure maximum contrast against Canvas White (#ffffff) backgrounds.
- Use Cerulean Blue (#1c60f6) consistently for all primary interactive elements, including main CTA buttons and active state indicators.
- Apply a 12px border-radius to all interactive buttons and input fields for a consistent, approachable feel.
- Maintain a clear visual hierarchy by utilizing the SecondaryFont at 60px or 96px with -0.0200em letter-spacing for prominent page titles.
- Separate major page sections with a 64px vertical gap, while using 8px for smaller element spacing.
- Employ Ash Gray (#ededed) for hairline borders and subtle background differentiators, avoiding heavy lines or shadows for division.
- Utilize Jasper Orange (#fa4028) strictly for secondary actions or specific brand highlights, reserving it for limited but impactful use.

### Don't
- Do not introduce new saturated colors outside of Cerulean Blue (#1c60f6) and Jasper Orange (#fa4028) without specific functional justification.
- Avoid using drop shadows on cards or containers; opt for distinct background colors and borders to define boundaries.
- Do not use letter-spacing on 'Primary' body text; it should remain normal unless for large SecondaryFont headings.
- Refrain from varying border-radius values for buttons, always use 12px, or 9999px for pill-shaped elements.
- Do not cluster elements excessively; use the defined elementGap of 8px and cardPadding of 12px to ensure comfortable density.
- Avoid using Deep Plum (#24355c) as a primary text color; it's intended for specific icon and accent text roles.
- Do not use Canvas White (#ffffff) for borders; use Ash Gray (#ededed) to maintain subtle visual separation.

## Imagery

The visual language focuses on demonstrating product capabilities through concise, high-contrast examples. Imagery primarily consists of product screenshots and carefully selected photography. Photography shows subjects (people, objects) often in the process of being edited or transformed by the AI, typically on transparent (checkerboard pattern) or pure white backgrounds to highlight the tool's output. Product screenshots are clean and focused on the UI. Icons are typically filled, monochrome, and have a moderate stroke weight, serving a functional rather than decorative purpose, often using the Charcoal (#2d2d2d) or Deep Plum (#24355c) colors. Imagery is contained within defined card shapes with 16px rounded corners, showcasing the edited visuals without overlapping.

## Layout

The page adheres to a max-width contained layout for most content, centered on the screen, though the hero section uses a full-bleed treatment for its visual demonstration. The hero typically features a commanding headline over an interactive video or dynamic visual. Sections maintain a consistent vertical rhythm with 64px gaps. Content is arranged in alternating patterns, often featuring text to one side and a visual or product card to the other, or structured grids of 3-column cards for showcasing tools. The navigation is a persistent top bar featuring minimal branding on the left and utility links/buttons on the right, maintaining a clear and accessible structure.

## Agent Prompt Guide

### Quick Color Reference
text: #000000
background: #ffffff
border: #ededed
accent: #fa4028
primary action: #1c60f6 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #1c60f6 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a navigation link: Text 'Pricing' using Primary font size 16px, weight 400, Graphite Black (#000000). This link should have a 8px border-radius for its interactive state and 6px horizontal padding.

## Similar Brands

- **Figma** — Shares a focus on clean, high-contrast UI with a prominent use of blues for interactive elements and a generally minimalist aesthetic.
- **Canva** — Features a similar lightweight, card-based approach for showcasing tools and templates, with clear actionable buttons against a light background.
- **Remove.bg** — Direct competitor with comparable UI patterns for showcasing AI-powered image editing, emphasizing functionality over heavy styling.
- **Stripe** — Exhibits a similar typographic confidence with large, impactful headlines combined with a concise, high-contrast body text system and a restrained color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ash-gray: #ededed;
  --color-graphite-black: #000000;
  --color-charcoal: #2d2d2d;
  --color-slate-steel: #404040;
  --color-silver-mist: #767676;
  --color-medium-gray: #8f8f8f;
  --color-subtle-blue: #c9d7f5;
  --color-midnight-ink: #171717;
  --color-cerulean-blue: #1c60f6;
  --color-jasper-orange: #fa4028;
  --color-deep-plum: #24355c;

  /* Typography — Font Families */
  --font-primary: 'Primary', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-secondaryfont: 'SecondaryFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 20px;
  --leading-body-lg: 1.4;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-pills: 9999px;
  --radius-buttons: 12px;
  --radius-default: 16px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ash-gray: #ededed;
  --color-graphite-black: #000000;
  --color-charcoal: #2d2d2d;
  --color-slate-steel: #404040;
  --color-silver-mist: #767676;
  --color-medium-gray: #8f8f8f;
  --color-subtle-blue: #c9d7f5;
  --color-midnight-ink: #171717;
  --color-cerulean-blue: #1c60f6;
  --color-jasper-orange: #fa4028;
  --color-deep-plum: #24355c;

  /* Typography */
  --font-primary: 'Primary', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-secondaryfont: 'SecondaryFont', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-body-lg: 20px;
  --leading-body-lg: 1.4;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;
}
```
