# Vanta — Style Reference
> Regal Clarity on White Canvas

**Theme:** light

Vanta projects a refined, authoritative presence through a primarily achromatic palette accented by deep, vivid violets. Stark white backgrounds provide a sense of expansive clarity, acting as a clean canvas for content. Typography is precise and impactful, balancing a custom sans-serif for functional elements with a sophisticated serif for headlines. Components are lightweight and well-defined by subtle borders, emphasizing content over heavy ornamentation. Elevation is minimal, achieved through soft borders and contained interactions rather than prominent shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, form inputs, button backgrounds |
| Background Snow | `#f7f8fa` | `--color-background-snow` | Subtle section backgrounds, alternative light surfaces |
| Cloud Gray | `#eaeaf1` | `--color-cloud-gray` | Subtle accents for UI elements, light border accents |
| Border Fog | `#dfdfe9` | `--color-border-fog` | Functional borders, dividers, subtle outlines |
| Muted Ash | `#9e9fb7` | `--color-muted-ash` | Secondary borders, ghost button outlines, disabled states |
| Stone Gray | `#6d6e87` | `--color-stone-gray` | Tertiary text, subtle fills, supporting icons |
| Dark Charcoal | `#484960` | `--color-dark-charcoal` | Secondary text, link text, muted headings |
| Midnight Ink | `#181822` | `--color-midnight-ink` | Primary text, main headings, critical information |
| Deep Plum | `#260048` | `--color-deep-plum` | Footer background, secondary brand elements, text on vivid backgrounds |
| Vanta Purple | `#5e05c4` | `--color-vanta-purple` | Primary action buttons, interactive elements, brand accents |
| Royal Violet | `#8f47d5` | `--color-royal-violet` | Link colors, badge text, decorative icon accents |
| Misty Lavender | `#ddd6ff` | `--color-misty-lavender` | Hero background, soft brand washes |
| Sky Lavender | `#cdd2f8` | `--color-sky-lavender` | Supporting background color, subtle brand elevation |
| Warning Gold | `#ffbe0f` | `--color-warning-gold` | Warning badges, informational highlights |

## Tokens — Typography

### Inter Variable — Functional UI text: body copy, navigation, buttons, labels. Its variable nature allows for precise weight control for hierarchy. · `--font-inter-variable`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px, 32px, 40px
- **Line height:** 1.30, 1.35, 1.43, 1.50, 1.60
- **Letter spacing:** -0.0020em
- **Role:** Functional UI text: body copy, navigation, buttons, labels. Its variable nature allows for precise weight control for hierarchy.

### Reckless — Headline text, where its serif elegance softens the technical feel of the content. The lighter weights provide authority through grace. · `--font-reckless`
- **Substitute:** serif
- **Weights:** 400, 500
- **Sizes:** 30px, 42px, 56px, 72px, 90px
- **Line height:** 1.10, 1.20, 1.25
- **Letter spacing:** -0.0180em
- **Role:** Headline text, where its serif elegance softens the technical feel of the content. The lighter weights provide authority through grace.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.6 | -0.2px | `--text-caption` |
| body | 16px | 1.5 | -0.32px | `--text-body` |
| subheading | 20px | 1.43 | -0.4px | `--text-subheading` |
| heading-sm | 24px | 1.35 | -0.48px | `--text-heading-sm` |
| heading | 32px | 1.3 | -0.64px | `--text-heading` |
| heading-lg | 42px | 1.1 | -0.714px | `--text-heading-lg` |
| display | 56px | 1.1 | -0.784px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| inputs | 999px |
| buttons | 999px |
| default | 8px |

### Layout

- **Section gap:** 32px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action button for primary actions

