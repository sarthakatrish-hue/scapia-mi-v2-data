---
title: Entity Registry
type: entity-registry
maintained_by: human+agent
last_updated: 2026-06-11
---

# Entity Registry

Single source of truth for WHO every entity is relative to Scapia. The
filter, checker, and ingest writer all read this — classification is
deterministic for listed entities; the LLM's rubric only applies to NEW
ones, which get appended here with provenance.

Line format (parsed line-by-line, pipes required):
`- slug | class | Display Name | aliases: a, b | note`

Classes: `self` (Scapia itself — NEVER gets a wiki page of any kind; own-news
routes to the curator with a pointer to the scapia.md baseline) ·
`partner` (Scapia commercial relationship — pages in partners/) ·
`regulator` (rule-setting body — pages in regulatory/ are per-regulation,
not per-body) · `competitor` (competes for the same customer spend or
travel bookings — pages in entities/) · `context` (investors, vendors,
people, foreign players — NEVER gets its own page) ·
`partner-candidate` (agent-proposed partner awaiting curator confirmation —
treated as context until promoted).

## Self

- scapia | self | Scapia | aliases: scapia federal, scapia credit card, scapia card, scapia technologies, scapia app | The company itself — the wiki tracks the MARKET; Scapia facts live in the human-maintained scapia.md baseline

## Partners

- federal-bank | partner | Federal Bank | aliases: federal | domain: federalbank.co.in | Co-brand issuer since Jun 2023; ALSO issues for other fintechs — competitive moves by Federal go on the partner page under Current Risks, never as a competitor page
- bobcard | partner | BOBCARD | aliases: bob card, bank of baroda cards | domain: bobcard.co.in | Second co-brand issuer (Bank of Baroda subsidiary)
- visa | partner | Visa | | Card network for the Visa variant
- rupay | partner | RuPay | | Card network for the UPI variant (NPCI product — NPCI itself is a regulator)

## Regulators

- project-nexus | regulator | Project Nexus | newly-surfaced · added_by: agent 2026-06-24 · source: upi-payments-in-2026-new-features-transaction-limits-future-of-digital-india.md · multilateral cross-border payment initiative to interlink fast payment systems, expected live by 2026

- aadhaar-face-authentication | regulator | Aadhaar Face Authentication | newly-surfaced · added_by: agent 2026-06-24 · source: upi-payments-in-2026-new-features-transaction-limits-future-of-digital-india.md · biometric authentication mechanism for UPI transactions piloted in 2026

- upi-lite | regulator | UPI Lite | newly-surfaced · added_by: agent 2026-06-24 · source: upi-payments-in-2026-new-features-transaction-limits-future-of-digital-india.md · offline-UPI payment product with ₹5,000 limit for low-connectivity areas

- epfo | regulator | Employees' Provident Fund Organisation | newly-surfaced · added_by: agent 2026-06-24 · source: major-banking-tax-upi-transaction-rule-changes-kicking-in-from-june-2026-key-poi.md · government social security body introducing UPI-linked withdrawal infrastructure

- authentication-mechanisms-for-digital-payment-transactions-directions-2025 | regulator | RBI Authentication Mechanisms Directions 2025 | domain: rbi.org.in | newly-surfaced · added_by: agent 2026-06-24 · source: rbi-new-upi-rules-2026-2fa-afa-impact-benefits-explained.md · mandate requiring 2FA/AFA for UPI, cards and wallets effective 1 April 2026

- rbi | regulator | Reserve Bank of India | aliases: reserve bank | domain: rbi.org.in
- npci | regulator | NPCI | aliases: national payments corporation of india | domain: npci.org.in
- dgca | regulator | DGCA | aliases: directorate general of civil aviation
- sebi | regulator | SEBI |
- meity | regulator | MeitY | aliases: ministry of electronics and information technology | DPDP Act owner
- irdai | regulator | IRDAI |


## Competitors

- suryoday-sfb | competitor | Suryoday Small Finance Bank | domain: suryodaybank.com | newly-surfaced · added_by: agent 2026-06-27 · source: prime-borrowers-emerge-as-key-users-of-credit-line-on-upi-suryoday-sfb.md · operates Credit Line on UPI (CLOU) product in partnership with Paytm, competing in embedded credit-on-UPI space

