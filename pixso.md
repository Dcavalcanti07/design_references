# Pixso — Style Reference
> Architectural Blueprint on White Marble. This system feels like designs precisely laid out in a brightly lit, expansive modern studio.

**Theme:** light

Pixso embodies a digital workspace aesthetic, with clean lines and a functional layout that prioritizes content. Its visual mood is bright and accessible, achieved through ample white space and subtle, almost invisible grays. The deliberate use of soft, colorful gradients primarily for decorative elements and featured cards prevents the grayscale foundation from feeling sterile, adding a touch of playful innovation without overshadowing the core content.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Primary text, critical borders, icons. Provides strong contrast against the light backgrounds, ensuring readability of all content. |
| Canvas White | `#FFFFFF` | `--color-canvas-white` | Page backgrounds, card surfaces, primary button backgrounds. Dominant color for creating an expansive, clean feel. |
| Warm Mist | `#F9F9FA` | `--color-warm-mist` | Subtle secondary backgrounds, button states. A near-white that adds minimal visual separation without appearing as a distinct color. |
| Slate Border | `#EAEBEE` | `--color-slate-border` | Inconspicuous borders, dividers between elements, secondary button backgrounds. Its light tone maintains the open feel. |
| Deep Graphite | `#121212` | `--color-deep-graphite` | Dark secondary text, navigation items. Slightly softer than Absolute Zero, used for less prominent dark elements. |
| Cloud Whisper | `#FAF8FD` | `--color-cloud-whisper` | Subtle background tint, almost imperceptible. Adds micro-texture without chromatic distraction. |
| Cool Teal | `#CFE7ED` | `--color-cool-teal` | Decorative card backgrounds signaling a fresh, innovative focus without being overtly branded. |
| Skybound Blue | `#336FFF` | `--color-skybound-blue` | Primary interactive elements like CTA buttons and active states; brings a sense of reliability and trust (from '--v2--color-bg-brand-normal'). |
| Skybound Blue Hover | `#4381FF` | `--color-skybound-blue-hover` | Hover state for primary interactive elements; a slightly lighter blue to indicate affordance (from '--v2--color-bg-brand-hover'). |
| Cosmic Drift Gradient | `linear-gradient(88deg, rgb(238, 124, 255) 1.37%, rgb(78, 111, 255) 45.72%, rgb(85, 156, 255) 106.06%)` | `--color-cosmic-drift-gradient` | Decorative background gradient used sparingly on hero sections or prominent feature cards; adds a dimension of futuristic flair. |
| Horizon Burst Gradient | `linear-gradient(270deg, rgba(255, 175, 62, 0.6) 0%, rgba(255, 134, 131, 0.6) 33.96%, rgba(255, 115, 248, 0.6) 64.64%, rgba(172, 121, 255, 0.6) 100%)` | `--color-horizon-burst-gradient` | Evocative background gradient for illustration features, suggesting creativity and expansive possibilities. |
| Dawn Spectrum Gradient | `linear-gradient(rgb(41, 116, 255) 7.51%, rgb(255, 158, 247) 46.67%, rgb(243, 243, 246) 90.62%)` | `--color-dawn-spectrum-gradient` | Soft, engaging background for key value propositions, illustrating a journey from concept to reality. |

## Tokens — Typography

