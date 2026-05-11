# Free Podcast Hosting — Style Reference
> Pine forest studio

**Theme:** light

Buzzsprout adopts a refreshing, nature-inspired professional aesthetic with deep forest greens contrasting against a bright, airy canvas. Typography is direct and confident without being overly assertive, emphasizing clarity. Components are tactile and inviting, featuring soft rounded corners and subtle elevation, creating a sense of approachability and trust. The overall impression is one of grounded reliability tempered with modern simplicity.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Forest Shadow | `#214538` | `--color-forest-shadow` | Primary brand color, text on light backgrounds, filled buttons, dark section backgrounds |
| Sunlit Yellow | `#faefc3` | `--color-sunlit-yellow` | Decorative background wash for cards and sections — bright, yet muted |
| Validation Green | `#208619` | `--color-validation-green` | Green text accent for links, tags, and emphasized short phrases. Use as a supporting accent, not as a status color |
| Canvas White | `#ffffff` | `--color-canvas-white` | Main page background, default surface for cards, neutral text on dark backgrounds |
| Ash Gray | `#e4e5e6` | `--color-ash-gray` | Subtle borders, dividers, subtle button borders and backgrounds |
| Deep Graphite | `#151e1b` | `--color-deep-graphite` | Heading text, robust link text, dark elements within components |
| Pale Sage | `#e5ede9` | `--color-pale-sage` | Card backgrounds, secondary section backgrounds — a very subtle tint |
| Cloud Mist | `#f4f4f4` | `--color-cloud-mist` | Hairline borders, dividers, input outlines, and card edges on light surfaces. Do not promote it to the primary CTA color |
| Whisper Gray | `#4d4d4f` | `--color-whisper-gray` | Muted body text, helper text, secondary information |
| Golden Gradient | `linear-gradient(125deg, rgb(250, 227, 139) 0%, rgb(244, 196, 25) 100%)` | `--color-golden-gradient` | Decorative highlights, possibly for promotional banners or special accents, evoking warmth |

## Tokens — Typography

### Graphik — Universal sans-serif for all UI text, body copy, headings large and small. Wide range of weights and sizes provide typographic hierarchy without relying on multiple typefaces. The subtle negative letter-spacing on larger sizes creates a composed, modern feel. · `--font-graphik`
- **Substitute:** Inter
- **Weights:** 400, 500, 600, 700
- **Sizes:** 10px, 12px, 14px, 15px, 16px, 18px, 20px, 24px, 25px, 30px, 35px, 48px, 50px, 60px
- **Line height:** 1.00, 1.10, 1.20, 1.33, 1.40, 1.43, 1.50, 1.60, 1.80, 2.50
- **Letter spacing:** -0.016em at 60px, -0.013em at 48px, -0.012em at 35px, -0.011em at 30px, -0.01em at 24px, -0.009em at 20px, -0.008em at 18px, -0.007em at 16px, -0.006em at 15px, -0.005em at 14px, -0.003em at 12px, normal at 10px
- **Role:** Universal sans-serif for all UI text, body copy, headings large and small. Wide range of weights and sizes provide typographic hierarchy without relying on multiple typefaces. The subtle negative letter-spacing on larger sizes creates a composed, modern feel.

### Girott — Display font used sparingly for very large, impactful headlines, commanding attention with its sheer scale and minimal tracking. Its single weight and unique character define hero sections. · `--font-girott`
- **Substitute:** Oswald
- **Weights:** 600
- **Sizes:** 168px
- **Line height:** 1.00, 1.50
- **Letter spacing:** -0.001em
- **Role:** Display font used sparingly for very large, impactful headlines, commanding attention with its sheer scale and minimal tracking. Its single weight and unique character define hero sections.

### Type Scale

