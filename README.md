# WebDevSmallProjects
Raccolta di piccoli progetti web sviluppati per esercitazioni e sperimentazioni pratiche.
Include giochi interattivi e applicazioni utility realizzate con HTML, CSS e JavaScript.

## Panoramica:
**obbiettivo:** Sperimentare interattività, manipolazione del DOM, gestione eventi e logica applicativa in JavaScript.
**Tecnologie principali:** HTML5, CSS3, JavaScript, PHP
**Destinatari:** Chi vuole vedere esempi di progetti web semplici ma funzionali, studenti e junior web developer.

## Progetti inclusi:

### 1. SecretWalkGame | Test ITS 2024

#### Descrizione del gioco

Il giocatore deve scoprire il percorso corretto all'interno di una griglia, cliccando sulle caselle giuste per avanzare verso la fine. Ogni casella corretta permette di proseguire, mentre un clic su una casella sbagliata fa perdere tempo. L'obiettivo è completare il percorso segreto prima che il tempo scada.

Durata della prova: 2.5 ore

#### Richiesta

##### 1. Struttura HTML di base

- Creare un file HTML con un titolo tag h1 che descriva il gioco ("Gioco del Percorso Segreto").
- Creare una griglia di caselle (ad esempio, 5x5) all'interno di un contenitore <div> con id="game-container".
- Creare un elemento <p> con id="message" per visualizzare messaggi e stato del gioco.

##### 2. Stile CSS di base

- Stilizzare le caselle della griglla per renderle uniformi e cliccabill.
- Dare uno stile visivo alle caselle selezionate e a quelle errate.
- Dare uno sfondo chiaro alla pagina con uno stile minimal.

##### 3. Logipa Logica JavaScript di base

- Creare dinamicamente una griglia 5x5 e definire un percorso segreto casuale che il giocatore deve scoprire.
- Implementare la logica per verificare se una casella cliccata è corretta. Se corretta, la casella viene evidenziata; se errata, si perde tempo.
- Mostrare un messaggio di vittoria quando il percorso è completato o un messaggio di fine gioco quando il tempo scade.

##### Parte Finale

1. Indicatore di Stato

Mostrare il tempo rimanente durante il gioco (es. "Tempo rimasto: X secondi") e aggiornarlo dinamicamente.

2. Difficoltà Progressiva

Aumentare la difficoltà generando un percorso segreto più lungo a rimuovendo indizi visivi dopo un certo numero di clic.

3. Feedback Visivo

### 2. TaskManager | 20.12.2025

#### Lista tasks:
##### User:
- Aggiungere attività
- Visualizzare attività
- filtrare attività (tutti, completati, da fare);
- completare tasks
- eliminare tasks
. modificare task
##### Persistenza:
- Salva nel browser
##### Struttura dati:
- ID;
- title
- completed (bool)
- CreatedAT
##### Controlli:
- verifica aggiunta task, non vuote

#### Progettazione:
Abbiamo una struttura HTML che comprense: titolo, container per aggiungere la task (data, titolo), container task (con tutte le task), sezione strumenti per cambiare visualizzazione.

Ogni task dovrà avere 3 bottoni:
- Modifica;
- Elimina;
- Completato.

Ognuna di questi aspetti ha una sua funzione dedicata


## Note a margine:
I progetti sono tutti front-end, in quanto tali non richiedono installazione di alcun tipo ne tool esterni. Puoi utilizare il codice semplicemente scaricandolo.

