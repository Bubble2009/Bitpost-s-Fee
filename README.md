![Bitpost Logo](assets/BitPost_logo.jpg)

# Bitpost e le fee

Recentemente, Zio Satoshi ha tenuto una *live* in cui presentava la piattaforma di **BitPost**.<br>
Dalle domande emerse in *live*, dai messaggi sul gruppo e anche dalle domande che mi hanno posto durante un SatoshiSpritz, ho compreso che la cosa si cui si fa più confusione sono le *fee* che verranno applicate. <br>
Spero con questo scritto di chiare il tutto.

## Due parole su BitPost
Per chi fosse capitato suo queste pagine casualmente, spiego brevemente in cosa consiste **BitPost**.

**Bitpost** è nato per accontentare due esigenze di cui il mercato aveva assoluta necessità e non sapeva come risolverle.

1. **L'acquisto di beni in totale privacy** e in modo pseudonimo
2. **L'acquisto di beni utilizzando bitcoin**

Gli utenti con queste esigenze vengono chiamati **buyer**<br>
Per soddisfare le esigenze dei **buyer**, viene richiesto altri utenti di effettuare gli acquisti.<br>
L'utente che effettuerà l'acquisto, viene chiamato **bitworker** e, come ricompensa per il suo operato, verrà pagato in bitcoin.<br>
Tramite alcuni stratagemmi che verranno illustrati all'interno della piattaforma, il **bitworker** potrà effettuare l'acquisto e la spedizione in modo totalmente pseudonimo.

La piattaforma non viene chiamata in causa durante la transazione, verrà soltanto interpellata qualora debba mediare una controversia.

# Le Fee
La piattaforma **BitPost**, per potersi mantenere, chiede una *fee* dell'8% sulla transazione.<br>
Di base, questa *fee* è pagata dal **bitworker**. Questo perchè il **bitworker** verrà ripagato ricevendo Satoshi no KYC e le *fee* saranno il prezzo di questa ricompensa.<br>
Come ho scritto, questa è la base, ma ora vediamo nello specifico questa ed altre due situazioni limite ed esattamente:

1. [Situazione Standard](#Situazione_Standard)
2. [**buyer** molto esoso](#Buyer_Esoso)
3. **buyer** con necessità di urgenza

## Situazione Standard

Ipotizziamo che il **buyer** voglia comprare una cosa a caso, un :link:[BitBox02](https://amzn.to/4qoXKBr) e che quindi (giustamente) lo voglia fare in maniera pseudonima.<br>
Il **buyer** andrà sulla piattaforma di **BitPost** e inserirà il link del BitBox02.

![fee 0%](assets/BitPost_0pc.jpg)

Dall'immagine potete vedere tre dati molto importanti:
* Il prezzo di vendita dell'oggetto, ovvero € 159,00
* Il Fee Order di questa transazione che in questo caso è impostato a 0%
* Il prezzo finale che il **buyer** andrà a pagare che in questo caso rimane € 159,00.<br>Questo è il controvalore in Euro, ma il pagamento avverrà in sats.

Dopo che il **buyer** avrà caricato questa transazione, aspetterà di trovare un **bitworker** che la prenda in carico ed esegua tutti i passaggi necessari ad arrivare alla fine della transazione.<br>
Un volta che il **buyer** avrà indicato alla piattaforma di aver ritirato l'oggetto integro, il **bitworker** potrà riscattare il suo pagamento in satoshi.

In questo caso, avendo il **buyer** indicato 0% come fee order, ecco quanto spetterà al **bitworker**:

``€ 159,00 - 8% = € 147,00`` [^1]

## Buyer Esoso

Ipotizziamo che il **buyer** di prima, che vuole il BitBox02, possa fare alcuni ragionamenti del tipo:
* Chi riceverà bitcoin avrà un vantaggio futuro come riserva di valore;
* Il controvalore è molto basso, non posso rimetterci troppo;
* Qualsiasi cosa passi per la testa di un **buyer**

Partendo da questi pensieri, il **buyer** potrebbe decidere di essere *Esoso*, pertanto di voler acquistare un oggetto scontato.

In questo caso, la piattaforma, permette di caricare un ordine di acquisto con uno sconto massimo del 5%.<br>
In questo esempio mostrerò appunto il caso limite:

![fee -5%](assets/BitPost_-5pc.jpg)

Dall'immagine potete rileviamo gli stessi 3 valori importanti di prima:
* Il prezzo di vendita dell'oggetto, ovvero € 159,00
* Il Fee Order di questa transazione che in questo caso è impostato a **-5%**
* Il prezzo finale che il **buyer** andrà a pagare che in questo caso rimane € 151,05.<br>Questo è il controvalore in Euro, ma il pagamento avverrà in sats.






[^1]: Valori arrotondati per semplicità