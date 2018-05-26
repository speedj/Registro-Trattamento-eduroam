### esempio di Registro del Trattamento per SP e IdP eduroam
GDPR Art. 30 L 119/52 Gazzetta ufficiale dell'Unione europea 4.5.2016

# a. Dati di contatto
Nome e dati di contatto del titolare del trattamento, del RPD (DPO) e, ove applicabile, del contitolare del trattamento, del rappre­sentante del titolare del trattamento.

# b. Finlità del trattamento

Il trattamento riguarda i dati dell’interessato appartenenti ad altre organizzazioni federate eduroam che si collega alla rete Wi-Fi di questa organizzazione ovvero quelli dell’interessato avente una identità digitale presso questa organizzazione e che si collega alla rete eduroam all’interno di questa organizzazione o di altre federate eduroam.
Interessa dati *non particolari* necessari all’identificazione e alla conseguente autorizzazione all’accesso dell'interessato alla rete eduroam.

# c1. Categorie di interessati
## IdP
Studenti, Docenti, Ricercatori, Personale TA, Affiliati esterni con contratto di fornitura
## SP
Persone omologhe identificate da enti di ricerca e istruzione federati eduroam a livello mondiale

# c2. Categorie di dati personali

## IdP
- **Personali identificativi**: Username, Mac Address, indirizzo IP
- **Correlati**: Istituzione di appartenenza, quantità di dati scambiati, nome AP di autenticazione, timestamp

## SP
Username (eventualmente anonimizzato), mac address, IP address, timestamp, eventuali altre informazioni fornite su decisione dell’IdP della Home Institution

# d. Categorie di destinatari (trasferimento)
## IdP
Organizzazioni federate eduroam a cui il dispositivo dell’interessato si collega o si è collegato
## SP
Organizzazioni federate eduroam a cui il dispositivo dell’interessato chiede di garantire l’accesso dalle reti eduroam della nostra organizzazione.

# e. Trasferimento extra UE (paesi terzi e org. internazionali)
- Per accertare, denunciare, porre rimedio a violazioni della eduroam policy o malfunzionamenti, tramite NRO verso altre NRO e Home Institution. Solo i dati necessari, non l’identità delle persone
- Richiesta di organi di polizia

# f. Periodo di conservazione dei dati (data retention)
- 3 mesi online per attività di troubleshooting, analisi di funzionamento del servizio, azioni di blocco account/dispositivo su segnalazione dei CERT e NRO
- Archiviazione per massimo 5 mesi offline per ragioni tecniche di backup di sistema

# g. Descrizione generale delle misure di sicurezza tecniche e organizzative
## ga. Pseudonimizzazione e la cifratura dei dati personali;
Viene usato un sistema di pseudonimizzazione dello username chiamato cui (Chargeable-User-Identity) per il trasferimento dei dati dei propri teressati. Gli username inoltre non sono "parlanti" e sono [numero di matricola] per i dipendenti e s[numero di account] per gli studenti.
## gb. Capacità di assicurare su base permanente la riservatezza, l'integrità, la disponibilità e la resilienza dei sistemi e dei servizi di trattamento;
Gli amministratori di sistema, individuati in numero di 4 hanno accessi distinti non privilegiati al sistema ridondato di due server in edifici diversi e possono eseguire operazioni privilegiate eseguendo un escaletion di permessi. Le operazioni di accesso ed elevazione dei permessi sono registrate localmente e su server remoto per più di un anno. 
## gc. Capacità di ripristinare tempestivamente la disponibilità e l'accesso dei dati personali in caso di incidente fisico o tecnico;
- Servizio ridondato su due server.
- Configurazione principale backuppata.
## gd. una procedura per testare, verificare e valutatare regolarmente l'efficacia delle misure tecniche e organizzative al fine di garantire la sicurezza del trattamento.
- Viene automaticamente testato il backup e il restore di un file giornalmente.
- Vengono tenuti dei grafici sui parametri di funzionamento dei sistemi.
- ...

----
----

# Addendum per la generazione dell'informativa
Art 13 commi 1 e 2 (IdP)

Art 14 commi 1 e 2 (SP)

Da pubblicare, ma è impossibile avere un consenso esplicito o  somministrarla al primo accesso o prima di esso.

## Dati di contatto
vedi Registro del trattamento lettera a
 nel solo caso di utenti di questa organizzazione.

## Finalità del trattamento 
- vedi Registro del trattamento lettera b
- [Riportare eventuale base giuridica del trattamento.]

## Categoria di dati personali necessari per l’erogazione del servizio
### IdP (utenti di questa organizzazione)
- Username (outer e inner), mac address
### SP (utenti ospiti)
- Username (outer), mac address, IP address, nome della rete, dati di performance e posizionamento
### Ulteriori dati raccolti
I seguenti dati sono raccolti dalle infrastrutture wireless e sebbene non siano di nostro interesse, siamo tecnicamente costretti a trattarli ugualmente:
- Net Application Profile
- Sistema operativo utilizzato

## Legittimi interessi del Titolare
- Perseguire il buon funzionamento del servizio per tutti e soli gli interessati aventi diritto, effettuare statistiche d'uso su base aggregata del servizio per lo stesso fine.
- Garantire la disponibilità della rete dell'organizzazione.
- Difesa in caso di contenziosi.
- ...

## Categorie di destinatari
- NRO, CERT e organizzazioni aderenti ad eduroam
- Autorità inquirenti su richiesta.

## Trasferimento extra UE (paesi terzi e org. internazionali)
- vedi Registro del trattamento lettera e
- Decisione di adeguatezza della Commissione assente in quanto legati a questo comportamento da contratto eduroam.

## Periodo di conservazione dei dati (data retention)
vedi Registro del trattamento lettera f

## Diritti dell'interessato
L'interessato ha il diritto di chiedere al titolare del trattamento:
- l'accesso ai dati personali dietro identificazione de visu
- la rettifica (non applicabile)
- la cancellazione (conflitto con legittimi interessi del titolare e possibilità tecniche)
- la limitazione del trattamento (obiezione pertinente e motivata)
- opporsi al trattamento (tramite obiezione pertinente e motivata)
- diritto alla portabilità dei dati (non applicabile, dimostrare l'interesse)

L'interessato ha il diritto di proporre reclamo a un'autorità di controllo;

In caso tu sia un nostro utente, sei obbligato ad identificrti attraverso il tuo account per accedere al servizio. Per il contratto che ci lega alla federazione eduroam non possiamo fornirti il servizio altrimenti.

I dati di collegamento possono inoltre essere utilizzati dal titolare in maniera aggregata per attività di troubleshooting, e statistiche sulla tipologia di dispositivi e utenti collegati.

## Fonte dei dati
### SP (utenti ospiti)
- Servizio eduroam della propria organizzazione

# Modalità dell’informativa
Asincrona, pubblicata su https://eduroam.<miaorganizzazione>.it/ senza consenso esplicito in quanto legati da contratto con NRO (un consenso esplicito preventivo violerebbe la eduroam policy)

Ai sensi del Regolamento Europeo L 119/52 Art. 14 comma 5 capo b

---
