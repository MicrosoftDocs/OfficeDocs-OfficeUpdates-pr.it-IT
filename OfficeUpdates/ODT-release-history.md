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
# <a name="release-history-for-office-deployment-tool"></a><span data-ttu-id="a552d-103">Cronologia delle versioni per lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="a552d-103">Release history for Office Deployment Tool</span></span>

<span data-ttu-id="a552d-104">Lo Strumento di distribuzione di Office (ODT) è uno strumento da riga di comando usato per scaricare e distribuire le versioni A portata di clic di Office, ad esempio Office 365 ProPlus, nei computer client.</span><span class="sxs-lookup"><span data-stu-id="a552d-104">The Office 2016 Deployment Tool (ODT) is a command-line tool that you can use to download and deploy Office 365 ProPlus to your client computers.</span></span> 


<span data-ttu-id="a552d-105">Lo strumento ODT consente un maggiore controllo sull'installazione di Office.</span><span class="sxs-lookup"><span data-stu-id="a552d-105">The ODT gives you more control over an Office installation.</span></span> <span data-ttu-id="a552d-106">È possibile specificare i prodotti e le lingue installati, la modalità di aggiornamento dei prodotti e se si vuole che l'esperienza di installazione sia visibile agli utenti.</span><span class="sxs-lookup"><span data-stu-id="a552d-106">The ODT gives you more control over an Office installation: you can define which products and languages are installed, how those products should be updated, and whether or not to display the install experience to your users.</span></span> <span data-ttu-id="a552d-107">Per altre informazioni sull'uso di ODT, vedere [Panoramica dello Strumento di distribuzione di Office](https://docs.microsoft.com/it-IT/deployoffice/overview-of-the-office-2016-deployment-tool).</span><span class="sxs-lookup"><span data-stu-id="a552d-107">For information on how to use the ODT, see the [Overview of the Office Deployment Tool](https://docs.microsoft.com/it-IT/deployoffice/overview-of-the-office-2016-deployment-tool).</span></span>

 <span data-ttu-id="a552d-108">**Sistema operativo supportato**: Windows 10, Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, Windows Server 2012 R2.</span><span class="sxs-lookup"><span data-stu-id="a552d-108">The tool runs on Windows 10 , Windows 7, Windows 8, Windows 8.1, Windows Server 2008 R2, Windows Server 2012, and Windows Server 2012 R2.</span></span> 
 
 <span data-ttu-id="a552d-109">**Istruzioni di installazione**: scaricare ed eseguire il file eseguibile autoestraente, che contiene il file eseguibile dello Strumento di distribuzione di Office (setup.exe) e un file di configurazione di esempio (configuration.xml).</span><span class="sxs-lookup"><span data-stu-id="a552d-109">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span> 

