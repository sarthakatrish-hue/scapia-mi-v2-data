---
subject: "NPCI"
type: subject
role: regulatory
domains: [fintech]
categories: [upi]
domain_url: npci.org.in
logo: null
issuer: null
keywords: [upi, payments, transaction-limits, two-factor-authentication, upi-lite, cross-border, global-expansion, ai-assistant, epfo, verified-name, digital-payments, project-nexus, market-share-cap, interchange-fees, operational-guidelines, two-factor-authentication]
signal: opportunity
headline: "'UPI 2FA mandate, 30% market-share cap extension and new category limits reshape rails for 2026'"
vitals: []
last_updated: 2026-06-25
---

## What we know

**30% UPI share cap extended** — NPCI extended the single-app 30% market-share cap deadline to 31 December 2026, giving PhonePe and Google Pay more time while allowing smaller apps to scale[^upi-rules-2026-06-25]
**Travel category gets ₹5L limit** — Travel UPI transactions now carry a ₹5 lakh per-transaction and ₹10 lakh per-day enhanced limit, effective 15 September 2025[^upi-rules-2026-06-25]
**Interchange fees on wallet-UPI** — UPI via prepaid wallets carries merchant-side interchange of 0.5%–1.1%; peer-to-peer and direct bank UPI remain free for users[^upi-rules-2026-06-25]
**AutoPay restricted to off-peak hours** — Recurring UPI mandates (subscriptions, EMIs) may only execute outside peak hours; up to 3 retries permitted per payment[^upi-rules-2026-06-25]
**International QR must be live-scanned** — From April 2025, international UPI payments require real-time in-person QR scanning; saved or shared QR codes abroad are disallowed[^upi-rules-2026-06-25]
**Recipient bank name mandatory** — UPI apps must display the recipient's bank name before payment confirmation to reduce misdirected transfers[^upi-rules-2026-06-25]
**Linked-account view capped** — Users can request their linked bank account list only 25 times per app per day; excessive attempts trigger a temporary block[^upi-rules-2026-06-25]

## Regulatory Intel

**Status:** Active — operational guidelines effective 1 August 2025; enhanced category limits effective 15 September 2025; 2FA mandate effective 1 April 2026; market-share cap extended to 31 December 2026[^upi-rules-2026-06-25]

**What it requires:** Two-factor authentication with at least one dynamic element (biometric or secure in-app approval) for all domestic digital payments; balance checks capped at 50/day; linked-account lookups capped at 25/day; transaction-status polling limited to 3 attempts with 90-second gaps; recipient bank name displayed pre-confirmation; recurring payments restricted to off-peak windows; live QR scanning required for international payments; compliance failures attract API access restrictions and onboarding bans[^upi-rules-2026-06-25]

**Posture:** Security-hardening plus utility-expansion — NPCI is simultaneously tightening fraud controls (2FA, live-QR rule, recipient bank display), managing systemic load (API rate caps, off-peak AutoPay), raising limits for productive categories (travel, capital markets, insurance), and extending the market-share cap to preserve ecosystem diversity[^upi-rules-2026-06-25]

**Implication:** The travel category's ₹5 lakh per-transaction / ₹10 lakh per-day limit is directly relevant to Scapia's core use-case — high-value flight and hotel bookings on UPI are now fully supported within the rail, reducing friction for users who might otherwise default to a card. The live-QR rule for international payments limits the abuse vectors NPCI is worried about, but also confirms UPI's intent to deepen global acceptance in a controlled way, reinforcing Scapia's zero-forex proposition. Interchange on wallet-UPI (0.5–1.1%) creates a cost asymmetry that keeps pure UPI less attractive for merchants at scale versus card rails where rewards fund engagement — a structural advantage for Scapia's card model [Inferred · Medium][^upi-rules-2026-06-25].

## Coverage

### UPI Market-Cap Extended, Travel Limits Raised — 2026-06-25

