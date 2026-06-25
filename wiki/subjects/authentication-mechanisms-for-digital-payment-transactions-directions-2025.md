---
subject: "Authentication Mechanisms for Digital Payment Transactions Directions, 2025"
type: subject
role: regulatory
domains: [fintech]
categories: [upi, cards]
domain_url: rbi.org.in
logo: null
issuer: null
keywords: [2FA, AFA, UPI, two-factor authentication, RBI, digital payments, OTP, risk-based authentication, card security, fraud prevention, biometric, device-binding, passkeys, cross-border, CNP, wallets, NPCI, operational-limits]
signal: watch
headline: "'RBI mandates two-factor authentication across all digital payments from April 2026'"
vitals: ["1 Apr 2026|Effective date|Full UPI + card compliance required", "1 Oct 2026|Card-not-present deadline|Cross-border non-recurring transactions", "2|Auth factors required|At least one must be dynamic"]
last_updated: 2026-06-25
---

## What we know

**OTP alone no longer sufficient** — SMS-based OTP as sole factor is prohibited; SIM-swap, phishing, and malware exploits drove the mandate effective 1 April 2026[^rbi-2fa-apr2026]
**Dynamic factor required** — At least one authentication factor must be uniquely generated per transaction — biometric, device-bound passkey, app token, or hardware token all qualify[^rbi-2fa-apr2026]
**Risk-based calibration** — Low-risk routine transactions on trusted devices authenticate silently; new devices, unusual geographies, or high-value amounts trigger stepped-up verification[^rbi-2fa-apr2026]
**Wallets/PPIs in scope** — Prepaid Payment Instruments and mobile wallets must also implement 2FA with one dynamic factor; risk-based anomaly flagging required[^rbi-2fa-apr2026]
**Cross-border CNP by Oct 2026** — Non-recurring cross-border card-not-present transactions have a separate compliance deadline of 1 October 2026[^rbi-2fa-apr2026]
**Issuer liability shift confirmed** — Banks and card issuers are directly liable for fraud losses if authentication standards are unmet; burden does not fall on the consumer[^rbi-2fa-apr2026]
**NPCI UPI operational limits** — Balance checks capped at 50/day per app; linked-account lookups at 25/day; pending transaction polls limited to 3 attempts with 90-second gaps; recurring payments restricted to off-peak windows[^rbi-2fa-apr2026]
**30% UPI market-share cap extended** — NPCI extended the single-app 30% cap compliance deadline to 31 December 2026[^rbi-2fa-apr2026]

## Regulatory Intel

**Status:** In force — effective 1 April 2026 for UPI and domestic cards; cross-border card-not-present compliance extended to 1 October 2026[^afa-2026-06-24]

**What it requires:** Every digital payment (UPI, credit/debit cards, mobile wallets/PPIs) must use at least two independent authentication factors drawn from knowledge, possession or inherence — with at least one dynamic factor per transaction. OTP alone is no longer sufficient. Institutions must implement risk-based authentication and may be held directly liable for compensating fraud victims if required standards are unmet[^afa-2026-06-24]

**Posture:** Compliance is mandatory — no opt-out. Payment providers must upgrade infrastructure; recurring e-mandate debits are exempt[^afa-2026-06-24]

**Implication:** For Scapia, as a co-branded credit card, card-issuer Federal Bank and network partners must ensure domestic transactions already meet the 2FA standard. Scapia's app-based UPI PIN + device binding model is broadly aligned [Inferred · Medium]. The liability-shift provision is positive for cardholders — any fraud attributable to inadequate bank/network authentication falls on the institution, reducing consumer dispute burden. The October 2026 cross-border deadline is the near-term watch point for Scapia's internationally-positioned travel card proposition[^afa-2026-06-24]

## Coverage

### RBI 2FA Rules Detailed, UPI Limits — 2026-06-25

India's RBI Authentication Directions, 2025 took full effect 1 April 2026, retiring SMS-OTP as a standalone factor across UPI, cards, and wallets[^rbi-2fa-apr2026]. This source provides the most granular public account of what replaces it: biometrics, device-bound passkeys, app tokens, and hardware tokens all qualify as the mandatory dynamic factor, while risk-based authentication ensures low-friction journeys for routine payments on recognised devices[^rbi-2fa-apr2026]. Cross-border card-not-present transactions get until 1 October 2026 — the near-term watch point for Scapia's internationally-used travel card.

NPCI's companion operational changes — 50 balance-check, 25 account-link, and 3 transaction-poll caps per day, plus off-peak scheduling for recurring mandates — are system-stability measures rather than user-facing friction, but they confirm both regulators are hardening the rails simultaneously[^rbi-2fa-apr2026]. For Scapia, the October CNP deadline and the institutional liability-shift provision are the live compliance items: Federal Bank must register card programs with the card networks for cross-border 2FA by that date, and any fraud attributable to authentication gaps will sit with the issuer, not the cardholder [Inferred · Medium][^rbi-2fa-apr2026].

### RBI Mandates 2FA All Digital Payments — 2026-06-24

India's RBI has made two-factor authentication compulsory for every digital payment — UPI, cards and wallets — effective 1 April 2026 under the Authentication Mechanisms for Digital Payment Transactions Directions, 2025[^afa-2026-06-24]. The rules retire the OTP-only model that enabled SIM-swap and phishing fraud, requiring at least two verification factors (one dynamic) per transaction, with risk-based systems handling low-friction authentication for routine payments[^afa-2026-06-24].

The more consequential shift is on liability: institutions that fail to implement required authentication standards now bear direct financial responsibility for resulting fraud — not the consumer[^afa-2026-06-24]. For Scapia, whose Federal Bank issuer must comply on domestic cards immediately and on cross-border card-not-present transactions by 1 October 2026, the framework raises the compliance bar but also strengthens the customer-protection story for a travel card used heavily abroad [Inferred · Medium][^afa-2026-06-24].

## Developments

- 2026-06-25 — RBI 2FA Rules Detailed, UPI Limits [^rbi-2fa-apr2026]
- 2026-06-24 — RBI Mandates 2FA All Digital Payments [^afa-2026-06-24]

## Sources

[^afa-2026-06-24]: raw/regulatory/rbi-new-upi-rules-2026-2fa-afa-impact-benefits-explained.md
[^rbi-2fa-apr2026]: raw/regulatory/rbi-s-new-digital-payment-rules-from-april-1-what-changes-for-upi-cards-and-e-wa.md
