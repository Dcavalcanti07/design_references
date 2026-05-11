# Slack — Style Reference
> Vibrant digital workbench.

**Theme:** light

The Slack design system evokes a sense of vibrant, collaborative professionalism, grounded in a playful yet authoritative use of color. Deep purples and a vivid blue serve as primary brand identifiers, balanced against a clean, near-white canvas. Subtle gradients and distinct radial color washes provide depth and visual interest without overwhelming the functional UI, while custom typography maintains a unique, approachable voice.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#fefbff` | `--color-canvas-ice` | Primary page background, expansive neutral space for content. |
| Surface Frost | `#ffffff` | `--color-surface-frost` | Elevated card backgrounds, component containers. |
| Whisper Cloud | `#f9f0ff` | `--color-whisper-cloud` | Subtle background for UI elements, light hovered states. |
| Active Lavender | `#f2defe` | `--color-active-lavender` | Background for active navigation items, subtle highlights. |
| Charcoal Black | `#000000` | `--color-charcoal-black` | Primary text color for headings, body, and high-emphasis elements. |
| Carbon Gray | `#1d1c1d` | `--color-carbon-gray` | Secondary text and icon color, slightly softer than Charcoal Black. |
| Pewter | `#696969` | `--color-pewter` | Tertiary text, muted labels, helper text. |
| Cement Gray | `#757575` | `--color-cement-gray` | Informational text, list item details. |
| Slate Border | `#edeaed` | `--color-slate-border` | Subtle borders and dividers for UI separation. |
| Medium Gray | `#808080` | `--color-medium-gray` | Placeholder text, disabled states, default icon color. |
| Icon Gray | `#5e5d60` | `--color-icon-gray` | Specific icon color within navigation and utility areas. |
| Dark Plum | `#481a54` | `--color-dark-plum` | Primary brand color, used for key UI components like navigation backgrounds and interactive elements. |
| Purple Heart | `#611f69` | `--color-purple-heart` | Primary button background, active states, and emphasized UI elements. |
| Dark Violet | `#730394` | `--color-dark-violet` | Accent text, links within dark backgrounds, and subtle branding elements. |
| Deep Aubergine | `#3d0157` | `--color-deep-aubergine` | Text color for buttons with transparent backgrounds, emphasizing interaction. |
| Grape Jelly | `#2e0039` | `--color-grape-jelly` | Darkest brand shade, used for subtle backgrounds in branded sections. |
| Electric Blue | `#1264a3` | `--color-electric-blue` | Primary link color, secondary interactive elements, and highlight indicator for certain actions. |
| Orchid Glow | `#d17dfe` | `--color-orchid-glow` | Accent text and graphic elements, drawing attention in a playful manner. |
| Vivid Amethyst | `#9602c7` | `--color-vivid-amethyst` | Bright accent for special iconography or decorative elements. |
| Pale Orchid | `#eac8fe` | `--color-pale-orchid` | Light accent border for subtle interaction states. |
| Magic Dust Gradient | `linear-gradient(104deg, rgb(0, 0, 0) 9.56%, rgb(186, 1, 255) 102.66%)` | `--color-magic-dust-gradient` | Hero background gradient, creating a vibrant, dynamic backdrop for key messages. |
| Rainbow Wash Bottom Left (pink) | `radial-gradient(20vw at 10% 70%, rgba(255, 100, 150, 0.25), rgba(0, 0, 0, 0))` | `--color-rainbow-wash-bottom-left-pink` | Decorative radial gradient, contributing to the site's playful atmosphere, bottom-left emphasis. |
| Rainbow Wash Mid Left (blue) | `radial-gradient(20vw at 30% 70%, rgba(100, 150, 255, 0.25), rgba(0, 0, 0, 0))` | `--color-rainbow-wash-mid-left-blue` | Decorative radial gradient, contributing to the site's playful atmosphere, mid-left emphasis. |
| Rainbow Wash Mid Right (green) | `radial-gradient(20vw at 65% 70%, rgba(100, 255, 150, 0.25), rgba(0, 0, 0, 0))` | `--color-rainbow-wash-mid-right-green` | Decorative radial gradient, contributing to the site's playful atmosphere, mid-right emphasis. |
| Rainbow Wash Bottom Right (yellow) | `radial-gradient(20vw at 90% 70%, rgba(255, 255, 100, 0.25), rgba(0, 0, 0, 0))` | `--color-rainbow-wash-bottom-right-yellow` | Decorative radial gradient, contributing to the site's playful atmosphere, bottom-right emphasis. |
| Purple Aura Gradient | `linear-gradient(102deg, rgba(131, 56, 138, 0.8) 0%, rgba(211, 137, 231, 0.8) 100%)` | `--color-purple-aura-gradient` | Subtle background gradient for specific content blocks, adding a soft brand touch. |

