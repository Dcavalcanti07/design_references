# Runway — Style Reference
> Precision-engineered black glass. Every element is deliberately placed like components in a high-performance machine, with a single bright light indicating activity.

**Theme:** light

This system projects an image of serious, understated technological leadership, avoiding visual exuberance. Typography is the primary visual differentiator, using a custom font family with precise letter-spacing to convey meticulous control. Colors are monochromatic with a single, highly saturated accent, creating a sharp brand impression against an otherwise stoic palette. Components are designed for functionality and subtle brand reinforcement, prioritizing clarity and direct interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Storm Gray | `#6b7280` | `--color-storm-gray` | Secondary text, subtle borders, inactive states — provides contrast to primary text without harshness. |
| Runway Midnight | `#2b22fa` | `--color-runway-midnight` | Primary brand accent, interactive elements like buttons and active navigation links — this vivid violet is the only chromatic color, signaling key actions and branding. |
| Cloud Burst | `#e5e7eb` | `--color-cloud-burst` | Light borders, dividers, subtle background fills — defines component boundaries without drawing attention. |
| Graphite | `#404040` | `--color-graphite` | Primary text for dark elements on light backgrounds, general informational text — anchors the content. |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, text on dark buttons — establishes the primary visual canvas. |
| Deep Shadow | `#0c0c0c` | `--color-deep-shadow` | Primary text on light backgrounds, dark buttons, deep background elements — provides strong contrast and visual weight. |
| Silver Mist | `#cccccc` | `--color-silver-mist` | Backgrounds for subtle containers or feature blocks, like the small announcement bar — provides a slightly deeper neutral than Pure White. |
| Obsidian | `#2a2a2a` | `--color-obsidian` | Dark button backgrounds, slightly darker text than Deep Shadow for hierarchical differentiation — adds depth to the dark palette. |
| Ash Gray | `#999999` | `--color-ash-gray` | Placeholder text, minor labels, supplemental information — lower prominence than Storm Gray. |
| Pitch Black | `#000000` | `--color-pitch-black` | Iconography, strong dividers, text requiring highest contrast, like the header background in the navigation — used sparingly for maximum impact. |
| Charcoal | `#1a1a1a` | `--color-charcoal` | Darker button text, certain detailed icons, darker internal elements within components — provides a slightly softer black for varied contrast. |
| Pale Gray | `#eef1f5` | `--color-pale-gray` | Subtle background for UI elements like search inputs or less prominent buttons — provides a very light, almost white background. |

## Tokens — Typography

### abcNormal — The primary typeface for all text content. Its variable weights from 400 to 600, combined with precise negative letter-spacing, create a distinctive sophisticated technical aesthetic, particularly noticeable in headlines where tight kerning conveys a sense of crafted precision. The wide range of sizes ensures scalability from fine print to large display headings. · `--font-abcnormal`
- **Substitute:** Inter, Arial
- **Weights:** 400, 450, 500, 600
- **Sizes:** 11px, 13px, 14px, 16px, 20px, 24px, 36px, 40px, 48px
- **Line height:** 1.00, 1.10, 1.25, 1.30, 1.43, 1.50
- **Letter spacing:** -0.0250em, -0.0200em, -0.0120em, -0.0100em, 0.0250em
- **Role:** The primary typeface for all text content. Its variable weights from 400 to 600, combined with precise negative letter-spacing, create a distinctive sophisticated technical aesthetic, particularly noticeable in headlines where tight kerning conveys a sense of crafted precision. The wide range of sizes ensures scalability from fine print to large display headings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.43 | 0.25px | `--text-caption` |
| heading-sm | 20px | 1.3 | -0.01px | `--text-heading-sm` |
| heading | 24px | 1.25 | -0.012px | `--text-heading` |
| heading-lg | 36px | 1.1 | -0.02px | `--text-heading-lg` |
| display | 48px | 1 | -0.025px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 160 | 160px | `--spacing-160` |
| 176 | 176px | `--spacing-176` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| buttons | 6px |
| default | 4px |

### Layout

