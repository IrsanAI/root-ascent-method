# Case Schema (Root-Ascent Method)

**Version:** 0.4.1  
Minimal structure for documenting a Root-Ascent run. Use in Issues, PRs, agent outputs, or EXAMPLES entries.

Human-readable prose is fine; filling these fields makes cases comparable and aggregable.

---

## Required fields

```yaml
meta:
  date: YYYY-MM-DD
  contributor: string          # human, model, or agent name
  role: string                 # from target audiences (primary/secondary/tertiary/experimental)
  mode: seeded | autonomous | retrospective
  prompt_version: "0.4"       # or later

intent:
  statement: string            # case-specific, 1–3 sentences
  notes: string                # optional: why not the default governance-gap framing

case:
  title: string
  summary: string              # short factual description
  not_in_examples: true        # must be true for new contributions
  sources:                     # primary public sources
    - url_or_citation: string

ladder:
  L1_incident:
    findings: string
    evidence_status: fact | strong_pattern | hypothesis | mixed
  L2_patterns:
    findings: string
    evidence_status: fact | strong_pattern | hypothesis | mixed
  L3_architecture:
    findings: string
    evidence_status: fact | strong_pattern | hypothesis | mixed
  L4_higher_order_cause:
    rival_explanations:
      - explanation: string
        weight: strong | weak | ruled_out | unresolved
    condensed_hypothesis: string
    status: plausible_condensation | strong_hypothesis | open
    what_would_falsify: string
    diagnosis_changed_by_rivals: true | false   # did counter-hypotheses change L4?
  L5_levers:
    - description: string
      priority: high | medium | low
  L6_operational_strategy:
    actors: string
    sequence: string
    metrics: string
    risks: string

method_critique:
  what_worked: string
  gaps_or_friction: string
  suggested_improvements: string

saturation_notes: string       # optional honesty about where evidence was thin
```

---

## Optional (strongly recommended for “how much better” claims)

```yaml
expectation:
  pre_registered_structure_metric: string   # e.g. "≥3 levers with cause+actor+12m test+metric"
  expected_value: string
  actual_value: string
  notes: string                             # never confuse structure metrics with field impact

evaluation_design:                          # required if claiming field outcomes
  comparison_group: string
  primary_outcome: string
  data_gaps: string
  falsification_rule: string
claim_boundary: string                      # e.g. "desk strategy only; no claimed % sales lift"
```

---

## Evidence status values

| Value | Meaning |
|-------|--------|
| `fact` | Sourced / strongly corroborated |
| `strong_pattern` | Recurring, multiply indicated |
| `hypothesis` | Plausible, not condensed |
| `mixed` | Combination; explain in findings |

---

## Notes

- Do not reuse cases already listed in [EXAMPLES.md](EXAMPLES.md) as the working basis for a *new* contribution.
- Counter-hypotheses at L4 are mandatory; set `diagnosis_changed_by_rivals` honestly.
- Fine-grained statistics should be marked if not cross-checked against primary sources.
- This schema is for the **Causal Ladder** method — not for numerical optimizers.

See also: [CONTRIBUTE.md](CONTRIBUTE.md), [PROMPT.md](PROMPT.md), [EXAMPLES.md](EXAMPLES.md).

---

*Root-Ascent Method / Causal Ladder*
