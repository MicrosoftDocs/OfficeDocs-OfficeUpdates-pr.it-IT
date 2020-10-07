---
title: Problemi noti di Office 365 ProPlus
ms.author: anankani
author: anankani
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Priority
ms.collection: RelNotes_ProPlus
description: Sono disponibili informazioni sui problemi noti di Office 365 ProPlus
ms.openlocfilehash: eb771e0584a76f4ab4d506987a6b2379cc7087ee
ms.sourcegitcommit: db492a4c51ec771ab97c67e4b1d43ee36d8794b8
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 10/07/2020
ms.locfileid: "48369944"
---
# <a name="microsoft-365-apps-known-issues"></a><span data-ttu-id="a467f-103">Problemi noti di Microsoft 365 Apps</span><span class="sxs-lookup"><span data-stu-id="a467f-103">Microsoft 365 Apps Known Issues</span></span>

<span data-ttu-id="a467f-104">Questi problemi noti forniscono informazioni sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale mensile, del Canale semestrale (mirato) e del Canale semestrale nel 2019 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="a467f-104">These known issues provide information about non-security updates that are included in Monthly Channel, Semi-Annual Channel (Targeted), and Semi-Annual Channel  updates in 2019 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>


> [!NOTE]
>- <span data-ttu-id="a467f-105">L'elenco non è completo.</span><span class="sxs-lookup"><span data-stu-id="a467f-105">This list is not comprehensive.</span></span>
>- <span data-ttu-id="a467f-106">Se si verifica un problema in un canale diverso dal canale indicato come risolto, la risoluzione sarà presto effettuata.</span><span class="sxs-lookup"><span data-stu-id="a467f-106">If you are experiencing an issue in a channel other than the channel shown as resolved, you can expect resolution soon.</span></span> [<span data-ttu-id="a467f-107">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="a467f-107">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/overview-of-update-channels-for-office-365-proplus#BKMK_SAC)
>- <span data-ttu-id="a467f-108">I problemi risolti sono documentati anche nelle rispettive pagine del canale.</span><span class="sxs-lookup"><span data-stu-id="a467f-108">Resolved issues are documented in their respective channel pages as well.</span></span>

<br>

### <a name="last-updated-november-12-2019"></a><span data-ttu-id="a467f-109">Ultimo aggiornamento 12 novembre 2019</span><span class="sxs-lookup"><span data-stu-id="a467f-109">Last Updated November 12, 2019</span></span>

### <a name="excel"></a><span data-ttu-id="a467f-110">Excel</span><span class="sxs-lookup"><span data-stu-id="a467f-110">Excel</span></span>

- <span data-ttu-id="a467f-111">I controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe</span><span class="sxs-lookup"><span data-stu-id="a467f-111">Check box controls could shrink when using autofit to adjust row height</span></span><br><br><span data-ttu-id="a467f-112">**In analisi**: mensile, SACT</span><span class="sxs-lookup"><span data-stu-id="a467f-112">**Investigating**: Monthly, SACT</span></span>

- <span data-ttu-id="a467f-113">Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.</span><span class="sxs-lookup"><span data-stu-id="a467f-113">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span><br><br><span data-ttu-id="a467f-114">**Risolto**: Versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-114">**Resolved**: SACT Version 1908 (11929.20436)</span></span> 

- <span data-ttu-id="a467f-115">Era possibile che gli utenti non riuscissero a salvare in formato cartella di lavoro Excel in Office 365</span><span class="sxs-lookup"><span data-stu-id="a467f-115">Users could be prevented from saving in Office 365 Excel Workbook format</span></span><br><br><span data-ttu-id="a467f-116">**Risolto**: Versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-116">**Resolved**: SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="a467f-117">Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.</span><span class="sxs-lookup"><span data-stu-id="a467f-117">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span><br><br><span data-ttu-id="a467f-118">**Risolto**: Versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-118">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="a467f-119">Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite</span><span class="sxs-lookup"><span data-stu-id="a467f-119">Significant improvements to the performance of deleting columns with merged cells</span></span><br><br><span data-ttu-id="a467f-120">**In analisi**: SACT</span><span class="sxs-lookup"><span data-stu-id="a467f-120">**Investigating**: SACT</span></span><br><span data-ttu-id="a467f-121">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-121">**Resolved**:  Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-122">Risultati non corretti ottenuti durante la conversione dei filtri dei report con il resto della Tabella pivot per le query ai server tabulari SQL.</span><span class="sxs-lookup"><span data-stu-id="a467f-122">Incorrect results when converting report filters along with the rest of the PivotTable for queries to SQL tabular servers.</span></span><br><br><span data-ttu-id="a467f-123">**In analisi**: mensile</span><span class="sxs-lookup"><span data-stu-id="a467f-123">**Investigating**: Monthly</span></span>

- <span data-ttu-id="a467f-124">Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico</span><span class="sxs-lookup"><span data-stu-id="a467f-124">Fix to correct colors used in previews when inserting charts using chart templates</span></span><br><br><span data-ttu-id="a467f-125">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-125">**Resolved**:  Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>


- <span data-ttu-id="a467f-126">È stato rilevato un problema relativo all'inserimento di file come oggetti da OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a467f-126">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="a467f-127">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-127">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-128">È stato rilevato un problema per cui le cartelle di lavoro create in versioni precedenti di Office possono causare il blocco di Excel se aperte nelle versioni correnti di Office.</span><span class="sxs-lookup"><span data-stu-id="a467f-128">Identified an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span><br><br>
<span data-ttu-id="a467f-129">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436), versione SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a467f-129">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="a467f-130">È stato rilevato un problema che causava ritardi nella visualizzazione dei valori digitati dopo l'eliminazione di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="a467f-130">Identified an issue that was causing delays in displaying typed values after deleting a range.</span></span><br><br>
<span data-ttu-id="a467f-131">**Risolto**: Versione SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a467f-131">**Resolved**: SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="a467f-132">È stato rilevato un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="a467f-132">Identified an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span><br><br>
<span data-ttu-id="a467f-133">**In analisi**: SACT</span><span class="sxs-lookup"><span data-stu-id="a467f-133">**Investigating**: SACT</span></span> <br><span data-ttu-id="a467f-134">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-134">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-135">È stato rilevato un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.</span><span class="sxs-lookup"><span data-stu-id="a467f-135">Identified an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span><br><br>
<span data-ttu-id="a467f-136">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20300)</span><span class="sxs-lookup"><span data-stu-id="a467f-136">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20300)</span></span>

