# Ameba — Style Reference
> Midnight Command Center

**Theme:** mixed

Ameba combines a dark, deep blue aesthetic with moments of crisp white UI, creating a sense of corporate sophistication and data-driven insight. Typography is highly refined, leveraging custom fonts with precise letter-spacing for a technical, almost blueprint-like clarity against the rich backdrops. Component surfaces are unadorned, relying on subtle borders and rounded corners for definition, with a single vivid teal accent providing functional highlights rather than decorative flourishes.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `radial-gradient(circle, rgb(6, 16, 90), rgb(0, 5, 46) 79%)` | `--color-midnight-ink` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color; Dramatic background for hero sections and key graphical elements, suggesting depth and data visualization |
| Arctic Mist | `#ffffff` | `--color-arctic-mist` | Text on dark backgrounds, primary page background for light sections, and outlines for ghost buttons on dark surfaces. Provides sharp contrast |
| Slate Shadow | `#6b6b83` | `--color-slate-shadow` | Subtle border outlines for ghost interactive elements on dark backgrounds, secondary text on dark. Hints at interactivity without starkness |
| Steel Gray | `#4f5166` | `--color-steel-gray` | Tertiary text for body copy and helper text on dark backgrounds, faint borders |
| Deep Blue Static | `#0428cb` | `--color-deep-blue-static` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color |
| Lagoon Spark | `#34fcff` | `--color-lagoon-spark` | Active states, highlight indicators, iconography on dark backgrounds for a sharp, technical accent. It's the primary functional accent color |
| Light Mauve Aura | `#afb4db` | `--color-light-mauve-aura` | Subtle decorative borders, low-key visual separators against dark backgrounds. Creates a gentle visual lift |
| Platinum Mist | `#dbdcdf` | `--color-platinum-mist` | Hairline separators and subtle borders in light sections |
| Frost Gleam | `#e9e9f3` | `--color-frost-gleam` | Subtle border outlines for light-themed UI elements, providing minimal definition |
| Dark Charcoal | `#222222` | `--color-dark-charcoal` | Text on light backgrounds, ghost button borders and text on light surfaces |

## Tokens — Typography

### F37 Bolton Book — F37 Bolton Book — detected in extracted data but not described by AI · `--font-f37-bolton-book`
- **Weights:** 300, 400
- **Sizes:** 13px, 27px, 35px, 54px, 59px
- **Line height:** 1.26, 1.3, 1.38, 1.41, 1.48, 1.54
- **Letter spacing:** -0.019, -0.014, -0.009, -0.008, 0.086
- **Role:** F37 Bolton Book — detected in extracted data but not described by AI

### Open Suace Sans — General body text and interface labels, ensuring high readability and a clean, modern feel across a range of sizes. · `--font-open-suace-sans`
- **Substitute:** Inter
- **Weights:** 300, 400, 700
- **Sizes:** 13px, 14px, 16px, 18px, 20px
- **Line height:** 1.43, 1.44, 1.50, 1.54, 1.56, 1.57, 1.63, 1.65, 1.86
- **Role:** General body text and interface labels, ensuring high readability and a clean, modern feel across a range of sizes.

### IBM Plex Mono — Code snippets, timestamps, and compact data displays, providing a technical, fixed-width clarity with generous letter-spacing for legibility in small type. · `--font-ibm-plex-mono`
- **Substitute:** Fira Code
- **Weights:** 400
- **Sizes:** 11px, 13px
- **Line height:** 1.38, 1.82
- **Letter spacing:** 0.077em at 11px, 0.086em at 13px
- **Role:** Code snippets, timestamps, and compact data displays, providing a technical, fixed-width clarity with generous letter-spacing for legibility in small type.

### F37 Bolton — Headings and key callouts. The light weights (300, 400) combined with negative letter-spacing for larger sizes create a distinctive, sophisticated, and impactful presence without being overly bold, conveying authority through restraint. Normal letter spacing at 13px. · `--font-f37-bolton`
- **Substitute:** DM Sans
- **Weights:** 400
- **Sizes:** 27px, 33px, 40px
- **Line height:** 1.20, 1.30
- **Letter spacing:** -0.019em at 59px, -0.014em at 35px, -0.009em at 27px, 0.086em at 13px
- **Role:** Headings and key callouts. The light weights (300, 400) combined with negative letter-spacing for larger sizes create a distinctive, sophisticated, and impactful presence without being overly bold, conveying authority through restraint. Normal letter spacing at 13px.

### F37 Bolton Medium — F37 Bolton Medium — detected in extracted data but not described by AI · `--font-f37-bolton-medium`
- **Weights:** 400, 700
- **Sizes:** 14px, 16px
- **Line height:** 0.81, 1.43
- **Letter spacing:** 0.05
- **Role:** F37 Bolton Medium — detected in extracted data but not described by AI

