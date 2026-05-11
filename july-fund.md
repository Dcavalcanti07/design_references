# July Fund — Style Reference
> Warm parchment in a dark library

**Theme:** dark

July Fund presents a grounded digital experience, blending rich, dark backgrounds with soft, off-white content surfaces. Typography marries traditional serif headlines with modern sans-serif body text, creating a subtle tension between heritage and forward-thinking. Accent colors are primarily deep, muted tones and vivid greens, used sparingly to highlight key information or status, giving the interface a considered, almost academic feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Background Charcoal | `#221f1e` | `--color-background-charcoal` | Page background, primary dark surface for cards and sections |
| Paper White | `#f0e7e4` | `--color-paper-white` | Light surface for cards, body text in dark mode, and outlined button text |
| Text Dark | `#433e3c` | `--color-text-dark` | Primary text color on light backgrounds, such as card body text and button text |
| Text Light | `#ffffff` | `--color-text-light` | Primary text color on dark backgrounds, secondary card elements |
| Shadow Ink | `#000000` | `--color-shadow-ink` | Accent text and borders, particularly for ghost buttons and subtle card outlines |
| Midtone Gray | `#898989` | `--color-midtone-gray` | Muted text, secondary information, and borders on light cards |
| Deep Plum | `#322b66` | `--color-deep-plum` | Accent color for specific cards, badges, and textual highlights — implies depth and focus |
| Forest Green | `#113619` | `--color-forest-green` | Subtle accent for card elements and text; part of the brand's earthy palette |
| Muted Espresso | `#2e2909` | `--color-muted-espresso` | Background for certain dark cards, contributing to a rich, tonal depth |
| Vivid Green | `#56d270` | `--color-vivid-green` | Success and highlight badge backgrounds, adds a vibrant, healthy accent |
| Lavender Mist | `#c6bffa` | `--color-lavender-mist` | Accent for certain badges and interface elements, paired with Deep Plum |
| Sunbeam Yellow | `#fde440` | `--color-sunbeam-yellow` | Accent color for badges and text within certain themed cards |
| Terra Cotta | `#b9534a` | `--color-terra-cotta` | Error or warning badge background. Used sparingly |
| Deep Night Gradient | `radial-gradient(circle at 54.348% 30.4783%, rgb(19, 20, 21) 0%, rgb(7, 27, 55) 100%)` | `--color-deep-night-gradient` | Background gradient for hero sections or prominent dark elements, creating a subtle dimensional effect |

## Tokens — Typography

### Portrait — Primary headings and display text, providing a distinctive, authoritative voice with its classic serif style. The generous line heights maintain legibility despite the decorative nature. · `--font-portrait`
- **Substitute:** Playfair Display
- **Weights:** 400
- **Sizes:** 18px, 30px, 34px, 35px, 40px
- **Line height:** 1.20, 1.30
- **Role:** Primary headings and display text, providing a distinctive, authoritative voice with its classic serif style. The generous line heights maintain legibility despite the decorative nature.

### Helvetica Neue — Body text, labels, and secondary information, offering a clean and modern contrast to the serif headings. The high letter-spacing at smaller sizes enhances readability in uppercase contexts like badges. · `--font-helvetica-neue`
- **Substitute:** Arial
- **Weights:** 400, 700
- **Sizes:** 8px, 10px, 15px, 16px, 18px
- **Line height:** 1.15, 1.20, 1.30
- **Letter spacing:** 0.2em at 8px and 0.25em at 10px, normal for others
- **Role:** Body text, labels, and secondary information, offering a clean and modern contrast to the serif headings. The high letter-spacing at smaller sizes enhances readability in uppercase contexts like badges.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| heading-sm | 18px | 1.2 | — | `--text-heading-sm` |
| heading | 30px | 1.2 | — | `--text-heading` |
| heading-lg | 34px | 1.3 | — | `--text-heading-lg` |
| display | 40px | 1.3 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 8px |
| buttons | 24px |
| largeCards | 20px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Outline Button (Dark)
**Role:** Secondary action button for general use on light backgrounds.

