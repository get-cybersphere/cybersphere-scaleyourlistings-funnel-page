# Scale Your Listings — Brand Bible (Compass-Inspired)

**Version 2.0** · April 26, 2026
**Owner:** Cybersphere LLC, DBA Scale Your Listings
**Domain:** scaleyourlistings.getcybersphere.com
**Document type:** Single source of truth for the Compass-inspired visual direction. Hand to any design LLM, contractor, or engineer. This document is an alternative to the v1 HouseCanary-inspired bible (Brand-Bible.md) and may replace it depending on which direction wins.

---

## 0. How to use this doc

This bible inherits the **visual philosophy** of Compass.com (editorial minimalism, photography-dominant, color restraint, generous whitespace) and applies it to Scale Your Listings. It does not copy Compass's brand. Hex codes, font names, and layout principles are functional design facts — those carry over. Compass's logo, copy, illustrations, and proprietary photography do not.

The voice, positioning, ICP, and counter-positioning rules from v1 (Brand-Bible.md) carry over unchanged. Only the visual layer changes in this revision.

Three rules of thumb in priority order:

1. **If a section says "do not," it's non-negotiable.**
2. **If a section says "always," follow unless documented exception.**
3. **If a section says "prefer," lean on judgment.**

---

## 1. Brand DNA (carried over from v1)

| | |
|---|---|
| **Name** | Scale Your Listings |
| **Legal entity** | Cybersphere LLC, DBA Scale Your Listings |
| **Domain** | scaleyourlistings.getcybersphere.com |
| **Category** | AI-native listing acquisition platform for real estate agents and brokers |
| **Tagline** | The AI Listing Engine for Top Producers |
| **Offer hook** | Pay only when listings close |
| **Concrete offer** | 25+ FSBOs, Expireds & Probates Booked In 90 Days, Or You Do Not Pay |

### Ideal customer profile

Top-producing listing agents and small teams scaling past $400K annual GCI. Multi-vertical listing prospecting (FSBO + expired + probate). Already running paid ads. Has a CRM. Already pitched by kvCORE / BoomTown / Real Geeks / FollowUpBoss / Sierra in the last 12 months and exhausted.

### Counter-positioning vs. legacy stack

Their CRMs added AI in a sprint. Ours started with AI and got a CRM later. (Wedge sentence stays unchanged.)

---

## 2. Why the Compass aesthetic register

Top-producing listing agents look at Compass-style design every day. Their personal listing pages, their MLS dashboards, their broker-supplied marketing tools, the high-end print collateral they leave at open houses — all converge on the same visual register: editorial-minimalist, photography-led, sparing color, serious whitespace. By matching that register on the Scale Your Listings landing page, the buyer pattern-matches to "this is for me, this is built by people who understand my world" inside the first 2 seconds.

The HouseCanary direction (v1) targeted real-estate-data SaaS register and works for backend-tech buyers. The Compass direction (this v2) targets the actual front-of-house listing-agent buyer and reads as one tier more aspirational. **For Scale Your Listings' specific ICP, this is structurally the better pick.**

---

## 3. Color System

### Primary palette

| Token | Hex | Usage |
|---|---|---|
| `paper-white` | `#FFFFFF` | Primary surface. Default body background. The dominant color on every page. |
| `paper-off` | `#FAFAFA` | Secondary surface. Alternates with white for section rhythm. Subtle, almost invisible difference. |
| `paper-warm` | `#F7F5F1` | Tertiary surface. Used only for the rare warm-section moment (founder bio, single accent block). Maximum 1 instance per page. |
| `ink-900` | `#0A0A0A` | Display headlines. Strongest text. |
| `ink-800` | `#1A1A1A` | Default body text. Slightly warmer than pure black. |
| `ink-600` | `#4A4A4A` | Secondary text, captions |
| `ink-500` | `#666666` | Muted text |
| `ink-400` | `#888888` | Disabled, very muted |
| `ink-300` | `#C8C8C8` | Disabled UI |
| `ink-200` | `#E5E5E5` | Standard border / hairline |
| `ink-100` | `#F0F0F0` | Subtle divider |

### Accent

