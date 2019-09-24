---
title: Problemi noti di Office 365 ProPlus
ms.author: andrewmo
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Sono disponibili informazioni sui problemi noti di Office 365 ProPlus
ms.openlocfilehash: a8b385e197a6f61c10797bf160101cdd70285aaf
ms.sourcegitcommit: a6d8dba3ee51727c2d3a2dad89cb986595c1a7b8
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/20/2019
ms.locfileid: "37068056"
---
# <a name="office-365-proplus-known-issues"></a><span data-ttu-id="1c4e5-103">Problemi noti di Office 365 ProPlus</span><span class="sxs-lookup"><span data-stu-id="1c4e5-103">Office 365 ProPlus Known Issues</span></span>

<span data-ttu-id="1c4e5-104">Questi problemi noti forniscono informazioni sugli aggiornamenti non della sicurezza inclusi negli aggiornamenti del Canale mensile, SACT e SAC per Office 365 ProPlus nel 2019, Visio Pro per Office 365, Project Online Desktop Client e Office 365 Business.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-104">These release notes provide information about new features and non-security updates that are included in Monthly Channel updates to Office 365 ProPlus in 2019, including Visio Pro for Office 365 and Project Online Desktop Client.</span></span>

<span data-ttu-id="1c4e5-105">Questa tabella offre un riepilogo dei problemi attuali attivi e dei problemi che sono stati risolti.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-105">This table offers a summary of current active issues and those issues that have been resolved.</span></span>  <span data-ttu-id="1c4e5-106">La tabella seguente verrà aggiornata con i problemi rilevanti che vengono esaminati.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-106">We will update the table below with significant issues we are investigating.</span></span>

 > [!NOTE]
 >- <span data-ttu-id="1c4e5-107">L'elenco non è completo.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-107">This list is not comprehensive.</span></span>

<br>

## <a name="september-2019"></a><span data-ttu-id="1c4e5-108">Settembre 2019</span><span class="sxs-lookup"><span data-stu-id="1c4e5-108">September 10, 2019</span></span>

|<span data-ttu-id="1c4e5-109">Riepilogo</span><span class="sxs-lookup"><span data-stu-id="1c4e5-109">Summary</span></span>|<span data-ttu-id="1c4e5-110">In analisi</span><span class="sxs-lookup"><span data-stu-id="1c4e5-110">Investigating</span></span>|<span data-ttu-id="1c4e5-111">Risolti</span><span class="sxs-lookup"><span data-stu-id="1c4e5-111">Resolved Property</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="1c4e5-112">**Outlook**</span><span class="sxs-lookup"><span data-stu-id="1c4e5-112">**Outlook**</span></span>
<span data-ttu-id="1c4e5-113">È stato rinvenuto un problema che poteva impedire il salvataggio di file in una posizione WebDAV.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-113">We found an issue which could have prevented files from being saved to a WebDAV location.</span></span>|<span data-ttu-id="1c4e5-114">Versione mensile 1909</span><span class="sxs-lookup"><span data-stu-id="1c4e5-114">Monthly Version 1909</span></span>||
|<span data-ttu-id="1c4e5-115">**Project**</span><span class="sxs-lookup"><span data-stu-id="1c4e5-115">**Project**</span></span>
<span data-ttu-id="1c4e5-116">Si prenda in considerazione il seguente scenario.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-116">Consider the following scenario.</span></span> <span data-ttu-id="1c4e5-117">Aprire un progetto.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-117">You open a project.</span></span> <span data-ttu-id="1c4e5-118">Fare clic sul menu File, poi su Esporta e ancora sul pulsante Crea PDF/XPS.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-118">You click the File menu, click Export and click the Create PDF/XPS button.</span></span> <span data-ttu-id="1c4e5-119">Nella finestra di dialogo Sfoglia si immette un nome file e fare clic su OK.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-119">Within the Browse dialog box, you enter a file name and click OK.</span></span> <span data-ttu-id="1c4e5-120">In questa situazione, si noterà che il file PDF di XPS non è stato creato.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-120">In this situation, you find that the PDF of XPS file is not created.</span></span> |<span data-ttu-id="1c4e5-121">Versione SAC 1902</span><span class="sxs-lookup"><span data-stu-id="1c4e5-121">SAC Version 1902</span></span>||
|<span data-ttu-id="1c4e5-122">**Word**</span><span class="sxs-lookup"><span data-stu-id="1c4e5-122">**Word**</span></span>
<span data-ttu-id="1c4e5-123">È stato rilevato un problema che poteva influire sull’apertura di un file da parte degli utenti.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-123">We found an issue users could hit on opening a file.</span></span>|<span data-ttu-id="1c4e5-124">Versione mensile 1908</span><span class="sxs-lookup"><span data-stu-id="1c4e5-124">Monthly Version 1908</span></span>||
<span data-ttu-id="1c4e5-125">Per i file di Office sincronizzati con il motore di sincronizzazione di OneDrive, i metadati del documento, come ad esempio i requisiti Richiedi proprietà e Tipo di contenuto, non vengono più convalidati al momento di fare clic su Salva e Salva con nome.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-125">For Office files synced by the OneDrive Sync Engine, document metadata such as Require Properties and Content Type requirements are no longer validated upon Save and Save As.</span></span>|<span data-ttu-id="1c4e5-126">Versione SAC 1902</span><span class="sxs-lookup"><span data-stu-id="1c4e5-126">SAC Version 1902</span></span>||

