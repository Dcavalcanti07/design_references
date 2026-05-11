# ClickHouse — Style Reference
> Terminal Console with Chartreuse Zap — a focused dark UI with high-contrast, almost neon, interactive highlights.

**Theme:** dark

ClickHouse presents as a high-performance console, leveraging a deep, near-black backdrop and stark white typography for a focused, technical aesthetic. Signature is the 'Chartreuse Zap' yellow-green accent, appearing on interactive elements and key brand highlights, creating a vivid contrast that directs attention without overwhelming the UI. Rounded forms are used sparingly for interactive elements, while container cards maintain sharp corners, building a hierarchy of interaction against static information. The visual atmosphere is one of serious capability and precise feedback, like a terminal display offering critical insights.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Oil | `#151515` | `--color-midnight-oil` | Primary background, deep sections, text for dark contrast backgrounds. |
| Smokey Carbon | `#1f1f1c` | `--color-smokey-carbon` | Secondary background, card surfaces, form fields. |
| Deep Graphite | `#282828` | `--color-deep-graphite` | Tertiary background, subtle elevation on dark surfaces. |
| Iron Oxide | `#343434` | `--color-iron-oxide` | Divider lines, subtle borders on cards, slight background shifts. |
| Cool Stone | `#3a3a3a` | `--color-cool-stone` | Borders for cards and interactive component outlines. |
| Muted Ash | `#414141` | `--color-muted-ash` | Navigation backgrounds and elements, subtle interactive states. |
| Shadow White | `#a0a0a0` | `--color-shadow-white` | Secondary text, inactive states, icons. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Primary text, prominent icons. |
| Highlight Silver | `#dfdfdf` | `--color-highlight-silver` | Tertiary text, less prominent links and elements. |
| Silken Whisper | `#bcbcbb` | `--color-silken-whisper` | Navigation text, subtle body text. |
| Border Light | `#e5e7eb` | `--color-border-light` | Prominent borders, separators; provides a light contrast on dark backgrounds. |
| Chartreuse Zap | `#faff69` | `--color-chartreuse-zap` | Primary call-to-action buttons, active navigation indicators, key highlights — commands attention against the dark palette. |
| Veridian Stroke | `#4f5100` | `--color-veridian-stroke` | Hover states for primary CTAs, subtle interactive borders for focused elements. |
| Emerald Glint | `#fbff46` | `--color-emerald-glint` | Interactive element highlights, subtle glows, accent text. |
| Alert Red | `#ff7575` | `--color-alert-red` | Error states, warning indicators; a stark contrast to the primary green. |
| Halo Gradient | `linear-gradient(to right, rgba(0, 0, 0, 0), rgb(250, 255, 105), rgba(0, 0, 0, 0))` | `--color-halo-gradient` | Decorative element behind focal points, drawing attention with a soft, spreading light. |

## Tokens — Typography

### Inter — Primary typeface for all body text, navigation, buttons, and smaller headings. Its clarity at various sizes supports an information-dense UI. The -0.01em letter-spacing at larger sizes tightens display copy, enhancing its technical feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700, 900
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 72px, 96px
- **Line height:** 1.00, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56
- **Letter spacing:** -0.01em
- **Role:** Primary typeface for all body text, navigation, buttons, and smaller headings. Its clarity at various sizes supports an information-dense UI. The -0.01em letter-spacing at larger sizes tightens display copy, enhancing its technical feel.

### Basier — Captivating typeface for main headings, used sparingly to command attention. Its bold weight and distinct letterforms provide a strong visual anchor against the Inter body. Normal letter-spacing allows the unique character shapes to breathe. · `--font-basier`
- **Substitute:** system-ui, sans-serif
- **Weights:** 600
- **Sizes:** 20px, 24px, 36px
- **Line height:** 1.17, 1.30, 1.40
- **Role:** Captivating typeface for main headings, used sparingly to command attention. Its bold weight and distinct letterforms provide a strong visual anchor against the Inter body. Normal letter-spacing allows the unique character shapes to breathe.

### Inconsolata — Monospace typeface for code snippets and technical output, ensuring high readability for code-related content. Its fixed-width character design emphasizes precision. · `--font-inconsolata`
- **Substitute:** monospace
- **Weights:** 600
- **Sizes:** 16px
- **Line height:** 1.50
- **Role:** Monospace typeface for code snippets and technical output, ensuring high readability for code-related content. Its fixed-width character design emphasizes precision.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.1px | `--text-caption` |
| body-sm | 14px | 1.43 | 0.1px | `--text-body-sm` |
| body | 16px | 1.5 | 0.1px | `--text-body` |
| subheading | 18px | 1.4 | 0.1px | `--text-subheading` |
| heading-sm | 20px | 1.4 | 0.1px | `--text-heading-sm` |
| heading | 24px | 1.33 | 0.1px | `--text-heading` |
| heading-lg | 36px | 1.17 | — | `--text-heading-lg` |
| display | 72px | 1 | 0.1px | `--text-display` |
| display-lg | 96px | 1 | 0.1px | `--text-display-lg` |

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
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 4px |
| cards | 8px |
| buttons | 9999px |
| inputField | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| sm | `rgba(0, 0, 0, 0.06) 0px 4px 4px 0px, rgba(0, 0, 0, 0.14) ...` | `--shadow-sm` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action

backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderColor: #faff69, borderRadius: 9999px, padding: 8px 16px. Text uses Inter 400. The roundness combined with the vivid Chartreuse Zap border makes it highly interactive and noticeable.

### Secondary Outline Button
**Role:** Alternative actions

backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderColor: #e5e7eb, borderRadius: 9999px, padding: 8px 16px. Text uses Inter 400. Provides a less intrusive interactive option compared to the primary button due to its neutral border.

### Hero CTA Button
**Role:** Prominent hero section action

backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderColor: #faff69, borderRadius: 4px, padding: 0px 32px. Text uses Inter 400. While still Chartreuse-bordered, its rectangular shape signals a more direct, less playful action than the 9999px pill buttons.

### Plain Text Button
**Role:** Inline actions or minimal interaction

backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderColor: #e5e7eb, borderRadius: 0px, padding: 0px. Text uses Inter 400. Used for navigational links within content or less emphasized actions.

### Round Icon Button
**Role:** Small, interactive icons

backgroundColor: rgba(0, 0, 0, 0), color: #1f1f1c, borderColor: #e5e7eb, borderRadius: 9999px, padding: 2px. Text uses Inter 400 (though often icon-only). This is a specialized, smaller button for purely iconic interactions.

### Monochrome Card
**Role:** Content grouping, less emphasis

backgroundColor: rgba(0, 0, 0, 0), borderRadius: 0px, boxShadow: none, padding: 24px. Primarily used for groupings without a distinct background or elevation, relying on borders or negative space.

### FAQ Accordion Item
**Role:** Expandable content

backgroundColor: rgba(0,0,0,0), borderBottom: 1px solid #3a3a3a. Uses Inter 18px for question, #ffffff for heading, and #bcbcbb for number indicator. The subtle border and consistent typography maintain content flow within the FAQ section.

### Navigation Link
**Role:** Primary navigation elements

color: #bcbcbb for inactive, #faff69 for active/hover. Text uses Inter 500.

## Do's and Don'ts

