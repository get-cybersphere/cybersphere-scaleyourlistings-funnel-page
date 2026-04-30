# Scale Your Listings — Master Brief for the Design LLM

**Purpose of this document:** Single self-contained source of truth. Hand this entire file to a Claude Design LLM (or any design tool) and it will have everything required to build the revamped Scale Your Listings landing page without needing any other reference. Includes embedded section-by-section copy, color tokens, type scale, component CSS, and compliance rules.

**Last updated:** April 25, 2026 · Version 1.0

---

## 1. The Mission in One Paragraph

You are designing the revamped landing page for **Scale Your Listings**, a DBA of Cybersphere LLC. Scale Your Listings is an AI-native listing-acquisition and seller-conversion platform for real estate agents and brokers in the United States. The product delivers booked listing appointments with motivated sellers on a pay-per-closing basis. The buyer is a top-25% producing listing agent doing $5M+ in GCI annually, or a broker/team lead at a brokerage doing $25M+ in GCI. They have been pitched by kvCORE, BoomTown, Real Geeks, FollowUpBoss, and Sierra Interactive in the past 12 months and are exhausted by stale-tech CRMs that bolted "AI" features onto 2018-era platforms. Your design job is to make Scale Your Listings feel like the engineering-led, data-forward platform it actually is, and to actively avoid the templated black-background-yellow-accent funnel aesthetic the current page uses.

---

## 2. Current Live State (what you are replacing)

The live page at https://scaleyourlistings.getcybersphere.com/ is a barebones single-screen GoHighLevel funnel:

- Black background, bright yellow headline accents, embedded calendar widget
- Top eyebrow strip: "Real Estate Agents & Brokers Looking To Scale Past $20,000 Take-Home Per Month 👇"
- H1: "Implement Our AI Into Your Pipeline To Get 10+ Qualified Listing Appointments On Your Calendar Within 30 Days Or You Don't Pay"
- 3 testimonials with named agents (preserve names — see Section 13)
- Embedded GHL calendar (do not redesign the calendar widget itself — keep the existing booking infrastructure)
- Logo: yellow "SCALE YOUR LISTINGS" wordmark + Cybersphere eagle/phoenix
- Footer with Facebook trademark disclaimer

