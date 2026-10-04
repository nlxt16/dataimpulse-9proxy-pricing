# DataImpulse pricing: what every proxy type actually costs, where the per-GB rate quietly doubles, and when 9Proxy's pay-per-IP model wins

Most people typing "DataImpulse pricing" into a search bar want one of three answers: the real per-gigabyte number, whether some tier is cheaper than the headline rate, or whether they can find a coupon that knocks the price down further. DataImpulse makes the first one easy. The other two need a bit more digging, because the published $1/GB floor is only the floor for one specific setup.

Here's what the plans cost, which features push the effective rate up, and where a different billing model (pay per IP with unlimited bandwidth, which is what 9Proxy does) turns out cheaper for the same job.

## How DataImpulse bills: pay-as-you-go, no subscription, traffic that doesn't expire

DataImpulse sells proxy traffic, not monthly seats. You buy a block of gigabytes, the balance sits in your account, and it decreases as you use it. Nothing resets at the end of a month, and unused data doesn't vanish.

Key terms to know before you calculate anything:

- Billing model: pay-as-you-go, per GB
- Minimum purchase: $5, which buys 5 GB of residential, 10 GB of datacenter, 2.5 GB of mobile, or 1 GB of premium residential
- Expiry: purchased traffic does not expire
- Free trial: none. Every type of access starts with a paid minimum
- Refunds: Intro plans purchased by card carry a 7-day money-back guarantee, provided you've consumed less than 80% of the traffic. Crypto purchases on Intro plans aren't refundable

> If you were counting on a free trial to test success rates against a hard target, that doesn't exist here. The $5 entry pack is the test.

Country targeting is included at no extra cost across all four proxy types. HTTP/HTTPS and SOCKS5 are both supported, sessions can rotate per request or hold sticky, and the advertised pool is 90M+ IPs across 195 countries.

## DataImpulse residential proxy pricing

This is the tier most buyers land on. The ladder is short, and the discount only arrives once you get to a terabyte.

| Plan | Traffic | Price | Effective rate |
| --- | --- | --- | --- |
| Intro | 5 GB | $5 | $1.00/GB |
| Basic | 50 GB | $50 | $1.00/GB |
| Advanced | 1 TB | $800 | $0.80/GB |
| Custom | 5 TB+ | Quote-based | Negotiated |

The important thing about that table: Intro and Basic cost the same per gigabyte. Buying 50 GB doesn't get you a discount, it just means you're paying for ten intro packs at once. The 20% break appears at 1 TB and above, or through a negotiated custom quote at 5 TB+.

## Datacenter, mobile, and premium residential pricing

Each proxy type has its own ladder with the same structure, and each has a different floor.

| Proxy type | Intro | Basic | Advanced (1 TB) | Custom |
| --- | --- | --- | --- | --- |
| Datacenter | 10 GB / $5 ($0.50/GB) | 100 GB / $50 ($0.50/GB) | $450 ($0.45/GB) | 5 TB+, quote |
| Mobile | 2.5 GB / $5 ($2.00/GB) | 25 GB / $50 ($2.00/GB) | $1,600 ($1.60/GB) | 5 TB+, quote |
| Premium residential | 1 GB / $5 ($5.00/GB) | 10 GB / $50 ($5.00/GB) | Not published | 5 TB+, quote |

Two things worth noticing here. Datacenter is the only type where the $5 pack gets you more traffic than the residential equivalent, and mobile costs twice what residential does per gigabyte. Premium residential is a completely different price universe at $5/GB, aimed at buyers who need a filtered pool and a dedicated account manager rather than the cheapest possible bytes.

## The three multipliers that change your real per-GB cost

The headline rate is only accurate if your workload happens to match the assumptions behind it. Three details move the number.

**Advanced geo-targeting doubles the residential rate.** Country selection is free. Once you filter by state, city, ZIP, or a specific ASN on standard residential plans, that traffic bills at 2× the normal rate. If you're running city-level price checks or ZIP-level ad verification, your effective cost isn't $1/GB, it's $2/GB. Datacenter plans are documented as including those filters without the surcharge, so if your targets tolerate datacenter IPs, that's the cheaper route.

**Sticky sessions are capped.** Residential sticky sessions run on a limited window (roughly 30 minutes by default, on ports in the 10000–20000 range), not for hours. Workflows that need the same IP tied to a login for a long session will burn through rotations faster than the per-GB math suggests.

**Volume discounts kick in late.** The first real discount lands at the 1 TB tier, and mobile and premium residential don't get meaningful price breaks until 1 TB either. Anyone consuming 20–100 GB a month pays list price forever.

