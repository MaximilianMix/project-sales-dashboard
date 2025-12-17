# project-sales-dashboard
 Sales Dashboard – Superstore Dataset

## 🧩 Problemstellung
Das Management eines Handelsunternehmens benötigt einen übersichtlichen Überblick über Umsatz, Bestellungen und Profitabilität.
Ziel ist ein interaktives Dashboard, das monatliche Entwicklungen, Top-Produkte und regionale Unterschiede sichtbar macht.

## 🎯 Ziel des Projekts
Entwicklung eines Power BI Dashboards zur Unterstützung von datengetriebenen Entscheidungen im Vertrieb.

## 📌 Analyse-Scope & Business-Fragestellungen
Das Dashboard beantwortet unter anderem folgende Fragestellungen:

- Wie hoch sind Umsatz, Gewinn und Anzahl der Bestellungen insgesamt?
- Wie entwickeln sich Umsatz und Profit im Zeitverlauf?
- Welche Produktkategorien und Produkte tragen am stärksten zum Umsatz bei?
- Welche Kundensegmente sind am profitabelsten?
- Wie unterscheiden sich die Regionen in ihrer Performance?
- Gibt es saisonale Trends oder Auffälligkeiten?


## 📊 Datengrundlage
Verwendet wird das öffentlich verfügbare "Superstore Sales" Dataset (Kaggle).
Die Daten enthalten Informationen zu Bestellungen, Kunden, Produkten, Regionen und Umsätzen.

## 🧹 Datenaufbereitung & Modellierung

- Import und Bereinigung der Rohdaten in Power Query
- Standardisierung von Spaltennamen und Datentypen
- Korrekte Umwandlung von Datumsfeldern unter Berücksichtigung des US-Datumsformats
- Validierung der Datenqualität (keine fehlerhaften Datumswerte in kritischen Spalten)

### Datenmodell
- Aufbau eines sauberen Sternschemas (Star Schema)
- Zentrale Faktentabelle auf Order-Position-Ebene
- Erstellung separater Dimensionstabellen für:
  - Kunden
  - Produkte
  - Regionen
- Entfernung von Duplikaten ausschließlich in Dimensionstabellen
- Einsatz von einfachen (einseitigen) Beziehungen von Dimensionen zur Faktentabelle
- Überprüfung der Filterlogik mittels Dimension-basierten Slicern

## 🛠 Projektstatus & Vorgehen
- ✔ Datenbereinigung und Transformation in Power Query  
- ✔ Aufbau eines sauberen Datenmodells (Sternschema)  
- ⏳ Definition zentraler KPIs (Umsatz, Bestellungen, Profit)  
- ⏳ Erstellung eines interaktiven Dashboards in Power BI  

## 🔧 Tools
- Power BI
- Power Query
- DAX
- Excel / CSV

## 📈 Erwarteter Business Mehrwert
Ein vergleichbares Dashboard kann das manuelle Monatsreporting ersetzen und Entscheidungen im Vertrieb und Management beschleunigen.

## 📌 Aktueller Stand
Das Datenmodell ist vollständig aufgebaut und validiert. 
Im nächsten Schritt werden zentrale KPIs definiert und erste Visualisierungen erstellt.