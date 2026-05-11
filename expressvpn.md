# ExpressVPN — Style Reference
> Secure utility, bright teal highlights

**Theme:** light

ExpressVPN utilizes a 'Confident Utility' visual language, combining a clean light canvas with distinct brand-colored accents for critical actions and information. The design promotes trust and clarity through a high-contrast monochromatic base, softened by rounded corners and subtle elevation for focal elements. Typography is precise and direct, avoiding flourishes, consistently driving attention to key product offerings and security benefits. The overall impression is professional and secure, with a clear hierarchy established through color and weight.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#001d2f` | `--color-midnight-ink` | Primary text, deep surface backgrounds, navigation elements, input borders, button text for ghost/outlined buttons |
| Cloud White | `#ffffff` | `--color-cloud-white` | Card backgrounds, primary surface background for specific components, essential text on dark backgrounds, selected badge backgrounds |
| Ghost Gray | `#f7f8f9` | `--color-ghost-gray` | Page background, secondary background for navigation elements, tertiary card backgrounds |
| Cool Stone | `#ccd2d5` | `--color-cool-stone` | Hairline borders, subtle dividers, secondary text, muted icon fills |
| Slate Blue | `#667782` | `--color-slate-blue` | Muted body text, helper text, and decorative icon fills |
| Forest Teal | `#0f866c` | `--color-forest-teal` | Primary action buttons, accented headings, highlighted links, functional card accents. This vibrant teal signifies activation and important calls to action |
| Dark Teal | `#00695c` | `--color-dark-teal` | Accent color for specific navigation items and active states, providing a deeper tonal variation of the brand's primary color |
| Warm Beige | `#f0eacf` | `--color-warm-beige` | Subtle background accent in navigation, providing a touch of warmth |
| Soft Peach | `#ffe4d4` | `--color-soft-peach` | Subtle background for specific card sections, introducing a soft, pastel accent |
| Sky Mist | `#b7d1d0` | `--color-sky-mist` | Background for specific card sections, a light, cool accent color |
| Light Mint | `#c3ece8` | `--color-light-mint` | Background for subtle accents within navigation, a very light, cool accent |
| Crimson Glow | `radial-gradient(circle, rgb(218, 57, 64) 0px, rgb(176, 39, 45) 100%)` | `--color-crimson-glow` | Highlight gradient, used for specific alerts or promotional banners, suggesting warmth and urgency |
| Deep Ocean Gradient | `linear-gradient(261deg, rgb(12, 57, 86) 21.96%, rgb(0, 24, 39) 82.57%)` | `--color-deep-ocean-gradient` | Background for hero sections or prominent feature blocks, creating depth and a sense of security |

## Tokens — Typography

### Inter — Body text, navigation items, button labels, and small descriptive text. It maintains clarity and a functional aesthetic across various contexts. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.00, 1.20, 1.33, 1.44, 1.50, 1.67, 1.72, 1.75, 1.80, 1.83, 1.90, 2.00
- **Letter spacing:** 0.1em, 0.133em, 0.14em
- **OpenType features:** `'palt'`
- **Role:** Body text, navigation items, button labels, and small descriptive text. It maintains clarity and a functional aesthetic across various contexts.

### Inter — Medium weight for specific body text, emphasized navigation, and subtitles. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.00, 1.20, 1.33, 1.44, 1.50, 1.67, 1.72, 1.75, 1.80, 1.83, 1.90, 2.00
- **Letter spacing:** 0.1em, 0.133em, 0.14em
- **OpenType features:** `'palt'`
- **Role:** Medium weight for specific body text, emphasized navigation, and subtitles.

### Inter — Semibold for strong emphasis in body text, navigation highlights, and subheadings. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.00, 1.20, 1.33, 1.44, 1.50, 1.67, 1.72, 1.75, 1.80, 1.83, 1.90, 2.00
- **Letter spacing:** 0.1em, 0.133em, 0.14em
- **OpenType features:** `'palt'`
- **Role:** Semibold for strong emphasis in body text, navigation highlights, and subheadings.

### Inter — Bold text for clear headings, active states, and important short phrases. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 20px, 24px
- **Line height:** 1.00, 1.20, 1.33, 1.44, 1.50, 1.67, 1.72, 1.75, 1.80, 1.83, 1.90, 2.00
- **Letter spacing:** 0.1em, 0.133em, 0.14em
- **OpenType features:** `'palt'`
- **Role:** Bold text for clear headings, active states, and important short phrases.

### Arial — Fallback and utility text, often for legacy components or system-level prompts. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400, 700
- **Sizes:** 13px, 18px
- **Line height:** 1.20, 1.45
- **Letter spacing:** normal
- **Role:** Fallback and utility text, often for legacy components or system-level prompts.

