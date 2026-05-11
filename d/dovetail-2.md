# Dovetail — Style Reference
> Warm parchment, sharp ink — a trusted signature.

**Theme:** light

Dovetail uses a sophisticated, understated aesthetic: a warm off-white canvas sets a clean foundation, punctuated by a soft, muted yellow accent. Typography is central, using a bespoke sans-serif for sharp, confident headlines and body text. Components are minimal, relying on subtle borders and rounded corners rather than heavy shadows or fills, maintaining an open and airy feel. The overall impression is one of approachable authority, balancing professional rigor with a comforting visual warmth.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment | `#fef9f3` | `--color-parchment` | Primary page background, text on dark surfaces, crucial brand text elements, footer text |
| Charcoal Ink | `#1d1e21` | `--color-charcoal-ink` | Primary text color, background for primary action buttons, borders for ghost buttons, dark surface accents |
| Haze Gray | `#e5e7eb` | `--color-haze-gray` | Subtle borders, dividers, muted backgrounds for secondary content blocks |
| Midnight | `#000000` | `--color-midnight` | Decorative SVG fills, high-contrast icon details |
| Sunkissed Ochre | `#f9e5b1` | `--color-sunkissed-ochre` | Muted background for specific sections or cards, brand accent color |

## Tokens — Typography

### Lausanne — Primary typeface for all headings, body text, navigation, and interactive elements. Its custom nature and precise tracking at different sizes define the brand's sharp, modern voice. · `--font-lausanne`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 20px, 22px, 28px, 32px, 48px, 72px
- **Line height:** 1.00, 1.17, 1.36, 1.40, 1.50
- **Letter spacing:** -0.01em at 72px, -0.005em at 48px, 0.005em at 32px, 0.007em at 28px, 0.010em at 20px
- **Role:** Primary typeface for all headings, body text, navigation, and interactive elements. Its custom nature and precise tracking at different sizes define the brand's sharp, modern voice.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 20px | 1.5 | 0.2px | `--text-body-sm` |
| body | 22px | 1.5 | 0.154px | `--text-body` |
| subheading | 28px | 1.4 | 0.196px | `--text-subheading` |
| heading-sm | 32px | 1.36 | 0.16px | `--text-heading-sm` |
| heading | 48px | 1.17 | -0.24px | `--text-heading` |
| display | 72px | 1 | -0.72px | `--text-display` |

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
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 16px |
| lists | 91px |
| images | 16px |
| buttons | 24px |
| navItems | 16px |

### Layout

- **Section gap:** 32px
- **Element gap:** 24px

## Components

### Filled Primary Button
**Role:** Call to action button

