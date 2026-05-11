# Rootly — Style Reference
> Violet-tinged command center behind frosted glass.

**Theme:** light

Rootly presents a calm yet capable aesthetic, balancing robust AI functionality with clear, user-centric design. Muted violet and near-black create a professional, deep canvas, punctuated by a brighter, vivid violet that signifies action and focus. Surfaces are typically soft and rounded, offering subtle visual cues rather than harsh divisions. Typography is precise and efficient, maintaining clarity across data-rich interfaces, while gradients offer a touch of sophisticated atmosphere without visual noise.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#100f12` | `--color-midnight-ink` | Primary text, major headings, background for dark elements like primary buttons. A near-black that provides high contrast |
| Canvas White | `#ffffff` | `--color-canvas-white` | Background for primary interactive elements like buttons and navigation. Creates a stark contrast against darker text elements |
| Haze White | `#fbfaff` | `--color-haze-white` | Default page background. A very slight off-white, providing a soft base layer |
| Cadet Violet | `#d9cffa` | `--color-cadet-violet` | Violet state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |
| Deep Space Violet | `#8d6fde` | `--color-deep-space-violet` | Primary accent for interactive states, icons, and borders. A vivid, saturated violet that draws attention |
| Lavender Mist | `#ebe5ff` | `--color-lavender-mist` | Subtle card backgrounds and low-prominence button fills. A very light, desaturated violet |
| Graphite Feather | `#787685` | `--color-graphite-feather` | Muted body text, secondary descriptions, and borders for subtle UI separation |
| Nightfall Violet | `#4a3e8a` | `--color-nightfall-violet` | Darker shade of violet used for text within interactive elements and borders for emphasis |
| Ash Grey | `#65646e` | `--color-ash-grey` | Auxiliary body text and less prominent content, offering slightly softer contrast than Midnight Ink |
| Faded Stone | `#aaa9ae` | `--color-faded-stone` | Placeholder text and subtle secondary information, appearing as a light gray |
| Sky Veil Gradient | `linear-gradient(90deg, rgb(233, 226, 255), rgb(254, 245, 247) 75%)` | `--color-sky-veil-gradient` | Decorative background gradient used for atmospheric sections, transitioning from a light violet to a pale pink |
| Twilight Horizon Gradient | `linear-gradient(112deg, rgb(119, 72, 246), rgb(245, 187, 195) 80%)` | `--color-twilight-horizon-gradient` | Hero section background, conveying depth and sophistication by blending vibrant violet with soft rose |

## Tokens — Typography

### Ppmori — Primary typeface for all text elements. Its sharp, modern lines and range of weights, particularly lighter weights for headlines, signal precision and a technical yet refined brand identity. A custom font, it brings a distinctive character that system fonts lack. · `--font-ppmori`
- **Substitute:** Inter
- **Weights:** 200, 500, 600
- **Sizes:** 10px, 12px, 14px, 16px, 17px, 31px, 52px
- **Line height:** 1.00, 1.03, 1.20, 1.30, 1.40, 1.43, 1.45, 1.46
- **Letter spacing:** -0.0150em, -0.0130em, -0.0100em, -0.0090em
- **Role:** Primary typeface for all text elements. Its sharp, modern lines and range of weights, particularly lighter weights for headlines, signal precision and a technical yet refined brand identity. A custom font, it brings a distinctive character that system fonts lack.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.45 | -0.15px | `--text-caption` |
| body | 14px | 1.46 | -0.14px | `--text-body` |
| heading | 31px | 1.2 | -0.31px | `--text-heading` |
| display | 52px | 1.03 | -0.78px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 17 | 17px | `--spacing-17` |
| 21 | 21px | `--spacing-21` |
| 28 | 28px | `--spacing-28` |
| 35 | 35px | `--spacing-35` |
| 42 | 42px | `--spacing-42` |
| 62 | 62px | `--spacing-62` |
| 69 | 69px | `--spacing-69` |
| 114 | 114px | `--spacing-114` |

### Border Radius

| Element | Value |
|---------|-------|
| full | 1440px |
| large | 34.6px |
| small | 13.84px |
| medium | 17.3px |
| xsmall | 6.92px |

### Layout

- **Page max-width:** 1600px
- **Section gap:** 42px
- **Card padding:** 14px
- **Element gap:** 7px

## Components

### Primary Filled Button
**Role:** Main call to action button.