### Figtree — The sole typeface, used for all textual elements from navigation to body text and headings. Its clean, geometric sans-serif quality supports the modern, functional aesthetic without demanding attention, allowing content and subtle UI elements to shine. The wide range of weights and sizes provides a flexible typographic hierarchy. · `--font-figtree`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 24px, 28px, 30px, 34px, 48px, 50px, 60px
- **Line height:** 1.10, 1.15, 1.17, 1.20, 1.21, 1.29, 1.30, 1.38, 1.40, 1.50, 1.55, 1.60, 1.61
- **Letter spacing:** normal
- **Role:** The sole typeface, used for all textual elements from navigation to body text and headings. Its clean, geometric sans-serif quality supports the modern, functional aesthetic without demanding attention, allowing content and subtle UI elements to shine. The wide range of weights and sizes provides a flexible typographic hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | — | `--text-caption` |
| body | 14px | 1.6 | — | `--text-body` |
| heading-sm | 18px | 1.4 | — | `--text-heading-sm` |
| heading | 24px | 1.38 | — | `--text-heading` |
| heading-lg | 28px | 1.29 | — | `--text-heading-lg` |
| display | 48px | 1.21 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 50 | 50px | `--spacing-50` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| input | 0px |
| buttons | 8px |
| largeButtons | 12px |
| decorativeRound | 18px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.04) 0px 2px 4px 0px, rgba(0, 0, 0, 0.3) 0...` | `--shadow-sm` |
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.4) 0p...` | `--shadow-subtle` |

### Layout

- **Section gap:** 64px
- **Card padding:** 0px
- **Element gap:** 6px

## Components

### Primary Action Button
**Role:** Core CTA for user actions

White background (`#FFFFFF`), Absolute Zero text (`#000000`), 12px border radius. 16px padding on all sides. Used for prominent 'Get started' actions.

### Secondary Action Button
**Role:** Alternative or less prominent actions

White background (`#FFFFFF`), Absolute Zero text (`#000000`), 18px border radius. Padding: 10px top/bottom, 10px left/right. Slightly more rounded to distinguish from primary. Has a text variant of font-size 13px.

### Ghost Button
**Role:** Tertiary actions, links, or navigation items

Transparent background (`rgba(0, 0, 0, 0)`), Absolute Zero text (`#000000`), 10px border radius. Padding: 10px top/bottom, 14px right, 12px left. Minimal visual weight for less emphasis.

### Small Button
**Role:** Compact actions, utility buttons

White background (`#FFFFFF`), Absolute Zero text (`#000000`), 8px border radius. Padding: 10px top/bottom, 20px left/right.

### Image Card (No Background)
**Role:** Displaying visual content without additional styling

Transparent background, 0px border radius, no shadow. Padding 0. Used for embedded examples or image-heavy layouts.

### Teal Accent Card
**Role:** Highlighting specific content, often decorative in nature

Cool Teal background (`#CFE7ED`), 8px border radius, no shadow, 0px padding. Acts as a subtle container against the white page.

### Background Detail Card
**Role:** Subtle background element or very light separation

Warm Mist background (`#F9F9FA`), 0px border radius, no shadow, 0px padding. Extremely low contrast for minimal visual impact.

### Subtle Teal Accent Card
**Role:** Minor highlights or visual breaks

Cool Teal background (`#CFE7ED`), 4px border radius, no shadow, 0px padding. A smaller, less prominent version of the Teal Accent Card.

### Text Input (Base)
**Role:** Standard user input fields

Transparent background, Absolute Zero text with 90% opacity, 0px border radius, 0px padding. Focus on functionality with minimal styling.

### Elevated Tooltip Button
**Role:** Interactive elements with a subtle lift, often in toolbars or secondary navigation.

White background (`#FFFFFF`), 8px border radius. Shadow: `rgba(0, 0, 0, 0.04) 0px 2px 4px 0px, rgba(0, 0, 0, 0.3) 0px 0px 1px 0px`.

## Do's and Don'ts

### Do
- Always use Figtree for all textual content, leveraging weights 400-700 to establish hierarchy rather than mixing font families.
- Maintain generous white space using Canvas White (`#FFFFFF`) as the dominant background color for pages and cards to foster an open, clean aesthetic.
- Apply an 8px border radius to most interactive elements like buttons and cards, creating a consistent soft rounding.
- Utilize Absolute Zero (`#000000`) for primary text and critical UI elements to ensure maximum readability and impact.
- Use Cool Teal (`#CFE7ED`) only as a background color for decorative cards or subtle feature highlights, not for typography or primary interactive elements.
- Prefer `padding-top: 10px`, `padding-right: 10px`, `padding-bottom: 18px`, `padding-left: 10px` for less prominent buttons to give them distinction from primary CTAs, using an 18px radius.
- Implement the Skybound Blue (`#336FFF`) for primary call-to-action buttons, ensuring a clear visual prompt for user engagement.

