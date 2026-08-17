# Contribute – Role-Based Application Prompt

**[English](CONTRIBUTE.md)** | **[Deutsch](CONTRIBUTE.de.md)**

For humans, online LLMs, and AI agents who want to contribute by applying Root-Ascent Method v0.4 — not only discussing it.

## Core rules

1. Read existing cases in [EXAMPLES.md](EXAMPLES.md). **Do not use them as your working basis.**
2. Use discipline from [PROMPT.md](PROMPT.md) v0.4 (case-specific intent, saturation checks, counter-hypotheses before Level 4, claim boundaries).
3. Prefer structuring the result with [CASE-SCHEMA.md](CASE-SCHEMA.md).
4. Optional: [INTENT.md](INTENT.md) if you apply the method to an intent or strategy itself.

### Paste-fallback

If you **cannot** fetch repository files through your tools: **stop and request a paste** of at least `AGENTS.md`, `PROMPT.md`, and `EXAMPLES.md` (plus optionally `CASE-SCHEMA.md` / this file). Do not invent the method. See also [AGENTS.md](AGENTS.md).

---

## Contribution Prompt (copy and use)

```text
You are invited to contribute to the Root-Ascent Method (Causal Ladder) v0.4 by applying it.

Repository: https://github.com/IrsanAI/root-ascent-method
Landing page: https://irsanai.github.io/root-ascent-method/

Required reading:
- AGENTS.md – orientation for agents (includes paste-fallback and what-this-is-not)
- PROMPT.md v0.4 – executable discipline (intent, saturation, counter-hypotheses, claim boundaries)
- METHOD.md – ladder and rules
- EXAMPLES.md – existing cases (read, then do not reuse as your case)
- CASE-SCHEMA.md – structured fields for your output
- INTENT.md – optional, for intent-layer / meta runs

If you cannot load these files: stop and request a paste. Do not guess the method.

Your task:

1) Adopt a role from the target audiences and state it clearly:

   Primary: investigative journalist; independent researcher; civil-society technologist; technology & society policy analyst; advanced AI user

   Secondary: academic researcher (STS / security studies / public policy / information ethics); digital-rights organization staff; strategic team in government or regulator

   Tertiary: think-tank analyst; OSINT practitioner; professional in complex socio-technical risk

   Experimental: PhD / research lab; independent AI-agent developer; data-journalism team; civic technologist; city innovation / public technology unit

2) Select a suitable case for that role
   - Concrete, current or recent, publicly documentable
   - NOT already listed as a working case in EXAMPLES.md (cases 1–9 and any later entries)
   - State why the case fits the role

3) Declare a case-specific intent (1–3 sentences). Do not auto-default to “reduce the capability–governance gap” unless it truly fits.

4) Apply Root-Ascent Method v0.4 fully
   - All six levels
   - Evidence status: fact / strong pattern / hypothesis
   - Saturation check before ascending
   - Before locking Level 4: list and weigh rival explanations; state what would falsify the condensed hypothesis; allow rivals to change the diagnosis
   - End with levers and operational strategy (actors, sequence, metrics, risks) — or state why not yet saturated enough to descend
   - Respect claim boundaries: desk analysis is not proof of field impact percentages

5) Critically assess the method
   What worked? Gaps or risks? What would you improve?

6) Optionally fill CASE-SCHEMA.md fields (YAML or equivalent).

Optional multi-role protocol:
   Same concrete case under two or more roles; compare where diagnoses converge and levers diverge.

Stay disciplined and evidence-oriented.
```

### Short activation version

```text
Adopt one Root-Ascent target-audience role. Read PROMPT v0.4, METHOD, EXAMPLES, CASE-SCHEMA (request paste if files unavailable). Do not reuse EXAMPLES cases. Choose a concrete role-fit case. Declare case-specific intent. Full Causal Ladder with saturation checks and counter-hypotheses before Level 4. Finish with levers/strategy, claim boundaries, and method critique. Optionally emit CASE-SCHEMA fields. Repo: https://github.com/IrsanAI/root-ascent-method
```

---

## How to return results

GitHub Issue or Pull Request, or send the full run to whoever issued this prompt. Failures and limitations are valuable.

---

*Root-Ascent Method / Causal Ladder · Contribute v0.4 (+ paste-fallback)*
