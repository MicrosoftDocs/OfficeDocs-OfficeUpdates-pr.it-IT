---
title: Note archiviate sulle versioni del Canale semestrale (Mirato) nel 2019
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT sulle note per le versioni del Canale semestrale (Mirato) per Office 365 ProPlus nel 2019
ms.openlocfilehash: 5d4d10b03d82788b4d3b561d0664b48d680dfc39
ms.sourcegitcommit: 96185aa6c5a06095c58b57ac36cb2800add8bea0
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 01/06/2021
ms.locfileid: "49760744"
---
# <a name="archived-release-notes-for-semi-annual-enterprise-channel-preview"></a>Note archiviate sulla versione del Canale Enterprise semestrale (Anteprima)

Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non inerenti alla sicurezza inclusi negli aggiornamenti del Canale Enterprise semestrale (Anteprima) per Office 365 ProPlus, Visio Pro per Office 365, Project Online Desktop Client e Office 365 Business.

> [!NOTE]
> - Spesso le funzionalità (e talvolta persino le correzioni) vengono distribuite nel Canale Enterprise semestrale (Anteprima) in un certo arco di tempo. Se non si vede subito un elemento descritto di seguito, è possibile aspettarselo al più presto. [Altre informazioni](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams è incluso nelle nuove installazioni del Canale Enterprise semestrale (Anteprima), a partire dalla versione 1902. Teams verrà aggiunto alle installazioni esistenti del Canale Enterprise semestrale (Anteprima) quando queste verranno aggiornate alla versione 1908 o successiva. Per altre informazioni, vedere [Distribuire Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).

## <a name="version-1908-december-10"></a>Versione 1908: 10 dicembre
*Versione 1908 (build 11929.20516)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.

- È stato risolto un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.

### <a name="excel"></a>Excel

- È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.

- Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal file cubo.

- La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.

- È stato risolto un problema per cui la funzione Cerca restituiva un errore.

- Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.

- È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.

### <a name="outlook"></a>Outlook

- È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.

- È stato risolto un problema che causava la visualizzazione del messaggio &quot;Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange&quot; all'apertura della finestra di dialogo Regole.

- È stato risolto un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto. 

### <a name="word"></a>Word

- Abbiamo risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.

- È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.

- Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-22"></a>Versione 1908: 22 novembre
*Versione 1908 (Build 11929.20494)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="access"></a>Access

- È stato risolto un problema per cui l'esecuzione di una query di aggiornamento restituiva erroneamente il messaggio di query danneggiata.

### <a name="excel"></a>Excel

- Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.

- È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.

- Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.

- È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante &quot;OK&quot; quando si provava a contattare il supporto dal contesto di creazione dell'account.

- È stata apportata una modifica che consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN. Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.

- È stato risolto un problema che causava il malfunzionamento della ricerca nei gruppi moderni.

- È stato risolto un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo &quot;Conversazione non effettuata&quot;.

- È stato risolto un problema che causava il malfunzionamento della ricerca in Gruppi moderni.

### <a name="word"></a>Word

- È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema che poteva causare un errore in PowerPoint quando si prova a presentare online.

- È stata migliorata l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.

- È stato risolto un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.

- È stato risolto un problema nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-november-12"></a>Versione 1908: 12 novembre
*Versione 1908 (Build 11929.20436)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel

- Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.
- È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.
- È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.
- È stato risolto un problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.
- Sono state notevolmente migliorate le prestazioni del filtro per colore.
- È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.
- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.

### <a name="outlook"></a>Outlook

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.
- È stato risolto un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.
- È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.
- È stato risolto un problema che causava un errore di Outlook durante l'interazione con determinati collegamenti sicuri.
- È stato risolto un problema che causava un errore durante l'elaborazione delle risposte del servizio di individuazione automatica.
- È stato risolto un problema per cui venivano visualizzate cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.
- È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.

### <a name="powerpoint"></a>PowerPoint

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.
- Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti causava un errore in PowerPoint.

### <a name="project"></a>Project

- È stato risolto un problema per cui il comando Livella tutto non risolveva adeguatamente una sovrassegnazione delle risorse.
- È stato risolto un problema per cui in caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.
- È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.

### <a name="word"></a>Word

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.
- Sono stati risolti diversi problemi che causavano il blocco dell'app durante la chiusura. Sono stati risolti anche alcuni problemi correlati ai componenti aggiuntivi.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Sono stati risolti dei problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="october-15"></a>15 ottobre

### <a name="non-security-updates"></a>Aggiornamenti non relativi alla sicurezza

### <a name="office-suite"></a>Famiglia di prodotti Office
- Abbiamo temporaneamente disabilitato la finestra di dialogo Salva nel cloud per risolvere il problema di salvataggio pubblicato il 14 ottobre 2019 per le build precedenti alla 16.0.11929.20396. Questa funzionalità verrà riattivata a breve.

## <a name="version-1908-october-14"></a>Versione 1908: 14 ottobre
*Versione 1908 (Build 11929.20396)*


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div>È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.</div>

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint 2019 per le build precedenti alla 16.0.11929.20396.  Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.

- È stato risolto un problema per cui, in alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento.  Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-08"></a>Versione 1908: 8 ottobre
*Versione 1908 (Build 11929.20388)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.

- È stato risolto un problema per abilitare più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.

- È stato risolto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.

### <a name="outlook"></a>Outlook

- È stato corretto un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.

- È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.

- È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema che causava un arresto anomalo all'apertura di un file.

- È stato risolto un problema per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.

- È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.

- Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-10"></a>Versione 1908: 10 September
*Versione 1908 (Build 11929.20300)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Zoom con più spazio:** ingrandire la casella Zoom e cambiare il tipo di carattere. Tutte le modifiche verranno mantenute. [Altre informazioni](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

- **Monitorare gli oggetti di database:** visualizzare chiaramente la scheda attiva, trascinare facilmente le schede per disporle in modo diverso e chiudere gli oggetti di database con un solo clic.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel"></a>Excel

- **Scoprire di più sui dati:** il nuovo pulsante Idee cerca modelli nei dati e li usa per creare suggerimenti intelligenti e personalizzati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

- **Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Fogli di lavoro animati:** è possibile inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella cartella di lavoro. [Altre informazioni](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **La collaborazione è stata semplificata:** i miglioramenti apportati alla creazione condivisa indicano che, quando si usa la formattazione condizionale, gli stili cella e così via, le modifiche vengono unite perfettamente con quelle dei propri collaboratori.

- **Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle. [Altre informazioni](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi. Semplice individuazione di funzioni, colonne e parametri.

- **Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a>Outlook

- **Continuare a lavorare durante lo spostamento di messaggi:** ora Outlook sposta i messaggi in background, di conseguenza è possibile continuare a lavorare durante lo spostamento di grandi quantità di messaggi tra le cartelle.

- **Avere un momento di respiro tra una riunione e l'altra:** dare ai partecipanti il tempo di riprendere fiato o di viaggiare da una località all'altra impostando le riunioni in modo che terminino per impostazione predefinita 5-10 minuti in anticipo.

- **Utilizzo di meme:** quando testo o immagini statiche non bastano, si può usare una GIF animata per esprimere il proprio pensiero. [Altre informazioni](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Aggiornamento dell'esperienza utente di Outlook:** è finalmente accessibile a tutti un'esperienza semplificata, in precedenza disponibile in anteprima con Prossimamente, progettata per consentire all'utente di concentrarsi sugli aspetti più importanti. [Altre informazioni](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Possibilità di scegliere tra layout medio o più ridotto:** l'opzione Usa spaziatura inferiore consente di decidere se si preferisce lasciare maggiore spazio fra gli elementi o adottare un layout più ridotto per visualizzare un maggior numero di elementi.

- **Barra multifunzione semplificata e personalizzabile:** un'unica riga essenziale riunisce i pulsanti usati di frequente. In questo modo è possibile passare facilmente dalla visualizzazione classica a quella semplificata e aggiungere/rimuovere comandi. [Altre informazioni](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Un modo più rapido per aggiungere account:** grazie ai miglioramenti per la configurazione dell'account, l'aggiunta di account di Outlook.com e Gmail che usano l'autenticazione a 2 fattori in Outlook è più facile che mai. [Altre informazioni](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Selezione dell'azione preferita:** le azioni Contrassegna e Elimina non vengono usate, ma si preferisce usare Archivia o Segna come già letto? Come personalizzare il menu Azioni rapide con i comandi usati più di frequente.

- **Addio ai limiti per la sincronizzazione:** con i miglioramenti di Outlook non esiste più il limite di cartelle e quindi è possibile sincronizzare le cassette postali condivise.

- **Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a>PowerPoint

- **Fare domande al pubblico con un test o un sondaggio:** inserire un test o un sondaggio in una diapositiva. Office raccoglie e archivia le risposte. [Ulteriori informazioni](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

- **Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.

- **Inserire un video online è più facile che mai:** se si vuole inserire un video da Vimeo o YouTube nella diapositiva, basta il collegamento alla pagina del video. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Spostamento di forme migliorato:** assegnare un nome alle forme per un maggiore controllo sul modo in cui effettuano il morphing. [Altre informazioni](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo, nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a>Project

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Addio ai collegamenti interrotti di Excel:** impossibile trovare la cartella di lavoro di Excel collegata al diagramma del Visualizzatore dati? Collegarla di nuovo per riprendere l’attività. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Stencil di Azure incorporati:** per progettare un'applicazione cloud o pianificare un'architettura è possibile scegliere tra decine di stencil di Azure. [Altre informazioni](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Maggiore controllo sui diagrammi di flusso di dati:** i nuovi fantastici layout per i diagrammi di flusso del Visualizzatore dati sono chiari, nitidi e facili da capire. Fare clic sulla scheda Progettazione.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Esportazione dei diagrammi di processo in Word:** è possibile aggiungere automaticamente il contenuto dei diagrammi, come forme e metadati, a un documento Word. Quindi, personalizzare il documento per creare linee guida di processi e manuali operativi. [Altre informazioni](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Esportare elementi visivi di Visio da Power BI:** gli oggetti visivi di Visio per Power BI vengono ora visualizzati correttamente quando si esportano i report di Power BI come PDF, file di PowerPoint e altro ancora. [Altre informazioni](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **Modifica semplificata con Editor input penna:** con un solo tratto della penna, si possono dividere o unire le parole, aggiungere una nuova riga o inserire parole. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Trasformare il documento da statico a sorprendente:** trasformare il documento in una pagina web interattiva, facile da condividere che si adatta perfettamente a qualsiasi dispositivo. [Altre informazioni](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Attirare l'attenzione tramite le \@menzioni:** usare le @menzioni nei commenti per informare altri utenti quando c'è bisogno del loro input. [Altre informazioni](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- **Migliorare la comprensione con Focus su riga:** spostarsi in un documento riga per riga senza distrazioni. Modificare lo stato attivo per rendere visibili una, tre o cinque righe alla volta. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.

- **Aumentare l'efficacia del contenuto:** rendere accessibili i documenti Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **La modalità Strumenti di apprendimento dispone di ulteriore supporto per più colori della pagina:** in Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina. Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)


- **Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Installazione di Microsoft Teams**: Teams viene aggiunto alle installazioni esistenti di Office 365 ProPlus. [Altre informazioni](https://docs.microsoft.com/DeployOffice/teams-install)

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.

- **Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse. [Altre informazioni](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Le icone di Office hanno un nuovo aspetto:** le icone di Office sono state riprogettate per riflettere l'esperienza semplice potente e intelligente di Office.

- **Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle installazioni esistenti di Office 365 ProPlus. [Altre informazioni](https://docs.microsoft.com/DeployOffice/teams-install)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.

- È stato risolto un problema per cui cambiare il modo in cui una tabella pivot viene ordinata e aggiornarla durante una sessione di creazione condivisa con altri utenti potrebbe causare un errore.

- È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.

- È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.

- È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.

- È stato risolto un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni. Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.

- È stato risolto un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.

- È stato risolto un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.

- È stato risolto un problema che causa ambiguità per i responsabili circa il fatto che un delegato abbia già risposto o meno a una determinata convocazione di riunione.

- È stato risolto un problema che causava agli utenti di Outlook di rimanere bloccati nello stato "Password necessaria" in alcuni scenari.

- È stato risolto un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.

- È stato risolto un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.

- È stato risolto un problema temporaneo del servizio che presentava agli utenti un messaggio di errore "Impossibile trovare il file. Verificare che il percorso e il nome file siano corretti" quando si usano allegati cloud. [Altre informazioni](https://support.office.com/article/outlook-unable-to-attach-onedrive-or-sharepoint-files-to-emails-136951bb-60dc-478a-b916-6ee39e62c37a)

- È stato risolto un problema che presentava agli utenti i file caricati da Outlook a OneDrive o SharePoint con il nome del file cambiato con diversi caratteri sostituiti da caratteri di sottolineatura.

- È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.


### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.

- È stato risolto un problema per ripristinare il nome accessibile per i controlli video di PowerPoint.

- È stato risolto un problema che impediva l'avvio di alcune animazioni

### <a name="project"></a>Project

- È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.


### <a name="visio"></a>Visio

- L'esportazione in SVG da Visio non funzionava per numerose forme.

### <a name="word"></a>Word

- È stato risolto un problema che presentava agli utenti dei messaggi di errore durante la collaborazione con altri utenti in un documento di Word.

- È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.


### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui in alcuni casi un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica.

- È stato risolto un problema per cui le visualizzazioni ad albero di grandi dimensioni causavano un errore.

- È stato risolto un problema di identificazione non corretta del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-august-13"></a>Versione 1902: 13 agosto
*Versione 1902 (Build 11328.20392)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema per cui l'icona di cancellazione del filtro veniva visualizzata sia per i filtri dei dati filtrati che per quelli non filtrati nelle tabelle.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema che causava una chiusura imprevista dell'applicazione mentre si collaborava a un documento con altri utenti.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema per cui i campi di aggiornamento VBA risultavano lenti.
- È stato risolto un problema per cui alcuni file DOC venivano indicati come danneggiati all'apertura.
- È stato risolto un problema che causava una chiusura imprevista dell'applicazione mentre si collaborava a un documento con altri utenti.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema per cui l'API impostazione nella libreria JavaScript di Office non funzionava in determinati scenari. [Altre informazioni](https://support.microsoft.com/help/4475551/august-6-2019-update-for-office-2016-kb4475551)

## <a name="version-1902-july-09"></a>Versione 1902: 9 luglio
*Versione 1902 (Build 11328.20368)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema di estrema lentezza nell'eliminazione di righe filtrate di Excel.
- È stato risolto un problema con lo scorrimento a due dita che disegnava rettangoli grigi sul foglio di lavoro bloccando Excel.


### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
- È stato risolto un problema che causava l’inserimento da parte di Outlook di lettere pinyin inglesi invece di mantenere aperta la finestra del candidato IME per consentire la selezione delle parole cinesi.
- È stato risolto un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.
- È stato risolto un problema che causava l’apertura della serie master se si tentava di aprire un’eccezione a una serie di riunioni.
- È stato risolto un problema che causava il calcolo errato delle date di scadenza per gli elementi contenuti nella cartella Posta eliminata.


### <a name="teams-non-security-updates"></a>Teams: aggiornamenti non relativi alla sicurezza

- Il programma di installazione di Teams ha ora dei criteri che consentono di disattivare l’avvio automatico al termine dell'installazione.


### <a name="visio-non-security-updates"></a>Visio: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema relativo alle soluzioni ActiveX per Visio che non funzionavano con Office 365, che restituiva un messaggio di errore per cui non era possibile trovare riched20.dll.


### <a name="word--non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza

- È stata corretta una impostazione dell’oggetto Criteri di gruppo che disabilitava la barra di ricerca del modello.
- È stato risolto un problema per cui gli utenti perdevano le modifiche apportate offline a un documento solo nel server.
- Prestazioni migliorate abilitando Parti rapide per le proprietà del documento.
- È stato risolto un problema per cui il primo download della revisione dal server poteva non riuscire


### <a name="office-suite--non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema per cui i dispositivi che usavano l'attivazione di computer condivisi ripristinavano l'attivazione basata sull’utente dopo l'installazione di prodotti Office aggiuntivi o Language Pack.
- È stato risolto un problema che impediva gli aggiornamenti di Office quando veniva eseguita l'autenticazione proxy come sistema.
- È stato risolto un problema per cui i componenti aggiuntivi di Office scomparivano con le modifiche al profilo utente.


## <a name="version-1902-june-11"></a>Versione 1902: 11 giugno
*Versione 1902 (Build 11328.20318)*
<br/>Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
 - È stato risolto un problema che causava un arresto anomalo durante il salvataggio in formato PDF di un file contenente un mapping XML.
 - È stato risolto un problema che causava la rimozione di collegamenti esterni durante il caricamento di cartelle di lavoro con nomi di foglio non validi.
 - È stato risolto un problema per cui quando si usava lo strumento Fotocamera in Excel poteva verificarsi un blocco del foglio di calcolo.
 - È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.
 - È stato risolto problema che causava un arresto anomalo quando si ricalcolava una tabella dati durante il calcolo del foglio di lavoro con una formula di matrice presente in un altro foglio dipendente dalla tabella. 
 - È stato risolto un problema che impediva di aprire da SharePoint cartelle di lavoro protette da password senza prima estrarre il file.
 - È stata apportata una modifica per assicurare che l'evento BeforeSave venga gestito durante la condivisione o l'attivazione del salvataggio automatico.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
 - È stato risolto un problema che causava la scomparsa delle attività dei clienti quando si aggiungeva una seconda condizione a "Raggruppa per".

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
 - È stato corretto un errore che causava la generazione di un allegato con estensione asd quando si condivideva un documento modificato in collaborazione.
 - È stato risolto un problema relativo ai commenti attribuiti ad autori casuali.
 - È stato risolto un problema relativo a Rimuovi firma durante l'estrazione di un documento.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
 - È stato risolto un bug in VBA per cui lo stato di riempimento della forma visualizzato non era corretto dopo un'azione di annullamento.


## <a name="version-1902-may-14"></a>Versione 1902: 14 maggio
*Versione 1902 (Build 11328.20286)*

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
 -  È stato risolto un problema per cui quando si usava lo strumento Fotocamera in Excel poteva verificarsi un blocco del foglio di calcolo.
 - È stato risolto un problema che causava un arresto anomalo durante lo scorrimento con la rotellina del mouse in una finestra inattiva contenente un foglio grafico.
 - È stato risolto un problema che causava la visualizzazione di un messaggio "Errore imprevisto" durante l'importazione di un foglio di calcolo in SharePoint.
 - È stato risolto un problema che causava l'arresto anomalo di Excel durante l'apertura di una cartella di lavoro contenente formattazione condizionale che usa un nome come regola e a cui è applicata una visualizzazione personalizzata.
 - Le macro che usano la convalida dei dati con formule contenenti più di 255 caratteri potevano generare errori in fase di esecuzione. Questo problema ora è stato corretto.
 - Un problema causava rallentamenti durante il caricamento di file contenenti tabelle pivot collegate a altre cartelle di lavoro. Questo problema è stato risolto.
 - È stato risolto un problema che si verificava all'apertura di file HTML e che causava la visualizzazione del messaggio di errore simile a "il formato e l'estensione del file non corrispondono".
 - È stata apportata una modifica per risolvere i problemi relativi allo scorrimento con la rotellina del mouse su finestre inattive.  

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
 - È stato risolto un problema che impediva ai clienti di poter modificare alcuni campi di elementi dei quali era stata eseguita la migrazione.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza
- Risolto un problema che in rari casi interrompeva il caricamento delle modifiche nel cloud in PowerPoint.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: aggiornamenti non relativi alla sicurezza
 - Risolto un problema in Lync (Skype for Business) per cui per le riunioni online con più di 7 partecipanti, la finestra della riunione poteva scomparire.
 - Accedere a Skype for Business con le credenziali utilizzate per accedere a un'altra applicazione di Office.
 - Attivare correttamente l’app Skype for Business quando è installata con attivazione di computer condivisi.

### <a name="visio-non-security-updates"></a>Visio: aggiornamenti non relativi alla sicurezza
 - Risolto un problema che causava l’interruzione della gerarchia delle finestre per l’estensione di Visio con soluzioni di terze parti, se si disabilitava la funzione dinamica DPI.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
 - È stato risolto un problema per cui la modifica di una persona correlata aggiunta da SharePoint poteva causare un arresto anomalo.
 - Risolto il problema della finestra di dialogo "Non è possibile caricare la risorsa" quando si avvia Word.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
 - Risolto un problema per cui non è possibile salvare i file nelle cartelle WebDAV di Apache.
 - Risolto un problema per cui Office si chiude improvvisamente all'apertura di alcuni file archiviati nel cloud da parte del cliente.
 - Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.
 - Risolto un problema per cui l'elenco dei file recenti risulta eliminato per molti utenti in Windows 10.
 - Risolto un problema che causava la visualizzazione di una barra di Office Update per l’utente finale anche se era in corso un aggiornamento generato da un amministratore.
 - Risolto un problema relativo alle istruzioni di accesso vuote e intermittenti.
 

## <a name="version-1902-april-9"></a>Versione 1902: 9 aprile
*Versione 1902 (Build 11328.20230)*

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza

- Risolto un problema per cui premendo il tasto TAB la selezione non passava alla cella successiva se conteneva una formula con un nome definito alla fine.
- Risolto un problema per cui la formattazione delle celle causava un inutile aumento delle dimensioni del file.
- Risolto un problema per cui l’operazione taglia e incolla di una tabella pivot tra cartelle di lavoro, comportava il trasferimento dei dati senza la tabella pivot condivisa con altri utenti.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza

- Risolto un problema per cui le finestre non venivano visualizzate nella posizione corretta quando la barra delle applicazioni del sistema era posizionata a sinistra o nella parte superiore dello schermo.
- Risolve un problema che determinava un arresto anomalo durante il caricamento di immagini nella scheda contatto.
- Risolve un problema che determinava un arresto anomalo all'avvio delle applicazioni di Office.
- Risolto un problema per cui le finestre non venivano visualizzate nella posizione corretta quando la barra delle applicazioni del sistema era posizionata a sinistra o nella parte superiore dello schermo.
- Risolve un problema che impediva ai clienti di poter modificare alcuni campi di elementi dei quali era stata eseguita la migrazione.

### <a name="visio-non-security-updates"></a>Visio: aggiornamenti non relativi alla sicurezza

- Risolto un problema che causava l’interruzione della gerarchia delle finestre per l’estensione di Visio con soluzioni di terze parti, se si disabilitava la funzione dinamica DPI.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza

- Risolto un problema di mancata visualizzazione dell'interfaccia di salvataggio che si verificava quando un file era aperto in sola lettura e si faceva clic su Salva con nome nel riquadro Informazioni.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza

- Risolto un problema per cui parti di un aggiornamento di Office non usavano il peer caching di Ottimizzazione recapito. [Altre informazioni](https://docs.microsoft.com/windows/deployment/update/waas-delivery-optimization)
- Risolto un bug che portava alla rimozione o alla mancata attivazione dei prodotti, se Office veniva installato tramite lo strumento di distribuzione e si verificava un errore di corrispondenza maiuscole/minuscole.
- Risolto un problema che causava un numero eccessivo di richieste di accesso nei dispositivi Windows 10 (1803 o versioni successive).
- Risolto un problema di regressione che causa blocchi durante il download di immagini collegate.
- Risolto un problema di sfocatura dei file EMF di grandi dimensioni incollati in Word, Excel e PowerPoint.
- Risolto il bug nella logica di analisi della cronologia delle versioni che in alcuni casi determinava l'apertura dei documenti in sola lettura.

## <a name="version-1902-march-12"></a>Versione 1902: 12 marzo
*Versione 1902 (Build 11328.20158)*

### <a name="access-feature-updates"></a>Access: aggiornamenti delle funzionalità

- **Aggiornare, ricollegare o rimuovere tabelle collegate:** la versione aggiornata di Gestione tabelle collegate è la posizione per la gestione di tutte le origini dati e tabelle collegate. [Altre informazioni](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)
- **Dipingi di nero, dipingi di grigio:** cambiare l'aspetto di Access ogni volta che si desidera. Quattro temi tra cui scegliere: A colori, Nero, Grigio e Bianco. [Altre informazioni](https://support.office.com/article/9d76a8b4-bfff-48a9-b8c8-8e133461bc94)
- **Nuovo look di Office:** le app di Office ora sono caratterizzate da icone moderne più semplici e accessibili, mentre nella barra multifunzione sono presenti oggetti visivi aggiornati che evidenziano le potenti funzionalità di collaborazione disponibili nelle app di Office.

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Iniziare più rapidamente** La pagina iniziale ridisegnata pone in primo piano i documenti aperti di recente. Si potrà accedere ai file con meno clic e aprire le opzioni o le impostazioni account direttamente da questa posizione.
- **Collaborare con i commenti:** mantenere la conversazione nel proprio foglio di calcolo con la casella di risposta integrata. [Altre informazioni](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)
- **Le icone della barra multifunzione hanno un nuovo aspetto**, ma non c'è da temere, perché tutto funziona come sempre. Inoltre, verranno visualizzate perfettamente su schermi di qualsiasi dimensione. [Altre informazioni](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Mostrare cosa c'è dietro un'immagine:** inserire un'immagine in un foglio di lavoro, selezionare l'impostazione predefinita e osservare la modifica nella trasparenza. È tutto! [Altre informazioni](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Sostenitori delle funzionalità per chiamare tutti e di visualizzazione e trasformazione:** chi usa spesso la funzionalità di visualizzazione e trasformazione, sarà lieto di apprendere che Colonna da esempi è stata migliorata. Inoltre, sono stati migliorati anche molti connettori. [Altre informazioni](https://support.office.com/article/ed01ec34-679d-48e7-ba49-bb14c7908f9e)
- **Supporto migliorato per schermi ad alta definizione:** se si usano più monitor o un portatile, ora le app di Office appaiono nitide su ogni schermo, anche se gli schermi hanno impostazioni di ridimensionamento diverse. [Altre informazioni](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Ricerca rapida** CERCA.VERT, CERCA.ORIZZ e CONFRONTA sono state implementate per trovare più rapidamente le risposte. [Altre informazioni](https://support.office.com/article/60f18521-2589-4734-89dd-ba4ee1f6c000)

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Ascoltare il testo del messaggio di posta elettronica con Leggi ad alta voce**: Outlook è in grado di leggere i messaggi di posta elettronica ad alta voce, evidenziando il testo durante la lettura. Per attivare Leggi ad alta voce, passare alle impostazioni Accessibilità. [Altre informazioni](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Digita in vivavoce:** se si ha un microfono, è possibile fare clic su Dettatura e osservare Outlook digitare mentre si parla. [Altre informazioni](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Le icone della barra multifunzione hanno un nuovo aspetto**, ma non c'è da temere, perché tutto funziona come sempre. Inoltre, verranno visualizzate perfettamente su schermi di qualsiasi dimensione. [Ulteriori informazioni](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Bloccare il download di contenuti esterni per impostazione predefinita nei messaggi di posta elettronica con firma e crittografia SMIME:** a causa di una vulnerabilità nel protocollo SMIME, Outlook bloccherà il download dei contenuti esterni sui messaggi che sono stati firmati o crittografati tramite SMIME. Per evitare la vulnerabilità di sicurezza, gli utenti non potranno scaricare con un singolo clic i contenuti esterni tramite l'interfaccia utente di Outlook. È presente una nuova opzione nella finestra di dialogo Opzioni che consente agli utenti di ripristinare il comportamento precedente.
- **Disattivare l'inoltro per una riunione:** per impedire ai partecipanti di inoltrare la riunione ad altri utenti. basta andare sulla barra multifunzione e fare clic su Opzioni di risposta. [Ulteriori informazioni](https://support.office.com/article/5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F)
- **Utenti suggeriti dall'Assistente Pianificazione:** visualizzare i partecipanti suggeriti quando si pianifica una riunione. Non è più necessario passare continuamente dall'Assistente Pianificazione alla riga A. [Altre informazioni](https://support.office.com/article/d284c6d9-206e-4926-92b4-5addc0fcbefb)
- **Maggiore facilità nella prenotazione delle sale:** cercare una sala riunioni utilizzando più di un elenco di sale e passare da un elenco all'altro senza perdere le sale selezionate.
- **Nuovo valore predefinito per l'intervallo di ricorrenza:** per la finestra di dialogo Ricorrenza, l'intervallo di ricorrenza predefinito era "Nessuna data di fine". Questo consentiva di creare una serie ricorrente di lunga durata, che nel tempo potrebbe danneggiarsi. Il valore predefinito per la finestra di dialogo è stato modificato in "Fine entro", in modo da allineare il valore predefinito alle procedure consigliate per la gestione dei calendari.
- **Partecipare alle riunioni di Teams dalla finestra di dialogo Promemoria di Outlook:** quando Outlook ricorda agli utenti una riunione imminente, mostra il pulsante Partecipa a riunione online se la riunione imminente è una riunione online di Teams. L'esperienza è analoga alla partecipazione a una riunione di Skype for Business dalla finestra di dialogo Promemoria di Outlook.
- **Nascondere i promemoria per gli eventi passati:** è possibile impostare il calendario per eliminare automaticamente i promemoria relativi ad eventi passati. [Ulteriori informazioni](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Visualizzare l'URL dei collegamenti sicuri:** i collegamenti sicuri proteggono l'utente dagli URL dannosi ricevuti tramite posta elettronica, ma nascondono l'URL originale. Per vedere l'originale, passare il puntatore del mouse sull'URL. Richiede una licenza Advanced Threat Protection. [Altre informazioni](https://products.office.com/exchange/advance-threat-protection)
- **Scegliere e applicare lo zoom:** invece di modificare lo zoom ogni volta che si legge un messaggio, scegliere un'impostazione predefinita da usare per tutti i messaggi. [Altre informazioni](https://support.office.com/article/56c090bc-e148-44a7-bd06-1290edd38983)
- **Crittografia dei messaggi: criteri IRM per la sola crittografia:** la nuova opzione Solo crittografia è disponibile nel menu Opzioni > Autorizzazioni per gli utenti di Office 365 Message Encryption. Questa opzione consente di crittografare un messaggio e inviarlo a chiunque, all'interno o all'esterno dell'organizzazione.
- **Messaggio di avviso per i contatti in copia nascosta:** la finestra popup per la copia nascosta avvertirà prima che si risponda inavvertitamente a un messaggio di posta elettronica in cui si è in copia nascosta.
- **Riga A: più intelligente:** quando si fa clic sulla riga A: per indicare il destinatario di un messaggio, vengono suggeriti alcuni nomi tra cui scegliere. Inoltre, è possibile visualizzare la loro foto come ulteriore conferma di aver selezionato la persona giusta. [Altre informazioni](https://support.office.com/article/147208AF-CA8E-4CDF-B71F-77BA81A54069)
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Supporto migliorato per schermi ad alta definizione:** se si usano più monitor o un portatile, ora le app di Office appaiono nitide su ogni schermo, anche se gli schermi hanno impostazioni di ridimensionamento diverse. [Altre informazioni](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Iniziare più rapidamente** La pagina iniziale ridisegnata pone in primo piano i documenti aperti di recente. Si potrà accedere ai file con meno clic e aprire le opzioni o le impostazioni account direttamente da questa posizione.
- **Digita in vivavoce:** se si ha un microfono, Fare clic su Dettatura e osservare PowerPoint digitare mentre si parla. [Altre informazioni](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Le icone della barra multifunzione hanno un nuovo aspetto**, ma non c'è da temere, perché tutto funziona come sempre. Inoltre, verranno visualizzate perfettamente su schermi di qualsiasi dimensione. [Altre informazioni](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Supporto migliorato per schermi ad alta definizione:** se si usano più monitor o un portatile, ora le app di Office appaiono nitide su ogni schermo, anche se gli schermi hanno impostazioni di ridimensionamento diverse. [Altre informazioni](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Collegamenti ipertestuali a colori:** i collegamenti ipertestuali non sono solo più blu. Ora si può applicare qualsiasi colore del carattere. [Altre informazioni](https://support.office.com/article/988ed94c-82e9-4e2c-96a1-7ffd2c382ce8)
- **Guardare le diapositive prendere vita:** inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex sullo schermo. [Altre informazioni](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **I bozzetti vengono rielaborati:** testi e forme disegnati a mano vengono ridisegnati in diagrammi sofisticati. Basta selezionare i tratti input penna per iniziare. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Mostrare cosa c'è dietro un'immagine:** inserire un'immagine in un foglio di lavoro, selezionare l'impostazione predefinita e osservare la modifica nella trasparenza. È tutto! [Altre informazioni](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Pubblicare in Microsoft Stream:** è possibile condividere una presentazione come un video in modo più sicuro all'interno dell'organizzazione tramite Microsoft Stream. [Altre informazioni](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Esportare in video 4K:** ora è possibile esportare una presentazione in formato video con risoluzione 4K.  [Altre informazioni](https://support.office.com/article/c140551f-cb37-4818-b5d4-3e30815c3e83)
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **L'apertura di file di grandi dimensioni è ora più veloce:** immagini, video e altri elementi di grandi dimensioni vengono ora scaricati in background quando si aprono file archiviati in OneDrive o SharePoint.

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Iniziare più rapidamente** La pagina iniziale ridisegnata pone in primo piano i documenti aperti di recente. Si potrà accedere ai file con meno clic e aprire le opzioni o le impostazioni account direttamente da questa posizione.
- **Digita in vivavoce:** se si ha un microfono, Fare clic su Dettatura e osservare Word digitare mentre si parla. [Altre informazioni](https://support.office.com/article/d4fd296e-8f15-4168-afec-1f95b13a6408)
- **Guardare i documenti prendere vita:** inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella pagina. [Altre informazioni](https://support.office.com/article/ad6ade3a-be41-4cf1-b761-46dcfd14dfc8)
- **Le icone della barra multifunzione hanno un nuovo aspetto**, ma non c'è da temere, perché tutto funziona come sempre. Inoltre, verranno visualizzate perfettamente su schermi di qualsiasi dimensione. [Ulteriori informazioni](https://support.office.com/article/c6bc4cd8-d151-41d3-8276-fc7c9975eb79)
- **Mostrare cosa c'è dietro un'immagine:** inserire un'immagine in un foglio di lavoro, selezionare l'impostazione predefinita e osservare la modifica nella trasparenza. È tutto! [Altre informazioni](https://support.office.com/article/ea62f9bf-f0ee-4b64-bcc5-c49275bf350d)
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Supporto migliorato per schermi ad alta definizione:** se si usano più monitor o un portatile, ora le app di Office appaiono nitide su ogni schermo, anche se gli schermi hanno impostazioni di ridimensionamento diverse. [Altre informazioni](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)
- **Scrivere il miglio CV con l'aiuto di LinkedIn:** Con Assistente curriculum, è possibile visualizzare le esperienze di lavoro, le competenze suggerite e altro per una data posizione. [Altre informazioni](https://support.office.com/article/444ff6f0-ef74-4a9c-9091-ffd7a9d1917a)

### <a name="project-feature-updates"></a>Project: Aggiornamenti delle funzionalità

- **Visualizzare ulteriori informazioni sulle schede della lavagna delle attività:** quando il titolo da solo non è esplicativo, è possibile personalizzare le schede della lavagna delle attività per mostrare tutti i dettagli più importanti. [Altre informazioni](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)
- **Nuovo look di Office:** le app di Office ora sono caratterizzate da icone moderne più semplici e accessibili, mentre nella barra multifunzione sono presenti oggetti visivi aggiornati che evidenziano le potenti funzionalità di collaborazione disponibili nelle app di Office.

### <a name="publisher-feature-updates"></a>Publisher: aggiornamenti delle funzionalità

- **Nuovo look di Office:** le app di Office ora sono caratterizzate da icone moderne più semplici e accessibili, mentre nella barra multifunzione sono presenti oggetti visivi aggiornati che evidenziano le potenti funzionalità di collaborazione disponibili nelle app di Office.

### <a name="visio-feature-updates"></a>Visio: aggiornamenti delle funzionalità

- **Usare un determinato momento nel diagramma successivo:** è possibile scegliere tra 26 nuovi stencil con le icone per analisi, arte, celebrazioni, facce, sport e altro ancora.
- **Nuovo look di Office:** le app di Office ora sono caratterizzate da icone moderne più semplici e accessibili, mentre nella barra multifunzione sono presenti oggetti visivi aggiornati che evidenziano le potenti funzionalità di collaborazione disponibili nelle app di Office.

### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: aggiornamenti delle funzionalità

- **Possibilità di inserire il supporto per SVG tramite le applicazioni di terze parti per Office con l'API Office.js:** le applicazioni di terze parti, note anche come componenti aggiuntivi in Office, ora possono inserire SVG. Gli utenti possono connettere la propria raccolta personale di SVG a Office, mentre gli sviluppatori possono usare l'API Office.js per implementare questa funzionalità.
- **Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle installazioni esistenti di Office 365 ProPlus. [Altre informazioni](https://docs.microsoft.com/DeployOffice/teams-install)

### <a name="skype-for-business-feature-updates"></a>Skype for Business: aggiornamenti delle funzionalità

- **Supporto migliorato per schermi ad alta definizione:** se si usano più monitor o un portatile, ora le app di Office appaiono nitide su ogni schermo, anche se gli schermi hanno impostazioni di ridimensionamento diverse. [Altre informazioni](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

### <a name="teams-feature-updates"></a>Teams: aggiornamenti delle funzionalità

- **Supporto migliorato per schermi ad alta definizione:** se si usano più monitor o un portatile, ora le app di Office appaiono nitide su ogni schermo, anche se gli schermi hanno impostazioni di ridimensionamento diverse. [Altre informazioni](https://support.office.com/article/6720ca0e-be59-41f6-b629-1369f549279d)

## <a name="version-1808-february-12"></a>Versione 1808: 12 febbraio
*Versione 1808 (Build 10730.20280)* 

### <a name="access-non-security-updates"></a>Access: aggiornamenti non relativi alla sicurezza 

- Questo aggiornamento aggiunge ad Access il supporto per le nuove ere giapponesi.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza 

- Risolve un problema a causa del quale viene visualizzato un errore quando gli utenti con regole che fanno riferimento a una cartella che non esiste più provano a gestire le regole e a causa del quale le regole lato client non vengono eseguite.
- Risolve un problema a causa del quale si verificano blocchi frequenti a intervalli imprevedibili per gli utenti con cassette postali delegate memorizzate nella cache.
- Risolve un problema a causa del quale in alcune viste le riunioni giornata intera includono un giorno in più del previsto a causa dell'ora di fine della riunione impostata sulla mezzanotte del giorno successivo.
- È stato risolto un blocco durante la creazione di nuovi appuntamenti o nuove riunioni che fanno riferimento a ere giapponesi.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza

- È stato risolto il problema per cui i componenti aggiuntivi distribuiti con la [distribuzione centralizzata di Office 365](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment) vengono bloccati e sono inutilizzabili.


## <a name="version-1808-january-8"></a>Versione 1808: 8 gennaio
*Versione 1808 (Build 10730.20264)* 

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza 

- Risolto un problema che causava errori di sincronizzazione del calendario.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza

- Migliorare le prestazioni di apertura.

## <a name="version-1808-december-11"></a>Versione 1808: 11 dicembre
*Versione 1808 (Build 10730.20262)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8597): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8598): vulnerabilità della divulgazione delle informazioni di Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8627): vulnerabilità della divulgazione delle informazioni di Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8636): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8587): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti della sicurezza 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8628): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft PowerPoint 

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza 

- Risolto un problema nelle sessioni di creazione condivisa in cui un filtro dei dati non veniva aggiornato correttamente dopo l’applicazione da parte di un altro utente di un filtro di colonna per i dati in quel filtro dei dati.
- Risolto un problema per il quale, quando un utente cancellava la didascalia di un filtro dei dati in una sessione di creazione condivisa, si verificava un arresto anomalo di Excel per un altro utente.
- Risolto un possibile arresto anomalo durante la creazione di più filtri dei dati nella tabella associati alla stessa colonna di dati e la successiva eliminazione di quella colonna di dati.
- Risolto un problema che causava, a volte, un arresto anomalo di Excel durante l'aggiornamento di una tabella Query filtrata contenente il testo con ritorno a capo automatico nelle celle quando l'opzione per modificare automaticamente la larghezza delle colonne era disattivata.
- Risolto un problema in cui i filtri dei dati salvati in Excel 2007 potevano attivare un arresto anomalo se aperti in versioni più recenti di Excel quando il numero di elementi visualizzati nel filtro dei dati era diverso.
- Introduce il supporto per il pulsante di diagnostica per semplificare l'analisi delle richieste di supporto.

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non relativi alla sicurezza

- Risolto un problema che causava la visualizzazione di un messaggio di errore all'avvio della finestra di dialogo "Gestisci regole e avvisi".
- Risolto un problema che impediva agli utenti di connettersi alle cassette postali tramite DirectAccess utilizzando una connessione a consumo.
- Risolto un problema che causava un’apertura erronea in "Visualizzazione protetta" di documenti liberi archiviati nelle cartelle pubbliche.
- Risolto un problema per il quale gli utenti visualizzavano allegati non previsti quando inoltravano messaggi con allegati in linea.
- Risolto un problema che causava il rendering non corretto di file OFT inviati come allegato.
- Risolto un problema che causava arresti anomali per alcuni utenti di componenti aggiuntivi quando si aggiungeva una riunione a un calendario condiviso.
- Risolto un problema che causava blocchi all’apertura della cartella Cronologia conversazioni.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non relativi alla sicurezza

- Risolto un problema riguardante il supporto di una nuova valuta venezuelana in Project.
- Risolto un problema per il quale era possibile un blocco di Project quando si usava un Surface 4 connesso a un monitor esterno.
- Risolto un problema per il quale era possibile un arresto anomalo di Project quando si salvava un progetto in formato XML.
- Risolto un problema per il quale era possibile l’eliminazione dei campi personalizzati delle risorse dell’organizzazione dopo la modifica del calendario della risorsa.
- Risolto un problema che causava arresti anomali durante la ricerca di nomi visualizzati coreani.

## <a name="version-1808-november-13"></a>Versione 1808: 13 novembre
*Versione 1808 (Build 10730.20205)*

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8574): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8577): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8522): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8524): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8558): vulnerabilità della divulgazione delle informazioni relative a Microsoft Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8576): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8579): vulnerabilità della divulgazione delle informazioni relative a Microsoft Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8582): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 

### <a name="project-security-updates"></a>Project: aggiornamenti della sicurezza 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8575): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8573): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype for Business: aggiornamenti della sicurezza 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8546): vulnerabilità relativa alla sospensione del servizio in Microsoft Skype for Business 

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza 

- Corretto un bug che non consentiva la visualizzazione di PowerPivot in alcuni build/versioni.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza 

- Risolto un problema che non consentiva agli utenti di usare correttamente il pulsante di controllo Account per spostarsi tra gli account nei moduli personalizzati.
- Risolto un problema che causava un arresto anomalo quando si utilizzava ScanPST per ripristinare un file OST/PST.
- Risolto un problema che non consentiva di visualizzare il campo Cc in alcuni messaggi di posta elettronica per utenti con profili in modalità online.

### <a name="onenote-non-security-updates"></a>OneNote: aggiornamenti non relativi alla sicurezza 

- Risolto un possibile problema di stabilità che coinvolge la sincronizzazione e l’accesso a una sezione eliminata.

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza 

- Risolto un problema per il quale se l’utente lavorava con file di Project in una raccolta documenti di SharePoint nella nuova esperienza moderna, le azioni Estrazione necessaria e Sola lettura non venivano applicate correttamente.


## <a name="version-1808-october-9"></a>Versione 1808: 9 ottobre
*Versione 1808 (Build 10730.20155)*

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8502): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza 
-   [ADV180026](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV180026): aggiornamento difensivo Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint: aggiornamenti della sicurezza 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8501): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft PowerPoint

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8504): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV180026): aggiornamento difensivo Microsoft Office 

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8432): vulnerabilità relativa all'esecuzione di codice remoto del componente di Microsoft Graphics 

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza 
-   Risolto il problema che si verificava quando i simboli nell'intervallo tra 2190 e 2194 passavano a Cambria Math e che faceva aumentare di 3 volte l’altezza della cella di Excel.
-   Risolve il problema in Excel per il quale Excel potrebbe non rispondere quando l’utente passa il puntatore del mouse sulle opzioni di formattazione in una cartella di lavoro con molti nomi definiti, e per il quale Excel potrebbe non rispondere nello strumento di Analisi rapida anche quando l’anteprima dinamica è disabilitata nelle opzioni.
-   Stiamo analizzando un rallentamento delle prestazioni quando si sposta la finestra dell'applicazione Excel da un desktop a un altro. Nel frattempo, se si nota questa lentezza, una soluzione da considerare consiste nel selezionare "Ottimizza compatibilità" per "Quando si usano più schermi" nella scheda "Generale" nella finestra di dialogo Opzioni file.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza
-   Risolto un problema di potenziali danneggiamenti di file durante il salvataggio di file con contenuto ActiveX.

### <a name="word-non-security-updates"></a>Word: aggiornamenti non relativi alla sicurezza
-   Risolto un problema per il quale quando si inseriva un oggetto documento di Word, veniva visualizzato equation editor.

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza
-   Risolto un problema per il quale se si impostava un'intestazione o un piè di pagina per una stampa, la modifica non era mantenuta nella stampa successiva del progetto.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
-   Risolto un problema delle applicazioni che mostravano le animazioni anche se queste erano state disabilitate nelle impostazioni di accessibilità e prestazioni. 
-   Risolto un problema che mandava in bianco lo sfondo quando si usava lo strumento di disegno evidenziatore.

## <a name="version-1808-september-11"></a>Versione 1808: 11 settembre
*Versione 1808 (Build 10730.20102)*

### <a name="access-feature-updates"></a>Access: aggiornamenti delle funzionalità
 - **Visualizzazione di dati con nuovi grafici**: scegliere tra 11 grafici e aggiungerne uno a maschere e report per visualizzare meglio i dati e prendere decisioni informate. [Ulteriori informazioni](https://support.office.com/article/1a463106-65d0-4dbb-9d66-4ecb737ea7f7)
 
 ### <a name="access-security-updates"></a>Access: Aggiornamenti della sicurezza
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8312): vulnerabilità di tipo use-after-free relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità
 - **Modifica collaborativa:** collaborare con altri utenti contemporaneamente all'interno della cartello di lavoro. [Altre informazioni](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **Il salvataggio automatico di file nel cloud è ora abilitato per impostazione predefinita:** il salvataggio automatico è attivato per impostazione predefinita nel rilascio del canale semestrale (mirato) di settembre 2018. Ciò significa che gli utenti non dovranno più preoccuparsi di perdere le modifiche nei documenti archiviati in OneDrive o SharePoint Online. Le modifiche vengono salvate automaticamente nel cloud e gli utenti non dovranno più premere esplicitamente CTRL+S o il pulsante Salva. Tuttavia, è necessario comprendere questa modifica al comportamento in modo da non apportare modifiche accidentali ai documenti. Si noti che gli utenti possono disattivare il salvataggio automatico con l'interruttore Salva automaticamente posto nella parte superiore dello schermo. È consigliabile comunicare ai propri utenti questa modifica imminente e fornire loro informazioni su come sfruttare al meglio questa nuova funzionalità in Office 365. [Altre informazioni sul salvataggio automatico](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Altre informazioni su cosa è importante che gli amministratori IT sappiano sul salvataggio automatico](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Cella e barra della formula per apportare modifiche migliorate:** è ora possibile usare CTRL+A per selezionare il testo in una cella o nella barra della formula. È stato anche migliorato il supporto di emoji e caratteri complessi. [Altre informazioni](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Miglioramenti di Verifica accessibilità:** Verifica accessibilità ha ricevuto aggiornamenti relativi al supporto per gli standard internazionali e consigli per rendere più accessibili le cartelle di lavoro. [Altre informazioni](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitare modifiche indesiderate:** Impostare l’apertura in modalità sola lettura delle cartelle di lavoro per impedire modifiche accidentali. Passare a File > informazioni > Proteggi cartella di lavoro > Apri sempre in sola lettura

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8331): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8429): vulnerabilità relativa alla divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8375): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8379): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8382): vulnerabilità relativa alla divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8246): vulnerabilità della divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8248): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8147): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8148): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8162): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8163): vulnerabilità della divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-1029): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Risolve un problema per il quale Excel potrebbe arrestarsi in modo anomalo quando si modificano i dati di origine del grafico dal set di celle originale.
-   Risolve un problema per il quale il ricalcolo potrebbe non verificarsi all’apertura anche se è impostata la proprietà FullCalcOnLoad.  
-   Consente di correggere un problema a causa del quale viene visualizzato l'anno errato quando si utilizza il calendario giapponese nel formato cella data.
-   Quando si importano i dati nel modello di dati di Excel, i valori zero negativo in ingresso danno origine a un errore. La correzione consente ora di importare tali valori come zero.
-   Consente di correggere un problema a causa del quale a volte un'operazione di raggruppamento (o di annullamento del raggruppamento) in una tabella pivot di Excel potrebbe provocare un arresto anomalo.
-   Consente di risolvere un problema in cui le azioni relative ai grafici potrebbero causare un arresto anomalo di Excel.
-   Consente di risolvere un problema a causa del quale un componente aggiuntivo Power View viene inavvertitamente disattivato per alcuni utenti.
-   Consente di risolvere un problema a causa del quale i file temporanei creati tramite il ripristino automatico durante il recupero di un documento non vengono mai eliminati.
-   Risolvere un problema in cui un tentativo di creare una nuova connessione ad un file di testo in una cartella di lavoro protetta genera il messaggio di errore "La cartella di lavoro è protetta e non può essere modificata".
-   Consente di risolvere un problema in cui la stampa immediata di una cartella di lavoro di Excel allegata a un messaggio di posta elettronica di Outlook potrebbe non essere stampata.
-   Consente di risolvere un problema per cui fare clic su un collegamento ipertestuale può causare un arresto anomalo di Excel.
-   Consente di risolvere un problema per cui l'utilizzo di funzioni cubo causa un arresto anomalo di Excel.

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità
 - **Miglioramenti di Verifica accessibilità:** Verifica accessibilità ha ricevuto aggiornamenti relativi al supporto per gli standard internazionali e consigli per rendere più accessibili i messaggi. [Altre informazioni](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
 - **Gestire i profili dalla Selezione profilo:** se si utilizza la Selezione profilo all'avvio di Outlook, è possibile apportare modifiche senza passare al pannello di controllo. In Selezione profilo è possibile creare ed eliminare profili e modificare le impostazioni.
- **Accessibilità integrata:** rendere accessibile a tutti i messaggi con l'aggiunta di un testo alternativo descrittivo alle immagini.
- **Avvisi relativi ai componenti aggiuntivi di Outlook:** occasionalmente un componente aggiuntivo COM di Outlook può incontrare problemi che rallentano il resto di Outlook. Questi problemi potrebbero essere dovuti alla latenza di eventi quali il passaggio tra cartelle di Outlook, l'arrivo di nuove e-mail, l'apertura di elementi del Calendario e così via. Quando si verificano tali problemi, Outlook visualizza un avviso nella barra di notifica.
- **Conoscere i partecipanti della riunione:** è ora possibile visualizzare le risposte di altri utenti a una convocazione riunione, anche se non si è l'organizzatore.
- **Non perdere nessun promemoria:** è possibile impostare l'apertura di pop up relativi ai promemoria nelle finestre in esecuzione oppure Outlook lampeggerà sulla barra delle applicazioni per attirare l'attenzione dell'utente. [Altre informazioni](https://support.office.com/article/7a992377-ca93-4ddd-a711-851ef3597925)
- **Contrassegnare gli elementi eliminati come già letti:** è ora possibile impostare tutti i messaggi eliminati come già letti. Scegliere facendo clic su File \> Opzioni \> Posta \> Altro.
- **Visualizzazione di tre fusi orari:** se si deve pianificare una riunione in fusi orari diversi, basta aggiungere più fusi orari al calendario per visualizzare facilmente la disponibilità di tutti i partecipanti e l'orario adatto a tutti. [Altre informazioni](https://support.office.com/article/5ab3e10e-5a6c-46af-ab48-156fedf70c04)
- **Perfezionata l’esperienza utente per la creazione di un gruppo:** abbiamo perfezionato l’esperienza utente per la creazione di un gruppo per ottenere un aspetto più moderno e ordinato.[ Altre informazioni](https://support.office.com/article/04d0c9cf-6864-423c-a380-4fa858f27102)

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8310): vulnerabilità relativa alla manomissione di Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8244): vulnerabilità relativa all'elevazione di privilegi in Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8150): le funzionalità di sicurezza di Microsoft Outlook ignorano la vulnerabilità
-   [ADV180021](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV180021): aggiornamento difensivo Microsoft Office

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza
-   Risolve un problema per il quale se si cambia la lingua del sistema in giapponese e si tenta di digitare caratteri giapponesi in IDE di VBA quando caricato in Outlook, si blocca.
-   Consente di risolvere un problema a causa del quale, quando si passa ad Outbox o alla cartella Posta inviata, Outlook si arresta in modo anomalo.
-   Consente di risolvere un errore a causa del quale tutti i partecipanti ricevono aggiornamenti sulla riunione quando vengono apportate delle modifiche agli allegati e al corpo della riunione, mentre l'invio di un aggiornamento della riunione ai partecipanti è facoltativo.
-   Consente di risolvere un problema a causa del quale gli utenti non sono in grado di connettersi agli endpoint EWS e REST a causa di una modifica nella stringa agente utente.
-   Consente di risolvere un problema in cui un aggiornamento della sede della riunione per i partecipanti mostra la vecchia posizione anziché la nuova.
-   Consente di risolvere un problema in cui l'utente riceve un messaggio di errore durante l'anteprima di un allegato nel riquadro di lettura.
-   Consente di risolvere un problema per cui Outlook si blocca durante la risoluzione dei nomi visualizzati per gli indirizzi di posta elettronica quando l'utente compone un messaggio di posta elettronica.
-   Consente di risolvere un problema per cui alcuni utenti non ricevono funzionalità di supporto che sono state abilitate dall’amministratore tenant.

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità 
- **Il salvataggio automatico di file nel cloud è ora abilitato per impostazione predefinita:** il salvataggio automatico è attivato per impostazione predefinita nel rilascio del canale semestrale (mirato) di settembre 2018. Ciò significa che gli utenti non dovranno più preoccuparsi di perdere le modifiche nei documenti archiviati in OneDrive o SharePoint Online. Le modifiche vengono salvate automaticamente nel cloud e gli utenti non dovranno più premere esplicitamente CTRL+S o il pulsante Salva. Tuttavia, è necessario comprendere questa modifica al comportamento in modo da non apportare modifiche accidentali alle presentazioni. Si noti che gli utenti possono disattivare il salvataggio automatico con l'interruttore Salva automaticamente posto nella parte superiore dello schermo. È consigliabile comunicare ai propri utenti questa modifica imminente e fornire loro informazioni su come sfruttare al meglio questa nuova funzionalità in Office 365. [Altre informazioni sul salvataggio automatico](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Altre informazioni su cosa è importante che gli amministratori IT sappiano sul salvataggio automatico](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Convertire l'input penna:** è possibile creare disegni e note a mano libera e convertirli in testo leggibile e forme nitide per creare una presentazione professionale. [Altre informazioni](https://support.office.com/article/8ca00db0-4342-4bde-bbb2-92d6cb5e2e45)
- **Supporto SVG migliorato:** è ora possibile inserire SVG con filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **Indicare le diapositive con una penna:** utilizzare la penna per evidenziare un titolo, PowerPoint lo convertirà poi in testo. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Evitare modifiche indesiderate:** Impostare l’apertura in modalità sola lettura delle cartelle di lavoro per impedire modifiche accidentali. Passare a File > informazioni > Proteggi cartella di lavoro > Apri sempre in sola lettura
- **Miglioramenti di Verifica accessibilità:** Verifica accessibilità ha ricevuto aggiornamenti relativi al supporto per gli standard internazionali e consigli per rendere più accessibili le presentazioni. [Altre informazioni](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale il rendering delle tabelle non è eseguito correttamente con i bordi spessi.
-   Consente di correggere un problema a causa del quale potrebbe verificarsi un arresto anomalo durante la modifica della proprietà Shape.Visible.
-   Consente di correggere un problema a causa del quale le modifiche nei documenti creati in modalità condivisa non si uniscono.
-   Consente di correggere un problema a causa del quale non sarebbe possibile la creazione condivisa di documenti contenenti controlli ActiveX.
-   Consente di risolvere un problema a causa del quale la correzione ortografica nelle forme causa l'arresto anomalo di PowerPoint.
-   Consente di risolvere un problema a causa del quale PowerPoint si arresta in modo anomalo quando si apre un file da SharePoint Online.
-   Consente di risolvere un problema a causa del quale il riquadro con le informazioni sul file recuperato viene visualizzato in modo errato quando è attivo Salvataggio automatico.
-   Consente di risolvere un problema a causa del quale l'accesso non viene visualizzato impedendo a un utente di accedere a un file.
-   Consente di risolvere un problema a causa del quale la creazione condivisa da parte di più utenti sulla stessa presentazione comporta una duplicazione errata degli schemi diapositiva.
-   Consente di risolvere un problema a causa del quale l'apertura di un file salvato su OneDrive comporta l'arresto anomalo di PowerPoint all'uscita dalla visualizzazione protetta.

### <a name="project-feature-updates"></a>Project: Aggiornamenti delle funzionalità 
- **Gestione di sprint:** aggiungere, aggiornare o eliminare velocemente sprint agili.
- **Filtro della scheda attività:** è possibile ottimizzare le schede attività, filtrando per risorse principali o attività di riepilogo.
- **Impostare la percentuale di completamento da una scheda attività:** è possibile scegliere una percentuale di completamento per ogni colonna e quindi aggiornare il completamento dell'attività con trascinamento della selezione.
- **Navigazione sprint:** è possibile passare da una vista sprint all'altra e spostare rapidamente le attività tra sprint.
- **Un nuovo metodo per gestire gli sprint:** adottare un approccio diretto nell'utilizzo delle bacheche attività. Accedendo a Gestisci sprint, è possibile aggiungere e rimuovere gli sprint mentre si sta lavorando a un progetto.
- **Organizzazione dei percorsi di salvataggio recenti:** Project mantiene un elenco in esecuzione dei progetti salvati. Quando si decide di salvare un progetto, scegliere uno dei percorsi di salvataggio recenti e proseguire con il lavoro.

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza
- Consente di correggere un problema a causa del quale non è possibile salvare un sottoprogetto mentre si lavora su di esso attraverso il contesto di un progetto principale.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Risolve un problema relativo al servizio di supporto TLS 1.2. (nota: è la stessa correzione riportata nelle note del 10 aprile e indicata qui nuovamente nell'ambito dell'aggiornamento cumulativo di settembre.)
-   Consente di risolvere un problema per cui l'aggiunta degli utenti selezionando "Chiamata Skype" in una riunione causa un errore.
-   Consente di rimuovere un'istruzione che richiede all'utente di aggiungere le coordinate Skype a una riunione, se viene aggiunta una Skype Room come posizione e la riunione già contiene le coordinate della riunione dei team.
-   Consente di risolvere un problema per cui la posizione viene popolata anche se UseLocationForE911Only è impostato su true.
-   Consente di risolvere un problema per cui Skype for Business si blocca quando si usa l'opzione "chiamata tramite il centro conferenze" per invitare gli utenti dall'elenco dei partecipanti.
-   Consente di risolvere un problema per cui Outlook in esecuzione su un server si blocca durante la creazione di una riunione di Skype for Business.
-   Modificare il valore predefinito di EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket su TRUE.

### <a name="visio-feature-updates"></a>Visio: aggiornamenti delle funzionalità
- **Sincronizzare il diagramma di origine:** Quando si modifica un diagramma visualizzatore dati in Visio, è possibile aggiornare i dati di origine di Excel collegati con il contenuto del diagramma più recente.
- **Modello di audit del Visualizzatore dati:** importare il contenuto da Excel e creare diagrammi di audit per transazioni finanziarie, gestione dell'inventario e altro ancora.
- **Diagrammi di base:** i modelli di organigramma, brainstorming e SDL hanno nuovi diagrammi di base per iniziare rapidamente.
 - **Creare un documento Word fuori dalle forme di Visio:** aggiungere automaticamente il contenuto del diagramma, incluse forme e metadati, a un documento di Word. Personalizzare quindi il documento per creare linee guida di processo e manuali operativi. [Altre informazioni](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità
- **Il salvataggio automatico di file nel cloud è ora abilitato per impostazione predefinita:** il salvataggio automatico è attivato per impostazione predefinita nel rilascio del canale semestrale (mirato) di settembre 2018. Ciò significa che gli utenti non dovranno più preoccuparsi di perdere le modifiche nei documenti archiviati in OneDrive o SharePoint Online. Le modifiche vengono salvate automaticamente nel cloud e gli utenti non dovranno più premere esplicitamente CTRL+S o il pulsante Salva. Tuttavia, è necessario comprendere questa modifica al comportamento in modo da non apportare modifiche accidentali alle presentazioni. Si noti che gli utenti possono disattivare il salvataggio automatico con l'interruttore Salva automaticamente posto nella parte superiore dello schermo. È consigliabile comunicare ai propri utenti questa modifica imminente e fornire loro informazioni su come sfruttare al meglio questa nuova funzionalità in Office 365. [Altre informazioni sul salvataggio automatico](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Altre informazioni su cosa è importante che gli amministratori IT sappiano sul salvataggio automatico]
- **Miglioramenti di Verifica accessibilità:** Verifica accessibilità ha ricevuto aggiornamenti relativi al supporto per gli standard internazionali e consigli per rendere più accessibili i documenti. [Altre informazioni](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Supporto SVG migliorato:** è ora possibile inserire SVG con filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8430): vulnerabilità relativa all'esecuzione di codice remoto in Word PDF
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0919): vulnerabilità della divulgazione delle informazioni di Microsoft Office

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema che causa la visualizzazione di un messaggio relativo alla memoria insufficiente.
-   È stato risolto un problema che impediva ad alcuni utenti di aprire e-mail e documenti protetti da IRM condivisi con tali utenti da persone in altre organizzazioni.
-   Risolve alcuni problemi relativi alle prestazioni.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8332): vulnerabilità relativa all'esecuzione di codice remoto in Win32k Graphics
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8378): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8157): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8158): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0950): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-1026): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-1030): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   
  **Attivazione bloccata dei controlli Flash, Silverlight e Shockwave in Office per motivi di sicurezza:** per motivi di sicurezza, nuove build di Microsoft Office per Office 365 in Windows bloccano l'attivazione dei controlli Flash, Silverlight e Shockwave. Altre informazioni [qui](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) e [qui](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
-  Risolve un problema a causa del quale l'installazione degli aggiornamenti richiedeva un lungo periodo di tempo in determinati scenari.
-  Consente di risolvere un problema a causa del quale, quando apre un'applicazione, l'utente potrebbe visualizzare un messaggio sull'avvio in modalità provvisoria e l'applicazione non si apre.
-  Risolve alcuni problemi relativi alle prestazioni.

## <a name="version-1803-august-14"></a>Versione 1803: 14 agosto
*Versione 1803 (Build 9126.2275)*

### <a name="access-security-updates"></a>Access: aggiornamenti della sicurezza
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8312): vulnerabilità di tipo use-after-free relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8375): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8379): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8382): vulnerabilità relativa alla divulgazione delle informazioni di Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [ADV180021](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV180021): aggiornamento difensivo Microsoft Office 

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8378): vulnerabilità della divulgazione delle informazioni di Microsoft Office 

