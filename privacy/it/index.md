---
layout: default
title: Informativa sulla privacy — Sacra Confraternita del Passo
description: Informativa sulla privacy della beta privata di Sacra Confraternita del Passo.
lang: it
alternate_url: /privacy/en/
alternate_lang: en
alternate_label: English
permalink: /privacy/it/
---

# Informativa sulla privacy — Sacra Confraternita del Passo

> **BOZZA — non revisionata da un legale.** Questa informativa è stata redatta
> per la beta TestFlight, accessibile solo su invito, di Sacra Confraternita
> del Passo. Descrive in buona fede, e con attenzione al GDPR, il funzionamento
> attuale dell'app. Dovrà essere sottoposta a revisione legale prima di una
> distribuzione pubblica, della monetizzazione o di qualsiasi ampliamento
> sostanziale oltre la cerchia chiusa di invitati del fondatore.

**Versione:** 2.1 · **Data di entrata in vigore:** 23 agosto 2026

## 1. Chi siamo

Sacra Confraternita del Passo ("SCP", "l'app", "noi") è un'app privata di
sfide a passi, accessibile solo su invito, destinata a un gruppo chiuso di amici
e amici di amici. Per questa beta, il fondatore e gestore di SCP è il titolare
del trattamento.

Per qualsiasi domanda o richiesta relativa alla privacy puoi contattarci
all'indirizzo **sacraconfraternitadelpasso@gmail.com**.

## 2. Dati che trattiamo

Trattiamo le seguenti categorie di dati:

- **Dati dell'account e del consenso:** indirizzo email, identificativo utente
  dell'autenticazione Supabase, nickname, data di creazione dell'account,
  relazione d'invito, data e versione del consenso privacy prestato.
- **Dati sui passi provenienti da Apple Health (HealthKit):** conteggi dei passi
  registrati automaticamente per i giorni e gli intervalli di date necessari
  all'app. Le registrazioni manuali sono escluse.
- **Dati derivati sull'attività fisica:** totali giornalieri sincronizzati,
  totali complessivi da quando hai aderito a SCP o hai iniziato l'attuale ciclo
  di Rango, XP del ciclo, Rango e relativi valori di avanzamento.
- **Dati relativi alle sfide e alle funzionalità social:** sfide create o a cui
  partecipi, inviti, stato di partecipazione, relazioni tra Confratelli, squadre,
  calendari, punteggi, classifiche, risultati, trofei, Imprese e altri dati
  storici delle competizioni.
- **Comunicazioni e preferenze:** notifiche nell'app, eventi del feed attività,
  stato di lettura, obiettivo giornaliero, scelte di visibilità e preferenze
  relative alle notifiche.
- **Dati tecnici e di sicurezza:** normali log di autenticazione e di servizio
  prodotti dai nostri fornitori, che possono comprendere data e ora, indirizzo
  IP, informazioni sul dispositivo o sulla rete e registrazioni antifrode quando
  un conteggio dei passi appena letto non coincide con un totale sincronizzato
  in precedenza.

La lingua, l'orario del promemoria giornaliero locale e il completamento della
prima introduzione ai permessi Health sono memorizzati sul dispositivo e non
vengono intenzionalmente caricati nel database di SCP. SCP non contiene
pubblicità né SDK di analisi di terze parti.

### Apple Health / HealthKit

SCP richiede accesso in sola lettura alla categoria **Conteggio passi** di Apple
Health. Non richiede frequenza cardiaca, sonno, posizione, allenamenti, cartelle
cliniche o altre categorie Health e non scrive mai dati in Apple Health. I passi
inseriti manualmente nell'app Salute sono esclusi dai conteggi di SCP.

Quando concedi l'accesso, SCP legge i totali necessari a calcolare i punteggi
giornalieri recenti o mancanti e l'avanzamento del Rango a partire dalla data in
cui hai aderito, oppure dall'inizio del ciclo di Rango corrente. Le letture
avvengono sul dispositivo quando l'app deve aggiornare queste funzioni. I totali
giornalieri e derivati risultanti vengono quindi sincronizzati con il database
Supabase di SCP, affinché sfide, classifiche e funzioni social possano operare
tra membri e dispositivi diversi.

Il permesso HealthKit è gestito da Apple e può essere modificato in qualsiasi
momento nell'app Salute o nelle impostazioni privacy di iOS. Apple non comunica
intenzionalmente a un'app se l'accesso in lettura è stato negato; SCP può quindi
non vedere dati sui passi sia quando l'accesso è negato, sia quando non esistono
dati corrispondenti. La revoca dell'accesso HealthKit interrompe le letture
future, ma non cancella automaticamente i totali già sincronizzati con SCP. Puoi
cancellare o richiedere accesso a tali copie come descritto nella sezione 7.

Non utilizziamo i dati derivati da HealthKit per pubblicità, marketing o data
mining e non li vendiamo.

