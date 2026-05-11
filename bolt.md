# Bolt — Style Reference
> vibrant financial command center

**Theme:** dark

Bolt presents a digital finance platform with a high-contrast dark theme punctuated by a vivid blue. Functional UI elements are precise and compact, while headings carry a bold, wide presence. The design balances a serious financial atmosphere with moments of dynamic color to highlight interaction and brand identity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#04091a` | `--color-midnight-ink` | Primary background for dark sections, structural borders, main navigation text. Establishes a deep, secure foundation |
| Abyssal Slate | `#111426` | `--color-abyssal-slate` | Elevated card backgrounds, input fields, badges within dark sections. Provides subtle depth against Midnight Ink |
| Skybound Blue | `#006cff` | `--color-skybound-blue` | Primary call-to-action buttons, interactive links, brand accents, and a distinctive outline for interactive elements. Serves as the key interactive highlight |
| Silver Whisper | `#8e92af` | `--color-silver-whisper` | Secondary text, muted links, subtle borders. Offers a soft contrast for less prominent information |
| Cloud Cover | `#f8f6fe` | `--color-cloud-cover` | Page canvas and light-themed backgrounds, subtly off-white. Provides a crisp backdrop |
| Ash Stone | `#262a42` | `--color-ash-stone` | Input placeholder text, disabled text, and minor decorative borders. Slightly darker than Silver Whisper for more subdued contexts |
| Deep Graphite | `#454a66` | `--color-deep-graphite` | Iconography and general body text in lighter sections. A stronger gray than Silver Whisper for higher contrast |
| Polar White | `#ffffff` | `--color-polar-white` | Text on dark backgrounds, active navigation elements. Ensures readability on very dark surfaces |
| Pale Mist | `#d3d7ed` | `--color-pale-mist` | Subtle borders and decorative fills. A very light, near-achromatic tone |

## Tokens — Typography

### Inter — Primary typeface for all body text, navigation, buttons, and form inputs. Its wide range of weights and optical adjustments supports a clean, functional interface across diverse elements, with subtle negative tracking for improved legibility at smaller sizes. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 9px, 11px, 12px, 13px, 14px, 15px, 16px, 18px, 20px
- **Line height:** 1.00, 1.20, 1.30, 1.50, 1.89
- **Letter spacing:** -0.0290em, -0.0200em, -0.0100em
- **Role:** Primary typeface for all body text, navigation, buttons, and form inputs. Its wide range of weights and optical adjustments supports a clean, functional interface across diverse elements, with subtle negative tracking for improved legibility at smaller sizes.

### agrandir-bolt — Signature display typeface for large headings and prominent brand elements. Its bold, condensed form, often with positive letter spacing at display sizes, delivers a strong, impactful brand statement. · `--font-agrandir-bolt`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 10px, 32px, 64px, 70px
- **Line height:** 1.00, 1.10, 1.30
- **Letter spacing:** -0.0200em, 0.0200em
- **Role:** Signature display typeface for large headings and prominent brand elements. Its bold, condensed form, often with positive letter spacing at display sizes, delivers a strong, impactful brand statement.

### Google Sans — Used sparingly for specific body text elements, offering a slightly different textual cadence at smaller sizes with tighter tracking and generous line height. · `--font-google-sans`
- **Substitute:** Roboto
- **Weights:** 500
- **Sizes:** 11px
- **Line height:** 1.89
- **Letter spacing:** -0.0290em
- **Role:** Used sparingly for specific body text elements, offering a slightly different textual cadence at smaller sizes with tighter tracking and generous line height.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.5 | -0.28px | `--text-body` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading | 32px | 1.1 | -0.64px | `--text-heading` |
| heading-lg | 64px | 1.1 | -1.28px | `--text-heading-lg` |
| display | 70px | 1 | 1.4px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 19 | 19px | `--spacing-19` |
| 22 | 22px | `--spacing-22` |
| 30 | 30px | `--spacing-30` |
| 50 | 50px | `--spacing-50` |
| 55 | 55px | `--spacing-55` |
| 71 | 71px | `--spacing-71` |
| 73 | 73px | `--spacing-73` |
| 75 | 75px | `--spacing-75` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| tabs | 30px |
| cards | 5px |
| links | 8px |
| badges | 100px |
| images | 12px |
| inputs | 5px |
| buttons | 1280px |

### Layout

