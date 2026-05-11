# The online bank — Style Reference
> Teal and White Ledger. A clear, high-contrast digital ledger laid out on a clean white page, highlighted by a single, prominent teal ink.

**Theme:** light

N26 employs a utilitarian, almost institutional aesthetic, built around a dominant teal that provides a singular brand anchor against an otherwise stark monochrome palette. The design emphasizes functional clarity, using crisp lines and generous whitespace to present complex financial information in an accessible manner. The restricted use of color focuses attention on key interactive elements and a distinct brand presence, avoiding visual clutter.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Arctic White | `#ffffff` | `--color-arctic-white` | Page backgrounds, card surfaces, primary button background. |
| Deep Teal | `#088177` | `--color-deep-teal` | Primary brand color for large hero sections, strong call-to-action buttons, and active indicators. It’s the visual core of the brand. |
| Ink Black | `#1b1b1b` | `--color-ink-black` | Primary text color for body, headings, and UI elements. Provides high contrast against light backgrounds. |
| Horizon Gray | `#e9e9e9` | `--color-horizon-gray` | Subtle borders and dividers for UI elements, defining structure without harshness. |
| Ghost White | `#faf8f5` | `--color-ghost-white` | Subtle background for differentiated sections or groupings within a light theme. |
| Slate Gray | `#6d6d6d` | `--color-slate-gray` | Secondary text, descriptive elements. Provides a softer hierarchy than Ink Black. |
| Warning Red | `#d80027` | `--color-warning-red` | Semantic color for warnings or negative indicators, sparingly used. |
| Caution Yellow | `#ffda44` | `--color-caution-yellow` | Semantic color for cautious states or highlights, used minimally. |
| Accent Teal | `#06736a` | `--color-accent-teal` | Slightly darker shade of Deep Teal, used for hover states on interactive elements and secondary brand components. |

## Tokens — Typography

### N26 — Used for all standard text: body copy, navigation labels, button text, and smaller headings. The varied letter-spacing at smaller sizes aims for optical clarity in dense financial information. · `--font-n26`
- **Substitute:** Open Sans
- **Weights:** 400, 500, 700
- **Sizes:** 11px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.33, 1.38, 1.43, 1.50, 1.60
- **Letter spacing:** -0.18px
- **Role:** Used for all standard text: body copy, navigation labels, button text, and smaller headings. The varied letter-spacing at smaller sizes aims for optical clarity in dense financial information.

### N26-Extended — Reserved for impactful headlines and display text, leveraging its wider character set for grandeur. Lower line heights give a compact, strong appearance to headings. · `--font-n26-extended`
- **Substitute:** Montserrat
- **Weights:** 400, 500
- **Sizes:** 18px, 32px, 44px, 58px, 80px
- **Line height:** 1.10, 1.20, 1.25, 1.50
- **Letter spacing:** normal
- **Role:** Reserved for impactful headlines and display text, leveraging its wider character set for grandeur. Lower line heights give a compact, strong appearance to headings.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 14.63 | -0.18px | `--text-caption` |
| body-sm | 14px | 19.32 | -0.14px | `--text-body-sm` |
| body | 16px | 22.88 | -0.25px | `--text-body` |
| subheading | 18px | 27 | -0.34px | `--text-subheading` |
| heading-sm | 24px | 31.92 | — | `--text-heading-sm` |
| heading | 32px | 38.4 | — | `--text-heading` |
| heading-lg | 44px | 48.4 | — | `--text-heading-lg` |
| display | 58px | 63.8 | — | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 4px |
| images | 24px |
| buttons | 6px |
| input_fields | 4px |

### Layout

- **Section gap:** 64-80px
- **Card padding:** 12-24px
- **Element gap:** 4-16px

## Components

### Primary Call-to-Action Button
**Role:** Interactive element

