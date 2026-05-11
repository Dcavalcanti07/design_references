# Ecosia — Style Reference
> Forest Canopy Blueprint — crisp text and vivid green for a nature-inspired search engine.

**Theme:** light

Ecosia employs a naturalistic, growth-focused design system with stark achromatic backgrounds overlaid by vivid green accents. Typography uses a confident sans-serif pairing for clarity and impact, while generous spacing creates an airy, uncrowded feel. Components prioritize soft, organic shapes with deep rounding, reflecting an environmental ethos. The visual language is quiet and purposeful, with color used sparingly to highlight key actions and data.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Fern | `#d7eb80` | `--color-forest-fern` | Primary action background, accent for data visualizations and highlighted cards. Its strong, natural green conveys growth and environmental impact |
| Midnight Ash | `#333333` | `--color-midnight-ash` | Neutral form states, badge text, and quiet UI feedback where color should stay understated. Do not promote it to the primary CTA color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, ghost button backgrounds. A clean, expansive base for content |
| Fog Gray | `#f0f0eb` | `--color-fog-gray` | Subtle background for alternate card surfaces, providing visual separation without harsh contrast |
| Muted Shadow | `#6c6c6c` | `--color-muted-shadow` | Secondary text, muted links, subtle button borders, and default icon fills. Softer than Midnight Ash for less visual emphasis |
| Soft Mist | `#f8f8f6` | `--color-soft-mist` | Elevated card backgrounds, offering a barely-there differentiation from the Canvas White |
| Silver Whisper | `#bebeb9` | `--color-silver-whisper` | Hairline borders and subtle dividers, almost disappearing into the background |
| Stone Glaze | `#b6b6b6` | `--color-stone-glaze` | Slightly darker secondary card backgrounds, subtly defining layered containers |
| Deep Shadow | `#cccccc` | `--color-deep-shadow` | Card shadow color, providing a soft, diffused elevation |

## Tokens — Typography

### Founders Grotesk — Display headlines and prominent section titles. Its purposeful appearance conveys authority without being overly bold, especially at larger sizes. · `--font-founders-grotesk`
- **Substitute:** Montserrat
- **Weights:** 400, 600, 700
- **Sizes:** 16px, 24px, 36px, 48px, 54px
- **Line height:** 1.10, 1.30, 1.40
- **Role:** Display headlines and prominent section titles. Its purposeful appearance conveys authority without being overly bold, especially at larger sizes.

