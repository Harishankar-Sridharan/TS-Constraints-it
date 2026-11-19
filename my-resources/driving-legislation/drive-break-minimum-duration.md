# Durata minima della pausa di guida

Questa restrizione definisce la durata minima che una pausa di guida deve avere affinché venga conteggiata come tempo di riposo durante una sessione di guida.

\
**Formato**: HH:MM

**Nota**:\
La durata della pausa di guida non è considerata tempo di lavoro da TourSolver. Pertanto, la giornata lavorativa totale viene estesa dell'equivalente durata della pausa.

**Esempio**:\
Se una pausa è considerata riposo solo se dura almeno 15 minuti, allora _Durata minima pausa di guida = 00:15_.

Scenario di esempio (Durata massima di guida senza pausa + Durata della pausa di guida + Durata minima pausa di guida)

* Durata massima di guida senza pausa = 04:30
* Durata della pausa di guida = 00:45
* Durata minima pausa di guida = 00:15

Ciò significa che la risorsa può guidare per 4 ore e 30 minuti se prende un totale di 45 minuti di pausa. Questa pausa può essere suddivisa, ad esempio, in tre pause da 15 minuti, oppure in una pausa da 30 minuti seguita da una pausa da 15 minuti.

Tuttavia, se la risorsa ha effettuato due pause da 20 minuti e una da 10 minuti, deve comunque effettuare una pausa aggiuntiva di almeno 15 minuti per raggiungere i 45 minuti richiesti di tempo di riposo valido, perché la pausa da 10 minuti non soddisfa il requisito minimo di 15 minuti e quindi non viene conteggiata.
