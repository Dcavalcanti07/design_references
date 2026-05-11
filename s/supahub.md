# Supahub — Style Reference
> whispering tech meadow

**Theme:** light

Supahub uses a soft, almost ethereal visual language, combining crisp dark typography with a predominantly white canvas and subtle pastel gradients. The design communicates a light, approachable, but structured feel, with rounded corners and a core accent palette of purples and pinks that emerge as focal points against the quiet neutrals. Components are lightweight with minimal elevation, favoring ghost buttons and soft cards to maintain an airy aesthetic.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111827` | `--color-midnight-ink` | Primary text, dark surface backgrounds, button background for primary action |
| Ghost Gray | `#3f4654` | `--color-ghost-gray` | Secondary text, subtle borders, navigation text |
| Mist Gray | `#6b7589` | `--color-mist-gray` | Tertiary text, helper text, ghost button borders and text |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds, primary button text |
| Pale Cloud | `#f1f5f9` | `--color-pale-cloud` | Subtle background sections, hover states on light elements |
| Mint Glaze | `#d6fcf4` | `--color-mint-glaze` | Gray wash for highlight backgrounds, decorative bands, and soft emphasis behind content |
| Lavender Mist | `#d8e0ea` | `--color-lavender-mist` | Subtle box shadows, background elements |
| Royal Amethyst | `#862fe7` | `--color-royal-amethyst` | Primary Call-to-action background, active navigation indicator, prominent links |
| Soft Amethyst | `#ad6df4` | `--color-soft-amethyst` | Decorative card backgrounds, icon fills |
| Muted Amethyst | `#bd8ff0` | `--color-muted-amethyst` | Subtle card backgrounds, decorative elements |
| Deep Plum | `#5f259e` | `--color-deep-plum` | Accent text, sometimes used for prominent headings |
| Fuchsia Glow | `#ff5fe4` | `--color-fuchsia-glow` | Decorative card backgrounds, accent elements |
| Rose Bloom | `#e22ba4` | `--color-rose-bloom` | Accent text for specific heading styles, decorative elements |
| Sunset Orange | `#dc5f05` | `--color-sunset-orange` | Accent text for specific heading styles, decorative elements |
| Gradient Violet Sparkle | `radial-gradient(circle at 0px -50%, rgba(255, 255, 255, 0) 15%, rgba(152, 26, 249, 0.4) 38%, rgba(255, 255, 255, 0) 65%)` | `--color-gradient-violet-sparkle` | Subtle radial background effect, evokes depth and digital sparkle |
| Gradient Pink Sparkle | `linear-gradient(214deg, rgba(255, 255, 255, 0), rgba(252, 52, 255, 0.3) 25%, rgba(255, 255, 255, 0) 71%)` | `--color-gradient-pink-sparkle` | Subtle linear background effect, adds vibrancy and visual interest |
| Gradient Magenta Flash | `linear-gradient(212deg, rgba(255, 255, 255, 0) 51%, rgba(145, 27, 255, 0.2) 64%, rgba(255, 255, 255, 0) 80%)` | `--color-gradient-magenta-flash` | Subtle linear background effect, provides depth and energy |
| Gradient Orange Flare | `radial-gradient(circle at 0px -50%, rgba(255, 255, 255, 0) 15%, rgba(249, 167, 26, 0.4) 38%, rgba(255, 255, 255, 0) 65%)` | `--color-gradient-orange-flare` | Subtle radial background effect, for warmth and highlight |
| Gradient Rose Blush | `linear-gradient(214deg, rgba(255, 255, 255, 0), rgba(255, 52, 143, 0.3) 25%, rgba(255, 255, 255, 0) 71%)` | `--color-gradient-rose-blush` | Subtle linear background effect, contributes to a soft, inviting atmosphere |
| Gradient Golden Glow | `linear-gradient(212deg, rgba(255, 255, 255, 0) 51%, rgba(255, 209, 27, 0.2) 64%, rgba(255, 255, 255, 0) 80%)` | `--color-gradient-golden-glow` | Subtle linear background effect, adds a touch of warmth and vibrancy |

## Tokens — Typography

