# Durata di carico/scarico per unità

Questa vincolo specifica il **tempo richiesto in deposito per caricare o scaricare un'unità di prodotto**. Il valore viene moltiplicato per il **quantità di prodotto** da caricare o scaricare, a seconda del tipo di percorso.

> **Nota:** Questo si applica **solo** al **Quantità 1** vincolo delle visite e **non** alle altre 23 quantità possibili.

**Formato:** HH:MM

**Esempio:**

* **Durata fissa carico/scarico:** 00:3:00
* **Durata carico/scarico per unità:** 120 secondi (2 minuti per unità)
* **Quantità da caricare:** 8 unità

Calcolo:

* Tempo per unità = 120 sec × 8 = 960 sec = 16 minuti
* Durata totale in deposito = 30 min (fisso) + 16 min = **46 minuti**

**Dipende da:** Quantità (Consegne)
