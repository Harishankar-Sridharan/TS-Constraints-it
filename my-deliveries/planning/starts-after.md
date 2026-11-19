# Inizia dopo

Questa vincolo ti consente di **collegare visite**, assicurando che due visite siano eseguite **lo stesso giorno dallo stesso autista**.

La visita a cui viene applicato questo vincolo sarà programmata **dopo la visita a cui è collegata**. Se qualsiasi visita nella catena non può essere programmata, **nessuna delle visite nella catena sarà collocata**.

Se utilizzato, il valore dovrebbe corrispondere a **ID Cliente** della visita con cui collegarsi.

**Formato:** Intero (corrispondente all'ID Cliente)

**Esempio:**

* La Visita A ha ID Cliente 101
* La Visita B ha questo vincolo impostato su 101

In questo caso, la Visita B sarà programmata **dopo la Visita A nello stesso giorno dallo stesso autista**.

**Dipende da:** ID Cliente\
**Incompatibile con:** Frequenza delle visite
