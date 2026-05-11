# Eclipse — Style Reference
> Cosmic Rave Command Center: stark black and white punctuated by electric green glow.

**Theme:** dark

Eclipse employs a high-contrast, 'cosmic rave' aesthetic, using crisp black-on-white text and large display typography. A vibrant neon green serves as the primary accent, appearing as glowing highlights, outlined ghost buttons, and an active primary action color. Typography is monumental, with condensed sans-serifs dominating headlines, while UI components are generally lightweight, often outlined or 'ghost' in style, with generous rounded corners hinting at a playful, energetic disposition. Layouts are spacious, providing ample negative space for the bold visual elements to stand out, often contrasting stark dark sections with bright white ones.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Page backgrounds, primary text, prominent borders, secondary button backgrounds (ghost style), icon fills |
| Canvas White | `#ffffff` | `--color-canvas-white` | Major surface backgrounds, highlighted text, outlined button borders and text |
| Electric Mint | `#a1fea0` | `--color-electric-mint` | Primary action button backgrounds, active link text, glowing accents, decorative borders, interactive states |
| Muted Ash | `#888680` | `--color-muted-ash` | Subtle secondary text or UI elements, based on token hint |
| Pale Stone | `#dfddd6` | `--color-pale-stone` | Light background elements or tertiary borders, based on token hint |
| Graphite | `#302f2c` | `--color-graphite` | Darker secondary text or subtle background panels, based on token hint |

## Tokens — Typography

### Gt Alpina Condensed — Dominant display and major heading font. Its ultra-light weights create a distinct, airy yet impactful presence, critical for the brand's 'monumental but not heavy' feel. · `--font-gt-alpina-condensed`
- **Substitute:** Montserrat Condensed
- **Weights:** 100, 200
- **Sizes:** 24px, 33px, 44px, 46px, 61px, 64px, 88px, 120px, 562px
- **Line height:** 0.80, 1.00, 1.10, 1.13, 1.16, 1.20
- **Letter spacing:** -0.0600em at 562px, -0.0400em at 120px, -0.0300em at 88px, -0.0100em at 64px
- **Role:** Dominant display and major heading font. Its ultra-light weights create a distinct, airy yet impactful presence, critical for the brand's 'monumental but not heavy' feel.

### Barlow Condensed — Utility font for navigation, buttons, and larger informational text. Its condensed nature supports a compact, highly legible UI, while maintaining visual harmony with the larger display font. Used for both interactive elements and feature descriptions. · `--font-barlow-condensed`
- **Substitute:** Oswald
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 16px, 32px, 44px, 48px, 80px, 96px, 120px, 182px
- **Line height:** 0.80, 0.83, 0.90, 1.00, 1.19, 1.20, 1.25, 1.50, 1.60
- **Letter spacing:** -0.0300em at 182px, -0.0200em at 96px, 0.1000em at 44px, 0.1300em at 32px, 0.2000em at 16px
- **Role:** Utility font for navigation, buttons, and larger informational text. Its condensed nature supports a compact, highly legible UI, while maintaining visual harmony with the larger display font. Used for both interactive elements and feature descriptions.

### Atlas Typewriter — Mono-spaced font for body copy, subheadings, and informational text. Its distinctive typewriter aesthetic adds a retro-futuristic, tech-oriented layer to the brand's voice. · `--font-atlas-typewriter`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 12px, 16px, 18px
- **Line height:** 1.00, 1.56, 1.60
- **Letter spacing:** 0.2000em
- **Role:** Mono-spaced font for body copy, subheadings, and informational text. Its distinctive typewriter aesthetic adds a retro-futuristic, tech-oriented layer to the brand's voice.

### math — Specialized font for mathematical or technical notation/symbols. · `--font-math`
- **Substitute:** Noto Sans Math
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Specialized font for mathematical or technical notation/symbols.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | 0.02px | `--text-caption` |
| body-sm | 16px | 1.6 | 0.02px | `--text-body-sm` |
| body | 18px | 1.56 | 0.02px | `--text-body` |
| subheading | 24px | 1.2 | -0.005px | `--text-subheading` |
| heading-sm | 32px | 1.25 | 0.013px | `--text-heading-sm` |
| heading | 44px | 1.19 | 0.01px | `--text-heading` |
| heading-lg | 61px | 1.13 | -0.01px | `--text-heading-lg` |
| display | 562px | 0.8 | -0.06px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| other | 25px |
| buttons | 100px |
| navItems | 100px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 10px