- hsbc-rewards-marketplace | competitor | HSBC Rewards Marketplace | domain: hsbc.co.in | added_by: agent 2026-06-26 · source: hsbc-launches-rewards-marketplace-how-it-fares-against-hdfc-smartbuy-icici-ishop.md · travel rewards portal for select HSBC cardholders offering accelerated points on flights, hotels, car rentals with partner airline/hotel redemption

- hopper | competitor | Hopper | domain: hopper.com | added_by: agent 2026-06-26 · source: hsbc-launches-rewards-marketplace-how-it-fares-against-hdfc-smartbuy-icici-ishop.md · travel platform and flight search engine providing booking infrastructure to HSBC Rewards Marketplace

- club-vistara | competitor | Club Vistara | newly-surfaced · added_by: agent 2026-06-26 · source: watch-out-major-changes-for-credit-cards-from-april-1-2025.md · airline loyalty program and co-branded credit card partner, merged with Air India April 2025

- makemytrip-icici-bank | competitor | MakeMyTrip ICICI Bank Credit Card | domain: icicibank.com | newly-surfaced · added_by: agent 2026-06-26 · source: best-travel-credit-cards-in-india-2026-charges-rewards.md · Co-branded ICICI travel card with 0.99% forex markup and Priority Pass membership

- niyo-sbm | competitor | Niyo SBM Credit Card | domain: niyo.co | newly-surfaced · added_by: agent 2026-06-26 · source: best-travel-credit-cards-in-india-2026-charges-rewards.md · Co-branded credit card offering 0% forex markup and lounge access in India market

- stan-chart-ultimate | competitor | Standard Chartered Ultimate | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · super-premium rewards card

- hdfc-marriott-bonvoy | competitor | HDFC Marriott Bonvoy | domain: hdfcbank.com | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · hotel loyalty co-brand card

- equitas-powermiles | competitor | Equitas Powermiles | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · international travel rewards card

- hsbc-travel-one | competitor | HSBC Travel One | domain: hsbc.co.in | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · travel rewards card with Accor transfers

- hdfc-tata-neu-infinity | competitor | HDFC Tata Neu Infinity | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · UPI credit card

- equitas-selfe | competitor | Equitas Selfe | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · entry-level cashback card with category multipliers

- axis-cashback-card | competitor | Axis Cashback Card | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · online spend cashback product

- hsbc-live-plus | competitor | HSBC Live+ | newly-surfaced · added_by: agent 2026-06-26 · source: 20-best-credit-cards-in-india-for-2026-for-beginners-to-high-spenders.md · dining and grocery cashback card

- idfc-first-millennia | competitor | IDFC FIRST Millennia | newly-surfaced · added_by: agent 2026-06-26 · source: best-rewards-credit-cards-india-2026-real-return-per-rupee-after-devaluations.md · lifetime-free cashback and rewards card

- bob-eterna | competitor | Bank of Baroda Eterna | newly-surfaced · added_by: agent 2026-06-26 · source: best-rewards-credit-cards-india-2026-real-return-per-rupee-after-devaluations.md · lifetime-free rewards credit card competing on domestic travel and dining

- amex-platinum-travel | competitor | American Express Platinum Travel Card | domain: americanexpress.com | newly-surfaced · added_by: agent 2026-06-26 · source: best-rewards-credit-cards-india-2026-real-return-per-rupee-after-devaluations.md · premium travel rewards card in India

- hdfc-pixel-play-credit-card | competitor | HDFC Pixel Play Credit Card | newly-surfaced · added_by: agent 2026-06-26 · source: axis-bank-credit-card-devaluation-in-2026-what-happened.md · zero-fee customizable category cashback card for young spenders

- axis-ace-credit-card | competitor | Axis ACE Credit Card | newly-surfaced · added_by: agent 2026-06-26 · source: axis-bank-credit-card-devaluation-in-2026-what-happened.md · everyday utility and food delivery cashback card with lounge access

- induslnd-bank | competitor | IndusInd Bank | domain: indusind.com | newly-surfaced · added_by: agent 2026-06-26 · source: credit-card-updates-changes-2026.md · operates IndusInd Tiger and other credit cards competing in the Indian card market

- hdfc-bizpower | competitor | HDFC BizPower | domain: hdfcbank.com | newly-surfaced · added_by: agent 2026-06-26 · source: hdfc-credit-card-devaluation-2026-what-changed.md · business credit card devalued May 2026

