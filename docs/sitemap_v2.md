# Sitemap V2 — Prestige Architecture

> Design system: **Porsche 997 Minimalism** — Swiss Grid, monochrome palette with one accent color,
> oversized typography, negative space as a trust signal. Every element earns its pixel.
>
> AIO strategy: All slugs are long-tail, question-shaped or outcome-shaped for AI Overview extraction.

---

## Navigation Model: Two-Track

The site serves two distinct visitors with fundamentally different intent.
Both tracks share a common header and footer, but the **primary CTA differs per track**.

```
+-------------------------------------------------------------------+
|  SCOTT BALES              [Track Toggle]         [Contact / Book]  |
+-------------------------------------------------------------------+
|                                                                    |
|  Track A: THE BUREAU HUB         Track B: THE EXECUTIVE EXPERIENCE |
|  (Event planners, bureau agents)  (C-Suite, conference chairs)      |
|                                                                    |
+-------------------------------------------------------------------+
```

### Shared Elements (Every Page)

| Element              | Purpose                                        |
|----------------------|------------------------------------------------|
| Proof bar            | Rotating client logos: Microsoft, Google, Visa, AIA, Standard Chartered, Vodafone |
| Single-line proof    | One rotating testimonial per page load         |
| Footer CTA           | "Have a question about Isaac and Esther?" + calendar link |
| Schema.org markup    | `SpeakerProfile`, `Event`, `Review` structured data on every page |

---

## Track A — The Bureau Hub

**Audience:** Speaker bureau agents, event coordinators, internal L&D teams
**Intent:** "I need assets and specs to pitch Scott to my client in 20 minutes"
**Tone:** Technical precision. Clean. Fast.

### A1. Bureau Home

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/bureau`                                                 |
| **Purpose**  | One-page spec sheet — everything a bureau needs, zero scrolling |
| **Sections** | Headshot grid (3 crops) / One-paragraph bio (150 words) / Topic tiles / Fee guidance / Tech rider / Availability calendar widget |
| **CTA**      | "Download Speaker Kit" (PDF) + "Hold a Date"             |

### A2. Speaker Kit (PDF Download)

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/bureau/speaker-kit-scott-bales`                         |
| **Purpose**  | Gated PDF: hi-res headshots, 50/150/300-word bios, topic one-sheets, stage photos, intro scripts, AV requirements |
| **AIO Note** | Landing page text targets: "scott bales speaker kit download" |

### A3. Topic One-Sheets

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/bureau/topics`                                          |
| **Purpose**  | Printable one-page summaries per keynote — title, 100-word abstract, 3 outcomes, audience fit, duration, format options |
| **Children** | One expandable card per topic (no sub-pages — keeps bureau UX flat) |

### A4. Media & Assets

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/bureau/media-assets-downloads`                          |
| **Purpose**  | Hi-res photos (editorial + stage), logos, intro scripts, social cards |
| **Format**   | Grid of downloadable assets with preview thumbnails       |

---

## Track B — The Executive Experience

**Audience:** C-Suite leaders, conference chairs, board members, heads of innovation
**Intent:** "Will this person change how my leadership team thinks?"
**Tone:** Commanding. Narrative. Inevitable.

### B1. Homepage (Dual-Native Hero)

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/`                                                       |
| **Meta Title** | `Isaac Defined Your Today. Esther Will Define Your Survival. | Scott Bales` |
| **Purpose**  | Dual provocation. No bio. No list of services. The generational pincer in one viewport. |
| **Layout**   | Full-viewport hero with headline + subline. Scroll reveals four content blocks: The Shift (Isaac) / The Outcome (Esther) / The Evidence (proof wall) / The Invitation (book) |

#### Hero Options (see Section 5 below)

#### Below-the-fold Sections

| Section               | Slug Anchor    | Content                                              |
|-----------------------|---------------|------------------------------------------------------|
| The Shift             | `#isaac`       | 2-sentence Isaac thesis + "Meet Isaac" link to `/isaac-the-consumer-who-will-replace-your-customer` |
| The Outcome           | `#esther`      | 2-sentence Esther thesis + "Meet Esther" link to `/esther-and-the-agentic-future` |
| The Evidence          | `#proof`       | 6 named testimonials in a 3x2 Swiss Grid. Company logo above quote. |
| The Invitation        | `#book`        | "One conversation. No pitch deck." + calendar embed  |

