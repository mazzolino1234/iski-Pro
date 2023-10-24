# iski-Pro

--------

Il problema che mi sono posto nel pensare di realizzare questo programma è stato la necessità di voler registrare i vari dati caratterizzanti ogni discesa sciistica in modo tale da poter confrontare tali dati nel tempo e visualizzare l'andamento nel corso degli anni. Inoltre un altro problema, risolvibile con la stessa applicazione, è stato il caso valanghe: negli ultimi anni sempre più sciatori vengono travolti e spesso non vengono trovati in tempo. Analizzando il problema è dunque nata l'idea di questa applicazione che non solo permette la registrazione discese ma anche un servizio di geolocalizzazione GPS.

Requisiti dell'applicazione:

1. Registrazione delle discese:
   * Requisiti funzionali:
     * Utente:
       * L'applicazione deve fornire un'interfaccia utente chiara e intuitiva che consenta agli utenti di avviare e interrompere la registrazione delle discese senza complicazioni.
       * Gli utenti devono poter facilmente accedere alle proprie registrazioni delle discese e visualizzare i dati associati a ciascuna di esse.
     * Sistema:
       * Gli utenti devono poter avviare e interromprere la registrazione delle loro discese in maniera facile e funzionale.
       * L'applicazione dovrà, per ogni discesa, registrare dati come la velocità massima, la velocità media, il tempo e la lunghezza della discesa.
       * I dati delle discese registrate devono essere conservati in modo sicuro e accessibili agli utenti.
     
   * Requisiti non funzionali:
     * Sistema:
       * La registrazione delle discese deve essere precisa e affidabile.
       * Deve essere possibile visualizzare i dati delle discese in un formato leggibile.
      
   * Requisiti di dominio:
     * L'applicazione deve rispettare le leggi e i regolamenti relativi alla raccolta e alla conservazione dei dati personali.
     *  L'applicazione deve essere compatibile con i dispositivi GPS per la registrazione dei dati delle discese.
     
2. Geolocalizzatore GPS per Valanghe:
   * Requisiti funzionali:
     * Utente:
       * Deve permettere agli utenti di poter diramare una segnalazione di soccorso con la loro posizione esatta ai contatti di emergenza più vicini.
       *  L'applicazione deve avere un'interfaccia utente semplice e intuitiva per consentire agli utenti di segnalare una valanga e attivare il geolocalizzatore GPS senza difficoltà.
     * Sistema:
       * L'applicazione deve essere in grado di rilevare automaticamente un evento di valanga e attivare il geolocalizzatore GPS in risposta a questo evento.
              
   * Requisiti non funzionali:
     * Sistema:
       * La geolocalizzazione GPS deve essere accurata per fornire informazioni precise sulla posizione dell'utente.
       * Il ritardo tra la valanga e l'invio delle informazione ai servizi di soccorso deve essere il più breve possibile
       * L'applicazione dovrebbe essere progettata per funzionare anche in condizioni di scarsa connessione o in caso di assenza di segnale.

   * Requisiti di dominio:
     * L'applicazione deve saper utilizzazre mezzi specifici al fine di comprendere cambiamenti molto rapidi di velocità per verificare la presenza di una valanga.
     * La privacy dell'utente deve essere protetta e crittografata.
     * Si devono impedire accessi indesiderati da parte di utenti esterni.

3. Confronto con Amici e Utenti Globali:
   * Requisiti funzionali:
     * Utente:
       * Gli utenti devono poter facilmente aggiungere amici attraverso la ricerca di altri utenti tramite il nome utente in app.
       * Gli utenti devono poter confrontare i loro risultati con quelli dei propri amici aggiunti in App.
       * Una leaderbord globale deve mostrare gli utenti con risultati migliori in modo di potersi confrontare.
     * Sistema:
       * Gli utenti devono poter confrontare i propri risultati con quelli dei propri amici.
       * L'applicazione deve fornire una leaderboard globale che mostri gli utenti con i migliori risultati sportivi a livello mondiale.

   * Requisiti non funzionali:
     * Sistema:
       * Il sistema deve essere in grado di gestire un numero crescente di utenti e dei loro specifici risultati

   * Requisiti di dominio:
     * L'app deve rispettare le normative relative la privacy per quanto riguarda la condivisione dei risultati e l'accesso a dati con altri utenti.
     * L'applicazione deve gestire la presenza di utenti provenienti da diverse parti del mondo, considerando le differenze linguistiche.
     * L'applicazione dovrebbe consentire agli utenti di condividere i propri risultati sportivi su piattaforme di social media 

