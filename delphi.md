# Delphi — Style Reference
> Cognac-Stained Parchment – A sense of aged wisdom and quiet authority, inviting deep contemplation.

**Theme:** light

This design system evokes a sense of thoughtful, quiet expertise, like a leather-bound journal filled with well-considered thoughts. The dominant use of an off-white, almost beige background (#fdf6ee) coupled with a nuanced palette of warm grays and subtle browns creates an inviting, scholarly atmosphere. The signature element is the `Martina Plantijn Light` typeface at whisper-weights, which gives a sophisticated, almost intimate feel, contrasting with the geometric precision of accompanying sans-serifs.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Parchment White | `#fdf6ee` | `--color-parchment-white` | Primary page and card backgrounds, lending a warm, analog feel to the digital interface. |
| Deep Cognac | `#2b180a` | `--color-deep-cognac` | Primary text color for body copy, headings, and key UI elements, offering strong contrast against the warm backgrounds. |
| Muted Stone | `#94877c` | `--color-muted-stone` | Secondary text, subtle borders, and placeholder text, providing visual hierarchy without harshness. |
| Pressed Cacao | `#7f6e60` | `--color-pressed-cacao` | Tertiary text and subtle accents, deepening the warm neutral palette. |
| Burnt Umber | `#3e2407` | `--color-burnt-umber` | Interactive elements like primary buttons and emphasized text, acting as a warm, grounded accent. |
| Warm Ash | `#a99d93` | `--color-warm-ash` | Subtle borders and muted instructional text. |
| Cloud Fog | `#f0e6dc` | `--color-cloud-fog` | Hover states and secondary button backgrounds, a slightly darker shade of the primary background for subtle interaction feedback. |
| Fire Opal | `#f65726` | `--color-fire-opal` | Used sparingly for dynamic highlights or notification states, providing a vibrant pop. |
| Sunset Orange | `#ff5c00` | `--color-sunset-orange` | Occasional accent for specific headline emphasis, drawing attention without being overwhelming. |
| White | `#ffffff` | `--color-white` | Text on dark backgrounds, or pure white elements for contrast against Parchment White. |
| Dark Charcoal | `#21201c` | `--color-dark-charcoal` | Deep, almost black text for strong contrast where needed. |

## Tokens — Typography

### Martina Plantijn Light — Primary display and headline font for all large text, creating an inviting, antique, and intellectual tone. The liberal use of negative letter-spacing for large sizes is a signature choice, drawing characters closer for a cohesive, refined look. · `--font-martina-plantijn-light`
- **Substitute:** Source Serif Pro
- **Weights:** 300, 400, 700
- **Sizes:** 10px, 12px, 14px, 15px, 20px, 24px, 40px, 56px, 64px
- **Line height:** 1.00, 1.20, 1.22, 1.32, 1.34
- **Letter spacing:** -0.03em at 64px, -0.022em at 56px, -0.02em at 40px, -0.013em at 24px, -0.012em at 20px, normal at 15px and below
- **Role:** Primary display and headline font for all large text, creating an inviting, antique, and intellectual tone. The liberal use of negative letter-spacing for large sizes is a signature choice, drawing characters closer for a cohesive, refined look.

### Inter — Dominant sans-serif for body text, navigation items, and descriptions, providing contemporary readability against the more expressive display font. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 10px, 13px, 14px, 15px, 17px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** -0.01em
- **Role:** Dominant sans-serif for body text, navigation items, and descriptions, providing contemporary readability against the more expressive display font.

### sans-serif — Fallback and utilitarian text where robust readability is paramount, such as system messages or very small captions. · `--font-sans-serif`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback and utilitarian text where robust readability is paramount, such as system messages or very small captions.

### Roboto Mono — Monospaced font used for data, code snippets, or any content requiring exact character alignment. · `--font-roboto-mono`
- **Substitute:** Roboto Mono
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** Monospaced font used for data, code snippets, or any content requiring exact character alignment.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | -0.01px | `--text-caption` |
| body | 15px | 1.4 | -0.01px | `--text-body` |
| subheading | 20px | 1.2 | -0.48px | `--text-subheading` |
| heading-sm | 24px | 1.22 | -0.48px | `--text-heading-sm` |
| heading | 40px | 1.22 | -0.8px | `--text-heading` |
| heading-lg | 56px | 1.2 | -1.23px | `--text-heading-lg` |
| display | 64px | 1.34 | -1.92px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** compact

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| small | 4px |
| buttons | 12px |
| default | 12px |
| testimonials | 70px |

### Layout

- **Section gap:** 75px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Button (Filled)
**Role:** Call to action.

Background: Burnt Umber (#3e2407), Text: White (#ffffff), Radius: 12px, Padding: 12px 16px. Font: Inter 500, 15px. This is the main interactive element, signifying a primary action.

### Secondary Button (Outlined)
**Role:** Secondary action or ghost button.

Background: Parchment White (#fdf6ee), Text: Deep Cognac (#2b180a), Border: 1px Muted Stone (#94877c), Radius: 12px, Padding: 12px 16px. Font: Inter 400, 15px. Provides a less emphasized action, often paired with the primary button.

### Tertiary Button
**Role:** Subtle, less emphasized actions, often within navigation.

Background: Cloud Fog (#f0e6dc), Text: Deep Cognac (#2b180a), Radius: 12px, Padding: 12px 16px. Font: Inter 400, 15px. Features a slightly darker background than the page for minimal differentiation.

### Auth Button
**Role:** Sign-in or Get-started actions in the header.

Background: White (#ffffff), Text: Deep Cognac (#2b180a), Radius: 12px, Padding: 12px 16px. Font: Inter 400, 15px. Used specifically for authentication flows, standing out against the header background.

### Testimonial Card
**Role:** Displaying expert quotes or profiles.

Background: Parchment White (#fdf6ee), Text: Deep Cognac (#2b180a), Radius: 16px-20px (dynamic, with an inner radius for the avatar at 70px), Padding: 20px. Features a soft shadow implying elevation.

### Input Field
**Role:** User data entry.

Background: Parchment White (#fdf6ee), Border: 1px Muted Stone (#94877c), Radius: 12px, Padding: 12px 16px. Placeholder text in Muted Stone, font Inter 400, 15px. Focus ring uses a subtle outline.

### Header Navigation Item
**Role:** Primary site navigation.

Text: Muted Stone (#94877c) for inactive, Deep Cognac (#2b180a) for active/hover. Font: Inter 400, 15px. Padding: 12px. No explicit background, integrates with header.

### Feature Card
**Role:** Highlighting product features or benefits.

Background: Parchment White (#fdf6ee), Radius: 16px, Padding: 20px. Headline and body text use Deep Cognac and Muted Stone. Features an almost invisible shadow for subtle depth.

## Do's and Don'ts

### Do
- Use Martina Plantijn Light at weight 300 for all content headings larger than 24px, applying appropriate negative letter-spacing.
- Maintain #fdf6ee as the primary background color for all main page content and interactive cards.
- Apply a default border-radius of 12px to all interactive elements and contained content blocks like cards.
- Employ the Deep Cognac (#2b180a) as the default text color for primary content and navigation.
- Utilize Inter at 15px with line height 1.4 for most body copy, ensuring an open and readable text block.
- Emphasize primary calls-to-action using a filled button with Burnt Umber (#3e2407) background and white text.
- Ensure consistent spacing elements are multiples of 4px, especially for padding within components and between text blocks.

### Don't
- Do not use highly saturated colors for backgrounds or large text areas; reserve them for small, impactful accents like #f65726 or #ff5c00.
- Avoid harsh shadows; prefer subtle, barely-there elevations to maintain the soft, warm aesthetic.
- Do not use pure black (#000000) for text on #fdf6ee backgrounds unless for specific, high-contrast, legal text. Prefer Deep Cognac (#2b180a) or Dark Charcoal (#21201c).
- Do not break the established type scale; Martina Plantijn Light scales with specific letter-spacing adjustments at larger sizes.
- Do not introduce strong, geometric shapes where rounded corners (12px or 70px) are the established pattern.
- Avoid busy or distracting imagery; prefer tightly cropped portraits or clean UI mockups.
- Do not use `sans-serif` (system font) for any primary content; it is reserved for inaccessible or fallback instances.

## Elevation

The design embraces a philosophy of subtle, organic elevation, shying away from strong, hard-edged shadows. Instead, elevation is primarily conveyed through slight background color variations (e.g., #fdf6ee for cards on potentially #f0e6dc backgrounds) and very soft, diffuse box-shadows. These shadows are barely perceptible, creating a gentle lift rather than a stark separation, maintaining the warm and inviting aesthetic without sharp contrasts.

## Imagery

The visual language is characterized by minimal photography, primarily featuring tightly cropped, professional headshots of individuals within testimonial-like thought bubbles. These headshots are typically well-lit, direct, and slightly desaturated, presenting a human but professional face to the AI's 'mind'. The images are often contained within rounded rectangular cards, sometimes layered or scattered, suggesting a constellation of expert voices. Product UI screenshots are presented cleanly within simulated device frames or as isolated, focused elements, detailing functionality without overwhelming the layout. There's an absence of abstract graphics, 3D renders, or decorative illustrations, reinforcing a serious, content-focused approach. The overall density is text-dominant, with imagery serving as supportive, grounded evidence.

## Layout

The page primarily employs a max-width contained model (around 1200px) centered on a 'Parchment White' background, creating a spacious and breathable feel. The hero section features a centered, inviting headline ('Digitize Your Mind') above a descriptive subtext and two call-to-action buttons, framed by dynamically floating, blurred testimonial-like cards, creating a sense of activity and social proof. Sections below alternate between a slightly darker off-white background (#f0e6dc) and the primary #fdf6ee, establishing a subtle rhythm. Content arrangement frequently uses two-column layouts, often pairing text with supporting UI snippets or further testimonial cards. There are instances of tightly clustered card grids for features, maintaining generous padding. The navigation is a classic sticky top bar, providing persistent access to key sections. The overall density is balanced, allowing ample whitespace to highlight cognitive ease.

## Agent Prompt Guide

### Quick Color Reference
- Text: #2b180a
- Background: #fdf6ee
- Primary CTA: #3e2407
- Secondary CTA: #f0e6dc
- Subtle Border: #94877c

### 3-5 Example Component Prompts
1. Create a hero section: background #fdf6ee. Centered Headline 'Digitize Your Mind' in Martina Plantijn Light 64px weight 300, #2b180a, letter-spacing -1.92px. Subtext 'Turn your knowledge into an interactive profile...' in Inter 17px weight 400, #94877c. Primary button 'Create Your Digital Mind' with background #3e2407, white text, 12px radius, 12px 16px padding. Secondary button 'See it in action' with background #f0e6dc, #2b180a text, 12px radius, 12px 16px padding.
2. Design a feature card: background #fdf6ee, radius 16px, 20px padding. Headline 'Never Repeat Yourself Again' in Martina Plantijn Light 24px weight 400, #2b180a, letter-spacing -0.48px. Body text 'You have expertise people want...' in Inter 15px weight 400, #2b180a.
3. Implement a header navigation bar: background #fdf6ee. Left-aligned logo. Navigation items 'Industries', 'Resources' at Inter 15px weight 400, #94877c, 12px padding. Right-aligned button 'Get Started' with background #ffffff, #2b180a text, 12px radius, 12px 16px padding.

## Similar Brands

- **Typeform** — Similar use of soft, warm background neutrals and rounded, approachable UI elements, suggesting a friendly user experience.
- **Readwise Reader** — Employs an editorial, content-first approach with a focus on comfortable typography and a calm, inviting reading environment.
- **Notion** — Similar structure of contained content blocks and a generally light, minimalist aesthetic, though Notion is cooler-toned.
- **Substack** — Features a strong emphasis on editorial-style typography and a clear, uncluttered presentation of text-heavy content, often with warm neutral backgrounds.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-parchment-white: #fdf6ee;
  --color-deep-cognac: #2b180a;
  --color-muted-stone: #94877c;
  --color-pressed-cacao: #7f6e60;
  --color-burnt-umber: #3e2407;
  --color-warm-ash: #a99d93;
  --color-cloud-fog: #f0e6dc;
  --color-fire-opal: #f65726;
  --color-sunset-orange: #ff5c00;
  --color-white: #ffffff;
  --color-dark-charcoal: #21201c;

  /* Typography — Font Families */
  --font-martina-plantijn-light: 'Martina Plantijn Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.01px;
  --text-body: 15px;
  --leading-body: 1.4;
  --tracking-body: -0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.22;
  --tracking-heading-sm: -0.48px;
  --text-heading: 40px;
  --leading-heading: 1.22;
  --tracking-heading: -0.8px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.23px;
  --text-display: 64px;
  --leading-display: 1.34;
  --tracking-display: -1.92px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 75px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8.21px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 70px;
  --radius-full-2: 582px;

  /* Named Radii */
  --radius-small: 4px;
  --radius-buttons: 12px;
  --radius-default: 12px;
  --radius-testimonials: 70px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-parchment-white: #fdf6ee;
  --color-deep-cognac: #2b180a;
  --color-muted-stone: #94877c;
  --color-pressed-cacao: #7f6e60;
  --color-burnt-umber: #3e2407;
  --color-warm-ash: #a99d93;
  --color-cloud-fog: #f0e6dc;
  --color-fire-opal: #f65726;
  --color-sunset-orange: #ff5c00;
  --color-white: #ffffff;
  --color-dark-charcoal: #21201c;

  /* Typography */
  --font-martina-plantijn-light: 'Martina Plantijn Light', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-mono: 'Roboto Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.01px;
  --text-body: 15px;
  --leading-body: 1.4;
  --tracking-body: -0.01px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.48px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.22;
  --tracking-heading-sm: -0.48px;
  --text-heading: 40px;
  --leading-heading: 1.22;
  --tracking-heading: -0.8px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -1.23px;
  --text-display: 64px;
  --leading-display: 1.34;
  --tracking-display: -1.92px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8.21px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 70px;
  --radius-full-2: 582px;
}
```
