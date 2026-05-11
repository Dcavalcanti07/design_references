# Stryds — Style Reference
> Neon rings in midnight

**Theme:** dark

Stryds embodies a dark, vibrant gamified aesthetic. The interface uses deep, near-black backgrounds contrasting with neon gradients and vivid accent colors. Typography is bold and assertive, prioritizing impact over traditional readability, often using large scale and tight tracking. Components are rounded and soft, emphasizing a playful yet high-tech feel, with a strategic use of color to highlight active states and primary actions.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#040126` | `--color-deep-space` | Text on bright surfaces, button borders for outlined actions, icon colors. Its deep violet tint adds subtle complexity to what would otherwise be pure black |
| Neon Green | `#a6ff00` | `--color-neon-green` | Primary action buttons, active indicators, and prominent highlight accents. This vivid green provides a sharp, energetic contrast against the dark background |
| Dark Matter | `#333333` | `--color-dark-matter` | Divider lines, subtle borders, secondary text, and muted icon fills. A foundational dark gray for content separation and hierarchy |
| Midnight Canvas | `#000000` | `--color-midnight-canvas` | Dominant background for the overall page, creating a deep, immersive dark mode experience |
| Graphite Border | `#3d3d3d` | `--color-graphite-border` | Card borders and subtle separating lines, slightly lighter than Dark Matter for softer definition |
| Muted Ash | `#6f6f6f` | `--color-muted-ash` | Tertiary text, subheadings, and supporting content. Provides subdued contrast, allowing primary information to stand out |
| Card Surface | `#171717` | `--color-card-surface` | Default background for cards and containers, subtly elevated from the main canvas |
| Bright Text | `#fdfdfd` | `--color-bright-text` | Primary text on dark backgrounds, ensuring high legibility for headings and key information |
| Component Dark | `#101010` | `--color-component-dark` | Background for certain buttons and interactive elements, providing a slightly lighter dark tone than the main canvas |

## Tokens — Typography

### Arial — Default text, links, and card descriptions. The system font choice implies directness and native integration. · `--font-arial`
- **Substitute:** Helvetica Neue
- **Weights:** 400, 500
- **Sizes:** 14px
- **Line height:** 1.43
- **Letter spacing:** -0.0340em
- **Role:** Default text, links, and card descriptions. The system font choice implies directness and native integration.

### Sf Pro Display — Headings and prominent display text. The wide range of sizes and tight letter spacing at larger scales creates a strong, impactful visual hierarchy, giving headlines a 'command center' feel. · `--font-sf-pro-display`
- **Substitute:** Inter
- **Weights:** 500, 600
- **Sizes:** 16px, 21px, 36px, 44px, 78px, 109px, 148px, 184px
- **Line height:** 0.95, 1.00, 1.10, 1.20, 1.25
- **Letter spacing:** -0.0340em, -0.0270em, -0.0260em, -0.0230em, -0.0120em, -0.0100em, -0.0070em, 0.0270em
- **Role:** Headings and prominent display text. The wide range of sizes and tight letter spacing at larger scales creates a strong, impactful visual hierarchy, giving headlines a 'command center' feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.43 | -0.48px | `--text-body` |
| heading-sm | 21px | 1.2 | -0.57px | `--text-heading-sm` |
| heading | 36px | 1.1 | -0.83px | `--text-heading` |
| heading-lg | 44px | 1 | -1.01px | `--text-heading-lg` |
| display | 78px | 1 | -1.33px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 80 | 80px | `--spacing-80` |
| 108 | 108px | `--spacing-108` |

### Border Radius

| Element | Value |
|---------|-------|
| misc | 100px |
| cards | 40px |
| buttons | 100px |

### Layout

- **Section gap:** 80px
- **Card padding:** 80px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Call to action button

