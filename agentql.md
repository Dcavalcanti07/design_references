# AgentQL — Style Reference
> Deep space console: layered dark surfaces, focused luminosity.

**Theme:** dark

AgentQL employs a 'nebula console' aesthetic: deep, near-black backgrounds accented by vibrant, contained violet and blue glows. Content is presented on layered, softly lit cards with subtle depth, creating an immersive yet highly functional interface. Typography is primarily monochrome and robust, punctuated by a single clear blue for interactive elements and brand accents. The overall impression is one of sophisticated, focused productivity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Gaze | `#0e111b` | `--color-midnight-gaze` | Primary background and base surface for cards and lists |
| Astral Deep | `#0d172b` | `--color-astral-deep` | Secondary background, often for action elements like buttons and deeper sections |
| Nebula Black | `#050606` | `--color-nebula-black` | Deepest shadow tint for subtle elevation and text effects |
| Crystal White | `#ffffff` | `--color-crystal-white` | Primary text, icons, and significant borders. Provides strong contrast against dark backgrounds |
| Lunar Dust | `#abaebb` | `--color-lunar-dust` | Secondary text, muted borders, and subtle navigation elements |
| Ash Outline | `#777a88` | `--color-ash-outline` | Outlined button borders and secondary interactive text |
| Comet Grey | `#c7c9d1` | `--color-comet-grey` | Subtle borders and minor text details |
| Twilight Indigo | `#12244f` | `--color-twilight-indigo` | Card backgrounds, providing a cooler, richer dark hue than the canvas |
| Cosmic Violet | `#1b346e` | `--color-cosmic-violet` | Card backgrounds, a slightly more saturated variant of Twilight Indigo |
| Starlight Violet | `#85a6e9` | `--color-starlight-violet` | Highlight card backgrounds, a luminous violet for emphasis |
| Etherium Blue | `#28b6ff` | `--color-etherium-blue` | Accent for code syntax, and decorative elements. Signifies active areas or syntax |
| Deep Space Glow | `radial-gradient(79.43% 95.88% at 38.94% -53.46%, rgba(98, 95, 255, 0.38) 0px, rgba(0, 0, 0, 0))` | `--color-deep-space-glow` | Subtle background glow or gradient start for prominent sections; Vivid brand accent for background effects. Dominant color: #625FFF |
| Pink Nova | `radial-gradient(27.99% 22.08% at 72.13% 103.46%, rgba(255, 125, 218, 0.33) 0px, rgba(0, 0, 0, 0))` | `--color-pink-nova` | Secondary brand accent for background effects. Dominant color: #FF7DDA |
| Frosty Glare | `linear-gradient(rgb(209, 211, 255) 35%, rgba(153, 157, 255, 0.1))` | `--color-frosty-glare` | Subtle background pattern or overlay, appearing as a soft, cool gradient from luminous white |

## Tokens — Typography

### Figtree — Used for prominent page headlines and key visual text. The wider tracking, compared to typical display fonts, gives it an open, modern feel, enhancing its presence against the dark backgrounds. · `--font-figtree`
- **Substitute:** Montserrat
- **Weights:** 500, 600
- **Sizes:** 32px, 36px, 44px, 48px, 64px
- **Line height:** 1.00, 1.13
- **Letter spacing:** -0.0200em
- **Role:** Used for prominent page headlines and key visual text. The wider tracking, compared to typical display fonts, gives it an open, modern feel, enhancing its presence against the dark backgrounds.

### Inter — Versatile all-purpose typeface for body text, navigation, buttons, and most UI elements. Its strong legibility at small sizes and varied weights support a dense information display. Negative letter-spacing in larger sizes helps maintain a compact, controlled appearance. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 300, 400, 500, 600
- **Sizes:** 9px, 12px, 13px, 14px, 15px, 16px, 18px, 20px, 28px, 40px
- **Line height:** 1.00, 1.13, 1.25, 1.38, 1.50
- **Letter spacing:** -0.0400em, -0.0270em, -0.0230em, -0.0200em, 0.0200em
- **Role:** Versatile all-purpose typeface for body text, navigation, buttons, and most UI elements. Its strong legibility at small sizes and varied weights support a dense information display. Negative letter-spacing in larger sizes helps maintain a compact, controlled appearance.

