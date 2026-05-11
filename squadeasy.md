# SquadEasy — Style Reference
> Playful block playground

**Theme:** light

SquadEasy's design system evokes a playful, high-contrast digital environment. It uses bold, unadorned typography set against vibrant, geometric color blocks and photo cutouts. The layout is dynamic, featuring angled visual elements and prominent typography to create a sense of directness and energy. Color is employed in large, flat regions and as vivid accents, while component styling is typically crisp with generous radii, prioritizing impact over subtle detail.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Amber Canvas | `#e1c19e` | `--color-amber-canvas` | Primary page background for hero sections and expansive content zones, evoking a warm, inviting atmosphere |
| Deep Violet | `#adabff` | `--color-deep-violet` | Background for certain cards and content sections, adding depth and a distinct visual interruption to the warm canvas |
| Electric Lime | `#e4ff60` | `--color-electric-lime` | Primary action background, indicating interactivity with a high-energy pop, and used for decorative fills |
| Sky Blue | `#7fb6e6` | `--color-sky-blue` | Secondary button backgrounds and decorative elements, providing a cooler accent hue |
| Hot Pink | `#ea5da3` | `--color-hot-pink` | Highlight text, decorative fills, and border accents, drawing immediate attention to key phrases and elements |
| Forest Green | `#6fb853` | `--color-forest-green` | Green accent for outlined action borders, linked labels, and lightweight interactive emphasis. Use as a supporting accent, not as a status color |
| Absolute Black | `#000000` | `--color-absolute-black` | Primary text, borders, and solid button fills, providing strong contrast against all backgrounds |
| Pure White | `#ffffff` | `--color-pure-white` | Secondary text, button text on dark backgrounds, and footer background, acting as a clean counterpoint |
| Soft Gray | `#f6f6f6` | `--color-soft-gray` | Subtle background for UI elements, offering a slight visual break from pure white |

## Tokens — Typography

### Body — General body text, links, and various UI elements. Its range of weights and sizes provides versatility for content hierarchy and interactive states. · `--font-body`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 14px, 16px, 17px, 18px, 19px, 22px
- **Line height:** 1.00, 1.20, 1.21
- **Letter spacing:** -0.0180em, -0.0160em, -0.0150em, -0.0140em, -0.0130em, -0.0110em
- **Role:** General body text, links, and various UI elements. Its range of weights and sizes provides versatility for content hierarchy and interactive states.

### Black — Dominant font for headings and impactful display text. Its inherent boldness, combined with tight line heights and negative letter-spacing, creates a commanding, space-efficient presence. · `--font-black`
- **Substitute:** Oswald
- **Weights:** 400, 700
- **Sizes:** 16px, 50px, 56px, 62px, 80px, 110px, 220px
- **Line height:** 0.87, 1.00, 1.05, 1.20
- **Letter spacing:** -0.0360em, -0.0320em, -0.0250em, -0.0180em, -0.0160em, -0.0050em, -0.0010em
- **Role:** Dominant font for headings and impactful display text. Its inherent boldness, combined with tight line heights and negative letter-spacing, creates a commanding, space-efficient presence.

### Regular — Used for specific button labels and navigation items, offering a slightly more relaxed feel than 'Body' to contrast interactive elements. · `--font-regular`
- **Substitute:** Open Sans
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px, 22px
- **Line height:** 1.20, 1.21
- **Letter spacing:** -0.0180em, -0.0160em, -0.0140em, -0.0110em
- **Role:** Used for specific button labels and navigation items, offering a slightly more relaxed feel than 'Body' to contrast interactive elements.

### Medium — Small text and button labels, maintaining legibility at smaller sizes with slightly tighter tracking. · `--font-medium`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.20
- **Letter spacing:** -0.0210em, -0.0180em, -0.0160em
- **Role:** Small text and button labels, maintaining legibility at smaller sizes with slightly tighter tracking.

### Arial — Fallback or specific utility text, relying on system font accessibility. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback or specific utility text, relying on system font accessibility.

### Sharpie — Specific decorative text, providing a distinctive, hand-drawn aesthetic. · `--font-sharpie`
- **Substitute:** Comic Neue
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** -0.0160em
- **Role:** Specific decorative text, providing a distinctive, hand-drawn aesthetic.

