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
ms.openlocfilehash: c01fbe403dacb0b474c37b7439eba5b616f8a08f
ms.sourcegitcommit: 591f5da255de896ef3156108349c6d2eaf34ed54
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/22/2020
ms.locfileid: "48174645"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="390f0-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="390f0-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="390f0-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="390f0-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="390f0-105">Lo strumento ODT consente un maggiore controllo sull'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="390f0-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="390f0-106">È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti.</span><span class="sxs-lookup"><span data-stu-id="390f0-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="390f0-107">Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="390f0-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="390f0-108">**Sistema operativo supportato**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="390f0-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="390f0-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="390f0-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="390f0-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="390f0-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="june-9-2020"></a><span data-ttu-id="390f0-111">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="390f0-111">June 9, 2020</span></span>

<span data-ttu-id="390f0-112">Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="390f0-112">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="390f0-113">Il Canale corrente ora è il canale predefinito se non viene specificato un canale</span><span class="sxs-lookup"><span data-stu-id="390f0-113">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="390f0-114">Aggiunta del supporto per il Canale Enterprise mensile</span><span class="sxs-lookup"><span data-stu-id="390f0-114">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="390f0-115">Aggiunta del supporto per i nomi nuovi dei canali</span><span class="sxs-lookup"><span data-stu-id="390f0-115">Added support for new channel names</span></span>
- <span data-ttu-id="390f0-116">Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua</span><span class="sxs-lookup"><span data-stu-id="390f0-116">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="390f0-117">Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007</span><span class="sxs-lookup"><span data-stu-id="390f0-117">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="390f0-118">Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access</span><span class="sxs-lookup"><span data-stu-id="390f0-118">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="390f0-119">15 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="390f0-119">April 15, 2020</span></span>

<span data-ttu-id="390f0-120">Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="390f0-120">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="390f0-121">Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7</span><span class="sxs-lookup"><span data-stu-id="390f0-121">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="390f0-122">Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto</span><span class="sxs-lookup"><span data-stu-id="390f0-122">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="390f0-123">Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto</span><span class="sxs-lookup"><span data-stu-id="390f0-123">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="390f0-124">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="390f0-124">January 16, 2020</span></span>

<span data-ttu-id="390f0-125">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="390f0-125">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="390f0-126">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="390f0-126">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="390f0-127">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="390f0-127">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="390f0-128">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="390f0-128">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="390f0-129">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-129">October 31, 2019</span></span>

<span data-ttu-id="390f0-130">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="390f0-130">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="390f0-131">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-131">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="390f0-132">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="390f0-132">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="390f0-133">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="390f0-133">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="390f0-134">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-134">July 10, 2019</span></span>

<span data-ttu-id="390f0-135">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="390f0-135">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="390f0-136">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="390f0-136">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="390f0-137">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="390f0-137">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="390f0-138">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-138">April 23, 2019</span></span>

<span data-ttu-id="390f0-139">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="390f0-139">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="390f0-140">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="390f0-140">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="390f0-141">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="390f0-141">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="390f0-142">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-142">April 16 2019</span></span>

<span data-ttu-id="390f0-143">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="390f0-143">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="390f0-144">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="390f0-144">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="390f0-145">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="390f0-145">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="390f0-146">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="390f0-146">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="390f0-147">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-147">March 13, 2019</span></span>

<span data-ttu-id="390f0-148">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="390f0-148">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="390f0-149">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="390f0-149">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="390f0-150">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="390f0-150">January 14, 2019</span></span>

<span data-ttu-id="390f0-151">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="390f0-151">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="390f0-152">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="390f0-152">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="390f0-153">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="390f0-153">Related links</span></span>

[<span data-ttu-id="390f0-154">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="390f0-154">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)