| Role | Size | Line Height | Letter Spacing | Token |
|------|------|-------------|----------------|-------|
| caption | 10px | 1.5 | — | `--text-caption` |
| body-sm | 14px | 1.5 | -0.07px | `--text-body-sm` |
| body | 16px | 1.5 | -0.112px | `--text-body` |
| subheading | 20px | 1.4 | -0.18px | `--text-subheading` |
| heading-sm | 25px | 1.33 | -0.25px | `--text-heading-sm` |
| heading | 48px | 1.1 | -0.624px | `--text-heading` |
| heading-lg | 60px | 1 | -0.96px | `--text-heading-lg` |
| display | 168px | 1 | -1.68px | `--text-display` |

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
| 80 | 80px | `--spacing-80` |
| 96 | 96px | `--spacing-96` |
| 100 | 100px | `--spacing-100` |
| 128 | 128px | `--spacing-128` |
| 132 | 132px | `--spacing-132` |
| 156 | 156px | `--spacing-156` |

### Border Radius

| Element | Value |
|---------|-------|
| tags | 9999px |
| cards | 12px |
| inputs | 8px |
| buttons | 6px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1)...` | `--shadow-xl` |
| xl-2 | `rgba(0, 0, 0, 0.16) 0px 10px 36px 0px` | `--shadow-xl-2` |

### Layout

- **Section gap:** 80px
- **Card padding:** 24px
- **Element gap:** 10px

## Components

### Primary Filled Button
**Role:** Main call to action

Fills with Forest Shadow (#214538), white Canvas White (#ffffff) text. Padding: 15px vertical, 40px horizontal. Border radius: 6px. Used for high-impact actions like 'Get Started Free'.

### Secondary Filled Button
**Role:** Prominent action, slightly smaller than primary

Fills with Forest Shadow (#214538), white Canvas White (#ffffff) text. Padding: 17px vertical, 25px horizontal. Border radius: 10px. Slightly more rounded than the primary.

### Ghost Button (Minimal)
**Role:** Subtle actions or navigation items

Transparent background, Forest Shadow (#214538) text. Padding: 0px vertical, 16px horizontal. Border radius: 4px, with a 1px Ash Gray (#e4e5e6) border. Lightweight interaction.

### Ghost Button (Tag)
**Role:** Categorization or filter tags

Light background of Cloud Mist (#f4f4f4), Forest Shadow (#214538) text. Padding: 4px vertical, 15px horizontal. Border radius: 10px. No explicit border.

### Product Feature Card
**Role:** Displaying product features with iconography

White Canvas White (#ffffff) background, rounded corners (20px radius). Features a subtle Elevation Shadow (rgba(0,0,0,0.16) 0px 10px 36px 0px). Inner padding of 24px.

### Muted Highlight Card
**Role:** Background for secondary content blocks

Light Pale Sage (#e5ede9) background, 12px border radius. Generous 80px internal padding around content. No shadows, acts as a soft surface differentiator.

### Testimonial Card
**Role:** Showcasing user reviews

Light Sunlit Yellow (#faefc3) background, 10px border radius. Features a 40px vertical padding. No shadows, serves as a bright, inviting content container.

### Small Image Tile
**Role:** Showcasing compact images or app screenshots

Features an 8px border radius and a distinct Dark Elevation shadow (rgba(0,0,0,0.1) 0px 20px 25px -5px, rgba(0,0,0,0.1) 0px 8px 10px -6px).

## Do's and Don'ts

### Do
- Prioritize Forest Shadow (#214538) for all primary text and calls to action.
- Apply 6px border radius to all interactive buttons for a consistent soft touch.
- Use Ash Gray (#e4e5e6) for all hairline borders and subtle dividers.
- Maintain a comfortable rhythm with 80px vertical spacing between major sections.
- Employ Pale Sage (#e5ede9) for secondary background surfaces to introduce subtle tonal variety.
- Utilize Graphik weight 600 for subheadings and Girott weight 600 for large display text to create clear hierarchy.
- Ensure all body text uses Graphik at 16px with a line height of 1.5 and letter spacing of -0.007em (approx -0.112px).

### Don't
- Avoid using harsh, saturated primary colors outside of very specific semantic indicators like Validation Green (#208619).
- Do not use sharp 0px corners on any UI elements; apply a minimum of 4px radius.
- Resist adding unnecessary borders or heavy shadows to cards; prefer subtle background color changes or the predefined Elevation Shadow.
- Do not break the established typographic scale; stick to the defined sizes and letter spacing for Graphik and Girott.
- Do not introduce alternative font families. Graphik and Girott are the only approved typefaces.
- Avoid arbitrary color choices. Every color must serve a specific functional or brand role defined in the palette.
- Do not clutter layouts. Maintain the comfortable 10px element gap and ample section spacing.

## Surfaces

| Level | Name | Value | Purpose |
|-------|------|-------|---------|
| 0 | Canvas White | `#ffffff` | Default page background. Provides a clean, bright foundation. |
| 1 | Pale Sage | `#e5ede9` | Secondary background for cards and distinct sections, offering a subtle tonal shift without being distracting. |
| 2 | Sunlit Yellow | `#faefc3` | Highlight background for specific cards or content blocks, adding a touch of warmth and visual interest. |

