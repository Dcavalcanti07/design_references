# Graphy — Style Reference
> Data on frosted glass

**Theme:** light

Graphy presents an airy, almost ethereal aesthetic, like data visualized on frosted glass. Its light, predominantly achromatic canvas is punctuated by subtle shadows and a signature vivid blue. Typography is compact and precise, maintaining a clear hierarchy without visual bulk. This system balances a soft, spacious feel with sharp, functional elements.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Canvas Ice | `#f2f4f8` | `--color-canvas-ice` | Primary page background, base card surfaces |
| Paper White | `#ffffff` | `--color-paper-white` | Elevated card surfaces, button backgrounds, modal backgrounds |
| Graphite Ink | `#000000` | `--color-graphite-ink` | Primary text, strong headings, prominent icons |
| Slate Blue | `#20295a` | `--color-slate-blue` | Secondary headings, section titles, rich dark accent |
| Action Blue | `#2e62ff` | `--color-action-blue` | Primary call-to-action buttons, active interactive elements, key brand accents |
| Mid-Tone Gray | `#666666` | `--color-mid-tone-gray` | Subtext, paragraph text, less prominent icons |
| Ghost Gray | `#c2c2c2` | `--color-ghost-gray` | Decorative strokes, disabled text, meta information |
| Light-touch Gray | `#999999` | `--color-light-touch-gray` | Helper text, subtle borders, placeholder text |
| Ocean Link | `#0099ff` | `--color-ocean-link` | Hyperlinks, interactive text that stands out |
| Dusty Violet | `#4a527a` | `--color-dusty-violet` | Muted text for announcements or secondary information |
| Form Fill | `#eeeeee` | `--color-form-fill` | Input field backgrounds, subtle inactive states |
| Transparent Blue Gradient | `linear-gradient(rgba(255, 255, 255, 0.3) 0%, rgba(76, 48, 237, 0.2) 100%)` | `--color-transparent-blue-gradient` | Subtle background gradient for hero sections or elevated elements, contributing to a frosted glass effect |
| Subtle Blue Wash Gradient | `linear-gradient(90deg, rgb(255, 255, 255) -11%, rgba(125, 128, 218, 0.8) 27%, rgb(125, 128, 218) 49.5953%, rgba(213, 213, 213, 0.8) 77.4775%, rgba(255, 255, 255, 0) 100%)` | `--color-subtle-blue-wash-gradient` | Complex background gradient for visual depth |

## Tokens — Typography

### sans-serif — sans-serif — detected in extracted data but not described by AI · `--font-sans-serif`
- **Weights:** 400
- **Sizes:** 12px
- **Line height:** 1.2
- **Role:** sans-serif — detected in extracted data but not described by AI

### Aeonik Medium — Headings and prominent display text. The medium weight with tight tracking gives titles a compact, confident presence without being overtly bold. · `--font-aeonik-medium`
- **Substitute:** Montserrat
- **Weights:** 400
- **Sizes:** 16px, 20px, 24px, 32px, 40px, 56px, 82px
- **Line height:** 0.85, 1.13, 1.15, 1.20, 1.35, 1.40
- **Letter spacing:** -0.0330em
- **Role:** Headings and prominent display text. The medium weight with tight tracking gives titles a compact, confident presence without being overtly bold.

### Aeonik Regular — Body text, links, and button labels. The custom features enhance legibility and offer a distinct typographic texture. · `--font-aeonik-regular`
- **Substitute:** Montserrat
- **Weights:** 400, 700
- **Sizes:** 12px, 14px, 16px, 18px, 22px
- **Line height:** 1.00, 1.05, 1.10, 1.20, 1.30, 1.35, 1.60, 1.83
- **Letter spacing:** -0.0440em at larger sizes, -0.0200em at smaller sizes
- **OpenType features:** `"blwf" on, "cv03" on, "cv04" on, "cv09" on, "cv11" on`
- **Role:** Body text, links, and button labels. The custom features enhance legibility and offer a distinct typographic texture.

### Aeonik Bold — Emphasis in headings or specific callouts. Used sparingly to ensure high impact where needed. · `--font-aeonik-bold`
- **Substitute:** Montserrat
- **Weights:** 700
- **Sizes:** 18px, 68px
- **Line height:** 1.05
- **Letter spacing:** normal
- **Role:** Emphasis in headings or specific callouts. Used sparingly to ensure high impact where needed.

