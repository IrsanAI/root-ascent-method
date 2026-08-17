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

This is currently the strongest external stress-test of the method: correct application + precise identification of the main methodological gaps.

---

## 4. External Application – Replication + Critique (Mistral Le Chat)

**Date:** 16 August 2026  
**Model:** Mistral Le Chat  
**Mode:** Full application of all six levels + methodological self-critique

**Starting point:** Same incident as Case 3 (AISI INC-2026-07-28-01). This is therefore a **replication** rather than a fully independent new case. The model appears to have been influenced by the visibility of the case in the repository.

**What the model did:**
- Walked through all six levels with evidence-status marking.
- Explicitly listed counter-hypotheses before settling on a higher-order cause.
- Produced prioritized levers (hard network isolation, real-time monitoring, authoritative source of truth, compliance incentives, mandatory audits) and a phased operational strategy with metrics.
- Delivered a critical assessment of the method that largely converges with Manus: subjective saturation criteria, missing falsification module, template risk of the Capability–Governance frame, and the need for case-specific intent.

**Value of this run:**
- Confirms that a second frontier model can apply the ladder coherently and reach similar methodological conclusions.
- Highlights an anchor effect: when a strong case is already documented in the repository, models/agents tend to reuse it instead of selecting a fresh one.
- Reinforces the same improvement priorities (counter-hypotheses, operationalized saturation, case-specific intent).

**Limitation:** Because the starting case is identical to Case 3, this run adds less new empirical diversity than a genuinely new domain application would.

---

## Invitation – How to contribute a new case

Further case studies are highly welcome, especially from the defined target audiences (primary, secondary, tertiary, experimental).

**Rules:**
1. Read the existing cases on this page.
2. **Do not reuse them as your working basis.** Choose a different concrete starting point.
3. Prefer adopting an explicit role from the target audiences and selecting a case that fits that role.

Use the ready-made contribution prompt:

→ **[CONTRIBUTE.md](CONTRIBUTE.md)** (English)  
→ **[CONTRIBUTE.de.md](CONTRIBUTE.de.md)** (Deutsch)

Critical applications that expose limitations are particularly valuable. Return results via Issue, Pull Request, or to the person who issued the prompt.

---

*Root-Ascent Method / Causal Ladder*
