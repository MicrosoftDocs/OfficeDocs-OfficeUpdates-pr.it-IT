---
title: Note sulle versioni per i rilasci del Canale semestrale (mirato) nel 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale semestrale (mirato) per Office 365 ProPlus nel 2020
ms.openlocfilehash: 64270156e5985b3214a0e75c56f4bdb1713125fa
ms.sourcegitcommit: 3598ca5e26109a1f99349ce3a4e70cb1d6f13e05
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 02/14/2020
ms.locfileid: "41978714"
---
# <a name="release-notes-for-semi-annual-channel-targeted-releases-in-2020"></a>Note sulle versioni per i rilasci del Canale semestrale (mirato) nel 2020

Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale semestrale (mirato) per Office 365 ProPlus nel 2020, Visio Pro per Office 365, Project Online Desktop Client e Office 365 Business.

> [!NOTE]
>
> - Spesso le funzionalità (e talvolta persino le correzioni) vengono distribuite nel Canale semestrale (mirato) in un certo arco di tempo. Se una funzionalità descritta di seguito non è ancora disponibile, non c'è da preoccuparsi. Arriverà a breve. [Altre informazioni](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516?ui=en-US&rs=en-US&ad=US)
> - Microsoft Teams è incluso nelle nuove installazioni del Canale semestrale (mirato), a partire dalla versione 1902. Teams verrà aggiunto alle installazioni esistenti del Canale semestrale (mirato) quando queste verranno aggiornate alla versione 1908 o successiva. Per altre informazioni, vedere [Distribuire Microsoft Teams con Office 365 ProPlus](https://docs.microsoft.com/deployoffice/teams-install).

## <a name="version-1908-february-11"></a>Versione 1908: 11 febbraio
*Versione 1908 (Build 11929.20606)*

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/it-IT/officeupdates/office365-proplus-security-updates)


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


- È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix. [Qui](https://support.microsoft.com/it-IT/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) è disponibile il singolo articolo della Knowledge Basa in cui è stato documentato per le versioni precedenti.

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

Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/office365-proplus-security-updates)


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

### <a name="office-suite"></a>Famiglia di prodotti Office

- È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto. In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.

- È stato risolto un problema per cui, in alcuni casi, un aggiornamento non veniva applicato se l'utente non era un amministratore e non era disponibile la connettività di rete per l'account di sistema.


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).