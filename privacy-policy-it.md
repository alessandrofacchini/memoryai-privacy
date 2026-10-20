# Informativa sulla Privacy di MemoryAI

**Data di entrata in vigore: 10/03/2026**
**Ultimo aggiornamento: 20/10/2026**

Grazie per aver scelto MemoryAI! La presente Informativa sulla Privacy spiega come gestiamo le tue informazioni quando utilizzi la nostra applicazione mobile. La tua privacy è la nostra massima priorità e ci impegniamo a proteggerla. Questa informativa è conforme al Regolamento Generale sulla Protezione dei Dati (GDPR) e alla normativa italiana in materia di protezione dei dati personali.

Questa informativa è disponibile in [Inglese](index.md) e [Italiano](privacy-policy-it.md).

---

## In breve

MemoryAI è un'applicazione privata che funziona principalmente offline. Tutti i tuoi dati — incluse note, registrazioni vocali, immagini e interazioni con l'IA — sono archiviati localmente sul tuo dispositivo per impostazione predefinita. **Non disponiamo di alcuna infrastruttura backend che riceva le tue informazioni.** L'attività di rete dell'app è limitata a: download di file dei modelli IA da repository di terze parti (ad es. HuggingFace); se scegli di abilitarlo, backup dei tuoi dati nel tuo spazio di archiviazione cloud personale (Google Drive su Android, iCloud su iOS); se accetti la richiesta "Notifiche" mostrata nell'app, registrazione presso il nostro fornitore di notifiche (OneSignal), con un token push del dispositivo se consenti anche le notifiche, per consentirci di inviare messaggi al tuo dispositivo; invio di statistiche di utilizzo a TelemetryDeck e di segnalazioni di crash a Sentry, nessuna delle quali contiene i contenuti che crei; i dati tecnici di utilizzo che Google ML Kit, la libreria che riconosce il testo nelle immagini, invia a Google (mai le tue immagini né il testo riconosciuto); su Android, verifica presso Google Play della disponibilità di aggiornamenti dell'app; e, solo sulle versioni Android precedenti alla 1.0.55 e solo con il tuo consenso, invio di dati di utilizzo a Google Analytics for Firebase.

---

## 1. Titolare del trattamento

Il titolare del trattamento dei dati per l'app MemoryAI è:

**Facchinits**
Email: postmaster@facchinits.it

Segnalazioni e Richieste: [github.com/alessandrofacchini/memoryai-feedback](https://github.com/alessandrofacchini/memoryai-feedback/issues)

Se ti trovi nell'Unione Europea, puoi anche contattare la tua autorità di controllo locale per la protezione dei dati. Per gli utenti in Italia, si tratta del **Garante per la protezione dei dati personali** ([www.garanteprivacy.it](https://www.garanteprivacy.it)).

---

## 2. Base giuridica del trattamento

Trattiamo i tuoi dati sulla base dei seguenti fondamenti giuridici ai sensi dell'Articolo 6 del GDPR:

- **Il tuo consenso (Art. 6(1)(a)):** Quando utilizzi la nostra app e concedi le autorizzazioni del dispositivo (microfono, fotocamera, archiviazione), acconsenti al trattamento locale dei tuoi dati come descritto nella presente informativa. Se scegli di abilitare la funzione di backup su cloud, acconsenti esplicitamente al caricamento dei tuoi dati nel tuo account di archiviazione cloud personale. Se accetti la richiesta "Notifiche" mostrata nell'app, acconsenti al trattamento da parte del nostro fornitore di notifiche, OneSignal, descritto nelle Sezioni 3, 5 e 9. Sulle versioni Android precedenti alla 1.0.55, accettare la precedente richiesta "Privacy e Notifiche" significa acconsentire anche alla raccolta di dati di utilizzo da parte di Google Analytics for Firebase descritta nelle Sezioni 3 e 9. La Sezione 10 spiega come revocare questo consenso.
- **Necessità contrattuale (Art. 6(1)(b)):** Il trattamento è necessario per fornire le funzionalità principali dell'app, come la RAG, le interazioni con i modelli di IA locali e la trascrizione vocale.

---

## 3. Informazioni che trattiamo

MemoryAI **non** raccoglie, trasmette o archivia alcun dato personale o contenuto creato dall'utente sui **nostri** server. Tutti i dati che crei e utilizzi all'interno dell'app vengono elaborati e archiviati **sul tuo dispositivo** per impostazione predefinita. Questi includono:

- **Testi e documenti:** Qualsiasi testo digitato o documento importato per la funzionalità RAG (Retrieval-Augmented Generation).
- **Input vocali:** Registrazioni vocali create per la trascrizione o per interagire con l'IA. Vengono elaborate interamente sul dispositivo.
- **Immagini:** Immagini selezionate dal dispositivo per il riconoscimento del testo o per essere incluse nelle note.
- **Interazioni con i modelli IA:** Le conversazioni e le interazioni con i modelli linguistici di grandi dimensioni (LLM) locali, che funzionano interamente sul dispositivo.
- **File adattatori LoRA:** File adattatori LoRA personalizzati (ad es. formato .gguf) che importi nell'archiviazione locale dell'app per personalizzare il comportamento del modello IA.
- **Dati di backup:** Se abiliti la funzione di backup su cloud, l'app crea una copia dei tuoi dati e la carica nel tuo account di archiviazione cloud personale (Google Drive su Android, iCloud su iOS). Vedi Sezione 5 per i dettagli.
- **Dati per le notifiche push (opzionale):** Se accetti la richiesta "Notifiche" mostrata nell'app, l'app si registra presso il nostro fornitore di notifiche, OneSignal; se consenti anche le notifiche, un token push del dispositivo generato da Apple (APNs) o Google (FCM) viene condiviso con OneSignal per consentire la consegna dei messaggi al tuo dispositivo. OneSignal riceve inoltre un identificativo casuale che l'app genera al primo avvio (lo stesso utilizzato per le statistiche di utilizzo, descritto più avanti, ma inviato a OneSignal così com'è e non sotto forma di hash), alcuni tag con la versione dell'app (app_version) e il nome dell'ultimo modello IA che hai caricato (preferred_model), e la registrazione di due traguardi: la prima chat completata e il primo documento importato (mai il loro contenuto). OneSignal può inoltre ricevere metadati tecnici limitati come la versione dell'app, la versione della piattaforma/sistema operativo, la preferenza linguistica, il paese (derivato dall'indirizzo IP al momento della registrazione) e il fuso orario. Questi dati sono utilizzati per inviarti notifiche pertinenti e localizzate e per misurarne l'efficacia. Vedi Sezioni 5 e 9 per i dettagli.
- **Preferenze dell'app:** Impostazioni e preferenze configurate all'interno dell'app (ad es. selezione della lingua, tema).

