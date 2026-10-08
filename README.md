# fcc-world-cup-database
Progettazione e implementazione di un database relazionale per tracciare le partite e i risultati storici della Coppa del Mondo FIFA.

Caratteristiche principali:

Progettazione dello schema relazionale conforme alla 3NF (tabelle teams e games) con chiavi primarie, vincoli di unicità e chiavi esterne per garantire l'integrità referenziale.

Sviluppo di uno script Bash (insert_data.sh) per il caricamento automatizzato (ETL) e l'inserimento dei dati a partire da un file sorgente CSV (while IFS="," read), gestendo l'inserimento condizionale di record unici per evitare duplicazioni.

Scrittura di uno script di interrogazione (queries.sh) con JOIN complesse, sottoquery, raggruppamenti (GROUP BY) e funzioni di aggregazione (AVG, MAX, SUM) per estrarre statistiche e report dettagliati.
