# Dub — Style Reference
> Crisp Utility on White Canvas

**Theme:** light

Dub presents a high-contrast, functionally transparent productivity aesthetic. Surfaces range from pure white to subtle light grays, often paired with crisp dark text. Typography is precise and clear, with a prominent serif display font for impact and a neutral sans-serif for content. Accent colors appear as small functional highlights rather than large blocks, creating a dynamic yet understated feel. Components are lightweight, featuring soft border radii and minimal, diffused shadows, emphasizing content over heavy ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, form fills, primary button text for dark buttons |
| Jet Black | `#000000` | `--color-jet-black` | Icon fills, outlines for ghost buttons, decorative strokes to establish boundaries |
| Ink Black | `#0a0a0a` | `--color-ink-black` | Primary text color for headings, body text, and prominent links |
| Thunder Gray | `#171717` | `--color-thunder-gray` | Secondary text for informational blocks, subtle accents |
| Shadow Gray | `#262626` | `--color-shadow-gray` | Tertiary text, less prominent details, active ghost button text |
| Steel Gray | `#404040` | `--color-steel-gray` | Muted text, less emphasis on secondary elements |
| Subtle Ash | `#f5f5f5` | `--color-subtle-ash` | Subtle background for UI elements, hover states, secondary card surfaces |
| Border Light | `#e5e5e5` | `--color-border-light` | Hairline borders, dividers, subtle outlines for cards and inputs |
| Border Muted | `#d4d4d4` | `--color-border-muted` | Default input borders, inactive states |
| Accent Blue | `#3b82f6` | `--color-accent-blue` | Decorative icons, interactive elements, button background for a primary action |
| Fresh Green | `#16a34a` | `--color-fresh-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Warm Orange | `#ea580c` | `--color-warm-orange` | Highlight text, specific icon accents, informative badges |
| Deep Violet | `#7c3aed` | `--color-deep-violet` | Link highlights, decorative icons, secondary brand accents |
| System Info | `#111827` | `--color-system-info` | Secondary body text, navigation labels, and subdued headings |
| Focus Ring Blue | `#1e40af` | `--color-focus-ring-blue` | Primary action background, focus state indication |
| Highlight Green | `#4ade80` | `--color-highlight-green` | Background for specific callouts or positive elements |
| Highlight Violet | `#c084fc` | `--color-highlight-violet` | Background for specific callouts or visual accents |
| Highlight Orange | `#fb923c` | `--color-highlight-orange` | Background for specific callouts or visual accents |
| Linear Gray Dark | `linear-gradient(rgb(82, 82, 82), rgb(23, 23, 23))` | `--color-linear-gray-dark` | Darker shade for linear gradients, often in backgrounds or decorative elements |
| Linear Gray Light | `linear-gradient(rgb(115, 115, 115), rgb(38, 38, 38))` | `--color-linear-gray-light` | Lighter shade for linear gradients, often in backgrounds or decorative elements |

## Tokens — Typography

### Satoshi — Display headlines and prominent marketing text. The semi-bold weight and clean, geometric forms provide a modern, confident voice. · `--font-satoshi`
- **Substitute:** Montserrat
- **Weights:** 500
- **Sizes:** 36px, 40px, 48px
- **Line height:** 1.00, 1.11, 1.15
- **Letter spacing:** normal
- **Role:** Display headlines and prominent marketing text. The semi-bold weight and clean, geometric forms provide a modern, confident voice.

### Inter — The primary typeface for all UI elements, body text, navigation, and detailed information. Its legibility across various sizes ensures clarity in product contexts. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 8px, 10px, 11px, 12px, 13px, 14px, 16px, 18px, 20px, 24px, 30px
- **Line height:** 1.00, 1.33, 1.38, 1.40, 1.43, 1.50, 1.56, 2.15, 2.80
- **Letter spacing:** normal
- **Role:** The primary typeface for all UI elements, body text, navigation, and detailed information. Its legibility across various sizes ensures clarity in product contexts.

