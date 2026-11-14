# Schritt 5 – Vertiefte Vorstudie für Hauptidee A

> **Ziel:** Aus einer überzeugenden Idee eine **begründete, prüfbare Entscheidungsgrundlage** erarbeiten, um am 11.01.2027 souverän die Genehmigung zu beantragen und danach ins Grobkonzept überzugehen.

| Merkmal             | Festlegung                                                                                                                     |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Art**             | Interdisziplinäre Teamarbeit mit verteilten GitHub-Issues und gemeinsamem Review                                               |
| **Schlüsseltermin** | Bis am **14.12.2026** um **13:00 Uhr** – internes Review und Go / Überarbeiten / No-Go\*\*                                     |
| **Methode**         | Planungszyklus: Auftrag → Analyse → Würdigung → Lösungssuche → Bewertung → Auswahl; leichtgewichtiges Requirements Engineering |
| **Ergebnis**        | Gemeinsamer Vorstudienbericht für Idee A, nicht sechs isolierte Berichte                                                       |
| **GitHub**          | Issues je Arbeitspaket; Review und Beschluss in [`../Protokolle/`](../Protokolle/)                                             |

## 1. Grundlage und Vorlagen

- **Ideenursprung:** Ausgewählte Ideenskizze und Bewertung unter [`../Top3/`](../Top3/).
- **Vorstudiengliederung:** [`../Templates/Vorstudie_Vorlage.docx`](../Templates/Vorstudie_Vorlage.docx) – gemeinsames Berichtsskelett.
- **Agentenanweisungen:** [`../Top3/AGENTS.md`](../Top3/AGENTS.md) – soweit bereits vorhanden. Bei Unterstützung durch KI die Gliederung des Vorstudienberichts explizit mitgeben.
- **Originale Schulvorgaben:** Projektauftrag/Modulbeschreibung als übergeordnete Grundlage. Falls Aussagen unklar sind, Betreuer fragen.

**KI-Regel:** KI darf Texte strukturieren und offene Fragen aufzeigen. Unbekannte Zahlen, Anforderungen oder technische Machbarkeitsnachweise nicht als Tatsachen darstellen. Fachprüfung bleibt bei den Teammitgliedern.

## 2. Inhalt des gemeinsamen Vorstudienberichts

Die Gliederung folgt den typischen Ergebnissen der Vorstudie aus dem Lehrbuch ( Projektmanagement für Führungsfachleute S.24 ):

1. **Ausgangslage / Problemkatalog:** Heutige Situation, betroffene Nutzer, Handlungsbedarf.
2. **Projektabgrenzung und Schnittstellen:** Was gehört zum System, was nicht? Externe Geräte/Dienste/Personen.
3. **Zielsystem:** Muss-Ziele, Wunschziele, messbare Erfolgskriterien auf hoher Ebene.
4. **Lösungsvarianten:** Einschliesslich Nullvariante bzw. Beibehaltung des Ist-Zustands, wo sinnvoll; Alternativen innerhalb von A beschreiben.
5. **Machbarkeit / Risiken:** Software, Sensorik/Aktorik, Infrastruktur, Integration, Sicherheit, Beschaffung; offene Fragen.
6. **Wirtschaftlichkeit / Ressourcen:** Grobe Zusatzkosten, vorhandene Infrastruktur, Teamaufwand, erwarteter Nutzen.
7. **Bewertung und Empfehlung:** Nachvollziehbarer Variantenvergleich und begründete Vorzugsvariante.
8. **Vorgehensplanung / Projektauftrag:** Nächste Phasen, Verantwortlichkeiten, Rahmenbedingungen und offene Entscheidungen.

**Abgrenzung:** Noch kein endgültiges ER-Modell, kein vollständiges API-Design, keine umfassende Implementierung. Ein kleiner Proof of Concept ist nur nötig, wenn damit eine zentrale Unsicherheit gezielt geklärt wird.

