---
name: Choco Factory Ledger
description: The Choco Factory Ledger — verifiable docs rendered as a warm editorial archive
colors:
  chocolate-deep: "#3C1518"
  chocolate-medium: "#4A1A1D"
  oompa-brown: "#8B5E3C"
  factory-wine: "#6B2D3E"
  factory-heading: "#2C1810"
  golden: "#D4A843"
  golden-dim: "#B8922E"
  golden-light: "#F2C94C"
  golden-ink: "#845B00"
  golden-ink-dark: "#D2A249"
  factory-warm: "#A44200"
  ledger-green: "#2D6A4F"
  badge-verified: "#C9923E"
  badge-failed: "#7A2E3A"
  factory-bg: "#FEFAE0"
  factory-surface: "#FFF8E7"
  factory-surface-raised: "#F8F8F8"
  factory-muted: "#E9E5D6"
  factory-border: "#D4C9A8"
  factory-border-cool: "#E5E7EB"
  factory-text: "#2C1810"
  factory-text-muted: "#5A4A3D"
  factory-text-cool-muted: "#6B7280"
  factory-bg-dark: "#1C1210"
  factory-surface-dark: "#261B16"
  factory-text-dark: "#F0E8DC"
  editor-code-bg: "#F5F2F0"
  editor-code-header-bg: "#5C2433"
typography:
  display:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "2rem"
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: "-0.03em"
  headline:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.5rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.015em"
  title:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
    lineHeight: 1.4
    letterSpacing: "-0.01em"
  body:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.8
    letterSpacing: "normal"
  label:
    fontFamily: "Inter, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: 600
    lineHeight: 1.5
    letterSpacing: "0.05em"
  mono:
    fontFamily: "JetBrains Mono, ui-monospace, Cascadia Code, monospace"
    fontSize: "0.875rem"
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: "normal"
rounded:
  none: "0"
  xs: "0.25rem"
  sm: "0.375rem"
  md: "0.5rem"
spacing:
  xs: "0.25rem"
  sm: "0.5rem"
  md: "0.75rem"
  lg: "1rem"
  xl: "1.5rem"
  "2xl": "2rem"
components:
  button-primary:
    backgroundColor: "{colors.golden-dim}"
    textColor: "{colors.factory-heading}"
    rounded: "{rounded.sm}"
    padding: "0.5rem 1rem"
  button-primary-hover:
    backgroundColor: "{colors.golden}"
    textColor: "{colors.factory-heading}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.factory-text-muted}"
    rounded: "{rounded.sm}"
    padding: "0.5rem 1rem"
  button-ghost-hover:
    backgroundColor: "{colors.factory-muted}"
    textColor: "{colors.factory-text}"
  toolbar-button:
    backgroundColor: "transparent"
    textColor: "{colors.factory-text}"
    rounded: "{rounded.sm}"
    size: "2rem"
  toolbar-button-active:
    backgroundColor: "{colors.factory-muted}"
    textColor: "{colors.factory-text}"
  editor-frame:
    backgroundColor: "{colors.factory-surface}"
    rounded: "{rounded.md}"
    padding: "1rem"
  oompa-annotation:
    backgroundColor: "{colors.factory-surface}"
    textColor: "{colors.oompa-brown}"
    rounded: "{rounded.sm}"
    padding: "0.75rem"
    typography: "{typography.mono}"
  badge-verified:
    backgroundColor: "{colors.badge-verified}"
    textColor: "{colors.factory-heading}"
    rounded: "{rounded.xs}"
    padding: "0.125rem 0.5rem"
    typography: "{typography.label}"
  badge-failed:
    backgroundColor: "{colors.badge-failed}"
    textColor: "{colors.factory-bg}"
    rounded: "{rounded.xs}"
    padding: "0.125rem 0.5rem"
    typography: "{typography.label}"
---

# Design System: Choco Factory Ledger

## 1. Overview

**Creative North Star: "The Choco Factory Ledger"**

The system reads like a warm reference book that turns out to also be a working compiler. Every published page is a stamped entry in the factory's ledger: chocolate ink on warm cream, with golden seals where the verifier signed, wine-red where the heading deserves weight, and Cocoa the bean appearing in the margins as a recurring narrator. The visual language is editorial and tonal — type, paper, and ink do the work; chrome retreats. This is not the SaaS-dashboard reflex.

