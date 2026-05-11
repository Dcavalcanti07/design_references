# Browserbase — Style Reference
> Pixelated digital landscape

**Theme:** light

Browserbase evokes a digital landscape with a stark white canvas and minimalist, pixel-inspired graphics. Typography uses custom sans-serif and monospaced fonts, emphasizing functional clarity and a slightly technical aesthetic. Orange and muted near-grays introduce moments of warm contrast, while primary UI elements are grounded in achromatic black and white, presenting a clean, high-contrast, and buttoned-down developer tool experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated surfaces, card surfaces, text elements where inverted against dark backgrounds |
| Ink Black | `#000000` | `--color-ink-black` | Primary text, button backgrounds, borders, strokes, icon fills — establishes strong contrast |
| Cloud Gray | `#f8fafc` | `--color-cloud-gray` | Subtle background for UI elements, very light surface differentiation |
| Powder Blue | `#e2e9f3` | `--color-powder-blue` | Card backgrounds, section separators, background for selected UI states |
| Pale Sage | `#fffde6` | `--color-pale-sage` | Alternative soft background for cards or sections, creating a subtle warmth |
| Charcoal Text | `#686562` | `--color-charcoal-text` | Secondary body text, muted details, hints of softer contrast |
| Impact Orange | `#ff4500` | `--color-impact-orange` | Key branding accent, highlighted text, decorative elements, focal points in hero sections — signals importance and brand identity |
| Sky Tint | `#c4edff` | `--color-sky-tint` | Badge backgrounds, subtle accents, background for informational elements |
| Pixel Mountain | `#c5d3e8` | `--color-pixel-mountain` | Decorative background fills, button backgrounds for secondary actions — adds muted, textured feel |

## Tokens — Typography

### plain — Primary text for body copy, links, navigation items, and button labels. Its clean and neutral sans-serif form ensures readability for functional content. · `--font-plain`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px, 24px
- **Line height:** 1.00, 1.10, 1.16, 1.30, 1.41, 1.50
- **Letter spacing:** 0.007em at 16px, 0.010em at 24px
- **Role:** Primary text for body copy, links, navigation items, and button labels. Its clean and neutral sans-serif form ensures readability for functional content.

### gtPlanar — Dominant font for headings and prominent display text. Its distinct character and tighter letter spacing at larger sizes contribute to a modern, confident tone, subtly hinting at its custom nature. · `--font-gtplanar`
- **Substitute:** DM Sans
- **Weights:** 400, 500
- **Sizes:** 16px, 24px, 34px, 45px, 189px
- **Line height:** 1.00, 1.10, 1.15, 1.50
- **Letter spacing:** -0.050em at 189px, -0.020em at 45px
- **OpenType features:** `"ss05"`
- **Role:** Dominant font for headings and prominent display text. Its distinct character and tighter letter spacing at larger sizes contribute to a modern, confident tone, subtly hinting at its custom nature.

### gtStandardMono — Used for code snippets, badges, and technical labels. The monospaced nature reinforces the developer-centric focus of the product. · `--font-gtstandardmono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.030em at 14px, 0.060em for other uses
- **Role:** Used for code snippets, badges, and technical labels. The monospaced nature reinforces the developer-centric focus of the product.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 14px | 1.2 | 0.42px | `--text-body-sm` |
| body | 16px | 1.5 | 0.112px | `--text-body` |
| subheading | 24px | 1.16 | 0.24px | `--text-subheading` |
| heading | 34px | 1.15 | — | `--text-heading` |
| heading-lg | 45px | 1.1 | -0.9px | `--text-heading-lg` |
| display | 189px | 1 | -9.45px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 96 | 96px | `--spacing-96` |
| 224 | 224px | `--spacing-224` |

### Border Radius

| Element | Value |
|---------|-------|
| lists | 999px |
| buttons | 50px |
| roundedElements | 4px |

### Layout

- **Section gap:** 75px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Call to action button for essential actions

