# August Health EHR — Style Reference
> Softly curved canvases on a clean sheet

**Theme:** light

August Health evokes a vibrant, healthcare-modern aesthetic, blending a clean white canvas with bursts of vivid, friendly colors. The system utilizes generous whitespace and soft-edged containers to create a sense of calm and approachability. Typography is a confident mix of a refined serif for headlines and a functional sans-serif for body text, maintaining legibility across diverse content. Components are lightweight, often presented as ghost elements or solid pops of color, contributing to a fluid, less-is-more interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#080331` | `--color-midnight-ink` | Primary text, deep navy accent outlines for interactive elements, navigation borders |
| Regal Violet | `#1b1463` | `--color-regal-violet` | Background for secondary navigation elements and subtle accent fills |
| Forest Fern | `#328a3b` | `--color-forest-fern` | Green action color for filled buttons, selected navigation states, and focused conversion moments |
| Sky Blue | `#4865ff` | `--color-sky-blue` | Primary Call-to-Action button background, interactive link color, icon fill |
| Deep Moss | `#0d5238` | `--color-deep-moss` | Footer background, providing a grounded contrast |
| Sunset Orange | `#ff6d39` | `--color-sunset-orange` | Accent background for cards and illustrative elements, used for cautionary or highlighted components |
| Blush Pink | `#f098d7` | `--color-blush-pink` | Accent background for cards and illustrative elements, providing a soft thematic variant |
| Vivid Green | `#114e0b` | `--color-vivid-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Lavender Bloom | `#ffaefe` | `--color-lavender-bloom` | Accent background for illustrative elements and selected interactive states |
| Outline Blue | `#a2baff` | `--color-outline-blue` | Border for ghost buttons and outlined interactive elements, indicating hover or focus |
| Hint of Blue | `#dce4fb` | `--color-hint-of-blue` | Subtle text color for badges, hinting at an informational status |
| Vibrant Orange | `#f65300` | `--color-vibrant-orange` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Do not promote it to the primary CTA color |
| Pitch Black | `#000000` | `--color-pitch-black` | Critical text elements, strong borders, and default icon fills |
| Pure Canvas | `#ffffff` | `--color-pure-canvas` | Page backgrounds, card surfaces, and primary text on dark backgrounds |
| Light Gray | `#cccccc` | `--color-light-gray` | Dividers and subtle borders for outlines |
| Warm Sand | `#f8f3eb` | `--color-warm-sand` | Secondary background for sections and elevated textured surfaces |
| Dark Charcoal | `#333333` | `--color-dark-charcoal` | Secondary text and icon elements offering contrast against lighter backgrounds |
| Muted Stone | `#eae4d9` | `--color-muted-stone` | Subtle background tones, almost invisible borders, providing depth |
| Gradient Aura | `linear-gradient(121deg, rgb(204, 122, 181) -80.58%, rgb(72, 101, 255) 36.36%, rgb(27, 20, 99) 102.7%)` | `--color-gradient-aura` | Dynamic background fill in hero sections and prominent visual highlights |

## Tokens — Typography

### Saans — Functional sans-serif for body text, navigation items, buttons, and detailed content. Its clear forms support readability across transactional and informational sections. · `--font-saans`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 20px, 24px
- **Line height:** 1.00, 1.10, 1.30, 1.40, 1.60
- **Letter spacing:** normal
- **Role:** Functional sans-serif for body text, navigation items, buttons, and detailed content. Its clear forms support readability across transactional and informational sections.