## Elevation

- **Card:** `rgba(0, 0, 0, 0.16) 0px 10px 36px 0px`
- **Image Tile:** `rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px`

## Imagery

The visual language for imagery leans towards clean, product-focused showcases and occasional abstract graphics. Photography consists of tight crops of people interacting with technology or product UI, presented against clean backdrops, often with an 8px radius. Illustrations, where present, appear to be flat, bold, and likely organic in shape, though not explicitly shown. Icons are minimal, outlined, with a moderate stroke weight and primarily in Forest Shadow. Imagery density is moderate, used to break up text sections and illustrate features rather than dominate the page. Graphics serve an explanatory and supportive role, enhancing understanding rather than being purely decorative.

## Layout

The page primarily uses a max-width contained layout, centered on a light Canvas White background. The hero section is full-width, centered text over a background image (implied, not fully visible but based on 'Keep podcasting...' header) that transitions to the light page canvas. Section rhythm is marked by consistent 80px vertical spacing, often with alternating background tints (e.g., White to Pale Sage). Content is largely arranged in clear, centered stacks for headlines and subtext, and symmetrical multi-column grids (like the 3-column review section) for feature presentation. A sticky top navigation bar with a distinct 'Get Started Free' button maintains primary access.

## Agent Prompt Guide

### Quick Color Reference
- text: #214538
- background: #ffffff
- border: #e4e5e6
- accent: #faefc3
- primary action: #214538 (filled action)