### Inter — Body copy, button labels, navigation, and all textual UI components. Its high legibility at small sizes ensures clarity across the interface. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 36px
- **Line height:** 1.15, 1.40
- **Letter spacing:** 0.006em at 12-14px, 0.007em at 16-36px
- **Role:** Body copy, button labels, navigation, and all textual UI components. Its high legibility at small sizes ensures clarity across the interface.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.072px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.084px | `--text-body-sm` |
| body | 16px | 1.4 | 0.096px | `--text-body` |
| subheading | 18px | 1.4 | 0.108px | `--text-subheading` |
| heading | 24px | 1.3 | — | `--text-heading` |
| heading-lg | 36px | 1.15 | — | `--text-heading-lg` |
| display | 54px | 1.1 | — | `--text-display` |

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
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10-20px |
| links | 4px |
| other | 40px |
| buttons | 9999px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.2) 0px 11px 33px 0px` | `--shadow-xl` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Pill Button - Primary
**Role:** Call to action for key conversions.

Filled with Forest Fern (#d7eb80), text in Midnight Ash (#333333), 9999px border-radius, 0px vertical padding, 15px horizontal padding. Example: 'Switch to Ecosia — it’s free'.

### Pill Button - Ghost
**Role:** Secondary actions or internal links where visual weight should be minimal.

Transparent background, text and 1px border in Midnight Ash (#333333), 9999px border-radius, 0px vertical padding, 11px horizontal padding.

### Search Input Field
**Role:** Primary interaction for content discovery.

Transparent background, 1px border in Midnight Ash (#333333), 0px border-radius by default, with potential for rounded container. Text in Midnight Ash (#333333).

### Primary Feature Card
**Role:** Highlighting key initiatives or features.

Background in Canvas White (#ffffff) or Forest Fern (#d7eb80), 20px border-radius, no shadow. Padding varies (e.g., 64px top, 40px bottom, 0px horizontal for full bleed sections, or 40px horizontal for contained sections).

### Data Stat Card
**Role:** Showcasing numerical impact.

Background in Soft Mist (#f8f8f6), 20px border-radius, sometimes with a subtle Deep Shadow. 16px padding on all sides. Content typically centered.

### Minimal Card
**Role:** Subtle content grouping, often within larger sections.

Background in Fog Gray (#f0f0eb), 20px border-radius, no shadow. Minimal padding (e.g., 16px).

### Overlay Card
**Role:** Semi-transparent elements, often for atmospheric display.

Background in rgba(26, 26, 26, 0.32), 10px border-radius, no shadow.

## Do's and Don'ts

### Do
- Prioritize Forest Fern (#d7eb80) for all primary actions and indicators of positive impact, ensuring it stands out against neutral backgrounds.
- Use Founders Grotesk for all major headings (24px and above) and Inter for all body text, UI elements, and smaller headings (20px and below).
- Apply 9999px border-radius to all buttons for a friendly, organic pill shape.
- Maintain a comfortable density with 16px element gaps and 40px vertical section gaps.
- Pad cards with 16px internally, using 20px border-radius, and ensure card text contrasting Midnight Ash (#333333) or Muted Shadow (#6c6c6c) against Canvas White (#ffffff) or Soft Mist (#f8f8f6).
- Use Midnight Ash (#333333) for primary text and strong borders, and Muted Shadow (#6c6c6c) for secondary, less emphasized information.
- Implement a maximum page width of 1200px to keep content focused and readable.

### Don't
- Avoid using saturated colors other than Forest Fern (#d7eb80) for core UI elements; color should be a conscious accent.
- Do not deviate from the established font families Founders Grotesk and Inter anywhere in the interface.
- Refrain from using sharp corners on interactive elements; prefer the provided radii for buttons, cards, and links.
- Do not introduce complex gradient fills; the system relies on solid color blocks and subtle background imagery.
- Avoid excessive use of shadows; elevation is minimal and applied subtly with Deep Shadow (#cccccc) only when necessary for visual hierarchy.
- Do not use dark backgrounds for main content areas; the theme is predominantly light and airy.
- Resist dense, information-heavy layouts; favor ample spacing and clear content blocks.

## Elevation

- **Data Stat Card:** `rgba(0, 0, 0, 0.2) 0px 11px 33px 0px`

## Imagery

Ecosia utilizes a mix of natural photography and abstract, organic-feeling graphics. Photography tends to be high-key, featuring lush green landscapes (often hinting at tree planting or nature vistas), or aspirational shots of renewable energy like solar panels. These images are often contained within softly rounded card shapes (20px radius). UI elements like the search bar background utilize abstract, painterly green textures that evoke nature without being literal. Icons are predominantly filled in mono-color (Midnight Ash or Forest Fern), simple, and communicative. The overall density is balanced, allowing imagery to serve as a backdrop or contextual element without overwhelming the textual content, creating an atmospheric feel that reinforces the brand's purpose.

## Layout

The page primarily follows a max-width contained model, typically within 1200px, centring content for focus. The hero section is full-bleed with a dark, abstracted green background, featuring a strong centered headline and the primary search interaction. Subsequent sections alternate between full-width and contained content, maintaining a consistent vertical rhythm through generous section gaps (around 40px). Content is often arranged in a two-column layout, with text on one side and a visual element (image, chart, card) on the other. A four-column grid is used for displaying feature cards. The navigation is a subtle top bar, with a prominent 'Switch to Ecosia' button, indicating an encouraging, rather than obtrusive, user journey.

## Agent Prompt Guide

Quick Color Reference: 
- text: #333333
- background: #ffffff
- border: #333333
- accent: #d7eb80
- primary action: #d7eb80 (filled action)

Example Component Prompts:
- Create a hero section with an abstract green background: Centered headline 'Search. Find. Change the World.' in Founders Grotesk 54px weight 700, #ffffff. Below that, a search input with a transparent background, 1px border #333333, with 'Search the web...' placeholder text, and an 'AI Chat' ghost button to the right (transparent background, #333333 text, 9999px radius, 0px vertical padding, 11px horizontal padding) aligned with the input field. The input field text is #333333, Inter 16px weight 400.
- Design a Primary Feature Card: Background Forest Fern (#d7eb80), 20px border-radius, with 64px top padding and 40px bottom padding. Inside, '100% of profits for the planet' headline in Founders Grotesk 24px weight 600, #333333. Body text 'We use all our profits for climate action...' in Inter 16px weight 400, #333333.
- Build a Data Stat Card: Background Soft Mist (#f8f8f6), 20px border-radius, with rgba(0, 0, 0, 0.2) 0px 11px 33px 0px shadow. Inside, text '#d7eb80' for the number '#d7eb80' in Founders Grotesk 36px weight 700 with a Muted Shadow (#6c6c6c) descriptive label below it in Inter 14px weight 400.

## Similar Brands

- **Tree Card** — Shares a green, nature-inspired palette with a focus on environmental impact and a clean, almost 'blank canvas' UI approach.
- **DuckDuckGo** — Employs a very clean, minimalist search interface with a focus on privacy and a restrained use of color for functional elements.
- **Linear** — Uses a mostly achromatic base with a single, vivid primary accent color for actions and highlights, alongside crisp typography.
- **OpenAI** — Features clean interfaces, ample white space, and a deliberate use of color to guide user attention, particularly in search/input contexts.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-fern: #d7eb80;
  --color-midnight-ash: #333333;
  --color-canvas-white: #ffffff;
  --color-fog-gray: #f0f0eb;
  --color-muted-shadow: #6c6c6c;
  --color-soft-mist: #f8f8f6;
  --color-silver-whisper: #bebeb9;
  --color-stone-glaze: #b6b6b6;
  --color-deep-shadow: #cccccc;

  /* Typography — Font Families */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.072px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.084px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.096px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.108px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.15;
  --text-display: 54px;
  --leading-display: 1.1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-cards: 10-20px;
  --radius-links: 4px;
  --radius-other: 40px;
  --radius-buttons: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.2) 0px 11px 33px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-fern: #d7eb80;
  --color-midnight-ash: #333333;
  --color-canvas-white: #ffffff;
  --color-fog-gray: #f0f0eb;
  --color-muted-shadow: #6c6c6c;
  --color-soft-mist: #f8f8f6;
  --color-silver-whisper: #bebeb9;
  --color-stone-glaze: #b6b6b6;
  --color-deep-shadow: #cccccc;

  /* Typography */
  --font-founders-grotesk: 'Founders Grotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.072px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.084px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: 0.096px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: 0.108px;
  --text-heading: 24px;
  --leading-heading: 1.3;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.15;
  --text-display: 54px;
  --leading-display: 1.1;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 10px;
  --radius-2xl: 20px;
  --radius-3xl: 40px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.2) 0px 11px 33px 0px;
}
```
