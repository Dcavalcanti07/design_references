# Whimsical — Style Reference
> Plush Violet Cloud

**Theme:** light

Whimsical evokes a vibrant, playful productivity studio: plush, rounded surfaces and a dynamic color palette built on deep violets and fuchsia gradients. Typography is clean and highly readable, grounding the energetic visuals. Components are generous in padding and radius, fostering an inviting tactile feel. The overall impression is one of approachable sophistication, designed for creative flow and seamless interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Plum | `#250835` | `--color-midnight-plum` | Primary text, prominent headings, primary action background — a deep, rich violet serving as a anchor for the vibrant system |
| Soft Mauve | `#473054` | `--color-soft-mauve` | Muted text, secondary body copy, subtle borders and outlines — a softer, desaturated variant of the primary brand color |
| Faded Violet | `#ab2fed` | `--color-faded-violet` | Interactive link text, accent icons, highlighted borders — a vivid violet used for emphasis and interactive states |
| Sky Blue | `#0283ec` | `--color-sky-blue` | Blue decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Luminous Grape | `#4b38ee` | `--color-luminous-grape` | Violet decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Fuschia Delight Gradient | `linear-gradient(142deg, rgb(186, 89, 255) 0%, rgb(186, 89, 255) 30%, rgb(255, 89, 241))` | `--color-fuschia-delight-gradient` | Decorative background gradients, highlight elements for hero sections — creates a sense of depth and dynamism |
| Cosmic Bloom Gradient | `linear-gradient(97deg, rgb(60, 161, 255) 5.54%, rgb(200, 82, 255) 49.85%, rgb(255, 96, 240) 94.14%)` | `--color-cosmic-bloom-gradient` | Supporting palette color for small decorative accents when the core palette needs contrast. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page background, primary card surfaces, ghost button backgrounds — provides a crisp, clean foundation for content |
| Ash Gray | `#ebe6ee` | `--color-ash-gray` | Secondary surface background, section dividers, subtle card backgrounds — slightly off-white for visual separation without harsh contrast |
| Silver Mist | `#f5f4f5` | `--color-silver-mist` | Lightest surface background, subtle card variations — a very light gray for minimal surface elevation |
| Washed Lavender | `#decaff` | `--color-washed-lavender` | Decorative card backgrounds, accent washes — a very light, desaturated violet for background textures |
| Blush Pink | `#e9bded` | `--color-blush-pink` | Decorative background surfaces, accent panels reminiscent of the brand's playful side |
| Slate Shadow | `#cdc7d1` | `--color-slate-shadow` | Supporting neutral for secondary UI, dividers, and muted labels. Do not promote it to the primary CTA color |
| Dusty Lilac | `#6a5b72` | `--color-dusty-lilac` | Muted secondary text, subtle borders, inactive link states — a mid-tone desaturated violet for hierarchy |
| Pewter Tone | `#918499` | `--color-pewter-tone` | Tertiary text, subtle separators, copyright text — a lighter, desaturated gray for unobtrusive details |

## Tokens — Typography

### Agrandir — Display headings, hero text, section titles — a bold, expansive sans-serif with subtle negative tracking for a confident, modern statement at large sizes. · `--font-agrandir`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 24px, 48px, 64px, 96px
- **Line height:** 1.00, 1.10
- **Letter spacing:** -0.0100em
- **Role:** Display headings, hero text, section titles — a bold, expansive sans-serif with subtle negative tracking for a confident, modern statement at large sizes.

