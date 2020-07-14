---
title: Note sulla versione del Canale beta
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Offre ai partecipanti al programma Insider Fast un elenco aggiornato delle nuove funzionalità principali, correzioni o problemi noti '
ms.openlocfilehash: d80bc153a2de2f3f364003a5691753d12bbb0416
ms.sourcegitcommit: 39056b7c6c4fc271ff1c559f4231800862f279b4
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/10/2020
ms.locfileid: "45098670"
---
# <a name="release-notes-for-beta-channel"></a>Note sulla versione del Canale beta

Questo articolo contiene le note sulla versione delle build del Canale beta di Word, Excel, PowerPoint, Outlook, Access e Project per Windows desktop. Ogni settimana vengono evidenziate nuove funzionalità interessanti, correzioni critiche e problemi significativi di cui è importante essere a conoscenza. Nota che spesso in un determinato periodo di tempo vengono distribuite funzionalità (e a volte anche correzioni) del Canale beta. Ciò consente di verificare che tutto funzioni correttamente prima di rilasciare la funzionalità a un pubblico più ampio. Pertanto, anche se al momento non fossero disponibili descrizioni, prima o poi lo saranno.  

> [!IMPORTANT]
> Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Monthly Enterprise Channel) e la modifica dei nomi dei canali di aggiornamento già presenti. Leggere [questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441) per altre informazioni.

> [!NOTE]
> - Le note sulla versione vengono pubblicate ogni settimana e possono riguardare più build.
> - La data di pubblicazione delle note sulla versione può non corrispondere all'effettiva data di rilascio della build.