## <a name="version-1803-july-10"></a>Versione 1803: 10 luglio
*Versione 1803 (Build 9126.2259)*

### <a name="access-security-updates"></a>Access: Aggiornamenti della sicurezza
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8312): vulnerabilità di tipo use-after-free relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8310): vulnerabilità relativa alla manomissione di Microsoft Office

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale viene visualizzato l'anno errato quando si utilizza il calendario giapponese nel formato cella data.
-   Quando si importano i dati nel modello di dati di Excel, i valori zero negativo in ingresso danno origine a un errore. La correzione consente ora di importare tali valori come zero.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale il rendering delle tabelle non è eseguito correttamente con i bordi spessi.

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale, se un'attività è divisa con una risorsa costo, quest'ultima non viene aggiornata correttamente e il costo viene perso.
-   Consente di correggere un problema a causa del quale in Visualizzazione cronologia, nella finestra di dialogo Aggiungi attività esistenti alla sequenza temporale, verrebbero visualizzate solo le attività della prima attività di riepilogo.
-   Consente di risolvere un problema a causa del quale il salvataggio nel formato XML potrebbe non riuscire per i progetti principali di Project Online o Project Server.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un bug a causa del quale l'installazione degli aggiornamenti ha richiesto un lungo periodo di tempo in determinati scenari. 
-   Consente di correggere un problema a causa del quale i test SVG non sono eseguiti correttamente.
-   Consente di correggere un problema a causa del quale, quando vengono distribuiti gli aggiornamenti con Configuration Manager a un client che esegue applicazioni di Office, l'aggiornamento non viene applicato dopo il riavvio del dispositivo.


