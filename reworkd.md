# Reworkd — Style Reference
> Clean data grid on a soft-shaded canvas.

**Theme:** light

Reworkd embraces a crisp, functional aesthetic with a subtle depth. A primary white canvas subtly blends into gradient backdrops, while structured content blocks appear lifted through nuanced shadows. Typography is precise and compact, ensuring efficient information delivery. A dominant vibrant blue provides clear accents for interactive elements and brand identity, establishing a trustworthy yet dynamic feel for data extraction services.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#272c30` | `--color-midnight-graphite` | Primary text, strong borders, dark card backgrounds for elevated elements |
| Pure Canvas | `linear-gradient(92deg, rgb(255, 255, 255) 0.37%, rgb(166, 180, 186) 48.8%)` | `--color-pure-canvas` | Page background, primary card surfaces, inverse text on dark elements; Subtle background blend, often used in transitions or layered elements |
| Soft Fog | `#e3e8ea` | `--color-soft-fog` | Subtle button backgrounds, light surface accents, dividers |
| Ash Gray | `#a6b4ba` | `--color-ash-gray` | Muted borders, secondary text, placeholder text in inputs |
| Slate Steel | `#526068` | `--color-slate-steel` | Secondary text, active navigation indicators, subtle button borders |
| Sky Surge | `#3e79ea` | `--color-sky-surge` | Primary action buttons, interactive elements, accent highlights |
| Deep Ocean | `#3161df` | `--color-deep-ocean` | Decorative highlights, accent borders, dynamic background elements |
| Azure Glow | `#3e9ed0` | `--color-azure-glow` | Infrequent accent for specific icon or text highlights |
| Mint Success | `#89ecb0` | `--color-mint-success` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Oceanic Gradient | `linear-gradient(rgb(88, 151, 247) 0px, rgb(56, 114, 230) 100%)` | `--color-oceanic-gradient` | Hero section background, large brand statements |
| Radial Spectrum | `radial-gradient(335.69% 99.21% at 57.77% 0px, rgb(0, 89, 255) 0px, rgba(129, 118, 255, 0.73) 36.5%, rgba(255, 225, 66, 0) 75.65%, rgba(72, 132, 239, 0) 100%)` | `--color-radial-spectrum` | Decorative background details, complex brand illustrations |
| Deep Space Overlay | `radial-gradient(100% 100% at 50% 0px, rgb(40, 77, 205) 56.6%, rgb(27, 37, 80) 100%)` | `--color-deep-space-overlay` | Darker background accents, subtle overlays, brand-aligned dark surfaces |
| Soft Sky Canvas | `linear-gradient(rgb(240, 248, 255), rgb(195, 217, 250))` | `--color-soft-sky-canvas` | Subtle page section background, creating visual separation without high contrast |

## Tokens — Typography

### Selecta — Primary display and heading font, its tight tracking and large sizes create a bold, modern statement for key messages. The negative letter spacing ensures visual cohesion at large scales. · `--font-selecta`
- **Substitute:** Montserrat
- **Weights:** 400, 500
- **Sizes:** 18px, 40px, 56px, 80px, 86px
- **Line height:** 0.95, 1.00, 1.10, 1.17, 1.33
- **Letter spacing:** -0.025em for 86px, -0.020em for 80px, -0.015em for 56px, -0.010em for 40px
- **Role:** Primary display and heading font, its tight tracking and large sizes create a bold, modern statement for key messages. The negative letter spacing ensures visual cohesion at large scales.

### Suisse Intl — Body copy, UI labels, navigation - its subtle letter spacing ensures readability and distinctiveness, while varying weights provide hierarchy within compact elements. · `--font-suisse-intl`
- **Weights:** 400, 450, 500, 600
- **Sizes:** 8px, 9px, 10px, 11px, 12px, 14px, 16px
- **Line height:** 1.00, 1.09, 1.20, 1.33, 1.40, 1.43, 1.45, 1.50, 1.57, 1.67
- **Letter spacing:** 0.01em for 16px, 0.02em for 12px, 0.04em for 10px, 0.05em for 8px
- **Role:** Body copy, UI labels, navigation - its subtle letter spacing ensures readability and distinctiveness, while varying weights provide hierarchy within compact elements.

