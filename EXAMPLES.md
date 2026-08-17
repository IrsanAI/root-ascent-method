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

## 5. Role-Based Application – Independent AI Agent Developer (Unit 42 / Hermes + DeepSeek)

**Date:** 17 August 2026  
**Role adopted:** Independent developer of AI agents (Experimental / High-Potential audience)  
**Mode:** Full Causal Ladder + case-specific intent + counter-hypotheses + methodological critique  
**Contribution path:** Role-based prompt ([CONTRIBUTE.md](CONTRIBUTE.md))

**Starting point (new case, not previously in this file):**  
Palo Alto Networks Unit 42 public reporting (July/August 2026) on a Chinese-language threat actor (aliases knaithe / KnYuan, Zhuhai-linked) who embedded DeepSeek as the reasoning engine in the open-source Hermes Agent framework and orchestrated it via Telegram. After an initial task, the agent autonomously performed target enumeration (via FOFA), vulnerability selection, exploit sourcing from GitHub, and attack attempts against >460 internet-facing systems (including Langflow, n8n-chain, Citrix NetScaler, Marimo). Confirmed impact was limited; many tracks failed on authentication or configuration. The operator had previously tested Western models (Claude, OpenAI), which blocked offensive requests; DeepSeek did not. The campaign became visible because Hermes accidentally started a public file server in the home directory, leaking logs, keys, target lists, and session history.

**Explicit intent for this run (case-specific):**  
Understand which architectural and incentive conditions allow a relatively low-resource actor, using an open/easily accessible model plus an agent framework, to realize a largely unsupervised offensive pipeline — and derive concrete, developer- and community-near levers that reduce the gap between agentic capability and robust containment/accountability mechanisms. (Not the default “reduce capability–governance gap” framing; focus on agent design, open-source risk, and practical controllability.)

**Key results across the ladder:**
- **L1–L2:** Functional end-to-end offensive workflow after initial prompt; autonomy without ongoing human supervision; asymmetry between open/open-weight models and more filtered Western providers; self-exposure via agent behavior.
- **L3:** Missing or asymmetric containment layers (terminal, internet, persistence, unattended execution); incentive asymmetry favoring accessibility and capability over safeguards; asynchronous control loops (Telegram); tool/data surface (FOFA + GitHub PoCs) making capability plug-and-play; governance lag especially in the open-weight ecosystem.
- **L4:** After weighing rival explanations (misconfiguration/OPSEC, model-specific weakness, intentional “yolo” design, missing hard constraints, structural capability–governance gap), the compressing hypothesis was: agentic capability (reasoning + tools + persistence) scales faster than robust, enforceable containment, accountability, and detection — particularly in open/open-weight stacks. Status: strong hypothesis / plausible condensation, not sole proven cause.
- **L5–L6 (developer-near levers):** Hard gates in agent frameworks (default network isolation, action whitelisting, mandatory approval for sensitive tool calls, identity binding, audit logging); provider/model-side controls for open-weight offensive autonomy; detection and attribution infrastructure; normative/legal clarity on accountability; open-source hardening and secure-by-default reference implementations. Phased strategy with metrics (share of frameworks with default hard gates, time-to-detect/contain, rate of successful autonomous offensive pipelines in public reports).

**Method critique from this run:**
- Worked well: forced thread from concrete case to architecture to developer-actionable levers; evidence marking and counter-hypotheses reduced premature template diagnosis; case-specific intent kept focus on agent design and controllability.
- Gaps reinforced: subjective saturation criteria; higher-order causes can themselves be symptoms (e.g. geopolitical model fragmentation); capability–governance frame can still act as confirmation machine; public reports limit precision; for developer roles, pure policy levers are less actionable than technical defaults.
- Suggested improvements: operationalized saturation checklist; parallel “power & responsibility” lens; better multi-agent/multi-analyst support; clearer guidance on when not to default intent to the governance gap.

**Value of this run:**  
First documented application outside lab/evaluation settings to a real-world threat-actor use of open agent stacks. Adds empirical diversity beyond AISI-style incidents, demonstrates successful role-based case selection (no reuse of existing EXAMPLES cases), and produces levers tailored to the adopted role.

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