4. Modalità duella:
   * Requisiti funzionali:
     * Utente:
       * Gli utenti devono poter attivare la modalità duella quando sono nelle vicinanze di altri utenti che desiderano partecipare a una sfida.
       * L'utente deve aver la possibilità di invitare uno dei propri amici a partecipare ad una sfida.
       * Alla fine della corsa gli utenti devono poter fermare la registrazione della discesa.
     * Sistema:
       * L'app deve permettere agli utenti di avviare la modalità duella solo dopo aver verificato la vicinanza tra i dispositivi.
       * Durante la modalità duella, l'applicazione deve registrare i dati delle discese dei partecipanti, inclusi tempi, velocità e altri dati pertinenti.
       * L'applicazione deve essere in grado di confrontare i risultati delle discese dei partecipanti e determinare un vincitore in base a criteri specifici.

   * Requisiti non funzionali:
     * Sistema:
       * La registrazione delle discese e il confronto dei risultati devono essere altamente precisi per determinare un vincitore in modo corretto ed eguale.
       * La verifica della vicinanza tra i dispositivi deve essere sicura e priva di attacchi esterni.
       * Il confronto dei risultati e la determinazione del vincitore devono avvenire in modo rapido ed efficiente per fornire una risposta quasi istantanea agli utenti alla fine della sfida.
     * Utente:
       * Gli utenti devono ricevere notifiche immediate o avvisi quando un altro utente nelle vicinanze avvia una sfida duella.

   * Requisiti di dominio:
     * L'applicazione deve rispettare le leggi e i regolamenti sulla privacy dei dati degli utenti, in particolare quando si tratta di condivisione di dati tra dispositivi tramite connession o bluetooth.
     * La comunicazione tra dispositivi in modalità duella deve essere protetta da minacce alla sicurezza
     
5. Registrazione e autenticazione:
   * Requisiti funzionali:
     * Utente:
       * Gli utenti devono avere la possibilità di registrarsi e create un account personale.
       * Gli utenti devono poter accedere all'applicazione inserendo le proprie credenziali.
       * Dare la possibilità di reset-password in caso di dimenticanza.
       * Possibilità di attivare l'autenticazione a due fattori (2FA) in modo da aggiungere una sicurezza in più all'utente.
     * Sistema:
       * Il sistema deve consentire agli utenti di registrarsi creando un account e archiviare in modo sicuro le informazioni di registrazione.
       * Il sistema deve verificare le credenziali dell'utente (email e password) durante il processo di accesso.
       * Il sistema deve consentire agli utenti di reimpostare la propria password in modo sicuro e inviare conferme di reimpostazione via email.

   * Requisiti non funzionali:
     * Sistema:
       * L'applicazione deve garantire tempi di risposta rapidi durante la registrazione e l'autenticazione, evitando ritardi significativi.
       * L'applicazione deve essere accessibile e garantire la registrazione su diverse piattaforme e dispositivi.
     * Utente:
       * Il processo di registrazione e autenticazione deve essere intuitivo e facile da seguire per gli utenti.
       * L'applicazione dovrebbe fornire messaggi chiari e comprensibili agli utenti in caso di errori durante la registrazione o l'autenticazione.

   * Requisiti di dominio:
     * L'applicazione deve rispettare le norme della privacy riguardo l'accesso e la registrazione degli utenti.
     * L'applicazione deve essere in grado di garantire sicurezza dei dati d'accesso e in caso di accesso indesiderato avvertire l'utente tramite email.
     * L'applicazione deve rispettare le norme dell'autenticazione a 2FA.
     
