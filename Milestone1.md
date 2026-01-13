# DIS08 – Datenmodellierung (Wintersemester 2025/26)  
### **Meilenstein 1 – Thema, Datensatz & Projektplanung**

---

## 1. Projekttitel
**„Bevölkerung und Fußballerfolg – Analyse des Zusammenhangs zwischen nationaler Demografie und Leistungen bei FIFA-Weltmeisterschaften“**

---

## 2. Motivation

Die FIFA-Weltmeisterschaft ist eines der bedeutendsten globalen Sportereignisse.  
Neben sportlichen Faktoren spiegeln die Turniere auch gesellschaftliche und demografische Unterschiede wider.  
Dieses Projekt untersucht, **ob und in welchem Maße die Bevölkerungsgröße eines Landes mit seinem Erfolg bei Fußball-Weltmeisterschaften korreliert.**

Wir möchten herausfinden:
- Haben bevölkerungsreiche Länder systematisch bessere Chancen auf sportlichen Erfolg?  
- Gibt es Ausnahmen (z. B. kleine Nationen mit überdurchschnittlichen Erfolgen)?  
- Wie haben sich diese Muster über die Jahrzehnte verändert?

---

## 3. Datensätze

### **Datensatz 1 – FIFA World Cup Statistics**
- **Quelle:** [Kaggle – FIFA World Cup Dataset von A. Becklas](https://www.kaggle.com/datasets/abecklas/fifa-world-cup)  
- **Lizenz:** *CC0 – Public Domain*  
- **Format:** CSV  
- **Beschreibung:** Enthält Daten zu allen Fußball-Weltmeisterschaften von 1930 bis 2018, darunter Austragungsland, Gewinner, Spiele, Tore, Zuschauerzahlen u. a.  
- **Verwendung im Projekt:** Grundlage zur Bewertung der sportlichen Leistungen der einzelnen Länder (z. B. Siege, Tore, Platzierungen).

---

### **Datensatz 2 – World Population Dataset**
- **Quelle:** [Kaggle – World Population Dataset von S. Banerjee](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset)  
- **Lizenz:** Auf Kaggle ist ein Lizenzfeld vorhanden, jedoch ohne konkrete Angabe der Lizenzart.  
  [World Bank Open Data – Population (CC BY 4.0)](https://data.worldbank.org/indicator/SP.POP.TOTL).  
- **Format:** CSV  
- **Beschreibung:** Enthält demografische Informationen (Länder, Jahre, Regionen, Bevölkerungszahlen).  
- **Verwendung im Projekt:** Bereitstellung der Bevölkerungsdaten zur Verknüpfung mit den Fußballstatistiken.

---

## 4. Forschungsfragen

1. Besteht ein Zusammenhang zwischen der Bevölkerungsgröße eines Landes und seinem Erfolg bei Fußball-Weltmeisterschaften?  
2. Haben sich diese Zusammenhänge im Zeitverlauf verändert (1930 – 2014)?  
3. Gibt es Länder, deren sportlicher Erfolg im Vergleich zu ihrer Bevölkerungsgröße besonders auffällig ist?  

---

## 5. Projekt-Roadmap (nach Kurszeitplan)

| Phase | Zeitraum | Inhalt / Aktivitäten | Erwartetes Ergebnis |
|:------|:----------|:---------------------|:--------------------|
| **Kick-off & Open Source Basics** | 08. 10. – 23. 10. 25 | Einführung, GitHub-Einrichtung, Themenfindung | Gruppen-Repo, erste Themenidee |
| **Meilenstein 1** | **bis 07. 11. 25** | Auswahl der Datensätze, Forschungsfragen, Roadmap (diese Datei) | Markdown-Doku vollständig |
| **Version Control & Web Scraping** | 06. 11. – 13. 11. 25 | Erste Datenerhebung / ggf. Web-Scraping | Rohdaten gesammelt |
| **Data Cleaning & Strukturen** | 20. 11. – 04. 12. 25 | Datenbereinigung, einheitliche Struktur | Bereinigter Datensatz |
| **Meilenstein 2** | **bis 12. 12. 25** | Augmentiertes Dataset + Pipeline-Prototyp | Jupyter-Notebook + neuer Datensatz |
| **Hypothesentests & Analyse** | 18. 12. – 08. 01. 26 | Statistische Analysen, Visualisierungen | Analytische Ergebnisse |
| **Abschluss / Poster / Demo** | **bis 19. 01. 26** | Posterpräsentation, Code-Demo, Doku-Abgabe | Meilenstein 3 / Final Exam |

---

## 6. Geplante Methoden & Werkzeuge

- **Programmiersprache:** Python  
- **Umgebung:** Jupyter Notebook  
- **Tools:** Pandas, Matplotlib / Seaborn, Git / GitHub, Markdown  
- **Arbeitsschritte:**  
  - Datenimport & Prüfung  
  - Zusammenführung über Länder + Jahr  
  - Bereinigung und Normalisierung  
  - Korrelationsanalyse und Visualisierung  

---

## 7. Team

| Name | Rolle | GitHub |
|------|-------|--------|
| Liam Alimonta | Datenanalyse & Dokumentation | 
| Ziryan Karim | Datenaufbereitung & Integration | [@zkarim2025](https://github.com/zkarim2025) | 
| Sara Huseynova | Visualisierung & Design | [@thsara6](https://github.com/thsara6) |
| Ilias Choumani | Projektmanagement & Repository | [@IliasChoumani](https://github.com/IliasChoumani) | 

**Gruppen-Repository:** [DIS08-GroupIlias-Karim-Liam-Sara](https://github.com/IliasChoumani/DIS08-GroupIlias-Karim-Liam-Sara)

---

## 8. Quellen

- Breuer, T. (2025). *DIS08 – Data Modeling (WS 2025/26)*, TH Köln – Vorlesungsfolien.  
- Kaggle (2024). *FIFA World Cup Dataset* von A. Becklas (CC0 Public Domain).  
- Kaggle (2024). *World Population Dataset* von S. Banerjee (Lizenzfeld vorhanden, Typ nicht spezifiziert).  
- World Bank Open Data (2024). *Population (SP.POP.TOTL)* – (CC BY 4.0).  

---

> **Hinweis:**   
> Alle Arbeiten erfolgen gemäß den FAIR-Data-Prinzipien (R1.1: klare und zugängliche Lizenzangabe).

