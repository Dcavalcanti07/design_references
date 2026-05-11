# Todoist — Style Reference
> Warm, minimal productivity suite. Like a neatly organized desk bathed in natural light.

**Theme:** light

This design system presents a clean, business-casual aesthetic, grounded in warm off-white and charcoal neutrals, punctuated by a signature vibrant red-orange. The generous use of rounded corners (15px for prominent elements, 8px for most others) softens the utilitarian feel of the task manager, while subtle, low-opacity shadows add minimal depth without visual clutter, creating an approachable, yet professional, interface.

## Tokens — Colors

| Name | Value | Token | Role |
|------|-------|-------|------|
| Faded Charcoal | `#25221` | `--color-faded-charcoal` | Primary text, headings, icons, borders, prominent interactive elements. It's the dominant dark shade, appearing in place of true black. |
| Paper White | `#fefdfc` | `--color-paper-white` | Page backgrounds, card surfaces, primary light background. Provides a soft, warm canvas contrasting with Faded Charcoal. |
| Soft Gray | `#d7d6d4` | `--color-soft-gray` | Subtle borders, inactive elements, muted backgrounds. A pale, desaturated gray for separation without harshness. |
| Light Peach | `#fff6f0` | `--color-light-peach` | Occasional background accents, footer background, illustration fills. A very pale, warm background hint. |
| Subtle Ash | `#6f6c69` | `--color-subtle-ash` | Secondary text, descriptive elements, subdued icons. Provides hierarchy without being too light. |
| True Black | `#000000` | `--color-true-black` | System icons, some text elements. Used sparingly, mostly for icon rendering or specific high-contrast text. |
| Dusty Sage | `#94928f` | `--color-dusty-sage` | Tertiary text, subtle icon detailing. Further de-emphasizes content. |
| Action Red | `#e34432` | `--color-action-red` | Primary call-to-action buttons, active navigation indicators, key interactive elements. This vivid red stands out against the muted palette. |
| Link Orange | `#cf3520` | `--color-link-orange` | Inline links, slightly darker shade of brand red used for text. |
| Accent Blue | `#0f66ae` | `--color-accent-blue` | Secondary links, distinct interactive elements. A cool counterpoint to the dominant red. |
| Teal Accent | `#497d7` | `--color-teal-accent` | Specific illustrative text or decorative elements. A muted teal that occasionally appears as an accent. |
| Success Green | `#4c7a45` | `--color-success-green` | Success states, specific informational badges. A moderate green for positive affirmation. |
| Badge Green | `#446c3d` | `--color-badge-green` | Text color for specific badges, slightly darker than Success Green. |
| Light Green Tint | `#f0f6df` | `--color-light-green-tint` | Background for success badges. A very light, near-gray green. |

## Tokens — Typography

### Graphik — Primary display and heading font. Used for prominent titles and key marketing messages. The slight tightening of letter spacing at larger sizes gives it a refined, bespoke feel, avoiding the sprawl of default sans-serifs. · `--font-graphik`
- **Substitute:** system-ui
- **Weights:** 400, 600, 700
- **Sizes:** 16px, 22px, 38px, 44px, 55px
- **Line height:** 1.00, 1.15, 1.28
- **Letter spacing:** -0.0100em at 55px, -0.0050em at 44px, 16px, 22px, 38px
- **Role:** Primary display and heading font. Used for prominent titles and key marketing messages. The slight tightening of letter spacing at larger sizes gives it a refined, bespoke feel, avoiding the sprawl of default sans-serifs.

### Inter — Primary body font, UI elements, buttons, links, and forms. Its wide range of weights and subtle tracking variations ensure readability and visual hierarchy across all transactional and informational content. · `--font-inter`
- **Substitute:** system-ui
- **Weights:** 400, 475, 500, 600, 625, 700
- **Sizes:** 12px, 14px, 15px, 16px, 17px, 18px, 19px, 21px
- **Line height:** 1.00, 1.35, 1.40, 1.50, 1.60, 1.75
- **Letter spacing:** 0.0050em at 21px, 0.0100em at 18px, 0.0120em at 19px, 0.0250em at 17px
- **Role:** Primary body font, UI elements, buttons, links, and forms. Its wide range of weights and subtle tracking variations ensure readability and visual hierarchy across all transactional and informational content.

### Arial — Fallback font for specific input elements, indicating utilitarian use where broad system compatibility is prioritized over specific branding. · `--font-arial`
- **Substitute:** system-ui
- **Weights:** 400
- **Sizes:** 13px
- **Line height:** 1.20
- **Letter spacing:** normal
- **Role:** Fallback font for specific input elements, indicating utilitarian use where broad system compatibility is prioritized over specific branding.

