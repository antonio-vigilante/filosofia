<div class="button orange">
Mappe argomentative
</div>

## Guida a Argdown

### Perché installare Argdown

Il modo migliore per usare Argdown in classe è usare la [Sandbox](https://argdown.org/sandbox/html), che consente di creare una mappa senza dover installare nulla; a scuola può non essere facile ottenere l'installazione di un programma sul computer di classe o sulla Lim. L'installazione di Argdown sul proprio computer consente invece di avere un maggiore controllo e l'integrazione con altri programmi.

### Installazione su Windows

Per usare Argdown abbiamo bisogno di Node.js. [Wikipedia ci informa](https://it.wikipedia.org/wiki/Node.js) che Node.js è "un runtime system open source multipiattaforma orientato agli eventi per l'esecuzione di codice JavaScript, costruito sul motore JavaScript V8 di Google Chrome". Per fortuna non abbiamo bisogno di capire esattamente cosa significhi; ci è sufficiente sapere che è uno strumento di cui abbiamo bisogno. E che, per fortuna, è molto facile da installare. Ci basta andare [nel sito di Node.js](https://nodejs.org/en/), cliccare su Download Node.js, avviare il file che abbiamo scaricato e seguire le istruzioni.

L'installazione di Argdown avviene invece attraverso riga di comando. Può spaventare chi sia abituato a installare software cliccando su un file .exe, ma in realtà è una procedura estremamente semplice.
Vediamo come fare passo dopo passo.

Apriamo il menu Start (in basso a sinistra sul monitor), digitiamo cmd e premiamo Invia. 
<figure>
  <img src="immagini/cmd.png">
</figure>

Nella finestra che si apre digitiamo

```
npm install -g @argdown/cli
```

Questo è sufficiente per installare Argdown. Per verificare che l'installazione sia andata a buon fine, digitiamo ancora:

```

### Installazione su Linux

Anche su Linux abbiamo bisogno in primo luogo di installare Node.js. Possiamo farlo aprendo il terminale e digitando:

``○6
sudo apt update
sudo apt install nodejs npm
```

Per verificare che l'installazione sia andata a buon fine digitare:

```
node -v
npm -v
```

Quindi procediamo con l'installazione di Argdown:

```
sudo npm install -g @argdown/cli
```

Per verificare che l'installazione sia andata a buon fine:

```
argdown --version
```

Se l'installazione è andata a buon fine, si vedrà la versione di Argdown installata.