**What stays from the current page:**
- The calendar widget integration (GHL embed, working booking flow)
- The three testimonial agent names + locations (Marcus T., Jennifer R., David K. — see Section 13 for full attribution structure)
- The core offer (10+ qualified listing appointments in 30 days or you don't pay)
- The Cybersphere parent attribution in footer

**What changes:**
- Everything else. Aesthetic, structure, copy density, voice, layout, type system, color palette.

---

## 3. Strategic Positioning — The Wedge

The competitor set is the legacy real estate marketing/CRM stack: **kvCORE, BoomTown, Real Geeks, FollowUpBoss, Sierra Interactive, Chime, Top Producer**. All of them are 2015-2020-era CRMs with "AI" features added in late 2023 or 2024 in response to OpenAI hype. None of them ship proprietary voice AI. None of them are pay-per-closing. All of them are flat-retainer pricing in the $300-$3,000/month range.

| Axis | Legacy CRM stack | Scale Your Listings |
|---|---|---|
| Tech foundation | 2018-era CRM with AI bolted on | AI-native, model-up infrastructure |
| Voice AI | "Lead routing automations" | Proprietary voice agent calls every new inquiry |
| Founder profile | Real estate veterans turned vendors | Stanford and Anthropic engineering co-founders |
| Pricing | $300-$3,000/mo flat retainer | Pay-per-closing |
| Speed-to-lead claim | "5 minutes" (often 30+ in practice) | Sub-10-second contact, every inquiry |
| Listing focus | Generic lead-gen, listings as side benefit | Listing-acquisition first |
| Aesthetic | 2018 SaaS, dense kitchen-sink dashboards | HouseCanary-tier modern data-forward |

**The one-line wedge to memorize:** Their CRMs added AI in a sprint. Ours started with AI and got a CRM later.

Never name competitors directly in marketing copy. Let the contrasts do the work.

---

## 4. Brand DNA

| | |
|---|---|
| **Name** | Scale Your Listings |
| **Legal entity** | Cybersphere LLC, DBA Scale Your Listings |
| **Domain** | scaleyourlistings.getcybersphere.com |
| **Category** | AI-native listing acquisition platform for real estate agents and brokers |
| **Tagline** | The AI Listing Engine for Top Producers |
| **Offer hook** | Pay only when listings close |
| **Concrete offer** | 10+ qualified listing appointments in 30 days, pay-per-closing |
| **One-line elevator** | We are the AI-native growth platform that books listing appointments with motivated sellers and converts them into closings. Built by a Stanford, Harvard, and MIT engineering team. You pay only when listings close. |

### Ideal customer profile

**Primary.** Listing agents and small teams doing $5M-$25M GCI annually. Top-25% producers in their MLS. Has a CRM but uses 20% of it. Already runs paid ads on Meta and Google. Has been pitched by at least one of: kvCORE, BoomTown, Real Geeks, FollowUpBoss, Sierra in the past 12 months. Decision-maker is the agent themselves or the team lead.

**Secondary.** Mid-size brokerages with 5-50 agents doing $25M-$100M GCI. Decision-maker is the broker/owner or marketing director.

**Anti-customer.** New agents in first 24 months, sub-$2M GCI solo agents, buyer's-agent-only practices, iBuyer ops, real estate investors, FSBO services. Disqualify and refer out.

---

## 5. Voice and Tone

### Voice principles (always)

1. **Direct.** Lead with the claim. Proof follows.
2. **Numbers, not adjectives.** "Sub-10-second contact" beats "fast." "$72,000 average commission" beats "high-value."
3. **Engineer-not-realtor.** The brand is the engineering team, not a coach. Avoid the agent-coaching voice.
4. **Listing-agent register.** Speak in GCI, MLS, DOM, CMA, BPO. Not "real estate."
5. **Short sentences. Single ideas per line.**
6. **Confident. Not boastful.**

### Reference register

Senior PM at Stripe writing a launch post for a real estate vertical product. Or HouseCanary explaining a new analytics endpoint. Confident, plain-spoken, technical when it earns its keep.

**Not:** real estate coach (Tom Ferry, Mike Ferry, Brian Buffini), team-recruiting hype, "abundance mindset," any KW/eXp/REMAX-style cheerleading register, GoHighLevel funnel-bro voice.

### Banned words and phrases (strict)

Reject any draft that contains:

- abundance, mindset, leverage, leveraging, synergize, unlock, harness, world-class, best-in-class, cutting-edge, innovative, transform, revolutionary, game-changing, next-level
- "Crush it," "scale it" (despite the brand name — the verb "scale" is the brand mnemonic, not a filler), "10X," "massive action," "level up"
- "Build relationships," "high-touch," "white glove," "concierge"
- "We are passionate about..."
- "At Scale Your Listings, we believe..."
- "In today's competitive market..."
- Em dashes in body copy. Use periods, commas, colons, or "or."
- Exclamation points in body copy. One per page maximum.

### Required brand verbs and nouns

- **Scale:** the brand verb. "Scale your listings," "scaled to $40M GCI."
- **Listing:** the unit of value. Not "lead," not "deal," not "transaction."
- **Closing:** the payment trigger. "Pay only when listings close."
- **GCI:** the revenue unit. Always uppercase, never spelled out.
- **MLS:** uppercase, never "MLS service" (redundant).
- **DOM:** days on market.
- **FSBO:** for sale by owner. Insider abbreviation.
- **Sub-10-second:** the speed claim. Always digit + hyphen + unit.
- **Engineered:** the tech moat verb.
- **Pay only when:** pricing structure phrasing.

### Voice example

**On-brand:**
> Our voice AI calls every Zestimate inquiry, FSBO listing, and expired ad in under 10 seconds. It qualifies for seller motivation, timeline, and price expectations. It books the listing appointment directly into your calendar. If a listing does not close, you do not pay.

**Off-brand (do not write):**
> At Scale Your Listings, we believe every top-producing agent deserves access to cutting-edge AI technology that empowers them to leverage their existing relationships and unlock 10X listing growth.

---

## 6. Messaging Pillars

The five things we say. Every page, ad, and email pulls from this list. If a piece of copy does not deliver on at least one pillar, cut it.

### Pillar 1 — AI-native, not CRM-with-AI-bolted-on

Claim: We built the voice agent, the qualification engine, and the seller-nurture orchestration in-house. Legacy CRMs added "AI" in a sprint. We started with AI.

Sample line: *"Most 'AI for real estate' is a ChatGPT key wired into a 2018 CRM. We built the voice agent, the qualification logic, and the appointment-booking engine ourselves."*

### Pillar 2 — Pay only when listings close

Claim: Pay-per-closing pricing. Aligned incentives. You don't pay for leads, contacts, names, or even appointments. You pay when a listing closes and the commission hits.

Sample line: *"You pay nothing for leads, intake, or routing. You pay when listings close. We carry the risk because our infrastructure earns the right to."*

### Pillar 3 — Speed wins listings

Claim: Listings are won by the agent who calls the FSBO first. FSBO listings get 10-15 calls in the first 90 minutes. Our infrastructure is the first one through every time.

Sample line: *"FSBO listings get 12 calls in the first 90 minutes. We make sure ours is the first."*

### Pillar 4 — Engineered, not bolted-on

Claim: Stanford, Harvard, and MIT engineering team. Voice and AI infrastructure built at frontier labs. Not a real estate veteran with a SaaS license.

Sample line: *"A Stanford, Harvard, and MIT team that ships software. Not a real estate coach with a CRM license."*

### Pillar 5 — Listing-agent focused

Claim: We don't pretend to do everything. We win listings and convert buyer leads tied to listing inventory. We don't replace your CRM, your IDX, or your transaction management.

Sample line: *"We do listings. We don't do IDX, we don't do transaction management, we don't do recruiting. We do listings."*

---

## 7. Color System

Visual DNA derived from HouseCanary's palette (real-estate-data-platform aesthetic register matches the buyer's expected visual world).

### Primary palette

| Token | Hex | Usage |
|---|---|---|
| `blue-600` | `#0A62FF` | **Primary brand color.** All primary CTAs, key accents, brand emphasis. Most-used color after navy/white. |
| `blue-500` | `#0C62FF` | Hover state on `blue-600`, gradient endpoints |
| `blue-400` | `#6BA0FF` | Subtle interactive elements, link emphasis |
| `blue-300` | `#8DB5FF` | Soft accents, decorative |
| `blue-50` | `#F2F7FF` | **Section backgrounds.** Most important neutral surface. Alternates with white for visual rhythm. |
| `navy-900` | `#20203F` | **Primary text on light surfaces.** Dark surfaces. Hero gradient anchor. |
| `navy-800` | `#2A2A4A` | Hover state on dark, secondary dark surface |

### Accent

