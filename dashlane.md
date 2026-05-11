# Dashlane — Style Reference
> secure data in deep space — a dark, controlled interface with focused light points

**Theme:** dark

Dashlane creates a sense of secure, high-tech control with a predominantly dark, almost black background and crisp white typography. Interactive elements are highlighted by vibrant, distinct aqua and indigo accents that pierce the dark canvas with precision. Surfaces are subtly elevated via color shifts rather than heavy shadows, and components maintain a compact, functional aesthetic with rounded corners, emphasizing speed and efficiency over ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#200f0a` | `--color-midnight-ink` | Page background, primary text color for light accents, subtle card backgrounds for depth |
| Almond Dust | `#e3ccc0` | `--color-almond-dust` | Subtle, soft borders for cards and navigation elements |
| Deep Plum | `#2b2538` | `--color-deep-plum` | Elevated card surfaces and secondary button backgrounds, creating a clear hierarchy without high contrast |
| Burnt Umber | `#4d3f3b` | `--color-burnt-umber` | Background for specific card types, indicating a slightly different contextual surface |
| Aquamarine Glow | `#a2f6f5` | `--color-aquamarine-glow` | Primary action buttons, active navigation states, interactive links, and key accent elements — a vivid highlight against the dark palette |
| Indigo Spark | `#858df9` | `--color-indigo-spark` | Secondary action buttons and selected navigation elements — a vibrant, distinct complement to Aquamarine Glow for interactive focus |
| Cadet Violet | `#6c74df` | `--color-cadet-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Lavender Mist | `#b6bbfb` | `--color-lavender-mist` | Violet outline accent for tags, dividers, and focused UI edges. |
| Light Ash | `#e5e7eb` | `--color-light-ash` | Hairline borders, dividers, and ghost button outlines, providing minimal visual separation |
| Paper White | `#fcfaf9` | `--color-paper-white` | Primary text color against dark backgrounds, iconography, and decorative small interface elements |
| Muted Stone | `#a69f9d` | `--color-muted-stone` | Muted helper text, secondary information, and subtle link colors |
| Silver Whisper | `#bcb7b5` | `--color-silver-whisper` | Iconography and decorative strokes that need to be subtle and blend into the background slightly |
| Deep Forest | `#3a3d39` | `--color-deep-forest` | Very dark, nearly black background for highly subtle elements or specific contextual surfaces |

## Tokens — Typography

### Saans — Used for all primary text content. Weight 300 provides a light, airy feel for larger headlines, balancing the dark interface, while 500 is used for readable body copy and UI elements. Letter spacing is subtly tightened at larger sizes for density. · `--font-saans`
- **Substitute:** Inter
- **Weights:** 300, 500
- **Sizes:** 12px, 14px, 16px, 18px, 28px, 36px, 48px, 56px, 72px, 100px
- **Line height:** 1.10, 1.17, 1.20, 1.50
- **Letter spacing:** -1.4px at 56px and above, -0.96px at 48px, normal at 16px and below
- **Role:** Used for all primary text content. Weight 300 provides a light, airy feel for larger headlines, balancing the dark interface, while 500 is used for readable body copy and UI elements. Letter spacing is subtly tightened at larger sizes for density.

### SaansMono — A monospaced font used sparingly for specific data displays or code-like elements, where precise alignment and character distinction are paramount. Its wider letter spacing gives it a technical, structured feel. · `--font-saansmono`
- **Substitute:** Space Mono
- **Weights:** 300
- **Sizes:** 16px
- **Line height:** 1.10
- **Letter spacing:** 0.0600em
- **Role:** A monospaced font used sparingly for specific data displays or code-like elements, where precise alignment and character distinction are paramount. Its wider letter spacing gives it a technical, structured feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.12px | `--text-caption` |
| body-sm | 14px | 1.5 | 0.14px | `--text-body-sm` |
| body | 16px | 1.5 | 0.16px | `--text-body` |
| subheading | 18px | 1.2 | 0.18px | `--text-subheading` |
| heading-sm | 28px | 1.2 | 0.28px | `--text-heading-sm` |
| heading | 36px | 1.17 | -0.72px | `--text-heading` |
| heading-lg | 48px | 1.17 | -0.96px | `--text-heading-lg` |
| display | 56px | 1.17 | -1.4px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| buttons | 4px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 32px
- **Element gap:** 12px

## Components

