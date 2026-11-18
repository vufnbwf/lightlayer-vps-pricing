# VPS promo code: does it still work, what does year two cost, and which LightLayer plan do you actually need? (full plan table + checkout checklist)

LightLayer has no publicly verifiable coupon code live right now, and pages claiming one exists are guessing. What actually lowers the bill is the billing cycle: the entry 1-core plan lists at **$4.00/month** on monthly billing but **$24.99/year** in Manila or Taiwan, roughly $2.08 a month. That gap, not a code box, is where the savings sit.

The other thing worth knowing before you shop: the 11.11 flash sales still running at several hosts expire tonight, 13 November, on **GMT+8**, and the 50%-off-yearly window I looked at in October has already closed. Promo pages age badly. The plan details and prices below are LightLayer's, and I have flagged where a price depends on location rather than a fixed list.

> **Most readers should take the 1-core / 1GB / 50GB plan on annual billing.** It runs $24.99/year in Manila or Taiwan, and $29.99 to $49.99/year in Los Angeles depending on which network route you pick. That covers a small site, a VPN endpoint, a bot, or a dev box. Move to the 4-core / 4GB tier only when a database or several containers share the machine, and to the 32-core tier only if you are reselling or running nested virtualization. 👉 [See the current LightLayer plans and prices](https://account.lightlayer.net/?affid=74)

## LightLayer's VPS plans and prices

LightLayer prices its VPS line through a configurator rather than a single static list, so the number in the cart moves with location, network route, and resources. The tiers below are the entry configurations currently quoted in plan listings (updated 24 October 2026); treat the cart as the final word on any specific build.

| Plan | CPU / RAM | Storage | Network | Starting price | Order |
| --- | --- | --- | --- | --- | --- |
| Startup | 1 core / 1GB | 50GB SSD | 100Mbps, unlimited | **$4.00/mo** | [Start here](https://account.lightlayer.net/?affid=74) |
| Pay As You Go | 2+ cores / 2GB+ | Scalable | 200Mbps+ | From **$5.60/mo** | [Configure resources](https://account.lightlayer.net/?affid=74) |
| Mid-tier | 4 cores / 4GB | 80GB SSD | 200Mbps, unlimited | **~$11–18/mo** | [Check mid-tier pricing](https://account.lightlayer.net/?affid=74) |
| Business | 32 cores / 32GB | Scalable | 200Mbps, unlimited | **$53.60/mo** | [See the high-core plan](https://account.lightlayer.net/?affid=74) |

The annual entry plan is the same 1-core / 1GB / 50GB build, priced by location:

| Location | Specs | Annual price | Order |
| --- | --- | --- | --- |
| Manila | 1 core / 1GB / 50GB SSD | **$24.99/yr** | [Take the Manila annual plan](https://account.lightlayer.net/?affid=74) |
| Taiwan | 1 core / 1GB / 50GB SSD | **$24.99/yr** | [Take the Taiwan annual plan](https://account.lightlayer.net/?affid=74) |
| Los Angeles (Global route) | 1 core / 1GB / 50GB SSD | **$29.99/yr** | [Check the LA annual price](https://account.lightlayer.net/?affid=74) |
| Los Angeles (Standard) | 1 core / 1GB / 50GB SSD | **$39.99/yr** | [Compare LA routes](https://account.lightlayer.net/?affid=74) |
| Los Angeles (Premium) | 1 core / 1GB / 50GB SSD | **$49.99/yr** | [See the premium-route plan](https://account.lightlayer.net/?affid=74) |

Three Los Angeles prices for identical specs is not a pricing error. The route differs, and route is the whole product when your users sit in Asia and the server sits in California.

LightLayer also publishes a dedicated-server line on its own pricing page. These are physical machines, not VPS, and they are listed here so you can see where the ceiling is:

| Configuration | Cores / RAM | Storage | Port | Price | Order |
| --- | --- | --- | --- | --- | --- |
| 2× AMD EPYC 7742 | 64 cores / 256GB | 2×240GB SSD + 2×4TB NVMe | 10Gbps, standard | **$9,230/mo** | [View dedicated configs](https://lightlayer.net/pricing-cs?affid=74) |
| Dual Intel E5-2696v4 | 44 cores / 128GB | 2TB SSD | 10Gbps, standard | **$8,630/mo** | [View dedicated configs](https://lightlayer.net/pricing-cs?affid=74) |
| 2× AMD EPYC 7502 | 64 cores / 256GB | 2×240GB SSD + 2×4TB NVMe | 100Mbps, premium | **$900/mo** | [View dedicated configs](https://lightlayer.net/pricing-cs?affid=74) |
| Dual Intel E5-2660 | 16 cores / 64GB | 1TB SSD | 50Mbps, premium | **$150/mo** | [View dedicated configs](https://lightlayer.net/pricing-cs?affid=74) |

All four include 5 IPs, unlimited data transfer, and upgrades on request.

## The three things hosts call a "promo code"

Every VPS promotion you will see this month is one of three products, and they cost you very different amounts over time.

**A first-invoice discount.** The code takes a percentage off the first payment only. Renewal returns to list price. A first-month-only offer is the most common shape and the least valuable if you plan to keep the server.

**A recurring discount.** The percentage applies to every invoice, including renewals, for as long as you stay on the qualifying billing cycle. One host's October page stated plainly that its 50% discount was "recurring and permanent for eligible yearly VPS plans." That is the version worth chasing, provided the renewal line on your invoice confirms it.

**A resource bonus.** No money off; you get extra RAM, an extra vCPU, or doubled transfer. These usually require a specific purchase date and a support ticket after provisioning, and they are capped at one bonus per server. A host running an 11.11 sale right now gives double transfer to every eligible plan but limits its 11% discount to two plan families, new purchases only, with renewals excluded.

LightLayer's current offers fall into none of these three cleanly, because there is no published code at all. The discount is structural: annual billing versus monthly.

## Year one versus year two, with real numbers

Take LightLayer's cheapest build and run the arithmetic both ways.

- Monthly billing: $4.00 × 24 months = **$96.00** over two years.
- Annual billing: $24.99 × 2 = **$49.98** over two years.

Same specs, same provider, **$46.02 difference**, because the annual rate is a permanent rate rather than a first-term teaser. Nothing to paste at checkout, nothing to remember before renewal.

That only holds if you keep the server for the full twelve months. The refund policy is the reason to think hard here: refunds are issued for provider-side faults only, and regular-priced as well as promotional products are excluded from change-of-mind refunds. Abandon an annual plan after two months and you have paid $24.99 for eight weeks of use, which is worse than $8.00 on monthly billing.

On renewal specifically, third-party trackers report that LightLayer's promotional rates have held at renewal rather than doubling. That is a report, not a contract term. Before you prepay, check the renewal amount shown in the cart or ask support in writing what year two costs on the plan you are buying.

## Which tier fits, and which ones to skip

**A single small site, a proxy, a VPN endpoint, a Telegram bot, a staging box.** The 1-core / 1GB plan is enough. 50GB of SSD and 100Mbps unmetered covers a low-traffic WordPress install or a WireGuard server without drama. Buy annual if you are confident about twelve months, monthly at $4.00 if you are not.

**A production app with a database, or a handful of Docker containers.** The 4-core / 4GB tier, around $11–18/mo, is the sane floor. Databases are the thing that punishes 1GB of RAM, and swapping on a shared box is slow in a way you will notice.

**You need 32 cores and 32GB.** Only if you are reselling slices, running CI, or virtualizing. A blog will never touch it, and $53.60/mo buys a lot of managed hosting instead.

**You need guaranteed CPU and full disk I/O.** Skip the VPS line entirely. That is what the dedicated table above is for, and the $150/mo dual E5-2660 with 64GB is the realistic entry point for workloads that cannot tolerate noisy neighbours.

One more honest note on fit: LightLayer is a smaller provider with data centers across Hong Kong, Taiwan, Japan, Thailand, Singapore, the Philippines, the US, the UK and Germany, and it runs KVM on AMD EPYC with NVMe storage. Smaller providers are where you find sub-$3 monthly rates and Asian routes that big clouds charge more for. They are also where you should keep your own backups and not assume an SLA you haven't read.

## Test on monthly before you commit to a year

The $4.00 monthly plan is the cheapest test available for this provider, and the refund policy makes it the only sensible one. Run it for a billing cycle. Check the route latency from where your users actually are, confirm the disk performance your workload needs, and read the renewal figure in the billing area.

👉 [Start with one month at $4.00](https://account.lightlayer.net/?affid=74) and upgrade to annual once you know the plan is right.

Payment is by PayPal and credit card. Confirm the method you intend to use on the order page, because gateway fees, where they exist, are added on top and vary by method.

## Checkout checklist before you paste any VPS promo code

The traps are nearly identical across providers. Run through this list whether you end up at LightLayer or somewhere else.

1. **New purchase or renewal?** Many codes are explicitly new-customer or new-service only. An existing server being renewed will silently ignore the code and charge full price.
2. **Does it require annual billing?** Half the "50% off" offers in the market only trigger when the cycle is set to twelve months. A monthly cart will show the discount failing.
3. **Which plans are excluded?** Discounts get limited to specific plan families while the rest of the catalogue gets only the add-on, or nothing.
4. **Is a ticket required after payment?** Resource bonuses are frequently manual. You buy, then open a ticket with the IP and invoice number, and pick one bonus. One per server, no stacking of vCPU plus RAM plus transfer.
5. **Which timezone does the deadline use?** Asian hosts commonly run promotions on GMT+8. A sale ending "13 November" closes at 16:00 UTC on the 12th, which is morning of the 13th in Europe and the middle of the night on the US west coast. Today's deadlines are GMT+8 deadlines.
6. **What does the order total actually show?** Apply the code, then read the final number and the renewal number. If the discount isn't visible in the total, it didn't apply, and support cannot always fix it afterwards.

## FAQ

**Can I stack a promo code with annual pricing at LightLayer?**
There is no published LightLayer code to stack. The annual rate is already the discounted rate, at about half the monthly effective price on the entry plan.

**Will my renewal price go up?**
The annual rate is a rate, not a first-term promotion, and third-party trackers report renewal pricing on promotional plans has held. Verify the renewal amount in the cart for the specific plan and location you choose, since Los Angeles routes already differ by $20/year.

**Do the 11.11 sales end at local midnight?**
No. The ones closing today close on GMT+8, Singapore time. If you are in New York or Berlin, the deadline lands earlier than the date suggests.

**Do I need to open a ticket to get a bonus?**
At providers that offer resource bonuses, usually yes. At LightLayer there is no bonus programme to claim; the value sits in the billing cycle.

**Can I get a refund if the server isn't right for me?**
LightLayer's stated policy covers provider-side faults only, and excludes regular-priced and promotional products from other refunds. Budget one monthly cycle as your trial rather than planning to reverse an annual charge.

## The decision, in one pass

Running a small site, a proxy, or a dev box and you'll keep it a year: **1-core / 1GB annual**, $24.99 in Manila or Taiwan, $29.99 in Los Angeles on the global route. Running an app with a database: **4-core / 4GB**, and pay monthly until you've confirmed it handles the load. Running anything that needs dedicated cores: the **$150/mo dual E5-2660** is the entry point, and no VPS tier substitutes for it.

Two things to confirm before you pay. Read the **renewal amount**, not just the first invoice, and check the **location and route**, because the same specs carry three different annual prices in Los Angeles. If your answer to "will I still need this in twelve months" is anything less than confident, take the monthly plan and keep your options open.

👉 [Compare the full LightLayer plan list and current prices](https://account.lightlayer.net/?affid=74)
