# Fall-Schema (Root-Ascent Method)

**[English](CASE-SCHEMA.md)** | **[Deutsch](CASE-SCHEMA.de.md)**  
**Version:** 0.4

Minimale Struktur zur Dokumentation eines Root-Ascent-Laufs. Nutzbar in Issues, PRs, Agent-Outputs oder EXAMPLES-Einträgen.

Prosa ist erlaubt; ausgefüllte Felder machen Fälle vergleichbar und aggregierbar.

---

## Pflichtfelder

```yaml
meta:
  date: YYYY-MM-DD
  contributor: string          # Mensch, Modell oder Agent
  role: string                 # aus den Zielgruppen
  mode: seeded | autonomous | retrospective
  prompt_version: "0.4"

intent:
  statement: string            # fallbezogen, 1–3 Sätze
  notes: string                # optional: warum nicht Default Governance-Gap

case:
  title: string
  summary: string
  not_in_examples: true        # bei neuen Beiträgen Pflicht
  sources:
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

saturation_notes: string
```

---

## Evidenzstatus

| Wert | Bedeutung |
|------|-----------|
| `fact` | Quellenbasiert / stark abgesichert |
| `strong_pattern` | Wiederkehrend, mehrfach indiziert |
| `hypothesis` | Plausibel, nicht verdichtet |
| `mixed` | Mischung; in findings erklären |

---

## Hinweise

- Fälle aus [EXAMPLES.md](EXAMPLES.md) nicht als Arbeitsgrundlage für *neue* Beiträge wiederverwenden.
- Gegenhypothesen auf L4 sind inhaltlich Pflicht.
- Feinzahlen kennzeichnen, wenn nicht gegen Primärquellen geprüft.

Siehe: [CONTRIBUTE.de.md](CONTRIBUTE.de.md), [PROMPT.de.md](PROMPT.de.md), [EXAMPLES.md](EXAMPLES.md).

---

*Root-Ascent Method / Causal Ladder*
