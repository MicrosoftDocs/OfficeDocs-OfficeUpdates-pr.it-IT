---
title: Note sulle versioni per i rilasci del Canale semestrale (mirato) nel 2018
ms.author: anankani
author: andymosten
manager: anankani
ms.date: 12/13/2018
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale semestrale (mirato) per Office 365 ProPlus nel 2018
ms.openlocfilehash: 116e590889d30fff7a2076865face01d45d17062
ms.sourcegitcommit: db492a4c51ec771ab97c67e4b1d43ee36d8794b8
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 10/07/2020
ms.locfileid: "48370044"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2018"></a>Note sulle versioni per i rilasci del Canale semestrale (mirato) nel 2018

Queste note sulle versioni forniscono informazioni sulle nuove caratteristiche, sugli aggiornamenti della sicurezza e non della sicurezza inclusi negli aggiornamenti del Canale semestrale (mirato) per Office 365 ProPlus nel 2018.
 
> [!NOTE]
> - Di seguito vengono fornite informazioni sulle nuove caratteristiche, sugli aggiornamenti della sicurezza e non della sicurezza per Visio Pro per Office 365 e Project Online Desktop Client.
> - Queste informazioni si applicano anche a Office 365 Business, ovvero la versione di Office fornita con alcuni piani di Office 365, ad esempio Business Premium.

 
> [!NOTE]
> - Le informazioni sugli aggiornamenti della sicurezza per ciascun canale di aggiornamento di Office 365 ProPlus saranno elencate separatamente in [Aggiornamenti della sicurezza](microsoft365-apps-security-updates.md).

## <a name="version-1808-december-11"></a>Versione 1808: 11 dicembre
*Versione 1808 (Build 10730.20262)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza 

-   [CVE-2018-8597](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8597): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8598](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8598): vulnerabilità della divulgazione delle informazioni di Microsoft Excel 
-   [CVE-2018-8627](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8627): vulnerabilità della divulgazione delle informazioni di Microsoft Excel 
-   [CVE-2018-8636](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8636): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza 

-   [CVE-2018-8587](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8587): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 

### <a name="powerpoint-security-updates"></a>PowerPoint: Aggiornamenti della sicurezza 

-   [CVE-2018-8628](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8628): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft PowerPoint 

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

-   [CVE-2018-8574](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8574): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8577](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8577): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza 

-   [CVE-2018-8522](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8522): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 
-   [CVE-2018-8524](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8524): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 
-   [CVE-2018-8558](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8558): vulnerabilità della divulgazione delle informazioni relative a Microsoft Outlook 
-   [CVE-2018-8576](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8576): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 
-   [CVE-2018-8579](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8579): vulnerabilità della divulgazione delle informazioni relative a Microsoft Outlook 
-   [CVE-2018-8582](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8582): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 

### <a name="project-security-updates"></a>Project: aggiornamenti della sicurezza 

-   [CVE-2018-8575](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8575): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook 

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza 

-   [CVE-2018-8573](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8573): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word 

### <a name="skype-for-business-security-updates"></a>Skype for Business: aggiornamenti della sicurezza 

-   [CVE-2018-8546](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8546): vulnerabilità relativa alla sospensione del servizio in Microsoft Skype for Business 

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
-   [CVE-2018-8502](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8502): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): aggiornamento difensivo Microsoft Office 

### <a name="powerpoint-security-updates"></a>PowerPoint: aggiornamenti della sicurezza 
-   [CVE-2018-8501](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8501): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft PowerPoint

