# Lottielab — Style Reference
> White canvas, violet spark

**Theme:** light

Lottielab employs a crisp, bright aesthetic with ample negative space. It combines straightforward typography with a vibrant violet accent for primary actions, creating a focused, inviting user experience. Surfaces are predominantly clean white, complemented by subtle background neutrals to delineate content areas. The overall impression is one of clarity and approachable functionality, emphasizing content and interaction without visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Stormy Indigo | `#2f2b4a` | `--color-stormy-indigo` | Primary text, prominent headings, strong links, and icon fills—a deep, muted violet for essential information |
| Midnight Charcoal | `#1c1a2c` | `--color-midnight-charcoal` | Secondary text, background for certain structural elements, and a darker shade for higher contrast text |
| Electric Violet | `#7270ff` | `--color-electric-violet` | Primary action button backgrounds, button borders, and highlighted text; signifies interactive elements and brand presence |
| Deep Sea Blue | `#1560fb` | `--color-deep-sea-blue` | Decorative icon fills, subtle background accents for links, adding dynamic blue to interactive content |
| Soft Gray | `#4b5563` | `--color-soft-gray` | Muted helper text, secondary information, and less prominent body copy |
| Bright White | `#ffffff` | `--color-bright-white` | Card backgrounds, primary page background, button text, and icon fills |
| Ash Gray | `#e5e7eb` | `--color-ash-gray` | Subtle borders, dividers, and ghost button borders, providing gentle visual separation |
| Light Mist | `#f3f4f6` | `--color-light-mist` | Secondary page background, adding a very light neutral contrast to primary white surfaces |
| Stone Gray | `#9ca3af` | `--color-stone-gray` | Icon colors, secondary text, and subtle link colors, providing visual lightness |
| Pale Silver | `#d9dbda` | `--color-pale-silver` | Subtle background accents, borders, and light icon fills |
| Snow Drift | `#f9fafb` | `--color-snow-drift` | Tertiary background color for subtle elevation or differentiation, lighter than Light Mist |
| Sunny Gradient | `linear-gradient(to right, rgb(250, 204, 21), rgb(249, 115, 22))` | `--color-sunny-gradient` | Decorative gradient for accent elements or callouts, evoking warmth and energy |
| Sunset Gradient | `linear-gradient(to right, rgb(236, 72, 153), rgb(248, 113, 113))` | `--color-sunset-gradient` | Decorative gradient for accent elements or callouts, providing a vibrant, modern touch |
| Midnight Black | `#000000` | `--color-midnight-black` | High-contrast text, icon fills, and foundational strokes |
| Sky Blue | `#3585ff` | `--color-sky-blue` | Decorative strokes and subtle highlights, adding an energetic blue to graphic elements |

## Tokens — Typography

### Plus Jakarta Sans — Primary typeface for all text content, including headings, body, and UI elements. Its clean, geometric sans-serif nature underpins the modern, crisp feel of the interface. · `--font-plus-jakarta-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 36px, 48px, 60px
- **Line height:** 1.00, 1.11, 1.33, 1.43, 1.50, 1.56, 1.71, 1.78
- **Letter spacing:** -0.0250em at 60px, 0.0250em at 12px-18px
- **Role:** Primary typeface for all text content, including headings, body, and UI elements. Its clean, geometric sans-serif nature underpins the modern, crisp feel of the interface.

### Google Sans Code — Used for code snippets or specific technical contexts, providing a distinct monospace visual for functional information. · `--font-google-sans-code`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** 0.0250em
- **Role:** Used for code snippets or specific technical contexts, providing a distinct monospace visual for functional information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.78 | 0.3px | `--text-caption` |
| body-sm | 14px | 1.71 | 0.35px | `--text-body-sm` |
| body | 16px | 1.5 | 0.4px | `--text-body` |
| subheading | 18px | 1.56 | 0.45px | `--text-subheading` |
| heading | 36px | 1.33 | -0.9px | `--text-heading` |
| heading-lg | 48px | 1.11 | -1.2px | `--text-heading-lg` |
| display | 60px | 1 | -1.5px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| inputs | 4px |
| buttons | 12px |

### Layout

- **Section gap:** 40px
- **Card padding:** 0px
- **Element gap:** 24px

## Components

### Primary Filled Button
**Role:** Interactive element, calls to action