| Token | Hex | Usage |
|---|---|---|
| `compass-navy` | `#0E1F3D` | **Primary CTA color.** The single accent color on the entire system. Used for buttons, key links, brand emphasis moments. Maximum 3-4 instances per page. |
| `navy-hover` | `#1A2E55` | Hover state on `compass-navy` |
| `navy-50` | `#F0F2F7` | Tinted navy background, very subtle (used for input focus states, tag pills) |

That is the complete palette. Three categories: paper (3 surfaces), ink (8 grayscale stops), navy (3 accents). Total 14 tokens. The discipline is the system.

### Color usage rules (non-negotiable)

- **Default surface is `paper-white`.** Sections alternate between `paper-white` and `paper-off`. The `paper-warm` cream is reserved for one section per page maximum (typically the founder bio or a single editorial moment).
- **Default text on light surfaces is `ink-800`** (`#1A1A1A`). Display headlines step up to `ink-900` (`#0A0A0A`). Body never goes lighter than `ink-600`.
- **Primary CTA is `compass-navy` background with `paper-white` text.** No other button colors exist. No gradient buttons. No outlined CTAs except the secondary variant which uses 1px `ink-900` border on transparent background.
- **`compass-navy` is the only chromatic color in the system.** Do not introduce green, red, gold, yellow, or any other accent. The discipline is what makes this aesthetic work. The moment a second color enters, the editorial register collapses.
- **No gradients anywhere.** No multi-color treatments. No glow effects. Compass uses zero gradients on their site. We follow.
- **Photography is the only color-rich element on the page.** All chromatic interest comes from real listing/lifestyle photography (see Section 9). The chrome around the photography stays neutral.

---

## 4. Typography

### Type stack

| Family | Source | Use |
|---|---|---|
| **Fraunces** | Google Fonts (free, OFL) | Display, hero headlines, large editorial moments |
| **Inter** | Google Fonts (free, OFL) | Body, UI, sub-headings, eyebrows, navigation, all utility text |
| **Geist Mono** | Vercel (free, OFL) | Stat callouts, data labels, the few moments that need monospace |

Google Fonts import:

```html
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,opsz,wght@0,9..144,400;0,9..144,500;0,9..144,600;1,9..144,400&family=Inter:wght@400;500;600;700&family=Geist+Mono:wght@400;500&display=swap" rel="stylesheet">
```

### Why this stack

**Fraunces** is a high-contrast variable serif designed for display use. It carries editorial-luxury weight without going full Tiempos/Reckless price territory. Free, open-source, and used by Anthropic, Stripe Press, and several luxury-magazine-style sites. It gives Scale Your Listings the "this is curated content, not a templated funnel" register that Compass nailed in their early branding.

**Inter** is the modern sans workhorse. Compass uses a clean modern sans-serif throughout their UI; Inter matches that direction. Open-source, ubiquitous, performant.

**Geist Mono** is the data voice for stat callouts. Used surgically (similar to the SMC and 7FS bibles).

### Type scale

| Token | Size | Line-height | Tracking | Weight | Family |
|---|---|---|---|---|---|
| `display-xl` | 80px | 1.0 | -0.025em | 500 | Fraunces |
| `display-lg` | 60px | 1.05 | -0.022em | 500 | Fraunces |
| `display-md` | 44px | 1.1 | -0.02em | 500 | Fraunces |
| `display-sm` | 32px | 1.15 | -0.015em | 500 | Fraunces |
| `eyebrow` | 12px | 1.4 | 0.18em | 500 UPPER | Inter |
| `heading-lg` | 24px | 1.3 | -0.01em | 600 | Inter |
| `heading-md` | 20px | 1.35 | -0.005em | 600 | Inter |
| `heading-sm` | 16px | 1.4 | 0 | 600 | Inter |
| `body-lg` | 18px | 1.6 | 0 | 400 | Inter |
| `body-md` | 16px | 1.6 | 0 | 400 | Inter |
| `body-sm` | 14px | 1.5 | 0 | 400 | Inter |
| `mono-md` | 14px | 1.4 | 0 | 500 | Geist Mono |
| `mono-sm` | 12px | 1.4 | 0.04em | 500 | Geist Mono |