### <a name="word-security-updates"></a>Word: aggiornamenti della sicurezza 
-   [CVE-2018-8504](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8504): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word 
-   [ADV180026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180026): aggiornamento difensivo Microsoft Office 

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza 
-   [CVE-2018-8432](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8432): vulnerabilità relativa all'esecuzione di codice remoto del componente di Microsoft Graphics 

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
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilità di tipo use-after-free relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="excel-feature-updates"></a>Excel: aggiornamenti delle funzionalità
 - **Modifica collaborativa:** collaborare con altri utenti contemporaneamente all'interno della cartello di lavoro. [Altre informazioni](https://support.office.com/article/7152aa8b-b791-414c-a3bb-3024e46fb104)
 - **Il salvataggio automatico di file nel cloud è ora abilitato per impostazione predefinita:** il salvataggio automatico è attivato per impostazione predefinita nel rilascio del canale semestrale (mirato) di settembre 2018. Ciò significa che gli utenti non dovranno più preoccuparsi di perdere le modifiche nei documenti archiviati in OneDrive o SharePoint Online. Le modifiche vengono salvate automaticamente nel cloud e gli utenti non dovranno più premere esplicitamente CTRL+S o il pulsante Salva. Tuttavia, è necessario comprendere questa modifica al comportamento in modo da non apportare modifiche accidentali ai documenti. Si noti che gli utenti possono disattivare il salvataggio automatico con l'interruttore Salva automaticamente posto nella parte superiore dello schermo. È consigliabile comunicare ai propri utenti questa modifica imminente e fornire loro informazioni su come sfruttare al meglio questa nuova funzionalità in Office 365. [Altre informazioni sul salvataggio automatico](https://support.office.com/article/What-is-AutoSave-6d6bd723-ebfd-4e40-b5f6-ae6e8088f7a5) [Altre informazioni su cosa è importante che gli amministratori IT sappiano sul salvataggio automatico](https://support.office.com/article/what-it-administrators-should-know-about-autosave-88e0f80f-e5ea-441b-9c5a-259f08490ae7)
- **Cella e barra della formula per apportare modifiche migliorate:** è ora possibile usare CTRL+A per selezionare il testo in una cella o nella barra della formula. È stato anche migliorato il supporto di emoji e caratteri complessi. [Altre informazioni](https://support.office.com/article/1798d9d5-842a-42b8-9c99-9b7213f0040f)
- **Miglioramenti di Verifica accessibilità:** Verifica accessibilità ha ricevuto aggiornamenti relativi al supporto per gli standard internazionali e consigli per rendere più accessibili le cartelle di lavoro. [Altre informazioni](https://support.office.com/article/a16f6de0-2f39-4a2b-8bd8-5ad801426c7f)
- **Evitare modifiche indesiderate:** Impostare l’apertura in modalità sola lettura delle cartelle di lavoro per impedire modifiche accidentali. Passare a File > informazioni > Proteggi cartella di lavoro > Apri sempre in sola lettura

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza
-   [CVE-2018-8331](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8331): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8429](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8429): vulnerabilità relativa alla divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): vulnerabilità relativa alla divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilità della divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilità della divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

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
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilità relativa alla manomissione di Microsoft Office
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilità relativa all'elevazione di privilegi in Microsoft Outlook
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): le funzionalità di sicurezza di Microsoft Outlook ignorano la vulnerabilità
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): aggiornamento difensivo Microsoft Office

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
-   [CVE-2018-8430](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8430): vulnerabilità relativa all'esecuzione di codice remoto in Word PDF
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilità della divulgazione delle informazioni di Microsoft Office

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema che causa la visualizzazione di un messaggio relativo alla memoria insufficiente.
-   È stato risolto un problema che impediva ad alcuni utenti di aprire e-mail e documenti protetti da IRM condivisi con tali utenti da persone in altre organizzazioni.
-   Risolve alcuni problemi relativi alle prestazioni.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza
-   [CVE-2018-8332](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8332): vulnerabilità relativa all'esecuzione di codice remoto in Win32k Graphics
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   **Attivazione bloccata dei controlli Flash, Silverlight e Shockwave in Office per motivi di sicurezza:** per motivi di sicurezza, nuove build di Microsoft Office per Office 365 in Windows bloccano l'attivazione dei controlli Flash, Silverlight e Shockwave. Altre informazioni [qui](https://techcommunity.microsoft.com/t5/Security-Privacy-and-Compliance/Blocking-Flash-Shockwave-Silverlight-controls-from-activating-in/ba-p/191729) e [qui](https://support.office.com/en-us/article/flash-silverlight-and-shockwave-controls-blocked-in-office-2016-55738f12-a01d-420e-a533-7cef1ff6aeb1?ui=en-US&rs=en-US&ad=US).

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: aggiornamenti non relativi alla sicurezza
-  Risolve un problema a causa del quale l'installazione degli aggiornamenti richiedeva un lungo periodo di tempo in determinati scenari.
-  Consente di risolvere un problema a causa del quale, quando apre un'applicazione, l'utente potrebbe visualizzare un messaggio sull'avvio in modalità provvisoria e l'applicazione non si apre.
-  Risolve alcuni problemi relativi alle prestazioni.

## <a name="version-1803-august-14"></a>Versione 1803: 14 agosto
*Versione 1803 (Build 9126.2275)*