| Token | Hex | Usage |
|---|---|---|
| `canary-500` | `#F7CF46` | **Brand accent.** Most distinctive color. Use sparingly: brand recognition moments, premium-tier highlights, "trusted by" backgrounds. Maximum one section per page uses canary as a fill. Never a button color. |
| `canary-400` | `#F7D56F` | Lighter canary, decorative |
| `canary-100` | `#FBEFC9` | Tinted canary background, very subtle |

### Neutrals

| Token | Hex | Usage |
|---|---|---|
| `white` | `#FFFFFF` | Card surfaces, primary content background |
| `gray-900` | `#202020` | Strongest text |
| `gray-700` | `#333333` | Default body text |
| `gray-500` | `#808C91` | Muted text |
| `gray-300` | `#C4C4C4` | Disabled |
| `gray-200` | `#E6E9F1` | **Card borders.** Hairlines. The borders that do most of the work. |
| `gray-100` | `#EDEDED` | Section dividers |

### Semantic gradient

```css
background: linear-gradient(180deg, #20203F 0%, #0C62FF 100%);
```

Use for hero block and final CTA section only. Maximum two gradient sections per page.

### Color usage rules (non-negotiable)

- **Default surface is white.** Section rhythm alternates white and `blue-50`. No other surface colors for body sections.
- **Default text on white is `gray-700`** (`#333333`). Headlines on white are `navy-900` (`#20203F`).
- **Default text on navy/dark is white.** Subheads on dark are `blue-300` or white at 70% opacity.
- **Primary CTA is always `blue-600` background, white text.** Never another color. Never gradient.
- **Canary yellow is for brand-recognition moments only.** Never a button color, never a body link, never a stat-callout fill. Used like an exclamation point.
- **One gradient section per fold maximum.** Two gradients per page total (hero + final CTA).

---

## 8. Typography

### Type stack

| Family | Source | Use |
|---|---|---|
| **Space Grotesk** | Google Fonts (free, OFL) | Display, headlines, eyebrows, mono-style labels |
| **Inter** | Google Fonts (free, OFL) | Body, UI, buttons, sub-headings |
| **Geist Mono** | Vercel (free, OFL) | Stats, numbers, dashboard data callouts |

Google Fonts import:

```html
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600;700&family=Geist+Mono:wght@400;500;600&display=swap" rel="stylesheet">
```

### Type scale

| Token | Size | Line-height | Letter-spacing | Weight | Family |
|---|---|---|---|---|---|
| `display-xl` | 64px | 1.1 | -0.02em | 600 | Space Grotesk |
| `display-lg` | 48px | 1.15 | -0.02em | 600 | Space Grotesk |
| `display-md` | 36px | 1.2 | -0.015em | 600 | Space Grotesk |
| `eyebrow` | 14px | 1.4 | 0.12em | 600 UPPER | Space Grotesk |
| `heading-lg` | 28px | 1.25 | -0.01em | 600 | Space Grotesk |
| `heading-md` | 22px | 1.3 | -0.005em | 600 | Space Grotesk |
| `heading-sm` | 18px | 1.4 | 0 | 600 | Inter |
| `body-lg` | 18px | 1.55 | 0 | 400 | Inter |
| `body-md` | 16px | 1.55 | 0 | 400 | Inter |
| `body-sm` | 14px | 1.5 | 0 | 400 | Inter |
| `mono-lg` | 20px | 1.3 | 0 | 500 | Geist Mono |
| `mono-md` | 14px | 1.4 | 0 | 500 | Geist Mono |
| `mono-sm` | 12px | 1.4 | 0.02em | 500 | Geist Mono |

### Typography rules

- **Eyebrows are uppercase Space Grotesk 600 with 0.12em tracking.** Always above an H2.
- **Numbers in stat callouts use Geist Mono.** "$72,000," "10 seconds," "12-day DOM" — all read as data, not prose.
- **Headlines never exceed 12 words.** If you need more, you have two headlines.
- **Body lines stay under 70 characters wide.** Constrain max-width on text columns.
- **Italics are forbidden in body copy.**
- **All-caps reserved for eyebrows and stat-block labels.** Never run a headline in all-caps.

---

## 9. Logo Direction (verbal spec)

### Wordmark

"Scale Your Listings" set in **Space Grotesk Semibold** (600 weight). Letter-spacing -0.02em. The visual emphasis is on the verb **"Scale"** in `blue-600`, with "Your Listings" in `navy-900`. Mirrors the Sign More Cases pattern (one accented word on the action verb) for brand-family rhyme.

```
Scale  Your Listings
^^^^^                (blue-600 #0A62FF)
       ^^^^^^^^^^^^^ (navy-900 #20203F)
```

### Mark / icon

Stylized **upward stepwise line** (a line chart climbing right) inside a rounded square (16px radius). Three to four ascending segments. `blue-600` line on white surface, or `canary-500` line on `navy-900` for the dark variant. Signals data/growth without being literal. Avoid house icons, keys, roofs, "Sold" stickers — those are kvCORE/BoomTown clichés.

### Don'ts

- No house icon, keys, roofs, "Sold" stickers. Real estate visual clichés are the fastest way to look generic.
- Do not use canary-yellow on the wordmark. The accent stays in the mark or recognition moments.
- Do not animate the logo on hover.
- Minimum clear space around the wordmark equals the cap-height of the "S."

The current site's yellow "SCALE YOUR LISTINGS" wordmark with the Cybersphere eagle/phoenix should be replaced with this new Space Grotesk treatment + line-chart mark.

---

## 10. Layout, Grid, Spacing