### Do
- Do use Midnight Oil (#151515) as the default page background to maintain the dark, focused aesthetic.
- Do exclusively use Chartreuse Zap (#faff69) for primary call-to-action buttons and active navigation indicators.
- Do apply a 9999px radius to all interactive buttons and tags for a consistent 'pill' shape, indicating interactivity.
- Do use Inter for all body text and secondary headings, ensuring an -0.01em letter-spacing for large text (72px, 96px).
- Do reserve Basier 600 for prominent headlines (20px, 24px, 36px) to give them visual weight and distinctiveness without overt decoration.
- Do differentiate static content cards with an 8px border-radius and a subtle inset shadow from the background, using Smokey Carbon (#1f1f1c) as their background.
- Do use Inconsolata 600 at 16px for all code snippets and command-line instructions, wrapped in a Smokey Carbon (#1f1f1c) background.

### Don't
- Don't use any other color besides Chartreuse Zap (#faff69) for primary interactive elements; it dilutes the brand's primary accent.
- Don't use pronounced drop shadows for elevation; rely on subtle inset shadows or shifts in background color (e.g., from Midnight Oil to Smokey Carbon) to indicate depth.
- Don't clutter the layout with excessive imagery; when images are used, ensure they are high-contrast and relevant to the technical context.
- Don't introduce additional font families; restrict typography to Inter, Basier, and Inconsolata to maintain type harmony.
- Don't use large, rounded corners on static content cards; keep them at 8px to distinguish them from the pill-shaped buttons and ensure a structured feel.
- Don't use generic or abstract background patterns; stick to solid dark colors or subtle gradients like Halo Gradient where visual emphasis is needed.

## Imagery

The site uses a mix of icons and occasional abstract graphics. Icons are primarily outlined, thin-stroke, and monocolor (either Cloud White #ffffff or Chartreuse Zap #faff69), reinforcing the technical, precise aesthetic. There's a minimal use of product screenshots, favoring abstract, data-centric visualizations if present, often with a green or yellow glow consistent with the brand accent color. Photography is notably absent. The visual language focuses on UI cleanliness and symbolic representation over literal imagery, making the content and interactive elements the primary visual information. Density is image-light, text-dominant.

## Layout

The site uses a full-bleed page model with a consistent max-width content container within sections, centered horizontally. The hero section is full-bleed Midnight Oil with a large, centered headline and subtext, followed by two prominent CTA buttons. Section rhythm is primarily defined by consistent vertical spacing (sectionGap '40px') and a subtle alternation of background shades, though the base is always dark. Content arrangement frequently uses 2 to 4-column card grids for features and use cases. Text and visual elements (like icons or code blocks) are often aligned centrally or in clear, symmetrical pairs. The navigation is a sticky top bar with a left-aligned logo and right-aligned links and buttons, all against the dark primary background. The layout prioritizes clear information hierarchy and scannability within a structured, dark environment.

## Agent Prompt Guide

### Quick Color Reference
- Text (#ffffff)
- Background (#151515)
- CTA Primary (#faff69)
- Border (#e5e7eb)
- Card Background (#1f1f1c)
- Accent Hover (#4f5100)

### Example Component Prompts
1. Create a Primary Action Button: `backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderColor: #faff69, borderRadius: 9999px, padding: 8px 16px`. Text uses Inter 400. Label: 'Get Started'.
2. Create a Feature Card: `backgroundColor: rgba(20, 20, 20, 0.5), borderRadius: 8px, boxShadow: rgba(0, 0, 0, 0.06) 0px 4px 4px 0px, rgba(0, 0, 0, 0.14) 0px 4px 25px 0px inset, padding: 24px`. Headline uses Basier 600 at 24px, color #ffffff. Body text uses Inter 400 at 16px, color #a0a0a0.
3. Create a Code Snippet Block: `backgroundColor: #1f1f1c, color: #e5e7eb, padding: 16px 24px`. Text uses Inconsolata 600 at 16px, lineHeight 1.5. Content: `curl https://clickhouse.com/ | sh`.
4. Create a Hero Headline: `font-family: Basier, font-weight: 600, font-size: 72px, line-height: 1.00, color: #ffffff`. Text: 'The leading database for AI'.
5. Create a Secondary Outline Button: `backgroundColor: rgba(0, 0, 0, 0), color: #ffffff, borderColor: #e5e7eb, borderRadius: 9999px, padding: 8px 16px`. Text uses Inter 400. Label: 'Contact Sales'.

## Similar Brands

- **Vercel** — Shares a developer-centric aesthetic with a dark background, high-contrast text, and a single vibrant accent color for interactivity and brand recognition.
- **Linear** — Utilizes a minimalist dark interface with precise typography and subtle, functional pops of color to highlight interactions and status, focusing on efficiency.
- **Supabase** — Employs a dark, technical UI with monospace fonts for code and a distinct accent color (often green/purple) against the dark canvas for calls to action.
- **Tailwind CSS** — Features clean, structured layouts with a strong emphasis on readable typography and a generally dark theme offset by high-contrast elements, often with a subtle color accent.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-oil: #151515;
  --color-smokey-carbon: #1f1f1c;
  --color-deep-graphite: #282828;
  --color-iron-oxide: #343434;
  --color-cool-stone: #3a3a3a;
  --color-muted-ash: #414141;
  --color-shadow-white: #a0a0a0;
  --color-cloud-white: #ffffff;
  --color-highlight-silver: #dfdfdf;
  --color-silken-whisper: #bcbcbb;
  --color-border-light: #e5e7eb;
  --color-chartreuse-zap: #faff69;
  --color-veridian-stroke: #4f5100;
  --color-emerald-glint: #fbff46;
  --color-alert-red: #ff7575;
  --color-halo-gradient: #faff69;
  --gradient-halo-gradient: linear-gradient(to right, rgba(0, 0, 0, 0), rgb(250, 255, 105), rgba(0, 0, 0, 0));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basier: 'Basier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inconsolata: 'Inconsolata', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.1px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.1px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.1px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: 0.1px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: 0.1px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.17;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: 0.1px;
  --text-display-lg: 96px;
  --leading-display-lg: 1;
  --tracking-display-lg: 0.1px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 4px;
  --radius-cards: 8px;
  --radius-buttons: 9999px;
  --radius-inputfield: 4px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 4px 4px 0px, rgba(0, 0, 0, 0.14) 0px 4px 25px 0px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-oil: #151515;
  --color-smokey-carbon: #1f1f1c;
  --color-deep-graphite: #282828;
  --color-iron-oxide: #343434;
  --color-cool-stone: #3a3a3a;
  --color-muted-ash: #414141;
  --color-shadow-white: #a0a0a0;
  --color-cloud-white: #ffffff;
  --color-highlight-silver: #dfdfdf;
  --color-silken-whisper: #bcbcbb;
  --color-border-light: #e5e7eb;
  --color-chartreuse-zap: #faff69;
  --color-veridian-stroke: #4f5100;
  --color-emerald-glint: #fbff46;
  --color-alert-red: #ff7575;
  --color-halo-gradient: #faff69;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-basier: 'Basier', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inconsolata: 'Inconsolata', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.43;
  --tracking-body-sm: 0.1px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.1px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.1px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.4;
  --tracking-heading-sm: 0.1px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: 0.1px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.17;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: 0.1px;
  --text-display-lg: 96px;
  --leading-display-lg: 1;
  --tracking-display-lg: 0.1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-sm: rgba(0, 0, 0, 0.06) 0px 4px 4px 0px, rgba(0, 0, 0, 0.14) 0px 4px 25px 0px inset;
}
```