## <a name="version-1803-june-12"></a>Versione 1803: 12 giugno
*Versione 1803 (Build 9126.2227)*

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8246): vulnerabilità della divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8248): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale a volte un'operazione di raggruppamento (o di annullamento del raggruppamento) in una tabella pivot di Excel potrebbe provocare un arresto anomalo.

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8244): vulnerabilità relativa all'elevazione di privilegi in Microsoft Outlook

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale potrebbe verificarsi un arresto anomalo durante la modifica della proprietà Shape.Visible.
-   Consente di correggere un problema a causa del quale le modifiche nei documenti creati in modalità condivisa non si uniscono.
-   Consente di correggere un problema a causa del quale non sarebbe possibile la creazione condivisa di documenti contenenti controlli ActiveX.

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale in Visualizzazione cronologia, nella finestra di dialogo Aggiungi attività esistenti alla sequenza temporale, verrebbero visualizzate solo le attività della prima attività di riepilogo.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale, quando vengono distribuiti gli aggiornamenti con Configuration Manager a un client che esegue applicazioni di Office, l'aggiornamento non viene applicato dopo il riavvio del dispositivo.



## <a name="version-1803-may-18"></a>Versione 1803: 18 maggio
*Versione 1803 (Build 9126.2210)*

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
- Consente di risolvere un problema in cui le azioni relative ai grafici potrebbero causare un arresto anomalo di Excel.
- Consente di risolvere un problema a causa del quale un componente aggiuntivo Power View viene inavvertitamente disattivato per alcuni utenti.
- Consente di risolvere un problema a causa del quale i file temporanei creati tramite il ripristino automatico durante il recupero di un documento non vengono mai eliminati.
- Consente di risolvere un problema a causa del quale un tentativo di creare una nuova connessione a un file di testo in una cartella di lavoro protetta genera il messaggio di errore "La cartella di lavoro è protetta e non può essere modificata".

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
- Consente di risolvere un problema a causa del quale la correzione ortografica nelle forme causa l'arresto anomalo di PowerPoint.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
- Consente di risolvere un problema a causa del quale, quando apre un'applicazione, l'utente potrebbe visualizzare un messaggio sull'avvio in modalità provvisoria e l'applicazione non si apre.



