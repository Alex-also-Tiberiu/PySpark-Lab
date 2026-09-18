# PySpark Lab

Esempi base di PySpark: RDD, DataFrame e Spark SQL.

## Requisiti

- Python 3
- [Dipendenze del progetto](requirements.txt)
- JupyterLab

Installa le dipendenze con:

```bash
pip install -r requirements.txt
```

## Notebook

| File | Contenuto |
|---|---|
| [01-PySpark-Get-Started.ipynb](01-PySpark-Get-Started.ipynb) | Avvio del primo programma PySpark. |
| [02-Create-SparkContext.ipynb](02-Create-SparkContext.ipynb) | Creazione e uso di `SparkContext`. |
| [03-Create-SparkSession.ipynb](03-Create-SparkSession.ipynb) | Creazione e uso di `SparkSession`. |
| [04-RDD-Operations.ipynb](04-RDD-Operations.ipynb) | RDD, trasformazioni, azioni e file di testo. |
| [05-DataFrame-Intro.ipynb](05-DataFrame-Intro.ipynb) | Introduzione ai DataFrame e confronto con gli RDD. |
| [06-DataFrame-from-various.ipynb](06-DataFrame-from-various.ipynb) | Lettura e scrittura di CSV, JSON e Parquet. |
| [07-DataFrame-Operations.ipynb](07-DataFrame-Operations.ipynb) | Selezione, filtri, raggruppamenti e aggregazioni. |
| [08-Spark-SQL.ipynb](08-Spark-SQL.ipynb) | Query SQL, viste temporanee, sottoquery e window functions. |

## Dati di esempio

| File | Uso |
|---|---|
| [data.txt](data/data.txt) | File di testo per gli esempi sugli RDD. |
| [stocks.txt](data/stocks.txt) | Dati testuali sui titoli azionari. |
| [persons.csv](data/persons.csv) | Dati di persone in formato CSV. |
| [products.csv](data/products.csv) | Prodotti in formato CSV. |
| [products_singleline.json](data/products_singleline.json) | Prodotti in JSON su una riga per record. |
| [products_multiline.json](data/products_multiline.json) | Prodotti in JSON su più righe. |
| [products.parquet](data/products.parquet) | Prodotti in formato Parquet, creato da Spark. |

## Avvio

```bash
jupyter lab
```

Apri i notebook in ordine, da `01` a `08`.