Solid Electric Violet (#7270ff) background, Bright White (#ffffff) text (Plus Jakarta Sans, weight 500, 16px), 12px border-radius, with 6px vertical and 20px horizontal padding. A vibrant, confident call to action.

### Navigation Link
**Role:** Primary navigation, secondary actions

Stormy Indigo (#2f2b4a) text (Plus Jakarta Sans, weight 500, 16px), with no background or border, used for key navigational items. On hover, a subtle interaction would likely be present.

### Image Card
**Role:** Content display, feature showcases

Bright White (#ffffff) background, with an 8px border-radius. No padding is set on the card itself, assuming content provides its own internal spacing. Designed for containing visual content like product shots or animated previews.

### Search/Input Field
**Role:** User input, search functionality

Implied white background with an Ash Gray (#e5e7eb) 1px solid border and 4px border-radius. Text input would be Stormy Indigo (#2f2b4a) (Plus Jakarta Sans, 16px).

### Branded Logo
**Role:** Identity mark, decorative branding

Lottielab logo with an implied Deep Sea Blue (#1560fb) or Electric Violet (#7270ff) fill, potentially using the 'L' character as an icon with 9999px border-radius creating a pill shape.

## Do's and Don'ts

### Do
- Prioritize Plus Jakarta Sans for all textual content, ensuring consistency across headlines, body, and UI elements.
- Use Electric Violet (#7270ff) exclusively for primary calls to action (filled buttons) and brand highlights, reserving its impact.
- Maintain a clear visual hierarchy with Stormy Indigo (#2f2b4a) for primary text and headings, and Soft Gray (#4b5563) for secondary or descriptive text.
- Apply 12px border-radius for all primary buttons and 8px for cards, establishing a consistent softening of UI elements.
- Utilize Bright White (#ffffff) as the primary canvas for content, with Light Mist (#f3f4f6) as a subtle background for section separation.
- Employ Ash Gray (#e5e7eb) for all hairline borders and subtle dividers, maintaining a lightweight visual structure.
- Use a minimum element gap of 24px and base vertical spacing on multiples of 8px to ensure comfortable density.

### Don't
- Do not introduce new typefaces; rely solely on Plus Jakarta Sans and Google Sans Code.
- Avoid using Electric Violet (#7270ff) for large blocks of text or non-interactive elements, as it dilutes its semantic meaning.
- Do not use dark backgrounds for main content areas; maintain the light theme with Bright White (#ffffff) and Light Mist (#f3f4f6).
- Do not deviate from the established border-radius values (12px for buttons, 8px for cards, 9999px for tags) to preserve component consistency.
- Avoid applying heavy shadows or complex gradients unless explicitly defined, adhere to the clean, flat aesthetic.
- Do not reduce primary text contrast by using lighter grays on white backgrounds; ensure readability with Stormy Indigo (#2f2b4a) or Midnight Charcoal (#1c1a2c).
- Avoid arbitrary color usage; every color should serve a defined role (brand, neutral, accent, semantic) from the established palette.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Bright White Canvas | `#ffffff` | Primary page background, default surface for most content. |
| 1 | Light Mist Section | `#f3f4f6` | Secondary background for alternating sections, providing a subtle contrast and visual rhythm. |
| 2 | Snow Drift Card | `#f9fafb` | Background for elevated cards or specific UI components, offering a slightly lighter visual plane. |

## Agent Prompt Guide

### Quick Color Reference
- text: #2f2b4a (Stormy Indigo)
- background: #ffffff (Bright White)
- border: #e5e7eb (Ash Gray)
- accent: #3585ff (Sky Blue)
- primary action: #7270ff (filled action)

### 3-5 Example Component Prompts
- Create a hero section: Bright White (#ffffff) background. Headline 'The motion design tool for product teams' in Stormy Indigo (#2f2b4a), Plus Jakarta Sans, 60px, weight 700, letter-spacing -1.5px. Subtext 'Create and edit lottie animations, ship to your apps and websites.' in Stormy Indigo (#2f2b4a), Plus Jakarta Sans, 18px, weight 400. Primary button: 'Get started for free' (Electric Violet background: #7270ff, Bright White text: #ffffff, Plus Jakarta Sans, 16px, weight 500, 12px border-radius, 6px 20px padding).
- Create a navigation bar: Bright White (#ffffff) background. Logo asset (Lottielab) on left. Nav links 'Templates', 'Case studies', 'Pricing' in Stormy Indigo (#2f2b4a), Plus Jakarta Sans, 16px, weight 500. Login link in Stormy Indigo (#2f2b4a), Plus Jakarta Sans, 16px, weight 500. Sign up button (Electric Violet background: #7270ff, Bright White text: #ffffff, Plus Jakarta Sans, 16px, weight 500, 12px border-radius, 6px 20px padding).
- Design a feature card: Snow Drift (#f9fafb) background. 8px border-radius. Headline (e.g. 'Customizable Animations') in Stormy Indigo (#2f2b4a), Plus Jakarta Sans, 18px, weight 600. Body text (e.g. 'Easily tweak every detail to fit your brand.') in Soft Gray (#4b5563), Plus Jakarta Sans, 16px, weight 400. Ensure internal padding is at least 24px.

## Similar Brands

- **Figma** — Clean white interfaces, focus on product functionality, and a single vibrant accent color (Figma's blue vs. Lottielab's violet) for interactive elements.
- **Linear** — Minimalist aesthetic, strong emphasis on typography for hierarchy, and sparse, deliberate use of color for functional cues.
- **Framerm** — Modern design tool aesthetic with a light background, prominent product showcases (interactive components or animations), and distinct, purposeful use of brand colors.
- **Vercel** — Crisp, developer-focused UI with a predominantly white/light grey theme, clear typography, and a strategic use of color to highlight actions and information.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-stormy-indigo: #2f2b4a;
  --color-midnight-charcoal: #1c1a2c;
  --color-electric-violet: #7270ff;
  --color-deep-sea-blue: #1560fb;
  --color-soft-gray: #4b5563;
  --color-bright-white: #ffffff;
  --color-ash-gray: #e5e7eb;
  --color-light-mist: #f3f4f6;
  --color-stone-gray: #9ca3af;
  --color-pale-silver: #d9dbda;
  --color-snow-drift: #f9fafb;
  --color-sunny-gradient: #facc15;
  --gradient-sunny-gradient: linear-gradient(to right, rgb(250, 204, 21), rgb(249, 115, 22));
  --color-sunset-gradient: #ec4899;
  --gradient-sunset-gradient: linear-gradient(to right, rgb(236, 72, 153), rgb(248, 113, 113));
  --color-midnight-black: #000000;
  --color-sky-blue: #3585ff;

  /* Typography — Font Families */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-google-sans-code: 'Google Sans Code', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.78;
  --tracking-caption: 0.3px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --tracking-body-sm: 0.35px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --tracking-subheading: 0.45px;
  --text-heading: 36px;
  --leading-heading: 1.33;
  --tracking-heading: -0.9px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.2px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.5px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 0px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-inputs: 4px;
  --radius-buttons: 12px;

  /* Surfaces */
  --surface-bright-white-canvas: #ffffff;
  --surface-light-mist-section: #f3f4f6;
  --surface-snow-drift-card: #f9fafb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-stormy-indigo: #2f2b4a;
  --color-midnight-charcoal: #1c1a2c;
  --color-electric-violet: #7270ff;
  --color-deep-sea-blue: #1560fb;
  --color-soft-gray: #4b5563;
  --color-bright-white: #ffffff;
  --color-ash-gray: #e5e7eb;
  --color-light-mist: #f3f4f6;
  --color-stone-gray: #9ca3af;
  --color-pale-silver: #d9dbda;
  --color-snow-drift: #f9fafb;
  --color-sunny-gradient: #facc15;
  --color-sunset-gradient: #ec4899;
  --color-midnight-black: #000000;
  --color-sky-blue: #3585ff;

  /* Typography */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-google-sans-code: 'Google Sans Code', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.78;
  --tracking-caption: 0.3px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --tracking-body-sm: 0.35px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --tracking-subheading: 0.45px;
  --text-heading: 36px;
  --leading-heading: 1.33;
  --tracking-heading: -0.9px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.11;
  --tracking-heading-lg: -1.2px;
  --text-display: 60px;
  --leading-display: 1;
  --tracking-display: -1.5px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-192: 192px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 24px;
  --radius-full: 9999px;
}
```
