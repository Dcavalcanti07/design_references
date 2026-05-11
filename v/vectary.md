# Vectary — Style Reference
> Digital Blueprint on Whiteboard. The crisp contrast and precise typography against a clean white background feel like technical specifications brought to life with minimal flourish.

**Theme:** light

This design evokes a feeling of structured clarity and restrained energy. The almost monochromatic palette, dominated by deep grays and stark white, creates a serious and direct atmosphere. A single vivid violet accent color, used sparingly, cuts through the neutrality, acting as a precise digital highlight. Sharp corners prevail, reinforcing a sense of precision and modern utility, with only minor softening for interactive elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Graphite | `#252525` | `--color-midnight-graphite` | Primary text, deep backgrounds for accented components, button backgrounds, borders — anchors the design with a grounded, serious tone. |
| Deep Slate | `#313131` | `--color-deep-slate` | Navigation bar background, dark surface elements — provides a subtle depth variation from Midnight Graphite. |
| Midtone Gray | `#595959` | `--color-midtone-gray` | Body text, secondary headings — provides contrast for extensive reading while maintaining a serious tone. |
| Muted Silver | `#949494` | `--color-muted-silver` | Subtle text, inactive elements, fine borders — allows information to recede without disappearing. |
| Alabaster White | `#ffffff` | `--color-alabaster-white` | Page backgrounds, primary container backgrounds, text on dark elements — provides a clean, expansive canvas. |
| Vectary Violet | `#6100ff` | `--color-vectary-violet` | Primary Call-to-Action button background, active state indicators — a vivid, high-energy accent that signals interaction and brand identity. |
| Violet Gradient | `linear-gradient(129deg, rgb(97, 0, 255), rgb(157, 80, 255))` | `--color-violet-gradient` | Distinctive brand element, likely for hero sections or specific promotional areas; creates an energetic focal point where applied. |

## Tokens — Typography

### Inter — The primary typeface for all textual content. Its variable weight functionality and precisely tracked letter spacing, particularly for larger sizes, provide a modern, highly legible feel. Heaviest weights (900) are reserved for impactful headlines, while 400 is used for readable body copy. Negative letter-spacing in headings creates a tight, composed visual. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700, 900
- **Sizes:** 14px, 16px, 18px, 22px, 26px, 83px
- **Line height:** 1.00, 1.09, 1.30, 1.40, 1.50, 1.69
- **Letter spacing:** -0.012em, -0.019em, -0.025em, -0.030em, -0.034em, -0.039em
- **Role:** The primary typeface for all textual content. Its variable weight functionality and precisely tracked letter spacing, particularly for larger sizes, provide a modern, highly legible feel. Heaviest weights (900) are reserved for impactful headlines, while 400 is used for readable body copy. Negative letter-spacing in headings creates a tight, composed visual.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.69 | -0.48px | `--text-caption` |
| body | 16px | 1.5 | -0.3px | `--text-body` |
| subheading | 18px | 1.4 | -0.45px | `--text-subheading` |
| heading-sm | 22px | 1.3 | -0.66px | `--text-heading-sm` |
| heading | 26px | 1.09 | -0.88px | `--text-heading` |
| display | 83px | 1 | -3.24px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 6 | 6px | `--spacing-6` |
| 9 | 9px | `--spacing-9` |
| 10 | 10px | `--spacing-10` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 53 | 53px | `--spacing-53` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 8px |
| default | 8px |
| navigation | 0px |

### Layout

- **Section gap:** 60px
- **Card padding:** 30px
- **Element gap:** 6px

## Components

### Primary Navigation Link
**Role:** Navigation, header

