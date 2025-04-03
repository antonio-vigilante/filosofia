<link rel="stylesheet" href="antonio-vigilante.github.io/filosofia/assets/style.css">

<div class="button orange">
Mappe argomentative
</div>

## Guida a Argdown

### Le mappe grafiche

Fino ad ora abbiamo considerato il rendering HTML del codice. Cliccando sulla voce di menu _Map_, in alto a destra, accediamo al rendering grafico del codice.
È possibile visualizzare la mappa in due formati grafici, Viz Js e Dagre D3, due librerie JavaScript che danno risultati grafici un po' diversi.
La nostra mappa sula pena di morte si presenta in questo modo nel formato Viz Js:

<figure>
  <img src="immagini/mappa01.png">
</figure>

Questo invece è il rendering in Dagre D3:

<figure>
  <img src="immagini/mappa02.png">
</figure>

Come si vede, gli argomenti a favore della dichiarazione sono collegati ad essa da linee verdi che terminano con una freccia, mentre quelli contrari sono collegati da linee rosse.

Se si desidera invertire la direzione della freccia, occore modificare il codice come segue:

```
[A]: a.
 +> <a1>: a1.
 + <a2>: a2
 -><b1>: b1
 -<b2>: b2
```

Il risultato è questo:

<figure>
  <img src="immagini/mappa03.png">
</figure>

Gli argomenti contrassegnati con `+>` e `->` risultano in uscita dalla dichiarazione, con una freccia che punta verso di essi.

[Indice](index.md) | [<<](argomenti.md) | [>>](raggruppare-gli-elementi.md)

