# SpatialChat — Style Reference
> Violet accented white canvas. Pure white surfaces are the backdrop for precise charcoal text and interactive violet elements, recalling an architect's blueprint highlighted with a single, crucial color.

**Theme:** light

This design system projects a feeling of modern clarity and understated robustness, achieved through a stark contrast of dark text on clean white surfaces, accentuated by a single vibrant violet. The generous use of space and subtle elevation creates a breathable, organized interface. Rounded corners on interactive elements and cards introduce an approachable softness to an otherwise precise and functional aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#ffffff` | `--color-absolute-zero` | Page backgrounds, card surfaces, form fields, primary button text — forms the expansive, clean base. |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Primary text, prominent headings, solid borders on buttons — provides strong contrast and legibility. |
| Deep Space Charcoal | `#030712` | `--color-deep-space-charcoal` | Main headings, important text, menu items — slightly softer than pure black, but still commanding. |
| Slate Gray | `#4b5563` | `--color-slate-gray` | Secondary text, descriptive body copy, input placeholders — provides visual hierarchy without competing with primary text. |
| Whisper Gray | `#f9fafb` | `--color-whisper-gray` | Subtle background for UI elements, light separation layers — provides slight visual depth from pure white. |
| Fog | `#e5e7eb` | `--color-fog` | Default input borders, subtle dividers — defines boundaries gently. |
| Periwinkle Mist | `#f2f2ff` | `--color-periwinkle-mist` | Background for accent badges, subtle highlights — a very light, almost white tint of the primary color. |
| Steel Gray | `#d1d5db` | `--color-steel-gray` | Input borders (focused state, or certain variants) — a slightly darker border than Fog. |
| Majestic Violet | `#5727e7` | `--color-majestic-violet` | Primary CTA buttons, active states, accent badges, interactive elements — the sole vibrant brand color, drawing immediate attention. |

## Tokens — Typography

