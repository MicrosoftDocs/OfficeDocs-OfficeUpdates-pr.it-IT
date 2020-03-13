---
title: Note sulla versione per i rilasci del canale semestrale (mirato) in 2017
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.date: 12/12/2017
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Normal
ms.collection: RelNotes_ProPlus
description: Fornisce ai professionisti IT le note sulle versioni per i rilasci del canale semestrale (mirato) per Office 365 ProPlus in 2017
ms.openlocfilehash: 911626feb56a68ab258b51de78142dfaf6926bbe
ms.sourcegitcommit: 9301d8769d8860013e7b789a3360f48de461ad49
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 03/13/2020
ms.locfileid: "42615002"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2017"></a>Note sulla versione per i rilasci del canale semestrale (mirato) in 2017

Queste note sulla versione forniscono informazioni su nuove funzionalità, aggiornamenti della sicurezza e aggiornamenti non correlati alla sicurezza inclusi negli aggiornamenti del canale semestrale (mirato) a Office 365 ProPlus in 2017.
 
> [!NOTE]
> - Di seguito vengono fornite informazioni sulle nuove caratteristiche, sugli aggiornamenti della sicurezza e non della sicurezza per Visio Pro per Office 365 e Project Online Desktop Client.
> - Queste informazioni si applicano anche a Office 365 Business, ovvero la versione di Office fornita con alcuni piani di Office 365, ad esempio Business Premium.
> - Il canale semestrale (mirato) è stato denominato First Release per Deferred Channel prima del settembre 2017.

## <a name="version-1708-december-12"></a>Versione 1708:12 dicembre
*Versione 1708 (Build 8431.2131)*

 ### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2017-11935](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11935): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema in cui l'utente visualizza un messaggio di "Errore irreparabile" non corretto quando viene aperta una cartella di lavoro di Office 2007 o versione precedente (.xls o .xla) con le macro.
-   Consente di risolvere un problema a causa del quale l'apertura di una cartella di lavoro dalla riga di comando potrebbe comportare la perdita del Rich Text Format di una cella.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilità della divulgazione delle informazioni di Microsoft Office

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti della sicurezza
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilità della divulgazione delle informazioni relative a Microsoft PowerPoint

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale i dati del campo personalizzato a livello di progetto non vengono salvati.
-   Consente di risolvere un errore a casa del quale un errore di salvataggio potrebbe danneggiare un file e causare l'arresto anomalo di Project all'avvio.
-   Consente di risolvere un problema a causa del quale l'apertura di un piano di progetto potrebbe determinare un arresto anomalo.

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza
-   [Avviso 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Aggiornamento difensivo di Microsoft Office



## <a name="version-1708-november-14"></a>Versione 1708:14 novembre
*Versione 1708 (Build 8431.2110)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui se si tenta di selezionare il testo nella casella di testo di una casella combinata viene selezionato tutto il testo, anziché la parte selezionata.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2017-11877:](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877) le funzionalità di sicurezza di Microsoft Excel ignorano la vulnerabilità
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilità di danneggiamento della memoria di Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema in cui l'utente non è in grado di chiudere una cartella di lavoro in visualizzazione protetta quando il nome file contiene parentesi quadre.
-   Consente di risolvere un problema in cui, quando si tenta di inserire un oggetto in una cartella di lavoro esistente, Excel si arresta in modo anomalo quando l'utente fa clic su Sfoglia.
-   Consente di risolvere un problema in cui, selezionando "Ridimensiona forma per correggere il testo" (nella porzione Opzioni testo/Casella di testo del riquadro Formato forma), non vengono apportate modifiche alla forma.
-   Consente di risolvere un problema in cui, quando si apre una cartella di lavoro facendo doppio clic su di essa, i tipi di carattere e i formati del testo della cella non vengono caricati oppure vengono aperte due cartelle di lavoro identiche per un singolo modello.
-   Consente di risolvere un problema in cui la prima cartella di lavoro creata all'avvio di Excel non si chiude quando viene aperta o creata un'altra cartella di lavoro.
-   Consente di risolvere un problema a causa del quale la descrizione comando non si allinea correttamente quando si trascinano elementi oppure si trascina il riempimento.
-   Consente di risolvere un errore che si verifica quando si salva una cartella di lavoro utilizzando File \> Salva con nome e causa del quale il nome del file viene visualizzato vuoto oppure troncato nella finestra di dialogo di salvataggio del file.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.
-   Consente di risolvere un problema con il rendering in cui vengono visualizzate intestazioni e linee nere a causa di un driver di grafica guasto.
-   Consente di risolvere un problema in cui Excel si arresta in modo anomalo o non è in grado di salvare la cartella di lavoro dopo l'inserimento di un grafico.
-   Consente di risolvere un problema in cui la linea di interruzione della pagina nell'anteprima interruzioni di pagina non è posizionata correttamente.

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui l'utente visualizza lo stato attivo nell'elenco dei messaggi in modo imprevisto quando elimina i messaggi.
-   Consente di risolvere un problema a causa del quale l'utente visualizza richieste di autenticazione quando interagisce con gli allegati.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.
-   Consente di risolvere un problema in cui la modifica e la formattazione del testo dopo un annullamento in una tabella causano l'arresto anomalo di PowerPoint.
-   Consente di risolvere un problema in cui i riferimenti a Flash Player basati sui codici di incorporamento di YouTube causano l&apos;apertura di una nuova finestra per la riproduzione del video. I vecchi codici di incorporamento sono ora aggiornati al riferimento HTML5 basato sui video di YouTube affinché vengano riprodotti correttamente.

### <a name="word-security-updates"></a>Word: Aggiornamenti della sicurezza
-   [Avviso 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Aggiornamento difensivo di Microsoft Office

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Word si arresta in modo anomalo quando un utente prova a salvare con il nome un documento esistente su OneDrive for Business e in seguito si annulla il salvataggio oppure si prova a unire le modifiche esistenti.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.
-   Consente di risolvere un problema in cui non è possibile chiudere Word se l'utente passa alla scheda Inserisci poco dopo aver aperto Word.
-   Consente di risolvere un problema in cui, dopo aver fatto clic sul margine, i caratteri vengono visualizzati nell'angolo superiore sinistro della schermata quando vengono immessi.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema con l'ingrandimento e il ridimensionamento nei componenti aggiuntivi per Office nell'ambiente DPI dinamico.
-   Consente di risolvere un problema in cui il nodo CurrentStatus del CSP (Configuration Service Provider) di Office restituisce una stringa vuota anche se Office 365 ProPlus è installato.
-   Consente di risolvere un problema a causa del quale il formato del file .box viene modificato, cosa che influisce sulle funzionalità delle versioni meno recenti di Office installate sullo stesso computer, perché i file .box sono condivisi tra tutte le versioni di un'app di Office sullo stesso computer.
-   Consente di risolvere un problema a causa del quale, nei casi in cui viene utilizzata l'attivazione di computer condivisi, viene visualizzato un messaggio di errore che indica che l'app eseguita ha provocato un errore che ne impedisce il corretto funzionamento e che chiede se si desidera eseguire un ripristino.



## <a name="version-1708-october-10"></a>Versione 1708:10 ottobre
*Versione 1708 (Build 8431.2107)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui una query non viene eseguita se la query presenta un join con una chiave primaria di una tabella collegata Microsoft Dynamics.
-   Consente di risolvere un problema per cui le posizioni decimali non vengono visualizzate per valori di valuta in una tabella Microsoft Dynamics.

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando si apre un file .XLL.
-   Consente di risolvere un problema per cui lo stile motivo di una cella non viene visualizzato correttamente dopo l'aggiunta di un'intestazione o piè di pagina nella visualizzazione Layout di pagina.
-   Consente di risolvere un problema per cui, incollando una copia di una Tabella pivot in un'altra cartella di lavoro, potrebbe verificarsi un arresto anomalo.
-   Consente di risolvere un problema per cui, quando si sceglie il comando Sostituisci e si apre la finestra di dialogo Trova e sostituisci, il focus della finestra di dialogo è nella scheda Trova invece che nella scheda Sostituisci.
-   Consente di risolvere un problema per cui Excel si arresta in modo anomalo quando si apre il riquadro Attività per una cartella di lavoro aperta da un server di SharePoint precedente a SharePoint Server 2016.
-   Consente di risolvere un problema per cui Excel si apre e visualizza una finestra vuota quando uno o più componenti aggiuntivi XLL sono abilitati.
-   Consente di risolvere un problema per cui Excel si arresta in modo anomalo dopo aver utilizzato il pulsante Forms in una cartella di lavoro già chiusa.
-   Consente di risolvere un problema per cui, quando si utilizza l'evento SheetBeforeRightClick, inserendo una colonna che interseca le celle unite non si espandono le celle unite.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-11774](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11774): le funzionalità di sicurezza di Microsoft Outlook ignorano la vulnerabilità
-   [CVE-2017-11776](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11776): vulnerabilità della divulgazione delle informazioni relative a Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui il collegamento "Ulteriori informazioni" in Suggerimenti per i criteri non è visibile quando si usa il tema Grigio scuro.
-   Consente di risolvere un problema per cui Outlook si arresta in modo anomalo quando l'utente prova a configurare un nuovo account e chiude la finestra senza completare la configurazione dell'account.
-   Consente di risolvere un problema per cui Segna come già letto e Segna come da leggere vengono visualizzate come opzioni dei messaggi nella Posta in arrivo condivisa di un gruppo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema per cui PowerPoint si arresta in modo anomalo quando si apre una presentazione da un server di SharePoint precedente a SharePoint Server 2016.

### <a name="word-security-updates"></a>Word: Aggiornamenti della sicurezza
-   [CVE-2017-11826](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11826): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema per cui Word si arresta in modo anomalo quando si apre il riquadro Attività per un documento aperto da un server di SharePoint precedente a SharePoint Server 2016.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-11825](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11825): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema per cui l'avanzamento di Ripristino online non viene mostrato all'utente.
-   Consente di risolvere un problema per cui le proprietà dei file Office non vengono visualizzate in Esplora file.
-   Consente di risolvere un problema in cui i pulsanti dei componenti aggiuntivi Office spariscono dalla barra multifunzione quando è presente un secondo documento aperto.
-   Consente di risolvere un problema per cui alcuni moduli VBA con nomi con caratteri a due byte non possono essere aperti.



## <a name="version-1708-september-12"></a>Versione 1708:12 settembre
*Versione 1708 (Build 8431.2079)*