### Epilogue — Used for distinctive button labels, offering a subtle, elegant touch for important actions. · `--font-epilogue`
- **Substitute:** Epilogue
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.20
- **Letter spacing:** -0.0140em
- **Role:** Used for distinctive button labels, offering a subtle, elegant touch for important actions.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | -0.252px | `--text-caption` |
| body-sm | 14px | 1.21 | -0.252px | `--text-body-sm` |
| body | 16px | 1.2 | -0.256px | `--text-body` |
| subheading | 18px | 1.2 | -0.252px | `--text-subheading` |
| heading-sm | 22px | 1.2 | -0.242px | `--text-heading-sm` |
| heading | 50px | 1.05 | -1.6px | `--text-heading` |
| heading-lg | 56px | 1 | -1.4px | `--text-heading-lg` |
| display | 80px | 0.87 | -2.88px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |
| 164 | 164px | `--spacing-164` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 10px |
| cards | 0px |
| buttons | 100px |
| navElements | 14px |

### Layout

- **Section gap:** 100px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Text Link Button
**Role:** Navigation and secondary actions.

Transparent background, 'Absolute Black' text or 'Pure White' on dark backgrounds. No border, 'Regular' or 'Body' font family at 16px, 0px border radius, 16px padding on all sides for clickable area.

### Pill Ghost Button (Black)
**Role:** Outlined secondary actions.

Transparent background, 'Absolute Black' text, 100px border radius, with a 1px 'Absolute Black' border. No horizontal/vertical padding detected, suggesting an icon button or minimal text treatment.

### Pill Ghost Button (White)
**Role:** Outlined secondary actions on dark backgrounds.

Transparent background, 'Pure White' text, 100px border radius, with a 1px 'Pure White' border. No horizontal/vertical padding detected, suggesting an icon button or minimal text treatment.

### Pill Filled Button (Black)
**Role:** Primary action within a neutral context.

'Absolute Black' background, 'Pure White' text, 100px border radius, 16px vertical padding, 14px horizontal padding on right and 16px on left.

### Pill Filled Button (Electric Lime)
**Role:** Prominent calls to action.

'Electric Lime' background, 'Absolute Black' text, 100px border radius, 16px padding. This is the most persuasive button style.

### Info Card (Squared)
**Role:** Content presentation with a distinctive background.

Background 'Deep Violet', 0px border radius, no box shadow, 40px top padding, 24px horizontal padding, 140px bottom padding. Large internal padding for generous content framing.

## Do's and Don'ts

