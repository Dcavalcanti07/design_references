# fastht.ml — Style Reference
> Midnight dev playground

**Theme:** dark

FastHTML embraces a playful yet pragmatic developer tool aesthetic, combining a dark, sophisticated backdrop with vibrant, rounded 'blob' shapes that punctuate the UI with energy. Typography is crisp and minimal, providing clear information hierarchy. Component surfaces are often soft and pill-shaped, creating a friendly, approachable feel within the dark theme. The system uses a limited, high-contrast palette where color serves primarily as decorative accents or functional states, maintaining a sense of focused clarity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian Canvas | `#3a2234` | `--color-obsidian-canvas` | Hero background, base background for content sections with contrasting light foreground elements |
| Deep Aubergine | `#333333` | `--color-deep-aubergine` | Secondary surface for card backgrounds and elevated components, providing slight visual separation from the canvas |
| Charcoal Smoke | `#808080` | `--color-charcoal-smoke` | Subtle shadows and button focus rings |
| Bright White | `#ffffff` | `--color-bright-white` | Primary text, button text, and occasional full-fill button backgrounds |
| Ash Gray | `#f3f3f3` | `--color-ash-gray` | Soft section background, alternate surface, and quiet card fill. |
| Off-White Mist | `#e5e7eb` | `--color-off-white-mist` | Predominant border color for all UI elements, creating a subtle, consistent structure |
| Soft Stone | `#e8e8fc` | `--color-soft-stone` | Soft section background, alternate surface, and quiet card fill. |
| Muted Lavender | `#939eeb` | `--color-muted-lavender` | Secondary text for helper content, metadata, and link accents, offering a slightly softer contrast than white |
| Electric Green | `#3cdd8c` | `--color-electric-green` | Vivid accent for decorative shapes, icons, and card backgrounds. Signals energy and positivity |
| Goldenrod Pop | `#ffc435` | `--color-goldenrod-pop` | Vivid accent for decorative shapes, icons, and card backgrounds. Adds a warm, energetic punctuation |
| Bubblegum Pink | `#e699d9` | `--color-bubblegum-pink` | Vivid accent for decorative shapes, icons, and card backgrounds. Conveys playfulness |
| Lilac Jelly | `#7575f0` | `--color-lilac-jelly` | Vivid accent for decorative shapes, icons, and card backgrounds, similar in hue to Muted Lavender but more saturated |
| Mint Cream | `#d4f7e6` | `--color-mint-cream` | Background for lighter-toned cards, a very pale greenish tint |
| Fairy Floss | `#ffccf7` | `--color-fairy-floss` | Background for lighter-toned cards, a very pale pinkish tint |
| Butter Cream | `#ffeecc` | `--color-butter-cream` | Background for lighter-toned cards, a very pale yellowish tint |
| Soft Mauve | `#eddee9` | `--color-soft-mauve` | Background for lighter-toned cards, a very pale purplish tint |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Filled button backgrounds, body text on light backgrounds, icon fills |
| Cloud Gray | `#cccccc` | `--color-cloud-gray` | Subtle secondary text, navigation links, and inactive UI elements providing less contrast than Bright White |
| Dark Silver | `#999999` | `--color-dark-silver` | Background for tabs or inactive buttons |

## Tokens — Typography

### Geist — Primary typeface for all headings, body text, UI labels, and links. Its slightly condensed forms maintain density and clarity. · `--font-geist`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 16px, 20px, 24px, 32px, 60px, 72px
- **Line height:** 1.10, 1.22, 1.25, 1.33, 1.40, 1.50
- **Letter spacing:** -0.24px at 16px, -0.3px at 20px, -0.24px at 24px, -0.32px at 32px, -0.6px at 60px, -0.72px at 72px
- **OpenType features:** `'clig' off, 'liga' off`
- **Role:** Primary typeface for all headings, body text, UI labels, and links. Its slightly condensed forms maintain density and clarity.

### Geist Mono — Used for code snippets, technical details, and table content, providing alignment and clear distinction from proportional text. · `--font-geist-mono`
- **Substitute:** SF Mono
- **Weights:** 500
- **Sizes:** 14px, 16px
- **Line height:** 1.80
- **Letter spacing:** normal
- **OpenType features:** `'clig' off, 'liga' off`
- **Role:** Used for code snippets, technical details, and table content, providing alignment and clear distinction from proportional text.

