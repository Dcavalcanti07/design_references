# Cards Against Humanity — Style Reference
> Irreverent, Urgent Distress: High-contrast black and off-white with a jarring red accent, like a bold, distressed propaganda poster.

**Theme:** dark

Cards Against Humanity Climate Catastrophe Pack projects an urgent, confrontational aesthetic: stark black and off-white surfaces, punctuated by a vibrant, almost aggressive red, and an eclectic, distressed display typography. The design leans into a deliberately unpolished, DIY feel, using basic geometric shapes, high-contrast text, and a loose rhythm of concentric circles and scattered warning icons. This visual system aims to grab attention and provoke, mirroring the brand's irreverent tone with bold, no-nonsense presentation.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Catastrophe Red | `#ff4034` | `--color-catastrophe-red` | Brand accent, highlighting urgent text, interactive borders, and key atmospheric elements like flames — a vivid, almost alarming splash of color |
| Pitch Black | `#000000` | `--color-pitch-black` | Dominant background, primary text color, button backgrounds, and strong borders — forms the high-contrast foundation of the design |
| Aged Paper | `#ebe4d8` | `--color-aged-paper` | Primary surface color for text blocks, card backgrounds, and button text when on dark backgrounds — a soft, slightly off-white that softens the stark black |
| Charcoal Haze | `#c3bdb3` | `--color-charcoal-haze` | Subtle button box shadow that provides minimal elevation without adding strong depth |

## Tokens — Typography

### Spektra — Display headlines and impactful calls to action — its distinctive, distressed character immediately communicates the brand's unique voice and satirical intent. · `--font-spektra`
- **Substitute:** Abril Fatface, or Public Sans Black
- **Weights:** 400
- **Sizes:** 32px, 40px, 100px, 202px
- **Line height:** 0.82, 0.88, 1.00, 2.00
- **Letter spacing:** normal
- **Role:** Display headlines and impactful calls to action — its distinctive, distressed character immediately communicates the brand's unique voice and satirical intent.

### Helvetica Neue LT — Body copy, links, and supporting text — provides a clear, utilitarian contrast to the expressive display font, ensuring readability for longer content blocks. · `--font-helvetica-neue-lt`
- **Substitute:** Arial, or Inter
- **Weights:** 400, 800
- **Sizes:** 14px, 16px, 28px, 30px
- **Line height:** 1.27, 1.29, 1.50
- **Letter spacing:** normal
- **Role:** Body copy, links, and supporting text — provides a clear, utilitarian contrast to the expressive display font, ensuring readability for longer content blocks.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.29 | — | `--text-caption` |
| body | 16px | 1.27 | — | `--text-body` |
| subheading | 28px | 1.5 | — | `--text-subheading` |
| heading | 30px | 1.29 | — | `--text-heading` |
| heading-lg | 32px | 1 | — | `--text-heading-lg` |
| display | 202px | 0.82 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 14 | 14px | `--spacing-14` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 25 | 25px | `--spacing-25` |
| 29 | 29px | `--spacing-29` |
| 30 | 30px | `--spacing-30` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |
| 168 | 168px | `--spacing-168` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 2520px |
| inputs | 10px |
| buttons | 80px |

### Layout

- **Section gap:** 30px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Rounded Primary Button
**Role:** Call to action

Filled Pitch Black background with Aged Paper text. Features extremely rounded corners at 120px for a soft, almost pill-like shape. Padding: 7px vertical, 7px horizontal.

### Elongated Primary Button
**Role:** Large call to action

Filled Pitch Black background with Aged Paper text. Employs a 80px border-radius, creating an elongated oval. Padding: 0px vertical, 60px horizontal.

### Pill Outline Button
**Role:** Subtle action

Ghost button with 48px border-radius, no background fill, and black text. Used for less prominent actions.

### Circular Card
**Role:** Decorative content container

Pitch Black background with a 100% border-radius, creating a perfect circle. No padding or shadow, used for visual accents or small, contained content.

### Input Field
**Role:** User entry field

Aged Paper background, Pitch Black text, and a 10px border-radius for rounded corners. Generous horizontal padding of 20px with 6px bottom padding, implying text entry.

## Do's and Don'ts

