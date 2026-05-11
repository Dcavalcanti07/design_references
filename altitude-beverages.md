# Altitude Beverages — Style Reference
> diffused neon glow

**Theme:** dark

Altitude's design system evokes a diffused neon glow in a dark, atmospheric setting. Signature elements include large, soft-edged cards and buttons, a muted dark background, and an interplay of blurred glass-like surfaces, creating depth without harsh shadows. Typography is a mix of clean sans-serifs and a distinctive editorial serif, often rendered in light and refined weights, contributing to a premium, understated feel. The overall visual language is designed to highlight product imagery within an almost theatrical, low-light environment.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Zero | `#000000` | `--color-absolute-zero` | Decorative borders for navigation, subtle accents |
| Night Sky | `#07060b` | `--color-night-sky` | Darkest text color for high contrast elements, primarily on light buttons |
| Cloud Mist | `#d9d9d9` | `--color-cloud-mist` | Translucent card backgrounds, muted button fills, providing a frosted glass effect |
| Ghostly Gray | `#cdcdce` | `--color-ghostly-gray` | Subtle body text for secondary information, link borders |
| Canvas White | `#fafafa` | `--color-canvas-white` | Primary background for light-themed components; text color on dark backgrounds; button backgrounds |
| Arctic Whisper | `#ddfcff` | `--color-arctic-whisper` | Minor body text, subtle fill for decorative icons; near-white with a cool tint |
| Sunrise Burst | `linear-gradient(rgb(217, 217, 217) 0%, rgba(199, 76, 23, 0.7) 100%)` | `--color-sunrise-burst` | Warm gradient accent for background imagery. Dominant color: #c74c17 (derived from avg hex from the gradient) |
| Sunset Blush | `linear-gradient(rgba(217, 217, 217, 0) 0%, rgba(168, 43, 58, 0.7) 100%)` | `--color-sunset-blush` | Reddish gradient accent for background imagery. Dominant color: #a82b3a |
| Olive Dusk | `linear-gradient(rgba(217, 217, 217, 0) 0%, rgba(190, 193, 58, 0.7) 100%)` | `--color-olive-dusk` | Greenish gradient accent for background imagery. Dominant color: #bebe3a |
| Deep Midnight Gradient | `linear-gradient(rgb(6, 5, 10) 0%, rgb(12, 12, 20) 5.43%, rgb(25, 29, 45) 12.1%, rgb(34, 40, 62) 18.86%, rgb(53, 68, 91) 25%, rgb(69, 96, 117) 32.3%, rgb(87, 119, 140) 38.7%, rgb(104, 137, 156) 44.45%, rgb(121, 150, 164) 50%, rgb(140, 162, 175) 56.05%, rgb(160, 178, 188) 62.3%, rgb(173, 190, 198) 68.4%, rgb(187, 200, 206) 75%, rgb(202, 212, 214) 80.62%, rgb(214, 219, 222) 86.41%, rgb(235, 237, 236) 93.78%, rgb(245, 246, 241) 100%)` | `--color-deep-midnight-gradient` | Dominant background gradient for page body, creating a dark, atmospheric canvas. Dominant color: #06050a |

## Tokens — Typography

### ui-sans-serif — Default body text, links, and navigational items. Used for small, functional text blocks. · `--font-ui-sans-serif`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.50
- **Letter spacing:** normal
- **Role:** Default body text, links, and navigational items. Used for small, functional text blocks.

### DepartureMono — Monospaced text for secondary information, product details, and small buttons, creating a technical, precise feel. Its tight tracking provides density without sacrificing clarity. · `--font-departuremono`
- **Substitute:** Space Mono
- **Weights:** 400
- **Sizes:** 11px, 12px, 14px, 16px
- **Line height:** 1.00, 1.06, 1.43, 1.50, 1.79, 2.33
- **Letter spacing:** -0.0710em
- **Role:** Monospaced text for secondary information, product details, and small buttons, creating a technical, precise feel. Its tight tracking provides density without sacrificing clarity.