### B2. Isaac — The Shift

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/isaac-the-consumer-who-will-replace-your-customer`      |
| **Meta Title** | `Isaac: The Consumer Who Will Replace Your Customer | Scott Bales` |
| **Purpose**  | The flagship narrative page. This is the page a CEO reads at 11pm on their phone. |
| **Layout**   | Long-scroll editorial. No sidebar. Generous whitespace.   |
| **Arc**      |                                                           |
| 1. Cold open | "Isaac is 19. He has never walked into a bank."          |
| 2. The shift | What Isaac expects vs. what your org delivers            |
| 3. The origin | Jenson — "My son taught me that technology's job is to include, not exclude. Isaac is what happens when inclusion scales." |
| 4. The framework | The Isaac Readiness Model (proprietary) — Transparency, Autonomy, Immediacy, Inclusion |
| 5. The bridge | "Isaac was the warning. Then November 30, 2022 happened." — link to Esther page |
| **CTA**      | "Bring Isaac and Esther to your leadership team" + booking link |

### B2b. Esther — The Outcome

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/esther-and-the-agentic-future`                          |
| **Meta Title** | `Esther and the Agentic Future: The AI Native Who Will Never Know Your Brand | Scott Bales` |
| **Purpose**  | The second thesis page. If Isaac is the shift your org is absorbing, Esther is the outcome it is not prepared for. This page completes the pincer. |
| **Layout**   | Long-scroll editorial. Same treatment as Isaac page. No sidebar. The two pages are a diptych — same structure, escalating stakes. |
| **Arc**      |                                                           |
| 1. Cold open | "Esther was born on November 30, 2022. So was ChatGPT. She will not remember a world before generative AI." |
| 2. The native | What "AI native" means at the identity level — AI is not a tool she adopted, it is the substrate she formed on. Language, learning, play, commerce — all mediated by models from birth. |
| 3. The agentic shift | Esther does not interact with your product. Her agent does. She does not compare. Her model does. No loyalty. No memory of your brand promise. |
| 4. The pincer | Isaac is still here. He is your customer today, your mid-career hire, your most demanding critic. Esther is behind him — and her expectations make his look quaint. |
| 5. The framework update | The Human Algorithm rewritten: Esther's four criteria — Intelligence (AI as a fundamental right, not a feature), Delegation (agent-first interaction), Anticipation (the answer before the question), Inclusion (inherited from Jenson — if it excludes, her AI will refuse to route her there) |
| 6. The close | "Isaac chose to leave. Esther will never arrive." |
| **CTA**      | "Your competitor's founder was born the same day as the technology you are still piloting." + booking link |

