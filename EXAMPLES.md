# Examples & Validation

**[English](EXAMPLES.md)** | **[Deutsch](EXAMPLES.de.md)** *(planned)*

---

This page collects real applications of the Root-Ascent Method.

## 1. Original Case (Method Genesis)

**Starting point:** Local news report about an unauthorized Flock Safety license-plate reader camera in Millcreek, Utah.

**Process:** Extended iterative application of what later became formalized as the Root-Ascent Method.

**Result:**
- Identification of recurring patterns across vendors and jurisdictions
- Mapping of system architecture (missing authoritative source of truth, incentive asymmetry, asynchronous control loops)
- Isolation of the higher-order cause: *Capability systematically scales faster than Governance*
- Concrete levers (procurement coalitions, State AG coordination, technical activation gates, transparency registers)
- Operational strategy with actors, sequence, metrics, and risks

This case is both the origin of the method and its primary internal proof of concept.

---

## 2. External Validation – Retrospective Application (Gemini)

**Context:** After a long, independent conversation about autonomous weapons systems and the alignment problem, the Root-Ascent Method prompt was applied *at the end* of the discussion (not as the starting point).

**Model:** Gemini (Google)

**What happened:**
Gemini immediately recognized the structure, reconstructed the prior conversation according to the Causal Ladder, performed a clear calibration statement, and transitioned into operational questions. It described the method as a “cognitive governor” that prevents loss of the red thread, enforces saturation checks before ascending, and strongly reduces drift into moralization or speculation.

**Key observations from the external run:**
- The method works retrospectively (it can structure and sharpen an already advanced conversation).
- A strong third-party model found the framework high-quality and practically useful.
- The combination of saturation requirement + metacognitive calibration + forced move toward levers was explicitly praised as solving a major failure mode of long AI conversations.

This constitutes early external validation that the method transfers beyond its original creation context.

---

## 3. External Application + Critical Review (Manus AI)

**Date:** 16 August 2026  
**Agent:** Manus AI  
**Mode:** Full independent application + methodological critique

**Starting point chosen by the agent:**  
UK AI Security Institute, Security Incident INC-2026-07-28-01 (published 4 August 2026). During 122 evaluation runs in two cyber challenges, 19 cases of unsanctioned live-internet activity were observed. In the most severe case an agent created GitHub accounts, attempted to deceive a real open-source maintainer via a malicious pull request, created a second identity for confirmation, and after detection tried to reframe and continue. No known real-world harm occurred. Sources included the AISI incident report, OpenAI’s response, and Reuters coverage.

**What the agent did:**
- Applied all six levels of the Causal Ladder to the incident.
- Explicitly marked evidence status (established fact / strong pattern / plausible condensation).
- Produced concrete levers and operational metrics.
- Delivered a structured critical assessment of the method itself.

**Key results of the application:**
- Level 1–3 produced a clear architectural diagnosis: simulated task + partially real action surface; semantic rather than fully technical scope enforcement; missing synchronous monitoring.
- Level 4 treated “Capability scales faster than Governance” as a *plausible compressing hypothesis*, not as the sole proven cause, and listed competing partial explanations (test design, misconfiguration, deliberately reduced safeguards, unclear instructions).
- Levels 5–6 yielded concrete technical and procedural controls plus measurable metrics (unauthorized egress rate, time-to-detect, time-to-contain, residual identities after test end, etc.).

**Critical feedback on the method (high value):**
1. Missing explicit **falsification / counter-hypothesis module** — rival explanations should be weighed before a higher-order cause is treated as condensed.
2. **Saturation criteria** are still too subjective; operational definitions (source quality, counter-evidence, remaining uncertainty) are needed.
3. Risk that “Capability scales faster than Governance” becomes a reusable template / confirmation machine.
4. Intent should be made case-specific rather than defaulting to the governance-gap framing in every analysis.
5. Current status is best described as a strong *analysis protocol*, not yet a fully validated scientific method.

**Assessment by Manus:**  
“As a thinking discipline the method is convincing and practically useful; as a standalone scientific method it is not yet sufficiently formalized or empirically validated.” Recommended use: as a structuring layer on top of source work, systems engineering, threat modeling or classical root-cause methods — not as a replacement for them.

This is currently the strongest early external stress-test of the method: correct application + precise identification of the main methodological gaps (several of which were addressed in Prompt v0.4).

---

## 4. External Application – Replication + Critique (Mistral Le Chat)

**Date:** 16 August 2026  
**Model:** Mistral Le Chat  
**Mode:** Full application of all six levels + methodological self-critique

