# The Leap — Style Reference
> Playful digital canvas: light, rounded, and vividly accented.

**Theme:** light

The Leap channels a vibrant, upbeat digital playground aesthetic through a light canvas, rounded organic shapes, and a playful brand palette. Typography uses custom, expressive sans-serifs, reserving a sophisticated serif for display headings. Surfaces are flat and borderless, relying on soft elevation and vivid background gradients to define regions. The system embraces a joyful, approachable tone, making heavy use of a bright yellow-green accent for calls to action and highlights, contrasting with a deep, muted brown for primary text. Design elements feel organic and friendly, avoiding sharp angles or heavy dividers.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Earth Clay | `#482317` | `--color-earth-clay` | Primary text, prominent links, heading, and subtle outlined borders. This deep, muted brown provides a grounded contrast to the otherwise light and vibrant palette |
| Lemon Zest | `#ecf956` | `--color-lemon-zest` | Primary calls to action, active navigation states, and highlight backgrounds. This vivid yellow-green injects energy and a playful urgency into interactive elements |
| Sky Mist | `#b1dcfc` | `--color-sky-mist` | Background for secondary cards or content sections, offering a cool, muted contrast to the warmer greens and yellows |
| Lime Spritz | `linear-gradient(323deg, rgb(198, 229, 125) 17.8%, rgb(239, 237, 238) 70.54%)` | `--color-lime-spritz` | Decorative card backgrounds and gradient components, contributing to the fresh, vibrant feel; Accent gradient for specific sections, blending earthy green with soft gray |
| Meadow Glow | `#f3fb9a` | `--color-meadow-glow` | Secondary card backgrounds and visual accents, deepening the site's overall green-yellow thematic |
| Page Canvas | `#e5e7eb` | `--color-page-canvas` | Dominant page background, neutral borders, and subtle separators. This light gray serves as the primary canvas for the UI |
| Whisper White | `#fafafa` | `--color-whisper-white` | Card backgrounds and secondary surface elements, providing a slightly brighter white for content areas |
| Lavender Bloom Gradient | `linear-gradient(129deg, rgb(243, 232, 243) 24.01%, rgb(223, 245, 221) 96.01%)` | `--color-lavender-bloom-gradient` | Background gradient for hero sections and prominent visual areas, creating a soft, organic wash of color |
| Sky Burst Gradient | `linear-gradient(0deg, rgb(239, 237, 238), rgb(41, 167, 255) 100.05%)` | `--color-sky-burst-gradient` | Dynamic visual gradients hinting at interactivity or depth |

## Tokens — Typography

### Favorit — Body text and user interface elements. This custom sans-serif brings a friendly, approachable tone to detailed information and controls. · `--font-favorit`
- **Substitute:** Inter
- **Weights:** 350, 400
- **Sizes:** 13px, 15px, 16px, 20px, 29px
- **Line height:** 1.00, 1.50
- **Letter spacing:** 0.13, 0.15, 0.13, 0.2, -0.435
- **Role:** Body text and user interface elements. This custom sans-serif brings a friendly, approachable tone to detailed information and controls.

### ABC Favorit — Subheadings, specific callouts, and secondary buttons. It extends the Favorit family with slightly more robust proportions for mid-size text. · `--font-abc-favorit`
- **Substitute:** Inter
- **Weights:** 350, 400
- **Sizes:** 14px, 15px, 16px, 20px, 22px, 25px, 27px, 30px
- **Line height:** 1.00, 1.07, 1.20
- **Letter spacing:** 0.14, 0.15, 0.14, 0.2, 0.22, 0.175, -0.54, -0.6
- **Role:** Subheadings, specific callouts, and secondary buttons. It extends the Favorit family with slightly more robust proportions for mid-size text.

### Favorit-Bold — Section titles and emphasized short phrases. Its bold weight brings hierarchy and impact without losing the friendly character. · `--font-favorit-bold`
- **Substitute:** Inter
- **Weights:** 700
- **Sizes:** 18px, 24px
- **Line height:** 1.00, 1.20
- **Letter spacing:** 0.18, -0.888
- **Role:** Section titles and emphasized short phrases. Its bold weight brings hierarchy and impact without losing the friendly character.

### Tobias — Hero and display headings. This light-weight serif exudes a refined confidence, creating a distinctive and memorable brand voice. · `--font-tobias`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 54px, 60px, 70px
- **Line height:** 1.03, 1.20
- **Letter spacing:** -1.08, -1.2, -1.4
- **Role:** Hero and display headings. This light-weight serif exudes a refined confidence, creating a distinctive and memorable brand voice.

