# Penpot — Style Reference
> Midnight Command Center.

**Theme:** dark

Penpot's design system uses a 'Dark Canvas, Teal Accent' approach. It grounds the user experience in a deep, dark violet background with text and interactive elements appearing in crisp white. A vibrant teal acts as the primary accent, drawing attention to calls-to-action and key information. Typography is precise and contained, complementing the overall density. Components are lightweight with subtly rounded corners, relying on color and text hierarchy rather than heavy borders or shadows for definition.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#151035` | `--color-midnight-ink` | Primary background for pages and cards, primary text color, link borders, list item borders |
| Activation Teal | `#1ccac7` | `--color-activation-teal` | Primary action button background, accent color for headings, decorative borders |
| Vivid Violet Accent | `#2f226c` | `--color-vivid-violet-accent` | Decorative border accent, subtle UI element outlining |
| Pure White | `#fafafa` | `--color-pure-white` | Primary text on dark backgrounds, active link text, high-contrast borders |
| Off-White | `#eeeeee` | `--color-off-white` | Secondary text on dark backgrounds, navigation item borders, subtle outlines |
| Subtle Gray | `#d3d3d3` | `--color-subtle-gray` | Ghost button borders, subtle inactive outlines |
| Black | `#000000` | `--color-black` | Highest contrast text, decorative icon borders |

## Tokens — Typography

### Work Sans — Primary typeface for all text content, including headings, body text, links, and buttons. Its wide range of weights and sizes contribute to clear hierarchy within the dark UI, with slight negative letter-spacing on larger sizes creating a contemporary feel. · `--font-work-sans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px, 48px, 52px, 72px
- **Line height:** 1.10, 1.20, 1.50
- **Letter spacing:** -0.0280em
- **Role:** Primary typeface for all text content, including headings, body text, links, and buttons. Its wide range of weights and sizes contribute to clear hierarchy within the dark UI, with slight negative letter-spacing on larger sizes creating a contemporary feel.

### Times — Times — detected in extracted data but not described by AI · `--font-times`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.2
- **Role:** Times — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.34px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.39px | `--text-body-sm` |
| body | 16px | 1.5 | -0.45px | `--text-body` |
| subheading | 18px | 1.5 | -0.5px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.67px | `--text-heading-sm` |
| heading | 48px | 1.1 | -1.34px | `--text-heading` |
| heading-lg | 52px | 1.1 | -1.46px | `--text-heading-lg` |
| display | 72px | 1.1 | -2.02px | `--text-display` |

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

### Border Radius

| Element | Value |
|---------|-------|
| tags | 50px |
| cards | 20px |
| inputs | 8px |
| buttons | 8px |

### Layout

- **Section gap:** 130px
- **Card padding:** 0px
- **Element gap:** 8px

## Components

### Ghost Button (Dark)
**Role:** Secondary action button with transparent background, used against dark backgrounds.