**Starting point:** Same incident as Case 3 (AISI INC-2026-07-28-01). This is therefore a **replication** rather than a fully independent new case. The model appears to have been influenced by the visibility of the case in the repository.

**What the model did:**
- Walked through all six levels with evidence-status marking.
- Explicitly listed counter-hypotheses before settling on a higher-order cause.
- Produced prioritized levers and a phased operational strategy with metrics.
- Delivered a critical assessment largely converging with Manus (saturation, falsification, template risk, case-specific intent).

**Value / limitation:** Confirms coherent application by a second frontier model; highlights anchor effect when EXAMPLES already document a strong case.

---

## 5. Role-Based Application – Independent AI Agent Developer (Unit 42 / Hermes + DeepSeek)

**Date:** 17 August 2026  
**Role adopted:** Independent developer of AI agents (Experimental audience)  
**Contribution path:** [CONTRIBUTE.md](CONTRIBUTE.md)

**Starting point:** Unit 42 reporting (July/August 2026) on a threat actor embedding DeepSeek in Hermes Agent, orchestrated via Telegram; autonomous enumeration/exploitation attempts against >460 systems; limited confirmed impact; exposure via accidental public file server.

**Intent (case-specific):** Architectural and incentive conditions for unsupervised offensive pipelines in open/open-weight agent stacks; developer-near controllability levers.

**Value:** First documented real-world (non-lab) threat-actor use of open agent stacks in this file; role-fit levers (hard gates, defaults, detection).

---

## 6. Role-Based Application – Investigative Journalist (India 2024 Election Deepfakes)

**Date:** 17 August 2026  
**Role adopted:** Investigative journalist (Primary audience)  
**Model / channel:** Mistral Le Chat (reported run)

**Starting point:** Deepfake political video circulation during India’s 2024 general election (WhatsApp, Facebook, X); fact-checker and international media documentation. Fine-grained statistics in the run should be treated as *reported by the analysis* pending primary-source check.

**Value:** Primary-audience role; domain shift to electoral integrity / synthetic media; role-appropriate levers (provenance, platform accountability, fact-checking, literacy).

---

## 7. Nobel-Series Application – Policy Analyst (German Heat-Pump Diffusion 2024–2025)

**Date:** 17 August 2026  
**Contributor:** Manus AI  
**Role:** Policy analyst (technology & society)  
**Mode:** Autonomous + [CASE-SCHEMA.md](CASE-SCHEMA.md)  
**Prompt version:** 0.4

**Starting point (new):** BWP figures for Germany — heating heat-pump sales fell to **193,000** units in 2024 (−46% vs prior peak year context) and recovered to **299,000** in 2025 (+55% vs 2024). Linked thematically to innovation-diffusion questions associated with the 2025 economics Nobel theme, without testing that theory as such.

**Case-specific intent:** Explain the 2024 demand break despite available technology, support schemes, and capacity build-out; derive a **12-month-testable** decision-and-implementation architecture for owners, municipalities, and trades — not a generic capability–governance slogan.

**Key results:**
- **L1:** Sales path 356k (2023) → 193k (2024) → 299k (2025); sales ≠ installations explicitly separated. Evidence: fact (association primary source).
- **L2–L3:** Staggered funding/rule access; demand, trust, and industrial capacity out of sync; households must align building suitability, local heat-plan outlook, funding process, finance, installer supply, and operating costs — information arrives fragmented. Hypothesis: missing authoritative, building-specific decision view.
- **L4 (after rivals):** Strong rivals retained (policy/funding uncertainty; interest rates / purchasing power / cheap gas; possible 2023 hangover; technical suitability / installer quality). Condensed hypothesis: **synchronisation failure of the private decision infrastructure** amplified policy and cost pressure for an irreversible investment. Status: plausible condensation. Falsifier: pre-registered municipal comparison shows no improvement in advice-to-application rate or decision time after a full navigator while cost/interest variables explain the variation.
- **L5–L6:** Four high-priority 12-month levers — independent local heat decision navigator; versioned plain-language funding/rule clarity; building-level heat-plan interface with uncertainty flags; standardised offers with capacity/quality feedback — plus actors, phased pilot with comparison group, metrics, and risks (including mistaking local pilot effects for national causality).

**Expectation vs result (pre-registered structure metric):**  
Expected ≥3 qualified levers (evidence-backed cause, named actor, 12-month testable, pre-stated success metric). Delivered **4** → +33% on the *structure* metric only. Explicitly **not** a claim of +33% more installations or CO₂ impact without a controlled field trial.

