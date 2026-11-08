---
name: Custard Pudding Scrapbook
colors:
  surface: '#fff9ec'
  surface-dim: '#e5dab0'
  surface-bright: '#fff9ec'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff4c8'
  surface-container: '#f9eec2'
  surface-container-high: '#f3e8bd'
  surface-container-highest: '#ede3b8'
  on-surface: '#201c02'
  on-surface-variant: '#54433c'
  inverse-surface: '#363113'
  inverse-on-surface: '#fcf1c5'
  outline: '#87736a'
  outline-variant: '#dac1b7'
  surface-tint: '#944a23'
  primary: '#592100'
  on-primary: '#ffffff'
  primary-container: '#78350f'
  on-primary-container: '#ffa072'
  inverse-primary: '#ffb693'
  secondary: '#6e5e0d'
  on-secondary: '#ffffff'
  secondary-container: '#f6df84'
  on-secondary-container: '#726212'
  tertiary: '#660043'
  on-tertiary: '#ffffff'
  tertiary-container: '#88175c'
  on-tertiary-container: '#ff98ca'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbcc'
  primary-fixed-dim: '#ffb693'
  on-primary-fixed: '#351000'
  on-primary-fixed-variant: '#76330d'
  secondary-fixed: '#f9e287'
  secondary-fixed-dim: '#dcc66e'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#534600'
  tertiary-fixed: '#ffd8e7'
  tertiary-fixed-dim: '#ffafd3'
  on-tertiary-fixed: '#3d0026'
  on-tertiary-fixed-variant: '#85145a'
  background: '#fff9ec'
  on-background: '#201c02'
  surface-variant: '#ede3b8'
typography:
  headline-xl:
    fontFamily: Comfortaa
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Comfortaa
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Comfortaa
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Comfortaa
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: 0em
  headline-md:
    fontFamily: Comfortaa
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Comfortaa
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system draws visual lineage from artisanal Japanese character stationery, vintage craft scrapbooks, and cozy cottagecore diaries. Inspired by nostalgic Sanrio character design (warm golden retrievers crowned with cocoa berets and sweet custard puddings), the atmosphere is soft, welcoming, and delightfully tactile. 

The aesthetic marries **Tactile / Skeuomorphic Scrapbooking** with modern digital usability. The UI simulates a dynamic physical paper journal: cream-toned vellum backdrops, tape tabs, rounded photo mounts, gently tilted polaroids, and plush, squishy buttons. 

Key principles:
- **Warmth Over Clinical Precision:** Surfaces mimic unbleached cotton paper, pastry dough, and buttermilk linen. Lines are soft, and colors are confectionery-inspired.
- **Craft & Nostalgia:** Washi tape banners, stitch borders, stamp badges, and stickers inject playful charm without sacrificing digital clarity.
- **Squishy Tactility:** Buttons, chips, and cards yield under touch with gentle compression shadows and elastic spring animations.

## Colors

The color palette centers on sweet confectioneries—golden custard pudding, molten caramel, milk chocolate, and whipped strawberry cream.

- **Primary (`#78350F` / Cocoa Beret Brown):** Used for primary text, structural outlines, high-contrast action strokes, and character details. Evokes rich milk chocolate and beret felt. Deep variant `#451A03` is reserved for ultra-dense typography.
- **Secondary (`#FDE68A` / Custard Cream):** Used for focal backgrounds, hero container fills, and primary button fills. Paired with `#FEF08A` for soft inner gradients.
- **Tertiary (`#F472B6` / Berry Glaze Pink):** Used for delicate accents, heart badges, playful interactive badges, and romantic scrapbook stickers. Paired with pastel blush (`#FCE7F3`) for soft tags.
- **Neutral Palette (`#FFFBEB` Buttermilk base to `#FEF3C7` Pudding Foam):** The canvas avoids cold digital white completely. All viewports sit on a base of warm buttermilk canvas (`#FFFBEB`), framed by soft toasted caramel borders (`#D97706` diluted or `#B45309`).
- **Semantic Feedback:**
  - Success: Sweet Matcha Green (`#65A30D`)
  - Warning: Toasted Toffee (`#D97706`)
  - Error: Strawberry Jam Red (`#E11D48`)

## Typography

The type system balances storybook roundness with rock-solid legibility:

- **Display & Headlines (`Comfortaa`):** Geometric, pillowy curved terminal letterforms inject a bubbly, friendly tone into headings. Used exclusively for titles, section headers, hero callouts, and numerical counters.
- **Body & Functional Text (`Plus Jakarta Sans`):** Warm, humanist geometry ensures continuous reading ease without cold corporate stiffness. Its open apertures and soft curves harmonize with `Comfortaa`.
- **Text Hierarchy & Colors:** All headings strictly utilize `#78350F` (Cocoa Brown) or `#451A03` rather than harsh `#000000`. Body copy defaults to `#78350F` at full opacity or softened to `#92400E` for secondary helper text.

## Layout & Spacing

The layout philosophy mirrors a layered stationery binder, alternating between grid consistency and organic scrapbook arrangements:

- **Grid Architecture:** 
  - **Mobile (< 768px):** 4-column layout with `1rem` margins and `1rem` gutters. Cards stack vertically like notebook index cards.
  - **Tablet (768px - 1024px):** 8-column layout with `2rem` margins and `1.25rem` gutters.
  - **Desktop (> 1024px):** 12-column layout with `3rem` margins and `1.5rem` gutters, contained within a maximum width of `1280px`.