## <a name="version-1803-may-8"></a>Versione 1803: 8 maggio
*Versione 1803 (Build 9126.2191)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8147): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8148): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8162): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8163): vulnerabilità della divulgazione delle informazioni di Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando si apre un file da SharePoint Online.
-   Consente di risolvere un problema a causa del quale si stampa o si visualizza l'anteprima di stampa solo di una parte del foglio di lavoro, con il contenuto troncato in un filtro dei dati sul foglio di lavoro.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8150): le funzionalità di sicurezza di Microsoft Outlook ignorano la vulnerabilità

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale, quando si passa ad Outbox o alla cartella Posta inviata, Outlook si arresta in modo anomalo.
-   Consente di risolvere un errore a causa del quale tutti i partecipanti ricevono aggiornamenti sulla riunione quando vengono apportate delle modifiche agli allegati e al corpo della riunione, mentre l'invio di un aggiornamento della riunione ai partecipanti è facoltativo.
-   Consente di risolvere un problema a causa del quale gli utenti non sono in grado di connettersi agli endpoint EWS e REST a causa di una modifica nella stringa agente utente.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale PowerPoint si arresta in modo anomalo quando si apre un file da SharePoint Online.
-   Consente di risolvere un problema a causa del quale il riquadro con le informazioni sul file recuperato viene visualizzato in modo errato quando è attivo Salvataggio automatico.
-   Consente di risolvere un problema a causa del quale l'accesso non viene visualizzato impedendo a un utente di accedere a un file.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale l'utilizzo del menu a discesa di filtro automatico in una colonna della data fa in modo che tutte le attività del progetto vengano nascoste.
-   Consente di risolvere un problema a causa del quale solo le attività della prima attività di riepilogo vengano visualizzate nella finestra di dialogo quando si aggiungono attività esistenti a una sequenza temporale in visualizzazione Sequenza temporale.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Word si arresta in modo anomalo quando si apre un file da SharePoint Online.
-   Consente di risolvere un problema a causa del quale i numeri di pagina romani minuscoli diventano maiuscoli erroneamente.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8157): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8158): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office



