# FIXIT
software engineering project

Proposta di progetto
Ingegneria del Software & Interazione Uomo Macchina

Lo scopo del progetto è la realizzazione di un Software sperimentale dedicato al ripiegamento proteico e alla progettazione di nuove 
proteine, denominato Fixit1. L'idea di fondo è di realizzare un puzzle-game, tramite il quale l'utente è chiamato a presentare una 
soluzione al ripiegamento proteico attraverso la manipolazione della macro molecola in un ambiente grafico tridimensionale2 (A1).  
L'utente può sfruttare molteplici strumenti, al fine di trovare una struttura a più bassa energia, ovvero di più probabile entità.
Quando il giocatore partecipa ad un puzzle, il software calcola un punteggio (score), basato su come è stata piegata la proteina o
sulla struttura della stessa.  I punteggi permettono di creare due classifiche: una per il puzzle e una globale degli utenti. 
L'uso dei dati raccolti sarà poi immagazzinato in un' apposito DB3(A2) , accessibile ai ricercatori al fine di migliorare la 
qualità delle previsioni nella strutturazione proteica.

A1. GUI 3D
L'interfaccia del gioco risulterà intuitiva e di facile utilizzo anche ad un pubblico inesperto,
dando l'opportunità di usare un sistema drag and drop già familiare all'utenza media, che simuli movimenti naturali. 
(Esempio di struttura avanzata di proteina e piegamento)

L'applicazione garantirà un tempo di risposta adeguato e sarà multi piattaforma (Windows, Mac OS, Linux). Sarà inoltre facilmente 
espandibile ed adattabile alle future esigenze di sviluppo, per questo interamente strutturata in linguaggio Oracle Java (1.7).
 
A2. DB
Il database sarà interrogabile tramite standard ODBC4  da parte di attori ricercatori e attori utenti:
da qui i primi potranno estrarre dati per lo studio di algoritmi performanti da usare in progetti paralleli come Rosetta@home5; 
mentre i secondi potranno aggiornare i propri punteggi.
Il tutto sarà gestito dal DBMS.








