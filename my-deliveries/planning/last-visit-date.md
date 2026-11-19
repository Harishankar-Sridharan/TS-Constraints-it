# Data dell'ultima visita

Questa restrizione specifica **quanti giorni fa è stata effettuata l'ultima visita** prima di iniziare la pianificazione corrente, per garantire il rispetto dell'intervallo minimo tra le visite.

**Formato:** Intero negativo

**Nota:** Se la frequenza delle visite ha più di una ricorrenza, questo vincolo è **non applicato**.

**Esempio:**

* **Frequenza delle visite:** 1/5
* **Spaziatura minima tra le visite:** 2 giorni
* **Data dell'ultima visita:** -1

In questo caso, il cliente sarà visitato a partire da **giorno 2**, perché una visita il giorno 1 violerebbe l'intervallo minimo di 2 giorni tra le visite.

**Dipende da:**

* Frequenza delle visite
* Intervallo minimo tra le visite