### BricolageGrotesque — Primary display and heading font. Used for strong brand presence and hierarchy. The tight letter-spacing at larger sizes gives it a distinct, impactful feel without being overly aggressive. · `--font-bricolagegrotesque`
- **Substitute:** Montserrat
- **Weights:** 400, 600
- **Sizes:** 16px, 20px, 22px, 24px, 32px, 48px, 56px
- **Line height:** 1.00, 1.20, 1.30, 1.50, 1.75
- **Letter spacing:** -0.0250em
- **Role:** Primary display and heading font. Used for strong brand presence and hierarchy. The tight letter-spacing at larger sizes gives it a distinct, impactful feel without being overly aggressive.

### Inter — Body copy and UI element text. Its larger letter-spacing provides excellent legibility for smaller text and secondary information, contrasting with the tighter tracking of headlines. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px
- **Line height:** 1.14, 1.25, 1.33, 1.50, 1.60, 1.80
- **Letter spacing:** 0.1000em
- **Role:** Body copy and UI element text. Its larger letter-spacing provides excellent legibility for smaller text and secondary information, contrasting with the tighter tracking of headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.6 | 1.2px | `--text-caption` |
| body-sm | 14px | 1.5 | 1.4px | `--text-body-sm` |
| body | 16px | 1.5 | 1.6px | `--text-body` |
| body-lg | 18px | 1.33 | 1.8px | `--text-body-lg` |
| subheading | 20px | 1.25 | -0.5px | `--text-subheading` |
| heading-sm | 22px | 1.2 | -0.55px | `--text-heading-sm` |
| heading | 24px | 1.2 | -0.6px | `--text-heading` |
| heading-lg | 32px | 1.2 | -0.8px | `--text-heading-lg` |
| display-sm | 48px | 1 | -1.2px | `--text-display-sm` |
| display | 56px | 1 | -1.4px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |
| 128 | 128px | `--spacing-128` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| badges | 9999px |
| images | 16px |
| inputs | 12px |
| avatars | 9999px |
| buttons | 12px |
| navItems | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(11, 61, 121, 0.16) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 32px
- **Card padding:** 32px
- **Element gap:** 12px

## Components

### Primary Action Button
**Role:** Filled button

