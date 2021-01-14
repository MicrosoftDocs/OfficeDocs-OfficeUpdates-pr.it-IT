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
ms.openlocfilehash: b9a5966e49653a4998a0cb3f3858decbe6f820c6
ms.sourcegitcommit: e7891ceed915afd2ae74689a366cebf9b3f60614
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 01/12/2021
ms.locfileid: "49837367"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="9d5b7-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="9d5b7-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="9d5b7-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="9d5b7-105">Lo strumento ODT consente un maggiore controllo sull'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="9d5b7-106">È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="9d5b7-107">Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="9d5b7-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="9d5b7-108">**Sistema operativo supportato**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="9d5b7-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="9d5b7-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="9d5b7-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="9d5b7-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="9d5b7-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="january-12-2021"></a><span data-ttu-id="9d5b7-111">12 gennaio 2021</span><span class="sxs-lookup"><span data-stu-id="9d5b7-111">January 12, 2021</span></span>
<span data-ttu-id="9d5b7-112">Versione 16.0.13530.20376 (setup.exe versione 16.0.13530.20334)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-112">Version 16.0.13530.20376 (setup.exe version 16.0.13530.20334)</span></span>
- <span data-ttu-id="9d5b7-113">È stato risolto un problema che causava il mancato funzionamento di RemoveMSI durante la registrazione di prodotti corrotti o non ordinari</span><span class="sxs-lookup"><span data-stu-id="9d5b7-113">Fixed an issue where corrupted or non-standard product registration could cause RemoveMSI operations to fail</span></span>

## <a name="december-21-2020"></a><span data-ttu-id="9d5b7-114">21 dicembre 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-114">December 21, 2020</span></span>
<span data-ttu-id="9d5b7-115">Versione 16.0.13426.20370 (setup.exe versione 16.0.13426.20352)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-115">Version 16.0.13426.20370 (setup.exe version 16.0.13426.20352)</span></span>
- <span data-ttu-id="9d5b7-116">È stato risolto un problema per cui le installazioni di origine locali di ProofingTools dal canale PerpetualVL2019 non riuscivano</span><span class="sxs-lookup"><span data-stu-id="9d5b7-116">Fixed an issue where local source installations of ProofingTools from the PerpetualVL2019 channel were failing</span></span>
- <span data-ttu-id="9d5b7-117">È stato risolto un problema per garantire che il client a portata di clic tenti un aggiornamento automatico quando si aggiungono altri prodotti in lingue di Office non complete a un'installazione esistente</span><span class="sxs-lookup"><span data-stu-id="9d5b7-117">Fixed an issue to ensure that the Click-To-Run client attempts a self-update when adding additional products in non-full Office languages to an existing installation</span></span>


## <a name="december-8-2020"></a><span data-ttu-id="9d5b7-118">8 dicembre 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-118">December 8, 2020</span></span>
<span data-ttu-id="9d5b7-119">Versione 16.0.13426.20308 (setup.exe versione 16.0.13426.20308)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-119">Version 16.0.13426.20308 (setup.exe version 16.0.13426.20308)</span></span>
- <span data-ttu-id="9d5b7-120">È stato risolto un problema per cui la modalità di download bloccava i download del canale perpetuo 2019 se il dispositivo aveva un prodotto Office installato da un canale non perpetuo 2019.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-120">Fixed an issue where Download mode was blocking Perpetual 2019 channel downloads if the device had an Office product installed from a non-Perpetual 2019 channel.</span></span>
- <span data-ttu-id="9d5b7-121">È stato risolto un problema per cui una migrazione dell'architettura non andava a buon fine rispetto a un'origine locale creata tramite una modalità di download che aveva specificato una versione esplicita nell'XML di configurazione.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-121">Fixed an issue where an Architecture Migration would fail against a local source created through Download mode that had specified an explicit Version in the configuration XML.</span></span>


## <a name="november-23-2020"></a><span data-ttu-id="9d5b7-122">23 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-122">November 23, 2020</span></span>
<span data-ttu-id="9d5b7-123">Versione 16.0.13328.20420 (setup.exe versione 16.0.13328.20420)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-123">Version 16.0.13328.20420 (setup.exe version 16.0.13328.20420)</span></span>
- <span data-ttu-id="9d5b7-124">È stato risolto un problema per cui gli strumenti di correzione non venivano scaricati in /modalità download</span><span class="sxs-lookup"><span data-stu-id="9d5b7-124">Fixed an issue where proofing tools were not being downloaded by /download mode</span></span>
- <span data-ttu-id="9d5b7-125">È stato risolto un problema per cui la /modalità download non funzionava se eseguita in un contesto utente non elevato</span><span class="sxs-lookup"><span data-stu-id="9d5b7-125">Fixed an issue where /download mode was failing when run in unelevated user context</span></span>
- <span data-ttu-id="9d5b7-126">È stato risolto un problema per cui la specifica di un attributo di Version nell'XML di configurazione causava un download incompleto in /modalità download</span><span class="sxs-lookup"><span data-stu-id="9d5b7-126">Fixed an issue where specifying a Version attribute in configuration XML resulted in an incomplete download in /download mode</span></span>
- <span data-ttu-id="9d5b7-127">È stato risolto un problema per cui lo strumento di distribuzione di Office non era denominato "setup.exe" quando veniva estratto</span><span class="sxs-lookup"><span data-stu-id="9d5b7-127">Fixed an issue where the Office Deployment Tool was not named “setup.exe” when extracted</span></span>
- <span data-ttu-id="9d5b7-128">È stato risolto un problema relativo alla priorità dell'origine dell'installazione quando viene fornito un attributo del canale nell'XML di configurazione</span><span class="sxs-lookup"><span data-stu-id="9d5b7-128">Fixed an issue regarding installation source prioritization when a Channel attribute is provided in configuration XML</span></span>

