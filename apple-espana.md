# Apple (España) — Style Reference
> White canvas, polished glass

**Theme:** light

Apple's AirPods Pro design system is a 'glass and light' aesthetic: a pristine white canvas, subtle gray surfaces, and compact, precise typography. Visual interest comes from bold, full-bleed product photography and occasional iridescent gradients acting as visual accents. Components adopt near-invisible borders and large, soft radii, creating a spacious, polished, and quietly confident user experience. Interactions are subtle and responsive, with a single vivid blue for primary actions.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, elevated card surfaces, main content areas |
| Light Mist | `#f5f5f7` | `--color-light-mist` | Secondary background surfaces, subtle distinctions for content blocks and badges |
| Frost Gray | `#e8e8ed` | `--color-frost-gray` | Tertiary background surfaces, subtle button backgrounds |
| Jet Black | `#1d1d1f` | `--color-jet-black` | Primary text, prominent headings, high-contrast UI elements |
| Steel Gray | `#474747` | `--color-steel-gray` | Secondary text, navigation items, less prominent body copy |
| Medium Gray | `#707070` | `--color-medium-gray` | Muted text, helper text, and subtle borders |
| Silver Whisper | `#d6d6d6` | `--color-silver-whisper` | Hairline borders and subtle dividers |
| Ocean Blue | `#0071e3` | `--color-ocean-blue` | Primary button and navigation backgrounds, active states |
| Sky Link | `#0066cc` | `--color-sky-link` | Interactive links and outlined button borders |
| Iridescent Spectra | `linear-gradient(60deg, rgb(8, 148, 255) 0%, rgb(201, 89, 221) 40%, rgb(255, 46, 84) 67%, rgb(255, 144, 3) 100%)` | `--color-iridescent-spectra` | Decorative background gradient, used for visual flair and product emphasis |
| Violet Tint | `#8668ff` | `--color-violet-tint` | Minor decorative accents or informational text elements |
| Sunset Orange | `#ed6300` | `--color-sunset-orange` | Minor decorative accents or informational text elements |
| Verdant Green | `#00c866` | `--color-verdant-green` | Minor decorative accents or informational text elements |
| Aqua Teal | `#00a1b3` | `--color-aqua-teal` | Minor decorative accents or informational text elements |

## Tokens — Typography

### SF Pro Display — Prominent headings and display text, crafted for visual impact and legibility at large scales. Its slightly wider stance and precise tracking ensure clarity even with tight kerning. · `--font-sf-pro-display`
- **Substitute:** Helvetica Neue, Arial, sans-serif
- **Weights:** 600
- **Sizes:** 19px, 21px, 24px, 28px, 32px, 56px, 72px, 80px, 96px
- **Line height:** 1.00, 1.04, 1.06, 1.07, 1.13, 1.14, 1.19, 1.21, 1.33, 1.38
- **Letter spacing:** -0.015em
- **OpenType features:** `"numr"`
- **Role:** Prominent headings and display text, crafted for visual impact and legibility at large scales. Its slightly wider stance and precise tracking ensure clarity even with tight kerning.

### SF Pro Text — Body copy, navigation, buttons, and detailed interface elements. Its multiple weights and optical sizing facilitate a clear hierarchy and comfortable reading across all functional text. · `--font-sf-pro-text`
- **Substitute:** Helvetica Neue, Arial, sans-serif
- **Weights:** 400, 600
- **Sizes:** 12px, 17px, 20px, 44px
- **Line height:** 1.00, 1.18, 1.24, 1.33, 1.47, 1.83
- **Letter spacing:** -0.010em
- **OpenType features:** `"numr"`
- **Role:** Body copy, navigation, buttons, and detailed interface elements. Its multiple weights and optical sizing facilitate a clear hierarchy and comfortable reading across all functional text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.33 | -0.37px | `--text-caption` |
| body-sm | 17px | 1.18 | -0.019px | `--text-body-sm` |
| body | 20px | 1.24 | -0.01px | `--text-body` |
| subheading | 24px | 1.07 | -0.009px | `--text-subheading` |
| heading | 32px | 1.06 | -0.005px | `--text-heading` |
| heading-lg | 56px | 1.07 | -0.015px | `--text-heading-lg` |
| display | 96px | 1.04 | -0.015px | `--text-display` |

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
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 28px |
| links | 10px |
| badges | 36px |
| images | 28px |
| buttons | 999px |

### Layout

- **Section gap:** 38px
- **Card padding:** 28px
- **Element gap:** 10px

## Components

### Ghost Button
**Role:** General action button with minimal visual presence.

Transparent background, Jet Black text SF Pro Text weight 400. Padded 0px vertical, 22px horizontal. Full pill shape with 999px border radius.

### Outline Button
**Role:** Secondary action button, often paired with primary actions.

