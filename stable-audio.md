# Stable Audio — Style Reference
> Warm parchment; vibrant neon bursts.

**Theme:** light

Stable Audio presents a playful and accessible aesthetic built on a foundation of warm, muted neutrals that evoke aged paper, punctuated by vibrant, almost neon, pops of color. This system employs gentle, rounded forms for interactive elements set against a backdrop of crisp, geometric content blocks. The primary contrast comes from a dark, near-black text on these soft backgrounds, giving it a friendly yet structured feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text, critical icons, high-contrast elements. |
| Charcoal Accent | `#27262b` | `--color-charcoal-accent` | Secondary text, button borders, subtle UI accents. |
| Clean Canvas | `#ffffff` | `--color-clean-canvas` | Overlay backgrounds, card surfaces, active states. |
| Parchment Base | `#f4f1ec` | `--color-parchment-base` | Body background, large content sections. |
| Subtle Ash | `#e2e2e7` | `--color-subtle-ash` | Component backgrounds, subtle borders, dividers. |
| Pale Earth | `#e5dfc8` | `--color-pale-earth` | Section backgrounds, visually separating content blocks. |
| Muted Sage | `#c9d19c` | `--color-muted-sage` | Distinctive card background, accent color for specific content areas. |
| Desert Sand | `#d4c9b4` | `--color-desert-sand` | Subtle background for specific interactive blocks. |
| Deep Plum | `#c4bae3` | `--color-deep-plum` | Highlight and distinct section background, signaling a content shift. |
| Ocean Mist | `#9fc2c7` | `--color-ocean-mist` | Unique sectional background, providing visual interest. |
| Vivid Chartreuse | `#a0f32f` | `--color-vivid-chartreuse` | Graphical accent within UI, drawing attention to visual elements. |
| Goldenrod Pop | `#e1ca46` | `--color-goldenrod-pop` | UI element highlights, emphasizing key data or states. |
| Sunset Orange | `#f9a916` | `--color-sunset-orange` | Primary call-to-action buttons, crucial interactive elements. |

## Tokens — Typography

### Inter — The sole typeface, Inter, handles all text roles. Its variable weights provide flexibility, but the consistent family choice ensures cohesion. The subtle negative letter-spacing on larger sizes creates a tighter, more deliberate appearance, while standard spacing on smaller text maintains readability. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 30px, 40px
- **Line height:** 1.00, 1.15, 1.33, 1.50, 1.71, 1.78
- **Letter spacing:** -0.0210em, -0.0170em, -0.0150em, -0.0140em, -0.0110em, -0.0060em
- **Role:** The sole typeface, Inter, handles all text roles. Its variable weights provide flexibility, but the consistent family choice ensures cohesion. The subtle negative letter-spacing on larger sizes creates a tighter, more deliberate appearance, while standard spacing on smaller text maintains readability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.71 | — | `--text-caption` |
| body-sm | 14px | 1.71 | -0.011px | `--text-body-sm` |
| body | 16px | 1.5 | -0.006px | `--text-body` |
| subheading | 18px | 1.33 | -0.014px | `--text-subheading` |
| heading-sm | 20px | 1.33 | -0.015px | `--text-heading-sm` |
| heading | 30px | 1.15 | -0.017px | `--text-heading` |
| display | 40px | 1 | -0.021px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| forms | 9999px |
| images | 4px |
| buttons | 9999px |
| default | 4px |

### Layout

- **Page max-width:** 1764px
- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Secondary Ghost Button
**Role:** Less prominent actions

Rounded pill button with transparent background, 'Midnight Ink' (000000) text (Inter 16px/1.50/400). Border 'Charcoal Accent' (27262b) 1px. Padding 4px vertical, 14px horizontal.

### Navigation Button
**Role:** Header navigation actions

