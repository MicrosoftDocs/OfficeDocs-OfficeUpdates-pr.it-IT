---
title: Note sulla versione per i partecipanti al programma Office Insider
ms.author: andrewmo
author: v-almuzz
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Offre ai partecipanti al programma Insider Fast un elenco aggiornato delle nuove funzionalità, correzioni o problemi noti principali
ms.openlocfilehash: e43a4c0dfcccd71ff2db672328488e9ffd363d71
ms.sourcegitcommit: cdd69a3af5873fd60a3dabc010339acc19265db3
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 12/06/2019
ms.locfileid: "39890460"
---
# <a name="release-notes-for-office-insiders"></a>Note sulla versione per i partecipanti al programma Office Insider

Questo articolo contiene le note sulla versione per le build Insider di Word, Excel, PowerPoint, Outlook, Access e Project per Windows desktop. Ogni settimana vengono evidenziate nuove funzionalità interessanti, correzioni critiche e problemi significativi di cui è importante essere a conoscenza. Spesso in un determinato periodo di tempo vengono distribuite funzionalità, e a volte anche correzioni, ai partecipanti al programma Insider. Ciò consente di verificare che tutto funzioni correttamente prima di rilasciare la funzionalità a un pubblico più ampio. Pertanto, anche se al momento non fossero disponibili descrizioni, prima o poi lo saranno.  

> [!NOTE]
> - Le note sulla versione vengono pubblicate ogni settimana e possono riguardare più build.
> - La data di pubblicazione delle note sulla versione può non corrispondere all'effettiva data di rilascio della build

 > [!NOTE]
> - Microsoft Teams in installazioni esistenti di Office 365 ProPlus: a partire dalla fine di giugno, Microsoft Teams verrà incluso nelle installazioni esistenti di Office 365 ProPlus (e Office 365 Business) quando si eseguono gli aggiornamenti di queste installazioni. La data in cui Teams verrà aggiunto dipende dal canale di aggiornamento usato. Per altre informazioni fare riferimento a [Distribuire Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/it-IT/deployoffice/teams-install).

