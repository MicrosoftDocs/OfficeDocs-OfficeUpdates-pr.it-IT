---
title: Note sulla versione del Canale corrente (Anteprima)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Offre ai partecipanti al programma Insider Slow un elenco aggiornato delle nuove funzionalità principali, correzioni o problemi noti '
ms.openlocfilehash: 63ae6dbe28765efde1ddc6a440adeddd53b71338
ms.sourcegitcommit: f7bb0455136794c38a7f934e391b17a9c98c9d52
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/10/2020
ms.locfileid: "45094646"
---
# <a name="release-notes-for-office-current-channel-preview"></a>Note sulla versione del Canale corrente di Office (Anteprima)

Questo articolo contiene le note sulla versione per le build del Canale corrente (Anteprima) di Word, Excel, PowerPoint, Outlook, Access e Project per Windows desktop. Ogni settimana verranno evidenziate nuove funzionalità interessanti, correzioni importanti e problemi significativi di cui è utile essere al corrente. Nota che spesso in un determinato periodo di tempo vengono distribuite funzionalità (e a volte anche correzioni) del Canale corrente (Anteprima). Ciò consente di verificare che tutto funzioni correttamente prima di rilasciare la funzionalità a un pubblico più ampio. Pertanto, anche se al momento non fossero disponibili descrizioni, prima o poi lo saranno.  

> [!IMPORTANT]
> Apporteremo alcune modifiche ai canali di aggiornamento per App di Microsoft 365, tra cui l'aggiunta di un nuovo canale di aggiornamento (canale mensile Enterprise) e la modifica dei nomi dei canali di aggiornamento già presenti. Per altre informazioni, [leggere questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

> [!NOTE]
> - La data di pubblicazione delle note sulla versione può non corrispondere all'effettiva data di rilascio della build.

