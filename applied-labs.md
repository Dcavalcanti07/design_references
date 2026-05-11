# Applied Labs — Style Reference
> Crisp AI Canvas

**Theme:** light

Applied Labs employs a modern, calm interface with a predominant use of soft neutrals and a single vivid blue accent. The design emphasizes clear hierarchy and readability through precise typography and ample negative space. Components are lightweight, featuring subtle elevation and rounded corners, creating a sense of approachability and digital sophistication. Color is used sparingly, primarily for functional elements like primary actions, iconography, and to denote active states, keeping most surfaces crisp and inviting.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#ffffff` | `--color-canvas-ice` | Primary page canvas and white card surfaces. Do not promote it to the primary CTA color |
| Cloud Drift | `#f7f7f4` | `--color-cloud-drift` | Subtle secondary background for sections and card surfaces, indicating a slight elevation or separation |
| Ghost Fog | `#f5f5f5` | `--color-ghost-fog` | Tertiary background for cards, often used in less prominent sections or for groupings |
| Subtle Ash | `#e4e4e7` | `--color-subtle-ash` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Graphite | `#09090b` | `--color-graphite` | Primary text color for headlines and body text, icon fills |
| Slate Text | `#26251e` | `--color-slate-text` | Secondary text color, ghost button text, link text primarily for navigation and lighter emphasis |
| Faded Stone | `#737373` | `--color-faded-stone` | Muted body text, helper text, and less prominent descriptive elements |
| Deep Space | `#111111` | `--color-deep-space` | Navigation text, footer text, and specific icon fills that require a darker emphasis than Graphite |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary headings, body text, and icon fills on light surfaces. Do not promote it to the primary CTA color |
| Skybound Blue | `#0051ff` | `--color-skybound-blue` | Violet text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Horizon Blue | `#5c7aa1` | `--color-horizon-blue` | Secondary accent for subtle background fills, often for information sections or conversational UI elements |
| Olive Mist | `#b39987` | `--color-olive-mist` | Background for specific card variants, suggesting a different content category or visual grouping |
| Success Green | `#00cb39` | `--color-success-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Geist — Primary typeface for all UI elements. Weight 300 for headlines provides a subtle, less aggressive presence, while 400 and 500 maintain clarity in body and interactive components. The variable letter-spacing tightens tracking for larger display text and loosens it for smaller text modes for optimal legibility. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 10px, 11px, 12px, 13px, 14px, 15px, 16px, 24px, 36px, 48px
- **Line height:** 1.00, 1.08, 1.17, 1.20, 1.25, 1.35, 1.43, 1.45, 1.50, 1.55
- **Letter spacing:** -0.0200em at 48px, -0.0120em at 36px, 0.0050em at 16px, 0.0070em at 14px, 0.0080em at 12px, 0.0100em at 10px
- **Role:** Primary typeface for all UI elements. Weight 300 for headlines provides a subtle, less aggressive presence, while 400 and 500 maintain clarity in body and interactive components. The variable letter-spacing tightens tracking for larger display text and loosens it for smaller text modes for optimal legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.55 | 0.01px | `--text-caption` |
| body | 14px | 1.43 | 0.007px | `--text-body` |
| heading | 24px | 1.35 | — | `--text-heading` |
| heading-lg | 36px | 1.25 | -0.432px | `--text-heading-lg` |
| display | 48px | 1.2 | -0.96px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 99px |
| cards | 8px |
| small | 4px |
| buttons | 8px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(38, 37, 30, 0.14) 0px 18px 36px 0px` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.03) -65px 67px 56px 0px, rgba(0, 0, 0, 0....` | `--shadow-xl-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 186px
- **Card padding:** 12px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Prominent calls to action.

Background: Midnight Ink (#000000), Text: Canvas Ice (#ffffff), Radius: 99px (pill shape), Padding: 13.5px vertical, 21.75px horizontal. Emphasizes key actions without overshadowing content.

### Ghost Callout Button
**Role:** Secondary action or navigational link within sections.

Background: transparent, Text: Slate Text (#26251e), Radius: 99px (pill shape), Padding: 8px vertical, 12px horizontal. Provides interactive options without high visual weight.

### Outline Accent Button
**Role:** Accent-driven interactive elements, often used for secondary features or filters.

Background: rgba(0, 81, 255, 0.05) (Skybound Blue transparent tint), Text: Skybound Blue (#0051ff), Radius: 8px, Padding: 12px vertical, 24px horizontal. Highlights interactability with a subtle colorful hint.

### Default Card
**Role:** Container for distinct content blocks, features, or details.

Background: Canvas Ice (#ffffff), Radius: 8px, No shadow. Provides a clean, unmarked surface for content.

### Subtle Background Card
**Role:** Alternative content container, often used for related but distinct information.

Background: Ghost Fog (#f5f5f5), Radius: 8px, No shadow. Creates a slight visual separation from the main canvas.

### Input Field
**Role:** User data entry.

Background: transparent, Text: Graphite (#09090b), Border: 1px solid Subtle Ash (#e4e4e7), Radius: 0px. Maintains minimal visual presence, prioritizing content density.

### Branded Logo Card
**Role:** Display partner or client logos.

Background: Cloud Drift (#f7f7f4), Radius: 8px, No shadow, Padding: 0px. A soft, contained surface for external branding elements.

## Do's and Don'ts

### Do
- Use Geist weight 300 for all primary headings (h1-h2) with letter spacing -0.0200em at 48px to maintain a sophisticated, understated feel.
- Apply Skybound Blue (#0051ff) exclusively for interactive text elements, active states, and non-destructive link text.
- Maintain a clear visual hierarchy by utilizing Canvas Ice (#ffffff) as the primary page background and Ghost Fog (#f5f5f5) or Cloud Drift (#f7f7f4) for secondary surface differentiation.
- Employ Subtle Ash (#e4e4e7) for all hairline borders and dividers to softly delineate content areas.
- Ensure all primary call-to-action buttons use the Dark Pillar (#26251e) background with Canvas Ice (#ffffff) text and a 99px pill radius.
- Organize content sections with a vertical gap of 186px to create significant breathing room and clear visual breaks.
- Use 8px border radius consistently for cards and primary interactive elements, with 4px for smaller interactive elements.

### Don't
- Do not introduce new vibrant colors outside of the defined brand and accent palette; maintain a subdued, neutral base.
- Avoid heavy shadows or strong gradients; rely on subtle background color shifts and border delineation for visual separation.
- Do not use letter spacing greater than 0.0100em for any text, as it contradicts the subtle, precise typographic style.
- Do not use sharp, unrounded corners for interactive components or content cards; a radius of 4px or 8px is always preferred.
- Do not overcrowd sections; adhere to the generous sectionGap of 186px to preserve the comfortable density.
- Avoid using bold or heavy weights for body text; stick to Geist 400 for optimal readability and a consistent tone.
- Do not use pure black for large background areas; prefer the softer neutral backgrounds like Canvas Ice or Ghost Fog unless explicitly for a primary button.

## Imagery

The imagery leans heavily on aspirational, lightly filtered photography with a focus on real people interacting with technology. The primary hero image features a subtle desaturated effect, creating a thoughtful, almost contemplative mood. Product screenshots, often depicting conversational AI interfaces, are integrated directly into the photographic elements, showing them in context. Icons are typically outlined or filled in monochrome, maintaining a light stroke weight, serving an explanatory and decorative role. The overall density of imagery is balanced, contributing to atmosphere and demonstration rather than image-heavy content blocks.

## Layout

The page model is a max-width contained layout, centering content within a 1200px constraint against a full-bleed background. The hero section prominently features a centered headline over a large, atmospheric photograph, with primary actions immediately below. Section rhythm is marked by consistent, generous vertical spacing (186px) between content blocks, fostering a spacious feel. Content arrangement often employs alternating text-left and image-right patterns for feature explanations, and a three-column card grid is used for feature sets. Navigation is a standard top-bar sticky header with primary links, log-in, and prominent 'Get Demo' button.

## Agent Prompt Guide

### Quick Color Reference
- text: #09090b
- background: #ffffff
- border: #e4e4e7
- accent: #0051ff
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a feature card: Subtle Background Card (Background: Ghost Fog #f5f5f5, Radius: 8px, no shadow). Heading: Graphite text (#09090b), Geist 24px, weight 500. Body text: Faded Stone text (#737373), Geist 14px, weight 400.
3. Create an input field: transparent background, Graphite text (#09090b), 1px solid Subtle Ash border (#e4e4e7), 0px radius. Placeholder text Faded Stone (#737373).

## Similar Brands

- **Anthropic (Claude AI)** — Shares a similar aesthetic of clean, calm UI with extensive use of muted neutrals and a strong focus on typography, signaling advanced AI technology.
- **Vercel** — Features a similar lightweight component design, precise typography, and a prominent use of white space to convey technical sophistication and performance.
- **Linear** — Exhibits a comparable design philosophy with compact, functional components, a primarily monochromatic color scheme, and an emphasis on clear, readable text interfaces.
- **Brex** — Uses a similar approach to brand colors: a largely neutral palette punctuated by a single vibrant accent color to highlight key actions and branding.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #ffffff;
  --color-cloud-drift: #f7f7f4;
  --color-ghost-fog: #f5f5f5;
  --color-subtle-ash: #e4e4e7;
  --color-graphite: #09090b;
  --color-slate-text: #26251e;
  --color-faded-stone: #737373;
  --color-deep-space: #111111;
  --color-midnight-ink: #000000;
  --color-skybound-blue: #0051ff;
  --color-horizon-blue: #5c7aa1;
  --color-olive-mist: #b39987;
  --color-success-green: #00cb39;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.55;
  --tracking-caption: 0.01px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.007px;
  --text-heading: 24px;
  --leading-heading: 1.35;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.432px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.96px;

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
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 186px;
  --card-padding: 12px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-full: 99px;

  /* Named Radii */
  --radius-pill: 99px;
  --radius-cards: 8px;
  --radius-small: 4px;
  --radius-buttons: 8px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-xl: rgba(38, 37, 30, 0.14) 0px 18px 36px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.03) -65px 67px 56px 0px, rgba(0, 0, 0, 0.05) -29px 30px 41px 0px, rgba(0, 0, 0, 0.05) -7px 7px 23px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #ffffff;
  --color-cloud-drift: #f7f7f4;
  --color-ghost-fog: #f5f5f5;
  --color-subtle-ash: #e4e4e7;
  --color-graphite: #09090b;
  --color-slate-text: #26251e;
  --color-faded-stone: #737373;
  --color-deep-space: #111111;
  --color-midnight-ink: #000000;
  --color-skybound-blue: #0051ff;
  --color-horizon-blue: #5c7aa1;
  --color-olive-mist: #b39987;
  --color-success-green: #00cb39;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.55;
  --tracking-caption: 0.01px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.007px;
  --text-heading: 24px;
  --leading-heading: 1.35;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.432px;
  --text-display: 48px;
  --leading-display: 1.2;
  --tracking-display: -0.96px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
  --radius-full: 99px;

  /* Shadows */
  --shadow-xl: rgba(38, 37, 30, 0.14) 0px 18px 36px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.03) -65px 67px 56px 0px, rgba(0, 0, 0, 0.05) -29px 30px 41px 0px, rgba(0, 0, 0, 0.05) -7px 7px 23px 0px;
}
```
