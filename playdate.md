# Playdate — Style Reference
> Lemon Drop Arcade. Bright, blocky, and instantly recognizable, like a classic handheld console that makes a statement.

**Theme:** mixed

This design system is a cheerful, high-contrast playground. It marries a distinctive vivid yellow with deep, grounded neutrals and a playful violet, creating an energetic yet sturdy aesthetic. The use of a single, custom typeface (Roobert) across all textual elements unifies the brand's voice, while varied weights and sizes carve out hierarchy. The system intentionally avoids complex shadows and layers, favoring bold color blocks and a crisp, almost physical, presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Playdate Yellow | `#ffc500` | `--color-playdate-yellow` | Primary brand color, highlights, accents, and section backgrounds — a distinctively vivid and playful yellow that defines the brand. |
| Crank Violet | `#7700ff` | `--color-crank-violet` | Key interactive elements like CTA buttons and active navigation links — a vivid violet provides a playful yet authoritative call to action. |
| Seafoam Teal | `#21c6a9` | `--color-seafoam-teal` | An additional accent color, used sparingly, possibly for status indicators or secondary highlights. |
| Deep Teal | `#127866` | `--color-deep-teal` | Darker variant of Seafoam Teal, likely for subtle accents or text on lighter backgrounds. |
| Charcoal Text | `#312f27` | `--color-charcoal-text` | Primary text color and darker element backgrounds — a very dark, slightly desaturated near-black that grounds the vibrant brand colors. |
| Pure White | `#ffffff` | `--color-pure-white` | Backgrounds, inverse text, and contrast elements — providing stark contrast to Charcoal Text and Playdate Yellow. |
| Midnight Absolute | `#000000` | `--color-midnight-absolute` | Shadows, outlines, and occasionally bold text — its pure black presence adds weight and definition. |
| Default Gray | `#788086` | `--color-default-gray` | Subtle background tones or secondary text. |
| Paper White | `#efefef` | `--color-paper-white` | Input field backgrounds and subtle borders — a very light, almost white gray. |
| Ink Wash | `#212223` | `--color-ink-wash` | Darker backgrounds, similar to Charcoal Text but slightly cooler. |
| Parchment | `#e9e4d9` | `--color-parchment` | Input field borders and light backgrounds — a warm, off-white neutral. |
| Stone Gray | `#b1afa7` | `--color-stone-gray` | Secondary text and borders — a mid-tone neutral, providing visual breathing room. |
| Order Now Gradient | `linear-gradient(rgb(148, 0, 255), rgb(92, 0, 255))` | `--color-order-now-gradient` | Specific call-to-action button background, adding a subtle depth to the dominant violet. |

## Tokens — Typography

### Roobert — Primary typeface for all content – headings, body, links, buttons. Its geometric, slightly condensed form, particularly at varied line heights and with a subtle negative letter spacing, contributes to the brand's distinctive, playful yet sharp voice. The use of a single font family simplifies the visual language. · `--font-roobert`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700, 800
- **Sizes:** 19px, 21px, 22px, 24px, 29px, 33px, 34px, 40px, 51px, 57px, 68px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 2.00
- **Letter spacing:** -0.0070em
- **Role:** Primary typeface for all content – headings, body, links, buttons. Its geometric, slightly condensed form, particularly at varied line heights and with a subtle negative letter spacing, contributes to the brand's distinctive, playful yet sharp voice. The use of a single font family simplifies the visual language.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 19px | 1.3 | -0.48px | `--text-body` |
| subheading | 21px | 1.2 | -0.48px | `--text-subheading` |
| heading | 29px | 1.2 | -0.48px | `--text-heading` |
| heading-lg | 40px | 1.1 | -0.48px | `--text-heading-lg` |
| display | 68px | 1 | -0.48px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 232 | 232px | `--spacing-232` |

### Border Radius

| Element | Value |
|---------|-------|
| nav | 21.945px |
| pill | 152.19px |
| cards | 0px |
| input | 6px |
| buttons | 6px |

### Layout

- **Section gap:** 68px
- **Card padding:** 0px
- **Element gap:** 3-19px

## Components

### Pill CTA Button (Violet Gradient)
**Role:** Primary call to action