## 3. Perché trattiamo i dati e relative basi giuridiche

- **Fornire l'account e il servizio di sfide:** i dati dell'account, delle sfide,
  delle funzioni social e delle preferenze sono necessari per eseguire il nostro
  accordo con te.
- **Leggere, sincronizzare, confrontare e mostrare i dati sui passi:** ci basiamo
  sul tuo consenso esplicito per le finalità indicate relative all'attività
  fisica e alle sfide. Trattiamo i dati sui passi come dati sensibili relativi
  alla salute o all'attività fisica e, ove si applica il GDPR, ci basiamo sugli
  articoli 6(1)(a) e 9(2)(a).
- **Proteggere il servizio e l'integrità delle competizioni:** utilizziamo
  controlli degli accessi, log e verifiche delle incongruenze nei passi sulla
  base del nostro legittimo interesse a prevenire abusi e mantenere affidabili
  le classifiche. Quando tali verifiche comportano il trattamento dei dati sui
  passi, si applica anche il tuo consenso esplicito al trattamento dei dati
  relativi all'attività fisica.
- **Inviare comunicazioni di servizio:** i codici di accesso e i messaggi
  nell'app servono al funzionamento del servizio. Le categorie facoltative di
  notifiche nell'app possono essere disattivate nelle Impostazioni; anche il
  promemoria giornaliero sul dispositivo è facoltativo e locale.

Presti il consenso esplicito al trattamento dei dati sui passi selezionando la
relativa casella dopo aver visualizzato questa informativa. iOS chiede poi
separatamente se SCP può leggere il Conteggio passi tramite HealthKit.

Puoi revocare il consenso in qualsiasi momento revocando l'accesso HealthKit e
contattandoci, oppure eliminando l'account dalle Impostazioni. La revoca non
pregiudica la liceità dei trattamenti effettuati prima di essa. Poiché il
trattamento dei passi è necessario al servizio principale di sfide di SCP, al
momento non possiamo mantenere attivo un account privo dei dati sui passi dopo
la revoca del consenso.

## 4. Chi può vedere i dati all'interno di SCP

SCP è accessibile solo su invito, ma include funzioni social e alcuni dati
vengono condivisi con altri membri autenticati:

- Nell'attuale beta chiusa, **l'elenco dei profili è leggibile da ogni membro
  autenticato**. Comprende nickname, email, avanzamento del Rango e totale
  complessivo, obiettivo giornaliero, preferenze di visibilità e notifiche e
  metadati del consenso. Le normali schermate dell'app non mostrano ogni campo,
  ma l'attuale regola di accesso della beta consente ai membri autenticati di
  leggerli. Questa regola ampia dovrà essere resa più restrittiva prima che SCP
  si espanda oltre il gruppo fidato di invitati.
- L'elenco degli inviti, inclusi gli indirizzi email invitati e l'identità di chi
  ha invitato, è leggibile dai membri autenticati per evitare inviti duplicati.
- Un **totale giornaliero dei passi** sincronizzato è leggibile soltanto da te e
  dai membri accettati che condividono una sfida con te, esclusivamente per le
  date comprese in quella sfida.
- Partecipanti, squadre, calendari, punteggi e classifiche sono visibili in base
  alle regole di accesso di ciascuna sfida. Le bacheche di comunità e i risultati
  storici condivisi possono essere visibili a tutti i membri autenticati.
- I tuoi risultati conclusi, i trofei e le attività legate alle Imprese sono
  visibili agli altri membri quando l'impostazione **Bacheca dei Vanti** è
  attiva. Disattivandola nascondi i dati regolati da tale impostazione e
  impedisci la creazione di nuovi elementi pubblici nel feed attività, ma
  l'operazione potrebbe non rimuovere attività o notifiche già create.
- Le notifiche personali nell'app sono leggibili soltanto dal destinatario. Il
  feed attività della comunità è leggibile da tutti i membri autenticati.

Nessun contenuto di SCP è destinato a essere visibile sul web aperto. Non
vendiamo né concediamo in uso i dati dei membri, non mostriamo pubblicità e non
condividiamo dati derivati da HealthKit con inserzionisti o intermediari di dati.

## 5. Fornitori del servizio e localizzazione dei dati

Per il funzionamento di SCP utilizziamo i seguenti fornitori:

- **Supabase:** autenticazione, database Postgres ospitato nell'Unione europea e
  funzioni lato server. La Row Level Security del database limita l'accesso in
  base all'utente autenticato e al contesto della funzione utilizzata.
- **Google / Gmail:** invio dei codici di accesso monouso tramite un account
  Gmail dedicato a SCP.
- **Google Fonts:** l'app può scaricare i file dei caratteri Inter e Playfair
  Display dal servizio di distribuzione dei font di Google. Google può ricevere
  normali informazioni di connessione, come indirizzo IP e metadati della
  richiesta. Le richieste dei font non contengono i totali dei passi di SCP.
