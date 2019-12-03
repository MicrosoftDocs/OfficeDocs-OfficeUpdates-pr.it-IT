---
title: Note sulla versione per il Canale mensile (mirato)
ms.author: anankani
author: v-lislo
manager: andrewmo
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Offre ai partecipanti al programma Insider Slow un elenco aggiornato delle nuove funzionalità, correzioni o problemi noti principali
ms.openlocfilehash: a1ad777f8794fe2ec85b583ebd51dcdfe6b07f06
ms.sourcegitcommit: 2008f3580435cc725ca36b2f762e5adf4df7f89a
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 12/02/2019
ms.locfileid: "39668046"
---
# <a name="release-notes-for-office-monthly-channel-targeted"></a>Note sulla versione per il Canale mensile (mirato) di Office

Questo articolo contiene le note sulla versione per le build del Canale mensile (mirato) di Word, Excel, PowerPoint, Outlook, Access e Project per Windows desktop. Ogni settimana vengono evidenziate nuove funzionalità interessanti, correzioni critiche e problemi significativi di cui è importante essere a conoscenza. Si noti che spesso le funzionalità (e talvolta persino le correzioni) vengono distribuite nel Canale mensile (mirato) in un certo arco di tempo. Ciò consente di verificare che tutto funzioni correttamente prima di rilasciare la funzionalità a un pubblico più ampio. Pertanto, anche se al momento non fossero disponibili descrizioni, prima o poi lo saranno.  

