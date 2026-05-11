# Arcadia — Style Reference
> Evergreen data canvas

**Theme:** light

Arcadia employs a grounded, sophisticated aesthetic, blending the precision of a data platform with the organic feel of clean energy. Its visual signature lies in its use of deep, muted teal (`Evergreen Deep`) as a primary brand color, paired with a soft, warm cream (`Pampas`) and an invigorating spring green (`Verdant Accent`). Typography is sharp and clear, providing authority without harshness, while spacious layouts and soft gradients hint at a natural, expansive energy landscape. Components are generally soft-edged and minimalist, emphasizing usability and understated confidence.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Evergreen Deep | `#104336` | `--color-evergreen-deep` | Primary brand color. Used for key navigation elements, dark text on light backgrounds, and borders of ghost buttons. Conveys authority and environmental connection |
| Mid-Tone Charcoal | `#101f1e` | `--color-mid-tone-charcoal` | Primary text color for headings and body copy, subtle card backgrounds, and dark button fills. Provides strong contrast and a sense of depth |
| Electric Violet | `#7c18d3` | `--color-electric-violet` | Decorative accent for visual elements, specific text highlights, and borders within data visualizations. Adds small pops of energetic color |
| Verdant Accent | `#0fff87` | `--color-verdant-accent` | Vivid accent for primary call-to-action buttons providing a strong visual cue for interaction and indicating positive action. Also used for some decorative purposes |
| Pale Sage | `linear-gradient(212.12deg, rgb(175, 196, 191) 14.83%, rgb(232, 231, 245) 52.99%, rgb(241, 238, 233) 79.47%)` | `--color-pale-sage` | Subtle border color for cards and other UI elements, creating soft definition in minimalist surfaces; Subtle background gradient for hero sections and key visual blocks, blending natural muted tones to evoke a sense of calm and innovation; Expansive background gradient using multiple subtle color changes, creating a soft, almost atmospheric backdrop for key content |
| White Canvas | `#ffffff` | `--color-white-canvas` | Dominant background color for most page content, card surfaces, and text on dark backgrounds. Creates an open, airy feel |
| Pampas | `#f3f1ec` | `--color-pampas` | Secondary background color, used for alternating sections and subtle card backgrounds. Adds warmth and depth to the overall light theme |
| Graphite | `#535e5d` | `--color-graphite` | Secondary text color for body copy, helper text, and less prominent information |
| Dark Carbon | `#333333` | `--color-dark-carbon` | Deep secondary text color for body copy and specific content areas, offering strong contrast |
| Silver Pine | `#c2cec8` | `--color-silver-pine` | Light border color for UI elements, offering a delicate separation |
| Fog Gray | `#798281` | `--color-fog-gray` | Muted text color for tertiary information, links, and borders |
| Input Gray | `#848c88` | `--color-input-gray` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |

## Tokens — Typography

### DM Sans — Primary typeface for all UI elements, headings, and body text. Its clean, geometric forms and varied weights provide clarity and a modern, authoritative tone. Specific letter-spacing maintains legibility at different scales. · `--font-dm-sans`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 700
- **Sizes:** 10px, 13px, 14px, 15px, 16px, 18px, 20px, 24px, 36px, 48px, 56px
- **Line height:** 1.00, 1.10, 1.15, 1.20, 1.29, 1.50
- **Letter spacing:** -0.0200em, 0.0100em, 0.0700em
- **Role:** Primary typeface for all UI elements, headings, and body text. Its clean, geometric forms and varied weights provide clarity and a modern, authoritative tone. Specific letter-spacing maintains legibility at different scales.

### Helvetica — Secondary typeface, primarily for small, utilitarian text where system font fallback is acceptable and high performance is prioritized. · `--font-helvetica`
- **Substitute:** Arial
- **Weights:** 400, 700
- **Sizes:** 13px
- **Line height:** 1.20
- **Role:** Secondary typeface, primarily for small, utilitarian text where system font fallback is acceptable and high performance is prioritized.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-lg | 16px | 1.5 | 0.16px | `--text-body-lg` |
| subheading | 20px | 1.2 | 0.2px | `--text-subheading` |
| heading | 36px | 1.15 | -0.72px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.96px | `--text-heading-lg` |
| display | 56px | 1.1 | -1.12px | `--text-display` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 88 | 88px | `--spacing-88` |
| 96 | 96px | `--spacing-96` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 18px |
| cards | 16px |
| image | 8px |
| input | 4px |
| buttons | 8px |

