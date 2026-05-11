# ORYZO AI — Style Reference
> Cork-textured midnight laboratory

**Theme:** dark

ORYZO AI embraces a deep, textural aesthetic, contrasting rich, dark surfaces with a warm, desaturated highlight palette. Textures and a muted orange accent color punctuate the composition, creating a refined yet tactile experience. The typography, primarily a custom variable font, leans into density and slight tracking, reinforcing a sense of engineered precision. This system feels grounded and thoughtfully constructed with a focus on core product detail.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Darkness | `#100904` | `--color-pitch-darkness` | Dark borders and separators for elevated surfaces and inverted UI. Do not promote it to the primary CTA color |
| Cork Dust | `#ffedd7` | `--color-cork-dust` | Primary text across dark backgrounds, light button backgrounds, input text and borders. Provides high contrast |
| Rust Accent | `#dc5000` | `--color-rust-accent` | Important accent details, button backgrounds for primary actions, decorative borders, active state indicators. A warm, vivid focal point |
| Olive Green | `#445231` | `--color-olive-green` | Subtle background accents, decorative text. A muted, organic highlight |
| Faded Bark | `#382416` | `--color-faded-bark` | Button backgrounds for secondary actions, subtle surface distinction. A warmer, slightly lighter neutral than Pitch Darkness |
| Aged Stone | `#887b6d` | `--color-aged-stone` | Secondary text, muted helper text, subtle outlines |
| Light Cork | `#f6e0c6` | `--color-light-cork` | Subtle background surfaces, highlights. A very light, near-neutral tone |
| Faint Hazel | `#bbac97` | `--color-faint-hazel` | Tertiary text, decorative elements with reduced prominence |
| Subtle Moss | `#5d6c49` | `--color-subtle-moss` | Minor decorative details, secondary green accents |
| Grayscale Gray | `#808080` | `--color-grayscale-gray` | Table borders, general neutral separators |
| Chalkboard Black | `#000000` | `--color-chalkboard-black` | Used sparingly for icon fills |
| Deep Mocha | `#40372e` | `--color-deep-mocha` | Darker, almost black borders |
| Rainbow Spectrum | `linear-gradient(rgb(253, 254, 237), rgb(255, 191, 2) 17%, rgb(233, 80, 14) 32%, rgb(205, 25, 125), rgb(140, 1, 156), rgb(37, 1, 135), rgb(3, 3, 16))` | `--color-rainbow-spectrum` | A distinct background gradient for hero sections or prominent visual statements, featuring a vibrant multi-color blend |

## Tokens — Typography

### halyard-display-variable — Primary UI text for headings, body, buttons, navigation, and badges. Its variable weights and precise tracking create a dense, modern feel. · `--font-halyard-display-variable`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 17px, 18px, 23px, 24px, 29px, 34px, 41px, 49px, 51px, 64px, 123px, 147px, 227px, 410px
- **Line height:** 0.90, 1.00, 1.09, 1.10, 1.20, 1.26, 1.33, 1.50, 1.78, 2.50, 3.00
- **Letter spacing:** -0.0450em at large sizes (410px), -0.0180em at smaller text, otherwise normal
- **Role:** Primary UI text for headings, body, buttons, navigation, and badges. Its variable weights and precise tracking create a dense, modern feel.

### Literata — Sub-headings and decorative text. Its lighter weights provide an elegant contrast to the primary typeface, hinting at a handcrafted quality. · `--font-literata`
- **Substitute:** Merriweather
- **Weights:** 200, 300, 500
- **Sizes:** 10px, 13px, 37px, 44px
- **Line height:** 1.00, 1.20, 1.50, 2.36
- **Role:** Sub-headings and decorative text. Its lighter weights provide an elegant contrast to the primary typeface, hinting at a handcrafted quality.

### DM Mono — Monospaced text for code snippets or technical details. · `--font-dm-mono`
- **Substitute:** ui-monospace
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.33
- **Role:** Monospaced text for code snippets or technical details.

### Arial — Fallback and utilitarian text, typically for small annotations or less prominent captions. Avoid direct usage when custom fonts are loaded. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400, 500
- **Sizes:** 8px, 12px
- **Line height:** 1.00, 1.10, 1.20
- **Role:** Fallback and utilitarian text, typically for small annotations or less prominent captions. Avoid direct usage when custom fonts are loaded.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.33 | — | `--text-body` |
| body-lg | 16px | 1.26 | — | `--text-body-lg` |
| subheading | 18px | 1.2 | — | `--text-subheading` |
| heading | 23px | 1.09 | -0.018px | `--text-heading` |
| heading-lg | 34px | 1.09 | -0.018px | `--text-heading-lg` |
| display-sm | 49px | 1 | -0.018px | `--text-display-sm` |
| display | 64px | 0.9 | -0.045px | `--text-display` |
| display-xl | 147px | 0.9 | -0.045px | `--text-display-xl` |
| display-hero | 410px | 0.9 | -0.045px | `--text-display-hero` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 9 | 9px | `--spacing-9` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 23 | 23px | `--spacing-23` |
| 24 | 24px | `--spacing-24` |
| 34 | 34px | `--spacing-34` |
| 36 | 36px | `--spacing-36` |
| 45 | 45px | `--spacing-45` |
| 77 | 77px | `--spacing-77` |
| 86 | 86px | `--spacing-86` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 36px |
| buttons | 36px |

