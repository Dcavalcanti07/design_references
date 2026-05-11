# Lithic — Style Reference
> High-contrast developer portal.

**Theme:** light

Lithic uses a high-contrast dark mode surface treatment for its primary hero, transitioning to a bright, spacious, and subtly textured light canvas for content sections. Its visual identity relies on strong typography, a single vivid orange accent for calls to action, and distinct colored tints for feature cards. The system balances developer-focused clarity with a modern, approachable aesthetic through rounded corners and ample white space, making the experience feel direct yet refined.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Obsidian | `#000000` | `--color-obsidian` | Primary text, dark backgrounds, borders, most UI elements in dark sections |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds in light sections, inverted text on dark backgrounds, ghost button text, and card surfaces |
| Faint Bronze | `#f6f3ee` | `--color-faint-bronze` | Subtle card background for featured content blocks |
| Faint Amethyst | `#f6f1fe` | `--color-faint-amethyst` | Subtle card background, providing a cool tint for specific feature sections |
| Muted Ash | `#e5e5e5` | `--color-muted-ash` | Lightest grey for button backgrounds or light borders |
| Mid Grey | `#888888` | `--color-mid-grey` | Muted body text, link text, and subtle icon strokes |
| Warm Copper | `#ff6600` | `--color-warm-copper` | Primary action buttons, interactive elements, and highlight strokes — provides a vibrant focal point |
| Muted Bronze | `#aa8855` | `--color-muted-bronze` | Decorative icons, borders, and text accents, hinting at a financial/traditional connection |
| Emerald Green | `#00cc88` | `--color-emerald-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Dark Amethyst | `#5c2999` | `--color-dark-amethyst` | Decorative borders, icons, and background tints for specific UI areas |
| Dark Bronze | `#665233` | `--color-dark-bronze` | Decorative strokes and icon details, a darker variant of Muted Bronze |
| Cream Tint | `#ebfef6` | `--color-cream-tint` | Light background tint for specific card surfaces, providing a warm, almost off-white feel |
| Pale Gold | `#eec07a` | `--color-pale-gold` | Icon and decorative element accents, a lighter, more moderate yellow hue |

## Tokens — Typography

### ABC Monument Grotesk — Used for all text elements. The -0.02em letter-spacing at all sizes gives a consistent, compact yet readable feel, especially noticeable on headings. · `--font-abc-monument-grotesk`
- **Substitute:** Arial
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 20px, 24px, 36px, 64px
- **Line height:** 1.00, 1.20, 1.40, 1.50, 1.52, 1.71
- **Letter spacing:** -0.02
- **Role:** Used for all text elements. The -0.02em letter-spacing at all sizes gives a consistent, compact yet readable feel, especially noticeable on headings.

### ABC Monument Grotesk — Used for emphasized text, headlines, and navigation items. The medium weight provides emphasis without being overly bold, maintaining the refined aesthetic. · `--font-abc-monument-grotesk`
- **Substitute:** Arial
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 20px, 24px, 36px, 64px
- **Line height:** 1.00, 1.20, 1.40, 1.50, 1.52, 1.71
- **Letter spacing:** -0.02
- **Role:** Used for emphasized text, headlines, and navigation items. The medium weight provides emphasis without being overly bold, maintaining the refined aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.71 | -0.28px | `--text-caption` |
| body | 16px | 1.5 | -0.32px | `--text-body` |
| subheading | 20px | 1.4 | -0.4px | `--text-subheading` |
| heading | 24px | 1.2 | -0.48px | `--text-heading` |
| heading-lg | 36px | 1.2 | -0.72px | `--text-heading-lg` |
| display | 64px | 1 | -1.28px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| icons | 800px |
| images | 21.6px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.5) 0px 16px 32px 0px` | `--shadow-xl` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 8px 0px` | `--shadow-sm` |
| xl-2 | `rgba(0, 0, 0, 0.1) 0px 16px 32px 0px` | `--shadow-xl-2` |

### Layout

- **Section gap:** 24px
- **Card padding:** 40px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action.

