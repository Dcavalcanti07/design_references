# Anything — Style Reference
> Cloud-swept dreamscape

**Theme:** light

Anything's visual system evokes a serene, imaginative canvas where ideas take form. The interplay of a light, expansive background with soft, almost translucent UI elements creates a sense of effortless creation. Typography, particularly the whimsical script for the brand name, suggests creativity, while structured sans-serifs convey purpose. Components use large border radii and minimal shadow for a friendly, approachable feel, emphasizing content over heavy chrome.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud White | `#ffffff` | `--color-cloud-white` | Page backgrounds, card surfaces, primary text on dark backgrounds, icon fills |
| Sky Mist | `#f9f9f9` | `--color-sky-mist` | Subtle background surfaces, secondary card backgrounds |
| Whisper Gray | `linear-gradient(90deg, rgb(242, 242, 242) 0%, rgb(242, 242, 242) 30%, rgb(109, 192, 120) 35%, rgb(153, 183, 250) 40%, rgb(242, 242, 242) 45%, rgb(242, 242, 242) 100%)` | `--color-whisper-gray` | Subtle card backgrounds, button borders; A subtle gradient for background textures, hinting at color without strong saturation |
| Slate Ink | `#18191b` | `--color-slate-ink` | Primary text, heading text |
| Abyssal Black | `#000000` | `--color-abyssal-black` | Strongest text contrast, button text |
| Soft Stone | `linear-gradient(90deg, rgb(172, 173, 174) 0%, rgb(172, 173, 174) 30%, rgb(109, 192, 120) 35%, rgb(153, 183, 250) 40%, rgb(172, 173, 174) 45%, rgb(172, 173, 174) 100%)` | `--color-soft-stone` | Muted text, placeholder text, icon strokes; Decorative background gradient used for visual interest or textured elements, transitioning through muted cool tones and a soft green |
| Stone Whisper | `#6a6a6c` | `--color-stone-whisper` | Secondary body text, supporting text |
| Slate Border | `#bbbbbb` | `--color-slate-border` | Hairline borders, subtle dividers |
| Cool Gray | `#c4c4c4` | `--color-cool-gray` | Card borders, disabled text |
| Pale Silver | `#dbdbdb` | `--color-pale-silver` | Soft button backgrounds, subtle input borders |
| Verdant Green | `#448f52` | `--color-verdant-green` | Green text accent for links, tags, and emphasized short phrases |
| Modern Tech Gradient | `linear-gradient(90deg, rgb(107, 114, 128) 0%, rgb(107, 114, 128) 30%, rgb(59, 130, 246) 35%, rgb(16, 185, 129) 40%, rgb(107, 114, 128) 45%, rgb(107, 114, 128) 100%)` | `--color-modern-tech-gradient` | A dynamic gradient for modern UI accents, blending cool blue and vibrant green with soft gray |

## Tokens — Typography

### Inter — Primary UI text for body copy, buttons, links, and general information. Its consistent letter-spacing across sizes provides a structured, digital feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 29px
- **Line height:** 1.33, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** 0.02em
- **Role:** Primary UI text for body copy, buttons, links, and general information. Its consistent letter-spacing across sizes provides a structured, digital feel.

### Instrument Serif — Decorative text, likely for the brand name or sub-headings where a more artistic, whimsical touch is desired. · `--font-instrument-serif`
- **Substitute:** serif
- **Weights:** 400, 500
- **Sizes:** 16px, 24px
- **Line height:** 1.00, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** Decorative text, likely for the brand name or sub-headings where a more artistic, whimsical touch is desired.

### Instrument Sans — Headlines and prominent text, offering a clean, modern contrast to the serif font for better readability at larger sizes. · `--font-instrument-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 600
- **Sizes:** 16px, 24px, 42px
- **Line height:** 1.20, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** Headlines and prominent text, offering a clean, modern contrast to the serif font for better readability at larger sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | 0.24px | `--text-caption` |
| body | 14px | 1.43 | 0.28px | `--text-body` |
| heading | 24px | 1.4 | — | `--text-heading` |
| heading-lg | 29px | 1.56 | 0.58px | `--text-heading-lg` |
| display | 42px | 1.2 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| images | 20px |
| inputs | 0px |
| buttons | 9999px |
| elements | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |

