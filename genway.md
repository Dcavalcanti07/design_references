# Genway — Style Reference
> Soft violet hazes, crisp text highlights

**Theme:** light

Genway uses a luminous, ethereal interface language, combining soft gradients and subtle shadows with sharp, direct typography. The aesthetic balances a dreamlike, almost hazy background atmosphere with crisp, authoritative foreground elements. A vibrant palette of deep purples and lilacs defines brand presence, appearing in gradients that hint at depth and in a few focused headline accents, while the majority of the UI remains pristine white. The system emphasizes clarity and a lightweight feel, with generous whitespace and minimal ornamentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Violet | `linear-gradient(0deg, rgb(10, 4, 73) 0%, rgb(107, 94, 224) 145%)` | `--color-midnight-violet` | Violet outline accent for tags, dividers, and focused UI edges. Do not promote it to the primary CTA color; Hero section background, subtle background effect, creating a sense of depth and brand identity |
| Cool Gray | `#706e87` | `--color-cool-gray` | Secondary body text, border for ghost buttons and outlined elements, providing a muted contrast to the vibrant brand colors |
| Soft Lilac | `#efb9fd` | `--color-soft-lilac` | Decorative background fills, faint gradient highlights, creating an atmospheric brand presence without overwhelming content |
| Vivid Amethyst | `#6b5ee0` | `--color-vivid-amethyst` | Accent text on dark backgrounds, decorative icon fills, and borders. This vivid violet acts as a point of energy |
| Deep Plum | `#0a0163` | `--color-deep-plum` | Darkest background in some gradients, subtle text accents, and outlines for secondary elements |
| Muted Lavender | `#a89fc7` | `--color-muted-lavender` | Subtle box shadows, secondary background fills, and decorative graphic elements, offering a desaturated version of the brand's purple |
| Soft Pinkish Gray | `#a085a6` | `--color-soft-pinkish-gray` | Light, subtle text color for interface elements that require less emphasis, like placeholder text or secondary descriptions |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, card backgrounds, and default text color for high contrast. Provides a clean, expansive foundation |
| Whisper Gray | `#f7f6fd` | `--color-whisper-gray` | Subtle background for UI panels and cards, offering a slight visual break from pure white without being distracting. Main surface for distinct cards |
| Faded Lilac Gradient | `linear-gradient(rgb(226, 224, 249) 0%, rgb(207, 204, 245) 100%)` | `--color-faded-lilac-gradient` | Subtle background gradients for sections, providing a soft, almost imperceptible shift in tone |
| Light Violet Wash Gradient | `linear-gradient(rgba(105, 92, 224, 0.2) 0%, rgb(207, 204, 245) 100%)` | `--color-light-violet-wash-gradient` | Decorative background accent, suggesting a gentle glow or aura |

## Tokens — Typography

### Geist Regular — Geist Regular — detected in extracted data but not described by AI · `--font-geist-regular`
- **Weights:** 400
- **Sizes:** 10px, 12px, 14px, 16px, 20px, 24px
- **Line height:** 1.2, 1.3, 1.5
- **Letter spacing:** -0.04, -0.02
- **Role:** Geist Regular — detected in extracted data but not described by AI

### Geist — Primary body and UI text. The custom typeface 'Geist' provides a distinct, clean aesthetic with a slightly technical feel, ensuring readability in small contexts and impact in larger ones. · `--font-geist`
- **Weights:** 400, 500
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** -0.0400em for 24px, -0.0200em for 10px-20px
- **Role:** Primary body and UI text. The custom typeface 'Geist' provides a distinct, clean aesthetic with a slightly technical feel, ensuring readability in small contexts and impact in larger ones.

### Geist — Emphasized body text, subheadings, and interactive elements. This medium weight provides subtle hierarchy within paragraphs. · `--font-geist`
- **Weights:** 400, 500
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** -0.0200em
- **Role:** Emphasized body text, subheadings, and interactive elements. This medium weight provides subtle hierarchy within paragraphs.

### Geist — Section titles and prominent secondary headings. While technically 'Semibold', its weight is 400 in the data — this maintains a sleek, non-shouting tone. · `--font-geist`
- **Weights:** 400, 500
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** -0.0200em for 24px-36px, -0.0100em for 14px-16px
- **Role:** Section titles and prominent secondary headings. While technically 'Semibold', its weight is 400 in the data — this maintains a sleek, non-shouting tone.

### Geist — Dominant display headings. Though listed as weight 400, size creates impact. The compressed line height for large sizes contributes to a commanding presence. · `--font-geist`
- **Weights:** 400, 500
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** -0.0400em
- **Role:** Dominant display headings. Though listed as weight 400, size creates impact. The compressed line height for large sizes contributes to a commanding presence.

