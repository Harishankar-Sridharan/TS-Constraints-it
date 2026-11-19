# Pausa pranzo

Queste restrizioni vengono utilizzate per definire la pausa pranzo della risorsa.

**Formato:** HH:MM

**Inizio:** Specifica l'orario più presto in cui la risorsa può iniziare la sua pausa pranzo.

**Fine:** Specifica l'orario più tardi entro il quale la pausa pranzo deve essere completata. Quando viene utilizzata questa restrizione, la pausa pranzo definita da _Durata_ deve avvenire interamente all'interno della finestra temporale Inizio–Fine.

**Durata:** Indica la durata della pausa pranzo. Questa durata è considerata tempo di pausa, non tempo di lavoro, e viene quindi detratta dalle ore lavorative totali definite per la giornata.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

Esempio 2:

Una risorsa con:\
**Orario di inizio** = 09:00;\
**Orario di fine** = 18:00;\
**Ora di pranzo** = 01:00;\
potrà lavorare (e svolgere visite) durante un periodo di 8 ore (= 18 – 9 – 1).