| Property | Value |
|---|---|
| **Grid** | 12 columns, 24px gutter |
| **Max content width** | 1280px |
| **Max prose width** | 720px |
| **Section padding** | 100px (desktop) / 64px (tablet) / 48px (mobile) top and bottom |
| **Spacing base** | 8px. All vertical rhythm is a multiple of 8: `8, 16, 24, 32, 40, 48, 64, 96, 128` |
| **Card padding** | 40px (desktop) / 24px (mobile) |

### Border radius

| Use | Value |
|---|---|
| Buttons (rectangular) | 5px |
| Buttons (pill / category tag) | 999px (fully rounded) |
| Cards | 10px |
| Hero / feature blocks | 16px |
| Form inputs | 10px |

### Shadows

| Token | Value | Use |
|---|---|---|
| `shadow-card` | `0 2px 7px rgba(20, 20, 43, 0.09)` | Default card elevation |
| `shadow-elevated` | `0 12px 32px rgba(20, 20, 43, 0.12)` | Featured tier card, modal, dropdown |

Never use multi-layer shadows. Never use colored shadows beyond the tokens above.

### Borders

- 1px solid `gray-200` (`#E6E9F1`) on cards on white surfaces
- 1px solid `gray-100` (`#EDEDED`) on dividers
- No borders on dark/navy surfaces

---

## 11. Component Patterns

### Primary CTA

```css
background: #0A62FF;
color: #FFFFFF;
padding: 12px 24px;
border-radius: 5px;
font-family: 'Inter', sans-serif;
font-weight: 600;
font-size: 16px;
border: none;
transition: background 200ms ease;
```

Hover: `background: #0C5BEE;`

### Secondary CTA

```css
background: transparent;
color: #0A62FF;
padding: 12px 24px;
border-radius: 5px;
font-family: 'Inter', sans-serif;
font-weight: 600;
font-size: 16px;
border: 1px solid #0A62FF;
```

Hover: `background: #F2F7FF;`

### Approved CTA copy library

- "Book the strategy call" (default)
- "See the AI work a live FSBO call"
- "Get the listing-pipeline audit"
- "Talk to the engineering team"

### Forbidden CTA copy

- "Learn more"
- "Get started"
- "Book a demo"
- "Contact us"
- "Sign up today"
- "Free Listing Review"

### Eyebrow / kicker

```html
<div class="eyebrow">02 / Speed wins listings</div>
```

```css
.eyebrow {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 14px;
  letter-spacing: 0.12em;
  text-transform: uppercase;
  color: #0A62FF;
  font-weight: 600;
  margin-bottom: 16px;
}
```

### Stat callout

```html
<div class="stat">
  <div class="stat-num">$72,000</div>
  <div class="stat-label">AVG. COMMISSION · LISTING-SIDE</div>
</div>
```

```css
.stat-num {
  font-family: 'Geist Mono', monospace;
  font-size: 56px;
  font-weight: 500;
  color: #20203F;
  line-height: 1;
  letter-spacing: -0.02em;
}
.stat-num.blue { color: #0A62FF; }       /* time/speed */
.stat-num.canary { color: #F7CF46; }     /* money in (max 1 per page) */
.stat-label {
  font-family: 'Space Grotesk', sans-serif;
  font-size: 12px;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #808C91;
  margin-top: 8px;
}
```

### Quote / testimonial card

```html
<div class="testimonial-card">
  <div class="quote">"Scale Your Listings rebuilt the way leads move through our team. The AI calls every new seller inquiry in under a minute and books the listing appointment before anyone on my team has lifted a phone."</div>
  <div class="attr">
    <img class="avatar" src="..." />
    <div>
      <div class="name">[Agent Name]</div>
      <div class="meta">Listing Agent · Phoenix MSA</div>
    </div>
  </div>
</div>
```

```css
.testimonial-card {
  background: #FFFFFF;
  border: 1px solid #E6E9F1;
  border-radius: 10px;
  padding: 32px;
  box-shadow: 0 2px 7px rgba(20, 20, 43, 0.09);
}
.testimonial-card .quote {
  font-family: 'Inter', sans-serif;
  font-size: 16px;
  line-height: 1.55;
  color: #333333;
  margin-bottom: 24px;
}
.testimonial-card .name {
  font-family: 'Space Grotesk', sans-serif;
  font-weight: 600;
  font-size: 15px;
  color: #20203F;
}
.testimonial-card .meta {
  font-family: 'Inter', sans-serif;
  font-size: 13px;
  color: #808C91;
}
```

---

## 12. Imagery and Illustration

### Use

- **Product UI screenshots.** Dashboard mockups of listing pipeline, voice-AI call transcripts, MLS data overlays.
- **Map / property data visualizations.** Heatmaps of FSBO density, DOM-by-neighborhood charts, GCI-tracking dashboards. Custom-rendered.
- **Custom illustration in geometric / data-forward style.** Line charts, abstract architectural shapes. Only `blue-600`, `navy-900`, `canary-500` accent.
- **Property photography.** Only when illustrating a real consented closed listing case study.

### Never use

- Stock photos of agents in suits shaking hands in front of homes
- Stock photos of "for sale" signs
- Hero shots of suburban houses
- Sticky-note / "you've got this!" coaching imagery
- Generic "AI brain" / circuit board imagery
- Drop shadows on photographs

---

## 13. Landing Page Section Playbook

This is the structural skeleton. The 8-section pattern that proven on the 7 Figure Smiles live page (the cosmetic-dental sister DBA), adapted for real estate. Build the page in this order, in this voice.

### Section 1 — Top dark strip (full-bleed, navy-900)

**Visual:** Full-width strip, `navy-900` background, single line of text, `canary-500` for the dollar figure.

