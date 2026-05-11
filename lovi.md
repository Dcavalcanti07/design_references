# Lovi — Style Reference
> violet-tinted laboratory under soft light — precision meets pastel.

**Theme:** light

Lovi evokes a sense of modern, approachable science through its minimalist aesthetic and a central playful violet. The design leverages soft, near-white backgrounds with subtle shadow-derived depth, creating an airy and calming user experience. Unexpectedly fluid headline letter-spacing and a mix of sharp and organic radii define its distinct contemporary feel, balancing clinical precision with user-friendly warmth.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Violet | `#151581` | `--color-midnight-violet` | Primary brand accent, used for prominent headlines, interactive text links, and key graphical elements. Its deep saturation provides a focal point against the light neutrals. |
| Cloud White | `#ffffff` | `--color-cloud-white` | Dominant page background, card surfaces, and text on darker elements, creating an expansive, clean canvas. |
| Obsidian Text | `#000000` | `--color-obsidian-text` | Primary body text and headings, providing high contrast against light backgrounds. |
| Shadow Gray | `#292824` | `--color-shadow-gray` | Subtle text for secondary information and iconography, offering softer contrast than Obsidian. |
| Onyx Outline | `#a9a9a7` | `--color-onyx-outline` | Less prominent text for descriptive content and some borders, sitting in the mid-range of the neutral scale. |
| Silver Mist | `#949392` | `--color-silver-mist` | Muted text, often for descriptive copy or less emphasized details. |
| Lavender Haze | `#a1a1cd` | `--color-lavender-haze` | Muted violet used for secondary text links or less critical elements, adding a subtle brand touch. |
| Pale Gray | `#f6f6fa` | `--color-pale-gray` | Background for certain interactive elements and sections, providing a slight visual separation from Cloud White. |
| Almond Dust | `#f6f5f4` | `--color-almond-dust` | Subtle background for specific button variants, differentiating them from other interactive elements. |
| Warm Gray | `#d6d6d6` | `--color-warm-gray` | Border colors and subtle dividers, providing minimal visual interruption. |
| Vivid Sky | `#5465ff` | `--color-vivid-sky` | Accent for certain text elements or graphical components, adding a bright, energetic touch. |
| Deep Rose | `#f25c75` | `--color-deep-rose` | Semantic use for alerts or specific product features, providing a warm, contrasting accent. |
| Fresh Green | `#00bb76` | `--color-fresh-green` | Semantic use for positive indicators or success states, like review ratings. |
| Radiant Pink | `#e6aeff` | `--color-radiant-pink` | Graphical element fill, appearing in illustrations and gradients. |
| Blush Gradient | `linear-gradient(270deg, rgba(102, 127, 255, 0.8) 19.614%, rgba(206, 162, 255, 0.8) 50.0389%, rgba(255, 133, 177, 0.8) 86.0908%)` | `--color-blush-gradient` | Illustrative gradient background, creating a soft, ethereal mood. |
| Mint Gradient | `linear-gradient(rgb(87, 222, 152) 0%, rgb(68, 183, 123) 100%)` | `--color-mint-gradient` | Illustrative gradient for graphical elements, suggesting freshness and nature. |
| Conic Aura | `conic-gradient(rgb(255, 255, 255) 0deg, rgb(235, 189, 215) 90.8108deg, rgb(196, 189, 228) 115.217deg, rgb(183, 230, 247) 178.144deg, rgb(233, 224, 185) 217.297deg, rgb(235, 195, 188) 284.202deg, rgb(255, 255, 255) 360deg)` | `--color-conic-aura` | Complex conic gradient used for abstract background elements, providing a multi-hued, soft glow. |
| Emerald Radial | `radial-gradient(75% 65.625% at 37.4% 50%, rgb(15, 217, 126) 0%, rgba(255, 255, 255, 0) 100%)` | `--color-emerald-radial` | Radial gradient for spot illustrations, creating a focused, soft-edged highlight. |

## Tokens — Typography

### ES Rebond Grotesque — Display headlines and prominent titles. Its custom 'ss02' feature likely adds a distinct character, while its tight line heights and negative letter-spacing create a dense, impactful presence. · `--font-es-rebond-grotesque`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 14px, 16px, 20px, 22px, 28px, 32px, 44px, 48px
- **Line height:** 0.91, 0.92, 1.05, 1.06, 1.09, 1.14, 1.20, 1.25
- **Letter spacing:** -0.042, -0.036, -0.031, -0.023
- **OpenType features:** `"ss02"`
- **Role:** Display headlines and prominent titles. Its custom 'ss02' feature likely adds a distinct character, while its tight line heights and negative letter-spacing create a dense, impactful presence.

