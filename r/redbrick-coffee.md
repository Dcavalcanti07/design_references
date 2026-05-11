# Redbrick Coffee — Style Reference
> Red enamel on white canvas.

**Theme:** light

Redbrick Coffee uses a bold, expressive e-commerce aesthetic, characterized by a dominant, warm red that demands attention. High-contrast typography emphasizes a traditional serif for large, editorial headlines and a practical sans-serif for functional UI elements. Surfaces are minimal, relying on stark white and a soft F2F2F2 gray for product cards, while interaction is guided by an outlined red accent. Elements are generously spaced, creating a clean rhythm against the vibrant brand color.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Crimson Roast | `#e82c2a` | `--color-crimson-roast` | Brand accent color for borders, outlines, links, and text highlights, creating a distinctive energetic feel. Used for primary interactive states |
| Inkwell | `#212529` | `--color-inkwell` | Primary text color and occasional border |
| Cloud Cover | `#f2f2f2` | `--color-cloud-cover` | Background for secondary surfaces like product cards |
| Pure White | `#ffffff` | `--color-pure-white` | Main page background and text on dark backgrounds |
| Deep Space | `#121212` | `--color-deep-space` | Used for specific link backgrounds and navigation elements |

## Tokens — Typography

### Surt — Body copy, primary navigation, input fields, and standard UI text. Its compact, almost compressed letterforms bring a modern, efficient feel to functional text. · `--font-surt`
- **Substitute:** Inter
- **Weights:** 400
- **Sizes:** 15px, 20px, 30px, 35px
- **Line height:** 1.00, 1.20, 1.30, 1.50
- **Letter spacing:** -0.013em at 35px, -0.017em at 30px, -0.030em at 20px, -0.040em at 15px
- **Role:** Body copy, primary navigation, input fields, and standard UI text. Its compact, almost compressed letterforms bring a modern, efficient feel to functional text.

### Editorial Old — Display and large editorial headlines. The light weight (300) combined with large sizes creates a sophisticated, almost whispered authority. · `--font-editorial-old`
- **Substitute:** Playfair Display
- **Weights:** 300
- **Sizes:** 100px, 105px, 150px
- **Line height:** 0.99, 1.10, 1.20
- **Letter spacing:** -0.005em at 150px, 0.004em at 105px, 0.006em at 100px
- **OpenType features:** `"clig" on, "liga" on`
- **Role:** Display and large editorial headlines. The light weight (300) combined with large sizes creates a sophisticated, almost whispered authority.

### system-ui — Small helper text and metadata where legibility is key without demanding attention. · `--font-system-ui`
- **Substitute:** Arial
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.50
- **Letter spacing:** 0.060em
- **Role:** Small helper text and metadata where legibility is key without demanding attention.

### GTStandard-M — GTStandard-M — detected in extracted data but not described by AI · `--font-gtstandard-m`
- **Weights:** 400
- **Sizes:** 10px
- **Line height:** 1.5
- **Letter spacing:** 0.06
- **Role:** GTStandard-M — detected in extracted data but not described by AI

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | 0.06px | `--text-caption` |
| body | 15px | 1.5 | -0.04px | `--text-body` |
| subheading | 20px | 1.3 | -0.03px | `--text-subheading` |
| heading-sm | 30px | 1.2 | -0.017px | `--text-heading-sm` |
| heading | 35px | 1 | -0.013px | `--text-heading` |
| display-sm | 100px | 1.2 | 0.006px | `--text-display-sm` |
| display-md | 105px | 1.1 | 0.004px | `--text-display-md` |
| display | 150px | 0.99 | -0.005px | `--text-display` |

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 12 | 12px | `--spacing-12` |
| 15 | 15px | `--spacing-15` |
| 20 | 20px | `--spacing-20` |
| 30 | 30px | `--spacing-30` |
| 50 | 50px | `--spacing-50` |
| 117 | 117px | `--spacing-117` |
| 234 | 234px | `--spacing-234` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 25px |
| links | 3.75px |
| images | 25px |
| inputs | 50px |
| buttons | 50px |

### Layout

- **Section gap:** 50px
- **Card padding:** 0px
- **Element gap:** 10px

## Components

### Outlined Call to Action Button
**Role:** Primary interactive element for actions.

