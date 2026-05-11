# New Genre — Style Reference
> Shifting Gradual Horizon — a continuous, subtle color transition across surfaces, like watching a sunrise or sunset unfold.

**Theme:** light

New Genre evokes a serene, almost academic atmosphere through subtle color gradients and precise typography. The core is a unique gradient background that shifts from deep, muted tones to soft, almost ethereal lightness, underpinning minimalist content blocks. Typography relies on custom fonts with generous letter-spacing, particularly noticeable in headlines, signaling thoughtfulness and understated authority rather than bold declarations. Interactive elements are sparingly defined, primarily through rounded shapes and light borders, maintaining a sense of quiet professionalism.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Ebon Depth | `#000000` | `--color-ebon-depth` | Primary text, headers, prominent UI elements, icon fill — anchors the gradients with stark contrast. |
| Whisper White | `#ffffff` | `--color-whisper-white` | Background for clean content sections, inverse text on dark backgrounds, active elements in navigation — creates clear content islands on the gradient canvas. |
| Midnight Oil Stain | `#1e1310` | `--color-midnight-oil-stain` | Darkest background for footer sections — grounds the site with a rich, almost black earth tone. |
| Onyx Shadow | `#0c1018` | `--color-onyx-shadow` | Main body text, input fields, prominent text — a very dark gray that provides high contrast without being pure black. |
| Mist Gray | `#9e9fa3` | `--color-mist-gray` | Subtle secondary text, border elements, placeholder text — used for less prominent information, allowing primary content to stand out. |
| Steel Glimmer | `#6d7074` | `--color-steel-glimmer` | Desaturated gray for some headings — provides a softer emphasis compared to Ebon Depth. |
| Sky Gradient | `linear-gradient(rgb(40, 14, 1) 0%, rgb(24, 38, 68) 15.2608%, rgb(90, 118, 159) 30.284%, rgb(135, 161, 196) 43.3787%, rgb(193, 211, 230) 58.8313%, rgb(254, 249, 225) 79.7139%, rgb(247, 243, 240) 100%)` | `--color-sky-gradient` | Primary page background, hero section — shifts from deep, burnt umber through cool blues to soft, pale gold, creating a dynamic, subtle backdrop that feels vast and atmospheric. |
| Amber Glow | `radial-gradient(75% 300% at 109.6% 147.1%, rgb(255, 230, 0) 0%, rgb(237, 148, 84) 29.5837%, rgba(153, 161, 175, 0.06) 100%)` | `--color-amber-glow` | Subtle accent for ephemeral elements, often with transparency — its soft luminosity is a counterpoint to the primary gradient. |
| Sunset Gradient | `linear-gradient(rgba(247, 243, 240, 0) 0%, rgba(241, 189, 122, 0.97) 17.3899%, rgb(252, 190, 109) 32.9462%, rgb(228, 108, 68) 51.4622%, rgb(84, 37, 18) 78.2939%, rgb(30, 19, 16) 100%)` | `--color-sunset-gradient` | Decorative background gradient used for visual breaks — transitions from transparent through fiery oranges and reds to a deep, earthy brown, adding warmth and energy. |
| Earthfire Gradient | `linear-gradient(rgb(30, 19, 16) 25.1883%, rgb(144, 60, 39) 50.2763%, rgb(228, 108, 68) 76.0487%, rgb(237, 148, 84) 100%)` | `--color-earthfire-gradient` | Rich, warm gradient for sections requiring strong visual presence — deep browns and oranges signifying grounding and energy. |

## Tokens — Typography

### Serrif Condensed Regular — Display headlines and primary page titles — its condensed form and generous negative letter-spacing (-0.02em = -1.44px at 72px) create a distinctive, slightly formal and precise look. · `--font-serrif-condensed-regular`
- **Substitute:** IBM Plex Serif
- **Weights:** 400
- **Sizes:** 64px, 72px
- **Line height:** 1.05
- **Letter spacing:** -1.44
- **Role:** Display headlines and primary page titles — its condensed form and generous negative letter-spacing (-0.02em = -1.44px at 72px) create a distinctive, slightly formal and precise look.

