# Ghost — Style Reference
> Crisp Blueprint on White Canvas. Black text etched onto a pristine white background, punctuated by a vibrant lime green flourish.

**Theme:** light

This design system grounds a clean, light interface with judicious dark elements, creating a sense of professional authority. A stark contrast between near-black text and a bright white background establishes immediate readability, while subtle, desaturated grays provide tiered information. The vivid lime green is reserved for primary calls to action, standing out against the neutral palette like a beacon. The interplay of sharp, functional typography with soft, rounded elements, especially in buttons, creates a balanced, approachable feel without sacrificing precision.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| White Canvas | `#ffffff` | `--color-white-canvas` | Page backgrounds, card surfaces, pristine backdrops for content. |
| Midnight Ink | `#000000` | `--color-midnight-ink` | Primary text across light backgrounds, creating strong contrast for headlines and body content. |
| Carbon Black | `#15171a` | `--color-carbon-black` | Background for deeply embedded components, like the main UI elements shown in the dashboard example, acting as a secondary, darker surface. |
| Slate Blue | `#94a3b8` | `--color-slate-blue` | Secondary text, link hovers, subtle borders, and placeholder text, providing visual hierarchy without harshness. |
| Graphite | `#334155` | `--color-graphite` | Tertiary text, less prominent UI elements, and occasional darker backgrounds for specific content blocks. |
| Ash Gray | `#e5e7eb` | `--color-ash-gray` | Subtle borders, dividers, subtle button backgrounds, and UI element outlines, providing structure without distraction. |
| Light Steel | `#cbd5e1` | `--color-light-steel` | Iconography and less prominent textual elements, contributing to the system's light aesthetic. |
| Dark Steel | `#112220` | `--color-dark-steel` | Prominent headings and critical interface labels within darker sections, almost black but with a very subtle green undertone. |
| Ghost Gray | `#0f172a` | `--color-ghost-gray` | Darker component backgrounds, especially in the featured UI example, providing depth to the otherwise light theme. |
| Ghost Border | `#1f2937` | `--color-ghost-border` | Darker borders and separators, primarily used within the embedded dark UI, providing definition to interactive elements. |
| Vivid Lime | `#d1ff19` | `--color-vivid-lime` | Primary call-to-action buttons and key interactive elements, drawing immediate attention with its high contrast. |
| Muted Lime | `#bef264` | `--color-muted-lime` | Subtle hover states or secondary interactive elements, a softer tone of the brand's primary accent. |
| Forest Green | `#1a2e05` | `--color-forest-green` | Background for secondary action buttons, providing a more subdued but still on-brand interactive element. |
| Sky Blue | `#1bb6eb` | `--color-sky-blue` | Accent color for specific interactive components, like the 'Get Started — free' secondary button, offering a crisp alternative to lime. |
| Neon Pink | `#f8b1e2` | `--color-neon-pink` | Decorative elements or indicators within the embedded dark UI, providing a vibrant, almost electric pop against dark backgrounds. |

## Tokens — Typography

### InterVariable — Body copy, button labels, navigation links, and descriptive text. Its versatility ensures readability across various functional elements. · `--font-intervariable`
- **Substitute:** Inter
- **Weights:** 400, 500, 600
- **Sizes:** 12px, 14px, 15px
- **Line height:** 1.25, 1.50
- **Letter spacing:** normal
- **OpenType features:** `"calt", "cv10", "cv11", "liga", "ss01", "ss03"`
- **Role:** Body copy, button labels, navigation links, and descriptive text. Its versatility ensures readability across various functional elements.

### InterDisplay — Headlines, section titles, and prominent calls-to-action. The tighter line height and varied letter spacing create a precise, impactful display type. The range of weights allows for a nuanced hierarchy, from assertive headings to more understated but still prominent display text. · `--font-interdisplay`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 15px, 18px, 20px, 24px, 36px, 48px, 72px, 96px
- **Line height:** 0.90, 1.00, 1.15, 1.25, 1.35, 1.50
- **Letter spacing:** -0.025em at 48px to 0.100em at 12px
- **OpenType features:** `"calt", "cv10", "cv11", "liga", "ss01", "ss03"`
- **Role:** Headlines, section titles, and prominent calls-to-action. The tighter line height and varied letter spacing create a precise, impactful display type. The range of weights allows for a nuanced hierarchy, from assertive headings to more understated but still prominent display text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 14px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.25 | — | `--text-subheading` |
| heading | 24px | 1.25 | — | `--text-heading` |
| heading-lg | 36px | 1.15 | — | `--text-heading-lg` |
| display | 48px | 1 | -0.48px | `--text-display` |
| display-lg | 72px | 0.9 | — | `--text-display-lg` |
| display-xl | 96px | 0.9 | — | `--text-display-xl` |

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
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 8px |
| input | 6px |
| buttons | 24px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, rgba(0, 0, 0, 0.03) 0...` | `--shadow-subtle` |
| sm | `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0...` | `--shadow-sm` |
| md | `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1)...` | `--shadow-md` |
| xl | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px` | `--shadow-xl-2` |