### Arial Black — Auxiliary display text for specific expressive moments, offering strong visual contrast to Geist. · `--font-arial-black`
- **Substitute:** Impact
- **Weights:** 400, 700
- **Sizes:** 16px, 20px
- **Line height:** 1.50
- **Letter spacing:** normal
- **OpenType features:** `'clig' off, 'liga' off`
- **Role:** Auxiliary display text for specific expressive moments, offering strong visual contrast to Geist.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.8 | — | `--text-caption` |
| body-sm | 16px | 1.5 | -0.24px | `--text-body-sm` |
| body | 20px | 1.25 | -0.3px | `--text-body` |
| subheading | 24px | 1.25 | -0.24px | `--text-subheading` |
| heading | 32px | 1.33 | -0.32px | `--text-heading` |
| heading-lg | 60px | 1.1 | -0.6px | `--text-heading-lg` |
| display | 72px | 1.1 | -0.72px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| tabs | 1000px |
| cards | 24px |
| buttons | 9999px |
| accentShapes | 20px, 24px, 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.5) 0px 2px 2px 0px, rgba(0, 0, 0, 0...` | `--shadow-subtle` |
| sm | `rgba(255, 255, 255, 0.1) 0px 2px 4px 0px inset, rgba(0, 0...` | `--shadow-sm` |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 8px

## Components

### Pill Button - Transparent
**Role:** Secondary action button, typically for 'Read docs' or similar navigation.

Nearly transparent background `rgba(255, 255, 255, 0.6)`, text `rgba(0, 0, 0, 0.8)`, `1px` border of `Off-White Mist`, `9999px` radius. Padding `8px` vertical, `16px` horizontal.

### Pill Button - Filled
**Role:** Primary action button, often for 'Learn more' or calls to action.

Solid `Midnight Ink` background, `Bright White` text, `1px` border of `Off-White Mist`, `9999px` radius. Padding `4px` vertical, `16px` horizontal.

### Pill Button - Light
**Role:** Interactive elements within specific modules, like 'Watch intro'.

Solid `Bright White` background, `rgba(0, 0, 0, 0.8)` text, `1px` border of `Off-White Mist`, `9999px` radius. Padding `8px` vertical, `8px` horizontal.

### Text Link Button (Ghost)
**Role:** Minimal interactive elements where focus is on text and not a prominent button shape.

Transparent background, `rgba(255, 255, 255, 0.8)` text, no border or radius. No explicit padding.

### Decorative Accent Card
**Role:** Large, irregularly shaped background elements used for visual interest rather than content containment.

Solid background of `Bubblegum Pink`, `Goldenrod Pop`, `Electric Green`, or `Lilac Jelly`. Radius `24px` or `16px` or `20px` or `40px`. No shadows. Padding `32px` or `48px`.

### Informational Card (Elevated)
**Role:** Content container for code samples or distinct feature blocks, providing visual lift.

Background `Soft Stone`, `20px` radius. Features an inset shadow `rgba(255, 255, 255, 0.1) 0px 2px 4px 0px` and a subtly cast shadow `rgba(0, 0, 0, 0.5) 0px 4px 8px 0px`.

### FAQ Accordion Item
**Role:** Interactive content accordion for questions and answers.

Background `Soft Stone` with a `20px` radius. Includes a subtle box shadow. Text color `Midnight Ink` and `Muted Lavender`.

## Do's and Don'ts

### Do
- Prioritize `Obsidian Canvas` and `Deep Aubergine` for backgrounds, using `Bright White` for primary text and `Muted Lavender` for secondary content.
- Use `Geist` for all primary text elements, and `Geist Mono` for code blocks and technical details.
- Apply `9999px` border-radius for all interactive buttons and small tags; use `24px` for main content cards and `20px` for elevated UI elements.
- Employ `Electric Green`, `Goldenrod Pop`, `Bubblegum Pink`, and `Lilac Jelly` judiciously for decorative 'blob' shapes and active state indicators, never as primary text or background for large content areas.
- Maintain a clear `8px` element gap between inline elements and a `32px` padding for card content, with `64px` vertical spacing between major sections.
- Use `Off-White Mist` as the consistent `1px` border for all UI components, including buttons, cards, and input fields.
- Apply the specific `rgba(255, 255, 255, 0.1) 0px 2px 4px 0px inset, rgba(0, 0, 0, 0.5) 0px 4px 8px 0px` shadow for elevated components like the `Informational Card`.

### Don't
- Avoid using `Electric Green`, `Goldenrod Pop`, `Bubblegum Pink`, or `Lilac Jelly` for large background areas or extensive body text; their role is purely accentual.
- Do not introduce sharp corners or low radii on interactive elements; `9999px` and `24px` are the primary radii.
- Refrain from using `Arial Black` for body text or general UI labels; reserve it for specific, high-impact display text only.
- Do not use generic gray values for text or borders when `Muted Lavender`, `Cloud Gray`, `Bright White`, or `Off-White Mist` are available and semantically appropriate.
- Avoid arbitrary changes in line-height or letter-spacing; adhere to the defined `Geist` and `Geist Mono` typography profiles.
- Do not use shadows indiscriminately; reserve them for interactive elements and designated elevated cards to maintain a clean aesthetic.
- Avoid cluttering the layout; maintain generous `64px` vertical section spacing and focus on clear, distinct component separation.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Obsidian Canvas | `#3a2234` | Primary page background, especially for hero sections. |
| 1 | Deep Aubergine | `#333333` | General content section backgrounds, providing a subtle shift from the canvas. |
| 2 | Soft Stone | `#e8e8fc` | Elevated cards and interactive components, with a slight tint away from pure white. |
| 3 | Ash Gray | `#f3f3f3` | Lightest surface for specific cards and decorative fills, providing maximum contrast on a dark background. |

## Elevation

- **Informational Card:** `rgba(255, 255, 255, 0.1) 0px 2px 4px 0px inset, rgba(0, 0, 0, 0.5) 0px 4px 8px 0px`
- **Pill Buttons:** `rgba(255, 255, 255, 0.5) 0px 2px 2px 0px, rgba(0, 0, 0, 0.2) 0px 3px 3px 0px`
- **FAQ Accordion Item:** `rgba(255, 255, 255, 0.5) 0px 2px 2px 0px, rgba(0, 0, 0, 0.2) 0px 3px 3px 0px`

## Imagery

The site uses abstract, geometric 'blob' illustrations in vibrant accent colors (`Electric Green`, `Goldenrod Pop`, `Bubblegum Pink`, `Lilac Jelly`) to add visual interest and a playful mood, often overlaid on hero sections or serving as background elements. Photography is minimal, appearing as small, circular profile pictures in social proof or inline video previews. Icons are typically filled, monochrome, and used functionally. Imagery density is low, with visuals serving primarily as decorative accents or concise product representations rather than extensive content. Product screenshots like code examples use the `Geist Mono` font and a simple, contained visual style.

## Layout

Pages use a full-bleed layout alternating darker `Obsidian Canvas` or `Deep Aubergine` sections with lighter `Soft Stone` elements. The hero section features a centered headline over a dark background, often with large, overlapping abstract shapes. Section rhythm is dictated by generous vertical spacing of `64px`. Content within sections is primarily organized in vertical stacks, often with `24px` gaps between elements. Feature sections frequently employ multi-column arrangements like a two-column text-left/image-right pattern or specific `Informational Cards`. Navigation is a sticky top bar with minimal links and calls to action.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #3a2234
border: #e5e7eb
accent: #939eeb
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a hero section: `Obsidian Canvas` background. Headline 'Modern web applications' in `Geist` font, 72px size, 1.1 lineHeight, -0.72px letterSpacing, `Bright White` color. Body text 'Built on solid web foundations...' in `Geist` font, 20px size, 1.25 lineHeight, -0.3px letterSpacing, `Muted Lavender` color. Include a `Pill Button - Filled` for 'Learn more' and a `Pill Button - Light` for 'Watch intro'.
2. Create an `Informational Card` showing a code snippet: `Soft Stone` background, `20px` radius, `rgba(255, 255, 255, 0.1) 0px 2px 4px 0px inset, rgba(0, 0, 0, 0.5) 0px 4px 8px 0px` shadow. Code uses `Geist Mono` font, 16px size, `Bright White` color. External `Midnight Ink` title using `Geist`, 24px size, 1.25 lineHeight, -0.24px letterSpacing.
3. Create an `FAQ Accordion Item`: `Soft Stone` background, `20px` radius. Question text in `Geist` font, 20px size, `Midnight Ink` color. Answer text in `Geist` font, 16px size, `Muted Lavender` color. Ensure `1px Off-White Mist` border and `8px` element gaps for internal spacing.

## Similar Brands

- **Vercel** — Similar dark-theme developer tool aesthetic with clean typography and soft, rounded elements.
- **Tailwind UI** — Modern SaaS/dev tool styling with strong emphasis on component-driven design, subtle shadows, and crisp typography.
- **Linear** — Monochromatic dark mode with restrained use of accent colors for functional elements, sharp typography, and low-prominence borders.
- **Supabase** — Playful, energetic visual elements (blobs, vivid accents) combined with a dark UI for a developer audience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian-canvas: #3a2234;
  --color-deep-aubergine: #333333;
  --color-charcoal-smoke: #808080;
  --color-bright-white: #ffffff;
  --color-ash-gray: #f3f3f3;
  --color-off-white-mist: #e5e7eb;
  --color-soft-stone: #e8e8fc;
  --color-muted-lavender: #939eeb;
  --color-electric-green: #3cdd8c;
  --color-goldenrod-pop: #ffc435;
  --color-bubblegum-pink: #e699d9;
  --color-lilac-jelly: #7575f0;
  --color-mint-cream: #d4f7e6;
  --color-fairy-floss: #ffccf7;
  --color-butter-cream: #ffeecc;
  --color-soft-mauve: #eddee9;
  --color-midnight-ink: #000000;
  --color-cloud-gray: #cccccc;
  --color-dark-silver: #999999;

  /* Typography — Font Families */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial-black: 'Arial Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.8;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.24px;
  --text-body: 20px;
  --leading-body: 1.25;
  --tracking-body: -0.3px;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.33;
  --tracking-heading: -0.32px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.6px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -0.72px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 1000px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-tabs: 1000px;
  --radius-cards: 24px;
  --radius-buttons: 9999px;
  --radius-accentshapes: 20px, 24px, 40px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.5) 0px 2px 2px 0px, rgba(0, 0, 0, 0.2) 0px 3px 3px 0px;
  --shadow-sm: rgba(255, 255, 255, 0.1) 0px 2px 4px 0px inset, rgba(0, 0, 0, 0.5) 0px 4px 8px 0px;

  /* Surfaces */
  --surface-obsidian-canvas: #3a2234;
  --surface-deep-aubergine: #333333;
  --surface-soft-stone: #e8e8fc;
  --surface-ash-gray: #f3f3f3;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian-canvas: #3a2234;
  --color-deep-aubergine: #333333;
  --color-charcoal-smoke: #808080;
  --color-bright-white: #ffffff;
  --color-ash-gray: #f3f3f3;
  --color-off-white-mist: #e5e7eb;
  --color-soft-stone: #e8e8fc;
  --color-muted-lavender: #939eeb;
  --color-electric-green: #3cdd8c;
  --color-goldenrod-pop: #ffc435;
  --color-bubblegum-pink: #e699d9;
  --color-lilac-jelly: #7575f0;
  --color-mint-cream: #d4f7e6;
  --color-fairy-floss: #ffccf7;
  --color-butter-cream: #ffeecc;
  --color-soft-mauve: #eddee9;
  --color-midnight-ink: #000000;
  --color-cloud-gray: #cccccc;
  --color-dark-silver: #999999;

  /* Typography */
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial-black: 'Arial Black', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.8;
  --text-body-sm: 16px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.24px;
  --text-body: 20px;
  --leading-body: 1.25;
  --tracking-body: -0.3px;
  --text-subheading: 24px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.24px;
  --text-heading: 32px;
  --leading-heading: 1.33;
  --tracking-heading: -0.32px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.6px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -0.72px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 1000px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.5) 0px 2px 2px 0px, rgba(0, 0, 0, 0.2) 0px 3px 3px 0px;
  --shadow-sm: rgba(255, 255, 255, 0.1) 0px 2px 4px 0px inset, rgba(0, 0, 0, 0.5) 0px 4px 8px 0px;
}
```