### Layout

- **Section gap:** 50px
- **Card padding:** 40px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action

Rounded pill shape with a `9999px` border-radius. Background is `Abyssal Black` (`#000000`), text is `Cloud White` (`#ffffff`), with `10px` vertical and `16px` horizontal padding. Uses Inter font.

### Naked Pill Button
**Role:** Softly styled button, often for secondary actions or tags.

Ghost button with a `9999px` border-radius. Background is `Pale Silver` (`#dbdbdb`), text is `Abyssal Black` (`#000000`), with an implicit `0px` padding (content drives size). Uses Inter, 0 padding from data.

### Ghost Chip Button
**Role:** Subtle, non-prominent button for filtering or alternative actions.

Softly rounded pill shape with a `20px` border-radius. Background is `Sky Mist` (`#f9f9f9`), text is `Soft Stone` (`#acadae`), with implicit `0px` padding. Uses Inter, 0 padding from data.

### Minimal Card
**Role:** Standard content container, light elevation.

Standard card with `12px` border-radius. Background is `Cloud White` (`#ffffff`), with a soft shadow: `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`. Inner padding is `25px` on all sides.

### Flat Card
**Role:** Container for content without elevation.

Flat card with `20px` border-radius. Background is `Sky Mist` (`#f9f9f9`), no shadow. Implicit `0px` padding.

### Subtle Input Field
**Role:** Text input area with minimal styling.

Input field with `0px` border-radius. Transparent background, text is `Abyssal Black` (`#000000`), with a `Slate Border` (`#bbbbbb`) on the top. Inner padding `16px` on all sides.

### Navigation Link
**Role:** Interactive text link within navigation.

Text in `Abyssal Black` (`#000000`) on `Instrument Sans` with `16px` font size. Implicit `4px` top and `12px` horizontal padding.

## Do's and Don'ts

### Do
- Prioritize Cloud White (`#ffffff`) for backgrounds and main surfaces to maintain an airy, open feel.
- Use Slate Ink (`#18191b`) for primary headings and body text to ensure strong readability against light backgrounds.
- Apply a `9999px` border-radius to all primary action buttons for a consistent pill shape signature.
- Utilize the Inter font family with `0.02em` letter-spacing for all general UI text elements at `12px` and `13px` for a structured appearance.
- Employ the Minimal Card shadow for any elevated element requiring visual depth against the page background.
- Implement the Instrument Serif font for decorative headlines and the brand name to introduce a whimsical, creative brand accent.
- Maintain `12px` as a common `elementGap` for horizontal and vertical spacing between small interactive elements and text blocks.

### Don't
- Avoid using highly saturated colors for large background areas; keep the canvas light and spacious.
- Do not introduce square corners on buttons or cards; maintain the `20px` or `9999px` radii for a soft, friendly aesthetic.
- Refrain from heavy, dark shadows; stick to the specified soft shadow `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px...` for subtle elevation.
- Do not deviate from the Inter typeface for crucial informational text; readability and consistency are key for UI elements.
- Do not use contrasting or multiple border styles on inputs; a clear, simple border from `Slate Border` is sufficient.
- Avoid overly dense layouts; leverage `sectionGap` of `50px` and `cardPadding` of `40px` to ensure comfortable breathing room.
- Do not use the decorative gradients (`Sky-to-Meadow Gradient`, `Modern Tech Gradient`, `Faded Sparkle Gradient`) as primary UI backgrounds; reserve them for subtle decorative accents or textural elements.

## Imagery

Imagery predominantly features dreamlike, slightly abstract photography of natural elements like clouds and flowers, often softened by blur. Product UI elements are occasionally depicted within an old CRT monitor, creating a blend of nostalgic technology and natural beauty. Icons are minimal, outlined, or filled with a mid-tone gray. Photography creates a decorative atmosphere, suggesting boundless possibility and a relaxed creative environment rather than direct product showcase.

## Layout