### Geist Mono — Code snippets, data displays, technical details. The monospaced nature emphasizes precision and data orientation. The wide letter spacing at smaller sizes creates clear differentiation for technical labels. · `--font-geist-mono`
- **Weights:** 400, 450, 500, 600
- **Sizes:** 8px, 9px, 10px, 12px, 16px
- **Line height:** 1.20, 1.33, 1.50, 1.60, 1.67
- **Letter spacing:** 0.01em for 16px, 0.013em for 12px, 0.02em for 10px, 0.15em for 8px
- **Role:** Code snippets, data displays, technical details. The monospaced nature emphasizes precision and data orientation. The wide letter spacing at smaller sizes creates clear differentiation for technical labels.

### Geist Sans — Small functional text like button labels, secondary navigation, and micro-text. Its clean structure supports clarity at small sizes. · `--font-geist-sans`
- **Weights:** 400, 500, 600, 700
- **Sizes:** 8px, 11px, 12px
- **Line height:** 1.45, 1.50, 1.67, 2.18
- **Letter spacing:** 0.01em for 12px, 0.02em for 8px
- **Role:** Small functional text like button labels, secondary navigation, and micro-text. Its clean structure supports clarity at small sizes.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.57 | — | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading | 40px | 1.17 | -0.8px | `--text-heading` |
| display | 86px | 0.95 | -2.15px | `--text-display` |

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
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 104 | 104px | `--spacing-104` |
| 136 | 136px | `--spacing-136` |

### Border Radius

