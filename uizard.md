# Uizard — Style Reference
> Midnight AI Canvas

**Theme:** dark

Uizard employs a dark, futuristic aesthetic with a strong emphasis on vivid purple accents. Interfaces are generally monochrome with ample negative space. Typography is confident and slightly condensed, guiding the user through AI-powered flows. Buttons and interactive elements are clearly defined by distinct radii and color choices, creating a functional, tech-forward experience. Surface depth is subtle, achieved more through slight tinting and border treatments than heavy shadows.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0b0b0b` | `--color-midnight-ink` | Primary page and card backgrounds transitioning into deeper shadows |
| Deep Space | `#000000` | `--color-deep-space` | Base canvas for darker sections, card backgrounds, and subtle shadow tints |
| Lunar Surface | `#f5f5f5` | `--color-lunar-surface` | Primary body text, neutral borders, and iconography |
| Asteroid Dust | `#aeaeae` | `--color-asteroid-dust` | Muted secondary text and less prominent borders |
| Cosmic Gray | `#212121` | `--color-cosmic-gray` | Divider lines, subtle card borders, and ghost button outlines |
| Eclipse Gray | `#2e2e2e` | `--color-eclipse-gray` | Focused card borders and dividers |
| Starlight | `#ffffff` | `--color-starlight` | Headlines, critical text, input fields, and active state accents |
| AI Violet | `#a881fe` | `--color-ai-violet` | Primary calls to action, interactive elements, highlights, and subtle background accent graphics |
| AI Violet Gradient | `linear-gradient(0deg, rgb(100, 25, 255), rgb(168, 129, 254))` | `--color-ai-violet-gradient` | Background gradients for hero sections and brand-focused elements, providing depth and energy |
| Call to Action Blue | `#1e90ff` | `--color-call-to-action-blue` | Secondary calls to action, distinct from the primary AI Violet, for specific conversion paths |

## Tokens — Typography

### Satoshi-Variable — Primary functional typeface for most UI elements, body text, and subheadings. Its variable nature allows for a range of expressiveness from compact readability to confident emphasis. The slightly condensed forms maintain a tech-forward feel. · `--font-satoshi-variable`
- **Substitute:** Inter
- **Weights:** 400, 480, 540, 560, 640
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px, 40px
- **Line height:** 1.00, 1.15, 1.20, 1.25, 1.29, 1.33, 1.38, 1.40, 1.43
- **Letter spacing:** -1px at 40px, -0.45px at 24px, -0.29px at 18px, -0.24px at 16px, -0.19px at 14px, -0.16px at 12px, 1px for 0.083em
- **Role:** Primary functional typeface for most UI elements, body text, and subheadings. Its variable nature allows for a range of expressiveness from compact readability to confident emphasis. The slightly condensed forms maintain a tech-forward feel.

