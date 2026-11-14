# Phase 1 – Vorstudie

## Ziel

Sammlung, Bewertung und Auswahl einer geeigneten
Projektidee für das interdisziplinäre Teamprojekt.
Eine Vorstudie ist nicht einfach nur eine Ideesammlung. Sie ist ein strukturiertes Entscheidungsprozess, der begründet, ob und wie ein Projekt weiterverfolgt werden soll.

Ziel ist es, eine Idee/Vision in den Vorstudienprozess einzubringen und mithilfe klarer Ziele, Projektabgrenzungen, Risiken, Lösungsvarianten zu erkennen, ob sie realisierbar ist und somit reif für ein Projekt ist.

## Gesammtmodell

```mermaid
flowchart TB
    IDEEN["6+ Projektideen<br/>Individuell formuliert<br/>Einheitliches Template, 1–2 Seiten"]

    VOTING["Gemeinsame Vorstellung und Voting<br/>Alle sechs Mitglieder entscheiden mit"]

    A["A – Favorit"]
    B["B – Reserve 1"]
    C["C – Reserve 2"]

    CHECK["Kurze Machbarkeitsprüfung<br/>aller drei Ideen"]

    STUDIE["Vertiefte Vorstudie für Projekt A<br/>Anforderungen auf hoher Ebene<br/>Ziele · Varianten · Risiken<br/>Wirtschaftlichkeit · Empfehlung"]

    EXPERTEN["11.01.2027 – Expertenentscheid<br/>5-Minuten-Pitch<br/>Genehmigung oder Überarbeitung"]

    IDEEN --> VOTING

    VOTING --> A
    VOTING --> B
    VOTING --> C

    A --> CHECK
    B --> CHECK
    C --> CHECK

    CHECK --> STUDIE
    STUDIE --> EXPERTEN

    classDef standard fill:#1c1c1c,stroke:#777,color:#fff
    classDef selected fill:#003d30,stroke:#00c878,color:#fff
    classDef reserve fill:#252525,stroke:#777,color:#fff

    class IDEEN,VOTING,CHECK,EXPERTEN standard
    class A,STUDIE selected
    class B,C reserve
```

## Vorgehensweise

1. Mindestens sechs Projektideen dokumentieren.
   _[Zu => Schritt eins](Projektmanagment/projekt_ideen.md)_
2. Alle Ideen gemeinsam vorstellen.
   _[Zu => Schritt zwei](Projektmanagment/idee_vorstellen.md)_
3. Voting durchführen.
   _[Zu => Schritt drei](Projektmanagment/voting_idee.md)_
4. Die drei besten Ideen auswählen.
   _[Zu => Schritt vier](Projektmanagment/top_idee.md)_
5. Hauptidee A umfassende Vostudie.
   _[Zu => Schritt fünf](Projektmanagment/vosrtudie_idee.md)_
6. Elevator Pitch für den Expertenentscheid vorbereiten.
   _[Zu => Schritt sechs](Projektmanagment/elevator_pitch.md)_

## Projektorganisation

- [Templates](Templates/)
- [Ideensammlung](Ideen/)
- [Projektmanagement](Projektmanagement/)
- [Sitzungsprotokolle](Protokolle/)
- [Top 3 Projektideen](Top3/)

## Meilenstein

M1 – Vorstellung der Projektidee: 11.01.2027