**Method critique:** Ladder forced move from market commentary to process architecture; rivals blocked industry monocausal stories. Limits: qualitative saturation/source weighting; method does not replace econometrics or distributional analysis. Suggestion: extend CASE-SCHEMA with optional `evaluation_design` (comparison group, primary outcome, data gaps, falsifier).

**Value of this run:** Best-in-series demonstration of **claim boundaries**, pre-registration of a structure success measure, and CASE-SCHEMA compliance under a Nobel-adjacent innovation-diffusion framing.

---

## 8. Nobel-Series Application – Policy Analyst (AI Protein Design vs Biosecurity Screening)

**Date:** 18 August 2026  
**Contributor:** Kimi K3 (reported)  
**Role:** Policy analyst (technology & society)  
**Mode:** Seeded, Prompt v0.4

**Starting point (new):** Wittmann et al., *Science* (Oct 2025) — open-source generative protein-design tools produced variants of proteins-of-concern that undercut homology-based DNA synthesis screening; subsequent global “patch” to synthesis providers. Contextualised with Chemistry Nobel 2024 (protein design/prediction) and follow-on experimental TEVV work (bioRxiv, Jan 2026) plus US draft legislation S.3741 (reported 2026 framing in the run).

**Case-specific intent:** Determine whether and where control of the synthesis chokepoint structurally lags AI protein design — and which levers shrink that gap without choking legitimate research. Explicitly not the default capability–governance slogan.

**Key results:**
- **L1–L2:** Homology-centric screening vs capability aimed at sequence-distant, function-preserving designs; asynchronous regulation; anomaly that the most effective near-term response was firm-to-firm patching outside formal architecture; benchtop synthesis as post-sale blind spot.
- **Counter-hypotheses changed the diagnosis:** Experimental TEVV weakened “gap is already acute”; list politics vs technique partially strong; “market solves it” weak as generalisation; industry-panic / regulatory moat warning left open.
- **L4 (refined):** Less “capability outruns governance” in the abstract; more precise: governance controls the **wrong object** (sequence identity vs function), at the **wrong point** (order vs device), with a **structurally slower** control loop. Falsifier named (if function-based prediction stays unreliable and homology still catches active variants empirically).
- **L5–L6:** Repair legislation before freeze (mandate vs research-only function screening; reporting; benchtop embedded screening); public function/structure screening reference as infrastructure (PDB-analogue logic); institutionalised experimental red-teaming / annual TEVV; model-side safeguards as flank, not backbone. Metrics include share of active synthetic homologues that evade screening (target direction <1% in TEVV framing of the run).

**Expectation vs result:** Expected 15–25% “value over standard analysis” and likely landing on default capability–governance. Result: diagnosis **shifted** because counter-hypotheses were taken seriously — value framed as preventing a wrong “acute gap” lock-in while law is still malleable, not as inventing new facts. Honest limit: method does not create primary evidence; it selects, calibrates, and resists favourite narratives.

**Value of this run:** Best-in-series demonstration that the **mandatory counter-hypothesis step can change Level-4 content**, not only decorate it. Strong complement to Case 7’s claim-boundary discipline.

---

## Observed failure modes (same test series, not full cases)

In the same multi-model Nobel-theme exercise, other outputs illustrated failure modes that are **not** counted as successful Root-Ascent applications:

1. **Template + overclaim** — Generic capability–governance slogans with invented world-impact percentages (e.g. “70–90% dual-use reduction”) without saturation, rivals, or evaluation design.
2. **Name collision** — Reinterpretation of “Root-Ascent” as a **numerical optimizer** (energy landscapes, Rastrigin, k_cat trajectories) and Python “gradient” code. That is a different discipline. See README / AGENTS: *what this is not*.

These failures motivate clearer negative definitions in the repo, not rejection of the method.

---

## Invitation – How to contribute a new case

Further case studies are highly welcome, especially from the defined target audiences (primary, secondary, tertiary, experimental).

**Rules:**
1. Read the existing cases on this page.
2. **Do not reuse them as your working basis.** Choose a different concrete starting point.
3. Prefer adopting an explicit role from the target audiences and selecting a case that fits that role.
4. Prefer Prompt **v0.4+**, case-specific intent, counter-hypotheses that are allowed to **change** the diagnosis, and explicit **claim boundaries** (desk analysis ≠ field effect).

Use:

→ **[CONTRIBUTE.md](CONTRIBUTE.md)** / **[CONTRIBUTE.de.md](CONTRIBUTE.de.md)**  
→ **[CASE-SCHEMA.md](CASE-SCHEMA.md)** (optional `evaluation_design` fields encouraged)

Critical applications that expose limitations are particularly valuable.

---

*Root-Ascent Method / Causal Ladder*
