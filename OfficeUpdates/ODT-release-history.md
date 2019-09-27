---
title: Cronologia delle versioni per lo Strumento di distribuzione di Office (ODT)
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fornisce ai professionisti IT una cronologia delle versioni per lo Strumento di distribuzione di Office (ODT)
ms.openlocfilehash: 1622ddf9a89767c2d0e456737362eecf4123b3fd
ms.sourcegitcommit: a5da36df390868d76bddfc78e9481ed8e9c5b673
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/26/2019
ms.locfileid: "37275487"
---
# <a name="release-history-for-office-deployment-tool"></a>Cronologia delle versioni per lo Strumento di distribuzione di Office

Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Office 365 ProPlus, nei computer client. 


Lo strumento ODT consente un maggiore controllo sull'installazione di Office. È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti. Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/it-IT/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Sistema operativo supportato**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2. 
 
 **Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml). 

[Scaricare lo Strumento di distribuzione di Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="july-10-2019"></a>10 luglio 2019

Versione 16.0.11901.20022
- Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.
- Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.

## <a name="april-23-2019"></a>23 aprile 2019

Versione 16.0.11617.33601
- Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.
- Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).

## <a name="april-16-2019"></a>16 aprile 2019

Versione 16.0.11615.33602
- Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.
- Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).
- Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.

## <a name="march-13-2019"></a>13 marzo 2019

Versione 16.0.11509.33604
- Miglioramenti agli scenari di aggiornamento e migrazione.

## <a name="january-14-2019"></a>14 gennaio 2019

Versione 16.0.11306.33602
- Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.


## <a name="related-links"></a>Collegamenti correlati

[Area download ODT](https://www.microsoft.com/en-us/download/details.aspx?id=49117)