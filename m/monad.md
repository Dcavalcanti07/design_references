# Monad — Style Reference
> Softly lit control panel

**Theme:** light

Monad employs a high-contrast, minimalist design with a soft, almost ephemeral quality achieved through understated typography and subtle, diffused gradients. The color palette is predominantly achromatic, allowing a single soft blue-gray wash to introduce a hint of color, primarily in background elements. Components generally favor soft curves and thin borders over heavy fills, maintaining an open, airy feel. The overall impression is one of clarity and focused information delivery, avoiding visual noise.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ink | `#000000` | `--color-ink` | Primary text, primary icon, strong borders, dark surface backgrounds |
| Paper Canvas | `#f6f3f1` | `--color-paper-canvas` | Page backgrounds, card backgrounds, light element borders |
| Off-Black | `#242424` | `--color-off-black` | Secondary text, button backgrounds, accent borders for ghost elements, navigation text |
| Pale Stone | `#4e4d4d` | `--color-pale-stone` | Muted body text, secondary heading text, subtle borders |
| Whisper Gray | `#3d3d3d` | `--color-whisper-gray` | Decorative lines, subtle text elements |
| Atmosphere Wash | `#cfdaf5` | `--color-atmosphere-wash` | Soft card backgrounds, decorative background fills – provides a cool, airy presence |
| Subtle Link | `#333333` | `--color-subtle-link` | Understated link text and associated borders |
| Faint Text | `#797776` | `--color-faint-text` | Tertiary text or secondary link text for reduced emphasis |
| Sunset Violet gradient | `linear-gradient(rgba(255, 148, 115, 0.8) 7%, rgba(160, 181, 235, 0.8) 83.82%)` | `--color-sunset-violet-gradient` | Decorative visual element; evokes warmth and transition. Primary hue is a soft orange |
| Sky Mint Gradient | `linear-gradient(rgb(160, 181, 235), rgb(167, 252, 205))` | `--color-sky-mint-gradient` | Decorative visual element; suggests freshness and clarity. Primary hue is a soft blue |
| Amber Glow Gradient | `linear-gradient(270deg, rgba(226, 193, 97, 0.7) 23.5%, rgba(243, 122, 10, 0.7) 76%)` | `--color-amber-glow-gradient` | Decorative visual element; adds a bright and energetic accent. Primary hue is a soft yellow |

## Tokens — Typography

### ABC Diatype Mono — Primary UI font for all interactive elements, body text, and monospaced content. Its fixed-width character evokes precision and technicality, while its range of tracking values allows for both compact and airy presentations. · `--font-abc-diatype-mono`
- **Substitute:** IBM Plex Mono
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 28px
- **Line height:** 1.00, 1.20, 1.30, 1.35
- **Letter spacing:** -0.0330em, -0.0250em, -0.0220em, -0.0200em, -0.0140em, 0.0500em
- **Role:** Primary UI font for all interactive elements, body text, and monospaced content. Its fixed-width character evokes precision and technicality, while its range of tracking values allows for both compact and airy presentations.

### Untitled Serif — Display and section headings. The serif typeface provides a touch of classic authority, contrasting subtly with the monospace UI elements, and its specific negative letter-spacing contributes to its restrained, sophisticated presence. · `--font-untitled-serif`
- **Substitute:** Noto Serif
- **Weights:** 400
- **Sizes:** 24px, 28px, 32px, 40px, 80px
- **Line height:** 1.20
- **Letter spacing:** -0.0200em
- **Role:** Display and section headings. The serif typeface provides a touch of classic authority, contrasting subtly with the monospace UI elements, and its specific negative letter-spacing contributes to its restrained, sophisticated presence.

