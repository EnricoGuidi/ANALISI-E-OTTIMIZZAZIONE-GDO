# Modello di Ottimizzazione per la Localizzazione di un Punto Vendita

## Descrizione del Progetto

Questo progetto implementa un modello di ottimizzazione per la localizzazione di un nuovo punto vendita, basato su un approccio multicriterio. L'obiettivo è supportare il processo decisionale attraverso l'elaborazione e la valutazione di indicatori chiave di performance (KPI), al fine di identificare la località ottimale in base a criteri predefiniti e ponderati.

Il modello è stato sviluppato in un ambiente Jupyter Notebook e utilizza un file Excel in input contenente i dati delle alternative localizzative e i relativi KPI. Il codice è strutturato per essere riutilizzato in contesti diversi, mantenendo la flessibilità del framework multicriterio.

---

## Struttura dei File

- `Modello di Ottimizzazione per la 0. Localizzazione di un Punto Vendita – EnryMarket.ipynb`: notebook principale che contiene il modello di analisi e il codice eseguibile.
- `input_kpi_localizzazione_liguria.xlsx`: file Excel contenente le alternative localizzative e i KPI su cui viene eseguita l’analisi.
- `README.md`: documento descrittivo del progetto.

Tutti i file sono localizzati nella stessa directory.

---

## Funzionalità del Modello

Il codice esegue le seguenti operazioni:

1. **Importazione dei dati**: lettura dei KPI dal file Excel.
2. **Pulizia e normalizzazione dei dati**: trasformazione dei valori su scala [0,1] per garantire l’omogeneità tra variabili.
3. **Definizione dei pesi**: attribuzione dei pesi ai KPI sulla base di criteri strategici.
4. **Calcolo del punteggio complessivo**: aggregazione dei punteggi normalizzati per ogni località.
5. **Analisi di sensitività**: verifica della stabilità della localizzazione ottimale al variare dei pesi.
6. **Visualizzazione dei risultati**: generazione di grafici comparativi e sintesi delle classifiche.

---

## Requisiti Tecnici

Per eseguire il notebook è necessario avere installate le seguenti librerie Python:

- `pandas`
- `numpy`
- `matplotlib`
- `openpyxl`

Può essere utile creare un ambiente virtuale con `venv` o `conda` e installare i pacchetti con:

```bash
pip install pandas numpy matplotlib openpyxl


## 🔧 Esecuzione

1. Assicurarsi di avere installato **Python 3.7** o versione superiore.
2. Clonare o scaricare il repository contenente il codice e i dati.
3. Posizionarsi nella directory principale del progetto.
4. Aprire il notebook in **JupyterLab**, **Jupyter Notebook** oppure direttamente in **Visual Studio Code** con estensione Jupyter attiva.
5. Eseguire tutte le celle in sequenza per completare l’analisi e generare i risultati.

---

## 👤 Autore

**Enrico Guidi**  
Contatto: _[inserire email professionale, se desiderato]_

---

## 📜 Licenza

Questo progetto è distribuito sotto **Licenza MIT**.  
Per maggiori dettagli, fare riferimento al file `LICENSE` (non incluso in questa versione).
