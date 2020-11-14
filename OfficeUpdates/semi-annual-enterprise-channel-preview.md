---
title: Note sulla versione per i rilasci del Canale Enterprise semestrale (Anteprima) nel 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per i professionisti IT con le note sulla versione per i rilasci del Canale semestrale (mirato) per Microsoft 365 Apps nel 2020
ms.openlocfilehash: e448b5e1d0ea334401c9bd9c91291376f6579367
ms.sourcegitcommit: 8e74984d0c36475374c34e76ed29c5d1ad81d971
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/10/2020
ms.locfileid: "48990055"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a>Note sulla versione per i rilasci del Canale Enterprise semestrale (Anteprima) nel 2020

Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale Enterprise semestrale (Anteprima) del 2020 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.

> [!IMPORTANT]
> Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Canale Enterprise mensile) e la modifica dei nomi dei canali di aggiornamento già presenti. Per ulteriori informazioni, [leggere questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441).


## <a name="version-2008-november-10"></a>Versione 2008: 10 novembre
*La versione prevista è la numero 2008 (Build 13127.20760).*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel

- È stato risolto un problema per cui alcune funzioni avrebbero avuto un risultato errato dopo il caricamento di una cartella di lavoro.


- È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto, correlato ai riferimenti del componente aggiuntivo XLAM e agli intervalli denominati.


- È stato risolto un problema relativo all'uso di una macro per impostare la proprietà FormulaR1C1 per un intervallo. I riferimenti di cella erano errati se un foglio grafico era il foglio attivo.


- È stato risolto un problema che causava la visualizzazione del messaggio "Excel ha esaurito le risorse durante il tentativo di calcolare una o più formule".


- È stato risolto un problema per cui, quando si selezionava lo spagnolo come lingua di Office, gli elenchi di convalida dei dati non mostravano tutti gli elementi.


- È stato risolto un problema che poteva causare un blocco durante l'aggiornamento delle tabelle pivot OLAP.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui gli utenti ora possono disabilitare IRM (Information Rights Management) per Outlook senza doverlo disabilitare per il resto delle applicazioni di Office.


- È stato risolto un problema che impediva agli utenti di concedere le autorizzazioni di Editor ai delegati.


- È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto se gli utenti selezionavano un risultato della ricerca.


- È stato risolto un problema per cui le ricerche nei calendari di gruppo non restituivano alcun risultato.


- È stato risolto un problema che provocava errori intermittenti quando i delegati aprivano cartelle condivise in altre cassette postali.


- È stato risolto un problema che ha causato l'invio di messaggi di posta elettronica generati automaticamente con un corpo vuoto quando la riga dell'oggetto è vuota.


- È stato risolto un problema per cui le intestazioni dei messaggi in cinese erano incomprensibili in caso di risposta o inoltro.

- È stato risolto un problema per cui le esperienze connesse facoltative bloccavano il caricamento dei componenti aggiuntivi Web.  <br />Vedere i dettagli nel [post di blog](https://developer.microsoft.com/it-IT/office/blogs/outlook-add-ins-and-optional-connected-experiences/)


### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui il componente aggiuntivo per i contenuti Forms non veniva eseguito dopo l'inserimento finché l'utente non faceva clic su un'altra diapositiva per visualizzarlo.


### <a name="office-suite"></a>Famiglia di prodotti di Office

- È stato risolto un problema per i clienti commerciali che usano System Center Configuration Manager o altri strumenti di gestione per l'aggiornamento di Office tramite Prevenzione della perdita di dati degli endpoint di Microsoft 365.

- Risolve un problema relativo al non funzionamento dell'API di messaggistica per i componenti aggiuntivi di Office.



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO BUG)

## <a name="version-2008-october-13"></a>Versione 2008: 13 ottobre
*Versione 2008 (Build 13127.20638)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato corretto un bug relativo alle API PivotDateFilter, per cui le condizioni di filtro "prima" e "dopo" erano invertite.


- È stato risolto un problema che impediva agli utenti di modificare un filtro della tabella pivot perché era configurato su un valore non più presente nel database Analysis Services.


- È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo quando si utilizzava l'Analisi rapida dopo aver bloccato la riga superiore del foglio.


- È stato risolto un problema che poteva generare un avviso su una cartella di lavoro danneggiata se conteneva formule utilizzando IFNA ().


### <a name="outlook"></a>Outlook

- Risolve un problema che impediva agli utenti di chiudere i calendari condivisi facendo clic sulla "X" nell'angolo.


- È stato risolto un problema per cui l'impostazione "Attiva miglioramenti calendari condivisi " talvolta non veniva applicata ai calendari condivisi esistenti.


- È stato risolto un problema per cui, all'apertura di un allegato cloud, gli utenti visualizzavano un messaggio di errore nella pagina Safelinks anziché il documento che stavano provando ad aprire.


- Risolve un problema relativo alle prestazioni con il caricamento degli allegati.


### <a name="powerpoint"></a>PowerPoint

- Questa modifica risolve un problema della funzionalità Esporta in GIF animata per cui, facendo clic sul pulsante Esporta, l'esportazione non veniva eseguita.


- Correzione di sicurezza che risolve un problema che disabilitava le protezioni IRM aprendo un file di PowerPoint in Visualizzazione protetta.

- È stato risolto un problema nella finestra di dialogo Impostazioni azione che causava un arresto anomalo dell'app PowerPoint.

### <a name="visio"></a>Visio

- È stato risolto un problema che causava l'arresto anomalo dell'anteprima live durante l'allineamento del testo.


### <a name="word"></a>Word

- È stato risolto un problema che causava l'arresto anomalo all'apertura di alcuni messaggi di posta elettronica molto grandi.


- È stato risolto un problema per cui poteva verificarsi un arresto anomalo all'apertura di un documento.


