# ChatGPT — Style Reference
> Frosted glass workstation. An environment of quiet focus, where soft grays frame crisp textual interaction.

**Theme:** light

This design system presents an austere, functional interface resembling a digital workspace focused on clarity. Predominantly achromatic with precise geometry and subtle textural shifts in its grays, it creates an environment where content takes precedence. The judicious use of system fonts with controlled letter spacing ensures legibility, while rounded forms are reserved for interactive elements, providing visual cues for action within an otherwise stark layout.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon | `#0d0d0d` | `--color-carbon` | Primary text, critical headings, icons – its near-black depth offers strong contrast against the light surfaces. |
| Snow | `#ffffff` | `--color-snow` | Page backgrounds, card surfaces, interactive button fills – the purest backdrop for content. |
| Fog | `#f9f9f9` | `--color-fog` | Secondary background for navigation panels, subtly differentiating sidebars from main content areas. |
| Pewter | `#5d5d5d` | `--color-pewter` | Secondary text, placeholder text – a muted gray that recedes subtly, hinting at information without demanding attention. |
| Stone | `#8f8f8f` | `--color-stone` | Placeholder text, inactive icons, subtle borders – an even lighter presence than Pewter, indicating non-primary elements. |
| Arctic Mist | `#ececec` | `--color-arctic-mist` | Ghost button background for hover states, providing a faint highlight against white. |
| Link Blue | `#007aff` | `--color-link-blue` | Interactive elements, links, indicating clickable actions within conversational text. |

## Tokens — Typography

### ui-sans-serif — Primary UI font for body text (14px, 16px), navigation labels (14px, 16px), and button text (14px, 16px). Its clarity and availability across platforms ensures consistent readability for core interactions. Headings use 24px weight 600 for emphasis, 18px and 14px uses weight 400 for sub-headings, body, and links. · `--font-ui-sans-serif`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600
- **Sizes:** 14px, 16px, 18px, 24px
- **Line height:** 1.00, 1.43, 1.50, 1.56
- **Letter spacing:** normal
- **OpenType features:** `"liga" 0`
- **Role:** Primary UI font for body text (14px, 16px), navigation labels (14px, 16px), and button text (14px, 16px). Its clarity and availability across platforms ensures consistent readability for core interactions. Headings use 24px weight 600 for emphasis, 18px and 14px uses weight 400 for sub-headings, body, and links.

### OpenAI Sans — Used for the primary prompt/headline in the main content area ('Where should we begin?'). Its distinct weight and slightly tighter letter spacing give it a refined, prominent voice that commands attention without being visually loud over other UI text. · `--font-openai-sans`
- **Substitute:** system-ui, sans-serif
- **Weights:** 600
- **Sizes:** 18px
- **Line height:** 1.56
- **Letter spacing:** -0.015
- **Role:** Used for the primary prompt/headline in the main content area ('Where should we begin?'). Its distinct weight and slightly tighter letter spacing give it a refined, prominent voice that commands attention without being visually loud over other UI text.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 14px | 1.43 | — | `--text-caption` |
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 18px | 1.56 | — | `--text-subheading` |
| heading | 24px | 1 | — | `--text-heading` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 60 | 60px | `--spacing-60` |
| 64 | 64px | `--spacing-64` |
| 127 | 127px | `--spacing-127` |

### Border Radius

| Element | Value |
|---------|-------|
| input | 28px |
| buttons | 10px |
| default | 10px |

### Layout

- **Page max-width:** 1150px
- **Section gap:** 64px
- **Card padding:** 20px
- **Element gap:** 4px

## Components

### Primary Ghost Button
**Role:** Interactive element

