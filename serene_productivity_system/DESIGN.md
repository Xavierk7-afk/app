---
name: Serene Productivity System
colors:
  surface: '#f9f9fc'
  surface-dim: '#dadadd'
  surface-bright: '#f9f9fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f6'
  surface-container: '#eeedf1'
  surface-container-high: '#e8e8eb'
  surface-container-highest: '#e2e2e5'
  on-surface: '#1a1c1e'
  on-surface-variant: '#42474e'
  inverse-surface: '#2f3033'
  inverse-on-surface: '#f1f0f4'
  outline: '#72777e'
  outline-variant: '#c2c7ce'
  surface-tint: '#396285'
  primary: '#002740'
  on-primary: '#ffffff'
  primary-container: '#0c3d5e'
  on-primary-container: '#80a8ce'
  inverse-primary: '#a2cbf2'
  secondary: '#006492'
  on-secondary: '#ffffff'
  secondary-container: '#6ac1fd'
  on-secondary-container: '#004e73'
  tertiary: '#00292c'
  on-tertiary: '#ffffff'
  tertiary-container: '#004144'
  on-tertiary-container: '#4db2b8'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cde5ff'
  primary-fixed-dim: '#a2cbf2'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#1e4a6c'
  secondary-fixed: '#cae6ff'
  secondary-fixed-dim: '#8cceff'
  on-secondary-fixed: '#001e2f'
  on-secondary-fixed-variant: '#004b6f'
  tertiary-fixed: '#91f2f8'
  tertiary-fixed-dim: '#74d6dc'
  on-tertiary-fixed: '#002021'
  on-tertiary-fixed-variant: '#004f53'
  background: '#f9f9fc'
  on-background: '#1a1c1e'
  surface-variant: '#e2e2e5'
typography:
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 17px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 20px
  lg: 32px
  xl: 48px
  margin-mobile: 24px
  gutter-mobile: 16px
---

## Brand & Style

The design system is rooted in a **Minimalist** and **Tactile** aesthetic tailored for a younger audience that values mental clarity over digital noise. The personality is "calmly productive"—it moves away from the aggressive, high-pressure "hustle" culture and toward a more organic, human-centric experience.

The visual narrative prioritizes breathing room, utilizing generous whitespace to reduce cognitive load. By blending soft, rounded geometry with a cool, aquatic-inspired color palette, the UI feels less like a technical tool and more like a physical journal or a well-organized workspace. The emotional goal is to evoke a sense of relief and focus every time the user opens the app.

## Colors

The palette is strictly derived from a sophisticated range of blues and teals, updated to provide a more vibrant and energetic secondary interaction layer.

- **Deep Blue (#0c3d5e):** The primary brand color. Used for high-emphasis actions, headers, and navigation anchors to provide grounding and legibility.
- **Ocean Blue (#2e90c9):** The new secondary color. This more saturated blue is used for secondary buttons, active selection states, and highlighting key interface elements.
- **Cyan (#6fd1d7):** The tertiary accent. Used for progress indicators, success markers, and decorative accents that require a soft, luminous quality.

The default mode is **Light**, emphasizing a clean "paper-like" canvas.

## Typography

This design system uses **Plus Jakarta Sans** across all levels. This font family was selected for its modern, rounded terminals which appear friendly and approachable without feeling juvenile. 

For mobile efficiency, headlines utilize tight letter spacing to maintain a compact yet bold presence. Body text is set with generous line heights to ensure long task descriptions remain legible and airy. Weight is used strategically: bold weights are reserved for page titles and task headers, while medium and regular weights handle metadata and instructional text.

## Layout & Spacing

The layout philosophy follows a **Fluid Grid** approach with substantial internal margins to mimic the spaciousness of the reference imagery. 

On mobile devices, a **24px outer margin** is mandatory to prevent content from feeling cramped against the screen edges. Vertical spacing follows an 8px base unit, with task cards separated by 12px or 16px to create clear visual grouping without the need for heavy dividers. Large "safe areas" are maintained at the bottom of the screen to accommodate the primary floating navigation and action triggers.

## Elevation & Depth

Depth in this design system is created through **Ambient Shadows** and **Tonal Layers** rather than harsh borders. 

- **Surface Layer:** The primary background is a very light off-white (#f9f9fc).
- **Object Layer:** Interactive cards and buttons use a pure white (#ffffff) background.
- **Shadow Profile:** Shadows are highly diffused, using a low-opacity Deep Blue tint (rgba(12, 61, 94, 0.05)) with a large blur radius (20px to 30px) and a subtle 4px vertical offset. This creates a "lifted" effect that feels soft and natural.
- **Active State:** When pressed, elements should subtly scale down (to 98%) rather than increasing shadow intensity, reinforcing the tactile, physical metaphor.

## Shapes

The shape language is characterized by **Rounded** geometry. Consistent with the goal of a friendly UI, sharp corners are entirely avoided. 

- **Standard Cards:** Use a 1rem (16px) corner radius.
- **Buttons & Inputs:** Use a 1rem (16px) or fully pill-shaped (100px) radius for larger touch targets.
- **Bottom Sheets:** Use a 1.5rem (24px) radius on top corners to create a soft, containerized feel when drawers are invoked.

## Components

### Buttons
Primary buttons are large (minimum height 56px) with pill-shaped corners. They utilize the Deep Blue (#0c3d5e) background with white text for high-impact actions, or the Ocean Blue (#2e90c9) for secondary interactions.

### Task Cards
Cards use a pure white background with the defined ambient shadow. Internal padding should be a minimum of 20px. Task titles use `title-lg`, and metadata (due dates, tags) uses `label-lg` in Ocean Blue (#2e90c9).

### Checkboxes
To maintain the "non-technological" feel, checkboxes are replaced with large, circular touch targets. An empty circle with a subtle 1.5px border (Ocean Blue) represents the "todo" state; a Cyan (#6fd1d7) filled circle with a white checkmark represents the "complete" state.

### Input Fields
Inputs are borderless, using a very light tint of the primary color as a background fill. They feature 16px rounded corners and large internal padding to ensure the text has room to breathe.

### Navigation Bar
The bottom navigation should be a floating container with high roundedness (32px+), detached from the screen edges, using backdrop blur (if possible) or a pure white surface with a soft shadow to appear as if it is hovering over the list content.