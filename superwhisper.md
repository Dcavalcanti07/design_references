# Superwhisper — Style Reference
> Celestial Command Center: A dark, gradient-infused UI where sharp, functional elements glow with purpose against an expansive, cosmic void.

**Theme:** dark

This design system evokes a 'celestial command center' feel, achieved through deep, gradient-rich dark backgrounds and high-contrast white typography. Vivid, almost neon-like accent colors emerge sparingly against the darkness, providing critical points of focus and interactivity. The primary visual tension arises from the interplay of vast, ethereal gradients and sharp, contained UI elements with precise 9px rounded corners and optional pill shapes for actions.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Eclipse | `#000000` | `--color-midnight-eclipse` | Page background, primary surface for elevated components, core text color for light UI elements. The canvas upon which all other elements are built. |
| Starless Night | `#030719` | `--color-starless-night` | Secondary surface background, subtly darker than Midnight Eclipse, providing a slight depth for cards and sections. |
| Twilight Ink | `#1C1D1F` | `--color-twilight-ink` | Muted text, subtle icons, border color for low-contrast elements. |
| Ghostly Gray | `#E5E7EB` | `--color-ghostly-gray` | High-contrast text on dark backgrounds, primary UI element borders, input outlines. Also used for accent text that needs strong readability. |
| Deep Ocean | `#001B33` | `--color-deep-ocean` | Alternative dark background for specific cards, adding depth with a cool blue undertone. Often paired with lighter text. |
| Frost | `#FFFFFF` | `--color-frost` | Primary text color against dark backgrounds, essential UI backgrounds (e.g., active navigation items, badges), and high-visibility icons. |
| Ash Gray | `#333333` | `--color-ash-gray` | Discreet shadows for subtle elevation, secondary text on light backgrounds. |
| Iron Gray | `#666666` | `--color-iron-gray` | Placeholder text in inputs, tertiary text details, inactive icon fills. |
| Slate Gray | `#70757C` | `--color-slate-gray` | Muted text for descriptive elements, secondary links, and less prominent icons. |
| Pewter | `#999999` | `--color-pewter` | Divider lines, subtle text hints, disabled state elements. |
| Cloud | `#CCCCCC` | `--color-cloud` | Subtle UI element borders on lighter surfaces, secondary text on dark background. |
| Electric Blue | `#0088FF` | `--color-electric-blue` | Interactive elements, primary CTA hover/accent, key information highlights. The leading accent color for interactive states. |
| Vivid Green | `#16C253` | `--color-vivid-green` | Success states, positive indicators, and secondary interactive elements. A vibrant contrast to the dark theme. |
| Sunset Orange | `#E6714F` | `--color-sunset-orange` | Highlighting key words or prices, secondary accent details that demand attention. |
| Goldenrod | `#FFB764` | `--color-goldenrod` | Subtle background for specific card types, often paired with dark text to signify importance. |
| Magenta Burst | `#B855E7` | `--color-magenta-burst` | Accent background for unique cards or sections, typically showcasing a specific feature. |
| Sunshine Yellow | `#FFDD00` | `--color-sunshine-yellow` | Warning states, secondary highlights for attention-grabbing text or icons. |
| Crimson Red | `#FF5252` | `--color-crimson-red` | Error states, destructive actions, or critical warnings. |
| Teal Glow | `#1CECBb` | `--color-teal-glow` | Special feature highlights, decorative accents in illustrations. |
| Fuchsia Flare | `#DD55e7` | `--color-fuchsia-flare` | Text accents, interactive elements, drawing attention to specific information. |
| Sky Blue | `#60A5FA` | `--color-sky-blue` | Link color for embedded text that needs clear differentiation from body text. |
| Twilight Gradient | `linear-gradient(rgba(0, 0, 0, 0.5) 0.85%, rgba(0, 5, 46, 0.5) 25.81%, rgba(41, 40, 94, 0.5) 58.36%, rgba(84, 60, 123, 0.5) 79.52%, rgba(133, 90, 146, 0.5) 95.8%, rgba(195, 134, 171, 0.5) 107.19%)` | `--color-twilight-gradient` | Large background sections, visually distinct hero banners. Creates an expansive, cosmic feel. |
| Nebula Horizon | `linear-gradient(rgb(0, 0, 0) 0.85%, rgb(17, 45, 114) 33.4%, rgb(75, 82, 170) 49.68%, rgb(168, 135, 220) 70.84%, rgb(230, 196, 231) 95.8%, rgb(252, 219, 239) 107.19%)` | `--color-nebula-horizon` | Alternative hero background, suggesting a deeper, more profound sense of space. |

