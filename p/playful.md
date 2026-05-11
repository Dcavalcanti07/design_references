# Playful — Style Reference
> Gradient Playground

**Theme:** light

Playful adopts a vibrant yet refined aesthetic with a spacious layout that emphasizes content clarity. Backgrounds feature subtle gradients, creating soft washes of color. Typography is predominantly dark and compact, giving a serious counterpoint to the playful accent colors. Interactive elements utilize a vivid pink, contrasting against a canvas dominated by off-white, imparting an energetic yet sophisticated feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0f172a` | `--color-midnight-ink` | Primary text, deep neutrals for icons and borders. This near-black provides strong contrast against light surfaces |
| Vivacious Pink | `#ff2e95` | `--color-vivacious-pink` | CTA buttons, accented links, and vibrant highlights — this vivid pink defines primary interactivity and branded elements |
| Frost Canvas | `linear-gradient(225deg, #f6f2ee 0%, #ffc8c6 10%, #edd8f8 20%, #ddbef8 30%, #ce9afa 40%, #c473f3 50%, #b258e7 60%, #9c3ae7 70%, #7e24dd 80%, #5a19d0 90%, #2f07b8 100%)` | `--color-frost-canvas` | Primary page background, footer background, and subtle secondary button backgrounds. It provides a warm, soft base; Hero section and key visual backgrounds – a soft, multi-hued gradient establishing a playful and spacious atmosphere |
| Pitch Black | `#000000` | `--color-pitch-black` | Deepest text for headlines and critical user interface elements, providing absolute contrast. Also used for dark component backgrounds and shadows |
| Deep Graphite | `#111111` | `--color-deep-graphite` | Card backgrounds, section headers, and dark surface accents |
| Coal Text | `#202126` | `--color-coal-text` | Headline text for secondary sections |
| Pale Ash | `#e8e5e0` | `--color-pale-ash` | Subtle borders and dividers, providing visual structure without harsh lines |
| Cloud White | `#ffffff` | `--color-cloud-white` | Input fields, content backgrounds within cards, and for text on dark backgrounds |
| Slate Gray | `#414040` | `--color-slate-gray` | Input field text, placeholder text, and muted body copy |
| Light Taupe | `#e2dcd6` | `--color-light-taupe` | Delicate borders and secondary structural elements |
| Light Graphite | `#353535` | `--color-light-graphite` | Darkest background for subtle overlays or components |

## Tokens — Typography

### Inter — The primary typeface for all text. Its weights are used for impactful headlines at larger sizes and for clear, concise body text. The tight letter spacing for display sizes gives it a modern, compact feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700, 900
- **Sizes:** 14px, 16px, 18px, 26px, 30px, 70px, 79px
- **Line height:** 1.00, 1.15, 1.19, 1.20, 1.23, 1.33, 1.70
- **Letter spacing:** -0.002
- **Role:** The primary typeface for all text. Its weights are used for impactful headlines at larger sizes and for clear, concise body text. The tight letter spacing for display sizes gives it a modern, compact feel.

