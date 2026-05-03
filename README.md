# Paper Plane Wing Optimization: Statistical Study
# Flügel-Optimierung bei Papierfliegern: Statistische Studie

## 🌎 Language / Sprache
- [English](#english)
- [Deutsch](#deutsch)

---

<a name="english"></a>
## 🇬🇧 English: Project Overview

### 📋 Description
This study evaluates the impact of wing length on flight duration. By comparing the "Base" model with an "Extended Wing" model, we determine if design changes significantly improve performance.

### 📊 Statistical Methodology
- **Normality Testing:** Shapiro-Wilk test indicated a non-normal distribution, leading to the selection of non-parametric methods.
- **Hypothesis Testing:** **Wilcoxon-Mann-Whitney Test** (as a robust alternative to the t-test).
- **Power Analysis:** Post-hoc analysis confirmed a Statistical Power ($1-\beta$) of **1.0**, exceeding the standard requirement of 0.90.

### 🔑 Key Findings
- **Statistical Significance:** Highly significant difference observed ($p < 0.001$).
- **Performance:** The extended wing model systematically outperforms the base model.
- **Recommendation:** Transitioning production to the extended wing design is statistically justified and highly recommended.

---

<a name="deutsch"></a>
## 🇩🇪 Deutsch: Projektübersicht

### 📋 Beschreibung
Diese Studie bewertet den Einfluss der Flügellänge auf die Flugdauer. Durch den Vergleich des Standardmodells ("Base") mit einem Modell mit verlängerten Flügeln ("Flügel") wird untersucht, ob Designänderungen die Leistung signifikant verbessern.

### 📊 Statistische Methodik
- **Normalverteilungstest:** Der Shapiro-Wilk-Test ergab eine Nicht-Normalverteilung, was zur Wahl nichtparametrischer Methoden führte.
- **Hypothesenprüfung:** **Wilcoxon-Mann-Whitney-Test** (als robuste Alternative zum t-Test).
- **Power-Analyse:** Die Post-hoc-Analyse bestätigte eine Teststärke ($1-\beta$) von **1,0**, was die Standardanforderung von 0,90 übertrifft.

### 🔑 Wichtigste Ergebnisse
- **Statistische Signifikanz:** Hochsignifikanter Unterschied festgestellt ($p < 0,001$).
- **Leistung:** Das Modell mit verlängerten Flügeln übertrifft das Standardmodell systematisch.
- **Empfehlung:** Die Umstellung der Produktion auf das optimierte Flügeldesign ist statistisch begründet und wird empfohlen.

---

## 📁 Project Structure / Projektstruktur
- `data/`: Raw experimental data (`.xlsx`) / Rohdaten
- `scripts/`: R analysis scripts / R-Skripte
- `reports/`: RMarkdown source and final PDF report / RMarkdown-Quellcode und PDF-Bericht

---
*Developed by: Siamak Goudarzi - 2026*
