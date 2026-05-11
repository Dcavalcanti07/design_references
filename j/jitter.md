# Jitter — Style Reference
> Graphic design studio on bleached white paper. A brightly lit, expansive canvas with meticulously placed, rounded interface elements and sharp, bold typography.

**Theme:** light

Jitter's design system feels like a playful yet precise workspace, balancing modern utility with a hint of creative energy. The stark contrast between near-black text and a luminous white background creates immediate clarity, while the prominent use of rounded forms, especially large 40-50px radii, softens the otherwise sharp presentation. Energetic violet and blue accents punctuate key interactions, guiding the user through a clean, spacious interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon | `#19171C` | `--color-carbon` | Primary text, deep backgrounds for inverted elements like the 'Try for free' button headers. |
| White Canvas | `#FFFFFF` | `--color-white-canvas` | Page backgrounds, card surfaces, primary button text color. |
| Lunar Dust | `#F2F1F3` | `--color-lunar-dust` | Subtle background for UI elements, very light card surfaces. |
| Gravel | `#E5E4E7` | `--color-gravel` | Subtle borders, inactive element backgrounds. |
| Ash | `#97979B` | `--color-ash` | Secondary text, descriptive body copy. |
| Slate | `#6E6E73` | `--color-slate` | Tertiary text, less prominent information, card detail text. |
| Jitter Violet | `#7A40ED` | `--color-jitter-violet` | Primary Call-to-Action buttons, interactive elements — a vibrant, playful invitation. |
| Sky Blue | `#00B2FF` | `--color-sky-blue` | Secondary accent for interactive elements, links, and highlighted content. Signifies progress or new features. |
| Lemon Drop | `#F5FF63` | `--color-lemon-drop` | Background for 'new' badges, bringing a sharp, attention-grabbing highlight. |
| Soft Violet | `#A981FF` | `--color-soft-violet` | Subtle background for cards or highlighted sections. |
| Lavender Mist | `#CAB3F8` | `--color-lavender-mist` | Lightest accent for subtle highlighting or hovers. |
| Nebula Gradient | `linear-gradient(rgb(20, 7, 38), rgb(113, 29, 226))` | `--color-nebula-gradient` | Background for bold, immersive sections or significant calls-to-action. |
| Aurora Gradient | `linear-gradient(rgb(169, 129, 255), rgb(208, 186, 254))` | `--color-aurora-gradient` | Subtle background gradient for elevated UI components or soft transitions. |

## Tokens — Typography

### TWK Lausanne — Display and primary headings. The extremely tight letter-spacing (-0.044em at 200px) creates a dense, impactful feel, while the range of heavy weights provides gravitas without excessive width. This custom font provides a distinctive, almost technical yet modern character. · `--font-twk-lausanne`
- **Substitute:** Montserrat
- **Weights:** 500, 600, 700, 750, 800
- **Sizes:** 16px, 18px, 20px, 21px, 24px, 36px, 40px, 48px, 72px, 80px, 200px
- **Line height:** 0.85, 0.90, 0.95, 1.00, 1.20, 1.38, 1.50, 2.50
- **Letter spacing:** -0.044em, -0.040em, -0.037em, -0.032em, -0.030em, -0.022em, -0.020em, -0.017em, -0.010em
- **Role:** Display and primary headings. The extremely tight letter-spacing (-0.044em at 200px) creates a dense, impactful feel, while the range of heavy weights provides gravitas without excessive width. This custom font provides a distinctive, almost technical yet modern character.

### Inter — Body text, navigation, secondary headings, and UI elements. Its high legibility at smaller sizes and various weights make it a versatile workhorse, maintaining clarity while supporting the visual hierarchy established by TWK Lausanne. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700, 800
- **Sizes:** 12px, 13px, 14px, 15px, 16px, 17px, 18px, 26px
- **Line height:** 1.10, 1.14, 1.15, 1.20, 1.25, 1.40, 1.41, 1.50, 1.60
- **Letter spacing:** -0.044em, -0.030em, -0.023em, -0.022em, -0.021em, -0.020em, -0.017em
- **Role:** Body text, navigation, secondary headings, and UI elements. Its high legibility at smaller sizes and various weights make it a versatile workhorse, maintaining clarity while supporting the visual hierarchy established by TWK Lausanne.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.44px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.32px | `--text-body-sm` |
| body | 16px | 1.5 | -0.32px | `--text-body` |
| subheading | 18px | 1.41 | -0.44px | `--text-subheading` |
| heading | 26px | 1.25 | -0.57px | `--text-heading` |
| heading-lg | 48px | 0.95 | -1.92px | `--text-heading-lg` |
| display | 80px | 0.9 | -2.88px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** comfortable

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 8 | 8px | `--spacing-8` |
| 12 | 12px | `--spacing-12` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 44 | 44px | `--spacing-44` |
| 60 | 60px | `--spacing-60` |
| 68 | 68px | `--spacing-68` |
| 80 | 80px | `--spacing-80` |
| 84 | 84px | `--spacing-84` |
| 100 | 100px | `--spacing-100` |
| 144 | 144px | `--spacing-144` |
| 180 | 180px | `--spacing-180` |
| 200 | 200px | `--spacing-200` |

