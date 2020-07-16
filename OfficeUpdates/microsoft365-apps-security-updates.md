---
title: Note sulla versione per gli aggiornamenti di sicurezza di Microsoft 365 Apps
ms.author: andrewmo
author: TimDavenport
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulla versione per gli aggiornamenti di sicurezza di Microsoft 365 Apps
ms.openlocfilehash: 58228af0a7958547331b95c28c6497b5bfa3f460
ms.sourcegitcommit: 9fba85e39543d5fa71669437ad88913c574c4371
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 07/15/2020
ms.locfileid: "45138522"
---
# <a name="release-notes-for-microsoft-365-apps-security-updates"></a><span data-ttu-id="e567b-103">Note sulla versione per gli aggiornamenti di sicurezza di Microsoft 365 Apps</span><span class="sxs-lookup"><span data-stu-id="e567b-103">Release notes for Microsoft 365 Apps Security Updates</span></span>

<span data-ttu-id="e567b-104">Queste note sulla versione forniscono informazioni sulle correzioni per la sicurezza incluse negli aggiornamenti a Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="e567b-104">These release notes provide information about security fixes that are included in updates to Microsoft 365 Apps.</span></span>

<span data-ttu-id="e567b-105">Queste informazioni sono valide per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e le versioni in abbonamento delle app desktop di Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="e567b-105">This information applies to Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!IMPORTANT]
> - <span data-ttu-id="e567b-106">Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Monthly Enterprise Channel) e la modifica dei nomi dei canali di aggiornamento già presenti.</span><span class="sxs-lookup"><span data-stu-id="e567b-106">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="e567b-107">Leggere [questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441) per altre informazioni.</span><span class="sxs-lookup"><span data-stu-id="e567b-107">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>
> - <span data-ttu-id="e567b-108">Office 365 ProPlus è stato rinominato Microsoft 365 Apps for enterprise a partire dalla versione 2004.</span><span class="sxs-lookup"><span data-stu-id="e567b-108">Office 365 ProPlus is being renamed to Microsoft 365 Apps for enterprise, starting with Version 2004.</span></span><span data-ttu-id="e567b-109">Leggere  [questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2123420) per altre informazioni.</span><span class="sxs-lookup"><span data-stu-id="e567b-109"> To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2123420).</span></span><span data-ttu-id="e567b-110">Nella nostra documentazione, in genere è sufficiente fare riferimento a Microsoft 365 Apps.</span><span class="sxs-lookup"><span data-stu-id="e567b-110"> In our documentation, we'll usually just refer to it as Microsoft 365 Apps.</span></span>


 

[//]: # (NON ELIMINARE LA RIGA SOPRA, viene usata per la spaziatura)  

## <a name="july-14-2020"></a><span data-ttu-id="e567b-112">14 luglio 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-112">July 14, 2020</span></span>
<span data-ttu-id="e567b-113">Canale corrente: versione 2006 (Build 13001.20384)</span><span class="sxs-lookup"><span data-stu-id="e567b-113">Current Channel: Version 2006 (Build 13001.20384)</span></span>  
<span data-ttu-id="e567b-114">Canale Enterprise mensile: versione 2005 (Build 12827.20538)</span><span class="sxs-lookup"><span data-stu-id="e567b-114">Monthly Enterprise Channel: Version 2005 (Build 12827.20538)</span></span>  
<span data-ttu-id="e567b-115">Canale Enterprise mensile: versione 2004 (Build 12730.20602)</span><span class="sxs-lookup"><span data-stu-id="e567b-115">Monthly Enterprise Channel: Version 2004 (Build 12730.20602)</span></span>  
<span data-ttu-id="e567b-116">Canale Enterprise semestrale (Anteprima): versione 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="e567b-116">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="e567b-117">Canale Enterprise semestrale: versione 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="e567b-117">Semi-Annual Enterprise Channel: Version 2002 (Build 12527.20880)</span></span>  
<span data-ttu-id="e567b-118">Canale Enterprise semestrale: versione 1908 (Build 11929.20904)</span><span class="sxs-lookup"><span data-stu-id="e567b-118">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20904)</span></span>  
<span data-ttu-id="e567b-119">Canale Enterprise semestrale: Versione 1902 (Build 11328.20624)</span><span class="sxs-lookup"><span data-stu-id="e567b-119">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20624)</span></span>  
<span data-ttu-id="e567b-120">Microsoft 365 Apps su Windows 7: versione 2002 (Build 12527.20880)</span><span class="sxs-lookup"><span data-stu-id="e567b-120">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20880)</span></span>  

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT START)


### <a name="excel"></a><span data-ttu-id="e567b-122">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-122">Excel</span></span>

-   [<span data-ttu-id="e567b-123">CVE-2020-1240</span><span class="sxs-lookup"><span data-stu-id="e567b-123">CVE-2020-1240</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1240)


### <a name="outlook"></a><span data-ttu-id="e567b-124">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-124">Outlook</span></span>

-   [<span data-ttu-id="e567b-125">CVE-2020-1349</span><span class="sxs-lookup"><span data-stu-id="e567b-125">CVE-2020-1349</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1349)

### <a name="project"></a><span data-ttu-id="e567b-126">Project</span><span class="sxs-lookup"><span data-stu-id="e567b-126">Project</span></span>

-   [<span data-ttu-id="e567b-127">CVE-2020-1449</span><span class="sxs-lookup"><span data-stu-id="e567b-127">CVE-2020-1449</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1449)

### <a name="word"></a><span data-ttu-id="e567b-128">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-128">Word</span></span>

-   [<span data-ttu-id="e567b-129">CVE-2020-1445</span><span class="sxs-lookup"><span data-stu-id="e567b-129">CVE-2020-1445</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1445)
-   [<span data-ttu-id="e567b-130">CVE-2020-1342</span><span class="sxs-lookup"><span data-stu-id="e567b-130">CVE-2020-1342</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1342)
-   [<span data-ttu-id="e567b-131">CVE-2020-1447</span><span class="sxs-lookup"><span data-stu-id="e567b-131">CVE-2020-1447</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1447)
-   [<span data-ttu-id="e567b-132">CVE-2020-1446</span><span class="sxs-lookup"><span data-stu-id="e567b-132">CVE-2020-1446</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1446)

### <a name="office-suite"></a><span data-ttu-id="e567b-133">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="e567b-133">Office Suite</span></span>

