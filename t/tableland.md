# Tableland — Style Reference
> Midnight data oasis

**Theme:** dark

Tableland employs a dark, tech-forward aesthetic, featuring deeply saturated neutral backgrounds punctuated by a vibrant teal and an electric green. The typography is understated yet distinct, pairing a clear sans-serif with monospace for code. Design elements lean towards soft, rounded containers and minimal elevation, presenting complex data concepts in an approachable, almost serene visual environment. Accents are used sparingly for active states or key information, directing attention efficiently without overwhelming the user.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#101e1e` | `--color-deep-space` | Primary page background, card backgrounds, fills for ghost buttons — provides the core dark canvas |
| Shadow Realm | `#162929` | `--color-shadow-realm` | Subtle card surface, button backgrounds, element borders — a slightly lighter variant of the canvas color, hints at depth |
| Graphite | `#3b4949` | `--color-graphite` | Elevated card backgrounds, interactive button fills — a mid-tone neutral for active elements and layered surfaces |
| Code Block | `#1a1a1a` | `--color-code-block` | Code block backgrounds, primary text on light surfaces (seen in contrast pairs) — a near-black for content blocks |
| Mist | `#e5e7eb` | `--color-mist` | Hairline borders, dividers, subtle outlines — provides contrast against dark neutrals without being stark white |
| Porcelain | `#ffffff` | `--color-porcelain` | Primary text on dark backgrounds, active icon fills — stands out crisply against the dark palette |
| Teal Accent | `#75b6b5` | `--color-teal-accent` | Teal text accent for links, tags, and emphasized short phrases. Do not promote it to the primary CTA color |
| Emerald Spark | `#0be291` | `--color-emerald-spark` | Decorative heading accents, special text highlights — a vivid green for emphasis and brand identity |
| Lavender Haze | `#e4cbf2` | `--color-lavender-haze` | Atmospheric hero section background, decorative oversized graphic elements — a soft, muted pink creates a gradient-like backdrop |
| Cardinal Red | `#f4706b` | `--color-cardinal-red` | Minimal accent for selected nav items, alerts — a vibrant red for small, impactful highlights |
| Subtle Grey Text | `#718b8b` | `--color-subtle-grey-text` | Muted body text, secondary information, icon strokes and fills — recedes slightly to support hierarchy |

## Tokens — Typography

### Poppins — Primary typeface for all text content including headings, body text, and UI elements. The consistent sans-serif provides clarity, with the lighter weights (300, 400) giving a clean, modern feel to headlines and body text. · `--font-poppins`
- **Substitute:** system-ui, sans-serif
- **Weights:** 300, 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 18px, 22px, 24px, 30px, 48px
- **Line height:** 1.00, 1.20, 1.33, 1.43, 1.45, 1.50, 1.56, 1.78
- **Letter spacing:** normal
- **Role:** Primary typeface for all text content including headings, body text, and UI elements. The consistent sans-serif provides clarity, with the lighter weights (300, 400) giving a clean, modern feel to headlines and body text.

### monospace — Strictly used for code snippets and technical examples. Its fixed-width nature ensures precise alignment for developer-focused content. · `--font-monospace`
- **Substitute:** SFMono-Regular, Consolas, Liberation Mono, Menlo, monospace
- **Weights:** 300
- **Sizes:** 12px
- **Line height:** 1.33
- **Letter spacing:** normal
- **Role:** Strictly used for code snippets and technical examples. Its fixed-width nature ensures precise alignment for developer-focused content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.5 | — | `--text-body` |
| heading-sm | 18px | 1.43 | — | `--text-heading-sm` |
| heading | 22px | 1.33 | — | `--text-heading` |
| heading-lg | 24px | 1.2 | — | `--text-heading-lg` |
| display-sm | 30px | 1 | — | `--text-display-sm` |
| display | 48px | 1 | — | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| inputs | 4px |
| buttons | 16px |
| navigation | 12px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Action button