- **Apple:** HealthKit fornisce sul dispositivo la fonte del Conteggio passi;
  Apple può inoltre trattare informazioni relative alla distribuzione e alla
  diagnostica di TestFlight o App Store secondo le proprie condizioni. SCP non
  invia ad Apple il proprio database dei passi sincronizzati tramite TestFlight.

Questi fornitori possono trattare dati tecnici o dell'account limitati in altri
Paesi, secondo le proprie condizioni in materia di protezione dei dati e le
relative garanzie per i trasferimenti. Puoi contattarci per ulteriori
informazioni pertinenti ai tuoi dati.

## 6. Conservazione ed eliminazione dell'account

Conserviamo i dati degli account attivi finché sono necessari a fornire SCP.
Questa beta non applica ancora un periodo fisso di cancellazione automatica agli
account inattivi, alla cronologia delle competizioni, alle notifiche nell'app o
agli eventi del feed attività.

La funzione autonoma **Elimina il mio account** elimina definitivamente:

- l'utente di autenticazione Supabase e il profilo SCP, inclusi email, nickname,
  identificativi dell'account, registrazione del consenso, preferenze e
  abilitazioni;
- i passi giornalieri sincronizzati, le registrazioni delle incongruenze
  antifrode, le partecipazioni e i risultati individuali delle sfide, i registri
  di sprint e costanza, i seeding dei tornei e i valori dei passi nelle partite,
  le Imprese, le amicizie, le notifiche ricevute, i dati del Confratello del Mese
  e l'invito associato all'email dell'account;
- notifiche, eventi del feed attività e istantanee dei primati di gruppo che
  contengono il nickname del membro;
- gli incontri di lega che coinvolgono il membro, nonché la sua identità e i
  passi registrati nelle partite condivise dei tornei; e
- i promemoria programmati da SCP e le preferenze legate all'account sul
  dispositivo dal quale viene eseguita l'eliminazione.

Una sfida creata dal membro eliminato potrebbe essere ancora necessaria agli
altri partecipanti. In questo caso SCP conserva soltanto la sua struttura
meccanica condivisa: l'identificativo del creatore e i testi della sfida o del
trofeo inseriti dall'utente vengono rimossi. I totali di squadra o altri
risultati aggregati condivisi possono rimanere quando non identificano più né
sono collegabili al membro eliminato. Non viene creato un profilo segnaposto: il
profilo eliminato e il suo identificativo utente originario non rimangono nel
database pubblico di SCP.

I log operativi e i backup di Supabase, Apple o Google possono rimanere per i
periodi limitati stabiliti da tali fornitori prima di essere sovrascritti o
eliminati.

## 7. I tuoi diritti

Ove applicabile, puoi chiederci di:

- accedere ai dati personali che conserviamo su di te;
- correggere dati inesatti;
- cancellare i dati;
- limitare il trattamento o opporti ad esso;
- ottenere dati portabili; e
- revocare il consenso in qualsiasi momento.

Le Impostazioni includono un'esportazione autonoma in formato JSON contenente
il record di autenticazione e del profilo, il consenso e le preferenze, gli
inviti, i passi giornalieri, la cronologia antifrode, tutti i dati direttamente
collegati a sfide, leghe, squadre e tornei, le notifiche, le istantanee del feed
attività, le relazioni tra Confratelli, le Imprese, i titoli di gruppo e le
strutture condivise delle sfide necessarie a comprendere tali dati. Non include
i dati privati non pertinenti degli altri membri.

Invia le richieste a **sacraconfraternitadelpasso@gmail.com**. Potremmo dover
verificare che l'account sia effettivamente tuo. Puoi inoltre presentare reclamo
all'autorità per la protezione dei dati del luogo in cui vivi o lavori, come il
Garante per la protezione dei dati personali in Italia.

## 8. Sicurezza

SCP utilizza connessioni di rete cifrate, le impostazioni predefinite di
cifratura dei dati a riposo di Supabase, accesso autenticato e Row Level
Security del database. L'app è accessibile solo su invito e non espone ai membri
credenziali dirette del database con privilegi amministrativi. Nessun sistema
può garantire una sicurezza assoluta; contattaci se sospetti un accesso non
autorizzato.

## 9. Minori

SCP non è rivolta a persone di età inferiore a 16 anni e non deve essere
utilizzata da esse.

## 10. Modifiche a questa informativa

Quando questa informativa cambia, ne aggiorniamo il numero di versione e la data
di entrata in vigore. SCP memorizza la versione dell'informativa e la data e ora
del consenso associate a ciascun account. Quando una modifica sostanziale
richiede un nuovo consenso, l'app blocca la normale navigazione e chiede al
membro di esaminare e confermare esplicitamente la nuova versione prima di
proseguire.
