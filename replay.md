# Replay — Style Reference
> Crisp developer console

**Theme:** light

Replay presents a clean, developer-focused interface with distinct call-to-action colors against a largely achromatic background. The design emphasizes clear hierarchy through bold typography and subtle surface variations rather than heavy shadows or complex gradients. The overall atmosphere is modern and precise, with interactive elements highlighted by a vibrant red-pink accent color and strategic use of rounded corners.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111827` | `--color-midnight-ink` | Primary text, deep surface backgrounds for elevated components, navigation text |
| Slate Gray | `#374151` | `--color-slate-gray` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Ghostly Carbon | `#1f2937` | `--color-ghostly-carbon` | Muted button backgrounds (e.g., for code samples or utility actions), dark card backgrounds |
| Lilac Whisper | `#e9d5ff` | `--color-lilac-whisper` | Subtle border accent for cards, indicating a specific state or category |
| Flamingo Red | `#f02d5e` | `--color-flamingo-red` | Decorative accent for headlines and text highlights, outline buttons, navigation links |
| Blue Violet | `#3762e2` | `--color-blue-violet` | Informational links and icons |
| Ash Cloud | `#6b7280` | `--color-ash-cloud` | Helper text, low-emphasis body copy |
| System Canvas | `#e5e7eb` | `--color-system-canvas` | Page backgrounds, dividers, low-contrast borders |
| Pure Black | `#000000` | `--color-pure-black` | Decorative elements, high-contrast text on light backgrounds |
| Pure White | `#ffffff` | `--color-pure-white` | Card backgrounds, primary surface, text on dark backgrounds |
| Pebble Gray | `#f3f4f6` | `--color-pebble-gray` | Subtle background for specific card states or data displays, slightly off-white surfaces |
| Silver Mist | `#d1d5db` | `--color-silver-mist` | Secondary button text, low-contrast borders |
| Pearly Black | `#8f949b` | `--color-pearly-black` | Muted background for hover states or subtle interactive elements |
| Stormy Sky | `#9ca3af` | `--color-stormy-sky` | Placeholder text, secondary icon colors |
| Replay Red | `linear-gradient(to right, rgb(244, 63, 94), rgb(147, 51, 234))` | `--color-replay-red` | Primary Call-to-action buttons (fill), prominent interactive elements; Accent gradient, often used decoratively or for subtle brand elements |
| Sunrise Horizon Gradient | `linear-gradient(to right top, rgb(255, 128, 181), rgb(144, 137, 252))` | `--color-sunrise-horizon-gradient` | Upper banner background, decorative elements |
| Ocean Deep Gradient | `linear-gradient(to right, rgb(128, 202, 255), rgb(79, 70, 229))` | `--color-ocean-deep-gradient` | Additional accent gradient, decorative |

## Tokens — Typography

### Inter — The primary typeface for all textual content. Its clean, modern character supports both highly legible body copy and impactful headlines. Varied weights create clear hierarchy while maintaining a cohesive voice. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 40px, 48px, 80px
- **Line height:** 0.90, 1.10, 1.17, 1.33, 1.40, 1.50, 1.60, 1.63, 1.71, 1.75, 1.78, 2.29
- **Letter spacing:** -0.0250em, -0.0190em, 0.0250em, 0.0500em
- **Role:** The primary typeface for all textual content. Its clean, modern character supports both highly legible body copy and impactful headlines. Varied weights create clear hierarchy while maintaining a cohesive voice.

