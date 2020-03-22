---
title: Note sulle versioni per i rilasci del Canale semestrale nel 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale semestrale per Office 365 ProPlus nel 2020
ms.openlocfilehash: b4a6ef107e4bd4904192d4c6e6d100194b2948b9
ms.sourcegitcommit: e2633701e5a00bd20a5f166e95fcb156461973ae
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 03/21/2020
ms.locfileid: "42890123"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a>Note sulle versioni per i rilasci del Canale semestrale nel 2020

Queste note sulle versioni forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non della sicurezza inclusi negli aggiornamenti del Canale semestrale per Office 365 ProPlus nel 2020, Visio Pro per Office 365, Project Online Desktop Client e Office 365 Business.

> [!NOTE]
>
>- Spesso le funzionalità (e talvolta persino le correzioni) vengono distribuite nel Canale semestrale in un certo arco di tempo. Se una funzionalità descritta di seguito non è ancora disponibile, non c'è da preoccuparsi. Arriverà a breve. [Altre informazioni](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- OneNote 2016 non sarà incluso per impostazione predefinita quando un utente del canale semestrale scarica e installa Office 365 in Windows 10 dal portale di Office.




## <a name="version-1908-march-10"></a>Versione 1908: 10 marzo
*Versione 1908 (Build 11929.20648)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.&nbsp;</span></div>


- <div><span style="display:inline !important;">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><br></div>


- <div style="box-sizing:border-box;"><span style="box-sizing:border-box;">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div>È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo&nbsp;Shape.Paste&nbsp;<span style="font-size:13.3333px;display:inline !important;">modifica la selezione nella forma incollata.</span></div>


### <a name="word"></a>Word

- <div>È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.<br></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span></div>

## <a name="version-1902-march-10"></a>Versione 1902: 10 marzo
*Versione 1902 (Build 11328.20554)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a>Versione 1908: 11 febbraio
*Versione 1908 (Build 11929.20606)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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

## <a name="version-1902-february-11"></a>Versione 1902: 11 febbraio
*Versione 1902 (Build 11328.20526)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.


### <a name="word"></a>Word

