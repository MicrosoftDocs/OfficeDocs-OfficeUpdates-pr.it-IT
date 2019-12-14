---
title: Note sulle versioni per i rilasci del Canale mensile nel 2019
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale mensile per Office 365 ProPlus nel 2019
ms.openlocfilehash: 69b4f1a573d412e665554f9c697cbce9e3003b27
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023601"
---
# <a name="release-notes-for-monthly-channel-releases-in-2019"></a>Note sulle versioni per i rilasci del Canale mensile nel 2019

Queste note sulle versioni forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non della sicurezza inclusi negli aggiornamenti del Canale mensile per Office 365 ProPlus nel 2019, Visio Pro per Office 365, Project Online Desktop Client e Office 365 Business.

 > [!NOTE]
>- Spesso le funzionalità vengono implementate (e a volte corrette) ogni mese per un periodo di tempo.  Se non si vede subito un elemento descritto di seguito, è possibile aspettarselo al più presto. [Altre informazioni](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
>- Microsoft Teams in installazioni esistenti di Office 365 ProPlus: a partire dall'inizio di luglio, gli aggiornamenti a Office 365 ProPlus (e Office 365 Business) includeranno Microsoft Teams.  La data in cui Teams verrà aggiunto dipende dal canale di aggiornamento usato. Per altre informazioni fare riferimento a [Distribuire Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/DeployOffice/teams-install).

## <a name="version-1911-december-10"></a>Versione 1911: 10 dicembre
*Versione 1911 (Build 12228.20364)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="excel"></a>Excel

- La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.

- Tramite il menu di scelta rapida predefinito per i grafici pivot ora è possibile abilitare l'opzione Mostra dettagli.

### <a name="outlook"></a>Outlook

- Risolve un problema che causava l'accesso dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1911-december-03"></a>Versione 1911: dicembre 03
*Versione 1911 (Build 12228.20332)*

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti. [Altre informazioni](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)

- **Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE. [Altre informazioni](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- **Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel. [Altre informazioni](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Miglioramenti apportati alla creazione condivisa:** l'esperienza di creazione condivisa è stata migliorata aumentando la probabilità che gli altri utenti ricevano in tempo reale le modifiche apportate al contenuto.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- È stato risolto un problema di Microsoft Access che potrebbe causare un errore di tipo &quot;Query danneggiata&quot; quando si esegue una query di aggiornamento o si usa un'istruzione UPDATE in SQL.

### <a name="excel"></a>Excel

- Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.

- È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.

### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante &quot;OK&quot; quando si provava a contattare il supporto dal contesto di creazione dell'account.

- Quando si usa il fuso orario di Brasilia nell'anno 2019, le riunioni e gli appuntamenti ricorrenti vengono visualizzati nella fascia oraria sbagliata per l'anno 2020. Questa modifica è rilevante per i client configurati per il fuso orario di Brasilia o per le riunioni e gli appuntamenti impostati in tale fuso orario. 

- È stato risolto un problema che causava la visualizzazione del messaggio &quot;Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange&quot; all'apertura della finestra di dialogo Regole.

- È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.

- È stato risolto un problema che causava l'aggiornamento imprevisto del campo Luogo nelle riunioni.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.

- È stato risolto un problema nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-november-22"></a>Versione 1910: 22 novembre
*Versione 1910 (Build 12130.20410)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1910-november-18"></a>Versione 1910: 18 novembre
*Versione 1910 (Build 12130.20390)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti

### <a name="access"></a>Access

- È stato risolto un problema per cui l'esecuzione di una query di aggiornamento restituiva erroneamente il messaggio di query danneggiata.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-november-12"></a>Versione 1910: 12 novembre
*Versione 1910 (Build 12130.20344)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava la modifica imprevista del campo del luogo nelle riunioni.

- È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante &quot;OK&quot; quando si provava a contattare il supporto dal contesto di creazione dell'account.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1910-october-30"></a>Versione 1910: 30 ottobre
*Versione 1910 (Build 12130.20272)*

### <a name="resolved-issues"></a>Problemi risolti
### <a name="outlook"></a>Outlook

- È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità

### <a name="excel"></a>Excel

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Applicare etichette di riservatezza ai documenti e ai messaggi di posta elettronica:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione. [Altre informazioni](https://aka.ms/officemipdocs)

### <a name="outlook"></a>Outlook

- **Viene ricevuta una richiesta di aggiornamento di Outlook dopo un errore:** quando Outlook rileva un errore che viene risolto in una versione successiva, chiede ai clienti di eseguire l'aggiornamento e la ricezione della correzione

- **Applicare etichette di riservatezza ai documenti e ai messaggi di posta elettronica:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione. [Altre informazioni](https://aka.ms/officemipdocs)

### <a name="powerpoint"></a>PowerPoint

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **Applicare etichette di riservatezza ai documenti e ai messaggi di posta elettronica:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione. [Altre informazioni](https://aka.ms/officemipdocs)

### <a name="word"></a>Word

- **Miglioramenti alla creazione condivisa**: prestazioni migliorate per la creazione condivisa nei documenti di Word con revisioni.

- **Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare. [Altre informazioni](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- **Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.

- **È stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.** È stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.

- **Applicare etichette di riservatezza ai documenti e ai messaggi di posta elettronica:** è possibile applicare etichette di riservatezza ai file e ai messaggi di posta elettronica per mantenerli conformi ai criteri di protezione delle informazioni dell'organizzazione. [Altre informazioni](https://aka.ms/officemipdocs)

### <a name="office-suite"></a>Famiglia di prodotti Office

- **Installare Microsoft Teams in installazioni esistenti di Office 365 ProPlus: ** a partire dalla fine di giugno, Microsoft Teams verrà incluso nelle installazioni esistenti di Office 365 ProPlus (e Office 365 Business) quando si eseguono gli aggiornamenti di queste installazioni. La data in cui Teams verrà aggiunto dipende dal canale di aggiornamento usato. Per altre informazioni fare riferimento a Distribuire Microsoft Teams con Office 365 ProPlus. [Altre informazioni](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-1909-october-22"></a>Versione 1909: 22 ottobre
*Versione 1909 (Build 12026.20344)*

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="project"></a>Project
- È stato risolto un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.<br></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)


## <a name="october-15"></a>15 ottobre

### <a name="non-security-updates"></a>Aggiornamenti non relativi alla sicurezza

### <a name="office-suite"></a>Famiglia di prodotti Office
- Abbiamo temporaneamente disabilitato la finestra di dialogo Salva nel cloud per risolvere il problema di salvataggio pubblicato il 14 ottobre 2019 per le build precedenti alla 12130.20184. Questa funzionalità verrà riattivata a breve.


## <a name="version-1909-october-14"></a>Versione 1909: 14 ottobre
*Versione 1909 (Build 12026.20334)*

### <a name="non-security-updates"></a>Aggiornamenti non relativi alla sicurezza

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint 2019 per le build precedenti alla 12130.20184.  Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.


## <a name="version-1909-october-08"></a>Versione 1909: 8 ottobre
*Versione 1909 (Build 12026.20320)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non relativi alla sicurezza

### <a name="outlook"></a>Outlook

- È stato risolto un problema con la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.

- È stato risolto un problema che impediva agli utenti di aprire alcune istanze di elementi ricorrenti del calendario.

- È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.

- È stato risolto un problema che causava un arresto anomalo durante la creazione del profilo.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1909-september-30"></a>Versione 1909: 30 settembre
*Versione 1909 (Build 12026.20264)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="access"></a>Access

- **Trovare velocemente le tabelle collegate:** la nostra nuova casella di ricerca rende molto più facile trovare le tabelle collegate. [Altre informazioni](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a>Excel

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

### <a name="outlook"></a>Outlook

- **Il menu Inserisci collegamento in Outlook inserisce un collegamento con l'autorizzazione definita dall'amministratore tenant:** un collegamento dall'elenco dei file usati di recenti in Inserisci collegamento in Outlook inseriva un collegamento che funzionava solo per gli utenti che avevano già le relative autorizzazioni. Questo causava spesso uno scambio di messaggi tra gli utenti per richiedere l'accesso a un documento. Questa esperienza è stata aggiornata in modo tale che il collegamento venga inserito con l'autorizzazione predefinita impostata dall'amministratore tenant.

- **Aggiornamento visivo di Outlook:** fa parte dell'aggiornamento visivo delle esperienze principali in Outlook, con aggiornamento del layout dei messaggi di posta elettronica nel riquadro di lettura e Inspector.

- **Gli aggiornamenti dei calendari condivisi sono più veloci:** Outlook può aggiornare i calendari condivisi in Office 365 usando l'API REST. Attivare l'anteprima per aggiornamenti più rapidi e affidabili ai calendari condivisi.

- **Visualizza i messaggi rilevanti nei risultati della ricerca:** Outlook analizza i termini di ricerca e visualizza i messaggi di posta elettronica più importanti nella parte superiore dei risultati della ricerca. I risultati saranno ordinati anche per data nella sezione Risultati principali.

- **Invio dei messaggi alle persone giuste:** basta fare clic nella riga A: e scegliere tra i contatti suggeriti. Un'immagine e un indicatore di presenza aiuteranno a scegliere la persona giusta.

- **Protezione avanzata dalle minacce:** con Office 365 Advanced Threat Protection, si è protetti dalle minacce tramite collegamenti ipertestuali negli oggetti di posta elettronica, messaggi allegati, messaggi firmati, percorsi di rete e così via.

- **Vedere i messaggi sotto una luce diversa:** usare il pulsante Sole/Luna per utilizzare lo sfondo chiaro o lo sfondo scuro nel riquadro di lettura. [Altre informazioni](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

### <a name="powerpoint"></a>PowerPoint

- **Salvare un'illustrazione in formato SVG:** è possibile salvare un grafico, una forma o un'altra illustrazione in formato SVG (Scalable Vector Graphic), che può essere ridimensionato senza perdita di qualità dell'immagine. [Altre informazioni](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- **Replay immediato:** è possibile animare un disegno a penna in modo che venga riprodotto in avanti o all'indietro durante la presentazione. [Altre informazioni](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

### <a name="visio"></a>Visio

- **Progettare e automatizzare flussi di lavoro aziendali con Microsoft Flow e Visio:** è possibile usare Visio per progettare diagrammi di flusso di lavoro ed esportarli in Microsoft Flow per automatizzarli.

### <a name="word"></a>Word

- **Dirlo in altre parole:** se si vuole dirlo in altre parole, è possibile riscriverlo. La riscrittura offre alternative per rifinire le frasi.

- **Miglioramenti alla creazione condivisa:** maggiore affidabilità durante la creazione condivisa.

- **Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.

- **Gli altri utenti possono vedere rapidamente le modifiche:** grazie ai miglioramenti apportati alla creazione condivisa, i collaboratori possono vedere le modifiche in modo più veloce che mai.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non della sicurezza
### <a name="excel"></a>Excel

- <div><span style="background-color:rgb(255, 255, 255);display:inline !important;">È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.</span><br></div>


- <div>Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare &nbsp;<span style="font-size:13.3333px;background-color:rgb(255, 255, 255);display:inline !important;">durante l'esplorazione in Gestione componenti aggiuntivi.</span></div>
- <div>È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.&nbsp;</div>

### <a name="outlook"></a>Outlook

- <div>È stato corretto un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.</div>


- <span style="background-color:rgb(255, 255, 255);display:inline !important;">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span>


- <span style="background-color:rgb(255, 255, 255);display:inline !important;">È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span>

- È stato risolto un problema che poteva impedire il salvataggio di file in una posizione WebDAV.


### <a name="office-suite"></a>Famiglia di prodotti Office

- <div><p style="margin:0in 0in 0.0001pt;font-size:11pt;font-family:Calibri, sans-serif;">È stato risolto un problema che si verificava all'apertura di un file.</p></div>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-10"></a>Versione 1908: 10 September
*Versione 1908 (Build 11929.20300)*

Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="non-security-updates"></a>Aggiornamenti non relativi alla sicurezza
### <a name="outlook"></a>Outlook

- È stato risolto un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.

- È stato risolto un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.

### <a name="powerpoint"></a>PowerPoint

- È stato risolto un problema relativo al ripristino del nome accessibile per i controlli video di PowerPoint.

- È stato risolto un problema che impediva l'avvio di alcune animazioni.

### <a name="word"></a>Word

- È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui le visualizzazioni ad albero di grandi dimensioni causavano un errore.



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-26"></a>Versione 1908: 26 agosto
*Versione 1908 (Build 11929.20254)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella cartella di lavoro, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

- **Organizzare i commenti:** selezionare Risolvi per comprimere i commenti ed evidenziare quelli ancora non risolti.

### <a name="office-suite-feature-updates"></a>Applicazioni Office: aggiornamenti delle funzionalità

- **Le nuove icone di Office:** l’aspetto delle icone di Office è cambiato per riflettere l'esperienza semplice, potente e intelligente di Office.

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Suggerimenti per il luogo delle riunioni:** è sufficiente iniziare a scrivere nella riga Luogo durante la pianificazione di appuntamenti e riunioni e Outlook suggerirà sale, indirizzi e altri luoghi recenti. [Altre informazioni](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- **Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella presentazione, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nel documento, in modo che sembrino disegnate a mano. [Altre informazioni](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- **Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata. E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

## <a name="version-1907-august-13"></a>Versione 1907: 13 agosto
*Versione 1907 (Build 11901.20218)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.

## <a name="version-1907-july-29"></a>Versione 1907: 29 luglio

*Versione 1907 (Build 11901.20176)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti ai documenti di Office, ovvero nel browser o nell'app.

- **Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi. Semplice individuazione di funzioni, colonne e parametri.

- **Creazione di un grafico a mappa:** questa funzionalità è un miglioramento destinato agli utenti che tracciano grafici a mappa colorata usando i tipi di dati geografici di Excel. Il vantaggio per gli utenti finali sarà una migliore integrazione tra le funzionalità e una maggiore accuratezza dell'area da includere nella mappa. Altri vantaggi includono la possibilità di creare mappe con poligoni di città. [Altre informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle. [Altre informazioni](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Suggerimenti di posta elettronica per cercare una persona:** quando si digita il nome di una persona nella casella di ricerca, i messaggi di posta elettronica più importanti saranno inclusi nei suggerimenti di ricerca. [Altre informazioni](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti ai documenti di Office, ovvero nel browser o nell'app.

- **Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo, nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- **Creazione di un grafico a mappa:** questa funzionalità è un miglioramento destinato agli utenti che tracciano grafici a mappa colorata usando i tipi di dati geografici di Excel. Il vantaggio per gli utenti finali sarà una migliore integrazione tra le funzionalità e una maggiore accuratezza dell'area da includere nella mappa. Altri vantaggi includono la possibilità di creare mappe con poligoni di città. [Altre informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Aggiungere i titoli delle diapositive per rendere accessibili le presentazioni:** Verifica accessibilità consente di individuare e correggere i titoli delle diapositive mancanti. [Altre informazioni](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- **L'impostazione per la stampa dei numeri di diapositiva in stampati è stata spostata nel menu Stampa per semplificare l'accesso:** trovarla nell'elenco a discesa Stampa > layout di stampa quando è selezionato un layout Stampati. L'opzione consente inoltre di attivare o disattivare facilmente la presentazione. [Altre informazioni](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Addio alle distrazioni:** una delle funzionalità preferite del Mac è ora disponibile in Windows. Passare alla modalità focus nel menu Visualizza per rimuovere elementi di distrazione e concentrarsi sul lavoro. [Altre informazioni](https://support.office.com/article/51af2fb2-194f-424b-ab7e-b65de9ec9292)

- **Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti ai documenti di Office, ovvero nel browser o nell'app.

- **Creazione di un grafico a mappa:** questa funzionalità è un miglioramento destinato agli utenti che tracciano grafici a mappa colorata usando i tipi di dati geografici di Excel. Il vantaggio per gli utenti finali sarà una migliore integrazione tra le funzionalità e una maggiore accuratezza dell'area da includere nella mappa. Altri vantaggi includono la possibilità di creare mappe con poligoni di città. [Altre informazioni](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- **Cancellare con precisione:** è possibile scegliere tra due dimensioni della gomma per correggere le piccole imperfezioni dell'input penna. [Altre informazioni](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

## <a name="version-1906-july-09"></a>Versione 1906: 09 luglio
*Versione 1906 (Build 11727.20244)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza

- Risolve un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.

## <a name="version-1906-june-27"></a>Versione 1906: 27 giugno
*Versione 1906 (Build 11727.20230)*

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza

- Risolve un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni.  Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.

## <a name="version-1906-june-26"></a>Versione 1906: 26 giugno
*Versione 1906 (Build 11727.20224)*

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.
- È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza

- Risolve un problema che causa ambiguità per i responsabili circa il fatto che un delegato abbia già risposto o meno a una determinata convocazione di riunione.

## <a name="version-1906-june-24"></a>Versione 1906: 24 giugno
*Versione 1906 (Build 11727.20210)*
* Diverse correzioni di bug e miglioramenti delle prestazioni.

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Fogli di lavoro animati:** è possibile inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella cartella di lavoro. [Altre informazioni](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Barra multifunzione semplificata e personalizzabile:** un'unica riga essenziale riunisce i pulsanti usati di frequente. In questo modo è possibile passare facilmente dalla visualizzazione classica a quella semplificata e aggiungere/rimuovere comandi. [Altre informazioni](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- **Selezione dell'azione preferita:** le azioni Contrassegna e Elimina non vengono usate, ma si preferisce usare Archivia o Segna come già letto? È possibile personalizzare il menu Azioni rapide con i comandi usati più di frequente.

- **Miglioramento della sincronizzazione delle cartelle condivise per cassette postali con numerose cartelle:** per anni Outlook ha limitato a un massimo di 500 il numero delle cartelle durante la sincronizzazione delle cassette postali condivise. Con questa modifica la sincronizzazione in Outlook è migliorata e il limite di 500 cartelle non è più presente.

- **Impostazioni di Posta in arrivo evidenziata invariate nei vari dispositivi:** le preferenze della Posta in arrivo evidenziata vengono archiviate nel cloud. È quindi ora possibile usufruire della stessa esperienza quando si usa Outlook per Windows in qualsiasi computer e in Outlook sul web. [Altre informazioni](https://support.office.com/article/d77a442e-a86c-4bf8-b3dd-5571ae556986)

- **Possibilità di scegliere tra layout medio o più ridotto:** l'opzione Usa spaziatura inferiore consente di decidere se si preferisce lasciare maggiore spazio fra gli elementi o adottare un layout più ridotto per visualizzare un maggior numero di elementi.

- **Aggiornamento dell'esperienza utente di Outlook:** è finalmente accessibile a tutti un'esperienza semplificata, in precedenza disponibile in anteprima con Prossimamente, progettata per consentire all'utente di concentrarsi sugli aspetti più importanti. [Altre informazioni](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- **Aggiunta della funzionalità Input penna:** è possibile scarabocchiare sopra le immagini o aggiungere un'area di disegno per inviare idee con l'input penna. [Altre informazioni](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Creazione condivisa:** per poter accedere immediatamente a documenti contenenti macro, ora i file docm in OneDrive for Business consentono a più autori di apportare modifiche contemporaneamente.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: aggiornamenti non relativi alla sicurezza 

 - È stata aggiunta una correzione per consentire la visualizzazione di tutti i flussi delle videocamere da dispositivi Polycom CX5500 e correlati in una riunione quando il monitor viene ridimensionato più del 100%.

- È ora possibile ritagliare correttamente il video in una riunione con un monitor 4K quando l'impostazione "Durante le riunioni ritaglia e centra il video" è abilitata.

- È ora consentito il trasferimento dei file a client Office Communicator legacy da un computer Windows 10 con più schede di rete. [Altre informazioni](help/4508477)

- Esperienza migliorata per la comunicazione tra i partecipanti a Skype for Business e Microsoft Teams


## <a name="version-1905-june-11"></a>Versione 1905: 11 giugno
*Versione 1905 (Build 11629.20246)*
<br/>Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.

### <a name="visio-non-security-updates"></a>Visio: aggiornamenti non relativi alla sicurezza

- L'esportazione in SVG da Visio non funzionava per numerose forme.

## <a name="version-1905-june-3"></a>Versione 1905: 3 giugno
*Versione 1905 (Build 11629.20214)*

### <a name="powerpoint-non-security-updates"></a>PowerPoint: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.

## <a name="version-1905-may-29"></a>Versione 1905: 29 maggio
*Versione 1905 (Build 11629.20196)*

### <a name="access-feature-updates"></a>Access: aggiornamenti delle funzionalità

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Prossimamente:** scoprire le interessanti modifiche presto disponibili in Office, provarle e inviare feedback. [Altre informazioni](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- **Collaborare in modo più efficace con @menzioni nei Commenti:** la collaborazione è molto più semplice. Ora è possibile menzionare con @ i colleghi nei commenti dei documenti e loro riceveranno automaticamente una notifica tramite posta elettronica che li riporterà al documento.

- **Creazione condivisa miglioramenti unione**: la creazione condivisa ha migliorato il tasso di unione quando si lavora con la formattazione condizionale, gli stili di cella, la protezione dell'intervallo, la griglia di visualizzazione e il taglia/incolla tra fogli. 

### <a name="outlook"></a>Outlook

- **Un modo più rapido per aggiungere account:** grazie ai miglioramenti per la configurazione dell'account, l'aggiunta di account di Outlook.com e Gmail che utilizzano l'autenticazione a 2 fattori in Outlook è più facile che mai. [Altre informazioni](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **Sottotitoli e sottotitoli in tempo reale:** le parole del relatore vengono visualizzate automaticamente sullo schermo come sottotitoli o tradotti in sottotitoli nella lingua scelta. [Altre informazioni](https://support.office.com/article/d68d20e49-aec3-456a-939d-34a79e8ddd5f)

- **Prossimamente:** scoprire le interessanti modifiche presto disponibili in Office, provarle e inviare feedback. [Altre informazioni](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

- **Collaborare in modo più efficace con @menzioni nei Commenti:** la collaborazione è molto più semplice. Ora è possibile menzionare con @ i colleghi nei commenti dei documenti e loro riceveranno automaticamente una notifica tramite posta elettronica che li riporterà al documento.

### <a name="project-feature-updates"></a>Project: Aggiornamenti delle funzionalità

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio-feature-updates"></a>Visio: aggiornamenti delle funzionalità

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **I report di Power BI esportati in PDF, PPT o configurati per la sottoscrizione messaggio di posta elettronica verranno ora visualizzati anche con Visio Visual:** se si esportano i report di Power BI in PDF, PPT o si configura una sottoscrizione messaggio di posta elettronica, Visio Visual verrà facilmente renderizzato in questi formati. [Altre informazioni](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità  

- **Collaborare in modo più efficace con @menzioni nei Commenti:** la collaborazione è molto più semplice. Ora è possibile menzionare con @ i colleghi nei commenti dei documenti e loro riceveranno automaticamente una notifica tramite posta elettronica che li riporterà al documento.

- **Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione. Passare da uno all’altro non è mai stato così facile. [Altre informazioni](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- **La modalità Strumenti di apprendimento dispone di ulteriore supporto per più colori della pagina:** in Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina.  Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.

- **Prossimamente:** scoprire le interessanti modifiche presto disponibili in Office, provarle e inviare feedback. [Altre informazioni](https://support.office.com/article/7800e0cf0-812f-475a-80aa-d47376e076f2)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: aggiornamenti non relativi alla sicurezza

- Fornisce agli utenti di Skype for Business online l'opzione per disabilitare il suggerimento contestuale "Aggiungi la tua foto - aiuterà le persone a conoscerti". Per abilitare questa correzione, vedere [Altre informazioni](https://support.microsoft.com/help/4503469).

- Impedisce l'attivazione ripetuta dell'impostazione della suoneria secondaria dopo il riavvio di Skype for Business. Per abilitare questa correzione, vedere [Altre informazioni](https://support.microsoft.com/help/4503470).

 - Correzione che consente di risolvere un problema che causava il blocco di Skype for Business durante la partecipazione a una riunione con un numero elevato di utenti in caso di utilizzo contestuale di un'applicazione basata su Lync SDK. Per abilitare questa correzione, vedere [Altre informazioni](https://support.microsoft.com/help/4503472).

## <a name="version-1904-may-22"></a>Versione 1904: 22 maggio
*Versione 1904 (Build 11601.20230)*

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza

- Si tratta di un problema che consente agli utenti di visualizzare la nuova richiesta di privacy per ogni avvio di un'applicazione, anche dopo aver selezionato ed effettuato una scelta per il livello di privacy.

## <a name="version-1904-may-14"></a>Versione 1904: 14 maggio 
*Versione 1904 (Build 11601.20204)*

- Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

## <a name="version-1904-may-8"></a>Versione 1904: 8 maggio
*Versione 1904 (Build 11601.20178)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1904-april-29"></a>Versione 1904: 29 aprile
*Versione 1904 (Build 11601.20144)*

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Connessione della rete LinkedIn a Outlook:** connessione sicura degli account LinkedIn all'account Microsoft per visualizzare le informazioni dei profili LinkedIn direttamente nella scheda Utenti. [Altre informazioni](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Colori per revisioni, commenti e collaborazione in tempo reale in Sincronia:** le correzioni dei prodotti ora garantiscono che commenti, revisioni e cursore di un collaboratore vengano visualizzati nello stesso colore.

- **Ricerca rapida del file:** Come cercare un file utilizzato di recente? È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.

### <a name="visio-feature-updates"></a>Visio: aggiornamenti delle funzionalità

- **Esportazione dei diagrammi di processo in Word:** è possibile aggiungere automaticamente il contenuto dei diagrammi, come forme e metadati, a un documento Word. Quindi, personalizzare il documento per creare linee guida di processi e manuali operativi. [Altre informazioni](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: aggiornamenti delle funzionalità

- **Nuove icone:** sono state aggiunte più di 300 nuove icone in base al feedback degli utenti. Sono disponibili usando il pulsante Icone nella scheda Inserisci della barra multifunzione.

- **Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse. [Altre informazioni](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

### <a name="outlook-non-security-updates"></a>Outlook: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema che causava la visualizzazione estremamente ridotta dell'oggetto.

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
- Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.

- È stato risolto un problema che impediva gli aggiornamenti di Office quando veniva eseguita l'autenticazione proxy come sistema.

## <a name="version-1903-april-23"></a>Versione 1903: 23 aprile
*Versione 1903 (Build 11425.20244)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1903-april-17"></a>Versione 1903: 17 aprile
*Versione 1903 (Build 11425.20228)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1903-april-16"></a>Versione 1903: 16 aprile
*Versione 1903 (Build 11425.20218)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1903-april-9"></a>Versione 1903: 9 aprile
*Versione 1903 (Build 11425.20204)* 

- Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/OfficeUpdates/office365-proplus-security-updates)

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: aggiornamenti non relativi alla sicurezza
- Risolto un problema in Lync (Skype for Business) per cui per le riunioni online con più di 7 partecipanti, la finestra della riunione poteva scomparire.

## <a name="version-1903-april-01"></a>Versione 1903: 1 aprile
*Versione 1903 (Build 11425.20202)* 

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Insights in Excel:** offre vantaggi a una serie di utenti. Insights fornisce un approccio più delicato per l'analisi dei dati e in altri casi fornisce un punto di vista diverso sui dati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)


- **Aumentare l'efficacia del contenuto:** rendere accessibili i fogli di calcolo Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Spostamento di forme migliorato:** assegnare un nome alle forme per un maggiore controllo sul modo in cui effettuano il morphing. [Altre informazioni](https://support.office.com/article/9bc7f48ff-f152-4ee8-9081-d3121788024f)

- **Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

- **Perché reinventare quando è possibile riutilizzare?**  È possibile risparmiare tempo riutilizzando le diapositive che sono state create o che altri hanno condiviso.

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza

- È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: aggiornamenti non relativi alla sicurezza

- Correzione di un problema che determinava il blocco di Skype for Business al momento della risposta alle notifiche di chat in presenza di un'app SfB/Lync SDK di terze parti.
- Correzione del blocco dell'app quando si incolla il contenuto degli Appunti in una chat.
- Correzione di un problema che impediva la visualizzazione dell'informazione "accettata da" per una chiamata nella Coda di chiamate che viene gestita da uno degli agenti di chiamata.
- Risolto un problema per cui le icone di chiamata risultavano nascoste quando un utente di Teams partecipa a una riunione in Skype for Business.

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Aumentare l'efficacia del contenuto:** rendere accessibili i documenti Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro. Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.

## <a name="version-1902-march-25"></a>Versione 1902: 25 marzo
*Versione 1902 (Build 11328.20222)*

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1902-march-12"></a>Versione 1902: 12 marzo
*Versione 1902 (Build 11328.20158)* 

- Diverse correzioni di bug e miglioramenti delle prestazioni.

## <a name="version-1902-march-4"></a>Versione 1902: 4 marzo
*Versione 1902 (Build 11328.20146)* 

### <a name="access-feature-updates"></a>Access: aggiornamenti delle funzionalità

- **Monitorare gli oggetti di database:** visualizzare chiaramente la scheda attiva, trascinare facilmente le schede per disporle in modo diverso e chiudere gli oggetti di database con un solo clic.
- **Zoom con più spazio:** ingrandire la casella Zoom e cambiare il tipo di carattere. Tutte le modifiche verranno mantenute. [Altre informazioni](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Ottenere l'attenzione tramite \@menzioni:** utilizzare @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input. [Altre informazioni](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)
- **Scoprire di più sui dati:** il nuovo pulsante Idee cerca modelli nei dati e li usa per creare suggerimenti intelligenti e personalizzati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)
- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Avere un momento di respiro tra una riunione e l'altra:** dare ai partecipanti il tempo di riprendere fiato o di viaggiare da una località all'altra impostando le riunioni in modo che terminino per impostazione predefinita 5-10 minuti in anticipo. [Altre informazioni](https://support.office.com/article/Schedule-a-meeting-with-other-people-5C9877BC-AB91-4A7C-99FB-B0B68D7EA94F#BKMK_endmeetingsearly)
- **Ascoltare il testo del messaggio di posta elettronica con Leggi ad alta voce**: Outlook è in grado di leggere i messaggi di posta elettronica ad alta voce, evidenziando il testo durante la lettura. Per attivare Leggi ad alta voce, passare alle impostazioni Accessibilità. [Altre informazioni](https://support.office.com/article/64e393a4-1229-45c0-acdb-dc93330ebdb3)
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Inserire un video online è più facile che mai:** se si vuole inserire un video da Vimeo o YouTube nella diapositiva, basta il collegamento alla pagina del video. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)
- **La formattazione dei calcoli diventa automatica:** le espressioni matematiche scritte a mano vengono convertite in caratteri standard. Per iniziare, basta selezionare le note scritte a mano e scegliere Da input penna a testo matematico. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)
- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
- **L'apertura di file di grandi dimensioni è ora più veloce:** immagini, video e altri elementi di grandi dimensioni vengono ora scaricati in background quando si aprono file archiviati in OneDrive o SharePoint.

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.
- **Ecco perché il salvataggio automatico non è attivo: ** se si seleziona l'opzione Salvataggio automatico, verrà visualizzato un utile callout con i motivi per cui il salvataggio automatico potrebbe essere disattivato. Se l'unico motivo per cui il salvataggio automatico è disattivato consiste nel fatto che il documento non si trova in OneDrive o SharePoint, viene offerta la possibilità di spostarlo comodamente con un semplice clic.
- **Possibilità di inserire SVG con filtri applicati:** gli utenti di Office ora possono inserire SVG a cui sono applicati filtri. [Altre informazioni](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)
 
### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: aggiornamenti delle funzionalità

- **Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle nuove installazioni di Office 365 ProPlus. [Altre informazioni](https://docs.microsoft.com/DeployOffice/teams-install)

## <a name="version-1901-february-12"></a>Versione 1901: 12 febbraio
*Versione 1901 (Build 11231.20174)* 

Aggiornamenti della sicurezza elencati [qui](office365-proplus-security-updates.md)

## <a name="version-1901-january-31"></a>Versione 1901: 31 gennaio
*Versione 1901 (Build 11231.20130)* 

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Collaborare con i commenti:** è possibile mantenere la conversazione nel proprio foglio di calcolo con la casella di risposta integrata. [Altre informazioni](https://support.office.com/article/bdcc9f5d-38e2-45b4-9a92-0b2b5c7bf6f8)

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Utilizzo di meme:** quando testo o immagini statiche non bastano, si può usare una GIF animata per esprimere il proprio pensiero. [Altre informazioni](https://support.office.com/article/114BB251-861F-41CD-B20F-7E7289630C5B)
 
### <a name="visio-feature-updates"></a>Visio: aggiornamenti delle funzionalità

- **Maggiore controllo sui diagrammi di flusso di dati:** i nuovi fantastici layout per i diagrammi di flusso del Visualizzatore dati sono chiari, nitidi e facili da capire. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

- **Stencil di Azure incorporati:** per progettare un'applicazione cloud o pianificare un'architettura è possibile scegliere tra decine di stencil di Azure. [Altre informazioni](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Trasformare il documento da statico a sorprendente:** trasformare il documento in una pagina web interattiva, facile da condividere che si adatta perfettamente a qualsiasi dispositivo. [Altre informazioni](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)

### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: aggiornamenti delle funzionalità

- **Possibilità di inserire il supporto per SVG tramite le applicazioni di terze parti per Office con l'API Office.js:** le applicazioni di terze parti, note anche come componenti aggiuntivi in Office, ora possono inserire SVG. Gli utenti possono connettere la propria raccolta personale di SVG a Office, mentre gli sviluppatori possono usare l'API Office.js per implementare questa funzionalità.


## <a name="version-1812-january-14"></a>Versione 1812: 14 gennaio
*Versione 1812 (Build 11126.20266)* 

Solo aggiornamenti non relativi alla sicurezza, rivolti ai problemi correlati alle prestazioni.

## <a name="version-1812-january-8"></a>Versione 1812: 8 gennaio
*Versione 1812 (Build 11126.20196)* 

### <a name="project-non-security-updates"></a>Project: aggiornamenti non relativi alla sicurezza
- Risolto un problema in cui non era possibile deselezionare gli stili delle barre Critical, Late e Slack per il diagramma di Gantt dopo averne selezionato uno.

## <a name="version-1812-january-3"></a>Versione 1812: 3 gennaio
*Versione 1812 (Build 11126.20188)* 

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità

- **Mantenere Verifica accessibilità in esecuzione mentre si lavora:** tenere traccia dei problemi di accessibilità del documento senza la necessità di tenere Verifica accessibilità sempre aperto. Tramite un indicatore nella barra di stato, in modo analogo al controllo ortografico, Excel contrassegna i problemi di accessibilità riscontrati mentre si lavora. 

### <a name="outlook-feature-updates"></a>Outlook: aggiornamenti delle funzionalità

- **Tutte le opzioni di crittografia in un'unica posizione:** basta passare a Opzioni > Crittografa per scegliere come proteggere il messaggio di posta elettronica. [Altre informazioni](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)


### <a name="powerpoint-feature-updates"></a>PowerPoint: aggiornamenti delle funzionalità

- **Input penna per diapositive meravigliose:** convertire l’input penna in forme e testo standard, quindi ottenere idee di progettazione delle diapositive intelligenti da PowerPoint Designer. [Altre informazioni](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)
- **Mantenere Verifica accessibilità in esecuzione mentre si lavora:** tenere traccia dei problemi di accessibilità del documento senza la necessità di tenere Verifica accessibilità sempre aperto. Tramite un indicatore nella barra di stato, in modo analogo al controllo ortografico, PowerPoint contrassegna i problemi di accessibilità riscontrati mentre si lavora. 

### <a name="word-feature-updates"></a>Word: aggiornamenti delle funzionalità

- **Migliorare la comprensione con Focus su riga:** spostarsi in un documento riga per riga senza distrazioni. Modificare lo stato attivo per rendere visibili una, tre o cinque righe alla volta. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)
- **Mantenere Verifica accessibilità in esecuzione mentre si lavora:** tenere traccia dei problemi di accessibilità del documento senza la necessità di tenere Verifica accessibilità sempre aperto. Tramite un indicatore nella barra di stato, in modo analogo al controllo ortografico, Word contrassegna i problemi di accessibilità riscontrati mentre si lavora.

### <a name="visio-feature-updates"></a>Visio: aggiornamenti delle funzionalità

- **Addio ai collegamenti interrotti di Excel:** impossibile trovare la cartella di lavoro di Excel collegata al diagramma del Visualizzatore dati? Collegarla di nuovo per riprendere l’attività. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)

### <a name="office-suite-feature-updates"></a>Famiglia di prodotti Office: aggiornamenti delle funzionalità

- **Riquadro Novità:** l'esperienza Novità è stata spostata nel riquadro della Guida e ora è più semplice accedervi e mantenersi aggiornati sugli ultimi aggiornamenti.

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
