---
title: Note sulla versione per le versioni in 2017 semi-annuale canale (personalizzati)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Consente ai professionisti IT note sulla versione per le versioni del canale e annuale (personalizzati) per Office 365 ProPlus in 2017
ms.openlocfilehash: 6014107ae2471707d226602cc71efaa24f1de310
ms.sourcegitcommit: 5dabd0a6045b54940da7821e2349ec78b6b99d00
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/04/2018
ms.locfileid: "19556162"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Note sulla versione per le versioni in 2017 semi-annuale canale (personalizzati)

Queste note sulla versione vengono fornite informazioni sulle nuove caratteristiche, aggiornamenti di sicurezza e non correlati alla sicurezza gli aggiornamenti inclusi negli aggiornamenti semi-annuale canale (personalizzati) per Office 365 ProPlus nelle 2017.
 
> [!NOTE]
> - Di seguito inoltre fornisce informazioni sulle nuove caratteristiche, aggiornamenti di sicurezza e aggiornamenti non correlati alla sicurezza per Visio Pro per Office 365 e il Client Desktop Project Online.
> - Queste informazioni si applicano anche a Office 365 Business, ovvero la versione di Office fornito con alcuni piani di Office 365, ad esempio Business Premium.
> - Canale semi-annuale (personalizzati) è stato denominato prima versione del canale rinviata prima 2017 settembre.

## <a name="version-1708-december-12"></a>Versione 1708: 12 dicembre
*Versione 1708 (Build 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): Microsoft Excel vulnerabilità

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove l'utente in modo errato Visualizza un messaggio di errore "Errore irreversibile" quando si apre un Office 2007 o meno recente di cartella di lavoro (file con estensione xls o xla) con le macro.
-   Risolvere problemi in apertura di una cartella di lavoro da riga di comando potrebbe causare la perdita di formattazione del testo in una cella.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti di sicurezza
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilità Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti di sicurezza
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilità Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Project: Aggiornamenti Non correlati alla sicurezza
-   Risolvere un problema problemi cui campo personalizzato del progetto livello dati possono ottenere perduti su Salva.
-   Risolvere i problemi in cui non riuscito save è un file danneggiato e causare progetto in modo anomalo all'apertura.
-   Risolvere problemi in apertura di un piano di progetto potrebbe causare un arresto anomalo del sistema.

### <a name="word-security-updates"></a>Word: Aggiornamenti di sicurezza
-   [170021 consulenza](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): difesa di Microsoft Office nell'aggiornamento della profondità



## <a name="version-1708-november-14"></a>Versione 1708: Novembre 14
*Versione 1708 (Build 8431.2110)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui si tenta di selezionare il testo in una casella di testo o in una casella combinata viene visualizzata a selezionare tutto il testo, anziché la selezione indicazione.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   [CVE-2017-11877](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877): Bypass funzionalità di Microsoft Excel vulnerabilità
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilità di danneggiamento della memoria di Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui l'utente non può chiudere una cartella di lavoro in visualizzazione protetta quando il nome del file contiene parentesi quadre.
-   Risolvere problemi dove, quando l'utente tenta di inserire un oggetto in una cartella di lavoro esistente, Excel si blocca quando l'utente fa clic su Sfoglia.
-   Risolvere problemi dove selezionando "Ridimensionare forma per correggere il testo" (nella parte casella di testo o di testo le opzioni del riquadro degli strumenti Formato forma) di conseguenza alcuna modifica alla forma.
-   Risolvere problemi dove, quando si apre una cartella di lavoro facendo doppio clic su di esso, non è possibile caricare i caratteri del testo cella e i formati o due identici vengono aperte per un singolo modello.
-   Risolvere problemi di cui non chiusa la prima cartella di lavoro creato durante l'avvio di Excel quando una nuova cartella di lavoro viene aperto o creato.
-   Risolvere i problemi a cui è disallineato posizionamento della descrizione comando quando si trascinano o si trascina il riempimento.
-   Risolvere problemi dove, quando si salva una cartella di lavoro tramite File \> Salva con nome, un nome di file che contiene i periodi visualizzata vuota o troncato nella finestra di dialogo Salva il file.
-   Risolvere problemi dove, quando si salva un file sottoposti a sincronizzazione, Office avrà esito negativo scrivere su disco, ma mantiene Office caricamento del file in OneDrive. Con questa correzione utente verrà ora visualizzato un messaggio di errore e il caricamento non procedere.
-   Risolvere un problema di rendering cui intestazioni e linee nere vengono visualizzati a causa di un driver di grafica presenta il problema.
-   Risolvere problemi in Excel si blocca o non è in grado di salvare la cartella di lavoro dopo l'inserimento di un grafico.
-   Risolvere problemi in cui la linea di interruzione di pagina nell'anteprima interruzioni di pagina è posizionata in modo non corretto.

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui viene visualizzato lo stato attivo nell'elenco dei messaggi passare in modo imprevisto durante l'eliminazione di messaggi.
-   Risolvere un problema che causa l'utente di visualizzare le richieste di autenticazione per l'interazione con allegati.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove, quando si salva un file sottoposti a sincronizzazione, Office avrà esito negativo scrivere su disco, ma mantiene Office caricamento del file in OneDrive. Con questa correzione utente verrà ora visualizzato un messaggio di errore e il caricamento non procedere.
-   Risolvere problemi in cui la modifica e la formattazione del testo dopo un'operazione di annullamento di una tabella causa PowerPoint per arresto anomalo del sistema.
-   Correzione un problema in cui i riferimenti a Flash Player basato YouTube incorporare risultati codici in aperta una finestra nuova per riprodurre il video. Old incorporare codici sono ora aggiornati a video di YouTube basato su riferimenti HTML5 in modo da riprodurle correttamente sul posto.

### <a name="word-security-updates"></a>Word: Aggiornamenti di sicurezza
-   [170020 consulenza](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): difesa di Microsoft Office nell'aggiornamento della profondità

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Word si blocca quando un utente tenta di Salva con nome a un documento esistente in OneDrive for Business quindi Annulla il salvataggio o di tentare di unire le modifiche esistente.
-   Risolvere problemi dove, quando si salva un file sottoposti a sincronizzazione, Office avrà esito negativo scrivere su disco, ma mantiene Office caricamento del file in OneDrive. Con questa correzione utente verrà ora visualizzato un messaggio di errore e il caricamento non procedere.
-   Risolvere problemi in Word può bloccarsi se l'utente passa alla scheda Inserisci subito dopo l'apertura di Word.
-   Risolvere problemi di cui, selezionando il margine caratteri vengono visualizzati nell'angolo superiore sinistro dello schermo durante l'immissione di caratteri.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi con lo zoom e la scala di componenti aggiuntivi di Office in ambiente DPI dinamico.
-   Risolvere problemi in cui il nodo CurrentStatus del provider di servizi (CSP) configurazione Office restituisce una stringa vuota anche se è attualmente installato Office 365 ProPlus.
-   Risolvere un problema che causa .box modifiche di formato di file, un impatto significativo sulla funzionalità delle versioni precedenti di Office nello stesso computer, poiché i file .box sono condivise tra tutte le versioni di un'applicazione di Office nello stesso computer.
-   Risolvere problemi di cui, in alcuni casi, quando si utilizza l'attivazione di computer condiviso, errore viene visualizzato un messaggio che informa che l'app sia stato eseguito un errore che impedisce che funzioni correttamente e che richiede se si desidera eseguire un ripristino dell'utente.



## <a name="version-1708-october-10"></a>Versione 1708: 10 ottobre
*Versione 1708 (Build 8431.2107)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in cui una query non vengono eseguite se la query ha un join con una chiave primaria di una tabella collegata Microsoft Dynamics.
-   Risolvere problemi in posizioni decimali non vengono visualizzati per i valori di valuta in una tabella di Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere i problemi in Excel si blocca quando si apre un. File XLL.
-   Risolvere problemi dove lo stile del motivo di una cella non esegue il rendering correttamente dopo l'aggiunta di un'intestazione o piè di pagina nella visualizzazione Layout di pagina.
-   Risolvere problemi in incollare una copia di una tabella pivot in un'altra cartella di lavoro potrebbe provocare un arresto anomalo del sistema.
-   Risolvere i problemi, quando si sceglie il comando Replace e verrà visualizzata la finestra di dialogo Trova e sostituisci, lo stato attivo della finestra di dialogo dove nella scheda ricerca anziché la scheda Sostituisci.
-   Risolvere problemi in Excel si blocca quando si apre il riquadro attività per una cartella di lavoro aperta da un server SharePoint precedente a SharePoint Server 2016.
-   Risolvere problemi in Excel viene aperto e viene visualizzata una finestra vuota quando vengono attivati uno o più componenti aggiuntivi XLL.
-   Risolvere problemi in Excel si blocca dopo aver utilizzato il pulsante di moduli in una cartella di lavoro già chiuso.
-   Risolvere problemi dove, quando si utilizza l'evento SheetBeforeRightClick, inserimento di una colonna che interseca celle unite non espanda le celle unite.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti di sicurezza
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): Microsoft Outlook vulnerabilità funzionalità Bypass
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): vulnerabilità Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui il collegamento "Ulteriori informazioni" in suggerimenti criteri non è visibile quando si utilizza il tema grigio scuro.
-   Risolvere problemi in Outlook si blocca quando l'utente tenta di impostare un nuovo account e si chiude la finestra senza aver completato la configurazione dell'account.
-   Risolvere problemi dove Segna come già letto e Segna come già letto visualizzate come opzioni per i messaggi di posta in arrivo condiviso per un gruppo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in PowerPoint si blocca quando si apre una presentazione di SharePoint server precedenti a SharePoint Server 2016.

### <a name="word-security-updates"></a>Word: Aggiornamenti di sicurezza
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Word si blocca quando si apre il riquadro attività per un documento aperto da un server SharePoint precedente a SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): Microsoft Office vulnerabilità

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in corso di ripristino Online non è visualizzato all'utente.
-   Risolvere problemi in proprietà del file di Office non vengono visualizzati in Esplora File.
-   Risolvere problemi in Office componente aggiuntivo pulsanti non sono visualizzati nella barra multifunzione quando si verifica un secondo documento aperto.
-   Risolvere problemi di cui non è possibile aprire alcuni moduli VBA con i nomi con caratteri DBCS.



## <a name="version-1708-september-12"></a>Versione 1708: Settembre 12
*Versione 1708 (Build 8431.2079)*

