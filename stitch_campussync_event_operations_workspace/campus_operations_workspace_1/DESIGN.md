---
name: Campus Operations Workspace
colors:
  surface: '#faf9ff'
  surface-dim: '#d5d9ea'
  surface-bright: '#faf9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f3ff'
  surface-container: '#e9edfe'
  surface-container-high: '#e4e8f8'
  surface-container-highest: '#dee2f3'
  on-surface: '#161b27'
  on-surface-variant: '#464553'
  inverse-surface: '#2b303d'
  inverse-on-surface: '#edf0ff'
  outline: '#777585'
  outline-variant: '#c7c4d6'
  surface-tint: '#4e4ec9'
  primary: '#4241bc'
  on-primary: '#ffffff'
  primary-container: '#5b5bd6'
  on-primary-container: '#edeaff'
  inverse-primary: '#c1c1ff'
  secondary: '#565f6d'
  on-secondary: '#ffffff'
  secondary-container: '#dae3f4'
  on-secondary-container: '#5c6573'
  tertiary: '#804300'
  on-tertiary: '#ffffff'
  tertiary-container: '#a35700'
  on-tertiary-container: '#ffe8d9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c1c1ff'
  on-primary-fixed: '#0a006b'
  on-primary-fixed-variant: '#3533b0'
  secondary-fixed: '#dae3f4'
  secondary-fixed-dim: '#bec7d7'
  on-secondary-fixed: '#131c28'
  on-secondary-fixed-variant: '#3e4755'
  tertiary-fixed: '#ffdcc3'
  tertiary-fixed-dim: '#ffb77e'
  on-tertiary-fixed: '#2f1500'
  on-tertiary-fixed-variant: '#6e3900'
  background: '#faf9ff'
  on-background: '#161b27'
  surface-variant: '#dee2f3'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.02em
  code-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
    letterSpacing: 0em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-lg: 1.5rem
  margin: 1rem
  margin-md: 1.5rem
  margin-lg: 2rem
  space-xxs: 0.125rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

The design system establishes a high-performance, distraction-free operations workspace built specifically for student leaders, administrative officers, and campus facility coordinators. Moving decisively away from antiquated, cluttered academic software, the aesthetic adheres to utility-first minimalism inspired by modern productivity environments like Linear and Notion.

The personality is dependable, agile, and structured:
- **Tone:** Methodical, frictionless, and respectful of cognitive bandwidth during high-stress scheduling and approval periods.
- **Visual Style:** Minimalist, data-dense, and structured. Interfaces rely on precise 1px borders, generous internal rhythm, uniform typographic pacing, and sharp semantic cues rather than ornamental gradients or decorative visual effects.
- **User Perception:** Feels like an elite engineering task manager retrofitted for institutional workflows, instilling speed, transparency, and administrative rigor.

## Colors

The palette is engineered for prolonged operational focus, strictly avoiding stark pure-black contrasts and heavy chromatic saturation.

### Surface Hierarchy
- **Canvas Base (`#F7F8FA`):** An engineered off-white canvas that softens screen glare and establishes structural separation from interactive surfaces.
- **Card & Surface (`#FFFFFF`):** High-clarity white for cards, slide-over panels, inspector rails, and modular data containers.
- **Border Default (`#E2E5EB`):** A hairline 1px boundary separating panels, table cells, and form zones without visual noise.

### Text & Tone
- **Primary Ink (`#1F2430`):** Deep charcoal delivering decisive readability for headers, primary data cells, and critical state indicators.
- **Secondary Slate (`#5B6472`):** Calm slate for subheaders, timestamps, metadata keys, and secondary navigation elements.
- **Muted Placeholder (`#9AA2B1`):** Subdued boundary color for empty states, field hints, and trailing iconography.

### Accents & Semantic Badges
- **Primary Indigo (`#5B5BD6` / Hover `#4E4EC5`):** Reserved for primary workflow actions (e.g., "Submit Permit", "Publish Schedule"), focused state rings, and active tab rules.
- **Success / Approved (`#10B981` / Surface `#ECFDF5`):** Clear emerald indicator for approved facility bookings, resolved logistics tickets, and cleared budgets.
- **Warning / Review Pending (`#F59E0B` / Surface `#FFFBEB`):** Warm amber for pending dean signatures, conditional permits, and resource warnings.
- **Critical / Rejected (`#EF4444` / Surface `#FEF2F2`):** Restrained crimson for hard venue conflicts, policy violations, and canceled reservations.

## Typography

The typographic system utilizes a singular, strictly calibrated implementation of Inter across all hierarchical tiers. By utilizing tabular figures (`font-variant-numeric: tabular-nums`) throughout operational contexts, the system guarantees flawless alignment in dense timetables, capacity tracking metrics, and room inventory schedules.

- **Display & Headings:** Scaled conservatively. Headings do not dominate the screen; they establish clear spatial bounds for operational tables and split views without pushing data below the fold.
- **Body & Data Grid:** The backbone of the system rests on 14px (`body-md`) and 13px (`body-sm`), paired with disciplined line heights to preserve vertical density while maintaining readability across high-volume log streams.
- **Labels & Microcopy:** Rendered with medium weight (`500`) and slight tracking expansion for instant parsing in badge pills, table headers, breadcrumbs, and shortcut tooltips.

## Layout & Spacing