Density is medium-low. Long-form reading is sacred; the docs body type and the editor's authoring surface share the same ink budget. Color is committed (not restrained) — the warm cream `#FEFAE0` carries 60–80% of any given screen as the page itself, with chocolate `#3C1518` as the ink and golden `#D4A843` as the seal. Verification status (ledger-green for attested, wine for needs-review, badge-failed for broken) is rendered as type and structure, never as fintech glitter.

This system explicitly rejects: generic devtools dark + electric-blue/purple gradient (the category-reflex look); AI-startup glassmorphic heroes with floating orbs and animated mesh; crypto/web3 neon-on-black, even though the TimeChain ledger is cryptographically attested; Notion/Confluence wiki softness with pastel emoji headers and friendly-blob illustrations.

**Key Characteristics:**

- Warm-cream paper, chocolate ink, golden seals — committed palette, not Restrained.
- Light-mode-first; dark mode is a deep-cocoa shift (`#1C1210`), never a default fallback.
- Flat surfaces with tonal layering — depth via warm tone shifts, not shadows.
- Editorial typographic hierarchy with serif-grade letter-spacing tightening on display.
- Mascot has a voice — Cocoa the bean appears in margins as `oompa-annotation` cards in mono type.
- Verification is rendered (ledger-green, badge-verified, attestation chain), not claimed.

## 2. Colors: The Choco Factory Palette

A committed warm palette built around three roles: chocolate ink, golden seal, warm-cream paper. Wine, oompa-brown, and ledger-green are role-specific accents that never compete with the seal.

### Primary
- **Deep Chocolate** (`#3C1518` — `oklch(22% 0.05 18)`): The primary brand color. Used as headline ink, factory-mythology surfaces, the deepest text contrast against cream. Reads as authoritative, not aggressive.
- **Choco Factory Heading** (`#2C1810` — `oklch(20% 0.025 50`)): Heading and primary body text. Slightly warmer/lighter than Deep Chocolate so headings layer cleanly on cream paper.
- **Golden Seal** (`#D4A843` — `oklch(73% 0.13 80)`): The signature accent. Stamped onto verified states, primary CTAs, accent borders on the floor-plan hover, link emphasis. The seal of attestation. Used at ≤15% of any given screen — its rarity is the point.
- **Golden Dim** (`#B8922E` — `oklch(64% 0.13 80)`): The default CTA background, carrying Factory Heading text. Quieter than the Seal so it can carry button-frequent surfaces without overwhelming. **Not a text, link or focus colour on light surfaces**: on Warm Cream it measures 2.8:1, below both AA thresholds. Use Golden Ink for those.
- **Golden Ink** (`#845B00` — `oklch(50% 0.11 80)`, step 3 of the Golden Dim ramp): Link text and the focus ring on light surfaces. The same hue as Golden Dim, dark enough to read: at least 4.6:1 on every light surface. **Golden Ink Dark** (`#D2A249` — `oklch(74% 0.12 80)`, step 5) does the same job in dark mode, at least 7.2:1 on the dark surfaces.

### Secondary
- **Factory Wine** (`#6B2D3E` — `oklch(35% 0.09 10)`): Editorial gravitas accent. Blockquote borders, table headers, H6 labels, narrator emphasis. The "literary" voice of the system.
- **Oompa Brown** (`#8B5E3C` — `oklch(46% 0.07 55)`): Cocoa's voice color. Annotation cards, mascot signature lines, marginalia text. Mono-set; never shouts.
- **Ledger Green** (`#2D6A4F` — `oklch(45% 0.09 155)`): The attestation color. Renders verification status, "published" indicators, TimeChain provenance ticks. Never used decoratively; ledger-green means *signed*.

### Tertiary
- **Factory Warm** (`#A44200` — `oklch(50% 0.16 45)`): The rare warning sienna. Used for *needs-attention* states that aren't quite errors. Used sparingly.
- **Badge Verified** (`#C9923E`): The gold-stamp variant for the verified-badge component itself. Distinct from Golden Dim because badges are pictographic, not typographic.
- **Badge Failed** (`#7A2E3A`): The rose-wine failure color for broken verification. Distinct from Factory Wine — failure is a signal, not a vibe.

