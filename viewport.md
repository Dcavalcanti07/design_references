# Viewport — Style Reference
> Crisp digital canvas

**Theme:** light

Viewport is a bright, clear digital workspace, using a predominantly achromatic palette accented by vivid blue and a soft, muted teal. The typography combines a modern sans-serif for content with a distinctive display font for headlines, creating a friendly yet authoritative tone. Surfaces are layered with subtle elevation and soft rounded corners, giving components a lightweight, approachable feel. Color is used sparingly to highlight primary actions and create a sense of focused energy.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Ink Black | `#000000` | `--color-ink-black` | Primary headings, body text, general UI elements |
| Cloud Gray | `#f8f9fa` | `--color-cloud-gray` | Subtle surface accents, secondary card backgrounds |
| Stone Gray | `#e3e6ec` | `--color-stone-gray` | Tertiary card backgrounds, elevated sections |
| Ash Gray | `#c8c9cf` | `--color-ash-gray` | Muted text, body text secondary color |
| Midnight Graphite | `#333333` | `--color-midnight-graphite` | Stronger secondary headings, dense body text |
| Muted Silver | `#7f8087` | `--color-muted-silver` | Helper text, link text, borders, small print |
| Frost Teal | `#c5fbee` | `--color-frost-teal` | Muted section backgrounds, soft card fills – provides quiet visual separation |
| Viewport Violet | `#4d4dff` | `--color-viewport-violet` | Primary action backgrounds, interactive states, brand accent for headlines – a vivid, energetic touch against the neutral palette |
| Aqua Glow | `#66dff7` | `--color-aqua-glow` | Blue supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Alert Red | `#ff5656` | `--color-alert-red` | Red wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Linear Gradient Violet to Aqua | `linear-gradient(0deg, rgb(0, 202, 242) 0%, rgb(77, 77, 255) 173.214%)` | `--color-linear-gradient-violet-to-aqua` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Radial Gradient Aqua Soft | `radial-gradient(102% 82% at 50% 107.7%, rgba(0, 202, 242, 0.3) 0%, rgb(241, 243, 245) 100%)` | `--color-radial-gradient-aqua-soft` | Subtle background overlay for focus or elevation, creates a light radial highlight |

## Tokens — Typography

### Silka Medium Italic — Silka Medium Italic — detected in extracted data but not described by AI · `--font-silka-medium-italic`
- **Weights:** 400
- **Sizes:** 18px
- **Line height:** 1.2
- **Letter spacing:** 0.01
- **Role:** Silka Medium Italic — detected in extracted data but not described by AI

### HK Sentiments Bold — Primary brand headlines. This decorative serif font adds a distinct, creative touch, balancing the technical precision of the sans-serif components with a welcoming character. · `--font-hk-sentiments-bold`
- **Substitute:** Georgia
- **Weights:** 400, 700
- **Sizes:** 24px, 28px, 32px
- **Line height:** 1.10, 1.20
- **Letter spacing:** -0.018em, -0.017em, -0.006em
- **Role:** Primary brand headlines. This decorative serif font adds a distinct, creative touch, balancing the technical precision of the sans-serif components with a welcoming character.

### Silka — Body text and links. The Regular weight provides a straightforward, highly readable foundation for all content. · `--font-silka`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 14px, 16px, 18px
- **Line height:** 1.00, 1.20, 1.30
- **Letter spacing:** 0.010em
- **Role:** Body text and links. The Regular weight provides a straightforward, highly readable foundation for all content.

### Silka — Secondary headings, subheadings, and emphasized body text. The Medium weight brings a subtle level of prominence without being overtly bold. · `--font-silka`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 14px, 16px, 18px
- **Line height:** 1.00, 1.20
- **Letter spacing:** -0.011em
- **Role:** Secondary headings, subheadings, and emphasized body text. The Medium weight brings a subtle level of prominence without being overtly bold.

### Silka — Strong emphasis, button labels, and navigation items. The SemiBold weight provides clear hierarchy and makes interactive elements stand out. · `--font-silka`
- **Substitute:** Inter
- **Weights:** 400, 600, 700
- **Sizes:** 14px, 16px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** -0.036em
- **Role:** Strong emphasis, button labels, and navigation items. The SemiBold weight provides clear hierarchy and makes interactive elements stand out.

