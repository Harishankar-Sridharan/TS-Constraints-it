# Intervallo massimo prima della visita

Questa vincolo definisce il **intervallo di tempo massimo consentito** tra due visite collegate.

**Formato:** HH:MM

**Nome tecnico del campo:** `tsOrderBeforeMaxTimeSpacing`

**Dipende da:** Inizia dopo

**Esempio:**

* La Visita A e la Visita B sono collegate.
* Lo spaziamento massimo tra di esse è impostato su `01:30:00`.

In questo caso, **La Visita B deve iniziare entro 1 ora e 30 minuti dopo la Visita A**; altrimenti, la catena non può essere programmata.
