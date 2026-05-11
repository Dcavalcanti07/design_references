# Reclaim — Style Reference
> Vibrant AI workspace

**Theme:** light

This design orchestrates a friendly yet authoritative presentation through vibrant accents against a clean, spacious white backdrop. Key information is spotlighted with bold headings and a signature electric violet, while supporting details use muted tones. The frequent use of rounded corners, especially 100px pill shapes, softens the otherwise structured content, creating an approachable and modern feel for an AI-driven tool.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White | `#ffffff` | `--color-white` | Page backgrounds, card surfaces, primary text on dark accents. |
| Charcoal | `#2b2b2b` | `--color-charcoal` | Primary body text, standard headings. |
| Graphite | `#474747` | `--color-graphite` | Secondary text, descriptive elements. |
| Light Steel | `#c2c4d0` | `--color-light-steel` | Subtle borders, dividers, ghost button outlines. |
| Electric Violet | `#5562eb` | `--color-electric-violet` | Primary interactive elements like CTA buttons, links, and key highlights — creating an energetic focal point. |
| AI Green | `#7ac17b` | `--color-ai-green` | Used for success states, value propositions, and numerical highlights, signifying positive outcomes. |
| Zenith Gradient | `linear-gradient(120deg, rgb(85, 98, 235) 40%, rgb(122, 193, 123) 61%)` | `--color-zenith-gradient` | Accents for section backgrounds or graphical elements, symbolizing a blend of progress and clarity. |
| Growth Gradient | `linear-gradient(90deg, rgb(122, 193, 123), rgb(85, 98, 235))` | `--color-growth-gradient` | Visual emphasis on statistics and features, conveying forward motion. |

## Tokens — Typography

### Poppins — Headings, primary body text, buttons, and most UI elements. Its consistent, slightly condensed form with light letter spacing provides a modern, clean textual presence. · `--font-poppins`
- **Substitute:** system-ui
- **Weights:** 300, 400, 500, 600, 700
- **Sizes:** all
- **Line height:** all
- **Letter spacing:** -0.01em
- **Role:** Headings, primary body text, buttons, and most UI elements. Its consistent, slightly condensed form with light letter spacing provides a modern, clean textual presence.

### Inter — Used sparingly for secondary information and card details, offering a slightly more utilitarian contrast to the prominent Poppins. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 18px
- **Line height:** all
- **Letter spacing:** normal
- **Role:** Used sparingly for secondary information and card details, offering a slightly more utilitarian contrast to the prominent Poppins.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 16px | 1.5 | -0.16px | `--text-body` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading | 24px | 1.25 | -0.24px | `--text-heading` |
| heading-lg | 40px | 1.18 | -0.4px | `--text-heading-lg` |
| display | 70px | 1.05 | -0.7px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 26 | 26px | `--spacing-26` |
| 30 | 30px | `--spacing-30` |
| 35 | 35px | `--spacing-35` |
| 40 | 40px | `--spacing-40` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 100 | 100px | `--spacing-100` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| buttons | 100px |
| default | 10px |

### Layout

- **Section gap:** 40-70px
- **Card padding:** 20-30px
- **Element gap:** 5-15px

## Components

### Primary Pill Button
**Role:** Primary call to action.

backgroundColor: #5562eb, color: #ffffff, borderRadius: 100px, paddingTop/Bottom: 15px, paddingLeft/Right: 30px, font: Poppins weight 500 equivalent to 16px.

### Secondary Outline Button
**Role:** Secondary call to action.

backgroundColor: #ffffff, color: #000000, border: 1px solid #c2caf9, borderRadius: 0px, paddingTop/Bottom: 0px, paddingLeft/Right: 30px, font: Poppins weight 500 equivalent to 16px. Height defined by 0px padding is a specific implementation detail.

### Ghost Header Button
**Role:** Navigation or tertiary actions in headers.

backgroundColor: transparent, color: #2b2b2b, no border, borderRadius: 0px, paddingTop/Bottom: 26px, paddingLeft/Right: 0px, font: Poppins weight 500 equivalent to 16px.

### Dark Square Button
**Role:** Secondary navigation or actions, offering higher contrast.

backgroundColor: #000000, color: #ffffff, borderRadius: 3px, paddingTop/Bottom: 15px, paddingLeft/Right: 30px, font: Poppins weight 500 equivalent to 16px.

### Feature Card
**Role:** Highlighting product features or benefits.

backgroundColor: transparent, borderRadius: 0px, boxShadow: none, paddingTop/Bottom: 0px, paddingLeft/Right: 20px. Content is meant to drive impact without visual framing.

### Product Insight Card
**Role:** Displaying key statistics or quotes.

backgroundColor: #ffffff, borderRadius: 0px, boxShadow: none, paddingTop/Bottom/Left/Right: 30px. Used for content blocks that need a clean white background.

### Accent Tag
**Role:** Categorization or small interactive labels.

backgroundColor: transparent, color: #181d25, borderRadius: 0px, padding: 0px. Text-only tag for unobtrusive labeling.

### Impact Statistic
**Role:** Presenting key performance indicators with visual hierarchy.

Large numerical value (e.g., '4.8h') in AI Green #7ac17b, Poppins Bold. Followed by descriptive text in Charcoal #2b2b2b, smaller Poppins regular. Overall composition for high readability and immediate impact.

## Do's and Don'ts

