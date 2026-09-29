---
name: Synthetic Intelligence Data Interface
colors:
  surface: '#0f131c'
  surface-dim: '#0f131c'
  surface-bright: '#353943'
  surface-container-lowest: '#0a0e17'
  surface-container-low: '#181b25'
  surface-container: '#1c1f29'
  surface-container-high: '#262a34'
  surface-container-highest: '#31353f'
  on-surface: '#dfe2ef'
  on-surface-variant: '#bcc9cd'
  inverse-surface: '#dfe2ef'
  inverse-on-surface: '#2c303a'
  outline: '#869397'
  outline-variant: '#3d494c'
  surface-tint: '#4cd7f6'
  primary: '#4cd7f6'
  on-primary: '#003640'
  primary-container: '#06b6d4'
  on-primary-container: '#00424f'
  inverse-primary: '#00687a'
  secondary: '#b4c5ff'
  on-secondary: '#002a78'
  secondary-container: '#0053db'
  on-secondary-container: '#cdd7ff'
  tertiary: '#93ccff'
  on-tertiary: '#003351'
  tertiary-container: '#4faef4'
  on-tertiary-container: '#004063'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#acedff'
  primary-fixed-dim: '#4cd7f6'
  on-primary-fixed: '#001f26'
  on-primary-fixed-variant: '#004e5c'
  secondary-fixed: '#dbe1ff'
  secondary-fixed-dim: '#b4c5ff'
  on-secondary-fixed: '#00174b'
  on-secondary-fixed-variant: '#003ea8'
  tertiary-fixed: '#cce5ff'
  tertiary-fixed-dim: '#93ccff'
  on-tertiary-fixed: '#001d31'
  on-tertiary-fixed-variant: '#004b73'
  background: '#0f131c'
  on-background: '#dfe2ef'
  surface-variant: '#31353f'
typography:
  headline-lg:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Geist
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Geist
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  code-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 22px
    letterSpacing: -0.02em
  code-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: -0.01em
  code-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 12px
    letterSpacing: 0.06em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 0.75rem
  gutter-desktop: 1.25rem
  margin: 1rem
  margin-desktop: 2rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.875rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style
The design system reflects a precision-engineered, high-velocity analytical environment designed for mobile devices. It serves data scientists, product managers, engineers, and business analysts who need to query enterprise databases on the go using natural language without sacrificing technical rigor.

The aesthetic bridges Modern Developer Ergonomics and Glass-Infused High-Tech Precision. It avoids playful or consumer-grade conversational tropes in favor of an authoritative, quiet intelligence. Interfaces evoke high-end terminal environments merged with ultra-refined mobile surfaces: deliberate structural density, crisp edge delineation, subtle radiant illumination at points of active AI synthesis, and purposeful contrast between natural language narration and raw, executable code tokens.

## Colors
The palette leverages a dark-mode architecture rooted in deep obsidian and technical navy underpinnings, contrasted against luminous cyan and electric blue signals.

- **Primary (`#06b6d4` - Luminous Cyan):** Used for AI status indicators, active generation states, primary interactive triggers, highlighted query tokens, and real-time execution feedback.
- **Secondary (`#2563eb` - Electric Cobalt):** Powering major navigational accents, selected pill filters, active relational schemas, and focused primary inputs.
- **Tertiary (`#0284c7` - Technical Sky):** Applied to SQL syntax parameters, structural metric callouts, and secondary link states.
- **Neutral Foundation (`#090d16` - Deep Space Navy):** The bedrock background tone, layered upward into `rgba(255, 255, 255, 0.04)` to `rgba(255, 255, 255, 0.12)` for elevated surface cards, input troughs, and tabular partitions.
- **Semantic Accents:**
  - Success/Valid SQL: Emerald `#10b981`
  - Error/Parse Failure: Crimson `#f43f5e`
  - Warning/High Resource Execution: Amber `#f59e0b`
  - Text Primary: `#f8fafc` (Slate 50)
  - Text Secondary: `#94a3b8` (Slate 400)
  - Text Code / Muted: `#64748b` (Slate 500)

## Typography
Typographic discipline pairs the hyper-clean, proportional clarity of **Geist** for structural interaction and natural language with the industrial authenticity of **JetBrains Mono** for technical artifacts, data representations, schema keys, and SQL code blocks.

