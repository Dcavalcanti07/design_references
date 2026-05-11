# Relief — Style Reference
> Oceanic clarity on a paper white canvas. Illustrations and confident blues guide the user through a clear, calm financial journey.

**Theme:** light

Relief's visual system evokes a refreshing, confident simplicity, utilizing a primarily cool blue and white palette. Illustrations are front-and-center, creating a friendly and approachable feel rather than an austere financial one. Typography is robust and direct, anchored by strong, rounded buttons that feel tangible and reassuring. The design favors soft elevation and ample whitespace, framing content with a playful organic rather than rigid geometric structure.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sky Canvas | `#f9f7f0` | `--color-sky-canvas` | Page background; a soft, warm off-white that creates a friendly and inviting base |
| Arctic Mist | `#ffffff` | `--color-arctic-mist` | Card backgrounds, elevated container surfaces, primary text for some inverted sections |
| Deep Ocean | `#13426f` | `--color-deep-ocean` | Primary heading text, dark section backgrounds, link borders and some dark card surfaces |
| Hope Blue | `#2e96ff` | `--color-hope-blue` | Primary call-to-action button fills, key interactive elements, subtle accent in some headings |
| Subtle Gray | `#616c8a` | `--color-subtle-gray` | Body text, secondary information, and soft borders |
| Slate Text | `#333333` | `--color-slate-text` | General body text, default text color for cards and other content blocks |
| Input Charcoal | `#202634` | `--color-input-charcoal` | Input field text, typically darker for clear readability |
| Powder Blue | `#bde1f9` | `--color-powder-blue` | Informational badges and subtle background accents, creating a soft blue highlight |
| Cerulean Link | `#0254a5` | `--color-cerulean-link` | Interactive link text and their hover states, subtly darker than Hope Blue for contrast |
| Shadow Tint | `#cde7fb` | `--color-shadow-tint` | The base color for button shadows, ensuring they appear as soft blue rather than harsh gray |
| Sky Fill | `#73b9ff` | `--color-sky-fill` | Decorative illustration fills, adding lighter blue elements without functional interaction |
| Ocean Fill | `#50a7ff` | `--color-ocean-fill` | Decorative illustration fills, providing a mid-toned blue accent |
| Accent Blue | `#328dd1` | `--color-accent-blue` | Decorative elements, particularly in illustrations and review card timestamps, indicating secondary information or visual interest |
| Dim Gray | `#d0d5dd` | `--color-dim-gray` | Subtle borders and dividers, indicating soft visual separation |

## Tokens — Typography

### Gilroy — Primary brand typeface, used across all headings, body text, and UI components. Its slightly soft, humanist sans-serif quality adds approachability and friendliness. Consistent negative letter-spacing contributes to its compact, confident presentation. · `--font-gilroy`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700, 800
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 32px, 40px, 49px, 53px, 58px
- **Line height:** 0.94, 1.00, 1.10, 1.11, 1.20, 1.29, 1.38, 1.40, 1.43, 1.50, 1.60, 1.63, 1.67, 1.70
- **Letter spacing:** -0.018
- **Role:** Primary brand typeface, used across all headings, body text, and UI components. Its slightly soft, humanist sans-serif quality adds approachability and friendliness. Consistent negative letter-spacing contributes to its compact, confident presentation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.7 | -0.22px | `--text-caption` |
| body-sm | 14px | 1.63 | -0.25px | `--text-body-sm` |
| body | 16px | 1.6 | -0.29px | `--text-body` |
| subheading | 18px | 1.5 | -0.32px | `--text-subheading` |
| heading-sm | 20px | 1.43 | -0.36px | `--text-heading-sm` |
| heading | 32px | 1.29 | -0.58px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.72px | `--text-heading-lg` |
| display | 58px | 1.11 | -1.04px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 30 | 30px | `--spacing-30` |
| 34 | 34px | `--spacing-34` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 70 | 70px | `--spacing-70` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 18px |
| badges | 100px |
| buttons | 70px |
| hero-elements | 49px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(154, 207, 246, 0.5) 0px 7px 0px 0px` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 3px 0px 0px` | `--shadow-subtle-2` |
| subtle-3 | `rgba(154, 207, 246, 0.5) 0px 5px 0px 0px` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 68px
- **Card padding:** 28px
- **Element gap:** 14px

## Components

### Primary Action Button
**Role:** Call-to-action button

Solid 'Hope Blue' fill with 'Arctic Mist' text and 'Shadow Tint' soft blue shadow, featuring a highly rounded '70px' border-radius. Padding is generous `14px 28px` to give ample tap area and visual weight.

### Compact Action Button
**Role:** Secondary call-to-action button

A variant of the primary action, using 'Hope Blue' fill and 'Arctic Mist' text. Features a '42px' border-radius for slightly less extreme rounding, and `0px 24px` padding, suggesting a more compact or secondary role without the prominent vertical padding.

### Dark Feature Card
**Role:** Informational display card

