Progetto realizzato per la materia "Tecniche Per La Gestione Degli Open Data", (Laurea Triennale in Informatica, docente: prof. Davide Taibi). L'obiettivo principale del progetto è, a partire da tre dataset in formato CSV (Comma Separated Value, 3 stelle), raffinare e combinare tra loro questi con lo scopo di creare uno strato semantico provvisto di interlinking alla risorsa DBPedia, trasformando quindi i dati a 5 stelle. Precisamente le fasi saranno:

    Selezione dei dataset e relative licenze
    Elaborazione dei dataset: lettura, pulizia, merge
    Ontologia
    Passaggio a 5 stelle
    Data visualization
    Sentiment Analysis

Problema: Si suppone che un utente, mentre si trovava in vacanza a Firenze, abbia ricevuto una notifica di cancellazione del volo, il tutto dopo aver fatto check-out nell'albergo in cui alloggiava. Deve quindi cercare un nuovo albergo. Si suppone inoltre che voglia alloggiare in una struttura ricettiva che si trovi entro un raggio di x chilometri dalla sua posizione. Interrogherà quindi il servizio affinché possa avere una lista delle possibili strutture ricettive.
L'utente sceglie di effettuare una valutazione delle strutture basandosi sul minor rapporto metri/stelle. Dopo aver alloggiato, dovrà decidere dove cenare. Sceglierà il ristorante allo stesso modo, data la sua posizione.

Fase di Sentiment Analysis: supponiamo che il cliente, una volta dopo aver alloggiato in albergo, voglia scegliere tra i tre ristoranti più vicini alla struttura in cui si trova, questa volta fara ciò basandosi sulla sentiment analysis (a partire dalle API di Dandelion) delle recensioni dei locali.