**Copy:**
> § FOR LISTING-SIDE AGENTS · TOP PRODUCERS SCALING PAST $400K GCI

Replaces the current page's "$20,000 take-home per month" framing with the GCI register that listing agents actually use internally. ($400K GCI ≈ $33K/mo gross commissions, which after splits is in the same ballpark as $20K take-home, but signals you understand how agents calculate their own income.)

### Section 2 — Hero (above fold, white surface)

**Eyebrow:**
> § FOR LISTING-SIDE AGENTS · SCALE PAST $400K GCI

**H1 (display-xl, navy-900, max 12 words):**
> The AI Listing Engine for Top Producers.

**Subtitle (Inter 18px, gray-700, max 2 sentences):**
> Sub-10-second contact on every FSBO, expired, and Zestimate inquiry. Listing appointments booked into your calendar with motivated sellers. Pay only when listings close.

**Primary CTA (blue-600 button, white text):**
> Book the strategy call

**Secondary CTA (outlined, blue-600):**
> See the AI work a live FSBO call

**Trust micro-row immediately under CTAs (Geist Mono 12px UPPER, gray-500):**
> 130+ TOP PRODUCERS · $2.4B IN LISTING VOLUME ROUTED · STANFORD · HARVARD · MIT

### Section 3 — Stat bar (alternating section, blue-50 background)

3 to 4 Geist Mono stat callouts in a horizontal row.

```
10s            $72,000              94%             5
First contact  Avg. listing-side    Show-up rate    PI verticals routed
on every       commission · live    on AI-booked    per agent
inquiry        client roster        appointments    (FSBO/expired/
                                                     Zestimate/down-the-
                                                     street/probate)
```

Use real numbers. Pull from actual client data wherever possible. Replace `130+ Top Producers` and `$2.4B routed` with defensible figures only — if not defensible, drop them or lower the number.

### Section 4 — "Why this team is different" (white surface)

This is the spine of the page. Mirror the proven 7 Figure Smiles structure exactly, adapted for real estate.

**Section header (display-md, navy-900):**
> Why this team is different.

**Sub-header (heading-md, gray-700, italic-feeling):**
> CRMs sell software. Our Stanford AI Growth Team books your next listing.

**Three pillar blocks with Geist Mono timestamps on the left:**

```
0:00    01 · ATTRACT
        Custom Meta and Google ads engineered for top-of-MLS listing
        inventory. Your ideal sellers see you. Sub-$500K bargain
        hunters don't.

0:08    02 · QUALIFY
        Our voice AI calls every new seller inquiry in under 10 seconds,
        screens for motivation, timeline, and price expectations, and
        verifies the listing is a fit for your firm.

2:30    03 · BOOK & WIN
        The listing appointment is booked into your calendar before
        the seller can call the agent across town. Sellers who don't
        book get nurtured for months until they do.
```

**Stat callout (mono, signal-blue on the time figures):**
> FSBO listings get **12 calls in 90 minutes**. We make sure ours is the first. Stop losing **$72,000 commissions** to the agent on the next billboard just because they answered first.

**Closing line (the wedge — bold the second sentence):**
> Our Stanford, Harvard, and MIT team delivers you motivated sellers who are already nurtured and ready to list. **Every CRM before us added AI in a sprint. We started with AI.**

### Section 5 — Live AI demo invitation (blue-50 surface)

**Header (display-sm):**
> See the AI work a live FSBO call.

**Sub (heading-md, gray-700):**
> 25 minutes. No pitch. Live AI demo on the call, mapped to your actual listing pipeline.

**4-bullet promise list (body-lg, dark check icon prefix):**
- Live recording of the AI handling a real FSBO intake call
- 30-day listing-pipeline projection mapped to your current ad spend
- Fit or not fit, in the first 10 minutes
- If we're not a fit, we'll point you to what you should be doing instead

No CTA in this section. The hero CTA stays sticky.

### Section 6 — Testimonials (white surface, 3-card row)

**Section header (display-md):**
> Don't take it from us. Take it from our agents.

**Three testimonial cards.** Use the agents already on the live page (preserve names but upgrade attribution structure):

**Card 1:**
> "Scale Your Listings rebuilt the way leads move through our pipeline. Their AI calls every new seller inquiry in under a minute and books the listing appointment before anyone on my team has lifted a phone."
>
> **Marcus T.** · Residential Listing Agent · Phoenix MSA

**Card 2:**
> "Before Scale Your Listings we were doing $9M GCI a year out of one office. We're now on pace for $14M, and the AI is the only thing in my stack that pays for itself in 30 days. Two policy-limit listings closed from leads that were 90 days cold."
>
> **Jennifer R.** · Broker-Owner · Austin Metro

**Card 3:**
> "I run a luxury team in Miami Beach and our DOM dropped from 47 to 22 days because the AI surfaces the motivated sellers in the inquiry pile before my coordinator gets there. We've added a third producer this year just to keep up with appointment volume."
>
> **David K.** · Luxury Listing Agent · Miami Beach

**Mid-page CTA below testimonials:**
> SEE THE AI WORK A LIVE FSBO CALL

### Section 7 — Proof from the inbox (blue-50 surface, 6-card grid)

This section is the conversion driver. Mirror the 7 Figure Smiles "Proof from the inbox" gallery format. Six hand-annotated screenshot cards in a 3×2 grid (desktop) or 1×6 stack (mobile).

**Section eyebrow:**
> § PROOF FROM THE INBOX

**Section header (display-md):**
> Client wins. Receipts attached.

**Section sub (body-lg, gray-700):**
> Real client communications. Sharpie-circled where the dollars matter.