- Titles, narrative prompt strings, and conversational explanations use Geist to maintain effortless human legibility in compact mobile formats.
- Generated SQL, raw outputs, latency stats, rows affected counts, and status indicators strictly employ JetBrains Mono.
- All code styles preserve clear tabular numeric figures (`tnum`) for instant scanning across data results.

## Layout & Spacing
Designed from a mobile-first paradigm, the layout utilizes a vertical stack flow reinforced by a 4-column fluid mobile grid that expands to 8 columns on tablet viewports and 12 columns on large screens.

- Touch targets maintain a minimum dimension of 44px vertically, offset by strict 8px/14px internal padding rhythms.
- Query workspace viewports lock persistent primary inputs to the bottom thumb zone, allowing the schema tree and conversational result thread to scroll independently.
- Tabular data renders dynamically through a responsive sheet model: previewing the primary composite keys inline and enabling frictionless lateral finger-swipes for extended relational columns.

## Elevation & Depth
Depth is established through dark-mode surface luminosity and low-contrast borders rather than drop shadows:

- **Level 0 (Canvas Base):** Solid deep-tech foundation (`#090d16`).
- **Level 1 (Sub-Containers & Query Blocks):** Translucent obsidian-slate fill (`rgba(15, 23, 42, 0.65)`) overlaid with a crisp `1px` stroke of `rgba(148, 163, 184, 0.12)`.
- **Level 2 (Interactive Floating Sheets & Action Modals):** Backdrop-filter blur (`16px`), filled with `rgba(15, 23, 42, 0.88)` and outlined with `rgba(6, 182, 212, 0.25)`.
- **AI Active Glow:** During real-time inference or SQL compilation, cards emit a directional, diffuse cyan edge-glow: `0 0 24px -4px rgba(6, 182, 212, 0.2)`. No harsh, opaque drop shadows are permitted.

## Shapes
A controlled, technical soft-corner geometry (`roundedness: 1`) conveys precision tooling. 

- Interactive inputs, cards, and execution panels use standard 4px (`rounded-sm`) to 8px (`rounded-md`) corner radii to maintain crisp architectural containment.
- Code blocks and data tables retain structured 8px corners to preserve rectangular grid alignment.
- Small contextual pills, schema badges, and execution chips utilize full rounded radii (`rounded-full`) to immediately contrast status markers against rigid data structures.

## Components

### Natural Language Prompt Input
- Docked at the bottom safe-area margin. 
- Integrated multi-line text input with automated vertical expansion up to 4 lines before internal scrolling.
- Features a leading lightning badge denoting the active database connection and a trailing electric cyan run trigger button (`#06b6d4`) with high-contrast dark glyphs (`#090d16`).
- Border shifts smoothly from `rgba(148, 163, 184, 0.12)` to `#06b6d4` upon focus.

### SQL Output & Code Containers
- Wrapped in a dark container with a top metadata bar displaying engine dialect (e.g., `PostgreSQL 16`), parse time (`42ms`), and one-tap "Copy" / "Explain" utilities in JetBrains Mono.
- Syntax highlighting uses calibrated cyan (`#06b6d4`), cobalt (`#60a5fa`), amber (`#fbbf24`), and emerald (`#34d399`) against a dense midnight backdrop.
- Long queries feature inline scroll indicators with sticky horizontal action handles.

### Data Result Cards & Mini-Tables
- Card wrappers contain a summary header with row counts, execution time, and quick view toggles (Card vs. Table).
- Cells are padded with `space-sm` vertically, utilizing monospaced digits with tabular lining for scanability.
- Headers are uppercase `label-sm` in slate gray (`#94a3b8`) with subtle bottom division strokes.

### Buttons & Interactive Chips
- **Primary Execution Button:** Solid `#06b6d4` with deep navy typography (`#090d16`) at 600 weight.
- **Secondary Actions:** `rgba(255, 255, 255, 0.05)` fill with a 1px border of `rgba(148, 163, 184, 0.2)` and Slate 200 text.
- **Filter / Schema Chips:** Compact horizontal scroll items with monospaced column names, subtle status pips for primary/foreign keys, and interactive popovers.

### Checkboxes & Relational Selectors
- Custom square selectors (16x16px) with 2px corner radii.
- Checked state fills with `#2563eb` and displays a crisp white check vector.
- Selection rings in table bulk-actions show clear cyan highlights.