Raccogliamo **dati di utilizzo minimi** tramite TelemetryDeck, un servizio di analisi rispettoso della privacy con sede nell'Unione Europea (Germania). Queste analisi ci aiutano a capire come viene utilizzata l'app e a migliorarla. I dati sono associati a un **identificativo casuale** che l'app genera al primo avvio e conserva sul tuo dispositivo; TelemetryDeck ne riceve solo un **hash non reversibile**, mai l'identificativo stesso. L'identificativo non è collegato al tuo nome, al tuo account, al tuo numero di telefono né agli identificativi hardware del tuo dispositivo. I dati non contengono indirizzi IP e non contengono mai ciò che scrivi, dici o importi. Esempi di segnali includono: "l'app è stata aperta", "un modello è stato caricato", "un messaggio è stato inviato" (mai il contenuto del messaggio). Per maggiori dettagli, vedi Sezione 9. Puoi saperne di più sulle pratiche di privacy di TelemetryDeck su [telemetrydeck.com/privacy](https://telemetrydeck.com/privacy/).

Utilizziamo inoltre **Sentry** per la diagnostica di crash ed errori. Sentry viene usato solo per aiutarci a rilevare, analizzare e correggere i malfunzionamenti dell'app; **non** viene usato per analisi di prodotto. Configuriamo Sentry per ridurre al minimo i dati inviati, disattivare la raccolta predefinita di informazioni personali identificabili e filtrare o oscurare i payload diagnostici prima dell'invio. **Non** inviamo intenzionalmente a Sentry i tuoi prompt, messaggi, contenuti dei documenti, contenuti dei backup o token di autenticazione. Nessun contenuto creato dall'utente viene inviato a server di proprietà o gestiti da MemoryAI, salvo quando scegli esplicitamente di eseguire un backup nel tuo archivio cloud personale o di condividere contenuti tramite la funzione di Condivisione (vedi Sezione 5).

