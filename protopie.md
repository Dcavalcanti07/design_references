# ProtoPie — Style Reference
> Tech console, soft glow.

**Theme:** light

ProtoPie's design system creates a feeling of approachable high-tech proficiency. Its light theme and ample whitespace are punctuated by vibrant violet accents that guide interaction without overwhelming, like glowing controls on a clean white console. The judicious use of rounded corners—from subtle 4px button radii to emphatic 9999px pills—softens the technical edge, making complex prototyping feel open and inviting. Custom display fonts contribute to a distinctive, playful yet authoritative brand voice.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#181818` | `--color-midnight-ink` | Primary text for headings and body, providing high contrast on light backgrounds. |
| Stone Gray | `#555555` | `--color-stone-gray` | Secondary text and subtle details, creating a softer visual hierarchy. |
| Pale Gray | `#999999` | `--color-pale-gray` | Tertiary text, descriptive labels, and subtle UI elements. |
| Ghost White | `#ffffff` | `--color-ghost-white` | Page backgrounds, card surfaces, and primary button text. |
| Crystal Frost | `#e9e9e9` | `--color-crystal-frost` | Subtle background for UI elements, separating sections without sharp contrast. |
| Iris Bloom | `#8169ff` | `--color-iris-bloom` | Primary interactive elements like buttons and links, defining key actions and brand presence. |
| Violet Signal | `#6d4ff0` | `--color-violet-signal` | Alternative interactive elements, hover states, and brand highlights. |
| Lavender Haze | `#c9bfff` | `--color-lavender-haze` | Soft button backgrounds and subtle decorative elements, hinting at interaction. |
| Aqua Tint | `#3eb2b2` | `--color-aqua-tint` | Decorative elements and occasional iconography. |
| Violet Fade | `#ab9eff` | `--color-violet-fade` | Background gradients and soft visual accents. |
| Aqua Gradient | `radial-gradient(47.72% 108.66% at -12.1% 21.18%, rgba(129, 219, 219, 0.25) 24.27%, rgba(160, 232, 232, 0) 100%)` | `--color-aqua-gradient` | Subtle background effect creating depth and a modern feel. |
| Lavender Swirl | `radial-gradient(62.81% 136.54% at 103.92% 77.32%, rgba(227, 222, 255, 0.7) 0%, rgba(201, 191, 255, 0) 100%)` | `--color-lavender-swirl` | Decorative background gradient, adding a soft, ethereal quality to sections. |
| Violet Mist | `linear-gradient(rgba(227, 222, 255, 0) 0%, rgba(201, 191, 255, 0.4) 17%, rgba(201, 191, 255, 0.4) 30%, rgba(227, 222, 255, 0) 50%)` | `--color-violet-mist` | Background gradient for sections, providing a gentle color transition. |

## Tokens — Typography

### Gilroy — Dominant brand typeface used across headings, navigation, and key brand messages. The varying weights and generous line heights contribute to a modern, airy feel, while the bold weights at display sizes carry authority. · `--font-gilroy`
- **Substitute:** Montserrat
- **Weights:** 400, 700
- **Sizes:** 16px, 18px, 20px, 22px, 28px, 48px, 62px
- **Line height:** 1.29, 1.30, 1.33, 1.43, 1.45, 1.50, 1.56, 1.60
- **Letter spacing:** normal
- **Role:** Dominant brand typeface used across headings, navigation, and key brand messages. The varying weights and generous line heights contribute to a modern, airy feel, while the bold weights at display sizes carry authority.

### Inter — Used for body text, links, and detailed UI elements, ensuring legibility and content-heavy sections. Its clean, functional design supports the technical nature of the product. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 24px
- **Line height:** 1.30, 1.40, 1.43, 1.50, 1.56, 1.67
- **Letter spacing:** normal
- **Role:** Used for body text, links, and detailed UI elements, ensuring legibility and content-heavy sections. Its clean, functional design supports the technical nature of the product.

