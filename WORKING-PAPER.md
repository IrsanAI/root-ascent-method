# Root-Ascent Method – Working Paper

**[English](WORKING-PAPER.md)** | **[Deutsch](WORKING-PAPER.de.md)**

---

**Status:** Draft / Living Document  
**Version:** 0.4 (August 2026)

## Abstract

This working paper documents the development, rationale, and structure of the Root-Ascent Method (Causal Ladder). The method provides a disciplined way to move from concrete incidents to systemic root causes and from there to actionable levers. It was created through extended human–AI collaboration and is deliberately domain-agnostic.

Version 0.4 records **implemented hardenings**: case-specific intent, saturation checks, mandatory counter-hypotheses before locking Level 4, a structured case schema, an explicit intent layer, and agent/contribute alignment.

## 1. Motivation

Complex socio-technical problems often share a failure pattern: capability scales faster than governance, oversight, and control. Public and internal analyses frequently stay at symptoms or jump into speculation, producing cycles of outrage, shallow reform, and structural drift.

Root-Ascent counters this through controlled causal ascent and deliberate return to the operational level.

## 2. Origins and proof of concept

The method emerged from an investigation that began with an unauthorized Flock Safety license-plate reader in Millcreek, Utah. Iterative questioning, evidence work, pattern detection, architectural analysis, and intent calibration crystallized into a generalizable method. Further applications and external critical reviews are in [EXAMPLES.md](EXAMPLES.md).

## 3. The Causal Ladder

1. Concrete Incident  
2. Patterns & Anomalies  
3. System Architecture  
4. Higher-Order Cause  
5. Levers  
6. Operational Strategy  

Executable rules: [PROMPT.md](PROMPT.md) v0.4. Compact reference: [METHOD.md](METHOD.md).

## 4. Design principles

- Evidence saturation before abstraction  
- Case-specific intent calibration as anti-drift mechanism  
- Preference for structural over purely personal explanations  
- Explicit transition from diagnosis to agency  
- Iterative question refinement  
- Domain-agnostic applicability  
- Counter-hypotheses before condensation of Level 4  

## 5. Intent layers

See [INTENT.md](INTENT.md).

- **Operational intent:** from symptoms to structural causes to changeable levers.  
- **Case-specific intent:** declared every run; not auto-defaulted to the governance gap.  
- **Higher repository intent:** a reusable discipline so intelligence can stay oriented and action-capable under acceleration — a protocol against drift, not only a case toolkit for governance gaps.  

The capability–governance framing remains a frequent and powerful *candidate* hypothesis. It must not become an unexamined template.

## 6. Target audiences

Primary, secondary, tertiary, and experimental audiences as in [README.md](README.md). Role-based contribution: [CONTRIBUTE.md](CONTRIBUTE.md).

## 7. Comparison with related approaches

Shares DNA with root-cause analysis, systems thinking, and intelligence cycles. Differs by: explicit ladder with saturation discipline; built-in intent calibration; mandatory move into operational strategy; explicit counter-hypothesis step (v0.4).

## 8. Limitations (honest status)

Root-Ascent is a strong **analysis protocol**, not yet a fully validated scientific method. It improves question sequence, reduces drift, and forces action-orientation. It does not guarantee correct root causes.

Remaining risks:

- Saturation checks can still be performed superficially  
- Template diagnosis if counter-hypotheses are listed but not truly weighed  
- Data quality dependence  
- Higher-order causes may themselves be symptoms  
- Structural focus can under-weight individual responsibility when it matters  
- Public-case bias  

## 9. What v0.4 implemented

| Hardening | Where |
|-----------|--------|
| Case-specific intent at run start | PROMPT v0.4, METHOD, AGENTS |
| Saturation checklist before ascent | PROMPT v0.4 |
| Mandatory counter-hypotheses before Level 4 | PROMPT v0.4, CASE-SCHEMA |
| Structured case fields | CASE-SCHEMA.md / .de.md |
| Explicit intent layers + meta-application | INTENT.md |
| No-reuse of EXAMPLES as working basis | CONTRIBUTE, AGENTS, EXAMPLES invitation |
| Agent orientation to v0.4 | AGENTS.md |

## 10. Further development

- Broader, higher-quality case base across domains  
- Multi-role protocol trials (same case, several intents/levers)  
- Optional parallel power-and-responsibility lens  
- Better multi-agent aggregation over CASE-SCHEMA fields  
- Empirical comparison against other frameworks (long-term)  

## References

[METHOD.md](METHOD.md) · [PROMPT.md](PROMPT.md) · [CASE-SCHEMA.md](CASE-SCHEMA.md) · [INTENT.md](INTENT.md) · [EXAMPLES.md](EXAMPLES.md) · [AGENTS.md](AGENTS.md) · [CONTRIBUTE.md](CONTRIBUTE.md) · [README.md](README.md)

---

*Living working paper. Critical applications and failures are as welcome as successes.*
