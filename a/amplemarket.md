# Amplemarket — Style Reference
> Subtle dynamism on a crisp canvas

**Theme:** light

Amplemarket presents a high-tech sales platform aesthetic using a predominantly neutral palette punctuated by dynamic, soft-edged gradients. The visual system balances strong, clean typography with subtle, layered surface treatments, and sparse, vibrant background accents that suggest energy and movement. Interactive elements are clearly defined, often contrasting crisp type against dark fills or light backgrounds. The overall impression is one of restrained power and sophisticated utility.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#111111` | `--color-midnight-ink` | Primary text, icon fills, dominant backgrounds on dark sections, heavy borders |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, light surface backgrounds, text on dark sections, subtle borders |
| Surface Charcoal | `#272625` | `--color-surface-charcoal` | Elevated card backgrounds, input backgrounds |
| Muted Ash | `#6d6c6b` | `--color-muted-ash` | Secondary text, subtle borders, inactive states |
| Whisper Gray | `#f4f3ef` | `--color-whisper-gray` | Subtle background panels, light hover states |
| Light Taupe | `#ecebea` | `--color-light-taupe` | Ghost button backgrounds, subtle surface variations |
| Phoenix Orange | `radial-gradient(386.06% 162.79% at -13.1926% -17.1008%, rgb(232, 64, 13) 0%, rgb(255, 238, 216) 26.1559%, rgb(208, 178, 255) 84.1533%)` | `--color-phoenix-orange` | Accent for dynamic backgrounds and gradients, pillar highlights; Decorative background graphic, giving sections a vibrant, flowing feel |
| Cyan Glow | `radial-gradient(80.17% 109.2% at 52.1169% 62.5363%, rgb(208, 178, 255) 0%, rgb(198, 236, 233) 35.282%, rgb(153, 255, 249) 96.5565%)` | `--color-cyan-glow` | Accent for dynamic backgrounds and gradients, pillar highlights; Decorative background graphic, providing a cool counterpart to warmer gradient tones |
| Deep Indigo | `#10054d` | `--color-deep-indigo` | Distinct element coloring, primary button text on light backgrounds |
| Petal Pink | `#ffd7f0` | `--color-petal-pink` | Soft accent cards, decorative background elements |
| Mint Green | `#b7efb2` | `--color-mint-green` | Soft accent cards, decorative background elements |
| Canary Yellow | `#ffef99` | `--color-canary-yellow` | Soft accent cards, decorative background elements |
| Subtle Lavender | `#e2ddfd` | `--color-subtle-lavender` | Soft accent cards, decorative background elements |
| Midnight Violet | `#2e2460` | `--color-midnight-violet` | Violet state accent for badges, validation surfaces, and short status labels. Do not promote it to the primary CTA color |
| Engagement Gold | `#fbc768` | `--color-engagement-gold` | Yellow wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| LeadGen Red | `#e16540` | `--color-leadgen-red` | Orange wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Intelligence Blue | `#328efa` | `--color-intelligence-blue` | Blue wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |
| Deliver Green | `#47d096` | `--color-deliver-green` | Green wash for highlight backgrounds, decorative bands, and soft emphasis behind content. Use as a supporting accent, not as a status color |

## Tokens — Typography

