# Signal Messenger — Style Reference
> open sky, clear communication

**Theme:** light

This design system projects an image of digital security and approachability, achieved through a bright, spacious layout with rounded elements. The intentional use of soft blue and white as primary background colors creates an open, trustworthy atmosphere, while dark typography ensures readability. The system strikes a balance between solid, clear interactive elements and subtle background variation, making complex privacy concepts feel accessible.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Cloud Cover | `#ffffff` | `--color-cloud-cover` | Page backgrounds, card surfaces, primary button backgrounds — provides a crisp, bright canvas. |
| Sky Dust | `#f6f6f6` | `--color-sky-dust` | Subtle section dividers, slight background variation to break visual monotony. |
| Stone Whisper | `#e9e9e9` | `--color-stone-whisper` | Subtle borders and dividers, providing separation without harsh lines. |
| Signal Blue | `#9dbbf8` | `--color-signal-blue` | Hero section background, conveying a sense of calm and clarity. |
| Ocean Deep | `#2c6bed` | `--color-ocean-deep` | Primary Call-to-Action button text and borders, links — a vibrant, trustworthy blue indicating action. |
| Night Sky | `#1b1b1b` | `--color-night-sky` | Primary text, headings, and key UI elements ensuring high contrast and legibility. |
| Deep Space | `#404654` | `--color-deep-space` | Secondary text, subtle accents, creating depth in informational sections. |
| Slate Shadow | `#3c3744` | `--color-slate-shadow` | Footer background, providing a grounding anchor to the page. |
| Link Blue | `#2942ff` | `--color-link-blue` | Navigation links and secondary interactive elements, differentiating them from primary CTAs. |
| Subtle Mist | `#a5cad5` | `--color-subtle-mist` | Decorative background fills on feature blocks, maintaining a light, airy feel. |

## Tokens — Typography

