# Lusion — Style Reference
> Computational Laboratory Blueprint — high-contrast text on bright surfaces, accented by vivid blue and lime green.

**Theme:** light

This design system conjures a computational laboratory aesthetic, balancing stark functionality with precise, vivid accents. The dominant bright off-white surfaces provide a clean canvas for sharp black typography, creating a high-contrast, information-focused layout. Carefully placed vivid blue and lime green appear in interactive elements, like focused indicators or calls to action, injecting focused energy against the predominantly neutral backdrop. Subtle elevation and generous border radii on active components soften the underlying hard-edged forms, implying a blend of digital precision and user-friendly interaction.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Absolute Black | `#000000` | `--color-absolute-black` | Primary text, critical UI elements, button text on light-colored buttons. |
| Canvas White | `#ffffff` | `--color-canvas-white` | Page backgrounds, card surfaces, button text on dark buttons. |
| Whisper Off-White | `#f0f1fa` | `--color-whisper-off-white` | Input fields, secondary backgrounds, subtle background differentiation. |
| Storm Gray | `#2b2e3a` | `--color-storm-gray` | Background for primary interactive elements, like the 'Let's Talk' button. |
| Button White | `#e4e6ef` | `--color-button-white` | Secondary button backgrounds, offering a slightly muted white option. |
| Dark Surface | `#121416` | `--color-dark-surface` | Base background for sections where a dark context is required, likely for visuals. |
| Deep Space Blue | `#1a2ffb` | `--color-deep-space-blue` | Interactive elements, active states, borders around focused components. This vivid blue serves as the primary accent, signaling interaction. |
| Electric Lime | `#c1ff00` | `--color-electric-lime` | Highlights, specific attention-grabbing elements. Its lower prominence suggests a secondary accent, used sparingly. |

## Tokens — Typography

### Aeonik — All textual content: headings, body text, buttons, links, and inputs. The consistent application of Aeonik across all roles contributes to the system's coherent, slightly technical feel, with negative letter spacing adding to the precise aesthetic. · `--font-aeonik`
- **Substitute:** system-ui (sans-serif)
- **Weights:** 400, 500
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 22px, 26px, 36px, 38px, 43px, 49px, 50px, 108px, 115px, 144px
- **Line height:** 0.90, 1.00, 1.10, 1.15, 1.20, 1.40, 1.50
- **Letter spacing:** -0.02
- **Role:** All textual content: headings, body text, buttons, links, and inputs. The consistent application of Aeonik across all roles contributes to the system's coherent, slightly technical feel, with negative letter spacing adding to the precise aesthetic.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.48px | `--text-caption` |
| body-sm | 14px | 1.5 | -0.48px | `--text-body-sm` |
| body | 16px | 1.5 | -0.48px | `--text-body` |
| subheading | 22px | 1.4 | -0.48px | `--text-subheading` |
| heading | 50px | 1 | -0.48px | `--text-heading` |
| heading-lg | 108px | 0.9 | -0.48px | `--text-heading-lg` |
| display | 144px | 0.9 | -0.48px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 4px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 168 | 168px | `--spacing-168` |
| 216 | 216px | `--spacing-216` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 15px |
| inputs | 18px |
| buttons | 87.5px |
| pillForms | 100px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| md | `rgba(0, 0, 0, 0.04) 0px 6px 10px 0px, rgba(0, 0, 0, 0.04)...` | `--shadow-md` |

### Layout

- **Card padding:** 25px
- **Element gap:** 13px

## Components

### Primary Action Button
**Role:** Primary Call to Action

