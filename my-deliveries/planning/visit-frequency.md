# Frequenza delle visite

Questa vincolo specifica quante volte una visita deve avvenire entro un numero definito di giorni. TourSolver ottimizza la pianificazione distribuendo le visite il più equamente possibile considerando tutti gli altri vincoli applicabili.\
Nota: il vincolo di frequenza guida la pianificazione ma non garantisce il rispetto perfetto degli intervalli definiti. L'interfaccia di TourSolver mostra un indicatore che segnala il numero di visite che non soddisfano la frequenza prevista.

**Formato:** Carattere 1/5

Se questo vincolo è abilitato, il **Giorni lavorati** vincolo deve essere anche definito per le risorse.

***

**Esempi**

**Esempio 1:**

* **Frequenza visite = 3/5**\
  Il cliente deve essere visitato **3 volte entro 5 giorni**.\
  TourSolver punta a mantenere un **intervallo di 2 giorni** tra ogni visita.

***

**Esempio 2:**

* **Frequenza visite = 3/5\***\
  Il cliente deve essere visitato **3 volte entro 5 giorni**.\
  TourSolver dà priorità a assegnare tutte e 3 le visite allo **stesso risorsa**.\
  In questo caso, mantenere una distanza uguale tra le visite diventa secondario.

***

**Esempio 3:**

* **Frequenza visite = 1/5**\
  Il cliente deve essere visitato **una volta ogni 5 giorni**.\
  Se **Giorni lavorati = 1–5**, il cliente sarà visitato:
  * una volta tra **giorni 1–5**
  * una volta tra **giorni 6–10**
  * una volta tra **giorni 11–15**\
    Per assicurare un intervallo minimo specifico tra queste visite, puoi usare il **Intervallo minimo tra le visite**&#x20;
