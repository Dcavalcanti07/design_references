# WalletConnect — Style Reference
> Digital ledger on white marble.

**Theme:** light

WalletConnect's design system evokes a digital ledger on a crisp white backdrop, emphasizing clarity and efficient data display. A vibrant spectrum of blues serves as the brand accent, signaling interactive elements and critical information without visual clutter. Typography is precise and utilitarian, supporting the feeling of a clean, functional interface where content takes precedence. Components are lightweight with subtle radii, avoiding heavy shadows or ornate flourishes to maintain an uncluttered visual plane.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, elevated card surfaces, body text on dark backgrounds |
| Paper White | `#f9f9f9` | `--color-paper-white` | Default card backgrounds, subtle background distinction from canvas |
| Ash Gray | `#e9e9e9` | `--color-ash-gray` | Muted background for sections or tertiary cards, slight elevation distinction |
| Graphite | `#202020` | `--color-graphite` | Primary text, prominent headings, dark button backgrounds, focused borders |
| Midnight Ink | `#1b2045` | `--color-midnight-ink` | Secondary text, subtle borders, high-contrast text on light backgrounds |
| Slate Gray | `#4f4f4f` | `--color-slate-gray` | Medium-dark text for supporting information, input borders |
| Silver Mist | `#787878` | `--color-silver-mist` | Placeholder text, inactive element borders, subtle dividers |
| Light Steel | `#bbbbbb` | `--color-light-steel` | Tertiary card backgrounds, subtle borders contrasting with dark |
| Sky Blue | `#cce2ff` | `--color-sky-blue` | Subtle highlights, secondary background accents, light border tints |
| Azure Blue | `#006cff` | `--color-azure-blue` | Primary links, active navigation indicators, decorative borders — creates a vibrant pull against neutral tones |
| Action Blue | `#4672ff` | `--color-action-blue` | Primary action button backgrounds, active states, focus rings — a bright, commanding blue for interactivity |
| Bright Blue | `#66a7ff` | `--color-bright-blue` | Outlined button borders, secondary interactive accents |
| Focus Shadow | `#b3b3b3` | `--color-focus-shadow` | Subtle box shadow for focus or elevation |
| Sky Burst Radial | `radial-gradient(78.13% 78.13% at 79.97% 80.72%, rgb(9, 159, 240) 0%, rgb(9, 121, 240) 100%)` | `--color-sky-burst-radial` | Hero section backgrounds, prominent accent fills for marketing elements |

## Tokens — Typography

### KHTeka — Primary typeface for all UI elements, headings, body text, and links. Its clean, geometric form supports readability across all sizes, driving clarity. · `--font-khteka`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 13px, 14px, 16px, 18px, 20px, 24px, 30px, 36px
- **Line height:** 1.00, 1.11, 1.20, 1.33, 1.40, 1.43, 1.46, 1.50, 1.56, 1.71
- **Letter spacing:** normal
- **Role:** Primary typeface for all UI elements, headings, body text, and links. Its clean, geometric form supports readability across all sizes, driving clarity.

### Roboto — Used for specific auxiliary text, such as some button labels, maintaining legibility for smaller informational notes. · `--font-roboto`
- **Substitute:** Roboto
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 16px, 17px
- **Line height:** 1.41, 1.50, 2.00
- **Letter spacing:** normal
- **Role:** Used for specific auxiliary text, such as some button labels, maintaining legibility for smaller informational notes.