### Labil Grotesk Variable — Primary typeface for all text elements. The variable font allows for fine-tuned expression across headers and body copy, giving a consistent, modern, and precise feel. The distinct letter-spacing adjustments, particularly negative tracking for larger sizes, create a sharp, intentional rhythm for headlines. · `--font-labil-grotesk-variable`
- **Substitute:** Inter
- **Weights:** 400, 500, 700, 900
- **Sizes:** 8px, 10px, 12px, 14px, 16px, 20px, 24px, 28px, 36px, 44px, 56px, 84px
- **Line height:** 0.80, 1.00, 1.10, 1.20, 1.30
- **Letter spacing:** -0.0500em at 84px, -0.0400em at 56px, -0.0300em at 44px, -0.0200em at 36px, -0.0170em at 28px, -0.0110em at 24px, -0.0100em at 20px, normal at 16px, 0.0250em at 14px, 0.0300em at 12px
- **OpenType features:** `"ss02", "ss01"`
- **Role:** Primary typeface for all text elements. The variable font allows for fine-tuned expression across headers and body copy, giving a consistent, modern, and precise feel. The distinct letter-spacing adjustments, particularly negative tracking for larger sizes, create a sharp, intentional rhythm for headlines.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | 0.3px | `--text-caption` |
| body | 14px | 1.3 | 0.25px | `--text-body` |
| subheading | 20px | 1.1 | -0.2px | `--text-subheading` |
| heading-sm | 24px | 1.1 | -0.26px | `--text-heading-sm` |
| heading | 28px | 1.1 | -0.48px | `--text-heading` |
| heading-lg | 44px | 1.1 | -1.32px | `--text-heading-lg` |
| display | 56px | 1 | -2.24px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 56 | 56px | `--spacing-56` |
| 84 | 84px | `--spacing-84` |
| 100 | 100px | `--spacing-100` |
| 112 | 112px | `--spacing-112` |
| 144 | 144px | `--spacing-144` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| icons | 12px |
| badges | 12px |
| images | 12px |
| inputs | 12px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(17, 17, 17, 0.05) 0px 0px 0px 1px inset` | `--shadow-subtle` |
| xl | `rgba(17, 17, 17, 0.12) 0px 26px 60px -6px, rgba(17, 17, 1...` | `--shadow-xl` |
| sm | `rgba(17, 17, 17, 0.02) 0px -6px 6px 0px, rgba(17, 17, 17,...` | `--shadow-sm` |
| subtle-2 | `rgba(17, 17, 17, 0.05) 0px 0px 1px 0px, rgba(17, 17, 17, ...` | `--shadow-subtle-2` |
| xl-2 | `rgba(25, 34, 35, 0.12) 0px 26px 60px -6px, rgba(25, 34, 3...` | `--shadow-xl-2` |
| subtle-3 | `rgba(17, 17, 17, 0.04) 0px 1px 2px 0px, rgba(17, 17, 17, ...` | `--shadow-subtle-3` |

### Layout

- **Section gap:** 56px
- **Card padding:** 20px
- **Element gap:** 8px

## Components

### Primary Filled Button - Dark
**Role:** Call to action button for primary actions.

Solid Midnight Ink background, Canvas White text. Rounded corners at 8px radius. Padding: 12px vertical, 16px horizontal. Font set to 'Labil Grotesk Variable', weight 500, size based on context (e.g., 16px).

### Default Button - Light
**Role:** Secondary action button, standard interactive element.

Solid Canvas White background, Deep Indigo text. Rounded corners at 8px radius. Padding: 12px vertical, 16px horizontal. Font set to 'Labil Grotesk Variable', weight 500.

### Ghost Button
**Role:** Tertiary actions, navigation items, or subtle interactive elements.

Transparent background, Muted Ash text when inactive, Canvas White on dark backgrounds. Rounded corners at 8px radius. Padding: 12px vertical, 16px horizontal, or 6px vertical, 14px horizontal for smaller instances. No visible border.

### Card - Elevated Light
**Role:** Container for featured content, testimonials, or key information.

Canvas White background with a subtle shadow (rgba(17, 17, 17, 0.02) 0px -6px 6px 0px, rgba(17, 17, 17, 0.01) 0px -23px 9px 0px). Rounded corners at 12px radius. Content padding is 20px.

### Card - Client Logo
**Role:** Container for client logos with light background.

Whisper Gray background, no shadow. Rounded corners at 12px radius. Internal padding 16px vertical, 20px horizontal.

### Card - Accent Colored
**Role:** Decorative cards using brand or accent colors.

Backgrounds in Petal Pink, Mint Green, Canary Yellow, or Subtle Lavender. No shadow. Rounded corners at 12px. Padding is implicitly driven by content.

### Input Field - Light
**Role:** Standard user input field on light backgrounds.

Canvas White background, Midnight Ink text. Border in rgba(17, 17, 17, 0.08). Rounded corners at 12px. Padding: 0px vertical, 16px horizontal.

### Input Field - Dark
**Role:** Standard user input field on dark backgrounds.

Midnight Violet background, Canvas White text. Border in rgba(255, 255, 255, 0.08). Rounded corners at 12px. Padding: 0px vertical, 16px horizontal.

### Navigation Link
**Role:** Primary navigation items in the header.

Ghost button styling with Muted Ash text. No explicit background or border. Tight spacing suitable for navigation menus. Padding 6px vertical, 14px horizontal.

### Info Badge - Inline
**Role:** Small, informative labels appearing within content.

Surface Charcoal background with Canvas White text. Rounded corners at 12px. Tight padding: 8px vertical, 10px horizontal. Font size 12px.

## Do's and Don'ts

### Do
- Use Labil Grotesk Variable with specific letter-spacing adjustments: larger text sizes from 20px up should have negative tracking, while smaller body text (14px, 12px) uses positive tracking to maintain readability.
- Prioritize Canvas White (#ffffff) for dominant page backgrounds and Midnight Ink (#111111) for primary text, creating high contrast.
- Apply 12px border radius to most containers: cards, inputs, and selected interactive elements, with 8px reserved for primary buttons and nav items.
- Intersperse sections with vibrant, soft-edged radial gradients (`Dynamic Energy Gradient 1` and `Dynamic Energy Gradient 2`) to introduce visual dynamism.
- When creating cards for features or client logos, use Whisper Gray (#f4f3ef) backgrounds to subtly differentiate them from the main canvas.
- Apply default elementGap of 8px for tight spacing between components, increasing to 20px for cardPadding and 56px for sectionGap to establish clear visual hierarchy.
- Utilize the pillar highlight colors (Engagement Gold, LeadGen Red, Intelligence Blue, Deliver Green) for small, functional accents such as icons or tags related to their respective categories.

### Don't
- Avoid using bright, saturated colors for large background areas unless they are part of a soft-edged gradient effect.
- Do not use generic system fonts; always specify 'Labil Grotesk Variable' to maintain brand consistency.
- Do not add heavy or opaque shadows; elevation should be subtle, employing diluted rgba(17, 17, 17, 0.02-0.05) values.
- Do not vary border radius arbitrarily; stick to 12px for cards/inputs and 8px for buttons/nav to maintain a consistent visual language.
- Do not use default browser blue for links; all links should use Midnight Ink text color or Canvas White on dark backgrounds, with explicit hover states.
- Do not use outline buttons for primary calls to action; reserve solid fill buttons (Primary Filled Button - Dark) for clear actionable items.
- Do not clutter layouts; maintain comfortable spacing with an 8px base unit and larger gaps for sections to provide breathing room.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Primary page background layer, providing a clean neutral base. |
| 1 | Whisper Gray | `#f4f3ef` | Slightly elevated background for content sections or client logo grids, adding subtle depth. |
| 2 | Surface Charcoal | `#272625` | Background for secondary containers like input fields on dark themes, or informational badges, providing distinct contrast. |

## Elevation

- **Card - Elevated Light:** `rgba(17, 17, 17, 0.02) 0px -6px 6px 0px, rgba(17, 17, 17, 0.01) 0px -23px 9px 0px`
- **Header/Floating Elements:** `rgba(17, 17, 17, 0.05) 0px 0px 1px 0px, rgba(17, 17, 17, 0.04) 1px 1px 1px 0px, rgba(17, 17, 17, 0.03) 2px 3px 2px 0px, rgba(17, 17, 17, 0.01) 4px 4px 2px 0px`
- **Button/Interactive Element:** `rgba(17, 17, 17, 0.04) 0px 1px 2px 0px, rgba(17, 17, 17, 0.04) 0px 4px 8px 0px`

## Imagery

Amplemarket utilizes a mix of abstract generative graphics, technical line-art illustrations, and product-focused images. The abstract graphics are soft, blurred radial gradients that introduce vibrant color and movement, often appearing as background elements. Illustrations are minimalist, outlined, and depict technological concepts (e.g., a rocket-powered box). Photography, if present, is primarily product screenshots or tight crops focused on UI elements, lacking human subjects or lifestyle contexts. Icons are outlined, lightweight, and mono-color, typically Midnight Ink or Canvas White. Imagery serves both decorative ambient roles and explanatory functions, highlighting features or conveying a technological mood. The density of imagery is balanced, with large key visuals followed by more text-dominant sections, but images always feel contained and intentional.

## Layout

The page primarily uses a max-width contained layout for core content, centered on the screen. The hero section is full-bleed, featuring a centered headline and input area over an atmospheric, diffused gradient background. Sections maintain a consistent vertical rhythm, with generous section gaps. Content is arranged in alternating patterns, often a large visual/gradient followed by a section with a grid of 2-3 column cards or alternating text-left/image-right blocks. The navigation is a sticky top bar, appearing slightly elevated (subtle shadow) and centered with functional 'Open app' and 'Get free trial' buttons.

## Agent Prompt Guide

### Quick Color Reference
- text: #111111
- background: #ffffff
- border: #11111114 (Midnight Ink at 8% opacity)
- accent: #e8400d
- primary action: no distinct CTA color

### 3-5 Example Component Prompts
No distinct primary action color was observed; use the extracted neutral button treatments instead of inventing a filled CTA color.
2. Design a 3-column client logo grid. Each cell is a Card - Client Logo (#f4f3ef background, 12px radius, 20px internal padding), containing a client logo image and Muted Ash (#6d6c6b) text 'Migrated off Apollo'. The grid should have 24px column and row gaps.

## Similar Brands

- **Anthropic** — Shares a sophisticated AI-focused aesthetic, balancing minimal UI with subtle gradient accents and crisp typography.
- **Linear** — Similar approach to clean, functional UI, emphasizing typography and subtle surface differentiation on a light theme.
- **Vercel** — Combines a dark background for brand elements with light content areas, utilizing strong typography and measured spacing.
- **Paddle** — Uses a blend of strong dark backgrounds with contrasting light elements and a clear, modern typographic hierarchy, often featuring soft, abstract background visual effects.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-canvas-white: #ffffff;
  --color-surface-charcoal: #272625;
  --color-muted-ash: #6d6c6b;
  --color-whisper-gray: #f4f3ef;
  --color-light-taupe: #ecebea;
  --color-phoenix-orange: #e8400d;
  --gradient-phoenix-orange: radial-gradient(386.06% 162.79% at -13.1926% -17.1008%, rgb(232, 64, 13) 0%, rgb(255, 238, 216) 26.1559%, rgb(208, 178, 255) 84.1533%);
  --color-cyan-glow: #99fff9;
  --gradient-cyan-glow: radial-gradient(80.17% 109.2% at 52.1169% 62.5363%, rgb(208, 178, 255) 0%, rgb(198, 236, 233) 35.282%, rgb(153, 255, 249) 96.5565%);
  --color-deep-indigo: #10054d;
  --color-petal-pink: #ffd7f0;
  --color-mint-green: #b7efb2;
  --color-canary-yellow: #ffef99;
  --color-subtle-lavender: #e2ddfd;
  --color-midnight-violet: #2e2460;
  --color-engagement-gold: #fbc768;
  --color-leadgen-red: #e16540;
  --color-intelligence-blue: #328efa;
  --color-deliver-green: #47d096;

  /* Typography — Font Families */
  --font-labil-grotesk-variable: 'Labil Grotesk Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: 0.3px;
  --text-body: 14px;
  --leading-body: 1.3;
  --tracking-body: 0.25px;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.26px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.32px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -2.24px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;
  --font-weight-black: 900;

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
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-84: 84px;
  --spacing-100: 100px;
  --spacing-112: 112px;
  --spacing-144: 144px;

  /* Layout */
  --section-gap: 56px;
  --card-padding: 20px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-icons: 12px;
  --radius-badges: 12px;
  --radius-images: 12px;
  --radius-inputs: 12px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-subtle: rgba(17, 17, 17, 0.05) 0px 0px 0px 1px inset;
  --shadow-xl: rgba(17, 17, 17, 0.12) 0px 26px 60px -6px, rgba(17, 17, 17, 0.02) 0px 28px 28px -14px, rgba(17, 17, 17, 0.04) 0px 6px 6px -3px, rgba(17, 17, 17, 0.04) 0px 1px 1px -0.5px;
  --shadow-sm: rgba(17, 17, 17, 0.02) 0px -6px 6px 0px, rgba(17, 17, 17, 0.01) 0px -23px 9px 0px;
  --shadow-subtle-2: rgba(17, 17, 17, 0.05) 0px 0px 1px 0px, rgba(17, 17, 17, 0.04) 1px 1px 1px 0px, rgba(17, 17, 17, 0.03) 2px 3px 2px 0px, rgba(17, 17, 17, 0.01) 4px 4px 2px 0px;
  --shadow-xl-2: rgba(25, 34, 35, 0.12) 0px 26px 60px -6px, rgba(25, 34, 35, 0.02) 0px 28px 28px -14px, rgba(25, 34, 35, 0.04) 0px 6px 6px -3px, rgba(25, 34, 35, 0.04) 0px 1px 1px -0.5px;
  --shadow-subtle-3: rgba(17, 17, 17, 0.04) 0px 1px 2px 0px, rgba(17, 17, 17, 0.04) 0px 4px 8px 0px, rgba(17, 17, 17, 0.04) 0px 0px 1px 0px, rgba(17, 17, 17, 0.04) 0px 0px 1px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-whisper-gray: #f4f3ef;
  --surface-surface-charcoal: #272625;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #111111;
  --color-canvas-white: #ffffff;
  --color-surface-charcoal: #272625;
  --color-muted-ash: #6d6c6b;
  --color-whisper-gray: #f4f3ef;
  --color-light-taupe: #ecebea;
  --color-phoenix-orange: #e8400d;
  --color-cyan-glow: #99fff9;
  --color-deep-indigo: #10054d;
  --color-petal-pink: #ffd7f0;
  --color-mint-green: #b7efb2;
  --color-canary-yellow: #ffef99;
  --color-subtle-lavender: #e2ddfd;
  --color-midnight-violet: #2e2460;
  --color-engagement-gold: #fbc768;
  --color-leadgen-red: #e16540;
  --color-intelligence-blue: #328efa;
  --color-deliver-green: #47d096;

  /* Typography */
  --font-labil-grotesk-variable: 'Labil Grotesk Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: 0.3px;
  --text-body: 14px;
  --leading-body: 1.3;
  --tracking-body: 0.25px;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --tracking-subheading: -0.2px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.1;
  --tracking-heading-sm: -0.26px;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 44px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -1.32px;
  --text-display: 56px;
  --leading-display: 1;
  --tracking-display: -2.24px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-56: 56px;
  --spacing-84: 84px;
  --spacing-100: 100px;
  --spacing-112: 112px;
  --spacing-144: 144px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-subtle: rgba(17, 17, 17, 0.05) 0px 0px 0px 1px inset;
  --shadow-xl: rgba(17, 17, 17, 0.12) 0px 26px 60px -6px, rgba(17, 17, 17, 0.02) 0px 28px 28px -14px, rgba(17, 17, 17, 0.04) 0px 6px 6px -3px, rgba(17, 17, 17, 0.04) 0px 1px 1px -0.5px;
  --shadow-sm: rgba(17, 17, 17, 0.02) 0px -6px 6px 0px, rgba(17, 17, 17, 0.01) 0px -23px 9px 0px;
  --shadow-subtle-2: rgba(17, 17, 17, 0.05) 0px 0px 1px 0px, rgba(17, 17, 17, 0.04) 1px 1px 1px 0px, rgba(17, 17, 17, 0.03) 2px 3px 2px 0px, rgba(17, 17, 17, 0.01) 4px 4px 2px 0px;
  --shadow-xl-2: rgba(25, 34, 35, 0.12) 0px 26px 60px -6px, rgba(25, 34, 35, 0.02) 0px 28px 28px -14px, rgba(25, 34, 35, 0.04) 0px 6px 6px -3px, rgba(25, 34, 35, 0.04) 0px 1px 1px -0.5px;
  --shadow-subtle-3: rgba(17, 17, 17, 0.04) 0px 1px 2px 0px, rgba(17, 17, 17, 0.04) 0px 4px 8px 0px, rgba(17, 17, 17, 0.04) 0px 0px 1px 0px, rgba(17, 17, 17, 0.04) 0px 0px 1px 0px;
}
```
