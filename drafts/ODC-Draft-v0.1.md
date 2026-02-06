# Open Discovery Commons (ODC)

## Draft v0.1 — Public Working Document

**Status:** Early draft · Open for discussion and critique
**Role:** Initiator and initial editor
**License:** CC BY-SA 4.0


## 1. Purpose

The Open Discovery Commons (ODC) is a proposal for a **neutral, open, and AI-readable discovery layer** for local businesses and services.

Its goal is to enable AI assistants to recommend businesses based on **facts, trust, and relevance**, rather than ads, SEO manipulation, or platform-owned ranking systems.

ODC is designed as a **public digital commons**, not a commercial platform.


## 2. Problem Statement

Discovery on the internet has shifted:

* Humans increasingly ask AI assistants instead of browsing websites.
* AI systems must infer business information from fragmented, inconsistent, and often biased sources.
* Current discovery mechanisms are dominated by advertising-driven incentives and opaque ranking algorithms.

This results in:

* Unfair visibility for small or local businesses
* Incentives to manipulate rankings rather than improve service
* Reduced trust in AI-generated recommendations

There is currently **no neutral, AI-native standard** for representing local business information as verifiable, machine-readable facts.


## 3. Core Principles

ODC is guided by the following non-negotiable principles:

1. **Neutrality**
   No paid ranking, ads, or preferential treatment.

2. **Openness**
   Specifications, data formats, and reference implementations are open and publicly documented.

3. **AI-first design**
   Profiles are optimized for machine understanding, not marketing or human persuasion.

4. **Decentralization of control**
   No single company owns discovery; multiple implementations are encouraged.

5. **Verification over optimization**
   Trust is derived from verification, consistency, and history – not popularity or spend.

6. **Local fairness**
   Small and local businesses should be discoverable on equal terms with large brands.


## 4. What ODC Is (and Is Not)

### ODC IS:

* A shared data standard for AI-readable business profiles
* A public registry concept (with multiple possible hosts)
* A trust-oriented discovery layer

### ODC IS NOT:

* A search engine
* A website directory
* An advertising platform
* A replacement for business websites
* A for-profit marketplace


## 5. The Business Profile Concept

At the center of ODC is a **Business Discovery Profile (BDP)** — a structured, factual representation of a business or service.

### Example (illustrative, not final):

```
Business ID: odc:munich:fitness-retail:00123

Category:
  primary: sport_equipment
  secondary: gym, fitness

Location:
  city: Munich
  service_radius_km: 20

Availability:
  in_store: true
  online_order: true

Pricing Level:
  relative: medium

Policies:
  returns: 30_days
  warranty: standard

Trust Signals:
  identity_verified: true
  review_score: 4.6
  review_count: 1284

Last Verified:
  2026-01-15
```

Profiles are **descriptive, not promotional**.


## 6. Discovery Flow (Conceptual)

1. A business submits or updates its profile through an ODC-compatible implementation.
2. Profile data is verified and timestamped.
3. Profiles are published via open, machine-readable feeds.
4. AI systems query these feeds when answering discovery-related questions.
5. Recommendations are based on relevance, constraints, and trust — not payment.

Websites may exist, but are **not required for discovery**.


## 7. Governance (Initial Proposal)

ODC governance should be:

* Transparent
* Non-commercial
* Multi-stakeholder

Proposed early structure:

* A non-profit foundation or association
* Public documentation and decision logs
* Clear separation between specification and implementations

No entity should have the ability to:

* sell visibility
* control ranking outcomes
* unilaterally change the standard


## 8. Funding Philosophy

The ODC core standard should remain **free and non-commercial**.

Sustainable support may include:

* Public grants
* Research funding
* Donations
* Optional, non-required certification or hosting services by third parties

Access to discovery **must never depend on payment**.


## 9. Initial Scope

ODC intentionally starts small:

* Local businesses and services
* City-by-city adoption
* Human-scale verification

Expansion should be driven by:

* demonstrated usefulness
* community consensus
* real AI discovery needs


## 10. Open Questions (for contributors)

* How should verification be performed fairly at scale?
* What trust signals are meaningful and resistant to gaming?
* How should disputes or incorrect data be handled?
* How can regional differences be respected?

These questions are open by design.


## 11. Call for Participation

ODC is an open initiative.

Contributions are welcome from:

* AI researchers
* Civic technologists
* Local business associations
* Policy and governance experts
* Developers interested in open digital infrastructure

This document is a starting point – not a finished answer.


**End of Draft v0.1**
