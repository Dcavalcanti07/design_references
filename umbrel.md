# Umbrel — Style Reference
> Deep Space Luxury Console. The UI is a console in a dark, high-tech environment, with glowing accents and soft, tactile controls.

**Theme:** dark

Umbrel's design system evokes a sense of deep, sophisticated technology housed within a warm, user-centric environment. The prevailing darkness, created by near-black backgrounds, is punctuated by rich, vibrant gradients that give a feeling of digital depth and energy. Subtle contrasts and varied text weights maintain readability within the dark theme, while rounded corners and soft shadows on elements like buttons and cards introduce approachability to the complex technical offering.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Midnight Void | `#000000` | `--color-midnight-void` | Primary background for pages, text color for light theme elements, accent for borders. |
| Obsidian Surface | `#292929` | `--color-obsidian-surface` | Subtle dark element backgrounds, card surfaces, and shadow bases. |
| Onyx Shadow | `#180f03` | `--color-onyx-shadow` | Deepest shadow color for elevated elements, adding subtle separation. |
| Moonlight Glimmer | `#ffffff` | `--color-moonlight-glimmer` | Primary text color on dark backgrounds, icon fills, form input text. |
| Warm Gray | `#61635d` | `--color-warm-gray` | Secondary text, subtle background tones for informational sections. |
| Cool Steel | `#cccccc` | `--color-cool-steel` | Tertiary text, subtle borders, inactive states. |
| Pale Mist | `#e0e0e0` | `--color-pale-mist` | Lightest grey for subtle highlights or disabled text. |
| System Gray | `#797985` | `--color-system-gray` | Placeholder text, minor labels, neutral icon fills. |
| #0a0a0a | `#0a0a0a` | `--color-0a0a0a` | Used for specific dark text instances, creating very slight depth against other blacks. |
| Violet Impulse | `#5351f3` | `--color-violet-impulse` | Primary interactive element background for CTAs, and active states. |
| Sunset Ember | `#e3a081` | `--color-sunset-ember` | Highlight color for headlines and key information, creating a warm contrast. |
| Neon Blue | `#41bdf5` | `--color-neon-blue` | Accent for illustrations and specific icon fills, adding a vibrant digital touch. |
| Electric Green | `#009b00` | `--color-electric-green` | Used sparingly for icon accents or success indicators. |
| Deep Web Gradient | `linear-gradient(-26deg, rgba(0, 86, 255, 0.29) 0%, rgb(194, 142, 1) 100%)` | `--color-deep-web-gradient` | Decorative background gradient for feature sections, adding depth and dynamic energy. |
| Plasma Flow Gradient | `linear-gradient(-26deg, rgba(133, 93, 255, 0.27) 0%, rgb(254, 121, 0) 100%)` | `--color-plasma-flow-gradient` | Decorative background gradient, creating a futuristic, energetic feel. |
| Core Melt Gradient | `linear-gradient(-26deg, rgb(89, 16, 16) 0%, rgba(69, 0, 16, 0.46) 22.631%, rgba(255, 59, 59, 0.5) 100%)` | `--color-core-melt-gradient` | Decorative background gradient for aggressive or high-impact sections. |
| Deep Sky Gradient | `radial-gradient(100% 147.839% at 0px 4.44089e-14%, rgb(6, 87, 161) 0%, rgb(5, 30, 34) 36.2271%, rgba(3, 29, 60, 0.97) 72.4655%, rgba(30, 83, 161, 0.93) 84.8958%, rgb(53, 90, 163) 100%)` | `--color-deep-sky-gradient` | Decorative background gradient, suggesting vastness and power. |

## Tokens — Typography

### Inter — Versatile workhorse for all body text, links, buttons, and varied-size headings. Its variable weights and precise letter spacing on larger sizes contribute to a refined textual feel. · `--font-inter`
- **Substitute:** system-ui, sans-serif
- **Weights:** 400, 500, 600, 700
- **Sizes:** 12px, 13px, 14px, 16px, 18px, 20px, 23px, 24px, 27px, 32px, 36px, 48px
- **Line height:** 1.10, 1.20, 1.24, 1.30, 1.40
- **Letter spacing:** -0.03em at 48px, -0.02em at 36px, -0.01em at 14px
- **OpenType features:** `"blwf", "cv03", "cv04", "cv09", "cv11"`
- **Role:** Versatile workhorse for all body text, links, buttons, and varied-size headings. Its variable weights and precise letter spacing on larger sizes contribute to a refined textual feel.