[//]: # (NON RIMUOVERE)

## <a name="version-2006-july-09"></a>Versione 2006: 9 luglio
*Versione 2006 (Build 13001.20384)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Creare una connessione PDF:** connettersi a, importare, aggiornare i dati da un file PDF. [Altre informazioni](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- **Creare variabili da usare nelle formule:** migliorare le prestazioni, la leggibilità e la compatibilità con la funzione LET. Questa funzione consente di creare variabili denominate nelle formule nuove o preesistenti. [Altre informazioni](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)

- **Scelte rapide da tastiera in Excel:** scelte rapide da tastiera aggiornate per Excel

### <a name="outlook"></a>Outlook

- **Creare sondaggi in Outlook con Sondaggio rapido:** Creare facilmente un sondaggio, raccogliere voti e visualizzare i risultati in un email [Altre informazioni](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)

- **Mantenere la qualità elevata delle immagini quando inserite in un messaggio di posta elettronica:** è disponibile una nuova opzione di Outlook per limitare la compressione quando si inviano immagini come parte del contenuto del messaggio di posta elettronica


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo problema è stato risolto e dovrebbe essere possibile inserire correttamente tabelle SQL collegate che includano un campo identità, ad esempio numerazione automatica, in Access.

### <a name="excel"></a>Excel

- È stato risolto un arresto anomalo che può verificarsi quando si cerca di creare una connessione dati, se l’utente è uscito dal proprio account.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.

### <a name="office-suite"></a>Applicazioni Office

- È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. 

- l'host di Office si arresta in modo anomalo in Windows, quando viene attivato un componente aggiuntivo mentre il valore del registro di sistema TabProcGrowth è di tipo REG_SZ e con valore "0".  Il valore del registro di sistema TabProcGrowth può seguire uno dei quattro percorsi seguenti: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main Questa modifica può risolvere il problema.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2006-june-25"></a>Versione 2006: 25 giugno
*Versione 2006 (Build 13001.20266)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="visio"></a>Visio

- **Creare impeccabili diagrammi di Visio in Excel:** è possibile creare un diagramma di flussi o un organigramma sulla base di dati inseriti in un foglio di lavoro.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- <div>Questo problema è ora risolto. Comunicare al team se si verificano altri problemi durante il processo.</div>


### <a name="outlook"></a>Outlook

- <div><span style="display:inline !important;">Risolve un problema a causa del quale gli utenti visualizzavano <span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">la data di creazione di&nbsp; allegati copiati nel file system tramite il trascinamento &nbsp;fissata all’1 gennaio 4501.</span><br></div>


- <div><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Risolve un problema a causa del quale gli utenti dei miglioramenti del Calendario condiviso visualizzavano errori di calendario.</span><br></div>


- <div><span style="display:inline !important;">Risolve un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.</span><br></div>


- <div><span style="display:inline !important;">Risolve un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.</span><br></div>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2006-june-18"></a>Versione 2006: 18 giugno
*Versione 2006 (Build 13001.20198)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel



- **Salva in Cartelle aggiunte:** le Cartelle aggiunte semplificano il salvataggio dei file di Office Abbiamo ricevuto feedback secondo cui gli utenti vogliono maggior controllo sulle cartelle disponibili al momento del salvataggio di un nuovo file. Siamo felici di offrire una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva. Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint. <br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="powerpoint"></a>PowerPoint

- **Salva in Cartelle aggiunte:** le Cartelle aggiunte semplificano il salvataggio dei file di Office Abbiamo ricevuto feedback secondo cui gli utenti vogliono maggior controllo sulle cartelle disponibili al momento del salvataggio di un nuovo file. Siamo felici di offrire una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva. Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)

### <a name="word"></a>Word

- **Salva in Cartelle aggiunte:** le Cartelle aggiunte semplificano il salvataggio dei file di OfficeAbbiamo ricevuto feedback secondo cui gli utenti vogliono maggior controllo sulle cartelle disponibili al momento del salvataggio di un nuovo file. Siamo felici di offrire una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva. Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint. <br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.

### <a name="outlook"></a>Outlook

- È stato risolto un problema a causa del quale CTRL+clic smetteva di funzionare quando le impostazioni del cloud erano abilitate.

### <a name="project"></a>Project

- È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2006-june-11"></a>Versione 2006: 11 giugno
*Versione 2006 (Build 13001.20144)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="powerpoint"></a>PowerPoint

- **Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida. I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.

### <a name="word"></a>Word

- **Mantenere il testo nei vettori:** ora è possibile mantenere il testo nelle mappe, nei grafici e in altri vettori SVG al momento della conversione di questi oggetti in Excel, Word e PowerPoint.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema che causava l’arresto occasionale di Excel durante l'attivazione di OneDrive.

- È stato risolto un problema per cui i valori personalizzati sull'asse del grafico non venivano applicati correttamente.

- È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.

- È stato risolto un problema che causava la duplicazione dei nomi delle stampanti nell'elenco delle stampanti disponibili.

- È stato risolto un problema che generava un miglioramento delle prestazioni quando gli utenti eliminavano le colonne unite insieme.

- È stato risolto un problema per cui compariva il messaggio di errore "La cartella di lavoro è attualmente consultata da un altro utente e non può essere chiusa", perché i componenti aggiuntivi erano caricati in ordine alfabetico invece che secondo un ordine specificato dall'utente.

- È stato risolto un problema di danneggiamento della memoria connesso con la gestione dei caratteri tra Excel e alcune applicazioni di assistive technology di terze parti.

- È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.

- È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappata invece che indirizzi universali.

- È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti per lo scorrimento CTRL+MAIUSC+Freccia, quando la finestra di Excel era condivisa attraverso Teams.

- È stato risolto un problema che causava l’arresto anomalo di Excel quando i componenti aggiuntivi richiedevano elementi host su un foglio di lavoro contenente forme con blocchi Nessuna selezione.

- È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo nel tentativo di inserire tabelle pivot in un foglio grafico.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante inserito attraverso l’IME, quando venivano usati più monitor con risoluzioni diverse.

- È stato risolto un problema per cui la visualizzazione di un modello durante la composizione di un nuovo messaggio di posta elettronica provocava un arresto anomalo.

- È stato risolto un problema per cui gli utenti non riuscivano a usare le cartelle pubbliche di Exchange 2010 dopo la versione 1911 di Outlook.

- È stato risolto un problema per cui il pulsante Categorizza per i calendari di gruppo sulla barra multifunzione di Office era disabilitato.

- È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.

- È stato risolto un problema che causava l'arresto anomalo di Outlook per alcune build di Windows.

- È stato risolto un problema che impediva agli utenti di condividere un calendario con un utente guest.

- È stato risolto un problema per cui gli utenti vedevano elementi del calendario che duravano oltre la mezzanotte come Eventi a giornata intera.

- È stato risolto un problema a causa del quale nell’archivio online scompariva l'elenco a discesa nelle proprietà della cartella per gli utenti che usavano monitor con valori DPI elevati.

- È stato risolto un problema a causa del quale l’evento Folder.BeforeItemMove non si attivava correttamente quando un utente spostava elementi tra le cartelle.

- È stato risolto un problema relativo all'arresto anomalo di Outlook quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo sulla barra multifunzione.

- È stato risolto un problema che causava l’arresto anomalo di Outlook quando l’utente inseriva collegamenti ipertestuali nei messaggi di posta elettronica con testo normale.

- È stato risolto un problema per cui Outlook non riusciva ad analizzare i nomi di file lunghi codificati con RFC2231.

- È stato risolto un problema che provocava blocchi intermittenti di Outlook dovuti alle utilità per la lettura dello schermo.

- È stato risolto un problema che causava l'arresto anomalo di Outlook agli utenti con contatti in conflitto.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema con l'apertura di file configurati dal server con l'autenticazione basata su moduli.

- È stato risolto un problema per cui i file di PowerPoint con grafici o cartelle di lavoro incorporati potevano causare errori durante il salvataggio del file.

- È stato risolto un problema per cui lo zoom avanti e indietro dall’area della presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.

- È stato risolto un problema per cui le diapositive non erano centrate dopo l’ingrandimento con la rotellina del mouse.

- È stato risolto un problema per cui le scelte rapide da tastiera e il controllo ortografico non funzionavano come previsto con l’uso di una tastiera inglese svizzera (QWERTZ).

- È stato risolto un problema per cui un riquadro commenti chiuso dall'utente veniva riaperto automaticamente.

- È stato risolto un problema per cui l'editor diapositive si sovrapponeva da una diapositiva a quella successiva.

### <a name="project"></a>Project

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.

- È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.

- È stato risolto un problema per cui Project si arrestava in modo anomalo dopo aver fatto clic su Opzioni.

- Abbiamo risolto un problema che impediva l'eliminazione o la riassegnazione di attività isolate dopo l'eliminazione del piano padre.

### <a name="visio"></a>Visio

- C’è stata una regressione nel codice dipendente che è state corretta. Ora le immagini sono sottoposte a rendering tramite i servizi Visio in esecuzione su SharePoint OnPrem.

### <a name="word"></a>Word

- È stato risolto un problema per cui i timbri data/ora nei riquadri dei commenti non erano basati sull'ora locale del sistema.

- È stato risolto un problema durante l'apertura di documenti di Word tramite consegna di documenti personalizzati (aspx) con URL contenente un componente di query.

- È stato risolto un problema per cui non era possibile visualizzare il testo copiato e incollato in un riquadro dei commenti.

- È stato risolto un problema per cui i collegamenti ipertestuali nei commenti non funzionavano.

- È stato risolto un problema per cui lo zoom avanti e indietro dall’area della presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.

- È stato risolto un problema per cui i commenti non erano sincronizzati tra l'app web e l'applicazione desktop.

- È stato risolto un problema per cui le bolle di suggerimenti per i commenti apparivano sfocate con lo zoom al 100%.

- È stato risolto un problema per cui non era possibile aggiungere un nuovo commento in un documento vuoto.

- È stato risolto un problema per cui incollare HTML in WordMail per il Calendario non funzionava.

- È stato risolto un problema per cui la risposta a un commento in una sessione condivisa in alcuni casi causava il blocco di Word.

- È stato risolto un problema per cui l'inserimento o l'aggiornamento dell’indice in un documento contenente più di cento voci comportava l'arresto anomalo dell'applicazione.

- È stato risolto un problema per cui l'abilitazione di Word 2007 e in seguito dei documenti e dei modelli binari causava il fallimento di alcuni casi di creazione condivisa.

- È stato risolto un problema per cui i file con valori XML personalizzati si aprivano in modo estremamente lento.

- È stato risolto un problema per cui i file con lunghi nomi di percorso, oltre 32K, non si aprivano e non veniva visualizzato un messaggio di errore appropriato.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Abbiamo esaminato e risolto il problema per cui una distribuzione di Office 365 ProPlus tramite InTune veniva sospesa dopo un arresto del sistema operativo.

- È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA contenenti riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso venivano visualizzati dall'applicazione di Office come danneggiati durante il caricamento.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-june-08"></a>Versione 2005: 08 giugno
*Versione 2005 (Build 12827.20336)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema con la finestra di dialogo Sostituisci caratteri, in cui il menu a discesa Sostituisci carattere mostrava solo i tipi di carattere all'interno della presentazione anziché quelli installati nel sistema.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-june-04"></a>Versione 2005: 04 giugno
*Versione 2005 (Build 12827.20320)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Rimani al passo con i tempi! La tipologia di dati con data/ora estesa offre una maggiore precisione:** introducendo un tipo di dati nuovo e migliorato.  Per migliorare la compatibilità della sintassi con SQL e per aumentare l'accuratezza e il livello di dettaglio nei record che includono date e ore, il tipo di dati DateTime2 viene implementato in Access. Questa tipologia aggiuntiva di dati data/ora includerà un intervallo di date più ampio (da 0001-01-01 a 9999-12-31), con precisione temporale più specifica (nanosecondi, anziché secondi), per cui sarà possibile fornire ed eseguire calcoli. Per abilitare, selezionare Nuovo campo > Data e ora estesa. [Altre informazioni](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a>Excel

- **Creare tabelle pivot da set di dati in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di dati archiviati in Power BI in pochi clic. Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI. Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI.

### <a name="outlook"></a>Outlook

- **Opzione per riaprire rapidamente gli elementi dalla sessione Outlook precedente:** è stata aggiunta un'opzione per riaprire rapidamente gli elementi da una sessione di Outlook precedente.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="powerpoint"></a>PowerPoint

- Ciò risolve un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.


### <a name="office-suite"></a>Applicazioni Office

- È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-may-29"></a>Versione 2005: 29 maggio
*Versione 2005 (Build 12827.20268)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità

### <a name="excel"></a>Excel

- **Visualizzazione foglio:** è possibile ordinare e filtrare mentre si collabora con altri utenti nella versione desktop di Excel.

### <a name="outlook"></a>Outlook

- **Altri pulsanti aggiunti agli avvisi popup di Outlook:** i pulsanti di azione rapida sono ora visualizzati negli avvisi popup di Outlook quando si esegue Outlook in Windows 10.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti



### <a name="outlook"></a>Outlook

- È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso  Stato dell’antivirus: non valido. Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato installato correttamente l’antivirus.

### <a name="office-suite"></a>Applicazioni Office

- L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero. La modifica potrebbe risolvere il problema.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-may-21"></a>Versione 2005: 21 maggio
*Versione 2005 (Build 12827.20210)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.


- In alcuni casi, se si fa clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro verrà nascosta.


### <a name="outlook"></a>Outlook

- È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.


- È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-may-14"></a>Versione 2005: 14 maggio
*Versione 2005 (Build 12827.20160)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.

### <a name="powerpoint"></a>PowerPoint

- **Non c'è bisogno del clicker grazie agli auricolari:** i Surface Earbuds permettono di controllare le presentazioni di PowerPoint. Importante: per usare i gesti per controllare le presentazioni è necessario associare gli auricolari Surface Earbuds nell'app Surface Audio per Windows 10. Le istruzioni per iniziare a usare l'app Surface Audio in Windows 10 sono disponibili qui. [Altre informazioni](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- **Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.

### <a name="word"></a>Word

- **Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel

- Sono state aumentate le dimensioni dei controlli per la modifica del riferimento di cella nella finestra di dialogo Barre di errore personalizzate usata con i grafici.

- È stato risolto un problema di rendering dei valori in un asse data nella tabella dati del grafico.

- È stato risolto un problema che impediva la disabilitazione delle interruzioni di pagina dopo il passaggio a Layout di pagina o Anteprima interruzioni di pagina.

- È stato risolto un problema di perdita degli stili di linea del grafico dopo aver nascosto e visualizzato le colonne con i dati della serie.

- È stato risolto un problema per cui l'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.

- È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.

- È stato risolto un problema per cui il collegamento esterno non funzionava dopo la riapertura del file se il percorso del file è troppo lungo.

- Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.

- Application.Evaluate (VBA) in alcuni casi non funzionava per le funzioni definite dall'utente.

- Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.

- Questa modifica risolve un problema per cui le informazioni con formattazione condizionale non venivano salvate correttamente nei file XLSB.

- Questa modifica consente di risolvere un problema per cui il valore R quadrato per una linea di tendenza (nel caso di intercetta y forzata), non era corretto, anche se la funzione REGR.LIN restituiva il valore corretto.

- Questa modifica risolve un problema per cui il formato della linea di tendenza del grafico personalizzata non sempre veniva salvato.

- Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità legacy "cartella di lavoro condivisa".

- È stato risolto il problema che poteva impedire il salvataggio della formattazione personalizzata dei grafici pivot quando era abilitata l'opzione "Inverti se negativo".

- È stato risolto un problema per cui non veniva salvata la formattazione personalizzata per un singolo punto dati in un grafico pivot se era stata selezionata l'opzione "Inverti se negativo".

- Questa modifica risolve un problema per cui il carattere "@" caricato in un file CSV comportava la conversione della stringa dopo il carattere "@" in una formula.

- È stato risolto un problema per cui i valori decimali della funzione sequenza non venivano arrotondati correttamente.

### <a name="onenote"></a>OneNote

- È stato risolto un problema per cui le interruzioni di riga venivano archiviate come schede verticali.

### <a name="outlook"></a>Outlook

- Risolve un problema che impediva agli utenti di aggiungere un gruppo di contatti personale come partecipante alla riunione.

- È stato risolto un problema per cui il pulsante categorizza per i calendari di gruppo sulla barra multifunzione di Office era disabilitato.

- È stato risolto un problema che causava l'arresto anomalo di Outlook all'apertura di file con estensione msg o oft salvati in locale dopo un aggiornamento di Windows.

- È stato risolto un problema per cui i clienti aziendali con cartelle di gruppo non implementate o non funzionanti visualizzavano il messaggio "Outlook non risponde".

- È stato risolto un problema che impediva il caricamento dei collegamenti sicuri molto lunghi su cui gli utenti facevano clic nel client desktop di Outlook a causa di un troncamento.

- È stato risolto un problema per cui le cartelle di Outlook con nomi contenenti caratteri del set di caratteri a due byte (DBCS) talvolta scomparivano durante la sincronizzazione con il server. Questo succedeva con Outlook configurato con un account IMAP ed eseguito in un sistema con le impostazioni locali impostate su giapponese.

- È stato risolto un problema per cui le regole di eliminazione create per le cassette postali diverse da quella principale dell'utente non erano più valide.

- È stato risolto un problema che causava la perdita di allegati quando si inoltrava un messaggio crittografato.

- È stato risolto un problema che impediva la visualizzazione in Assistente Pianificazione dell'oggetto delle riunioni pianificate tra più di 2 mesi.

- È stato risolto un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.

- È stata aggiunta la funzionalità della configurazione di firma predefinita S/MIME tramite criteri di gruppo.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui, se un utente creava un commento senza pubblicarlo e chiudeva il riquadro Commenti, quindi apriva una nuova finestra, si spostava tra più diapositive, chiudeva la finestra e infine riapriva il riquadro Commenti nella presentazione originale, i commenti bozza non erano disponibili.

- È stato risolto un problema per cui, posizionando il puntatore del mouse sul simbolo dell'asterisco (*), non venivano mostrati il nome utente dell'ultima persona ad aggiornare il documento e la data della modifica.

### <a name="project"></a>Project

- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.

- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si cambia il campo Stato bacheca in un progetto connesso a un elenco attività di SharePoint.

- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.

- È stato risolto un problema per cui se Project era connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies aveva esito negativo quando veniva aggiunto un elemento Lag.


### <a name="word"></a>Word

- È stato risolto un problema per cui l'inserimento di commenti in un documento in modalità di collaborazione non sempre funzionava.

- Questo cambiamento risolve un problema per cui la scheda Persone lampeggiava se veniva selezionata la menzione con @.

- Abilitando l'opzione "Mostra segnalibri", i segnalibri non venivano visualizzati. Questo problema è stato risolto.

- È stata risolto il problema per cui alla chiusura di un documento con commenti in bozza veniva chiesto di confermare la chiusura del documento senza salvare la bozza. Annullando il messaggio, il documento veniva chiuso invece di rimanere aperto.

- È stato risolto un problema di copia e incolla di intestazioni.

- È stato risolto un problema per cui durante la traduzione di un commento pubblicato veniva visualizzato l'errore ‘L'inserimento del testo tradotto non è riuscito’.

- Questa modifica risolve un problema per cui il testo con collegamenti ipertestuali poteva non essere visualizzato se era abilitata l'opzione: "Mostra codici di campo anziché i relativi valori".

- In visualizzazione Web/Strumento di lettura immersiva, la selezione di un suggerimento determinava lo scorrimento verso l'alto anche se era già visualizzato. Questo problema è stato risolto.

- È stato risolto un problema per cui, quando si provava a salvare un file contenente una macro con un nuovo nome, il file veniva salvato con estensione docx e il nome file WRO0004.docx, indipendentemente dall'immissione dell'utente, rendendo il documento inutilizzabile.

### <a name="office-suite"></a>Applicazioni Office

- Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni.  In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola.  Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a>Versione 2004: 11 marzo
*Versione 2004 (Build 12730.20270)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

### <a name="outlook"></a>Outlook

- **Collegamenti migliorati nei messaggi di posta elettronica:** quando si include un collegamento a un file, il nome del file sostituisce l'URL. È possibile modificare le autorizzazioni per consentire l'accesso a tutti i destinatari. [Altre informazioni](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

### <a name="powerpoint"></a>PowerPoint

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.  [Altre informazioni](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a>Word

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un arresto anomalo quando venivano visualizzati avvisi popup.



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-2004-may-04"></a>Versione 2004: 4 marzo
*Versione 2004 (Build 12730.20250)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai. [Altre informazioni](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Notifica di evento imprevisto per gli amministratori IT:** gli amministratori globali dei tenant di Microsoft 365 e gli amministratori delle app di Office verranno avvisati degli eventi imprevisti di Outlook e Office 365 Exchange che interessano gli utenti tramite una nuova notifica nel riquadro a destra in Outlook per Windows. [Altre informazioni](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="office-suite"></a>Famiglia di prodotti Office

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a>Versione 2004: 29 aprile
*Versione 2004 (Build 12730.20236)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Protezione dei dati nel gruppo:** l'etichetta di riservatezza che si sceglie quando si crea un gruppo viene applicata ai messaggi di posta elettronica, ai documenti e ai siti del team del gruppo.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2004-april-25"></a>Versione 2004: 25 aprile
*Versione 2004 (Build 12730.20206)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.

### <a name="project"></a>Project

- È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.


### <a name="office-suite"></a>Applicazioni Office

- Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2004-april-21"></a>Versione 2004: 21 aprile
*Versione 2004 (Build 12730.20182)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- Risolve un problema che ha causato il cambiamento inatteso della larghezza del riquadro delle cartelle.

- Risolve un problema che causava un blocco uscendo da Outlook.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2004-april-15"></a>Versione 2004: 15 aprile
*Versione 2004 (Build 12730.20150)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Il supporto per il connettore Facebook sta per terminare:** a partire dal 2020 aprile, Excel non supporterà più connessioni dati esterne che usano il connettore Facebook.

### <a name="outlook"></a>Outlook

- **Nuova opzione per disabilitare i suggerimenti di @menzioni durante la composizione dei messaggi di posta elettronica in Outlook:** si trovano i suggerimenti per la selezione delle menzioni più fastidiosi che utili? Ora è possibile disattivarli.

### <a name="powerpoint"></a>PowerPoint

- **Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione.

### <a name="word"></a>Word

- **Annotare la copia privata:** è possibile creare note scritte a mano visibili solo a se stessi creando una copia privata di un documento condiviso. Passare alla Visualizza > Crea una copia privata per iniziare.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Sono stati risolti problemi relativi al ridimensionamento e all'aggiornamento di tabelle nel riquadro attività.

- È stato risolto un problema per cui nell'interfaccia utente delle versioni internazionali di Access venivano visualizzate stringhe in inglese.

### <a name="excel"></a>Excel

- È stato risolto un problema per cui, selezionando un intervallo di celle in un foglio, veniva selezionata una singola cella.

- Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.

- È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.

- Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.

- È stato risolto un problema di prestazioni che talvolta gli utenti sperimentavano quando modificavano un intervallo di celle elevato a livello di programmazione.

- È stato risolto un problema di prestazioni che si verificava durante l'apertura di file CSV in ambiente giapponese.

- È stato risolto un problema per cui, inserendo un modello di grafico definito dall'utente come predefinito, veniva salvato come istogramma.

- È stato risolto un problema per cui le etichette dati apparivano vuote quando le celle di dati sottostanti non avevano una didascalia.

- È stato risolto un problema per cui Excel poteva smettere di rispondere riducendo le dimensioni di un grafico con alcuni intervalli dell'asse x.

- È stato risolto un problema per cui, durante la condivisione/creazione in modalità condivisa di un foglio di Excel con lo stile di riferimento R1C1 abilitato, passando il mouse sull'icona di presenza utente non compariva il riferimento di cella attivo in modalità R1C1.

- Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.

### <a name="outlook"></a>Outlook

- Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.

- Questa modifica risolve un problema per cui le ultime modifiche apportate alle bozze di messaggi di posta elettronica non venivano aggiornate.

- È stato risolto un problema per cui fare clic con il pulsante destro del mouse su un file e scegliere "Invia a" non funzionava.

- È stato risolto un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.

- È stato risolto un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.

- È stato risolto un problema che causava la mancata attivazione di alcuni promemoria cambiando il fuso orario in un computer.

- È stato risolto un problema che causava l'arresto anomalo provando a visualizzare le proprietà di un modulo dell'organizzazione.

- È stato risolto un problema per cui, se un utente aveva personalizzato il percorso di ricerca per la Rubrica, l'ambito di risoluzione dei nomi di Outlook era limitato al percorso personalizzato e non includeva l'elenco indirizzi globale.

- È stato risolto un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.

- È stato risolto un problema che impediva agli utenti di aggiungere una firma rispondendo a un messaggio protetto con Digital Rights Management da una finestra Inspector quando l'utente non ha l'autorizzazione di proprietario per il messaggio a cui sta rispondendo.

- È stato risolto un problema che impediva agli utenti di aggiungere altri allegati da un percorso Web a una riunione creata in precedenza.

- È stato risolto un problema per la cui i dati relativi all'ultima modifica di un file venivano aggiornati quando si aggiungeva un allegato a un messaggio di posta elettronica o si salvava un allegato da un messaggio di posta elettronica trascinandolo, anziché tramite un menu.

- È stato risolto un problema per cui nel riquadro Trova espanso premendo INVIO non si avviava la ricerca, ma era necessario fare clic sul pulsante Cerca.

- È stato risolto un problema per cui, all'interno di un set di risultati della ricerca restituiti, l'ordinamento dei risultati in base alla categoria non mostrava i colori delle categorie.

- È stato risolto un problema per cui la ricerca non mostrava informazioni sugli utenti quando l'opzione "Mostra fotografie dell'utente quando disponibili" era disabilitata.


### <a name="powerpoint"></a>PowerPoint

- Questa modifica risolve un errore che poteva causare un errore nel salvataggio dei file di PowerPoint contenenti emoji.

- Questa modifica risolve un problema per cui, nel rendering di un grafico di Excel legacy incorporato come oggetto OLE in PowerPoint o Word, non sempre veniva visualizzato il titolo del grafico.

- È stato risolto un problema per cui la formattazione di un testo copiato da Excel a PowerPoint poteva essere modificata.

- Questa modifica risolve un problema per cui la ricerca di caratteri speciali con l'opzione "Solo parole intere" non funzionava come previsto.

### <a name="project"></a>Project

- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.

- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.

- È stato risolto un problema per cui l'evento "ProjectBeforeTaskChange" di Visual Basic, Applications Edition (VBA) non veniva attivato quando un utente faceva clic sul pulsante "Disattiva" disponibile nella barra multifunzione Attività nel gruppo Programmazione.

- Impostando i dettagli su predecessore o successore da una visualizzazione di tipo modulo, l'evento ProjectBeforeTaskChange Visual Basic Applications (VBA) non sempre acquisiva le modifiche. Ad esempio, eliminando una dipendenza e facendo clic su OK nel modulo, l'evento non veniva attivato. Questo comportamento è stato corretto.

- È stato risolto un problema per cui i valori più recenti per il costo effettivo del lavoro eseguito (ACWP) non venivano visualizzati dopo avere apportato una modifica, ad esempio dopo aver cambiato la data.

- È stato risolto un problema per cui, aprendo un progetto dal menu Usati di recente (MRU), il file di progetto veniva aperto con accesso in lettura/scrittura.

- Questa modifica risolve un problema per cui, creando un'attività manuale con una data e un'ora di inizio, ma non una durata, l'attività veniva visualizzata con un orario non corretto nella sequenza temporale.

- È stato risolto un problema per cui la stampa di una sequenza temporale usando un calendario Hijri comportava l'omissione o la duplicazione di un mese nella visualizzazione stampa.

- Questa modifica risolve un problema relativo all'uso di Pianificazione team con oggetti GDI, che poteva comportare la sovrassegnazione di oggetti GDI e di conseguenza condizioni di memoria insufficiente.

- È stato risolto un problema per cui, eseguendo "CustomFieldValueListGetItem" quando non esiste una tabella di ricerca per il campo personalizzato, viene creata una tabella di ricerca vuota anche se non dovrebbe esserlo.

- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.

- È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.

### <a name="word"></a>Word

- Questa modifica risolve un problema per cui, posizionando il cursore su un suggerimento, non veniva evidenziata la relativa scheda.

- Questa modifica risolve un problema per cui selezionando più pagine selezionata nel menu Visualizza, il riquadro Commenti poteva apparire vuoto.

- È stato risolto un problema per cui la funzionalità di invio commenti era disabilitata.

- Questa modifica risolve un problema che causava la scomparsa temporanea del testo nelle forme raggruppate usando lo strumento di selezione Lazo.

- Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.

- Questa modifica risolve un problema per cui, nel rendering di un grafico di Excel legacy incorporato come oggetto OLE in PowerPoint o Word, non sempre veniva visualizzato il titolo del grafico.

- Questa modifica risolve un problema che impediva all'account manager di inviare messaggi, causando un blocco nelle applicazioni di terze parti.

- Questa modifica risolve un problema della visualizzazione a due pagine per cui, creando un commento, l'ancoraggio del commento non sempre era visibile.

- È stato risolto un problema per cui digitando o modificando un commento e usando la combinazione di tasti CTRL+A veniva selezionato il testo nell'area di disegno anziché nella scheda del commento.

- È stato risolto un problema per cui, in un paragrafo il cui stile è un predecessore di uno stile collegato a un elenco, la numerazione dell'elenco poteva andare persa.

- Questa modifica risolve un problema per cui il Sommario veniva aggiornato con stili del titolo non presenti nel documento.

- È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.

- È stato risolto un problema che si verificava unendo due documenti in uno.

- È stato risolto un problema per cui le firme digitali salvate nei documenti di Word venivano rimosse al momento dell'invio dei documenti.

- È stato risolto un problema per cui quando si contrassegnavano le revisioni contenenti delle equazioni si verificava un errore durante il salvataggio del file.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a>Versione 2003: 14 aprile
*Versione 2003 (Build 12624.20466)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- Diverse correzioni di bug e miglioramenti delle prestazioni.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a>Versione 2003: 9 aprile
*Versione 2003 (Build 12624.20442)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="outlook"></a>Outlook

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="powerpoint"></a>PowerPoint

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)

### <a name="word"></a>Word

- **Selezione di contenuti Premium di M365:** dare vita ai propri documenti. Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a>Versione 2003: 3 aprile
*Versione 2003 (Build 12624.20410)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- L'uso di Application.Evaluate di VBA talvolta non funzionava per le funzioni definite dall'utente.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.

### <a name="project"></a>Project

- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.

### <a name="word"></a>Word

- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a>Versione 2003: 31 marzo
*Versione 2003 (Build 12624.20382)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Riquadro attività Aggiungi tabelle:** il nuovo riquadro attività Aggiungi tabelle è finalmente disponibile. Questa funzionalità consente la selezione/selezione multipla più semplice delle tabelle che si vogliono aggiungere/rimuovere nell'intervallo di query, senza passare alla finestra di dialogo "Mostra tabelle" per le query e per la visualizzazione relazioni. Include anche una nuova scheda "collegamenti" per visualizzare le tabelle collegate, una casella di ricerca per filtrare l'elenco corrente, la funzionalità "trascinamento della selezione" e altro ancora.


[//]: # (NON RIMUOVERE I DETTAGLI DELLE FUNZINALITÀ DI INIZIO CONTENUTO)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="project"></a>Project

- <div><span style="display:inline !important;">È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione di protezione del lavoro effettivo.</span><br></div>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-march-25"></a>Versione 2003: 25 marzo
*Versione 2003 (Build 12624.20320)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-2003-march-23"></a>Versione 2003: 23 marzo
*Versione 2003 (Build 12624.20296)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-2003-march-21"></a>Versione 2003: 21 marzo
*Versione 2003 (Build 12624.20276)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online. Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.

- **Aggiornamento visivo del calendario:** l'anno scorso abbiamo presentato un'esperienza di posta elettronica rinnovata e quest'anno è il turno del calendario. Gli aggiornamenti sono innovativi ma familiari, in modo che gli utenti esperti di Outlook siano subito più produttivi.

### <a name="powerpoint"></a>PowerPoint

- **Aggiornamento delle diapositive durante la presentazione:** è possibile aggiornare le diapositive modificate da altri autori durante la presentazione.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a>Versione 2003: 16 marzo
*Versione 2003 (Build 12624.20224)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.

### <a name="outlook"></a>Outlook

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.

### <a name="powerpoint"></a>PowerPoint

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.

### <a name="word"></a>Word

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.

### <a name="office-suite"></a>Applicazioni Office

- **Riquadri a schede:** ora è possibile passare da un riquadro all'altro usando un'interfaccia a schede sul lato destro dell'app. L'interfaccia utente sarà visibile solo se sono presenti almeno due riquadri.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava la visualizzazione del processo di Outlook in esecuzione in Gestione attività dopo la chiusura.



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-march-10"></a>Versione 2003: 10 marzo
*Versione 2003 (Build 12624.20176)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel
- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate. [Altre informazioni](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="powerpoint"></a>PowerPoint
- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate. [Altre informazioni](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)

### <a name="word"></a>Word
- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate. [Altre informazioni](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions)
</br>

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.

- È stato risolto un problema riscontrato dagli utenti quando rinominavano le misure delle tabelle pivot.

- È stato risolto un problema per cui il testo in un filtro dati non veniva ridimensionato correttamente nell'anteprima di stampa.

- È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.

- È stato risolto un problema che causava il lampeggio dell’interfaccia utente durante l'esecuzione di una macro che interagiva con la barra multifunzione.

- È stato risolto un problema per cui i file CSV venivano caricati erroneamente quando la prima parola nel file era TABLE.

- È stato risolto un problema per cui gli utenti potevano riscontrare arresti anomali durante il passaggio da una cartella di lavoro a un’altra con un livello di zoom diverso.

- È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.

- La modifica risolve un errore di run-time nel modello a oggetti e l'arresto anomalo dell'app (Excel, Word) che si verificano quando i componenti aggiuntivi chiedono elementi host nei documenti/fogli di lavoro che contengono forme con blocchi noSelect.

- Risolve un problema che causava un arresto anomalo di Outlook sincronizzando le impostazioni.



### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui una regola creata in Outlook Web Access veniva cancellata nel server Exchange generando un conflitto.

- È stato risolto un problema che causava un arresto anomalo di Outlook sincronizzando le impostazioni.

- È stato risolto un problema per cui nella modalità scura di Outlook non veniva visualizzato l'elenco a discesa nel campo "Da:".

- È stato risolto un problema per cui Outlook generava in modo inatteso l'output di registrazione in alcuni scenari, anche quando la registrazione era disattivata.

- È stato risolto un problema che impediva agli utenti di aprire messaggi di cartelle pubbliche quando Outlook era rimasto in esecuzione durante la notte.

- È stata risolta una race condition in cui i pulsanti "Consenti" e "Nega" nella pagina delle autorizzazioni venivano disabilitati durante il flusso di lavoro di autenticazione per l'aggiunta di un account Gmail.

- È stato risolto un problema per cui gli utenti perdevano l'accesso alla finestra di dialogo delle autorizzazioni del calendario &quot;Opzioni disponibilità&quot;.

- È stato risolto un problema per cui veniva visualizzato l'avviso &quot;Si è verificato un problema con l'apertura di questo elemento&quot; quando si aprivano le istanze di riunioni ricorrenti inviate da un fuso orario diverso.

- È stato risolto un problema a causa del quale gli utenti potrebbero non essere in grado di riaprire un file .msg dopo aver trascinato un allegato da quel messaggio.

- È stato risolto un problema a causa del quale, dopo aver caricato un allegato da Outlook a OneDrive, il nome file potrebbe cambiare se il nome dell'allegato contiene delle parentesi.

- È stato risolto un problema che impediva agli utenti di allegare un file al messaggio di posta elettronica tramite Esplora file se il file era aperto in un'altra applicazione.

- È stato risolto un problema che causava un arresto anomalo di Outlook sincronizzando le impostazioni.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui le anteprime consigliate lampeggiavano durante il passaggio del mouse su di esse. In alcuni casi questo causava un arresto anomalo di PowerPoint.

- È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.

- È stato risolto un problema che causava un errore durante il salvataggio di un documento in PowerPoint o Word se il documento conteneva un grafico di Excel.



### <a name="project"></a>Project

- È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.

- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.

- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.

### <a name="visio"></a>Visio

- Nel riquadro Informazioni forma, la sezione Proprietà forma mostrava dettagli incoerenti quando il file veniva aperto nella versione desktop di Visio. Ora il problema è stato risolto.

- Nelle versioni precedenti al 2016, le bitmap importate non venivano visualizzate a causa di alcuni controlli di sicurezza. Questo problema è stato risolto nell'abbonamento di Visio.

### <a name="word"></a>Word

- È stato risolto un problema per cui le schede di commento non venivano sempre evidenziate quando si passava il puntatore del mouse su di esse.

- È stato risolto un problema per cui spostandosi tramite TAB in una scheda commento, lo stato attivo sulla casella di modifica del commento non era visibile.

- È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.

- Durante una sessione di creazione condivisa di documenti attiva, l'aggiunta diretta di un'immagine in una scheda di commento può comportare l'aggiunta di un contrassegno. Questo problema è stato risolto.

- Se veniva inserito un controllo in un'equazione, ad esempio un controllo contenuto testo, il salvataggio e l'apertura del file comportavano un errore di contenuto illeggibile.

- È stato risolto un problema per cui non era possibile salvare un file protetto in precedenza da password, in uno spazio di archiviazione cloud.

- È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.




### <a name="office-suite"></a>Applicazioni Office

- Se si usavano proprietà di scelta multipla, ricerca o metadati gestiti con documenti di Word, Excel o PowerPoint e si eseguiva il salvataggio in una raccolta documenti di SharePoint, queste proprietà erano limitate a 255 caratteri. Quando queste proprietà superavano i 255 caratteri, non era possibile salvare i documenti. Con questa modifica, il limite è stato aumentato a 2048 caratteri.

- È stato risolto un problema in Word/Excel/PowerPoint per cui il nome dell'entità utente (UPN) non distingueva più tra maiuscole e minuscole, causando la visualizzazione di un numero inferiore di errori durante l'uso dei file in SharePoint.

- È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.


[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2002-march-05"></a>Versione 2002: 5 marzo
*Versione 2002 (Build 12527.20278)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.


## <a name="version-2002-march-04"></a>Versione 2002: 4 marzo
*Versione 2002 (Build 12527.20264)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="project"></a>Project
- <div>È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</div>


### <a name="office-suite"></a>Famiglia di prodotti Office
- <div>È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a>Versione 2002: 1 marzo
*Versione 2002 (Build 12527.20242)*

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- <div>È stato risolto un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a>Versione 2002: 24 febbraio
*Versione 2002 (Build 12527.20194)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-2002-february-22"></a>Versione 2002: 22 febbraio
*Versione 2002 (Build 12527.20186)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-2002-february-21"></a>Versione 2002: 21 febbraio
*Versione 2002 (Build 12527.20174)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla. Cercare e sostituire il testo nella visualizzazione SQL. Selezionare più tabelle nella finestra Relazioni.

### <a name="outlook"></a>Outlook

- **Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web? Outlook ora consente di rimanere connessi in scenari di questo tipo.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- <div style="box-sizing:border-box;">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.&nbsp;</div><div><span style="display:inline !important;"></span><br></div>


### <a name="outlook"></a>Outlook

- <div>Risolto un problema per cui la virgola nel campo Luogo della riunione cambiava in punto e virgola.</div>


- <div>Risolto un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.</div>


- <div>Risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.&nbsp;</div>


- <div>Risolto un problema per cui gli utenti con il tema Nero visualizzavano l'elenco a discesa &quot;Da&quot; con il testo bianco su sfondo bianco.</div>


- <div><span style="display:inline !important;">Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.</span><br></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a>Versione 2002: 18 febbraio
*Versione 2002 (Build 12527.20138)*

## <a name="version-2002-february-11"></a>Versione 2002: 11 febbraio
*Versione 2002 (Build 12527.20092)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo. I messaggi trascinati verranno condivisi con tutti i membri del gruppo.

### <a name="word"></a>Word

- **Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Icone delle barre di stato più chiare:** ora le icone della barra di stato sono più facili da vedere.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database. Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.

- Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB. L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.

- Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.


### <a name="excel"></a>Excel

- È stato risolto un problema i comandi di commento nel menu di scelta rapida non venivano visualizzati.


- È stato risolto un problema che causava arresti anomali convertendo il testo in colonne con celle con una matrice con espansione.


- È stato risolto un problema relativo all'arresto anomalo di Excel quando si usa Testo in colonne con matrici dinamiche.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui scorrendo il calendario con la visualizzazione per mese, non è possibile visualizzare gli eventi del calendario precedente.

- Le cartelle salvate in "Preferiti" nel riquadro di spostamento a sinistra scomparivano in modo intermittente.


- È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.


- È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.

- È stato risolto un problema che causava un arresto anomalo annullando la configurazione dell'account.


- È stato risolto un problema per cui i messaggi di posta elettronica in scadenza in base ai criteri di conservazione visualizzavano due etichette. Una indicava che la posta sarebbe scaduta entro un giorno e l'altra entro due giorni.


- È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix.


### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui l'input penna non era corretto o non veniva eseguito durante le animazioni dell'input penna di PowerPoint.

- È stato risolto un problema per cui, dopo aver chiuso un file, PowerPoint non lo rimuove immediatamente dalla raccolta presentazioni se sono in esecuzione gestori di eventi. Di conseguenza, il numero di presentazioni aperte riportate dal modello a oggetti non è corretto e viene impedita la chiusura di PowerPoint.


- È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.


### <a name="project"></a>Project

- È stato risolto un problema per cui il 100% delle attività di tipo durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.


### <a name="word"></a>Word

- L'aggiornamento e lo scorrimento di un sommario possono talvolta visualizzare un'area grigia sul documento.


- È stato risolto un problema per cui l'utilizzo di "Sfoglia" per salvare un file non funzionava se un commento veniva scritto ma non pubblicato e l'utente provava a salvare il file.


- È stato risolto un problema per cui, quando ci si spostava tra le schede commento, talvolta il commento inizialmente selezionato veniva visualizzato con un'evidenziazione della selezione.


- È stato risolto un problema per cui la formattazione in corsivo veniva persa dopo aver modificato un commento, applicato il corsivo al testo e postato il commento.


- È stato risolto un problema per cui l'indicatore del commento non era visibile in modalità di lettura con colore di pagina Inverso.


- È stato risolto un problema per cui, se un documento è stato creato in modo condiviso, la versione bozza di un commento radice potrebbe non essere mantenuta.


- Con SlideTrack abilitato e il riquadro commenti chiuso, CTRL + ALT + M potrebbe non aprire il riquadro commenti.


- È stato risolto un problema per cui quando si aggiungeva una @menzione in una tabella poteva venire generato il messaggio di errore: "una tabella in questo documento è stata danneggiata".


- È stato risolto un problema per cui nel menu di scelta rapida dei commenti non venivano visualizzati i comandi per i commenti (Modifica commento, Rispondi a commento, Elimina commento, Risolvi commento).


### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema che potrebbe aver causato l'installazione errata del pacchetto di strumenti di correzione norvegese Nynorsk (nn-no).


- Questo cambiamento affronta i problemi segnalati con le schede grafiche che utilizzano le GPU integrate Intel.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)
