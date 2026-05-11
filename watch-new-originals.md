# Watch new Originals — Style Reference
> Midnight Command Center: Dark, immersive interfaces punctuated by vivid interactive highlights.

**Theme:** dark

Disney+ maintains a 'midnight command center' aesthetic, designed for content consumption. It features a predominantly dark background with contrasting light typography to highlight content. Functional elements are often subtle until interaction, utilizing a vibrant blue for calls to action, drawing attention against the otherwise subdued palette. The visual system is defined by its strong reliance on dark surfaces, minimal borders, and a focus on content presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Midnight | `#040714` | `--color-deep-midnight` | Primary page background, core content surface. Provides an immersive, dark canvas for media |
| Cool Graphite | `#282a36` | `--color-cool-graphite` | Input field backgrounds, subtle borders, secondary surface elements. A slightly lighter dark gray for contrast |
| Sky Blue | `#33ddff` | `--color-sky-blue` | Primary call-to-action button backgrounds. A vibrant accent to guide user action |
| Electric Teal | `#02d6e8` | `--color-electric-teal` | Secondary call-to-action details, selected active states, descriptive text emphasizing value |
| Text Dark | `#02172a` | `--color-text-dark` | Text on very light backgrounds (e.g. within active buttons) |
| Muted Silver | `#e5e7eb` | `--color-muted-silver` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Light Gray | `#c0c0c0` | `--color-light-gray` | Secondary text, unselected icons, helper text for content metadata |
| Off-White | `#fafafa` | `--color-off-white` | Primary text, headlines, navigation labels. High-contrast text on dark backgrounds |
| Deep Space | `#0e0b14` | `--color-deep-space` | Footer background, elevated sections for visual separation |
| Ghost Gray | `#b7b8bd` | `--color-ghost-gray` | Placeholder text in input fields, less prominent body copy |
| Accent Gray | `#1e1f24` | `--color-accent-gray` | Subtle background for UI elements that need mild distinction from Deep Midnight |
| Button Dark Text | `#17171c` | `--color-button-dark-text` | Text color for primary buttons with vibrant backgrounds |
| Faint Border | `#6f717b` | `--color-faint-border` | Decorative borders on certain navigation elements |
| Canvas Blue Black | `#010104` | `--color-canvas-blue-black` | Navigation bar background. Provides a distinct and consistent top-level UI element |

## Tokens — Typography

### Inspire — Primary typeface for all text content, from body copy to headlines. Its consistent tracking provides a unified and readable experience across different scales. Weight 400 is used for general content, while 700 emphasizes critical information. · `--font-inspire`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 28px, 40px
- **Line height:** 1.20, 1.38, 1.40, 1.50, 1.83
- **Letter spacing:** 0.0250em
- **Role:** Primary typeface for all text content, from body copy to headlines. Its consistent tracking provides a unified and readable experience across different scales. Weight 400 is used for general content, while 700 emphasizes critical information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | 0.3px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.35px | `--text-body-sm` |
| body | 16px | 1.38 | 0.4px | `--text-body` |
| subheading | 18px | 1.38 | 0.45px | `--text-subheading` |
| heading | 20px | 1.2 | 0.5px | `--text-heading` |
| heading-lg | 28px | 1.2 | 0.7px | `--text-heading-lg` |
| display | 40px | 1.2 | 1px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| inputs | 8px |
| buttons | 8px |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Ghost Button
**Role:** Navigation, secondary actions, in-content links

Transparent background, 'Off-White' text, 'Muted Silver' 1px border. No padding specified for common usage, implying content-based sizing.

### Primary Action Button
**Role:** Main calls to action, form submissions

Background 'Sky Blue', text 'Button Dark Text', 8px border-radius, 8px vertical padding, 16px horizontal padding.

### Signup CTA Button
**Role:** Specific call to action, usually in hero or signup forms.

Background 'Electric Teal', text 'Text Dark', 0px 8px 8px 0px border-radius (rounded right side), 8px vertical padding, 44px horizontal padding.

### Default Card
**Role:** Content presentation, media cards.

Transparent background, 12px border-radius, no box-shadow, no padding implies content fills the card directly.

### Black Background Card
**Role:** Emphasized content cards, often for media previews.

Background 'rgb(0, 0, 0)' (black), 12px border-radius, no box-shadow, no padding.

### Email Input Field
**Role:** User input for email addresses.

Background 'Cool Graphite', placeholder text 'Ghost Gray', 8px 0px 0px 8px border-radius (rounded left side), 12px horizontal padding. No vertical padding explicitly defined, implying default browser or container sizing.

### Ghost Badge
**Role:** Content metadata, labels

Transparent background, 'Off-White' text, 0px border-radius, no padding.

## Do's and Don'ts