### ES Rebond Grotesque Medium — Subheadings and emphasized body text. Though labeled 'Medium', its 400 weight paired with distinctive line heights and letter spacing suggests a visual presence akin to a medium weight in other families. · `--font-es-rebond-grotesque-medium`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 14px, 16px, 20px, 22px
- **Line height:** 1.09, 1.14, 1.20, 1.25
- **Letter spacing:** -0.045, -0.036, -0.031, -0.025
- **Role:** Subheadings and emphasized body text. Though labeled 'Medium', its 400 weight paired with distinctive line heights and letter spacing suggests a visual presence akin to a medium weight in other families.

### Inter — General body text, links, and various UI elements. Its broad range of weights and granular letter-spacing control allow for fine-tuned information hierarchy. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 16px, 18px, 24px
- **Line height:** 1.11, 1.25, 1.29, 1.33, 1.38, 1.43
- **Letter spacing:** -0.062, -0.044, -0.042, -0.04, -0.036, -0.031, -0.029, -0.028, -0.025, -0.019
- **Role:** General body text, links, and various UI elements. Its broad range of weights and granular letter-spacing control allow for fine-tuned information hierarchy.

### Inter-Medium — Specific emphasized text blocks and UI labels, where its distinct letter-spacing provides visual differentiation from regular Inter. · `--font-inter-medium`
- **Substitute:** Inter Medium
- **Weights:** 500
- **Sizes:** 14px, 16px, 20px, 24px
- **Line height:** 1.20, 1.25, 1.29
- **Letter spacing:** -0.071, -0.05, -0.044, -0.042, -0.037, -0.031
- **Role:** Specific emphasized text blocks and UI labels, where its distinct letter-spacing provides visual differentiation from regular Inter.

