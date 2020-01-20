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
ms.openlocfilehash: fb59993362c4c186518f8472cb0330fa1b1e8d58
ms.sourcegitcommit: f042b25b15960fc4911a7e7d8500dcfd992ee95c
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 01/17/2020
ms.locfileid: "41230064"
---
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="23aa8-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="23aa8-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="23aa8-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Office 365 ProPlus, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="23aa8-104">The Office Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Click-to-Run versions of Office, such as Office 365 ProPlus, to your client computers.</span></span> 


<span data-ttu-id="23aa8-105">Lo strumento ODT consente un maggiore controllo sull'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="23aa8-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="23aa8-106">È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti.</span><span class="sxs-lookup"><span data-stu-id="23aa8-106">You can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="23aa8-107">Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="23aa8-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="23aa8-108">**Sistema operativo supportato**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="23aa8-108">**Supported Operating System**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2</span></span> 
 
 <span data-ttu-id="23aa8-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="23aa8-109">**Install Instructions**: Download and then run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="23aa8-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="23aa8-110">Download Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="january-16-2020"></a><span data-ttu-id="23aa8-111">16 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="23aa8-111">January 16, 2020</span></span>

<span data-ttu-id="23aa8-112">Versione 16.0.12325.20288</span><span class="sxs-lookup"><span data-stu-id="23aa8-112">Version 16.0.12325.20288</span></span>
- <span data-ttu-id="23aa8-113">Risolve un problema per cui l'interfaccia utente di istallazione di Office veniva visualizzata in una lingua non corretta in caso di installazione di più lingue</span><span class="sxs-lookup"><span data-stu-id="23aa8-113">Fixes an issue where Office installation UI may display in an incorrect language when multiple languages are installed</span></span>
- <span data-ttu-id="23aa8-114">Risolve un problema per cui si verificava un errore imprevisto al momento dell'installazione di alcuni pacchetti di strumenti di correzione durante l'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="23aa8-114">Fixes an issue where Office installation may unexpectedly fail when certain proofing tools packages are installed</span></span>
- <span data-ttu-id="23aa8-115">Aggiunge il supporto per controllare, in modo facoltativo, la distribuzione iniziale della [funzionalità Microsoft Search in Bing](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span><span class="sxs-lookup"><span data-stu-id="23aa8-115">Adds support to optionally control initial deployment of [Microsoft Search in Bing feature](https://go.microsoft.com/fwlink/p/?linkid=2109345)</span></span>


## <a name="october-31-2019"></a><span data-ttu-id="23aa8-116">31 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-116">October 31, 2019</span></span>

<span data-ttu-id="23aa8-117">Versione 16.0.12130.20272</span><span class="sxs-lookup"><span data-stu-id="23aa8-117">Version 16.0.12130.20272</span></span>
- <span data-ttu-id="23aa8-118">Risolve un problema per consentire l'installazione di Skype for Business Basic 2019 con prodotti con contratto multilicenza enterprise perpetua 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-118">Fixes an issue to allow Skype for Business Basic 2019 to install with 2019 perpetual enterprise volume licensed products</span></span>
- <span data-ttu-id="23aa8-119">Risolve un problema che può causare l'interruzione imprevista della modalità di download ODT in determinate circostanze quando viene usato un proxy</span><span class="sxs-lookup"><span data-stu-id="23aa8-119">Fixes an issue that may cause ODT download mode to fail unexpectedly in certain circumstances when a proxy is used</span></span>
- <span data-ttu-id="23aa8-120">Nuova funzionalità che consente il download nella modalità di download ODT tramite HTTP usando una porta diversa dalla porta 80</span><span class="sxs-lookup"><span data-stu-id="23aa8-120">New capability that allows ODT download mode to download via HTTP using a port other than port 80</span></span>


## <a name="july-10-2019"></a><span data-ttu-id="23aa8-121">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-121">July 10, 2019</span></span>

<span data-ttu-id="23aa8-122">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="23aa8-122">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="23aa8-123">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="23aa8-123">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="23aa8-124">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="23aa8-124">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="23aa8-125">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-125">April 23, 2019</span></span>

<span data-ttu-id="23aa8-126">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="23aa8-126">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="23aa8-127">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="23aa8-127">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="23aa8-128">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="23aa8-128">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="23aa8-129">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-129">April 16 2019</span></span>

<span data-ttu-id="23aa8-130">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="23aa8-130">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="23aa8-131">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="23aa8-131">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="23aa8-132">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="23aa8-132">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="23aa8-133">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="23aa8-133">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="23aa8-134">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-134">March 13, 2019</span></span>

<span data-ttu-id="23aa8-135">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="23aa8-135">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="23aa8-136">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="23aa8-136">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="23aa8-137">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="23aa8-137">January 14, 2019</span></span>

<span data-ttu-id="23aa8-138">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="23aa8-138">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="23aa8-139">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="23aa8-139">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="23aa8-140">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="23aa8-140">Related links</span></span>

[<span data-ttu-id="23aa8-141">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="23aa8-141">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)