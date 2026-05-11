# Pitch — Style Reference
> Vibrant Violet Gradient Canvas

**Theme:** light

Pitch embodies an 'energetic professional' mood, achieved through a vibrant violet spectrum contrasted with clean whites and subtle grays. The hero section bursts with rich gradients, while content sections maintain clarity with ample negative space. A blend of sharp geometric forms and soft, rounded elements creates a dynamic yet approachable feel, balancing technical precision with modern friendliness. Custom typography provides distinct voices for headlines and body text, contributing to an overall sense of refined dynamism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Pitch Violet | `#8d49f7` | `--color-pitch-violet` | Primary brand color, used for active links, icons, and significant accents. It provides visual energy and indicates interactivity. |
| Deep Violet | `#6b53ff` | `--color-deep-violet` | Secondary brand color, appearing in badges, card elements, and as a strong accent. It provides depth to the violet palette. |
| Midnight Graphite | `#1e1d28` | `--color-midnight-graphite` | Darkest text and card backgrounds, providing high contrast against light surfaces. Used where information density or visual weight is desired. |
| Action Yellow | `#ffd02c` | `--color-action-yellow` | Accentuating specific card backgrounds or illustrative elements that require high visibility, often paired with gradients. |
| Faded Shadow | `#b5b3cd` | `--color-faded-shadow` | Used for subtle card shadows, providing a soft lift without harshness. |
| Medium Gray | `#3f4250` | `--color-medium-gray` | Mid-tone text and borders, offering a slightly softer alternative to Midnight Graphite for less prominent text. |
| Button Gray | `#6f7387` | `--color-button-gray` | Default text color for secondary buttons, balancing visibility with a muted appearance. |
| Bright Violet | `#586ee0` | `--color-bright-violet` | Used for illustrative fills and minor accent details within graphics, adding vibrancy. |
| Dark Violet Text | `#371789` | `--color-dark-violet-text` | Specific text instances on lighter backgrounds, providing a contrasting, rich violet tone. |
| Sunset Orange | `#ffa000` | `--color-sunset-orange` | Used in fills and as a background accent in some graphic elements, pairing with Action Yellow to create a warm highlight. |
| Sky Blue | `#81d4fa` | `--color-sky-blue` | Specific graphic fills and background accents, contributing to a broader vibrant palette. |
| Rich Dark | `#2b2a35` | `--color-rich-dark` | Dominant text color for headings and body copy across most light backgrounds, providing strong legibility. |
| Pure White | `#ffffff` | `--color-pure-white` | Canvas background, text on dark elements, and primary button backgrounds. |
| Canvas Faint | `#f0eff4` | `--color-canvas-faint` | Subtle background for main page canvas and sections, providing a near-white base without being stark. |
| Border Light Gray | `#dddfe5` | `--color-border-light-gray` | Default border color for inputs and subtle dividers, creating clear separation without being heavy. |
| Mid-tone Border | `#cfcfd0` | `--color-mid-tone-border` | Slightly darker border choice for elements requiring more definition, like some button states. |
| Coal Black | `#000000` | `--color-coal-black` | Used for some link text and specific icons, offering an alternative to Rich Dark where maximum contrast is required. |
| Faint Shadow Gray | `#95959a` | `--color-faint-shadow-gray` | Used for subtle button shadows, providing depth without visual weight. |
| Hero Gradient Purple | `linear-gradient(90deg, rgb(83, 24, 235), rgb(171, 110, 249))` | `--color-hero-gradient-purple` | Primary gradient for hero sections and prominent background elements, creating a dynamic and immersive brand experience. Dominant color is #5318eb from `rgb(83, 24, 235)`. |
| Light Gradient Overlay | `linear-gradient(90deg, rgb(228, 207, 255), rgb(255, 255, 255))` | `--color-light-gradient-overlay` | Subtle background gradient for internal sections, adding a soft, branded layer. Dominant color is #e4cfff from `rgb(228, 207, 255)`. |
| Dark Gradient Accent | `linear-gradient(45deg, rgb(43, 42, 53), rgb(138, 76, 249) 120%)` | `--color-dark-gradient-accent` | Used for internal graphic accents and backgrounds, providing a dark-to-violet transition. Dominant color is #2b2a35 from `rgb(43, 42, 53)`. |
| Warm Gradient Highlight | `linear-gradient(90deg, rgb(255, 208, 44), rgb(255, 158, 44))` | `--color-warm-gradient-highlight` | Used for specific illustrative elements, creating a warm and inviting highlight effect. Dominant color is #ffd02c from `rgb(255, 208, 44)`. |