### <a name="access-feature-updates"></a>Access: Aggiornamenti delle funzionalità
-   **Proprietà Nome etichetta:** migliora l'accessibilità poiché associa un'etichetta a un controllo presente in una maschera.
-   **L'operazione di modifica di un nuovo elemento è più accessibile:** utilizzare i tasti di scelta rapida CTRL+E per modificare un nuovo elemento dalla casella combinata oppure dalla casella di riepilogo.
-   **Dynamics Connector:** consente di importare i dati oppure collegare i dati archiviati in Microsoft Dynamics. [Ulteriori informazioni](https://support.office.com/article/636079c1-9fc3-4fca-8410-6596d62223da)
-   **Connettore Salesforce:** importare i dati oppure collegare i dati archiviati in Salesforce. [Ulteriori informazioni](https://support.office.com/article/7375ffb6-1d6a-46f1-bb0c-c6ac3c58f5a0)

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti delle funzionalità
-   **Miglioramenti di "Aggiungi colonna da esempi":** supporta più trasformazioni di Data/ora, Matematica e Colonna indice.
-   **Miglioramenti alle prestazioni:** Excel consente di aprire cartelle di lavoro complesse in modo da elaborare formule con intervalli estesi, filtrare un gran numero di righe o copiare e incollare più velocemente.
-   **Inserimento di immagini online:** La nuova pagina di destinazione per selezionare immagini e informazioni sull'attribuzione è automaticamente inserita con l'immagine.
-   **Connettore Azure Data Lake Store:** Gli utenti possono ora importare dati da Azure Data Lake Store.
-   **Miglioramenti di "Aggiungi colonna da esempi":** Supporta suggerimenti, ulteriori operazioni su data/ora e trasformazioni aggiuntive.
-   **Scheda dei dati**: i pulsanti della barra multifunzione nella scheda dei dati sono stati riorganizzati in due nuovi gruppi: Visualizzazione e trasformazione dei dati e Query e connessioni.
-   **Condivisione delle query**: Esportare qualsiasi definizione query in un file ODC (Office Database Connection), quindi condividerlo nelle cartelle di lavoro o con altri utenti.
-   **Caricamento dei dati:** Caricare i dati da una query direttamente in Tabelle pivot o Grafici pivot senza dover salvare i dati nel modello di dati.
-   **Attività di un file condiviso:** selezionare il pulsante Attività nell'angolo superiore destro del file per visualizzare quando un file condiviso in OneDrive for Business o SharePoint è stato condiviso, modificato, rinominato o ripristinato.
-   **Collegamenti sicuri:** quando un utente fa clic su un collegamento, Office 365 Advanced Threat Protection (ATP) esamina il collegamento per verificare se è dannoso. Se il collegamento è ritenuto dannoso, l'utente viene reindirizzato a una pagina di avviso anziché all'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Funzionalità di importazione dei dati migliorata:** È possibile importare e creare facilmente dati da diverse origini. Gestire le query e le connessioni delle cartelle di lavoro con il riquadro laterale Query e collegamento e condividere le query con altri utenti tramite file ODC. [Ulteriori informazioni](https://support.office.com/article/ad78befd-eb1c-4ea7-a55d-79d1d67cf9b3)
-   **Modifiche nei file condivisi**: visualizzare l'autore delle modifiche apportate alle cartelle condivise e ripristinare le versioni precedenti. [Ulteriori informazioni](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)
-   **Selezione con Lazo tramite pulsante della penna:** utilizzare i pulsanti della penna digitale supportati per eseguire una selezione con Lazo dell'inchiostro senza accedere alla barra multifunzione.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8631](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8631): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8632](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8632): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale Excel si blocca quando si espande oppure si comprime una tabella pivot e le intestazioni della tabella pivot si spostano sullo schermo.
-   Consente di risolvere un problema a causa del quale le schede vengono ignorate durante il copia e incolla di testo delimitato da tabulazione da Word, impedendo quindi di incollare tale testo nelle colonne.
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando si apre la finestra di dialogo Pubblica come pagina Web.
-   Consente di risolvere un problema a causa del quale un aggiornamento dei dati ha esito negativo oppure Excel si arresta in modo anomalo quando si utilizzano i dati da un server SQL Server Analysis Services e le impostazioni locali di Excel e le impostazioni locali del server SQL Server Analysis Services sono diverse.
-   Consente di risolvere un problema a causa del quale vengono visualizzati degli errori quando si tenta di salvare le modifiche apportate ai documenti sincronizzati con il client OneDrive.
-   Consente di risolvere un problema a causa del quale non è possibile apportare modifiche in un punto qualsiasi in un foglio di lavoro quando è presente una Tabella pivot con campi nell'area filtro, ma non sono presenti campi in altre posizioni.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti delle funzionalità
-   **Miglioramenti dell'accessibilità:** è più facile leggere e modificare testo, tabelle, elenchi e immagini nei messaggi di posta elettronica quando si utilizza un'utilità per la lettura dello schermo.
-   **Configurazione di nuovi account:** impostare nuovi account con una nuova procedura guidata che richiede meno passaggi manuali.
-   **Finestra di dialogo Allega per link:** quando si allega un link tramite l'opzione Allega file sulla barra multifunzione, è possibile selezionare se aggiungerlo come link o come allegato. Se non si desidera visualizzare sempre questa finestra di dialogo, andare a File \> Opzioni \> Generale e specificare in che modo allegare i link in "Opzioni allegato".
-   **Supporto di allegati in locale:** I file di SharePoint Server in locale vengono visualizzati come file recenti in Messaggio \> Allega file, OneDrive for Business in locale e i siti del team di SharePoint sono visualizzati in Allega file \> Esplora percorsi Web e i file locali possono essere caricati nei siti di OneDrive for Business in locale.
-   **Classificazioni aziendali per gruppi:**  quando si crea o modifica un gruppo, è possibile assegnare un livello di classificazione commerciale definito dall'amministratore tenant, ad esempio Riservato, classificazione che viene poi visualizzata nell'intestazione del gruppo.
-   **Accesso guest ai gruppi di Office 365:** collaborare con utenti esterni all'organizzazione autorizzandoli ad accedere alle conversazioni dei gruppi, ai file, agli inviti al calendario e al blocco appunti dei gruppi. [Ulteriori informazioni](https://support.office.com/article/bfc7a840-868f-4fd6-a390-f347bf51aff6)
-   **Messaggi operativi:** gli sviluppatori possono creare messaggi per facilitare gli utenti a effettuare azioni rapide o semplici direttamente da Outlook, senza dover passare a un sito Web esterno o a un'app separata. [Ulteriori informazioni](https://dev.office.com/blogs/create-more-engaging-conversations-with-new-actionable-messages-updates-announced-at-microsoft-build)

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): le funzionalità di sicurezza di Microsoft Office Outlook ignorano la vulnerabilità
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilità della divulgazione delle informazioni relative a Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilità di danneggiamento della memoria di Microsoft Office Outlook

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale non è possibile configurare un account IMAP in Outlook.
-   Consente di risolvere un problema che causa un arresto anomalo intermittente quando si apre Outlook.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti delle funzionalità
-   **Inserimento di immagini online:** la nuova pagina di destinazione per selezionare immagini e informazioni sull'attribuzione è automaticamente inserita con l'immagine.
-   **Sottotitoli codificati per i video:** aggiungere sottotitoli codificati a un video per renderlo più accessibile. [Ulteriori informazioni](https://support.office.com/article/a16745e1-b3da-4428-b2a7-ff0c8b758d0b)
-   **Narrazione di una registrazione:** Includere video di se stessi durante il commento quando si effettua la registrazione di una presentazione. Le registrazioni possono includere animazioni, input penna, audio e video.
-   **Attività di un file condiviso:** selezionare il pulsante Attività nell'angolo superiore destro del file per visualizzare quando un file condiviso in OneDrive for Business o SharePoint è stato condiviso, modificato, rinominato o ripristinato.
-   **Creazione di testo alternativo:** un servizio basato su cloud genera automaticamente testo alternativo per le immagini di una presentazione.
-   **Collegamenti sicuri:** quando un utente fa clic su un collegamento, Office 365 Advanced Threat Protection (ATP) esamina il collegamento per verificare se è dannoso. Se il collegamento è ritenuto dannoso, l'utente viene reindirizzato a una pagina di avviso anziché all'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Miglioramenti per la progettazione:** suggerisce idee per progetti professionali per elenchi orientati all'azione.
-   **Modifiche nei file condivisi** Visualizzazione dell'autore delle modifiche apportate alle presentazioni condivise e ripristino delle versioni precedenti. [Ulteriori informazioni](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti della sicurezza
-   [CVE-2017-8742](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8742): vulnerabilità relativa all'esecuzione di codice remoto in PowerPoint
-   [CVE-2017-8743](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8743): vulnerabilità relativa all'esecuzione di codice remoto in PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale i caratteri definiti dall'utente finale (EUDC, End-User Defined Character) che sono collegati ai tipi di carattere non vengono visualizzati.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Project si arresta in modo anomalo quando si aprono determinati file da Project Online.
-   Consente di risolvere un problema a causa del quale l'inizio effettivo potrebbe essere erroneamente cancellato quando si imposta il lavoro rimanente.
-   Consente di risolvere un problema a causa del quale la data di inizio effettivo delle assegnazioni può mostrare dati diversi da quelli riportati dalla risorsa tramite la definizione dello stato in Project Web App.
-   Consente di risolvere un problema a causa del quale il lavoro effettivo potrebbe essere riprogrammato se la data di fine dell'attività viene modificata.
-   Consente di risolvere un problema a causa del quale se si copiano e si incollano campi Costo, i valori incollati potrebbero non corrispondere esattamente ai valori copiati per via di un problema di arrotondamento.
-   Consente di risolvere un problema a causa del quale i dati rapportati alla scala cronologica per le risorse preventivo non vengono copiati quando si salva da una linea di base a un'altra.
-   Consente di risolvere un problema a causa del quale il campo di stato non sempre viene calcolato correttamente per le attività di riepilogo.
-   Consente di risolvere un problema per il quale il lavoro effettivo viene erroneamente trasferito a una risorsa aziendale quando sostituisce una risorsa locale e il lavoro protetto è abilitato.
-   Consente di risolvere un problema per il quale Project si arresta in modo anomalo nel caso in cui si disponga di una tabella in cui la prima colonna, è Nome attività, la colonna è bloccata e si seleziona un'attività.
-   Consente di risolvere un problema per il quale è possibile assegnare la stessa risorsa più volte alla stessa attività attraverso la visualizzazione Gestione attività.
-   Consente di risolvere un problema in cui i valori dei campi personalizzati numerici potrebbero andare persi quando si aprono file XML.
-   Consente di risolvere un problema in cui il rientro delle attività di primo livello non si sincronizza correttamente da Project a un elenco attività di SharePoint.
-   Consente di risolvere un problema per il quale se si importano informazioni su attività, risorse o assegnazioni da una cartella di lavoro di Excel, i valori nel campo lavoro potrebbero essere ignorati.
-   Consente di risolvere un problema a causa del quale i valori di base rapportati alla scala cronologica non corrispondono ai valori iniziali quando si salva un progetto in formato di file XML.
-   Consente di risolvere un problema a causa del quale non è possibile aprire un progetto nel client di Project poiché il progetto in realtà non viene estratto.
-   Consente di risolvere un problema in modo che i file Project da un file server ad alta latenza vengano aperti più velocemente.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Aggiornamenti della sicurezza
-   [CVE-2017-8676](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8676): vulnerabilità di divulgazione di informazioni in Windows GDI+
-   [CVE-2017-8695](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8695): vulnerabilità della divulgazione delle informazioni relative a Graphics Component
-   [CVE-2017-8696](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8696): esecuzione di codice remoto del componente di Microsoft Graphics

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Consente di aggiungere una finestra di dialogo che spiega perché un utente non è in grado di accedere a una riunione quando determinate porte sono bloccate o gli IP non sono consentiti.
-   Consente di risolvere un problema a causa del quale i messaggi non letti nelle chat room permanenti sono contrassegnati come letti quando si fa clic sulle schede della chat.
-   Consente di risolvere un problema a causa del quale gli avvisi popup dei messaggi in arrivo vengono ricevuti con qualche secondo di ritardo.
-   Consente di risolvere un problema a causa del quale un contatto di Active Directory viene visualizzato come numero di telefono anziché come nome di contatto quando la sincronizzazione con Exchange è disabilitata.
-   Consente di risolvere un problema a causa del quale gli utenti con accesso anonimo vengono bloccati quando la federazione è disabilitata e l'accesso anonimo non è esplicitamente bloccato dall'organizzatore della riunione.
-   Consente di risolvere un problema a causa del quale il numero di invitati non viene visualizzato correttamente dall'organizzatore della riunione per le riunioni che superano il limite impostato.
-   Consente di risolvere un problema a causa del quale il numero di telefono non viene visualizzato nel messaggio popup sulle chiamate PSTN in ingresso.
-   Consente di risolvere un problema a causa del quale, quando si utilizza il tasto Elimina durante la ridenominazione di un elenco contatti, viene eliminato l'intero gruppo.
-   Consente di risolvere un problema a causa del quale la notifica di condivisione in una chat viene ignorata prima che la condivisione venga interrotta.
-   Consente di risolvere un problema a causa del quale la schermata di accesso è vuota per alcune lingue diverse dall'inglese.
-   Consente di risolvere un problema a causa del quale i caratteri diversi da quelli inglesi nelle chat e nella cronologia di chat appaiono confusi.
-   Possibilità di visualizzare il numero di telefono del chiamante per le chiamate in arrivo gestite dall'Operatore automatico aziendale, se il nome dell'utente non è noto.
-   Possibilità di aggiungere un'impostazione di accesso in banda che offre la limitazione "Tutti gli utenti (senza restrizioni)" come opzione per "Persone che non devono aspettare nella sala di attesa".
-   Possibilità di attivare o disattivare i video automatici per videochiamate P2P in VDIv2.
-   Viene risolto un problema a causa del quale numeri duplicati vengono visualizzati per i contatti nel menu a discesa della chiamata.
-   Viene risolto un problema a causa del quale i delegati vengono eliminati per gli utenti che passano da Skype for Business a Skype for Business Basic.
-   Viene risolto un problema a causa del quale l'impostazione "Risulta Invisibile" non viene visualizzata quando si utilizzano i criteri client "Attiva Risulta Invisibile" e "URL stato personalizzato".
-   Ampliato il pulsante per partecipare alla riunione per correggere il troncamento di alcune lingue localizzate.
-   Aumentare la diffusione dei messaggi di priorità alta in chat.
-   Aggiungere tipi di estensione di file per Office e Skype for Business all'elenco di indirizzi bloccati per il trasferimento di file consentiti.
-   Correzioni alla localizzazione negli inviti alle riunioni di Outlook per il testo del piè di pagina delle riunioni impostato in una lingua diversa dall'inglese.
-   Consente di risolvere un problema a causa del quale i nomi dei mittenti possono essere cambiati nelle conversazioni di più utenti.
-   Consente di risolvere un problema a causa del quale la finestra di conversazione vuota non viene visualizzata finché non si accede a una riunione.
-   Consente di risolvere un problema a causa del quale le informazioni del campo relativo al reparto in un biglietto da visita non vengono visualizzate nei risultati della ricerca se il campo del titolo è vuoto.
-   Consente di risolvere i problemi di accesso per gli utenti migrati da un ambiente locale a un ambiente online a causa di regole del firewall.
-   Aggiungere una nuova chiave del Registro di sistema DWORD per correggere un problema in cui, quando un utente accede al cliente su una rete esterna eseguendo LyncAutoD, il client reimposta la chiave del Registro di sistema OAuthUsed su false. Per risolvere il problema, impostare il valore su 1 per EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket in HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Lync\\\<SipID\>.

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti delle funzionalità
-   **Creazione di diagrammi dai dati in Excel:** consente di creare automaticamente un diagramma di flusso di base o un diagramma di flusso interfunzionale partendo dai dati in Excel con i nuovi modelli di Visualizzatore dati. [Ulteriori informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)
-   **Collegamenti sicuri:** quando un utente fa clic su un collegamento, Office 365 Advanced Threat Protection (ATP) esamina il collegamento per verificare se è dannoso. Se il collegamento è ritenuto dannoso, l'utente viene reindirizzato a una pagina di avviso anziché all'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)

### <a name="visio-non-security-updates"></a>Visio: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale i componenti aggiuntivi COM non ricevono eventi di apertura dei documenti, quando un file Visio viene aperto tramite doppio clic su un'icona o su un nome file.

### <a name="word-feature-updates"></a>Word: Aggiornamenti delle funzionalità
-   **Inserimento di immagini online:** la nuova pagina di destinazione per selezionare immagini e informazioni sull'attribuzione è automaticamente inserita con l'immagine.
-   **Creazione di testo alternativo:** un servizio basato su cloud genera automaticamente testo alternativo per le immagini di un documento.
-   **Attività di un file condiviso:** selezionare il pulsante Attività nell'angolo superiore destro del file per visualizzare quando un file condiviso in OneDrive for Business o SharePoint è stato condiviso, modificato, rinominato o ripristinato.
-   **Collegamenti sicuri:** quando un utente fa clic su un collegamento, Office 365 Advanced Threat Protection (ATP) esamina il collegamento per verificare se è dannoso. Se il collegamento è ritenuto dannoso, l'utente viene reindirizzato a una pagina di avviso anziché all'URL di destinazione originale. [Ulteriori informazioni](https://support.office.com/article/dd6a1fef-ec4a-4cf4-a25a-bb591c5811e3)
-   **Modifiche nei file condivisi:** Visualizzazione dell'autore delle modifiche apportate ai documenti condivisi e ripristino delle versioni precedenti. [Ulteriori informazioni](https://support.office.com/article/5c1e076f-a9c9-41b8-8ace-f77b9642e2c2)

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Word viene chiuso in modo imprevisto durante il caricamento del componente aggiuntivo Grammarly.
-   Consente di risolvere un problema a causa del quale, in determinate condizioni, Word si arresta in modo anomalo durante il tentativo di recupero di file basati su cloud.
-   Consente di risolvere un problema a causa del quale non è possibile ruotare le forme all'interno dell'area di disegno.
-   Consente di risolvere un problema a causa del quale, durante la digitazione in coreano, consonanti e vocali vengono separate erroneamente.
-   Salvataggio di un documento come un PDF salva il documento in versione 1.7 PDF.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-8630](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8630): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8744](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8744): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema che impedisce alla finestra di dialogo Novità di essere visualizzata.
-   Consente di risolvere un problema a causa del quale le azioni di clic sulla scheda di disegno causa l'arresto anomalo dell'applicazione per alcuni utenti.
-   Consente di risolvere un problema a causa del quale il passaggio del mouse su un controllo comune con descrizione comando causa l'arresto anomalo dell'applicazione.
-   Consente di risolvere un problema a causa del quale viene visualizzato un messaggio di errore di licenza quando si utilizzano i controlli comuni.
-   Consente di risolvere un problema relativo al modo in cui vengono firmati alcuni file. Tale modalità di firma fa sì che i programmi antivirus contrassegnino i file e i problemi di protezione o accesso ai dati in Windows Information Protection (WIP).
-   Aggiungere supporto per consentire agli utenti che usano le versioni a 64 bit di Office di aprire i file macro che contengono i controlli mscomctl.ocx.
-   Migliorare l'accessibilità dei controlli utilizzati in mscomctl.ocx.
-   Consente di risolvere un problema a causa del quale i comandi della barra multifunzione o delle finestre di dialogo di personalizzazione della barra di accesso rapido sono assenti.



## <a name="version-1705-august-8"></a>Versione 1705:8 agosto
*Versione 1705 (Build 8201.2171)*

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema relativo alle operazioni di trascinamento della barra di scorrimento in modo che si sposti in un elenco di messaggi.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema relativo al modo in cui vengono firmati alcuni file. Tale modalità di firma fa sì che i programmi antivirus contrassegnino i file e i problemi di protezione o accesso ai dati in Windows Information Protection (WIP).
-   Consente di risolvere un problema che impedisce alla finestra di dialogo Novità di essere visualizzata.



## <a name="version-1705-july-27"></a>Versione 1705:27 luglio
*Versione 1705 (Build 8201.2158)*

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale vengono visualizzati degli errori quando si tenta di salvare le modifiche apportate ai documenti sincronizzati con il client OneDrive.
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando si aggiungono dati di un foglio di lavoro a un modello dati e il tema a contrasto elevato è impostato su nero.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-8571](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8571): le funzionalità di sicurezza di Microsoft Office Outlook ignorano la vulnerabilità
-   [CVE-2017-8572](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8572): vulnerabilità della divulgazione delle informazioni relative a Microsoft Office Outlook
-   [CVE-2017-8663](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8663): vulnerabilità di danneggiamento della memoria di Microsoft Office Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale si verifica un errore di unione quando si aggiunge una forma dopo che un altro utente ha modificato il layout.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale, durante la digitazione in coreano, consonanti e vocali vengono separate erroneamente.
-   Consente di risolvere un problema a causa del quale l'indirizzo di recapito sulle buste viene stampato troppo vicino al bordo sinistro.



