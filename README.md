/*CONSEGNA*/

Progetto HTML/VueJS
 Repo : proj-html-vuejs
 Cosa fare
 Riprodurre il layout proposto solo in versione Desktop
 Tecnologie da utilizzare
 ● HTML
 ● CSS/Scss
 ● VueJs / Vite
 Requisiti tecnici minimi
 Creare un progetto con Vite, strutturando il layout in almeno 3 macro-componenti:
 Header, Main e Footer.
 Popolare le voci di menù di Header e Footer dinamicamente, tramite delle props, creando
 una struttura dati idonea.
 Deadline
 Lunedì 02 settembre 2024 ore 20
 Supporto
 Venerdì 30 agosto (mattina e pomeriggio) potrete prenotare uno slot di 15 minuti (1 solo slot
 su tutta la giornata) con un insegnante, per poter porre domande di
 approfondimento/chiarimento sul progetto (non domande tecniche sul codice, solo
 organizzative).
 La prenotazione dovrà avvenire almeno 30 minuti prima dell’orario selezionato, è
 fondamentale che prima dell’appuntamento abbiate pushato tutto il codice e preparato le
 vostre domande: è importante arrivare con le idee chiare per poter ricevere il massimo
 supporto.
 Ricordate: avete 15 minuti a testa, potrete chiedere un numero limitato di consigli.
 Non sarà possibile invece aprire le consuete richieste Hotwell.
 Inoltre, non avrete supporto il primo e ultimo giorno di progetto (il giorno della
 deadline).
Presentazione dei progetti
 I lavori saranno presentati Martedì 3 settembre e Mercoledì 4 settembre personalmente con
 l’insegnante 1-to-1; sarà indispensabile quindi prenotare uno slot per poter parlare con un
 insegnante.
 Non si tratterà del classico Feedback, ma dovrete presentare il vostro progetto.
 Consigli per lo svolgimento del progetto
 Organizzazione del lavoro
 Analizzate attentamente il layout prima di partire, utilizzate sempre il metodo dei commenti
 per identificare le aree del layout e individuare elementi comuni riutilizzabili, che potrebbero
 anche diventare dei componenti.
 Una volta analizzato il progetto, create una tabella di marcia e almeno una volta al giorno
 controllate di essere in linea con la vostra programmazione.
 Meglio un layout con header,footer e 3 o 4 sezioni ben fatte, che un layout completo ma mal
 strutturato. Tenete presente comunque che l’ideale è sempre consegnare il lavoro completo.
 Procedete poi con il layout sezione per sezione raggiungendo un livello di dettaglio il più
 simile a quello proposto dal designer.
 Ricordate: il designer ha lavorato duramente per immaginare il layout e ha scelto certe
 soluzioni per ottime motivazioni, il nostro compito è rendere reale la sua creatività!
 GIT
 Create un primo commit con lo scaffolding, un secondo con la macrostruttura e così via,
 all’aggiunta di ogni piccolo frammento.
 Committare e pushare con regolarità vi consentirà:
 1. di non perdere versioni del vostro lavoro. Il vostro datore di lavoro alla deadline
 pretende di ricevere il lavoro commissionato, nella vita lavorativa non è possibile dire
 “ho perso il lavoro svolto”;
 2. di ricevere una migliore assistenza e valutazione da parte dei vostri insegnanti che
 controlleranno i vostri lavori durante tutto lo svolgimento del progetto.
 Come affrontare il lavoro
 Affrontate il progetto a mente serena allontanando ogni ansia, divertitevi mentre mettete in
 pratica i concetti imparati fino ad ora, focalizzate il vero obiettivo: domani questa sarà la
 vostra giornata tipo.

/*SOLUZIONE/SCALETTA*/

- Come rischiesto dalla consegna eseguo per prima cosa lo scaffolding per ottenere la struttura base del progetto;
- instalo sia sass che boostrap, in modo tale quante più opzioni disponibili per "decorare" l'intera impaginazione del progetto;
- modifico la strutture base di vue+vite per avvicinarmi alle rischiesta dell'immagine di mockup, iniziando dalla sezione header;
- imposto un impaginazione preliminare per AppMain.vue;
- imposto un impaginazione preliminare per AppFooter.vue;
- aggiungo la cartella img nella cartella assets;
- continuo a modificare AppHeader.vue;
    - aggiungo nel file index.html il link che mi permette di usare le icone da Fontawesome;
    - continuo a modficare la barra di navigazione di AppHeader, ma non risco ad impostare i colori come si deve, forse a causa di una sorta interferenza da parte delle classi di boostrap;
    - modifico nuovamente l'aspetto della navbar di AppHeader, stavolta prendendo in prestito una struttura navbar da w3school: il risultato è insoddisfacente...
- procedo ad impaginare AppFooter.vue:
    - dal momento che in AppHeader non sono attualmente soddisfatto dell'impaginazione, in AppFooter voglio impostare delle classi css personalizzaten nel tentativo di ottenere un risultato estetico migliore;
- procedo con l'impaginazione di AppMain.vue;
- procedo col popolare dinamicamente AppHeader e AppFooter tramite props;