### Manrope — Body copy, UI elements, navigation, buttons, small text — a versatile, highly readable sans-serif with varied weights and positive tracking for clarity and approachability. · `--font-manrope`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 9px, 10px, 12px, 13px, 14px, 16px, 32px
- **Line height:** 1.00, 1.20, 1.40, 2.67
- **Letter spacing:** 0.0090em
- **Role:** Body copy, UI elements, navigation, buttons, small text — a versatile, highly readable sans-serif with varied weights and positive tracking for clarity and approachability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.15px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.01px | `--text-body-sm` |
| body | 16px | 1.4 | 0.009px | `--text-body` |
| subheading | 24px | 1.1 | -0.24px | `--text-subheading` |
| heading | 48px | 1.1 | -0.48px | `--text-heading` |
| display | 64px | 1 | -0.64px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 8px |
| buttons | 12px |
| containers | 16px |
| largeElements | 120px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(37, 8, 53, 0.06) 0px 16px 32px -4px` | `--shadow-xl` |
| md | `rgba(37, 8, 53, 0.2) 0px 12px 16px -4px` | `--shadow-md` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 60px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call to action, interactive controls

Uses Midnight Plum (#250835) background with Canvas White (#ffffff) text, a generous 12px border radius, and 8px vertical, 40px horizontal padding. Features a subtle elevated shadow (rgba(37, 8, 53, 0.06) 0px 16px 32px -4px).

### Menu Ghost Button
**Role:** Secondary navigation links, discreet actions

Transparent background with Midnight Plum (#250835) text and border, 12px radius, and 0px vertical, 18px horizontal padding. Used for subtle, non-intrusive actions.

### Large Feature Button
**Role:** Prominent feature calls to action within content sections

Canvas White (#ffffff) background with Midnight Plum (#250835) text, a generous 16px border radius, and 24px padding all around. Creates a spacious, inviting target.

### Standard Content Card
**Role:** Organizes content blocks, visual features

Ash Gray (#ebe6ee) background with 8px border radius. Padding is 24px left, 0px right, 0px top, 0px bottom. Used for visual distinction of content.

### Decorative Background Card (Washed Lavender)
**Role:** Background visual elements, abstract shapes

Washed Lavender (#decaff) background with a large 120px border radius, no padding or shadow. Functions as a soft, rounded accent shape.

### Hero Message Bar
**Role:** Top-banner message, alert, or navigation

Deep gradient from Fuschia Delight Fade (#ba59ff) to Pink Fade, with a 12px border radius. Contains Canvas White text and a link to a new feature.

### Text Link - Faded Violet
**Role:** Inline links, secondary calls to action

Uses Faded Violet (#ab2fed) for text color. No explicit background, serves as a chromatic accent for navigation within content.

## Do's and Don'ts

### Do
- Prioritize Midnight Plum (#250835) for primary textual elements, including body copy and main headings, ensuring high contrast against light backgrounds.
- Use Manrope font with positive letter spacing (e.g., 0.0090em for body text) to maintain readability across all UI elements.
- Apply generous border radii, typically 12px for buttons and 8px for cards, to reinforce the soft, approachable aesthetic.
- Implement the linear-gradient(142deg, #ba59ff 0%, #ba59ff 30%, #ff59f1) for hero banner backgrounds and brand-defining visual accents.
- Maintain comfortable spacing with a 16px element gap and 24px card vertical padding to prevent visual clutter.
- Utilize a subtle, diffused shadow rgba(37, 8, 53, 0.06) 0px 16px 32px -4px for primary buttons to give a gentle lift.
- Feature large, bold Agrandir display headings (e.g., 64px, -0.01em letter spacing) against the soft background surfaces to command attention.

### Don't
- Avoid sharp corners; all interactive elements and contained surfaces should have visible rounding.
- Do not use highly saturated colors for large background areas; reserve vivid tones for accents, interactive states, and gradients.
- Steer clear of aggressive, high-contrast shadows; elevation should be subtle and hint at depth rather than creating harsh lines.
- Do not neglect the Manrope font's positive letter spacing; tighter tracking compromises the friendly, readable aesthetic of body text.
- Avoid using multiple chromatic colors for primary actions; maintain Midnight Plum (#250835) as the dominant call-to-action color.
- Do not introduce square or rectangular brand imagery; all product mockups and illustrations should align with the rounded aesthetic.
- Refrain from dense, information-heavy layouts; give elements and sections ample breathing room dictated by the 60px section gap.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#ffffff` | Dominant background for the entire page, providing a bright, clean foundation. |
| 1 | Base Surface | `#f5f4f5` | Slightly elevated background for minor sections or subtle container separation, providing minimal visual break. |
| 2 | Card Surface | `#ebe6ee` | Primary background for cards and feature blocks, offering a clear visual boundary against the page canvas. |
| 3 | Accent Surface | `#decaff` | Decorative background for specific cards or sections, adding a soft, branded color wash. |
| 4 | Decorative Highlight | `#e9bded` | Stronger decorative background to draw attention to key sections, often paired with gradients. |

## Elevation

- **Primary Filled Button:** `rgba(37, 8, 53, 0.06) 0px 16px 32px -4px`
- **Interactive Link/Button Hover:** `rgba(37, 8, 53, 0.2) 0px 12px 16px -4px`

## Imagery

Whimsical employs product screenshots and abstract, geometric illustrations. Product screenshots are contained within heavily rounded 'device' frames and gently elevated with shadows, showcasing the UI in a friendly, approachable manner. Illustrations are flat, often outlined, and utilize the brand's vibrant violet and blue accent colors, appearing as decorative elements to enhance content. Icons are outlined, fine-lined, and mono-color, primarily using the Faded Violet and Sky Blue accents. Imagery serves to explain capabilities, showcase the product, and add a playful, modern atmosphere without being overwhelming, balancing density with spacious UI.

## Layout

