# Tempo lavorato 1 a 10

Il **Ora di inizio/fine 1 fino a 10** i vincoli definiscono fino a quattro diverse finestre temporali giornaliere durante le quali una risorsa è autorizzata a iniziare e completare le proprie visite. Queste finestre temporali aiutano a controllare quando una risorsa può svolgere le attività all'interno di una giornata lavorativa.

Ogni coppia—**Ora di inizio** e **Ora di fine**—rappresenta un periodo operativo valido. È possibile configurare fino a quattro intervalli di tempo separati per riflettere orari di lavoro variabili, turni divisi o disponibilità speciali.

**Formato:** HH:MM\
Puoi definire da una a quattro finestre temporali a seconda di quanti periodi lavorativi la risorsa ha in un giorno.

***

#### **Esempio 1: Finestra temporale singola**

La risorsa lavora ogni giorno da **08:00 a 17:00**.

* _Ora di inizio 1 = 08:00_
* _Ora di fine 1 = 17:00_

Ciò significa che la risorsa può effettuare visite solo all'interno di questa singola finestra temporale.

***

#### **Esempio 2: Turno spezzato**

**La risorsa lavora in due turni**:

* Turno mattutino da **08:00 a 12:00**
* Turno pomeridiano da **14:00 a 18:00**

**Configurazione**:

* _Ora di inizio 1 = 08:00_, _Ora di fine 1 = 12:00_
* _Ora di inizio 2 = 14:00_, _Ora di fine 2 = 18:00_

Il sistema programmerà le visite solo all'interno di questi due intervalli.

***

#### **Esempio 3: Tre periodi lavorativi distinti**

**La risorsa è disponibile**:

* Di prima mattina da **06:00 a 08:00**
* A mezzogiorno da **11:00 a 13:00**
* Di sera da **16:00 a 19:00**

**Configurazione**:

* _Ora di inizio 1 = 06:00_, _Ora di fine 1 = 08:00_
* _Ora di inizio 2 = 11:00_, _Ora di fine 2 = 13:00_
* _Ora di inizio 3 = 16:00_, _Ora di fine 3 = 19:00_

Le visite saranno pianificate solo all'interno di questi tre blocchi orari.

***

#### **Esempio 4: Utilizzo di tutte e quattro le finestre temporali**

**La risorsa ha periodi di disponibilità brevi e variabili durante la giornata:**

* **07:00–09:00**
* **10:00–12:00**
* **14:00–15:00**
* **17:00–19:00**

**Configurazione**:

* _Ora di inizio 1 = 07:00_, _Ora di fine 1 = 09:00_
* _Ora di inizio 2 = 10:00_, _Ora di fine 2 = 12:00_
* _Ora di inizio 3 = 14:00_, _Ora di fine 3 = 15:00_
* _Ora di inizio 4 = 17:00_, _Ora di fine 4 = 19:00_

Allo stesso modo è possibile configurare i restanti sei orari di lavoro.
