# Employment Hero — Style Reference
> Vivid violet productivity canvas

**Theme:** light

Employment Hero employs a vibrant, confident design language using a clean white canvas offset by a dominant, vivid violet. Typography is bold and assertive for headlines, while functional elements remain crisp and legible. Components exhibit softer, rounded edges for approachability, and subtle background tints introduce visual segmentation without heavy dividers, creating a sense of clarity and focused information presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Violet Empress | `#7622d7` | `--color-violet-empress` | Primary action buttons, accented links, interactive elements — a deep, vivid violet that energizes the UI |
| Lavender Mist | `#e6d5fe` | `--color-lavender-mist` | Subtle borders, interactive highlights, and soft background accents, providing a muted counterpoint to Violet Empress |
| Deep Violet | `#460078` | `--color-deep-violet` | Background for bold hero sections or prominent feature blocks, adding depth to the violet palette |
| Cybernetic Green | `#94e022` | `--color-cybernetic-green` | Green action color for filled buttons, selected navigation states, and focused conversion moments. Use as a supporting accent, not as a status color |
| Obsidian | `#000000` | `--color-obsidian` | Primary text for headlines and prominent UI labels, ensuring maximum contrast |
| Ghost White | `#ffffff` | `--color-ghost-white` | Page backgrounds, card surfaces, and text on darker backgrounds |
| Whisper Lilac | `#f9f5ff` | `--color-whisper-lilac` | Subtle card backgrounds, section separators, and hover states, providing soft visual distinction |
| Near Black | `#121214` | `--color-near-black` | Secondary text, descriptive body copy, and icons, offering readability without harshness |
| Silver Thread | `#e4e4e7` | `--color-silver-thread` | Subtle borders, dividers, and input field outlines, providing soft structure |
| Stone Gray | `#71717a` | `--color-stone-gray` | Tertiary text, helper text, and disabled states, receding gracefully into the background |
| Cloud Gray | `#a9a9b2` | `--color-cloud-gray` | Placeholder text and subtle input borders, hinting at interactivity |
| Dark Charcoal | `#27272a` | `--color-dark-charcoal` | Darker background accents, subtle text for contrast on lighter elements |
| AI Gradient | `linear-gradient(90deg, rgb(154, 88, 252), rgb(112, 221, 255), rgb(230, 213, 254), rgb(186, 252, 88), rgb(154, 88, 252))` | `--color-ai-gradient` | Decorative background for featured sections and badges, symbolizing technological fluidity and motion |
| Region Banner | `#f0e6fa` | `--color-region-banner` | Background for regional information banners |
| Info Banner | `#280541` | `--color-info-banner` | Violet wash for highlight backgrounds, decorative bands, and soft emphasis behind content |

## Tokens — Typography

### Saiga — Display and primary headlines — custom font with tight tracking and a bold presence, establishing a modern, authoritative voice. The higher weights, up to 1000, create a robust visual impact. · `--font-saiga`
- **Substitute:** Montserrat
- **Weights:** 300, 500, 600, 700, 800, 900, 1000
- **Sizes:** 18px, 24px, 28px, 32px, 38px, 42px, 60px, 80px
- **Line height:** 1.06, 1.08, 1.10, 1.14, 1.25, 1.55
- **Letter spacing:** -0.008em at 80px, -0.007em at 60px, -0.006em at 42px, -0.005em at 38px, -0.003em at 32px, -0.002em at 28px
- **Role:** Display and primary headlines — custom font with tight tracking and a bold presence, establishing a modern, authoritative voice. The higher weights, up to 1000, create a robust visual impact.

### DM Sans — Body copy, subheadings, interface labels, and buttons — a highly legible and versatile sans-serif that balances the impact of Saiga. · `--font-dm-sans`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600, 700, 800, 900
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 24px, 28px, 36px
- **Line height:** 1.00, 1.13, 1.14, 1.25, 1.33, 1.43, 1.50, 1.55, 1.67, 2.67
- **Letter spacing:** normal
- **Role:** Body copy, subheadings, interface labels, and buttons — a highly legible and versatile sans-serif that balances the impact of Saiga.