Rounded pill button with 'Clean Canvas' (#ffffff) background, 'Midnight Ink' (000000) text (Inter 16px/1.50/400). Border 'Subtle Ash' (#e2e2e7) 1px. No explicit padding, likely uses inherent text spacing.

### Section Title (Main)
**Role:** Hero and major section headings

Text is Inter 40px/1.00/700 with letter-spacing -0.0210em, in 'Midnight Ink' (#000000).

### Body Text
**Role:** Paragraphs and descriptions

Text is Inter 16px/1.50/400, in 'Midnight Ink' (#000000).

### Minor Card
**Role:** Information blocks, e.g., prompt details

Background 'Clean Canvas' (#ffffff), border 1px 'Subtle Ash' (#e2e2e7). Border radius 4px. Internal padding varies (e.g. 16px). Contains body text and icon.

### Highlight Card (Purple)
**Role:** Visually distinct content sections

Background 'Deep Plum' (#c4bae3), border radius 4px. Contains imagery, heading.

### Highlight Card (Yellow)
**Role:** Highlighting unique features or categories

Background 'Goldenrod Pop' (#e1ca46), border radius 4px. Contains imagery, heading.

### Image Placeholder
**Role:** Visual representation for audio/music

Square shaped with a 4px border-radius, background colors vary (e.g., 'Vivid Chartreuse' (#a0f32f), 'Goldenrod Pop' (#e1ca46)), containing a semi-circular visual element.

## Do's and Don'ts

### Do
- Use 'Parchment Base' (#f4f1ec) as the default page background.
- Apply 'Midnight Ink' (#000000) for all primary text elements, including headings and body copy.
- Utilize 'Sunset Orange' (#f9a916) exclusively for primary call-to-action buttons, paired with 'Midnight Ink' text.
- Implement a 9999px border-radius for all interactive buttons and input fields to maintain a soft, approachable feel.
- Maintain a 4px border-radius for static containers like cards and images.
- Employ the Inter typeface for all content, selecting weights 400 for body and 700 for headings, adjusting letter-spacing as per type scale.
- Separate major content sections using a `sectionGap` of 64px.

### Don't
- Do not use dark backgrounds for large content blocks; stick to the light, muted neutral palette.
- Avoid sharp corners on interactive elements; maintain the 9999px radius for buttons and form fields.
- Do not introduce new typefaces; Inter is the sole font allowed.
- Do not add additional drop shadows unless explicitly specified for an overlay; rely on background color changes for hierarchy.
- Avoid complex, multi-color gradients for backgrounds; stick to solid or subtly varying background colors.
- Do not introduce additional vivid accent colors beyond 'Sunset Orange', 'Vivid Chartreuse', and 'Goldenrod Pop' without explicit approval.

## Imagery

The visual language for imagery is characterized by minimalist, geometric abstract shapes acting as placeholders for audio content, frequently rendered in vivid brand colors like 'Vivid Chartreuse' (#a0f32f) or 'Goldenrod Pop' (#e1ca46). These abstract forms (often semi-circles) are contained within square or rectangular frames with a 4px border-radius, giving them a polished, almost 'album art' feel for UI elements. Product screenshots are clean and direct, showing the interface in action without heavy masking or stylized effects. Icons are simple, outlined, and monochromatic, typically in 'Midnight Ink' (#000000), serving a functional rather than decorative role. The overall density is balanced, with imagery serving as clear visual anchors in text-rich sections.

## Layout

The site employs a contained layout with a `pageMaxWidth` of 1764px, centrally aligned. The hero section presents as a split layout: a prominent headline on a 'Parchment Base' background on the left, balanced by an interactive content block on the right. Section rhythm is marked by alternating subtle background colors (e.g., 'Pale Earth', 'Deep Plum', 'Ocean Mist') creating distinct yet flowing content zones. Content arrangement frequently uses a 2-column pattern, with text on one side and a corresponding visual component (like an abstract graphic or product screenshot) on the other. Feature grids are present, likely 3-column. Spacing between sections is generous, lending a comfortable and breathable feel, rather than information-dense blocks. Navigation is a simple top bar with aligned 'Sign up' and 'Log in' buttons, appearing minimal and functional.

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Midnight Ink)
- Background (Page): #f4f1ec (Parchment Base)
- CTA Button: #f9a916 (Sunset Orange)
- Border (Subtle): #e2e2e7 (Subtle Ash)
- Accent (Highlight Card): #c4bae3 (Deep Plum)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Use 'Parchment Base' background (#f4f1ec) for the left panel. Set a headline 'Create music with AI.' using Inter 40px, weight 700, line-height 1, letter-spacing -0.021em, color 'Midnight Ink' (#000000). Below it, add a body text 'Generate up to 3-minute high-quality audio...' using Inter 16px, weight 400, line-height 1.5, color 'Midnight Ink'. Include a 'Try now' button matching the 'Primary Action Button' spec.
2. **Generate a Primary Action Button:** Button text 'Try Now'. Background 'Sunset Orange' (#f9a916). Text color 'Midnight Ink' (#000000). Font Inter 16px, weight 400, line-height 1.5. Border radius 9999px. Padding 6px vertical, 16px horizontal.
3. **Design a Secondary Ghost Button:** Button text 'Learn more'. Transparent background. Text color 'Midnight Ink' (#000000). Font Inter 16px, weight 400, line-height 1.5. Border 'Charcoal Accent' (#27262b) 1px. Border radius 9999px. Padding 4px vertical, 14px horizontal.
4. **Build a Highlight Card (Purple):** Full-width card with background set to 'Deep Plum' (#c4bae3). Inner padding of 24px across all sides. Add a heading (e.g. 'Text-to-audio') using Inter 30px, weight 700, line-height 1.15, letter-spacing -0.017em, color 'Midnight Ink'. Include a square image placeholder with 4px border-radius within this card.
5. **Create a Body Text Block:** Render the paragraph 'Soulful Boom Bap Hip Hop instrumental...' using Inter 16px, weight 400, line-height 1.5, letter-spacing -0.006em, color 'Midnight Ink' (#000000).

## Similar Brands

- **Framer** — Combination of soft, desaturated background colors with strong, saturated accents for interactive elements and clear typography.
- **Linear** — Minimalist UI with a strong focus on clear typography, subtle use of background color changes for hierarchy, and monochromatic icon styling.
- **Canva** — Playful use of color in content and UI elements, with a foundation of light neutrals, and rounded-edge components.
- **Webflow** — Emphasis on well-defined content blocks, clear visual hierarchy through background changes, and a systematic approach to typography and spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-charcoal-accent: #27262b;
  --color-clean-canvas: #ffffff;
  --color-parchment-base: #f4f1ec;
  --color-subtle-ash: #e2e2e7;
  --color-pale-earth: #e5dfc8;
  --color-muted-sage: #c9d19c;
  --color-desert-sand: #d4c9b4;
  --color-deep-plum: #c4bae3;
  --color-ocean-mist: #9fc2c7;
  --color-vivid-chartreuse: #a0f32f;
  --color-goldenrod-pop: #e1ca46;
  --color-sunset-orange: #f9a916;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --tracking-body-sm: -0.011px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.006px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.014px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.015px;
  --text-heading: 30px;
  --leading-heading: 1.15;
  --tracking-heading: -0.017px;
  --text-display: 40px;
  --leading-display: 1;
  --tracking-display: -0.021px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Layout */
  --page-max-width: 1764px;
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-forms: 9999px;
  --radius-images: 4px;
  --radius-buttons: 9999px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-charcoal-accent: #27262b;
  --color-clean-canvas: #ffffff;
  --color-parchment-base: #f4f1ec;
  --color-subtle-ash: #e2e2e7;
  --color-pale-earth: #e5dfc8;
  --color-muted-sage: #c9d19c;
  --color-desert-sand: #d4c9b4;
  --color-deep-plum: #c4bae3;
  --color-ocean-mist: #9fc2c7;
  --color-vivid-chartreuse: #a0f32f;
  --color-goldenrod-pop: #e1ca46;
  --color-sunset-orange: #f9a916;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --tracking-body-sm: -0.011px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.006px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.014px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.015px;
  --text-heading: 30px;
  --leading-heading: 1.15;
  --tracking-heading: -0.017px;
  --text-display: 40px;
  --leading-display: 1;
  --tracking-display: -0.021px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-96: 96px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 9999px;
}
```