### KHTekaMono — Monospaced font used for code snippets or technical details, offering clear character distinction, typically in cards. · `--font-khtekamono`
- **Substitute:** Fira Code
- **Weights:** 400
- **Sizes:** 12px, 14px
- **Line height:** 1.33, 1.43
- **Letter spacing:** normal
- **Role:** Monospaced font used for code snippets or technical details, offering clear character distinction, typically in cards.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | — | `--text-caption` |
| body | 14px | 1.71 | — | `--text-body` |
| heading | 18px | 1.4 | — | `--text-heading` |
| heading-lg | 20px | 1.33 | — | `--text-heading-lg` |
| display | 36px | 1 | — | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| default | 3px |
| heroElement | 40px |
| interactive | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.3) 0px 0px 8px 0px` | `--shadow-sm` |

### Layout

- **Page max-width:** 1600px
- **Section gap:** 32px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Ghost Navigation Button
**Role:** Top navigation links, secondary calls to action.

Transparent background, 'Midnight Ink' text, no border. Used for discrete, text-based actions.

### Default Small Button
**Role:** General purpose action button.

Canvas White background, 'Graphite' text, 16px border-radius, 11px vertical padding, 23px horizontal padding. A soft, approachable interactive element.

### Primary Action Button (Filled)
**Role:** Main call to action.

'Action Blue' background, 'Paper White' text, 3px border-radius, 10px vertical padding. This button is used sparingly to draw prominent attention to key user actions.

### Outline CTA Button
**Role:** Secondary call to action.

Canvas White background, 'Graphite' text, 'Graphite' border, 16px border-radius, 12px vertical padding, 18px horizontal padding. Offers a clear action without the strong visual weight of a filled button.

### Subtle Padding Card
**Role:** Generic card for content regions.

Transparent background, 0px border-radius, 0px padding-top/bottom, 8px padding-left/right. Used for structural grouping without adding visual weight.

### Rounded Edge Card (Top)
**Role:** Visually distinct card for section headers or feature blocks.

Light Steel background, 40px top-left and top-right border-radius, 0px for bottom corners. Used for creating unique section boundaries.

### Rounded Edge Card (Bottom)
**Role:** Visually distinct card for section footers or related content.

Ash Gray background, 0px top-left and top-right border-radius, 40px bottom-left and bottom-right border-radius, 32px padding. Provides a visual closure to content blocks.

### Rounded Corner Card
**Role:** General content card.

Transparent background, 40px border-radius, no shadow, no padding. Used for imagery or graphical elements that need a soft container.

### Input Field
**Role:** User input for forms.

Transparent background, 'Canvas White' text, 'Silver Mist' border, 16px border-radius, 12.5px vertical padding, 13px horizontal padding. Provides a clear, modern input area.

### Toast/Dialog Card
**Role:** Temporary information display, such as cookie preferences.

Paper White background, 16px padding-left/right, 40px border-radius, with a subtle 'Focus Shadow' (rgba(0, 0, 0, 0.3) 0px 0px 8px 0px). Provides a temporary overlay context.

### Badge (Text Only)
**Role:** Informational labels.

Transparent background, 'Graphite' text, 0px border-radius, 15px padding. Used for unobtrusive categorization or status indicators.

## Do's and Don'ts

### Do
- Prioritize 'Canvas White' (#ffffff) and 'Paper White' (#f9f9f9) for primary backgrounds to maintain a bright, open aesthetic.
- Use 'Action Blue' (#4672ff) exclusively for primary call-to-action button backgrounds and active states to ensure high impact and clarity.
- Employ 'KHTeka' font for all primary text elements, adjusting weight and size to establish hierarchy as defined in the type scale.
- Apply a 16px border-radius for all interactive elements like buttons and input fields to maintain visual consistency.
- Maintain a comfortable information density using an 8px 'elementGap' for most horizontal and vertical spacing between UI elements.
- Use 'Midnight Ink' (#1b2045) for secondary text and subtle borders to create distinction without over-saturating the interface with dark tones.
- Utilize a page max-width of 1600px, centering content within this constraint to provide ample breathing room and consistent layout.

### Don't
- Do not introduce new saturated colors outside the defined blue palette in primary UI elements; reserve them for specific content or imagery.
- Avoid using heavy drop shadows for elevation; instead, rely on subtle background color shifts and the single 'Focus Shadow' for distinction.
- Do not deviate from the specified border-radii; the 3px default, 16px for interactive elements, and 40px for large rounded elements are critical to the brand's shape language.
- Refrain from using `Roboto` or `KHTekaMono` for headings or extensive body copy; their roles are specific and should not be expanded.
- Do not use generic gray tones for borders or accents where a 'Sky Blue' (#cce2ff) or 'Azure Blue' (#006cff) could reinforce brand identity.
- Avoid tight, constrained layouts; aim for a comfortable density with ample whitespace, especially around content blocks and sections.
- Do not use text decoration (underline) on standard body links; reserve it for specific interactive states or functional UI elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Base page background |
| 1 | Paper White | `#f9f9f9` | Default surface for cards and modals |
| 2 | Ash Gray | `#e9e9e9` | Secondary background for distinguished sections or cards |
| 3 | Light Steel | `#bbbbbb` | Tertiary background for specific accented areas or larger cards |

## Elevation

- **Card (Dialog/Toast):** `rgba(0, 0, 0, 0.3) 0px 0px 8px 0px`

## Imagery

The imagery style is product-focused, featuring tightly cropped product shots of abstract devices displaying QR codes and digital interfaces, often set against brand-blue backgrounds. Photography uses high-key lighting for clarity, positioning the object as the hero without lifestyle context. Illustrations are minimal, with a clean, vector-based style. Icons are primarily outlined or subtle fills, contributing to the lightweight UI aesthetic. The visual density heavily favors UI elements and text, with imagery serving as clear, direct product showcasing rather than decorative atmosphere.

