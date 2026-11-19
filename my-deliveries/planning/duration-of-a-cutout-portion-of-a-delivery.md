# Durata di una porzione staccata di una consegna

Questa vincolo specifica il **durata minima richiesta per consentire che una visita venga suddivisa** in più parti. Una visita può essere suddivisa in diversi giorni o intorno a una pausa pranzo. Questo valore è strettamente legato al **Durata della visita** .

**Formato:**  HH:MM

**Esempio:**

* La visita A ha un **Durata della visita** di 4 ore.
* La visita B ha un **Durata della visita** di 30 minuti.
* Il **La durata di una porzione di una visita suddivisa** è impostato su 01:00

Questo significa che **solo le visite più lunghe di 1 ora** possono essere suddivise:

* La visita A può essere divisa in più parti se necessario.
* La visita B non può essere suddivisa, poiché è più breve della durata minima della porzione.

Il **durata minima per ogni porzione divisa** è controllata dal **Durata soglia per tagliare le visite** .

**Regola aggiuntiva:** Una visita **non può essere suddivisa in più di 16 blocchi**.

**Dipende da:**

* Durata della visita
* Durata soglia per tagliare le visite