### B3. Keynotes

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/keynotes`                                               |
| **Meta Title** | `Keynotes That Prepare Leaders for Isaac and Esther | Scott Bales` |
| **Purpose**  | Topic pages reframed through the Isaac/Esther dual-native lens |
| **Layout**   | Card grid, each card links to a deep-dive sub-page        |

#### Keynote Sub-Pages

| Keynote                     | Slug                                              | Dual-Native Frame                            |
|-----------------------------|---------------------------------------------------|----------------------------------------------|
| Are You Ready for Isaac?    | `/keynotes/isaac-consumer-future`                  | The signature talk. Isaac defined. The shift your org is still absorbing. |
| Are You Ready for Esther?   | `/keynotes/esther-ai-native-agentic-future`        | The new signature talk. Esther defined. The outcome your org has not prepared for. |
| Recode Leadership           | `/keynotes/recode-leadership-ai-transformation`    | "Isaac distrusts your leaders. Esther's agent will never meet them." |
| Innovation Wars             | `/keynotes/innovation-wars-corporate-strategy`     | "Isaac doesn't care about your innovation lab. Esther's agent already built one." |
| The Future of Work          | `/keynotes/future-of-work-ai-workforce`            | "Isaac is your next employee. Esther is your next employee's AI co-pilot." |
| Smart Cities                | `/keynotes/smart-cities-digital-citizens`           | "Isaac expects smart cities. Esther expects cities that anticipate." |
| Empowering Potential        | `/keynotes/empowering-potential-technology-inclusion` | "Jenson is why Isaac matters. Jenson is why Esther's AI will refuse to exclude." |

### B4. The Origin — Jenson + The Human Algorithm

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/origin-story-jenson-human-algorithm`                    |
| **Meta Title** | `Why I Do This: Jenson, Isaac, Esther and The Human Algorithm | Scott Bales` |
| **Purpose**  | The emotional center of the site. Converts "interesting speaker" to "must-book speaker." The three-body narrative: Jenson (origin) -> Isaac (shift) -> Esther (outcome). |
| **Layout**   | Photo-essay style. Personal images. Long-form narrative.  |
| **Arc**      |                                                           |
| 1. The fraud moment | "The moment I realised I was a fraud" — The Human Algorithm Part 1 |
| 2. Jenson    | Raising a child with special needs while advising Fortune 500s on innovation |
| 3. The turn  | "I was telling boardrooms to put humans first while the most important human in my life was showing me I didn't know what that meant" |
| 4. The front lines | 20 years at WING, Visa, Moven — "Who is this not working for?" |
| 5. Isaac     | The mobile/social native. The shift. The consumer who expects inclusion. |
| 6. Esther    | Born Nov 30, 2022. The AI/agentic native. The outcome. AI as a fundamental right, not a feature. |
| 7. The pincer | Isaac is still here demanding more. Esther is behind him making his demands look quaint. |
| **CTA**      | "This is why every keynote I deliver starts with a human, not a technology." |

### B5. Proof

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/proof-results-client-testimonials`                      |
| **Meta Title** | `What Happens After Scott Bales Speaks | Client Results` |
| **Purpose**  | Social proof page organized by authority tier, not chronology |
| **Layout**   | Three tiers in Swiss Grid                                 |

| Tier                    | Content                                              |
|-------------------------|------------------------------------------------------|
| **Tier 1: The Names**   | Microsoft, Google, Visa, Brett King — named attribution, large format |
| **Tier 2: The Outcomes** | Vodafone, AIA, Standard Chartered, Cognizant — event context + quote |
| **Tier 3: The Pattern**  | Remaining quotes — presented as a density wall showing volume of proof |

### B6. About

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/about-scott-bales`                                      |
| **Meta Title** | `About Scott Bales | From Moven to Isaac to Esther`    |
| **Purpose**  | Career narrative, not a CV. The reader should finish thinking "this person has *earned* this perspective." |
| **Layout**   | Timeline-as-narrative, not a list of roles               |
| **Arc**      | WING Money (emerging markets) -> Fundamo/Visa (global scale) -> Moven (first digital bank) -> Innovation Labs Asia (advisor) -> Isaac (the shift) -> Esther (the outcome) |
| **What it is NOT** | A list of seven titles. No "Guru." No "Warrior."   |

### B7. Publications

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/publications-books-scott-bales`                         |
| **Purpose**  | Books as credentials, not products. Brief description + "how this shaped the Isaac/Esther thesis" for each. |

### B8. Insights (Blog)

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/insights`                                               |
| **Children** | `/insights/{post-slug}` (migrated from current `/post/` URLs with 301 redirects) |
| **Purpose**  | Thought leadership. AI-focused content. Each post ends with an Isaac/Esther-lens takeaway. |
| **Categories** | AI Leadership / Future Consumer / The Agentic Future / Smart Cities / The Human Algorithm |

### B9. Book Scott

