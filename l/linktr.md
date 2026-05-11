# Linktr — Style Reference
> Vibrant digital playground: link in bio as a personal, colorful hub

**Theme:** light

Linktree presents a playful, high-energy digital identity built on vibrant, contrasting color blocks and rounded, organic shapes. The design emphasizes clear calls to action and distinct content zones through a dynamic interplay of saturated hues. Typography is primarily functional, leaning into a friendly, approachable tone with varying weights and subtle tracking adjustments to maintain a conversational cadence. Components are often expressed with maximal border-radii, contributing to an overall soft, engaging user experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Green | `#254f1a` | `--color-forest-green` | Decorative card backgrounds, accent text on light backgrounds — conveys growth and natural energy |
| Chartreuse Pop | `#d2e823` | `--color-chartreuse-pop` | Primary action button backgrounds, highlighted card accents, energetic background fill. This vivid lime serves as the main interactive accent |
| Hydrangea Blue | `#2665d6` | `--color-hydrangea-blue` | Hero section backgrounds, prominent links, accent for specific UI elements — a complementary, strong color that frames content |
| Dahlia Purple | `#502274` | `--color-dahlia-purple` | Decorative background sections, signaling depth and richness |
| Currant Red | `#780016` | `--color-currant-red` | Decorative card backgrounds, strong accent where high contrast and intensity are desired |
| Lavender Mist | `#e9c0e9` | `--color-lavender-mist` | Elevated card backgrounds, soft button fills, decorative section backgrounds |
| Iris Blue | `#061492` | `--color-iris-blue` | Button backgrounds, card backgrounds, a profound, darker blue for functional elements |
| Goldenrod | `#d6a337` | `--color-goldenrod` | Distinct card backgrounds for callouts or special features |
| Graphite | `#1e2330` | `--color-graphite` | Primary body text, headers, neutral button backgrounds, prominent borders — the core dark text color |
| White | `#ffffff` | `--color-white` | Component backgrounds, form fields, text on dark backgrounds, icon fills |
| Marble | `#f3f3f1` | `--color-marble` | Page background, container backgrounds — the base canvas of the application |
| Lunar Dust | `#e8efd6` | `--color-lunar-dust` | Subtle background surfaces, slight variation on the main canvas |
| Slate Gray | `#676b5f` | `--color-slate-gray` | Muted text, secondary links, subtle borders |
| Whisper Gray | `#adadad` | `--color-whisper-gray` | Card backgrounds, placeholder text |
| Text Gray | `#757575` | `--color-text-gray` | Placeholder text in input fields |
| Black | `#000000` | `--color-black` | Dominant text color, borders, icon fills, utility elements |

## Tokens — Typography

### Arial — Fallback for general body text and default page elements, providing a robust system font base. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Fallback for general body text and default page elements, providing a robust system font base.

### Linksans Linksansvf — Primary brand typeface for headings, interactive elements, and key informational text. Its variable font nature allows for precise weight control, contributing to distinct visual hierarchy. · `--font-linksans-linksansvf`
- **Substitute:** Inter
- **Weights:** 400, 500, 700, 800
- **Sizes:** 14px, 16px, 18px, 24px, 28px, 56px, 80px
- **Line height:** 1.00, 1.06, 1.07, 1.20, 1.30, 1.50
- **Letter spacing:** -0.0200em at 80px, -0.0100em at 56px, 0.0100em at 14px
- **Role:** Primary brand typeface for headings, interactive elements, and key informational text. Its variable font nature allows for precise weight control, contributing to distinct visual hierarchy.

### Linksans — Supporting brand typeface for navigation, labels, and smaller details, reinforcing the primary Linksans aesthetic with slightly tighter tracking on larger sizes. · `--font-linksans`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 13px, 14px, 15px, 20px, 24px, 25px, 51px
- **Line height:** 1.06, 1.20, 1.31, 1.50, 2.32
- **Letter spacing:** -0.0430em at 51px, -0.0240em at 25px, -0.0200em at 24px, -0.0130em at 15px
- **Role:** Supporting brand typeface for navigation, labels, and smaller details, reinforcing the primary Linksans aesthetic with slightly tighter tracking on larger sizes.

### yerk — yerk — detected in extracted data but not described by AI · `--font-yerk`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.5
- **Role:** yerk — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | 0.1px | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 24px | 1.3 | — | `--text-subheading` |
| heading-sm | 28px | 1.2 | — | `--text-heading-sm` |
| heading | 56px | 1.07 | -0.56px | `--text-heading` |
| display | 80px | 1 | -1.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 65 | 65px | `--spacing-65` |
| 128 | 128px | `--spacing-128` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 64px |
| inputs | 8px |
| buttons | 99px |
| pillForms | 99px |
| accentBlobs | 1000px |