### <a name="access-feature-updates"></a>Accesso: Aggiornamenti alle funzionalità
-   **Proprietà etichetta nome:** Migliorare l'accessibilità associa un'etichetta a un controllo in una maschera.
-   **Modifica un nuovo elemento è più accessibile:** Per modificare un nuovo elemento da una casella combinata o casella di riepilogo, eseguire una rapida combinazione di tasti (Ctrl + A).
-   **Connettore dynamics:** Importare i dati da o collegare dati memorizzati in Microsoft Dynamics. [Ulteriori informazioni](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Forza vendita connettore:** Importare i dati da o collegare dati memorizzati in forza vendita. [Ulteriori informazioni](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti alle funzionalità
-   **Miglioramenti apportati a "Aggiungere colonne da esempi":** Supporta più le trasformazioni di data/ora, matematica e indice di colonna.
-   **Miglioramenti delle prestazioni:** Excel apre cartelle di lavoro complesse con più fogli più veloce, in modo che è possibile vengono frammentati le formule con gli intervalli di grandi dimensioni, filtrare una quantità elevata di righe, o copiare e incollare più rapidamente le operazioni.
-   **Inserimento di immagini online:** Nuova pagina di destinazione per la selezione di immagini e informazioni di attribuzione viene inserito automaticamente con l'immagine.
-   **Connettore archivio lago dati azure:** Gli utenti possono ora importare dati dall'archivio lago dati Azure.
-   **Miglioramenti apportati a "Aggiungi colonna da esempi":** Supporta i suggerimenti, ulteriori operazioni di data/ora e trasformazioni aggiuntive.
-   **Scheda dati**: pulsanti della barra multifunzione della scheda dati sono stati riorganizzati in due nuovi gruppi: Get & Trasforma dati e le query e connessioni.
-   **Condivisione di query**: esportare tutte le definizioni query in un file di connessione del Database (ODC) e quindi condividerlo nelle cartelle di lavoro o con altri utenti.
-   **Caricamento dei dati:** Caricare dati da una query direttamente in tabelle pivot o grafici pivot senza la necessità di salvare i dati nel modello di dati.
-   **Condivisi attività del file:** Fare clic sul pulsante attività nell'angolo superiore destro del file da visualizzare quando un file condiviso in OneDrive for Business o SharePoint è stato condiviso, la modifica, rinominati o ripristinato.
-   **Collegamenti sicuri:** Quando un utente fa clic su un collegamento, Office 365 avanzate Threat Protection (degli strumenti di analisi) controlla se il collegamento per verificare se è dannoso. Se il collegamento viene ritenuto dannoso, l'utente viene reindirizzato a una pagina avviso anziché l'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Avanzata funzionalità di importazione dei dati:** Importare facilmente e la forma dati provenienti da origini diverse. Gestire le query di cartella di lavoro e le connessioni con la connessione di query riquadro laterale e condividere le query con altri utenti mediante i file ODC. [Ulteriori informazioni](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Le modifiche nei file condivisi**: visualizzare che ha apportato modifiche nelle cartelle di lavoro condivise e ripristinare le versioni precedenti. [Ulteriori informazioni](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Selezione con lazo con un pulsante della penna:** Utilizzo supportato pulsanti penna digitali per l'input penna selezione con lazo senza visitando la barra multifunzione.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Excel temporaneamente si blocca quando si espande o comprime una tabella pivot e spostare le intestazioni di tabella pivot fuori dello schermo.
-   Risolvere i problemi a cui le schede vengono ignorate durante la copia e testo da Word, risultando in testo non analizzato in colonne delimitato da tabulazione incollare.
-   Risolvere problemi in Excel si blocca quando si apre il dialogo Pubblica come pagina Web.
-   Risolvere problemi in un aggiornamento dei dati ha esito negativo o Excel si blocca quando si utilizzano i dati da un server SQL Server Analysis Services e le impostazioni locali di Excel e le impostazioni locali del server SQL Server Analysis Services diversi.
-   Risolvere problemi di cui vengono visualizzati errori durante il tentativo di salvare le modifiche apportate ai documenti sincronizzati con il client OneDrive.
-   Risolvere problemi in non apportare modifiche via Internet in un foglio di lavoro quando è presente una tabella pivot con i campi nell'area filtro, ma nessun campo incluso in un punto qualsiasi altro utente.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti alle funzionalità
-   **Miglioramenti accessibilità:** È stata rielaborata per semplificare la lettura e la modifica di testo, tabelle, elenchi e le immagini nella posta elettronica quando si utilizza un software screen reader.
-   **Nuova configurazione di account:** Impostare i nuovi account con una nuova procedura guidata che richiede meno interventi manuali.
-   **Finestra di dialogo Connetti per i collegamenti:** Quando si collega un collegamento utilizzo di File basato sul collegamento nella barra multifunzione, è possibile selezionare se si desidera aggiungere come collegamento o come allegato. Se non si desidera visualizzare ogni volta che questa finestra di dialogo, passare al File \> opzioni \> generali e specificare la modalità di collegamenti da collegare in "Opzioni allegati".
-   **Il supporto per gli allegati in locale:** I file dal Server di SharePoint locale vengono visualizzati backup dei file recenti in messaggio \> Allega File locale OneDrive for Business e team siti di SharePoint vengono visualizzati in Allega File \> passare percorsi Web e file locali possono essere caricati in locale OneDrive per i siti.
-   **Classificazioni aziendali per i gruppi:**  È possibile assegnare un livello di classificazione business definito dall'amministratore tenant, ad esempio riservato, quando si crea o modifica di un gruppo e la classificazione viene visualizzata nell'intestazione di gruppo.
-   **Accesso Guest ai gruppi di Office 365:** Collaborare con utenti esterni all'organizzazione per concedere l'accesso a conversazioni di gruppo, file, gli inviti di calendario e il blocco appunti di gruppo. [Ulteriori informazioni](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Messaggi pronti per interventi:** Gli sviluppatori possono creare messaggi a in modo semplice per gli utenti di eseguire operazioni semplici o rapidi direttamente in Outlook senza dover passare a un sito web esterno o app separato. [Ulteriori informazioni](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti di sicurezza
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook vulnerabilità funzionalità Bypass
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook vulnerabilità
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilità di danneggiamento della memoria di Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui si è non è possibile configurare un account IMAP in Outlook.
-   Risolvere un problema che causa un arresto anomalo intermittente durante l'apertura di Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti alle funzionalità
-   **Inserimento di immagini online:** Nuova pagina di destinazione per la selezione di immagini e informazioni di attribuzione viene inserito automaticamente con l'immagine.
-   **Chiuso didascalie per video:** Aggiungere didascalie a un video per rendere più accessibile. [Ulteriori informazioni](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Commentare una registrazione:** Includere video personale il commento quando si effettua una registrazione di una presentazione. Le registrazioni possono includere le animazioni, inchiostro, audio e video.
-   **Condivisi attività del file:** Fare clic sul pulsante attività nell'angolo superiore destro del file da visualizzare quando un file condiviso in OneDrive for Business o SharePoint è stato condiviso, la modifica, rinominati o ripristinato.
-   **Creazione testo alternativo:** Un servizio basato su cloud genera automaticamente il testo alternativo per le immagini in una presentazione.
-   **Collegamenti sicuri:** Quando un utente fa clic su un collegamento, Office 365 avanzate Threat Protection (degli strumenti di analisi) controlla se il collegamento per verificare se è dannoso. Se il collegamento viene ritenuto dannoso, l'utente viene reindirizzato a una pagina avviso anziché l'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Miglioramenti della finestra di progettazione:** È consigliabile idee di progettazione professionali per elenchi di azione.
-   **Modifiche nei file condivisi:** Visualizzare che ha apportato modifiche nelle presentazioni condivise e ripristinare le versioni precedenti. [Ulteriori informazioni](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti di sicurezza
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): PowerPoint vulnerabilità
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): PowerPoint vulnerabilità

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in caso di caratteri definiti per l'utente finale (EUDCs) collegati ai tipi di carattere da visualizzare.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in apertura di file specifici da Project Online, progetto per arresto anomalo del sistema.
-   Risolvere problemi in inizio effettivo potrebbe essere erroneamente deselezionata quando si imposta il lavoro rimanente.
-   Risolvere problemi dove assegnazione data di inizio effettiva potrebbe visualizzare dati diversi rispetto a quanto indicato dalla risorsa tramite definizione dello stato in Project Web App.
-   Risolvere problemi di cui il lavoro effettivo può essere pianificate di nuovo se viene modificata la data di fine dell'attività.
-   Risolvere problemi quale se si copia e Incolla campi dei costi, i valori incollati potrebbero non corrispondono esattamente i valori copiati a causa di un problema di arrotondamento.
-   Risolvere problemi cui dati rapportati alla scala cronologica per le risorse preventivo non vengono copiati quando si salva da una linea di base in un altro.
-   Risolvere problemi di cui il campo stato non esegue sempre il calcolo correttamente per attività di riepilogo.
-   Risolvere problemi di cui il lavoro effettivo erroneamente Ottiene trasferito a una risorsa dell'organizzazione quando sostituisce una risorsa locale e lavoro protetto è abilitata.
-   Risolvere problemi in Project si blocca se si dispone di una tabella nella prima colonna è nome attività, la colonna è bloccata e si fa clic su un'attività.
-   Risolvere problemi di cui è possibile assegnare la stessa risorsa più volte alla stessa operazione tramite la visualizzazione Gestione attività.
-   Risolvere problemi di cui i valori dei campi personalizzati numeri potrebbero andare persi quando apertura dei file XML.
-   Risolvere problemi dove il rientro di attività di livello superiore non sincronizza correttamente dal progetto per un elenco di attività di SharePoint.
-   Risolvere problemi dove se si importa attività, risorsa o informazioni sulle assegnazioni da una cartella di lavoro di Excel, i valori del campo lavoro verrà ignorati.
-   Risolvere problemi dove rapportato alla linea di base non corrisponda ai valori iniziali quando si salva un progetto per il formato di file XML.
-   Risolvere problemi cui il client di Project non è possibile aprire un progetto dopo che è ritenuto che il progetto è estratto quando non è in realtà.
-   Risolvere i problemi in modo che l'apertura dei file di progetto da un file server con latenza elevata open più velocemente.

### <a name="skype-for-business-security-updates"></a>Skype per le aziende: aggiornamenti di sicurezza
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): GDI+ vulnerabilità di Windows
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): grafica componente vulnerabilità
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): esecuzione di codice remoto componente Microsoft grafica

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Finestra di dialogo che spiega perché un utente è in grado di partecipare a una riunione quando bloccare alcune porte o IP non whitelisted Aggiungi.
-   Risolvere problemi cui messaggi non letti di chat permanenti vengono contrassegnati come letti quando si fa clic su schede di conversazione di messaggistica immediata.
-   Risolvere problemi cui messaggi immediati in arrivo toasts esperienza un ritardo secondo diversi.
-   Risolvere problemi in un contatto di Active Directory viene visualizzato come un numero di telefono anziché il nome di contatto durante la sincronizzazione con Exchange è disabilitata.
-   Risolvere problemi di cui gli utenti di accesso anonimo non possono partecipare quando viene disattivata la federazione e accesso anonimo non viene esplicitamente bloccato dall'organizzatore della riunione.
-   Risolvere problemi in modo non corretto viene visualizzato il numero degli invitati a riunioni che superano il limite di organizzatore della riunione.
-   Risolvere problemi in numero di telefono non viene visualizzato nel popup su PSTN le chiamate in ingresso.
-   Risolvere problemi dove, quando si utilizza il tasto CANC durante la ridenominazione di un gruppo dell'elenco contatti, viene eliminato l'intero gruppo.
-   Risolvere problemi in cui la notifica di condivisione in una conversazione di messaggistica immediata viene chiuso prima si interrompe la condivisione.
-   Risolvere problemi in cui la schermata di accesso è vuota per alcune lingue localizzate.
-   Risolvere problemi di cui sono incomprensibile caratteri non inglesi in chat e la cronologia della chat.
-   Visualizza il numero di telefono del chiamante per una chiamata in arrivo gestita mediante l'operatore automatico dell'organizzazione, se non si conosce il nome dell'utente.
-   Aggiungere un impostazioni in-band consentendo restrizione della "Chiunque (nessuna restrizione)" come opzione per "queste persone non sono necessario attendere nella sala d'attesa".
-   Aggiungere possibilità di attivare o disattivare i self-video per P2P video chiamate in VDIv2.
-   Risolvere problemi di cui visualizzano numeri duplicati per contatti nel menu a discesa di chiamata.
-   Risolvere i problemi che rimuove i delegati per gli utenti che passano tra Skype per le aziende e Skype per Business Basic.
-   Risolvere problemi dove invisibile non è visibile quando si utilizza abilitare invisibile e i criteri client URL stato personalizzato.
-   Ingrandire il pulsante di partecipazione alle riunioni per correggere il troncamento di alcune lingue localizzate.
-   Aumentare la diffusione dei messaggi con priorità alta nella chat.
-   Aggiungere Office e Skype per tipi di estensioni di file Business blocklists trasferimento di file consentiti.
-   Correzioni localizzazione negli inviti alle riunioni di Outlook per riunioni testo piè di pagina impostare non in lingua inglese.
-   Risolvere problemi di cui è possono passare nomi mittente nelle conversazioni di più utenti.
-   Risolvere problemi di cui la finestra di conversazione vuota non viene visualizzato fino a una riunione è stato aggiunto correttamente.
-   Risolvere problemi di cui le informazioni sui campi reparto in una scheda contatto è vuote nei risultati della ricerca se il campo titolo è vuoto.
-   Correggere gli errori di accesso per gli utenti migrati da locale a online per le regole del firewall.
-   Aggiungere una nuova chiave del Registro di sistema DWORD per risolvere un problema di cui, quando un utente accede a client in una rete esterna esegue LyncAutoD, il client consente di ripristinare la chiave del Registro di sistema OAuthUsed false. Per risolvere il problema, impostare il valore su 1 per EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket in HKEY\_corrente\_utente\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti alle funzionalità
-   **Effettuare diagrammi dei dati di Excel:** Creare automaticamente un diagramma di flusso di base o un diagramma di flusso interfunzionali dai dati di Excel tramite nuovi modelli di dati visualizzatore. [Ulteriori informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Collegamenti sicuri:** Quando un utente fa clic su un collegamento, Office 365 avanzate Threat Protection (degli strumenti di analisi) controlla se il collegamento per verificare se è dannoso. Se il collegamento viene ritenuto dannoso, l'utente viene reindirizzato a una pagina avviso anziché l'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in componenti aggiuntivi COM non si ricevono gli eventi di documenti aperti quando si apre un file di Visio da un doppio clic su un file icona o nome del file.

### <a name="word-feature-updates"></a>Word: Aggiornamenti alle funzionalità
-   **Inserimento di immagini online:** Nuova pagina di destinazione per la selezione di immagini e informazioni di attribuzione viene inserito automaticamente con l'immagine.
-   **Creazione testo alternativo:** Un servizio basato su cloud genera automaticamente il testo alternativo (testo alternativo) per le immagini in un documento.
-   **Condivisi attività del file:** Fare clic sul pulsante attività nell'angolo superiore destro del file da visualizzare quando un file condiviso in OneDrive for Business o SharePoint è stato condiviso, la modifica, rinominati o ripristinato.
-   **Collegamenti sicuri:** Quando un utente fa clic su un collegamento, Office 365 avanzate Threat Protection (degli strumenti di analisi) controlla se il collegamento per verificare se è dannoso. Se il collegamento viene ritenuto dannoso, l'utente viene reindirizzato a una pagina avviso anziché l'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Modifiche nei file condivisi:** Visualizzare che ha apportato modifiche nella cartella Documenti condivisi e ripristinare le versioni precedenti. [Ulteriori informazioni](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Word viene chiuso in modo imprevisto durante il caricamento del componente aggiuntivo Grammarly.
-   Risolvere problemi di cui, in determinate condizioni, Word si blocca durante il tentativo di recupero dei file basati su cloud.
-   Risolvere problemi di cui non possono essere ruotate forme all'interno dell'area di disegno.
-   Risolvere problemi di cui, durante la digitazione in coreano, consonanti e vocali sono erroneamente separate.
-   Salvataggio di un documento come PDF il documento viene salvato come versione 1.7 PDF.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office vulnerabilità
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti Non correlati alla sicurezza
-   Risolvere un problema che impedisce il che cos'è nuova finestra di dialogo venga visualizzata.
-   Risolvere problemi dove facendo clic sulla scheda disegnare fa sì che l'applicazione in modo anomalo per alcuni utenti.
-   Risolvere problemi di cui si posiziona su un controllo comune con una descrizione comandi su di esso fa sì che l'applicazione in modo anomalo.
-   Risolvere problemi di cui viene visualizzato un messaggio di errore delle licenze quando si utilizzano i controlli comuni.
-   Risolvere un problema con la modalità di firma alcuni file di programma, causando programmi antivirus contrassegnare tali file nonché problemi di protezione o accesso ai dati in Windows Information Protection (WIP).
-   Aggiungere support.to consentire agli utenti che utilizzano versioni a 64 bit di Office per aprire i file di macro contenenti controlli Mscomctl.
-   Migliorare l'accessibilità dei controlli utilizzati in Mscomctl.
-   Risolvere problemi dove comandi mancano alcuni della barra multifunzione o le finestre di dialogo Personalizzazione barra di accesso rapido.



## <a name="version-1705-august-8"></a>Versione 1705: Agosto 8
*Versione 1705 (Build 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere un problema di trascinare la barra di scorrimento per spostarsi in un elenco di messaggi.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti Non correlati alla sicurezza
-   Risolvere un problema con la modalità di firma alcuni file di programma, causando programmi antivirus contrassegnare tali file nonché problemi di protezione o accesso ai dati in Windows Information Protection (WIP).
-   Risolvere un problema che impedisce il che cos'è nuova finestra di dialogo venga visualizzata.



## <a name="version-1705-july-27"></a>Versione 1705: Luglio 27
*Versione 1705 (Build 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui vengono visualizzati errori durante il tentativo di salvare le modifiche apportate ai documenti sincronizzati con il client OneDrive.
-   Risolvere problemi in Excel si blocca quando si aggiungono dati del foglio di lavoro a un modello di dati e i temi a contrasto elevato sono impostato su nero.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti di sicurezza
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): Microsoft Office Outlook vulnerabilità funzionalità Bypass
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): Microsoft Office Outlook vulnerabilità
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilità di danneggiamento della memoria di Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in cui si aggiunge una forma dopo un altro utente modifica il layout causa un errore di unione.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui, durante la digitazione in coreano, consonanti e vocali sono erroneamente separate.
-   Risolvere problemi di cui l'indirizzo di consegna sulle buste viene stampata troppo vicino al bordo sinistro.



## <a name="version-1705-july-13"></a>Versione 1705: 13 luglio
*Versione 1705 (Build 8201.2136)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Excel si blocca per le cartelle di lavoro che contengono collegamenti esterni.
-   Risolvere problemi dove incollano le celle da Excel in Word vengono illustrati gli zero iniziali nelle celle, anche se non è selezionata l'impostazione "Mostra a zero nelle celle con valore uguale a zero".

### <a name="project-non-security-updates"></a>Project: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui i valori selezionati per una tabella/grafico non sono visibili nel riquadro grafico/tabella.

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Risolvere i problemi in una finestra di conversazione non viene visualizzata in background quando si partecipa a una riunione e viene visualizzata la finestra di dialogo partecipa a dispositivi audio all'utente.
-   Risolvere problemi di cui il collegamento della riunione da Outlook non sempre passa URI interno in modo corretto.
-   Ampliare sul pulsante di partecipazione alle riunioni per correggere il troncamento di alcune lingue localizzate.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in tabelle non essere visualizzati correttamente dopo determinate azioni.
-   Risolvere problemi dove di citazioni più modifiche tempo viene visualizzato come una singola azione di annullamento anziché le singole azioni consecutive.
-   Risolvere problemi di cui l'annullamento è disabilitato dopo determinate azioni.
-   Risolvere i problemi per impedire la perdita di dati possibili dopo alcune annullare le azioni.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): Microsoft Office vulnerabilità

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti Non correlati alla sicurezza
-   Risolvere un problema che causa l'aggiornamento automatico di Office 2013 a Office 2016 errore quando si utilizza System Center Configuration Manager.
-   Risolvere problemi di cui non caricano componenti aggiuntivi legacy distribuiti dall'archivio tramite il catalogo aziendale.



## <a name="version-1705-june-13"></a>Versione 1705: 13 giugno
*Versione 1705 (Build 8201.2102)*

### <a name="access-feature-updates"></a>Accesso: Aggiornamenti alle funzionalità
-   **Che cos'è una nuova finestra di dialogo:** Finestra di dialogo che vengono illustrate le nuove funzionalità di accesso viene visualizzato quando si apre Access dopo l'accesso è stato aggiornato con nuove funzionalità. La finestra di dialogo è disponibile anche tramite File \> Account \> What's New.
-   **Il supporto di numero elevato (bigint):** Utilizzare il tipo di dati di numerosi nelle tabelle di Access per calcolare un numero elevato e per collegare o importare dal database esterni che utilizzano un tipo di dati equivalenti, ad esempio bigint in SQL Server. [Ulteriori informazioni](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti alle funzionalità
-   **Supporto Windows Information Protection (WIP):**   Excel è ora un'app enlightenment e distinguere tra i dati aziendali e personali, in modo corretto nel determinare quali per la protezione, in base ai criteri configurati.  [Ulteriori informazioni](https://aka.ms/wiptechnet)
-   **Ottenere & trasformazione analisi utilizzo software:** Nell'Editor di Query, creare una nuova colonna fornendo valori di esempio. Durante la digitazione, Excel rileva le trasformazioni obbligatorie e viene visualizzata un'anteprima della nuova colonna.
-   **Inserire collegamenti recenti:** Semplice basato sul collegamento di collegamenti ipertestuali a file basati su cloud recenti o siti Web e creare nomi visualizzato significativo per gli utenti che utilizzano screen reader. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personalizzare il layout di tabella pivot predefinito:** Impostare una tabella pivot nel modo desiderato e iniziare con tale layout ogni volta che si crea una nuova tabella pivot. [Ulteriori informazioni](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Ottenere e trasformare i miglioramenti apportati:** Gli utenti possono creare nuove colonne dall'esempio e divisa righe colonne della tabella. Specificare i parametri per HANA SAP e raggruppamento dei dati è ora più semplice.
-   **Distribuzione centralizzata dei componenti aggiuntivi**: gli amministratori possono distribuire e aggiornare i componenti aggiuntivi a utenti o gruppi dall'interfaccia di amministrazione di Office 365. [Ulteriori informazioni](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personalizzazione della barra di accesso rapido:** Le icone pedice o apice è possibile aggiungere alla barra di accesso rapido.
-   **Ottenere e trasformare i miglioramenti apportati:** Rilevamento automatico del carattere delimitatore quando colonne divisione utilizzando l'Editor di Query, selezionare il file di esempio da utilizzare con file binari di combinare e specificare l'insieme di pacchetto a cui connettersi quando si utilizza il connettore DB2.
-   **Carattere Dubai:** Famiglia di caratteri che supporta le lingue dell'Europa occidentale e su come le lingue principale che utilizzano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione sfondo:** Rimuovere uno sfondo immagine con un strumento disegno a mano libera.
-   **Ottenere e trasformare i miglioramenti apportati:** Utilizzare "Selezionare tabelle correlate" nella finestra di dialogo Selezione con i connettori OLEDB e ODCB, combinare più file direttamente dalla finestra di dialogo Anteprima dati cartella e utilizzare una nuova opzione di menu di scelta nella finestra Editor di Query per inserire i nuovi passaggi nelle query esistente.
-   **Utilizzare una penna per selezionare e modificare gli oggetti:** Punti di controllo di oggetti con una penna digitale per ridimensionare, ruotare, spostare e altro ancora.
-   **Mappare grafico:** Confrontare i valori e visualizzare le categorie in aree geografiche diverse. [Ulteriori informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Immagini SVG:** Inserire e modificare la grafica vettoriale scalabile (SVG) nelle cartelle di lavoro. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**  Utilizzare le icone da una raccolta di file grafici (SVG) scalabili vettoriale standard all'inserimento \> illustrazioni \> icone. [Ulteriori informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salva in cartelle recenti:** Salvare una cartella di lavoro in una cartella utilizzata di recente tramite la scheda recente quando si passa al File \> Salva con nome.
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, l'Assistente vocale e altre tecnologie per leggere e modificare le cartelle di lavoro. [Ulteriori informazioni](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   Bollettino Microsoft [MS17 014](https://technet.microsoft.com/library/security/ms17-014): aggiornamento di sicurezza per Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Excel non viene impostata la password di protezione foglio quando applicate a livello di programmazione per le cartelle di lavoro creati in Excel 2010 o versioni precedenti.
-   Risolvere problemi in centro e stampa unione non funziona nei fogli di lavoro raggruppate.
-   Risolvere problemi di cui sono presenti nuove funzioni che sono state introdotte dopo il rilascio di Office 2016 -, ad esempio, TEXTJOIN, concatena, IFS, MAXIFS e MINIFS.
-   Risolvere problemi in Excel si blocca quando l'utente tenta di applicare le autorizzazioni a livello di cella.
-   Risolvere i problemi a cui il salvataggio di un file di grandi dimensioni a OneDrive for Business fa sì che il file di blocco e fino a quando l'utente viene chiuso e vengono riaperte Excel non è possibile modificare il file.
-   Risolvere problemi in una nuova verrà visualizzata la finestra visualizzata in grigio quando si apre una cartella di lavoro. xls.
-   Risolvere problemi in Excel potrebbe bloccarsi quando si inserisce i collegamenti ipertestuali.
-   Risolvere problemi in Excel potrebbe avere esito negativo durante l'aggiunta di mapping XML.
-   Risolvere problemi di cui il pulsante di comando per un componente aggiuntivo non funziona dopo che il componente aggiuntivo viene aggiornato o dopo avere rimosso e il download del componente aggiuntivo da Office store.
-   Risolvere problemi in Excel potrebbe bloccarsi durante la manipolazione fogli DLL tramite VBA.
-   Risolvere problemi in Excel si blocca quando si seleziona una casella combinata di controllo di modulo in un foglio grafico.

### <a name="onenote-feature-updates"></a>OneNote: Aggiornamenti delle funzionalità
-   **Supporto Windows Information Protection (WIP):** OneNote è un'app enlightenment e distinguere tra i dati aziendali e personali, in modo corretto nel determinare quali per la protezione, in base ai criteri configurati. [Ulteriori informazioni](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in area di OneNote nasconde il contenuto o gli aggiornamenti dopo molti paragrafi nella visualizzazione.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti alle funzionalità
-   **Supporto Windows Information Protection (WIP):**   Outlook è ora un'app enlightenment e distinguere tra i dati aziendali e personali, in modo corretto nel determinare quali per la protezione, in base ai criteri configurati.  [Ulteriori informazioni](https://aka.ms/wiptechnet)
-   **Inserire collegamenti recenti:** Collegare i collegamenti ipertestuali a file basati su cloud recenti o siti Web e creare nomi visualizzato significativo per gli utenti che utilizzano screen reader. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Carattere Dubai:** Famiglia di caratteri che supporta le lingue dell'Europa occidentale e su come le lingue principale che utilizzano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione sfondo:** Rimuovere uno sfondo immagine con un strumento disegno a mano libera.
-   **Verificare l'accesso ai file condivisi:** Outlook indica all'utente anticipo se destinatari potrebbero non essere in grado di accedere a un file allegato OneDrive o SharePoint e vengono suggerite alcune procedure per risolvere il problema.
-   **Impostare le autorizzazioni per gli allegati:** Per gli allegati OneDrive o SharePoint, l'utente può impostare se destinatari nell'organizzazione o esternamente, leggere o modificare le autorizzazioni per l'allegato.
-   **Taskpane aggiungibili:** Lasciare aperto il riquadro attività componente aggiuntivo durante il passaggio tra i messaggi in una cassetta postale. [Ulteriori informazioni](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Immagini SVG:** Inserire e modificare la grafica vettoriale scalabile (SVG) in messaggi di posta elettronica. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**  Utilizzare le icone da una raccolta di file grafici (SVG) scalabili vettoriale standard all'inserimento \> illustrazioni \> icone.  [Ulteriori informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti di sicurezza
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook vulnerabilità
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilità di Microsoft Office Security funzionalità Bypass
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): vulnerabilità di Microsoft Office Security funzionalità Bypass

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui il riquadro di spostamento di Outlook smette di rendering quando il computer è disponibile poca memoria.
-   Larghezza allegato adattarsi visivamente le informazioni di autorizzazione e nome file.
-   Risolvere problemi in cui l'utente non può cercare i file PST.
-   Risolvere problemi in cui l'utente visualizza una nuova "Microsoft Exchange" archiviare tipo nella finestra di dialogo "Nuovo File di dati Outlook" e se si seleziona il nuovo tipo di dati, il profilo dell'utente di diventare inutilizzabile.
-   Risolvere problemi in un'immagine in un messaggio è oscurata quando inviato da un computer tramite DPI elevata.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti alle funzionalità
-   **Supporto Windows Information Protection (WIP):**   PowerPoint è ora un'app enlightenment e distinguere tra i dati aziendali e personali, in modo corretto nel determinare quali per la protezione, in base ai criteri configurati.  [Ulteriori informazioni](https://aka.ms/wiptechnet)
-   **Inserire collegamenti recenti:** Collegare i collegamenti ipertestuali a file basati su cloud recenti o siti Web e creare nomi visualizzato significativo per gli utenti che utilizzano screen reader. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Distribuzione centralizzata dei componenti aggiuntivi**: gli amministratori possono distribuire e aggiornare i componenti aggiuntivi a utenti o gruppi dall'interfaccia di amministrazione di Office 365. [Ulteriori informazioni](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Carattere Dubai:** Famiglia di caratteri che supporta le lingue dell'Europa occidentale e su come le lingue principale che utilizzano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione sfondo:** Rimuovere uno sfondo immagine con un strumento disegno a mano libera.
-   **Immagini SVG:** Inserire e modificare la grafica vettoriale scalabile (SVG) nelle presentazioni. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**  Utilizzare le icone da una raccolta di file grafici (SVG) scalabili vettoriale standard all'inserimento \> illustrazioni \> icone. [Ulteriori informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Digitando in tempo reale durante la creazione condivisa:** Vedere dove altre persone utilizza la presentazione e visualizzare le modifiche durante la digitazione. [Ulteriori informazioni](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Salva in cartelle recenti:** Salvare una presentazione in una cartella utilizzata di recente tramite la scheda recente quando si passa al File \> Salva con nome.
-   **Creare forme input penna precisa:** Trascinare il segmento gomma per rimuovere in eccesso bit dell'input penna, sopra la riga più vicina.
-   **Selezionare e modificare gli oggetti a penna:** Utilizzare una penna digitale per spostare, ridimensionare o oggetti utilizzando i punti di manipolazione di rotazione o utilizzare i pulsanti penna supportati per l'input penna selezione con lazo.
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, l'Assistente vocale e altre tecnologie per leggere e modificare le presentazioni. [Ulteriori informazioni](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in PowerPoint si blocca quando l'utente è nel riquadro struttura idee se il file mfplat.dll non è installato nel computer.
-   Risolvere problemi di cui il pulsante di comando per un componente aggiuntivo non funziona dopo che il componente aggiuntivo viene aggiornato o dopo avere rimosso e il download del componente aggiuntivo da Office store.

### <a name="project-feature-updates"></a>Project: Aggiornamenti della funzionalità
-   **Veloce elenco a discesa per l'impostazione predecessori:** Utilizzare il diagramma di Gantt elenco a discesa per scegliere i predecessori o successori che si desidera collegare a un'attività.
-   **Riepilogo Nome attività:**  Campo delle attività di sola lettura che visualizza il nome dell'attività di riepilogo dell'attività.  

### <a name="project-non-security-updates"></a>Project: Aggiornamenti Non correlati alla sicurezza
-   Correggere la finestra di dialogo Crea sito di Project per visualizzare il percorso corretto per il sito dopo che in Project Online ogni modello di progetto dell'organizzazione (accetta) avrà il proprio URL per i siti di progetto.
-   Risolvere i problemi a cui l'evento BeforeClose VBA viene generato prima del salvataggio prompt e non si dispone di una modalità a livello di programmazione per determinare la risposta dell'utente alla Salva prompt dei comandi.
-   Risolvere problemi dove fisico % completamento non rollup correttamente per attività che iniziano dopo la data stato del progetto.
-   Risolvere problemi quando una risorsa costo e lavoro viene assegnata alla stessa attività, potrebbero non essere in grado di modificare i responsabili dello stato dell'attività.
-   Risolvere problemi dove per alcuni progetti, l'intero progetto livellamento possono lasciare è in un ciclo infinito.
-   Correzione un problema cui attività inizio e fine date non eseguire la sincronizzazione a un elenco di attività di SharePoint correttamente se si dispone di alcune impostazioni internazionali spagnolo.
-   Risolvere problemi dove se si avvia il processo di approvazione stato dal client di Project, non può mai fine, lasciare il progetto inutilizzabile.
-   Risolvere problemi in anteprima di stampa non i nomi delle attività layout correttamente se sono presenti parole cinese e viceversa.
-   Risolvere problemi cui copia sequenza temporale in PowerPoint come le singole forme non funziona.
-   Risolvere problemi dove la finestra di dialogo "Collegamenti tra progetti" in modo imprevisto consente di visualizzare il valore "File non trovato".
-   Correzione dei risultati di un problema che viene visualizzato non coerente durante l'assegnazione di risorse con unità Max pari a 0.
-   Risolvere problemi in una data di inizio attività reimpostata su più presto possibile quando si elimina data di inizio un'assegnazione, ignorando le operazioni come predecessori, che può avere gli effetti divise iniziali per le assegnazioni.
-   Risolvere i problemi a cui se si apre un file da SharePoint tramite il menu di recente, il progetto viene automaticamente estratto per l'utente anche se l'impostazione "Obbligatoria dei documenti per l'estrazione prima che possono essere modificati"? è abilitata.
-   Risolvere problemi dove se si passa direttamente all'applicazione di profili di Project, Project si blocca.
-   Risolvere problemi dove le attività pianificate manualmente non vengono aggiornate correttamente per gli utenti di eseguire l'aggiornamento da Project 2013.
-   Risolvere problemi dove quando si apre un progetto di SharePoint, elenco attività, progetti possono bloccarsi come progetto consente di avviare il processo di sincronizzazione di attività.
-   Risolvere problemi in Project a volte si blocca quando si passa a Crea Team.
-   Risolvere problemi cui informazioni di base vengono perse durante il salvataggio di un progetto.
-   Risolvere problemi dove stampe sono difficili da leggere per piani di progetto di grandi dimensioni.
-   Risolvere problemi in progetti modificati in Project Web App non visualizzare i valori corretti per campi formula.
-   Risolvere problemi cui informazioni per campi personalizzati delle risorse dell'organizzazione non sono state salvate correttamente per un piano di progetto.
-   Risolvere problemi in cui l'aggiornamento % dell'attività completamento lavoro informazioni Aggiorna informazioni Complete % dell'attività.
-   Risolvere problemi in cui la proprietà project cambia quando si salva il progetto.
-   Risolvere problemi in CPI viene calcolato in modo non corretto per un'attività di riepilogo.
-   Risolvere problemi cui copiare e incollare attività esegue i dati di base e i dati vengono salvati, anche se l'utente non è autorizzato a salvare i dati di previsione protetta.
-   Risolvere problemi dove importazione dei dati da Excel restituisce informazioni relative alle date non corretto per le attività e assegnazioni.
-   Risolvere problemi di cui, dopo l'apertura di un report, Project si blocca quando si chiude.
-   Risolvere problemi in Project smette di funzionare durante il salvataggio di un progetto in un elenco personalizzato contiene le impostazioni di convalida.
-   Risolvere problemi in cui immettere il "\>" nella colonna della condizione nella finestra di dialogo Definizione filtro non è corretto interpretato come significato "è maggiore di".
-   Risolvere i problemi con la visualizzazione delle linee di avanzamento in relazione "Previsione."
-   Risolvere problemi di cui non viene visualizzato l'elenco a discesa di nomi di campo durante la personalizzazione dei filtri.
-   Risolvere problemi in stile della barra anteprime non vengono visualizzati nella finestra di dialogo Stile barre.

### <a name="publisher-non-security-updates"></a>Publisher: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Publisher non visualizzare le immagini CMYK TIF.

### <a name="skype-for-business-feature-updates"></a>Skype per le aziende: gli aggiornamenti delle funzionalità
-   **Inserisci collegamento:** Aggiungere un collegamento alla messaggistica Istantanea e le chat di gruppo e fornire il testo descrittivo per il collegamento anziché l'URL completo.
-   **Notifica di condivisione dello schermo:** Quando si condivide una schermata di una conversazione di messaggistica immediata o durante la condivisione dello schermo continuerà fino a quando si abbandona una riunione, nella finestra Conversazione viene visualizzata una notifica. La notifica per ricordare sono ancora condivisione dello schermo in modo semplice interrompere la condivisione con il pulsante "Interrompi condivisione".
-   **Supporto Windows Information Protection (WIP):** Skype per le aziende è ora supportato come un'app sola lavoro WIP.  Aggiungendo Skype all'elenco dei domini consentiti App, indica a Windows non gestisce i dati personali.  Windows proteggere i dati per conto di Skype per le aziende.  [Ulteriori informazioni](https://aka.ms/wiptechnet)
-   **Opzione reimpostazione password:** Quando un utente non riesce ad accedere almeno una volta, viene visualizzato un collegamento di pulsante Reimposta nella finestra di accesso.

### <a name="skype-for-business-security-updates"></a>Skype per le aziende: aggiornamenti di sicurezza
-   Bollettino Microsoft [MS17 013](https://technet.microsoft.com/library/security/ms17-013): aggiornamento di sicurezza per il componente Microsoft grafica (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office vulnerabilità
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): Windows Uniscribe Remote vulnerabilità
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): Skype per Business vulnerabilità

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Modificare messaggio per le chiamate di tentativi per gli utenti con audio disabilitata dal criterio da "Impossibile completare la chiamata" a "Impossibile chiamata dal momento che un amministratore IT ha limitato audio. Provare a utilizzare invece la messaggistica immediata o posta elettronica e chiederà di contattare il proprio amministratore IT".
-   Aggiungere che un collegamento ipertestuale "Dimenticato il PIN di accesso esterno" in riunione invita degli utenti di servizi di conferenza PSTN abilitati per Skype Business online.
-   Abilitare partecipazione alle riunioni team da Skype Business online.
-   Modificare il volume di sessione dell'altoparlante predefinito da 40% al 75%.
-   Consentire il ridimensionamento dell'elenco della scheda in una larghezza minima inferiore.
-   Aggiornare i tasti di scelta rapida in modo da corrispondere ordine delle schede.
-   Correggere errata direzione del testo ebraico durante l'invio di un dispositivo mobile.
-   Risolvere i problemi con le informazioni udibile da un software screen reader per la funzionalità presente Desktop/Concedi controllo.
-   Mostra aperto room oltre visitato room negli elenchi delle chat Room selezionare.
-   Aggiungere possibilità di disattivare la funzionalità VoIP app personalizzata di controllo delle chiamate remote è abilitato.
-   Modificare slogan messaggistica Istantanea non in linea di "Prova Skype per app per dispositivi mobili aziendali".
-   Risolvere un problema che causa una finestra di conversazione per una conversazione automaticamente accettata aprire anziché come finestra normale, ridotta a icona e in modo imprevisto impostare lo stato attivo dal altre finestre.
-   Risolvere i problemi a utilizzare un software screen reader della finestra di dialogo Opzioni riunione Skype.
-   Risolvere problemi di cui non è riportato il primo messaggio in un invito nel messaggio di posta elettronica conversazioni non effettuate.
-   Risolvere problemi in cui vengono visualizzati i numeri di accesso esterno duplicati durante la creazione di un invito alla riunione da Outlook utilizzando il pulsante Nuova riunione Skype.
-   Risolvere problemi di cui, quando viene visualizzata una barra di scorrimento, tutte le conversazioni in una cronologia di messaggistica immediata non sono selezionate quando si utilizza Ctrl + A per selezionare tutti.
-   Risolvere problemi di cui il testo di output potrebbe non essere dello stesso formato esatto quando si utilizza il cmdlet Export-CsArchivingData.
-   Risolvere problemi di cui è in grado di vedere video dei partecipanti remoti utilizzando riunione immediata con 3 o più partecipanti, l'organizzatore della riunione.
-   Risolvere problemi in cui la prima riga dell'elenco dei partecipanti alla riunione è vuota, quando l'utente fa clic sul nome di un altro utente nell'elenco partecipanti.
-   Risolvere problemi di cui gli utenti sono in grado di effettuare l'accesso quando si passa dalla rete interna ed esterne aziendale.
-   Risolvere problemi di cui l'area di chat non viene chiuso quando escalation dalla messaggistica immediata a Audio del trasferimento con consultazione.
-   Risolvere problemi in nomi vengono troncati nelle notifiche avvisi quando lo squillo simultaneo dei due endpoint utilizzato.
-   Risolvere problemi dove il nome del file viene troncato nel file le notifiche di condivisione.
-   Aggiungere le descrizioni comandi per Back ai pulsanti delle chiamate e il trasferimento.
-   Verificare il tempo di attesa nella finestra di trasferimento con consultazione disponibile agli assistenti, ad esempio l'Assistente vocale.
-   Aggiungere la possibilità di scegliere di messaggistica immediata oppure le chiamate come le preferenze predefinite per il trasferimento con consultazione.
-   Aggiungere la capacità, effettuare un trasferimento con consultazione, per fare clic sul pulsante "Trasferimento" per visualizzare un elenco di numeri di telefono del contatto.
-   Migliorare un messaggio di errore generale per renderlo clear il problema è che l'utente dispone di una licenza non valida o non è stata assegnata una licenza.
-   Risolvere problemi di cui non tutti i contatti vengono visualizzati nel titolo della finestra Conversazione quando un utente avvia una conversazione con un contatto e quindi viene aggiunto un altro contatto.
-   Risolvere problemi in Assistente vocale non legge la riga 2 ° delle notifiche.
-   Risolvere problemi in cui le chiamate vengono trasferite a VOIP anziché il numero consultato.
-   Risolvere problemi di cui l'Assistente vocale annuncia informazioni errate quando l'utente sta spostando nella finestra di contenuto.
-   Risolvere i problemi a cui non vengono visualizzati i nomi creatore e il modificatore quando si posiziona un'annotazione su una lavagna

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti alle funzionalità
-   **Individuare gli stencil di terze parti:** Cercare gli stencil di terze parti forniti da provider di contenuto selezionato.
-   **Diapositive frammenti:** Richiedere frammenti di un disegno di Visio ed esportarli come diapositive di PowerPoint. [Ulteriori informazioni](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: Aggiornamenti alle funzionalità
-   **Supporto Windows Information Protection (WIP):**   Word è ora un'app enlightenment e distinguere tra i dati aziendali e personali, in modo corretto nel determinare quali per la protezione, in base ai criteri configurati.  [Ulteriori informazioni](https://aka.ms/wiptechnet)
-   **Inserire collegamenti recenti:** Collegare i collegamenti ipertestuali a file basati su cloud recenti o siti Web e creare nomi visualizzato significativo per gli utenti che utilizzano screen reader. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Distribuzione centralizzata dei componenti aggiuntivi**: gli amministratori possono distribuire e aggiornare i componenti aggiuntivi a utenti o gruppi dall'interfaccia di amministrazione di Office 365.  [Ulteriori informazioni](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Carattere Dubai:** Famiglia di caratteri che supporta le lingue dell'Europa occidentale e su come le lingue principale che utilizzano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione sfondo:** Rimuovere uno sfondo immagine con un strumento disegno a mano libera.
-   **Lato a altro:** Spostarsi tra pagine nella visualizzazione Layout di stampa scorrendo li a Affianca come uno stack di carta. [Ulteriori informazioni](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Utilizzare una penna per selezionare e modificare gli oggetti:** Punti di controllo di oggetti con una penna digitale per ridimensionare, ruotare, spostare e altro ancora.
-   **Immagini SVG:** Inserire e modificare la grafica vettoriale scalabile (SVG) nei documenti. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**  Utilizzare le icone da una raccolta di file grafici (SVG) scalabili vettoriale standard all'inserimento \> illustrazioni \> icone.  [Ulteriori informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salva in cartelle recenti:** Salvare un documento in una cartella utilizzata di recente tramite la scheda recente quando si passa al File \> Salva con nome.
-   **Migliorata lettura con gli strumenti di apprendimento:** Nuovi comandi in boost modalità lettura leggere le competenze per regolare la spaziatura di testo, che mostra le interruzioni di pagina sillabe e l'evidenziazione ogni parola del documento è di lettura ad alta voce. [Ulteriori informazioni](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **Forma riconoscimento:** Trasformare automaticamente i disegni in forme mediante il disegnare \> convertire alle forme. [Ulteriori informazioni](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: Aggiornamenti di sicurezza
-   Bollettino Microsoft [MS17 014](https://technet.microsoft.com/library/security/ms17-014): aggiornamento di sicurezza per Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office vulnerabilità
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): Windows PDF vulnerabilità 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): Microsoft Office vulnerabilità  

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in cui l'utente non può cercare i file PST.
-   Risolvere problemi in cui l'utente visualizza una nuova "Microsoft Exchange" archiviare tipo nella finestra di dialogo "Nuovo File di dati Outlook" e se si seleziona il nuovo tipo di dati, il profilo dell'utente di diventare inutilizzabile.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): API di Microsoft Office/WordPad codice remoto esecuzione vulnerabilità w/Windows
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office vulnerabilità
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office vulnerabilità
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office vulnerabilità
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): Microsoft Office vulnerabilità
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): Microsoft Office vulnerabilità



## <a name="version-1701-may-9"></a>Versione 1701: Maggio 9
*Versione 1701 (Build 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere i problemi che consente agli utenti di visualizzare in modo intermittente la selezione dei messaggi nell'elenco dei messaggi passare in modo imprevisto durante l'eliminazione di messaggi.
-   Risolvere un problema che causa arresti anomali intermittenti.
-   Aggiungere HKEY\_corrente\_utente\\Software\\Microsoft\\Office\\16.0\\Outlook\\opzioni\\generali\\DisableSupportBackstage chiave del Registro di sistema per consentire gli amministratori nascondere il supporto scelta della scheda File.
-   Aggiungere HKEY\_corrente\_utente\\Software\\Microsoft\\Office\\16.0\\Outlook\\opzioni\\generali\\DisableOutlookFeedbackFeatures chiave del Registro di sistema per consentire gli amministratori di disattivare il Le opzioni "Outlook 2016 commenti e suggerimenti" e "Blog su Outlook" in File \> commenti e suggerimenti.

### <a name="skype-for-business-security-updates"></a>Skype per le aziende: aggiornamenti di sicurezza
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office vulnerabilità

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Risolvere un problema che causa una finestra di conversazione per una conversazione automaticamente accettata aprire anziché come finestra normale, ridotta a icona e in modo imprevisto impostare lo stato attivo dal altre finestre.

### <a name="word-security-updates"></a>Word: Aggiornamenti di sicurezza
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office vulnerabilità

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): Microsoft Office vulnerabilità
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): Microsoft Office vulnerabilità
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): Microsoft Office vulnerabilità



## <a name="version-1701-april-11"></a>Versione 1701: Aprile 11
*Versione 1701 (Build 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in una nuova verrà visualizzata la finestra visualizzata in grigio quando si apre una cartella di lavoro. xls.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti di sicurezza
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): Microsoft Outlook vulnerabilità
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): vulnerabilità di Microsoft Office Security funzionalità Bypass

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in cui l'utente visualizza una nuova "Microsoft Exchange" archiviare tipo nella finestra di dialogo "Nuovo File di dati Outlook" e se si seleziona il nuovo tipo di dati, il profilo dell'utente di diventare inutilizzabile.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in un'immagine mancanti errore si verifica quando l'utente effettua una "Salva con nome" in un percorso alternativo di un file di PowerPoint archiviato nel supporto rimovibile, ad esempio un'unità USB.

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui gli utenti sono in grado di effettuare l'accesso quando si passa dalla rete interna ed esterne aziendale.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): API di Microsoft Office/WordPad codice remoto esecuzione vulnerabilità w/Windows



## <a name="version-1701-march-14"></a>Versione 1701: 14 marzo
*Versione 1701 (Build 7766.2071)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in cui non sono chiuso menu a comparsa.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   Bollettino Microsoft [MS17 014](https://technet.microsoft.com/library/security/ms17-014): aggiornamento di sicurezza per Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Excel potrebbe bloccarsi quando si inserisce i collegamenti ipertestuali.
-   Risolvere problemi in Excel potrebbe avere esito negativo durante l'aggiunta di mapping XML.
-   Risolvere problemi di cui il pulsante di comando per un componente aggiuntivo non funziona dopo che il componente aggiuntivo viene aggiornato o dopo avere rimosso e il download del componente aggiuntivo da Office store.
-   Risolvere problemi in Excel potrebbe bloccarsi durante la manipolazione fogli DLL tramite VBA.

### <a name="onenote-non-security-updates"></a>OneNote: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in area di disegno pagina OneNote smette di rispondere al clic del mouse dopo l'autenticazione tramite PIN su Windows 10 versione 1607 (noto anche come Windows anniversario Update).
-   Disabilitare ottimizzata EDU specifiche printout comportamento quando un utente inserisce un documento modificabile, ad esempio file con estensione pptx o docx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui i conflitti di unione apparire erroneamente come durante la creazione condivisa.
-   Risolvere problemi di cui il pulsante di comando per un componente aggiuntivo non funziona dopo che il componente aggiuntivo viene aggiornato o dopo avere rimosso e il download del componente aggiuntivo da Office store.
-   Risolvere problemi in chiamate a VBA oggetto risultati del modello di un errore di runtime quando applicato alle forme nei grafici.

### <a name="publisher-non-security-updates"></a>Publisher: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in Publisher non visualizzare le immagini CMYK TIF.

### <a name="skype-for-business-security-updates"></a>Skype per le aziende: aggiornamenti di sicurezza
-   Bollettino Microsoft [MS17 013](https://technet.microsoft.com/library/security/ms17-013): aggiornamento di sicurezza per il componente Microsoft grafica (4013075)

### <a name="word-security-updates"></a>Word: Aggiornamenti di sicurezza
-   Bollettino Microsoft [MS17 014](https://technet.microsoft.com/library/security/ms17-014): aggiornamento di sicurezza per Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere i problemi con il consumo di memoria quando si utilizza alcune configurazioni del monitor.
-   Risolvere problemi di cui il pulsante di comando per un componente aggiuntivo non funziona dopo che il componente aggiuntivo viene aggiornato o dopo avere rimosso e il download del componente aggiuntivo da Office store.



## <a name="version-1701-february-22"></a>Versione 1701: Febbraio 22
*Versione 1701 (Build 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti alle funzionalità
-   **Miglioramenti della trasformazione e la connettività dei dati:** Espandere un elenco in una nuova colonna di testo con delimitatore tra i valori e consente di specificare un'opzione di failover durante la connessione a SQL.
-   **Miglioramenti della trasformazione e la connettività dei dati:** Il tipo di dati percentuale è ora supportato ed esperienze di creazione e modifica binario la combinazione di funzione sono state migliorate.
-   **Connettore OLEDB:** Utilizzare il connettore OLEDB Get & Transform per creare una query per importare i dati specificando una stringa di connessione e, facoltativamente, un'istruzione SQL da eseguire.
-   **Riesecuzione input penna:** Accedere a disegnare \> input penna riesecuzione di riesecuzione riconoscimento della grafia avanti e indietro per nascondere e visualizzare il contenuto, vengono fornite istruzioni dettagliate o comprendere meglio il flusso di opinioni degli altri utenti. [Ulteriori informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Supporto CSV (UTF-8):** Aprire e salvare i file CSV che utilizzano la codifica dei caratteri UTF-8.
-   **Trasformazioni dei dati e miglioramenti relativi alla connettività:** Selezionare questa opzione per importare le tabelle correlate durante il caricamento di dati da origini OData, aggiungere colonne personalizzate con valori provenienti da un calcolo della funzione o visualizzare le relazioni tra le query che utilizzano una visualizzazione dedicata.
-   **Condiviso con Me:** Visualizzare i documenti ad altri sono condivise con l'utente selezionando File \> Open \> condiviso con Me. [Ulteriori informazioni](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Cambiare i colori:** Utilizzare segnala per impostare il colore per il tipo di carattere, l'evidenziazione, riempimento della forma e altro ancora. [Ulteriori informazioni](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: Aggiornamenti di sicurezza
-   Microsoft Security bollettini [MS16 148](https://technet.microsoft.com/library/security/ms16-148): aggiornamento di sicurezza per Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove, quando il tema di Office è impostato su nero, un messaggio di errore "Errore imprevisto" viene visualizzato quando il mouse su una query nel riquadro delle query di cartella di lavoro.
-   Risolvere problemi in Excel si blocca quando l'utente tenta di accedere alle opzioni di tabella pivot.
-   Risolvere problemi in valori delle celle con testo e tra virgolette doppie non vengono esportati correttamente quando si salva come CSV o CSV UTF-8.
-   Risolvere problemi in Excel si blocca o si blocca quando si chiude.
-   Risolvere problemi in un collegamento ipertestuale che contiene una formula concatena Ignora parte del risultato concatena.
-   Risolvere problemi dove Incolla una tabella di Excel in formato RTF (RICH) in Word non preserve il formato di tabella.
-   Risolvere problemi di cui l'utente non può eseguire Salva con nome quando la cartella di lavoro contenente un foglio di lavoro di Macro di Microsoft Excel 4.0.
-   Effettuare il collegamento per spostare una selezione a livello di oggetti per identificare altre applicazioni CTRL + ALT + 5.
-   Correzione un problema cui, quando la digitazione nella barra della formula e l'utilizzo di una funzione con un elenco a discesa, ad esempio VLOOKUP, premendo INVIO per completare la formula seleziona il primo elemento nell'elenco a discesa di completamento automatico anziché leavingthe digitato in valore-è.
-   Risolvere problemi in apertura di un file in formato (BIFF8) file binario di Excel 2003 che contiene un collegamento ipertestuale in un foglio di lavoro protetto Excel 97 - fa sì che Excel da considerare il file è danneggiato ed Excel tenta di ripristinare o rimuovere il contenuto illeggibile.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: aggiornamenti Non correlati alla sicurezza
-   Risolvere i problemi a cui, se il GrooveIntlResource.dll non possono essere caricati correttamente (che è improbabile in condizioni normali), un'applicazione di Office può bloccarsi se l'utente tenta di aprire o salvare un file in una cartella sincronizzata o Esplora può bloccarsi se l'utente passa a un cartella sincronizzato tramite Esplora risorse.
-   Risolvere problemi in OneDrive for Business non è disabilitato, anche se la chiave del Registro di sistema appropriate è impostata su disabilitarlo quando Office è configurato per ricevere aggiornamenti da una posizione diversa dall'Office contenuto rete (CDN).

### <a name="onenote-feature-updates"></a>OneNote: Aggiornamenti delle funzionalità
-   **Controllare la sincronizzazione file e immagine:** Passare a File \> opzioni \> di sincronizzazione per controllare se tutti i file e le immagini vengono scaricate automaticamente per tutte le pagine in blocchi appunti.

### <a name="onenote-non-security-updates"></a>OneNote: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in OneNote si blocca quando si stampa un'immagine più grande della pagina.
-   Risolvere problemi in cui un utente non può eliminare un modello di pagina personalizzato.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti alle funzionalità
-   **Collaborare per gli allegati in tempo reale:** Caricare un allegato a OneDrive for Business consentire a chiunque di lavorare la versione più recente. Utilizzare il menu a discesa sull'allegato per caricare o salvarlo.
-   **Riepilogo schede per viaggiano prenotazioni e dei pacchetti:** Verificare e tenere traccia di prenotazioni viaggi, nonché consegne pacchetto, tramite schede riepilogo automaticamente create nella cartella Posta in arrivo e calendario. [Ulteriori informazioni](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Editor:** Vengono fornite avanzate e contestuale strumenti di correzione per migliorare la scrittura di uno. [Ulteriori informazioni](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove, quando il mouse su un allegato nell'elenco degli allegati per una conversazione, tutte le voci di menu di scelta sono visibili invece solo le voci di menu applicabile.
-   Risolvere problemi in messaggi di posta elettronica RTF (RICH Text Format) non possono essere aperti se il messaggio è stato inviato tramite Information Rights Management dal destinatario.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti alle funzionalità
-   **Chiuso didascalie:** Se una diapositiva contiene un video che è stata chiusa didascalie, è possibile riprodurre le didascalie nella presentazione.
-   **Più tracce audio:** Se una diapositiva contiene un video con più tracce audio, è possibile riprodurre le tracce nella presentazione.
-   **Sezione copia:** Copiare e incollare sezioni tra le presentazioni.
-   **Condiviso con Me:** Visualizzare i documenti ad altri sono condivise con l'utente selezionando File \> Open \> condiviso con Me. [Ulteriori informazioni](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Riesecuzione input penna:** Riproduzione di riconoscimento della grafia avanti e indietro per nascondere e visualizzare il contenuto, vengono fornite istruzioni dettagliate o comprendere meglio il flusso di opinioni degli altri utenti. [Ulteriori informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Registrazioni dell'integrazione:** Creazione di una presentazione composto da diapositive registrate, le registrazioni dello schermo e inserito video e quindi condividere tale contenuto registrato da visualizzare in remoto. È inoltre possibile incorporare quiz per contribuire alla formazione a distanza e rendere la presentazione più interattive e cambia il colore di penna e all'utilizzo più semplice registrare commenti audio e controlli audio.
-   **Miglioramenti della finestra di progettazione:** Vengono forniti suggerimenti di progettazione con SmartArt per gli elenchi puntati processo.
-   **Scheda della barra multifunzione di registrazione:** Personalizzazione della barra multifunzione per aggiungere una scheda di registrazione.
-   **Cambiare i colori:** Utilizzare segnala per impostare il colore per il tipo di carattere, l'evidenziazione, riempimento della forma e altro ancora. [Ulteriori informazioni](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Zoom:** Creare un riepilogo delle presentazioni interattivo con collegamenti di spostamento automatiche. [Ulteriori informazioni](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Aprire i collegamenti ipertestuali:** Tenendo premuto CTRL fare clic per aprire i collegamenti ipertestuali durante la modifica di una presentazione.
-   **Evidenziazione del testo:** Evidenziare le parti di testo utilizzando l'evidenziazione del testo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove, quando il ritaglio immagine, la parte dell'immagine ritagliata viene visualizzato scura.
-   Risolvere problemi dove, durante l'esecuzione in modalità di presentazione e l'Assistente vocale, arresti anomali PowerPoint quando l'utente fa clic su un collegamento ipertestuale e il sito sono lenti da caricare.
-   Risolvere problemi digitando in tempo reale durante la creazione condivisa dove non funziona con le tabelle.
-   Risolvere problemi cui, durante l'apertura di PowerPoint in un computer che ha installato 3.0 Malwarebytes, viene visualizzato un errore "Stopped lavoro" o PowerPoint si blocca.
-   Risolvere i problemi a cui il modello predefinito non viene visualizzata in File \> New.
-   Risolvere problemi in digitare il testo viene interrotta e ritardato quando un file che incorpora tipi di carattere viene salvato automaticamente.
-   Risolvere i problemi con la copia di immagini (SVG) grafiche scalabili vettoriale da Adobe Illustrator.

### <a name="project-feature-updates"></a>Project: Aggiornamenti della funzionalità
-   **Campo bloccato:** Impostare il valore su Sì per impedire l'invio di aggiornamenti per un'attività i membri del team.
-   **Etichette sequenza temporale:** Distinguere barre sequenza temporale in base alle etichette per assegnare nomi descrittivi.
-   **Gli indicatori di stato sequenza temporale:** Utilizzare i segni di spunta e colorato gli indicatori di stato nella visualizzazione sequenza temporale per mostrare di avanzamento vengono con ogni attività.
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, l'Assistente vocale e altre tecnologie di leggere e modificare progetti.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui viene visualizzata alcuna linea di collegamento durante la creazione di un collegamento tra progetti tra un progetto principale e un sottoprogetto.
-   Risolvere i problemi a cui rapportato alla linea di base non è sempre salvata correttamente in formato XML, soprattutto costi e sul lavoro valori che includono le durate parziale.
-   Risolvere problemi dove, quando si applica gli aggiornamenti dello stato, lavoro effettivo viene aggiunto per l'assegnazione non segnala il membro del team.
-   Risolvere problemi in cui vengono visualizzati i valori di base per una risorsa, anche se non è stato creato una linea di base per la risorsa.
-   Risolvere problemi in anteprima di stampa Ritaglia testo in modo che il testo non è visibile.
-   Risolvere problemi dove, quando si apre un file con estensione mpp di SharePoint con un URL di collegamento, il file viene aperto come check-out, anche se l'impostazione "obbligatoria dei documenti per l'estrazione prima che possano modificati?" è abilitata.
-   Risolvere problemi dove gli aggiornamenti alle risorse materiali da Project Web App viene modificato in modo non corretto dei dati rapportati alla scala cronologica.
-   Risolvere problemi di cui l'apertura di un progetto con un'attività cardine può aggiungere una data di inizio effettivo a esso anche se non dispongono di una data nel momento in cui l'ultimo salvataggio.
-   Risolvere un problema di lavoro breakdown structure (WBS) rinumerando.
-   Risolvere problemi in Project si blocca quando si passa da una visualizzazione basata su griglia e Assistente vocale è nella.
-   Risolvere problemi in cui è visualizzato sul troncamento dei dati rapportati alla scala cronologica un messaggio di errore non corretto durante l'apertura di un file XML.
-   Risolvere problemi di cui viene salvata una previsione non imposta correttamente rapportati alla scala cronologica.
-   Risolvere problemi in ritardo assegnazione viene ignorato quando vengono letti i dati di progetto da un file XML.
-   Risolvere problemi dove, quando si apre un file di Project Online, mostrato nella data ultima modifica dell'ora UTC anziché il fuso orario corretti ora.
-   Risolvere problemi di cui non appaiono raggruppamento colore bande per le righe di raggruppamento non viene stampata una visualizzazione a elenco.
-   Risolvere problemi in cui è un'opzione di ripristino in modo non corretto visualizzata quando l'utente controlla se un'attività che è presente un'assegnazione di là problema unità max.
-   Risolvere problemi dove il valore di un campo codice struttura non può essere modificato dopo la pubblicazione del progetto.
-   Risolvere problemi dove le barre di Gantt non sono dimensioni corrette in alta schermate DPI 175% dello schermo.
-   Risolvere problemi dove se l'utente imposta il tempo di ritardo tramite la finestra di dialogo Informazioni attività, viene impostata erroneamente su una durata.
-   Risolvere problemi dove se aprire alcuni file XML, la data di inizio attività non è impostato correttamente a causa di un problema con l'assegnazione.

### <a name="skype-for-business-feature-updates"></a>Skype per le aziende: gli aggiornamenti delle funzionalità
-   **Lo stile di notifica di Windows:** Modifiche apportate all'aspetto delle notifiche per le conversazioni e le chiamate in arrivo. [Ulteriori informazioni](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Trasferimento con consultazione:** All'interno di una chiamata, rivolgersi a un altro utente tramite messaggistica immediata o di chiamata prima di trasferire la chiamata a tale utente. [Ulteriori informazioni](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notifiche microfono:** Mostra notifica nella finestra di conversazione quando il microfono è disattivato nel sistema operativo o se il microfono non preleva qualsiasi audio.
-   **Disattivare "My number":** Utilizzare la voce del Registro di sistema DisableDisplayMyNumber per disabilitare "My number" sotto la tastiera.

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Modificare i pulsanti sala d'attesa utilizzati per ammettere o negare partecipanti dal testo alle immagini (X o un segno di spunta).
-   Modificare la riunione testo di notifica promemoria da "Accetta" a "Join".
-   Aggiornare il messaggio visualizzato al mittente di un messaggio Istantaneo quando lo stato del destinatario è impostato su non disturbare.
-   Aggiorna il messaggio visualizzato al mittente di un messaggio Istantaneo, quando il destinatario è non in linea e "salvataggio alla cronologia" è disattivato per chiarire che il destinatario non verrà visualizzato il messaggio.
-   Aggiungere la funzionalità di spostamento della barra di divisione verticale tra l'elenco dei partecipanti in una chat di gruppo e la cronologia della chat.
-   Aggiungere la funzionalità per ridimensionare l'elenco delle schede nelle finestre di messaggistica immediata o la chat.
-   Aggiungere la funzionalità selezionare le chat room effettuate durante la creazione di un argomento feed.
-   Risolvere problemi quale messaggio non visualizzate nella Mid-conversazione cronologia della chat.
-   Risolvere problemi cui messaggi duplicati vengono visualizzati nella finestra Conversazione.
-   Risolvere problemi in azioni di notifica avvisi (accetta e ignora) non vengono visualizzate correttamente durante un volume elevato di notifiche.
-   Risolvere problemi in cui l'utente non può digitare un messaggio dopo aver utilizzato Alt + Tab per aprire una finestra di conversazione ridotta a icona.
-   Risolvere problemi in grigio sul pulsante messaggio Istantaneo nella scheda contatto per un utente, anche se messaggistica immediata è disponibile.
-   Risolvere problemi in più finestre di conversazione non aprire nuovamente per le dimensioni precedenti e i percorsi dopo essere stato chiuso e riaperto.
-   Risolvere problemi in collegamenti personalizzati non sulla barra di avvio quando selezionato.
-   Risolvere problemi di cui la riunione online nel campo zona non è visualizzato correttamente per i caratteri non in lingua inglese.
-   Risolvere problemi cui informazioni di notifica, ad esempio durata della chiamata, non vengono visualizzate correttamente nelle lingue da destra a sinistra.
-   Risolvere problemi dove, quando si crea un argomento feed, la deselezione di risultati della ricerca non reimposta i risultati a un elenco di sale visitati.
-   Risolvere problemi dove Skype per le aziende si blocca quando sono aperte più finestre di conversazione contemporaneamente.
-   Risolvere problemi di cui l'ultima finestra di conversazione scompare una volta chiuse tutte le altre schede.
-   Risolvere problemi di cui lo stato attivo predefinito non è nell'area di immissione chat durante le conversazioni a schede sono disattivate.
-   Risolvere problemi dove il "dimenticato il PIN di accesso esterno?" collegamento non viene visualizzato nell'invito alla riunione.
-   Risolvere i problemi in parte del testo viene troncato e troncati nelle pagine del dispositivo Audio e generale quando utilizzando DPI elevata delle schermate in visualizzazione 175% o superiore.
-   Risolvere problemi dove Skype per le aziende si blocca quando il computer è sospeso o ripreso quando non è disponibile alcuna rete e il computer che esegue un "sempre in, sempre connessi (AOAC").
-   Risolvere problemi di cui non microfono viene rilevata una chiamata quando si utilizza un dispositivo Polycom CX100.
-   Risolvere problemi in cui la scelta di un collegamento ad esempio \\ \\nomeserver o file:// in un messaggio immediato dei risultati in un messaggio di errore anziché aprire il percorso.
-   Risolvere i problemi, in un ambiente Virtual Desktop Infrastructure (VDI) che utilizza il routing basato sulla posizione, dove l'utente non può effettuare o ricevere chiamate PSTN in quanto il server rileva che la posizione dell'utente non è valida per le chiamate PSTN.
-   Modificare la riga dell'oggetto del messaggio di posta elettronica inviato per un messaggio senza risposta, quando lo stato dell'utente è impostato su non disturbare o parola presentazione, da "conversazioni con perse \<nome\>"a"\<nome\> è un messaggio inviato in Skype per le aziende."
-   Avviare il processo di data/ora per la prima ora sign-nel dispositivo come parte dei [dati](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) per aiutare a identificare le tendenze accesso affidabilità.
-   Risolvere problemi di cui non viene visualizzata l'opzione per condividere un monitor secondario con alcune configurazioni monitor nella finestra di 10 versione 1607 (detto anche l'aggiornamento anniversario).
-   Risolvere problemi dove Skype per arresti anomali Business quando lo zoom nel contenuto condiviso quando il condivisore utilizza un 3rd parti implementazione del protocollo RDP.
-   Risolvere problemi di cui il pannello di controllo Audio non viene visualizzata quando un utente fa clic sul pulsante controlli in una chiamata audio in un ambiente Virtual Desktop Infrastructure (VDI).
-   Risolvere problemi di cui gli utenti visualizzeranno una schermata nera quando un utente è in esecuzione Windows 7 e condivide innanzitutto il monitor principale e quindi si passa per condividere un monitor secondo.
-   Risolvere problemi dove speciale caratteri, ad esempio la e commerciale (&), non è possibile immettere nella casella di immissione di ricerca o il "appuntamenti giornalieri?" Nella sezione.
-   Risolvere un problema in cui il numero di messaggi non letti non viene visualizzato quando sono disponibili senza risposta a messaggi immediati non in linea.
-   Risolvere problemi cui "Invita tramite posta elettronica" modelli menzionato Lync anziché Skype.
-   Risolvere problemi dove il numero di riga è mancano dall'area "My Number" sotto la tastiera.
-   Risolvere problemi di cui non è riportato il puntatore del mouse nell'area di immissione immediata dopo l'invio di un messaggio in una chat.
-   Risolvere i problemi a cui si blocca Skype per le aziende durante l'accesso e non esiste un problema durante il caricamento il pool della cache.
-   Risolvere problemi di cui si blocca Skype per le aziende durante l'accesso e il ripristino delle conversazioni.
-   Risolvere problemi di cui si blocca Skype per le aziende durante l'accesso dopo la riattivazione.
-   Risolvere problemi di cui è disabilitato il collegamento della riunione se i server di Exchange in entrambe le organizzazioni sono TNEF disabilitata.
-   Risolvere problemi di cui non è possibile riavviare una videochiamata se esiste una sola conversazione di messaggistica Istantanea succedendo.
-   Risolvere problemi dove le annotazioni di testo su una lavagna vengono perse quando si salva un file PNG Lavagna.
-   Risolvere problemi di cui la prima riga viene nascosta quando immissione su due righe in giapponese nella finestra di messaggistica immediata.
-   Risolvere problemi dove il carattere e commerciale (&) in modo non corretto viene sostituito da un carattere di sottolineatura nei nomi.
-   Risolvere i problemi con l'URL "Partecipa a riunione online" in una riunione pianificata.
-   Risolvere problemi di cui si posiziona il puntatore del mouse su una finestra non attiva la finestra anche se il sistema operativo è configurato per eseguire questa operazione.
-   Risolvere problemi di cui verificare che gli elementi della cronologia conversazioni di chiamata in uscita viene illustrato il chiamante anziché la persona chiamata.
-   Risolvere problemi in cui il F12 localmente non salvare una conversazione.
-   Risolvere problemi in un messaggio di posta elettronica conversazioni non effettuate non contiene il messaggio immediato iniziale.
-   Risolvere problemi di cui è possibile aggiungere a un emoji nell'area di testo di messaggi immediati anche se il relatore ha disabilitato la partecipazione di messaggistica immediata.
-   Risolvere i problemi con il layout della finestra di dialogo Opzioni suonerie e suoni.
-   Risolvere problemi dove Skype per le aziende si blocca quando si chiude una finestra di conversazione.
-   Risolvere problemi in DNS meno accesso ha esito negativo se il dominio è registrato come un dominio personale.
-   Risolvere i problemi a cui le impostazioni di notifica di chat persistente non vengono salvata o caricati correttamente.
-   Risolvere problemi in finestre di conversazione peer-to-peer esistenti o le chat non viene visualizzata dopo l'accesso anche se l'impostazione per riaprire conversazioni.
-   Risolvere i problemi a cui la disattivazione dell'audio o viceversa conversazione attiva fa sì che altre finestre di conversazione venga visualizzato come se dispongono di messaggi non letti.
-   Risolvere problemi di cui gli utenti che sono configurati per il bypass multimediale sono in grado di riprendere una chiamata da un gateway PSTN dopo la chiamata è stato messo in attesa.
-   Risolvere problemi di cui l'utente visualizza una casella blu anziché il video durante una riunione tramite URL quando utilizzando un 3rd parti implementazione del protocollo RDP.
-   Risolvere problemi di cui viene visualizzata la parte di utenti dell'indirizzo SIP anziché il nome visualizzato in un avviso popup.
-   Risolvere i problemi a cui, se Skype per le aziende si connette a un server SIP tramite la porta 443 e un server proxy è presente, non esiste un notevole ritardo nel processo di accesso se il proxy non accetta tale connessione. La correzione è abilitata per aggiungere la voce del Registro di sistema EnableDetectProxyForAllConnections DWORD in HKEY\_corrente\_utente\\Software\\Microsoft\\UCCPlatform\\Lync e impostare il valore su 1.
-   Risolvere problemi dove, quando si utilizzano le conversazioni a schede, fare doppio clic su una scheda e iniziare a digitare potrebbero causare lo stato attivo passare a un'altra scheda e continuare a digitarlo nella finestra Conversazione.
-   Risolvere problemi dove gli URL inclusi in un messaggio immediato non possono essere selezionati nella finestra di cronologia delle chat utilizzando la tastiera.
-   Risolvere problemi di cui deve Impossibile ascoltare l'audio di digitazione Se in Opzioni di suoneria e suoni è selezionata la casella di controllo "Riproducono un suono quando la visualizzazione di una conversazione di messaggistica immediata e si digita".
-   Risolvere problemi di cui non sono annunciate finestre di dialogo che vengono visualizzati quando si utilizza un software screen reader, ad esempio l'Assistente vocale.
-   Risolvere problemi in cui non è possibile spostarsi con una tastiera esercitazione prima esecuzione e non può essere letti da un software screen reader, ad esempio l'Assistente vocale.
-   Risolvere problemi di cui l'icona della presenza della barra delle applicazioni non viene scalata nelle impostazioni DPI elevata.
-   Risolvere problemi di cui il pulsante di campo deselezionare la casella di ricerca non può essere selezionato utilizzando la tastiera.
-   Risolvere problemi di cui un utente non può avviare una riunione se l'invito proviene da un utente in un altro pool.
-   Risolvere problemi di cui un utente l'aggiunta a una riunione in modo non corretto viene indicato come un account utente diverso.
-   Risolvere problemi a cui era nascosta l'icona di presenza di contatti nella notifica dello stato di modifica per le chiamate in arrivo per il proprio responsabile.
-   Risolvere problemi dove non corrisponde ad intermittenza del cursore di testo nella finestra di messaggistica immediata le proprietà della tastiera l'impostazione di Windows.
-   Risolvere problemi in un software screen reader annuncia un nome di contatto non corretto per una conversazione di gruppo.
-   Risolvere problemi quali l'utente non può selezionare più contatti utilizzando la tastiera.
-   Risolvere problemi di cui non è possibile recuperare foto dell'utente di Exchange.
-   Risolvere problemi in Skype per Business client si connette a un Skype per Business Server nella rete interna, anziché una rete esterna, quando l'utente si connette tramite accesso diretto.
-   Risolvere problemi dove Skype per client Business si blocca quando si tenta di risolvere il nome del proprietario della riunione.
-   Risolvere un problema se si modifica un Windows impostazione durante l'avvio di Skype per le aziende o l'arresto, dove Skype for Business in modo anomalo.
-   Risolvere problemi dove Skype per le aziende si blocca quando lo stato attivo aprire l'elenco dei partecipanti in una chat persistente e tenta di spostare la tastiera per l'elenco dei partecipanti.
-   Risolvere problemi dove Skype per le aziende si blocca in resume quando è disponibile alcuna rete.

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti alle funzionalità
-   **Database modellazione componente aggiuntivo:** Utilizzare il componente aggiuntivo per creare un modello di database di un database esistente per pianificare un nuovo database o acquisire familiarità con uno esistente. [Ulteriori informazioni](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [Scarica componente aggiuntivo](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, l'Assistente vocale e altre tecnologie per utilizzare le forme, modificare con altri utenti e altro ancora.
-   **Modelli di terze parti e diagrammi:** Individuare o cercare nuovi modelli e diagrammi di esempio rese disponibili da selezionare provider di contenuti di terze parti. Nome del provider di terze parti è elencato in anteprima.
-   **Input penna di supporto:** Utilizzare la penna o un dito per disegnare e aggiungere note con gli strumenti della scheda nuovo disegno.

### <a name="word-feature-updates"></a>Word: Aggiornamenti alle funzionalità
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, l'Assistente vocale e altre tecnologie di leggere e modificare i documenti. [Ulteriori informazioni](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Editor:** Vengono fornite avanzate e contestuale strumenti di correzione per migliorare la scrittura di uno. [Ulteriori informazioni](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Riesecuzione input penna:** Accedere a disegnare \> input penna riesecuzione di riesecuzione riconoscimento della grafia avanti e indietro per nascondere e visualizzare il contenuto, vengono fornite istruzioni dettagliate o comprendere meglio il flusso di opinioni degli altri utenti. [Ulteriori informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Modificare con movimenti naturale della penna:** Apportare modifiche a un documento di un cerchio per selezionare e cancellando da eliminare. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Condiviso con Me:** Visualizzare i documenti ad altri sono condivise con l'utente selezionando File \> Open \> condiviso con Me. [Ulteriori informazioni](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Cambiare i colori:** Utilizzare segnala per impostare il colore per il tipo di carattere, l'evidenziazione, riempimento della forma e altro ancora. [Ulteriori informazioni](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in un documento visualizzato in modalità lettura impedisce il tasto TAB lavorare in un secondo documento venga visualizzato come Layout di stampa.
-   Risolvere problemi in Word si blocca quando viene caricata più di una raccolta di grammatica.
-   Risolvere problemi dove finale e tratti eliminate dopo due o tre tratti.
-   Risolvere i problemi con virgolette inglesi che scompaiono quando si utilizza il Google Editor IME (Input Method).
-   Risolvere problemi di cui un utente non può utilizzare input penna con controlli contenuto o quando non contigui selezioni.

### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: gli aggiornamenti delle funzionalità
-   **Inviare commenti e suggerimenti:** Suggerire nuove funzionalità o commenti Microsoft che si desidera o cosa non funziona tramite File \> commenti e suggerimenti

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti di sicurezza
-   Microsoft Security bollettini [MS16 148](https://technet.microsoft.com/library/security/ms16-148): aggiornamento di sicurezza per Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi in utilizzando CTRL + ALT + 7 o CTRL + ALT + 8 sulla tastiera tedesca apre lo strumento commenti e suggerimenti utente, anziché l'inserimento di caratteri appropriato.
-   Risolvere problemi dove TraceLogging causa l'interruzione in Windows 7 durante l'installazione o aggiornamento di Office.
-   Risolvere problemi dove, quando il disegno con penna e l'utilizzo del mouse, rilasciare il pulsante del mouse provoca l'input penna spostare leggermente.
-   Risolvere problemi di cui, dopo l'inserimento di un'immagine SVG in un documento di Office, l'immagine SVG viene nascosta quando il documento viene salvato e vengono riaperte.
-   Risolvere i problemi in Office visualizza il messaggio di errore durante l'attivazione per gli utenti non in lingua inglese: "la lunghezza massima del codice product key è 25 caratteri".
-   Risolvere un problema con i moduli VBA possono causare l'ordine z delle cornici le cui smettere di funzionare o non vengono visualizzati correttamente.
-   Risolvere problemi in un aggiornamento trigged per System Center Configuration Manager modifica l'impostazione UpdateChannel nel Registro di sistema per un elemento che non è un canale di aggiornamento valido.



## <a name="version-1609-january-10"></a>Versione 1609: 10 gennaio
*Versione 1609 (Build 7369.2102)*

Nota: Gli aggiornamenti di sicurezza descritti nel Bollettino Microsoft [MS17-002](https://technet.microsoft.com/library/security/ms17-002) non si applicano alla versione di Word in questa versione di canale.

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove utilizzando la finestra di dialogo Modifica misura fa sì che Excel per arresto anomalo del sistema.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi cui utilizzo delle forme in alcuni casi fa sì che PowerPoint per arresto anomalo del sistema.

### <a name="skype-for-business-non-security-updates"></a>Skype per le aziende: aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi di cui non viene visualizzata l'opzione per condividere un monitor secondario con alcune configurazioni monitor nella finestra di 10 versione 1607 (detto anche l'aggiornamento anniversario).
-   Risolvere problemi dove Skype per arresti anomali Business quando lo zoom nel contenuto condiviso quando il condivisore utilizza un 3rd parti implementazione del protocollo RDP.
-   Risolvere i problemi a cui, se Skype per le aziende si connette a un server SIP tramite la porta 443 e un server proxy è presente, non esiste un notevole ritardo nel processo di accesso se il proxy non accetta tale connessione. La correzione è abilitata per aggiungere la voce del Registro di sistema EnableDetectProxyForAllConnections DWORD in HKEY\_corrente\_utente\\Software\\Microsoft\\UCCPlatform\\Lync e impostare il valore su 1.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti Non correlati alla sicurezza
-   Risolvere problemi dove, quando si utilizza il metodo InsertXML, viene visualizzato un segnaposto per un collegamento immagine interrotta anziché all'immagine.