**Solo sulle versioni Android precedenti alla 1.0.55**, se hai accettato la precedente richiesta "Privacy e Notifiche" mostrata nell'app, utilizziamo inoltre **Google Analytics for Firebase**, fornito da Google. Quelle versioni disattivano la raccolta all'avvio e la attivano solo se hai accettato. Quando accetti, l'app attiva la raccolta e, tramite Google Consent Mode, comunica a Google che hai concesso il consenso per l'archiviazione dei dati di analisi, l'archiviazione dei dati pubblicitari, i dati utente per la pubblicità e la personalizzazione degli annunci (i segnali analytics_storage, ad_storage, ad_user_data e ad_personalization). L'app registra due eventi — il completamento della configurazione iniziale e l'invio di un messaggio (solo il primo messaggio di ogni sessione, mai il suo contenuto) — e la lingua dell'app, oltre agli eventi che Firebase registra automaticamente. Utilizziamo questi dati per misurare l'efficacia delle nostre campagne pubblicitarie su Google Ads (monitoraggio delle conversioni). **La versione 1.0.55 e le successive non contengono Google Analytics for Firebase** e non utilizzano l'identificativo pubblicitario: aggiornare l'app interrompe questa raccolta. Google Analytics for Firebase non viene utilizzato su iOS. Vedi Sezioni 5, 7, 8 e 9 per i dettagli.

---

## 4. Autorizzazioni del dispositivo

Per fornire le sue funzionalità principali, MemoryAI può richiedere le seguenti autorizzazioni del dispositivo:

| Autorizzazione | Finalità |
|---|---|
| **Microfono** | Per registrare input vocali per la trascrizione e le interazioni con l'IA. |
| **Fotocamera** | Per acquisire immagini per il riconoscimento del testo e la creazione di note. |
| **Archiviazione / Foto** | Per accedere alle immagini dalla galleria, per importare file adattatori LoRA e per archiviare i dati dell'app localmente. |
| **Rete / Internet** | Per scaricare file dei modelli IA da repository di terze parti (ad es. HuggingFace); se abilitato, per eseguire il backup e il ripristino dei dati tramite archiviazione cloud; per inviare le statistiche di utilizzo, le segnalazioni di crash e i dati per le notifiche descritti nella Sezione 3; e per i dati tecnici che Google ML Kit invia a Google (Sezione 9). Nessun dato viene inviato a server di MemoryAI. |
| **Account Google (Android)** | Richiesto solo se abiliti la funzione di backup su Google Drive. Utilizzato per autenticarsi con il tuo account Google e accedere al tuo spazio Google Drive. |
| **Notifiche** | Richiesta solo se scegli di abilitare le notifiche push. Utilizzata dal sistema operativo per visualizzare i messaggi che inviamo tramite il nostro fornitore di notifiche (OneSignal). Puoi revocare questa autorizzazione in qualsiasi momento senza compromettere alcuna altra funzionalità dell'app. |

Puoi revocare qualsiasi di queste autorizzazioni in qualsiasi momento tramite le impostazioni di sistema del tuo dispositivo. La revoca di un'autorizzazione potrebbe disabilitare la funzionalità corrispondente, ma non influenzerà il resto dell'app.

---

## 5. Come utilizziamo le tue informazioni

Tutta l'elaborazione IA dei tuoi contenuti avviene **localmente sul tuo dispositivo**. Utilizziamo i dati che fornisci per:

- Abilitare le funzionalità principali dell'app, come la creazione di note, la RAG e l'interazione con i modelli IA locali.
- Trascrivere le tue registrazioni vocali sul dispositivo.
- Riconoscere ed estrarre testo dalle tue immagini sul dispositivo.

I contenuti che crei nell'app non vengono mai utilizzati per pubblicità o profilazione. Le statistiche di utilizzo e le segnalazioni di crash descritte nella Sezione 3 servono solo a migliorare l'app. Sulle versioni Android precedenti alla 1.0.55, se hai dato il tuo consenso, Google Analytics for Firebase viene inoltre utilizzato per misurare l'efficacia delle nostre campagne pubblicitarie.

### Backup e ripristino su cloud

MemoryAI offre una funzione **opzionale** di backup e ripristino su cloud per aiutarti a proteggere i tuoi dati o trasferirli tra dispositivi:

- **Su Android**, i tuoi dati vengono salvati nel tuo account personale **Google Drive**.
- **Su iOS**, i tuoi dati vengono salvati nel tuo account personale **iCloud**.

Questa funzione **non è abilitata per impostazione predefinita** — devi scegliere esplicitamente di creare un backup o ripristinarne uno. Quando avvii un backup, una copia dei dati dell'app (note, conversazioni, preferenze e contenuti correlati) viene caricata nel tuo account di archiviazione cloud personale. MemoryAI non ha accesso al tuo account di archiviazione cloud e non può leggere, modificare o eliminare i tuoi backup. I dati salvati sono soggetti alle informative sulla privacy e alle pratiche di sicurezza di Google o Apple, rispettivamente.

Puoi eliminare i tuoi backup su cloud in qualsiasi momento direttamente tramite Google Drive o iCloud.

### Condivisione ed esportazione

