# Overflow — Style Reference
> Vibrant digital canvas. A bright, expansive white canvas animated by soft, flowing color gradients.

**Theme:** light

Overflow's design evokes a sense of vibrant, dynamic clarity, like a digital canvas brought to life with soft pastels. The dominant white background keeps the focus on content, while subtle card shadows provide necessary dimensional separation. The playful use of gradient backgrounds infuses energy without overwhelming the UI, suggesting creativity within a structured environment. Varied border radii, from sharp 8px to soft 24px and even circular forms, add visual interest and a touch of approachability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#000000` | `--color-midnight-graphite` | Primary text, core UI elements, primary button background. |
| Ghost White | `#fafafc` | `--color-ghost-white` | Page backgrounds, prominent card surfaces. |
| Slate Gray | `#666666` | `--color-slate-gray` | Secondary text, descriptive body copy, subtle iconography. |
| Light Ash | `#dadce0` | `--color-light-ash` | Subtle border colors, separators in navigation. |
| Cloud Gray | `#f0f0f2` | `--color-cloud-gray` | Subtle card backgrounds, input fields, less prominent buttons. |
| Deep Violet | `#161637` | `--color-deep-violet` | Hero headlines, navigation links — deep, sophisticated color provides a calm anchor to the vibrant gradients. |
| Overflow Blue | `#0085e4` | `--color-overflow-blue` | Interactive links, specific highlights, subtle accents within illustrations. |
| Gradient Sky | `linear-gradient(127deg, rgb(114, 114, 251) 0px, rgb(184, 225, 255) 99%)` | `--color-gradient-sky` | Hero section background, large banners — creates an expansive, dreamlike atmosphere. |
| Gradient Ocean | `linear-gradient(90deg, rgb(0, 123, 255) 0px, rgb(98, 174, 255) 100%)` | `--color-gradient-ocean` | Promotional banners, subtle background shifts — signifies optimism and connection. |

## Tokens — Typography