### HelveticaNowDisplay — Display font for large headlines and prominent textual elements, commanding attention without being overtly decorative. Its condensed nature allows for impact at large sizes. · `--font-helveticanowdisplay`
- **Substitute:** Inter
- **Weights:** 400, 500, 800
- **Sizes:** 11px, 18px, 160px
- **Line height:** 0.90, 1.00
- **Letter spacing:** -0.0500em
- **Role:** Display font for large headlines and prominent textual elements, commanding attention without being overtly decorative. Its condensed nature allows for impact at large sizes.

### EditorialNew — Elegant serif for large headings, subheadings, and flavor text. The exceptionally light weight at 200 offers a whisper of sophistication, breaking from typical bold heading conventions, conveying luxury through restraint. · `--font-editorialnew`
- **Substitute:** Playfair Display
- **Weights:** 200
- **Sizes:** 14px, 16px, 40px, 60px
- **Line height:** 1.06
- **Letter spacing:** -0.0250em
- **Role:** Elegant serif for large headings, subheadings, and flavor text. The exceptionally light weight at 200 offers a whisper of sophistication, breaking from typical bold heading conventions, conveying luxury through restraint.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1 | -0.78px | `--text-caption` |
| body | 14px | 1.43 | -0.99px | `--text-body` |
| body-lg | 16px | 1.5 | -1.13px | `--text-body-lg` |
| subheading | 18px | 1 | -0.9px | `--text-subheading` |
| heading | 40px | 1.06 | -1px | `--text-heading` |
| heading-lg | 60px | 1.06 | -1.5px | `--text-heading-lg` |
| display | 160px | 0.9 | -8px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 44px |
| buttons | 100px |
| elements | 110px |
| navigation | 100px |

### Layout

- **Section gap:** 36px
- **Card padding:** 64px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call-to-action button for initiating key actions.