### Caecilia — Used for specific body text sections, particularly for testimonials or quotes. Its serif nature provides a distinct, classic, and editorial feel, breaking the sans-serif dominance. · `--font-caecilia`
- **Substitute:** serif
- **Weights:** 400
- **Sizes:** 20px
- **Line height:** 1.80
- **Letter spacing:** normal
- **Role:** Used for specific body text sections, particularly for testimonials or quotes. Its serif nature provides a distinct, classic, and editorial feel, breaking the sans-serif dominance.

### Shantell Sans — Rarely used, possibly for decorative or illustrative text. Its distinct, informal style provides a whimsical contrast to the otherwise structured design. · `--font-shantell-sans`
- **Substitute:** cursive
- **Weights:** 400
- **Sizes:** 19px
- **Line height:** 1.60
- **Letter spacing:** 0.0100em
- **Role:** Rarely used, possibly for decorative or illustrative text. Its distinct, informal style provides a whimsical contrast to the otherwise structured design.

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
| 32 | 32px | `--spacing-32` |
| 48 | 48px | `--spacing-48` |
| 64 | 64px | `--spacing-64` |
| 128 | 128px | `--spacing-128` |
| 192 | 192px | `--spacing-192` |

### Border Radius

| Element | Value |
|---------|-------|
| cards | 10px |
| badges | 6px |
| images | 15px |
| buttons | 15px |
| default | 8px |

### Shadows

| Name | Value | Token |
|------|-------|-------|
| subtle | `rgba(37, 34, 30, 0.04) 0px 1px 0px 0px` | `--shadow-subtle` |
| lg | `rgba(37, 34, 30, 0.07) 0px 14px 19px -9px, rgba(37, 34, 3...` | `--shadow-lg` |

### Layout

- **Section gap:** 64px
- **Card padding:** 0px
- **Element gap:** 4px

## Components

### Primary Action Button
**Role:** Main call to action