### Reckless Neue — Elegant serif with expressive character, reserved for prominent headlines and brand statements. Its lighter weight for display ensures a sophisticated, inviting tone rather than heavy impact. · `--font-reckless-neue`
- **Substitute:** Lora
- **Weights:** 400
- **Sizes:** 24px, 32px, 48px, 64px
- **Line height:** 1.00, 1.10, 1.30
- **Letter spacing:** normal
- **Role:** Elegant serif with expressive character, reserved for prominent headlines and brand statements. Its lighter weight for display ensures a sophisticated, inviting tone rather than heavy impact.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.3 | — | `--text-body` |
| subheading | 20px | 1.1 | — | `--text-subheading` |
| heading-sm | 24px | 1 | — | `--text-heading-sm` |
| heading | 32px | 1.1 | — | `--text-heading` |
| heading-lg | 48px | 1 | — | `--text-heading-lg` |
| display | 64px | 1 | — | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 128 | 128px | `--spacing-128` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| links | 24px |
| badges | 1600px |
| buttons | 1600px |
| navigation | 100px |
| miscellaneous | 48px |
| decorative_elements | 3200px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| lg | `rgba(75, 68, 57, 0.1) 0px 12px 24px 0px, rgba(75, 68, 57,...` | `--shadow-lg` |
| sm | `rgba(75, 68, 57, 0.05) 0px 4px 4px 0px, rgba(75, 68, 57, ...` | `--shadow-sm` |
| md | `rgba(99, 91, 79, 0.08) 0px 8px 16px 0px, rgba(99, 91, 79,...` | `--shadow-md` |
| xl | `rgba(75, 68, 57, 0.1) 0px 48px 48px 0px` | `--shadow-xl` |

### Layout

- **Section gap:** 64px
- **Card padding:** 32px
- **Element gap:** 16px

## Components

### Ghost Button
**Role:** Outline button with Brand Blue text, often used for secondary actions or navigation links.

Background: transparent, Text: #080331 (Midnight Ink), Border: 1px solid #080331 (Midnight Ink), Radius: 1600px, Padding: 12px vertical, 16px horizontal.

### Primary Call-to-Action Button
**Role:** Prominent, filled button for main user actions.

Background: #4865ff (Sky Blue), Text: #ffffff (Pure Canvas), Border: 1px solid #ffffff (Pure Canvas), Radius: 1600px, Padding: 16px vertical, 40px horizontal.

### Themed Card (Green)
**Role:** Educational or feature card with a distinct brand color.

Background: #328a3b (Forest Fern), Border: none, Radius: 16px, Padding: 24px.

### Themed Card (Orange)
**Role:** Highlight card drawing attention to specific content.

Background: #ff6d39 (Sunset Orange), Border: none, Radius: 16px, Padding: 24px.

### Compact Badge
**Role:** Small, informative label.

Background: transparent, Text: #000000 (Pitch Black), Radius: 1600px, Padding: 10px vertical, 16px horizontal.

### Feature Card (Subtle Blush)
**Role:** Highlight card with a soft, engaging color.

Background: #f098d7 (Blush Pink), Border: none, Radius: 16px, Padding: 24px.

### Themed Green Button
**Role:** Action button indicating success or positive affirmation.

Background: #114e0b (Vivid Green), Text: #ffffff (Pure Canvas), Border: 1px solid #ffffff (Pure Canvas), Radius: 16px, Padding: 32px vertical, 32px horizontal.

### Themed Orange Button
**Role:** Action button used for warnings or prominent secondary interactions.

Background: #ff6d39 (Sunset Orange), Text: #000000 (Pitch Black), Border: 1px solid #000000 (Pitch Black), Radius: 16px, Padding: 32px vertical, 32px horizontal.

## Do's and Don'ts

