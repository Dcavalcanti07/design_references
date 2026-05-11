# Analogue aF-1 — Style Reference
> monochromatic product showcase with blue spark

**Theme:** light

Analogue aF-1 employs a monochromatic, product-focused aesthetic, contrasting stark black product shots with clean white or subtle gradient backgrounds. Typography is precise and compact, using narrow sans-serifs for headings and a modern sans-serif for body text, contributing to an impression of quiet confidence. A single vivid blue serves as the primary accent, drawing attention to calls to action, while overall density is compact, prioritizing content over expansive negative space.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary body text, borders, iconography |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, primary card surfaces, input text |
| Deep Graphite | `#171717` | `--color-deep-graphite` | Secondary text, darker card backgrounds, text on light cards |
| Pale Ash | `#ededed` | `--color-pale-ash` | Subtle card backgrounds, section dividers, very subtle contrast on white |
| Mid Slate | `#696969` | `--color-mid-slate` | Muted helper text, secondary body text |
| Light Mist | `#b9b9b9` | `--color-light-mist` | Tertiary text, subtle borders, placeholder text in inputs |
| Electric Blue | `#002fff` | `--color-electric-blue` | Primary action buttons, interactive elements, accent for key information. This vivid blue is the only chromatic color used for functional UI elements |
| Dark Film Gradient | `linear-gradient(rgb(7, 7, 7) 27%, rgb(36, 36, 38) 100%)` | `--color-dark-film-gradient` | Background for full-bleed dark sections, evoking a film strip |
| Sky Fade Gradient | `radial-gradient(50% 75%, rgb(0, 54, 140) 0%, rgb(0, 79, 206) 10.6771%, rgb(237, 237, 237) 100%)` | `--color-sky-fade-gradient` | Subtle background gradient for hero section, creating a soft atmospheric effect |

## Tokens — Typography

### Graphik Medium — Primary headings, action button text, and other prominent text elements. Its geometric structure provides a modern, functional voice, with precise and often very tight letter-spacing that suggests careful engineering. · `--font-graphik-medium`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 11px, 13px, 14px, 15px, 16px, 22px, 34px, 40px, 150px
- **Line height:** 0.85, 1.00, 1.20, 1.50
- **Letter spacing:** -0.0670em at 150px, -0.0530em at 40px, -0.0450em at 34px, -0.0300em at 22px, -0.0250em at 16px, -0.0210em at 15px, -0.0200em at 14px
- **Role:** Primary headings, action button text, and other prominent text elements. Its geometric structure provides a modern, functional voice, with precise and often very tight letter-spacing that suggests careful engineering.

### ITC Garamond Std Light Narrow — Secondary headings and larger body text. This delicate, narrow serif is used for more reflective or poetic statements, providing a classic counterpoint to the more rigorous sans-serif. · `--font-itc-garamond-std-light-narrow`
- **Substitute:** Garamond, serif
- **Weights:** 400
- **Sizes:** 15px, 17px, 30px, 40px, 64px
- **Line height:** 0.90, 1.20
- **Letter spacing:** -0.0230em at 64px, -0.0220em at 40px, -0.0180em at 30px, -0.0170em at 17px
- **Role:** Secondary headings and larger body text. This delicate, narrow serif is used for more reflective or poetic statements, providing a classic counterpoint to the more rigorous sans-serif.

