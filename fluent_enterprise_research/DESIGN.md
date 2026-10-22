---
name: Fluent Enterprise Research
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#464555'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#777587'
  outline-variant: '#c7c4d8'
  surface-tint: '#4d44e3'
  primary: '#3525cd'
  on-primary: '#ffffff'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#c3c0ff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#7e3000'
  on-tertiary: '#ffffff'
  tertiary-container: '#a44100'
  on-tertiary-container: '#ffd2be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#ffdbcc'
  tertiary-fixed-dim: '#ffb695'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7b2f00'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Inter
    fontSize: 2.25rem
    fontWeight: '600'
    lineHeight: 2.75rem
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2rem
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '400'
    lineHeight: 1rem
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: '0'
  label-sm:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.02em
  caption:
    fontFamily: Inter
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: 0.875rem
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1rem
  space-xl: 1.5rem
  space-2xl: 2rem
---

## Brand & Style

This design system embodies the authentic Microsoft Windows 11 Fluent aesthetic, calibrated for complex enterprise analytical platforms. It merges the tactile precision of desktop operating systems with the agility of high-density web software. 

The visual personality is authoritative, calm, and systematic. Designed for researchers, strategists, and operations leads analyzing nuanced behavioral data across emerging markets, the interface recedes to let rich field artifacts, video clips, and high-dimensional metrics take center stage. 

Visual characteristics include:
- **Mica-inspired canvas layering**: Distinct structural backgrounds paired with pure white operational cards.
- **Physical precision**: Crisp 1px borders, subtle depth transitions, and consistent 8px standard corner radii across interactive widgets.
- **Micro-tactile dynamics**: Restrained elevation shifts, clear active states, and intentional spatial rhythm derived from modern enterprise desktop ergonomics.

## Colors

The palette balances systematic enterprise clarity with purposeful semantic indicators:

- **Primary (`#4F46E5`) & Primary Hover (`#4338CA`)**: Drives decisive user pathways, primary command bar actions, and active navigation nodes.
- **Secondary / Accent (`#0D9488`)**: Dedicated to quantitative trends, market insights, telemetry signals, and key emerging market research indicators.
- **Canvas & Surface Tier**: The foundation relies on a Mica-tinted window base (`#F5F7FB`) overlaid with high-luminance working surfaces (`#FFFFFF`). Content panels never sit directly on raw canvas without clear spatial or structural definition.
- **Borders (`#E2E8F0`)**: Crisp 1px boundaries provide explicit demarcation between data panes, headers, and inspector sidebars without heavy visual weight.
- **Typography Tone**: Text Primary (`#172554`) delivers deep navy-ink contrast for readability during long analytical sessions, while Text Secondary (`#64748B`) establishes secondary hierarchy for metadata and field timestamps.
- **Semantic Suite**: Dedicated functional tokens for Success (`#059669`), Warning (`#D97706`), and Danger (`#DC2626`) signal participant status, pipeline errors, and compliance flags.

## Typography

Typography prioritizes density, structure, and tabular scanning. Inter functions as the digital bedrock, matching Segoe UI metric rhythm for enterprise workflows.

### Scaling & Rules
- **Display & Large Headlines**: Reserved strictly for platform dashboard overviews, cohort synthesis titles, and executive briefs. Line-heights are tightly coupled to preserve vertical real estate.
- **Data Densities**: Primary analysis occurs at `body-md` (14px) and `label-sm` (12px). These sizes optimize reading efficiency across side-by-side video feeds, participant quotes, and data tables.
- **Tabular Figures**: Numeric outputs, timeline stamps, and metric cards must enforce monospace or tabular lining number rendering (`font-variant-numeric: tabular-nums`) to maintain alignment across columns.

## Layout & Spacing

The layout model is governed by a desktop-first fluid structure anchored by fixed application chrome:

- **Application Shell Architecture**:
  - **Left Rail**: 48px collapsed icon bar expandable to 240px contextual menu tree.
  - **Command Bar**: 44px uniform height persistent header housing view switches, filters, and global platform actions.
  - **Working Workspace**: Fluid canvas partitioned into 12 columns with 16px desktop gutters (`gutter-desktop`) and 24px outer margins (`margin-desktop`).
  - **Inspector Panel**: Optional right-docked 320px/400px split-pane for real-time field note transcriptions and metadata tagging.

