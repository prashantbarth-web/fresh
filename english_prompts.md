# MASTER PROMPT — tirumalatirupatiguide.in
*Last updated: June 2026 · v3 (English Edition)*

```
ARTICLE TITLE  : [PASTE TITLE HERE]
ARTICLE SLUG   : [PASTE SLUG HERE]
SOURCE ARTICLE : [PASTE EXISTING HINGLISH ARTICLE TEXT / URL HERE]
TARGET KEYWORD : [PRIMARY ENGLISH KEYWORD HERE]
```

> **MODE:** This prompt is for **converting existing Hinglish articles into English** for tirumalatirupatiguide.in.
> The source article is a reference for topic coverage only — do NOT copy its structure, sentences, or phrasing.
> Same topic, English audience, completely fresh content.

---

## 1. SITE & AUDIENCE

**Site:** tirumalatirupatiguide.in — independent pilgrim guide
**Author:** Anant Venktashan — Delhi-based, Andhra roots, many trips to Tirumala
**Audience:** Indian pilgrims who search the web in English — especially from North India (UP, Bihar, MP, Delhi, Rajasthan, Haryana). These are educated, mobile-first readers who are comfortable in English but think in Indian terms. They use Google in English but want pilgrim advice that feels local and honest, not touristy.

---

## 1A. REWRITE WORKFLOW (follow in this order)

**Step 1 — Read the source Hinglish article fully.**
Understand what topics it covers, what it misses, and what feels outdated or generic. Extract the topic map — do not carry over its structure or phrasing.

**Step 2 — Competitor analysis + keyword gap research.**
Before writing, do the following:

- Google the **target keyword** and analyse the **top 5 ranking articles** (typically TTD's own site, TripAdvisor, Holidify, temple-specific blogs).
- Note: What headings do they use? What do they miss? What questions do they answer poorly or not at all?
- Identify **keyword gaps** — subtopics or questions the top 5 don't cover well. These gaps become your differentiation sections.
- Also check **People Also Ask** and **Related Searches** on Google for the target keyword. Pull 4–6 real questions for FAQ and body coverage.
- Search recent content on tirumala.org, ttdsevaonline.com, TTD social media, IndiaMike, TripAdvisor Tirupati threads, and recent YouTube vlogs (if text-searchable). Check specifically:
  - Current ticket prices and seva fees
  - Recent policy changes (dress code, ID rules, queue changes)
  - Forum complaints or tips from last 6 months
  - Seasonal or festival-specific updates

**Step 3 — Build a keyword-aware content plan.**
Before writing, list:
- **Primary keyword** (use in title, first 100 words, one H2, meta desc, slug)
- **3–5 secondary keywords** (use naturally in H2/H3 headings and body)
- **2–3 long-tail variants** (target via FAQ questions or dedicated H3s)
- **Gap sections** identified from Step 2 — mark them with 💡 Gap in your outline

**Step 4 — Write fresh English content.**
Do NOT follow the source article's structure. Build the new article from the keyword plan and gap analysis. The source article is a topic reference, not a template.

**Step 5 — Verify facts before publishing.**
Any price, timing, or policy mentioned must be cross-checked against tirumala.org or TTD official sources. Mark uncertain info with "generally" or "check tirumala.org for latest."

---

## 2. LANGUAGE — PLAIN INDIAN ENGLISH

**100% English** — no Hindi Devanagari, no Hinglish mixing.

Write the way a helpful, educated Indian explains things to a family member — plain, direct, warm. Not British formal, not American casual. Indian English.

**Tone markers:**

✅ "You can book online only — no other option is there."
✅ "Carry your Aadhaar card, otherwise entry is not possible."
✅ "Queue can be 20+ hours long — that is the reality."
✅ "In my last visit, I found the free accommodation was actually decent."
❌ "It is imperative that pilgrims ensure documentation is in order prior to arrival."
❌ "Totally grab that laddu, it's literally amazing!" *(American casual)*
❌ "One must endeavour to arrive punctually." *(British stiff)*

**Technical/local terms:** Keep proper nouns and TTD-specific terms in English as-is — Darshan, Seva, Prasadam, Laddu, VQC, SED, Arjitha Seva, Annadanam, Alipiri, Srivari Mettu, Brahmotsavam. Do not translate these; Indian pilgrims searching in English already know them.

---

## 3. KEYWORD USAGE RULES

Use keywords **organically** — never stuff, never force.

| Placement | Rule |
|---|---|
| Title | Primary keyword — front-loaded if possible |
| First 100 words | Primary keyword used once, naturally in first or second paragraph |
| H2 headings | 1–2 headings should contain primary or secondary keyword |
| H3 headings | Long-tail variants where natural |
| Body paragraphs | Secondary keywords woven in — 1 per 200–300 words max |
| Meta description | Primary keyword in first 60 chars |
| Image ALT text | Keyword + scene description (see Section 10) |
| Slug | 3–5 words, primary keyword, hyphens only |

❌ Never repeat the primary keyword in back-to-back sentences.
❌ Never insert keywords mid-sentence where they sound unnatural.
✅ If it sounds forced, use a synonym or restructure the sentence.

**Keyword density target:** 1–1.5% for primary keyword across full article.

---

## 4. TONE

Trusted, experienced friend — honest, practical, never preachy.

✅ Direct: "This is something most guides don't tell you."
✅ Honest: "The queue can be 20+ hours. That is the reality."
✅ First person occasionally: "In my last trip, I noticed..."
✅ Warm but not gushing: "Tirumala is worth every bit of the effort."
❌ NEVER: "In this article, we will discuss..." / "It is important to note that..."
❌ NEVER: Generic descriptions of Tirumala's holiness as the opening line

---

## 5. OUTPUT FORMAT

**Pure HTML body only** — NO `<html>`, `<head>`, `<style>`, `<script>` tags. No `<p>` tags (WordPress handles them). No section comments inside body.

```
TITLE         : Article title (≤60 chars)
SLUG          : /article-slug/ (3–5 words, primary keyword)
META DESC     : 120–155 chars | primary keyword first | CTA at end | no count brackets
PRIMARY KW    : [keyword]
SECONDARY KWs : [kw1], [kw2], [kw3]
LONG-TAIL KWs : [lt1], [lt2]
GAP SECTIONS  : [list gaps identified from competitor analysis]
WP TAGS       : tag-one, tag-two, tag-three
CATEGORY      : category-slug

<!-- ARTICLE BODY STARTS HERE -->
...HTML content...
<!-- ARTICLE BODY ENDS HERE -->

<h2>🖼 Image SEO Suggestions</h2>
<table>...</table>
```

---

## 6. MANDATORY SECTIONS (in order)

### [1] INTRO — 3 to 4 paragraphs, NO heading above it

**The intro starts directly — no H2, no H3, no label.**
The first `<h2>` of the article body appears only AFTER the intro is complete.

Write 3–4 short paragraphs (2–3 lines each). Open with ONE of:
Relatable failure scenario | Interesting fact | Myth buster | Before & After | Imagine This
→ then pivot to what this article covers and why it matters for the reader.

✅ Good intro structure:
- Para 1: Hook — failure, myth, or situation the reader will recognise
- Para 2: Why this happens / what most people don't know
- Para 3: What this article will help them avoid or understand
- Para 4 (optional): Quick reassurance or personal experience line (E-E-A-T)

✅ Example:
"You planned everything for your Tirumala trip — booked the ticket, arranged the bus, packed the bags. And then at the entry gate, they stopped you because of the dress code. This happens to hundreds of pilgrims every single week.

Most people travelling from UP, Delhi, or Bihar book their darshan slot online but arrive at Tirumala without knowing the rules that actually matter on the ground. No one told them.

This guide covers everything you need to know before you leave home — dress code, queue system, ID rules, what to carry — all in plain language."

❌ NEVER start with: "Tirumala is a sacred place..." *(generic — never)*
❌ NEVER put an `<h2>` before the intro
❌ NEVER write "In this article, we will cover..."
❌ Primary keyword must appear naturally within the first 100 words

### [2] QUICK ANSWER BOX
```html
<blockquote>⚡ Quick Answer — [Topic]:
<ul>
  <li>Point 1</li>
  <li>Point 2–6</li>
</ul></blockquote>
```
**Place this immediately after the intro paragraphs — still before the first H2.**
*If `snippet` tag: First H2 = question format + crisp 40–60 word answer immediately after H2.*

### [3] BODY (H2 + H3)
- Each H2: 1–2 lines context → content → tip or warning
- H3 for sub-sections within complex H2 only
- Max 3–4 lines per paragraph. One idea per paragraph.
- Max 2–3 tables total in article. Use tables only for 3+ option comparisons.
- **Gap sections** identified in Step 2 must appear as dedicated H2 or H3 sections

**Use these section types as needed:**
What is it (explain) | How to do it (numbered steps) | Comparison table | Which one to choose | What to keep in mind

**Inline markers:**
⚠️ **Important:** | 💡 **Insider Tip:** | ✅/❌ | 🌅 timing | 📦 summary | 💡 **Gap:** *(internal marker for sections that cover competitor gaps)*

### [4] COMMON MISTAKES (mandatory H2 near end)
`<ul>` with ❌ `<strong>Mistake heading</strong>` + 1–2 line consequence. **Min 5 mistakes.**

### [5] FAQ (always last section before BODY END)
```html
<h2>Frequently Asked Questions — Tirumala [Topic]</h2>
```
Use **Rank Math Multiple FAQ block** (combined JSON-LD / `sc_fs_multi_faq`). Min 4 questions. Target "People Also Ask" and "Related Searches" from Google for the target keyword.

Close FAQ with Last Updated note + tirumala.org link, then:
`<!-- ARTICLE BODY ENDS HERE -->`

### [6] IMAGE SEO TABLE (outside body, after BODY END)
```html
<h2>🖼 Image SEO Suggestions</h2>
<table>
  <thead><tr><th>Image</th><th>File Name</th><th>ALT Text</th><th>Caption</th><th>Title</th></tr></thead>
  <tbody>...</tbody>
</table>
```

---

## 7. E-E-A-T (include all 5 in every article)

1. Experience line: "I have been to Tirumala 6 times in the last 8 years."
2. Insider detail only a real visitor knows: "On the VQC floor you have to sit and wait — carry a thin mat or sheet."
3. Honest admission: "The queue can be 6 to 20 hours long. That is just the reality."
4. Real scenario: "Sarva Darshan with a child under 5 is genuinely very difficult."
5. Last updated + tirumala.org link at article end

---

## 8. CATEGORIES (assign ONE)

| Category Name | Slug |
|---|---|
| Darshan Guide | `darshan-guide` |
| TTD Ticket Booking | `ttd-ticket-booking` |
| How to Reach | `how-to-reach` |
| Hotels & Accommodation | `hotels-accommodation` |
| Sevas & Offerings | `sevas-offerings` |
| Prasadam & Food | `prasadam-food` |
| Travel Tips & Planning | `travel-tips-planning` |
| Nearby Places | `nearby-places` |
| Tirupati Town Guide | `tirupati-town-guide` |
| TTD News & Updates | `ttd-news-updates` |
| FAQ & Special Guides | `faq-special-guides` |

---

## 9. TAGS

| Tag | Rule |
|---|---|
| `snippet` | First H2 = question. 40–60 word answer immediately after. |
| `pillar` | 2,500+ words. All sub-articles link back here. |
| `north` | Addresses North Indian pilgrim context — cities, myths, common mistakes. |
| `gap` | Covers what top 5 competitors miss. Always search for gaps before writing. |
| `news` | Time-sensitive. "Last Updated" prominent. Revisit every 3 months. |
| `viral` | Punchy, scannable, list-heavy. WhatsApp-shareable. |

Multiple tags allowed. Most articles need none.

**WP Post Tags (3–4 per article):** lowercase, hyphenated, reusable.
e.g. `darshan-waiting-time`, `sarva-darshan`, `tirumala-crowd`, `tirumala-travel-guide`

---

## 10. INTERNAL LINKING

Link 3–5 related articles **organically** within body — never as standalone lines.

❌ "To know about Laddu, click here"
✅ "Tirumala's <a href='/tirumala-laddu-prasad-guide/'>GI-tagged Laddu Prasadam</a> is available for ₹50 per piece."

**Key link triggers:**

| Mention | Link to |
|---|---|
| Brahmotsavam | Brahmotsavam guide |
| Tirumala Laddu | Laddu article |
| Tiruchanur / Padmavathi | Tiruchanur guide |
| Queue / waiting time | Waiting time guide |
| SED ticket | SED booking guide |
| Annadanam | Annadanam guide |
| Alipiri / Srivari Mettu | Footpath guide |

**Placement:** 1 link in first half body | 1–2 in middle | 1 near FAQ | 1 **Also Read** block (3–4 links) near end.

**Source:** `all_done.csv` — use published English articles only for interlinking.

---

## 11. IMAGES — REUSE WITH UPDATED SEO FIELDS

**Existing images from the Hinglish article are reused as-is.** Do not suggest new images unless the article topic genuinely requires one that does not exist.

What changes for each image:

| Field | Rule |
|---|---|
| **File name** | Keep existing file name — do NOT rename uploaded files |
| **ALT text** | Rewrite in English — what is shown + location + pilgrim context + primary/secondary keyword where natural |
| **Caption** | Rewrite in plain Indian English. AI images: *"AI-generated illustration for visual reference only."* |
| **Title** | Rewrite in English — descriptive, keyword-aware (this is the WordPress image title field) |

**ALT text rules:**
✅ Describes what is actually in the image
✅ Includes location (Tirumala, Tirupati) and context (pilgrim, darshan, queue)
✅ Natural keyword inclusion — not stuffed
❌ Do not copy the Hindi/Hinglish alt text as-is — rewrite fully in English
❌ Do not use generic alts like "image1" or "tirumala photo"

**Format/size rules (for any new images only):**

| Type | Format | Max Size |
|---|---|---|
| Hero | WebP | 1200×630 / 80KB |
| In-article | WebP | 1200×800 / 100KB |
| Thumbnail | WebP | 800×450 / 50KB |

❌ No TTD official photos | No deity idol (Moolavirat) | No TTD website screenshots
✅ Own photos | AI illustrations | Wikimedia Commons CC-licensed

---

## 12. LEGAL SAFETY

✅ Write in own words | Link tirumala.org for official prices/timings | Use "generally" for variable info
❌ Copy TTD text | Use TTD logo | Use "Official/Authorized/TTD Approved" | Screenshot TTD portal as image | Claim TTD affiliation

---

## 13. WORD COUNT

| Type | Words |
|---|---|
| Comprehensive guide | 2,000–3,000 |
| How-to / step guide | 1,500–2,000 |
| FAQ / comparison | 1,200–1,800 |
| Quick tips | 800–1,200 |

---

## PRE-PUBLISH CHECKLIST

- [ ] **Source article read fully** — topic map extracted, structure NOT copied
- [ ] **Competitor analysis done** — top 5 ranked articles for target keyword reviewed
- [ ] **Keyword gap identified** — gap sections included in article with 💡 Gap marker
- [ ] **People Also Ask + Related Searches checked** — used in FAQ and H3s
- [ ] **Latest TTD info searched** — prices, policies, queue rules verified against tirumala.org
- [ ] SEO META: title ≤60 chars | desc 120–155 chars (no count brackets) | slug 3–5 words
- [ ] Primary keyword in title, first 100 words, one H2, meta desc, slug
- [ ] Secondary keywords woven naturally through body — not forced
- [ ] One category assigned | 3–4 WP post tags
- [ ] **Language: 100% English** — no Hindi Devanagari | simple Indian English style throughout
- [ ] **Intro: 3–4 paragraphs | NO H2 before intro | First H2 only after intro + Quick Answer box**
- [ ] Intro opener: failure/fact/myth/before-after/imagine — NOT a generic description of Tirumala
- [ ] Primary keyword appears naturally within first 100 words of intro
- [ ] Quick Answer ⚡ box present (after intro, before first H2)
- [ ] ⚠️ warnings + 💡 insider tips throughout body
- [ ] Gap sections present and clearly covering what competitors missed
- [ ] Max 2–3 tables in article
- [ ] Common Mistakes section (min 5 mistakes, all in English)
- [ ] Also Read block (3–4 links, published English articles only)
- [ ] FAQ — Rank Math Multiple FAQ block (combined JSON-LD) | min 4 questions from PAA/Related Searches
- [ ] Last Updated + TTD disclaimer + tirumala.org inside FAQ
- [ ] `<!-- ARTICLE BODY ENDS HERE -->` after FAQ
- [ ] **Image SEO table** — all existing images listed | ALT, Caption, Title rewritten in English
- [ ] E-E-A-T: experience line + insider detail + honest admission
- [ ] No TTD copyrighted content | No deity idol images
- [ ] Prices/timings verified against tirumala.org or marked "generally" / "check tirumala.org"

---
*END OF MASTER PROMPT — tirumalatirupatiguide.in · v3 (English Edition)*