Rounded pill shape with `Order Now Gradient` background, `Pure White` text, `Pure White` top border for highlight, and extreme `152.19px` border radius. Padding `5.073px` top, `15.219px` bottom, `25.365px` horizontal. Text `Roobert` weight `700`.

### Basic Button (White)
**Role:** Secondary action or general button

`Pure White` background with `Midnight Absolute` text, `Midnight Absolute` top border to define, `10px` border radius. Padding `10px` vertical, `15px` horizontal. Text `Roobert` weight `400`.

### Wait! Button (Playdate Yellow)
**Role:** Informational or subtle action button

`Playdate Yellow` background with `Charcoal Text`, `Charcoal Text` top border, `6px` border radius. Padding `4.275px` top, `7.125px` bottom, `28.5px` horizontal. Text `Roobert` weight `400`.

### Input Field
**Role:** User data entry

`Paper White` background with `Charcoal Text`, `Parchment` border, `6px` border radius. Padding `14.25px` all sides. Placeholder text is `Charcoal Text`.

### Feature Card (Image Grid)
**Role:** Displays game titles or features in a grid

Transparent background `rgba(0, 0, 0, 0)`, `0px` border radius, no shadow. Padding `0px`.

### Small Feature Card (Rounded Image Grid)
**Role:** Displays smaller game titles or features in a grid with subtle rounding

Transparent background `rgba(0, 0, 0, 0)`, `2.85px` border radius, no shadow. Padding `0px`.

### Navigation Link
**Role:** Top navigation item

Text in `Pure White` (unhovered) or `Crank Violet` (active/hovered), `Roobert` font, typically `19px` or `21px` weight `700` or `800`. Minimal padding `10px` horizontal.

## Do's and Don'ts

