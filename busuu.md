# Busuu — Style Reference
> Vibrant learning portal on a clean canvas. A spacious, friendly digital environment where interactive elements pop against a minimal backdrop.

**Theme:** light

Busuu's design creates an educational and encouraging atmosphere through its vibrant, optimistic color palette and clear, structured layout. A dominant hero section with a gradient background grounds the brand's primary visual identity, which then transitions into a clean, spacious white canvas. Vivid blue and a unique, bright green act as key interactive accents, indicating engagement and positive action, while the consistent use of rounded corners on buttons and navigation elements softens the overall feel, enhancing approachability.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ocean Blue | `#116eee` | `--color-ocean-blue` | Primary brand color for interactive text, links, and secondary buttons, creating a sense of clarity and trustworthiness. |
| Spring Green | `#11ee92` | `--color-spring-green` | Prominent action color for primary CTA buttons, signaling progress and success. Its high saturation ensures immediate visibility. |
| Sky Tint | `#87b6f6` | `--color-sky-tint` | Secondary brand accent, used for subtle visual cues and illustrations, supporting the primary blue without competing. |
| Light Bluewash | `#b8d4fa` | `--color-light-bluewash` | Muted blue accent for background elements or illustrations, adding depth to the brand palette. |
| Electric Cyan | `#06d2ff` | `--color-electric-cyan` | Tertiary accent, provides an additional dynamic pop of color in illustrations. |
| Action Red | `#fa3746` | `--color-action-red` | Accent color for specific, high-attention elements within illustrations. |
| Mellow Yellow | `#ffcf00` | `--color-mellow-yellow` | Accent color, provides friendly contrast in illustrations or minor highlights. |
| Pure White | `#ffffff` | `--color-pure-white` | Dominant background color for content sections, cards, and prominent text elements for excellent readability. |
| Cloud Gray | `#f2f7fd` | `--color-cloud-gray` | Subtle background color for alternating section bands or very light surface elevation. |
| Border Fog | `#d6dee6` | `--color-border-fog` | Light gray for input borders and subtle UI separators, maintaining a soft aesthetic. |
| Text Anthracite | `#252b2f` | `--color-text-anthracite` | Primary text color for headlines, body copy, and form elements, offering strong contrast against light backgrounds. |
| Slate Blue | `#666e7` | `--color-slate-blue` | Secondary text color for less prominent information, links, and subheadings, providing visual hierarchy. |
| Disabled Ash | `#b3b3b3` | `--color-disabled-ash` | Color for disabled states or subtle placeholder text, indicating non-interactivity. |
| Deep Black | `#000000` | `--color-deep-black` | Used for most icons and some instances of body text, providing maximum contrast and clarity where needed. |
| Hero Gradient | `linear-gradient(90deg, #116eee, #11ee92, #0ef076)` | `--color-hero-gradient` | Background for the primary hero section, creating an immersive and dynamic introduction to the brand. |

## Tokens — Typography

