# Tedy — Style Reference
> Vibrant Pastel Softness

**Theme:** light

Tedy's design system evokes a warm, vibrant professionalism, balancing clarity with approachable pops of color. Muted pastel shades of purple, green, and yellow serve as soft background washes or semantic badges, while a vivid berry red provides energetic accents and distinct calls to action. Strong, tracked-in typography (Montreal Neue) anchors content, set against clean white surfaces with rounded rectangles that soften the overall feel. The system prioritizes a friendly but secure experience.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#030712` | `--color-midnight-ink` | Primary text, darkest borders, icons, and some card elements – establishing a deep, authoritative base |
| Cloud White | `#ffffff` | `--color-cloud-white` | Canvas background, primary surface color for cards and buttons, providing a clean and expansive backdrop |
| Muted Silver | `#6b7280` | `--color-muted-silver` | Secondary text, muted borders, and subtle fills, offering a softer tone than primary text |
| Pale Ash | `#e5e7eb` | `--color-pale-ash` | Interface dividers, subtle button borders, and list item separators |
| Berry Burst | `#fd1774` | `--color-berry-burst` | Primary call to action button backgrounds, active interaction states, and distinctive icon accents – the system's most vivid and energetic accent |
| Lavender Mist | `#e5d6ff` | `--color-lavender-mist` | Soft card backgrounds, link highlights, and decorative badge fills |
| Lemon Chiffon | `#fff1cd` | `--color-lemon-chiffon` | Accent backgrounds for badges signalling warnings or informational statuses |
| Mint Whisper | `#e3f7d6` | `--color-mint-whisper` | Accent backgrounds for badges signalling success or positive statuses |
| Sky Haze | `#ddf5fb` | `--color-sky-haze` | Subtle background wash for content sections |
| Bubblegum Pop | `#fe74ac` | `--color-bubblegum-pop` | Red supporting accent for decorative details and low-frequency emphasis. Do not promote it to the primary CTA color |
| Turquoise Dream | `#4bb7cf` | `--color-turquoise-dream` | Decorative icon accents and illustrative elements |
| Fresh Sprout | `#64d71e` | `--color-fresh-sprout` | Decorative icon accents and illustrative elements |
| Lavender Glow Gradient | `linear-gradient(to top, rgb(231, 214, 255) 0%, oklab(0.902604 0.0325668 -0.0481643 / 0.85) 50%, rgba(0, 0, 0, 0) 100%)` | `--color-lavender-glow-gradient` | Subtle background gradient for hero sections or prominent content blocks, creating a soft atmospheric effect |

## Tokens — Typography

### Montreal Neue — The primary typeface for all headings, body text, and UI elements. Its confident, subtly tracked-in appearance maintains a modern and precise tone, especially at larger sizes where tracking tightens. · `--font-montreal-neue`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500
- **Sizes:** 14px, 15px, 16px, 17px, 19px, 23px, 28px, 56px, 59px, 61px, 64px, 70px, 80px, 85px, 86px, 104px
- **Line height:** 0.90, 0.92, 0.95, 0.96, 0.98, 1.00, 1.02, 1.05, 1.38, 1.40, 1.43, 1.45, 1.50
- **Letter spacing:** -0.0650em, -0.0550em, -0.0500em, -0.0450em, -0.0400em, -0.0300em, -0.0250em, -0.0200em, -0.0050em
- **Role:** The primary typeface for all headings, body text, and UI elements. Its confident, subtly tracked-in appearance maintains a modern and precise tone, especially at larger sizes where tracking tightens.