NPCI and RBI have released a consolidated set of 2026 UPI rule updates covering operational limits, enhanced category thresholds, and the 2FA mandate[^upi-rules-2026-06-25]. The most commercially significant change for Scapia's market is the travel category receiving an enhanced ₹5 lakh per-transaction and ₹10 lakh per-day limit from 15 September 2025, putting high-value trip payments firmly within UPI's reach. The 30% single-app market-share cap deadline has been pushed to 31 December 2026, extending a compliance runway that primarily benefits PhonePe and Google Pay — together holding over 85% of UPI volume — while smaller apps gain more time to compete[^upi-rules-2026-06-25].

The operational guidelines (effective 1 August 2025) introduce API rate limits — 50 balance checks and 25 linked-account lookups per app per day — alongside AutoPay off-peak scheduling and a 3-poll cap on pending transaction status checks[^upi-rules-2026-06-25]. These are system-stability measures rather than user-facing friction, but they signal NPCI tightening the rails as transaction volumes scale. For Scapia, the interchange framework is worth watching: wallet-based UPI now carries 0.5–1.1% merchant interchange, structurally favouring card rails — where rewards fund engagement — over wallet-UPI for discretionary spend [Inferred · Medium][^upi-rules-2026-06-25].

### UPI 2026 Scale and Rule Overhaul — 2026-06-24

UPI crossed 500 million unique users and 21 billion monthly transactions by early 2026, cementing its position as the world's most dominant real-time payments system[^upi2026-jun24]. NPCI has layered in a raft of rule changes: mandatory two-factor authentication with a dynamic element from April 2026, a 50-balance-check-per-day API cap to prevent system overloads, verified bank-registered names on all transactions, and expanded daily limits up to ₹10 lakh for verified categories such as tax, education, and healthcare[^upi2026-jun24]. UPI Lite now supports offline payments up to a ₹5,000 total limit, targeting rural and low-connectivity users.

The global expansion story is accelerating[^upi2026-jun24]: UPI is live or agreed in 12+ countries, with NPCI connecting UPI to Cambodia's Bakong KHQR network on 3 June 2026 and an India-Israel bilateral agreement signed in February 2026; Project Nexus — linking multiple countries' fast-payment systems — is expected live this year. For Scapia, the international reach is the most material angle: as UPI acceptance grows abroad, outbound Indian travelers gain a local-currency payment option, reinforcing Scapia's zero-forex positioning and the case for a travel-first card that bridges both rails[^upi2026-jun24] [Inferred · Medium].

### NPCI Verified Names, EPFO UPI Withdrawals — 2026-06-24

NPCI is rolling out a verified-name display requirement for UPI transactions in June 2026: whenever a user scans a QR code or enters a mobile number, apps must show the bank-registered name of the recipient rather than any custom alias[^npci-jun2026]. The move is designed to close a common fraud vector where scammers use lookalike display names to deceive payers.

Simultaneously, EPFO has completed testing of instant provident fund withdrawals via UPI, with Union Labour Minister Mansukh Mandaviya confirming members will soon be able to withdraw EPF balances directly into their bank accounts through UPI[^npci-jun2026]. Taken together, these two developments expand UPI's utility and trustworthiness — a structural tailwind for any fintech building on top of the UPI rail.

## Developments

- 2026-06-25 — UPI Market-Cap Extended, Travel Limits Raised [^upi-rules-2026-06-25]
- 2026-06-24 — UPI 2026 Scale and Rule Overhaul [^upi2026-jun24]
- 2026-06-24 — NPCI Verified Names, EPFO UPI Withdrawals [^npci-jun2026]

## Sources

[^npci-jun2026]: raw/ambiguous/major-banking-tax-upi-transaction-rule-changes-kicking-in-from-june-2026-key-poi.md
[^upi2026-jun24]: raw/ambiguous/upi-payments-in-2026-new-features-transaction-limits-future-of-digital-india.md
[^upi-rules-2026-06-25]: raw/ambiguous/upi-payment-new-rules-2026-transaction-limits-guidelines.md