## Is there a DataImpulse promo code?

No. Multiple coupon-tracking pages that cover the provider report the same thing: no public promo code exists, and there hasn't been one to hand out. The $5 intro pack is the standing entry offer, and $1/GB is already below what most competitors charge even during their promotions.

So if a "DataImpulse coupon 2026" page tells you to copy a code at checkout, you're looking at filler content. There's nothing to redeem.

What that also means: the pricing you see is the pricing. There's no first-month discount to wait for, and no reason to time a purchase around a sale. The one lever you control is volume, and it only matters above 1 TB.

## Where per-GB billing is the wrong shape entirely

Everything above assumes your cost driver is traffic. For a lot of real workflows, it isn't.

If you're running long-lived sessions with heavy data transfer, or keeping the same IP attached to an account for hours at a time, metered billing punishes you for something you can't avoid. Every megabyte counts against the balance, and the session-length limits create their own workarounds.

That's the gap 9Proxy built its pricing around: pay per IP, not per gigabyte, with unlimited bandwidth attached to each IP. Buy 100 IPs for $24 and the traffic those IPs push doesn't add to the bill.

👉 [Check 9Proxy's current IP-based packages and start with 100 IPs](https://bit.ly/9-Proxy)

The trade-off is the mirror image of DataImpulse's. You get predictable, flat costs and no anxiety about bandwidth, but you're paying per IP rather than per byte, which only makes sense if you actually use the bandwidth. It's also residential-only: the lineup documented by 9Proxy covers residential proxies sold by IP, by GB, or as bundles, with no mobile or datacenter products alongside them. If you specifically need 4G/5G carrier IPs, DataImpulse's mobile tier is the relevant comparison and 9Proxy isn't in that race.

## 9Proxy pricing: the full package list

9Proxy adjusts IP-based and bundle pricing periodically, and the GB-based ladder has stayed put. The numbers below are the currently published rates.

### Residential proxies by IP (unlimited bandwidth per IP)

| Package | Total price | Per IP |
| --- | --- | --- |
| 100 IPs | $24 | $0.24 |
| 500 IPs | $72 | $0.144 |
| 1,000 IPs (+500 bonus) | $126 | $0.084 |
| 2,500 IPs | $210 | $0.084 |
| 5,000 IPs | $360 | $0.072 |
| 15,000 IPs | $720 | $0.048 |
| 25,000 IPs | $863 | $0.035 |
| 50,000 IPs | $1,438 | $0.029 |
| 100,000 IPs (Business) | $2,300 | $0.023 |
| 200,000 IPs (Business) | $4,140 | $0.021 |
| 500,000 IPs (Business) | $8,625 | $0.018 |

👉 [Buy a 9Proxy IP package with unlimited bandwidth](https://bit.ly/9-Proxy)

Unused IPs don't expire. Each IP stays naturally active for a few hours up to roughly 24 hours, and setup for this model runs through the 9Proxy desktop app with local port forwarding.

### Residential proxies by GB

| Package | Total price | Per GB | Validity |
| --- | --- | --- | --- |
| 5 GB | $15 | $3.00 | 180 days |
| 50 GB (+5 GB bonus) | $105 | $2.10 | 180 days |
| 100 GB | $150 | $1.50 | 180 days |
| 200 GB | $200 | $1.00 | 180 days |
| 1,000 GB | $800 | $0.80 | 180 days |
| 2,000 GB | $1,500 | $0.75 | 180 days |
| 3,000 GB (Enterprise) | $2,160 | $0.72 | Unlimited |
| 6,000 GB (Enterprise) | $4,200 | $0.70 | Unlimited |
| 10,000 GB (Enterprise) | $6,800 | $0.68 | Unlimited |

The GB-based model works straight from the dashboard. You generate as many endpoints as you want, pick sticky or rotating sessions, authenticate by username/password or IP whitelist, and filter by country, state, city, ZIP, or ISP. Enterprise packages drop the 180-day validity window entirely, add team mode (one owner plus up to five members), per-member traffic controls, and activity logs.

### Bundle packages

| Bundle | Contents | Price |
| --- | --- | --- |
| Starter | 100 IPs + 5 GB | $30 |
| Popular | 1,500 IPs + 50 GB | $180 |
| Pro | 5,000 IPs + 500 GB | $720 |

👉 [Compare 9Proxy's bundle packages against buying separately](https://bit.ly/9-Proxy)

## The two pricing models, side by side

Here's where the numbers actually diverge, using the published rates for both providers.

| Volume | DataImpulse residential | 9Proxy GB-based |
| --- | --- | --- |
| 5 GB | $5 | $15 |
| 100 GB | $100 | $150 |
| 200 GB | $200 | $200 |
| 1,000 GB | $800 | $800 |
| 10,000 GB | Quote-based | $6,800 ($0.68/GB) |

At small volumes, DataImpulse is the cheaper buy by a clear margin. At 200 GB and 1 TB, the two are effectively identical. Above that, 9Proxy's published ladder keeps going while DataImpulse shifts to negotiation.

But the more interesting comparison isn't the GB ladder at all. Take a workload that pushes 400 GB of traffic through 50 stable IPs over a month:

- DataImpulse residential: 400 GB × $1 = $400, and that's before any advanced targeting surcharges
- 9Proxy IP-based: 50 IPs at $0.144/IP = $7.20, bandwidth included

Same traffic, wildly different invoices. That's not a knock on DataImpulse's pricing, it's a difference in what each provider is charging for. Metered billing assumes light traffic spread across many IPs. Per-IP billing assumes heavy traffic concentrated on a few stable ones.

There's a real expiry difference too. DataImpulse traffic never expires at any tier. 9Proxy's GB packages carry a 180-day window unless you're on Enterprise, where validity becomes unlimited. If you buy in bulk and consume slowly, that's a genuine consideration rather than a footnote.

## Which one to pick

**Small, exploratory, mixed-target work.** DataImpulse's $5 intro pack. You get 5 GB of residential, 10 GB of datacenter, or 2.5 GB of mobile for the price of lunch, and nothing expires while you decide. Datacenter at $0.50/GB is the cheapest way to test whether your targets tolerate non-residential IPs at all.

**Long sessions, heavy transfers, IP stability.** 9Proxy's IP-based packages. Paying per IP instead of per gigabyte removes the bandwidth variable completely, and unused IPs don't expire. Its limited new-user trial, when available, is a low-risk way to test the session quality before committing to a larger tier.

**High-rotation scraping with small payloads per request.** Both work, and the tie-breaker is targeting cost. DataImpulse charges 2× for city/ZIP/ASN filters on residential, so a rotation-heavy job that needs fine geo-precision can quietly double. 9Proxy's country/state/city/ZIP/ISP filters are part of the GB packages as documented, with no per-filter multiplier mentioned.

**Teams and agencies.** 9Proxy's Enterprise packages are the ones built for this: shared bandwidth across five members, per-member controls, no expiry on shared traffic. DataImpulse routes enterprise needs to a custom quote.

**Mobile IPs.** DataImpulse, at $2/GB. That's the cheapest published mobile rate among the providers covered in the pricing roundups, and it's the tier where its advantage is widest.

## FAQ

**Does DataImpulse have a free trial?**
No. Access starts at a $5 minimum purchase. Card purchases on Intro plans come with a 7-day money-back guarantee if less than 80% of the traffic has been used; crypto purchases on those plans aren't refundable.

**Do DataImpulse credits expire?**
No. Balances stay in your account and drain only as you use them, at every tier.

**What's the cheapest way to start?**
$5 buys 5 GB of residential, 10 GB of datacenter, 2.5 GB of mobile, or 1 GB of premium residential. The datacenter pack gives you the most test traffic per dollar.

**Is 9Proxy cheaper than DataImpulse?**
On raw per-GB at low volume, no. At 200 GB and 1 TB the two are level. For bandwidth-heavy work on a fixed set of IPs, 9Proxy's per-IP model is dramatically cheaper because traffic isn't billed at all. Compare it against your own usage pattern rather than the headline rate.

**Can I mix both?**
Plenty of teams do. Per-GB for high-rotation jobs where each request pulls little data, per-IP with unlimited bandwidth for the long-haul accounts that would otherwise rack up metered costs.

👉 [Open a 9Proxy account and price out the IP-based model for your workload](https://bit.ly/9-Proxy)

## The short version

DataImpulse pricing is simple until it isn't. The published $1/GB is real, and traffic genuinely never expires, but advanced geo-targeting doubles the residential rate, sticky sessions are capped, and the first volume discount doesn't arrive until 1 TB. There are no coupon codes to hunt for, and no free trial to test with. The $5 entry pack is the whole experiment.

If your workload is light traffic across many rotating IPs, that pricing is close to unbeatable at the entry level. If your workload is heavy traffic across a handful of stable IPs, you're paying per gigabyte for something you could be buying per IP with unlimited bandwidth included, and that's the situation 9Proxy's model is priced for.

Pick based on which line item actually grows when your project scales. That's the answer to the pricing question, regardless of what the per-GB headline says.
