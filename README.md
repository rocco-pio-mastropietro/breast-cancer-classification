# Progetto unico per i corsi di "Piattaforme per i Big Data" & "Machine Learning"


## Obiettivi dell'analisi
Il set di dati proviene dal Breast Cancer Wisconsin (Diagnostic) Data Set, un benchmark
ampiamente utilizzato nell'apprendimento automatico per la diagnostica medica. Contiene
misurazioni dettagliate dei nuclei cellulari da campioni di tessuto mammario, consentendo la
classificazione dei tumori come benigni (non cancerosi) o maligni (cancerosi).

Anche se il dataset in questione non presenta dimensioni particolarmente impegnative in
termini di consumo delle risorse di calcolo, per assolvere agli obiettivi didattici dei corsi di
"Piattaforme per i big data" e "Machine learning" del corso di laurea magistrale in ingegneria
informatica della Università Telematica Internazionale UniNettuno, partirò non l'utilizzo di una
nota piattaforma per la gestione dei big data "Spark" - nella sua implementazione Pyton con
la API "PySpark" - creando un dataframe dal file "Breast_cancer_dataset.csv" (fonte:
https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset).

I primi passi dell'analisi consisteranno nell'estrapolare un sottoinsieme ridotto di dati e,
utilizzando la nota distribuzione API Pandas, nell'ottenere le classiche informazioni
descrittive di carattere strutturale del dataset (nomi delle colonne, tipi dei dati, presenza di
campi vuoti o duplicati, etc.).

Successivamente, tornerò a gestire il dataset originario effettuando operazioni di pulizia e
aggregazione dei dati finalizzate all'ottenimento di un nuovo dataframe costituito da un
sottoinsieme di interesse per gli obiettivi dell'analisi.

Riprendendo l'utilizzo della ricca libreria delle classi di Pandas, effettuerò inizialmente analisi
di tipo esplorativo; successivamente - servendomi di note tecniche di data visualization -
ricercherò possibili correlazioni fra le più significative delle variabili disponibili e la
classificazione dei tumori.

In ultima analisi, implementerò alcuni fra i più noti algoritmi di machine learning che, con un
addestramento basato su una selezione di dati che limiti il fenomeno dell'overfitting,
riclassifichi i tumori con un livello di attendibilità utile a possibili applicazioni future.


## Pensiero critico
I risultati delle metriche applicate ai classificatori scelti per il lavoro presentato hanno rivelato
accuratezza, precisione e un punteggio F1 maggiori per il RandomForest, nonché una migliore qualità
della curva ROC, seguita da un alto valore AUC (0,98), per lo stesso algoritmo.

L'esito delle operazioni condotte hanno confermato, pertanto, la bontà delle attività di analisi
esplorativa e selezione dei dati, effettuate preliminarmente al fine di estrapolare un dataset
idoneo per l'addestramento degli algoritmi di machine learning adottati.


(Rocco Pio Mastropietro, 31/08/2025)
