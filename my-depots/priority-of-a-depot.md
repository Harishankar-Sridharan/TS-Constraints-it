# Priorità di un deposito

Questo vincolo consente di impostare un Deposito come prioritario rispetto agli altri siti.

* Se due Depositi sono vicini tra loro, il sistema darà priorità al sito con il valore di priorità più alto.
* Se i Depositi sono distanti, il sistema terrà comunque conto del valore di priorità, ma considererà anche la distanza tra la risorsa e i Depositi.
* Un deposito con un valore più alto è considerato di maggiore priorità.

**Formato:** Numero (intero)

**Esempio:**

* Il Deposito A ha un valore di priorità pari a 8 e il Deposito B ha un valore di priorità pari a 5.
* Se entrambi i Depositi sono vicini, il sistema visiterà prima il Deposito A.
* Se il Deposito B è più lontano, il sistema può comunque dare priorità al Deposito A in base alla distanza di percorrenza.