- È stato risolto un problema che poteva causare un arresto anomalo all'avvio di Word.


- È stato risolto un problema con la finestra di dialogo raccolta Stili.


### <a name="office-suite"></a>Famiglia di prodotti Office

- Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner. I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".


- È stato risolto un problema che causava un utilizzo elevato della CPU in modalità inattiva con GIF/modelli animati 3D


- Questa modifica risolve il problema dell'arresto anomalo all'avvio delle app Office dovuto al mancato caricamento del file d2d1.dll.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-08"></a>Versione 2008: 8 settembre
*Versione 2008 (Build 13127.20408)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Accesso

- **Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla. Cercare e sostituire il testo nella visualizzazione SQL. Selezionare più tabelle nella finestra Relazioni.

- **Aggiungere tabelle con meno clic** : usare il riquadro attività Aggiungere tabelle, che resta aperto mentre si lavora, per aggiungere tabelle a relazioni e query. [Altre informazioni](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate. [Altre informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Creare tabelle pivot da set di documenti in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di documenti archiviati in Power BI in pochi click.  Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI. Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI. [Altre informazioni](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

- **Le tue funzioni Excel preferite sono diventate più veloci:** le funzioni SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS e MINIFS sono più veloci che mai. Passa alla riga inferiore più rapidamente. Provane una ora.

- **Miglioramenti di RealTimeData (RTD):** in Office 365 versione 2002 canale mensile e successiva, la funzione RealTimeData (RTD) di Excel è molto più veloce rispetto a Excel 2010 per il calcolo dei dati nel foglio di calcolo. Sono stati rimossi i colli di bottiglia nelle strutture di memoria e di dati sottostanti oltre a renderlo thread-safe per consentirne il calcolo su tutti i thread disponibili di ricalcolo multithread (MTR).

### <a name="outlook"></a>Outlook

- **Gli aggiornamenti dei calendari condivisi sono più veloci:** Outlook può aggiornare i calendari condivisi in Office 365 usando l'API REST. Attivare l'anteprima per aggiornamenti più rapidi e affidabili ai calendari condivisi.

- **Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai. [Altre informazioni](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo. I messaggi trascinati verranno condivisi con tutti i membri del gruppo.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **Aggiornamento del calendario:** aggiornamenti visivi che rendono il calendario più facile da analizzare. [Altre informazioni](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online. Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.

- **Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web? Outlook ora consente di rimanere connessi in scenari di questo tipo.<br />Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/outlook-on-public-wi-fi-networks-just-got-easier)

- **Suggerimenti di posta elettronica per cercare una persona:** quando si digita il nome di una persona nella casella di ricerca, i messaggi di posta elettronica più importanti saranno inclusi nei suggerimenti di ricerca. [Altre informazioni](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a>PowerPoint

- **Ottenere l'attenzione tramite \@menzioni:** è possibile usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input. [Altre informazioni](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate. [Altre informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **GIF in un batter d'occhio:** una diapositiva, un frame. Crea facilmente GIF a ripetizione continua in PowerPoint. [Altre informazioni](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)

- **Diagrammi migliori:** connettori più efficienti e un processo di conversione dell'input penna più fluido consentono di dare forma alle idee più facilmente. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Commenti:** la nuova esperienza di commento in PowerPoint consente di individuare e aggiungere i commenti ai documenti in modo semplice e rapido. È possibile modernizzare i flussi di lavoro di collaborazione con nuove funzionalità, come l'ancoraggio di commenti, la risoluzione, le attività, le notifiche di menzione migliorate e molto altro. [Altre informazioni](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- **Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione. [Altre informazioni](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Collegamento a una diapositiva:** è possibile chiedere a un collega di contribuire a una presentazione e indirizzalo direttamente alla diapositiva per la quale serve assistenza. [Altre informazioni](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)

- **Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida. I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.


### <a name="word"></a>Word

- **Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate. [Altre informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Lazo dell'input penna:** lo strumento Lazo della scheda Disegno consente di selezionare gli oggetti disegnati con l'input penna. È possibile selezionare singoli tratti o parole intere. [Altre informazioni](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Conferma dell'azione nelle utilità per la lettura dello schermo:** la conferma dell'azione rappresenta un requisito importante per l'accessibilità. Con l'introduzione di una nuova API di notifica di Windows, è ora possibile avvisare gli utenti delle utilità per la lettura dello schermo della riuscita delle azioni. I comandi taglia, copia, incolla, grassetto, corsivo, sottolineato, annulla, ripristina, correzione automatica e maiuscole automatiche ora sono tutti annunciati agli utenti dell'Assistente vocale in Win32 Word. Per abilitare questa funzionalità, attivare l'Assistente vocale premendo il tasto Windows + CTRL + INVIO.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)

### <a name="office-suite"></a>Applicazioni Office

- **Etichette di riservatezza** : è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema relativo all'inserimento di tabelle SQL collegate che includono un campo identità, ad esempio numerazione automatica.

- È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.

- È stato risolto un problema per cui ora è possibile usare il tipo di dati data/ora esteso nel codice senza subire alcun arresto anomalo dell'app.

- È stato risolto un problema che consente ora di tornare alla versione di Access più aggiornata e usare DAO/VBA per gestire e modificare un tipo di dati decimale.

- Questa correzione risolve il problema per cui il tentativo di eseguire determinate query in precedenza generava il messaggio di errore 'La query è troppo complessa.'

- Il problema è ora risolto per Access, ma analizzeremo le nostre altre interfacce per garantire che il problema non persista. Il team notificherà i prossimi aggiornamenti; apprezziamo la vostra pazienza.

- Questo problema è stato risolto. ora è possibile usare il driver ODBC all'esterno delle applicazioni a portata di clic di Office.

### <a name="excel"></a>Excel

- È possibile che si sia verificata la classificazione automatica dei documenti per le cartelle di lavoro in modalità di sola lettura.

- È stato risolto un problema che provocava un arresto anomalo quando si provava a creare una connessione dati dopo aver disconnesso il proprio account.

- È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo nel tentativo di inserire tabelle pivot in un foglio grafico.

- È possibile che si verifichi un errore quando si prova a salvare un file che contiene una formula usando la funzione LET().

- È stato risolto un problema per cui Excel potrebbe arrestarsi in modo anomalo in determinate circostanze quando si usa Copia formato.

- È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.

- È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.

- È stato risolto un problema per cui, in alcuni casi, se si faceva clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro veniva nascosta.

- È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.

- Application.Evaluate (VBA) in alcuni casi non funzionava per le funzioni definite dall'utente.

- Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.

- È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.

- Questo risolve un problema in cui le connessioni create dal provider di dati SQL nelle versioni precedenti di Office imposterebbero le proprietà della tabella interna in modo diverso da Office 365. Ciò ha causato la disabilitazione dell'elenco a discesa Anteprima tabella/Editor di query per i file con connessioni create nelle versioni precedenti di Office quando sono stati aperti utilizzando Office 365.

- È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.

- È stato risolto un problema per cui l’input penna poteva far sì che Excel smettesse di rispondere.

### <a name="onenote"></a>OneNote

- Informazioni per gli utenti tramite la Barra informazioni sulle rettifiche temporanee in Microsoft OneNote che consentono di migliorare la sincronizzazione e la disponibilità dei servizi durante i picchi di utilizzo in tutto il mondo.

- Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.

- È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.

- Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016. Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.

- Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016. I blocchi appunti locali non vengono interessati da questa operazione.

- Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza con cui vengono create le cronologie delle versioni delle pagine.

- Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente lo spostamento delle pagine nel Cestino. Agli utenti che vogliono eliminare una pagina verrà mostrata una finestra di dialogo in cui viene chiesto se si vuole eliminare la pagina definitivamente.

### <a name="outlook"></a>Outlook

- Risolve un problema che faceva sì che gli utenti che tentavano di creare una convocazione di riunione da un account secondario aggiunto al loro profilo non vedessero uno spazio da: campo al posto del loro indirizzo e-mail.

- Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.

- È stato risolto un problema che causava il mancato retrazione delle riunioni dal calendario di un responsabile in alcuni casi.

- È stato risolto un problema che impediva ad alcuni utenti della funzionalità Miglioramenti dei Calendar - Calendario di Outlook condivisi di visualizzare un calendario condiviso appena aggiunto.

- Risolve un problema che faceva sì che gli utenti sperimentassero occasionalmente degli arresti anomali durante l’interazione con gli allegati cloud.

- È stato risolto un problema che causava l'arresto anomalo di CLP cambiando l'indirizzo Da in una risposta da un contesto protetto a uno non protetto.

- È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.

- È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.

- È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.

- È stato risolto un problema a causa del quale gli utenti visualizzavano la data di creazione degli allegati copiati nel file system tramite il trascinamento fissata all’1 gennaio 4501.

- È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.

- È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'aggiornamento delle regole in Outlook.

- È stato risolto un problema che causava il mancato recupero di suggerimenti per la ricerca da parte di Outlook.

- È stato risolto un problema a causa del quale gli utenti dei miglioramenti del Calendario di Outlook condivisi visualizzavano errori di Calendario di Outlook.

- È stato risolto un problema che causava blocchi o arresti intermittenti in alcune situazioni.

- È stato risolto un problema che causava l'arresto anomalo di quattro o più messaggi di posta elettronica da un account POP con l'opzione "solo intestazioni di download" selezionata.

- Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.

- È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un manager.

- È stato risolto un problema che causava arresti anomali nelle applicazioni MAPI di terze parti.

- È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.

- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.

- È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso "Stato dell’antivirus: non valido". Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato installato correttamente l’antivirus.

- È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.

- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.

- È stato risolto un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.

- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.

- È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.

- È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione.

- È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente pianificazione da parte di alcuni utenti.

- È stato risolto un problema che causava occasionalmente l’arresto anomalo degli utenti durante il recupero delle informazioni personali.

- Questo risolve un problema che causava agli utenti degli arresti anomali occasionali durante la modifica dei destinatari.

- Risolve un problema che consente agli utenti di visualizzare anomalie durante l'uso della visualizzazione compatta.

- È stato risolto un problema che causava agli utenti di Outlook la comparsa di errori connessi con lo spostamento in modalità di visualizzazione compatta.

- È stato risolto un problema che causava il mancato recapito del menu di scelta rapida.

- È stato risolto un problema che causava la ricezione dell'errore seguente quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio, "Alcuni dei file in questa pagina Web non sono nella posizione prevista. Scaricarli comunque? Se si è sicuri che la pagina Web sia una fonte attendibile, fare clic su Sì"

- Risolve un problema che causava un blocco uscendo da Outlook.

- È stato risolto un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.

- È stato risolto un problema che causava problemi di formattazione negli avvisi di notifica degli eventi imprevisti.

- È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.

- È stato risolto un problema relativo al comando copia e incolla immagine SVG.

- Questo risolve un problema che causava agli utenti degli arresti anomali occasionali durante la modifica dei destinatari.

- È stato risolto un problema relativo al comando copia e incolla immagine SVG.


### <a name="powerpoint"></a>PowerPoint

- È stato risolto un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.

- È stato risolto un problema relativo all'arresto anomalo di PowerPoint.

- È stato risolto un problema relativo all'arresto anomalo del riquadro suggerimenti.

### <a name="project"></a>Project

- È stato risolto un problema per cui, quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un evento ProjectBeforeTaskChange aggiuntivo.

- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.

- È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.

- È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.

- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.

- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.

- È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.

- È stato risolto un problema per cui non era possibile aprire progetti nel client Project per desktop da Project Web App con gli URL con suffisso .com.

- È stato risolto un problema per cui, incollando un'attività con più dipendenze, non tutte le dipendenze vengono copiate correttamente.

- È stato risolto un problema per cui non era possibile salvare un file PDF/XPS da Project a una raccolta documenti di SharePoint.

- È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.

- È stato risolto un problema per cui, se una risorsa aveva più di una tabella tariffe definita, il costo residuo non sempre veniva calcolato correttamente.

- È stato risolto un problema per cui la data di fine del progetto non viene aggiornata per i progetti collegati all'elenco attività di SharePoint.

- È stato risolto un problema per cui l'attività selezionata nella finestra di dialogo Assegna risorse non è la stessa selezionata nella visualizzazione Bacheca attività.

- È stato risolto un problema che impediva l’apertura di un progetto che aveva ottenuto uno stato non valido.

### <a name="skype"></a>Skype

- Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni. In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola. Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.

- Il tono della pelle dell’emoticon che balla modificato su un colorito neutro.

### <a name="word"></a>Word

- È stato risolto un problema durante l'apertura di documenti di Word tramite consegna di documenti personalizzati (aspx) con URL contenente un componente di query.

- Questa modifica consente di risolvere un problema in cui le applicazioni di Office possono bloccarsi in uno stato di errore di salvataggio silenzioso dopo una sessione di creazione condivisa precedente.

- È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio.

- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.

- È stato risolto un problema relativo al comando copia e incolla immagine SVG.

- È stato risolto un problema per cui l'utente poteva perdere il contenuto quando ridimensionava una forma.

- È stato risolto un problema per cui gli stili di base non venivano aggiornati con lo stile normale.

- È stato risolto un problema per cui la macro AutoOpen veniva eseguita prima di AutoExec.

- È stato risolto un problema relativo al comando copia e incolla immagine SVG.

- È stato risolto un problema che può aver causato un arresto anomalo durante il trascinamento del contenuto dall'app.


### <a name="office-suite"></a>Famiglia di prodotti Office

- Per il riquadro Condividi basato su servizi non Web precedente, dopo aver chiuso il documento mentre il riquadro Condividi è aperto potrebbe verificarsi un arresto anomalo. Questo problema è stato risolto.

- È stato risolto un problema di tempistiche che poteva causare un arresto anomalo durante la chiusura dei file di Office.

- È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.

- È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. 

- È stato risolto un problema a portata di clic che causava un errore nell'aggiornamento durante il tentativo di creare collegamenti simbolici reali.

- È stato risolto un problema che causava la visualizzazione di un messaggio di runtime, anche se la transizione al prodotto completo era stata completata. Il problema è stato corretto verificando che il servizio calcolasse correttamente i prodotti aggiunti. I nuovi prodotti aggiunti sono stati filtrati (verificando che esistano anche nella nuova configurazione) e aggiunti alla fine degli ID di rilascio prodotti esistenti.

- È stato risolto un problema per cui gli elementi o il contenuto dell'interfaccia utente non erano visualizzati dagli utenti in determinate condizioni, in particolare con l’entrata e l’uscita dalla visualizzazione Relatore o l'utilizzo di più monitor.

- Questa modifica risolve potenziali blocchi che si verificano durante il caricamento e la riproduzione di contenuti animati, ad esempio GIF o modelli 3D.

- Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.

- Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.

- È stato risolto un problema di arresto imprevisto con l'host di Office in Windows, per cui un componente aggiuntivo viene attivato quando il valore del registro TabProcGrowth è di tipo REG_SZ.

- L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero. La modifica potrebbe risolvere il problema.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-august-11"></a>Versione 2002: 11 agosto
*Versione 2002 (Build 12527.20988)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema che impediva di modificare i file aperti in modalità "Consigliata sola lettura".

### <a name="onenote"></a>OneNote

- Sono state rimosse le chiamate di identità ridondanti per ridurre l'utilizzo delle risorse

- È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.

- Sono state migliorate la funzionalità di rilevamento di errori e la qualità dell'esperienza di sincronizzazione.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un notevole problema di prestazioni durante l'avvio di Outlook per alcuni tenant.

### <a name="skype"></a>Skype

- È stato risolto un problema che causava un errore di avvio della condivisione dello schermo quando un client Skype for Business a 32 bit era in uso per diversi giorni.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui, se il salvataggio automatico era disattivato con i criteri di gruppo, quando si aprivano alcuni documenti per visualizzare il contenuto più recente sul server bisognava fare clic su "Aggiornamenti disponibili".



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a>Versione 2002: 14 luglio
*Versione 2002 (Build 12527.20880)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Velocizzato il caricamento dei file disponibili nella cartella locale di OneDrive.

- È stato risolto un problema per cui il codice XML CustomUI per una scheda della barra multifunzione personalizzata veniva rimosso salvando in SharePoint/OneDrive.

- È stato risolto un problema per cui veniva visualizzato il messaggio di errore "Questa cartella di lavoro non può essere chiusa in quanto esiste un'altra cartella di lavoro che fa riferimento ad essa", perché i componenti aggiuntivi venivano caricati in ordine alfabetico anziché in un ordine specificato dall'utente.

- È stato risolto un problema per cui una cartella di lavoro poteva essere impostata come nascosta facendo clic su un collegamento ipertestuale a un punto una cartella di lavoro già aperta.

- È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappati anziché indirizzi universali.

- Sono state migliorate le prestazioni associate all'eliminazione di colonne con celle unite.

- È stato risolto un problema che causava la ripetizione dei nomi delle stampanti nell'elenco all'interno della finestra di dialogo Stampa.

- È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.


### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante inserito attraverso l’IME, quando venivano usati più monitor con risoluzioni diverse.

- È stato risolto un problema per cui appuntamenti o riunioni ricorrenti venivano visualizzati al momento sbagliato avvicinandosi al momento di cambiare la definizione del fuso orario.

- È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'aggiornamento delle regole in Outlook.

- Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.

- È stato risolto un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.

- È stato risolto un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.

- È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un responsabile.

- È stato risolto un problema per cui il corpo di un messaggio NDR passava da Unicode a ASCII dopo aver modificato l'oggetto.

- È stato risolto un problema che causava un arresto anomalo quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo della barra multifunzione.

- È stato risolto un problema che impediva agli utenti di inviare messaggi di posta elettronica a una lista di distribuzione personale.

- È stato risolto un problema che causava la mancata aggiunta di collegamenti ai messaggi di posta elettronica con l'autorizzazione predefinita del tenant corretta quando questa era configurata su "chiunque".

- È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.

### <a name="word"></a>Word

- È stato risolto un problema relativo alla creazione condivisa abilitando il criterio FileBlick\Word2007Files.

- È stato risolto un problema per cui le parti rapide di Word non funzionavano aggiungendo un campo di ricerca rinominato.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui gli utenti riscontravano un utilizzo eccessivo della rete e della CPU durante la creazione condivisa in file di PowerPoint di grandi dimensioni.

- È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. 

- È stato risolto un problema di arresto imprevisto con l'host di Office in Windows, per cui un componente aggiuntivo viene attivato quando il valore del registro TabProcGrowth è di tipo REG_SZ.


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO BUG)

## <a name="version-2002-june-09"></a>Versione 2002: giugno 09
*Versione 2002 (Build 12527.20720)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.

- È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.

- È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.

- Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.

- L'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.

- È stato risolto un problema per cui un simbolo @ che avvia una formula verrebbe considerato come operatore di intersezione implicito.

### <a name="outlook"></a>Outlook

- Consente di partecipare a una riunione di Teams direttamente tramite il client nativo teams.

- È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.

- È stato risolto un problema che causava l'installazione errata dell'emulazione del browser nell'ambito del mancato completamento della richiesta di autenticazione di Gmail.

- È stato risolto un problema che restituiva agli utenti di Outlook sui sistemi operativi del server l'errore "stato antivirus: non valido. Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato configurato in modo appropriato.

### <a name="word"></a>Word

- È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.

### <a name="office-suite"></a>Applicazioni Office

- Il problema è stato risolto aggiornando i nomi dei canali nella visualizzazione backstage ai nuovi nomi dei canali nel fork 2020 gennaio.

- Il problema è stato risolto e in futuro, se un dispositivo viene gestito da criteri, non chiamerà l'API DMS Audience.

- È stato risolto il problema relativo alla rimozione incompleta nell'ambito dell'aggiunta e della rimozione di app in una singola operazione.

- L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero. La modifica potrebbe risolvere il problema.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2002-may-12"></a>Versione 2002: 12 maggio
*Versione 2002 (Build 12527.20612)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel

- Aprire una cartella di lavoro con riferimenti a molte altre cartelle di lavoro, in particolare con finestre nascoste, risulterebbe un'operazione piuttosto lenta.

- In alcuni casi, l'apertura di file CSV impiega più tempo del previsto.

- In alcuni casi, Excel potrebbe arrestarsi in modo anomalo quando si passa da una cartella di lavoro a un'altra con livelli di zoom diversi.

- È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.

- I dati copiati da una colonna filtrata in base al colore a volte non vengono incollati correttamente.

- È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.

- Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.

- È stato risolto un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambiava in modo imprevisto in caso di salvataggio e riapertura di un file.

- Se si usa un Range.Value e un Range.Value2 (VBA), le formule vengono immesse come matrici dinamiche.

### <a name="onenote"></a>OneNote

- Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.

- Visualizza una notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.

- Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente il numero e la frequenza di sincronizzazione delle pagine della cronologia versioni di OneNote 2016.

- Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente il cestino in OneNote 2016. Quando un utente prova a eliminare dati che normalmente verrebbero spostati nel cestino, all'utente verrà chiesto se vuole mantenere o eliminare definitamente il file.

- Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.

- Miglioramento della sincronizzazione e della stabilità del servizio rimandando temporaneamente il download di immagini e file incorporati in blocchi appunti online finché l'utente esplora la pagina in OneNote 2016.

- Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016. I blocchi appunti locali non vengono interessati da questa operazione.

- Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016. Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.

- È stato risolto un problema che causava un arresto anomalo quando si cerca di aprire file .msg e .oft dopo un aggiornamento di Windows.

- È stato risolto un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.

- Questo aggiornamento consente di risolvere un problema di Microsoft Outlook che non visualizza l'etichetta di riservatezza corrente durante la visualizzazione o la creazione di messaggi.

- È stato risolto un problema che impediva agli utenti di inviare messaggi di posta elettronica a una lista di distribuzione personale.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema relativo all'inoltro della messaggistica corretta per gli utenti che aprono una copia di un file con commenti migliorati.

### <a name="word"></a>Word

- È stato risolto il problema per cui Access e Publisher potrebbero non essere avviati correttamente a seconda delle lingue installate.

- È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.

- È stato risolto un problema che si verificava unendo due documenti in uno.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Si tratta di una soluzione per il blocco della rete da parte dell'app di Project quando il file viene memorizzato nella cache del client.

- Il problema è stato risolto quando un'operazione interna genera un'eccezione in caso di errore anziché registrare e continuare. Gli utenti interessati non riscontreranno più il blocco della ricezione degli aggiornamenti.

- Ciò assicura che la struttura disegnata funzioni correttamente nella barra multifunzione.

- È stato risolto un problema che si verificava durante l'apertura di file da posizioni locali con alcune configurazioni proxy specifiche.

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

- Questo aggiornamento consente di risolvere un problema di Microsoft Word per il quale un testo più lungo di 255 caratteri inserito durante l'applicazione di un'etichetta di riservatezza non può essere identificato e rimosso in seguito modificando o rimuovendo l'etichetta se il criterio di etichetta applica un'intestazione, un piè di pagina o una filigrana.

- È stato risolto un problema che causa l'arresto anomalo durante le sessioni di handoff di Office ed è stata migliorata l'affidabilità dell'esperienza utente.  

- Questo bug aggiorna l'endpoint url di Enhanced Configuration Service (ECS). Richiamare questo nuovo endpoint ha un tasso di successo maggiore per recuperare dati dall'ECS.

[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-2002-april-14"></a>Versione 2002: 14 aprile
*Versione 2002 (Build 12527.20442)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti. [Altre informazioni](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE.  [Altre informazioni](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X.  
  [Altre informazioni](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- In alcuni casi, Excel si arrestava in modo anomalo alla riapertura di una cartella di lavoro incorporata in Word o PowerPoint.

- Durante il salvataggio in formato CSV, in alcuni casi Excel univa tutte le colonne in una singola colonna.

- L'uso di Range.ClearContents in un intervallo in un foglio protetto poteva richiedere più tempo del previsto.

- È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.

- Le macro VBA che interagiscono con la barra multifunzione possono essere eseguite con ScreenUpdating inaspettatamente impostato su True.

- È stato risolto un problema per cui i collegamenti esterni non vengono aggiornati durante il riempimento (copia in basso o tra fogli di lavoro) se la cartella di lavoro di origine è chiusa.

- L'uso di Application.Evaluate di VBA talvolta non funzionava per le funzioni definite dall'utente.

- È stato risolto un problema di prestazioni durante la creazione di grafici dai modelli.


### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava l'espansione improvvisa dell'intestazione del gruppo in alcuni scenari.

- È stato risolto un problema che causava un arresto anomalo selezionando alcuni risultati della ricerca.

- È stato risolto un problema che causava un arresto anomalo usando il pulsante X del mouse.

- È stato risolto un problema che causava l'assenza del pulsante Salva nel cloud da Strumenti allegati.

### <a name="powerpoint"></a>PowerPoint

- È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.


### <a name="project"></a>Project

- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.

### <a name="word"></a>Word

- È stato risolto un problema che causava un arresto anomalo usando il pulsante X del mouse.

- È stato risolto un problema relativo all'adattamento del testo in una tabella.

- È stato risolto un problema per cui le righe orizzontali inserite non sono più brevi e centrate.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a>Versione 2002: 10 marzo
*Versione 2002 (Build 12527.20278)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Trovare velocemente le tabelle collegate:** la nostra nuova casella di ricerca rende molto più facile trovare le tabelle collegate. [Altre informazioni](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Ottenere l'attenzione tramite \@menzioni:** è possibile usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input. [Altre informazioni](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Trovare gli elementi cercati:** è possibile cercare comandi, persone, file, foto, notizie e molto altro ancora. [Altre informazioni](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Creare schizzi** : è possibile conferire un aspetto informale alle forme di Office incluse nella cartella di lavoro, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **Concentrarsi su ciò che resta da fare:** selezionare Risolvi per comprimere i commenti e far risaltare quelli ancora non risolti.

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel. [Altre informazioni](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Leggere e rispondere all'istante:** è possibile rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.

- **Ottenere le statistiche sulla cartella di lavoro:** le statistiche della cartella di lavoro forniscono una panoramica del contenuto di una cartella di lavoro, per facilitarne la ricerca.

- **Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone. Per scoprirle, scegliere Inserisci > Icone. [Altre informazioni](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a>Outlook

- **Connessione della rete LinkedIn a Outlook:** connessione sicura degli account LinkedIn all'account Microsoft per visualizzare le informazioni dei profili LinkedIn direttamente nella scheda Utenti. [Altre informazioni](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- **Tutte le opzioni di crittografia in un'unica posizione:** basta passare a Opzioni > Crittografa per scegliere come proteggere il messaggio di posta elettronica. [Altre informazioni](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)

- **Il menu Inserisci collegamento in Outlook inserisce un collegamento con l'autorizzazione definita dall'amministratore tenant:** un collegamento dall'elenco dei file usati di recenti in Inserisci collegamento in Outlook inseriva un collegamento che funzionava solo per gli utenti che avevano già le relative autorizzazioni. Questo causava spesso uno scambio di messaggi tra gli utenti per richiedere l'accesso a un documento. Questa esperienza è stata aggiornata in modo tale che il collegamento venga inserito con l'autorizzazione predefinita impostata dall'amministratore tenant. Per MSIT si tratta dell’opzione "L’organizzazione può modificare", pertanto tutti gli utenti interni che riceveranno un collegamento condiviso in questo modo saranno in grado di accedervi.

- **Cercare testo contenente errori di ortografia o di digitazione:** Outlook troverà il testo cercato anche quando l'ortografia non è corretta.

- **I messaggi di phishing sono facilmente individuabili:** la posta indesiderata e i messaggi di phishing hanno un aspetto diverso, in modo da poterli identificare e rimuovere facilmente dalla posta in arrivo.

- **Protezione avanzata dalle minacce:** con Office 365 Advanced Threat Protection, si è protetti dalle minacce tramite collegamenti ipertestuali negli oggetti di posta elettronica, messaggi allegati, messaggi firmati, percorsi di rete e così via.

- **Aggiunta della funzionalità Input penna:** è possibile scarabocchiare sopra le immagini o aggiungere un'area di disegno per inviare idee con l'input penna. [Altre informazioni](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- **Visualizza i messaggi rilevanti nei risultati della ricerca:** Outlook analizza i termini di ricerca e visualizza i messaggi di posta elettronica più importanti nella parte superiore dei risultati della ricerca. I risultati saranno ordinati anche per data nella sezione Risultati principali. [Altre informazioni](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- **Suggerimenti per il luogo delle riunioni:** è sufficiente iniziare a scrivere nella riga Luogo durante la pianificazione di appuntamenti e riunioni e Outlook suggerirà sale, indirizzi e altri luoghi recenti. [Altre informazioni](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Possibilità di visualizzare più messaggi sullo schermo:** Selezionare Visualizza > Usa spazio più stretto per regolare la spaziatura tra i messaggi. [Altre informazioni](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- **Vedere i messaggi sotto una luce diversa:** usare il pulsante Sole/Luna per utilizzare lo sfondo chiaro o lo sfondo scuro nel riquadro di lettura. [Altre informazioni](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- **Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone. Per scoprirle, scegliere Inserisci > Icone. [Altre informazioni](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a>PowerPoint

- **Collaborazione in tempo reale veloce in PowerPoint:** è possibile collaborare in tempo reale rapidamente in PowerPoint

- **Nuovi strumenti di correzione:** niente più preoccupazione per le parole. PowerPoint offre suggerimenti relativi a grammatica e ortografia. [Altre informazioni](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- **Sottotitoli e sottotitoli in tempo reale:** le parole del relatore vengono visualizzate automaticamente sullo schermo come sottotitoli o tradotti in sottotitoli nella lingua scelta. [Altre informazioni](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **La formattazione dei calcoli diventa automatica:** le espressioni matematiche scritte a mano vengono convertite in caratteri standard. Per iniziare, basta selezionare le note scritte a mano e scegliere Da input penna a testo matematico. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora. [Altre informazioni](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Trovare e correggere titoli di diapositive mancanti:** i titoli delle diapositive ottimizzano la presentazione e rendono le diapositive accessibili per tutti gli utenti, anche con diverse abilità. L’opzione Verifica accessibilità mostra dove mancano i titoli in modo da aggiungerli in pochi secondi. [Altre informazioni](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Creare schizzi** : è possibile conferire un aspetto informale alle forme di Office incluse nella presentazione, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **Salvare un'illustrazione in formato SVG:** è possibile salvare un grafico, una forma o un'altra illustrazione in formato SVG (Scalable Vector Graphic), che può essere ridimensionato senza perdita di qualità dell'immagine. [Altre informazioni](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Stampa dei numeri delle diapositive negli stampati:** i numeri delle diapositive vengono inclusi automaticamente negli stampati. Lasciarli attivati o disattivarli è a discrezione dell'utente. [Altre informazioni](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Replay immediato:** applicare un'animazione di riproduzione per ripetere la sequenza di disegno con l'input penna durante la presentazione. [Altre informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.

- **Ottimizzazione della presentazione per tutti:** l’opzione Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.

- **Perché reinventare quando è possibile riutilizzare?:** per risparmiare tempo, è possibile riutilizzare le diapositive create personalmente o condivise da altri utenti. [Altre informazioni](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- **Convertire l'input penna a mano libera in forme, testo o equazioni matematiche in PowerPoint per Office 365:** è possibile passare dall'input penna a mano libera al testo, a un'espressione matematica o alle forme di Office, con un paio di tratti. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Input penna per diapositive meravigliose:** è possibile convertire l'input penna in forme e testo standard e quindi ottenere idee di progettazione delle diapositive intelligenti da PowerPoint Designer. [Altre informazioni](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- **Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone. Per scoprirle, scegliere Inserisci > Icone. [Altre informazioni](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a>Visio

- **Analisi della scena del crimine:** è possibile usare i nuovi stencil Prova, Interni ed Esterni nel modello di indagine della scena del crimine per ricreare in dettaglio le scene del crimine.

- **Creare diagrammi di Visio chiari in Excel:** è possibile creare un diagramma di flussi o un organigramma inserendo i dati in un foglio di lavoro. [Altre informazioni](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Editor per curriculum unito all’Assistente curriculum LinkedIn:** l’editor per il curriculum offre una selezione di controlli grammaticali e stilistici appositamente studiati per i curriculum, per rendere la scrittura più precisa e professionale.

- **Risoluzione di un problema di danneggiamento di un documento causato dall'unione di oggetti 3D:** è stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.

- **Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora. [Altre informazioni](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Collaborare con colori vivaci:** i commenti e le modifiche sono contraddistinti da colori associati ai vari collaboratori, in modo che risulti facile identificarli.

- **Modificare i documenti con attivazione macro in modo collaborativo:** è possibile salvare i file docm su OneDrive for Business e modificarli con i collaboratori in tempo reale.

- **Miglioramenti alla creazione condivisa** : prestazioni migliorate per la creazione condivisa nei documenti di Word con revisioni.

- **Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone. Per scoprirle, scegliere Inserisci > Icone. [Altre informazioni](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.

- **Creare schizzi** : è possibile conferire un aspetto informale alle forme di Office incluse nel documento, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Cancellare con precisione:** è possibile scegliere tra due dimensioni della gomma per correggere le piccole imperfezioni dell'input penna. [Altre informazioni](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app. [Altre informazioni](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- **Miglioramenti alla creazione condivisa:** affidabilità migliore durante la creazione condivisa.

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura. [Altre informazioni](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo “Query danneggiata” quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.

- Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.

- Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB. L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.

- I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database. Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.

### <a name="excel"></a>Excel

- È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.

- La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.

- È stato risolto un problema che causava arresti anomali durante la conversione del testo in colonne con celle dotate di una matrice con espansione.

- Questo aggiornamento risolve un problema per cui la barra della formula causava la visualizzazione del testo in un carattere diverso da quello previsto.

- La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.

- È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.

- È possibile che gli utenti possano visualizzare un errore durante il salvataggio delle modifiche, quando si usano alcuni set di caratteri non inglesi.

- È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.

- Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.

- La funzionalità Testo in colonne può non funzionare per alcune localizzazioni.

- È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.

- È possibile che gli utenti possano visualizzare un errore durante il salvataggio delle modifiche, quando si usano alcuni set di caratteri non inglesi.

- È stato risolto un problema che alcuni utenti potrebbero aver riscontrato con oggetti incorporati e collegati (OLE).

- Tramite il menu di scelta rapida predefinito per i grafici pivot ora è possibile abilitare l'opzione Mostra dettagli.

- È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.

- È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.

- È stato risolto un problema che impediva la visualizzazione dei comandi di commento nel menu di scelta rapida.

- È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.

- È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.

- È stato risolto un problema che causava agli utenti un blocco in Outlook durante il recupero delle impostazioni del cloud.

- È stato risolto un problema che causava l’errato allineamento della casella di ricerca in modalità dpi elevato.

- È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.

- È stato risolto un problema per cui gli utenti vedevano i messaggi di posta elettronica inviati a un indirizzo che in alcuni casi non corrispondeva all'indirizzo SMTP visualizzato.

- Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.

- È stato risolto un problema che poteva impedire il salvataggio di file in una posizione WebDAV.

- È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.

- È stato risolto un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.

- È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante "OK" quando si provava a contattare il supporto dal contesto di creazione dell'account.

- È stato risolto un problema che causava un arresto anomalo durante la creazione del profilo.

- È stato risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.

- È stato risolto un problema per cui gli utenti con Tema Nero visualizzavano l'elenco a discesa “Da” con il testo bianco su sfondo bianco.

- È stato risolto un problema che causava un arresto anomalo annullando la configurazione dell'account.

- È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.

- È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.

- È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'apertura della finestra di dialogo Regole.

- È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.

- È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.

- È stato risolto un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.

- È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.

- È stato risolto un problema che impediva agli utenti di aprire alcune istanze di elementi ricorrenti del calendario.

- È stato risolto un problema che interessava le cassette postali sui server di Exchange 2010 durante l'aggiunta di allegati agli elementi del calendario da parte degli utenti.

- È stato risolto un problema che si verificava agli utenti durante la risposta a messaggi con firma digitale.

- È stato risolto un problema che causava l'aggiornamento imprevisto del campo Sede nelle riunioni.

- È stato risolto un problema per cui la virgola nel campo Sede della riunione cambiava in punto e virgola.

- È stato risolto un problema per cui la sede di una riunione veniva inaspettatamente aggiunta di nuovo alla riunione dopo che era stata cancellata.

- Sono stati risolti i problemi relativi alle riunioni e appuntamenti impostati nel fuso orario di Brasilia.

- È stato risolto un problema che causava l'invio imprevisto di messaggi di posta elettronica quando gli utenti premevano il tasto “S” dopo aver chiuso il riquadro Verifica accessibilità.

- È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.

- È stato risolto un problema che causava l'accesso dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.

- È stato risolto un problema che causava un arresto anomalo durante la creazione del profilo.

- È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.

- È stato risolto un problema che potrebbe aver causato un arresto anomalo durante l’utilizzo del menu di scelta rapida nei commenti PPT legacy.

### <a name="project"></a>Progetto

- È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.

- È stato risolto un problema per cui il 100% delle attività di tipo a durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.

- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.

- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.

### <a name="word"></a>Word

- È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.

- Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: "Sono stati modificati gli stili, i blocchi predefiniti".

### <a name="office-suite"></a>Famiglia di prodotti Office

- Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.

- Questa modifica risolve i problemi con gli adattatori grafici che sfruttano la GPU integrata Intel.

- È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.

- È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.

- È stato risolto un problema per cui l’apertura di più documenti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint comportava la conseguente analisi solo del primo documento per la conformità dei criteri.

[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-1908-february-11"></a>Versione 1908: 11 febbraio
*Versione 1908 (Build 11929.20606)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.

- È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.

- È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.

- È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.


- È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.

- È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.


### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.

- È stato risolto un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.

- È stato risolto un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.

- È stato risolto un problema che causava arresti anomali intermittenti cambiando visualizzazione.


- È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix. [Qui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) è disponibile il singolo articolo della Knowledge Basa in cui è stato documentato per le versioni precedenti.

- È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.


### <a name="powerpoint"></a>PowerPoint

- È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.


- È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.

- È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.

- È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.

### <a name="project"></a>Project

- È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.

### <a name="word"></a>Word

- È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a>Versione 1908: 14 gennaio
*Versione 1908 (Build 11929.20562)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Il Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt+G.

- È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.

- È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.

- È stato risolto un problema che causava la mancata visualizzazione dei suggerimenti per i criteri quando si usava un mittente alternativo.

- È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema che causava la creazione di schemi duplicati quando si copiava una diapositiva da una presentazione a un'altra.
- Per i file con nuovi commenti moderni viene visualizzato un avviso di colore giallo se vengono aperti in una versione non supportata

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto. In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.

- È stato risolto un problema per cui, in alcuni casi, un aggiornamento non veniva applicato se l'utente non era un amministratore e non era disponibile la connettività di rete per l'account di sistema.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).


[//]: # (NON MODIFICARE IL CONTENUTO DEI METADATI DELL'INTERFACCIA DI AMMINISTRAZIONE)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.13127.20760|versione-2008-novembre-10|)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.13127.20638|versione-2008-ottobre-13|)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.13127.20408|versione-2008-settembre-08|)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.12527.20988|versione-2002-agosto-11|)
[//]: # (| Win32 | FRDC | Partecipanti al programma Office Insider | | 16.0.12527.20880 | versione-2002-luglio-14 |)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