> [!NOTE]
> - La data di pubblicazione delle note sulla versione può non corrispondere all'effettiva data di rilascio della build.
> - Microsoft Teams in installazioni esistenti di Office 365 ProPlus: a partire dalla fine di giugno, Microsoft Teams verrà incluso nelle installazioni esistenti di Office 365 ProPlus (e Office 365 Business) quando si eseguono gli aggiornamenti di queste installazioni. La data in cui Teams verrà aggiunto dipende dal canale di aggiornamento usato. Per altre informazioni fare riferimento a [Distribuire Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

[//]: # (NON RIMUOVERE)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)


## <a name="version-1911-november-20"></a>Versione 1911: 20 novembre
*Versione 1911 (Build 12228.20250)*


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="outlook"></a>Outlook

- **Impostazioni avanzate della posta elettronica del gruppo:** questa funzionalità consente a gruppi di utenti di personalizzare i messaggi di posta elettronica o gli eventi da ricevere/seguire nella Posta in arrivo.

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-1911-november-15"></a>Versione 1911: 15 novembre
*Versione 1911 (Build 12228.20206)*

## <a name="version-1911-november-12"></a>Versione 1911: 12 novembre
*Versione 1911 (Build 12228.20120)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a>Aggiornamenti delle funzionalità
### <a name="excel"></a>Excel

- **Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel. [Altre informazioni](https://support.office.com/it-IT/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="outlook"></a>Outlook

- **Invio di messaggi accessibili a chi ne ha bisogno:** in Outlook viene visualizzato un suggerimento per i messaggi che consente di verificare l'accessibilità dei contenuti quando si invia a un utente che preferisce contenuto accessibile.

### <a name="powerpoint"></a>PowerPoint

- **Ottimizzazione della presentazione per tutti:** Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.

### <a name="visio"></a>Visio

- **Creare diagrammi di Visio chiari in Excel:** è possibile visualizzare i dati in modo semplice e rapido nei diagrammi di Visio in Excel. [Altre informazioni](https://support.office.com/it-IT/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a>Word

- **Miglioramenti apportati alla creazione condivisa:** l'esperienza di creazione condivisa è stata migliorata aumentando la probabilità che gli altri utenti ricevano in tempo reale le modifiche apportate al contenuto.

### <a name="office-suite"></a>Famiglia di prodotti Office

- **L'Upload Center verrà sostituito dall'esperienza File che richiedono attenzione:** l'Upload Center sarà sostituito dall'esperienza File che richiedono attenzione visualizzata all'interno delle applicazioni Office in File > Apri. Questa nuova esperienza è più moderna, integrata e meno intrusiva rispetto all'Upload Center.


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a>Problemi risolti
### <a name="access"></a>Access

- Il conteggio record poteva non essere corretto.

### <a name="excel"></a>Excel

- È stato risolto un problema per cui l'eliminazione di fogli contenenti grafici sparkline che fanno riferimento a un altro foglio poteva far sì che il file venisse identificato come corrotto in fase di riapertura.
- Non era possibile salvare le modifiche apportate alle dimensioni di un grafico.
- Il rendering delle caselle di controllo non veniva eseguito correttamente.
- Le finestre di dialogo di selezione origine dati non facevano distinzione tra maiuscole e minuscole per alcuni campi.
- Alcune funzioni VBA restituivano un errore nei nuovi grafici.
- Era possibile che gli utenti non riuscissero a salvare in formato cartella di lavoro di Excel in Office 365.
- È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.
- È stato risolto un problema per cui potevano essere ottenuti risultati non corretti durante la conversione di filtri rapporto con il resto della Tabella pivot per le query ai server tabulari SQL.
- È stato risolto un problema che poteva causare un errore di Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.
- L'uso simultaneo di Assistente vocale e Lente di ingrandimento poteva causare un arresto anomalo.
- È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.
- Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.

### <a name="onenote"></a>OneNote

- È stato rilevato un problema che può influire sulla sincronizzazione di una risorsa locale con una risorsa cloud.

### <a name="outlook"></a>Outlook

- Lo strumento Ricerca sala poteva mostrare &quot;Nessuna&quot; per le sale disponibili.
- È stato rilevato un problema per cui la casella di ricerca spariva quando la barra multifunzione era impostata su Nascondi automaticamente.
- È stato rilevato un problema che causava il danneggiamento della firma digitale quando si firmava un messaggio di posta elettronica con un allegato con firma digitale.
- Un messaggio di posta elettronica inoltrato potrebbe essere privo di immagini incorporate.
- Gli utenti potrebbero non riuscire a creare profili di Outlook con restrizioni rigorose del tenant.
- È stato rilevato un problema per cui i nomi file lunghi venivano troncati dopo il trascinamento e il rilascio nel corpo del messaggio.

### <a name="powerpoint"></a>PowerPoint

- Non era possibile salvare le modifiche apportate alle dimensioni di un grafico.
- L'uso simultaneo di Assistente vocale e Lente di ingrandimento poteva causare un arresto anomalo.
- È stato rilevato un problema per cui le proporzioni dell'anteprima delle diapositive non venivano bloccate/sbloccate correttamente.

### <a name="project"></a>Project

- È stato rilevato un problema per cui le note venivano cancellate se aggiunte durante operazioni di aggiornamento.
- L'utente non è in grado di contrassegnare un'attività come completata e tale attività viene impostata su 99%.
- Le sovrassegnazioni non vengono risolte dal livellamento.
- È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.
- È stato rilevato un problema per cui un file poteva venire bloccato da un utente, ma nel messaggio di errore non veniva visualizzato alcun nome utente.

### <a name="publisher"></a>Publisher

- Le forme potevano essere visualizzate fuori dal bordo dell'elemento grafico.

### <a name="word"></a>Word

- I suggerimenti degli strumenti di correzione non vengono visualizzati nei menu di scelta rapida.
- Non era possibile salvare le modifiche apportate alle dimensioni di un grafico.
- Le forme potevano essere visualizzate fuori dal bordo dell'elemento grafico.
- È stato rilevato un problema durante la visualizzazione dei commenti con un'utilità per la lettura dello schermo.
- È stato rilevato un problema per cui alcune critiche venivano identificate come errori di ortografia o grammatica.
- I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.
- Potrebbero essere visualizzati dei caratteri errati quando si usa la correzione automatica coreano/inglese.
- La ricerca dal riquadro di spostamento potrebbe non riuscire.
- L'uso simultaneo di Assistente vocale e Lente di ingrandimento poteva causare un arresto anomalo.
- I criteri di contenuto vengono applicati ai commenti in modo errato.
- Potrebbero essere applicate etichette criteri inferiori quando dovrebbe avere la priorità un'etichetta criteri di livello superiore.
- L'apertura di documenti legacy e il successivo passaggio alla scheda Informazioni può causare un arresto anomalo.
- È stato rilevato un problema per cui una nuova finestra di dialogo commento poteva non ottenere lo stato attivo.
- Poteva risultare impossibile aprire una scheda contatto dopo aver applicato la formattazione a una @menzione.
- Evidenziare il testo poteva risultare problematico.
- È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint. Questo problema interessa gli utenti che creano un nuovo file e visualizzano l'opzione "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.
- I commenti legacy scritti con testo scuro non sono visibili in modalità scura.
- Poteva non essere possibile passare a un singolo elemento nell'editor.
- Alcuni errori grammaticali o ortografici potevano non essere segnalati.

### <a name="office-suite"></a>Famiglia di prodotti Office

- Alcuni disegni potrebbero non essere visualizzati in anteprima o nelle presentazioni.
- È stato risolto un problema per cui un aggiornamento potrebbe essere impedito da un messaggio errato di errore di un'altra installazione in corso.
- Alcuni caratteri katakana potrebbero non essere visualizzati correttamente in una casella di testo verticale.
- Se si tenta di salvare un file in una condivisione di rete disconnessa, potrebbe verificarsi un errore.
- Problema di prestazioni correlato all'uso delle forme in Windows 7.

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