### Inter — Primary typeface for all textual content, from navigation to display headings. Inter's clean, humanist grotesque design supports clarity and readability across various sizes, reinforcing the message of clear communication. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 600, 800
- **Sizes:** 16px, 20px, 28px, 40px, 60px
- **Line height:** 1.07, 1.10, 1.14, 1.38, 1.40, 1.50
- **Letter spacing:** normal
- **Role:** Primary typeface for all textual content, from navigation to display headings. Inter's clean, humanist grotesque design supports clarity and readability across various sizes, reinforcing the message of clear communication.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| body | 16px | 1.5 | — | `--text-body` |
| subheading | 20px | 1.4 | — | `--text-subheading` |
| heading | 28px | 1.14 | — | `--text-heading` |
| heading-lg | 40px | 1.1 | — | `--text-heading-lg` |
| display | 60px | 1.07 | — | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 6px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 12 | 12px | `--spacing-12` |
| 18 | 18px | `--spacing-18` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 48 | 48px | `--spacing-48` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| images | 16px |
| buttons | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08)...` | `--shadow-md` |

### Layout

- **Page max-width:** 1344px
- **Section gap:** 64px
- **Card padding:** 30px
- **Element gap:** 12px

## Components

### Primary Call-to-Action Button
**Role:** Primary interactive element for key actions

White background, Ocean Deep (#2c6bed) text and 1px border. Height is text-based with 0px vertical padding, 20px horizontal padding. Border radius 8px. Text is Inter 400 at 16px, line-height 1.50.

### Navigation Link Button
**Role:** Secondary action in header navigation

Transparent background, Night Sky (#1b1b1b) text. 1px Night Sky (#1b1b1b) border. Height is text-based with 8px vertical padding, 12px horizontal padding. No border radius. Text is Inter 400 at 16px, line-height 1.50.

### Navigation Item Link
**Role:** Standard navigation link

Night Sky (#1b1b1b) text (Inter 400, 16px). Uses a secondary accent color, Link Blue (#2942ff), on hover and active states.

### Product Screenshot Wrapper
**Role:** Encapsulates product visuals

Wraps product screenshots with a 16px border radius. Shadows applied: rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px to provide subtle elevation.

## Do's and Don'ts

### Do
- Use Night Sky (#1b1b1b) for all primary headings and body text to ensure maximum readability against light backgrounds.
- Apply Signal Blue (#9dbbf8) as a primary background accent for hero sections to immediately establish brand identity.
- Utilize 8px border-radius for all primary buttons to maintain a soft, approachable aesthetic.
- Maintain a clear page structure with sections separated by at least 64px, alternating backgrounds where appropriate (Cloud Cover #ffffff, Sky Dust #f6f6f6, or Signal Blue #9dbbf8).
- Ensure all interactive elements, such as buttons and links, use Ocean Deep (#2c6bed) or Link Blue (#2942ff) to signify action and interaction clearly.
- Use Inter font family exclusively for all text elements, leveraging weights 400 for body, 600 for subheadings, and 800 for major headings and display titles.

### Don't
- Avoid using highly saturated, non-brand colors; stick to the established palette of blues, grays, and whites.
- Do not deviate from the 8px and 16px border radii; squared or overly complex rounded shapes are not part of this system.
- Never use dark backgrounds for large text blocks except in the footer where Slate Shadow (#3c3744) is established, always prioritize high contrast with light backgrounds.
- Do not introduce complex gradients or texture overlays on backgrounds; maintain a flat, clean aesthetic.
- Avoid excessive use of shadows; reserve the specific shadow token rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px only for elevated elements like product mocks.

## Elevation

- **Product Screenshot Wrapper:** `rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px`

## Imagery

Imagery primarily consists of product screenshots of the Signal app on mobile devices, treated with subtle shadows indicating elevation. These are typically contained within the main layout. Illustrations are abstract and geometric, using brand colors and outlines to convey concepts like global communication and security without being overly literal. Icons are outlined, simple, and monochrome, complementing the clean UI. The visual emphasis is on functionality and clarity, using images to explain product features rather than for decorative atmosphere.

## Layout

The site uses a max-width 1344px centered container for most content, with a full-bleed hero section employing Signal Blue (#9dbbf8) background. Sections generally alternate between clean white backgrounds (Cloud Cover #ffffff) and very subtle gray backgrounds (Sky Dust #f6f6f6) or brand-colored fills (Signal Blue #9dbbf8, Subtle Mist #a5cad5), creating a gentle visual rhythm. Content is often arranged in a split layout, with text on one side and a visual (product screenshot or illustration) on the other. Navigation is a sticky top bar with clearly delineated links and buttons. Vertical spacing between main sections is generous, around 64px, contributing to a spacious feel.

## Agent Prompt Guide

### Quick Color Reference
- Text: #1b1b1b (Night Sky)
- Background: #ffffff (Cloud Cover)
- CTA Button: #2c6bed (Ocean Deep)
- Border: #e9e9e9 (Stone Whisper)
- Accent Background: #9dbbf8 (Signal Blue)
- Footer Background: #3c3744 (Slate Shadow)

### 3-5 Example Component Prompts
1.  **Create a Hero Section:** Background Signal Blue (#9dbbf8). Centered headline 'Speak Freely' using Inter 800 at 60px, line-height 1.07, color #1b1b1b. Subtext 'Say hello...' using Inter 400 at 20px, line-height 1.40, color #1b1b1b. Include a primary CTA button: background white, text Ocean Deep (#2c6bed), 1px Ocean Deep (#2c6bed) border, 8px radius, 0px vertical padding, 20px horizontal padding, Inter 400 at 16px.
2.  **Generate a Feature Block:** Background Cloud Cover (#ffffff). Heading `Share Without Insecurity` using Inter 800 at 40px, line-height 1.10, color #1b1b1b. Body text `State-of-the-art...` using Inter 400 at 16px, line-height 1.50, color #1b1b1b. A decorative block with Subtle Mist (#a5cad5) background and 16px border-radius, right-aligned.
3.  **Design a Footer:** Background Slate Shadow (#3c3744). Text (links and copyright) primarily using Inter 400 at 16px, line-height 1.50, color #e9e9e9. Columns should have an element gap of 12px.

## Similar Brands

- **ProtonMail** — Both prioritize privacy and convey trust through clean, clear light-themed interfaces with blue accents and direct typography.
- **DuckDuckGo** — Similar focus on user privacy and a commitment to a light, uncluttered UI with a distinct blue brand color for interaction.
- **Telegram** — Messaging app promoting security, using a light theme with prominent blue interactions and clean, legible typography.
- **Wire** — Another secure messaging platform, employs a crisp, functional design with emphasis on interaction clarity and a subdued color palette.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-cloud-cover: #ffffff;
  --color-sky-dust: #f6f6f6;
  --color-stone-whisper: #e9e9e9;
  --color-signal-blue: #9dbbf8;
  --color-ocean-deep: #2c6bed;
  --color-night-sky: #1b1b1b;
  --color-deep-space: #404654;
  --color-slate-shadow: #3c3744;
  --color-link-blue: #2942ff;
  --color-subtle-mist: #a5cad5;

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 28px;
  --leading-heading: 1.14;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --text-display: 60px;
  --leading-display: 1.07;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-semibold: 600;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 6px;
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-48: 48px;

  /* Layout */
  --page-max-width: 1344px;
  --section-gap: 64px;
  --card-padding: 30px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-images: 16px;
  --radius-buttons: 8px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-cloud-cover: #ffffff;
  --color-sky-dust: #f6f6f6;
  --color-stone-whisper: #e9e9e9;
  --color-signal-blue: #9dbbf8;
  --color-ocean-deep: #2c6bed;
  --color-night-sky: #1b1b1b;
  --color-deep-space: #404654;
  --color-slate-shadow: #3c3744;
  --color-link-blue: #2942ff;
  --color-subtle-mist: #a5cad5;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-body: 16px;
  --leading-body: 1.5;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --text-heading: 28px;
  --leading-heading: 1.14;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.1;
  --text-display: 60px;
  --leading-display: 1.07;

  /* Spacing */
  --spacing-12: 12px;
  --spacing-18: 18px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-48: 48px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.12) 0px 4px 12px 0px, rgba(0, 0, 0, 0.08) 0px 0px 2px 0px;
}
```
