# Handshake — Style Reference
> Shifting gradient nebula

**Theme:** light

Handshake employs a dark, dynamic canvas lit by a vibrant, shifting gradient backdrop, creating a sense of energy and opportunity. Bold, blocky typography ensures high impact against this fluid background, while UI elements are purposefully minimal, often appearing as ghost outlines or subtle containers. The prominent use of a single vivid green accent ensures calls to action pop with urgency, contrasting sharply with the deep dark base.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Deep Space | `#000000` | `--color-deep-space` | Primary text, deep shadow, content background on footer, icon fill |
| Midnight Core | `#14151c` | `--color-midnight-core` | Placeholder text, subtle background for dark ghost buttons, input borders |
| Cosmic Gray | `#052326` | `--color-cosmic-gray` | Footer background |
| Stardust | `#ffffff` | `--color-stardust` | Heading text, body text, canvas for forms, ghost button backgrounds, input background |
| Guidepost Green | `radial-gradient(rgb(211, 251, 82) 0%, rgb(122, 243, 255) 52%, rgba(0, 0, 0, 0) 78%)` | `--color-guidepost-green` | Primary action background, active navigation indicator, sign-up button, decorative accents — a vibrant beacon against the dark UI; Hero background creating a dynamic, almost ethereal feel, blending blues and greens |
| Muted Text | `#666666` | `--color-muted-text` | Secondary body text, helper text |

## Tokens — Typography

### NoiGrotesk — All body text, navigation links, buttons, and most UI elements. Its slightly condensed feel at various weights maintains compactness. · `--font-noigrotesk`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px, 16px, 20px, 22px, 28px, 40px
- **Line height:** 0.85, 1.10, 1.40, 1.50
- **Letter spacing:** -0.0250em at large sizes, -0.0200em, -0.0150em at smaller sizes
- **OpenType features:** `"ss03" on, "ss06" on, "ss12" on`
- **Role:** All body text, navigation links, buttons, and most UI elements. Its slightly condensed feel at various weights maintains compactness.

### NoiGrotesk — Used for button labels, and emphasized text segments where a subtle increase in visual weight is needed without feeling heavy. · `--font-noigrotesk`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 12px, 14px, 16px, 20px, 22px, 28px, 40px
- **Line height:** 0.85, 1.10, 1.40, 1.50
- **Letter spacing:** -0.0250em at large sizes, -0.0200em, -0.0150em at smaller sizes
- **OpenType features:** `"ss03" on, "ss06" on, "ss12" on`
- **Role:** Used for button labels, and emphasized text segments where a subtle increase in visual weight is needed without feeling heavy.

### SansPlomb — Large display headings — the extreme size and tight letter spacing create a commanding, impactful presence that emphasizes the brand's bold statement. · `--font-sansplomb`
- **Substitute:** Anton
- **Weights:** 600
- **Sizes:** 201px
- **Line height:** 0.80
- **Letter spacing:** -0.0200em
- **Role:** Large display headings — the extreme size and tight letter spacing create a commanding, impactful presence that emphasizes the brand's bold statement.

### Arial — Arial — detected in extracted data but not described by AI · `--font-arial`
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.5
- **OpenType features:** `"ss03", "ss06", "ss12"`
- **Role:** Arial — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | — | `--text-caption` |
| body-sm | 14px | 1.4 | — | `--text-body-sm` |
| body | 16px | 1.4 | — | `--text-body` |
| subheading | 20px | 1.1 | — | `--text-subheading` |
| heading-sm | 22px | 1.1 | — | `--text-heading-sm` |
| heading | 28px | 1.1 | — | `--text-heading` |
| heading-lg | 40px | 0.85 | — | `--text-heading-lg` |
| display | 201px | 0.8 | -4.02px | `--text-display` |

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
| 64 | 64px | `--spacing-64` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 24px |
| inputs | 24px |
| buttons | 8px |
| buttons-large | 12px |
| navigationItems | 8px |

### Layout

- **Section gap:** 24px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Ghost Button
**Role:** Call to action variant