### Typography rules

- **Display Fraunces is for headline moments only.** Hero H1, section H2 on long-form sections, the rare editorial pull-quote. Never use Fraunces below 32px.
- **Eyebrows are uppercase Inter 500 with 0.18em tracking.** Wider tracking than the v1 HouseCanary bible (0.12em). The looser tracking signals editorial register vs. SaaS register.
- **Italic is allowed in Fraunces only.** Used for the rare emphasized phrase in display headlines (e.g., "*Scale* your listings"). Never italicize Inter body copy.
- **Numbers in stat callouts use Geist Mono.** "$72,000," "10 seconds" — read as data, not prose.
- **Body lines stay under 65 characters wide.** Tighter than v1 (70). Editorial register prefers narrower columns.
- **Headlines never exceed 12 words.**

---

## 5. Logo Direction

### Wordmark

"Scale Your Listings" set in **Fraunces 500** (medium weight, the editorial sweet spot for serifs). Letter-spacing -0.022em. Color: `ink-900` (`#0A0A0A`) on light surfaces, `paper-white` on dark surfaces.

The previous concept of accenting "More" in italic red is **replaced** in this aesthetic. The new emphasis: italicize "**Scale**" in Fraunces italic, in the same `ink-900` color (no chromatic accent). The italic moment becomes the brand mnemonic without breaking color discipline.

```
Scale Your Listings
^^^^^                (ink-900, Fraunces italic)
       ^^^^^^^^^^^^^ (ink-900, Fraunces upright)
```

This is a meaningful change from v1 — there's no chromatic moment in the logo at all. The italic serif carries the entire brand-mnemonic load.

### Mark / icon

A minimalist abstract mark. Recommend: **a single ascending serif "S"** in `ink-900`, set inside an unfilled `ink-200` 1px square (no rounded corners, no shadow). Or alternatively, no mark at all — just the wordmark. Compass uses both their wordmark and a needle symbol; we deliberately do not copy the needle. The ascending-S concept is its own thing.

### Don'ts

- **Do not use a compass needle or any directional/navigational icon.** Compass owns that visual territory.
- **Do not use house icons, keys, roofs, "for sale" signs.** Real estate clichés. The whole point of this aesthetic is to look like a Saint Laurent campaign that happens to be about listings.
- **Do not introduce color into the logo.** No navy, no canary, no nothing. Pure ink-on-paper.
- **Do not animate the logo on hover.**
- **Minimum clear space equals the cap-height of "S" on all sides.**

---

## 6. Layout, Grid, Spacing