### Arial — Utility text for small components like quick actions, certain input fields, or system messages, ensuring ubiquitous availability. · `--font-arial`
- **Weights:** 400, 600
- **Sizes:** 13px, 16px
- **Line height:** 1.00, 1.20
- **Letter spacing:** normal
- **Role:** Utility text for small components like quick actions, certain input fields, or system messages, ensuring ubiquitous availability.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 18px | 1.55 | -0.002px | `--text-body-lg` |
| subheading | 24px | 1.14 | — | `--text-subheading` |
| heading-sm | 28px | 1.14 | -0.002px | `--text-heading-sm` |
| heading | 36px | 1.14 | — | `--text-heading` |
| heading-lg | 42px | 1.1 | -0.006px | `--text-heading-lg` |
| display | 80px | 1.06 | -0.008px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 9999px |
| images | 8px |
| inputs | 6px |
| buttons | 32px |
| default | 8px |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 32px
- **Card padding:** 24px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Main call-to-action throughout the site.

Filled with Violet Empress (#7622d7), white text, fully rounded (32px radius). Padding: 14px vertical, 24px horizontal. Text uses DM Sans.

### Ghost Action Button (White)
**Role:** Secondary calls-to-action on dark backgrounds.

Transparent background, white text, 4px radius. No internal padding, relying on external layout. Text uses DM Sans.

### Outlined Action Button
**Role:** Secondary calls-to-action on light backgrounds.

White background, text in Violet Empress (#7622d7), 12px radius. Padding: 0px vertical, 12px horizontal. Border is 1px Violet Empress. Text uses DM Sans.

### Region Selector Button
**Role:** Small, outlined button for changing region.

Transparent background, white text, 32px radius. Border is 1px Silver Thread (#f4f4f5). Padding: 6px vertical, 16px horizontal. Text uses DM Sans.

### Clean Card
**Role:** Content container without visual hierarchy.

Transparent background, 0px border radius, no shadow. Internal content padding is 40px top, 20px bottom, 0px horizontal.

### Elevated Card
**Role:** Standard content container to highlight information.

Ghost White (#ffffff) background, 12px border radius, no shadow. No internal padding, content provides its own layout.

### Soft Tint Card
**Role:** Segmented content areas for features or categories.

Whisper Lilac (#f9f5ff) background, 20px border radius, no shadow. No internal padding, content provides its own layout.

### Minimal Input Field
**Role:** Text input fields for forms.

Transparent background, Dark Charcoal (#27272a) text. Border bottom is 1px Dark Charcoal. No radius. Padding: 0px top, 8px right, 8px bottom, 0px left. DM Sans font.

### Bordered Input Field
**Role:** Standard input fields for user data.

Transparent background, Near Black (#27272a) text. Border is 1px Cloud Gray (#a9a9b2), 6px radius. Padding: 8px vertical, 12px left, 36px right. DM Sans font.

### Gradient AI Badge
**Role:** Visual indicator for AI-driven features.

Transparent background with the AI Gradient applied as a border or background image. Text in Near Black (#121214), 9999px (pill-shaped) border radius. No padding, uses intrinsic text sizing.

## Do's and Don'ts

### Do
- Prioritize Violet Empress (#7622d7) for all primary calls-to-action and critical interactive elements.
- Use Saiga for all display and large headlines, applying tight letter-spacing for visual impact.
- Utilize DM Sans (weights 400-600) for all body text, subheadings, and interface components, preferring normal letter-spacing for legibility.
- Apply a 32px border-radius to all primary buttons for a soft, approachable feel.
- Separate content sections with subtle Whisper Lilac (#f9f5ff) background fills or by increasing vertical spacing using a 32px sectionGap.
- For all text, ensure sufficient contrast by pairing with Obsidian (#000000) for headlines and Near Black (#121214) for body copy on light backgrounds.
- Employ the AI Gradient for decorative elements such as badges or subtle background washes, to reinforce the brand's AI theme.

### Don't
- Avoid generic system fonts for prominent headlines; Saiga is a key brand identifier.
- Do not use harsh, square corners; adhere to the established radii of 8px for general elements, 12px for cards, and 32px for buttons.
- Refrain from introducing new accent colors outside of Violet Empress (#7622d7) or Cybernetic Green (#94e022).
- Avoid heavy drop shadows or glows; the design system favors clean, flat surfaces and subtle background tints for hierarchy.
- Do not use small text sizes (below 14px DM Sans) for critical information; prioritize readability over density.
- Do not use black backgrounds except for specific, deeply intentional hero sections or banners where Deep Violet or Info Banner colors are preferred.
- Do not deviate from the defined spacing scale; maintain comfortable density with elementGap at 4px and cardPadding at 24px.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Ghost White Canvas | `#ffffff` | Primary page background, providing a clean, bright foundation for all content. |
| 2 | Whisper Lilac Card | `#f9f5ff` | Background for feature cards and distinct content blocks, offering a soft visual separation from the main canvas without harsh lines. |
| 3 | Soft Tint Hero | `#9a58fc` | Background for prominent hero sections, badges, or informational banners, adding deeper brand color saturation. |

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #e4e4e7
accent: #e6d5fe
primary action: #7622d7 (filled action)

Example Component Prompts:
1. Create a Primary Action Button labeled 'Request a demo': Violet Empress (#7622d7) background, white text, 32px radius, 14px vertical padding, 24px horizontal padding, DM Sans font. 
2. Create a Soft Tint Card: Whisper Lilac (#f9f5ff) background, 20px border radius, no internal padding. Place a heading 'FOR BUSINESSES' using Saiga weight 700, 24px, #000000, 40px top padding.
3. Create a Ghost Action Link labeled 'Learn more': Transparent background, white text, 4px radius, DM Sans font, no padding.
4. Create a Bordered Input Field: Transparent background, 1px Cloud Gray (#a9a9b2) border, 6px radius, 8px vertical padding, 12px left padding, DM Sans font. The placeholder text should be Stone Gray (#71717a).

## Similar Brands

- **Rippling** — Clean white background, vibrant accent color for CTAs, and a focus on product visuals within device mocks.
- **Deel** — Use of bold sans-serif headlines, strong brand color accents, and a direct, confident tone.
- **Gusto** — Friendly, approachable aesthetic for HR/Payroll software, with clear information hierarchy on a light canvas.
- **Carta** — Modern, crisp typography for a B2B SaaS platform, with emphasis on clarity and subtle use of color for functional elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-violet-empress: #7622d7;
  --color-lavender-mist: #e6d5fe;
  --color-deep-violet: #460078;
  --color-cybernetic-green: #94e022;
  --color-obsidian: #000000;
  --color-ghost-white: #ffffff;
  --color-whisper-lilac: #f9f5ff;
  --color-near-black: #121214;
  --color-silver-thread: #e4e4e7;
  --color-stone-gray: #71717a;
  --color-cloud-gray: #a9a9b2;
  --color-dark-charcoal: #27272a;
  --color-ai-gradient: #9a58fc;
  --gradient-ai-gradient: linear-gradient(90deg, rgb(154, 88, 252), rgb(112, 221, 255), rgb(230, 213, 254), rgb(186, 252, 88), rgb(154, 88, 252));
  --color-region-banner: #f0e6fa;
  --color-info-banner: #280541;

  /* Typography — Font Families */
  --font-saiga: 'Saiga', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.55;
  --tracking-body-lg: -0.002px;
  --text-subheading: 24px;
  --leading-subheading: 1.14;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.14;
  --tracking-heading-sm: -0.002px;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.006px;
  --text-display: 80px;
  --leading-display: 1.06;
  --tracking-display: -0.008px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;
  --font-weight-black: 900;
  --font-weight-w1000: 1000;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 32px;
  --card-padding: 24px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-full: 50px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 9999px;
  --radius-images: 8px;
  --radius-inputs: 6px;
  --radius-buttons: 32px;
  --radius-default: 8px;

  /* Surfaces */
  --surface-ghost-white-canvas: #ffffff;
  --surface-whisper-lilac-card: #f9f5ff;
  --surface-soft-tint-hero: #9a58fc;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-violet-empress: #7622d7;
  --color-lavender-mist: #e6d5fe;
  --color-deep-violet: #460078;
  --color-cybernetic-green: #94e022;
  --color-obsidian: #000000;
  --color-ghost-white: #ffffff;
  --color-whisper-lilac: #f9f5ff;
  --color-near-black: #121214;
  --color-silver-thread: #e4e4e7;
  --color-stone-gray: #71717a;
  --color-cloud-gray: #a9a9b2;
  --color-dark-charcoal: #27272a;
  --color-ai-gradient: #9a58fc;
  --color-region-banner: #f0e6fa;
  --color-info-banner: #280541;

  /* Typography */
  --font-saiga: 'Saiga', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 18px;
  --leading-body-lg: 1.55;
  --tracking-body-lg: -0.002px;
  --text-subheading: 24px;
  --leading-subheading: 1.14;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.14;
  --tracking-heading-sm: -0.002px;
  --text-heading: 36px;
  --leading-heading: 1.14;
  --text-heading-lg: 42px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.006px;
  --text-display: 80px;
  --leading-display: 1.06;
  --tracking-display: -0.008px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 28px;
  --radius-3xl-2: 32px;
  --radius-full: 50px;
  --radius-full-2: 9999px;
}
```
