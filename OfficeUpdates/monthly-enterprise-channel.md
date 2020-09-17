---
title: Note sulle versioni per i rilasci del Canale mensile Enterprise nel 2020
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale mensile Enterprise per Microsoft 365 Apps nel 2020
ms.openlocfilehash: a9301d0f53144a666571e563472f88b3bc5da924
ms.sourcegitcommit: b7cd1fc37ece6cf0399d89549f7916a4dc40d829
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/16/2020
ms.locfileid: "47942803"
---
# <a name="release-notes-for-monthly-enterprise-channel-releases-in-2020"></a>Note sulle versioni per i rilasci del Canale mensile Enterprise nel 2020

Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale mensile Enterprise nel 2020 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.

> [!IMPORTANT]
> Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Monthly Enterprise Channel) e la modifica dei nomi dei canali di aggiornamento già presenti. Leggere [questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441) per altre informazioni.

[//]: # (NON RIMUOVERE)



## <a name="version-2007-september-08"></a>Versione 2007: 8 settembre
*Versione 2007 (Build 13029,20534)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Notifica di evento imprevisto per gli amministratori IT:** gli amministratori globali dei tenant di Microsoft 365 e gli amministratori delle app di Office verranno avvisati degli eventi imprevisti di Outlook e Office 365 Exchange che interessano gli utenti tramite una nuova notifica nel riquadro a destra in Outlook per Windows. [Altre informazioni](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- **Riaprire rapidamente gli elementi dalla sessione precedente:** è stata aggiunta un'opzione per riaprire rapidamente gli elementi da una sessione di Outlook precedente. Se Outlook si arresta in modo anomalo o lo chiudi, è possibile rilanciare rapidamente gli elementi quando si riapre l'app. Questa funzionalità è attivata per impostazione predefinita. Per disattivarla, vai a Opzioni > Generale > Opzioni di avvio.

### <a name="word"></a>Word

- **Mantenere il testo nei vettori:** ora è possibile mantenere il testo nelle mappe, nei grafici e in altri vettori SVG al momento della conversione di questi oggetti in Excel, Word e PowerPoint.

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Riquadri a schede:** ora è possibile passare da un riquadro all'altro usando un'interfaccia a schede sul lato destro dell'app. L'interfaccia utente sarà visibile solo se sono presenti almeno due riquadri.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Questa correzione risolve il problema per cui il tentativo di eseguire determinate query in precedenza generava il messaggio di errore 'La query è troppo complessa.'


### <a name="excel"></a>Excel

- È stato risolto un problema che impediva il caricamento di una cartella di lavoro con più fogli in visualizzazione Anteprima interruzioni di pagina.


- È possibile che si verifichi un errore quando si prova a salvare un file che contiene una formula usando la funzione LET().


### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava problemi di formattazione negli avvisi di notifica degli eventi imprevisti.


- È stato risolto un problema che causava agli utenti di Outlook la comparsa di errori connessi con lo spostamento in modalità di visualizzazione compatta.


- È stato risolto un problema che causava occasionalmente l’arresto anomalo degli utenti durante il recupero delle informazioni personali.


- È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione.


- È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.


- Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.


- È stato risolto un problema che causava il mancato recupero di suggerimenti per la ricerca da parte di Outlook.


- È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.


- È stato risolto un problema che causava l'arresto anomalo di CLP cambiando l'indirizzo Da in una risposta da un contesto protetto a uno non protetto.

- È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio o componevano un nuovo messaggio.


### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema relativo all'arresto anomalo di PowerPoint.


### <a name="project"></a>Project

- È stato risolto un problema per cui non era possibile salvare un file PDF/XPS da Project a una raccolta documenti di SharePoint.


- È stato risolto un problema per cui, incollando un'attività con più dipendenze, non tutte le dipendenze vengono copiate correttamente.


- È stato risolto un problema per cui l'attività selezionata nella finestra di dialogo Assegna risorse non è la stessa selezionata nella visualizzazione Bacheca attività.


- È stato risolto un problema che impediva l’apertura di un progetto che aveva ottenuto uno stato non valido.



### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui gli elementi o il contenuto dell'interfaccia utente non erano visualizzati dagli utenti in determinate condizioni, in particolare con l’entrata e l’uscita dalla visualizzazione Relatore o l'utilizzo di più monitor.


- È stato risolto un problema che causava la visualizzazione di un messaggio di runtime, anche se la transizione al prodotto completo era stata completata. Il problema è stato corretto verificando che il servizio calcolasse correttamente i prodotti aggiunti. I nuovi prodotti aggiunti sono stati filtrati (verificando che esistano anche nella nuova configurazione) e aggiunti alla fine degli ID di rilascio prodotti esistenti.


- Per il riquadro Condividi basato su servizi non Web precedente, dopo aver chiuso il documento mentre il riquadro Condividi è aperto potrebbe verificarsi un arresto anomalo. Questo problema è stato risolto.



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2006-september-08"></a>Versione 2006: 8 settembre
*Versione 2006 (Build 13001,20648)*

Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2006-august-11"></a>Versione 2006: 11 agosto
*Versione 2006 (Build 13001.20520)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

- **Filtrare e ordinare senza interrompere le altre persone:** È ora possibile ordinare e filtrare i file di Excel mentre si collabora con altre persone con la Visualizzazione foglio. Questa nuova caratteristica fa in modo che gli ordinamenti e i filtri di altri utenti non abbiano alcun impatto durante la creazione condivisa del documento. [Altre informazioni](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

### <a name="outlook"></a>Outlook

- **Protezione dei dati nel gruppo:** l'etichetta di riservatezza che si sceglie quando si crea un gruppo viene applicata ai messaggi di posta elettronica, ai documenti e ai siti del team del gruppo.

- **Raccontare le storie con le GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza per i tuoi documenti.

- **Nuova opzione per disabilitare i suggerimenti di @menzioni durante la composizione dei messaggi di posta elettronica in Outlook:** si trovano i suggerimenti per la selezione delle menzioni più fastidiosi che utili? Ora è possibile disattivarli.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)

- **Mantenere la qualità delle immagini quando si inseriscono nei messaggi di posta elettronica:** è disponibile una nuova opzione di Outlook per limitare la compressione quando si inseriscono immagini nei messaggi di posta elettronica.

### <a name="powerpoint"></a>PowerPoint

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

- **Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida. I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.

### <a name="word"></a>Word

- **Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.

- **Dirlo in altre parole:** se si vuole dirlo in altre parole, è possibile riscriverlo. La riscrittura offre alternative per rifinire le frasi.<br />Vedere i dettagli nel [post del blog](https://blog-insider.office.com/2019/08/12/rewrite-in-word-say-it-another-way/)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.

- È stato risolto un problema relativo all'inserimento di tabelle SQL collegate che includono un campo identità, ad esempio numerazione automatica.


### <a name="excel"></a>Excel

- È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.

- È stato risolto un problema che impediva il caricamento di una cartella di lavoro con più fogli in visualizzazione Anteprima interruzioni di pagina.

- È stato risolto un problema che provocava un arresto anomalo quando si provava a creare una connessione dati dopo aver disconnesso il proprio account.

- La classificazione automatica dei documenti poteva verificarsi per le cartelle di lavoro in modalità di sola lettura.

### <a name="onenote"></a>OneNote

- Miglioramento del rilevamento dello stato di creazione condivisa per ridurre l’utilizzo delle risorse.

### <a name="outlook"></a>Outlook

- È stato risolto un problema relativo al comando copia e incolla immagine SVG.

- Risolve un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.

- È stato risolto un problema che impediva il funzionamento di CTRL+clic quando le impostazioni del cloud erano abilitate.

- È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive dall'esterno del tenant al computer locale selezionando l'opzione "Salva" nella finestra di dialogo relativa alla sicurezza.

- È stato risolto un problema a causa del quale Outlook chiedeva continuamente agli utenti di eseguire lo strumento Manutenzione Posta in arrivo.

- È stato risolto un problema che generava errori del calendario agli utenti delle funzionalità migliorate dei calendari condivisi.

- È stato risolto un problema a causa del quale la data degli allegati copiati tramite trascinamento nel file system veniva impostata su 1 gennaio 4501.

### <a name="project"></a>Project

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.

- È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.

- È stato risolto un problema per cui non era possibile aprire progetti nel client Project per desktop da Project Web App con gli URL con suffisso .com.

### <a name="word"></a>Word

- È stato risolto un problema relativo al comando copia e incolla immagine SVG.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. 

- Un problema di tempi poteva causare un arresto anomalo durante la chiusura dei file di Office.

- È stato risolto un problema di arresto imprevisto con l'host di Office in Windows, per cui un componente aggiuntivo viene attivato quando il valore del registro TabProcGrowth è di tipo REG_SZ.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-august-11"></a>Versione 2005: 11 agosto
*Versione 2005 (Build 12827.20656)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2005-july-14"></a>Versione 2005: 14 luglio
*Versione 2005 (Build 12827.20538)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai. [Altre informazioni](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema per cui ora è possibile usare il tipo di dati data/ora esteso nel codice senza subire alcun arresto anomalo dell'app.

- È stato risolto un problema che consente ora di tornare alla versione di Access più aggiornata e usare DAO/VBA per gestire e modificare un tipo di dati decimale.

### <a name="excel"></a>Excel

- È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.

- In alcuni casi, se si fa clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro verrà nascosta.

- È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.

- È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo nel tentativo di inserire tabelle pivot in un foglio grafico.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una notifica di amministratore.

- Risolve un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.

- È stato risolto un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.

- È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso Stato dell’antivirus: non valido. Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato installato correttamente l’antivirus.

- È stato risolto un problema che causava blocchi o arresti intermittenti in alcune situazioni.

- È stato risolto un problema a causa del quale gli utenti dei miglioramenti del Calendario di Outlook condivisi visualizzavano errori di Calendario di Outlook.

- Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'aggiornamento delle regole in Outlook.

- È stato risolto un problema a causa del quale la data degli allegati copiati tramite trascinamento nel file system veniva impostata su 1 gennaio 4501.

- Risolve un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.

- È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.


### <a name="powerpoint"></a>PowerPoint

- Ciò risolve un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.

- È stato risolto un problema relativo all'arresto anomalo del riquadro suggerimenti.


### <a name="project"></a>Project

- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.

- È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.

### <a name="skype"></a>Skype

- Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni. In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola. Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.

### <a name="word"></a>Word

- È stato risolto un problema che può aver causato un arresto anomalo durante il trascinamento del contenuto dall'app.

### <a name="office-suite"></a>Applicazioni Office

- Questa modifica risolve potenziali blocchi che si verificano durante il caricamento e la riproduzione di contenuti animati, ad esempio GIF o modelli 3D.

- È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.

- L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero. La modifica potrebbe risolvere il problema.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-july-14"></a>Versione 2004: 14 luglio
*Versione 2004 (Build 12730.20602)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)

## <a name="version-2004-june-09"></a>Versione 2004: giugno 09
*Versione 2004 (Build 12730.20430)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Aggiungere tabelle con meno clic**: usare il riquadro attività Aggiungere tabelle, che resta aperto mentre si lavora, per aggiungere tabelle a relazioni e query. [Altre informazioni](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a>Excel

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Il supporto per il connettore Facebook sta per terminare:** a partire dall'aprile del 2020, Excel non supporterà più connessioni dati esterne che usano il connettore Facebook.

- **Nuove immagini per dare vita alle cartelle di lavoro:** migliaia di immagini, icone e adesivi gratuiti da usare nelle cartelle di lavoro. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="outlook"></a>Outlook

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo. I messaggi trascinati verranno condivisi con tutti i membri del gruppo.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)

- **Aggiornamento del calendario:** aggiornamenti visivi che rendono il calendario più facile da analizzare. [Altre informazioni](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)

- **Nuove immagini per dare vita ai messaggi:** migliaia di immagini, icone e adesivi gratuiti da usare nei messaggi di posta elettronica. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="powerpoint"></a>PowerPoint

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione. [Altre informazioni](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

- **Nuove immagini per dare vita alle diapositive:** migliaia di immagini, icone e adesivi gratuiti da usare nelle diapositive. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="word"></a>Word

- **Lazo dell'input penna:** lo strumento Lazo della scheda Disegno consente di selezionare gli oggetti disegnati con l'input penna. È possibile selezionare singoli tratti o parole intere. [Altre informazioni](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- **Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)

- **Nuove immagini per dare vita ai documenti:** migliaia di immagini, icone e adesivi gratuiti da usare nei documenti. Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio. [Altre informazioni](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/06/premium-creative-content/)

### <a name="office-suite"></a>Applicazioni Office

- **Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.

- Application.Evaluate (VBA) in alcuni casi non funzionava per le funzioni definite dall'utente.

- Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.

- È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.

- È stato risolto un problema che causava un blocco durante la chiusura di Outlook.

- È stato risolto un problema che causava un arresto anomalo quando venivano visualizzati avvisi popup.

- È stato risolto un problema che causava l'arresto anomalo di Outlook all'apertura di file con estensione msg o oft salvati in locale dopo un aggiornamento di Windows.

- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.

- È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.

### <a name="project"></a>Project

- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.

- È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.

### <a name="office-suite"></a>Applicazioni Office

- È stato risolto un problema a portata di clic che causava un errore nell'aggiornamento durante il tentativo di creare collegamenti simbolici reali.

- L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero. La modifica potrebbe risolvere il problema.

- Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2003-june-09"></a>Versione 2003: giugno 09
*Versione 2003 (Build 12624.20708)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="office-suite"></a>Applicazioni Office

- Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.

[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2003-may-12"></a>Versione 2003: 12 maggio
*Versione 2003 (Build 12624.20588)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla. Cercare e sostituire il testo nella visualizzazione SQL. Selezionare più tabelle nella finestra Relazioni.

### <a name="excel"></a>Excel

- **Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti. [Altre informazioni](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE. [Altre informazioni](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X. [Altre informazioni](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)

- **Leggere e rispondere all'istante:** rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.

### <a name="outlook"></a>Outlook

- **Suggerimenti di posta elettronica per cercare una persona:** quando si digita il nome di una persona nella casella di ricerca, i messaggi di posta elettronica più importanti saranno inclusi nei suggerimenti di ricerca. [Altre informazioni](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- **Criteri di denominazione dei gruppi:** i criteri di denominazione dei gruppi consentono all'amministratore IT di standardizzare e gestire i nomi dei gruppi creati dagli utenti nell'organizzazione. L'amministratore può richiedere l'aggiunta di un prefisso e un suffisso specifici al nome per un gruppo al momento della creazione e può impedire l'utilizzo di parole specifiche. Questo consente di ridurre al minimo l'uso di parole inappropriate nei nomi dei gruppi e di gestire la rappresentazione dei gruppi nella directory. I criteri di denominazione, inoltre, consentono alle organizzazioni che distribuiscono siti del team di categorizzarli in base al reparto.

- **Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online. Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.

- **Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web? Outlook ora consente di rimanere connessi in scenari di questo tipo.

### <a name="powerpoint"></a>PowerPoint

- **Collaborazione in tempo reale veloce in PowerPoint:** è possibile collaborare in tempo reale rapidamente in PowerPoint

- **Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo, nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **GIF in un batter d'occhio:** una diapositiva, un frame. Crea facilmente GIF a ripetizione continua in PowerPoint. [Altre informazioni](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)

- **Diagrammi migliori:** connettori più efficienti e un processo di conversione dell'input penna più fluido consentono di dare forma alle idee più facilmente. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- **Aggiornamento delle diapositive durante la presentazione:** è possibile aggiornare le diapositive modificate da altri autori durante la presentazione.<br />Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)

### <a name="word"></a>Word

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.

- **Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Apertura incrementale dei file di grandi dimensioni:** è ora possibile scaricare, aprire e interagire con presentazioni di PowerPoint di grandi dimensioni anche se il download di alcune parti della presentazione, ad esempio video o immagini, non è stato ancora completato.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="excel"></a>Excel

- Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.

- È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.


### <a name="onenote"></a>OneNote

- Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza con cui vengono create le cronologie delle versioni delle pagine.


- Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente lo spostamento delle pagine nel Cestino. Agli utenti che vogliono eliminare una pagina verrà mostrata una finestra di dialogo in cui viene chiesto se si vuole eliminare la pagina definitivamente.


- Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016. Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.


- Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016. I blocchi appunti locali non vengono interessati da questa operazione.


- Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.


- Informazioni per gli utenti tramite la Barra informazioni sulle rettifiche temporanee in Microsoft OneNote che consentono di migliorare la sincronizzazione e la disponibilità dei servizi durante i picchi di utilizzo in tutto il mondo.


### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava la visualizzazione del processo di Outlook in esecuzione in Gestione attività dopo la chiusura.


- È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante del mouse.


- È stato risolto un problema che causava arresti anomali nelle applicazioni MAPI di terze parti.


- È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.


- È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.


- È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.


### <a name="project"></a>Project

- È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.


- È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.


- È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.


- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.


- È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.


- È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.


- È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.


- Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.


### <a name="word"></a>Word

- Risolve un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.

- Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)


[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

[//]: # (NON RIMUOVERE LA FINE)

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|MEC|Production|Feature|16.0.13029.20534|version-2007-september-08|)
[//]: # (|Win32|MEC|Production|Feature|16.0.13001.20520|version-2006-august-11|)
[//]: # (| Win32|MEC|Produzione|Caratteristica|16.0.12827.20538|versione-2005-luglio-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
