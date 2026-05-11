# Moxie — Style Reference
> Midnight velvet, shimmering ink

**Theme:** dark

Moxie embraces a dark, atmospheric interface where rich blacks and deep grays provide a dramatic backdrop for subtle typography and a singular, vivid blue accent. Content appears on soft, low-contrast surfaces, outlined by fine borders, creating a quiet depth rather than sharp separation. Typography is a deliberate interplay of classic serifs for impact and clean sans-serifs for detail, all rendered in a warm, near-white hue that feels inviting against the dark theme. The overall aesthetic is one of understated authority, with controlled bursts of color for key interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Background Ink | `#000000` | `--color-background-ink` | Page background, primary dark surface |
| Parchment White | `#f4efd4` | `--color-parchment-white` | Primary text, icon fill, ghost button text and borders, outline for cards |
| Twilight Gray | `#626055` | `--color-twilight-gray` | Muted text, secondary borders, subtle dividers |
| Deep Shadow | `#333333` | `--color-deep-shadow` | Decorative borders, detailed link colors |
| Authority Blue | `#84acfb` | `--color-authority-blue` | Violet action color for filled buttons, selected navigation states, and focused conversion moments. |

## Tokens — Typography

### IBM Plex Serif — Headlines and prominent display text – the delicate weight of 300 for larger sizes lends an antique, authoritative whisper, eschewing typical bold declarations. · `--font-ibm-plex-serif`
- **Substitute:** Source Serif Pro
- **Weights:** 300, 400, 500
- **Sizes:** 17px, 22px, 26px, 28px, 43px, 55px
- **Line height:** 1.10, 1.20
- **Role:** Headlines and prominent display text – the delicate weight of 300 for larger sizes lends an antique, authoritative whisper, eschewing typical bold declarations.

### IBM Plex Sans — Body copy, navigation, buttons, and functional interface elements – provides clarity and legibility for detailed information against a dark background. · `--font-ibm-plex-sans`
- **Substitute:** Inter
- **Weights:** 300, 400, 500
- **Sizes:** 10px, 12px, 14px, 16px, 17px, 24px
- **Line height:** 1.00, 1.20, 1.50
- **Role:** Body copy, navigation, buttons, and functional interface elements – provides clarity and legibility for detailed information against a dark background.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | — | `--text-caption` |
| body | 14px | 1 | — | `--text-body` |
| heading-sm | 22px | 1.1 | — | `--text-heading-sm` |
| heading | 26px | 1.1 | — | `--text-heading` |
| heading-lg | 28px | 1.1 | — | `--text-heading-lg` |
| display-sm | 43px | 1.1 | — | `--text-display-sm` |
| display | 55px | 1.1 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 28 | 28px | `--spacing-28` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 76 | 76px | `--spacing-76` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 1000px |
| cards | 13.8417px |
| buttons | 1000px |
| smallCards | 8.65108px |

### Layout

- **Section gap:** 107px
- **Card padding:** 19px
- **Element gap:** 21px

## Components

### Primary Action Button
**Role:** Interactive element

Filled button with 'Authority Blue' background, 'Parchment White' text, and full pill-shaped '1000px' radius. Padding is 6.92px vertical, 20.76px horizontal. Background color is #84acfb, text color is #f4efd4.

### Ghost Outline Button
**Role:** Interactive element

Ghost button with a subtle 'Parchment White' border and text. The border is 1px, color #f4efd4, and radius is 1000px, creating a delicate pill shape. Text color is #f4efd4.

### Soft Border Card
**Role:** Content container

Content card with no background fill, a rounded border radius of 13.84px, and an interior padding of 19.03px on all sides. Border color is #626055, creating a subtle division.

### Client Logo Card
**Role:** Display brand logos

Transparent background cards for client logos, outlined with a 1px border in 'Parchment White' and a full pill-shaped radius of 1000px. Padding is minimal to contain the logo.

### Quote Card
**Role:** Testimonial display

Card with nearly square corners (0px), transparent background, generous padding of 19.03px on all sides. The content within relies on text color to stand out against the background.

## Do's and Don'ts