### Arial — Used for accessibility-focused elements like button labels and form inputs, providing robust legibility. · `--font-arial`
- **Substitute:** Helvetica Neue, Helvetica, sans-serif
- **Weights:** 400, 600, 700
- **Sizes:** 13px, 15px, 16px, 20px
- **Line height:** 1.20, 1.40
- **Role:** Used for accessibility-focused elements like button labels and form inputs, providing robust legibility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.4 | — | `--text-caption` |
| body | 16px | 1.2 | -0.002px | `--text-body` |
| subheading | 26px | 1.33 | -0.002px | `--text-subheading` |
| heading-sm | 30px | 1.23 | -0.002px | `--text-heading-sm` |
| heading | 70px | 1.15 | -0.002px | `--text-heading` |
| display | 79px | 1 | -0.002px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 60 | 60px | `--spacing-60` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 999px |
| cards | 44px |
| images | 16px |
| buttons | 99px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08...` | `--shadow-xl` |

### Layout

- **Page max-width:** 1500px
- **Section gap:** 113px
- **Card padding:** 12px
- **Element gap:** 10px

## Components

### Ghost Button
**Role:** Navigational or secondary actions where visual weight should be minimal.

Transparent background, 'Midnight Ink' (0f172a) text, no border or explicit radius. Padding: 12px vertical, 32px horizontal.

### Primary Action Button
**Role:** Main calls to action.

Filled with 'Vivacious Pink' (ff2e95), 'Frost Canvas' (f6f2ee) text, 99px border-radius, giving it a pill shape. Padding: 14px vertical, 24px horizontal. Arial 600 at 15px.

### Circular Secondary Button
**Role:** Icon-only or small, focused interactive elements.

Filled with 'Frost Canvas' (f6f2ee), 'Vivacious Pink' (ff2e95) text, 50% border-radius for a perfect circle. No padding specified (implied from 0px values).

### Feature Card
**Role:** Displaying product features or content blocks.

Background 'Deep Graphite' (111111), 44px border-radius. Shadow: rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08) 0px 2px 8px 0px.

### Input Field
**Role:** Collecting user data.

Transparent background, 'Slate Gray' (414040) text, 'Slate Gray' (414040) border. No explicit border-radius (implied from 0px values). Arial 400 at 16px.

## Do's and Don'ts

### Do
- Always use a generous `sectionGap` of 113px to maintain spaciousness between primary content blocks.
- Apply `border-radius: 44px` to article cards and larger UI containers to soften surfaces and align with the playful aesthetic.
- Utilize 'Vivacious Pink' (#ff2e95) exclusively for primary calls to action, active navigation states, and key interactive highlights.
- Ensure all primary headings use Inter font with `letter-spacing: -0.002em` to achieve a compact, signature appearance.
- Prioritize 'Frost Canvas' (#f6f2ee) for main page backgrounds to maintain a light and airy feel.
- Employ the dual shadow `rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08) 0px 2px 8px 0px` for elevated cards.
- Use 'Midnight Ink' (#0f172a) for body text and secondary element borders for strong contrast and clarity.

### Don't
- Do not use dark backgrounds for sections that contain extensive body copy; maintain a light background to preserve readability.
- Avoid arbitrary border radii; stick to the established system tokens: 44px for cards, 99px for buttons, 16px for images.
- Never introduce new chromatic colors outside of 'Vivacious Pink' (#ff2e95) and the brand gradient for UI elements.
- Do not use a default system font for any body text or headings; 'Inter' is paramount for brand identity.
- Avoid dense, information-heavy blocks without sufficient padding or `elementGap` of at least 10px.
- Do not add any additional box-shadows to elements other than cards; rely on the subtle elevation provided by background color differences.

## Elevation

- **Feature Card:** `rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08) 0px 2px 8px 0px`

## Imagery

The site uses a mix of playful, graphic-style illustrations for app icons and abstract, colorful gradients as hero and background elements. App icons are displayed as contained, rounded-corner elements, sometimes overlapping, showcasing a product-focused content. There are also simple, functional icons (like chevron arrows) that are outlined, and monochrome 'Midnight Ink' or 'Slate Gray'. Imagery serves primarily as decorative atmosphere and product showcase, with a medium density relative to text.

## Layout

The page adheres to a max-width of 1500px, centered on the screen. The hero section is full-bleed with a top custom gradient background, featuring a large, centered headline, subtext, and an input/button pair. Subsequent sections maintain consistent vertical spacing of 113px and alternate between centered text blocks and grids of feature cards. Navigation is a minimal top bar. Overall, the layout is spacious, allowing content to breathe.

## Agent Prompt Guide

Quick Color Reference: 
text: #0f172a
background: #f6f2ee
border: #e8e5e0
accent: #ff2e95
primary action: #ff2e95 (filled action)

Example Component Prompts:
Create a Primary Action Button: #ff2e95 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a Feature Card: Background 'Deep Graphite' (111111), 44px border-radius, shadow 'rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08) 0px 2px 8px 0px'. Content inside should use Inter 16px weight 400 in 'Cloud White' (ffffff) for body, with 12px card padding. 

Create a Ghost Button: Background transparent, 'Midnight Ink' (0f172a) text using Arial 16px weight 400. Padding: 12px vertical, 32px horizontal. Used for secondary navigation like 'When will it be available?' 

## Similar Brands

- **Figma** — Clean, spacious UI with strong typography and a single vibrant accent color for interactivity.
- **Linear** — Minimalist aesthetic with focus on subtle shadows/borders for cards and interaction, strong typographic hierarchy.
- **Notion** — Understated design, heavy reliance on grayscale neutrals, and a precise type system to convey functionality and content.
- **Stripe** — Elegant visual design with careful use of gradients, clean typography, and a restrained color palette where accents stand out.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0f172a;
  --color-vivacious-pink: #ff2e95;
  --color-frost-canvas: #f6f2ee;
  --gradient-frost-canvas: linear-gradient(225deg, #f6f2ee 0%, #ffc8c6 10%, #edd8f8 20%, #ddbef8 30%, #ce9afa 40%, #c473f3 50%, #b258e7 60%, #9c3ae7 70%, #7e24dd 80%, #5a19d0 90%, #2f07b8 100%);
  --color-pitch-black: #000000;
  --color-deep-graphite: #111111;
  --color-coal-text: #202126;
  --color-pale-ash: #e8e5e0;
  --color-cloud-white: #ffffff;
  --color-slate-gray: #414040;
  --color-light-taupe: #e2dcd6;
  --color-light-graphite: #353535;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.002px;
  --text-subheading: 26px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.002px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.23;
  --tracking-heading-sm: -0.002px;
  --text-heading: 70px;
  --leading-heading: 1.15;
  --tracking-heading: -0.002px;
  --text-display: 79px;
  --leading-display: 1;
  --tracking-display: -0.002px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-180: 180px;

  /* Layout */
  --page-max-width: 1500px;
  --section-gap: 113px;
  --card-padding: 12px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 44px;
  --radius-full: 99px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-tags: 999px;
  --radius-cards: 44px;
  --radius-images: 16px;
  --radius-buttons: 99px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08) 0px 2px 8px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0f172a;
  --color-vivacious-pink: #ff2e95;
  --color-frost-canvas: #f6f2ee;
  --color-pitch-black: #000000;
  --color-deep-graphite: #111111;
  --color-coal-text: #202126;
  --color-pale-ash: #e8e5e0;
  --color-cloud-white: #ffffff;
  --color-slate-gray: #414040;
  --color-light-taupe: #e2dcd6;
  --color-light-graphite: #353535;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.4;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.002px;
  --text-subheading: 26px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.002px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.23;
  --tracking-heading-sm: -0.002px;
  --text-heading: 70px;
  --leading-heading: 1.15;
  --tracking-heading: -0.002px;
  --text-display: 79px;
  --leading-display: 1;
  --tracking-display: -0.002px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-60: 60px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 44px;
  --radius-full: 99px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.22) 0px 32px 80px 0px, rgba(0, 0, 0, 0.08) 0px 2px 8px 0px;
}
```