### IBM Plex Mono — Dedicated to code blocks and technical snippets. Its monospace nature clearly differentiates code from regular content, providing a predictable character width essential for readability in programming contexts. · `--font-ibm-plex-mono`
- **Substitute:** JetBrains Mono
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.00, 1.25, 1.50
- **Letter spacing:** normal
- **Role:** Dedicated to code blocks and technical snippets. Its monospace nature clearly differentiates code from regular content, providing a predictable character width essential for readability in programming contexts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| heading-sm | 20px | 1.25 | -0.027px | `--text-heading-sm` |
| heading | 28px | 1.25 | -0.023px | `--text-heading` |
| heading-lg | 40px | 1.13 | -0.02px | `--text-heading-lg` |
| display | 64px | 1 | -0.02px | `--text-display` |

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
| 36 | 36px | `--spacing-36` |
| 40 | 40px | `--spacing-40` |
| 64 | 64px | `--spacing-64` |
| 76 | 76px | `--spacing-76` |
| 80 | 80px | `--spacing-80` |
| 104 | 104px | `--spacing-104` |
| 160 | 160px | `--spacing-160` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 12px |
| badges | 9999px |
| inputs | 8px |
| modals | 12px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.2) 0px 3px 16px 0px` | `--shadow-md` |
| xl | `rgba(0, 0, 0, 0.5) 0px 4px 30px 0px` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.34) 0px 20px 35px 0px, rgba(0, 0, 0, 0.25...` | `--shadow-xl-2` |
| md-2 | `rgba(255, 255, 255, 0.35) 0px 2px 14px 0px` | `--shadow-md-2` |
| xl-3 | `rgba(0, 0, 0, 0.35) 0px 20px 34px 0px` | `--shadow-xl-3` |
| subtle | `rgba(0, 0, 0, 0.15) 0px 0px 0px 1px` | `--shadow-subtle` |

### Layout

- **Page max-width:** 1408px
- **Section gap:** 104px
- **Card padding:** 16px
- **Element gap:** 4px

## Components

### Primary Ghost Button
**Role:** Main action button for driving user engagement, appearing as an outlined element against dark backgrounds.

backgroundColor: rgba(0, 0, 0, 0), color: #abaebb (Lunar Dust), borderColor: #abaebb (Lunar Dust), borderRadius: 9999px, paddingTop: 8px, paddingRight: 12px, paddingBottom: 8px, paddingLeft: 12px. Text uses Inter weight 400.

### Filled Secondary Button
**Role:** Secondary calls to action or interactive toggles.

backgroundColor: #0d172b (Astral Deep), text color: #8798c1, border: 1px solid #172540. borderRadius: 4px. Text uses Inter weight 400, no padding on button component, implied from content.

### Integration Grid Card
**Role:** Displaying individual integration partners, with varied background colors to add visual interest to groupings.

