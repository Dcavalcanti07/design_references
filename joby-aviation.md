# Joby Aviation — Style Reference
> Skyward Glide

**Theme:** light

Joby Aviation's visual system evokes a sense of aspirational flight and advanced technology. The primary design language pairs deep, saturated blues with stark white typography, creating a high-contrast, almost nocturnal-but-optimistic feel. Large, asymmetric rounded forms in backgrounds and card elements suggest fluidity and motion, while the overall spaciousness and minimal use of decorative elements keep the focus on the product's promise.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Ink | `#0e1620` | `--color-midnight-ink` | Primary text, darkest backgrounds, interface borders |
| Cloud Whisper | `#f5f4df` | `--color-cloud-whisper` | Off-white for backgrounds, secondary text, button outlines, and subtle card surfaces |
| Skybound Blue | `#007ae5` | `--color-skybound-blue` | Dominant brand blue for primary backgrounds, full page sections, and active navigation indicators. Conveys innovation and optimism |
| Cosmic Violet | `#1c3f99` | `--color-cosmic-violet` | Brand accent for navigation, subtle surface backgrounds, and graphic elements. Used in conjunction with other blues |
| Sunset Orange | `#eb6110` | `--color-sunset-orange` | Accent for navigation elements and small graphic details |
| Horizon Blue | `#083e6f` | `--color-horizon-blue` | Outlined button borders when interacting with light backgrounds; also used for informational icons and input borders |
| Pale Peach | `#ffd9c9` | `--color-pale-peach` | Subtle accent for navigation backgrounds and decorative graphics |
| Shadow Grey | `#abab9c` | `--color-shadow-grey` | Used for card box shadows, providing a soft lift |

## Tokens — Typography

### JobyDisplay — Headlines and display text. The bold weights and precise tracking convey authority and a contemporary feel. · `--font-jobydisplay`
- **Substitute:** Inter
- **Weights:** 500, 550
- **Sizes:** 10px, 18px, 24px, 28px, 40px, 48px, 64px, 80px, 141px, 207px
- **Line height:** 1.00, 1.05, 1.20
- **Letter spacing:** -0.0300em, -0.0200em, -0.0100em
- **Role:** Headlines and display text. The bold weights and precise tracking convey authority and a contemporary feel.

### jobyText — Body text, navigation links, and badges. Its slightly condensed nature at smaller sizes maintains a structured, purposeful tone. · `--font-jobytext`
- **Substitute:** Inter
- **Weights:** 400, 450, 500, 550
- **Sizes:** 12px, 14px, 16px, 18px
- **Line height:** 0.89, 1.00, 1.20, 1.30, 1.40
- **Letter spacing:** -0.0200em, -0.0100em
- **Role:** Body text, navigation links, and badges. Its slightly condensed nature at smaller sizes maintains a structured, purposeful tone.

### Arial — Fallback and specific utility text, primarily for buttons and icons where system legibility is prioritized. · `--font-arial`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback and specific utility text, primarily for buttons and icons where system legibility is prioritized.

### Joby Sans Display — Used for specific body and icon text, featuring tighter tracking for a more compact impression. · `--font-joby-sans-display`
- **Substitute:** Inter
- **Weights:** 500
- **Sizes:** 12px
- **Line height:** 1.20
- **Letter spacing:** -0.0300em
- **Role:** Used for specific body and icon text, featuring tighter tracking for a more compact impression.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1 | -0.03px | `--text-caption` |
| body | 14px | 1.3 | -0.01px | `--text-body` |
| subheading | 18px | 1.4 | -0.01px | `--text-subheading` |
| heading-sm | 24px | 1.2 | -0.02px | `--text-heading-sm` |
| heading | 28px | 1.05 | -0.02px | `--text-heading` |
| heading-lg | 40px | 1.05 | -0.03px | `--text-heading-lg` |
| display | 64px | 1.05 | -0.03px | `--text-display` |

## Tokens — Spacing & Shapes

**Base unit:** 8px

**Density:** spacious

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 8 | 8px | `--spacing-8` |
| 16 | 16px | `--spacing-16` |
| 24 | 24px | `--spacing-24` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 56 | 56px | `--spacing-56` |
| 80 | 80px | `--spacing-80` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 16px |
| default | 8px |
| otherLarge | 147.6px |
| asymmetricCards | 160px 160px 0px 0px |

### Layout

- **Section gap:** 113px
- **Card padding:** 40px
- **Element gap:** 8px

## Components

### Ghost Navigation Button (Light Text)
**Role:** Interactive element for navigation or secondary actions, appearing on dark backgrounds.

