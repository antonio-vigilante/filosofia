<link rel="stylesheet" href="../assets/style.css">

### Sintassi di base

Entriamo quindi nella [sandbox](https://argdown.org/sandbox/html). Troviamo nella finestra a sinistra del codice, che viene elaborato (_rendering_) nella finestra a destra.  

Dopo una breve presentazione, ci troviamo di fronte al seguente testo che fornisce alcune basi di Argdown:


```
 
## Argdown Basics

This is a normal statement with __bold__ and _italic_ text, 
a #tag and a [link](https://github.com/christianvoigt/
argdown-parser).

[Statement 1]: Another statement (after a blank line), 
this time with a title defined in square brackets. 
We can use the title to refer to this statement later 
or mention it in other statements. #(Another tag)

[Statement 2]: Let's do that now: The previous 
statement was @[Statement 1].
  + <Argument title>: Statements can be supported 
    by __arguments__. Arguments are defined by 
    using angle brackets. #tag
  - <Another argument>: This arguments attacks
  @[Statement 2]. #tag
    - <Yet another argument>: Arguments can also 
      be supported or attacked. #yet-another-tag

 ```

Nelle prime righe ci sono forniti alcuni semplici elementi del **markdown**, cui Argdown si ispira e che ingloba per la formattazione del testo.

\begin{tcolorbox}[colback=yellow!20, colframe=yellow!60]
\footnotesize Il \textbf{markdown} è un linguaggio di markup leggero creato da John Gruber nel 2004 con lo scopo di fornire un modo semplice e intuitivo per scrivere testi formattati. La sua sintassi è progettata per essere leggibile anche in formato plain text, rendendolo ideale per la scrittura di documentazione, blog, note e contenuti web. La sua semplicità lo rende accessibile anche a chi non ha esperienza con linguaggi di markup più complessi come HTML o LaTeX. Alcune fomattazioni del testo (corsivo, grassetto, barrato, sottolineato) sono supportate anche dalla popolare app di messagistica WhatsApp.
\end{tcolorbox}


Molto semplicemente, per scrivere del testo in corsivo è sufficiente inserire un trattino basso prima e dopo la parola, (\verb|_testo_|); per ottenere un testo in grassetto, il trattino basso dovrà essere doppio (\verb|__testo__|), per taggare una parola useremo l'asterisco (\verb|#testo|), mentre per collegare una parola ad un link  faremo così:

{\footnotesize
\begin{verbatim}
[parola](https://www.sitointernet.com)
\end{verbatim}
}

Sappiamo dunque, da queste prime righe, che per creare uno \textit{statement}, ossia una \textit{tesi}, possiamo semplicemente scrivere del testo, formattandolo se occorre nel modo indicato e, se vogliamo, aggiungendo dei tag. Possiamo però anche dare un titolo o nome alla nostra tesi usando le parentesi quadre, come segue (naturalmente si può usare qualsiasi titolo, possibilmente breve):

{\footnotesize
\begin{verbatim}
[Tesi_1]: Testo della tesi
\end{verbatim}
}

Possiamo far riferimento a questa tesi, nel corso della mappa, usando l'asterisco:

{\footnotesize
\begin{verbatim}
@Tesi_1
\end{verbatim}
}

Ora che abbiamo la tesi, dobbiamo aggiungere argomenti a favore o contrari. Per aggiungere un argomento a favore della tesi, andiamo nella riga successiva, lasciamo uno spazio, digitiamo + e scriviamo il testo di un argomento \textit{a favore} della tesi, mentre digiteremo - per un argomento contrario:
