# 🍽️ Analisi dell'Impatto Economico delle Cene e Pranzi Fuori in Australia

## 📌 Descrizione del Progetto
Questo progetto analizza l'impatto economico delle spese per pranzi e cene fuori casa in Australia, utilizzando un'analisi di serie storiche con metodi di previsione avanzati. L'obiettivo è identificare trend, stagionalità e ciclicità nei dati e confrontare diversi modelli di previsione per determinare il più accurato.

## 📂 Struttura del Progetto
- 📊 **`dataset/`**: Contiene la serie storica dei dati di spesa per pranzi e cene fuori in Australia.
- 🛠 **`scripts/`**: Script R per la pulizia dei dati, analisi esplorativa e modellazione.
- 📜 **`results/`**: Report e visualizzazioni dei risultati delle previsioni.
- 📖 **`README.md`**: Questo file, che fornisce informazioni dettagliate sul progetto.

## 📋 Requisiti
Per eseguire il progetto, installa i seguenti pacchetti R:
```r
install.packages(c("tidyverse", "forecast", "fpp2", "tsibble", "caret", "ggplot2"))
```


## 📊 Metodologia
1. **📈 Analisi Esplorativa della Serie Storica**: Identificazione di trend, stagionalità e valori anomali con grafici e statistiche descrittive.
2. **🔍 Modelli Benchmark**: Confronto tra metodi semplici di previsione:
   - Drift Method
   - Naive Method
   - Seasonal Naive Method
   - Average Method
3. **⚙️ Modelli di Previsione Avanzati**:
   - **Modelli Lineari**: Regressione autoregressiva e multipla
   - **Modelli di Machine Learning**: Reti neurali autoregressive
4. **📊 Valutazione dell'Accuratezza**: Confronto tra modelli usando metriche di errore (RMSE, MAE, MAPE).
5. **🔬 Interpretazione dei Risultati**: Analisi dei residui per verificare la qualità delle previsioni.

## 📜 Risultati Principali
📌 L'analisi ha evidenziato che:
- **Il modello di regressione lineare con trend e stagionalità ha fornito buone previsioni**.
- **Le reti neurali autoregressive hanno migliorato la capacità predittiva rispetto ai modelli benchmark**.
- **I mesi di dicembre e luglio mostrano un picco di spese dovuto alle festività e vacanze scolastiche**.

## 👩‍💻 Autore

## Author and contact 

| Name                | Description                                                                                       |
|---------------------|---------------------------------------------------------------------------------------------------|
| **Carmela Pia Senatore** | Developer - [carmens0](https://github.com/carmens0) <br> Email - [carmensenatore58@gmail.com](mailto:carmensenatore58@gmail.com) <br> LinkedIn - [Carmela Pia Senatore](https://linkedin.com/in/carmela-pia-senatore-ba1797207) |