Background: Canvas White (#fafafa), Text: Night Sky (#07060b), Border Radius: 100px, Padding: 16px vertical, 28px horizontal.

### Ghost Nav Button
**Role:** Secondary interactive elements within navigation or subtle actions.

Background: Cloud Mist (#d9d9d9) with 30% opacity, Text: Canvas White (#fafafa) with 50% opacity, Border Radius: 100px, Padding: 17px vertical, 28px horizontal. No visible border.

### Product Info Button
**Role:** Small, information-dense buttons often associated with product details.

Background: Cloud Mist (#d9d9d9) with 30% opacity, Text: Canvas White (#fafafa), Border Radius: 44px, Padding: 36px vertical, 20px horizontal. Accommodates larger text block.

### Navigation Link (Text-only)
**Role:** Non-interactive text links within navigation or footer.

Background: transparent, Text: Canvas White (#fafafa), No border or radius, No padding.

### Product Detail Card
**Role:** Container for product information, often displayed prominently in a grid.

Background: Cloud Mist (#d9d9d9) with 30% opacity, Border Radius: 44px, Padding: 64px. No box shadow, relying on backdrop blur for depth.

### Text Input (Transparent)
**Role:** Input fields designed to blend into the background.

Background: transparent, Text: Canvas White (#fafafa), Border: 1px solid Canvas White (#fafafa) on focus, No radius, No padding. Placeholder text is Canvas White (#fafafa) with opacity.

## Do's and Don'ts

### Do
- Prioritize Cloud Mist (#d9d9d9) with 30% opacity and a backdrop filter blur for all card and container surfaces to achieve the frosted glass effect.
- Use DepartureMono at 11-16px with -0.071em letter spacing for product details, meta-information, and secondary button labels.
- Apply a 100px border-radius to all buttons and navigation elements to maintain a uniformly soft, pill-shaped aesthetic.
- Ensure all primary button text is Night Sky (#07060b) on a Canvas White (#fafafa) background for maximum contrast and readability.
- Utilize EditorialNew weight 200 for all major headlines to convey understated elegance and sophistication, avoiding heavier weights.
- Implement the Deep Midnight Gradient (#06050a start) as the primary page background to establish the atmospheric dark theme.
- Maintain a comfortable density with a base unit of 4px and elemental gaps at 16px to ensure ample breathing room around elements.

### Don't
- Do not use harsh, opaque background colors unless specifically for primary interactive elements like buttons.
- Avoid standard box-shadows; rely on the translucent background with backdrop-filter blur for depth and surface separation.
- Do not use bold or heavy weights for headlines; the brand aesthetic prioritizes lightness and restraint.
- Never introduce fully opaque borders that detract from the translucent, soft-edged component feel.
- Do not break away from the 44px or 100px border radii for cards and buttons; distinct rounding defines the brand.
- Avoid using bright, saturated single-color backgrounds for sections; leverage the provided brand gradients for visual interest.
- Do not use generic sans-serifs for primary headings unless explicitly specified; EditorialNew is critical to the brand's sophisticated voice.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#06050a` | Dominant background for the entire page, providing a deep, atmospheric foundation. |
| 1 | Frosted Surface | `#d9d9d9` | Translucent background for cards, navigation, and secondary buttons, creating layered depth with a blurred effect. |
| 2 | Interactive White | `#fafafa` | Solid background for primary calls-to-action, contrasting with the muted surfaces below. |

## Imagery

This site prominently features ultra-high-quality product photography of beverage cans, presented in highly stylized, immersive environments. Products are often cropped tightly or presented with selective focus, highlighting textures and labels. Photography is mood-driven, using dynamic lighting and rich, saturated colors (e.g., orange, red, green tones) as atmospheric backdrops for the cans, often featuring botanicals or fruits relevant to the product flavor. Imagery serves a decorative, atmospheric, and product showcase role, creating a sense of premium quality. Density is moderate, with large hero images and product visuals taking up significant screen real estate, balanced by short textual descriptions.

## Layout

The page uses a full-bleed layout for background gradients and imagery, creating an immersive experience. Content is subtly constrained to a comfortable width, often centered. The hero section features a full-width, visually rich product image with a centered headline and a prominent shop button. Subsequent sections alternate between product showcases using large, soft-edged cards against the atmospheric background. The primary navigation is a pill-shaped, translucent bar fixed at the top, blurring the content behind it. The overall density is comfortable, ensuring focus on product visuals.

## Agent Prompt Guide

Quick Color Reference:
text: #fafafa
background: #06050a (start of gradient)
border: #000000
accent: #c74c17
primary action: no distinct CTA color

Example Component Prompts:
Create a hero section with a gradient background using 'Deep Midnight Gradient': centered 'Low-Key Sophisticated Rosemary Spritz' headline in EditorialNew weight 200 at 60px, #fafafa, letter-spacing -1.5px. Below it, a 'SHOP' button: background #fafafa, text #07060b, border-radius 100px, 16px 28px padding, DepartureMono weight 400 at 16px, letter-spacing -0.071em.

Create a product card: background rgba(217, 217, 217, 0.3), border-radius 44px, 64px padding. Inside, 'Rosemary Spritz' in EditorialNew weight 200 at 40px, #fafafa, letter-spacing -1px; below it, 'Herbal | Bittersweet | Refreshing' in DepartureMono weight 400 at 14px, #fafafa, letter-spacing -0.071em.

Create a navigation bar: background rgba(217, 217, 217, 0.3) with backdrop-filter blur(50px), border-radius 100px. Links like 'SHOP', 'ABOUT', 'FIND US': ui-sans-serif weight 400 at 16px, text #fafafa, no specific padding (rely on parent container).

## Similar Brands

- **Recess** — Shares a similar dark, mood-driven aesthetic with elevated product photography and sophisticated branding for beverages.
- **Kin Euphorics** — Employs premium product presentation on dark backgrounds, often with diffused lighting and subtle color accents, focusing on a refined-casual feel.
- **Haus** — Uses a similar approach to sophisticated beverage branding with polished imagery and clean, modern typography against often muted or dark backdrops.
- **Superhuman** — Although a software product, it shares the 'frosted glass' UI elements and a focus on subtle depth without heavy shadows in a generally dimmer interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-night-sky: #07060b;
  --color-cloud-mist: #d9d9d9;
  --color-ghostly-gray: #cdcdce;
  --color-canvas-white: #fafafa;
  --color-arctic-whisper: #ddfcff;
  --color-sunrise-burst: #c74c17;
  --gradient-sunrise-burst: linear-gradient(rgb(217, 217, 217) 0%, rgba(199, 76, 23, 0.7) 100%);
  --color-sunset-blush: #a82b3a;
  --gradient-sunset-blush: linear-gradient(rgba(217, 217, 217, 0) 0%, rgba(168, 43, 58, 0.7) 100%);
  --color-olive-dusk: #bebe3a;
  --gradient-olive-dusk: linear-gradient(rgba(217, 217, 217, 0) 0%, rgba(190, 193, 58, 0.7) 100%);
  --color-deep-midnight-gradient: #06050a;
  --gradient-deep-midnight-gradient: linear-gradient(rgb(6, 5, 10) 0%, rgb(12, 12, 20) 5.43%, rgb(25, 29, 45) 12.1%, rgb(34, 40, 62) 18.86%, rgb(53, 68, 91) 25%, rgb(69, 96, 117) 32.3%, rgb(87, 119, 140) 38.7%, rgb(104, 137, 156) 44.45%, rgb(121, 150, 164) 50%, rgb(140, 162, 175) 56.05%, rgb(160, 178, 188) 62.3%, rgb(173, 190, 198) 68.4%, rgb(187, 200, 206) 75%, rgb(202, 212, 214) 80.62%, rgb(214, 219, 222) 86.41%, rgb(235, 237, 236) 93.78%, rgb(245, 246, 241) 100%);

  /* Typography — Font Families */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-departuremono: 'DepartureMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-helveticanowdisplay: 'HelveticaNowDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorialnew: 'EditorialNew', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --tracking-caption: -0.78px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.99px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -1.13px;
  --text-subheading: 18px;
  --leading-subheading: 1;
  --tracking-subheading: -0.9px;
  --text-heading: 40px;
  --leading-heading: 1.06;
  --tracking-heading: -1px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.06;
  --tracking-heading-lg: -1.5px;
  --text-display: 160px;
  --leading-display: 0.9;
  --tracking-display: -8px;

  /* Typography — Weights */
  --font-weight-extralight: 200;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 36px;
  --card-padding: 64px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-3xl: 44px;
  --radius-full: 100px;
  --radius-full-2: 110.016px;

  /* Named Radii */
  --radius-cards: 44px;
  --radius-buttons: 100px;
  --radius-elements: 110px;
  --radius-navigation: 100px;

  /* Surfaces */
  --surface-page-canvas: #06050a;
  --surface-frosted-surface: #d9d9d9;
  --surface-interactive-white: #fafafa;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-zero: #000000;
  --color-night-sky: #07060b;
  --color-cloud-mist: #d9d9d9;
  --color-ghostly-gray: #cdcdce;
  --color-canvas-white: #fafafa;
  --color-arctic-whisper: #ddfcff;
  --color-sunrise-burst: #c74c17;
  --color-sunset-blush: #a82b3a;
  --color-olive-dusk: #bebe3a;
  --color-deep-midnight-gradient: #06050a;

  /* Typography */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-departuremono: 'DepartureMono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;
  --font-helveticanowdisplay: 'HelveticaNowDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorialnew: 'EditorialNew', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1;
  --tracking-caption: -0.78px;
  --text-body: 14px;
  --leading-body: 1.43;
  --tracking-body: -0.99px;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: -1.13px;
  --text-subheading: 18px;
  --leading-subheading: 1;
  --tracking-subheading: -0.9px;
  --text-heading: 40px;
  --leading-heading: 1.06;
  --tracking-heading: -1px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1.06;
  --tracking-heading-lg: -1.5px;
  --text-display: 160px;
  --leading-display: 0.9;
  --tracking-display: -8px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-36: 36px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-3xl: 44px;
  --radius-full: 100px;
  --radius-full-2: 110.016px;
}
```