## <a name="version-1705-july-13"></a>Versione 1705:13 luglio
*Versione 1705 (Build 8201.2136)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2017-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8501): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8502): vulnerabilità di danneggiamento della memoria di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui Excel si arresta in modo anomalo in caso di cartelle di lavoro contenenti collegamenti esterni.
-   Consente di risolvere un problema per il quale incollando celle da Excel in Word vengono visualizzati zero nelle celle, anche se l'impostazione "Visualizza zero nelle celle con valore zero" non è selezionata.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui i valori selezionati per una grafico o tabella non sono visibili nel riquadro tabella/grafico.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per il quale una finestra di conversazione non è visibile in background quando si partecipa a una riunione e all'utente viene visualizzata la finestra di dialogo per aggiungere dispositivi audio.
-   Consente di risolvere un problema per il quale il collegamento della riunione di Outlook non trasmette sempre correttamente l'URI interno.
-   Ampliato il pulsante per partecipare alla riunione per correggere il troncamento di alcune lingue localizzate.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema per il quale le tabelle non vengono visualizzate correttamente dopo determinate azioni.
-   Consente di risolvere un problema per il quale le modifiche a citazioni a volte vengono visualizzate come una singola azione di annullamento invece di singole azioni consecutive.
-   Consente di risolvere un problema in cui l'annullamento viene disabilitato dopo determinate azioni.
-   Consente di risolvere un problema per impedire la perdita di alcuni dati dopo determinate azioni di annullamento.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-8570](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8570): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema che causa l'esito negativo degli aggiornamenti non presidiati di Office 2013 a Office 2016 quando si utilizza Configuration Manager.
-   Consente di risolvere un problema per il quale i componenti aggiuntivi legacy distribuiti dall'archivio attraverso il catalogo aziendale non vengono caricati.



## <a name="version-1705-june-13"></a>Versione 1705:13 giugno
*Versione 1705 (Build 8201.2102)*

