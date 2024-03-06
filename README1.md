# W(s)C: Waste Sorter Classificator
## Progetto per lo sviluppo di una web application per la raccolta differenziata. 
L'idea consiste nell'avere un sito con una fotocamera che, inquadrato un'oggetto, invia le informazioni all'utente su dove debba essere differenziato. 
(Opzionale: riconoscimento di testo tramite immagini e successiva analisi con NLP per capire il nome del prodotto così sapere il tipo di materiale) 
Attenzione: per i vari tipi di plastica si può inquadrare anche il codice per identificare meglio la tipologia di plastica.

## Implementazione:
### Backend:
Linguaggio: Python <p>
Database:  https://github.com/collindching/waste-sorter/blob/master/Waste%20sorter.ipynb <p>
File:
- [x] `main.py`: file principale per avviare il programma:
	- [x] avvio camera
	- [x] riconoscimento immagine e scatto (bottone che scatta e prende la foto)
	- [x] invio immagine alla rete neurale
	- [x] stampa del risultato
- [ ] `utils.py`: file che contiene tutte le funzioni di supporto e di confronto con le immaingi, cerchiamo di tenere i vari jobs più divisi possibili così da poter eseguire una modifica eventuale in futuro più veloce

Nel main ci sarà la funzione che una volta scattata la foto prenderà quell'immagine e la invierà alla funzione di confronto, la quale restituirà il risultato migliore tra le varie directory. <p>







