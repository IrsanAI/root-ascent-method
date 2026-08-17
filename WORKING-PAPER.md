# Root-Ascent Method – Working Paper

**[English](WORKING-PAPER.md)** | **[Deutsch](WORKING-PAPER.de.md)**

---

**Status:** Draft / Living Document  
**Version:** 0.4 (August 2026)

## Abstract

This working paper documents the development, rationale, and structure of the Root-Ascent Method (Causal Ladder). The method provides a disciplined way to move from concrete incidents to systemic root causes and from there to actionable levers. It was created through extended human–AI collaboration and is deliberately domain-agnostic.

Version 0.4 hardens the executable prompt (case-specific intent, saturation check, mandatory counter-hypotheses), adds a case schema for structured contributions, and records a higher-level reading of the repository intent.

## 1. Motivation

Complex socio-technical problems frequently exhibit the same failure pattern: capability scales faster than governance, oversight, and control. Public and internal analyses often stay at symptoms or jump into speculation, producing cycles of outrage and shallow reform.

Root-Ascent counters this through controlled causal ascent and deliberate return to the operational level.

## 2. Origins and Evidence Base

The method emerged from an investigation that began with an unauthorized Flock Safety ALPR camera (Millcreek, Utah) and crystallized into a generalizable process. External applications and critiques (Gemini, Manus AI, Mistral Le Chat, role-based runs on Unit 42/Hermes+DeepSeek and India 2024 election deepfakes) are documented in [EXAMPLES.md](EXAMPLES.md).

## 3. The Causal Ladder

1. Concrete Incident  
2. Patterns & Anomalies  
3. System Architecture  
4. Higher-Order Cause  
5. Levers  
6. Operational Strategy  

Ascent only after evidence saturation; descent into levers once the structural cause is sufficiently clear. See [METHOD.md](METHOD.md) and [PROMPT.md](PROMPT.md) v0.4.

## 4. Design Principles

- Evidence saturation before abstraction  
- Explicit case-specific intent + ongoing calibration  
- Mandatory counter-hypothesis weighing before locking Level 4  
- Preference for structural over purely personal explanations  
- Explicit transition from diagnosis to agency  
- Iterative question refinement  
- Domain-agnostic applicability  

## 5. Intent Layers (metacognitive note)

**Operational intent (per run):** Declared at the start of each application; case- and role-specific.

**Stated repository intent:** Help intelligence climb from noise and symptoms to structural causes and back down to what can be changed — often operationalized as understanding and reducing capability–governance gaps.

**Higher reading (v0.4):** The capability–governance framing is frequently correct but may itself be symptom-proximate. A broader intent is to provide a reusable discipline so that human and artificial intelligence remain oriented and action-capable under acceleration — a protocol against drift, not only a toolkit for governance gaps. Surveillance, agent incidents, and synthetic media remain primary proving grounds; the ladder can also be applied *to intents and strategies themselves* (treat the intent as the “incident”).

This higher reading does not replace the operational method; it situates it.

## 6. Target Audiences

Primary, secondary, tertiary, and experimental audiences as in [README.md](README.md). Role-based contribution: [CONTRIBUTE.md](CONTRIBUTE.md).

## 7. Comparison with Related Approaches

Shares DNA with root-cause analysis, systems thinking, and intelligence cycles. Differs by: explicit ladder + saturation checks; intent calibration; mandatory counter-hypotheses before Level-4 lock (v0.4); mandatory move into operational strategy.

## 8. Limitations

Still best described as a strong *analysis protocol*, not a fully validated scientific method. Known residual risks:

- Saturation checks improve honesty but remain partly qualitative  
- Template diagnosis of “Capability > Governance” can still occur if counter-hypotheses are performed mechanically  
- Quality depends on available public data  
- Higher-order causes may themselves be symptoms of deeper conditions  
- Structural focus can under-weight individual responsibility when relevant  

## 9. Hardening implemented in v0.4

| Item | Where |
|------|--------|
| Case-specific intent at start of every run | [PROMPT.md](PROMPT.md) |
| Saturation checklist before ascent | [PROMPT.md](PROMPT.md) |
| Mandatory counter-hypothesis step before Level 4 | [PROMPT.md](PROMPT.md) |
| Structured case schema for contributions | [CASE-SCHEMA.md](CASE-SCHEMA.md) |
| Explicit note on applying method to intents/strategies | PROMPT + this paper |
| Role-based contribution without reusing EXAMPLES cases | [CONTRIBUTE.md](CONTRIBUTE.md) |

## 10. Future Development

- Multi-role protocol: same case, parallel roles, compare levers  
- Richer multi-agent / shared knowledge-matrix support  
- Optional parallel “power & responsibility” lens  
- Broader case base and community stress tests  
- Stronger evaluation of inter-analyst reliability  

## References

- [METHOD.md](METHOD.md) · [PROMPT.md](PROMPT.md) · [EXAMPLES.md](EXAMPLES.md) · [CASE-SCHEMA.md](CASE-SCHEMA.md) · [CONTRIBUTE.md](CONTRIBUTE.md) · [AGENTS.md](AGENTS.md) · [README.md](README.md)

---

*Living working paper. Critical applications and improvements welcome via Issues or Pull Requests.*