Rounded pill-shaped button with 'Storm Gray' background (#2b2e3a), 'Canvas White' text (#ffffff). Uses 87.5px border-radius, with 22.75px left padding and 15.75px right padding for specific visual balance, and no vertical padding.

### Secondary Action Button
**Role:** Secondary Call to Action

Rounded pill-shaped button with 'Button White' background (#e4e6ef), 'Absolute Black' text (#000000). Uses 87.5px border-radius, with 22.75px left padding and 15.75px right padding for specific visual balance, and no vertical padding.

### Tertiary Button
**Role:** Further Actions / Navigation

Rounded pill-shaped button with 'Canvas White' background (#ffffff), 'Absolute Black' text (#000000). Uses 76.5px border-radius, with 21.6px horizontal padding and 14.4px vertical padding.

### Text Input Active
**Role:** User input fields

Input field with 'Whisper Off-White' background (#f0f1fa), 'Absolute Black' text (#000000). Features an 18px border-radius and 25px uniform padding. Border color is #000000 at 0px width.

### Interactive Card Container
**Role:** Content grouping

Container with a 15px border-radius, likely on a 'Canvas White' background or 'Storm Gray'. Features a subtle shadow: rgba(0, 0, 0, 0.04) 0px 6px 10px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px, suggesting an interactive or elevated state.

## Do's and Don'ts

### Do
- Prioritize 'Absolute Black' (#000000) for all primary body text, headings, and critical UI labels.
- Use 'Canvas White' (#ffffff) as the default background for main content areas and cards, creating a bright, spacious canvas.
- Apply 'Deep Space Blue' (#1a2ffb) as the primary accent color, specifically for interactive elements, links, and focused states.
- Ensure all buttons use an 87.5px border-radius unless specified, maintaining a soft, pill-like form.
- Utilize Aeonik at `weight: 500` for headings and important UI labels, combined with a negative letter-spacing for a modern, compact feel.
- Enforce a base padding unit of 16px around interactive elements like buttons and 25px for inputs to ensure ample breathing room.
- Introduce 'Whisper Off-White' (#f0f1fa) specifically for less prominent interactive elements or background differentiation in forms.

### Don't
- Avoid using multiple accent colors in close proximity; 'Deep Space Blue' and 'Electric Lime' should be used sparingly and distinctly.
- Do not deviate from the specified negative letter-spacing for Aeonik, as it is a core characteristic of the typographic identity.
- Do not use sharp corners for interactive elements; maintain the consistent application of generous border radii for buttons and inputs.
- Avoid generic or default shadow values; use the specified shadow `rgba(0, 0, 0, 0.04) 0px 6px 10px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px` for subtle elevation.
- Do not introduce highly saturated primary colors beyond 'Deep Space Blue' and 'Electric Lime' without specific justification.
- Avoid dense information blocks; maintain generous inter-element and inter-section spacing, aligning with the spacious density.

## Elevation

- **Interactive Button/Card:** `rgba(0, 0, 0, 0.04) 0px 6px 10px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px`

## Imagery

The site uses hero section imagery dominated by 3D abstract renders: interlocking shapes in white, black, and 'Deep Space Blue' against a dark background. These are contained within a main content area, with rounded corners (15px radius) rather than full-bleed. The role of these visuals is primarily decorative atmosphere and brand showcase, indicating expertise in 3D and interactive storytelling, rather than explanatory content. Image density is high in the hero, but otherwise the site appears to be text-dominant.

## Layout

The site uses a max-width contained layout, not full-bleed, with ample horizontal padding visible through the main content area. The hero section features 3D abstract graphics centrally aligned, framed by a card-like container with rounded corners. The overall section rhythm appears to alternate between bright white backgrounds for textual content and darker backgrounds for visual elements. Content arrangement leans towards centered stacks for headlines and calls to action, with text and potentially visuals arranged in a balanced, open manner. Navigation is a top bar with clear 'LET'S TALK' and 'MENU' buttons, maintaining ample space.

## Agent Prompt Guide

Quick Color Reference:
- Text: #000000
- Background: #ffffff
- CTA: #2b2e3a
- Border: #1a2ffb (for active/focus)
- Accent: #1a2ffb

Example Component Prompts:
1. Create a hero section with a "Canvas White" (#ffffff) background. Include a headline using Aeonik weight 500, size 144px, line-height 0.9, letter-spacing -0.02em, color "Absolute Black" (#000000). Below it, place a "Primary Action Button".
2. Build a card with a 'Canvas White' background, 15px border-radius, and the standard button/card shadow. Inside, include descriptive text using Aeonik weight 400, size 16px, line-height 1.5, color 'Absolute Black' (#000000).
3. Design a form input field using the 'Text Input Active' component specifications: 'Whisper Off-White' (#f0f1fa) background, 18px border-radius, 25px uniform padding. The placeholder text should be Aeonik weight 400, size 16px, color 'Absolute Black' (#000000) with 50% opacity.
4. Generate a navigation bar item: Text 'Home' with Aeonik weight 500, size 16px, color 'Absolute Black' (#000000), letter spacing -0.02em. On hover, apply 'Deep Space Blue' (#1a2ffb) as the text color.

## Similar Brands

- **Framer** — High-contrast text on bright, spacious layouts with a focus on modern, sans-serif typography and minimal but precise accent colors.
- **Superlist** — Uses a similar approach to slightly rounded pill-shaped buttons and inputs against a mostly neutral background, with focused use of vivid accents.
- **Linear** — Monochromatic approach with a strong typographic hierarchy, subtle elevation, and distinct color accents for interactive states.
- **Vercel** — Clean, developer-tool aesthetic with high contrast, precise typography, and a deliberate, sparing use of accent colors.
- **Stripe** — Understated visual design where clarity and functional typography combined with refined spacing create a sophisticated yet approachable interface.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-absolute-black: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-off-white: #f0f1fa;
  --color-storm-gray: #2b2e3a;
  --color-button-white: #e4e6ef;
  --color-dark-surface: #121416;
  --color-deep-space-blue: #1a2ffb;
  --color-electric-lime: #c1ff00;

  /* Typography — Font Families */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.48px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.48px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.48px;
  --text-heading: 50px;
  --leading-heading: 1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 108px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.48px;
  --text-display: 144px;
  --leading-display: 0.9;
  --tracking-display: -0.48px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-168: 168px;
  --spacing-216: 216px;

  /* Layout */
  --card-padding: 25px;
  --element-gap: 13px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-xl: 15px;
  --radius-2xl: 18px;
  --radius-full: 76.5px;
  --radius-full-2: 87.5px;
  --radius-full-3: 100px;

  /* Named Radii */
  --radius-cards: 15px;
  --radius-inputs: 18px;
  --radius-buttons: 87.5px;
  --radius-pillforms: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.04) 0px 6px 10px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-absolute-black: #000000;
  --color-canvas-white: #ffffff;
  --color-whisper-off-white: #f0f1fa;
  --color-storm-gray: #2b2e3a;
  --color-button-white: #e4e6ef;
  --color-dark-surface: #121416;
  --color-deep-space-blue: #1a2ffb;
  --color-electric-lime: #c1ff00;

  /* Typography */
  --font-aeonik: 'Aeonik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.48px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.48px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.48px;
  --text-subheading: 22px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.48px;
  --text-heading: 50px;
  --leading-heading: 1;
  --tracking-heading: -0.48px;
  --text-heading-lg: 108px;
  --leading-heading-lg: 0.9;
  --tracking-heading-lg: -0.48px;
  --text-display: 144px;
  --leading-display: 0.9;
  --tracking-display: -0.48px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-168: 168px;
  --spacing-216: 216px;

  /* Border Radius */
  --radius-sm: 3px;
  --radius-xl: 15px;
  --radius-2xl: 18px;
  --radius-full: 76.5px;
  --radius-full-2: 87.5px;
  --radius-full-3: 100px;

  /* Shadows */
  --shadow-md: rgba(0, 0, 0, 0.04) 0px 6px 10px 0px, rgba(0, 0, 0, 0.04) 0px 2px 4px 0px;
}
```
