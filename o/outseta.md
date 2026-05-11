# Outseta — Style Reference
> Gradient-infused SaaS canvas

**Theme:** light

Outseta employs a vibrant, confident design aesthetic, blending a clean white canvas with rich, dark purples and an energetic pink accent. Gradients are strategically used to create depth and visual interest in key areas like the hero section, while components maintain a crisp, contained feel with subtle shadows. Typography uses a mix of sharp, modern sans-serifs and a playful hand-drawn font to balance professionalism with approachability, making the SaaS product feel both robust and inviting. The overall impression is one of modern vitality and clear functionality.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, form input backgrounds, primary text for some inverted sections |
| Midnight Plum | `linear-gradient(145deg, rgb(255, 189, 211), rgb(255, 241, 189) 40%, rgb(255, 241, 189) 60%, rgb(255, 203, 15))` | `--color-midnight-plum` | Primary text, significant borders, dark card backgrounds in inverted sections, active navigation states. This deep, almost-black purple forms the foundational dark tone; Hero section background, footer background, with a rich purple-yellow gradient overlay |
| Whisper Gray | `#d4ccd4` | `--color-whisper-gray` | Subtle borders, button outlines, muted text accents, light box shadows for elements |
| Input Border Gray | `#767676` | `--color-input-border-gray` | Input field borders when not focused |
| Deep Plum Text | `#333333` | `--color-deep-plum-text` | Secondary text, faded link colors |
| Rose Bloom | `#df37a7` | `--color-rose-bloom` | Primary call-to-action button backgrounds, prominent headings, decorative elements. This vivid pink provides a strong point of action and brand identity |
| Muted Orchid | `#6d526d` | `--color-muted-orchid` | Ghost button text, subtle link borders, navigation item borders. A desaturated plum for restrained interactive elements |
| Sunshine Gold | `#ffcc11` | `--color-sunshine-gold` | Accent backgrounds in gradient heavy sections, card borders in featured content areas |
| Vivid Cobalt | `#635bff` | `--color-vivid-cobalt` | Decorative SVG fills and strokes. A strong, electric blue for illustrative elements |
| Deep Pink Accent | `#d0339c` | `--color-deep-pink-accent` | Decorative text styling and borders within prominent marketing sections. Slightly deeper than Rose Bloom |
| Sky Blue Accent | `#3898ec` | `--color-sky-blue-accent` | Decorative borders for specific UI elements, often for distinction |
| Success Green Text | `#15803d` | `--color-success-green-text` | Success state text, such as in status badges |
| Success Green Border | `#bbf7d0` | `--color-success-green-border` | Green outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |
| Success Green Background | `#dcfce7` | `--color-success-green-background` | Success state badge backgrounds |
| Faded Plum Accent | `#bbadbb` | `--color-faded-plum-accent` | Subtle borders and muted text, often in secondary explanatory content |
| Warning Red | `#ef4444` | `--color-warning-red` | Red outline accent for tags, dividers, and focused UI edges. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Inter Var — Primary UI text, body copy, navigation, buttons, and form labels. Its variable nature allows for precise control of visual density and hierarchy. · `--font-inter-var`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 20px, 24px, 36px
- **Line height:** 1.00, 1.20, 1.40, 1.43, 1.50
- **Letter spacing:** -0.0200em at 36px, -0.0130em at 24px, -0.0110em at 20px, -0.0100em at 16px, -0.0080em at 14px, -0.0070em at 12px, -0.0040em at 10px
- **OpenType features:** `"calt", "cv11", "ss02"; "ss03"`
- **Role:** Primary UI text, body copy, navigation, buttons, and form labels. Its variable nature allows for precise control of visual density and hierarchy.

### Kaio — Dominant display headlines. Its bold weight and tight tracking create a powerful, impactful statement while retaining legibility. · `--font-kaio`
- **Substitute:** sans-serif
- **Weights:** 700
- **Sizes:** 36px, 56px, 80px
- **Line height:** 1.00, 1.10, 1.20
- **Letter spacing:** -0.0200em at 80px, -0.0040em at 36px
- **OpenType features:** `"ss03"; "calt", "cv11", "ss02"`
- **Role:** Dominant display headlines. Its bold weight and tight tracking create a powerful, impactful statement while retaining legibility.