Text-only button for navigation items and secondary actions. Background rgba(0, 0, 0, 0), text Carbon (#0d0d0d) via color=rgb(13, 13, 13). No explicit padding in base state, suggesting internal content dictates size.

### Pill Outline Button
**Role:** Main CTAs

Used for 'Sign up for free'. White background (#ffffff), Carbon text (#0d0d0d). Border defined by borderTopColor rgba(0, 0, 0, 0.15), implying a subtle bottom shadow or edge. Full pill radius 16777215px, 16px horizontal padding.

### Black Filled Button
**Role:** Key CTAs

Used for 'Log in'. Inherits Carbon (#0d0d0d) as background, white text (#ffffff). Full pill radius 16777215px, 16px horizontal padding.

### Input with Voice Button
**Role:** Primary interaction input

The main 'Ask anything' input field. Background rgba(0, 0, 0, 0), text Carbon (#0d0d0d). Rounded rectangle with 28px radius. Contains a subtle 'Voice' button with 16px radius, similar styling to Pill Outline Button but within the input.

### Sidebar Navigation Item
**Role:** Navigation links

Items like 'New chat' and 'Search chats'. Background rgba(0, 0, 0, 0) in default state. Text Carbon (#0d0d0d), icons fill Carbon (#000000). Radius 10px, with 6px vertical padding and 8px left padding, 6px right padding, suggesting minimal touch targets.

### Sidebar Login Prompt
**Role:** Information/action block

The 'Get responses tailored to you' section in the sidebar. Text Pewter (#5d5d5d). Contains a 'Log In' button with White background (#ffffff) and Carbon text (#0d0d0d), 16px radius, 8px vertical and 16px horizontal padding.

### Contextual Link
**Role:** Informational links

Used for 'Terms', 'Privacy Policy'. Color Pewter (#5d5d5d) via color=rgb(13, 13, 13) with specific text decoration. No explicit padding or border properties.

## Do's and Don'ts

### Do
- Use Carbon (#0d0d0d) for all primary text content to ensure maximum legibility against light backgrounds.
- Apply Snow (#ffffff) for primary page and component backgrounds, utilizing Fog (#f9f9f9) for secondary background panels like sidebars.
- Ensure interactive components like buttons and inputs feature generous border radii; use 16px for buttons and 28px for the main input field.
- Maintain a clear visual hierarchy by using OpenAI Sans weight 600 at 18px for main conversational prompts and ui-sans-serif for all other UI text.
- Implement 6px vertical padding paired with 8px horizontal padding for active navigation items to establish distinctive hover/selected states.
- Utilize Pewter (#5d5d5d) for all secondary, descriptive, or placeholder text, providing subtle content without drawing primary attention.

### Don't
- Avoid introducing any colors other than the defined neutrals and Link Blue (#007aff), to preserve the system's austere palette.
- Do not use sharp corners for interactive elements; all buttons and inputs must adhere to the specified radii of 16px or 28px.
- Never use type weights exceeding 600; the system relies on lighter weights for a calm, understated voice.
- Refrain from adding explicit shadows; the system prioritizes background color shifts (e.g., from Snow to Fog) for depth, with only subtle borders or pseudo-shadows for outlines.
- Do not deviate from the established spacing scale of 4px, 6px, 8px, 10px, 12px, 16px, 20px, 60px, 64px, 127px for element and section separation.
- Avoid full-bleed backgrounds for content sections; adhere to the 1150px max-width content container, even for the main interaction area.

## Imagery

The design relies primarily on clean, outlined icons for navigation and functional elements. There are no prominent photographs or illustrations; visual storytelling is achieved through minimalist iconography. Icons are monochromatic, mostly in Carbon or Stone, and serve a purely functional, explanatory role rather than decorative. The density is extremely low, preferring white space and typography to communicate.

## Layout

The page adheres to a two-column, fixed-width layout, centered within a max-width of 1150px. A left sidebar (nav) provides persistent global navigation, while the main content area (main) is dedicated to the AI chat interface. The hero pattern is a centered, conversational prompt ('Where should we begin?') above a single prominent input field. Sections are delineated by clear white space and subtle background color shifts rather than dividers. The overall density is spacious, ensuring focus on the primary interaction. A top-right header contains utility buttons.

## Agent Prompt Guide

### Quick Color Reference
- Text: #0d0d0d (Carbon)
- Background: #ffffff (Snow)
- Sidebar Background: #f9f9f9 (Fog)
- CTA Button Background: #0d0d0d (Carbon) or #ffffff (Snow)
- Placeholder Text: #5d5d5d (Pewter)
- Active/Link Accent: #007aff (Link Blue)

### 3-5 Example Component Prompts
1. **Create a primary conversational input field:** Centered on the page, text 'Ask anything' in Pewter #5d5d5d, font ui-sans-serif weight 400 at 16px. Background Snow #ffffff, border rgba(0, 0, 0, 0.15) on top, 28px radius. Include an inline 'Voice' button with ui-sans-serif weight 400 at 14px, #0d0d0d text, 16px radius, 16px internal horizontal padding, and a subtle light gray background for a pill shape.
2. **Generate a sidebar navigation item for 'New chat':** Text 'New chat' in Carbon #0d0d0d, ui-sans-serif weight 400 at 16px. Include a monochrome icon (like a plus sign) in Carbon #000000. Give it 6px vertical padding, 8px left padding, and 6px right padding, with 10px corner radius on hover.
3. **Design a pair of top-right utility buttons:** A 'Log in' button with Carbon #0d0d0d background, white text #ffffff, ui-sans-serif weight 400 at 16px, 16777215px (pill) radius, and 16px horizontal padding. Beside it, a 'Sign up for free' button with Snow #ffffff background, Carbon #0d0d0d text, border from rgba(0, 0, 0, 0.15) top, and the same pill radius and padding.
4. **Create a descriptive text block within the sidebar:** 'Get responses tailored to you' as a heading in Carbon #0d0d0d, ui-sans-serif weight 500 at 14px. Followed by a paragraph 'Log in to get answers based on saved chats, plus create images and upload files' in Pewter #5d5d5d, ui-sans-serif weight 400 at 14px, with a line height of 1.43.
5. **Render a main page headline:** "Where should we begin?" centered on the page, using OpenAI Sans weight 600 at 18px (lineHeight 1.56, letterSpacing -0.015em), in Carbon #0d0d0d.

## Similar Brands

- **Google Search** — Dominant white space, central input field as primary interaction, and minimalist 'less-is-more' approach to UI elements.
- **Notion** — Clean, functional aesthetic with strong typographic hierarchy, extensive use of white space, and subtle gray tones for UI elements.
- **Linear** — Achromatic color palette, focus on information density within a structured layout, and understated interactive elements.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon: #0d0d0d;
  --color-snow: #ffffff;
  --color-fog: #f9f9f9;
  --color-pewter: #5d5d5d;
  --color-stone: #8f8f8f;
  --color-arctic-mist: #ececec;
  --color-link-blue: #007aff;

  /* Typography — Font Families */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-openai-sans: 'OpenAI Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 24px;
  --leading-heading: 1;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-127: 127px;

  /* Layout */
  --page-max-width: 1150px;
  --section-gap: 64px;
  --card-padding: 20px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 28px;

  /* Named Radii */
  --radius-input: 28px;
  --radius-buttons: 10px;
  --radius-default: 10px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon: #0d0d0d;
  --color-snow: #ffffff;
  --color-fog: #f9f9f9;
  --color-pewter: #5d5d5d;
  --color-stone: #8f8f8f;
  --color-arctic-mist: #ececec;
  --color-link-blue: #007aff;

  /* Typography */
  --font-ui-sans-serif: 'ui-sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-openai-sans: 'OpenAI Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 14px;
  --leading-caption: 1.43;
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.56;
  --text-heading: 24px;
  --leading-heading: 1;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-60: 60px;
  --spacing-64: 64px;
  --spacing-127: 127px;

  /* Border Radius */
  --radius-lg: 10px;
  --radius-2xl: 16px;
  --radius-3xl: 28px;
}
```