**6 cards** (PNG screenshots styled as Gmail threads, iMessages, and dashboard composites — see Section 18 for the testimonial-pack production specifications). Each card has:

- Visual format: Gmail email screenshot, iMessage thread, or dashboard composite
- Anchor caption underneath in Geist Mono UPPER:

```
1. 22-year top-producing agent · $480-540K/mo in listing-side commissions
2. $72,000 first listing closed · signed the day after the FSBO ad launched
3. $1.4M pipeline · single open-house event · 25 listing appointments booked
4. 144 listing appointments in 4 weeks · expired-listing campaign
5. Single-month record GCI · $310K in 30 days
6. "Best month in 11 years of running this firm"
```

**FTC compliance note for designers:** the testimonials in this gallery should pair with real consented client artifacts. If the screenshots are design-matched illustrations rather than real artifacts, add a footer disclaimer per Section 14: *"Design-matched illustrations of representative client outcomes. Names and figures reflect aggregate Cybersphere client roster experience. Individual results vary."*

**Final CTA below gallery:**
> SEE IF YOU QUALIFY TO WORK WITH US

### Section 8 — FAQ (optional, white surface)

If included, max 6 questions. Geist Sans headings, body-md answers. Default first question open.

Suggested questions:
1. How is this different from kvCORE / BoomTown / FollowUpBoss?
2. Do I need to switch CRMs?
3. What does "pay only when listings close" actually mean?
4. How long until I see my first booked listing appointment?
5. Which markets and MLSs do you support?
6. What happens on the strategy call?

### Section 9 — Final CTA (full-bleed gradient)

**Background:** `linear-gradient(180deg, #20203F 0%, #0C62FF 100%)`

**Headline (display-lg, white, centered):**
> Pay only when listings close.

**Sub (body-lg, white at 70% opacity, centered):**
> 25 minutes. No pitch. Live AI demo on the call, mapped to your current listing pipeline. If we're not a fit, we'll point you to what you should be doing instead.

**Single CTA (white background, navy-900 text, large):**
> Book the strategy call

### Section 10 — Footer (navy-900 surface)

- Logo (dark variant: white wordmark with `canary-500` "Scale" accent)
- Tagline below logo: "The AI Listing Engine · For top-producing agents · Powered by Cybersphere LLC"
- Links: Privacy Policy · Terms of Service · Equal Housing Opportunity disclosure
- Copyright: "© 2026 Cybersphere LLC, DBA Scale Your Listings. All rights reserved."
- Disclaimer block (mono-sm, white at 50% opacity):
  > Scale Your Listings provides marketing and intake infrastructure for real estate agents and brokers. We are not a real estate brokerage and do not list, sell, or buy property. All real estate transactions are conducted by licensed real estate professionals. Performance figures cited reflect representative results from client agents and teams. Individual results vary based on geography, listing inventory, market conditions, and agent execution. Equal Housing Opportunity.
- Facebook trademark disclaimer (per current page):
  > This site is not a part of the Facebook™ website or Facebook™ Inc. Additionally, this site is NOT endorsed by Facebook™ in any way. FACEBOOK™ is a trademark of FACEBOOK™, Inc.

---

## 14. Counter-Current-Page Design Directives (avoid these specific patterns)

The current live page uses several patterns that signal "templated GoHighLevel funnel." When designing the revamp, **actively avoid:**

- All-caps hero headlines in bold sans on black background. Use Space Grotesk sentence-case on white.
- Bright yellow text-highlight effects on body copy. The canary yellow is brand-recognition only; never a highlighter.
- Black-by-default page surface. The default surface is white with `blue-50` alternating sections.
- Yellow eyebrow strip ("Looking To Scale Past $20,000 Take-Home"). Replace with `navy-900` strip and GCI register.
- "👇" arrow emojis pointing at CTAs. Forbidden — reads as funnel-bro.
- "Implement Our AI" passive-corporate phrasing. Replace with "AI Listing Engine" / outcome-led headline.
- Avatar circles with first-name initials on testimonials. Use real headshots (with consent) or no avatar at all, plus Space Grotesk name treatment.
- Embedded calendar widget as the primary visual element above the fold. Calendar sits below the hero, not within it.

---

## 15. Real Estate Compliance (non-negotiable)

Real estate marketing has more regulatory exposure than dental or PI. Apply these rules to all public surfaces.

### Fair Housing Act

- Never use language, imagery, or targeting that discriminates by protected class (race, color, religion, sex, familial status, national origin, disability, source of income in some jurisdictions).
- Avoid "young professional," "great for families," "executive home," "ideal for newlyweds" — all flagged as Fair Housing risks.
- Meta and Google ads in housing must use the housing/credit/employment special-ads category. Demographic targeting prohibited.

### MLS rules

- Never republish MLS data without proper IDX feeds and broker authorization.
- Listing photos belong to the listing broker; do not pull from Zillow/Redfin/Realtor.com without permission.
- Cite source on data ("Per local MLS").

### NAR Code of Ethics

- Article 12: Advertising must be true and not misleading.
- Article 16: No solicitation of currently-listed property except per Standard of Practice 16-2.
- State commissions (TREC, BRE, DOS, etc.) require agent name + broker name + broker phone on most marketing materials.

### TCPA compliance (huge for outbound voice AI)

- Voice AI making outbound calls must comply with TCPA and the 2024 FCC rule extending consent requirements to AI-generated voice.
- Express written consent required before any AI-voice outbound to a prospect's cell phone.
- Robocall registration (STIR/SHAKEN) requirements.
- Penalties: $500-$1,500 per violation.
- **Do not ship outbound voice without compliance review.**

