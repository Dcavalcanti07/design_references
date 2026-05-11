# Join Parker — Style Reference
> Matte bluescreen material

**Theme:** light

Parker's visual system evokes a smart, modern financial platform with a distinct material quality. Cool grays and crisp whites form a quiet canvas that allows a vibrant blue and a warm orange to highlight key interactive elements and brand accents. Typography is compact and precise, maintaining readability while maximizing information density. Softly rounded cards and buttons provide a friendly tactile feel, contrasting with the directness of the color palette.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Off-Black | `#1b1d20` | `--color-off-black` | Primary text, darkest surface background for sections, base UI elements like navigation |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, ghost button backgrounds, text on dark accents |
| Medium Gray | `#6e6e6e` | `--color-medium-gray` | Secondary text, muted icon fills, dividers in neutral contexts |
| Ash Gray | `#f2f1ec` | `--color-ash-gray` | Subtle background for UI elements, light card surfaces within sections |
| Border Gray | `#e1dfd8` | `--color-border-gray` | Hairline borders for cards and other UI components, subtle visual separation |
| Input Border | `#a3a3a3` | `--color-input-border` | Default border color for input fields |
| Parker Blue | `#5196fe` | `--color-parker-blue` | Interactive elements like links, outlined buttons, decorative accents, and the main brand color |
| Parker Orange | `#f9754e` | `--color-parker-orange` | Primary call-to-action button fills – a warm, inviting accent for crucial actions |
| Alert Blue | `#f4ebff` | `--color-alert-blue` | Background for informational banners or highlights, providing a soft background contrast |

## Tokens — Typography

### Inter — Primary typeface for all UI elements, including body text, navigation, and smaller headings. Its compact nature supports dense information presentation without sacrificing clarity. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 19px, 20px, 32px, 48px, 64px
- **Line height:** 1.05, 1.13, 1.16, 1.42, 1.43, 1.50, 1.55
- **Letter spacing:** -0.1em at 64px, -0.06em at 48px, -0.03em at 32px, -0.023em at 20px, -0.02em at 18px, 0.008em at 14px
- **Role:** Primary typeface for all UI elements, including body text, navigation, and smaller headings. Its compact nature supports dense information presentation without sacrificing clarity.

### Gambetta — Used for prominent display headlines, providing a distinctive, authoritative voice. Its moderate weight and tighter tracking set it apart for key statements. · `--font-gambetta`
- **Substitute:** Georgia
- **Weights:** 500
- **Sizes:** 51px, 64px
- **Line height:** 1.05, 1.16
- **Letter spacing:** -0.08em at 64px, -0.04em at 51px
- **Role:** Used for prominent display headlines, providing a distinctive, authoritative voice. Its moderate weight and tighter tracking set it apart for key statements.