Background: rgba(0, 0, 0, 0), Text color: Midnight Ink (#151035), Border: 1px solid Pure White (#fafafa), Border radius: 10px, Padding: 12px vertical, 24px horizontal. Should only be used against light backgrounds as text becomes invisible on dark.

### Ghost Button (Light)
**Role:** Secondary action button with transparent background, used against light backgrounds.

Background: rgba(255, 255, 255, 0), Text color: Midnight Ink (#151035), Border: 1px solid Subtle Gray (#d3d3d3), Border radius: 8px, Padding: 12px vertical, 20px horizontal.

### Primary Action Button
**Role:** Main call-to-action button.

Background: Activation Teal (#1ccac7), Text color: Midnight Ink (#151035), Border: 1px solid Pure White (#fafafa), Border radius: 8px, Padding: 12px vertical, 20px horizontal.

### Neutral Button
**Role:** Default interactive button for general actions.

Background: #f5f8fb, Text color: Midnight Ink (#151035), Border: 1px solid Pure White (#fafafa), Border radius: 8px, Padding: 12px vertical, 20px horizontal.

### Product Display Card
**Role:** Container for product showcases or feature descriptions.

Background: Midnight Ink (#151035), Border radius: 20px, No padding or shadow at the card level; content provides its own spacing.

### Navigation Link
**Role:** Interactive navigation element with border interaction.

Text Color: Pure White (#fafafa), Hover/Active Border Bottom: 1px solid Off-White (#eeeeee), Padding: 8px vertical, 8-24px horizontal (flexible).

## Do's and Don'ts

### Do
- Always use Midnight Ink (#151035) for page and card backgrounds to maintain the dark canvas theme.
- Highlight primary actions with Activation Teal (#1ccac7) as the background color for filled buttons.
- Apply a border-radius of 8px to all buttons and input fields for consistent soft corners.
- Utilize Work Sans with a negative letter-spacing of -0.0280em for all typography to achieve the intended compact, crisp look.
- Ensure ample vertical spacing between sections, with a minimum `sectionGap` of 130px to prevent visual clutter.
- Use Pure White (#fafafa) for primary text on dark backgrounds to ensure high readability and contrast.
- Define interactive elements such as links and ghost buttons with subtle borders rather than solid backgrounds, using Off-White (#eeeeee) or Subtle Gray (#d3d3d3) for outlines.

### Don't
- Avoid using light backgrounds for primary content areas; the system is built on a dark canvas foundation.
- Do not introduce strong shadows or elevation effects; components rely on color contrast and subtle borders for visual hierarchy, not depth.
- Do not deviate from the Work Sans typeface or modify its defined letter-spacing presets, especially for larger headings.
- Avoid using bright, saturated colors other than Activation Teal (#1ccac7) for primary UI elements; reserve other chromatic colors for highly specific, decorative accents.
- Do not use generic border radii; adhere strictly to 8px for buttons/inputs and 20px for cards.
- Do not use excessive padding within cards; the default is 0px, allowing internal content to dictate its own structure and spacing.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Midnight | `#151035` | Primary page background, base layer. |
| 1 | Card Surface | `#151035` | Background for product display cards and grouped content sections, matching the canvas for a flush look. |

## Imagery

This design system primarily uses product screenshots and abstract graphics. Product screenshots are typically full-bleed or large, contained within dark backgrounds, often showcasing UI elements with a light theme contrasting against the dark site. Illustrations are minimal, hinted at by icon usage, favoring clean, geometric forms but not prominently featured. Icons are outlined or subtly filled, with a light stroke weight, aligning with the Ghost Button aesthetic. Imagery serves to demonstrate product functionality and features, acting as explanatory content rather than decorative atmosphere. The visual density is balanced, allowing prominent imagery to stand out without overwhelming the text.

## Layout

The page model is a full-bleed dark canvas with content contained within a roughly 1000px maximum width, centered horizontally. The hero section is full-bleed, featuring a large, centered headline with a prominent teal accent. Sections below the hero primarily consist of alternating two-column layouts, often with text on one side and a product screenshot or visual on the other. Vertical spacing between sections is generous, around 130px, creating a comfortable density. Navigation is a sticky top bar with clearly defined interactive elements. There are no explicit grid systems, but content alignment appears to be a mix of left-aligned text blocks and visually balanced two-column content areas.

## Agent Prompt Guide

### Quick Color Reference
text: Pure White (#fafafa)
background: Midnight Ink (#151035)
border: Off-White (#eeeeee)
accent: Activation Teal (#1ccac7)
primary action: #1ccac7 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #1ccac7 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
3. Create a Ghost Button (Light): 'Self-host install' with transparent background rgba(255, 255, 255, 0), text color Midnight Ink (#151035), border 1px solid Subtle Gray (#d3d3d3), radius 8px, padding 12px vertical, 20px horizontal. Font Work Sans 16px, weight 400, letterSpacing -0.45px.
4. Create a Product Display Card: Background Midnight Ink (#151035), radius 20px. Inside, an image cropped to the card edges and a text label below it like 'UI Design' using Work Sans 24px, Pure White (#fafafa), letterSpacing -0.67px.

## Similar Brands

- **Figma** — Dark-mode UI, focus on collaboration, with a clean and functional aesthetic that prioritizes content.
- **Linear** — Minimalist dark theme, precise typography, and a deliberate use of accent colors to highlight interactive elements and status.
- **Vercel** — Developer-centric dark UI, strong emphasis on product visuals and clear, high-contrast text against dark backgrounds with contained layouts.
- **Spline** — Tool-like interface with a dark theme and prominent use of an accent color (often blue or purple) for interactive elements and features.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #151035;
  --color-activation-teal: #1ccac7;
  --color-vivid-violet-accent: #2f226c;
  --color-pure-white: #fafafa;
  --color-off-white: #eeeeee;
  --color-subtle-gray: #d3d3d3;
  --color-black: #000000;

  /* Typography — Font Families */
  --font-work-sans: 'Work Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.34px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.39px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.45px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.5px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.67px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -1.34px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.46px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -2.02px;

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
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Layout */
  --section-gap: 130px;
  --card-padding: 0px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 50px;
  --radius-full-2: 100px;

  /* Named Radii */
  --radius-tags: 50px;
  --radius-cards: 20px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-canvas-midnight: #151035;
  --surface-card-surface: #151035;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #151035;
  --color-activation-teal: #1ccac7;
  --color-vivid-violet-accent: #2f226c;
  --color-pure-white: #fafafa;
  --color-off-white: #eeeeee;
  --color-subtle-gray: #d3d3d3;
  --color-black: #000000;

  /* Typography */
  --font-work-sans: 'Work Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-times: 'Times', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.34px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.39px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.45px;
  --text-subheading: 18px;
  --leading-subheading: 1.5;
  --tracking-subheading: -0.5px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.67px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -1.34px;
  --text-heading-lg: 52px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.46px;
  --text-display: 72px;
  --leading-display: 1.1;
  --tracking-display: -2.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-2xl: 20px;
  --radius-full: 50px;
  --radius-full-2: 100px;
}
```