- **Section gap:** 48-80px
- **Card padding:** 16-24px
- **Element gap:** 4px

## Components

### Primary Dark Button
**Role:** Call to action buttons

Background: Obsidian (#262626), Text: Pure White (#ffffff), Border: Cloud Burst (#e5e7eb) 1px, Radius: 6px, Padding: 6px vertical, 10px horizontal. This creates a highly visible, actionable button on light backgrounds.

### Ghost Button
**Role:** Secondary actions, tertiary navigation

Background: transparent, Text: Pure White (#ffffff), Border: Cloud Burst (#e5e7eb) 1px, Radius: 4px, Padding: 4px vertical, 8px horizontal. Used for less prominent actions, maintaining visual hierarchy with minimal footprint.

### Light Action Button
**Role:** Informational action, contextual buttons

Background: Pale Gray (#eef1f5), Text: Deep Shadow (#1a1a1a), Border: Cloud Burst (#e5e7eb) 1px, Radius: 6px, Padding: 6px vertical, 10px horizontal. Used for actions within lighter sections, maintaining consistency with neutral palette.

### Brand Secondary Button
**Role:** Prominent but not primary calls to action

Background: Pale Gray (#f7f7f7), Text: Deep Shadow (#0c0c0c), Border: Cloud Burst (#e5e7eb) 1px, Radius: 8px, Padding: 8px vertical, 12px horizontal. A slightly larger, subtly more rounded button for important but not primary actions.

### Global Header
**Role:** Main navigation and branding

Background: Pitch Black (#000000), Text: Pure White (#ffffff) for logo and navigation. Features 'Enterprise Sales' and 'Log in' as Ghost Buttons and 'Try Runway' as Primary Dark Button, creating a dark, authoritative top bar.

### Content Card
**Role:** Showcasing articles, products, or features

Background: Pure White (#ffffff), Border: Cloud Burst (#e5e7eb) 1px, Radius: 8px, Padding: 20px (inferred from various padding tokens around card-like elements). Contains imagery and text, providing structured content blocks.

## Do's and Don'ts

### Do
- Prioritize abcNormal font for all text, leveraging its specific weights and negative letter-spacing for headlines to create a precise, technical feel.
- Use Deep Shadow (#0c0c0c) and Pure White (#ffffff) as primary text/background contrast, ensuring AAA readability.
- Apply Runway Midnight (#2b22fa) exclusively for primary calls to action, active states, and brand signifiers to maintain its high impact.
- Implement Cloud Burst (#e5e7eb) for all neutral borders and dividers to softly delineate content areas.
- Maintain 6px radius for primary buttons and 8px for cards, establishing a subtle rounding language.
- Use a base spacing unit of 4px, ensuring all padding and margins are multiples of this unit for consistent rhythm.
- For headlines, apply letter-spacing -0.020em at large sizes (48px) and -0.012em at medium sizes (24-36px) to maintain the signature tight kerning effect.

### Don't
- Avoid introducing additional saturated colors beyond Runway Midnight (#2b22fa); the system relies on a monochromatic base with a single pop.
- Do not vary border radius widely; stick to 4px for default, 6px for buttons, and 8px for cards to maintain visual consistency.
- Refrain from using strong box shadows; the design uses subtle borders for element separation, not elevation through depth.
- Avoid overly casual or decorative typography; the system is built on the precise, controlled aesthetic of abcNormal.
- Do not use generic button styles; ensure all interactive buttons adhere to the defined Primary Dark, Ghost, Light Action, or Brand Secondary Button specifications.
- Do not overuse Pitch Black (#000000); reserve it for high-impact elements like the header background or critical iconography to prevent overwhelming the page.

## Imagery

The site uses a mix of sophisticated product imagery, often in tight crops, showcasing AI-generated content (e.g., goats, toy cars) or robotic components. These visuals are typically contained within card-like structures with 8px rounded corners. Photography is professional, often high-key with strong focus on the subject. Illustrations are absent. Overall, imagery functions as direct evidence of the technology's capabilities rather than decorative elements, consistent with a deep-tech brand.

## Layout

The page primarily uses a max-width contained layout, approximately 1200px, symmetrically centered. The hero section features a centered headline over a white background. Content sections follow a consistent rhythm of alternating image and text blocks, often with a two-column layout. A three-column grid is visible for showcasing research or product cards. Vertical spacing between sections is generous but consistent, allowing content to breathe. The navigation is a sticky top bar, dark-themed, anchoring the brand and key actions.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #0c0c0c (Deep Shadow)
- Background (Page): #ffffff (Pure White)
- CTA (Primary): #2b22fa (Runway Midnight)
- Border (Neutral): #e5e7eb (Cloud Burst)
- Text (Secondary): #6b7280 (Storm Gray)

### Example Component Prompts
1. **Create a Primary Dark Button**: Background #262626, text #ffffff, border #e5e7eb 1px solid, radius 6px, padding 6px 10px. Label 'Try Runway'.
2. **Generate a Hero Headline Section**: Centered text '#0c0c0c, font abcNormal, weight 600, size 48px, line-height 1.0, letter-spacing -0.025em. Subtext #6b7280, font abcNormal, weight 400, size 16px, line-height 1.5, letter-spacing 0.
3. **Design a Content Card**: Background #ffffff, border #e5e7eb 1px solid, radius 8px, padding 20px. Include an image slot at the top with 8px radius and a headline below the image: #0c0c0c, font abcNormal, weight 500, size 24px, line-height 1.25, letter-spacing -0.012em.
4. **Create a Global Header Navigation**: Background #000000, logo 'runway' in #ffffff, navigation links in #ffffff, font abcNormal, weight 400, size 14px, line-height 1.5, letter-spacing 0. Include a Primary Dark Button as specified above.

## Typography Philosophy

The choice of 'abcNormal' with its precisely controlled letter-spacing (especially negative kerning at larger sizes) is central to the brand's identity. This isn't just about readability; it's about conveying extreme precision and technicality. The use of lighter weights (400, 450) even for significant headlines, combined with tight spacing, creates an impression of 'authority through understatement' rather than shouting with bold, heavy fonts. The design trusts the clarity of its content and the elegance of its typography to communicate sophistication.

## Similar Brands

- **OpenAI** — Similar focus on advanced AI technology, and a clean, function-first aesthetic with a limited color palette and structured content.
- **Anthropic** — Shares a technical, research-oriented presentation, using clear typography and a subdued color scheme to convey seriousness and innovation.
- **Replicate** — Features a similar design approach for a developer-centric AI platform, combining strong typography with minimal color and structured content blocks.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-storm-gray: #6b7280;
  --color-runway-midnight: #2b22fa;
  --color-cloud-burst: #e5e7eb;
  --color-graphite: #404040;
  --color-pure-white: #ffffff;
  --color-deep-shadow: #0c0c0c;
  --color-silver-mist: #cccccc;
  --color-obsidian: #2a2a2a;
  --color-ash-gray: #999999;
  --color-pitch-black: #000000;
  --color-charcoal: #1a1a1a;
  --color-pale-gray: #eef1f5;

  /* Typography — Font Families */
  --font-abcnormal: 'abcNormal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.43;
  --tracking-caption: 0.25px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.01px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.012px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.02px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;
  --spacing-176: 176px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 48-80px;
  --card-padding: 16-24px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-buttons: 6px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-storm-gray: #6b7280;
  --color-runway-midnight: #2b22fa;
  --color-cloud-burst: #e5e7eb;
  --color-graphite: #404040;
  --color-pure-white: #ffffff;
  --color-deep-shadow: #0c0c0c;
  --color-silver-mist: #cccccc;
  --color-obsidian: #2a2a2a;
  --color-ash-gray: #999999;
  --color-pitch-black: #000000;
  --color-charcoal: #1a1a1a;
  --color-pale-gray: #eef1f5;

  /* Typography */
  --font-abcnormal: 'abcNormal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.43;
  --tracking-caption: 0.25px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.01px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.012px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.02px;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.025px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-160: 160px;
  --spacing-176: 176px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```
