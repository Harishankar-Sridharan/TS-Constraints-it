# Richiedi che tutte le competenze siano compatibili

Quando il **Compatibilità con le risorse** vincolo è applicato (soprattutto con più valori), questa impostazione ti permette di specificare se **solo una** caratteristica dall'elenco è sufficiente o se **tutte** le caratteristiche elencate sono necessarie.

**Formato:** Binario

* **0** – È richiesta solo una caratteristica dall'elenco.
* **1** – Sono richieste tutte le caratteristiche nell'elenco.

**Valore predefinito:** 1

**Esempio:**\
Se una visita può essere eseguita da una risorsa che soddisfa **una qualsiasi** delle caratteristiche elencate, imposta il valore su `0`.\
Se la visita richiede che una risorsa soddisfi **tutte** caratteristiche nell'elenco, lascia il valore su `1`