Filled with Neon Green (#a6ff00) background, Deep Space (#040126) text. Features 100px border radius, 13px vertical padding, 20px horizontal padding, creating a distinct pill shape for immediate visibility.

### Ghost Icon Button
**Role:** Secondary action or branding button

Component Dark (#101010) background, Deep Space (#040126) text and border. Features 100px border radius, 16px vertical padding, 56px left padding (implying icon alignment), and 20px right padding. Used for branding or less prominent interactive elements.

### Elevated Card
**Role:** Content container for featured sections

Card Surface (#171717) background, 40px border radius. Uses 80px internal padding on all sides, providing generous breathing room for content. Bordered with Graphite Border (#3d3d3d).

### Transparent Content Card
**Role:** Subtle content grouping within larger sections

Transparent background, 40px border radius. Used for visually light content grouping without adding additional surface depth. Contains 0px padding, relying on content's own spacing.

## Do's and Don'ts

### Do
- Always use Deep Space (#040126) for neutral button outlines on dark backgrounds.
- Prioritize Neon Green (#a6ff00) for all primary calls to action, ensuring button background fills and critical highlights stand out.
- Apply a 100px border radius to all buttons and small interactive elements, creating a distinct pill-shaped aesthetic.
- Maintain a section gap of 80px between major content blocks to create a generous, comfortable density.
- Use Bright Text (#fdfdfd) for all primary headings and body text on dark backgrounds to ensure legibility.
- Ensure headings use a tight line height, typically 0.95 to 1.25, with negative letter spacing for a compact, impactful look.
- Backgrounds should predominantly use Midnight Canvas (#000000) or Card Surface (#171717) to maintain the dark theme.

### Don't
- Do not use highly saturated colors for large background areas; colors are reserved for accents and interactive elements.
- Avoid sharp corners; all significant UI elements like cards and buttons should embrace the generous 40px or 100px border radii.
- Do not use generic system fonts for display typography; Sf Pro Display (or a suitable substitute) is critical for brand impact.
- Refrain from excessive use of visual hierarchy with shadows; rely on color contrast and spacing for distinction.
- Do not break the dark theme with light backgrounds for content sections; maintain consistency with the neutral dark palette.
- Avoid standard letter spacing on headings; always apply the specified negative tracking for a unique type rhythm.

## Imagery

This site features abstract, energetic visuals dominated by vibrant, multi-colored rings that swirl and overlap. Imagery is primarily abstract and decorative, forming large background elements rather than product-specific showcases. The rings appear to be vector-based or graphically rendered, using a broad spectrum of vivid hues against deep dark backgrounds. There are some small profile picture-style circular image crops, suggesting social or user-generated content, but they are not the primary imagery focus. The visual language is image-heavy in decorative elements, but text-dominant for content presentation, relying on the background graphics for atmosphere while keeping the foreground UI clear.

## Layout

The page uses a full-bleed model, with content elements centered within a flexible width, rather than a strict `pageMaxWidth`. The hero section is full-bleed, featuring the brand name and tagline centered over the dynamic, colorful rings on a Midnight Canvas background. Sections appear to flow seamlessly, punctuated by the large background graphics, with a consistent vertical section gap of 80px. Content within sections tends to be centrally stacked or arranged in prominent, isolated blocks. Navigation is minimal, likely integrated into a subtle bottom bar as suggested by the ghost and primary action buttons at the base of the viewport.

## Agent Prompt Guide

Quick Color Reference:
text: #fdfdfd
background: #000000
border: #333333
accent: #a6ff00
primary action: #a6ff00 (filled action)

Example Component Prompts:
Create a hero section with 'Stryds' as the main title and 'The Social Health App' as a subtitle: Midnight Canvas (#000000) background. Main title in Sf Pro Display weight 600, 184px, #fdfdfd, letter-spacing -0.0100em. Subtitle in Sf Pro Display weight 500, 36px, #6f6f6f, letter-spacing -0.0260em. Both centered.

Create a Primary Action Button: #a6ff00 background, #333333 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create an elevated card with a headline 'Your Progress' and body text underneath: Card Surface (#171717) background, 40px border radius, 80px padding. Headline in Sf Pro Display weight 600, 44px, #fdfdfd, letter-spacing -0.0230em. Body text in Arial weight 400, 14px, #fdfdfd.

Create a ghost button labeled 'Stryds' with an implied icon offset: Component Dark (#101010) background, Deep Space (#040126) text in Arial weight 400, 14px, 100px border radius, 16px vertical padding, 56px left padding, 20px right padding.

## Similar Brands

- **Spotify** — Dark UI with vivid accent colors and prominent, rounded interactive elements.
- **Discord** — Deep dark aesthetic with playful, sometimes neon-like, color accents for active states and highlights.
- **Apple Fitness+** — Uses a dark backdrop with vibrant, color-coded rings or graphic elements to convey activity and progress.
- **Linear** — Focus on high information density within a dark theme, paired with strong, confident typography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #040126;
  --color-neon-green: #a6ff00;
  --color-dark-matter: #333333;
  --color-midnight-canvas: #000000;
  --color-graphite-border: #3d3d3d;
  --color-muted-ash: #6f6f6f;
  --color-card-surface: #171717;
  --color-bright-text: #fdfdfd;
  --color-component-dark: #101010;

  /* Typography — Font Families */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'Sf Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.48px;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.57px;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.83px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.01px;
  --text-display: 78px;
  --leading-display: 1;
  --tracking-display: -1.33px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-80: 80px;
  --spacing-108: 108px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 80px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-misc: 100px;
  --radius-cards: 40px;
  --radius-buttons: 100px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #040126;
  --color-neon-green: #a6ff00;
  --color-dark-matter: #333333;
  --color-midnight-canvas: #000000;
  --color-graphite-border: #3d3d3d;
  --color-muted-ash: #6f6f6f;
  --color-card-surface: #171717;
  --color-bright-text: #fdfdfd;
  --color-component-dark: #101010;

  /* Typography */
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-display: 'Sf Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.48px;
  --text-heading-sm: 21px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.57px;
  --text-heading: 36px;
  --leading-heading: 1.1;
  --tracking-heading: -0.83px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -1.01px;
  --text-display: 78px;
  --leading-display: 1;
  --tracking-display: -1.33px;

  /* Spacing */
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-80: 80px;
  --spacing-108: 108px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 100px;
}
```