## Layout

The page employs a max-width 1600px centered layout for content, but the hero section often uses full-bleed backgrounds often featuring gradients to establish a rich initial visual. Sections typically alternate between white '#ffffff' and light gray '#e9e9e9' or '#bbbbbb' backgrounds, creating a clear visual rhythm. Content is arranged in alternating text-left/image-right or image-left/text-right patterns, alongside centered stacks for calls to action and descriptive paragraphs. A notable feature is the use of rounded edge cards for distinct top and bottom section boundaries. The navigation is a sticky top bar with ghost buttons and a prominent 'Request Demo' button. Overall density is comfortable, with generous vertical spacing between sections.

## Agent Prompt Guide

Quick Color Reference: 
text: #202020
background: #ffffff
border: #1b2045
accent: #006cff
primary action: #4672ff (filled action)

Example Component Prompts:
Create a Primary Action Button: #4672ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a standard content card: 'Paper White' (#f9f9f9) background, 12px padding, 0px border-radius. Headline is 'KHTeka' 20px, #202020. Body text 'KHTeka' 14px, #1b2045.
Create an input field: transparent background, 'Silver Mist' (#787878) border, 16px border-radius, 12.5px vertical padding, 13px horizontal padding. Placeholder text is 'Silver Mist' 'KHTeca' 14px, weight 400.
Create a ghost navigation item: 'Midnight Ink' (#1b2045) text, no background, no border. Text is 'KHTeka' 16px, weight 400. On hover, text color changes to 'Azure Blue' (#006cff).

## Similar Brands

- **Stripe** — Shares a professional, modern aesthetic with a focus on clean typography, ample white space, and a measured use of brand-colored accents for interactive elements.
- **Ramp** — Utilizes a crisp UI, strong blue accents against a light background, and a similar approach to functional, uncluttered component design for financial services.
- **Mercury** — Employs a refined use of whitespace, precise typography, and a limited, purposeful brand color palette (blue) to evoke trustworthiness and efficiency in financial tech.
- **Checkout.com** — Features a clean, data-driven interface with a prominent blue brand color, minimal shadows, and a strong emphasis on clear, readable information presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-paper-white: #f9f9f9;
  --color-ash-gray: #e9e9e9;
  --color-graphite: #202020;
  --color-midnight-ink: #1b2045;
  --color-slate-gray: #4f4f4f;
  --color-silver-mist: #787878;
  --color-light-steel: #bbbbbb;
  --color-sky-blue: #cce2ff;
  --color-azure-blue: #006cff;
  --color-action-blue: #4672ff;
  --color-bright-blue: #66a7ff;
  --color-focus-shadow: #b3b3b3;
  --color-sky-burst-radial: #099ff0;
  --gradient-sky-burst-radial: radial-gradient(78.13% 78.13% at 79.97% 80.72%, rgb(9, 159, 240) 0%, rgb(9, 121, 240) 100%);

  /* Typography — Font Families */
  --font-khteka: 'KHTeka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto: 'Roboto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-khtekamono: 'KHTekaMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body: 14px;
  --leading-body: 1.71;
  --text-heading: 18px;
  --leading-heading: 1.4;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.33;
  --text-display: 36px;
  --leading-display: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

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
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Layout */
  --page-max-width: 1600px;
  --section-gap: 32px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;

  /* Named Radii */
  --radius-default: 3px;
  --radius-heroelement: 40px;
  --radius-interactive: 16px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.3) 0px 0px 8px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-paper-white: #f9f9f9;
  --surface-ash-gray: #e9e9e9;
  --surface-light-steel: #bbbbbb;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-paper-white: #f9f9f9;
  --color-ash-gray: #e9e9e9;
  --color-graphite: #202020;
  --color-midnight-ink: #1b2045;
  --color-slate-gray: #4f4f4f;
  --color-silver-mist: #787878;
  --color-light-steel: #bbbbbb;
  --color-sky-blue: #cce2ff;
  --color-azure-blue: #006cff;
  --color-action-blue: #4672ff;
  --color-bright-blue: #66a7ff;
  --color-focus-shadow: #b3b3b3;
  --color-sky-burst-radial: #099ff0;

  /* Typography */
  --font-khteka: 'KHTeka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto: 'Roboto', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-khtekamono: 'KHTekaMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --text-body: 14px;
  --leading-body: 1.71;
  --text-heading: 18px;
  --leading-heading: 1.4;
  --text-heading-lg: 20px;
  --leading-heading-lg: 1.33;
  --text-display: 36px;
  --leading-display: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.3) 0px 0px 8px 0px;
}
```
