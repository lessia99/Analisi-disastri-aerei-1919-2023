# Analisi-disastri-aerei-1919-2023

Accurata analisi di tutti gli incidenti aerei che si sono verificati dal 1919 al 2023.

## Descrizione allegati

1.**aviation-accidents.csv**: file csv dove sono registrati quasi 25.000 incidenti con le seguenti informazioni:
- *date*: data dell'incidente
- *type*: tipo del velivolo
- *registration*: codice di registrazione del velivolo
- *operator*: operatore del velivolo
- *fatalities*: numero di morti
- *location*: luogo dell'incidente
- *country*: nazione dell'incidente
- *cat*: categoria dell'incidente come descritto dal ASN
- *year* : anno in cui 

2. **Flights_disasters_analysis.ipynb**: notebook contente l'analisi svolta con Python

## Dettagli analisi

### Analisi preliminari

**Valori mancanti**
Dopo aver caricato il dataset, ho controllato i valori mancanti e le variabili *registration*, *operator*, *fatalities* e *location* hanno dei valori mancanti. Essendo i dati dei record molto accurati, non trovo opportuno sostituirli con medie o altre statistiche.
Il metodo più appropriato, in questo caso,è quello di assegnare zero dove il valore è mancante, in modo da non perdere intere righe del set di dati.

**Trasformazione variabili**
Ho trasformato il numero di morti da un oggetto ad un float e *year* e *date* in formato datetime.
Inoltre alcuni valori erano 'unknow', in particolare nelle colonne di *date*, *year* e *country*, ho proseguito a eliminarle

### Analisi grafiche 

1. Dove si sono verificati più incidenti
2. In quale anno si sono verificati più incidenti
3. Quali sono gli operatori più sicuri
4. Quale tipo di veicolo ha causato più morti e quale meno
5. Dopo l'11 settembre 2001 come si sono evoluti gli incidenti
6. Analisi dell'USA
7. Analisi dell'Italia
8. Come si sono evoluti gli incidenti negli anni


## Requisiti e utilizzo

- Python installato
- librerie da installare tramite pip (pip install nome_libreria):
  - pandas
  - numpy,
  - matplotlib.pyplot

### Istruzioni 

1. **Download repository**: il notebook contiene il codice python, i grafici e i relativi commenti.
   
2. **Install Required Libraries**:
    - assicurarsi di avere Python 3.10 installato
    - installare le librerie necessarie
 
3.**Runnare il file Python**: eseguire il file Python usando direttamente un interprete Python come Google Colab.

## Contatti
Per domande, suggerimenti o feedback, contattatemi pure alla mail alessiaagostini53@gmail.com.
  