-   [<span data-ttu-id="e567b-134">CVE-2020-1458</span><span class="sxs-lookup"><span data-stu-id="e567b-134">CVE-2020-1458</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1458)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="june-09-2020"></a><span data-ttu-id="e567b-136">9 giugno 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-136">June 09, 2020</span></span>
<span data-ttu-id="e567b-137">Canale corrente: versione 2005 (Build 12827.20336)</span><span class="sxs-lookup"><span data-stu-id="e567b-137">Current Channel: Version 2005 (Build 12827.20336)</span></span>  
<span data-ttu-id="e567b-138">Canale Enterprise mensile: versione 2004 (Build 12730.20430)</span><span class="sxs-lookup"><span data-stu-id="e567b-138">Monthly Enterprise Channel: Version 2004 (Build 12730.20430)</span></span>  
<span data-ttu-id="e567b-139">Canale Enterprise mensile: versione 2003 (Build 12624.20708)</span><span class="sxs-lookup"><span data-stu-id="e567b-139">Monthly Enterprise Channel: Version 2003 (Build 12624.20708)</span></span>  
<span data-ttu-id="e567b-140">Canale Enterprise semestrale (Anteprima): versione 2002 (Build 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="e567b-140">Semi-Annual Enterprise Channel (Preview): Version 2002 (Build 12527.20720)</span></span>  
<span data-ttu-id="e567b-141">Canale Enterprise semestrale: Versione 1908 (Build 11929.20838)</span><span class="sxs-lookup"><span data-stu-id="e567b-141">Semi-Annual Enterprise Channel: Version 1908 (Build 11929.20838)</span></span>  
<span data-ttu-id="e567b-142">Canale Enterprise semestrale: Versione 1902 (Build 11328.20602)</span><span class="sxs-lookup"><span data-stu-id="e567b-142">Semi-Annual Enterprise Channel: Version 1902 (Build 11328.20602)</span></span>  
<span data-ttu-id="e567b-143">Microsoft 365 Apps su Windows 7: versione 2002 (Build 12527.20720)</span><span class="sxs-lookup"><span data-stu-id="e567b-143">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20720)</span></span>  

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT START)


### <a name="excel"></a><span data-ttu-id="e567b-145">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-145">Excel</span></span>

-   [<span data-ttu-id="e567b-146">CVE-2020-1226</span><span class="sxs-lookup"><span data-stu-id="e567b-146">CVE-2020-1226</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1226)
-   [<span data-ttu-id="e567b-147">CVE-2020-1225</span><span class="sxs-lookup"><span data-stu-id="e567b-147">CVE-2020-1225</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1225)

### <a name="outlook"></a><span data-ttu-id="e567b-148">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-148">Outlook</span></span>

-   [<span data-ttu-id="e567b-149">CVE-2020-1229</span><span class="sxs-lookup"><span data-stu-id="e567b-149">CVE-2020-1229</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1229)

### <a name="project"></a><span data-ttu-id="e567b-150">Project</span><span class="sxs-lookup"><span data-stu-id="e567b-150">Project</span></span>

-   [<span data-ttu-id="e567b-151">CVE-2020-1322</span><span class="sxs-lookup"><span data-stu-id="e567b-151">CVE-2020-1322</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1322)

### <a name="office-suite"></a><span data-ttu-id="e567b-152">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="e567b-152">Office Suite</span></span>

-   [<span data-ttu-id="e567b-153">CVE-2020-1321</span><span class="sxs-lookup"><span data-stu-id="e567b-153">CVE-2020-1321</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-1321)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="may-12-2020"></a><span data-ttu-id="e567b-155">12 maggio 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-155">May 12, 2020</span></span>
<span data-ttu-id="e567b-156">Canale mensile: versione 2004 (Build 12730.20270)</span><span class="sxs-lookup"><span data-stu-id="e567b-156">Monthly Channel: Version 2004 (Build 12730.20270)</span></span>  
<span data-ttu-id="e567b-157">Canale Enterprise mensile: versione 2003 (Build 12624.20588)</span><span class="sxs-lookup"><span data-stu-id="e567b-157">Monthly Enterprise Channel: Version 2003 (Build 12624.20588)</span></span>  
<span data-ttu-id="e567b-158">Canale semestrale (mirato): versione 2002 (Build 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="e567b-158">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20612)</span></span>  
<span data-ttu-id="e567b-159">Canale semestrale: versione 1908 (Build 11929.20776)</span><span class="sxs-lookup"><span data-stu-id="e567b-159">Semi-Annual Channel: Version 1908 (Build 11929.20776)</span></span>  
<span data-ttu-id="e567b-160">Canale semestrale: versione 1902 (Build 11328.20586)</span><span class="sxs-lookup"><span data-stu-id="e567b-160">Semi-Annual Channel: Version 1902 (Build 11328.20586)</span></span>  
<span data-ttu-id="e567b-161">Microsoft 365 Apps in Windows 7: versione 2002 (Build 12527.20612)</span><span class="sxs-lookup"><span data-stu-id="e567b-161">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20612)</span></span>  

[//]: # (NON RIMUOVERE INIZIO CONTENUTO CON DETTAGLI SULLA SICUREZZA)


### <a name="excel"></a><span data-ttu-id="e567b-163">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-163">Excel</span></span>

-   [<span data-ttu-id="e567b-164">CVE-2020-0901</span><span class="sxs-lookup"><span data-stu-id="e567b-164">CVE-2020-0901</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0901)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="april-14-2020"></a><span data-ttu-id="e567b-166">14 aprile 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-166">April 14, 2020</span></span>
<span data-ttu-id="e567b-167">Canale mensile: versione 2003 (Build 12624.20442)</span><span class="sxs-lookup"><span data-stu-id="e567b-167">Monthly Channel: Version 2003 (Build 12624.20442)</span></span>  
<span data-ttu-id="e567b-168">Canale semestrale (mirato): versione 2002 (Build 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="e567b-168">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20442)</span></span>  
<span data-ttu-id="e567b-169">Canale semestrale: versione 1908 (Build 11929.20708)</span><span class="sxs-lookup"><span data-stu-id="e567b-169">Semi-Annual Channel: Version 1908 (Build 11929.20708)</span></span>  
<span data-ttu-id="e567b-170">Canale semestrale: versione 1902 (Build 11328.20564)</span><span class="sxs-lookup"><span data-stu-id="e567b-170">Semi-Annual Channel: Version 1902 (Build 11328.20564)</span></span>  
<span data-ttu-id="e567b-171">Microsoft 365 Apps in Windows 7: versione 2002 (Build 12527.20442)</span><span class="sxs-lookup"><span data-stu-id="e567b-171">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20442)</span></span>  

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


