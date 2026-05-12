# Informativa sulla Privacy di MemoryAI

**Data di entrata in vigore: 10/03/2026**
**Ultimo aggiornamento: 12/05/2026**

Grazie per aver scelto MemoryAI! La presente Informativa sulla Privacy spiega come gestiamo le tue informazioni quando utilizzi la nostra applicazione mobile. La tua privacy è la nostra massima priorità e ci impegniamo a proteggerla. Questa informativa è conforme al Regolamento Generale sulla Protezione dei Dati (GDPR) e alla normativa italiana in materia di protezione dei dati personali.

Questa informativa è disponibile in [Inglese](index.md) e [Italiano](privacy-policy-it.md).

---

## In breve

MemoryAI è un'applicazione privata che funziona principalmente offline. Tutti i tuoi dati — incluse note, registrazioni vocali, immagini e interazioni con l'IA — sono archiviati localmente sul tuo dispositivo per impostazione predefinita. **Non disponiamo di alcuna infrastruttura backend che riceva le tue informazioni.** L'attività di rete dell'app è limitata a: download di file dei modelli IA da repository di terze parti (ad es. HuggingFace); se scegli di abilitarlo, backup dei tuoi dati nel tuo spazio di archiviazione cloud personale (Google Drive su Android, iCloud su iOS); e, se acconsenti a ricevere le notifiche push, condivisione di un token push del dispositivo con il nostro fornitore di notifiche (OneSignal) per consentirci di inviare messaggi al tuo dispositivo.

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

- **Il tuo consenso (Art. 6(1)(a)):** Quando utilizzi la nostra app e concedi le autorizzazioni del dispositivo (microfono, fotocamera, archiviazione), acconsenti al trattamento locale dei tuoi dati come descritto nella presente informativa. Se scegli di abilitare la funzione di backup su cloud, acconsenti esplicitamente al caricamento dei tuoi dati nel tuo account di archiviazione cloud personale. Se scegli di abilitare le notifiche push, acconsenti esplicitamente alla condivisione di un token push (e di metadati minimi correlati) con il nostro fornitore di notifiche, come descritto nelle Sezioni 5 e 9. Puoi revocare questo consenso in qualsiasi momento disabilitando le notifiche push.
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
- **Dati per le notifiche push (opzionale):** Se abiliti le notifiche push, un token push del dispositivo viene generato da Apple (APNs) o Google (FCM) e condiviso con il nostro fornitore di notifiche, OneSignal, per consentire la consegna dei messaggi al tuo dispositivo. Insieme al token, OneSignal può ricevere metadati tecnici limitati come la versione dell'app, la versione della piattaforma/sistema operativo, la preferenza linguistica, il paese (derivato dall'indirizzo IP al momento della registrazione) e il fuso orario, utilizzati per inviarti notifiche pertinenti e localizzate. Vedi Sezioni 5 e 9 per i dettagli.
- **Preferenze dell'app:** Impostazioni e preferenze configurate all'interno dell'app (ad es. selezione della lingua, tema).

Raccogliamo **dati di utilizzo anonimi minimi** tramite TelemetryDeck, un servizio di analisi rispettoso della privacy con sede nell'Unione Europea (Germania). Queste analisi ci aiutano a capire come viene utilizzata l'app e a migliorarla. I dati raccolti sono **completamente anonimi** — non contengono informazioni personali, identificativi del dispositivo, indirizzi IP né contenuti generati dall'utente. Esempi di segnali anonimi includono: "l'app è stata aperta", "un modello è stato caricato", "un messaggio è stato inviato" (mai il contenuto del messaggio). Per maggiori dettagli, vedi Sezione 9. Puoi saperne di più sulle pratiche di privacy di TelemetryDeck su [telemetrydeck.com/privacy](https://telemetrydeck.com/privacy/).

Utilizziamo inoltre **Sentry** per la diagnostica di crash ed errori. Sentry viene usato solo per aiutarci a rilevare, analizzare e correggere i malfunzionamenti dell'app; **non** viene usato per analisi di prodotto. Configuriamo Sentry per ridurre al minimo i dati inviati, disattivare la raccolta predefinita di informazioni personali identificabili e filtrare o oscurare i payload diagnostici prima dell'invio. **Non** inviamo intenzionalmente a Sentry i tuoi prompt, messaggi, contenuti dei documenti, contenuti dei backup o token di autenticazione. Nessun contenuto creato dall'utente viene inviato a server di proprietà o gestiti da MemoryAI, salvo quando scegli esplicitamente di eseguire un backup nel tuo archivio cloud personale o di condividere contenuti tramite la funzione di Condivisione (vedi Sezione 5).