### Untitled Sans — Used for specific body text instances, acting as a clean, highly readable alternative to the monospace text for longer content blocks. Its tight letter-spacing ensures a compact feel. · `--font-untitled-sans`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.35
- **Letter spacing:** -0.0200em
- **Role:** Used for specific body text instances, acting as a clean, highly readable alternative to the monospace text for longer content blocks. Its tight letter-spacing ensures a compact feel.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.35 | 0.05px | `--text-caption` |
| body-sm | 14px | 1.3 | -0.014px | `--text-body-sm` |
| body | 16px | 1.35 | -0.02px | `--text-body` |
| subheading | 20px | 1.2 | -0.02px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.02px | `--text-heading-sm` |
| heading | 28px | 1.2 | -0.02px | `--text-heading` |
| heading-lg | 40px | 1.2 | -0.02px | `--text-heading-lg` |
| display | 80px | 1.2 | -0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 200 | 200px | `--spacing-200` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 2000px |
| cards | 40px |
| other | 100px |
| buttons | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.1) 0px 0px 10px 0px` | `--shadow-md` |

### Layout

- **Page max-width:** 1432px
- **Section gap:** 40px
- **Card padding:** 40px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call-to-action button for initiating primary actions.

Background: 'Off-Black' (#242424), Text: 'Paper Canvas' (#f6f3f1). Padding: 16px horizontal, 16px vertical. Radius: 100px. Uses ABC Diatype Mono, weight 400.

### Secondary Ghost Button
**Role:** Call-to-action button for secondary actions.

Background: transparent. Border: 1px solid 'Off-Black' (#242424). Text: 'Off-Black' (#242424). Padding: 16px horizontal, 16px vertical. Radius: 100px. Uses ABC Diatype Mono, weight 400.

### Inline Text Link
**Role:** Navigational or contextual links within body text.

Text: 'Ink' (#000000) or 'Subtle Link' (#333333). Padding: 5px horizontal. No border or background. Uses ABC Diatype Mono.

### Hero Headline
**Role:** Prominent display text for main page sections.

Text: 'Ink' (#000000). Font: Untitled Serif, weight 400, size 80px, lineHeight 1.2, letterSpacing -0.0200em.

### Feature Card
**Role:** Container for showcasing features or information blocks.

Background: 'Atmosphere Wash' (#cfdaf5). Border-radius: 40px. Padding: 40px. No explicit shadow, relies on background color differentiation.

### Navigation Item
**Role:** Top navigation links.

Text: 'Off-Black' (#242424). Underlined on hover with 'Off-Black'. Uses ABC Diatype Mono. Padding: 8px vertical, 10px horizontal.

### Notification Bar
**Role:** Top-level information banner.

Background: 'Ink' (#000000). Text: 'Paper Canvas' (#f6f3f1). Button text: 'Paper Canvas' (#f6f3f1), button border: 'Paper Canvas' (#f6f3f1). Font: ABC Diatype Mono, size 14px.

### FAQ Accordion Item
**Role:** Interactive question and answer section.

Background: transparent. Border-bottom: 1px solid 'Pale Stone' (#4e4d4d). Text: 'Ink' (#000000) or 'Pale Stone' (#4e4d4d). Font: ABC Diatype Mono, weight 400.

### Diagram Node Tag
**Role:** Small, descriptive labels within visual diagrams.

Background: transparent. Border: 1px solid 'Ink' (#000000) or 'Off-Black' (#242424) or 'Faint Text' (#797776). Text: matching border color. Radius: 2000px (pill shape). Font: ABC Diatype Mono, size 12px, letterSpacing 0.0500em.

## Do's and Don'ts

### Do
- Prioritize 'ABC Diatype Mono' for all UI elements and body text to maintain the brand's precision-oriented voice.
- Use 'Untitled Serif' exclusively for primary section headings and display text to establish visual hierarchy and gravitas.
- Apply 'Ink' (#000000) for all primary text and critical interactive elements, ensuring high contrast against light backgrounds.
- Employ 'Paper Canvas' (#f6f3f1) as the default background for general page content and 'Atmosphere Wash' (#cfdaf5) for subtle visual differentiation on cards or specific content blocks.
- Ensure all buttons have a 100px border-radius, creating a consistent 'pill' shape.
- Utilize a minimal 1px border for ghost buttons and tags, defaulting to 'Off-Black' (#242424) or 'Ink' (#000000) for definition.
- Maintain 40px of internal padding for cards and primary CTAs to create generous breathing room.

### Don't
- Avoid using bright, saturated colors for primary UI elements; reserve them strictly for decorative gradients or illustrations and only as an accent.
- Do not introduce sharp corners into interactive elements or cards; all elements should adhere to the established radii of 40px, 100px, or 2000px.
- Do not use heavy shadows or gradients on interactive elements; rely on color contrast and subtle borders for distinction.
- Refrain from using multiple font families beyond the defined 'ABC Diatype Mono', 'Untitled Serif', and 'Untitled Sans'.
- Do not deviate from the specified letter-spacing for headings; the negative tracking is a signature visual characteristic.
- Avoid dense or cluttered layouts; prioritize ample whitespace and consistent section gaps (40px) to maintain clarity.
- Do not use dark backgrounds for sections without explicit reasoning; maintain the dominant light theme.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Paper Canvas | `#f6f3f1` | Base page background |
| 1 | Atmosphere Wash | `#cfdaf5` | Elevated card and section backgrounds |
| 2 | Off-Black | `#242424` | Primary filled button backgrounds, dark UI elements |
| 3 | Ink | `#000000` | Top-level notification bar, highest contrast elements |

## Elevation

- **Floating Elements / Popovers:** `rgba(0, 0, 0, 0.1) 0px 0px 10px 0px`

## Imagery