Solid background button with 'Graphite' fill (#3b4949), 'Porcelain' text (#ffffff) at 16px Poppins weight 400, and 16px border-radius. Padding is 12px vertical, 32px horizontal.

### Secondary Ghost Button
**Role:** Secondary action button

Outline button with 'Deep Space' background (#101e1e), 'Porcelain' text (#ffffff) at 16px Poppins weight 400, and 16px border-radius. Border is 1px solid 'Shadow Realm' (#162929). Padding is 12px vertical, 32px horizontal.

### Navigation Link Button
**Role:** Navigation and secondary calls to action

Ghost button with a 'Deep Space' background (#101e1e), 'Porcelain' text (#ffffff) at 16px Poppins weight 400, and 16px border-radius. Border is 1px solid 'Mist' (#e5e7eb). Padding is 12px vertical, 32px horizontal.

### Social Proof Card
**Role:** Content container for testimonials/social feeds

Card with 'Graphite' background (#3b4949), 8px border-radius, and 24px padding on all sides. Contains body text in 'Porcelain' (#ffffff) and links in 'Teal Accent' (#75b6b5).

### Feature Card
**Role:** Information display for features or benefits

Transparent card with a 'Shadow Realm' background (#162929), 8px border-radius and 24px padding on all sides. Used without explicit borders, relies on background contrast.

### Code Terminal Block
**Role:** Display of code snippets

Rectangle with 'Code Block' background (#1a1a1a), 'Porcelain' text (#ffffff) set in monospace font at 12px size. The default border-radius is not explicitly defined but visually appears small (4-8px). Padding 12px vertical, up to 24px horizontal. Shows an inner, subtle 'Shadow Realm' (#162929) border.

### Tag / Category Pill
**Role:** Categorization or short labels

Small text containers with 'Deep Space' background (#101e1e), 'Teal Accent' text (#75b6b5), and fully rounded corners (9999px radius). Padding is minimal, typically 4px vertical, 8px horizontal.

## Do's and Don'ts

### Do
- Use 'Deep Space' (#101e1e) as the dominant background color for most page sections.
- Apply 'Porcelain' (#ffffff) for primary text on dark backgrounds and 'Teal Accent' (#75b6b5) for interactive links.
- Utilize Poppins font for all textual content, opting for weight 300 or 400 for a lightweight, modern appearance.
- Ensure buttons consistently use a 16px border-radius and 12px vertical, 32px horizontal padding.
- Employ a base unit of 8px for all spacing decisions, building up elements with 16px gaps and sections with 40px gaps.
- Accent headlines with 'Emerald Spark' (#0be291) when emphasizing key product features or benefits.
- Use 'Mist' (#e5e7eb) for subtle separation, particularly for hairline borders or dividers between content areas.

### Don't
- Avoid using harsh, fully opaque white (#ffffff) for backgrounds; reserve it for high-contrast text.
- Do not introduce sharp corners; maintain the overall soft and rounded aesthetic with radii like 8px or 16px for cards and buttons.
- Refrain from heavy drop shadows or strong elevation; prefer subtle background color shifts ('Shadow Realm' vs 'Deep Space') for defining layers.
- Do not deviate from Poppins for main text or monospace for code; avoid introducing additional typefaces.
- Avoid over-saturating the interface with chromatic colors; reserve 'Teal Accent', 'Emerald Spark', and 'Cardinal Red' for functional or highlight purposes.
- Do not use generic system borders; always apply the defined 'Mist' (#e5e7eb) or 'Shadow Realm' (#162929) for borders.
- Do not use letter-spacing other than 'normal' for the Poppins typeface.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space Canvas | `#101e1` | The foundational page background for most sections, creating a dark, immersive base layer. |
| 1 | Shadow Realm Substrate | `#162929` | A slightly elevated surface used for subtle content blocks or as a border for ghost elements, providing minimal visual separation. |
| 2 | Graphite Card Surface | `#3b4949` | Used for distinct cards and active interactive elements like filled buttons, providing a clear visual lift from the base canvas. |

## Imagery

The site uses a mix of abstract and functional imagery. On the hero, there's a large, abstract, muted pink and purple gradient graphic featuring stylized, canyon-like organic shapes, creating an atmospheric backdrop without specific visual content. For code examples, a minimalist terminal window with monospace text is employed as a product screenshot. For social proof, circular avatar icons are used alongside text. Icons are generally outlined, monochrome, and have a consistent subtle stroke weight, primarily serving an explanatory role. The overall density is text-dominant, with imagery used sparingly to either set a mood or provide functional context.

## Layout

The page primarily uses a max-width 1280px centered content container. The hero section features a full-bleed background with an abstract graphic, and a centered headline inviting interaction. Content sections below often alternate between a dark 'Deep Space' background and a slightly lighter 'Shadow Realm' for visual rhythm, separated by consistent vertical spacing. Text is typically stacked centrally or arranged in multi-column grids (e.g., a 2x2 grid for features), occasionally featuring an image-left/text-right split. Card grids are used for testimonials, employing a flexible, responsive layout where cards have generous padding. Navigation is handled by a sticky top bar with minimal links and a distinct 'Enter Studio' button.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #101e1e
border: #e5e7eb
accent: #75b6b5
primary action: #101e1e (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #101e1e background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Build a Feature Card: 'Shadow Realm' (#162929) background, 8px border-radius, 24px padding. Headline 'SQLite' in Poppins weight 700 with a subtle 'Emerald Spark' (#0be291) color. Body text in 'Porcelain' (#ffffff), and a 'Learn more' link in 'Teal Accent' (#75b6b5).
3. Design a Social Proof Card: 'Graphite' (#3b4949) background, 8px border-radius, 24px padding. Contains body text in 'Porcelain' (#ffffff) Poppins weight 400, and a small '@username' link in 'Teal Accent' (#75b6b5). 
4. Implement a Terminal Code Block: 'Code Block' (#1a1a1a) background, 12px vertical / 24px horizontal padding, 'Porcelain' (#ffffff) text using 'monospace' font at 12px size. Include a top border of 1px solid 'Shadow Realm' (#162929).

## Similar Brands

- **Alchemy.com** — Dark UI with vibrant accent colors for links and calls to action, similar use of muted abstract background graphics.
- **Vercel.com** — Minimalist dark theme, sharp typography, and subtle gradients contrasted with clear, functional UI elements.
- **Supabase.io** — Developer-focused dark UI, prominent use of monospace for code, and a clean, spacious layout with a clear information hierarchy.
- **Polygon.technology** — Blockchain/web3 brand applying dark mode, often with subtle background illustrations and accent colors for interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #101e1e;
  --color-shadow-realm: #162929;
  --color-graphite: #3b4949;
  --color-code-block: #1a1a1a;
  --color-mist: #e5e7eb;
  --color-porcelain: #ffffff;
  --color-teal-accent: #75b6b5;
  --color-emerald-spark: #0be291;
  --color-lavender-haze: #e4cbf2;
  --color-cardinal-red: #f4706b;
  --color-subtle-grey-text: #718b8b;

  /* Typography — Font Families */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monospace: 'monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.43;
  --text-heading: 22px;
  --leading-heading: 1.33;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 30px;
  --leading-display-sm: 1;
  --text-display: 48px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-inputs: 4px;
  --radius-buttons: 16px;
  --radius-navigation: 12px;

  /* Surfaces */
  --surface-deep-space-canvas: #101e1;
  --surface-shadow-realm-substrate: #162929;
  --surface-graphite-card-surface: #3b4949;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #101e1e;
  --color-shadow-realm: #162929;
  --color-graphite: #3b4949;
  --color-code-block: #1a1a1a;
  --color-mist: #e5e7eb;
  --color-porcelain: #ffffff;
  --color-teal-accent: #75b6b5;
  --color-emerald-spark: #0be291;
  --color-lavender-haze: #e4cbf2;
  --color-cardinal-red: #f4706b;
  --color-subtle-grey-text: #718b8b;

  /* Typography */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-monospace: 'monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.43;
  --text-heading: 22px;
  --leading-heading: 1.33;
  --text-heading-lg: 24px;
  --leading-heading-lg: 1.2;
  --text-display-sm: 30px;
  --leading-display-sm: 1;
  --text-display: 48px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-128: 128px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 9999px;
}
```
