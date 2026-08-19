# Prompt-Factory – Root-Ascent Method

**[English](PROMPT-FACTORY.md)** | **[Deutsch](PROMPT-FACTORY.de.md)**

Baue die **passende Prompt** für dein Vorhaben. Zwei Ausgabe-Typen:

| Typ | Wann |
|-----|------|
| **Full run** | Vollständige Kausalleiter (Chat, Agent, Recherche) |
| **Embed-Snippet** | Kurzer Block für *jedes* Textfeld zu Stil, Intent, Leitplanken oder Feintuning (NotebookLM Audio, Suno, andere Studios, Agent-Systemfelder, Mid-Thread-Kalibrierung) |

Repo: https://github.com/IrsanAI/root-ascent-method  
Landingpage: https://irsanai.github.io/root-ascent-method/

Immer beachten: [AGENTS.de.md](AGENTS.de.md) · [PROMPT.de.md](PROMPT.de.md) v0.4 · [EXAMPLES.md](EXAMPLES.md) (**Fälle 1–15 nicht als Arbeitsgrundlage**) · *What this is not* (kein numerischer Optimizer).

---

## 1. Entscheidungspfad (User wählt)

1. **Sprache:** Deutsch | Englisch (passende Factory-Datei).  
2. **Ausgabe-Typ:** Full run | Embed-Snippet.  
3. **Modus (Full run):** Autonomous | Seeded (URL/Text) | Seeded commercial | Investigation-open | Mid-Thread-Rekalibrierung | Gesprächsabschluss.  
4. **Rolle (Full run):** Primär / Sekundär / Tertiär / Experimentell — eine benennen.  
5. **Intent-Fokus (optional):** Legitimität · Kontrolle/Macht · Wertschöpfung · Sicherheit/Resilienz · Verteilung/Gerechtigkeit · journalistische Aufdeckung · kreative Form · anderes.  
6. **Claim-Härte:** Standard | Streng (keine Feld-%, provisional L4 wenn Verfahren offen).

Danach passendes Template kopieren und Klammern füllen.

---

## 2. Embed-Snippets (hohe Hebelwirkung)

Wenn ein anderes Produkt nur ein **kleines Textfeld** anbietet („worauf achten?“, „Style“, „Constraints“): Das Modell soll aus **Gesamtkontext + Methode** einen hochdimensionalen Intent **selbst ableiten**.

### 2.1 Universal-Embed (Default)

```text
Wende die Root-Ascent Method (Kausalleiter) als Intent- und Qualitätsdisziplin an:
https://github.com/IrsanAI/root-ascent-method
Leite aus dem hier verfügbaren Gesamtkontext einen klaren fallbezogenen Intent ab, nenne plausible Gegenhypothesen und beachte Claim-Grenzen (keine erfundenen Fakten oder Wirkungsprozente). Bevorzuge nachvollziehbare Struktur vor generischen Stil-Klischees oder Tool-Defaults.
```

### 2.2 NotebookLM / Studio-Audio (Podcast)

```text
Nutze bei der Erzeugung dieses Audio-Überblicks die Root-Ascent Method (Kausalleiter):
https://github.com/IrsanAI/root-ascent-method
Leite aus den Quellen in diesem Notebook ab: (1) einen präzisen kommunikativen Intent, (2) was nicht überbehauptet werden darf, (3) rivalisierende Deutungen, die Hörerinnen haben könnten, (4) eine Struktur von konkreter Evidenz zu Mustern und praktischen Takeaways—ohne Jargon-Show. Keine erfundenen Zitate, Zahlen oder Scheinsicherheit bei dünner Quellenlage.
```

### 2.3 Musik- / Style-Feld (z. B. Suno)

```text
Leite Stil- und Arrangement-Prioritäten mit der Root-Ascent Method ab:
https://github.com/IrsanAI/root-ascent-method
Aus Briefing und ggf. Quellen einen impliziten Intent formulieren (Publikum, Spannung, Anspruch des Stücks), eindimensionale „Trend“-Defaults verwerfen, wenn sie dem Intent widersprechen, und Kohärenz halten. Das ist ästhetische Disziplin, keine Erfolgsgarantie.
```

### 2.4 Mid-Thread-Rekalibrierung

```text
Pause und Rekalibrierung mit Root-Ascent Method v0.4:
https://github.com/IrsanAI/root-ascent-method
Intent aus dem bisherigen Gespräch neu formulieren. Rivalen nennen, die die aktuelle Diagnose ändern könnten. Drift in Slogans oder erfundene Wirkungsprozente markieren. Erst dann fortfahren.
```

### 2.5 Gesprächsabschluss / Synthese