### Inter — Primary typeface for all content. A workhorse sans-serif, its varied weights and precise letter-spacing create a sophisticated yet highly readable typographic hierarchy, from commanding headlines to fine print. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 550, 600, 700, 800
- **Sizes:** 12px, 14px, 15px, 16px, 20px, 24px, 26px, 32px, 48px, 56px
- **Line height:** 1.00, 1.07, 1.14, 1.15, 1.16, 1.20, 1.25, 1.33, 1.42, 1.43, 1.50, 1.57, 1.58, 1.60, 1.67, 1.75
- **Letter spacing:** -0.0250em at 56px, -0.0210em at 48px, -0.0190em at 32px, -0.0170em at 26px, -0.0120em at 24px, -0.0100em at 20px, -0.0080em at 16px, -0.0060em at 15px, -0.0050em at 14px, -0.0020em at 12px, 0.0080em at ~10px, 0.0130em at ~8px, 0.0710em at ~6px
- **Role:** Primary typeface for all content. A workhorse sans-serif, its varied weights and precise letter-spacing create a sophisticated yet highly readable typographic hierarchy, from commanding headlines to fine print.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.24px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.07px | `--text-body-sm` |
| subheading | 20px | 1.4 | -0.2px | `--text-subheading` |
| heading | 24px | 1.33 | -0.29px | `--text-heading` |
| heading-lg | 32px | 1.25 | -0.61px | `--text-heading-lg` |
| display | 48px | 1.15 | -1.01px | `--text-display` |
| display-lg | 56px | 1.07 | -1.4px | `--text-display-lg` |

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
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 96 | 96px | `--spacing-96` |
| 128 | 128px | `--spacing-128` |
| 156 | 156px | `--spacing-156` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px, 24px, 0px |
| inputs | 8px |
| buttons | 8px, 22px, 50% |
| navElements | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.08) 0px 4px 16px -8px` | `--shadow-md` |
| lg | `rgba(0, 0, 0, 0.08) 0px 8px 20px -7px` | `--shadow-lg` |

### Layout

- **Page max-width:** 1288px
- **Section gap:** 40px

## Components

### Primary Dark Button
**Role:** Main calls to action.

backgroundColor: #000000, color: #FFFFFF, borderRadius: 8px, padding: 15px 12.8px. Emphasizes action against a light background.

### Circular Icon Button
**Role:** Small, contained actions like 'play video' or 'more info'.

backgroundColor: #f2f2f4, color: #000000, borderRadius: 50%, padding: 15px 16px. Visually distinctive and playful for non-critical interactions.

### Ghost Card
**Role:** Content container without visual hierarchy emphasis.

backgroundColor: rgba(0, 0, 0, 0), borderRadius: 0px, padding: 40px. Used for sectioning content on the primary page background without additional styling.

### Light Gray Input
**Role:** Standard form input fields.

backgroundColor: rgba(0, 0, 0, 0.04), borderColor: #e8e8ea, borderRadius: 8px, padding: 16px. A subtle, unobtrusive field blending with the light theme.

### Subtle Gray Card
**Role:** Feature cards or content blocks needing slight background distinction.

backgroundColor: #f5f5f7, borderRadius: 24px, padding: 24px. Provides a visual break from the main white background without strong contrast or shadow.

## Do's and Don'ts

### Do
- Use Inter font family exclusively for all text elements.
- Prioritize Midnight Graphite (#000000) for primary text and Ghost White (#fafafc) for background surfaces to ensure optimal contrast.
- Apply Soft Shadow Cards (background: #FFFFFF, borderRadius: 24px, boxShadow: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px) to visually elevate key content blocks.
- Utilize either 8px or 24px borderRadius for most UI elements like buttons and cards, creating a consistent soft yet defined aesthetic.
- Introduce brand gradients like Gradient Sky (linear-gradient(127deg, rgb(114, 114, 251) 0px, rgb(184, 225, 255) 99%)) in hero sections or large thematic areas to add dynamic visual interest.
- Maintain consistent letter spacing as defined for Inter, especially negative values for larger text, to enhance readability and visual density: e.g., -0.0210em for 48px headlines.

### Don't
- Avoid using harsh or dark shadow values; adhere to the subtle, diffused style like rgba(0, 0, 0, 0.08) 0px 4px 16px -8px.
- Do not introduce new color hues; stick to the established palette of Deep Violet, Overflow Blue, and the neutral scale.
- Refrain from using square (0px) border radii for interactive elements; maintain a degree of roundness (at least 8px).
- Avoid excessive text decoration or capitalization; rely on weight and color changes for emphasis.
- Do not deviate from the defined Inter font scale, line heights, or letter spacing. These are critical for brand consistency and readability.

## Imagery

Imagery primarily features product screenshots with a focus on UI elements, often presented within white or subtle gray frames, sometimes overlapping for a dynamic effect. The screenshot treatment highlights the software's functionality, with minimal surrounding context. Photography is completely absent. Icons are typically monolinear or filled, matching the overall clean aesthetic. Abstract gradients serve as atmospheric backgrounds rather than explicit imagery. The density suggests a product-heavy site where the application itself is the hero, supported by graphical representations of its features.

## Layout

The layout is primarily a max-width 1288px container, centered, with occasional full-bleed sections. The hero section is full-bleed, featuring a striking gradient background with a large, centered headline and a prominent call-to-action. Subsequent sections alternate between the main white background and subtle gray backgrounds, with consistent vertical spacing. Content is arranged in flexible patterns, including centered stacks, multi-column feature grids (like the 3-column card grid for 'superpowers'), and fluid component arrangements. There's a clear visual rhythm established by the section breaks and card layouts, with ample breathing room. The navigation is a sticky top bar with a logo, primary links, and prominent download buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #000000
- Background (Page): #fafafc
- CTA Button (Background): #000000
- Accent (Links): #0085e4
- Card Background (Elevated): #FFFFFF

### 3-5 Example Component Prompts
1. Create a hero section: Gradient Sky background (linear-gradient(127deg, rgb(114, 114, 251) 0px, rgb(184, 225, 255) 99%)). Centered headline 'User flows done right' (Inter, 56px, 800 weight, -1.4px letter spacing, #161637 color). Underneath, a paragraph of body text (Inter, 20px, 400 weight, -0.2px letter spacing, Slate Gray #666666). Below that, a Primary Dark Button 'Download - free trial' (backgroundColor: #000000, color: #FFFFFF, borderRadius: 8px, padding: 15px 12.8px).
2. Generate a featured card: Soft Shadow Card (backgroundColor: #FFFFFF, borderRadius: 24px, boxShadow: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px, padding: 24px). Inside, a heading 'Discover your new superpowers' (Inter, 32px, 700 weight, -0.61px letter spacing, #000000 color). Add a paragraph of body copy (Inter, 15px, 400 weight, -0.09px letter spacing, #666666 color).
3. Design a navigation bar: Ghost White background (#fafafc), padding 12px vertical. Include a 'Sign in' link (Inter, 16px, 500 weight, -0.13px letter spacing, #161637). Next to it, a Primary Dark Button 'Download for free' (backgroundColor: #000000, color: #FFFFFF, borderRadius: 8px, padding: 15px 12.8px).

## Similar Brands

- **Figma** — Clean, product-focused UI with an emphasis on clarity, similar use of soft card shadows, and interactive illustrations.
- **Miro** — White canvas aesthetic, digital-first illustration style, and subtle use of brand colors for interactive elements.
- **Notion** — Minimalist layout, strong typographic hierarchy on a light background, and functional UI elements taking precedence over decorative imagery.
- **Linear** — High-contrast text on light backgrounds, measured use of rounded corners, and a focus on essential UI components.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-ghost-white: #fafafc;
  --color-slate-gray: #666666;
  --color-light-ash: #dadce0;
  --color-cloud-gray: #f0f0f2;
  --color-deep-violet: #161637;
  --color-overflow-blue: #0085e4;
  --color-gradient-sky: #7272fb;
  --gradient-gradient-sky: linear-gradient(127deg, rgb(114, 114, 251) 0px, rgb(184, 225, 255) 99%);
  --color-gradient-ocean: #007bff;
  --gradient-gradient-ocean: linear-gradient(90deg, rgb(0, 123, 255) 0px, rgb(98, 174, 255) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.07px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.29px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.61px;
  --text-display: 48px;
  --leading-display: 1.15;
  --tracking-display: -1.01px;
  --text-display-lg: 56px;
  --leading-display-lg: 1.07;
  --tracking-display-lg: -1.4px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w550: 550;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

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
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-156: 156px;
  --spacing-160: 160px;

  /* Layout */
  --page-max-width: 1288px;
  --section-gap: 40px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-full: 139px;

  /* Named Radii */
  --radius-cards: 8px, 24px, 0px;
  --radius-inputs: 8px;
  --radius-buttons: 8px, 22px, 50%;
  --radius-navelements: 12px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px;
  --shadow-lg: rgba(0, 0, 0, 0.08) 0px 8px 20px -7px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #000000;
  --color-ghost-white: #fafafc;
  --color-slate-gray: #666666;
  --color-light-ash: #dadce0;
  --color-cloud-gray: #f0f0f2;
  --color-deep-violet: #161637;
  --color-overflow-blue: #0085e4;
  --color-gradient-sky: #7272fb;
  --color-gradient-ocean: #007bff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.07px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.33;
  --tracking-heading: -0.29px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.61px;
  --text-display: 48px;
  --leading-display: 1.15;
  --tracking-display: -1.01px;
  --text-display-lg: 56px;
  --leading-display-lg: 1.07;
  --tracking-display-lg: -1.4px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-96: 96px;
  --spacing-128: 128px;
  --spacing-156: 156px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-full: 139px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.08) 0px 4px 16px -8px;
  --shadow-lg: rgba(0, 0, 0, 0.08) 0px 8px 20px -7px;
}
```
