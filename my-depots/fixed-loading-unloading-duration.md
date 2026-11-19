# Durata fissa di carico/scarico

Questa vincolo definisce il **quantità minima di tempo** che una risorsa deve trascorrere al deposito quando esegue una **operazione di carico o scarico**.\
Questo tempo base può essere **integrato** dalla durata aggiuntiva specificata nel **vincolo Durata di carico/scarico per unità** .

In altre parole, il tempo totale trascorso al deposito =\
**Tempo minimo al deposito + (Tempo per unità × Numero di unità)**

***

**Esempio**

* **Tempo minimo di carico al deposito:** 10 minuti
* **Durata di carico per unità:** 2 minuti
* **Numero di unità da caricare:** 5

**Calcolo:**\
Tempo totale al deposito = 10 minuti + (2 × 5)\
Tempo totale al deposito = **20 minuti**

In questo caso, la risorsa trascorrerà **20 minuti** al deposito prima di partire per la prossima visita pianificata.
