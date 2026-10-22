# Above the Scroll 2027: Figma → HubSpot Build Process

How each monthly issue is designed in Figma, sent from HubSpot, and how much of it Claude Code can do for you. January 2027 is the test build.

**Figma file:** [DR Above the Scroll 2027](https://www.figma.com/design/OiN1antRYf5laXXSicSUXj) (Creative's team) · January frame: [`ATS 2027-01 · January · Fresh Start`](https://www.figma.com/design/OiN1antRYf5laXXSicSUXj?node-id=2-19)
**Copy:** [`../copy/2027-01-january-copy.md`](../copy/2027-01-january-copy.md) · **Calendar:** [`../copy/2027-above-the-scroll-calendar.csv`](../copy/2027-above-the-scroll-calendar.csv)

---

## 1. Why Figma, not Canva

Both work. Figma is the better fit for a process Claude Code runs every month:

| Need | Figma | Canva |
|---|---|---|
| Claude Code sets exact hex values, spacing and layer names by script | Yes (Plugin API through the Figma connector) | Limited: AI generation and partial edits |
| Brand colours stored as reusable tokens | Yes: the file has a **DR Brand** variable collection (13 colours) | Brand kit, but not bindable by script |
| Swap one month's text into last month's layout | Yes: layers are named by copy key (`TXT/03-h1`), so a script finds and replaces them | Manual |
| Export only the image blocks as PNG @2x | Yes: export settings are already set on every `IMG/` frame | Manual per element |
| Team already knows it | DR Web Style Guide lives in Figma | Cooling Drip lives in Canva |

Canva stays the home for the Cooling Drip and social. Above the Scroll moves to Figma.

## 2. How the January frame is organised

The frame is 650 px wide (same as the Cooling Drip), with 20 px side margins and 610 px panels with a 20 px corner radius. Every top-level block has a prefix that says how it gets into HubSpot:

| Prefix | What it is | In HubSpot |
|---|---|---|
| `IMG/` | Artwork (masthead, hero art, proof card, Behind the Screens card) | Export PNG @2x → File Manager → Image module at 610 px, with alt text from the copy doc |
| `TXT/` | Live text (H1, intro, tips, proof line, BTS line, CTA band, sign-off) | Paste into a Rich Text module. Never as an image. |
| `BTN/` | Buttons (the four poll answers) | Button module: `#26A9E1`, white bold caps, full width, pill radius |
| `HUBSPOT/` | Footer, for reference only | HubSpot's own footer module (it handles the address, preferences and unsubscribe) |

Blocks in order: `IMG/01-masthead` · `IMG/02-hero-art` · `TXT/03-h1` · `TXT/04-intro` · `TXT/05-tips` · `IMG/06-proof-card` + `TXT/06b-proof-line` · `TXT+BTN/07-poll` · `IMG/08-bts-card` + `TXT/08b-bts-line` · `TXT/09-cta-band` · `TXT/10-signoff` · `HUBSPOT/11-footer`.

About 2,900 px tall, inside the 2,000–2,600 px Cooling Drip guide plus the poll block. Only 4 images, so the email stays mostly live text (the Feb 2024 lesson).

**Before the first export (one-time, in Figma desktop):**

1. Place `dr_logo_primary.png` in both **DR LOGO** slots (Fill: Fit). The connector couldn't upload it because the network blocks Figma's upload endpoint from this environment.
2. Select all text and switch the family from Inter to **Inter Tight** (the API couldn't load it). Black for the H1 and wordmark, Semi Bold for subheads, Regular for body.
3. Drop the approved client photo and the team photo into the grey slots.

## 3. HubSpot template (build once)

Build January in HubSpot's drag-and-drop editor, then **Save as template: "ATS 2027 Master"**. Every later month clones it.

| Section | HubSpot setup |
|---|---|
| Body | 650 px, background white, font Inter Tight with Arial fallback (Inter Tight isn't installed on most phones; Arial is the safe fallback) |
| Text | H1 34 px Black `#010F37`; lead sentence 19 px Semi Bold `#010F37`; body 16 px/155% `#404041` |
| Tips | Section background `#F3F5F8`. Numbered circles are part of the text (1, 2, 3 in bold) or small PNG icons. |
| Poll | Section background `#E9F6FC`, 4 button modules |
| CTA band | Section background `#010F37`, white text, link `#26A9E1` underlined |
| Mobile | Text stays live and reflows. Images scale to 100%. Check at 375 px. |

## 4. The monthly workflow (what Claude Code does vs. what a person does)

| Step | Who | What | Time |
|---|---|---|---|
| 1. Brief | Claude Code | Read the month's row from `2027-above-the-scroll-calendar.csv` | instant |
| 2. Copy | Claude Code → owner reviews | Write `copy/2027-MM-<month>-copy.md` using the January doc as the template and `guides/dr-brand-voice-copywriting.md` for voice. Every block keeps its key. | 10 min + review |
| 3. Design | Claude Code | Duplicate the January page in Figma, rename to the month, replace the text in every `TXT/` and `BTN/` layer by key, update the masthead pill and hero art | 5 min |
| 4. Art + photos | Designer | Swap the hero illustration, client photo and team photo; check in Figma | 30–60 min |
| 5. Export | Designer (or script with a Figma token) | Export the 4 `IMG/` frames as PNG @2x, named `ats-2027-MM-<block>.png` | 2 min |
| 6. HubSpot build | Owner | Clone "ATS 2027 Master", replace the 4 images, paste the `TXT/` blocks, set subject A/B, preheader, links with UTMs, plain-text version | 30 min |
| 7. QA | Owner + one reviewer | The QA checklist at the bottom of the copy doc. Send a test to the seed list. | 20 min |
| 8. Send | HubSpot | Last Tuesday, 5:30pm ET (see calendar for exceptions) | |
| 9. Report | Claude Code (with a HubSpot export) | Fill `reporting/2027-MM-report.md` with the standard one-screen report 7 days after send | 10 min |

Target: under 3 hours of human time per issue, down from 2–6 hours on reporting alone.

**What stops it being fully automatic today:**

- The HubSpot connector in this workspace can only query segments. It can't create or edit emails, so step 6 is copy-paste. If DR adds a HubSpot private-app token, a script could clone the template and fill the modules by name.
- Figma uploads and exports from Claude Code's cloud container are blocked by the network policy (`mcp.figma.com` and `www.figma.com`). Running Claude Code locally, or allowing those hosts in the environment, would let it place images and export PNGs itself.

## 5. Naming

- Figma page: `January 2027`, `February 2027`, …
- Frame: `ATS 2027-MM · <Month> · <Theme>`
- PNGs: `ats-2027-01-masthead.png`, `ats-2027-01-hero-art.png`, `ats-2027-01-proof-card.png`, `ats-2027-01-bts-card.png`
- HubSpot email: `ATS 2027-01 January – General` and `… – Franchise`
- UTM campaign: `ats-2027-01`

## 6. Franchise version

Same HubSpot email cloned once. Change only:
1. `[tip2]` text (franchise swap in the copy doc)
2. The proof image and proof line
3. Subject line if the calendar gives a franchise one

Send to the Franchise list at the same time.