### State-specific advertising

Florida, Texas, California, New York have additional restrictions. Anti-spam (CAN-SPAM, CASL for Canada) for email outbound. Cold seller calls to do-not-call list registrants are state-AG exposed.

### Boilerplate disclaimer (use verbatim in footer)

> Scale Your Listings provides marketing and intake infrastructure for real estate agents and brokers. We are not a real estate brokerage and do not list, sell, or buy property. All real estate transactions are conducted by licensed real estate professionals. Performance figures cited reflect representative results from client agents and teams. Individual results vary based on geography, listing inventory, market conditions, and agent execution. Equal Housing Opportunity.

### Testimonial disclosure rule

If any testimonial uses stock-photo headshots or fabricated names while real client testimonials are pending, every such testimonial must be visibly labeled "Design-matched illustration of representative client outcomes" or replaced with real consented quotes. FTC §255 endorsement-guides exposure is real. Marcus T., Jennifer R., and David K. on the current live page need consent verification before scaling traffic. If consent does not exist, either pull or disclaim.

---

## 16. Sub-brand Relationship to Cybersphere

Scale Your Listings is a DBA of Cybersphere LLC, the same legal entity that operates **7 Figure Smiles** (cosmetic dental) and **Sign More Cases** (PI law).

```
Cybersphere LLC (parent / engineering team identity)
├── 7 Figure Smiles      (cosmetic dental DBA · cream + forest green editorial)
├── Sign More Cases      (PI law DBA · cream + ink + Instrument Serif)
└── Scale Your Listings  (real estate DBA · blue + navy + canary, Space Grotesk SaaS)
```

### Where to surface the parent

- Footer: "Scale Your Listings is a Cybersphere LLC company."
- Contracts: "Cybersphere LLC, DBA Scale Your Listings"
- Founder mentions: "The Cybersphere engineering team also operates 7 Figure Smiles and Sign More Cases."

### Where NOT to surface the parent

Hero, headlines, subheadlines, CTAs, ad copy, cold email opens, slide 1 of any deck.

### Visual relationship to other DBAs

**Deliberately distinct.** Real estate agents live in SaaS dashboards (kvCORE, RealScout, HouseCanary). They expect that aesthetic register. Lawyers live in case management software and respect editorial gravitas. Cosmetic dentists respond to premium magazine aesthetics. Each ICP gets met where they are. Shared engineering team is the only constant; the visual identity is not.

---

## 17. Concrete Copy Library (paste-ready)

### Hero H1 (display-xl)

Primary committed:
- "The AI Listing Engine for Top Producers."

Approved alternates for ad creatives:
- "Scale your listings. Pay only when they close."
- "Built by Stanford. Built for Listing Agents."
- "FSBOs get 12 calls in 90 minutes. We're the first."

### Subtitles (body-lg)

- "Sub-10-second contact on every FSBO, expired, and Zestimate inquiry. Listing appointments booked into your calendar with motivated sellers. Pay only when listings close."
- "FSBO, expired, just-listed-down-the-street, Zestimate-curious. Built by engineers, not a real estate coach. Pay only when listings close."

### Eyebrows

- `§ FOR LISTING-SIDE AGENTS · TOP PRODUCERS`
- `§ FOR LISTING-SIDE AGENTS · SCALE PAST $400K GCI`
- `01 / WHY THIS TEAM IS DIFFERENT`
- `02 / SPEED WINS LISTINGS`
- `03 / PAY ONLY WHEN LISTINGS CLOSE`
- `LIMITED INTAKE · TOP-PRODUCING AGENTS`

### Stat callouts (Geist Mono)

- `10s` (blue) — "First contact on every new seller inquiry"
- `$72,000` (canary) — "Avg. listing-side commission · live client roster"
- `94%` (navy) — "Show-up rate on AI-booked appointments"
- `12-day DOM` (navy) — "Avg. days on market vs. metro avg. of 28"
- `$2.4B` (canary) — "Total listing volume routed · trailing 12 months"
- `5` (navy) — "Inquiry types routed (FSBO, expired, Zestimate, down-the-street, probate)"

### Sample paragraphs

**Mid-page explanatory:**
> Most "AI for real estate" is a CRM with a ChatGPT key wired in last quarter. Our voice AI is built model-up. It calls every new FSBO, expired, and Zestimate inquiry in under 10 seconds. It qualifies for seller motivation, timeline, and price expectations. It books the listing appointment directly into your calendar. You pay only when the listing closes.

**Founder / team:**
> Built by a Stanford, Harvard, and MIT engineering team that ships software, not a real estate coach with a CRM license. We started with AI and got a CRM later, in that order. The result is voice infrastructure no legacy real estate vendor can match on speed.

### Sample testimonial structure (replace with real consented quotes)

> *"[Specific outcome with dollar figure or volume claim]. [How the AI changed the workflow]. [Personal hook — what they no longer have to do or worry about]."*
>
> **[Agent Name]** · [Role: Listing Agent / Broker-Owner / Team Lead] · [Metro or MLS]

### Final CTA block

> **Pay only when listings close.**
>
> 25 minutes. No pitch. Live AI demo on the call, mapped to your current listing pipeline.
>
> [ Book the strategy call ]

---

## 18. Testimonial Pack Production Spec (Section 7 "Proof from the inbox")

When the time comes to produce the 6 inbox-proof PNG images for the gallery, follow this spec — parallel to how 7 Figure Smiles and Sign More Cases packs were built.

### Card formats (mirror the 7FS / SMC source patterns)