A card with 'Deep Ocean' background, '18px' border-radius, and generous `28px` padding. Used for features or content blocks that require a distinct, darker background to stand out.

### Review Testimonial Card
**Role:** User testimonial display

Cards for displaying user reviews, set against 'Arctic Mist' with '26px' border-radius. Features a subtle `rgba(0, 0, 0, 0.05) 0px 3px 0px 0px` box shadow, giving a slight lift without being overly heavy. Padding is `34px 30px 24px 30px`.

### Input Field
**Role:** User data entry

Input fields have an 'Arctic Mist' background with 'Input Charcoal' text, with a `32px` left padding. There's no visible border-radius or border color, implying a minimalist aesthetic where the field itself is visually integrated into the background.

### Pill Badge
**Role:** Categorization or status indicator

Uses 'Powder Blue' as a background color with 'Slate Text' for content, and a '100px' border-radius to create a full pill shape. Vertical padding is `10.5px` and horizontal is `21px`, indicating a small, rounded tag.

## Do's and Don'ts

### Do
- Prioritize 'Hope Blue' (#2e96ff) for all primary interactive elements like call-to-action buttons, maintaining a '70px' border-radius for their rounded pill shape.
- Use 'Gilroy' font throughout, applying the detected negative letter-spacing for each specific `typeScale` role to maintain a compact and confident appearance.
- Employ 'Deep Ocean' (#13426f) for primary headings and dark content sections, contrasted with 'Sky Canvas' (#f9f7f0) or 'Arctic Mist' (#ffffff) for backgrounds.
- Apply '18px' border-radius to general information cards and `26px` for testimonial cards, providing a consistent soft-edged aesthetic.
- Maintain a clear visual hierarchy by limiting prominent shadows to interactive elements and specific cards (e.g., `rgba(0, 0, 0, 0.05) 0px 3px 0px 0px` for review cards).
- Use 'Sky Canvas' (#f9f7f0) as the underlying page background, with 'Arctic Mist' (#ffffff) for most interactive card surfaces, ensuring a bright and open feel.

### Don't
- Avoid harsh, dark shadows; instead, use the subtle 'Shadow Tint' (#cde7fb) for button elevation to keep the visual tone light and approachable.
- Do not introduce new saturated accent colors outside of the blues and grays; the color palette is intentionally focused for brand consistency.
- Refrain from using sharp corners; all UI elements from buttons to cards should have a generous border-radius, typically `18px`, `26px`, `70px`, or `100px`.
- Do not deviate from the 'Gilroy' typeface or adjust its letter-spacing outside the defined `typeScale` roles, as its specific tracking is a key brand identifier.
- Avoid dense, information-heavy blocks; ensure generous `28px` card padding and `14px` element gaps to maintain a spacious and airy layout.
- Do not use dark backgrounds for general body text or utility elements; save 'Deep Ocean' for prominent headings or distinct sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Sky Canvas | `#f9f7f0` | Dominant page background, providing a warm, inviting canvas. |
| 1 | Arctic Mist | `#ffffff` | Primary surface for cards, input fields, and elevated components, appearing brighter and slightly lifted. |
| 2 | Deep Ocean | `#13426f` | Background for feature cards and distinct content blocks, creating a section of visual weight and contrast. |
| 3 | Powder Blue | `#bde1f9` | Background for badges and small informational tags, providing a soft chromatic accent on surfaces. |

## Elevation

- **Primary Action Button:** `rgba(154, 207, 246, 0.5) 0px 7px 0px 0px`
- **Secondary Action Button:** `rgba(154, 207, 246, 0.5) 0px 5px 0px 0px`
- **Review Testimonial Card:** `rgba(0, 0, 0, 0.05) 0px 3px 0px 0px`

## Imagery

Imagery primarily utilizes custom conceptual illustrations and product screenshots. Illustrations are dimensional and playful, featuring organic, rounded forms in blues, grays, and occasional pops of warm orange or yellow. They often show symbolic objects (money, boats, anchors, piggy banks) within scenes that evoke financial journey narratives, heavily using the brand's blue palette. Product screenshots are typically presented within mockups of mobile devices. Icons are filled, rounded, and mono-color, complementing the illustration style. Imagery plays a dual role: setting a decorative, approachable atmosphere and serving as explanatory content, often adjacent to text blocks. It is image-heavy, balancing UI with illustrative storytelling.

## Layout

The page primarily uses a max-width contained layout, with content centered. The hero section features a soft 'Sky Canvas' background with a large, centered headline and button, anchored by significant illustrations across the bottom. Sections maintain a consistent vertical rhythm, often alternating between white and blue backgrounds in bands. Content frequently follows a text-left/image-right or image-left/text-right pattern, or stacked centered elements. Feature sections often employ 3-column card grids. There is a strong emphasis on spaciousness, with ample vertical and horizontal padding, creating a comfortable density. Navigation is a simple top bar, with a logo on the left and a 'Primary Action Button' on the far right.

## Agent Prompt Guide

Quick Color Reference:
text: #333333
background: #f9f7f0
border: #d0d5dd
accent: #2e96ff
primary action: #2e96ff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #2e96ff background, #40444e text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a 'Dark Feature Card': 'Deep Ocean' background, 18px radius, 28px padding. Headline 'Link your debt' at 20px Gilroy weight 700, #ffffff, letter-spacing -0.36px. Body text 'Discover savings...' at 16px Gilroy weight 400, #ffffff, letter-spacing -0.29px. Include a central illustration. 
3. Build a 'Review Testimonial Card': 'Arctic Mist' background, 26px radius, rgba(0, 0, 0, 0.05) 0px 3px 0px 0px shadow. Padding 34px 30px 24px 30px. Body text 'I've already seen improvements...' at 16px Gilroy weight 400, #333333, letter-spacing -0.29px. Author name 'JazzyJ367' at 14px Gilroy weight 700, #333333, letter-spacing -0.25px.

## Similar Brands

- **Wealthfront** — Clean, light UI with strong photography and clear, confident calls-to-action, avoiding visual clutter.
- **Chime** — Approachable financial app design using blues and whites, friendly illustrations, and clear path to action.
- **Mint** — Financial management with an emphasis on clarity, soft UI elements, and a user-friendly, non-intimidating aesthetic.
- **SoFi** — Modern fintech feel with a focus on simple, clean layouts and a strong brand color, often using illustrations to convey concepts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sky-canvas: #f9f7f0;
  --color-arctic-mist: #ffffff;
  --color-deep-ocean: #13426f;
  --color-hope-blue: #2e96ff;
  --color-subtle-gray: #616c8a;
  --color-slate-text: #333333;
  --color-input-charcoal: #202634;
  --color-powder-blue: #bde1f9;
  --color-cerulean-link: #0254a5;
  --color-shadow-tint: #cde7fb;
  --color-sky-fill: #73b9ff;
  --color-ocean-fill: #50a7ff;
  --color-accent-blue: #328dd1;
  --color-dim-gray: #d0d5dd;

  /* Typography — Font Families */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.7;
  --tracking-caption: -0.22px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.63;
  --tracking-body-sm: -0.25px;
  --text-body: 16px;
  --leading-body: 1.6;
  --tracking-body: -0.29px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.32px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.36px;
  --text-heading: 32px;
  --leading-heading: 1.29;
  --tracking-heading: -0.58px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.72px;
  --text-display: 58px;
  --leading-display: 1.11;
  --tracking-display: -1.04px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-34: 34px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-70: 70px;

  /* Layout */
  --section-gap: 68px;
  --card-padding: 28px;
  --element-gap: 14px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 49px;
  --radius-full-2: 70px;
  --radius-full-3: 100px;

  /* Named Radii */
  --radius-cards: 18px;
  --radius-badges: 100px;
  --radius-buttons: 70px;
  --radius-hero-elements: 49px;

  /* Shadows */
  --shadow-subtle: rgba(154, 207, 246, 0.5) 0px 7px 0px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 3px 0px 0px;
  --shadow-subtle-3: rgba(154, 207, 246, 0.5) 0px 5px 0px 0px;

  /* Surfaces */
  --surface-sky-canvas: #f9f7f0;
  --surface-arctic-mist: #ffffff;
  --surface-deep-ocean: #13426f;
  --surface-powder-blue: #bde1f9;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sky-canvas: #f9f7f0;
  --color-arctic-mist: #ffffff;
  --color-deep-ocean: #13426f;
  --color-hope-blue: #2e96ff;
  --color-subtle-gray: #616c8a;
  --color-slate-text: #333333;
  --color-input-charcoal: #202634;
  --color-powder-blue: #bde1f9;
  --color-cerulean-link: #0254a5;
  --color-shadow-tint: #cde7fb;
  --color-sky-fill: #73b9ff;
  --color-ocean-fill: #50a7ff;
  --color-accent-blue: #328dd1;
  --color-dim-gray: #d0d5dd;

  /* Typography */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.7;
  --tracking-caption: -0.22px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.63;
  --tracking-body-sm: -0.25px;
  --text-body: 16px;
  --leading-body: 1.6;
  --tracking-body: -0.29px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.32px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.43;
  --tracking-heading-sm: -0.36px;
  --text-heading: 32px;
  --leading-heading: 1.29;
  --tracking-heading: -0.58px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.72px;
  --text-display: 58px;
  --leading-display: 1.11;
  --tracking-display: -1.04px;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-30: 30px;
  --spacing-34: 34px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-70: 70px;

  /* Border Radius */
  --radius-2xl: 18px;
  --radius-3xl: 26px;
  --radius-3xl-2: 30px;
  --radius-3xl-3: 40px;
  --radius-full: 49px;
  --radius-full-2: 70px;
  --radius-full-3: 100px;

  /* Shadows */
  --shadow-subtle: rgba(154, 207, 246, 0.5) 0px 7px 0px 0px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 3px 0px 0px;
  --shadow-subtle-3: rgba(154, 207, 246, 0.5) 0px 5px 0px 0px;
}
```