Text in Crimson Roast (#e82c2a), outlined with a 1px Crimson Roast border, and a 50px border-radius. Padding is 5px vertical and 30px horizontal, ensuring a minimal yet distinct presence against the white background.

### Product Card
**Role:** Displays individual product items in a grid.

Background is Cloud Cover (#f2f2f2) with a 25px border-radius. Contains product imagery and text, with no internal padding on the card itself, assuming content provides its own spacing.

### Outlined Input Field
**Role:** User input fields.

Background is transparent, text color matching Crimson Roast (#e82c2a). Outlined with a 1px Crimson Roast border, and a 50px border-radius. Padding is 5px vertical and 30px horizontal, identical to CTA buttons.

### Navigation Link
**Role:** Top-level navigation items.

Text in Inkwell (#212529) using the Surt font, size 15px. Underlined on hover or active with a 1px Crimson Roast solid border, and occasionally uses a 3.75px border-radius sparingly.

### Hero Headline
**Role:** Large, attention-grabbing titles.

Uses Editorial Old font, weight 300, color Crimson Roast (#e82c2a). Sizes can range from 100px to 150px with tight line heights and varying negative letter-spacing for an impactful, editorial feel.

### Banner Notification
**Role:** Top narrow banner for announcements.

Background is Crimson Roast (#e82c2a), text color is Pure White (#ffffff). Utilizes compact Surt 15px text and serves as a full-width information strip.

## Do's and Don'ts

### Do
- Prioritize Crimson Roast (#e82c2a) as the primary accent for all interactive elements, borders, and significant text highlights.
- Use Editorial Old font for all display-level headings (100px and above), maintaining its delicate weight 300.
- Apply a 50px border-radius to all buttons and input fields for a consistent, soft pill-like shape.
- Utilize Cloud Cover (#f2f2f2) specifically for product card backgrounds, maintaining a soft, recessive surface.
- Maintain generous section gaps of 50px to create ample negative space and visual segmentation between content blocks.
- Ensure all body text and UI elements use the Surt font at its specified weights and compact letter-spacing values.

### Don't
- Do not introduce new saturated colors; maintain the brand's restraint to its single vivid red.
- Avoid heavy drop shadows or significant elevation; rely on outlines and background color differences for distinction.
- Do not use bold weights or all-caps for large editorial headlines; Editorial Old 300 is meant to be restrained.
- Do not deviate from the 25px radius for cards and images, or the 50px radius for buttons/inputs; these are signature shapes.
- Do not use deep, dark backgrounds for entire sections, except for specific, contained elements like the 'skip to content' link, maintaining a light theme.
- Avoid using system-ui for anything other than small, supporting text; it is not for primary content or UI elements.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 1 | Pure White Canvas | `#ffffff` | Dominant page background, providing a clean, bright foundation. |
| 2 | Cloud Cover Card | `#f2f2f2` | Background for product cards, providing a subtle differentiation from the main canvas. |
| 3 | Crimson Roast Accent | `#e82c2a` | Used as prominent background for banners or active states, drawing immediate attention. |
| 4 | Deep Space Overlay | `#121212` | Highly contrasting background for specific, usually interactive, calls to action like 'Skip to content'. |

## Imagery

Photography is product-focused, featuring tight crops of coffee bags and brewing equipment in clean, often brightly lit, environments. There's a strong emphasis on the product itself, sometimes with hands interacting with equipment or holding a cup, without extensive lifestyle contexts. Images frequently use a soft 25px border-radius, maintaining the brand's rounded aesthetic. Hero imagery often shows product packaging in vivid red. Icons are minimalist, outline-based, and primarily rendered in Crimson Roast (#e82c2a) against white, serving as functional accents.

## Layout

The page primarily uses a full-bleed structure for hero sections and banners, transitioning to a centered, contained layout for product listings and textual content. The hero often features a large image on one side and a prominent Editorial Old headline on the other. Sections alternate between full-bleed vibrant red areas (like announcement bars) and white or light gray content blocks. Content is arranged in alternating image-left/text-right or text-left/image-right patterns, and occasionally a 3-column grid for product cards. Vertical spacing is consistent and generous, using a 50px section gap for a spacious feel. Navigation is a top bar with a sticky header, featuring minimal Surt font links and a distinct Crimson Roast 'Menu' button.

## Agent Prompt Guide

Quick Color Reference:
text: #212529
background: #ffffff
border: #e82c2a
accent: #e82c2a
primary action: #e82c2a (outlined action border)

Example Component Prompts:
Create an Outlined Primary Action: Transparent background, #e82c2a border and text, 9999px radius, compact pill padding. Use it for the main CTA instead of a filled button.

Create a product card: Cloud Cover (#f2f2f2) background, 25px radius. Add an image with 25px radius covering the top portion. Below the image, add product title 'Espresso Blend' in Inkwell (#212529), Surt font, size 20px, weight 400. Include price '$18.00' in Inkwell (#212529), Surt font, size 15px, weight 400.

Create a navigation bar: Pure White (#ffffff) background. Include 'Shop' link in Inkwell (#212529), Surt font, size 15px, weight 400. Include a 'Cart' link with an icon in Inkwell (#212529). Include an 'Outlined Menu Button': 'Menu', text #e82c2a, 1px border #e82c2a, 50px radius, 5px vertical padding, 30px horizontal padding.

Create a section with a large heading: 'Our Story' in Crimson Roast (#e82c2a), Editorial Old font, size 100px, weight 300, line height 1.2. Below, add a paragraph of body text in Inkwell (#212529), Surt font, size 15px, weight 400, line height 1.5, element gap 15px from heading.

## Similar Brands

- **Oatly** — Dominant single brand color (blue/green for Oatly, red for Redbrick) paired with primarily neutral supporting UI and large, characterful typography.
- **Trade Coffee** — Clean e-commerce layout for coffee products, emphasis on product photography, and a distinct, memorable brand color used for accents.
- **Minor Figures** — Modern, playful branding with a clear primary accent color, minimal UI on white backgrounds, and a mix of serif headlines with sans-serif body text.
- **Fellow Products** — Focus on product-centric imagery within a clean and spacious layout, using specific typographic choices for brand personality.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-crimson-roast: #e82c2a;
  --color-inkwell: #212529;
  --color-cloud-cover: #f2f2f2;
  --color-pure-white: #ffffff;
  --color-deep-space: #121212;

  /* Typography — Font Families */
  --font-surt: 'Surt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-old: 'Editorial Old', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.06px;
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: -0.04px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.017px;
  --text-heading: 35px;
  --leading-heading: 1;
  --tracking-heading: -0.013px;
  --text-display-sm: 100px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: 0.006px;
  --text-display-md: 105px;
  --leading-display-md: 1.1;
  --tracking-display-md: 0.004px;
  --text-display: 150px;
  --leading-display: 0.99;
  --tracking-display: -0.005px;

  /* Typography — Weights */
  --font-weight-light: 300;
  --font-weight-regular: 400;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-50: 50px;
  --spacing-117: 117px;
  --spacing-234: 234px;

  /* Layout */
  --section-gap: 50px;
  --card-padding: 0px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 3.75px;
  --radius-3xl: 25px;
  --radius-full: 50px;

  /* Named Radii */
  --radius-cards: 25px;
  --radius-links: 3.75px;
  --radius-images: 25px;
  --radius-inputs: 50px;
  --radius-buttons: 50px;

  /* Surfaces */
  --surface-pure-white-canvas: #ffffff;
  --surface-cloud-cover-card: #f2f2f2;
  --surface-crimson-roast-accent: #e82c2a;
  --surface-deep-space-overlay: #121212;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-crimson-roast: #e82c2a;
  --color-inkwell: #212529;
  --color-cloud-cover: #f2f2f2;
  --color-pure-white: #ffffff;
  --color-deep-space: #121212;

  /* Typography */
  --font-surt: 'Surt', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-editorial-old: 'Editorial Old', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-system-ui: 'system-ui', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-gtstandard-m: 'GTStandard-M', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --tracking-caption: 0.06px;
  --text-body: 15px;
  --leading-body: 1.5;
  --tracking-body: -0.04px;
  --text-subheading: 20px;
  --leading-subheading: 1.3;
  --tracking-subheading: -0.03px;
  --text-heading-sm: 30px;
  --leading-heading-sm: 1.2;
  --tracking-heading-sm: -0.017px;
  --text-heading: 35px;
  --leading-heading: 1;
  --tracking-heading: -0.013px;
  --text-display-sm: 100px;
  --leading-display-sm: 1.2;
  --tracking-display-sm: 0.006px;
  --text-display-md: 105px;
  --leading-display-md: 1.1;
  --tracking-display-md: 0.004px;
  --text-display: 150px;
  --leading-display: 0.99;
  --tracking-display: -0.005px;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-12: 12px;
  --spacing-15: 15px;
  --spacing-20: 20px;
  --spacing-30: 30px;
  --spacing-50: 50px;
  --spacing-117: 117px;
  --spacing-234: 234px;

  /* Border Radius */
  --radius-md: 3.75px;
  --radius-3xl: 25px;
  --radius-full: 50px;
}
```
