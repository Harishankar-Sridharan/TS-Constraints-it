# Penalità per ora di ritardo

Questa restrizione rappresenta un **costo aggiuntivo applicato per ogni ora di ritardo**. Dà all'utente un controllo più preciso su quanto rigorosamente vengano rispettate le finestre temporali di visita. **Nota:** Le restrizioni relative alla tolleranza dovrebbero essere usate con cautela, poiché possono dominare il processo di ottimizzazione rendendo i ritardi la priorità principale dell'ottimizzazione.

**Formato:** Numerico (intero o decimale)

**Esempio:**\
Se sei disposto ad accettare deviazioni e distanza aggiuntiva per rispettare meglio le finestre di consegna—for esempio percorrendo un extra **70 km** per evitare di essere **in ritardo di 5 minuti**—la penalità può essere calcolata come segue:

* Costo per km = **0.5**
* Distanza extra = **70 km**
* Fattore di conversione = **12** (60 minuti / 5 minuti)

Penalità per ora di ritardo = **0,5 × 70 × 12 = 420**

Pertanto, il valore da inserire per la **Penalità per ora di ritardo** restrizione è **420**.

**Dipende da:**

* Orario di apertura
* Orario di chiusura

**Incompatibile con:**

* Tolleranza al ritardo