### Neutral
- **Warm Cream Paper** (`#FEFAE0` — `oklch(97% 0.025 95)`): The page itself. Carries 60–80% of every screen. The visual equivalent of book paper.
- **Cream Surface** (`#FFF8E7`): Lifted page — sidebars, cards, secondary surfaces. Subtly raised tonal step from Warm Cream, no shadow needed.
- **Surface Raised** (`#F8F8F8`): The cooler-neutral toolbar/status surface (BUNDLE-E tokens). Used in editor chrome where warm cream would compete with chocolate prose.
- **Muted Cream** (`#E9E5D6`): Hover surfaces, disabled fields, reading rests. The "shadow of the page" without being a shadow.
- **Parchment Border** (`#D4C9A8`): The default dividing line. Warm, low-contrast, never aggressive.
- **Cool Border** (`#E5E7EB`): Editor-chrome border (BUNDLE-E). Used where Parchment Border would warm-tint code surfaces.
- **Body Ink** (`#2C1810`): Primary body and heading text on cream paper.
- **Muted Ink** (`#5A4A3D`): Secondary text, captions, breadcrumbs. Maintains AA on cream.
- **Cool Muted** (`#6B7280`): Editor-chrome muted text where warm muted would clash with code.

### Dark Mode
- **Deep Cocoa** (`#1C1210`): The dark-mode body. *Not* black, not slate — a hand-warmed cocoa tone.
- **Cocoa Surface** (`#261B16`): Lifted dark surface — sidebars, cards.
- **Warm Cream Inverse** (`#F0E8DC`): Body text on dark mode. Warmer than off-white; reads as cream, not paper.

### Named Rules

**The Cream Paper Rule.** Every primary surface defaults to `factory-bg` (`#FEFAE0`) in light mode and `factory-bg-dark` (`#1C1210`) in dark. Pure `#FFF` and pure `#000` are forbidden — every neutral is tinted toward chocolate, even at the extremes. If a designer reaches for `#FFFFFF`, redo the surface.

**The One Seal Rule.** Golden Seal (`#D4A843`) appears on ≤15% of any given screen. It is the verified-stamp color and the primary-emphasis color. If it covers more than that, the surface has lost its seal economy — demote uses to Golden Dim or remove.

**The Ledger-Green Means Signed Rule.** `#2D6A4F` is reserved for *cryptographic attestation rendered in the UI*: TimeChain ticks, verified-publication indicators, signed-by markers. Forbidden as a generic success color, a "save complete" toast, or a chart hue. If something is green, it has been signed.

**The Measured Contrast Rule.** A text or focus colour is chosen by measurement, never by eye. Text meets 4.5:1 and focus rings and other non-text indicators meet 3:1 (WCAG 2.2 AA, 1.4.3 and 1.4.11) against **every** surface they can sit on, not just the page background. The pairs below are measured; each figure is the worst case across this file's hex value and DESIGN.json's OKLCH `canonical`, which do not always agree (see the note after the table).

| Foreground | Background | Use | Worst case |
|---|---|---|---|
| Golden Ink `#845B00` | Warm Cream, Cream Surface, Code Background, Muted | link text, focus ring (light) | 4.63:1 (on Muted), 5.22:1 (on Code Background) |
| Golden Ink Dark `#D2A249` | Deep Cocoa, Cocoa Surface | link text, focus ring (dark) | 7.20:1 |
| Factory Heading `#2C1810` | Golden Dim | primary button | 4.95:1 |
| Factory Heading | Golden Seal | primary button hover | 6.98:1 |
| Factory Heading | Badge Verified | verified badge | 5.51:1 |
| Warm Cream `#FEFAE0` | Badge Failed | failed badge | 8.44:1 |
| Warm Cream | Ledger Green | attested badge | 5.85:1 |

These pairs fail and are not used: white on Golden Dim (2.92:1), white on Golden Seal (2.21:1), white on Badge Verified (2.74:1), Golden Dim as text or focus on Warm Cream (2.78:1) or Code Background (2.62:1).

