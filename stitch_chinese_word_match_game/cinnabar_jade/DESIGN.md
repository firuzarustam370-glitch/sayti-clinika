---
name: Cinnabar & Jade
colors:
  surface: '#f8f9ff'
  surface-dim: '#d6dae4'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f4fd'
  surface-container: '#eaeef8'
  surface-container-high: '#e4e8f2'
  surface-container-highest: '#dee2ec'
  on-surface: '#171c23'
  on-surface-variant: '#5b403e'
  inverse-surface: '#2c3138'
  inverse-on-surface: '#edf1fb'
  outline: '#8f706d'
  outline-variant: '#e3bebb'
  surface-tint: '#b81f26'
  primary: '#b41c23'
  on-primary: '#ffffff'
  primary-container: '#d73839'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb3ad'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#825100'
  on-tertiary: '#ffffff'
  tertiary-container: '#a36700'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad7'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410004'
  on-primary-fixed-variant: '#930013'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffddb8'
  tertiary-fixed-dim: '#ffb95f'
  on-tertiary-fixed: '#2a1700'
  on-tertiary-fixed-variant: '#653e00'
  background: '#f8f9ff'
  on-background: '#171c23'
  surface-variant: '#dee2ec'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: 0em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
  hanzi-display:
    fontFamily: system-ui, -apple-system, 'PingFang SC', 'Noto Sans SC', sans-serif
    fontSize: 64px
    fontWeight: '500'
    lineHeight: 72px
  hanzi-card:
    fontFamily: system-ui, -apple-system, 'PingFang SC', 'Noto Sans SC', sans-serif
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
  pinyin-annotation:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0.04em
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 2rem
  margin-sm: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a vibrant, culturally anchored, and gamified language-learning experience. It bridges traditional Chinese aesthetic touchstones—calligraphic ink, cinnabar seal paste, and polished jade—with contemporary product mechanics: celebratory progression feedback, tactile interactive states, and generous spatial rhythm.

### Aesthetic Direction: Tactile Neo-Heritage
- **Warm & Organic Backdrop**: Built on an ivory parchment foundation that mitigates eye fatigue while evoking physical rice paper.
- **Vibrant Ceramic Accents**: Primary actions rely on saturated cinnabar red, counterweighted by lush bamboo jade for success feedback and streaks.
- **Physical Feedback & Micro-Celebrations**: Cards exhibit a subtle 3D lift with distinct bottom-edge press states, providing tactile satisfaction during rapid character-matching quizzes.
- **Scholarly Clarity**: Dual-layer typographic presentation that honors native Hanzi stroke forms alongside clean, modern Latin glyphs for pinyin and translations.

## Colors

The palette balances energetic vermilion with grounding earthen neutrals, creating a structured hierarchy for gamified education.

### Palette Architecture
- **Primary (`#E03E3E`) — Cinnabar Vermilion**: Denotes vital interactive prompts, active streak markers, critical CTA buttons, and foundational brand moments. Associated with celebration and auspicious energy.
- **Secondary (`#10B981`) — Bamboo Jade**: Expresses mastery, correct answers, completed stroke orders, and progression metrics. Softened slightly from raw terminal green to match ceramic jade glazes.
- **Tertiary (`#F59E0B`) — Imperial Ochre**: Reserved for secondary rewards, XP tallies, lingering review states, and level stars.
- **Neutral Dark (`#1E232A`) — Ink Slate**: Derived from ground inkstone. Replaces harsh true black for body text, character strokes, and high-contrast structural borders.
- **Canvas Base (`#FAF8F5`) — Raw Xuan Parchment**: A warm off-white surface eliminating stark digital glare.
- **Surface Elevation (`#FFFFFF`)**: Pure white containers and quiz cards creating clean separation against the parchment canvas.
- **Muted Borders (`#E8E3DA`)**: Low-contrast stone grey for card perimeters, dividing rules, and inactive states.

## Typography

Typography establishes an unambiguous vertical rhythm between Chinese characters, phonetic Pinyin with tone marks, and English translations.

### Font Pairing Strategy
- **Headlines & Interface Labels**: Set in `Plus Jakarta Sans`. Its geometric, friendly terminals reinforce playfulness and quick scannability in buttons, headers, and score tallies.
- **Body & Explanatory Prose**: Set in `Be Vietnam Pro`. Its robust diacritic handling and balanced humanist proportions ensure flawless rendering of Latin tone markings without vertical clipping.
- **Hanzi Characters**: Rendered via modern simplified Chinese system stacks (`PingFang SC`, `Noto Sans SC`) at proportional optical scalings to match the weight and baseline of accompanying Latin letterforms.

### Vertical Lockups for Language Units
When rendering interactive word units, always place `pinyin-annotation` directly above `hanzi-card` with an 8px offset, followed by the English translation in `body-md` below.

## Layout & Spacing