6. Profilo:
   * Requisiti funzionali:
     * Utente:
       * L'utente deve poter visualizzare il proprio profilo e poter modificare i propri dati in base alle proprie esigenze.
       * Ogni utente deve avere un profilo personale che mostri le statistiche e discese in uno storico.
     * Sistema:
       * L'applicazione deve consentire agli utenti di visualizzare il proprio profilo utente, che includerà informazioni come nome, foto profilo, statistiche e storico delle discese.
       * Gli utenti devono poter modificare le informazioni del proprio profilo.
       
   * Requisiti non funzionali:
     * Sistema:
       * L'applicazione deve garantire tempi di risposta rapidi durante l'accesso e la modifica dei dati del profilo.
     * Utente:
       * La visualizzazione e la modifica del profilo devono essere intuitive e facili da utilizzare

   * Requisiti di dominio:
     * L'applicazione deve adottare misure di sicurezza per proteggere i dati contenuti nel profilo dell'utente.
     * L'applicazione deve rispettare le normative della privacy per il trattanto dei dati presenti nel profilo utente.
 
7. Gps e tracciamento:
   * Requisiti funzionali:
     * Utente:
       * Gli utenti devono essere in grado di concedere o revocare l'autorizzazione all'applicazione per accedere al sistema GPS del loro dispositivo.
     * Sistema:
       * L'applicazione deve essere in grado di accedere al sistema GPS del dispositivo dell'utente per registrare dati di posizione durante l'attività sportiva.

   * Requisiti non funzionali:
     * Sistema:
       * L'applicazione deve utilizzare il GPS in modo accurato per fornire informazioni precise sulla posizione dell'utente.
     * Utente:
       *  L'applicazione dovrebbe fornire feedback visivo sull'uso del GPS.

   * Requisiti di dominio:
     * L'applicazione deve rispettare le leggi e i regolamenti sulla privacy dei dati degli utenti riguardo all'uso del GPS e del tracciamento della posizione.

8. Condivisione:
   * Requisiti funzionali:
     * Utente:
       * Gli utenti devono poter selezionare specifici dati o risultati della discesa da condividere.
       * Gli utenti devono avere la possibilità di scegliere il metodo di condivisione desiderato.
       * Gli utenti devono poter selezionare a chi condividere i risultati selezionati.
     * Sistema:
       * L'applicazione deve consentire agli utenti di condividere i risultati di una singola discesa con altre persone o su piattaforme di social media.

   * Requisiti non funzionali:
     * Sistema:
       * L'applicazione deve consetire una condivisione dati in modo velcoe e affidabile.
     * Utente:
       *  La funzione di condivisione deve essere intuitiva e di facile utilizzo per gli utenti.

   * Requisiti di dominio:
     * L'applicazione deve rispettare la privacy dell'utente e richiedere l'autorizzazione dell'utente prima di condividere dati.

9. Modalità premium:
    * L'applicazione, tramite pagamento mensile, permetterà di avere accesso a maggiori funzionalità.
    9.1 Sistema di tracciamento migliorato.
    9.2 Mappa discesa:
       * Requisiti funzionali:
          * Utente:
            * La mappa deve permettere all'utente di muoversi e di visualizzare gli impianti scsiistici attivi e le piste aperte con relativa difficoltà di discesa.
            * Visualizzazione satellite per osservare la conformazione del territorio, le montagne e le cime intorno a me.
            * Visualizzare discesa effettuata su mappa.
    
       * Requisiti non funzionali:
         * Sistema:
           * Le informazioni sulla posizione delle piste e degli impianti sciistici sulla mappa devono essere accurate e aggiornate per garantire una corretta navigazione.
           * L'applicazione deve avere un collegamento con varie sedi sciistiche in modo da consetire la visualizzazione degli impianti attivi e delle piste aperte.
           *  L'applicazione dovrebbe consentire agli utenti di scaricare porzioni della mappa per un uso offline.
    
       * Requisiti di dominio:
         * L'applicazione deve utilizzare dati derivanti da tecnologie presenti negli impianti.
       
    * 9.3 Confronto automatico:
       * Tramite la modalità premium sarà possibile confrontare la discesa effettuata con una precedente in modo tale da avere un confronto reale.
    * 9.4 Modalità fuori pista:
        * Nella modalità premium deve essere presente la possibilità di scegliere la modalità fuori pista in modo da registrare le sciate su neve fresca.
    * 9.5 Report:
       * Nella versione premium sarà possibile creare e stampare (PDF) un report automatico dei record di sciate.
    * 9.6 Modalità duella ampliata:
       * Tramite la versione premium dell'applicazione il numero di contendenti nella modalità duella (PUNTO 4) sarà ampliato da 2 a 4 persone massime.
    * 9.1 Condivisione ampliata:
      * La modalità premium consente la condivisione di più risultati contemporanteamente.
     
