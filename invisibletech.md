# Invisibletech — Style Reference
> Whiteboard precision with colored ink

**Theme:** light

Invisibletech employs a stark, minimalist aesthetic with a clean white canvas broken by strong typographic hierarchy and punctuated by a precise, functional use of color. UI elements are generally light and ethereal, relying on subtle borders and high contrast text rather than heavy fills or shadows. The overall impression is one of clarity, precision, and a somewhat academic or technical understated confidence, with strategic color accents guiding interaction and attention.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Carbon Black | `#0f0f0f` | `--color-carbon-black` | Primary text, darkest backgrounds, bold borders and dividers, prominent icon fills |
| Pure White | `#ffffff` | `--color-pure-white` | Page backgrounds, card surfaces, ghost button text, essential icon fills |
| Dark Wolf | `#222222` | `--color-dark-wolf` | Secondary text, solid button text, prominent icon strokes |
| Light Cloud | `#efefef` | `--color-light-cloud` | Subtle button backgrounds, light surface backgrounds, soft element borders |
| Muted Stone | `#606060` | `--color-muted-stone` | Helper text, muted heading details, subtle icon strokes |
| Ash Gray | `#4c4c4c` | `--color-ash-gray` | Body text, input text, ghost button borders, subtle icon fills |
| Silver Mist | `#b2b2b2` | `--color-silver-mist` | Hairline borders, disabled text, low-emphasis information |
| Pale Gray | `#dbdbdb` | `--color-pale-gray` | Lightest borders, section dividers |
| Slate Dust | `#898989` | `--color-slate-dust` | Input placeholders, disabled element text |
| Blue Sapphire | `#0c76fe` | `--color-blue-sapphire` | Blue decorative accent for icons, marks, and small graphic details. Do not promote it to the primary CTA color |
| Sky Tint | `#e6f1ff` | `--color-sky-tint` | Soft section background, alternate surface, and quiet card fill. Do not promote it to the primary CTA color |
| Hyper Citrus | `#dcf58f` | `--color-hyper-citrus` | Primary call-to-action background, active navigation indicator — a vibrant, high-energy accent for key interactions |
| Laser Pink | `#e37de1` | `--color-laser-pink` | Decorative background splashes, secondary accent highlights |
| Twilight Violet | `#8e8ef6` | `--color-twilight-violet` | Decorative background splashes, secondary accent highlights |

## Tokens — Typography

### Apk Galeria — Dominant display and body typeface. Its extended character set and precise tracking create a confident yet approachable tone. Used for all primary content, headings, and interactive elements, defining the site's distinct typographic voice. · `--font-apk-galeria`
- **Substitute:** Inter
- **Weights:** 400, 500
- **Sizes:** 12px, 14px, 16px, 18px, 20px, 22px, 24px, 28px, 36px, 48px, 52px, 64px
- **Line height:** 1.00, 1.10, 1.20, 1.40, 1.43, 1.50
- **Letter spacing:** -0.0300em, -0.0240em, -0.0180em, -0.0140em, -0.0110em, -0.0100em, -0.0090em, 0.0200em, 0.0230em, 0.0270em
- **Role:** Dominant display and body typeface. Its extended character set and precise tracking create a confident yet approachable tone. Used for all primary content, headings, and interactive elements, defining the site's distinct typographic voice.

### Apkpraktikal — Secondary typeface for detailed information, labels, and small text. Its higher letter-spacing provides distinctiveness and legibility at smaller sizes, particularly for navigation and button labels, complementing the primary display font with a more technical feel. · `--font-apkpraktikal`
- **Substitute:** IBM Plex Sans
- **Weights:** 400, 700
- **Sizes:** 12px, 13px, 14px, 16px, 20px
- **Line height:** 1.00, 1.20, 1.40
- **Letter spacing:** 0.0300em, 0.0340em, 0.0380em, 0.0400em, 0.0500em, 0.1200em, 0.1400em
- **Role:** Secondary typeface for detailed information, labels, and small text. Its higher letter-spacing provides distinctiveness and legibility at smaller sizes, particularly for navigation and button labels, complementing the primary display font with a more technical feel.