## Tokens — Typography

### Inter — Primary typeface for all UI elements, headings, and body text. Its clean, geometric forms maintain readability across sizes and weights, providing a digital-native but approachable feel. The precise letter-spacing at larger sizes contributes to the sharp, modern aesthetic. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 24px, 30px, 31px, 48px, 60px
- **Line height:** 1.00, 1.06, 1.07, 1.20, 1.25, 1.33, 1.40, 1.43, 1.45, 1.50, 1.56, 1.60, 1.63, 1.71
- **Letter spacing:** -0.057, -0.05, -0.04, -0.037, -0.025, -0.01, 0.01
- **Role:** Primary typeface for all UI elements, headings, and body text. Its clean, geometric forms maintain readability across sizes and weights, providing a digital-native but approachable feel. The precise letter-spacing at larger sizes contributes to the sharp, modern aesthetic.

### ui-monospace — Used sparingly for technical details, code snippets, or monospace display, offering a precise, fixed-width contrast to Inter. · `--font-ui-monospace`
- **Substitute:** monospace
- **Weights:** 300, 400
- **Sizes:** 11px
- **Line height:** 1.00, 1.30, 1.50
- **Letter spacing:** normal
- **Role:** Used sparingly for technical details, code snippets, or monospace display, offering a precise, fixed-width contrast to Inter.

### -apple-system — System fallback, or for specific native OS-like UI elements, ensuring consistent rendering on Apple devices. · `--font-apple-system`
- **Substitute:** system-ui
- **Weights:** 500
- **Sizes:** 9px, 10px
- **Line height:** 1.60, 1.78
- **Letter spacing:** normal
- **Role:** System fallback, or for specific native OS-like UI elements, ensuring consistent rendering on Apple devices.

