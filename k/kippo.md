# Kippo — Style Reference
> Fuchsia glow in the dark.

**Theme:** dark

Kippo builds a dark-mode, gaming-centric interface with a compelling use of a single vibrant fuchsia accent color against a deep charcoal background. Typography leans modern and compact, utilizing a monospace font that evokes code or terminal screens. Interactive elements are softened with generous corner radii, creating a friendly contrast to the sharp, dark theme. The overall aesthetic is engaging and dynamic, designed to keep users immersed.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Black | `#000000` | `--color-pitch-black` | Page backgrounds, section dividers, default text for contrast |
| Charcoal Surface | `#29292a` | `--color-charcoal-surface` | Card backgrounds, elevated container surfaces |
| Snow Ghost | `#ffffff` | `--color-snow-ghost` | Primary text, navigation links, button text, subtle borders |
| Smoke Text | `#333333` | `--color-smoke-text` | Muted text, secondary links |
| Kippo Fuchsia | `#ee1f66` | `--color-kippo-fuchsia` | Red action color for filled buttons, selected navigation states, and focused conversion moments. |
| Sunshine Aura | `linear-gradient(to right, rgb(255, 196, 0), rgb(255, 51, 224))` | `--color-sunshine-aura` | Decorative gradient accent for highlights or special content |
| Fresh Mint Gradient | `linear-gradient(to right, rgb(51, 190, 255), rgb(51, 255, 184))` | `--color-fresh-mint-gradient` | Decorative gradient accent, possibly for rewards or positive feedback |
| Silver Gloss Gradient | `linear-gradient(to right, rgb(207, 207, 207), rgb(255, 255, 255))` | `--color-silver-gloss-gradient` | Subtle decorative gradient for background textures or UI embellishments |

## Tokens — Typography

### Source Code Pro — Body text, captions, and secondary information, maintaining a legible, compact density. · `--font-source-code-pro`
- **Substitute:** monospace
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 12px, 16px, 42px
- **Line height:** 1.19, 1.67, 1.88, 2.00
- **Letter spacing:** 0.10em at 10px, 0.083em at 12px, 0.417em at 16px
- **OpenType features:** `"zero"`
- **Role:** Body text, captions, and secondary information, maintaining a legible, compact density.

### Source Code Pro — Subheadings and emphasized text, providing a slightly bolder voice while retaining the monospace aesthetic. · `--font-source-code-pro`
- **Substitute:** monospace
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 12px, 16px, 42px
- **Line height:** 1.19, 1.67, 1.88, 2.00
- **Letter spacing:** 0.313em at 16px
- **OpenType features:** `"zero"`
- **Role:** Subheadings and emphasized text, providing a slightly bolder voice while retaining the monospace aesthetic.

### Source Code Pro — Primary headlines and impactful statements, using increased weight and generous letter spacing to command attention within the dark theme. · `--font-source-code-pro`
- **Substitute:** monospace
- **Weights:** 400, 600, 700
- **Sizes:** 10px, 12px, 16px, 42px
- **Line height:** 1.19, 1.67, 1.88, 2.00
- **Letter spacing:** 0.333em at 42px
- **OpenType features:** `"zero"`
- **Role:** Primary headlines and impactful statements, using increased weight and generous letter spacing to command attention within the dark theme.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.67 | 1px | `--text-caption` |
| body | 16px | 1.67 | 6.67px | `--text-body` |
| heading | 42px | 1.88 | 14px | `--text-heading` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 50 | 50px | `--spacing-50` |
| 100 | 100px | `--spacing-100` |
| 128 | 128px | `--spacing-128` |
| 150 | 150px | `--spacing-150` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| icons | 50px |
| other | 15px |
| images | 15px |
| buttons | 10px |

### Layout

- **Page max-width:** 1170px
- **Section gap:** 50px
- **Card padding:** 15px
- **Element gap:** 15px

## Components

### Primary Action Button
**Role:** Interactive element

Solid Kippo Fuchsia background (#ee1f66) with Snow Ghost text (#ffffff), 10px border-radius, and 10px vertical, 15px horizontal padding. This is the primary call to action, demanding attention with its vibrant color.

### Standard Card
**Role:** Content container

Charcoal Surface (#29292a) background with 10px border-radius and 15px padding on all sides. Used for grouping related content in a distinct, elevated block.

### Promo Callout Card
**Role:** Featured content container

Charcoal Surface (#29292a) background with a larger 15px border-radius and generous 35px vertical, 30px horizontal padding. Used for prominent content sections requiring more visual breathing room.

### Ghost Navigation Link
**Role:** Navigation element

Transparent background with Snow Ghost text (#ffffff) and subtle 1px Snow Ghost border visible on hover or focus within a navigation menu. No border-radius or padding.

## Do's and Don'ts

### Do
- Prioritize Kippo Fuchsia (#ee1f66) exclusively for primary calls to action or key interactive states, ensuring it stands out against the dark canvas.
- Container elements like cards should use Charcoal Surface (#29292a) with radius 10px, providing subtle depth against the Pitch Black (#000000) background.
- Use Source Code Pro at weight 700 and size 42px for main headlines, applying its distinctive 0.333em letter spacing to establish brand identity.
- Employ consistent padding of 15px around content within cards and as element gaps between distinct UI elements.
- Ensure all interactive elements and content containers adhere to either 10px or 15px border-radius for a consistent soft-edged aesthetic.
- For all text content, default to Source Code Pro with Snow Ghost (#ffffff) for readability on dark backgrounds.

### Don't
- Do not introduce new saturated colors; maintain the brand focus on Kippo Fuchsia (#ee1f66) as the primary accent.
- Avoid using drop shadows for elevation; rely on background color changes from Pitch Black (#000000) to Charcoal Surface (#29292a) and border radii for depth.
- Do not use generic sans-serif fonts; the monospace Source Code Pro is integral to the brand's 'gamer tech' aesthetic.
- Never overcrowd sections; maintain a generous sectionGap of 50px between major content blocks to preserve visual breathing room.
- Avoid sharp corners on interactive components; 10px or 15px border radii are critical for the brand's softer, approachable feel.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Background | `#000000` | The foundational layer for the entire dark theme, providing a deep, immersive canvas. |
| 1 | Card Surface | `#29292a` | Elevated containers for prominent content sections, offering slight visual separation from the main background. |

## Imagery

This site uses product screenshots and abstract vector illustrations. Product screenshots are typically displayed within a mobile device mock-up, showcasing UI functionality. Abstract vector illustrations are used decoratively, sometimes with subtle gradients like Sunshine Aura or Fresh Mint Gradient. Photography is minimal, appearing primarily as small profile images of users, often desaturated or blended into the dark theme. Icons are outlined, mono-color (either Snow Ghost or Kippo Fuchsia), and have a substantial stroke weight, sometimes with a 50px border-radius creating a circular appearance. Imagery serves both as explanatory content (product UI) and decorative atmosphere (abstract graphics), maintaining a balanced density relative to the text.

## Layout

The page model is a max-width contained layout at 1170px, centered on the screen, creating a focused content area while allowing the Pitch Black background to extend full-bleed. The hero pattern features a split layout: a bold, centered headline on the left alongside a product UI screenshot within a dark mobile mock-up on the right. Sections primarily follow an alternating content arrangement, featuring textual information on one side and supporting visuals or client logos on the other. A rhythm of consistent vertical spacing is created by a section gap of 50px between major blocks, sometimes with a sub-section elementGap of 15px. Navigation is a sticky top bar with minimal links.

## Agent Prompt Guide

Quick Color Reference:
text: #ffffff
background: #000000
border: #ffffff
accent: #ee1f66
primary action: #ee1f66 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #ee1f66 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Create a feature card: Charcoal Surface (#29292a) background, 10px radius, 15px padding. Title 'Match based on what you both love' in Snow Ghost (#ffffff) using Source Code Pro weight 600 at 16px, letter-spacing 5px. Body text in Snow Ghost (#ffffff) using Source Code Pro weight 400 at 12px, letter-spacing 1px.
3. Create a navigation bar: Pitch Black (#000000) background. Left aligned logo. Right aligned navigation links 'Home', 'Comics', 'Support' as Ghost Navigation Links in Snow Ghost (#ffffff).
4. Create a download button for an app store: Primary Action Button with Kippo Fuchsia (#ee1f66) background, Snow Ghost (#ffffff) text, 10px radius, 10px vertical/15px horizontal padding. The button should display an app store icon to its left, which is outlined and white.
5. Create a callout section for partners: Pitch Black (#000000) background. Heading 'AS SEEN ON' in Snow Ghost (#ffffff) using Source Code Pro weight 400 at 16px, letter-spacing 6.67px. Display logos, e.g., 'Mashable', as interactive elements with Snow Ghost (#ffffff) text which changes to Kippo Fuchsia (#ee1f66) on hover.

## Similar Brands

- **Discord** — Dark UI with vibrant accent colors, monospace-influenced typography, and a community-focused product.
- **Twitch** — Heavy reliance on a dark theme and prominent accent colors for interactive elements, catering to a gaming audience.
- **Razer** — Gaming-focused brand with dark aesthetics and strong, singular accent colors that define interactive elements.
- **Linear** — Minimalist dark mode UI with compact, code-like typography and a focus on clean content presentation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-black: #000000;
  --color-charcoal-surface: #29292a;
  --color-snow-ghost: #ffffff;
  --color-smoke-text: #333333;
  --color-kippo-fuchsia: #ee1f66;
  --color-sunshine-aura: #ffc400;
  --gradient-sunshine-aura: linear-gradient(to right, rgb(255, 196, 0), rgb(255, 51, 224));
  --color-fresh-mint-gradient: #33beff;
  --gradient-fresh-mint-gradient: linear-gradient(to right, rgb(51, 190, 255), rgb(51, 255, 184));
  --color-silver-gloss-gradient: #cfcfcf;
  --gradient-silver-gloss-gradient: linear-gradient(to right, rgb(207, 207, 207), rgb(255, 255, 255));

  /* Typography — Font Families */
  --font-source-code-pro: 'Source Code Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.67;
  --tracking-caption: 1px;
  --text-body: 16px;
  --leading-body: 1.67;
  --tracking-body: 6.67px;
  --text-heading: 42px;
  --leading-heading: 1.88;
  --tracking-heading: 14px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-50: 50px;
  --spacing-100: 100px;
  --spacing-128: 128px;
  --spacing-150: 150px;

  /* Layout */
  --page-max-width: 1170px;
  --section-gap: 50px;
  --card-padding: 15px;
  --element-gap: 15px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-3xl: 28px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-icons: 50px;
  --radius-other: 15px;
  --radius-images: 15px;
  --radius-buttons: 10px;

  /* Surfaces */
  --surface-page-background: #000000;
  --surface-card-surface: #29292a;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-black: #000000;
  --color-charcoal-surface: #29292a;
  --color-snow-ghost: #ffffff;
  --color-smoke-text: #333333;
  --color-kippo-fuchsia: #ee1f66;
  --color-sunshine-aura: #ffc400;
  --color-fresh-mint-gradient: #33beff;
  --color-silver-gloss-gradient: #cfcfcf;

  /* Typography */
  --font-source-code-pro: 'Source Code Pro', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.67;
  --tracking-caption: 1px;
  --text-body: 16px;
  --leading-body: 1.67;
  --tracking-body: 6.67px;
  --text-heading: 42px;
  --leading-heading: 1.88;
  --tracking-heading: 14px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-50: 50px;
  --spacing-100: 100px;
  --spacing-128: 128px;
  --spacing-150: 150px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-3xl: 28px;
  --radius-full: 50px;
}
```