### ui-monospace — Used for code snippets and technical examples, providing a distinct, monospaced visual language for developer-centric content. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 600
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** normal
- **Role:** Used for code snippets and technical examples, providing a distinct, monospaced visual language for developer-centric content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.71 | — | `--text-caption` |
| body-sm | 14px | 1.71 | — | `--text-body-sm` |
| body | 16px | 1.71 | — | `--text-body` |
| subheading | 18px | 1.78 | — | `--text-subheading` |
| heading-sm | 20px | 1.6 | — | `--text-heading-sm` |
| heading | 40px | 1.1 | -0.6px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.72px | `--text-heading-lg` |
| display | 80px | 0.9 | -2px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| large | 16px |
| inputs | 8px |
| buttons | 9999px |
| general | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(17, 24, 39, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1...` | `--shadow-subtle` |
| subtle-2 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-2` |
| xl | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl` |

### Layout

- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Call-to-Action Button
**Role:** Main action button, drawing immediate attention.

Filled with Replay Red (#f43f5e), white text (#ffffff), and a full pill shape (9999px radius). Padding: 0px vertical, 32px horizontal. Font: Inter, weight 400.

### Navigation Link Button
**Role:** Outlined button for navigation, less prominent than primary CTA.

Ghost button with a border in #e5e7eb, text in Midnight Ink (#111827), 9999px radius. Padding: 8px vertical, 12px horizontal.

### Muted Code Card
**Role:** Card for displaying code snippets or technical details.

Background Ghostly Carbon (#1f2937) with 8px border-radius, no shadow. Padding 0px. Text color #d1d5db.

### Testimonial Card
**Role:** Used for displaying customer testimonials or quotes.

Pure White (#ffffff) background, 12px border-radius, no box shadow. Padding: 24px in all directions. Utilizes a subtle Lilac Whisper (#e9d5ff) border as an accent.

### Ghost Text Button (Interactive)
**Role:** Low-emphasis actions, often inline or secondary to primary actions.

Transparent background, text in Midnight Ink (#111827), no radius explicitly set, but often 0px. Padding variable: 20px vertical, 0px horizontal.

### Section Heading
**Role:** Large, impactful titles for major page sections.

Text color Midnight Ink (#111827) with a portion accented in Flamingo Red (#f02d5e). Font: Inter, weights 600 or 700, sizes 40px, 48px or 80px, with negative letter spacing.

### Utility Bar Banner
**Role:** Top-most information banner for announcements.

Background uses Sunrise Horizon Gradient (linear-gradient(to right top, #ff80b5, #908dfc)). Text color Pure White (#ffffff). Small font size.

## Do's and Don'ts

### Do
- Use Inter for all UI text, selecting appropriate weights (400, 500, 600, 700) from the provided scale.
- Highlight primary actions with Replay Red (#f43f5e) filled buttons with 9999px radius for a pill shape.
- Structure information using Pure White (#ffffff) cards with 12px border-radius for testimonials and content blocks.
- Employ System Canvas (#e5e7eb) as the primary page background color for a clean, light base.
- Use Midnight Ink (#111827) for primary heading and body text to ensure strong contrast against light surfaces.
- For subtle borders and dividers, use System Canvas (#e5e7eb) at 1px solid.
- Maintain a clear visual hierarchy with generous vertical spacing, typically 48px to 64px between sections and 24px as a standard padding for content blocks.

### Don't
- Do not introduce new typefaces outside of Inter and ui-monospace.
- Avoid using a full range of saturated colors for general UI elements; reserve them for accents and specific brand elements.
- Do not use heavy, complex shadows; rely on minimal elevation values like rgba(0, 0, 0, 0.05) 0px 1px 2px 0px for subtle depth.
- Do not deviate from the established border radii: 9999px for buttons, 12px for cards, 8px for smaller elements, and 4px for general utility.
- Avoid making every button a brightly colored CTA; use ghost buttons with text in Midnight Ink (#111827) for secondary actions.
- Do not use dark backgrounds for main content sections; maintain a light theme for readability and visual calm.
- Do not neglect the subtle negative letter spacing on larger headlines; it is a signature characteristic of Inter at scale.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | System Canvas | `#e5e7eb` | Base page background |
| 1 | Pebble Gray | `#f3f4f6` | Slightly elevated backgrounds, subtle differentiation |
| 2 | Pure White | `#ffffff` | Primary surface for cards, panels, and content blocks |
| 3 | Ghostly Carbon | `#1f2937` | Darker surfaces for code blocks or specific card types |

## Elevation

- **Button:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Card (Testimonial Example):** `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px`

## Imagery

The site predominantly uses product screenshots and technical icons, avoiding lifestyle photography. Product screenshots are typically contained rather than full-bleed, often placed next to explanatory text. Icons are simple, outlined or filled, and primarily monochrome or in Brand Blue Violet (#3762e2). Graphics are functional, providing context or illustrating concepts, rather than purely decorative. There is a preference for abstract geometric patterns and subtle gradients as background elements, creating an atmospheric but non-distracting visual layer. The overall density is text-dominant, with imagery serving as supportive illustration.

## Layout

The page uses a maximum-width contained layout, centered on the screen, adhering to a conceptual grid typically wider than typical. The hero section often features a centered headline over a subtle abstract background pattern or gradient. Content sections alternate between centered stacks of text and visuals, and two-column layouts featuring text on one side and an illustrative visual (screenshot, data display, or icon) on the other. Card grids, typically 3-column, are used for features or testimonials. Vertical spacing between major sections is generous, ensuring breathing room, with section gaps around 48px. The header is sticky, featuring a logo, navigation links, and a prominent call-to-action button.

## Agent Prompt Guide

Quick Color Reference:
text: #111827
background: #e5e7eb
border: #e5e7eb
accent: #f02d5e
primary action: #f43f5e (filled action)

Example Component Prompts:
1. Create a primary CTA button: Replay Red (#f43f5e) background, Pure White (#ffffff) text (Inter weight 400), 9999px radius, 0px vertical padding, 32px horizontal padding.
2. Create a testimonial card: Pure White (#ffffff) background, 24px padding, 12px border-radius, Lilac Whisper (#e9d5ff) 1px solid border, with a title in Midnight Ink (#111827) Inter weight 600 size 18px.
3. Create a dark utility button: Ghostly Carbon (#1f2937) background, Silver Mist (#d1d5db) text (Inter weight 400), 8px radius, 8px vertical padding, 12px horizontal padding.
4. Create a main section headline: Midnight Ink (#111827) text (Inter weight 700 size 48px, letterSpacing -0.72px), with a specific word in Flamingo Red (#f02d5e).

## Similar Brands

- **Vercel** — Monochromatic clean aesthetic with a single strong accent color, clear typography, and a developer-focused, component-driven UI.
- **Supabase** — Light theme, Inter typography, and use of vibrant, tech-y accent colors against a largely gray/white palette.
- **Plausible Analytics** — Straightforward data-centric design, strong typography, and a focus on clarity over visual embellishment, with subtle color accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111827;
  --color-slate-gray: #374151;
  --color-ghostly-carbon: #1f2937;
  --color-lilac-whisper: #e9d5ff;
  --color-flamingo-red: #f02d5e;
  --color-blue-violet: #3762e2;
  --color-ash-cloud: #6b7280;
  --color-system-canvas: #e5e7eb;
  --color-pure-black: #000000;
  --color-pure-white: #ffffff;
  --color-pebble-gray: #f3f4f6;
  --color-silver-mist: #d1d5db;
  --color-pearly-black: #8f949b;
  --color-stormy-sky: #9ca3af;
  --color-replay-red: #f43f5e;
  --gradient-replay-red: linear-gradient(to right, rgb(244, 63, 94), rgb(147, 51, 234));
  --color-sunrise-horizon-gradient: #ff80b5;
  --gradient-sunrise-horizon-gradient: linear-gradient(to right top, rgb(255, 128, 181), rgb(144, 137, 252));
  --color-ocean-deep-gradient: #80caff;
  --gradient-ocean-deep-gradient: linear-gradient(to right, rgb(128, 202, 255), rgb(79, 70, 229));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --text-body: 16px;
  --leading-body: 1.71;
  --text-subheading: 18px;
  --leading-subheading: 1.78;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.6;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.6px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.72px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -2px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-large: 16px;
  --radius-inputs: 8px;
  --radius-buttons: 9999px;
  --radius-general: 4px;

  /* Shadows */
  --shadow-subtle: rgba(17, 24, 39, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;

  /* Surfaces */
  --surface-system-canvas: #e5e7eb;
  --surface-pebble-gray: #f3f4f6;
  --surface-pure-white: #ffffff;
  --surface-ghostly-carbon: #1f2937;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111827;
  --color-slate-gray: #374151;
  --color-ghostly-carbon: #1f2937;
  --color-lilac-whisper: #e9d5ff;
  --color-flamingo-red: #f02d5e;
  --color-blue-violet: #3762e2;
  --color-ash-cloud: #6b7280;
  --color-system-canvas: #e5e7eb;
  --color-pure-black: #000000;
  --color-pure-white: #ffffff;
  --color-pebble-gray: #f3f4f6;
  --color-silver-mist: #d1d5db;
  --color-pearly-black: #8f949b;
  --color-stormy-sky: #9ca3af;
  --color-replay-red: #f43f5e;
  --color-sunrise-horizon-gradient: #ff80b5;
  --color-ocean-deep-gradient: #80caff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.71;
  --text-body-sm: 14px;
  --leading-body-sm: 1.71;
  --text-body: 16px;
  --leading-body: 1.71;
  --text-subheading: 18px;
  --leading-subheading: 1.78;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.6;
  --text-heading: 40px;
  --leading-heading: 1.1;
  --tracking-heading: -0.6px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.72px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(17, 24, 39, 0.05) 0px 0px 0px 1px, rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-subtle-2: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
}
```