### Layout

- **Page max-width:** 1200px
- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 16px

## Components

### Primary Call-to-action Button
**Role:** Main interactive element

Filled with Forest Green (#1a2e05), text in Muted Lime (#bef264), 8px border-radius, 8px vertical padding, 16px horizontal padding. Delivers a bold, on-brand interactive experience.

### Secondary Outline Button
**Role:** Subtle interactive element

Transparent background, text in #4d4d4d, 6px border-radius, 0px vertical and horizontal padding. Used for less prominent calls to action or navigation. Subtle shadows indicate interactability.

### Solid Dark Button
**Role:** Tertiary action, often within dark contexts

Filled with Carbon Black (#15171a), text in White Canvas (#ffffff), 6px border-radius, 8px vertical padding, 16px horizontal padding. Provides a clear action point on lighter backgrounds.

### Sky Blue Pill Button
**Role:** Prominent secondary action for specific features

Filled with Sky Blue (#1bb6eb), text in Midnight Ink (#000000), 24px border-radius, 12px vertical and horizontal padding. Its distinct color and shape highlight special offers or actions.

### Informational Badge
**Role:** Contextual labels or status indicators

Pill-shaped with a 9999px border-radius. Example: 'Just launched: Ghost 6.0 →' badge with Vivid Lime (#d1ff19) background and Midnight Ink (#000000) text, 8px padding.

### Feature Card
**Role:** Content container for features or services

White Canvas (#ffffff) background, 8px border-radius, subtle shadow rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, 24px internal padding. Contains images, headlines, and body text.

### Navigation Link
**Role:** Primary site navigation

Midnight Ink (#000000) text (InterVariable, weight 400, 15px), 0px padding, no background. Hover states are implied to change text color to Slate Blue (#94a3b8) or similar subtle shift.

### Dashboard UI Panel
**Role:** Embedded complex interface element

Ghost Gray (#0f172a) background, with Ghost Border (#1f2937) for internal divisions. Text in Midnight Ink or appropriate neutrals. Features intricate data visualization and functional navigation within.

## Do's and Don'ts

### Do
- Use Midnight Ink (#000000) for all primary body and headline text on White Canvas (#ffffff) backgrounds to ensure maximum contrast (21.0:1 AAA).
- Apply Vivid Lime (#d1ff19) exclusively for primary calls-to-action and key indicators, reserving its high visual impact.
- Maintain the 24px border-radius for all primary buttons and significant interactive elements for a consistent soft-edged aesthetic.
- Utilize InterDisplay for headlines at sizes 36px and above, with letter-spacing adjusted between -0.025em and normal for optimal legibility.
- Ensure a minimum vertical spacing of 24px between content blocks and 16px for element gaps to maintain a comfortable density.
- Employ the rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, rgba(0, 0, 0, 0.03) 0px 2px 6px 0px shadow for interactive cards and buttons to provide subtle depth.

### Don't
- Do not use highly saturated colors for large areas or non-interactive elements; colors beyond the defined brand/accent palette will appear off-brand.
- Avoid deviating from the defined InterVariable and InterDisplay font families; no other fonts should be introduced.
- Refrain from using shadows or borders that are more pronounced than those defined (e.g., rgba(0, 0, 0, 0.25) 0px 25px 50px -12px is reserved for highly elevated, transient elements like modals or dropdowns).
- Do not mix border-radius values indiscriminately; stick to 24px for buttons, 8px for cards, and 9999px for pill-shaped elements.
- Do not use generic gray values; always refer to the specific neutral palette (Slate Blue, Graphite, Ash Gray, Light Steel, Dark Steel, Ghost Gray) to maintain subtle chromatic tint and consistency.
- Do not use a line height greater than 1.5 for any text block, as this design favors a compact, focused presentation.

## Elevation

- **Card/Button subtle shadow:** `rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, rgba(0, 0, 0, 0.03) 0px 2px 6px 0px`
- **Medium elevation (e.g., dropdowns, tooltips):** `rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px`
- **Hover/Active element elevation:** `rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px`
- **Modal/Prominent Overlay:** `rgba(0, 0, 0, 0.25) 0px 25px 50px -12px`

## Imagery

The visual language focuses on clear product demonstration, particularly through embedded UI screenshots. There are no lifestyle photos; instead, the site uses tight, contained screenshots of its own interface (like the dashboard) to directly showcase functionality. These are presented with sharp, unmasked edges. Additionally, there are branded icons from popular integrations, rendered as contained white squares with rounded corners, providing a sense of seamless connectivity. Imagery is functional and explanatory rather than decorative, occupying significant visual space to underscore product capability, but always within a structured layout.

## Layout

The site uses a max-width contained layout, typically centered around 1200px. The hero section is a full-width presentation with a prominent, large headline in Midnight Ink against a White Canvas background, flanked by a smaller, informational badge. Directly below the hero is a large, dark-themed screenshot of the product's dashboard UI, contrasting sharply with the light page background, effectively showcasing the product. Subsequent sections follow a clean, structured pattern, alternating between full-width content blocks and more contained sections, often using a single-column stack for text information, creating a clear and focused content flow. The navigation is a fixed top bar with simple text links and a distinct 'Get Started' button.

## Agent Prompt Guide

### Quick Color Reference
- Text (Primary): #000000
- Background (Primary): #ffffff
- CTA (Primary): #d1ff19
- Border (Subtle): #e5e7eb
- Link/Secondary Text: #94a3b8
- Dark UI Surface: #15171a

### Example Component Prompts
1. Create a hero section: White Canvas background. Headline 'Turn your audience into a business.' using InterDisplay, weight 700, 48px, line-height 1.0, letter-spacing -0.48px, Midnight Ink text. Add an 'Informational Badge' above the headline: Vivid Lime background, Midnight Ink text 'Just launched: Ghost 6.0 →', 9999px radius, 8px padding. Center align all content.
2. Create a Primary Call-to-action Button: Text 'Get Started — free', with Forest Green background, Muted Lime text, InterVariable weight 600, 15px, line-height 1.25, 8px radius, 8px vertical padding, 16px horizontal padding. Apply the subtle card shadow: rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, rgba(0, 0, 0, 0.03) 0px 2px 6px 0px.
3. Create a Navigation Link: Text 'Product', Midnight Ink color, InterVariable weight 400, 15px, line-height 1.25, with no background or padding. Ensure it is vertically central within a 94px tall header.
4. Create a Feature Card: White Canvas background, 8px radius, 24px padding. Headline 'Easy site design' using InterDisplay, weight 600, 24px, line-height 1.25, Dark Steel text. Body text 'Launch a custom website and tweak the design settings to perfectly match your brand and style.' using InterVariable, weight 400, 15px, line-height 1.5, Graphite text. Apply the subtle card shadow.

## Similar Brands

- **Stripe** — Shares a clean, high-contrast light UI with a strong focus on typography and subtle use of brand colors for interactive elements.
- **Linear** — Exhibits a similar approach to integrated dark UI elements (like a dashboard) within a predominantly light-themed page, maintaining clarity and function.
- **Notion** — Employs an extensive system of neutrals for hierarchy and a very limited palette of accent colors for key actions, paired with sharp, functional typography.
- **Vercel** — Features a light, spacious layout punctuated by dark UI components, particularly for code or application interfaces, emphasizing product capability over aesthetic flourish.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-midnight-ink: #000000;
  --color-carbon-black: #15171a;
  --color-slate-blue: #94a3b8;
  --color-graphite: #334155;
  --color-ash-gray: #e5e7eb;
  --color-light-steel: #cbd5e1;
  --color-dark-steel: #112220;
  --color-ghost-gray: #0f172a;
  --color-ghost-border: #1f2937;
  --color-vivid-lime: #d1ff19;
  --color-muted-lime: #bef264;
  --color-forest-green: #1a2e05;
  --color-sky-blue: #1bb6eb;
  --color-neon-pink: #f8b1e2;

  /* Typography — Font Families */
  --font-intervariable: 'InterVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-interdisplay: 'InterDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.15;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.48px;
  --text-display-lg: 72px;
  --leading-display-lg: 0.9;
  --text-display-xl: 96px;
  --leading-display-xl: 0.9;

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
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;

  /* Layout */
  --page-max-width: 1200px;
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 8px;
  --radius-input: 6px;
  --radius-buttons: 24px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, rgba(0, 0, 0, 0.03) 0px 2px 6px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-2: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-white-canvas: #ffffff;
  --color-midnight-ink: #000000;
  --color-carbon-black: #15171a;
  --color-slate-blue: #94a3b8;
  --color-graphite: #334155;
  --color-ash-gray: #e5e7eb;
  --color-light-steel: #cbd5e1;
  --color-dark-steel: #112220;
  --color-ghost-gray: #0f172a;
  --color-ghost-border: #1f2937;
  --color-vivid-lime: #d1ff19;
  --color-muted-lime: #bef264;
  --color-forest-green: #1a2e05;
  --color-sky-blue: #1bb6eb;
  --color-neon-pink: #f8b1e2;

  /* Typography */
  --font-intervariable: 'InterVariable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-interdisplay: 'InterDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 14px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.25;
  --text-heading: 24px;
  --leading-heading: 1.25;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.15;
  --text-display: 48px;
  --leading-display: 1;
  --tracking-display: -0.48px;
  --text-display-lg: 72px;
  --leading-display-lg: 0.9;
  --text-display-xl: 96px;
  --leading-display-xl: 0.9;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-72: 72px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 0px 1px 0px, rgba(0, 0, 0, 0.03) 0px 2px 6px 0px;
  --shadow-sm: rgba(0, 0, 0, 0.1) 0px 4px 6px -1px, rgba(0, 0, 0, 0.1) 0px 2px 4px -2px;
  --shadow-md: rgba(0, 0, 0, 0.1) 0px 10px 15px -3px, rgba(0, 0, 0, 0.1) 0px 4px 6px -4px;
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-2: rgba(0, 0, 0, 0.25) 0px 25px 50px -12px;
}
```