### Inter — System fallback or minimal utility text where Geist is not strictly necessary. Should be used sparingly to maintain brand consistency. · `--font-inter`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** System fallback or minimal utility text where Geist is not strictly necessary. Should be used sparingly to maintain brand consistency.

### system-ui, sans-serif — Fallback for unstyled text. · `--font-system-ui-sans-serif`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Fallback for unstyled text.

### Geist SemiBold — Geist SemiBold — detected in extracted data but not described by AI · `--font-geist-semibold`
- **Weights:** 400
- **Sizes:** 14px, 16px, 24px, 36px
- **Line height:** 1.2, 1.3, 1.5
- **Letter spacing:** -0.02, -0.01
- **Role:** Geist SemiBold — detected in extracted data but not described by AI

### Geist Bold — Geist Bold — detected in extracted data but not described by AI · `--font-geist-bold`
- **Weights:** 400
- **Sizes:** 56px, 68px, 88px
- **Line height:** 0.9, 1
- **Letter spacing:** -0.04
- **Role:** Geist Bold — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.2 | -0.4px | `--text-caption` |
| body | 14px | 1.5 | -0.28px | `--text-body` |
| heading-sm | 20px | 1.3 | -0.4px | `--text-heading-sm` |
| heading | 24px | 1.3 | -0.48px | `--text-heading` |
| heading-lg | 36px | 1.2 | -0.36px | `--text-heading-lg` |
| display | 56px | 0.9 | -0.896px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 124 | 124px | `--spacing-124` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| images | 120px |
| buttons | 32px |
| default | 12px |
| circular | 2000px |
| largeCards | 16px |
| specialCardTop | 16px 16px 0px 0px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(10, 1, 99, 0.4) 0px 8px 16px -10px` | `--shadow-md` |
| subtle | `rgba(10, 1, 99, 0.08) 0px 0px 0px 4px` | `--shadow-subtle` |
| sm | `rgba(4, 0, 41, 0.1) 0px 1px 8px 0px inset` | `--shadow-sm` |
| sm-2 | `rgba(11, 1, 101, 0.14) 1px 0px 8px 0px inset` | `--shadow-sm-2` |

### Layout

- **Section gap:** 64px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Headline
**Role:** Hero headline text

Large, bold 'Geist' type at 56-88px, color Midnight Violet (#0a0449), with a tight line height of 0.9 and letter spacing of -0.0400em. This creates a powerful, compact statement.

### Body Text
**Role:** General paragraph content

Geist Regular (weight 400), at sizes like 16px or 20px, with Cool Gray (#706e87) for standard paragraphs and Midnight Violet (#0a0449) for emphasized segments or links. Line height should be 1.5, with tight letter-spacing of -0.0200em.

### Ghost Button
**Role:** Secondary action button

Text in Cool Gray (#706e87) on a transparent background, with a 1px border in Cool Gray (#706e87). Text uses Geist Semibold 16px with -0.0100em letter-spacing. Has a 32px border-radius, giving it a soft, pill-like shape.

### Primary Card (Subtle Elevation)
**Role:** Informational container

Canvas White (#ffffff) background, with a 12px border-radius. Features a soft shadow: rgba(0, 0, 0, 0.004) 0px 2.76px 2.21px, rgba(0, 0, 0, 0.004) 0px 6.65px 5.32px, rgba(0, 0, 0, 0.004) 0px 12.52px 10.01px, rgba(0, 0, 0, 0.008) 0px 22.33px 17.86px, rgba(0, 0, 0, 0.008) 0px 41.77px 33.42px, rgba(0, 0, 0, 0.01) 0px 100px 80px.

### Background Card (No Elevation)
**Role:** Decorative or background informational container

Whisper Gray (#f7f6fd) background, 12px border-radius, with no box-shadow. Used for less prominent content blocks.

### Section Header (Step Indicator)
**Role:** Numbered section title

A number (e.g., '01') in Midnight Violet (#0a0449). This combines Geist Bold 56px with a smaller Geist Regular 16px text description, creating a clear ordered hierarchy.

### Product Insight Card
**Role:** Content card for insights or features

Canvas White (#ffffff) background, rounded top corners at 16px, 0px bottom corners. Distinct, higher elevation shadow: rgba(0, 0, 0, 0.03) 0px 2.76px 2.21px to rgba(0, 0, 0, 0.12) 0px 100px 80px.

### Avatar/Pill
**Role:** Small interactive element or branding

Elements using a 2000px border-radius to achieve a perfect pill or circular shape. Often combined with small images or icons.

## Do's and Don'ts

### Do
- Prioritize Canvas White (#ffffff) for primary backgrounds to maintain a clean aesthetic, reserving Whisper Gray (#f7f6fd) for subtle surface differentiation.
- Use Geist Bold at 56-88px with a line height of 0.9-1.0 and -0.0400em letter-spacing for all hero and main section headlines to convey authority.
- Apply the soft, multi-layered shadow stack on primary cards (like `rgba(0, 0, 0, 0.01) 0px 100px 80px`) to add depth without heaviness.
- Incorporate the Night Sky Gradient (`linear-gradient(0deg, #0a0163 0%, #6b5ee0 145%)`) for hero sections or prominent visual anchors to establish brand identity.
- Utilize 32px border-radius for all interactive buttons and tags to ensure a consistent, pill-like soft shape.
- Maintain an element gap of 8px for vertical and horizontal spacing between small UI elements to ensure tightness and order.
- Use Midnight Violet (#0a0449) for primary text and key interactive outlines, and Cool Gray (#706e87) for secondary text and ghost button borders.

### Don't
- Avoid using harsh, opaque drop shadows; instead, prefer the subtle, layered shadows provided in the system.
- Do not introduce new typefaces; adhere strictly to the Geist family for all text to maintain brand consistency.
- Refrain from using solid, saturated background colors for entire sections; instead, leverage the provided subtle gradients or the Whisper Gray (#f7f6fd) surface.
- Do not deviate from the established border-radius values; particularly, use 32px for buttons and 12px for standard cards.
- Avoid over-saturating the interface with multiple vivid colors; reserve Vivid Amethyst (#6b5ee0) for small, impactful accents.
- Do not use generic system fonts for body text; always use 'Geist' to preserve the unique typographic voice.
- Do not create primary actions as filled buttons with a distinct background color; prefer outlined `Ghost Buttons` using Cool Gray (#706e87) for borders.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas White | `#ffffff` | Primary page background, base for most content sections. |
| 2 | Whisper Gray | `#f7f6fd` | Background for distinct card-like sections or subtle content groupings, offering a slight visual offset from the main canvas. |
| 3 | Muted Lavender | `#a89fc7` | Used in some background gradients or as a very subtle elevated surface effect, providing an ethereal quality. |
| 4 | Deep Plum | `#0a0163` | The darkest tone in background gradients, creating deeper visual depth or as a base for hero sections. |

## Elevation

- **Primary Card (Subtle Elevation):** `rgba(0, 0, 0, 0.004) 0px 2.76726px 2.21381px 0px, rgba(0, 0, 0, 0.004) 0px 6.6501px 5.32008px 0px, rgba(0, 0, 0, 0.004) 0px 12.5216px 10.0172px 0px, rgba(0, 0, 0, 0.008) 0px 22.3363px 17.869px 0px, rgba(0, 0, 0, 0.008) 0px 41.7776px 33.4221px 0px, rgba(0, 0, 0, 0.01) 0px 100px 80px 0px`
- **Product Insight Card:** `rgba(0, 0, 0, 0.03) 0px 2.76726px 2.21381px 0px, rgba(0, 0, 0, 0.05) 0px 6.6501px 5.32008px 0px, rgba(0, 0, 0, 0.06) 0px 12.5216px 10.0172px 0px, rgba(0, 0, 0, 0.07) 0px 22.3363px 17.869px 0px, rgba(0, 0, 0, 0.09) 0px 41.7776px 33.4221px 0px, rgba(0, 0, 0, 0.12) 0px 100px 80px 0px`
- **Focus/Active State:** `rgba(10, 1, 99, 0.08) 0px 0px 0px 4px`

## Agent Prompt Guide

### Quick Color Reference
- text: #0a0449
- background: #ffffff
- border: #706e87
- accent: #6b5ee0
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
1. Create a hero section: Full-width using Night Sky Gradient background. Centered primary headline 'Unlock Deeper Insights with Genway' using Geist Bold 88px, Midnight Violet (#0a0449), line height 0.9, letter-spacing -0.0400em. Below, add a paragraph 'Revolutionize your research with AI' using Geist Regular 24px, Cool Gray (#706e87), line-height 1.3, letter-spacing -0.0200em.
2. Design a feature card: Use Whisper Gray (#f7f6fd) background, 12px border-radius, no shadow. Headline 'Seamless Integration' in Geist Semibold 24px, Midnight Violet (#0a0449), letter-spacing -0.0200em. Body copy in Geist Regular 16px, Cool Gray (#706e87), line-height 1.5, letter-spacing -0.0200em. Include an icon filled with Vivid Amethyst (#6b5ee0), and use an 8px element gap between items.
3. Build a ghost button: Text 'Learn More' using Geist Semibold 16px, Cool Gray (#706e87), letter-spacing -0.0100em. Transparent background, 1px border in Cool Gray (#706e87), and a 32px border-radius.
4. Create an 'Insight' product card for a UI element: Canvas White (#ffffff) background, with top corners 16px radius and bottom corners 0px radius. Apply the Product Insight Card shadow. Headline 'User Journey Mapping' in Geist Semibold 36px, Midnight Violet (#0a0449), letter-spacing -0.0200em.
5. Design a numbered step: The number '01' uses Geist Bold 56px, Midnight Violet (#0a0449), line-height 0.9, letter-spacing -0.0400em. Below, add a descriptive text 'Set your learning goals' in Geist Regular 20px, Cool Gray (#706e87), line-height 1.3, letter-spacing -0.0200em.

## Similar Brands

- **Linear** — Shares a focus on precise typography, subtle elevation, and a cool-toned, minimalist UI with a single accent color.
- **Raycast** — Visually similar with crisp, compact UI elements, restrained use of color, and preference for clarity over heavy ornamentation.
- **Stripe** — Employs an expansive white canvas, light gradients, and strategic pops of brand color to highlight interactive elements and sections, similar to Genway's use of purple.
- **Vercel** — Known for clean, developer-focused interfaces, often featuring subtle background gradients, sharp typography, and a modern, airy feel, much like Genway.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-violet: #0a0449;
  --gradient-midnight-violet: linear-gradient(0deg, rgb(10, 4, 73) 0%, rgb(107, 94, 224) 145%);
  --color-cool-gray: #706e87;
  --color-soft-lilac: #efb9fd;
  --color-vivid-amethyst: #6b5ee0;
  --color-deep-plum: #0a0163;
  --color-muted-lavender: #a89fc7;
  --color-soft-pinkish-gray: #a085a6;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f7f6fd;
  --color-faded-lilac-gradient: #e2e0f9;
  --gradient-faded-lilac-gradient: linear-gradient(rgb(226, 224, 249) 0%, rgb(207, 204, 245) 100%);
  --color-light-violet-wash-gradient: #695ce0;
  --gradient-light-violet-wash-gradient: linear-gradient(rgba(105, 92, 224, 0.2) 0%, rgb(207, 204, 245) 100%);

  /* Typography — Font Families */
  --font-geist-regular: 'Geist Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui-sans-serif: 'system-ui, sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-semibold: 'Geist SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-bold: 'Geist Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.4px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --tracking-heading: -0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.36px;
  --text-display: 56px;
  --leading-display: 0.9;
  --tracking-display: -0.896px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-124: 124px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 50px;
  --radius-full-2: 120px;
  --radius-full-3: 200px;
  --radius-full-4: 2000px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-images: 120px;
  --radius-buttons: 32px;
  --radius-default: 12px;
  --radius-circular: 2000px;
  --radius-largecards: 16px;
  --radius-specialcardtop: 16px 16px 0px 0px;

  /* Shadows */
  --shadow-md: rgba(10, 1, 99, 0.4) 0px 8px 16px -10px;
  --shadow-subtle: rgba(10, 1, 99, 0.08) 0px 0px 0px 4px;
  --shadow-sm: rgba(4, 0, 41, 0.1) 0px 1px 8px 0px inset;
  --shadow-sm-2: rgba(11, 1, 101, 0.14) 1px 0px 8px 0px inset;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-whisper-gray: #f7f6fd;
  --surface-muted-lavender: #a89fc7;
  --surface-deep-plum: #0a0163;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-violet: #0a0449;
  --color-cool-gray: #706e87;
  --color-soft-lilac: #efb9fd;
  --color-vivid-amethyst: #6b5ee0;
  --color-deep-plum: #0a0163;
  --color-muted-lavender: #a89fc7;
  --color-soft-pinkish-gray: #a085a6;
  --color-canvas-white: #ffffff;
  --color-whisper-gray: #f7f6fd;
  --color-faded-lilac-gradient: #e2e0f9;
  --color-light-violet-wash-gradient: #695ce0;

  /* Typography */
  --font-geist-regular: 'Geist Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist: 'Geist', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui-sans-serif: 'system-ui, sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-semibold: 'Geist SemiBold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-geist-bold: 'Geist Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.2;
  --tracking-caption: -0.4px;
  --text-body: 14px;
  --leading-body: 1.5;
  --tracking-body: -0.28px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --tracking-heading: -0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.36px;
  --text-display: 56px;
  --leading-display: 0.9;
  --tracking-display: -0.896px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-124: 124px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 50px;
  --radius-full-2: 120px;
  --radius-full-3: 200px;
  --radius-full-4: 2000px;

  /* Shadows */
  --shadow-md: rgba(10, 1, 99, 0.4) 0px 8px 16px -10px;
  --shadow-subtle: rgba(10, 1, 99, 0.08) 0px 0px 0px 4px;
  --shadow-sm: rgba(4, 0, 41, 0.1) 0px 1px 8px 0px inset;
  --shadow-sm-2: rgba(11, 1, 101, 0.14) 1px 0px 8px 0px inset;
}
```
