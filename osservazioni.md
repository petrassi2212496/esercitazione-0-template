# Osservazioni — Esercitazione 0

Gruppo: group-44ebd5030990d022-6

Componenti (nome, cognome e username GitHub di entrambi): Vittoria Petrassi petrassi2212496, Chiara Luce Masci masci2271682

URL del repository condiviso: https://github.com/petrassi2212496/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: Ci siamo alternate.

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete saper spiegare le prove svolte.

## Step 1 - Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello Viene eseguito l'eseguibile che stampa la frase contenuta nel printf su terminale.

Che cosa ho capito su sorgente ed eseguibile: Il sorgente è il codice scritto a mano, una volta compilato si crea l'eseguibile in linguaggio macchina.

Output richiesto e comportamento del programma prima della modifica: Ci è stato richiesto di stampare "Hello computational physics", prima delle modifiche l'eseguibile non restituiva nulla sul terminale.

Esito dopo la modifica e spiegazione della correzione: Aggiungendo un printf e ricompilando l'eseguibile restituisce su terminale la frase richiesta, stampandola e andando a capo.

## Step 1 — Git
(Verifica commit changes)
Quali file ho incluso nel commit e perché: abbiamo incluso hello.c e osservazioni.md perché sono i due file sorgente modificati durante l'esercitazione.

Come ho verificato che la versione provata sia presente su GitHub: abbiamo controllato la cronologia nel repository.

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: prima del pull le modifiche fatte su github non erano visibile sulla copia locale, dopo le modifiche fatte su github sono state copiate sul file locale, non serve un nuvo clone perché stiamo di volta in volta esportando le modifiche fatte.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: una stringa, un intero e un reale attraverso il comando ./eco TESTO INTERO REALE con stampa dei valori inseriti su terminale.

Che cosa posso concludere: Si possono passare argomenti di diverso tipo a un eseguibile e fare una conversione.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: abbiamo passato gli stessi argomenti passati prima e ottenuto gli stessi risultati, passando ora però argomenti "errati" abbiamo ottenuto dei messaggi di "warning" che segnalavano l'errore nell'inserimento.

Che cosa ho capito su testo, conversioni e stampa: è possibile inserire variabili di diverso tipo, lette inizialmente dal programma come stringhe, e convertirle in interi o double attraverso opportune funzioni. Si può verificare l'inserimento corretto della variabile e stampare di conseguenza avvisi o altro.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: con argomenti validi l'eseguibile stamperà gli argomenti inseriti, con "dodici" stamperà 0 sdpettandosi un intero.

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: eco.txt contiene nel primo caso i valori inseriti, nel secondo il secodno valore viene stampato come 0 perché si aspettava un intero e invece è stata inserito "dodici". ">" redirige l'output dell'eseguibile dal terminale sul file txt.

Come un controllo automatico può riconoscere un errore: a seconda di ciò che legge l'eseguibile, il controllo può riconoscere l'input dato e stampare un messaggio di conseguenza. Se si vuole avere un intero e l'eseguibile riceve in input dei caratteri di testo il controllo rileverà un errore.

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: Per cambiare come il programma usa i dati inseriti bisogna ricompilare, per cambiare i dati in input basta avviare nuovamente l'eseguibile con altri dati.

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: usando git log posso vedere lo storico di tutti i commit, aggiungendo --online li vedrò compatti (occuperanno una sola riga ognuno), usando poi -5 vedrò solo gli ultimi cinque commit. Se quando uso git commit lo nomino con -m "nome commit" allora lo rendo riconoscibile a futuri controlli.

Come ho verificato che la versione finale sia presente su GitHub: mi basta aprire sulla pagina web il file per vedere se è uguale a quello che ho modificato localmente o digitare git status e verificare se appare "your branch is up to date with origin".
