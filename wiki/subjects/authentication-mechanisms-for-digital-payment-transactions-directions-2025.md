---
subject: "Authentication Mechanisms for Digital Payment Transactions Directions, 2025"
type: subject
role: regulatory
domains: [fintech]
categories: [upi, cards]
domain_url: rbi.org.in
logo: null
issuer: null
keywords: [2FA, AFA, UPI, two-factor authentication, RBI, digital payments, OTP, risk-based authentication, card security, fraud prevention, biometric, device-binding, passkeys, cross-border, CNP, wallets, NPCI, operational-limits, april-2026, POS, dynamic-factor]
signal: watch
headline: "'RBI mandates two-factor authentication across all digital payments from April 2026'"
vitals: ["1 Apr 2026|Effective date|Full UPI + card compliance required", "1 Oct 2026|Card-not-present deadline|Cross-border non-recurring transactions", "2|Auth factors required|At least one must be dynamic"]
last_updated: 2026-06-26
---

## What we know

**Applies at POS too** — The 2FA mandate covers all credit card transactions whether online or at point-of-sale; OTP remains a valid dynamic factor for card transactions[^card-rules-apr2026]
**Low-risk transactions exempted** — RBI built in flexibility for small-value, low-risk transactions so not every card swipe triggers extra verification steps[^card-rules-apr2026]

## Regulatory Intel

**Status:** In force — effective 1 April 2026 for UPI and domestic cards; cross-border card-not-present compliance extended to 1 October 2026[^afa-2026-06-24]

**What it requires:** Every digital payment (UPI, credit/debit cards, mobile wallets/PPIs) must use at least two independent authentication factors drawn from knowledge, possession or inherence — with at least one dynamic factor per transaction. OTP alone is no longer sufficient. Institutions must implement risk-based authentication and may be held directly liable for compensating fraud victims if required standards are unmet[^afa-2026-06-24]

**Posture:** Compliance is mandatory — no opt-out. Payment providers must upgrade infrastructure; recurring e-mandate debits are exempt[^afa-2026-06-24]

**Implication:** For Scapia, as a co-branded credit card, card-issuer Federal Bank and network partners must ensure domestic transactions already meet the 2FA standard. Scapia's app-based UPI PIN + device binding model is broadly aligned [Inferred · Medium]. The liability-shift provision is positive for cardholders — any fraud attributable to inadequate bank/network authentication falls on the institution, reducing consumer dispute burden. The October 2026 cross-border deadline is the near-term watch point for Scapia's internationally-positioned travel card proposition[^afa-2026-06-24]

## Coverage

### 2FA Rule In Force April 2026 — 2026-04-01

India's RBI Authentication Directions, 2025 came into force on 1 April 2026, requiring all credit card transactions — online and at POS — to use at least two independent authentication factors, with at least one dynamic per transaction[^card-rules-apr2026]. OTP continues to qualify as a valid dynamic factor; low-risk, small-value transactions carry built-in exemptions to preserve checkout fluency[^card-rules-apr2026].

The practical impact for most compliant cardholders is minimal friction on routine payments, with stepped-up verification reserved for high-value or unfamiliar transactions[^card-rules-apr2026]. For Scapia's Federal Bank issuer, domestic card compliance is already required; the cross-border card-not-present deadline of 1 October 2026 remains the live watch point for Scapia's internationally-used travel card proposition. [Inferred · Medium]

### RBI 2FA Rules Detailed, UPI Limits — 2026-06-25

India's RBI Authentication Directions, 2025 took full effect 1 April 2026, retiring SMS-OTP as a standalone factor across UPI, cards, and wallets[^rbi-2fa-apr2026]. This source provides the most granular public account of what replaces it: biometrics, device-bound passkeys, app tokens, and hardware tokens all qualify as the mandatory dynamic factor, while risk-based authentication ensures low-friction journeys for routine payments on recognised devices[^rbi-2fa-apr2026]. Cross-border card-not-present transactions get until 1 October 2026 — the near-term watch point for Scapia's internationally-used travel card.

NPCI's companion operational changes — 50 balance-check, 25 account-link, and 3 transaction-poll caps per day, plus off-peak scheduling for recurring mandates — are system-stability measures rather than user-facing friction, but they confirm both regulators are hardening the rails simultaneously[^rbi-2fa-apr2026]. For Scapia, the October CNP deadline and the institutional liability-shift provision are the live compliance items: Federal Bank must register card programs with the card networks for cross-border 2FA by that date, and any fraud attributable to authentication gaps will sit with the issuer, not the cardholder [Inferred · Medium][^rbi-2fa-apr2026].

### RBI Mandates 2FA All Digital Payments — 2026-06-24

India's RBI has made two-factor authentication compulsory for every digital payment — UPI, cards and wallets — effective 1 April 2026 under the Authentication Mechanisms for Digital Payment Transactions Directions, 2025[^afa-2026-06-24]. The rules retire the OTP-only model that enabled SIM-swap and phishing fraud, requiring at least two verification factors (one dynamic) per transaction, with risk-based systems handling low-friction authentication for routine payments[^afa-2026-06-24].

The more consequential shift is on liability: institutions that fail to implement required authentication standards now bear direct financial responsibility for resulting fraud — not the consumer[^afa-2026-06-24]. For Scapia, whose Federal Bank issuer must comply on domestic cards immediately and on cross-border card-not-present transactions by 1 October 2026, the framework raises the compliance bar but also strengthens the customer-protection story for a travel card used heavily abroad [Inferred · Medium][^afa-2026-06-24].

## Developments

- 2026-04-01 — 2FA Rule In Force April 2026 [^card-rules-apr2026]
- 2026-06-25 — RBI 2FA Rules Detailed, UPI Limits [^rbi-2fa-apr2026]
- 2026-06-24 — RBI Mandates 2FA All Digital Payments [^afa-2026-06-24]

## Sources

[^afa-2026-06-24]: raw/regulatory/rbi-new-upi-rules-2026-2fa-afa-impact-benefits-explained.md
[^rbi-2fa-apr2026]: raw/regulatory/rbi-s-new-digital-payment-rules-from-april-1-what-changes-for-upi-cards-and-e-wa.md
[^card-rules-apr2026]: raw/ambiguous/9-major-credit-card-rule-changes-in-india-2026.md
