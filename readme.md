# Titolo del progetto: Schedule della data

# Descrizione
Questo programma permette di visualizzare la data con la stringa '/'.

Progetto realizzato allo scopo didattico per applicare:
1. libreria datetime
2. dichiarare la viaribile exam_date
3. visualizzare la data con print

# 🛠 Requisiti
1. Python 3.x
2. Sistema operativo: Windows

# ▶️ Esecuzione del programma
python data.py

# 💻 Output
11 / 12 / 2014

# 🧠 Codice Python
```python

import datetime

data = datetime.date(2014,12,11)

print(data.day , "/", data.month, "/", data.year)

```
# 🏗 Struttura del progetto
python-schedula-data/

|

|---- data.py

|

|---- readme.md

# 🔄 Ciclo di vita del software
Analisi dei requisiti

Progettazione (diagramma: variabile exam_date → elaborazione → output)

Datetime in Python

Test e collaudo

Rilascio

Manutenzione futura (eventuali nuove funzionalità)

# 📊 WBS – Work Breakdown Structure
| **Livello** | **Attivita** | **Durata** | **Risorsa** | **Costo** |
|---|---|---|---|---|
| 1 | Analisi requisiti | 0,5 giorni | Studente | 0 |
| 1 | Progettazione | 0,5 giorni | Studente | 0 |
| 1 | Sviluppo | 0,5 giorni | Studente | 0 |
| 1 | Test | 0,5 giorni | Studente | 0 |
| 1 | Documentazione | 0,5 giorni | Studente | 0 |

# 📈 Earned Value
Planned Value (PV): 5

Earned Value (EV): 4

Schedule Variance (SV): -1 → leggero ritardo

Cost Variance (CV): 0 → costi rispettati

# 🔍 Qualita del Software
Il progetto tiene conto dei principi di qualità secondo:
ISO 9001 (gestione qualità)

ISO/IEC 25010 (qualità del prodotto software)

CMMI (maturità dei processi)

Caratteristiche considerate:
Affidabilità

Manutenibilità

Usabilità

Efficienza

Portabilità

# Autore

**Andrei Grunin**

Studente di Informatica

Progetto realizzato a scopo formativo.
