# Root-Ascent Method – Working Paper

**[English](WORKING-PAPER.md)** | **[Deutsch](WORKING-PAPER.de.md)**

---

**Status:** Entwurf / Living Document  
**Version:** 0.3 (August 2026)

## Abstract

Dieses Working Paper dokumentiert die Entwicklung, Begründung und Struktur der Root-Ascent Method (auch bekannt als Causal Ladder Method / Kausalleiter-Methode). Die Methode bietet einen disziplinierten Weg, von konkreten Vorfällen zu systemischen Ursachen und von dort zu handlungsfähigen Hebeln zu gelangen. Sie entstand vollständig durch erweiterte Mensch-KI-Kollaboration und ist bewusst domänenagnostisch.

## 1. Motivation

Komplexe sozio-technische Probleme (Überwachungsinfrastrukturen, KI-Governance, Plattformmacht, kritische Systeme usw.) zeigen häufig dasselbe Versagensmuster: Technische oder organisatorische Capability skaliert deutlich schneller als die dazugehörige Governance-, Aufsichts- und Kontrollfähigkeit.

Die meisten öffentlichen und internen Analysen bleiben auf der Ebene einzelner Vorfälle oder Symptome stehen. Das führt zu wiederkehrenden Zyklen aus Empörung, begrenzten Reformen und fortgesetzter struktureller Drift.

Die Root-Ascent Method wurde entwickelt, um diesem Muster durch kontrollierten, iterativen kausalen Aufstieg in Kombination mit bewusster Rückkehr auf die operative Ebene entgegenzuwirken.

## 2. Entstehung und Proof of Concept

Die Methode entstand aus einem intensiven, mehrstufigen investigativen Dialog, der mit einer einzelnen unerlaubt installierten Kennzeichenleser-Kamera (Flock Safety, Millcreek, Utah) begann. Durch wiederholte Zyklen aus Fragen, Evidenzsammlung, Mustererkennung, Architekturanalyse und strenger Selbstkalibrierung gegen den Intent kristallisierte sich der Prozess selbst zu einer verallgemeinerbaren Methode.

Was als enge Vorfallanalyse begann, erzeugte:
- Identifikation wiederkehrender Muster über Hersteller und Jurisdiktionen hinweg
- Kartierung der systemischen Architektur (fehlende Authoritative Source of Truth, Anreiz-Asymmetrie, asynchrone Kontrollschleifen)
- Isolation der höheren Ursache: Capability skaliert systematisch schneller als Governance
- Konkrete Hebel und eine realistische operative Strategie

Diese Entwicklung dient als primärer empirischer Nachweis. Weitere externe Anwendungen und kritische Reviews sind in [EXAMPLES.md](EXAMPLES.md) dokumentiert.

## 3. Die Kausalleiter im Detail

(Siehe auch die kompakte Version in [METHOD.de.md](METHOD.de.md))

1. Konkreter Vorfall
2. Muster & Anomalien
3. Systemarchitektur (Anreize, Kontrollschleifen, fehlende Authoritative Sources of Truth usw.)
4. Höhere Ursache
5. Hebel
6. Operative Strategie

Der Wechsel zwischen den Ebenen ist kontrolliert: Aufstieg nur nach Evidenz-Sättigung; Abstieg in die Hebel, sobald die strukturelle Ursache hinreichend klar ist.

## 4. Gestaltungsprinzipien

- Evidenz-Sättigung vor Abstraktion
- Intent-Kalibrierung als Anti-Drift-Mechanismus
- Bevorzugung struktureller gegenüber personaler Erklärungen
- Expliziter Übergang von Diagnose zu Handlungsfähigkeit
- Iterative Frageschärfung als Kernmotor
- Domänenagnostische Anwendbarkeit

## 5. Zielgruppen

**Primär:** Investigative Journalisten, unabhängige Forscher, Civil-Society-Technologen, Technik-Policy-Analysten und fortgeschrittene KI-Nutzer.

**Sekundär:** Akademische Forscher in STS, Security Studies, Public Policy und Informationsethik; digitale Bürgerrechtsorganisationen; strategische Teams in Verwaltungen und Regulierungsbehörden.

**Tertiär:** Think-Tank-Analysten, OSINT-Praktiker und Fachleute für komplexe sozio-technische Risiken.

**Experimentell / Hochpotenzial:** Promovierende und Labore in STS / AI Governance / Critical Security Studies, unabhängige Entwickler von KI-Agenten, Data-Journalism-Einheiten, Civic Technologists und zukunftsorientierte Teams im öffentlichen Sektor.

## 6. Vergleich mit verwandten Ansätzen