### Do
- Always use 'Absolute Black' (#000000) for primary text on light backgrounds and 'Pure White' (#ffffff) on dark backgrounds.
- Apply a 100px border radius to all interactive buttons for a consistent, soft pill shape.
- Use 'Electric Lime' (#e4ff60) specifically for primary call-to-action button backgrounds.
- Employ 'Deep Violet' (#adabff) for prominent content cards to differentiate them from the main canvas.
- Layer large, angled photographic cutouts to create a dynamic and energetic visual composition.
- Utilize 'Black' font family at large sizes for headlines (50-220px) with tight line heights to ensure a commanding presence.
- Maintain a comfortable density with a base spacing unit of 4px and elemental gaps around 16px.

### Don't
- Do not use generic gray tones for primary interactive elements; always use chromatic colors for emphasis.
- Avoid subtle shadows or gradients on component surfaces; stick to flat, vibrant color blocks or crisp borders.
- Do not use small, delicate fonts for headlines; always leverage the 'Black' font family for impact.
- Never use square corners for buttons; always apply the 100px border radius for a distinct visual identity.
- Do not place images in simple, contained boxes; allow them to break out of their bounds or appear dynamically angled.
- Avoid highly ornate or complex typography; the system favors bold, direct, and efficient typefaces.
- Do not introduce additional background colors outside of the defined 'Amber Canvas', 'Deep Violet', 'Electric Lime', and 'Soft Gray' for major sections.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Amber Canvas | `#e1c19` | Primary page background, providing a warm, foundational tone for expansive sections. |
| 1 | Soft Gray | `#f6f6f6` | Subtle background for specific content areas, offering a slight visual differentiation from pure white. |
| 2 | Pure White | `#ffffff` | Background for specific content blocks, footer, and internal elements requiring a clean, bright surface. |
| 3 | Deep Violet | `#adabff` | Elevated card backgrounds, creating strong visual segments and conveying importance. |

## Imagery

Imagery primarily consists of high-contrast, candid lifestyle photography featuring diverse individuals, often cropped tightly and presented as angled, unmasked cutouts. These images are used decoratively to add a human element and dynamic energy, frequently layered over solid color blocks. Icons are minimal, utilizing bold strokes or fills in black or accent colors. Product screenshots are contained within device mockups, maintaining a clean, focused presentation.

## Layout

The page primarily uses a full-bleed layout for background color blocks and hero sections, with text content often centered or presented in two-column arrangements. The hero features a bold, centered headline overlaying the 'Amber Canvas' background with dynamic, angled photo cutouts. Sections alternate between solid color backgrounds (like 'Amber Canvas' and 'Deep Violet') with strong vertical spacing provided by a section gap of 100px. Content blocks, such as testimonial cards, often use a grid-like structure. Elements within sections generally maintain a max-width for readability, but the backgrounds extend full-width. Navigation is a sticky top bar with a centered logo, text links, and a prominent pill-shaped CTA button.

## Agent Prompt Guide

**Quick Color Reference**
- text: #000000
- background: #e1c19e
- border: #000000
- accent: #ea5da3
- primary action: #000000 (filled action)

**3-5 Example Component Prompts**
- Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a testimonial card: 'Deep Violet' background (#adabff), no border radius, 40px top padding, 24px horizontal padding, 140px bottom padding. Body text 'Body' 16px weight 400 #000000.
- Create a navigation link: No background, 'Absolute Black' text, 'Regular' 16px font, no border, no radius. Hover state: text changes to 'Hot Pink' (#ea5da3).
- Create a ghost button: Transparent background, 'Forest Green' (#6fb853) text, 1px 'Forest Green' (#6fb853) border, 100px radius. No padding specified by system, implying visual icon or minimal text.

## Similar Brands

- **Stripe** — Uses large, impactful typography, clear functional interface elements on neutral backgrounds, and strategic use of a limited, vibrant accent color for interaction and branding.
- **Linear** — Combines a sense of modern playfulness with high-contrast elements, using bold text, geometric shapes, and a distinctive color palette.
- **Figma** — Features a light theme with clear information hierarchy, strong typography, and a strategic application of playful, saturated colors for key UI elements and branding.
- **Notion** — Employs a clean, spacious layout with a focus on powerful typography and functional colored elements that stand out against a generally light, minimalist canvas.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-amber-canvas: #e1c19e;
  --color-deep-violet: #adabff;
  --color-electric-lime: #e4ff60;
  --color-sky-blue: #7fb6e6;
  --color-hot-pink: #ea5da3;
  --color-forest-green: #6fb853;
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-soft-gray: #f6f6f6;

  /* Typography — Font Families */
  --font-body: 'Body', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-black: 'Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-regular: 'Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-medium: 'Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sharpie: 'Sharpie', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-epilogue: 'Epilogue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.252px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.21;
  --tracking-body-sm: -0.252px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.256px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.252px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.242px;
  --text-heading: 50px;
  --leading-heading: 1.05;
  --tracking-heading: -1.6px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.4px;
  --text-display: 80px;
  --leading-display: 0.87;
  --tracking-display: -2.88px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-164: 164px;

  /* Layout */
  --section-gap: 100px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-full: 100px;
  --radius-full-2: 500px;

  /* Named Radii */
  --radius-misc: 10px;
  --radius-cards: 0px;
  --radius-buttons: 100px;
  --radius-navelements: 14px;

  /* Surfaces */
  --surface-amber-canvas: #e1c19;
  --surface-soft-gray: #f6f6f6;
  --surface-pure-white: #ffffff;
  --surface-deep-violet: #adabff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-amber-canvas: #e1c19e;
  --color-deep-violet: #adabff;
  --color-electric-lime: #e4ff60;
  --color-sky-blue: #7fb6e6;
  --color-hot-pink: #ea5da3;
  --color-forest-green: #6fb853;
  --color-absolute-black: #000000;
  --color-pure-white: #ffffff;
  --color-soft-gray: #f6f6f6;

  /* Typography */
  --font-body: 'Body', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-black: 'Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-regular: 'Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-medium: 'Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sharpie: 'Sharpie', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-epilogue: 'Epilogue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --tracking-caption: -0.252px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.21;
  --tracking-body-sm: -0.252px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.256px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.252px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.242px;
  --text-heading: 50px;
  --leading-heading: 1.05;
  --tracking-heading: -1.6px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.4px;
  --text-display: 80px;
  --leading-display: 0.87;
  --tracking-display: -2.88px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-164: 164px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-full: 100px;
  --radius-full-2: 500px;
}
```