### <a name="outlook"></a><span data-ttu-id="a467f-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="a467f-137">Outlook</span></span>

- <span data-ttu-id="a467f-138">È stato rilevato un problema per cui alcuni utenti visualizzavano cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="a467f-138">Identified an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="a467f-139">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-139">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="a467f-140">È stato rilevato un problema che causava una perdita di memoria.</span><span class="sxs-lookup"><span data-stu-id="a467f-140">Identified an issue which could have resulted in a memory leak.</span></span> <br><br>
<span data-ttu-id="a467f-141">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20388), versione SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a467f-141">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20388), SAC Version 1902 (11328.20468)</span></span>

- <span data-ttu-id="a467f-142">È stato risolto un problema per cui alcuni utenti visualizzavano cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="a467f-142">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span><br><br>
<span data-ttu-id="a467f-143">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-143">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="a467f-144">È stato rilevato un problema che comportava un arresto anomalo quando un utente riceveva un messaggio di "Conversazione non effettuata" da Skype.</span><span class="sxs-lookup"><span data-stu-id="a467f-144">Identified an issue which could sometimes result in a crash when a user receives a 'Missed Conversation' message from Skype.</span></span><br><br>
<span data-ttu-id="a467f-145">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-145">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-146">È stato rilevato un problema per il quale gli utenti ricevevano un messaggio di errore generico "operazione non riuscita" all'apertura di un allegato in un computer in cui è abilitato DisableBGSave.</span><span class="sxs-lookup"><span data-stu-id="a467f-146">Identified an issue that caused Users to receive a generic ""operation failed"" error when opening an attachment on a machine where DisableBGSave is enabled.</span></span><br><br>
<span data-ttu-id="a467f-147">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-147">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-148">È stato rilevato un problema con i collegamenti di CID: le immagini (immagini basate su posta elettronica di Outlook) non possono essere interrotte.</span><span class="sxs-lookup"><span data-stu-id="a467f-148">Identified an issue with the links of cid: images (Outlook email-based images) were not able to be broken.</span></span><br><br>
<span data-ttu-id="a467f-149">**Risolto**: Versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-149">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="a467f-150">È stato rilevato un problema che causava un messaggio di errore non corretto quando si provava a inviare posta elettronica crittografata s/MIME.</span><span class="sxs-lookup"><span data-stu-id="a467f-150">Identified an issue which could have caused an incorrect error message when attempting to send s/MIME encrypted e-mail.</span></span><br><br><span data-ttu-id="a467f-151">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-151">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="a467f-152">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="a467f-152">PowerPoint</span></span>

- <span data-ttu-id="a467f-153">Alcuni caratteri katakana potrebbero non essere visualizzati correttamente in una casella di testo verticale.</span><span class="sxs-lookup"><span data-stu-id="a467f-153">Some katakana characters may display incorrectly in a vertical text box.</span></span><br><br>
<span data-ttu-id="a467f-154">**In analisi**: mensile</span><span class="sxs-lookup"><span data-stu-id="a467f-154">**Investigating**: Monthly</span></span>

