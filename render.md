# Render — Style Reference
> Crisp canvas, gradient fireworks. A bright, white backdrop that provides contrast for a constellation of colorful gradients and powerful typography.

**Theme:** light

This design system is a light, airy canvas punctuated by bold, evocative gradients and a vibrant, expansive color palette. The combination of clean, modern sans-serifs and a striking, multi-color gradient usage creates a dynamic yet professional atmosphere. Text is predominantly dark charcoal against a pristine white background, allowing the rich accent colors and gradients to highlight key information and interactive elements, giving the impression of a sophisticated, high-performance platform.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Primary page and component backgrounds, offering a pristine, expansive base for content. |
| Charcoal Text | `#0d0d0d` | `--color-charcoal-text` | Primary text color for headlines and body copy, ensuring strong contrast against light backgrounds. |
| Asphalt Gray | `#272727` | `--color-asphalt-gray` | Darker borders and subtle background elements, providing visual separation without harshness. |
| Pebble Gray | `#4d4d4d` | `--color-pebble-gray` | Secondary text, navigation items, and less prominent text, offering a softened contrast. |
| Smoke Gray | `#6b6b6b` | `--color-smoke-gray` | Tertiary text, subtle descriptions, and inactive states. |
| Silver Lining | `#e3e3e3` | `--color-silver-lining` | Borders, dividers, and subtle background fills, establishing visual structure on cards and sections. |
| Lavender Mist | `#e6daff` | `--color-lavender-mist` | Lightest accent background for navigation states and contextual highlights. |
| Arctic Blue Tint | `#e0f4ff` | `--color-arctic-blue-tint` | Background for specific informational sections or subtle visual separation. |
| Grape Glow | `#8a05ff` | `--color-grape-glow` | Highlight elements, interactive states, and specific brand feature callouts – the primary accent color. |
| Sunset Violet | `linear-gradient(to right, rgb(138, 5, 255), rgb(214, 127, 46))` | `--color-sunset-violet` | Prominent headings and visual highlights, signifying importance and drawing immediate attention with its vibrant energy. |
| Digital Emerald | `#009e7a` | `--color-digital-emerald` | Specific callouts and highlighted text/icons, indicating positive states or unique offerings. |
| Deep Plum | `#48008c` | `--color-deep-plum` | Link states and stronger purple accents, providing depth to interactive elements. |
| Crimson Spark | `#e96770` | `--color-crimson-spark` | Highlighting specific sections and attention-grabbing elements, signaling urgency or novelty. |
| Candy Pink | `#f347ff` | `--color-candy-pink` | Secondary vibrant accent, used for diverse visual elements to add a playful yet modern touch. |
| Sky Surge | `#33acff` | `--color-sky-surge` | Secondary accent for active states and informational elements, providing a clear, bright contrast. |
| Twilight Gradient | `linear-gradient(to right, rgb(28, 0, 55), rgb(42, 0, 82), rgb(226, 166, 110))` | `--color-twilight-gradient` | Used for hero sections and distinctive backgrounds, creating a sense of depth and advanced technology. |
| Radiant Purple to Pink | `linear-gradient(to right, rgb(157, 102, 255), rgb(251, 206, 255))` | `--color-radiant-purple-to-pink` | Used for specific interactive elements or visual flourishes, adding a dynamic and soft touch. |

## Tokens — Typography

### Roobert — Headlines and prominent display text that require a strong, modern presence. The negative letter spacing at larger sizes creates a tight, impactful visual. · `--font-roobert`
- **Substitute:** Inter
- **Weights:** 300, 400
- **Sizes:** 20px, 32px, 40px, 48px, 56px, 64px, 80px
- **Line height:** 1.00, 1.05, 1.06, 1.07, 1.08, 1.10, 1.15, 1.20
- **Letter spacing:** -0.03em at 80px, -0.025em at 64px, -0.02em at 56px, -0.015em at 48px, -0.01em at 40px
- **Role:** Headlines and prominent display text that require a strong, modern presence. The negative letter spacing at larger sizes creates a tight, impactful visual.

### PPNeueMontreal — Body copy, navigation, buttons, and general UI text. Its clean, readable nature ensures clarity for all informational content. · `--font-ppneuemontreal`
- **Substitute:** System UI
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.12, 1.21, 1.25, 1.33, 1.38, 1.40, 1.44, 1.50
- **Letter spacing:** 0.02em at 12px, 0.01em at 14px, 0.005em at 16px
- **Role:** Body copy, navigation, buttons, and general UI text. Its clean, readable nature ensures clarity for all informational content.

### PPNeueMontrealMono — Code snippets, technical labels, and specialized data display where monospaced precision is essential for alignment and clarity. · `--font-ppneuemontrealmono`
- **Substitute:** Space Mono
- **Weights:** 400, 500
- **Sizes:** 11px, 12px, 14px
- **Line height:** 1.27, 1.33, 1.43
- **Letter spacing:** 0.025em at 11px, 0.02em at 12px
- **Role:** Code snippets, technical labels, and specialized data display where monospaced precision is essential for alignment and clarity.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.43 | 0.24px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.14px | `--text-body-sm` |
| body | 16px | 1.5 | 0.08px | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading-sm | 20px | 1.2 | -0.2px | `--text-heading-sm` |
| heading | 24px | 1.25 | — | `--text-heading` |
| heading-lg | 32px | 1.15 | -0.48px | `--text-heading-lg` |
| display | 64px | 1.08 | -1.6px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 60 | 60px | `--spacing-60` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 937px |
| buttons | 0px |
| default | 0px |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Dark Button
**Role:** Call to Action