### Saans Variable — Versatile all-purpose sans-serif for body text, subheadings, and UI elements — its variable nature and consistent negative letter-spacing (-0.01em = -0.12px at 12px) contribute to the compact, yet legible aesthetic. · `--font-saans-variable`
- **Substitute:** Inter Variable
- **Weights:** 300, 400, 500
- **Sizes:** 12px, 14px, 16px, 20px, 24px, 32px
- **Line height:** 1.00, 1.10, 1.15, 1.40
- **Letter spacing:** -0.12
- **Role:** Versatile all-purpose sans-serif for body text, subheadings, and UI elements — its variable nature and consistent negative letter-spacing (-0.01em = -0.12px at 12px) contribute to the compact, yet legible aesthetic.

### Saans Medium — Specific use for input fields, providing slight visual differentiation from other Saans weights. The subtle letter-spacing maintains consistency. · `--font-saans-medium`
- **Substitute:** Inter Medium
- **Weights:** 400, 570
- **Sizes:** 16px
- **Line height:** 1.00
- **Letter spacing:** -0.16
- **Role:** Specific use for input fields, providing slight visual differentiation from other Saans weights. The subtle letter-spacing maintains consistency.

### Saans Regular — Used for standard body text, featuring a slightly lighter weight and increased line height for enhanced readability in paragraphs. · `--font-saans-regular`
- **Substitute:** Inter Regular
- **Weights:** 380
- **Sizes:** 16px
- **Line height:** 1.30
- **Letter spacing:** -0.16
- **Role:** Used for standard body text, featuring a slightly lighter weight and increased line height for enhanced readability in paragraphs.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.2 | — | `--text-caption` |
| body | 16px | 1.3 | -0.16px | `--text-body` |
| subheading | 20px | 1.15 | -0.2px | `--text-subheading` |
| heading | 32px | 1.15 | -0.32px | `--text-heading` |
| display-sm | 64px | 1.05 | -1.28px | `--text-display-sm` |
| display | 72px | 1.05 | -1.44px | `--text-display` |

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
| 24 | 24px | `--spacing-24` |
| 26 | 26px | `--spacing-26` |
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 52 | 52px | `--spacing-52` |
| 56 | 56px | `--spacing-56` |
| 64 | 64px | `--spacing-64` |

### Border Radius

| Element | Value |
|---------|-------|
| buttons | 50px |
| default | 8px |
| components | 16px |
| pillButtons | 90px |

### Layout

- **Section gap:** 48-52px
- **Card padding:** 16-32px
- **Element gap:** 6-24px

## Components

### Navigation Link
**Role:** Interactive text link

Text only, Saans Variable weight 400 at 12px, color Ebon Depth #000000. Underline appears on hover.

### Subtle Accent Button
**Role:** Ghost button with subtle background

Background rgba(153, 161, 175, 0.06), text Ebon Depth #000000, 90px border-radius (pill shape). Padding 16px vertical, 24px horizontal. Typography Saans Variable, often weight 400.

### Transparent Header Button
**Role:** Navigation button or inline action

Transparent background, text Mist Gray #9e9fa3, no explicit border-radius (inherits 0px), 0px padding. Typography Saans Variable, weight 400.

### Round Input Field
**Role:** User input field

Background rgba(153, 161, 175, 0.06), text Onyx Shadow #0c1018, 50px border-radius. Padding 16px all sides. Typography Saans Medium, weight 570 or 400 at 16px.

### Text Input Field
**Role:** Standard text input

Transparent background, text Onyx Shadow #0c1018, 0px border-radius. No explicit padding (likely inherited or minimal). Typography Saans Medium, weight 570 or 400 at 16px.

### Work Section Header
**Role:** Primary section title

Serrif Condensed Regular, weight 400, sizes 64px or 72px, line-height 1.05, letter-spacing -1.44px. Color Ebon Depth #000000 on light backgrounds or Whisper White #ffffff on dark gradient sections.

### Process Step Card
**Role:** Informational card outlining a step

White background, with Onyx Shadow #0c1018 text for headings and body. Features 16px border-radius. Vertical padding likely 32px, horizontal 24px. The primary text uses Saans Variable at 16px, weight 400 with -0.16px letter-spacing.

### Cookie Consent Banner
**Role:** Small, bottom-right notification