Ghost button with no background, 'Stardust' #ffffff text, and a 'Guidepost Green' #d3fb52 1px border, 8px radius, with 12px vertical and 16px horizontal padding. Prompts interaction without visual weight.

### Navigation Ghost Button
**Role:** Navigation and secondary actions

Ghost button with no background, 'Stardust' #ffffff text, and a 'Midnight Core' oklab(1 0 5.96046e-8 / 0.2) 1px border, 8px radius. Padding 16px all sides.

### Primary Filled Button
**Role:** High-priority, primary action.

Filled with 'Guidepost Green' #d3fb52, 'Stardust' #ffffff text, 8px radius, and 12px vertical, 16px horizontal padding. Used for the prominent 'Sign up' action.

### Filter Tag
**Role:** Interactive content categorization

Background oklab(0.19794 0.0021212 -0.0139539 / 0.1), 'Stardust' #ffffff text, with a 12px radius, and no explicit padding. Used for 'AI trainer', 'Full-time' etc.

### Search Input
**Role:** Primary form input for search queries.

Rounded input with 'Stardust' #ffffff background, 'Deep Space' #000000 text and placeholder, 'Midnight Core' #14151c 1px border, 24px radius. Left padding 64px to accommodate the search icon.

### Feature Card
**Role:** Content grouping for features or testimonials.

Background oklab(1 0 5.96046e-8 / 0.06), no shadow, and 24px border radius. Used for cards that group information.

## Do's and Don'ts

### Do
- Use 'Stardust' #ffffff for all primary text content and 'Deep Space' #000000 for secondary text and sub-headings to maximize contrast against the dynamic backgrounds.
- Apply 'Guidepost Green' #d3fb52 strictly for primary calls-to-action like 'Sign up' and navigational highlights to draw immediate attention. Do not use for generic elements.
- Maintain a clear visual hierarchy using the large SansPlomb 201px heading specifically for page and section titles, with its tight letter-spacing of -0.0200em for impact.
- Round all interactive elements like buttons and primary inputs with 8px uniform radius, and larger content blocks (cards, main inputs) with 24px radius, unless a pill shape (9999px) is used for tags.
- Implement the radial gradient backgrounds for hero sections or prominent content areas to provide a dynamic, branded visual anchor, ensuring the 'Nebula Gradation' blends from 'Guidepost Green' #d3fb52 to blue.
- Use the Base Unit 8px for all spacing decisions, creating consistent element gaps of 16px horizontally and vertically, and section gaps of 24px.
- Employ ghost button styles (no background, white text, defined border) for secondary actions like 'Log In', making the primary 'Sign up' button stand out distinctly.

### Don't
- Do not introduce new vibrant colors outside of the 'Guidepost Green' #d3fb52 accent, or the blue component of the 'Nebula Gradation', to avoid diluting the brand's energetic yet focused palette.
- Avoid generic box shadows or heavy borders on background elements; components should breathe and appear lightweight against the fluid gradient.
- Do not deviate from the specified typefaces, especially SansPlomb for large headlines, as its distinct letter spacing and weight are critical for brand identity.
- Do not use subtle neutrals for critical calls-to-action; 'Guidepost Green' #d3fb52 is reserved for this purpose.
- Avoid excessive text density or complex multi-column layouts, sticking to a comfortable density with clear vertical rhythm and ample breathing room between elements.
- Do not create completely flat design elements. Even ghost buttons and inputs should retain a subtle border or background transparency as defined.
- Do not use generic system fonts for body or UI text; NoiGrotesk with its feature settings is fundamental to the brand's typographic tone.

## Imagery

The site uses minimal imagery, primarily focusing on abstract, atmospheric radial gradients as backgrounds. There are no photographs or complex illustrations. Icons are simple, outlined, and monochromatic, primarily using 'Stardust' #ffffff or 'Deep Space' #000000, serving purely functional roles like search or navigation prompts rather than decorative ones.

## Layout