### System Sans-serif — Utility text, metadata, and labels. Defaults to simple, system-level readability for non-critical information. · `--font-system-sans-serif`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Utility text, metadata, and labels. Defaults to simple, system-level readability for non-critical information.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1 | -0.154px | `--text-body-sm` |
| body | 16px | 1.2 | -0.576px | `--text-body` |
| subheading | 18px | 1.2 | -0.198px | `--text-subheading` |
| heading | 24px | 1.1 | -0.432px | `--text-heading` |
| heading-lg | 28px | 1.2 | -0.476px | `--text-heading-lg` |
| display | 32px | 1.2 | -0.192px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| pills | 100px |
| buttons | 12px |
| controls | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 202, 242, 0.6) 0px 4px 12px 0px` | `--shadow-md` |
| md-2 | `rgba(0, 0, 0, 0.25) 0px 8px 16px 0px` | `--shadow-md-2` |
| lg | `rgba(0, 0, 0, 0.1) 0px 15px 20px -5px` | `--shadow-lg` |

### Layout

- **Section gap:** 40px
- **Card padding:** 24px
- **Element gap:** 12px

## Components

### Primary Filled Button
**Role:** Call to action with full visual emphasis

Background: Viewport Violet (#4d4dff), Text: Canvas White (#ffffff), Border Radius: 12px, Padding: 12px 16px. Typography: Silka SemiBold, 16px.

### Ghost Button
**Role:** Secondary action or navigation link with minimal visual weight

Background: transparent, Text: Muted Silver (#7f8087), Border: 1px solid Muted Silver (#7f8087) on hover/focus, Border Radius: 12px, Padding: 12px 16px. Typography: Silka SemiBold, 16px.

### Navigation Link
**Role:** Tertiary navigation or inline links

Text: Muted Silver (#7f8087), no background, no border. On hover, text becomes Viewport Violet (#4d4dff). Typography: Silka Medium, 14px.

### Feature Card (Default)
**Role:** Container for content blocks, features information

Background: Canvas White (#ffffff), Border Radius: 16px, Padding: 24px, Shadow: rgba(0, 0, 0, 0.1) 0px 15px 20px -5px. Features rounded corners and soft elevation.

### Feature Card (Ambient)
**Role:** Container for content, with a subtle background color

Background: Frost Teal (#c5fbee), Border Radius: 16px, no shadow, no padding. Used for background visual interest.

### Feature Card (Stone)
**Role:** Subtle, slightly darker container for content blocks

Background: Stone Gray (#e3e6ec), Border Radius: 16px, no shadow, no padding. Used for visual separation when a darker neutral is needed.

### Input Field
**Role:** User input for forms

Background: Canvas White (#ffffff), Border: 1px solid Ash Gray (#c8c9cf) or Muted Silver (#7f8087), Border Radius: 8px, Padding: 10px 14px. On focus, border color becomes Viewport Violet (#4d4dff).

## Do's and Don'ts

### Do
- Use Viewport Violet (#4d4dff) exclusively for primary calls to action and critical interactive elements.
- Apply 16px border-radius to all main content cards and section containers for a consistently soft appearance.
- Employ HK Sentiments Bold for all display-level headings (24px and greater) to convey brand personality.
- Maintain an elementGap of 12px for consistent internal spacing between UI components.
- Use Muted Silver (#7f8087) for all subtle textual elements like captions, meta information, and secondary link text.
- Ensure all backgrounds like Canvas White (#ffffff) and Cloud Gray (#f8f9fa) remain pristine, without heavy shadows or complex textures.
- Utilize Frost Teal (#c5fbee) primarily for background sections or ambient card fills, not for interactive elements.

### Don't
- Do not use multiple chromatic colors for primary calls to action; only Viewport Violet (#4d4dff) should fulfill this role.
- Avoid sharp corners; never use radii less than 8px for interactive elements or less than 12px for primary cards.
- Do not apply drop shadows to text or static icons, reserving them for interactive elements or elevated cards.
- Never replace Silka typography with a generic serif font; the specific characterful serifs of HK Sentiments Bold are reserved for headings.
- Do not introduce strong, dark backgrounds unless they are clearly defined as a contained, specific section, maintaining the overall light theme.
- Avoid dense, information-heavy blocks of text; break content into manageable paragraphs with clear hierarchy using Silka weights.
- Do not use gradients from the brand palette for subtle background fills; reserve them for impactful hero sections or distinct product showcases.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #7f8087
accent: #c5fbee
primary action: #4d4dff (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #4d4dff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Canvas White background, 16px radius, padding 24px, subtle shadow rgba(0, 0, 0, 0.1) 0px 15px 20px -5px. Inside, place a heading 'Sharing creative work is messy' in Silka SemiBold, 16px, Ink Black (#000000), letter-spacing -0.576px, and body text 'and feels impossible to follow.' in Silka Regular, 14px, Muted Silver (#7f8087), letter-spacing 0.14px.
3. Create a secondary navigation link: 'Use cases' in Silka Medium, 14px, Muted Silver (#7f8087), letter-spacing -0.154px. On hover, change text color to Viewport Violet (#4d4dff).

## Similar Brands

- **Figma** — Clean, predominantly light interface with a focus on product visuals and a single vivid accent color for interactive elements.
- **Linear** — Structured, minimalist design with soft shadows and rounded corners on cards, using system-level typography for content clarity.
- **Notion** — Whitespace-driven layout, heavy reliance on grayscale neutrals for visual hierarchy, and subtle color accents for functional components.
- **Pitch** — Modern sans-serif typography paired with a distinctive display font for headlines, creating an approachable yet refined brand voice.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-cloud-gray: #f8f9fa;
  --color-stone-gray: #e3e6ec;
  --color-ash-gray: #c8c9cf;
  --color-midnight-graphite: #333333;
  --color-muted-silver: #7f8087;
  --color-frost-teal: #c5fbee;
  --color-viewport-violet: #4d4dff;
  --color-aqua-glow: #66dff7;
  --color-alert-red: #ff5656;
  --color-linear-gradient-violet-to-aqua: #00caf2;
  --gradient-linear-gradient-violet-to-aqua: linear-gradient(0deg, rgb(0, 202, 242) 0%, rgb(77, 77, 255) 173.214%);
  --color-radial-gradient-aqua-soft: #f1f3f5;
  --gradient-radial-gradient-aqua-soft: radial-gradient(102% 82% at 50% 107.7%, rgba(0, 202, 242, 0.3) 0%, rgb(241, 243, 245) 100%);

  /* Typography — Font Families */
  --font-silka-medium-italic: 'Silka Medium Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hk-sentiments-bold: 'HK Sentiments Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-silka: 'Silka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-sans-serif: 'System Sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --tracking-body-sm: -0.154px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.576px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.198px;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: -0.432px;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.476px;
  --text-display: 32px;
  --leading-display: 1.2;
  --tracking-display: -0.192px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 24px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-pills: 100px;
  --radius-buttons: 12px;
  --radius-controls: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 202, 242, 0.6) 0px 4px 12px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.25) 0px 8px 16px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 15px 20px -5px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-ink-black: #000000;
  --color-cloud-gray: #f8f9fa;
  --color-stone-gray: #e3e6ec;
  --color-ash-gray: #c8c9cf;
  --color-midnight-graphite: #333333;
  --color-muted-silver: #7f8087;
  --color-frost-teal: #c5fbee;
  --color-viewport-violet: #4d4dff;
  --color-aqua-glow: #66dff7;
  --color-alert-red: #ff5656;
  --color-linear-gradient-violet-to-aqua: #00caf2;
  --color-radial-gradient-aqua-soft: #f1f3f5;

  /* Typography */
  --font-silka-medium-italic: 'Silka Medium Italic', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-hk-sentiments-bold: 'HK Sentiments Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-silka: 'Silka', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-sans-serif: 'System Sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1;
  --tracking-body-sm: -0.154px;
  --text-body: 16px;
  --leading-body: 1.2;
  --tracking-body: -0.576px;
  --text-subheading: 18px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.198px;
  --text-heading: 24px;
  --leading-heading: 1.1;
  --tracking-heading: -0.432px;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.476px;
  --text-display: 32px;
  --leading-display: 1.2;
  --tracking-display: -0.192px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 202, 242, 0.6) 0px 4px 12px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.25) 0px 8px 16px 0px;
  --shadow-lg: rgba(0, 0, 0, 0.1) 0px 15px 20px -5px;
}
```
