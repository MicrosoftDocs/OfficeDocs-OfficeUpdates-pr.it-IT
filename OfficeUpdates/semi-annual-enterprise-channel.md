---
title: Note sulla versione per i rilasci del Canale Enterprise semestrale nel 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per i professionisti IT con le note sulla versione per i rilasci del Canale semestrale per Microsoft 365 Apps nel 2020
ms.openlocfilehash: 9e420ed8c7c6f5c329b3137f21b952f7a29af7e1
ms.sourcegitcommit: b7cd1fc37ece6cf0399d89549f7916a4dc40d829
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 09/16/2020
ms.locfileid: "47942773"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-releases-in-2020"></a><span data-ttu-id="2e732-103">Note sulla versione per i rilasci del Canale Enterprise semestrale nel 2020</span><span class="sxs-lookup"><span data-stu-id="2e732-103">Release notes for Semi-Annual Enterprise Channel releases in 2020</span></span>

<span data-ttu-id="2e732-104">Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale Enterprise semestrale nel 2020 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="2e732-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="2e732-105">Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Monthly Enterprise Channel) e la modifica dei nomi dei canali di aggiornamento già presenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="2e732-106">Leggere [questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441) per altre informazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="2e732-107">OneNote 2016 sarà ora incluso per impostazione predefinita quando un utente del Canale Enterprise scarica e installa Microsoft 365 Apps in Windows 10 dal portale di Office.</span><span class="sxs-lookup"><span data-stu-id="2e732-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-september-08"></a><span data-ttu-id="2e732-109">Versione 2002: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="2e732-109">Version 2002: September 08</span></span>
<span data-ttu-id="2e732-110">*Versione 2002 (Build 12527,21104)*</span><span class="sxs-lookup"><span data-stu-id="2e732-110">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="2e732-111">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-113">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-114">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-114">Excel</span></span>

- <span data-ttu-id="2e732-115">Questo risolve un problema in cui le connessioni create dal provider di dati SQL nelle versioni precedenti di Office imposterebbero le proprietà della tabella interna in modo diverso da Office 365.</span><span class="sxs-lookup"><span data-stu-id="2e732-115">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="2e732-116">Ciò ha causato la disabilitazione dell'elenco a discesa Anteprima tabella/Editor di query per i file con connessioni create nelle versioni precedenti di Office quando sono stati aperti utilizzando Office 365.</span><span class="sxs-lookup"><span data-stu-id="2e732-116">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="2e732-117">È stato risolto un problema per cui l’input penna poteva far sì che Excel smettesse di rispondere.</span><span class="sxs-lookup"><span data-stu-id="2e732-117">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e732-118">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-118">Outlook</span></span>

- <span data-ttu-id="2e732-119">Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.</span><span class="sxs-lookup"><span data-stu-id="2e732-119">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e732-120">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-120">Office Suite</span></span>