### 3-5 Example Component Prompts
- Create a hero section: pale sage background. Headline 'KEEP PODCASTING' in Girott, 168px, weight 600, #214538, letter-spacing -1.68px. Subtext 'You have the inspiration...' in Graphik, 20px, weight 400, #214538, letter-spacing -0.18px. Followed by a primary filled button 'Get Started Free' with background #214538, text #ffffff, padding 15px 40px, border-radius 6px.
- Create a testimonial card: Sunlit Yellow (#faefc3) background, 10px border-radius, 40px vertical padding. Quote text 'Everything about this service is fantastic!' in Graphik, 20px, weight 600, #214538, letter-spacing -0.18px. Author name below in Graphik, 16px, weight 400, #4d4d4f, letter-spacing -0.112px.
- Create a product feature block: White Canvas White (#ffffff) background, with a subtle Elevation Shadow. Title in Deep Graphite (#151e1b) Graphik, 25px, weight 600, letter-spacing -0.25px. Description text below in Whisper Gray (#4d4d4f) Graphik, 16px, weight 400, letter-spacing -0.112px. Icon in Forest Shadow (#214538).
- Create a Ghost Tag button: Cloud Mist (#f4f4f4) background, #214538 text, Graphik 14px weight 400, padding 4px 15px, border-radius 10px.

## Similar Brands

- **Webflow** — Shares a clean, modern aesthetic with a focus on clear typography and understated color accents against a predominantly neutral background.
- **Linear** — Exhibits a similar approach to typography, prioritizing readability and clear hierarchy with subtle negative letter-spacing for large text, and a refined use of neutral colors with selective brand accents.
- **Superhuman** — Features a strong, readable sans-serif typeface for the entire UI and relies on a minimal color palette where brand colors serve as distinct functional indicators over widespread decoration.
- **Notion** — Employs a content-first design with a clean, white canvas, subtle borders, and a focus on clarity through typography and functional color use, rather than heavy visual effects.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-forest-shadow: #214538;
  --color-sunlit-yellow: #faefc3;
  --color-validation-green: #208619;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #e4e5e6;
  --color-deep-graphite: #151e1b;
  --color-pale-sage: #e5ede9;
  --color-cloud-mist: #f4f4f4;
  --color-whisper-gray: #4d4d4f;
  --color-golden-gradient: #fae78b;
  --gradient-golden-gradient: linear-gradient(125deg, rgb(250, 227, 139) 0%, rgb(244, 196, 25) 100%);

  /* Typography — Font Families */
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-girott: 'Girott', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.07px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.112px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.25px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.624px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.96px;
  --text-display: 168px;
  --leading-display: 1;
  --tracking-display: -1.68px;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
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
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-128: 128px;
  --spacing-132: 132px;
  --spacing-156: 156px;

  /* Layout */
  --section-gap: 80px;
  --card-padding: 24px;
  --element-gap: 10px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 9999px;

  /* Named Radii */
  --radius-tags: 9999px;
  --radius-cards: 12px;
  --radius-inputs: 8px;
  --radius-buttons: 6px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-2: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px;

  /* Surfaces */
  --surface-canvas-white: #ffffff;
  --surface-pale-sage: #e5ede9;
  --surface-sunlit-yellow: #faefc3;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-forest-shadow: #214538;
  --color-sunlit-yellow: #faefc3;
  --color-validation-green: #208619;
  --color-canvas-white: #ffffff;
  --color-ash-gray: #e4e5e6;
  --color-deep-graphite: #151e1b;
  --color-pale-sage: #e5ede9;
  --color-cloud-mist: #f4f4f4;
  --color-whisper-gray: #4d4d4f;
  --color-golden-gradient: #fae78b;

  /* Typography */
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-girott: 'Girott', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-caption: 10px;
  --leading-caption: 1.5;
  --text-body-sm: 14px;
  --leading-body-sm: 1.5;
  --tracking-body-sm: -0.07px;
  --text-body: 16px;
  --leading-body: 1.5;
  --tracking-body: -0.112px;
  --text-subheading: 20px;
  --leading-subheading: 1.4;
  --tracking-subheading: -0.18px;
  --text-heading-sm: 25px;
  --leading-heading-sm: 1.33;
  --tracking-heading-sm: -0.25px;
  --text-heading: 48px;
  --leading-heading: 1.1;
  --tracking-heading: -0.624px;
  --text-heading-lg: 60px;
  --leading-heading-lg: 1;
  --tracking-heading-lg: -0.96px;
  --text-display: 168px;
  --leading-display: 1;
  --tracking-display: -1.68px;

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
  --spacing-80: 80px;
  --spacing-96: 96px;
  --spacing-100: 100px;
  --spacing-128: 128px;
  --spacing-132: 132px;
  --spacing-156: 156px;

  /* Border Radius */
  --radius-md: 4px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 20px;
  --radius-full: 9999px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.1) 0px 20px 25px -5px, rgba(0, 0, 0, 0.1) 0px 8px 10px -6px;
  --shadow-xl-2: rgba(0, 0, 0, 0.16) 0px 10px 36px 0px;
}
```