---

## 4. Autorizzazioni del dispositivo

Per fornire le sue funzionalità principali, MemoryAI può richiedere le seguenti autorizzazioni del dispositivo:

| Autorizzazione | Finalità |
|---|---|
| **Microfono** | Per registrare input vocali per la trascrizione e le interazioni con l'IA. |
| **Fotocamera** | Per acquisire immagini per il riconoscimento del testo e la creazione di note. |
| **Archiviazione / Foto** | Per accedere alle immagini dalla galleria, per importare file adattatori LoRA e per archiviare i dati dell'app localmente. |
| **Rete / Internet** | Per scaricare file dei modelli IA da repository di terze parti (ad es. HuggingFace) e, se abilitato, per eseguire il backup e il ripristino dei dati tramite archiviazione cloud. Nessun dato viene inviato a server di MemoryAI. |
| **Account Google (Android)** | Richiesto solo se abiliti la funzione di backup su Google Drive. Utilizzato per autenticarsi con il tuo account Google e accedere al tuo spazio Google Drive. |
| **Notifiche** | Richiesta solo se scegli di abilitare le notifiche push. Utilizzata dal sistema operativo per visualizzare i messaggi che inviamo tramite il nostro fornitore di notifiche (OneSignal). Puoi revocare questa autorizzazione in qualsiasi momento senza compromettere alcuna altra funzionalità dell'app. |

Puoi revocare qualsiasi di queste autorizzazioni in qualsiasi momento tramite le impostazioni di sistema del tuo dispositivo. La revoca di un'autorizzazione potrebbe disabilitare la funzionalità corrispondente, ma non influenzerà il resto dell'app.

---

## 5. Come utilizziamo le tue informazioni

Tutto il trattamento delle tue informazioni avviene **localmente sul tuo dispositivo**. Utilizziamo i dati che fornisci per:

- Abilitare le funzionalità principali dell'app, come la creazione di note, la RAG e l'interazione con i modelli IA locali.
- Trascrivere le tue registrazioni vocali sul dispositivo.
- Riconoscere ed estrarre testo dalle tue immagini sul dispositivo.

Poiché non abbiamo accesso ai tuoi dati, non li utilizziamo e non possiamo utilizzarli per pubblicità, profilazione, analisi o qualsiasi altro scopo diverso dalla fornitura delle funzionalità dell'app.

### Backup e ripristino su cloud

MemoryAI offre una funzione **opzionale** di backup e ripristino su cloud per aiutarti a proteggere i tuoi dati o trasferirli tra dispositivi:

- **Su Android**, i tuoi dati vengono salvati nel tuo account personale **Google Drive**.
- **Su iOS**, i tuoi dati vengono salvati nel tuo account personale **iCloud**.

Questa funzione **non è abilitata per impostazione predefinita** — devi scegliere esplicitamente di creare un backup o ripristinarne uno. Quando avvii un backup, una copia dei dati dell'app (note, conversazioni, preferenze e contenuti correlati) viene caricata nel tuo account di archiviazione cloud personale. MemoryAI non ha accesso al tuo account di archiviazione cloud e non può leggere, modificare o eliminare i tuoi backup. I dati salvati sono soggetti alle informative sulla privacy e alle pratiche di sicurezza di Google o Apple, rispettivamente.

Puoi eliminare i tuoi backup su cloud in qualsiasi momento direttamente tramite Google Drive o iCloud.

### Condivisione ed esportazione

Quando utilizzi la **funzione di Condivisione/Esportazione**, i dati delle tue conversazioni vengono passati alla funzionalità di condivisione nativa del tuo dispositivo (tramite il foglio di condivisione del sistema operativo). Da lì, i dati possono essere inviati ad altre app o servizi da te scelti. MemoryAI non ha alcun controllo su come tali app di terze parti gestiscono i tuoi dati.

### Notifiche push

MemoryAI offre notifiche push **opzionali** per informarti su nuove funzionalità, aggiornamenti dei modelli e miglioramenti dell'app. Questa funzione **non è abilitata per impostazione predefinita** — devi accettare esplicitamente quando richiesto dal sistema operativo o tramite le Impostazioni dell'app.

Utilizziamo **OneSignal** (OneSignal, Inc., con sede negli Stati Uniti) come fornitore per la consegna delle notifiche. Quando abiliti le notifiche push:

