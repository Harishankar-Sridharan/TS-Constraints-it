# Fascia fissa

Questa vincolo designa un **visita prioritaria**, fissando il **risorsa, il giorno e l'orario** della visita se specificato.

**Formato:** Binario

* **0** – La visita è **non fissata**.
* **1** – La visita è **fissata** secondo le condizioni specificate.

**Valore predefinito:** 1

**Dipende da:**

* Orario di apertura
* Durata della visita

**Esempio:**

* Una visita è programmata con un flag di priorità impostato su 1, un orario di inizio alle 09:00 e una durata di 2 ore.
* Il sistema garantisce che la risorsa assegnata esegua questa visita **esattamente alle 09:00** per 2 ore, rispettando l'orario di apertura
