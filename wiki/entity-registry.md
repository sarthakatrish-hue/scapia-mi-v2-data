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

- federal-bank | partner | Federal Bank | aliases: federal | Co-brand issuer since Jun 2023; ALSO issues for other fintechs — competitive moves by Federal go on the partner page under Current Risks, never as a competitor page
- bobcard | partner | BOBCARD | aliases: bob card, bank of baroda cards | Second co-brand issuer (Bank of Baroda subsidiary)
- visa | partner | Visa | | Card network for the Visa variant
- rupay | partner | RuPay | | Card network for the UPI variant (NPCI product — NPCI itself is a regulator)

## Regulators

- rbi | regulator | Reserve Bank of India | aliases: reserve bank
- npci | regulator | NPCI | aliases: national payments corporation of india
- dgca | regulator | DGCA | aliases: directorate general of civil aviation
- sebi | regulator | SEBI |
- meity | regulator | MeitY | aliases: ministry of electronics and information technology | DPDP Act owner
- irdai | regulator | IRDAI |


## Competitors

- atlys | competitor | Atlys | domain: atlys.com | added_by: agent 2026-06-22 · source: visa-processing-startup-atlys-raises-36-mn-in-series-c-funding.md · Digital visa discovery, application, and management platform serving 120+ destinations; operates in UAE, US, UK, Australia; processing 700K+ visa applications annually with AI-driven document verification and eligibility checks.

- phonepe | competitor | PhonePe | domain: phonepe.com | added_by: agent 2026-06-22 · source: phonepe-enables-credit-line-on-upi-on-its-platform.md · Fintech payments platform offering UPI, wallet, and credit-on-UPI products; material benchmark in India's credit-on-UPI ecosystem.

- tbo-tek | competitor | TBO Tek | domain: tbo.com | added_by: agent 2026-06-22 · source: the-ai-divide-in-indian-travel-what-makemytrip-ixigo-tbo-and-yatra-s-earnings-ca.md · India travel vertical SaaS and OTA operator focused on B2B distribution and internal productivity.
- onecard-issuer | competitor | Onecard Issuer | added_by: foundation 2026-06-22
- yes-bank | competitor | Yes Bank | added_by: foundation 2026-06-22
- sbm-bank | competitor | Sbm Bank | added_by: foundation 2026-06-22
- au-bank | competitor | Au Bank | added_by: foundation 2026-06-22
- idfc-first-bank | competitor | Idfc First Bank | added_by: foundation 2026-06-22
- rbl-bank | competitor | Rbl Bank | added_by: foundation 2026-06-22
- sbi-card | competitor | Sbi Card | added_by: foundation 2026-06-22
- icici-bank | competitor | Icici Bank | added_by: foundation 2026-06-22
- axis-bank | competitor | Axis Bank | added_by: foundation 2026-06-22
- bobcard-etihad-base | competitor | Bobcard Etihad Base | added_by: foundation 2026-06-22
- axis-burgundy-private | competitor | Axis Burgundy Private | added_by: foundation 2026-06-22
- uni-nxtwave | competitor | Uni Nxtwave | added_by: foundation 2026-06-22
- onecard | competitor | Onecard | added_by: foundation 2026-06-22
- niyo-global-sbm | competitor | Niyo Global Sbm | added_by: foundation 2026-06-22
- idfc-first-wow | competitor | Idfc First Wow | added_by: foundation 2026-06-22
- bobcard-etihad-premium | competitor | Bobcard Etihad Premium | added_by: foundation 2026-06-22
- ixigo-au | competitor | Ixigo Au | domain: aubank.in | added_by: foundation 2026-06-22
- rbl-world-safari | competitor | Rbl World Safari | added_by: foundation 2026-06-22
- idfc-first-mayura | competitor | Idfc First Mayura | added_by: foundation 2026-06-22
- sbi-elite | competitor | Sbi Elite | added_by: foundation 2026-06-22
- axis-atlas | competitor | Axis Atlas | domain: axisbank.com | added_by: foundation 2026-06-22
- icici-emeralde | competitor | Icici Emeralde | added_by: foundation 2026-06-22
- hdfc-diners-black | competitor | Hdfc Diners Black | added_by: foundation 2026-06-22
- hdfc-infinia | competitor | Hdfc Infinia | added_by: foundation 2026-06-22

- hdfc-bank | competitor | HDFC Bank | added_by: agent 2026-06-22 · source: 2026-06-22-hdfc-regalia-gold-revamp.md · Indian systemically important bank; issuer of co-branded and proprietary premium travel credit cards (Regalia Gold, Regalia Platinum, etc.); major benchmark in India's premium segment.

## Context (never gets a page)

## Partner candidates (pending curator confirmation)
