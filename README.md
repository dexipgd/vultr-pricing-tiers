# Vultr cost: what does the $2.50 plan actually bill, and which tier fits a blog, an app or a database? (full price table plus the add-ons that change the total)

Vultr's Regular Performance line starts at **$2.50 a month**, and that plan is IPv6-only. Add an IPv4 address and the entry price becomes **$3.50**. The three plans most people actually buy are 1 GB at **$5**, 2 GB at **$10** and 4 GB at **$20**, billed by the hour with a monthly cap of 672 hours, and they renew at the same price rather than jumping in month two.

What follows is every plan Vultr lists, then the parts of the bill that never appear on the plan card: backups, snapshots, extra IPv4 addresses, Windows licences, and servers you powered off but never destroyed.

> For one WordPress site with MySQL, the **2 GB / 1 vCPU plan at $10 a month** is the smallest size that won't run out of memory under load. For a static site, a cron box or a VPN endpoint, the **1 GB at $5** is enough.
> 👉 [See the full plan list and per-location prices](https://www.vultr.com/pricing/?ref=9738262-9J)

## Every Vultr plan and what it costs

| Plan | Specs (RAM · vCPU · disk · traffic) | Price/month | Billing | Order |
| --- | --- | --- | --- | --- |
| Regular 0.5 GB (IPv6 only) | 0.5 GB · 1 · 10 GB SSD · 500 GB | $2.50 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 0.5 GB (IPv4) | 0.5 GB · 1 · 10 GB SSD · 500 GB | $3.50 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 1 GB | 1 GB · 1 · 25 GB SSD · 1 TB | $5.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 2 GB | 2 GB · 1 · 55 GB SSD · 2 TB | $10.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 2 GB / 2 vCPU | 2 GB · 2 · 65 GB SSD · 3 TB | $15.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 4 GB | 4 GB · 2 · 80 GB SSD · 3 TB | $20.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 8 GB | 8 GB · 4 · 160 GB SSD · 4 TB | $40.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 16 GB | 16 GB · 6 · 320 GB SSD · 5 TB | $80.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 32 GB | 32 GB · 8 · 640 GB SSD · 6 TB | $160.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 64 GB | 64 GB · 16 · 1.3 TB SSD · 10 TB | $320.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Regular 96 GB | 96 GB · 24 · 1.6 TB SSD · 15 TB | $640.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 1 GB | 1 GB · 1 · NVMe · 2 TB | $6.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 2 GB | 2 GB · NVMe · 3 TB | $12.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Performance 4 GB | 4 GB · NVMe · 5 TB | $24.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| High Frequency 1 GB | 1 GB · 32 GB NVMe · 1 TB | $6.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Optimized, CPU (dedicated) | 1 dedicated vCPU · 2 GB · 25 GB NVMe · 4 TB | from $28.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Optimized, General Purpose | dedicated vCPU, more RAM per core | from $30.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Optimized, Memory | dedicated vCPU, high RAM ratio | from $40.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Optimized, Storage | dedicated vCPU, large NVMe | from $75.00 | Hourly, 672 h cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1, block-storage boot | 2 GB… 2 vCPU · 8 GB, no local disk | from ≈$43.80 + storage | Hourly, no cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1 2 vCPU | 8 GB · 120 GB NVMe · 5 TB | ≈$55.48 | Hourly, no cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1 4 vCPU | 16 GB · 240 GB NVMe · 6 TB | ≈$111.69 | Hourly, no cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1 8 vCPU | 32 GB · 480 GB NVMe · 7 TB | ≈$223.38 | Hourly, no cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| VX1 16 vCPU | 64 GB · 960 GB NVMe · 8 TB | ≈$446.76 | Hourly, no cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Bare Metal | 4 cores / 8 threads · 32 GB · 2 × 240 GB SSD · 5 TB | $120.00 | Monthly | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Cloud GPU | GPU instance, specs by card | from $344.00 | Hourly, no cap | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Managed Databases | MySQL, PostgreSQL, Kafka, Valkey | from $15.00 | Monthly | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Block Storage | attachable volume, NVMe at $0.10/GB | from $1.00 | Monthly | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| Object Storage | S3-compatible buckets | from $5.00 | Monthly | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |
| DDoS Protection | add-on per instance | $10.00 | Monthly | [ View plan](https://www.vultr.com/pricing/?ref=9738262-9J) |

VX1 figures are hourly rates converted at 730 hours, because VX1 is not capped. Vultr's Kubernetes Engine charges nothing for the control plane; you pay for worker nodes, block storage and load balancers.

## What gets added to the plan price

**Automatic backups cost 20% of the instance price.** A $10 server with backups enabled bills $12. Vultr's documentation states the base monthly and hourly fee rises by 20% when backups are on, so this applies to every size.

**Snapshots are $0.05 per GB per month.** A 55 GB snapshot of the 2 GB plan runs about $2.75 monthly for as long as you keep it.

**Bandwidth overage is $0.01 per GB, worldwide, and inbound traffic is free.** The allowances above look small next to Hetzner's 20 TB, but every account also gets **2 TB of free outbound transfer per month pooled across all instances and all locations**. A busy server can consume a quiet one's allowance, and most small accounts never see an overage line.

**Bandwidth is allocated by the hour.** Spin up a server for two weeks to move data and you get roughly half the listed allowance, not all of it.

**A powered-off server still bills.** Charges start at deploy and continue while the instance is stopped, because the RAM, disk and IP stay reserved. To stop paying you snapshot it and destroy it. That is also why a test box you forget about costs the same as one running production.

**The minimum charge is one hour.** Destroy an instance after 20 minutes and you pay for a full hour.

**The 672-hour cap is not universal.** Regular, High Performance, High Frequency and Optimized Cloud Compute stop charging at 672 hours, which is 28 days, so a server left running all month pays exactly the listed price. VX1 and GPU instances bill every hour of the month, which makes a 31-day month more expensive than a 30-day one.

**Extra IPv4 addresses cost extra**, with a limit of two per instance.

**Windows licences are separate from the server price.** Vultr's own documentation puts the add-on at **+$16 a month** on a $10 plan.

**Control panels are licensed separately.** cPanel starts at **$31.99 a month** for 5 accounts and Plesk at $13.99. CyberPanel, CloudPanel and Webmin add nothing.

**Some locations cost more than the list price.** Vultr prices certain regions above the base rate, so the number in the control panel for your chosen city is the one you'll actually be charged.

👉 [Check the current per-plan and per-location pricing](https://www.vultr.com/pricing/?ref=9738262-9J)

## Is the $2.50 IPv6-only plan usable?

Only for a narrow set of jobs. Anyone on an IPv4-only connection cannot reach it directly, and some package mirrors and APIs still resolve over IPv4 only. It works as a test box, or behind a proxy such as Cloudflare that accepts IPv4 visitors and connects to your origin over IPv6.

The other limit is memory. 0.5 GB will not run PHP and MySQL together on a modern stack, so the $2.50 plan is not a cheap WordPress host. Both entry plans are also restricted to a small number of locations, which rules them out if you need a specific city.

## Which tier fits your workload

**Static site, cron jobs, VPN, small API:** the 1 GB Regular at **$5** is the floor worth buying. The $0.007 hourly rate makes it cheap to keep a staging box around for a few hours.

**One WordPress site with MySQL:** the 2 GB Regular at **$10**. A November 2026 test of two Vultr-hosted WordPress sites measured a 32 ms median time to first byte with page caching on and 271 ms with it off. Under load without the cache, response times climbed to roughly 5,900–6,900 ms at 40–50 concurrent visitors, with no failed requests. That is the point where a bigger plan or a cache layer pays for itself.

**Database-driven app where disk latency shows up in queries:** High Performance at **$12** for 2 GB. Newer AMD EPYC or Intel Xeon plus NVMe costs about 20% more than Regular and includes more bandwidth at every size, and the AMD and Intel variants are priced the same.

**PHP, game servers, anything bound to a single core:** High Frequency at **$6** for 1 GB, with 3 GHz+ Intel CPUs and NVMe. Small sizes cost the same as High Performance but carry more disk and less bandwidth.

**Shared vCPU demonstrably the bottleneck:** VX1 from about **$43.80 a month** for 2 vCPU and 8 GB, booting from block storage and billed on actual hours, or Optimized Cloud Compute from **$28** for a dedicated vCPU. Both are five to eight times the price of the $5 plan. Move up only when monitoring shows steal time or sustained CPU wait, not because a benchmark looked better.

## Vultr vs DigitalOcean vs Hetzner on the same three sizes

| Size | Vultr Regular | Vultr High Performance | DigitalOcean Basic | Hetzner (EU) |
| --- | --- | --- | --- | --- |
| 1 GB | $5 (1 TB) | $6 (2 TB) | $6 (1 TB) | €6.49 CPX02 (20 TB) |
| 2 GB | $10 (2 TB) | $12 (3 TB) | $12 (2 TB) | €11.99 CPX12 (20 TB) |
| 4 GB | $20 (3 TB) | $24 (5 TB) | $24 (4 TB) | €5.99 CX23 (20 TB) |

Vultr's Regular line is $1 to $4 cheaper than DigitalOcean at each of these sizes, and High Performance matches DigitalOcean's price while including more transfer. Hetzner is far cheaper at 4 GB and bundles much more traffic, but it has restricted new cloud server orders since June 2026 and its cheapest plans are frequently sold out, so it isn't a dependable option when you need a server today.

## Who should not buy Vultr

Vultr sells unmanaged infrastructure. The instance is **entirely self-managed**: OS updates, firewall rules, the web server, PHP and WordPress problems are yours. If you want someone to fix a broken plugin, this is the wrong product.

Support runs **24/7 by ticket only**, through the control panel, email or a Slack app. No live chat, no phone. A November 2026 test submitted two low-priority tickets and got complete replies from the same agent after about 19.5 hours, which is fine for planning questions and slow for an outage.

There is **no refund window**. Payments are final and account credits cannot be cashed out, which matters if you prepay a year and change your mind. There is also no free tier and no free trial. New accounts get a promotional credit that requires a linked card or PayPal, is limited to one per user, and expires if unused. The amount depends on the current offer, so read the terms on the signup page rather than assuming a number.

Reviews split sharply. G2 reviewers rate it **4.3 out of 5** (April 2026), with praise centred on price, fast deployment and region coverage. On Trustpilot it sat at **1.5 from 589 reviews** as of October 27, 2026, with complaints about sudden account suspensions, verification requests after a deposit and slow ticket replies. Both are real; the pattern in the negative reviews is account verification and fraud checks rather than server performance, so complete verification before you deposit a large balance.

The uptime SLA promises **100% for the network and the host node**, with service credits: 12 hours for a short outage, up to a full month (672 hours) for an outage over 7 hours. You have to open a ticket to claim it. Scheduled maintenance announced 24 hours ahead is excluded, and GPU instances are excluded from the SLA entirely.

## FAQ

**Does the price go up on renewal?**
No. Vultr's cheapest tiers renew at the same rate as the first term, so the listed price is what you keep paying.

**Is there a free trial?**
No free plan and no trial period. Only the new-user promotional credit, which needs a card or PayPal, is limited to one per account, and expires.

**Am I charged for a server I shut down?**
Yes. Billing continues while the instance is stopped, because its CPU, RAM, disk and IP stay allocated. Destroy it to stop the charges.

**How much do backups add?**
20% of the instance price, so $12 instead of $10 on the 2 GB plan. Snapshots are separate at $0.05 per GB per month.

**Can I get a refund?**
No. Vultr has no money-back window and credits are non-refundable. Cancel at any time and the billing stops at the next hour.

**How do I claim the SLA credit?**
Open a support ticket and document the downtime. Credits are not automatic, and GPU instances and pre-announced maintenance are not covered.

## Before you order

Match the plan to the job rather than to the price list: a static site or a VPN needs only the **$5 / 1 GB** instance; one WordPress site with MySQL needs the **$10 / 2 GB**; a database-heavy app justifies the **$12 High Performance** for NVMe; dedicated CPUs only make sense once you can show shared vCPU contention, at **$28+** for Optimized or about **$43.80** for VX1.

Two things to confirm at checkout. First, the price shown for your chosen region, since some locations bill above the base rate. Second, the promotional credit terms on the signup page, because the credit expires and cannot be converted to cash.

👉 [Start with a 1 GB or 2 GB instance and see the exact price for your region](https://bit.ly/VuLtr)
