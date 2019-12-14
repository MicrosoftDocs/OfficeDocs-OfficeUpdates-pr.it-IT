---
title: Problemi noti di Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Sono disponibili informazioni sui problemi noti di Office 365 ProPlus
ms.openlocfilehash: 73cd91d43e09900d81418427dab1da01d89f227b
ms.sourcegitcommit: 18190a7f0d562d254300120529a4dfd0d47d26d9
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 12/14/2019
ms.locfileid: "40023551"
---
# <a name="office-365-proplus-known-issues"></a>Problemi noti di Office 365 ProPlus

Questi problemi noti forniscono informazioni sugli aggiornamenti non della sicurezza inclusi negli aggiornamenti del Canale mensile, SACT e SAC per Office 365 ProPlus nel 2019, Visio Pro per Office 365, Project Online Desktop Client e Office 365 Business.

Questa tabella offre un riepilogo dei problemi attuali attivi e dei problemi che sono stati risolti.  La tabella seguente verrà aggiornata con i problemi rilevanti che vengono esaminati.

> [!NOTE]
>- L'elenco non è completo.
>- Se si verifica un problema in un canale diverso dal canale indicato come risolto, la risoluzione sarà presto effettuata. [Altre informazioni](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- I problemi risolti sono documentati anche nelle rispettive pagine del canale.

<br>

### <a name="last-updated-november-12-2019"></a>Ultimo aggiornamento 12 novembre 2019

### <a name="excel"></a>Excel

- I controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe<br><br>**In analisi**: mensile, SACT

- Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.<br><br>**Risolto**: Versione SACT 1908 (11929.20436) 

- Era possibile che gli utenti non riuscissero a salvare in formato cartella di lavoro Excel in Office 365<br><br>**Risolto**: Versione SACT 1908 (11929.20436)


- Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.<br><br>**Risolto**: Versione SACT 1908 (11929.20436)

- Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite<br><br>**In analisi**: SACT<br>**Risolto**: Versione mensile 1910 (12130.20272)

- Risultati non corretti ottenuti durante la conversione dei filtri dei report con il resto della Tabella pivot per le query ai server tabulari SQL.<br><br>**In analisi**: mensile

- Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico<br><br>**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436)


- È stato rilevato un problema relativo all'inserimento di file come oggetti da OneDrive.<br><br> **Risolto**: Versione mensile 1910 (12130.20272)

- È stato rilevato un problema per cui le cartelle di lavoro create in versioni precedenti di Office possono causare il blocco di Excel se aperte nelle versioni correnti di Office.<br><br>
**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436), versione SAC 1902 (11328.20468)

- È stato rilevato un problema che causava ritardi nella visualizzazione dei valori digitati dopo l'eliminazione di un intervallo.<br><br>
**Risolto**: Versione SAC 1902 (11328.20468)

- È stato rilevato un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.<br><br>
**In analisi**: SACT <br>**Risolto**: Versione mensile 1910 (12130.20272)

- È stato rilevato un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.<br><br>
**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20300)

### <a name="outlook"></a>Outlook

- È stato rilevato un problema per cui alcuni utenti visualizzavano cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.<br><br>
**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436)

- È stato rilevato un problema che causava una perdita di memoria. <br><br>
**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20388), versione SAC 1902 (11328.20468)

- È stato risolto un problema per cui alcuni utenti visualizzavano cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.<br><br>
**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436)

- È stato rilevato un problema che comportava un arresto anomalo quando un utente riceveva un messaggio di "Conversazione non effettuata" da Skype.<br><br>
**Risolto**: Versione mensile 1910 (12130.20272)

- È stato rilevato un problema per il quale gli utenti ricevevano un messaggio di errore generico "operazione non riuscita" all'apertura di un allegato in un computer in cui è abilitato DisableBGSave.<br><br>
**Risolto**: Versione mensile 1910 (12130.20272)

- È stato rilevato un problema con i collegamenti di CID: le immagini (immagini basate su posta elettronica di Outlook) non possono essere interrotte.<br><br>
**Risolto**: Versione SACT 1908 (11929.20436)

- È stato rilevato un problema che causava un messaggio di errore non corretto quando si provava a inviare posta elettronica crittografata s/MIME.<br><br>**Risolto**: Versione mensile 1910 (12130.20272)

### <a name="powerpoint"></a>PowerPoint

- Alcuni caratteri katakana potrebbero non essere visualizzati correttamente in una casella di testo verticale.<br><br>
**In analisi**: mensile

- È stato rilevato un problema che impediva la creazione di un collegamento ipertestuale quando si incollava il testo con tale collegamento. <br><br>**Risolto**: Versione mensile 1910 (12130.20272)

- È stato rilevato un problema che causava il danneggiamento dei TextRanges dopo aver incollato il testo nei segnaposto intestazione/piè di pagina/numero nello schema diapositiva e layout di diapositiva. <br><br>**Risolto**: Versione mensile 1910 (12130.20272)

- È stato identificato un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.<br>
<br>**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20396), versione SAC 1902 (11328.20468)

### <a name="project"></a>Project

- In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.<br><br>
**In analisi**: mensile<br>
**Risolto**: Versione SACT 1908 (11929.20436)

- Le sovrassegnazioni non vengono risolte dal livellamento<br><br>
**In analisi**: mensile

- È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.<br><br>
**Risolto**: Versione mensile 1910 (12130.20344), versione SACT 1908 (11929.20436)

### <a name="word"></a>Word

- La ricerca dal riquadro di spostamento potrebbe non riuscire<br><br>
**In analisi**: mensile

- È stato rilevato un problema relativo all'inserimento di file come oggetti da OneDrive.<br><br> **Risolto**: Versione mensile 1910 (12130.20272)

### <a name="office-suite"></a>Applicazioni Office
- Se si tenta di salvare un file in una condivisione di rete disconnessa, potrebbero verificarsi dei problemi **In analisi**: mensile



<br>
<br>

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).
