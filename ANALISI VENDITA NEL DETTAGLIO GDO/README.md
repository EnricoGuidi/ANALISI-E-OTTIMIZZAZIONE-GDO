
# ANALISI DATI DI VENDITA DEGLI ARTICOLI  
Analisi esplorativa dei driver di vendita con Python

## 📌 Descrizione del Progetto

Questo progetto ha l’obiettivo di analizzare i **dati di vendita al dettaglio** di articoli commercializzati in una rete di punti vendita.  
L’intero processo è implementato in un notebook Python (`Analisi_vendita_dettaglio_GDO.ipynb`) che elabora un dataset pulito (`train_dataset_vendita_dettaglio_GDO.csv`), con lo scopo di:

- Individuare i **principali fattori che influenzano le vendite**
- Fornire insight utili al **team marketing, operations e controllo di gestione**
- Preparare la base per eventuali **modelli predittivi o dashboard interattive**

Il progetto è stato sviluppato per un ambiente lavorativo di alto livello, con attenzione alla chiarezza, tracciabilità e scalabilità.

---

## 📁 Struttura dei File

```
📦 retail-sales-analysis/
├── new.ipynb                 # Notebook Python con logica di analisi dati
├── train_dataset_cleaned.csv # Dataset pulito contenente i dati di vendita
├── README.md                 # Documentazione del progetto
```

---

## 📊 Dataset di Input – `train_dataset_cleaned.csv`

Il dataset contiene informazioni dettagliate sui prodotti, i punti vendita e le rispettive vendite. È utilizzato per eseguire l’analisi descrittiva e generare visualizzazioni mirate.  
Di seguito alcune delle colonne chiave:

| Colonna                    | Descrizione                                         |
|---------------------------|-----------------------------------------------------|
| `Item_Identifier`         | Codice univoco del prodotto                         |
| `Item_Fat_Content`        | Categoria di contenuto di grassi (Low Fat, Regular)|
| `Item_Weight`             | Peso in kg del prodotto                             |
| `Item_MRP`                | Prezzo massimo al dettaglio                         |
| `Item_Visibility`         | Percentuale di visibilità nel punto vendita         |
| `Item_Outlet_Sales`       | Volume di vendite del prodotto                      |
| `Item_Type`               | Tipologia di prodotto (es. Soft Drinks, Dairy)      |
| `Outlet_Identifier`       | Codice del punto vendita                            |
| `Outlet_Establishment_Year`| Anno di apertura del punto vendita                |
| `Outlet_Size`             | Dimensione del negozio (Small, Medium, High)        |
| `Outlet_Location_Type`    | Livello geografico/urbanistico (Tier 1, 2, 3)       |
| `Outlet_Type`             | Tipo di negozio (es. Grocery Store, Supermarket)    |

---

## 🔎 Obiettivi dell’Analisi

- Esplorare la distribuzione delle vendite per **categoria prodotto** e **tipo punto vendita**
- Verificare le correlazioni tra variabili (es. `Item_MRP`, `Item_Visibility`)
- Analizzare la performance di vendita in base a **fattori geografici e dimensionali**
- Identificare eventuali **anomalie, outlier o pattern ricorrenti**
- Costruire basi per modelli predittivi o KPI aziendali

---

## 🚀 Come Eseguire il Progetto

### 1. Clona il Repository

```bash
git clone https://github.com/EnricoGuidi/ANALISI-E-OTTIMIZZAZIONE-GDO.git
cd Analisi_vendita_dettaglio_GDO
```

### 2. Installa le Dipendenze

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Avvia Jupyter Notebook

```bash
jupyter notebook Analisi_vendita_dettaglio_GDO.ipynb
```

---

## 📈 Output del Notebook

- **Grafici esplorativi**: distribuzioni, boxplot, istogrammi, heatmap
- **Sintesi statistiche**: medie, deviazioni standard, outlier
- **Pulizia del dataset**: gestione dei NaN e codifica delle variabili
- **Analisi di vendita**: per categoria, per prezzo, per visibilità e per store

---

## 🛠️ Requisiti Tecnici

- Python 3.9+
- Jupyter Notebook
- Librerie: `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 📎 Dipendenze

```text
pandas >= 1.5.0  
numpy >= 1.21  
matplotlib >= 3.5  
seaborn >= 0.12
```

---

## 👤 Autore

Sviluppato da **Enrico Guidi**  
_Consulente in Ingegneria e Controllo di Gestione_  
RSI S.r.l. – Divisione Data Science

---

## 📬 Contatti

📧 enrico.guidi.ing@gmail.com
🌐 

---

## ⚠️ Note Finali

Il progetto è pensato come base per moduli di data analytics.  
Può essere facilmente esteso per modelli di regressione, clustering o sistemi di raccomandazione.