Ink Black background (#000000), Canvas White text (#ffffff), 50px border-radius, 11px vertical padding, 9.936px horizontal padding. Prominent and easily identifiable.

### Ghost Navigation Button
**Role:** Navigation items and secondary actions within headers/menus

Transparent background, Ink Black text (#000000), no border-radius or border, 10px vertical and 20.8px horizontal padding. Subtle and integrates into flow.

### Accent Pill Button
**Role:** Secondary action button with specific highlight

Pixel Mountain background (#e2e9f3), Ink Black text (#000000), 50px border-radius, 11.2px vertical padding, 16-20.8px horizontal padding. Draws attention without being primary.

### Compact Info Button
**Role:** Small, information-dense button often used in feature lists

Pale Sage background (#fffde6), Ink Black text (#000000), no border-radius. 7.2px vertical and 12-47px horizontal padding. Visually distinct but not as attention-grabbing as primary.

### Transparent Content Card
**Role:** Container for content sections without visual separation

Transparent background, no box shadow or border, 0px border-radius, generous 75px vertical padding and 16px horizontal padding. Used for large, flowing sections.

### Pale Gray Feature Card
**Role:** Container for feature blocks or grouped content

Powder Blue background (#e2e9f3), no box shadow or border, 0px border-radius, 16px padding on top. Used to subtly differentiate sections of content.

### White Section Card
**Role:** Standard content card, visually distinct from background

Canvas White background (#ffffff), no box shadow or border, 0px border-radius, 75px vertical and 16px horizontal padding. Provides a clean content surface.

### Text Badge
**Role:** Minimalist textual indicator or tag

Transparent background, Ink Black text (#000000), no border-radius or padding. Used for simple categorization.

### Sky Tint Badge
**Role:** Informational or emphasized tag

Sky Tint background (#c4edff), Ink Black text (#000000), no border-radius, `gtStandardMono` font, minimal horizontal padding (3.5px). Used for accentuating specific keywords or statuses.

## Do's and Don'ts

### Do
- Prioritize Ink Black (#000000) for primary text and interactive elements to maintain high contrast and clarity.
- Use Impact Orange (#ff4500) sparingly for emphasis, branding accents, or key headlines to draw attention.
- Apply 50px border-radius to all primary and accent buttons to create a consistent pill-shaped aesthetic.
- Segment content using Powder Blue (#e2e9f3) and Pale Sage (#fffde6) as background colors for cards and feature blocks.
- Maintain generous vertical spacing for sections (75px) with narrower horizontal padding for text containers (16px) to ensure readability.
- Employ `gtPlanar` for all headings and `plain` for body text, reserving `gtStandardMono` for technical labels and badges.
- Ensure interactive elements such as buttons and navigation items have clear Ink Black (#000000) text against light backgrounds.

### Don't
- Do not introduce new primary action colors; stick to Ink Black for filled buttons or transparent for ghost buttons.
- Avoid using multiple high-saturation colors at once, as the system relies on a mostly achromatic palette with specific accents.
- Do not deviate from the specified font families for their respective roles; `gtPlanar`, `plain`, and `gtStandardMono` define the typographic voice.
- Do not add heavy box shadows or decorative gradients; the design emphasizes flat surfaces and minimal elevation.
- Avoid using a single large border-radius for all elements; adapt radius based on component (50px for buttons, 4px for other UI elements).
- Do not use generic system fonts; the custom 'plain', 'gtPlanar', and 'gtStandardMono' are crucial for brand identity.
- Do not create dense layouts; maintain compact element spacing (8px) while allowing ample section separation (75px).

## Imagery

The imagery primarily consists of simplified, abstract graphical representations and pixel art, rather than photography or complex illustrations. These graphics often feature clean, geometric shapes and an outlined style. Color is used sparingly within these graphics, often leveraging the brand's accent colors or muted tones. Imagery serves an explanatory and atmospheric role, showcasing product concepts or creating an abstract digital environment. The density is moderate, allowing text to dominate while visuals provide conceptual anchors.

## Layout

The page follows a max-width contained model, centrally aligning content within a clear visual boundary. The hero section is full-bleed, featuring a striking pixelated mountain graphic with a centered headline and action buttons. Subsequent sections alternate between full-width transparent cards and slightly tinted, contained feature cards, maintaining a consistent vertical rhythm with generous 75px section gaps. Content is arranged in flexible patterns, sometimes centered stacks, sometimes text-left/image-right or multi-column card grids. The navigation is a classic top bar, sticky on scroll, with log in/sign up links and a distinct primary action button. The overall density is balanced, providing breathing room between sections while presenting information in clear, organized blocks.

## Agent Prompt Guide

### Quick Color Reference
- text: #000000
- background: #ffffff
- border: #000000
- accent: #ff4500
- primary action: #000000 (filled action)

### 3-5 Example Component Prompts
- Create a hero callout: Background Powder Blue (#e2e9f3). Headline 'Give your agents access to the whole web.' in gtPlanar, 45px weight 500, Ink Black (#000000), letter-spacing -0.9px. Primary Action Button 'Get API key' with Ink Black (#000000) background, Canvas White (#ffffff) text, 50px radius, 11px vertical padding.
- Design a feature card: Powder Blue (#e2e9f3) background, 0px radius, 16px top padding. Body text 'Build agents that never sleep' in plain, 16px weight 400, Ink Black (#000000). At the bottom, a Primary Action Button 'Get started' with Ink Black (#000000) background, Canvas White (#ffffff) text, 50px radius.
- Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Vercel** — Monochrome palette with a single bright accent color, minimalist UI, and strong typography.
- **Supabase** — Developer-tool aesthetic with clean lines, high-contrast text, and subtle background textures/gradients.
- **Linear** — Focus on high-density information display within a clean, achromatic interface, using small, functional color accents.
- **Clerk** — Modern SaaS with prominent, custom display typography and a heavy reliance on a neutral color scheme for UI elements.
- **Anthropic** — AI/tech brand utilizing a clean white canvas, prominent sans-serif headings, and restrained use of color for key brand elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-cloud-gray: #f8fafc;
  --color-powder-blue: #e2e9f3;
  --color-pale-sage: #fffde6;
  --color-charcoal-text: #686562;
  --color-impact-orange: #ff4500;
  --color-sky-tint: #c4edff;
  --color-pixel-mountain: #c5d3e8;

  /* Typography — Font Families */
  --font-plain: 'plain', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtplanar: 'gtPlanar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandardmono: 'gtStandardMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.112px;
  --text-subheading: 24px;
  --leading-subheading: 1.16;
  --tracking-subheading: 0.24px;
  --text-heading: 34px;
  --leading-heading: 1.15;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.9px;
  --text-display: 189px;
  --leading-display: 1;
  --tracking-display: -9.45px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-96: 96px;
  --spacing-224: 224px;

  /* Layout */
  --section-gap: 75px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 50px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-lists: 999px;
  --radius-buttons: 50px;
  --radius-roundedelements: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-cloud-gray: #f8fafc;
  --color-powder-blue: #e2e9f3;
  --color-pale-sage: #fffde6;
  --color-charcoal-text: #686562;
  --color-impact-orange: #ff4500;
  --color-sky-tint: #c4edff;
  --color-pixel-mountain: #c5d3e8;

  /* Typography */
  --font-plain: 'plain', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtplanar: 'gtPlanar', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandardmono: 'gtStandardMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: 0.42px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.112px;
  --text-subheading: 24px;
  --leading-subheading: 1.16;
  --tracking-subheading: 0.24px;
  --text-heading: 34px;
  --leading-heading: 1.15;
  --text-heading-lg: 45px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.9px;
  --text-display: 189px;
  --leading-display: 1;
  --tracking-display: -9.45px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-96: 96px;
  --spacing-224: 224px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-full: 50px;
  --radius-full-2: 999px;
}
```
