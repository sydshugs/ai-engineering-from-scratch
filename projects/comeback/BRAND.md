# Comeback — brand v0.1

Doorstep returns and exchanges, sold to retailers, offered to shoppers as one button inside the store's own return flow. A driver collects the item, brings it to the store or warehouse, and the refund or exchange lands the same day.

Status: draft v0.2, September 2026. Name checked by web search only; see "Name status" below.

## Name

**Comeback.** Two things come back: the item to the shelf, and the shopper to the store. The retailer only needs to hear the second one.

Why it works:

- Reads as a verb. "Comeback picks it up." "Sent with Comeback."
- Built to be co-branded. The shopper's screen belongs to the retailer, so Comeback appears as "Return with Comeback", never as a second app.
- No collision found in the returns space in a first-pass web search. See "Name status" for what a closer look found.

Rejected on collision: Roundtrip (funded medical-transport startup), Backhaul (generic freight term, backhaul.io), Runback (ShopRunBack, Paris returns logistics), Redo (existing Shopify returns app), Loop and Rebound (existing returns products).

Sketched alternates, kept on the canvas: **Ferry** (utility, logistics-first, reads as boats) and **Volley** (playful, exchange-first, sports metaphor may feel light to retail ops).

## One-liners

- To the shopper: *Don't take it back. We will.*
- To the retailer: *Turn a refund into a second visit.*
- Headline: *The return that brings the customer back.*

## Mark

A lowercase "c" drawn as a return arrow. Adapted from the Hugeicons *Refresh01* icon (free set, MIT licence): stroke thickened from 1.5 to 2.4 on the 24px grid, the arrow bracket shortened, and the arc ended earlier so the opening reads as a letter. One stroke, round ends, no fill.

```svg
<svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round">
  <path d="M19.5 16.5C17.9 19.2 15.1 21 12 21C7.02943 21 3 16.9706 3 12C3 7.02943 7.02943 3 12 3C15.7292 3 18.9286 5.26806 20.2941 8.5"/>
  <path d="M16.5 9H18C19.4142 9 20.1213 9 20.5607 8.56066C21 8.12132 21 7.41421 21 6V4.5"/>
</svg>
```

Wordmark: `comeback`, lowercase, Gabarito 800, letter-spacing −0.03em.

## Palette

| Name      | Hex       | oklch                | Role                                          |
|-----------|-----------|----------------------|-----------------------------------------------|
| Ink       | `#16221d` | 24% 0.02 165         | Text, primary buttons, dark surfaces          |
| Paper     | `#f9f5ec` | 97% 0.012 85         | Page background                               |
| Parchment | `#eee7d9` | 93% 0.02 85          | Cards, panels, secondary buttons              |
| Line      | `#d7d0c3` | 86% 0.02 85          | Borders, dividers                             |
| Mute      | `#67756f` | 55% 0.02 165         | Secondary text, metadata                      |
| Signal    | `#ea6f2f` | 68% 0.17 45          | Movement: driver en route, pickup window, mark |
| Moss      | `#00b667` | 68% 0.17 155         | Done: item received, refund landed            |

Signal and Moss share lightness and chroma and differ only in hue. Never both on one screen unless one is a status.

## Type

- Display: **Gabarito** 700/800 (Google Fonts). Fallback: Arial Black, Helvetica Neue.
- Body: **Host Grotesk** 400/500/600 (Google Fonts). Fallback: Helvetica, Arial.
- Caps labels: Host Grotesk 600, 13px, letter-spacing 0.08em.

Chosen from a sixteen-face comparison of the lowercase wordmark. Gabarito's round c, e and a echo the mark and read warm to a shopper who is mildly annoyed, while the 800 weight holds up in a retail ops deck. Two runners-up are kept on the canvas: Funnel Display + Onest (sharper, cooler, better for investors than doorsteps) and Sora + Figtree (wider, heavier, closest to how delivery apps already look).

## Colour, and why

Ink is a near-black green rather than pure black: calm and trustworthy, which matters because a return starts from a small disappointment. Paper and Parchment are warm off-whites so the page feels like a store, not a warehouse. Signal orange carries movement and urgency (a driver on the way) and is deliberately rationed to the mark, status, and one call to action. Moss green closes the loop (item received, refund landed). The risk to watch: orange is the colour of the delivery category, so if Signal spreads beyond those three jobs the brand blurs into the apps it sits beside.

## Voice

1. **Say it in one breath.** "We'll come get it." Not "Schedule a convenient doorstep collection."
2. **Promise the pickup, not the policy.** The retailer owns the return rules. Comeback owns the trip. Never explain a policy in our voice.
3. **Talk like the store, not the courier.** Shoppers hear "your refund," never "the package." Retailers hear "your customer," never "the consignee."

## Co-branded surface

Inside a retailer's "How do you want to send it back?" step, Comeback is one option among "Bring it to a store" and "Ship it back". Label: **Return with Comeback** or **Exchange with Comeback**. Sublabel: *A driver picks it up at your door. No box or label.* Price shown is the retailer's to set.

Status chips: Signal dot for "Driver on the way", Moss dot for "Refund landed". Attribution line: "Picked up by Comeback".

## Name status

Checked September 2026 by web search only. The USPTO database, Justia and Trademarkia were not reachable from this session, so this is not a clearance search.

- No exact **COMEBACK** mark was found live in classes 35, 39 or 42. The word appears in many longer marks (THE COMEBACK for a sports site, COMEBACK KID, COMEBACK MOBILITY for medical equipment, a dead COMEBACK SPORTS BAR filing). One bare COMEBACK serial (77420884) surfaced without readable details.
- **ComeBack App** (comebackapp.net) sells white-label loyalty apps to businesses. Same buyer as ours, adjacent service. This is the collision that matters.
- Domains: comeback.com and comeback.co are a clothing retailer, comeback.app is the loyalty company, comeback.io, comeback.ai and comebackhq.com all resolve. comebackreturns.com had no DNS record, which suggests it is free but does not prove it.

Verdict: usable as a working name, not yet safe to spend on. Get a paid clearance search before printing anything. If it fails, the canvas keeps two alternates.

## Design files

`design/` holds the artboard sources for the brand canvas (`Main`, `Mark`, `Button`, `Type`, and the two alternate sketches) plus `canvas.json`.

## Next

Three user journeys, one artboard series each: shopper, driver, retailer.