- hdfc-diners-club-privilege | competitor | HDFC Diners Club Privilege | domain: hdfcbank.com | newly-surfaced · added_by: agent 2026-06-26 · source: hdfc-credit-card-devaluation-2026-what-changed.md · mid-premium credit card devalued May 2026

- hdfc-regalia-gold | competitor | HDFC Regalia Gold | domain: hdfcbank.com | newly-surfaced · added_by: agent 2026-06-26 · source: hdfc-credit-card-devaluation-2026-what-changed.md · mid-premium credit card devalued May 2026

- air-india-express | competitor | Air India Express | newly-surfaced · added_by: agent 2026-06-25 · source: air-india-announces-key-enhancements-to-maharaja-club.md · Low-cost carrier within Air India Group, operates 50+ domestic and Gulf routes, integrating into Maharaja Club redemption network.

- air-india-maharaja-club-credit-card | competitor | Air India Maharaja Club Co-Branded Credit Card | domain: airindia.com | newly-surfaced · added_by: agent 2026-06-25 · source: coming-soon-air-india-maharaja-club-co-branded-credit-cards.md · planned 2026 relaunch of Air India co-branded cards tied to loyalty program refresh and points accrual on Air India Express flights

- flipkart-travel | competitor | Flipkart Travel | newly-surfaced · added_by: agent 2026-06-25 · source: bobcard-rolls-out-travel-deals-with-air-india-travel-websites-details.md · e-commerce player offering travel booking and deals

- yatra | competitor | Yatra | newly-surfaced · added_by: agent 2026-06-25 · source: bobcard-rolls-out-travel-deals-with-air-india-travel-websites-details.md · online travel agency for flights, hotels, and experiences

- goibibo | competitor | Goibibo | newly-surfaced · added_by: agent 2026-06-25 · source: bobcard-rolls-out-travel-deals-with-air-india-travel-websites-details.md · travel booking platform for flights, stays, and buses

- easemytrip | competitor | EaseMyTrip | newly-surfaced · added_by: agent 2026-06-25 · source: bobcard-rolls-out-travel-deals-with-air-india-travel-websites-details.md · domestic and international flight/hotel OTA

- makemytrip | competitor | MakeMyTrip | newly-surfaced · added_by: agent 2026-06-25 · source: bobcard-rolls-out-travel-deals-with-air-india-travel-websites-details.md · OTA and travel platform competing in flights, stays, and experiences

- sbi-card-miles-elite | competitor | SBI Card Miles Elite | newly-surfaced · added_by: agent 2026-06-25 · source: credit-cards-on-a-devaluation-spree-how-to-still-maximise-benefits.md · airline-linked premium variant; discontinued as part of SBI portfolio rationalization

- sbi-card-elite | competitor | SBI Card Elite | newly-surfaced · added_by: agent 2026-06-25 · source: credit-cards-on-a-devaluation-spree-how-to-still-maximise-benefits.md · premium card with withdrawn air accident insurance; premium travel card benchmark

- axis-etihad | competitor | Axis Etihad | newly-surfaced · added_by: agent 2026-06-25 · source: credit-cards-on-a-devaluation-spree-how-to-still-maximise-benefits.md · co-branded airline card; mentioned as discontinued variant but signals ecosystem co-brand strategy

- american-express | competitor | American Express India | domain: americanexpress.com | newly-surfaced · added_by: agent 2026-06-25 · source: credit-cards-on-a-devaluation-spree-how-to-still-maximise-benefits.md · operates co-branded and premium cards competing for high-value travel spenders

- bank-of-baroda | competitor | Bank of Baroda | domain: bankofbaroda.in | newly-surfaced · added_by: agent 2026-06-24 · source: major-banking-tax-upi-transaction-rule-changes-kicking-in-from-june-2026-key-poi.md · operates credit card products and reward programs competing in Indian market

- fi-money | competitor | Fi Money | domain: fi.money | added_by: agent 2026-06-22 · source: cash-strapped-fi-money-pivots-to-ai-led-b2b-play.md · Indian neobank founded 2019, pivoting from consumer lending to B2B/AI after funding burnout and ₹300 Cr FY23 losses

- revolut | competitor | Revolut | domain: revolut.com | added_by: agent 2026-06-22 · source: revolut-rolls-out-services-to-thousands-of-users-in-india-ahead-of-broader-launc.md · British fintech offering multi-currency cards, digital wallets, and UPI services in beta launch across India and other emerging markets.