[//]: # (NON RIMUOVERE)


## <a name="version-1912-december-06"></a>Versione 1912: 6 dicembre
*Versione 1912 (Build 12325.20012)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Impostazioni avanzate della posta elettronica del gruppo:** questa funzionalità consente a gruppi di utenti di personalizzare i messaggi di posta elettronica o gli eventi da ricevere/seguire nella Posta in arrivo.

- **Criteri di denominazione dei gruppi:** i criteri di denominazione dei gruppi consentono all'amministratore IT di standardizzare e gestire i nomi dei gruppi creati dagli utenti nell'organizzazione. L'amministratore può richiedere l'aggiunta di un prefisso e un suffisso specifici al nome per un gruppo al momento della creazione e può impedire l'utilizzo di parole specifiche. Questo consente di ridurre al minimo l'uso di parole inappropriate nei nomi dei gruppi e di gestire la rappresentazione dei gruppi nella directory. I criteri di denominazione, inoltre, consentono alle organizzazioni che distribuiscono siti del team di categorizzarli in base al reparto.

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Riquadri a schede:** ora è possibile passare da un riquadro all'altro usando un'interfaccia a schede sul lato destro dell'app. L'interfaccia utente sarà visibile solo se sono presenti almeno due riquadri.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.

- È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.

- La disabilitazione dell'accelerazione grafica hardware con risoluzione 4K può comportare un ritardo nel rendering delle celle durante lo scorrimento.

- Se si elimina una formula lunga che si sovrappone a un bordo di cella, è possibile che rimanga visualizzata lungo il bordo di cella.

- È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.

- Il rendering del menu a discesa al margine potrebbe non essere corretto.

### <a name="onenote"></a>OneNote

- OneNote potrebbe non venire aperto tramite il componente aggiuntivo "Note riunione" di Outlook.

### <a name="outlook"></a>Outlook

- Le etichette dei criteri di conservazione potrebbero non mostrare il periodo di conservazione tra parentesi.

- Potrebbero essere visualizzati degli spazi nelle schede contatto con il Language Pack giapponese.

- Le immagini inserite inline nei messaggi di posta elettronica di Outlook talvolta vengono ridimensionate.

### <a name="powerpoint"></a>PowerPoint

- Se un utente ha due (o più) video diversi in una diapositiva in un file cloud, il rendering delle immagini dei video viene eseguito correttamente, ma quando l'utente fa clic su di esse per avviare la riproduzione, il contenuto del video è lo stesso.

- In alcuni casi, lo scorrimento con i dispositivi touch non funziona.

- Il rendering del menu a discesa al margine potrebbe non essere corretto.

- I collegamenti sicuri da un'applicazione di Office a un'altra potrebbero non avviare l'applicazione collegata.

### <a name="project"></a>Project

- Project potrebbe arrestarsi in modo anomalo quando si usa la funzionalità Confronta progetti.

- Se è attiva la modalità scura, quando si passa al riquadro Controllo attività in un'attività con una risorsa sovrassegnata, non è possibile leggere la tabella.

- L'impostazione delle risorse su attività prive di assegnazioni viene arrotondata a 1 giorno.

### <a name="word"></a>Word

- Il salvataggio di un file dopo una stampa unione potrebbe non funzionare in determinate condizioni.

- Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: &quot;Sono stati modificati gli stili, i blocchi predefiniti&quot;.

- Il riquadro Commenti talvolta viene ricaricato quando si usa copia/incolla.

- A volte i commenti non vengono incollati nell'ordine corretto.

- Quando si applica un modello costituito da un elenco a più livelli con stili personalizzati ai documenti esistenti, è possibile che lo stile non venga mantenuto in determinate condizioni.

- Quando si ridimensiona il bordo di uno schermo diviso, potrebbe comparire un altro schermo diviso.

- Il rendering del menu a discesa al margine potrebbe non essere corretto

- Quando si menziona un utente con @ in una scheda commento, potrebbe comparire un codice JSON.

- I collegamenti sicuri da un'applicazione di Office a un'altra potrebbero non avviare l'applicazione collegata.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Per i prodotti basati sul giapponese, il nome e cognome dell'utente dell'account potrebbero essere visualizzati nell'ordine non corretto.

- Quando si passa il puntatore del mouse sui commenti, è possibile che venga visualizzato un contorno di casella di testo attorno al commento.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-15"></a>Versione 1912: 15 novembre
*Versione 1912 (Build 12307.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="insights-services"></a>Servizi Insights

- **Query in linguaggio naturale in Idee in Excel:** nuova caratteristica in Idee di Excel per porre domande in linguaggio naturale sui dati


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- <div><span>La funzionalità Testo in colonne può avere esito negativo per alcune localizzazioni</span></div>


- <div>La modifica delle formule di matrice dinamica all'interno di una cella può comportare l'allineamento del testo all'esterno del contorno della cella</div>


### <a name="outlook"></a>Outlook

- <div>Aggiunta della funzionalità di applicazione della configurazione S/MIME tramite Criteri di gruppo</div>


- <div><span>Le immagini incorporate potrebbero apparire più piccole del previsto</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Il cursore potrebbe sparire dopo aver spostato lo stato attivo dal testo</span></div>


### <a name="project"></a>Project

- <div><span>È possibile che gli utenti riscontrino un errore di licenza</span></div>


- <div><span>Il pulsante Oggi nel controllo di selezione data può talvolta impostare la data non corretta</span></div>


### <a name="word"></a>Word

- <div><span>Talvolta, facendo clic con il pulsante destro del mouse non viene selezionata l'intera parola</span></div>


- <div>Il cursore potrebbe rimanere attivo all'interno di un oggetto dopo la conversione in un formato consigliato</div>


- <div>Le immagini nei messaggi potrebbero essere ridimensionate in modo non corretto in alcuni scenari</div>


- <div>Alcuni temi potrebbero rendere difficile determinare quale commento è selezionato</div>


- <div><span>Selezionando un indicatore del commento ora dovrebbe essere visualizzato il riquadro commenti moderni, se nascosto</span></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>Rispondendo a un commento, la casella di testo potrebbe espandersi in verticale oltre il bordo del riquadro</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-november-08"></a>Versione 1912: 8 novembre
*Versione 1912 (Build 12231.20000)*


[//]: # (NON RIMUOVERE I DETTAGLI DELLA FUNZIONALITÀ DI INIZIO CONTENUTO)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="user-lifecycle"></a>Ciclo di vita degli utenti

- **Miglioramenti dell'esperienza utente per l'attivazione AFO:** aggiornamenti delle schermate che vengono visualizzate quando si attiva Office fornito con il nuovo PC

### <a name="word"></a>Word

- **Esperienza video online nuova e migliorata in Word :** esperienza video online nuova e più sicura, consente di inserire nuovi video e di riprodurre video esistenti in Word


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- <div><span>Arresto anomalo intermittente associato al recupero di contenuto delle cartelle</span></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>L'incollamento di un grafico da Excel a PowerPoint che riduceva le dimensioni del grafico</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-november-01"></a>Versione 1911: 1° novembre
*Versione 1911 (Build 12228.20020)*


[//]: # (NON RIMUOVERE I DETTAGLI DELLA FUNZIONALITÀ DI INIZIO CONTENUTO)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Oggi il contesto segue gli oggetti SVG:** ora è possibile mantenere il testo nelle mappe, nei grafici e in altri vettori SVG quando si convertono questi oggetti in Office

- **Visualizzazione delle opzioni della Penna per Surface quando la si prende:** la prima volta che si usa la Penna per Surface in Word, Excel o PowerPoint, la scheda Disegno si attiverà per agevolare la selezione dei colori della penna.

### <a name="powerpoint"></a>PowerPoint

- **Oggi il contesto segue gli oggetti SVG:** ora è possibile mantenere il testo nelle mappe, nei grafici e in altri vettori SVG quando si convertono questi oggetti in Office

- **Visualizzazione delle opzioni della Penna per Surface quando la si prende:** la prima volta che si usa la Penna per Surface in Word, Excel o PowerPoint, la scheda Disegno si attiverà per agevolare la selezione dei colori della penna.

### <a name="visio"></a>Visio

- **Creare diagrammi di Visio chiari in Excel:** è possibile visualizzare i dati in modo semplice e rapido nei diagrammi di Visio in Excel. [Altre informazioni](https://support.office.com/it-IT/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Visualizzazione delle opzioni della Penna per Surface quando la si prende:** la prima volta che si usa la Penna per Surface in Word, Excel o PowerPoint, la scheda Disegno si attiverà per agevolare la selezione dei colori della penna.

- **Miglioramenti apportati alla creazione condivisa:** l'esperienza di creazione condivisa è stata migliorata, aumentando la probabilità che gli altri utenti ricevano in tempo reale le modifiche apportate al contenuto.

- **Visualizzazione rapida delle modifiche di altri utenti:** grazie ai miglioramenti della creazione condivisa, i collaboratori possono visualizzare le modifiche ancor più velocemente.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema che poteva causare l'arresto anomalo di Excel durante la modifica di un file protetto da una condivisione di rete non attendibile</span></div>


- <div>È stato risolto un problema per cui l'eliminazione di fogli contenenti grafici sparkline che fanno riferimento a un altro foglio poteva far sì che il file venisse identificato come corrotto in fase di riapertura.</div>


- <div>È stato risolto un problema per cui potevano essere ottenuti risultati non corretti durante la conversione di filtri rapporto con il resto della Tabella pivot per le query ai server tabulari SQL.</span></div>


- <div><span>L'uso simultaneo di Assistente vocale e Lente di ingrandimento potrebbe causare un arresto anomalo</span></div>


- <div><span>L'uso simultaneo di Assistente vocale e Lente di ingrandimento potrebbe causare un arresto anomalo</span></div>


### <a name="outlook"></a>Outlook

- <div>Un messaggio di posta elettronica inoltrato potrebbe essere privo di immagini incorporate</div>


- <div><span>Lo strumento Ricerca sala potrebbe mostrare &quot;Nessuna&quot; per le sale disponibili</span></div>


- <div><span>Gli utenti potrebbero non riuscire a creare profili di Outlook con restrizioni rigorose del tenant</div></span>


### <a name="powerpoint"></a>PowerPoint

- <div><span>L'uso simultaneo di Assistente vocale e Lente di ingrandimento potrebbe causare un arresto anomalo</span></div>


### <a name="project"></a>Project

- <div><span>L'utente non è in grado di contrassegnare un'attività come completata e tale attività viene impostata su 99%</span></div>


- <div>Le sovrassegnazioni non vengono risolte dal livellamento</div>


### <a name="word"></a>Word

- <div><span>L'uso simultaneo di Assistente vocale e Lente di ingrandimento potrebbe causare un arresto anomalo</span></div>


- <div><span>L'apertura di documenti legacy e il successivo passaggio alla scheda Informazioni può causare un arresto anomalo</span></div>


- <div><span>I suggerimenti degli strumenti di correzione non vengono visualizzati nei menu di scelta rapida</span></div>


- <div><span>I criteri di contenuto vengono applicati ai commenti in modo errato</span></div>


- <div><span>I commenti legacy scritti con testo scuro non sono visibili in modalità scura</span></div>


- <div><span>Potrebbero essere visualizzati dei caratteri errati quando si usa la correzione automatica coreano/inglese</span></div>


- <div><span>Potrebbero essere applicate etichette criteri inferiori quando dovrebbe avere la priorità un'etichetta criteri di livello superiore</div></span>


- <div><span>I collegamenti di immagini cid: dai messaggi di Outlook&nbsp;ora possono essere interrotti quando richiesto.</div></span>


- <div><span>L'uso simultaneo di Assistente vocale e Lente di ingrandimento potrebbe causare un arresto anomalo</span></div>


- <div><span>La ricerca dal riquadro di spostamento potrebbe non riuscire</span></div>


### <a name="office-suite"></a>Applicazioni Office

- <div><span>Alcuni disegni potrebbero non essere visualizzati in anteprima o nelle presentazioni</span></div>


- <div><span>Alcuni caratteri katakana potrebbero non essere visualizzati correttamente in una casella di testo verticale</span></div>


- <div>Se si tenta di salvare un file in una condivisione di rete disconnessa, potrebbe verificarsi un arresto anomalo</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-25"></a>Versione 1911: 25 ottobre
*Versione 1911 (Build 12215.20006)*


[//]: # (NON RIMUOVERE I DETTAGLI DELLA FUNZIONALITÀ DI INIZIO CONTENUTO)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="visio"></a>Visio

- **Creare diagrammi di Visio chiari in Excel:** è possibile visualizzare i dati in modo semplice e rapido nei diagrammi di Visio in Excel. [Altre informazioni](https://support.office.com/it-IT/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Miglioramenti apportati alla creazione condivisa:** l'esperienza di creazione condivisa è stata migliorata aumentando la probabilità che gli altri utenti ricevano in tempo reale le modifiche apportate al contenuto.

- **Visualizzazione rapida delle modifiche di altri utenti:** grazie ai miglioramenti della creazione condivisa, i collaboratori possono visualizzare le modifiche ancor più velocemente.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- <div><span>Il conteggio record potrebbe non essere corretto</span></div>


### <a name="excel"></a>Excel

- <div><span>Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite</span></div>


- <div><span>Era possibile che gli utenti non riuscissero a salvare in formato cartella di lavoro Excel in Office 365</span></div>


- <div><span>Le caselle di controllo non venivano eseguite correttamente</span></div>


- <div><span>Non era possibile salvare le modifiche apportate alle dimensioni di un grafico</span></div>


- <div><span>Alcune funzioni VBA restituivano un errore nei nuovi tipi di grafico</span></div>


- <div><span>Alcune finestre di dialogo delle origini dati non facevano distinzione tra maiuscole e minuscole per alcuni campi</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>Non era possibile salvare le modifiche apportate alle dimensioni di un grafico</span></div>


### <a name="publisher"></a>Publisher

- <div><span>Le forme potevano essere visualizzate fuori dal bordo dell'elemento grafico</span></div>


### <a name="word"></a>Word

- <div><span>Le forme potevano essere visualizzate fuori dal bordo dell'elemento grafico</span></div>


- <div><span>Evidenziare il testo poteva risultare problematico</span></div>


- <div><span>Poteva non essere possibile passare a un singolo elemento nell'editor</span></div>


- <div><span>Alcuni errori grammaticali o ortografici potevano non essere segnalati</span></div>


- <div><span>Non era possibile salvare le modifiche apportate alle dimensioni di un grafico</span></div>


- <div><span>Poteva risultare impossibile aprire una scheda contatto dopo aver applicato la formattazione a una @menzione</span></div>


- <div><span>È stato risolto un problema per cui può non essere possibile salvare documenti Word, Excel e PowerPoint.&nbsp; Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo &quot;Salva come modello&quot; dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.</span></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>Problema di prestazioni correlato all'uso delle forme in Windows 7</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-october-18"></a>Versione 1911: 18 ottobre
*Versione 1911 (Build 12209.20010)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Invio di messaggi accessibili a chi ne ha bisogno:** in Outlook viene visualizzato un suggerimento per i messaggi che consente di assicurarne l'accessibilità dei contenuti durante l'invio a un utente che preferisce contenuti accessibili

### <a name="powerpoint"></a>PowerPoint

- **Ottimizzazione della presentazione per tutti:** Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.

### <a name="office-suite"></a>Applicazioni Office

- **L'Upload Center verrà sostituito dall'esperienza File che richiedono attenzione:** l'Upload Center sarà sostituito dall'esperienza File che richiedono attenzione visualizzata all'interno delle applicazioni Office in File > Apri. Questa nuova esperienza è più moderna, integrata e meno intrusiva rispetto all'Upload Center.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe</span></div>


- <div><span>È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata</span></div>


### <a name="outlook"></a>Outlook

- <div><span>È stato rilevato un problema che causava il danneggiamento della firma digitale quando si firmava un messaggio di posta elettronica con un allegato con firma digitale</span></div>


- <div><span>È stato rilevato un problema per cui i nomi file lunghi venivano troncati dopo il trascinamento e il rilascio nel corpo del messaggio</span></div>


- <div>È stato rilevato un problema per cui la casella di ricerca spariva quando la barra multifunzione era impostata su Nascondi automaticamente</div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato rilevato un problema per cui le proporzioni dell'anteprima delle diapositive non venivano bloccate/sbloccate correttamente</span></div>

### <a name="project"></a>Project

- <div>È stato rilevato un problema per cui le note venivano cancellate se aggiunte durante operazioni di aggiornamento<br></div>


- <div>È stato rilevato un problema per cui un file poteva venire bloccato da un utente, ma nel messaggio di errore non veniva visualizzato alcun nome utente</div>


- <div><span>È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura</span></div>


### <a name="word"></a>Word

- <div><span>È stato rilevato un problema durante la visualizzazione dei commenti con un'utilità per la lettura dello schermo</span></div>


- <div><span>È stato rilevato un problema per cui alcune critiche venivano identificate come errori di ortografia o grammatica</span></div>


- <div><span>È stato rilevato un problema per cui una nuova finestra di dialogo commento poteva non ottenere lo stato attivo</span></div>


### <a name="office-suite"></a>Applicazioni Office

- <div><span>È stato risolto un problema per cui un aggiornamento potrebbe essere impedito da un messaggio errato di errore di &quot;un'altra installazione in corso&quot;</span></div>

- <div><span>È stato rilevato problema che poteva influire sulla sincronizzazione di una risorsa locale con una risorsa cloud</span></div>

- <div><span>È stato rilevato un problema per cui un messaggio di benvenuto conteneva un collegamento non valido</span></div>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-11"></a>Versione 1910: 11 ottobre
*Versione 1910 (Build 12130.20112)*


[//]: # (NON RIMUOVERE I DETTAGLI DELLA FUNZIONALITÀ DI INIZIO CONTENUTO)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div>È stato risolto un problema relativo all'inserimento di file come oggetti da OneDrive</div>


- <div>È stato risolto un problema per cui era possibile che il formato collegamento ipertestuale non venisse applicato correttamente a determinati tipi di contenuto</div>


- <div>È stato risolto un problema per cui le formule che contenevano riferimenti assoluti strutturati potevano essere adattate in modo non corretto</div>


- <div>È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office</div>


- <div>È stato risolto un problema per cui il contenuto copiato da Excel poteva risultare non corretto se incollato in altre applicazioni di Office</div>


- <div>Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico</div>


### <a name="powerpoint"></a>PowerPoint

- <div>È stato rilevato un problema per cui i dispositivi ARC potrebbero perdere la connessione se in esecuzione in AirSpace WinComp</div>


### <a name="word"></a>Word

- <div>È stato risolto un problema relativo all'inserimento di file come oggetti da OneDrive</div>


- <div>Sono stati migliorati i passaggi per la <span>risoluzione di un problema che causava l'eliminazione del contenuto grafico dai thread di posta elettronica.&nbsp;</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-04"></a>Versione 1910: 4 ottobre
*Versione 1910 (Build 12126.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel. [Altre informazioni](https://support.office.com/it-IT/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema per cui l'area di stampa in anteprima di stampa non era corretta</span></div>


- <div><span>È stato risolto un problema che poteva impedire l'aggiornamento delle tabelle pivot durante una sessione di creazione condivisa</span></div>


### <a name="access"></a>Access

- <div>È stato risolto un problema per cui gli utenti potevano ricevere un errore di &quot;stato incoerente&quot; durante l'uso di un database condiviso.</div>


### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema che poteva causare la duplicazione delle cartelle di posta elettronica</span></div>


- <div><span>È stato risolto un problema che poteva causare un messaggio di errore non corretto tentando di inviare posta con crittografia S/MIME</span></div>


- <div><span>È stato risolto un problema per cui la ricezione di un messaggio di "Conversazione non effettuata" da Skype poteva causare un arresto anomalo</span></div>


- <div><span>È stato risolto un problema che poteva causare la perdita di memoria</span></div>


- <div><span>È stato risolto un problema che poteva causare la modifica del nome del mittente al salvataggio del messaggio come bozza</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span></span></div>È stato risolto un problema che causava il danneggiamento degli intervalli di testo dopo aver incollato testo nei segnaposto intestazione/piè di pagina/numero diapositiva in schema diapositiva e layout diapositiva


- <div><span></span></div>È stato risolto un problema che impediva la creazione del collegamento ipertestuale incollando testo con un collegamento ipertestuale


- <div>È stato risolto un problema che impediva il corretto funzionamento delle statistiche</div>


### <a name="word"></a>Word

- <div><span>È stato risolto un problema per cui i colori dei tipi di carattere non venivano applicati</span></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div>È stato risolto un problema per cui poteva essere offerta la cronologia delle versioni anche se la funzionalità era disabilitata</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-27"></a>Versione 1910: 27 settembre
*Versione 1910 (Build 12119.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)
[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)
[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie</span></div>


### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema che poteva causare la segnalazione di errori di autorizzazione durante l'interazione con cartelle di calendari condivisi</span></div>


- <div><span>È stato risolto un problema che poteva impedire agli utenti di aggiungere allegati ai calendari</span></div>


- <div><span>È stato risolto un problema che causava la visualizzazione di messaggi di errore rispondendo a un messaggio con firma digitale</span></div>


### <a name="word"></a>Word

- <div><span>È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet</span></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>È stato risolto un problema per cui il testo in grassetto medio poteva essere reso con lo stile errato</span></div>


- <div><span>È stato risolto un problema per cui l'utente poteva ricevere un messaggio di errore non corretto alla chiusura di un file con caricamento in sospeso</span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-20"></a>Versione 1910: 20 settembre
*Versione 1910 (Build 12112.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema per cui Excel poteva talvolta bloccarsi all'avvio</span></div>

### <a name="outlook"></a>Outlook

- <div><span>Sono state notevolmente migliorate le prestazioni di selezione della sala quando sono disponibili numerose sale</span></div>


- <div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">È stato risolto un problema che può impedire la sincronizzazione della cassetta postale per i clienti che hanno più cassette postali di Outlook quando si esegue la migrazione all'autenticazione moderna in Office 365.</span><br></div>


- <div><span>È stato risolto un problema per cui alcuni caratteri nelle etichette delle firme non vengono visualizzati nel menu a discesa</span></div>


### <a name="project"></a>Project

- <div><span>È stato risolto un problema che poteva causare un arresto anomalo sostituendo una risorsa dell'organizzazione con una risorsa locale</span></div>


### <a name="word"></a>Word

- <div><span>È stato risolto un problema che poteva impedire il funzionamento corretto dello scorrimento sincrono in visualizzazione Bozza</span></div>


- <div>È stato risolto un problema che poteva impedire la visualizzazione corretta delle descrizioni comandi dopo aver salvato un documento per la prima volta</div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-september-13"></a>Versione 1910: 13 settembre
*Versione 1910 (Build 12105.20000)*


[//]: # (NON RIMUOVERE INIZIO CONTENUTO DETTAGLI DEL BUG)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema che poteva impedire a un utente di incollare collegamenti ipertestuali in alcuni fogli protetti</span></div>


### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema per cui l'interfaccia utente poteva rimanere bloccata in una visualizzazione compatta</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato risolto un problema per cui poteva verificarsi un errore durante la stampa in formato PDF</span></div>


### <a name="project"></a>Project

- <div><span>È stato risolto un problema per cui <span style="display:inline !important;background-color:rgb(255, 255, 255);font-size:13.33px;">le modifiche apportate a un valore di lavoro per un'attività di riepilogo potevano causare un arresto anomalo se era abilitato il lavoro protetto</span></span></div>


- <font size=2 style="background-color:rgb(255, 255, 255);">È stato risolto un problema che poteva impedire la sincronizzazione degli eventi con i calendari dell'organizzazione</font>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>È stato risolto un problema che poteva comportare un avviso ripetuto per l'eliminazione delle versioni locali di un file</span></div>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEL BUG)

## <a name="version-1910-september-06"></a>Versione 1910: 6 settembre
*Versione 1910 (Build 12030.20004)*


[//]: # (NON RIMUOVERE I DETTAGLI DELLA FUNZIONALITÀ DI INIZIO CONTENUTO)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Pronti, partenza, disegna:** quando si afferra la Penna per Surface, si è pronti per disegnare. [Altre informazioni](https://support.office.com/it-IT/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="powerpoint"></a>PowerPoint

- **Pronti, partenza, disegna:** quando si afferra la Penna per Surface, si è pronti per disegnare. [Altre informazioni](https://support.office.com/it-IT/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

### <a name="word"></a>Word

- **Pronti, partenza, disegna:** quando si afferra la Penna per Surface, si è pronti per disegnare. [Altre informazioni](https://support.office.com/it-IT/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema che poteva comportare una differenza tra il nome del carattere sulla barra multifunzione e il carattere utilizzato</span></div>


### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema che poteva comportare il consumo inappropriato delle risorse da parte di Outlook quando la Modalità protetta era disabilitata per i siti con restrizioni in Internet Explorer</span></div>


- <div><span>È stato risolto un problema che a volte poteva causare la comparsa di caratteri Unicode quando si incolla il testo da un'origine ANSI</span></div>


- <div><span>È stato risolto un problema per cui alcuni utenti risultavano offline per errore in una visualizzazione della pianificazione di gruppo</span></div>


### <a name="word"></a>Word

- <div><span>È stato risolto un problema che poteva comportare la perdita della formattazione della tabella</span></div>


- <div><span>È stato risolto un problema che poteva compromettere la scelta rapida da tastiera CTRL+V</span></div>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUDGET DI FINE CONTENUTO)

## <a name="version-1909-august-30"></a>Versione 1909: 30 agosto
*Versione 1909 (Build 12026.20000)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità

### <a name="access"></a>Access

- **Trovare velocemente le tabelle collegate:** la nostra nuova casella di ricerca rende molto più facile trovare le tabelle collegate.

### <a name="powerpoint"></a>PowerPoint

- **Salvare un'illustrazione in formato SVG:** è possibile salvare un grafico, una forma o un'altra illustrazione in formato SVG (Scalable Vector Graphic), che può essere ridimensionato senza perdita di qualità dell'immagine. [Altre informazioni](https://support.office.com/it-IT/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema in cui il suggerimento tasto di scelta per &nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">Sensibilità </span>era&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);">in conflitto con un altro suggerimento tasto di scelta.</span></span></div>

- <div><span>È stato risolto un problema che si verificava quando si cercava di salvare una cartella di lavoro condivisa in fase di modifica.</span></div>

- <div><span>È stato risolto un problema per cui Excel elencava solo i primi 16 componenti aggiuntivi presenti nei valori '\Excel\Add-in Manager' del Registro di sistema.<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"></span></span></div>


- <div><span>È stato risolto un problema per cui la funzione Frequency() restituiva risultati errati.</span></div>


- <div><span>Le prestazioni del filtro per colore sono state notevolmente migliorate.</span></div>


- <div><span>È stato risolto un problema relativo agli utenti di Surface in cui lo spostamento del mouse poteva essere interpretato come un evento clic del mouse.</span></div>


- <div><span>È stato risolto un problema che impediva gli spostamenti da tastiera nella finestra di dialogo Trova/Sostituisci.</span></div>


- <div><span>È stato risolto un problema per cui il nome di alcuni tipi di carattere non venivano visualizzati correttamente.</span></div>


- <div><span>È stato risolto un problema che impediva la visualizzazione del formato CSV nei tipi di file supportati.</span></div>


### <a name="access"></a>Access

- <div>È stato risolto un problema per cui gli utenti potevano ricevere un errore di &quot;stato incoerente&quot; durante l'uso di un database condiviso.</div>


- <div><span>È stato risolto un problema per cui il controllo selezione data veniva visualizzato per errore.</span></div>


### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema che impediva la visualizzazione di contenuto HTML per alcuni utenti POP3.</span></div>


- <div><span>È stato risolto un problema relativo alla rimozione del collegamento 'Planner' non funzionante dal menu riversamento nella scheda contatto durante l'uso in ambienti in cui non era disponibile.</span></div>

### <a name="onenote"></a>OneNote

- <div><span>È stato risolto un problema in cui la sincronizzazione in background di&nbsp;OneNote talvolta acquisiva erroneamente lo stato attivo.</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato risolto un problema che influiva sull'orientamento della rotazione di un effetto Giravolta 3D.</span></div>

- <div><span>È stato risolto un problema che impediva il corretto funzionamento di alcuni collegamenti ipertestuali se contenevano caratteri speciali.</span></div>

- <div><span>È stato risolto un problema che causava l'apertura simultanea di più riquadri commenti.</span></div>

### <a name="project"></a>Project

- <div><span>È stato risolto un problema che poteva talvolta causare un arresto anomalo del sistema durante la stampa di una visualizzazione di Pianificazione team.</span></div>

### <a name="word"></a>Word

- <div><span>È stato risolto un problema per cui i caratteri multibyte in una casella di testo verticale venivano visualizzati sovrapposti nella visualizzazione di lettura.<br></span></div>

- <div><span>È&nbsp;<span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">stato risolto un problema per cui le risorse dei componenti aggiuntivi correlate a cartoline o biglietti di auguri giapponesi non venivano trovate quando l'utente eseguiva un'azione nella procedura guidata dei componenti aggiuntivi.</span></span></div>

- <div><span>È stato risolto un problema che poteva causare problemi relativi all'interfaccia utente della barra del titolo in visualizzazione protetta.</span></div>

### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span><span style="display:inline !important;background-color:rgba(255, 255, 255, 1);"> È stato risolto un problema di file danneggiato quando si esegue Cambia forma su una selezione che contiene sia una forma normale che una forma connettore.</span></span></div>

- <div><span>È stato risolto un problema che <span style="display:inline !important;background-color:rgba(255, 255, 255, 1);color:rgba(0, 0, 0, 0.9);">causava un problema nelle applicazioni durante il collegamento o lo scollegamento da più monitor esterni. </span></span></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="august-23-2019br"></a>**23 agosto 2019**<br/>
Versione 1909 (Build 12015.20004)<br/>



## <a name="non-security-updates"></a>Aggiornamenti non della sicurezza:

### <a name="excel"></a>Excel

- <div><span>Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite</span></div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>È stato risolto un problema che poteva impedire la visualizzazione di alcuni caratteri Unicode all'interno di un browser</span></div>


### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema che poteva impedire il salvataggio di file in una posizione WebDAV</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato risolto un problema per cui un utente faceva clic su un commento, ma veniva selezionato un altro commento</span></div>





## <a name="august-16-2019br"></a>**16 agosto 2019**<br/>
Versione 1909 (Build 12013.20000)<br/>

### <a name="powerpoint-feature-updates"></a>Aggiornamenti delle funzionalità di PowerPoint:

- **Stampa dei numeri delle diapositive negli stampati:** i numeri delle diapositive vengono inclusi automaticamente negli stampati. Lasciarli attivati o disattivarli è a discrezione dell'utente.




## <a name="non-security-updates"></a>Aggiornamenti non della sicurezza:

### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema che causava l'abilitazione del salvataggio automatico</span></div>


- <div>È stato risolto un problema che poteva comportare una misurazione inesatta delle altezze delle celle</div>


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>È stato risolto un problema che migliora significativamente le prestazioni della funzionalità Commenti</span></div>


- <div><span>È stato risolto un problema che poteva causare un arresto anomalo usando i tasti di direzione durante una ricerca</span></div>


- <div><span>È stato risolto un problema che poteva impedire di creare una @menzione se il simbolo @ veniva inserito dopo determinati caratteri</span></div>


- <div><span>È stato risolto un problema che poteva causare un arresto anomalo quando si eliminavano @menzioni</span></div>


- <div><span>È stato risolto un problema che impediva la visualizzazione corretta delle emoji nelle schede commento</span></div>


- <div><span>È stato risolto un problema per cui lo stato attivo degli Appunti poteva causare un arresto anomalo</span></div>


- <div><span>È stato risolto un problema che causava il mancato funzionamento dei pulsanti della barra di accesso rapido</span></div>


- <div><span>È stato risolto un problema che impediva all'anteprima della formattazione del documento di passare allo sfondo</span></div>

### <a name="onenote"></a>OneNote

- È stato risolto un problema per cui i nomi delle sezioni appaiono vuoti nell'elenco a discesa della sezione quando il tema di Office è impostato su nero.

### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema con l'invio di eventi per cui Outlook poteva assumere e perdere ripetutamente lo stato attivo</span></div>


- <div><span>È stato risolto un problema che impediva il funzionamento della scelta rapida da tastiera Inserisci risposta nella cartella</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato risolto un problema con la visualizzazione protetta che talvolta causava errori durante la collaborazione</span></div>


- <div><span>È stato risolto un problema che poteva impedire la visualizzazione corretta delle attività nei riquadri dei commenti</span></div>


- <div><span>È stato risolto un problema che poteva causare un arresto anomalo durante l'inserimento di nuove diapositive</span></div>


### <a name="user-lifecycle"></a>Ciclo di vita degli utenti

- <div><span>È stato risolto un problema che a volte comportava la scomparsa delle funzionalità in abbonamento</span></div>


### <a name="word"></a>Word

- <div><span>È stato risolto un problema per cui i collegamenti ipertestuali potevano non funzionare se contenevano determinati caratteri</span></div>


- <div><span>È stato risolto un problema per cui, visualizzando un commento per un'immagine, questa poteva essere ridimensionata in modo errato</span></div>


- <div><span>È stato risolto un problema con il menu a discesa degli elenchi puntati che poteva causare un arresto anomalo</span></div>





## <a name="august-09-2019br"></a>**9 agosto 2019**<br/>
Versione 1909 (Build 12001.20000)<br/>

### <a name="excel-feature-updates"></a>Aggiornamenti delle funzionalità di Excel:

- **La collaborazione è stata semplificata:** i miglioramenti apportati alla creazione condivisa indicano che, quando si usa la formattazione condizionale, gli stili cella e così via, le modifiche vengono unite perfettamente con quelle dei propri collaboratori.


- **Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono state trovate.


### <a name="office-suite-feature-updates"></a>Aggiornamenti delle funzionalità della Famiglia di prodotti Office:

- **Nuove icone dell’app di Office:** le icone dell'app sono state riprogettate per riflettere l'esperienza semplice, potente e intelligente di Office


### <a name="outlook-feature-updates"></a>Aggiornamenti delle funzionalità di Outlook:

- **Protezione avanzata dalle minacce:** con Office 365 Advanced Threat Protection, si è protetti dalle minacce tramite collegamenti ipertestuali negli oggetti di posta elettronica, messaggi allegati, messaggi firmati, percorsi di rete e così via.


- **Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono state trovate.


### <a name="powerpoint-feature-updates"></a>Aggiornamenti delle funzionalità di PowerPoint:

- **Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono state trovate.


### <a name="word-feature-updates"></a>Aggiornamenti delle funzionalità di Word:

- **Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.


- **Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono state trovate.




## <a name="non-security-updates"></a>Aggiornamenti non per la sicurezza:

### <a name="outlook"></a>Outlook

- <div><span>È stato risolto un problema che causava la ricezione di due notifiche da parte dei destinatari della riunione dopo l'annullamento di una riunione</span></div>


### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato risolto un problema che causava un arresto anomalo quando l'utente ha selezionato Nessun contorno o Nessun riempimento per forme e icone</span></div>





## <a name="august-02-2019br"></a>**2 agosto 2019**<br/>
Versione 1908 (Build 11929.20002)<br/>

### <a name="excel-feature-updates"></a>Aggiornamenti delle funzionalità di Excel:

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.


- **Applicare etichette di riservatezza ai documenti:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione.


### <a name="outlook-feature-updates"></a>Aggiornamenti delle funzionalità di Outlook:

- **Applicare etichette di riservatezza ai documenti:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione.


### <a name="powerpoint-feature-updates"></a>Aggiornamenti delle funzionalità di PowerPoint:

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.


- **Applicare etichette di riservatezza ai documenti:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione.


### <a name="word-feature-updates"></a>Aggiornamenti delle funzionalità di Word:

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.


- **Dirlo in altre parole:** se si vuole dirlo in altre parole, è possibile riscriverlo. La riscrittura offre alternative per rifinire le frasi.


- **Applicare etichette di riservatezza ai documenti:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione.




## <a name="non-security-updates"></a>Aggiornamenti non della sicurezza:

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="excel"></a>Excel

- <div><span>È stato risolto un problema che faceva sembrare che si applicasse &quot;Ripeti tutte le etichette&quot; durante la stampa di un PDF</span></div>

### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><span>È stato risolto un problema che impediva agli utenti di aprire un documento dal desktop</span></div>

- <div><span>È stato risolto un problema per cui un aggiornamento potrebbe essere impedito da un messaggio errato di errore di &quot;un'altra installazione in corso&quot;</span></div>

- <div><span>È stato risolto un problema che consente a un utente di visualizzare i messaggi di errore durante l'installazione degli aggiornamenti di sicurezza</span></div>

- <div><span>È stato risolto un problema che potrebbe far scomparire il cursore</span></div>

- <div><span>È stato risolto un problema per cui veniva visualizzata per impostazione predefinita la scheda Disegno invece della scheda Home</span></div>

- <div><span>È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo</span></div>

### <a name="outlook"></a>Outlook

- <div></div><span style="font-size:11.0pt;font-family:&quot;Calibri&quot;,sans-serif;">È stato risolto un problema che può causare richieste ripetute di password</span>

- <div><span>È stato risolto un problema che impediva l'esecuzione corretta della query di un indirizzo di posta elettronica</span></div>

- <div><span>È stato risolto un problema che impediva agli utenti di aprire gli elementi del calendario creati da versioni legacy di Outlook</span></div>

### <a name="powerpoint"></a>PowerPoint

- <div><span>È stato risolto un problema che impediva l'avvio di alcune animazioni</span></div>

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

### <a name="word"></a>Word

- <div><span>È stato risolto un problema per cui le risposte ai commenti potrebbero non essere più ordinate</span></div>

- <div><span>È stato risolto un problema per cui in alcune situazioni verranno visualizzati suggerimenti anziché commenti</span></div>

- <div><span>È stato risolto un problema per cui potrebbe essere visualizzato il riquadro revisioni quando si prova ad aggiungere un nuovo commento</span></div>

- <div><span>È stato risolto un problema che potrebbe impedire la visualizzazione dell'elenco a discesa Annulla</span></div>

- <div><span>È stato risolto un problema che impediva l'aggiunta di commenti</span></div>


## <a name="july-26-2019"></a>26 luglio 2019
Versione 1908 (build 11916.20000)

## <a name="whats-new"></a>Novità:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="create-more-accessible-pdfs"></a>Creare file PDF accessibili

Creare un file PDF e Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto

- È stato risolto un problema per il quale talvolta si poteva interrompere l’associazione del tipo di file e delle icone dopo l'aggiornamento di Office.

### <a name="word"></a>Word 
- Diverse correzioni a prestazioni e stabilità

### <a name="excel"></a>Excel
- È stato risolto un problema per cui lo spostamento di un grafico poteva causare un arresto anomalo
- È stato risolto un problema per il quale a volte si poteva verificare un errore nell’ottenere un oggetto della Cartella di lavoro dall'oggetto Grafico dopo aver modificato i tipi di grafici

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui, in una barra multifunzione semplificata, un controllo disabilitato a volte poteva non essere disattivato sulla barra multifunzione

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="july-19-2019"></a>19 luglio 2019
Versione 1908 (Build 11911.20000)

## <a name="whats-new"></a>Novità:

### <a name="word"></a>Word

#### <a name="learn-what-acronyms-mean-when-you-read-in-word-online"></a>Informazioni sugli acronimi durante la lettura in Word Online

Quando viene rilevato un acronimo, Word proverà a definirlo usando i dati dell'organizzazione.


## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema per cui il tag BookMarkEnd era mancante.
- È stato risolto un problema per cui la selezione del carattere poteva cambiare durante la digitazione di caratteri speciali
- È stato risolto un problema che poteva talvolta causare una risposta vuota a una nuova scheda commento
- È stato risolto un problema che poteva causare la perdita della formattazione durante la condivisione di un messaggio di posta elettronica

### <a name="excel"></a>Excel
- È stato risolto un problema per cui una matrice con un intervallo molto ampio poteva talvolta causare un arresto anomalo
- Le prestazioni di copia dei dati da intervalli filtrati sono state notevolmente migliorate
- È stato risolto un problema che impediva l'apertura di alcuni file se i nomi file contenevano caratteri speciali

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema per cui il nome della sezione non veniva selezionato per impostazione predefinita per le nuove sezioni create in PowerPoint.
- È stato risolto un problema che causava difficoltà nell'uso dell'interfaccia utente su schermo 4:3

### <a name="outlook"></a>Outlook
- È stato risolto un problema che poteva impedire la visualizzazione dell'elenco di sale disponibili
- È stato risolto un problema che impediva l'uso della formattazione HTML per alcuni utenti POP3

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="july-12-2019"></a>12 luglio 2019
Versione 1907 (Build 11901.20038)

## <a name="whats-new"></a>Novità:

### <a name="powerpoint"></a>PowerPoint
 
#### <a name="use-ink-replay-in-your-presentations"></a>Usare la riproduzione input penna nelle presentazioni
 
Applicare un'animazione di riproduzione input penna in PowerPoint per aggiungere contenuti e comunicare di più nelle presentazioni. 

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- Diverse correzioni a prestazioni e stabilità

### <a name="excel"></a>Excel
- Diverse correzioni a prestazioni e stabilità

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- Diverse correzioni a prestazioni e stabilità

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="july-5-2019"></a>5 luglio 2019
Versione 1907 (Build 11901.20018)

## <a name="whats-new"></a>Novità:

### <a name="word-excel-powerpoint"></a>Word, Excel, PowerPoint

#### <a name="sketchy-shapes"></a>Forme Schizzo

Se si sta lavorando a una bozza di presentazione, è possibile applicare lo stile Schizzo per indicare che non è ancora finale. Questo stile consente di conferire un tocco personale agli oggetti senza trasformarli in forme libere, disegnate a mano.

### <a name="excel"></a>Excel

- **Condivisione dei file più rapida**: è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.
### <a name="powerpoint"></a>PowerPoint

- **L'impostazione per la stampa dei numeri di diapositiva in stampati è stata spostata nel menu Stampa per semplificare l'accesso:** trovarla nell'elenco a discesa Stampa > layout di stampa quando è selezionato un layout Stampati. L'opzione consente inoltre di attivare o disattivare facilmente la presentazione. [Altre informazioni](https://support.office.com/it-IT/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

### <a name="word"></a>Word

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto
- Le prestazioni dei suggerimenti tasto di scelta della barra multifunzione sono state notevolmente migliorate
- È stato risolto un problema che impediva la visualizzazione corretta della finestra di dialogo "Scopri le prossime novità"
- È stato risolto un problema che poteva causare il disallineamento di Foto nel riquadro a comparsa della raccolta di Creazione condivisa

### <a name="word"></a>Word 
- È stato risolto un problema che poteva talvolta impedire l'aggiunta di nuovi commenti
- È stato risolto un problema per cui le tabelle potevano talvolta causare un arresto anomalo
- È stato risolto un problema per cui alla fine di una stampa unione potevano essere aggiunti dati non validi
- È stato risolto un problema che poteva causare il rendering non corretto di alcune equazioni LaTeX

### <a name="excel"></a>Excel
- È stato risolto un problema per cui la modifica dei tipi di grafico poteva causare un'eccezione di runtime
- È stato risolto un problema che causava la visualizzazione di una barra multifunzione errata all'apertura di più finestre
- È stato risolto un problema che poteva causare un errore quando una macro apriva una seconda istanza di una cartella di lavoro
- È stato risolto un problema che poteva causare un arresto anomalo durante l'apertura o la creazione di una cartella di lavoro o il passaggio da una cartella di lavoro all'altra
- È stato risolto un problema che impediva agli utenti di aprire in Teams un PDF creato in Word

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema che poteva peggiorare la qualità di un grafico esportato in un PDF
- È stato risolto un problema che impediva la visualizzazione di una descrizione comando con l'indicazione della distanza dal centro

### <a name="outlook"></a>Outlook
- È stato risolto un problema che poteva talvolta impedire la visualizzazione dell'errore Disco pieno
- È stato risolto un problema che poteva causare la duplicazione degli allegati durante l'aggiornamento di una convocazione di riunione

### <a name="access"></a>Access
- È stato risolto un problema che impediva ad alcune query di restituire valori interi di grandi dimensioni
- È stato risolto un problema che poteva impedire la modifica della casella di testo SQL
- È stato risolto un problema per cui le descrizioni comandi potevano essere difficili da visualizzare in alcuni schermi con valori DPI elevati

### <a name="project"></a>Project
- È stato risolto un problema che poteva impedire la modifica dei valori di contrassegno nelle nuove attività
- È stato risolto un problema per cui un aggiornamento di stato poteva impostare una data di inizio effettivo errata nelle assegnazioni e nelle attività
- È stato risolto un problema che poteva comportare la sovrassegnazione errata di alcune risorse
- È stato risolto un problema per cui il metodo Add di TaskDependencies poteva non riuscire quando veniva aggiunto un elemento Lag, il separatore decimale era una virgola e in caso di connessione a un server
- È stato risolto un problema per cui l'aggiornamento dei valori delle tabelle di ricerca dei campi personalizzati locali tramite CSOM poteva causare l'arresto anomalo dei PC
- È stato risolto un problema per cui i valori totali del lavoro potevano risultare errati se contenevano un numero decimale

</BR></BR>

## <a name="june-28-2019"></a>28 giugno 2019
Versione 1907 (Build 11819.20002)

## <a name="whats-new"></a>Novità:

### <a name="excel"></a>Excel

- **Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi. Semplice individuazione di funzioni, colonne e parametri

- **Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle.

### <a name="word"></a>Word

- **Miglioramenti alla creazione condivisa:** affidabilità migliore durante la creazione condivisa.
 
### <a name="word-excel-powerpoint-and-visio"></a>Word, Excel, PowerPoint e Visio

#### <a name="recommended-documents"></a>Documenti consigliati

Individuare i documenti con attività rilevanti consigliati.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema che impediva di aprire alcuni file .DOC.
- È stato risolto un problema che poteva impedire il caricamento corretto dei commenti.

### <a name="excel"></a>Excel
- Sono state migliorate le prestazioni di Power Query.

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema relativo all'uso di una penna su un dispositivo Surface che poteva causare lo sfarfallio dello schermo.

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui lo stato di disponibilità di un appuntamento poteva cambiare quando veniva convertito in una riunione.
- È stato risolto un problema per cui un modello e una descrizione non corretti venivano visualizzati quando un messaggio di posta elettronica era protetto con un modello ad-hoc.

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="june-21-2019"></a>21 giugno 2019
Versione 1907 (Build 11815.20002)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

#### <a name="dark-mode-for-black-theme-in-outlook-desktop"></a>Modalità scura per il tema nero nella versione desktop di Outlook

Durante la lettura e la composizione dei messaggi di posta elettronica, gli utenti che utilizzano la modalità scura ora visualizzeranno il riquadro di lettura e di composizione con uno sfondo nero. Nel riquadro di lettura e sulla barra multifunzione, è presente un interruttore con l'icona sole/luna, nel caso in cui gli utenti desiderino visualizzare l'anteprima del messaggio con uno sfondo chiaro.

#### <a name="getting-started"></a>Guida introduttiva:

1. Se si attiva il tema nero, la modalità scura sarà attiva per impostazione predefinita.
2. Usare l'interruttore con l'icona sole/luna (presente nel riquadro di lettura e sulla barra multifunzione) per visualizzare l'anteprima del messaggio per gli utenti che non utilizzano la modalità scura.

#### <a name="scenarios-to-try"></a>Scenari da provare

1. Leggere i messaggi di posta elettronica in modalità scura. Se non si riesce a leggere parte del testo, utilizzare l'interruttore a forma di sole nel riquadro di lettura per passare a uno sfondo chiaro. 
2. Comporre i messaggi di posta elettronica in modalità scura. Visualizzare l'anteprima del messaggio con uno sfondo chiaro utilizzando l'interruttore con l'icona del sole presente sulla barra multifunzione. 

Nel caso in cui i messaggi di posta elettronica non vengano visualizzati correttamente, inviarli come allegato a OutlookDarkModeFail@service.microsoft.com

#### <a name="get-location-suggestions"></a>Ottenere suggerimenti per il luogo

Iniziare a digitare e Outlook cercherà le località corrispondenti.

Ciò si applica al campo Luogo durante la creazione di appuntamenti e riunioni.

#### <a name="getting-started"></a>Guida introduttiva:

- Creare un appuntamento o una riunione in un calendario di Office 365 o Outlook.com in Outlook. 
- Fare clic nel campo Luogo e iniziare a digitare...

#### <a name="scenarios-to-try"></a>Scenari da provare

Quando si aggiunge una sala riunioni a una riunione, fare clic sul campo Luogo anziché utilizzare il componente aggiuntivo Ricerca sala o la Rubrica.
Per gli appuntamenti in un luogo fisico pubblico (ad esempio, un ristorante, un bar o uno studio dentistico), cercare la posizione esatta utilizzando la nuova selezione. In questo modo, sarà possibile ricevere una notifica su Outlook Mobile al momento di andar via.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto
- È stato risolto un problema per cui la casella di ricerca rimaneva abilitata offline.

### <a name="word"></a>Word 
- È stato risolto un problema per cui talvolta risultava difficile visualizzare lo stato attivo della tastiera.
- È stato risolto un problema per cui talvolta il testo incollato in un nuovo documento presentava un allineamento non corretto.
- È stato risolto un problema che impediva ad alcuni utenti di salvare le modifiche dopo aver attivato lo stato di sospensione del computer.
- È stato risolto un problema per cui, in alcuni casi, veniva stampato un intero documento anziché l'intervallo selezionato.
- È stato risolto un problema che rendeva difficile la lettura di commenti su display più piccoli.
- È stato risolto un problema per cui l'acquisizione a un dispositivo causava un arresto anomalo.

### <a name="excel"></a>Excel
- Diverse correzioni a prestazioni e stabilità

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema per cui talvolta risultava difficile visualizzare lo stato attivo della tastiera.

### <a name="outlook"></a>Outlook
- È stato risolto un problema che causava la visualizzazione errata di un componente aggiuntivo disabilitato come abilitato.
- È stato risolto un problema che impediva ai clienti di visualizzare tutti i criteri di conservazione, nel caso ne fosse presente un numero elevato.

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="june-14-2019"></a>14 giugno 2019
Versione 1907 (Build 11807.20000)

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema che impediva a un utente di eseguire l'accesso durante il salvataggio in OneDrive
- È stato risolto un problema che impediva a un utente di modificare le proprietà di SharePoint in modalità accesso limitato
- È stato risolto un problema per cui il contenuto dell'intestazione e del piè di pagina poteva cambiare durante la regolazione dei margini
- È stato risolto un problema per cui la formattazione poteva interrompersi durante il passaggio alla visualizzazione Web
- È stato risolto un problema che impediva a un utente di usare i campi personalizzati se aperti da SharePoint

### <a name="excel"></a>Excel
- È stato risolto un problema di prestazioni riscontrato durante l'eliminazione di righe di un set filtrato
- È stato risolto un problema che poteva talvolta causare lo sfarfallio del mouse in Visualizzazione protetta
- È stato risolto un problema che poteva causare un arresto anomalo durante l'eliminazione di una serie
- È stato risolto un problema per cui gli utenti non potevano scegliere di aggiungere la cronologia versioni quando non era disponibile
- È stato risolto un problema che poteva causare un'eccezione durante l'uso dello strumento Confronto di fogli di calcolo

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema per cui poteva verificarsi un arresto anomalo quando si faceva clic su un collegamento a SharePoint
- È stato risolto un problema per cui l'utente passava alla pagina successiva durante la digitazione con una penna per Surface

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui, in alcuni casi, il campo A era più lungo del normale

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="june-7-2019"></a>7 giugno 2019
Versione 1907 (Build 11727.20064)

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema per cui poteva verificarsi un arresto anomalo di Word quando la correzione automatica era impostata in modo da convertire in maiuscolo la prima lettera di una frase
- Sono state migliorate le prestazioni relative alla modifica di un documento in SharePoint.
- È stato risolto un problema per cui le immagini vettoriali create in Adobe Illustrator non venivano visualizzate correttamente.

### <a name="excel"></a>Excel
- È stato risolto un problema per cui i campi di ordinamento talvolta non venivano configurati correttamente durante la registrazione di una macro.
- È stato risolto un problema che causava un blocco o un arresto anomalo durante il calcolo di una formula di matrice.

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui gli allegati incorporati talvolta non venivano ridimensionati correttamente

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- È stato risolto un problema per cui le schede attività a durata fissa potevano talvolta modificare la data di fine di un'attività.
- È stato risolto un problema per cui i valori di Percentuale di completamento potevano risultare errati all'apertura di un progetto di una versione precedente.

</BR></BR>

## <a name="may-31-2019"></a>31 maggio 2019
Versione 1906 (build 11722.20008)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

#### <a name="dialog-for-contacting-support-now-is-dockable-and-appears-on-the-right"></a>La finestra di dialogo per contattare il supporto è ora ancorabile e viene visualizzata a destra

La finestra di dialogo usata per contattare il supporto verrà ora visualizzata in un riquadro a destra e avviata come finestra ancorata.

#### <a name="ink-in-your-email"></a>Input penna disponibile nei messaggi di posta elettronica

È ora possibile creare e aggiungere annotazioni alle immagini nei messaggi di posta elettronica di Outlook.

### <a name="word"></a>Word

#### <a name="open-document-links-in-word"></a>Aprire i collegamenti ai documenti in Word

Quando si fa clic su un collegamento a un documento in Office, è possibile aggiornare la preferenza in modo da aprire l'app Word per impostazione predefinita.  Per aggiornare la preferenza, passare a File -> Opzioni -> Avanzate -> Gestione del link. Altre informazioni: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Guida introduttiva:

Per impostazione predefinita, la funzionalità è disattivata. Gli utenti possono attivarla tramite l'impostazione Opzioni -> Avanzate -> Gestione del link oppure possono sceglierla quando le app WXP Win32 visualizzano un'apposita esperienza.
Quando gli utenti fanno clic su collegamenti a file di Word/PowerPoint/Excel archiviati in OneDrive/OneDrive for Business/SharePoint da Outlook/Word/PowerPoint/Excel, per impostazione predefinita tali collegamenti verranno aperti nell'applicazione di Office appropriata anziché nel browser.

Per modificare questa impostazione predefinita, gli utenti possono aggiornare l'impostazione seguente in Outlook/Word/Excel/PowerPoint:

File -> Opzioni -> Avanzate -> Gestione del link

Questa impostazione è condivisa in Outlook/Word/PowerPoint/Excel e può essere impostata in una di queste app.

##### <a name="scenarios-to-try"></a>Scenari da provare:

Per attivare l'esperienza di scelta, aprire un collegamento a un documento di Word archiviato in OneDrive/SharePoint da Outlook/Word/PowerPoint/Excel, quindi fare clic su Apri nell'applicazione client da Office Online. Eseguire questa operazione per due volte nell'arco di 30 giorni. Dopo aver effettuato la scelta, per impostazione predefinita i collegamenti verranno aperti nelle app Win 32.

### <a name="powerpoint"></a>PowerPoint

#### <a name="open-presentation-links-in-powerpoint"></a>Aprire i collegamenti alle presentazioni in PowerPoint

Quando si fa clic su un collegamento a una presentazione in Office, è possibile aggiornare la preferenza in modo da aprire l'app PowerPoint per impostazione predefinita. Per aggiornare la preferenza, passare a File -> Opzioni -> Avanzate -> Gestione del link. Altre informazioni: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Guida introduttiva:

Per impostazione predefinita, la funzionalità è disattivata. Gli utenti possono attivarla tramite l'impostazione Opzioni -> Avanzate -> Gestione del link oppure possono sceglierla quando le app WXP Win32 visualizzano un'apposita esperienza.
Quando gli utenti fanno clic su collegamenti a file di Word/PowerPoint/Excel archiviati in OneDrive/OneDrive for Business/SharePoint da Outlook/Word/PowerPoint/Excel, per impostazione predefinita tali collegamenti verranno aperti nell'applicazione di Office appropriata anziché nel browser.

Per modificare questa impostazione predefinita, gli utenti possono aggiornare l'impostazione seguente in Outlook/Word/Excel/PowerPoint:

File -> Opzioni -> Avanzate -> Gestione del link

Questa impostazione è condivisa in Outlook/Word/PowerPoint/Excel e può essere impostata in una di queste app.

##### <a name="scenarios-to-try"></a>Scenari da provare:

Per attivare l'esperienza di scelta, aprire un collegamento a una presentazione di PowerPoint archiviata in OneDrive/SharePoint da Outlook/Word/PowerPoint/Excel, quindi fare clic su Apri nell'applicazione client da Office Online. Eseguire questa operazione per due volte nell'arco di 30 giorni. Dopo aver effettuato la scelta, per impostazione predefinita i collegamenti verranno aperti nelle app Win 32.

### <a name="excel"></a>Excel

#### <a name="open-workbook-links-in-excel"></a>Aprire i collegamenti alle cartelle di lavoro in Excel

Quando si fa clic su un collegamento a una cartella di lavoro in Office, è possibile aggiornare la preferenza in modo da aprire l'app Excel per impostazione predefinita. Per aggiornare la preferenza, passare a File -> Opzioni -> Avanzate -> Gestione del link. Altre informazioni: https://support.office.com/en-us/article/open-file-links-directly-in-office-desktop-apps-fe241745-9e05-4142-9ba8-1bb1dc044773?ui=en-US&rs=en-US&ad=US

##### <a name="getting-started"></a>Guida introduttiva:

Per impostazione predefinita, la funzionalità è disattivata. Gli utenti possono attivarla tramite l'impostazione Opzioni -> Avanzate -> Gestione del link oppure possono sceglierla quando le app WXP Win32 visualizzano un'apposita esperienza.
Quando gli utenti fanno clic su collegamenti a file di Word/PowerPoint/Excel archiviati in OneDrive/OneDrive for Business/SharePoint da Outlook/Word/PowerPoint/Excel, per impostazione predefinita tali collegamenti verranno aperti nell'applicazione di Office appropriata anziché nel browser.

Per modificare questa impostazione predefinita, gli utenti possono aggiornare l'impostazione seguente in Outlook/Word/Excel/PowerPoint:

File -> Opzioni -> Avanzate -> Gestione del link

Questa impostazione è condivisa in Outlook/Word/PowerPoint/Excel e può essere impostata in una di queste app.

##### <a name="scenarios-to-try"></a>Scenari da provare:

Per attivare l'esperienza di scelta, aprire un collegamento a una cartella di lavoro di Excel archiviata in OneDrive/SharePoint da Outlook/Word/PowerPoint/Excel, quindi fare clic su Apri nell'applicazione client da Office Online. Eseguire questa operazione per due volte nell'arco di 30 giorni. Dopo aver effettuato la scelta, per impostazione predefinita i collegamenti verranno aperti nelle app Win 32.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto
- È stato risolto un problema per cui i file potevano essere salvati automaticamente anche quando il salvataggio automatico era disabilitato.

### <a name="word"></a>Word 
- È stato risolto un problema che poteva impedire ad alcuni utenti di salvare in SharePoint.

### <a name="excel"></a>Excel
- È stato risolto un problema che causava la visualizzazione di un'icona errata per i filtri inattivi.

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui alcuni utenti risultavano offline per errore in una visualizzazione della pianificazione di gruppo.
- È stato risolto un problema che impediva a SafeLink di analizzare un URL con uno spazio finale.
- È stato risolto un problema per cui le sale venivano visualizzate come disponibili in orario non lavorativo.

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="may-24-2019"></a>24 maggio 2019
Versione 1906 (Build 11715.20002)

## <a name="whats-new"></a>Novità:

#### <a name="user-experience-updates"></a>Aggiornamenti dell'esperienza utente

Gli aggiornamenti nella sezione Prossimamente sono ora disponibili e includono la barra multifunzione semplificata, nonché un aggiornamento visivo del riquadro delle cartelle, dell'elenco dei messaggi e del riquadro di lettura.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto

- È stato risolto un problema che impediva la visualizzazione del riquadro della chat

### <a name="word"></a>Word 
- È stato risolto un problema per cui, in alcuni casi, Word evidenziava in modo errato il testo per indicare errori grammaticali

### <a name="excel"></a>Excel
- È stato risolto un problema per cui veniva usata un'icona errata per Elementi grafico
- È stato risolto un problema per cui poteva essere attivata la cartella di lavoro errata in uno script VBA quando la stessa cartella era già aperta

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- Diverse correzioni a prestazioni e stabilità

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- È stato risolto un problema per cui Project poteva arrestarsi in modo anomalo dopo il passaggio alla barra delle applicazioni

</BR></BR>

## <a name="may-17-2019"></a>17 maggio 2019
Versione 1906 (build 11708.20006)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

#### <a name="user-experience-updates"></a>Aggiornamenti dell’esperienza utente

Gli aggiornamenti nella sezione Presto disponibile sono ora disponibili, con la barra multifunzione semplificata e l’aggiornamento visivo del riquadro delle cartelle, dell’elenco dei messaggi e del riquadro di lettura.

##### <a name="getting-started"></a>Guida introduttiva:

Questa modifica farà parte della nuova interfaccia utente predefinita, che è già presente nella scheda Presto disponibile dalla metà di dicembre per il 100% dei prodotti.

#### <a name="customizable-simplified-ribbon"></a>Barra multifunzione semplificata personalizzabile

Il passaggio dalla visualizzazione classica a quella semplificata e il blocco o sblocco dei comandi sono facilmente personalizzabili.

##### <a name="getting-started"></a>Guida introduttiva:

Gli utenti possono accedere alla barra multifunzione semplificata attivando, inizialmente, la scheda Presto disponibile e facendo clic sulla freccia di espansione per passare dalla visualizzazione classica multiriga alla nuova barra multifunzione semplificata.

##### <a name="scenarios-to-try"></a>Scenari da provare:

Passare dalla barra multifunzione classica a quella semplificata

#### <a name="pick-your-favorite-action"></a>Selezionare l’azione preferita

Non si utilizza Contrassegna ed Elimina? E invece Archivia o Segna come già letto? Come personalizzare il menu Azioni rapide con i comandi utilizzati più spesso.

##### <a name="getting-started"></a>Guida introduttiva:

Per selezionare le Azioni rapide, fare clic con il pulsante destro del mouse su un messaggio di posta elettronica nell'elenco per aprire il Menu di scelta rapida. Quindi fare clic su "Imposta azioni rapide"

##### <a name="scenarios-to-try"></a>Scenari da provare:

Modificare le impostazione predefinite da Contrassegna ed Elimina ad Archivia, Sposta, Segna come già letto o nessuna per un elenco dei messaggi più ordinato.

#### <a name="relaxed-or-tighter-layout-you-choose"></a>Layout medio o più ridotto? A te la scelta

Usa spaziatura inferiore consente di decidere se si vuole più spazio fra gli elementi o un layout più ridotto per visualizzare più elementi.

##### <a name="getting-started"></a>Guida introduttiva:

Scheda Visualizza, usare la casella di controllo con spaziatura ridotta: nel gruppo Messaggi per la barra multifunzione classica, impostazioni di Visualizzazione corrente per la barra multifunzione semplificata

##### <a name="scenarios-to-try"></a>Scenari da provare:

Usare Outlook per la valutazione della posta elettronica e per scrivere un messaggio, con e senza l’impostazione abilitata. Con Usa spaziatura ridotta abilitata, sono presenti più messaggi in ogni pagina e i form di composizione sono semplificati.

#### <a name="dedupe-mru-entries-when-using-the-onedrive-sync-client"></a>Eliminare le voci usate di recente e duplicate tramite il client di sincronizzazione di OneDrive.

Abilitare una migliore integrazione del client di sincronizzazione di OneDrive con gli allegati cloud tramite l’eliminazione delle voci usate di recente e duplicate. Abilitare il comportamento allega come copia più veloce per i dati sincronizzati.

##### <a name="getting-started"></a>Guida introduttiva:

Se si usa il client di sincronizzazione di OneDrive, non verranno più visualizzati file duplicati negli Allega file usati di recente.

##### <a name="scenarios-to-try"></a>Scenari da provare:

Abilitare il client di sincronizzazione di OneDrive e usare il menu Allega file nella versione desktop di Outlook

#### <a name="improved-shared-folder-synchronization-for-mailboxes-with-many-folders"></a>È stata migliorata la sincronizzazione delle cartelle condivise per le cassette postali con più cartelle

Per anni Outlook ha limitato a un massimo di 500 il numero delle cartelle durante la sincronizzazione delle cassette postali condivise. Con questa modifica Outlook ha migliorato la sincronizzazione in modo che non sia più presente il limite di 500 nelle cartelle condivise.

##### <a name="getting-started"></a>Guida introduttiva:

Creare 1000 cartelle in una cassetta postale, concedere ad altri utenti l'accesso alla cassetta postale, creare un profilo di Outlook per un altro utente e verificare che la sincronizzazione funzioni.

### <a name="word"></a>Word

#### <a name="erase-just-a-little-bit"></a>Effettuare delle piccole cancellazioni

##### <a name="getting-started"></a>Guida introduttiva:

Passare alla scheda Disegno. Selezionare il menu a discesa Gomma. Scegliere Gomma piccola o Gomma media.

##### <a name="scenarios-to-try"></a>Scenari da provare:

Passare alla scheda Disegno. Selezionare la penna. Disegnare un tratto input penna. Selezionare il menu a discesa Gomma. Scegliere Gomma piccola o Gomma media. Eliminare alcuni punti del tratto input penna.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto 
- È stato risolto un problema che impediva ad alcuni utenti di salvare in formato PDF
- È stato risolto un problema che poteva influire sul salvataggio di file di grandi dimensioni in un sistema a 32 bit

### <a name="word"></a>Word 
- Sono state migliorate significativamente le funzionalità di dettatura

### <a name="excel"></a>Excel
- È stato risolto un problema per cui gli eventi di doppio clic potevano non riuscire sui dispositivi con touchscreen
- È stato risolto un problema che impediva ad alcuni utenti di modificare le macro VBA
- È stato risolto un problema che poteva influire sulle prestazioni quando si usavano i filtri dei dati

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui veniva visualizzato un modello diverso da quello selezionato.

### <a name="access"></a>Accesso
- È stato risolto un problema per cui l'uso del generatore di zoom per la visualizzazione di testo RTF poteva rendere difficile la lettura.

### <a name="project"></a>Project
- Diverse correzioni su prestazioni e stabilità

</BR></BR>

## <a name="may-10-2019"></a>10 maggio 2019
Versione 1906 (Build 11702.20000)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

**Possibilità di visualizzare più messaggi sullo schermo:** Selezionare Visualizza > Usa spazio più stretto per regolare la spaziatura tra i messaggi.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto
- È stato risolto un problema in cui la finestra di dialogo Salva con nome poteva mostrare un percorso non corretto

### <a name="word"></a>Word 
- È stato risolto un problema in cui alcune selezioni di Aiutami non venivano inserite

### <a name="excel"></a>Excel
- Diverse correzioni a prestazioni e stabilità

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- Diverse correzioni a prestazioni e stabilità

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- È stato risolto un problema in cui le ID attività dovevano essere evidenziate per essere visualizzate

</BR></BR>

## <a name="may-3-2019"></a>3 maggio 2019
Versione 1906 (Build 11629.20008)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

**Tutte le opzioni di crittografia in un'unica posizione:** basta passare a Opzioni > Crittografa per scegliere come proteggere il messaggio di posta elettronica.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all"></a>Tutto
- È stato risolto un problema in cui alcuni utenti riscontravano problemi di sincronizzazione con OneDrive for Business

### <a name="word"></a>Word 
- È stato risolto un problema per cui, in alcuni casi, l'apertura di Word poteva richiedere molto tempo.

### <a name="excel"></a>Excel
- È stato risolto un problema in cui i collegamenti esterni a volte venivano rimossi dalle cartelle di lavoro dopo l'aggiornamento a una versione più recente di Excel
- È stato risolto un problema in cui alcuni utenti riscontravano problemi durante la selezione di celle in una cartella di lavoro

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema in cui le dimensioni del carattere non rimanevano tali quando si convertivano i disegni in testo

### <a name="outlook"></a>Outlook
- È stato risolto un problema in cui salvare un contatto di un File VCF poteva generare campi vuoti come risultato
- È stato risolto un problema in cui un messaggio poteva bloccarsi nella cartella Posta in uscita, anche se era stato inviato
- È stato risolto un problema in cui Outlook poteva arrestarsi in modo anomalo durante l’uso dello strumento di disegno

### <a name="access"></a>Accesso
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- È stato risolto un problema per cui l’editor passava dal cinese all'inglese
- È stato risolto un problema in cui le attività non pubblicate potevano comparire nella copia pubblicata di un progetto principale

</BR></BR>

## <a name="april-26-2019"></a>26 aprile 2019
Versione 1905 (build 11617.20002)

## <a name="new-features"></a>Nuove funzionalità

### <a name="outlook"></a>Outlook

**Gli aggiornamenti dei calendari condivisi sono più veloci:** Outlook può aggiornare i calendari condivisi in Office 365 usando l'API REST. Attivare l'anteprima per aggiornamenti più rapidi e affidabili ai calendari condivisi.

### <a name="excel"></a>Excel

#### <a name="coauthoring-improvements"></a>Miglioramenti alla creazione condivisa

L'esperienza di creazione condivisa è stata migliorata, aumentando la probabilità che gli altri utenti ricevano le modifiche apportate al contenuto in tempo reale.

### <a name="visio"></a>Visio

- **Esportare elementi visivi di Visio da Power BI:** gli oggetti visivi di Visio per Power BI vengono ora visualizzati correttamente quando si esportano i report di Power BI come PDF, file di PowerPoint e altro ancora.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- Diverse correzioni a prestazioni e stabilità

### <a name="excel"></a>Excel
- È stato risolto un problema in cui i macro del Risolutore presentavano problemi di esecuzione
- È stato risolto un problema che potrebbe impedire l'importazione di file di Excel in SharePoint

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- Diverse correzioni a prestazioni e stabilità

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="april-19-2019"></a>19 aprile 2019
Versione 1905 (build 11609.20002)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

**Suggerimenti di posta elettronica per cercare una persona:** quando si digita il nome di una persona nella casella di ricerca, i messaggi di posta elettronica più importanti saranno inclusi nei suggerimenti di ricerca.

### <a name="excel"></a>Excel

#### <a name="improved-filled-maps-experience-using-data-types"></a>Esperienza migliorata delle mappe colorate con tipi di dati

Questa funzionalità è un miglioramento destinato agli utenti che tracciano grafici Mappa colorata usando i tipi di dati geografici di Excel. Il vantaggio per gli utenti finali sarà una migliore integrazione tra le funzionalità e una maggiore accuratezza dell'area da includere nella mappa. Altri vantaggi includono la possibilità di creare mappe con poligoni di città.

##### <a name="getting-started"></a>Introduzione:

- Questa funzionalità è un aggiornamento delle funzionalità esistenti in Excel. Per usare il miglioramento, convertire le posizioni in entità complesse e tracciare il grafico Mappa colorata. 

##### <a name="scenarios-to-try"></a>Scenari da provare:

- Gli utenti possono provare a creare mappe di città, stati, province e codici postali. 


## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all-applications"></a>Tutte le applicazioni
- È stato risolto un problema per cui a ogni avvio di un'applicazione veniva visualizzata la finestra di dialogo della prima esecuzione
- È stato risolto un problema per cui nella finestra di dialogo "Salva con nome" mancava un collegamento a SharePoint.
- È stato risolto un problema per cui agli utenti veniva erroneamente mostrata una finestra di dialogo "Ripristina ora"

### <a name="word"></a>Word 
- È stato risolto un problema per cui alcuni utenti potevano ricevere un errore di memoria o spazio su disco insufficiente richiedendo un tipo di carattere
- È stato risolto un problema per cui una finestra poteva perdere lo stato attivo uscendo dal riquadro commenti

### <a name="excel"></a>Excel
- Diverse correzioni a prestazioni e stabilità

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema che impediva il ridimensionamento di forme personalizzate
- È stato risolto un problema per cui PowerPoint poteva arrestarsi in modo anomalo aprendo un file in modalità di visualizzazione protetta

### <a name="outlook"></a>Outlook
- È stato risolto un problema che impediva ad alcuni utenti di selezionare parole in cinese
- È stato risolto un problema per cui le date di scadenza non erano calcolate correttamente 

### <a name="access"></a>Access
- È stato risolto un problema che impediva ad alcuni utenti di usare il Generatore di macro
- È stato risolto un problema per cui, stampando un report, veniva stampata solo la prima pagina
- È stato risolto un problema per cui l'applicazione poteva arrestarsi in modo anomalo al passaggio del mouse su un collegamento ipertestuale
- È stato risolto un problema per cui alcuni elementi non comparivano nello schermo nella visualizzazione Relazioni

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="april-12-2019"></a>12 aprile 2019
Versione 1905 (Build 11601.20042)

## <a name="whats-new"></a>Novità:

### <a name="access"></a>Access

#### <a name="get-smart-with-microsoft-graph"></a>Suggerimenti intelligenti per Microsoft Graph

Importare o collegare dati intelligenti e reinventare il database desktop con la tecnologia intelligente.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all-applications"></a>Tutte le applicazioni
 - È stato risolto un problema che impedisce ad alcuni utenti di salvare file nelle posizioni del cloud
 - È stato risolto un problema in cui il riquadro errato si apre dalla barra multifunzione

### <a name="word"></a>Word 
- Diverse correzioni a prestazioni e stabilità

### <a name="excel"></a>Excel
- È stato risolto un problema in cui gli utenti vedono un messaggio di errore per i tipi di dati collegati quando la cartella di lavoro non contiene tipi di dati collegati
- È stato risolto un problema in cui i collegamenti URL all'interno di un documento di Word si possono modificare quando vengono visualizzati localmente e online

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema nel punto in cui l'applicazione può bloccarsi dopo l'annullamento di modifiche nella scheda animazioni

### <a name="outlook"></a>Outlook
- È stato risolto un problema che impedisce ad alcuni utenti di modificare il campo Note per i contatti in una cartella pubblica
- È stato risolto un problema in cui può verificarsi un conflitto tra le date di scadenza e le date di eliminazione

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="april-5-2019"></a>5 aprile 2019
Versione 1904 (build 11527.20014)

## <a name="whats-new"></a>Novità:

### <a name="outlook"></a>Outlook

#### <a name="outlook-for-windows--set-and-share-your-focused-inbox-settings"></a>Outlook per Windows: impostare e condividere le impostazioni di Posta in arrivo evidenziata

Le preferenze di Posta in arrivo evidenziata sono archiviate nel cloud, di conseguenza è possibile usufruire della stessa esperienza coerente indipendentemente dall'uso di Outlook per Windows o di Outlook sul web in qualsiasi computer.

#### <a name="getting-started"></a>Guida introduttiva:

In File > Opzioni > scheda Generale è presente una nuova preferenza per 'Memorizza le mie impostazioni di Outlook nel cloud'. Gli utenti dovranno selezionare la casella per abilitare l'impostazione di Posta in arrivo evidenziata a effettuare il roaming ad altre installazioni di Outlook Desktop e a Outlook Web App.

#### <a name="scenarios-to-try"></a>Scenari da provare:

Cambiare Posta in arrivo evidenziata nel computer in cui è attivata la preferenza delle impostazioni cloud. Passare a Outlook Web App e verificare l'applicazione della preferenza. Cambiare Posta in arrivo evidenziata in Outlook Web App e avviare la versione desktop di Outlook per verificare l'applicazione della preferenza.

### <a name="word"></a>Word

#### <a name="learning-tools-mode-has-additional-support-for-more-page-colors"></a>Nella modalità Strumenti di apprendimento è disponibile ulteriore supporto per altri colori della pagina

In Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina.  Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.

#### <a name="getting-started"></a>Guida introduttiva:

Per provare, passare alla scheda Visualizza, scegliere Strumenti di apprendimento e quindi Colore pagina.

#### <a name="scenarios-to-try"></a>Scenari da provare:

Per provare, passare alla scheda Visualizza, scegliere Strumenti di apprendimento e quindi Colore pagina.

### <a name="excel"></a>Excel

#### <a name="elevate-creativity-with-animated-3d-models"></a>Aumentare la creatività con modelli 3D animati

Office ora supporta i modelli animati, che verranno riprodotti nell'editor e consentiranno di animare i fogli.

#### <a name="getting-started"></a>Guida introduttiva:

1. Aprire Excel
2. Inserire un modello 3D animato. A breve tali modelli saranno inseriti in Remix, ma per il momento sono disponibili nel percorso seguente: \\osan\ogx\Public\TestFiles\3D Models\Animated3D\C3Art
3. Il modello animato verrà riprodotto nell'editor, nonché nella modalità Presentazione.
4. Nella barra multifunzione del formato 3D esplorare altre scene di animazione disponibili nel modello

#### <a name="scenarios-to-try"></a>Scenari da provare:

1. Inserire un modello animato, che verrà riprodotto nell'editor.
2. Esplorare le scene di animazione disponibili nel modello animato tramite la raccolta Scene, disponibile nella barra multifunzione del formato 3D
3. È possibile riprodurre e mettere in pausa l'animazione con la barra multifunzione, la barra degli strumenti mobile o la barra spaziatrice

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="all-applications"></a>Tutte le applicazioni
- È stato risolto un problema per cui nei menu di scelta rapida poteva comparire l'icona dell'app errata per Excel
- È stato risolto un problema per cui il pulsante del menu File spariva dopo l'installazione di un aggiornamento
- È stato risolto un problema per cui la licenza dell'utente veniva modificata

### <a name="word"></a>Word 
- È stato risolto un problema per cui il rendering del testo non veniva eseguito correttamente a determinati livelli di zoom

### <a name="excel"></a>Excel
- È stato risolto un problema per cui agli utenti da non veniva chiesto di salvare una cartella di lavoro dopo aver apportato modifiche
- È stato risolto un problema per cui non veniva attivato un evento BeforeSave se l'utente aveva condiviso la cartella di lavoro.
- È stato risolto un problema per cui il ridimensionamento di una colonna a meno di 6 pixel generava un messaggio di errore non corretto.
- È stato risolto un problema per cui Excel ignorava il flag Application.Visible
- È stato risolto un problema per cui le frecce di relazione restavano attive in riquadri bloccati non attivi
- È stato risolto un problema per cui la formattazione delle celle di data e valuta poteva cambiare all'apertura di una cartella di lavoro
- È stato risolto un problema per cui le descrizioni comandi si spostavano in modo imprevisto
- Sono stati risolti i problemi di localizzazione dell'editor di Power Query
- È stato risolto un problema per una cartella di lavoro inviata come allegato di posta elettronica veniva rimossa

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema per cui la copia di forme richiedeva più tempo del previsto

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui Outlook poteva arrestarsi in modo anomalo usando lo strumento di disegno
- È stato risolto un problema di localizzazione durante la composizione di messaggi di posta elettronica in formato HTML
- È stato risolto un problema per cui l'utente aveva difficoltà a selezionare il riquadro inferiore

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="march-22-2019"></a>22 marzo 2019
Versione 1904 (build 11514.20004)

## <a name="new-features"></a>Nuove funzionalità

- **Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse. Altre informazioni <https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json>

- **Le icone di Office hanno un nuovo aspetto:** le icone di Office sono state riprogettate per riflettere l'esperienza semplice potente e intelligente di Office.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema per cui l'interfaccia utente mostrava costantemente "Ricerca modifiche in corso"

### <a name="excel"></a>Excel
- È stato risolto un problema per cui l'applicazione poteva arrestarsi in modo anomalo dopo lo spostamento di un foglio di lavoro
- È stato risolto un problema per cui l'applicazione poteva arrestarsi in modo anomalo dopo il salvataggio come PDF
- È stato risolto un problema per cui la finestra di dialogo per il salvataggio non accettava alcuni caratteri coreani

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- Diverse correzioni a prestazioni e stabilità

### <a name="access"></a>Access
- È stato risolto un messaggio di errore di Access per cui veniva creato un collegamento aggiuntivo ad Access
- È stato risolto un problema per cui i dati di un elemento di SharePoint collegato non venivano visualizzati correttamente.

### <a name="project"></a>Project
- È stato risolto un problema per cui le impostazioni della lingua passavano dal cinese all'inglese
- È stato risolto un problema per cui l'applicazione poteva arrestarsi in modo anomalo durante la sincronizzazione con SharePoint

</BR></BR>

## <a name="march-15-2019"></a>15 marzo 2019
Versione 1904 (build 11504.20000)

## <a name="whats-new"></a>Novità:

### <a name="word"></a>Word

#### <a name="focus-mode"></a>Modalità focus

Passare alla modalità focus nel menu Visualizza per rimuovere elementi di distrazione e concentrarsi sul lavoro. Solo per gli abbonati a Office 365.

#### <a name="getting-started"></a>Guida introduttiva:

Pulsante "Focus" nella scheda Visualizza oppure pulsante "Focus" sulla barra di stato della barra multifunzione

#### <a name="scenarios-to-try"></a>Scenari da provare:

Accedere alla modalità focus e sperimentare la nuova esperienza con focus

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema in Word per cui le immagini di un documento salvato in formato PDF avevano valori DPI non corretti

### <a name="excel"></a>Excel
- Diverse correzioni a prestazioni e stabilità

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema in PowerPoint per cui il riquadro commenti non si apriva e chiudeva correttamente
- È stato risolto un problema per cui l'applicazione poteva arrestarsi in modo anomalo eliminando un video
- È stato risolto un problema per cui in alcuni casi non si riusciva ad avviare l'applicazione

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui le conferme di lettura in giapponese non risultavano corrette

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>

## <a name="march-8-2019"></a>8 marzo 2019 
Versione 1903 (build 11425.20036)

## <a name="whats-new"></a>Novità:

### <a name="word"></a>Word

### <a name="find-what-youre-looking-for-with-microsoft-search"></a>Trovare tutto ciò che serve con Microsoft Search

Con Microsoft Search è possibile trovare i file, le azioni, le persone e l'assistenza necessari per completare il lavoro.

#### <a name="getting-started"></a>Guida introduttiva:

- La funzionalità viene visualizzata in posizione prominente sopra l'interfaccia utente nell'intestazione.

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Cercare un'università, un documento recente o i comandi della barra multifunzione usati più di frequente
- Cercare un argomento o un oggetto e ottenere altre informazioni sull'elemento cercato
- 
#### <a name="coauthoring"></a>Creazione condivisa

Si è stanchi di non poter accedere immediatamente a documenti contenenti macro? Ora i file docm in OneDrive for Business consentono a più autori di apportare modifiche contemporaneamente.

#### <a name="getting-started"></a>Guida introduttiva:

Per accedere a questa funzionalità, l'utente non deve fare clic su alcun pulsante nell'interfaccia utente. La funzionalità è abilitata per impostazione predefinita nei file docm di OneDrive for Business.
L'utente deve quindi salvare un file docm in OneDrive for Business per provare.

#### <a name="scenarios-to-try"></a>Scenari da provare:

Creare un file docm in OneDrive for Business, condividerlo con i colleghi e collaborare.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema di arresto anomalo che si verificava facendo clic su "ESC" in Opzioni
- È stato risolto un problema di arresto anomalo quando si rispondeva ai commenti
- È stato risolto un problema che si verificava effettuando copia e incolla da Word a PowerPoint Online

### <a name="excel"></a>Excel
- È stato risolto un errore per cui copiare una cella in Excel causava un utilizzo elevato della CPU al momento dell'apertura di documenti protetti e modificabili

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui la funzione di ricerca di Outlook non rispettava l'ordinamento cronologico selezionato
- È stato risolto un problema per cui il pulsante della barra multifunzione del flusso di lavoro "Apri attività" non funzionava per alcuni messaggi di posta elettronica.
- È stato risolto un problema per cui Outlook non cancellava le sale in locale dopo che gli utenti selezionavano una sala disponibile in Ricerca sala

### <a name="access"></a>Access
- È stato risolto un problema per cui la finestra di dialogo Importazione/Esportazione salvata presentava del testo bianco su sfondo bianco nel tema scuro
- È stato risolto un problema per cui gli utenti non potevano impostare la proprietà DisplayControl per un campo Sì/No in una casella di testo nella struttura della tabella.

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità


## <a name="march-1-2019"></a>1 marzo 2019 
Versione 1903 (build 11414.20014)

## <a name="whats-new"></a>Novità

### <a name="word"></a>Word

#### <a name="colors-for-track-changes-comments-and-real-time-collaboration-in-sync"></a>Colori sincronizzati per revisioni, commenti e collaborazione in tempo reale

Le correzioni dei prodotti ora garantiscono che commenti, revisioni e cursore di un collaboratore vengano visualizzati nello stesso colore.

#### <a name="getting-started"></a>Guida introduttiva:

Aprire un documento di SharePoint o OneDrive aperto da altri utenti. Verificare che il colore delle revisioni e dei commenti di un utente corrisponda a quello del cursore di tale utente.

#### <a name="scenarios-to-try"></a>Scenari da provare:

Aprire un documento di SharePoint o OneDrive aperto da altri utenti. Verificare che il colore delle revisioni e dei commenti di un utente corrisponda a quello del cursore di tale utente.

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema di arresto anomalo che si verificava facendo clic su "ESC" in Opzioni
- È stato risolto un problema che si verificava effettuando copia e incolla da Word a PowerPoint Online

### <a name="excel"></a>Excel
- È stato risolto un errore per cui copiare una cella in Excel causava un utilizzo elevato della CPU al momento dell'apertura di documenti protetti e modificabili

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema riguardante le dimensioni dell'immagine della diapositiva durante l'utilizzo delle @menzioni in PowerPoint

### <a name="outlook"></a>Outlook
- È stato risolto un problema per cui la funzione di ricerca di Outlook non rispettava l'ordinamento cronologico selezionato
- È stato risolto un problema per cui il pulsante della barra multifunzione del flusso di lavoro "Apri attività" non funzionava per alcuni messaggi di posta elettronica.
- È stato risolto un problema per cui Outlook non cancellava le sale in locale dopo che gli utenti selezionavano una sala disponibile in Ricerca sala

### <a name="access"></a>Access
- È stato aggiornato il testo di richiesta visualizzato durante la conferma del ricollegamento delle tabelle con un'origine dati
- È stato risolto un problema per cui la finestra di dialogo Importazione/Esportazione salvata presentava del testo bianco su sfondo bianco nel tema scuro
- È stato risolto un problema per cui gli utenti non potevano impostare la proprietà Controllo visualizzazione per un campo Sì/No in una casella di testo nella struttura della tabella.

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>



## <a name="february-15-2019"></a>15 febbraio 2019 
Versione 1903 (build 11310.20016)

## <a name="whats-new"></a>Novità:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Miglioramenti apportati alla transizione morphing: morphing in base al nome

Specificare le forme a cui applicare il morphing

#### <a name="getting-started"></a>Guida introduttiva:

- Per fare in modo che il morphing consideri due oggetti come lo stesso oggetto, l'utente può rinominare le forme usando il riquadro di selezione.
- Il nome che il morphing deve usare per sostituire il comportamento predefinito di abbinamento deve essere preceduto da "!!" (due punti esclamativi), ad esempio "!!Nome".
- Gli utenti possono continuare a rinominare le forme con nomi che non iniziano con "!!" senza preoccuparsi che questo incida sul modo in cui funziona il morphing

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Inserire una forma nella diapositiva, ad esempio un rettangolo
- Creare una nuova diapositiva
- Inserire un'altra forma nella seconda diapositiva, ad esempio un triangolo
- Aprire il riquadro di selezione, rinominare il rettangolo nella diapositiva 1 in "!!forma" e rinominare il triangolo nella diapositiva 2 in "!!forma"
- Applicare il morphing nella seconda diapositiva

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Miglioramenti apportati alla transizione morphing: grafica SmartArt

Morphing della grafica SmartArt con transizioni più agevoli

#### <a name="getting-started"></a>Guida introduttiva:

Usare il morphing in modo analogo alla grafica SmartArt

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Inserire un elemento grafico SmartArt in una diapositiva
- Duplicare la diapositiva
- Ridimensionare/modificare/spostare l'elemento grafico SmartArt nella diapositiva duplicata
- Applicare il morphing nella diapositiva duplicata

</BR>

### <a name="morph-transition-enhancements---tables"></a>Miglioramenti apportati alla transizione morphing: tabelle

Morphing delle tabelle con transizioni più agevoli

#### <a name="getting-started"></a>Guida introduttiva:
Usare il morphing in modo analogo alle tabelle

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Inserire una tabella in una diapositiva
- Duplicare la diapositiva
- Ridimensionare/modificare/spostare la tabella nella diapositiva duplicata
- Applicare il morphing nella diapositiva duplicata

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher e Visio

### <a name="seamlessly-switch-between-accounts"></a>Passare facilmente da un account a un altro

La nuova Gestione account consente di visualizzare gli account aziendale e personale in un'unica posizione e permette di passare da uno all'altro. Questa esperienza aggiornata indica in modo chiaro la modalità di accesso e consente ora di passare dall'account aziendale a quello personale e viceversa senza dovere prima effettuare la disconnessione o gestire finestre di dialogo complesse.


![MeMock.png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Scenari da provare:
- Passare da un account a un altro
- Aggiungere un nuovo account [Nota: è consigliabile accedere prima a File | Account | Servizi connessi e rimuovere eventuali servizi personali connessi agli account aziendali o viceversa]
- Disconnettersi da un account
</BR>

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema relativo all'anteprima contesto per tabelle e immagini

### <a name="excel"></a>Excel
- È stato risolto un problema in cui il testo nel campo Cerca del filtro automatico veniva visualizzato in bianco quando il tema era Nero
- È stato risolto un problema relativo all'interfaccia utente del consenso con Nuovo componente aggiuntivo per Office

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema relativo all'estensione automatica dello schermo durante la visualizzazione di presentazioni su portatili o tablet

### <a name="outlook"></a>Outlook
- È stato risolto un problema relativo alla visualizzazione del pulsante Invio a OneNote

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità


</BR></BR>
## <a name="february-11-2019"></a>11 febbraio 2019
Versione 1903 (build 11330.20014)


## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema che impediva l'applicazione di alcuni stili personalizzati in Word Online
- Sono stati risolti i problemi relativi all'anteprima contesto con oggetti complessi in Word
- È stato risolto un problema che causava un arresto anomalo di Word quando si incollavano elenchi

### <a name="excel"></a>Excel
- È stato risolto un problema che impediva la visualizzazione degli spazi aggiunti dopo formati numerici quando non era presente alcun simbolo di valuta
- È stato risolto un problema relativo al rilevamento automatico per le azioni

### <a name="powerpoint"></a>PowerPoint
- Diverse correzioni a prestazioni e stabilità

### <a name="outlook"></a>Outlook
- Diverse correzioni a prestazioni e stabilità

### <a name="access"></a>Access
- Diverse correzioni a prestazioni e stabilità

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità

</BR></BR>


## <a name="february-1-2019"></a>1 febbraio 2019 
Versione 1902 (build 11326.20000)


## <a name="notable-fixes"></a>Correzioni importanti

### <a name="word"></a>Word 
- È stato risolto un problema di ridimensionamento delle celle in una tabella di Excel incorporata
- È stato risolto un problema con il copia e incolla delle forme in un'area di disegno

### <a name="excel"></a>Excel
- È stato risolto un problema di apertura dei file da Excel Web App
- È stato risolto un problema che impediva il salvataggio di un file CSV come file XLSX a causa delle dimensioni del nome file
- È stato corretto il menu di scelta rapida in modo da visualizzare le opzioni del menu di scelta rapida

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema che impediva agli utenti di usare i tasti di scelta rapida CTRL+ALT+7/CTRL+ALT+8 per inserire parentesi quadre
- È stato risolto un problema per il quale l'inserimento di un video locale nel file PPT comportava una riduzione dello spazio su disco dell'unità 'C'
- È stato corretto il pulsante Pubblica in Microsoft Stream che non veniva visualizzato per alcuni utenti

### <a name="outlook"></a>Outlook
- È stato risolto un problema che impediva la corretta visualizzazione dell'oggetto dell'attività nella visualizzazione attività del calendario

### <a name="access"></a>Access
- È stato risolto un problema di ridimensionamento relativo ai grafici

### <a name="project"></a>Project
- Diverse correzioni a prestazioni e stabilità