*Note:* for most colours, the hex value in this file's frontmatter and DESIGN.json's OKLCH `canonical` are visibly different colours (Golden Dim: `#B8922E` here, `oklch(64% 0.13 80)` = `#B5820C` there). Consumers that read DESIGN.json render the OKLCH value. Which representation is authoritative is an open question; until it is answered, every contrast figure above is checked against both.

## 3. Typography

**Display Font:** Inter (with `ui-sans-serif, system-ui, sans-serif` fallback).
**Body Font:** Inter — same family; hierarchy carried by weight and size, not family.
**Mono Font:** JetBrains Mono (with `ui-monospace, Cascadia Code, monospace` fallback). Used for code samples, document IDs, mascot annotations, and label-grade signal text.

**Character:** Inter does the structural work; JetBrains Mono carries the factory-machinery voice — anywhere the system reveals its mechanism (code, IDs, annotations), it shifts to mono. Letter-spacing tightens negatively as size increases (`-0.03em` at display, `0` at body) to keep large headings tight and authoritative.

### Hierarchy
- **Display** (700, `2rem` / `clamp` to `1.5rem` mobile, `1.25` line-height, `-0.03em` letter-spacing): Page-level H1 in prose surfaces (`.prose-factory h1`). Carries a `2px solid Golden Dim` underline border-bottom — the factory's H1 stamp. *(See Don'ts for the heading stripe pattern.)*
- **Headline** (600, `1.5rem`, `1.3` line-height, `-0.015em` letter-spacing): Section H2. Carries a `3px solid Golden` left-edge accent in legacy code — flagged for cleanup.
- **Title** (600, `1.25rem`, `1.4` line-height, `-0.01em`): Subsection H3.
- **Body** (400, `1rem`, `1.8` line-height): The reading body. Line length must be capped at **65–75ch** on `/docs/*` long-form routes. Never below `16px` rendered, per accessibility (FEAT-054); keep margins at <640px by reducing padding, not type size.
- **Label** (600, `0.8125rem`, `1.5` line-height, `0.05em` letter-spacing, uppercase): H6 tags, table headers, badge text, breadcrumb meta. The system's "stamp" voice — small, spaced, authoritative.
- **Mono Code** (400, `0.875rem`, `1.6` line-height): Code blocks, inline code, document IDs, oompa-annotation copy.

### Named Rules

**The Mono-As-Mechanism Rule.** Mono type signals *the system speaking* — code, identifiers, annotations, telemetry. It is never used decoratively. If a piece of UI copy is in mono and is not a code/ID/annotation surface, rewrite it in sans.

**The 65ch Rule.** On any long-form prose route (`/docs/*`, published documents, factory-prose containers), body type wraps at 65–75ch. Wider columns are forbidden — long-form reading is sacred (per PRODUCT.md).

**The Inter-Only Rule.** Display, headline, title, body, and label all share Inter as their family. Hierarchy comes from weight + size + letter-spacing, never from a second display family. Do not introduce a serif display, a brand wordmark face, or a "personality" font without a decision-doc — a font addition is a north-star change.

## 4. Elevation

The system is **flat by default with warm tonal layering**. Depth is conveyed by stepping through cream tones (`factory-bg` → `factory-surface` → `factory-card-bg`), not by shadows. The single in-system shadow is a hairline ambient lift on the editor frame for legibility — it is not a "design effect."

Hover-state lifts use `transform: translateY(-3px)` (the floor-plan room hover) — a 3px nudge, not a shadow bloom. Animations ease out via `cubic-bezier(0.22, 1, 0.36, 1)` (page-fade-in) and `cubic-bezier(0.34, 1.3, 0.64, 1)` (springy room enter). No bounce, no elastic, no symmetric ease-in-out.

### Shadow Vocabulary
- **Editor Frame Lift** (`box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1)`): Used only on the `.editor-frame` container to separate the authoring surface from the page. Forbidden on cards, buttons, popovers, tooltips, or any other surface.

### Named Rules

**The Tonal-Layering Rule.** Depth is rendered by stepping warm tones, not by `box-shadow`. To raise a surface above the page, change its background tone (cream → cream-surface → card-bg), not its shadow. If you need a shadow to make a card feel "above," you are in the wrong system.

**The No-Glow Rule.** Hover and focus do not glow. Hover uses tonal shift (background warms one step) or translation (`translateY(-2..3px)`); focus uses a 2px `Golden Ink` outline (`Golden Ink Dark` in dark mode). Glassmorphic blurs, glow halos, ambient mesh backgrounds — forbidden.

**The Asymmetric-Easing Rule.** Enter and exit transitions never share a curve. Enters use a slight overshoot (`cubic-bezier(0.34, 1.3, 0.64, 1)` at 280ms — the room-spring); exits use a gentler settle (`cubic-bezier(0.25, 0.46, 0.45, 0.94)` at 360ms). The asymmetry avoids the mechanical feel of symmetric ease-in-out and is load-bearing for the factory's living quality.

## 5. Components

### Buttons
- **Shape:** Subtly rounded (`0.375rem` `rounded.sm`).
- **Primary (Publish, Save):** `Golden Dim` (`#B8922E`) background, `Factory Heading` (`#2C1810`) text (4.9:1; white text measures 2.9:1 and fails AA), `0.5rem 1rem` padding, body weight 500. Hover: shifts to `Golden` (`#D4A843`) at `opacity: 0.9` — the seal "brightens." No shadow, no scale.
- **Ghost (Cancel, Secondary actions):** Transparent background, `Muted Ink` text. Hover: `Muted Cream` background tint, text shifts to `Body Ink`. The ghost button never grows a border at rest.
- **Focus:** 2px `Golden Ink` outline (`Golden Ink Dark` in dark mode), `2px` offset. Always visible on `:focus-visible`.

### Toolbar Buttons (Editor)
- **Shape:** `2rem × 2rem` square with `0.375rem` radius.
- **Default:** Transparent background, `Body Ink` icon.
- **Hover:** `editor-toolbar-button-hover` — `rgba(184, 146, 46, 0.08)` (Golden Dim at 8% — a faint seal-tint).
- **Active (toggled on):** `editor-toolbar-button-active` — `rgba(184, 146, 46, 0.10)` plus a `1px Parchment Border` outline. The toggled state reads as pressed-into-paper.
- **Disabled:** `opacity: 0.5`, `cursor: not-allowed`. No greyscale shift.

