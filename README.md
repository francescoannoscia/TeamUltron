# Gioco dell'impiccato
Questa applicazione simula il gioco dell'impiccato.
Come linguaggio di programmazione è stato utilizzato il Python, mentre per la scrittura del codice è stata utilizzata l'applicazione web open-source Jupyter Notebook.

# Indice
1. **main.ipynb**: programma per giocare al gioco dell'impiccato
2. **randomWord_function.ipynb**: funzione per la generazione casuale della parola da indovinare (Francesco Annoscia)
3. **askToPlay_function.ipynb**: funzione per l'avvio del gioco (Emanuele Colasanto)
4. **chooseDifficulty_function.ipynb**: funzione per la scelta della difficoltà di gioco (Emanuele Colasanto)
5. **handleError_function.ipynb**: funzione per la gestione degli errori (Caterina Pappadà)
6. **checkLetter_function.ipynb**: funzione per la gestione delle varianti accentate delle vocali (Francesco Annoscia)
7. **checkSingleLetter.ipynb**: funzione per la verifica della presenza della lettera nella parola da indovinare (Caterina Pappadà)
8. **checkFullWord_function.ipynb**: funzione per la verifica della parola inserita con la parola da indovinare (Caterina Pappadà)
9. **checkInput_function.ipynb**: funzione che combina le funzioni 5-8 (Caterina Pappadà)
10. **gameOutput.ipynb**: funzione per la gestione della grafica del gioco (Mario Nacci)
11. **askPlayAgain_function.ipynb**: funzione per la gestione del riavvio del gioco (Emanuele Colasanto)

# Utilizzo
Scaricare il file "main.ipynb" e aprirlo su Jupyter Notebook. Eseguire il codice presente in tutte le celle del Jupyter Notebook (caricamento delle funzioni), creare una nuova cella, scrivere semplicemente 'main()' ed eseguirla per avviare il gioco.

# Ringraziamenti
Come "dizionari" per la generazione casuale di parole, sono stati utilizzati due file di testo (elenchi di parole) depositati sul repository GitHub "parole italiane" (https://github.com/napolux/paroleitaliane) di Francesco Napoletano (https://github.com/napolux).

La realizzazione dell'applicazione è il risultato di un lavoro di gruppo al quale hanno partecipato:
- Caterina Pappadà (https://github.com/CaterinaPG) ed Emanuele Colasanto (https://github.com/colasantoemanuele-cloud) per la scrittura delle funzioni per la gestione e il controllo dei vari input dell'utente e per il fulcro algoritmico del gioco
- Mario Nacci (https://github.com/Rioma305) per la scrittura delle funzioni per la gestione della grafica
