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
ms.openlocfilehash: 4f65d41bfa18321a951fb18abcf919056bec7c5d
ms.sourcegitcommit: 57e715a8a3c0565b902cb3e6ca45d18a26f8ec45
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 10/15/2020
ms.locfileid: "48469995"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="e5471-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="e5471-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="e5471-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Microsoft 365 Apps, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="e5471-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Microsoft 365 Apps, to your client computers.</span></span> 


<span data-ttu-id="e5471-105">Lo strumento ODT consente un maggiore controllo sull'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="e5471-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="e5471-106">È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti.</span><span class="sxs-lookup"><span data-stu-id="e5471-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="e5471-107">Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="e5471-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="e5471-108">**Sistema operativo supportato**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span><span class="sxs-lookup"><span data-stu-id="e5471-108">**Supported Operating System**: Windows 10, Windows 8.1, Windows Server 2019, Windows Server 2016</span></span> 
 
 <span data-ttu-id="e5471-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="e5471-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="e5471-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="e5471-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)

## <a name="october-14-2020"></a><span data-ttu-id="e5471-111">14 ottobre 2020</span><span class="sxs-lookup"><span data-stu-id="e5471-111">October 14, 2020</span></span>
<span data-ttu-id="e5471-112">Versione 16.0.13231.20368 (setup.exe versione 16.0.13231.20350)</span><span class="sxs-lookup"><span data-stu-id="e5471-112">Version 16.0.13231.20368 (setup.exe version 16.0.13231.20350)</span></span>
- <span data-ttu-id="e5471-113">Tutti i prodotti useranno ora Canale mensile per impostazione predefinita, se non viene specificato alcun canale</span><span class="sxs-lookup"><span data-stu-id="e5471-113">All products will now use Monthly Channel by default when no channel is specified</span></span>
- <span data-ttu-id="e5471-114">Risolve un problema in cui alcuni prodotti di Office 2007 potrebbero bloccare in modo imprevisto l'installazione quando si usa RemoveMSI</span><span class="sxs-lookup"><span data-stu-id="e5471-114">Resolves an issue where certain Office 2007 products may unexpectedly block installation when using RemoveMSI</span></span>
- <span data-ttu-id="e5471-115">Sicurezza ottimizzata durante l'esecuzione di ODT da una directory che contiene altri DLL</span><span class="sxs-lookup"><span data-stu-id="e5471-115">Improved security when running ODT from a directory that contains other DLL’s</span></span>
- <span data-ttu-id="e5471-116">Migliorie per affidabilità e resilienza</span><span class="sxs-lookup"><span data-stu-id="e5471-116">Reliability and resiliency improvements</span></span>

## <a name="june-9-2020"></a><span data-ttu-id="e5471-117">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="e5471-117">June 9, 2020</span></span>

<span data-ttu-id="e5471-118">Versione 16.0.12827.20268 (setup.exe versione 16.0.12827.20258)</span><span class="sxs-lookup"><span data-stu-id="e5471-118">Version 16.0.12827.20268 (setup.exe version 16.0.12827.20258)</span></span>
- <span data-ttu-id="e5471-119">Il Canale corrente ora è il canale predefinito se non viene specificato un canale</span><span class="sxs-lookup"><span data-stu-id="e5471-119">Current Channel is now the default channel when a channel is not specified</span></span>
- <span data-ttu-id="e5471-120">Aggiunta del supporto per il Canale Enterprise mensile</span><span class="sxs-lookup"><span data-stu-id="e5471-120">Added support for Monthly Enterprise Channel</span></span>
- <span data-ttu-id="e5471-121">Aggiunta del supporto per i nomi nuovi dei canali</span><span class="sxs-lookup"><span data-stu-id="e5471-121">Added support for new channel names</span></span>
- <span data-ttu-id="e5471-122">Altre funzionalità di resilienza per continuare l'installazione, se possibile, anche se non sono disponibili risorse per la lingua</span><span class="sxs-lookup"><span data-stu-id="e5471-122">Additional resiliency features to continue install if possible even when some language resources are unavailable</span></span>
- <span data-ttu-id="e5471-123">Funzionalità RemoveMSI espanse per rimuovere i prodotti di Office 2007</span><span class="sxs-lookup"><span data-stu-id="e5471-123">MSIRemove capabilities expanded to remove Office 2007 products</span></span>
- <span data-ttu-id="e5471-124">Funzionalità RemoveMSI espanse per rimuovere il motore di database di Access</span><span class="sxs-lookup"><span data-stu-id="e5471-124">MSIRemove capabilities expanded to remove Access Database Engine</span></span> 

## <a name="april-15-2020"></a><span data-ttu-id="e5471-125">15 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="e5471-125">April 15, 2020</span></span>

<span data-ttu-id="e5471-126">Versione 16.0.12624.20320 (setup.exe versione 16.0.12624.20290)</span><span class="sxs-lookup"><span data-stu-id="e5471-126">Version 16.0.12624.20320 (setup.exe version 16.0.12624.20290)</span></span>
- <span data-ttu-id="e5471-127">Aggiunge il supporto per versioni di Office alla fine del ciclo di vita specifiche per Windows 7</span><span class="sxs-lookup"><span data-stu-id="e5471-127">Adds support for Windows 7-specific end of life Office versions</span></span>
- <span data-ttu-id="e5471-128">Risolve un problema per cui le impostazioni di personalizzazione potrebbero non essere applicate come previsto</span><span class="sxs-lookup"><span data-stu-id="e5471-128">Fixes an issue where customization settings may not be applied as expected</span></span>
- <span data-ttu-id="e5471-129">Risolve un problema per cui i file CAT estranei possono essere scaricati in modo imprevisto</span><span class="sxs-lookup"><span data-stu-id="e5471-129">Fixes an issue where extraneous .cat files may be downloaded unexpectedly</span></span>

## <a name="january-16-2020"></a><span data-ttu-id="e5471-130">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="e5471-130">January 16, 2020</span></span>

<span data-ttu-id="e5471-131">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="e5471-131">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="e5471-132">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="e5471-132">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="e5471-133">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="e5471-133">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="e5471-134">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="e5471-134">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="e5471-135">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-135">October 31, 2019</span></span>

<span data-ttu-id="e5471-136">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="e5471-136">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="e5471-137">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-137">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="e5471-138">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="e5471-138">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="e5471-139">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="e5471-139">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="e5471-140">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-140">July 10, 2019</span></span>

<span data-ttu-id="e5471-141">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="e5471-141">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="e5471-142">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="e5471-142">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="e5471-143">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="e5471-143">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="e5471-144">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-144">April 23, 2019</span></span>

<span data-ttu-id="e5471-145">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="e5471-145">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="e5471-146">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="e5471-146">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="e5471-147">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="e5471-147">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="e5471-148">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-148">April 16 2019</span></span>

<span data-ttu-id="e5471-149">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="e5471-149">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="e5471-150">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="e5471-150">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="e5471-151">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="e5471-151">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="e5471-152">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="e5471-152">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="e5471-153">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-153">March 13, 2019</span></span>

<span data-ttu-id="e5471-154">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="e5471-154">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="e5471-155">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="e5471-155">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="e5471-156">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="e5471-156">January 14, 2019</span></span>

<span data-ttu-id="e5471-157">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="e5471-157">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="e5471-158">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="e5471-158">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="e5471-159">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="e5471-159">Related links</span></span>

[<span data-ttu-id="e5471-160">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="e5471-160">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)