## <a name="november-10-2020"></a><span data-ttu-id="9d5b7-129">10 novembre 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-129">November 10, 2020</span></span>
<span data-ttu-id="9d5b7-130">Versione 16.0.13328.20356 (setupODT.exe versione 16.0.13328.20336)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-130">Version 16.0.13328.20356 (setupODT.exe version 16.0.13328.20336)</span></span>
- <span data-ttu-id="9d5b7-131">Miglioramenti per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="9d5b7-131">Reliability and resiliency improvements</span></span>
- <span data-ttu-id="9d5b7-132">Per evitare confusione e diagnosticare più facilmente errori di configurazione, lo Strumento di distribuzione di Office è ora denominato setupODT.exe per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-132">To prevent confusion and more easily diagnose setup errors, the ODT is now named setupODT.exe by default</span></span>

## <a name="october-29-2020"></a><span data-ttu-id="9d5b7-133">29 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-133">October 29, 2020</span></span>
<span data-ttu-id="9d5b7-134">Versione 16.0.13328.20292 (setup.exe versione 16.0.13328.20290)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-134">Version 16.0.13328.20292 (setup.exe version 16.0.13328.20290)</span></span>
- <span data-ttu-id="9d5b7-135">Risolve un problema per cui alcuni prodotti di Office 2007 bloccavano in modo imprevisto l'installazione quando si usava RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="9d5b7-135">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>

## <a name="october-14-2020"></a><span data-ttu-id="9d5b7-136">14 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-136">October 14, 2020</span></span>
<span data-ttu-id="9d5b7-137">Versione 16.0.13231.20368 (setup.exe versione 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-137">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="9d5b7-138">Tutti i prodotti useranno ora Canale mensile per impostazione predefinita, se non viene specificato alcun canale</span><span class="sxs-lookup"><span data-stu-id="9d5b7-138">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="9d5b7-139">Sicurezza ottimizzata durante l'esecuzione di ODT da una directory che contiene altri DLL</span><span class="sxs-lookup"><span data-stu-id="9d5b7-139">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="9d5b7-140">Migliorie per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="9d5b7-140">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="9d5b7-141">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-141">June 9, 2020</span></span>

<span data-ttu-id="9d5b7-142">Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-142">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="9d5b7-143">Il Canale corrente ora è il canale predefinito se non viene specificato un canale</span><span class="sxs-lookup"><span data-stu-id="9d5b7-143">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="9d5b7-144">Aggiunta del supporto per il Canale Enterprise mensile</span><span class="sxs-lookup"><span data-stu-id="9d5b7-144">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="9d5b7-145">Aggiunta del supporto per i nomi nuovi dei canali</span><span class="sxs-lookup"><span data-stu-id="9d5b7-145">Added support for new channel names</span></span>
- <span data-ttu-id="9d5b7-146">Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua</span><span class="sxs-lookup"><span data-stu-id="9d5b7-146">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="9d5b7-147">Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007</span><span class="sxs-lookup"><span data-stu-id="9d5b7-147">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="9d5b7-148">Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access</span><span class="sxs-lookup"><span data-stu-id="9d5b7-148">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="9d5b7-149">15 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-149">April 15, 2020</span></span>

<span data-ttu-id="9d5b7-150">Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-150">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="9d5b7-151">Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7</span><span class="sxs-lookup"><span data-stu-id="9d5b7-151">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="9d5b7-152">Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto</span><span class="sxs-lookup"><span data-stu-id="9d5b7-152">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="9d5b7-153">Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto</span><span class="sxs-lookup"><span data-stu-id="9d5b7-153">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="9d5b7-154">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="9d5b7-154">January 16, 2020</span></span>

<span data-ttu-id="9d5b7-155">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="9d5b7-155">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="9d5b7-156">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="9d5b7-156">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="9d5b7-157">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-157">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="9d5b7-158">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="9d5b7-158">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="9d5b7-159">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-159">October 31, 2019</span></span>

<span data-ttu-id="9d5b7-160">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="9d5b7-160">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="9d5b7-161">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-161">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="9d5b7-162">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="9d5b7-162">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="9d5b7-163">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="9d5b7-163">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="9d5b7-164">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-164">July 10, 2019</span></span>

<span data-ttu-id="9d5b7-165">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="9d5b7-165">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="9d5b7-166">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-166">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="9d5b7-167">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-167">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="9d5b7-168">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-168">April 23, 2019</span></span>

<span data-ttu-id="9d5b7-169">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="9d5b7-169">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="9d5b7-170">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-170">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="9d5b7-171">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="9d5b7-171">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="9d5b7-172">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-172">April 16 2019</span></span>

<span data-ttu-id="9d5b7-173">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="9d5b7-173">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="9d5b7-174">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-174">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="9d5b7-175">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="9d5b7-175">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="9d5b7-176">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-176">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="9d5b7-177">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-177">March 13, 2019</span></span>

<span data-ttu-id="9d5b7-178">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="9d5b7-178">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="9d5b7-179">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-179">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="9d5b7-180">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="9d5b7-180">January 14, 2019</span></span>

<span data-ttu-id="9d5b7-181">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="9d5b7-181">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="9d5b7-182">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="9d5b7-182">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="9d5b7-183">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="9d5b7-183">Related links</span></span>

[<span data-ttu-id="9d5b7-184">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="9d5b7-184">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)