## Tokens — Typography

### Salesforce-Sans — Used for all body text, navigation items, buttons, and detailed descriptive content, providing clarity and an approachable tone across all UI elements. · `--font-salesforce-sans`
- **Substitute:** Open Sans, Arial, sans-serif
- **Weights:** 300, 400, 600, 700
- **Sizes:** 12px, 14px, 15px, 16px, 18px
- **Line height:** 1.20, 1.29, 1.30, 1.38, 1.40, 1.43, 1.56
- **Letter spacing:** -0.004em, -0.002em, -0.001em, 0.007em, 0.012em, 0.013em, 0.057em
- **Role:** Used for all body text, navigation items, buttons, and detailed descriptive content, providing clarity and an approachable tone across all UI elements.

### Salesforce-Avant-Garde — Reserved for headlines and high-impact textual elements, where its distinctive character creates a strong brand presence and visual hierarchy. · `--font-salesforce-avant-garde`
- **Substitute:** Montserrat, Georgia, serif
- **Weights:** 400, 600, 700
- **Sizes:** 18px, 21px, 22px, 24px, 32px, 50px, 58px, 64px, 76px, 96px
- **Line height:** 0.97, 1.00, 1.08, 1.11, 1.12, 1.20, 1.25, 1.33, 1.50
- **Letter spacing:** -0.012em, -0.008em, -0.004em, -0.001em
- **Role:** Reserved for headlines and high-impact textual elements, where its distinctive character creates a strong brand presence and visual hierarchy.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.057px | `--text-caption` |
| body-sm | 14px | 1.29 | 0.013px | `--text-body-sm` |
| body | 16px | 1.3 | 0.007px | `--text-body` |
| subheading | 18px | 1.4 | -0.002px | `--text-subheading` |
| heading-sm | 22px | 1.08 | -0.001px | `--text-heading-sm` |
| heading | 32px | 1.12 | -0.004px | `--text-heading` |
| heading-lg | 58px | 1 | -0.008px | `--text-heading-lg` |
| display | 96px | 0.97 | -0.012px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 18 | 18px | `--spacing-18` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 98 | 98px | `--spacing-98` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| pills | 90px |
| inputs | 4px |
| buttons | 4px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 0px 0px 32px 0px` | `--shadow-xl` |
| subtle | `rgb(97, 31, 105) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| lg | `rgba(0, 0, 0, 0.1) 0px 5px 20px 0px` | `--shadow-lg` |

### Layout

- **Section gap:** 98px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action