- kiwi | competitor | Kiwi | domain: kiwi.co.in | added_by: agent 2026-06-22 · source: pnb-partners-kiwi-to-launch-rupay-credit-card-on-upi-platform.md · Fintech specialist in credit-on-UPI and QR-code-based credit transactions; launched co-branded PNB Kiwi Credit Card as first public-sector bank partnership.

- amazon-pay | competitor | Amazon Pay | domain: pay.amazon.in | added_by: agent 2026-06-22 · source: amazon-pay-launches-rewards-gold-get-5-cashback-every-time-you-spend.md · Cashback and UPI/payments fintech player in India, operating a wallet and buy-now-pay-later adjacent product; launched Rewards Gold cashback programme with up to 5% earn on travel, groceries, food delivery, and entertainment.

- pop | competitor | POP (Rewards UPI App) | domain: pop.in | added_by: agent 2026-06-22 · source: razorpay-acquires-majority-stake-in-pop-with-30-mn-investment.md · Consumer UPI payments and multi-brand rewards currency platform issuing RuPay credit cards via Yes Bank; acquired by Razorpay in majority stake deal.

- razorpay | competitor | Razorpay | domain: razorpay.com | added_by: agent 2026-06-22 · source: razorpay-acquires-majority-stake-in-pop-with-30-mn-investment.md · B2B/B2C fintech payments and commerce platform acquiring majority stake in consumer UPI and rewards app POP.

- google-pay | competitor | Google Pay | added_by: agent 2026-06-22 · source: flex-by-google-pay-reimagining-everyday-credit-for-india.md · UPI-powered digital credit platform and fintech ecosystem player in India

- super-money | competitor | Super.money (Flipkart Fintech) | domain: super.money | added_by: agent 2026-06-22 · source: flipkart-s-super-money-teams-up-with-kotak811-to-make-india-s-free-upi-payments-.md · Flipkart's fintech arm offering UPI, secured credit cards, and BNPL bundled into a single account; 10M active users, $36M ARR, targeting 2M secured cards in 12 months via bank partnerships.

- atlys | competitor | Atlys | domain: atlys.com | added_by: agent 2026-06-22 · source: visa-processing-startup-atlys-raises-36-mn-in-series-c-funding.md · Digital visa discovery, application, and management platform serving 120+ destinations; operates in UAE, US, UK, Australia; processing 700K+ visa applications annually with AI-driven document verification and eligibility checks.

- phonepe | competitor | PhonePe | domain: phonepe.com | added_by: agent 2026-06-22 · source: phonepe-enables-credit-line-on-upi-on-its-platform.md · Fintech payments platform offering UPI, wallet, and credit-on-UPI products; material benchmark in India's credit-on-UPI ecosystem.

- tbo-tek | competitor | TBO Tek | domain: tbo.com | added_by: agent 2026-06-22 · source: the-ai-divide-in-indian-travel-what-makemytrip-ixigo-tbo-and-yatra-s-earnings-ca.md · India travel vertical SaaS and OTA operator focused on B2B distribution and internal productivity.
- onecard-issuer | competitor | Onecard Issuer | added_by: foundation 2026-06-22
- yes-bank | competitor | Yes Bank | domain: yesbank.in | added_by: foundation 2026-06-22
- sbm-bank | competitor | Sbm Bank | domain: sbmbank.co.in | added_by: foundation 2026-06-22
- au-bank | competitor | Au Bank | added_by: foundation 2026-06-22
- idfc-first-bank | competitor | Idfc First Bank | domain: idfcfirstbank.com | added_by: foundation 2026-06-22
- rbl-bank | competitor | Rbl Bank | added_by: foundation 2026-06-22
- sbi-card | competitor | Sbi Card | domain: sbicard.com | added_by: foundation 2026-06-22
- icici-bank | competitor | Icici Bank | domain: icicibank.com | added_by: foundation 2026-06-22
- axis-bank | competitor | Axis Bank | domain: axisbank.com | added_by: foundation 2026-06-22
- bobcard-etihad-base | competitor | Bobcard Etihad Base | added_by: foundation 2026-06-22
- axis-burgundy-private | competitor | Axis Burgundy Private | domain: axisbank.com | added_by: foundation 2026-06-22
- uni-nxtwave | competitor | Uni Nxtwave | added_by: foundation 2026-06-22
- onecard | competitor | Onecard | domain: getonecard.app | added_by: foundation 2026-06-22
- niyo-global-sbm | competitor | Niyo Global Sbm | domain: sbmbank.co.in | added_by: foundation 2026-06-22
- idfc-first-wow | competitor | Idfc First Wow | added_by: foundation 2026-06-22
- bobcard-etihad-premium | competitor | Bobcard Etihad Premium | added_by: foundation 2026-06-22
- ixigo-au | competitor | Ixigo Au | domain: aubank.in | added_by: foundation 2026-06-22
- rbl-world-safari | competitor | Rbl World Safari | added_by: foundation 2026-06-22
- idfc-first-mayura | competitor | Idfc First Mayura | added_by: foundation 2026-06-22
- sbi-elite | competitor | Sbi Elite | added_by: foundation 2026-06-22
- axis-atlas | competitor | Axis Atlas | domain: axisbank.com | added_by: foundation 2026-06-22
- icici-emeralde | competitor | Icici Emeralde | domain: icicibank.com | added_by: foundation 2026-06-22
- hdfc-diners-black | competitor | Hdfc Diners Black | domain: hdfcbank.com | added_by: foundation 2026-06-22
- hdfc-infinia | competitor | Hdfc Infinia | domain: hdfcbank.com | added_by: foundation 2026-06-22