## Tokens — Typography

### Eina01 — Primary UI and body text font. Its regular weights (400, 600) ensure readability for extensive copy, while its extended size range supports diverse UI elements from caption to sub-heading. Used for links, icons, buttons, and general informational text. · `--font-eina01`
- **Substitute:** Inter
- **Weights:** 400, 600, 700, 800
- **Sizes:** 13px, 14px, 15px, 16px, 18px, 22px, 24px, 28px
- **Line height:** 1.00, 1.10, 1.20, 1.30, 1.40, 1.60, 1.69, 2.00, 2.25
- **Letter spacing:** 0.1000em
- **Role:** Primary UI and body text font. Its regular weights (400, 600) ensure readability for extensive copy, while its extended size range supports diverse UI elements from caption to sub-heading. Used for links, icons, buttons, and general informational text.

### Mark Pro — Distinctive display font for headings and prominent card titles. Its heavier weights (700, 800) and tighter letter-spacing create a bold, modern statement without being aggressive, contributing significantly to brand identity. Used across major headings and highlighted content. · `--font-mark-pro`
- **Substitute:** Montserrat
- **Weights:** 700, 800
- **Sizes:** 13px, 27px, 28px, 42px, 60px, 80px
- **Line height:** 1.00, 1.10, 1.30, 1.40, 1.85
- **Letter spacing:** -0.0200em
- **Role:** Distinctive display font for headings and prominent card titles. Its heavier weights (700, 800) and tighter letter-spacing create a bold, modern statement without being aggressive, contributing significantly to brand identity. Used across major headings and highlighted content.