### Inter Display — Headline font for primary page titles, its semi-bold weight and tight letter spacing deliver impact and clarity in large display sizes. · `--font-inter-display`
- **Substitute:** system-ui, sans-serif
- **Weights:** 600
- **Sizes:** 43px
- **Line height:** 1.20
- **Letter spacing:** -0.02em
- **Role:** Headline font for primary page titles, its semi-bold weight and tight letter spacing deliver impact and clarity in large display sizes.

### Inter Tight — Used for specific compact text elements, often in conjunction with other Inter styles to create subtle visual hierarchy at small sizes. · `--font-inter-tight`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 12px
- **Line height:** 1.20
- **Role:** Used for specific compact text elements, often in conjunction with other Inter styles to create subtle visual hierarchy at small sizes.

### Manrope — Used for compact body text where slight visual distinction from Inter is desired, often for captions or metadata. · `--font-manrope`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** -0.01em
- **Role:** Used for compact body text where slight visual distinction from Inter is desired, often for captions or metadata.

### Roboto Condensed — A distinct, more condensed secondary body font for specific information, offering a different texture compared to Inter. · `--font-roboto-condensed`
- **Substitute:** system-ui, sans-serif
- **Weights:** 500
- **Sizes:** 14px
- **Line height:** 1.24
- **Letter spacing:** -0.01em
- **Role:** A distinct, more condensed secondary body font for specific information, offering a different texture compared to Inter.

## Tokens — Spacing & Shapes

**Density:** compact

### Spacing Scale

| Name | Value | Token |
|------|-------|-------|
| 5 | 5px | `--spacing-5` |
| 6 | 6px | `--spacing-6` |
| 8 | 8px | `--spacing-8` |
| 10 | 10px | `--spacing-10` |
| 11 | 11px | `--spacing-11` |
| 12 | 12px | `--spacing-12` |
| 13 | 13px | `--spacing-13` |
| 14 | 14px | `--spacing-14` |
| 16 | 16px | `--spacing-16` |
| 19 | 19px | `--spacing-19` |
| 20 | 20px | `--spacing-20` |
| 24 | 24px | `--spacing-24` |
| 25 | 25px | `--spacing-25` |
| 40 | 40px | `--spacing-40` |
| 50 | 50px | `--spacing-50` |
| 60 | 60px | `--spacing-60` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 24px |
| pills | 99px |
| images | 12px |
| inputs | 20px |
| buttons | 32px |
| default | 16px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| xl | `rgba(0, 0, 0, 0.24) -12px -12px 32px 0px` | `--shadow-xl` |
| lg | `rgba(104, 65, 13, 0.23) 0px 10px 20px 0px` | `--shadow-lg` |

### Layout

- **Card padding:** 12px

## Components

### Primary Filled Button
**Role:** Main call-to-action button, highlighted against dark backgrounds.

