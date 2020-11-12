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
ms.openlocfilehash: acc7e37ae203c824c0759eab641491d377073a7f
ms.sourcegitcommit: 0cba381a1439abdc7044a81772609c91998d65f0
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/12/2020
ms.locfileid: "48999541"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="8051f-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="8051f-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="8051f-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="8051f-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="8051f-p101">Lo strumento ODT consente un maggiore controllo sull'installazione di Office: è possibile specificare i prodotti e le lingue installate, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti. Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="8051f-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="8051f-108">**Sistema operativo supportato** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="8051f-108">**Supported Operating System** : Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="8051f-109">**Istruzioni di installazione** : scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setupodt.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="8051f-109">**Install Instructions** : Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setupodt.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="8051f-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="8051f-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-10-2020"></a><span data-ttu-id="8051f-111">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="8051f-111">November 10, 2020</span></span>
<span data-ttu-id="8051f-112">Versione 16.0.13328.20356 (setupODT.exe versione 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="8051f-112">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="8051f-113">Miglioramenti per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="8051f-113">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="8051f-114">Per evitare confusione e diagnosticare più facilmente errori di configurazione, lo Strumento di distribuzione di Office è ora denominato setupODT.exe per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="8051f-114">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="8051f-115">29 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="8051f-115">October 29, 2020</span></span>
<span data-ttu-id="8051f-116">Versione 16.0.13328.20292 (setup.exe versione 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="8051f-116">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="8051f-117">Risolve un problema per cui alcuni prodotti di Office 2007 bloccavano in modo imprevisto l'installazione quando si usava RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="8051f-117">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="8051f-118">14 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="8051f-118">October 14, 2020</span></span>
<span data-ttu-id="8051f-119">Versione 16.0.13231.20368 (setup.exe versione 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="8051f-119">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="8051f-120">Tutti i prodotti useranno ora Canale mensile per impostazione predefinita, se non viene specificato alcun canale</span><span class="sxs-lookup"><span data-stu-id="8051f-120">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="8051f-121">Sicurezza ottimizzata durante l'esecuzione di ODT da una directory che contiene altri DLL</span><span class="sxs-lookup"><span data-stu-id="8051f-121">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="8051f-122">Migliorie per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="8051f-122">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="8051f-123">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="8051f-123">June 9, 2020</span></span>

<span data-ttu-id="8051f-124">Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="8051f-124">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="8051f-125">Il Canale corrente ora è il canale predefinito se non viene specificato un canale</span><span class="sxs-lookup"><span data-stu-id="8051f-125">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="8051f-126">Aggiunta del supporto per il Canale Enterprise mensile</span><span class="sxs-lookup"><span data-stu-id="8051f-126">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="8051f-127">Aggiunta del supporto per i nomi nuovi dei canali</span><span class="sxs-lookup"><span data-stu-id="8051f-127">Added support for new channel names</span></span>
- <span data-ttu-id="8051f-128">Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua</span><span class="sxs-lookup"><span data-stu-id="8051f-128">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="8051f-129">Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007</span><span class="sxs-lookup"><span data-stu-id="8051f-129">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="8051f-130">Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access</span><span class="sxs-lookup"><span data-stu-id="8051f-130">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="8051f-131">15 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="8051f-131">April 15, 2020</span></span>

<span data-ttu-id="8051f-132">Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="8051f-132">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="8051f-133">Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7</span><span class="sxs-lookup"><span data-stu-id="8051f-133">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="8051f-134">Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto</span><span class="sxs-lookup"><span data-stu-id="8051f-134">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="8051f-135">Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto</span><span class="sxs-lookup"><span data-stu-id="8051f-135">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="8051f-136">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="8051f-136">January 16, 2020</span></span>

<span data-ttu-id="8051f-137">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="8051f-137">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="8051f-138">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="8051f-138">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="8051f-139">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="8051f-139">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="8051f-140">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="8051f-140">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="8051f-141">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-141">October 31, 2019</span></span>

<span data-ttu-id="8051f-142">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="8051f-142">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="8051f-143">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-143">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="8051f-144">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="8051f-144">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="8051f-145">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="8051f-145">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="8051f-146">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-146">July 10, 2019</span></span>

<span data-ttu-id="8051f-147">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="8051f-147">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="8051f-148">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="8051f-148">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="8051f-149">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="8051f-149">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="8051f-150">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-150">April 23, 2019</span></span>

<span data-ttu-id="8051f-151">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="8051f-151">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="8051f-152">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="8051f-152">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="8051f-153">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="8051f-153">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="8051f-154">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-154">April 16 2019</span></span>

<span data-ttu-id="8051f-155">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="8051f-155">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="8051f-156">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="8051f-156">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="8051f-157">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="8051f-157">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="8051f-158">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="8051f-158">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="8051f-159">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-159">March 13, 2019</span></span>

<span data-ttu-id="8051f-160">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="8051f-160">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="8051f-161">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="8051f-161">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="8051f-162">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="8051f-162">January 14, 2019</span></span>

<span data-ttu-id="8051f-163">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="8051f-163">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="8051f-164">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="8051f-164">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="8051f-165">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="8051f-165">Related links</span></span>

[<span data-ttu-id="8051f-166">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="8051f-166">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)