Solid Charcoal Text button. `backgroundColor: #0d0d0d`, `color: #ffffff`. `borderRadius: 0px`. `padding: 0px 10px`.

### Outline Button
**Role:** Secondary Action

Transparent button with Charcoal Text and a light gray border. `backgroundColor: rgba(0, 0, 0, 0)`, `color: #0d0d0d`, `border: 1px solid #e3e3e3`. `borderRadius: 0px`. `padding: 16px 30px`.

### Text Link Button
**Role:** Tertiary Action

Plain text button. `backgroundColor: #ffffff`, `color: #0d0d0d`. `borderRadius: 0px`. `padding: 0px`.

### Header Navigation Item
**Role:** Primary Navigation

Text link using `PPNeueMontreal`, `weight: 500`, `size: 14px`, `lineHeight: 1.25`, `color: #4d4d4d`. On hover, the text color changes or a subtle underline appears.

### Hero Headline
**Role:** Page Title

Uses `Roobert`, `weight: 400`, `size: 64px`, `lineHeight: 1.08`, `letterSpacing: -0.025em`. Features embedded gradients for specific words, e.g., 'apps & agents' uses `linear-gradient(to right, rgb(138, 5, 255), rgb(214, 127, 46))`.

### Feature List Item Heading
**Role:** Section Sub-heading