### Satoshi — The sole typeface, Satoshi, is used across all text elements. Its clean, geometric yet humanist forms provide a modern and friendly professionalism at all sizes. Heading sizes leverage higher weights (500-700) for presence, while body text remains legible at 400. Letter spacing remains neutral for open readability. · `--font-satoshi`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 14px, 16px, 18px, 20px, 24px, 32px, 40px, 44px, 48px, 60px
- **Line height:** 1.30, 1.38, 1.40, 1.43, 1.50, 1.56, 1.60
- **Letter spacing:** normal
- **Role:** The sole typeface, Satoshi, is used across all text elements. Its clean, geometric yet humanist forms provide a modern and friendly professionalism at all sizes. Heading sizes leverage higher weights (500-700) for presence, while body text remains legible at 400. Letter spacing remains neutral for open readability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.5 | — | `--text-body-lg` |
| subheading | 20px | 1.5 | — | `--text-subheading` |
| heading | 24px | 1.43 | — | `--text-heading` |
| heading-lg | 32px | 1.38 | — | `--text-heading-lg` |
| display-sm | 40px | 1.38 | — | `--text-display-sm` |
| display | 48px | 1.3 | — | `--text-display` |
| display-lg | 60px | 1.3 | — | `--text-display-lg` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 180 | 180px | `--spacing-180` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 8px |
| inputs | 8px |
| buttons | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.06) 0px 4px 28px 0px` | `--shadow-xl` |
| subtle | `rgba(0, 0, 0, 0.06) 0px 1px 2px 0px` | `--shadow-subtle` |
| md | `rgba(0, 0, 0, 0.06) 0px 4px 16px 0px` | `--shadow-md` |

### Layout

- **Section gap:** 64px
- **Card padding:** 12-24px
- **Element gap:** 8px

## Components

### Primary Action Button
**Role:** Main call to action

Solid Majestic Violet (#5727e7) background, Absolute Zero (#ffffff) text, 12px border radius, 12px 15px padding. This button stands out as the primary interactive element.

### Outline Accent Button
**Role:** Secondary action or navigation

Transparent background, Charcoal Black (#000000) text and 1px border, 12px border radius, 12px 15px padding. Used for alternative actions where emphasis is not as high as primary.

### Dark Outline Neutral Button
**Role:** Tertiary action, often in headers

Transparent background, Charcoal Black (#222222) text and 1px border, 8px border radius, 15px padding. A more prominent outline button used for login/demo in the header area.

### Hero White Button
**Role:** Prominent utility button in hero

Absolute Zero (#ffffff) background, Charcoal Black (#000000) text, 12px border radius, 12px 24px padding. Used for high-visibility secondary actions within hero sections.

### Default Input Field
**Role:** Standard text input

Absolute Zero (#ffffff) background, Slate Gray (#6b7280) placeholder text, 1px Fog (#e5e7eb) border, 8px border radius, 12px padding all around. Clean and unobtrusive.

### Premium Input Field
**Role:** Enhanced or larger text input

Absolute Zero (#ffffff) background, Slate Gray (#6b7280) placeholder text, 1px Fog (#e5e7eb) border, 14px border radius, 18px padding vertical, 16px horizontal. Features a slightly larger size and more rounded corners.

### Violet New Badge
**Role:** Indicator for new features/items

Solid Majestic Violet (#5727e7) background, Absolute Zero (#ffffff) text, 8px border radius, 6px 10px padding. Boldly highlights new content.

### Periwinkle Info Badge
**Role:** General informational tag

Periwinkle Mist (#f2f2ff) background, Deep Space Charcoal (#030712) text, 8px border radius, 6px 8px padding. A softer, background-compatible tag for information.

### Outline Subtle Badge
**Role:** Contextual, less obtrusive tag

Transparent background, RGBA(51, 51, 51, 0.8) text, 8px border radius, 8px padding all around. Used for informational tags or categories where a background is not desired.

### Client Logo Card
**Role:** Display partner or client logos

Absolute Zero (#ffffff) background, 12px border radius, with a subtle rgba(0, 0, 0, 0.1) box-shadow. Standard padding for contained logos. Used in grids.

## Do's and Don'ts

### Do
- Use Deep Space Charcoal (#030712) for all primary headings and key text to maintain visual impact.
- Apply Majestic Violet (#5727e7) exclusively to primary call-to-action buttons and critical interactive elements.
- Prioritize Absolute Zero (#ffffff) for all main backgrounds and card surfaces to ensure visual spaciousness.
- Maintain 12px border radius for all buttons and image containers, with 8px for badges and inputs, and 16px for cards.
- Utilize Clear Shadow Subtle (rgba(0,0,0,0.06) 0px 1px 2px 0px) for buttons or very light elevation, and Large Shadow Subtle (rgba(0, 0, 0, 0.06) 0px 4px 28px 0px) for cards for visible yet soft depth.
- Employ Satoshi font with normal letter spacing across all text for a consistent, accessible typographic voice.

### Don't
- Do not introduce additional vibrant colors; the system relies on a focused palette of neutrals and a single Majestic Violet accent.
- Avoid using hard, sharp corners; all interactive and container elements should adhere to the established radii.
- Do not deviate from the Satoshi typeface or its specified weights; it is the brand's sole typographic identity.
- Refrain from heavy, dark shadows; elevation is achieved through subtle, light shadow effects.
- Do not cluster elements without adequate spacing; maintain generous internal padding (12px, 15px) and external spacing (16px, 24px) for visual comfort.
- Do not use highly saturated colorful icons; all icons should be achromatic or carry the Majestic Violet accent.

## Elevation

- **Card/Container:** `rgba(0, 0, 0, 0.06) 0px 4px 28px 0px`
- **Button/Link:** `rgba(0, 0, 0, 0.06) 0px 1px 2px 0px`

## Imagery

The visual language focuses on a mix of product screenshots, abstract geometric graphics, and crisp, minimal icons. Product screenshots are contained within rounded frames (12px radius) and sometimes feature subtle elevation via shadows, showing the interface clearly and often in a context of use (e.g., small user profile circles). Illustration is minimal, leaning towards very abstract, simple forms or clean line art. Icons are primarily outlined or solid in achromatic colors, with occasionally Majestic Violet accents for interactive states. The overall role of imagery is explanatory and showcases the product's functionality in a clean, non-distracting manner, rather than decorative high-key photography.

## Layout

The page primarily uses a max-width contained layout, centered on the screen, providing ample negative space on wider viewports. The hero section is full-width with a centered headline and subtext, followed by centered CTA buttons. Content sections typically alternate between a two-column layout of text on one side and an illustrative product screenshot on the other, or feature grids like the 3-column client logo display. Vertical rhythm is established by consistent section gaps, creating distinct, breathable content blocks. Navigation is a fixed top bar with a left-aligned logo and right-aligned action buttons, maintaining visibility throughout scrolling. The layout emphasizes clarity and easy scannability of information.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #030712
- Background (Page): #ffffff
- CTA (Button): #5727e7
- Border (Input): #e5e7eb
- Accent (Badge background): #f2f2ff

### 3-5 Example Component Prompts
1. Create a Hero Section: Absolute Zero (#ffffff) background. Centered primary heading 'SpatialChat is an All-in-One Virtual Events & Meetings Platform' (Satoshi, 60px, weight 700, #030712, lineHeight 1.3). Below it, centered body text 'Create an engaging virtual environment where attendees can connect, interact, and move freely just like a real-life event.' (Satoshi, 18px, weight 400, #4b5563, lineHeight 1.5). Two centered buttons below: Primary Action Button ('Book a Demo'), and Outline Accent Button ('Try it Free ->', text #000000).
2. Design a Client Logo Card: Create a card with an Absolute Zero (#ffffff) background, 16px border radius, and the shadow 'rgba(0, 0, 0, 0.06) 0px 4px 28px 0px'. Inside, center a placeholder logo with 12px padding vertically and 24px horizontally. Label this 'ClientLogoCard' for a grid layout.
3. Make a Default Input Field: Use Absolute Zero (#ffffff) background, 1px Fog (#e5e7eb) border, 8px border radius. Placeholder text 'Enter your email' should be Slate Gray (#6b7280) and use Satoshi 16px weight 400. Apply 12px padding all around.
4. Build a Majestic Violet New Badge: Utilize a Majestic Violet (#5727e7) background, with Absolute Zero (#ffffff) text 'New'. Set 8px border radius, and 6px 10px padding.

## Similar Brands

- **Zoom** — Clean white backgrounds with dark text and a single, strong accent color for CTAs, conveying professionalism in virtual communication.
- **Miro** — Focus on highly readable content on a clean, light canvas, leveraging crisp typography and subtle visual hierarchy through elevation and spacing.
- **Figma** — Interface-focused design with clear content containers, strong typographic hierarchy, and a restrained use of color to emphasize functionality.
- **Slack** — Employs an energetic accent color against a largely achromatic, space-efficient UI to highlight interaction points and brand identity.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #ffffff;
  --color-charcoal-black: #000000;
  --color-deep-space-charcoal: #030712;
  --color-slate-gray: #4b5563;
  --color-whisper-gray: #f9fafb;
  --color-fog: #e5e7eb;
  --color-periwinkle-mist: #f2f2ff;
  --color-steel-gray: #d1d5db;
  --color-majestic-violet: #5727e7;

  /* Typography — Font Families */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.43;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.38;
  --text-display-sm: 40px;
  --leading-display-sm: 1.38;
  --text-display: 48px;
  --leading-display: 1.3;
  --text-display-lg: 60px;
  --leading-display-lg: 1.3;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 12-24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 8px;
  --radius-inputs: 8px;
  --radius-buttons: 12px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.06) 0px 4px 28px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.06) 0px 4px 16px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #ffffff;
  --color-charcoal-black: #000000;
  --color-deep-space-charcoal: #030712;
  --color-slate-gray: #4b5563;
  --color-whisper-gray: #f9fafb;
  --color-fog: #e5e7eb;
  --color-periwinkle-mist: #f2f2ff;
  --color-steel-gray: #d1d5db;
  --color-majestic-violet: #5727e7;

  /* Typography */
  --font-satoshi: 'Satoshi', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.5;
  --text-heading: 24px;
  --leading-heading: 1.43;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.38;
  --text-display-sm: 40px;
  --leading-display-sm: 1.38;
  --text-display: 48px;
  --leading-display: 1.3;
  --text-display-lg: 60px;
  --leading-display-lg: 1.3;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 50px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.06) 0px 4px 28px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
  --shadow-md: rgba(0, 0, 0, 0.06) 0px 4px 16px 0px;
}
```