Background: Royal Amethyst (#862fe7), Text: Canvas White (#ffffff), Padding: 12px vertical, 24px horizontal. Corner Radius: 12px. Used for conversion-focused actions like 'Sign up for free'.

### Secondary Action Button
**Role:** Outlined button

Background: Canvas White (#ffffff), Text: Midnight Ink (#111827), Padding: 12px vertical, 24px horizontal. Corner Radius: 12px. Used for alternative actions like 'See Demo' or general navigation.

### Ghost Navigation Button
**Role:** Text button with minimal styling

Background: transparent, Text: Mist Gray (#6b7589), Padding: 8px. Corner Radius: 9999px. Used for sub-navigation or subtle interactive elements.

### Feature Card
**Role:** Card container for content blocks

Background: Canvas White (#ffffff), Border: none, Shadow: none. Padding: 32px vertical, 32px horizontal. Corner Radius: 24px. Visual consistency for content grouping.

### Accent Feature Card (Violet)
**Role:** Decorative card container

Background: Muted Amethyst (#bd8ff0), Border: none, Shadow: none. Padding: 0px. Corner Radius: 24px. Used for visually distinct blocks, often showcasing product UI.

### Testimonial Card
**Role:** Card for user reviews and social proof

Background: Canvas White (#ffffff), Border: 1px solid Mist Gray, Shadow: none. Padding: 32px vertical, 32px horizontal. Corner Radius: 24px. Contains user images and quotes.

### Avatar Image
**Role:** User profile image

Border Radius: 9999px (full circle). Used for showing individual users or team members.

### Input Field
**Role:** Form input elements

Background: Canvas White (#ffffff), Border: 1px solid Midnight Ink (#111827) inset, Placeholder Text: Mist Gray (#6b7589). Corner Radius: 12px. Minimalist input for data entry.

## Do's and Don'ts

### Do
- Always use BricolageGrotesque for marketing headlines, with specific attention to the negative letter-spacing for large sizes.
- Apply a 12px radius to all interactive elements such as buttons and input fields for a consistent soft touch.
- Prioritize Royal Amethyst (#862fe7) for primary call-to-action backgrounds to maintain brand recognition.
- Use a default vertical section gap of 32px to ensure comfortable spacing between content blocks.
- Implement the soft radial and linear gradients (Royal Amethyst, Fuchsia Glow, etc.) as subtle background effects to add depth and visual interest behind content, not as foreground elements.
- Utilize Mint Glaze (#d6fcf4) as a background for sections that require a subtle visual break from the main canvas.
- Ensure image elements, especially user avatars, receive a 9999px (full circle) border-radius for distinct visual treatment.

### Don't
- Do not use highly saturated colors for large background areas; reserve Canvas White (#ffffff) and Pale Cloud (#f1f5f9) as dominant backgrounds.
- Avoid harsh, dark box-shadows or heavy borders on cards; prefer soft, almost invisible shadows or no shadow at all.
- Do not use BricolageGrotesque for body text; reserve Inter for all paragraph and long-form content to optimize readability.
- Refrain from drastically altering letter-spacing on Inter; maintain its slightly wider tracking for clarity.
- Do not introduce new border-radius values; adhere strictly to 12px for buttons/inputs, 24px for cards, and 9999px for avatars/badges.
- Avoid using multiple vivid accent colors in close proximity; let Purple Reign (#862fe7) and its variations be the primary chromatic accents.
- Do not use Midnight Ink (#111827) for small, functional icons, use Mint Gray (#6b7589) instead for a softer appearance.

## Imagery

The site uses a combination of product screenshots, user photography (avatars), and abstract, soft, pastel-toned gradient shapes. Product screenshots are typically clean, direct, and showcased within mock devices or simple UI examples, often against the white canvas, with some having a subtle background color like Mint Glaze or soft amethyst gradients. User photography in testimonials appears as small, circular avatars. Abstract gradient shapes serve a decorative, atmospheric role, creating a sense of digital fluidity and subtle dynamism without being distracting. Icons are generally outlined or solid mono-color (Mist Gray or Royal Amethyst), with a light stroke weight.

## Layout

The page primarily uses a max-width contained layout, approximately 1200px wide, centered on the screen. The hero section is full-width with a centered headline, subtext, and stacked calls-to-action, overlaid on a large, subtle gradient background. Sections typically alternate between white and light gray backgrounds, creating a clear visual rhythm. Content is arranged in alternating text-left/image-right or text-right/image-left patterns, as well as vertically stacked content blocks and multi-column card grids (e.g., testimonial grid with 4 columns). The header is sticky, occupying 64px vertically, with a left-aligned logo and right-aligned navigation links and actions. Spacing between major sections is generous, contributing to an open, comfortable density.

## Agent Prompt Guide

Quick Color Reference:
text: #111827
background: #ffffff
border: #6b7589
accent: #bd8ff0
primary action: #862fe7 (filled action)

Example Component Prompts:
Create a Primary Action Button: #862fe7 background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Create a testimonial card: Canvas White (#ffffff) background, 1px solid Mist Gray (#6b7589) border, 24px radius. Padding 32px. Quote text using Inter 16px, weight 400, color Midnight Ink (#111827). Author name using Inter 14px, weight 600, color Midnight Ink (#111827). Circular avatar image: 9999px radius, no border.

Create an input field: Canvas White (#ffffff) background, 1px solid Midnight Ink (#111827) inset border, 12px radius. Placeholder text color Mist Gray (#6b7589). Input text color Midnight Ink (#111827). Padding 12px vertical, 16px horizontal.

Create a feature section: Pale Cloud (#f1f5f9) background. Heading using BricolageGrotesque 32px, weight 600, color Midnight Ink (#111827). Body text using Inter 16px, weight 400, color Ghost Gray (#3f4654). Image with 16px radius, separated by 32px vertical spacing.

## Similar Brands

- **Linear** — Shares a clean, light UI with sophisticated typography and a single accent color for primary actions.
- **Fathom Analytics** — Similar approach to using subtle gradients for backgrounds and emphasizing white space around content, combined with dark, crisp text.
- **Amie** — Uses a white canvas with small, functional color accents and lightweight components, favoring an airy and composed feel.
- **Height** — Exhibits a similar pairing of a strong, modern sans-serif for headings and a highly legible body font, combined with minimal UI styling and strategic use of rounded corners.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111827;
  --color-ghost-gray: #3f4654;
  --color-mist-gray: #6b7589;
  --color-canvas-white: #ffffff;
  --color-pale-cloud: #f1f5f9;
  --color-mint-glaze: #d6fcf4;
  --color-lavender-mist: #d8e0ea;
  --color-royal-amethyst: #862fe7;
  --color-soft-amethyst: #ad6df4;
  --color-muted-amethyst: #bd8ff0;
  --color-deep-plum: #5f259e;
  --color-fuchsia-glow: #ff5fe4;
  --color-rose-bloom: #e22ba4;
  --color-sunset-orange: #dc5f05;
  --color-gradient-violet-sparkle: #981af9;
  --gradient-gradient-violet-sparkle: radial-gradient(circle at 0px -50%, rgba(255, 255, 255, 0) 15%, rgba(152, 26, 249, 0.4) 38%, rgba(255, 255, 255, 0) 65%);
  --color-gradient-pink-sparkle: #fc34ff;
  --gradient-gradient-pink-sparkle: linear-gradient(214deg, rgba(255, 255, 255, 0), rgba(252, 52, 255, 0.3) 25%, rgba(255, 255, 255, 0) 71%);
  --color-gradient-magenta-flash: #911aff;
  --gradient-gradient-magenta-flash: linear-gradient(212deg, rgba(255, 255, 255, 0) 51%, rgba(145, 27, 255, 0.2) 64%, rgba(255, 255, 255, 0) 80%);
  --color-gradient-orange-flare: #f9a71a;
  --gradient-gradient-orange-flare: radial-gradient(circle at 0px -50%, rgba(255, 255, 255, 0) 15%, rgba(249, 167, 26, 0.4) 38%, rgba(255, 255, 255, 0) 65%);
  --color-gradient-rose-blush: #ff348f;
  --gradient-gradient-rose-blush: linear-gradient(214deg, rgba(255, 255, 255, 0), rgba(255, 52, 143, 0.3) 25%, rgba(255, 255, 255, 0) 71%);
  --color-gradient-golden-glow: #ffd11b;
  --gradient-gradient-golden-glow: linear-gradient(212deg, rgba(255, 255, 255, 0) 51%, rgba(255, 209, 27, 0.2) 64%, rgba(255, 255, 255, 0) 80%);

  /* Typography — Font Families */
  --font-bricolagegrotesque: 'BricolageGrotesque', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 1.2px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 1.4px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 1.6px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: 1.8px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.5px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.55px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.6px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.8px;
  --text-display-sm: 48px;
  --leading-display-sm: 1;
  --tracking-display-sm: -1.2px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -1.4px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 32px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-badges: 9999px;
  --radius-images: 16px;
  --radius-inputs: 12px;
  --radius-avatars: 9999px;
  --radius-buttons: 12px;
  --radius-navitems: 8px;

  /* Shadows */
  --shadow-subtle: rgba(11, 61, 121, 0.16) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111827;
  --color-ghost-gray: #3f4654;
  --color-mist-gray: #6b7589;
  --color-canvas-white: #ffffff;
  --color-pale-cloud: #f1f5f9;
  --color-mint-glaze: #d6fcf4;
  --color-lavender-mist: #d8e0ea;
  --color-royal-amethyst: #862fe7;
  --color-soft-amethyst: #ad6df4;
  --color-muted-amethyst: #bd8ff0;
  --color-deep-plum: #5f259e;
  --color-fuchsia-glow: #ff5fe4;
  --color-rose-bloom: #e22ba4;
  --color-sunset-orange: #dc5f05;
  --color-gradient-violet-sparkle: #981af9;
  --color-gradient-pink-sparkle: #fc34ff;
  --color-gradient-magenta-flash: #911aff;
  --color-gradient-orange-flare: #f9a71a;
  --color-gradient-rose-blush: #ff348f;
  --color-gradient-golden-glow: #ffd11b;

  /* Typography */
  --font-bricolagegrotesque: 'BricolageGrotesque', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.6;
  --tracking-caption: 1.2px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: 1.4px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: 1.6px;
  --text-body-lg: 18px;
  --leading-body-lg: 1.33;
  --tracking-body-lg: 1.8px;
  --text-subheading: 20px;
  --leading-subheading: 1.25;
  --tracking-subheading: -0.5px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.55px;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --tracking-heading: -0.6px;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.2;
  --tracking-heading-lg: -0.8px;
  --text-display-sm: 48px;
  --leading-display-sm: 1;
  --tracking-display-sm: -1.2px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -1.4px;

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
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-112: 112px;
  --spacing-128: 128px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(11, 61, 121, 0.16) 0px 0px 0px 1px inset;
}
```