### Arial — Bold fallback text, similar to the regular weight but for stronger emphasis. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400, 700
- **Sizes:** 13px, 18px
- **Line height:** 1.20, 1.45
- **Letter spacing:** normal
- **Role:** Bold fallback text, similar to the regular weight but for stronger emphasis.

### FS Kim — Distinctive headings and display text, particularly for hero sections. Its precise tracking at larger sizes implies modern authority without being overly decorative. · `--font-fs-kim`
- **Substitute:** serif
- **Weights:** 500, 700
- **Sizes:** 18px, 32px, 46px, 64px
- **Line height:** 1.00, 1.09, 1.25
- **Letter spacing:** -0.016em
- **OpenType features:** `'palt'`
- **Role:** Distinctive headings and display text, particularly for hero sections. Its precise tracking at larger sizes implies modern authority without being overly decorative.

### FS Kim — Bold headings and display text, used for primary headlines where maximum impact is required through size and weight. · `--font-fs-kim`
- **Substitute:** serif
- **Weights:** 500, 700
- **Sizes:** 18px, 32px, 46px, 64px
- **Line height:** 1.00, 1.09, 1.25
- **Letter spacing:** -0.016em
- **OpenType features:** `'palt'`
- **Role:** Bold headings and display text, used for primary headlines where maximum impact is required through size and weight.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.1px | `--text-caption` |
| body | 14px | 1.72 | — | `--text-body` |
| body-lg | 16px | 1.83 | — | `--text-body-lg` |
| subheading | 18px | 1.67 | -0.016px | `--text-subheading` |
| heading | 24px | 1.5 | — | `--text-heading` |
| heading-lg | 32px | 1.25 | -0.016px | `--text-heading-lg` |
| display | 64px | 1 | -0.016px | `--text-display` |

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
| 44 | 44px | `--spacing-44` |
| 64 | 64px | `--spacing-64` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 104 | 104px | `--spacing-104` |
| 196 | 196px | `--spacing-196` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 10px |
| cards | 24px |
| badges | 24px |
| inputs | 10px |
| buttons | 34px |
| navItems | 4px |
| extraLarge | 1132.2px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.12) 0px 0px 32px 0px` | `--shadow-xl` |
| md | `rgba(0, 0, 0, 0.1) 0px 0px 15px 0px` | `--shadow-md` |
| md-2 | `rgba(0, 0, 0, 0.12) 0px 4px 16px 0px` | `--shadow-md-2` |

### Layout

- **Section gap:** 24px
- **Card padding:** 32px
- **Element gap:** 24px

## Components

### Primary Action Button
**Role:** Filled button indicating primary calls to action

Background: Forest Teal (#0f866c), Text: Cloud White (#ffffff), Border Radius: 34px, Padding: 14px vertical, 24px horizontal. Represents a key interactive element.

### Ghost Button
**Role:** Outlined button for secondary actions or navigation.

Background: transparent (#00000000), Text: Midnight Ink (#001d2f), Border: 1px solid Midnight Ink (#001d2f), Border Radius: 10px, Padding: 21px vertical, 40px horizontal.

### Subtle Ghost Button
**Role:** Outlined button with lighter background for less prominent actions.

Background: Ghost Gray (#f7f8f9), Text: Midnight Ink (#001d2f), Border: none, Border Radius: 10px, Padding: 21px vertical, 40px horizontal. Softened visual weight.

### Inline Text Link
**Role:** Non-button interactive text within content.

Background: transparent (#00000000), Text: Midnight Ink (#001d2f), Border: none, Padding: 13px vertical, 0px horizontal.

### Elevated Feature Card
**Role:** Prominent information card with emphasis.

Background: Cloud White (#ffffff), Border Radius: 24px, Box Shadow: rgba(0, 0, 0, 0.12) 0px 0px 32px 0px, Padding: 32px all sides. Used for important content blocks with visual separation.

### Neutral Content Card
**Role:** Standard content grouping without strong visual hierarchy.

Background: transparent (#00000000), Border Radius: 0px, Box Shadow: none, Padding: 100px vertical, 0px horizontal. Acts as a divider or section for related content.

### Subtle Feature Card
**Role:** Card with slight background distinction.

Background: Ghost Gray (#f7f8f9), Border Radius: 32px, Box Shadow: none, Padding: 24px all sides. Used for sections that need a slight distinction from the page background.

### Accent Card
**Role:** Card with the primary brand color background for high importance.

Background: Forest Teal (#0f866c), Border Radius: 20px, Box Shadow: rgba(0, 0, 0, 0.1) 0px 0px 15px 0px, Padding: 30px all sides. Draws significant attention to its content.

### Informative Badge
**Role:** Small informational tag or label.

Background: Cloud White (#ffffff), Text: Midnight Ink (#001d2f), Border Radius: 24px, Padding: 24px vertical, 40px horizontal. Often used for status or categorization.

### Chat Widget Badge
**Role:** Interactive chat notification badge.

Background: Cloud White (#ffffff), Text: Midnight Ink (#001d2f), Border: 1px solid Cool Stone (#adadad), Border Radius: 24px, Box Shadow: rgba(0, 0, 0, 0.12) 0px 4px 16px 0px, Padding: 24px vertical, 40px horizontal.

## Do's and Don'ts

### Do
- Use FS Kim weight 500 or 700 with -0.016em letter-spacing for all primary headings (h1, h2, h3) to maintain a modern, crisp feel.
- Apply Forest Teal (#0f866c) for primary action buttons and key monetary values in headlines to draw immediate attention.
- Adhere to Cloud White (#ffffff) for elevated card backgrounds and Hero Gray (#f7f8f9) for global page backgrounds to establish clear surface hierarchy.
- Implement a 24px border-radius for all primary content cards and badges to ensure consistent softness and approachability.
- Utilize Midnight Ink (#001d2f) for all body text, navigation labels, and borders of ghost buttons, ensuring strong contrast and readability.
- Maintain 32px padding for elevated content cards, ensuring ample visual breathing room within structured elements.
- Employ a 34px border-radius for primary action buttons to give them a distinct, pill-like appearance.

### Don't
- Avoid using highly saturated colors for large background areas or extensive text blocks, as the system relies on a neutral canvas with targeted accents.
- Do not deviate from the Inter typeface for body copy and navigational elements; reserve FS Kim exclusively for larger headlines and display text.
- Do not use sharp 0px corners for cards or buttons that convey actions or significant information; maintain rounded edges for a consistent brand feel.
- Refrain from introducing decorative gradients outside of the two specified accent gradients (Crimson Glow and Deep Ocean Gradient).
- Do not apply heavy, opaque shadows to elements that are not feature cards or interactive badges; rely on subtle elevation for most UI elements.
- Avoid arbitrary changes to letter spacing for body text; only apply the specified negative tracking for FS Kim headings and the positive tracking for Inter utility text.
- Do not use #001d2f as a primary text color against backgrounds other than #f7f8f9 or #ffffff; check contrast ratios carefully.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Page Canvas | `#f7f8f9` | The default background for the entire page, providing a light, crisp base. |
| 2 | Standard Surface | `#ffffff` | Used for main content cards, badges, and primary components, providing distinct elevation from the page canvas. |
| 3 | Accent Surface | `#0f866c` | Used for highly prominent cards or sections where immediate attention is required, leveraging the primary brand color. |