Background: Warm Copper (#ff6600), Text: Canvas White (#ffffff), Border Radius: 8px, Padding: 10px vertical, 24px horizontal.

### Ghost Action Button
**Role:** Outlined button for secondary actions or navigation.

Background: Transparent (rgba(0,0,0,0)), Text: Obsidian (#000000), Border: 1px solid Obsidian (#000000), Border Radius: 0px, Padding: 24px vertical, 16px horizontal.

### Pill Ghost Button (Hero)
**Role:** Large, ghosted button used in hero sections.

Background: Transparent (rgba(255,255,255,0.1)), Text: Canvas White (#ffffff), Border Radius: 24px, Padding: 40px vertical, 38.4px horizontal.

### Neutral Tag Button
**Role:** Small, light grey button for tags or metadata.

Background: Muted Ash (#e5e5e5), Text: Obsidian (#000000), Border Radius: 8px, Padding: 8px vertical, 12px horizontal.

### Feature Card - Faint Bronze
**Role:** Card for showcasing features with a warm background tint.

Background: Faint Bronze (#f6f3ee), Border Radius: 24px, Padding: 40px. No shadow.

### Feature Card - Faint Amethyst
**Role:** Card for highlighting specific sections with a cool background tint.

Background: Faint Amethyst (#f6f1fe), Border Radius: 24px, Padding: 40px. No shadow.

### Hero Overlay Card
**Role:** Card with subtle background and elevated appearance, used in dark sections.

Background: Transparent (rgba(255,255,255,0.1)), Border Radius: 24px, Shadow: rgba(0, 0, 0, 0.5) 0px 16px 32px 0px, Padding: 40px vertical, 38.4px horizontal.

### Dark Content Card
**Role:** Card with solid dark background for content within dark sections.

Background: Obsidian (#000000), Border Radius: 24px, Padding: 32px. No shadow.

## Do's and Don'ts

### Do
- Prioritize Obsidian (#000000) for primary text on light backgrounds and Canvas White (#ffffff) for primary text on dark backgrounds to maintain high contrast.
- Use Warm Copper (#ff6600) exclusively for primary calls to action, ensuring it stands out against neutral palettes.
- Apply a 24px border radius to all cards and large components, and an 8px radius for buttons and smaller interactive elements to maintain a consistent soft edge.
- Maintain a consistent -0.02em letter-spacing for all text in 'ABC Monument Grotesk' to prevent text feeling loose in larger sizes.
- Employ a 40px padding for card interiors to ensure comfortable spacing around content.
- Use Faint Bronze (#f6f3ee) and Faint Amethyst (#f6f1fe) backgrounds on cards to gently differentiate content blocks without adding strong color.
- Ensure section gaps are at least 24px, often larger up to 40-50px for spacious content separation.

### Don't
- Do not use Warm Copper (#ff6600) for any purely decorative purpose; reserve it strictly for calls to action.
- Avoid arbitrary border radii; stick to 24px for cards/large components and 8px for buttons/small elements unless specifically defining an icon (800px).
- Do not introduce new color tints for card backgrounds; use the existing Faint Bronze, Faint Amethyst, and Cream Tint.
- Avoid using multiple font families; all text must use 'ABC Monument Grotesk' in its specified weights.
- Do not use generic gray shadows; use the defined rgba(0, 0, 0, 0.5) 0px 16px 32px 0px for elevated elements to maintain strong contrast.
- Avoid using highly saturated colors for large background areas; backgrounds should mostly remain in the neutral palette or subtle tints.
- Do not clutter cards; maintain the 40px internal padding and clear visual hierarchy.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Obsidian Base | `#000000` | Primary background for hero sections and dark content blocks, providing a high-contrast starting point. |
| 1 | Canvas White | `#ffffff` | Dominant background for most content sections, providing a clean, bright canvas. |
| 2 | Cream Tint Card | `#ebfef6` | Subtle, slightly warm background tint for certain information cards. |
| 3 | Faint Bronze Card | `#f6f3ee` | Mildly textured, warm card background for highlighting specific content areas. |
| 4 | Faint Amethyst Card | `#f6f1fe` | Cool-tinted card background for distinct feature blocks. |

## Elevation

- **Hero Overlay Card:** `rgba(0, 0, 0, 0.5) 0px 16px 32px 0px`
- **Button Shadow (Subtle):** `rgba(0, 0, 0, 0.1) 0px 4px 8px 0px`
- **Image Shadow (Prominent):** `rgba(0, 0, 0, 0.1) 0px 16px 32px 0px`

## Imagery

The site primarily uses abstract, geometric illustrations and product-focused graphics. Illustrations are monochromatic or duotone, often featuring faint lines, organic circular paths, and subtle gradient fills in muted shades of the brand's accent colors. Product imagery consists of tight crops of dark-colored cards with intricate texture, presented at an angle, and often integrated into flowing abstract line patterns. Iconography is primarily outlined, using a thin stroke weight, sometimes with a subtle color tint from the accent palette. Imagery serves a decorative and atmospheric role rather than explicit explanation, creating a sophisticated backdrop for the clear UI.

## Layout

The page primarily uses a max-width contained layout rather than full-bleed content. The hero section is full-bleed with a dark Obsidian background and centered headline, featuring a 'swirling card' visual. Subsequent content sections typically center within a main container, alternating between white and occasionally subtly tinted backgrounds. Layouts are generally spacious with clear vertical sections, often employing a text-left, image-right alternation or a multi-column card grid pattern. Navigation is a sticky top bar with minimal links and clear call-to-action buttons. Spacing between sections is generous and consistent, creating a breathable visual rhythm.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e5e5e5
accent: #5c2999
primary action: #ff6600 (filled action)

Example Component Prompts:
1. Create a Hero Section: Use Obsidian background. Headline 'Breakthrough Products' in ABC Monument Grotesk 64px weight 500, Canvas White text, letter-spacing -1.28px. Two Pill Ghost Buttons: 'Explore Sandbox' and 'Contact us', both with Background rgba(255,255,255,0.1), Canvas White text, 24px radius, 40px vertical padding, 38.4px horizontal padding.
2. Create a Feature Card: Use Faint Bronze (#f6f3ee) background, 24px radius, 40px internal padding. Headline 'Direct to Banks' in ABC Monument Grotesk 24px weight 400, Obsidian text, letter-spacing -0.48px. Body text 'Seamless integration' in ABC Monument Grotesk 16px weight 400, Obsidian text, letter-spacing -0.32px. Include a decorative icon using Muted Bronze (#aa8855).
3. Create a Primary CTA Button: 'Sign Up Now'. Use Warm Copper (#ff6600) background, Canvas White text, ABC Monument Grotesk 16px weight 500, 8px radius, 10px vertical padding, 24px horizontal padding.
4. Create a Ghost Nav Link: 'Platform'. Use transparent background, Obsidian text, ABC Monument Grotesk 16px weight 400, 0px radius, 24px vertical padding, 16px horizontal padding.

## Similar Brands

- **Stripe** — High-contrast dark mode hero, clear and spacious light content sections, strong sans-serif typography, and subtle accent colors for code/status.
- **Ramp** — Clean data-driven aesthetic, combination of dark and light sections, emphasis on card-like elements, and a focus on clarity through ample spacing.
- **Adyen** — Modern fintech feel, restrained color palette with strategic accents, strong typographic hierarchy, and visual abstraction of financial products.
- **Modern Treasury** — Developer-centric, clean UI, alternating light and dark backgrounds, and precise use of typography with tight letter-spacing.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-obsidian: #000000;
  --color-canvas-white: #ffffff;
  --color-faint-bronze: #f6f3ee;
  --color-faint-amethyst: #f6f1fe;
  --color-muted-ash: #e5e5e5;
  --color-mid-grey: #888888;
  --color-warm-copper: #ff6600;
  --color-muted-bronze: #aa8855;
  --color-emerald-green: #00cc88;
  --color-dark-amethyst: #5c2999;
  --color-dark-bronze: #665233;
  --color-cream-tint: #ebfef6;
  --color-pale-gold: #eec07a;

  /* Typography — Font Families */
  --font-abc-monument-grotesk: 'ABC Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.71;
  --tracking-caption: -0.28px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.72px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.28px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 40px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 21.6px;
  --radius-3xl: 24px;
  --radius-full: 800px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-icons: 800px;
  --radius-images: 21.6px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.5) 0px 16px 32px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 8px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.1) 0px 16px 32px 0px;

  /* Surfaces */
  --surface-obsidian-base: #000000;
  --surface-canvas-white: #ffffff;
  --surface-cream-tint-card: #ebfef6;
  --surface-faint-bronze-card: #f6f3ee;
  --surface-faint-amethyst-card: #f6f1fe;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-obsidian: #000000;
  --color-canvas-white: #ffffff;
  --color-faint-bronze: #f6f3ee;
  --color-faint-amethyst: #f6f1fe;
  --color-muted-ash: #e5e5e5;
  --color-mid-grey: #888888;
  --color-warm-copper: #ff6600;
  --color-muted-bronze: #aa8855;
  --color-emerald-green: #00cc88;
  --color-dark-amethyst: #5c2999;
  --color-dark-bronze: #665233;
  --color-cream-tint: #ebfef6;
  --color-pale-gold: #eec07a;

  /* Typography */
  --font-abc-monument-grotesk: 'ABC Monument Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.71;
  --tracking-caption: -0.28px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.4px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.48px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.72px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -1.28px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 21.6px;
  --radius-3xl: 24px;
  --radius-full: 800px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.5) 0px 16px 32px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 8px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.1) 0px 16px 32px 0px;
}
```