### Border Radius

| Element | Value |
|---------|-------|
| badges | 40px |
| inputs | 0px 50px 50px 0px |
| buttons | 50px |
| default | 40px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(25, 23, 28, 0.01) 0px 152px 61px 0px, rgba(25, 23, 2...` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.01) 0px 63px 25px 0px, rgba(0, 0, 0, 0.05...` | `--shadow-xl-2` |
| subtle | `rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) -1...` | `--shadow-subtle` |
| xl-3 | `rgba(0, 0, 0, 0.01) 0px 119px 48px 0px, rgba(0, 0, 0, 0.0...` | `--shadow-xl-3` |

### Layout

- **Page max-width:** 860px
- **Section gap:** 64px
- **Element gap:** 12px

## Components

### Primary Call-to-Action Button
**Role:** Interactive element

Rounded button with Jitter Violet (#7A40ED) background and White Canvas (#FFFFFF) text. No border, large 50px border-radius, 13px vertical padding. Bold, inviting. Example: 'Try Jitter for free'.

### Secondary Call-to-Action Button
**Role:** Interactive element

Ghost button with Carbon (#19171C) text and transparent background. No border, 0px border-radius, minimum padding. Used for less prominent actions. Example: 'Log in'.

### Light Elevated Card
**Role:** Content container

White Canvas (#FFFFFF) background with a layered shadow: rgba(25, 23, 28, 0.01) 0px 152px 61px, rgba(25, 23, 28, 0.05) 0px 85px 51px, rgba(25, 23, 28, 0.09) 0px 38px 38px, rgba(25, 23, 28, 0.1) 0px 9px 21px. No border, 0px border-radius. Used for prominent content blocks requiring visual lift.

### Subtle Feature Card
**Role:** Content container

Lunar Dust (#F2F1F3) background, 40px border-radius. No shadow, 65px top padding. Used for displaying feature blocks or grouped content with a soft, distinct background.

### Search Input with Radius
**Role:** Form element

Dark background (rgba(45, 41, 51)), White Canvas (#FFFFFF) placeholder text. Unique 0px 50px 50px 0px border-radius (rounded on right side only). 13px vertical padding, 24px left padding. Used for focused input fields.

### 'New' Badge
**Role:** Informational label

Lemon Drop (#F5FF63) background, Carbon (#19171C) text. 0px border-radius, 4px horizontal and 2px vertical padding. Used for highlighting new features or content.

## Do's and Don'ts

### Do
- Prioritize TWK Lausanne for all display text and primary headings to maintain a bold, modern voice, using the tight letter-spacing as found in the typography specification.
- Utilize Jitter Violet (#7A40ED) exclusively for primary calls-to-action to ensure maximum visual hierarchy and user guidance.
- Apply a 40px border-radius to almost all interactive elements and contained content blocks to maintain the system's signature soft, approachable shape.
- Use White Canvas (#FFFFFF) as the dominant background color for page sections and primary content areas, contrasted by deep Carbon (#19171C) text.
- Implement the layered shadow rgba(25, 23, 28, 0.01) 0px 152px 61px, rgba(25, 23, 28, 0.05) 0px 85px 51px, rgba(25, 23, 28, 0.09) 0px 38px 38px, rgba(25, 23, 28, 0.1) 0px 9px 21px for elements requiring significant visual elevation.
- Employ Inter font for all body copy and UI element text for optimal readability across various sizes and contexts.
- Maintain a clear page structure with a maximum content width of 860px, ensuring consistent alignment and readability.

### Don't
- Avoid using flat, square buttons or cards; all interactive elements should incorporate the generous 40-50px border-radius.
- Do not introduce new vibrant colors beyond the defined Jitter Violet and Sky Blue accents; the color palette is intentionally refined.
- Refrain from using excessive or varied drop shadows; stick to the defined layered shadow for elevation or no shadow for flat elements.
- Do not deviate from the specified TWK Lausanne and Inter fonts or their respective letter-spacing values, especially for headings, to preserve typographic identity.
- Avoid centering large blocks of body text; left-alignment is preferred for readability within the narrow max-width constraint.
- Do not use dark backgrounds for entire page sections unless leveraging the specific Nebula Gradient, preserving the light theme's clarity.

## Elevation

- **Light Elevated Card:** `rgba(25, 23, 28, 0.01) 0px 152px 61px 0px, rgba(25, 23, 28, 0.05) 0px 85px 51px 0px, rgba(25, 23, 28, 0.09) 0px 38px 38px 0px, rgba(25, 23, 28, 0.1) 0px 9px 21px 0px`
- **Body context (subtle elevation):** `rgba(0, 0, 0, 0.01) 0px 63px 25px 0px, rgba(0, 0, 0, 0.05) 0px 35px 21px 0px, rgba(0, 0, 0, 0.09) 0px 16px 16px 0px, rgba(0, 0, 0, 0.1) 0px 4px 9px 0px`
- **Secondary card elevation:** `rgba(0, 0, 0, 0.01) 0px 119px 48px 0px, rgba(0, 0, 0, 0.05) 0px 67px 40px 0px, rgba(0, 0, 0, 0.09) 0px 30px 30px 0px, rgba(0, 0, 0, 0.1) 0px 7px 16px 0px`

## Imagery

The site's imagery is primarily product-focused, featuring abstract or simplified visuals that represent motion design elements. There are no photographs or complex illustrations. Instead, it utilizes clean icon outlines and abstract graphic shapes, often rendered in shades of gray or accented with Jitter Violet, Sky Blue, and Lemon Drop. These visuals are contained, rarely full-bleed, and serve an explanatory or decorative role to punctuate text blocks, maintaining the spacious, UI-centric feel. Iconography is minimal, using simple geometric shapes and clear lines.

## Layout

The page maintains a centered, fixed-width model, predominantly 860px, providing a structured and readable experience. The hero section often features a centered headline over a background that shifts between White Canvas and the Nebula Gradient. Content is arranged in alternating sections, commonly featuring a clear heading followed by text and then a visual or interactive element. There's a consistent vertical rhythm of spacing, creating ample breathing room, especially with generous top padding for components. Navigation is a sticky top bar, containing essential links and a prominent 'Try for free' button, suggesting ease of access and clear calls-to-action.

## Agent Prompt Guide

### Quick Color Reference
- Text: #19171C
- Background: #FFFFFF
- CTA: #7A40ED
- Border/Inactive: #E5E4E7
- Accent: #00B2FF

### 3-5 Example Component Prompts
1. Create a Hero Section: White Canvas background, page max-width 860px. Headline 'Super fast motion for every team' using TWK Lausanne weight 800, size 80px, line-height 0.9, color #19171C, letter-spacing -2.88px. Immediately below, a Jitter Violet CTA button (hex: #7A40ED, text: #FFFFFF, radius: 50px, padding: 13px 24px) with text 'Try Jitter for free' using Inter weight 500, size 16px.
2. Design a Feature Card: Lunar Dust background (hex: #F2F1F3), 40px border-radius, 65px top padding. Content inside should use Inter font, Slate (#6E6E73) for descriptions and Carbon (#19171C) for feature titles (Inter weight 600, size 18px).
3. Implement a 'New' Badge: Lemon Drop background (hex: #F5FF63), Carbon text (hex: #19171C), 0px border-radius, 4px horizontal padding, 2px vertical padding. Text content 'new' using Inter font weight 600, size 12px.
4. Create a Navigation Bar: Sticky top, White Canvas background. Left aligned logo (replace with Jitter logo asset if available). Right aligned links 'Product', 'Customers', 'Templates', 'Pricing' using Inter font weight 500, size 16px, color #19171C. Far right, the Header 'Try for free' Button (Carbon background #000000, White Canvas text, 50px radius).

## Similar Brands

- **Framer** — Similar high-contrast light theme, bold sans-serif display typography, and extensive use of rounded corners for UI elements.
- **Linear** — Shares a sophisticated, minimalist aesthetic with strong typographic hierarchy, subtle elevation, and a restrained use of accent colors.
- **Raycast** — Aligns on the modern, tool-oriented UI feel; clean typography, limited color palette, and focus on usability over heavy graphics.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon: #19171C;
  --color-white-canvas: #FFFFFF;
  --color-lunar-dust: #F2F1F3;
  --color-gravel: #E5E4E7;
  --color-ash: #97979B;
  --color-slate: #6E6E73;
  --color-jitter-violet: #7A40ED;
  --color-sky-blue: #00B2FF;
  --color-lemon-drop: #F5FF63;
  --color-soft-violet: #A981FF;
  --color-lavender-mist: #CAB3F8;
  --color-nebula-gradient: #711DE2;
  --gradient-nebula-gradient: linear-gradient(rgb(20, 7, 38), rgb(113, 29, 226));
  --color-aurora-gradient: #D0BAFE;
  --gradient-aurora-gradient: linear-gradient(rgb(169, 129, 255), rgb(208, 186, 254));

  /* Typography — Font Families */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.44px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.32px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 18px;
  --leading-subheading: 1.41;
  --tracking-subheading: -0.44px;
  --text-heading: 26px;
  --leading-heading: 1.25;
  --tracking-heading: -0.57px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -1.92px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -2.88px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;
  --font-weight-w750: 750;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-100: 100px;
  --spacing-144: 144px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Layout */
  --page-max-width: 860px;
  --section-gap: 64px;
  --element-gap: 12px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-3xl: 26px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 375px;

  /* Named Radii */
  --radius-badges: 40px;
  --radius-inputs: 0px 50px 50px 0px;
  --radius-buttons: 50px;
  --radius-default: 40px;

  /* Shadows */
  --shadow-xl: rgba(25, 23, 28, 0.01) 0px 152px 61px 0px, rgba(25, 23, 28, 0.05) 0px 85px 51px 0px, rgba(25, 23, 28, 0.09) 0px 38px 38px 0px, rgba(25, 23, 28, 0.1) 0px 9px 21px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.01) 0px 63px 25px 0px, rgba(0, 0, 0, 0.05) 0px 35px 21px 0px, rgba(0, 0, 0, 0.09) 0px 16px 16px 0px, rgba(0, 0, 0, 0.1) 0px 4px 9px 0px;
  --shadow-subtle: rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) -1px 0px 0px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.01) 0px 119px 48px 0px, rgba(0, 0, 0, 0.05) 0px 67px 40px 0px, rgba(0, 0, 0, 0.09) 0px 30px 30px 0px, rgba(0, 0, 0, 0.1) 0px 7px 16px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon: #19171C;
  --color-white-canvas: #FFFFFF;
  --color-lunar-dust: #F2F1F3;
  --color-gravel: #E5E4E7;
  --color-ash: #97979B;
  --color-slate: #6E6E73;
  --color-jitter-violet: #7A40ED;
  --color-sky-blue: #00B2FF;
  --color-lemon-drop: #F5FF63;
  --color-soft-violet: #A981FF;
  --color-lavender-mist: #CAB3F8;
  --color-nebula-gradient: #711DE2;
  --color-aurora-gradient: #D0BAFE;

  /* Typography */
  --font-twk-lausanne: 'TWK Lausanne', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.44px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.32px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.32px;
  --text-subheading: 18px;
  --leading-subheading: 1.41;
  --tracking-subheading: -0.44px;
  --text-heading: 26px;
  --leading-heading: 1.25;
  --tracking-heading: -0.57px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 0.95;
  --tracking-heading-lg: -1.92px;
  --text-display: 80px;
  --leading-display: 0.9;
  --tracking-display: -2.88px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-44: 44px;
  --spacing-60: 60px;
  --spacing-68: 68px;
  --spacing-80: 80px;
  --spacing-84: 84px;
  --spacing-100: 100px;
  --spacing-144: 144px;
  --spacing-180: 180px;
  --spacing-200: 200px;

  /* Border Radius */
  --radius-2xl: 20px;
  --radius-3xl: 26px;
  --radius-3xl-2: 40px;
  --radius-full: 50px;
  --radius-full-2: 375px;

  /* Shadows */
  --shadow-xl: rgba(25, 23, 28, 0.01) 0px 152px 61px 0px, rgba(25, 23, 28, 0.05) 0px 85px 51px 0px, rgba(25, 23, 28, 0.09) 0px 38px 38px 0px, rgba(25, 23, 28, 0.1) 0px 9px 21px 0px;
  --shadow-xl-2: rgba(0, 0, 0, 0.01) 0px 63px 25px 0px, rgba(0, 0, 0, 0.05) 0px 35px 21px 0px, rgba(0, 0, 0, 0.09) 0px 16px 16px 0px, rgba(0, 0, 0, 0.1) 0px 4px 9px 0px;
  --shadow-subtle: rgb(255, 255, 255) 1px 0px 0px 0px, rgb(255, 255, 255) -1px 0px 0px 0px;
  --shadow-xl-3: rgba(0, 0, 0, 0.01) 0px 119px 48px 0px, rgba(0, 0, 0, 0.05) 0px 67px 40px 0px, rgba(0, 0, 0, 0.09) 0px 30px 30px 0px, rgba(0, 0, 0, 0.1) 0px 7px 16px 0px;
}
```
