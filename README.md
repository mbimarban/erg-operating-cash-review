# ERG Operating Cash Review

Interaktywna analiza przepływów pieniężnych ERG S.A. za lata 2023–2025.

Projekt pokazuje, w jaki sposób spółka produkcyjna zamienia sprzedaż, zapasy i finansowanie od dostawców na realną gotówkę operacyjną.

Projekt online:  
https://mbimarban.github.io/erg-operating-cash-review/

## Cel projektu

To nie jest klasyczny dashboard finansowy.

Celem projektu jest pokazanie w prostym języku biznesowym:

- gdzie utknęła gotówka,
- dlaczego wróciła,
- czym różni się EBITDA od realnej gotówki,
- czy poprawa CFO jest trwała.

Analiza została przygotowana dla:
- właścicieli firm,
- managerów,
- osób biznesowych bez finansowego backgroundu.

## Główny wniosek

W 2025 roku ERG poprawił przepływy operacyjne,
ale poprawa wynikała głównie z uwolnienia kapitału obrotowego:
- spadku zapasów,
- dłuższego finansowania od dostawców,
- poprawy cyklu gotówki,

a nie z trwałej poprawy rentowności.

## Projekt zawiera

- interaktywny raport HTML,
- narrację CFO-first,
- analizę EBITDA vs CFO,
- analizę kapitału obrotowego,
- Cash Flow Sales,
- CCC / DSO / DIO / DPO,
- prosty simulator „what-if”,
- analizę marż i ryzyk operacyjnych.

## Struktura repozytorium

```text
/
├── index.html
├── data/
│   ├── erg_sa_data.json
│   ├── erg_sa_storytelling.json
│   └── erg_sa_visualization_config.json
└── financial-model/
    └── ERG_SA_CFO_Analysis_2023_2025.xlsx