Solid 'Deep Teal' background (#088177) with 'Arctic White' (#ffffff) text, 6px border-radius, and 12px vertical, 24px horizontal padding. Font is N26 weight 400.

### Secondary Outlined Button
**Role:** Interactive element

Transparent background with 'Deep Teal' (#088177) text and a 1px 'Deep Teal' border, 6px border-radius, and 12px vertical, 24px horizontal padding. Font is N26 weight 400.

### Navigation Link Button
**Role:** Interactive element

Transparent background, 'Ink Black' (#1b1b1b) text, 8px border-radius, and 4px vertical, 8px horizontal padding. Font is N26 weight 400.

### Header Navigation Link
**Role:** Navigation

Transparent background, 'Ink Black' (#1b1b1b) text, 0px border-radius, 0px padding. Font is N26 weight 400.

### Informational QR Module
**Role:** Utility element

White background with a 1px 'Horizon Gray' (#e9e9e9) border and 4px radius. Text is 'Ink Black' (#1b1b1b).

## Do's and Don'ts

### Do
- Use 'Deep Teal' (#088177) exclusively for primary calls-to-action and key branding in hero sections.
- Maintain high contrast text with 'Ink Black' (#1b1b1b) on 'Arctic White' (#ffffff) backgrounds for all body and heading content.
- Apply 'Horizon Gray' (#e9e9e9) for subtle UI borders and dividers to structure content without heavy lines.
- Structure display headings with 'N26-Extended' font family, using weights 400 or 500 for impact.
- Utilize 'Arctic White' (#ffffff) for page backgrounds and elevated card surfaces, creating a clean canvas.
- Apply a 6px border-radius for all primary and secondary buttons, balancing softness with a structured look.

### Don't
- Do not introduce additional saturated colors beyond 'Deep Teal' for primary interactive elements; color saturation is highly restrained.
- Avoid applying heavy shadows or complex gradients; the system relies on flat colors and distinct borders for depth.
- Do not deviate from the specified tight letter-spacing for 'N26' font at smaller sizes, as it's critical for text clarity.
- Avoid using 'N26-Extended' font for body copy or small text; it is reserved for headlines.
- Do not use different radius values for buttons and input fields; consistently apply 6px for buttons and 4px for inputs.
- Do not use highly decorative imagery; illustrations and photos should be either product-focused or abstract and minimal.

## Imagery

The site's visual language is dominated by UI elements and product-focused graphics. Photography is absent, replaced by crisp product screenshots or abstract, clean graphics to illustrate financial concepts. Icons are filled, monochrome, matching the 'Ink Black' text where 'Deep Teal' is the primary background. Imagery is primarily explanatory and functional, contained within clear sections, avoiding full-bleed or overlapping styles. The density is moderate, allowing text to remain dominant while visuals support key messages.

## Layout

The page adheres to a max-width centered content model, creating visual stability. The header floats at the top, consistent across different content. The hero section is full-bleed 'Deep Teal' with a prominent centered headline and descriptive text, followed by the primary CTA. Content sections follow a vertical rhythm with generous spacing. Information is presented in clear, distinct blocks, often utilizing a multi-column grid for features or data like the 'Risk Indicator' modules. The layout is spacious with strong visual separation between content blocks.

## Agent Prompt Guide

**Quick Color Reference:**
- Text: #1b1b1b (Ink Black)
- Background: #ffffff (Arctic White)
- CTA Background: #088177 (Deep Teal)
- CTA Text: #ffffff (Arctic White)
- Border: #e9e9e9 (Horizon Gray)
- Secondary Text: #6d6d6d (Slate Gray)

**3-5 Example Component Prompts:**
1. Create a Hero Section: 'Deep Teal' (#088177) full-width background. Centered 'display' heading in 'Arctic White' (#ffffff) using 'N26-Extended' font, weight 500, line-height 1.1. Subtext 'body' in 'Arctic White' (#ffffff). A 'Primary Call-to-Action Button' ('Open free bank account') centered below the subtext.
2. Design a 'Risk Indicator Card': 'Arctic White' (#ffffff) background, 1px 'Horizon Gray' (#e9e9e9) border, 0px border-radius. Title 'Risk indicator for all N26 accounts' as 'body' text, 'Ink Black' (#1b1b1b), N26 font weight 700. Content text 'caption' in 'Ink Black' (#1b1b1b), N26 font weight 400. Padding 24px everywhere.
3. Implement a Header Navigation Bar: 'Arctic White' (#ffffff) background, 73px height. Left-aligned N26 Logo. Right-aligned 'Navigation Link Button' ('Log in') using N26 font, weight 400. Next to it, a 'Primary Call-to-Action Button' ('Open free bank account').
4. Generate a Secondary Feature Card: 'Arctic White' (#ffffff) background, 4px border-radius, no border. 'heading-sm' title 'Save flexibly. Earn 1.30 % AER.' in 'Ink Black' (#1b1b1b), N26 font weight 700. 'body' description in 'Ink Black' (#1b1b1b), N26 font weight 400. Padding 24px vertical, 16px horizontal.
5. Create a 'Get The App' QR Module: 'Arctic White' (#ffffff) background, 1px 'Horizon Gray' (#e9e9e9) border, 4px border-radius. Centered QR code. Below the QR code, 'body-sm' text 'Get the app' in 'Ink Black' (#1b1b1b), N26 font weight 400.

## Similar Brands

- **Revolut** — Clean, minimalist UI with a strong accent color against a neutral base, focusing on financial data clarity.
- **Monzo** — Digital banking identity featuring a focused accent color for branding and CTAs, simple typography, and structured layouts.
- **Wise (formerly TransferWise)** — High-contrast text on white backgrounds, strong geometric branding with a single dominant brand color against a very clean aesthetic.
- **Starling Bank** — Bright, clear, and functional interface with a signature brand color used for primary interaction and identity. Emphasis on information hierarchy.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-arctic-white: #ffffff;
  --color-deep-teal: #088177;
  --color-ink-black: #1b1b1b;
  --color-horizon-gray: #e9e9e9;
  --color-ghost-white: #faf8f5;
  --color-slate-gray: #6d6d6d;
  --color-warning-red: #d80027;
  --color-caution-yellow: #ffda44;
  --color-accent-teal: #06736a;

  /* Typography — Font Families */
  --font-n26: 'N26', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-n26-extended: 'N26-Extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 14.63;
  --tracking-caption: -0.18px;
  --text-body-sm: 14px;
  --leading-body-sm: 19.32;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 22.88;
  --tracking-body: -0.25px;
  --text-subheading: 18px;
  --leading-subheading: 27;
  --tracking-subheading: -0.34px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 31.92;
  --text-heading: 32px;
  --leading-heading: 38.4;
  --text-heading-lg: 44px;
  --leading-heading-lg: 48.4;
  --text-display: 58px;
  --leading-display: 63.8;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 64-80px;
  --card-padding: 12-24px;
  --element-gap: 4-16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;

  /* Named Radii */
  --radius-cards: 4px;
  --radius-images: 24px;
  --radius-buttons: 6px;
  --radius-inputfields: 4px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-arctic-white: #ffffff;
  --color-deep-teal: #088177;
  --color-ink-black: #1b1b1b;
  --color-horizon-gray: #e9e9e9;
  --color-ghost-white: #faf8f5;
  --color-slate-gray: #6d6d6d;
  --color-warning-red: #d80027;
  --color-caution-yellow: #ffda44;
  --color-accent-teal: #06736a;

  /* Typography */
  --font-n26: 'N26', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-n26-extended: 'N26-Extended', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 14.63;
  --tracking-caption: -0.18px;
  --text-body-sm: 14px;
  --leading-body-sm: 19.32;
  --tracking-body-sm: -0.14px;
  --text-body: 16px;
  --leading-body: 22.88;
  --tracking-body: -0.25px;
  --text-subheading: 18px;
  --leading-subheading: 27;
  --tracking-subheading: -0.34px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 31.92;
  --text-heading: 32px;
  --leading-heading: 38.4;
  --text-heading-lg: 44px;
  --leading-heading-lg: 48.4;
  --text-display: 58px;
  --leading-display: 63.8;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-3xl: 24px;
}
```
