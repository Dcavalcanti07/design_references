# Getclockwise — Style Reference
> Evergreen clarity on a clean slate

**Theme:** light

Clockwise employs a crisp, professional visual system with a bright canvas and strong green branding. Text is highly structured, using a custom display font for headlines and a clear sans-serif for body content. Borders are prominent, acting as dividers and enclosures, while color accents are used sparingly for links and interactive elements, maintaining an airy yet authoritative feel.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas White | `#fdf9f7` | `--color-canvas-white` | Page background, primary surface for content blocks |
| Midnight Pine | `#003f2e` | `--color-midnight-pine` | Primary text, major headlines, brand elements, and prominent borders for content sections. Establishes a deep, grounded presence |
| Forest Link | `#039861` | `--color-forest-link` | Interactive text links, decorative accents, and outlines for ghost buttons or interactive states. A vivid green for functional highlights |
| Slate Text | `#333333` | `--color-slate-text` | Secondary text for paragraphs and descriptive content, offering strong contrast on light backgrounds |
| Ash Gray | `#6e7673` | `--color-ash-gray` | Muted text for subheadings and informational cues, borders for less prominent components |
| Steel Border | `#a6a6a6` | `--color-steel-border` | Hairline borders for dividers and subtle content segregation |
| Light Gray Border | `#d6d6d6` | `--color-light-gray-border` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |

## Tokens — Typography

### PP Mori — Display headlines and hero text. The condensed, strong presence of PP Mori at higher weights anchors the page and communicates authority. Its unique character distinguishes the brand's voice without being overly decorative. · `--font-pp-mori`
- **Substitute:** Montserrat
- **Weights:** 600, 700
- **Sizes:** 23px, 52px, 64px, 66px
- **Line height:** 0.95, 1.00, 1.10, 1.20
- **Role:** Display headlines and hero text. The condensed, strong presence of PP Mori at higher weights anchors the page and communicates authority. Its unique character distinguishes the brand's voice without being overly decorative.

### Inter — Primary text for body, links, lists, and secondary headings. Inter provides high legibility and a neutral, professional tone, complementing the distinctiveness of PP Mori without competing with it. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 700
- **Sizes:** 16px, 18px, 20px, 23px, 24px
- **Line height:** 1.30, 1.40
- **Letter spacing:** -0.0300em
- **Role:** Primary text for body, links, lists, and secondary headings. Inter provides high legibility and a neutral, professional tone, complementing the distinctiveness of PP Mori without competing with it.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body-sm | 16px | 1.4 | -0.48px | `--text-body-sm` |
| body | 18px | 1.4 | -0.54px | `--text-body` |
| subheading | 20px | 1.3 | -0.6px | `--text-subheading` |
| heading-sm | 23px | 1.2 | -0.69px | `--text-heading-sm` |
| heading | 52px | 1 | — | `--text-heading` |
| heading-lg | 64px | 0.95 | — | `--text-heading-lg` |
| display | 66px | 0.95 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 20 | 20px | `--spacing-20` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 180 | 180px | `--spacing-180` |

### Border Radius

| Element | Value |
|---------|-------|
| soft | 800px |
| circular | 9999px |

### Layout

- **Section gap:** 32px
- **Card padding:** 20px
- **Element gap:** 20px

## Components

### Primary Headline
**Role:** Dominant page titles and hero content.