[//]: # (NON RIMUOVERE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

## <a name="version-2008-july-10"></a>Versione 2008: 10 luglio
*Versione 2008 (Build 13102.20002)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui non era stata selezionata l'opzione Consenti l'inoltro dalle “Opzioni risposta” del calendario condiviso della riunione se la cartella dei download condivisi non era stata selezionata.
- È stato risolto un problema che mostrava il pulsante stampa nello stato disabilitato anche se l'utente aveva le autorizzazioni di stampa appropriate.

### <a name="project"></a>Project

- È stato risolto un problema in cui se si tentava di salvare un PDF / XPS da Project in una raccolta documenti di SharePoint, non sarebbe successo nulla.

### <a name="word"></a>Word

- È stato risolto un problema in cui Word smette di rispondere dopo aver incollato del testo e un'immagine in una casella di testo.
- È stato risolto un problema in cui il pulsante "Nuovo commento" viene disabilitato dopo l'eliminazione dell'ultimo commento.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-03"></a>Versione 2007: 3 luglio
*Versione 2007 (Build 13029.20006)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Creare sondaggi in Outlook con Sondaggio rapido:** Creare facilmente un sondaggio, raccogliere voti e visualizzare i risultati in un messaggio di posta elettronica [Altre informazioni](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Nuova ricerca sala:** è possibile cercare sale riunioni in base a diverse caratteristiche.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema in cui le tabelle del modello di dati create in determinate versioni di Excel non possono essere visualizzate in "anteprima tabelle", anche se non sono state modificate.
- È stato risolto un problema in cui la disabilitazione dei riferimenti "Ignora relativi/assoluti" nella finestra di dialogo Definisci nome \ applica nomi causa il mancato funzionamento delle formule.
- È stato risolto un problema per cui la cancellazione di un filtro dati avanzato faceva perdere la formattazione della tabella.
- È stato risolto un problema in cui il percorso completo di un documento PDF incorporato viene visualizzato nella didascalia del documento, anziché solo nel nome del file.
- È stato risolto un problema per cui dopo aver disabilitato il connettore Cloud di Wolfram e aver salvato e riaperto una cartella di lavoro di Excel, poteva verificarsi un arresto anomalo.
- È stato risolto un problema per cui all'avvio di Excel con il componente aggiuntivo Risolutore poteva comportare un arresto anomalo.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui Outlook si bloccava se erano presenti più di 130 destinatari nella riga "a" e sono state migliorate anche le prestazioni di rendering del testo.
- È stato risolto un problema relativo alla “barra da fare” in cui gli eventi con più di due giorni mostravano la stessa ora di fine per tutti i giorni successivi.
- È stato risolto un problema che causava l'interruzione dell'aggiornamento dell'elenco dei messaggi degli utenti di Outlook per alcuni minuti dopo l'utilizzo dei calendari condivisi.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui quando si incollava l’HTML in un'area di testo su una diapositiva questo veniva invece incollato in una casella di testo creata nella parte superiore della diapositiva.
- È stato risolto un problema per cui selezionare tutte le diapositive nella visualizzazione relatore, uscire dalla visualizzazione relatore con ALT + TAB e tornare alla presentazione e fare clic su "fine presentazione" comportava un'eccezione non gestita.

### <a name="project"></a>Project

- È stato risolto un problema per cui il progetto potrebbe arrestarsi in modo anomalo all'apertura di alcuni file XML.
- È stato risolto un problema per cui non era possibile aprire un file di progetto da una raccolta documenti di SharePoint, se la raccolta era in modalità moderna.
- È stato risolto un problema per cui non era possibile aprire progetti nel client Project Desktop da Project Web App se l'URL terminava in ". com".

### <a name="word"></a>Word

- È stato risolto un problema durante la modalità di creazione condivisa quando si verifica un conflitto di Unione e l'utente ha già scelto di ignorare le modifiche, ma non veniva più visualizzata l'opzione per salvare o annullare le modifiche.
- È stato risolto un problema per cui, quando si provava a salvare un file contenente una macro con un nuovo nome, il file veniva salvato con estensione .docx e il nome file “WRO0004.docx”, indipendentemente dall'immissione dell'utente, rendeva il documento inutilizzabile.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-26"></a>Versione 2007: 26 giugno
*Versione 2007 (Build 13020.20004)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema per cui il responsabile della tabella collegata richiede una chiave primaria se una tabella SQL collegata era aggiornata.
- È stato risolto un problema relativo alla visualizzazione di query nell'Editor di query.
- È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui gli utenti non potevano utilizzare "Invia come" o "Invia per conto di” di una lista di distribuzione.
- È stato risolto un problema per cui l'inserimento di un'immagine in linea in un messaggio, e il successivo salvataggio del messaggio come bozza, comportava un ridimensionamento dell'immagine.
- È stato risolto un problema che causava il cambiamento del corpo di un messaggio NDR da Unicode a ASCII dopo aver modificato l'oggetto.

### <a name="project"></a>Project

- È stato risolto un problema per cui i collegamenti di Project Planner negli ambienti Government Community Cloud erano stati disabilitati.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui il testo inserito in un file SVG (Scalable Vector Graphics) era illeggibile dopo averlo inserito in un file di Word, Excel o PowerPoint, salvando e chiudendo il file e successivamente riaprendo il file.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-19"></a>Versione 2007: 19 giugno
*Versione 2007 (Build 13012.20000)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per il quale la scheda della barra multifunzione di CustomUI per una barra multifunzione era rimossa durante il salvataggio di una cartella di lavoro su SharePoint/OneDrive.
- È stato risolto un problema per cui le cartelle di lavoro erano di sola lettura quando per il file era soltanto consigliata sola lettura.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante immesso dall'IME quando si usavano più monitor con risoluzioni diverse.
- È stato risolto un problema per cui gli utenti visualizzavano il seguente errore seguente quando chiudevano un appuntamento salvato in precedenza: "non è possibile salvare l'elemento perché è stato modificato da un altro utente o in un'altra finestra. Si vuole creare una copia nella cartella predefinita per l'elemento? "
- È stato risolto un problema per cui le date nel mini calendario non erano visualizzate in grassetto per gli utenti in Giappone.
- È stato risolto un problema che impediva ai promemoria del calendario di mostrare le ore esatte per le riunioni da tenersi in meno di una settimana.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui l'indicatore di colore di presenza di un utente non si aggiornava nella raccolta condivisa durante una sessione di creazione condivisa in tempo reale.

### <a name="project"></a>Project

- È stato risolto un problema per cui, se le attività a durata fissa sono al 100% complete ma il completamento effettivo non è specificato, l'attività % di completamento era visualizzata come inferiore al 100%.

### <a name="word"></a>Word

- È stato risolto un problema per cui non era eseguito il rendering del colore del collegamento ipertestuale HTML.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui non erano visualizzati URL non basati su http o https nell'elenco di file usati di recente.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-june-12"></a>Versione 2007: 12 giugno
*Versione 2007 (Build 13006.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Accedere ai dati dell'organizzazione da Power BI usando i tipi di dati:** i tipi di dati di Excel di Power BI sono ora distribuiti ai partecipanti al programma Office Insider nelle organizzazioni con Office 365 E5/A5 o Microsoft 365 E5/A5. Ottenere le informazioni necessarie e aggiornarle con facilità è fondamentale per molti flussi di lavoro quotidiani. In Excel è possibile accedere alle informazioni della società o dell'organizzazione da Power BI come tipo di dati, in modo da espandere la tua capacità di inserire informazioni collegate nei fogli di calcolo. [Altre informazioni](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema che impedisce a Microsoft Access di identificare una colonna Identity in una tabella collegata di SQL Server, che poteva causare la segnalazione delle righe in modo non corretto.

### <a name="excel"></a>Excel

- È stato risolto un problema per cui le linee principali della griglia dei grafici radar non potevano essere formattate correttamente.

### <a name="project"></a>Project

- È stato risolto un problema per cui non era possibile eseguire l'evento ProjectBeforeTaskChange quando era apportata una modifica all'attività di riepilogo del progetto, sia inizio progetto che campo delle attività.
- È stato risolto un problema per cui una reimpostazione o aggiornamento di una linea di base poteva cambiare il costo del budget o le risorse lavoro a scala cronologica e la linea di base rifletteva valori di budget non corretti.

### <a name="word"></a>Word

- È stato risolto un problema per cui la possibilità di cancellare la formattazione nel riquadro commenti con il pulsante Cancella formattazione sulla barra multifunzione di Office non funzionava.
- È stato risolto un problema per cui si modificavano le dimensioni di una tabella quando il righello non veniva visualizzato e le altre applicazioni eseguite in background iniziavano a lampeggiare.
- È stato risolto un problema per cui, in modalità di creazione condivisa, le risposte ai commenti non venivano talvolta visualizzate nel riquadro commenti ma erano visibili nel riquadro revisioni.
- È stato risolto un problema per cui, se Word includeva un elenco di più di 50 documenti aperti di frequente, dopo il salvataggio e l'apertura di un documento veniva visualizzata la cronologia delle revisioni, anche se non erano state apportate revisioni al documento.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-05"></a>Versione 2006: 5 giugno
*Versione 2006 (Build 13001.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Ordinare/filtrare mentre si collabora in Excel:** è ora possibile ordinare e filtrare il file di Excel mentre si collabora con altri utenti. Questa nuova caratteristica evita che i tipi e i filtri di altri utenti siano d’impatto durante la creazione condivisa del documento.

- **Creare tabelle pivot da set di documenti in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di documenti archiviati in Power BI in pochi click. Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI. Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI. [Altre informazioni](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)

### <a name="outlook"></a>Outlook

- **Riaprire rapidamente gli elementi dalla sessione precedente:** è stata aggiunta un'opzione per riaprire rapidamente gli elementi da una sessione di Outlook precedente. Se Outlook si arresta in modo anomalo o lo chiudi, è possibile rilanciare rapidamente gli elementi quando si riapre l'app. Questa funzionalità è attivata per impostazione predefinita. Per disattivarla, vai a Opzioni > Generale > Opzioni di avvio.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per cui i valori personalizzati sull'asse del grafico non venivano applicati correttamente.
- È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante immesso dall'IME quando si usavano più monitor con risoluzioni diverse.
- È stato risolto un problema per cui la visualizzazione di un modello durante la composizione di un nuovo messaggio di posta elettronica causava un arresto anomalo.
- È stato risolto un problema per cui gli utenti non erano in grado di eseguire le cartelle pubbliche di Exchange 2010 dopo Outlook versione 1911.
- È stato risolto un problema per cui il pulsante Categorizza per i calendari di gruppo sulla barra multifunzione di Office era disabilitato.
- È stato risolto un problema che causava l'arresto anomalo degli utenti con contatti in conflitto in Outlook.
- È stato risolto un problema che causava il mancato recapito nell'elenco a discesa Archivio online nelle proprietà della cartella per gli utenti di monitor con valori DPI elevati.
- È stato risolto un problema che causava l’arresto anomalo di Outlook quando si lavorava con collegamenti ipertestuali nei messaggi di posta elettronica in testo normale.
- È stato risolto un problema che causava la possibilità di analizzare nomi file lunghi codificati con RFC2231.
- È stato risolto un problema che causava blocchi intermittenti di Outlook quando si usavano le utilità per la lettura dello schermo.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema con l'apertura di file configurati dal server con l'autenticazione basata su moduli.
- È stato risolto un problema per cui i file di PowerPoint con grafici o cartelle di lavoro incorporate potevano causare errori durante il salvataggio del file.
- È stato risolto un problema per cui un riquadro commenti che era stato chiuso dall'utente veniva riaperto automaticamente.
- È stato risolto un problema per cui l'editor di diapositive di una diapositiva si sovrapponeva alla diapositiva successiva.

### <a name="project"></a>Project

- Abbiamo risolto un problema che impediva l'eliminazione o la riassegnazione di attività orfane dopo l'eliminazione del piano padre.

### <a name="word"></a>Word

- È stato risolto un problema per cui i timestamp nei riquadri dei commenti non erano basati sull'ora locale di sistema.
- È stato risolto un problema per cui i commenti tra l'app Web e l'applicazione desktop non erano sincronizzati.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version2006may29"></a>Versione 2006: 29 maggio
*Versione 2006 (Build 12920.20000)*

### <a name="featureupdates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Altri pulsanti aggiunti agli avvisi popup di Outlook:** i pulsanti di azione rapida sono ora visualizzati negli avvisi popup di Outlook quando si esegue Outlook in Windows 10.

### <a name="powerpoint"></a>PowerPoint

- **Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida.  I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolvedissues"></a>Problemi risolti

### <a name="excel"></a>Excel

- È stato risolto un problema che causava l’arresto occasionale di Excel durante l'interazione con OneDrive.
- È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.
- È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappata invece che indirizzi universali.
- È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui le diapositive non erano centrate dopo l'ingrandimento con la rotellina del mouse.

### <a name="word"></a>Word

- È stato risolto un problema per cui non era possibile visualizzare e incollare il testo in un riquadro dei commenti.
- È stato risolto un problema per cui le bolle di suggerimenti per i commenti apparivano sfocate al 100% di zoom.
- È stato risolto un problema per cui l'abilitazione dei documenti e dei modelli binari di Word 2007 e successivi causava il fallimento di alcuni casi di creazione condivisa.
- È stato risolto un problema per cui i file con nomi di percorso lunghi, maggiore di 32K, non si aprivano e non veniva visualizzato un messaggio di errore appropriato.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2006-may-22"></a>Versione 2006: 22 maggio
*Versione 2006 (Build 12914.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Salvare in cartelle aggiunte:** aggiungere le cartelle semplifica il salvataggio dei file di Office. Abbiamo ricevuto feedback per cui gli utenti desiderano un maggiore controllo sulle cartelle disponibili per il salvataggio di un nuovo file. Siamo entusiasti di offrirti una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva. Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Salvare in cartelle aggiunte:** aggiungere le cartelle semplifica il salvataggio dei file di Office. Abbiamo ricevuto feedback per cui gli utenti desiderano un maggiore controllo sulle cartelle disponibili per il salvataggio di un nuovo file. Siamo entusiasti di offrirti una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva. Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Salvare in cartelle aggiunte:** aggiungere le cartelle semplifica il salvataggio dei file di Office. Abbiamo ricevuto feedback per cui gli utenti desiderano un maggiore controllo sulle cartelle disponibili per il salvataggio di un nuovo file. Siamo entusiasti di offrirti una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva. Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per cui compariva il messaggio di errore "La cartella di lavoro è attualmente consultata da un altro utente e non può essere chiusa", perché i componenti aggiuntivi erano caricati in ordine alfabetico invece che secondo un ordine specificato dall'utente.
- È stato risolto un problema di danneggiamento della memoria connesso con la gestione dei caratteri tra Excel e alcune applicazioni di Assistive Technology di terze parti.
- È stato risolto un problema che causava l’arresto anomalo di Excel quando i componenti aggiuntivi richiedevano elementi host su un foglio di lavoro contenente forme con blocchi noSelect.

### <a name="outlook"></a>Outlook

- È stato risolto un problema a causa del quale l’evento Folder.BeforeItemMove non si attivava correttamente quando un utente spostava elementi tra le cartelle.
- È stato risolto un problema per cui gli utenti vedevano elementi del calendario che duravano oltre la mezzanotte come Eventi a giornata intera.
- È stato risolto un problema relativo all'arresto anomalo di Outlook quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo sulla barra multifunzione.
- È stato risolto un problema che impediva agli utenti di condividere un calendario con un utente guest.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui lo zoom avanti e indietro dall’area di presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.

### <a name="project"></a>Project

- È stato risolto un problema per cui Project si arrestava in modo anomalo dopo aver fatto clic su Opzioni.

### <a name="word"></a>Word

- È stato risolto un problema per cui i collegamenti ipertestuali nei commenti non funzionavano.
- È stato risolto un problema per cui lo zoom avanti e indietro dall’area di presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.
- È stato risolto un problema per cui incollare HTML in WordMail per il Calendario non funzionava.
- È stato risolto un problema per cui la risposta a un commento in una sessione condivisa in alcuni casi causava il blocco di Word.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-15"></a>Versione 2006: 15 maggio
*Versione 2006 (Build 12905.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Creare una connessione PDF:** connettersi a, importare, aggiornare i dati da un file PDF. [Altre informazioni](https://support.office.com/article/9967afd8-85ee-4df3-aa06-753bcc1a2724)

### <a name="outlook"></a>Outlook

- **Trovare solo quello che serve:** è possibile restringere la ricerca con opzioni come cartelle, mittente, data, info allegati e altro ancora.

### <a name="powerpoint"></a>PowerPoint

- **Non c'è bisogno del clicker grazie agli auricolari:** i Surface Earbuds permettono di controllare le presentazioni di PowerPoint. Importante: per usare i gesti per controllare le presentazioni è necessario associare gli auricolari Surface Earbuds nell'app Surface Audio per Windows 10. Le istruzioni per iniziare a usare l'app Surface Audio in Windows 10 sono disponibili qui. [Altre informazioni](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="word"></a>Word

- **Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel
- È stato risolto un problema che produceva tempi di prestazioni migliorati quando gli utenti eliminavano le colonne combinate.
- <div>È stato risolto un problema che causava la duplicazione dei nomi delle stampanti nell'elenco delle stampanti disponibili.</div>

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema per cui le scelte rapide da tastiera e il controllo ortografico non funzionavano come previsto quando si usava una tastiera svizzera inglese (QWERTZ).

### <a name="word"></a>Word
- È stato risolto un problema per cui non era possibile aggiungere un nuovo commento in un documento vuoto.
- È stato risolto un problema per cui l'inserimento o l'aggiornamento di un indice in un documento contenente più di cento voci comportava l'arresto anomalo dell'applicazione.
- È stato risolto un problema per cui i file con valori XML personalizzati si aprivano in modo estremamente lento.

### <a name="office-suite"></a>Famiglia di prodotti Office
- È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-may-08"></a>Versione 2006: 8 marzo
*Versione 2006 (Build 12829.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

### <a name="outlook"></a>Outlook

- **Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai. [Altre informazioni](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

### <a name="powerpoint"></a>PowerPoint

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti. [Altre informazioni](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="office-suite"></a>Famiglia di prodotti Office

- Abbiamo esaminato e risolto il problema per cui una distribuzione di Office 365 ProPlus tramite InTune veniva sospesa dopo un arresto del sistema operativo.

[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-2005-may-01"></a>Versione 2005: 1 maggio
*Versione 2005 (Build 12827.20030)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Collegamenti migliorati nei messaggi di posta elettronica:** quando si include un collegamento a un file, il nome del file sostituisce l'URL. È possibile modificare le autorizzazioni per consentire l'accesso a tutti i destinatari. [Altre informazioni](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema di rendering dei valori in un asse data nella tabella dati del grafico.
- È stato risolto un problema che impediva la disabilitazione delle interruzioni di pagina dopo il passaggio a Layout di pagina o Anteprima interruzioni di pagina.
- È stato risolto un problema di perdita degli stili di linea del grafico dopo aver nascosto e visualizzato le colonne con i dati della serie.
- L'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.
- Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.
- È stato risolto il problema che poteva impedire il salvataggio della formattazione personalizzata dei grafici pivot quando era abilitata l'opzione "Inverti se negativo".
- È stato risolto un problema per cui non veniva salvata la formattazione personalizzata per un singolo punto dati in un grafico pivot se era stata selezionata l'opzione "Inverti se negativo".
- Questa modifica risolve un problema per cui il carattere "@" caricato in un file CSV comportava la conversione della stringa dopo il carattere "@" in una formula.
- È stato risolto un problema per cui i valori decimali della funzione sequenza non venivano arrotondati correttamente.

### <a name="outlook"></a>Outlook

- Risolve un problema che impediva il caricamento dei collegamenti sicuri molto lunghi su cui gli utenti facevano clic nel client desktop di Outlook a causa di un troncamento.
- È stato risolto un problema per cui le cartelle di Outlook con nomi contenenti caratteri del set di caratteri a due byte (DBCS) talvolta scomparivano durante la sincronizzazione con il server. Questo succedeva con Outlook configurato con un account IMAP ed eseguito in un sistema con le impostazioni locali impostate su giapponese.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui, se un utente creava un commento senza pubblicarlo e chiudeva il riquadro Commenti, quindi apriva una nuova finestra, si spostava tra più diapositive, chiudeva la finestra e infine riapriva il riquadro Commenti nella presentazione originale, i commenti bozza non erano disponibili.

### <a name="project"></a>Project

- È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies aveva esito negativo quando veniva aggiunto un elemento Lag.

### <a name="word"></a>Word

- È stato risolto un problema per cui l'inserimento di commenti in un documento in modalità di collaborazione non sempre funzionava.
- Questo cambiamento risolve un problema per cui la scheda Persone lampeggiava se veniva selezionata la menzione con @.
- È stata risolto il problema per cui alla chiusura di un documento con commenti in bozza veniva chiesto di confermare la chiusura del documento senza salvare la bozza. Annullando il messaggio, il documento veniva chiuso invece di rimanere aperto.
- È stato risolto un problema per cui durante la traduzione di un commento pubblicato veniva visualizzato l'errore "L'inserimento del testo tradotto non è riuscito".
- In visualizzazione Web/Strumento di lettura immersiva, la selezione di un suggerimento determinava lo scorrimento verso l'alto anche se era già visualizzato. Questo problema è stato risolto.
- È stato risolto un problema per cui, quando si provava a salvare un file contenente una macro con un nuovo nome, il file veniva salvato con estensione docx e il nome file WRO0004.docx, indipendentemente dall'immissione dell'utente, rendendo il documento inutilizzabile.

[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)


## <a name="version-2005-april-24"></a>Versione 2005: 24 aprile
*Versione 2005 (Build 12816.20006)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel
- Questa modifica consente di risolvere un problema per cui il valore R quadrato per una linea di tendenza (nel caso di intercetta y forzata), non era corretto, anche se la funzione REGR.LIN restituiva il valore corretto.
- Questa modifica risolve un problema per cui il formato della linea di tendenza del grafico personalizzata non sempre veniva salvato.

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui il pulsante Categorizza per i calendari di gruppo sulla barra multifunzione di Office era disabilitato.
- È stato risolto un problema per cui i clienti aziendali con cartelle di gruppo non implementate o non funzionanti visualizzavano un messaggio di tipo "Outlook non risponde".

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema per cui, posizionando il puntatore del mouse sul simbolo dell'asterisco (*), non venivano mostrati il nome utente dell'ultima persona ad aggiornare il documento e la data della modifica.

### <a name="word"></a>Word
- Abilitando l'opzione "Mostra segnalibri", i segnalibri non venivano visualizzati. Questo problema è stato risolto.
- Questa modifica risolve un problema per cui il testo con collegamenti ipertestuali poteva non essere visualizzato se era abilitata l'opzione "Mostra codici di campo anziché i relativi valori".

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2005-april-17"></a>Versione 2005:17 aprile
*Versione 2005 (Build 12810.20002)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel
- Sono state aumentate le dimensioni dei controlli per la modifica del riferimento di cella nella finestra di dialogo Barre di errore personalizzate usata con i grafici.
- Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.
- È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.
- Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.
- Questa modifica risolve un problema per cui le informazioni sulla formattazione condizionale non venivano salvate correttamente nei file XLSB.

### <a name="onenote"></a>OneNote
- È stato risolto un problema per cui le interruzioni di riga venivano archiviate come schede verticali.

### <a name="outlook"></a>Outlook
- Risolve un problema che impediva agli utenti di aggiungere un gruppo di contatti personale come partecipante alla riunione.
- Risolve un problema che impediva la visualizzazione in Assistente Pianificazione dell'oggetto delle riunioni pianificate tra più di 2 mesi.
- Risolve un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.
- Aggiunta della funzionalità di applicazione della configurazione di firma predefinita S/MIME tramite Criteri di gruppo.
- Risolve un problema per cui le regole di eliminazione create per le cassette postali diverse da quella principale dell'utente non erano più valide.
- Risolve un problema che causava la perdita di allegati quando si inoltrava un messaggio crittografato.

### <a name="project"></a>Project
- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.
- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si cambia il campo Stato bacheca in un progetto connesso a un elenco attività di SharePoint.
- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="version-2004-april-10"></a>Versione 2004: 10 aprile
*Versione 2004 (Build 12730.20024)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Ignorare la finestra di dialogo Mostra tabella, passare direttamente a un riquadro attività e semplificare l'aggiunta di tabelle alle relazioni e alle query:** aggiungere tabelle e query facendo clic su quattro schede, selezionando più nomi, eseguendo una ricerca testuale e trascinando da un riquadro attività che resta aperto mentre si lavora.

### <a name="excel"></a>Excel

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Mantenere la qualità elevata delle immagini quando inserite in un messaggio di posta elettronica:** è disponibile una nuova opzione di Outlook per limitare la compressione quando si inviano immagini come parte del contenuto del messaggio di posta elettronica

### <a name="powerpoint"></a>PowerPoint

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione.

### <a name="word"></a>Word

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

- **Annotare la copia privata:** è possibile creare note scritte a mano visibili solo a se stessi creando una copia privata di un documento condiviso. Passare alla Visualizza > Crea una copia privata per iniziare.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Sono stati risolti problemi relativi al ridimensionamento e all'aggiornamento di tabelle nel riquadro attività.

### <a name="excel"></a>Excel

- È stato risolto un problema per cui, selezionando un intervallo di celle in un foglio, veniva selezionata una singola cella.

- È stato risolto un problema per cui Excel poteva smettere di rispondere riducendo le dimensioni di un grafico con alcuni intervalli dell'asse x.

- È stato risolto un problema per cui, inserendo un modello di grafico definito dall'utente come predefinito, veniva salvato come istogramma.

- È stato risolto un problema per cui le etichette dati apparivano vuote quando le celle di dati sottostanti non avevano una didascalia.

- È stato risolto un problema per cui, durante la condivisione/creazione in modalità condivisa di un foglio di Excel con lo stile di riferimento R1C1 abilitato, passando il mouse sull'icona di presenza utente non compariva il riferimento di cella attivo in modalità R1C1.

### <a name="outlook"></a>Outlook

- Risolve un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.

- Risolve un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.

- Risolve un problema che causava l'arresto anomalo provando a visualizzare le proprietà di un modulo dell'organizzazione.

- Risolve un problema che causava la mancata attivazione di alcuni promemoria cambiando il fuso orario in un computer.

### <a name="powerpoint"></a>PowerPoint

- Questa modifica risolve un problema per cui, nel rendering di un grafico di Excel legacy incorporato come oggetto OLE in PowerPoint o Word, non sempre veniva visualizzato il titolo del grafico.

- È stato risolto un problema per cui la formattazione di un testo copiato da Excel a PowerPoint poteva essere modificata.

- Questa modifica risolve un problema per cui la ricerca di caratteri speciali con l'opzione "Solo parole intere" non funzionava come previsto.

### <a name="project"></a>Project

- È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.

### <a name="word"></a>Word

- Questa modifica risolve un problema per cui, posizionando il cursore su un suggerimento, non veniva evidenziata la relativa scheda.

- Questa modifica risolve un problema che causava la scomparsa temporanea del testo nelle forme raggruppate usando lo strumento di selezione Lazo.

- Questa modifica risolve un problema per cui, nel rendering di un grafico di Excel legacy incorporato come oggetto OLE in PowerPoint o Word, non sempre veniva visualizzato il titolo del grafico.

- Questa modifica risolve un problema della visualizzazione a due pagine per cui, creando un commento, l'ancoraggio del commento non sempre era visibile.

- È stato risolto un problema per cui, in un paragrafo il cui stile è un predecessore di uno stile collegato a un elenco, la numerazione dell'elenco poteva andare persa.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-27"></a>Versione 2004: 27 marzo
*Versione 2004 (Build 12718.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Nuova opzione per disabilitare i suggerimenti di @menzioni durante la composizione dei messaggi di posta elettronica:** si trovano i suggerimenti per la selezione delle menzioni più fastidiosi che utili? Ora è possibile disattivarli.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook
- Risolve un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.
- Risolve un problema che impediva agli utenti di aggiungere una firma rispondendo a un messaggio protetto con Digital Rights Management da una finestra Inspector quando l'utente non ha l'autorizzazione di proprietario per il messaggio a cui sta rispondendo.
- Risolve un problema che impediva agli utenti di aggiungere altri allegati da un percorso Web a una riunione creata in precedenza.

### <a name="powerpoint"></a>PowerPoint
- Questa modifica risolve un errore che poteva causare un errore nel salvataggio dei file di PowerPoint contenenti emoji.

### <a name="project"></a>Project
- È stato risolto un problema per cui, eseguendo "CustomFieldValueListGetItem" quando non esiste una tabella di ricerca per il campo personalizzato, viene creata una tabella di ricerca vuota anche se non dovrebbe esserlo.

### <a name="word"></a>Word
- Questa modifica risolve un problema per cui selezionando più pagine selezionata nel menu Visualizza, il riquadro Commenti poteva apparire vuoto.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-20"></a>Versione 2004: 20 marzo
*Versione 2004 (Build 12711.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Aggiornamento visivo del calendario:** l'anno scorso abbiamo presentato un'esperienza di posta elettronica rinnovata e quest'anno è il turno del calendario. Gli aggiornamenti sono innovativi ma familiari, in modo che gli utenti esperti di Outlook siano subito più produttivi.

- **Protezione dei dati nel gruppo:** l'etichetta di riservatezza che si sceglie quando si crea un gruppo viene applicata ai messaggi di posta elettronica, ai documenti e ai siti del team del gruppo

### <a name="powerpoint"></a>PowerPoint

- **Aggiornamento delle diapositive durante la presentazione:** è possibile aggiornare le diapositive modificate da altri autori durante la presentazione.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.

### <a name="outlook"></a>Outlook

- Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.

- Questa modifica risolve un problema per cui le ultime modifiche apportate alle bozze di messaggi di posta elettronica non venivano aggiornate.

- È stato risolto un problema per cui fare clic con il pulsante destro del mouse su un file e scegliere "Invia a" non funzionava.

- È stato risolto un problema per cui, se un utente aveva personalizzato il percorso di ricerca per la Rubrica, l'ambito di risoluzione dei nomi di Outlook era limitato al percorso personalizzato e non includeva l'elenco indirizzi globale.

- È stato risolto un problema per cui, all'interno di un set di risultati della ricerca restituiti, l'ordinamento dei risultati in base alla categoria non mostrava i colori delle categorie.

### <a name="project"></a>Project

- È stato risolto un problema per cui l'evento "ProjectBeforeTaskChange" di Visual Basic, Applications Edition (VBA) non veniva attivato quando un utente faceva clic sul pulsante "Disattiva" disponibile nella barra multifunzione Attività nel gruppo Programmazione.

- Impostando i dettagli su predecessore o successore da una visualizzazione di tipo modulo, l'evento ProjectBeforeTaskChange Visual Basic Applications (VBA) non sempre acquisiva le modifiche. Ad esempio, eliminando una dipendenza e facendo clic su OK nel modulo, l'evento non veniva attivato. Questo comportamento è stato corretto.

- È stato risolto un problema per cui i valori più recenti per il costo effettivo del lavoro eseguito (ACWP) non venivano visualizzati dopo avere apportato una modifica, ad esempio dopo aver cambiato la data.

- È stato risolto un problema per cui, aprendo un progetto dal menu Usati di recente (MRU), il file di progetto veniva aperto con accesso in lettura/scrittura.

- Questa modifica risolve un problema per cui, creando un'attività manuale con una data e un'ora di inizio, ma non una durata, l'attività veniva visualizzata con un orario non corretto nella sequenza temporale.

- È stato risolto un problema per cui la stampa di una sequenza temporale usando il calendario Hijri comportava l'omissione o la duplicazione di un mese nella visualizzazione stampa.

- Questa modifica risolve un problema relativo all'uso di Pianificazione team con oggetti GDI, che poteva comportare la sovrassegnazione di oggetti GDI e di conseguenza condizioni di memoria insufficiente.

### <a name="word"></a>Word

- È stato risolto un problema per cui la funzionalità di invio commenti era disabilitata.

- Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.

- Questa modifica risolve un problema che impediva all'account manager di inviare messaggi, causando un blocco nelle applicazioni di terze parti.

- Questa modifica risolve un problema per cui il Sommario veniva aggiornato con stili del titolo non presenti nel documento.

- È stato risolto un problema per cui le firme digitali salvate nei documenti di Word venivano rimosse al momento dell'invio dei documenti.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-march-13"></a>Versione 2004: 13 marzo
*Versione 2004 (Build 12703.20010)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità

### <a name="excel"></a>Excel
- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate. [Altre informazioni](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate. [Altre informazioni](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate. [Altre informazioni](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="access"></a>Access
- È stato risolto un problema per cui nell'interfaccia utente delle versioni internazionali di Access venivano visualizzate stringhe in inglese.

### <a name="excel"></a>Excel
- È stato risolto un problema di prestazioni che talvolta gli utenti sperimentavano quando modificavano un intervallo di celle elevato a livello di programmazione.
- È stato risolto un problema di prestazioni che si verificava durante l'apertura di file CSV in ambiente giapponese.

### <a name="outlook"></a>Outlook
- È stato risolto un problema per la cui i dati relativi all'ultima modifica di un file venivano aggiornati aggiungendo un allegato a un messaggio di posta elettronica o salvando un allegato da un messaggio di posta elettronica mediante trascinamento, anziché tramite un menu.
- Risolve un problema per cui nel riquadro Trova espanso premendo il tasto Invio non si avviava la ricerca; era invece necessario fare clic sul pulsante Cerca.
- È stato risolto un problema per cui la ricerca non mostrava informazioni sugli utenti quando l'opzione "Mostra le foto degli utenti quando disponibili" era disabilitata.

### <a name="project"></a>Project
- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.
- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.

### <a name="word"></a>Word
- È stato risolto un problema per cui digitando o modificando un commento e usando la combinazione di tasti CTRL+A veniva selezionato il testo nell'area di disegno anziché nella scheda del commento.
- È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.
- È stato risolto un problema che si verificava unendo due documenti in uno.
- È stato risolto un problema per cui quando si contrassegnavano le revisioni contenenti delle equazioni si verificava un errore durante il salvataggio del file.

[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-march-06"></a>Versione 2003: 6 marzo
*Versione 2003 (Build 12624.20086)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui una regola creata in Outlook Web Access non veniva mantenuta nel server Exchange e generava un conflitto.
- È stato risolto un problema per cui nella modalità scura di Outlook non veniva visualizzato l'elenco a discesa nel campo "Da:".
- Risolve un problema che impediva agli utenti di allegare un file al messaggio di posta elettronica tramite Esplora file se il file era aperto in un'altra applicazione.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui le anteprime consigliate lampeggiavano durante il passaggio del mouse su di esse. In alcuni questo causava un arresto anomalo di PowerPoint.

### <a name="word"></a>Word

- È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema con Word/Excel/PowerPoint per cui il nome dell'entità utente (UPN) non distingueva più tra maiuscole e minuscole, causando la visualizzazione di un numero inferiore di errori durante l'uso dei file in SharePoint.

- È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.

[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

[//]: # (NON RIMUOVERE L'INIZIO DEI CONTENUTI RELATIVI AI DETTAGLI DELLE FUNZIONALITÀ)

## <a name="version-2003-february-28"></a>Versione 2003: 28 febbraio
*Versione 2003 (Build 12619.20002)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Notifica di evento imprevisto per gli amministratori IT:** gli amministratori globali dei tenant di Microsoft 365 e gli amministratori delle app di Office verranno avvisati degli eventi imprevisti di Outlook e Office 365 Exchange che interessano gli utenti tramite una nuova notifica nel riquadro a destra in Outlook per Windows. [Altre informazioni](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

### <a name="powerpoint"></a>PowerPoint

- **Migliorata l'esperienza di input penna in forma per la creazione di diagrammi:** è possibile disegnare diagrammi più efficaci e convertirli in oggetti di Office da modificare [Scopri di più](https://support.office.com/article/f304ef73-9514-450b-9bb9-28c6057020f2)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per cui il testo in un filtro dati non veniva ridimensionato correttamente nell'anteprima di stampa.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per la cui i dati relativi all'ultima modifica di un file venivano aggiornati quando si aggiungeva un allegato a un messaggio di posta elettronica o si salvava un allegato da un messaggio di posta elettronica trascinandolo, anziché tramite un menu.

### <a name="word"></a>Word

- È stato risolto un problema per cui spostandosi con TAB in una scheda commento, lo stato attivo sulla casella di modifica del commento non era visibile.

- Se veniva inserito un controllo in un'equazione, ad esempio un controllo contenuto testo, il salvataggio e l'apertura del file comportavano un errore di contenuto illeggibile.

- È stato risolto un problema per cui non era possibile salvare un file protetto in precedenza da password, in uno spazio di archiviazione cloud.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-21"></a>Versione 2003: 21 febbraio
*Versione 2003 (Build 12615.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="office-suite"></a>Famiglia di prodotti Office

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel
- È stato risolto un problema che può essere stato riscontrato dagli utenti nel rinominare le misure delle tabelle pivot.
- È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.
- È stato risolto un problema che causava il lampeggio dell’interfaccia utente durante l'esecuzione di una macro che interagiva con la barra multifunzione.
- È stato risolto un problema per cui i file CSV venivano caricati erroneamente quando la prima parola nel file era TABLE.
- È stato risolto un problema per cui gli utenti potevano riscontrare arresti anomali durante il passaggio da una cartella di lavoro a un’altra con un livello di zoom diverso.

### <a name="outlook"></a>Outlook
- È stato risolto un problema che impediva agli utenti di aprire messaggi di cartelle pubbliche quando Outlook era rimasto in esecuzione durante la notte.
- È stata risolta una race condition in cui i pulsanti "Consenti" e "Nega" nella pagina delle autorizzazioni venivano disabilitati durante il flusso di lavoro di autenticazione per l'aggiunta di un account Gmail.
- È stato risolto un problema per cui Outlook generava in modo inatteso l'output di registrazione in alcuni scenari, anche quando la registrazione era disattivata.

### <a name="word"></a>Word
- È stato risolto un problema per cui le schede di commento non venivano sempre evidenziate quando si passava il puntatore del mouse su di esse.
- Durante una sessione di creazione condivisa di documenti attiva, l'aggiunta diretta di un'immagine in una scheda di commento può comportare l'aggiunta di un contrassegno. Questo problema è stato risolto.

### <a name="office-suite"></a>Famiglia di prodotti Office
- Se si usavano proprietà di scelta multipla, ricerca o metadati gestiti con documenti di Word, Excel o PowerPoint e si eseguiva il salvataggio in una raccolta documenti di SharePoint, queste proprietà erano limitate a 255 caratteri. Quando queste proprietà superavano i 255 caratteri, non era possibile salvare i documenti. Con questa modifica, il limite è stato aumentato a 2048 caratteri.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-february-14"></a>Versione 2003: 14 febbraio
*Versione 2003 (Build 12607.20000)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web? Outlook ora consente di rimanere connessi in scenari di questo tipo.

### <a name="word"></a>Word

- **Editor input penna disponibile nella casella degli strumenti da disegno:** selezionare Disegno e quindi scegliere Editor input penna per modificare il documento con un dito o una penna digitale. [Altre informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

### <a name="office-suite"></a>Applicazioni Office

- **Icone delle barre di stato più chiare:** ora le icone della barra di stato sono più facili da vedere

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema a causa del quale gli utenti perdevano l'accesso alla finestra di dialogo delle autorizzazioni del calendario "Opzioni disponibilità".

- È stato risolto un problema a causa del quale potrebbe essere visualizzato l'avviso "Si è verificato un problema con l'apertura di questo elemento" quando si aprono istanze di riunioni ricorrenti inviate da un fuso orario diverso.

- È stato risolto un problema a causa del quale gli utenti potrebbero non essere in grado di riaprire un file .msg dopo aver trascinato un allegato da quel messaggio.

- È stato risolto un problema a causa del quale, dopo aver caricato un allegato da Outlook a OneDrive, il nome file potrebbe cambiare se il nome dell'allegato contiene delle parentesi.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema che potrebbe causare un errore durante il salvataggio di un documento in PowerPoint o Word che contiene un grafico di Excel.

### <a name="word"></a>Word

- È stato risolto un problema a causa del quale le immagini nei documenti perdono la trasparenza quando vengono esportate in PDF.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-07"></a>Versione 2002: 7 febbraio
*Versione 2002 (Build 12527.20040)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla. Cercare e sostituire il testo nella visualizzazione SQL. Selezionare più tabelle nella finestra Relazioni.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB. L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.

- Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.

### <a name="excel"></a>Excel

- È stato risolto un problema relativo all'arresto anomalo di Excel quando si usa Testo in colonne con matrici dinamiche.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui scorrendo il calendario con la visualizzazione per mese, non è possibile visualizzare gli eventi del calendario precedente.

- Risolve un problema che causa l'arresto anomalo quando si visualizzano più di 30 calendari in un ambiente Citrix.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui, dopo aver chiuso un file, PowerPoint non lo rimuove immediatamente dalla raccolta presentazioni se sono in esecuzione gestori di eventi. Di conseguenza, il numero di presentazioni aperte riportate dal modello a oggetti non è corretto e viene impedita la chiusura di PowerPoint.

- È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.

### <a name="word"></a>Word

- L'aggiornamento e lo scorrimento di un sommario possono talvolta visualizzare un'area grigia sul documento.

- È stato risolto un problema per cui, se un documento è stato creato in modo condiviso, la versione bozza di un commento radice potrebbe non essere mantenuta.

- È stato risolto un problema per cui quando ci si spostava tra le schede commento talvolta il commento inizialmente selezionato veniva visualizzato con un'evidenziazione della selezione.

- È stato risolto un problema per cui l'utilizzo di "Sfoglia" per salvare un file non funzionava se un commento veniva scritto ma non pubblicato e l'utente provava a salvare il file.

- Con SlideTrack abilitato e il riquadro commenti chiuso, CTRL + ALT + M potrebbe non aprire il riquadro commenti.

- È stato risolto un problema per cui quando si aggiungeva una @menzione in una tabella poteva venire generato il messaggio di errore: "una tabella in questo documento è stata danneggiata".

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema che potrebbe aver causato l'installazione errata del pacchetto di strumenti di correzione norvegese Nynorsk (nn-no).

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|DevMain|Insiders| |16.0.13102.20002|version-2008-july-10|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)