### Geist — Tertiary body text and notes. Its specific font-feature-settings ('dlig', 'ss01', 'ss02', 'ss06') hint at a distinctive stylistic flavor for nuanced body copy, giving it a more bespoke feel than a standard sans-serif. · `--font-geist`
- **Substitute:** Geist
- **Weights:** 400
- **Sizes:** 16px, 18px
- **Line height:** 1.22, 1.38
- **Letter spacing:** -0.031, -0.028
- **OpenType features:** `"dlig", "ss01", "ss02", "ss06"`
- **Role:** Tertiary body text and notes. Its specific font-feature-settings ('dlig', 'ss01', 'ss02', 'ss06') hint at a distinctive stylistic flavor for nuanced body copy, giving it a more bespoke feel than a standard sans-serif.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.25 | — | `--text-body-sm` |
| body | 16px | 1.29 | — | `--text-body` |
| subheading | 20px | 1.2 | — | `--text-subheading` |
| heading | 28px | 0.91 | -1.18px | `--text-heading` |
| heading-lg | 32px | 0.92 | -1.44px | `--text-heading-lg` |
| display | 48px | 1.06 | -1.1px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 104 | 104px | `--spacing-104` |
| 112 | 112px | `--spacing-112` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 8px |
| cards | 24px |
| large | 40px |
| inputs | 16px |
| buttons | 48px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(36, 36, 41, 0.07) 0px 8px 34px 0px, rgba(37, 36, 41,...` | `--shadow-xl` |

### Layout

- **Section gap:** 80px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Call to Action Button
**Role:** Main user action button

Rounded pill shape with backgroundColor: #f6f5f4, text color: #151581, borderTopColor: #151581, borderRadius: 48px, padding: 32px all around. This implies a very large, soft-edged button with a clear brand accent.

### Secondary Call to Action Button
**Role:** Less prominent interactive element

backgroundColor: #FFFFFF, text color: #151581, borderTopColor: #151581, borderRadius: 24px, padding: 32px vertical, 28px horizontal. Slightly smaller radius and padding than the primary CTA, offering visual hierarchy.

### Ghost Accent Button
**Role:** Subtle interactive element, often for supplementary actions or links

backgroundColor: rgba(255, 255, 255, 0.2), text color: #151581, borderTopColor: #151581, borderRadius: 56px, padding: 6px vertical, 10px-12px horizontal. A highly transparent, highly rounded button used for minimal visual impedance, often for small tags or informational accents.

## Do's and Don'ts

### Do
- Use Midnight Violet (#151581) exclusively for primary interactive states and headline accents.
- Apply ES Rebond Grotesque with its specific letter-spacing for all headings to maintain the fluid, typographic tension.
- Utilize Cloud White (#ffffff) as the default background for all main page content and card surfaces.
- Maintain high contrast for body text by using Obsidian Text (#000000) or Shadow Gray (#292824) on light backgrounds.
- Implement 48px border-radius for all primary buttons, and 24px for secondary buttons or cards, ensuring consistent softness.
- Leverage the subtle shadow rgba(36, 36, 41, 0.07) 0px 8px 34px 0px for elevated cards and review containers.

### Don't
- Do not introduce new primary font families; adhere strictly to ES Rebond Grotesque, Inter, and Geist.
- Avoid using highly saturated accent colors in large blocks; reserve them for small icons, text accents, or controlled gradient uses.
- Do not deviate from the established spacing scale (multiples of 4px) to ensure consistent content density.
- Avoid hard, sharp corners; all significant UI elements should incorporate a border radius of at least 8px.
- Do not use dark backgrounds for main content sections; the system is built around a predominantly light theme.
- Do not apply shadows indiscriminately; reserve them for intentional elevation of components like cards and modals, using the defined subtle shadow style.

## Elevation

- **Review Card:** `rgba(36, 36, 41, 0.07) 0px 8px 34px 0px, rgba(37, 36, 41, 0.09) 0px 1px 2px 0px`
- **Other elevated containers (e.g., modals, tooltips):** `rgba(36, 36, 41, 0.07) 0px 8px 34px 0px, rgba(37, 36, 41, 0.09) 0px 1px 2px 0px`

## Imagery

Imagery primarily consists of high-quality product photography (a person's face interacting with a mobile app) and professional portrait photography for team members. Product shots are contained within device mockups or cropped precisely, often appearing isolated against the clean background, creating a focused, almost clinical presentation. Illustrations are abstract and colorful, featuring vivid and muted pastel gradients (Blush Gradient, Mint Gradient, Conic Aura) with soft, organic shapes that act as decorative atmosphere without direct explanatory content. Icons are minimal, often line-based or small filled shapes, using brand accent colors (#151581) or vivid semantic colors (Fresh Green #00bb76, Deep Rose #f25c75). Imagery density is moderate, used to break up text-heavy sections or highlight key features without overwhelming the clean aesthetic.

## Layout

The site employs a max-width contained layout, with content centered on the page. The hero section uses a full-width background, but the primary headline and visual elements are contained. A prominent pattern is the alternation of content blocks: a large centered headline and subtext often leads into a section with a large image/illustration paired with text, sometimes in a 2-column arrangement. Review sections feature a grid of cards (likely 3-column on desktop). Vertical rhythm is maintained by consistent section gaps, creating definition between content blocks. Navigation is a simple top bar with a logo and an app store download button, suggesting a minimalist and direct user journey.

## Agent Prompt Guide

**Quick Color Reference:**
- Text: #000000 (Black)
- Background: #ffffff (Cloud White)
- CTA: #f6f5f4 (Almond Dust) with #151581 (Midnight Violet) text
- Border: #d6d6d6 (Warm Gray)
- Accent: #151581 (Midnight Violet)

**3-5 Example Component Prompts:**
1.  **Create a Hero Section:** Use Cloud White background. Headline (ES Rebond Grotesque, 48px, 0.91 line-height, #000000, letter-spacing -2.3px). Subtext (Inter, 18px, 1.33 line-height, Shadow Gray #292824). Centered prominent button as 'Primary Call to Action Button'.
2.  **Generate a Review Card:** White background, borderRadius 24px, apply the subtle shadow 'rgba(36, 36, 41, 0.07) 0px 8px 34px, rgba(37, 36, 41, 0.09) 0px 1px 2px'. Content inside should use Inter body text (#000000) and Fresh Green (#00bb76) for star ratings.
3.  **Design an Award Badge:** Use Almond Dust (#f6f5f4) background, borderRadius 16px. Text should be ES Rebond Grotesque Medium (16px, #151581, 1.2 line-height, letter-spacing -0.496px) with an accompanying icon.
4.  **Compose a Feature Point:** Body text (Geist, 16px, 1.22 line-height, #000000, letter-spacing -0.496px) with an inline Vivid Sky (#5465ff) text accent. Prepend with a small icon, potentially using Radiant Pink (#e6aeff) as a fill color.

## Similar Brands

- **Glossier** — Similar use of clean, minimalist aesthetic with intentional pops of color and rounded, approachable forms.
- **Oura Ring** — Combines science/tech product with a clean, high-end, approachable visual language and subtle gradients.
- **Calm** — Employs soft color palettes, ample white space, and gentle typography to create a sense of tranquility and ease.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-violet: #151581;
  --color-cloud-white: #ffffff;
  --color-obsidian-text: #000000;
  --color-shadow-gray: #292824;
  --color-onyx-outline: #a9a9a7;
  --color-silver-mist: #949392;
  --color-lavender-haze: #a1a1cd;
  --color-pale-gray: #f6f6fa;
  --color-almond-dust: #f6f5f4;
  --color-warm-gray: #d6d6d6;
  --color-vivid-sky: #5465ff;
  --color-deep-rose: #f25c75;
  --color-fresh-green: #00bb76;
  --color-radiant-pink: #e6aeff;
  --color-blush-gradient: #c6a2ff;
  --gradient-blush-gradient: linear-gradient(270deg, rgba(102, 127, 255, 0.8) 19.614%, rgba(206, 162, 255, 0.8) 50.0389%, rgba(255, 133, 177, 0.8) 86.0908%);
  --color-mint-gradient: #57de98;
  --gradient-mint-gradient: linear-gradient(rgb(87, 222, 152) 0%, rgb(68, 183, 123) 100%);
  --color-conic-aura: #ebbdde;
  --gradient-conic-aura: conic-gradient(rgb(255, 255, 255) 0deg, rgb(235, 189, 215) 90.8108deg, rgb(196, 189, 228) 115.217deg, rgb(183, 230, 247) 178.144deg, rgb(233, 224, 185) 217.297deg, rgb(235, 195, 188) 284.202deg, rgb(255, 255, 255) 360deg);
  --color-emerald-radial: #0fd97;
  --gradient-emerald-radial: radial-gradient(75% 65.625% at 37.4% 50%, rgb(15, 217, 126) 0%, rgba(255, 255, 255, 0) 100%);

  /* Typography — Font Families */
  --font-es-rebond-grotesque: 'ES Rebond Grotesque', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-es-rebond-grotesque-medium: 'ES Rebond Grotesque Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-medium: 'Inter-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.29;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 28px;
  --leading-heading: 0.91;
  --tracking-heading: -1.18px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.92;
  --tracking-heading-lg: -1.44px;
  --text-display: 48px;
  --leading-display: 1.06;
  --tracking-display: -1.1px;

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
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-104: 104px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 36px;
  --radius-3xl-5: 40px;
  --radius-3xl-6: 44px;
  --radius-full: 48px;
  --radius-full-2: 56px;
  --radius-full-3: 60px;
  --radius-full-4: 64px;
  --radius-full-5: 70px;
  --radius-full-6: 80px;
  --radius-full-7: 100px;
  --radius-full-8: 300px;

  /* Named Radii */
  --radius-tags: 8px;
  --radius-cards: 24px;
  --radius-large: 40px;
  --radius-inputs: 16px;
  --radius-buttons: 48px;

  /* Shadows */
  --shadow-xl: rgba(36, 36, 41, 0.07) 0px 8px 34px 0px, rgba(37, 36, 41, 0.09) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-violet: #151581;
  --color-cloud-white: #ffffff;
  --color-obsidian-text: #000000;
  --color-shadow-gray: #292824;
  --color-onyx-outline: #a9a9a7;
  --color-silver-mist: #949392;
  --color-lavender-haze: #a1a1cd;
  --color-pale-gray: #f6f6fa;
  --color-almond-dust: #f6f5f4;
  --color-warm-gray: #d6d6d6;
  --color-vivid-sky: #5465ff;
  --color-deep-rose: #f25c75;
  --color-fresh-green: #00bb76;
  --color-radiant-pink: #e6aeff;
  --color-blush-gradient: #c6a2ff;
  --color-mint-gradient: #57de98;
  --color-conic-aura: #ebbdde;
  --color-emerald-radial: #0fd97;

  /* Typography */
  --font-es-rebond-grotesque: 'ES Rebond Grotesque', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-es-rebond-grotesque-medium: 'ES Rebond Grotesque Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-medium: 'Inter-Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.25;
  --text-body: 16px;
  --leading-body: 1.29;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --text-heading: 28px;
  --leading-heading: 0.91;
  --tracking-heading: -1.18px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 0.92;
  --tracking-heading-lg: -1.44px;
  --text-display: 48px;
  --leading-display: 1.06;
  --tracking-display: -1.1px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-104: 104px;
  --spacing-112: 112px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 36px;
  --radius-3xl-5: 40px;
  --radius-3xl-6: 44px;
  --radius-full: 48px;
  --radius-full-2: 56px;
  --radius-full-3: 60px;
  --radius-full-4: 64px;
  --radius-full-5: 70px;
  --radius-full-6: 80px;
  --radius-full-7: 100px;
  --radius-full-8: 300px;

  /* Shadows */
  --shadow-xl: rgba(36, 36, 41, 0.07) 0px 8px 34px 0px, rgba(37, 36, 41, 0.09) 0px 1px 2px 0px;
}
```