Solid Purple Heart (#611f69) background with white (#ffffff) text. Padding: 19px vertical, 40px horizontal. Border radius: 4px. Features a subtle inset shadow by rgb(97, 31, 105) for depth.

### Ghost Button
**Role:** Secondary action

Transparent background with Deep Aubergine (#3d0157) text. Padding: 12px circular. Border radius: 90px (pill shape). No border. Used for 'Find your plan' and other secondary CTAs.

### Navigation Link
**Role:** Navigation, in-text link

Default text is Pewter (#696969) or Charcoal Black (#000000). Hover state uses Electric Blue (#1264a3) for text. No specific padding or border, inherits from layout.

### Text Only Button
**Role:** Utility action

Transparent background, Charcoal Black (#000000) text (color: rgb(0, 0, 0)). Padding: 0px. Border radius: 4px. Used for subtle actions like 'Skip to main content'.

### Content Card
**Role:** Information display

Surface Frost (#ffffff) background. Border radius: 16px. Padding: 16px. No box shadow in most contexts.

### Hero Section Gradient Background
**Role:** Thematic background

Uses Magic Dust Gradient (linear-gradient(104deg, rgb(0, 0, 0) 9.56%, rgb(186, 1, 255) 102.66%)) for a dynamic backdrop. Contains various radial gradients for additional visual flair.

### Trusted By Logo Grid
**Role:** Social proof

Logos displayed against the Canvas Ice (#fefbff) background. Uses a subtle box-shadow: rgba(0, 0, 0, 0.1) 0px 0px 32px 0px for some elements.

### Annoucement Banner
**Role:** Global alert

Top-most banner with Deep Aubergine (#3d0157) or similar dark purple background and white text. Height 40-80px. Used for site-wide messages like 'Meet the new Slack, where AI works.'

### Tab Navigation Item
**Role:** Content filtering

Transparent button with Pewter (#696969) text. Active state might have an Orchid Glow (#d17dfe) or Purple Heart (#611f69) accent, defined by context (e.g., underlines or background fills). Padding approximately 10px vertical, 30px horizontal, with 0px radius.

## Do's and Don'ts

### Do
- Prioritize Salesforce-Avant-Garde for all headings and large display text to maintain brand voice.
- Use Purple Heart (#611f69) for primary call-to-action buttons, ensuring a visible contrast against white or near-white backgrounds.
- Apply a 4px `border-radius` to all functional buttons and input fields for a consistent interactive element shape.
- Use Charcoal Black (#000000) for primary body text and headings on light backgrounds to ensure AAA contrast.
- Utilize Electric Blue (#1264a3) exclusively for interactive links and secondary accents, reserving it for clear action points.
- Maintain a comfortable `elementGap` of 16px for spacing between most UI elements, and `cardPadding` of 16px for internal card content.
- Implement the Magic Dust Gradient (linear-gradient(104deg, rgb(0, 0, 0) 9.56%, rgb(186, 1, 255) 102.66%)) sparingly, typically for hero sections or significant brand statements.

### Don't
- Do not use generic system fonts; always map to Salesforce-Sans or Salesforce-Avant-Garde with appropriate substitutes.
- Avoid using multiple shades of purple for primary actions; stick to Purple Heart (#611f69) for consistency.
- Do not introduce sharp corners; maintain 4px or 16px `border-radius` based on component type, or 90px for pill shapes.
- Refrain from using Electric Blue (#1264a3) for large blocks of text; it is an accent and link color, not a primary text color.
- Do not neglect the subtle radial gradients in hero backgrounds; they contribute significantly to the playful brand feel.
- Avoid arbitrary elevation shadows; use the defined `rgba(0, 0, 0, 0.1) 0px 0px 32px 0px` for elevated elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Ice | `#fefbff` | Base page background or main content area. |
| 1 | Surface Frost | `#ffffff` | Standard interactive cards, elevated containers on the Canvas Ice background. |
| 2 | Whisper Cloud | `#f9f0ff` | Very light hover states, subtle background accents, or contained UI elements slightly raised from Surface Frost. |

## Elevation

- **Card Shadow:** `rgba(0, 0, 0, 0.1) 0px 0px 32px 0px`
- **Button Inset Focus/Highlight:** `rgb(97, 31, 105) 0px 0px 0px 1px inset`
- **Subtle Button Shadow:** `rgba(0, 0, 0, 0.1) 0px 5px 20px 0px`

## Imagery

Imagery on Slack's site predominantly features product screenshots and abstract graphic elements. Product screenshots are typically contained within device mocks or UI frames, often showcasing the Slack interface with examples of AI integration. Abstract graphics include geometric shapes, sparkling effects, and subtle background gradients like the radial washes, used decoratively to add dynamism and a playful vibe. Icons are outlined, simple, and mono-color, often using the brand's purple or accent blue. Photography is minimal, appearing mostly for social proof with small headshots. The imagery serves primarily to illustrate product functionality and create an aspirational, slightly whimsical brand atmosphere, rather than purely decorative content.

## Layout

The page primarily uses a max-width contained layout, though specific hero sections and decorative gradients (like the radial washes) span full viewport width. The hero section often features a centered headline over a dark, gradient background. Subsequent content sections typically alternate between clean white and light off-white bands, creating a visible rhythm. Content is arranged in alternating text-left/image-right or text-right/image-left patterns, or organized into multi-column card grids for features. Vertical spacing between sections is generous and consistent. The top navigation bar is sticky and features a fixed width, centered content, with a clear brand logo on the left and primary actions (sign-in, get started) on the right.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #000000
- Background (Canvas): #fefbff
- CTA (Primary): #611f69
- Links/Accent: #1264a3
- Borders (Subtle): #edeaed

### 3-5 Example Component Prompts
1. Create a Hero Section: Background uses `Magic Dust Gradient`. Headline text `All your people and AI agents working together.` with `display` role, `Charcoal Black` color. Subtext `Slack connects your team. Slackbot multiplies what they can do.` with `body` role, `Pewter` color. Include two buttons: filled `Primary Filled Button` (text `Get Started`) and ghost `Ghost Button` (text `Find your plan`).
2. Create a Feature Card: Background `Surface Frost`. Border radius `cards`. Padding `cardPadding`. Heading `Meet Slackbot` using `Salesforce-Sans` weight 700 at 22px, `Charcoal Black`. Body text `Slack isn't just any AI...` using `body` role, `Pewter`. Include a link `Learn more about Slackbot` using `Electric Blue`.
3. Create a Primary Navigation Bar: Background `Surface Frost`. Height 80px. Left-aligned Slack logo (SVG color `Dark Plum`). Right-aligned `Primary Filled Button` (`Get started`) and `Ghost Button` (`Request a demo`). Navigation links use `Salesforce-Sans` weight 400 at 16px, `Pewter` color, with `Electric Blue` on hover.

## Similar Brands

- **Airtable** — Shares a clean, light UI with vibrant accent colors against a predominantly white background, and a unique, expressive custom sans-serif typography.
- **Figma** — Known for a balance of functional, bright UI elements and playful, often abstract background gradients and illustrations that enhance the user experience.
- **Notion** — Employs a minimal, functional design with a clear hierarchy and subtle use of color for interaction states and specific UI elements, similar to Slack's clean content presentation.
- **Discord** — Utilizes a strong brand purple as its primary identifying color, alongside a clean interface and a combination of functional and illustrative graphics, though with a darker default theme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #fefbff;
  --color-surface-frost: #ffffff;
  --color-whisper-cloud: #f9f0ff;
  --color-active-lavender: #f2defe;
  --color-charcoal-black: #000000;
  --color-carbon-gray: #1d1c1d;
  --color-pewter: #696969;
  --color-cement-gray: #757575;
  --color-slate-border: #edeaed;
  --color-medium-gray: #808080;
  --color-icon-gray: #5e5d60;
  --color-dark-plum: #481a54;
  --color-purple-heart: #611f69;
  --color-dark-violet: #730394;
  --color-deep-aubergine: #3d0157;
  --color-grape-jelly: #2e0039;
  --color-electric-blue: #1264a3;
  --color-orchid-glow: #d17dfe;
  --color-vivid-amethyst: #9602c7;
  --color-pale-orchid: #eac8fe;
  --color-magic-dust-gradient: #000000;
  --gradient-magic-dust-gradient: linear-gradient(104deg, rgb(0, 0, 0) 9.56%, rgb(186, 1, 255) 102.66%);
  --color-rainbow-wash-bottom-left-pink: #ff6496;
  --gradient-rainbow-wash-bottom-left-pink: radial-gradient(20vw at 10% 70%, rgba(255, 100, 150, 0.25), rgba(0, 0, 0, 0));
  --color-rainbow-wash-mid-left-blue: #6496ff;
  --gradient-rainbow-wash-mid-left-blue: radial-gradient(20vw at 30% 70%, rgba(100, 150, 255, 0.25), rgba(0, 0, 0, 0));
  --color-rainbow-wash-mid-right-green: #64ff96;
  --gradient-rainbow-wash-mid-right-green: radial-gradient(20vw at 65% 70%, rgba(100, 255, 150, 0.25), rgba(0, 0, 0, 0));
  --color-rainbow-wash-bottom-right-yellow: #ffff64;
  --gradient-rainbow-wash-bottom-right-yellow: radial-gradient(20vw at 90% 70%, rgba(255, 255, 100, 0.25), rgba(0, 0, 0, 0));
  --color-purple-aura-gradient: #83388a;
  --gradient-purple-aura-gradient: linear-gradient(102deg, rgba(131, 56, 138, 0.8) 0%, rgba(211, 137, 231, 0.8) 100%);

  /* Typography — Font Families */
  --font-salesforce-sans: 'Salesforce-Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-salesforce-avant-garde: 'Salesforce-Avant-Garde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.057px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --tracking-body-sm: 0.013px;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: 0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.002px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.08;
  --tracking-heading-sm: -0.001px;
  --text-heading: 32px;
  --leading-heading: 1.12;
  --tracking-heading: -0.004px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.008px;
  --text-display: 96px;
  --leading-display: 0.97;
  --tracking-display: -0.012px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-98: 98px;

  /* Layout */
  --section-gap: 98px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 48px;
  --radius-full-2: 60px;
  --radius-full-3: 90px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-pills: 90px;
  --radius-inputs: 4px;
  --radius-buttons: 4px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 0px 32px 0px;
  --shadow-subtle: rgb(97, 31, 105) 0px 0px 0px 1px inset;
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 5px 20px 0px;

  /* Surfaces */
  --surface-canvas-ice: #fefbff;
  --surface-surface-frost: #ffffff;
  --surface-whisper-cloud: #f9f0ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #fefbff;
  --color-surface-frost: #ffffff;
  --color-whisper-cloud: #f9f0ff;
  --color-active-lavender: #f2defe;
  --color-charcoal-black: #000000;
  --color-carbon-gray: #1d1c1d;
  --color-pewter: #696969;
  --color-cement-gray: #757575;
  --color-slate-border: #edeaed;
  --color-medium-gray: #808080;
  --color-icon-gray: #5e5d60;
  --color-dark-plum: #481a54;
  --color-purple-heart: #611f69;
  --color-dark-violet: #730394;
  --color-deep-aubergine: #3d0157;
  --color-grape-jelly: #2e0039;
  --color-electric-blue: #1264a3;
  --color-orchid-glow: #d17dfe;
  --color-vivid-amethyst: #9602c7;
  --color-pale-orchid: #eac8fe;
  --color-magic-dust-gradient: #000000;
  --color-rainbow-wash-bottom-left-pink: #ff6496;
  --color-rainbow-wash-mid-left-blue: #6496ff;
  --color-rainbow-wash-mid-right-green: #64ff96;
  --color-rainbow-wash-bottom-right-yellow: #ffff64;
  --color-purple-aura-gradient: #83388a;

  /* Typography */
  --font-salesforce-sans: 'Salesforce-Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-salesforce-avant-garde: 'Salesforce-Avant-Garde', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.057px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.29;
  --tracking-body-sm: 0.013px;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: 0.007px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.002px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.08;
  --tracking-heading-sm: -0.001px;
  --text-heading: 32px;
  --leading-heading: 1.12;
  --tracking-heading: -0.004px;
  --text-heading-lg: 58px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.008px;
  --text-display: 96px;
  --leading-display: 0.97;
  --tracking-display: -0.012px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-18: 18px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-98: 98px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-full: 48px;
  --radius-full-2: 60px;
  --radius-full-3: 90px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 0px 32px 0px;
  --shadow-subtle: rgb(97, 31, 105) 0px 0px 0px 1px inset;
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 5px 20px 0px;
}
```
