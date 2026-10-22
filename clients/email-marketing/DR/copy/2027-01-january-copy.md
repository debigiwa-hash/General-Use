# Above the Scroll: January 2027 Copy

**Status:** Draft for review · **Send:** Tue 26 Jan 2027, 5:30pm ET · **Figma:** see `../design/2027-above-the-scroll-build-process.md` for the file link

This is the test build for the 2027 process. Every block below has a **key** in brackets (for example `[h1]`). The same key is the layer name in Figma and the module name in HubSpot, so copy can be swapped by script each month.

Legend: **IMG** = exported from Figma as PNG and uploaded to HubSpot. **TXT** = live text, copied from this doc (or Figma) into a HubSpot rich-text module. **BTN** = HubSpot button module.

---

## Brief

| Field | Value |
|---|---|
| Month | January |
| Theme | Fresh Start |
| Topic | We're back. How customers find a business in 2027 (Google + AI answers), and a one-click vote on what we cover this year. |
| Purpose | Restart the list after about 16 months, clean it, and learn what readers want. Test the Figma → HubSpot build. |
| Audience | General: everyone on the cleaned list (one-time, for the restart). Franchise: same email with the swaps below. DR employees suppressed, seed copy only. |
| Primary CTA | **Vote for Your 2027 Topics** (the 4 poll buttons, blue) |
| Secondary link | Book a free 30-minute strategy call (text link only) |
| Proof | One approved client result (see `[proof_*]`) |
| Q1 test | Subject line A (benefit) vs. B (curiosity), 50/50, winner on click rate |
| Main number | Click rate. Goal for this send: **2%** (any poll click or the strategy-call link) |

## Inbox

| Key | Copy |
|---|---|
| `[subject_a]` | How customers find a business now, in 2 minutes |
| `[subject_b]` | We've been quiet. Search hasn't. |
| `[preheader]` | Plus one click to pick what we cover in 2027. |
| `[from_name]` | [Owner first name] at Digital Resource |
| `[reply_to]` | [owner email] (replies are welcome; see Behind the Screens) |

## Body

**`[masthead]` IMG**
Artwork: "ABOVE THE SCROLL" wordmark, "January 2027 · Fresh Start" kicker, DR logo.
Alt text: `Above the Scroll, January 2027, from Digital Resource`

**`[hero_art]` IMG**
Artwork: navy panel with a search bar showing an AI-style answer card that has a business listing in it (illustration, no words that matter).
Alt text: `A search answer that recommends a local business`

**`[h1]` TXT** (H1, Title Case; green highlight on "Changed" in the design)
> Search Changed While We Were Quiet

**`[intro]` TXT**
> **It's been a while, and we're glad you're still here.**
>
> We took a break from Above the Scroll. In that time, the way people look for a business kept changing. More of them now get one answer from Google or an AI tool like ChatGPT, instead of a page of ten links.
>
> That's good news if you're the business in the answer. Here's what helps you get there, in about the time it takes to finish your coffee.

**`[tips_title]` TXT**
> The 60-Second Version

**`[tip1]` TXT**
> **Keep Your Google Profile Current:**
> Hours, photos, services and a phone number that actually rings. Google and AI tools lean on this listing, so wrong details cost you calls.

**`[tip2]` TXT** (General)
> **Answer Real Questions on Your Site:**
> Add short, plain answers to the questions customers ask you on the phone. Those answers are what search engines and AI tools quote back.

**`[tip2]` TXT** (Franchise swap)
> **Give Every Location Its Own Google Profile:**
> Each location needs its own hours, photos and local number. One shared listing makes it hard for nearby customers to find the right door.

**`[tip3]` TXT**
> **Ask Every Happy Customer for a Review:**
> Recent reviews tell Google, AI tools and new customers that you're active and trusted. A quick text with a link does the job.

**`[proof_card]` IMG** + **`[proof_line]` TXT**
Artwork: client logo or photo, one big number, short quote.
> **476 leads** for KPAI after we brought their marketing under one roof.

Alt text: `KPAI: 476 leads`
⚠️ **Confirm before build:** the KPAI number and wording come from Cooling Drip #14 and need client approval and a date. Alternates already used in DR emails: Happy Hemp (+60% market presence), Afloat Waterbeds (+67.83% sales). Franchise version: use a franchise client.
Not linked this month, so the vote stays the only primary click.

**`[poll_title]` TXT**
> Quick Poll: What Should We Cover First in 2027?

**`[poll_intro]` TXT**
> One click is your vote. We'll share the results in February and plan the year around them.

**`[poll_1]`–`[poll_4]` BTN** (blue, full width, stacked; each is its own tracked link)