### Don't
- Do not introduce new font families; the system relies exclusively on Figtree.
- Avoid high-contrast, saturated colors for UI element backgrounds, maintaining the serene, clean feel through neutrals and subtle accents.
- Do not use hard, sharp shadows; instead, use the defined, soft elevation for buttons (`rgba(0, 0, 0, 0.04) 0px 2px 4px 0px, rgba(0, 0, 0, 0.3) 0px 0px 1px 0px`).
- Do not overcrowd sections; maintain a comfortable density with consistent element and section gaps.
- Avoid excessive gradients on functional elements; reserve them primarily for large decorative sections or illustrative backgrounds.
- Do not deviate from the established border radii; avoid sharp corners on interactive components or overly rounded, pill-like shapes outside specific button variants.
- Do not use dark backgrounds for main content areas; maintain the integrity of the light theme.

## Imagery

The site uses a mix of abstract 3D elements, product screenshots, and stylized flat icons. Product screenshots are typically tightly cropped UI examples of the Pixso product, often presented within UI frames, emphasizing functionality. Abstract 3D elements feature soft, organic shapes with soft gradients (e.g., violet, blue, orange, pink), serving as decorative flourishes that animate subtly and add a sense of modern digital artistry. Icons are outlined or filled, mostly monochromatic, and provide visual cues without dominating the layout. The overall language is explanatory and product-centric, with imagery serving to enhance understanding of software capabilities.

## Layout

The page primarily uses a max-width contained layout, with content centered within a generous Canvas White background. The hero section features a prominent, centered headline with a subtext and dual calls-to-action, optionally flanked by abstract 3D graphic elements on either side. Sections alternate between white and very light gray backgrounds (like Warm Mist or Slate Border), creating a subtle visual rhythm without harsh dividers. Content arrangements are generally centered stacks or two-column layouts (text on one side, image/illustration on the other). Feature grids are common, often presenting content in 3 or 4 columns. Navigation is a sticky top bar with a clear logo, global navigation links, and login/signup buttons. The density is comfortable, with ample vertical spacing between sections.

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary:** `#000000` (Absolute Zero)
- **Page Background:** `#FFFFFF` (Canvas White)
- **CTA Button Background:** `#336FFF` (Skybound Blue)
- **Card Accent:** `#CFE7ED` (Cool Teal)
- **Subtle Border:** `#EAEBEE` (Slate Border)

### 3-5 Example Component Prompts
1. **Create a hero section:** background Canvas White (`#FFFFFF`). Headline: "Unify your UI/UX design workflow with Pixso" using Figtree, weight 700, 48px size, 1.21 lineHeight, Absolute Zero (`#000000`). Subtext: "Ideate, design, and handoff in one place. Enhance team collaboration with the AI-powered, all-in-one design tool." using Figtree, weight 400, 16px size, 1.5 lineHeight, Absolute Zero (`#000000`). Two buttons below the subtext: one Primary Action Button ("Get started") and one Secondary Action Button ("Generate designs with AI").
2. **Generate a feature card row:** three cards side-by-side. Each card is a Teal Accent Card (`#CFE7ED` background, 8px radius, 0px padding). Title inside each card is Figtree, weight 600, 18px size, 1.4 lineHeight, Absolute Zero (`#000000`). Body text is Figtree, weight 400, 14px size, 1.6 lineHeight, Absolute Zero (`#000000`).
3. **Design a navigation bar:** Canvas White (`#FFFFFF`) background. Logo left: Pixso in Absolute Zero (`#000000`). Navigation links: Figtree, weight 500, 14px size, 1.6 lineHeight, Deep Graphite (`#121212`). Right-aligned buttons: Ghost Button ("Log in") and Small Button ("Get started"). Navbar height should be 54px.
4. **Create a decorative image card:** using the Cool Teal (`#CFE7ED`) background, 8px border radius, 0px padding. Place a product screenshot inside, ensuring there are no rounded corners on the screenshot itself, maintaining its original form. The overall card should feel like a contained highlight rather than a heavily styled component.
5. **Render a call-to-action block in a section:** background Warm Mist (`#F9F9FA`). A headline like "Try Pixso for free today!" using Figtree, weight 700, 34px size, 1.2 LineHeight, Absolute Zero (`#000000`). Centered beneath, a Primary Action Button labeled "Start Designing Now" with White text and Skybound Blue background.

