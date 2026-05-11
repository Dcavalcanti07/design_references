# Daniel Sun — Style Reference
> Solar Flare Canvas. A radiant yellow burst on a clean, stark white backdrop defines the visual energy.

**Theme:** light

This design system feels like a bold, sunny declaration. It pairs extreme typographic scale with a soft, limited color palette focused on vivid yellow and stark black and white. The visual identity hinges on the tension between playful handwritten accents and massive, condensed sans-serif headlines, creating a brand that feels both approachable and impactful.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Sunbeam Yellow | `#ffd500` | `--color-sunbeam-yellow` | Decorative elements, subtle highlights, active button indicators — a burst of vivid energy in an otherwise neutral palette. |
| Pitch Black | `#000000` | `--color-pitch-black` | Most prominent text color for headings and body, providing stark contrast against white backgrounds. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Primary page background, card surfaces, and text color on dark elements. |
| Pale Gray | `#f5f5f5` | `--color-pale-gray` | Secondary background color for sections and cards, providing a subtle differentiation from pure white. |
| Ash Gray | `#808080` | `--color-ash-gray` | Secondary text, descriptive elements. Offers softer contrast than Pitch Black, maintaining legibility. |
| Silver Mist | `#a6a6a6` | `--color-silver-mist` | Subtle text and borders, creating visual texture without distraction. |
| Shadow Gradient | `linear-gradient(rgb(230, 230, 230) 0%, rgb(166, 166, 166) 100%)` | `--color-shadow-gradient` | Background for subtle elevation or depth, usually found in larger UI sections or shadowed elements. |

## Tokens — Typography

### Reddit Sans Condensed — Dominant display font for headlines and impactful statements. Its condensed, ultra-bold presence with tight letter-spacing is a signature visual identity marker, creating strong, almost architectural text blocks. · `--font-reddit-sans-condensed`
- **Substitute:** Bebas Neue
- **Weights:** 900
- **Sizes:** 36px, 88px, 246px
- **Line height:** 0.90, 0.96, 1.00
- **Letter spacing:** -0.0730em, -0.0340em, -0.0280em
- **OpenType features:** `"cpsp"; "liga" 0`
- **Role:** Dominant display font for headlines and impactful statements. Its condensed, ultra-bold presence with tight letter-spacing is a signature visual identity marker, creating strong, almost architectural text blocks.

### Inter Display — Primary font for body text, subheadings, and medium-sized informational content. Its clarity and moderate weight provide a clean balance to the condensed headlines. · `--font-inter-display`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 18px, 20px, 26px, 30px
- **Line height:** 1.10, 1.30, 1.35
- **Role:** Primary font for body text, subheadings, and medium-sized informational content. Its clarity and moderate weight provide a clean balance to the condensed headlines.

### Inter — Used for smaller body text, captions, and occasionally for very large, specific type treatments. The tighter letter-spacing subtly adds to its readability in dense contexts. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 14px, 20px, 128px
- **Line height:** 1.20
- **Letter spacing:** -0.0360em, -0.0160em
- **Role:** Used for smaller body text, captions, and occasionally for very large, specific type treatments. The tighter letter-spacing subtly adds to its readability in dense contexts.

### sans-serif — Utility font for the smallest text elements like tags, metadata, and default browser text. Its neutrality ensures it doesn't compete with brand fonts. · `--font-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Utility font for the smallest text elements like tags, metadata, and default browser text. Its neutrality ensures it doesn't compete with brand fonts.

### Caveat — Accent font for playful, humanistic touches, often used for dates or call-outs like 'from 2020 'til today'. Its handwritten feel provides a stark, warm contrast to the geometric sans-serifs. · `--font-caveat`
- **Substitute:** Dancing Script
- **Weights:** 700
- **Sizes:** 18px, 28px
- **Line height:** 0.96, 1.20
- **Letter spacing:** -0.0360em
- **Role:** Accent font for playful, humanistic touches, often used for dates or call-outs like 'from 2020 'til today'. Its handwritten feel provides a stark, warm contrast to the geometric sans-serifs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body-sm | 14px | 1.2 | -0.48px | `--text-body-sm` |
| body | 18px | 1.1 | -0.648px | `--text-body` |
| subheading | 20px | 1.2 | -0.72px | `--text-subheading` |
| heading | 30px | 1.35 | — | `--text-heading` |
| heading-lg | 36px | 0.9 | -2.628px | `--text-heading-lg` |
| display | 88px | 0.96 | -2.992px | `--text-display` |
| display-xl | 246px | 1 | -6.888px | `--text-display-xl` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 160 | 160px | `--spacing-160` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 32px |
| default | 14px |
| heroElement | 110px |
| largeImages | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.12) -2px 3px 3px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 64px