### Jetbrains Mono — Code snippets, technical labels, and specialized data displays, providing a clear, fixed-width appearance. · `--font-jetbrains-mono`
- **Substitute:** monospace
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px
- **Line height:** 1.20, 1.50
- **Letter spacing:** 0.0400em at 16px, 0.1000em at 12px
- **OpenType features:** `"calt", "cv11", "ss02"; "ss03"`
- **Role:** Code snippets, technical labels, and specialized data displays, providing a clear, fixed-width appearance.

### Phosphor-Bold — Decorative icons as part of icon fonts, used to convey semantic meaning or decoration in navigation and headings. · `--font-phosphor-bold`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 20px, 32px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"liga"`
- **Role:** Decorative icons as part of icon fonts, used to convey semantic meaning or decoration in navigation and headings.

### Phosphor-Fill — Filled decorative icons, complementing outlined icons for emphasis. · `--font-phosphor-fill`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px, 20px, 32px
- **Line height:** 1.00
- **Letter spacing:** normal
- **OpenType features:** `"liga"`
- **Role:** Filled decorative icons, complementing outlined icons for emphasis.

### Permanent Marker — Handwritten-style accents and annotations, adding a personal and informal touch to instructional elements or highlights. · `--font-permanent-marker`
- **Substitute:** cursive
- **Weights:** 400
- **Sizes:** 16px, 20px
- **Line height:** 1.40, 1.50
- **Letter spacing:** -0.0100em at 20px, -0.0080em at 16px
- **OpenType features:** `"calt", "cv11", "ss02"`
- **Role:** Handwritten-style accents and annotations, adding a personal and informal touch to instructional elements or highlights.

### -apple-system — -apple-system — detected in extracted data but not described by AI · `--font-apple-system`
- **Weights:** 400
- **Sizes:** 14px
- **Line height:** 1.43
- **OpenType features:** `"calt", "cv11", "ss02"`
- **Role:** -apple-system — detected in extracted data but not described by AI

### Font Awesome 6 Brands — Font Awesome 6 Brands — detected in extracted data but not described by AI · `--font-font-awesome-6-brands`
- **Weights:** 400
- **Sizes:** 16px, 20px
- **Line height:** 1
- **Letter spacing:** -0.01, -0.009, 0.024
- **OpenType features:** `"calt", "cv11", "ss02"`
- **Role:** Font Awesome 6 Brands — detected in extracted data but not described by AI

### Family — Family — detected in extracted data but not described by AI · `--font-family`
- **Weights:** 400, 500, 700
- **Sizes:** 26px
- **Line height:** 1.5
- **Letter spacing:** -0.001
- **OpenType features:** `"calt", "cv11", "ss02"`
- **Role:** Family — detected in extracted data but not described by AI

### Phosphor — Phosphor — detected in extracted data but not described by AI · `--font-phosphor`
- **Weights:** 400
- **Sizes:** 24px
- **Line height:** 1
- **OpenType features:** `"liga"`
- **Role:** Phosphor — detected in extracted data but not described by AI

### Fraunces — Fraunces — detected in extracted data but not described by AI · `--font-fraunces`
- **Weights:** 700
- **Sizes:** 36px
- **Line height:** 1.2
- **Letter spacing:** -0.004
- **OpenType features:** `"calt", "cv11", "ss02"`
- **Role:** Fraunces — detected in extracted data but not described by AI