- Un token push del dispositivo emesso da Apple Push Notification service (APNs) su iOS o da Firebase Cloud Messaging (FCM) su Android viene condiviso con OneSignal affinché i messaggi possano essere instradati al tuo dispositivo.
- Insieme al token, possiamo condividere metadati tecnici limitati — come la versione dell'app, la versione della piattaforma/sistema operativo, la preferenza linguistica, il paese (derivato dall'indirizzo IP al momento della registrazione) e il fuso orario — per poterti inviare notifiche pertinenti e localizzate.
- **Non** condividiamo con OneSignal alcuna nota, conversazione, registrazione vocale, immagine, documento, contenuto di backup o qualsiasi altro contenuto da te creato all'interno dell'app. Non ti assegniamo un identificativo personale; OneSignal vede solo un identificatore opaco a livello di dispositivo.

In questo trattamento, MemoryAI agisce come **titolare del trattamento** e OneSignal agisce come **responsabile del trattamento** per nostro conto, sulla base di un Accordo sul Trattamento dei Dati (DPA) conforme al GDPR.

Puoi disabilitare le notifiche push in qualsiasi momento:

- tramite le impostazioni di sistema del tuo dispositivo (su iOS: Impostazioni → Notifiche; su Android: Impostazioni → App → Notifiche), oppure
- all'interno della schermata Impostazioni dell'app.

La disabilitazione delle notifiche interrompe tutti i messaggi push e comporta la rimozione del tuo dispositivo dalla lista di distribuzione di OneSignal per la nostra app. La disabilitazione delle notifiche push costituisce inoltre la revoca del consenso ai sensi dell'Articolo 7(3) del GDPR per questo specifico trattamento.

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
- **Token per le notifiche push:** Se hai abilitato le notifiche push, il token push del dispositivo e i metadati associati vengono conservati da OneSignal per nostro conto solo finché il tuo dispositivo rimane iscritto al servizio. Quando disabiliti le notifiche, disinstalli l'app o il tuo dispositivo diventa non raggiungibile, il record del dispositivo viene rimosso dal servizio e successivamente eliminato conformemente alle pratiche di conservazione di OneSignal.

Non conserviamo alcuna copia dei tuoi dati sui nostri server, poiché non ne operiamo alcuno.

---

## 8. Trasferimenti internazionali di dati

MemoryAI non trasferisce alcun dato ai propri server, poiché non ne operiamo alcuno.

Tuttavia, se scegli di utilizzare la funzione di backup su cloud, i tuoi dati saranno archiviati su server gestiti da Google (per Google Drive) o Apple (per iCloud). Queste aziende possono archiviare i tuoi dati in data center situati al di fuori del tuo paese di residenza, incluso al di fuori dello Spazio Economico Europeo (SEE). Google e Apple dispongono di propri meccanismi per garantire la conformità ai requisiti di trasferimento internazionale dei dati, incluse le Clausole Contrattuali Standard e altre garanzie. Per maggiori informazioni, consulta le rispettive informative sulla privacy:

- Google: [policies.google.com/privacy](https://policies.google.com/privacy)
- Apple: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/)

Inoltre, il download di file dei modelli IA da repository di terze parti (ad es. HuggingFace) comporta richieste di rete a server che possono trovarsi a livello internazionale. Nessun dato personale viene trasmesso durante questo processo.

