---
title: Note sulla versione per le versioni di Channel Enterprise (Preview) semestrali in 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale semestrale (mirato) per Microsoft 365 Apps nel 2020
ms.openlocfilehash: 301194a89cdd6208a98bd0baa471c531e4d8c80e
ms.sourcegitcommit: 1f8cb906d8d0af5eb26eaedf008180375d2fd55d
ms.translationtype: MT
ms.contentlocale: it-IT
ms.lasthandoff: 06/09/2020
ms.locfileid: "44668144"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a>Note sulla versione per le versioni di Channel Enterprise (Preview) semestrali in 2020

Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del canale semestrale (Preview) in 2020 per le app di Microsoft 365 per Enterprise, Microsoft 365 Apps for business e le versioni di sottoscrizione delle app desktop per Project e Visio.

> [!IMPORTANT]
> Apporteremo alcune modifiche ai canali di aggiornamento per App di Microsoft 365, tra cui l'aggiunta di un nuovo canale di aggiornamento (canale mensile Enterprise) e la modifica dei nomi dei canali di aggiornamento già presenti. Per altre informazioni, [leggere questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441).


## <a name="version-2002-june-09"></a>Versione 2002: giugno 09
*Versione 2002 (Build 12527,20720)*

Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- Risolto un problema a causa del quale il collegamento esterno ha smesso di funzionare dopo che il file è stato riaperto se il percorso del file è troppo lungo.

- Risolto un problema a causa del quale Excel non rispondeva dopo aver usato CTRL + MAIUSC + tasti di direzione per scorrere quando la finestra di Excel è condivisa tramite Team.

- È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.

- Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.

- L'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.

- Risolto un problema a causa del quale un simbolo @ che inizia una formula verrebbe considerato un operatore di intersezione implicito.

### <a name="outlook"></a>Outlook

- Consente di partecipare a una riunione di teams direttamente tramite il client di Team nativi.

- Risolto un problema a causa del quale Outlook non è stato in grado di abilitare i criteri di protezione dalla perdita dei dati per gli utenti che hanno pagato il servizio che si trovano in M365 Business Plus plans.

- Risolto un problema che causava l'impostazione di emulazione del browser non corretta quando non è possibile completare la richiesta di autenticazione per Gmail.

- Risolto un problema che causava la verifica dell'errore da parte degli utenti di Outlook sui sistemi operativi del server, "stato antivirus: non valido. Questa versione di Windows supporta il rilevamento antivirus, ma non è stato trovato alcun antivirus "Nonostante sia stato configurato correttamente il virus anti.

### <a name="word"></a>Word

- È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.

### <a name="office-suite"></a>Applicazioni Office

- Questo problema è stato risolto aggiornando i nomi dei canali nei backstage ai nuovi nomi di canale nella forcella January 2020.

- Questo problema è stato risolto e in futuro, se un dispositivo è gestito da criteri, non chiamerà l'API del gruppo di destinatari DMS.

- Risolto il problema in cui si è verificata una rimozione incompleta quando si aggiungono e si rimuovono app in una singola transazione.

- L'host di Office si stava bloccando in Windows, quando un componente aggiuntivo viene attivato mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth è impostata su zero. Questa modifica consente di risolvere il problema.


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

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

- Risolto un problema che indusse gli utenti a non essere in grado di risolvere i messaggi di posta elettronica in una lista di distribuzione personale.

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