- <span data-ttu-id="a467f-155">È stato rilevato un problema che impediva la creazione di un collegamento ipertestuale quando si incollava il testo con tale collegamento.</span><span class="sxs-lookup"><span data-stu-id="a467f-155">Identified an issue which prevented hyperlink from being created when pasting text with hyperlink.</span></span> <br><br><span data-ttu-id="a467f-156">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-156">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-157">È stato rilevato un problema che causava il danneggiamento dei TextRanges dopo aver incollato il testo nei segnaposto intestazione/piè di pagina/numero nello schema diapositiva e layout di diapositiva.</span><span class="sxs-lookup"><span data-stu-id="a467f-157">Identified an issue which could cause TextRanges to become broken after pasting text into the header/footer/slide number placeholders on slide master and slide layout.</span></span> <br><br><span data-ttu-id="a467f-158">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-158">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

- <span data-ttu-id="a467f-159">È stato identificato un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.</span><span class="sxs-lookup"><span data-stu-id="a467f-159">Identified a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span><br>
<br><span data-ttu-id="a467f-160">**Risolto**: Versione mensile 1910 (12130.20272), versione SACT 1908 (11929.20396), versione SAC 1902 (11328.20468)</span><span class="sxs-lookup"><span data-stu-id="a467f-160">**Resolved**: Monthly Version 1910 (12130.20272), SACT Version 1908 (11929.20396), SAC Version 1902 (11328.20468)</span></span>

### <a name="project"></a><span data-ttu-id="a467f-161">Project</span><span class="sxs-lookup"><span data-stu-id="a467f-161">Project</span></span>

- <span data-ttu-id="a467f-162">In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.</span><span class="sxs-lookup"><span data-stu-id="a467f-162">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span><br><br>
<span data-ttu-id="a467f-163">**In analisi**: mensile</span><span class="sxs-lookup"><span data-stu-id="a467f-163">**Investigating**: Monthly</span></span><br>
<span data-ttu-id="a467f-164">**Risolto**: Versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-164">**Resolved**: SACT Version 1908 (11929.20436)</span></span>

- <span data-ttu-id="a467f-165">Le sovrassegnazioni non vengono risolte dal livellamento</span><span class="sxs-lookup"><span data-stu-id="a467f-165">Overallocations are not resolved by leveling</span></span><br><br>
<span data-ttu-id="a467f-166">**In analisi**: mensile</span><span class="sxs-lookup"><span data-stu-id="a467f-166">**Investigating**: Monthly</span></span>

- <span data-ttu-id="a467f-167">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="a467f-167">Identified an issue where users could get several messages when opening a read-only project.</span></span><br><br>
<span data-ttu-id="a467f-168">**Risolto**: Versione mensile 1910 (12130.20344), versione SACT 1908 (11929.20436)</span><span class="sxs-lookup"><span data-stu-id="a467f-168">**Resolved**: Monthly Version 1910 (12130.20344), SACT Version 1908 (11929.20436)</span></span>

### <a name="word"></a><span data-ttu-id="a467f-169">Word</span><span class="sxs-lookup"><span data-stu-id="a467f-169">Word</span></span>

- <span data-ttu-id="a467f-170">La ricerca dal riquadro di spostamento potrebbe non riuscire</span><span class="sxs-lookup"><span data-stu-id="a467f-170">Searching from the Navigation pane may fail</span></span><br><br>
<span data-ttu-id="a467f-171">**In analisi**: mensile</span><span class="sxs-lookup"><span data-stu-id="a467f-171">**Investigating**: Monthly</span></span>

- <span data-ttu-id="a467f-172">È stato rilevato un problema relativo all'inserimento di file come oggetti da OneDrive.</span><span class="sxs-lookup"><span data-stu-id="a467f-172">Identified an issue in inserting files as object from OneDrive.</span></span><br><br> <span data-ttu-id="a467f-173">**Risolto**: Versione mensile 1910 (12130.20272)</span><span class="sxs-lookup"><span data-stu-id="a467f-173">**Resolved**: Monthly Version 1910 (12130.20272)</span></span>

### <a name="office-suite"></a><span data-ttu-id="a467f-174">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="a467f-174">Office Suite</span></span>
- <span data-ttu-id="a467f-175">Se si tenta di salvare un file in una condivisione di rete disconnessa, potrebbero verificarsi dei problemi **In analisi**: mensile</span><span class="sxs-lookup"><span data-stu-id="a467f-175">Attempting to save a file to a disconnected network share may result in issues **Investigating**: Monthly</span></span>



<br>
<br>

> [!NOTE]
> <span data-ttu-id="a467f-176">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="a467f-176">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
