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
ms.openlocfilehash: 125f37f1fb4b21d2d63784e51703c1297d928f49
ms.sourcegitcommit: c7f7982f4d2d0d8db4fc4fbf961b79a03bc8b36e
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 12/08/2020
ms.locfileid: "49601411"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="bbd39-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="bbd39-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="bbd39-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="bbd39-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="bbd39-105">Lo strumento ODT consente un maggiore controllo sull'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="bbd39-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="bbd39-106">È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti.</span><span class="sxs-lookup"><span data-stu-id="bbd39-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="bbd39-107">Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="bbd39-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="bbd39-108">**Sistema operativo supportato**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="bbd39-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="bbd39-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="bbd39-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="bbd39-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="bbd39-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="december-8-2020"></a><span data-ttu-id="bbd39-111">8 dicembre 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-111">December 8, 2020</span></span>
<span data-ttu-id="bbd39-112">Versione 16.0.13426.20308 (setup.exe versione 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="bbd39-112">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="bbd39-113">È stato risolto un problema per cui la modalità di download bloccava i download del canale perpetuo 2019 se il dispositivo aveva un prodotto Office installato da un canale non perpetuo 2019.</span><span class="sxs-lookup"><span data-stu-id="bbd39-113">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="bbd39-114">È stato risolto un problema per cui una migrazione dell'architettura non andava a buon fine rispetto a un'origine locale creata tramite una modalità di download che aveva specificato una versione esplicita nell'XML di configurazione.</span><span class="sxs-lookup"><span data-stu-id="bbd39-114">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="bbd39-115">23 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-115">November 23, 2020</span></span>
<span data-ttu-id="bbd39-116">Versione 16.0.13328.20420 (setup.exe versione 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="bbd39-116">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="bbd39-117">È stato risolto un problema per cui gli strumenti di correzione non venivano scaricati in /modalità download</span><span class="sxs-lookup"><span data-stu-id="bbd39-117">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="bbd39-118">È stato risolto un problema per cui la /modalità download non funzionava se eseguita in un contesto utente non elevato</span><span class="sxs-lookup"><span data-stu-id="bbd39-118">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="bbd39-119">È stato risolto un problema per cui la specifica di un attributo di Version nell'XML di configurazione causava un download incompleto in /modalità download</span><span class="sxs-lookup"><span data-stu-id="bbd39-119">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="bbd39-120">È stato risolto un problema per cui lo strumento di distribuzione di Office non era denominato "setup.exe" quando veniva estratto</span><span class="sxs-lookup"><span data-stu-id="bbd39-120">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="bbd39-121">È stato risolto un problema relativo alla priorità dell'origine dell'installazione quando viene fornito un attributo del canale nell'XML di configurazione</span><span class="sxs-lookup"><span data-stu-id="bbd39-121">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="bbd39-122">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-122">November 10, 2020</span></span>
<span data-ttu-id="bbd39-123">Versione 16.0.13328.20356 (setupODT.exe versione 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="bbd39-123">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="bbd39-124">Miglioramenti per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="bbd39-124">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="bbd39-125">Per evitare confusione e diagnosticare più facilmente errori di configurazione, lo Strumento di distribuzione di Office è ora denominato setupODT.exe per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="bbd39-125">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="bbd39-126">29 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-126">October 29, 2020</span></span>
<span data-ttu-id="bbd39-127">Versione 16.0.13328.20292 (setup.exe versione 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="bbd39-127">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="bbd39-128">Risolve un problema per cui alcuni prodotti di Office 2007 bloccavano in modo imprevisto l'installazione quando si usava RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="bbd39-128">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="bbd39-129">14 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-129">October 14, 2020</span></span>
<span data-ttu-id="bbd39-130">Versione 16.0.13231.20368 (setup.exe versione 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="bbd39-130">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="bbd39-131">Tutti i prodotti useranno ora Canale mensile per impostazione predefinita, se non viene specificato alcun canale</span><span class="sxs-lookup"><span data-stu-id="bbd39-131">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="bbd39-132">Sicurezza ottimizzata durante l'esecuzione di ODT da una directory che contiene altri DLL</span><span class="sxs-lookup"><span data-stu-id="bbd39-132">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="bbd39-133">Migliorie per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="bbd39-133">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="bbd39-134">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-134">June 9, 2020</span></span>

<span data-ttu-id="bbd39-135">Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="bbd39-135">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="bbd39-136">Il Canale corrente ora è il canale predefinito se non viene specificato un canale</span><span class="sxs-lookup"><span data-stu-id="bbd39-136">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="bbd39-137">Aggiunta del supporto per il Canale Enterprise mensile</span><span class="sxs-lookup"><span data-stu-id="bbd39-137">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="bbd39-138">Aggiunta del supporto per i nomi nuovi dei canali</span><span class="sxs-lookup"><span data-stu-id="bbd39-138">Added support for new channel names</span></span>
- <span data-ttu-id="bbd39-139">Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua</span><span class="sxs-lookup"><span data-stu-id="bbd39-139">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="bbd39-140">Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007</span><span class="sxs-lookup"><span data-stu-id="bbd39-140">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="bbd39-141">Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access</span><span class="sxs-lookup"><span data-stu-id="bbd39-141">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="bbd39-142">15 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-142">April 15, 2020</span></span>

<span data-ttu-id="bbd39-143">Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="bbd39-143">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="bbd39-144">Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7</span><span class="sxs-lookup"><span data-stu-id="bbd39-144">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="bbd39-145">Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto</span><span class="sxs-lookup"><span data-stu-id="bbd39-145">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="bbd39-146">Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto</span><span class="sxs-lookup"><span data-stu-id="bbd39-146">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="bbd39-147">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="bbd39-147">January 16, 2020</span></span>

<span data-ttu-id="bbd39-148">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="bbd39-148">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="bbd39-149">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="bbd39-149">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="bbd39-150">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="bbd39-150">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="bbd39-151">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="bbd39-151">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="bbd39-152">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-152">October 31, 2019</span></span>

<span data-ttu-id="bbd39-153">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="bbd39-153">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="bbd39-154">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-154">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="bbd39-155">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="bbd39-155">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="bbd39-156">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="bbd39-156">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="bbd39-157">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-157">July 10, 2019</span></span>

<span data-ttu-id="bbd39-158">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="bbd39-158">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="bbd39-159">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="bbd39-159">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="bbd39-160">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="bbd39-160">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="bbd39-161">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-161">April 23, 2019</span></span>

<span data-ttu-id="bbd39-162">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="bbd39-162">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="bbd39-163">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="bbd39-163">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="bbd39-164">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="bbd39-164">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="bbd39-165">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-165">April 16 2019</span></span>

<span data-ttu-id="bbd39-166">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="bbd39-166">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="bbd39-167">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="bbd39-167">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="bbd39-168">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="bbd39-168">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="bbd39-169">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="bbd39-169">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="bbd39-170">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-170">March 13, 2019</span></span>

<span data-ttu-id="bbd39-171">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="bbd39-171">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="bbd39-172">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="bbd39-172">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="bbd39-173">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="bbd39-173">January 14, 2019</span></span>

<span data-ttu-id="bbd39-174">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="bbd39-174">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="bbd39-175">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="bbd39-175">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="bbd39-176">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="bbd39-176">Related links</span></span>

[<span data-ttu-id="bbd39-177">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="bbd39-177">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)