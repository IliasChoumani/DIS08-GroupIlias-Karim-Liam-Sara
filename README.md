# DIS08-GroupIlias-Karim-Liam-Sara
Gruppen-Repository für DIS08 Datenmodellierung

# Data-Modeling-Projekt – WM-Erfolg & Bevölkerungsgröße  
**Wintersemester 2025/26**

Dieses Repository dokumentiert unser **Kursprojekt im Fach Data Modeling**.  
Ziel des Projekts ist es, zu analysieren, ob Länder mit größerer Bevölkerung tendenziell erfolgreicher bei FIFA-Weltmeisterschaften sind. Dabei verwenden wir transparente Datenaufbereitung und grundlegende statistische Methoden.

Das Repository ist entlang der **drei im Kurs definierten Meilensteine** strukturiert.

---

## Projektüberblick

Das Projekt folgt einer klaren analytischen Pipeline:

1. Definition der Forschungsfragen und der Hypothese  
2. Datenbeschaffung und Aufbau der Datenpipeline  
3. Statistische Analyse und Interpretation  

Alle Schritte sind in diesem Repository dokumentiert, um Transparenz und Nachvollziehbarkeit sicherzustellen.

---

## Meilenstein 1 – Forschungsdesign & Datenauswahl

In **Meilenstein 1** legen wir die konzeptionelle Grundlage des Projekts fest.

Zentrale Bestandteile:
- Motivation des Forschungsthemas
- Formulierung von drei leitenden **Forschungsfragen**
- Definition einer **statistisch testbaren Hypothese**
- Auswahl geeigneter Datensätze:
  - FIFA-Weltmeisterschaftsergebnisse
  - Bevölkerungsdaten der Weltbank
- Diskussion von Datenscope, Einschränkungen und Lizenzen

Dieser Meilenstein klärt, **was wir analysieren wollen und warum**.

---

## Meilenstein 2 – Datenbeschaffung & Datenpipeline

**Meilenstein 2** konzentriert sich auf den Aufbau einer strukturierten und transparenten Datenpipeline.

Zentrale Bestandteile:
- Einlesen der Rohdaten aus CSV-Dateien
- Harmonisierung von Länderkennungen
- Zuordnung der Bevölkerungsdaten zu den jeweiligen WM-Jahren
- Definition der Beobachtungseinheit als **(Land, Jahr)**
- Zusammenführung aller relevanten Informationen in einem Datensatz
- Erstellen der vollständigen Data-Pipeline

Das Ergebnis dieses Meilensteins ist ein **angereicherter Datensatz**, der kombiniert:
- WM-Erfolg
- Bevölkerungsgröße pro Land und Jahr

Dieser Datensatz bildet die Grundlage für alle weiteren Analysen.

---

## Meilenstein 3 – Analyse & Statistische Modellierung

In **Meilenstein 3** führen wir die statistische Analyse durch.

Zentrale Bestandteile:
- **Operationalisierung der Variablen**
  - Erfolg: binärer Indikator (Podium vs. kein Podium)
  - Bevölkerung: logarithmierte Bevölkerungsgröße (log10)
- Gruppenvergleich zwischen:
  - Ländern mit Podiumsplatzierungen
  - Ländern ohne Podiumsplatzierungen
- Anwendung eines **Welch-t-Tests**, um ungleiche Gruppengrößen und Varianzen zu berücksichtigen
- Berechnung einer **Effektgröße (Cohen’s d)** zur Bewertung der praktischen Relevanz
- Zusätzliche explorative Analyse mit abgestufter Erfolgsmetrik und Korrelation

---

## Ergebnisse – Zusammenfassung auf hoher Ebene

Die wichtigsten numerischen Ergebnisse der Analyse sind:

- **Anzahl der Beobachtungen**
  - Podiumsbeobachtungen: *n = 39*
  - Nicht-Podiumsbeobachtungen: *n = 3003*

- **Durchschnittliche Bevölkerungsgröße (log10-Skala)**
  - Podiumsländer: *≈ 7,68*
  - Nicht-Podiumsländer: *≈ 6,25*

- **Gruppenvergleich (Welch-t-Test)**
  - *t ≈ 22,9*
  - *p ≈ 7,4 × 10⁻²⁸*

- **Effektgröße**
  - *Cohen’s d ≈ 1,22* (großer Effekt)

- **Zusatzanalyse**
  - Korrelation zwischen Bevölkerungsgröße und abgestuftem Erfolg: *r ≈ 0,13* (schwacher positiver Zusammenhang)

Insgesamt deuten die Ergebnisse auf eine **starke statistische Assoziation** zwischen Bevölkerungsgröße und WM-Erfolg hin, zeigen aber gleichzeitig, dass Bevölkerungsgröße allein nur einen begrenzten Teil der Gesamtleistung erklärt.

---

## Interpretation & Einschränkungen

Wichtige Punkte zur Interpretation:
- Bevölkerungsgröße scheint ein relevanter Faktor zu sein, ist jedoch **keine ausreichende Erklärung** für WM-Erfolg.
- Weitere potenziell wichtige Einflussfaktoren (z. B. wirtschaftliche Ressourcen, Fußballkultur, Infrastruktur, Talententwicklung) werden nicht modelliert.

---

## Werkzeuge & Technologien

Das Projekt wurde umgesetzt mit:
- Python
- Jupyter Notebooks
- Git & GitHub für Versionskontrolle und Dokumentation

---

## Fazit

Dieses Repository bietet einen vollständigen Überblick über unser Data-Modeling-Projekt – von Forschungsdesign und Datenaufbereitung bis hin zur statistischen Analyse und Interpretation.  
Die meilensteinbasierte Struktur spiegelt den Kursaufbau wider und unterstützt eine klare Kommunikation von Methodik und Ergebnissen.