### Do
- Prioritize Reckless Neue for all headlines (24px-64px, weight 400), Saans for all body text (12px-24px, weights 400-500).
- Use Pure Canvas (#ffffff) extensively as the primary background for content sections to maintain an open, clean aesthetic.
- Accent actions and key interactive elements exclusively with Sky Blue (#4865ff).
- Incorporate Warm Sand (#f8f3eb) for subtle shifts in background or elevated sections to add texture without heavy contrast.
- Apply a generous border-radius of 1600px to all buttons and badges for a soft, approachable feel.
- Utilize a base spacing unit of 8px, with element gaps typically at 16px and card padding at 32px.
- Ensure text contrast with Midnight Ink (#080331) or Pitch Black (#000000) on light backgrounds, and Pure Canvas (#ffffff) on colored backgrounds.

### Don't
- Avoid using multiple vibrant chromatic colors in close proximity; maintain a restrained palette with one primary accent color.
- Do not introduce strong, dark shadows; instead, use the subtle, layered shadow styles for buttons rgba(75, 68, 57, 0.1) 0px 12px 24px 0px, rgba(75, 68, 57, 0.1) 0px 48px 48px 0px when elevation is needed.
- Refrain from using strong visual dividers between sections; rely on background color changes (e.g., Pure Canvas to Warm Sand) and spacing to delineate content.
- Do not use highly saturated brand colors for extensive text blocks; reserve them for highlights, buttons, and decorative elements.
- Avoid sharp corners; a minimum radius of 16px should be applied to cards and containers to maintain softness.
- Do not use generic system fonts; stick to Saans for body text and Reckless Neue for headlines.
- Do not introduce heavy borders or outlines for cards; they should appear as floating elements or have only subtle background changes.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pure Canvas | `#ffffff` | Base page background |
| 1 | Warm Sand | `#f8f3eb` | Secondary background for sections, often housing cards or distinct content blocks |
| 2 | Gradient Aura | `#c87ab5` | Elevated, highly prominent backgrounds for hero sections or brand-defining visual elements, featuring a dynamic linear gradient. |

## Elevation

- **Button (prominent):** `rgba(75, 68, 57, 0.1) 0px 12px 24px 0px, rgba(75, 68, 57, 0.1) 0px 48px 48px 0px`
- **Card (highlighted):** `rgba(75, 68, 57, 0.1) 0px 48px 48px 0px`
- **Other interactive elements:** `rgba(75, 68, 57, 0.05) 0px 4px 4px 0px, rgba(75, 68, 57, 0.08) 0px 32px 16px 0px`

## Imagery

The site uses a mix of high-quality, authentic photography (lifestyle shots of caregivers and residents with genuine expressions), interspersed with abstract, colorful circular shapes that act as both masks for photography and decorative elements. Photography is typically framed by these large, soft-edged circular or blob-like masks, which bring a playful and human-centric feel. Icons are monochrome, outlined, and have a consistent stroke weight, serving a functional and supportive role rather than decorative. Imagery density is moderate, carefully balanced with significant whitespace.

## Layout

The page primarily employs a contained, centered layout, implicitly max-width, though the hero section often uses full-bleed background elements. The hero features a centered headline over a dynamic, full-bleed gradient and masked photography pattern. Sections generally adopt an alternating, 'z-pattern' content arrangement, often with text-aligned left and visual elements right, or vice-versa, creating a comfortable flow. Vertical rhythm is established through consistent section gaps and clear breaks, utilizing background color changes (Pure Canvas and Warm Sand) rather than strong dividers. Navigation is a sticky top bar, providing persistent access.

## Agent Prompt Guide

### Quick Color Reference
- text: #080331
- background: #ffffff
- border: #cccccc
- accent: #ff6d39
- primary action: #4865ff (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #4865ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a feature card for 'Move-Ins': Pure Canvas background, 16px radius, 32px padding all around. Headline 'Move-Ins' at 24px Reckless Neue weight 400, #080331. Body text 'Fully-digital move-in experiences that families love...' at 16px Saans weight 400, #080331. Include a Ghost Button for more details: transparent background, #080331 text, 1px solid #080331 border, 16px vertical and 24px horizontal padding, 1600px radius.
3. Create a navigation bar item: Text 'Platform' at 16px Saans weight 500, #080331. Underline on hover with Sky Blue. Add an internal element gap of 8px between text and a small icon.

## Similar Brands

- **Rippling** — Similar approach to clean white layouts with prominent, playful use of organic shapes and vibrant brand colors as accents.
- **Notion** — Emphasizes abundant whitespace, minimalist UI, and a clear functional aesthetic with soft-edged components.
- **Webflow** — Features a strong, elegant serif for headlines combined with a clean sans-serif for body, creating a sophisticated yet approachable online presence.
- **Klaviyo** — Uses bright, distinct brand colors for calls-to-action against a largely neutral background, creating visual pops strategically.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #080331;
  --color-regal-violet: #1b1463;
  --color-forest-fern: #328a3b;
  --color-sky-blue: #4865ff;
  --color-deep-moss: #0d5238;
  --color-sunset-orange: #ff6d39;
  --color-blush-pink: #f098d7;
  --color-vivid-green: #114e0b;
  --color-lavender-bloom: #ffaefe;
  --color-outline-blue: #a2baff;
  --color-hint-of-blue: #dce4fb;
  --color-vibrant-orange: #f65300;
  --color-pitch-black: #000000;
  --color-pure-canvas: #ffffff;
  --color-light-gray: #cccccc;
  --color-warm-sand: #f8f3eb;
  --color-dark-charcoal: #333333;
  --color-muted-stone: #eae4d9;
  --color-gradient-aura: #c87ab5;
  --gradient-gradient-aura: linear-gradient(121deg, rgb(204, 122, 181) -80.58%, rgb(72, 101, 255) 36.36%, rgb(27, 20, 99) 102.7%);

  /* Typography — Font Families */
  --font-saans: 'Saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless-neue: 'Reckless Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 32px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 100px;
  --radius-full-3: 1600px;
  --radius-full-4: 3200px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-links: 24px;
  --radius-badges: 1600px;
  --radius-buttons: 1600px;
  --radius-navigation: 100px;
  --radius-miscellaneous: 48px;
  --radius-decorativeelements: 3200px;

  /* Shadows */
  --shadow-lg: rgba(75, 68, 57, 0.1) 0px 12px 24px 0px, rgba(75, 68, 57, 0.1) 0px 48px 48px 0px;
  --shadow-sm: rgba(75, 68, 57, 0.05) 0px 4px 4px 0px, rgba(75, 68, 57, 0.08) 0px 32px 16px 0px;
  --shadow-md: rgba(99, 91, 79, 0.08) 0px 8px 16px 0px, rgba(99, 91, 79, 0.04) 0px 32px 32px 0px;
  --shadow-xl: rgba(75, 68, 57, 0.1) 0px 48px 48px 0px;

  /* Surfaces */
  --surface-pure-canvas: #ffffff;
  --surface-warm-sand: #f8f3eb;
  --surface-gradient-aura: #c87ab5;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #080331;
  --color-regal-violet: #1b1463;
  --color-forest-fern: #328a3b;
  --color-sky-blue: #4865ff;
  --color-deep-moss: #0d5238;
  --color-sunset-orange: #ff6d39;
  --color-blush-pink: #f098d7;
  --color-vivid-green: #114e0b;
  --color-lavender-bloom: #ffaefe;
  --color-outline-blue: #a2baff;
  --color-hint-of-blue: #dce4fb;
  --color-vibrant-orange: #f65300;
  --color-pitch-black: #000000;
  --color-pure-canvas: #ffffff;
  --color-light-gray: #cccccc;
  --color-warm-sand: #f8f3eb;
  --color-dark-charcoal: #333333;
  --color-muted-stone: #eae4d9;
  --color-gradient-aura: #c87ab5;

  /* Typography */
  --font-saans: 'Saans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-reckless-neue: 'Reckless Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.3;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1;
  --text-heading: 32px;
  --leading-heading: 1.1;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1;
  --text-display: 64px;
  --leading-display: 1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-128: 128px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 48px;
  --radius-full-2: 100px;
  --radius-full-3: 1600px;
  --radius-full-4: 3200px;

  /* Shadows */
  --shadow-lg: rgba(75, 68, 57, 0.1) 0px 12px 24px 0px, rgba(75, 68, 57, 0.1) 0px 48px 48px 0px;
  --shadow-sm: rgba(75, 68, 57, 0.05) 0px 4px 4px 0px, rgba(75, 68, 57, 0.08) 0px 32px 16px 0px;
  --shadow-md: rgba(99, 91, 79, 0.08) 0px 8px 16px 0px, rgba(99, 91, 79, 0.04) 0px 32px 32px 0px;
  --shadow-xl: rgba(75, 68, 57, 0.1) 0px 48px 48px 0px;
}
```
