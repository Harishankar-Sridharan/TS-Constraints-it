# Tipo

Questa restrizione specifica se una visita comporta un **consegna/lasciare** o un **reso/ritiro**.

**Formato:** Binario

* **0** – Il percorso è in **modalità di consegna**.
* **1** – Il percorso è in **modalità di ritiro**.
* **2** – Il percorso è in **modalità di consegna**, che deve essere completato **prima di qualsiasi ritiro** possa avvenire.

**Dipende da:** Quantità

**Esempio:**\
Se una risorsa deve prima consegnare articoli prima di raccogliere eventuali resi, impostare il valore su `2`.\
Se la visita comporta solo un ritiro, impostare il valore su `1`.