### Karla — Used sparingly for specific body text contexts, providing a high-readability alternative possibly for long-form content or accessible text blocks. Its neutral, friendly demeanor contrasts with the more stylized custom fonts. · `--font-karla`
- **Substitute:** Karla
- **Weights:** 400
- **Sizes:** 16px
- **Line height:** 1.40
- **Letter spacing:** normal
- **Role:** Used sparingly for specific body text contexts, providing a high-readability alternative possibly for long-form content or accessible text blocks. Its neutral, friendly demeanor contrasts with the more stylized custom fonts.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.4 | 0.38px | `--text-caption` |
| body-sm | 14px | 1.4 | 0.23px | `--text-body-sm` |
| body | 16px | 1.4 | -0.14px | `--text-body` |
| subheading | 20px | 1.4 | -0.18px | `--text-subheading` |
| heading-sm | 28px | 1.2 | -0.28px | `--text-heading-sm` |
| heading | 36px | 1.2 | -0.36px | `--text-heading` |
| heading-lg | 48px | 1.1 | -0.48px | `--text-heading-lg` |
| display | 64px | 1 | -0.64px | `--text-display` |

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
| 72 | 72px | `--spacing-72` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |
| 160 | 160px | `--spacing-160` |
| 240 | 240px | `--spacing-240` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 0px |
| pills | 9999px |
| badges | 0px |
| inputs | 0px |
| buttons | 9999px |

### Layout

- **Section gap:** 64px
- **Card padding:** 24px
- **Element gap:** 24px

## Components

### Standard Button
**Role:** Default interactive button for secondary actions or non-primary calls to action.