## <a name="version-1803-april-10"></a>Versione 1803: 10 aprile
*Versione 1803 (Build 9126.2152)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-1029): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale la creazione condivisa da parte di più utenti sulla stessa presentazione comporta una duplicazione errata degli schemi diapositiva.
-   Consente di risolvere un problema a causa del quale l'apertura di un file salvato su OneDrive comporta l'arresto anomalo di PowerPoint all'uscita dalla visualizzazione protetta.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema relativo al supporto TLS 1.2.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema che causa la visualizzazione di un messaggio relativo alla memoria insufficiente.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0950): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-1026): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-1030): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office



## <a name="version-1803-march-20"></a>Versione 1803: 20 marzo
*Versione 1803 (Build 9126.2098)*

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui la stampa immediata di una cartella di lavoro di Excel allegata a un messaggio di posta elettronica di Outlook potrebbe non essere stampata.
-   Consente di risolvere un problema per cui fare clic su un collegamento ipertestuale può causare un arresto anomalo di Excel.
-   Consente di risolvere un problema per cui l'utilizzo di funzioni cubo causa un arresto anomalo di Excel.

### <a name="onedrive-for-business-non-security-updates"></a>OneDrive for Business: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema per cui OneDrive for Business (Groove.exe) consuma l'equivalente di CPU di core CPU (ad esempio, il 25% su una 4 core CPU) in Task Manager per lunghi periodi di tempo.

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui un aggiornamento della sede della riunione per i partecipanti mostra la vecchia posizione anziché la nuova.
-   Consente di risolvere un problema in cui l'utente riceve un messaggio di errore durante l'anteprima di un allegato nel riquadro di lettura.
-   Consente di risolvere un problema per cui Outlook si blocca durante la risoluzione dei nomi visualizzati per gli indirizzi di posta elettronica quando l'utente compone un messaggio di posta elettronica.
-   Consente di risolvere un problema per cui alcuni utenti non ricevono funzionalità di supporto che sono state abilitate dall’amministratore tenant.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di correggere un problema per cui non è possibile aprire Word su un computer con Windows 7 se non è installato[Aggiornamento per i clienti e diagnostica telemetria](https://support.microsoft.com/help/3080149/update-for-customer-experience-and-diagnostic-telemetry)Installato
-   Consente di risolvere un problema per cui gli elenchi puntati non vengono stampati.



## <a name="version-1803-march-13"></a>Versione 1803: 13 marzo
*Versione 1803 (Build 9126.2072)*

### <a name="access-security-updates"></a>Access: Aggiornamenti della sicurezza
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0903): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="access-non-security-updates"></a>Access: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema che si verifica quando si apre un'applicazione runtime di Access (file accde); a causa di questo problema, viene visualizzato il messaggio di errore "Formato di database non riconosciuto" e l'applicazione non si apre.
-   Consente di risolvere un problema in cui se si tenta di selezionare il testo nella casella di testo di una casella combinata viene selezionato tutto il testo, anziché la parte selezionata.

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti delle funzionalità
-   **Microsoft Translator:** è possibile tradurre parole e frasi in un'altra lingua con Microsoft Translator nella scheda Revisione della barra multifunzione.
-   **Conversione delle icone SVG in forme**: per cambiare il colore, le dimensioni o una trama, trasformare tutte le immagini SVG e le icone in forme di Office.
-   **Deselezionare le celle:** Consente di selezionare le opzioni del foglio di lavoro e deselezionare le celle accidentalmente selezionate senza dover ricominciare da capo.
-   **Accedere rapidamente ai siti e gruppi:** Utilizzare il menu File per utilizzare i documenti archiviati nei siti e gruppi più usati.
-   **Matita digitale:** scrivere o prendere appunti usando il nuovo tratto della matita. È sufficiente inclinare la penna digitale per fare le ombre.
-   **Impostazione delle funzionalità LinkedIn:** andare a File \> Opzioni \> Generale per controllare se le funzionalità di LinkedIn sono visualizzate nelle proprie applicazioni Office. [Ulteriori informazioni](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelli 3D:** Utilizzare il formato 3D per aumentare l'impatto visivo e creativo delle cartelle di lavoro. Inserire facilmente un modello 3D affinché sia possibile ruotarlo di 360 gradi. [Altre informazioni](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuovi effetti di input penna:** esprimere le proprie idee con un tocco in più usando penne metalliche ed effetti di input penna come Arcobaleno, Galassia, Lava, Oceano, Oro, Argento e altro ancora.
-   **UI per la condivisione di file:** nel caso dei file di OneDrive for Business o SharePoint, fare clic sul pulsante Condividi nell'angolo superiore destro oppure andare a File \> Condividi per avviare una finestra di dialogo Condividi semplificata e migliorata. Per i file nuovi o salvati in locale, l'interfaccia utente permette agli utenti di caricare in un attimo i file su OneDrive e avviare la collaborazione.
-   **Bloccare estensioni pericolose:** per impostazione predefinita, viene impedita l'attivazione delle estensioni considerate ad alto rischio e incorporate come oggetti di pacchetti OLE, bloccandole. Queste sono, ad esempio, EXE, VBS e JS. [Ulteriori informazioni](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Suoni utili per migliorare l'accessibilità:** attivare gli avvisi audio per ottenere assistenza durante il lavoro. Sono disponibili in File \> Opzioni \> Accessibilità. Non sono necessari componenti aggiuntivi. [Altre informazioni](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Percorsi dei file per account:** quando si apre o si salva un file, l'elenco dei percorsi è organizzato in base all'account associato.
-   **Personalizzazione della penna:** scegliere un set personale di penne ed evidenziatori per l'input penna. Il set personalizzato è disponibile in tutti i PC Windows.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2017-11877:](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2017-11877) le funzionalità di sicurezza di Microsoft Excel ignorano la vulnerabilità
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2017-11878): vulnerabilità di danneggiamento della memoria di Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2017-11884): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0796): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0841): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0907): superamento delle funzionalità di sicurezza di Microsoft Office Excel
-   [Avviso 170021](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV170021): Aggiornamento difensivo di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui, se la lingua di modifica è giapponese, cinese o coreano, Excel potrebbe bloccarsi quando si prova a scegliere un nuovo tipo di carattere nella scheda Home o quando si modifica.
-   Consente di risolvere un problema per cui le barre di scorrimento non sono presenti quando una cartella di lavoro viene aperta quando Excel è ridotto a icona.
-   Consente di risolvere un problema in caso di errore nei riferimenti delle cartelle di lavoro durante l’apertura di più cartelle, facendo doppio clic sui nomi dei file in Esplora File.
-   Consente di risolvere un problema in cui la creazione programmatica di una Tabella pivot seguita da un aggiornamento programmatico causa l’arresto anomalo di Excel.
-   Consente di risolvere un problema in cui la chiamata Workbook.Open() a livello di programmazione potrebbe causare l’arresto anomalo di Excel.
-   Consente di risolvere un problema in cui l'utente visualizza un messaggio di "Errore irreparabile" non corretto quando viene aperta una cartella di lavoro di Office 2007 o versione precedente (.xls o .xla)con le macro.
-   Consente di risolvere un problema a causa del quale Excel potrebbe arrestarsi in modo anomalo quando un utente apre a menu di scelta rapida.
-   Consente di risolvere un problema in cui, quando si tenta di inserire un oggetto in una cartella di lavoro esistente, Excel si arresta in modo anomalo quando l'utente fa clic su Sfoglia.
-   Consente di risolvere un problema a causa del quale, quando si protegge un intervallo tramite password, non viene visualizzata la finestra di dialogo nella quale immettere la password di sblocco intervallo.
-   Consente di risolvere un problema in cui l'utente non è in grado di chiudere una cartella di lavoro in visualizzazione protetta quando il nome file contiene parentesi quadre.
-   Consente di risolvere un problema a causa del quale la descrizione comando non si allinea correttamente quando si trascinano elementi oppure si trascina il riempimento.
-   Consente di risolvere un errore che si verifica quando si salva una cartella di lavoro utilizzando File \> Salva con nome e causa del quale il nome del file viene visualizzato vuoto oppure troncato nella finestra di dialogo di salvataggio del file.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.