```text
Schließe diesen Thread mit Root-Ascent-Disziplin:
https://github.com/IrsanAI/root-ascent-method
Synthese: Intent → stärkste evidenzgestützte Muster → Architektur → vorläufige höhere Ursache (mit Rivalen) → Hebel oder explizit „noch nicht gesättigt“. Keine neuen unbelegten Claims.
```

---

## 3. Full-Run-Templates

### 3.1 Autonomous (rollenbezogen)

```text
Arbeite mit https://github.com/IrsanAI/root-ascent-method (zuerst AGENTS, PROMPT v0.4, EXAMPLES; Paste-Fallback wenn Dateien fehlen).
Fälle 1–15 in EXAMPLES nicht als Arbeitsgrundlage nutzen.
Rolle: [ROLLE]. Modus: Autonomous.
Frischen öffentlichen Fall wählen; fallbezogenen Intent deklarieren (kein automatischer Capability–Governance-Default).
Volle Kausalleiter L1–L6: Sättigung; Rivalen vor L4 (dürfen Diagnose ändern); Hebel + operative Strategie; Claim-Grenzen.
Ende: Erwartung vs. Ergebnis nur an Strukturmaßen. Kein numerischer Optimizer.
```

### 3.2 Seeded – Artikel / URL

```text
Arbeite mit https://github.com/IrsanAI/root-ascent-method (AGENTS, PROMPT v0.4, EXAMPLES; Paste-Fallback).
Fälle 1–15 nicht wiederverwenden.
Modus: Seeded. Rolle: [ROLLE].
Seed: [URL ODER TEXT]
Fakten / journalistisches Framing / Spekulation trennen. Fallbezogener Intent: [1–3 Sätze oder „aus Seed + Rolle ableiten“].
Volle Leiter L1–L6; Rivalen vor L4; Hebel; Claim-Grenzen; Erwartung vs. Ergebnis nur strukturell.
```

### 3.3 Seeded commercial

```text
Arbeite mit https://github.com/IrsanAI/root-ascent-method.
Modus: Seeded commercial. Rolle: unabhängiger Business-/Technologie-Analyst (oder andere).
Gegenstand: [Unternehmenstyp / anonymisierte Beschreibung / öffentliche URL falls erlaubt].
Leitfrage: [z. B. nachhaltige Wertschöpfung mit KI für diesen Typ].
Intent: überprüfbare Angebotsarchitektur und Kontrollpunkte—kein Hype, keine erfundenen Umsatz-%.
Volle Leiter; Rivalen dürfen „Tool-Weiterverkauf = Geschäft“ verwerfen; experimentelle Hebel; strenge Claim-Grenzen.
```

### 3.4 Investigation-open

```text
Arbeite mit https://github.com/IrsanAI/root-ascent-method (PROMPT v0.4).
Modus: Investigation-open. Rolle: [z. B. investigativer Journalist].
Vorfall: [was gesichert vs. unter Untersuchung].
L4 als provisional markieren. Evidenz event-spezifisch vs. sektor-weit trennen.
Rivalen müssen reinen lokalen Technikdefekt einschließen. Keine Schuld-/Ursachenzuweisung über die Beleglage hinaus.
Hebel als testbare Systemproben, nicht als Schuldspruch.
```

### 3.5 Kreativer Full run (Form selbst)

```text
Arbeite mit https://github.com/IrsanAI/root-ascent-method.
Modus: Creative derivation. Rolle: [Redaktion / Produktion / Künstler-Recherche].
Material: [Quellen, Briefing, Publikum].
Intent: welche Formentscheidungen (Länge, Ton, Konflikt, Evidenzdichte) aus Material und Zweck folgen—nicht aus Plattform-Klischee.
Leichte Leiter: konkretes Material → Publikum/Risiko-Muster → Produktionsarchitektur → Form-Hypothese (mit Rivalen) → Produktionshebel → Testplan.
Claim-Grenze: Form-Hypothese, kein Erfolgszertifikat.
```

---

## 4. Qualitätsleiste

- Fallbezogener Intent genannt oder abgeleitet  
- Rivalen dürfen Diagnose/Formwahl ändern  
- Keine Optimizer-Umdeutung von „Root-Ascent“  
- Keine erfundenen Feldwirkungsprozente  
- EXAMPLES-Fälle nicht als neuer Arbeitsfall recycelt  

---

## 5. Warum Embed-Modus zählt

Die Methode ist nicht nur ein langes Analyseritual. Der Repo-Verweis in **beliebigen Constraint-Feldern** erhöht die Intent-Dimensionalität in Podcast-Studios, Musik-Style-Boxen, Agent-Configs und Mid-Chat-Recovery—während die volle Leiter bleibt, wenn Tiefe nötig ist.

---

*Root-Ascent Method / Causal Ladder · Prompt-Factory v0.1 · 2026*