### Layout

- **Section gap:** 45px
- **Card padding:** 18px
- **Element gap:** 18px

## Components

### Primary Action Button
**Role:** Filled button

Background: Rust Accent (#dc5000), text: Pitch Darkness (#100904). Padding: 14.4px vertical, 24px horizontal. Full pill shape with 36px radius.

### Secondary Action Button
**Role:** Filled button

Background: Faded Bark (#382416), text: Cork Dust (#ffedd7). Padding: 18px vertical, 36px horizontal. Full pill shape with 36px radius.

### Ghost Button (Orange Border)
**Role:** Outlined button

Background: Faded Bark (#382416), text: Cork Dust (#ffedd7), border: 1px solid Rust Accent (#dc5000). Padding: 18px vertical, 36px horizontal. Full pill shape with 36px radius.

### Light Ghost Button
**Role:** Outlined button

Background: Cork Dust (#ffedd7), text: Pitch Darkness (#100904), border: 1px solid Pitch Darkness (#100904). Padding: 14.4px vertical, 24px horizontal. Full pill shape with 36px radius.

### Form Input Field
**Role:** Input element

Background: transparent, text & border: Cork Dust (#ffedd7). Padding: 12px vertical, 18px horizontal. No border radius, sharp corners. Placeholder text uses Cork Dust (#ffedd7).

### Invisible Badge
**Role:** Informational tag

Transparent background, text: Cork Dust (#ffedd7). No padding or border radius. Used for minimal, content-adjacent labels.

## Do's and Don'ts

### Do
- Prioritize Pitch Darkness (#100904) for all background surfaces to maintain a deep, rich foundation.
- Use Cork Dust (#ffedd7) extensively for primary text and highlights against dark backgrounds, ensuring readability and contrast.
- Employ Rust Accent (#dc5000) sparingly as a functional highlight for primary actions and key interactive elements.
- Apply halyard-display-variable for all main headings and body text, varying weights for hierarchy and using negative letter-spacing for density.
- Ensure all buttons have a 36px border-radius to consistently achieve a full pill shape.
- Maintain an 18px elementGap for consistent spacing between distinct UI elements.
- Leverage the gradients, particularly the Rainbow Spectrum, exclusively for hero sections or large, impactful visual backgrounds to create a sense of wonder and depth.

### Don't
- Avoid using Rust Accent (#dc5000) for large blocks of text or decorative elements, as its vibrance should be reserved for actionable focus.
- Do not introduce additional bold, saturated colors beyond Rust Accent and Olive Green; the palette relies on controlled chromatic accents.
- Do not deviate from the full pill 36px button radius; inconsistent radii will break the tactile and rounded component aesthetic.
- Avoid excessive spacing or empty canvases; the design maintains a comfortable density, particularly with tight text alignment.
- Do not use generic system fonts when halyard-display-variable and Literata are available; the custom typography is crucial to the brand's identity.
- Do not apply shadows or complex elevation to UI elements; the system prioritizes flat surfaces and subtle texture over layered depth cues.

## Imagery

The site uses a mix of high-fidelity 3D product renders and abstract visual textures. Product imagery features the cork coaster as the central element, often floating or subtly angled against dark, minimal backgrounds, emphasizing its form and material. Photography is limited, focusing on high-key abstract shots of materials like cork or production-related tools, often with a slight yellow-orange tint. Iconography is minimal, using simple fills in Pitch Darkness or Cork Dust, contributing less to visual density and more to functional clarity. There are no lifestyle photos or complex illustrations; the imagery is precise, object-focused, and plays a supportive role to the core product narrative.

## Layout

The page primarily uses a full-bleed, dark background model that creates an immersive canvas. The hero section often features large, centered product renders over a dark gradient background, setting an immediate, dramatic tone. Content sections beneath follow a structured, often two-column layout with text-dominant blocks offset by product visuals, maintaining a comfortable density. Vertical section spacing is consistent, without hard dividers, relying on shifts in background tone or large product imagery to delineate new content areas. Navigation is minimal: a sticky top-right menu for primary links, and a small, fixed vertical 'ORYZO + MODEL' slider on the right edge, emphasizing product exploration.

## Agent Prompt Guide

Quick Color Reference: 
text: #ffedd7
background: #100904
border: #100904
accent: #dc5000
primary action: #dc5000 (filled action)

Example Component Prompts:
Create a Primary Action Button: #dc5000 background, #ffedd7 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
Create a secondary action button: Background #382416, text #ffedd7, 36px radius, 18px vertical padding, 36px horizontal padding, 'halyard-display-variable' font, weight 400.
Create a ghost button: Background #382416, text #ffedd7, 1px solid border #dc5000, 36px radius, 18px vertical padding, 36px horizontal padding, 'halyard-display-variable' font, weight 400.
Create an input field: Transparent background, text #ffedd7, 1px solid border #ffedd7, 0px radius, 12px vertical padding, 18px horizontal padding, 'halyard-display-variable' font, weight 400.
Create a hero headline: Text 'Cork Dust' (#ffedd7), 410px size, 'halyard-display-variable' font, weight 700, line-height 0.9, letter-spacing -0.045em on a 'Pitch Darkness' (#100904) background.

## Similar Brands

- **Apple (Product Pages)** — Focus on high-fidelity 3D product renders against stark, minimal backgrounds, allowing the product to be the hero.
- **Stripe** — Clean, dark mode UI with a focus on refined typography and a limited, high-contrast color palette for functional elements.
- **Linear** — Dark-themed interface, using subtle background variations and controlled accent colors, with a strong emphasis on precise typography and compact information display.
- **Figma (dark mode)** — Functional dark UI that uses a limited, yet effective, color palette to distinguish interactive elements without overwhelming the user.
- **Master & Dynamic (product marketing)** — Luxurious dark aesthetic, accentuating product details with sophisticated typography and rich textures.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-darkness: #100904;
  --color-cork-dust: #ffedd7;
  --color-rust-accent: #dc5000;
  --color-olive-green: #445231;
  --color-faded-bark: #382416;
  --color-aged-stone: #887b6d;
  --color-light-cork: #f6e0c6;
  --color-faint-hazel: #bbac97;
  --color-subtle-moss: #5d6c49;
  --color-grayscale-gray: #808080;
  --color-chalkboard-black: #000000;
  --color-deep-mocha: #40372e;
  --color-rainbow-spectrum: #e95000;
  --gradient-rainbow-spectrum: linear-gradient(rgb(253, 254, 237), rgb(255, 191, 2) 17%, rgb(233, 80, 14) 32%, rgb(205, 25, 125), rgb(140, 1, 156), rgb(37, 1, 135), rgb(3, 3, 16));

  /* Typography — Font Families */
  --font-halyard-display-variable: 'halyard-display-variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-literata: 'Literata', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.33;
  --text-body-lg: 16px;
  --leading-body-lg: 1.26;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading: 23px;
  --leading-heading: 1.09;
  --tracking-heading: -0.018px;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.09;
  --tracking-heading-lg: -0.018px;
  --text-display-sm: 49px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.018px;
  --text-display: 64px;
  --leading-display: 0.9;
  --tracking-display: -0.045px;
  --text-display-xl: 147px;
  --leading-display-xl: 0.9;
  --tracking-display-xl: -0.045px;
  --text-display-hero: 410px;
  --leading-display-hero: 0.9;
  --tracking-display-hero: -0.045px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-34: 34px;
  --spacing-36: 36px;
  --spacing-45: 45px;
  --spacing-77: 77px;
  --spacing-86: 86px;

  /* Layout */
  --section-gap: 45px;
  --card-padding: 18px;
  --element-gap: 18px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 22.5px;
  --radius-3xl: 36px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 36px;
  --radius-buttons: 36px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-darkness: #100904;
  --color-cork-dust: #ffedd7;
  --color-rust-accent: #dc5000;
  --color-olive-green: #445231;
  --color-faded-bark: #382416;
  --color-aged-stone: #887b6d;
  --color-light-cork: #f6e0c6;
  --color-faint-hazel: #bbac97;
  --color-subtle-moss: #5d6c49;
  --color-grayscale-gray: #808080;
  --color-chalkboard-black: #000000;
  --color-deep-mocha: #40372e;
  --color-rainbow-spectrum: #e95000;

  /* Typography */
  --font-halyard-display-variable: 'halyard-display-variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-literata: 'Literata', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.33;
  --text-body-lg: 16px;
  --leading-body-lg: 1.26;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --text-heading: 23px;
  --leading-heading: 1.09;
  --tracking-heading: -0.018px;
  --text-heading-lg: 34px;
  --leading-heading-lg: 1.09;
  --tracking-heading-lg: -0.018px;
  --text-display-sm: 49px;
  --leading-display-sm: 1;
  --tracking-display-sm: -0.018px;
  --text-display: 64px;
  --leading-display: 0.9;
  --tracking-display: -0.045px;
  --text-display-xl: 147px;
  --leading-display-xl: 0.9;
  --tracking-display-xl: -0.045px;
  --text-display-hero: 410px;
  --leading-display-hero: 0.9;
  --tracking-display-hero: -0.045px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-34: 34px;
  --spacing-36: 36px;
  --spacing-45: 45px;
  --spacing-77: 77px;
  --spacing-86: 86px;

  /* Border Radius */
  --radius-xl: 12px;
  --radius-2xl: 22.5px;
  --radius-3xl: 36px;
}
```