Uses `Roobert`, `weight: 400`, `size: 20px`, `lineHeight: 1.2`, `letterSpacing: -0.01em`. Initial number is highlighted with `Grape Glow` (#8a05ff).

### Body Paragraph
**Role:** General Content

Uses `PPNeueMontreal`, `weight: 400`, `size: 18px`, `lineHeight: 1.33`, `color: #0d0d0d`.

### Pill Tag
**Role:** Metadata/Label

Small label with `backgroundColor: rgba(0,0,0,0)`, `color: #0d0d0d`, `borderRadius: 937px`, `padding: 0px 10px`. Border of `Silver Lining` (#e3e3e3).

## Do's and Don'ts

### Do
- Use Charcoal Text (`#0d0d0d`) for all primary text against white backgrounds to ensure AAA contrast.
- Apply `borderRadius: 0px` for all standard buttons and cards to maintain a sharp, modern aesthetic.
- Utilize `Roobert` for all headlines with negative letter spacing (`-0.03em` to `-0.01em`) to create a signature tight, impactful look.
- Employ the `Grape Glow` (`#8a05ff`) as the primary accent for interactive elements and key numerical highlights.
- Incorporate the linear brand gradients (e.g., `linear-gradient(to right, rgb(138, 5, 255), rgb(214, 127, 46))`) for high-impact headlines or distinctive background sections.
- Maintain a clear visual hierarchy by consistently using `PPNeueMontreal` for body text and UI elements, with `16px` as a base font size.
- Ensure all interactive elements have a clear hover state, typically darkening the text or background subtly as seen on navigation items.

### Don't
- Do not introduce rounded corners other than `937px` for specific pill-shaped tags to maintain the sharp aesthetic.
- Avoid using additional bright, highly saturated colors for backgrounds; reserve them for accents and gradients.
- Do not deviate from the specified font families; PPNeueMontreal and Roobert define the typographic voice.
- Do not use generic box shadows; elevation is primarily achieved through background color shifts and borders.
- Avoid overuse of the vivid accent colors; their power comes from strategic placement to highlight key information.
- Do not apply `letterSpacing: 0` to large headlines; the distinctive negative letter spacing of Roobert is crucial.
- Do not use a solid background color for the 'apps & agents' portion of the main hero headline; it must retain its gradient fill.

## Imagery

The visual language focuses on abstract, geometric patterns and subtle product illustrations. Graphics often feature white or muted backgrounds, with elements constructed from simple shapes and lines, frequently incorporating the brand's vibrant accent colors and gradients. Treatment typically isolates elements against a clean backdrop, avoiding busy compositions. Icons are outlined or filled in a minimalist style, often monochromatic or using a single accent color. Photography is absent; the emphasis is on schematic representations and UI mockups. The overall role is to explain technical concepts and showcase product functionality through stylized, uncluttered visuals.

## Layout

The page model is a max-width, center-aligned container for main content, providing comfortable reading width on a full-bleed white background. The hero section is full-bleed with a left-aligned, gradient-filled headline over a white background, accompanied by a stylized technical illustration on the right. Sections are clearly delineated by consistent vertical spacing, creating an airy feel. Content is primarily arranged in two-column layouts, often alternating text and image/illustration, with some sections stacking content centrally. The navigation is a sticky top bar with a left-aligned logo and right-aligned links and CTA buttons. Density is spacious, prioritizing readability and visual breathing room between blocks of information.

## Agent Prompt Guide

### Quick Color Reference
- Text: `#0d0d0d` (Charcoal Text)
- Background: `#ffffff` (White Canvas)
- CTA Background: `#0d0d0d` (Charcoal Text)
- CTA Text: `#ffffff` (White Canvas)
- Border: `#e3e3e3` (Silver Lining)
- Accent: `#8a05ff` (Grape Glow)

### 3-5 Example Component Prompts
1. **Create a hero section:** White background. Headline 'Your fastest path to production for' in Roobert, 64px, weight 400, #0d0d0d, letter-spacing -1.6px. Followed by 'apps & agents' using `linear-gradient(to right, rgb(138, 5, 255), rgb(214, 127, 46))` as foreground color, same font. Body text 'Intuitive infrastructure to scale any app or agent from your first user to your billionth.' in PPNeueMontreal, 18px, weight 400, #0d0d0d, line-height 1.33. Add a Primary Dark Button 'Start for free' and an Outline Button 'Get in touch'.
2. **Generate a feature card:** White background, 0px border-radius, 20px padding. Title 'Select a service' in Roobert, 20px, weight 400, #0d0d0d, letter-spacing -0.2px. A numeric indicator '1' in Grape Glow (`#8a05ff`), size 24px. Body text 'Choose what you need to run your apps, APIs, agent logic, databases, cron jobs, and more.' in PPNeueMontreal, 16px, weight 400, #0d0d0d, line-height 1.5. Border-bottom of the card is Silver Lining (`#e3e3e3`).
3. **Design a top navigation bar:** White background, 0px border-radius. Logo on the left, `#0d0d0d`. Navigation links 'Product', 'Pricing', 'Customers' using PPNeueMontreal, 14px, weight 500, #4d4d4d, line-height 1.25. On the far right, an Outline Button 'Sign In' and a Primary Dark Button 'Get Started'.

## Similar Brands

- **Vercel** — Shares a clean, light aesthetic with a developer-tool focus, uses strong typography, and leverages select accent colors to highlight key UI elements.
- **Supabase** — Exhibits a similar design philosophy with clear, dark text on light backgrounds and uses vibrant, often purple-hued, accent colors for interactive components and branding.
- **Figma** — Features a strong emphasis on clean, functional UI, distinct typography, and strategic use of color to differentiate features and states rather than decorative elements.
- **Railway** — Employs bold headlines, clear information hierarchy, and a restrained color palette punctuated by vibrant, often gradient-based, accents for a modern developer-centric experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-charcoal-text: #0d0d0d;
  --color-asphalt-gray: #272727;
  --color-pebble-gray: #4d4d4d;
  --color-smoke-gray: #6b6b6b;
  --color-silver-lining: #e3e3e3;
  --color-lavender-mist: #e6daff;
  --color-arctic-blue-tint: #e0f4ff;
  --color-grape-glow: #8a05ff;
  --color-sunset-violet: #d67f2;
  --gradient-sunset-violet: linear-gradient(to right, rgb(138, 5, 255), rgb(214, 127, 46));
  --color-digital-emerald: #009e7a;
  --color-deep-plum: #48008c;
  --color-crimson-spark: #e96770;
  --color-candy-pink: #f347ff;
  --color-sky-surge: #33acff;
  --color-twilight-gradient: #8a05ff;
  --gradient-twilight-gradient: linear-gradient(to right, rgb(28, 0, 55), rgb(42, 0, 82), rgb(226, 166, 110));
  --color-radiant-purple-to-pink: #9b52fb;
  --gradient-radiant-purple-to-pink: linear-gradient(to right, rgb(157, 102, 255), rgb(251, 206, 255));

  /* Typography — Font Families */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ppneuemontreal: 'PPNeueMontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ppneuemontrealmono: 'PPNeueMontrealMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: 0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.08px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1.08;
  --tracking-display: -1.6px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 937px;

  /* Named Radii */
  --radius-tags: 937px;
  --radius-buttons: 0px;
  --radius-default: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-charcoal-text: #0d0d0d;
  --color-asphalt-gray: #272727;
  --color-pebble-gray: #4d4d4d;
  --color-smoke-gray: #6b6b6b;
  --color-silver-lining: #e3e3e3;
  --color-lavender-mist: #e6daff;
  --color-arctic-blue-tint: #e0f4ff;
  --color-grape-glow: #8a05ff;
  --color-sunset-violet: #d67f2;
  --color-digital-emerald: #009e7a;
  --color-deep-plum: #48008c;
  --color-crimson-spark: #e96770;
  --color-candy-pink: #f347ff;
  --color-sky-surge: #33acff;
  --color-twilight-gradient: #8a05ff;
  --color-radiant-purple-to-pink: #9b52fb;

  /* Typography */
  --font-roobert: 'Roobert', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ppneuemontreal: 'PPNeueMontreal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ppneuemontrealmono: 'PPNeueMontrealMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.43;
  --tracking-caption: 0.24px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.14px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 0.08px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.2px;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.15;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1.08;
  --tracking-display: -1.6px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-60: 60px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-full: 937px;
}
```
