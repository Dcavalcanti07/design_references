# Leandra-isler — Style Reference
> Warm earth, solid type

**Theme:** light

Leandra-isler presents a grounding, natural aesthetic built on warm earth tones and a robust, sans-serif typography. The system emphasizes clear hierarchy through bold headings and generous spacing, while relying on a limited yet expressive color palette. Surfaces subtly hint at natural textures with creamy off-whites and muted ochres, creating a calm and inviting atmosphere. Typography communicates authority without harshness, and interactive elements blend into the overall organic feel rather than standing out with sharp contrasts.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Amber Canvas | `#f4e6cd` | `--color-amber-canvas` | Primary page background, base surface for content sections |
| Pale Ochre | `#edddc3` | `--color-pale-ochre` | Card backgrounds, secondary container surfaces, subtly lifting content from the canvas |
| Forest Shadow | `#1e211e` | `--color-forest-shadow` | Primary text, headings, borders, and main button states – provides strong contrast against warm neutrals |
| Deep Earth | `#888151` | `--color-deep-earth` | Accent backgrounds for attention-grabbing sections or decorative elements |
| Sunken Gold | `#a29a65` | `--color-sunken-gold` | Hover state for accent backgrounds, offering a slightly brighter, more engaged tone |
| Midnight Truffle | `#000000` | `--color-midnight-truffle` | Secondary text, icons, and strong graphical elements where absolute black is required |
| Gradient Earth | `linear-gradient(184deg, rgb(143, 119, 75), rgb(186, 157, 106) 51%, rgb(214, 189, 151) 65%, rgb(244, 230, 205))` | `--color-gradient-earth` | Hero section background, creating a deep, natural gradient that transitions from rich brown to creamy beige, evoking depth and organic texture |

## Tokens — Typography

### PP Neue Montreal — Primary typeface for all text content. Its clean, geometric sans-serif shapes contrast with the organic colors, establishing a modern yet grounded feel. Heavier weights (500) are reserved for impactful headlines, while 400 is standard for body and UI elements. Tight letter-spacing on larger sizes (-0.045em at 173px, -0.030em at 122px) creates a refined, impactful display without feeling overly airy. · `--font-pp-neue-montreal`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 26px, 40px, 43px, 50px, 58px, 75px, 122px, 158px, 173px
- **Line height:** 0.90, 1.00, 1.20, 1.40, 1.50
- **Letter spacing:** -0.045em or -0.030em depending on size
- **Role:** Primary typeface for all text content. Its clean, geometric sans-serif shapes contrast with the organic colors, establishing a modern yet grounded feel. Heavier weights (500) are reserved for impactful headlines, while 400 is standard for body and UI elements. Tight letter-spacing on larger sizes (-0.045em at 173px, -0.030em at 122px) creates a refined, impactful display without feeling overly airy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.4 | — | `--text-caption` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 24px | 1.2 | — | `--text-subheading` |
| heading | 40px | 1.2 | — | `--text-heading` |
| heading-lg | 75px | 1 | -0.045px | `--text-heading-lg` |
| display | 173px | 0.9 | -0.045px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 17 | 17px | `--spacing-17` |
| 20 | 20px | `--spacing-20` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 50px |
| default | 4px |

### Layout

- **Section gap:** 32px
- **Card padding:** 20px
- **Element gap:** 4px

## Components

### Navigation Link
**Role:** Primary navigation element

Text links for navigation, using PP Neue Montreal, weight 400, color Forest Shadow. No distinct background or border, relying on text contrast against Amber Canvas. Padding 2px vertical, 13px horizontal. On hover, the text color changes to a muted variant of Forest Shadow (not detected, use a shade between Forest Shadow and Amber).

### Ghost Button
**Role:** Secondary action button

Transparent background, Forest Shadow text, and Forest Shadow border. No explicit border radius (0px identified as default). Padding is minimal or zero, making it purely a text link with an implied interactive area. Uses PP Neue Montreal, weight 400.

### Pill Button
**Role:** Call to action variant

Used rarely for prominent actions, featuring a 50px border radius for a distinct 'pill' shape. Text is PP Neue Montreal, weight 400, with Forest Shadow color. Background can vary but a common pattern is Pale Ochre with Forest Shadow text.

### Content Card
**Role:** Information grouping

Uses Pale Ochre as its background, with 4px border radius. Padding is around 20px, creating good internal breathing room for text and other elements. Text is Forest Shadow, using PP Neue Montreal at various sizes.

### Accent Section
**Role:** Highlighted content block

Background is Deep Earth, with text in Forest Shadow or a lighter neutral for contrast. Used to visually break up content or draw attention to key information.

## Do's and Don'ts