## <a name="may-2019---sample"></a><span data-ttu-id="1c4e5-127">Maggio 2019 - ESEMPIO</span><span class="sxs-lookup"><span data-stu-id="1c4e5-127">May 2019 - SAMPLE</span></span>

|<span data-ttu-id="1c4e5-128">Riepilogo</span><span class="sxs-lookup"><span data-stu-id="1c4e5-128">Summary</span></span>|<span data-ttu-id="1c4e5-129">In analisi</span><span class="sxs-lookup"><span data-stu-id="1c4e5-129">Investigating</span></span>|<span data-ttu-id="1c4e5-130">Risolti</span><span class="sxs-lookup"><span data-stu-id="1c4e5-130">Resolved Property</span></span>|
|:-------------------------------------------------------------------------------------|:-----|:-----|
|<span data-ttu-id="1c4e5-131">**Excel**</span><span class="sxs-lookup"><span data-stu-id="1c4e5-131">**Excel**</span></span>
<span data-ttu-id="1c4e5-132">Esempio risolto in più build -- È stato rilevato un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-132">Sample resoved in multiple builds -- We found an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>||<span data-ttu-id="1c4e5-133">Versione SAC 1902</span><span class="sxs-lookup"><span data-stu-id="1c4e5-133">SAC Version 1902</span></span> <br> <span data-ttu-id="1c4e5-134">(16.0.11328.20306)</span><span class="sxs-lookup"><span data-stu-id="1c4e5-134">(16.0.11328.20306)</span></span> <br> <span data-ttu-id="1c4e5-135">Versione mensile 1905</span><span class="sxs-lookup"><span data-stu-id="1c4e5-135">Monthly Version 1905</span></span> <br> <span data-ttu-id="1c4e5-136">(16.0.11629.20210)</span><span class="sxs-lookup"><span data-stu-id="1c4e5-136">(16.0.11629.20210)</span></span>|
|<span data-ttu-id="1c4e5-137">**Word**</span><span class="sxs-lookup"><span data-stu-id="1c4e5-137">**Word**</span></span>
<span data-ttu-id="1c4e5-138">Esempio risolto in alcune build, non in tutte -- È stato rilevato un problema con le prestazioni quando si attiva parti rapide per documento propertiesk.</span><span class="sxs-lookup"><span data-stu-id="1c4e5-138">Sample resoved in some builds, not all -- We found an issue with performance when enabling Quick Parts for Document propertiesk.</span></span>|<span data-ttu-id="1c4e5-139">Versione SAC 1808</span><span class="sxs-lookup"><span data-stu-id="1c4e5-139">SAC Version 1808</span></span>|<span data-ttu-id="1c4e5-140">Versione SAC 1902</span><span class="sxs-lookup"><span data-stu-id="1c4e5-140">SAC Version 1902</span></span> <br> <span data-ttu-id="1c4e5-141">(16.0.11328.20340)</span><span class="sxs-lookup"><span data-stu-id="1c4e5-141">(16.0.11328.20340)</span></span>|

<br>
<br>

> [!NOTE]
> <span data-ttu-id="1c4e5-142">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="1c4e5-142">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