### Palmer Lake Print — A distinctive, decorative display font used sparingly for unique headings or stylistic elements. Its very tight line height and decorative nature add a unique flair, distinguishing specific brand messaging. · `--font-palmer-lake-print`
- **Substitute:** Rubik
- **Weights:** 400
- **Sizes:** 32px
- **Line height:** 0.80
- **Letter spacing:** normal
- **Role:** A distinctive, decorative display font used sparingly for unique headings or stylistic elements. Its very tight line height and decorative nature add a unique flair, distinguishing specific brand messaging.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.5 | — | `--text-body-sm` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading | 22px | 1.45 | — | `--text-heading` |
| heading-lg | 28px | 1.43 | — | `--text-heading-lg` |
| display-sm | 32px | 0.8 | — | `--text-display-sm` |
| display | 48px | 1.33 | — | `--text-display` |
| display-lg | 62px | 1.29 | — | `--text-display-lg` |

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
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 140 | 140px | `--spacing-140` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 12px |
| other | 8px |
| pills | 9999px |
| buttons | 4px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) ...` | `--shadow-md` |

### Layout

- **Card padding:** 16px
- **Element gap:** 8px

## Components

### Primary Filled Button
**Role:** Main call-to-action.

Background: Iris Bloom (#8169ff), Text: Ghost White (#ffffff), Border: Ghost White (#ffffff), Radius: 4px, Padding: 11px vertical, 16px horizontal. Uses Gilroy 700.

### Secondary Soft Button
**Role:** Alternative call-to-action or secondary action.

Background: Lavender Haze (#c9bfff), Text: Midnight Ink (#000000), Border: none, Radius: 8px, Padding: 0px. Uses Gilroy 400.

### Ghost Text Button
**Role:** Navigation or less prominent actions.

Background: transparent, Text: Midnight Ink (#000000), Border: none, Radius: 0px, Padding: 0px. Uses Gilroy 400.

### Pill Button
**Role:** Tags, categories, or filtering elements.

Background: Ghost White (#ffffff), Text: Midnight Ink (#000000), Border: none, Radius: 9999px, Padding: 0px (likely content-driven). Uses Gilroy 400.

### Header Navigation Link
**Role:** Main navigation items.

Text: Midnight Ink (#181818), no background, no border. Uses Gilroy 400 at 16px.

### Input Field
**Role:** User data entry.

Background: transparent, Text: Midnight Ink (#181818), Border: Midnight Ink (#181818), Radius: 0px, Padding: 16px vertical, 8px horizontal. Uses Inter 400.

### Elevated Card
**Role:** Content container with visual separation.

Background: Ghost White (#ffffff), Border Radius: 16px. Shadow: `rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) 0px 0px 2px 0px`.

## Do's and Don'ts

### Do
- Use Iris Bloom (#8169ff) for primary interactive buttons and links to consistently highlight calls to action.
- Apply Gilroy 700 for all headings to maintain brand's bold and clear voice, particularly at display sizes up to 62px.
- Implement 4px border-radius on primary action buttons for a subtle softening, contrasting with the overall sharpness.
- Incorporate `radial-gradient(47.72% 108.66% at -12.1% 21.18%, rgba(129, 219, 219, 0.25) 24.27%, rgba(160, 232, 232, 0) 100%)` for background accents to add depth without strong hard lines.
- Maintain a clear visual hierarchy using Midnight Ink (#181818) for primary text, Stone Gray (#555555) for secondary, and Pale Gray (#999999) for tertiary information.
- Use 9999px radius for all pill-shaped elements to differentiate them clearly as tags or small categorizations.
- Employ the `rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) 0px 0px 2px 0px` shadow for cards or elevated content to give subtle lift.

### Don't
- Avoid using highly saturated colors outside of the brand's defined violet and aqua accents to maintain a clean, light aesthetic.
- Do not introduce sharp corners on card-like elements; maintain a minimum of 8px radius to keep the system's approachable feel.
- Refrain from heavy, dark backgrounds on main content areas; the Ghost White (#ffffff) and Crystal Frost (#e9e9e9) provide necessary breathing room.
- Do not use generic system fonts for prominent headings; always use Gilroy or designated substitutes to preserve brand identity.
- Avoid excessive use of Palmer Lake Print; reserve it for specific, high-impact decorative headings only, due to its distinct character.
- Do not clutter layouts; leverage the comfortable density and significant whitespace to emphasize key content and interactions.
- Do not deviate from the established padding and spacing units; consistent use of 8px, 12px, 16px is crucial for a cohesive system.

## Elevation

- **Elevated Card:** `rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) 0px 0px 2px 0px`

## Imagery

The site uses a mix of tightly cropped product screenshots and playful, sometimes abstract, illustrations. Product shots are typically clean, isolated, and demonstrate UI interactions. Illustrations are dimensional and often incorporate brand colors (violet/aqua) or soft gradients, lending a friendly but sophisticated feel. Icons are primarily outlined or filled monochrome, reflecting the precision of a design tool. The visual density is balanced; images are present but not overwhelming, serving to explain and showcase the product's capabilities rather than just decorate.

## Layout

The page maintains a centered, max-width content area (around 1200px inferred) within a full-bleed background. The hero section often features a centered headline over a subtle gradient background, setting an open tone. Section rhythm relies on generous vertical spacing and occasional background color shifts, primarily using soft white and light gradient bands to delineate content blocks. Content arrangement frequently uses two-column layouts, often text on one side and product visuals or user testimonials on the other. Card grids organize features or customer logos in a 3-column structure. Navigation is a persistent top bar, sticky on scroll, with a clear 'Get Started' CTA.

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary:** `#181818` (Midnight Ink)
- **Background Primary:** `#ffffff` (Ghost White)
- **CTA Primary:** `#8169ff` (Iris Bloom)
- **Border Generic:** `rgba(0, 0, 0, 0.12)` (Shadow)
- **Accent Soft:** `#c9bfff` (Lavender Haze)