This site features abstract, somewhat ethereal illustrations and small product-like diagrams rather than photography. Illustrations are colorful, often incorporating linear gradients, and appear contained within sections as decorative elements or to explain concepts. Icons are outlined, fine-lined, and predominantly 'Ink' (#000000) or 'Pale Stone' (#4e4d4d), used minimally for functionality rather than decoration. Imagery is used to provide visual breathing room and metaphoric explanation, not direct product showcase or social proof, and keeps a relatively low density on the page.

## Layout

The page uses a contained layout with a maximum width of 1432px, centered for content. The hero section features a centered headline and subtext over whitespace, followed by primary and secondary call-to-action buttons. Sections maintain a consistent vertical rhythm with 40px section gaps. Content is arranged in alternating patterns, typically featuring text on one side and a visual element or card on the other, or stacked elements for FAQs. Navigation is a sticky top bar with left-aligned branding and right-aligned actions, featuring a distinct black notification bar above it. Overall density is comfortable and spacious.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #f6f3f1
border: #242424
accent: #cfdaf5
primary action: no distinct CTA color

Example Component Prompts:

1. Create a Hero Section with a primary headline: 'Security Data Pipelines, Made Easy' using Untitled Serif weight 400, 80px, #000000, letter-spacing -0.0200em. Below it, a monochromatic filled button 'Get Started' with background #242424, text #f6f3f1, 100px radius, 16px vertical padding, 16px horizontal padding, using ABC Diatype Mono 400.

2. Design a Feature Card for 'Managed Data Pipelines'. Background #cfdaf5, border-radius 40px, internal padding 40px. The feature title 'Managed Data Pipelines' uses ABC Diatype Mono weight 500, 20px, #000000. Underneath, a short description 'Connect any security tool in minutes...' uses ABC Diatype Mono weight 400, 16px, #4e4d4d.

3. Construct a Navigation Bar. Background #f6f3f1. On the left, brand logo. On the right, a ghost button link 'Get A Demo >' with text #242424, a 1px border #242424, 100px radius, 16px vertical padding, 16px horizontal padding. Other navigation links like 'Platform' use ABC Diatype Mono weight 400, 16px, #242424, with no background or border.

## Similar Brands

- **Linear** — High-contrast monochrome interface with a single accent color, sharp typographic choices, and clean, functional component design.
- **Vercel** — Prominent use of monospace typography in UI, minimalist layout, and focus on subtle shading/gradients for visual interest rather than heavy colors.
- **Stripe** — Clear information hierarchy, restrained use of color, and emphasis on elegant typography, especially for headings and body text.
- **Figma** — Dominant white/light backgrounds, emphasis on clean, functional UI components, and subtle use of color for interactive states and accents.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ink: #000000;
  --color-paper-canvas: #f6f3f1;
  --color-off-black: #242424;
  --color-pale-stone: #4e4d4d;
  --color-whisper-gray: #3d3d3d;
  --color-atmosphere-wash: #cfdaf5;
  --color-subtle-link: #333333;
  --color-faint-text: #797776;
  --color-sunset-violet-gradient: #ffa773;
  --gradient-sunset-violet-gradient: linear-gradient(rgba(255, 148, 115, 0.8) 7%, rgba(160, 181, 235, 0.8) 83.82%);
  --color-sky-mint-gradient: #a0b5eb;
  --gradient-sky-mint-gradient: linear-gradient(rgb(160, 181, 235), rgb(167, 252, 205));
  --color-amber-glow-gradient: #e2c161;
  --gradient-amber-glow-gradient: linear-gradient(270deg, rgba(226, 193, 97, 0.7) 23.5%, rgba(243, 122, 10, 0.7) 76%);

  /* Typography — Font Families */
  --font-abc-diatype-mono: 'ABC Diatype Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-untitled-serif: 'Untitled Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-untitled-sans: 'Untitled Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.35;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --tracking-body-sm: -0.014px;
  --text-body: 16px;
  --leading-body: 1.35;
  --tracking-body: -0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.02px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.02px;
  --text-display: 80px;
  --leading-display: 1.2;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-200: 200px;
  --spacing-216: 216px;

  /* Layout */
  --page-max-width: 1432px;
  --section-gap: 40px;
  --card-padding: 40px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 100px;
  --radius-full-2: 2000px;

  /* Named Radii */
  --radius-tags: 2000px;
  --radius-cards: 40px;
  --radius-other: 100px;
  --radius-buttons: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 0px 10px 0px;

  /* Surfaces */
  --surface-paper-canvas: #f6f3f1;
  --surface-atmosphere-wash: #cfdaf5;
  --surface-off-black: #242424;
  --surface-ink: #000000;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ink: #000000;
  --color-paper-canvas: #f6f3f1;
  --color-off-black: #242424;
  --color-pale-stone: #4e4d4d;
  --color-whisper-gray: #3d3d3d;
  --color-atmosphere-wash: #cfdaf5;
  --color-subtle-link: #333333;
  --color-faint-text: #797776;
  --color-sunset-violet-gradient: #ffa773;
  --color-sky-mint-gradient: #a0b5eb;
  --color-amber-glow-gradient: #e2c161;

  /* Typography */
  --font-abc-diatype-mono: 'ABC Diatype Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-untitled-serif: 'Untitled Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-untitled-sans: 'Untitled Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.35;
  --tracking-caption: 0.05px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.3;
  --tracking-body-sm: -0.014px;
  --text-body: 16px;
  --leading-body: 1.35;
  --tracking-body: -0.02px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.2;
  --tracking-heading: -0.02px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.02px;
  --text-display: 80px;
  --leading-display: 1.2;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-200: 200px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-3xl: 40px;
  --radius-full: 100px;
  --radius-full-2: 2000px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 0px 10px 0px;
}
```