### Georgia — Georgia — detected in extracted data but not described by AI · `--font-georgia`
- **Weights:** 700
- **Sizes:** 80px
- **Line height:** 
- **Role:** Georgia — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.5 | -0.005px | `--text-caption` |
| body | 16px | 1.45 | -0.005px | `--text-body` |
| subheading | 23px | 1.4 | -0.02px | `--text-subheading` |
| heading-sm | 28px | 1.38 | -0.025px | `--text-heading-sm` |
| heading | 56px | 1.05 | -0.04px | `--text-heading` |
| heading-lg | 70px | 1.02 | -0.05px | `--text-heading-lg` |
| display | 86px | 0.96 | -0.065px | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 84 | 84px | `--spacing-84` |
| 96 | 96px | `--spacing-96` |
| 112 | 112px | `--spacing-112` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| badges | 32px |
| images | 32px |
| buttons | 999px |
| general | 999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(17, 24, 39, 0.16) 0px 28px 52px 0px` | `--shadow-xl` |
| subtle | `rgb(255, 241, 205) 0px 0px 0px 1px` | `--shadow-subtle` |
| xl-2 | `rgba(253, 23, 116, 0.6) 0px 14px 35px -18px` | `--shadow-xl-2` |
| subtle-2 | `rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset, rgba(255...` | `--shadow-subtle-2` |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 18px

## Components

### Primary Action Button
**Role:** Critical calls to action.

Filled button with a Berry Burst background, Cloud White text, and a full pill-shaped radius. Padding: 10px vertical, 18px horizontal. Has a soft Berry Burst shadow: rgba(253, 23, 116, 0.6) 0px 14px 35px -18px.

### Ghost Button
**Role:** Secondary actions or navigation.

Transparent background with Midnight Ink text. No border, no padding indicated from extracted data (defaults to browser). Used for discrete inline actions.

### Outline Neutral Button
**Role:** Tertiary actions or navigation.

Cloud White background with Midnight Ink text and a Pale Ash border. Full pill-shaped radius (999px). Padding: 10px vertical, 18px horizontal.

### Outline Small Button
**Role:** Compact secondary actions.

Cloud White background with Midnight Ink text and a Pale Ash border. Full pill-shaped radius (999px). Padding: 8px vertical, 14px horizontal.

### Content Card
**Role:** Information grouping, feature presentation, testimonials.

Transparent background, 0px padding, no shadow by default, 0px border radius, indicating it often acts as a container for other elements.

### Elevated Content Card
**Role:** Prominent information blocks or data visualizations.

Cloud White background with 20px border radius. This variant has a soft shadow: rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.03) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.35) 0px 30px 80px 0px and a backdrop blur of 24px.

### Accent Highlight Card
**Role:** Highlighting key information or user inputs.

Lavender Mist background with 16px border radius. 32px padding on all sides. Used for sections like 'Choose the categories that are important to you'.

### Testimonial Card (Hover)
**Role:** Engaging user testimonials.

Transparent background, 16px radius, with a strong shadow for emphasis: rgba(17, 24, 39, 0.16) 0px 28px 52px 0px. Padding variable: 41.6px top, 43.2px right, 35.2px bottom, 36.8px left.

### Status Badge - Warning
**Role:** Indicating warning or informational states.

Lemon Chiffon background with Midnight Ink text. Rounded rectangle shape, 0px top-left/bottom-right, 21.6px top-right, 32px bottom-left. Padding: 12.8px top, 12.8px right, 14.4px bottom, 18.4px left. Includes a 1px Lemon Chiffon outline.

### Status Badge - Success
**Role:** Indicating successful actions or positive states.

Mint Whisper background with Midnight Ink text. Rounded rectangle shape, 0px top-left/bottom-right, 21.6px top-right, 32px bottom-left. Padding: 12.8px top, 12.8px right, 14.4px bottom, 18.4px left.

### Status Badge - Accent
**Role:** Highlighting specific categories or features.

Lavender Mist background with Midnight Ink text. Rounded rectangle shape, 0px top-left/bottom-right, 21.6px top-right, 32px bottom-left. Padding: 12.8px top, 12.8px right, 14.4px bottom, 18.4px left.

## Do's and Don'ts

### Do
- Use Midnight Ink (#030712) for all primary body text and headings.
- Apply Cloud White (#ffffff) as the default background for all large sections and surface elements.
- Utilize Berry Burst (#fd1774) exclusively for primary call-to-action buttons and interactive highlights to maintain its impact.
- Ensure all buttons and navigational elements use a 999px border-radius for a distinct pill shape.
- Employ Montreal Neue weight 500 for headings, with letter spacing adjusted according to the type scale for impact.
- Apply Lavender Mist (#e5d6ff) as a subtle background for card-like elements that require a gentle accent.
- Maintain a clear visual hierarchy with element gaps of 18px and card padding at 24px.

### Don't
- Do not use Berry Burst (#fd1774) for non-interactive elements or large background areas.
- Avoid using a border-radius less than 16px for cards, exceptions are images or badges with specific rounding.
- Do not introduce new shadow styles; adhere to the existing definition for Elevated Content Cards and Primary Action Buttons.
- Never use generic system fonts when Montreal Neue is available; always prioritize its specific weights and letter-spacing.
- Do not vary paragraph line-height from the specified Montreal Neue values (e.g., 1.45 at 16px) to avoid readability issues.
- Avoid using strong, saturated colors for backgrounds; reserve them for accents and semantic indicators only.
- Do not add additional decorative gradients beyond the defined Lavender Glow or radial accents; maintain clean primary surfaces.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Canvas Background | `#ffffff` | The primary page background, providing a clean white foundation. |
| 2 | Accent Wash | `#ddf5fb` | Soft, light blue background tint for specific content sections to provide visual separation without heavy contrast. |
| 3 | Tinted Surface | `#e5d6ff` | Soft lavender background for prominent cards or sections, indicating a special feature or input area. |

## Elevation

- **Primary Action Button:** `rgba(253, 23, 116, 0.6) 0px 14px 35px -18px`
- **Elevated Content Card:** `rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.03) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.35) 0px 30px 80px 0px`
- **Testimonial Card (Hover):** `rgba(17, 24, 39, 0.16) 0px 28px 52px 0px`

## Imagery

The visual language mixes authentic photography with clean UI examples and illustrative icons. Photography features diverse groups of happy, laughing people in candid, lifestyle-oriented shots, often contained within rounded rectangular masks. Product screenshots are clean, functional, and presented flat on white or subtly tinted backgrounds, sometimes with a soft shadow or transparency effect. Icons are minimal, outlined, and monochromatic, usually in Midnight Ink, occasionally adopting moderate accent colors like Turquoise Dream or Fresh Sprout. Imagery serves to establish an approachable, human-centered atmosphere and clarify product functionality simultaneously. Image density is moderate, with visuals often balanced against text blocks.

## Layout

The page primarily uses a max-width contained layout, likely around 1200px, with content centered. The hero section is a split layout: a large, off-center Lavender Mist background block with dominant text on the left, juxtaposed with a collage of lifestyle photography on the right. Content sections generally feature alternating text-left/image-right (or product UI) patterns, maintaining a comfortable vertical rhythm with consistent spacing. Testimonials are presented in a two-column grid format with large, rounded cards. The navigation is a sticky top bar with a left-aligned logo and right-aligned buttons and links.

## Agent Prompt Guide

Quick Color Reference:
text: #030712
background: #ffffff
border: #e5e7eb
accent: #e5d6ff
primary action: #fd1774 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: background #fd1774, text #ffffff, radius 999px, padding 10px 18px. The text should be 'Book a Demo'.
2. Create an Accent Highlight Card: background #e5d6ff, radius 16px, padding 32px. Place a heading 'Custom Benefits' (Montreal Neue, weight 500, size 28px, #030712, letter-spacing -0.025em) and body text 'Flexible plans for specific categories' (Montreal Neue, weight 400, size 16px, #030712, letter-spacing -0.005em) inside.
3. Create a Testimonial Card in hover state: transparent background, radius 16px, box-shadow rgba(17, 24, 39, 0.16) 0px 28px 52px 0px. The text should be '“ Tedy helped us increase our team's engagement...' (Montreal Neue, weight 400, size 19px, #030712, letter-spacing -0.02em).

## Similar Brands

- **Rippling** — Clean white backgrounds with a strong, custom sans-serif typeface and a single vibrant accent color for CTAs.
- **Carta** — Modern, approachable aesthetic with distinctive, rounded UI elements and a focus on clarity through clean layout.
- **Ramp** — Utilizes a crisp, professional aesthetic with an emphasis on bold typography and strategic use of brand color highlights.
- **Gusto** — Combines friendly, diverse photography with clear product UIs and bright, inviting accent colors.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #030712;
  --color-cloud-white: #ffffff;
  --color-muted-silver: #6b7280;
  --color-pale-ash: #e5e7eb;
  --color-berry-burst: #fd1774;
  --color-lavender-mist: #e5d6ff;
  --color-lemon-chiffon: #fff1cd;
  --color-mint-whisper: #e3f7d6;
  --color-sky-haze: #ddf5fb;
  --color-bubblegum-pop: #fe74ac;
  --color-turquoise-dream: #4bb7cf;
  --color-fresh-sprout: #64d71e;
  --color-lavender-glow-gradient: #e7d6ff;
  --gradient-lavender-glow-gradient: linear-gradient(to top, rgb(231, 214, 255) 0%, oklab(0.902604 0.0325668 -0.0481643 / 0.85) 50%, rgba(0, 0, 0, 0) 100%);

  /* Typography — Font Families */
  --font-montreal-neue: 'Montreal Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-georgia: 'Georgia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.005px;
  --text-body: 16px;
  --leading-body: 1.45;
  --tracking-body: -0.005px;
  --text-subheading: 23px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.38;
  --tracking-heading-sm: -0.025px;
  --text-heading: 56px;
  --leading-heading: 1.05;
  --tracking-heading: -0.04px;
  --text-heading-lg: 70px;
  --leading-heading-lg: 1.02;
  --tracking-heading-lg: -0.05px;
  --text-display: 86px;
  --leading-display: 0.96;
  --tracking-display: -0.065px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
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
  --spacing-56: 56px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 18px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 44.8px;
  --radius-full: 48px;
  --radius-full-2: 57.6px;
  --radius-full-3: 999px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-badges: 32px;
  --radius-images: 32px;
  --radius-buttons: 999px;
  --radius-general: 999px;

  /* Shadows */
  --shadow-xl: rgba(17, 24, 39, 0.16) 0px 28px 52px 0px;
  --shadow-subtle: rgb(255, 241, 205) 0px 0px 0px 1px;
  --shadow-xl-2: rgba(253, 23, 116, 0.6) 0px 14px 35px -18px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.03) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.35) 0px 30px 80px 0px;

  /* Surfaces */
  --surface-canvas-background: #ffffff;
  --surface-accent-wash: #ddf5fb;
  --surface-tinted-surface: #e5d6ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #030712;
  --color-cloud-white: #ffffff;
  --color-muted-silver: #6b7280;
  --color-pale-ash: #e5e7eb;
  --color-berry-burst: #fd1774;
  --color-lavender-mist: #e5d6ff;
  --color-lemon-chiffon: #fff1cd;
  --color-mint-whisper: #e3f7d6;
  --color-sky-haze: #ddf5fb;
  --color-bubblegum-pop: #fe74ac;
  --color-turquoise-dream: #4bb7cf;
  --color-fresh-sprout: #64d71e;
  --color-lavender-glow-gradient: #e7d6ff;

  /* Typography */
  --font-montreal-neue: 'Montreal Neue', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-georgia: 'Georgia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.5;
  --tracking-caption: -0.005px;
  --text-body: 16px;
  --leading-body: 1.45;
  --tracking-body: -0.005px;
  --text-subheading: 23px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.02px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.38;
  --tracking-heading-sm: -0.025px;
  --text-heading: 56px;
  --leading-heading: 1.05;
  --tracking-heading: -0.04px;
  --text-heading-lg: 70px;
  --leading-heading-lg: 1.02;
  --tracking-heading-lg: -0.05px;
  --text-display: 86px;
  --leading-display: 0.96;
  --tracking-display: -0.065px;

  /* Spacing */
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
  --spacing-56: 56px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-96: 96px;
  --spacing-112: 112px;

  /* Border Radius */
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 44.8px;
  --radius-full: 48px;
  --radius-full-2: 57.6px;
  --radius-full-3: 999px;

  /* Shadows */
  --shadow-xl: rgba(17, 24, 39, 0.16) 0px 28px 52px 0px;
  --shadow-subtle: rgb(255, 241, 205) 0px 0px 0px 1px;
  --shadow-xl-2: rgba(253, 23, 116, 0.6) 0px 14px 35px -18px;
  --shadow-subtle-2: rgba(255, 255, 255, 0.08) 0px 1px 0px 0px inset, rgba(255, 255, 255, 0.03) 0px -1px 0px 0px inset, rgba(0, 0, 0, 0.35) 0px 30px 80px 0px;
}
```