Uses PP Mori, weight 700, size 66px, lineHeight 0.95, color Midnight Pine (#003f2e).

### Section Heading
**Role:** Titles for major content sections, establishing hierarchy.

Uses PP Mori, weight 600, size 52px, lineHeight 1.0, color Midnight Pine (#003f2e).

### Body Text Paragraph
**Role:** Standard paragraph content for readability.

Uses Inter, weight 400, size 18px, lineHeight 1.4, letterSpacing -0.0300em, color Slate Text (#333333).

### Muted Subheading
**Role:** Descriptive text under headlines or for secondary information.

Uses Inter, weight 400, size 20px, lineHeight 1.3, letterSpacing -0.0300em, color Ash Gray (#6e7673).

### Link Text
**Role:** Hyperlinks within body copy or navigation.

Uses Inter, weight 400, size 16px, lineHeight 1.4, letterSpacing -0.0300em, color Forest Link (#039861).

### FAQ Section Divider
**Role:** Visual separator for question groups in an FAQ.

A 3px solid border in Light Gray Border (#d6d6d6) spanning full width, positioned below a heading.

### FAQ Accordion Item
**Role:** Interactive question and answer section.

Clickable heading (Inter, weight 700, size 23px, color Midnight Pine #003f2e) with a circular '+' icon (color Forest Link #039861) on one side, and a 3px solid border in Light Gray Border (#d6d6d6) on the bottom.

### Stat Card
**Role:** Highlighting key numerical achievements.

Large number (PP Mori, weight 600, size 64px, color Midnight Pine #003f2e) with descriptive text below (Inter, weight 400, size 18px, color Ash Gray #6e7673, lineHeight 1.4). No explicit borders, relies on surrounding negative space.

## Do's and Don'ts

### Do
- Prioritize PP Mori for all headlines and display text, leveraging its strong character at larger sizes.
- Use Midnight Pine (#003f2e) for primary text content to maintain strong contrast and brand presence.
- Apply Forest Link (#039861) exclusively for active links and interactive elements, ensuring its vibrancy draws attention.
- Employ Light Gray Border (#d6d6d6) and Steel Border (#a6a6a6) for functional dividers and UI element outlines, using 3px solid for major sections and 1px solid for subtle distinctions.
- Maintain generous vertical spacing between sections (32px to 64px) to emphasize clarity and airiness.
- Utilize the `circular` (9999px) and `soft` (800px) radii for all interactive elements and badges, to convey a friendly tangibility.
- Ensure all body text uses Inter with -0.0300em letter spacing for enhanced readability on screen.

### Don't
- Avoid using saturated colors other than Forest Link (#039861) on interactive elements.
- Never use generic rectangular buttons; all buttons must adopt the `circular` (9999px) or `soft` (800px) radius.
- Do not introduce new serif fonts; the system relies on the distinct contrast between PP Mori and Inter.
- Avoid heavy drop shadows or complex gradients; the system prefers a flat, border-driven aesthetic.
- Do not deviate from the established text colors; use Midnight Pine (#003f2e), Slate Text (#333333), and Ash Gray (#6e7673) only for their designated roles.
- Refrain from using tight line spacing; maintain the established line heights (1.3-1.4) for all body copy to prevent text density.
- Do not use accent colors for large background areas; reserve them for small, functional UI elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#fdf9f7` | Primary background for the entire page, providing a spacious, light base. |

## Imagery

The site uses minimal imagery, primarily focusing on its logo and a grid of partner logos that are presented in a monochrome, desaturated style to maintain visual harmony. There are no full-bleed photographs or illustrations. Icons, like the plus/minus in the FAQ, are simple, outlined, and monochromatic, with a prominent stroke weight, and use the accent green for interactive states. The overall density of imagery is low, with text dominating the visual space and acting as the primary carrier of information.

## Layout

The page follows a classic max-width contained layout, likely centered, though specific max-width is not provided. The hero section presents a large, centered headline followed by a descriptive subtitle. Content is arranged in a single-column flow with consistent vertical spacing between paragraphs and sections. The FAQ section uses a clear question-and-answer format, bordered for distinction. Towards the bottom, there's a multi-column grid for partner logos, and a two-column grid for numerical stats, indicating a balanced use of white space and structured content blocks. The navigation is a simple top bar with a logo.

## Agent Prompt Guide

Create an Outlined Primary Action: Transparent background, #039861 border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.

Example Component Prompts:
Create a hero section: background Canvas White (#fdf9f7). Headline 'Our Next Chapter' using PP Mori weight 700, 66px, lineHeight 0.95, color Midnight Pine (#003f2e). Subtitle 'A new chapter for our team, and an important update for our customers.' using Inter weight 400, 20px, lineHeight 1.3, letter-spacing -0.6px, color Ash Gray (#6e7673).
Create an FAQ accordion item: Title 'How will the events on my calendar be impacted when the Clockwise services end?' using Inter weight 700, 23px, lineHeight 1.2, letter-spacing -0.69px, color Midnight Pine (#003f2e). Plus icon should be outlined, color Forest Link (#039861). Bottom border 3px solid Light Gray Border (#d6d6d6).
Create a stat card: Large number '8 million' using PP Mori weight 600, 64px, lineHeight 0.95, color Midnight Pine (#003f2e). Descriptive text 'hours of Focus Time created' using Inter weight 400, 18px, lineHeight 1.4, letter-spacing -0.54px, color Ash Gray (#6e7673).

## Similar Brands

- **Calendly** — Clean, calendar-focused, minimal color use with a dominant accent green for functionality.
- **Notion** — Strong emphasis on structured text, clear typography hierarchy, and subtle borders for content organization.
- **linear.app** — Highly structured information display, subtle use of branding colors for interactive elements, and a focus on content hierarchy over heavy visual design.
- **Superhuman** — Fast, UI-centric design with crisp typography and restrained color usage primarily for functional cues.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-white: #fdf9f7;
  --color-midnight-pine: #003f2e;
  --color-forest-link: #039861;
  --color-slate-text: #333333;
  --color-ash-gray: #6e7673;
  --color-steel-border: #a6a6a6;
  --color-light-gray-border: #d6d6d6;

  /* Typography — Font Families */
  --font-pp-mori: 'PP Mori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.48px;
  --text-body: 18px;
  --leading-body: 1.4;
  --tracking-body: -0.54px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.6px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.69px;
  --text-heading: 52px;
  --leading-heading: 1;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.95;
  --text-display: 66px;
  --leading-display: 0.95;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-180: 180px;

  /* Layout */
  --section-gap: 32px;
  --card-padding: 20px;
  --element-gap: 20px;

  /* Border Radius */
  --radius-full: 800px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-soft: 800px;
  --radius-circular: 9999px;

  /* Surfaces */
  --surface-canvas-white: #fdf9f7;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-white: #fdf9f7;
  --color-midnight-pine: #003f2e;
  --color-forest-link: #039861;
  --color-slate-text: #333333;
  --color-ash-gray: #6e7673;
  --color-steel-border: #a6a6a6;
  --color-light-gray-border: #d6d6d6;

  /* Typography */
  --font-pp-mori: 'PP Mori', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body-sm: 16px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: -0.48px;
  --text-body: 18px;
  --leading-body: 1.4;
  --tracking-body: -0.54px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.6px;
  --text-heading-sm: 23px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.69px;
  --text-heading: 52px;
  --leading-heading: 1;
  --text-heading-lg: 64px;
  --leading-heading-lg: 0.95;
  --text-display: 66px;
  --leading-display: 0.95;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-20: 20px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-180: 180px;

  /* Border Radius */
  --radius-full: 800px;
  --radius-full-2: 9999px;
}
```