### Inter — Fine print, meta information, and small functional text where economy of space and high legibility are paramount. · `--font-inter`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 12px, 14px
- **Line height:** 1.10, 1.20, 1.50
- **Letter spacing:** -0.0500em
- **Role:** Fine print, meta information, and small functional text where economy of space and high legibility are paramount.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 12px | 1.5 | -0.6px | `--text-caption` |
| body-sm | 14px | 1.2 | -0.56px | `--text-body-sm` |
| body | 16px | 1.35 | -0.7px | `--text-body` |
| subheading | 22px | 1.05 | -0.88px | `--text-subheading` |
| heading-sm | 32px | 1.2 | -1.056px | `--text-heading-sm` |
| heading | 56px | 1.13 | -1.848px | `--text-heading` |
| heading-lg | 68px | 1.05 | — | `--text-heading-lg` |
| display | 82px | 0.85 | -2.706px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 4 | 4px | `--spacing-4` |
| 6 | 6px | `--spacing-6` |
| 7 | 7px | `--spacing-7` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 16 | 16px | `--spacing-16` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 30 | 30px | `--spacing-30` |
| 32 | 32px | `--spacing-32` |
| 40 | 40px | `--spacing-40` |
| 48 | 48px | `--spacing-48` |
| 60 | 60px | `--spacing-60` |
| 80 | 80px | `--spacing-80` |
| 120 | 120px | `--spacing-120` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 40px |
| cards | 8px |
| input | 8px |
| buttons | 20px |
| containers | 16px |
| roundedElements | 70px |
| smallInteractive | 4px |

### Layout

- **Section gap:** 40px
- **Card padding:** 16px
- **Element gap:** 16px

## Components

### Primary Filled Button
**Role:** Main call to action.