- **Section gap:** 50px
- **Card padding:** 22px
- **Element gap:** 6px

## Components

### Primary Action Button
**Role:** Main call-to-action

Filled button with Skybound Blue (#006cff) background and Polar White (#ffffff) text. Features extra-large radius (1280px) for a pill shape. Padding is 13px vertical, 22px horizontal, using Inter font at a moderate size.

### Ghost Navigation Button
**Role:** Secondary navigation action

Transparent background with Silver Whisper (#8e92af) text. No visible border. Padding is 10px vertical, 19px horizontal, with Inter font. Used for secondary actions in navigation.

### Subtle Link Button
**Role:** Informational/utility button

Off-white background (#f8f6fe) with Deep Graphite (#454a66) text. No border, no radius. Padding is 10px vertical, 15px horizontal. Used for less prominent informational actions like 'For Users'.

### Navigation Link
**Role:** Header navigation item

Transparent background with Midnight Ink (#04091a) text for standard state on light backgrounds, Polar White (#ffffff) on dark backgrounds. No specific padding or border, relies on surrounding layout for spacing. Inter font.

### Input Field
**Role:** User data entry

Abyssal Slate (#111426) background with Polar White (#ffffff) text. Borderless. Radius is 4px. Padding is 16px vertical, 12px left, 40px right. Inter font.

### Informational Card
**Role:** Content grouping

Transparent background, no shadow, and 5px border radius. Content arranged within its bounds. Used mostly for structuring content blocks that don't require visual elevation.

### Pill Badge
**Role:** Categorization/status indicator

Abyssal Slate (#111426) background with Midnight Ink (#04091a) text. Large 100px border radius for a full pill shape. Content determines actual sizing. Used for specific, small informational labels.

## Do's and Don'ts

### Do
- Use Midnight Ink (#04091a) for primary dark backgrounds and Polar White (#ffffff) for text on these surfaces to maintain strong contrast.
- Apply Skybound Blue (#006cff) exclusively for primary interactive elements and brand accents, avoiding its use for static decoration.
- Ensure all buttons utilize a 1280px border radius to achieve the uniform pill shape.
- Prioritize Inter font for all functional UI text like navigation, forms, and body content, using its specific weight and letter spacing values.
- Maintain a clear visual hierarchy by limiting large, bold typography to 'agrandir-bolt' for headings and brand statements.
- Space elements with a default of 6px for `elementGap` and 50px for `sectionGap` unless specific components override this with larger padding.
- Use transparent card backgrounds and rely on the page section's background color for defining content blocks.

### Don't
- Never introduce new chromatic colors outside the established brand palette (Skybound Blue, various Grays).
- Avoid using shadows for UI elements; the system relies on color contrast and subtle background shifts for hierarchy.
- Do not deviate from the specified border radii (e.g., 5px for inputs, 1280px for buttons) as they define component identity.
- Do not use generic system fonts; 'Inter' and 'agrandir-bolt' are key to Bolt's typographic identity.
- Avoid excessive use of Polar White on light backgrounds; reserve it for text on dark surfaces or very subtle highlights.
- Do not apply large heading styles to body copy; 'agrandir-bolt' is reserved for impactful titles.
- Do not use gradients for backgrounds or surfaces; the system is built on solid color blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas Light | `#f8f6fe` | Base background for lighter page sections. |
| 2 | Page Canvas Dark | `#04091a` | Dominant background for main content sections and footer, establishing a deep, secure tone. |
| 3 | Elevated Surface | `#111426` | Used for cards, input fields, and badges, providing subtle visual separation on dark backgrounds. |

## Elevation

The design intentionally avoids traditional shadows, relying instead on high-contrast color shifts and changes in surface hues (e.g., Midnight Ink to Abyssal Slate) to define different layers and components. This creates a flat, modern aesthetic where elements appear to be cut out or layered directly without atmospheric effects, contributing to a sense of directness and efficiency.

## Imagery

The imagery focuses on tightly cropped, close-up product photography of a smartphone displaying the Bolt app. The phone is often held by a hand. The visual treatment is high-key, with clear focus on the device and its screen content, typically set against a stark, contrasting background. Icons are filled, mono-color with a heavy stroke appearance, often appearing in Skybound Blue (#006cff) or Polar White (#ffffff). The imagery primarily serves as product showcase and explanatory content, demonstrating the app's interface and functionality, occupying significant visual space in key sections.

## Layout

The page model alternates between full-bleed dark sections and max-width contained sections. The hero features a centered headline over a dark background, with a product shot off-center. Section rhythm is created by alternating Midnight Ink (#04091a) and Abyssal Slate (#111426) backgrounds. Content is often arranged in centered stacks or fluid text blocks, occasionally with image-left/text-right or text-left/image-right patterns. A fixed top navigation bar provides core links and actions.

## Agent Prompt Guide

Quick Color Reference: text: #ffffff, background: #04091a, border: #8e92af, accent: #006cff, primary action: #006cff (filled action)

Example Component Prompts:
Create a hero section: Dark background using Midnight Ink (#04091a). Headline 'One SuperApp to rule them all' in agrandir-bolt weight 700 at 64px, Polar White (#ffffff), letter spacing -0.0200em. Subtext 'Send money, earn rewards...' in Inter weight 400 at 18px, Silver Whisper (#8e92af).
Create a primary call-to-action button: Skybound Blue (#006cff) background, Polar White (#ffffff) text, 1280px radius, 13px vertical padding, 22px horizontal padding, 'Download SuperApp' in Inter font.
Create an input field: Abyssal Slate (#111426) background, Polar White (#ffffff) text, 4px radius, 16px vertical padding, 12px left padding, 40px right padding, placeholder text in Ash Stone (#262a42).
Create a navigation link: Transparent background, Midnight Ink (#04091a) text for 'Pay' in Inter weight 400 at 16px. Active state text is Skybound Blue (#006cff).
Create an informational badge: Abyssal Slate (#111426) background, 100px radius, Midnight Ink (#04091a) text (Inter font).

## Similar Brands

- **Revolut** — Similar dark, high-contrast UI with a single vivid accent color for interactive elements and an emphasis on digital finance.
- **Wise (formerly TransferWise)** — Uses a flat design aesthetic with strong typography and a functional approach to color and spacing in financial services.
- **Curve** — Employs a financial app design with dark themes, distinct card visuals, and clear call-to-action color usage.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #04091a;
  --color-abyssal-slate: #111426;
  --color-skybound-blue: #006cff;
  --color-silver-whisper: #8e92af;
  --color-cloud-cover: #f8f6fe;
  --color-ash-stone: #262a42;
  --color-deep-graphite: #454a66;
  --color-polar-white: #ffffff;
  --color-pale-mist: #d3d7ed;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-agrandir-bolt: 'agrandir-bolt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-google-sans: 'Google Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.28px;
  --text-display: 70px;
  --leading-display: 1;
  --tracking-display: 1.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-19: 19px;
  --spacing-22: 22px;
  --spacing-30: 30px;
  --spacing-50: 50px;
  --spacing-55: 55px;
  --spacing-71: 71px;
  --spacing-73: 73px;
  --spacing-75: 75px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 22px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 30px;
  --radius-full: 100px;
  --radius-full-2: 1280px;

  /* Named Radii */
  --radius-tabs: 30px;
  --radius-cards: 5px;
  --radius-links: 8px;
  --radius-badges: 100px;
  --radius-images: 12px;
  --radius-inputs: 5px;
  --radius-buttons: 1280px;

  /* Surfaces */
  --surface-page-canvas-light: #f8f6fe;
  --surface-page-canvas-dark: #04091a;
  --surface-elevated-surface: #111426;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #04091a;
  --color-abyssal-slate: #111426;
  --color-skybound-blue: #006cff;
  --color-silver-whisper: #8e92af;
  --color-cloud-cover: #f8f6fe;
  --color-ash-stone: #262a42;
  --color-deep-graphite: #454a66;
  --color-polar-white: #ffffff;
  --color-pale-mist: #d3d7ed;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-agrandir-bolt: 'agrandir-bolt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-google-sans: 'Google Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --tracking-heading: -0.64px;
  --text-heading-lg: 64px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.28px;
  --text-display: 70px;
  --leading-display: 1;
  --tracking-display: 1.4px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-19: 19px;
  --spacing-22: 22px;
  --spacing-30: 30px;
  --spacing-50: 50px;
  --spacing-55: 55px;
  --spacing-71: 71px;
  --spacing-73: 73px;
  --spacing-75: 75px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-3xl: 30px;
  --radius-full: 100px;
  --radius-full-2: 1280px;
}
```