10. Soddisfazione requisiti GDPR:
    * L'applicazione deve rispettare le norme europee, il regolamento generale sulla protezione dei dati (GDPR).
   

**CASI D'USO:**

1.1 L'utente, solo dopo aver effettuato l'accesso, avvia la registrazione discesa e al termine la interrompe.
<img src="http://yuml.me/diagram/scruffy/usecase/(note: N. 1.1{bg:beige}), [Utente]-(Accesso Utente), (Accesso Utente)>(Avviare registrazione discesa), (Avviare registrazione discesa)>(Termina registrazione discesa), [Sistema iSki]-(Calcolo registrazione discesa),(Registrazione velocità massima)^(Calcolo registrazione discesa), (Calcolo velocità media)^(Calcolo registrazione discesa), (Registrazione lunghezza percorso)^(Calcolo registrazione discesa), (Registrazione tempo impiegato)^(Calcolo registrazione discesa)" >

1.2 L'utente dopo aver effettuato l'accesso visualizza i dati delle discese precedenti.
<img src="http://yuml.me/diagram/scruffy/usecase/(note: N. 1.2{bg:beige}), [Utente]-(Accesso Utente), (Accesso Utente)-(Visualizza record discese)" >

2.1 L'utente deve poter diramare una segnalazione di soccorso con la sua esatta posizione ai contatti di emergenza più vicini, scelti dal sistema, in caso di valange anche senza aver efettuato l'accesso avendo però la posizione GPS attiva.
<img src="http://yuml.me/diagram/scruffy/usecase/(note: N. 2.1{bg:beige}), [Utente non autenticato]-(Invio segnalazione di soccorso), [Utente non autenticato]-(Attivazione GPS), [Utente non autenticato]-(Accesso Utente),  (Invio segnalazione di soccorso)>(Invio posizione GPS), (Invio posizione GPS)>(Determinazione posizione GPS), (Invio segnalazione di soccorso)>(Notifica confermo invio)">

2.2 Il sistema rileva in automatico la valanga e invia una segnalazione di soccorso.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 2.2{bg:beige}), [Sistema iSki] - (Monitora Sensori), (Monitora Sensori) < (Rileva Valanga), (Rileva Valanga) > (Attiva Geolocalizzatore GPS), (Rileva Valanga) > (Invia Segnalazione), (Invia Segnalazione)<(Fornisce Feedback)'>

3.1 L'utente accede e aggiunge un amico. ---------------------------------------------------
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 3.1{bg:beige}), [Utente]-(Accesso Utente), (Accesso Utente)-(Aggiungi Amico)'>

3.2 L'utente visualizza la leaderboard globale anche senza aver effettuato l'accesso.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 3.2{bg:beige}), [Utente]-(Accesso Utente),  [Utente]-(Mostra Leaderboard Globale)'>

3.3 L'utente effettua l'accesso aggiunge un amico o confronta i risultati dei prori amici aggiungi in ordine di punteggio.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 3.3{bg:beige}), [Utente]-(Accesso Utente), (Accesso Utente)<(Aggiungi Amico), (Accesso Utente)<(Confronta Risultati con Amici), (Confronta Risultati con Amici) > (Mostra Risultati Migliori)'>

4.1 L'utente dopo aver effettuato l'accesso avvia la modalità duella, il sitema deve verificare la vicinanza tra i due dispositivi. L'utente invita un proprio amico o uno sconosciuto alla sfida alla sfida. Al termine della discesa il sistema confronta in automatico i risultati e decreta un vincitore
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 4.1{bg:beige}), [Utente]- (Accesso Utente), (Accesso Utente) - (Attiva Modalità Duella), (Attiva Modalità Duella) < (Invita Amico a Duella), (Attiva Modalità Duella) < (Invita utente sconosciuto a Duella), [Sistema]-(Confronta Risultati Duella), (Invita Amico a Duella)>(Ferma Registrazione Discesa Duella), (Invita utente sconosciuto a Duella) > (Ferma Registrazione Discesa Duella), [Sistema]-(Verifica Vicinanza), (Confronta Risultati Duella) > (Determina Vincitore Duella)'>