### Arial — System fallback for specific button text, ensuring accessibility if custom fonts are unavailable. Used sparingly. · `--font-arial`
- **Substitute:** sans-serif
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** System fallback for specific button text, ensuring accessibility if custom fonts are unavailable. Used sparingly.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 13px | 1.2 | 0.1px | `--text-caption` |
| body | 16px | 1.6 | 0.1px | `--text-body` |
| subheading | 22px | 1.4 | 0.1px | `--text-subheading` |
| heading-sm | 27px | 1.3 | -0.02px | `--text-heading-sm` |
| heading | 42px | 1.1 | -0.02px | `--text-heading` |
| display | 80px | 1 | -0.02px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 120 | 120px | `--spacing-120` |
| 159 | 159px | `--spacing-159` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 26px |
| large | 56px |
| small | 3px |
| badges | 20px |
| buttons | 20px |
| default | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.15) 0px 3px 10px 0px` | `--shadow-md` |
| xl | `rgba(103, 110, 144, 0.2) 0px 8px 26px 0px` | `--shadow-xl` |
| xl-2 | `rgba(43, 42, 53, 0.25) 0px 6px 27px 0px` | `--shadow-xl-2` |
| xl-3 | `rgba(43, 42, 53, 0.5) 0px 6px 27px 0px` | `--shadow-xl-3` |
| xl-4 | `rgba(10, 3, 89, 0.3) 0px 20px 90px 0px, rgba(0, 0, 0, 0.0...` | `--shadow-xl-4` |

### Layout

- **Section gap:** 40px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Button
**Role:** Action

Filled button with Pure White background and Deep Violet text. Uses 20px border-radius, with 20px padding. Text is Eina01 400.

### Ghost Button
**Role:** Action

Transparent button with Button Gray text and border, no border-radius defined (inherits 0px). Uses 16px vertical and 20px horizontal padding. Text is Eina01 400.

### Inline Text Button
**Role:** Navigation/Action

Small, transparent button for inline interactions. Text is Pure White at 60% opacity with a matching border. No padding or border-radius.

### Navigation Button
**Role:** Navigation

White background button with Deep Violet text for primary navigation calls to action. Uses 20px border-radius, with 20px padding. Features a subtle Light Gray border (#dddfe5).

### Feature Card
**Role:** Display

Standard content card with Pure White background, a subtle shadow of rgba(103, 110, 144, 0.2) 0px 8px 26px 0px, and 26px border-radius. Internal padding is 20px. Content elements within are spaced by 20px.

### Badge Default
**Role:** Information

Transparent background badge with Midnight Graphite text, no border-radius. Displays concise information. Padding is 0px.

### Violet Tag Badge
**Role:** Information/Categorization

Light Deep Violet background (rgba(107, 83, 255, 0.05)) with Deep Violet text. Has a 20px border-radius and 4px vertical, 12px horizontal padding. Text is Eina01 400.

### Hero Headline
**Role:** Display

Large, eye-catching text using Mark Pro 800 with Riverbank Violet color, sizes from 42px to 80px and letter-spacing -0.0200em.

### Input Field
**Role:** Form Element

Implicitly Pure White background with the default Border Light Gray (#dddfe5) border ensuring clear definition against the canvas.

### Rounded Icon Button
**Role:** Action

Small, Pure White circular button with 50% border-radius for icons. Minimal 1px padding for internal spacing.

## Do's and Don'ts

### Do
- Prioritize Deep Violet (#6b53ff) for all primary interactive elements and brand accents.
- Use Eina01 for all body text, UI labels, and secondary information, maintaining consistency at weights 400-600.
- Apply Mark Pro 700 or 800 for all headlines and subheadings to maintain the brand's bold typographic voice.
- Utilize 26px border-radius for all primary display cards, and 20px for buttons and badges to enforce soft geometry.
- Implement Canvas Faint (#f0eff4) as the default page background to provide a consistent light theme base.
- Space elements with a default 20px elementGap, and content cards with 20px internal padding for comfortable density.
- Apply the Hero Gradient Purple to full-width hero sections to create visual impact and reinforce brand identity.

### Don't
- Avoid using raw black (#000000) for body text; use Rich Dark (#2b2a35) or Midnight Graphite (#1e1d28) for softer contrast.
- Do not introduce new border-radius values beyond 3px, 6px, 10px, 16px, 20px, 26px, 56px to preserve shape consistency.
- Avoid using highly saturated colors for large text blocks; reserve them for accents and interactive elements.
- Do not deviate from Eina01 and Mark Pro font families; avoid using system default fonts unless for accessibility fallbacks.
- Refrain from adding arbitrary shadows; restrict shadow usage to the specified values and contexts for deliberate depth.
- Avoid tight spacing; maintain comfort and legibility by adhering to 20px element gaps and section separations.
- Do not use multiple accent colors simultaneously in proximity; allow Pitch Violet and specific accents (like Action Yellow) to stand out.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Faint | `#f0eff4` | Base page background, light and airy foundation. |
| 1 | Pure White | `#ffffff` | Primary content surfaces like cards, modal backgrounds, providing high contrast. |
| 2 | Midnight Graphite | `#1e1d28` | Elevated card backgrounds, dark sections, creating prominent content blocks. |
| 3 | Action Yellow | `#ffd02c` | Highlighting specific cards or illustrative elements, indicating special content. |

## Elevation

- **Card:** `rgba(10, 3, 89, 0.3) 0px 20px 90px 0px, rgba(0, 0, 0, 0.02) 0px 0px 0px 1px`
- **Default Shadow:** `rgba(0, 0, 0, 0.15) 0px 3px 10px 0px`
- **Feature Card:** `rgba(103, 110, 144, 0.2) 0px 8px 26px 0px`
- **Button (Dark):** `rgba(43, 42, 53, 0.25) 0px 6px 27px 0px`
- **Button (Dark Pressed):** `rgba(43, 42, 53, 0.5) 0px 6px 27px 0px`

## Imagery

The visual language primarily uses abstract 3D renders with soft, organic shapes and occasional product screenshots. The 3D elements, often in shades of violet and gray, are used decoratively to add a sense of depth and modernity, frequently appearing as background accents or overlapping UI elements. Product screenshots are contained within UI frameworks, highlighting features, and are treated with sharp edges, contrasting the softer 3D elements. Icons are filled, predominantly in Pitch Violet or white, with a consistent, moderate stroke weight, serving an explanatory and navigational role. The overall density is balanced, allowing imagery to complement text without overwhelming it.

## Layout

The page uses a maximum content width centered model, subtly implied by generous side padding on most sections. The hero section is a full-bleed, vibrant gradient background with centered, prominent headline and call-to-action. Content sections alternate between the Canvas Faint background and occasional gradient overlays. There's a consistent vertical rhythm created by explicit section gaps. Content is arranged using a mix of centered stacks for headlines and subtext, and alternating text-left/image-right or text-right/image-left for feature sections. A clear grid structure appears for displaying cards and badges, often in 3-column layouts where applicable. The layout prioritizes spaciousness, using ample negative space around content blocks. Navigation is a sticky top bar with a left-aligned logo and right-aligned actions (login, sign up).

## Agent Prompt Guide

### Quick Color Reference
- **Text Primary:** #2b2a35 (Rich Dark)
- **Background:** #f0eff4 (Canvas Faint)
- **CTA Background:** #6b53ff (Deep Violet)
- **CTA Text:** #ffffff (Pure White)
- **Border Default:** #dddfe5 (Border Light Gray)
- **Accent:** #8d49f7 (Pitch Violet)

### Example Component Prompts
1. **Create a Hero Section:** Use `Hero Gradient Purple` as the background. Centered headline 'Don’t just present. Pitch.' using `Mark Pro` 800 at 80px, color `Pure White`. Below it, a subtext at `Eina01` 18px 400, color `Pure White`. Include two buttons: a 'Sign up for free' `Primary Button`, and a 'Get a demo' `Ghost Button` with `Pure White` text and `Pure White` border.
2. **Generate a Feature Card:** Use `Pure White` background with `26px` border-radius and the `Feature Card` shadow. Apply `20px` internal padding. Inside, place a headline 'Powerful Integrations' using `Mark Pro` 700 at 27px, color `Midnight Graphite`, and a paragraph of body text using `Eina01` 16px 400, color `Midnight Graphite`.
3. **Design a Navigation Bar Button:** Create a `Navigation Button` with 'Sign up' as its label. This button has a `Pure White` background with `Deep Violet` text, `20px` border-radius. Position it within a sticky header on `Canvas Faint` background.
4. **Create a Tag Badge:** Use the `Violet Tag Badge` for a categorical label 'New Feature'. It should have a background of `rgba(107, 83, 255, 0.05)`, `Deep Violet` text (`#6b53ff`), `20px` border-radius, and `4px` vertical, `12px` horizontal padding.

## Similar Brands

- **Figma** — Similar use of vibrant, inviting gradients and a clean, modern UI for a creative/productivity tool.
- **Linear** — Shared aesthetic of structured, clean interface design with deliberate use of colored accents on a mostly neutral canvas.
- **Notion** — Comparable emphasis on clear, functional layouts, often using white cards on a light background, with minimalist-yet-engaging branding.
- **Canva** — Similar focus on vivid, engaging brand colors and accessible, polished UI for creative content creation.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-pitch-violet: #8d49f7;
  --color-deep-violet: #6b53ff;
  --color-midnight-graphite: #1e1d28;
  --color-action-yellow: #ffd02c;
  --color-faded-shadow: #b5b3cd;
  --color-medium-gray: #3f4250;
  --color-button-gray: #6f7387;
  --color-bright-violet: #586ee0;
  --color-dark-violet-text: #371789;
  --color-sunset-orange: #ffa000;
  --color-sky-blue: #81d4fa;
  --color-rich-dark: #2b2a35;
  --color-pure-white: #ffffff;
  --color-canvas-faint: #f0eff4;
  --color-border-light-gray: #dddfe5;
  --color-mid-tone-border: #cfcfd0;
  --color-coal-black: #000000;
  --color-faint-shadow-gray: #95959a;
  --color-hero-gradient-purple: #5318eb;
  --gradient-hero-gradient-purple: linear-gradient(90deg, rgb(83, 24, 235), rgb(171, 110, 249));
  --color-light-gradient-overlay: #e4cfff;
  --gradient-light-gradient-overlay: linear-gradient(90deg, rgb(228, 207, 255), rgb(255, 255, 255));
  --color-dark-gradient-accent: #2b2a35;
  --gradient-dark-gradient-accent: linear-gradient(45deg, rgb(43, 42, 53), rgb(138, 76, 249) 120%);
  --color-warm-gradient-highlight: #ffd02c;
  --gradient-warm-gradient-highlight: linear-gradient(90deg, rgb(255, 208, 44), rgb(255, 158, 44));

  /* Typography — Font Families */
  --font-eina01: 'Eina01', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mark-pro: 'Mark Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.2;
  --tracking-caption: 0.1px;
  --text-body: 16px;
  --leading-body: 1.6;
  --tracking-body: 0.1px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.1px;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.02px;
  --text-heading: 42px;
  --leading-heading: 1.1;
  --tracking-heading: -0.02px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-120: 120px;
  --spacing-159: 159px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 26px;
  --radius-full: 56px;

  /* Named Radii */
  --radius-cards: 26px;
  --radius-large: 56px;
  --radius-small: 3px;
  --radius-badges: 20px;
  --radius-buttons: 20px;
  --radius-default: 6px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 3px 10px 0px;
  --shadow-xl: rgba(103, 110, 144, 0.2) 0px 8px 26px 0px;
  --shadow-xl-2: rgba(43, 42, 53, 0.25) 0px 6px 27px 0px;
  --shadow-xl-3: rgba(43, 42, 53, 0.5) 0px 6px 27px 0px;
  --shadow-xl-4: rgba(10, 3, 89, 0.3) 0px 20px 90px 0px, rgba(0, 0, 0, 0.02) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-canvas-faint: #f0eff4;
  --surface-pure-white: #ffffff;
  --surface-midnight-graphite: #1e1d28;
  --surface-action-yellow: #ffd02c;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-pitch-violet: #8d49f7;
  --color-deep-violet: #6b53ff;
  --color-midnight-graphite: #1e1d28;
  --color-action-yellow: #ffd02c;
  --color-faded-shadow: #b5b3cd;
  --color-medium-gray: #3f4250;
  --color-button-gray: #6f7387;
  --color-bright-violet: #586ee0;
  --color-dark-violet-text: #371789;
  --color-sunset-orange: #ffa000;
  --color-sky-blue: #81d4fa;
  --color-rich-dark: #2b2a35;
  --color-pure-white: #ffffff;
  --color-canvas-faint: #f0eff4;
  --color-border-light-gray: #dddfe5;
  --color-mid-tone-border: #cfcfd0;
  --color-coal-black: #000000;
  --color-faint-shadow-gray: #95959a;
  --color-hero-gradient-purple: #5318eb;
  --color-light-gradient-overlay: #e4cfff;
  --color-dark-gradient-accent: #2b2a35;
  --color-warm-gradient-highlight: #ffd02c;

  /* Typography */
  --font-eina01: 'Eina01', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-mark-pro: 'Mark Pro', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 13px;
  --leading-caption: 1.2;
  --tracking-caption: 0.1px;
  --text-body: 16px;
  --leading-body: 1.6;
  --tracking-body: 0.1px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.1px;
  --text-heading-sm: 27px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.02px;
  --text-heading: 42px;
  --leading-heading: 1.1;
  --tracking-heading: -0.02px;
  --text-display: 80px;
  --leading-display: 1;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-120: 120px;
  --spacing-159: 159px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 26px;
  --radius-full: 56px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.15) 0px 3px 10px 0px;
  --shadow-xl: rgba(103, 110, 144, 0.2) 0px 8px 26px 0px;
  --shadow-xl-2: rgba(43, 42, 53, 0.25) 0px 6px 27px 0px;
  --shadow-xl-3: rgba(43, 42, 53, 0.5) 0px 6px 27px 0px;
  --shadow-xl-4: rgba(10, 3, 89, 0.3) 0px 20px 90px 0px, rgba(0, 0, 0, 0.02) 0px 0px 0px 1px;
}
```
