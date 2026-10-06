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

eco.txt contiene nel primo caso i valori inseriti, nel secondo il secondo valore viene stampato come 0 perché si aspettava un intero e invece è stata inserita una stringa. ">" redirige l'output dell'eseguibile su un file txt.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato:

Che cosa ho capito su testo, conversioni e stampa:

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`:

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati:

Come un controllo automatico può riconoscere un errore:

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti:

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step:

Come ho verificato che la versione finale sia presente su GitHub:
