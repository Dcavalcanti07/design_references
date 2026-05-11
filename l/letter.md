# Letter — Style Reference
> Sublime Depth, Minimal Interface

**Theme:** light

Letter employs a 'dark academia meets finance' aesthetic, characterized by dramatic, almost painterly dark backgrounds with glowing abstract forms that provide depth and visual interest. Over this, a minimalist, high-contrast typography system ensures clarity and seriousness. Components are unfussy, with sharp corners and subtle borders, allowing the rich backgrounds to take center stage, creating an atmosphere of understated luxury and technological sophistication. The overall impression is one of grounded authority with a hint of digital mystique.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight | `#000000` | `--color-midnight` | Page backgrounds, hero sections, primary text for dark backgrounds |
| Canvas White | `#ffffff` | `--color-canvas-white` | Card backgrounds, primary text on dark elements, button fills |
| Carbon | `#191b1f` | `--color-carbon` | Primary text on light backgrounds, hero subheadings, button backgrounds |
| Ghost Gray | `#f6f9f9` | `--color-ghost-gray` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Whisper Gray | `#e6ebec` | `--color-whisper-gray` | Lightest grey for borders and disabled text |
| Stone Whisper | `#9fabad` | `--color-stone-whisper` | Muted secondary text, copyright information |
| Deep Teal | `#186f64` | `--color-deep-teal` | Teal action color for filled buttons, selected navigation states, and focused conversion moments. |
| Royal Violet | `#536eff` | `--color-royal-violet` | Violet action color for filled buttons, selected navigation states, and focused conversion moments. |
| Grape Dusk | `#644bc4` | `--color-grape-dusk` | Violet action color for filled buttons, selected navigation states, and focused conversion moments. |
| Ocean Gaze | `#154ea5` | `--color-ocean-gaze` | Blue action color for filled buttons, selected navigation states, and focused conversion moments. |
| Lilac Mist | `#e6def0` | `--color-lilac-mist` | Hairline borders, dividers, input outlines, and card edges on light surfaces. |
| Mint Glaze | `#eefcef` | `--color-mint-glaze` | Hairline borders, dividers, input outlines, and card edges on light surfaces. |
| Canyon Haze | `#fcede1` | `--color-canyon-haze` | Hairline borders, dividers, input outlines, and card edges on light surfaces. |

## Tokens — Typography

### Albra Sans — Display and large headings — evokes a sense of established authority and refined impact through its robust weight and subtle tracking. · `--font-albra-sans`
- **Substitute:** Playfair Display
- **Weights:** 600
- **Sizes:** 22px, 46px, 80px
- **Line height:** 1.10, 1.20
- **Letter spacing:** 0.0200em
- **Role:** Display and large headings — evokes a sense of established authority and refined impact through its robust weight and subtle tracking.

### Neufile Grotesk Extended — Body copy, navigation, buttons, and subheadings — a compact, strong sans-serif that provides modern legibility without sacrificing character. · `--font-neufile-grotesk-extended`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 13px, 16px, 28px
- **Line height:** 1.00, 1.30, 1.40, 2.00
- **Letter spacing:** normal
- **Role:** Body copy, navigation, buttons, and subheadings — a compact, strong sans-serif that provides modern legibility without sacrificing character.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 2 | — | `--text-caption` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 22px | 1.1 | 0.44px | `--text-subheading` |
| heading-sm | 28px | 1.3 | — | `--text-heading-sm` |
| heading | 46px | 1.2 | 0.92px | `--text-heading` |
| display | 80px | 1.2 | 1.6px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |

### Border Radius

| Element | Value |
|---------|-------|
| links | 2px |
| buttons | 2px |

### Layout

- **Page max-width:** 1440px
- **Section gap:** 64px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Dark Button
**Role:** Call to action for joining or getting started.

Background: Carbon (#191b1f), Text: Canvas White (#ffffff), Border: Canvas White (#ffffff), Radius: 2px, Padding: 12px vertical, 27.2px horizontal. Uses Neufile Grotesk Extended, weight 400.

### Secondary Light Button
**Role:** Alternative call to action, often for signing in or less prominent actions.

Background: Canvas White (#ffffff), Text: Carbon (#191b1f), Border: Carbon (#191b1f), Radius: 2px, Padding: 12px vertical, 27.2px horizontal. Uses Neufile Grotesk Extended, weight 400.

### Teal Action Button
**Role:** Primary action for 'Invest' or 'Browse' related features.

Background: Deep Teal (#186f64), Text: Canyon Haze (#fcede1), Border: Canyon Haze (#fcede1), Radius: 2px, Padding: 12px vertical, 27.2px horizontal. Uses Neufile Grotesk Extended, weight 400.

### Violet Action Button
**Role:** Primary action for 'Borrow' related features.

Background: Royal Violet (#536eff), Text: Whisper Gray (#e6ebec), Border: Whisper Gray (#e6ebec), Radius: 2px, Padding: 12px vertical, 27.2px horizontal. Uses Neufile Grotesk Extended, weight 400.

### Ghost Card
**Role:** Decorative card used as a background or for subtle visual separation without strong outlines.

Background: transparent (rgba(0,0,0,0)), Border: none, Radius: 0px, Padding: 0px.

### Surface Card
**Role:** Content card providing a slightly raised, clean surface for information.

Background: Ghost Gray (#f6f9f9), Border: none, Radius: 0px, Padding: 0px.

### Navigation Link
**Role:** Top-level navigation items.

Text: Carbon (#191b1f), Neufile Grotesk Extended.

## Do's and Don'ts

### Do
- Prioritize Neufile Grotesk Extended for all body text, buttons, and navigation, maintaining normal letter-spacing for high legibility.
- Use Albra Sans with 0.0200em letter-spacing for all headings and display text (`h1`-`h3`) to convey sophistication and impact.
- Apply a consistent 2px border radius to all interactive elements like buttons and links to maintain a sharp, deliberate feel.
- Employ Midnight (#000000) for hero section backgrounds and large textual content over them, creating a dramatic, immersive experience.
- Use Ghost Gray (#f6f9f9) as a subtle background for content sections or light cards, contrasting with the dramatic dark hero.
- Reserve Deep Teal (#186f64) for primary calls to action, ensuring attention is drawn to key interactive elements.
- Maintain maximum content width at 1440px, centering all major content blocks to ensure consistent presentation.

### Don't
- Avoid using curved or soft shapes; all radii should be sharp and minimal (2px) or absent (0px).
- Do not introduce strong drop shadows; the design relies on background gradients and subtle surface changes for depth, not elevation.
- Steer clear of overly saturated, single-color backgrounds for main content areas; maintain the subdued, high-contrast palette.
- Do not use generic system fonts; stick to Neufile Grotesk Extended and Albra Sans for brand continuity.
- Refrain from using thin weights for body or navigation text; Neufile Grotesk Extended should be used at 400 or 500 weight.
- Do not deviate from the established 12px vertical and 27.2px horizontal padding for primary actions; consistency is key.
- Avoid overly dense information layouts; utilize the 16px element gap and ample section gaps to create a sense of breathing room and exclusivity.

## Imagery

The visual language is characterized by abstract 3D rendered forms with metallic or translucent surfaces, often set against a gradient-heavy, dark, moody background. These visuals act primarily as decorative atmosphere and brand representation, rather than explanatory content. They are typically contained within sections, not full-bleed images, and may feature subtle blur filters. On lighter sections, these forms appear to be more crystalline and less moody. The overall effect is sophisticated and slightly mysterious, fitting for a high-net-worth financial institution.

## Layout

The site uses a contained page model with a maximum width of 1440px, centered on the screen. The hero section is full-bleed and dramatic, featuring a large centered headline and subtext over an abstract dark background. Subsequent sections often alternate between two primary content arrangements: a full-width header over a light background, and two-column layouts where text is left-aligned and paired with a visual element on the right (or vice-versa). Vertical rhythm is established through consistent section gaps, creating a spacious and unhurried feel. Navigation is a minimalist top bar, sticky at the top, integrating branding with key menu items and action buttons.

## Agent Prompt Guide

Quick Color Reference: 
text: #191b1f
background: #ffffff
border: #e6ebec
accent: #536eff
primary action: #186f64 (filled action)

Example Component Prompts:
1. Create a hero section: Midnight (#000000) background. Headline 'Beyond banking' in Albra Sans, 80px, weight 600, Canvas White text, letter-spacing 1.6px. Subtext 'Thoughtful finance and modern wealth management for high net worth individuals.' in Neufile Grotesk Extended, 28px, weight 400, Canvas White text.
2. Create a Teal Action Button: Deep Teal (#186f64) background, Canyon Haze (#fcede1) text and border, 2px radius, 12px vertical / 27.2px horizontal padding, 'Invest Now' label in Neufile Grotesk Extended weight 400.
3. Create a Surface Card: Ghost Gray (#f6f9f9) background, 0px radius, 0px padding. Inside, a heading 'FDIC insured accounts' in Albra Sans, 22px, weight 600, Carbon (#191b1f) text, letter-spacing 0.44px. Below it, body text 'Checking accounts and cards for family and staff.' in Neufile Grotesk Extended, 16px, weight 400, Carbon (#191b1f) text.
4. Create a Secondary Light Button: Canvas White (#ffffff) background, Carbon (#191b1f) text and border, 2px radius, 12px vertical / 27.2px horizontal padding, 'Sign In' label in Neufile Grotesk Extended weight 400.

## Similar Brands

- **Ramp** — Similar focus on modern finance with a clean, high-contrast UI and a restrained, premium aesthetic.
- **Mercury** — Adopts a sophisticated, dark-mode approach for banking, often using subtle gradients and sharp typography.
- **Stripe** — Combines a strong brand identity with clean typography, minimalist components, and strategic use of negative space in financial services.
- **Linear** — Employs dark interfaces, precision typography, and subtle component styling to convey efficiency and advanced functionality.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight: #000000;
  --color-canvas-white: #ffffff;
  --color-carbon: #191b1f;
  --color-ghost-gray: #f6f9f9;
  --color-whisper-gray: #e6ebec;
  --color-stone-whisper: #9fabad;
  --color-deep-teal: #186f64;
  --color-royal-violet: #536eff;
  --color-grape-dusk: #644bc4;
  --color-ocean-gaze: #154ea5;
  --color-lilac-mist: #e6def0;
  --color-mint-glaze: #eefcef;
  --color-canyon-haze: #fcede1;

  /* Typography — Font Families */
  --font-albra-sans: 'Albra Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neufile-grotesk-extended: 'Neufile Grotesk Extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 2;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 22px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.44px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.3;
  --text-heading: 46px;
  --leading-heading: 1.2;
  --tracking-heading: 0.92px;
  --text-display: 80px;
  --leading-display: 1.2;
  --tracking-display: 1.6px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Layout */
  --page-max-width: 1440px;
  --section-gap: 64px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 2px;

  /* Named Radii */
  --radius-links: 2px;
  --radius-buttons: 2px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight: #000000;
  --color-canvas-white: #ffffff;
  --color-carbon: #191b1f;
  --color-ghost-gray: #f6f9f9;
  --color-whisper-gray: #e6ebec;
  --color-stone-whisper: #9fabad;
  --color-deep-teal: #186f64;
  --color-royal-violet: #536eff;
  --color-grape-dusk: #644bc4;
  --color-ocean-gaze: #154ea5;
  --color-lilac-mist: #e6def0;
  --color-mint-glaze: #eefcef;
  --color-canyon-haze: #fcede1;

  /* Typography */
  --font-albra-sans: 'Albra Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neufile-grotesk-extended: 'Neufile Grotesk Extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 2;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 22px;
  --leading-subheading: 1.1;
  --tracking-subheading: 0.44px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.3;
  --text-heading: 46px;
  --leading-heading: 1.2;
  --tracking-heading: 0.92px;
  --text-display: 80px;
  --leading-display: 1.2;
  --tracking-display: 1.6px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;

  /* Border Radius */
  --radius-sm: 2px;
}
```