## Elevation

- **Elevated Feature Card:** `rgba(0, 0, 0, 0.12) 0px 0px 32px 0px`
- **Accent Card:** `rgba(0, 0, 0, 0.1) 0px 0px 15px 0px`
- **Chat Widget Badge:** `rgba(0, 0, 0, 0.12) 0px 4px 16px 0px`

## Imagery

The imagery leans towards product-focused presentation, featuring clean, modern product shots (e.g., phone UI) with contextually relevant, minimal UI elements. Iconography is clean and functional, generally outlined or monochrome with a medium stroke weight. There's a minimal use of abstract graphics (like subtle background gradients) for atmospheric depth rather than decorative content. Photography is absent. Imagery primarily serves an explanatory and product showcase role, with a focus on clarity and directness, not heavy. The density is moderate, with images typically contained within the layout rather than full-bleed.

## Layout

The page exhibits a max-width contained layout, likely around a 1200px equivalent, with content consistently centered. The hero section features a prominent centered headline over a background that can vary from a deep gradient to a softer fill. Subsequent sections employ distinct visual banding, often alternating between the Ghost Gray (#f7f8f9) page canvas and Cloud White (#ffffff) content blocks. Content arrangement frequently uses a centered stack for textual information, transitioning to a simple 2-column or card grid for features. Navigation is a sticky top bar with clearly segmented links and a distinct 'Get Started' button. Vertical spacing between sections is generous and consistent, creating a comfortable, open density.

## Agent Prompt Guide

Quick Color Reference: 
text: #001d2f
background: #f7f8f9
border: #ccd2d5
accent: #0f866c
primary action: #0f866c (filled action)

Example Component Prompts:
1. Create a Hero Section: Background is Deep Ocean Gradient, headline 'World’s #1 VPN. Now at $2.79/mo.' uses FS Kim weight 700 at 64px, #ffffff, letter-spacing -0.016em. Subheadline 'Your all-in-one app for online privacy, security, and freedom' uses Inter weight 400 at 20px, #ffffff. Centered Primary Action Button 'Get the Deal Now' (#0f866c background, #ffffff text, 34px radius, 14px vertical 24px horizontal padding).
2. Create an Elevated Feature Card: Background Cloud White (#ffffff), 24px radius, box-shadow 'rgba(0, 0, 0, 0.12) 0px 0px 32px 0px', 32px padding all sides. Headline 'Why ExpressVPN?' uses FS Kim weight 500 at 32px, #001d2f. Body text 'Discover the benefits.' uses Inter weight 400 at 16px, #001d2f.
3. Create a Ghost Button: Transparent background, text 'Explore ExpressVPN' in Midnight Ink (#001d2f) using Inter weight 400 at 16px, 1px solid Midnight Ink (#001d2f) border, 10px radius, 21px vertical 40px horizontal padding.
4. Create an Accent Card: Background Forest Teal (#0f866c), 20px radius, box-shadow 'rgba(0, 0, 0, 0.1) 0px 0px 15px 0px', 30px padding all sides. Text in Cloud White (#ffffff), such as '30-DAY MONEY-BACK GUARANTEE FOR FIRST-TIME USERS' using Inter weight 700 at 14px.

## Similar Brands

- **NordVPN** — Similar focus on cybersecurity, often uses dark/light modes with a strong brand accent, and clear, functional typography.
- **ProtonVPN** — Shares a clean, modern UI aesthetic, a focus on privacy, and a functional color palette with a prominent brand accent color.
- **Cloudflare** — Employs a stark, high-contrast UI with a single vivid accent color for key actions, emphasizing technical utility and performance, large, confident display typography.
- **LastPass** — Utilizes a clear, direct visual design with a dominant brand color for trust and action, clean card-based layouts, and functional iconography.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #001d2f;
  --color-cloud-white: #ffffff;
  --color-ghost-gray: #f7f8f9;
  --color-cool-stone: #ccd2d5;
  --color-slate-blue: #667782;
  --color-forest-teal: #0f866c;
  --color-dark-teal: #00695c;
  --color-warm-beige: #f0eacf;
  --color-soft-peach: #ffe4d4;
  --color-sky-mist: #b7d1d0;
  --color-light-mint: #c3ece8;
  --color-crimson-glow: #da3940;
  --gradient-crimson-glow: radial-gradient(circle, rgb(218, 57, 64) 0px, rgb(176, 39, 45) 100%);
  --color-deep-ocean-gradient: #0c3956;
  --gradient-deep-ocean-gradient: linear-gradient(261deg, rgb(12, 57, 86) 21.96%, rgb(0, 24, 39) 82.57%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fs-kim: 'FS Kim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body: 14px;
  --leading-body: 1.72;
  --text-body-lg: 16px;
  --leading-body-lg: 1.83;
  --text-subheading: 18px;
  --leading-subheading: 1.67;
  --tracking-subheading: -0.016px;
  --text-heading: 24px;
  --leading-heading: 1.5;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.016px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.016px;

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
  --spacing-44: 44px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-196: 196px;
  --spacing-200: 200px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 32px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 34px;
  --radius-full: 1132.2px;

  /* Named Radii */
  --radius-tags: 10px;
  --radius-cards: 24px;
  --radius-badges: 24px;
  --radius-inputs: 10px;
  --radius-buttons: 34px;
  --radius-navitems: 4px;
  --radius-extralarge: 1132.2px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.12) 0px 0px 32px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 0px 15px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.12) 0px 4px 16px 0px;

  /* Surfaces */
  --surface-page-canvas: #f7f8f9;
  --surface-standard-surface: #ffffff;
  --surface-accent-surface: #0f866c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #001d2f;
  --color-cloud-white: #ffffff;
  --color-ghost-gray: #f7f8f9;
  --color-cool-stone: #ccd2d5;
  --color-slate-blue: #667782;
  --color-forest-teal: #0f866c;
  --color-dark-teal: #00695c;
  --color-warm-beige: #f0eacf;
  --color-soft-peach: #ffe4d4;
  --color-sky-mist: #b7d1d0;
  --color-light-mint: #c3ece8;
  --color-crimson-glow: #da3940;
  --color-deep-ocean-gradient: #0c3956;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-fs-kim: 'FS Kim', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.1px;
  --text-body: 14px;
  --leading-body: 1.72;
  --text-body-lg: 16px;
  --leading-body-lg: 1.83;
  --text-subheading: 18px;
  --leading-subheading: 1.67;
  --tracking-subheading: -0.016px;
  --text-heading: 24px;
  --leading-heading: 1.5;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1.25;
  --tracking-heading-lg: -0.016px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.016px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-64: 64px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-104: 104px;
  --spacing-196: 196px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 34px;
  --radius-full: 1132.2px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.12) 0px 0px 32px 0px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 0px 15px 0px;
  --shadow-md-2: rgba(0, 0, 0, 0.12) 0px 4px 16px 0px;
}
```
