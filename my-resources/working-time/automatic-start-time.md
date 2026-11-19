# Ora di inizio automatica

**Questo valore determina se l'orario di partenza della risorsa deve essere adattato in base agli orari di apertura della prima visita.**\
Quando attivato, aiuta a ridurre al minimo i tempi di attesa non necessari e migliora l'efficienza del percorso.

* Se **Disabilitato**, la risorsa inizia all'orario definito nel **Tempo di Lavoro** vincolo, anche se la prima visita apre più tardi. Potrebbe verificarsi tempo di attesa.
* Se **Abilitato**, l'orario di partenza della risorsa viene regolato automaticamente in base all'orario di apertura della prima visita per ridurre i tempi di attesa.

La risorsa non può mai iniziare prima del suo **Tempo di Lavoro**. Se l'orario di partenza cambia, l'orario di fine si sposta della stessa quantità, tranne quando il **Tempo di Lavoro Giornaliero** vincolo è applicato anche.

\
**Formato:** Sì / No

**Esempio**: Orario di Inizio Automatico - Sì

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption></figcaption></figure>