Background: Violet Impulse (#5351f3), Text: Moonlight Glimmer (#ffffff), Border: none, Radius: 32px or 99px for pills, Padding: 12px vertical, 16px horizontal. Uses Inter 400 at 16px.

### Ghost Button
**Role:** Secondary action or navigation element, subtle interaction.

Background: transparent (rgba(0,0,0,0)), Text: Moonlight Glimmer (#ffffff), Border: 1px solid Moonlight Glimmer (#ffffff), Radius: 32px, Padding: 12px vertical, 16px horizontal. Uses Inter 400 at 16px.

### Navigation Link Button
**Role:** Internal navigation or subtle secondary actions within sections.

Background: transparent (rgba(0,0,0,0)), Text: #0000ee (browser default link color for some contexts, but visually #ffffff), Border: none, Radius: 99px, Padding: 8px vertical, 16px horizontal. Uses Inter 400 at 12px.

### Umbrel Pro Info Card
**Role:** Highlights key product features or variants.

Background: near-black #191919 or transparent (rgba(0,0,0,0.2)), Border: none, Radius: 24px, Shadow: rgba(0,0,0,0.24) -12px -12px 32px 0px. Text is Moonlight Glimmer (#ffffff).

### Feature Teaser Card
**Role:** Compact informational blocks, often in grids.

Background: deep gradients (Deep Web Gradient), Radius: 24px. Contains small icons and body text.

### Input Field
**Role:** User entry for forms.

Background: transparent (rgba(235,235,235,0)), Text: Moonlight Glimmer (#ffffff), Border: 1px solid Moonlight Glimmer (#ffffff), Radius: 20px, Padding: 14px vertical, 10px horizontal. Placeholder text uses System Gray (#797985).

### Headline Banner
**Role:** Dominant text for section introductions.

Text: Moonlight Glimmer (#ffffff) for primary headlines, with Sunset Ember (#e3a081) for key emphasized words. Uses Inter Display 600 at 43px with -0.02em letter spacing.

## Do's and Don'ts

### Do
- Prioritize Midnight Void (#000000) for all page and primary section backgrounds, ensuring a consistent dark theme.
- Use Moonlight Glimmer (#ffffff) for primary text on dark backgrounds, and Warm Gray (#61635d) or Cool Steel (#cccccc) for secondary or tertiary text hierarchy.
- Apply Violet Impulse (#5351f3) consistently only to primary call-to-action buttons for clear visual guidance.
- Utilize Inter font family for all textual content, leveraging its multiple weights (400, 500, 600, 700) and varying letter spacing to establish clear typographic hierarchy.
- Employ generous padding of 12px vertically and 16px horizontally for all prominent buttons, using a 32px or 99px corner radius to create a soft, approachable pill shape.
- Integrate the brand gradients (e.g., Deep Web Gradient, Plasma Flow Gradient) judiciously as background fills for feature sections or distinct content blocks to add visual dynamism and depth.
- Maintain a clear visual hierarchy by contrasting headline sizes using Inter Display 600 at 43px with tight letter spacing against body text at 16px Inter 400.

### Don't
- Avoid introducing bright or highly saturated colors outside the defined brand and accent palette; they will detract from the sophisticated dark theme.
- Do not use sharp corners for interactive elements or cards; maintain the established softer aesthetic with radii like 24px, 32px, or 99px.
- Refrain from using more than two distinct gradients close to each other; allow gradients to breathe as distinct background elements for different sections.
- Do not place plain text directly on complex gradient backgrounds without sufficient contrast or a text container; ensure readability at all times.
- Avoid excessive shadow usage on every element; reserve prominent shadows (like rgba(0,0,0,0.24) -12px -12px 32px 0px) for truly elevated elements to indicate interactive depth or importance.
- Do not use generic system fonts when Inter or its customized variants are available; maintaining the specific typographic choices is crucial to brand identity.
- Avoid using small, pixel-based letter spacing adjustments on body copy; reserve negative letter spacing for larger headlines as defined in the type scale.

## Elevation

- **Card / Elevated Section:** `box-shadow: rgba(0, 0, 0, 0.24) -12px -12px 32px 0px`
- **Product Showcase Shadow:** `box-shadow: rgba(104, 65, 13, 0.23) 0px 10px 20px 0px`

## Imagery

The visual language is a blend of product photography and abstract, colored graphics. Product images are tightly cropped, studio-lit, and focus on the hardware itself against dark, often reflective, backgrounds, lending a premium, almost jewelry-like quality. These are typically contained with soft, rounded corners (12px-24px). Abstract graphics, often gradient-filled (like the Deep Web Gradient or Plasma Flow Gradient), serve as decorative backdrops for feature sections, adding depth and energy without specific representational content. Icons are minimal, often line-based or simple filled shapes, using accent colors like Neon Blue (#41bdf5) or Electric Green (#009b00) when not Moonlight Glimmer (#ffffff). The overall role of imagery is to showcase the product with precision, explain concepts abstractly through color, and create an immersive, futuristic atmosphere.

## Layout

The page primarily uses a full-bleed dark background, creating an expansive, borderless feel. Content is typically centered within a max-width constraint (though not explicitly defined, visually appears around 1200-1400px). The hero section features a large, centered headline over a dark background with subtle product imagery. Section rhythm is marked by significant vertical spacing, often with different gradient backgrounds or distinct product showcases. Content arrangement frequently alternates between large stacked headlines and subtext, followed by a product visual or feature grid. Card grids for features feature 3-column layouts. The navigation is a minimalist top bar, staying hidden on scroll but appearing on interaction, maintaining a clean, uncluttered visual.

## Agent Prompt Guide

### Quick Color Reference
- **Text:** #ffffff (Moonlight Glimmer)
- **Background:** #000000 (Midnight Void)
- **CTA:** #5351f3 (Violet Impulse)
- **Border:** #ffffff (Moonlight Glimmer, for ghost buttons/inputs)
- **Accent:** #e3a081 (Sunset Ember)

### 3-5 Example Component Prompts
1. **Create a Primary Call-to-Action Button:** background #5351f3, text #ffffff, border none, radius 32px, padding 12px 16px. Text 'Order Now' using Inter 16px weight 400.
2. **Design a Feature Teaser Card:** background linear-gradient(-26deg, rgba(0, 86, 255, 0.29) 0%, rgb(194, 142, 1) 100%), radius 24px, no border, with an icon (Moonlight Glimmer #ffffff fill) and body text at Inter 14px weight 400, color #ffffff.
3. **Generate a Hero Section Headline:** text 'Your cloud. In your ' using Inter Display 43px weight 600 color #ffffff, followed by 'home.' in Inter Display 43px weight 600 color #e3a081. Letter spacing -0.02em for both. Place this centered over a Midnight Void (#000000) background.
4. **Build an Input Field:** background transparent, border 1px solid #ffffff, radius 20px, padding 14px 10px. Placeholder text 'Enter your email' in System Gray (#797985), actual text in Moonlight Glimmer (#ffffff), using Inter 16px weight 400.
5. **Create a Ghost Navigation Button:** background transparent, text #ffffff, border 1px solid #ffffff, radius 99px, padding 8px 16px. Text 'Explore' using Inter 12px weight 400.

## Similar Brands

- **Apple** — Premium dark mode aesthetic, focus on hardware photography against dark backgrounds, minimalist typography.
- **Linear** — Sophisticated dark UI, emphasis on crisp typography, subtle gradients for depth, and controlled use of accent colors.
- **Figma (dark mode)** — Deep dark surfaces, strategic use of vibrant accent colors for interactivity, and emphasis on clear content structure within a dark theme.
- **Framework Laptop** — Clean, product-focused presentation with strong typography and a subtle tech aesthetic, often with dark modes available.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-midnight-void: #000000;
  --color-obsidian-surface: #292929;
  --color-onyx-shadow: #180f03;
  --color-moonlight-glimmer: #ffffff;
  --color-warm-gray: #61635d;
  --color-cool-steel: #cccccc;
  --color-pale-mist: #e0e0e0;
  --color-system-gray: #797985;
  --color-0a0a0a: #0a0a0a;
  --color-violet-impulse: #5351f3;
  --color-sunset-ember: #e3a081;
  --color-neon-blue: #41bdf5;
  --color-electric-green: #009b00;
  --color-deep-web-gradient: #0056ff;
  --gradient-deep-web-gradient: linear-gradient(-26deg, rgba(0, 86, 255, 0.29) 0%, rgb(194, 142, 1) 100%);
  --color-plasma-flow-gradient: #855dff;
  --gradient-plasma-flow-gradient: linear-gradient(-26deg, rgba(133, 93, 255, 0.27) 0%, rgb(254, 121, 0) 100%);
  --color-core-melt-gradient: #591010;
  --gradient-core-melt-gradient: linear-gradient(-26deg, rgb(89, 16, 16) 0%, rgba(69, 0, 16, 0.46) 22.631%, rgba(255, 59, 59, 0.5) 100%);
  --color-deep-sky-gradient: #0657a1;
  --gradient-deep-sky-gradient: radial-gradient(100% 147.839% at 0px 4.44089e-14%, rgb(6, 87, 161) 0%, rgb(5, 30, 34) 36.2271%, rgba(3, 29, 60, 0.97) 72.4655%, rgba(30, 83, 161, 0.93) 84.8958%, rgb(53, 90, 163) 100%);

  /* Typography — Font Families */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-condensed: 'Roboto Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.2;
  --text-sm: 13px;
  --leading-sm: 1.3;
  --text-sm-2: 14px;
  --leading-sm-2: 1.2;
  --text-base: 16px;
  --leading-base: 1.24;
  --text-lg: 18px;
  --leading-lg: 1.3;
  --text-xl: 20px;
  --leading-xl: 1.1;
  --text-xl-2: 23px;
  --leading-xl-2: 1.1;
  --text-2xl: 24px;
  --leading-2xl: 1.1;
  --text-2xl-2: 27px;
  --leading-2xl-2: 1.2;
  --text-3xl: 32px;
  --leading-3xl: 1.2;
  --text-4xl: 36px;
  --leading-4xl: 1.2;
  --text-4xl-2: 43px;
  --leading-4xl-2: 1.2;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;

  /* Layout */
  --card-padding: 12px;

  /* Border Radius */
  --radius-sm: 2.5px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 48px;
  --radius-full-2: 60px;
  --radius-full-3: 93px;
  --radius-full-4: 99px;

  /* Named Radii */
  --radius-cards: 24px;
  --radius-pills: 99px;
  --radius-images: 12px;
  --radius-inputs: 20px;
  --radius-buttons: 32px;
  --radius-default: 16px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.24) -12px -12px 32px 0px;
  --shadow-lg: rgba(104, 65, 13, 0.23) 0px 10px 20px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-midnight-void: #000000;
  --color-obsidian-surface: #292929;
  --color-onyx-shadow: #180f03;
  --color-moonlight-glimmer: #ffffff;
  --color-warm-gray: #61635d;
  --color-cool-steel: #cccccc;
  --color-pale-mist: #e0e0e0;
  --color-system-gray: #797985;
  --color-0a0a0a: #0a0a0a;
  --color-violet-impulse: #5351f3;
  --color-sunset-ember: #e3a081;
  --color-neon-blue: #41bdf5;
  --color-electric-green: #009b00;
  --color-deep-web-gradient: #0056ff;
  --color-plasma-flow-gradient: #855dff;
  --color-core-melt-gradient: #591010;
  --color-deep-sky-gradient: #0657a1;

  /* Typography */
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-display: 'Inter Display', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter-tight: 'Inter Tight', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-manrope: 'Manrope', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-roboto-condensed: 'Roboto Condensed', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.2;
  --text-sm: 13px;
  --leading-sm: 1.3;
  --text-sm-2: 14px;
  --leading-sm-2: 1.2;
  --text-base: 16px;
  --leading-base: 1.24;
  --text-lg: 18px;
  --leading-lg: 1.3;
  --text-xl: 20px;
  --leading-xl: 1.1;
  --text-xl-2: 23px;
  --leading-xl-2: 1.1;
  --text-2xl: 24px;
  --leading-2xl: 1.1;
  --text-2xl-2: 27px;
  --leading-2xl-2: 1.2;
  --text-3xl: 32px;
  --leading-3xl: 1.2;
  --text-4xl: 36px;
  --leading-4xl: 1.2;
  --text-4xl-2: 43px;
  --leading-4xl-2: 1.2;

  /* Spacing */
  --spacing-5: 5px;
  --spacing-6: 6px;
  --spacing-8: 8px;
  --spacing-10: 10px;
  --spacing-11: 11px;
  --spacing-12: 12px;
  --spacing-13: 13px;
  --spacing-14: 14px;
  --spacing-16: 16px;
  --spacing-19: 19px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-25: 25px;
  --spacing-40: 40px;
  --spacing-50: 50px;
  --spacing-60: 60px;

  /* Border Radius */
  --radius-sm: 2.5px;
  --radius-md: 5px;
  --radius-lg: 8px;
  --radius-xl: 12px;
  --radius-2xl: 16px;
  --radius-3xl: 24px;
  --radius-3xl-2: 32px;
  --radius-3xl-3: 40px;
  --radius-full: 48px;
  --radius-full-2: 60px;
  --radius-full-3: 93px;
  --radius-full-4: 99px;

  /* Shadows */
  --shadow-xl: rgba(0, 0, 0, 0.24) -12px -12px 32px 0px;
  --shadow-lg: rgba(104, 65, 13, 0.23) 0px 10px 20px 0px;
}
```
