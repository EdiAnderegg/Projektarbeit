# AGENTS.md – Vertiefte Vorstudie für Hauptidee A

## Geltungsbereich und Auftrag

Diese Anweisungen gelten **ausschliesslich für die nach dem Voting und der fachlichen Top-3-Prüfung ausgewählte Hauptidee A**.

Der Agent unterstützt das sechs Personen starke, interdisziplinäre Team dabei, eine überprüfbare **Vorstudie als Entscheidungsgrundlage** zu verfassen.

Die Reserveideen B und C werden nicht automatisch ebenso tief ausgearbeitet.

**Verbindliche Gliederung:** [`../../Templates/Vertiefte_Vorstudie_Vorlage.md`](../../Templates/Vertiefte_Vorstudie_Vorlage.md)

**Word-Berichtsvorlage:** [`../../Templates/Vertiefte_Vorstudie_Vorlage.docx`](../../Templates/Vertiefte_Vorstudie_Vorlage.docx)

**Eingaben:** freigegebene Ideenskizze, Top-3-Bewertung, Schulvorgaben, Protokolle, belastbare technische Quellen, vom Team gelieferte Fakten.

**Ausgabe des Agenten:** Kapitelweise Markdown-Entwürfe, Tabellen und Prüffragen. Das Team übernimmt überprüfte Inhalte nach Word.

## Ziel / Meilensteine

- **14.12.2026:** Internes Review (Go / Überarbeiten / No-Go). Das ist **keine externe Genehmigung**.
- **11.01.2027:** Fünfminütiger Experten-Pitch; formeller Entscheid zur vorgestellten Projektidee.
- Ergebnis der Vorstudie: nachvollziehbare Empfehlung für ein Vorhaben, dessen Grenzen, Nutzen, Risiken, Aufwand und Realisierbarkeit plausibel sind, als Grundlage für das Grobkonzept.

## Methodische Grundlage – sechsstufiger Planungszyklus

1. **Auftrag / Vertrag:** Ziele, Vorgaben, Zuständigkeiten, verfügbare Mittel klären.
2. **Erhebung / Analyse:** Ausgangslage, Stakeholder, Probleme, vorhandene Infrastruktur, Fakten erheben.
3. **Würdigung / Zielrevision:** Stärken/Schwächen, Chancen/Risiken beurteilen; Ziele bei Bedarf nachführen.
4. **Lösungssuche:** prinzipielle Alternativen innerhalb von Idee A entwickeln (wenn sinnvoll inklusive Nullvariante).
5. **Bewertung:** Muss-Kriterien prüfen; praktikable Varianten anhand vorab definierter Kriterien vergleichen.
6. **Auswahl:** begründete Empfehlung **für die interne Teamfreigabe und den externen Entscheid** vorbereiten.

Der Zyklus ist iterativ: Erkenntnisse können erneute Erhebung oder eine Zielrevision auslösen.

**Vorstudie nicht mit dem Grob- oder Detailkonzept verwechseln**: Es geht noch nicht um eine endgültige Architektur oder ausführungsreife Pläne.

## Verbindliche Kapitel des Berichts

1. Management Summary und Entscheidungsbedarf
2. Ausgangslage, Stakeholder und Problemkatalog
3. Zielsystem, Muss-/Wunschziele und Restriktionen
4. Projektabgrenzung und Schnittstellen
5. Lösungsvarianten (ggf. inklusive Nullvariante)
6. Machbarkeitsprüfung (Software, Systemtechnik, Integration, Sicherheit)
7. Wirtschaftlichkeit, Ressourcen und Aufwand
8. Chancen, Risiken und offene Prüfaufträge
9. Variantenbewertung und begründete Empfehlung
10. Vorgehensplanung für die nächsten Phasen
11. Internes Review und Expertenentscheid
12. Quellen, Nachweise und Anhänge

Die Kapitel sind im Template präzisiert.

Für die erste Fassung dürfen Tabellen offen sein – aber ihre fehlenden Daten müssen ausdrücklich gekennzeichnet werden.

## Rollen und Arbeitsteilung (Vorschlag, Teamentscheid erforderlich)

| Rollenpaar                | Software                                           | Systemtechnik                                          |
| ------------------------- | -------------------------------------------------- | ------------------------------------------------------ |
| Management / Koordination | Projektkoordination und Softwareleitung            | Systemtechnikleitung                                   |
| Requirements Engineering  | Nutzerbedürfnisse, Softwarefunktionen, Prüfbarkeit | Sensorik, Infrastruktur, Kommunikation, Betriebsbedarf |
| Quality Assurance         | Dokumenten- und Softwarequalität                   | Sicherheits-, Integrations- und Infrastrukturqualität  |