### Do
- Use Spektra for all headlines and impactful short text to leverage its unique character, prioritizing visual impact over conventional readability.
- Maintain a stark contrast by pairing Pitch Black (#000000) for backgrounds and text with Aged Paper (#ebe4d8) for supporting surfaces and inverted text.
- Implement Catastrophe Red (#ff4034) sparingly, primarily as an urgent accent for borders, interactive elements, or key text, emphasizing its high saturation.
- Apply extremely high border-radii (80px, 120px, 48px) to buttons to convey a playful, almost blob-like or pill aesthetic.
- Utilize Helvetica Neue LT for all body copy and instructional text, ensuring clarity and contrast against the expressive display font.
- Maintain a spacious rhythm between content blocks with a section gap of 30px to prevent visual clutter and allow design elements breathing room.

### Don't
- Avoid using gradients or subtle shadows, as the system relies on high contrast and flat surfaces, except for the subtle Charcoal Haze button shadow.
- Do not introduce additional color hues; restrict the palette strictly to Pitch Black, Aged Paper, and Catastrophe Red to maintain visual integrity.
- Refrain from complex component structures; components should be simple, high-contrast shapes, often with extreme roundedness.
- Do not use subtle spacing values; prefer clear, distinct gaps like 20px for elements and 30px for sections to reinforce the bold aesthetic.
- Avoid decorative imagery that dilutes the stark, graphic, and text-heavy nature of the design.
- Do not use traditional, corporate typography or unrounded shapes, which would contradict the brand's irreverent and distressed visual language.

## Imagery

The site uses a mix of scattered, minimalistic, and somewhat distressed iconography/geometric shapes (concentric red circles, abstract warning symbols) for decorative atmosphere, rather than photography or complex illustrations. These are often outlined in Catastrophe Red. There's also striking, full-bleed imagery like the 'flames' graphic, which serves as a decorative, high-impact background element, purely for atmosphere. Imagery is dense in selective areas to create visual intensity, contrasting with text-dominant sections.

## Layout

The page primarily uses a full-bleed layout, particularly for hero and atmospheric sections, allowing large graphic elements to span the full viewport width. Content sections are centrally aligned, but with a flexible max-width, allowing for long-form text blocks on an Aged Paper background. The hero section prominently features a centered, oversized headline (Spektra font) over a dark, graphically rich background. Section rhythm is irregular, creating an almost chaotic, collage-like feel, underscored by a dense, circular graphic pattern rather than consistent spacing. Content stacks are generally simple, centered text blocks, occasionally broken by decorative elements.

## Agent Prompt Guide

Quick Color Reference:
text: #000000
background: #000000
border: #ff4034
accent: #ff4034
primary action: #000000 (filled action)

Example Component Prompts:
1. Create a Primary Action Button: #000000 background, #ebe4d8 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
2. Design a central text card: Aged Paper background, Helvetica Neue LT body text at 16px weight 400, Pitch Black color, with 20px padding. 
3. Build a large headline section: Spektra font, size 202px weight 400, Pitch Black text, on an Aged Paper background.
4. Produce an input field: Aged Paper background, 10px border-radius, Pitch Black text, 20px horizontal padding, 6px bottom padding, Helvetica Neue LT font.

## Similar Brands

- **Cards Against Humanity (main site)** — Shares the same irreverent, anti-design design philosophy with jarring typography and high-contrast color schemes.
- **Oatly** — Uses a similar approach to bold, highly opinionated typography and a limited, punchy color palette to convey a strong brand voice.
- **VICE Media** — Employs high-contrast, often black-and-white visuals with disruptive typography and occasional use of strong accent colors to communicate an edgy, confrontational tone.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-catastrophe-red: #ff4034;
  --color-pitch-black: #000000;
  --color-aged-paper: #ebe4d8;
  --color-charcoal-haze: #c3bdb3;

  /* Typography — Font Families */
  --font-spektra: 'Spektra', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-neue-lt: 'Helvetica Neue LT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.29;
  --text-body: 16px;
  --leading-body: 1.27;
  --text-subheading: 28px;
  --leading-subheading: 1.5;
  --text-heading: 30px;
  --leading-heading: 1.29;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --text-display: 202px;
  --leading-display: 0.82;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-168: 168px;

  /* Layout */
  --section-gap: 30px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 48px;
  --radius-full-2: 80px;
  --radius-full-3: 120px;
  --radius-full-4: 2520px;

  /* Named Radii */
  --radius-cards: 2520px;
  --radius-inputs: 10px;
  --radius-buttons: 80px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-catastrophe-red: #ff4034;
  --color-pitch-black: #000000;
  --color-aged-paper: #ebe4d8;
  --color-charcoal-haze: #c3bdb3;

  /* Typography */
  --font-spektra: 'Spektra', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-helvetica-neue-lt: 'Helvetica Neue LT', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.29;
  --text-body: 16px;
  --leading-body: 1.27;
  --text-subheading: 28px;
  --leading-subheading: 1.5;
  --text-heading: 30px;
  --leading-heading: 1.29;
  --text-heading-lg: 32px;
  --leading-heading-lg: 1;
  --text-display: 202px;
  --leading-display: 0.82;

  /* Spacing */
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-14: 14px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-25: 25px;
  --spacing-29: 29px;
  --spacing-30: 30px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;
  --spacing-168: 168px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-full: 48px;
  --radius-full-2: 80px;
  --radius-full-3: 120px;
  --radius-full-4: 2520px;
}
```