- **Responsive Adaptations**:
  - **Desktop (>= 1280px)**: Multi-pane layout active. Data tables and canvas widgets maintain side-by-side analysis views.
  - **Tablet / Medium (768px - 1279px)**: Inspector collapses into an overlay drawer. Navigation rail stays in icon-only mode (48px). Margins reduce to `1.5rem`.
  - **Mobile (< 768px)**: Single column reflow. Command bar converts into a horizontal scrollable strip. Main padding drops to `margin: 1rem`.

## Elevation & Depth

Fluent elevation mimics physical lighting directed from the top of the interface down to the surface, utilizing layered ambient occlusions and low-opacity border strokes rather than heavy shadows:

- **Level 0 (Canvas Base)**: `#F5F7FB`. Completely flat, non-elevated background surface.
- **Level 1 (Card & Content Blocks)**: `#FFFFFF` resting on `#F5F7FB`. Defined by a 1px continuous outline (`#E2E8F0`) paired with a whisper shadow: `0 1px 2px rgba(0, 0, 0, 0.04)`.
- **Level 2 (Hover States & Dropdowns)**: Surfaces slightly elevate upon hover or interaction: `0 4px 8px -2px rgba(15, 23, 42, 0.06), 0 2px 4px -2px rgba(15, 23, 42, 0.04)`. Border remains `#E2E8F0`.
- **Level 3 (Command Flyouts & Modals)**: Dialogs, command palettes, and filter menus use deeper elevation: `0 12px 24px -4px rgba(15, 23, 42, 0.08), 0 4px 8px -2px rgba(15, 23, 42, 0.03)`, accompanied by a 1px border (`#E2E8F0`) and an 8px blur acrylic backdrop on mobile viewports.
- **Active Focus Rings**: 2px solid primary border (`#4F46E5`) with an offset of 1px for high-contrast accessibility compliance.

## Shapes

In keeping with the Windows 11 Fluent aesthetic, the baseline geometry is calibrated to `roundedness: 2`:

- **Standard Elements (0.5rem / 8px)**: Applied uniformly to buttons, text input fields, dropdown triggers, cards, and modal dialogs.
- **Inner Controls (0.25rem / 4px)**: Nested items within larger cards—such as segmented toggles, table selection checkboxes, and progress indicators—adopt a tighter 4px radius to ensure concentric visual nesting.
- **Pills / Dynamic Tags (9999px)**: Data status badges, market country tags, and recording state chips use full pill shapes to clearly differentiate operational metadata from actionable rectangular buttons.

## Components

### Buttons
- **Primary**: Solid `#4F46E5` background, `#FFFFFF` text, 8px radius, height 36px (compact enterprise height). Hover: `#4338CA`. Active: scale transform down to `0.985` with 1px inset drop.
- **Secondary (Standard)**: `#FFFFFF` surface, 1px `#E2E8F0` border, `#172554` text. Hover: `#F8FAFC` background with `#CBD5E1` border.
- **Subtle / Ghost (Command Bar Item)**: Transparent background, 6px internal radius, `#172554` text. Hover: `#F1F5F9`.

### Input Fields & Search Bars
- Background: `#FFFFFF`. Border: 1px `#E2E8F0`. Height: 36px. Typography: `body-md`. Padding: `0 12px`.
- Bottom stroke accent: 1px bottom border transitions to 2px `#4F46E5` on focus with no horizontal expansion.
- Placeholder text: `#94A3B8`.

### Navigation Rails & Command Bars
- **Command Bar**: Flat container with a 1px bottom border (`#E2E8F0`). Distributes actions horizontally with 4px internal gaps between icon-text groupings.
- **Nav Rail Items**: 40px height with 8px radius. Active state shows an indigo left indicator tick (3px wide, 16px high, rounded) paired with a `#EEF2FF` soft tinted container.

### Cards & Analytical Widgets
- White `#FFFFFF` foundation with 1px `#E2E8F0` border. Padding: 16px (`space-lg`).
- Header split: Title uses `headline-sm`, right-aligned meta uses `caption` (`#64748B`). Optional top accent border line available for critical status items.

### Data Badges & Filter Chips
- **Chips**: 24px height, 9999px border-radius, 1px `#E2E8F0` border, background `#F8FAFC`. Active filter state switches to `#EEF2FF` background and `#4F46E5` text.
- **Metric Badges**: Subtle tint containers (`#0D9488` at 10% opacity) with solid `#0D9488` text for emerging market index gains.

### Checkboxes & Radio Controls
- Checkbox: 16px × 16px square with 4px corner radius. Inactive: 1.5px `#94A3B8` outline. Checked: Solid `#4F46E5` with white checkmark icon.
- Radio: 16px diameter circle with central 6px solid dot indicator on selection.