### Open Sauce Sans Medium — Open Sauce Sans Medium — detected in extracted data but not described by AI · `--font-open-sauce-sans-medium`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **Role:** Open Sauce Sans Medium — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.38 | 0.077px | `--text-caption` |
| heading-sm | 27px | 1.2 | -0.009px | `--text-heading-sm` |
| heading | 35px | 1.38 | -0.014px | `--text-heading` |
| display | 59px | 1.26 | -0.019px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 21 | 21px | `--spacing-21` |
| 23 | 23px | `--spacing-23` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 43 | 43px | `--spacing-43` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 196 | 196px | `--spacing-196` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| default | 4px |

### Layout

- **Section gap:** 80px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Ghost Navigation Button (Dark)
**Role:** Navigation, secondary actions on dark backgrounds.

Transparent background with 'Arctic Mist' #ffffff text and border. No border-radius. Padding 20px all sides. Uses Open Suace Sans Regular.

### Ghost Navigation Button (Light)
**Role:** Navigation, secondary actions on light backgrounds.

Transparent background with 'Dark Charcoal' #222222 text and border. No border-radius. Padding 20px all sides. Uses Open Suace Sans Regular.

### Schedule Demo Button (Filled - Navy)
**Role:** Primary Call to Action for dark sections.

Filled with 'Deep Blue Static' #0428cb background. Text in 'Arctic Mist' #ffffff. 4px border-radius. Padding 20px top/bottom, 40px left/right. Uses Open Suace Sans Regular.

### Informational Card (Dark)
**Role:** Displaying data snippets, event summaries, or short notifications.

Background 'Midnight Ink' #00052e. 8px border-radius. No box shadow. Internal padding varies (e.g., 10px, 15px, 16px, 20px).

### Highlight Tag (Teal Border)
**Role:** Drawing attention to specific statuses or meta-information.

Transparent background. Border 'Lagoon Spark' #34fcff. Text color 'Lagoon Spark' #34fcff. 4px border-radius. Small internal padding.

## Do's and Don'ts

### Do
- Use 'Midnight Ink' #00052 as the primary background for dark sections and component surfaces to establish the core visual personality.
- Apply 'Arctic Mist' #ffffff for all primary text on dark backgrounds and for page backgrounds on light sections to ensure sharp contrast.
- Implement F37 Bolton for all headings, leveraging weights 300 or 400 and negative letter-spacing for large sizes, as a signature typographic style.
- Utilize 'Lagoon Spark' #34fcff as the single vivid accent color for interactive states, key iconography, and small highlight elements.
- Maintain a comfortable density with element spacing often at '10px' and section gaps at '80px' to provide breathing room.
- Apply an 8px border-radius uniformly to all card-like elements for gentle softening of edges, and 4px for smaller interactive elements.
- Employ IBM Plex Mono for all technical details, timestamps, or code-like text, utilizing its generous letter-spacing feature for legibility.

### Don't
- Avoid using multiple chromatic colors; restrict accent colors primarily to 'Lagoon Spark' #34fcff to maintain a focused palette.
- Do not use heavy box-shadows; prefer minimal elevation or subtle border treatments for element distinction.
- Refrain from using common system fonts; the custom typography is crucial for the brand's unique technical and sophisticated feel.
- Never introduce additional decorative gradients beyond the established 'Blue Orbit Gradient'; maintain a largely flat and dark UI.
- Do not vary line-height significantly from the specified values; precise line-heights are critical for typographic rhythm.
- Avoid generic button styles; stick to ghost buttons or filled buttons with the specified colors and radii for consistency.
- Do not use dark text on dark backgrounds except where intentional low-contrast effects are part of specific component designs (e.g., helper text on cards).

## Imagery

The visual language primarily uses abstract, energetic graphics and product screenshots within contained frames. Imagery serves a decorative and explanatory role rather than social proof or lifestyle. The hero section features a dynamic, abstract blue radial gradient suggestive of data and global connections, serving as an atmospheric backdrop. Product screenshots are clean, showcasing the UI directly within simulated device frames, often with a subtle white background in contrast to the dark page. Iconography is minimalist, outlined, and uses the 'Lagoon Spark' accent color to highlight functionality, maintaining a lightweight feel. Imagery density is moderate, carefully balancing UI with explanatory text.

## Layout