| Field        | Value                                                     |
|--------------|----------------------------------------------------------|
| **Slug**     | `/book-scott-bales-keynote-speaker`                       |
| **Meta Title** | `Book Scott Bales | Keynote Speaker Inquiry`           |
| **Purpose**  | Single-page booking form. Not a "contact" page — a *commitment* page. |
| **Layout**   | Left column: "One conversation. No pitch deck. No PDF will tell you what Scott will do for *your* audience." / Right column: Form (name, org, event date, audience size, topic interest dropdown) |

---

## Section 5: Dual-Native Hero — Four Headline Options

All four options eliminate generic titles. No "Futurist." No "Guru." No "Digital Strategist."
The hero is a full-viewport provocation. Options A-C retain Isaac-first framing.
**Option D is the recommended Dual-Native hero** — it introduces the pincer in the first viewport.

---

### Option A — The Question (Isaac-First)

```
ARE YOU READY FOR ISAAC?

He's 19. He's never satisficed. And he's about to become
your most important customer, employee, and competitor.

                                            [Meet Isaac]
```

**Subtext logic:** Three words — customer, employee, competitor — position Isaac as an
omnidirectional threat. This hero works for any industry because every C-Suite leader
has all three. The verb "satisficed" is a deliberate provocation: it signals academic
depth (Herbert Simon's satisficing theory) without explaining it, rewarding the
sophisticated buyer and filtering out the wrong audience.

---

### Option B — The Countdown (Isaac-First)

```
YOUR CUSTOMERS HAVE 18 MONTHS.
THEN ISAAC ARRIVES.

20 years building the future of banking, AI, and cities
taught me one thing: the next consumer won't adapt to you.

                                        [The Isaac Thesis]
```

**Subtext logic:** The urgency frame ("18 months") creates a ticking clock that
justifies a $20k booking *now* rather than next quarter. The single credential
line — "20 years building" — replaces the seven-title stack with one earned statement.
The closer — "won't adapt to you" — flips the traditional consulting posture from
"we'll help you adapt" to "you're the one who's behind."

---

### Option C — The Declaration (Isaac-First)

```
I DON'T PREDICT THE FUTURE.
I BUILT THE FIRST DIGITAL BANK, WROTE THE BOOK,
AND NAMED THE CONSUMER WHO'LL REPLACE YOURS.

His name is Isaac.

                                        [Are You Ready?]
```

**Subtext logic:** Three verbs — built, wrote, named — replace all titles with
proof-of-work. "The first digital bank" (Moven) is a verifiable, singular claim
no other speaker can make. "Wrote the book" is both literal (Mobile Ready,
Innovation Wars) and idiomatic. "Named the consumer" positions Isaac as a
proprietary concept, not a generic trend. The final line — "His name is Isaac" —
lands like a closing argument.

---

### Option D — The Generational Pincer (Dual-Native) **[RECOMMENDED]**

```
ISAAC DEFINED YOUR TODAY.
ESTHER WILL DEFINE YOUR SURVIVAL.

One was born with a screen in his hand.
The other was born the same day as ChatGPT.
Your organization is caught between both.

                                    [Meet the Pincer]
```

**Subtext logic:** This is the only hero that delivers the full thesis in one viewport.
Two names. Two sentences. The reader immediately understands there are two forces,
not one — and that they are caught in between. "Defined your today" positions Isaac
as settled fact, not a future prediction. "Define your survival" makes Esther
existential, not aspirational. The subtext — "born with a screen" / "born the same
day as ChatGPT" — gives each persona a single, concrete origin that needs no
explanation. The final line — "Your organization is caught between both" — is the
provocation. It does not say "might be" or "could be." It says *is.* The CTA
"Meet the Pincer" introduces proprietary language that positions the framework
as something only Scott delivers.

**Why this is the recommended option:** At the $20k tier, the buyer is not
looking for a speaker who covers one trend. They are looking for someone who
sees the structural relationship between trends. Isaac alone is a good talk.
Isaac + Esther is a thesis. A thesis commands a fee. A talk gets compared to
other talks.

---

## Section 6: URL Architecture — AIO Optimization

| Page                    | Slug                                              | Target AIO Query                              |
|-------------------------|---------------------------------------------------|-----------------------------------------------|
| Homepage                | `/`                                               | "scott bales speaker"                         |
| Isaac — The Shift       | `/isaac-the-consumer-who-will-replace-your-customer` | "who is the future consumer isaac"           |
| Esther — The Outcome    | `/esther-and-the-agentic-future`                  | "ai native consumer esther agentic future"    |
| Origin Story            | `/origin-story-jenson-human-algorithm`            | "scott bales human algorithm jenson"          |
| Keynotes Hub            | `/keynotes`                                       | "scott bales keynote topics"                  |
| Isaac Keynote           | `/keynotes/isaac-consumer-future`                 | "future consumer keynote speaker"             |
| Esther Keynote          | `/keynotes/esther-ai-native-agentic-future`       | "ai native keynote speaker agentic"           |
| Recode Leadership       | `/keynotes/recode-leadership-ai-transformation`   | "leadership keynote ai transformation"        |
| Innovation Wars         | `/keynotes/innovation-wars-corporate-strategy`    | "corporate innovation keynote speaker"        |
| Future of Work          | `/keynotes/future-of-work-ai-workforce`           | "future of work ai keynote"                   |
| Smart Cities            | `/keynotes/smart-cities-digital-citizens`         | "smart cities keynote speaker"                |
| Empowering Potential    | `/keynotes/empowering-potential-technology-inclusion` | "technology inclusion accessibility keynote" |
| Proof                   | `/proof-results-client-testimonials`              | "scott bales reviews testimonials"            |
| About                   | `/about-scott-bales`                              | "who is scott bales speaker"                  |
| Publications            | `/publications-books-scott-bales`                 | "scott bales books mobile ready"              |
| Insights                | `/insights`                                       | "scott bales blog ai leadership"              |
| Book                    | `/book-scott-bales-keynote-speaker`               | "book scott bales speaker"                    |
| Bureau Home             | `/bureau`                                         | "scott bales speaker bureau kit"              |
| Speaker Kit             | `/bureau/speaker-kit-scott-bales`                 | "scott bales speaker kit download"            |
| Bureau Topics           | `/bureau/topics`                                  | "scott bales speaking topics"                 |
| Media Assets            | `/bureau/media-assets-downloads`                  | "scott bales headshot press photos"           |

### Redirect Map (Old Wix -> New)

```
301  /about          ->  /about-scott-bales
301  /publications   ->  /publications-books-scott-bales
301  /partner        ->  /book-scott-bales-keynote-speaker
301  /blog           ->  /insights
301  /post/*         ->  /insights/*  (pattern match)
```

---

## Section 7: Technical Guardrails

### Design System — Porsche 997 Minimalism

| Principle              | Rule                                                      |
|------------------------|----------------------------------------------------------|
| Grid                   | 12-column Swiss Grid. Content never exceeds 8 columns on desktop. |
| Typography             | One serif for headlines (editorial authority). One sans-serif for body (clarity). No third typeface. |
| Color                  | Monochrome base (black, white, 2 grays). One accent color only — used exclusively for CTAs, the Isaac name, and the Esther name. Both personas share the accent to signal they are two expressions of the same thesis. |
| Photography            | Full-bleed, desaturated, high-contrast. Stage shots and editorial portraits only. No stock. No clip art. No icons. |
| Whitespace             | Minimum 120px vertical padding between sections. Whitespace is the most expensive thing on the page — use it to signal value. |
| Animation              | None on first load. Subtle fade-in on scroll only. No parallax. No particle effects. No sliders. |
| Mobile                 | Single column. Hero text scales to fill viewport width. Proof bar becomes swipeable. |
| Load target            | < 2s LCP. No Wix. Static-first (Next.js/Astro SSG).     |
