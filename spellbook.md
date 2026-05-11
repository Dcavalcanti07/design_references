# Spellbook — Style Reference
> Midnight command center, crisp and precise.

**Theme:** dark

Spellbook projects a sophisticated 'midnight command center' visual language, centered around a deep charcoal background and crisp white typography. Accents of vibrant orange signal primary actions, creating focal points against the monochromatic palette. Surface treatments are minimal, relying on subtle shifts in dark gray and crisp borders rather than heavy shadows or complex gradients. The design emphasizes clear information hierarchy through thoughtful font pairing and precise spacing, suggesting efficiency and precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Charcoal | `#121719` | `--color-midnight-charcoal` | Primary background, dark text, subtle borders, input text |
| Deep Slate | `#222729` | `--color-deep-slate` | Card backgrounds, secondary dark surfaces, link backgrounds |
| Pure White | `#ffffff` | `--color-pure-white` | Primary text, button backgrounds, primary borders, icons |
| Ghost Gray | `#f1f3f4` | `--color-ghost-gray` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Cool Steel | `#909394` | `--color-cool-steel` | Muted body text, secondary link text, hairline borders |
| Input Charcoal | `#2b3133` | `--color-input-charcoal` | Input field backgrounds, text dark gray contrast |
| Sunset Orange | `#f94d1e` | `--color-sunset-orange` | Primary CTA buttons, accent fills, interactive highlights — warmth against the dark UI creates urgency |
| Electric Blue | `#029cff` | `--color-electric-blue` | Link accents, decorative icon fills, active state indicators — brings a digital, tech-forward feel |
| Royal Violet | `#7834b5` | `--color-royal-violet` | Specific card backgrounds, decorative button fills |

## Tokens — Typography

### Soehne — Body text, navigation, buttons, labels. Its subtle tracking creates a sense of refinement, preventing a too-wide appearance common in digital interfaces. · `--font-soehne`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 13px, 14px, 16px, 18px, 20px, 22px, 24px
- **Line height:** 1.00, 1.30, 1.40, 1.44, 1.50, 1.60, 1.63
- **Letter spacing:** -0.0100em
- **Role:** Body text, navigation, buttons, labels. Its subtle tracking creates a sense of refinement, preventing a too-wide appearance common in digital interfaces.