Background white, 8px border-radius. Text Onyx Shadow #0c1018, with body text Saans Variable 12px, weight 400. Contains an 'Okay' button with 50px radius and transparent background.

## Do's and Don'ts

### Do
- Prioritize the Sky Gradient as the primary background for full-page or hero segments to establish the atmospheric and shifting visual identity.
- Use Serrif Condensed Regular with -0.02em letter-spacing for all significant headlines to emphasize precision and a slightly formal tone.
- Maintain a clear hierarchy with Ebon Depth #000000 or Onyx Shadow #0c1018 for primary text and Mist Gray #9e9fa3 for secondary information.
- Apply 90px border-radius for all primary action buttons ('pill buttons') and 50px radius for input fields, establishing a soft, approachable interaction style.
- Ensure consistent horizontal padding of 24px for all major content blocks and card elements to maintain a structured, spacious feel.
- Leverage the Saans Variable font family for all body, subheading, and UI text, ensuring its specific negative letter-spacing for a tight, refined look.

### Don't
- Avoid harsh, solid background colors; instead, opt for gradients or Whisper White #ffffff to preserve the site's ethereal quality.
- Do not use overly bold or heavy font weights; the system relies on lighter weights like Saans Variable 300-500 and Serrif Condensed Regular 400.
- Refrain from using strong, single-color accents; instead, any accent should be subtle, transparent, or part of a larger gradient.
- Do not introduce sharp corners or small radii on interactive elements; all buttons and inputs should adhere to 50px or 90px border-radius.
- Avoid dense, information-heavy sections without adequate section gaps (48-52px) or element gaps (6-24px); maintain a compact yet breathable layout.
- Do not use default browser link styling; ensure all links use Saans Variable and are styled consistently with the navigation links or body text.

## Imagery

The site uses stylized, artistic product photography or conceptual imagery. These are not typical product shots but rather abstract representations — like the botanical images showing growth in the 'process' section. They are meticulously arranged against clean white or softly blurred backgrounds, often masked with subtle transparency or soft edges, focusing on visual metaphor rather than literal depiction. The style prioritizes atmosphere and sophisticated concept over direct product showcasing, reinforcing the studio's design and strategic capabilities. Icons, if present, are likely minimal and monochromatic, adhering to the restrained aesthetic.

## Agent Prompt Guide

**Quick Color Reference:**
- Text (Primary): #0c1018
- Background (Sections): #ffffff
- Background (Hero/Page): #280e01 (start of Sky Gradient)
- Hint Text/Border: #9e9fa3
- Footer Background: #1e1310

**Example Component Prompts:**
1. Create a hero section: full-bleed background using the Sky Gradient. Place a heading in the center: Serif Condensed Regular, weight 400, 72px, line-height 1.05, letter-spacing -1.44px, color Whisper White #ffffff. Position a 'Our work' button 52px from the bottom-left edge, using the Subtle Accent Button style.
2. Design a 'Process Step Card': background Whisper White #ffffff, 16px border-radius, 32px vertical padding, 24px horizontal padding. Include a subheading: Saans Variable, weight 500, 24px, line-height 1.15, letter-spacing -0.24px, color Onyx Shadow #0c1018. Followed by body text: Saans Regular, weight 380, 16px, line-height 1.3, letter-spacing -0.16px, color Onyx Shadow #0c1018.
3. Implement a primary action button: text 'Sign me up', background rgba(153, 161, 175, 0.06), 90px border-radius, padding 16px vertical and 24px horizontal. Typography Saans Variable, weight 400, 16px, letter-spacing -0.16px, color Ebon Depth #000000.
4. Generate a clean input field: background rgba(153, 161, 175, 0.06), 50px border-radius, padding 16px all sides. Placeholder text in Mist Gray #9e9fa3, typography Saans Medium, weight 570, 16px, color Onyx Shadow #0c1018.
5. Create a standard link: text 'Artificial Intelligence', color Ebon Depth #000000, typography Saans Variable, weight 400, 14px, letter-spacing -0.14px. Underline on hover.

## Similar Brands