The page primarily uses a max-width contained layout, centered at around 1200px, but features full-bleed sections for dramatic impact. The hero section is full-bleed, dark-themed, with a centered headline over the 'Blue Orbit Gradient' background, aiming for immediate visual impact. Subsequent sections alternate between dark ('Midnight Ink') and light ('Arctic Mist') backgrounds, creating a clear vertical rhythm. Content is arranged in alternating two-column layouts (text left, image right / image left, text right) or centered stacks for features and testimonials, fostering engagement. Card grids are used for feature presentation, typically in three columns. Vertical spacing is comfortable, with '80px' section gaps. Navigation is a persistent top bar featuring ghost buttons and a distinct 'Schedule a Demo' button, maintaining accessibility throughout the scroll.

## Agent Prompt Guide

Quick Color Reference:
- text: #ffffff
- background: #00052e
- border: #6b6b83
- accent: #34fcff
- primary action: no distinct CTA color

Example Component Prompts:
- Create a dark hero section: background 'Midnight Ink' #00052e with 'Blue Orbit Gradient'. Centered headline 'Integrate, automate and elevate your supply chain' at 59px F37 Bolton weight 300, #ffffff, letter-spacing -0.019em. Below it, a 'Schedule a Demo' button: #0428cb background, #ffffff text, 4px radius, 20px 40px padding.
- Design an informational card for dark theme: 'Midnight Ink' #00052e background, 8px border-radius, default padding 20px all sides. Main text in 'Arctic Mist' #ffffff, secondary text 'Slate Shadow' #6b6b83 at 14px Open Suace Sans weight 400.
- Construct a ghost navigation item: 'Arctic Mist' #ffffff text, 'Arctic Mist' #ffffff border, 20px padding (all sides). Text in Open Suace Sans Regular 16px.
- Create a small data badge: transparent background, 'Lagoon Spark' #34fcff border (1px), 'Lagoon Spark' #34fcff text. 4px border-radius, 4px internal horizontal padding. Text in IBM Plex Mono 11px, letter-spacing 0.077em.

## Similar Brands

- **Linear** — Uses dark backgrounds, precise typography with subtle color accents, and a focus on clean, functional UI over heavy decoration.
- **Vercel** — Employs a sophisticated dark theme, high contrast typography, and careful use of a single, vibrant accent color for interactive elements.
- **Coda.io** — Combines a professional, tool-like aesthetic with meticulous typography and a clear separation of content and UI using subtle borders and shadows.
- **Retool** — Features a strong dark mode UI, data-heavy displays, and a focus on clarity through high contrast and minimal, functional design elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #00052e;
  --gradient-midnight-ink: radial-gradient(circle, rgb(6, 16, 90), rgb(0, 5, 46) 79%);
  --color-arctic-mist: #ffffff;
  --color-slate-shadow: #6b6b83;
  --color-steel-gray: #4f5166;
  --color-deep-blue-static: #0428cb;
  --color-lagoon-spark: #34fcff;
  --color-light-mauve-aura: #afb4db;
  --color-platinum-mist: #dbdcdf;
  --color-frost-gleam: #e9e9f3;
  --color-dark-charcoal: #222222;

  /* Typography — Font Families */
  --font-f37-bolton-book: 'F37 Bolton Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-suace-sans: 'Open Suace Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-f37-bolton: 'F37 Bolton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-f37-bolton-medium: 'F37 Bolton Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-sauce-sans-medium: 'Open Sauce Sans Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.38;
  --tracking-caption: 0.077px;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.009px;
  --text-heading: 35px;
  --leading-heading: 1.38;
  --tracking-heading: -0.014px;
  --text-display: 59px;
  --leading-display: 1.26;
  --tracking-display: -0.019px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-43: 43px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-196: 196px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-default: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #00052e;
  --color-arctic-mist: #ffffff;
  --color-slate-shadow: #6b6b83;
  --color-steel-gray: #4f5166;
  --color-deep-blue-static: #0428cb;
  --color-lagoon-spark: #34fcff;
  --color-light-mauve-aura: #afb4db;
  --color-platinum-mist: #dbdcdf;
  --color-frost-gleam: #e9e9f3;
  --color-dark-charcoal: #222222;

  /* Typography */
  --font-f37-bolton-book: 'F37 Bolton Book', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-suace-sans: 'Open Suace Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-f37-bolton: 'F37 Bolton', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-f37-bolton-medium: 'F37 Bolton Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-open-sauce-sans-medium: 'Open Sauce Sans Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.38;
  --tracking-caption: 0.077px;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.009px;
  --text-heading: 35px;
  --leading-heading: 1.38;
  --tracking-heading: -0.014px;
  --text-display: 59px;
  --leading-display: 1.26;
  --tracking-display: -0.019px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-21: 21px;
  --spacing-23: 23px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-43: 43px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-196: 196px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
}
```