Quando utilizzi la **funzione di Condivisione/Esportazione**, i dati delle tue conversazioni vengono passati alla funzionalità di condivisione nativa del tuo dispositivo (tramite il foglio di condivisione del sistema operativo). Da lì, i dati possono essere inviati ad altre app o servizi da te scelti. MemoryAI non ha alcun controllo su come tali app di terze parti gestiscono i tuoi dati.

### Notifiche push

MemoryAI offre notifiche push **opzionali** per informarti su nuove funzionalità, aggiornamenti dei modelli e miglioramenti dell'app. Questa funzione **non è abilitata per impostazione predefinita** — si attiva solo se accetti la richiesta "Notifiche" mostrata nell'app, e i messaggi vengono mostrati solo se consenti anche le notifiche quando il sistema operativo te lo chiede.

Utilizziamo **OneSignal** (OneSignal, Inc., con sede negli Stati Uniti) come fornitore per la consegna delle notifiche. Quando accetti la richiesta:

- Se consenti le notifiche, un token push del dispositivo emesso da Apple Push Notification service (APNs) su iOS o da Firebase Cloud Messaging (FCM) su Android viene condiviso con OneSignal affinché i messaggi possano essere instradati al tuo dispositivo.
- Condividiamo un identificativo casuale generato dall'app e alcuni tag con la versione dell'app (app_version) e il nome dell'ultimo modello IA che hai caricato (preferred_model), e possiamo condividere metadati tecnici limitati — come la versione dell'app, la versione della piattaforma/sistema operativo, la preferenza linguistica, il paese (derivato dall'indirizzo IP al momento della registrazione) e il fuso orario — per poterti inviare notifiche pertinenti e localizzate. Segnaliamo inoltre a OneSignal quando completi la prima chat e importi il primo documento (mai il loro contenuto), per misurare l'efficacia delle nostre notifiche.
- **Non** condividiamo con OneSignal alcuna nota, conversazione, registrazione vocale, immagine, documento, contenuto di backup o qualsiasi altro contenuto da te creato all'interno dell'app. L'identificativo è casuale e non è legato al tuo nome, al tuo account, al tuo numero di telefono né agli identificativi hardware, ma è un identificativo persistente dell'app: è lo stesso utilizzato per le statistiche di utilizzo (vedi Sezione 3) e OneSignal lo riceve così com'è, non sotto forma di hash.

In questo trattamento, MemoryAI agisce come **titolare del trattamento** e OneSignal agisce come **responsabile del trattamento** per nostro conto, sulla base di un Accordo sul Trattamento dei Dati (DPA) conforme al GDPR.

Puoi disabilitare le notifiche push in qualsiasi momento:

- nelle Impostazioni dell'app → Notifiche, operazione che revoca anche il tuo consenso (Sezione 10);
- tramite le impostazioni di sistema del tuo dispositivo (su iOS: Impostazioni → Notifiche; su Android: Impostazioni → App → Notifiche).

Disattivare le notifiche nelle Impostazioni dell'app rimuove il tuo dispositivo dalla lista di distribuzione di OneSignal e revoca il tuo consenso: da quel momento OneSignal non riceve più nulla dall'app. Disattivarle nelle impostazioni del dispositivo interrompe i messaggi push. Se avevi accettato la precedente richiesta "Privacy e Notifiche", l'app ti chiede una volta di nuovo il consenso con il nuovo testo; se rifiuti, il tuo dispositivo viene rimosso allo stesso modo. Le notifiche sono disattivate mentre la Modalità Bambini è attiva (Sezione 11).

Per maggiori informazioni, consulta:

- Informativa sulla privacy di OneSignal: [onesignal.com/privacy_policy](https://onesignal.com/privacy_policy)
- Documentazione GDPR di OneSignal: [documentation.onesignal.com/docs/gdpr](https://documentation.onesignal.com/docs/en/gdpr-compliance)

---

## 6. Archiviazione e sicurezza dei dati

Tutti i tuoi dati sono archiviati in un database locale sul tuo dispositivo per impostazione predefinita. Non sono crittografati dall'app per impostazione predefinita, ma beneficiano delle funzionalità di sicurezza integrate nel tuo dispositivo (ad es. crittografia del dispositivo, schermata di blocco).

Se utilizzi la funzione di backup su cloud, i tuoi dati vengono inoltre archiviati nel tuo account personale Google Drive o iCloud. La sicurezza dei dati salvati è regolata dalle pratiche di sicurezza di Google o Apple, inclusi i loro standard di crittografia per i dati in transito e a riposo.

Ti consigliamo di:

- Mantenere aggiornato il sistema operativo del tuo dispositivo.
- Utilizzare un codice di accesso sicuro o il blocco biometrico.
- Non installare app da fonti non attendibili.
- Proteggere il tuo account Google o Apple con una password sicura e l'autenticazione a due fattori se utilizzi la funzione di backup.

Adottiamo misure ragionevoli nella progettazione dell'app per proteggere i tuoi dati, ma non possiamo garantire la sicurezza assoluta del tuo dispositivo o dei servizi di archiviazione cloud di terze parti.

---

## 7. Conservazione e cancellazione dei dati

I tuoi dati sono conservati sul tuo dispositivo per tutto il tempo che desideri. Hai il pieno controllo sui tuoi dati:

- **Cancellazione nell'app:** Puoi eliminare singole note, registrazioni, immagini e cronologie delle conversazioni in qualsiasi momento dall'interno dell'app.
- **Cancellazione completa dei dati:** La disinstallazione dell'app rimuoverà tutti i dati dell'app dal tuo dispositivo.
- **Cancellazione dei backup su cloud:** Se hai creato backup su cloud, la disinstallazione dell'app **non** elimina automaticamente tali backup. Devi eliminare i tuoi backup manualmente tramite Google Drive o iCloud. MemoryAI non conserva né ha accesso ai tuoi backup su cloud.
- **Dati per le notifiche:** Se hai accettato la richiesta "Notifiche" mostrata nell'app (o la precedente richiesta "Privacy e Notifiche"), il tuo record su OneSignal (l'identificativo casuale, i tag e i traguardi descritti nella Sezione 5 e, se hai consentito le notifiche, il token push) viene conservato da OneSignal per nostro conto; puoi chiederci di eliminarlo (Sezione 10). Quando disattivi le notifiche nelle Impostazioni dell'app o nelle impostazioni del dispositivo, disinstalli l'app o il tuo dispositivo diventa non raggiungibile, il record del dispositivo viene rimosso dal servizio e successivamente eliminato conformemente alle pratiche di conservazione di OneSignal.
- **Google Analytics for Firebase (versioni Android precedenti alla 1.0.55):** Se hai accettato la precedente richiesta "Privacy e Notifiche" su una di quelle versioni, i dati di utilizzo descritti nella Sezione 3 sono conservati da Google per il periodo impostato nelle nostre impostazioni di Google Analytics.

Non conserviamo alcuna copia dei tuoi dati sui nostri server, poiché non ne operiamo alcuno.

---

## 8. Trasferimenti internazionali di dati

MemoryAI non trasferisce alcun dato ai propri server, poiché non ne operiamo alcuno.

Tuttavia, se scegli di utilizzare la funzione di backup su cloud, i tuoi dati saranno archiviati su server gestiti da Google (per Google Drive) o Apple (per iCloud). Queste aziende possono archiviare i tuoi dati in data center situati al di fuori del tuo paese di residenza, incluso al di fuori dello Spazio Economico Europeo (SEE). Google e Apple dispongono di propri meccanismi per garantire la conformità ai requisiti di trasferimento internazionale dei dati, incluse le Clausole Contrattuali Standard e altre garanzie. Per maggiori informazioni, consulta le rispettive informative sulla privacy:

- Google: [policies.google.com/privacy](https://policies.google.com/privacy)
- Apple: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)

Inoltre, il download di file dei modelli IA da repository di terze parti (ad es. HuggingFace) comporta richieste di rete a server che possono trovarsi a livello internazionale. Nessun dato personale viene trasmesso durante questo processo.

Se accetti la richiesta "Notifiche" mostrata nell'app, i dati descritti nella Sezione 5 vengono trasmessi a **OneSignal**, che ha sede negli Stati Uniti. Questo trasferimento al di fuori dello Spazio Economico Europeo avviene sulla base delle Clausole Contrattuali Standard adottate dalla Commissione Europea e delle ulteriori garanzie descritte nella documentazione GDPR di OneSignal: [documentation.onesignal.com/docs/gdpr](https://documentation.onesignal.com/docs/en/gdpr-compliance). Anche la consegna della notifica stessa avviene tramite i servizi APNs di Apple (iOS) o FCM di Google (Android), che possono instradare i messaggi attraverso server situati al di fuori del SEE in conformità ai rispettivi quadri di compliance.

Sulle versioni Android precedenti alla 1.0.55, se hai accettato la precedente richiesta "Privacy e Notifiche", i dati di utilizzo raccolti da Google Analytics for Firebase (vedi Sezione 3) vengono trasmessi a **Google LLC**, che ha sede negli Stati Uniti. Anche i dati tecnici di utilizzo che Google ML Kit invia a Google (vedi Sezione 9) sono trattati da Google. Questi trasferimenti si basano sui meccanismi di Google per i trasferimenti internazionali di dati descritti sopra.

---

## 9. Librerie e servizi di terze parti

MemoryAI è costruita utilizzando librerie di terze parti. La maggior parte opera **sul dispositivo** e non trasmette i tuoi dati a server esterni. I principali componenti di terze parti includono:

- **Flutter:** Il framework multipiattaforma utilizzato per costruire l'app. Flutter stesso non raccoglie dati degli utenti.
- **Google ML Kit (Riconoscimento testo sul dispositivo):** Utilizzato per il riconoscimento del testo nelle immagini. Il riconoscimento avviene interamente sul dispositivo: le tue immagini e il testo riconosciuto **non** vengono inviati ai server di Google. Come tutte le librerie ML Kit, invia però a Google dati tecnici sul suo utilizzo e sulle sue prestazioni — informazioni sul dispositivo (come produttore, modello, versione del sistema operativo e hardware disponibile per l'apprendimento automatico), il nome del pacchetto e la versione dell'app, la versione della funzionalità ML Kit, un identificativo d'installazione non destinato a identificare te o il tuo dispositivo, i tempi di risposta e impostazioni come formato e risoluzione delle immagini, la dimensione dei dati in ingresso e in uscita, i tipi di evento e i codici di errore — che Google utilizza per diagnostica e analisi di utilizzo; Google può inoltre scaricare aggiornamenti dei modelli in background. Informativa di Google sui dati di ML Kit: [developers.google.com/ml-kit/android-data-disclosure](https://developers.google.com/ml-kit/android-data-disclosure). Informativa sulla privacy di Google: [policies.google.com/privacy](https://policies.google.com/privacy).
- **Google Drive (Backup Android):** Se abiliti la funzione di backup su Android, l'app utilizza l'API di Google Drive per caricare e scaricare file di backup dal tuo account personale Google Drive. Ciò richiede l'autenticazione con il tuo account Google. Vengono archiviati solo i dati di backup dell'app; MemoryAI non accede ad altri file nel tuo Google Drive. Informativa sulla privacy di Google: [policies.google.com/privacy](https://policies.google.com/privacy).
- **iCloud (Backup iOS):** Se abiliti la funzione di backup su iOS, l'app utilizza l'archiviazione iCloud di Apple per caricare e scaricare file di backup dal tuo account personale iCloud. Vengono archiviati solo i dati di backup dell'app; MemoryAI non accede ad altri file nel tuo iCloud. Informativa sulla privacy di Apple: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/).
- **Download modelli da HuggingFace:** L'app scarica file dei modelli IA da repository di terze parti (ad es. HuggingFace). Questi download richiedono una connessione di rete e possono comportare l'invio di un token di autenticazione al fornitore del repository. **Nessun dato personale o contenuto creato dall'utente viene trasmesso durante questo processo.** Solo i file dei modelli vengono scaricati sul tuo dispositivo. Informativa sulla privacy di HuggingFace: [huggingface.co/privacy](https://huggingface.co/privacy).
- **File adattatori LoRA:** L'app consente di importare file adattatori LoRA personalizzati (ad es. formato .gguf) dall'archiviazione del dispositivo. Questi file vengono copiati nell'archiviazione locale dell'app e vengono elaborati interamente sul dispositivo.
- **LLM sul dispositivo:** I modelli IA utilizzati per le conversazioni e la RAG funzionano localmente. Nessuna query o risposta viene trasmessa esternamente.
- **Condivisione/Esportazione (share_plus):** Quando utilizzi la funzione di Condivisione per esportare le conversazioni, l'app utilizza il foglio di condivisione nativo del tuo dispositivo (tramite la libreria share_plus). I dati vengono trasferiti al sistema operativo e poi all'app da te selezionata. MemoryAI non controlla né monitora i dati una volta che lasciano l'app.
- **TelemetryDeck (Analisi di utilizzo):** Utilizziamo TelemetryDeck per raccogliere statistiche di utilizzo. TelemetryDeck è un servizio di analisi rispettoso della privacy con sede in Germania (UE). **Non** raccoglie indirizzi IP. Le statistiche sono associate a un identificativo casuale che l'app genera al primo avvio e conserva sul tuo dispositivo; TelemetryDeck ne riceve solo un hash non reversibile, che ci permette di contare gli utenti distinti. L'identificativo non è collegato al tuo nome, al tuo account, al tuo numero di telefono né agli identificativi hardware del tuo dispositivo, e le statistiche non contengono mai ciò che scrivi, dici o importi. Tutti i dati vengono elaborati e archiviati nell'Unione Europea. Informativa sulla privacy di TelemetryDeck: [telemetrydeck.com/privacy](https://telemetrydeck.com/privacy/).
- **Sentry (Diagnostica di crash ed errori):** Utilizziamo Sentry per ricevere segnalazioni di crash e diagnostica sugli errori, così da individuare bug, correggere problemi di stabilità e migliorare l'affidabilità. Sentry **non** viene utilizzato per analisi di prodotto. Lo configuriamo per ridurre al minimo la raccolta dei dati, mantenere disattivato `sendDefaultPii` e filtrare o oscurare i payload diagnostici prima dell'invio. **Non** inviamo intenzionalmente prompt, conversazioni, contenuti dei documenti, contenuti dei backup o token di autenticazione a Sentry. A seconda della natura dell'errore, gli eventi diagnostici possono includere metadati tecnici come versione dell'app, numero di build, piattaforma, stack trace, lo stato della memoria nativa del dispositivo al momento dell'arresto anomalo (crash) e contesto dell'errore sanificato. Informativa sulla privacy di Sentry: [sentry.io/privacy](https://sentry.io/privacy/).
- **OneSignal (Notifiche push):** Se accetti la richiesta "Notifiche" mostrata nell'app, utilizziamo OneSignal (OneSignal, Inc., Stati Uniti) per consegnare le notifiche. In questo trattamento, MemoryAI è il titolare del trattamento e OneSignal agisce come responsabile del trattamento per nostro conto sulla base di un Accordo sul Trattamento dei Dati (DPA) conforme al GDPR. I dati condivisi con OneSignal sono limitati a un token push del dispositivo, se consenti le notifiche (emesso da APNs su iOS o FCM su Android); un identificativo casuale generato dall'app; alcuni tag con la versione dell'app (app_version) e il nome dell'ultimo modello IA che hai caricato (preferred_model); la registrazione della prima chat completata e del primo documento importato (mai il loro contenuto), utilizzata per misurare l'efficacia delle nostre notifiche; e metadati tecnici utilizzati per consegnare e localizzare le notifiche (versione dell'app, versione della piattaforma/sistema operativo, preferenza linguistica, paese derivato dall'indirizzo IP al momento della registrazione e fuso orario). **Non** condividiamo con OneSignal alcuna nota, conversazione, registrazione vocale, immagine, documento, contenuto di backup o altro contenuto generato dall'utente. L'identificativo è casuale e non è legato al tuo nome, al tuo account, al tuo numero di telefono né agli identificativi hardware, ma è un identificativo persistente dell'app, lo stesso utilizzato per le statistiche di utilizzo, e OneSignal lo riceve così com'è, non sotto forma di hash. Puoi disattivare le notifiche nelle Impostazioni dell'app, operazione che rimuove il tuo dispositivo e revoca il tuo consenso, oppure nelle impostazioni del dispositivo. Informativa sulla privacy di OneSignal: [onesignal.com/privacy_policy](https://onesignal.com/privacy_policy). Documentazione GDPR di OneSignal: [documentation.onesignal.com/docs/gdpr](https://documentation.onesignal.com/docs/en/gdpr-compliance).
- **Google Analytics for Firebase (solo versioni Android precedenti alla 1.0.55):** Su quelle versioni, se hai accettato la precedente richiesta "Privacy e Notifiche" mostrata nell'app, utilizziamo Google Analytics for Firebase per misurare l'efficacia delle nostre campagne pubblicitarie su Google Ads (monitoraggio delle conversioni). L'app disattiva la raccolta all'avvio e la attiva solo se hai accettato. Quando accetti, l'app comunica il tuo consenso a Google tramite Google Consent Mode (analytics_storage, ad_storage, ad_user_data e ad_personalization, tutti concessi) e registra due eventi — il completamento della configurazione iniziale e il primo messaggio inviato in ogni sessione (mai il suo contenuto) — e la lingua dell'app, oltre agli eventi che Firebase registra automaticamente. La versione 1.0.55 e le successive non lo contengono, e non viene utilizzato su iOS. Informativa sulla privacy di Google: [policies.google.com/privacy](https://policies.google.com/privacy).

Se in futuro integreremo nuovi servizi di terze parti, aggiorneremo di conseguenza la presente informativa.

---

## 10. I tuoi diritti ai sensi del GDPR

In qualità di utente nell'Unione Europea, hai i seguenti diritti ai sensi del GDPR. Poiché i tuoi contenuti sono archiviati localmente sul tuo dispositivo (e opzionalmente nel tuo archivio cloud personale), puoi esercitare la maggior parte di questi diritti direttamente:

- **Diritto di essere informato (Art. 13–14):** La presente informativa sulla privacy adempie al nostro obbligo di informarti sul trattamento dei dati.
- **Diritto di accesso (Art. 15):** Tutti i tuoi dati sono accessibili direttamente all'interno dell'app e, se salvati, nel tuo account Google Drive o iCloud.
- **Diritto di rettifica (Art. 16):** Puoi modificare qualsiasi dato all'interno dell'app in qualsiasi momento.
- **Diritto alla cancellazione (Art. 17):** Puoi eliminare singoli elementi all'interno dell'app, rimuovere tutti i dati disinstallando l'app ed eliminare i backup su cloud tramite Google Drive o iCloud.
- **Diritto alla limitazione del trattamento (Art. 18):** Puoi revocare le autorizzazioni del dispositivo per limitare specifiche attività di trattamento.
- **Diritto alla portabilità dei dati (Art. 20):** Puoi esportare le tue conversazioni come testo o Markdown utilizzando la funzione di Condivisione all'interno dell'app.
- **Diritto di opposizione (Art. 21):** Puoi interrompere il trattamento locale in qualsiasi momento revocando le autorizzazioni o disinstallando l'app, e puoi opporti al trattamento da parte dei fornitori di servizi descritti nella Sezione 3 contattandoci.
- **Diritto di revocare il consenso (Art. 7(3)):** Laddove il trattamento sia basato sul tuo consenso — la richiesta "Notifiche" mostrata nell'app ("Privacy e Notifiche" nelle versioni precedenti) — puoi revocarlo in qualsiasi momento nelle Impostazioni dell'app → Notifiche, operazione che rimuove anche il tuo dispositivo da OneSignal, scrivendo a postmaster@facchinits.it o disinstallando l'app. Riattivare le notifiche nelle Impostazioni equivale a dare di nuovo il consenso. Su Android, aggiornare l'app alla versione 1.0.55 o successive interrompe inoltre la raccolta da parte di Google Analytics for Firebase delle versioni precedenti. La revoca non pregiudica la liceità del trattamento basato sul consenso effettuato prima della revoca.
- **Diritti relativi al processo decisionale automatizzato (Art. 22):** Le funzionalità IA dell'app ti assistono ma non prendono decisioni che producano effetti giuridici o che ti riguardino in modo analogo e significativo.
- **Diritto di presentare un reclamo:** Hai il diritto di presentare un reclamo a un'autorità di controllo. In Italia, si tratta del **Garante per la protezione dei dati personali** ([www.garanteprivacy.it](https://www.garanteprivacy.it)).

Per esercitare qualsiasi diritto che richieda la nostra assistenza, contattaci all'indirizzo **postmaster@facchinits.it**.

---

## 11. Privacy dei minori

Come per tutti gli utenti, non raccogliamo, trasmettiamo o archiviamo alcuna conversazione o contenuto creato dagli utenti sui nostri server. Tutta l'elaborazione IA e il filtraggio dei contenuti, inclusa la Modalità Bambini, avvengono interamente a livello locale sul dispositivo.

Offriamo una **Modalità Bambini** protetta da PIN, progettata per aiutare i genitori a fornire un'esperienza più sicura e limitata per i bambini. Quando la Modalità Bambini è attiva, tutta l'elaborazione dell'IA e il filtraggio dei contenuti avvengono comunque in modo completamente locale sul dispositivo. Non registriamo né trasmettiamo ciò che tuo figlio scrive o dice. Le statistiche di utilizzo e le segnalazioni di crash descritte nella Sezione 3, che non contengono mai contenuti, possono essere raccolte anche mentre la Modalità Bambini è attiva (e, sulle versioni Android precedenti alla 1.0.55, lo stesso vale per Google Analytics for Firebase se la precedente richiesta è stata accettata). Le notifiche sono disattivate mentre la Modalità Bambini è attiva: il dispositivo viene rimosso da OneSignal, non gli viene inviato nulla e la richiesta per le notifiche non viene mostrata; disattivando la Modalità Bambini si ripristina la scelta del genitore. In qualità di genitore o tutore, mantieni il pieno controllo e puoi eliminare i dati dell'app in qualsiasi momento disinstallando l'app dal dispositivo e rimuovendo eventuali backup su cloud da Google Drive o iCloud.

---

## 12. Modifiche alla presente Informativa sulla Privacy

Potremmo aggiornare la presente Informativa sulla Privacy di tanto in tanto. Quando lo faremo:

- Aggiorneremo la data di "Ultimo aggiornamento" nella parte superiore di questa pagina.
- Per modifiche significative, forniremo una notifica all'interno dell'app prima che le modifiche entrino in vigore.

Ti invitiamo a consultare periodicamente la presente Informativa sulla Privacy.

---

## 13. Contattaci

Per qualsiasi domanda, dubbio o richiesta relativa alla presente Informativa sulla Privacy o ai tuoi dati, contattaci:

- **Email:** postmaster@facchinits.it

Ci impegniamo a rispondere a tutte le richieste entro 30 giorni, come previsto dal GDPR.