- **Huge Inc.** — Employs spacious, clean layouts with strong typography and subtle gradients for a sophisticated digital agency feel.
- **Pentagram** — Focuses on exceptional typography and minimal color palettes, letting content and form speak for themselves, similar to New Genre's atmospheric approach.
- **AKQA** — Uses large, impactful headlines, a restrained color palette, and a blend of full-bleed backgrounds with structured content areas to convey a sense of modern design authority.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-ebon-depth: #000000;
  --color-whisper-white: #ffffff;
  --color-midnight-oil-stain: #1e1310;
  --color-onyx-shadow: #0c1018;
  --color-mist-gray: #9e9fa3;
  --color-steel-glimmer: #6d7074;
  --color-sky-gradient: #280e01;
  --gradient-sky-gradient: linear-gradient(rgb(40, 14, 1) 0%, rgb(24, 38, 68) 15.2608%, rgb(90, 118, 159) 30.284%, rgb(135, 161, 196) 43.3787%, rgb(193, 211, 230) 58.8313%, rgb(254, 249, 225) 79.7139%, rgb(247, 243, 240) 100%);
  --color-amber-glow: #ffe600;
  --gradient-amber-glow: radial-gradient(75% 300% at 109.6% 147.1%, rgb(255, 230, 0) 0%, rgb(237, 148, 84) 29.5837%, rgba(153, 161, 175, 0.06) 100%);
  --color-sunset-gradient: #f7f3f0;
  --gradient-sunset-gradient: linear-gradient(rgba(247, 243, 240, 0) 0%, rgba(241, 189, 122, 0.97) 17.3899%, rgb(252, 190, 109) 32.9462%, rgb(228, 108, 68) 51.4622%, rgb(84, 37, 18) 78.2939%, rgb(30, 19, 16) 100%);
  --color-earthfire-gradient: #1e1310;
  --gradient-earthfire-gradient: linear-gradient(rgb(30, 19, 16) 25.1883%, rgb(144, 60, 39) 50.2763%, rgb(228, 108, 68) 76.0487%, rgb(237, 148, 84) 100%);

  /* Typography — Font Families */
  --font-serrif-condensed-regular: 'Serrif Condensed Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-variable: 'Saans Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-medium: 'Saans Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-regular: 'Saans Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.15;
  --tracking-subheading: -0.2px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.32px;
  --text-display-sm: 64px;
  --leading-display-sm: 1.05;
  --tracking-display-sm: -1.28px;
  --text-display: 72px;
  --leading-display: 1.05;
  --tracking-display: -1.44px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-w380: 380;
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-w570: 570;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Layout */
  --section-gap: 48-52px;
  --card-padding: 16-32px;
  --element-gap: 6-24px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;
  --radius-full-2: 90px;

  /* Named Radii */
  --radius-buttons: 50px;
  --radius-default: 8px;
  --radius-components: 16px;
  --radius-pillbuttons: 90px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-ebon-depth: #000000;
  --color-whisper-white: #ffffff;
  --color-midnight-oil-stain: #1e1310;
  --color-onyx-shadow: #0c1018;
  --color-mist-gray: #9e9fa3;
  --color-steel-glimmer: #6d7074;
  --color-sky-gradient: #280e01;
  --color-amber-glow: #ffe600;
  --color-sunset-gradient: #f7f3f0;
  --color-earthfire-gradient: #1e1310;

  /* Typography */
  --font-serrif-condensed-regular: 'Serrif Condensed Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-variable: 'Saans Variable', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-medium: 'Saans Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-saans-regular: 'Saans Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.2;
  --text-body: 16px;
  --leading-body: 1.3;
  --tracking-body: -0.16px;
  --text-subheading: 20px;
  --leading-subheading: 1.15;
  --tracking-subheading: -0.2px;
  --text-heading: 32px;
  --leading-heading: 1.15;
  --tracking-heading: -0.32px;
  --text-display-sm: 64px;
  --leading-display-sm: 1.05;
  --tracking-display-sm: -1.28px;
  --text-display: 72px;
  --leading-display: 1.05;
  --tracking-display: -1.44px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-26: 26px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-52: 52px;
  --spacing-56: 56px;
  --spacing-64: 64px;

  /* Border Radius */
  --radius-lg: 8px;
  --radius-2xl: 16px;
  --radius-full: 50px;
  --radius-full-2: 90px;
}
```
