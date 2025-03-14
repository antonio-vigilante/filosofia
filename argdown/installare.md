## Insallare

### Installazioen su Windows

L'installazione di Argdown avviene attraverso riga di comando. Può spaventare chi sia abituato a installare software cliccando su un file .exe, ma in realtà è una procedura estremamente semplice.
Vediamo come fare passo dopo passo.
Apriamo il menu Start (in basso a sinistra sul monitor), digitiamo cmd e premiamo Invia. 
<figure>
  <a href="cmd.PNG">
</figure>


Metodo 1: Prompt dei comandi (CMD)
Apri il menu Start (⊞ Win).
Digita cmd e premi Invio per aprire il Prompt dei comandi.
Ora puoi eseguire il comando per verificare/installare Node.
Metodo 2: PowerShell
Premi ⊞ Win + X e seleziona Windows Terminal o PowerShell.
Digita i comandi come node -v per verificare se Node è già installato.
Metodo 3: Terminale di Visual Studio Code
Apri Visual Studio Code.
Premi Ctrl + ò oppure Ctrl + Shift + P e cerca "Toggle Terminal".
Ora puoi digitare comandi come:
sh
Copia codice
npm install -g @argdown/cli
Mac
Metodo 1: Terminale macOS
Premi Cmd + Spazio per aprire Spotlight Search.
Digita Terminale e premi Invio.
Ora puoi installare Node con Homebrew:
sh
Copia codice
brew install node
Metodo 2: Terminale in Visual Studio Code
Apri VSC.
Premi Cmd + ò oppure Cmd + Shift + P e cerca "Toggle Terminal".
Digita i comandi per verificare/installare Node.
Linux
Apri il terminale con Ctrl + Alt + T oppure cerca "Terminale" nel menu delle applicazioni.
Installa Node.js con il comando:
sh
Copia codice
sudo apt install nodejs npm  # Per Ubuntu/Debian
Ora puoi controllare se Node è installato con:

sh
Copia codice
node -v
npm -v