### Flow Circular — A decorative, custom typeface used for unique design accents, probably within illustrations or specific brand callouts. Its circular nature adds a playful, organic touch contrasting the overall sharp UI. · `--font-flow-circular`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 14px, 16px
- **Line height:** 1.43, 1.50
- **Letter spacing:** normal
- **Role:** A decorative, custom typeface used for unique design accents, probably within illustrations or specific brand callouts. Its circular nature adds a playful, organic touch contrasting the overall sharp UI.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | 0.01px | `--text-body` |
| subheading | 18px | 1.5 | -0.01px | `--text-subheading` |
| heading-sm | 24px | 1.25 | -0.025px | `--text-heading-sm` |
| heading | 31px | 1.2 | -0.037px | `--text-heading` |
| heading-lg | 48px | 1.07 | -0.05px | `--text-heading-lg` |
| display | 60px | 1.06 | -0.057px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 144 | 144px | `--spacing-144` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| card | 24px |
| pill | 9999px |
| image | 24px |
| button | 4px |
| default | 9px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.2) 0px 0px 0px 2px inset` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset` | `--shadow-subtle-2` |
| md | `rgba(0, 0, 0, 0.3) 0px 0px 10px 0px` | `--shadow-md` |
| subtle-3 | `rgba(255, 255, 255, 0.25) 0px 0px 0px 1px inset` | `--shadow-subtle-3` |
| sm | `rgba(0, 0, 0, 0.25) 0px 1px 4px 0px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| sm-2 | `rgba(0, 0, 0, 0.1) 0px 4px 6px 0px` | `--shadow-sm-2` |
| sm-3 | `rgba(0, 0, 0, 0.08) 0px 2px 6px 0px` | `--shadow-sm-3` |
| subtle-4 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px` | `--shadow-subtle-4` |
| xl | `rgba(0, 0, 0, 0.4) 0px 8px 32px 0px` | `--shadow-xl` |
| subtle-5 | `rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.35) 0...` | `--shadow-subtle-5` |
| lg | `rgba(0, 0, 0, 0.25) 0px 3px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Ghost Button
**Role:** Call to action

Ghost button with `Frost` text on a transparent background, `Ghostly Gray` border, `9999px` border-radius, and `10px` vertical, `16px` horizontal padding typically used for primary actions within dark immersive sections.

### Pill Download Button (Light)
**Role:** Download action

Button with `Frost` text on a `rgba(228, 232, 239, 0.1)` background, `9999px` border-radius. Padding is inherited from text/icon size, creating a tight pill shape. Used for software downloads, often includes a platform icon.

### Pill Download Button (Dark)
**Role:** Download action

Button with `Frost` text on a `Midnight Eclipse` background, `9999px` border-radius. Padding is inherited from text/icon size. Used for software downloads, providing higher contrast on lighter elements.

### Navigation Link
**Role:** Navigation element

Text link with `Frost` color on transparent background, no radius, `8px` padding. Appears in the top navigation bar.

### Feature Card (Gradient BG)
**Role:** Content display

Card with `24px` border-radius, `24px` padding, and a `Nebula Horizon` gradient background. Often used for showcasing key features with an immersive visual.

### Standard Card (White BG)
**Role:** Content display

Card with `Frost` background, `24px` border-radius, `24px` padding, and subtle shadow (`rgba(0, 0, 0, 0.25) 0px 1px 4px 0px, rgba(0, 0, 0, 0.1) 0px 4px 59px 0px`). Used for detailed content sections, creating a light mode within the dark theme.

### Success Badge
**Role:** Status indicator

Badge with `Vivid Green` background, `24px` top/bottom `10px` side border-radius, `16px` vertical, `24px` horizontal padding. Used for highlighting positive status or 'top choice' labels.

### Warning Badge
**Role:** Status indicator

Badge with `Goldenrod` background, `24px` top/bottom `10px` side border-radius, `16px` vertical, `24px` horizontal padding. Used for highlighting warnings or special offers.

### Form Input
**Role:** Data entry

Input field with `rgba(255, 255, 255, 0.1)` background, `Frost` text, `9px` border-radius, `8px` vertical, `12px` left, `100px` right padding. Provides a semi-transparent, subtle input style.

### Header Download Button
**Role:** Primary Navigation CTA

Button with `Frost` background, `Midnight Eclipse` text, `9999px` border-radius. Used in the header navigation for primary downloads. Padding for a clear, compact pill shape, often containing an icon.

## Do's and Don'ts

### Do
- Prioritize `Midnight Eclipse` (#000000) for all page backgrounds when not using gradients, to maintain the dark theme.
- Use `Frost` (#FFFFFF) for all primary text on dark backgrounds and `Ghostly Gray` (#E5E7EB) for secondary text and borders.
- Apply `9px` border-radius as the default for most UI elements, especially interactive components and containers, and `9999px` for all pill-shaped buttons and tags.
- Utilize `Electric Blue` (#0088FF) as the primary accent color for all interactive states, active indicators, and prominent CTAs.
- Maintain `16px` as the default `elementGap` between closely related UI components and `32px` for `sectionGap` between distinct content blocks.
- Employ the Inter font family for all textual content, leveraging its range of weights from 300 to 700 to establish clear typographic hierarchy.
- When incorporating vivid gradients like `Nebula Horizon`, ensure text overlay is `Frost` (#FFFFFF) for optimal contrast and readability.

### Don't
- Avoid using `Electric Blue` (#0088FF) as a primary background color; reserve it strictly for accents and interactive elements.
- Do not introduce sharp corners on interactive elements; maintain `9px` or `9999px` radius for consistency.
- Refrain from using light backgrounds or `Frost` (#FFFFFF) as the default page canvas; it should only appear on purposefully elevated cards or specific content sections.
- Do not deviate from the Inter font family for headings and body text, unless for decorative elements using 'Flow Circular' as specified.
- Avoid generic, full-bleed images without context; imagery must be contained or integrate seamlessly into the gradient backgrounds.
- Do not use subtle shadows on dark backgrounds; if elevation needs a shadow, ensure it's a prominent, dark `rgba(0, 0, 0, 0.25)` or an inset white shadow to define edges.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Midnight Eclipse | `#000000` | Page background (base) |
| 1 | Starless Night | `#030719` | Subtle low-elevation background for cards/sections |
| 2 | Sky Blue Transparency | `#001b33` | Specialized card backgrounds, providing a cool dark tint |
| 3 | Frost | `#FFFFFF` | High-contrast card backgrounds, breaking the dark theme for emphasis |

## Elevation

