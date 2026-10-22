# Digital Resource: Email Design Process (Cooling Drip and Above the Scroll)

Reference for Claude Code. It describes how DR's marketing emails are designed: the Cooling Drip in Canva (sections 1–8, based on an audit of **Projects > Emails > Cooling Drip Emails**, 20 designs, audited 22 Oct 2026) and the Above the Scroll newsletter in Figma from 2027 (section 9). Use it to design new emails, rebuild existing ones, or check work against house standards.

> **Confirmed** means it was read directly from the Canva files. **Assumption** means it should be checked with the team before you rely on it.

---

## 1. What the Cooling Drip is

- A numbered series of **18 nurture emails** (#1–#18) for "cooling" contacts: leads and past prospects who aren't ready to buy yet. The goal is to keep DR top of mind and get the reader to book a **free consultation / strategy review**.
- Each email takes **one marketing topic** (SEO, content, social and multimedia, email, ads, website compliance, retention, CRM, full-service), teaches 3–4 quick points, gives one piece of proof (a stat or a client story), then asks for the consultation.
- Audience: small and mid-sized business owners with limited marketing knowledge. Write for a busy owner, not a marketer.

## 2. Canva file conventions (as they exist today)

| Convention | Current practice | Standard to follow going forward |
|---|---|---|
| Location | `Projects / Emails / Cooling Drip Emails` | Same |
| File name | `Cooling Drip Email #N — Topic` (em dash). #17 and #18 have no topic, #11 uses a hyphen. | Always `Cooling Drip Email #NN — Topic` with a two-digit number |
| Canvas width | **650 px** on every email | Keep 650 px |
| Canvas height | Varies: 1800, 3000 (most), 4000 and ~4200 px. Several have 400–1,000 px of empty white space at the bottom (#9, #11, #15, #16). | Resize the canvas to fit the content (Canva: Resize, or trim to the last element plus 40 px) |
| Pages in a file | Page 1 is the current version. The other pages hold A/B variants (for example a "Take the Quiz" version), older drafts that are **hidden**, and asset sheets (icons, a phone mockup). | Page 1 is always the live version. Name the other pages in their page notes (`VARIANT – quiz CTA`, `ARCHIVE – 2024 grey`, `ASSETS`). Keep asset sheets hidden. |
| Non-email files | `z- Archived - aniamtedThe Future of Marketing` and `Copy of aniamted…` are 1500 px animated "DR 2.0 is here" banners, not emails | Move them to an Assets folder and fix the typo "aniamted" |

## 3. Anatomy of a DR email (current house template)

Seen in the 2025–26 refresh (#1, #3, #10, #16, #17, #18 and others). Build sections in this order, top to bottom:

1. **Header bar.** The DR primary logo on the left (or centred), with a small pill button on the right on some emails ("Visit Our Site" / "Let's Connect").
2. **Hero block.** A rounded-corner panel about 610 px wide inside a 20 px margin. Two styles are used:
   - **Navy hero** (`#010F37`) with a white headline, an optional green highlight box on the key phrase, a 3D icon or illustration on the right, and a green pill CTA with a ↗ arrow.
   - **Light gradient hero.** White with a soft blue, green or orange glow, a navy headline and a centred illustration.
   - The headline is a question or a bold claim ("Are You Paying to Lose Customers?", "46% of all searches on Google are for a local business").
3. **Intro copy.** One bold lead sentence, then 2 short paragraphs. Left-aligned, about 13–14 px body text at 650 px width.
4. **Value section.** A light grey rounded card holding 3–4 rows. Each row has an icon on the left (blue, orange or green line icon), a coloured subhead, and 2–3 lines of body text. Numbered circles (1-2-3) are used for steps. Older emails alternate icons left and right in a zig-zag.
5. **Proof block** (optional, recommended). A client success story with a photo or video thumbnail and a stat, for example Happy Hemp (+60% presence), Afloat Waterbeds (+67.83% sales), Dr. Paré, Green Olive, KPAI testimonial (476 leads). The CTA is "Read the case study".
6. **Secondary offer** (optional). A downloadable resource card: a PDF mockup on the left, headline and orange "Download Now" button on the right (checklists, SEO guide).
7. **Closing CTA band.** A full-width rounded navy (or bright blue `#26A9E1`) panel with a headline, 2 lines of copy and a pill button: "Book Your Free Consultation Now", "Get a Free Strategy Review" or "Free Consultation".
8. **Sign-off.** A centred, themed closing line plus "The Digital Resource Team" in bold. Closing lines used so far: "Cheers to your journey," "Your partner in digital growth," "Let's Capture Your Audience's Attention," "Together, Towards Greater Success,".
9. **Footer.** A thin gradient divider, the logo with the tagline "Your resource for everything digital", social icons in blue (Facebook, X, LinkedIn, YouTube, Pinterest, Instagram), then the copyright line.

## 4. Design tokens

Brand values come from the DR brand guide. The "seen in Canva" column was read from the text colours inside the files.

| Token | Brand value | Seen in Canva | Notes |
|---|---|---|---|
| Navy | `#010F37` | `#010F37`, `#000F37`, `#06164B` | Standardise on `#010F37` |
| Blue | `#26A9E1` | `#26A9E1`, `#0B91CB` (#1, #13) | `#0B91CB` is off-brand |
| Orange | `#F6931E` | `#F6921E`, `#EB750B` (#10, #11, #16) | `#EB750B` is off-brand |
| Green | `#D5DE23` | `#D5DE22` | OK |
| Body text | `#404041` | `#000000`, `#313133`, `#404041` | Use `#404041` for body text and reserve black for the logo |
| Font | Inter Tight (Black/Bold for headlines, Semi-Bold for subheads, Regular for body) | A bold geometric sans in the new emails; a different sans in older ones such as #11 | Use Inter Tight only |
| Corners | Rounded sections and images | About 16–20 px radius on panels, pill buttons | Keep one radius per email |
| Surface (support neutral) | `#F3F5F8` | Tips card in Above the Scroll 2027 | **Proposed:** light grey for value cards, confirm with the brand owner |
| Blue tint (support neutral) | `#E9F6FC` | Poll section in Above the Scroll 2027 | **Proposed:** pale blue behind interactive blocks |
| Border (support neutral) | `#E3E6EB` | Proof card outline | **Proposed:** 1.5 px outlines on white cards |

**Button logic (brand rule):**

- Green = primary lead CTA (consultation, contact).
- Orange = downloads and media.
- Blue = secondary or informational ("Learn more", "Visit our site").
- Outlined = navigation.

## 5. Copy pattern

- **Subject:** topic plus curiosity or benefit. **Assumption:** subject lines aren't stored in Canva, so ask where they live (HubSpot?).
- **Hero headline:** at most 10 words, a question or a stat.
- **Structure:** problem → why it matters → 3–4 tips (subhead plus 2–3 lines each) → proof → one main CTA.
- **Tone:** friendly and confident, light humour ("Smart, isn't it?"). Use em dashes sparingly.
- **Industries:** keep examples industry-neutral. #6 includes a healthcare-only "Internal Practice Marketing" block, which should only go to the medical segment.

## 6. Audit findings (what to fix)

**Across all emails**

1. **Copyright says "2024"** on every email checked. Change it to the current year, or remove the year.
2. **Too many CTAs.** #3 has 6 buttons, #10 has 4 different CTAs, and #4, #9 and #13 have two competing primary CTAs. Aim for one primary CTA, repeated at most twice (hero and closing band), plus at most one secondary link.
3. **Uneven canvas heights and trailing white space** (see section 2).
4. **Colour drift.** Off-brand blue `#0B91CB`, orange `#EB750B`, and three different navies.
5. **Two visual generations mixed.** #11 (and #12, partly) still use the older style: orange headings, black body text, zig-zag icons. The other emails use the 2025–26 template. Restyle #11 and #12.
6. **Naming.** #17 and #18 have no topic, #11 uses a hyphen, and the sequence order isn't written anywhere.
7. **Hidden or old pages in live files.** They add risk of exporting the wrong page. Label them or move them out.

**Specific emails**

| # | Topic / headline | Size | Notes |
|---|---|---|---|
| 1 | Stop Losing Customers You Already Have | 650×3000, 5 pages (3 hidden) | Good model email. Page 2 is a quiz variant. |
| 2 | Ever Wonder What It Truly Means to Captivate Your Audience? (SEO + content) | 650×3000, 4 pages | Several variants; pick one |
| 3 | Your Best Customers Are Searching for You — Can They Find You? | 650×3000, 2 pages | 6 CTAs; cut the per-section "Learn more" buttons |
| 4 | Boost Your Site's Impact with SEO-Smart Content | 650×3000, 1 page | 4 CTAs |
| 5 | Snap Your SEO Into Focus with Multimedia (Green Olive) | 650×3000, 4 pages | |
| 6 | Are You Paying to Lose Customers? (retention) | 650×3000, 3 pages | Healthcare-only IPM block |
| 7 | Welcome to Your Digital Marketing Journey | 1 page | Only CTA is a blog post; no consultation ask |
| 8 | Boost Your Business Growth with Multichannel Marketing (Dr. Paré) | 650×3000, 2 pages | |
| 9 | Compliance Is the Backbone of Digital Growth | 650×3000, 2 pages | Download + consult compete; ~600 px blank space |
| 10 | What Posts Do You Engage With? (Happy Hemp) | 650×3000, 5 pages | 4 CTAs; page 5 is just a phone asset |
| 11 | Is Email Marketing Really Dead? (Afloat Waterbeds) | 650×4000, 3 pages | Old style; ~1,000 px blank space |
| 12 | 55% More Website Traffic with One Simple Strategy | ~650×4200, 1 page | Longest email; consider splitting it |
| 13 | Did You Know? 7–8 touchpoints | 650×1800, 3 pages | All in one navy block; 2 CTAs |
| 14 | Why a Full-Service Agency Is Your Secret Weapon (KPAI) | 2 pages | Last edited 11 months ago |
| 15 | Targeted Ads Deliver Results, Not Empty Clicks | 650×4000, 2 pages | ~1,000 px blank space |
| 16 | Customers Need to See It to Believe It (video) | 650×3000, 1 page | Clean model email; ~400 px blank space |
| 17 | DR Lead Manager (CRM): "You're leaving money on the table" | 650×3000, 2 pages | Needs a topic in its name |
| 18 | 46% of searches are local | 650×3000, 4 pages | Needs a topic in its name; pages 3–4 are alternative heroes |

## 7. Workflow for building a new email

1. **Brief.** Confirm the topic, audience segment, the one primary CTA, the proof asset and the send position in the drip.
2. **Duplicate** a model email (#1 or #16), not a blank canvas, and rename it `Cooling Drip Email #NN — Topic`.
3. **Write copy** in the section-3 structure. Keep the whole email to about 2,000–2,600 px tall.
4. **Apply tokens** from section 4: exact hex values, Inter Tight, one corner radius, button colour by intent.
5. **Trim the canvas** to fit the content. Hide or label any variant pages.
6. **QA checklist:**
   - one primary CTA
   - current-year copyright
   - no off-brand hex values
   - readable at mobile width (body text at least 14 px when the 650 px canvas scales to 375 px)
   - alt text and link list prepared
   - the sign-off line is new and themed
7. **Hand-off. Confirmed for Above the Scroll 2027, assumed for the Cooling Drip:** the design is the visual mockup, and the email is rebuilt in HubSpot as live text and buttons, with the design tool used to export images (hero art, icons, case-study cards) as PNG. Don't send one flat full-length image: it hurts deliverability, accessibility and mobile.

## 8. Open questions to confirm with the team

- Which platform sends the Cooling Drip (HubSpot?), and is each email rebuilt as live text or sliced from Canva? (Above the Scroll: HubSpot, live text plus PNG images. Confirmed.)
- What are the send cadence and the order of #1–#18? The file numbers may not match the send order.
- Where do subject lines, preheaders and UTM links live? (Above the Scroll: in the monthly copy doc and `copy/2027-above-the-scroll-calendar.csv`. The Cooling Drip could follow the same pattern.)
- Which hidden pages or variants are live A/B tests and which are just archive?

## 9. Above the Scroll (monthly newsletter) in Figma, from 2027

Full process: `../design/2027-above-the-scroll-build-process.md`. Figma file: **DR Above the Scroll 2027** (Creative's team), one page per month.

**Why Figma for this series:** Claude Code can build and edit it by script (exact tokens, named layers, per-block PNG export settings), so each month starts from last month's frame with only the text and art swapped.

**Frame:** 650 px wide, 20 px margins, 610 px panels, 20 px radius everywhere, 24 px between blocks. Colours come from the file's **DR Brand** variable collection, never typed in as hex.

**Layer naming is the contract** between the copy doc, Figma and HubSpot:

| Prefix | Meaning | HubSpot module |
|---|---|---|
| `IMG/NN-name` | Exported as PNG @2x (export settings already on the frame) | Image, 610 px, alt text from the copy doc |
| `TXT/NN-name` | Live text, never exported as an image | Rich Text |
| `BTN/NN-name` | Button (instance of the `BTN/poll-option` component) | Button |
| `HUBSPOT/NN-name` | Reference only | HubSpot's own module (footer) |

**Anatomy:** `IMG/01-masthead` (logo, issue pill, "ABOVE THE SCROLL" wordmark, Blue→Green→Orange vibrant lines) · `IMG/02-hero-art` (navy panel, low-opacity dot grid, illustration) · `TXT/03-h1` (Inter Tight Black 34–36 px, green highlight on one word) · `TXT/04-intro` · `TXT/05-tips` (surface card, numbered circles in Blue, Green, Orange) · `IMG/06-proof-card` + `TXT/06b-proof-line` · `TXT+BTN/07-poll` (blue-tint card, four full-width blue pill buttons) · `IMG/08-bts-card` (real team photo + orange department pointer) + `TXT/08b-bts-line` · `TXT/09-cta-band` (navy) · `TXT/10-signoff` · `HUBSPOT/11-footer`.

**Rules learned from 2019–2025:**

- Keep it to 4 images or fewer. Everything that's words is live text.
- One primary CTA. Poll buttons count as one CTA (blue). A consult offer that isn't the month's CTA is a text link, not a second green button.
- Every image needs alt text that makes sense on its own. No important words only inside an image.
- About 2,600–2,900 px tall. If it grows past 3,000 px, cut a block, don't shrink the type.
- Live text in HubSpot: H1 34 px, body 16 px. Images can scale to 375 px on phones, so text inside images must be at least 13 px at 650 px.

**Known gaps:** Inter Tight isn't available to the Figma API, so scripted layers are set in Inter; switch the family to Inter Tight in Figma desktop before export. The DR logo has to be placed by hand (the cloud environment can't upload to Figma).
