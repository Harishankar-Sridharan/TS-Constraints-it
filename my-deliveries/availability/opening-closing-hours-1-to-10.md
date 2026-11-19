# Orari di apertura/chiusura 1 a 10

### Orari di apertura/chiusura

Questi vincoli consentono di specificare la finestra temporale durante la quale una visita può avere luogo.\
**Orario di apertura 1** indica l'orario più presto in cui la visita può iniziare, e **Orario di chiusura 1** indica l'orario più tardi in cui può iniziare. Questa finestra temporale si applica a tutti i giorni a meno che **Giorni di apertura 1** sia definito; in tal caso, la finestra temporale si applica solo ai giorni specificati.

Se non viene definita alcuna finestra temporale per una visita, questa può essere effettuata in qualsiasi momento nei Giorni di apertura consentiti e nell'orario di lavoro della risorsa. È possibile configurare fino a quattro diverse finestre temporali (ognuna con i propri giorni associati) per una singola visita.

**Formato:** HH:MM:SS

**Esempio 1:**\
Orario di apertura 1 = 07:30:00 e Orario di chiusura 1 = 11:30:00 creano una finestra temporale di quattro ore durante la quale il cliente può essere visitato.

**Esempio 2:**\
Per un cliente che richiede la consegna tra le 23:00 e le 03:00, gli orari devono essere spostati in modo che ricadano nello stesso giorno. Questo permette di determinare correttamente l'ordine delle visite.\
Ad esempio:\
Orario di apertura 1 = 19:00:00 e Orario di chiusura 1 = 23:00:00 definiscono una finestra di quattro ore.\
Dopo l'ottimizzazione, gli orari di visita pianificati devono essere riportati all'intervallo di orario originale.\
Se TourSolver programma la visita alle 21:00, la visita effettiva avverrà alle 01:00 (= 23:00:00 + 2 ore).

Non sono supportate finestre temporali che si estendono su più giorni. Ad esempio, una finestra temporale dalle 23:00:00 alle 03:00:00 non può essere utilizzata senza adeguare gli orari.

Una visita non può iniziare prima dell'orario di apertura. Per impostazione predefinita, una visita che inizia all'interno della finestra temporale può proseguire oltre l'orario di chiusura. Se si desidera che la visita termini prima dell'orario di chiusura, abilitate l'opzione **Termina visita prima dell'orario di chiusura** opzione.

### Orari di apertura/chiusura 2 a 10

**Orari di apertura e chiusura 2**

Questi vincoli consentono di definire una seconda finestra temporale che si applica ai giorni di visita specificati in **Possibili giorni di visita 2**.\
**Orario di apertura 2** indica l'orario più presto in cui una visita può iniziare, mentre **Orario di chiusura 2** specifica l'orario più tardi in cui può iniziare.

**Formato:** HH:MM:SS

**Esempio 1:**\
Un cliente è disponibile per la consegna durante due periodi separati:

* Mattina: dalle 09:00 alle 12:00
* Pomeriggio: dalle 14:00 alle 17:00

**Per configurarlo, impostare**:

* Orario di apertura 1 = 09:00:00
* Orario di chiusura 1 = 12:00:00
* Orario di apertura 2 = 14:00:00
* Orario di chiusura 2 = 17:00:00

**Esempio 2:**\
Un cliente può essere visitato:

* Lunedì dalle 07:00 alle 17:00
* Mercoledì dalle 09:00 alle 18:00

**La configurazione sarebbe:**

* Orario di apertura 1 = 07:00:00
* Orario di chiusura 1 = 17:00:00
* Giorni di apertura 1 = 1 (Lunedì)
* Orario di apertura 2 = 09:00:00
* Orario di chiusura 2 = 18:00:00
* Giorni di apertura 2 = 3 (Mercoledì)

**Orari di apertura e chiusura 3**

Questi vincoli consentono di impostare una terza finestra temporale che si applica ai giorni di visita specificati in **Possibili giorni di visita 3**.\
**Orario di apertura 3** indica quando la visita può iniziare, e **Orario di chiusura 3** indica l'orario più tardi in cui la visita può iniziare.

**Formato:** HH:MM:SS

**Orari di apertura e chiusura 4**

Questi vincoli consentono di definire una seconda fascia oraria che si applicherà ai giorni di visita definiti in\
Possibili giorni di visita 4. L'orario di apertura 4 corrisponde all'orario a partire dal quale la visita può essere effettuata.\
L'orario di chiusura 4 corrisponde all'orario oltre il quale la visita non può più essere effettuata.