- <span data-ttu-id="2e732-121">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="2e732-121">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-08"></a><span data-ttu-id="2e732-123">Versione 1908: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="2e732-123">Version 1908: September 08</span></span>
<span data-ttu-id="2e732-124">*Versione 1908 (Build 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="2e732-124">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="2e732-125">Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-125">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="2e732-126">Versione 2002: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="2e732-126">Version 2002: August 11</span></span>
<span data-ttu-id="2e732-127">*Versione 2002 (Build 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="2e732-127">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="2e732-128">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-128">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-130">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-130">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-131">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-131">Excel</span></span>

- <span data-ttu-id="2e732-132">È stato risolto un problema che impediva di modificare i file aperti in modalità "Consigliata sola lettura".</span><span class="sxs-lookup"><span data-stu-id="2e732-132">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="2e732-133">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e732-133">OneNote</span></span>

- <span data-ttu-id="2e732-134">Sono state rimosse le chiamate di identità ridondanti per ridurre l'utilizzo delle risorse</span><span class="sxs-lookup"><span data-stu-id="2e732-134">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="2e732-135">È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.</span><span class="sxs-lookup"><span data-stu-id="2e732-135">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="2e732-136">Sono state migliorate la funzionalità di rilevamento di errori e la qualità dell'esperienza di sincronizzazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-136">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-137">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-137">Outlook</span></span>

- <span data-ttu-id="2e732-138">È stato risolto un problema che causava un notevole problema di prestazioni durante l'avvio di Outlook per alcuni tenant.</span><span class="sxs-lookup"><span data-stu-id="2e732-138">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="2e732-139">Skype</span><span class="sxs-lookup"><span data-stu-id="2e732-139">Skype</span></span>

- <span data-ttu-id="2e732-140">È stato risolto un problema che causava un errore di avvio della condivisione dello schermo quando un client Skype for Business a 32 bit era in uso per diversi giorni.</span><span class="sxs-lookup"><span data-stu-id="2e732-140">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-141">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-141">Office Suite</span></span>

- <span data-ttu-id="2e732-142">È stato risolto un problema per cui, se il salvataggio automatico era disattivato con i criteri di gruppo, quando si aprivano alcuni documenti per visualizzare il contenuto più recente sul server bisognava fare clic su "Aggiornamenti disponibili".</span><span class="sxs-lookup"><span data-stu-id="2e732-142">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-11"></a><span data-ttu-id="2e732-144">Versione 1908: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="2e732-144">Version 1908: August 11</span></span>
<span data-ttu-id="2e732-145">*Versione 1908 (Build 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="2e732-145">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="2e732-146">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="2e732-147">Versione 1902: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="2e732-147">Version 1902: August 11</span></span>
<span data-ttu-id="2e732-148">*Versione 1902 (Build 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="2e732-148">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="2e732-149">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-149">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="2e732-152">Versione 2002: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="2e732-152">Version 2002: July 14</span></span>
<span data-ttu-id="2e732-153">*Versione 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="2e732-153">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="2e732-154">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-154">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e732-156">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="2e732-156">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2e732-157">Access</span><span class="sxs-lookup"><span data-stu-id="2e732-157">Access</span></span>

- <span data-ttu-id="2e732-158">**Trovare velocemente le tabelle collegate:** la nostra nuova casella di ricerca rende molto più facile trovare le tabelle collegate.</span><span class="sxs-lookup"><span data-stu-id="2e732-158">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="2e732-159">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-159">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="2e732-160">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-160">Excel</span></span>

- <span data-ttu-id="2e732-161">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="2e732-161">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2e732-162">**Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel.</span><span class="sxs-lookup"><span data-stu-id="2e732-162">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="2e732-163">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-163">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2e732-164">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="2e732-164">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2e732-165">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-165">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2e732-166">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="2e732-166">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2e732-167">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-167">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2e732-168">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-168">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2e732-169">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-169">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2e732-170">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="2e732-170">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2e732-171">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="2e732-171">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2e732-172">**Concentrarsi su ciò che resta da fare:** selezionare Risolvi per comprimere i commenti e far risaltare quelli ancora non risolti.</span><span class="sxs-lookup"><span data-stu-id="2e732-172">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="2e732-173">**Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-173">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="2e732-174">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-174">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="2e732-175">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="2e732-175">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="2e732-176">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="2e732-176">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2e732-177">**Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella cartella di lavoro, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="2e732-177">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="2e732-178">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-178">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2e732-179">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="2e732-179">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2e732-180">**Trovare gli elementi cercati:** è possibile cercare comandi, persone, file, foto, notizie e molto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="2e732-180">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="2e732-181">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-181">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2e732-182">**Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE.</span><span class="sxs-lookup"><span data-stu-id="2e732-182">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="2e732-183">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-183">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="2e732-184">**Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X.</span><span class="sxs-lookup"><span data-stu-id="2e732-184">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="2e732-185">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-185">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="2e732-186">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="2e732-186">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="2e732-187">**Gestire al meglio le cartelle di lavoro di grandi dimensioni:** celle, formule, grafici, tabelle... ottenere un’istantanea della cartella di lavoro con l’opzione Statistiche cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-187">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="2e732-188">**Leggere e rispondere all'istante:** rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-188">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="2e732-189">**Ottenere l'attenzione tramite \@menzioni:** usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="2e732-189">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2e732-190">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-190">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="2e732-191">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-191">Outlook</span></span>

- <span data-ttu-id="2e732-192">**Possibilità di visualizzare più messaggi sullo schermo:** Selezionare Visualizza > Usa spazio più stretto per regolare la spaziatura tra i messaggi.</span><span class="sxs-lookup"><span data-stu-id="2e732-192">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="2e732-193">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-193">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="2e732-194">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-194">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2e732-195">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-195">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2e732-196">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-196">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2e732-197">**Aggiunta della funzionalità Input penna:** è possibile scarabocchiare sopra le immagini o aggiungere un'area di disegno per inviare idee con l'input penna.</span><span class="sxs-lookup"><span data-stu-id="2e732-197">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="2e732-198">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-198">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="2e732-199">**Suggerimenti per il luogo delle riunioni:** è sufficiente iniziare a scrivere nella riga Luogo durante la pianificazione di appuntamenti e riunioni e Outlook suggerirà sale, indirizzi e altri luoghi recenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-199">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="2e732-200">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-200">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="2e732-201">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="2e732-201">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="2e732-202">**Protezione avanzata dalle minacce:** con Office 365 Advanced Threat Protection, si è protetti dalle minacce tramite collegamenti ipertestuali negli oggetti di posta elettronica, messaggi allegati, messaggi firmati, percorsi di rete e così via.</span><span class="sxs-lookup"><span data-stu-id="2e732-202">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="2e732-203">**Il menu Inserisci collegamento in Outlook inserisce un collegamento con l'autorizzazione definita dall'amministratore tenant:** un collegamento dall'elenco dei file usati di recenti in Inserisci collegamento in Outlook inseriva un collegamento che funzionava solo per gli utenti che avevano già le relative autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-203">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="2e732-204">Questo causava spesso uno scambio di messaggi tra gli utenti per richiedere l'accesso a un documento.</span><span class="sxs-lookup"><span data-stu-id="2e732-204">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="2e732-205">Questa esperienza è stata aggiornata in modo tale che il collegamento venga inserito con l'autorizzazione predefinita impostata dall'amministratore tenant. Per MSIT si tratta dell’opzione "L’organizzazione può modificare", pertanto tutti gli utenti interni che riceveranno un collegamento condiviso in questo modo saranno in grado di accedervi.</span><span class="sxs-lookup"><span data-stu-id="2e732-205">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="2e732-206">**Vedere i messaggi sotto una luce diversa:** usare il pulsante Sole/Luna per utilizzare lo sfondo chiaro o lo sfondo scuro nel riquadro di lettura.</span><span class="sxs-lookup"><span data-stu-id="2e732-206">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="2e732-207">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-207">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="2e732-208">**I messaggi di phishing sono facilmente individuabili:** la posta indesiderata e i messaggi di phishing hanno un aspetto diverso, in modo da poterli identificare e rimuovere facilmente dalla posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="2e732-208">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="2e732-p119">**Tutte le opzioni di crittografia in un'unica posizione:** basta passare a Opzioni > Crittografa per scegliere come proteggere il messaggio di posta elettronica. [Altre informazioni](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="2e732-p119">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="2e732-211">**Cercare testo contenente errori di ortografia o di digitazione:** Outlook troverà il testo cercato anche quando l'ortografia non è corretta.</span><span class="sxs-lookup"><span data-stu-id="2e732-211">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="2e732-212">**Connessione della rete LinkedIn a Outlook:** connessione sicura degli account LinkedIn all'account Microsoft per visualizzare le informazioni dei profili LinkedIn direttamente nella scheda Utenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-212">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="2e732-213">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-213">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="2e732-214">**Visualizza i messaggi rilevanti nei risultati della ricerca:** Outlook analizza i termini di ricerca e visualizza i messaggi di posta elettronica più importanti nella parte superiore dei risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-214">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="2e732-215">I risultati saranno ordinati anche per data nella sezione Risultati principali.</span><span class="sxs-lookup"><span data-stu-id="2e732-215">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="2e732-216">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-216">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="2e732-217">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-217">PowerPoint</span></span>

- <span data-ttu-id="2e732-p122">**La formattazione dei calcoli diventa automatica:** le espressioni matematiche scritte a mano vengono convertite in caratteri standard. Per iniziare, basta selezionare le note scritte a mano e scegliere Da input penna a testo matematico. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="2e732-p122">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="2e732-221">**Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="2e732-221">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2e732-222">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-222">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2e732-223">**Input penna per diapositive meravigliose:** è possibile convertire l'input penna in forme e testo standard e quindi ottenere idee di progettazione delle diapositive intelligenti da PowerPoint Designer.</span><span class="sxs-lookup"><span data-stu-id="2e732-223">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="2e732-224">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-224">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="2e732-225">**Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella presentazione, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="2e732-225">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="2e732-226">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-226">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2e732-227">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="2e732-227">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2e732-228">**Replay immediato:** applicare un'animazione di riproduzione per ripetere la sequenza di disegno con l'input penna durante la presentazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-228">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="2e732-229">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-229">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="2e732-230">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="2e732-230">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="2e732-231">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="2e732-231">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="2e732-232">**Salvare un'illustrazione in formato SVG:** è possibile salvare un grafico, una forma o un'altra illustrazione in formato SVG (Scalable Vector Graphic), che può essere ridimensionato senza perdita di qualità dell'immagine.</span><span class="sxs-lookup"><span data-stu-id="2e732-232">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="2e732-233">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-233">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="2e732-234">**Stampa dei numeri delle diapositive negli stampati:** i numeri delle diapositive vengono inclusi automaticamente negli stampati.</span><span class="sxs-lookup"><span data-stu-id="2e732-234">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="2e732-235">Lasciarli attivati o disattivarli è a discrezione dell'utente.</span><span class="sxs-lookup"><span data-stu-id="2e732-235">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="2e732-236">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-236">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="2e732-237">**Trovare e correggere titoli di diapositive mancanti:** i titoli delle diapositive ottimizzano la presentazione e rendono le diapositive accessibili per tutti gli utenti, anche con diverse abilità.</span><span class="sxs-lookup"><span data-stu-id="2e732-237">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="2e732-238">L’opzione Verifica accessibilità mostra dove mancano i titoli in modo da aggiungerli in pochi secondi.</span><span class="sxs-lookup"><span data-stu-id="2e732-238">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="2e732-239">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-239">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="2e732-240">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="2e732-240">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2e732-241">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="2e732-241">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2e732-242">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-242">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="2e732-243">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-243">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2e732-244">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-244">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="2e732-245">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="2e732-245">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="2e732-246">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="2e732-246">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2e732-247">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="2e732-247">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2e732-248">**Collaborazione in tempo reale veloce in PowerPoint:** è possibile collaborare in tempo reale rapidamente in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-248">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="2e732-249">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="2e732-249">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="2e732-250">**Nuovi strumenti di correzione:** niente più preoccupazione per le parole.</span><span class="sxs-lookup"><span data-stu-id="2e732-250">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="2e732-251">PowerPoint offre suggerimenti relativi a grammatica e ortografia.</span><span class="sxs-lookup"><span data-stu-id="2e732-251">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="2e732-252">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-252">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="2e732-253">**Sottotitoli e sottotitoli in tempo reale:** le parole del relatore vengono visualizzate automaticamente sullo schermo come sottotitoli o tradotti in sottotitoli nella lingua scelta.</span><span class="sxs-lookup"><span data-stu-id="2e732-253">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="2e732-254">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-254">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="2e732-255">**Ottimizzazione della presentazione per tutti:** Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="2e732-255">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="2e732-256">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="2e732-256">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="2e732-257">**Perché reinventare quando è possibile riutilizzare?:** per risparmiare tempo, è possibile riutilizzare le diapositive create personalmente o condivise da altri utenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-257">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="2e732-258">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-258">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="2e732-259">Visio</span><span class="sxs-lookup"><span data-stu-id="2e732-259">Visio</span></span>

- <span data-ttu-id="2e732-260">**Creare diagrammi di Visio chiari in Excel:** è possibile creare un diagramma di flussi o un organigramma inserendo i dati in un foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-260">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="2e732-261">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-261">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="2e732-262">**Analisi della scena del crimine:** è possibile usare i nuovi stencil Prova, Interni ed Esterni nel modello di indagine della scena del crimine per ricreare in dettaglio le scene del crimine.</span><span class="sxs-lookup"><span data-stu-id="2e732-262">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-263">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-263">Word</span></span>

- <span data-ttu-id="2e732-264">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="2e732-264">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="2e732-265">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-265">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="2e732-266">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="2e732-266">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="2e732-267">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-267">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="2e732-268">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="2e732-268">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="2e732-269">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="2e732-269">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="2e732-270">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-270">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="2e732-271">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="2e732-271">Find them at Insert > Icons.</span></span> [<span data-ttu-id="2e732-272">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-272">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="2e732-273">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="2e732-273">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="2e732-274">**Cancellare con precisione:** è possibile scegliere tra due dimensioni della gomma per correggere le piccole imperfezioni dell'input penna.</span><span class="sxs-lookup"><span data-stu-id="2e732-274">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="2e732-275">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-275">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="2e732-276">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="2e732-276">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="2e732-277">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="2e732-277">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="2e732-278">**Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nel documento, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="2e732-278">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="2e732-279">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-279">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="2e732-280">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="2e732-280">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="2e732-281">**Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="2e732-281">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="2e732-282">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-282">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="2e732-283">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="2e732-283">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="2e732-284">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-284">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="2e732-285">**Editor per curriculum unito all’Assistente curriculum LinkedIn:** l’editor per il curriculum offre una selezione di controlli grammaticali e stilistici appositamente studiati per i curriculum, per rendere la scrittura più precisa e professionale.</span><span class="sxs-lookup"><span data-stu-id="2e732-285">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="2e732-286">**Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.</span><span class="sxs-lookup"><span data-stu-id="2e732-286">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="2e732-287">**Risoluzione di un problema di danneggiamento di un documento causato dall'unione di oggetti 3D:** è stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.</span><span class="sxs-lookup"><span data-stu-id="2e732-287">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="2e732-288">**Miglioramenti alla creazione condivisa:** prestazioni migliorate per la creazione condivisa nei documenti di Word con revisioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-288">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="2e732-289">**Miglioramenti alla creazione condivisa:** maggiore affidabilità durante la creazione condivisa.</span><span class="sxs-lookup"><span data-stu-id="2e732-289">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="2e732-290">**Collaborare con colori vivaci:** i commenti e le modifiche sono contraddistinti da colori associati ai vari collaboratori, in modo che risulti facile identificarli.</span><span class="sxs-lookup"><span data-stu-id="2e732-290">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="2e732-291">**Modificare i documenti con attivazione macro in modo collaborativo:** è possibile salvare i file docm su OneDrive for Business e modificarli con i collaboratori in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="2e732-291">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-292">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-292">Office Suite</span></span>

- <span data-ttu-id="2e732-293">**Convertire l'input penna a mano libera in forme, testo o equazioni matematiche in PowerPoint per Office 365:** è possibile passare dall'input penna a mano libera al testo, a un'espressione matematica o alle forme di Office, con un paio di tratti.</span><span class="sxs-lookup"><span data-stu-id="2e732-293">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="2e732-294">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-294">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-297">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-297">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e732-298">Access</span><span class="sxs-lookup"><span data-stu-id="2e732-298">Access</span></span>

- <span data-ttu-id="2e732-299">Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB.</span><span class="sxs-lookup"><span data-stu-id="2e732-299">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="2e732-300">L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.</span><span class="sxs-lookup"><span data-stu-id="2e732-300">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="2e732-301">I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database.</span><span class="sxs-lookup"><span data-stu-id="2e732-301">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="2e732-302">Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.</span><span class="sxs-lookup"><span data-stu-id="2e732-302">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="2e732-303">Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="2e732-303">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="2e732-304">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo “Query danneggiata” quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="2e732-304">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2e732-305">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-305">Excel</span></span>

- <span data-ttu-id="2e732-306">Velocizzato il caricamento dei file disponibili nella cartella locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2e732-306">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="2e732-307">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.</span><span class="sxs-lookup"><span data-stu-id="2e732-307">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="2e732-308">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="2e732-308">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2e732-309">In alcuni casi, Excel si arrestava in modo anomalo alla riapertura di una cartella di lavoro incorporata in Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-309">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="2e732-310">È stato risolto un problema che impediva la visualizzazione dei comandi di commento nel menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="2e732-310">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="2e732-311">Tramite il menu di scelta rapida predefinito per i grafici pivot ora è possibile abilitare l'opzione Mostra dettagli.</span><span class="sxs-lookup"><span data-stu-id="2e732-311">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="2e732-312">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="2e732-312">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2e732-313">È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-313">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2e732-314">Durante il salvataggio in formato CSV, in alcuni casi Excel univa tutte le colonne in una singola colonna.</span><span class="sxs-lookup"><span data-stu-id="2e732-314">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="2e732-315">L'uso di Range.ClearContents in un intervallo in un foglio protetto poteva richiedere più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-315">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="2e732-316">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-316">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2e732-317">Le macro VBA che interagiscono con la barra multifunzione possono essere eseguite con ScreenUpdating inaspettatamente impostato su True.</span><span class="sxs-lookup"><span data-stu-id="2e732-317">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="2e732-318">È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="2e732-318">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="2e732-319">In alcuni casi, l'apertura di file CSV impiega più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-319">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="2e732-320">In alcuni casi, Excel potrebbe arrestarsi in modo anomalo quando si passa da una cartella di lavoro a un'altra con livelli di zoom diversi.</span><span class="sxs-lookup"><span data-stu-id="2e732-320">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="2e732-321">È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-321">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2e732-322">I dati copiati da una colonna filtrata in base al colore a volte non vengono incollati correttamente.</span><span class="sxs-lookup"><span data-stu-id="2e732-322">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="2e732-323">Aprire una cartella di lavoro con riferimenti a molte altre cartelle di lavoro, in particolare con finestre nascoste, risulta un'operazione piuttosto lenta.</span><span class="sxs-lookup"><span data-stu-id="2e732-323">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2e732-324">È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento (copia in basso o tra fogli di lavoro) se la cartella di lavoro di origine era& chiusa.</span><span class="sxs-lookup"><span data-stu-id="2e732-324">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="2e732-325">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="2e732-325">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2e732-326">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="2e732-326">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2e732-327">Risolve un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambia in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="2e732-327">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2e732-328">È stato risolto un problema per cui la personalizzazione CustomUI XML per la scheda della barra multifunzione veniva rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="2e732-328">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="2e732-329">Sono state migliorate le prestazioni associate all'eliminazione di colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="2e732-329">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="2e732-330">È stato risolto un problema che causava la ripetizione dei nomi delle stampanti nell'elenco all'interno della finestra di dialogo Stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-330">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="2e732-331">È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="2e732-331">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="2e732-332">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-332">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2e732-333">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="2e732-333">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2e732-334">L'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-334">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="2e732-335">È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappata invece che indirizzi universali.</span><span class="sxs-lookup"><span data-stu-id="2e732-335">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="2e732-336">È stato risolto un problema per cui veniva visualizzato il messaggio di errore "Questa cartella di lavoro non può essere chiusa in quanto esiste un'altra cartella di lavoro che fa riferimento ad essa", perché i componenti aggiuntivi venivano caricati in ordine alfabetico anziché in un ordine specificato dall'utente.</span><span class="sxs-lookup"><span data-stu-id="2e732-336">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="2e732-337">È stato risolto un problema per cui una cartella di lavoro poteva venire nascosta dopo aver fatto clic su un collegamento ipertestuale a un punto in una cartella di lavoro già aperta.</span><span class="sxs-lookup"><span data-stu-id="2e732-337">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="2e732-338">Aprire una cartella di lavoro con riferimenti a molte altre cartelle di lavoro, in particolare con finestre nascoste, risulta un'operazione piuttosto lenta.</span><span class="sxs-lookup"><span data-stu-id="2e732-338">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="2e732-339">L'uso di Application.Evaluate di VBA talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="2e732-339">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="2e732-340">È stato risolto un problema che alcuni utenti potrebbero aver riscontrato con oggetti incorporati e collegati (OLE).</span><span class="sxs-lookup"><span data-stu-id="2e732-340">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="2e732-341">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-341">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2e732-342">Questo aggiornamento risolve un problema per cui nella barra della formula veniva visualizzato del testo in un carattere diverso da quello previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-342">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="2e732-343">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-343">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2e732-344">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="2e732-344">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2e732-345">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="2e732-345">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2e732-346">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="2e732-346">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2e732-347">La funzionalità Testo in colonne può non funzionare per alcune localizzazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-347">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="2e732-348">Risolve un problema di prestazioni durante la creazione di grafici dai modelli.</span><span class="sxs-lookup"><span data-stu-id="2e732-348">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="2e732-349">È stato risolto un problema che causava arresti anomali durante la conversione del testo in colonne con celle dotate di una matrice con espansione.</span><span class="sxs-lookup"><span data-stu-id="2e732-349">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="2e732-350">Se si usa un Range.Value e un Range.Value2 (VBA), le formule vengono immesse come matrici dinamiche.</span><span class="sxs-lookup"><span data-stu-id="2e732-350">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="2e732-351">È stato risolto un problema per cui un simbolo @ che avvia una formula veniva considerato come operatore di intersezione implicito.</span><span class="sxs-lookup"><span data-stu-id="2e732-351">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="2e732-352">È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.</span><span class="sxs-lookup"><span data-stu-id="2e732-352">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="2e732-353">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="2e732-353">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2e732-354">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="2e732-354">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="2e732-355">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e732-355">OneNote</span></span>

- <span data-ttu-id="2e732-356">Migliora la sincronizzazione e la stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-356">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="2e732-357">Migliora la sincronizzazione e la stabilità del servizio rimandando temporaneamente il download di immagini e file incorporati in blocchi appunti online finché l'utente esplora la pagina in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-357">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="2e732-358">Migliora la sincronizzazione e la stabilità del servizio disabilitando temporaneamente il cestino in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-358">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="2e732-359">Quando un utente prova a eliminare dati che normalmente verrebbero spostati nel cestino, all'utente verrà chiesto se vuole mantenere o eliminare definitamente il file.</span><span class="sxs-lookup"><span data-stu-id="2e732-359">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="2e732-360">Migliora la sincronizzazione e la stabilità del servizio riducendo temporaneamente il numero e la frequenza di sincronizzazione delle pagine della cronologia versioni di OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-360">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="2e732-361">Visualizza una notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="2e732-361">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="2e732-362">Migliora la sincronizzazione e la stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-362">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="2e732-363">Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.</span><span class="sxs-lookup"><span data-stu-id="2e732-363">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="2e732-364">Migliora la sincronizzazione e la stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-364">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="2e732-365">I blocchi appunti locali non vengono interessati da questa operazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-365">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="2e732-366">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="2e732-366">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-367">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-367">Outlook</span></span>

- <span data-ttu-id="2e732-368">È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante inserito attraverso l’IME, quando venivano usati più monitor con risoluzioni diverse.</span><span class="sxs-lookup"><span data-stu-id="2e732-368">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="2e732-369">Risolve un problema per cui gli utenti visualizzavano arresti anomali occasionali in Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-369">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2e732-370">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="2e732-370">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2e732-371">Risolve un problema che causava l'accesso dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto. </span><span class="sxs-lookup"><span data-stu-id="2e732-371">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="2e732-372">Risolve un problema per cui appuntamenti o riunioni ricorrenti venivano visualizzati all’orario sbagliato quando era necessario cambiare la definizione del fuso orario.</span><span class="sxs-lookup"><span data-stu-id="2e732-372">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="2e732-373">Quando si usa il fuso orario di Brasilia nell'anno 2019, le riunioni e gli appuntamenti ricorrenti vengono visualizzati nella fascia oraria sbagliata per l'anno 2020.</span><span class="sxs-lookup"><span data-stu-id="2e732-373">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="2e732-374">Questa modifica è rilevante per i client configurati per il fuso orario di Brasilia o per le riunioni e gli appuntamenti impostati in tale fuso orario.</span><span class="sxs-lookup"><span data-stu-id="2e732-374">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="2e732-375">Questa modifica consente a Outlook di ignorare determinate impostazioni del fuso orario usate da Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-375">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="2e732-376">Per poter ignorare un fuso orario è necessario impostare una chiave del Registro di sistema per l'utente corrente.</span><span class="sxs-lookup"><span data-stu-id="2e732-376">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="2e732-377">Il nome della chiave del Registro di sistema deve corrispondere al nome interno del fuso orario.</span><span class="sxs-lookup"><span data-stu-id="2e732-377">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="2e732-378">Il valore indica l’anno della regola del fuso orario da usare al posto dell'anno effettivo.</span><span class="sxs-lookup"><span data-stu-id="2e732-378">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="2e732-379">Ad esempio, il seguente valore di override della chiave del Registro di sistema userà la regola del fuso orario di Brasilia per l'anno 2020 come regola effettiva.</span><span class="sxs-lookup"><span data-stu-id="2e732-379">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="2e732-380">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="2e732-380">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="2e732-381">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="2e732-381">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="2e732-382">Risolve un problema che causava la modifica imprevista del campo della sede nelle riunioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-382">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="2e732-383">Risolve un problema che causava l'aggiornamento imprevisto del campo Sede nelle riunioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-383">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="2e732-384">Risolve un problema per cui la sede di una riunione veniva inaspettatamente aggiunta di nuovo alla riunione dopo averla cancellata.</span><span class="sxs-lookup"><span data-stu-id="2e732-384">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="2e732-385">Risolve un problema per cui la virgola nel campo Sede della riunione cambiava in punto e virgola.</span><span class="sxs-lookup"><span data-stu-id="2e732-385">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="2e732-386">Consente di partecipare a una riunione di Teams direttamente tramite il client nativo di Teams.</span><span class="sxs-lookup"><span data-stu-id="2e732-386">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="2e732-387">Risolve un problema relativo all'aggiunta di allegati agli elementi del calendario per utenti con cassette postali sui server di Exchange 2010.</span><span class="sxs-lookup"><span data-stu-id="2e732-387">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="2e732-388">Risolve un problema relativo alla risposta a messaggi con firma digitale.</span><span class="sxs-lookup"><span data-stu-id="2e732-388">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="2e732-389">Risolve un problema che impediva agli utenti di aprire alcune istanze di elementi ricorrenti del calendario.</span><span class="sxs-lookup"><span data-stu-id="2e732-389">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="2e732-390">Risolve un problema che causava l'espansione improvvisa dell'intestazione del gruppo in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="2e732-390">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="2e732-391">Risolve un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="2e732-391">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="2e732-392">Risolve un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="2e732-392">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="2e732-393">Risolve un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="2e732-393">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2e732-394">Risolve un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.</span><span class="sxs-lookup"><span data-stu-id="2e732-394">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="2e732-395">Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'aggiornamento delle regole in Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-395">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="2e732-396">Risolve un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="2e732-396">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2e732-397">Risolve un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="2e732-397">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2e732-398">Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="2e732-398">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2e732-399">Risolve un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.</span><span class="sxs-lookup"><span data-stu-id="2e732-399">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="2e732-400">Risolve un problema che causava l'invio imprevisto di messaggi di posta elettronica quando gli utenti premevano il tasto “S” dopo aver chiuso il riquadro Verifica accessibilità.</span><span class="sxs-lookup"><span data-stu-id="2e732-400">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="2e732-401">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="2e732-401">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2e732-402">Risolve un problema che causava un arresto anomalo annullando la configurazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="2e732-402">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="2e732-403">Risolve un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.</span><span class="sxs-lookup"><span data-stu-id="2e732-403">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="2e732-404">Risolve un problema per cui gli utenti con il tema Nero visualizzavano l'elenco a discesa "Da" con il testo bianco su sfondo bianco.</span><span class="sxs-lookup"><span data-stu-id="2e732-404">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="2e732-405">Risolve un problema che causava un arresto anomalo durante la creazione del profilo.</span><span class="sxs-lookup"><span data-stu-id="2e732-405">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2e732-406">Risolve un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante “OK” quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="2e732-406">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2e732-407">Risolve un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante “OK” quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="2e732-407">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2e732-408">Risolve un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="2e732-408">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="2e732-409">Risolve un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="2e732-409">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="2e732-410">Risolve un problema che restituiva agli utenti di Outlook sui sistemi operativi del server l'errore: "Stato antivirus: non valido.</span><span class="sxs-lookup"><span data-stu-id="2e732-410">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="2e732-411">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun programma antivirus”, anche se l’antivirus è stato configurato in modo appropriato.</span><span class="sxs-lookup"><span data-stu-id="2e732-411">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="2e732-412">Risolve un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="2e732-412">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="2e732-413">Risolve un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un responsabile.</span><span class="sxs-lookup"><span data-stu-id="2e732-413">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="2e732-414">Risolve un problema che impediva agli utenti con l'impostazione errata dell'emulazione del browser di completare la richiesta di autenticazione di Gmail.</span><span class="sxs-lookup"><span data-stu-id="2e732-414">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="2e732-415">Risolve un problema per cui l'opzione “Consenti inoltro” non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="2e732-415">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="2e732-416">Risolve un problema che causava un arresto anomalo quando si cercava di aprire file .msg e .oft dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="2e732-416">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="2e732-417">Risolve un problema che causava un arresto anomalo occasionale quando veniva usato il pulsante X del mouse.</span><span class="sxs-lookup"><span data-stu-id="2e732-417">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2e732-418">Risolve un problema che causava un arresto anomalo quando venivano selezionati alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-418">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2e732-419">Risolve un problema che causava l'assenza del pulsante Salva nel cloud in Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="2e732-419">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2e732-420">Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.</span><span class="sxs-lookup"><span data-stu-id="2e732-420">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="2e732-421">Risolve un problema che causava un arresto anomalo quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo della barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="2e732-421">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="2e732-422">Risolve un problema che causava la mancata aggiunta di collegamenti ai messaggi di posta elettronica con l'autorizzazione predefinita del tenant corretta quando questa era configurata su "chiunque".</span><span class="sxs-lookup"><span data-stu-id="2e732-422">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="2e732-423">Risolve un problema che impediva agli utenti di inviare messaggi di posta elettronica a una lista di distribuzione personale.</span><span class="sxs-lookup"><span data-stu-id="2e732-423">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="2e732-424">Risolve un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-424">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2e732-425">È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="2e732-425">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2e732-426">È stato risolto un problema che poteva impedire il salvataggio di file in una posizione WebDAV.</span><span class="sxs-lookup"><span data-stu-id="2e732-426">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="2e732-427">Risolve un problema che impediva agli utenti di salvare gli allegati di OneDrive dall'esterno del tenant al computer locale selezionando l'opzione "Salva" nella finestra di dialogo relativa alla sicurezza.</span><span class="sxs-lookup"><span data-stu-id="2e732-427">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="2e732-428">Risolve un problema per cui il corpo di un messaggio NDR passava da Unicode a ASCII dopo aver modificato l'oggetto.</span><span class="sxs-lookup"><span data-stu-id="2e732-428">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="2e732-429">Risolve un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-429">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2e732-430">È stato risolto un problema per cui gli utenti vedevano i messaggi di posta elettronica inviati a un indirizzo che in alcuni casi non corrispondeva all'indirizzo SMTP visualizzato.</span><span class="sxs-lookup"><span data-stu-id="2e732-430">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="2e732-431">Risolve un problema che causava l’errato allineamento della casella di ricerca in modalità dpi elevato.</span><span class="sxs-lookup"><span data-stu-id="2e732-431">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="2e732-432">Risolve un problema che causava il blocco di Outlook durante il recupero delle impostazioni del cloud.</span><span class="sxs-lookup"><span data-stu-id="2e732-432">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="2e732-433">Risolve un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-433">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2e732-434">Risolve un problema per cui gli utenti visualizzavano arresti anomali occasionali in Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-434">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="2e732-435">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="2e732-435">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="2e732-436">Risolve un problema che causava un arresto anomalo durante la creazione del profilo.</span><span class="sxs-lookup"><span data-stu-id="2e732-436">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="2e732-437">Risolve un problema per cui gli utenti visualizzavano arresti anomali occasionali in Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-437">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e732-438">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-438">PowerPoint</span></span>

- <span data-ttu-id="2e732-439">È stato risolto un problema che potrebbe aver causato un arresto anomalo durante l’utilizzo del menu di scelta rapida nei commenti PPT legacy.</span><span class="sxs-lookup"><span data-stu-id="2e732-439">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="2e732-440">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="2e732-440">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2e732-441">Risolve un problema relativo all'inoltro della messaggistica corretta per gli utenti che aprono una copia di un file con commenti migliorati.</span><span class="sxs-lookup"><span data-stu-id="2e732-441">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="2e732-442">Project</span><span class="sxs-lookup"><span data-stu-id="2e732-442">Project</span></span>

- <span data-ttu-id="2e732-443">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="2e732-443">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="2e732-444">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="2e732-444">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="2e732-445">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.</span><span class="sxs-lookup"><span data-stu-id="2e732-445">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="2e732-446">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-446">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="2e732-447">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura</span><span class="sxs-lookup"><span data-stu-id="2e732-447">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="2e732-448">È stato risolto un problema per cui il 100% delle attività di tipo a durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.</span><span class="sxs-lookup"><span data-stu-id="2e732-448">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-449">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-449">Word</span></span>

- <span data-ttu-id="2e732-450">Risolve un problema che causava un arresto anomalo occasionale quando veniva usato il pulsante X del mouse.</span><span class="sxs-lookup"><span data-stu-id="2e732-450">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="2e732-451">È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.</span><span class="sxs-lookup"><span data-stu-id="2e732-451">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="2e732-452">È stato risolto un problema relativo all'adattamento del testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="2e732-452">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="2e732-453">È stato risolto un problema per cui le righe orizzontali inserite non sono più brevi e centrate.</span><span class="sxs-lookup"><span data-stu-id="2e732-453">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="2e732-454">Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: "Sono stati modificati gli stili, i blocchi predefiniti".</span><span class="sxs-lookup"><span data-stu-id="2e732-454">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="2e732-455">È stato risolto un problema relativo alla creazione condivisa abilitando il criterio FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="2e732-455">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="2e732-456">È stato risolto un problema per cui le parti rapide di Word non funzionavano aggiungendo un campo di ricerca rinominato.</span><span class="sxs-lookup"><span data-stu-id="2e732-456">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="2e732-457">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="2e732-457">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2e732-458">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="2e732-458">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2e732-459">Questo aggiornamento consente di risolvere un problema di Microsoft Word per il quale un testo più lungo di 255 caratteri inserito durante l'applicazione di un'etichetta di riservatezza non può essere identificato e rimosso in seguito modificando o rimuovendo l'etichetta se il criterio di etichetta applica un'intestazione, un piè di pagina o una filigrana.</span><span class="sxs-lookup"><span data-stu-id="2e732-459">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-460">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-460">Office Suite</span></span>

- <span data-ttu-id="2e732-461">È stato risolto un problema per cui gli utenti riscontravano un utilizzo eccessivo della rete e della CPU durante la creazione condivisa in file di PowerPoint di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-461">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="2e732-462">Si tratta di una soluzione per il blocco della rete da parte dell'app di Project quando il file viene memorizzato nella cache del client.</span><span class="sxs-lookup"><span data-stu-id="2e732-462">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="2e732-463">Il problema è stato risolto aggiornando i nomi dei canali nella visualizzazione backstage ai nuovi nomi dei canali nel fork 2020 gennaio.</span><span class="sxs-lookup"><span data-stu-id="2e732-463">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="2e732-464">Il problema è stato risolto e in futuro, se un dispositivo viene gestito da criteri, non chiamerà l'API DMS Audience.</span><span class="sxs-lookup"><span data-stu-id="2e732-464">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="2e732-465">È stato risolto il problema relativo alla rimozione incompleta nell'ambito dell'aggiunta e della rimozione di app in una singola operazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-465">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="2e732-466">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-466">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2e732-467">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2e732-467">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2e732-468">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-468">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2e732-469">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="2e732-469">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="2e732-470">Il problema è stato risolto quando un'operazione interna genera un'eccezione in caso di errore anziché registrare e continuare.</span><span class="sxs-lookup"><span data-stu-id="2e732-470">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="2e732-471">Gli utenti interessati non riscontreranno più il blocco della ricezione degli aggiornamenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-471">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="2e732-472">Il team ha aggiunto il supporto client per la creazione di report di telemetria sui domini CDN di Office nell'anteprima aziendale semestrale.</span><span class="sxs-lookup"><span data-stu-id="2e732-472">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="2e732-473">Questa modifica risolve i problemi con gli adattatori grafici che sfruttano la GPU integrata Intel.</span><span class="sxs-lookup"><span data-stu-id="2e732-473">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="2e732-474">Ciò assicura che la struttura disegnata funzioni correttamente nella barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="2e732-474">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="2e732-475">È stato risolto un problema che si verificava durante l'apertura di file da posizioni locali con alcune configurazioni proxy specifiche.</span><span class="sxs-lookup"><span data-stu-id="2e732-475">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="2e732-476">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-476">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2e732-477">È stato risolto un problema che causa l'arresto anomalo durante le sessioni di handoff di Office ed è stata migliorata l'affidabilità dell'esperienza utente.</span><span class="sxs-lookup"><span data-stu-id="2e732-477">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="2e732-478">Questo bug aggiorna l'endpoint url di Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="2e732-478">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="2e732-479">Richiamare questo nuovo endpoint ha un tasso di successo maggiore per recuperare dati dall'ECS.</span><span class="sxs-lookup"><span data-stu-id="2e732-479">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="2e732-480">Questo aggiornamento consente di risolvere un problema per cui Microsoft Outlook non visualizza l'etichetta di riservatezza corrente durante la visualizzazione o la creazione di messaggi.</span><span class="sxs-lookup"><span data-stu-id="2e732-480">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="2e732-481">È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.</span><span class="sxs-lookup"><span data-stu-id="2e732-481">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="2e732-482">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="2e732-482">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2e732-483">L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="2e732-483">The office host was crashing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="2e732-484">La modifica può risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="2e732-484">This change would fix this issue.</span></span>

- <span data-ttu-id="2e732-485">È stato risolto un problema di arresto anomalo con l'host di Office in Windows quando un componente aggiuntivo veniva attivato mentre il valore del registro TabProcGrowth era di tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="2e732-485">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="2e732-486">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="2e732-486">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="2e732-487">È stato risolto il problema per cui Access e Publisher potevano non venire avviati correttamente a seconda delle lingue installate.</span><span class="sxs-lookup"><span data-stu-id="2e732-487">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)





[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-july-14"></a><span data-ttu-id="2e732-490">Versione 1908: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="2e732-490">Version 1908: July 14</span></span>
<span data-ttu-id="2e732-491">*Versione 1908 (Build 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="2e732-491">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="2e732-492">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-492">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-494">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-494">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e732-495">Access</span><span class="sxs-lookup"><span data-stu-id="2e732-495">Access</span></span>

- <span data-ttu-id="2e732-496">Questo aggiornamento risolve un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.</span><span class="sxs-lookup"><span data-stu-id="2e732-496">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2e732-497">Questo aggiornamento risolve un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.</span><span class="sxs-lookup"><span data-stu-id="2e732-497">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2e732-498">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo “Query danneggiata” quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="2e732-498">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2e732-499">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-499">Excel</span></span>

- <span data-ttu-id="2e732-500">Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt-G.</span><span class="sxs-lookup"><span data-stu-id="2e732-500">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2e732-501">È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.</span><span class="sxs-lookup"><span data-stu-id="2e732-501">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2e732-502">È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-502">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2e732-503">Questo aggiornamento risolve un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-503">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2e732-504">Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal cubo.</span><span class="sxs-lookup"><span data-stu-id="2e732-504">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2e732-505">Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.</span><span class="sxs-lookup"><span data-stu-id="2e732-505">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2e732-506">È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie</span><span class="sxs-lookup"><span data-stu-id="2e732-506">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="2e732-507">Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.</span><span class="sxs-lookup"><span data-stu-id="2e732-507">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2e732-508">È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.</span><span class="sxs-lookup"><span data-stu-id="2e732-508">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2e732-509">È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-509">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2e732-510">È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.</span><span class="sxs-lookup"><span data-stu-id="2e732-510">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2e732-511">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="2e732-511">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2e732-512">È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-512">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2e732-513">È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.</span><span class="sxs-lookup"><span data-stu-id="2e732-513">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2e732-514">È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="2e732-514">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2e732-515">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="2e732-515">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2e732-516">È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.</span><span class="sxs-lookup"><span data-stu-id="2e732-516">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2e732-517">È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.</span><span class="sxs-lookup"><span data-stu-id="2e732-517">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="2e732-518">È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="2e732-518">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2e732-519">È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-519">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2e732-520">Risolve un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambia in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="2e732-520">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2e732-521">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="2e732-521">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="2e732-522">È stato risolto un problema che causava il rallentamento delle prestazioni quando si eliminavano colonne contenenti celle unite.</span><span class="sxs-lookup"><span data-stu-id="2e732-522">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2e732-523">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-523">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="2e732-524">Quando si copiavano dati filtrati in base al colore in una colonna di larghezza differente, i valori non venivano incollati.</span><span class="sxs-lookup"><span data-stu-id="2e732-524">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="2e732-525">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="2e732-525">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2e732-526">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-526">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2e732-527">È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-527">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="2e732-528">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "Cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="2e732-528">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="2e732-529">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><span class="sxs-lookup"><span data-stu-id="2e732-529">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="2e732-530">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="2e732-530">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="2e732-531">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-531">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2e732-532">È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.</span><span class="sxs-lookup"><span data-stu-id="2e732-532">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="2e732-533">Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-533">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2e732-534">Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="2e732-534">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2e732-535">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="2e732-535">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2e732-536">È stato risolto un problema per cui la funzione Cerca restituiva un errore.</span><span class="sxs-lookup"><span data-stu-id="2e732-536">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2e732-537">È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.</span><span class="sxs-lookup"><span data-stu-id="2e732-537">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2e732-538">È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.</span><span class="sxs-lookup"><span data-stu-id="2e732-538">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="2e732-539">Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.</span><span class="sxs-lookup"><span data-stu-id="2e732-539">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2e732-540">È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.</span><span class="sxs-lookup"><span data-stu-id="2e732-540">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2e732-541">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="2e732-541">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2e732-542">Sono state notevolmente migliorate le prestazioni del filtro per colore.</span><span class="sxs-lookup"><span data-stu-id="2e732-542">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2e732-543">È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.</span><span class="sxs-lookup"><span data-stu-id="2e732-543">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2e732-544">Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-544">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2e732-545">È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.</span><span class="sxs-lookup"><span data-stu-id="2e732-545">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2e732-546">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="2e732-546">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2e732-547">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-547">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-548">Questo aggiornamento corregge un errore in cui il caricamento dei documenti di Office in OneDrive for Business potrebbe avere esito negativo con il messaggio "Caricamento non riuscito".</span><span class="sxs-lookup"><span data-stu-id="2e732-548">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2e732-549">È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.</span><span class="sxs-lookup"><span data-stu-id="2e732-549">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="2e732-550">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e732-550">OneNote</span></span>

- <span data-ttu-id="2e732-551">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="2e732-551">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-552">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-552">Outlook</span></span>

- <span data-ttu-id="2e732-553">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-553">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-554">È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-554">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2e732-555">Risolve un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.</span><span class="sxs-lookup"><span data-stu-id="2e732-555">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2e732-556">Risolve un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="2e732-556">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2e732-557">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="2e732-557">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2e732-558">Risolve un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-558">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2e732-559">Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="2e732-559">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2e732-560">Risolve un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.</span><span class="sxs-lookup"><span data-stu-id="2e732-560">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2e732-561">Risolve un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="2e732-561">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2e732-562">Risolve un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="2e732-562">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2e732-563">Risolve un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="2e732-563">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2e732-564">Risolve un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="2e732-564">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2e732-565">Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="2e732-565">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2e732-566">Risolve un problema che causava un arresto anomalo di Outlook durante l'interazione con determinati collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="2e732-566">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2e732-567">Risolve un problema che causava ambiguità per i responsabili circa il fatto che un delegato avesse già risposto o meno a una determinata convocazione di riunione.</span><span class="sxs-lookup"><span data-stu-id="2e732-567">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2e732-568">Risolve un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="2e732-568">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2e732-569">Risolve un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante “OK” quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="2e732-569">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2e732-570">Questa modifica consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN.</span><span class="sxs-lookup"><span data-stu-id="2e732-570">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2e732-571">Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.</span><span class="sxs-lookup"><span data-stu-id="2e732-571">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2e732-572">Risolve un problema che causava il malfunzionamento della ricerca in Gruppi moderni.</span><span class="sxs-lookup"><span data-stu-id="2e732-572">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2e732-573">Risolve un problema che bloccava gli utenti di Outlook nello stato "Password necessaria" in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="2e732-573">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2e732-574">Risolve un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.</span><span class="sxs-lookup"><span data-stu-id="2e732-574">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2e732-575">Risolve un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="2e732-575">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2e732-576">Risolve un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-576">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2e732-577">Risolve un problema che causava un arresto anomalo quando venivano selezionati alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-577">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2e732-578">Risolve un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="2e732-578">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2e732-579">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-579">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2e732-580">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="2e732-580">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2e732-581">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = default 1 = verrà mostrato solo il NomeCriterio nel testo dei criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-581">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="2e732-582">Risolve un problema che causava un arresto anomalo durante la chiusura di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-582">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2e732-583">Risolve un problema che causava la visualizzazione di un elenco sale vuoto in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="2e732-583">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="2e732-584">Risolve un problema che causava arresti anomali intermittenti cambiando visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-584">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="2e732-585">È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.</span><span class="sxs-lookup"><span data-stu-id="2e732-585">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="2e732-586">Risolve un problema che causa l'arresto anomalo quando si visualizzano più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="2e732-586">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2e732-587">Qui è disponibile il singolo [articolo della Knowledge Base in cui è stato documentato per le versioni precedenti](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen).</span><span class="sxs-lookup"><span data-stu-id="2e732-587">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/en-us/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="2e732-588">Risolve un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="2e732-588">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2e732-589">Risolve un problema che causava la mancata visualizzazione di Suggerimenti per i criteri usando un mittente alternativo.</span><span class="sxs-lookup"><span data-stu-id="2e732-589">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2e732-590">Risolve un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.</span><span class="sxs-lookup"><span data-stu-id="2e732-590">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2e732-591">È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.</span><span class="sxs-lookup"><span data-stu-id="2e732-591">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2e732-592">Risolve un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo "Conversazione non effettuata".</span><span class="sxs-lookup"><span data-stu-id="2e732-592">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2e732-593">Risolve un problema per cui alcuni utenti visualizzavano cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="2e732-593">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2e732-594">Risolve un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-594">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="2e732-595">Risolve un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-595">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2e732-596">Risolve un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-596">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2e732-597">Risolve un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.</span><span class="sxs-lookup"><span data-stu-id="2e732-597">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2e732-598">Risolve un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-598">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2e732-599">Risolve un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-599">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2e732-600">Risolve un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="2e732-600">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2e732-601">Risolve un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-601">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e732-602">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-602">PowerPoint</span></span>

- <span data-ttu-id="2e732-603">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-603">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-604">Questa modifica ripristina il nome accessibile per i controlli video di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-604">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2e732-605">È stato risolto un problema che impediva l'avvio di alcune animazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-605">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="2e732-606">È stato risolto un problema che causava la creazione di schemi duplicati quando si copiava una diapositiva da una presentazione a un'altra.</span><span class="sxs-lookup"><span data-stu-id="2e732-606">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="2e732-607">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="2e732-607">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="2e732-608">È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.</span><span class="sxs-lookup"><span data-stu-id="2e732-608">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="2e732-609">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata.</span><span class="sxs-lookup"><span data-stu-id="2e732-609">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="2e732-610">È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-610">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2e732-611">Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti poteva causare l'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-611">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2e732-612">È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.</span><span class="sxs-lookup"><span data-stu-id="2e732-612">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2e732-613">È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.</span><span class="sxs-lookup"><span data-stu-id="2e732-613">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="2e732-614">È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-614">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="2e732-615">È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.</span><span class="sxs-lookup"><span data-stu-id="2e732-615">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2e732-616">Impedisce un errore in PowerPoint quando si prova a presentare online.</span><span class="sxs-lookup"><span data-stu-id="2e732-616">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="2e732-617">Project</span><span class="sxs-lookup"><span data-stu-id="2e732-617">Project</span></span>

- <span data-ttu-id="2e732-618">È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-618">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2e732-619">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="2e732-619">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2e732-620">Il comando Livella tutte non risolve correttamente una sovrassegnazione della risorsa.</span><span class="sxs-lookup"><span data-stu-id="2e732-620">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2e732-621">In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-621">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="2e732-622">È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.</span><span class="sxs-lookup"><span data-stu-id="2e732-622">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="2e732-623">Skype</span><span class="sxs-lookup"><span data-stu-id="2e732-623">Skype</span></span>

- <span data-ttu-id="2e732-624">È stato risolto un problema relativo al nome titolo per la conversazione su schede mentre erano in corso più conversazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-624">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="2e732-625">Visio</span><span class="sxs-lookup"><span data-stu-id="2e732-625">Visio</span></span>

- <span data-ttu-id="2e732-626">L'esportazione in SVG da Visio non funzionava per numerose forme.</span><span class="sxs-lookup"><span data-stu-id="2e732-626">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-627">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-627">Word</span></span>

- <span data-ttu-id="2e732-628">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-628">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-629">È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet</span><span class="sxs-lookup"><span data-stu-id="2e732-629">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="2e732-630">È stato risolto un problema relativo all’adattamento del testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="2e732-630">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="2e732-631">È stato risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.</span><span class="sxs-lookup"><span data-stu-id="2e732-631">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2e732-632">È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="2e732-632">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="2e732-633">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="2e732-633">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2e732-634">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="2e732-634">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="2e732-635">Risolve diversi problemi che causavano il blocco dell'app durante la chiusura.</span><span class="sxs-lookup"><span data-stu-id="2e732-635">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2e732-636">Sono stati risolti anche alcuni arresti anomali correlati ai componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-636">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-637">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="2e732-637">Office Suite</span></span>

- <span data-ttu-id="2e732-638">Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.</span><span class="sxs-lookup"><span data-stu-id="2e732-638">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2e732-639">È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-639">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2e732-640">È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-640">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2e732-641">Si tratta di una correzione per un problema che causava un arresto anomalo all'apertura di un file.</span><span class="sxs-lookup"><span data-stu-id="2e732-641">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2e732-642">In alcuni casi, un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica, comportando una perdita di dati.</span><span class="sxs-lookup"><span data-stu-id="2e732-642">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2e732-643">È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-643">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2e732-644">Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="2e732-644">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2e732-645">Risolve un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="2e732-645">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="2e732-646">È in corso la risoluzione di un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-646">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="2e732-647">È stato risolto un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.</span><span class="sxs-lookup"><span data-stu-id="2e732-647">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2e732-648">È stato risolto un bug per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.</span><span class="sxs-lookup"><span data-stu-id="2e732-648">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2e732-649">Migliora l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.</span><span class="sxs-lookup"><span data-stu-id="2e732-649">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2e732-650">I nomi dei canali per i fork gennaio e luglio 2019 sono stati aggiornati ai nuovi nomi di canale.</span><span class="sxs-lookup"><span data-stu-id="2e732-650">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2e732-651">Risolve un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.</span><span class="sxs-lookup"><span data-stu-id="2e732-651">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2e732-652">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-652">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2e732-653">In alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-653">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2e732-654">Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.</span><span class="sxs-lookup"><span data-stu-id="2e732-654">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2e732-655">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2e732-655">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2e732-656">Risolve un problema per cui, in alcuni casi, un aggiornamento non veniva applicato se l'utente non era un amministratore e non era disponibile la connettività di rete per l'account di sistema.</span><span class="sxs-lookup"><span data-stu-id="2e732-656">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2e732-657">È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-657">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2e732-658">In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.</span><span class="sxs-lookup"><span data-stu-id="2e732-658">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2e732-659">È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-659">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2e732-660">Risolvere problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.</span><span class="sxs-lookup"><span data-stu-id="2e732-660">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2e732-661">Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.</span><span class="sxs-lookup"><span data-stu-id="2e732-661">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="2e732-662">Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span><span class="sxs-lookup"><span data-stu-id="2e732-662">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="2e732-663">È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo</span><span class="sxs-lookup"><span data-stu-id="2e732-663">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="2e732-664">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-664">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="2e732-665">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="2e732-665">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="2e732-666">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="2e732-666">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-july-14"></a><span data-ttu-id="2e732-668">Versione 1902: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="2e732-668">Version 1902: July 14</span></span>
<span data-ttu-id="2e732-669">*Versione 1902 (Build 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="2e732-669">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="2e732-670">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-670">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="2e732-671">Versione 1908: 09 giugno</span><span class="sxs-lookup"><span data-stu-id="2e732-671">Version 1908: June 09</span></span>
<span data-ttu-id="2e732-672">*Versione 1908 (Build 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="2e732-672">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="2e732-673">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-673">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-675">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-675">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-676">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-676">Excel</span></span>

- <span data-ttu-id="2e732-677">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="2e732-677">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="2e732-678">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-678">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="2e732-679">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="2e732-679">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-680">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-680">Outlook</span></span>

- <span data-ttu-id="2e732-681">È stato risolto un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-681">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-682">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="2e732-682">Office Suite</span></span>

- <span data-ttu-id="2e732-683">I nomi dei canali sono stati aggiornati per i fork gennaio e luglio 2019 ai nuovi nomi di canale.</span><span class="sxs-lookup"><span data-stu-id="2e732-683">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-june-09"></a><span data-ttu-id="2e732-685">Versione 1902: 09 giugno</span><span class="sxs-lookup"><span data-stu-id="2e732-685">Version 1902: June 09</span></span>
<span data-ttu-id="2e732-686">*Versione 1902 (Build 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="2e732-686">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="2e732-687">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-687">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-689">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-689">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2e732-690">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="2e732-690">Office Suite</span></span>

- <span data-ttu-id="2e732-691">I nomi dei canali sono stati aggiornati per i fork gennaio e luglio 2019 ai nuovi nomi di canale.</span><span class="sxs-lookup"><span data-stu-id="2e732-691">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="2e732-692">Sono stati rimossi riferimenti obsoleti dai file di base che stavano interrompendo la build C2R.</span><span class="sxs-lookup"><span data-stu-id="2e732-692">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-12"></a><span data-ttu-id="2e732-694">Versione 1908: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="2e732-694">Version 1908: May 12</span></span>
<span data-ttu-id="2e732-695">*Versione 1908 (Build 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="2e732-695">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="2e732-696">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-696">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-698">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-698">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-699">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-699">Excel</span></span>

- <span data-ttu-id="2e732-700">Quando si copiavano dati filtrati in base al colore in una colonna di larghezza differente, i valori non venivano incollati.</span><span class="sxs-lookup"><span data-stu-id="2e732-700">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-701">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-701">Outlook</span></span>

- <span data-ttu-id="2e732-702">È stato risolto un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="2e732-702">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-703">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-703">Word</span></span>

- <span data-ttu-id="2e732-704">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="2e732-704">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="2e732-705">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="2e732-705">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-may-12"></a><span data-ttu-id="2e732-707">Versione 1902: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="2e732-707">Version 1902: May 12</span></span>
<span data-ttu-id="2e732-708">*Versione 1902 (Build 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="2e732-708">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="2e732-709">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-709">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-711">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-711">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e732-712">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-712">Outlook</span></span>

- <span data-ttu-id="2e732-713">È stato risolto un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="2e732-713">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="2e732-714">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-714">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="2e732-715">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="2e732-715">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="2e732-716">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="2e732-716">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="2e732-717">0 = Predefinito.</span><span class="sxs-lookup"><span data-stu-id="2e732-717">0 = Default.</span></span>  <span data-ttu-id="2e732-718">1 = Verrà visualizzato solo il NomeCriterio nel testo dei criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-718">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-1908-may-04"></a><span data-ttu-id="2e732-720">Versione 1908: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="2e732-720">Version 1908: May 04</span></span>
<span data-ttu-id="2e732-721">*Versione 1908 (build 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="2e732-721">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="2e732-722">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-722">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2e732-723">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-723">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e732-724">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-724">Outlook</span></span>

- <span data-ttu-id="2e732-725">È stato risolto un problema che causava un arresto anomalo selezionando alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-725">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="2e732-726">È stato risolto un problema che causava l'assenza del pulsante Salva nel cloud da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="2e732-726">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="2e732-727">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-727">By default, retention policy labels display the retention time period in parenthesis.</span></span><span data-ttu-id="2e732-728">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="2e732-728"> This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span><span data-ttu-id="2e732-729"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="2e732-729"> HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span><span data-ttu-id="2e732-730"> 0 = predefinito 1 = verrò visualizzato solo il nomecriterio per il testo del criterio di conservazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-730"> 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-731">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="2e732-731">Office Suite</span></span>

- <span data-ttu-id="2e732-732">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-732">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="2e732-733">Versione 1902: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="2e732-733">Version 1902: May 04</span></span>
<span data-ttu-id="2e732-734">*Versione 1902 (build 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="2e732-734">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2e732-735">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-735">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="2e732-736">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-736">Office Suite</span></span>

- <span data-ttu-id="2e732-737">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-737">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version1908april-26"></a><span data-ttu-id="2e732-738">Versione 1908: 26 aprile</span><span class="sxs-lookup"><span data-stu-id="2e732-738">Version 1908: April 26</span></span>
<span data-ttu-id="2e732-739">*Versione 1908 (Build 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="2e732-739">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="2e732-740">Aggiornamenti della sicurezza elencati  [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-740">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="2e732-741">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-741">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-742">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-742">Excel</span></span>

- <span data-ttu-id="2e732-743">È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell'utilizzo di una macro VBA per eliminare il contenuto di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="2e732-743">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="2e732-744">È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-744">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="2e732-745">È stato risolto un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambiava in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="2e732-745">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="2e732-746">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="2e732-746">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="2e732-747">OneNote</span><span class="sxs-lookup"><span data-stu-id="2e732-747">OneNote</span></span>

- <span data-ttu-id="2e732-748">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="2e732-748">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="2e732-749">Versione 1908: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="2e732-749">Version 1908: April 14</span></span>
<span data-ttu-id="2e732-750">*Versione 1908 (Build 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="2e732-750">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="2e732-751">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-751">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-753">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-753">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-754">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-754">Excel</span></span>

- <span data-ttu-id="2e732-755">È stato risolto un problema che causava il rallentamento delle prestazioni quando si eliminavano colonne contenenti celle unite.</span><span class="sxs-lookup"><span data-stu-id="2e732-755">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="2e732-756">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="2e732-756">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="2e732-757">Skype</span><span class="sxs-lookup"><span data-stu-id="2e732-757">Skype</span></span>

- <span data-ttu-id="2e732-758">È stato risolto un problema relativo al nome titolo per la conversazione su schede mentre erano in corso più conversazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-758">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-759">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-759">Outlook</span></span>

- <span data-ttu-id="2e732-760">È stato risolto un problema che causava un arresto anomalo durante l'arresto di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-760">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="2e732-761">È stato risolto un problema che causava la visualizzazione di un elenco sale vuoto in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="2e732-761">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e732-762">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-762">PowerPoint</span></span>

- <span data-ttu-id="2e732-763">È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.</span><span class="sxs-lookup"><span data-stu-id="2e732-763">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-764">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-764">Word</span></span>

- <span data-ttu-id="2e732-765">È stato risolto un problema relativo ad Adatta testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="2e732-765">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="2e732-766">Versione 1902: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="2e732-766">Version 1902: April 14</span></span>
<span data-ttu-id="2e732-767">*Versione 1902 (Build 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="2e732-767">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="2e732-768">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-768">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="2e732-770">Versione 1908: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="2e732-770">Version 1908: March 10</span></span>
<span data-ttu-id="2e732-771">*Versione 1908 (Build 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="2e732-771">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="2e732-772">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-772">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-774">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-774">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-775">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-775">Excel</span></span>

- <span data-ttu-id="2e732-776">È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato la presenza di più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.</span><span class="sxs-lookup"><span data-stu-id="2e732-776">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="2e732-777">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><span class="sxs-lookup"><span data-stu-id="2e732-777">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="2e732-778">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="2e732-778">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e732-779">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-779">PowerPoint</span></span>

- <span data-ttu-id="2e732-780">È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.</span><span class="sxs-lookup"><span data-stu-id="2e732-780">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="2e732-781">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-781">Word</span></span>

- <span data-ttu-id="2e732-782">È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="2e732-782">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="2e732-783">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="2e732-783">Office Suite</span></span>

- <span data-ttu-id="2e732-784">Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span><span class="sxs-lookup"><span data-stu-id="2e732-784">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="2e732-785">Versione 1902: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="2e732-785">Version 1902: March 10</span></span>
<span data-ttu-id="2e732-786">*Versione 1902 (Build 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="2e732-786">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="2e732-787">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-787">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="2e732-789">Versione 1908: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="2e732-789">Version 1908: February 11</span></span>
<span data-ttu-id="2e732-790">*Versione 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="2e732-790">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="2e732-791">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-791">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-793">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-793">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-794">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-794">Excel</span></span>

- <span data-ttu-id="2e732-795">Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.</span><span class="sxs-lookup"><span data-stu-id="2e732-795">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="2e732-796">È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.</span><span class="sxs-lookup"><span data-stu-id="2e732-796">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="2e732-797">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="2e732-797">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="2e732-798">È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.</span><span class="sxs-lookup"><span data-stu-id="2e732-798">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="2e732-799">È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.</span><span class="sxs-lookup"><span data-stu-id="2e732-799">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="2e732-800">È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.</span><span class="sxs-lookup"><span data-stu-id="2e732-800">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="2e732-801">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-801">Outlook</span></span>

- <span data-ttu-id="2e732-802">È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="2e732-802">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="2e732-803">È stato risolto un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.</span><span class="sxs-lookup"><span data-stu-id="2e732-803">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="2e732-804">È stato risolto un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-804">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="2e732-805">È stato risolto un problema che causava arresti anomali intermittenti cambiando visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-805">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="2e732-806">È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="2e732-806">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="2e732-807">[Qui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) è disponibile il singolo articolo della Knowledge Basa in cui è stato documentato per le versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-807">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="2e732-808">È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.</span><span class="sxs-lookup"><span data-stu-id="2e732-808">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="2e732-809">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-809">PowerPoint</span></span>

- <span data-ttu-id="2e732-810">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="2e732-810">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="2e732-811">È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-811">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="2e732-812">È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.</span><span class="sxs-lookup"><span data-stu-id="2e732-812">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="2e732-813">È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-813">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2e732-814">Project</span><span class="sxs-lookup"><span data-stu-id="2e732-814">Project</span></span>

- <span data-ttu-id="2e732-815">È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.</span><span class="sxs-lookup"><span data-stu-id="2e732-815">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-816">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-816">Word</span></span>

- <span data-ttu-id="2e732-817">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="2e732-817">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-818">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-818">Office Suite</span></span>

- <span data-ttu-id="2e732-819">Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.</span><span class="sxs-lookup"><span data-stu-id="2e732-819">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="2e732-821">Versione 1902: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="2e732-821">Version 1902: February 11</span></span>
<span data-ttu-id="2e732-822">*Versione 1902 (Build 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="2e732-822">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="2e732-823">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-823">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-825">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-825">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="2e732-826">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-826">Outlook</span></span>

- <span data-ttu-id="2e732-827">Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="2e732-827">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="2e732-828">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-828">Word</span></span>

- <span data-ttu-id="2e732-829">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="2e732-829">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="2e732-832">Versione 1808: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="2e732-832">Version 1808: February 11</span></span>
<span data-ttu-id="2e732-833">*Versione 1808 (Build 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="2e732-833">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="2e732-834">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-834">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="2e732-836">Versione 1908: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="2e732-836">Version 1908: January 14</span></span>
<span data-ttu-id="2e732-837">*Versione 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="2e732-837">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="2e732-838">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-838">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="2e732-840">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="2e732-840">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="2e732-841">Access</span><span class="sxs-lookup"><span data-stu-id="2e732-841">Access</span></span>

- <span data-ttu-id="2e732-842">**Monitorare gli oggetti di database:** visualizzare chiaramente la scheda attiva, trascinare facilmente le schede per disporle in modo diverso e chiudere gli oggetti di database con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="2e732-842">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="2e732-843">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="2e732-843">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2e732-844">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="2e732-844">Switching between them has never been easier.</span></span> [<span data-ttu-id="2e732-845">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-845">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2e732-846">**Zoom con più spazio:** ingrandire la casella Zoom e cambiare il tipo di carattere. Tutte le modifiche verranno mantenute.</span><span class="sxs-lookup"><span data-stu-id="2e732-846">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="2e732-847">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-847">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="2e732-848">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-848">Excel</span></span>

- <span data-ttu-id="2e732-849">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="2e732-849">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2e732-850">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="2e732-850">Switching between them has never been easier.</span></span> [<span data-ttu-id="2e732-851">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-851">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2e732-852">**Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-852">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2e732-853">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-853">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2e732-854">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="2e732-854">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2e732-855">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="2e732-855">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2e732-856">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="2e732-856">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2e732-857">**Fogli di lavoro animati:** è possibile inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-857">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="2e732-858">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-858">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="2e732-p171">**Scoprire di più sui dati:** il nuovo pulsante Idee cerca modelli nei dati e li usa per creare suggerimenti intelligenti e personalizzati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="2e732-p171">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="2e732-861">**La collaborazione è stata semplificata:** i miglioramenti apportati alla creazione condivisa indicano che, quando si usa la formattazione condizionale, gli stili cella e così via, le modifiche vengono unite perfettamente con quelle dei propri collaboratori.</span><span class="sxs-lookup"><span data-stu-id="2e732-861">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="2e732-862">**Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle.</span><span class="sxs-lookup"><span data-stu-id="2e732-862">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="2e732-863">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-863">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="2e732-864">**Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi.</span><span class="sxs-lookup"><span data-stu-id="2e732-864">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="2e732-865">Semplice individuazione di funzioni, colonne e parametri.</span><span class="sxs-lookup"><span data-stu-id="2e732-865">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="2e732-866">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="2e732-866">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2e732-867">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="2e732-867">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2e732-868">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-868">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="2e732-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-869">Outlook</span></span>

- <span data-ttu-id="2e732-870">**Aggiornamento dell'esperienza utente di Outlook:** è finalmente accessibile a tutti un'esperienza semplificata, in precedenza disponibile in anteprima con Prossimamente, progettata per consentire all'utente di concentrarsi sugli aspetti più importanti.</span><span class="sxs-lookup"><span data-stu-id="2e732-870">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="2e732-871">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-871">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="2e732-872">**Barra multifunzione semplificata e personalizzabile:** un'unica riga essenziale riunisce i pulsanti usati di frequente.</span><span class="sxs-lookup"><span data-stu-id="2e732-872">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="2e732-873">In questo modo è possibile passare facilmente dalla visualizzazione classica a quella semplificata e aggiungere/rimuovere comandi.</span><span class="sxs-lookup"><span data-stu-id="2e732-873">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="2e732-874">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-874">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="2e732-875">**Continuare a lavorare durante lo spostamento di messaggi:** ora Outlook sposta i messaggi in background, di conseguenza è possibile continuare a lavorare durante lo spostamento di grandi quantità di messaggi tra le cartelle.</span><span class="sxs-lookup"><span data-stu-id="2e732-875">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="2e732-876">**Avere un momento di respiro tra una riunione e l'altra:** dare ai partecipanti il tempo di riprendere fiato o di viaggiare da una località all'altra impostando le riunioni in modo che terminino per impostazione predefinita 5-10 minuti in anticipo.</span><span class="sxs-lookup"><span data-stu-id="2e732-876">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="2e732-877">**Selezione dell'azione preferita:** le azioni Contrassegna e Elimina non vengono usate,</span><span class="sxs-lookup"><span data-stu-id="2e732-877">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="2e732-878">ma si preferisce usare Archivia o Segna come già letto?</span><span class="sxs-lookup"><span data-stu-id="2e732-878">How about Archive or Mark as Read?</span></span> <span data-ttu-id="2e732-879">È possibile personalizzare il menu Azioni rapide con i comandi usati più di frequente.</span><span class="sxs-lookup"><span data-stu-id="2e732-879">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="2e732-p178">**Utilizzo di meme:** quando testo o immagini statiche non bastano, si può usare una GIF animata per esprimere il proprio pensiero. [Altre informazioni](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="2e732-p178">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="2e732-882">**Un modo più rapido per aggiungere account:** grazie ai miglioramenti per la configurazione dell'account, l'aggiunta di account di Outlook.com e Gmail che utilizzano l'autenticazione a 2 fattori in Outlook è più facile che mai.</span><span class="sxs-lookup"><span data-stu-id="2e732-882">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="2e732-883">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-883">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="2e732-884">**Addio ai limiti per la sincronizzazione:** con i miglioramenti di Outlook non esiste più il limite di cartelle e quindi è possibile sincronizzare le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="2e732-884">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="2e732-885">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="2e732-885">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2e732-886">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="2e732-886">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2e732-887">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-887">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="2e732-888">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-888">PowerPoint</span></span>

- <span data-ttu-id="2e732-889">**Spostamento di forme migliorato:** assegnare un nome alle forme per un maggiore controllo sul modo in cui effettuano il morphing.</span><span class="sxs-lookup"><span data-stu-id="2e732-889">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="2e732-890">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-890">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="2e732-891">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="2e732-891">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2e732-892">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="2e732-892">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2e732-893">**Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-893">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="2e732-894">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-894">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2e732-895">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="2e732-895">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2e732-896">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="2e732-896">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2e732-897">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="2e732-897">Switching between them has never been easier.</span></span> [<span data-ttu-id="2e732-898">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-898">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2e732-899">**Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo,</span><span class="sxs-lookup"><span data-stu-id="2e732-899">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="2e732-900">nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file.</span><span class="sxs-lookup"><span data-stu-id="2e732-900">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="2e732-901">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-901">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="2e732-902">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="2e732-902">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2e732-p186">**Fare domande al pubblico con un test o un sondaggio:** inserire un test o un sondaggio in una diapositiva. Office raccoglie e archivia le risposte. [Ulteriori informazioni](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="2e732-p186">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="2e732-p187">**Inserire un video online è più facile che mai:** se si vuole inserire un video da Vimeo o YouTube nella diapositiva, basta il collegamento alla pagina del video. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="2e732-p187">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="2e732-909">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="2e732-909">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2e732-910">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="2e732-910">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2e732-911">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-911">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="2e732-912">Project</span><span class="sxs-lookup"><span data-stu-id="2e732-912">Project</span></span>

- <span data-ttu-id="2e732-913">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="2e732-913">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2e732-914">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="2e732-914">Switching between them has never been easier.</span></span> [<span data-ttu-id="2e732-915">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-915">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="2e732-916">Visio</span><span class="sxs-lookup"><span data-stu-id="2e732-916">Visio</span></span>

- <span data-ttu-id="2e732-917">**Esportazione dei diagrammi di processo in Word:** è possibile aggiungere automaticamente il contenuto dei diagrammi, come forme e metadati, a un documento Word.</span><span class="sxs-lookup"><span data-stu-id="2e732-917">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="2e732-918">Quindi, personalizzare il documento per creare linee guida di processi e manuali operativi.</span><span class="sxs-lookup"><span data-stu-id="2e732-918">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="2e732-919">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-919">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="2e732-920">**Maggiore controllo sui diagrammi di flusso di dati:** i nuovi fantastici layout per i diagrammi di flusso del Visualizzatore dati sono chiari, nitidi e facili da capire.</span><span class="sxs-lookup"><span data-stu-id="2e732-920">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="2e732-921">Fare clic sulla scheda Progettazione.</span><span class="sxs-lookup"><span data-stu-id="2e732-921">Click the Design tab for options.</span></span>

- <span data-ttu-id="2e732-922">**Stencil di Azure incorporati:** per progettare un'applicazione cloud o pianificare un'architettura è possibile scegliere tra decine di stencil di Azure.</span><span class="sxs-lookup"><span data-stu-id="2e732-922">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="2e732-923">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-923">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="2e732-p193">**Addio ai collegamenti interrotti di Excel:** impossibile trovare la cartella di lavoro di Excel collegata al diagramma del Visualizzatore dati? Collegarla di nuovo per riprendere l’attività. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="2e732-p193">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="2e732-927">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="2e732-927">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2e732-928">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="2e732-928">Switching between them has never been easier.</span></span> [<span data-ttu-id="2e732-929">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-929">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2e732-930">**Esportare elementi visivi di Visio da Power BI:** gli oggetti visivi di Visio per Power BI vengono ora visualizzati correttamente quando si esportano i report di Power BI come PDF, file di PowerPoint e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="2e732-930">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="2e732-931">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-931">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="2e732-932">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-932">Word</span></span>

- <span data-ttu-id="2e732-933">**La modalità Strumenti di apprendimento dispone di ulteriore supporto per più colori della pagina:** in Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina.</span><span class="sxs-lookup"><span data-stu-id="2e732-933">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="2e732-934">Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.</span><span class="sxs-lookup"><span data-stu-id="2e732-934">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="2e732-p197">**Modifica semplificata con Editor input penna:** con un solo tratto della penna, si possono dividere o unire le parole, aggiungere una nuova riga o inserire parole. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="2e732-p197">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="2e732-p198">**Trasformare il documento da statico a sorprendente:** trasformare il documento in una pagina web interattiva, facile da condividere che si adatta perfettamente a qualsiasi dispositivo. [Altre informazioni](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="2e732-p198">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="2e732-939">**Aumentare l'efficacia del contenuto:** rendere accessibili i documenti</span><span class="sxs-lookup"><span data-stu-id="2e732-939">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="2e732-940">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-940">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="2e732-941">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="2e732-941">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="2e732-942">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="2e732-942">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2e732-943">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="2e732-943">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="2e732-944">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="2e732-944">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="2e732-945">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="2e732-945">Switching between them has never been easier.</span></span> [<span data-ttu-id="2e732-946">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-946">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="2e732-p202">**Migliorare la comprensione con Focus su riga:** spostarsi in un documento riga per riga senza distrazioni. Modificare lo stato attivo per rendere visibili una, tre o cinque righe alla volta. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="2e732-p202">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="2e732-950">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="2e732-950">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2e732-951">**Ottenere l'attenzione tramite \@menzioni:** usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="2e732-951">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="2e732-952">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-952">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="2e732-953">**Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="2e732-953">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="2e732-954">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="2e732-954">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="2e732-955">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-955">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="2e732-956">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="2e732-956">Office Suite</span></span>

- <span data-ttu-id="2e732-957">**Ricerca rapida del file:** come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="2e732-957">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="2e732-958">È sufficiente digitare nella casella di ricerca su File > Apri per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="2e732-958">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="2e732-959">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="2e732-959">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="2e732-960">**Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse.</span><span class="sxs-lookup"><span data-stu-id="2e732-960">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="2e732-961">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-961">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="2e732-962">**Le icone di Office hanno un nuovo aspetto:** le icone di Office sono state riprogettate per riflettere l'esperienza semplice potente e intelligente di Office.</span><span class="sxs-lookup"><span data-stu-id="2e732-962">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="2e732-963">**Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle installazioni esistenti di Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="2e732-963">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="2e732-964">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="2e732-964">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-967">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-967">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="2e732-968">Access</span><span class="sxs-lookup"><span data-stu-id="2e732-968">Access</span></span>

- <span data-ttu-id="2e732-969">Questo aggiornamento risolve un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.</span><span class="sxs-lookup"><span data-stu-id="2e732-969">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="2e732-970">Questo aggiornamento risolve un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.</span><span class="sxs-lookup"><span data-stu-id="2e732-970">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="2e732-971">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo &quot;Query danneggiata&quot; quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="2e732-971">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="2e732-972">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-972">Excel</span></span>

- <span data-ttu-id="2e732-973">Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt-G.</span><span class="sxs-lookup"><span data-stu-id="2e732-973">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="2e732-974">È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.</span><span class="sxs-lookup"><span data-stu-id="2e732-974">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="2e732-975">È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-975">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="2e732-976">Questo aggiornamento risolve un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-976">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="2e732-977">Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal cubo.</span><span class="sxs-lookup"><span data-stu-id="2e732-977">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="2e732-978">Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.</span><span class="sxs-lookup"><span data-stu-id="2e732-978">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="2e732-979">È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.</span><span class="sxs-lookup"><span data-stu-id="2e732-979">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="2e732-980">È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.</span><span class="sxs-lookup"><span data-stu-id="2e732-980">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="2e732-981">È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="2e732-981">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="2e732-982">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="2e732-982">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2e732-983">È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.</span><span class="sxs-lookup"><span data-stu-id="2e732-983">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="2e732-984">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="2e732-984">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="2e732-985">È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="2e732-985">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="2e732-986">È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.</span><span class="sxs-lookup"><span data-stu-id="2e732-986">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="2e732-987">È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="2e732-987">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="2e732-988">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="2e732-988">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="2e732-989">Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-989">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="2e732-990">Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="2e732-990">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="2e732-991">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="2e732-991">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="2e732-992">È stato risolto un problema per cui la funzione Cerca restituiva un errore.</span><span class="sxs-lookup"><span data-stu-id="2e732-992">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="2e732-993">È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.</span><span class="sxs-lookup"><span data-stu-id="2e732-993">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="2e732-994">Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.</span><span class="sxs-lookup"><span data-stu-id="2e732-994">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="2e732-995">È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.</span><span class="sxs-lookup"><span data-stu-id="2e732-995">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="2e732-996">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="2e732-996">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="2e732-997">Sono state notevolmente migliorate le prestazioni del filtro per colore.</span><span class="sxs-lookup"><span data-stu-id="2e732-997">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="2e732-998">È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.</span><span class="sxs-lookup"><span data-stu-id="2e732-998">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="2e732-999">Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-999">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="2e732-1000">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="2e732-1000">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="2e732-1001">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-1001">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-1002">Questo aggiornamento corregge un errore in cui il caricamento dei documenti di Office in OneDrive for Business potrebbe avere esito negativo con il messaggio "Caricamento non riuscito".</span><span class="sxs-lookup"><span data-stu-id="2e732-1002">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="2e732-1003">È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.</span><span class="sxs-lookup"><span data-stu-id="2e732-1003">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-1004">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-1004">Outlook</span></span>

- <span data-ttu-id="2e732-1005">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-1005">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-1006">È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-1006">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="2e732-1007">È stato risolto un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.</span><span class="sxs-lookup"><span data-stu-id="2e732-1007">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="2e732-1008">È stato corretto un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="2e732-1008">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="2e732-1009">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="2e732-1009">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="2e732-1010">È stato risolto un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-1010">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="2e732-1011">Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="2e732-1011">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="2e732-1012">È stato risolto un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.</span><span class="sxs-lookup"><span data-stu-id="2e732-1012">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="2e732-1013">È stato risolto un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="2e732-1013">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="2e732-1014">È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="2e732-1014">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="2e732-1015">È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="2e732-1015">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="2e732-1016">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="2e732-1016">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="2e732-1017">È stato risolto un problema che causava un arresto anomalo di Outlook durante l'interazione con determinati collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="2e732-1017">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="2e732-1018">È stato risolto un problema che causava ambiguità per i responsabili circa il fatto che un delegato abbia già risposto o meno a una determinata convocazione di riunione.</span><span class="sxs-lookup"><span data-stu-id="2e732-1018">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="2e732-1019">È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="2e732-1019">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2e732-1020">È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante "OK" quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="2e732-1020">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="2e732-1021">Questa modifica consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN.</span><span class="sxs-lookup"><span data-stu-id="2e732-1021">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="2e732-1022">Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.</span><span class="sxs-lookup"><span data-stu-id="2e732-1022">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="2e732-1023">È stato risolto un problema che causava il malfunzionamento della ricerca nei gruppi moderni.</span><span class="sxs-lookup"><span data-stu-id="2e732-1023">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="2e732-1024">È stato risolto un problema che causava agli utenti di Outlook di rimanere bloccati nello stato "Password necessaria" in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="2e732-1024">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="2e732-1025">È stato risolto un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.</span><span class="sxs-lookup"><span data-stu-id="2e732-1025">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="2e732-1026">È stato risolto un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="2e732-1026">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="2e732-1027">È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.</span><span class="sxs-lookup"><span data-stu-id="2e732-1027">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="2e732-1028">È stato risolto un problema per cui venivano visualizzate cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="2e732-1028">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="2e732-1029">È stato risolto un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo "Conversazione non effettuata".</span><span class="sxs-lookup"><span data-stu-id="2e732-1029">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="2e732-1030">È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="2e732-1030">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="2e732-1031">È stato risolto un problema che causava la mancata visualizzazione dei suggerimenti per i criteri quando si usava un mittente alternativo.</span><span class="sxs-lookup"><span data-stu-id="2e732-1031">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="2e732-1032">È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-1032">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="2e732-1033">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-1033">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="2e732-1034">È stato risolto un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.</span><span class="sxs-lookup"><span data-stu-id="2e732-1034">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="2e732-1035">È stato risolto un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.</span><span class="sxs-lookup"><span data-stu-id="2e732-1035">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="2e732-1036">È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="2e732-1036">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="2e732-1037">È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="2e732-1037">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="2e732-1038">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-1038">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e732-1039">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-1039">PowerPoint</span></span>

- <span data-ttu-id="2e732-1040">È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.</span><span class="sxs-lookup"><span data-stu-id="2e732-1040">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="2e732-1041">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-1041">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-1042">Questa modifica ripristina il nome accessibile per i controlli video di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-1042">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="2e732-1043">È stato risolto un problema che impediva l'avvio di alcune animazioni.</span><span class="sxs-lookup"><span data-stu-id="2e732-1043">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="2e732-1044">Abbiamo risolto un problema che provoca la creazione di schemi duplicati quando si copia una diapositiva da una presentazione a un'altra.</span><span class="sxs-lookup"><span data-stu-id="2e732-1044">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="2e732-1045">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata</span><span class="sxs-lookup"><span data-stu-id="2e732-1045">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="2e732-1046">Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti poteva causare l'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-1046">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="2e732-1047">È stato risolto un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-1047">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="2e732-1048">Project</span><span class="sxs-lookup"><span data-stu-id="2e732-1048">Project</span></span>

- <span data-ttu-id="2e732-1049">È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-1049">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="2e732-1050">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="2e732-1050">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="2e732-1051">Il comando Livella tutte non risolve correttamente una sovrassegnazione della risorsa.</span><span class="sxs-lookup"><span data-stu-id="2e732-1051">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="2e732-1052">In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-1052">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="2e732-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="2e732-1053">Visio</span></span>

- <span data-ttu-id="2e732-1054">L'esportazione in SVG da Visio non funzionava per numerose forme.</span><span class="sxs-lookup"><span data-stu-id="2e732-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-1055">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-1055">Word</span></span>

- <span data-ttu-id="2e732-1056">Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.</span><span class="sxs-lookup"><span data-stu-id="2e732-1056">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="2e732-1057">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="2e732-1057">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="2e732-1058">È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet.</span><span class="sxs-lookup"><span data-stu-id="2e732-1058">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="2e732-1059">Abbiamo risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.</span><span class="sxs-lookup"><span data-stu-id="2e732-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="2e732-1060">Sono stati risolti diversi problemi che causavano il blocco dell'app durante la chiusura.</span><span class="sxs-lookup"><span data-stu-id="2e732-1060">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="2e732-1061">Sono stati risolti anche alcuni arresti anomali correlati ai componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-1061">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="2e732-1062">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="2e732-1062">Office Suite</span></span>

- <span data-ttu-id="2e732-1063">Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.</span><span class="sxs-lookup"><span data-stu-id="2e732-1063">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="2e732-1064">È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="2e732-1064">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="2e732-1065">È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-1065">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="2e732-1066">Si tratta di una correzione per un problema che causava un arresto anomalo all'apertura di un file.</span><span class="sxs-lookup"><span data-stu-id="2e732-1066">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="2e732-1067">Può causare un errore in PowerPoint quando si prova a presentare online.</span><span class="sxs-lookup"><span data-stu-id="2e732-1067">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="2e732-1068">In alcuni casi, un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica, comportando una perdita di dati.</span><span class="sxs-lookup"><span data-stu-id="2e732-1068">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="2e732-1069">È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="2e732-1069">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="2e732-1070">Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="2e732-1070">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="2e732-1071">È stato risolto un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.</span><span class="sxs-lookup"><span data-stu-id="2e732-1071">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="2e732-1072">È stato risolto un bug per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.</span><span class="sxs-lookup"><span data-stu-id="2e732-1072">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="2e732-1073">Migliora l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.</span><span class="sxs-lookup"><span data-stu-id="2e732-1073">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="2e732-1074">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="2e732-1074">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="2e732-1075">È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto.</span><span class="sxs-lookup"><span data-stu-id="2e732-1075">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="2e732-1076">In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.</span><span class="sxs-lookup"><span data-stu-id="2e732-1076">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="2e732-1077">È stato risolto un problema per cui, in alcuni casi, un aggiornamento non viene applicato se l'utente non è un amministratore e l'account di sistema non dispone della connettività di rete.</span><span class="sxs-lookup"><span data-stu-id="2e732-1077">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="2e732-1078">In alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento.</span><span class="sxs-lookup"><span data-stu-id="2e732-1078">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="2e732-1079">Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.</span><span class="sxs-lookup"><span data-stu-id="2e732-1079">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="2e732-1080">È stato risolto un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.</span><span class="sxs-lookup"><span data-stu-id="2e732-1080">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="2e732-1081">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="2e732-1081">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="2e732-1082">È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.</span><span class="sxs-lookup"><span data-stu-id="2e732-1082">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="2e732-1083">Sono stati risolti dei problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.</span><span class="sxs-lookup"><span data-stu-id="2e732-1083">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="2e732-1084">È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="2e732-1084">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="2e732-1085">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="2e732-1085">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="2e732-1087">Versione 1902: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="2e732-1087">Version 1902: January 14</span></span>
<span data-ttu-id="2e732-1088">*Versione 1902 (build 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="2e732-1088">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="2e732-1089">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-1089">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="2e732-1091">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="2e732-1091">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="2e732-1092">Excel</span><span class="sxs-lookup"><span data-stu-id="2e732-1092">Excel</span></span>

- <span data-ttu-id="2e732-1093">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="2e732-1093">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="2e732-1094">Outlook</span><span class="sxs-lookup"><span data-stu-id="2e732-1094">Outlook</span></span>

- <span data-ttu-id="2e732-1095">Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="2e732-1095">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="2e732-1096">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="2e732-1096">PowerPoint</span></span>

- <span data-ttu-id="2e732-1097">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata.</span><span class="sxs-lookup"><span data-stu-id="2e732-1097">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="2e732-1098">Word</span><span class="sxs-lookup"><span data-stu-id="2e732-1098">Word</span></span>

- <span data-ttu-id="2e732-1099">Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.</span><span class="sxs-lookup"><span data-stu-id="2e732-1099">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="2e732-1101">Versione 1808: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="2e732-1101">Version 1808: January 14</span></span>
<span data-ttu-id="2e732-1102">*Versione 1808 (build 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="2e732-1102">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="2e732-1103">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="2e732-1103">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="2e732-1105">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="2e732-1105">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
