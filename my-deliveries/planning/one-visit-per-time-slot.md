# Una visita per fascia oraria

Questa opzione abilita il **ripetersi di una visita** per ogni fascia oraria disponibile.

**Formato:** Binario

* Se impostato su **1**, la risorsa **torna al deposito** tra le ripetizioni.
* Se impostato su **0** (predefinito), la risorsa non **torna al deposito** tra le ripetizioni.

**Esempio:**

* Una visita ha 3 fasce orarie durante il giorno.
* Se questo vincolo è impostato su `1`, la risorsa effettuerà la visita **tre volte**, tornando al deposito **dopo ogni visita**.