## 3. Rollenverteilung für sechs Personen – Vorschlag

Alle sechs arbeiten weiterhin fachlich mit. Die Rollen beschreiben zusätzliche **Koordinations- und Prüfverantwortung**, keine getrennten Silos.

| Rollenpaar                        | Softwareentwicklung                                     | Systemtechnik                                                  |
| --------------------------------- | ------------------------------------------------------- | -------------------------------------------------------------- |
| **Koordination / Management (2)** | Projektkoordination und Softwareleitung                 | Koordination Systemtechnik / Infrastruktur                     |
| **Requirements Engineering (2)**  | Anforderungen an Anwendung / Nutzerabläufe              | Anforderungen an Geräte, Netzwerk und Betrieb                  |
| **Quality Assurance (2)**         | Prüfbarkeit der Anwendungsanforderungen / Dokumentation | Sicherheit, Machbarkeitsnachweise und technische Plausibilität |

Die genaue Zuweisung im Team beschliessen. Die QA-Personen sollten **nicht ausschliesslich ihre eigenen Beiträge freigeben**. Die Rollen ersetzen nicht die Mitverantwortung aller für Integration und Projektresultat.

## 4. Beispiel für GitHub-Issues

- `Ist-Zustand und Problemkatalog erheben` – RE-Paar, mit Reviews durch beide Koordinationen.
- `Ziele, Muss-Vorgaben und Systemgrenzen formulieren` – RE-Paar.
- `Software- und Infrastrukturmachbarkeit prüfen` – jeweilige fachliche Verantwortliche, gegenseitige Abstimmung.
- `Lösungsvarianten und Risiken analysieren` – Koordination + RE; QA prüft Nachweise.
- `Grobe Kosten und Ressourcen aufstellen` – Koordination mit beiden Fachrichtungen.
- `Vorstudienbericht redigieren und Qualität prüfen` – QA-Paar; Kapitelautoren überarbeiten.
- `Review vom 14.12. vorbereiten und protokollieren` – Projektkoordination.

Jedes Issue erhält: verantwortliche Person, konkretes Ergebnis, Link zum Abschnitt/Dokument und kurze Akzeptanzkriterien. Niemand wartet allein auf eine andere Disziplin: unsichere Schnittstellen werden früh gemeinsam abgestimmt.

## 5. Gemeinsames Review am 14.12.2026

Prüffragen: Ist das Problem relevant? Sind die Muss-Ziele plausibel? Ist der Aufwand realistisch? Reicht das Budget? Sind die Beiträge beider Fachrichtungen klar? Welche Risiken oder Annahmen sind noch offen? Ist eine Variante fachlich empfehlbar?

**Mögliche Beschlüsse:**

- **Go zur Pitch-Vorbereitung:** Entscheidungsgrundlage ausreichend; kleinere offene Aufgaben terminiert.
- **Überarbeiten:** Konkrete Korrekturaufträge mit Verantwortlichen und Fristen; anschliessend erneute Prüfung.
- **No-Go / Reserve prüfen:** Zentrale Vorgaben werden nicht erfüllt oder Risiken sind nicht vertretbar.

Das Review ist ein **interner Checkpoint**, keine formelle Genehmigung durch die Experten.

## Ergebnis / Definition of Done

- [ ] Gemeinsamer Vorstudienbericht liegt in einer abgestimmten Version vor.
- [ ] Ziele, Machbarkeit, Varianten, Kosten, Risiken und Empfehlung sind nachvollziehbar.
- [ ] Beide Fachrichtungen haben den Bericht geprüft.
- [ ] Beschluss vom 14.12. und verbleibende Aufgaben sind dokumentiert.
- [ ] Die Hauptidee ist für den Pitch freigegeben oder mit konkreten Auflagen versehen.

**Nächster Schritt:** [Elevator Pitch vorbereiten](elevator_pitch.md).
