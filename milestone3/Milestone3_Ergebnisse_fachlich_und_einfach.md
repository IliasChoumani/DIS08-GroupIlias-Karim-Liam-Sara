# Meilenstein 3 – Überblick über berechnete Metriken und Ergebnisse

## 1. Gruppendefinition
- **Gruppe A (Podium = 1):**
  Länder, die bei einer Weltmeisterschaft den 1., 2. oder 3. Platz erreicht haben.
- **Gruppe B (Podium = 0):**
  Alle anderen Länder im jeweiligen WM-Jahr.

Beobachtungseinheit: **(Land, Jahr)**  
Zeitraum: **1966–2014**

### Interpretation (fachlich)
Die Analyse vergleicht Länder mit WM-Podiumsplatzierungen mit allen anderen Ländern im jeweiligen WM-Jahr. Dadurch wird der WM-Erfolg binär operationalisiert und jahresspezifisch vergleichbar gemacht.

### Interpretation (sehr einfach erklärt)
(Wir teilen pro WM alle Länder in zwei Gruppen: Gewinner und alle anderen.)

---

## 2. Bevölkerungsvariable
### Metrik
- **log10(Population im WM-Jahr)**

### Bedeutung
Die logarithmierte Bevölkerungsgröße eines Landes im jeweiligen WM-Jahr dient als Vergleichsgröße zwischen sehr kleinen und sehr großen Ländern.

### Interpretation (fachlich)
Die Log-Transformation reduziert die starke Schiefe der Bevölkerungsverteilung und verhindert, dass sehr große Länder die Analyse dominieren.

### Interpretation (sehr einfach erklärt)
(Sehr große Länder und sehr kleine Länder werden „zusammengeschoben“, damit man sie fair vergleichen kann.)

---

## 3. Gruppengrößen
### Ergebnis
- Podium-Beobachtungen: **39**
- Nicht-Podium-Beobachtungen: **3003**

### Interpretation (fachlich)
Die geringe Anzahl an Podiumsländern ist strukturell durch das Turnierformat bedingt, während die Vergleichsgruppe nahezu alle Länder der Welt umfasst.

### Interpretation (sehr einfach erklärt)
(Es gibt nur wenige Gewinner, aber sehr viele Länder, die nicht gewinnen – das ist normal.)

---

## 4. Mittelwerte der Bevölkerungsgröße
### Ergebnis
- **Podium:** mean(log10(population)) ≈ **7.68**
- **Nicht-Podium:** mean(log10(population)) ≈ **6.25**

### Interpretation (fachlich)
Länder mit Podiumsplatzierungen weisen im Durchschnitt eine deutlich höhere Bevölkerungsgröße auf als Länder ohne Podiumsplatzierung.

### Interpretation (sehr einfach erklärt)
(Gewinnerländer sind im Durchschnitt deutlich größer als Länder, die nicht auf dem Podium landen.)

---

## 5. Welch-t-Test
### Metrik
- **t-Wert**

### Ergebnis
- **t ≈ 22.9**

### Interpretation (fachlich)
Der sehr hohe t-Wert zeigt, dass der Unterschied der Mittelwerte im Verhältnis zur Streuung und Stichprobengröße außergewöhnlich groß ist.

### Interpretation (sehr einfach erklärt)
(Der Unterschied zwischen den Gruppen ist viel größer, als man ihn durch Zufall erwarten würde.)

---

## 6. p-Wert
### Metrik
- **p-Wert**

### Ergebnis
- **p ≈ 7.4 × 10⁻²⁸**

### Interpretation (fachlich)
Der extrem kleine p-Wert zeigt, dass der beobachtete Unterschied unter der Annahme gleicher Mittelwerte praktisch unmöglich wäre.

### Interpretation (sehr einfach erklärt)
(Es ist fast ausgeschlossen, dass dieser Unterschied nur durch Zufall entstanden ist.)

---

## 7. Effektgröße (Cohen’s d)
### Metrik
- **Cohen’s d**

### Ergebnis
- **d ≈ 1.22**

### Interpretation (fachlich)
Die Effektgröße weist auf einen sehr starken praktischen Unterschied zwischen den Gruppen hin.

### Interpretation (sehr einfach erklärt)
(Der Unterschied ist nicht nur da, sondern auch wirklich groß und wichtig.)

---

## 8. Gewichteter WM-Erfolg (Zusatzanalyse)
### Metrik
- **Pearson-Korrelation (r)**

### Ergebnis
- **r ≈ 0.13**

### Interpretation (fachlich)
Es besteht ein schwacher positiver Zusammenhang zwischen Bevölkerungsgröße und abgestuftem WM-Erfolg.

### Interpretation (sehr einfach erklärt)
(Größere Länder haben einen kleinen Vorteil, aber Größe allein erklärt den Erfolg nicht.)

---

## 9. Gesamtergebnis
### Interpretation (fachlich)
Die Analyse zeigt eine statistisch signifikante und praktisch relevante Assoziation zwischen Bevölkerungsgröße und WM-Erfolg. Eine kausale Interpretation ist nicht zulässig.

### Interpretation (sehr einfach erklärt)
(Große Länder haben statistisch gesehen bessere Chancen auf WM-Erfolg, aber viele andere Dinge spielen auch eine Rolle.)
