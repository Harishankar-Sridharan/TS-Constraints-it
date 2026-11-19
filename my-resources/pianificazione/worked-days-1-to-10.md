# Giorni lavorati 1 a 10

Questo vincolo specifica tutti i **Giorni lavorati** (fino a 64 giorni) nei quali le finestre temporali definite dai **Tempo di Lavoro** vincoli si applicano.

\
**Formato:** Valori di carattere.

I giorni lavorati possono essere inseriti individualmente (ad esempio, _1,4_), come numeri interi (_1 a 64_), o utilizzando intervalli di date (ad esempio, _14/05/2016 => 17/07/2016_).

**Esempio 1:**

* _Giorni lavorati = 1,2,5_ (o _14/05/2016, 15/05/2016, 18/05/2016_) significa che la risorsa può effettuare visite nei giorni 1, 2 e 5 del periodo di pianificazione (o nelle date corrispondenti) all'interno delle finestre temporali definite dai vincoli di Orario di Lavoro.
* _Giorni lavorati = 1–5_ (o _14/05/2016 => 18/05/2016_) significa che la risorsa può effettuare visite in tutti i giorni da 1 a 5 del periodo di pianificazione (o in tutte le date dell'intervallo) all'interno delle finestre di Orario di Lavoro definite.

**Esempio 2:**\
Una risorsa lavora:

* Lunedì dalle 07:00 alle 17:00
* Mercoledì dalle 09:00 alle 18:00\
  Configurazione:
* _Orario di lavoro = 07:00–17:00_, _Giorni lavorati = 1_
* _Orario di lavoro 2 = 09:00–18:00_, _Giorni lavorati 2 = 3_

**Esempio 3:**\
Una risorsa lavora:

* Da lunedì a venerdì dalle 07:00 alle 17:00
* Sabato dalle 09:00 alle 12:00\
  Configurazione:
* _Orario di lavoro = 07:00–17:00_, _Giorni lavorati = 1–5_
* _Orario di lavoro 2 = 09:00–12:00_, _Giorni lavorati 2 = 6_