### GeistMono — Used for code snippets, data displays, and elements requiring a fixed-width, precise appearance, such as tracking IDs or numeric metrics. · `--font-geistmono`
- **Substitute:** Roboto Mono
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 24px
- **Line height:** 1.00, 1.33, 1.43
- **Letter spacing:** normal
- **Role:** Used for code snippets, data displays, and elements requiring a fixed-width, precise appearance, such as tracking IDs or numeric metrics.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | — | `--text-caption` |
| body | 14px | 1.43 | — | `--text-body` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading-sm | 24px | 1.33 | — | `--text-heading-sm` |
| heading | 30px | 1.33 | — | `--text-heading` |
| heading-lg | 36px | 1.11 | — | `--text-heading-lg` |
| display | 48px | 1.15 | — | `--text-display` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| lg | 12px |
| md | 8px |
| xl | 16px |
| xxl | 20px |
| full | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.2) 0px 2px 6px 0px inset` | `--shadow-sm-2` |
| subtle-2 | `rgba(0, 0, 0, 0.1) 0px 0px 0px 4px` | `--shadow-subtle-2` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| lg | `rgba(0, 0, 0, 0.09) 0px 20px 20px 0px` | `--shadow-lg` |
| subtle-3 | `rgb(255, 255, 255) 0px 0px 0px 3px, rgb(0, 0, 0) 0px 0px ...` | `--shadow-subtle-3` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action.

Background: Accent Blue (#3b82f6) or Focus Ring Blue (#1e40af), Text: Canvas White (#ffffff), Border Radius: 8px, Padding: 6px 12px.

### Ghost Button
**Role:** Interactive elements that blend into the background, typically for secondary actions.

Background: transparent (rgba(0,0,0,0)), Text: Ink Black (#0a0a0a) or Thunder Gray (#171717), Border: none, Border Radius: 9999px, Padding: 0px 16px.

### Outlined Card
**Role:** Informational containers with a subtle visual boundary.

Background: Canvas White (#ffffff), Border: 1px solid Border Light (#e5e5e5), Border Radius: 12px, Padding: 8px.

### Raised Card
**Role:** Elevated cards for prominent content or interactive sections.

Background: Canvas White (#ffffff), Border Radius: 16px, Shadow: rgba(0, 0, 0, 0.1) 0px 0px 0px 4px, Padding: 0px.

### Subtle Background Card
**Role:** Cards with a slightly off-white background, often used for grouped information or light contrast.

Background: Subtle Ash (#f5f5f5) or #dcfce7, Border Radius: 16px, Padding: 16px.

### Text Input
**Role:** Standard input fields for user data.

Background: Canvas White (#ffffff), Text: System Info (#111827), Border: 1px solid Border Muted (#d4d4d4) on top with clear bottom/sides, Border Radius: 0px 6px 6px 0px (asymmetric). Focus state uses a blue ring.

### Pill Tag
**Role:** Informative labels or categories.

Background: #dcfce7, Text: Fresh Green (#16a34a), Border Radius: 9999px, Padding: 6px 12px.

### Navigation Link
**Role:** Top-level navigation items.

Text: Ink Black (#0a0a0a), Hover: Underlined with Ink Black (#0a0a0a), Padding: 0px 24px.

### Featured Badge
**Role:** Small, colorful highlights for features or status.

Background: #fb923c, #c084fc, or #4ade80. Text: Ink Black (#0a0a0a) or similar dark neutral. Border radius: 9999px. Padding: dynamic based on content.

## Do's and Don'ts

### Do
- Use Satoshi (or Montserrat) at 48px, weight 500, line-height 1.15 for primary page headings.
- Apply Canvas White (#ffffff) for all main page and card backgrounds to maintain a bright, open feel.
- Employ Ink Black (#0a0a0a) for all primary body text, headings, and crucial interactive text for maximum readability.
- Utilize Border Light (#e5e5e5) for all hairline borders and subtle dividers to define content areas without adding visual weight.
- Apply a 9999px (full pill shape) border-radius to all ghost buttons and tags for a distinctive soft, approachable quality.
- Use Element Gap of 16px to separate most inline elements and Card Padding of 16px for content within containers.
- Employ Accent Blue (#3b82f6) or Focus Ring Blue (#1e40af) as the background for primary call-to-action buttons, with Canvas White (#ffffff) text.

### Don't
- Avoid using heavy drop shadows; prefer diffused, subtle shadows like rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.
- Do not deviate from Inter for body text, links, and most UI elements; consistency is key for readability and brand recognition.
- Refrain from using saturated colors as large background blocks; reserve them for small accents, highlights, or semantic indicators.
- Avoid tight line spacing for larger text; ensure line-heights are generous, especially for headings, to enhance scannability.
- Do not overcrowd sections; maintain a Section Gap of at least 64px to provide clear visual separation and breathing room.
- Do not use arbitrary border radii; adhere strictly to the defined scales: 9999px for pills, 8px for small components, 12px for cards, and 16px for larger containers.
- Do not introduce new typefaces; the combination of Satoshi (display), Inter (UI), and Geist Mono (monospace) is comprehensive.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background, base for most content sections. |
| 2 | Subtle Ash | `#f5f5f5` | Secondary background for cards, recessed sections, or hover states. |
| 3 | Info Tint | `#dcfce7` | Background for specific callouts, badges, or areas needing a subtle colored highlight. |

## Elevation

- **Button:** `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`
- **Card (General):** `rgba(0, 0, 0, 0.1) 0px 0px 0px 4px`
- **Dropdown/Menu:** `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px`

## Imagery

The visual language for imagery is primarily product-focused, featuring clean, cropped screenshots of the Dub UI. These screenshots often appear against a slightly muted background, sometimes with a soft blur or slight elevation. Icons are minimal, featuring outline styles with thin strokes in black or occasionally brand accent colors (green, orange, violet), serving as decorative or explanatory elements. There is a general absence of lifestyle photography or complex illustrations, keeping the focus squarely on the product's interface and functionality. Density is moderate, with images used to break up text blocks and demonstrate product features rather than purely decorative purposes.

