📁[Storytelling](https://antonio-vigilante.github.io/filosofia/storytelling.html)

## Ink

Guardiamo subito un esempio di attività con Ink.

🔗 [L'esistenza di Dio](https://antonio-vigilante.github.io/filosofia/storytelling/ink/dio/index.html)

Questo piccolo percorso permette allo studente di esplorare diverse posizioni riguardo all'esistenza di Dio: fede in un Dio personale, apertura a un principio cosmico, agnosticismo e ateismo. Selezionando di volta in volta la risposta nella quale si riconosce, giunge a chiarire la sua posizione; giunto alla fine ha la possibilità di ricominciare dall'inizio.

Si tratta di un percorso molto semplice, che mostra però già le potenzialità di Ink, un linguaggio creato da [Inkle Studios](https://www.inklestudios.com/), una casa di sviluppo indipendente britannica, fondata nel 2011 da Jon Ingold e Joseph Humfrey, cui si devono videogiochi di successo come _80 Days_ e _Heaven's Vault_. Ink è un linguaggio di scripting open-source che permette di scrivere storie interattive con una sintassi semplice, leggibile e potente. Ink è stato poi reso pubblico, diventando uno strumento molto apprezzato da scrittori, game designer, educatori e creativi di tutto il mondo. _Inky_, l'editor per il linguaggio Ink, può essere scaricato gratis a 🔗[questo link](https://www.inklestudios.com/ink/), in versione Mac, Windows e Linux.

Esporiamo il codice dell'attività precedente per familiarizzarci con il linguaggio.

```
TITLE: L'esistenza di Dio

->Inizio

=== Inizio ===
Sei in un tranquillo giardino, assorto nei tuoi pensieri sull'universo e il senso della vita. Una domanda si fa strada nella tua mente: "Dio esiste?"

* "Sì, ne sono convinto."
    -> Credente
* "No, è un'invenzione umana."
    -> Ateo
* "Non ne sono sicuro."
    -> Agnostico
* "Dipende da cosa intendi per 'Dio'."
    -> Filosofico

=== Credente ===
Credi fermamente in Dio. Ma ora ti chiedi: che tipo di Dio?

* "Un Dio personale, che ascolta e guida."
    -> DioPersonale
* "Un principio cosmico, impersonale."
    -> DioCosmico
* "Il Dio delle Scritture."
    -> DioReligioso

=== Ateo ===
Sei convinto che Dio non esista. Ma come sei giunto a questa conclusione?

* "Attraverso la scienza e la ragione."
    -> AteoScientifico
* "Perché il male esiste."
    -> ProblemaMale
* "Perché le religioni sono strumenti di potere."
    -> CriticaReligione

=== Agnostico ===
Non sai se Dio esiste. Ma come vivi questa incertezza?

* "Con apertura e ricerca."
    -> RicercaSpirituale
* "Con indifferenza."
    -> Indifferenza
* "Con timore e dubbio."
    -> Angoscia

=== Filosofico ===
Vuoi riflettere sul concetto di Dio.

* "Un Dio causa prima dell'universo."
    -> CausaPrima
* "Un Dio come orizzonte del bene."
    -> DioEtico
* "Un Dio come invenzione simbolica."
    -> DioSimbolico

=== DioPersonale ===
Credi in un Dio che ha un rapporto personale con gli esseri umani. Come vivi questa fede?

* "Attraverso la preghiera quotidiana."
    -> Preghiera
* "Cercando segni della Sua presenza."
    -> Segni
* "Nel rapporto con gli altri."
    -> AmoreProssimo

=== DioCosmico ===
Credi in un principio universale, come il Tao o il Brahman. Come ti relazioni a esso?

* "Attraverso la meditazione."
    -> Meditazione
* "Cercando armonia con la natura."
    -> Armonia
* "Studiando le tradizioni orientali."
    -> Tradizioni

=== DioReligioso ===
Credi nel Dio delle Scritture. A quale tradizione appartieni?

* "Cristianesimo."
    -> Cristianesimo
* "Islam."
    -> Islam
* "Ebraismo."
    -> Ebraismo

=== AteoScientifico ===
Credi che l'universo si spieghi senza Dio. Come reagisci al senso della vita?

* "Lo trovo nella conoscenza."
    -> Conoscenza
* "Nel miglioramento dell'umanità."
    -> Umanesimo
* "Non ha senso, e va accettato."
    -> Assurdo

=== ProblemaMale ===
Come può esistere Dio se esiste il male?

* "È una contraddizione insanabile."
    -> RifiutoTeismo
* "Forse Dio non è onnipotente."
    -> TeismoLimitato
* "Il male è una prova o mistero."
    -> Teodicea

=== Preghiera ===
La preghiera ti dà conforto e connessione. Ma a volte ti chiedi se qualcuno ascolta davvero.
-> Fine

=== Segni ===
Ogni giorno cerchi piccoli miracoli e coincidenze significative. A volte sembrano esserci.
-> Fine

=== AmoreProssimo ===
Nel volto dell'altro riconosci una scintilla divina. Questo ti guida nel mondo.
-> Fine

=== Meditazione ===
Ti immergi nel silenzio e nella contemplazione, cercando di cogliere l'unità del tutto.
-> Fine

=== Armonia ===
Cerchi equilibrio tra te stesso, gli altri e la natura. È una forma di sacralità immanente.
-> Fine

=== Tradizioni ===
Ti dedichi allo studio dei testi e delle pratiche orientali, trovando una sapienza profonda.
-> Fine

=== Cristianesimo ===
La figura di Gesù e il Vangelo ti parlano profondamente. La fede è una via personale e comunitaria.
-> Fine

=== Islam ===
La bellezza del Corano e la disciplina della preghiera ti guidano nella vita.
-> Fine

=== Ebraismo ===
Le Scritture e la memoria del popolo d'Israele sono per te sorgenti di senso.
-> Fine

=== Conoscenza ===
Nella scienza e nella filosofia trovi lo stupore e la meraviglia dell'esistenza.
-> Fine

=== Umanesimo ===
Credi nel valore dell'uomo e nell'impegno per il bene comune, senza bisogno di Dio.
-> Fine

=== Assurdo ===
La vita è priva di senso oggettivo, ma puoi ancora scegliere come viverla.
-> Fine

=== RifiutoTeismo ===
Il male del mondo ti ha convinto che nessun Dio buono e onnipotente può esistere.
-> Fine

=== TeismoLimitato ===
Forse Dio c'è, ma non può tutto. È una presenza imperfetta, come noi.
-> Fine

=== Teodicea ===
Cerchi di conciliare Dio e male: libero arbitrio, prova, mistero. Ma restano dubbi.
-> Fine

=== CriticaReligione ===
Vedi nella religione un costrutto storico, spesso usato per dominare.
-> Fine

=== RicercaSpirituale ===
Pur nell'incertezza, continui a cercare. Filosofia, spiritualità, dialogo.
-> Fine

=== Indifferenza ===
Dio o no, vivi la tua vita giorno per giorno senza pensarci troppo.
-> Fine

=== Angoscia ===
L'incertezza ti pesa. Il silenzio dell'universo ti opprime.
-> Fine

=== CausaPrima ===
Dio come causa prima: razionale, necessario, non personale. Un principio metafisico.
-> Fine

=== DioEtico ===
Dio come ideale del bene: esiste in quanto guida morale, non come ente.
-> Fine

=== DioSimbolico ===
Dio come creazione del linguaggio umano: utile, evocativo, ma non reale.
-> Fine

=== Fine ===
La tua posizione è chiara. Ma forse hai voglia di interrogarti ancora.
+ "Sì"
    -> Inizio2
+ "No"
    -> Uscita

-> END

=== Inizio2 ===
Bene, interroghiamoci ancora. Dunque: esiste Dio?
* "Sì, ne sono convinto."
    -> Credente
* "No, è un'invenzione umana."
    -> Ateo
* "Non ne sono sicuro."
    -> Agnostico
* "Dipende da cosa intendi per 'Dio'."
    -> Filosofico

== Uscita ==
Bene. Buon cammino!

 -> END
```
 