Root-Ascent teilt DNA mit klassischer Root-Cause-Analysis, Systems Thinking und Intelligence-Analysis-Zyklen, unterscheidet sich aber in drei Punkten:
- Explizite kontrollierte Leiter mit Sättigungskriterien
- Eingebaute Intent-Kalibrierung gegen Drift
- Verpflichtender Übergang von Diagnose in operative Strategie statt reine Verstehensarbeit

## 7. Grenzen und bekannte Lücken

Die folgenden Grenzen werden ausdrücklich anerkannt. Mehrere wurden durch eine unabhängige kritische Anwendung (Manus AI, August 2026) geschärft, dokumentiert in [EXAMPLES.md](EXAMPLES.md).

**Aktueller Status**  
Root-Ascent ist am besten als starkes *Analyseprotokoll* und Denkdisziplin zu verstehen. Es ist noch keine vollständig formalisierte oder empirisch validierte wissenschaftliche Methode. Es verbessert die Fragenfolge, reduziert Drift und erzwingt den Übergang von Diagnose zu Handlung. Es garantiert für sich genommen keine richtigen Root Causes.

**Bekannte Lücken**

1. **Sättigungskriterien sind noch subjektiv**  
   Die Regel „nur nach ausreichender Evidenz-Sättigung aufsteigen“ ist im Prinzip richtig, besitzt aber noch keine operationalisierten Schwellen (Quellenqualität, Menge, Gegenbelege, verbleibende Unsicherheit).

2. **Fehlendes explizites Falsifikations- / Gegenhypothesen-Modul**  
   Rivalisierende Erklärungen sollten aktiv erzeugt und gewichtet werden, bevor eine höhere Ursache als verdichtet gilt. Ohne diesen Schritt besteht das Risiko von Bestätigungsfehlern.

3. **Risiko der Schablonen-Diagnose**  
   Das Framing „Capability skaliert schneller als Governance“ ist mächtig und häufig zutreffend, kann aber zur wiederverwendbaren Schablone werden. Es sollte eine Kandidaten-Hypothese bleiben, kein Default-Schluss.

4. **Intent sollte fallbezogen sein**  
   Wenn jede Analyse standardmäßig auf „Verringerung der Capability–Governance-Lücke“ ausgerichtet wird, können andere legitime Intents verdrängt werden (Legitimität, Machtverteilung, die Frage ob eine Capability überhaupt existieren sollte, Verteilungsgerechtigkeit usw.). Der Intent sollte zu Beginn jedes Laufs explizit gemacht werden.

5. **Allgemeine Grenzen**  
   - Erfordert Disziplin; kann zu endloser Abstraktion missbraucht werden  
   - Qualität hängt stark von verfügbaren Daten ab  
   - Höhere Ursachen können selbst Symptome tieferer Bedingungen sein  
   - Derzeit am stärksten bei öffentlich beobachtbaren sozio-technischen Systemen  
   - Strukturelle Erklärungen können individuelle Verantwortung unterbetonen, wenn sie relevant ist

## 8. Geplante Härtung

Prioritäre Verbesserungen aus externem Stress-Testing:

- Operationalisierte Sättigungs-Checkliste pro Ebene (untersuchte Behauptung, stützende Quellen, Gegenbelege, Restunsicherheit, was die Analyse verändern würde)
- Expliziter Gegenhypothesen-Schritt vor dem Festschreiben einer höheren Ursache
- Fallbezogene Intent-Erklärung zu Beginn jedes Laufs
- Klarere Trennung von Fakten, Mustern, Hypothesen und verdichteten Diagnosen
- Weitere unabhängige Fallstudien über Domänen hinweg
- Bessere Unterstützung für Multi-Agenten- / Multi-Analysten-Nutzung

## 9. Zukünftige Entwicklung

- Breitere öffentliche Fallbasis
- Verfeinerte Evaluationskriterien für Ebenen-Sättigung
- Formalisierung der Wissensmatrix
- Community-generierte Beispiele und Stress-Tests
- Optionale parallele „Macht- & Verantwortungs“-Linse neben der Kausalleiter

## Referenzen & verwandte Dokumente

- [METHOD.de.md](METHOD.de.md) – Kompakte Referenzversion
- [PROMPT.md](PROMPT.md) / [PROMPT.de.md](PROMPT.de.md) – System-Prompt / Blueprint
- [EXAMPLES.md](EXAMPLES.md) – Reale Anwendungen und externe kritische Reviews
- [README.md](README.md) – Value Proposition und Überblick

---

*Dies ist ein lebendes Working Paper. Feedback, Fallstudien, kritische Anwendungen und Verbesserungen sind über Issues oder Pull Requests willkommen. Experimentelle Nutzer sind ausdrücklich eingeladen, die Methode unter realen Bedingungen zu testen und Ergebnisse zu berichten — einschließlich Fehlschlägen und Grenzen.*