### Ghost Navigation Link
**Role:** Navigation and secondary actions

Text in Paper White (#fcfaf9) with a 0px border radius, effectively appearing as plain text links that hover to reveal interactivity. No background fill, relies on the background context for visual definition.

### Primary Filled Button
**Role:** Call to action

Filled with Aquamarine Glow (#a2f6f5) background, featuring Midnight Ink (#200f0a) text. Has a 4px border radius and 8px vertical, 16px horizontal padding. This button stands out as the main interactive element.

### Secondary Filled Button
**Role:** Alternative call to action, less prominent than primary

Filled with Indigo Spark (#858df9) background, featuring Midnight Ink (#200f0a) text. Has a 4px border radius and 8px vertical, 16px horizontal padding. Offers a distinct, yet secondary, interactive option.

### Standard Content Card
**Role:** Group related content, statistics, or testimonials

Uses Deep Plum (#2b2538) as the background with an 8px border radius. Padding is generous at 40px top/right/left and 80px bottom, providing ample breathing room for content. No shadow.

### Highlighted Content Card
**Role:** Feature specific content or testimonials with slight visual distinction

Uses Burnt Umber (#4d3f3b) as the background with an 8px border radius. Padding is generous at 40px top/right/left and 80px bottom, similar to the standard card but with a warmer undertone for subtle differentiation. No shadow.

### Hero Message Bar
**Role:** Temporary announcements or promotions

A full-bleed element with Midnight Ink (#200f0a) background. Features text in Paper White (#fcfaf9) and links with Aquamarine Glow (#a2f6f5).

### Ghost Bordered Button
**Role:** Subtle secondary actions, often paired with primary buttons

Transparent background with a 1px solid Light Ash (#e5e7eb) border. Text is Paper White (#fcfaf9). Features a 4px border radius and 8px vertical, 16px horizontal padding. Maintains visual lightness.

### Pill Tag
**Role:** Categorization or short status labels

A small element with a 9999px border radius, giving it a pill shape. Background color varies by context (e.g., Aquamarine Glow for active states, Deep Plum for neutral). Text is Midnight Ink (#200f0a) or Paper White (#fcfaf9) as appropriate.

## Do's and Don'ts

### Do
- Prioritize Midnight Ink (#200f0a) as the primary background for most sections to maintain a dark, focused aesthetic.
- Use Paper White (#fcfaf9) for all primary body text, headings, and iconography against dark backgrounds to ensure high contrast and legibility.
- Highlight primary actions with Aquamarine Glow (#a2f6f5) for filled button backgrounds, active navigation indicators, and key interactive text.
- Apply 4px border radius to all interactive buttons and inputs for a consistent, subtly softened feel.
- Employ Saans font with 300 weight for large headlines (48px+) and Saans 500 for body text to create a balanced typographic hierarchy.
- Utilize 9999px border radius sparingly for small, descriptive elements like tags or micro-chips to provide a distinct 'pill' shape.
- Maintain a clear visual hierarchy for cards by using Deep Plum (#2b2538) for standard content and Burnt Umber (#4d3f3b) for subtly different or emphasized content.

### Don't
- Avoid using bright or light backgrounds for major content sections; the system is designed around a dark canvas.
- Do not use generic gray borders (e.g., #a69f9d) on interactive elements; use Light Ash (#e5e7eb) for ghost button borders or Almond Dust (#e3ccc0) for subtle dividers.
- Do not use more than two distinct chromatic accent colors in close proximity; maintain focus on Aquamarine Glow and Indigo Spark.
- Avoid heavy drop shadows or highly dimensional components; surfaces gain definition through color shifts and minimal elevation hints.
- Do not deviate from the specified Saans (Inter) and SaansMono (Space Mono) font families; these are central to the brand's identity.
- Do not apply excessive padding to elements within tightly-packed components like navigation bars; maintain a comfortable density with 8px or 12px gaps.
- Do not introduce gradients unless explicitly defined; the visual system relies on solid color blocks and precise accent colors.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Ink Canvas | `#200f0a` | Primary page background, creating a deep, dark base for content. |
| 1 | Deep Plum Card | `#2b2538` | Standard content card background, providing subtle elevation and visual grouping on the dark canvas. |
| 2 | Burnt Umber Card Accent | `#4d3f3b` | Alternative card background for specific content, subtly differentiating it from other surfaces. |

## Imagery

Dashlane uses abstract, technical 3D illustrations that depict data flows or security concepts with a dark, muted palette, often featuring glowing accents in Aquamarine Glow. These graphics are contained within the content area and do not bleed. Product screenshots are typically tight crops on a dark minimal background, focusing on the interface itself. Icons are primarily outlined, single-color (Paper White or Aquamarine Glow) with a fine stroke weight, used for functional navigation and feature illustration. Imagery serves to explain and decorate, maintaining a high-tech, controlled atmosphere.

## Layout

The site employs a max-width 1200px centered layout for most content, with a full-bleed dark header and hero section. The hero prominently features a centered headline over an abstract background graphic, accompanied by primary and secondary action buttons. Content sections follow a consistent vertical rhythm with 40px section gaps, often using alternating content arrangements, such as text on the left with a corresponding visual on the right, or 2-3 column grids for statistics and testimonials. A sticky top navigation bar maintains key links and actions accessible. The overall density is comfortable, with ample breathing room around content blocks.

## Agent Prompt Guide

**Quick Color Reference**
text: #fcfaf9
background: #200f0a
border: #e5e7eb
accent: #a2f6f5
primary action: #a2f6f5 (filled action)

**3-5 Example Component Prompts**
1. Create a Primary Action Button: #a2f6f5 background, #200f0a text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a statistics card: Deep Plum (#2b2538) background, 8px radius, 40px all-around padding except 80px bottom. Headline '70%' in Saans 48px weight 300, Paper White (#fcfaf9). Subtext 'of customers reduced admin time spent managing passwords' in Saans 16px weight 500, Paper White (#fcfaf9).
3. Create a testimonial card: Burnt Umber (#4d3f3b) background, 8px radius, 40px all-around padding except 80px bottom. Quote in Saans 18px weight 500, Paper White (#fcfaf9). Name and title in Saans 14px weight 500, Paper White (#fcfaf9).

## Similar Brands

- **Keeper Security** — Dark UI, focus on security, and similar component styling for buttons and cards.
- **1Password** — Emphasis on credential management, dark interface, and modern, clean typography.
- **Okta** — Identity management and security, with a business-focused dark aesthetic and clear, functional UI elements.
- **Auth0** — Developer-focused design, sophisticated dark mode, and a functional yet visually cohesive component library.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #200f0a;
  --color-almond-dust: #e3ccc0;
  --color-deep-plum: #2b2538;
  --color-burnt-umber: #4d3f3b;
  --color-aquamarine-glow: #a2f6f5;
  --color-indigo-spark: #858df9;
  --color-cadet-violet: #6c74df;
  --color-lavender-mist: #b6bbfb;
  --color-light-ash: #e5e7eb;
  --color-paper-white: #fcfaf9;
  --color-muted-stone: #a69f9d;
  --color-silver-whisper: #bcb7b5;
  --color-deep-forest: #3a3d39;

  /* Typography — Font Families */
  --font-saans: 'Saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saansmono: 'SaansMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.18px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.28px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: -0.72px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -0.96px;
  --text-display: 56px;
  --leading-display: 1.17;
  --tracking-display: -1.4px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 32px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-buttons: 4px;

  /* Surfaces */
  --surface-midnight-ink-canvas: #200f0a;
  --surface-deep-plum-card: #2b2538;
  --surface-burnt-umber-card-accent: #4d3f3b;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #200f0a;
  --color-almond-dust: #e3ccc0;
  --color-deep-plum: #2b2538;
  --color-burnt-umber: #4d3f3b;
  --color-aquamarine-glow: #a2f6f5;
  --color-indigo-spark: #858df9;
  --color-cadet-violet: #6c74df;
  --color-lavender-mist: #b6bbfb;
  --color-light-ash: #e5e7eb;
  --color-paper-white: #fcfaf9;
  --color-muted-stone: #a69f9d;
  --color-silver-whisper: #bcb7b5;
  --color-deep-forest: #3a3d39;

  /* Typography */
  --font-saans: 'Saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saansmono: 'SaansMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.12px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.18px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: 0.28px;
  --text-heading: 36px;
  --leading-heading: 1.17;
  --tracking-heading: -0.72px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.17;
  --tracking-heading-lg: -0.96px;
  --text-display: 56px;
  --leading-display: 1.17;
  --tracking-display: -1.4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-full: 9999px;
}
```