Jedes Teammitglied liefert einen nachvollziehbaren Beitrag.

**Nicht die verantwortliche Person erfinden**.

Der Agent darf passende GitHub-Issues mit Ziel, Ergebnis, Akzeptanzkriterien, Abhängigkeiten und Prüfer-Rolle vorschlagen.

Kritische Kapitel sollen fachübergreifend geprüft werden; niemand sollte seine eigene Arbeit allein freigeben.

## Anforderungen an die Qualität der Analyse

- **Fakten:** mit Quelle, Datum oder internem Nachweis belegen.
- **Annahmen:** als `[ANNAHME: ...]` mit Prüfweg markieren.
- **Offene Punkte:** als `[OFFEN: ...]` mit möglichem Issue oder Verantwortungsrolle kennzeichnen.
- **Ziele:** klar, lösungsneutral und auf hoher Ebene prüfbar formulieren.
- **Varianten:** nachvollziehbar voneinander unterscheiden; kein Scheinvergleich einer Lieblingslösung mit unrealistischen Alternativen.
- **Kosten und Zeit:** Spannbreiten/Schätzgrundlage nennen; keine erfundenen Preise, Stunden oder Zusicherungen.
- **Risiken:** mindestens Ursache, Auswirkung und geplante Prüfmassnahme/Gegenmassnahme erfassen.
- **Schnittstellen:** zwischen Sensoren/Aktoren, Netz, Diensten, Software, Anwendern und externen Quellen beschreiben, ohne Protokolle willkürlich festzulegen.
- **Machbarkeit:** Unklarheiten benennen; bei kritischen Annahmen einen kleinen Proof of Concept als _Option_ empfehlen.
- **Entscheidung:** interne Empfehlung ist nicht gleich externe Projektfreigabe.

## Vorlagen- und Ausgabeprozess

1. Alle übergebenen Quellen und Entscheidungen zuerst lesen; Widersprüche hervorheben.
2. Für jedes Arbeitspaket ein Kapitel bzw. eine begrenzte Aufgabe bearbeiten, statt einen kompletten Bericht ohne Nachweise zu behaupten.
3. Inhalt gemäss `Vertiefte_Vorstudie_Vorlage.md` ausgeben; Tabellen und Quellenstellen erhalten.
4. Prüffragen und nötige Nachweise am Ende des Arbeitspakets kenntlich machen.
5. Nach fachlichem Review die freigegebenen Abschnitte in die Word-Vorlage übernehmen.
6. Vor dem Review am 14.12.2026 eine konsolidierte Fassung und offene Risiken erstellen.

## Was der Agent nicht tun darf

- Keine erfundenen Interviewergebnisse, Expertengenehmigungen, Beschaffungspreise oder Quellen.
- Keine technische Architektur, Frameworkwahl, MQTT-/API-Verträge, Datenbankmodellierung oder Testimplementierung ohne entsprechenden Auftrag und ausreichende Fakten als «beschlossen» darstellen.
- Kein Überspringen von Muss-Kriterien, Sicherheit, Budget oder interdisziplinären Anforderungen.
- Die sechs ursprünglichen Ideen nicht mit technischen **Lösungsvarianten innerhalb von A** gleichsetzen.
- Kein automatisches Go / No-Go aus einer Punktzahl ableiten; Entscheidung vom Team bzw. den Experten herbeiführen lassen.
- Keine Änderung anderer Projektdokumente ohne ausdrücklichen Auftrag.

## Sprache und Stil

Schweizer Hochdeutsch, sachlich, konsistent, präzise.

Fachbegriffe kurz erklären. Unbekannte Zahlen nicht als Fakten formulieren.

Die Formulierungen sollen für technische und nichttechnische Entscheider verständlich sein.

## Prüfliste vor Abgabe eines Kapitels

- [ ] Aussagegrundlagen, Annahmen und offene Punkte sind sichtbar getrennt.
- [ ] Systemtechnik und Software sowie deren Integration berücksichtigt.
- [ ] Relevante Schulvorgaben eingehalten oder als ungeprüft markiert.
- [ ] Abschnitte passen zum Detaillierungsgrad der Vorstudie.
- [ ] Entscheidungsrelevanz, Risiken und nächste Prüfaufgaben sind erkennbar.

## Beispielauftrag

> Lies `Vorstudie/Top3/A/AGENTS.md` und `Vorstudie/Templates/Vertiefte_Vorstudie_Vorlage.md`. Entwirf Kapitel 3 (Zielsystem) aus den folgenden geprüften Notizen. Kennzeichne Annahmen und offene Informationen. Erstelle zusätzlich drei passende GitHub-Issue-Vorschläge für noch fehlende Nachweise: ...
