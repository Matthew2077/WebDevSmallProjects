# WebDevSmallProjects
A collection of small sities of all kind. 

## Test ITS 2024 | SecretWalkGame:

Prova Teorico pratica web gruppo 1: Gioco del Percorso Segreto

### Descrizione del gioco

Il giocatore deve scoprire il percorso corretto all'interno di una griglia, cliccando sulle caselle giuste per avanzare verso la fine. Ogni casella corretta permette di proseguire, mentre un clic su una casella sbagliata fa perdere tempo. L'obiettivo è completare il percorso segreto prima che il tempo scada.

Durata della prova: 2.5 ore

### Richiesta

#### 1. Struttura HTML di base

- Creare un file HTML con un titolo tag h1 che descriva il gioco ("Gioco del Percorso Segreto").
- Creare una griglia di caselle (ad esempio, 5x5) all'interno di un contenitore <div> con id="game-container".
- Creare un elemento <p> con id="message" per visualizzare messaggi e stato del gioco.

#### 2. Stile CSS di base

- Stilizzare le caselle della griglla per renderle uniformi e cliccabill.
- Dare uno stile visivo alle caselle selezionate e a quelle errate.
- Dare uno sfondo chiaro alla pagina con uno stile minimal.

#### 3. Logipa Logica JavaScript di base

- Creare dinamicamente una griglia 5x5 e definire un percorso segreto casuale che il giocatore deve scoprire.
- Implementare la logica per verificare se una casella cliccata è corretta. Se corretta, la casella viene evidenziata; se errata, si perde tempo.
- Mostrare un messaggio di vittoria quando il percorso è completato o un messaggio di fine gioco quando il tempo scade.

#### Parte Finale

1. Indicatore di Stato

Mostrare il tempo rimanente durante il gioco (es. "Tempo rimasto: X secondi") e aggiornarlo dinamicamente.

2. Difficoltà Progressiva

Aumentare la difficoltà generando un percorso segreto più lungo a rimuovendo indizi visivi dopo un certo numero di clic.

3. Feedback Visivo