### <a name="outlook-feature-updates"></a>Outlook: Aggiornamenti delle funzionalità
-   **Ordinare e-mail con facilità:** Grazie ai commenti offriamo di nuovo la possibilità di ordinare l'elenco dei messaggi e il filtro Da leggere per gli utenti che non usano Posta in arrivo evidenziata.
-   **Convertire le icone SVG in forme:** Per cambiare colore, dimensioni o una trama, trasformare tutte le immagini SVG e le icone in forme di Office.
-   **Miglioramenti per i gruppi di Office 365:** Leggere e rispondere alle conversazioni di gruppo è più facile che mai, perché basta fare doppio clic su un messaggio di gruppo per aprirlo in una finestra separata.
-   **Impostazione delle funzionalità LinkedIn:** andare a File \> Opzioni \> Generale per controllare se le funzionalità di LinkedIn sono visualizzate nelle proprie applicazioni Office. [Ulteriori informazioni](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelli 3D:** Utilizzare il formato 3D per aumentare l'impatto visivo e creativo della posta elettronica.  Inserire facilmente un modello 3D affinché sia possibile ruotarlo di 360 gradi. [Altre informazioni](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Scheda del profilo:** Mostra i dettagli più importanti di utenti e gruppi su un computer desktop, sul Web o tramite un'app per dispositivi mobili.
-   **Aggiungere un appuntamento a un calendario di gruppo:** Ora è possibile comunicare a ogni membro del gruppo quando si sarà assenti senza inviare un invito a una riunione tramite posta elettronica.
-   **Download degli allegati cloud:** quando si salvano oppure trascinano gli allegati di OneDrive nel computer, il file viene scaricato automaticamente.
-   **Suoni utili per migliorare l'accessibilità:** attivare gli avvisi audio per ottenere assistenza durante il lavoro. Sono disponibili in File \> Opzioni \> Accessibilità. Non sono necessari componenti aggiuntivi. [Altre informazioni](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Posta in arrivo evidenziata:** La cartella Posta in arrivo è suddivisa in due schede: Evidenziata e Altro. I messaggi vengono ordinati in base al contenuto del messaggio e in base a con quali utenti si interagisce maggiormente. [Altre informazioni](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **Accedere rapidamente ai gruppi più utilizzati:** I gruppi con i quali è più probabile che si interagirà ora vengono visualizzati nella parte superiore dell'elenco in Gruppi nel riquadro delle cartelle.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2017-11939): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0791): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0850): vulnerabilità elevazione di privilegi in Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0852): vulnerabilità di danneggiamento della memoria di Microsoft Outlook