### Arizona Mix — Display and large headings. The tighter letter-spacing at larger sizes gives a stately, compact word appearance, enhancing its premium feel. · `--font-arizona-mix`
- **Substitute:** Georgia, serif
- **Weights:** 500
- **Sizes:** 28px, 51px, 67px, 77px
- **Line height:** 1.00, 1.10, 1.15
- **Letter spacing:** -0.0400em at 77px, -0.0300em at 67px, -0.0200em at 51px
- **Role:** Display and large headings. The tighter letter-spacing at larger sizes gives a stately, compact word appearance, enhancing its premium feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.5 | -0.13px | `--text-caption` |
| body | 16px | 1.44 | -0.16px | `--text-body` |
| subheading | 20px | 1.4 | -0.2px | `--text-subheading` |
| heading-sm | 28px | 1.15 | -0.56px | `--text-heading-sm` |
| heading | 51px | 1.1 | -1.53px | `--text-heading` |
| heading-lg | 67px | 1 | -2.01px | `--text-heading-lg` |
| display | 77px | 1 | -3.08px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 100px |
| buttons | 1600px |
| default | 4px |
| decorative | 320px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.05) -20px 20px 30px -13px, rgba(0, 0, 0, ...` | `--shadow-xl` |

### Layout

- **Page max-width:** 1360px
- **Section gap:** 27px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Filled button

Background: Sunset Orange (#f94d1e). Text: Pure White (#ffffff). Fully rounded corners (1600px). Padding: 16px vertical, 28px horizontal. Uses Soehne font, typically weights 400-500.

### Secondary Ghost Button
**Role:** Outlined button

Background: transparent. Border: 1px Pure White (#ffffff). Text: Pure White (#ffffff). Fully rounded corners (1600px). Padding: 14.4px vertical, 25.2px horizontal. Uses Soehne font.

### Navigation Link Button
**Role:** Subtle button/link

Background: transparent. Border: 1px Pure White (#ffffff). Text: Pure White (#ffffff). Slightly rounded corners (3.2px). Padding: 4.8px vertical, 12.8px horizontal. Uses Soehne font.

### Dark Card
**Role:** Content container

Background: Deep Slate (#222729). Border radius: 4px. No shadow. Content padding: 0px.

### Decorative Card
**Role:** Featured content container

Background: Royal Violet (#7834b5). Border radius: 4px. No shadow. Content padding: 0px.

### Text Input Field
**Role:** User input control

Background: Input Charcoal (#2b3133). Text: Pure White (#ffffff). Border radius: 4px. No visible border. Padding: 8px vertical, 16px horizontal. Uses Soehne font.

### Light Input Field
**Role:** User input control

Background: Ghost Gray (#f1f3f4). Text: Midnight Charcoal (#121719). Border radius: 4px. No visible border. Padding: 8-32px vertical, 16px horizontal. Uses Soehne font.

### Pill Badge
**Role:** Categorization tag

Background: transparent. Text: Pure White (#ffffff). Fully rounded corners (100px). Padding: 0px vertical, 12px horizontal. Uses Soehne font.

## Do's and Don'ts

### Do
- Always use Midnight Charcoal (#121719) as the dominant background color for content sections.
- Apply Arizona Mix font with tight letter-spacing for all headlines to maintain a formal, compact appearance.
- Reserve Sunset Orange (#f94d1e) exclusively for primary call-to-action buttons, ensuring high contrast and immediate recognition.
- Use Pure White (#ffffff) text on Midnight Charcoal (#121719) or Deep Slate (#222729) backgrounds for maximum readability.
- Maintain a default border-radius of 4px for most card-like elements and inputs, transitioning to 1600px for buttons and 100px for badges to create distinct shape hierarchies.
- Employ Soehne with -0.0100em letter-spacing for all body and UI text, ensuring a refined, organized look.
- Utilize Electric Blue (#029cff) sparingly for interactive link accents and decorative elements.

### Don't
- Do not use multiple shadow styles; prefer flat surfaces with subtle shifts in dark neutral colors.
- Avoid using bright colors other than Sunset Orange or Electric Blue; the pallette is monochromatic with minimal saturation.
- Do not deviate from the specified letter-spacing for Arizona Mix headings; its tight tracking is a signature element.
- Do not use generic gray buttons; all interactive elements should either be transparent, white-outlined, or Sunset Orange-filled.
- Avoid large imagery or photography; the visual language focuses on UI elements and understated graphics.
- Do not use complex gradients; surfaces rely on solid colors or simple chromatic accents.
- Avoid excessive padding or large gaps between elements; the density is comfortable but not overly spacious.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Primary Canvas | `#121719` | The foundational background for the entire page. |
| 1 | Card Surface | `#222729` | Background for content cards, feature blocks, and secondary interactive areas. |
| 2 | Input Surface | `#2b3133` | Background for form input fields, providing slight elevation from card surfaces. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.05) -20px 20px 30px -13px, rgba(0, 0, 0, 0.15) 5px 5px 35px 15px`

## Imagery

The site's imagery is minimal and functional. It primarily features product screenshots demonstrating the AI in action, often appearing as contained elements within content blocks. Icons are used, appearing as outlined or filled vectors, typically monochrome (white on dark background). There are few, if any, photographs. Graphics are abstract and decorative, using solid brand colors like Electric Blue as subtle accents or fills in more technical illustrations. The overall density is text-dominant, with imagery serving as clear, explanatory content rather than decorative atmosphere.

## Layout

The page implements a contained layout model, centered within a max-width of 1360px. The hero section is full-bleed dark, featuring a centered headline and subtext, followed by two primary action buttons side-by-side. Sections maintain consistent vertical spacing, often presenting as alternating dark neutral backgrounds. Content is frequently arranged in two-column text-left/image-right patterns or centered stacks for feature descriptions. Logo grids for social proof are prominent. Navigation is a sticky top bar with distinct primary and secondary CTA buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #121719
border: #ffffff
accent: #029cff
primary action: #ffffff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ffffff background, #121719 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: background #222729, 4px border-radius, 0px padding. Title 'Automated Workflow' using Soehne, 24px, weight 600, #ffffff. Description 'Streamline your legal processes with intelligent AI automation.' using Soehne, 16px, weight 400, #909394.
3. Create an input field: background #2b3133, text #ffffff, 4px border-radius, 8px 16px padding. Placeholder text 'e.g. jdoe@email.com' using Soehne, 16px, weight 400, #909394.

## Similar Brands

- **Rippling** — Monochromatic dark UI with sharp typography and a single vibrant accent color for primary actions.
- **Linear** — Command-line aesthetic, low-saturation dark palette, and emphasis on clear, functional typography.
- **Vercel** — Developer-focused dark theme, minimalist card designs, and stark text against dark backgrounds.
- **Gusto** — Clean, understated UI with functional accent colors on a largely achromatic background, focused on conveying reliability.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-charcoal: #121719;
  --color-deep-slate: #222729;
  --color-pure-white: #ffffff;
  --color-ghost-gray: #f1f3f4;
  --color-cool-steel: #909394;
  --color-input-charcoal: #2b3133;
  --color-sunset-orange: #f94d1e;
  --color-electric-blue: #029cff;
  --color-royal-violet: #7834b5;

  /* Typography — Font Families */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arizona-mix: 'Arizona Mix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: -0.13px;
  --text-body: 16px;
  --leading-body: 1.44;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.56px;
  --text-heading: 51px;
  --leading-heading: 1.1;
  --tracking-heading: -1.53px;
  --text-heading-lg: 67px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.01px;
  --text-display: 77px;
  --leading-display: 1;
  --tracking-display: -3.08px;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-112: 112px;

  /* Layout */
  --page-max-width: 1360px;
  --section-gap: 27px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;
  --radius-full-2: 320px;
  --radius-full-3: 1600px;

  /* Named Radii */
  --radius-badges: 100px;
  --radius-buttons: 1600px;
  --radius-default: 4px;
  --radius-decorative: 320px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.05) -20px 20px 30px -13px, rgba(0, 0, 0, 0.15) 5px 5px 35px 15px;

  /* Surfaces */
  --surface-primary-canvas: #121719;
  --surface-card-surface: #222729;
  --surface-input-surface: #2b3133;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-charcoal: #121719;
  --color-deep-slate: #222729;
  --color-pure-white: #ffffff;
  --color-ghost-gray: #f1f3f4;
  --color-cool-steel: #909394;
  --color-input-charcoal: #2b3133;
  --color-sunset-orange: #f94d1e;
  --color-electric-blue: #029cff;
  --color-royal-violet: #7834b5;

  /* Typography */
  --font-soehne: 'Soehne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arizona-mix: 'Arizona Mix', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.5;
  --tracking-caption: -0.13px;
  --text-body: 16px;
  --leading-body: 1.44;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.15;
  --tracking-heading-sm: -0.56px;
  --text-heading: 51px;
  --leading-heading: 1.1;
  --tracking-heading: -1.53px;
  --text-heading-lg: 67px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -2.01px;
  --text-display: 77px;
  --leading-display: 1;
  --tracking-display: -3.08px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 100px;
  --radius-full-2: 320px;
  --radius-full-3: 1600px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.05) -20px 20px 30px -13px, rgba(0, 0, 0, 0.15) 5px 5px 35px 15px;
}
```
