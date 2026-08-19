# Prompt Factory – Root-Ascent Method

**[English](PROMPT-FACTORY.md)** | **[Deutsch](PROMPT-FACTORY.de.md)**

Build the **right prompt** for your use case. Two output types:

| Type | When |
|------|------|
| **Full run** | A complete Causal Ladder analysis (chat, agent, research) |
| **Embed snippet** | A short block for *any* text field that asks for style, intent, constraints, or fine-tuning (NotebookLM Audio, Suno, other studios, agent system fields, mid-thread recalibration) |

Repo: https://github.com/IrsanAI/root-ascent-method  
Landing: https://irsanai.github.io/root-ascent-method/

Always respect: [AGENTS.md](AGENTS.md) · [PROMPT.md](PROMPT.md) v0.4 · [EXAMPLES.md](EXAMPLES.md) (**do not reuse Cases 1–15** as your working basis) · *What this is not* (not a numerical optimizer).

---

## 1. Decision path (user chooses)

1. **Language:** English | German (use matching factory file).
2. **Output type:** Full run | Embed snippet.
3. **Mode (full run):** Autonomous | Seeded (URL/text) | Seeded commercial | Investigation-open | Mid-thread recalibration | End-of-conversation synthesis.
4. **Role (full run):** Primary / Secondary / Tertiary / Experimental — pick one and name it.
5. **Intent focus (optional tags):** legitimacy · control/power · value capture · safety/resilience · distribution/fairness · journalistic exposure · creative form · other (free text).
6. **Claim hardness:** Standard | Strict (no field-impact %; provisional L4 if investigation open).

Then copy the matching template below and fill brackets.

---

## 2. Embed snippets (high leverage)

Use when another product only offers a **small text box** for “how should this be made / what to prioritize.” The model should **derive** a high-dimensional intent from context + this method — you do not need to write the full ladder by hand.

### 2.1 Universal embed (default)

```text
Apply the Root-Ascent Method (Causal Ladder) as intent and quality discipline:
https://github.com/IrsanAI/root-ascent-method
From the full context available here, derive a clear case-specific intent, name plausible rival explanations, and respect claim boundaries (no invented facts or impact percentages). Prefer accountable structure over generic style clichés or tool defaults.
```

### 2.2 NotebookLM / studio audio (podcast)

```text
When generating this audio overview, use the Root-Ascent Method (Causal Ladder):
https://github.com/IrsanAI/root-ascent-method
Infer from the sources in this notebook: (1) a precise communicative intent, (2) what must not be overclaimed, (3) rival interpretations listeners might hold, (4) a structure that moves from concrete evidence toward higher-order patterns and practical takeaways—without turning the episode into jargon. No fabricated quotes, numbers, or certainty where sources are thin.
```

### 2.3 Music / style field (e.g. Suno)

```text
Derive style and arrangement priorities using the Root-Ascent Method:
https://github.com/IrsanAI/root-ascent-method
From the brief and any sources, state an implicit intent (audience, tension, claim of the piece), reject one-dimensional “trending” defaults when they conflict with that intent, and keep the result coherent. This is aesthetic discipline, not a guarantee of commercial success.
```

### 2.4 Mid-thread recalibration (paste into an ongoing chat)

```text
Pause and recalibrate with Root-Ascent Method v0.4:
https://github.com/IrsanAI/root-ascent-method
Re-state case-specific intent from this conversation so far. List rivals that could change the current diagnosis. Flag any drift into slogans or invented impact %. Only then continue.
```

### 2.5 End-of-conversation synthesis

```text
Close this thread using Root-Ascent Method discipline:
https://github.com/IrsanAI/root-ascent-method
Synthesize: intent → strongest evidence-backed patterns → architecture → provisional higher-order cause (with rivals) → levers or explicit “not yet saturated.” No new unsupported claims.
```

---

## 3. Full-run templates

### 3.1 Autonomous (role-based)

```text
Work with https://github.com/IrsanAI/root-ascent-method (read AGENTS, PROMPT v0.4, EXAMPLES first; paste-fallback if files unavailable).
Do not reuse EXAMPLES Cases 1–15 as your working basis.
Role: [NAME ROLE]. Mode: Autonomous.
Pick a fresh public case; declare case-specific intent (no automatic capability–governance default).
Full Causal Ladder L1–L6: saturation checks; rivals before L4 (may change diagnosis); levers + operational strategy; claim boundaries.
End with expectation vs result on structure metrics only. Not a numerical optimizer.
```

### 3.2 Seeded – article / URL

```text
Work with https://github.com/IrsanAI/root-ascent-method (AGENTS, PROMPT v0.4, EXAMPLES; paste-fallback if needed).
Do not reuse Cases 1–15.
Mode: Seeded. Role: [ROLE].
Seed: [URL OR PASTE]
Separate facts / reporting frame / speculation. Case-specific intent: [1–3 sentences or “derive from seed + role”].
Full ladder L1–L6; rivals before L4; levers; claim boundaries; expectation vs result on structure only.
```

### 3.3 Seeded commercial (firm or product type)

```text
Work with https://github.com/IrsanAI/root-ascent-method (AGENTS, PROMPT v0.4, EXAMPLES).
Mode: Seeded commercial. Role: independent business/technology analyst (or name another).
Subject: [company type / anonymized description / public URL if allowed].
Lead question: [e.g. how can this type of firm create sustainable value with AI?]
Intent: verifiable offer architecture and control points for value capture—not hype, not invented revenue %.
Full ladder; rivals must be allowed to kill “tool resale = business”; experiment-style levers; strict claim boundaries.
```

### 3.4 Investigation-open

```text
Work with https://github.com/IrsanAI/root-ascent-method (PROMPT v0.4).
Mode: Investigation-open. Role: [e.g. investigative journalist].
Incident: [what is established vs under investigation].
Mark L4 as provisional. Prefer event-specific vs sector-level evidence labels.
Rivals must include pure local technical failure. No cause attribution beyond public evidence.
Levers as testable system probes, not guilt assignment.
```

### 3.5 Creative full run (when you want the ladder applied to form itself)

```text
Work with https://github.com/IrsanAI/root-ascent-method.
Mode: Creative derivation. Role: [editor / producer / artist-researcher].
Materials: [sources, brief, audience].
Intent: which structural choices of form (length, tone, conflict, evidence density) follow from materials and purpose—not from platform cliché.
Climb a lightweight ladder: concrete materials → patterns of audience/risk → production architecture → form hypothesis (with rivals) → production levers → test plan.
Claim boundary: form hypothesis, not guaranteed performance.
```

---

## 4. Quality bar (all outputs)

- Case-specific intent stated or derived  
- Rivals allowed to change the diagnosis / form choice  
- No numerical-optimizer reinterpretation of “Root-Ascent”  
- No invented field-impact percentages  
- EXAMPLES cases not recycled as the new working case  

---

## 5. Why embed mode matters

The method is not only a long analysis ritual. Pointing models at this repository inside **arbitrary constraint fields** lets them raise intent dimensionality in podcast studios, music style boxes, agent configs, and mid-chat recovery—while the full ladder remains available when depth is required.

---

*Root-Ascent Method / Causal Ladder · Prompt Factory v0.1 · 2026*