The layout is built upon an 8px structural grid (with a 4px sub-grid for fine internal alignment), prioritized for dual-pane reviews, split workflows, and docked utility drawers.

### Structural Framework
- **Shell Layout:** A persistent 240px collateral navigation sidebar on the left, an expansive core workbench in the center, and an optional 380px contextual slide-over inspector on the right.
- **Split-Screen Review Pattern:** When adjudicating permit requests or venue conflicts, the interface bifurcates into a 50/50 split canvas—displaying submitted proposal materials on the left and administrative audit rails on the right.
- **Density Scaling:**
  - **Desktop (>=1280px):** Wide, multi-column tables with inline quick actions, sticky table headers, and an always-accessible side inspector panel.
  - **Tablet (768px - 1279px):** Inspector panels convert to full slide-overs triggered on demand; data tables collapse minor metadata into drawer views.
  - **Mobile (<768px):** Single-column stacked workflow, prioritizing urgent status alerts, quick approval buttons, and notification feeds.

## Elevation & Depth

Visual hierarchy relies on structural planes and subtle, ultra-soft dropshadows rather than dramatic z-axis shifts or blur effects.

- **Level 0 (Canvas):** Flat `#F7F8FA` background. No elevation.
- **Level 1 (Card / Table Container):** `#FFFFFF` surface bounded by a crisp `1px solid #E2E5EB` border and supported by an ambient micro-shadow: `0 1px 2px 0 rgba(31, 36, 48, 0.04)`.
- **Level 2 (Hover / Popovers / Dropdowns):** Used for filter menus, dropdown selects, and date-range pickers. Bounded by `#E2E5EB` and elevated with `0 4px 12px 0 rgba(31, 36, 48, 0.08)`.
- **Level 3 (Modal / Slide-Over Review Inspector):** Positioned over workspace backdrops with a soft neutral scrim (`rgba(31, 36, 48, 0.2)`). The panel retains a structural left or border-surround with `0 12px 32px 0 rgba(31, 36, 48, 0.12)`.

## Shapes

The design system standardizes on a disciplined, medium-rounded radius curve (`roundedness: 2`) that balances modern software aesthetics with crisp enterprise structure.

- **Base Radii (`0.5rem` / `8px`):** Applied to form inputs, buttons, filter chips, dropdowns, and inline notifications.
- **Container Radii (`0.75rem` - `1rem` / `12px` - `16px`):** Applied to main workspace cards, data table wrappers, empty states, and modal windows.
- **Pill Geometry (`9999px`):** Reserved exclusively for semantic status badges, user presence indicators, and keyboard shortcut indicators to instantly differentiate static metadata from actionable square-cornered elements.

## Components

### Buttons
- **Primary:** Background `#5B5BD6`, text `#FFFFFF`, border `transparent`. Hover transitions to `#4E4EC5`. Active presses scale to `98%` with zero shadow.
- **Secondary / Ghost:** Background `#FFFFFF`, text `#1F2430`, border `1px solid #E2E5EB`. Hover shifts background to `#F7F8FA` and text to `#1F2430`.
- **Destructive:** Background `#FEF2F2`, text `#EF4444`, border `1px solid #FEE2E2`. Hover shifts background to `#FEE2E2`.
- **Heights & Spacing:** Compact height of 32px for in-table actions (`text-xs`), standard 36px for toolbars (`text-sm`), and 40px for primary form controls.

### Status Badges & Chips
- **Geometry:** Height 22px, horizontal padding `8px`, fully rounded pill (`border-radius: 9999px`).
- **Variants:**
  - *Approved / Active:* Background `#ECFDF5`, text `#065F46`, paired with a 6px solid `#10B981` bullet point.
  - *Pending / Review:* Background `#FFFBEB`, text `#92400E`, paired with a 6px solid `#F59E0B` bullet point.
  - *Conflict / Cancelled:* Background `#FEF2F2`, text `#991B1B`, paired with a 6px solid `#EF4444` bullet point.

### Inputs & Form Controls
- **Text & Select Fields:** Height 36px, background `#FFFFFF`, border `1px solid #E2E5EB`, text `#1F2430`, placeholder `#9AA2B1`. On focus: border shifts to `#5B5BD6` accompanied by an indigo halo ring `0 0 0 3px rgba(91, 91, 214, 0.12)`.
- **Checkboxes & Radios:** 16x16px boundary, rounded 4px (checkbox) or circular (radio), `#E2E5EB` border. Active state fills with `#5B5BD6` displaying a white check/dot icon.

### Data Tables & List Views
- **Header:** Height 36px, background `#F7F8FA`, text `#5B6472`, `font-size: 12px`, uppercase letter tracking `0.05em`, bottom border `1px solid #E2E5EB`.
- **Rows:** Alternating neutral hover states (`#FBFBFC`), minimum row height 44px, cell border `1px solid #F0F2F5`. Tabular figures aligned flush right for numbers and currency.

### Split-Screen Review & Slide-Over Inspector
- **Slide-Over Panel:** Anchored flush to the right viewport edge. Border-left `1px solid #E2E5EB`, pure white background, fixed header and footer toolbars with scrollable internal body content.
- **Key-Value Audit Grids:** Standardized 2-column inspector layout pairing a 120px muted label column (`#5B6472`, `text-xs`) with a dynamic content column (`#1F2430`, `text-sm`) for rapid credential checks.