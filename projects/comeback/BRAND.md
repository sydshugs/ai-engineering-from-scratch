# Comeback — brand v0.1

Doorstep returns and exchanges, sold to retailers, offered to shoppers as one button inside the store's own return flow. A driver collects the item, brings it to the store or warehouse, and the refund or exchange lands the same day.

Status: draft, September 2026. Nothing here is trademark- or domain-checked.

## Name

**Comeback.** Two things come back: the item to the shelf, and the shopper to the store. The retailer only needs to hear the second one.

Why it works:

- Reads as a verb. "Comeback picks it up." "Sent with Comeback."
- Built to be co-branded. The shopper's screen belongs to the retailer, so Comeback appears as "Return with Comeback", never as a second app.
- No collision found in the returns space in a first-pass web search. Wider trademark and domain checks are still to do.

Rejected on collision: Roundtrip (funded medical-transport startup), Backhaul (generic freight term, backhaul.io), Runback (ShopRunBack, Paris returns logistics), Redo (existing Shopify returns app), Loop and Rebound (existing returns products).

Sketched alternates, kept on the canvas: **Ferry** (utility, logistics-first, reads as boats) and **Volley** (playful, exchange-first, sports metaphor may feel light to retail ops).

## One-liners

- To the shopper: *Don't take it back. We will.*
- To the retailer: *Turn a refund into a second visit.*
- Headline: *The return that brings the customer back.*

## Mark

A lowercase "c" drawn as a return arrow. One stroke, round ends, no fill. Stroke is 1/8 of the box at every size.

```svg
<svg viewBox="0 0 64 64" fill="none" stroke="currentColor" stroke-width="8" stroke-linecap="round" stroke-linejoin="round">
  <path d="M43 46A18 18 0 1 1 43 18"/>
  <path d="M40 7L43 18L32 19"/>
</svg>
```

Wordmark: `comeback`, lowercase, Bricolage Grotesque 800, letter-spacing −0.04em.

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

- Display: **Bricolage Grotesque** 700/800 (Google Fonts). Fallback: Arial Black, Helvetica Neue.
- Body: **Instrument Sans** 400/500/600 (Google Fonts). Fallback: Helvetica, Arial.
- Caps labels: Instrument Sans 600, 13px, letter-spacing 0.08em.

## Voice

1. **Say it in one breath.** "We'll come get it." Not "Schedule a convenient doorstep collection."
2. **Promise the pickup, not the policy.** The retailer owns the return rules. Comeback owns the trip. Never explain a policy in our voice.
3. **Talk like the store, not the courier.** Shoppers hear "your refund," never "the package." Retailers hear "your customer," never "the consignee."

## Co-branded surface

Inside a retailer's "How do you want to send it back?" step, Comeback is one option among "Bring it to a store" and "Ship it back". Label: **Return with Comeback** or **Exchange with Comeback**. Sublabel: *A driver picks it up at your door. No box or label.* Price shown is the retailer's to set.

Status chips: Signal dot for "Driver on the way", Moss dot for "Refund landed". Attribution line: "Picked up by Comeback".

## Design files

`design/` holds the artboard sources for the brand canvas (`Main`, `Mark`, `Button`, and the two alternate sketches) plus `canvas.json`.

## Next

Three user journeys, one artboard series each: shopper, driver, retailer.