### Chakra Petch — Chakra Petch — detected in extracted data but not described by AI · `--font-chakra-petch`
- **Weights:** 700
- **Sizes:** 36px
- **Line height:** 1.2
- **Letter spacing:** -0.004
- **OpenType features:** `"calt", "cv11", "ss02"`
- **Role:** Chakra Petch — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.4 | -0.04px | `--text-caption` |
| body | 14px | 1.43 | -0.11px | `--text-body` |
| heading-sm | 20px | 1.2 | -0.22px | `--text-heading-sm` |
| heading | 24px | 1.2 | -0.31px | `--text-heading` |
| heading-lg | 36px | 1.2 | -0.14px | `--text-heading-lg` |
| display | 56px | 1.1 | -1.12px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 96 | 96px | `--spacing-96` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 14px |
| input | 4px |
| badges | 999px |
| buttons | 4px |
| default | 6px |
| heroCards | 22px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(41, 0, 41, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0....` | `--shadow-subtle` |
| subtle-2 | `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset, rgba(0, 0...` | `--shadow-subtle-2` |
| subtle-3 | `rgba(255, 255, 255, 0.05) 0px 0px 0px 1px` | `--shadow-subtle-3` |
| subtle-4 | `rgba(41, 0, 41, 0.2) 0px 0px 0px 1px inset` | `--shadow-subtle-4` |
| subtle-5 | `rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0....` | `--shadow-subtle-5` |
| subtle-6 | `rgba(32, 0, 36, 0.01) 0px 1px 1.5px 0px, rgba(32, 0, 36, ...` | `--shadow-subtle-6` |
| subtle-7 | `rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0....` | `--shadow-subtle-7` |
| subtle-8 | `rgba(32, 0, 36, 0.11) 0px 0px 0px 1px` | `--shadow-subtle-8` |
| subtle-9 | `rgba(41, 0, 41, 0.11) 0px 0px 0px 1px` | `--shadow-subtle-9` |
| subtle-10 | `rgba(255, 255, 255, 0.11) 0px 0px 0px 1px` | `--shadow-subtle-10` |
| subtle-11 | `rgba(0, 0, 0, 0.05) 0px 1px 2px 0px` | `--shadow-subtle-11` |
| subtle-12 | `rgba(32, 0, 36, 0.05) 0px 1px 2px 0px, rgba(255, 255, 255...` | `--shadow-subtle-12` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 48px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Call to action

Solid Rose Bloom (#df37a7) background, Canvas White (#ffffff) text, 4px border-radius, 8px vertical padding, 24px horizontal padding. Shadow: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px.

### Ghost Button
**Role:** Secondary action (light background)

Transparent background, Muted Orchid (#6d526d) text and 1px border. 8px border-radius, 4px vertical padding, 12px horizontal padding.

### Inverted Ghost Button (Dark Background)
**Role:** Secondary action (dark background)

Transparent background, Canvas White (#ffffff) text and 1px border, 6px border-radius, 4px vertical padding, 12px horizontal padding. Used against dark or gradient backgrounds.

### Main Navigation Link Button
**Role:** Navigation button

Midnight Plum (#240029) background for active state, Canvas White (#ffffff) text, 999px border-radius, 8px vertical padding, 16px horizontal padding. Hover state matches active.

### Standard Card
**Role:** Content container

Canvas White (#ffffff) background with 14px border-radius. Subtle shadow: rgba(41, 0, 41, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px.

### Faded Card
**Role:** Secondary content grouping

rgba(41, 0, 41, 0.02) background, 0px border-radius, no shadow, 24px padding on all sides. Used for sections that need a slight lift off the main background without heavy visual weight.

### Hero Card
**Role:** Prominent interactive elements in hero section

Slightly translucent Canvas White (#ffffff, 20% opacity) background with 22px border-radius. Thin border: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px.

### Text Input
**Role:** Form element

Translucent background (rgba(255, 255, 255, 0.05)), Canvas White (#ffffff) text, Input Border Gray (#767676) border, 4px border-radius, 8px vertical padding, 12px horizontal padding.

### Default Badge
**Role:** Categorization/tagging

rgba(41, 0, 41, 0.02) background, Midnight Plum (#240029) text, 999px (pill) border-radius, 4px vertical padding, 12px horizontal padding.

### Success Badge
**Role:** Positive status indicator

Success Green Background (#dcfce7) with Success Green Border (#bbf7d0), Success Green Text (#15803d), 999px border-radius, 1.6px vertical padding, 12px horizontal padding.

## Do's and Don'ts

### Do
- Always use Inter Var for UI text (buttons, labels, body copy) adjusting weight for hierarchy and letter-spacing for legibility: e.g., 16px Inter Var 400 for body, -0.16px letter-spacing.
- Apply Rose Bloom (#df37a7) as the primary brand accent for call-to-action buttons and key interactive elements, ensuring high contrast with Canvas White (#ffffff) text.
- Utilize the full page width for hero sections and footers, creating immersive experiences, while containing main content to max-width 1200px.
- Employ soft drop shadows with a slight purple tint (e.g., rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px) for cards and interactive elements for subtle elevation.
- Use 999px border-radius for badges and circular elements like avatars to maintain a friendly, approachable aesthetic.
- Incorporate the gradient from rgb(255, 189, 211) to rgb(255, 203, 15) for high-impact header and footer backgrounds to introduce a vibrant brand feel.
- Maintain a clear vertical rhythm between sections using a 48px `sectionGap`.
- For subtle visual breaks between content, use the Faded Card (rgba(41, 0, 41, 0.02) background) without heavy borders or shadows.

### Don't
- Do not introduce new primary typefaces for headings; stick to Kaio for prominent titles and Inter Var for subheadings.
- Avoid harsh, high-contrast borders unless for semantic emphasis (e.g., warning states); use Whisper Gray (#d4ccd4) for subtle dividers.
- Do not use highly saturated colors for large background areas that are not hero or footers; keep primary canvas white (#ffffff) for content sections.
- Refrain from using strong, opaque shadows that create heavy visual weight; prefer the subtle, multi-layered shadows provided in the component descriptions.
- Do not deviate from the established border radii (e.g., 4px for buttons, 14px for cards) as they contribute significantly to the perceived polish.
- Do not use Permanent Marker for body text or functional UI elements; reserve it for decorative annotations only.
- Avoid arbitrary color choices for interactive states; only use Rose Bloom (#df37a7) for primary calls to action, and Muted Orchid (#6d526d) for secondary actions on light backgrounds.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Primary background for most page content. |
| 1 | Faded Card Surface | `#29002905` | Subtle background for grouped content, offering a slight visual offset from the canvas. |
| 2 | Standard Card Surface | `#ffffff` | Elevated white cards with subtle shadow for main content blocks. |

## Elevation

- **Standard Card:** `rgba(41, 0, 41, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px`
- **Hero Card:** `rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.01) 0px 1px 1.5px 0px, rgba(32, 0, 36, 0.02) 0px 2px 3px 0px, rgba(32, 0, 36, 0.03) 0px 4px 6px 0px, rgba(32, 0, 36, 0.04) 0px 8px 12px 0px, rgba(32, 0, 36, 0.05) 0px 16px 24px 0px, rgba(32, 0, 36, 0.06) 0px 24px 36px 0px, rgba(32, 0, 36, 0.07) 0px 36px 54px 0px, rgba(32, 0, 36, 0.08) 0px 54px 81px 0px`
- **Input Field / Button (on focused state):** `rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px`

## Imagery

Outseta uses a mix of product screenshots, abstract illustrations, and small decorative icons. Product screenshots are contained within cards with rounded corners, often implying a context of use on a laptop or mobile device. These are generally isolated without busy backgrounds. Illustrations are abstract, featuring organic shapes and flowing lines in brand colors (purple, pink, yellow gradients) rather than outlined or flat styles, contributing to the vibrant atmosphere. Icons are primarily 'Phosphor' font-based, appearing as outlined or filled, mostly monochrome (Midnight Plum) for clarity and functionality within the UI, with some larger decorative icons. The imagery often serves to explain content or showcase the product, generally at a balanced density to allow for prominent text.

## Layout

The page primarily uses a contained layout with a maximum width of 1200px, centering content for most sections. The hero section, however, utilizes a full-bleed background featuring a vibrant gradient from rgb(255, 189, 211) to rgb(255, 203, 15) with centered text and primary calls to action. Subsequent sections alternate between the primary white canvas and the lighter Faded Card Surface (rgba(41, 0, 41, 0.02)), with consistent vertical spacing of 48px. Content is often arranged in symmetrical stacks or 2-column layouts, with text-left/image-right patterns common. Card grids (e.g., for customer testimonials or feature showcases) typically display 3 columns. Navigation is a sticky top bar with brand logo and prominent login/sign-up buttons.

## Agent Prompt Guide

Quick Color Reference:
text: #240029
background: #ffffff
border: #d4ccd4
accent: #ffcc11
primary action: #df37a7 (filled action)

Example Component Prompts:
1. Create a primary call-to-action button: 'Sign Up Now', Rose Bloom (#df37a7) background, Canvas White (#ffffff) text, 4px border-radius, 8px 24px padding.
2. Design a standard content card: Canvas White (#ffffff) background, 14px border-radius, standard card shadow, Midnight Plum (#240029) heading (24px Inter Var 600, -0.31px letter-spacing), and Midnight Plum (#240029) body text (14px Inter Var 400, -0.11px letter-spacing).
3. Generate a ghost button for secondary action: 'Learn More', transparent background, Muted Orchid (#6d526d) text and 1px border, 8px border-radius, 4px 12px padding.
4. Produce a success badge: text 'Status: Active', Success Green Background (#dcfce7), Success Green Border (#bbf7d0), Success Green Text (#15803d), 999px border-radius, 1.6px 12px padding.

## Similar Brands

- **Memberstack** — Modern SaaS aesthetic with a blend of light backgrounds and distinct accent colors for interactive elements, similar typography attitudes.
- **Webflow** — Clean, structured layouts, liberal use of white space, and a mix of professional sans-serifs with playful accents, along with strong brand coloring in hero sections.
- **Stripe** — Attention to subtle shadows and transitions, a clean white canvas with high-contrast text, and a focused use of chromatic colors to highlight key actions and brand identity.
- **ConvertKit** — Emphasis on clear, concise product messaging backed by vibrant color accents and approachable typography, using gradients for visual depth.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-plum: #240029;
  --gradient-midnight-plum: linear-gradient(145deg, rgb(255, 189, 211), rgb(255, 241, 189) 40%, rgb(255, 241, 189) 60%, rgb(255, 203, 15));
  --color-whisper-gray: #d4ccd4;
  --color-input-border-gray: #767676;
  --color-deep-plum-text: #333333;
  --color-rose-bloom: #df37a7;
  --color-muted-orchid: #6d526d;
  --color-sunshine-gold: #ffcc11;
  --color-vivid-cobalt: #635bff;
  --color-deep-pink-accent: #d0339c;
  --color-sky-blue-accent: #3898ec;
  --color-success-green-text: #15803d;
  --color-success-green-border: #bbf7d0;
  --color-success-green-background: #dcfce7;
  --color-faded-plum-accent: #bbadbb;
  --color-warning-red: #ef4444;

  /* Typography — Font Families */
  --font-inter-var: 'Inter Var', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kaio: 'Kaio', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'Jetbrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-phosphor-bold: 'Phosphor-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor-fill: 'Phosphor-Fill', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-permanent-marker: 'Permanent Marker', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-6-brands: 'Font Awesome 6 Brands', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-family: 'Family', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor: 'Phosphor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fraunces: 'Fraunces', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chakra-petch: 'Chakra Petch', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: -0.04px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.11px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.31px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.14px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.12px;

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
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-96: 96px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 48px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-3xl: 32px;
  --radius-3xl-2: 46px;
  --radius-full: 64px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-cards: 14px;
  --radius-input: 4px;
  --radius-badges: 999px;
  --radius-buttons: 4px;
  --radius-default: 6px;
  --radius-herocards: 22px;

  /* Shadows */
  --shadow-subtle: rgba(41, 0, 41, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-4: rgba(41, 0, 41, 0.2) 0px 0px 0px 1px inset;
  --shadow-subtle-5: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.01) 0px 1px 1.5px 0px, rgba(32, 0, 36, 0.02) 0px 2px 3px 0px, rgba(32, 0, 36, 0.03) 0px 4px 6px 0px, rgba(32, 0, 36, 0.04) 0px 8px 12px 0px, rgba(32, 0, 36, 0.05) 0px 16px 24px 0px, rgba(32, 0, 36, 0.06) 0px 24px 36px 0px, rgba(32, 0, 36, 0.07) 0px 36px 54px 0px, rgba(32, 0, 36, 0.08) 0px 54px 81px 0px;
  --shadow-subtle-6: rgba(32, 0, 36, 0.01) 0px 1px 1.5px 0px, rgba(32, 0, 36, 0.02) 0px 2px 3px 0px, rgba(32, 0, 36, 0.03) 0px 4px 6px 0px, rgba(32, 0, 36, 0.04) 0px 8px 12px 0px, rgba(32, 0, 36, 0.05) 0px 16px 24px 0px;
  --shadow-subtle-7: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px;
  --shadow-subtle-8: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px;
  --shadow-subtle-9: rgba(41, 0, 41, 0.11) 0px 0px 0px 1px;
  --shadow-subtle-10: rgba(255, 255, 255, 0.11) 0px 0px 0px 1px;
  --shadow-subtle-11: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-12: rgba(32, 0, 36, 0.05) 0px 1px 2px 0px, rgba(255, 255, 255, 0.4) 0px 10px 24px -10px inset;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-faded-card-surface: #29002905;
  --surface-standard-card-surface: #ffffff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #ffffff;
  --color-midnight-plum: #240029;
  --color-whisper-gray: #d4ccd4;
  --color-input-border-gray: #767676;
  --color-deep-plum-text: #333333;
  --color-rose-bloom: #df37a7;
  --color-muted-orchid: #6d526d;
  --color-sunshine-gold: #ffcc11;
  --color-vivid-cobalt: #635bff;
  --color-deep-pink-accent: #d0339c;
  --color-sky-blue-accent: #3898ec;
  --color-success-green-text: #15803d;
  --color-success-green-border: #bbf7d0;
  --color-success-green-background: #dcfce7;
  --color-faded-plum-accent: #bbadbb;
  --color-warning-red: #ef4444;

  /* Typography */
  --font-inter-var: 'Inter Var', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-kaio: 'Kaio', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jetbrains-mono: 'Jetbrains Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-phosphor-bold: 'Phosphor-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor-fill: 'Phosphor-Fill', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-permanent-marker: 'Permanent Marker', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apple-system: '-apple-system', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-font-awesome-6-brands: 'Font Awesome 6 Brands', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-family: 'Family', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-phosphor: 'Phosphor', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fraunces: 'Fraunces', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-chakra-petch: 'Chakra Petch', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.4;
  --tracking-caption: -0.04px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.11px;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.22px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.31px;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.14px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.12px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-96: 96px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 14px;
  --radius-2xl: 18px;
  --radius-2xl-2: 22px;
  --radius-3xl: 32px;
  --radius-3xl-2: 46px;
  --radius-full: 64px;
  --radius-full-2: 999px;

  /* Shadows */
  --shadow-subtle: rgba(41, 0, 41, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.2) 0px 0px 0px 1px inset, rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-3: rgba(255, 255, 255, 0.05) 0px 0px 0px 1px;
  --shadow-subtle-4: rgba(41, 0, 41, 0.2) 0px 0px 0px 1px inset;
  --shadow-subtle-5: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.01) 0px 1px 1.5px 0px, rgba(32, 0, 36, 0.02) 0px 2px 3px 0px, rgba(32, 0, 36, 0.03) 0px 4px 6px 0px, rgba(32, 0, 36, 0.04) 0px 8px 12px 0px, rgba(32, 0, 36, 0.05) 0px 16px 24px 0px, rgba(32, 0, 36, 0.06) 0px 24px 36px 0px, rgba(32, 0, 36, 0.07) 0px 36px 54px 0px, rgba(32, 0, 36, 0.08) 0px 54px 81px 0px;
  --shadow-subtle-6: rgba(32, 0, 36, 0.01) 0px 1px 1.5px 0px, rgba(32, 0, 36, 0.02) 0px 2px 3px 0px, rgba(32, 0, 36, 0.03) 0px 4px 6px 0px, rgba(32, 0, 36, 0.04) 0px 8px 12px 0px, rgba(32, 0, 36, 0.05) 0px 16px 24px 0px;
  --shadow-subtle-7: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px, rgba(32, 0, 36, 0.05) 0px 2px 2px 0px;
  --shadow-subtle-8: rgba(32, 0, 36, 0.11) 0px 0px 0px 1px;
  --shadow-subtle-9: rgba(41, 0, 41, 0.11) 0px 0px 0px 1px;
  --shadow-subtle-10: rgba(255, 255, 255, 0.11) 0px 0px 0px 1px;
  --shadow-subtle-11: rgba(0, 0, 0, 0.05) 0px 1px 2px 0px;
  --shadow-subtle-12: rgba(32, 0, 36, 0.05) 0px 1px 2px 0px, rgba(255, 255, 255, 0.4) 0px 10px 24px -10px inset;
}
```
