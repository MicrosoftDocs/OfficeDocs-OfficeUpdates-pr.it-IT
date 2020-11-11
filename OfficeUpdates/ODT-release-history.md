---
title: Cronologia delle versioni per lo Strumento di distribuzione di Office (ODT)
ms.author: timda
author: TimDavenport
manager: TimDavenport
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ODT
description: Fornisce ai professionisti IT una cronologia delle versioni per lo Strumento di distribuzione di Office (ODT)
ms.openlocfilehash: b14d9998a0dab3ea0d4a4f6cae10702688fa4427
ms.sourcegitcommit: d898fa4f06c90444f9d729a1b0df2c82bde7d719
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/11/2020
ms.locfileid: "48992681"
---
# <a name="release-history-for-office-deployment-tool"></a>Cronologia delle versioni per lo Strumento di distribuzione di Office

Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client. 


Lo strumento ODT consente un maggiore controllo sull'installazione di Office. È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti. Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).

 **Sistema operativo supportato** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016 
 
 **Istruzioni di installazione** : scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml). 

[Scaricare lo Strumento di distribuzione di Office](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-10-2020"></a>10 novembre 2020
Versione 16.0.13328.20356 (setupODT.exe versione 16.0.13328.20336)
- Miglioramenti per affidabilità e resilienza
- Per evitare confusione e diagnosticare più facilmente errori di configurazione, lo Strumento di distribuzione di Office è ora denominato setupODT.exe per impostazione predefinita.

## <a name="october-29-2020"></a>29 ottobre 2020
Versione 16.0.13328.20292 (setup.exe versione 16.0.13328.20290)
- Risolve un problema per cui alcuni prodotti di Office 2007 bloccavano in modo imprevisto l'installazione quando si usava RemoveMSI

## <a name="october-14-2020"></a>14 ottobre 2020
Versione 16.0.13231.20368 (setup.exe versione 16.0.13231.20350)
- Tutti i prodotti useranno ora Canale mensile per impostazione predefinita, se non viene specificato alcun canale
- Sicurezza ottimizzata durante l'esecuzione di ODT da una directory che contiene altri DLL
- Migliorie per affidabilità e resilienza

## <a name="june-9-2020"></a>9 giugno 2020

Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)
- Il Canale corrente ora è il canale predefinito se non viene specificato un canale
- Aggiunta del supporto per il Canale Enterprise mensile
- Aggiunta del supporto per i nomi nuovi dei canali
- Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua
- Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007
- Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access 

## <a name="april-15-2020"></a>15 aprile 2020

Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)
- Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7
- Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto
- Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto

## <a name="january-16-2020"></a>16 gennaio 2020

Versione 16.0.12325.20288
- Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue
- Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.
- Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)


## <a name="october-31-2019"></a>31 ottobre 2019

Versione 16.0.12130.20272
- Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019
- Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy
- Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80


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