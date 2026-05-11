# Krisp — Style Reference
> Deep space command console. Information-dense, with critical functions highlighted by a bright, singular light source against a dark, expansive backdrop.

**Theme:** light

Krisp's visual identity balances robust clarity with a subtle, dynamic energy. Dominant neutral whites and a deep, muted indigo base (#131032) provide a stable foundation, allowing a single, vivid violet accent (#614efa) to punctuate interactive elements. The type scale relies on the highly functional Plus Jakarta Sans, with an emphasis on generous line heights and subtle letter spacing for hierarchy, ensuring legibility even for dense information. Rounded elements contrast with the underlying structural precision, adding a soft, approachable quality to the technical focus.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space Indigo | `#131032` | `--color-deep-space-indigo` | Primary text, darkest surface background (rarely used, mostly for backgrounds of large sections or card headers), borders, prominent icons. Establishes a serious, professional tone. |
| Krisp Violet | `#614efa` | `--color-krisp-violet` | Primary Call-to-Action buttons, active states, key interactive elements. Provides a vibrant, energetic accent against the neutral and dark tones. |
| Off White Background | `#ffffff` | `--color-off-white-background` | Page backgrounds, card surfaces, form inputs. Creates a clean, expansive canvas. |
| Pale Gray Surface | `#f7f7f8` | `--color-pale-gray-surface` | Subtle background for secondary sections, borders. Adds visual texture and separation without strong contrast. |
| Subtle Accent Teal | `#eafdfa` | `--color-subtle-accent-teal` | Badge backgrounds, subtle accents. A very light, near-neutral tint that hints at freshness. |
| Muted Gray Text | `#918f9f` | `--color-muted-gray-text` | Secondary text, descriptive elements. Softens informational blocks. |
| Light Gray Border | `#e7e7ea` | `--color-light-gray-border` | Component borders, dividers. Delimits elements with a light touch. |
| Vivid Red Accent | `#fe6257` | `--color-vivid-red-accent` | Error states, occasional strong call-out accents. Appears sparingly for high-attention elements. |
| Crisp White Text | `#ffffff` | `--color-crisp-white-text` | Text on dark backgrounds, particularly accent buttons. Ensures readability against saturated colors. |
| Indigo Gradient 1 | `linear-gradient(90deg, rgb(97, 78, 250) 22.93%, rgb(98, 200, 255) 76.42%)` | `--color-indigo-gradient-1` | Decorative elements, background fills for featured sections, creating a dynamic sense of depth and interaction. |
| Indigo Gradient 2 | `linear-gradient(90deg, rgb(74, 59, 190) 0%, rgb(190, 115, 250) 77.2%)` | `--color-indigo-gradient-2` | Decorative elements, background fills for featured sections, conveying richness and sophistication. |

## Tokens — Typography

### Plus Jakarta Sans — The sole typeface, used across all elements from headings to body text and UI components. Its contemporary geometric sans-serif nature provides a clean, highly legible foundation that scales well from small captions to large display headlines. Weight variation is critical for hierarchy, from light informational text to bold CTAs. · `--font-plus-jakarta-sans`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 14px, 16px, 18px, 20px, 22px, 26px, 36px, 42px, 48px, 58px
- **Line height:** 1.14, 1.17, 1.20, 1.24, 1.25, 1.33, 1.40, 1.43, 1.45, 1.50, 1.60, 1.62, 1.63, 1.70, 1.73, 1.75, 1.78, 1.86, 1.89, 2.00, 2.63
- **Letter spacing:** normal
- **Role:** The sole typeface, used across all elements from headings to body text and UI components. Its contemporary geometric sans-serif nature provides a clean, highly legible foundation that scales well from small captions to large display headlines. Weight variation is critical for hierarchy, from light informational text to bold CTAs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.7 | — | `--text-caption` |
| body-sm | 14px | 1.6 | — | `--text-body-sm` |
| body | 16px | 1.6 | — | `--text-body` |
| body-lg | 18px | 1.6 | — | `--text-body-lg` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 26px | 1.25 | — | `--text-heading` |
| heading-lg | 36px | 1.2 | — | `--text-heading-lg` |
| display | 42px | 1.17 | — | `--text-display` |
| display-xl | 48px | 1.14 | — | `--text-display-xl` |
| display-xxl | 58px | 1.14 | — | `--text-display-xxl` |

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
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |
| 88 | 88px | `--spacing-88` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |
| 140 | 140px | `--spacing-140` |
| 160 | 160px | `--spacing-160` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| pill | 9999px |
| cards | 16px |
| badges | 12px |
| buttons | 8px |