Background: Action Blue (#2e62ff). Text: Graphite Ink (#000000). Border Radius: 20px. Padding: 16px vertical, 32px horizontal. Text uses Aeonik Regular, 16px, weight 400.

### Secondary Ghost Button
**Role:** Subtle alternative actions, often next to a primary button.

Background: Paper White (#ffffff) with 0.9 opacity. Text: Graphite Ink (#000000). Border Radius: 20px. Padding: 16px vertical, 32px horizontal. Text uses Aeonik Regular, 16px, weight 400.

### Outline Ghost Button (Product Announcement)
**Role:** Outlined button for secondary, less prominent, or informative actions.

Background: Paper White (#ffffff) with 0.6 opacity. Text: Ocean Link (#0099ff). Border Radius: 51px. Padding: 8px vertical, 17-25px horizontal. Text uses Aeonik Regular, 12px, weight 400.

### Base Feature Card
**Role:** Informational cards on secondary canvas.

Background: Canvas Ice (#f2f4f8). Border Radius: 8px. No shadow. Padding: 4px on all sides.

### Elevated Content Card
**Role:** Highlighting content against the main canvas.

Background: Paper White (#ffffff). Border Radius: 8px. No shadow. Padding: 16px on all sides.

### Customer Testimonial Card
**Role:** Prominent display of user feedback.

Background: Paper White (#ffffff). Border Radius: 8px. Shadow: rgba(0, 0, 0, 0.02) 0px 0.48px 1.64px, rgba(0, 0, 0, 0.03) 0px 1.83px 6.22px, rgba(0, 0, 0, 0.08) 0px 8px 27.2px. Padding: 30px on all sides.

### Text Input Field
**Role:** Standard form input area.

Background: Form Fill (#eeeeee). Text and Border: Mid-Tone Gray (#444444). Border Radius: 8px. Padding: 10px on all sides. Text uses Aeonik Regular, 16px, weight 400.

## Do's and Don'ts

### Do
- Use Canvas Ice (#f2f4f8) as the default background for most page sections, ensuring a light and airy feel.
- Apply Action Blue (#2e62ff) exclusively for primary interactions and key brand elements to maintain its high impact.
- Ensure all headings use Aeonik Medium with compact tracking (e.g., -0.0330em) to convey clarity and precision.
- Round corners with a consistent 8px radius for cards and input fields, while buttons use a more distinct 20px radius.
- Employ the Transparent Blue Gradient (linear-gradient(rgba(255, 255, 255, 0.3) 0%, rgba(76, 48, 237, 0.2) 100%)) as a subtle background layer for hero sections to create depth.
- Maintain an element gap of 16px between most vertical and horizontal elements for a predictable and spacious rhythm.
- Use Graphite Ink (#000000) for primary text and headings, relying on its strong contrast against light backgrounds.

### Don't
- Do not use saturated colors other than Action Blue (#2e62ff) or Ocean Link (#0099ff) for interactive elements, to avoid diluting brand identity.
- Avoid heavy or complex shadows on cards or elements unless specifically for high-priority components like Testimonial Cards.
- Do not introduce new typefaces; restrict typography to Aeonik variants and Inter to maintain brand consistency.
- Avoid large, uncontained images; always ensure images or illustrations are either contained within cards, elements with defined radii, or are abstract background gradients.
- Do not deviate from the established spacing scale; custom padding or margin values should be avoided to preserve density.
- Refrain from using overly bright or primary colors for descriptive text; utilize Mid-Tone Gray (#666666) or Dusty Violet (#4a527a) for secondary information.
- Never use full-width sections without a contained max-width hero or content block within, as the system favors a centered, structured layout approach.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas Ice | `#f2f4f8` | Base page background |
| 1 | Paper White | `#ffffff` | Elevated card surfaces, primary content blocks |
| 2 | Form Fill | `#eeeeee` | Input field backgrounds |

## Elevation

- **Customer Testimonial Card:** `rgba(0, 0, 0, 0.02) 0px 0.48175px 1.63795px -0.333333px, rgba(0, 0, 0, 0.03) 0px 1.83083px 6.22481px -0.666667px, rgba(0, 0, 0, 0.08) 0px 8px 27.2px -1px`

## Imagery

Imagery on Graphy is minimal and highly conceptual, focusing on abstract 3D elements and geometric shapes rather than photography or complex illustrations. These visuals feature a translucent, frosted glass effect with soft blue and white hues, often appearing to float or scatter across the canvas. Icons are outlined, conveying functionality with thin strokes. The visual density is very low, with imagery serving purely decorative or atmospheric roles, enhancing the 'data visualization' theme without competing with text.

## Layout

The page embraces a contained, centered layout, primarily using a max-width approach for content. The hero section is characterized by a prominent, centered headline and calls to action against a light background, often with subtle abstract background gradients or shapes. Sections predominantly follow a consistent vertical rhythm with ample section gaps. Content is arranged in alternating patterns, often with text contrasted against visual elements (like 3D data shapes) or a grid system for features and testimonials. Navigation consists of a simple top bar, likely sticky, with minimal links.

## Agent Prompt Guide

**Quick Color Reference**
text: #000000
background: #f2f4f8
border: #c2c2c2
accent: #2e62ff
primary action: #2e62ff (filled action)

**3-5 Example Component Prompts**
Create a Primary Action Button: #2e62ff background, #ffffff text, 9999px radius, compact pill padding. Use this filled treatment for the main CTA.

Design a Customer Testimonial Card: Paper White (#ffffff) background, 8px radius, with the distinct shadow style rgba(0, 0, 0, 0.02) 0px 0.48px 1.64px, rgba(0, 0, 0, 0.03) 0px 1.83px 6.22px, rgba(0, 0, 0, 0.08) 0px 8px 27.2px. Use 30px padding on all sides. Text for the reviewer's name is Graphite Ink (#000000), Aeonik Regular, 18px.

Build a standard Text Input Field: Form Fill (#eeeeee) background, 8px radius, 10px padding. Text and border color Mid-Tone Gray (#444444). Placeholder text should use Light-touch Gray (#999999), Inter font, 16px, weight 400.

Create a navigation link: "Pricing" in Aeonik Regular, 16px, weight 400, color Graphite Ink (#000000), using 10px element gap for list items. The active state should use Ocean Link (#0099ff).

## Similar Brands

- **Linear** — Both use a crisp, light UI with soft shadows and a single vivid accent color against a largely achromatic background.
- **Typeform** — Shares a spacious, clean aesthetic with abstract background elements and a focus on intuitive user experience.
- **Figma** — Similar approach to geometric forms in UI, compact typography, and a functional yet elegant design language.
- **Notion** — Employs a lightweight, highly readable typography system and predominantly neutral color palette to focus on content.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-canvas-ice: #f2f4f8;
  --color-paper-white: #ffffff;
  --color-graphite-ink: #000000;
  --color-slate-blue: #20295a;
  --color-action-blue: #2e62ff;
  --color-mid-tone-gray: #666666;
  --color-ghost-gray: #c2c2c2;
  --color-light-touch-gray: #999999;
  --color-ocean-link: #0099ff;
  --color-dusty-violet: #4a527a;
  --color-form-fill: #eeeeee;
  --color-transparent-blue-gradient: #4c30ed;
  --gradient-transparent-blue-gradient: linear-gradient(rgba(255, 255, 255, 0.3) 0%, rgba(76, 48, 237, 0.2) 100%);
  --color-subtle-blue-wash-gradient: #7d80da;
  --gradient-subtle-blue-wash-gradient: linear-gradient(90deg, rgb(255, 255, 255) -11%, rgba(125, 128, 218, 0.8) 27%, rgb(125, 128, 218) 49.5953%, rgba(213, 213, 213, 0.8) 77.4775%, rgba(255, 255, 255, 0) 100%);

  /* Typography — Font Families */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-medium: 'Aeonik Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-regular: 'Aeonik Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-bold: 'Aeonik Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.56px;
  --text-body: 16px;
  --leading-body: 1.35;
  --tracking-body: -0.7px;
  --text-subheading: 22px;
  --leading-subheading: 1.05;
  --tracking-subheading: -0.88px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -1.056px;
  --text-heading: 56px;
  --leading-heading: 1.13;
  --tracking-heading: -1.848px;
  --text-heading-lg: 68px;
  --leading-heading-lg: 1.05;
  --text-display: 82px;
  --leading-display: 0.85;
  --tracking-display: -2.706px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Layout */
  --section-gap: 40px;
  --card-padding: 16px;
  --element-gap: 16px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 51px;
  --radius-full-2: 70px;

  /* Named Radii */
  --radius-tags: 40px;
  --radius-cards: 8px;
  --radius-input: 8px;
  --radius-buttons: 20px;
  --radius-containers: 16px;
  --radius-roundedelements: 70px;
  --radius-smallinteractive: 4px;

  /* Surfaces */
  --surface-canvas-ice: #f2f4f8;
  --surface-paper-white: #ffffff;
  --surface-form-fill: #eeeeee;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-canvas-ice: #f2f4f8;
  --color-paper-white: #ffffff;
  --color-graphite-ink: #000000;
  --color-slate-blue: #20295a;
  --color-action-blue: #2e62ff;
  --color-mid-tone-gray: #666666;
  --color-ghost-gray: #c2c2c2;
  --color-light-touch-gray: #999999;
  --color-ocean-link: #0099ff;
  --color-dusty-violet: #4a527a;
  --color-form-fill: #eeeeee;
  --color-transparent-blue-gradient: #4c30ed;
  --color-subtle-blue-wash-gradient: #7d80da;

  /* Typography */
  --font-sans-serif: 'sans-serif', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-medium: 'Aeonik Medium', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-regular: 'Aeonik Regular', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-aeonik-bold: 'Aeonik Bold', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 12px;
  --leading-caption: 1.5;
  --tracking-caption: -0.6px;
  --text-body-sm: 14px;
  --leading-body-sm: 1.2;
  --tracking-body-sm: -0.56px;
  --text-body: 16px;
  --leading-body: 1.35;
  --tracking-body: -0.7px;
  --text-subheading: 22px;
  --leading-subheading: 1.05;
  --tracking-subheading: -0.88px;
  --text-heading-sm: 32px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -1.056px;
  --text-heading: 56px;
  --leading-heading: 1.13;
  --tracking-heading: -1.848px;
  --text-heading-lg: 68px;
  --leading-heading-lg: 1.05;
  --text-display: 82px;
  --leading-display: 0.85;
  --tracking-display: -2.706px;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-6: 6px;
  --spacing-7: 7px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-30: 30px;
  --spacing-32: 32px;
  --spacing-40: 40px;
  --spacing-48: 48px;
  --spacing-60: 60px;
  --spacing-80: 80px;
  --spacing-120: 120px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-2xl-2: 20px;
  --radius-3xl: 24px;
  --radius-3xl-2: 40px;
  --radius-full: 51px;
  --radius-full-2: 70px;
}
```
