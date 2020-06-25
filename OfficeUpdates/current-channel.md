---
title: Note sulla versione per i rilasci del canale corrente in 2020
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale mensile per Microsoft 365 Apps nel 2020
ms.openlocfilehash: 6ff977d90ed98988af281f026276cbc3f0d21807
ms.sourcegitcommit: a0285b69d4d48b5ef4ac3c54678fb67ce399b73e
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/25/2020
ms.locfileid: "44874782"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a>Note sulla versione per i rilasci del canale corrente in 2020

Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del canale corrente in 2020 per le app Microsoft 365 per Enterprise, Microsoft 365 Apps for business e le versioni di sottoscrizione delle app desktop per Project e Visio.

> [!IMPORTANT]
> Apporteremo alcune modifiche ai canali di aggiornamento per App di Microsoft 365, tra cui l'aggiunta di un nuovo canale di aggiornamento (canale mensile Enterprise) e la modifica dei nomi dei canali di aggiornamento già presenti. Per altre informazioni, [leggere questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441).

 > [!NOTE]
>
>- Spesso si tirano fuori le caratteristiche (e talvolta anche le correzioni) alla corrente per un determinato periodo di tempo.  Se non si vede subito un elemento descritto di seguito, è possibile aspettarselo al più presto. [Altre informazioni](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-24"></a>Versione 2005:24 giugno
*Versione 2005 (Build 12827,20470)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo bug è stato risolto. si dovrebbe essere in grado di chiamare il tipo di dati data/ora esteso nel codice senza riscontrare alcun crash nell'app. Si prega di informare il team se si verificano ulteriori problemi.


- Questo problema è stato risolto. è ora possibile ripristinare la versione di accesso più aggiornata e utilizzare DAO/VBA per gestire e modificare un tipo di dati Decimal. Si prega di informare il team di accesso se si verificano ulteriori problemi con l'utilizzo del tipo di dati.


### <a name="excel"></a>Excel

- Risolto un problema che causava la rimozione di XML CustomUI per una scheda della barra multifunzione personalizzata durante il salvataggio in SharePoint/OneDrive.





### <a name="outlook"></a>Outlook

- Risolto un problema a causa del quale Outlook non è stato in grado di abilitare i criteri di protezione dalla perdita dei dati per gli utenti che hanno pagato il servizio che si trovano in M365 Business Plus plans.


- Risolto un problema che indusse gli utenti a visualizzare la data di creazione degli allegati copiati nel file System tramite il drag and drop getting set to January 1, 4501.


- Risolto un problema che indusse gli utenti a visualizzare le regole nel computer in uso &quot; non corrispondono alle regole del messaggio di Microsoft Exchange &quot; quando si aggiornano le regole in Outlook.


- Risolto un problema che indusse gli utenti dei miglioramenti del calendario condiviso a visualizzare gli errori del calendario.


- È stato risolto un problema che causava l'utilizzo di arresti anomali e crash intermittenti in alcuni scenari.


- Risolto un problema che indusse gli utenti a visualizzare continuamente gli avvisi di Outlook per l'esecuzione dello strumento di ripristino Posta in arrivo.


- Risolto un problema che causava la ricerca di una funzionalità in Suggerisci una funzionalità per restituire nessun risultato e lasciare che l'utente non disponga di alcuna opzione per inviare una nuova idea di funzionalità.


### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema di arresto anomalo del riquadro dei suggerimenti.


### <a name="project"></a>Project

- Risolto un problema a causa del quale un'attività contrassegnata con il 100% è stata modificata erroneamente per essere meno del 100% completata.

### <a name="word"></a>Word

- Risolto un problema che potrebbe aver causato un arresto anomalo durante il trascinamento di alcuni contenuti dall'app.


### <a name="office-suite"></a>Applicazioni Office

- Questa modifica si blocca quando si esegue il caricamento e la riproduzione di contenuto animato, ad esempio GIF o modelli 3D.




[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2005-june-09"></a>Versione 2005: giugno 09
*Versione 2005 (Build 12827,20336)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Risolve un problema a causa del quale potrebbe verificarsi un arresto anomalo di Excel quando si tenta di inserire tabelle pivot in un foglio grafico.

### <a name="powerpoint"></a>PowerPoint

- Questo consente di correggere un arresto anomalo quando gli utenti dispongono di commenti sia moderni che legacy in un file, attivando così un aggiornamento dei commenti.

### <a name="project"></a>Project

- Risolto un problema a causa del quale l'evento ProjectBeforeTaskChange non viene generato quando viene apportata una modifica all'attività di riepilogo del progetto, ovvero il campo inizio/attività del progetto.

### <a name="office-suite"></a>Applicazioni Office

- È stato risolto il problema ValidateInstall Fail rate impostando la convalida di installazione di Bing addon su true per impostazione predefinita e considerando che il risultato restituito da MSI come operazione di installazione ha avuto esito positivo.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2005-june-02"></a>Versione 2005:02 giugno
*Versione 2005 (Build 12827,20268)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Utilizzo automatico di nuovi tipi di dati:** Quando si digita un valore di dati simile a un titolo o a una posizione geografica, Excel offre di convertirlo nel tipo di dati connesso a destra, ovvero scorte o geografia. [Altre informazioni](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- **Racconta le tue storie con gif animate:** Le gif animate sono ora supportate nell'editor di Office: i documenti sono stati appena snazzier

### <a name="outlook"></a>Outlook

- **Protezione dei dati nel gruppo:** l'etichetta di riservatezza che si sceglie quando si crea un gruppo viene applicata ai messaggi di posta elettronica, ai documenti e ai siti del team del gruppo

- **Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai. [Altre informazioni](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- **Racconta le tue storie con gif animate:** Le gif animate sono ora supportate nell'editor di Office: i documenti sono stati appena snazzier

- **Il calendario ottiene un rifacimento:** Vedere gli aggiornamenti visivi che semplificano l'analisi del calendario. [Altre informazioni](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

### <a name="powerpoint"></a>PowerPoint

- **Racconta le tue storie con gif animate:** Le gif animate sono ora supportate nell'editor di Office: i documenti sono stati appena snazzier per [saperne di più](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

- **Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione. [Altre informazioni](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Non c'è bisogno di un clicker: gli auricolari sono stati coperti:** Utilizzare gli auricolari di superficie per controllare le presentazioni di PowerPoint. Funzionamento: una volta associati, è necessario abilitare la funzionalità in PowerPoint. Avviare una presentazione premendo F5 o selezionando > di presentazione dall'inizio.  In presentazione fare clic con il pulsante destro del mouse sulla diapositiva e in impostazioni auricolari di superficie scegliere Usa movimenti per controllare la presentazione.  Questa impostazione verrà ricordata per tutte le presentazioni future. Ora è possibile scorrere verso l'interno e l'auricolare sinistro per esplorare le presentazioni in modalità presentazione.  Toccare doppio per riprodurre o sospendere i video incorporati.  Importante: è necessario associare gli auricolari di superficie all'app Surface audio per Windows 10 per utilizzare gesti per controllare le presentazioni. Le istruzioni per iniziare a usare l'app Surface audio su Windows 10 sono disponibili qui. [Altre informazioni](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a>Teams

- **Modifiche apportate al layout video nelle riunioni dei team:** A breve, il numero di partecipanti che possono essere visualizzati contemporaneamente durante una riunione di teams aumenterà da 4 a 9.

- **Includere l'audio del sistema in eventi dinamici:** I relatori e i produttori in eventi dinamici possono ora includere l'audio del sistema quando si condivide una schermata del desktop o della finestra durante l'evento Live. Ciò consentirà agli utenti di ascoltare qualsiasi parte audio del contenuto che si sta condividendo.

- **Abilitare gli organizzatori per modificare le impostazioni della lobby per i partecipanti alle chiamate in ingresso:** Questa impostazione consente di controllare se gli utenti che effettuano la chiamata tramite telefono accedono alla riunione direttamente o attendono nella lobby indipendentemente dall'impostazione di ammetti automaticamente persone.

- **Alzare la mano nelle riunioni:** Gli utenti possono ora generare una mano virtuale in una riunione. Gli altri partecipanti vedranno la tua mano sollevata accanto al tuo nome nella fase di riunione e accanto al tuo nome nell'elenco.

- **Personalizzare gli sfondi video delle riunioni:** Quando si incontrano video, è ora possibile scegliere tra diverse immagini di sfondo statiche da utilizzare. In questo modo è possibile visualizzare l'immagine e non lo sfondo effettivo del percorso in cui si è seduti.

- **Aggiungere altre persone a chat:** È ora possibile aggiungere fino a 350 persone a un singolo thread di chat.

- **Ingranaggio delle impostazioni del feed attività:** Gli utenti possono ora accedere direttamente all'impostazione di notifica e feed attività dalla barra di avanzamento a sinistra tramite un ingranaggio delle impostazioni.

- **Accedere facilmente alle opzioni di riunione dall'interno di una riunione di team in progress:** Per gli organizzatori della riunione, è più facile cambiare rapidamente e facilmente le impostazioni del relatore e della lobby quando una riunione di teams inizia fornendo un collegamento di facile accesso direttamente nel riquadro partecipanti. Questa nuova funzionalità sarà presente sia per le riunioni pianificate che per quelle "incontra ora".

- **Analisi del team e del canale:** Oltre a Team Analytics, è ora possibile visualizzare le metriche e le informazioni di livello del canale. È stato inoltre migliorato il periodo di tempo per 90 giorni, in modo da poter analizzare i dati per periodi più lunghi. A parte questo, questa versione include anche nuove metriche e grafici intorno al numero di post, risposte e riunioni per un team o un canale.

- **Annunci di entrata/uscita:** È stata aggiunta questa funzionalità che consente agli organizzatori di riunioni di abilitare o disattivare gli annunci di entrata e uscita per una riunione.

### <a name="word"></a>Word

- **Decodifica gli acronimi senza lasciare Word:** Quando si incontra un acronimo, Word tenterà di definirlo in base al modo in cui gli altri utenti lo utilizzano.

- **Racconta le tue storie con gif animate:** Le gif animate sono ora supportate nell'editor di Office: i documenti sono stati appena snazzier


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel

- Risolto un problema a causa del quale Excel non rispondeva dopo aver usato CTRL + MAIUSC + tasti di direzione per scorrere quando la finestra di Excel è condivisa tramite Team.

- In alcuni casi, se si fa clic su un collegamento ipertestuale in una posizione all'interno della stessa cartella di lavoro, la cartella di lavoro verrà nascosta.

### <a name="outlook"></a>Outlook

- Ha risolto un problema con l'evento di controllo CLP per l'etichetta di risposta/inoltro.

- Risolto un problema che indusse gli utenti delle versioni di Windows 10 server a visualizzare l'avviso "stato antivirus: non valido". Questa versione di Windows supporta il rilevamento antivirus, ma non è stato trovato alcun antivirus nonostante l'installazione corretta di anti virus.

- Risolto un problema che indusse gli utenti a verificarsi un arresto anomalo durante l'invio di commenti e suggerimenti da una notifica di amministratore.

### <a name="skype"></a>Skype

- Quando a un utente viene assegnato un criterio che lo sposta solo ai team, è ancora in grado di utilizzare il componente aggiuntivo di Skype for Business Outlook per pianificare le riunioni. Dopo questo aggiornamento, non sarà più possibile programmare le riunioni di Skype for business dopo che il client ha letto il criterio che indica che l'utente è solo per i team e immette la modalità di partecipazione alle riunioni. Inoltre, il componente aggiuntivo di Outlook per Skype for business non si attiverà durante l'avvio, se il client Skype for business è in modalità solo partecipazione alle riunioni.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

- L'host di Office si stava bloccando in Windows, quando un componente aggiuntivo viene attivato mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth è impostata su zero. Questa modifica consente di risolvere il problema.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2004-may-21"></a>Versione 2004:21 maggio
*Versione 2004 (Build 12730,20352)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Risolto un problema a causa del quale il collegamento esterno ha smesso di funzionare dopo che il file è stato riaperto se il percorso del file è troppo lungo.


### <a name="outlook"></a>Outlook

- Risolto un problema che indusse gli utenti a verificarsi un arresto anomalo durante l'invio di commenti e suggerimenti da una notifica di amministratore.


### <a name="office-suite"></a>Applicazioni Office

- Risolto un problema di a portata di clic che causava errori di aggiornamento occasionali alle build più recenti.

- Risolto un problema in Microsoft Office in cui i progetti di Visual Basic, Applications Edition con riferimenti previsti per la ricerca dei percorsi specificati nella variabile di ambiente PATH potrebbero non essere trovati correttamente in fase di esecuzione, determinando gli errori di runtime di VBA.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2004-may-12"></a>Versione 2004: 12 maggio
*Versione 2004 (Build 12730.20270)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- Risolve un problema che causava un arresto anomalo quando vengono visualizzate notifiche toast.



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-2004-may-04"></a>Versione 2004: 4 marzo
*Versione 2004 (Build 12730.20250)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="office-suite"></a>Famiglia di prodotti Office

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a>Versione 2004: 29 aprile
*Versione 2004 (Build 12730.20236)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla. Cercare e sostituire il testo nella visualizzazione SQL. Selezionare più tabelle nella finestra Relazioni.

- **Aggiungere tabelle con meno clic**: usare il riquadro attività Aggiungere tabelle, che resta aperto mentre si lavora, per aggiungere tabelle a relazioni e query. [Altre informazioni](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a>Excel

- **Il supporto per il connettore Facebook sta per terminare:** a partire dal 2020 aprile, Excel non supporterà più connessioni dati esterne che usano il connettore Facebook.

- **Avete una domanda? Ask Excel:** ora Excel Ideas consente di fare domande sui dati-non è necessario spendere tempo scrivendo formule (disponibile solo in inglese). [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- **Nuove immagini per dare vita alle cartelle di lavoro:** migliaia di immagini, icone e adesivi gratuiti da usare nelle cartelle di lavoro. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a>Outlook

- **Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online. Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.

- **Nuove immagini per dare vita ai messaggi:** migliaia di immagini, icone e adesivi gratuiti da usare nei messaggi di posta elettronica. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- **Supporto suggerimenti per il luogo di una riunione ricorrente:** cercare sale riunioni con la pianificazione di riunioni ricorrenti.

### <a name="powerpoint"></a>PowerPoint

- **Aggiornamento delle diapositive durante la presentazione:** è possibile aggiornare le diapositive modificate da altri autori durante la presentazione.

- **Nuove immagini per dare vita alle diapositive:** migliaia di immagini, icone e adesivi gratuiti da usare nelle diapositive. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a>Teams

- **Miglioramenti al calendario di Teams:** fare clic con il pulsante destro del mouse su un elemento del calendario per visualizzare le opzioni per le conferme di partecipazione, avviare una chat con i partecipanti alla riunione o partecipare rapidamente a una riunione quando inizia. Sono stati apportati miglioramenti anche al modulo di pianificazione eventi.

- **Tag:** creare tag e assegnarli alle persone, in modo da poter @menzionare un gruppo, un ruolo, un reparto e così via. I proprietari del team possono provarli autonomamente. Passare a un team, selezionare Altre opzioni, Gestisci tag.

### <a name="word"></a>Word

- **Strumenti a portata di mano:** nella casella degli strumenti di disegno c'è la penna intelligente che consente di aggiungere gesti di input penna al testo. [Altre informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- **Nuove immagini per dare vita ai documenti:** migliaia di immagini, icone e adesivi gratuiti da usare nei documenti. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.

- È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.

- Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.


- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.


- È stato risolto un problema che causava l'arresto anomalo di Outlook all'apertura di file con estensione msg o oft salvati in locale dopo un aggiornamento di Windows.


- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.


- È stato risolto un problema che causava un blocco durante la chiusura di Outlook.


### <a name="project"></a>Project

- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.


- È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.

### <a name="office-suite"></a>Applicazioni Office

- È stato risolto un errore che impedisce di limitare e proteggere i file con una password contemporaneamente.



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-april-15"></a>Versione 2003: 15 aprile
*Versione 2003 (Build 12624.20466)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-2003-april-14"></a>Versione 2003: 14 aprile
*Versione 2003 (Build 12624.20442)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.

### <a name="project"></a>Project

- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.

### <a name="word"></a>Word

- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a>Versione 2003: 31 marzo
*Versione 2003 (Build 12624.20382)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="onenote"></a>OneNote

- Informazioni per gli utenti tramite la Barra informazioni sulle rettifiche temporanee in Microsoft OneNote che consentono di migliorare la sincronizzazione e la disponibilità dei servizi durante i picchi di utilizzo in tutto il mondo.

### <a name="project"></a>Project

- È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2003-march-25"></a>Versione 2003: 25 marzo
*Versione 2003 (Build 12624.20320)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo. I messaggi trascinati verranno condivisi con tutti i membri del gruppo.

- **Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web? Outlook ora consente di rimanere connessi in scenari di questo tipo.

### <a name="word"></a>Word

- **Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- In alcuni casi, Excel si arrestava in modo anomalo alla riapertura di una cartella di lavoro incorporata in Word o PowerPoint.

- È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.

- È stato risolto un problema di prestazioni durante la creazione di grafici dai modelli.

### <a name="onenote"></a>OneNote

- Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati. Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.

- Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava la visualizzazione del processo di Outlook in esecuzione in Gestione attività dopo la chiusura.

### <a name="powerpoint"></a>PowerPoint

- È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.


### <a name="project"></a>Project

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.

- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.

- È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.

- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2002-march-10"></a>Versione 2002: 10 marzo
*Versione 2002 (Build 12527.20278)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="project"></a>Project

- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2002-march-01"></a>Versione 2002: 1 marzo
*Versione 2002 (Build 12527.20242)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2002-february-25"></a>Versione 2002: 25 febbraio
*Versione 2002 (Build 12527.20194)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Statistiche della cartella di lavoro:** 
Celle, formule, grafici, tabelle... Li contiamo noi al tuo posto.

- **Profiling dei dati nell'editor di query:** Ottenere un'analisi a colpo d'occhio dei dati nelle colonne, identificare gli errori e i valori vuoti, vedere gli istogrammi di distribuzione e altro ancora.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.

### <a name="outlook"></a>Outlook

- Risolto un problema per cui la virgola nel campo Luogo della riunione cambiava in punto e virgola.

- Risolto un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.

- È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.

- Risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.


- Consente di risolvere un problema che causava la visualizzazione del testo bianco su un sfondo bianco da parte degli utenti con tema nero.


- Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-february-19"></a>Versione 2001: 19 febbraio
*Versione 2001 (Build 12430.20288)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-2001-february-11"></a>Versione 2001: 11 febbraio
*Versione 2001 (Build 12430.20264)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database. Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.

### <a name="excel"></a>Excel

- È stato risolto un problema i comandi di commento nel menu di scelta rapida non venivano visualizzati.

- È stato risolto un problema che causava arresti anomali convertendo il testo in colonne con celle con una matrice con espansione.


### <a name="outlook"></a>Outlook

- Risolve un problema che causava un arresto anomalo specificando un indirizzo Da non valido.


- Risolve un problema che causava un arresto anomalo annullando la configurazione dell'account.


### <a name="project"></a>Project

- È stato risolto un problema per cui il 100% delle attività di tipo durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.


### <a name="office-suite"></a>Famiglia di prodotti Office

- Questo cambiamento affronta i problemi segnalati con le schede grafiche che utilizzano le GPU integrate Intel.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-2001-january-30"></a>Versione 2001: 30 gennaio
*Versione 2001 (build 12430.20184)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Leggere e rispondere all'istante:** Rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.

- **Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X. [Altre informazioni](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a>Outlook

- **Impostazioni avanzate della posta elettronica del gruppo:** questa funzionalità consente a gruppi di utenti di personalizzare i messaggi di posta elettronica o gli eventi da ricevere/seguire nella Posta in arrivo.

- **Criteri di denominazione dei gruppi:** i criteri di denominazione dei gruppi consentono all'amministratore IT di standardizzare e gestire i nomi dei gruppi creati dagli utenti nell'organizzazione. L'amministratore può richiedere l'aggiunta di un prefisso e un suffisso specifici al nome per un gruppo al momento della creazione e può impedire l'utilizzo di parole specifiche. Questo consente di ridurre al minimo l'uso di parole inappropriate nei nomi dei gruppi e di gestire la rappresentazione dei gruppi nella directory. I criteri di denominazione, inoltre, consentono alle organizzazioni che distribuiscono siti del team di categorizzarli in base al reparto.

### <a name="word"></a>Word

- **Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura. [Altre informazioni](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Lazo dell'input penna:** lo strumento Lazo della scheda Disegno consente di selezionare gli oggetti disegnati con l'input penna. È possibile selezionare singoli tratti o parole intere. [Altre informazioni](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Salvataggio delle forme come immagini:** con pochi clic del mouse è possibile salvare una forma, un'icona o un altro oggetto come file di immagine, così da poterlo riutilizzare altrove. [Altre informazioni](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB. L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.


- Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.


### <a name="excel"></a>Excel

- Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.


### <a name="outlook"></a>Outlook

- Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-1912-january-22"></a>Versione 1912: 22 gennaio
*Versione 1912 (Build 12325.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-1912-january-14"></a>Versione 1912: 14 gennaio
*Versione 1912 (Build 12325.20298)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-1912-january-08"></a>Versione 1912: 8 gennaio
*Versione 1912 (Build 12325.20288)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità

### <a name="outlook"></a>Outlook

- **Invio di messaggi accessibili a chi ne ha bisogno:** in Outlook viene visualizzato un suggerimento per i messaggi che consente di assicurarne l'accessibilità dei contenuti durante l'invio a un utente che preferisce contenuti accessibili

### <a name="powerpoint"></a>PowerPoint

- **Ottimizzazione della presentazione per tutti:** Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.

- **GIF in un batter d'occhio:** una diapositiva, un frame. Crea facilmente GIF a ripetizione continua in PowerPoint. [Altre informazioni](https://support.office.com/en-us/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.

### <a name="outlook"></a>Outlook

- È stato risolto un problema per cui il luogo di una riunione veniva inaspettatamente aggiunto di nuovo alla riunione dopo che era stato cancellato.

- È stato risolto un problema che causava un considerevole ritardo quando si interagiva con le cartelle delle cassette postali degli utenti usando i tasti di scelta rapida.

- È stato risolto un problema per cui gli utenti vedevano i messaggi di posta elettronica inviati a un indirizzo che in alcuni casi non corrispondeva all'indirizzo SMTP visualizzato.

- È stato risolto un problema che causava blocchi utente in Outlook durante il recupero delle impostazioni del cloud.

### <a name="word"></a>Word

- L'organizzatore di blocchi predefiniti può visualizzare un avviso non valido: "sono stati modificati gli stili, i blocchi predefiniti".

### <a name="office-suite"></a>Applicazioni Office

- È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.

[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
