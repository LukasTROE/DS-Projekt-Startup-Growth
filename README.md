# 🛒 Online Retail Sales Analysis

## 📊 Projektübersicht

Dieses Projekt analysiert Verkaufsdaten eines Online-Shops, um datenbasierte Erkenntnisse über Kaufverhalten, Umsatztrends und Kundensegmente zu gewinnen. Im Rahmen einer Gruppenarbeit werden Python-Bibliotheken wie Pandas, NumPy, Matplotlib und Seaborn eingesetzt, um explorative Datenanalysen durchzuführen und aussagekräftige Visualisierungen zu erstellen.

## 🎯 Projektziel

Identifikation von Umsatzpotenzialen und Entwicklung von Handlungsempfehlungen für:
- Optimierung der Produktstrategie
- Gezielte Kundenansprache nach Segmenten
- Effizienteren Einsatz von Marketing-Ressourcen
- Verbesserung der Kundenbindung

## 📁 Projektstruktur

```
DS-Projekt-Online-Retail/
│
├── project.ipynb          # Hauptanalyse-Notebook
├── README.md              # Projektdokumentation
└── data/                  # Datensatz (optional lokal)
```

## 📈 Datensatz

**Quelle:** [Kaggle - Online Shop Customer Sales Data](https://www.kaggle.com/datasets/onlineretailshop/online-shop-customer-sales-data)

**Beschreibung:**  
Transaktionsdaten eines internationalen Online-Einzelhändlers mit folgenden Variablen:

| Variable | Typ | Beschreibung |
|----------|-----|--------------|
| Transaction ID | Numerisch | Eindeutige Transaktionsnummer |
| Date | Datum | Zeitpunkt der Transaktion |
| Customer ID | Numerisch | Kundenidentifikation |
| Gender | Kategorial | Geschlecht (Male/Female) |
| Age | Numerisch | Alter des Kunden |
| Product Category | Kategorial | Produktkategorie |
| Quantity | Numerisch | Anzahl der Produkte |
| Price per Unit | Numerisch | Einzelpreis |
| Total Amount | Numerisch | Gesamtumsatz |

## 🔍 Analyseschwerpunkte

### 1. Datenimport & Vorbereitung
- Laden und Inspektion der Daten
- Data Cleaning (fehlende Werte, Duplikate, Ausreißer)
- Datentyp-Konvertierung

### 2. Explorative Datenanalyse (EDA)
- Deskriptive Statistiken
- Umsatzanalyse nach Produktkategorien
- Zeitreihenanalyse (Trends, Saisonalität)
- Kundenanalyse (Demografie, Kaufverhalten)

### 3. Visualisierungen
- Zeitliche Umsatzentwicklung
- Top-Produktkategorien
- Kundensegmente nach Alter und Geschlecht
- Umsatzverteilungen

### 4. Erkenntnisse & Handlungsempfehlungen
- Wichtigste Findings
- Business-relevante Empfehlungen
- Limitationen der Analyse

## 🛠️ Verwendete Technologien

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** - Datenmanipulation und -analyse
- **NumPy** - Numerische Berechnungen
- **Matplotlib** - Datenvisualisierung
- **Seaborn** - Statistische Visualisierungen

## 🚀 Installation & Ausführung

### Voraussetzungen
```bash
Python 3.8 oder höher
pip (Python Package Manager)
```

### Setup
1. Repository klonen oder herunterladen
```bash
git clone <repository-url>
cd DS-Projekt-Online-Retail
```

2. Benötigte Packages installieren
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Jupyter Notebook starten
```bash
jupyter notebook project.ipynb
```

## 📊 Analysestruktur im Notebook

1. **Einführung & Datensatz**
   - Problemstellung
   - Datensatzbeschreibung
   - Fragestellungen

2. **Datenimport & Vorbereitung**
   - Daten laden
   - Erste Inspektion
   - Data Cleaning

3. **Explorative Datenanalyse**
   - Umsatzanalyse
   - Zeitreihenanalyse
   - Produktanalyse
   - Kundenanalyse

4. **Visualisierungen**
   - Trends und Muster
   - Vergleiche und Rankings

5. **Erkenntnisse & Fazit**
   - Key Findings
   - Handlungsempfehlungen

## 👥 Team

Projektarbeit im Rahmen des Kurses "Introduction to Data Science"

---

**Hinweis:** Der Datensatz stammt von Kaggle und sollte gemäß der Kaggle-Nutzungsbedingungen verwendet werden.