### Do
- Prioritize `Roobert` font for all text elements; variations in weight and size, not font family, should create hierarchy.
- Use `Playdate Yellow` (#ffc500) for section backgrounds and major highlights to emphasize key content.
- Employ `Crank Violet` (#7700ff) or its gradient variant for primary call-to-action buttons to ensure high visibility and playful urgency.
- Maintain high contrast pairings like `Charcoal Text` (#312f27) on `Pure White` (#ffffff) or `Playdate Yellow` for optimal readability.
- Apply `152.19px` radius for primary CTA buttons to achieve the signature pill shape; use `6px` for general buttons and input fields.
- Utilize `3px` and `11px` as the core `elementGap` values for consistent vertical rhythm and spacing between small elements.
- In sections with neutral backgrounds, use `Charcoal Text` (#312f27) for headings and `Pure White` (#ffffff) for subtle highlights on interactive elements.

### Don't
- Avoid introducing additional font families; `Roobert` is the sole typographic voice.
- Refrain from using complex `box-shadow` effects; the design relies on direct color blocking and shape for visual depth.
- Do not deviate from the core color palette; unexpected hues will clash with the brand's vivid but defined identity.
- Do not use generic button shapes; prefer `152.19px` (pill) or `6px` radius for specific button types.
- Avoid overly tight vertical spacing; ensure a `68px` `sectionGap` between major content blocks to provide breathing room.
- Do not use `Midnight Absolute` (#000000) for body text; reserve it for outlines, shadows, or very bold statements, preferring `Charcoal Text` (#312f27) for readability.

## Imagery

The site uses a mix of high-quality product photography (dominant), custom illustrations, and game screenshots. Product shots are typically clean, well-lit, and focus on the device itself against neutral or brand-colored backgrounds. The Playdate device is often rendered in 3D, showcasing its form and features, sometimes with a subtle shadow but no complex environment. Illustrations are stylized, often black-and-white or limited-palette, evoking a retro-console aesthetic for game previews. Game screenshots are presented as compact, self-contained units with a consistent border. The overall role is to showcase the product's unique design and the distinct visual style of its game library, rather than abstract concepts or lifestyle.

## Layout

The site uses a primarily full-bleed layout alternating with sections contained within a maximum width. The hero section is full-width with a dramatic, centrally placed 3D product render. Subsequent sections alternate between full-bleed `Playdate Yellow` background blocks and sections with `Default Gray` or `Charcoal Text` backgrounds that often contain text and image elements. Content is generally centered within its allocated width, with clear vertical spacing between major sections. A prominent 3-column game grid showcases visual content, with each item clearly isolated. Navigation features a sticky top bar, while the footer is a more traditional multi-column link structure.

## Agent Prompt Guide

Quick Color Reference:
- Text: #312f27
- Background (light): #ffffff
- Background (dark): #312f27
- CTA: #7700ff
- Accent: #ffc500
- Border: #e9e4d9

Example Component Prompts:
- Create a primary Call-to-Action button: 'Order now for $229.', using 'Order Now Gradient' for background, 'Pure White' for text, 'Pure White' top border, `152.19px` borderRadius, `Roobert` font weight `700`, padding `5.073px 25.365px 15.219px 25.365px`.
- Generate a section heading: 'The System.', using `Charcoal Text`, `Roobert` font, size `40px`, weight `800`, lineHeight `1.1`, letterSpacing `-0.0070em`.
- Design a text input field: 'Enter your email', with `Paper White` background, `Charcoal Text` placeholder, `Parchment` border, `6px` borderRadius, padding `14.25px` on all sides.
- Create a footer navigation link: 'Catalog', using `Pure White` text, `Roobert` font, size `19px`, weight `700`.
- Produce a game preview card: An image placeholder with 'Casual Birder' text, transparent background `rgba(0, 0, 0, 0)`, `2.85px` borderRadius, no boxShadow, and `0px` padding.

## Similar Brands

- **Teenage Engineering** — Shares a similar playful, minimalist hardware product aesthetic and bold, blocky typography.
- **Panic (parent company)** — Maintains design consistency with other Panic products, often featuring custom, unique typefaces and strong graphic identities.
- **Nintendo (classic era)** — Evokes a sense of retro-gaming nostalgia with bright colors and distinct hardware, reminiscent of classic handhelds.
- **Monzo Bank** — Uses a similar strategy of a signature bright accent color (hot coral) against a largely neutral background to create a distinct brand.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-playdate-yellow: #ffc500;
  --color-crank-violet: #7700ff;
  --color-seafoam-teal: #21c6a9;
  --color-deep-teal: #127866;
  --color-charcoal-text: #312f27;
  --color-pure-white: #ffffff;
  --color-midnight-absolute: #000000;
  --color-default-gray: #788086;
  --color-paper-white: #efefef;
  --color-ink-wash: #212223;
  --color-parchment: #e9e4d9;
  --color-stone-gray: #b1afa7;
  --color-order-now-gradient: #9400ff;
  --gradient-order-now-gradient: linear-gradient(rgb(148, 0, 255), rgb(92, 0, 255));

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 19px;
  --leading-body: 1.3;
  --tracking-body: -0.48px;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading: 29px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.48px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: -0.48px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-232: 232px;

  /* Layout */
  --section-gap: 68px;
  --card-padding: 0px;
  --element-gap: 3-19px;

  /* Border Radius */
  --radius-sm: 2.85px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 21.945px;
  --radius-3xl: 28.5px;
  --radius-3xl-2: 34.2px;
  --radius-3xl-3: 37.3065px;
  --radius-3xl-4: 39.9px;
  --radius-full: 152.19px;

  /* Named Radii */
  --radius-nav: 21.945px;
  --radius-pill: 152.19px;
  --radius-cards: 0px;
  --radius-input: 6px;
  --radius-buttons: 6px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-playdate-yellow: #ffc500;
  --color-crank-violet: #7700ff;
  --color-seafoam-teal: #21c6a9;
  --color-deep-teal: #127866;
  --color-charcoal-text: #312f27;
  --color-pure-white: #ffffff;
  --color-midnight-absolute: #000000;
  --color-default-gray: #788086;
  --color-paper-white: #efefef;
  --color-ink-wash: #212223;
  --color-parchment: #e9e4d9;
  --color-stone-gray: #b1afa7;
  --color-order-now-gradient: #9400ff;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 19px;
  --leading-body: 1.3;
  --tracking-body: -0.48px;
  --text-subheading: 21px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading: 29px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.48px;
  --text-display: 68px;
  --leading-display: 1;
  --tracking-display: -0.48px;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-232: 232px;

  /* Border Radius */
  --radius-sm: 2.85px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 21.945px;
  --radius-3xl: 28.5px;
  --radius-3xl-2: 34.2px;
  --radius-3xl-3: 37.3065px;
  --radius-3xl-4: 39.9px;
  --radius-full: 152.19px;
}
```