The page uses a contained layout with a maximum width of approximately 1200px, centering content within a generous horizontal margin. The hero section is full-bleed, featuring a large, rounded background panel with a bold, centered headline and a prominent primary action. Sections below alternate between white and a very light gray (#f5f4f5 or #ebe6ee) backgrounds, separated by a consistent 60px vertical gap. Content is arranged in alternating two-column text-left/image-right patterns, and three-column grids for feature cards, each with ample internal padding. Navigation is a sticky top bar with a branded logo, links, and distinct sign-up/login buttons.

## Agent Prompt Guide

### Quick Color Reference
text: #250835
background: #ffffff
border: #6a5b72
accent: #ab2fed
primary action: #250835 (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #250835 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card: Ash Gray (#ebe6ee) background, 8px radius, 24px left padding. Title uses Manrope weight 600 at 16px, Midnight Plum (#250835) text. Body text is Manrope weight 400 at 14px, Soft Mauve (#473054) text. Include a Faded Violet (#ab2fed) text link for 'Explore'.
3. Construct a navigation bar: Canvas White (#ffffff) background. Left-aligned brand logo. Right-aligned ghost buttons using Midnight Plum (#250835) text and border, 12px radius, 0px vertical 18px horizontal padding. The 'Sign up' button uses Midnight Plum (#250835) background, Canvas White (#ffffff) text, 12px radius, 8px vertical 40px horizontal padding, with a subtle shadow.

## Similar Brands

- **Figma** — Bright, spacious canvas with a focus on collaborative tools and a playful, professional color accent palette.
- **Notion** — Clean, light UI with a high degree of content density, structured surfaces, and a balance of powerful features with a friendly aesthetic.
- **Miro** — Whiteboard-centric interface, blending creative tools with a clean design, and a similar approach to using a few vibrant accents on a neutral canvas.
- **Linear** — Minimalist design, strong typography, efficient use of space, and subtle, functional pops of color on an otherwise muted interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-plum: #250835;
  --color-soft-mauve: #473054;
  --color-faded-violet: #ab2fed;
  --color-sky-blue: #0283ec;
  --color-luminous-grape: #4b38ee;
  --color-fuschia-delight-gradient: #ba59ff;
  --gradient-fuschia-delight-gradient: linear-gradient(142deg, rgb(186, 89, 255) 0%, rgb(186, 89, 255) 30%, rgb(255, 89, 241));
  --color-cosmic-bloom-gradient: #3ca1ff;
  --gradient-cosmic-bloom-gradient: linear-gradient(97deg, rgb(60, 161, 255) 5.54%, rgb(200, 82, 255) 49.85%, rgb(255, 96, 240) 94.14%);
  --color-canvas-white: #ffffff;
  --color-ash-gray: #ebe6ee;
  --color-silver-mist: #f5f4f5;
  --color-washed-lavender: #decaff;
  --color-blush-pink: #e9bded;
  --color-slate-shadow: #cdc7d1;
  --color-dusty-lilac: #6a5b72;
  --color-pewter-tone: #918499;

  /* Typography — Font Families */
  --font-agrandir: 'Agrandir', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.15px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.01px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.009px;
  --text-subheading: 24px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.24px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-180: 180px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 60px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-sm: 0.5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;
  --radius-full: 80px;
  --radius-full-2: 120px;
  --radius-full-3: 160px;

  /* Named Radii */
  --radius-cards: 8px;
  --radius-buttons: 12px;
  --radius-containers: 16px;
  --radius-largeelements: 120px;

  /* Shadows */
  --shadow-xl: rgba(37, 8, 53, 0.06) 0px 16px 32px -4px;
  --shadow-md: rgba(37, 8, 53, 0.2) 0px 12px 16px -4px;

  /* Surfaces */
  --surface-page-canvas: #ffffff;
  --surface-base-surface: #f5f4f5;
  --surface-card-surface: #ebe6ee;
  --surface-accent-surface: #decaff;
  --surface-decorative-highlight: #e9bded;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-plum: #250835;
  --color-soft-mauve: #473054;
  --color-faded-violet: #ab2fed;
  --color-sky-blue: #0283ec;
  --color-luminous-grape: #4b38ee;
  --color-fuschia-delight-gradient: #ba59ff;
  --color-cosmic-bloom-gradient: #3ca1ff;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #ebe6ee;
  --color-silver-mist: #f5f4f5;
  --color-washed-lavender: #decaff;
  --color-blush-pink: #e9bded;
  --color-slate-shadow: #cdc7d1;
  --color-dusty-lilac: #6a5b72;
  --color-pewter-tone: #918499;

  /* Typography */
  --font-agrandir: 'Agrandir', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.15px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.01px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.009px;
  --text-subheading: 24px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.24px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-sm: 0.5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 40px;
  --radius-full: 80px;
  --radius-full-2: 120px;
  --radius-full-3: 160px;

  /* Shadows */
  --shadow-xl: rgba(37, 8, 53, 0.06) 0px 16px 32px -4px;
  --shadow-md: rgba(37, 8, 53, 0.2) 0px 12px 16px -4px;
}
```
