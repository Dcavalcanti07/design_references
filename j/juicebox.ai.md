# Juicebox.ai — Style Reference
> Vivid Analyst Workspace

**Theme:** light

Juicebox.ai employs a 'Vivid Analyst' aesthetic, blending a clean, technical interface with bursts of energetic purple. Typography is precise and utilitarian, prioritizing readability and information density. Surfaces are predominantly light with subtle elevation, creating a sense of clarity while the brand's signature purple provides functional highlights and a distinct visual identity, especially in larger background areas and interactive elements. The overall impression is one of focused, high-performance tooling.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud Canvas | `#f8f6f8` | `--color-cloud-canvas` | Page backgrounds, large content sections |
| Paper White | `#ffffff` | `--color-paper-white` | Card surfaces, input fields, prominent content blocks, primary button background |
| Ink | `#000000` | `--color-ink` | Primary text, critical body copy, button text on light backgrounds |
| Deep Plum | `#1d161d` | `--color-deep-plum` | Headlines, secondary text for high contrast |
| Graphite | `#574e57` | `--color-graphite` | Body text, input placeholder text, secondary contrast text |
| Border Fog | `#d9d9d9` | `--color-border-fog` | Hairline separators, subtle borders, inactive element outlines |
| Dusty Gray | `#786c78` | `--color-dusty-gray` | Muted text, helper text, subtle accents |
| Obsidian | `#2a232a` | `--color-obsidian` | Primary filled button background, dark surface elements |
| Juicebox Purple | `#6a2f8d` | `--color-juicebox-purple` | Primary accent color for interactive elements, CTA buttons (filled and ghost), links, and brand iconography. Used expansively in hero sections to establish identity |
| Highlight Violet | `#da9efd` | `--color-highlight-violet` | Decorative stroke, subtle visual accents, high-energy highlights |
| Blueprint Blue | `#186bd8` | `--color-blueprint-blue` | Blue outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Success Green | `#2f8d6e` | `--color-success-green` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Aqua Teal | `#2f878d` | `--color-aqua-teal` | Teal outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Radiant Purple | `#b054e7` | `--color-radiant-purple` | Strong secondary accent, often in decorative or gradient contexts |
| Hero Gradient Purple | `conic-gradient(rgb(231, 222, 237) 0deg, rgb(173, 34, 255) 360deg)` | `--color-hero-gradient-purple` | Distinct background for hero sections and prominent visual areas, creating an energetic brand presence |
| Section Gradient Dark | `linear-gradient(rgb(58, 25, 77) 0%, rgb(38, 17, 50) 100%)` | `--color-section-gradient-dark` | Darker gradient background for content sections |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Roobert Medium — Primary branding and display headlines. Its substantial weight and tight tracking create a powerful, authoritative voice. · `--font-roobert-medium`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 28px, 40px, 48px, 64px, 72px
- **Line height:** 1.00, 1.13, 1.15, 1.25
- **Letter spacing:** -0.0400em, -0.0300em, -0.0200em
- **Role:** Primary branding and display headlines. Its substantial weight and tight tracking create a powerful, authoritative voice.

### Haas Grot Text Web — The core text font for body copy, links, and various UI elements. Its neutrality and optical clarity maintain a professional and highly readable interface. · `--font-haas-grot-text-web`
- **Substitute:** Inter
- **Weights:** 400, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.00, 1.08, 1.20, 1.25, 1.29, 1.33, 1.43, 1.56
- **Letter spacing:** -0.0200em, -0.0100em
- **Role:** The core text font for body copy, links, and various UI elements. Its neutrality and optical clarity maintain a professional and highly readable interface.

### Haas Grot Text Web — Used for specific UI elements or emphasized body text requiring slightly more visual weight. · `--font-haas-grot-text-web`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 16px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Used for specific UI elements or emphasized body text requiring slightly more visual weight.

### DM Mono — Monospaced font for code snippets, technical data, or whenever a fixed-width, precise display is required. Wider letter-spacing distinguishes it from body text. · `--font-dm-mono`
- **Substitute:** Roboto Mono
- **Weights:** 500
- **Sizes:** 13px, 14px, 15px
- **Line height:** 1.00, 1.14
- **Letter spacing:** 0.0200em, 0.0770em
- **Role:** Monospaced font for code snippets, technical data, or whenever a fixed-width, precise display is required. Wider letter-spacing distinguishes it from body text.

### Inter — Reserved for input fields, ensuring clear and legible user entry. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Reserved for input fields, ensuring clear and legible user entry.