### Do
- Always use Poppins for display headings and primary text, leveraging its -0.01em letterSpacing for a sophisticated feel.
- Apply Electric Violet (#5562eb) exclusively for primary interactive elements, such as main CTA buttons and navigation links.
- Utilize 100px border-radius for all primary buttons and image masks to maintain a consistent soft, modern touch.
- Pair AI Green (#7ac17b) with Poppins Bold for all numerical statistics or positive affirmations.
- Maintain generous vertical spacing between sections to ensure content breathe and visual comfort.
- Use Charcoal (#2b2b2b) for general paragraph text and secondary headings for clear readability against a white background.

### Don't
- Do not use box shadows for content cards; rely on background color changes for hierarchy when needed.
- Avoid using multiple chromatic colors for primary calls to action; reserve Electric Violet (#5562eb) for this role.
- Do not use Poppins with default letter-spacing; ensure -0.01em is applied for the consistent brand typography.
- Do not introduce square buttons unless for specific dark background contexts (like the Get Started button in the header) to avoid inconsistency with the dominant pill style.
- Do not use dark backgrounds for sections unless explicitly defined with gradient fills or for specific hero moments.
- Avoid arbitrary border-radii; stick to 0px, 10px, or 100px for consistency.

## Imagery

The site uses a combination of abstract graphics and product screenshots. Product imagery features tight crops of the Reclaim UI, often presented on a clean white background with a subtle, friendly purple-tinted shadow like #ebefff. These screenshots are typically contained rather than full-bleed, showcasing the application's functionality. Icons are primarily outlined or subtle filled, using either dark neutrals or brand colors like AI Green, maintaining a clean, technical aesthetic. There are no lifestyle photos.

## Layout

The layout is predominantly max-width contained, centered on the page, with a pageMaxWidth implicitly around 1200px based on visual density. The hero section features a left-aligned, prominent headline over a white background, balanced by a large product screenshot on the right. Subsequent sections alternate between centered content stacks for testimonials or statistics and two-column layouts featuring text on the left and a product graphic or illustration on the right. There's a consistent vertical rhythm from varied margin-bottoms, leading to a comfortable density. The navigation is a sticky top bar with a logo, text links, and prominent pill-shaped buttons for CTAs.

## Agent Prompt Guide

### Quick Color Reference
- Text (Charcoal): #2b2b2b
- Background (White): #ffffff
- CTA (Electric Violet): #5562eb
- Border (Light Steel): #c2c4d0
- Accent (AI Green): #7ac17b

### 3-5 Example Component Prompts
1. Create a hero section: white background. Headline '#1 AI calendar app for work.' using Poppins 70px weight 700 letter-spacing -0.7px #2b2b2b. Subtext 'AI that schedules work, meetings, and life – automatically.' using Poppins 18px weight 400 #474747. Primary button 'Get started free!' with backgroundColor #5562eb, color #ffffff, borderRadius 100px, padding 15px 30px, font Poppins 16px weight 500.
2. Design a statistics section: background white. Display a statistic '4.8h' using Poppins 40px weight 700 color #7ac17b. Below it, add descriptive text 'more focus time/week' using Poppins 16px weight 400 color #2b2b2b. Duplicate this pattern for a 4-column layout.
3. Create a secondary navigation link: 'Book a Demo' with backgroundColor #ffffff, color #000000, border 1px solid #c2caf9, borderRadius 0px, padding 0px 30px, font Poppins 16px weight 500.

## Similar Brands

- **Calendly** — Dominant white background with product screenshots and bright accent colors for CTAs.
- **Asana** — Clean, spacious UI with strong typography and a clear distinction between neutral content and brand-colored interactive elements.
- **Notion** — Minimalist aesthetic, focus on content clarity, and use of subtle neutral elements with occasional brand color pops.
- **Linear** — Modern and functional feel with strong emphasis on type hierarchy and a limited, purposeful color palette for UI elements.
- **ClickUp** — Bright, friendly colors used as accents and for primary calls-to-action against a primarily white, spacious background.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white: #ffffff;
  --color-charcoal: #2b2b2b;
  --color-graphite: #474747;
  --color-light-steel: #c2c4d0;
  --color-electric-violet: #5562eb;
  --color-ai-green: #7ac17b;
  --color-zenith-gradient: #5562eb;
  --gradient-zenith-gradient: linear-gradient(120deg, rgb(85, 98, 235) 40%, rgb(122, 193, 123) 61%);
  --color-growth-gradient: #7ac17b;
  --gradient-growth-gradient: linear-gradient(90deg, rgb(122, 193, 123), rgb(85, 98, 235));

  /* Typography — Font Families */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.24px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.18;
  --tracking-heading-lg: -0.4px;
  --text-display: 70px;
  --leading-display: 1.05;
  --tracking-display: -0.7px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Layout */
  --section-gap: 40-70px;
  --card-padding: 20-30px;
  --element-gap: 5-15px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 10px;
  --radius-full: 100px;
  --radius-full-2: 200px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-buttons: 100px;
  --radius-default: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white: #ffffff;
  --color-charcoal: #2b2b2b;
  --color-graphite: #474747;
  --color-light-steel: #c2c4d0;
  --color-electric-violet: #5562eb;
  --color-ai-green: #7ac17b;
  --color-zenith-gradient: #5562eb;
  --color-growth-gradient: #7ac17b;

  /* Typography */
  --font-poppins: 'Poppins', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.16px;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --tracking-heading: -0.24px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.18;
  --tracking-heading-lg: -0.4px;
  --text-display: 70px;
  --leading-display: 1.05;
  --tracking-display: -0.7px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-26: 26px;
  --spacing-30: 30px;
  --spacing-35: 35px;
  --spacing-40: 40px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-100: 100px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-lg: 10px;
  --radius-full: 100px;
  --radius-full-2: 200px;
}
```