### Layout

- **Page max-width:** 1504px
- **Section gap:** 48px
- **Card padding:** 16px
- **Element gap:** 10px

## Components

### Primary Action Button
**Role:** Main call-to-action button, highly visible.

Background: Chartreuse Pop (#d2e823). Text: Graphite (#1e2330). Border Radius: 99px. Padding: 20px vertical, 26px horizontal. Font: Linksans Linksansvf, 16px, weight 500.

### Navigation Link Button
**Role:** Transparent button for navigation items.

Background: transparent. Text: Black (#000000). No border. No explicit padding, implied by content.

### Input Field
**Role:** Standard input for user data entry.

Background: White (#ffffff). Text: Gray Text (#757575). Border: 1px solid Black (#000000). Border Radius: 8px. Padding: 8px vertical, 16px horizontal.

### Tertiary Ghost Button
**Role:** Alternative action button with minimal visual hierarchy.

Background: Marble (#f3f3f1). Text: Graphite (#1e2330). Border: 1px solid Graphite (#1e2330). Border Radius: 8px. Padding: 22px vertical, 26px horizontal.

### Pill Accent Button
**Role:** Decorative button with high curvature for specific actions.

Background: Lavender Mist (#e9c0e9). Text: Black (#000000). Border: 1px solid Black (#000000). Border Radius: 99px. Padding: 20px vertical, 26px horizontal.

### Default Card
**Role:** Standard container for content.

Background: transparent. Border Radius: 0px. No shadow. Padding: 0px.

### Elevated Content Card
**Role:** Card with subtle elevation and rounded corners.

Background: rgba(0, 0, 0, 0.32). Border Radius: 32px. No explicit shadow, the background tint provides a sense of depth.

### Feature Highlight Card
**Role:** Cards designed to stand out with bold colors and maximal rounding.

Background: Goldenrod (#d6a337), Iris Blue (#061492), Forest Green (#254f1a), or Lavender Mist (#e9c0e9). Border Radius: 64px or 1000px. No shadow.

## Do's and Don'ts

### Do
- Prioritize Chartreuse Pop (#d2e823) for all primary calls to action, ensuring it is the brightest element on the screen.
- Utilize 99px border-radius generously for all buttons and rounded interactive elements, for a soft, friendly feel.
- Employ the full spectrum of brand colors (Hydrangea Blue, Dahlia Purple, Currant Red, etc.) for distinct section backgrounds and decorative panels.
- Maintain high visual contrast for text elements, preferring Graphite (#1e2330) on light backgrounds and White (#ffffff) on saturated or dark backgrounds.
- Apply Linksans Linksansvf or Linksans for all headings and key UI text, adjusting letter-spacing according to the type scale for subtle refinement.
- Use Marble (#f3f3f1) as the default page canvas, creating a consistent light foundation.
- Structure layouts with a 1504px max-width, centering content horizontally for coherence.

### Don't
- Avoid using flat, desaturated background colors for major sections; Linktree's identity relies on vibrant, distinct color blocks.
- Do not use sharp 0px corners for interactive elements or containers; leverage the specified border radii to maintain the organic, friendly aesthetic.
- Refrain from introducing system default shadows; Linktree uses tinted backgrounds and color blocks to create visual depth instead of drop shadows.
- Do not rely solely on neutral colors for visual hierarchy; use brand colors as primary indicators for interaction and distinction.
- Do not use generic, default system fonts for headings or prominent text; always use Linksans or Linksans Linksansvf to uphold brand typography.
- Avoid tight element spacing; ensure at least 10px element gaps and 16px card padding for a comfortable density.
- Do not apply excessive letter spacing to body text; maintain normal tracking for readability, using negative tracking points only for display headings.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Marble | `#f3f3f1` | Base page background or canvas. |
| 1 | Lunar Dust | `#e8efd6` | Slightly elevated background surface for sections or larger content blocks. |
| 2 | White | `#ffffff` | Card and input field backgrounds, primary interactive surfaces. |
| 3 | Tinted Overlay | `#00000052` | Elevated content cards, creating a sense of depth without traditional shadows. |

## Imagery

Linktree's imagery palette is a mix of product-in-use photography and abstract, organic shapes. Photography features diverse individuals or product shots, often with a vibrant, playful filter or color overlay, integrated into color-blocked sections rather than being full-bleed. Illustrations are minimal, generally functional icons or simple, bold shapes rather than complex scenes. The emphasis is on product showcase and community representation, with a high density of visual elements carefully choreographed within the colorful blocks. Icons are typically filled and monochromatic in either black or white, varying based on background contrast.

## Layout

The page maintains a centered, contained layout with a maximum width of 1504px. Heroes often feature full-width color backgrounds (e.g., Hydrangea Blue or Chartreuse Pop) with centrally aligned headline text. Sections are distinct, often using alternating vibrant color blocks to break vertical rhythm rather than subtle dividers. Content is arranged in alternating text-left/image-right patterns or centered stacks for feature descriptions. Card grids are prevalent, showcasing features or examples within the highly rounded feature highlight cards. The navigation is a sticky top bar with prominent 'Log in' and 'Sign up free' buttons, maintaining a tight, accessible structure.

## Agent Prompt Guide

Quick Color Reference:
- text: #000000
- background: #f3f3f1
- border: #000000
- accent: #2665d6
- primary action: #d2e823 (filled action)

Example Component Prompts:
- Create a Primary Action Button: #d2e823 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
- Create a feature card: Forest Green (#254f1a) background, 64px border radius. Title 'Unlimited Links' in Linksans, 24px, weight 700, #ffffff. Description 'Add as many links as you need, no limits.' in Arial, 16px, weight 400, #ffffff. Padding: 16px.
- Create an input field: White (#ffffff) background, 1px solid Black (#000000) border, 8px border radius. Placeholder text 'Your Linktree username' in Text Gray (#757575), 16px. Padding: 8px vertical, 16px horizontal.
- Create a navigation link: Black (#000000) text (Arial, 16px, weight 400). No background or border. On hover, change text color to Hydrangea Blue (#2665d6).

## Similar Brands

- **Bento.me** — Shares the 'link in bio' product category and uses a similar vibrant, blocky, and highly customizable personal branding aesthetic.
- **Canva** — Employs a wide range of saturated, joyful colors and aims for an approachable, user-friendly interface for creatives, similar to Linktree's energetic feel.
- **Figma** — Features a playful, modular UI with good use of vibrant brand colors as accents against primarily neutral backgrounds, and a focus on soft, rounded interface elements.
- **VSCO** — Although different product, has a distinct minimalist aesthetic with emphasis on visual content and a clean, direct approach to UI that Linktree shares, but with more color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-green: #254f1a;
  --color-chartreuse-pop: #d2e823;
  --color-hydrangea-blue: #2665d6;
  --color-dahlia-purple: #502274;
  --color-currant-red: #780016;
  --color-lavender-mist: #e9c0e9;
  --color-iris-blue: #061492;
  --color-goldenrod: #d6a337;
  --color-graphite: #1e2330;
  --color-white: #ffffff;
  --color-marble: #f3f3f1;
  --color-lunar-dust: #e8efd6;
  --color-slate-gray: #676b5f;
  --color-whisper-gray: #adadad;
  --color-text-gray: #757575;
  --color-black: #000000;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans-linksansvf: 'Linksans Linksansvf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans: 'Linksans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-yerk: 'yerk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.1px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --text-heading: 56px;
  --leading-heading: 1.07;
  --tracking-heading: -0.56px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-65: 65px;
  --spacing-128: 128px;
  --spacing-216: 216px;

  /* Layout */
  --page-max-width: 1504px;
  --section-gap: 48px;
  --card-padding: 16px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 29.09px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 41.6px;
  --radius-full: 64px;
  --radius-full-2: 99px;
  --radius-full-3: 1000px;

  /* Named Radii */
  --radius-cards: 64px;
  --radius-inputs: 8px;
  --radius-buttons: 99px;
  --radius-pillforms: 99px;
  --radius-accentblobs: 1000px;

  /* Surfaces */
  --surface-marble: #f3f3f1;
  --surface-lunar-dust: #e8efd6;
  --surface-white: #ffffff;
  --surface-tinted-overlay: #00000052;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-green: #254f1a;
  --color-chartreuse-pop: #d2e823;
  --color-hydrangea-blue: #2665d6;
  --color-dahlia-purple: #502274;
  --color-currant-red: #780016;
  --color-lavender-mist: #e9c0e9;
  --color-iris-blue: #061492;
  --color-goldenrod: #d6a337;
  --color-graphite: #1e2330;
  --color-white: #ffffff;
  --color-marble: #f3f3f1;
  --color-lunar-dust: #e8efd6;
  --color-slate-gray: #676b5f;
  --color-whisper-gray: #adadad;
  --color-text-gray: #757575;
  --color-black: #000000;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans-linksansvf: 'Linksans Linksansvf', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-linksans: 'Linksans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-yerk: 'yerk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 0.1px;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 24px;
  --leading-subheading: 1.3;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --text-heading: 56px;
  --leading-heading: 1.07;
  --tracking-heading: -0.56px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -1.6px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-65: 65px;
  --spacing-128: 128px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 29.09px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 41.6px;
  --radius-full: 64px;
  --radius-full-2: 99px;
  --radius-full-3: 1000px;
}
```