### Do
- Use 'Deep Midnight' (#040714) as the base background for most full-bleed sections to maintain immersion.
- Apply 'Sky Blue' (#33ddff) for primary interactive elements, ensuring high contrast against dark backgrounds.
- Maintain a comfortable density with an 'elementGap' of '8px' for most inline spacing between UI elements.
- Ensure all text, especially headlines, uses the Inspire typeface with a consistent '0.0250em' letter-spacing.
- Define card and button corners with '12px' and '8px' border-radius respectively, using the specified tokens.
- Prioritize high contrast for text: 'Off-White' (#fafafa) on 'Deep Midnight' (#040714) or 'Cool Graphite' (#282a36).
- Use 'Muted Silver' (#e5e7eb) for subtle UI borders, outlines, and dividers to articulate structure without distraction.

### Don't
- Do not introduce light backgrounds for main content areas; maintain the dark theme for immersion.
- Avoid using highly saturated colors for large areas or decorative elements; reserve vibrancy for functional accents.
- Do not deviate from the established border radii; maintain '12px' for cards and '8px' for interactive controls.
- Do not add prominent shadows or elevation unless specifically called for by a component; the system relies on flat surfaces.
- Refrain from using generic sans-serif fonts; the Inspire typeface is critical for brand recognition.
- Do not use overly dense layouts; maintain a 'comfortable' spacing with '24px' section gaps.
- Avoid decorative gradients; the system uses solid colors for background and accents.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Blue Black | `#010104` | Base layer for global navigation. |
| 1 | Deep Midnight | `#040714` | Primary page background and main content container. |
| 2 | Accent Gray | `#1e1f24` | Slightly elevated background for some UI elements that need mild distinction. |
| 3 | Cool Graphite | `#282a36` | Backgrounds for interactive elements like input fields, providing slight elevation. |

## Imagery

This system primarily uses product-focused imagery, specifically movie posters and show thumbnails, which are presented as contained elements within a grid. These are generally full-color, cinematic stills or stylized artwork, with minimal alteration. The iconography is typically simple, often white or light gray outlines or fills, serving functional roles rather than decorative. Image density is high in content sections, where visuals are the primary draw, while informational sections remain text-dominant.

## Layout

The page primarily uses a max-width contained layout in its main content areas, set against a full-bleed dark background. The hero section often features content previews or a signup form centered over a blurred background of media. Section rhythm is driven by consistent vertical spacing of '24px' between content blocks. Content is arranged in flexible grids for media display and alternating text-left/visual-right patterns for feature descriptions. Navigation is a sticky top bar, minimally styled with 'Canvas Blue Black' background and 'Off-White' text.

## Agent Prompt Guide

Quick Color Reference:
text: #fafafa
background: #040714
border: #e5e7eb
accent: #02d6e8
primary action: #33ddff (filled action)

Example Component Prompts:
Create a primary action button: background 'Sky Blue' (#33ddff), text 'Button Dark Text' (#17171c), 8px border-radius, 8px vertical padding, 16px horizontal padding, using Inspire weight 700 at 16px.
Create an email input field: background 'Cool Graphite' (#282a36), placeholder text 'Ghost Gray' (#b7b8bd), 8px 0px 0px 8px border-radius, 12px horizontal padding, using Inspire weight 400 at 16px.
Create a ghost button for navigation: transparent background, text 'Off-White' (#fafafa), 1px border 'Muted Silver' (#e5e7eb), no explicit padding (content-based), using Inspire weight 400 at 14px.
Create a content card: 'Deep Midnight' (#040714) background, 12px border-radius, no padding, 'Muted Silver' (#e5e7eb) 1px border.

## Similar Brands

- **Netflix** — Dark-mode UI, emphasis on content thumbnails, and a primary accent color for CTAs.
- **HBO Max** — Content-heavy, dark-themed UI with clear grid layouts for media consumption and similar typographic treatment.
- **Apple TV+** — Uses dark backgrounds, stark white typography, and a clean presentation for visual content.
- **Prime Video** — Focus on content discovery within a dark interface, utilizing carousels and grid views.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-midnight: #040714;
  --color-cool-graphite: #282a36;
  --color-sky-blue: #33ddff;
  --color-electric-teal: #02d6e8;
  --color-text-dark: #02172a;
  --color-muted-silver: #e5e7eb;
  --color-light-gray: #c0c0c0;
  --color-off-white: #fafafa;
  --color-deep-space: #0e0b14;
  --color-ghost-gray: #b7b8bd;
  --color-accent-gray: #1e1f24;
  --color-button-dark-text: #17171c;
  --color-faint-border: #6f717b;
  --color-canvas-blue-black: #010104;

  /* Typography — Font Families */
  --font-inspire: 'Inspire', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.35px;
  --text-body: 16px;
  --leading-body: 1.38;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --tracking-subheading: 0.45px;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --tracking-heading: 0.5px;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.7px;
  --text-display: 40px;
  --leading-display: 1.2;
  --tracking-display: 1px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-inputs: 8px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-canvas-blue-black: #010104;
  --surface-deep-midnight: #040714;
  --surface-accent-gray: #1e1f24;
  --surface-cool-graphite: #282a36;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-midnight: #040714;
  --color-cool-graphite: #282a36;
  --color-sky-blue: #33ddff;
  --color-electric-teal: #02d6e8;
  --color-text-dark: #02172a;
  --color-muted-silver: #e5e7eb;
  --color-light-gray: #c0c0c0;
  --color-off-white: #fafafa;
  --color-deep-space: #0e0b14;
  --color-ghost-gray: #b7b8bd;
  --color-accent-gray: #1e1f24;
  --color-button-dark-text: #17171c;
  --color-faint-border: #6f717b;
  --color-canvas-blue-black: #010104;

  /* Typography */
  --font-inspire: 'Inspire', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: 0.3px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.35px;
  --text-body: 16px;
  --leading-body: 1.38;
  --tracking-body: 0.4px;
  --text-subheading: 18px;
  --leading-subheading: 1.38;
  --tracking-subheading: 0.45px;
  --text-heading: 20px;
  --leading-heading: 1.2;
  --tracking-heading: 0.5px;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: 0.7px;
  --text-display: 40px;
  --leading-display: 1.2;
  --tracking-display: 1px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-40: 40px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
}
```
