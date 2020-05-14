---
title: Note sulle versioni per i rilasci del Canale semestrale nel 2020
ms.author: andrewmo
author: andymosten
manager: andrewmo
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale semestrale per Microsoft 365 Apps nel 2020
ms.openlocfilehash: 6074529d8a37228a191ae9e5d4a93d966a8d15ad
ms.sourcegitcommit: 1c78e7def81461cd758dded4b443b5dcffa17461
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 05/12/2020
ms.locfileid: "44210861"
---
# <a name="release-notes-for-semi-annual-channel-releases-in-2020"></a><span data-ttu-id="55038-103">Note sulle versioni per i rilasci del Canale semestrale nel 2020</span><span class="sxs-lookup"><span data-stu-id="55038-103">Release notes for Semi-Annual Channel releases in 2020</span></span>

<span data-ttu-id="55038-104">Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale semestrale nel 2020 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="55038-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="55038-105">Apporteremo alcune modifiche ai canali di aggiornamento per App di Microsoft 365, tra cui l'aggiunta di un nuovo canale di aggiornamento (canale mensile Enterprise) e la modifica dei nomi dei canali di aggiornamento già presenti.</span><span class="sxs-lookup"><span data-stu-id="55038-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="55038-106">Per altre informazioni, [leggere questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="55038-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="55038-107">OneNote 2016 sarà ora incluso per impostazione predefinita quando un utente del canale semestrale scarica e installa Microsoft 365 Apps in Windows 10 dal portale di Office.</span><span class="sxs-lookup"><span data-stu-id="55038-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-1908-may-12"></a><span data-ttu-id="55038-109">Versione 1908: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="55038-109">Version 1908: May 12</span></span>
<span data-ttu-id="55038-110">*Versione 1908 (Build 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="55038-110">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="55038-111">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-113">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-113">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="55038-114">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-114">Excel</span></span>

- <span data-ttu-id="55038-115">Quando si copiavano dati filtrati in base al colore in una colonna di larghezza differente, i valori non venivano incollati.</span><span class="sxs-lookup"><span data-stu-id="55038-115">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="55038-116">È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="55038-116">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="55038-117">È stato risolto un problema in VBA per cui scrivere valori in un intervallo era più lento del previsto.</span><span class="sxs-lookup"><span data-stu-id="55038-117">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="55038-118">È stato risolto un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambiava in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="55038-118">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="55038-119">Quando si aprivano nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.</span><span class="sxs-lookup"><span data-stu-id="55038-119">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

### <a name="onenote"></a><span data-ttu-id="55038-120">OneNote</span><span class="sxs-lookup"><span data-stu-id="55038-120">OneNote</span></span>

- <span data-ttu-id="55038-121">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote, per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="55038-121">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="55038-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-122">Outlook</span></span>

- <span data-ttu-id="55038-123">È stato risolto un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="55038-123">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="55038-124">È stato risolto un problema che causava un arresto anomalo selezionando alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="55038-124">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="55038-125">È stato risolto un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="55038-125">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="55038-126">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="55038-126">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="55038-127">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="55038-127">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="55038-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="55038-128">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="55038-129">0 = Predefinito.</span><span class="sxs-lookup"><span data-stu-id="55038-129">0 = Default.</span></span>  <span data-ttu-id="55038-130">1 = Verrà visualizzato solo il NomeCriterio nel testo dei criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="55038-130">1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="word"></a><span data-ttu-id="55038-131">Word</span><span class="sxs-lookup"><span data-stu-id="55038-131">Word</span></span>

- <span data-ttu-id="55038-132">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="55038-132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="55038-133">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="55038-133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-1902-may-12"></a><span data-ttu-id="55038-135">Versione 1902: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="55038-135">Version 1902: May 12</span></span>
<span data-ttu-id="55038-136">*Versione 1902 (Build 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="55038-136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="55038-137">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-139">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="55038-140">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-140">Outlook</span></span>

- <span data-ttu-id="55038-141">È stato risolto un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="55038-141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="55038-142">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="55038-142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="55038-143">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="55038-143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="55038-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="55038-144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="55038-145">0 = Predefinito.</span><span class="sxs-lookup"><span data-stu-id="55038-145">0 = Default.</span></span>  <span data-ttu-id="55038-146">1 = Verrà visualizzato solo il NomeCriterio nel testo dei criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="55038-146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-1908-may-04"></a><span data-ttu-id="55038-148">Versione 1908: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="55038-148">Version 1908: May 04</span></span>
<span data-ttu-id="55038-149">*Versione 1908 (build 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="55038-149">*Version 1908 (Build 11929.20752)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="55038-150">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-150">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="55038-151">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="55038-151">Office Suite</span></span>

- <span data-ttu-id="55038-152">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="55038-152">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="55038-153">Versione 1902: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="55038-153">Version 1902: May 04</span></span>
<span data-ttu-id="55038-154">*Versione 1902 (build 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="55038-154">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="55038-155">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-155">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="55038-156">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="55038-156">Office Suite</span></span>

- <span data-ttu-id="55038-157">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="55038-157">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-14"></a><span data-ttu-id="55038-158">Versione 1908: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="55038-158">Version 1908: April 14</span></span>
<span data-ttu-id="55038-159">*Versione 1908 (Build 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="55038-159">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="55038-160">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-160">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-162">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-162">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55038-163">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-163">Excel</span></span>

- <span data-ttu-id="55038-164">È stato risolto un problema che causava il rallentamento delle prestazioni quando si eliminavano colonne contenenti celle unite.</span><span class="sxs-lookup"><span data-stu-id="55038-164">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="55038-165">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="55038-165">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="55038-166">Skype</span><span class="sxs-lookup"><span data-stu-id="55038-166">Skype</span></span>

- <span data-ttu-id="55038-167">È stato risolto un problema relativo al nome titolo per la conversazione su schede mentre erano in corso più conversazioni.</span><span class="sxs-lookup"><span data-stu-id="55038-167">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="55038-168">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-168">Outlook</span></span>

- <span data-ttu-id="55038-169">È stato risolto un problema che causava un arresto anomalo durante l'arresto di Outlook.</span><span class="sxs-lookup"><span data-stu-id="55038-169">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="55038-170">È stato risolto un problema che causava la visualizzazione di un elenco sale vuoto in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="55038-170">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55038-171">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55038-171">PowerPoint</span></span>

- <span data-ttu-id="55038-172">È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.</span><span class="sxs-lookup"><span data-stu-id="55038-172">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="55038-173">Word</span><span class="sxs-lookup"><span data-stu-id="55038-173">Word</span></span>

- <span data-ttu-id="55038-174">È stato risolto un problema relativo ad Adatta testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="55038-174">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="55038-175">Versione 1902: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="55038-175">Version 1902: April 14</span></span>
<span data-ttu-id="55038-176">*Versione 1902 (Build 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="55038-176">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="55038-177">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-177">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="55038-179">Versione 1908: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="55038-179">Version 1908: March 10</span></span>
<span data-ttu-id="55038-180">*Versione 1908 (Build 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="55038-180">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="55038-181">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-181">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-183">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-183">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55038-184">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-184">Excel</span></span>

- <span data-ttu-id="55038-185">È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato la presenza di più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.</span><span class="sxs-lookup"><span data-stu-id="55038-185">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="55038-186">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><span class="sxs-lookup"><span data-stu-id="55038-186">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="55038-187">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="55038-187">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="55038-188">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55038-188">PowerPoint</span></span>

- <span data-ttu-id="55038-189">È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.</span><span class="sxs-lookup"><span data-stu-id="55038-189">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="55038-190">Word</span><span class="sxs-lookup"><span data-stu-id="55038-190">Word</span></span>

- <span data-ttu-id="55038-191">È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="55038-191">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="55038-192">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="55038-192">Office Suite</span></span>

- <span data-ttu-id="55038-193">Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span><span class="sxs-lookup"><span data-stu-id="55038-193">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="55038-194">Versione 1902: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="55038-194">Version 1902: March 10</span></span>
<span data-ttu-id="55038-195">*Versione 1902 (Build 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="55038-195">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="55038-196">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="55038-198">Versione 1908: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="55038-198">Version 1908: February 11</span></span>
<span data-ttu-id="55038-199">*Versione 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="55038-199">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="55038-200">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-202">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55038-203">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-203">Excel</span></span>

- <span data-ttu-id="55038-204">Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.</span><span class="sxs-lookup"><span data-stu-id="55038-204">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="55038-205">È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.</span><span class="sxs-lookup"><span data-stu-id="55038-205">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="55038-206">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="55038-206">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="55038-207">È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.</span><span class="sxs-lookup"><span data-stu-id="55038-207">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="55038-208">È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.</span><span class="sxs-lookup"><span data-stu-id="55038-208">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="55038-209">È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.</span><span class="sxs-lookup"><span data-stu-id="55038-209">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="55038-210">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-210">Outlook</span></span>

- <span data-ttu-id="55038-211">È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="55038-211">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="55038-212">È stato risolto un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.</span><span class="sxs-lookup"><span data-stu-id="55038-212">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="55038-213">È stato risolto un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.</span><span class="sxs-lookup"><span data-stu-id="55038-213">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="55038-214">È stato risolto un problema che causava arresti anomali intermittenti cambiando visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="55038-214">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="55038-215">È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="55038-215">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="55038-216">[Qui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) è disponibile il singolo articolo della Knowledge Basa in cui è stato documentato per le versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="55038-216">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="55038-217">È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.</span><span class="sxs-lookup"><span data-stu-id="55038-217">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="55038-218">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55038-218">PowerPoint</span></span>

- <span data-ttu-id="55038-219">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="55038-219">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="55038-220">È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.</span><span class="sxs-lookup"><span data-stu-id="55038-220">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="55038-221">È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.</span><span class="sxs-lookup"><span data-stu-id="55038-221">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="55038-222">È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="55038-222">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="55038-223">Project</span><span class="sxs-lookup"><span data-stu-id="55038-223">Project</span></span>

- <span data-ttu-id="55038-224">È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.</span><span class="sxs-lookup"><span data-stu-id="55038-224">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="55038-225">Word</span><span class="sxs-lookup"><span data-stu-id="55038-225">Word</span></span>

- <span data-ttu-id="55038-226">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="55038-226">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="55038-227">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="55038-227">Office Suite</span></span>

- <span data-ttu-id="55038-228">Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.</span><span class="sxs-lookup"><span data-stu-id="55038-228">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="55038-230">Versione 1902: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="55038-230">Version 1902: February 11</span></span>
<span data-ttu-id="55038-231">*Versione 1902 (Build 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="55038-231">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="55038-232">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-232">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-234">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-234">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="55038-235">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-235">Outlook</span></span>

- <span data-ttu-id="55038-236">Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="55038-236">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="55038-237">Word</span><span class="sxs-lookup"><span data-stu-id="55038-237">Word</span></span>

- <span data-ttu-id="55038-238">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="55038-238">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="55038-241">Versione 1808: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="55038-241">Version 1808: February 11</span></span>
<span data-ttu-id="55038-242">*Versione 1808 (Build 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="55038-242">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="55038-243">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-243">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="55038-245">Versione 1908: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="55038-245">Version 1908: January 14</span></span>
<span data-ttu-id="55038-246">*Versione 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="55038-246">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="55038-247">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-247">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="55038-249">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="55038-249">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="55038-250">Access</span><span class="sxs-lookup"><span data-stu-id="55038-250">Access</span></span>

- <span data-ttu-id="55038-251">**Monitorare gli oggetti di database:** visualizzare chiaramente la scheda attiva, trascinare facilmente le schede per disporle in modo diverso e chiudere gli oggetti di database con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="55038-251">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="55038-252">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="55038-252">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55038-253">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="55038-253">Switching between them has never been easier.</span></span> [<span data-ttu-id="55038-254">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-254">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55038-255">**Zoom con più spazio:** ingrandire la casella Zoom e cambiare il tipo di carattere. Tutte le modifiche verranno mantenute.</span><span class="sxs-lookup"><span data-stu-id="55038-255">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="55038-256">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-256">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="55038-257">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-257">Excel</span></span>

- <span data-ttu-id="55038-258">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="55038-258">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55038-259">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="55038-259">Switching between them has never been easier.</span></span> [<span data-ttu-id="55038-260">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-260">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55038-261">**Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni</span><span class="sxs-lookup"><span data-stu-id="55038-261">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="55038-262">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="55038-262">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="55038-263">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="55038-263">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="55038-264">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="55038-264">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55038-265">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="55038-265">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="55038-266">**Fogli di lavoro animati:** è possibile inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="55038-266">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="55038-267">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-267">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="55038-p111">**Scoprire di più sui dati:** il nuovo pulsante Idee cerca modelli nei dati e li usa per creare suggerimenti intelligenti e personalizzati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="55038-p111">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="55038-270">**La collaborazione è stata semplificata:** i miglioramenti apportati alla creazione condivisa indicano che, quando si usa la formattazione condizionale, gli stili cella e così via, le modifiche vengono unite perfettamente con quelle dei propri collaboratori.</span><span class="sxs-lookup"><span data-stu-id="55038-270">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="55038-271">**Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle.</span><span class="sxs-lookup"><span data-stu-id="55038-271">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="55038-272">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-272">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="55038-273">**Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi.</span><span class="sxs-lookup"><span data-stu-id="55038-273">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="55038-274">Semplice individuazione di funzioni, colonne e parametri.</span><span class="sxs-lookup"><span data-stu-id="55038-274">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="55038-275">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="55038-275">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55038-276">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="55038-276">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55038-277">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-277">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="55038-278">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-278">Outlook</span></span>

- <span data-ttu-id="55038-279">**Aggiornamento dell'esperienza utente di Outlook:** è finalmente accessibile a tutti un'esperienza semplificata, in precedenza disponibile in anteprima con Prossimamente, progettata per consentire all'utente di concentrarsi sugli aspetti più importanti.</span><span class="sxs-lookup"><span data-stu-id="55038-279">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="55038-280">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-280">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="55038-281">**Barra multifunzione semplificata e personalizzabile:** un'unica riga essenziale riunisce i pulsanti usati di frequente.</span><span class="sxs-lookup"><span data-stu-id="55038-281">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="55038-282">In questo modo è possibile passare facilmente dalla visualizzazione classica a quella semplificata e aggiungere/rimuovere comandi.</span><span class="sxs-lookup"><span data-stu-id="55038-282">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="55038-283">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-283">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="55038-284">**Continuare a lavorare durante lo spostamento di messaggi:** ora Outlook sposta i messaggi in background, di conseguenza è possibile continuare a lavorare durante lo spostamento di grandi quantità di messaggi tra le cartelle.</span><span class="sxs-lookup"><span data-stu-id="55038-284">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="55038-285">**Avere un momento di respiro tra una riunione e l'altra:** dare ai partecipanti il tempo di riprendere fiato o di viaggiare da una località all'altra impostando le riunioni in modo che terminino per impostazione predefinita 5-10 minuti in anticipo.</span><span class="sxs-lookup"><span data-stu-id="55038-285">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="55038-286">**Selezione dell'azione preferita:** le azioni Contrassegna e Elimina non vengono usate,</span><span class="sxs-lookup"><span data-stu-id="55038-286">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="55038-287">ma si preferisce usare Archivia o Segna come già letto?</span><span class="sxs-lookup"><span data-stu-id="55038-287">How about Archive or Mark as Read?</span></span> <span data-ttu-id="55038-288">È possibile personalizzare il menu Azioni rapide con i comandi usati più di frequente.</span><span class="sxs-lookup"><span data-stu-id="55038-288">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="55038-p118">**Utilizzo di meme:** quando testo o immagini statiche non bastano, si può usare una GIF animata per esprimere il proprio pensiero. [Altre informazioni](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="55038-p118">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="55038-291">**Un modo più rapido per aggiungere account:** grazie ai miglioramenti per la configurazione dell'account, l'aggiunta di account di Outlook.com e Gmail che utilizzano l'autenticazione a 2 fattori in Outlook è più facile che mai.</span><span class="sxs-lookup"><span data-stu-id="55038-291">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="55038-292">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-292">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="55038-293">**Addio ai limiti per la sincronizzazione:** con i miglioramenti di Outlook non esiste più il limite di cartelle e quindi è possibile sincronizzare le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="55038-293">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="55038-294">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="55038-294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55038-295">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="55038-295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55038-296">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="55038-297">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55038-297">PowerPoint</span></span>

- <span data-ttu-id="55038-298">**Spostamento di forme migliorato:** assegnare un nome alle forme per un maggiore controllo sul modo in cui effettuano il morphing.</span><span class="sxs-lookup"><span data-stu-id="55038-298">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="55038-299">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-299">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="55038-300">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="55038-300">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55038-301">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="55038-301">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="55038-302">**Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni</span><span class="sxs-lookup"><span data-stu-id="55038-302">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="55038-303">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="55038-303">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="55038-304">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="55038-304">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="55038-305">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="55038-305">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55038-306">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="55038-306">Switching between them has never been easier.</span></span> [<span data-ttu-id="55038-307">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-307">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55038-308">**Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo,</span><span class="sxs-lookup"><span data-stu-id="55038-308">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="55038-309">nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file.</span><span class="sxs-lookup"><span data-stu-id="55038-309">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="55038-310">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-310">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="55038-311">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="55038-311">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="55038-p126">**Fare domande al pubblico con un test o un sondaggio:** inserire un test o un sondaggio in una diapositiva. Office raccoglie e archivia le risposte. [Ulteriori informazioni](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="55038-p126">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="55038-p127">**Inserire un video online è più facile che mai:** se si vuole inserire un video da Vimeo o YouTube nella diapositiva, basta il collegamento alla pagina del video. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="55038-p127">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="55038-318">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="55038-318">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55038-319">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="55038-319">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55038-320">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-320">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="55038-321">Project</span><span class="sxs-lookup"><span data-stu-id="55038-321">Project</span></span>

- <span data-ttu-id="55038-322">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="55038-322">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55038-323">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="55038-323">Switching between them has never been easier.</span></span> [<span data-ttu-id="55038-324">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-324">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="55038-325">Visio</span><span class="sxs-lookup"><span data-stu-id="55038-325">Visio</span></span>

- <span data-ttu-id="55038-326">**Esportazione dei diagrammi di processo in Word:** è possibile aggiungere automaticamente il contenuto dei diagrammi, come forme e metadati, a un documento Word.</span><span class="sxs-lookup"><span data-stu-id="55038-326">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="55038-327">Quindi, personalizzare il documento per creare linee guida di processi e manuali operativi.</span><span class="sxs-lookup"><span data-stu-id="55038-327">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="55038-328">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-328">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="55038-329">**Maggiore controllo sui diagrammi di flusso di dati:** i nuovi fantastici layout per i diagrammi di flusso del Visualizzatore dati sono chiari, nitidi e facili da capire.</span><span class="sxs-lookup"><span data-stu-id="55038-329">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="55038-330">Fare clic sulla scheda Progettazione.</span><span class="sxs-lookup"><span data-stu-id="55038-330">Click the Design tab for options.</span></span>

- <span data-ttu-id="55038-331">**Stencil di Azure incorporati:** per progettare un'applicazione cloud o pianificare un'architettura è possibile scegliere tra decine di stencil di Azure.</span><span class="sxs-lookup"><span data-stu-id="55038-331">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="55038-332">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-332">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="55038-p133">**Addio ai collegamenti interrotti di Excel:** impossibile trovare la cartella di lavoro di Excel collegata al diagramma del Visualizzatore dati? Collegarla di nuovo per riprendere l’attività. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="55038-p133">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="55038-336">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="55038-336">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55038-337">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="55038-337">Switching between them has never been easier.</span></span> [<span data-ttu-id="55038-338">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-338">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55038-339">**Esportare elementi visivi di Visio da Power BI:** gli oggetti visivi di Visio per Power BI vengono ora visualizzati correttamente quando si esportano i report di Power BI come PDF, file di PowerPoint e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="55038-339">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="55038-340">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-340">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="55038-341">Word</span><span class="sxs-lookup"><span data-stu-id="55038-341">Word</span></span>

- <span data-ttu-id="55038-342">**La modalità Strumenti di apprendimento dispone di ulteriore supporto per più colori della pagina:** in Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina.</span><span class="sxs-lookup"><span data-stu-id="55038-342">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="55038-343">Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.</span><span class="sxs-lookup"><span data-stu-id="55038-343">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="55038-p137">**Modifica semplificata con Editor input penna:** con un solo tratto della penna, si possono dividere o unire le parole, aggiungere una nuova riga o inserire parole. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="55038-p137">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="55038-p138">**Trasformare il documento da statico a sorprendente:** trasformare il documento in una pagina web interattiva, facile da condividere che si adatta perfettamente a qualsiasi dispositivo. [Altre informazioni](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="55038-p138">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="55038-348">**Aumentare l'efficacia del contenuto:** rendere accessibili i documenti</span><span class="sxs-lookup"><span data-stu-id="55038-348">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="55038-349">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="55038-349">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="55038-350">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="55038-350">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="55038-351">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="55038-351">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55038-352">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="55038-352">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="55038-353">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="55038-353">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="55038-354">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="55038-354">Switching between them has never been easier.</span></span> [<span data-ttu-id="55038-355">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-355">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="55038-p142">**Migliorare la comprensione con Focus su riga:** spostarsi in un documento riga per riga senza distrazioni. Modificare lo stato attivo per rendere visibili una, tre o cinque righe alla volta. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="55038-p142">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="55038-359">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="55038-359">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="55038-360">**Ottenere l'attenzione tramite \@menzioni:** usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="55038-360">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="55038-361">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-361">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="55038-362">**Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="55038-362">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="55038-363">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="55038-363">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="55038-364">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-364">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="55038-365">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="55038-365">Office Suite</span></span>

- <span data-ttu-id="55038-366">**Ricerca rapida del file:** come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="55038-366">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="55038-367">È sufficiente digitare nella casella di ricerca su File > Apri per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="55038-367">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="55038-368">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="55038-368">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="55038-369">**Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse.</span><span class="sxs-lookup"><span data-stu-id="55038-369">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="55038-370">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-370">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="55038-371">**Le icone di Office hanno un nuovo aspetto:** le icone di Office sono state riprogettate per riflettere l'esperienza semplice potente e intelligente di Office.</span><span class="sxs-lookup"><span data-stu-id="55038-371">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="55038-372">**Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle installazioni esistenti di Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="55038-372">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="55038-373">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="55038-373">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-376">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-376">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="55038-377">Access</span><span class="sxs-lookup"><span data-stu-id="55038-377">Access</span></span>

- <span data-ttu-id="55038-378">Questo aggiornamento risolve un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.</span><span class="sxs-lookup"><span data-stu-id="55038-378">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="55038-379">Questo aggiornamento risolve un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.</span><span class="sxs-lookup"><span data-stu-id="55038-379">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="55038-380">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo &quot;Query danneggiata&quot; quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="55038-380">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="55038-381">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-381">Excel</span></span>

- <span data-ttu-id="55038-382">Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt-G.</span><span class="sxs-lookup"><span data-stu-id="55038-382">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="55038-383">È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.</span><span class="sxs-lookup"><span data-stu-id="55038-383">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="55038-384">È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.</span><span class="sxs-lookup"><span data-stu-id="55038-384">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="55038-385">Questo aggiornamento risolve un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="55038-385">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="55038-386">Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal cubo.</span><span class="sxs-lookup"><span data-stu-id="55038-386">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="55038-387">Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.</span><span class="sxs-lookup"><span data-stu-id="55038-387">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="55038-388">È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.</span><span class="sxs-lookup"><span data-stu-id="55038-388">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="55038-389">È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.</span><span class="sxs-lookup"><span data-stu-id="55038-389">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="55038-390">È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="55038-390">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="55038-391">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="55038-391">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="55038-392">È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.</span><span class="sxs-lookup"><span data-stu-id="55038-392">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="55038-393">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="55038-393">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="55038-394">È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="55038-394">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="55038-395">È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.</span><span class="sxs-lookup"><span data-stu-id="55038-395">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="55038-396">È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="55038-396">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="55038-397">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="55038-397">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="55038-398">Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.</span><span class="sxs-lookup"><span data-stu-id="55038-398">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="55038-399">Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="55038-399">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="55038-400">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="55038-400">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="55038-401">È stato risolto un problema per cui la funzione Cerca restituiva un errore.</span><span class="sxs-lookup"><span data-stu-id="55038-401">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="55038-402">È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.</span><span class="sxs-lookup"><span data-stu-id="55038-402">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="55038-403">Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.</span><span class="sxs-lookup"><span data-stu-id="55038-403">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="55038-404">È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.</span><span class="sxs-lookup"><span data-stu-id="55038-404">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="55038-405">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="55038-405">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="55038-406">Sono state notevolmente migliorate le prestazioni del filtro per colore.</span><span class="sxs-lookup"><span data-stu-id="55038-406">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="55038-407">È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.</span><span class="sxs-lookup"><span data-stu-id="55038-407">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="55038-408">Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="55038-408">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="55038-409">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="55038-409">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="55038-410">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="55038-410">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="55038-411">Questo aggiornamento corregge un errore in cui il caricamento dei documenti di Office in OneDrive for Business potrebbe avere esito negativo con il messaggio "Caricamento non riuscito".</span><span class="sxs-lookup"><span data-stu-id="55038-411">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="55038-412">È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.</span><span class="sxs-lookup"><span data-stu-id="55038-412">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="55038-413">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-413">Outlook</span></span>

- <span data-ttu-id="55038-414">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="55038-414">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="55038-415">È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.</span><span class="sxs-lookup"><span data-stu-id="55038-415">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="55038-416">È stato risolto un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.</span><span class="sxs-lookup"><span data-stu-id="55038-416">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="55038-417">È stato corretto un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="55038-417">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="55038-418">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="55038-418">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="55038-419">È stato risolto un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="55038-419">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="55038-420">Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="55038-420">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="55038-421">È stato risolto un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.</span><span class="sxs-lookup"><span data-stu-id="55038-421">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="55038-422">È stato risolto un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="55038-422">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="55038-423">È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="55038-423">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="55038-424">È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="55038-424">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="55038-425">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="55038-425">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="55038-426">È stato risolto un problema che causava un arresto anomalo di Outlook durante l'interazione con determinati collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="55038-426">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="55038-427">È stato risolto un problema che causava ambiguità per i responsabili circa il fatto che un delegato abbia già risposto o meno a una determinata convocazione di riunione.</span><span class="sxs-lookup"><span data-stu-id="55038-427">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="55038-428">È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="55038-428">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="55038-429">È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante "OK" quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="55038-429">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="55038-430">Questa modifica consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN.</span><span class="sxs-lookup"><span data-stu-id="55038-430">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="55038-431">Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.</span><span class="sxs-lookup"><span data-stu-id="55038-431">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="55038-432">È stato risolto un problema che causava il malfunzionamento della ricerca nei gruppi moderni.</span><span class="sxs-lookup"><span data-stu-id="55038-432">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="55038-433">È stato risolto un problema che causava agli utenti di Outlook di rimanere bloccati nello stato "Password necessaria" in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="55038-433">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="55038-434">È stato risolto un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.</span><span class="sxs-lookup"><span data-stu-id="55038-434">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="55038-435">È stato risolto un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="55038-435">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="55038-436">È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.</span><span class="sxs-lookup"><span data-stu-id="55038-436">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="55038-437">È stato risolto un problema per cui venivano visualizzate cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="55038-437">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="55038-438">È stato risolto un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo "Conversazione non effettuata".</span><span class="sxs-lookup"><span data-stu-id="55038-438">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="55038-439">È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="55038-439">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="55038-440">È stato risolto un problema che causava la mancata visualizzazione dei suggerimenti per i criteri quando si usava un mittente alternativo.</span><span class="sxs-lookup"><span data-stu-id="55038-440">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="55038-441">È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="55038-441">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="55038-442">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="55038-442">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="55038-443">È stato risolto un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.</span><span class="sxs-lookup"><span data-stu-id="55038-443">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="55038-444">È stato risolto un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.</span><span class="sxs-lookup"><span data-stu-id="55038-444">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="55038-445">È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="55038-445">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="55038-446">È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="55038-446">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="55038-447">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="55038-447">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55038-448">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55038-448">PowerPoint</span></span>

- <span data-ttu-id="55038-449">È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.</span><span class="sxs-lookup"><span data-stu-id="55038-449">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="55038-450">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="55038-450">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="55038-451">Questa modifica ripristina il nome accessibile per i controlli video di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="55038-451">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="55038-452">È stato risolto un problema che impediva l'avvio di alcune animazioni.</span><span class="sxs-lookup"><span data-stu-id="55038-452">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="55038-453">Abbiamo risolto un problema che provoca la creazione di schemi duplicati quando si copia una diapositiva da una presentazione a un'altra.</span><span class="sxs-lookup"><span data-stu-id="55038-453">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="55038-454">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata</span><span class="sxs-lookup"><span data-stu-id="55038-454">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="55038-455">Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti poteva causare l'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="55038-455">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="55038-456">È stato risolto un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="55038-456">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="55038-457">Project</span><span class="sxs-lookup"><span data-stu-id="55038-457">Project</span></span>

- <span data-ttu-id="55038-458">È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="55038-458">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="55038-459">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="55038-459">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="55038-460">Il comando Livella tutte non risolve correttamente una sovrassegnazione della risorsa.</span><span class="sxs-lookup"><span data-stu-id="55038-460">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="55038-461">In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.</span><span class="sxs-lookup"><span data-stu-id="55038-461">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="55038-462">Visio</span><span class="sxs-lookup"><span data-stu-id="55038-462">Visio</span></span>

- <span data-ttu-id="55038-463">L'esportazione in SVG da Visio non funzionava per numerose forme.</span><span class="sxs-lookup"><span data-stu-id="55038-463">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="55038-464">Word</span><span class="sxs-lookup"><span data-stu-id="55038-464">Word</span></span>

- <span data-ttu-id="55038-465">Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.</span><span class="sxs-lookup"><span data-stu-id="55038-465">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="55038-466">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="55038-466">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="55038-467">È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet.</span><span class="sxs-lookup"><span data-stu-id="55038-467">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="55038-468">Abbiamo risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.</span><span class="sxs-lookup"><span data-stu-id="55038-468">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="55038-469">Sono stati risolti diversi problemi che causavano il blocco dell'app durante la chiusura.</span><span class="sxs-lookup"><span data-stu-id="55038-469">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="55038-470">Sono stati risolti anche alcuni arresti anomali correlati ai componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="55038-470">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="55038-471">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="55038-471">Office Suite</span></span>

- <span data-ttu-id="55038-472">Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.</span><span class="sxs-lookup"><span data-stu-id="55038-472">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="55038-473">È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="55038-473">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="55038-474">È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="55038-474">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="55038-475">Si tratta di una correzione per un problema che causava un arresto anomalo all'apertura di un file.</span><span class="sxs-lookup"><span data-stu-id="55038-475">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="55038-476">Può causare un errore in PowerPoint quando si prova a presentare online.</span><span class="sxs-lookup"><span data-stu-id="55038-476">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="55038-477">In alcuni casi, un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica, comportando una perdita di dati.</span><span class="sxs-lookup"><span data-stu-id="55038-477">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="55038-478">È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="55038-478">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="55038-479">Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="55038-479">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="55038-480">È stato risolto un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.</span><span class="sxs-lookup"><span data-stu-id="55038-480">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="55038-481">È stato risolto un bug per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.</span><span class="sxs-lookup"><span data-stu-id="55038-481">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="55038-482">Migliora l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.</span><span class="sxs-lookup"><span data-stu-id="55038-482">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="55038-483">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="55038-483">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="55038-484">È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto.</span><span class="sxs-lookup"><span data-stu-id="55038-484">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="55038-485">In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.</span><span class="sxs-lookup"><span data-stu-id="55038-485">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="55038-486">È stato risolto un problema per cui, in alcuni casi, un aggiornamento non viene applicato se l'utente non è un amministratore e l'account di sistema non dispone della connettività di rete.</span><span class="sxs-lookup"><span data-stu-id="55038-486">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="55038-487">In alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento.</span><span class="sxs-lookup"><span data-stu-id="55038-487">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="55038-488">Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.</span><span class="sxs-lookup"><span data-stu-id="55038-488">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="55038-489">È stato risolto un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.</span><span class="sxs-lookup"><span data-stu-id="55038-489">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="55038-490">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="55038-490">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="55038-491">È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.</span><span class="sxs-lookup"><span data-stu-id="55038-491">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="55038-492">Sono stati risolti dei problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.</span><span class="sxs-lookup"><span data-stu-id="55038-492">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="55038-493">È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="55038-493">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="55038-494">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="55038-494">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="55038-496">Versione 1902: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="55038-496">Version 1902: January 14</span></span>
<span data-ttu-id="55038-497">*Versione 1902 (build 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="55038-497">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="55038-498">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-498">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="55038-500">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="55038-500">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="55038-501">Excel</span><span class="sxs-lookup"><span data-stu-id="55038-501">Excel</span></span>

- <span data-ttu-id="55038-502">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="55038-502">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="55038-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="55038-503">Outlook</span></span>

- <span data-ttu-id="55038-504">Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="55038-504">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="55038-505">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="55038-505">PowerPoint</span></span>

- <span data-ttu-id="55038-506">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata.</span><span class="sxs-lookup"><span data-stu-id="55038-506">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="55038-507">Word</span><span class="sxs-lookup"><span data-stu-id="55038-507">Word</span></span>

- <span data-ttu-id="55038-508">Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.</span><span class="sxs-lookup"><span data-stu-id="55038-508">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="55038-510">Versione 1808: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="55038-510">Version 1808: January 14</span></span>
<span data-ttu-id="55038-511">*Versione 1808 (build 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="55038-511">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="55038-512">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="55038-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="55038-514">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="55038-514">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>
