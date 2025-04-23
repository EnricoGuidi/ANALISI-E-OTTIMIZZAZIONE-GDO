# 🛒 Ottimizzazione Layout Scaffale - EnryMarket

Progetto di data science sviluppato per **EnryMarket** con l’obiettivo di ottimizzare la disposizione dei prodotti a scaffale combinando:
- 🔍 Analisi del Sentiment sulle recensioni clienti
- 📦 Studio delle Co-Occorrenze d’Acquisto
- 🧠 Raccomandazioni strategiche di merchandising

## 📁 Struttura del Progetto

- `VADER_Sentiment_Analysis.ipynb`  
  Notebook Python che:
  - Traduce recensioni italiane in inglese
  - Applica VADER per calcolare il sentiment
  - Aggrega i punteggi e genera grafici esplicativi

- `dataset_EnryMarket_Sentyment_Analysis_VADER.xlsx`  
  Dataset con:
  - 704 recensioni di 10 prodotti alimentari (P001–P010)
  - Sentiment score per ogni recensione
  - Sintesi media per ciascun prodotto

- `OTTIMIZZAZIONE DELLA DISPOSIZIONE PRODOTTI A SCAFFALE.pdf`  
  Report finale contenente:
  - Risultati dell’analisi
  - Identificazione dei **top 3 prodotti** per gradimento
  - Cluster tematici consigliati:
    - 🥣 Colazione Sana
    - ☕ Pausa Caffè
    - 🥚 Ingredienti Naturali
  - Raccomandazioni per il layout e il marketing a scaffale

## 🎯 Obiettivi

- Migliorare la visibilità e le vendite dei prodotti a scaffale
- Favorire acquisti combinati tramite cluster logici
- Utilizzare dati reali (recensioni + transazioni simulate) per decisioni data-driven

## 🛠️ Tecnologie Utilizzate

- Python 3.11+
- [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment)
- Pandas, Matplotlib
- Excel (dataset)
- PDF (report strategico)

## 📊 Esempio di Risultato

| Codice Prodotto | Nome Prodotto      | Sentiment Medio |
|-----------------|--------------------|------------------|
| P006            | Biscotti Avena     | 0.89 🥇          |
| P001            | Latte Intero       | 0.83 🥈          |
| P010            | Zucchero di Canna  | 0.76 🥉          |

## 👨‍💼 Autore

**Ing. Enrico Guidi**  
📧 enrico.guidi.ing@gmail.com  
📱 +39 345 318 5732

---

© 2025 Enrico Guidi. Tutti i diritti riservati.  
Il contenuto del presente progetto non può essere riprodotto o utilizzato senza autorizzazione scritta.