## Components

### Navigation Button
**Role:** Interactive element

Rounded button with rgba(255, 213, 0, 0.15) background, rgb(0, 0, 238) text color and border. Uses 32px border-radius, 6px vertical padding, 14px horizontal padding. The transparent yellow background with a blue border creates a subtle, interactive state contrasting a vivid yellow accent.

### Work Showcase Card
**Role:** Content display

Background is Pale Gray (#f5f5f5) or Canvas White (#ffffff). Features a drop shadow: rgba(0, 0, 0, 0.12) -2px 3px 3px 0px. Rounded corners at 14px. Inner content has padding of 16px. Imagery within may have 14px radius.

### Primary Heading (Sectional)
**Role:** Information hierarchy

Uses Reddit Sans Condensed, weight 900, size 36px, lineHeight 0.90, letterSpacing -2.628px. Color Pitch Black (#000000). Establishes major section titles with high impact.

### Sub-heading / Descriptor
**Role:** Contextual information

Uses Caveat, weight 700, size 18px, lineHeight 0.96, letterSpacing -0.648px. Color Ash Gray (#808080). Provides a warm, casual tone to introduce sections or add emphasis.

### Hero Display Text
**Role:** Brand statement

Uses Reddit Sans Condensed, weight 900, size 246px, lineHeight 1.00, letterSpacing -6.888px for 'Daniel Sun'. Pitch Black (#000000) text on Canvas White (#ffffff) background. The immense scale creates an immediate, unforgettable brand presence.

## Do's and Don'ts

### Do
- Use Reddit Sans Condensed (weight 900) for all main headlines and significant display text to maintain the strong, condensed visual identity.
- Pair the bold Reddit Sans Condensed with Inter Display (weight 500) for body text to ensure readability and balance.
- Introduce playful, handwritten elements using Caveat (weight 700) for dates, sub-headers like 'from 2020 'til today', or subtle accent text.
- Apply Sunbeam Yellow (#ffd500) sparingly as a vivid accent color, primarily for interactive elements or to draw attention to specific keywords.
- Maintain a predominantly Canvas White (#ffffff) and Pale Gray (#f5f5f5) background with Pitch Black (#000000) text for high contrast and readability.
- Use 32px border-radius for all primary buttons and interactive elements, giving them a distinct pill-like shape.
- Apply 14px border-radius consistently to all image containers and content cards (like Work Showcase Cards).

### Don't
- Do not use generic sans-serif fonts for headlines; always default to Reddit Sans Condensed for brand consistency.
- Avoid overusing Sunbeam Yellow (#ffd500); its impact comes from its scarcity and specific application.
- Do not introduce additional bold, condensed typefaces or calligraphic scripts; maintain the established font hierarchy.
- Avoid complex gradients beyond the subtle linear-gradient(rgb(230, 230, 230) 0%, rgb(166, 166, 166) 100%) for backgrounds.
- Do not use box-shadows other than rgba(0, 0, 0, 0.12) -2px 3px 3px 0px for element elevation.
- Do not introduce new border radii values; stick to 14px for cards/images and 32px for buttons.
- Avoid heavily stylized backgrounds or textures that detract from the clean canvas aesthetic.

## Imagery

The site uses a mix of photographic hero elements (the sunbeam graphic) and product screenshots within a clean UI. Photography is treated as a full-bleed background for the hero, creating an atmospheric backdrop. Product screenshots are contained within rounded (14px radius) card components, presented clearly with minimal embellishment, serving an explanatory and showcasing role. Icons are minimal, monochromatic, and likely part of a utility set, primarily functional rather than decorative. The overall density is balanced, with imagery serving as clear illustrative content contrasted against large type.

## Layout

The page primarily uses a full-bleed design, allowing the striking yellow sunbeam graphic to dominate the initial viewport. Content sections generally appear centered but without a strict max-width, allowing for large-scale typography and images to stretch. The rhythm is characterized by distinct, vertically stacked sections, often alternating between stark white backgrounds and subtle Pale Gray (#f5f5f5). Content is arranged in prominent stacks of headline-level text, followed by descriptive copy and product showcases. There's a strong emphasis on spaciousness, with ample vertical padding between sections (implied by 'sectionGap' and general visual breaks).

## Agent Prompt Guide

### Quick Color Reference
- Text: #000000 (Pitch Black)
- Background: #ffffff (Canvas White)
- Accent: #ffd500 (Sunbeam Yellow)
- Secondary Text: #808080 (Ash Gray)
- Button Background: rgba(255, 213, 0, 0.15)

### Example Component Prompts
1. Create a hero section: full-width, with a radial gradient from transparent to vivid yellow (representing 'Sunbeam Yellow') from the top-left corner as a background, fading to white on the right. Overlay this with a headline 'DANIEL SUN' (Reddit Sans Condensed, 246px, 900, #000000, letter-spacing -6.888px) centered vertically. Below it, add a sub-headline 'Howdy! Meet your trusted design partner,' (Inter Display, 30px, 500, #000000, 1.35 lineHeight) left-aligned.
2. Design a primary navigation button: 'Start project' text (Inter Display, 18px, 500, #0000ee - this blue is a browser default for links, so for brand consistency assume a dark neutral like #000000 unless specified). The button should have a background of rgba(255, 213, 0, 0.15), a 32px border-radius, and padding of 6px top/bottom, 14px left/right. The border should also be #0000ee (again, assume black as default unless clearly primary color).
3. Generate a 'work showcase' card: use Pale Gray (#f5f5f5) as the background with a 14px border-radius. Apply a box-shadow of rgba(0, 0, 0, 0.12) -2px 3px 3px 0px. Inside, add an image (14px border-radius) at the top, then 16px padding. Below the image, include a title 'Ruby' (Inter Display, 26px, 500, #000000), and a descriptor 'Branding, Web design, Development' (Inter Display, 18px, 500, #808080).
4. Create a section title: Start with a hand-written accent 'from 2020 'til today' (Caveat, 28px, 700, #808080, letter-spacing -1.008px). Below it, add a main heading 'MY LATEST WORK' (Reddit Sans Condensed, 36px, 900, #000000, letter-spacing -2.628px). Center both elements.

## Similar Brands

- **AIGA** — Exploits oversized, condensed typography for high impact and modern aesthetic.
- **Superside** — Uses a similar approach of clean layouts with impactful, often colorful, hero sections with stark typography.
- **Frank Digital** — Combines a minimalist aesthetic with a single strong accent color and bold, modern typefaces.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-sunbeam-yellow: #ffd500;
  --color-pitch-black: #000000;
  --color-canvas-white: #ffffff;
  --color-pale-gray: #f5f5f5;
  --color-ash-gray: #808080;
  --color-silver-mist: #a6a6a6;
  --color-shadow-gradient: #e6e6e6;
  --gradient-shadow-gradient: linear-gradient(rgb(230, 230, 230) 0%, rgb(166, 166, 166) 100%);

  /* Typography — Font Families */
  --font-reddit-sans-condensed: 'Reddit Sans Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caveat: 'Caveat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.48px;
  --text-body: 18px;
  --leading-body: 1.1;
  --tracking-body: -0.648px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.72px;
  --text-heading: 30px;
  --leading-heading: 1.35;
  --text-heading-lg: 36px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -2.628px;
  --text-display: 88px;
  --leading-display: 0.96;
  --tracking-display: -2.992px;
  --text-display-xl: 246px;
  --leading-display-xl: 1;
  --tracking-display-xl: -6.888px;

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
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Layout */
  --section-gap: 64px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 80px;
  --radius-full-2: 110px;
  --radius-full-3: 128px;

  /* Named Radii */
  --radius-buttons: 32px;
  --radius-default: 14px;
  --radius-heroelement: 110px;
  --radius-largeimages: 24px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.12) -2px 3px 3px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-sunbeam-yellow: #ffd500;
  --color-pitch-black: #000000;
  --color-canvas-white: #ffffff;
  --color-pale-gray: #f5f5f5;
  --color-ash-gray: #808080;
  --color-silver-mist: #a6a6a6;
  --color-shadow-gradient: #e6e6e6;

  /* Typography */
  --font-reddit-sans-condensed: 'Reddit Sans Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caveat: 'Caveat', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.48px;
  --text-body: 18px;
  --leading-body: 1.1;
  --tracking-body: -0.648px;
  --text-subheading: 20px;
  --leading-subheading: 1.2;
  --tracking-subheading: -0.72px;
  --text-heading: 30px;
  --leading-heading: 1.35;
  --text-heading-lg: 36px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -2.628px;
  --text-display: 88px;
  --leading-display: 0.96;
  --tracking-display: -2.992px;
  --text-display-xl: 246px;
  --leading-display-xl: 1;
  --tracking-display-xl: -6.888px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-160: 160px;

  /* Border Radius */
  --radius-xl: 14px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-full: 80px;
  --radius-full-2: 110px;
  --radius-full-3: 128px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.12) -2px 3px 3px 0px;
}
```