Background: Midnight Ink (#100f12). Text: Canvas White (#ffffff). Corner radius: 17.3px. Padding: 15.57px vertical, 27.68px horizontal.

### Secondary Filled Button (Canvas)
**Role:** Secondary call to action, often paired with primary button.

Background: Canvas White (#ffffff). Text: Midnight Ink (#100f12). Corner radius: 17.3px. Padding: 20.76px vertical, 20.76px horizontal.

### Ghost Button
**Role:** Tertiary action or navigational button within text.

Background: transparent. Text: Midnight Ink (#100f12). Border: 1px solid Midnight Ink (#100f12). Corner radius: 13.84px. Padding: 8.65px top, 13.84px horizontal, 7.266px bottom.

### Light Card
**Role:** Content container with a soft background.

Background: Haze White (#fbfaff). Corner radius: 34.6px. Padding: 6.92px. No shadow.

### Accent Card
**Role:** Highlighted content container.

Background: Lavender Mist (#ebe5ff). Corner radius: 17.3px. No shadow. No padding.

### Text Input Field
**Role:** Standard input for user data.

Background: transparent. Text: Nightfall Violet (#4a3e8a). Border: 1px solid Cadet Violet (#d9cffa). Corner radius: 1440px (full pill shape). Padding: 13.84px top, 17.3px horizontal, 12.11px bottom.

## Do's and Don'ts

### Do
- Prioritize Ppmori weight 600 for main headings, Midnight Ink (#100f12) text color, and a line height of 1.03 for impact. Apply tracking like -0.0150em for large sizes.
- Use Haze White (#fbfaff) for default page backgrounds to maintain a soft, light canvas.
- Accent interactive elements (icons, borders, active states) with Deep Space Violet (#8d6fde) to draw focus and provide visual feedback.
- Ensure all buttons and interactive elements apply a rounded corner, with a full pill shape (1440px) or 17.3px for other prominent elements.
- Utilize a 7px element gap for comfortable spacing between general UI elements.
- Apply Cadet Violet (#d9cffa) for input borders to indicate interactive fields without high visual noise.
- Employ Lavender Mist (#ebe5ff) for subtle card backgrounds to differentiate content blocks gently.

### Don't
- Avoid using highly saturated colors for large background areas, reserving them for small, functional accents.
- Do not introduce sharp corners on interactive components; maintain the rounded aesthetic across cards, buttons, and inputs.
- Do not use dark backgrounds for general page content; maintain a light theme for readability and brand consistency.
- Avoid overly bold or heavy typography for body text; rely on the lighter weights of Ppmori and Midnight Ink for primary content.
- Do not use box-shadows for elevation; rely on background color changes or subtle borders for surface distinction.
- Avoid generic blue for links or buttons; use Canvas White (#ffffff) or Midnight Ink (#100f12) for filled buttons, or Deep Space Violet (#8d6fde) for outlined accents.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Haze White Canvas | `#fbfaff` | Base page background, providing a soft, almost imperceptible off-white foundation. |
| 1 | Lavender Mist Card | `#ebe5ff` | Background for secondary content cards or sections, offering a gentle visual lift from the canvas. |
| 2 | Canvas White Element | `#ffffff` | Background for primary interactive elements like buttons, header, and active states, creating distinct contrast and visual hierarchy. |

## Imagery

The site uses a combination of abstract, atmospheric imagery and product-focused UI screenshots. Backgrounds often feature stylized, muted purple-and-pink gradients depicting mountainous or cloud-like formations, providing a soft, almost ethereal backdrop. Product screenshots are typically tightly cropped and presented with clean, often transparent, backgrounds, highlighting the UI elements themselves. Icons are monochromatic, using Midnight Ink (#100f12) or Deep Space Violet (#8d6fde), with a clear, outlined style, some showing rounded square containers. Imagery serves both as decorative atmosphere for brand identity and explanatory content for product features, balancing visual appeal with clear communication. The image density is moderate, allowing ample space for text.

## Layout

The page primarily employs a max-width contained layout of 1600px, centered on the screen. The hero section is full-bleed, featuring a centered headline over a gradient background, setting an atmospheric tone. Subsequent sections alternate between light backgrounds (Haze White) and gradient backgrounds (Sky Veil Gradient), creating a rhythmic flow down the page. Content within sections is arranged in a fluid, often two-column layout with text on one side and product visuals or abstract graphics on the other, occasionally reversing the order. There's a notable use of a 3-column grid for partner logos below the hero. Navigation is handled by a sticky top bar with text links and two distinct pill-shaped buttons in the top right corner.

## Agent Prompt Guide

Quick Color Reference:
text: #100f12
background: #fbfaff
border: #d9cffa
accent: #8d6fde
primary action: #100f12 (filled action)

Example Component Prompts:
Create a Primary Action Button: #100f12 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a product feature card: Accent Card (#ebe5ff, 17.3px radius, no padding). Inside, a Ppmori weight 500, 16px subheading (#100f12) with a short Ppmori weight 500, 14px body text (#65646e) below it. Add 14px padding to the content inside the card.

Create an input field: Text Input Field type="text" with placeholder 'Enter your email' (Ppmori weight 500, 14px, Faded Stone #aaa9ae). Border is Cadet Violet (#d9cffa), radius 1440px. Text color Nightfall Violet (#4a3e8a).

## Similar Brands

- **Linear** — Shares a precise, data-rich UI with a focus on functional typography and subtle color accents rather than heavy graphics.
- **Vercel** — Uses a dark-mode default with minimalistic UI, sophisticated typography, and one primary accent color for key actions, similar to Rootly's light-mode approach.
- **Notion** — Employs a clean, white-canvas aesthetic with crisp typography and subtle interactive elements, prioritizing clarity and user focus.
- **Stripe** — Known for clean interfaces, strong use of gradients in hero sections, and precise, functional typography combined with soft, rounded UI elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #100f12;
  --color-canvas-white: #ffffff;
  --color-haze-white: #fbfaff;
  --color-cadet-violet: #d9cffa;
  --color-deep-space-violet: #8d6fde;
  --color-lavender-mist: #ebe5ff;
  --color-graphite-feather: #787685;
  --color-nightfall-violet: #4a3e8a;
  --color-ash-grey: #65646e;
  --color-faded-stone: #aaa9ae;
  --color-sky-veil-gradient: #e9e2ff;
  --gradient-sky-veil-gradient: linear-gradient(90deg, rgb(233, 226, 255), rgb(254, 245, 247) 75%);
  --color-twilight-horizon-gradient: #7748f6;
  --gradient-twilight-horizon-gradient: linear-gradient(112deg, rgb(119, 72, 246), rgb(245, 187, 195) 80%);

  /* Typography — Font Families */
  --font-ppmori: 'Ppmori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.45;
  --tracking-caption: -0.15px;
  --text-body: 14px;
  --leading-body: 1.46;
  --tracking-body: -0.14px;
  --text-heading: 31px;
  --leading-heading: 1.2;
  --tracking-heading: -0.31px;
  --text-display: 52px;
  --leading-display: 1.03;
  --tracking-display: -0.78px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-21: 21px;
  --spacing-28: 28px;
  --spacing-35: 35px;
  --spacing-42: 42px;
  --spacing-62: 62px;
  --spacing-69: 69px;
  --spacing-114: 114px;

  /* Layout */
  --page-max-width: 1600px;
  --section-gap: 42px;
  --card-padding: 14px;
  --element-gap: 7px;

  /* Border Radius */
  --radius-md: 6.92px;
  --radius-xl: 13.84px;
  --radius-2xl: 17.3px;
  --radius-2xl-2: 20.76px;
  --radius-3xl: 27.68px;
  --radius-3xl-2: 34.6px;
  --radius-full: 1440px;

  /* Named Radii */
  --radius-full: 1440px;
  --radius-large: 34.6px;
  --radius-small: 13.84px;
  --radius-medium: 17.3px;
  --radius-xsmall: 6.92px;

  /* Surfaces */
  --surface-haze-white-canvas: #fbfaff;
  --surface-lavender-mist-card: #ebe5ff;
  --surface-canvas-white-element: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #100f12;
  --color-canvas-white: #ffffff;
  --color-haze-white: #fbfaff;
  --color-cadet-violet: #d9cffa;
  --color-deep-space-violet: #8d6fde;
  --color-lavender-mist: #ebe5ff;
  --color-graphite-feather: #787685;
  --color-nightfall-violet: #4a3e8a;
  --color-ash-grey: #65646e;
  --color-faded-stone: #aaa9ae;
  --color-sky-veil-gradient: #e9e2ff;
  --color-twilight-horizon-gradient: #7748f6;

  /* Typography */
  --font-ppmori: 'Ppmori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.45;
  --tracking-caption: -0.15px;
  --text-body: 14px;
  --leading-body: 1.46;
  --tracking-body: -0.14px;
  --text-heading: 31px;
  --leading-heading: 1.2;
  --tracking-heading: -0.31px;
  --text-display: 52px;
  --leading-display: 1.03;
  --tracking-display: -0.78px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-17: 17px;
  --spacing-21: 21px;
  --spacing-28: 28px;
  --spacing-35: 35px;
  --spacing-42: 42px;
  --spacing-62: 62px;
  --spacing-69: 69px;
  --spacing-114: 114px;

  /* Border Radius */
  --radius-md: 6.92px;
  --radius-xl: 13.84px;
  --radius-2xl: 17.3px;
  --radius-2xl-2: 20.76px;
  --radius-3xl: 27.68px;
  --radius-3xl-2: 34.6px;
  --radius-full: 1440px;
}
```