backgroundColor: unique violet hues (#85a6e9, #1b346, #12244f), borderRadius: 9999px, boxShadow: none, padding: 0. Content centered within.

### Elevated Content Card
**Role:** Standard container for content blocks, features, or pricing tiers, providing an elevated surface.

backgroundColor: #0e111b (Midnight Gaze), borderRadius: 12px, boxShadow: rgba(0, 0, 0, 0.5) 0px 4px 30px 0px, paddingTop: 24px, paddingRight: 24px, paddingBottom: 24px, paddingLeft: 24px. Text uses Inter, headings use Figtree.

### Product Hunt Badge
**Role:** Prominent display of achievements or endorsements.

Container is a small card with backgroundColor: #0d172b (Astral Deep), text color: #abaebb (Lunar Dust). Text uses Inter, typically small sizes like 12px-14px. Border varies, sometimes 1px solid #172540.

### Nav Link Pill
**Role:** Interactive navigation items or categories, with a distinct pill shape.

backgroundColor: rgba(0, 0, 0, 0), color: #abaebb (Lunar Dust), borderColor: #abaebb (Lunar Dust) 1px solid, borderRadius: 9999px, paddingTop: 8px, paddingRight: 12px, paddingBottom: 8px, paddingLeft: 12px. Text uses Inter weight 400.

## Do's and Don'ts

### Do
- Always use Figtree for primary headings to maintain the distinct visual voice of the brand, applying -0.0200em letter-spacing.
- Layer content on dark, slightly divergent background hues: #0e111b (Midnight Gaze) for base, #0d172b (Astral Deep) for secondary sections, and #12244f (Twilight Indigo) for prominent cards.
- Utilize #ffffff (Crystal White) for primary text and critical UI elements to ensure high contrast against the dark theme.
- Apply a generous border-radius of 9999px for all buttons and badge-like elements to create a friendly, approachable feel.
- Employ subtle shadow effects, like rgba(0, 0, 0, 0.5) 0px 4px 30px 0px for cards, to introduce realistic depth without heavy elements.
- Reserve the vivid #28b6ff (Etherium Blue) accent color exclusively for code syntax, subtle interactive highlights, or decorative flourishes, not for primary actions.

### Don't
- Avoid using bright uncontained colors for large areas; the palette relies on deep tones and focused accents.
- Do not deviate from the specified font families; their negative letter-spacing and specific weights are key to the brand's typographic identity.
- Never introduce hard, sharp corners; all UI elements should have at least an 8px border-radius, with 12px for cards and 9999px for buttons/badges being standard.
- Do not use generic, default box-shadows; all elevation should use the brand's blue-tinted or dark-toned shadow tokens for consistency.
- Avoid large hero imagery that distracts from the UI; prefer abstract, muted graphics or product shots contained within cards.
- Do not clutter layouts; maintain a comfortable density with ample horizontal and vertical padding around elements and sections, adhering to the 4px base unit.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Page Canvas | `#0b0c0` | The deepest, foundational background of the entire page. |
| 1 | Base Surface | `#0e111b` | Primary background for main content areas and standard cards. |
| 2 | Elevated Surface | `#0d172b` | Used for sections with slightly more prominence or interactive components. |
| 3 | Accent Card Surface | `#12244f` | Distinct card background, often for highlighted features or integrations. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.5) 0px 4px 30px 0px`
- **Hero Image/Content:** `rgba(0, 0, 0, 0.34) 0px 20px 35px 0px, rgba(0, 0, 0, 0.25) 0px 4px 13px 0px`
- **Link Hover:** `rgba(0, 0, 0, 0.2) 0px 3px 16px 0px`

## Imagery

The visual language for imagery is abstract and atmospheric, focusing on glowing, blurred light effects rather than literal photography or detailed illustrations. Product screenshots are contained within dark, code-like interface mockups with blue-tinged borders, often floating with subtle elevation and background radial gradients (Neon Burst, Pink Nova). Icons are typically white or Lunar Dust, with a filled style and a thin stroke, emphasizing clarity against the dark canvas. The overall impression is one of UI-centric visuals, with 'imagery' serving to create a futuristic, tech-forward ambiance around the product interfaces.

## Layout

The page uses a contained layout with a maximum width of 1408px, centered on the screen. The hero section is full-bleed, featuring a dark background with prominent centered headlines and product mockups floating within atmospheric gradients. Sections maintain a consistent vertical rhythm with a `sectionGap` of 104px, creating ample breathing room. Content arrangement frequently uses a dual-column layout, often with text on one side and a visual (card, image, or mock-up) on the other. Navigation is a sticky top bar with links and a subtle ghost button for primary actions. A 3-column grid is evident for pricing plans and feature lists, and card elements are a primary container.

## Agent Prompt Guide

Quick Color Reference:
- text: #ffffff (Crystal White)
- background: #0e111b (Midnight Gaze)
- border: #172540 (Violet Edge)
- accent: #28b6ff (Etherium Blue)
- primary action: #0d172b (filled action)

Example Component Prompts:
- Create a Hero Headline: 'Make the web AI-Ready' using Figtree weight 600, size 64px, color #ffffff, letter-spacing -0.02em, centered on a #0b0c0e background with a surrounding pink nova gradient.
- Design a Product Hunt Badge: Text 'Product Hunt #1 Product of the Day' as caption, Inter weight 400, size 12px, color #abaebb, on a #0d172b background, with borderRadius 9999px.
- Build an Integration Card: A 9999px borderRadius card, 200x200px, with background #85a6e9, containing a centered abstract icon in #ffffff, and no padding. Apply box-shadow rgba(0,0,0,0.5) 0px 4px 30px 0px.
- Render a Ghost Navigation Button: Label 'Docs', Inter weight 400, size 16px, color #abaebb, with a 1px solid #abaebb border, and 9999px border-radius, 8px vertical padding, 12px horizontal padding.
- Construct an Elevated Content Card: Background #0e111b, borderRadius 12px, padding 24px on all sides, with box-shadow rgba(0,0,0,0.5) 0px 4px 30px 0px. Title 'Plays well with others' (Figtree 40px, #ffffff) and body text (Inter 16px, #abaebb).

## Similar Brands

- **Vercel** — Dark-mode UI, focus on code/developer experience, and high-contrast text on deep backgrounds with subtle gradients.
- **Linear** — Minimalist dark theme, sharp typography, and focus on functional, almost monochromatic UI with small, focused color accents.
- **Stripe (dark mode)** — Sophisticated use of dark surfaces, layered cards with subtle shadows, and a restrained color palette for interactive elements.
- **Midjourney** — Deep, immersive dark theme with subtle lighting effects and a focus on abstract, atmospheric visuals around a central product experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-gaze: #0e111b;
  --color-astral-deep: #0d172b;
  --color-nebula-black: #050606;
  --color-crystal-white: #ffffff;
  --color-lunar-dust: #abaebb;
  --color-ash-outline: #777a88;
  --color-comet-grey: #c7c9d1;
  --color-twilight-indigo: #12244f;
  --color-cosmic-violet: #1b346e;
  --color-starlight-violet: #85a6e9;
  --color-etherium-blue: #28b6ff;
  --color-deep-space-glow: #2862d7;
  --gradient-deep-space-glow: radial-gradient(79.43% 95.88% at 38.94% -53.46%, rgba(98, 95, 255, 0.38) 0px, rgba(0, 0, 0, 0));
  --color-pink-nova: #FF7DDA;
  --gradient-pink-nova: radial-gradient(27.99% 22.08% at 72.13% 103.46%, rgba(255, 125, 218, 0.33) 0px, rgba(0, 0, 0, 0));
  --color-frosty-glare: #D1D3FF;
  --gradient-frosty-glare: linear-gradient(rgb(209, 211, 255) 35%, rgba(153, 157, 255, 0.1));

  /* Typography — Font Families */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.027px;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.023px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.02px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.02px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
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
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-160: 160px;
  --spacing-192: 192px;

  /* Layout */
  --page-max-width: 1408px;
  --section-gap: 104px;
  --card-padding: 16px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 12px;
  --radius-badges: 9999px;
  --radius-inputs: 8px;
  --radius-modals: 12px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.2) 0px 3px 16px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.5) 0px 4px 30px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.34) 0px 20px 35px 0px, rgba(0, 0, 0, 0.25) 0px 4px 13px 0px;
  --shadow-md-2: rgba(255, 255, 255, 0.35) 0px 2px 14px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.35) 0px 20px 34px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.15) 0px 0px 0px 1px;

  /* Surfaces */
  --surface-page-canvas: #0b0c0;
  --surface-base-surface: #0e111b;
  --surface-elevated-surface: #0d172b;
  --surface-accent-card-surface: #12244f;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-gaze: #0e111b;
  --color-astral-deep: #0d172b;
  --color-nebula-black: #050606;
  --color-crystal-white: #ffffff;
  --color-lunar-dust: #abaebb;
  --color-ash-outline: #777a88;
  --color-comet-grey: #c7c9d1;
  --color-twilight-indigo: #12244f;
  --color-cosmic-violet: #1b346e;
  --color-starlight-violet: #85a6e9;
  --color-etherium-blue: #28b6ff;
  --color-deep-space-glow: #2862d7;
  --color-pink-nova: #FF7DDA;
  --color-frosty-glare: #D1D3FF;

  /* Typography */
  --font-figtree: 'Figtree', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-ibm-plex-mono: 'IBM Plex Mono', ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace;

  /* Typography — Scale */
  --text-heading-sm: 20px;
  --leading-heading-sm: 1.25;
  --tracking-heading-sm: -0.027px;
  --text-heading: 28px;
  --leading-heading: 1.25;
  --tracking-heading: -0.023px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.13;
  --tracking-heading-lg: -0.02px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.02px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-36: 36px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-76: 76px;
  --spacing-80: 80px;
  --spacing-104: 104px;
  --spacing-160: 160px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-sm: 2px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.2) 0px 3px 16px 0px;
  --shadow-xl: rgba(0, 0, 0, 0.5) 0px 4px 30px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.34) 0px 20px 35px 0px, rgba(0, 0, 0, 0.25) 0px 4px 13px 0px;
  --shadow-md-2: rgba(255, 255, 255, 0.35) 0px 2px 14px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.35) 0px 20px 34px 0px;
  --shadow-subtle: rgba(0, 0, 0, 0.15) 0px 0px 0px 1px;
}
```