## Layout

The page typically follows a max-width contained model, centered at around 1200px, creating a structured and professional feel. The hero section often presents a centered headline and subtext, followed by primary call-to-action buttons. Sections alternate between full-width content blocks and contained content, maintaining a rhythm of visual interest. Content arrangement leans towards alternating text-left/image-right compositions, or feature grids. There's a consistent vertical spacing between sections, primarily using a large section gap, creating a sense of spaciousness. Navigation is a sticky top bar with logo, main links, and distinct login/signup buttons.

## Agent Prompt Guide

Quick Color Reference:
- text: #0a0a0a
- background: #ffffff
- border: #e5e5e5
- accent: #3b82f6
- primary action: #000000 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a feature card: Background Canvas White (#ffffff), 12px radius, 1px solid Border Light (#e5e5e5). Title 'Advanced Analytics' at 20px Inter 600, Ink Black (#0a0a0a). Body text 'Gain deep insights into your link performance with real-time data.' at 14px Inter 400, Ink Black (#0a0a0a).

## Similar Brands

- **Vercel** — High-contrast light UI, emphasis on clear typography and functional accents, similar button styling and shadow usage.
- **Linear** — Clean, productivity-focused interface, subtle use of neutrals, and a distinct sans-serif for UI with a strong black/white contrast.
- **Framer** — Modern SaaS aesthetic with ample white space, precise typography, and a limited, purposeful accent color palette.
- **Notion** — Minimalist visual style, heavy reliance on grayscale tones for structure, and a highly legible sans-serif font for content focus.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-jet-black: #000000;
  --color-ink-black: #0a0a0a;
  --color-thunder-gray: #171717;
  --color-shadow-gray: #262626;
  --color-steel-gray: #404040;
  --color-subtle-ash: #f5f5f5;
  --color-border-light: #e5e5e5;
  --color-border-muted: #d4d4d4;
  --color-accent-blue: #3b82f6;
  --color-fresh-green: #16a34a;
  --color-warm-orange: #ea580c;
  --color-deep-violet: #7c3aed;
  --color-system-info: #111827;
  --color-focus-ring-blue: #1e40af;
  --color-highlight-green: #4ade80;
  --color-highlight-violet: #c084fc;
  --color-highlight-orange: #fb923c;
  --color-linear-gray-dark: #525252;
  --gradient-linear-gray-dark: linear-gradient(rgb(82, 82, 82), rgb(23, 23, 23));
  --color-linear-gray-light: #737373;
  --gradient-linear-gray-light: linear-gradient(rgb(115, 115, 115), rgb(38, 38, 38));

  /* Typography — Font Families */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 30px;
  --leading-heading: 1.33;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --text-display: 48px;
  --leading-display: 1.15;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-lg: 12px;
  --radius-md: 8px;
  --radius-xl: 16px;
  --radius-xxl: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-sm-2: rgba(0, 0, 0, 0.2) 0px 2px 6px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 0px 0px 4px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-lg: rgba(0, 0, 0, 0.09) 0px 20px 20px 0px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0px 0px 3px, rgb(0, 0, 0) 0px 0px 0px 4px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-subtle-ash: #f5f5f5;
  --surface-info-tint: #dcfce7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-jet-black: #000000;
  --color-ink-black: #0a0a0a;
  --color-thunder-gray: #171717;
  --color-shadow-gray: #262626;
  --color-steel-gray: #404040;
  --color-subtle-ash: #f5f5f5;
  --color-border-light: #e5e5e5;
  --color-border-muted: #d4d4d4;
  --color-accent-blue: #3b82f6;
  --color-fresh-green: #16a34a;
  --color-warm-orange: #ea580c;
  --color-deep-violet: #7c3aed;
  --color-system-info: #111827;
  --color-focus-ring-blue: #1e40af;
  --color-highlight-green: #4ade80;
  --color-highlight-violet: #c084fc;
  --color-highlight-orange: #fb923c;
  --color-linear-gray-dark: #525252;
  --color-linear-gray-light: #737373;

  /* Typography */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geistmono: 'GeistMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --text-body: 14px;
  --leading-body: 1.43;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.33;
  --text-heading: 30px;
  --leading-heading: 1.33;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.11;
  --text-display: 48px;
  --leading-display: 1.15;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-sm-2: rgba(0, 0, 0, 0.2) 0px 2px 6px 0px inset;
  --shadow-subtle-2: rgba(0, 0, 0, 0.1) 0px 0px 0px 4px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-lg: rgba(0, 0, 0, 0.09) 0px 20px 20px 0px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0px 0px 3px, rgb(0, 0, 0) 0px 0px 0px 4px;
}
```