## Components

### Ghost Navigation Button
**Role:** Primary navigation links and secondary actions, typically found in headers or footers.

Text in Canvas White (#ffffff) on a transparent background, with a 1px solid Canvas White (#ffffff) border, no border-radius (0px), and no padding or shadows to emphasize lightness. Uses Barlow Condensed 400.

### Mint Pill Button
**Role:** Prominent calls to action.

Electric Mint (#a1fea0) background with Midnight Ink (#000000) text (Barlow Condensed 400). Features a 100px border-radius for a distinct pill shape and 10px padding vertically, 18px horizontally.

### Dark Pill Button
**Role:** Secondary calls to action or alternative actions.

Midnight Ink (#000000) background with Canvas White (#ffffff) text (Barlow Condensed 400). Features a 100px border-radius for a distinct pill shape and 10px padding vertically, 18px horizontally.

### Framed Text Button
**Role:** General interactive elements or links with emphasis.

Canvas White (#ffffff) background with Midnight Ink (#000000) text (Barlow Condensed 400). Styled with a distinct 25px border-radius and generous 32px padding on all sides, often used for larger interactive blocks.

### Outline Investor Card
**Role:** Listing partners or investors with a subtle visual presence.

Transparent background with a 1px Midnight Ink (#000000) border, 0px border-radius, and 0px padding. Text is typically Midnight Ink (#000000) using Atlas Typewriter.

### Text Badge
**Role:** Categorization or short labels.

Transparent background with Midnight Ink (#000000) text (Barlow Condensed 400) and no border-radius. Padding is 0px initially, indicating it relies on parent spacing.

## Do's and Don'ts

### Do
- Prioritize Gt Alpina Condensed for all primary headlines, leveraging its ultra-light weights (100, 200) for monumental presence, e.g., Headline at 562px weight 100, letter-spacing -0.06em.
- Use Electric Mint (#a1fea0) exclusively for primary interactive states, glow effects, and functional highlights, ensuring it always stands out against neutral backgrounds.
- Implement a 100px border-radius for all primary action buttons to achieve a consistent pill shape, e.g., `border-radius: 100px;`.
- Maintain a clear visual hierarchy by switching between dark (Midnight Ink #000000) and light (Canvas White #ffffff) background sections with strong contrast.
- Apply Atlas Typewriter 400 with 0.20em letter-spacing for standard body and descriptive text to maintain the stylistic, tech-oriented brand voice.
- Incorporate a generous 24px section gap to provide ample breathing room between major content blocks on the page.
- Use 1px borders of either Midnight Ink (#000000) or Canvas White (#ffffff) for subtle structural definition and ghost components.

### Don't
- Do not use Electric Mint (#a1fea0) for large background areas or non-interactive decorative elements, as its impact is diluted by overuse.
- Avoid using multiple colors for text; stick to Midnight Ink (#000000) on light backgrounds and Canvas White (#ffffff) on dark backgrounds for readability.
- Do not introduce sharp corners or small radii for interactive elements; the pill-shaped 100px radius for buttons is a signature feature.
- Do not use heavy box-shadows or complex gradients; the design thrives on flat surfaces, high contrast, and subtle glow (filter) effects.
- Avoid dense, information-packed sections without clear visual separation; maintain significant vertical spacing (24px section gap) between content blocks.
- Do not clutter navigation with filled buttons; Ghost Navigation Buttons are preferred for their lightweight, subtle presence.
- Do not mix font families freely; restrict usage to the defined roles for Gt Alpina Condensed, Barlow Condensed, and Atlas Typewriter to maintain typographic consistency.

## Imagery

The site utilizes a blend of stylized, vibrant 2D illustrations and occasionally 3D renders. Visuals are typically contained within sections, often showing futuristic landscapes, vehicles, and abstract celestial bodies, frequently featuring a recurring bull-like character. Illustrations have a digital, almost comic-book feel, often incorporating strong outlines and a glowing effect, primarily in electric mint and cool tones, contrasting starkly with dark backgrounds in the hero sections. The role of imagery is primarily decorative atmosphere and metaphorical storytelling, rather than direct product showcase, adding to the 'cosmic rave' brand identity. Images are not full-bleed; they are carefully placed within content zones.

## Layout

The page primarily uses a full-bleed structure with content contained within an implied `pageMaxWidth` of 1200px and centered. The hero section is full-viewport, featuring a dark background with a monumental, centered headline and a primary CTA. Section rhythm alternates between stark dark backgrounds and clean white backgrounds, often defined by bold, full-width headers or atmospheric illustrations. Content is typically arranged in centered stacks for headlines and CTAs, transitioning into responsive grids (like 3-column investor logos) or text-heavy blocks with ample vertical spacing (24px section gap). Navigation is a fixed top bar on a dark background, minimal but functional.

## Agent Prompt Guide

Quick Color Reference: 
text: #000000
background: #ffffff
border: #000000
accent: #a1fea0
primary action: #a1fea0 (filled action)

Example Component Prompts:
1. Create a hero section: Midnight Ink (#000000) background. Headline 'SOLANA ON ETHEREUM' using Gt Alpina Condensed 562px weight 100, letter-spacing -0.06em, Canvas White (#ffffff) text, centered. Below, a Mint Pill Button: Electric Mint (#a1fea0) background, Midnight Ink (#000000) text (Barlow Condensed 400), 100px border-radius, 10px vertical and 18px horizontal padding.
2. Create a Primary Action Button: #a1fea0 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a feature section with investor logos: Canvas White (#ffffff) background. Headline 'BACKED BY GREAT INVESTORS' using Gt Alpina Condensed 61px weight 200, Midnight Ink (#000000) text. Below, a 3-column grid of Outline Investor Cards: transparent background, 1px Midnight Ink (#000000) border, 0px radius, with Midnight Ink (#000000) Atlas Typewriter 400 text centered within each card, e.g., 'Apollo'.

## Similar Brands

- **Solana** — Similar high-contrast, modern UI with bold typography and a developer/blockchain focus, often using saturated accent colors.
- **Optimism** — Shares a vibrant, often single-color accent approach contrasting against a dark or light minimalist UI, common in the crypto L2/blockchain space.
- **Arbitrum** — Similar bold, condensed headings and a technical, somewhat futuristic aesthetic with an emphasis on performance and transparency.
- **Neon EVM** — Visual identity uses a strong, singular neon accent color against dark themes, with striking typography and clean layouts for a technical product.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-electric-mint: #a1fea0;
  --color-muted-ash: #888680;
  --color-pale-stone: #dfddd6;
  --color-graphite: #302f2c;

  /* Typography — Font Families */
  --font-gt-alpina-condensed: 'Gt Alpina Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-barlow-condensed: 'Barlow Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atlas-typewriter: 'Atlas Typewriter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-math: 'math', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 0.02px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.6;
  --tracking-body-sm: 0.02px;
  --text-body: 18px;
  --leading-body: 1.56;
  --tracking-body: 0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.005px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: 0.013px;
  --text-heading: 44px;
  --leading-heading: 1.19;
  --tracking-heading: 0.01px;
  --text-heading-lg: 61px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.01px;
  --text-display: 562px;
  --leading-display: 0.8;
  --tracking-display: -0.06px;

  /* Typography — Weights */
  --font-weight-thin: 100;
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-3xl: 25px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-other: 25px;
  --radius-buttons: 100px;
  --radius-navitems: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-electric-mint: #a1fea0;
  --color-muted-ash: #888680;
  --color-pale-stone: #dfddd6;
  --color-graphite: #302f2c;

  /* Typography */
  --font-gt-alpina-condensed: 'Gt Alpina Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-barlow-condensed: 'Barlow Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-atlas-typewriter: 'Atlas Typewriter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-math: 'math', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 0.02px;
  --text-body-sm: 16px;
  --leading-body-sm: 1.6;
  --tracking-body-sm: 0.02px;
  --text-body: 18px;
  --leading-body: 1.56;
  --tracking-body: 0.02px;
  --text-subheading: 24px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.005px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: 0.013px;
  --text-heading: 44px;
  --leading-heading: 1.19;
  --tracking-heading: 0.01px;
  --text-heading-lg: 61px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.01px;
  --text-display: 562px;
  --leading-display: 0.8;
  --tracking-display: -0.06px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-120: 120px;
  --spacing-140: 140px;

  /* Border Radius */
  --radius-3xl: 25px;
  --radius-full: 100px;
}
```