Text link with padding of 30px top and bottom, 0px left and right. Text color is Midnight Graphite (#252525) and font weight 400. No border or background unless active.

### Section Heading (Large)
**Role:** Primary page title

Display font size 83px, weight 900, color Midnight Graphite (#252525), line height 1.0, letter spacing -0.039em. Used for main page titles.

### Section Heading (Medium)
**Role:** Section title

Heading font size 26px, weight 700, color Midnight Graphite (#252525), line height 1.09, letter spacing -0.034em. Used for primary content sections.

### Body Text Paragraph
**Role:** Standard content

Body font size 16px, weight 400, color Midtone Gray (#595959), line height 1.5, letter spacing -0.019em. Used for general body copy, providing readability.

### Bullet Point Item
**Role:** Lists and details

Body font size 16px, weight 400, color Midtone Gray (#595959), line height 1.5, letter spacing -0.019em, with a 20px left margin for the bullet point.

### Timestamp Text
**Role:** Metadata

Body font size 16px, weight 400, color Muted Silver (#949494), line height 1.5, letter spacing -0.019em. Used for dates and other secondary information, indicating passage of time or less emphasis.

## Do's and Don'ts

### Do
- Prioritize Alabaster White (#ffffff) for all main page backgrounds to maintain visual spaciousness.
- Use Midnight Graphite (#252525) for all primary text elements, including large headings and bolded content.
- Apply Vectary Violet (#6100ff) exclusively for primary interactive elements, such as CTA buttons, to maximize its impact.
- Ensure all headings use Inter font with appropriate negative letter spacing: '-0.039em' for 83px, '-0.034em' for 26px, and '-0.030em' for 22px.
- Maintain 8px radius for all buttons that are not purely navigation links.
- Utilize a base unit of 6px for managing vertical and horizontal spacing, resulting in 6px, 9px, 10px, 16px, 20px, 30px, 53px, and 60px increments.
- Employ Midtone Gray (#595959) for body text and Muted Silver (#949494) for less emphasized text like timestamps or secondary links to create clear information hierarchy.

### Don't
- Avoid using multiple chromatic colors; limit accents strictly to Vectary Violet (#6100ff) and its gradient variant.
- Do not use dark backgrounds for entire sections unless it's a specific brand feature or navigation bar; reserve Alabaster White for overall page content.
- Do not introduce additional border radii beyond 8px for buttons and elements, or 0px for navigation items.
- Avoid generic system fonts; always specify Inter with its defined weights and letter spacing for all text.
- Do not use box shadows or other elevation effects; rely on color and spacing hierarchy to convey depth.
- Do not deviate from the defined spacing tokens; avoid arbitrary padding or margins.
- Never use bold (weight 700) for body text; reserve it for headings or specific emphasis points to maintain visual clarity.

## Imagery

This site features a clean, professional aesthetic with a strong focus on UI and typography over illustrative or photographic content. Graphics are minimal, primarily consisting of icons (not directly visible in the screenshots but implied by component data) that are likely outlined or filled in a monochromatic style. There is an absence of lifestyle photography, complex illustrations, or 3D renders. The visual language emphasizes clarity and straightforward presentation, relying on crisp lines and precise spacing rather than decorative imagery. When imagery is present, it is likely contained and supportive of the UI, rather than a dominant visual element.

## Layout

The page adheres to a maximal width layout, though a `pageMaxWidth` isn't strictly defined, hinting at a flexible container centered on larger screens. The hero section is a full-width header composed of a centered logo and right-aligned navigation. Content sections are vertical stacks, using generous top/bottom padding (60px) to separate them. Text content is primarily left-aligned, with headings followed by body paragraphs and bulleted lists. The overall impression is one of structured, information-dense content presented in a clean, scrollable format, with a notable lack of complex grid patterns or alternating content blocks.

## Agent Prompt Guide

### Quick Color Reference
- Text: #252525 (Midnight Graphite)
- Background: #ffffff (Alabaster White)
- CTA: #6100ff (Vectary Violet)
- Border: #949494 (Muted Silver)
- Secondary Text: #595959 (Midtone Gray)

### Example Component Prompts
1. Create a large page title: 'Acceptable Use Policy' with Inter, weight 900, 83px, line height 1.0, letter spacing -3.24px, color #252525.
2. Design a primary navigation button: 'Login' with an 8px radius, background #252525, text #ffffff, and 30px padding on top/bottom, 16px left/right (implied from other buttons, assuming horizontal). Text should be Inter, weight 400, 16px, line height 1.5, letter spacing -0.3px.
3. Implement a section heading: '1. Intended Purpose of AI Features' with Inter, weight 700, 26px, line height 1.09, letter spacing -0.88px, color #252525. Ensure 60px spacing above it.
4. Create a standard body paragraph: 'This Acceptable Use Policy...' with Inter, weight 400, 16px, line height 1.5, letter spacing -0.3px, color #595959. Add a 10px top margin after a heading.
5. Build a bulleted list item: '• Enabling surveillance...' using Inter, weight 400, 16px, line height 1.5, letter spacing -0.3px, color #595959, with a 20px left margin for the bullet.

## Similar Brands

- **Figma** — Clean, predominantly light interface with strong typography and minimal, precise use of accent colors for interactive elements.
- **Notion** — Information-heavy pages with strong emphasis on readable text hierarchies, simple layout, and an almost achromatic base with sparing colorful accents.
- **Stripe (docs)** — Technical documentation style with clear typography, high contrast, and a professional, uncluttered presentation.
- **Linear** — Slightly dark-tinted neutrals, strong typographic emphasis, and a single, vibrant accent color to highlight key interactive elements against a clean backdrop.
- **Vercel** — Development tool aesthetic with a focus on dark, crisp text against clean backgrounds and very minimal, impactful use of a single accent color.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-graphite: #252525;
  --color-deep-slate: #313131;
  --color-midtone-gray: #595959;
  --color-muted-silver: #949494;
  --color-alabaster-white: #ffffff;
  --color-vectary-violet: #6100ff;
  --color-violet-gradient: #6100ff;
  --gradient-violet-gradient: linear-gradient(129deg, rgb(97, 0, 255), rgb(157, 80, 255));

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.69;
  --tracking-caption: -0.48px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.3px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.45px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.66px;
  --text-heading: 26px;
  --leading-heading: 1.09;
  --tracking-heading: -0.88px;
  --text-display: 83px;
  --leading-display: 1;
  --tracking-display: -3.24px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-black: 900;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-53: 53px;
  --spacing-60: 60px;

  /* Layout */
  --section-gap: 60px;
  --card-padding: 30px;
  --element-gap: 6px;

  /* Border Radius */
  --radius-lg: 8px;

  /* Named Radii */
  --radius-buttons: 8px;
  --radius-default: 8px;
  --radius-navigation: 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-graphite: #252525;
  --color-deep-slate: #313131;
  --color-midtone-gray: #595959;
  --color-muted-silver: #949494;
  --color-alabaster-white: #ffffff;
  --color-vectary-violet: #6100ff;
  --color-violet-gradient: #6100ff;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.69;
  --tracking-caption: -0.48px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.3px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.45px;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.3;
  --tracking-heading-sm: -0.66px;
  --text-heading: 26px;
  --leading-heading: 1.09;
  --tracking-heading: -0.88px;
  --text-display: 83px;
  --leading-display: 1;
  --tracking-display: -3.24px;

  /* Spacing */
  --spacing-6: 6px;
  --spacing-9: 9px;
  --spacing-10: 10px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-53: 53px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-lg: 8px;
}
```