### ClashGrotesk-Variable — Display font for large, impactful headlines, conveying a modern and bold brand voice. Its distinct character shapes set it apart for hero content. · `--font-clashgrotesk-variable`
- **Substitute:** Space Mono
- **Weights:** 540
- **Sizes:** 72px
- **Line height:** 1.00
- **Letter spacing:** -0.58px at 72px
- **Role:** Display font for large, impactful headlines, conveying a modern and bold brand voice. Its distinct character shapes set it apart for hero content.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | -0.16px | `--text-caption` |
| body-sm | 14px | 1.4 | -0.19px | `--text-body-sm` |
| body | 16px | 1.38 | -0.24px | `--text-body` |
| subheading | 18px | 1.33 | -0.29px | `--text-subheading` |
| heading-sm | 20px | 1.29 | -0.29px | `--text-heading-sm` |
| heading | 24px | 1.25 | -0.45px | `--text-heading` |
| heading-lg | 40px | 1.15 | -1px | `--text-heading-lg` |
| display | 72px | 1 | -0.58px | `--text-display` |

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
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 4px |
| cards | 16px |
| inputs | 10px |
| buttons | 12px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(3, 3, 3, 0.12) 0px 12px 30px -4px` | `--shadow-xl` |
| md | `rgba(168, 129, 254, 0.64) 0px 2px 12px 0px, rgb(168, 129,...` | `--shadow-md` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Filled button for primary calls to action, leveraging the brand violet.

Background: AI Violet (#a881fe), Text: Starlight (#ffffff), Border Radius: 12px, Padding: 0px vertical, 24px horizontal. Uses Satoshi-Variable font.

### Secondary Action Button
**Role:** Filled button for secondary actions, using a vivid blue.

Background: Call to Action Blue (#1e90ff), Text: Starlight (#ffffff), Border Radius: 8px, Padding: 0px vertical, 16px horizontal. Uses Satoshi-Variable font.

### Ghost Navigation Button
**Role:** Text-only button for navigation, blending into the dark background.

Background: transparent, Text: Starlight (#ffffff), Border Radius: 0px, Padding: 0px. Uses Satoshi-Variable font.

### Testimonial Card
**Role:** Transparent card for displaying customer testimonials.

Background: rgba(33, 33, 33, 0.32), Border Radius: 16px, Padding: 24px. No shadow. Uses Satoshi-Variable font for content.

### Implicit Card
**Role:** Card defined by padding and rounded corners on the base background, without explicit background color.

Background: transparent, Border Radius: 16px, Padding: 40px 0px 40px 40px. No shadow. Used for complex content blocks that subtly emerge from the main background.

### Primary Input Field
**Role:** Input field for user text entry.

Background: Starlight (#ffffff), Text: Midnight Ink (#111111), Border Radius: 10px, Padding: 12px. Placeholder text is Muted Secondary Text.

## Do's and Don'ts

### Do
- Prioritize AI Violet (#a881fe) for all primary calls to action, ensuring prominence and brand consistency.
- Use Satoshi-Variable for all body text and interface elements, varying weight according to hierarchy but favoring 400-540 for readability.
- Apply 12px border radius to all primary buttons and 10px to input fields for a consistent interactive element feel.
- Maintain a clear visual hierarchy by contrasting Starlight (#ffffff) for headlines and primary text against Midnight Ink (#0b0b0b) backgrounds.
- Use Cosmic Gray (#212121) or Meteor Gray (#2e2e2e) for subtle borders and dividers, avoiding heavy strokes.
- Employ the AI Violet Gradient for hero sections and illustrative backgrounds to add depth and brand energy.
- Utilize ClashGrotesk-Variable for display headlines (72px, weight 540) to convey a bold, modern brand voice.

### Don't
- Avoid using bright, saturated colors other than AI Violet (#a881fe) or Call to Action Blue (#1e90ff) for functional UI elements.
- Don't apply heavy, opaque shadows; opt for subtle, tinted shadows like rgba(3, 3, 3, 0.12) or the brand-specific AI Violet inset shadow.
- Do not deviate from the established type scale; maintain consistent line heights and letter spacing found in Satoshi-Variable and ClashGrotesk.
- Avoid excessive use of different border radii; stick to 12px for primary buttons, 10px for inputs, and 16px for cards.
- Don't introduce additional achromatic colors that are visually close to Lunar Surface (#f5f5f5) or Asteroid Dust (#aeaeae), to prevent visual clutter.
- Never use full-width, uncontained layouts for main content; always adhere to the implied max-width and central alignment for text blocks.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Deep Space | `#000000` | Base page background for large sections and deep elevation. |
| 1 | Midnight Ink | `#0b0b0b` | Primary page background, slightly lighter than Deep Space, and for card surfaces. |
| 2 | Transparent Card | `#21212152` | Subtly elevated card surfaces with a translucent effect, allowing the background to show through. |
| 3 | Starlight | `#ffffff` | Highest contrast surface for interactive elements like input fields, standing out against dark backgrounds. |

## Elevation

- **Interactive Card:** `rgba(3, 3, 3, 0.12) 0px 12px 30px -4px`
- **Active Brand Element:** `rgba(168, 129, 254, 0.64) 0px 2px 12px 0px, rgb(168, 129, 254) 0px 1px 1px 0px inset`

## Imagery

This site uses a blend of illustrative and abstract graphics, alongside implied product screenshots. The imagery is primarily dark-themed, echoing the UI. Product visuals are presented as sleek, contained representations within device mockups, often with a subtle glowing aura of the AI Violet. Icons are typically filled with 'Starlight' or 'Lunar Surface' against dark backgrounds, maintaining a clean yet visible presence. Abstract gradients, particularly using the AI Violet Gradient, serve as decorative backdrops for hero sections and key messaging. Imagery density is moderate, used to emphasize core product features or add atmospheric depth rather than for exhaustive product tours or heavy content.

## Layout

The page primarily uses a max-width, center-aligned layout, creating a contained and focused experience. The hero section is full-bleed, featuring a large, centered headline over a dramatic AI Violet Gradient background. Sections below alternate between dark tones, maintaining consistent vertical spacing at 40px for major section breaks. Content within sections is often structured in two columns, alternating media and text. A prominent feature is a card grid for testimonials, presenting information in a structured, digestible format. Navigation is a consistent top bar that remains visible, suggesting a sticky header, with prominent 'Sign up for free' button as the primary action.

## Agent Prompt Guide

Quick Color Reference:
text: #f5f5f5
background: #0b0b0b
border: #212121
accent: #1e90ff
primary action: #1e90ff (filled action)

Example Component Prompts:
1. Create a hero section: AI Violet Gradient (linear-gradient(0deg, rgb(100, 25, 255), rgb(168, 129, 254))) background. Headline 'Turn product ideas into concepts' ClashGrotesk-Variable weight 540, 72px, #ffffff, letter-spacing -0.58px. Subtext 'Visualize, communicate, and iterate' Satoshi-Variable weight 400, 18px, #f5f5f5, letter-spacing -0.29px. Input field: background #ffffff, text #111111, padding 12px, radius 10px; beside it, a button: AI Violet (#a881fe), text #ffffff, padding 0px 24px, radius 12px.
2. Create a testimonial card: Background rgba(33, 33, 33, 0.32), radius 16px, padding 24px. Text body-sm Satoshi-Variable weight 400, #f5f5f5, letter-spacing -0.19px. Author name caption Satoshi-Variable weight 400, #aeaeae, letter-spacing -0.16px.
3. Create a Primary Action Button: #1e90ff background, #212121 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

## Similar Brands

- **Framer** — Shares a dark-themed UI with expressive typography, and a similar focus on design tool innovation with strong brand color accents.
- **Linear** — Features a dark, compact interface with sharp typography, limited color palette, and clear, functional button styling.
- **Vercel** — Employs an elevated dark mode, crisp typography, and uses a single dominant accent color for interactive elements and branding.
- **Magic Leap** — Visual identity often includes dark backgrounds, futuristic typefaces, and vibrant purple/blue lighting or accent glows.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0b0b0b;
  --color-deep-space: #000000;
  --color-lunar-surface: #f5f5f5;
  --color-asteroid-dust: #aeaeae;
  --color-cosmic-gray: #212121;
  --color-eclipse-gray: #2e2e2e;
  --color-starlight: #ffffff;
  --color-ai-violet: #a881fe;
  --color-ai-violet-gradient: #6419ff;
  --gradient-ai-violet-gradient: linear-gradient(0deg, rgb(100, 25, 255), rgb(168, 129, 254));
  --color-call-to-action-blue: #1e90ff;

  /* Typography — Font Families */
  --font-satoshi-variable: 'Satoshi-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-clashgrotesk-variable: 'ClashGrotesk-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: -0.16px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.19px;
  --text-body: 16px;
  --leading-body: 1.38;
  --tracking-body: -0.24px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.29px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.29;
  --tracking-heading-sm: -0.29px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.45px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -1px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.58px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w480: 480;
  --font-weight-w540: 540;
  --font-weight-w560: 560;
  --font-weight-w640: 640;

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
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 28px;

  /* Named Radii */
  --radius-tags: 4px;
  --radius-cards: 16px;
  --radius-inputs: 10px;
  --radius-buttons: 12px;

  /* Shadows */
  --shadow-xl: rgba(3, 3, 3, 0.12) 0px 12px 30px -4px;
  --shadow-md: rgba(168, 129, 254, 0.64) 0px 2px 12px 0px, rgb(168, 129, 254) 0px 1px 1px 0px inset;

  /* Surfaces */
  --surface-deep-space: #000000;
  --surface-midnight-ink: #0b0b0b;
  --surface-transparent-card: #21212152;
  --surface-starlight: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0b0b0b;
  --color-deep-space: #000000;
  --color-lunar-surface: #f5f5f5;
  --color-asteroid-dust: #aeaeae;
  --color-cosmic-gray: #212121;
  --color-eclipse-gray: #2e2e2e;
  --color-starlight: #ffffff;
  --color-ai-violet: #a881fe;
  --color-ai-violet-gradient: #6419ff;
  --color-call-to-action-blue: #1e90ff;

  /* Typography */
  --font-satoshi-variable: 'Satoshi-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-clashgrotesk-variable: 'ClashGrotesk-Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: -0.16px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.19px;
  --text-body: 16px;
  --leading-body: 1.38;
  --tracking-body: -0.24px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --tracking-subheading: -0.29px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.29;
  --tracking-heading-sm: -0.29px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.45px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -1px;
  --text-display: 72px;
  --leading-display: 1;
  --tracking-display: -0.58px;

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
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 28px;

  /* Shadows */
  --shadow-xl: rgba(3, 3, 3, 0.12) 0px 12px 30px -4px;
  --shadow-md: rgba(168, 129, 254, 0.64) 0px 2px 12px 0px, rgb(168, 129, 254) 0px 1px 1px 0px inset;
}
```