### Do
- Prioritize 'Background Ink' (#000000) for all page backgrounds to maintain the deep, dark aesthetic.
- Use 'Parchment White' (#f4efd4) for primary text and icon elements across the interface.
- Apply IBM Plex Serif with a weight of 300 for headlines to achieve an understated, elegant authority.
- Employ the 'Authority Blue' (#84acfb) exclusively for primary interactive elements, such as button backgrounds and key accents, to create high-impact punctuation.
- Utilize a 1000px border-radius for all interactive buttons and tags to ensure a consistent pill-shaped appearance.
- Maintain comfortable density by using 19px for card padding and 21px for element gaps.
- Outline content cards and sections with subtle borders in 'Twilight Gray' (#626055) or 'Parchment White' (#f4efd4) rather than using strong background fills.

### Don't
- Avoid using bright or overly saturated colors beyond 'Authority Blue' to prevent distracting from the dark, sophisticated palette.
- Do not use heavy box shadows; the system relies on subtle borders and transparent fills for depth.
- Refrain from using bold or heavy weights for IBM Plex Serif headlines; the system's impact comes from lightness and restraint.
- Do not introduce additional sans-serif fonts; stick to IBM Plex Sans for all functional text.
- Avoid large blocks of filled background colors for cards or content sections; prefer transparent or subtly bordered containers.
- Do not deviate from the defined border radii; maintain 1000px for buttons and tags, and 13.84px/8.65px for cards.
- Do not use generic system greys; ensure all achromatic elements align with 'Parchment White','Twilight Gray', or 'Deep Shadow'.

## Imagery

The site uses minimal imagery, primarily relying on embedded videos or product shots within framed containers. When present, images are contained within cards, often with rounded corners or subtle borders, blending into the dark interface without harsh edges. There's an implied focus on product showcases or testimonials through video content, rather than decorative photography. Icons are outlined, typically monochrome using 'Parchment White', with thin stroke weights, providing functional clarity without visual clutter. The density is image-light, text-dominant, with visuals serving an explanatory or evidence-based role.

## Layout

The page primarily uses a full-bleed dark background and a centered content area with varying widths. The hero section features a large, centered headline (IBM Plex Serif) over an unadorned dark expanse, immediately establishing the brand's quiet authority. Subsequent sections alternate between full-width presentations (like client logos) and more structured content blocks, often laid out with alternating text-left/visual-right patterns. Testimonials are presented in a horizontal scroll arrangement of transparent cards with subtle borders. Vertical spacing between sections is generous, contributing to a spacious feel despite the content density. Navigation is a minimal top bar with a hamburger menu and a single 'Become a Client' button, reinforcing the uncluttered aesthetic.

## Agent Prompt Guide

### Quick Color Reference
text: #f4efd4
background: #000000
border: #626055
accent: #84acfb
primary action: #84acfb (filled action)

### 3-5 Example Component Prompts
1. Create a Primary Action Button: #84acfb background, #333333 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a ghost button for secondary actions: 1px border in Parchment White (#f4efd4), text in Parchment White (#f4efd4) using IBM Plex Sans weight 400 at 16px, full pill shape (1000px radius).
3. Generate a testimonial card: transparent background, rounded corners (13.8417px radius), 19px padding all around. Body text in Parchment White (#f4efd4) using IBM Plex Sans weight 400 at 14px.
4. Create a hero headline: Centered, using IBM Plex Serif weight 300 at 55px, color Parchment White (#f4efd4).
5. Build a client logo section: Display client logos within transparent cards with a 1px border in Parchment White (#f4efd4), 1000px radius, minimal padding.

## Similar Brands

- **Framer** — Dark UI with subtle accent colors and sophisticated typography, relying on transparency and fine borders for component structure.
- **Linear** — Primarily dark theme, focus on clear information hierarchy with minimal chromatic accents, and understated text styles.
- **Vercel** — Dark aesthetic with high contrast text, occasional use of vivid blues for interactive elements, and a clean interface devoid of heavy graphics.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-background-ink: #000000;
  --color-parchment-white: #f4efd4;
  --color-twilight-gray: #626055;
  --color-deep-shadow: #333333;
  --color-authority-blue: #84acfb;

  /* Typography — Font Families */
  --font-ibm-plex-serif: 'IBM Plex Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.1;
  --text-heading: 26px;
  --leading-heading: 1.1;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 43px;
  --leading-display-sm: 1.1;
  --text-display: 55px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-28: 28px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-76: 76px;

  /* Layout */
  --section-gap: 107px;
  --card-padding: 19px;
  --element-gap: 21px;

  /* Border Radius */
  --radius-lg: 8.65108px;
  --radius-xl: 13.8417px;
  --radius-full: 1000px;

  /* Named Radii */
  --radius-tags: 1000px;
  --radius-cards: 13.8417px;
  --radius-buttons: 1000px;
  --radius-smallcards: 8.65108px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-background-ink: #000000;
  --color-parchment-white: #f4efd4;
  --color-twilight-gray: #626055;
  --color-deep-shadow: #333333;
  --color-authority-blue: #84acfb;

  /* Typography */
  --font-ibm-plex-serif: 'IBM Plex Serif', ui-serif, Georgia, Cambria, "Times New Roman", Times, serif;
  --font-ibm-plex-sans: 'IBM Plex Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --text-body: 14px;
  --leading-body: 1;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.1;
  --text-heading: 26px;
  --leading-heading: 1.1;
  --text-heading-lg: 28px;
  --leading-heading-lg: 1.1;
  --text-display-sm: 43px;
  --leading-display-sm: 1.1;
  --text-display: 55px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-28: 28px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-76: 76px;

  /* Border Radius */
  --radius-lg: 8.65108px;
  --radius-xl: 13.8417px;
  --radius-full: 1000px;
}
```