- **Scrapbook Offset Rules:** On desktop and tablet views, featured cards and polaroids may employ slight CSS rotational offsets (`transform: rotate(-1.5deg)` to `transform: rotate(2deg)`) on hover or static display, simulating scattered desk items while keeping layout grids strictly aligned underneath.

## Elevation & Depth

Elevation is achieved not through cold industrial dropshadows, but via **warm, caramel-tinted pillowy elevation** and tactile paper layering:

- **Ambient Tinted Shadows:** Shadows use chocolate-caramel hues (`rgba(120, 53, 15, 0.08)` to `rgba(120, 53, 15, 0.16)`) with high diffusion and gentle offsets:
  - **Level 1 (Paper Layer / Soft Sheet):** `0 2px 8px -2px rgba(120, 53, 15, 0.08)`
  - **Level 2 (Pudding Card / Lifted Note):** `0 8px 20px -4px rgba(120, 53, 15, 0.12), 0 2px 4px -1px rgba(120, 53, 15, 0.06)`
  - **Level 3 (Floating Polaroid / Modal):** `0 16px 32px -8px rgba(120, 53, 15, 0.16), 0 4px 8px -2px rgba(120, 53, 15, 0.08)`
- **Skeuomorphic Scrapbook Details:**
  - **Washi Tape Strips:** Translucent pastel stickers (`rgba(254, 240, 138, 0.7)` or `rgba(252, 231, 243, 0.7)`) with jagged or semi-transparent mask edges anchored atop cards.
  - **Dashed Stitch Lines:** Subtle border treatments (`2px dashed #FDE68A` or `#D97706`) around specialty recipe or game cards.
  - **Physical Button "Squish":** Active states on buttons translate `translateY(3px)` with inner highlight shifts to feel like sponge pudding.

## Shapes

The shape system adopts hyper-rounded geometry (`level 3: Pill-shaped`), eliminating harsh technical angles to reinforce the soft, organic, squishy world of custard and golden pup paws:

- **Base Radius:** Controls and micro-elements use `1rem` (16px).
- **Cards & Notebook Frames (`rounded-lg`):** Use `2rem` (32px), creating pillowy, biscuit-like panels.
- **Modals, Floating Panels & Scrapbook Sheets (`rounded-xl`):** Use `3rem` (48px) for maximum approachability.
- **Pills:** All chips, tags, and interactive action triggers feature full pill radii (`border-radius: 9999px`).
- **Organic Cutouts:** Stamp frames and polaroid masks feature scalloped or perforated edges where decorative borders are applied.

## Components

### Buttons
- **Primary ("Pudding Squish"):** Fills are rich Custard Yellow (`#FDE68A`) with an inner top highlight border (`2px solid #FEF08A`), a chunky Cocoa Brown outline (`2px solid #78350F`), and Cocoa text (`#78350F`, `label-lg`). Shadow is a hard 3px drop in Cocoa Brown (`0 3px 0 #78350F`). On click/active: `translateY(3px)` and the shadow drops to `0`.
- **Secondary ("Beret Wool"):** Fill is Cocoa Brown (`#78350F`) with Buttercream text (`#FFFBEB`). On hover, warm amber glow.
- **Tertiary / Sticker Button:** White buttermilk pill with dashed chocolate outline and soft pink icon adornment.

### Cards & Polaroid Slots
- **Polaroid Photo Cards:** Ivory/White frame (`#FFFFFF`) with thick bottom padding (`space-xl`), holding an inner image slot (`rounded-md`). Bottom border includes space for handwritten or Comfortaa labels. Static elements can feature a faint rotation (`-1deg` or `1.5deg`).
- **Scrapbook Content Cards:** Cream buttermilk canvas (`#FFFBEB`) framed with a 2px solid biscuit line (`#FDE68A`) and Level 2 ambient caramel shadow. Often adorned with a simulated tape strip at the top center.

### Chips & Badges
- Pill-shaped (`9999px`).
- Soft strawberry tint (`#FCE7F3`) or caramel cream (`#FEF3C7`) with Cocoa text (`label-md`). 
- Prefixed with small custom icons (pudding cups, paw prints, berets, little stars).

### Form Inputs
- Deep, pill-shaped input fields (`rounded-full` or `rounded-xl`).
- Background: `#FFFBEB` with an inset shadow (`inset 0 2px 4px rgba(120, 53, 15, 0.05)`).
- Border: `2px solid #FDE68A`. Focus state shifts border to Cocoa Brown (`#78350F`) with a warm butter halo glow (`box-shadow: 0 0 0 4px #FEF08A`).

### Checkboxes & Radios
- Checkbox: Rounded square (`rounded-md`), `2px solid #78350F`, checking displays a chubby cocoa heart or paw print.
- Radio: Full circle with a soft custard inner dot expanding upon selection.

### Scrapbook Widgets & Gamification Details
- **Interactive Mini-Games / Daily Dials:** Styled like vintage wooden dials or pudding timers with round knobs.
- **Sticker Drawer:** A floating draggable drawer storing decorative pins, washi stickers, and stamps users can place into their journal views.
- **Diary Ribbon Bookmark:** Decorative hanging satin ribbon SVG positioned at the top right of the primary view container.