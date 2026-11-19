# Ritardo massimo

Questa restrizione ti consente di definire il **ritardo massimo consentito** oltre la fine della finestra temporale di una visita.

Il **Penalità per ritardo** vincolo deve essere utilizzato contemporaneamente.

**Formato:** HH:MM o HH:MM:SS

**Dipende da:**

* Orario di apertura
* Orario di chiusura
* Penalità per ora di ritardo

**Incompatibile con:**

* Tolleranza al ritardo

**Esempio**

Se la finestra temporale di visita di un cliente termina alle **17:00** e il **Ritardo massimo** è impostato su **00:10**, la risorsa è autorizzata ad arrivare fino a **10 minuti di ritardo**, cioè non oltre **17:10**.

Qualsiasi arrivo oltre **17:10** non sarà accettato e i ritardi entro questo limite saranno penalizzati secondo la **Penalità per ora di ritardo**