- **Standard Card (White BG):** `rgba(0, 0, 0, 0.25) 0px 1px 4px 0px, rgba(0, 0, 0, 0.1) 0px 4px 59px 0px`
- **Icon (hover/active):** `rgba(255, 255, 255, 0.2) 0px 0px 0px 2px inset`

## Imagery

The visual language is characterized by abstract, ethereal gradient backgrounds that suggest cosmic or digital expanses. Interspersed are realistic or subtly stylized product screenshots (laptops, phones) which are often cropped and contained, emphasizing the software's integration into devices. Photography of people is minimal and high-contrast, using silhouettes against dark backgrounds to represent the user. Icons are primarily monochromatic, either `Frost` or `Ghostly Gray` fills with slight `Ghostly Gray` strokes, occasionally accented with `Electric Blue` or other brand colors. They appear mostly outlined, with a moderate stroke weight, and follow a general system icon style. Imagery serves both decorative atmosphere and explicit product demonstration, with a lower density of visual content than text-heavy sites but used strategically for impact. Visuals are typically contained, not full-bleed, and often integrate with the subtle blur/gloss effects.

## Layout

The page primarily uses a max-width contained layout, likely centered, against a full-bleed dark background or gradient. The hero section features a full-bleed gradient (`Nebula Horizon` or `Twilight Gradient`) with a large, centered headline and aligned call-to-action buttons. Content sections alternate between these deep gradient backgrounds and occasional `Frost` (#FFFFFF) cards, creating a rhythmic dark/light contrast. Information is often arranged in centered stacks or alternating 2-column text + image layouts. Feature sets are presented in grid structures, potentially 3 or 4 columns, with distinct card backgrounds. Spacing is comfortable, allowing elements to breathe. The navigation is a sticky top bar with left-aligned links and a prominent 'Download' button, maintaining presence across scrolls.

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary:** #FFFFFF (Frost)
- **Background Primary:** #000000 (Midnight Eclipse)
- **CTA Accent:** #0088FF (Electric Blue)
- **Border Default:** #E5E7EB (Ghostly Gray)
- **Card Background (Elevated):** #FFFFFF (Frost)

### 3-5 Example Component Prompts
1. **Create a Hero Section:** Full-bleed background using `Nebula Horizon` gradient. Centered `display` headline in `Inter` weight `700`, `Frost` text. Below, two `Pill Download Button (Light)` components side-by-side with 16px elementGap.
2. **Design a Feature Card:** Use `Starless Night` (#030719) as the background. Apply `24px` border-radius. Inside, a `heading-sm` text in `Frost`, followed by `body` text in `Ghostly Gray`, with `16px` vertical and horizontal `cardPadding`.
3. **Build a Navigation Bar:** Fixed at the top, `Midnight Eclipse` background. Left-aligned links using `Navigation Link` components with `Frost` text. Right-aligned `Header Download Button`.

## Similar Brands

- **Linear** — Dark-mode UI with strong emphasis on typography, sharp corners, and a vivid accent color against a mostly monochrome palette.
- **Stripe** — Focus on high-contrast text on dark backgrounds, subtle gradients, and elegant, functional UI elements.
- **Notion** — Clean, functional design with flexible content blocks and a mix of contained UI elements against a neutral background (though Notion is light, the structural approach to content is similar).
- **Raycast** — Dark-themed UI, minimalist approach, and a strong emphasis on precise and responsive interactive elements with minimal decorative flair.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-eclipse: #000000;
  --color-starless-night: #030719;
  --color-twilight-ink: #1C1D1F;
  --color-ghostly-gray: #E5E7EB;
  --color-deep-ocean: #001B33;
  --color-frost: #FFFFFF;
  --color-ash-gray: #333333;
  --color-iron-gray: #666666;
  --color-slate-gray: #70757C;
  --color-pewter: #999999;
  --color-cloud: #CCCCCC;
  --color-electric-blue: #0088FF;
  --color-vivid-green: #16C253;
  --color-sunset-orange: #E6714F;
  --color-goldenrod: #FFB764;
  --color-magenta-burst: #B855E7;
  --color-sunshine-yellow: #FFDD00;
  --color-crimson-red: #FF5252;
  --color-teal-glow: #1CECBb;
  --color-fuchsia-flare: #DD55e7;
  --color-sky-blue: #60A5FA;
  --color-twilight-gradient: #000000;
  --gradient-twilight-gradient: linear-gradient(rgba(0, 0, 0, 0.5) 0.85%, rgba(0, 5, 46, 0.5) 25.81%, rgba(41, 40, 94, 0.5) 58.36%, rgba(84, 60, 123, 0.5) 79.52%, rgba(133, 90, 146, 0.5) 95.8%, rgba(195, 134, 171, 0.5) 107.19%);
  --color-nebula-horizon: #000000;
  --gradient-nebula-horizon: linear-gradient(rgb(0, 0, 0) 0.85%, rgb(17, 45, 114) 33.4%, rgb(75, 82, 170) 49.68%, rgb(168, 135, 220) 70.84%, rgb(230, 196, 231) 95.8%, rgb(252, 219, 239) 107.19%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-flow-circular: 'Flow Circular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.025px;
  --text-heading: 31px;
  --leading-heading: 1.2;
  --tracking-heading: -0.037px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: -0.05px;
  --text-display: 60px;
  --leading-display: 1.06;
  --tracking-display: -0.057px;

  /* Typography — Weights */
  --font-weight-light: 300;
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 9px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 999px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-card: 24px;
  --radius-pill: 9999px;
  --radius-image: 24px;
  --radius-button: 4px;
  --radius-default: 9px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px 0px 0px 2px inset;
  --shadow-subtle-2: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset;
  --shadow-md: rgba(0, 0, 0, 0.3) 0px 0px 10px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.25) 0px 0px 0px 1px inset;
  --shadow-sm: rgba(0, 0, 0, 0.25) 0px 1px 4px 0px, rgba(0, 0, 0, 0.1) 0px 4px 59px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.1) 0px 4px 6px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.08) 0px 2px 6px 0px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px;
  --shadow-xl: rgba(0, 0, 0, 0.4) 0px 8px 32px 0px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.35) 0px 8px 24px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.25) 0px 3px 20px 0px;

  /* Surfaces */
  --surface-midnight-eclipse: #000000;
  --surface-starless-night: #030719;
  --surface-sky-blue-transparency: #001b33;
  --surface-frost: #FFFFFF;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-eclipse: #000000;
  --color-starless-night: #030719;
  --color-twilight-ink: #1C1D1F;
  --color-ghostly-gray: #E5E7EB;
  --color-deep-ocean: #001B33;
  --color-frost: #FFFFFF;
  --color-ash-gray: #333333;
  --color-iron-gray: #666666;
  --color-slate-gray: #70757C;
  --color-pewter: #999999;
  --color-cloud: #CCCCCC;
  --color-electric-blue: #0088FF;
  --color-vivid-green: #16C253;
  --color-sunset-orange: #E6714F;
  --color-goldenrod: #FFB764;
  --color-magenta-burst: #B855E7;
  --color-sunshine-yellow: #FFDD00;
  --color-crimson-red: #FF5252;
  --color-teal-glow: #1CECBb;
  --color-fuchsia-flare: #DD55e7;
  --color-sky-blue: #60A5FA;
  --color-twilight-gradient: #000000;
  --color-nebula-horizon: #000000;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ui-monospace: 'ui-monospace', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-flow-circular: 'Flow Circular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: 0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.025px;
  --text-heading: 31px;
  --leading-heading: 1.2;
  --tracking-heading: -0.037px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: -0.05px;
  --text-display: 60px;
  --leading-display: 1.06;
  --tracking-display: -0.057px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-144: 144px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 9px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 999px;
  --radius-full-2: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.2) 0px 0px 0px 2px inset;
  --shadow-subtle-2: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset;
  --shadow-md: rgba(0, 0, 0, 0.3) 0px 0px 10px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.25) 0px 0px 0px 1px inset;
  --shadow-sm: rgba(0, 0, 0, 0.25) 0px 1px 4px 0px, rgba(0, 0, 0, 0.1) 0px 4px 59px 0px;
  --shadow-sm-2: rgba(0, 0, 0, 0.1) 0px 4px 6px 0px;
  --shadow-sm-3: rgba(0, 0, 0, 0.08) 0px 2px 6px 0px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px;
  --shadow-xl: rgba(0, 0, 0, 0.4) 0px 8px 32px 0px;
  --shadow-subtle-5: rgba(0, 0, 0, 0.4) 0px 0px 1px 0px, rgba(0, 0, 0, 0.35) 0px 8px 24px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.25) 0px 3px 20px 0px;
}
```