Transparent background, text in Sky Link (#0066cc), SF Pro Text weight 400. Padded 0px. Rounded corners at 28px radius.

### Filled Primary Button
**Role:** Main call-to-action button, drawing immediate attention.

Ocean Blue (#0071e3) background, White Canvas (#ffffff) text SF Pro Text weight 600. Rounded corners at 999px radius. Explicit padding not available in data, assume 12px vertical, 24px horizontal for legibility.

### Subtle Button
**Role:** Tertiary action button with a soft, understated appearance.

Frost Gray (#e8e8ed) background, Steel Gray (#474747) text SF Pro Text weight 400. Rounded corners at 36px radius. Explicit padding not available in data, assume 12px vertical, 24px horizontal for legibility.

### Product Feature Card
**Role:** Highlights key features or product facts.

White Canvas (#ffffff) background, 28px border radius. No visible shadows or borders, relying on background contrast for separation. Internal content padding is responsive.

### Section Header
**Role:** Introduces new content sections.

Jet Black (#1d1d1f) text using SF Pro Display weight 600 at 56px, line height 1.07, letter spacing -0.015em. Often paired with a subtle 'View video' link.

### Standard Content Badge
**Role:** Small, informative labels or tags.

Light Mist background (#f5f5f7), Jet Black (#1d1d1f) text SF Pro Text weight 400. Rounded corners at 28px radius. Padding is context-dependent but typically minimal.

## Do's and Don'ts

### Do
- Prioritize SF Pro Display for headlines (56px or larger) at weight 600, using -0.015em letter-spacing to reinforce a precise, confident tone.
- Use White Canvas (#ffffff) as the default page background and for primary content cards, creating a bright, expansive feel.
- Apply 28px border radius to all cards and major imagery, and 999px (full pill) to all interactive buttons for a consistent soft, approachable aesthetic.
- Reserve Ocean Blue (#0071e3) exclusively for primary call-to-action button backgrounds, ensuring clear visual hierarchy for user actions.
- Maintain generous padding around content blocks and between sections, using a sectionGap of at least 38px and cardPadding of 28px to enhance readability and spaciousness.
- Use Light Mist (#f5f5f7) for subtle background differentiation, such as secondary content areas or feature blocks, to prevent visual monotony on lighter themes.
- Utilize Sky Link (#0066cc) for all interactive text links and bordered 'ghost' buttons, maintaining a distinct but integrated interactive visual cue.

### Don't
- Avoid arbitrary use of shadows; the system relies on subtle background shifts and strong imagery for visual depth, not drop shadows.
- Do not introduce strong chromatic colors outside of accent gradients without a clear functional purpose; color is used sparingly as punctuation.
- Do not vary font families; stick strictly to SF Pro Display for large headings and SF Pro Text for all other text, leveraging their optical properties.
- Avoid tight element spacing; maintain a minimum elementGap of 10px to ensure visual breathability and reduce cognitive load.
- Do not use generic square buttons; all buttons should feature large border radii, either 36px or 999px (pill-shaped).
- Refrain from using heavily decorative borders or outlines on cards; cards should appear as floating planes on the page.
- Do not deviate from the established type scale; maintain the precise size, line height, and letter-spacing values to preserve typographic rhythm.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | White Canvas | `#ffffff` | Base page background and primary elevated surfaces for components like modal dialogs or featured cards. |
| 1 | Light Mist | `#f5f5f7` | Secondary background surfaces for distinct content sections or information blocks, providing subtle visual separation. |
| 2 | Frost Gray | `#e8e8ed` | Tertiary background, typically for subtle interactive elements like background fills for ghost buttons or form fields. |

## Imagery

The visual language is characterized by high-key photography and abstract graphics against pristine white backgrounds. Photography is product-focused, often featuring subjects in dynamic, active poses, or close-up detail shots, with strong lighting and minimal environmental context. Abstract graphics, like the iridescent rainbow sonic waves, are used decoratively to evoke technological features. Icons are minimal, outlined, and monochromatic, maintaining a clean UI. Imagery serves a decorative atmosphere and product showcase role, often occupying large, full-bleed sections, making the pages image-heavy and visually dominant.

## Layout

The page maintains a centered, max-width layout for much of its content, although specific hero and feature sections are full-bleed. The hero pattern features a full-viewport image with a centered headline and subtext, creating immediate impact. Section rhythm is marked by consistent vertical spacing, often with subtle background shifts from `White Canvas` to `Light Mist` to delineate content blocks. Content arrangement frequently uses large, centrally aligned blocks of text and full-bleed imagery, emphasizing individual product features. Navigation is a sticky top bar with minimal elements, ensuring focus on the main content.

## Agent Prompt Guide

### Quick Color Reference
text: #1d1d1f
background: #ffffff
border: #d6d6d6
accent: #0894ff (primary hue of Iridescent Spectra gradient)
primary action: #0071e3 (filled action)

### 3-5 Example Component Prompts
1. Create a Hero section: full-bleed background featuring an image. Headline 'Los auriculares in-ear con la mejor cancelación activa de ruido del mundo.' using SF Pro Display Bold at 96px, #1d1d1f, letter-spacing -0.015em. Subtext 'Hasta el doble que los AirPods Pro 2.' using SF Pro Text Regular at 20px, #474747, letter-spacing -0.010em. Include a Filled Primary Button 'Comprar' with #0071e3 background, #ffffff text (SF Pro Text Bold), 999px radius.
2. Create a Product Feature Card: Background is White Canvas (#ffffff), 28px border-radius, with 28px padding. Headline 'Lo principal.' with SF Pro Display Bold at 56px, #1d1d1f, letter-spacing -0.015em. Beside it, a Ghost Button 'Ver el vídeo' with #1d1d1f text (SF Pro Text Regular), 999px radius.
3. Create a Subtly Marked Text Block: Use Light Mist (#f5f5f7) as background. A secondary heading 'Control de ruido inteligente' with SF Pro Text Bold at 20px, #1d1d1f, letter-spacing -0.010em. Body text 'Lo nunca oído.' with SF Pro Display Bold at 72px, #1d1d1f, letter-spacing -0.015em.

## Similar Brands

- **Samsung** — Shares a clean, product-centric approach with high-quality photography against minimalistic backgrounds, and a focus on premium digital experiences.
- **Google (Hardware Div.)** — Employs similar full-bleed product imagery, a light theme with subtle neutral surface changes, and a focus on sleek typography for their hardware showcases.
- **Bose** — Uses high-contrast product shots, a very clean and often white UI, and precise typography to convey a sense of quality and focus.
- **Dyson** — Known for showcasing sleek products with strong photography and clear, concise messaging on light backgrounds, with subtle interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-light-mist: #f5f5f7;
  --color-frost-gray: #e8e8ed;
  --color-jet-black: #1d1d1f;
  --color-steel-gray: #474747;
  --color-medium-gray: #707070;
  --color-silver-whisper: #d6d6d6;
  --color-ocean-blue: #0071e3;
  --color-sky-link: #0066cc;
  --color-iridescent-spectra: #0894ff;
  --gradient-iridescent-spectra: linear-gradient(60deg, rgb(8, 148, 255) 0%, rgb(201, 89, 221) 40%, rgb(255, 46, 84) 67%, rgb(255, 144, 3) 100%);
  --color-violet-tint: #8668ff;
  --color-sunset-orange: #ed6300;
  --color-verdant-green: #00c866;
  --color-aqua-teal: #00a1b3;

  /* Typography — Font Families */
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: -0.37px;
  --text-body-sm: 17px;
  --leading-body-sm: 1.18;
  --tracking-body-sm: -0.019px;
  --text-body: 20px;
  --leading-body: 1.24;
  --tracking-body: -0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1.07;
  --tracking-subheading: -0.009px;
  --text-heading: 32px;
  --leading-heading: 1.06;
  --tracking-heading: -0.005px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: -0.015px;
  --text-display: 96px;
  --leading-display: 1.04;
  --tracking-display: -0.015px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;

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
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 38px;
  --card-padding: 28px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 18px;
  --radius-3xl: 25px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 36px;
  --radius-full: 980px;
  --radius-full-2: 999px;

  /* Named Radii */
  --radius-cards: 28px;
  --radius-links: 10px;
  --radius-badges: 36px;
  --radius-images: 28px;
  --radius-buttons: 999px;

  /* Surfaces */
  --surface-white-canvas: #ffffff;
  --surface-light-mist: #f5f5f7;
  --surface-frost-gray: #e8e8ed;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-light-mist: #f5f5f7;
  --color-frost-gray: #e8e8ed;
  --color-jet-black: #1d1d1f;
  --color-steel-gray: #474747;
  --color-medium-gray: #707070;
  --color-silver-whisper: #d6d6d6;
  --color-ocean-blue: #0071e3;
  --color-sky-link: #0066cc;
  --color-iridescent-spectra: #0894ff;
  --color-violet-tint: #8668ff;
  --color-sunset-orange: #ed6300;
  --color-verdant-green: #00c866;
  --color-aqua-teal: #00a1b3;

  /* Typography */
  --font-sf-pro-display: 'SF Pro Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sf-pro-text: 'SF Pro Text', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.33;
  --tracking-caption: -0.37px;
  --text-body-sm: 17px;
  --leading-body-sm: 1.18;
  --tracking-body-sm: -0.019px;
  --text-body: 20px;
  --leading-body: 1.24;
  --tracking-body: -0.01px;
  --text-subheading: 24px;
  --leading-subheading: 1.07;
  --tracking-subheading: -0.009px;
  --text-heading: 32px;
  --leading-heading: 1.06;
  --tracking-heading: -0.005px;
  --text-heading-lg: 56px;
  --leading-heading-lg: 1.07;
  --tracking-heading-lg: -0.015px;
  --text-display: 96px;
  --leading-display: 1.04;
  --tracking-display: -0.015px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 18px;
  --radius-3xl: 25px;
  --radius-3xl-2: 28px;
  --radius-3xl-3: 32px;
  --radius-3xl-4: 36px;
  --radius-full: 980px;
  --radius-full-2: 999px;
}
```