## Similar Brands

- **Figma** — Clean, collaborative design tool UI with a focus on simplicity and a light theme, using a sans-serif typeface and subtle elevation.
- **Linear** — Functional, content-focused UI with a similar sans-serif typeface, strong negative space, and minimal decorative elements.
- **Miro** — Online collaborative workspace. Shares a bright, approachable aesthetic with a strong emphasis on content and clear hierarchy, using a similar light theme.
- **Notion** — Content-first digital workspace. Employs a clean, minimal design, extensive white space, and a sans-serif font for readability across various content types.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #FFFFFF;
  --color-warm-mist: #F9F9FA;
  --color-slate-border: #EAEBEE;
  --color-deep-graphite: #121212;
  --color-cloud-whisper: #FAF8FD;
  --color-cool-teal: #CFE7ED;
  --color-skybound-blue: #336FFF;
  --color-skybound-blue-hover: #4381FF;
  --color-cosmic-drift-gradient: #BFBFBF;
  --gradient-cosmic-drift-gradient: linear-gradient(88deg, rgb(238, 124, 255) 1.37%, rgb(78, 111, 255) 45.72%, rgb(85, 156, 255) 106.06%);
  --color-horizon-burst-gradient: #BFBFBF;
  --gradient-horizon-burst-gradient: linear-gradient(270deg, rgba(255, 175, 62, 0.6) 0%, rgba(255, 134, 131, 0.6) 33.96%, rgba(255, 115, 248, 0.6) 64.64%, rgba(172, 121, 255, 0.6) 100%);
  --color-dawn-spectrum-gradient: #BFBFBF;
  --gradient-dawn-spectrum-gradient: linear-gradient(rgb(41, 116, 255) 7.51%, rgb(255, 158, 247) 46.67%, rgb(243, 243, 246) 90.62%);

  /* Typography — Font Families */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.38;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.29;
  --text-display: 48px;
  --leading-display: 1.21;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-50: 50px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 0px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 25px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-input: 0px;
  --radius-buttons: 8px;
  --radius-largebuttons: 12px;
  --radius-decorativeround: 18px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 2px 4px 0px, rgba(0, 0, 0, 0.3) 0px 0px 1px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.4) 0px 0px 1px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-canvas-white: #FFFFFF;
  --color-warm-mist: #F9F9FA;
  --color-slate-border: #EAEBEE;
  --color-deep-graphite: #121212;
  --color-cloud-whisper: #FAF8FD;
  --color-cool-teal: #CFE7ED;
  --color-skybound-blue: #336FFF;
  --color-skybound-blue-hover: #4381FF;
  --color-cosmic-drift-gradient: #BFBFBF;
  --color-horizon-burst-gradient: #BFBFBF;
  --color-dawn-spectrum-gradient: #BFBFBF;

  /* Typography */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.6;
  --text-heading-sm: 18px;
  --leading-heading-sm: 1.4;
  --text-heading: 24px;
  --leading-heading: 1.38;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.29;
  --text-display: 48px;
  --leading-display: 1.21;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-50: 50px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 18px;
  --radius-3xl: 25px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.04) 0px 2px 4px 0px, rgba(0, 0, 0, 0.3) 0px 0px 1px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 1px 0px, rgba(0, 0, 0, 0.4) 0px 0px 1px 0px;
}
```
