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
ms.openlocfilehash: a1553a3f08a254c9c177fec88073073c34a3427c
ms.sourcegitcommit: 413694d561d367e93ad51c9be41495ad09a24af3
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/23/2020
ms.locfileid: "49385482"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="69d25-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="69d25-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="69d25-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="69d25-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="69d25-p101">Lo strumento ODT consente un maggiore controllo sull'installazione di Office: è possibile specificare i prodotti e le lingue installate, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti. Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="69d25-p101">The ODT gives you more control over an Office installation. You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users. For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="69d25-108">**Sistema operativo supportato**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="69d25-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="69d25-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="69d25-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="69d25-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="69d25-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="november-23-2020"></a><span data-ttu-id="69d25-111">23 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-111">November 23, 2020</span></span>
<span data-ttu-id="69d25-112">Versione 16.0.13328.20420 (setup.exe versione 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="69d25-112">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="69d25-113">È stato risolto un problema per cui gli strumenti di correzione non venivano scaricati in /modalità download</span><span class="sxs-lookup"><span data-stu-id="69d25-113">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="69d25-114">È stato risolto un problema per cui la /modalità download non funzionava se eseguita in un contesto utente non elevato</span><span class="sxs-lookup"><span data-stu-id="69d25-114">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="69d25-115">È stato risolto un problema per cui la specifica di un attributo di Version nell'XML di configurazione causava un download incompleto in /modalità download</span><span class="sxs-lookup"><span data-stu-id="69d25-115">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="69d25-116">È stato risolto un problema per cui lo strumento di distribuzione di Office non era denominato "setup.exe" quando veniva estratto</span><span class="sxs-lookup"><span data-stu-id="69d25-116">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="69d25-117">È stato risolto un problema relativo alla priorità dell'origine dell'installazione quando viene fornito un attributo del canale nell'XML di configurazione</span><span class="sxs-lookup"><span data-stu-id="69d25-117">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="69d25-118">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-118">November 10, 2020</span></span>
<span data-ttu-id="69d25-119">Versione 16.0.13328.20356 (setupODT.exe versione 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="69d25-119">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="69d25-120">Miglioramenti per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="69d25-120">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="69d25-121">Per evitare confusione e diagnosticare più facilmente errori di configurazione, lo Strumento di distribuzione di Office è ora denominato setupODT.exe per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="69d25-121">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="69d25-122">29 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-122">October 29, 2020</span></span>
<span data-ttu-id="69d25-123">Versione 16.0.13328.20292 (setup.exe versione 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="69d25-123">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="69d25-124">Risolve un problema per cui alcuni prodotti di Office 2007 bloccavano in modo imprevisto l'installazione quando si usava RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="69d25-124">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="69d25-125">14 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-125">October 14, 2020</span></span>
<span data-ttu-id="69d25-126">Versione 16.0.13231.20368 (setup.exe versione 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="69d25-126">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="69d25-127">Tutti i prodotti useranno ora Canale mensile per impostazione predefinita, se non viene specificato alcun canale</span><span class="sxs-lookup"><span data-stu-id="69d25-127">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="69d25-128">Sicurezza ottimizzata durante l'esecuzione di ODT da una directory che contiene altri DLL</span><span class="sxs-lookup"><span data-stu-id="69d25-128">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="69d25-129">Migliorie per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="69d25-129">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="69d25-130">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-130">June 9, 2020</span></span>

<span data-ttu-id="69d25-131">Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="69d25-131">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="69d25-132">Il Canale corrente ora è il canale predefinito se non viene specificato un canale</span><span class="sxs-lookup"><span data-stu-id="69d25-132">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="69d25-133">Aggiunta del supporto per il Canale Enterprise mensile</span><span class="sxs-lookup"><span data-stu-id="69d25-133">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="69d25-134">Aggiunta del supporto per i nomi nuovi dei canali</span><span class="sxs-lookup"><span data-stu-id="69d25-134">Added support for new channel names</span></span>
- <span data-ttu-id="69d25-135">Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua</span><span class="sxs-lookup"><span data-stu-id="69d25-135">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="69d25-136">Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007</span><span class="sxs-lookup"><span data-stu-id="69d25-136">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="69d25-137">Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access</span><span class="sxs-lookup"><span data-stu-id="69d25-137">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="69d25-138">15 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-138">April 15, 2020</span></span>

<span data-ttu-id="69d25-139">Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="69d25-139">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="69d25-140">Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7</span><span class="sxs-lookup"><span data-stu-id="69d25-140">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="69d25-141">Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto</span><span class="sxs-lookup"><span data-stu-id="69d25-141">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="69d25-142">Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto</span><span class="sxs-lookup"><span data-stu-id="69d25-142">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="69d25-143">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="69d25-143">January 16, 2020</span></span>

<span data-ttu-id="69d25-144">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="69d25-144">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="69d25-145">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="69d25-145">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="69d25-146">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="69d25-146">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="69d25-147">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="69d25-147">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="69d25-148">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-148">October 31, 2019</span></span>

<span data-ttu-id="69d25-149">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="69d25-149">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="69d25-150">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-150">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="69d25-151">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="69d25-151">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="69d25-152">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="69d25-152">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="69d25-153">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-153">July 10, 2019</span></span>

<span data-ttu-id="69d25-154">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="69d25-154">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="69d25-155">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="69d25-155">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="69d25-156">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="69d25-156">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="69d25-157">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-157">April 23, 2019</span></span>

<span data-ttu-id="69d25-158">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="69d25-158">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="69d25-159">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="69d25-159">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="69d25-160">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="69d25-160">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="69d25-161">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-161">April 16 2019</span></span>

<span data-ttu-id="69d25-162">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="69d25-162">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="69d25-163">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="69d25-163">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="69d25-164">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="69d25-164">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="69d25-165">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="69d25-165">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="69d25-166">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-166">March 13, 2019</span></span>

<span data-ttu-id="69d25-167">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="69d25-167">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="69d25-168">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="69d25-168">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="69d25-169">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="69d25-169">January 14, 2019</span></span>

<span data-ttu-id="69d25-170">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="69d25-170">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="69d25-171">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="69d25-171">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="69d25-172">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="69d25-172">Related links</span></span>

[<span data-ttu-id="69d25-173">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="69d25-173">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)