### <a name="outlook-non-security-updates"></a>Outlook: Aggiornamenti non della sicurezza
-   Consente di correggere un problema per cui la ricerca ha esito negativo restituendo "Nessuna corrispondenza trovata" quando l'ambito della ricerca include tutte le cassette postali.
-   Consente di risolvere un problema a causa del quale, quando si utilizza Monitoraggio eventi accessibile (AccEvent.exe), Outlook si arresta in modo anomalo durante il passaggio da una cartella all'altra.

### <a name="powerpoint-feature-updates"></a>PowerPoint: Aggiornamenti delle funzionalità
-   **Microsoft Translator:** è possibile tradurre parole e frasi in un'altra lingua con Microsoft Translator nella scheda Revisione della barra multifunzione.
-   **Animazioni 3D:** dare vita a modelli 3D con animazioni, ad esempio con movimenti graduali, spostamenti e rotazioni.
-   **Convertire le icone SVG in forme:** Per cambiare colore, dimensioni o una trama, trasformare tutte le immagini SVG e le icone in forme di Office.
-   **Roaming delle informazioni di verifica revisione:** Lo stato dei messaggi già letti o da leggere letto per evidenziare diapositive condivise modificate da altri utenti è archiviato in un servizio roaming (anziché nel computer dell'utente), in modo che queste informazioni possano essere sincronizzate su più dispositivi o piattaforme.
-   **Accedere rapidamente ai siti e gruppi:** Utilizzare il menu File per utilizzare i documenti archiviati nei siti e gruppi più usati.
-   **Matita digitale:** scrivere o prendere appunti usando il nuovo tratto della matita. È sufficiente inclinare la penna digitale per fare le ombre.
-   **Impostazione delle funzionalità LinkedIn:** andare a File \> Opzioni \> Generale per controllare se le funzionalità di LinkedIn sono visualizzate nelle proprie applicazioni Office. [Ulteriori informazioni](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Effettuare una presentazione utilizzando una penna digitale:** usare la penna per Surface oppure un'altra dotata di pulsante Bluetooth per passare da una diapositiva all'altra. È necessario disporre di Windows 10 Fall Creators Update. [Ulteriori informazioni](https://support.office.com/article/e36da834-7d34-4b71-aafd-071727549f7a)
-   **Modelli 3D:** Utilizzare il formato 3D per aumentare l'impatto visivo e creativo delle presentazioni. Creare modelli 3D nelle presentazioni con transizioni come Morphing per generare animazioni cinematografiche tra le diapositive. [Altre informazioni](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuovi effetti di input penna:** esprimere le proprie idee con un tocco in più usando penne metalliche ed effetti di input penna come Arcobaleno, Galassia, Lava, Oceano, Oro, Argento e altro ancora.
-   **UI per la condivisione di file:** nel caso dei file di OneDrive for Business o SharePoint, fare clic sul pulsante Condividi nell'angolo superiore destro oppure andare a File \> Condividi per avviare una finestra di dialogo Condividi semplificata e migliorata. Per i file nuovi o salvati in locale, l'interfaccia utente permette agli utenti di caricare in un attimo i file su OneDrive e avviare la collaborazione.
-   **Bloccare estensioni pericolose:** per impostazione predefinita, viene impedita l'attivazione delle estensioni considerate ad alto rischio e incorporate come oggetti di pacchetti OLE, bloccandole. Queste sono, ad esempio, EXE, VBS e JS. [Ulteriori informazioni](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Evidenziazione di revisione:** vengono evidenziate le diapositive modificate da altri utenti.
-   **Durante l'assenza:** PowerPoint mostra all'utente chi ha modificato la presentazione condivisa a partire dall'ultima visita.
-   **Miglioramenti per la progettazione:** nelle finestre di progettazione le idee per progetti vengono presentate in forma di elenco puntato.
-   **Suoni utili per migliorare l'accessibilità:** attivare gli avvisi audio per ottenere assistenza durante il lavoro. Sono disponibili in File \> Opzioni \> Accessibilità. Non sono necessari componenti aggiuntivi. [Altre informazioni](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Percorsi dei file per account:** quando si apre o si salva un file, l'elenco dei percorsi è organizzato in base all'account associato.
-   **Personalizzazione della penna:** scegliere un set personale di penne ed evidenziatori per l'input penna. Il set personalizzato è disponibile in tutti i PC Windows.
-   **Miglioramenti per la progettazione:** la finestra di progettazione suggerisce ora idee di progettazione per i grafici aggiunti alle diapositive.
-   **Avvio rapido:** consente di compilare automaticamente una struttura per agevolare gli utenti nella ricerca di un oggetto di loro scelta. [Ulteriori informazioni](https://support.office.com/article/4784f273-0b2c-456c-9c89-24e5b977c224)
-   **Righello digitale:** nei dispositivi con touchscreen, andare a Disegno \> Righello, quindi usare la penna o il dito per disegnare linee dritte o per allineare un insieme di oggetti. [Altre informazioni](https://support.office.com/article/6222c9b4-2fdf-48f7-a3fd-1687fbe2bf84)

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti della sicurezza
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2017-11934): vulnerabilità della divulgazione delle informazioni relative a Microsoft PowerPoint

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema in cui la rimozione delle proprietà del documento e delle informazioni personali causa errori nel salvataggio in SharePoint.
-   Consente di risolvere un problema in cui i riferimenti a Flash Player basati sui codici di incorporamento di YouTube causano l&apos;apertura di una nuova finestra per la riproduzione del video. I vecchi codici di incorporamento sono ora aggiornati al riferimento HTML5 basato sui video di YouTube affinché vengano riprodotti correttamente.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.

### <a name="project-feature-updates"></a>Project: Aggiornamenti delle funzionalità
-   **Vista della lavagna delle attività:** ordinare le attività nelle schede nella vista della lavagna delle attività. Ordinare nuovamente e spostare le schede tra le colonne della lavagna, così come avviene per i progetti Agile.
-   **Progetti Agile:** gestire i progetti Agile utilizzando backlog, lavagne delle attività, sprint e molto altro ancora. Sono supportate sia la metodologia Scrum sia la metodologia Kanban. [Ulteriori informazioni](https://support.office.com/article/1b9b44d7-fd8e-4b3b-ab94-2b97deb9945b)  
-   **Gestire un'attività in Planner:** collegare un’attività progetto a Planner e creare una relativa pianificazione. Suddividere l'attività in sottoattività, aggiungere un team, assegnare attività e gestire il lavoro su una lavagna delle attività.

### <a name="project-non-security-updates"></a>Project: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui impostando più di una linea di base in una sessione viene impostato il valore MOD\_DATE allo stesso modo.
-   Consente di risolvere un problema per cui il lavoro effettivo viene comunque visualizzato nelle tabelle di creazione report dopo essere stato rimosso in una sessione Salva per la condivisione.
-   Consente di risolvere un problema nella versione in lingua tedesca per cui quando si usa il formato data in settimane viene visualizzato un errore durante la pianificazione.
-   Consente di risolvere un problema per cui, quando si modificano le date di fine in Pianifica Web Part, le attività rimangono 8 ore al giorno invece di estendersi nel tempo.
-   Consente di risolvere un problema per cui "Forma punto di avanz." viene visualizzato in una posizione inattesa.
-   Risolvere un problema di perdita del codice VBA dai progetti.
-   Consente di risolvere un problema in cui le attività vengono visualizzate come completate anche se non è così.
-   Consente di risolvere un problema in cui Project si interrompe quando si utilizza la funzionalità della sequenza delle attività.
-   Consente di risolvere un problema in cui la scala cronologica non mostra le relative etichette.
-   Consente di risolvere un problema in cui le relazioni grafiche mostrano informazioni incomplete o si bloccano del tutto.
-   Consente di risolvere un errore a casa del quale un errore di salvataggio potrebbe danneggiare un file e causare l'arresto anomalo di Project all'avvio.
-   Consente di risolvere un problema a causa del quale l'utente non riesce a trascinare le attività nella Sequenza temporale e nella vista Pianificazione team.
-   Consente di risolvere un problema a causa del quale la disponibilità delle risorse non viene visualizzata in Creazione team.
-   Consente di risolvere un problema a causa del quale gli indicatori grafici non vengono visualizzati correttamente.
-   Consente di risolvere un problema a causa del quale Project si blocca durante il livellamento orario o giornaliero.
-   Consente di risolvere un problema per lavorare con progetti principali/secondari da una raccolta documenti di SharePoint.
-   Consente di risolvere un problema a causa del quale l'aggiunta di assegnazioni a un'attività con durata fissa genera una risorsa senza nome.
-   Consente di risolvere un problema a causa del quale viene mostrato un messaggio relativo a una modifica di lavoro protetto.
-   Consente di risolvere un problema a causa del quale Project potrebbe arrestarsi in modo anomalo quando si accede a report che includono molte immagini.

### <a name="publisher-feature-updates"></a>Publisher: aggiornamenti delle funzionalità
-   **Bloccare estensioni pericolose:** per impostazione predefinita, viene impedita l'attivazione delle estensioni considerate ad alto rischio e incorporate come oggetti di pacchetti OLE, bloccandole. Queste sono, ad esempio, EXE, VBS e JS. [Ulteriori informazioni](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="publisher-non-security-updates"></a>Publisher: aggiornamenti non della sicurezza
-   Consente di correggere un errore che si verifica quando si applica un filtro ai campi dell'origine dati che contengono valori null (vuoti). A causa del problema, non si riesce ad applicare il filtro quando si esegue la procedura guidata Stampa unione.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui l'aggiunta degli utenti selezionando "Chiamata Skype" in una riunione causa un errore.
-   Consente di rimuovere un'istruzione che richiede all'utente di aggiungere le coordinate Skype a una riunione, se viene aggiunta una Skype Room come posizione e la riunione già contiene le coordinate della riunione dei team.
-   Consente di risolvere un problema per cui la posizione viene popolata anche se UseLocationForE911Only è impostato su true.
-   Consente di risolvere un problema per cui Skype for Business si blocca quando si usa l'opzione "chiamata tramite il centro conferenze" per invitare gli utenti dall'elenco dei partecipanti.
-   Consente di risolvere un problema per cui Outlook in esecuzione su un server si blocca durante la creazione di una riunione di Skype for Business.
-   Modificare il valore predefinito di EnableRestoreOAuthUsedKeyWhenUsingCachedWebTicket su TRUE.
-   Consente di risolvere un problema per cui i pulsanti "Altre opzioni" e "Invita altre persone" sono nascosti quando una riunione è in modalità schermo intero.
-   Consente di risolvere un problema per cui la finestra della chiamata audio P2P o della conferenza telefonica diventa trasparente quando si prova a partecipare.
-   Consente di risolvere un problema per cui le riunioni di Skype programmate non vengono visualizzate nella scheda delle riunioni.
-   Consente di risolvere un problema per cui, quando Skype for Business è configurato per partecipare a riunioni senza audio, l'aggiunta di audio a una riunione avvia una nuova chiamata P2P allo stesso utente invece di aggiungere audio alla riunione esistente.
-   Consente di risolvere un problema per cui l'utente riceve il messaggio di errore "Impossibile trovare la riunione di Skype" quando si fa clic sul link "Partecipa a riunione Skype" in una convocazione riunione di Outlook.
-   Aggiungere il pulsante di trasferimento di chiamata all'interfaccia utente di avviso per chiamate PSTN in arrivo.
-   Comunicare agli utenti che chiamate e chat vengono inviate ai team quando le opzioni ChatDefaultClient e CallDefaultClient sono impostate su Team.
-   Visualizzare la presenza dell'utente come non in linea quando non è in riunione e risulta non attivo su Skype for Business e l’opzione per partecipare alla riunione è impostata su Native Limited Client.
-   Disattivare tutte le opzioni ad eccezione di Apri e Chiudi, quando Skype for Business è ridotto a icona nell'area di notifica.
-   Eliminare le nuove chiamate e conversazioni in abbinamento con telefoni Aries e RedirectClient è abilitato.
-   Risolvere un problema in caso di errore relativo alla data durante la ricerca di messaggi in PChat, quando il formato della data è diverso da quello statunitense (mm/gg/aa).
-   Risolvere un problema in cui sia ancora possibile allegare file nelle riunioni, quando il criterio EnableExternalP2PFileTransfer è impostato su false.
-   Consente di risolvere un problema in cui, nella cronologia di una conversazione, viene mostrato il chiamante anziché la persona chiamata. Ciò accade quando il numero di lavoro della persona chiamata viene modificato tramite Active Directory.
-   Consente di risolvere un problema in cui, per le chiamate PSTN verso numeri di cellulare, le informazioni sui destinatari non vengono visualizzate nella cronologia delle chiamate nella cronologia delle conversazioni.
-   Consente di risolvere un problema in cui, quando si inizia una chat da un messaggio di posta elettronica in Outlook, la riga dell'oggetto del messaggio non è inclusa nell'oggetto della chat.
-   Consente di risolvere un problema in cui, quando le finestre delle chat vengono bloccate su un lato, le conversazioni vengono visualizzate sovrapposte.
-   Consente di risolvere un problema in cui, in un ambiente VDIv2, le richieste di condivisione dello schermo VbSS vengono visualizzate come richieste basate su RDP.
-   Consente di risolvere un problema in cui, in un trasferimento di chiamata non riuscito, nella notifica di errore viene mostrato il chiamante anziché il destinatario mancante.
-   Consente di risolvere un problema in cui il pulsante "Inizia a usare Teams" è nascosto all'interno del banner di reindirizzamento dell'aggiornamento del client.
-   Consente di risolvere problemi di scalabilità DPI nelle finestre di chat.
-   Consente di risolvere un problema in cui i dati di LinkedIn non vengono visualizzati nella scheda contatto Skype for Business.
-   Aggiungere la possibilità che gli utenti non ricevano più chiamate per conto di un gruppo di risposta.
-   Aggiungere la possibilità di mettere automaticamente in attesa le chiamate quando una chiamata è attiva in Skype for Business o Team e viene ricevuta o avviata una nuova chiamata.
-   Consente di risolvere un problema a causa del quale gli utenti non possono utilizzare la messaggistica istantanea dopo la condivisione dello schermo intero.
-   Consente di risolvere un problema a causa del quale gli utenti nella sala di attesta non ricevono notifiche in merito al divieto di partecipare a una riunione.
-   Consente di risolvere un problema a causa del quale il controllo guadagno automatico aumenta in modo incontrollabile durante le chiamate.
-   Consente di risolvere un problema a causa del quale gli utenti non riescono a selezionare un relatore nelle opzioni della riunione, se la cassetta postale delle risorse di una sala riunioni viene aggiunta all'invito della riunione.
-   Consente di risolvere un problema a causa del quale il pulsante di condivisione desktop viene disattivato durante una videochiamata peer-to-peer, se AllowlPVideo è impostato su False.
-   Consente di risolvere un problema a causa del quale la messaggistica istantanea rimane disattivata dopo aver modificato le impostazioni relative alle opzioni della riunione in "Abilita messaggistica istantanea" per le riunioni correnti, create disattivando la messaggistica istantanea.
-   Consente di risolvere un problema a causa del quale la descrizione comando non viene visualizzata quando si passa con il mouse sul pulsante "Inserisci collegamento" nella finestra di chat e non è presente un nome di accessibilità quando il pulsante viene selezionato.

### <a name="visio-feature-updates"></a>Visio: Aggiornamenti delle funzionalità
-   **Diagrammi modello database integrati**: usare il nuovo Diagramma modello database per modellare in modo accurato il database come un diagramma di Visio. Nessun componente aggiuntivo necessario.
-   **Altri stencil per diagrammi aziendali:** Utilizzo di forme moderne, confrontare e contrastare dati con un diagramma di Venn o disegnare diagrammi circolari, di matrice o a piramide per arricchire i contenuti.
-   **Creare un diagramma reticolo per un sito Web:** Creare rapidamente un diagramma reticolo di un sito Web con interfaccia, barra di spostamento e come interagiscono tra loro. [Altre informazioni](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Creare un reticolo dell'applicazione per dispositivi mobili:** Utilizzare un modello per creare un reticolo dell'applicazione per dispositivi mobili. [Ulteriori informazioni](https://support.office.com/article/2d54dc55-f5c4-49a2-85da-d649eb7fc281)
-   **Applicare elementi grafici dati ai diagrammi di Data Visualizer:** velocizzare la creazione di un diagramma di Data Virtualizer applicando automaticamente dati di forma e di elementi grafici. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6?#apply_dg)
-   **Collaborare ai disegni:** collaborare con altri utenti condividendo i disegni su OneDrive for Business o SharePoint Online. È possibile visualizzare gli utenti che stanno attualmente lavorando ai disegni, aggiungere commenti e visualizzare l'attività del file. [Ulteriori informazioni](https://support.office.com/article/413c0b5a-0d52-4ace-af85-8b9bf115bbbf)
-   **Bloccare estensioni pericolose:** per impostazione predefinita, viene impedita l'attivazione delle estensioni considerate ad alto rischio e incorporate come oggetti di pacchetti OLE, bloccandole. Queste sono, ad esempio, EXE, VBS e JS. [Ulteriori informazioni](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità
-   **Conversione delle icone SVG in forme**: per cambiare il colore, le dimensioni o una trama, trasformare tutte le immagini SVG e le icone in forme di Office.
-   **Conteggio dei caratteri:** mostra il conteggio dei caratteri sulla barra di stato durante la digitazione. È possibile abilitarla dal menu Personalizza barra di stato.
-   **Accedere rapidamente ai siti e gruppi:** utilizzare il menu File per utilizzare i documenti archiviati nei siti e gruppi più usati.
-   **Microsoft Translator:** tradurre parole, frasi oppure il documento intero in un'altra lingua utilizzando Microsoft Translator direttamente in Word. [Ulteriori informazioni](https://support.office.com/article/24a987b3-03a1-4c17-8c1b-54495fca6b17)
-   **Matita digitale:** scrivere o prendere appunti usando il nuovo tratto della matita. È sufficiente inclinare la penna digitale per fare le ombre.
-   **Impostazione delle funzionalità LinkedIn:** andare a File \> Opzioni \> Generale per controllare se le funzionalità di LinkedIn sono visualizzate nelle proprie applicazioni Office. [Ulteriori informazioni](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Riquadro proprietà di SharePoint:** visualizzare e modificare i valori della colonna relativa alla raccolta documenti di SharePoint all'interno di un documento. Un pulsante della barra multifunzione sulla scheda Visualizza fornisce un rapido accesso al pannello; gli amministratori di SharePoint possono utilizzare un'impostazione della raccolta documenti per aprire automaticamente il pannello delle proprietà.
-   **Modelli 3D:** Utilizzare il formato 3D per aumentare l'impatto visivo e creativo delle cartelle di lavoro.  Inserire facilmente un modello 3D affinché sia possibile ruotarlo di 360 gradi. [Altre informazioni](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuovi effetti di input penna:** esprimere le proprie idee con un tocco in più usando penne metalliche ed effetti di input penna come Arcobaleno, Galassia, Lava, Oceano, Oro, Argento e altro ancora.
-   **UI per la condivisione di file:** nel caso dei file di OneDrive for Business o SharePoint, fare clic sul pulsante Condividi nell'angolo superiore destro oppure andare a File \> Condividi per avviare una finestra di dialogo Condividi semplificata e migliorata. Per i file nuovi o salvati in locale, l'interfaccia utente permette agli utenti di caricare in un attimo i file su OneDrive e avviare la collaborazione.
-   **Bloccare estensioni pericolose:** per impostazione predefinita, viene impedita l'attivazione delle estensioni considerate ad alto rischio e incorporate come oggetti di pacchetti OLE, bloccandole. Queste sono, ad esempio, EXE, VBS e JS. [Ulteriori informazioni](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Modificare tramite strumenti di apprendimento:** gli strumenti di apprendimento sono ora disponibile nel layout Web di Word. Regolare la spaziatura del testo e possibilità di visualizzare le sillabe durante la modifica. In qualsiasi visualizzazione, le parole vengono evidenziate di pari passo alla lettura ad alta voce del documento. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
-   **Sintassi LaTex:** creare e modificare le equazioni matematiche tramite sintassi LaTeX.
-   **Suoni utili per migliorare l'accessibilità:** attivare gli avvisi audio per ottenere assistenza durante il lavoro. Sono disponibili in File \> Opzioni \> Accessibilità. Non sono necessari componenti aggiuntivi. [Altre informazioni](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Percorsi dei file per account:** quando si apre o si salva un file, l'elenco dei percorsi è organizzato in base all'account associato.
-   **Personalizzazione della penna:** scegliere un set personale di penne ed evidenziatori per l'input penna. Il set personalizzato è disponibile in tutti i PC Windows.
-   **Assistenza alla scrittura migliorata con il riquadro Editor:** Utilizzare il riquadro Editor per consigli avanzati su ortografia, grammatica e stile di scrittura. È stato creato per essere accessibile con supporto migliorato per assistive technology.

### <a name="word-security-updates"></a>Word: Aggiornamenti della sicurezza
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0792): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0794): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0798): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0801): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0802): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0804): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0805): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0806): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0807): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0812): vulnerabilità di danneggiamento della memoria di Microsoft Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0919): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [Avviso 170020](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV170020): Aggiornamento difensivo di Microsoft Office

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Word si arresta in modo anomalo quando un utente prova a salvare con il nome un documento esistente su OneDrive for Business e in seguito si annulla il salvataggio oppure si prova a unire le modifiche esistenti.
-   Consente di correggere un errore che si verifica quando si applica un filtro ai campi dell'origine dati che contengono valori null (vuoti). A causa del problema, non si riesce ad applicare il filtro quando si esegue la procedura guidata Stampa unione.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.
-   Consente di risolvere un problema a causa del quale l'annullamento della protezione IRM da un documento non rimuove effettivamente la protezione.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2017-11882): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0795): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0851): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0853): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [Avviso 180003](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV180003): Aggiornamento difensivo di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale, quando apre un'applicazione, l'utente potrebbe visualizzare un messaggio sull'avvio in modalità provvisoria e l'applicazione non si apre.
-   L'opzione Aggiorna adesso è nascosta da File \> Account \> Opzioni di aggiornamento quando un oggetto COM di Office è abilitato in modo che gli aggiornamenti del client Office 365 vengono gestiti da Configuration Manager.
-   Consente di risolvere un problema in cui l'app di Office si arresta in modo anomalo quando l'utente tenta di attivare Office utilizzando la finestra di dialogo Attiva Office.
-   Consente di risolvere un problema con l'ingrandimento e il ridimensionamento nei componenti aggiuntivi per Office nell'ambiente DPI dinamico.
-   Consente di risolvere un problema in cui il nodo CurrentStatus del CSP (Configuration Service Provider) di Office restituisce una stringa vuota anche se Office 365 ProPlus è installato.
-   Consente di risolvere un problema a causa del quale il formato del file .box viene modificato, cosa che influisce sulle funzionalità delle versioni meno recenti di Office installate sullo stesso computer, perché i file .box sono condivisi tra tutte le versioni di un'app di Office sullo stesso computer.



