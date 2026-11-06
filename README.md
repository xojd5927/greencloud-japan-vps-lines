# greencloud japan vps: SoftBank vs IIJ Lines Compared, $25/Year Plans, and the Fine Print Before You Order

GreenCloud sells some of the cheapest Tokyo VPS plans you'll find anywhere, and almost all of its Japan inventory comes in two flavors: a **SoftBank** network and an **IIJ** network, with entry pricing at **$25/year** on recent annual sale batches. The trade-offs are real, though. Every Japan plan is non-refundable, the sale lines run on shared CPU, and stock rotates constantly — popular Tokyo tiers have disappeared for months at a time before restocking.

This article walks through every Tokyo product line GreenCloud currently lists, what each one actually costs, which network makes sense for your route, the current anniversary promotion, and the clauses worth reading before you click order.

> **In a hurry?**
> - **Cheapest entry point:** Premium KVM Sale, 1 core / 2GB RAM / 25GB NVMe / 750GB traffic — **$25/year**, on either the IIJ or SoftBank line (October restock batch).
> - **Need lots of disk:** the Storage KVM line packs 500GB to 2TB of data storage from $25/year (NVMe boot drive plus a large SATA data volume).
> - **Prefer monthly billing:** KVMJP-2 at $10/month, 1 core / 2GB / 15GB.
> - **China-optimized routing:** the CN Premium Tokyo line (CN2GIA / CU PREMIUM / CMIN2) — strong config, but all five tiers showed zero stock on the official order page at the time of our last check.
> - **Buying big this week:** GreenCloud's 13th birthday sale runs October 26–31, with a 13% account-credit cashback on single orders over $500 — details below.
>
> 👉 [Check GreenCloud's current Tokyo stock and prices](https://greencloudvps.com/billing/aff.php?aff=6679)

## Every Tokyo plan GreenCloud currently sells

GreenCloud runs several parallel product lines for Japan, and the pricing logic differs between them. The annual sale lines (Premium KVM, Storage KVM) are where the headline prices live; monthly plans and the CN Premium line sit at higher price points with different purposes. Pricing below comes from the most recent published batches — October restock coverage for Premium KVM, mid-year review data for Storage KVM — so confirm the current number on the order page before paying.

**Annual plans (Tokyo, billed yearly):**

| Plan (Tokyo) | CPU / RAM | Storage | Traffic / Port | Price | Order |
| --- | --- | --- | --- | --- | --- |
| Premium KVM – entry (IIJ or SoftBank) | 1 core EPYC Milan / 2GB | 25GB NVMe RAID10 | 750GB / 10Gbps | $25/yr | [ Order — $25/yr](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Premium KVM – mid | 2 cores / 3GB | 35GB NVMe | 1TB / 10Gbps | $35/yr | [ Order — $35/yr](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Premium KVM – top | 4 cores / 8GB | 60GB NVMe | 2TB / 10Gbps | $68/yr | [ Order — $68/yr](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Storage KVM – 0.5TB (IIJ or SoftBank) | 1 core / 2GB | 20GB NVMe + 500GB SATA RAID-10 | 1TB / 10Gbps | $25/yr | [ Order — 0.5TB](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Storage KVM – 1TB | 2 cores / 3GB | 40GB NVMe + 1TB SATA | 2TB / 10Gbps | $45/yr | [ Order — 1TB](https://greencloudvps.com/billing/aff.php?aff=6679) |
| Storage KVM – 2TB | 4 cores / 6GB | 60GB NVMe + 2TB SATA | 4TB / 10Gbps | $80/yr | [ Order — 2TB](https://greencloudvps.com/billing/aff.php?aff=6679) |

A few things the table doesn't show. All of these plans include 1 IPv4 and a /64 IPv6 block, run Linux only (no Windows), are managed through the VirtFusion panel, and come with one free backup/snapshot. The 10Gbps port is shared infrastructure, not a guaranteed dedicated rate. Both sale lines are offered on **both** the SoftBank and IIJ networks at identical prices. Storage on the Storage KVM line is deliberately split: a small NVMe boot volume handles the OS, while the large SATA RAID-10 volume holds your data — built for file storage, backups, and media libraries rather than high-IO databases.

Stock at our last check of the official cart page: the 0.5TB tier showed zero availability on both networks; IIJ had six of the 1TB tier left, and SoftBank had five of the 2TB tier. These counters move constantly.

**CN Premium Optimized Tokyo** is the premium line, built specifically for China routes: CN2GIA for Telecom, CU PREMIUM for Unicom, CMIN2 for Mobile. All tiers run EPYC Milan on NVMe RAID-10 with daily backups — a feature the sale lines don't include. The five Tokyo tiers:

| Tier | CPU / RAM | Storage | Traffic / Port |
| --- | --- | --- | --- |
| Mini | 1 core / 2GB | 20GB NVMe | 500GB / 500Mbps |
| Plan 1 | 2 cores / 4GB | 40GB NVMe | 1TB / 1Gbps |
| Plan 2 | 4 cores / 8GB | 80GB NVMe | 2TB / 1.5Gbps |
| Plan 3 | 8 cores / 16GB | 160GB NVMe | 4TB / 2Gbps |
| Plan 4 | 8 cores / 32GB | 320GB NVMe | 8TB / 3Gbps |

The one price we could confirm from recent coverage is Plan 1 at **$45/month**. The catch: when we checked the official order page, all five Tokyo tiers (and all five Singapore tiers on the same product line) showed zero available stock. This line restocks periodically, so it's worth watching if China routing is your priority.

**Monthly plans** are listed by third-party VPS trackers rather than official pages we could price-check: KVMJP-2 (1 core / 2GB / 15GB) at $10/month and KVMJP-4 (4 cores / 8GB / 60GB / 4TB) at $40/month, with a larger KVMJP-5 SoftBank tier around $80/month. Treat these as indicative and confirm on the order page. There's also a Budget KVM family where Tokyo appears as one location among many — Tokyo SoftBank tiers on Intel Platinum Gen 2 CPUs with SSD storage, and Tokyo IIJ tiers on Xeon E5v3/v4 — but the official cart page didn't display prices for those in our snapshot, so we won't quote numbers we can't back up.

## SoftBank or IIJ: which Tokyo line should you pick?

Both lines cost the same, so choose on routing — this is the single most important decision when buying a GreenCloud Japan VPS, and it's also where most listings gloss over the details.

Here's what published route testing shows. On the **SoftBank** line, all three major Chinese carriers (Telecom, Unicom, Mobile) route via SoftBank; Chinese reviewer digvps found its routing consistent with other well-regarded SoftBank Tokyo products, with no particularly bad carrier among the three. On the **IIJ** line, everything routes via IIJ, and digvps's data flagged Telecom performance on that line as notably poor at the time of testing. Neither line carries any official China-optimization promise — that's what the CN Premium line is for — so you're buying standard international transit either way.

Two ways to check before spending money:

1. Run a ping/MTR from your own connection to GreenCloud's published Tokyo test IPs: **103.201.131.131** for SoftBank, **91.200.242.41** for IIJ.
2. If you're a Telecom customer and the IIJ test IP looks bad from your location, that's your answer — go SoftBank.

One nuance worth knowing: both lines sit in Tokyo, but the IIJ line's routing characteristics resemble Osaka-route products from other providers, per digvps's comparison. Same city, different network personality.

If your use case has nothing to do with China connectivity — a proxy endpoint elsewhere, a dev sandbox, a game server for Japanese users — the line choice matters much less, and you can just grab whichever tier is in stock. 👉 [See which Tokyo line currently has inventory](https://greencloudvps.com/billing/aff.php?aff=6679)

## The current promo: 13th birthday sale, and a renewal-price promise

GreenCloud is running its 13th birthday sale on LowEndTalk from **October 26–31 (UTC+0)**, and the company has said this is its only big promotion of the season — no Black Friday sale this year. Stock rotates during the event and sells through on a first-come basis.

The headline anniversary plan is the "1313" config: 6 fair-share EPYC Milan cores, 13GB RAM, 113GB NVMe 4.0 RAID-10, 3333GB–12TB traffic depending on location, 10Gbps port, at **$123 for three years**, available across APAC, US, and EU datacenters. On top of that, single orders over $500 paid between October 26–30 earn a **13% account-balance cashback** (excluding account top-ups); you claim it by opening a ticket before November 5.

The most interesting part for existing customers, though, is a written commitment on renewals. From the company's own announcement: *"we will continue honoring your existing renewal rates without surprise hikes"* — despite rising hardware, NVMe, RAM, and datacenter costs. For a provider whose entire model is cheap multi-year sale pricing, renewal-price stability is the difference between a good deal and a bait-and-switch. That promise makes the annual plans meaningfully easier to recommend, since the low first-year price is what you'll keep paying. 👉 [See GreenCloud's anniversary sale lineup](https://greencloudvps.com/billing/aff.php?aff=6679)

## The fine print: four things most listings skip

**Nothing on the Japan inventory is refundable.** Every Tokyo plan we checked — Premium KVM, Storage KVM, Budget KVM, CN Premium — carries a "No refund / money back on this plan" note directly on the order page. This is the clause that should shape your whole purchase: test the route first, decide second.

**Shared CPU, and it shows on the cheap lines.** The Premium KVM sale plans (and the 1313 anniversary plan) run EPYC Milan cores explicitly marked as fair-share, meaning you share physical cores with neighbors. The Storage KVM Tokyo tiers run Xeon E5v4. Either way, digvps's benchmark data on the Storage KVM line showed CPU scores consistent with noticeable overselling, and the reviewer settled on a conservative "E4 / acceptable" rating for that reason — while still concluding the product was attractive for its price tier. Translation: fine for light services, storage, proxies, and small sites; don't expect consistent full-core performance for compile jobs or databases under load.

**The Storage KVM line's disk is a hybrid.** The big 500GB–2TB numbers are a separate SATA RAID-10 data volume; the boot drive is a small NVMe SSD (20–60GB). digvps's published IO numbers only covered the SSD portion because the test machine's data volume was already mounted and in use, so large-disk performance remains formally untested by third parties. If your workflow hammers the big volume with random IO, treat the SATA volume as archival-grade.

**Stock is the real scarcity, and the $25/year tier has worn different faces.** Community trackers reported a 2 vCPU / 4GB SoftBank tier at $25/year restocking in early September after a long absence; the October restock coverage listed the Premium KVM entry at 1 core / 2GB / 25GB NVMe for the same $25/year. Same headline price, different configurations across batches — so read the spec list on the order page rather than trusting the price alone. GreenCloud's sales are inventory-based with no published end date. If a tier you want is in stock and the route test passes, waiting rarely improves the situation.

## What a GreenCloud Japan VPS actually costs over time

The annual sale pricing is where the value is concentrated, and the math is worth seeing plainly.

The $25/year Premium KVM entry plan works out to roughly **$2.08 per month**. Compare that with the KVMJP-2 monthly plan at $10/month: twelve months of the monthly plan costs $120 — nearly five times the annual plan's price for comparable RAM, though the monthly tier is a different product with its own storage sizing. If you're confident you'll keep the VPS for a year, the annual sale plan is the obvious spend.

The Storage KVM line scales differently: $25/year for 500GB of data storage, $45/year for 1TB, and $80/year for 2TB. At the top tier you're paying about **$6.67/month for over 2TB of storage with 4TB of traffic** — per-GB pricing that mainstream cloud providers don't get close to.

For reference on where prices have moved: during the October 2025 twelfth-anniversary sale, GreenCloud offered a 6-core / 12GB / 112GB NVMe Tokyo SoftBank plan at $112 for three years (about $3.11/month) and mid-size IIJ plans at $66 per two years and $88 per three years. Whether those exact batches are still orderable we can't confirm — the activity page didn't load during our checks — but the current 13th anniversary sale shows the pattern holding: this year's 1313 plan lands at $123 for three years, about **$3.42/month** for 6 cores and 13GB.

One caution on commitment length: since refunds don't exist here, a three-year prepayment is only sensible if you've already lived with the route and performance for a while, or if the renewal-price guarantee covers you. Starting with one annual term is the low-regret path. 👉 [Check current $25/year Tokyo availability](https://greencloudvps.com/billing/aff.php?aff=6679)

## Who should skip GreenCloud Japan entirely

Honest limits, so you can self-select before checkout:

- **You need Windows.** All Japan plans are Linux-only. No workaround listed on the product pages.
- **You need a refund window.** Every Tokyo plan is final sale. If you want the option to change your mind, a provider with a money-back guarantee fits better.
- **You need guaranteed CPU.** Fair-share cores on the Premium line and documented overselling on the Storage line make GreenCloud the wrong tool for sustained heavy compute. The CN Premium line on EPYC Milan is a step up in class but was out of stock at our last check.
- **You're Telecom-heavy and eyeing the IIJ line.** Published route data flagged Telecom performance on IIJ as the weak spot. SoftBank or CN Premium are the sane picks for Telecom users — and if CN Premium is out of stock, SoftBank is the fallback.
- **You want daily backups on the cheap lines.** Only the CN Premium line includes daily backups; the sale lines give you one snapshot slot and that's it.

## Quick answers

**Is GreenCloud Japan VPS good for China users?**
It depends entirely on the line. The SoftBank line routes all three major Chinese carriers via SoftBank with no standout bad carrier in published tests; the IIJ line routes everything via IIJ and tested poorly for Telecom. For guaranteed China-optimized routes (CN2GIA/CU PREMIUM/CMIN2), the CN Premium Tokyo line is the purpose-built option, but check stock — it has run zero-available recently.

**Can I get a refund if I don't like it?**
No. Every Japan plan, on every line, is marked non-refundable on the order page. Use the published test IPs (103.201.131.131 for SoftBank, 91.200.242.41 for IIJ) to validate your route before paying.

**What can I realistically run on a $25/year Tokyo plan?**
Light web hosting, proxy endpoints, personal git or VPN boxes, small bots, and file/media storage (especially on the Storage KVM tiers). Published benchmarks show shared-CPU contention under load, so sustained compute and busy databases are the wrong fit.

**Are the plans oversold?**
Third-party CPU benchmark data on the Storage KVM line indicates overselling is noticeable, which is expected at this price tier and consistent with the fair-share CPU designation on the Premium plans. It's a reasonable trade for a $25/year machine, as long as your workload tolerates variable CPU performance.

**Do prices jump at renewal?**
The company has publicly committed to honoring existing renewal rates without surprise hikes, announced alongside its 13th birthday sale. Historically its sale pricing has also been multi-year (the 2025 batch ran $66–$112 across two- and three-year terms), so the cheap rate is designed to stick.

## Before you click order

Match the plan to your situation: light web hosting or a proxy endpoint → the $25/year Premium KVM entry tier on whichever line passed your route test. Bulk storage or media → Storage KVM, sizing up only as far as your traffic needs actually require. Telecom-heavy China connectivity → SoftBank line today, CN Premium when it restocks. Monthly flexibility over savings → KVMJP-2 at $10/month, knowing it costs nearly five times the annual rate over a year.

Two last checks before payment: confirm the order page still shows the spec list and stock count you expect, since sale batches rotate without notice — and remember that during the birthday window, orders over $500 qualify for the 13% cashback only if paid by October 30 and claimed by ticket before November 5. 👉 [Browse GreenCloud's full Tokyo lineup and current stock](https://greencloudvps.com/billing/aff.php?aff=6679)
