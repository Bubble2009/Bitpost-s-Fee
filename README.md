![Bitpost Logo](assets/BitPost_logo.jpg)

# Bitpost e le fee

:link:[**BitPost**](https://www.bitpost.shop) è un progetto nato dalla mente di Zio Satoshi.<br>
Recentemente, Zio Satoshi ha tenuto una *live* in cui presentava la piattaforma di **BitPost**.<br>
Dalle domande emerse in *live*, dai messaggi sul gruppo e anche dalle domande che mi hanno posto durante un SatoshiSpritz, ho compreso che la cosa si cui si fa più confusione sono le *fee* che verranno applicate. <br>
Spero con questo scritto di chiare il tutto.

## Due parole su BitPost
Per chi fosse capitato suo queste pagine casualmente, spiego brevemente in cosa consiste :link:[**BitPost**](https://www.bitpost.shop).

Zio Satoshi ha scoperto che il mercato aveva delle esigenze che nessuno, fino ad ora, era riuscito a risolvere.<br>
Da un lato troviamo utenti con le seguenti necessità:

1. **L'acquisto di beni in totale privacy** e in modo pseudonimo
2. **L'acquisto di beni utilizzando bitcoin**

E dall'altro utenti che vogliono acquistare bitcoin in maniera *non KYC* senza esporsi a rischi.

**BitPost** è nato per mettere in contatto queste due tipologie di utenti.

Il primo tipo di utenti, sulla piattaforma vengono chiamati **buyer**<br>
La seconda tipologia di utenti, invece, viene definito **bitworker**.

Lo staff di **BitPost** lavorando strenuamente, ha definito un flusso di lavoro che permette di effettuare tutto con un alto livello di privacy ed anonimato.

Il tutto avviene in maniera automatica e la piattaforma interviene solo nella malaugurata ipotesi in cui nasca una controversia che non viene risolta di comune accordo tra le parti.

# Le Fee
La piattaforma **BitPost**, per potersi mantenere, chiede una *fee* dell'8% sulla transazione.<br>
Queste *fee* possono essere pagate da una o da entrambe le parti.<br>
In questo testo, voglio appunto mostrare le varie casistiche.

1. [Scenario SHA](#Scneario_con_fee_Condivise) ovvero *fee* equamente condivise;
2. [Scenario Standard](#Scenario_Standard)
3. [Scenario **buyer** con necessità di urgenza](#Scenario_Buyer_Frettoloso)
4. [Scenario con **buyer** molto esoso](#Scneario_Buyer_Esoso)

Di seguito ci sarà anche una [analisi di questi scenari](#Analisi_Scenari).

## Scenario con *fee* condivise
Ipotizziamo che il **buyer** voglia comprare una cosa a caso, un :link:[BitBox02](https://amzn.to/4qoXKBr) e che quindi (giustamente) lo voglia fare in maniera pseudonima.<br>
Il **buyer** andrà sulla piattaforma di **BitPost** e inserirà il link del BitBox02.

![fee 4%](assets/BitPost_4pc.jpg)

Dall'immagine potete vedere tre dati molto importanti:
* Il prezzo di vendita dell'oggetto, ovvero € 159,00
* Il Fee Order di questa transazione che in questo caso è impostato a 4%
* Il prezzo finale che il **buyer** andrà a pagare.<br>Avendo impostato le *fee* al 4%, il **buyer** pagherà l'oggetto in questione con una maggiorazione del 4% ovvero € 165,36.<br>Questo è il controvalore in Euro, ma il pagamento avverrà in sats.

Dopo che il **buyer** avrà caricato questa transazione, aspetterà di trovare un **bitworker** che la prenda in carico ed esegua tutti i passaggi necessari ad arrivare alla fine della transazione.<br>
Un volta che il **buyer** avrà indicato alla piattaforma di aver ritirato l'oggetto integro, il **bitworker** potrà riscattare il suo pagamento in satoshi.

In questo caso, avendo il **buyer** indicato 4% come fee order, ha già pagato il 4% delle *fee* ed il restante 4% spetterà al **bitworker**<btìr>Vediamo quanto spetterà al **bitworker**:

*  ``€ 159,00 - 4% = € 152,89``  [^1]


## Scenario Standard

Ipotizziamo che il **buyer** di prima, che vuole il BitBox02, possa non voler pagare *fee* e voglia comprare l'oggetto pagandolo esattamente quanto è venduto da Amazon.<br>
Ecco come **buyer** andrà sulla piattaforma di **BitPost** e inserirà il link del BitBox02.

![fee 0%](assets/BitPost_0pc.jpg)

Andiamo ad analizzare i tre dati molto importanti:
* Il prezzo di vendita dell'oggetto, ovvero € 159,00<br>(stesso oggetto, stesso prezzo);
* Il Fee Order di questa transazione che in questo caso è impostato a 0%
* Il prezzo finale che il **buyer** andrà a pagare che in questo caso rimane € 159,00.<br>Questo è il controvalore in Euro, ma il pagamento avverrà in sats.

Vediamo cosa accadrà questa accadrà in questo scenario quando la transazione sarà segnalata come andata a buon fine.

In questo caso, avendo il **buyer** indicato 0% come fee order, sarà il **bitworker** a dover pagare tutte le *fee*<br>Vediamo quindi quanto spetterà al **bitworker**:

* ``€ 159,00 - 8% = € 146,28`` [^1]

## Scenario Buyer Frettoloso
Il nostro **buyer**  ha veramente fretta di ricevere il suo BitBox, così decide di accollarsi lui tutte le *fee* in modo da incentivare un **bitworker** a prendere in carico il suo acquisto il più presto possibile.

Quando caricherà l'oggetto sulla piattaforma, indicherà quindi queste *fee*:

![fee 8%](assets/BitPost_8pc.jpg)

Andiamo ad analizzare i soliti tre dati molto importanti:
* Il prezzo di vendita dell'oggetto, ovvero € 159,00<br>(stesso oggetto, stesso prezzo);
* Il Fee Order di questa transazione che in questo caso è impostato a **+8%**
* Il prezzo finale che il **buyer** andrà a pagare che in questo caso sale a € 171,72.<br>Questo è il controvalore in Euro, ma il pagamento avverrà sempre in sats.

In questo caso, il **buyer** ha deciso di accollarsi tutte le *fee* ed una volta completata la transazione, il **bitworker** incasserà il controvalore del costo dell'oggetto acquistato:

* ``€ 159,00 - 0% = € 159,00`` [^1]

## Scenario Buyer Esoso

Ipotizziamo che il **buyer** di prima, che vuole il BitBox02, possa fare alcuni ragionamenti del tipo:
* Chi riceverà bitcoin avrà un vantaggio futuro come riserva di valore;
* Il controvalore è molto basso, non posso rimetterci troppo;
* Qualsiasi cosa passi per la testa di un **buyer**

Facendo simili pensieri, il **buyer**, potrebbe decidere di essere *Esoso*, e di provare ad acquistare l'oggetto scontato rispetto al prezzo di vendita.

In questo caso, la piattaforma, permette di caricare un ordine di acquisto con *uno sconto massimo del 5%*.<br>
In questo esempio mostrerò appunto questo limite:

![fee -5%](assets/BitPost_-5pc.jpg)

Guardiamo ancora una volta i soliti tre dati molto importanti:
* Il prezzo di vendita dell'oggetto, ovvero € 159,00<br>(stesso oggetto, stesso prezzo);
* Il Fee Order di questa transazione che in questo caso è impostato a **-5%**
* Il prezzo finale che il **buyer** andrà a pagare che in questo caso scende a € 151,05.<br>Questo è il controvalore in Euro, ma il pagamento avverrà in sats.

In questo scenario, il **buyer** sta chiedendo al **bitworker** non solo di pagare le *fee* della piattaforma, ma anche una sua *fee* personale.

Ammesso di trovare un **bitworker** che accetti di prendere in carico questa transazione, andiamo a vedere cosa accadrà alla sua ricompensa:

>*fee piattaforma* <br>
il **bitworker** dovrà sempre pagare l'8% di *fee* alla piattaforma, queste *fee* verranno calcolate sul valore originale del prodotto quindi:<br>
 * `8 di € 159 = € 12,72` [^1]
> Queste *fee* verranno sottratte dalla cifra versata dal **buyer**<br>
Al termine di questa transazione, il **bitworker** potrà quindi riscattare quanto segue:<br>
* `€ 151,05 - € 12,72 = € 138,99` [^1]<br>
> In questo caso, il **bitworker** pagherà il 13% di *fee*

## Analisi Scenari
Sopra ho riportato gli scenari limite che si possono trovare su BitPost.<br>
Se un **buyer** inserirà un ordine con [Scenario con **buyer** esoso](#Scneario_Buyer_Esoso), avrà più difficoltà a trovare un **bitworker** disposto a prendersi carico del suo ordine, ma se lo troverà potrà portarsi a casa un oggetto scontato.<br>
In maniera opposta, invece, quanto verrà caricato un ordine con [Scenario **buyer** Frettoloso](#Scenario_Buyer_Frettoloso), allora, sarà molto probabile che in pochissimo tempo un **bitworker** porterà a termine l'incarico.

Non è mio interesse dirvi quale scenario adottare durante l'uso di **BitPost**, ma, utilizzando quanto descritto, valutate le vostre esigenze e le vostre necessità.

| | |
| :------- | :--------: |
|  Per avere maggiori informazioni su BitPost, vi invito ad unirvi al canale Telegram ufficiale.<br>Dal canale potrete accedere ad una chat di supporto in cui potrete interagire direttamente con ZioSatoshi e con lo staff di BitPost.| [![QR](assets/qr-code_ABC.png)](https://t.me/+GlEaD0WD53BmNGE0) |
---
[^1]: Valori arrotondati per semplicità