### <a name="access-feature-updates"></a>Access: aggiornamenti delle funzionalità
-   **What’s New dialog:** A dialog box that highlights new Access features appears when Access is opened after Access is updated with new features. The dialog box is also available by going to File \> Account \> What’s New.
-   **Supporto per numero grande (bigint):** consente di utilizzare il tipo di dati Numero grande nelle tabelle di Access per fare calcoli con numeri elevati e per collegarsi a o importare da database esterni che sfruttano un tipo di dati equivalente, come bigint in SQL Server. [Ulteriori informazioni](https://blogs.office.com/2017/03/06/new-in-access-2016-large-number-bigint-support/)

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti delle funzionalità
-   **Supporto per Windows Information Protection (WIP):**    Excel è ora un'app illuminata e può distinguere tra dati aziendali e personali, determinando in modo corretto quali proteggere, in base ai criteri configurati.   [Altre informazioni](https://aka.ms/wiptechnet)
-   **Get & Transform improvement:** In the Query Editor, create a new column by providing sample values. As you type, Excel detects the required transformations and shows a preview of the new column.
-   **Inserire collegamenti recenti:** È possibile allegare facilmente i collegamenti ipertestuali ai file o siti Web basati sul cloud recenti e creare nomi visualizzati significativi per gli utenti che utilizzano utilità per la lettura dello schermo. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Personalizzare il layout di tabella pivot predefinito:** Configurare una tabella pivot secondo le proprie preferenze e iniziare con il layout personalizzato ogni volta che si crea una nuova tabella pivot. [Ulteriori informazioni](https://support.office.com/article/efd8569c-f07a-43c1-9db2-4f2912a0f94e)
-   **Miglioramenti di visualizzazione e trasformazione:** Gli utenti possono creare nuove colonne per esempio e dividere le colonne delle tabelle in righe. Specificare parametri per SAP HANA e raggruppare i dati sono operazioni ora più semplici.
-   **Distribuzione centralizzata dei componenti aggiuntivi**: gli amministratori possono distribuire e aggiornare i componenti aggiuntivi per utenti o gruppi dall'interfaccia di amministrazione di Office 365. [Ulteriori informazioni](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Personalizzazione della barra di accesso rapido:** è possibile aggiungere le icone per indice inferiore e indice superiore alla barra di accesso rapido.
-   **Miglioramenti di visualizzazione e trasformazione:** rilevamento automatico del carattere di delimitazione durante la separazione di colonne mediante l'editor di query; selezionare quale file di esempio utilizzare con Combina binari e specificare la raccolta di pacchetti cui connettersi quando si utilizza il connettore per DB2.
-   **Tipo di carattere Dubai:** gruppo di caratteri che supporta sia le lingue dell'Europa occidentale sia la maggior parte delle lingue che usano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione dello sfondo:** consente di rimuovere un'immagine di sfondo con uno strumento di disegno a mano libera.
-   **Miglioramenti di visualizzazione e trasformazione:** consente di utilizzare "Selezione tabelle correlate" nella finestra di dialogo dello strumento di spostamento con i connettori ODCB e OLEDB, di unire più file direttamente dalla finestra di dialogo Anteprima dati della cartella e di usare una nuova opzione del menu di scelta rapida nella finestra Editor query per inserire nuovi passaggi nelle query esistenti.
-   **Usare una penna per selezionare e modificare gli oggetti:** Catturare i punti di controllo dell'oggetto con una penna digitale per ridimensionare, ruotare, spostare e altro.
-   **Grafico mappa:** Confrontare i valori e visualizzare le categorie in aree geografiche diverse. [Ulteriori informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)
-   **Immagini SVG:** Inserire e modificare SVG (Scalable Vector Graphics) nelle cartelle di lavoro. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**   utilizzare le icone di una raccolta standard di file SVG (Scalable Vector Graphics) inserendo le \> icone \> delle illustrazioni. [Ulteriori informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salvare in cartelle recenti:** Salvare una cartella di lavoro in una cartella usata di recente tramite la scheda Recenti quando si accede a File \> Salva con nome.
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, Assistente vocale e altri strumenti di Assistive Technology per leggere e modificare le cartelle di lavoro. [Ulteriori informazioni](https://support.office.com/article/51fcb17a-b15b-4b13-ae04-d4f38ece3f78)

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Aggiornamento della sicurezza per Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale la password di protezione dei fogli Excel non viene visualizzata quando la si applica a livello di programmazione per cartelle di lavoro create in Excel 2010 o versioni precedenti.
-   Consente di risolvere un problema a causa del quale Unisci e centra non funziona nei fogli di lavoro raggruppati.
-   Consente di risolvere un problema a causa del quale le nuove funzioni introdotto dopo la pubblicazione di Office 2016 (ad esempio, TEXTJOIN, CONCAT, IFS, MAXIFS e MINIFS) sono mancanti.
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando l'utente prova ad applicare autorizzazioni a livello di cella.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di grandi dimensioni su OneDrive for Business. A causa dell'errore, il file si blocca e l'utente non è in grado di modificarlo finché non chiude e riapre Excel.
-   Consente di risolvere un problema a causa del quale una nuova finestra viene visualizzata come disattivata quando è aperta una cartella di lavoro xls.
-   Consente di risolvere un problema a causa del quale Excel potrebbe arrestarsi in modo anomalo quando si inseriscono i collegamenti ipertestuali.
-   Consente di risolvere un problema a causa del quale Excel non funziona in modo corretto quando si aggiungono mapping XML.
-   Consente di risolvere un problema a causa del quale il pulsante di comando per un componente aggiuntivo non funziona dopo l'aggiornamento del componente aggiuntivo o dopo la rimozione o il download del componente aggiuntivo dall'Office Store.
-   Consente di risolvere un problema a causa del quale Excel potrebbe arrestarsi in modo anomalo quando si modificano fogli DDL tramite VBA.
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando si seleziona una casella combinata del modulo su un foglio grafico.

### <a name="onenote-feature-updates"></a>OneNote: Aggiornamenti delle funzionalità
-   **Supporto per Windows Information Protection (WIP):** OneNote è ora un'app con riconoscimento e distingue tra dati aziendali e personali. In questo modo, riesce a determinare in modo corretto quali sono quelli da proteggere, sulla base dei criteri configurati. [Ulteriori informazioni](https://aka.ms/wiptechnet)

### <a name="onenote-non-security-updates"></a>OneNote: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale l'area di disegno di OneNote nasconde i contenuti oppure si aggiorna quando vengono visualizzati molti paragrafi.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti delle funzionalità
-   **Supporto per Windows Information Protection (WIP):**    Outlook è ora un'app illuminata e può distinguere tra dati aziendali e personali, determinando in modo corretto quali proteggere, in base ai criteri configurati.   [Altre informazioni](https://aka.ms/wiptechnet)
-   **Inserire collegamenti recenti:** È possibile allegare i collegamenti ipertestuali ai file o siti Web basati sul cloud recenti e creare nomi visualizzati significativi per gli utenti che utilizzano utilità per la lettura dello schermo. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Tipo di carattere Dubai:** gruppo di caratteri che supporta sia le lingue dell'Europa occidentale sia la maggior parte delle lingue che usano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione dello sfondo:** consente di rimuovere un'immagine di sfondo con uno strumento di disegno a mano libera.
-   **Controllo dell'accesso ai file condivisi:** Outlook indica in anticipo all'utente se i destinatari non sono in grado di accedere a un file di OneDrive o SharePoint allegato e suggerisce una procedura di risoluzione del problema.
-   **Impostazione delle autorizzazioni sugli allegati:** per gli allegati di OneDrive o SharePoint, l'utente può impostare se i destinatari, interni o esterni all'organizzazione, dispongono di autorizzazioni di lettura o modifica per l'allegato.
-   **Riquadro attività che è possibile aggiungere:** Tenere aperto il riquadro attività del componente aggiuntivo mentre si passa da un messaggio all'altro nella cassetta postale. [Ulteriori informazioni](https://blogs.msdn.microsoft.com/exchangedev/2017/01/26/pinnable-taskpane-in-outlook-2016/)
-   **Immagini SVG:** Inserire e modificare SVG (Scalable Vector Graphics) nelle e-mail. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**   utilizzare le icone di una raccolta standard di file SVG (Scalable Vector Graphics) inserendo le \> icone \> delle illustrazioni.   [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): le funzionalità di sicurezza di Microsoft Office ignorano la vulnerabilità
-   [CVE-2017-8506](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8506): esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-8507](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8507): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-8508](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8508): le funzionalità di sicurezza di Microsoft Office ignorano la vulnerabilità

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale il pannello di navigazione di Outlook interrompe il rendering quando il computer ha memoria insufficiente.
-   La larghezza dell'allegato aumenta in base al nome del file e alle informazioni relative alle autorizzazioni.
-   Consente di risolvere un problema a causa del quale l'utente non riesce a cercare i file PST.
-   Consente di risolvere un problema a causa del quale l'utente visualizza un nuovo tipo di archivio "Microsoft Exchange" nella finestra di dialogo "Nuovo file di dati di Outlook", ma la selezione di tale archivio rende inutilizzabile il profilo utente.
-   Consente di risolvere un problema a causa del quale un'immagine in un messaggio è oscurata quando viene inviata da un computer con valori DPI alti.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti delle funzionalità
-   **Supporto per Windows Information Protection (WIP):**    PowerPoint è ora un'app illuminata e può distinguere tra dati aziendali e personali, determinando in modo corretto quali proteggere, in base ai criteri configurati.   [Altre informazioni](https://aka.ms/wiptechnet)
-   **Inserire collegamenti recenti:** È possibile allegare i collegamenti ipertestuali ai file o siti Web basati sul cloud recenti e creare nomi visualizzati significativi per gli utenti che utilizzano utilità per la lettura dello schermo. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Distribuzione centralizzata dei componenti aggiuntivi**: gli amministratori possono distribuire e aggiornare i componenti aggiuntivi per utenti o gruppi dall'interfaccia di amministrazione di Office 365. [Ulteriori informazioni](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Tipo di carattere Dubai:** gruppo di caratteri che supporta sia le lingue dell'Europa occidentale sia la maggior parte delle lingue che usano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione dello sfondo:** consente di rimuovere un'immagine di sfondo con uno strumento di disegno a mano libera.
-   **Immagini SVG:** Inserire e modificare SVG (Scalable Vector Graphics) nelle presentazioni. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**   utilizzare le icone di una raccolta standard di file SVG (Scalable Vector Graphics) inserendo le \> icone \> delle illustrazioni. [Ulteriori informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Digitazione in tempo reale durante la creazione condivisa:** Vedere dove gli altri stanno lavorando nella presentazione e visualizzare le modifiche durante la digitazione. [Ulteriori informazioni](https://support.office.com/article/0c30ee3f-8674-4f0e-97be-89cf2892a34d)
-   **Salvare in cartelle recenti:** Salvare una presentazione in una cartella usata di recente tramite la scheda Recenti quando si accede a File \> Salva con nome.
-   **Creare forme input penna precise:** Trascinare la gomma per segmenti al fine di rimuovere bit in eccesso dell'input penna, a destra fino alla riga più vicina.
-   **Selezionare e modificare gli oggetti con una penna:** Utilizzare una penna digitale per spostare, ridimensionare oppure ruotare gli oggetti tramite gli appositi punti di controllo. In alternativa, utilizzare i pulsanti della penna per eseguire selezione con lazo dell'inchiostro.
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, Assistente vocale e altri strumenti di Assistive Technology per leggere e modificare le presentazioni. [Ulteriori informazioni](https://support.office.com/article/3fce93f5-9ca8-42a6-bc1f-776749f6e32e)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale PowerPoint si arresta in modo anomalo quando l'utente è nel riquadro Idee per progetti se il file mfplat.dll non è installato nel computer.
-   Consente di risolvere un problema a causa del quale il pulsante di comando per un componente aggiuntivo non funziona dopo l'aggiornamento del componente aggiuntivo o dopo la rimozione o il download del componente aggiuntivo dall'Office Store.

### <a name="project-feature-updates"></a>Project: Aggiornamenti delle funzionalità
-   **Elenco a discesa rapido per l'impostazione di predecessori:** Usare il menu a discesa del diagramma di Gantt per scegliere quali predecessori o successori collegare a un'attività.
-   **Nome Riepilogo attività:**   campo attività di sola lettura in cui viene visualizzato il nome dell'attività di riepilogo dell'attività.  

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza
-   Consente di correggere la finestra di dialogo Crea sito di progetto che visualizza la posizione corretta del sito ora che in Project Online ogni Enterprise Project Template (EPT) ha il proprio URL per i siti di progetto.
-   Consente di risolvere un problema a causa del quale l'evento VBA BeforeClose viene attivato prima del prompt Salva e non si dispone di un modo programmatico per stabilire la risposta dell'utente al prompt di salvataggio.
-   Consente di risolvere un problema a causa del quale % fisica completamento non esegue il roll up correttamente per le attività che iniziano dopo la data dello stato del progetto.
-   Consente di risolvere un problema a causa del quale, quando una risorsa costo e una risorsa lavoro vengono assegnate alla stessa attività, potrebbe non essere possibile modificare il responsabile dello stato dell'attività.
-   Consente di risolvere un problema a causa del quale per alcuni progetti, il livellamento dell'intero progetto può creare un ciclo infinito.
-   Consente di risolvere un problema a causa del quale le date di inizio e fine dell'attività non vengono sincronizzate correttamente con un elenco di attività di SharePoint in presenza di determinate impostazioni internazionali spagnole.
-   Consente di risolvere un problema a causa del quale se si avvia il processo di approvazione dello stato dal client del progetto, tale processo potrebbe non avere mai fine, lasciando il progetto in uno stato inutilizzabile.
-   Consente di risolvere un problema a causa del quale nell'anteprima di stampa non vengono visualizzati correttamente i nomi delle attività in presenza di parole inglesi o cinesi.
-   Consente di risolvere un problema a causa del quale la copia della sequenza temporale in PowerPoint come forme individuali ha esito negativo.
-   Consente di risolvere un problema a causa del quale la finestra di dialogo "Collegamenti tra progetti" mostra inaspettatamente il valore "File non trovato".
-   Consente di risolvere un problema a causa del quale vengono visualizzati risultati non uniformi quando si assegnano risorse con Unità massima pari a 0.
-   Consente di risolvere un problema a causa del quale la data di inizio di un'attività viene ripristinata su "Al più presto" quando si elimina la data di inizio di un'assegnazione, ignorando elementi come i precedenti. In questo caso, le assegnazioni vengono suddivise.
-   Consente di risolvere un problema che si verifica quando si apre un file da SharePoint usando il menu Recenti. In questo caso, il progetto viene estratto automaticamente anche se l'impostazione "Estrazione obbligatoria dei documenti prima della modifica" è attiva.
-   Consente di risolvere un problema a causa del quale Project si arresta in modo anomalo se l'utente va direttamente all'applicazione Project Profiles.
-   Consente di risolvere un problema a causa del quale le attività pianificate manualmente non vengono aggiornate correttamente per gli utenti che eseguono l'aggiornamento da Project 2013.
-   Consente di risolvere un problema che causa l'arresto anomalo di Project, quando si apre un progetto da un elenco attività di SharePoint. L'arresto anomalo si verifica non appena Project avvia il processo di sincronizzazione dell'attività.
-   Consente di risolvere un problema a causa del quale Project si arresta in modo anomalo quando si passa al Build Team.
-   Consente di risolvere un problema a causa del quale le informazioni iniziali vengono perse durante il salvataggio di un progetto.
-   Consente di risolvere un problema a causa del quale le stampe sono di difficile lettura per i piani di progetto di grandi dimensioni.
-   Consente di risolvere un problema a causa del quale i progetti modificati in Project Web App non mostrano i valori corretti per i campi formula.
-   Consente di risolvere un problema a causa del quale le informazioni per i campi personalizzati dell'organizzazione delle risorse non vengono salvate correttamente per un piano di progetto.
-   Consente di risolvere un problema a causa del quale l'aggiornamento delle informazioni sulla % di completamento del lavoro di un'attività permette di aggiornare le informazioni sulla % di completamento di un'attività.
-   Consente di risolvere un problema a causa del quale la proprietà del progetto viene modificata quando il progetto viene salvato.
-   Consente di risolvere un problema a causa del quale CPI viene calcolato in modo errato per un'attività di riepilogo.
-   Consente di risolvere un problema a causa del quale le attività di copia e incolla spostano i dati iniziali e i dati vengono salvati, anche se l'utente non è autorizzato a salvare i dati iniziali protetti.
-   Consente di risolvere un problema a causa del quale l'importazione di dati da Excel genera informazioni sulla data non corrette per attività e assegnazioni.
-   Consente di risolvere un problema a causa del quale, dopo aver aperto un report, Project si arresta in modo anomalo quando si chiude.
-   Consente di risolvere un problema a causa del quale Project smette di funzionare durante il salvataggio di un progetto in cui un elenco personalizzato contiene impostazioni di convalida.
-   Consente di risolvere un problema a causa del quale l'immissione del carattere "\>" nella colonna Test nella finestra di dialogo Definizione di filtro non viene interpretata in modo corretto, ovvero come significato "è maggiore di".
-   Consente di risolvere un problema con la visualizzazione delle linee di avanzamento in relazione a "Previsione".
-   Consente di risolvere un problema a causa del quale l'elenco a discesa dei nomi di campo non viene visualizzato quando si personalizzano i filtri.
-   Consente di risolvere un problema a causa del quale le anteprime sullo stile della barra non vengono visualizzate nella relativa finestra di dialogo.

### <a name="publisher-non-security-updates"></a>Publisher: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale in Publisher non vengono visualizzate le immagini CMYK TIF.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Aggiornamenti delle funzionalità
-   **Inserimento di collegamenti:** Aggiungere un collegamento nei messaggi istantanei e nelle chat di gruppo e fornire testo descrittivo per il collegamento anziché l'intero URL.
-   **Screen sharing notification:** A notification displays in the conversation window when you’re sharing a screen in an IM conversation or when screen sharing continues after you leave a meeting. The notification reminds you that you are still sharing your screen and makes it easy to stop sharing by using the “Stop Sharing” button.
-   **Windows Information Protection (WIP) support:** Skype for Business is now supported as a WIP-work only app.By adding Skype to your allowed apps list, it indicates to Windows that it does not handle personal data.Windows proteggerà i dati per conto di Skype for business.   [Altre informazioni](https://aka.ms/wiptechnet)
-   **Opzione di reimpostazione della password:** un collegamento a un pulsante di ripristino viene visualizzato nella finestra di accesso quando un utente non riesce ad accedere almeno una volta.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS17-013](https://technet.microsoft.com/library/security/ms17-013): aggiornamento della sicurezza per Microsoft Graphics Component (4013075)
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0283](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0283): vulnerabilità relativa all'esecuzione di codice remoto in Windows Uniscribe
-   [CVE-2017-8550](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8550): vulnerabilità relativa all'esecuzione di codice remoto in Skype for Business

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Change message for attempted calls to users with audio disabled by policy from "Cannot complete the call" to "Cannot call because an IT administrator has restricted audio. Try using instant messaging or email instead and ask to check with their IT administrator."
-   Aggiungere un collegamento ipertestuale "PIN di accesso dimenticato?" agli inviti alle riunioni di utenti abilitati ai Servizi di conferenza PSTN per Skype for Business Online.
-   Consentire di partecipare alle riunioni dei team da Skype for Business Online.
-   Modificare il volume della sessione dell'altoparlante dal 40% al 75%.
-   Consentire il ridimensionamento dell'elenco delle schede a una larghezza minima inferiore.
-   Aggiornare i tasti di scelta rapida in modo che corrispondano all'ordinamento delle schede.
-   Consente di correggere la direzione errata del testo ebraico durante l'invio da un dispositivo mobile.
-   Consente di risolvere un problema con le informazioni visualizzate da un'utilità per la lettura dello schermo per la funzionalità Presenta desktop/Concedi controllo.
-   Mostrare le stanze aperte in aggiunta a quelle che si seguono negli elenchi Seleziona stanza.
-   Aggiungere la possibilità di disattivare la funzione VoIP quando l'app RCC personalizzata è attiva.
-   Modificare lo slogan offline per la messaggistica istantanea in "Prova l'app mobile Skype for Business".
-   Consente di risolvere un problema a causa del quale la finestra di una conversazione accettata automaticamente si apre come una finestra normale invece di ridursi a icona e nasconde in modo imprevisto le altre finestre.
-   Consente di risolvere un problema relativo all'utilizzo di un'utilità per la lettura dello schermo nella finestra di dialogo Opzioni riunione Skype.
-   Consente di risolvere un problema a causa del quale il primo messaggio di un invito non viene visualizzato nell'e-mail Conversazione non effettuata.
-   Consente di risolvere un problema a causa del quale i numeri digitati vengono visualizzati quando si crea l'invito a una riunione da Outlook utilizzando il pulsante Nuova riunione Skype.
-   Consente di risolvere un problema a causa del quale, quando viene visualizzata una barra di scorrimento, tutte le conversazioni della cronologia di messaggistica istantanea non vengono selezionate se si usa la combinazione CTRL+A.
-   Consente di risolvere un problema a causa del quale il testo di output potrebbe non avere lo stesso formato quando si utilizza il cmdlet Export-CsArchivingData.
-   Consente di risolvere un problema a causa del quale l'organizzatore di una riunione non riesce a vedere il video dei partecipanti in remoto quando usa Riunione immediata con 3 o più partecipanti.
-   Consente di risolvere un problema a causa del quale la prima riga dell'elenco dei partecipanti alla riunione è vuota quando un utente fa clic con il pulsante destro del mouse sul nome di un altro utente nell'elenco di partecipanti.
-   Consente di risolvere un problema a causa del quale gli utenti non possono accedere quando passano dall'esterno all'interno di una rete aziendale.
-   Consente di risolvere un problema a causa del quale l'area della chat non si chiude quando si passa dalla messaggistica istantanea ai file audio in Consultative Transfer.
-   Consente di risolvere un problema a causa del quale i nomi vengono troncati nelle notifiche di tipo avviso popup quando è in uso la chiamata simultanea di due endpoint.
-   Consente di risolvere un problema a causa del quale il nome file viene troncato nelle notifiche di condivisione dei file.
-   Consente di aggiungere le descrizioni dei comandi per i pulsanti Torna alla chiamata e di trasferimento.
-   Consente di rendere il tempo trascorso in attesa nella finestra del trasferimento di consulenza disponibile per le utilità per la lettura dello schermo, come Narrator.
-   Consente di aggiungere la possibilità di selezionare la messaggistica istantanea o le chiamate come preferenza predefinita per il trasferimento di consulenza.
-   Consente di aggiungere la possibilità, quando si esegue un trasferimento di consulenza, di fare clic con il pulsante destro del mouse sul pulsante "Trasferimento" per visualizzare un elenco di numeri di telefono per il contatto.
-   Consente di migliorare un messaggio di errore generale per rendere chiaro che il problema consiste nel fatto che l'utente dispone di una licenza non valida o che non ha nessuna licenza.
-   Consente di risolvere un problema a causa del quale non tutti i contatti vengono visualizzati nel titolo della finestra della conversazione quando un utente avvia una conversazione con un contatto e quindi aggiunge un altro contatto.
-   Consente di risolvere un problema a causa del quale l'assistente vocale non legge la seconda riga delle notifiche.
-   Consente di risolvere un problema a causa del quale le chiamate vengono trasferite a VOIP anziché al numero consultato.
-   Consente di risolvere un problema a causa del quale l'assistente vocale annuncia informazioni non corrette quando l'utente si sposta nella finestra del contenuto.
-   Consente di risolvere un problema a causa del quale i nomi di autore e modificatore non vengono visualizzati quando si passa il puntatore su un'annotazione su una lavagna

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti delle funzionalità
-   **Trovare stencil di terze parti:** Cercare stencil di terze parti forniti dai provider di contenuti selezionato.
-   **Frammenti di diapositiva:** consente di creare frammenti di un disegno di Visio ed esportarli come diapositive di PowerPoint. [Ulteriori informazioni](https://support.office.com/article/e7da404b-4208-49d1-9518-6fe1a4723657)

### <a name="word-feature-updates"></a>Word: Aggiornamenti delle funzionalità
-   **Supporto per Windows Information Protection (WIP):**    Word è ora un'app illuminata e può distinguere tra dati aziendali e personali, determinando correttamente quali proteggere, in base ai criteri configurati.   [Altre informazioni](https://aka.ms/wiptechnet)
-   **Inserire collegamenti recenti:** È possibile allegare i collegamenti ipertestuali ai file o siti Web basati sul cloud recenti e creare nomi visualizzati significativi per gli utenti che utilizzano utilità per la lettura dello schermo. [Ulteriori informazioni](https://support.office.com/article/002684c4-bf06-422b-821f-b4ef84fdb0e3)
-   **Distribuzione centralizzata dei componenti**aggiuntivi: gli amministratori possono distribuire e aggiornare i componenti aggiuntivi agli utenti o ai gruppi dall'interfaccia di amministrazione di Office 365.   [Altre informazioni](https://dev.office.com/docs/add-ins/publish/centralized-deployment)
-   **Tipo di carattere Dubai:** gruppo di caratteri che supporta sia le lingue dell'Europa occidentale sia la maggior parte delle lingue che usano l'alfabeto arabo. [Ulteriori informazioni](https://support.office.com/article/c862df16-ae0d-46d9-b117-aa3f41f9706e)
-   **Rimozione dello sfondo:** consente di rimuovere un'immagine di sfondo con uno strumento di disegno a mano libera.
-   **Affiancato:** Consente di esplorare le pagine in visualizzazione Layout di stampa scorrendo tra loro in modalità affiancata, come se si trattasse di una pila di carta. [Ulteriori informazioni](https://support.office.com/article/21bfd0ff-0e1f-4c43-b188-8b36dfe6dcf4)
-   **Usare una penna per selezionare e modificare gli oggetti:** Catturare i punti di controllo dell'oggetto con una penna digitale per ridimensionare, ruotare, spostare e altro.
-   **Immagini SVG:** Inserire e modificare SVG (Scalable Vector Graphics) nei documenti. [Ulteriori informazioni](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)
-   **Inserire icone:**   utilizzare le icone di una raccolta standard di file SVG (Scalable Vector Graphics) inserendo le \> icone \> delle illustrazioni.   [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
-   **Salvare in cartelle recenti:** Salvare un documento in una cartella usata di recente tramite la scheda Recenti quando si accede a File \> Salva con nome.
-   **Lettura migliorata con strumenti di apprendimento:** Nuovi comandi nelle competenze di lettura boost della Modalità di lettura modificando testo spaziatura, mostrando le interruzioni di pagina tra sillabe ed evidenziando ogni parola del documento letto ad alta voce. [Ulteriori informazioni](https://support.office.com/article/29efa413-e2da-4cac-b2a5-2defc6d34fd9)
-   **Identificazione delle forme:** consente di trasformare automaticamente i disegni in forme utilizzando Disegno \> Converti in forma. [Ulteriori informazioni](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Aggiornamento della sicurezza per Microsoft Office (3217868)
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0292](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0292): vulnerabilità relativa all'esecuzione di codice remoto in Windows PDF 
-   [CVE-2017-8509](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8509): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office  

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale l'utente non riesce a cercare i file PST.
-   Consente di risolvere un problema a causa del quale l'utente visualizza un nuovo tipo di archivio "Microsoft Exchange" nella finestra di dialogo "Nuovo file di dati di Outlook", ma la selezione di tale archivio rende inutilizzabile il profilo utente.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): vulnerabilità relativa all'esecuzione in codice remoto con API Windows in Microsoft Office/WordPad
-   [CVE-2017-0260](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0260): esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-8510](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8510): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-8512](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-8512): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office



## <a name="version-1701-may-9"></a>Versione 1701:9 maggio
*Versione 1701 (Build 7766.2084)*

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale gli utenti visualizzano a intermittenza che la selezione dei messaggi all'interno dell'elenco salta quando si eliminano i messaggi.
-   Consente di risolvere un problema che causa arresti in modo anomalo intermittenti.
-   Aggiungere la chiave del Registro di sistema HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableSupportBackstage per consentire agli amministratori di nascondere la scelta Supporto nella scheda File.
-   Aggiungere la chiave del Registro di sistema HKEY\_CURRENT\_USER\\Software\\Microsoft\\Office\\16.0\\Outlook\\Options\\General\\DisableOutlookFeedbackFeatures per consentire agli amministratori di disattivare le opzioni "Feedback Outlook 2016" e "Blog di Outlook" in File \> Feedback.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Aggiornamenti della sicurezza
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale la finestra di una conversazione accettata automaticamente si apre come una finestra normale invece di ridursi a icona e nasconde in modo imprevisto le altre finestre.

### <a name="word-security-updates"></a>Word: Aggiornamenti della sicurezza
-   [CVE-2017-0254](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0254): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza
-   [CVE-2017-0261](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0261): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0262](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0262): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2017-0281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office



## <a name="version-1701-april-11"></a>Versione 1701:11 aprile
* Versione 1701 (Build 7766.2076)*

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale una nuova finestra viene visualizzata come disattivata quando è aperta una cartella di lavoro xls.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-0106](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0106): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2017-0204](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0204): le funzionalità di sicurezza di Microsoft Office ignorano la vulnerabilità

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale l'utente visualizza un nuovo tipo di archivio "Microsoft Exchange" nella finestra di dialogo "Nuovo file di dati di Outlook", ma la selezione di tale archivio rende inutilizzabile il profilo utente.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale si verifica un errore d'immagine mancante quando l'utente seleziona "Salva con nome" e sceglie un percorso alternativo per un file PowerPoint che è salvato su un dispositivo rimovibile, ad esempio, una chiavetta USB.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale gli utenti non possono accedere quando passano dall'esterno all'interno di una rete aziendale.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-0199](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-0199): vulnerabilità relativa all'esecuzione in codice remoto con API Windows in Microsoft Office/WordPad



## <a name="version-1701-march-14"></a>Versione 1701:14 marzo
*Versione 1701 (Build 7766.2071)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale i riquadri a comparsa del menu non possono essere ignorati.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Aggiornamento della sicurezza per Microsoft Office (3217868)

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Excel potrebbe arrestarsi in modo anomalo quando si inseriscono i collegamenti ipertestuali.
-   Consente di risolvere un problema a causa del quale Excel non funziona in modo corretto quando si aggiungono mapping XML.
-   Consente di risolvere un problema a causa del quale il pulsante di comando per un componente aggiuntivo non funziona dopo l'aggiornamento del componente aggiuntivo o dopo la rimozione o il download del componente aggiuntivo dall'Office Store.
-   Consente di risolvere un problema a causa del quale Excel potrebbe arrestarsi in modo anomalo quando si modificano fogli DDL tramite VBA.

### <a name="onenote-non-security-updates"></a>OneNote: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale l'area disegno della pagina di OneNote non risponde più ai clic del mouse dopo aver usato un PIN su Windows 10 versione 1607 (noto anche come aggiornamento dell'anniversario di Windows).
-   Disattivare il comportamento di stampa specifico di EDU quando l'utente inserisci un documento modificabile, ad esempio, docx o pptx.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale i conflitti di unione vengono visualizzati in modo errato durante la creazione condivisa.
-   Consente di risolvere un problema a causa del quale il pulsante di comando per un componente aggiuntivo non funziona dopo l'aggiornamento del componente aggiuntivo o dopo la rimozione o il download del componente aggiuntivo dall'Office Store.
-   Consente di risolvere un problema a causa del quale le chiamate verso il modello a oggetti VBA danno vita a un errore di runtime, se applicate alle forme dei grafici.

### <a name="publisher-non-security-updates"></a>Publisher: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale in Publisher non vengono visualizzate le immagini CMYK TIF.

### <a name="skype-for-business-security-updates"></a>Skype for Business: Aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS17-013](https://technet.microsoft.com/library/security/ms17-013): aggiornamento della sicurezza per Microsoft Graphics Component (4013075)

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS17-014](https://technet.microsoft.com/library/security/ms17-014): Aggiornamento della sicurezza per Microsoft Office (3217868)

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema relativo all'utilizzo della memoria quando si applicano determinate configurazioni del monitor.
-   Consente di risolvere un problema a causa del quale il pulsante di comando per un componente aggiuntivo non funziona dopo l'aggiornamento del componente aggiuntivo o dopo la rimozione o il download del componente aggiuntivo dall'Office Store.



## <a name="version-1701-february-22"></a>Versione 1701:22 febbraio
*Versione 1701 (Build 7766.2060)*

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità
-   **Miglioramenti della connettività e della trasformazione di dati:** Consente di espandere un elenco in una nuova colonna di testo con delimitatore tra i valori e di specificare un'opzione di failover durante la connessione a SQL.
-   **Miglioramenti della connettività e della trasformazione di dati:** Il tipo di dati percentuale è ora supportato e sono stati apportati dei miglioramenti alle esperienze di creazione di funzioni e combinazioni binarie.
-   **Connettore OLEDB:** Utilizzare il connettore OLEDB in Get & Transform per creare una query per importare i dati specificando una stringa di connessione e, facoltativamente, un'istruzione SQL da eseguire.
-   **Riproduzione dell'input penna:** Andare a Disegno \> Riproduzione input penna per riprodurre l'input penna avanti e indietro al fine di nascondere o mostrare i contenuti, fornire istruzioni dettagliate o comprendere meglio il flusso dei pensieri degli altri. [Ulteriori informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Supporto CSV (UTF-8):** aprire e salvare i file CSV che utilizzano la codifica di carattere UTF8.
-   **Miglioramenti della connettività e delle trasformazioni di dati:** selezionare per importare tabelle correlate durante il caricamento dei dati da un'origine OData, aggiungere colonne personalizzate con valori che derivano dal calcolo di una funzione oppure visualizzare le dipendenze tra query che usano una vista dedicata.
-   **Condivisi con l'utente corrente:** visualizzare i documenti condivisi dagli altri utenti andando a File \> Apri \> Condivisi con l'utente corrente. [Ulteriori informazioni](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Modifica dei colori:** utilizzare Aiutami per impostare il colore per il tipo di carattere, per l'evidenziazione, per il completamento di una forma e altro. [Ulteriori informazioni](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Aggiornamento della sicurezza per Microsoft Office (3204068)

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale, quando il tema di Office è impostato su Nero, viene visualizzato il messaggio "Errore imprevisto" quando si fa clic con il tasto destro del mouse su una query nel riquadro Query cartella di lavoro.
-   Consente di risolvere un errore a causa del quale Excel si arresta in modo anomalo quando l'utente tenta di accedere a Opzioni tabella pivot.
-   Risolvere un problema in cui i valori della cella con testo e virgolette doppie non sono esportati correttamente durante il salvataggio come CSV o CSV UTF-8.
-   Risolvere un problema in cui Excel si blocca o si arresta in modo anomalo quando viene chiuso.
-   Risolvere un problema in cui un collegamento ipertestuale contenente una formula di concatenazione ignora parte del risultato di concatenazione.
-   Risolvere un problema in cui incollando una tabella di Excel in formato RTF (RICH) su Word non viene preservato il formato della tabella.
-   Risolvere un problema in cui l'utente non può eseguire l’operazione Salva con nome quando la cartella di lavoro contiene un foglio di lavoro MS Excel 4.0 Macro.
-   Rendere la combinazione di tasti CTRL+ALT+5 il collegamento per spostare una selezione a livello di oggetti per associare altre applicazioni.
-   Consente di risolvere un problema che si verifica quando si digita nella barra della formula, si utilizza una funzione con elenco a discesa (ad esempio, VLOOKUP) e si preme Invio per completare la formula. L'errore comporta la selezione dell'elemento principale dell'elenco a discesa di completamento automatico invece di conservare il valore digitato.
-   Consente di risolvere un problema che si verifica quando si apre un file binario (BIFF8) di Excel 97 - Excel 2003 che contiene un collegamento ipertestuale all'interno di un foglio protetto. In questo caso, Excel considera il file come danneggiato e prova a correggere o rimuovere il contenuto non leggibile.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: Aggiornamenti non relativi alla sicurezza
-   Risolvere un problema in cui, se non è possibile caricare correttamente GrooveIntlResource.dll (situazione improbabile in condizioni normali), potrebbe verificarsi l’arresto anomalo di un’app Office se l'utente tenta di aprire o salvare un file in una cartella sincronizzata; oppure potrebbe verificarsi l’arresto anomalo di Esplora risorse se l'utente passa a una cartella sincronizzata utilizzando Esplora risorse.
-   Consente di risolvere un problema a causa del quale OneDrive for Business non è disabilitato, anche se la relativa chiave del Registro di sistema è impostata in modo da disabilitarlo, quando Office è configurato per ricevere aggiornamenti da una posizione diversa dalla rete per la distribuzione di contenuti (CDN) di Office.

### <a name="onenote-feature-updates"></a>OneNote: Aggiornamenti delle funzionalità
-   **Controllare la sincronizzazione di file e immagini:** Accedere a File \> Opzioni \> Sincronizza per controllare che tutti i file e le immagini vengano scaricati automaticamente per tutte le pagine nei blocchi appunti.

### <a name="onenote-non-security-updates"></a>OneNote: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale OneNote si arresta in modo anomalo quando viene stampata un'immagine di dimensioni superiori rispetto alla pagina.
-   Consente di risolvere un problema a causa del quale un utente non può eliminare un modello di pagina personalizzato.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti delle funzionalità
-   **Collaborate on attachments in real time:** Upload attachments to OneDrive for Business to let everyone work on the latest version. Use the drop-down menu on the attachment to upload or save it.
-   **Schede di riepilogo per pacchi e prenotazioni di viaggi:** Verificare e tenere traccia delle prenotazioni di viaggi e delle consegne di pacchi mediante le schede di riepilogo automaticamente create nella Posta in arrivo e nel Calendario. [Ulteriori informazioni](https://blogs.office.com/2016/06/28/stay-on-top-of-your-travel-and-deliveries-with-outlook/)
-   **Editor:** Offre strumenti di correzione contestuali avanzati che permettono di migliorare la scrittura. [More information](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale, quando si fa clic con il pulsante destro del mouse su un allegato nell'elenco degli allegati per una conversazione, sono visibili tutti gli elementi del menu di scelta rapida, anziché solo quelli applicabili.
-   Consente di risolvere un problema a causa del quale non è possibile aprire i messaggi di posta elettronica RTF inviati utilizzando Information Rights Management.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti delle funzionalità
-   **Sottotitoli codificati:** Se una diapositiva contiene un video con sottotitoli codificati, le didascalie possono essere riprodotte nella presentazione.
-   **Più tracce audio:** Se una diapositiva contiene un video con più tracce audio, le tracce possono essere riprodotte nella presentazione.
-   **Copia della sezione:** copiare e incollare le sezioni tra presentazioni.
-   **Condivisi con l'utente corrente:** visualizzare i documenti condivisi dagli altri utenti andando a File \> Apri \> Condivisi con l'utente corrente. [Ulteriori informazioni](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Riproduzione dell'input penna:** consente di riprodurre l'input penna avanti e indietro per nascondere o mostrare i contenuti, per fornire istruzioni dettagliate o per comprendere meglio il flusso dei pensieri degli altri. [Ulteriori informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Better recordings:** Create a presentation made up of recorded slides, screen recordings and inserted video, and then share that recorded content to be viewed remotely. You can also embed quizzes to assist with remote learning and make your presentation more interactive as well as change the ink color and use simpler controls to record narrations and audio.
-   **Miglioramenti per la progettazione:** fornisce suggerimenti per la progettazione mediante SmartArt per elenchi dei processi puntati.
-   **Scheda della barra multifunzione di registrazione:** consente di aggiungere una scheda di registrazione personalizzando la barra multifunzione.
-   **Modifica dei colori:** utilizzare Aiutami per impostare il colore per il tipo di carattere, per l'evidenziazione, per il completamento di una forma e altro. [Ulteriori informazioni](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)
-   **Zoom:** consente di creare un riepilogo interattivo della presentazione dell'utente con collegamenti di spostamento automatici. [Ulteriori informazioni](https://support.office.com/article/9d6c58cd-2125-4d29-86b1-0097c7dc47d7)
-   **Apertura di collegamenti ipertestuali:** Utilizzare CTRL+click per aprire i collegamenti ipertestuali quando si modifica una presentazione.
-   **Evidenziazione del testo:** consente di attirare l'attenzione su porzioni di testo impostanti utilizzando l'evidenziatore testo.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale la porzione ritagliata di un'immagine appare scura.
-   Consente di risolvere un problema a causa del quale, quando si è in modalità Presentazione standard e Assistente vocale è in esecuzione, PowerPoint si arresta in modo anomalo quando l'utente fa clic su un collegamento ipertestuale e il sito viene caricato lentamente.
-   Consente di risolvere un problema a causa del quale la digitazione in tempo reale durante la creazione condivisa non funziona con le tabelle.
-   Risolvere un problema in cui, quando si apre PowerPoint su un computer in cui è installato Malwarebytes 3.0, viene visualizzato l'errore "Ha smesso di funzionare" o PowerPoint si arresta in modo anomalo.
-   Risolvere un problema in cui il modello predefinito non viene visualizzato in File \> Nuovo.
-   Risolvere un problema in cui l'immissione del testo viene interrotta e ritardata quando un file con tipi di carattere incorporati viene salvato automaticamente.
-   Risolvere un problema copiando le immagini SVG (Scalable Vector Graphics) da Adobe Illustrator.

### <a name="project-feature-updates"></a>Project: Aggiornamenti delle funzionalità
-   **Campo bloccato:** Impostare il valore su Sì per evitare che i membri del team inviino aggiornamenti su un'attività.
-   **Etichette di sequenza temporale:** Distinguere le barre di sequenza temporale utilizzando etichette per assegnare nomi descrittivi.
-   **Indicatori di stato di sequenza temporale:** Utilizzare segni di spunta e indicatori di avanzamento di stato colorati nella visualizzazione della sequenza temporale per mostrare l’avanzamento di ogni attività.
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, Assistente vocale e altri strumenti di Assistive Technology per leggere e modificare progetti.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale non vengono visualizzate linee di collegamento durante la creazione di un collegamento tra progetti (uno principale e uno secondario).
-   Consente di risolvere un problema a causa del quale i valori di base rapportati alla scala cronologica non vengono sempre salvati correttamente in formato XML. Questo problema interessa soprattutto i valori di lavoro e costo che includono durate parziali.
-   Consente di risolvere un problema che si verifica durante l'applicazione di aggiornamenti di stato e a causa del quale il lavoro effettivo viene aggiunto all'assegnazione che il membro del team non ha segnalato.
-   Consente di risolvere un problema a causa del quale i valori di base vengono visualizzati per una risorsa, anche se una linea di base non è stata creata per tale risorsa.
-   Consente di risolvere un problema a causa del quale i clip multimediali per l'anteprima di stampa vengono riprodotti in modo che il testo non sia visibile.
-   Consente di risolvere un problema che si verifica durante l'apertura di un file mpp da SharePoint utilizzando un URL di collegamento e a causa del quale il file di apre come estratto, anche se l'opzione "Estrarre i documenti prima di poterli modificare?" è abilitata.
-   Consente di risolvere un problema a causa del quale gli aggiornamenti apportati alle risorse materiali da Project Web App modificano in modo errato i dati rapportati alla scala cronologica.
-   Consente di risolvere un problema che si verifica durante l'apertura di un progetto con attività cardine e a causa del quale è possibile che venga aggiunta una data di inizio effettiva all'attività, anche se non ne era provvista al momento dell'ultimo salvataggio.
-   Consente di risolvere un problema relativo alla nuova numerazione della struttura di suddivisione del lavoro (WBS).
-   Consente di risolvere un problema a causa del quale Project si arresta in modo anomalo quando si esce da una visualizzazione basata su griglie e Assistente vocale è attivo.
-   Consente di risolvere un problema a causa del quale viene visualizzato un messaggio di errore errato sul troncamento dei dati rapportato alla scala cronologica quando viene aperto un file XML.
-   Consente di risolvere un problema a causa del quale il salvataggio di una baseline non imposta correttamente i valori rapportati alla scala cronologica.
-   Consente di risolvere un problema a causa del quale il ritardo di assegnazione viene ignorato quando i dati del progetto vengono letti da un file XML.
-   Consente di risolvere un problema a causa del quale, quando si apre un file da Project Online, in Data ultima modifica viene mostrata l'ora UTC anziché l'ora adattata al fuso orario.
-   Consente di risolvere un problema a causa del quale non vengono visualizzati i bordi colorati di raggruppamento per le righe non di raggruppamento quando si stampa una visualizzazione elenco.
-   Consente di risolvere un problema a causa del quale un'opzione di ripristino viene visualizzata in modo errato quando l'utente controlla un'attività che ha un'assegnazione oltre il problema dell'unità massima.
-   Consente di risolvere un problema a causa del quale non è possibile modificare il valore di un campo Codice struttura dopo la pubblicazione del progetto.
-   Consente di risolvere un problema in cui le barre di Gantt non vengono ridimensionate correttamente nelle schermate a DPI elevato nella visualizzazione al 175%.
-   Consente di risolvere un problema in cui se l'utente imposta il tempo di ritardo tramite la finestra di dialogo Informazioni attività, questo viene impostato in modo errato su una durata trascorsa.
-   Consente di risolvere un problema in cui all’apertura di alcuni file XML, la data di inizio delle attività non è impostata correttamente a causa di un problema con l'assegnazione.

### <a name="skype-for-business-feature-updates"></a>Skype for Business: Aggiornamenti delle funzionalità
-   **Stile di notifica di Windows:** Modifiche apportate all'aspetto delle notifiche per le chiamate in arrivo e le conversazioni. [Ulteriori informazioni](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/New-Skype-for-Business-2016-on-Windows-Notifications-look-and/ba-p/39885)
-   **Trasferimento consultivo:** All'interno di una chiamata, consultarsi con un altro utente tramite una chat o una chiamata prima di trasferire la chiamata a quell'utente. [Ulteriori informazioni](https://techcommunity.microsoft.com/t5/Skype-Operations-Framework-Skype/Skype-for-Business-2016-on-Windows-Consultative-Transfer/ba-p/41122)
-   **Notifiche del microfono:** Viene visualizzata una notifica nella conversazione quando l'audio del microfono viene disattivato nel sistema operativo oppure quando il microfono non rileva audio.
-   **Disabilitare "Numero personale":** Utilizzare la voce del Registro di sistema DisableDisplayMyNumber per disattivare "Numero personale" nella tastiera del telefono.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Modifica da testo a immagine (X o segno di spunta) dei pulsanti della sala di attesa usati per accettare o rifiutare partecipanti.
-   Modifica relativa al testo della notifica di promemoria delle riunioni da "Accetta" a "Partecipa".
-   Aggiornamento del messaggio visualizzato dal mittente di un messaggio istantaneo, nel momento in cui lo stato del destinatario è impostato su Non disturbare.
-   Aggiornamento del messaggio visualizzato dal mittente di un messaggio istantaneo, quando il destinatario è offline e l'opzione "salvataggio dati" è disattivata. Ora è più chiaro che il destinatario non riceverà il messaggio.
-   Aggiunta della funzionalità per spostare la barra di divisione verticale tra la cronologia della chat e l'elenco dei partecipanti a una chat di gruppo.
-   Aggiunta della funzionalità per ridimensionare l'elenco di schede nella messaggistica istantanea oppure nelle finestre della chatroom.
-   Aggiunta della funzionalità per selezionare le chatroom cercate durante la creazione di un feed argomenti.
-   Consente di risolvere un problema a causa del quale non viene più visualizzato un messaggio a metà conversazione della cronologia chat.
-   Consente di risolvere un problema a causa del quale i messaggi duplicati vengono visualizzati nella finestra della conversazione.
-   Consente di risolvere un problema a causa del quale le azioni delle notifiche di tipo avviso popup (Accetta o Ignora) non vengono visualizzate correttamente in presenza di un numero elevato di notifiche.
-   Consente di risolvere un problema a causa del quale l'utente non riesce a digitare un messaggio dopo aver utilizzato la combinazione ALT+TAB per aprire la finestra di una conversazione ridotta a icona.
-   Consente di risolvere un problema a causa del quale il pulsante della messaggistica non è selezionabile nella scheda del contatto di un utente, anche se il servizio di messaggistica istantanea è disponibile.
-   Consente di risolvere un errore a causa del quale non viene ripristinata la dimensione e la posizione precedente di più finestre di conversazione, dopo che sono state chiude e aperte di nuovo.
-   Consente di risolvere un problema a causa del quale i link non si aprono quando vengono selezionati.
-   Consente di risolvere un problema a causa del quale il testo per la riunione online inserito nel campo Paese non viene visualizzato correttamente per gli utenti che non utilizzano i caratteri inglesi.
-   Consente di risolvere un problema a causa del quale le informazioni di notifica (ad esempio, la durata di una chiamata) non vengono visualizzate correttamente nelle lingue che utilizzano la scrittura da destra a sinistra.
-   Consente di risolvere un problema che si verifica durante la creazione di un feed argomenti e a causa del quale la cancellazione dei risultati di ricerca non determina il ripristino dei risultati su un elenco di chatroom seguite.
-   Consente di risolvere un problema in cui Skype for Business si blocca quando sono aperte più finestre di conversazione contemporaneamente.
-   Consente di risolvere un problema a causa del quale la finestra dell'ultima conversazione diventa vuota una volta che tutte le altre schede vengono chiuse.
-   Consente di risolvere un problema a causa del quale lo stato attivo predefinito non è presente nell'area di input della chat quando le conversazioni a schede sono disabilitate.
-   Consente di risolvere un problema a causa del quale il collegamento "PIN di accesso dimenticato?" non viene visualizzato nell'invito alla riunione.
-   Consente di risolvere un problema a causa del quale una parte del testo viene ritagliata e troncata nelle pagine Generali e Audio del dispositivo quando si utilizzano schermate a DPI elevato nella visualizzazione al 175% o superiore.
-   Consente di risolvere un problema a causa del quale Skype for Business si arresta in modo anomalo quando il computer viene sospeso o riavviato quando non c'è rete e il computer è un dispositivo "Always On/Always Connected (AOAC)".
-   Consente di risolvere un problema a causa del quale non vengono rilevati microfoni in una chiamata quando si utilizza un dispositivo Polycom CX100.
-   Consente di risolvere un problema a causa del quale la selezione di un collegamento come \\\\nomeserver o file:// in un messaggio IM restituisce un messaggio di errore anziché aprire il relativo percorso.
-   Consente di risolvere un problema a causa del quale, in un ambiente VDI (Virtual Desktop Infrastructure) che utilizza il routing in base alla posizione, l'utente non può effettuare o ricevere chiamate PSTN poiché il server considera la posizione dell'utente non valida per tali chiamate.
-   Modificare la riga dell'oggetto dell'e-mail inviata per un messaggio perso, quando lo stato dell'utente è impostato su Non disturbare o Presentazione, da "Conversazione non effettuata con \<nome\>" a "\<Nome\> ti ha inviato un messaggio in Skype for Business".
-   Avviare l'acquisizione del timestamp per il primo accesso sul dispositivo come parte dei [dati di censimento](https://docs.microsoft.com/skypeforbusiness/legal-and-regulatory/data-collection-practices) per individuare le tendenze di affidabilità di accesso.
-   Risolvere un problema in cui l'opzione che consente di condividere un monitor secondario non viene visualizzata con determinate configurazioni del monitor su Window 10 Versione 1607 (nota anche come Aggiornamento dell'anniversario).
-   Risolvere un problema per il quale Skype for Business si arresta in modo anomalo quando si esegue lo zoom di contenuto condiviso se il condivisore usa un'implementazione di terze parti di RDP.
-   Consente di risolvere un problema in cui il pannello Controlli audio non viene visualizzato quando un utente fa clic sul pulsante dei controlli durante una chiamata vocale in un ambiente VDI (Virtual Desktop Infrastructure).
-   Risolvere un problema in cui viene visualizzato uno schermo nero quando un utente esegue Windows 7 e condivide innanzitutto il monitor principale e quindi passa a condividere un secondo monitor.
-   Risolvere un problema in cui determinati caratteri speciali, ad esempio la "e commerciale" (&), non possono essere immessi nella casella di input di ricerca oppure nella sezione "Cosa succede oggi?".
-   Risolvere un problema in cui il numero di messaggi non letti non è visualizzato se non ci sono messaggi istantanei persi mentre si era offline.
-   Risolvere un problema in cui i modelli "Invita tramite posta elettronica" hanno menzionato Lync invece di Skype.
-   Risolvere un problema in cui manca il numero di riga dall'area sotto la tastiera del telefono "Numero personale".
-   Risolvere un problema in cui il puntatore del mouse non è visualizzato nell'area di input del messaggio istantaneo dopo l'invio di un messaggio in una chat.
-   Risolvere un problema in cui Skype for Business si blocca durante l'accesso ed esiste un problema durante il caricamento del pool nella cache.
-   Risolvere un problema in cui Skype for Business si arresta in modo anomalo durante l'accesso e il ripristino delle conversazioni.
-   Risolvere un problema in cui Skype for Business si blocca durante l'accesso dopo la ripresa.
-   Risolvere un problema in cui il collegamento alla riunione è disabilitato se nei server di Exchange di entrambe le organizzazioni TNEF è disabilitato.
-   Risolvere un problema in cui non è possibile riavviare una videochiamata se si sta svolgendo solo una conversazione istantanea.
-   Risolvere un problema in cui le annotazioni di testo su una lavagna vengono perse quando si salva la lavagna come file PNG.
-   Risolvere un problema in cui la prima riga è nascosta quando si immettono più di due righe in giapponese nella finestra di messaggistica istantanea.
-   Risolvere un problema in cui la e commerciale (&) viene sostituita da un carattere di sottolineatura nei nomi in modo non corretto.
-   Risolvere un problema con l'URL "Partecipa a riunione online" durante una riunione pianificata.
-   Risolvere un problema in cui se si posiziona il mouse su una finestra, questa non si attiva anche se il sistema operativo è configurato per eseguire questa operazione.
-   Risolvere un problema in cui gli elementi della cronologia di una conversazione in uscita mostrano il chiamante anziché la persona chiamata.
-   Risolvere un problema in cui F12 non consente di salvare in locale una conversazione.
-   Risolvere un problema in cui il messaggio di posta elettronica di una conversazione perso non contiene il messaggio istantaneo iniziale.
-   Risolvere un problema in cui è possibile aggiungere un emoji nell'area di testo di messaggistica istantanea, anche se il relatore ha disabilitato la partecipazione alla messaggistica istantanea.
-   Risolvere un problema con il layout della finestra di dialogo dell’opzione Suonerie e suoni.
-   Risolvere un problema in cui Skype for Business si arresta in modo anomalo durante la chiusura di una finestra di conversazione.
-   Risolvere un problema in cui l’accesso DNS-less ha esito negativo quando il dominio è registrato come dominio personale.
-   Risolvere un problema in cui le impostazioni di notifica della chat persistenti non vengono salvate o caricate correttamente.
-   Risolvere un problema in cui le finestre o chat room di conversazione peer-to-peer non vengono visualizzate dopo l'accesso anche se l'impostazione per riaprire le conversazioni è impostata.
-   Risolvere un problema in cui la disattivazione o l’attivazione dell'audio di una conversazione attiva causa la visualizzazione di altre finestre di conversazione come messaggi non letti.
-   Risolvere un problema in cui gli utenti configurati per il bypass multimediale non riescono a riprendere una chiamata da un gateway PSTN dopo aver messo la chiamata in attesa.
-   Risolvere un problema in cui l'utente visualizza una casella blu anziché il video quando partecipa a una riunione tramite un URL usando l’implementazione RDP di terze parti.
-   Consente di risolvere un problema a causa del quale viene visualizzata parte dell'indirizzo SIP dell'utente anziché il nome visualizzato in un avviso popup.
-   Fix an issue where, when Skype for Business connects to a SIP server over port 443 and a proxy server is present, there is a significant delay in the sign-in process if the proxy doesn't allow such connections. The fix is enabled by adding the EnableDetectProxyForAllConnections DWORD registry entry under HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync, and setting the value to 1.
-   Consente di risolvere un problema che si verifica quando si utilizzano conversazioni a schede, si fa doppio clic su una scheda e si inizia a scrivere. Talvolta, queste operazioni causano il passaggio a una scheda differente, anche se si continua a scrivere nella finestra della conversazione.
-   Consente di risolvere un problema a causa del quale gli URL contenuti in un messaggio istantaneo non possono essere selezionati nella finestra di cronologia della chat utilizzando la tastiera.
-   Consente di risolvere un problema a causa del quale dovrebbe essere possibile sentire l'audio di digitazione se è stata selezionata la casella di controllo "Riproduci un suono in caso di digitazione da parte di un utente durante la visualizzazione di un messaggio istantaneo" nelle opzioni di suonerie e suoni.
-   Consente di risolvere un problema a causa del quale le finestre di dialogo visualizzate non vengono annunciate durante l'utilizzo di un'utilità per la lettura dello schermo, ad esempio Assistente vocale.
-   Consente di risolvere un problema a causa del quale non è possibile usare la tastiera per spostarsi durante la prima visione di un'esercitazione e questa non può essere letta da un'utilità per la lettura dello schermo, ad esempio Assistente vocale.
-   Consente di risolvere un problema a causa del quale l'icona di presenza della barra delle applicazioni non modifica la scala delle impostazioni con valori DPI alti.
-   Consente di risolvere un problema a causa del quale non è possibile selezionare il pulsante Cancella campo nella casella di ricerca utilizzando la tastiera.
-   Consente di risolvere un problema a causa del quale un utente non può avviare una riunione se l'invito proviene da un utente in un altro pool.
-   Consente di risolvere un problema a causa del quale un utente che aggiunge se stesso a una riunione viene visualizzato erroneamente come utente differente.
-   Consente di risolvere un problema a causa del quale l'icona di presenza dei contatti sulla notifica di modifica dello stato è stata nascosta per le chiamate in arrivo per il responsabile.
-   Consente di risolvere un problema a causa del quale l'intermittenza del cursore di testo non corrisponde alle impostazioni delle proprietà della tastiera in Windows.
-   Consente di risolvere un problema a causa del quale un'utilità di lettura dello schermo annuncia un nome di contatto errato per una conversazione di gruppo.
-   Consente di risolvere un problema a causa del quale l'utente non può selezionare più contatti utilizzando la tastiera.
-   Consente di risolvere un problema a causa del quale non è possibile recuperare da Exchange le foto dell'utente.
-   Consente di risolvere un problema a causa del quale il client Skype for Business si connette a un server Skype for Business sulla rete interna, anziché quella esterna, quando l'utente si connette tramite accesso diretto.
-   Consente di risolvere un problema a causa del quale il client Skype for Business si blocca quando si tenta di risolvere il nome del proprietario della riunione.
-   Consente di risolvere un problema a causa del quale Skype for Business si blocca se si modifica un'impostazione di Windows durante l'avvio o la chiusura dell'applicazione.
-   Consente di risolvere un problema a causa del quale Skype for Business si blocca quando si apre l'elenco dei partecipanti in una chat room persistente e si tenta di spostare lo stato attivo della tastiera sull'elenco dei partecipanti.
-   Consente di risolvere un problema a causa del quale Skype for Business si arresta in modo anomalo, quando viene riattivato e non sono disponibili reti.

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti delle funzionalità
-   **Componente aggiuntivo di modellazione del database:** Utilizzare il componente aggiuntivo per creare un modello di database relativo a un database esistente. In questo modo, è possibile pianificare un nuovo database oppure comprendere quello esistente. [Ulteriori informazioni](https://support.office.com/article/fb034862-acfc-45bc-88b2-f33d1e1f8614), [Scaricare il componente aggiuntivo](https://go.microsoft.com/fwlink/p/?linkid=835953)
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, Assistente vocale e altri strumenti di Assistive Technology per utilizzare le forme, modificare con altri e molto altro.
-   **Third-party templates and diagrams:** Browse or search for new templates and sample diagrams available from select third-party content providers. The third-party provider’s name is listed on the thumbnail.
-   **Supporto input penna:** per creare disegni e inserire note con gli strumenti della nuova scheda nuovo Disegno, usare la penna o il dito.

### <a name="word-feature-updates"></a>Word: Aggiornamenti delle funzionalità
-   **Miglioramenti accessibilità:** Supporto migliorato per l'utilizzo della tastiera, Assistente vocale e altri strumenti di Assistive Technology per leggere e modificare documenti. [Ulteriori informazioni](https://support.office.com/article/69aed572-336e-4722-a97e-23393cc481b2)
-   **Editor:** Offre strumenti di correzione contestuali avanzati che permettono di migliorare la scrittura. [Ulteriori informazioni](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)
-   **Riproduzione dell'input penna:** Andare a Disegno \> Riproduzione input penna per riprodurre l'input penna avanti e indietro al fine di nascondere o mostrare i contenuti, fornire istruzioni dettagliate o comprendere meglio il flusso dei pensieri degli altri. [Ulteriori informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)
-   **Modifica con gesti naturali della penna:** apportare modifiche a un documento cerchiando gli elementi da selezionare e tagliando le parti da eliminare. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)
-   **Condivisi con l'utente corrente:** visualizzare i documenti condivisi dagli altri utenti andando a File \> Apri \> Condivisi con l'utente corrente. [Ulteriori informazioni](https://support.office.com/article/e0476dc7-bf2f-4203-b9ad-c809578b03e7)
-   **Modifica dei colori:** utilizzare Aiutami per impostare il colore per il tipo di carattere, per l'evidenziazione, per il completamento di una forma e altro. [Ulteriori informazioni](https://support.office.com/article/5bab7082-b772-427c-a106-14ae46f8687f)

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale la visualizzazione di un documento in modalità di lettura impedisce al tasto TAB di funzionare in modo corretto all'interno di un secondo documento che viene visualizzato in modalità di stampa.
-   Consente di risolvere un problema a causa del quale Word si arresta in modo anomalo quando vengono caricate più raccolte del correttore grammaticale.
-   Consente di risolvere un problema in cui i tratti con input penna scompaiono dopo due o tre tratti.
-   Consente di risolvere un problema con virgolette che scompaiono quando si usa Google Input Method Editor (IME).
-   Consente di risolvere un problema a causa del quale un utente non può utilizzare l'input penna con controlli contenuto o quando si effettuano selezioni non contigue.

### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: Aggiornamenti delle funzionalità
-   **Commenti e suggerimenti:** Consente di suggerire nuove funzionalità o indicare gli aspetti positivi o negativi a Microsoft accedendo a File \> Commenti e suggerimenti

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   Bollettino Microsoft sulla sicurezza [MS16-148](https://technet.microsoft.com/library/security/ms16-148): Aggiornamento della sicurezza per Microsoft Office (3204068)

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale l'utilizzo delle combinazioni CTRL + ALT + 7 o CTRL + ALT + 8 su una tastiera tedesca determina l'apertura dello strumento dei commenti e suggerimenti anziché l'inserimento del carattere corretto.
-   Consente di risolvere un problema a causa del quale TraceLogging causa l'arresto anomalo di Windows 7 durante l'installazione o l'aggiornamento di Office.
-   Consente di risolvere un problema a causa del quale, quando si disegna con l'input penna e un mouse, rilasciando il pulsante del mouse l'input penna si sposta lentamente.
-   Consente di risolvere un problema a causa del quale, dopo aver inserito un'immagine SVG in un documento di Office, tale immagine scompare quando il documento viene salvato e riaperto.
-   Fix an issue where Office shows the following error message during activation for non-English users: "The maximum length of the product key is 25 characters."
-   Risolvere un problema con i moduli VBA che possono causare l'interruzione del funzionamento o la visualizzazione non corretta dell'ordine Z dei frame.
-   Consente di risolvere un problema a causa del quale un aggiornamento attivato da Configuration Manager modifica le impostazioni di UpdateChannel nel registro di sistema in qualcosa che non è un canale di aggiornamento valido.



## <a name="version-1609-january-10"></a>Versione 1609:10 gennaio
*Versione 1609 (Build 7369.2102)*

Nota: gli aggiornamenti della sicurezza descritti nel Bollettino Microsoft sulla sicurezza [MS17-002](https://technet.microsoft.com/library/security/ms17-002) non si applicano alla versione di Word in questa versione del canale.

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Risolvere un problema in cui l'utilizzo di una finestra di dialogo Modifica misura causa l'arresto anomalo di Excel.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Risolvere un problema in cui a volte l'utilizzo di forme causa l'arresto anomalo di PowerPoint.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Risolvere un problema in cui l'opzione che consente di condividere un monitor secondario non viene visualizzata con determinate configurazioni del monitor su Window 10 Versione 1607 (nota anche come Aggiornamento dell'anniversario).
-   Risolvere un problema per il quale Skype for Business si arresta in modo anomalo quando si esegue lo zoom di contenuto condiviso se il condivisore usa un'implementazione di terze parti di RDP.
-   Fix an issue where, when Skype for Business connects to a SIP server over port 443 and a proxy server is present, there is a significant delay in the sign-in process if the proxy doesn't allow such connections. The fix is enabled by adding the EnableDetectProxyForAllConnections DWORD registry entry under HKEY\_CURRENT\_USER\\Software\\Microsoft\\UCCPlatform\\Lync, and setting the value to 1.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Risolvere un problema a causa del quale, quando si utilizza il metodo InsertXML, viene visualizzato un segnaposto per un collegamento immagine interrotto anziché l'immagine effettiva.