Filled with Vanta Purple (#5e05c4), white text (Vanta White), and a full-rounded (999px) border. Padding is 8px vertical, 12px horizontal.

### Ghost Navigation Button
**Role:** Secondary navigation or subtle actions

Transparent background, Midnight Ink (#181822) text, minimal padding (8px vertical, 10.4px horizontal) and a full-rounded (999px) border.

### Outlined Input Field
**Role:** Text input areas for forms

Canvas White (#ffffff) background, Midnight Ink (#181822) text, full-rounded (999px) border of Muted Ash (#9e9fb7) at 1.5px. Padding is 13.6px vertical, 16px horizontal.

### Elevated Content Card
**Role:** Container for features or grouped information

Canvas White (#ffffff) background, 16px border-radius, no shadow. Padding internal content at 32px all around.

### Feature Highlight Card
**Role:** Cards within hero section or for key features

Transparent background, 0px border-radius, no shadow. Internal padding of 32px.

### Brand Chip Badge
**Role:** Informational tags or status indicators

Transparent background with Royal Violet (#8f47d5) text. No padding or border-radius.

### Warning Badge
**Role:** Notification or status badge indicating a warning

Warning Gold (#ffbe0f) background with Deep Plum (#260048) text. No border-radius, 4px horizontal padding.

## Do's and Don'ts

### Do
- Use Midnight Ink (#181822) for all primary body text and main headings to ensure strong contrast and readability.
- Apply Canvas White (#ffffff) as the default background for most content sections and interactive components.
- Utilize Vanta Purple (#5e05c4) exclusively for primary calls to action, such as 'Get a demo' buttons.
- Maintain a 999px border-radius for all interactive elements like buttons and input fields to ensure a consistent friendly, modern feel.
- Establish hierarchy in headings by using Reckless font, applying its smaller letter-spacing values (-0.0180em to -0.0120em) for larger sizes.
- Use Border Fog (#dfdfe9) or Muted Ash (#9e9fb7) for all hairline borders and subtle dividers.
- Prioritize Inter Variable for all functional text, maintaining -0.0020em letter-spacing for consistency.

### Don't
- Do not introduce strong shadows; rely on subtle borders or background color shifts for element separation.
- Avoid using highly saturated colors for large background areas; reserve them for accents and interactive elements.
- Do not deviate from the full-rounded (999px) radius for buttons and input fields; this is a signature shape.
- Never use Reckless font for body text or other small functional elements; it is reserved for headlines.
- Do not use generic blue for links or interactive elements; all brand interaction should use Royal Violet (#8f47d5) or Vanta Purple (#5e05c4).
- Avoid dense stacking of information; provide ample white space, leveraging Cloud Gray (#eaeaf1) or Background Snow (#f7f8fa) for breathing room.
- Do not use bright or vibrant photography; imagery should be understated, product-focused, or abstract to allow UI to dominate.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Background Snow | `#f7f8fa` | Primary page background |
| 2 | Canvas White | `#ffffff` | Default card surfaces, interactive containers |
| 3 | Sky Lavender | `#cdd2f8` | Accentuated section backgrounds, soft elevated areas |

## Imagery

This site prominently features product screenshots and abstract, geometric illustrations. Product shots are typically contained within cards, showcasing clean UI with minimal surrounding context, emphasizing functionality. Illustrations are often flat or subtly dimensional, using muted brand colors or achromatic tones, serving as decorative accents or explanatory visuals. Icons are predominantly outlined, featuring a moderate stroke weight in either Midnight Ink or Royal Violet, providing clear visual cues without being heavy. Imagery serves as explanatory content, clarifying complex processes rather than creating mood. The overall density is balanced, with imagery carefully placed to break up text blocks without overwhelming the content.

## Layout

The page uses a maximum-width contained layout rather than full-bleed, with content centered. The hero section is full-bleed but employs a lighter background tone (Misty Lavender) with a large, centered headline and a centered sign-up form. Sections alternate a subtle visual rhythm, primarily using Canvas White and Background Snow. Content is typically arranged in clear, symmetrical blocks, often with centered stacks for text and calls to action. Feature sections use a 3-column card grid. Vertical spacing between logical blocks is generous, providing a comfortable density. Navigation is a persistent top bar featuring a minimal logo, clear text links, and distinct 'Log in' (ghost) and 'Get a demo' (filled) buttons.

## Agent Prompt Guide

Quick Color Reference:
- text: #181822
- background: #f7f8fa
- border: #dfdfe9
- accent: #5e05c4
- primary action: #5e05c4 (filled action)

Example Component Prompts:
- Create a hero section with a Misty Lavender (#ddd6ff) background. Headline 'Trust is everything' at 56px Reckless weight 500, #181822, letter-spacing -0.784px. Below, a Ghost Navigation Button with 'Learn more' text in #181822, border #9e9fb7, 999px radius, 8px vertical 10.4px horizontal padding.
- Design a feature card: Canvas White (#ffffff) background, 16px radius, no shadow. Inside, use a heading 'Compliance' at 24px Inter Variable weight 700, #181822, line-height 1.35. Body text at 16px Inter Variable weight 400, #484960.
- Create a Primary Action Button: #5e05c4 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create an input field: Canvas White (#ffffff) background, 999px border-radius, border 1.5px solid Muted Ash (#9e9fb7). Placeholder text should be #484960 at 16px Inter Variable weight 400. Internal padding 13.6px vertical, 16px horizontal.
- Display a Warning Badge with text 'Review' using Warning Gold (#ffbe0f) background and Deep Plum (#260048) text, no border-radius and 4px horizontal padding.

## Similar Brands

- **Ramp** — Similar achromatic background palette with a single bright, vivid accent color for CTAs and interactive states, paired with strong typography.
- **Gusto** — Adoption of a distinct sans-serif for UI and a more expressive serif for headlines, creating a dual typographic personality.
- **Linear** — Emphasis on subtle borders and minimal elevation for component definition over heavy shadows, creating a lightweight feel.
- **Okta** — Clean, enterprise-focused SaaS aesthetic with structured layouts and a strong focus on readability and clear information hierarchy.
- **Brex** — Prominent use of a deep, rich purple as a primary brand accent against a largely neutral background for a premium feel.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-background-snow: #f7f8fa;
  --color-cloud-gray: #eaeaf1;
  --color-border-fog: #dfdfe9;
  --color-muted-ash: #9e9fb7;
  --color-stone-gray: #6d6e87;
  --color-dark-charcoal: #484960;
  --color-midnight-ink: #181822;
  --color-deep-plum: #260048;
  --color-vanta-purple: #5e05c4;
  --color-royal-violet: #8f47d5;
  --color-misty-lavender: #ddd6ff;
  --color-sky-lavender: #cdd2f8;
  --color-warning-gold: #ffbe0f;

  /* Typography — Font Families */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless: 'Reckless', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --tracking-caption: -0.2px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.4px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.35;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.64px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.714px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -0.784px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-inputs: 999px;
  --radius-buttons: 999px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-background-snow: #f7f8fa;
  --surface-canvas-white: #ffffff;
  --surface-sky-lavender: #cdd2f8;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-background-snow: #f7f8fa;
  --color-cloud-gray: #eaeaf1;
  --color-border-fog: #dfdfe9;
  --color-muted-ash: #9e9fb7;
  --color-stone-gray: #6d6e87;
  --color-dark-charcoal: #484960;
  --color-midnight-ink: #181822;
  --color-deep-plum: #260048;
  --color-vanta-purple: #5e05c4;
  --color-royal-violet: #8f47d5;
  --color-misty-lavender: #ddd6ff;
  --color-sky-lavender: #cdd2f8;
  --color-warning-gold: #ffbe0f;

  /* Typography */
  --font-inter-variable: 'Inter Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless: 'Reckless', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.6;
  --tracking-caption: -0.2px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.43;
  --tracking-subheading: -0.4px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.35;
  --tracking-heading-sm: -0.48px;
  --text-heading: 32px;
  --leading-heading: 1.3;
  --tracking-heading: -0.64px;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.714px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -0.784px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 999px;
}
```