- È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a>Versione 1808: 11 febbraio
*Versione 1808 (Build 10730.20438)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a>Versione 1908: 14 gennaio
*Versione 1908 (Build 11929.20562)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Monitorare gli oggetti di database:** visualizzare chiaramente la scheda attiva, trascinare facilmente le schede per disporle in modo diverso e chiudere gli oggetti di database con un solo clic.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Zoom con più spazio:** ingrandire la casella Zoom e cambiare il tipo di carattere. Tutte le modifiche verranno mantenute. [Altre informazioni](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a>Excel

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

- **Fogli di lavoro animati:** è possibile inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella cartella di lavoro. [Altre informazioni](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- **Scoprire di più sui dati:** il nuovo pulsante Idee cerca modelli nei dati e li usa per creare suggerimenti intelligenti e personalizzati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **La collaborazione è stata semplificata:** i miglioramenti apportati alla creazione condivisa indicano che, quando si usa la formattazione condizionale, gli stili cella e così via, le modifiche vengono unite perfettamente con quelle dei propri collaboratori.

- **Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle. [Altre informazioni](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- **Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi. Semplice individuazione di funzioni, colonne e parametri.

### <a name="outlook"></a>Outlook

- **Aggiornamento dell'esperienza utente di Outlook:** è finalmente accessibile a tutti un'esperienza semplificata, in precedenza disponibile in anteprima con Prossimamente, progettata per consentire all'utente di concentrarsi sugli aspetti più importanti. [Altre informazioni](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Barra multifunzione semplificata e personalizzabile:** un'unica riga essenziale riunisce i pulsanti usati di frequente. In questo modo è possibile passare facilmente dalla visualizzazione classica a quella semplificata e aggiungere/rimuovere comandi. [Altre informazioni](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Continuare a lavorare durante lo spostamento di messaggi:** ora Outlook sposta i messaggi in background, di conseguenza è possibile continuare a lavorare durante lo spostamento di grandi quantità di messaggi tra le cartelle.

- **Avere un momento di respiro tra una riunione e l'altra:** dare ai partecipanti il tempo di riprendere fiato o di viaggiare da una località all'altra impostando le riunioni in modo che terminino per impostazione predefinita 5-10 minuti in anticipo.

- **Selezione dell'azione preferita:** le azioni Contrassegna e Elimina non vengono usate, ma si preferisce usare Archivia o Segna come già letto? È possibile personalizzare il menu Azioni rapide con i comandi usati più di frequente.

- **Utilizzo di meme:** quando testo o immagini statiche non bastano, si può usare una GIF animata per esprimere il proprio pensiero. [Altre informazioni](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)

- **Possibilità di scegliere tra layout medio o più ridotto:** l'opzione Usa spaziatura inferiore consente di decidere se si preferisce lasciare maggiore spazio fra gli elementi o adottare un layout più ridotto per visualizzare un maggior numero di elementi.

- **Un modo più rapido per aggiungere account:** grazie ai miglioramenti per la configurazione dell'account, l'aggiunta di account di Outlook.com e Gmail che utilizzano l'autenticazione a 2 fattori in Outlook è più facile che mai. [Altre informazioni](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- **Addio ai limiti per la sincronizzazione:** con i miglioramenti di Outlook non esiste più il limite di cartelle e quindi è possibile sincronizzare le cassette postali condivise.

### <a name="powerpoint"></a>PowerPoint

- **Spostamento di forme migliorato:** assegnare un nome alle forme per un maggiore controllo sul modo in cui effettuano il morphing. [Altre informazioni](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

- **Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo, nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.

- **Fare domande al pubblico con un test o un sondaggio:** inserire un test o un sondaggio in una diapositiva. Office raccoglie e archivia le risposte. [Ulteriori informazioni](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)

- **Inserire un video online è più facile che mai:** se si vuole inserire un video da Vimeo o YouTube nella diapositiva, basta il collegamento alla pagina del video. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

### <a name="project"></a>Project

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a>Visio

- **Esportazione dei diagrammi di processo in Word:** è possibile aggiungere automaticamente il contenuto dei diagrammi, come forme e metadati, a un documento Word. Quindi, personalizzare il documento per creare linee guida di processi e manuali operativi. [Altre informazioni](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- **Maggiore controllo sui diagrammi di flusso di dati:** i nuovi fantastici layout per i diagrammi di flusso del Visualizzatore dati sono chiari, nitidi e facili da capire. Fare clic sulla scheda Progettazione.

- **Stencil di Azure incorporati:** per progettare un'applicazione cloud o pianificare un'architettura è possibile scegliere tra decine di stencil di Azure. [Altre informazioni](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- **Addio ai collegamenti interrotti di Excel:** impossibile trovare la cartella di lavoro di Excel collegata al diagramma del Visualizzatore dati? Collegarla di nuovo per riprendere l’attività. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Esportare elementi visivi di Visio da Power BI:** gli oggetti visivi di Visio per Power BI vengono ora visualizzati correttamente quando si esportano i report di Power BI come PDF, file di PowerPoint e altro ancora. [Altre informazioni](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a>Word

- **La modalità Strumenti di apprendimento dispone di ulteriore supporto per più colori della pagina:** in Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina. Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.

- **Modifica semplificata con Editor input penna:** con un solo tratto della penna, si possono dividere o unire le parole, aggiungere una nuova riga o inserire parole. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Trasformare il documento da statico a sorprendente:** trasformare il documento in una pagina web interattiva, facile da condividere che si adatta perfettamente a qualsiasi dispositivo. [Altre informazioni](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

- **Aumentare l'efficacia del contenuto:** rendere accessibili i documenti Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Addio alle distrazioni:** una delle funzionalità preferite del Mac è ora disponibile in Windows. Passare alla modalità focus nel menu Visualizza per rimuovere elementi di distrazione e concentrarsi sul lavoro. [Altre informazioni](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- **Migliorare la comprensione con Focus su riga:** spostarsi in un documento riga per riga senza distrazioni. Modificare lo stato attivo per rendere visibili una, tre o cinque righe alla volta. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.

- **Ottenere l'attenzione tramite \@menzioni:** usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input. [Altre informazioni](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Ricerca rapida del file:** come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Apri per trovare il file che si sta cercando.

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.

- **Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse. [Altre informazioni](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- **Le icone di Office hanno un nuovo aspetto:** le icone di Office sono state riprogettate per riflettere l'esperienza semplice potente e intelligente di Office.

- **Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle installazioni esistenti di Office 365 ProPlus. [Altre informazioni](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo aggiornamento risolve un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.

- Questo aggiornamento risolve un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.

- Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo &quot;Query danneggiata&quot; quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.

### <a name="excel"></a>Excel

- Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt-G.

- È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.

- È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.

- Questo aggiornamento risolve un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.

- Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal cubo.

- Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.

- È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.

- È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.

- È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.

- È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.

- È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.

- È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.

- È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.

- È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.

- È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.

- È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.

- Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.

- Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.

- È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.

- È stato risolto un problema per cui la funzione Cerca restituiva un errore.

- È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.

- Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.

- È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.

- Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.

- Sono state notevolmente migliorate le prestazioni del filtro per colore.

- È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.

- Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.

- La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.

- Questo aggiornamento corregge un errore in cui il caricamento dei documenti di Office in OneDrive for Business potrebbe avere esito negativo con il messaggio "Caricamento non riuscito".

- È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.

### <a name="outlook"></a>Outlook

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.

- È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.

- È stato risolto un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.

- È stato corretto un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.

- È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.

- È stato risolto un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni. Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.

- È stato risolto un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.

- È stato risolto un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.

- È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.

- È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.

- È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'apertura della finestra di dialogo Regole.

- È stato risolto un problema che causava un arresto anomalo di Outlook durante l'interazione con determinati collegamenti sicuri.

- È stato risolto un problema che causava ambiguità per i responsabili circa il fatto che un delegato abbia già risposto o meno a una determinata convocazione di riunione.

- È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.

- È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante "OK" quando si provava a contattare il supporto dal contesto di creazione dell'account.

- Questa modifica consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN. Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.

- È stato risolto un problema che causava il malfunzionamento della ricerca nei gruppi moderni.

- È stato risolto un problema che causava agli utenti di Outlook di rimanere bloccati nello stato "Password necessaria" in alcuni scenari.

- È stato risolto un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.

- È stato risolto un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.

- È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.

- È stato risolto un problema per cui venivano visualizzate cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.

- È stato risolto un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo "Conversazione non effettuata".

- È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.

- È stato risolto un problema che causava la mancata visualizzazione dei suggerimenti per i criteri quando si usava un mittente alternativo.

- È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.

- È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.

- È stato risolto un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.

- È stato risolto un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.

- È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.

- È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.

- È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.

- Questa modifica ripristina il nome accessibile per i controlli video di PowerPoint.

- È stato risolto un problema che impediva l'avvio di alcune animazioni.

- Abbiamo risolto un problema che provoca la creazione di schemi duplicati quando si copia una diapositiva da una presentazione a un'altra.

- I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata

- Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti poteva causare l'arresto anomalo di PowerPoint.

- È stato risolto un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.

### <a name="project"></a>Project

- È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.

- È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.

- Il comando Livella tutte non risolve correttamente una sovrassegnazione della risorsa.

- In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.

### <a name="visio"></a>Visio

- L'esportazione in SVG da Visio non funzionava per numerose forme.

### <a name="word"></a>Word

- Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.

- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.

- È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet.

- Abbiamo risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.

- Sono stati risolti diversi problemi che causavano il blocco dell'app durante la chiusura. Sono stati risolti anche alcuni arresti anomali correlati ai componenti aggiuntivi.

### <a name="office-suite"></a>Applicazioni Office

- Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.

- È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.

- È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.

- Si tratta di una correzione per un problema che causava un arresto anomalo all'apertura di un file.

- Può causare un errore in PowerPoint quando si prova a presentare online.

- In alcuni casi, un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica, comportando una perdita di dati.

- È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint. Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.

- È stato risolto un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.

- È stato risolto un bug per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.

- Migliora l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.

- È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.

- È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto. In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.

- È stato risolto un problema per cui, in alcuni casi, un aggiornamento non viene applicato se l'utente non è un amministratore e l'account di sistema non dispone della connettività di rete.

- In alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento. Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.

- È stato risolto un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.

- È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.

- È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.

- Sono stati risolti dei problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.

- È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo.

- Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a>Versione 1902: 14 gennaio
*Versione 1902 (build 11328.20512)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.

### <a name="outlook"></a>Outlook

- Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.

### <a name="powerpoint"></a>PowerPoint

- I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata.

### <a name="word"></a>Word

- Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a>Versione 1808: 14 gennaio
*Versione 1808 (build 10730.20432)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