| Element | Value |
|---------|-------|
| card | 8px |
| pill | 9999px |
| button | 6px |
| default | 6px |
| largeCard | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(39, 44, 48, 0.1) 0px 0px 0px 1px` | `--shadow-subtle` |
| subtle-2 | `rgba(63, 70, 75, 0.1) 0px 1px 3px 0px, rgba(63, 70, 75, 0...` | `--shadow-subtle-2` |
| xl | `rgba(63, 70, 75, 0.1) 0px 21px 44px -32px, rgba(39, 44, 4...` | `--shadow-xl` |
| subtle-3 | `rgb(255, 255, 255) 0px 0px 0px 2px, rgba(39, 44, 48, 0.13...` | `--shadow-subtle-3` |
| subtle-4 | `rgba(255, 255, 255, 0.25) 0px 1px 0px 0px inset, rgba(26,...` | `--shadow-subtle-4` |
| xl-2 | `rgba(63, 70, 75, 0.5) 0px 21px 44px -40px, rgba(39, 44, 4...` | `--shadow-xl-2` |
| sm | `rgba(63, 70, 75, 0.04) 0px 0px 8px 0px, rgba(63, 70, 75, ...` | `--shadow-sm` |
| subtle-5 | `rgba(63, 70, 75, 0.4) 0px 1px 3px 0px, rgb(70, 81, 88) 0p...` | `--shadow-subtle-5` |
| md | `rgba(63, 70, 75, 0.1) 0px 3px 12px 0px, rgba(63, 70, 75, ...` | `--shadow-md` |
| subtle-6 | `rgba(63, 70, 75, 0.2) 0px 1px 2px 0px` | `--shadow-subtle-6` |
| subtle-7 | `rgba(0, 0, 0, 0.25) 0px 1px 3px 0px, rgba(255, 255, 255, ...` | `--shadow-subtle-7` |
| subtle-8 | `rgba(255, 255, 255, 0.05) 0px 1px 0px 0px inset, rgba(33,...` | `--shadow-subtle-8` |
| xl-3 | `rgba(255, 255, 255, 0.04) 0px -4px 36px 1px inset, rgba(2...` | `--shadow-xl-3` |

### Layout

- **Page max-width:** 1344px
- **Section gap:** 24px
- **Card padding:** 12px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Filled button for main calls to action.

Background: Sky Surge (#3e79ea), Text: Pure Canvas (#ffffff), Padding: 8px vertical, 14px horizontal, Radius: 6px. Uses Suisse Intl, weight 500.

### Ghost Button
**Role:** Minimal impact button for secondary actions or links.

Background: transparent, Text: Slate Steel (#526068), Border: 1px solid Slate Steel (#526068), Padding: 2.5px vertical (adjusted implicitly by text), Radius: 6px. Utilizes Suisse Intl.

### Subtle Neutral Button
**Role:** Light background button for filters or toggles.

Background: Soft Fog (#e3e8ea), Text: Slate Steel (#526068), Radius: 6px. Padding: 2.5px vertical, 40px horizontal for broader elements. Uses Geist Sans.

### Clean Data Card
**Role:** Default card for displaying content blocks.

Background: Pure Canvas (#ffffff), Padding: 0px, Radius: 8px. Shadow: a deep, multi-layered projection rgba(63, 70, 75, 0.1) 0px 21px 44px -32px, rgba(39, 44, 48, 0.2) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.08) 0px 0px 0px 1px, rgba(39, 44, 48, 0.12) 0px 4px 8px 0px.

### Elevated Data Card
**Role:** Emphasized card for key information or interactive components.

Background: Pure Canvas (#ffffff), Padding: 0px, Radius: 12px. Shadow: a more pronounced projection rgba(63, 70, 75, 0.5) 0px 21px 44px -40px, rgba(39, 44, 48, 0.1) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.1) 0px 0px 0px 1px, rgba(39, 44, 48, 0.07) 0px 4px 9px 0px. This deeper shadow reinforces hierarchy.

### Light Utility Card
**Role:** Simplified card for listing or grouped information.

Background: Pure Canvas (#ffffff), Padding: 0px, Radius: 8px. Shadow: subtle and singular, rgba(63, 70, 75, 0.04) 0px 0px 8px 0px, rgba(63, 70, 75, 0.03) 0px 1px 5px 0px, rgba(55, 61, 66, 0.05) 0px 0px 0px 1px. Best for nested or less important content.

### Dark Code Card
**Role:** Themed card specifically for code examples or dark UI elements.

Background: #373d42, Padding: 12px, Radius: 8px. Shadow: rgba(63, 70, 75, 0.1) 0px 3px 12px 0px, rgba(63, 70, 75, 0.55) 0px 1px 5px 0px, rgb(63, 70, 75) 0px 0px 0px 1px. Uses Geist Mono for content.

### Pill Tag Button
**Role:** Small, rounded tags for categories or status labels.

Background: transparent or very light, Text: Ash Gray (#a6b4ba) or similar neutral, Radius: 9999px for full pill shape. Padding: 2px vertical, 4px horizontal. Uses Suisse Intl.

## Do's and Don'ts

### Do
- Use Sky Surge (#3e79ea) for primary interactive elements and brand accents.
- Apply Deep Ocean (#3161df) selectively for large, impactful brand statements or vibrant background elements.
- Employ the Selecta font family for all display and large heading text, ensuring negative letter spacing decreases proportionally as size increases.
- Structure layout with a compact density, maintaining an element gap of 8px and card padding of 12px as default relationships.
- Utilize distinct shadow patterns for cards: a subtle shadow for utility cards, and a more pronounced, multi-layered shadow for elevated, primary content cards. For instance, Clean Data Card uses rgba(63, 70, 75, 0.1) 0px 21px 44px -32px.
- Ensure all interactive elements and contained content blocks adhere to a default border radius of 6px, with exceptions for larger cards at 8px or 12px, and pill shapes at 9999px.
- Maintain a maximum page content width of 1344px for main content areas to keep balance and readability.

### Don't
- Do not use highly saturated colors for general backgrounds; stick to Pure Canvas (#ffffff) and Soft Sky Canvas (linear-gradient(rgb(240, 248, 255), rgb(195, 217, 250))).
- Avoid arbitrary changes to font weights within a single text block. Use predetermined weights within Suisse Intl and Geist Sans for consistency.
- Do not introduce new border radii beyond 6px, 8px, 12px, and 9999px if not explicitly defined for a component.
- Never use generic box-shadows; always apply one of the defined multi-layer shadow tokens for cards and elements needing elevation.
- Do not deviate from the established letter-spacing values for each font size and family, especially for Selecta's tight tracking which is a signature element.
- Avoid using primary brand colors (Sky Surge, Deep Ocean) for large blocks of text; reserve them for accents and active states.
- Do not use the monospaced Geist Mono for general body text; restrict its use to code, data, or technical labels.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pure Canvas | `#ffffff` | Base page background |
| 1 | Soft Sky Canvas | `#f0f8ff` | Subtle section backgrounds, creates gentle visual separation |
| 2 | Pure Canvas Card | `#ffffff` | Primary content cards, slightly elevated |
| 3 | Dark Code Card | `#373d42` | Elevated specific elements like code blocks or focused dark UI sections |

## Elevation

- **Clean Data Card:** `rgba(63, 70, 75, 0.1) 0px 21px 44px -32px, rgba(39, 44, 48, 0.2) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.08) 0px 0px 0px 1px, rgba(39, 44, 48, 0.12) 0px 4px 8px 0px`
- **Elevated Data Card:** `rgba(63, 70, 75, 0.5) 0px 21px 44px -40px, rgba(39, 44, 48, 0.1) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.1) 0px 0px 0px 1px, rgba(39, 44, 48, 0.07) 0px 4px 9px 0px`
- **Light Utility Card:** `rgba(63, 70, 75, 0.04) 0px 0px 8px 0px, rgba(63, 70, 75, 0.03) 0px 1px 5px 0px, rgba(55, 61, 66, 0.05) 0px 0px 0px 1px`
- **Dark Code Card:** `rgba(63, 70, 75, 0.1) 0px 3px 12px 0px, rgba(63, 70, 75, 0.55) 0px 1px 5px 0px, rgb(63, 70, 75) 0px 0px 0px 1px`
- **Icon with Focus:** `rgb(255, 255, 255) 0px 0px 0px 2px, rgba(39, 44, 48, 0.13) 0px 1px 2px 2px`

## Imagery

Minimal imagery focused on UI screenshots and small, functional line icons. Product screenshots are typically contained within cards, presented flat against white or dark backgrounds with clean borders and subtle shadows. The visual space is dominated by UI elements and text, with imagery serving explanatory or demonstrative roles rather than decorative.

## Layout

The page uses a maxWidth: 1344px centered content model, with some background gradients extending full-bleed, like the hero. The hero features a centered headline over a gradient background. Sections maintain consistent vertical spacing and alternate between Pure Canvas (#ffffff) and Soft Sky Canvas (gradient) for subtle visual rhythm. Content is arranged in either centered stacks for headlines and subtext or two-column text-left/visual-right patterns. Feature sections often use 3-column card grids, and pagination elements are horizontally centered. The navigation is a sticky top bar with clearly segmented links and a sign-up button.

## Agent Prompt Guide

Quick Color Reference: 
  text: #272c30
  background: #ffffff
  border: #a6b4ba
  accent: #3e79ea
  primary action: #3e79ea (filled action)

Example Component Prompts:
1. Create a Hero Section: Use Oceanic Gradient for background (linear-gradient(rgb(88, 151, 247) 0px, rgb(56, 114, 230) 100%)). Headline text 'End-to-end data extraction' using Selecta font, size 86px, weight 500, #ffffff, letter-spacing -2.15px. Subtext 'Effortlessly extract web data at scale. No code. No maintenance. No worries.' in Suisse Intl, size 16px, weight 400, #ffffff. Include a Primary Action Button 'Book an intro call' (background #3e79ea, text #ffffff, radius 6px, 8px vertical 14px horizontal padding).
2. Create a Clean Data Card: Background Pure Canvas (#ffffff), radius 8px, with the shadow rgba(63, 70, 75, 0.1) 0px 21px 44px -32px, rgba(3 chín, 44, 48, 0.2) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.08) 0px 0px 0px 1px, rgba(39, 44, 48, 0.12) 0px 4px 8px 0px. Internal content text in Suisse Intl, size 14px, weight 400, Midnight Graphite (#272c30).
3. Create a Subtle Neutral Button: Background Soft Fog (#e3e8ea), text Slate Steel (#526068), radius 6px, padding 2.5px vertical, 40px horizontal for a 'Filter' button. Text using Geist Sans, size 12px, weight 500.
4. Show an Elevated Data Card with a 'Powered By' partner logo section: Card background Pure Canvas (#ffffff), radius 12px, with shadow rgba(63, 70, 75, 0.5) 0px 21px 44px -40px, rgba(39, 44, 48, 0.1) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.1) 0px 0px 0px 1px, rgba(39, 44, 48, 0.07) 0px 4px 9px 0px. The internal logos are visually balanced with 12px element gaps.

## Similar Brands

- **Axiom.ai** — Similar focus on web data extraction, combining light UI with subtle blue accents and structured content forms.
- **PhantomBuster** — Clean SaaS aesthetic with a predominant use of white space, precise typography, and a single vibrant accent color for interaction.
- **Browserless** — Developer-focused tool with a blend of clean UI and structured data presentation, often featuring monochromatic design with a blue highlight.
- **ParseHub** — Direct competitor with a similar layout using prominent headlines, clear CTAs, and a focus on product screenshots within white cards.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #272c30;
  --color-pure-canvas: #ffffff;
  --gradient-pure-canvas: linear-gradient(92deg, rgb(255, 255, 255) 0.37%, rgb(166, 180, 186) 48.8%);
  --color-soft-fog: #e3e8ea;
  --color-ash-gray: #a6b4ba;
  --color-slate-steel: #526068;
  --color-sky-surge: #3e79ea;
  --color-deep-ocean: #3161df;
  --color-azure-glow: #3e9ed0;
  --color-mint-success: #89ecb0;
  --color-oceanic-gradient: #5897f7;
  --gradient-oceanic-gradient: linear-gradient(rgb(88, 151, 247) 0px, rgb(56, 114, 230) 100%);
  --color-radial-spectrum: #0059ff;
  --gradient-radial-spectrum: radial-gradient(335.69% 99.21% at 57.77% 0px, rgb(0, 89, 255) 0px, rgba(129, 118, 255, 0.73) 36.5%, rgba(255, 225, 66, 0) 75.65%, rgba(72, 132, 239, 0) 100%);
  --color-deep-space-overlay: #284dcd;
  --gradient-deep-space-overlay: radial-gradient(100% 100% at 50% 0px, rgb(40, 77, 205) 56.6%, rgb(27, 37, 80) 100%);
  --color-soft-sky-canvas: #f0f8ff;
  --gradient-soft-sky-canvas: linear-gradient(rgb(240, 248, 255), rgb(195, 217, 250));

  /* Typography — Font Families */
  --font-selecta: 'Selecta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-geist-sans: 'Geist Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.57;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 40px;
  --leading-heading: 1.17;
  --tracking-heading: -0.8px;
  --text-display: 86px;
  --leading-display: 0.95;
  --tracking-display: -2.15px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-136: 136px;

  /* Layout */
  --page-max-width: 1344px;
  --section-gap: 24px;
  --card-padding: 12px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-3xl: 26px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-card: 8px;
  --radius-pill: 9999px;
  --radius-button: 6px;
  --radius-default: 6px;
  --radius-largecard: 12px;

  /* Shadows */
  --shadow-subtle: rgba(39, 44, 48, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-2: rgba(63, 70, 75, 0.1) 0px 1px 3px 0px, rgba(63, 70, 75, 0.1) 0px 0px 0px 1px;
  --shadow-xl: rgba(63, 70, 75, 0.1) 0px 21px 44px -32px, rgba(39, 44, 48, 0.2) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.08) 0px 0px 0px 1px, rgba(39, 44, 48, 0.12) 0px 4px 8px 0px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0px 0px 2px, rgba(39, 44, 48, 0.13) 0px 1px 2px 2px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.25) 0px 1px 0px 0px inset, rgba(26, 41, 61, 0.15) 0px 1px 3px 0px, rgba(26, 41, 61, 0.11) 0px 7px 11px -5px, rgba(26, 41, 61, 0.08) 0px 0px 0px 1px;
  --shadow-xl-2: rgba(63, 70, 75, 0.5) 0px 21px 44px -40px, rgba(39, 44, 48, 0.1) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.1) 0px 0px 0px 1px, rgba(39, 44, 48, 0.07) 0px 4px 9px 0px;
  --shadow-sm: rgba(63, 70, 75, 0.04) 0px 0px 8px 0px, rgba(63, 70, 75, 0.03) 0px 1px 5px 0px, rgba(55, 61, 66, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-5: rgba(63, 70, 75, 0.4) 0px 1px 3px 0px, rgb(70, 81, 88) 0px 0px 0px 1px;
  --shadow-md: rgba(63, 70, 75, 0.1) 0px 3px 12px 0px, rgba(63, 70, 75, 0.55) 0px 1px 5px 0px, rgb(63, 70, 75) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(63, 70, 75, 0.2) 0px 1px 2px 0px;
  --shadow-subtle-7: rgba(0, 0, 0, 0.25) 0px 1px 3px 0px, rgba(255, 255, 255, 0.1) 0px 0px 2px 1px inset, rgba(255, 255, 255, 0.25) 0px 1px 1px 0px inset;
  --shadow-subtle-8: rgba(255, 255, 255, 0.05) 0px 1px 0px 0px inset, rgba(33, 38, 41, 0.1) 0px 3px 12px 0px, rgba(33, 38, 41, 0.2) 0px 1px 5px 0px, rgba(33, 38, 41, 0.9) 0px 0px 0px 1px;
  --shadow-xl-3: rgba(255, 255, 255, 0.04) 0px -4px 36px 1px inset, rgba(255, 255, 255, 0.13) 0px 0px 8px 2px inset, rgba(255, 255, 255, 0.1) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.5) 0px 21px 44px -40px, rgba(0, 0, 0, 0.1) 0px 26px 30px -23px, rgba(0, 0, 0, 0.05) 0px 14px 40px 0px, rgba(0, 0, 0, 0.07) 0px 4px 9px 0px;

  /* Surfaces */
  --surface-pure-canvas: #ffffff;
  --surface-soft-sky-canvas: #f0f8ff;
  --surface-pure-canvas-card: #ffffff;
  --surface-dark-code-card: #373d42;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #272c30;
  --color-pure-canvas: #ffffff;
  --color-soft-fog: #e3e8ea;
  --color-ash-gray: #a6b4ba;
  --color-slate-steel: #526068;
  --color-sky-surge: #3e79ea;
  --color-deep-ocean: #3161df;
  --color-azure-glow: #3e9ed0;
  --color-mint-success: #89ecb0;
  --color-oceanic-gradient: #5897f7;
  --color-radial-spectrum: #0059ff;
  --color-deep-space-overlay: #284dcd;
  --color-soft-sky-canvas: #f0f8ff;

  /* Typography */
  --font-selecta: 'Selecta', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-suisse-intl: 'Suisse Intl', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-mono: 'Geist Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-geist-sans: 'Geist Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.57;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 40px;
  --leading-heading: 1.17;
  --tracking-heading: -0.8px;
  --text-display: 86px;
  --leading-display: 0.95;
  --tracking-display: -2.15px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-136: 136px;

  /* Border Radius */
  --radius-sm: 1px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-3xl: 26px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(39, 44, 48, 0.1) 0px 0px 0px 1px;
  --shadow-subtle-2: rgba(63, 70, 75, 0.1) 0px 1px 3px 0px, rgba(63, 70, 75, 0.1) 0px 0px 0px 1px;
  --shadow-xl: rgba(63, 70, 75, 0.1) 0px 21px 44px -32px, rgba(39, 44, 48, 0.2) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.08) 0px 0px 0px 1px, rgba(39, 44, 48, 0.12) 0px 4px 8px 0px;
  --shadow-subtle-3: rgb(255, 255, 255) 0px 0px 0px 2px, rgba(39, 44, 48, 0.13) 0px 1px 2px 2px;
  --shadow-subtle-4: rgba(255, 255, 255, 0.25) 0px 1px 0px 0px inset, rgba(26, 41, 61, 0.15) 0px 1px 3px 0px, rgba(26, 41, 61, 0.11) 0px 7px 11px -5px, rgba(26, 41, 61, 0.08) 0px 0px 0px 1px;
  --shadow-xl-2: rgba(63, 70, 75, 0.5) 0px 21px 44px -40px, rgba(39, 44, 48, 0.1) 0px 26px 30px -23px, rgba(39, 44, 48, 0.05) 0px 14px 40px 0px, rgba(39, 44, 48, 0.1) 0px 0px 0px 1px, rgba(39, 44, 48, 0.07) 0px 4px 9px 0px;
  --shadow-sm: rgba(63, 70, 75, 0.04) 0px 0px 8px 0px, rgba(63, 70, 75, 0.03) 0px 1px 5px 0px, rgba(55, 61, 66, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-5: rgba(63, 70, 75, 0.4) 0px 1px 3px 0px, rgb(70, 81, 88) 0px 0px 0px 1px;
  --shadow-md: rgba(63, 70, 75, 0.1) 0px 3px 12px 0px, rgba(63, 70, 75, 0.55) 0px 1px 5px 0px, rgb(63, 70, 75) 0px 0px 0px 1px;
  --shadow-subtle-6: rgba(63, 70, 75, 0.2) 0px 1px 2px 0px;
  --shadow-subtle-7: rgba(0, 0, 0, 0.25) 0px 1px 3px 0px, rgba(255, 255, 255, 0.1) 0px 0px 2px 1px inset, rgba(255, 255, 255, 0.25) 0px 1px 1px 0px inset;
  --shadow-subtle-8: rgba(255, 255, 255, 0.05) 0px 1px 0px 0px inset, rgba(33, 38, 41, 0.1) 0px 3px 12px 0px, rgba(33, 38, 41, 0.2) 0px 1px 5px 0px, rgba(33, 38, 41, 0.9) 0px 0px 0px 1px;
  --shadow-xl-3: rgba(255, 255, 255, 0.04) 0px -4px 36px 1px inset, rgba(255, 255, 255, 0.13) 0px 0px 8px 2px inset, rgba(255, 255, 255, 0.1) 0px 1px 0px 0px inset, rgba(0, 0, 0, 0.5) 0px 21px 44px -40px, rgba(0, 0, 0, 0.1) 0px 26px 30px -23px, rgba(0, 0, 0, 0.05) 0px 14px 40px 0px, rgba(0, 0, 0, 0.07) 0px 4px 9px 0px;
}
```
