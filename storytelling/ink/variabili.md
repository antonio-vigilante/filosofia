## Ink

### Le variabili

Queste indicazioni sono sufficienti per creare percorsi semplici, come quello dell'esempio. Per creare percorsi più complessi è necessario considerare le variabili.  Una variabile è un “contenitore” che memorizza un’informazione: un numero, un valore logico (vero/falso), una parola; in Ink le variabili permettono di ricordare cosa ha scelto l’utente o modificare il testo in base al suo percorso.

Vediamo ancora un esempio. 

🔗 [Un profilo morale secondo Kant](kant/index.html) 

Guardiamo il codice.

```
VAR usa_ragione = false
VAR aiuta_altri = false
VAR mente_per_convenienza = false

== inizio ==
Ti trovi davanti a una scelta morale. Che cosa segui?

* [La voce della ragione] 
    ~ usa_ragione = true
    Agisci per dovere, non per inclinazione.
    -> seconda_scelta

* [Il mio desiderio personale] 
    "Seguo ciò che sento."
    -> seconda_scelta

== seconda_scelta ==
Più tardi, vedi una persona in difficoltà che chiede aiuto.

* [Aiutala, è giusto così] 
    ~ aiuta_altri = true
    Offri il tuo sostegno senza esitare.
    -> terza_scelta

* [Ignora, non è affar tuo] 
    Passi oltre, concentrato su te stesso.
    -> terza_scelta

== terza_scelta ==
Qualcuno ti fa una domanda scomoda: dire la verità potrebbe metterti in difficoltà.

* [Dico la verità, sempre] 
    "Non posso mentire, anche se mi danneggia."
    -> conseguenze_finali

* [Mento per evitare problemi] 
    ~ mente_per_convenienza = true
    "Meglio una bugia utile che una verità pericolosa."
    -> conseguenze_finali

== conseguenze_finali ==
Ecco il tuo profilo morale, secondo Kant:

{usa_ragione:
Kant ti osserva con stima. Hai cercato di seguire la ragione.
- else:
Hai agito mosso da inclinazione, non per dovere.
}

{aiuta_altri:
Hai rispettato il dovere verso l'altro trattandolo come fine.
- else:
Hai ignorato il dovere morale di aiutare chi è in difficoltà.
}

{mente_per_convenienza:
La tua menzogna ha compromesso la tua moralità.
- else:
Hai detto la verità, anche a tuo svantaggio: atto moralmente valido.
}

-> END
```

Abbiamo inserito all'inizio tre variabili:
```
VAR usa_ragione = false
VAR aiuta_altri = false
VAR mente_per_convenienza = false
```
Tutte e tre sono settate su `fale`. All’avvio della storia l’utente non ha ancora fatto alcuna scelta, quindi tutte le variabili che rappresentano azioni o atteggiamenti morali (es. usare la ragione, aiutare, mentire) devono partire da un valore neutro, che in questo caso è, appunto, `false`. 
Durante il gioco, quando il giocatore fa una scelta significativa, una variabile può essere aggiornata: 
```
* [Aiutala, è giusto così] 
    ~ aiuta_altri = true
```

Qui il simbolo `~` indica che stiamo modificando la variabile `aiuta_altri`, impostandola su `true` (vero), perché il giocatore ha aiutato la persona in difficoltà.

Alla fine del gioco, le variabili sono controllate per fornire un giudizio morale personalizzato:

```
{usa_ragione:
Kant ti osserva con stima. Hai cercato di seguire la ragione.
- else:
Hai agito mosso da inclinazione, non per dovere.
}
```
Questa struttura significa: Se la variabile `usa_ragione` è vera, stampa la prima frase. Altrimenti (`else`), stampa la seconda.