### Nista — The primary typeface for all text elements, from body copy to headlines, maintaining a consistent, approachable brand voice across all sizes and weights. Weight 400 is standard for body text, 700 and 800 for emphasizing headlines and navigation. · `--font-nista`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 700, 800
- **Sizes:** 10px, 12px, 14px, 16px, 18px, 24px, 36px, 40px
- **Line height:** 1.14, 1.20, 1.30, 1.33, 1.50, 1.70
- **Letter spacing:** normal
- **Role:** The primary typeface for all text elements, from body copy to headlines, maintaining a consistent, approachable brand voice across all sizes and weights. Weight 400 is standard for body text, 700 and 800 for emphasizing headlines and navigation.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body | 14px | 1.5 | — | `--text-body` |
| body-lg | 16px | 1.5 | — | `--text-body-lg` |
| subheading | 18px | 1.33 | — | `--text-subheading` |
| heading | 24px | 1.2 | — | `--text-heading` |
| heading-lg | 36px | 1.14 | — | `--text-heading-lg` |
| display | 40px | 1.14 | — | `--text-display` |

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
| 28 | 28px | `--spacing-28` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| inputs | 5px |
| buttons | 45.04px |
| navItems | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px` | `--shadow-subtle` |

### Layout

- **Section gap:** 40-60px
- **Card padding:** 20px
- **Element gap:** 8-20px

## Components

### Primary Call to Action Button
**Role:** Interactive element

Rounded pill button with 'Spring Green' background (#11ee92) and 'Text Anthracite' (#252b2f) text, providing clear visual hierarchy for primary actions. Padding is 12px vertical, 40px horizontal, with a 45.04px border-radius.

### Hero Section Headline
**Role:** Information display

Uses Nista font, typically at 40px, weight 800, with Pure White (#ffffff) color, set against the 'Hero Gradient' background to immediately capture attention.

### Text Input Field
**Role:** Form element

A text input with 'Border Fog' (#d6dee6) border, 'Text Anthracite' (#252b2f) text color, and a 5px border-radius. Padding of 10px vertical and 10px left/right, with 25px additional padding on the right for implied icons.

### General Body Text
**Role:** Information display

Uses Nista font, typically at 16px, weight 400, in 'Text Anthracite' (#252b2f) for primary content and 'Slate Blue' (#666e7e) for supporting information.

## Do's and Don'ts

### Do
- Prioritize 'Spring Green' (#11ee92) for all primary call-to-action buttons, ensuring a 45.04px border-radius and 'Text Anthracite' (#252b2f) text.
- Use 'Ocean Blue' (#116eee) exclusively for interactive elements like links and secondary navigation items, either as text color or outline.
- Maintain a clear visual hierarchy by setting headlines in Nista 800 and body text in Nista 400 at their respective semantic sizes.
- Apply the `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px` shadow consistently for subtle elevation on cards or modal elements.
- Utilize 'Pure White' (#ffffff) as the predominant background color for content sections to maximize readability.
- Employ a 4px base unit for all spacing, with common increments like 8px, 16px, 20px, and 40px for larger gaps and padding.
- Align all input fields with a 5px border-radius and 'Border Fog' (#d6dee6) border for a unified form aesthetic.

### Don't
- Do not use dark or highly saturated colors for large background areas, except for the hero section's specific gradient.
- Avoid using any border-radius value other than 5px for inputs, 16px for nav items, or 45.04px for buttons, to preserve brand consistency.
- Refrain from using strong, contrasting colors for general body text; stick to 'Text Anthracite' (#252b2f) and 'Slate Blue' (#666e7e).
- Do not introduce new shadow styles; adhere to the specified `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px` for all elevation.
- Do not add unnecessary decorative elements or strong graphical treatments that compete with the clean, friendly aesthetic.
- Avoid using the 'Spring Green' (#11ee92) or 'Ocean Blue' (#116eee) colors for non-interactive textual content; reserve them for active elements.

## Elevation

- **body:** `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px`

## Imagery

The site uses a combination of abstract, friendly vector illustrations with a flat, clean aesthetic, and flags as small, functional icons. Illustrations feature simplified human figures engaged in learning activities, often within subtle outlines and filled with brand colors (like 'Sky Tint', 'Electric Cyan', 'Action Red', and 'Mellow Yellow') against a world map motif. Imagery is primarily explanatory and decorative, supporting the educational content rather than product showcases. There's a minimal use of complex photography, shifting focus to the UI and illustrations. Icons are outlined or filled, generally monochrome in 'Deep Black' or 'Text Anthracite', with a consistent visual weight.

## Layout

The page primarily follows a max-width contained model after an initial full-bleed hero section. The hero is a dynamic gradient with a centered headline and CTA. Subsequent sections alternate between a 'Pure White' background and a 'Cloud Gray' or similar light neutral background, creating a gentle visual rhythm. Content within sections is often structured with left-aligned text and right-aligned visuals (or vice-versa) or as centered stacks for key messages. Navigation is a sticky top bar with clearly defined 'Learn for free' and 'Log in' actions, utilizing both a primary accent button and a secondary outlined button. A prominent feature is the use of horizontal scrollable carousels for content like language selection, indicating more content availability without cluttering the initial view.

## Agent Prompt Guide

### Quick Color Reference
- Text Anthracite: #252b2f
- Pure White: #ffffff
- Spring Green: #11ee92
- Ocean Blue: #116eee
- Border Fog: #d6dee6

### 3-5 Example Component Prompts
1. Create a primary call-to-action button: 'Spring Green' background (#11ee92), 'Text Anthracite' text (#252b2f), 'Nista' font weight 700, 12px vertical / 40px horizontal padding, 45.04px border-radius.
2. Design a navigation link button: transparent background, 'Ocean Blue' text (#116eee), 'Ocean Blue' border (#116eee, 1px solid), 'Nista' font weight 700, 12px vertical / 40px horizontal padding, 45.04px border-radius.
3. Generate a section subheading: 'Text Anthracite' (#252b2f), 'Nista' font weight 700, 24px size, 1.2 line-height.
4. Produce a standard input field: 'Border Fog' border (#d6dee6, 1px solid), 'Pure White' background (#ffffff), 'Text Anthracite' placeholder text (#252b2f), 5px border-radius, 10px vertical / 10px left / 25px right padding.
5. Create a language selection card: 'Pure White' background (#ffffff), `rgba(0, 0, 0, 0.1) 0px 1px 2px 0px` box-shadow, 16px corner radius, 'Nista' font weight 400 at 16px, 'Slate Blue' (#666e7e) text, with an image slot above the text.

## Similar Brands

- **Duolingo** — Shares a vibrant color palette, friendly illustrations, and a gamified, approachable aesthetic for language learning.
- **Coursera** — Offers structured educational content with clear visual hierarchy and an emphasis on clean layouts for a seamless learning experience, with similar accent color usage.
- **Headspace** — Utilizes friendly, simplified illustrations and a calm, clean aesthetic to convey a sense of accessibility and ease for its core offering.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ocean-blue: #116eee;
  --color-spring-green: #11ee92;
  --color-sky-tint: #87b6f6;
  --color-light-bluewash: #b8d4fa;
  --color-electric-cyan: #06d2ff;
  --color-action-red: #fa3746;
  --color-mellow-yellow: #ffcf00;
  --color-pure-white: #ffffff;
  --color-cloud-gray: #f2f7fd;
  --color-border-fog: #d6dee6;
  --color-text-anthracite: #252b2f;
  --color-slate-blue: #666e7;
  --color-disabled-ash: #b3b3b3;
  --color-deep-black: #000000;
  --color-hero-gradient: #116eee;
  --gradient-hero-gradient: linear-gradient(90deg, #116eee, #11ee92, #0ef076);

  /* Typography — Font Families */
  --font-nista: 'Nista', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.14;
  --text-display: 40px;
  --leading-display: 1.14;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;
  --font-weight-extrabold: 800;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40-60px;
  --card-padding: 20px;
  --element-gap: 8-20px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-2xl: 16px;
  --radius-3xl: 45.04px;

  /* Named Radii */
  --radius-inputs: 5px;
  --radius-buttons: 45.04px;
  --radius-navitems: 16px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ocean-blue: #116eee;
  --color-spring-green: #11ee92;
  --color-sky-tint: #87b6f6;
  --color-light-bluewash: #b8d4fa;
  --color-electric-cyan: #06d2ff;
  --color-action-red: #fa3746;
  --color-mellow-yellow: #ffcf00;
  --color-pure-white: #ffffff;
  --color-cloud-gray: #f2f7fd;
  --color-border-fog: #d6dee6;
  --color-text-anthracite: #252b2f;
  --color-slate-blue: #666e7;
  --color-disabled-ash: #b3b3b3;
  --color-deep-black: #000000;
  --color-hero-gradient: #116eee;

  /* Typography */
  --font-nista: 'Nista', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body: 14px;
  --leading-body: 1.5;
  --text-body-lg: 16px;
  --leading-body-lg: 1.5;
  --text-subheading: 18px;
  --leading-subheading: 1.33;
  --text-heading: 24px;
  --leading-heading: 1.2;
  --text-heading-lg: 36px;
  --leading-heading-lg: 1.14;
  --text-display: 40px;
  --leading-display: 1.14;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-28: 28px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 5px;
  --radius-2xl: 16px;
  --radius-3xl: 45.04px;

  /* Shadows */
  --shadow-subtle: rgba(0, 0, 0, 0.1) 0px 1px 2px 0px;
}
```