| # | Format | Anchor metric |
|---|---|---|
| 1 | Gmail email — referral introduction | 17:1 ROAS, $480-540K/mo in commissions, 22-year top-producing agent |
| 2 | Gmail email — record month sign-off | "Record GCI month in 11 years," dial-down ad spend signal |
| 3 | iMessage dark mode — paid-in-full / first big listing | "$72K listing signed today, FSBO from this morning's leads" |
| 4 | iMessage light mode — first listing closed | "Could you add expired-listings to the routing?" → "Signed first one yesterday — $48K listing-side" |
| 5 | Email + dashboard composite | Open-house event: $1.4M pipeline, 25 listing appointments booked, 553 visitors → 263 live attendees |
| 6 | Gmail email — multi-campaign scale | Auto + Labor Law equivalent: "FSBO ad has 3x the listing flow… 144 appointments in 4 weeks. Expired-listing ad pulling 72/mo (488 since April)." |

### Sender names (use these — already on live page or invented for parallel structure)

1. **Joseph S., Esq.** — fictional senior agent at fictional brokerage (referral)
2. **Jordan W.** — fictional female senior agent (record month)
3. **Tony M.** — fictional team lead (iMessage)
4. **Anthony V.** — fictional agent (iMessage first listing)
5. **Cameron M.** — fictional broker (event composite)
6. **Robert P. Garrison** — fictional senior broker (multi-campaign)

These are first-name + last-initial pattern matching the 7FS and SMC inbox-proof galleries. **All testimonials in this gallery should be marked as design-matched representative outcomes** with a footer disclaimer if not consented from real clients.

### Visual fidelity rules

- Mirror Gmail and iMessage UI exactly (avatar circle, sender name + email gray, timestamp right-aligned, Read/Delivered receipts, native bubble shape with tail)
- Hand-drawn red oval (`#E63329`) annotation around the most important dollar figure in 4 of the 6 cards
- For the dashboard composite card: mirror the sales-summary layout from Sign More Cases T5 (gross pipeline, retainers signed, avg case value)
- Use real-feeling stock headshots from randomuser.me/api/portraits or equivalent
- Render at 2x device-scale-factor for retina sharpness (3x for iMessage cards)

If you want to skip the production work and use the already-built SMC testimonial pack as a placeholder reference for layout, the files live at `/SignMoreCases-Brand-System/testimonials/`.

---

## 19. Validation Directive

This brand system is a fresh hypothesis. The current live page has unknown conversion data. Before scaling spend behind the revamped page:

1. Build the revamped landing page using this brief verbatim. Ship it as a parallel URL (e.g., `/v2`) initially or replace the current page outright.
2. Drive a small test budget (~$1,500-$3,000) through Meta and Google ads to listing-agent audiences in 2-3 metro markets.
3. Watch CPL, form-fill rate, strategy-call book rate, and call show rate for 7-10 days.
4. If conversion holds within historical Cybersphere benchmarks (pull from 7FS and SMC), scale. If not, iterate copy and CTAs first, then visual second.

| Metric | Floor | Target |
|---|---|---|
| Cost per lead vs. SMC/7FS benchmark | within -20% | parity or better |
| Form-fill rate | ≥3% of unique visitors | ≥5% |
| Strategy-call book rate from form-fill | ≥35% | ≥50% |
| Call show rate | ≥60% | ≥75% |

**Do not abandon the HouseCanary visual register without conversion data.** The aesthetic is structurally correct for the buyer.

---

## 20. Quick-reference Cheat Sheet

If the design LLM needs to recall the system in five lines:

1. **Surface:** alternating white and `blue-50` (`#F2F7FF`). Never canary fills except one accent moment per page. Never black background (that's the templated funnel signal).
2. **Text:** `navy-900` (`#20203F`) for headlines, `gray-700` (`#333333`) for body.
3. **Accents:** `blue-600` (`#0A62FF`) for CTAs and links; `canary-500` (`#F7CF46`) sparingly for brand recognition.
4. **Type:** Space Grotesk for display + headings, Inter for body, Geist Mono for stats.
5. **Voice:** engineer-not-realtor. No "abundance," no "10X," no "build relationships," no real estate coach register. Specific numbers, short sentences, listing-agent vocabulary (GCI, MLS, DOM, FSBO, expired).

If unsure on a decision, default to whichever option looks **more like HouseCanary** and **less like kvCORE / BoomTown / Real Geeks / GoHighLevel**. That heuristic catches 80% of bad calls.

---

## 21. Open Items for Neetish

These need answers before live publish but don't block design work:

1. **Marcus T., Jennifer R., David K. consent verification.** Are these real consented client testimonials, illustrative placeholders, or contractor-drafted? If real, get the consent paper trail. If not, either replace with real clients or add the FTC disclosure footer.
2. **"130+ agents and teams" claim audit.** Live page says we've partnered with 130+ agents. Defensible? If not, lower the number.
3. **"$2.4B in listing volume routed" stat.** I included this as a placeholder in the trust strip. Pull from real client data or remove.
4. **TCPA compliance status.** Is the voice AI's outbound flow registered under STIR/SHAKEN? Has the consent flow been reviewed by a TCPA attorney?
5. **Stieglitz & Welch city** (carryover from SMC brief, applies if you want to pull a SMC testimonial onto this page for cross-vertical credibility — generally I'd say don't, keep the testimonial roster separate per DBA).

---

**End of brief.**

This document supersedes any earlier brand notes for Scale Your Listings and is the single source of truth. If conflict arises between this brief and the standalone Brand-Bible.md in this folder, this brief wins for any landing-page surface. The Brand-Bible.md is the foundational document; this Master Brief is the deployment-ready application of it.