### <a name="excel"></a><span data-ttu-id="e567b-173">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-173">Excel</span></span>

-   [<span data-ttu-id="e567b-174">CVE-2020-0906</span><span class="sxs-lookup"><span data-stu-id="e567b-174">CVE-2020-0906</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0906)
-   [<span data-ttu-id="e567b-175">CVE-2020-0979</span><span class="sxs-lookup"><span data-stu-id="e567b-175">CVE-2020-0979</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0979)

### <a name="word"></a><span data-ttu-id="e567b-176">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-176">Word</span></span>

-   [<span data-ttu-id="e567b-177">CVE-2020-0980</span><span class="sxs-lookup"><span data-stu-id="e567b-177">CVE-2020-0980</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0980)

### <a name="office-suite"></a><span data-ttu-id="e567b-178">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-178">Office Suite</span></span>

-   [<span data-ttu-id="e567b-179">CVE-2020-0760</span><span class="sxs-lookup"><span data-stu-id="e567b-179">CVE-2020-0760</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0760)
-   [<span data-ttu-id="e567b-180">CVE-2020-0991</span><span class="sxs-lookup"><span data-stu-id="e567b-180">CVE-2020-0991</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0991)
-   [<span data-ttu-id="e567b-181">CVE-2020-0961</span><span class="sxs-lookup"><span data-stu-id="e567b-181">CVE-2020-0961</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0961)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="march-10-2020"></a><span data-ttu-id="e567b-183">10 marzo 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-183">March 10, 2020</span></span>
<span data-ttu-id="e567b-184">Canale mensile: versione 2002 (Build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="e567b-184">Monthly Channel: Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="e567b-185">Canale semestrale (mirato): versione 2002 (Build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="e567b-185">Semi-Annual Channel (Targeted): Version 2002 (Build 12527.20278)</span></span>  
<span data-ttu-id="e567b-186">Canale semestrale: versione 1908 (Build 11929.20648)</span><span class="sxs-lookup"><span data-stu-id="e567b-186">Semi-Annual Channel: Version 1908 (Build 11929.20648)</span></span>  
<span data-ttu-id="e567b-187">Canale semestrale: versione 1902 (Build 11328.20554)</span><span class="sxs-lookup"><span data-stu-id="e567b-187">Semi-Annual Channel: Version 1902 (Build 11328.20554)</span></span>  
<span data-ttu-id="e567b-188">Microsoft 365 Apps in Windows 7: versione 2002 (Build 12527.20278)</span><span class="sxs-lookup"><span data-stu-id="e567b-188">Microsoft 365 Apps on Windows 7: Version 2002 (Build 12527.20278)</span></span>  

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



### <a name="word"></a><span data-ttu-id="e567b-190">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-190">Word</span></span>

-   [<span data-ttu-id="e567b-191">CVE-2020-0850</span><span class="sxs-lookup"><span data-stu-id="e567b-191">CVE-2020-0850</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0850)
-   [<span data-ttu-id="e567b-192">CVE-2020-0892</span><span class="sxs-lookup"><span data-stu-id="e567b-192">CVE-2020-0892</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0892)
-   [<span data-ttu-id="e567b-193">CVE-2020-0855</span><span class="sxs-lookup"><span data-stu-id="e567b-193">CVE-2020-0855</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0855)
-   [<span data-ttu-id="e567b-194">CVE-2020-0851</span><span class="sxs-lookup"><span data-stu-id="e567b-194">CVE-2020-0851</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0851)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="february-11-2020"></a><span data-ttu-id="e567b-196">11 febbraio 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-196">February 11, 2020</span></span>
<span data-ttu-id="e567b-197">Canale mensile: versione 2001 (Build 12430.20264)</span><span class="sxs-lookup"><span data-stu-id="e567b-197">Monthly Channel: Version 2001 (Build 12430.20264)</span></span>  
<span data-ttu-id="e567b-198">Canale semestrale (mirato): versione 1908 (Build 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="e567b-198">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="e567b-199">Canale semestrale: Versione 1908 (Build 11929.20606)</span><span class="sxs-lookup"><span data-stu-id="e567b-199">Semi-Annual Channel: Version 1908 (Build 11929.20606)</span></span>  
<span data-ttu-id="e567b-200">Canale semestrale: Versione 1902 (Build 11328.20526)</span><span class="sxs-lookup"><span data-stu-id="e567b-200">Semi-Annual Channel: Version 1902 (Build 11328.20526)</span></span>  
<span data-ttu-id="e567b-201">Canale semestrale: Versione 1808 (Build 10730.20438)</span><span class="sxs-lookup"><span data-stu-id="e567b-201">Semi-Annual Channel: Version 1808 (Build 10730.20438)</span></span>  

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


### <a name="excel"></a><span data-ttu-id="e567b-203">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-203">Excel</span></span>

-   [<span data-ttu-id="e567b-204">CVE-2020-0759</span><span class="sxs-lookup"><span data-stu-id="e567b-204">CVE-2020-0759</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0759)

### <a name="outlook"></a><span data-ttu-id="e567b-205">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-205">Outlook</span></span>

-   [<span data-ttu-id="e567b-206">CVE-2020-0696</span><span class="sxs-lookup"><span data-stu-id="e567b-206">CVE-2020-0696</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0696)

### <a name="office-suite"></a><span data-ttu-id="e567b-207">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-207">Office Suite</span></span>

-   [<span data-ttu-id="e567b-208">CVE-2020-0697</span><span class="sxs-lookup"><span data-stu-id="e567b-208">CVE-2020-0697</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0697)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="january-14-2020"></a><span data-ttu-id="e567b-210">14 gennaio 2020</span><span class="sxs-lookup"><span data-stu-id="e567b-210">January 14, 2020</span></span>
<span data-ttu-id="e567b-211">Canale mensile: versione 1912 (Build 12325.20298)</span><span class="sxs-lookup"><span data-stu-id="e567b-211">Monthly Channel: Version 1912 (Build 12325.20298)</span></span>  
<span data-ttu-id="e567b-212">Canale semestrale (mirato): versione 1908 (Build 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="e567b-212">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="e567b-213">Canale semestrale: versione 1908 (Build 11929.20562)</span><span class="sxs-lookup"><span data-stu-id="e567b-213">Semi-Annual Channel: Version 1908 (Build 11929.20562)</span></span>  
<span data-ttu-id="e567b-214">Canale semestrale: versione 1902 (Build 11328.20512)</span><span class="sxs-lookup"><span data-stu-id="e567b-214">Semi-Annual Channel: Version 1902 (Build 11328.20512)</span></span>  
<span data-ttu-id="e567b-215">Canale semestrale: versione 1808 (Build 10730.20432)</span><span class="sxs-lookup"><span data-stu-id="e567b-215">Semi-Annual Channel: Version 1808 (Build 10730.20432)</span></span>  

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT START)


### <a name="excel"></a><span data-ttu-id="e567b-217">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-217">Excel</span></span>

-   [<span data-ttu-id="e567b-218">CVE-2020-0651</span><span class="sxs-lookup"><span data-stu-id="e567b-218">CVE-2020-0651</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0651)
-   [<span data-ttu-id="e567b-219">CVE-2020-0650</span><span class="sxs-lookup"><span data-stu-id="e567b-219">CVE-2020-0650</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0650)
-   [<span data-ttu-id="e567b-220">CVE-2020-0653</span><span class="sxs-lookup"><span data-stu-id="e567b-220">CVE-2020-0653</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0653)

### <a name="office-suite"></a><span data-ttu-id="e567b-221">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-221">Office Suite</span></span>

-   [<span data-ttu-id="e567b-222">CVE-2020-0652</span><span class="sxs-lookup"><span data-stu-id="e567b-222">CVE-2020-0652</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2020-0652)

[//]: # (DO NOT REMOVE SECURITY DETAILS CONTENT END)



## <a name="december-10-2019"></a><span data-ttu-id="e567b-224">10 dicembre 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-224">December 10, 2019</span></span>
<span data-ttu-id="e567b-225">Canale mensile: versione 1911 (Build 12228.20364)</span><span class="sxs-lookup"><span data-stu-id="e567b-225">Monthly Channel: Version 1911 (Build 12228.20364)</span></span>  
<span data-ttu-id="e567b-226">Canale semestrale (mirato): versione 1908 (Build 11929.20516)</span><span class="sxs-lookup"><span data-stu-id="e567b-226">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20516)</span></span>  
<span data-ttu-id="e567b-227">Canale semestrale: versione 1902 (Build 11328.20492)</span><span class="sxs-lookup"><span data-stu-id="e567b-227">Semi-Annual Channel: Version 1902 (Build 11328.20492)</span></span>  
<span data-ttu-id="e567b-228">Canale semestrale: versione 1808 (Build 10730.20426)</span><span class="sxs-lookup"><span data-stu-id="e567b-228">Semi-Annual Channel: Version 1808 (Build 10730.20426)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-229">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-229">Excel</span></span>

-   [<span data-ttu-id="e567b-230">CVE-2019-1464</span><span class="sxs-lookup"><span data-stu-id="e567b-230">CVE-2019-1464</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1464)

### <a name="powerpoint"></a><span data-ttu-id="e567b-231">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e567b-231">PowerPoint</span></span>

-   [<span data-ttu-id="e567b-232">CVE-2019-1462</span><span class="sxs-lookup"><span data-stu-id="e567b-232">CVE-2019-1462</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1462)

### <a name="word"></a><span data-ttu-id="e567b-233">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-233">Word</span></span>

-   [<span data-ttu-id="e567b-234">CVE-2019-1461</span><span class="sxs-lookup"><span data-stu-id="e567b-234">CVE-2019-1461</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1461)

### <a name="office-suite"></a><span data-ttu-id="e567b-235">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-235">Office Suite</span></span>

-   [<span data-ttu-id="e567b-236">CVE-2019-1400</span><span class="sxs-lookup"><span data-stu-id="e567b-236">CVE-2019-1400</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1400)
-   [<span data-ttu-id="e567b-237">CVE-2019-1463</span><span class="sxs-lookup"><span data-stu-id="e567b-237">CVE-2019-1463</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1463)

## <a name="november-12-2019"></a><span data-ttu-id="e567b-238">12 novembre 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-238">November 12, 2019</span></span>
<span data-ttu-id="e567b-239">Canale mensile: versione 1910 (Build 12130.20344)</span><span class="sxs-lookup"><span data-stu-id="e567b-239">Monthly Channel: Version 1910 (Build 12130.20344)</span></span>  
<span data-ttu-id="e567b-240">Canale semestrale (mirato): versione 1908 (Build 11929.20436)</span><span class="sxs-lookup"><span data-stu-id="e567b-240">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20436)</span></span>  
<span data-ttu-id="e567b-241">Canale semestrale: versione 1902 (Build 11328.20468)</span><span class="sxs-lookup"><span data-stu-id="e567b-241">Semi-Annual Channel: Version 1902 (Build 11328.20468)</span></span>  
<span data-ttu-id="e567b-242">Canale semestrale: versione 1808 (Build 10730.20416)</span><span class="sxs-lookup"><span data-stu-id="e567b-242">Semi-Annual Channel: Version 1808 (Build 10730.20416)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-243">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-243">Excel</span></span>

-   [<span data-ttu-id="e567b-244">CVE-2019-1448</span><span class="sxs-lookup"><span data-stu-id="e567b-244">CVE-2019-1448</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1448)
-   [<span data-ttu-id="e567b-245">CVE-2019-1446</span><span class="sxs-lookup"><span data-stu-id="e567b-245">CVE-2019-1446</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1446)

### <a name="office-suite"></a><span data-ttu-id="e567b-246">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-246">Office Suite</span></span>

-   [<span data-ttu-id="e567b-247">CVE-2019-1449</span><span class="sxs-lookup"><span data-stu-id="e567b-247">CVE-2019-1449</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1449)
-   [<span data-ttu-id="e567b-248">CVE-2019-1402</span><span class="sxs-lookup"><span data-stu-id="e567b-248">CVE-2019-1402</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1402)

## <a name="october-08-2019"></a><span data-ttu-id="e567b-249">8 ottobre 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-249">October 08, 2019</span></span>
<span data-ttu-id="e567b-250">Canale mensile: versione 1909 (Build 12026.20320)</span><span class="sxs-lookup"><span data-stu-id="e567b-250">Monthly Channel: Version 1909 (Build 12026.20320)</span></span>  
<span data-ttu-id="e567b-251">Canale semestrale (mirato): versione 1908 (Build 11929.20388)</span><span class="sxs-lookup"><span data-stu-id="e567b-251">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20388)</span></span>  
<span data-ttu-id="e567b-252">Canale semestrale: versione 1902 (Build 11328.20438)</span><span class="sxs-lookup"><span data-stu-id="e567b-252">Semi-Annual Channel: Version 1902 (Build 11328.20438)</span></span>  
<span data-ttu-id="e567b-253">Canale semestrale: versione 1808 (Build 10730.20386)</span><span class="sxs-lookup"><span data-stu-id="e567b-253">Semi-Annual Channel: Version 1808 (Build 10730.20386)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-254">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-254">Excel</span></span>

-   [<span data-ttu-id="e567b-255">CVE-2019-1331</span><span class="sxs-lookup"><span data-stu-id="e567b-255">CVE-2019-1331</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1331)
-   [<span data-ttu-id="e567b-256">CVE-2019-1327</span><span class="sxs-lookup"><span data-stu-id="e567b-256">CVE-2019-1327</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1327)

## <a name="september-10-2019"></a><span data-ttu-id="e567b-257">10 settembre 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-257">September 10, 2019</span></span>
<span data-ttu-id="e567b-258">Canale mensile: versione 1908 (Build 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="e567b-258">Monthly Channel: Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="e567b-259">Canale semestrale (mirato): versione 1908 (Build 11929.20300)</span><span class="sxs-lookup"><span data-stu-id="e567b-259">Semi-Annual Channel (Targeted): Version 1908 (Build 11929.20300)</span></span>  
<span data-ttu-id="e567b-260">Canale semestrale: versione 1902 (Build 11328.20420)</span><span class="sxs-lookup"><span data-stu-id="e567b-260">Semi-Annual Channel: Version 1902 (Build 11328.20420)</span></span>  
<span data-ttu-id="e567b-261">Canale semestrale: versione 1808 (Build 10730.20380)</span><span class="sxs-lookup"><span data-stu-id="e567b-261">Semi-Annual Channel: Version 1808 (Build 10730.20380)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-262">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-262">Excel</span></span>

-   [<span data-ttu-id="e567b-263">CVE-2019-1263</span><span class="sxs-lookup"><span data-stu-id="e567b-263">CVE-2019-1263</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1263)
-   [<span data-ttu-id="e567b-264">CVE-2019-1297</span><span class="sxs-lookup"><span data-stu-id="e567b-264">CVE-2019-1297</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1297)

### <a name="office-suite"></a><span data-ttu-id="e567b-265">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-265">Office Suite</span></span>

-   [<span data-ttu-id="e567b-266">CVE-2019-1246</span><span class="sxs-lookup"><span data-stu-id="e567b-266">CVE-2019-1246</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1246)
-   [<span data-ttu-id="e567b-267">CVE-2019-1264</span><span class="sxs-lookup"><span data-stu-id="e567b-267">CVE-2019-1264</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1264)

## <a name="august-13-2019"></a><span data-ttu-id="e567b-268">13 agosto 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-268">August 13, 2019</span></span>
<span data-ttu-id="e567b-269">Canale mensile: versione 1907 (Build 11901.20218)</span><span class="sxs-lookup"><span data-stu-id="e567b-269">Monthly Channel: Version 1907 (Build 11901.20218)</span></span>  
<span data-ttu-id="e567b-270">Canale semestrale (mirato): versione 1902 (Build 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="e567b-270">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="e567b-271">Canale semestrale: versione 1902 (Build 11328.20392)</span><span class="sxs-lookup"><span data-stu-id="e567b-271">Semi-Annual Channel: Version 1902 (Build 11328.20392)</span></span>  
<span data-ttu-id="e567b-272">Canale semestrale: versione 1808 (Build 10730.20370)</span><span class="sxs-lookup"><span data-stu-id="e567b-272">Semi-Annual Channel: Version 1808 (Build 10730.20370)</span></span>  
<span data-ttu-id="e567b-273">Canale semestrale: versione 1803 (Build 9126.2432)</span><span class="sxs-lookup"><span data-stu-id="e567b-273">Semi-Annual Channel: Version 1803 (Build 9126.2432)</span></span>  

### <a name="outlook"></a><span data-ttu-id="e567b-274">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-274">Outlook</span></span>

-   [<span data-ttu-id="e567b-275">CVE-2019-1199</span><span class="sxs-lookup"><span data-stu-id="e567b-275">CVE-2019-1199</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1199)
-   [<span data-ttu-id="e567b-276">CVE-2019-1204</span><span class="sxs-lookup"><span data-stu-id="e567b-276">CVE-2019-1204</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1204)
-   [<span data-ttu-id="e567b-277">CVE-2019-1200</span><span class="sxs-lookup"><span data-stu-id="e567b-277">CVE-2019-1200</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1200)

### <a name="word"></a><span data-ttu-id="e567b-278">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-278">Word</span></span>

-   [<span data-ttu-id="e567b-279">CVE-2019-1205</span><span class="sxs-lookup"><span data-stu-id="e567b-279">CVE-2019-1205</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1205)
-   [<span data-ttu-id="e567b-280">CVE-2019-1201</span><span class="sxs-lookup"><span data-stu-id="e567b-280">CVE-2019-1201</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1201)

### <a name="office-suite"></a><span data-ttu-id="e567b-281">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-281">Office Suite</span></span>

-   [<span data-ttu-id="e567b-282">CVE-2019-1155</span><span class="sxs-lookup"><span data-stu-id="e567b-282">CVE-2019-1155</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1155)

## <a name="july-09-2019"></a><span data-ttu-id="e567b-283">9 luglio 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-283">July 09, 2019</span></span>
<span data-ttu-id="e567b-284">Canale mensile: versione 1906 (Build 11727.20244)</span><span class="sxs-lookup"><span data-stu-id="e567b-284">Monthly Channel: Version 1906 (Build 11727.20244)</span></span>  
<span data-ttu-id="e567b-285">Canale semestrale (mirato): Versione 1902 (Build 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="e567b-285">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="e567b-286">Canale semestrale: Versione 1902 (Build 11328.20368)</span><span class="sxs-lookup"><span data-stu-id="e567b-286">Semi-Annual Channel: Version 1902 (Build 11328.20368)</span></span>  
<span data-ttu-id="e567b-287">Canale semestrale: Versione 1808 (Build 10730.20360)</span><span class="sxs-lookup"><span data-stu-id="e567b-287">Semi-Annual Channel: Version 1808 (Build 10730.20360)</span></span>  
<span data-ttu-id="e567b-288">Canale semestrale: Versione 1803 (Build 9126.2428)</span><span class="sxs-lookup"><span data-stu-id="e567b-288">Semi-Annual Channel: Version 1803 (Build 9126.2428)</span></span>   

### <a name="excel"></a><span data-ttu-id="e567b-289">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-289">Excel</span></span>

-   [<span data-ttu-id="e567b-290">CVE-2019-1112</span><span class="sxs-lookup"><span data-stu-id="e567b-290">CVE-2019-1112</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1112)
-   [<span data-ttu-id="e567b-291">CVE-2019-1110</span><span class="sxs-lookup"><span data-stu-id="e567b-291">CVE-2019-1110</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1110)
-   [<span data-ttu-id="e567b-292">CVE-2019-1111</span><span class="sxs-lookup"><span data-stu-id="e567b-292">CVE-2019-1111</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1111)

### <a name="outlook"></a><span data-ttu-id="e567b-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-293">Outlook</span></span>

-   [<span data-ttu-id="e567b-294">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="e567b-294">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1084)

### <a name="skype-for-business"></a><span data-ttu-id="e567b-295">Skype for Business</span><span class="sxs-lookup"><span data-stu-id="e567b-295">Skype for Business</span></span>

-   [<span data-ttu-id="e567b-296">CVE-2019-1084</span><span class="sxs-lookup"><span data-stu-id="e567b-296">CVE-2019-1084</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1084)

### <a name="office-suite"></a><span data-ttu-id="e567b-297">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-297">Office Suite</span></span>

-   [<span data-ttu-id="e567b-298">CVE-2019-1109</span><span class="sxs-lookup"><span data-stu-id="e567b-298">CVE-2019-1109</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1109)

## <a name="june-11-2019"></a><span data-ttu-id="e567b-299">11 giugno 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-299">June 11, 2019</span></span>
<span data-ttu-id="e567b-300">Canale mensile: versione 1905 (Build 11629.20246)</span><span class="sxs-lookup"><span data-stu-id="e567b-300">Monthly Channel: Version 1905 (Build 11629.20246)</span></span>  
<span data-ttu-id="e567b-301">Canale semestrale (mirato): versione 1902 (Build 11328.20318)</span><span class="sxs-lookup"><span data-stu-id="e567b-301">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20318)</span></span>   
<span data-ttu-id="e567b-302">Canale semestrale: versione 1808 (Build 10730.20348)</span><span class="sxs-lookup"><span data-stu-id="e567b-302">Semi-Annual Channel: Version 1808 (Build 10730.20348)</span></span>  
<span data-ttu-id="e567b-303">Canale semestrale: versione 1803 (Build 9126.2388)</span><span class="sxs-lookup"><span data-stu-id="e567b-303">Semi-Annual Channel: Version 1803 (Build 9126.2388)</span></span>  

### <a name="word"></a><span data-ttu-id="e567b-304">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-304">Word</span></span>

-   [<span data-ttu-id="e567b-305">CVE-2019-1034</span><span class="sxs-lookup"><span data-stu-id="e567b-305">CVE-2019-1034</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1034)
-   [<span data-ttu-id="e567b-306">CVE-2019-1035</span><span class="sxs-lookup"><span data-stu-id="e567b-306">CVE-2019-1035</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-1035)

## <a name="may-14-2019"></a><span data-ttu-id="e567b-307">14 maggio 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-307">May 14, 2019</span></span>
<span data-ttu-id="e567b-308">Canale mensile: versione 1904 (Build 11601.20204)</span><span class="sxs-lookup"><span data-stu-id="e567b-308">Monthly Channel: Version 1904 (Build 11601.20204)</span></span>  
<span data-ttu-id="e567b-309">Canale semestrale (mirato): versione 1902 (Build 11328.20286)</span><span class="sxs-lookup"><span data-stu-id="e567b-309">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20286)</span></span>  
<span data-ttu-id="e567b-310">Canale semestrale: versione 1808 (Build 10730.20344)</span><span class="sxs-lookup"><span data-stu-id="e567b-310">Semi-Annual Channel: Version 1808 (Build 10730.20344)</span></span>  
<span data-ttu-id="e567b-311">Canale semestrale: versione 1803 (Build 9126.2387)</span><span class="sxs-lookup"><span data-stu-id="e567b-311">Semi-Annual Channel: Version 1803 (Build 9126.2387)</span></span>  

### <a name="word"></a><span data-ttu-id="e567b-312">Word</span><span class="sxs-lookup"><span data-stu-id="e567b-312">Word</span></span>

-   [<span data-ttu-id="e567b-313">CVE-2019-0953</span><span class="sxs-lookup"><span data-stu-id="e567b-313">CVE-2019-0953</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0953)

### <a name="office-suite"></a><span data-ttu-id="e567b-314">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-314">Office Suite</span></span>

-   [<span data-ttu-id="e567b-315">CVE-2019-0945</span><span class="sxs-lookup"><span data-stu-id="e567b-315">CVE-2019-0945</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0945)
-   [<span data-ttu-id="e567b-316">CVE-2019-0946</span><span class="sxs-lookup"><span data-stu-id="e567b-316">CVE-2019-0946</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0946)

## <a name="april-09-2019"></a><span data-ttu-id="e567b-317">09 aprile 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-317">April 09, 2019</span></span>
<span data-ttu-id="e567b-318">Canale mensile: versione 1903 (Build 11425.20204)</span><span class="sxs-lookup"><span data-stu-id="e567b-318">Monthly Channel: Version 1903 (Build 11425.20204)</span></span>  
<span data-ttu-id="e567b-319">Canale semestrale (mirato): versione 1902 (Build 11328.20230)</span><span class="sxs-lookup"><span data-stu-id="e567b-319">Semi-Annual Channel (Targeted): Version 1902 (Build 11328.20230)</span></span>  
<span data-ttu-id="e567b-320">Canale semestrale: versione 1808 (Build 10730.20334)</span><span class="sxs-lookup"><span data-stu-id="e567b-320">Semi-Annual Channel: Version 1808 (Build 10730.20334)</span></span>  
<span data-ttu-id="e567b-321">Canale semestrale: versione 1803 (Build 9126.2382)</span><span class="sxs-lookup"><span data-stu-id="e567b-321">Semi-Annual Channel: Version 1803 (Build 9126.2382)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-322">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-322">Excel</span></span>

-   [<span data-ttu-id="e567b-323">CVE-2019-0828</span><span class="sxs-lookup"><span data-stu-id="e567b-323">CVE-2019-0828</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0828)

### <a name="office-suite"></a><span data-ttu-id="e567b-324">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-324">Office Suite</span></span>

-   [<span data-ttu-id="e567b-325">CVE-2019-0822</span><span class="sxs-lookup"><span data-stu-id="e567b-325">CVE-2019-0822</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0822)
-   [<span data-ttu-id="e567b-326">CVE-2019-0827</span><span class="sxs-lookup"><span data-stu-id="e567b-326">CVE-2019-0827</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0827)
-   [<span data-ttu-id="e567b-327">CVE-2019-0824</span><span class="sxs-lookup"><span data-stu-id="e567b-327">CVE-2019-0824</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0824)
-   [<span data-ttu-id="e567b-328">CVE-2019-0825</span><span class="sxs-lookup"><span data-stu-id="e567b-328">CVE-2019-0825</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0825)
-   [<span data-ttu-id="e567b-329">CVE-2019-0826</span><span class="sxs-lookup"><span data-stu-id="e567b-329">CVE-2019-0826</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0826)
-   [<span data-ttu-id="e567b-330">CVE-2019-0801</span><span class="sxs-lookup"><span data-stu-id="e567b-330">CVE-2019-0801</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0801)

## <a name="march-12-2019"></a><span data-ttu-id="e567b-331">12 marzo 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-331">March 12, 2019</span></span>
<span data-ttu-id="e567b-332">Questo mese non sono disponibili aggiornamenti della sicurezza per alcun canale.</span><span class="sxs-lookup"><span data-stu-id="e567b-332">There are no security updates for any channel this month.</span></span>

## <a name="february-12-2019"></a><span data-ttu-id="e567b-333">12 febbraio 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-333">February 12, 2019</span></span>
<span data-ttu-id="e567b-334">Canale mensile: versione 1901 (Build 11231.20174)</span><span class="sxs-lookup"><span data-stu-id="e567b-334">Monthly Channel: Version 1901 (Build 11231.20174)</span></span>  
<span data-ttu-id="e567b-335">Canale semestrale (mirato): versione 1808 (Build 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="e567b-335">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20280)</span></span>   
<span data-ttu-id="e567b-336">Canale semestrale: versione 1808 (Build 10730.20280)</span><span class="sxs-lookup"><span data-stu-id="e567b-336">Semi-Annual Channel: Version 1808 (Build 10730.20280)</span></span>  
<span data-ttu-id="e567b-337">Canale semestrale: versione 1803 (Build 9126.2356)</span><span class="sxs-lookup"><span data-stu-id="e567b-337">Semi-Annual Channel: Version 1803 (Build 9126.2356)</span></span>  
<span data-ttu-id="e567b-338">Canale semestrale: versione 1708 (Build 8431.2372)</span><span class="sxs-lookup"><span data-stu-id="e567b-338">Semi-Annual Channel: Version 1708 (Build 8431.2372)</span></span>  


### <a name="excel"></a><span data-ttu-id="e567b-339">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-339">Excel</span></span>

-   [<span data-ttu-id="e567b-340">CVE-2019-0669</span><span class="sxs-lookup"><span data-stu-id="e567b-340">CVE-2019-0669</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0669)

### <a name="office-suite"></a><span data-ttu-id="e567b-341">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="e567b-341">Office suite</span></span>

-   [<span data-ttu-id="e567b-342">CVE-2019-0540</span><span class="sxs-lookup"><span data-stu-id="e567b-342">CVE-2019-0540</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0540)
-   [<span data-ttu-id="e567b-343">CVE-2019-0674</span><span class="sxs-lookup"><span data-stu-id="e567b-343">CVE-2019-0674</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0674)
-   [<span data-ttu-id="e567b-344">CVE-2019-0673</span><span class="sxs-lookup"><span data-stu-id="e567b-344">CVE-2019-0673</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0673)
-   [<span data-ttu-id="e567b-345">CVE-2019-0672</span><span class="sxs-lookup"><span data-stu-id="e567b-345">CVE-2019-0672</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0672)
-   [<span data-ttu-id="e567b-346">CVE-2019-0582</span><span class="sxs-lookup"><span data-stu-id="e567b-346">CVE-2019-0582</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0582)
-   [<span data-ttu-id="e567b-347">CVE-2019-0671</span><span class="sxs-lookup"><span data-stu-id="e567b-347">CVE-2019-0671</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0671)

## <a name="january-8-2019"></a><span data-ttu-id="e567b-348">8 gennaio 2019</span><span class="sxs-lookup"><span data-stu-id="e567b-348">January 8, 2019</span></span>

<span data-ttu-id="e567b-349">Canale mensile: versione 1812 (Build 11126.20196)</span><span class="sxs-lookup"><span data-stu-id="e567b-349">Monthly Channel: Version 1812 (Build 11126.20196)</span></span>  
<span data-ttu-id="e567b-350">Canale semestrale (mirato): versione 1808 (Build 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="e567b-350">Semi-Annual Targeted Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="e567b-351">Canale semestrale: versione 1808 (Build 10730.20264)</span><span class="sxs-lookup"><span data-stu-id="e567b-351">Semi-Annual Channel: Version 1808 (Build 10730.20264)</span></span>  
<span data-ttu-id="e567b-352">Canale semestrale: versione 1803 (Build 9126.2351)</span><span class="sxs-lookup"><span data-stu-id="e567b-352">Semi-Annual Channel: Version 1803 (Build 9126.2351)</span></span>  
<span data-ttu-id="e567b-353">Canale semestrale: versione 1708 (Build 8431.2366)</span><span class="sxs-lookup"><span data-stu-id="e567b-353">Semi-Annual Channel: Version 1708 (Build 8431.2366)</span></span>  


### <a name="outlook"></a><span data-ttu-id="e567b-354">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-354">Outlook</span></span>
-   [<span data-ttu-id="e567b-355">CVE-2019-0559</span><span class="sxs-lookup"><span data-stu-id="e567b-355">CVE-2019-0559</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0559)

### <a name="word-security-updates"></a><span data-ttu-id="e567b-356">Word: aggiornamenti della sicurezza</span><span class="sxs-lookup"><span data-stu-id="e567b-356">Word: Security updates</span></span> 
-   [<span data-ttu-id="e567b-357">CVE-2019-0561</span><span class="sxs-lookup"><span data-stu-id="e567b-357">CVE-2019-0561</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0561)
-   [<span data-ttu-id="e567b-358">CVE-2019-0585</span><span class="sxs-lookup"><span data-stu-id="e567b-358">CVE-2019-0585</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0585) 
 
### <a name="office-suite-security-updates"></a><span data-ttu-id="e567b-359">Famiglia di prodotti Office: aggiornamenti della sicurezza</span><span class="sxs-lookup"><span data-stu-id="e567b-359">Office suite: Security updates</span></span> 
-   [<span data-ttu-id="e567b-360">CVE-2019-0541</span><span class="sxs-lookup"><span data-stu-id="e567b-360">CVE-2019-0541</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0541)
-   [<span data-ttu-id="e567b-361">CVE-2019-0560</span><span class="sxs-lookup"><span data-stu-id="e567b-361">CVE-2019-0560</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2019-0560)

## <a name="december-11-2018"></a><span data-ttu-id="e567b-362">11 dicembre 2018</span><span class="sxs-lookup"><span data-stu-id="e567b-362">December 11, 2018</span></span>
<span data-ttu-id="e567b-363">Canale mensile: versione 1811 (Build 11029.20108)</span><span class="sxs-lookup"><span data-stu-id="e567b-363">Monthly Channel: Version 1811 (Build 11029.20108)</span></span>  
<span data-ttu-id="e567b-364">Canale semestrale: versione 1803 (Build 9126.2336)</span><span class="sxs-lookup"><span data-stu-id="e567b-364">Semi-Annual Channel: Version 1803 (Build 9126.2336)</span></span>  
<span data-ttu-id="e567b-365">Canale semestrale (mirato): versione 1808 (Build 10730.20262)</span><span class="sxs-lookup"><span data-stu-id="e567b-365">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20262)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-366">Excel</span><span class="sxs-lookup"><span data-stu-id="e567b-366">Excel</span></span>

-   [<span data-ttu-id="e567b-367">CVE-2018-8597</span><span class="sxs-lookup"><span data-stu-id="e567b-367">CVE-2018-8597</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8597)
-   [<span data-ttu-id="e567b-368">CVE-2018-8627</span><span class="sxs-lookup"><span data-stu-id="e567b-368">CVE-2018-8627</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8627)
-   [<span data-ttu-id="e567b-369">CVE-2018-8598</span><span class="sxs-lookup"><span data-stu-id="e567b-369">CVE-2018-8598</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8598)
-   [<span data-ttu-id="e567b-370">CVE-2018-8636</span><span class="sxs-lookup"><span data-stu-id="e567b-370">CVE-2018-8636</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8636)

### <a name="outlook"></a><span data-ttu-id="e567b-371">Outlook</span><span class="sxs-lookup"><span data-stu-id="e567b-371">Outlook</span></span>

-   [<span data-ttu-id="e567b-372">CVE-2018-8587</span><span class="sxs-lookup"><span data-stu-id="e567b-372">CVE-2018-8587</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8587)

### <a name="powerpoint"></a><span data-ttu-id="e567b-373">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="e567b-373">PowerPoint</span></span>

-   [<span data-ttu-id="e567b-374">CVE-2018-8628</span><span class="sxs-lookup"><span data-stu-id="e567b-374">CVE-2018-8628</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8628)

## <a name="november-13-2018"></a><span data-ttu-id="e567b-375">13 novembre 2018</span><span class="sxs-lookup"><span data-stu-id="e567b-375">November 13, 2018</span></span>
<span data-ttu-id="e567b-376">Canale mensile: versione 1810 (Build 11001.20108)</span><span class="sxs-lookup"><span data-stu-id="e567b-376">Monthly Channel: Version 1810 (Build 11001.20108)</span></span>  
<span data-ttu-id="e567b-377">Canale semestrale: versione 1803 (Build 9126.2315)</span><span class="sxs-lookup"><span data-stu-id="e567b-377">Semi-Annual Channel: Version 1803 (Build 9126.2315)</span></span>  
<span data-ttu-id="e567b-378">Canale semestrale (mirato): versione 1808 (Build 10730.20205)</span><span class="sxs-lookup"><span data-stu-id="e567b-378">Semi-Annual Channel (Targeted): Version 1808 (Build 10730.20205)</span></span>  

### <a name="excel"></a><span data-ttu-id="e567b-379">Excel:</span><span class="sxs-lookup"><span data-stu-id="e567b-379">Excel:</span></span>

-   [<span data-ttu-id="e567b-380">CVE-2018-8574</span><span class="sxs-lookup"><span data-stu-id="e567b-380">CVE-2018-8574</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8574)
-   [<span data-ttu-id="e567b-381">CVE-2018-8577</span><span class="sxs-lookup"><span data-stu-id="e567b-381">CVE-2018-8577</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8577)

### <a name="outlook"></a><span data-ttu-id="e567b-382">Outlook:</span><span class="sxs-lookup"><span data-stu-id="e567b-382">Outlook:</span></span>

-   [<span data-ttu-id="e567b-383">CVE-2018-8522</span><span class="sxs-lookup"><span data-stu-id="e567b-383">CVE-2018-8522</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8522)
-   [<span data-ttu-id="e567b-384">CVE-2018-8524</span><span class="sxs-lookup"><span data-stu-id="e567b-384">CVE-2018-8524</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8524)
-   [<span data-ttu-id="e567b-385">CVE-2018-8558</span><span class="sxs-lookup"><span data-stu-id="e567b-385">CVE-2018-8558</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8558)
-   [<span data-ttu-id="e567b-386">CVE-2018-8576</span><span class="sxs-lookup"><span data-stu-id="e567b-386">CVE-2018-8576</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8576)
-   [<span data-ttu-id="e567b-387">CVE-2018-8579</span><span class="sxs-lookup"><span data-stu-id="e567b-387">CVE-2018-8579</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8579)
-   [<span data-ttu-id="e567b-388">CVE-2018-8582</span><span class="sxs-lookup"><span data-stu-id="e567b-388">CVE-2018-8582</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8582)

### <a name="project"></a><span data-ttu-id="e567b-389">Project:</span><span class="sxs-lookup"><span data-stu-id="e567b-389">Project:</span></span>

-   [<span data-ttu-id="e567b-390">CVE-2018-8575</span><span class="sxs-lookup"><span data-stu-id="e567b-390">CVE-2018-8575</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8575)

### <a name="skype-for-business"></a><span data-ttu-id="e567b-391">Skype for Business:</span><span class="sxs-lookup"><span data-stu-id="e567b-391">Skype for Business:</span></span>

-   [<span data-ttu-id="e567b-392">CVE-2018-8546</span><span class="sxs-lookup"><span data-stu-id="e567b-392">CVE-2018-8546</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8546)

### <a name="word"></a><span data-ttu-id="e567b-393">Word:</span><span class="sxs-lookup"><span data-stu-id="e567b-393">Word:</span></span>

-   [<span data-ttu-id="e567b-394">CVE-2018-8573</span><span class="sxs-lookup"><span data-stu-id="e567b-394">CVE-2018-8573</span></span>](https://portal.msrc.microsoft.com/it-IT/security-guidance/advisory/CVE-2018-8573)
