# People's Canadian Roofing — handoff at ~60%

**Live:** https://10elizabethbell.github.io/peoplesCanadianRoofing/ · **Repo:** https://github.com/10elizabethbell/peoplesCanadianRoofing · **Built:** 2026-10-19 from Muse brief of 2026-10-19 (Facebook group "Essex County Contractor Referrals" flyer post)

## What's built
- One page, `index.html`, single file (~55KB, no images except the og/touch icon files beside it), phone-first.
- **World:** a fall storm at dusk over a Windsor roof. Navy storm sky with drifting cloud masses and last light behind the ridge, flag red, flyer gold, cool flag-white paper; heavy uppercase system type; the wordmark follows the flyer (upright caps, ROOFING in gold between two gold bars). On desktop a brick chimney stands in the right-hand sky.
- **Signature element (hero):** a live canvas roof of old, weathered shingles (moss, algae streaks, curled corners, missing tabs showing felt and nails) under rain, with maple leaves blowing across and landing on it. Drag a finger (any direction) or run the mouse across it and new slate shingles drop into place; rain soaks dark patches into the old shingles and splashes off the new ones; leaves get blown off as you work. Untouched for 5s, a "roofer" lays it course by course from the eave up, admires it, then it weathers back and starts again. Leaves and rain stay out of the text.
- **Carried through the page:** navy sections end in a white aluminum eavestrough (the How-it-works one has two courses of new shingles above it) that grows and drops water into the next section; a hand passing near the gutter knocks the drops loose.
- **Sections:** header (maple-leaf wordmark, 519-999-2445 top right) · hero ("Keep the weather out.", promise, *Get a free estimate* + outlined *Text us a photo of the roof*) · What we do (two service rows → form with that service preselected; care line; Licensed & insured / Free estimates) · How it works (3 steps) · Free estimate (where we work + towns beside the form on desktop; name, phone, address, need, notes → pre-filled text message to 519-999-2445, inline errors) · red close with the big tap-to-call number right after the form · footer.
- Tunables are in the `TUNE` object at the top of the script (brush size, speeds, rain/leaf counts, wind, idle time, drip spacing).

## Assumptions I made
- **Voice "we":** roofing is crew work; crew size is unknown.
- **Colors:** taken from the flyer (flag red, flag white, flyer gold, flyer navy panel). There's no logo file; the wordmark is set in the site's own type with a drawn maple leaf, and the favicon/home-screen icon is that leaf on navy.
- **Texting:** the brief says texts are unknown and the flyer only says "Call". 519-999 looks like a cell number, so I wired the hero secondary button and the estimate form to SMS. The number is still always one tap away: in the header, and in the red close directly under the form. **Confirm he can take texts**, or switch the form to call-first.
- **Step 2 copy** ("We look at your roof and tell you straight what it needs and what it will cost") assumes the free estimate is an in-person look.
- **Towns list** (Windsor, LaSalle, Tecumseh, Lakeshore, Amherstburg, Essex, Kingsville, Leamington, Chatham, Wallaceburg, Tilbury) is my expansion of "Windsor-Essex County & Chatham-Kent"; the flyer names only the regions.
- **Care copy** ("We look after your roof like our own family lives under it", "the only thing between your family and a Windsor winter") is mine, written in the owner's voice; swap in his words when you have them.
- **Audience:** the brief doesn't flag 40+, so the signature motion is on. Roofing customers skew older; if Mike's customers are mostly retirees, switch to the older-audience rules (draw the roof once, still).
- **"Licensed & Insured"** is on the flyer image (verified 2026-10-19); I didn't verify it independently.

## Placeholders and gaps
- **No Facebook link.** There's no business page; the ad came from Mike Peoples' personal profile, and his role isn't confirmed, so I didn't link a personal profile. Add the business page under the services/proof area and in the footer once one exists.
- **No work photos, no before/afters, no reviews**, so there's no proof section. The roof hero carries the page for now.
- **No email** (footer has none), **no hours**, **no years in business**, **no prices**.
- **Owner not named** on the page (relationship to Mike Peoples unconfirmed).

## Questions for the owner
- Is it your number for texts as well as calls?
- Your name and role: OK to say "I'm Mike" on the page?
- Photos of finished roofs (before/after from the same spot would light up the page), and a few customer reviews?
- A business Facebook page, Google Business listing, or email?
- Which towns do you actually go to; anything you won't do (flat roofs, commercial)?
- Hours / do you answer evenings and weekends?
- Any brands you install, warranty you offer, years doing this?

## Ideas not built (yours to pick)
- **Runner-up world:** the flyer's own waving Canadian flag: the whole hero a cloth-simulated flag you can ripple with a finger, wordmark on the white band. More literal, very on-brand, less about the trade.
- Nail-gun "thunk" puff of granule dust when a shingle lands; a little roofer's ladder at the roof edge.
- When the roof is fully re-shingled, the rain stops and the sky clears for a moment.
- Before/after sliders as soon as there are photos (plain red divider line).
- A Google Business Profile setup is probably worth more to him than anything else here (searches for "roofer Windsor" land on Maps).
- Booking page (`book.html`) with the same world, if he wants more structured intake.

## Not verified
- Real-device touch on iPhone/Android and inside Facebook's in-app browser (tested with Playwright Chromium + WebKit touch emulation at 360/390/430 and desktop 1440).
- The real SMS handoff on iOS and Android (the `sms:` link and decoded message body were checked in the browser, not on a phone).
- Frame rate on older phones.

## Review trail
- Impeccable: every mode except `live` and `onboard` (critique, audit, harden, adapt, optimize, clarify, polish, layout, typeset, colorize, bolder, quieter, distill, animate, delight, overdrive) ran as two parallel review passes; fixes applied. Then the finish reviewer: round 1 "fix" (8 items), round 2 scored 6 resolved, sky partial, plus one phone-order regression; both addressed, and I stopped at the two-round budget, so the last sky/form change hasn't had a third review.
- Impeccable's concept roll (seed f5fdb490) assigned my 7th-ranked world (storm-radar sweep); the pitch-site rule picks the world that best carries brand + touch, so I built #1 instead.
- Detector: two cramped-padding findings suppressed as intentional (service-list top rule; the gutter sitting on the How-it-works boundary). One tight-leading (1.27) finding on a heading left standing.