Se acconsenti a ricevere notifiche push, il token push e i metadati tecnici associati descritti nella Sezione 5 vengono trasmessi a **OneSignal**, che ha sede negli Stati Uniti. Questo trasferimento al di fuori dello Spazio Economico Europeo avviene sulla base delle Clausole Contrattuali Standard adottate dalla Commissione Europea e delle ulteriori garanzie descritte nella documentazione GDPR di OneSignal: [documentation.onesignal.com/docs/gdpr](https://documentation.onesignal.com/docs/en/gdpr-compliance). Anche la consegna della notifica stessa avviene tramite i servizi APNs di Apple (iOS) o FCM di Google (Android), che possono instradare i messaggi attraverso server situati al di fuori del SEE in conformità ai rispettivi quadri di compliance.

---

## 9. Librerie e servizi di terze parti

MemoryAI è costruita utilizzando librerie di terze parti. La maggior parte opera **sul dispositivo** e non trasmette i tuoi dati a server esterni. I principali componenti di terze parti includono:

- **Flutter:** Il framework multipiattaforma utilizzato per costruire l'app. Flutter stesso non raccoglie dati degli utenti.
- **Google ML Kit (Riconoscimento testo sul dispositivo):** Utilizzato per il riconoscimento del testo nelle immagini. Questa API funziona interamente sul dispositivo. Sebbene Google possa scaricare aggiornamenti dei modelli in background, le tue immagini e il testo riconosciuto **non** vengono inviati ai server di Google. Informativa sulla privacy di Google: [policies.google.com/privacy](https://policies.google.com/privacy).
- **Google Drive (Backup Android):** Se abiliti la funzione di backup su Android, l'app utilizza l'API di Google Drive per caricare e scaricare file di backup dal tuo account personale Google Drive. Ciò richiede l'autenticazione con il tuo account Google. Vengono archiviati solo i dati di backup dell'app; MemoryAI non accede ad altri file nel tuo Google Drive. Informativa sulla privacy di Google: [policies.google.com/privacy](https://policies.google.com/privacy).
- **iCloud (Backup iOS):** Se abiliti la funzione di backup su iOS, l'app utilizza l'archiviazione iCloud di Apple per caricare e scaricare file di backup dal tuo account personale iCloud. Vengono archiviati solo i dati di backup dell'app; MemoryAI non accede ad altri file nel tuo iCloud. Informativa sulla privacy di Apple: [apple.com/legal/privacy](https://www.apple.com/legal/privacy/).
- **Download modelli da HuggingFace:** L'app scarica file dei modelli IA da repository di terze parti (ad es. HuggingFace). Questi download richiedono una connessione di rete e possono comportare l'invio di un token di autenticazione al fornitore del repository. **Nessun dato personale o contenuto creato dall'utente viene trasmesso durante questo processo.** Solo i file dei modelli vengono scaricati sul tuo dispositivo. Informativa sulla privacy di HuggingFace: [huggingface.co/privacy](https://huggingface.co/privacy).
- **File adattatori LoRA:** L'app consente di importare file adattatori LoRA personalizzati (ad es. formato .gguf) dall'archiviazione del dispositivo. Questi file vengono copiati nell'archiviazione locale dell'app e vengono elaborati interamente sul dispositivo.
- **LLM sul dispositivo:** I modelli IA utilizzati per le conversazioni e la RAG funzionano localmente. Nessuna query o risposta viene trasmessa esternamente.
- **Condivisione/Esportazione (share_plus):** Quando utilizzi la funzione di Condivisione per esportare le conversazioni, l'app utilizza il foglio di condivisione nativo del tuo dispositivo (tramite la libreria share_plus). I dati vengono trasferiti al sistema operativo e poi all'app da te selezionata. MemoryAI non controlla né monitora i dati una volta che lasciano l'app.
- **Acquisti in-app:** Utilizziamo le API native per gli acquisti in-app fornite da Apple (App Store) e Google (Google Play) per gestire lo sblocco delle funzionalità premium. Non abbiamo accesso alle tue informazioni di pagamento o fatturazione — questo è gestito interamente da Apple o Google. L'acquisto di funzionalità premium **non** modifica il modo in cui i tuoi dati vengono gestiti; tutti i dati rimangono locali a meno che tu non scelga di utilizzare la funzione di backup.
- **TelemetryDeck (Analisi anonime):** Utilizziamo TelemetryDeck per raccogliere statistiche di utilizzo anonime e aggregate. TelemetryDeck è un servizio di analisi rispettoso della privacy con sede in Germania (UE). **Non** raccoglie dati personali, identificativi del dispositivo, indirizzi IP né alcun contenuto generato dall'utente. L'identificazione degli utenti utilizza un hash crittografico a rotazione giornaliera che non può essere invertito o collegato a nessun individuo. Tutti i dati vengono elaborati e archiviati nell'Unione Europea. Informativa sulla privacy di TelemetryDeck: [telemetrydeck.com/privacy](https://telemetrydeck.com/privacy/).
- **Sentry (Diagnostica di crash ed errori):** Utilizziamo Sentry per ricevere segnalazioni di crash e diagnostica sugli errori, così da individuare bug, correggere problemi di stabilità e migliorare l'affidabilità. Sentry **non** viene utilizzato per analisi di prodotto. Lo configuriamo per ridurre al minimo la raccolta dei dati, mantenere disattivato `sendDefaultPii` e filtrare o oscurare i payload diagnostici prima dell'invio. **Non** inviamo intenzionalmente prompt, conversazioni, contenuti dei documenti, contenuti dei backup o token di autenticazione a Sentry. A seconda della natura dell'errore, gli eventi diagnostici possono includere metadati tecnici come versione dell'app, numero di build, piattaforma, stack trace, lo stato della memoria nativa del dispositivo al momento dell'arresto anomalo (crash) e contesto dell'errore sanificato. Informativa sulla privacy di Sentry: [sentry.io/privacy](https://sentry.io/privacy/).
- **OneSignal (Notifiche push):** Se acconsenti a ricevere notifiche push, utilizziamo OneSignal (OneSignal, Inc., Stati Uniti) per consegnarle. In questo trattamento, MemoryAI è il titolare del trattamento e OneSignal agisce come responsabile del trattamento per nostro conto sulla base di un Accordo sul Trattamento dei Dati (DPA) conforme al GDPR. I dati condivisi con OneSignal sono limitati a un token push del dispositivo (emesso da APNs su iOS o FCM su Android) insieme a metadati tecnici utilizzati per consegnare e localizzare le notifiche (versione dell'app, versione della piattaforma/sistema operativo, preferenza linguistica, paese derivato dall'indirizzo IP al momento della registrazione e fuso orario). **Non** condividiamo con OneSignal alcuna nota, conversazione, registrazione vocale, immagine, documento, contenuto di backup o altro contenuto generato dall'utente, e non assegniamo identificativi utente personalmente identificabili. Puoi disabilitare le notifiche push in qualsiasi momento dalle impostazioni del dispositivo o dalla schermata Impostazioni dell'app, operazione che comporta la rimozione del tuo dispositivo dalla lista di distribuzione di OneSignal. Informativa sulla privacy di OneSignal: [onesignal.com/privacy_policy](https://onesignal.com/privacy_policy). Documentazione GDPR di OneSignal: [documentation.onesignal.com/docs/gdpr](https://documentation.onesignal.com/docs/en/gdpr-compliance).

Se in futuro integreremo nuovi servizi di terze parti, aggiorneremo di conseguenza la presente informativa.

---

## 10. I tuoi diritti ai sensi del GDPR

In qualità di utente nell'Unione Europea, hai i seguenti diritti ai sensi del GDPR. Poiché tutti i tuoi dati sono archiviati localmente sul tuo dispositivo (e opzionalmente nel tuo archivio cloud personale), puoi esercitare la maggior parte di questi diritti direttamente:

- **Diritto di essere informato (Art. 13–14):** La presente informativa sulla privacy adempie al nostro obbligo di informarti sul trattamento dei dati.
- **Diritto di accesso (Art. 15):** Tutti i tuoi dati sono accessibili direttamente all'interno dell'app e, se salvati, nel tuo account Google Drive o iCloud.
- **Diritto di rettifica (Art. 16):** Puoi modificare qualsiasi dato all'interno dell'app in qualsiasi momento.
- **Diritto alla cancellazione (Art. 17):** Puoi eliminare singoli elementi all'interno dell'app, rimuovere tutti i dati disinstallando l'app ed eliminare i backup su cloud tramite Google Drive o iCloud.
- **Diritto alla limitazione del trattamento (Art. 18):** Puoi revocare le autorizzazioni del dispositivo per limitare specifiche attività di trattamento.
- **Diritto alla portabilità dei dati (Art. 20):** Puoi esportare le tue conversazioni come testo o Markdown utilizzando la funzione di Condivisione all'interno dell'app.
- **Diritto di opposizione (Art. 21):** Poiché il trattamento è locale e sotto il tuo controllo, puoi interrompere il trattamento in qualsiasi momento revocando le autorizzazioni o disinstallando l'app.
- **Diritto di revocare il consenso (Art. 7(3)):** Laddove il trattamento sia basato sul tuo consenso — come nel caso delle notifiche push — puoi revocare tale consenso in qualsiasi momento disabilitando le notifiche nelle impostazioni del dispositivo o all'interno dell'app, senza pregiudicare la liceità del trattamento basato sul consenso effettuato prima della revoca.
- **Diritti relativi al processo decisionale automatizzato (Art. 22):** Le funzionalità IA dell'app ti assistono ma non prendono decisioni che producano effetti giuridici o che ti riguardino in modo analogo e significativo.
- **Diritto di presentare un reclamo:** Hai il diritto di presentare un reclamo a un'autorità di controllo. In Italia, si tratta del **Garante per la protezione dei dati personali** ([www.garanteprivacy.it](https://www.garanteprivacy.it)).

Per esercitare qualsiasi diritto che richieda la nostra assistenza, contattaci all'indirizzo **postmaster@facchinits.it**.

---

## 11. Privacy dei minori

MemoryAI non è destinata all'uso da parte di minori di età inferiore ai 16 anni nell'Unione Europea o inferiore ai 13 anni in altre giurisdizioni. Non raccogliamo consapevolmente informazioni personali da minori. Poiché tutti i dati vengono trattati localmente, non abbiamo modo di identificare l'età dei nostri utenti. Se sei un genitore o un tutore e ritieni che tuo figlio stia utilizzando l'app in modo inappropriato, puoi eliminare i dati dell'app disinstallando l'app dal dispositivo e rimuovendo eventuali backup su cloud da Google Drive o iCloud.

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