- **Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti. [Altre informazioni](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- **Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE.  [Altre informazioni](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- **Cercare a sinistra, cercare a destra... ecco CERCA.X:** riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X.  [Altre informazioni](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)

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


- **Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella cartella di lavoro, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **Concentrarsi su ciò che resta da fare:** selezionare Risolvi per comprimere i commenti e far risaltare quelli ancora non risolti.

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel. [Altre informazioni](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- **Leggere e rispondere all'istante:** è possibile rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.

- **Ottenere le statistiche sulla cartella di lavoro:** le statistiche della cartella di lavoro forniscono una panoramica del contenuto di una cartella di lavoro, per facilitarne la ricerca.





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



### <a name="powerpoint"></a>PowerPoint

- **Collaborazione in tempo reale veloce in PowerPoint:** è possibile collaborare in tempo reale rapidamente in PowerPoint

- **Nuovi strumenti di correzione:** niente più preoccupazione per le parole. PowerPoint offre suggerimenti relativi a grammatica e ortografia. [Altre informazioni](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)


- **Sottotitoli e sottotitoli in tempo reale:** le parole del relatore vengono visualizzate automaticamente sullo schermo come sottotitoli o tradotti in sottotitoli nella lingua scelta. [Altre informazioni](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **La formattazione dei calcoli diventa automatica:** le espressioni matematiche scritte a mano vengono convertite in caratteri standard. Per iniziare, basta selezionare le note scritte a mano e scegliere Da input penna a testo matematico. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora. [Altre informazioni](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- **Trovare e correggere titoli di diapositive mancanti:** i titoli delle diapositive ottimizzano la presentazione e rendono le diapositive accessibili per tutti gli utenti, anche con diverse abilità. L’opzione Verifica accessibilità mostra dove mancano i titoli in modo da aggiungerli in pochi secondi. [Altre informazioni](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella presentazione, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

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

### <a name="visio"></a>Visio

- **Analisi della scena del crimine:** è possibile usare i nuovi stencil Prova, Interni ed Esterni nel modello di indagine della scena del crimine per ricreare in dettaglio le scene del crimine.

- **Creare diagrammi di Visio chiari in Excel:** è possibile creare un diagramma di flussi o un organigramma inserendo i dati in un foglio di lavoro. [Altre informazioni](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Editor per curriculum unito all’Assistente curriculum LinkedIn:** l’editor per il curriculum offre una selezione di controlli grammaticali e stilistici appositamente studiati per i curriculum, per rendere la scrittura più precisa e professionale.

- **Risoluzione di un problema di danneggiamento di un documento causato dall'unione di oggetti 3D:** è stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.

- **Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora. [Altre informazioni](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- **Collaborare con colori vivaci:** i commenti e le modifiche sono contraddistinti da colori associati ai vari collaboratori, in modo che risulti facile identificarli.

- **Modificare i documenti con attivazione macro in modo collaborativo:** è possibile salvare i file docm su OneDrive for Business e modificarli con i collaboratori in tempo reale.

- **Miglioramenti alla creazione condivisa**: prestazioni migliorate per la creazione condivisa nei documenti di Word con revisioni.

- **Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone. Per scoprirle, scegliere Inserisci > Icone. [Altre informazioni](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- **Gli altri utenti possono vedere rapidamente le modifiche:** grazie ai miglioramenti apportati alla creazione condivisa, i collaboratori possono vedere le modifiche in modo più veloce che mai.

- **Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nel documento, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Cancellare con precisione:** è possibile scegliere tra due dimensioni della gomma per correggere le piccole imperfezioni dell'input penna. [Altre informazioni](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.

- **Miglioramenti alla creazione condivisa:** maggiore affidabilità durante la creazione condivisa.

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura. [Altre informazioni](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- **Salvataggio delle forme come immagini:** con pochi clic del mouse è possibile salvare una forma, un'icona o un altro oggetto come file di immagine, così da poterlo riutilizzare altrove. [Altre informazioni](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo &quot;Query danneggiata&quot; quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.

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

- È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante &quot;OK&quot; quando si provava a contattare il supporto dal contesto di creazione dell'account.

- È stato risolto un problema che causava un arresto anomalo durante la creazione del profilo.

- È stato risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.

- È stato risolto un problema per cui gli utenti con il tema Nero visualizzavano l'elenco a discesa &quot;Da&quot; con il testo bianco su sfondo bianco.

- È stato risolto un problema che causava un arresto anomalo annullando la configurazione dell'account.

- È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.

- È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.

- È stato risolto un problema che causava la visualizzazione del messaggio &quot;Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange&quot; all'apertura della finestra di dialogo Regole.

- È stato risolto un problema che causava un arresto anomalo durante la specifica di un indirizzo mittente non valido.

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

- È stato risolto un problema che causava l'invio imprevisto di messaggi di posta elettronica quando gli utenti premevano il tasto &quot;S&quot; dopo aver chiuso il riquadro Verifica accessibilità.

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

- Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: &quot;Sono stati modificati gli stili, i blocchi predefiniti&quot;.

### <a name="office-suite"></a>Applicazioni Office

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

### <a name="office-suite"></a>Applicazioni Office

- È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto. In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.

- È stato risolto un problema per cui, in alcuni casi, un aggiornamento non veniva applicato se l'utente non era un amministratore e non era disponibile la connettività di rete per l'account di sistema.


[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
