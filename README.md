# Analisi Produzione Uova 🐔🥚

Questo progetto si propone di analizzare la produzione di uova di un lotto di galline in un capannone, monitorando l’andamento della produttività dal momento dell’acquisto delle galline (agosto 2021) fino ad aprile 2023.  

Lo scopo principale è identificare quando inizia a manifestarsi un calo significativo nella produzione di uova legato all’invecchiamento delle galline, utilizzando metodi statistici.  

---

## Contenuti del repository

- **`dataset.csv`** – Dataset giornaliero contenente le seguenti variabili:  
  - `anno`, `mese`, `giorno`  
  - `capannone`  
  - `razza`  
  - `n_galline` (numero di galline presenti)  
  - `uova_prodotte` (numero di uova prodotte)  
  - `giorni_in_capannone`  
  - `n_morte` (numero di galline morte)  
  - `n_vendute` (numero di galline vendute)  

- **`analisi_produzione_uova.ipynb`** – Notebook con le analisi statistiche effettuate sul dataset, grafici e interpretazioni dei risultati.  

- **`capannone3_08-2021_04-2023.pdf`** – Report completo delle analisi eseguite, pronto per la consultazione.  

---

## Obiettivi dello studio

1. Monitorare la produzione di uova giorno per giorno per un singolo lotto di galline.  
2. Identificare il momento in cui l’invecchiamento delle galline provoca un calo significativo nella produzione.  
3. Valutare le variabili che influenzano maggiormente la produttività.  

---

## Possibili miglioramenti futuri

- Avere più campioni e combinare diverse razze di galline per aumentare la robustezza dello studio.  
- Integrare dati su alimentazione e condizioni climatiche (temperatura, umidità, luce) per analisi più approfondite.  
- Creare un modello predittivo basato su machine learning per stimare la produttività futura delle galline in base a età, razza e condizioni ambientali.  
- Ottimizzare la rotazione dei lotti conoscendo i **costi di mantenimento**, sostituendo le galline quando i costi superano i ricavi stimati dalla produzione.  

---

## Note

- La produzione di uova diminuisce con l’età delle galline, ma la tempistica e l’entità del calo possono variare tra razze e condizioni ambientali.  
- Questo studio rappresenta un primo passo verso un monitoraggio più accurato e l’ottimizzazione della gestione del capannone.  