5.1 Gli utenti possono registrarsi creando un account personale, il sistema salva le informazioni e invia conferma email.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 5.1{bg:beige}), [Utente]-(Registrazione), [Sistema]-(Salva dati registrazione), [Sistema]-(Invio email conferma registrazione)'>

5.2 L'utente tenta di accedere all'applicazione inserendo le credenziali.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 5.2{bg:beige}), [Utente]-(Accesso account), [Sistema]-(Verifica credenziali), (Verifica credenziali)<(Credenziali errate), (Verifica credenziali)<(Accesso consentito)'>

5.3 L'utente chiede un ripristino della password. ----------------------------------------------
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 5.3{bg:beige}), [Utente]-(Reset Password), (Reset Password) > (Specifica email di riferimento), [Sistema iSki]-(Invio istruzioni per reimpostare password)'>

5.4 L'utente tenta l'accesso all'account e in caso di credenziali errate può richiedere di reimpostare la password.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 5.4{bg:beige}), [Utente]-(Accesso account), [Utente] - (Reset Password), (Reset Password) > (Specifica Email di riferimento), [Sistema]-(Verifica credenziali), (Verifica credenziali)<(Credenziali errate), (Verifica credenziali)<(Accesso consentito), [Sistema]-(Invio istruzioni per reimpostare password)'>

5.5 L'utente attiva l'autenticazione a 2FA per avere maggiore sicurezza. ----------------------
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 5.5{bg:beige}), [Utente]-(Attivazione 2FA), [Sistema] - (Invio conferma tramite email specificata)'>

5.6 L'utente tenta l'accesso ad un account e in caso di accesso consentito autenticazione a 2FA verifica accesso tramite email.
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 5.6{bg:beige}), [Utente]-(Accesso account), [Utente] - (Reset Password), (Reset Password) > (Specifica Email di riferimento), [Sistema]-(Verifica credenziali), (Verifica credenziali)<(Credenziali errate), (Verifica credenziali)<(Accesso consentito), (Accesso consentito) > (Verifica 2FA tramite email), [Sistema]-(Invio istruzioni per reimpostare password)'>

6.1 L'utente dopo aver effettuato l'accesso visualizza il suo profilo utente
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 6.1{bg:beige}), [Utente] - (Accesso utente), (Accesso utente) - (Visualizzazione profilo)'>

6.2 L'utente dopo l'accesso ha la possibilità di modificare le proprie informazioni relative all'account (nome,cognome,data di nascita,email,nome utente,password,immagine profilo).
<img src='http://yuml.me/diagram/scruffy/usecase/(note: N. 6.2{bg:beige}), [Utente] - (Accesso utente), (Accesso utente) - (Modifica profilo), (Modifica profilo) < (Modifica nome), (Modifica profilo) < (Modifica cognome), (Modifica profilo) < (Modifica data di nascita), (Modifica profilo) < (Modifica email), (Modifica profilo) < (Modifica nome utente), (Modifica profilo) < (Modifica password), (Modifica profilo) < (Modifica immagine profilo)'>

6.3 L'utente dopo aver effettuato l'accesso visualizza le statistiche delle proprie discese.
<img src="http://yuml.me/diagram/scruffy/usecase/(note: N. 6.3{bg:beige}), [Utente]-(Accesso Utente), (Accesso Utente)-(Visualizza statistiche)" >

7.1 L'utente per poter utilizzare l'applicazione deve accettare il tracciamento GPS.
<img src="http://yuml.me/diagram/scruffy/usecase/(note: N. 7.1{bg:beige}), [Utente]-(Autorizzazione GPS), (Autorizzazione GPS) < (Accetta condizione), (Autorizzazione GPS) < (Rifiuta condizione), [Sistema]-(Invio notifica autorizzazione)" >

8.1 L'utente loggato condivide i propri risultati di una sola discesa selezionata.
<img src="http://yuml.me/diagram/scruffy/usecase/(note: N. 8.1{bg:beige}), [Utente]-(Accesso utente), (Accesso utente) - (Visualizzazione dati discese), (Visualizzazione dati discese) - (Selezione dati da condividere), (Selezione dati da condividere)<(Selezione piattaforma di condivisione),(Selezione dati da condividere)<(Selezione destinatario), [Sistema]-(Invio notifica condivisione effettuata)" >
      