| Property | Value |
|---|---|
| **Grid** | 12 columns, 24px gutter |
| **Max content width** | 1280px |
| **Max prose width** | 640px (tighter than v1; editorial register favors narrow columns) |
| **Section padding (desktop)** | 120px top + 120px bottom (more generous than v1's 100px; editorial breathing room is the signature move) |
| **Section padding (tablet)** | 80px |
| **Section padding (mobile)** | 56px |
| **Spacing base** | 8px. Multiples used: `8, 16, 24, 32, 48, 64, 96, 120, 160` |
| **Card padding** | 32px (desktop) / 24px (mobile) — tighter than v1, more editorial |

### Border radius

| Use | Value |
|---|---|
| Buttons | 4px (subtle, nearly square — Compass uses minimal rounding) |
| Cards | 8px |
| Hero blocks / large containers | 12px |
| Form inputs | 4px (matches buttons) |
| Pill tags | 999px (the only fully rounded element, used sparingly) |

Note: significantly tighter radii than v1. Editorial luxury aesthetics use minimal rounding. Compass-style design hovers around 4-8px max for nearly all components.

### Shadows

| Token | Value | Use |
|---|---|---|
| `shadow-soft` | `0 4px 24px rgba(10, 10, 10, 0.06)` | Default card elevation. Barely visible. |
| `shadow-photo` | `0 8px 40px rgba(10, 10, 10, 0.12)` | Photography card or featured listing card |
| `shadow-modal` | `0 16px 64px rgba(10, 10, 10, 0.16)` | Modal, dropdown |

Use shadows sparingly. The dominant separation device on this aesthetic is **whitespace and surface-color contrast**, not shadows.

### Borders

- 1px solid `ink-200` (`#E5E5E5`) on cards and dividers
- 1px solid `ink-100` (`#F0F0F0`) on subtle separators between content blocks
- 0.5px hairlines on small UI elements (text input bottom borders)

---

## 7. Component Patterns

### Primary CTA

```css
.btn-primary {
  background: #0E1F3D;
  color: #FFFFFF;
  padding: 16px 28px;
  border-radius: 4px;
  font-family: 'Inter', sans-serif;
  font-weight: 500;
  font-size: 15px;
  letter-spacing: 0.02em;
  border: none;
  transition: background 200ms ease;
  text-transform: none;
}
.btn-primary:hover { background: #1A2E55; }
```

Note: **Sentence-case button copy** ("Book the strategy call"), not all-caps. Compass uses sentence-case throughout. This is a meaningful divergence from v1 (which used UPPERCASE in some CTAs) — adopt the editorial register fully.

### Secondary CTA

```css
.btn-secondary {
  background: transparent;
  color: #0A0A0A;
  padding: 16px 28px;
  border-radius: 4px;
  font-family: 'Inter', sans-serif;
  font-weight: 500;
  font-size: 15px;
  border: 1px solid #0A0A0A;
}
.btn-secondary:hover { background: #0A0A0A; color: #FFFFFF; }
```

### Approved CTA copy library

- "Book the strategy call" (default)
- "See the AI work a live FSBO call"
- "Get the listing-pipeline audit"
- "Talk to the engineering team"

Same as v1. Voice doesn't change.

### Eyebrow / kicker

```html
<div class="eyebrow">For listing agents</div>
```

```css
.eyebrow {
  font-family: 'Inter', sans-serif;
  font-size: 12px;
  letter-spacing: 0.18em;
  text-transform: uppercase;
  color: #4A4A4A;
  font-weight: 500;
  margin-bottom: 24px;
}
```

Note: eyebrow color is `ink-600`, not navy. The accent stays restricted. Eyebrow is structural, not chromatic.

### Stat callout

```html
<div class="stat">
  <div class="stat-num">$72,000</div>
  <div class="stat-label">Avg. listing-side commission</div>
</div>
```

```css
.stat-num {
  font-family: 'Fraunces', serif;
  font-size: 60px;
  font-weight: 500;
  color: #0A0A0A;
  line-height: 1;
  letter-spacing: -0.02em;
}
.stat-label {
  font-family: 'Inter', sans-serif;
  font-size: 13px;
  color: #4A4A4A;
  margin-top: 12px;
  letter-spacing: 0.02em;
}
```

Note: stat numbers use **Fraunces serif**, not Geist Mono. This is the editorial register flex — numbers as typography, not data. Geist Mono is reserved for inline data labels, timestamps, and small dashboard moments. Big stat callouts get the Fraunces serif treatment.

### Card

```css
.card {
  background: #FFFFFF;
  border: 1px solid #E5E5E5;
  border-radius: 8px;
  padding: 32px;
  /* No shadow by default. Add only when card needs to lift off the surface. */
}
```

### Quote / testimonial

```css
.quote {
  font-family: 'Fraunces', serif;
  font-style: italic;
  font-size: 28px;
  line-height: 1.4;
  font-weight: 400;
  color: #0A0A0A;
  border-left: 2px solid #0A0A0A;
  padding-left: 32px;
  max-width: 720px;
}
.quote-attr {
  font-family: 'Inter', sans-serif;
  font-size: 14px;
  font-weight: 500;
  color: #4A4A4A;
  margin-top: 24px;
  padding-left: 34px;
}
```

Note: quote italic in Fraunces serif (not Inter). Quote left border in `ink-900` (not signal-red). Editorial register, no chromatic accent.

---

## 8. Imagery & Photography Direction

This is the section that **most differentiates** this v2 system from v1 and from every other Cybersphere DBA. The aesthetic is **photography-dominant**. Photography carries the entire visual interest of the page.

### Use

- **Architectural / property photography.** Real listings (with consent), exterior shots, interior detail shots. Editorial color, full-resolution, natural lighting. No filters, no Instagram-style desaturation, no duotone overlays.
- **Lifestyle photography that implies the listing-agent world.** Open house signage, listing presentation moments, agents on showings (with consent), neighborhood streetscapes. Aspirational but real.
- **Hero images go full-bleed.** No padding. The image is the hero, not the text overlaid on it. Text overlays use `ink-900` text directly on the image (with subtle drop-shadow or gradient backing only when contrast requires it).
- **Aspect ratios:** 16:9 for hero, 4:3 or 3:2 for property cards, 1:1 for thumbnail or grid imagery.

### Never use

- **Stock photos of agents in suits in front of homes.** The cliché.
- **Stock photos of "for sale" signs on lawns.** Same.
- **Hand-shake imagery.** Same.
- **AI-generated photorealistic property imagery.** Reads as fake within seconds.
- **Color filters or Instagram-style preset treatments.** Editorial color is natural color.
- **Drop shadows on photography.** Compass uses zero. We follow.

### When real photography isn't available

If you don't have access to consented client property photos, use:

- **Custom geometric illustration** in `ink-900` line work on `paper-white`. Architectural-feeling line drawings of building exteriors, floor plans, or abstract listing-pipeline visualizations.
- **Typography-as-image.** Display-size Fraunces serif as the visual element — a single word at 200px size can carry a hero block better than a generic stock image.
- **Single editorial photograph.** One real listing-context photo per major section, used large.

---

## 9. Section Application Examples

### Hero block (replaces v1 hero)

- **Eyebrow (Inter 500 UPPER, 12px, ink-600, 0.18em tracking):** *FOR LISTING AGENTS*
- **H1 (Fraunces 500, ink-900, 80px, italic-on-Scale-only):** *Scale your listings.*
- **H1 line 2 (Fraunces 400, ink-600, 80px):** Pay only when they close.
- **Sub (Inter 400, ink-600, 18px, max-width 480px):** Sub-10-second contact on every FSBO, expired, and probate inquiry. Listing appointments booked into your calendar with motivated sellers.
- **Primary CTA (compass-navy, paper-white text):** *Book the strategy call*
- **Below CTA, optional small line (Inter 400, ink-500, 13px):** *25 minutes. No pitch. Live AI demo.*
- **Background:** A single full-bleed editorial photograph of a luxury listing exterior at golden hour. Or pure `paper-white` with the typography carrying the entire hero. Both work; pick based on photography availability.

### "Why this team is different" section (adapted from v1)

Surface: `paper-off` (#FAFAFA) — alternating section.

- **Eyebrow:** *01 / WHY THIS TEAM*
- **H2 (Fraunces 500, ink-900, 44px):** *Why this team is different.*
- **Subhead (Inter 400, ink-600, 20px, max-width 640px):** Lead vendors sell shared lead lists. Our Stanford AI Growth Team brings you booked listing appointments.
- **Three-column block** with the existing 0:00 / 0:08 / 2:30 timestamp + ATTRACT / QUALIFY / BOOK & FOLLOW-UP body copy from the SYL Master Brief.
- **Stat callout below (Fraunces 60px serif numbers):** Listings go cold in 5 minutes...
- **Closing line (Inter 400, ink-800, 18px):** Every lead vendor before us was too slow by design. We finally fix that.

### Testimonial section (new application of v2)

Surface: `paper-warm` (#F7F5F1) — the rare warm moment, used here for the social proof block. 

- **H2 (Fraunces 500, ink-900):** *Don't take it from us. Take it from our clients.*
- Three cards per the existing Testimonial-Section-Payload.md, but restyled:
  - Card surface: `paper-white` on `paper-warm` background — subtle contrast
  - Quote body: Inter 400, ink-800, 16px (not italic)
  - Quote bold treatments: ink-900, weight 600
  - Attribution: Inter 500 ink-900 name, ink-600 role line, Geist Mono blue-600 for Andres's @handle (the only place navy appears in this section)
  - 5-star rating: replace canary stars with `ink-900` filled stars (accent color discipline)

### Final CTA (full-bleed dark)

Surface: `ink-900` (#0A0A0A) — the only dark section on the page.

- H2 (Fraunces 500, paper-white, 60px): *Pay only when listings close.*
- Sub (Inter 400, paper-white at 70% opacity, 18px): 25 minutes. No pitch. Live AI demo on the call, mapped to your current listing pipeline.
- CTA (paper-white background, ink-900 text): Book the strategy call

### Footer

Surface: `ink-900` text on `paper-off` background. Inter 400, 13px. Multi-column link grid in the Compass-style 4-column layout. Compliance disclaimer (Equal Housing Opportunity, etc.) in ink-500 11px at the bottom.

---

## 10. What This System Forbids

Hard "do nots" specific to this aesthetic:

- **No green, red, gold, yellow, orange, or purple anywhere.** The color system is paper + ink + navy. Period.
- **No gradients on any element.** Backgrounds are flat color or photography. No exceptions.
- **No glow effects, no neon, no "tech-futuristic" visual language.** The aesthetic is editorial print, not Silicon Valley.
- **No emoji in body copy.** No 👇 arrows pointing at CTAs (the templated GHL funnel signal). No celebration emojis.
- **No drop-shadows on text.** Text is flat. Always.
- **No oversized rounded corners.** Maximum 12px on the largest container. Buttons stay at 4px.
- **No animation on the logo or hover-spin effects.** Subtle fade-ins on scroll are acceptable. Bouncing, parallax-heavy, or scroll-jacked animations are not.

---

## 11. Voice and Tone (carried over from v1)

Voice rules don't change. Engineer-not-realtor. Direct. Numbers, not adjectives. Listing-agent register (GCI, MLS, DOM, FSBO, expired, probate). Banned words list applies in full.

The visual register is editorial. The voice register stays technical-engineering. The intentional contrast — visual luxury + voice precision — is the brand's most distinctive textural choice.

Banned words (carried from v1): leverage, synergize, world-class, best-in-class, cutting-edge, innovative, transform, unlock, harness, empower, revolutionary, abundance, mindset, "10X," "build relationships," "high-touch," "white glove," "concierge."

Required brand verbs and nouns (carried from v1): Scale, Listing, Closing, GCI, MLS, DOM, FSBO, sub-10-second, engineered, pay only when.

---

## 12. Sub-brand Relationship to Cybersphere

Updated brand-family architecture under the v2 direction:

```
Cybersphere LLC (parent)
├── 7 Figure Smiles      (cosmetic dental DBA · cream + forest green editorial)
├── Sign More Cases      (PI law DBA · cream + ink + Instrument Serif editorial)
└── Scale Your Listings  (real estate DBA · paper + ink + Fraunces · Compass-inspired editorial)
```

All three DBAs are now editorial in register but **distinctively positioned within editorial:**

- 7 Figure Smiles = warm editorial (forest green + cream)
- Sign More Cases = institutional editorial (cream + ink + serif)
- Scale Your Listings = minimalist-luxury editorial (paper + ink + Fraunces serif)

The brand family rhymes. Each DBA still has its own visual identity. SYL's specific differentiator: tighter color discipline (literally only navy as accent), Fraunces serif for display (vs. Instrument Serif at SMC), photography-dominant imagery direction.

---

## 13. Compliance (carried over from v1, unchanged)

Real estate marketing compliance rules don't change with the visual revision:

- Fair Housing Act
- MLS rules
- NAR Code of Ethics
- TCPA compliance for outbound voice AI
- State-specific advertising rules
- Equal Housing Opportunity disclosure in footer

Use the same boilerplate disclaimer as v1.

---

## 14. Concrete Copy Library (paste-ready)

Voice-level copy carries over from v1's Master Brief. Visual-level applications (eyebrow casing, headline italic placement, button copy capitalization) follow this v2 spec.

### Hero stack (committed)

```
Eyebrow:   FOR LISTING AGENTS

H1 line 1: Scale your listings.    [Fraunces 500, italic on "Scale" only]
H1 line 2: Pay only when they close.    [Fraunces 400, ink-600]

Subtitle: 25+ FSBOs, Expireds & Probates Booked in 90 days, or you do not pay.
            [Fraunces italic 400, 22px, ink-600, max-width 600px]

CTA:        Book the strategy call    [compass-navy bg, paper-white text]
```

### Section eyebrows (sentence-case UPPER tracked)

- `FOR LISTING AGENTS`
- `01 / WHY THIS TEAM`
- `02 / SPEED WINS LISTINGS`
- `03 / PAY ONLY WHEN LISTINGS CLOSE`

Note: section numbering replaces SaaS-style "Pillar" or "Step" framing.

### Stat callouts (Fraunces 60px serif numbers, Inter 13px ink-600 labels)

- `10s` — *First contact on every new seller inquiry*
- `$72,000` — *Avg. listing-side commission · live client roster*
- `94%` — *Show-up rate on AI-booked appointments*
- `12-day DOM` — *Avg. days on market vs. metro avg. of 28*

### Section headers (Fraunces 500, ink-900, 44px)

- *Why this team is different.*
- *Built by engineers. Not by another lead vendor.*
- *Don't take it from us. Take it from our clients.*
- *Pay only when listings close.*

### Final CTA block (on ink-900 dark surface)

```
Pay only when listings close.    [Fraunces 500, paper-white, 60px]

25 minutes. No pitch. Live AI demo on the call, mapped to your current
listing pipeline. If we're not a fit, we'll point you to what you should
be doing instead.    [Inter 400, paper-white at 70% opacity, 18px]

[ Book the strategy call ]    [paper-white bg, ink-900 text]
```

---

## 15. Validation Directive

This is v2 of the brand system. Whether to ship v2 over v1 (HouseCanary) or run them in parallel is a strategic decision that depends on:

1. **Speed-to-test.** v1 is already implemented in the live page hero. v2 requires re-implementation.
2. **Conversion priority.** If conversion math is more important than aesthetic polish, v1 ships faster. If aesthetic credibility with top-producer ICP is more important, v2 wins.
3. **A/B test feasibility.** Run both as parallel landing pages (e.g., `/v1` and `/v2` on scaleyourlistings.getcybersphere.com) for 7-10 days against the same paid traffic. Watch CPL, form-fill rate, strategy-call book rate.

| Metric | Floor | Target |
|---|---|---|
| Cost per lead vs. v1 baseline | within -15% | parity or better |
| Form-fill rate | ≥3% of unique visitors | ≥5% |
| Strategy-call book rate from form-fill | ≥35% | ≥50% |
| Call show rate | ≥60% | ≥75% |

**Hypothesis:** v2 will outperform v1 on call-show-rate (because the editorial register builds trust with top-producer buyers who are already pitched constantly), and will be roughly equal on form-fill rate. v1 may have a slight edge on cost-per-lead because the more colorful visual register is slightly louder in feed and may pick up more clicks.

If hypothesis confirms: replace v1 with v2 across all SYL surfaces. If conflicting: keep v2 for partner-pitch and sales decks, keep v1 for cold-traffic landing pages.

---

## 16. Quick Reference Cheat Sheet

If the design LLM needs to recall the system in five lines:

1. **Surface:** alternating `paper-white` (#FFFFFF) and `paper-off` (#FAFAFA). One section on `paper-warm` (#F7F5F1) per page max. Final CTA on `ink-900` dark.
2. **Text:** `ink-900` (#0A0A0A) for display, `ink-800` (#1A1A1A) for body, `ink-600` (#4A4A4A) for muted.
3. **Accent:** `compass-navy` (#0E1F3D) is the *only* chromatic accent. CTAs only. No green, red, gold, yellow, anywhere.
4. **Type:** Fraunces serif for display + stat numbers, Inter sans for body + UI, Geist Mono for inline data labels.
5. **Voice:** engineer-not-realtor. Banned-words list from v1 applies. Sentence-case in CTAs and buttons.

If unsure on a decision, default to whichever option looks **more like Compass** and **less like a templated GoHighLevel funnel**. That heuristic catches 80% of bad calls.

---

**End of Brand Bible v2.0 (Compass-inspired).**

This document is an alternative to Brand-Bible.md (v1, HouseCanary-inspired). Pick which version wins, or run them in parallel. The voice, ICP, positioning, and compliance rules are shared. Only the visual layer differs.