### Layout

- **Page max-width:** 1280px
- **Section gap:** 64-80px
- **Card padding:** 24px
- **Element gap:** 8px

## Components

### Primary Action Button (Violet Filled)
**Role:** Call to action

Solid Krisp Violet (#614efa) background with Crisp White text. Slightly rounded corners at 8px. Padding 8px top/bottom, 20px left/right. Used for primary conversions like 'Get Krisp'.

### Secondary Action Button (Indigo Filled)
**Role:** Secondary action

Solid Deep Space Indigo (#131032) background with Crisp White text. Sharp 0px corners. Padding 8px top/bottom, 20px left/right. Used for actions like 'Book a demo'.

### Pill Button (White Outlined)
**Role:** Tertiary action/informational link

Crisp White background with Deep Space Indigo text and border (#131032). Fully rounded, 48px border-radius creating a pill shape. Padding 12px top/bottom, 16px-20px left/right. Used for attention-grabbing links like 'Vote for Krisp'.

### Feature Card (White Background)
**Role:** Content display

Crisp White background (#ffffff) with rounded corners at 16px. Content padding is typically 24px. Contains headings and body text, occasionally with an icon.

### Navigation Link
**Role:** Primary navigation

Deep Space Indigo text (#131032) at 16px, weight 400. Hover states likely involve a subtle underline or color change, though not explicitly defined by single tokens.

## Do's and Don'ts

### Do
- Prioritize Plus Jakarta Sans at all weights for both headings and body text to maintain typographic consistency.
- Use Krisp Violet (#614efa) exclusively for primary call-to-action buttons and key interactive states to maximize impact.
- Establish clear hierarchy with the Deep Space Indigo (#131032) for main headings and text, and Muted Gray Text (#918f9f) for secondary descriptive copy.
- Implement a base border-radius of 8px for most interactive elements, reserving 12px for badges and 9999px for distinct pill-shaped components.
- Leverage the Crisp White Background (#ffffff) and Pale Gray Surface (#f7f7f8) to create clear visual separation between content sections.
- Employ gradients (e.g., linear-gradient(90deg, #614efa 22.93%, #62c8ff 76.42%)) for hero sections or distinct visual components to add dynamism.

### Don't
- Do not introduce new typefaces; rely solely on Plus Jakarta Sans.
- Avoid using highly saturated colors other than Krisp Violet (#614efa) for interactive elements, except for semantic red where appropriate.
- Do not use dark backgrounds for general page content; maintain a light theme with crisp white or pale gray surfaces.
- Avoid excessive use of drop shadows; maintain a flat aesthetic except for intentional elevation of modals or specific cards.
- Do not deviate from the established spacing scale (multiples of 4px) for padding and margins.
- Avoid non-functional decorative elements; every visual choice should serve a purpose in clarity or interaction.

## Imagery

The visual language focuses on abstract graphics and conceptual illustrations rather than photography. Imagery features gradients of Deep Space Indigo and Krisp Violet, often with subtle geometric patterns or soft, ethereal glows. Product screenshots, when present, are clean and tightly integrated into the UI. Icons are simple, outlined, and monochromatic, largely in Deep Space Indigo, serving an explanatory role. The overall density is balanced, allowing ample negative space around key text blocks while using graphics to enhance meaning and break visual monotony.

## Layout

The page employs a max-width 1280px centered content model, with some hero sections extending full-bleed, particularly when using a darker background. The hero typically features a centered headline over a subtle gradient or solid background, followed by descriptive text and CTAs. Sections alternate between Crisp White and Pale Gray backgrounds, creating a clear vertical rhythm. Content is generally arranged in 2-column layouts (text alongside imagery/cards) or 3-column card grids for features. Vertical spacing between sections is generous, around 64-80px. The navigation is a sticky top bar with clearly defined links and primary/secondary action buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #131032 (Deep Space Indigo)
- Background: #ffffff (Off White Background)
- CTA Button: #614efa (Krisp Violet)
- Border: #e7e7ea (Light Gray Border)
- Secondary Text: #918f9f (Muted Gray Text)

### 3-5 Example Component Prompts
1. Create a primary call-to-action button: solid #614efa background, #ffffff text, Plus Jakarta Sans weight 700, 16px size, padding 8px top/bottom, 20px left/right, 8px border-radius.
2. Create an informational badge: solid #eafdfa background, #131032 text, Plus Jakarta Sans weight 500, 14px size, padding 4px top/bottom, 16px left/right, 12px border-radius.
3. Create a feature card: #ffffff background, 16px border-radius, 24px internal padding. Headline 'Transcription & Recording' in Plus Jakarta Sans weight 600, 26px size, #131032. Body text in Plus Jakarta Sans weight 400, 16px size, #918f9f.
4. Create a hero section headline: 'Voice AI for meetings' in #131032 and #614efa, Plus Jakarta Sans weight 700, 58px size, line-height 1.14. Subtext: 'For teams, call centers, and developers' with Plus Jakarta Sans weight 400, 22px size, #918f9f, line-height 1.4.

## Similar Brands

- **Linear** — Both use a minimalist, high-contrast aesthetic with deep neutrals and a single strong accent color to highlight interactions and status.
- **Anthropic** — Similar approach to using clean sans-serif typography, ample whitespace, and a focus on clarity for complex AI-related content.
- **Vercel** — Shares a sophisticated, developer-focused aesthetic with strong typography, careful use of color for hierarchy, and gradients for visual interest.
- **Notion** — Employs a clean, functional UI with an emphasis on legibility and structured information, using subtle color accents for interactives.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space-indigo: #131032;
  --color-krisp-violet: #614efa;
  --color-off-white-background: #ffffff;
  --color-pale-gray-surface: #f7f7f8;
  --color-subtle-accent-teal: #eafdfa;
  --color-muted-gray-text: #918f9f;
  --color-light-gray-border: #e7e7ea;
  --color-vivid-red-accent: #fe6257;
  --color-crisp-white-text: #ffffff;
  --color-indigo-gradient-1: #614efa;
  --gradient-indigo-gradient-1: linear-gradient(90deg, rgb(97, 78, 250) 22.93%, rgb(98, 200, 255) 76.42%);
  --color-indigo-gradient-2: #4a3bbe;
  --gradient-indigo-gradient-2: linear-gradient(90deg, rgb(74, 59, 190) 0%, rgb(190, 115, 250) 77.2%);

  /* Typography — Font Families */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.7;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-body-lg: 18px;
  --leading-body-lg: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 26px;
  --leading-heading: 1.25;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 42px;
  --leading-display: 1.17;
  --text-display-xl: 48px;
  --leading-display-xl: 1.14;
  --text-display-xxl: 58px;
  --leading-display-xxl: 1.14;

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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Layout */
  --page-max-width: 1280px;
  --section-gap: 64-80px;
  --card-padding: 24px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-pill: 9999px;
  --radius-cards: 16px;
  --radius-badges: 12px;
  --radius-buttons: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space-indigo: #131032;
  --color-krisp-violet: #614efa;
  --color-off-white-background: #ffffff;
  --color-pale-gray-surface: #f7f7f8;
  --color-subtle-accent-teal: #eafdfa;
  --color-muted-gray-text: #918f9f;
  --color-light-gray-border: #e7e7ea;
  --color-vivid-red-accent: #fe6257;
  --color-crisp-white-text: #ffffff;
  --color-indigo-gradient-1: #614efa;
  --color-indigo-gradient-2: #4a3bbe;

  /* Typography */
  --font-plus-jakarta-sans: 'Plus Jakarta Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.7;
  --text-body-sm: 14px;
  --leading-body-sm: 1.6;
  --text-body: 16px;
  --leading-body: 1.6;
  --text-body-lg: 18px;
  --leading-body-lg: 1.6;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 26px;
  --leading-heading: 1.25;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --text-display: 42px;
  --leading-display: 1.17;
  --text-display-xl: 48px;
  --leading-display-xl: 1.14;
  --text-display-xxl: 58px;
  --leading-display-xxl: 1.14;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;
  --spacing-88: 88px;
  --spacing-100: 100px;
  --spacing-120: 120px;
  --spacing-140: 140px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 48px;
  --radius-full-2: 9999px;
}
```
