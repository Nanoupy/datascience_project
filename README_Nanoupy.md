Author: Nanoupy

Language: Italian

Tools: Python, Pandas, Seaborn, Matplotlib

Overview

Questo progetto analizza l’evoluzione globale dell’accesso all’elettricità (% della popolazione) utilizzando dati della World Bank / SE4ALL.
L’obiettivo è esplorare le differenze tra regioni, individuare trend temporali e visualizzare i progressi verso l’Obiettivo di Sviluppo Sostenibile n.7 (SDG7):
Garantire a tutti l’accesso a un’energia economica, affidabile, sostenibile e moderna.

Project Structure

1. Descrizione del dataset: fonte, variabili e formato
2. Analisi esplorativa: dimensioni, tipi di dati, valori mancanti e statistiche descrittive
3. Selezioni e ordinamenti: esercizi con .loc[] e .iloc[], ordinamenti crescenti/decrescenti con motivazione
4. Feature engineering: nuova colonna creata con apply + lambda per classificare il livello di accesso
5. Visualizzazioni: 5+ grafici con Matplotlib e Seaborn
   - Istogramma (distribuzione)
   - Boxplot (confronto per continente)
   - Scatterplot / lineplot (trend temporali per Paesi selezionati)
   - Barplot (bottom 10 Paesi 2016)
   - Lineplot (media globale per anno)
   
6. Conclusioni 

Key Insights
L’accesso globale all’elettricità è aumentato in modo significativo dal 2012 al 2016.
Persistono forti disuguaglianze tra regioni: l’Africa subsahariana rimane l’area più svantaggiata.
I Paesi industrializzati mantengono un accesso pressoché universale (oltre il 99%).
Alcune economie emergenti, come India e Bangladesh, mostrano progressi notevoli nel periodo analizzato.

Files
Analisi_Accesso_Elettricita.ipynb — notebook con analisi completa in italiano

access_electricity.csv — dataset utilizzato

LICENSE — Mozilla Public License 2.0