| Key | Button label | Opens (existing DR blog post) |
|---|---|---|
| `[poll_1]` | Showing Up in Google and AI Answers | `/post/seo-aeo-and-geo-why-search-optimization-still-runs-through-seo` |
| `[poll_2]` | Getting More Good Reviews | `/post/how-to-turn-negative-reviews-into-a-reputation-management-opportunity` |
| `[poll_3]` | Turning Website Visits Into Calls | `/post/the-connection-between-website-development-and-ai-search-rankings` |
| `[poll_4]` | Ads That Pay for Themselves | `/post/how-google-ads-drive-real-business-growth-through-conversions` |

Each vote takes the reader straight to DR's own article on the topic they picked, so the vote is also their first visit to the website.

**`[bts_card]` IMG** + **`[bts_line]` TXT**
Artwork: real photo of the 2027 newsletter owner at their desk, "Behind the Screens" orange pointer label.
> **Behind the Screens:** Meet [Name], our [role] and the person writing to you each month. Hit reply and your note lands in [Name]'s inbox. [Name]'s pick for January: [one song or one tool].

Alt text: `[Name] from the Digital Resource team`

**`[cta_band]` TXT** (navy section, white text)
> **Prefer a Quick Chat Instead?**
> If you'd rather we check how your business shows up on Google and in AI answers, book a free 30-minute call. You'll leave with a short list of what to fix first.
>
> [Book a free 30-minute strategy call →](/contact-us)

**`[signoff]` TXT**
> Here's to being found in 2027,
> **The Digital Resource Team**

**`[footer]`** HubSpot default footer: logo, tagline "Your resource for everything digital", social icons, address, **Manage preferences** and **Unsubscribe**, © 2027.

## Links and UTMs

Base: `https://www.yourdigitalresource.com`. Every link below is an existing DR page; nothing new needs building. Open each one the week before send to confirm it still loads.
Every link gets: `utm_source=hubspot&utm_medium=email&utm_campaign=ats-2027-01&utm_content=<key>`

| Key | URL path | utm_content |
|---|---|---|
| `[poll_1]` | `/post/seo-aeo-and-geo-why-search-optimization-still-runs-through-seo` | `poll-search-ai` |
| `[poll_2]` | `/post/how-to-turn-negative-reviews-into-a-reputation-management-opportunity` | `poll-reviews` |
| `[poll_3]` | `/post/the-connection-between-website-development-and-ai-search-rankings` | `poll-website` |
| `[poll_4]` | `/post/how-google-ads-drive-real-business-growth-through-conversions` | `poll-ads` |
| `[cta_band]` | `/contact-us` | `cta-strategy-call` |

**Counting votes:** each poll button is a different link, so HubSpot already reports clicks per link. Build one active list per link ("Clicked link in email" = that URL) to tag each contact's interest. This replaces Typeform and needs no thank-you page.

**Franchise version:** swap `[poll_2]` to `/post/franchise-review-management-for-positive-image`.

## Plain-text version (paste into HubSpot's plain-text tab)

```
ABOVE THE SCROLL · JANUARY 2027

Search Changed While We Were Quiet

It's been a while, and we're glad you're still here.

We took a break from Above the Scroll. In that time, the way people look for a business kept changing. More of them now get one answer from Google or an AI tool like ChatGPT, instead of a page of ten links.

That's good news if you're the business in the answer. Here's what helps you get there.

THE 60-SECOND VERSION

Keep Your Google Profile Current: Hours, photos, services and a phone number that actually rings. Google and AI tools lean on this listing, so wrong details cost you calls.

Answer Real Questions on Your Site: Add short, plain answers to the questions customers ask you on the phone. Those answers are what search engines and AI tools quote back.

Ask Every Happy Customer for a Review: Recent reviews tell Google, AI tools and new customers that you're active and trusted. A quick text with a link does the job.

QUICK POLL: WHAT SHOULD WE COVER FIRST IN 2027?
Showing up in Google and AI answers: {poll_1 link}
Getting more good reviews: {poll_2 link}
Turning website visits into calls: {poll_3 link}
Ads that pay for themselves: {poll_4 link}

Prefer a quick chat instead? Book a free 30-minute strategy call: {cta link}

Here's to being found in 2027,
The Digital Resource Team
```

## QA checklist (from the Sept 2025 checklist plus this plan)

- [ ] One primary CTA (the poll). Only one secondary link (strategy call).
- [ ] Subject A/B set in HubSpot, 50/50, winner metric = **click rate**
- [ ] Preheader set and doesn't repeat the subject
- [ ] Proof number approved by the client and dated
- [ ] All links have UTMs and open the right existing DR page
- [ ] Every image has alt text; no text-only meaning baked into images
- [ ] Franchise version has `[tip2]` and proof swapped
- [ ] DR employees suppressed; seed list receives a test
- [ ] Footer: © 2027, Manage preferences link works
- [ ] Read aloud once; no comma splices, at most 2 em dashes (this draft uses 0)
- [ ] Mobile preview at 375 px: body text 16 px, buttons full width

## Word count

About 230 words of body copy: a 60-second read.
