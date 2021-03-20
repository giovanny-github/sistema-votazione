# sistema-votazione
Sistema di votazione 5BA
È necessario un sistema per registrare e contare i voti per i candidati alle elezioni del consiglio scolastico. Il
sistema consentirà di eleggere un rappresentante da un gruppo di tutor. La scuola ha tra 28 e 35 studenti in
ogni gruppo di tutor, ci sono cinque gruppi nominati dal anno 7 fino al anno 11 e ci sono sei gruppi di tutor
in ogni gruppo annuale. I nomi dei gruppi di tutor sono il loro numero di gruppo seguito da una singola
lettera, ad es. 7A, 7B, ecc.

 Tutti gli studenti possono votare nel sistema.
 Ogni studente può votare una sola volta per un rappresentante dal loro gruppo di tutor nelle elezioni.

Scrivere e testare uno o più programmi per il sistema di votazione.

 Il programma o programmi devono includere messaggi appropriati per l&#39;immissione dei dati; i dati devono essere convalidati all&#39;ingresso.
 I messaggi di errore e altri output devono essere definiti in modo chiaro e comprensibile.
 Tutte le variabili, le costanti e altri identificatori devono avere nomi significativi.

Per creare il programma, dovrai completare queste tre attività. Ogni attività deve essere completamente testata.

Attività 1: Impostazione il sistema di voto per consentire a un gruppo di tutor di eleggere un rappresentante.

Scrivere un programma per:

• consentire al tutor di inserire il nome del gruppo di tutor.
• consentire al tutor di inserire il numero di studenti nel gruppo tutor.
• consentire al tutor di inserire il numero di candidati all&#39;elezione; massimo quattro candidati.
• consentire al tutor di inserire i nominativi dei candidati e di memorizzarli in una struttura dati adeguata.
• consentire a ogni studente di inserire il proprio voto o di astenersi.
• contare i voti per ogni candidato e le astensioni degli studenti.

Quando tutti gli studenti hanno votato, visualizzare il nome del gruppo di tutor, i voti per ogni candidato e il
nome del candidato che ha vinto le elezioni. Se c&#39;è un pareggio per il primo posto, mostrare tutti i candidati
con il maggior numero di voti pari.

Attività 2: Verificare che gli studenti votino una sola volta.

A ogni studente viene assegnato un numero di elettore univoco dal proprio insegnante. Estendere l&#39;attività 1 per ottenere quanto segue:

• Consentire agli studenti di inserire il proprio numero elettore univoco prima di esprimere il voto.

• Controlla se lo studente ha già votato:
  - in caso affermativo, fornire un messaggio adeguato e non consentire loro di votare.
  - in caso contrario, memorizzare il numero di elettori univoco, ma non il loro voto, 
  in una struttura dati adeguata e aggiungere il loro voto al candidato pertinente conteggio o astensione.

Attività 3: Visualizzazione delle statistiche e gestione di un pareggio.

Estendi l&#39;attività 2 per ottenere quanto segue:

 Calcola la percentuale dei voti che ogni candidato ha ricevuto dal numero dei voti espressi, escluse le astensioni.
 Visualizzare il nome di ogni candidato, il numero di voti e la percentuale di voti che hanno ottenuto dal numero dei voti espressi, escluse le astensioni.

 Visualizzare il numero totale di voti espressi nelle elezioni e il numero di astensioni.
 In caso di parità, consentire di ripetere immediatamente l&#39;elezione, con i soli candidati in parità come candidati e tutti gli studenti del gruppo tutor votano nuovamente.
