# Superintelligence for work — Style Reference
> AI Blueprint on Polished Glass

**Theme:** light

Sana embodies a high-contrast, polished AI platform aesthetic: a largely white canvas punctuated by deep dark text and occasional vibrant accents. Components are lightweight and confident, favoring rounded shapes and minimal elevation. Typography is distinctive with a custom sans-serif that uses precise letter-spacing for a sophisticated, modern feel. Color appears primarily as functional cues, highlighting calls to action or distinguishing interactive elements within an otherwise achromatic UI.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card backgrounds, button backgrounds for ghost/outlined states, text on dark backgrounds |
| Ghost Fog | `#efefed` | `--color-ghost-fog` | Subtle background for UI sections and elevated cards, providing gentle visual separation from the main canvas |
| Midnight Ink | `#090909` | `--color-midnight-ink` | Primary text, headings, most iconography, borders, and input text – a core color for content and structure |
| Abyssal Black | `#000000` | `--color-abyssal-black` | Headings on light backgrounds, filled button backgrounds, and strong accent borders for interactive elements |
| Sterling Gray | `#d9d9d9` | `--color-sterling-gray` | Subtle borders, dividers, and background elements, especially in footers or less prominent UI areas |
| Action Blue | `#0057f3` | `--color-action-blue` | Primary call-to-action buttons – a vivid, energetic blue that draws immediate attention |
| Warning Orange | `#ff5102` | `--color-warning-orange` | Orange action color for filled buttons, selected navigation states, and focused conversion moments |

## Tokens — Typography

### Sana Sans — All textual elements on the site, from large display headings to fine print. The custom Sana Sans ensures a distinct brand voice through precise tracking and varied weights, establishing authority without formality. The tight letter-spacing on larger sizes creates a sense of precision and modernism. · `--font-sana-sans`
- **Substitute:** Inter
- **Weights:** 400, 450, 500
- **Sizes:** 14px, 15px, 16px, 32px, 40px, 48px, 83px
- **Line height:** 0.95, 1.00, 1.10, 1.23, 1.40, 1.49, 1.60
- **Letter spacing:** -0.0300em (at 83px), -0.0200em (at 48px), -0.0110em (at 40px), -0.0100em (at 32px), -0.0040em (at 16px)
- **OpenType features:** `"kern"`
- **Role:** All textual elements on the site, from large display headings to fine print. The custom Sana Sans ensures a distinct brand voice through precise tracking and varied weights, establishing authority without formality. The tight letter-spacing on larger sizes creates a sense of precision and modernism.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.49 | -0.056px | `--text-caption` |
| body | 16px | 1.4 | -0.064px | `--text-body` |
| subheading | 32px | 1.1 | -0.32px | `--text-subheading` |
| heading-sm | 40px | 1.1 | -0.44px | `--text-heading-sm` |
| heading | 48px | 1.1 | -0.96px | `--text-heading` |
| display | 83px | 0.95 | -2.49px | `--text-display` |

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
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| buttons | 32px |
| navigation | 6px |
| largeFeatures | 24px |
| specialButtons | 36px |

### Layout

- **Section gap:** 64px
- **Card padding:** 40px
- **Element gap:** 16px

## Components

### Main Call to Action Button
**Role:** Interactive element