## <a name="version-1708-february-13"></a>Versione 1708: 13 febbraio
*Versione 1708 (Build 8431.2215)*

### <a name="access-non-security-updates"></a>Access: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema per cui, quando si utilizzano più moduli di elementi, modificando la posizione della rotellina del mouse o facendo scorrere il cursore gli elementi visualizzati nel form non cambiano.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0841): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0850): vulnerabilità elevazione di privilegi in Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0852): vulnerabilità di danneggiamento della memoria di Microsoft Outlook

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0851): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0853): vulnerabilità della divulgazione delle informazioni di Microsoft Office



## <a name="version-1708-january-9"></a>Versione 1708: 9 gennaio
*Versione 1708 (Build 8431.2153)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0796): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [Avviso 170021](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV170021): Aggiornamento difensivo di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui la creazione programmatica di una Tabella pivot seguita da un aggiornamento programmatico causa l’arresto anomalo di Excel.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0791): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook

### <a name="word-security-updates"></a>Word: Aggiornamenti della sicurezza
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0792): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0794): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0798): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0801): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0802): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0804): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0805): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0806): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0807): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0812): vulnerabilità di danneggiamento della memoria di Microsoft Word

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-0795): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [Avviso 180003](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/ADV180003): Aggiornamento difensivo di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di aggiungere il supporto per Single Sign-On (SSO) per gli utenti del dominio per i piani di Office 365 Germania, in cui l'identità è federata con Active Directory locale.
-   Consente di aggiungere funzionalità per impedire ai minorenni di acquistare e attivare componenti aggiuntivi per Office dall’Office Store.


> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