### <a name="access-security-updates"></a>Access: aggiornamenti della sicurezza
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilità di tipo use-after-free relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="excel-security-updates"></a>Excel: aggiornamenti della sicurezza
-   [CVE-2018-8375](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8375): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8379](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8379): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel 
-   [CVE-2018-8382](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8382): vulnerabilità relativa alla divulgazione delle informazioni di Microsoft Excel 

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [ADV180021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180021): aggiornamento difensivo Microsoft Office 

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: aggiornamenti della sicurezza
-   [CVE-2018-8378](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8378): vulnerabilità della divulgazione delle informazioni di Microsoft Office 

## <a name="version-1803-july-10"></a>Versione 1803: 10 luglio
*Versione 1803 (Build 9126.2259)*

### <a name="access-security-updates"></a>Access: Aggiornamenti della sicurezza
-   [CVE-2018-8312](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8312): vulnerabilità di tipo use-after-free relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [CVE-2018-8310](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8310): vulnerabilità relativa alla manomissione di Microsoft Office

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-8281](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8281): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office

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
-   [CVE-2018-8246](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8246): vulnerabilità della divulgazione delle informazioni di Microsoft Excel
-   [CVE-2018-8248](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8248): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: aggiornamenti non relativi alla sicurezza
-   Consente di correggere un problema a causa del quale a volte un'operazione di raggruppamento (o di annullamento del raggruppamento) in una tabella pivot di Excel potrebbe provocare un arresto anomalo.

### <a name="outlook-security-updates"></a>Outlook: aggiornamenti della sicurezza
-   [CVE-2018-8244](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8244): vulnerabilità relativa all'elevazione di privilegi in Microsoft Outlook

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
-   [CVE-2018-8147](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8147): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8148](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8148): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8162](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8162): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-8163](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8163): vulnerabilità della divulgazione delle informazioni di Microsoft Excel

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Excel si arresta in modo anomalo quando si apre un file da SharePoint Online.
-   Consente di risolvere un problema a causa del quale si stampa o si visualizza l'anteprima di stampa solo di una parte del foglio di lavoro, con il contenuto troncato in un filtro dei dati sul foglio di lavoro.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2018-8150](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8150): le funzionalità di sicurezza di Microsoft Outlook ignorano la vulnerabilità

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
-   [CVE-2018-8157](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8157): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-8158](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-8158): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office



## <a name="version-1803-april-10"></a>Versione 1803: 10 aprile
*Versione 1803 (Build 9126.2152)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2018-1029](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1029): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="powerpoint-non-security-updates"></a>PowerPoint: Aggiornamenti non relativi alla sicurezza
-   Consente di risolvere un problema a causa del quale la creazione condivisa da parte di più utenti sulla stessa presentazione comporta una duplicazione errata degli schemi diapositiva.
-   Consente di risolvere un problema a causa del quale l'apertura di un file salvato su OneDrive comporta l'arresto anomalo di PowerPoint all'uscita dalla visualizzazione protetta.

### <a name="skype-for-business-non-security-updates"></a>Skype for Business: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema relativo al supporto TLS 1.2.

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema che causa la visualizzazione di un messaggio relativo alla memoria insufficiente.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-0950](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0950): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-1026](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1026): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-1030](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-1030): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office



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
-   [CVE-2018-0903](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0903): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Access

### <a name="access-non-security-updates"></a>Access: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema che si verifica quando si apre un'applicazione runtime di Access (file accde); a causa di questo problema, viene visualizzato il messaggio di errore "Formato di database non riconosciuto" e l'applicazione non si apre.
-   Consente di risolvere un problema in cui se si tenta di selezionare il testo nella casella di testo di una casella combinata viene selezionato tutto il testo, anziché la parte selezionata.