### Favorit-Regular — Specific iconography and decorative text elements. Provides a consistent base for small, functional text. · `--font-favorit-regular`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.20
- **Letter spacing:** 0.16
- **Role:** Specific iconography and decorative text elements. Provides a consistent base for small, functional text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1 | 0.13px | `--text-caption` |
| body-sm | 15px | 1 | 0.15px | `--text-body-sm` |
| subheading | 20px | 1.2 | 0.2px | `--text-subheading` |
| heading | 24px | 1 | -0.888px | `--text-heading` |
| heading-lg | 29px | 1 | -0.435px | `--text-heading-lg` |
| display | 60px | 1.03 | -1.2px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 22 | 22px | `--spacing-22` |
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 30px |
| badges | 100px |
| buttons | 100px |
| elements | 30px |
| navigation | 20px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) ...` | `--shadow-sm` |

### Layout

- **Section gap:** 24px
- **Card padding:** 30px
- **Element gap:** 16px

## Components

### Primary Action Button
**Role:** Call to action

Filled button with 'Lemon Zest' (#ecf956) background, 'Earth Clay' (#482317) text, and a highly rounded '100px' border-radius. Padding is 10px top / 7px bottom, 30px horizontal, creating an elongated, soft pill shape. Text uses ABC Favorit weight 400.

### Navigation Link
**Role:** Navigation element

Text link using Favorit font, weight 350, with 'Earth Clay' (#482317) color. No background, minimal padding, and an implicit active state shown through 'Lemon Zest' (#ecf956) backgrounds in specific contexts.

### Standard Content Card
**Role:** Content container

Utilizes 'Whisper White' (#fafafa) background, '30px' border-radius, and no explicit border or shadow, relying on spacing and background contrast for definition. Inner padding is '40px' all around.

### Review Card
**Role:** Testimonial display

Features 'Whisper White' (#fafafa) background, a '15px' border-radius, and no shadow. Internal padding is tighter at '15px' vertical and '22px' horizontal.

### Featured Content Card
**Role:** Prominent content container

Uses 'Whisper White' (#fafafa) background with a '30px' border-radius, similar to standard but with more generous '53px' vertical and '50px' horizontal padding.

### Highlight Card
**Role:** Decorative content block

A visually distinct card with 'Sky Mist' (#b1dcfc) background and a '28px' border-radius. It appears to act as a background element for layered content, featuring no explicit padding as the inner content dictates spacing.

## Do's and Don'ts

### Do
- Prioritize 'Earth Clay' (#482317) for all primary text and 'Lemon Zest' (#ecf956) for primary interactive elements.
- Use 'Tobias' weight 300 for significant display headings, emphasizing its unique character and light visual weight.
- Apply a '100px' border-radius to buttons and tags to maintain the soft, playful aesthetic.
- Layer text on 'Page Canvas' (#e5e7eb) or 'Whisper White' (#fafafa) for optimal contrast, ensuring readability for smaller text sizes.
- Employ linear gradients like 'Lavender Bloom Gradient' for backgrounds to create subtle depth and organic visual interest.
- Maintain a comfortable density with an 'elementGap' of '16px' and 'cardPadding' of '30px' for most content blocks.

### Don't
- Avoid sharp corners; all functional elements like cards and buttons should use generous border-radii (e.g., 30px or 100px).
- Do not use dark or opaque backgrounds for body text; maintain the light theme with high contrast text on pale surfaces.
- Refrain from heavy drop shadows; rely on background gradients and distinct background colors for visual separation.
- Do not introduce new typefaces; utilize the established Favorit and Tobias families exclusively.
- Avoid overly dense layouts; use generous spacing including a 'sectionGap' of '24px' to provide breathing room.
- Do not use highly saturated blues or reds outside of the approved accent and semantic palettes; these would clash with the existing vibrant but pastel-influenced brand colors.

## Imagery

The site predominantly uses product screenshots and abstract, playful illustrations to convey its message. Product screenshots are typically presented as mobile device mockups, often within a blurred, pastel-gradient background, showing clear, staged UI. Illustrations are flat, geometric, and often outlined, depicting abstract concepts or simplified figures with brand colors like 'Lemon Zest' as accents. Photography is primarily lifestyle-oriented, showcasing creators, often cropped with organic, soft-edged masking or placed within decorative frames. Icons are minimalist, outlined, and mono-color, typically in 'Earth Clay'. Imagery plays a dual role: explanatory for product features and aspirational for creator lifestyle, maintaining a light, approachable density within sections.

## Layout

The page uses a full-bleed model with content centered within an implied maximum width, creating a spacious feel. The hero section features a large, sophisticated serif headline centered over a soft gradient background with a prominent product mockup on the right. Sections alternate between a light 'Page Canvas' background and soft decorative gradients. Content is often arranged in prominent two-column layouts, combining text on the left with a visual element on the right, or three-column card grids for features and testimonials. Vertical section spacing is comfortable, promoting a flow from one block to the next without harsh dividers. The sticky top navigation is minimal, featuring a discreet logo, text links, and a 'Lemon Zest' pill-shaped primary action button.

## Agent Prompt Guide

### Quick Color Reference
text: #482317
background: #e5e7eb
border: #e5e7eb
accent: #c6e57d
primary action: #ecf956 (filled action)

### 3-5 Example Component Prompts
1. Create a hero section: 'Lavender Bloom Gradient' background. Headline "Selling on social, made simple" using Tobias weight 300 at 70px, color 'Earth Clay' (#482317), letter-spacing -1.4px. Subtitle "The link-in-bio store made for selling digital products to mobile audiences." using Favorit weight 400 at 20px, color 'Earth Clay'. A Primary Action Button: 'Lemon Zest' (#ecf956) background, 'Earth Clay' (#482317) text "SIGN UP FREE", 100px radius, 10px 30px padding.
2. Design a feature card: 'Whisper White' (#fafafa) background, 30px border-radius, 40px padding. Title "Seamless customer experience" using Favorit-Bold weight 700 at 24px, color 'Earth Clay' (#482317), letter-spacing -0.888px. Body text "Create a seamless customer experience that earns you $$$, all with one simple tool." using Favorit weight 400 at 16px, color 'Earth Clay'.
3. Construct a navigation bar: 'Page Canvas' (#e5e7eb) background with a subtle nav shadow: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px. Standard navigation links "Features", "Pricing" using Favorit weight 350 at 15px, color 'Earth Clay' (#482317). A Primary Action Button "SIGN UP FREE" using 'Lemon Zest' (#ecf956) background, 'Earth Clay' (#482317) text, 100px radius, 10px 30px padding.
4. Build a testimonial card: 'Whisper White' (#fafafa) background, 15px border-radius, 15px 22px padding. Testimonial quote text "My link in bio is GORGEOUS!" using Favorit weight 400 at 16px, color 'Earth Clay' (#482317). Author name using Favorit weight 350 at 13px, color 'Earth Clay' (#482317).

## Similar Brands

- **Canva** — Shares a playful, intuitive interface with bright accent colors, soft shapes, and a focus on creative empowerment.
- **FloDesk** — Features a pastel color palette, custom typography, and a feminine, approachable aesthetic for creator-focused tools.
- **Linktree** — Employs an emphasis on clean, mobile-first design for 'link-in-bio' solutions, often featuring custom branding and high-contrast calls to action.
- **Buffer** — Uses soft illustrations, a friendly sans-serif combined with a distinctive display font, and light, spacious layouts for digital tools.
- **Notion** — Known for minimal UI complemented by expressive typography and subtle, functional color accents within a clean, productive canvas.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-earth-clay: #482317;
  --color-lemon-zest: #ecf956;
  --color-sky-mist: #b1dcfc;
  --color-lime-spritz: #c6e57d;
  --gradient-lime-spritz: linear-gradient(323deg, rgb(198, 229, 125) 17.8%, rgb(239, 237, 238) 70.54%);
  --color-meadow-glow: #f3fb9a;
  --color-page-canvas: #e5e7eb;
  --color-whisper-white: #fafafa;
  --color-lavender-bloom-gradient: #f3e8f3;
  --gradient-lavender-bloom-gradient: linear-gradient(129deg, rgb(243, 232, 243) 24.01%, rgb(223, 245, 221) 96.01%);
  --color-sky-burst-gradient: #29a7ff;
  --gradient-sky-burst-gradient: linear-gradient(0deg, rgb(239, 237, 238), rgb(41, 167, 255) 100.05%);

  /* Typography — Font Families */
  --font-favorit: 'Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-favorit: 'ABC Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-bold: 'Favorit-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tobias: 'Tobias', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-regular: 'Favorit-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1;
  --tracking-caption: 0.13px;
  --text-body-sm: 15px;
  --leading-body-sm: 1;
  --tracking-body-sm: 0.15px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.2px;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: -0.888px;
  --text-heading-lg: 29px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.435px;
  --text-display: 60px;
  --leading-display: 1.03;
  --tracking-display: -1.2px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w350: 350;
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 30px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 9px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 30px;
  --radius-badges: 100px;
  --radius-buttons: 100px;
  --radius-elements: 30px;
  --radius-navigation: 20px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-earth-clay: #482317;
  --color-lemon-zest: #ecf956;
  --color-sky-mist: #b1dcfc;
  --color-lime-spritz: #c6e57d;
  --color-meadow-glow: #f3fb9a;
  --color-page-canvas: #e5e7eb;
  --color-whisper-white: #fafafa;
  --color-lavender-bloom-gradient: #f3e8f3;
  --color-sky-burst-gradient: #29a7ff;

  /* Typography */
  --font-favorit: 'Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-abc-favorit: 'ABC Favorit', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-bold: 'Favorit-Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-tobias: 'Tobias', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-favorit-regular: 'Favorit-Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1;
  --tracking-caption: 0.13px;
  --text-body-sm: 15px;
  --leading-body-sm: 1;
  --tracking-body-sm: 0.15px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.2px;
  --text-heading: 24px;
  --leading-heading: 1;
  --tracking-heading: -0.888px;
  --text-heading-lg: 29px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.435px;
  --text-display: 60px;
  --leading-display: 1.03;
  --tracking-display: -1.2px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-22: 22px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 9px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.06) 0px 2px 4px -1px;
}
```