Background: Action Red (#e34432), Text: Paper White (#ffffff), Border Radius: 15px, Padding: 12px vertical, 16px horizontal. Prominent for guiding user actions.

### Text Only Button
**Role:** Secondary action in nav/toolbar

Background: transparent, Text: Faded Charcoal (#25221e), Border: Faded Charcoal (#25221e), Border Radius: 8px, Padding: 9px vertical, 14px horizontal. Minimalist interaction for less emphasis.

### Subtle Action Button
**Role:** Tertiary actions, filters, or less critical interactions

Background: rgba(37, 34, 30, 0.07), Text: Faded Charcoal (#25221e), Border: Faded Charcoal (#25221e), Border Radius: 8px, Padding: 8px all sides. Provides a hint of background for subtle interaction.

### Hero Pill Button
**Role:** Prominent, often decorative buttons in hero sections

Background: rgba(37, 34, 30, 0.83), Text: Paper White (#ffffff), Border: Paper White (#ffffff), Border Radius: 15px, Padding: 0px vertical, 27px horizontal. Large, rounded, and dark for visual impact.

### Feature Card
**Role:** Information display, grouping related content

Background: Paper White (#fefdfc), Border Radius: 10px, Shadow: rgba(37, 34, 30, 0.04) 0px 1px 0px 0px, Padding: 0px. A clean, slightly elevated surface for content sections.

### Success Badge
**Role:** Status indicators or small informational tags

Background: Light Green Tint (#f0f6df), Text: Badge Green (#446c3d), Border Radius: 6px, Padding: 4px vertical, 8px horizontal. Clearly signals positive status.

### Form Input Field
**Role:** User data entry

Background: transparent, Text: Faded Charcoal (#25221e), Border: Faded Charcoal (#25221e), Border Radius: 8px, Padding: 7px vertical, 32px right, 35px left. Features generous horizontal padding for internal iconography or labels.

## Do's and Don'ts

### Do
- Use Action Red (#e34432) exclusively for primary calls-to-action and active states to maintain visual prominence.
- Apply 15px border-radius to prominent interactive elements like buttons and large images for a soft, friendly aesthetic.
- Utilize Graphik for all main headings and titles, ensuring distinct letter spacing: -0.0100em at 55px, -0.0050em at 44px, and normal at smaller sizes.
- Maintain a clear hierarchy using Paper White (#fefdfc) for backgrounds and Faded Charcoal (#25221e) for primary text and elements.
- Employ the subtle shadow rgba(37, 34, 30, 0.04) 0px 1px 0px 0px for all cards to provide slight elevation without heavy visual weight.
- Ensure generous padding on interactive elements, like 12px vertical and 16px horizontal for primary buttons, to create comfortable touch targets.

### Don't
- Do not use true black (#000000) for body text; instead, use Faded Charcoal (#25221e) or Subtle Ash (#6f6c69) for softer contrast.
- Avoid using multiple chromatic colors in close proximity; the palette should remain largely neutral with controlled accents.
- Do not use sharp corners; the minimum border-radius for UI elements should be 6px (for badges), with 8px and 15px being more common.
- Refrain from using heavy or multiple shadows; subtle single-layer shadows are the standard for elevation.
- Do not introduce new decorative fonts beyond Caecilia unless specifically approved; maintain the Graphik and Inter pairing.
- Avoid making inline links blend with body text; always use Link Orange (#cf3520) or Accent Blue (#0f66ae) for clear distinction.

## Elevation

- **Feature Card:** `rgba(37, 34, 30, 0.04) 0px 1px 0px 0px`
- **Prominent Buttons:** `rgba(37, 34, 30, 0.07) 0px 14px 19px -9px, rgba(37, 34, 30, 0.18) 0px 10px 48px 0px`

## Imagery

The visual language focuses on clean product screenshots of the Todoist app, often embedded within device mockups (like phones or laptops). These are typically contained within a design, not full-bleed, and often have generous rounded corners (15px). Photography is absent. Illustrations are minimal, sometimes involving abstract, squiggly lines or simple star shapes (#fff6f0 for fills) used decoratively in backgrounds, providing a touch of playfulness without being distracting. Icons are primarily line-based or solid, rendered in Faded Charcoal or True Black, often accompanying text to explain features. The overall density suggests a balance between UI elements and supportive, explanatory visuals.

## Layout

The page primarily uses a max-width contained layout, with content centered. The hero section often features a prominent headline and text on the left, paired with a device mockup on the right. Below the hero, the content typically alternates between text-left/image-right and text-right/image-left sections, providing an engaging rhythm. Sections are clearly delineated by consistent vertical spacing (sectionGap) and sometimes subtly different background colors (like Light Peach for the footer). There are clear examples of multi-column layouts, particularly for feature grids or testimonials (3-column layout implied by testimonial spacing). The navigation is a sticky top bar with a mix of text links and a prominent 'Start for free' button.

## Agent Prompt Guide

### Quick Color Reference
- **Primary Text:** #25221 (Faded Charcoal)
- **Background:** #fefdfc (Paper White)
- **CTA Button:** #e34432 (Action Red)
- **Border/Subtle elements:** #d7d6d4 (Soft Gray)
- **Accent Link:** #0f66ae (Accent Blue)

### 3-5 Example Component Prompts
1. **Create a Primary Action Button:** Text 'Start Now' in Inter 475 weight, color Paper White (#ffffff). Background Action Red (#e34432), border-radius 15px. Padding 12px vertical, 16px horizontal.
2. **Generate a Feature Card:** Background Paper White (#fefdfc), border-radius 10px, box-shadow rgba(37, 34, 30, 0.04) 0px 1px 0px 0px. Inside, headline 'Clarity, finally.' using Graphik 600 weight at 38px, color Faded Charcoal (#25221e). Body text 'Get things done.' in Inter 400 weight at 16px, color Subtle Ash (#6f6c69).
3. **Design a Success Badge:** Text 'New!' in Inter 400 weight, color Badge Green (#446c3d). Background Light Green Tint (#f0f6df), border-radius 6px. Padding 4px vertical, 8px horizontal.
4. **Build a subtle navigation link:** Text 'Pricing' in Graphik 400 weight at 16px, color Faded Charcoal (#25221e). Background transparent, border transparent, border-radius 8px. Padding 9px vertical, 14px horizontal.

## Similar Brands

- **Asana** — Shares a clean, light SaaS UI with a focus on task management tools and subtle color accents for interaction cues.
- **Notion** — Employs a warm, almost-white background, minimal design, and a blend of custom and system fonts for professional clarity without appearing cold.
- **ClickUp** — Utilizes a functional, modern design approach with clear typography, intuitive layouts, and controlled use of brand colors for hierarchy.
- **Monday.com** — Features a light, inviting color palette, rounded elements, and a similar approach to using product screenshots within device mockups.

## Quick Start

### CSS Custom Properties

```css
:root {
  /* Colors */
  --color-faded-charcoal: #25221;
  --color-paper-white: #fefdfc;
  --color-soft-gray: #d7d6d4;
  --color-light-peach: #fff6f0;
  --color-subtle-ash: #6f6c69;
  --color-true-black: #000000;
  --color-dusty-sage: #94928f;
  --color-action-red: #e34432;
  --color-link-orange: #cf3520;
  --color-accent-blue: #0f66ae;
  --color-teal-accent: #497d7;
  --color-success-green: #4c7a45;
  --color-badge-green: #446c3d;
  --color-light-green-tint: #f0f6df;

  /* Typography — Font Families */
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caecilia: 'Caecilia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-shantell-sans: 'Shantell Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.5;
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-sm-2: 14px;
  --leading-sm-2: 1.35;
  --text-base: 15px;
  --leading-base: 1.35;
  --text-base-2: 16px;
  --leading-base-2: 1;
  --text-lg: 17px;
  --leading-lg: 1.4;
  --text-lg-2: 18px;
  --leading-lg-2: 1.75;
  --text-lg-3: 19px;
  --leading-lg-3: 1.4;
  --text-xl: 20px;
  --leading-xl: 1.8;
  --text-xl-2: 21px;
  --leading-xl-2: 1.6;
  --text-xl-3: 22px;
  --leading-xl-3: 1.28;
  --text-4xl: 38px;
  --leading-4xl: 1.28;

  /* Typography — Weights */
  --font-weight-regular: 400;
  --font-weight-w475: 475;
  --font-weight-medium: 500;
  --font-weight-semibold: 600;
  --font-weight-w625: 625;
  --font-weight-bold: 700;

  /* Spacing */
  --spacing-unit: 4px;
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Layout */
  --section-gap: 64px;
  --card-padding: 0px;
  --element-gap: 4px;

  /* Border Radius */
  --radius-sm: 2.5px;
  --radius-lg: 8px;
  --radius-xl: 15px;

  /* Named Radii */
  --radius-cards: 10px;
  --radius-badges: 6px;
  --radius-images: 15px;
  --radius-buttons: 15px;
  --radius-default: 8px;

  /* Shadows */
  --shadow-subtle: rgba(37, 34, 30, 0.04) 0px 1px 0px 0px;
  --shadow-lg: rgba(37, 34, 30, 0.07) 0px 14px 19px -9px, rgba(37, 34, 30, 0.18) 0px 10px 48px 0px;
}
```

### Tailwind v4

```css
@theme {
  /* Colors */
  --color-faded-charcoal: #25221;
  --color-paper-white: #fefdfc;
  --color-soft-gray: #d7d6d4;
  --color-light-peach: #fff6f0;
  --color-subtle-ash: #6f6c69;
  --color-true-black: #000000;
  --color-dusty-sage: #94928f;
  --color-action-red: #e34432;
  --color-link-orange: #cf3520;
  --color-accent-blue: #0f66ae;
  --color-teal-accent: #497d7;
  --color-success-green: #4c7a45;
  --color-badge-green: #446c3d;
  --color-light-green-tint: #f0f6df;

  /* Typography */
  --font-graphik: 'Graphik', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-inter: 'Inter', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-arial: 'Arial', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-caecilia: 'Caecilia', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  --font-shantell-sans: 'Shantell Sans', ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;

  /* Typography — Scale */
  --text-xs: 12px;
  --leading-xs: 1.5;
  --text-sm: 13px;
  --leading-sm: 1.2;
  --text-sm-2: 14px;
  --leading-sm-2: 1.35;
  --text-base: 15px;
  --leading-base: 1.35;
  --text-base-2: 16px;
  --leading-base-2: 1;
  --text-lg: 17px;
  --leading-lg: 1.4;
  --text-lg-2: 18px;
  --leading-lg-2: 1.75;
  --text-lg-3: 19px;
  --leading-lg-3: 1.4;
  --text-xl: 20px;
  --leading-xl: 1.8;
  --text-xl-2: 21px;
  --leading-xl-2: 1.6;
  --text-xl-3: 22px;
  --leading-xl-3: 1.28;
  --text-4xl: 38px;
  --leading-4xl: 1.28;

  /* Spacing */
  --spacing-4: 4px;
  --spacing-8: 8px;
  --spacing-12: 12px;
  --spacing-16: 16px;
  --spacing-20: 20px;
  --spacing-24: 24px;
  --spacing-32: 32px;
  --spacing-48: 48px;
  --spacing-64: 64px;
  --spacing-128: 128px;
  --spacing-192: 192px;

  /* Border Radius */
  --radius-sm: 2.5px;
  --radius-lg: 8px;
  --radius-xl: 15px;

  /* Shadows */
  --shadow-subtle: rgba(37, 34, 30, 0.04) 0px 1px 0px 0px;
  --shadow-lg: rgba(37, 34, 30, 0.07) 0px 14px 19px -9px, rgba(37, 34, 30, 0.18) 0px 10px 48px 0px;
}
```