### <a name="excel-feature-updates"></a>Excel: Aggiornamenti delle funzionalità
-   **Microsoft Translator:** è possibile tradurre parole e frasi in un'altra lingua con Microsoft Translator nella scheda Revisione della barra multifunzione.
-   **Conversione delle icone SVG in forme**: per cambiare il colore, le dimensioni o una trama, trasformare tutte le immagini SVG e le icone in forme di Office.
-   **Deselezionare le celle:** Consente di selezionare le opzioni del foglio di lavoro e deselezionare le celle accidentalmente selezionate senza dover ricominciare da capo.
-   **Accedere rapidamente ai siti e gruppi:** Utilizzare il menu File per utilizzare i documenti archiviati nei siti e gruppi più usati.
-   **Matita digitale:** scrivere o prendere appunti usando il nuovo tratto della matita. È sufficiente inclinare la penna digitale per fare le ombre.
-   **Impostazione delle funzionalità LinkedIn:** andare a File \> Opzioni \> Generale per controllare se le funzionalità di LinkedIn sono visualizzate nelle proprie applicazioni Office. [Altre informazioni](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelli 3D:** Utilizzare il formato 3D per aumentare l'impatto visivo e creativo delle cartelle di lavoro. Inserire facilmente un modello 3D affinché sia possibile ruotarlo di 360 gradi. [Altre informazioni](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Nuovi effetti di input penna:** esprimere le proprie idee con un tocco in più usando penne metalliche ed effetti di input penna come Arcobaleno, Galassia, Lava, Oceano, Oro, Argento e altro ancora.
-   **UI per la condivisione di file:** nel caso dei file di OneDrive for Business o SharePoint, fare clic sul pulsante Condividi nell'angolo superiore destro oppure andare a File \> Condividi per avviare una finestra di dialogo Condividi semplificata e migliorata. Per i file nuovi o salvati in locale, l'interfaccia utente permette agli utenti di caricare in un attimo i file su OneDrive e avviare la collaborazione.
-   **Bloccare estensioni pericolose:** per impostazione predefinita, viene impedita l'attivazione delle estensioni considerate ad alto rischio e incorporate come oggetti di pacchetti OLE, bloccandole. Queste sono, ad esempio, EXE, VBS e JS. [Ulteriori informazioni](https://support.office.com/article/packager-activation-in-office-365-desktop-applications-52808039-4a7c-4550-be3a-869dd338d834)
-   **Suoni utili per migliorare l'accessibilità:** attivare gli avvisi audio per ottenere assistenza durante il lavoro. Sono disponibili in File \> Opzioni \> Accessibilità. Non sono necessari componenti aggiuntivi. [Altre informazioni](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Percorsi dei file per account:** quando si apre o si salva un file, l'elenco dei percorsi è organizzato in base all'account associato.
-   **Personalizzazione della penna:** scegliere un set personale di penne ed evidenziatori per l'input penna. Il set personalizzato è disponibile in tutti i PC Windows.

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2017-11877:](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11877) le funzionalità di sicurezza di Microsoft Excel ignorano la vulnerabilità
-   [CVE-2017-11878](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11878): vulnerabilità di danneggiamento della memoria di Microsoft Excel
-   [CVE-2017-11884](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11884): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [CVE-2018-0907](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0907): superamento delle funzionalità di sicurezza di Microsoft Office Excel
-   [Avviso 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Aggiornamento difensivo di Microsoft Office

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
-   **Impostazione delle funzionalità LinkedIn:** andare a File \> Opzioni \> Generale per controllare se le funzionalità di LinkedIn sono visualizzate nelle proprie applicazioni Office. [Altre informazioni](https://support.office.com/article/dc81cc70-4d64-4755-9f1c-b9536e34d381)
-   **Modelli 3D:** Utilizzare il formato 3D per aumentare l'impatto visivo e creativo della posta elettronica.  Inserire facilmente un modello 3D affinché sia possibile ruotarlo di 360 gradi. [Altre informazioni](https://support.office.com/article/ec5feb79-b0af-47f6-a885-151fcc88ac0a)
-   **Scheda del profilo:** Mostra i dettagli più importanti di utenti e gruppi su un computer desktop, sul Web o tramite un'app per dispositivi mobili.
-   **Aggiungere un appuntamento a un calendario di gruppo:** Ora è possibile comunicare a ogni membro del gruppo quando si sarà assenti senza inviare un invito a una riunione tramite posta elettronica.
-   **Download degli allegati cloud:** quando si salvano oppure trascinano gli allegati di OneDrive nel computer, il file viene scaricato automaticamente.
-   **Suoni utili per migliorare l'accessibilità:** attivare gli avvisi audio per ottenere assistenza durante il lavoro. Sono disponibili in File \> Opzioni \> Accessibilità. Non sono necessari componenti aggiuntivi. [Altre informazioni](https://support.office.com/article/49fda9be-cce5-4c72-a87f-b11000197f5f)
-   **Posta in arrivo evidenziata:** La cartella Posta in arrivo è suddivisa in due schede: Evidenziata e Altro. I messaggi vengono ordinati in base al contenuto del messaggio e in base a con quali utenti si interagisce maggiormente. [Altre informazioni](https://support.office.com/article/f445ad7f-02f4-4294-a82e-71d8964e3978)
-   **Accedere rapidamente ai gruppi più utilizzati:** I gruppi con i quali è più probabile che si interagirà ora vengono visualizzati nella parte superiore dell'elenco in Gruppi nel riquadro delle cartelle.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2017-11939](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11939): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): vulnerabilità elevazione di privilegi in Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): vulnerabilità di danneggiamento della memoria di Microsoft Outlook

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
-   [CVE-2017-11934](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11934): vulnerabilità della divulgazione delle informazioni relative a Microsoft PowerPoint

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
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): vulnerabilità di danneggiamento della memoria di Microsoft Word
-   [CVE-2018-0919](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0919): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [Avviso 170020](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170020): Aggiornamento difensivo di Microsoft Office

### <a name="word-non-security-updates"></a>Word: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema a causa del quale Word si arresta in modo anomalo quando un utente prova a salvare con il nome un documento esistente su OneDrive for Business e in seguito si annulla il salvataggio oppure si prova a unire le modifiche esistenti.
-   Consente di correggere un errore che si verifica quando si applica un filtro ai campi dell'origine dati che contengono valori null (vuoti). A causa del problema, non si riesce ad applicare il filtro quando si esegue la procedura guidata Stampa unione.
-   Consente di risolvere un problema che si verifica durante il salvataggio di un file di supporto di sincronizzazione. In questo caso, Office non riesce a scrivere sul disco, ma continua a caricare il file su OneDrive. Grazie a questa correzione, l&apos;utente è ora in grado di visualizzare un messaggio di errore e il caricamento si arresta.
-   Consente di risolvere un problema a causa del quale l'annullamento della protezione IRM da un documento non rimuove effettivamente la protezione.

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2017-11882](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2017-11882): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): vulnerabilità della divulgazione delle informazioni di Microsoft Office
-   [Avviso 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Aggiornamento difensivo di Microsoft Office

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
-   [CVE-2018-0841](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0841): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2018-0850](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0850): vulnerabilità elevazione di privilegi in Microsoft Outlook
-   [CVE-2018-0852](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0852): vulnerabilità di danneggiamento della memoria di Microsoft Outlook

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-0851](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0851): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0853](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0853): vulnerabilità della divulgazione delle informazioni di Microsoft Office