Filled button with 'Action Blue' (#0057f3) background, 'Canvas White' text, and a generous 32px border-radius, giving it a soft, approachable feel. Padding is 10px vertical and 16px horizontal to ensure a comfortable tap target.

### Secondary Call to Action Button
**Role:** Interactive element

Filled button with 'Warning Orange' (#ff5102) background, 'Canvas White' text, and 32px border-radius. Padding is 10px vertical and 16px horizontal.

### Call to Action Button (Dark)
**Role:** Interactive element

Black filled button with 'Abyssal Black' (#000000) background, 'Canvas White' text, and 32px border-radius for high contrast. Padding is 10px vertical and 16px horizontal.

### Ghost Button (Book an Intro)
**Role:** Interactive element

Black button with 'Abyssal Black' (#000000) background and 'Canvas White' text, but with a specific 36px border-radius and minimal vertical padding (4px top, 0px bottom), suggesting a smaller, more integrated control.

### Outlined Button (Watch video)
**Role:** Interactive element

Button with 'Canvas White' (#ffffff) background, 'Abyssal Black' (#000000) text and border, maintaining a 32px border-radius and 10px vertical, 16px horizontal padding. Integrates into surfaces for less prominence than filled buttons.

### Feature Card (Subtle BG)
**Role:** Information display

Card with 'Ghost Fog' (#efefed) background, 16px border-radius, and generous interior padding (64px top, 43px horizontal) for structured content presentation. No explicit shadow, relying on background color for elevation.

### Feature Card (Large Radius)
**Role:** Information display

Card with no background, 24px border-radius, and internal padding of 40px on all sides, used for more prominent content blocks or to create internal grouping without a strong visual boundary.

### Navigation Link
**Role:** Interactive element

Text link using 'Midnight Ink' (#090909) with Sana Sans font. Features a subtle 6px border-radius for containing small interactive elements within navigation, and horizontal padding of 8px to 16px.

## Do's and Don'ts

### Do
- Prioritize 'Midnight Ink' (#090909) and 'Abyssal Black' (#000000) for all primary text and headings, ensuring high contrast against light backgrounds.
- Use 'Canvas White' (#ffffff) as the default page background and for ghost-style interactive elements.
- Apply 'Ghost Fog' (#efefed) for secondary section backgrounds or cards to create a subtle depth layer without shadows.
- Reserve 'Action Blue' (#0057f3) for the primary call-to-action buttons, maximizing urgency and visibility.
- Maintain a clear visual hierarchy with distinct font sizes and precise letter-spacing from the Sana Sans typography scale, especially for larger headings.
- Employ rounded corners consistently: 32px for most buttons and 16px for cards, giving elements a soft, approachable character.
- Utilize 16px as the primary value for horizontal and vertical spacing between related elements and for internal component padding to maintain comfortable density.

### Don't
- Avoid arbitrary color usage; limit chromatic colors strictly to 'Action Blue' (#0057f3) and 'Warning Orange' (#ff5102) for interactive elements.
- Do not introduce strong shadows or complex elevation schemes; the design relies on subtle background color shifts for depth.
- Do not deviate from the defined Sana Sans font family, weights, and letter-spacing values to preserve the brand's typographic precision.
- Do not use sharp corners; maintain the rounded aesthetic across all interactive and content-containing components.
- Avoid overly dense layouts; ensure ample 'Ghost Fog' (#efefed) or 'Canvas White' (#ffffff) space between content blocks and sections.
- Do not use dark backgrounds for large content areas; the system is designed for a light-themed interface with dark typography.
- Do not use generic system fonts; the custom Sana Sans is integral to the brand's visual identity.

## Imagery

The site uses a mix of realistic product screenshots and staged photography. Product visuals often feature a clean, bright aesthetic against light backgrounds, emphasizing the UI. Photography includes close-ups of people, often with a natural, unposed style that conveys approachability and authentic engagement, rather than highly stylized studio shots. Illustrations are minimal and typically brand-aligned, such as simplified vector icons or subtle graphic elements within UI. Imagery serves both to showcase the product's functionality and to foster a sense of human connection, with a density that allows generous white space for a premium feel.

## Layout

The page primarily uses a max-width contained layout, though the hero section can be full-bleed. The hero pattern prominently features a centered, bold headline over a clean background. Sections typically follow a consistent vertical rhythm with comfortable spacing, often alternating between a 'Canvas White' and 'Ghost Fog' background to delineate content blocks. Content arrangement favors a balanced, often centered, stacking of elements, occasionally incorporating two-column layouts for text-plus-image sections. There's a subtle use of a card-like grid for features, maintaining generous padding and rounded corners. Navigation is a simple, fixed top bar with minimal links.

## Agent Prompt Guide

### Quick Color Reference
text: #090909
background: #ffffff
border: #090909
accent: #ff5102
primary action: #000000 (filled action)

### 3-5 Example Component Prompts
1. Create a Hero Section: 'Canvas White' (#ffffff) background. Headline 'Superintelligence for work' using Sana Sans 83px, weight 400, 'Abyssal Black' (#000000), letter-spacing -2.49px, line-height 0.95. Subtext 'Give your teams the tools they need to thrive in an AI-first world.' using Sana Sans 16px, weight 400, 'Midnight Ink' (#090909), letter-spacing -0.064px, line-height 1.4. Center both vertically and horizontally.
2. Create a Primary Action Button: #000000 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create an Outlined Button: Text 'Watch video', 'Canvas White' (#ffffff) background, 'Abyssal Black' (#000000) text, 1px 'Abyssal Black' (#000000) border, Sana Sans 16px, weight 450, 32px border-radius, 10px vertical padding, 16px horizontal padding.
4. Create a Section Card: 'Ghost Fog' (#efefed) background, 16px border-radius, 64px top padding, 43px horizontal padding. Title 'Sana Learn' Sana Sans 40px, weight 400, 'Midnight Ink' (#090909), letter-spacing -0.44px, line-height 1.1.

## Similar Brands

- **Workday** — High-contrast typography, focus on structured content, and restrained use of color within an enterprise SaaS context.
- **Stripe** — Clean, spacious layouts, strong typography, and a balance of technical and human elements, with a sophisticated but understated aesthetic.
- **Linear** — Emphasis on precise typography and minimal UI, using subtle background shifts instead of heavy shadows for hierarchy.
- **Amie** — Sunlit productivity workspace feel with white canvas, flat product surfaces, and one vivid accent color for key actions.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghost-fog: #efefed;
  --color-midnight-ink: #090909;
  --color-abyssal-black: #000000;
  --color-sterling-gray: #d9d9d9;
  --color-action-blue: #0057f3;
  --color-warning-orange: #ff5102;

  /* Typography — Font Families */
  --font-sana-sans: 'Sana Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.49;
  --tracking-caption: -0.056px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.064px;
  --text-subheading: 32px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.32px;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.44px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-display: 83px;
  --leading-display: 0.95;
  --tracking-display: -2.49px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 40px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-buttons: 32px;
  --radius-navigation: 6px;
  --radius-largefeatures: 24px;
  --radius-specialbuttons: 36px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ghost-fog: #efefed;
  --color-midnight-ink: #090909;
  --color-abyssal-black: #000000;
  --color-sterling-gray: #d9d9d9;
  --color-action-blue: #0057f3;
  --color-warning-orange: #ff5102;

  /* Typography */
  --font-sana-sans: 'Sana Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.49;
  --tracking-caption: -0.056px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.064px;
  --text-subheading: 32px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.32px;
  --text-heading-sm: 40px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.44px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.96px;
  --text-display: 83px;
  --leading-display: 0.95;
  --tracking-display: -2.49px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 36px;
}
```