### Dialogs / Modals
- **Use sparingly** — per **The Modal-Justification Rule** (below). Default to inline editing, slide-overs, and route-based dialogs.
- **Scrim:** `rgba(28, 18, 16, 0.55)` — a Deep Cocoa wash, never a `backdrop-filter: blur` glass effect. Fades in over 200ms.
- **Surface:** `Cream Surface` with `1px Parchment Border`, `0.5rem` radius, `Editor Frame Lift` shadow (the system's only sanctioned shadow). Animates in with an 8px translateY drop over 320ms.
- **Title:** Title-grade type (600 / `1.25rem`), with optional mono `0.75rem` meta line below (e.g. document ID, word count).
- **Actions:** Right-aligned. Ghost button (Cancel) + Primary button (Confirm/Publish). Action footer carries a `1px Parchment Border` top divider.
- **A11y:** `role="dialog"`, `aria-modal="true"`, `aria-labelledby` pointing at the title. Focus trapped inside; `Esc` and scrim-click both dismiss.

**The Modal-Justification Rule.** A modal must justify itself against three alternatives: inline editing, slide-overs, and route-based dialogs. If any of those fits the task, use it instead. Modals are appropriate for irreversible operations (publish, delete, attest), authentication, and explicit confirmations — almost nothing else.

### Floor-Plan SVG Room (signature spatial component)
The factory floor-plan is the dashboard's spatial metaphor — rooms represent services or document categories, hover springs the room up off the page. The signature interaction.
- **Layout:** SVG `<g class="room-group">` with three layered children: `room-tint` (golden wash, `opacity: 0` at rest), `room-body` (the visible rect with stroke), `room-status-ring` (circle with semantic color — Ledger Green for attested, Factory Wine for needs-review).
- **Hover/focus:** Spring up by `translateY(-3px)` over 280ms with overshoot easing; stroke brightens to `Golden Seal` at `2.5px`; tint fades in to `opacity: 0.10`. Mouse-leave settles back gently over 360ms (see The Asymmetric-Easing Rule).
- **Reduced motion:** All transitions and transforms disabled.
- **Keyboard:** Each room group is keyboard-focusable; focus-visible mirrors hover.

### Cards / Containers
- **Corner Style:** `0.5rem` (`rounded.md`) on editor frames; `0.375rem` (`rounded.sm`) on inline cards and annotations.
- **Background:** `Cream Surface` (warm) or `Surface Raised` (cool — chrome surfaces only). The choice signals whether the card is *paper* or *machinery*.
- **Shadow Strategy:** None. Flat by default. Editor frame is the single exception (Editor Frame Lift).
- **Border:** `1px Parchment Border` on warm/paper surfaces; `1px Cool Border` on chrome surfaces.
- **Internal Padding:** `1rem` standard; `0.75rem` for dense annotation cards; `2rem` for editor-frame interior.

### Oompa Annotation (signature component — REQ-011-004-C)
The system's narrator card. Cocoa-the-bean speaks here.
- **Layout:** Flex row, `0.5rem` gap, `0.75rem` padding.
- **Surface:** `Cream Surface` (or `factory-card-bg` in dark mode).
- **Type:** Mono, `0.75rem`, `1.5` line-height.
- **Color:** `Oompa Brown` (`#8B5E3C`) text by default. Variants: `--golden` (Golden text + border accent — narrator celebrating), `--warning` (Badge Failed text + border — narrator concerned).
- **Legacy concern:** Currently uses `border-left: 3px solid Factory Wine` as the accent stripe. This is a **side-stripe border**, banned per impeccable design laws. Flagged for cleanup — replace with full hairline border + leading mascot avatar, or with leading character glyph.

### Inputs / Fields
- **Style:** `1px Parchment Border` (warm surfaces) or `1px Cool Border` (chrome surfaces). Background `factory-surface` or `editor-content-bg`. Radius `0.375rem`.
- **Focus:** 2px `Golden Ink` outline (`Golden Ink Dark` in dark mode), 2px offset. The focus ring is the only state shift — no inner glow.
- **Selection:** `rgba(184, 146, 46, 0.15)` — a faint seal-wash.
- **Placeholder:** `Muted Ink` (warm) or `Cool Muted` (cool).

### Navigation
- **Background:** `factory-nav-bg` (`#FAFAFA` light, `#1A1310` dark).
- **Active item:** `rgba(184, 146, 46, 0.08)` background tint (the "seal-tint" — see toolbar hover).
- **Type:** Body weight 500 at `0.875rem`. Breadcrumbs use Body weight 400, separators use `Parchment Border` color.
- **Mobile:** Horizontal-scroll toolbar pattern when needed (editor toolbar already does this).

### Badges (Verification)
The system's stamp vocabulary. Type-driven, never icon-only.
- **Verified:** `Badge Verified` (`#C9923E`) background, `Factory Heading` text (5.5:1; white measures 2.7:1 and fails AA), label-grade type. Forbidden to use a green checkmark icon — verification status is rendered as a stamp, not a tick.
- **Failed:** `Badge Failed` (`#7A2E3A`) background, `Warm Cream` text (8.4:1). Forbidden to render this as red — `Badge Failed` is rose-wine, deliberately distinct from generic SaaS error red.
- **Attested (TimeChain-rendered):** `Ledger Green` background, `Warm Cream` text (5.9:1). Reserved for *cryptographic attestation surfaced in UI* — see The Ledger-Green Means Signed Rule.

### Code Blocks
- **Container:** `1px Cool Border`, `0.5rem` radius.
- **Header bar:** `editor-code-header-bg` (`#5C2433` light — a deep wine — / inverted dark). Carries language label in mono `0.75rem` uppercase.
- **Body:** `editor-code-bg` (`#F5F2F0` light / `#1E1612` dark). Mono `0.875rem`, `1.6` line-height.
- **Syntax tokens:** Choco-themed (`--choco-keyword: #8B6914`, `--choco-string: #B45309`, `--choco-function: #2563EB`, etc.). All token pairs verified ≥ AA contrast (≥6.8:1 light, ≥9.2:1 dark).

## 6. Do's and Don'ts

### Do:
- **Do** default every primary surface to **Warm Cream** (`#FEFAE0`) light / **Deep Cocoa** (`#1C1210`) dark. Pure `#FFF` and pure `#000` are forbidden.
- **Do** reserve **Golden Seal** (`#D4A843`) for ≤15% of any screen — verified states, primary CTAs, accent emphasis. Demote heavier uses to Golden Dim.
- **Do** use **Ledger Green** (`#2D6A4F`) only for cryptographic attestation rendered in UI. Never as a generic success color.
- **Do** render verification status as a typographic **stamp** (label-grade, uppercase, badge-shaped), not as an icon-only checkmark.
- **Do** use **JetBrains Mono** wherever the system speaks: code, document IDs, annotations, telemetry. Sans everywhere else.
- **Do** convey depth through **warm tonal layering** (cream → cream-surface → card-bg), not shadows.
- **Do** cap long-form body at **65–75ch** on `/docs/*` routes. Body must be ≥`16px` rendered.
- **Do** announce verification status, presence, and attestation as **screen-reader text**, not only as color.
- **Do** route page entrances through `factory-fade-in-up` (`500ms cubic-bezier(0.22, 1, 0.36, 1)`); honor `prefers-reduced-motion`.
- **Do** draw focus rings in **Golden Ink** (light) / **Golden Ink Dark** (dark) with `2px` offset. Always visible, and at least 3:1 against every surface they sit on.

### Don't:
- **Don't** use `#FFFFFF` or `#000000` for any surface, text, or border. Every neutral is tinted toward chocolate.
- **Don't** ship **gradient text**. The legacy `.golden-shimmer` (background-clip: text on a linear gradient) violates impeccable's absolute ban — flagged for cleanup. Use solid `Golden Seal` and emphasize via weight/size.
- **Don't** ship **side-stripe colored borders** greater than 1px. The legacy `.prose-factory h2` (3px Golden left edge), `h3` (2px Golden Dim left edge), `.oompa-annotation` (3px Wine left edge), and `.editor-blockquote` (3px Wine left edge) all violate the absolute ban — flagged for cleanup. Replace with full hairline borders, leading numbers/glyphs, mascot avatars, or background tint blocks.
- **Don't** introduce **glassmorphism** — backdrop-blur, frosted glass cards, glow halos, animated mesh backgrounds. AI-startup hero clichés are forbidden (per PRODUCT.md anti-references).
- **Don't** use **electric blue / purple / cyan gradient** as accent or emphasis. The category-reflex devtools palette is forbidden — Choco's accent is gold, not neon (per PRODUCT.md anti-references).
- **Don't** render verification with **crypto/web3 chrome**: holographic gradients, neon green, "transaction confirmed" toasts. The TimeChain is cryptographic; the UI is editorial (per PRODUCT.md anti-references).
- **Don't** introduce **pastel emoji block headers** or **rounded-everything friendly-blob illustrations** — the wiki softness reflex (per PRODUCT.md anti-references).
- **Don't** use **modal-as-first-thought**. Exhaust inline editing, slide-overs, route-based dialogs, and progressive disclosure first. A modal must justify itself.
- **Don't** stack **identical card grids** (icon + heading + text repeated endlessly). The SaaS-cliché grid is forbidden.
- **Don't** ship **the hero-metric template** (big number + small label + supporting stats + gradient accent). Find a better affordance.
- **Don't** use shadows for depth. Tonal layering only. The single `box-shadow: 0 1px 3px rgba(0,0,0,0.1)` on `.editor-frame` is the system's exception — do not extend it.
- **Don't** introduce a second display family. Inter carries display through label. A new face is a north-star change, not a refactor.
- **Don't** animate CSS layout properties (`width`, `height`, `top`, `left`, `padding`). Use `transform` and `opacity`.
- **Don't** use **bounce or elastic easing**. Ease out via exponential curves (`cubic-bezier(0.22, 1, 0.36, 1)` is the house easing).