Ghost button with 24px border-radius. Text: Text Dark (#433e3c), 15px Helvetica Neue, weight 400. Border: 1px solid Text Dark (#433e3c). Padding: 0px vertical, 22px horizontal.

### Outline Button (Light)
**Role:** Secondary action button for general use on dark backgrounds.

Ghost button with 24px border-radius. Text: Paper White (#f0e7e4), 15px Helvetica Neue, weight 400. Border: 1px solid Paper White (#f0e7e4). Padding: 0px vertical, 22px horizontal.

### Minimal Link Button
**Role:** Tertiary action or navigational link with minimal styling.

Text: Paper White (#f0e7e4), 15px Helvetica Neue, weight 400. No background or border. Padding: 0.

### Content Card (Paper White)
**Role:** Standard information card for displaying content sections.

Background: Paper White (#f0e7e4). Border-radius: 12px. Padding: 0px for content, with internal elements using 20px spacing.

### Content Card (Charcoal)
**Role:** Standard information card for displaying content sections on dark backgrounds.

Background: Background Charcoal (#221f1e). Border-radius: 12px. Padding: 0px for content.

### Callout Card (Deep Plum)
**Role:** Themed card for highlighting specific categories or insights.

Background: Deep Plum (#322b66). Border-radius: 12px. Text color and internal content spacing adjusted for contrast.

### News Badge
**Role:** Informational tag for categorizing content, particularly news items.

Background: Vivid Green (#56d270). Text: Shadow Ink (#000000), 10px Helvetica Neue, weight 700, letter-spacing 0.25em. Border-radius: 8px. Padding: 12px vertical, 22px horizontal.

### Category Badge (Lavender Mist)
**Role:** Secondary thematic badge for categorizing content.

Background: Lavender Mist (#c6bffa). Text: Deep Plum (#322b66), 10px Helvetica Neue, weight 700, letter-spacing 0.25em. Border-radius: 8px. Padding: 9px vertical, 16px horizontal.

## Do's and Don'ts

### Do
- Always use Portrait for headlines (18px and above) and Helvetica Neue for body text, ensuring distinction.
- Apply a 12px border-radius to all general cards, reserving 20px for larger feature cards or sections.
- Use Vivid Green (#56d270) only for positive status indicators or 'news' badges, never for primary actions.
- Ensure letter-spacing is applied to Helvetica Neue at smaller sizes: 0.2em for 8px, 0.25em for 10px.
- Prioritize tonal shifts for surface differentiation, utilizing Background Charcoal (#221f1e) and Paper White (#f0e7e4) as primary background surfaces.
- Maintain comfortable visual density using 20px for element gaps and 40px for section gaps.
- Employ ghost buttons with 24px radius, using Text Dark (#433e3c) on light backgrounds and Paper White (#f0e7e4) on dark backgrounds for text and border.

### Don't
- Do not use saturated colors for large background areas or primary text; restrict them to small accents like badges.
- Avoid mixing more than two distinct font families on a single page.
- Do not introduce new border-radius values; adhere strictly to 8px for badges, 24px for buttons, and 12px/20px for cards.
- Never use Vivid Green (#56d270) as a primary action color; it is reserved for semantic success/news indicators.
- Do not use drop shadows for elevation; rely on color contrast and subtle borders for perceived depth.
- Do not vary line-height based on individual preference; use the established 1.2 or 1.3 for Portrait and 1.15-1.3 for Helvetica Neue based on context.
- Avoid decorative gradients outside of the Deep Night Gradient on large, singular hero sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Background Charcoal | `#221f1` | Dominant page background, deepest visible surface level. |
| 1 | Muted Espresso Card | `#2e2909` | Container cards that are slightly lighter than the background, creating a subtle lift. |
| 2 | Deep Plum Card | `#322b66` | Accentuated cards, often for specific thematic content, offering a richer background color. |
| 3 | Paper White Card | `#f0e7e4` | Elevated, light-themed cards that stand out against the dark background, for news or prominent features. |

## Imagery

The imagery on July Fund is sparse and highly curated, focusing on abstract graphics, subtle 3D renders, and occasional product-adjacent photography. When present, images are often contained within cards, sometimes featuring masked or soft-edged compositions. Photography consists of tight crops or distant, atmospheric shots (e.g., Earth from space), lacking lifestyle context and focusing on the essence of the subject. Icons, when visible, are minimal, often outlined, and primarily monochromatic, serving explanatory or decorative atmospheric roles. The overall density is text-dominant, with imagery serving as visual punctuation rather than extensive content.

## Layout

The page uses a contained layout with no explicit max-width, suggesting a responsive design that adapts fluidly. The hero section features a centered headline over a dark, full-bleed gradient background, establishing an immersive tone. Subsequent sections follow an alternating pattern of dark and light surfaces, with content arranged in a dynamic, sometimes asymmetric grid. There's a prominent use of 2-column and 3-column card grids for features and articles, which break from strict linear flow to create visual interest. Vertical spacing is consistent and comfortable, promoting readability without feeling cramped. A minimal sticky top bar provides subtle navigation.

## Agent Prompt Guide

Quick Color Reference:
- text: #ffffff (on dark) / #433e3c (on light)
- background: #221f1e
- border: #433e3c (on light) / #f0e7e4 (on dark)
- accent: #322b66
- primary action: no distinct CTA color

Example Component Prompts:
- Create a headline card: Background Charcoal (#221f1e) with 12px border-radius, 40px Portrait font, weight 400, Text Light (#ffffff), centered. Add a 'News Badge' (Vivid Green background, Shadow Ink text) above the headline padding 15px below.
- Create a 'Read More' ghost button: Text Dark (#433e3c), Helvetica Neue 15px, weight 400. Border: 1px solid Text Dark (#433e3c). Radius: 24px. Padding: 0px vertical, 22px horizontal.
- Create a news article card: Paper White (#f0e7e4) background, 12px border-radius. Headline (18px Portrait, Text Dark #433e3c). Body text (15px Helvetica Neue, Text Dark #433e3c), Muted Gray (#898989) for date/meta info. Include a 'News Badge' (Vivid Green background, Shadow Ink text) at the top, padding 20px below it.

## Similar Brands

- **Founders Fund** — Shares a similar dark-mode aesthetic with a focus on substantial typography and minimal, controlled use of color.
- **Andreessen Horowitz** — Employs a blend of classic and modern typography, often with a muted, professional color palette on dark backgrounds.
- **Kleiner Perkins** — Features a sophisticated dark theme with clear content segmentation and subtle brand accents via deep colors.
- **Sequoia Capital** — Utilizes a clean, high-contrast dark interface, often with a single dominant accent color for highlights and interactions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-background-charcoal: #221f1e;
  --color-paper-white: #f0e7e4;
  --color-text-dark: #433e3c;
  --color-text-light: #ffffff;
  --color-shadow-ink: #000000;
  --color-midtone-gray: #898989;
  --color-deep-plum: #322b66;
  --color-forest-green: #113619;
  --color-muted-espresso: #2e2909;
  --color-vivid-green: #56d270;
  --color-lavender-mist: #c6bffa;
  --color-sunbeam-yellow: #fde440;
  --color-terra-cotta: #b9534a;
  --color-deep-night-gradient: #131415;
  --gradient-deep-night-gradient: radial-gradient(circle at 54.348% 30.4783%, rgb(19, 20, 21) 0%, rgb(7, 27, 55) 100%);

  /* Typography — Font Families */
  --font-portrait: 'Portrait', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.2;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.3;
  --text-display: 40px;
  --leading-display: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 8px;
  --radius-buttons: 24px;
  --radius-largecards: 20px;

  /* Surfaces */
  --surface-background-charcoal: #221f1;
  --surface-muted-espresso-card: #2e2909;
  --surface-deep-plum-card: #322b66;
  --surface-paper-white-card: #f0e7e4;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-background-charcoal: #221f1e;
  --color-paper-white: #f0e7e4;
  --color-text-dark: #433e3c;
  --color-text-light: #ffffff;
  --color-shadow-ink: #000000;
  --color-midtone-gray: #898989;
  --color-deep-plum: #322b66;
  --color-forest-green: #113619;
  --color-muted-espresso: #2e2909;
  --color-vivid-green: #56d270;
  --color-lavender-mist: #c6bffa;
  --color-sunbeam-yellow: #fde440;
  --color-terra-cotta: #b9534a;
  --color-deep-night-gradient: #131415;

  /* Typography */
  --font-portrait: 'Portrait', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-neue: 'Helvetica Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.2;
  --text-heading: 30px;
  --leading-heading: 1.2;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.3;
  --text-display: 40px;
  --leading-display: 1.3;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
}
```