Background: Light Cloud (#efefef), Text: Ash Gray (#4c4c4c), Border: 0px, Radius: 0px, Padding: 32px all around or 24px all around.

### Primary Action Button
**Role:** High-emphasis button for critical calls to action.

Background: Hyper Citrus (#dcf58f), Text: Carbon Black (#0f0f0f), Border: 0px, Radius: 9999px, Padding: 8px vertical, 20px horizontal.

### Ghost Button
**Role:** Low-emphasis button, often for secondary actions, text links, or navigation.

Background: transparent (rgba(255, 255, 255, 0)), Text: Carbon Black (#0f0f0f), Border: 1px solid Carbon Black (#0f0f0f), Radius: 9999px, Padding: 8px vertical, 20px horizontal.

### Dark Filled Button
**Role:** Alternative primary action or prominent secondary button, typically used in monochrome areas.

Background: Carbon Black (#0f0f0f), Text: Pure White (#ffffff), Border: 0px, Radius: 9999px, Padding: 8px vertical, 20px horizontal.

### Information Card
**Role:** Container for information, often used in grids or listings.

Background: transparent (rgba(0, 0, 0, 0)), Border: 0px, Radius: 0px, Padding: 0px all around. This card is visually defined by its content and implied structure.

### Elevated Info Card
**Role:** Card with a subtle background and padding, indicating a distinct content block or interactive area.

Background: transparent white (rgba(255, 255, 255, 0.7)), Border: 0px, Radius: 0px, Padding: 24px all around.

### Rounded Tag/Pill
**Role:** Small, distinct labels or filters.

Background: Carbon Black (#0f0f0f), Text: Pure White (#ffffff), Border: 0px, Radius: 9999px, Padding: 8px vertical, 20px horizontal.

### Text Input (Default)
**Role:** Standard form input field.

Background: transparent (rgba(0, 0, 0, 0)), Text: Ash Gray (#4c4c4c), Border: 1px solid Carbon Black (#0f0f0f) at bottom, Radius: 0px, Padding: 10px.

### Navigation Link
**Role:** Top-level navigation item or secondary link within content.

Text: Carbon Black (#0f0f0f), Underline: 0px, Hover: implied color change or interaction. Background: transparent (rgba(0, 0, 0, 0)), Border: 0px, Radius: 0px, Padding: 0px.

## Do's and Don'ts

### Do
- Prioritize Carbon Black (#0f0f0f) for all primary text and critical elements to maintain high contrast and clarity against Pure White (#ffffff) backgrounds.
- Use Hyper Citrus (#dcf58f) exclusively for primary calls-to-action, active navigation indicators, and key focus elements to telegraph importance.
- Apply 9999px (pill shape) radius for all interactive buttons and tags to create a consistent, modern yet rounded aesthetic.
- Utilize Apkgaleria for all headlines and content blocks, varying weights and letter-spacing precisely as defined in `typography` to establish typographic hierarchy.
- Implement a 24px `elementGap` for horizontal and vertical spacing between most interactive components or distinct content blocks.
- Maintain a transparent (rgba(0,0,0,0)) or very light (#efefef, #e6f1ff) background for cards and containers, relying on content and borders to define their presence rather than heavy fills or shadows.
- Employ the Blue Sapphire (#0c76fe) specifically for interactive link states or selected navigation items to denote clickable functionality and active status.

### Don't
- Do not use saturated colors other than Hyper Citrus (#dcf58f), Blue Sapphire (#0c76fe), Laser Pink (#e37de1), or Twilight Violet (#8e8ef6) within the main UI. Other colors are for decorative graphics only.
- Avoid applying heavy shadows or complex gradients unless explicitly defined; the design system favors flat surfaces and clear contrasts.
- Do not introduce additional border radii beyond 9999px (for pills) or 0px (for most elements) without explicit justification, as sharp corners are a key aesthetic.
- Resist using bold font weights for body text; rely on appropriate light or regular weights from Apk Galeria or Karla for readability and a lightweight feel.
- Do not deviate from the defined letter-spacing values in `typography`; precise tracking is crucial for the distinct feel of the custom fonts.
- Avoid overlaying text on complex backgrounds; prefer text on solid Pure White (#ffffff) or Carbon Black (#0f0f0f) for readability and clean presentation.
- Do not use blocky or square buttons for primary calls-to-action; all primary CTAs should utilize the 9999px radius and Hyper Citrus background.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Pure White Canvas | `#ffffff` | Primary page background, most expansive surface areas. |
| 1 | Cloud Surface | `#efefef` | Secondary background for sections or softer cards, offering a slight visual shift from the canvas. |
| 2 | Sky Tinted Surface | `#e6f1ff` | Specific informational or interactive areas, denoting a different semantic grouping or soft focus. |

## Elevation

The design intentionally minimizes the use of shadows. Elevation is primarily achieved through changes in background color, strong typographic hierarchy, and the use of borders. When elements appear 'elevated' (like prompt pop-ups or focused states), they might use a slightly darker transparent background layer (e.f., #0f0f0fb3) or a subtle 1px border shift to imply depth, rather than traditional box-shadows. This choice emphasizes a flat, crisp UI.

## Imagery

The site uses a mix of minimal line-art illustrations and abstract, often geometric, graphics. Photography is absent. Illustrations are typically light-colored lines or filled shapes, occasionally featuring subtle color washes (#e37de1, #8e8ef6). Icons are outlined with a consistent stroke weight, predominantly in Carbon Black (#0f0f0f) or Ash Gray (#4c4c4c). Imagery serves primarily as decorative atmosphere and explanatory content, occupying significant visual space in some sections but always feeling lightweight and integrated rather than heavy. Product screenshots, when present, are clean, monochrome, and bordered, emphasizing the UI, not lifestyle.

## Layout

The page structure is a mix of full-bleed and max-width contained sections, centered around a 1200px implicit maximum width for core content. The hero section is full-bleed, featuring a centered headline and subtext, often with abstract graphics around it. Sections alternate between pure white backgrounds and very subtle light gray or tinted backgrounds (#e6f1ff, #efefef), creating a gentle visual rhythm. Content is generally arranged in centered stacks or two-column layouts with text and visuals, favoring clear horizontal division. A 3-column card grid is used for features. Navigation is a sticky top bar with clearly segmented links and a distinct primary action button. Density is comfortable, with ample whitespace and clear separation between elements and sections.

## Agent Prompt Guide

### Quick Color Reference
text: #0f0f0f
background: #ffffff
border: #dbdbdb
accent: #0c76fe
primary action: #dcf58f (filled action)

### 3-5 Example Component Prompts
1. Create a hero section with a centered headline: 'Advancing AI models from frontier innovation to' in Apk Galeria, 64px, weight 400, #0f0f0f, letter-spacing -0.64px. Below it, a subtext 'We've trained over 80%...' in Apk Galeria, 20px, weight 400, #4c4c4c, letter-spacing -0.18px. Include a 'Book a Demo' button: background #dcf58f, text #0f0f0f, 9999px radius, 8px vertical 20px horizontal padding, font Apk Galeria, 14px, weight 700, letter-spacing 0.14em.
2. Design a feature card: background transparent (rgba(255, 255, 255, 0.7)), padding 24px, 0px border-radius. Inside, a subheading 'Synapse' in Apk Galeria, 28px, weight 400, #0f0f0f, letter-spacing -0.28px, and a body text 'Run rigorous evaluation...' in Apk Galeria, 16px, weight 400, #4c4c4c, letter-spacing -0.14px.
3. Implement a ghost button for 'Explore': background transparent (rgba(255, 255, 255, 0)), text #0f0f0f, 1px solid #0f0f0f border, 9999px radius, 8px vertical 20px horizontal padding, font Apk Galeria, 14px, weight 700, letter-spacing 0.14em.
4. Show a navigation link: 'Industries' in Apk Galeria, 16px, weight 400, #0f0f0f, letter-spacing -0.14px. On hover, change text color to Blue Sapphire (#0c76fe).
5. Create a standard input field: background transparent (rgba(0,0,0,0)), text #4c4c4c, 1px solid #0f0f0f bottom border, 0px radius, 10px padding, placeholder text in Slate Dust (#898989), font Apk Galeria, 16px, weight 400, letter-spacing -0.14px.

## Similar Brands

- **Airtable** — Shares a clean, grid-based layout approach with a strong typographic foundation and minimal, functional use of color accents on a largely white canvas.
- **Linear** — Exhibits a precise, detail-oriented design with understated neutrals, sharp corners, and a focus on highly legible type with careful tracking and strategic, limited color accents for interaction (though Linear uses dark mode more).
- **Vercel** — Features a similar lightweight component style, strong typographic hierarchy with distinctive custom fonts (or a custom feel), and a preference for borders and subtle background shifts over heavy shadows for UI definition.
- **Stripe (documentation)** — Mimics the technical clarity, high contrast text on white, and structured content presentation, using color sparingly for code examples or critical calls to action.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-carbon-black: #0f0f0f;
  --color-pure-white: #ffffff;
  --color-dark-wolf: #222222;
  --color-light-cloud: #efefef;
  --color-muted-stone: #606060;
  --color-ash-gray: #4c4c4c;
  --color-silver-mist: #b2b2b2;
  --color-pale-gray: #dbdbdb;
  --color-slate-dust: #898989;
  --color-blue-sapphire: #0c76fe;
  --color-sky-tint: #e6f1ff;
  --color-hyper-citrus: #dcf58f;
  --color-laser-pink: #e37de1;
  --color-twilight-violet: #8e8ef6;

  /* Typography — Font Families */
  --font-apk-galeria: 'Apk Galeria', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apkpraktikal: 'Apkpraktikal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.38px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.23px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.14px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.28px;
  --text-heading: 36px;
  --leading-heading: 1.2;
  --tracking-heading: -0.36px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-bold: 700;

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
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 24px;
  --element-gap: 24px;

  /* Border Radius */
  --radius-full: 50px;
  --radius-full-2: 9999px;

  /* Named Radii */
  --radius-cards: 0px;
  --radius-pills: 9999px;
  --radius-badges: 0px;
  --radius-inputs: 0px;
  --radius-buttons: 9999px;

  /* Surfaces */
  --surface-pure-white-canvas: #ffffff;
  --surface-cloud-surface: #efefef;
  --surface-sky-tinted-surface: #e6f1ff;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-carbon-black: #0f0f0f;
  --color-pure-white: #ffffff;
  --color-dark-wolf: #222222;
  --color-light-cloud: #efefef;
  --color-muted-stone: #606060;
  --color-ash-gray: #4c4c4c;
  --color-silver-mist: #b2b2b2;
  --color-pale-gray: #dbdbdb;
  --color-slate-dust: #898989;
  --color-blue-sapphire: #0c76fe;
  --color-sky-tint: #e6f1ff;
  --color-hyper-citrus: #dcf58f;
  --color-laser-pink: #e37de1;
  --color-twilight-violet: #8e8ef6;

  /* Typography */
  --font-apk-galeria: 'Apk Galeria', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-apkpraktikal: 'Apkpraktikal', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-karla: 'Karla', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.4;
  --tracking-caption: 0.38px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.4;
  --tracking-body-sm: 0.23px;
  --text-body: 16px;
  --leading-body: 1.4;
  --tracking-body: -0.14px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 28px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.28px;
  --text-heading: 36px;
  --leading-heading: 1.2;
  --tracking-heading: -0.36px;
  --text-heading-lg: 48px;
  --leading-heading-lg: 1.1;
  --tracking-heading-lg: -0.48px;
  --text-display: 64px;
  --leading-display: 1;
  --tracking-display: -0.64px;

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
  --spacing-72: 72px;
  --spacing-80: 80px;
  --spacing-120: 120px;
  --spacing-160: 160px;
  --spacing-240: 240px;

  /* Border Radius */
  --radius-full: 50px;
  --radius-full-2: 9999px;
}
```