### Example Component Prompts
1. **Create a Primary Filled Button:** Background `#8169ff`, text `#ffffff`, border `#ffffff`, radius `4px`, padding `11px 16px`. Text 'Get Started' in Gilroy 700, 16px.
2. **Generate an Elevated Card:** Background `#ffffff`, border-radius `16px`, box-shadow `rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) 0px 0px 2px 0px`. Inner padding `16px`.
3. **Design a Heading 1:** Text `#181818`, Gilroy 700, size `48px`, line-height `1.33`. Content: '#1 advanced prototyping tool'.
4. **Produce a Pill Button:** Background `#ffffff`, text `#000000`, border-radius `9999px`, padding `6px 12px` (inferred). Text 'Automotive' in Gilroy 400, 16px.

## Similar Brands

- **Figma** — Shares a clean, light-themed UI with strong color accents that highlight interactive elements and a focus on product visuals.
- **Sketch** — Utilizes a balanced approach of whitespace and clear typography for a professional, tool-oriented aesthetic while maintaining approachability.
- **Webflow** — Exhibits a similar use of vibrant accent colors against a predominantly light background to guide users through complex functionality and emphasize calls to action.
- **Linear** — Adopts fine-grained control over typography and spacing, paired with a focus on functional, modern design, although Linear is darker-themed.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #181818;
  --color-stone-gray: #555555;
  --color-pale-gray: #999999;
  --color-ghost-white: #ffffff;
  --color-crystal-frost: #e9e9e9;
  --color-iris-bloom: #8169ff;
  --color-violet-signal: #6d4ff0;
  --color-lavender-haze: #c9bfff;
  --color-aqua-tint: #3eb2b2;
  --color-violet-fade: #ab9eff;
  --color-aqua-gradient: #81dbdb;
  --gradient-aqua-gradient: radial-gradient(47.72% 108.66% at -12.1% 21.18%, rgba(129, 219, 219, 0.25) 24.27%, rgba(160, 232, 232, 0) 100%);
  --color-lavender-swirl: #e3deff;
  --gradient-lavender-swirl: radial-gradient(62.81% 136.54% at 103.92% 77.32%, rgba(227, 222, 255, 0.7) 0%, rgba(201, 191, 255, 0) 100%);
  --color-violet-mist: #c9bfff;
  --gradient-violet-mist: linear-gradient(rgba(227, 222, 255, 0) 0%, rgba(201, 191, 255, 0.4) 17%, rgba(201, 191, 255, 0.4) 30%, rgba(227, 222, 255, 0) 50%);

  /* Typography — Font Families */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-palmer-lake-print: 'Palmer Lake Print', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 22px;
  --leading-heading: 1.45;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.43;
  --text-display-sm: 32px;
  --leading-display-sm: 0.8;
  --text-display: 48px;
  --leading-display: 1.33;
  --text-display-lg: 62px;
  --leading-display-lg: 1.29;

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
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-140: 140px;
  --spacing-160: 160px;

  /* Layout */
  --card-padding: 16px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 12px;
  --radius-other: 8px;
  --radius-pills: 9999px;
  --radius-buttons: 4px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) 0px 0px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #181818;
  --color-stone-gray: #555555;
  --color-pale-gray: #999999;
  --color-ghost-white: #ffffff;
  --color-crystal-frost: #e9e9e9;
  --color-iris-bloom: #8169ff;
  --color-violet-signal: #6d4ff0;
  --color-lavender-haze: #c9bfff;
  --color-aqua-tint: #3eb2b2;
  --color-violet-fade: #ab9eff;
  --color-aqua-gradient: #81dbdb;
  --color-lavender-swirl: #e3deff;
  --color-violet-mist: #c9bfff;

  /* Typography */
  --font-gilroy: 'Gilroy', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-palmer-lake-print: 'Palmer Lake Print', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 22px;
  --leading-heading: 1.45;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.43;
  --text-display-sm: 32px;
  --leading-display-sm: 0.8;
  --text-display: 48px;
  --leading-display: 1.33;
  --text-display-lg: 62px;
  --leading-display-lg: 1.29;

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
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-140: 140px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 3px 12px 0px, rgba(0, 0, 0, 0.3) 0px 0px 2px 0px;
}
```