Background: Charcoal Ink (#1d1e21), Text: Parchment (#fef9f3). Border radius: 24px. Padding: 14px vertical, 16px horizontal. Font: Lausanne, 400 weight.

### Ghost Navigation Button
**Role:** Secondary call to action or navigation item

Transparent background, Text: Charcoal Ink (#1d1e21). Border radius: 9999px (pill-shaped). Padding: 0px. Font: Lausanne, 400 weight.

### Primary Card
**Role:** Group related content, feature sections

Background: Sunkissed Ochre (#f9e5b1). Border radius: 16px. No shadow. Padding: 28px vertical, 32px horizontal. Used to highlight section details.

### Navigation Link
**Role:** Site navigation item

Text: Charcoal Ink (#1d1e21). Padding: 9px vertical, 12px horizontal. Font: Lausanne, 400 weight. No explicit background or border, relies on text for presence.

### Image Card
**Role:** Display images within content

Border radius: 16px. Background is inherited from the parent container. Minimal styling around images to keep focus on content.

### Accent Tag
**Role:** Highlight key terms within text or lists

Background: Sunkissed Ochre (#f9e5b1). Border radius: 91px (pill-shaped). Padding: 15px vertical, 20px horizontal. Text: Charcoal Ink (#1d1e21). Font: Lausanne, 400 weight.

## Do's and Don'ts

### Do
- Use Parchment (#fef9f3) as the default page background to establish a warm, clean canvas.
- Apply Lausanne typeface for all text elements, maintaining its specified weights and letter-spacing for brand consistency.
- Utilize Charcoal Ink (#1d1e21) for primary text and interactive button backgrounds to ensure strong contrast and visual hierarchy.
- Employ Haze Gray (#e5e7eb) for subtle borders and dividers, providing visual segmentation without heaviness.
- Round corners with 16px for cards and images, and 24px or 9999px for buttons and tags to maintain a consistent soft, yet structured, feel.
- Structure layout with base unit 8px. Maintain 24px element gaps and 32px section gaps for comfortable density.
- Integrate Sunkissed Ochre (#f9e5b1) as a background accent for feature sections, adding warmth and differentiation.

### Don't
- Avoid heavy shadows; the system relies on subtle borders and background colors for differentiation instead of elevation.
- Do not introduce new chromatic colors outside of Sunkissed Ochre, as the brand identity is built on a restricted, warm neutral palette.
- Refrain from altering the specified font weights or letter spacing for Lausanne; these are critical for the brand's typographic tone.
- Do not use sharp 0px radius corners unless specifically called for by a unique component, as most interactive elements use rounded forms.
- Avoid dense, information-heavy blocks. Opt for comfortable spacing and clear visual hierarchy using designated element and section gaps.
- Do not use generic system fonts; Lausanne is a key brand identifier and should be used consistently across all platforms.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Parchment Canvas | `#fef9f3` | Dominant page background, providing a warm, inviting foundation. |
| 2 | Haze Gray Surface | `#e5e7eb` | Muted background for secondary content areas or subtle dividers for internal separation. |
| 3 | Sunkissed Ochre Card | `#f9e5b1` | Highlighting specific content blocks or cards, adding warmth and visual distinction from the canvas. |

## Imagery

The visual language combines stylized two-tone illustrations with high-quality, candid, somewhat desaturated photography. Illustrations appear organic and playful, using the brand's primary black and white with occasional use of Sunkissed Ochre as an accent. Photography is contained within rounded-corner frames (16px radius), appearing as authentic, non-staged glimpses into teamwork or product interaction. Both types serve as explanatory content and create atmosphere, without being overly dense, allowing text to dominate.

## Layout

The page primarily uses a full-bleed layout, particularly in the hero section, which features a large headline and illustration over a Sunkissed Ochre background. Subsequent sections maintain a comfortable vertical rhythm with consistent 32px section gaps. Content is typically arranged in two-column structures (text left, image/illustration right, or vice versa) or centered stacks for headings and single paragraph blocks. A specific feature uses a grid of 'pill-shaped' tags.

## Agent Prompt Guide

### Quick Color Reference
text: #1d1e21
background: #fef9f3
border: #e5e7eb
accent: #f9e5b1
primary action: #1d1e21 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: Sunkissed Ochre background (#f9e5b1). Headline: 'We invest in tech-enabled companies that last' (Lausanne, 72px, 1.0 line-height, Charcoal Ink #1d1e21, letter-spacing -0.72px). Button: 'Get in touch' (Filled Primary Button with Charcoal Ink #1d1e21 background, Parchment #fef9f3 text, 24px radius, 14px 16px padding).
2. Design a feature section: Parchment background (#fef9f3). Headline: 'Driven by people, enabled by technology' (Lausanne, 48px, 1.17 line-height, Charcoal Ink #1d1e21, letter-spacing -0.24px). Body text: 'Combining capital with hands-on experience...' (Lausanne, 22px, 1.5 line-height, Charcoal Ink #1d1e21). Accent tags: 'Capital', '+ Design', '+ Tech' (Accent Tag with Sunkissed Ochre #f9e5b1 background, 91px radius, 15px 20px padding).
3. Build a navigation bar: Parchment background (#fef9f3). Logo: 'Dovetail' (Lausanne, 32px, 1.4 line-height, Charcoal Ink #1d1e21). Navigation links: 'About us', 'Portfolio' (Lausanne, 20px, 1.5 line-height, Charcoal Ink #1d1e21). Action button: 'Get in touch' (Filled Primary Button with Charcoal Ink #1d1e21 background, Parchment #fef9f3 text, 24px radius, 14px 16px padding).

## Similar Brands

- **Alinea Invest** — Warm, minimal, illustration-heavy aesthetic with a strong focus on bespoke typography and limited accent colors against light backgrounds.
- **Braid** — Sophisticated use of a custom sans-serif typeface, subtle background color changes between sections, and clean card-based layouts.
- **Linear** — Reliance on a restricted neutral palette, impactful typography for headings, and minimal component styling (ghost buttons, subtle borders).
- **Monzo** — Clean layouts with ample whitespace, a single brand accent color, and friendly but precise sans-serif typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment: #fef9f3;
  --color-charcoal-ink: #1d1e21;
  --color-haze-gray: #e5e7eb;
  --color-midnight: #000000;
  --color-sunkissed-ochre: #f9e5b1;

  /* Typography — Font Families */
  --font-lausanne: 'Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 20px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.2px;
  --text-body: 22px;
  --leading-body: 1.5;
  --tracking-body: 0.154px;
  --text-subheading: 28px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.196px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.36;
  --tracking-heading-sm: 0.16px;
  --text-heading: 48px;
  --leading-heading: 1.17;
  --tracking-heading: -0.24px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.72px;

  /* Typography — Weights */
  --font-weight-regular: 400;
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
  --spacing-72: 72px;

  /* Layout */
  --section-gap: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 91px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 16px;
  --radius-lists: 91px;
  --radius-images: 16px;
  --radius-buttons: 24px;
  --radius-navitems: 16px;

  /* Surfaces */
  --surface-parchment-canvas: #fef9f3;
  --surface-haze-gray-surface: #e5e7eb;
  --surface-sunkissed-ochre-card: #f9e5b1;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment: #fef9f3;
  --color-charcoal-ink: #1d1e21;
  --color-haze-gray: #e5e7eb;
  --color-midnight: #000000;
  --color-sunkissed-ochre: #f9e5b1;

  /* Typography */
  --font-lausanne: 'Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 20px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.2px;
  --text-body: 22px;
  --leading-body: 1.5;
  --tracking-body: 0.154px;
  --text-subheading: 28px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.196px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.36;
  --tracking-heading-sm: 0.16px;
  --text-heading: 48px;
  --leading-heading: 1.17;
  --tracking-heading: -0.24px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.72px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 91px;
  --radius-full-2: 9999px;
}
```