### Do
- Use Amber Canvas (#f4e6cd) for all primary page backgrounds and spacious content areas.
- Employ Forest Shadow (#1e211e) for all body text, headings, and primary borders to ensure consistent contrast.
- Apply PP Neue Montreal weight 500 for all main headings (h1-h3) and weight 400 for subheadings and body text.
- Incorporate Pale Ochre (#edddc3) for card and subtle container backgrounds, providing a soft lift from the main canvas.
- Maintain a comfortable density with element gaps typically at 4px and section gaps around 32px.
- Utilize 4px border radius for general elements like cards and images, but apply 50px for distinctive 'pill' shaped buttons or tags.
- For prominent hero sections, use the Gradient Earth linear gradient, defining a natural, deep visual anchor.

### Don't
- Avoid using bright, saturated colors that deviate from the established earthy palette.
- Do not introduce sharp, angular shapes or hard lines; prefer gentle curves and soft borders (4px radius) for most UI elements.
- Refrain from heavy drop shadows or complex elevation; surfaces should appear natural and integrated, not floating.
- Do not overcrowd sections; ensure generous vertical spacing with a section gap of at least 32px.
- Avoid using a single black/white monochrome palette; leverage the subtle warmth of Amber Canvas and Pale Ochre.
- Do not use generic system fonts; PP Neue Montreal is a core part of the brand's identity.
- Do not make interactive elements stand out with high contrast backgrounds; interactive text or soft borders are preferred.

## Imagery

The imagery predominantly features highly detailed, natural elements, specifically plants. These are tightly cropped, studio-quality product shots emphasizing organic textures and deep greens against the warm, desaturated background of the canvas. The imagery functions decoratively, adding a natural and calming atmosphere without being full-bleed or overlapping. There are no illustrations, abstract graphics, or product screenshots. Icons appear to be simple, monoline outlines in Forest Shadow, complementing the clean typography.

## Layout

The page primarily uses a contained layout within a maximum width that is not explicitly defined but suggests a comfortable reading experience. The hero section is full-width with a prominent gradient background, featuring a very large, centered headline. Content sections below likely employ consistent vertical spacing (sectionGap 32px) for rhythm. The overall arrangement suggests centered stacks or potentially simple two-column layouts, prioritizing readability and visual balance over complex grids. Navigation is a minimalist top bar with ghost links, centered or right-aligned.

## Agent Prompt Guide

Quick Color Reference: 
text: #1e211e
background: #f4e6cd
border: #1e211e
accent: #888151
primary action: no distinct CTA color

Example Component Prompts:
Create a navigation bar: Amber Canvas background, with ghost links using PP Neue Montreal, weight 400, font size 16px, color Forest Shadow, 2px vertical padding and 13px horizontal padding. Include a subtly outlined button as the primary interaction: no background, 1px border #1e211e, color #1e211e, 50px border-radius, PP Neue Montreal weight 400, text 'Book Appointment'.
Create a hero section: Gradient Earth background. Centered headline 'Praxis für Atlaslogie und Naturheilkunde' using PP Neue Montreal, weight 500, font size 173px, line height 0.9, letter-spacing -0.045em, color Forest Shadow. Place a detailed plant image centrally to break the text.
Create a content card: Pale Ochre background, 4px border radius, 20px padding. Content text using PP Neue Montreal, weight 400, font size 16px, color Forest Shadow. Include a subheading 'Our Approach' using PP Neue Montreal, weight 500, font size 24px, color Forest Shadow, with 4px margin-bottom.

## Similar Brands

- **Osea Malibu** — Similar earthy, muted color palettes and emphasis on natural elements in imagery.
- **Aesop** — Shared aesthetic of understated elegance, minimalist typography, and natural product focus.
- **Goop** — Combination of clean, serif-like sans-serif typography with naturalistic elements and a health-focused brand.
- **Studio McGee** — Warm neutral background colors paired with strong, dark typography for a grounded, refined look.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-amber-canvas: #f4e6cd;
  --color-pale-ochre: #edddc3;
  --color-forest-shadow: #1e211e;
  --color-deep-earth: #888151;
  --color-sunken-gold: #a29a65;
  --color-midnight-truffle: #000000;
  --color-gradient-earth: #8f774b;
  --gradient-gradient-earth: linear-gradient(184deg, rgb(143, 119, 75), rgb(186, 157, 106) 51%, rgb(214, 189, 151) 65%, rgb(244, 230, 205));

  /* Typography — Font Families */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 75px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.045px;
  --text-display: 173px;
  --leading-display: 0.9;
  --tracking-display: -0.045px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 20px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-pill: 50px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-amber-canvas: #f4e6cd;
  --color-pale-ochre: #edddc3;
  --color-forest-shadow: #1e211e;
  --color-deep-earth: #888151;
  --color-sunken-gold: #a29a65;
  --color-midnight-truffle: #000000;
  --color-gradient-earth: #8f774b;

  /* Typography */
  --font-pp-neue-montreal: 'PP Neue Montreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --text-heading: 40px;
  --leading-heading: 1.2;
  --text-heading-lg: 75px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.045px;
  --text-display: 173px;
  --leading-display: 0.9;
  --tracking-display: -0.045px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-17: 17px;
  --spacing-20: 20px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 50px;
}
```