## <a name="version-1708-january-9"></a>Versione 1708: 9 gennaio
*Versione 1708 (Build 8431.2153)*

### <a name="excel-security-updates"></a>Excel: Aggiornamenti della sicurezza
-   [CVE-2018-0796](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0796): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Excel
-   [Avviso 170021](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV170021): Aggiornamento difensivo di Microsoft Office

### <a name="excel-non-security-updates"></a>Excel: Aggiornamenti non della sicurezza
-   Consente di risolvere un problema in cui la creazione programmatica di una Tabella pivot seguita da un aggiornamento programmatico causa l’arresto anomalo di Excel.

### <a name="outlook-security-updates"></a>Outlook: Aggiornamenti della sicurezza
-   [CVE-2018-0791](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0791): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook

### <a name="word-security-updates"></a>Word: Aggiornamenti della sicurezza
-   [CVE-2018-0792](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0792): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0793](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0793): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Outlook
-   [CVE-2018-0794](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0794): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0798](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0798): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0801](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0801): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [CVE-2018-0802](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0802): vulnerabilità di danneggiamento della memoria di Microsoft Office
-   [CVE-2018-0804](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0804): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0805](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0805): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0806](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0806): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0807](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0807): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Word
-   [CVE-2018-0812](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0812): vulnerabilità di danneggiamento della memoria di Microsoft Word

### <a name="office-suite-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti della sicurezza
-   [CVE-2018-0795](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/CVE-2018-0795): vulnerabilità relativa all'esecuzione di codice remoto in Microsoft Office
-   [Avviso 180003](https://portal.msrc.microsoft.com/en-us/security-guidance/advisory/ADV180003): Aggiornamento difensivo di Microsoft Office

### <a name="office-suite-non-security-updates"></a>Famiglia di prodotti Office: Aggiornamenti non relativi alla sicurezza
-   Consente di aggiungere il supporto per Single Sign-On (SSO) per gli utenti del dominio per i piani di Office 365 Germania, in cui l'identità è federata con Active Directory locale.
-   Consente di aggiungere funzionalità per impedire ai minorenni di acquistare e attivare componenti aggiuntivi per Office dall’Office Store.


> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