### system-ui — system-ui — detected in extracted data but not described by AI · `--font-system-ui`
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px
- **Line height:** 1.42, 1.5
- **Role:** system-ui — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | 0.008px | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.43 | -0.02px | `--text-body-lg` |
| subheading | 20px | 1.42 | -0.023px | `--text-subheading` |
| heading | 32px | 1.13 | -0.03px | `--text-heading` |
| heading-lg | 48px | 1.16 | -0.06px | `--text-heading-lg` |
| display-sm | 51px | 1.16 | -0.04px | `--text-display-sm` |
| display | 64px | 1.05 | -0.08px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| badges | 12.8px |
| inputs | 12px |
| buttons | 1584px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 2px 10px 0px` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button (Orange)
**Role:** Call to action

Filled button with Parker Orange (#f9754e) background and Pure White (#ffffff) text. Features a full pill shape (1584px border-radius) with 8px vertical and 24px horizontal padding.

### Outlined Action Button (Blue)
**Role:** Secondary action or link

Ghost button with a 1px Parker Blue (#5196fe) border and Parker Blue text. Full pill shape (1584px border-radius) with 8px vertical and 24px horizontal padding.

### Neutral Ghost Button
**Role:** Tertiary action or navigation

Ghost button with Pure White (#ffffff) background and Off-Black (#1b1d20) text, with no visible border. Full pill shape (1584px border-radius) with 8px vertical and 24px horizontal padding.

### Feature Card
**Role:** Content container

Pure White (#ffffff) background, with Border Gray (#e1dfd8) 1px border. Features a 24px border-radius and generous internal padding (48px top/bottom, 32px right, ~58px left).

### Input Field
**Role:** User input

Plain white background, Input Border (#a3a3a3) with a 1px border, and 12px border-radius. Internal padding is 8px vertical and 12px horizontal. Text is Medium Gray (#333333).

### Branded Pill Badge
**Role:** Categorization or status

Off-Black (#1b1d20) background with Off-Black text. Features a 12.8px border-radius for a slightly rounded pill shape with 10px vertical and 20px horizontal padding.

## Do's and Don'ts

### Do
- Always use the Parker Orange (#f9754e) for primary call-to-action button fills to maintain brand recognition and visual hierarchy.
- Apply 24px border-radius to all content cards and major section containers to maintain the friendly, soft aesthetic.
- Utilize Inter for all body text, UI labels, and most headings, adjusting weight to 400 for body and 600/700 for distinct headings.
- Ensure a horizontal padding of 24px and vertical of 8px for all buttons to achieve the consistent pill shape.
- Use Parker Blue (#5196fe) for all interactive links and secondary action outlines, ensuring clear visual distinction from primary actions.
- Maintain maximum content width at 1200px, centered on the page, with consistent 64px vertical section gaps.
- Use Gambetta for high-impact headlines (e.g., above 48px) with its defined tighter letter spacing (e.g., -0.08em at 64px) for a focused, bold statement.

### Don't
- Do not use multiple accent colors for CTA buttons; restrict chromatic fills to Parker Orange and outlines to Parker Blue.
- Avoid sharp corners; all major UI elements like cards and buttons must adhere to the specified border-radii of 24px or 1584px.
- Do not introduce new typefaces; rely solely on Inter and Gambetta to preserve typographic rhythm and brand voice.
- Do not use generic gray backgrounds for prominent cards; use Pure White (#ffffff) or Ash Gray (#f2f1ec).
- Avoid heavy drop shadows; elevation should be subtle, defined by a single rgba(0,0,0,0.1) 0px 2px 10px 0px shadow for cards, or none at all.
- Do not vary line-height arbitrarily; stick to the defined ratios of 1.05 and 1.16 for display text and 1.42-1.55 for body text.
- Do not use less than 8px element gap for components unless explicitly defined in a specific component recipe.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#ffffff` | Dominant background for the overall page, providing a clean, bright foundation. |
| 2 | Accent Surface | `#f2f1ec` | A subtle, slightly off-white background for specific sections or contained UI elements to add visual texture without strong contrast. |
| 3 | Interactive Surface | `#5196fe` | Background for selected interactive elements or larger brand-accented blocks, creating visual prominence. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.1) 0px 2px 10px 0px`

## Agent Prompt Guide

### Quick Color Reference
text: #1b1d20
background: #ffffff
border: #e1dfd8
accent: #5196fe
primary action: #f9754e (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #f9754e background, #1b1d20 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create an outlined secondary button: background transparent, border 1px solid #5196fe, text #5196fe, Inter font weight 500, 1584px radius, 8px vertical and 24px horizontal padding, 'Learn More'.
3. Generate a feature card: background #ffffff, border 1px solid #e1dfd8, 24px radius, 48px top/bottom padding, 32px right padding, 58px left padding. Card title: Inter 32px weight 600, #1b1d20; Body text: Inter 16px weight 400, #6e6e6e.
4. Design an input field: background #ffffff, border 1px solid #a3a3a3, 12px radius, 8px vertical and 12px horizontal padding. Placeholder text: Inter 16px weight 400, #6e6e6e.

## Similar Brands

- **Ramp** — Business finance platforms with clean, card-based layouts and a strong accent color.
- **Brex** — Fintech companies for startups, often featuring product visuals of their credit cards and a modern, approachable UI.
- **Mercury** — Online banking interfaces with a focus on simplicity, clear typography, and subtle use of brand colors for hierarchy.
- **Stripe** — Developer-friendly platforms with compact UI, sans-serif typography, and a balance of informational density with clear spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-off-black: #1b1d20;
  --color-pure-white: #ffffff;
  --color-medium-gray: #6e6e6e;
  --color-ash-gray: #f2f1ec;
  --color-border-gray: #e1dfd8;
  --color-input-border: #a3a3a3;
  --color-parker-blue: #5196fe;
  --color-parker-orange: #f9754e;
  --color-alert-blue: #f4ebff;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gambetta: 'Gambetta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.008px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --tracking-body-lg: -0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.42;
  --tracking-subheading: -0.023px;
  --text-heading: 32px;
  --leading-heading: 1.13;
  --tracking-heading: -0.03px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -0.06px;
  --text-display-sm: 51px;
  --leading-display-sm: 1.16;
  --tracking-display-sm: -0.04px;
  --text-display: 64px;
  --leading-display: 1.05;
  --tracking-display: -0.08px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12.8px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-full: 1584px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-badges: 12.8px;
  --radius-inputs: 12px;
  --radius-buttons: 1584px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 2px 10px 0px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-accent-surface: #f2f1ec;
  --surface-interactive-surface: #5196fe;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-off-black: #1b1d20;
  --color-pure-white: #ffffff;
  --color-medium-gray: #6e6e6e;
  --color-ash-gray: #f2f1ec;
  --color-border-gray: #e1dfd8;
  --color-input-border: #a3a3a3;
  --color-parker-blue: #5196fe;
  --color-parker-orange: #f9754e;
  --color-alert-blue: #f4ebff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gambetta: 'Gambetta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: 0.008px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.43;
  --tracking-body-lg: -0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.42;
  --tracking-subheading: -0.023px;
  --text-heading: 32px;
  --leading-heading: 1.13;
  --tracking-heading: -0.03px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.16;
  --tracking-heading-lg: -0.06px;
  --text-display-sm: 51px;
  --leading-display-sm: 1.16;
  --tracking-display-sm: -0.04px;
  --text-display: 64px;
  --leading-display: 1.05;
  --tracking-display: -0.08px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12.8px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-full: 1584px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 2px 10px 0px;
}
```
