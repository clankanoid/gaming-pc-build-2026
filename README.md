# Gaming PC Build — eBay Used Parts ($1,200 budget)

**Status:** RESEARCHED, NOT PURCHASED
**Prices verified live on eBay:** 2026-09-08 (US, ships to 78758)
**Budget:** $1,200 (Venmo funds) — before tax
**Use case:** Omarchy (Arch Linux), CS2-first gaming, 1080p ultra / 1440p high-refresh, upgrade headroom
**Key decision:** AM4 platform (not AM5) — ~$250 cheaper for equal gaming performance, freeing budget for a 7900-class GPU. 3D V-Cache CPU prioritized for CS2.

---

## The build — $1,175.90 total (with monitor)

| # | Part | Listing | Price (ship) | Condition / Seller |
|---|------|---------|--------------|--------------------|
| 1 | **GPU** — Sapphire Pulse RX 7900 GRE 16GB | https://www.ebay.com/itm/336780580887 | $515.00 (free) | Used — aaeiken_0, 100% (108), OBO, no returns, MBG |
| 2 | **CPU** — Ryzen 5 5500X3D | https://www.ebay.com/itm/267610189625 | $209.99 + $5.99 | **New sealed**, free returns — desolate_puppy 99.9% (5.5K), 207 sold |
| 3 | **Motherboard** — MSI PRO B550M-VC WiFi mATX | https://www.ebay.com/itm/137710051407 | $74.95 (free) | Used — hitexstore 99.6% (173.7K), OBO, free returns |
| 4 | **RAM** — Corsair Vengeance LPX 32GB (2×16) DDR4-3600 | https://www.ebay.com/itm/820099466086 | $44.00 | Pre-owned |
| 5 | **PSU** — Corsair RM850e 850W 80+ Gold | https://www.ebay.com/itm/227491490870 | $54.99 (free) | **Factory refurb via corsairdirect**, 100% (488), 549 sold, free returns |
| 6 | **SSD** — Crucial P310 1TB Gen4 NVMe | https://www.ebay.com/itm/336783170737 | $59.00 (free) | New |
| 7 | **Case** — Phanteks XT Pro mesh mid-tower | https://www.ebay.com/itm/296236895993 | $61.99 (free) | New (Newegg on eBay), free returns |
| 8 | **Monitor** — LG UltraGear 32GP83B-B 32″ 1440p 165Hz IPS | https://www.ebay.com/itm/377472303537 | $149.99 OBO (free) | Used — thirdwavediscounts 99.4% (26.6K), 30-day returns seller-paid, **no power cable included** (any C13 cord works) |

- **PC only: $1,025.91** — $174 under budget
- **PC + monitor: $1,175.90** — $24 under budget (before TX sales tax; eBay collects it, real ceiling ≈ $1,270–1,290 all-in. Best Offers are the lever to pull under $1,200)

---

## Alternates (verified same day)

| Part | Listing | Price | Notes |
|------|---------|-------|-------|
| GPU: XFX MERC 310 RX 7900 XT 20GB | https://www.ebay.com/itm/800601552180 | $624.99 OBO + $19.98 | ~10–12% faster than GRE, 20GB. Small seller (6 fb, no returns) — offer ~$570. Build total w/ XT ≈ $1,156 (PC only) |
| GPU: Sapphire Pulse RX 9060 XT 16GB (new OC) | market ~$470–530, rising | — | ~35–40% SLOWER than GRE (128-bit bus vs 256-bit). Only buy if ≤$440 AND warranty matters more than fps. AMD discontinuing 16GB variant |
| Monitor: Samsung Odyssey G5 32″ 165Hz open box | https://www.ebay.com/itm/365833789297 | $149.99 | VA curved vs LG IPS — LG better for CS2 response times |
| Monitor: LG 32GR93U 4K 144Hz | https://www.ebay.com/itm/147309493903 | $179.99 | ⚠ visible "LCD line" defect — skip |
| CPU: used 5700X3D | none available ≤$260 | ~$260+ | Discontinued, used market bid up — not worth it over 5500X3D |
| CPU: 5700X (cheaper, non-X3D) | https://www.ebay.com/itm/158261365854 | ~$143 | Saves ~$73; keeps build at $953 but loses V-Cache |

## Upgrade path

- **Drop-in 5700X3D** on AM4 when used prices normalize (~$230) — board supports it
- Second M.2 slot free; 850W PSU leaves GPU headroom for future upgrades

## Suggested buy order

1. No-brainers first (strong sellers, returns): CPU → PSU → SSD → Case
2. Best Offers: ~$470 on GRE, ~$60 on motherboard, ~$130 on monitor
3. RAM last (high supply, prices drift daily)

## Platform comparison (why this vs prebuilt)

| | Prebuilt 5700X3D + RX 7600 XT | This DIY build |
|---|---|---|
| Total | $945.89 (PC only, no monitor) | $1,175.90 (PC + monitor) |
| GPU perf index | 100 (RX 7600 XT) | ~137 (7900 GRE) — 37% faster |
| CPU | 5700X3D (8C V-Cache) | 5500X3D (6C V-Cache, similar gaming perf) |
| Risk profile | One tested unit from one seller | 8 packages, self-assembly, MBG per item |
| Resale/upgrade | Monolithic | Modular — parts individually sellable/upgradeable |

## Risks & mitigations

- Used GPU = ex-mining risk (RDNA3 less so), no seller returns → covered by eBay Money Back Guarantee (30 days, DOA/not-as-described)
- PSU is the most failure-prone part → deliberately bought factory refurb with free returns
- All prices are pre-tax; TX sales tax collected by eBay at checkout
- Listings are eBay items — they expire. Re-verify before purchase; if any listing died, re-search with same specs (note: 32GB DDR4-3600 2×16 used ~$44–60, MSI B550M-VC WiFi ~$70–80 used)

## Notes for re-verification later

- `git log` in this repo shows when prices were checked
- To re-verify: paste listing URLs into a browser or fetch item pages; confirm price/shipping/seller feedback/returns still match
- Don't auto-purchase: per house rules, human confirms final order placement