### sans-serif — Small functional text like footnotes, labels, or meta-information. Uses browser default rendering for utility. · `--font-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Small functional text like footnotes, labels, or meta-information. Uses browser default rendering for utility.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 11px | 1.5 | -0.22px | `--text-caption` |
| body | 15px | 1.2 | -0.315px | `--text-body` |
| heading-sm | 22px | 1 | -0.66px | `--text-heading-sm` |
| heading | 30px | 0.9 | -0.54px | `--text-heading` |
| heading-lg | 40px | 0.9 | -0.88px | `--text-heading-lg` |
| display | 64px | 0.9 | -1.472px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 5 | 5px | `--spacing-5` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 20px |
| inputs | 15px |
| buttons | 10px |
| capsules | 100px |
| largeElements | 30px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset` | `--shadow-subtle` |

### Layout

- **Section gap:** 50px
- **Card padding:** 20px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Main call to action.

Electric Blue background (#002fff), Canvas White text (#ffffff). Rounded corners at 10px radius. Padding 0px top/bottom, 14px left/right. Tight letter-spacing from Graphik Medium.

### Ghost Button
**Role:** Secondary and tertiary actions.

Canvas White background (#ffffff), Deep Graphite text (#171717), and a 1px border of Deep Graphite. Rounded corners at 10px radius. No internal padding specified from analysis.

### Outline Ghost Button (Header)
**Role:** Ghost action, but with brand primary color border.

Canvas White text (#ffffff), transparent background, with a 1px border in Canvas White. Used in contexts demanding subtle action. Rounded corners at 10px.

### Input Field (Dark)
**Role:** User input for forms in dark sections.

Semi-transparent background (rgba(255, 255, 255, 0.11)), Canvas White text (#ffffff), 1px border in Canvas White. Rounded at 15px radius. Has an inset shadow rgba(255, 255, 255, 0.15) 0px 0px 0px 1px. Padding 15px top, 115px right (likely for internal icon or suffix), 15px bottom, 15px left.

### Light Card
**Role:** Content container on light backgrounds.

Pale Ash (rgba(237, 237, 237, 0.5) or rgb(237, 237, 237)) background with 20px radius. No shadow. No standard padding observed, implying content dictates spacing.

### Dark Card
**Role:** Content container on light backgrounds for contrasting information.

Deep Graphite background (#171717) with 20px radius. No shadow. 20px padding on all sides internally.

### Rounded Highlight Card
**Role:** Distinct content container or image wrapper.

Uses Pale Ash background (#ededed) with a large 30px border radius. No shadow. No internal padding set by the component itself.

## Do's and Don'ts

### Do
- Use Electric Blue (#002fff) exclusively for active clickable elements and strong accents, reserving it for primary calls to action.
- Apply Graphik Medium for all headings and interactive text, ensuring precise letter-spacing with a strong negative track, especially at larger sizes.
- Utilize ITC Garamond Std Light Narrow for softer, more narrative content, maintaining its light weight and tight line height.
- Implement Canvas White (#ffffff) as the dominant background for the UI, providing a clean canvas for product display.
- Employ Pale Ash (#ededed) for subtle background shifts to differentiate content blocks or as card surfaces against Canvas White.
- Ensure all interactive elements, especially buttons and inputs, adhere to the specified border radii: 10px for buttons, 15px for inputs.
- Maintain a compact element gap of 10px for vertical stacking of related items, reflecting the site's dense information presentation.

### Don't
- Do not introduce new chromatic colors; maintain the monochromatic palette with Electric Blue as the sole accent.
- Avoid excessive use of shadows; elevation is minimal and typically inset on specific input fields only.
- Do not use ITC Garamond Std Light Narrow for primary UI actions or very small text, where readability is paramount.
- Do not deviate from the prescribed letter-spacing values for Graphik Medium; they are crucial to the typographic identity.
- Avoid large amounts of negative space between sections; the layout favors a compact content arrangement.
- Do not use generic border radii; adhere strictly to 10px for buttons, 15px for inputs, 20px for cards, and 30px for prominent elements.
- Do not use generic system fonts for headings; Graphik Medium and ITC Garamond Std Light Narrow establish the brand's distinct voice.

## Imagery

The site primarily uses high-fidelity product photography, showcasing the camera from various angles as the central focus. These product shots are usually isolated on clean white or subtle gradient backgrounds, emphasizing the product itself over lifestyle context. Minimal photography for context (e.g., a couple at night) is treated with a dark, moody filter to support the introspective brand message. Graphics are limited to simple outlines or solid fills, with icons following a clean, minimalist style. Imagery is dominant in the hero section and product detail areas, serving to showcase and explain, often taking up significant visual space.

## Layout

The page generally follows a max-width contained layout, with content centered. The hero section is full-bleed, featuring a large product render over a soft radial gradient. Subsequent sections often alternate between full-bleed dark photographic backgrounds that establish mood, and clean white sections for product details and specifications. Content within sections is often arranged in centered stacks or simple two-column layouts. Vertical spacing is compact, creating an information-dense feel. Navigation is a minimal top bar with logo and language selector.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #ffffff
border: #171717
accent: #002fff
primary action: #002fff (filled action)

Example Component Prompts:
1. Create a Primary Filled Button: Electric Blue background (#002fff), Canvas White text (#ffffff), 10px radius, Graphik Medium font, 0px top/bottom padding, 14px left/right padding.
2. Design an Input Field: Semi-transparent white background (rgba(255, 255, 255, 0.11)), Canvas White text (#ffffff), 1px Canvas White border, 15px radius, with an inset shadow rgba(255, 255, 255, 0.15) 0px 0px 0px 1px. Use Graphik Medium for text input.
3. Build a Light Card: Pale Ash background (#ededed), 20px radius. Content inside should use Deep Graphite text (#171717) with 20px padding around it. 
4. Render a Hero Headline: 'Analogue aF-1' using ITC Garamond Std Light Narrow, size 64px, weight 400, line-height 0.9, letter-spacing -1.472px, Canvas White text (#ffffff).
5. Create a Ghost Button for Secondary Action: Canvas White background (#ffffff), Deep Graphite text (#171717), 1px Deep Graphite border, 10px radius, Graphik Medium font.

## Similar Brands

- **Nothing** — Monochrome palette with a single, vivid accent color, coupled with bold but precise typography for a tech brand aesthetic.
- **Field Notes** — Product-focused landing pages with clean visuals and a strong emphasis on practical utility and minimalist design.
- **Areaware** — Showcasing engineered products with detailed photography on stark, clean backgrounds, using a sophisticated typographic blend.
- ** Teenage Engineering** — Minimalist design language, compact and intentionally constrained color palettes, and distinct typographic choices for electronic products.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-graphite: #171717;
  --color-pale-ash: #ededed;
  --color-mid-slate: #696969;
  --color-light-mist: #b9b9b9;
  --color-electric-blue: #002fff;
  --color-dark-film-gradient: #070707;
  --gradient-dark-film-gradient: linear-gradient(rgb(7, 7, 7) 27%, rgb(36, 36, 38) 100%);
  --color-sky-fade-gradient: #00368c;
  --gradient-sky-fade-gradient: radial-gradient(50% 75%, rgb(0, 54, 140) 0%, rgb(0, 79, 206) 10.6771%, rgb(237, 237, 237) 100%);

  /* Typography — Font Families */
  --font-graphik-medium: 'Graphik Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-itc-garamond-std-light-narrow: 'ITC Garamond Std Light Narrow', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.22px;
  --text-body: 15px;
  --leading-body: 1.2;
  --tracking-body: -0.315px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.66px;
  --text-heading: 30px;
  --leading-heading: 0.9;
  --tracking-heading: -0.54px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.88px;
  --text-display: 64px;
  --leading-display: 0.9;
  --tracking-display: -1.472px;

  /* Typography — Weights */
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 20px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Named Radii */
  --radius-cards: 20px;
  --radius-inputs: 15px;
  --radius-buttons: 10px;
  --radius-capsules: 100px;
  --radius-largeelements: 30px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #000000;
  --color-canvas-white: #ffffff;
  --color-deep-graphite: #171717;
  --color-pale-ash: #ededed;
  --color-mid-slate: #696969;
  --color-light-mist: #b9b9b9;
  --color-electric-blue: #002fff;
  --color-dark-film-gradient: #070707;
  --color-sky-fade-gradient: #00368c;

  /* Typography */
  --font-graphik-medium: 'Graphik Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-itc-garamond-std-light-narrow: 'ITC Garamond Std Light Narrow', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 11px;
  --leading-caption: 1.5;
  --tracking-caption: -0.22px;
  --text-body: 15px;
  --leading-body: 1.2;
  --tracking-body: -0.315px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1;
  --tracking-heading-sm: -0.66px;
  --text-heading: 30px;
  --leading-heading: 0.9;
  --tracking-heading: -0.54px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.88px;
  --text-display: 64px;
  --leading-display: 0.9;
  --tracking-display: -1.472px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-5: 5px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-md: 6px;
  --radius-lg: 10px;
  --radius-xl: 15px;
  --radius-2xl: 20px;
  --radius-3xl: 30px;
  --radius-full: 100px;

  /* Shadows */
  --shadow-subtle: rgba(255, 255, 255, 0.15) 0px 0px 0px 1px inset;
}
```