### Layout

- **Section gap:** 24px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Ghost Bordered Button
**Role:** Secondary action button

Transparent background with a border of `Evergreen Deep` (#104336) and text color `Mid-Tone Charcoal` (#101f1e). Features a large radius of 18px for a distinct, rounded appearance. Padding is 16px horizontal, 0px vertical.

### Request Demo Button (Filled)
**Role:** Primary Call-to-Action

Filled with `Verdant Accent` (#0fff87) background color, `Evergreen Deep` (#104336) text. Features 8px border-radius and 16px horizontal padding. Signals the most important action with vibrant color.

### Sign In Button (Filled)
**Role:** Secondary Call-to-Action

Filled with `Mid-Tone Charcoal` (#101f1e) background, `White Canvas` (#ffffff) text. Features 8px border-radius and 24px horizontal padding. Provides a strong, high-contrast action for key secondary interactions.

### Default Card
**Role:** Content container

Uses `White Canvas` (#ffffff) background with 16px border-radius. Padding of 24px on all sides. No shadow, creating a flat, modern aesthetic.

### Pampas Section Card
**Role:** Section background container

Applies `Pampas` (#f3f1ec) as background. Has 0px border-radius, acting as a full-width background panel for distinct content sections.

### Circular Callout Card
**Role:** Decorative content element

A visually distinct card with 50% border-radius, typically used for decorative or icon-based content. Transparent background and no shadow.

### Text Input Field
**Role:** User input element

Has a `White Canvas` (#ffffff) background, `Mid-Tone Charcoal` (#101f1e) text, and a `Input Gray` (#848c88) border. Rounded with a 4px border-radius. Padding is 16px horizontal, 0px vertical.

## Do's and Don'ts

### Do
- Prioritize `DM Sans` for all textual content, adjusting weight and letter-spacing according to the type scale for optimal legibility and brand tone.
- Use `Evergreen Deep` (#104336) for primary interactive elements, ensuring a consistent brand presence.
- Apply a 16px `radius` for cards and a 8px `radius` for buttons, maintaining a soft, approachable feel across major components.
- Utilize `White Canvas` (#ffffff) and `Pampas` (#f3f1ec) as primary section backgrounds, alternating to create visual rhythm on long pages.
- Integrate `Verdant Accent` (#0fff87) exclusively for crucial calls-to-action to maximize visual impact and guide user focus.
- Maintain comfortable element spacing using multiples of 8px, with a default `elementGap` of `24px` for consistent information density.
- When using gradients for large visual sections, always prefer the `Gradient Aura` or `Gradient Horizon` tokens to ensure brand consistency.

### Don't
- Avoid using `Electric Violet` (#7c18d3) as a primary action color; reserve its vividness for decorative accents or specific data highlights.
- Do not introduce new border radii beyond 4px, 8px, 16px, or 18px to preserve the system's consistent soft-edged aesthetic.
- Refrain from adding hard shadows; the design relies on flat planes and subtle background shifts rather than prominent elevation effects.
- Do not use highly saturated or dark backgrounds for entire page sections; maintain the dominant `light` theme using `White Canvas` (#ffffff) or `Pampas` (#f3f1ec).
- Avoid generic system fonts where `DM Sans` is specified; the custom typeface is integral to the brand's identity.
- Do not deviate from the established letter-spacing values for `DM Sans` to prevent degradation of typographic harmony and legibility.
- Do not use black (#000000) for body text; `Mid-Tone Charcoal` (#101f1e) or `Graphite` (#535e5d) should be used for readability and warmth.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | White Canvas | `#ffffff` | Base page background and default elevated surface for cards. |
| 1 | Pampas | `#f3f1ec` | Secondary background for alternating sections, providing subtle visual separation and warmth without stark contrast. |
| 2 | Gradient Aura | `#afc4bf` | Soft gradient background for hero sections or prominent content blocks, adding atmospheric depth. |

## Imagery

The site uses a mix of muted, abstract 3D illustrations and product screenshots. Abstract elements feature organic shapes, soft light, and a color palette aligned with the brand's greens and grays, sometimes with a pop of violet. Product screenshots are clean, showcasing UI against a light background with a subtle border or within a card. Icons are outlined, simple, and monochrome, often in `Evergreen Deep`. Imagery is primarily decorative and atmospheric, rather than strictly explanatory, conveying a sense of sophisticated technology and clean energy.

## Layout

The page primarily uses a full-bleed structure with content often contained within logical sections. The hero section leverages a full-width background gradient with centered headlines and calls-to-action. Content sections alternate between `White Canvas` and `Pampas` backgrounds, creating a clear vertical rhythm. Inner content is often arranged in a two-column or three-column grid for features and cards. Navigation is handled by a sticky top bar with clearly delineated primary and secondary actions. The layout feels spacious and organized, guiding the eye through a progression of information.

## Agent Prompt Guide

### Quick Color Reference
- text: #101f1e
- background: #ffffff
- border: #104336
- accent: #7c18d3
- primary action: #0fff87 (filled action)

### 3-5 Example Component Prompts
- Create a hero section: `Gradient Aura` background, centered headline 'Solutions to power the new energy era' in `DM Sans` weight 700 at 56px, `Mid-Tone Charcoal` text, `letterSpacing` -1.12px. Add a `Request Demo Button (Filled)` below.
- Create a feature card: `Default Card` with a `White Canvas` background and 16px radius. Inside, use `DM Sans` weight 500 at 24px, `Mid-Tone Charcoal` text for the title, `DM Sans` weight 400 at 16px, `Graphite` text for the description.
- Create a ghost button for navigation: `Ghost Bordered Button` with `Evergreen Deep` border and text. `DM Sans` weight 400 at 16px, using 18px radius.
- Create an input form: `Text Input Field` for email entry, with `Mid-Tone Charcoal` placeholder text 'Enter your email'. Follow with a `Request Demo Button (Filled)` to submit.

## Similar Brands

- **Stripe** — Shares a sophisticated, clean aesthetic with subtle background gradients and a dominant single accent color for primary actions.
- **Figma** — Uses a spacious, minimalist layout with soft card-like surfaces and a focus on clean typography against light backgrounds.
- **Workday** — Employs a professional, enterprise-focused design with deep greens/teals in branding, ample negative space, and clear hierarchical typography.
- **Atlassian** — Similar approach to information density, comfortable spacing, and soft-edged components in a primarily light-themed interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-evergreen-deep: #104336;
  --color-mid-tone-charcoal: #101f1e;
  --color-electric-violet: #7c18d3;
  --color-verdant-accent: #0fff87;
  --color-pale-sage: #afc4bf;
  --gradient-pale-sage: linear-gradient(212.12deg, rgb(175, 196, 191) 14.83%, rgb(232, 231, 245) 52.99%, rgb(241, 238, 233) 79.47%);
  --color-white-canvas: #ffffff;
  --color-pampas: #f3f1ec;
  --color-graphite: #535e5d;
  --color-dark-carbon: #333333;
  --color-silver-pine: #c2cec8;
  --color-fog-gray: #798281;
  --color-input-gray: #848c88;

  /* Typography — Font Families */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.2px;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -0.72px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.96px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.12px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-tags: 18px;
  --radius-cards: 16px;
  --radius-image: 8px;
  --radius-input: 4px;
  --radius-buttons: 8px;

  /* Surfaces */
  --surface-white-canvas: #ffffff;
  --surface-pampas: #f3f1ec;
  --surface-gradient-aura: #afc4bf;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-evergreen-deep: #104336;
  --color-mid-tone-charcoal: #101f1e;
  --color-electric-violet: #7c18d3;
  --color-verdant-accent: #0fff87;
  --color-pale-sage: #afc4bf;
  --color-white-canvas: #ffffff;
  --color-pampas: #f3f1ec;
  --color-graphite: #535e5d;
  --color-dark-carbon: #333333;
  --color-silver-pine: #c2cec8;
  --color-fog-gray: #798281;
  --color-input-gray: #848c88;

  /* Typography */
  --font-dm-sans: 'DM Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica: 'Helvetica', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --tracking-body-lg: 0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: 0.2px;
  --text-heading: 36px;
  --leading-heading: 1.15;
  --tracking-heading: -0.72px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.96px;
  --text-display: 56px;
  --leading-display: 1.1;
  --tracking-display: -1.12px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-88: 88px;
  --spacing-96: 96px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-2xl: 16px;
}
```
