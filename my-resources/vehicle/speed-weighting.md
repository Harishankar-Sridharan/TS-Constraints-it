# Ponderazione della velocità

Se i tempi di percorrenza osservati sono generalmente troppo bassi o troppo alti, l'utente può aggiustarli specificando, per ciascorsa risorsa, se essa opera più velocemente o più lentamente rispetto alla velocità definita nelle statistiche stradali. Questo permette all'utente di adattare i dati sul traffico ai vincoli specifici di ogni risorsa pur preservando le variazioni di velocità basate sull'orario e sulla direzione di marcia.

Il **Normale** il valore è il predefinito e funge da velocità di riferimento definita nel profilo del veicolo e/o fornita dalle mappe Here (statistiche stradali).

**Formato:** Numero

**Esempio:**\
Le statistiche stradali indicano una velocità di **50 km/h** sull'Avenue Aristide Briand a Bagneux.

* Se l'utente ritiene questa velocità troppo alta, assegna un **Peso di Velocità di 1,2 (più lento)**. La risorsa quindi viaggia **20% più lentamente**, a **40 km/h** invece di 50 km/h.
* Se l'utente ritiene questa velocità troppo bassa, assegna un **Peso di Velocità di 1,2 (più veloce)**. La risorsa quindi viaggia **20% più veloce**, a **60 km/h** invece di 50 km/h.