- hdfc-bank | competitor | HDFC Bank | domain: hdfcbank.com | added_by: agent 2026-06-22 · source: 2026-06-22-hdfc-regalia-gold-revamp.md · Indian systemically important bank; issuer of co-branded and proprietary premium travel credit cards (Regalia Gold, Regalia Platinum, etc.); major benchmark in India's premium segment.

## Context (never gets a page)

- bankbazaar | context | BankBazaar | newly-surfaced · added_by: agent 2026-06-25 · source: credit-cards-on-a-devaluation-spree-how-to-still-maximise-benefits.md · fintech comparison platform; source of aggregated issuer intelligence

- pine-labs | context | Pine Labs | newly-surfaced · added_by: agent 2026-06-24 · source: rbi-new-upi-rules-2026-2fa-afa-impact-benefits-explained.md · payments infrastructure provider and systems integrator

## Partner candidates (pending curator confirmation)

- paytm | partner-candidate | Paytm | newly-surfaced · added_by: agent 2026-06-27 · source: prime-borrowers-emerge-as-key-users-of-credit-line-on-upi-suryoday-sfb.md · distribution/technology partner for Suryoday SFB's CLOU product

- air-india | partner-candidate | Air India | newly-surfaced · added_by: agent 2026-06-25 · source: bobcard-rolls-out-travel-deals-with-air-india-travel-websites-details.md · airline offering co-branded travel bookings and discounts

- vodafone-idea | partner-candidate | Vodafone Idea Limited | added_by: agent 2026-06-22 · source: vodafone-idea-partners-with-niyo-to-offer-zero-markup-forex-card-for-internation.md · Indian telecom operator partnering with travel fintech on forex card distribution.

- pnb | partner-candidate | Punjab National Bank | added_by: agent 2026-06-22 · source: pnb-partners-kiwi-to-launch-rupay-credit-card-on-upi-platform.md · Indian public-sector bank, 180M customer base, 10k+ branch network; entered credit-on-UPI space via Kiwi partnership on RuPay.

- smfg-india-credit | partner-candidate | SMFG India Credit | added_by: agent 2026-06-22 · source: flex-by-google-pay-reimagining-everyday-credit-for-india.md · Credit origination partner to Google Pay Flex ecosystem

- payu-finance | partner-candidate | PayU Finance | added_by: agent 2026-06-22 · source: flex-by-google-pay-reimagining-everyday-credit-for-india.md · Credit origination partner to Google Pay Flex ecosystem

- l-t-finance | partner-candidate | L&T Finance | added_by: agent 2026-06-22 · source: flex-by-google-pay-reimagining-everyday-credit-for-india.md · Credit origination partner to Google Pay Flex ecosystem

- juspay | partner-candidate | Juspay | added_by: agent 2026-06-22 · source: flipkart-s-super-money-teams-up-with-kotak811-to-make-india-s-free-upi-payments-.md · SoftBank-backed payment orchestration and checkout platform partnering with Super.money for D2C one-click checkout; relevant to Scapia's card-linked commerce positioning.