The page structure is full-bleed, with content centered but not strictly constrained by a fixed max-width, allowing the background gradients to stretch across the viewport. The hero section is characterized by a central, bold headline over a gradient background, followed by an input field. Sections are distinct but flow seamlessly, often with ample vertical spacing. Content is generally stacked centrally or in simple text-right/image-left type patterns, ensuring focus on typography and the dynamic backdrop. Navigation is a sticky top bar with ghost controls, and a prominent green primary action button.

## Agent Prompt Guide

**Quick Color Reference**
text: #ffffff
background: #000000
border: #14151c
accent: #d3fb52
primary action: #d3fb52 (filled action)

**3-5 Example Component Prompts**
1. Create a Hero Section: Background is 'Nebula Gradation' #d3fb52 radial gradient. Primary headline "LET'S FIND YOUR NEXT JOB" using SansPlomb 201px, weight 600, #ffffff, letter-spacing -4.02px, centered. Subtext "1M+ companies ready to hire. 500+ AI gigs open for you." using NoiGrotesk 28px, weight 400, #ffffff. Centered search input component.
2. Create a Search Input Field: With 'Stardust' #ffffff background, 'Midnight Core' #14151c 1px border, 24px radius, left padding 64px. Placeholder text "AI trainer roles focused on data" in 'Deep Space' #000000 with NoiGrotesk 16px, weight 400. Include a simple outlined search icon.
3. Create a Primary Action Button: #d3fb52 background, #000000 text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.
4. Create a Ghost Navigation Link: "Log in" with no background, 'Stardust' #ffffff text using NoiGrotesk 16px, weight 400, and a 1px border of 'Midnight Core' #14151c, 8px radius, 16px padding on all sides.
5. Create a Filter Tag: "AI trainer" with background oklab(0.19794 0.0021212 -0.0139539 / 0.1), 'Stardust' #ffffff text using NoiGrotesk 14px, weight 400, and a 12px radius, no padding.

## Similar Brands

- **Rive** — Dynamic, vibrant gradient backgrounds with bold typography and minimal, ghost-like UI elements.
- **Pitch** — Prominent use of a single, vivid accent color against a dark or mostly neutral UI, paired with impactful display typography.
- **Linear** — Emphasis on functional, lightweight UI components, often with subtle borders or transparent backgrounds, against a generally dark theme.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-deep-space: #000000;
  --color-midnight-core: #14151c;
  --color-cosmic-gray: #052326;
  --color-stardust: #ffffff;
  --color-guidepost-green: #d3fb52;
  --gradient-guidepost-green: radial-gradient(rgb(211, 251, 82) 0%, rgb(122, 243, 255) 52%, rgba(0, 0, 0, 0) 78%);
  --color-muted-text: #666666;

  /* Typography — Font Families */
  --font-noigrotesk: 'NoiGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sansplomb: 'SansPlomb', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.1;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --text-heading-lg: 40px;
  --leading-heading-lg: 0.85;
  --text-display: 201px;
  --leading-display: 0.8;
  --tracking-display: -4.02px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 24px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 24px;
  --radius-inputs: 24px;
  --radius-buttons: 8px;
  --radius-buttons-large: 12px;
  --radius-navigationitems: 8px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-deep-space: #000000;
  --color-midnight-core: #14151c;
  --color-cosmic-gray: #052326;
  --color-stardust: #ffffff;
  --color-guidepost-green: #d3fb52;
  --color-muted-text: #666666;

  /* Typography */
  --font-noigrotesk: 'NoiGrotesk', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-sansplomb: 'SansPlomb', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --text-body: 16px;
  --leading-body: 1.4;
  --text-subheading: 20px;
  --leading-subheading: 1.1;
  --text-heading-sm: 22px;
  --leading-heading-sm: 1.1;
  --text-heading: 28px;
  --leading-heading: 1.1;
  --text-heading-lg: 40px;
  --leading-heading-lg: 0.85;
  --text-display: 201px;
  --leading-display: 0.8;
  --tracking-display: -4.02px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-64: 64px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;
}
```
