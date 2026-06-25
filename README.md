# Open-Source Petition: Restore Manual Model Selection and Reclaim Student Autonomy


This repository serves as a decentralized, immutable ledger for developers, students, and open-source maintainers to formally protest the systematic degradation of the GitHub Copilot ecosystem. 

Over a multi-stage rollout culminating in June 2026, Microsoft and GitHub have dismantled the flat-rate pricing structure, stripped essential model selection autonomy, and reduced the Student Developer Pack to a highly restricted, metered environment. This manifesto documents these structural changes and outlines the community demands required to restore platform trust.

## [SIGN THE PETITION](https://github.com/ilim-cell/copilot/issues/new?template=signature.yml)

---

## Comprehensive Timeline of Ecosystem Degradation

The transition of GitHub Copilot from an industry-standard development assistant to an opaque, usage-metered utility occurred across a calculated sequence of policy updates and technical restrictions.

### Phase 1: Late 2025 – Preliminary Infrastructure Throttling
* **Hidden Compute Metrics**: GitHub quietly introduced background telemetry to track total repository token ingestion. Users noticed unexpected latency spikes during large codebase indexing, marking the initial phase of server-side resource conservation.
* **The Premium Request Unit (PRU) Prototype**: Internal shifts began moving away from raw token indexing toward PRUs, establishing the framework necessary to phase out the unlimited, flat-rate subscription model.

### Phase 2: February 2026 – The Exclusion of Frontier Models
* **Anthropic Restrictions**: In early February, manual routing to third-party frontier models, specifically Claude 3.5 Sonnet and Claude 3 Opus, was abruptly restricted on lower-tier accounts. 
* **The February 4 Mandate**: GitHub formally capped monthly allocations for proprietary high-reasoning models on paid Pro plans and completely barred verified student accounts from accessing them. This forced the educational tier onto older, less capable legacy architectures.

### Phase 3: March to May 2026 – The Shift to Usage-Based Billing
* **The May 19 Policy Announcement**: At the mid-May product keynote, GitHub formalized the structural death of the flat-rate model by unveiling the Core, Pro, Pro+, and Max tiers, explicitly shifting the entire platform to usage-based billing effective June 1, 2026.
* **Introduction of the AI Credit System**: Flat monthly fees were replaced by rigid token pools. The baseline Student and Free tiers were assigned a strict cap of 200 AI Credits per month. Because 1 AI Credit equates to exactly $0.01 USD, the comprehensive monthly allowance for students was capped at an effective value of $2.00 USD.
* **The Agentic Token Loop Trap**: Complex developer tasks, such as automated multi-file restructurings and repository-wide implementations, began consuming tens of thousands of tokens per background cycle. Heavy users reported completely exhausting their monthly $100 Max tier credit allotments within the first 24 hours of usage.

### Phase 4: June 24, 2026 – The Elimination of Autonomy (Auto Mode Mandate)
* **Forced Auto-Selection**: GitHub deployed an official changelog update stating that Copilot Free and Student plans would exclusively utilize "Copilot auto model selection" as the default and only available experience. Manual model selection was permanently disabled.
* **Defaulting to Raptor Mini**: Under the hood, the black-box auto-routing algorithm calculates account credit limits. Because students operate on a micro-allotment of 200 credits, the router aggressively defaults almost all incoming prompts to Raptor Mini—a lightweight, lower-tier model prone to logical hallucinations and compile-time syntax errors.
* **Obfuscation via Label Retirement**: To mitigate user backlash, the changelog announced the formal retirement of the `(Preview)` and explicit model labels within the IDE interface, stating they were "no longer needed to guide user decisions." This effectively hid the underlying model identity from the end-user, making it impossible to audit which model executed a given prompt.
* **The Paid Upgrade Penalty**: Documentation revealed that if a student outgrew their 200-credit cap during high-demand workloads and paid to temporarily upgrade to a paid Pro tier, their verified educational account status was automatically revoked, forcing them to re-apply for the student pack in subsequent billing cycles.

---

## Core Grievances

### 1. Complete Loss of Architectural Autonomy
Forcing developers into a black-box auto-routing algorithm prevents technical users from selecting the correct model for a specific task. Fast, lightweight models are ideal for routine boilerplate code, while heavy reasoning models are required for debugging complex asynchronous logic. Forcing an automated router to make this decision based on infrastructure cost margins destroys developer velocity.

### 2. Information Obfuscation
The removal of explicit model identifiers and `(Preview)` labels from the IDE extension interface represents a regression in software transparency. Without clear visibility into which engine is compiling code, developers cannot file accurate bug reports, track context window limits, or understand how their credit pools are being drawn down.

### 3. Destruction of Educational Utility
Limiting verified students to an identical credit footprint as the standard Free tier ($2.00 USD monthly compute value) invalidates the core mission of the GitHub Student Developer Pack. Modern computer science workloads require analyzing multi-file repositories, an optimization task that immediately depletes a 200-credit pool via background context token replication.

---

## Our Demands

1. **Reinstate Manual Model Selection**: Allow Free and Student tiers to explicitly select their preferred model family (OpenAI, Anthropic, Google) based on task complexity.
2. **Mandate Interface Transparency**: Return explicit model name labels to the IDE extension dropdown menus so users can audit system performance.
3. **Protect Verified Educational Status**: Eliminate the automated downgrade penalty that revokes a user's verified student status if they consume paid overages or temporarily purchase higher credit tiers.
4. **Eliminate Usage Based Billing**: Return to the older flat rate model that was PERFECTLY SUSTAINABLE for Microsoft.

---

## How to Sign the Petition

To maintain a permanent, public record of community resistance, add your signature by submitting a **new issue**
## [SIGN THE PETITION](https://github.com/ilim-cell/copilot/issues/new?template=signature.yml)