The layout is engineered around focused learning zones using an 8pt modular grid. It favors centered, constrained-width viewports over unbounded edge-to-edge stretching to maintain user focus during quizzes.

### Grid & Breakpoints
- **Desktop (1024px+)**: Max container width of 1120px for dashboards; tightly centered 680px single-column track for matching quizzes and flashcards. Gutters set to `gutter` (1.5rem).
- **Tablet (768px - 1023px)**: Responsive 8-column layout with 1.5rem margins.
- **Mobile (< 768px)**: 4-column layout with `margin-sm` (1rem). Word-matching matrices reflow from 4x2 grids into 2x4 vertical card blocks.

### Component Spacing Rhythm
- Compact internal card padding uses `space-md` (1rem).
- Inter-card matching distances use `space-md` horizontally and vertically.
- Section boundaries and interactive stage transitions leverage `space-xl` (2.5rem).

## Elevation & Depth

Visual depth combines warm atmospheric tinting with gamified tactile surfaces.

### Elevation Tiers
- **Flat Ground**: Xuan Parchment background (`#FAF8F5`) sits at the lowest layer without shadows.
- **Level 1 (Parchment Tile / Unselected Card)**: Pure white `#FFFFFF` surface enclosed by a 2px solid border (`#E8E3DA`) and supported by a subtle physical edge: `box-shadow: 0 3px 0 0 #E8E3DA`.
- **Level 2 (Hover / Active Interactive Card)**: Translates 2px upward on hover with an intensified edge shadow: `box-shadow: 0 5px 0 0 #D1C9BE`.
- **Level 3 (Floating Modal / Reward Chest)**: Elevated high above the canvas: `box-shadow: 0 12px 32px -4px rgba(30, 35, 42, 0.12), 0 4px 12px -2px rgba(30, 35, 42, 0.06)`.

### Tactile Press Mechanism
Interactive tiles, quiz chips, and primary buttons use an anchor shadow technique. On click or tap (`:active`), the element translates down by 2px, and the bottom anchor shadow reduces correspondingly to 1px, replicating the sensation of pressing an arcade button.

## Shapes

The design uses roundedness tier 2 to deliver a welcoming, tactile educational atmosphere that avoids looking overly childish or strictly enterprise.

### Geometric Rules
- **Base Components**: Buttons, quiz options, and flashcards utilize `0.5rem` (8px) corner radii.
- **Containers & Panels (`rounded-lg`)**: Learning track summaries, quiz stages, and modal envelopes use `1rem` (16px) corner radii.
- **Large Dialogue Frames (`rounded-xl`)**: Mascot speech bubbles and celebratory level banners use `1.5rem` (24px) corner radii.
- **Pills & Badges**: Retain a complete pill radius (9999px) for streaks, audio pronounce toggles, and status tags.

## Components

### Buttons
- **Primary CTA**: Vermilion base (`#E03E3E`), white label, with a darker base rim (`#B92B2B`, 3px bottom inset/shadow). On press, transforms downward 2px.
- **Secondary / Action Affirmative**: Jade green (`#10B981`) base with deep emerald anchor shadow (`#059669`) for positive validation buttons ("Next Word", "Submit Answer").
- **Ghost / Tertiary**: Transparent base, 2px border in `#E8E3DA`, Slate text (`#1E232A`). Hover transitions to cream fill (`#F4EFE6`).

### Word-Matching Cards
- **Base Tile**: 1:1 or 4:3 aspect ratio, `#FFFFFF` background, `#E8E3DA` 2px solid border, 8px radius. Centers Hanzi, Pinyin, or English translation.
- **Selected State**: Border shifts to `#E03E3E` (2px), background tint fills with `#FDF2F2`, bottom anchor shadow colored with `#F8B4B4`.
- **Success Matched**: Border transitions to `#10B981`, surface tint fills `#ECFDF5`, triggers subtle scale bounce.
- **Error Shake State**: Border snaps to crimson `#EF4444`, surface fills `#FEF2F2` accompanied by a horizontal micro-shake animation.

### Stroke Progress Indicators
- Linear progress bars: 12px height, parchment-toned trough (`#E8E3DA`) with pill radius (`9999px`). Active fill uses Jade (`#10B981`) or Cinnabar (`#E03E3E`) with a rounded head cap.
- Hanzi Stroke Order Visualizer: Gray placeholder paths (`#E5E7EB`) overlaid with animated ink strokes drawn dynamically in `#1E232A`.

### Streak & Reward Badges
- Continuous streak pill: `#FEF3C7` (soft amber) background with `#F59E0B` icon and `#B45309` typography.
- Level Stamp: Circular badge evoking traditional cinnabar seal chops (yin/yang balance), framed with an inset dashed line.

### Input Fields
- Underline-box hybrid: Clean white surface, 2px border in `#E8E3DA`, 8px radius. Focus state swaps border to `#E03E3E` with zero ambient fuzzy halo, keeping edges crisp and intentional.