[<span data-ttu-id="a552d-110">Scaricare lo Strumento di distribuzione di Office</span><span class="sxs-lookup"><span data-stu-id="a552d-110">Download the Office Deployment Tool</span></span>](https://www.microsoft.com/en-us/download/confirmation.aspx?id=49117)


## <a name="july-10-2019"></a><span data-ttu-id="a552d-111">10 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="a552d-111">July 10, 2019</span></span>

<span data-ttu-id="a552d-112">Versione 16.0.11901.20022</span><span class="sxs-lookup"><span data-stu-id="a552d-112">Version 16.0.11901.20022</span></span>
- <span data-ttu-id="a552d-113">Aggiunta del supporto per altri prodotti se installato con Office 2019: Access Runtime, Skype for Business Basic.</span><span class="sxs-lookup"><span data-stu-id="a552d-113">Added support for additional products when installed with Office 2019: Access Runtime, Skype for Business Basic.</span></span>
- <span data-ttu-id="a552d-114">Aggiunta del supporto per l'installazione condizionale di prodotti autonomi durante l'aggiornamento da MSI.</span><span class="sxs-lookup"><span data-stu-id="a552d-114">Added support for conditional installation of standalone products when upgrading from MSI.</span></span>

## <a name="april-23-2019"></a><span data-ttu-id="a552d-115">23 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="a552d-115">April 23, 2019</span></span>

<span data-ttu-id="a552d-116">Versione 16.0.11617.33601</span><span class="sxs-lookup"><span data-stu-id="a552d-116">Version 16.0.11617.33601</span></span>
- <span data-ttu-id="a552d-117">Correzione di un bug con RemoveMSI=True per pulire le impostazioni del Registro di sistema correlate.</span><span class="sxs-lookup"><span data-stu-id="a552d-117">Fixed a bug with RemoveMSI=True to clean up related registry settings.</span></span>
- <span data-ttu-id="a552d-118">Aggiornamento dei codici di errore per fornire ulteriori dettagli per gli errori imprevisti (E_UNEXPECTED).</span><span class="sxs-lookup"><span data-stu-id="a552d-118">Updated error codes to provide additional detail for unexpected failures (E_UNEXPECTED).</span></span>

## <a name="april-16-2019"></a><span data-ttu-id="a552d-119">16 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="a552d-119">April 16, 2019</span></span>

<span data-ttu-id="a552d-120">Versione 16.0.11615.33602</span><span class="sxs-lookup"><span data-stu-id="a552d-120">Version 16.0.11615.33602</span></span>
- <span data-ttu-id="a552d-121">Supporto per l'aggiornamento da C2R a 32 bit a C2R a 64 bit con il nuovo attributo MigrateArch.</span><span class="sxs-lookup"><span data-stu-id="a552d-121">Support for upgrading 32-bit C2R to 64-bit C2R with new MigrateArch attribute.</span></span>
- <span data-ttu-id="a552d-122">Aggiornamento della logica per /configure che consente l'accesso ai file XML di configurazione archiviati in percorsi Web (http e https).</span><span class="sxs-lookup"><span data-stu-id="a552d-122">Updated logic for /configure that allows accessing configuration XML files stored in web locations (http and https).</span></span>
- <span data-ttu-id="a552d-123">Aggiunta del nuovo attributo MatchInstalled, che consente a ODT di mantenere la corrispondenza con la versione esistente quando si aggiungono altri prodotti o lingue.</span><span class="sxs-lookup"><span data-stu-id="a552d-123">MatchInstalled added as a new attribute which allows ODT to match the existing version when adding additional products or languages.</span></span>

## <a name="march-13-2019"></a><span data-ttu-id="a552d-124">13 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="a552d-124">March 13, 2019</span></span>

<span data-ttu-id="a552d-125">Versione 16.0.11509.33604</span><span class="sxs-lookup"><span data-stu-id="a552d-125">Version 16.0.11509.33604</span></span>
- <span data-ttu-id="a552d-126">Miglioramenti agli scenari di aggiornamento e migrazione.</span><span class="sxs-lookup"><span data-stu-id="a552d-126">Improvements to upgrade and migration scenarios.</span></span>

## <a name="january-14-2019"></a><span data-ttu-id="a552d-127">14 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="a552d-127">January 14, 2019</span></span>

<span data-ttu-id="a552d-128">Versione 16.0.11306.33602</span><span class="sxs-lookup"><span data-stu-id="a552d-128">Version 16.0.11306.33602</span></span>
- <span data-ttu-id="a552d-129">Miglioramenti alla registrazione e alla telemetria per la configurazione della distribuzione.</span><span class="sxs-lookup"><span data-stu-id="a552d-129">Improvements to logging and telemetry for deployment configuration.</span></span>


## <a name="related-links"></a><span data-ttu-id="a552d-130">Collegamenti correlati</span><span class="sxs-lookup"><span data-stu-id="a552d-130">Related links</span></span>

[<span data-ttu-id="a552d-131">Area download ODT</span><span class="sxs-lookup"><span data-stu-id="a552d-131">ODT Download Center</span></span>](https://www.microsoft.com/en-us/download/details.aspx?id=49117)