The page adheres to a mostly full-bleed layout for background imagery, creating an immersive atmospheric hero section. Content is centered within this broad canvas. The hero features a large, centered brand name with a descriptive subtitle, followed by a prominent search-like input field. Sections appear to flow continuously without strong visual dividers, but with consistent vertical spacing. Content appears to be presented in centered stacks or possibly two-column arrangements within subsequent sections.

## Agent Prompt Guide

### Quick Color Reference
- text: `#18191b` (Slate Ink)
- background: `#ffffff` (Cloud White)
- border: `#bbbbbb` (Slate Border)
- accent: `#448f52` (Verdant Green)
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Create a `Minimal Card`: `12px` radius, background `Cloud White` (`#ffffff`), shadow `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`, `25px` padding on all sides.
3. Create a `Subtle Input Field`: `0px` radius, transparent background, text `Abyssal Black` (`#000000`), `Slate Border` (`#bbbbbb`) top border, `Inter` font weight `400`, `16px` size, `16px` padding on all sides.

## Similar Brands

- **Midjourney** — Shares a whimsical, almost dreamlike aesthetic with a focus on creativity and generative AI, using soft colors and a broad, open layout.
- **Notion** — Employs a clean, minimalist UI with strong typography, ample white space, and a focus on content over heavy visual chrome, similar to Anything's functional elements.
- **Framer** — Features a light, spacious design with subtle shadows and a modern sans-serif typography, creating a feeling of ease and clarity in design creation.
- **Read.cv** — Uses a very neutral palette accented by a primary color, combined with significant white space and structured typography to convey clarity and simplicity, much like Anything's core UI.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-white: #ffffff;
  --color-sky-mist: #f9f9f9;
  --color-whisper-gray: #f2f2f2;
  --gradient-whisper-gray: linear-gradient(90deg, rgb(242, 242, 242) 0%, rgb(242, 242, 242) 30%, rgb(109, 192, 120) 35%, rgb(153, 183, 250) 40%, rgb(242, 242, 242) 45%, rgb(242, 242, 242) 100%);
  --color-slate-ink: #18191b;
  --color-abyssal-black: #000000;
  --color-soft-stone: #acadae;
  --gradient-soft-stone: linear-gradient(90deg, rgb(172, 173, 174) 0%, rgb(172, 173, 174) 30%, rgb(109, 192, 120) 35%, rgb(153, 183, 250) 40%, rgb(172, 173, 174) 45%, rgb(172, 173, 174) 100%);
  --color-stone-whisper: #6a6a6c;
  --color-slate-border: #bbbbbb;
  --color-cool-gray: #c4c4c4;
  --color-pale-silver: #dbdbdb;
  --color-verdant-green: #448f52;
  --color-modern-tech-gradient: #6b7280;
  --gradient-modern-tech-gradient: linear-gradient(90deg, rgb(107, 114, 128) 0%, rgb(107, 114, 128) 30%, rgb(59, 130, 246) 35%, rgb(16, 185, 129) 40%, rgb(107, 114, 128) 45%, rgb(107, 114, 128) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: 0.24px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.28px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --text-heading-lg: 29px;
  --leading-heading-lg: 1.56;
  --tracking-heading-lg: 0.58px;
  --text-display: 42px;
  --leading-display: 1.2;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 40px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 31px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-images: 20px;
  --radius-inputs: 0px;
  --radius-buttons: 9999px;
  --radius-elements: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-white: #ffffff;
  --color-sky-mist: #f9f9f9;
  --color-whisper-gray: #f2f2f2;
  --color-slate-ink: #18191b;
  --color-abyssal-black: #000000;
  --color-soft-stone: #acadae;
  --color-stone-whisper: #6a6a6c;
  --color-slate-border: #bbbbbb;
  --color-cool-gray: #c4c4c4;
  --color-pale-silver: #dbdbdb;
  --color-verdant-green: #448f52;
  --color-modern-tech-gradient: #6b7280;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-instrument-serif: 'Instrument Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-instrument-sans: 'Instrument Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: 0.24px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.28px;
  --text-heading: 24px;
  --leading-heading: 1.4;
  --text-heading-lg: 29px;
  --leading-heading-lg: 1.56;
  --tracking-heading-lg: 0.58px;
  --text-display: 42px;
  --leading-display: 1.2;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-3xl: 31px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
}
```