### Neue Haas Grotesk Text — Neue Haas Grotesk Text — detected in extracted data but not described by AI · `--font-neue-haas-grotesk-text`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.43
- **Role:** Neue Haas Grotesk Text — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | -0.01px | `--text-caption` |
| body | 14px | 1.25 | -0.02px | `--text-body` |
| subheading | 18px | 1.29 | -0.02px | `--text-subheading` |
| heading | 28px | 1.15 | -0.04px | `--text-heading` |
| heading-lg | 40px | 1.13 | -0.03px | `--text-heading-lg` |
| display | 72px | 1 | -0.04px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 128 | 128px | `--spacing-128` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 6px |
| buttons | 4px |
| elements | 2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.5) 0px 0px 12px 0px inset` | `--shadow-md` |

### Layout

- **Section gap:** 48px
- **Card padding:** 14px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Interactive element for primary actions.

Background: Obsidian (#2a232a), Text: Paper White (#ffffff). Padding: 13px vertical, 14px horizontal. Border radius: 4px. Features a subtle inset shadow `rgba(0, 0, 0, 0.5) 0px 0px 12px 0px inset` on hover/active states.

### Secondary Ghost Button
**Role:** Interactive element for secondary actions, or when a less prominent call to action is needed.

Background: transparent, Text: Juicebox Purple (#6a2f8d). Padding: 14px vertical, 20px horizontal. No border radius. On hover/active, the text color darkens subtly. This presents actions clearly without high visual weight.

### Solid White Button
**Role:** Interactive element for alternative actions, provides strong contrast on dark backgrounds.

Background: Paper White (#ffffff), Text: Ink (#000000). Padding: 13px vertical, 14px horizontal. Border radius: 4px.

### Juicebox Purple Filled Button
**Role:** Primary branded action.

Background: Juicebox Purple (#6a2f8d), Text: Paper White (#ffffff). Padding: 13px vertical, 14px horizontal. Border radius: 4px.

### Product Feature Card
**Role:** Container for showcasing features or information blocks.

Background: Paper White (#ffffff). Border radius: 6px. No box shadow, relying on spacing for separation. Inner padding: 14px (cardPadding).

### Basic Input Field
**Role:** Standard input for user data.

Background: transparent. Text/placeholder color: Graphite (#574e57). Border: 1px solid Graphite (#574e57). No border radius, sharp corners for a technical aesthetic.

### Navigation Bar Link
**Role:** Primary navigation elements.

Text: Deep Plum (#1d161d), size 16px, weight 500 (Haas Grot Text Web 65 Medium). Underlined on hover.

### Tag / Badge (Small)
**Role:** Categorization or small status indicators.

Background: Cloud Canvas (#f8f6f8). Text: Juicebox Purple (#6a2f8d). Border radius: 2px. Padding: 4px horizontal. Font: Haas Grot Text Web, 12px, 400.

## Do's and Don'ts

### Do
- Prioritize Cloud Canvas (#f8f6f8) for primary page backgrounds to maintain a light, airy feel.
- Use Juicebox Purple (#6a2f8d) sparingly for primary calls to action, active states, and brand iconography—making every instance impactful.
- Apply Haas Grot Text Web for all body and UI text, ensuring high readability and a consistent typographic rhythm.
- Maintain a tight negative letter-spacing for large headlines (Roobert Medium) to convey authority and precision.
- Utilize Paper White (#ffffff) for card and component backgrounds, creating clear content separation against the canvas.
- Employ Border Fog (#d9d9d9) for subtle dividers and borders, keeping visual noise to a minimum.
- Use 4px border radius for interactive elements (buttons) and 6px for content containers (cards) to subtly differentiate their function and hierarchy.

### Don't
- Do not introduce new primary background colors; stick to Cloud Canvas (#f8f6f8) and Paper White (#ffffff) for surfaces.
- Avoid using highly saturated colors for large text blocks; reserve them for accents and actionable elements.
- Do not deviate from the specified font families for headings and body text to preserve brand consistency.
- Refrain from adding arbitrary box shadows; elevation should be subtle or used for clear interaction feedback, not decoration.
- Avoid excessive spacing or overly decorative elements that would compromise the compact and information-dense nature of the UI.
- Do not use black text on Obsidian buttons; ensure contrast with Paper White (#ffffff) to maintain legibility.
- Do not round input field corners; maintain a sharp, technical aesthetic with 0px border-radius unless specified.

## Elevation

- **Primary Filled Button:** `rgba(0, 0, 0, 0.5) 0px 0px 12px 0px inset`

## Imagery

Imagery is minimal and primarily serves as a background for hero sections or as framed product screenshots within the UI. Abstract, textured backgrounds in brand purple establish mood without distracting from content. Product screenshots are typically high-fidelity and contained within UI elements, acting as direct visual explanations of functionality. Icons are functional, using either Ink (#000000) or Juicebox Purple (#6a2f8d), and appear to be outlined or filled with a moderate stroke weight. The overall density is text-dominant, with imagery serving as supportive illustration rather than primary content.

## Layout

The site uses a contained page model, with content centered within a max-width constraint, though no explicit maximum width was detected. The hero sections often feature full-width or full-viewport backgrounds with a combination of text and abstract purple graphics. Sections alternate with consistent vertical spacing (approx. 48px). Content primarily follows a centered stack pattern for headings and CTAs, often transitioning to text-left/image-right or multi-column card grids for features. Navigation is handled by a sticky top bar with a prominent 'Try for Free' button.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f8f6f8
border: #d9d9d9
accent: #6a2f8d
primary action: #6a2f8d (filled action)

Example Component Prompts:
Create a Primary Action Button: #6a2f8d background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a feature card: Paper White (#ffffff) background, 6px border-radius, 14px padding. Headline 'How it works' at 28px Roobert Medium weight 400, #1d161d. Body text 'Discover our features' at 14px Haas Grot Text Web weight 400, #574e57.

Create a navigation link: Text 'Features' at 16px Haas Grot Text Web weight 500, #1d161d. On hover, underline the text. No background or border.

Create a search input: Background transparent, 1px solid border #574e57, no border-radius. Placeholder text 'Search...' in Graphite (#574e57) using Inter font 14px weight 400. Include a Primary Filled Button variant with a send icon to the right, using Juicebox Purple (#6a2f8d) background, white text.

Create a ghost button: Text 'Book a Demo' at 14px Haas Grot Text Web weight 400, #6a2f8d. Background transparent, padding 14px vertical, 20px horizontal. No border or radius.

## Similar Brands

- **Rippling** — Clean, predominantly light interface with a focus on productivity and subtle use of a primary brand color for accents and interactive elements.
- **Linear** — Minimalist aesthetic focused on clarity and precision, with restrained use of color and sharp typographic hierarchy.
- **Vercel** — Technical, developer-focused aesthetic with strong typography, ample whitespace, and strategic use of a signature accent color.
- **Notion** — Information-dense UI with a very high contrast ratio for text, simple card-based layouts, and functional use of color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-canvas: #f8f6f8;
  --color-paper-white: #ffffff;
  --color-ink: #000000;
  --color-deep-plum: #1d161d;
  --color-graphite: #574e57;
  --color-border-fog: #d9d9d9;
  --color-dusty-gray: #786c78;
  --color-obsidian: #2a232a;
  --color-juicebox-purple: #6a2f8d;
  --color-highlight-violet: #da9efd;
  --color-blueprint-blue: #186bd8;
  --color-success-green: #2f8d6e;
  --color-aqua-teal: #2f878d;
  --color-radiant-purple: #b054e7;
  --color-hero-gradient-purple: #ad22ff;
  --gradient-hero-gradient-purple: conic-gradient(rgb(231, 222, 237) 0deg, rgb(173, 34, 255) 360deg);
  --color-section-gradient-dark: #3a194d;
  --gradient-section-gradient-dark: linear-gradient(rgb(58, 25, 77) 0%, rgb(38, 17, 50) 100%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert-medium: 'Roobert Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-web: 'Haas Grot Text Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.01px;
  --text-body: 14px;
  --leading-body: 1.25;
  --tracking-body: -0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.29;
  --tracking-subheading: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.15;
  --tracking-heading: -0.04px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.03px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.04px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 48px;
  --card-padding: 14px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;

  /* Named Radii */
  --radius-cards: 6px;
  --radius-buttons: 4px;
  --radius-elements: 2px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.5) 0px 0px 12px 0px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-canvas: #f8f6f8;
  --color-paper-white: #ffffff;
  --color-ink: #000000;
  --color-deep-plum: #1d161d;
  --color-graphite: #574e57;
  --color-border-fog: #d9d9d9;
  --color-dusty-gray: #786c78;
  --color-obsidian: #2a232a;
  --color-juicebox-purple: #6a2f8d;
  --color-highlight-violet: #da9efd;
  --color-blueprint-blue: #186bd8;
  --color-success-green: #2f8d6e;
  --color-aqua-teal: #2f878d;
  --color-radiant-purple: #b054e7;
  --color-hero-gradient-purple: #ad22ff;
  --color-section-gradient-dark: #3a194d;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roobert-medium: 'Roobert Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-haas-grot-text-web: 'Haas Grot Text Web', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-mono: 'DM Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-neue-haas-grotesk-text: 'Neue Haas Grotesk Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.01px;
  --text-body: 14px;
  --leading-body: 1.25;
  --tracking-body: -0.02px;
  --text-subheading: 18px;
  --leading-subheading: 1.29;
  --tracking-subheading: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.15;
  --tracking-heading: -0.04px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.03px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.04px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-md: 6px;
  --radius-lg: 10px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.5) 0px 0px 12px 0px inset;
}
```
