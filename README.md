## ⚽ Football Team Cards Project
Benvenuti al progetto Football Team Cards! Questo progetto è stato creato per imparare i metodi moderni di JavaScript costruendo delle schede di giocatori di una squadra di calcio. 🌟

Questo è il nono esercizio del corso di freecodecamp.org (https://www.freecodecamp.org/), nello specifico https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures-v8/#learn-modern-javascript-methods-by-building-football-team-cards

Lezione: Learn Modern JavaScript Methods by Building Football Teams Cards

## 📝 Descrizione
Questo progetto utilizza HTML, CSS e JavaScript per visualizzare le informazioni sui giocatori di una squadra di calcio. Puoi filtrare i giocatori per posizione o per soprannome.

## 📁 Struttura del Progetto
index.html: La struttura di base del progetto.
styles.css: Gli stili utilizzati per rendere il progetto visivamente accattivante.
script.js: Lo script JavaScript che gestisce la logica del progetto.

## 📜 Studio JS
In questo esercizio ho imparato diversi metodi JS:

 - **Object.freeze(nomeOggetto)**: congela l'oggetto, non permettendo modifiche di nessun tipo.
 - **Object Destructuring Syntax**: permette di estrarre proprietà da oggetti e assegnarle a variabili in modo più conciso e leggibile. Esempio:
     - const { sport, team, year, players } = myFavoriteFootballTeam; **--> è come scrivere** const sport = myFavoriteFootballTeam.sport; ecc.
     - const { coachName } = myFavoriteFootballTeam.headCoach; **--> è come scrivere** const coachName = myFavoriteFootballTeam.headCoach.coachName;
 - **.map()**: è un metodo degli array che crea un nuovo array popolato con i risultati della chiamata a una funzione fornita su ogni elemento dell'array chiamante. Il metodo .map() è estremamente utile per trasformare gli array, consentendo di applicare una funzione a ciascun elemento e restituendo un nuovo array con i risultati di queste applicazioni. Nell'esercizio viene utilizzato applicando anche il metodo .join() per unire tutte le stringhe in una unica.
 - **ciclo switch**: è una struttura di controllo del flusso che permette di eseguire diverse azioni basate sul valore di un'espressione.
     - switch (espressione) {
          case valore1:
            // Codice da eseguire se espressione === valore1
            break;
          case valore2:
            // Codice da eseguire se espressione === valore2
            break;
          // Aggiungi altri case come necessari
          default:
            // Codice da eseguire se nessun case corrisponde
        }



## 📜 Licenza
Questo progetto è rilasciato sotto la licenza MIT. Vedi il file LICENSE per maggiori dettagli.