Background: transparent (rgba(0, 0, 0, 0)), Text: Cloud Whisper (#f5f4df), Border: Cloud Whisper (#f5f4df), Radius: 0px, Padding: 0px.

### Ghost Navigation Button (Dark Text)
**Role:** Interactive element for navigation or secondary actions, appearing on light backgrounds.

Background: transparent (rgba(0, 0, 0, 0)), Text: Horizon Blue (#083e6f), Border: Horizon Blue (#083e6f), Radius: 0px, Padding: 0px.

### Feature Card (Blue BG)
**Role:** Container for showcasing features or information, using the primary brand blue.

Background: Skybound Blue (#007ae5), Text: Cloud Whisper (#f5f4df), Border Radius: 16px, Shadow: rgba(0, 0, 0, 0.3) 0px 16px 47.6px 0px, Padding: 0px. Headings use 'JobyDisplay' 550, body uses 'jobyText' 400.

### Hero Section Card
**Role:** Prominent card used in hero sections, often with asymmetric rounded corners.

Background: Skybound Blue (#007ae5), Border Radius: 160px 160px 0px 0px, Shadow: none, Padding: 0px 40px 0px 40px. Content within uses 'JobyDisplay' for titles and 'jobyText' for descriptive text, typically in Cloud Whisper.

### Ghost Input
**Role:** Input field for user entry, designed for dark backgrounds.

Background: transparent (rgba(0, 0, 0, 0)), Text/Placeholder: Cloud Whisper (#f5f4df), Border: Cloud Whisper (#f5f4df), Radius: 0px, Padding: 0px.

### Context Badge
**Role:** Small informational or labeling element.

Background: transparent (rgba(0, 0, 0, 0)), Text: Cloud Whisper (#f5f4df), Radius: 0px, Padding: 0px.

## Do's and Don'ts

### Do
- Always use Midnight Ink (#0e1620) for primary text on light backgrounds and Cloud Whisper (#f5f4df) for text on dark/brand backgrounds to maintain high contrast (16.4:1 AAA on Cloud Whisper).
- Employ JobyDisplay for all headings and JobyText for body copy, adjusting letter-spacing per size: tighter for display text (-0.0300em) and slightly looser for body text (-0.0100em).
- Utilize Skybound Blue (#007ae5) as the primary background color for immersive sections, conveying the brand's core identity.
- Apply 16px border-radius to standard cards and 160px 160px 0px 0px for distinctive, flowing card shapes in prominent areas.
- Maintain a spacious layout with a consistent elementGap of 8px and a sectionGap of approximately 113px for clear content separation.
- Use Horizon Blue (#083e6f) as the border color for outlined ghost buttons on light backgrounds, ensuring brand-aligned interactivity.
- Integrate expressive motion with ease timing and 0.4s duration for transitions like transform, visibility, and opacity to enhance perceived responsiveness.

### Don't
- Avoid using highly saturated colors for large text blocks; reserve them for accents or backgrounds.
- Do not use box-shadows on elements not explicitly defined with one; maintain a generally flat aesthetic unless an element needs distinct visual elevation (like the Feature Card's rgba(0, 0, 0, 0.3) 0px 16px 47.6px 0px).
- Do not deviate from the established font families and their respective weights; consistency is key to brand recognition.
- Refrain from tight spacing between content blocks or elements; maintain the spacious feel with the established elementGap and sectionGap values.
- Do not use generic system font Arial unless it's for specific, small utility components where JobyText doesn't fit the specified size range.
- Avoid arbitrary border radii; stick to the defined 16px, 8px, 160px, or 147.6px values for visual consistency and brand recognition.
- Never use primary brand colors like Skybound Blue or Cosmic Violet for primary action text or borders. Interactivity for primary actions is conveyed through ghost buttons with specific text/border colors (e.g., Cloud Whisper or Horizon Blue).

## Imagery

The visual language predominantly features high-contrast, moody photography showcasing an individual looking out of an aircraft window at a city skyline, emphasizing aspiration and cutting-edge travel. Imagery is often full-bleed or large-scale, providing an immersive experience. Product shots are not explicitly shown but implied. Iconography is minimal and appears as stroke-based and monochromatic, consistent with the overall clean UI. Imagery serves a decorative and atmospheric role, setting the brand's aspirational tone rather than explaining specific features.

## Layout

The page primarily utilizes a full-bleed layout, where background imagery and brand colors extend to the viewport edges, especially in the hero section. Content is typically centered within this full-bleed context. The hero section features a dramatic, large-scale image with a prominent, centered headline. Subsequent sections exhibit consistent vertical spacing, often switching between full-bleed brand color backgrounds (Skybound Blue) and white content areas. A loose, implicit grid is used for feature presentation, combining text and visuals. Navigation consists of a sticky top bar with minimal links.

## Agent Prompt Guide

Quick Color Reference:
text: #0e1620
background: #007ae5
border: #f5f4df
accent: #083e6f
primary action: #083e6f (outlined action border)

Example Component Prompts:
1. Create a hero section: full-bleed Skybound Blue (#007ae5) background, centered headline 'Skip traffic. Time to fly.' in JobyDisplay weight 550, size 80px, Cloud Whisper (#f5f4df) color, letter-spacing -0.03em. Max-width 1200px. Add a Ghost Navigation Button (Light Text) 'Investors' on the top right using JobyText weight 400, size 16px, transparent background, Cloud Whisper (#f5f4df) border and text.
2. Design a feature card: Background Skybound Blue (#007ae5), 16px border-radius, box-shadow rgba(0, 0, 0, 0.3) 0px 16px 47.6px 0px. Headline 'Technology that makes the dream possible' in JobyDisplay weight 500, size 24px, Cloud Whisper (#f5f4df). Body text 'Achieve seamless door to door travel with our innovative electric air taxi.' in jobyText weight 400, size 16px, Cloud Whisper (#f5f4df). No padding on card itself, content uses elementGap: 8px.
3. Implement a secondary navigation link: 'Discover the Experience' using jobyText weight 400, size 18px, Midnight Ink (#0e1620) text color, with a Horizon Blue (#083e6f) 1.5px solid border on hover, padding 15px top/right/bottom/left. Ensure base elementGap of 8px around it.

## Similar Brands

- **Archer Aviation** — Competitor in the advanced air mobility space, sharing a focus on aspirational imagery and high-tech feel.
- **Boom Supersonic** — Similar high-contrast and sophisticated branding for futuristic travel with a focus on dark backgrounds and vibrant accents.
- **Airbus** — Large-scale, aspirational imagery for a high-tech transportation company, with emphasis on clean layouts and minimal UI text.
- **Impossible Foods** — Uses full-bleed, moody photography with large, impactful typography, creating an immersive brand experience.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-ink: #0e1620;
  --color-cloud-whisper: #f5f4df;
  --color-skybound-blue: #007ae5;
  --color-cosmic-violet: #1c3f99;
  --color-sunset-orange: #eb6110;
  --color-horizon-blue: #083e6f;
  --color-pale-peach: #ffd9c9;
  --color-shadow-grey: #abab9c;

  /* Typography — Font Families */
  --font-jobydisplay: 'JobyDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jobytext: 'jobyText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-joby-sans-display: 'Joby Sans Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.03px;
  --text-body: 14px;
  --leading-body: 1.3;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.05;
  --tracking-heading: -0.02px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.03px;
  --text-display: 64px;
  --leading-display: 1.05;
  --tracking-display: -0.03px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w450: 450;
  --font-weight-medium: 500;
  --font-weight-w550: 550;

  /* Spacing */
  --spacing-unit: 8px;
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;

  /* Layout */
  --section-gap: 113px;
  --card-padding: 40px;
  --element-gap: 8px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 147.6px;
  --radius-full-2: 160px;

  /* Named Radii */
  --radius-cards: 16px;
  --radius-default: 8px;
  --radius-otherlarge: 147.6px;
  --radius-asymmetriccards: 160px 160px 0px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-ink: #0e1620;
  --color-cloud-whisper: #f5f4df;
  --color-skybound-blue: #007ae5;
  --color-cosmic-violet: #1c3f99;
  --color-sunset-orange: #eb6110;
  --color-horizon-blue: #083e6f;
  --color-pale-peach: #ffd9c9;
  --color-shadow-grey: #abab9c;

  /* Typography */
  --font-jobydisplay: 'JobyDisplay', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-jobytext: 'jobyText', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-joby-sans-display: 'Joby Sans Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1;
  --tracking-caption: -0.03px;
  --text-body: 14px;
  --leading-body: 1.3;
  --tracking-body: -0.01px;
  --text-subheading: 18px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.01px;
  --text-heading-sm: 24px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.02px;
  --text-heading: 28px;
  --leading-heading: 1.05;
  --tracking-heading: -0.02px;
  --text-heading-lg: 40px;
  --leading-heading-lg: 1.05;
  --tracking-heading-lg: -0.03px;
  --text-display: 64px;
  --leading-display: 1.05;
  --tracking-display: -0.03px;

  /* Spacing */
  --spacing-8: 8px;
  --spacing-16: 16px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-56: 56px;
  --spacing-80: 80px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 147.6px;
  --radius-full-2: 160px;
}
```
