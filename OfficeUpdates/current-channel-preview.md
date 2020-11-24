---
title: Note sulla versione del Canale corrente (Anteprima)
ms.author: anankani
author: v-lislo
manager: anankani
ms.audience: Win32 Fast
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: 'Offre ai partecipanti al programma Insider Slow un elenco aggiornato delle nuove funzionalità, correzioni o problemi noti '
ms.openlocfilehash: 2702cc1098282aa53972a2b01beb8eb9545b04ff
ms.sourcegitcommit: 4b5ee25e335d9585dfe5660faac747600c9e3e69
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/23/2020
ms.locfileid: "49382636"
---
# <a name="release-notes-for-office-current-channel-preview"></a><span data-ttu-id="525c8-103">Note sulla versione del Canale corrente di Office (Anteprima)</span><span class="sxs-lookup"><span data-stu-id="525c8-103">Release Notes for Office Current Channel (Preview)</span></span>

<span data-ttu-id="525c8-p101">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span><span class="sxs-lookup"><span data-stu-id="525c8-p101">This article contains release notes for Current Channel (Preview) builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Current Channel (Preview) over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

> [!IMPORTANT]
> <span data-ttu-id="525c8-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="525c8-p102">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
> - <span data-ttu-id="525c8-111">La data di pubblicazione delle note sulla versione può non corrispondere all'effettiva data di rilascio della build.</span><span class="sxs-lookup"><span data-stu-id="525c8-111">The release notes publication date may not match the actual build release date.</span></span>

[//]: # (DO NOT REMOVE)

## <a name="version-2011-november-21"></a><span data-ttu-id="525c8-113">Versione 2011: 21 novembre</span><span class="sxs-lookup"><span data-stu-id="525c8-113">Version 2011: November 21</span></span>
<span data-ttu-id="525c8-114">*Versione 2011 (Build 13426.20274)*</span><span class="sxs-lookup"><span data-stu-id="525c8-114">*Version 2011 (Build 13426.20274)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-116">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-116">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="525c8-117">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-117">PowerPoint</span></span>

- <span data-ttu-id="525c8-118">**Catalogo video:** migliorare i documenti con una catalogo di filmati video curati e con licenza a titolo gratuito disponibili in-app</span><span class="sxs-lookup"><span data-stu-id="525c8-118">**Video Library:** Elevate your documents with a library of curated, royalty-free video footage available in-app</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-121">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-121">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-122">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-122">Outlook</span></span>

- <span data-ttu-id="525c8-123">È stato risolto un problema che causava l'interruzione dell'evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="525c8-123">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="525c8-124">È stato aggiunto una chiave di registro che consente ai clienti di disabilitare l'inclusione filetime per gli allegati nelle operazioni IDataObject (ad esempio trascinamento, appunti).</span><span class="sxs-lookup"><span data-stu-id="525c8-124">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="525c8-125">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span><span class="sxs-lookup"><span data-stu-id="525c8-125">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments.</span></span> <span data-ttu-id="525c8-126">REG_DWORD IncludeFileTimesInDataObject.</span><span class="sxs-lookup"><span data-stu-id="525c8-126">REG_DWORD IncludeFileTimesInDataObject.</span></span> <span data-ttu-id="525c8-127">0 = filetime esclusi.</span><span class="sxs-lookup"><span data-stu-id="525c8-127">0 = filetimes are excluded.</span></span> <span data-ttu-id="525c8-128">1 = (impostazione predefinita) filetime inclusi</span><span class="sxs-lookup"><span data-stu-id="525c8-128">1 = (default) filetimes are included</span></span>


- <span data-ttu-id="525c8-129">È stato risolto un problema che causava la scomparsa delle immagini in linea quando si rispondeva a un messaggio con un'etichetta di protezione da Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="525c8-129">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-18"></a><span data-ttu-id="525c8-131">Versione 2011: 18 novembre</span><span class="sxs-lookup"><span data-stu-id="525c8-131">Version 2011: November 18</span></span>
<span data-ttu-id="525c8-132">*Versione 2011 (Build 13426.20250)*</span><span class="sxs-lookup"><span data-stu-id="525c8-132">*Version 2011 (Build 13426.20250)*</span></span>
* <span data-ttu-id="525c8-133">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-133">Various bugs and performance fixes.</span></span>

## <a name="version-2011-november-16"></a><span data-ttu-id="525c8-134">Versione 2011: 16 novembre</span><span class="sxs-lookup"><span data-stu-id="525c8-134">Version 2011: November 16</span></span>
<span data-ttu-id="525c8-135">*Versione 2011 (Build 13426.20234)*</span><span class="sxs-lookup"><span data-stu-id="525c8-135">*Version 2011 (Build 13426.20234)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-137">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-137">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-138">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-138">Outlook</span></span>

- <span data-ttu-id="525c8-139">**Stessa firma, tutti i dispositivi:** la firma viene archiviata nel cloud.</span><span class="sxs-lookup"><span data-stu-id="525c8-139">**Same signature, all devices:** Your signature is stored in the cloud.</span></span> <span data-ttu-id="525c8-140">È sufficiente crearla una sola volta per poterla usare ovunque si usi Outlook.</span><span class="sxs-lookup"><span data-stu-id="525c8-140">Create it once and use it everywhere you use Outlook.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-143">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-143">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-144">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-144">Outlook</span></span>

- <span data-ttu-id="525c8-145">È stato risolto un problema per cui il campo A era vuoto quando di inviava una relazione sullo stato su un’attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-145">We fixed an issue that caused the To field to be blank when sending a status report on a task.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-146">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-146">PowerPoint</span></span>

- <span data-ttu-id="525c8-147">È stato risolto un problema di VBA in cui Slide.Shapes.AddMediaObject2 si arrestava in modo anomalo con formati video legacy (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="525c8-147">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 crashing with legacy video formats (MPG-1,Mpeg-2).</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2011-november-09"></a><span data-ttu-id="525c8-149">Versione 2011: 09 novembre</span><span class="sxs-lookup"><span data-stu-id="525c8-149">Version 2011: November 09</span></span>
<span data-ttu-id="525c8-150">*Versione 2011 (Build 13426.20184)*</span><span class="sxs-lookup"><span data-stu-id="525c8-150">*Version 2011 (Build 13426.20184)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-152">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-152">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-153">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-153">Excel</span></span>

- <span data-ttu-id="525c8-154">**Creare flussi di dati di Power Platform dalle query:** è ora possibile esportare le query in modelli di Power query che possono essere usati per creare nuovi flussi di dati di Power Platform</span><span class="sxs-lookup"><span data-stu-id="525c8-154">**Create Power Platform dataflows from queries:** You can now export your queries into Power Query templates that can be used to create new Power Platform dataflows</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-157">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-157">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-158">Accesso</span><span class="sxs-lookup"><span data-stu-id="525c8-158">Access</span></span>

- <span data-ttu-id="525c8-159">È stato risolto un problema per cui alcuni utenti vedevano un errore di tipo risorse di sistema insufficienti tentando di esportare una query dalla cartella di OneDrive sincronizzata.</span><span class="sxs-lookup"><span data-stu-id="525c8-159">We fixed an issue where some users were seeing the "system resource exceeded" error when they tried to export a query from their synced OneDrive folder.</span></span>


- <span data-ttu-id="525c8-160">È stato risolto un problema relativo al passaggio automatico tra finestre delle maschere.</span><span class="sxs-lookup"><span data-stu-id="525c8-160">We fixed an issue where 'auto'-switching between form windows was switching to another form.</span></span>


- <span data-ttu-id="525c8-161">È stato risolto un problema per cui l'uso di DAO da applicazioni non di Office causava la chiusura imprevista dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-161">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="excel"></a><span data-ttu-id="525c8-162">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-162">Excel</span></span>

- <span data-ttu-id="525c8-163">È stato risolto un problema relativo al fatto che il nome del file non cambiava dopo aver abilitato l'operazione SaveAs con i componenti aggiuntivi COM.</span><span class="sxs-lookup"><span data-stu-id="525c8-163">We fixed an issue where Filename was not changing after a SaveAs operation with COM add-ins enabled.</span></span>


- <span data-ttu-id="525c8-164">È stato risolto un problema con Power Pivot che si verificava quando si usava la connessione a un database Oracle.</span><span class="sxs-lookup"><span data-stu-id="525c8-164">Fixed an issue with Power Pivot when using a connection to an Oracle database.</span></span>


- <span data-ttu-id="525c8-165">È stato risolto un problema per cui il salvataggio automatico restituiva un messaggio di errore errato o ingannevole quando nel modello di dati di Excel era presente una definizione di misura errata.</span><span class="sxs-lookup"><span data-stu-id="525c8-165">We fixed an issue when Auto-Save fails with incorrect/misleading error message when there's a bad measure definition in the Excel data model.</span></span>


- <span data-ttu-id="525c8-166">È stato risolto un problema per cui Excel si chiudeva in modo imprevisto quando venivano attivati il processo di calcolo MTR e l'aggiornamento dei criteri di gruppo, ad esempio tramite aggiornamento dei criteri di gruppo in remoto.</span><span class="sxs-lookup"><span data-stu-id="525c8-166">We fixed an issue where Excel terminated unexpectedly when the process of MTR calc and Group Policy Object update (e.g. via Remote Group Policy Refresh) was triggered.</span></span>


- <span data-ttu-id="525c8-167">È stato risolto un problema per cui un utente non era in grado di aprire il file atomsvc (UTF8 + BOM) direttamente da SharePoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-167">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="525c8-168">È stato risolto un problema per cui lo zoom avanti e indietro dall’area di presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-168">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="525c8-169">È stato risolto un problema per cui Word appariva bloccato quando si inseriva una cartella di lavoro di Excel in un documento di Word.</span><span class="sxs-lookup"><span data-stu-id="525c8-169">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


### <a name="outlook"></a><span data-ttu-id="525c8-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-170">Outlook</span></span>

- <span data-ttu-id="525c8-171">È stato risolto un problema che causava talvolta l'arresto di Outlook quando si aggiungevano o si salvano allegati.</span><span class="sxs-lookup"><span data-stu-id="525c8-171">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


- <span data-ttu-id="525c8-172">È stato risolto un problema per cui la stampa rapida per gli allegati di immagini generava l'errore "Impossibile per Windows trovare questa immagine.</span><span class="sxs-lookup"><span data-stu-id="525c8-172">We fixed an issue where quick print for image attachments resulted in error, "Windows can't find this picture.</span></span> <span data-ttu-id="525c8-173">Controllare il percorso e riprovare".</span><span class="sxs-lookup"><span data-stu-id="525c8-173">Check the location, and then try again".</span></span>


- <span data-ttu-id="525c8-174">È stato risolto un problema per cui, per alcuni utenti, Outlook si avviava in modalità offline finché l'utente sceglieva di lavorare online. </span><span class="sxs-lookup"><span data-stu-id="525c8-174">We fixed an issue that caused some users to see Outlook start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="525c8-175">È stato risolto un problema per cui, incollando un URL copiato dalla posizione della riunione a un'altra posizione, ad esempio un browser, l'URL terminava con un punto e virgola.</span><span class="sxs-lookup"><span data-stu-id="525c8-175">We fixed an issue when pasting a URL copied from meeting location to somewhere else (such as a browser), the URL contains a semicolon at the end.</span></span>


- <span data-ttu-id="525c8-176">È stato risolto un problema che impediva agli utenti di eliminare gli appuntamenti nel calendario dei Gruppi di Microsoft 365 nell'autenticazione di base.</span><span class="sxs-lookup"><span data-stu-id="525c8-176">We fixed an issue where users were unable to delete appointments in Calendar of Microsoft 365 Groups in Basic Auth.</span></span>


- <span data-ttu-id="525c8-177">È stato risolto un problema che impediva l'avvio di Outlook durante il caricamento della cache dei soprannomi.</span><span class="sxs-lookup"><span data-stu-id="525c8-177">We fixed an issue where starting Outlook failed while loading nickname cache.</span></span>


- <span data-ttu-id="525c8-178">È stato risolto un problema per cui il proprietario della cassetta postale non riusciva a gestire le autorizzazioni condivise per il proprio calendario perché l'opzione era disattivata.</span><span class="sxs-lookup"><span data-stu-id="525c8-178">We fixed an issue where a mailbox owner wasn't able to manage Shared permission for their own Calendar as the option was greyed out.</span></span>


- <span data-ttu-id="525c8-179">È stato risolto un problema per cui in Outlook non era possibile creare un messaggio con autorizzazioni limitate.</span><span class="sxs-lookup"><span data-stu-id="525c8-179">We fixed an issue where Outlook was not able to create a message with restricted permission.</span></span>


- <span data-ttu-id="525c8-180">È stato risolto un problema per cui se si salvava un modello di posta elettronica come .OFT i caratteri cinesi venivano trasformati in punti interrogativi.</span><span class="sxs-lookup"><span data-stu-id="525c8-180">We fixed an issue where saving email templates as .OFT changed Chinese characters to question marks.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-181">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-181">PowerPoint</span></span>

- <span data-ttu-id="525c8-182">È stato risolto un problema per cui lo zoom avanti e indietro dall’area di presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-182">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="525c8-183">È stato risolto un problema per cui nell'icona del segnaposto dei contenuti accanto a Immagini non era presente una descrizione comando.</span><span class="sxs-lookup"><span data-stu-id="525c8-183">We fixed an issue where in content placeholder icon next to Pictures didn't have a tooltip.</span></span>


- <span data-ttu-id="525c8-184">È stato risolto un problema per cui la vista protetta della presentazione, visualizzata da file di pptsx, consentiva l'acquisizione dello schermo di un documento protetto da IRM.</span><span class="sxs-lookup"><span data-stu-id="525c8-184">We have fixed an issue where Protected view of slide show, shown by pptsx file, allows screen capture of IRM protected document.</span></span>


- <span data-ttu-id="525c8-185">È stato risolto un problema per cui le linee della griglia venivano spostate dalle diapositive quando si chiudeva il riquadro di progettazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-185">We fixed an issue where grid lines were getting shifted from slides when closing design pane.</span></span>


- <span data-ttu-id="525c8-186">È stato risolto un problema per cui, duplicando una presentazione su un monitor secondario, la presentazione poteva risultare nascosta dietro un'altra finestra.</span><span class="sxs-lookup"><span data-stu-id="525c8-186">We fixed an issue when duplicating slideshow to secondary monitor, the slideshow may hide behind other window.</span></span>


- <span data-ttu-id="525c8-187">È stato risolto un problema per cui la barra di scorrimento nella diapositiva iniziava a regolarsi dopo l'interruzione della registrazione dello schermo con il riquadro di selezione aperto.</span><span class="sxs-lookup"><span data-stu-id="525c8-187">We fixed an issue where the scroll bar in the slide starts adjusting itself after stopping screen recording with selection pane opened.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-188">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-188">Project</span></span>

- <span data-ttu-id="525c8-189">È stato risolto un problema per cui il valore di NewVal nell'evento ProjectBeforeTaskChagne non aveva il valore corretto se un intervallo veniva modificato all'interno di una visualizzazione tipo di modulo attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-189">Fixed an issue where the NewVal in the ProjectBeforeTaskChagne event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


- <span data-ttu-id="525c8-190">È stato risolto un problema per cui Project poteva chiudersi in modo imprevisto all'apertura di file in cui i profili delle risorse erano specificati in un certo modo.</span><span class="sxs-lookup"><span data-stu-id="525c8-190">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="525c8-191">È stato risolto un problema per cui, salvando un progetto da PWA a un file MPP locale, veniva generato l'evento ProjectBeforeTaskChangeEvent per dati che in realtà l'utente non aveva modificato.</span><span class="sxs-lookup"><span data-stu-id="525c8-191">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="525c8-192">È stato risolto un problema per cui gli impegni delle risorse eseguivano la ricerca di una risorsa per nome anziché come GUID. Ciò causava problemi quando erano presenti più risorse con lo stesso nome.</span><span class="sxs-lookup"><span data-stu-id="525c8-192">Fixed an issue where resource engagements searched for a resource by name instead of GUID which would cause issues if there were multiple resources with the same name.</span></span>


- <span data-ttu-id="525c8-193">È stato risolto un problema per cui, se si dispone di un elenco attività in un sito di progetto e si raggruppa l'elenco attività, non sarà possibile modificare rapidamente l'elenco attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-193">Fixed an issue where if you have a task list in a project site and group the task list, you will not be able to quick edit the task list.</span></span>


- <span data-ttu-id="525c8-194">È stato risolto un problema per cui, se si aggiorna una risorsa dell'organizzazione con CSOM, le unità di risorse max potrebbero andare perse.</span><span class="sxs-lookup"><span data-stu-id="525c8-194">Fixed an issue where if you update an enterprise resource via CSOM, resource max units may be lost.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-195">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-195">Word</span></span>

- <span data-ttu-id="525c8-196">È stato risolto un problema per cui lo zoom avanti e indietro dall’area di presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-196">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>


- <span data-ttu-id="525c8-197">È stato risolto un problema per cui facendo clic sull'indicatore del commento non veniva eseguito lo zoom indietro per mostrare la scheda del commento nella visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-197">We fixed an issue where clicking comment hint didn't zoom out to show comment card in view.</span></span>


- <span data-ttu-id="525c8-198">È stato risolto un problema di layout per cui talvolta la linea tra le colonne era spostata.</span><span class="sxs-lookup"><span data-stu-id="525c8-198">We fixed a layout issue which the line between columns might have shifted.</span></span>


- <span data-ttu-id="525c8-199">È stato risolto un problema relativo al rilevamento delle modifiche per cui talvolta, all'apertura di un documento di Word, veniva visualizzata una finestra di errore.</span><span class="sxs-lookup"><span data-stu-id="525c8-199">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="525c8-200">È stato risolto un problema per cui Word appariva bloccato quando si inseriva una cartella di lavoro di Excel in un documento di Word.</span><span class="sxs-lookup"><span data-stu-id="525c8-200">We fixed an issue where Word appears to hang when inserting an Excel workbook into a Word document.</span></span>


- <span data-ttu-id="525c8-201">È stato risolto un problema di stampa che si verificava applicando etichette di riservatezza con filigrana.</span><span class="sxs-lookup"><span data-stu-id="525c8-201">We fixed a print issue when sensitivity label with watermarks are applied.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-202">Famiglia di prodotti di Office</span><span class="sxs-lookup"><span data-stu-id="525c8-202">Office Suite</span></span>

- <span data-ttu-id="525c8-203">È stato risolto un problema dello strumento di distribuzione di Office per cui era possibile la configurazione quando si usava la funzionalità RemoveMSI con il prodotto Office 2007 "Segnalazione errori applicazioni Microsoft".</span><span class="sxs-lookup"><span data-stu-id="525c8-203">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="525c8-204">È stato risolto un problema per cui l'accesso interattivo API SSO restituiva un codice di errore.</span><span class="sxs-lookup"><span data-stu-id="525c8-204">We fixed an issue where SSO API interactive Sign-In was returning an error code.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-november-06"></a><span data-ttu-id="525c8-206">Versione 2010: 6 novembre</span><span class="sxs-lookup"><span data-stu-id="525c8-206">Version 2010: November 06</span></span>
<span data-ttu-id="525c8-207">*Versione 2010 (Build 13328.20356)*</span><span class="sxs-lookup"><span data-stu-id="525c8-207">*Version 2010 (Build 13328.20356)*</span></span>
* <span data-ttu-id="525c8-208">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-208">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2010-november-04"></a><span data-ttu-id="525c8-211">Versione 2010: 4 novembre</span><span class="sxs-lookup"><span data-stu-id="525c8-211">Version 2010: November 04</span></span>
<span data-ttu-id="525c8-212">*Versione 2010 (Build 13328.20340)*</span><span class="sxs-lookup"><span data-stu-id="525c8-212">*Version 2010 (Build 13328.20340)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-214">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-214">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-215">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-215">Excel</span></span>

- <span data-ttu-id="525c8-216">**Supporto per Appunti SVG:** è ora possibile incollare il contenuto SVG di Office in un'app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-216">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="525c8-217">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-217">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="outlook"></a><span data-ttu-id="525c8-218">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-218">Outlook</span></span>

- <span data-ttu-id="525c8-219">**Supporto per Appunti SVG:** è ora possibile incollare il contenuto SVG di Office in un'app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-219">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="525c8-220">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-220">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)

### <a name="powerpoint"></a><span data-ttu-id="525c8-221">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-221">PowerPoint</span></span>

- <span data-ttu-id="525c8-222">**Supporto per Appunti SVG:** è ora possibile incollare il contenuto SVG di Office in un'app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-222">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="525c8-223">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-223">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)<br /><span data-ttu-id="525c8-224">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)</span><span class="sxs-lookup"><span data-stu-id="525c8-224">See details in [blog post](https://insider.office.com/en-us/blog/svg-content-office-third-party-apps)</span></span>

- <span data-ttu-id="525c8-225">**Creare GIF con sfondi trasparenti:** all'esportazione in una GIF animata, una nuova opzione consente di rendere trasparente lo sfondo.</span><span class="sxs-lookup"><span data-stu-id="525c8-225">**Create GIFs with Transparent Backgrounds:** When exporting to an Animated GIF, a new option will allow you to make the background transparent.</span></span><br /><span data-ttu-id="525c8-226">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)</span><span class="sxs-lookup"><span data-stu-id="525c8-226">See details in [blog post](https://insider.office.com/en-us/blog/export-animated-gifs-transparent-backgrounds)</span></span>

- <span data-ttu-id="525c8-227">**Esportare immagini GIF animate in un intervallo:** selezionare un intervallo di diapositive durante l'esportazione in formato GIF animata</span><span class="sxs-lookup"><span data-stu-id="525c8-227">**Export animated GIF in a range:** Select a range of slides when exporting to animated GIF</span></span>

### <a name="word"></a><span data-ttu-id="525c8-228">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-228">Word</span></span>

- <span data-ttu-id="525c8-229">**Supporto per Appunti SVG:** è ora possibile incollare il contenuto SVG di Office in un'app di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-229">**SVG Clipboard Support:** You can now paste SVG content from Office into 3rd party apps.</span></span> [<span data-ttu-id="525c8-230">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-230">Learn more</span></span>](https://support.office.com/article/69f29d39-194a-4072-8c35-dbe5e7ea528c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-233">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-233">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-234">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-234">Outlook</span></span>

- <span data-ttu-id="525c8-235">È stato risolto un problema che impediva agli utenti di concedere le autorizzazioni di Editor ai delegati.</span><span class="sxs-lookup"><span data-stu-id="525c8-235">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-236">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-236">Office Suite</span></span>

- <span data-ttu-id="525c8-237">È stato risolto un problema che causava un errore durante il tentativo di salvare file passati dallo stato di sincronizzazione inversa a solo server.</span><span class="sxs-lookup"><span data-stu-id="525c8-237">We fixed an issue that was causing a failure when trying to save files that have transitioned from syncbacked to server-only.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-27"></a><span data-ttu-id="525c8-239">Versione 2010: 27 ottobre</span><span class="sxs-lookup"><span data-stu-id="525c8-239">Version 2010: October 27</span></span>
<span data-ttu-id="525c8-240">*Versione 2010 (Build 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="525c8-240">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-244">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-244">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-245">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-245">Outlook</span></span>

- <span data-ttu-id="525c8-246">È stato risolto un problema per cui le impostazioni cloud non risultavano attivate per gli utenti per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="525c8-246">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="525c8-247">È stato risolto un problema per cui le modifiche alla firma di un utente non venivano salvate.</span><span class="sxs-lookup"><span data-stu-id="525c8-247">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-24"></a><span data-ttu-id="525c8-249">Versione 2010: 24 ottobre</span><span class="sxs-lookup"><span data-stu-id="525c8-249">Version 2010: October 24</span></span>
<span data-ttu-id="525c8-250">*Versione 2010 (Build 13328.20278)*</span><span class="sxs-lookup"><span data-stu-id="525c8-250">*Version 2010 (Build 13328.20278)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-254">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-254">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-255">Outlook</span></span>

- <span data-ttu-id="525c8-256">È stato risolto un problema per cui le intestazioni dei messaggi in cinese erano illeggibili in caso di risposta o inoltro.</span><span class="sxs-lookup"><span data-stu-id="525c8-256">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="525c8-257">È stato risolto un problema per cui, salvando in formato OTF, i caratteri in cinese venivano trasformati in punti interrogativi.</span><span class="sxs-lookup"><span data-stu-id="525c8-257">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-258">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-258">Project</span></span>

- <span data-ttu-id="525c8-259">È stato risolto un problema per cui, salvando un progetto da PWA a un file MPP locale, veniva generato l'evento ProjectBeforeTaskChangeEvent per dati che in realtà l'utente non aveva modificato.</span><span class="sxs-lookup"><span data-stu-id="525c8-259">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="525c8-260">È stato risolto un problema per cui il valore di NewVal nell'evento ProjectBeforeTaskChange non aveva il valore corretto modificando un intervallo all'interno di una visualizzazione Maschera attività - Tipo.</span><span class="sxs-lookup"><span data-stu-id="525c8-260">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-19"></a><span data-ttu-id="525c8-262">Versione 2010: 19 ottobre</span><span class="sxs-lookup"><span data-stu-id="525c8-262">Version 2010: October 19</span></span>
<span data-ttu-id="525c8-263">*Versione 2010 (Build 13328.20210)*</span><span class="sxs-lookup"><span data-stu-id="525c8-263">*Version 2010 (Build 13328.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-265">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-265">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-266">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-266">Outlook</span></span>

- <span data-ttu-id="525c8-267">**Risparmiare tempo durante la composizione dei messaggi:** Outlook mostra dei  suggerimenti che consentono di scrivere rapidamente i messaggi.</span><span class="sxs-lookup"><span data-stu-id="525c8-267">**Save time while composing messages:** Outlook shows you writing suggestions that help you compose messages quickly.</span></span> <span data-ttu-id="525c8-268">Per accettare il suggerimento, basta usare l’opzione TAB.</span><span class="sxs-lookup"><span data-stu-id="525c8-268">To accept the suggestion, just use the Tab key.</span></span><br /><span data-ttu-id="525c8-269">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/text-predictions-in-word-outlook)</span><span class="sxs-lookup"><span data-stu-id="525c8-269">See details in [blog post](https://insider.office.com/en-us/blog/text-predictions-in-word-outlook)</span></span>

- <span data-ttu-id="525c8-270">**Supera le barriere linguistiche con un traduttore integrato:** i componenti aggiuntivi per la traduzione non servono più!</span><span class="sxs-lookup"><span data-stu-id="525c8-270">**Break the language barrier with a built-in translator:** Add-ins for translation aren't required anymore!</span></span> <span data-ttu-id="525c8-271">In un messaggio, basta fare doppio clic per tradurre parole, frasi o interi messaggi.</span><span class="sxs-lookup"><span data-stu-id="525c8-271">In a message, right-click to translate specific words, phrases, or the whole message.</span></span> [<span data-ttu-id="525c8-272">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-272">Learn more</span></span>](https://support.office.com/article/287380e4-a56c-48a1-9977-f2dca89ce93f)

- <span data-ttu-id="525c8-273">**Aggiornamenti dell’esperienza utente per Attività:** aggiornamento visivo degli elementi di Attività </span><span class="sxs-lookup"><span data-stu-id="525c8-273">**User Experience Updates for Tasks:** A visual refresh of task items</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-274">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-274">PowerPoint</span></span>

- <span data-ttu-id="525c8-275">**Esercitarsi con la presentazione con Training per relatore:** esercitarsi con gli elementi che consentono di coinvolgere il pubblico, ad esempio l’andatura, le parole sovrautilizzate, il linguaggio del corpo e così via.</span><span class="sxs-lookup"><span data-stu-id="525c8-275">**Practice your presentation with Presenter Coach:** Get coaching on the things that help keep an audience engaged — like pacing, overused words, body language, and more.</span></span> [<span data-ttu-id="525c8-276">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-276">Learn more</span></span>](https://support.office.com/article/cd7fc941-5c3b-498c-a225-83ef3f64f07b)

### <a name="word"></a><span data-ttu-id="525c8-277">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-277">Word</span></span>

- <span data-ttu-id="525c8-278">**Il riquadro Editor Microsoft ottiene un aggiornamento in Word per il desktop:** è stata aggiornata l'esperienza corrente con il riquadro Editor per i client desktop di Word.</span><span class="sxs-lookup"><span data-stu-id="525c8-278">**Microsoft Editor pane gets an update in Word for desktop:** We have upgraded the current experience with the Editor pane in Word for desktop clients.</span></span>

- <span data-ttu-id="525c8-279">**Suggerimenti per la scrittura con un clic:** applicare i suggerimenti per la scrittura con un singolo clic.</span><span class="sxs-lookup"><span data-stu-id="525c8-279">**One-click writing suggestions:** Apply writing suggestions with a single click.</span></span> <span data-ttu-id="525c8-280">Il riquadro Editor aggiornato facilita lo spostamento tra i suggerimenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-280">The updated Editor pane makes it easy to navigate between suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-283">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-283">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="525c8-284">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-284">PowerPoint</span></span>

- <span data-ttu-id="525c8-285">Si tratta della correzione di un problema che causava la visualizzazione della richiesta di salvataggio a ciclo continuo durante la chiusura di un documento se era presente un componente aggiuntivo per l’ascolto dell’evento PresentationBeforeClose e il controllo della proprietà Presentation.Saved come parte del gestore dell'evento.</span><span class="sxs-lookup"><span data-stu-id="525c8-285">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>



[//]: # (NON RIMUOVERE FINE DE CONTENUTO DEI BUG)

## <a name="version-2010-october-11"></a><span data-ttu-id="525c8-287">Versione 2010: 11 ottobre</span><span class="sxs-lookup"><span data-stu-id="525c8-287">Version 2010: October 11</span></span>
<span data-ttu-id="525c8-288">*Versione 2010 (Build 13328.20154)*</span><span class="sxs-lookup"><span data-stu-id="525c8-288">*Version 2010 (Build 13328.20154)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-290">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-290">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-291">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-291">Excel</span></span>

- <span data-ttu-id="525c8-292">**Proteggere i dati contro i file dannosi:** Application Guard migliora la protezione contro i malware consentendo di leggere, stampare e salvare i file di Office in un contenitore isolato.</span><span class="sxs-lookup"><span data-stu-id="525c8-292">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="525c8-293">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-293">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="powerpoint"></a><span data-ttu-id="525c8-294">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-294">PowerPoint</span></span>

- <span data-ttu-id="525c8-295">**Proteggere i dati contro i file dannosi:** Application Guard migliora la protezione contro i malware consentendo di leggere, stampare e salvare i file di Office in un contenitore isolato.</span><span class="sxs-lookup"><span data-stu-id="525c8-295">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="525c8-296">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-296">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)

### <a name="word"></a><span data-ttu-id="525c8-297">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-297">Word</span></span>

- <span data-ttu-id="525c8-298">**Proteggere i dati contro i file dannosi:** Application Guard migliora la protezione contro i malware consentendo di leggere, stampare e salvare i file di Office in un contenitore isolato.</span><span class="sxs-lookup"><span data-stu-id="525c8-298">**Help protect your data from malicious files:** Application Guard helps protect you from malware by letting you read, print, and save Office files in an isolated container.</span></span> [<span data-ttu-id="525c8-299">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-299">Learn more</span></span>](https://support.office.com/article/9e0fb9c2-ffad-43bf-8ba3-78f785fdba46)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-302">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-302">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-303">Accesso</span><span class="sxs-lookup"><span data-stu-id="525c8-303">Access</span></span>

- <span data-ttu-id="525c8-304">È stato risolto un problema relativo all’errata impostazione della posizione della barra di scorrimento durante il caricamento della finestra di dialogo/relazione salvata durante lo scorrimento.</span><span class="sxs-lookup"><span data-stu-id="525c8-304">We fixed an issue where scrollbar position was not set correctly when loading query/relationship window saved while scrolled.</span></span>


- <span data-ttu-id="525c8-305">È stato risolto un problema relativo alla errata visualizzazione di nomi contenenti "&" nel Riquadro attività Aggiungi tabella.</span><span class="sxs-lookup"><span data-stu-id="525c8-305">We fixed an issue where Add Table Task Pane was not displaying names containing '&' correctly.</span></span>


### <a name="excel"></a><span data-ttu-id="525c8-306">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-306">Excel</span></span>

- <span data-ttu-id="525c8-307">È stato risolto un problema relativo al mancato funzionamento dell’intervallo manuale a più livelli di categoria nei grafici.</span><span class="sxs-lookup"><span data-stu-id="525c8-307">We fixed an issue where multi-level category manual interval was not working in charts.</span></span>


- <span data-ttu-id="525c8-308">È stato risolto un problema con i grafici a mappa 2D che impediva di usare VBA per configurare il colori per il valore massimo, medio e minimo.</span><span class="sxs-lookup"><span data-stu-id="525c8-308">Fixed an issue with 2D Map Charts where using VBA to set the colors for the max, mid, and min values for a series was not working.</span></span>


- <span data-ttu-id="525c8-309">È stato risolto un problema che causava la visualizzazione del messaggio "Excel ha esaurito le risorse durante il tentativo di calcolare una o più formule".</span><span class="sxs-lookup"><span data-stu-id="525c8-309">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="525c8-310">È stato risolto un problema per cui, quando si selezionava lo spagnolo come lingua di Office, gli elenchi di convalida dei dati non mostravano tutti gli elementi.</span><span class="sxs-lookup"><span data-stu-id="525c8-310">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="525c8-311">È stato risolto un problema per cui poteva verificarsi un notevole ritardo durante il passaggio tra fogli di lavoro con grandi quantità di dati quando era "Anteprima interruzioni di pagina" era abilitato.</span><span class="sxs-lookup"><span data-stu-id="525c8-311">Fixed an issue where there could be a noticeable delay when switching between worksheets with large amounts of data when 'Page Break Preview' was enabled.</span></span>


- <span data-ttu-id="525c8-312">È stato risolto un problema relativo al mancato aggiornamento delle opzioni di tutti i fogli della cartella di lavoro in seguito all'aggiunta a una tabella usata per la Convalida dei dati.</span><span class="sxs-lookup"><span data-stu-id="525c8-312">We fixed an issue where adding to a table used for Data Validation did not update options for all sheets in the workbook.</span></span>


- <span data-ttu-id="525c8-313">È stato risolto un problema che poteva causare un blocco durante l'aggiornamento delle tabelle pivot OLAP.</span><span class="sxs-lookup"><span data-stu-id="525c8-313">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="525c8-314">È stato risolto un problema che causava l'arresto anomalo di ChartSheet, in certi casi, quando veniva inserita una formula tramite la barra della formula.</span><span class="sxs-lookup"><span data-stu-id="525c8-314">Fixed an issue where ChartSheet crashed in some cases when a formula is entered through formula bar.</span></span>


- <span data-ttu-id="525c8-315">È stato risolto un problema per cui la barra della formula di Excel non veniva visualizzata interamente quando la connessione a un dispositivo veniva interrotta, ad esempio in caso di connessione/disconnessione di una sessione remota o di un cambio del monitor.</span><span class="sxs-lookup"><span data-stu-id="525c8-315">We fixed an issue where the Excel formula bar would not render completely after connection to a device was lost, such as a remote session connect/disconnect or a monitor change.</span></span>


### <a name="onenote"></a><span data-ttu-id="525c8-316">OneNote</span><span class="sxs-lookup"><span data-stu-id="525c8-316">OneNote</span></span>

- <span data-ttu-id="525c8-317">È stato risolto un problema per cui un utente non era in grado di selezionare e copiare l'URL del blocco appunti da TextBox in File OutSpace > Info.</span><span class="sxs-lookup"><span data-stu-id="525c8-317">We fixed an issue where a user was unable to select and copy notebook URL from textbox in OutSpace File > Info.</span></span>


- <span data-ttu-id="525c8-318">È stato risolto un problema per cui, quando si passava il mouse sopra al colore verde nel selettore colore del blocco appunti, il pop-up indicava "gessetto rosso".</span><span class="sxs-lookup"><span data-stu-id="525c8-318">We fixed an issue when you hover over green color in notebook color selector, the pop up reads "red chalk".</span></span>


- <span data-ttu-id="525c8-319">È stato risolto un problema relativo al mancato rispetto dei colori a contrasto elevato nell'area di disegno per i temi personalizzati da parte di OneNote.</span><span class="sxs-lookup"><span data-stu-id="525c8-319">We fixed an issue where OneNote didn't honor High Contrast colors in the canvas for custom themes.</span></span>


### <a name="outlook"></a><span data-ttu-id="525c8-320">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-320">Outlook</span></span>

- <span data-ttu-id="525c8-321">Risolve un problema che causava l'invio di e-mail generate automaticamente con un corpo vuoto quando l'oggetto è vuoto.</span><span class="sxs-lookup"><span data-stu-id="525c8-321">Addresses an issue that caused automatically generated emails to be sent with a blank body when the subject is blank.</span></span>


- <span data-ttu-id="525c8-322">È stato risolto un problema per cui il GUID della cartella errata è memorizzato nella cache per le cartelle.</span><span class="sxs-lookup"><span data-stu-id="525c8-322">We fixed an issue where the wrong folder guid is cached for folders.</span></span>


- <span data-ttu-id="525c8-323">Quando un utente copiava e incollava un indirizzo di posta elettronica nel campo del destinatario con il nome visualizzato, l'indirizzo non era sempre analizzato correttamente e veniva visualizzato un avviso relativo a un indirizzo di posta elettronica non valido.</span><span class="sxs-lookup"><span data-stu-id="525c8-323">When a user copy-and-pastes an email address into the recipient field with the display name, the email address wasn't always parsed correctly and caused a warning about an invalid email address to appear.</span></span>  <span data-ttu-id="525c8-324">Il problema è stato risolto: ora il mome e l'indirizzo sono analizzati correttamente e l'avviso non viene più mostrato.</span><span class="sxs-lookup"><span data-stu-id="525c8-324">It's been fixed so the name and email address are parsed correctly so the warning is no longer shown.</span></span>


- <span data-ttu-id="525c8-325">È stato risolto un problema per cui le cartelle condivise online non restituivano il nome della cartella padre.</span><span class="sxs-lookup"><span data-stu-id="525c8-325">We fixed an issue where online shared folders did not return parent folder name.</span></span> <span data-ttu-id="525c8-326">Invece di dare errore, restituiva un percorso vuoto che erroneamente passava all'account principale.</span><span class="sxs-lookup"><span data-stu-id="525c8-326">Intsead of failing, it returned an empty path which incorrectly went to the primary account.</span></span>


- <span data-ttu-id="525c8-327">È stato risolto un problema per cui l'opzione Salva con nome non era disponibile per gli allegati classici.</span><span class="sxs-lookup"><span data-stu-id="525c8-327">We fixed an issue where the Save As option was not available for classic attachments.</span></span>


- <span data-ttu-id="525c8-328">È stato risolto un problema che consente agli utenti di personalizzare il testo della giustificazione quando si esegue l'override di un criterio.</span><span class="sxs-lookup"><span data-stu-id="525c8-328">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="525c8-329">È stato risolto un problema per cui le revisioni si attivavano dopo la riapertura delle bozze dal riquadro di anteprima di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="525c8-329">We fixed an issue where track changes turned on after reopening draft from read-only preview pane.</span></span>


- <span data-ttu-id="525c8-330">È stato risolto un problema per cui i messaggi di posta elettronica venivano nascosti dopo aver disattivato Posta in arrivo evidenziata e ordinato i dati.</span><span class="sxs-lookup"><span data-stu-id="525c8-330">We fixed an issue with emails being hidden after turning Focused Inbox off and doing a sort.</span></span>


- <span data-ttu-id="525c8-331">È stato risolto un problema che causava la creazione da parte di Outlook di una firma vuota secondaria per gli utenti che avevano abilitato le impostazioni cloud.</span><span class="sxs-lookup"><span data-stu-id="525c8-331">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-332">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-332">PowerPoint</span></span>

- <span data-ttu-id="525c8-333">È stato risolto un problema per cui PowerPoint non esportava i punti elenco rettangolari durante l'esportazione in formato PDF.</span><span class="sxs-lookup"><span data-stu-id="525c8-333">We fixed an issue where PowerPoint was not exporting rectangle bullet points while exporting to PDF.</span></span>


- <span data-ttu-id="525c8-334">È stato risolto un problema per cui le GIF erano animate solo una volta nell’editor e nelle diapositive.</span><span class="sxs-lookup"><span data-stu-id="525c8-334">We fixed an issue where GIF's would animate only once in the editor and slide shows.</span></span>


- <span data-ttu-id="525c8-335">È stato risolto un problema per cui il grafico di Excel collegato veniva modificato in modo errato nel foglio di Excel quando l'utente modificava il percorso di origine in una cartella locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="525c8-335">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="525c8-336">È stato risolto un problema per cui se ci si trova nell'ultima diapositiva e si scorre alla diapositiva successiva dopo aver premuto "Termina sessione" e prima che venga visualizzato il riepilogo, la finestra di dialogo Fine sessione è visibile anche nella pagina di riepilogo.</span><span class="sxs-lookup"><span data-stu-id="525c8-336">We fixed an issue that If you are on the last slide and if you swipe to the next slide after pressing 'End Session' and before the summary shows up, the End-Session dialog is visible on the summary page as well.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-337">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-337">Project</span></span>

- <span data-ttu-id="525c8-338">È stato risolto un problema per cui il metodo VBA ConsolidateProjects potrebbe fallire se si prova ad aggiungere più volte lo stesso progetto e se AttachToSources è impostato su falso.</span><span class="sxs-lookup"><span data-stu-id="525c8-338">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="525c8-339">È stato risolto un problema per cui, se si ha un codice di evento in esecuzione e si prova a modificare la visualizzazione di un modulo attività, facendo clic sul pulsante OK le modifiche potrebbero non essere inserite.</span><span class="sxs-lookup"><span data-stu-id="525c8-339">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


- <span data-ttu-id="525c8-340">È stato risolto un problema per cui il metodo VBA ConsolidateProjects potrebbe fallire se si prova ad aggiungere più volte lo stesso progetto e se AttachToSources è impostato su falso.</span><span class="sxs-lookup"><span data-stu-id="525c8-340">Fixed an issue where the ConsolidateProjects VBA method may file if you try to add the same project multiple times and have AttachToSources set to false.</span></span>


- <span data-ttu-id="525c8-341">È stato risolto un problema per cui, se si dispone di campi personalizzati con formule e si usa costo realizzato, è possibile notare ritardi nel cambio di visualizzazione e nell'apertura dei dettagli del progetto/attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-341">Fixed an issue where if you have custom fields with formulas and are using earned value, you may notice performance delays switching views and opening project/task details.</span></span>


- <span data-ttu-id="525c8-342">È stato risolto un problema per cui Project poteva bloccarsi se si applica un gruppo a Uso della risorsa o visualizzazione Foglio e quindi si inserisce una colonna.</span><span class="sxs-lookup"><span data-stu-id="525c8-342">Fixed an issue where Project may crash if you apply a group by to the Resource Usage or Sheet view and then insert a column.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-343">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-343">Word</span></span>

- <span data-ttu-id="525c8-344">È stato risolto un problema per cui i collegamenti ai file abilitati al flusso di lavoro non sono stati aperti come previsto.</span><span class="sxs-lookup"><span data-stu-id="525c8-344">We fixed an issue where links to workflow enabled files were not opening as expected.</span></span>


- <span data-ttu-id="525c8-345">È stato risolto un problema che causava la visualizzazione di un commento a comparsa quando l'utente toccava una modifica tracciata (inserimento/cancellazione).</span><span class="sxs-lookup"><span data-stu-id="525c8-345">Fixed an issue where a user tapping on a tracked change (insertion/deletion) would bring up a comment pop-out.</span></span>


- <span data-ttu-id="525c8-346">È stato risolto un problema relativo all'eliminazione dei callout di commento in Word.</span><span class="sxs-lookup"><span data-stu-id="525c8-346">We fixed an issue with deleting comment callouts in Word.</span></span>


- <span data-ttu-id="525c8-347">È stato risolto un problema relativo ai messaggi di Outlook configurati come "Non inoltrare".</span><span class="sxs-lookup"><span data-stu-id="525c8-347">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="525c8-348">È stato risolto un problema relativo al salvataggio di un documento di Word contenente citazioni ed equazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-348">We fixed an issue with saving Word document that contains citation and equation.</span></span>


- <span data-ttu-id="525c8-349">È stato risolto un problema con la finestra di dialogo raccolta Stili.</span><span class="sxs-lookup"><span data-stu-id="525c8-349">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-350">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-350">Office Suite</span></span>

- <span data-ttu-id="525c8-351">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="525c8-351">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="525c8-352">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="525c8-352">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-07"></a><span data-ttu-id="525c8-354">Versione 2009: ottobre 07</span><span class="sxs-lookup"><span data-stu-id="525c8-354">Version 2009: October 07</span></span>
<span data-ttu-id="525c8-355">*Versione 2009 (Build 13231.20360)*</span><span class="sxs-lookup"><span data-stu-id="525c8-355">*Version 2009 (Build 13231.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-357">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-357">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-358">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-358">Excel</span></span>

- <span data-ttu-id="525c8-359">**Creare tipi di dati con Power Query:** è possibile creare tipi di dati formattati con Power Query da qualsiasi origine dati</span><span class="sxs-lookup"><span data-stu-id="525c8-359">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-360">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-360">Outlook</span></span>

- <span data-ttu-id="525c8-361">**Il controllo grammaticale è tornato:** Outlook contrassegna gli errori grammaticali mentre si scrive, e l'utente può applicare i suggerimenti con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="525c8-361">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> <br /><span data-ttu-id="525c8-362">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="525c8-362">See details in [blog post](https://insider.office.com/en-us/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-365">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-365">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-366">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-366">Outlook</span></span>

- <span data-ttu-id="525c8-367">Risolve un problema che impediva di restituire i risultati delle ricerche eseguite su calendari condivisi con memorizzati nella cache.</span><span class="sxs-lookup"><span data-stu-id="525c8-367">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="525c8-368">Risolve un problema che causava, in certe circostanze, l'avvio inatteso di Outlook in modalità offline.</span><span class="sxs-lookup"><span data-stu-id="525c8-368">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="525c8-369">Risolve un problema che provocava errori intermittenti quando i delegati aprivano cartelle condivise in altre cassette postali.</span><span class="sxs-lookup"><span data-stu-id="525c8-369">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-370">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-370">PowerPoint</span></span>

- <span data-ttu-id="525c8-371">Correzione di sicurezza che risolve un problema che disabilitava le protezioni IRM quando si apriva un file PowerPoint nella modalità Visualizzazione protetta.</span><span class="sxs-lookup"><span data-stu-id="525c8-371">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-372">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-372">Office Suite</span></span>

- <span data-ttu-id="525c8-373">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="525c8-373">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="525c8-374">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="525c8-374">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-26"></a><span data-ttu-id="525c8-376">Versione 2009: 26 settembre</span><span class="sxs-lookup"><span data-stu-id="525c8-376">Version 2009: September 26</span></span>
<span data-ttu-id="525c8-377">*Versione 2009 (Build 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="525c8-377">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-379">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-379">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-380">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-380">Outlook</span></span>

- <span data-ttu-id="525c8-381">Risolve un problema che ha causato l'invio di messaggi di posta elettronica generati automaticamente con un corpo vuoto quando la riga dell'oggetto è vuota.</span><span class="sxs-lookup"><span data-stu-id="525c8-381">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-382">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-382">Project</span></span>

- <span data-ttu-id="525c8-383">È stato risolto un problema per cui, se si ha un codice di evento in esecuzione e si prova a modificare la visualizzazione di un modulo attività, facendo clic sul pulsante OK le modifiche potrebbero non essere inserite.</span><span class="sxs-lookup"><span data-stu-id="525c8-383">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-21"></a><span data-ttu-id="525c8-385">Versione 2009: 21 settembre</span><span class="sxs-lookup"><span data-stu-id="525c8-385">Version 2009: September 21</span></span>
<span data-ttu-id="525c8-386">*Versione 2009 (Build 13231.20200)*</span><span class="sxs-lookup"><span data-stu-id="525c8-386">*Version 2009 (Build 13231.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-388">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-388">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="525c8-389">Accesso</span><span class="sxs-lookup"><span data-stu-id="525c8-389">Access</span></span>

- <span data-ttu-id="525c8-390">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-390">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-391">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-391">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-392">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-392">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="excel"></a><span data-ttu-id="525c8-393">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-393">Excel</span></span>

- <span data-ttu-id="525c8-394">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-394">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="525c8-395">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="525c8-395">No conversion required.</span></span><br /><span data-ttu-id="525c8-396">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="525c8-396">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="525c8-397">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-397">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-398">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-398">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-399">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-399">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="onenote"></a><span data-ttu-id="525c8-400">OneNote</span><span class="sxs-lookup"><span data-stu-id="525c8-400">OneNote</span></span>

- <span data-ttu-id="525c8-401">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-401">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-402">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-402">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-403">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-403">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="outlook"></a><span data-ttu-id="525c8-404">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-404">Outlook</span></span>

- <span data-ttu-id="525c8-405">**Eliminare una conversazione con il proprietario del messaggio:** questa funzionalità consente di eliminare una conversazione dal proprietario del messaggio.</span><span class="sxs-lookup"><span data-stu-id="525c8-405">**Delete conversation by message owner:** This feature allows you to delete a conversation by message owner.</span></span>

- <span data-ttu-id="525c8-406">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-406">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="525c8-407">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="525c8-407">No conversion required.</span></span><br /><span data-ttu-id="525c8-408">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="525c8-408">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="525c8-409">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-409">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-410">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-410">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-411">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-411">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="powerpoint"></a><span data-ttu-id="525c8-412">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-412">PowerPoint</span></span>

- <span data-ttu-id="525c8-413">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-413">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="525c8-414">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="525c8-414">No conversion required.</span></span><br /><span data-ttu-id="525c8-415">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="525c8-415">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="525c8-416">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-416">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-417">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-417">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-418">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-418">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="project"></a><span data-ttu-id="525c8-419">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-419">Project</span></span>

- <span data-ttu-id="525c8-420">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-420">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-421">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-421">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-422">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-422">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="publisher"></a><span data-ttu-id="525c8-423">Publisher</span><span class="sxs-lookup"><span data-stu-id="525c8-423">Publisher</span></span>

- <span data-ttu-id="525c8-424">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-424">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-425">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-425">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-426">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-426">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="visio"></a><span data-ttu-id="525c8-427">Visio</span><span class="sxs-lookup"><span data-stu-id="525c8-427">Visio</span></span>

- <span data-ttu-id="525c8-428">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-428">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-429">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-429">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-430">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-430">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)

### <a name="word"></a><span data-ttu-id="525c8-431">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-431">Word</span></span>

- <span data-ttu-id="525c8-432">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-432">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="525c8-433">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="525c8-433">No conversion required.</span></span><br /><span data-ttu-id="525c8-434">Vedere i dettagli nel [post di blog](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="525c8-434">See details in [blog post](https://insider.office.com/en-us/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="525c8-435">**Cambiare automaticamente i temi di Office:** Office può cambiare automaticamente i temi in base alle impostazioni del tema di Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-435">**Switch Office themes automatically:** Office can automatically switch themes to match your Windows 10 theme settings.</span></span> <span data-ttu-id="525c8-436">Passare a File > Opzioni e selezionare "Usa impostazioni di sistema" accanto al tema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-436">Go to File > Options and select "Use system setting" next to Office Theme.</span></span> [<span data-ttu-id="525c8-437">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-437">Learn more</span></span>](https://support.office.com/article/63e65e1c-08d4-4dea-820e-335f54672310)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-440">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-440">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="525c8-441">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-441">PowerPoint</span></span>

- <span data-ttu-id="525c8-442">È stato risolto un problema che causava il rallentamento della creazione condivisa di file contenenti un numero elevato di determinati tipi di oggetto dati (E2o).</span><span class="sxs-lookup"><span data-stu-id="525c8-442">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2009-september-14"></a><span data-ttu-id="525c8-444">Versione 2009: 14 settembre</span><span class="sxs-lookup"><span data-stu-id="525c8-444">Version 2009: September 14</span></span>
<span data-ttu-id="525c8-445">*Versione 2009 (Build 13231.20152)*</span><span class="sxs-lookup"><span data-stu-id="525c8-445">*Version 2009 (Build 13231.20152)*</span></span>
* <span data-ttu-id="525c8-446">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-446">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2009-september-10"></a><span data-ttu-id="525c8-449">Versione 2009: 10 settembre</span><span class="sxs-lookup"><span data-stu-id="525c8-449">Version 2009: September 10</span></span>
<span data-ttu-id="525c8-450">*Versione 2009 (Build 13231,20126)*</span><span class="sxs-lookup"><span data-stu-id="525c8-450">*Version 2009 (Build 13231.20126)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-452">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-452">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-453">Accesso</span><span class="sxs-lookup"><span data-stu-id="525c8-453">Access</span></span>

- <span data-ttu-id="525c8-454">Questo problema è stato risolto e non si dovrebbe più riscontrare un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="525c8-454">This issue has now been resolved and you should no longer experience a crash.</span></span>


- <span data-ttu-id="525c8-455">È stato risolto un problema per cui le connessioni a un database ODBC non funzionavano con le applicazioni di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-455">We fixed an issue where connections to an ODBC database were not working with third party applications.</span></span>


### <a name="excel"></a><span data-ttu-id="525c8-456">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-456">Excel</span></span>

- <span data-ttu-id="525c8-457">È stato risolto un problema per cui, se si apriva un file contenente una funzione LET, veniva mostra l'avviso: "Si è verificato un problema con il contenuto del file "iltuofile.xlsx".</span><span class="sxs-lookup"><span data-stu-id="525c8-457">We fixed an issue where if you opened a file containing the LET function, it would display the alert:  "We found a problem with content in "your file.xlsx".</span></span> <span data-ttu-id="525c8-458">Si vuole provare a recuperare il più possibile?</span><span class="sxs-lookup"><span data-stu-id="525c8-458">Do you want us to try to recover as much as we can?</span></span> <span data-ttu-id="525c8-459">Se l'origine di questa cartella di lavoro è attendibile, fare clic su Sì".</span><span class="sxs-lookup"><span data-stu-id="525c8-459">If you trust the source of this workbook, click Yes".</span></span>


- <span data-ttu-id="525c8-460">È stato risolto un problema per cui se un utente digitava il nome di una formula incluse le parentesi e richiamava la guida tramite F1, l'argomento della guida specifico per quella formula non veniva visualizzato.</span><span class="sxs-lookup"><span data-stu-id="525c8-460">We fixed an issue where if a user typed a formula name including the parenthesis and invoked help via F1, the help topic specific to that formula would not be displayed.</span></span>


- <span data-ttu-id="525c8-461">È stato risolto un problema relativo all'uso di una macro per impostare la proprietà FormulaR1C1 per un intervallo. I riferimenti di cella era corretto se un foglio grafico era il foglio attivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-461">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="525c8-462">È stato risolto un problema che impediva agli utenti di modificare un filtro della tabella pivot perché era configurato su un valore non più presente nel database Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="525c8-462">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="525c8-463">È stato risolto un arresto anomalo correlato ai riferimenti e agli intervalli nominati del componente aggiuntivo XLAM.</span><span class="sxs-lookup"><span data-stu-id="525c8-463">Fixed a crash related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="525c8-464">È stato risolto un problema per cui, quando l'utente applicava uno stile personalizzato a una matrice dinamica, riceveva l'errore: "Non è possibile cambiare una parte di una matrice".</span><span class="sxs-lookup"><span data-stu-id="525c8-464">We fixed an issue where if a user applied a custom style to a dynamic array, they would get the error: "You can't change part of an array".</span></span> <span data-ttu-id="525c8-465">Si tratta di una restrizione ereditata che è stata rimossa.</span><span class="sxs-lookup"><span data-stu-id="525c8-465">This was a legacy restriction that has been removed.</span></span>


- <span data-ttu-id="525c8-466">È stato risolto un problema per cui le macro assegnate ai pulsanti venivano interrotte dopo il ripristino di una versione precedente del file.</span><span class="sxs-lookup"><span data-stu-id="525c8-466">Fixed an issue where macros assigned to buttons were broken after restoring an older version of the file.</span></span>


- <span data-ttu-id="525c8-467">È stato risolto un problema per cui l’input penna poteva far sì che Excel smettesse di rispondere.</span><span class="sxs-lookup"><span data-stu-id="525c8-467">We fixed an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="525c8-468">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-468">Outlook</span></span>

- <span data-ttu-id="525c8-469">È stato risolto un problema che consente maggiore flessibilità per l'abilitazione e la disabilitazione delle opzioni di autenticazione predefinite tramite i Criteri di gruppo.</span><span class="sxs-lookup"><span data-stu-id="525c8-469">We fixed an issue which provides more flexibility in enabling / disabling the default logging options via Group Policy.</span></span>


- <span data-ttu-id="525c8-470">È stato risolto un problema per cui il nome di dominio di un mittente di posta elettronica veniva preservato e mostrato dopo che una bozza del messaggio veniva spostato da una cassetta postale all'altra con le autorizzazioni dell'assistente e del manager.</span><span class="sxs-lookup"><span data-stu-id="525c8-470">We fixed an issue where the Legacy Domain Name for an email sender was preserved and displayed after a draft of the email was moved between mailboxes with assistant permissions and manager permissions.</span></span>


- <span data-ttu-id="525c8-471">Risolve un problema per cui, per alcuni utenti, Outlook si avviava in modalità offline finché l'utente sceglieva di lavorare online.</span><span class="sxs-lookup"><span data-stu-id="525c8-471">Fixes an issue that caused some users to see Outlook to start in an Offline state until they manually chose to work online.</span></span>


- <span data-ttu-id="525c8-472">È stato risolto un problema per cui l'esecuzione del codice VBA ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") dopo l'abilitazione della barra multifunzione su una riga causava un errore di runtime.</span><span class="sxs-lookup"><span data-stu-id="525c8-472">We fixed an issue where running the VBA code ActiveInspector.CommandBars.ExecuteMso("ShowSchedulingPage") after enabling the Single Line Ribbon (SLR) would result in a runtime error.</span></span>


- <span data-ttu-id="525c8-473">È stato risolto un problema per cui i pulsanti OK e Annulla nella finestra di dialogo Risposte automatiche non erano visibili su sistemi ad alta risoluzione (ad esempio 1750 x 1920) quando è selezionata la dimensione grande dei caratteri (come 175%).</span><span class="sxs-lookup"><span data-stu-id="525c8-473">We fixed an issue where the 'OK' and 'Cancel' buttons on the Automatic Replies dialog would not be visible on a system with a high resolution (such as 1750 x 1920) combined with a large text size (such as 175%).</span></span>


- <span data-ttu-id="525c8-474">È stato risolto un problema che causava l'arresto anomalo quando si inviava una convocazione riunione da un gruppo di contatti vuoto a un altro gruppo di contatti.</span><span class="sxs-lookup"><span data-stu-id="525c8-474">We fixed a condition where sending a meeting request from an empty contact group to another contact group would result in a crash.</span></span>


- <span data-ttu-id="525c8-475">Risolve un problema che causava l'arresto anomalo quando venivano aperti alcuni messaggi di posta elettronica molto grandi.</span><span class="sxs-lookup"><span data-stu-id="525c8-475">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="525c8-476">È stato risolto un problema per cui, se Criteri di gruppo richiedeva un componente aggiuntivo per essere sempre abilitato, il monitoraggio dei componenti aggiuntivi non era disponibile per impedire agli utenti di disabilitare il componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-476">We fixed an issue where if Group Policy requires an Add-in to be always enabled, then monitoring add-in's becomes unavailable in order to prevent users from disabling the Add-in.</span></span>


- <span data-ttu-id="525c8-477">Indirizza un problema che consentiva agli utenti di inviare il contenuto della posta elettronica con un criterio "non inoltrato" applicato a OneNote quando si selezionavano più messaggi.</span><span class="sxs-lookup"><span data-stu-id="525c8-477">Addresses an issue that caused users to be able to send email content that had a "Do Not Forward" policy applied to OneNote when selecting more than one message.</span></span>


- <span data-ttu-id="525c8-478">È stato risolto un problema per cui gli utenti ora possono disabilitare IRM (Information Rights Management) per Outlook senza doverlo disabilitare per il resto delle applicazioni di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-478">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="525c8-479">È stato risolto un problema per cui gli attributi dell'account utente in Active Directory per "otherTelephone" e "otherHomePhone" non venivano mappati agli attributi LDAP di Outlook corrispondenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-479">We fixed an issue where the user account attributes in Active Directory for "otherTelephone" and "otherHomePhone" were not mapped to the corresponding Outlook LDAP attributes.</span></span>


- <span data-ttu-id="525c8-480">Questa modifica risolve un problema per cui la pagina Riunione continuava a essere visualizzata dopo che l'utente aveva cambiato scheda dalla pagina Riunione alla pagina Assistente pianificazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-480">This change fixes an issue where the Meeting page would continue to be displayed after the user switched tabs from the Meeting page to the Scheduling Assistant page.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-481">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-481">PowerPoint</span></span>

- <span data-ttu-id="525c8-482">È stato risolto un problema per cui, in determinate condizioni, la barra multifunzione o la barra del titolo non veniva visualizzata.</span><span class="sxs-lookup"><span data-stu-id="525c8-482">We fixed an issue where users were seeing the ribbon/title bar not being displayed under certain conditions.</span></span>


- <span data-ttu-id="525c8-483">È stato risolto un problema per cui, dopo l'avvio di PowerPoint, l'inserimento di una diapositiva e l'apertura e la chiusura del riquadro dei commenti, le diapositive del riquadro anteprima erano mostrate sovrapposte.</span><span class="sxs-lookup"><span data-stu-id="525c8-483">We fixed an issue where after booting PowerPoint, inserting a slide and opening and closing the comments pane, the slides in the thumbnail pane displayed as being overlapped.</span></span>


- <span data-ttu-id="525c8-484">È stato risolto un problema per cui la funzionalità di inserimento di un video era disabilitata.</span><span class="sxs-lookup"><span data-stu-id="525c8-484">We fixed an issue where the functionality to insert a video was disabled.</span></span>


- <span data-ttu-id="525c8-485">È stato risolto un problema che impediva la riproduzione automatica dei video nelle presentazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-485">We fixed an issue where videos were not playing automatically in slideshows.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-486">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-486">Project</span></span>

- <span data-ttu-id="525c8-487">È stato risolto un problema per cui, se una risorsa aveva tabelle tariffarie multiple, i costi rimanenti a volte non venivano calcolati correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-487">We fixed an issue where if a resource has multiple cost rate tables, the remaining cost may not be calculated correctly.</span></span>


- <span data-ttu-id="525c8-488">È stato risolto un problema per cui la data di fine del progetto non viene aggiornata per i progetti collegati all'elenco attività di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-488">We fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


### <a name="visio"></a><span data-ttu-id="525c8-489">Visio</span><span class="sxs-lookup"><span data-stu-id="525c8-489">Visio</span></span>

- <span data-ttu-id="525c8-490">L'anteprima dinamica si arresta in modo anomalo sull'allineamento del testo segnalato dai clienti.</span><span class="sxs-lookup"><span data-stu-id="525c8-490">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="525c8-491">Arresto anomalo di maggior impatto della fork di repository di luglio.</span><span class="sxs-lookup"><span data-stu-id="525c8-491">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-492">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-492">Word</span></span>

- <span data-ttu-id="525c8-493">È stato risolto un problema per cui la scheda commento mostrava un bordo attorno al testo del commento quando l'utente faceva clic su di esso.</span><span class="sxs-lookup"><span data-stu-id="525c8-493">We fixed an issue where the Comment card would display a border around the comment text if the user clicked on the comment.</span></span>


- <span data-ttu-id="525c8-494">È stato risolto un problema per cui l'icona dell’elenco puntato non veniva visualizzata correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-494">We fixed an issue where the bullet picture icon didn't display correctly.</span></span>


- <span data-ttu-id="525c8-495">È stato risolto un problema per cui l'utente non poteva chiudere l'intestazione o il piè di pagina quando veniva selezionato un commento.</span><span class="sxs-lookup"><span data-stu-id="525c8-495">We fixed an issue where the user could not exit the Header/Footer when selecting a comment.</span></span>


- <span data-ttu-id="525c8-496">È stato risolto un problema per cui Word poteva arrestarsi in modo anomalo dopo l'eliminazione dei commenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-496">We fixed an issue where Word could crash after comments were deleted.</span></span>


- <span data-ttu-id="525c8-497">È stato risolto un problema per cui, se un utente creava una bozza di un commento ancorata a una riga contenente commenti approvati, la bozza veniva disposta nell'ordine sbagliato rispetto al commento approvato nel SideTrack.</span><span class="sxs-lookup"><span data-stu-id="525c8-497">We fixed an issue where if a user created a comment draft anchored to a line already containing committed comments, then the draft was arranged in the wrong order relative to the committed comment in the SideTrack.</span></span>


- <span data-ttu-id="525c8-498">È stato risolto un problema per cui la messa a fuoco non passava al riquadro del commento se il documento era ingrandito almeno al 160% e il riquadro del commento non era visibile. </span><span class="sxs-lookup"><span data-stu-id="525c8-498">We fixed an issue where the focus would not go to the comment pane if the document was zoomed to 160% or more and the comment pane was not visible.</span></span>


- <span data-ttu-id="525c8-499">È stato risolto un problema che impediva agli utenti di visualizzare i thread dei commenti che avevano superato il confine del sidetrack, poichè quando si scorreva il sidetrack, questo non funzionava.</span><span class="sxs-lookup"><span data-stu-id="525c8-499">We fixed an issue that prevented users from seeing comment threads that exceeded the sidetrack boundary because scrolling through the sidetrack was not working.</span></span>


- <span data-ttu-id="525c8-500">È stato risolto un problema per cui la ricerca di commenti risolti nel riquadro sidetrack non funzionava.</span><span class="sxs-lookup"><span data-stu-id="525c8-500">We fixed an issue where searching for resolved comments in the sidetrack pane was not working.</span></span>


- <span data-ttu-id="525c8-501">È stato risolto un problema per cui i commenti di un documento venivano visualizzati su altri documenti aperti dopo il passaggio da un documento aperto all'altro.</span><span class="sxs-lookup"><span data-stu-id="525c8-501">We fixed an issue where the comments on one document would be displayed on other open documents after switching between the multiple open documents.</span></span>


- <span data-ttu-id="525c8-502">È stato risolto un problema per cui i collegamenti lunghi non venivano mandati a capo quando un documento veniva salvato in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="525c8-502">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="525c8-503">È stato risolto un problema in cui, in alcuni casi, i punti elenco non vengono visualizzati correttamente nelle e-mail.</span><span class="sxs-lookup"><span data-stu-id="525c8-503">We fixed an issue where in some cases, bullets are not displaying correctly in email.</span></span>


- <span data-ttu-id="525c8-504">È stato risolto un problema per cui la macro AutoOpen veniva eseguita prima di AutoExec.</span><span class="sxs-lookup"><span data-stu-id="525c8-504">We fixed an issue with macros in which AutoOpen runs before AutoExec.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-505">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-505">Office Suite</span></span>

- <span data-ttu-id="525c8-506">È stato risolto un problema dello strumento di distribuzione di Office in cui la era possibile la configurazione quando si usava la funzionalità RemoveMSI con il prodotto Office 2007 "Segnalazione errori applicazioni Microsoft".</span><span class="sxs-lookup"><span data-stu-id="525c8-506">We fixed an issue in the Office Deployment Tool where configuration was failing when using the RemoveMSI feature with the Office 2007 "Microsoft Application Error Reporting" product present.</span></span>


- <span data-ttu-id="525c8-507">È stato risolto un problema nella finestra di dialogo Comprimi immagine in cui alcune impostazioni DPI selezionate dall'utente non venivano mantenute.</span><span class="sxs-lookup"><span data-stu-id="525c8-507">We fixed an issue in the Compress Picture dialog where some user-selected DPI settings are not retained.</span></span>


- <span data-ttu-id="525c8-508">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="525c8-508">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2008-september-04"></a><span data-ttu-id="525c8-510">Versione 2008: 4 settembre</span><span class="sxs-lookup"><span data-stu-id="525c8-510">Version 2008: September 04</span></span>
<span data-ttu-id="525c8-511">*Versione 2008 (Build 13127.20378)*</span><span class="sxs-lookup"><span data-stu-id="525c8-511">*Version 2008 (Build 13127.20378)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-513">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-513">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="525c8-514">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-514">Office Suite</span></span>

- <span data-ttu-id="525c8-515">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="525c8-515">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-02"></a><span data-ttu-id="525c8-517">Versione 2008: 2 settembre</span><span class="sxs-lookup"><span data-stu-id="525c8-517">Version 2008: September 02</span></span>
<span data-ttu-id="525c8-518">*Versione 2008 (Build 13127.20360)*</span><span class="sxs-lookup"><span data-stu-id="525c8-518">*Version 2008 (Build 13127.20360)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-520">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-520">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-521">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-521">Excel</span></span>

- <span data-ttu-id="525c8-522">**Salvataggio delle forme come immagini:** con pochi clic del mouse è possibile salvare una forma, un'icona o un altro oggetto come file di immagine, così da poterlo riutilizzare altrove.</span><span class="sxs-lookup"><span data-stu-id="525c8-522">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="525c8-523">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-523">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="525c8-524">**Effettua rapide modifiche con la penna di Excel:** strumento penna per scrivere e apportare modifiche rapide ai dati</span><span class="sxs-lookup"><span data-stu-id="525c8-524">**Make quick edits using the Excel pen:** Pen Tool to help you handwrite and make quick edits to your data</span></span>



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-527">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-527">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-528">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-528">Excel</span></span>

- <span data-ttu-id="525c8-529">È stato risolto un problema per cui Excel potrebbe arrestarsi in modo anomalo in determinate circostanze quando si usa Copia formato.</span><span class="sxs-lookup"><span data-stu-id="525c8-529">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-530">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-530">Word</span></span>

- <span data-ttu-id="525c8-531">È stato risolto un problema per cui gli stili di base non vengono aggiornati con lo stile normale.</span><span class="sxs-lookup"><span data-stu-id="525c8-531">We fixed an issue which the base styles are not updated with Normal style.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-august-27"></a><span data-ttu-id="525c8-533">Versione 2008: 27 agosto</span><span class="sxs-lookup"><span data-stu-id="525c8-533">Version 2008: August 27</span></span>
<span data-ttu-id="525c8-534">*Versione 2008 (Build 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="525c8-534">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-538">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-538">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-539">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-539">Outlook</span></span>

- <span data-ttu-id="525c8-540">Risolve un problema che faceva sì che gli utenti che tentavano di creare una convocazione di riunione da un account secondario aggiunto al loro profilo non vedessero uno spazio da: campo al posto del loro indirizzo e-mail.</span><span class="sxs-lookup"><span data-stu-id="525c8-540">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="525c8-541">Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.</span><span class="sxs-lookup"><span data-stu-id="525c8-541">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="525c8-542">Risolve un problema che faceva sì che gli utenti sperimentassero occasionalmente degli arresti anomali durante l’interazione con gli allegati cloud.</span><span class="sxs-lookup"><span data-stu-id="525c8-542">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="525c8-543">Questo risolve un problema che causava agli utenti degli arresti anomali occasionali durante la modifica dei destinatari.</span><span class="sxs-lookup"><span data-stu-id="525c8-543">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="525c8-544">Risolve un problema che consente agli utenti di visualizzare anomalie durante l'uso della visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="525c8-544">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-545">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-545">Word</span></span>

- <span data-ttu-id="525c8-546">Questa modifica consente di risolvere un problema in cui le applicazioni di Office possono bloccarsi in uno stato di errore di salvataggio silenzioso dopo una sessione di creazione condivisa precedente.</span><span class="sxs-lookup"><span data-stu-id="525c8-546">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="525c8-547">È stato risolto un problema per cui la macro AutoOpen veniva eseguita prima di AutoExec</span><span class="sxs-lookup"><span data-stu-id="525c8-547">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2008-august-25"></a><span data-ttu-id="525c8-549">Versione 2008: 25 agosto</span><span class="sxs-lookup"><span data-stu-id="525c8-549">Version 2008: August 25</span></span>
<span data-ttu-id="525c8-550">*Versione 2008 (Build 13127.20268)*</span><span class="sxs-lookup"><span data-stu-id="525c8-550">*Version 2008 (Build 13127.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-552">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-552">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-553">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-553">Outlook</span></span>

- <span data-ttu-id="525c8-554">**Ricevere suggerimenti di posta elettronica quando si esegue una ricerca per persona.:** mentre si digitano i termini di ricerca in Outlook verranno resi visibili i messaggi di posta elettronica più rilevanti nei suggerimenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-554">**Receive email suggestions when searching by person.:** As you type your search terms in Outlook you'll receive the most relevant emails surfaced in the suggestions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-557">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-557">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-558">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-558">Outlook</span></span>

- <span data-ttu-id="525c8-559">È stato risolto un problema che causava la ricezione dell'errore seguente quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio, "Alcuni dei file in questa pagina Web non sono nella posizione prevista.</span><span class="sxs-lookup"><span data-stu-id="525c8-559">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="525c8-560">Scaricarli comunque?</span><span class="sxs-lookup"><span data-stu-id="525c8-560">Do you want to download them anyway?</span></span> <span data-ttu-id="525c8-561">Se si è sicuri che la pagina Web sia una fonte attendibile, fare clic su Sì"</span><span class="sxs-lookup"><span data-stu-id="525c8-561">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="525c8-562">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-562">Project</span></span>

- <span data-ttu-id="525c8-563">È stato risolto un problema per cui, se una risorsa aveva più di una tabella tariffe definita, il costo residuo non sempre veniva calcolato correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-563">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-564">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-564">Word</span></span>

- <span data-ttu-id="525c8-565">È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio.</span><span class="sxs-lookup"><span data-stu-id="525c8-565">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2008-august-17"></a><span data-ttu-id="525c8-567">Versione 2008: 17 agosto</span><span class="sxs-lookup"><span data-stu-id="525c8-567">Version 2008: August 17</span></span>
<span data-ttu-id="525c8-568">*Versione 2008 (Build 13127.20208)*</span><span class="sxs-lookup"><span data-stu-id="525c8-568">*Version 2008 (Build 13127.20208)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-570">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-570">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-571">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-571">Outlook</span></span>

- <span data-ttu-id="525c8-572">È stato risolto un problema che causava il mancato retrazione delle riunioni dal calendario di un responsabile in alcuni casi.</span><span class="sxs-lookup"><span data-stu-id="525c8-572">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="525c8-573">È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-573">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="525c8-574">È stato risolto un problema che causava l'arresto anomalo di quattro o più messaggi di posta elettronica da un account POP con l'opzione "solo intestazioni di download" selezionata.</span><span class="sxs-lookup"><span data-stu-id="525c8-574">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="525c8-575">È stato risolto un problema che causava il mancato recapito del menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="525c8-575">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2008-august-11"></a><span data-ttu-id="525c8-577">Versione 2008: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="525c8-577">Version 2008: August 11</span></span>
<span data-ttu-id="525c8-578">*Versione 2008 (Build 13127.20164)*</span><span class="sxs-lookup"><span data-stu-id="525c8-578">*Version 2008 (Build 13127.20164)*</span></span>

<span data-ttu-id="525c8-579">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="525c8-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-581">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-581">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-582">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-582">Access</span></span>

- <span data-ttu-id="525c8-583">Questa correzione risolve il problema per cui il tentativo di eseguire determinate query in precedenza generava il messaggio di errore 'La query è troppo complessa.'</span><span class="sxs-lookup"><span data-stu-id="525c8-583">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="525c8-584">Se è installato Office 365, non è più necessario installare il motore Microsoft ACE Redistributable per esporre ACE all'esterno dell'ecosistema di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-584">If you have Office 365 installed, you no longer need to install our ACE Redistributable Engine to expose ACE outside of the Office ecosystem.</span></span> <span data-ttu-id="525c8-585">Quindi, per gli utenti con Office 365, non sarà più necessario il motore ACE Redist e, di conseguenza, questo problema non dovrebbe verificarsi.</span><span class="sxs-lookup"><span data-stu-id="525c8-585">Therefore, for those with Office 365, you will no longer need the ACE Redist Engine, and consequently you should not experience this issue.</span></span>

- <span data-ttu-id="525c8-586">Questo problema è stato risolto. ora è possibile usare il driver ODBC all'esterno delle applicazioni a portata di clic di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-586">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="525c8-587">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-587">Excel</span></span>

- <span data-ttu-id="525c8-588">È stato risolto un problema per cui, se veniva modificato l'ordine di una serie del grafico, la casella di controllo corrispondente allineata alla serie non era riordinata insieme alla serie.</span><span class="sxs-lookup"><span data-stu-id="525c8-588">We fixed an issue where if the order of a chart series was changed, the corresponding checkbox aligned with the series was not reordered along with the series.</span></span>

- <span data-ttu-id="525c8-589">È possibile che si verifichi un errore quando si prova a salvare un file che contiene una formula usando la funzione LET ().</span><span class="sxs-lookup"><span data-stu-id="525c8-589">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="525c8-590">È stato risolto un problema per cui i grafici non venivano sempre aggiornati come previsto quando era abilitato "ForceFullCalculation" tramite VBA per la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="525c8-590">We fixed an issue where charts were not always updated as expected when "ForceFullCalculation" was enabled via VBA for the workbook.</span></span>

- <span data-ttu-id="525c8-591">È stato risolto un problema per cui una copia di un'immagine con riempimento sfumato non corrispondeva all'originale.</span><span class="sxs-lookup"><span data-stu-id="525c8-591">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

### <a name="onenote"></a><span data-ttu-id="525c8-592">OneNote</span><span class="sxs-lookup"><span data-stu-id="525c8-592">OneNote</span></span>

- <span data-ttu-id="525c8-593">È stato risolto un problema per cui il testo segnaposto nella casella di modifica di ricerca veniva riversato se la finestra dell'applicazione era ridimensionata in una dimensione ridotta.</span><span class="sxs-lookup"><span data-stu-id="525c8-593">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-594">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-594">Outlook</span></span>

- <span data-ttu-id="525c8-595">È stato risolto un problema relativo alla creazione di più profili in Outlook dallo stesso dominio di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="525c8-595">We fixed an issue around creating multiple profiles in Outlookfrom the same email domain.</span></span>

- <span data-ttu-id="525c8-596">È stato risolto un problema che impediva ad alcuni utenti della funzionalità Miglioramenti dei Calendar - Calendario di Outlook condivisi di visualizzare un calendario condiviso appena aggiunto.</span><span class="sxs-lookup"><span data-stu-id="525c8-596">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="525c8-597">Risolto un problema che causava l'errore di visualizzazione dell'icona di blocco nell'intestazione dei messaggi crittografati S/MIME.</span><span class="sxs-lookup"><span data-stu-id="525c8-597">Addressed an issue that caused the lock icon to fail to display in the header of S/MIME encrypted messages.</span></span>

- <span data-ttu-id="525c8-598">È stato risolto un problema per cui mancava l'opzione “Consenti Inoltro” dalle “Opzioni di risposta” del calendario condiviso della riunione se la cartella dei download condivisi non era stata selezionata.</span><span class="sxs-lookup"><span data-stu-id="525c8-598">We fixed an issue where the "Allow Forwarding" option was missing from the shared calendar meeting "Response Options" if Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="525c8-599">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="525c8-599">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="525c8-600">È stato risolto un problema che mostrava il pulsante stampa nello stato disabilitato anche se l'utente aveva le autorizzazioni di stampa appropriate.</span><span class="sxs-lookup"><span data-stu-id="525c8-600">We fixed an issue that would display the print button in a disabled state even though the user had the appropriate print permissions.</span></span>

- <span data-ttu-id="525c8-601">Risolto un problema che causava la rimozione degli allegati dai messaggi S/MIME quando inviati non crittografati.</span><span class="sxs-lookup"><span data-stu-id="525c8-601">Addressed an issue that caused attachments to get stripped from S/MIME messages when sending as unencrypted.</span></span>

- <span data-ttu-id="525c8-602">Risolto un problema che causava il danneggiamento dei messaggi S/MIME di testo normale durante l'invio.</span><span class="sxs-lookup"><span data-stu-id="525c8-602">Addressed an issue that caused plain text S/MIME messages to become garbled when sending.</span></span>

- <span data-ttu-id="525c8-603">Risolto un problema che causava il danneggiamento degli allegati durante l'invio di un messaggio di posta elettronica S/MIME non crittografato.</span><span class="sxs-lookup"><span data-stu-id="525c8-603">Addressed an issue that caused attachments to become corrupted when sending an S/MIME email unencrypted.</span></span>

- <span data-ttu-id="525c8-604">Risolto un problema che impediva ai destinatari di salvare i messaggi protetti, anche quando era stata concessa l'autorizzazione “Salva come” dal mittente.</span><span class="sxs-lookup"><span data-stu-id="525c8-604">Addressed an issue that cause recipients to be unable to save rights protected messages even when the save as permission was granted by the sender.</span></span>

- <span data-ttu-id="525c8-605">Questa correzione risolve un problema che impediva agli utenti di aggiungere una firma rispondendo a un messaggio protetto con Digital rights management da una finestra di controllo, quando l'utente non aveva le autorizzazioni di tipo proprietario per il messaggio a cui stava rispondendo.</span><span class="sxs-lookup"><span data-stu-id="525c8-605">This fix addresses an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user did not have Owner permissions on the message being replied to.</span></span>

- <span data-ttu-id="525c8-606">Questa correzione risolve un problema che impediva a Outlook di mostrare correttamente le interruzioni di riga nel contenuto markdown.</span><span class="sxs-lookup"><span data-stu-id="525c8-606">This fix addresses an issue that was causing Outlook to fail to display line breaks properly in markdown content.</span></span>

- <span data-ttu-id="525c8-607">Risolto un problema che causava il troncamento delle etichette per alcune opzioni di ricerca avanzate in alcune lingue.</span><span class="sxs-lookup"><span data-stu-id="525c8-607">Addressed an issue that caused the labels for some Advanced Search options to be truncated in some languages.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-608">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-608">PowerPoint</span></span>

- <span data-ttu-id="525c8-609">È stato risolto un problema per cui una copia di un'immagine con riempimento sfumato non corrispondeva all'originale.</span><span class="sxs-lookup"><span data-stu-id="525c8-609">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="525c8-610">È stato risolto un problema per cui il pulsante Moduli in PowerPoint non consentiva la creazione di Moduli quando l'accesso all’Office Store non era consentito.</span><span class="sxs-lookup"><span data-stu-id="525c8-610">We fixed an issue where the Forms button in PowerPoint did not allow the creation of Forms when access to Office Store was not permitted.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-611">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-611">Project</span></span>

- <span data-ttu-id="525c8-612">È stato risolto un problema per cui le attività elencate nella visualizzazione della Bacheca delle attività non erano sincronizzate con quelle della finestra di dialogo Assegna risorse.</span><span class="sxs-lookup"><span data-stu-id="525c8-612">We fixed an issue where tasks listed in the Task Board view were not in sync with those in the Assign Resources dialog.</span></span>

- <span data-ttu-id="525c8-613">È stato risolto un problema per cui se si tentava di salvare un PDF/XPS da Project in una raccolta documenti di SharePoint non sarebbe successo nulla.</span><span class="sxs-lookup"><span data-stu-id="525c8-613">We fixed an issue where if you tried to save a PDF/XPS from Project to a SharePoint document library, nothing would happen.</span></span>

- <span data-ttu-id="525c8-614">È stato risolto un problema per cui copiando e incollando un'attività con più dipendenze, non tutte le dipendenze venivano copiate correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-614">We fixed an issue where if you copied & pasted a task that had multiple dependencies, not all dependencies were copied correctly.</span></span>

- <span data-ttu-id="525c8-615">È stato risolto un problema per cui, in relazione a un elenco attività di SharePoint, i pulsanti della barra multifunzione nella seconda scheda potevano essere disabilitati.</span><span class="sxs-lookup"><span data-stu-id="525c8-615">Fixed an issue where for a SharePoint tasks list, the ribbon buttons on the second tab may be disabled.</span></span>

### <a name="skype"></a><span data-ttu-id="525c8-616">Skype</span><span class="sxs-lookup"><span data-stu-id="525c8-616">Skype</span></span>

- <span data-ttu-id="525c8-617">Il tono della pelle dell’emoticon che balla modificato a colorito neutro</span><span class="sxs-lookup"><span data-stu-id="525c8-617">Changed dancing emoticon skin tone to neutral color</span></span>

### <a name="visio"></a><span data-ttu-id="525c8-618">Visio</span><span class="sxs-lookup"><span data-stu-id="525c8-618">Visio</span></span>

- <span data-ttu-id="525c8-619">Dopo questa correzione, se l'utente ha interrotto l'esecuzione del comando Elimina con qualsiasi meccanismo (in questo caso tramite il componente aggiuntivo), la memoria non verrà persa e il computer non sarà coinvolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-619">After this fix, if the user halted the execution of delete command by any mechanism in between (in this case it was through add-in) the memory won't leak and the whole machine won't be impacted.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-620">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-620">Word</span></span>

- <span data-ttu-id="525c8-621">È stato risolto un problema in cui Word smette di rispondere dopo aver incollato del testo e un'immagine in una casella di testo.</span><span class="sxs-lookup"><span data-stu-id="525c8-621">We fixed an issue where Word would stop responding after pasting some text and an image in to a comments box.</span></span>

- <span data-ttu-id="525c8-622">È stato risolto un problema per cui una copia di un'immagine con riempimento sfumato non corrispondeva all'originale.</span><span class="sxs-lookup"><span data-stu-id="525c8-622">We fixed an issue where a copy of an image with a radial gradient fill did not match the original.</span></span>

- <span data-ttu-id="525c8-623">È stato risolto un problema per cui il testo segnaposto nella casella di modifica di ricerca veniva riversato se la finestra dell'applicazione era ridimensionata in una dimensione ridotta.</span><span class="sxs-lookup"><span data-stu-id="525c8-623">We fixed an issue where the placeholder text in the Search edit box would overflow if the application window was resized to a small dimension.</span></span>

- <span data-ttu-id="525c8-624">È stato risolto un problema per cui, se veniva aggiunto un commento per tenere traccia di una modifica, il riquadro delle revisioni si apriva improvvisamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-624">We fixed an issue where if a comment was added to track a change, the revisions pane would unexpectedly open.</span></span>

- <span data-ttu-id="525c8-625">È stato risolto un problema per cui il comando "Editor" veniva disabilitato quando ci si trovava in una casella di testo del commento.</span><span class="sxs-lookup"><span data-stu-id="525c8-625">We fixed an issue where the Editor command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="525c8-626">È stato risolto un problema per cui il comando "Mostra commenti" veniva disabilitato quando ci si trovava in una casella di testo del commento.</span><span class="sxs-lookup"><span data-stu-id="525c8-626">We fixed an issue where the Show Markup command was disabled when the focus was in a comment text box.</span></span>

- <span data-ttu-id="525c8-627">È stato risolto un problema in cui il pulsante "Nuovo commento" viene disabilitato dopo l'eliminazione dell'ultimo commento.</span><span class="sxs-lookup"><span data-stu-id="525c8-627">We fixed an issue where the 'New comment' button would be disabled after deleting the last comment.</span></span>

- <span data-ttu-id="525c8-628">È stato risolto un problema per cui l'opzione "Persone Specifiche" per le Revisioni è stata disabilitata.</span><span class="sxs-lookup"><span data-stu-id="525c8-628">We fixed an issue where the 'Specific People' option for Track Changes was disabled.</span></span>

- <span data-ttu-id="525c8-629">È stato risolto un problema per cui i collegamenti ai documenti non venivano inseriti nella casella commenti tramite il menu a discesa Inserisci -> Collegamento.</span><span class="sxs-lookup"><span data-stu-id="525c8-629">We fixed an issue where links to documents were not being inserted to the comments box via the Insert -> Link dropdown.</span></span>

- <span data-ttu-id="525c8-630">È stato risolto un blocco occasionale durante l'apertura di file HTML.</span><span class="sxs-lookup"><span data-stu-id="525c8-630">We fixed an occasional hang while opening HTML files.</span></span>

- <span data-ttu-id="525c8-631">È stato risolto un problema nel linguaggio XML personalizzato per cui lo stato dei commenti poteva andare perso all'apertura del documento.</span><span class="sxs-lookup"><span data-stu-id="525c8-631">We fixed an issue in custom XML where the state of comments may be lost when opening the document.</span></span>

- <span data-ttu-id="525c8-632">È stato risolto un problema per cui il conteggio dei collegamenti ipertestuali nella raccolta dei collegamenti ipertestuali VBA non eseguiva l’iterazione correttamente dopo l'aggiunta di un'immagine contenente un collegamento ipertestuale.</span><span class="sxs-lookup"><span data-stu-id="525c8-632">We fixed an issue where the hyperlink count in the VBA hyperlinks collection was not iterating correctly after adding an image containing a hyperlink.</span></span>

- <span data-ttu-id="525c8-633">Per il riquadro Condividi basato su servizi non Web precedente, dopo aver chiuso il documento mentre il riquadro Condividi è aperto potrebbe verificarsi un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="525c8-633">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="525c8-634">Questo problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-634">This is now fixed.</span></span>

- <span data-ttu-id="525c8-635">È stato risolto un problema per cui venivano creati altri file dopo che l'utente aveva aperto una nuova finestra dell'app dalla barra delle applicazioni e creato un nuovo documento vuoto.</span><span class="sxs-lookup"><span data-stu-id="525c8-635">We fixed an issue where after the user opened a new app window from the taskbar and created a new blank document, additional files were created.</span></span>

- <span data-ttu-id="525c8-636">È stato risolto un problema per cui non era possibile inviare una notifica all'utente informandolo che il documento doveva essere nuovamente autenticato nel caso in cui un utente avesse modificato un documento senza disporre delle autorizzazioni per farlo.</span><span class="sxs-lookup"><span data-stu-id="525c8-636">We fixed an issue where if a user was editing a document but had lost permissions, we were not notifying the user that they had to re-authenticate.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-august-05"></a><span data-ttu-id="525c8-638">Versione 2007: 05 agosto</span><span class="sxs-lookup"><span data-stu-id="525c8-638">Version 2007: August 05</span></span>
<span data-ttu-id="525c8-639">*Versione 2007 (Build 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="525c8-639">*Version 2007 (Build 13029.20344)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)



[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-643">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-643">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-644">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-644">Outlook</span></span>

- <span data-ttu-id="525c8-645">È stato risolto un problema che causava il mancato recupero di suggerimenti per la ricerca da parte di Outlook.</span><span class="sxs-lookup"><span data-stu-id="525c8-645">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="525c8-646">È stato risolto un problema che causava occasionalmente l’arresto anomalo degli utenti durante il recupero delle informazioni personali.</span><span class="sxs-lookup"><span data-stu-id="525c8-646">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-647">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-647">Project</span></span>

- <span data-ttu-id="525c8-648">È stato risolto un problema che impediva l’apertura di un progetto che aveva ottenuto uno stato non valido.</span><span class="sxs-lookup"><span data-stu-id="525c8-648">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEL BUG)

## <a name="version-2007-july-29"></a><span data-ttu-id="525c8-650">Versione 2007: 29 luglio</span><span class="sxs-lookup"><span data-stu-id="525c8-650">Version 2007: July 29</span></span>
<span data-ttu-id="525c8-651">*Versione 2007 (Build 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="525c8-651">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-653">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-653">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-654">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-654">Excel</span></span>

- <span data-ttu-id="525c8-655">**Accedere ai dati dell'organizzazione da Power BI usando i tipi di dati:** i tipi di dati di Excel di Power BI sono ora distribuiti ai partecipanti al programma Office Insider nelle organizzazioni con Office 365 E5/A5 o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="525c8-655">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="525c8-656">Ottenere le informazioni necessarie e aggiornarle con facilità è fondamentale per molti flussi di lavoro quotidiani.</span><span class="sxs-lookup"><span data-stu-id="525c8-656">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="525c8-657">In Excel è possibile accedere alle informazioni della società o dell'organizzazione da Power BI come tipo di dati, in modo da espandere la tua capacità di inserire informazioni collegate nei fogli di calcolo.</span><span class="sxs-lookup"><span data-stu-id="525c8-657">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="525c8-658">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-658">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="525c8-659">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="525c8-659">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-660">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-660">Outlook</span></span>

- <span data-ttu-id="525c8-661">**Scelta della posizione in cui cercare:** il nuovo elenco a discesa dell'ambito di ricerca consente di modificare più facilmente la ricerca e spostarsi tra cartella corrente e cassetta postale corrente.</span><span class="sxs-lookup"><span data-stu-id="525c8-661">**Pick where to search:** The new search scope drop down allows you to more easily modify your search and switch between Current Folder and Current Mailbox.</span></span> <span data-ttu-id="525c8-662">Grazie a tutti coloro che hanno inviato un feedback sulla nuova esperienza di ricerca in alto.</span><span class="sxs-lookup"><span data-stu-id="525c8-662">Thank you to everyone in Coming Soon who provided feedback on the new Search at Top experience.</span></span> <span data-ttu-id="525c8-663">Questo design e questo aggiornamento sono basati proprio su quel feedback.</span><span class="sxs-lookup"><span data-stu-id="525c8-663">This design and update came out of that feedback!</span></span>

### <a name="word"></a><span data-ttu-id="525c8-664">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-664">Word</span></span>

- <span data-ttu-id="525c8-665">**Collaborazione migliore con i commenti moderni:** ora è possibile aggiungere commenti agli oggetti, @menzionare colleghi e risolvere i thread dei commenti per una migliore esperienza di collaborazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-665">**Better collaboration with modern comments:** Add comments to objects, @mention colleagues, and resolve comment threads for a better collaboration experience.</span></span> [<span data-ttu-id="525c8-666">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-666">Learn more</span></span>](https://support.office.com/article/8d3f868a-867e-4df2-8c68-bf96671641e2)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-669">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-669">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-670">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-670">Outlook</span></span>

- <span data-ttu-id="525c8-671">È stato risolto un problema che causava l'arresto anomalo di CLP cambiando l'indirizzo Da in una risposta da un contesto protetto a uno non protetto.</span><span class="sxs-lookup"><span data-stu-id="525c8-671">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="525c8-672">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-672">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="525c8-673">È stato risolto un problema che causava problemi di formattazione negli avvisi di notifica degli eventi imprevisti.</span><span class="sxs-lookup"><span data-stu-id="525c8-673">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-27"></a><span data-ttu-id="525c8-675">Versione 2007: 27 luglio</span><span class="sxs-lookup"><span data-stu-id="525c8-675">Version 2007: July 27</span></span>
<span data-ttu-id="525c8-676">*Versione 2007 (Build 13029.20292)*</span><span class="sxs-lookup"><span data-stu-id="525c8-676">*Version 2007 (Build 13029.20292)*</span></span>
* <span data-ttu-id="525c8-677">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-677">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-20"></a><span data-ttu-id="525c8-678">Versione 2007: 20 luglio</span><span class="sxs-lookup"><span data-stu-id="525c8-678">Version 2007: July 20</span></span>
<span data-ttu-id="525c8-679">*Versione 2007 (Build 13029.20236)*</span><span class="sxs-lookup"><span data-stu-id="525c8-679">*Version 2007 (Build 13029.20236)*</span></span>
* <span data-ttu-id="525c8-680">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-680">Various bugs and performance fixes.</span></span>

## <a name="version-2007-july-15"></a><span data-ttu-id="525c8-681">Versione 2007: 15 luglio</span><span class="sxs-lookup"><span data-stu-id="525c8-681">Version 2007: July 15</span></span>
<span data-ttu-id="525c8-682">*Versione 2007 (Build 13029.20200)*</span><span class="sxs-lookup"><span data-stu-id="525c8-682">*Version 2007 (Build 13029.20200)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-684">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-684">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-685">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-685">Excel</span></span>

- <span data-ttu-id="525c8-686">**Creare diagrammi di Visio chiari in Excel:** è possibile creare un diagramma di flussi o un organigramma inserendo i dati in un foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="525c8-686">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="525c8-687">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-687">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-690">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-690">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-691">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-691">Access</span></span>

- <span data-ttu-id="525c8-692">È stato risolto un problema per cui Gestione tabelle collegate richiede una chiave primaria se una tabella SQL collegata era aggiornata.</span><span class="sxs-lookup"><span data-stu-id="525c8-692">We fixed an issue where the linked table manager would prompt a primary key if a linked SQL table was refreshed.</span></span>

- <span data-ttu-id="525c8-693">È stato risolto un problema relativo alla visualizzazione di query nell'Editor di query.</span><span class="sxs-lookup"><span data-stu-id="525c8-693">We fixed an issue where queries in the Query Editor scrolled out of view.</span></span>

- <span data-ttu-id="525c8-694">È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.</span><span class="sxs-lookup"><span data-stu-id="525c8-694">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="525c8-695">È stato risolto un problema che impedisce a Microsoft Access di identificare una colonna Identity in una tabella collegata di SQL Server, che poteva causare la segnalazione delle righe in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-695">We fixed an issue that caused Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which could cause rows to be reported as deleted incorrectly.</span></span>

### <a name="excel"></a><span data-ttu-id="525c8-696">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-696">Excel</span></span>

- <span data-ttu-id="525c8-697">È stato risolto un problema per cui gli URL non basati su http o https non venivano visualizzati nell'elenco di file usati di recente.</span><span class="sxs-lookup"><span data-stu-id="525c8-697">We fixed an issue where URLs that were not http or https based were not being displayed in the Most Recently Used list.</span></span>

- <span data-ttu-id="525c8-698">È stato risolto un problema per cui può verificarsi un errore o un blocco caricando una cartella di lavoro con più fogli in visualizzazione Anteprima interruzioni di pagina.</span><span class="sxs-lookup"><span data-stu-id="525c8-698">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="525c8-699">È stato risolto un problema in cui le tabelle del modello di dati create in determinate versioni di Excel non possono essere visualizzate in "anteprima tabelle", anche se non sono state modificate.</span><span class="sxs-lookup"><span data-stu-id="525c8-699">We fixed an issue where data model tables created in certain versions of Excel could not be seen in 'Table Preview' even though the query associated with the table had not been edited.</span></span>

- <span data-ttu-id="525c8-700">I riferimenti "Ignora relativo/assoluto" nella finestra di dialogo Definisci nome \ Applica nomi causano il mancato funzionamento delle formule.</span><span class="sxs-lookup"><span data-stu-id="525c8-700">Ignore Relative/Absolute' references in the Define Name \ Apply Names dialog would cause formulas to not work.</span></span>

- <span data-ttu-id="525c8-701">È stato risolto un problema per il quale la scheda della barra multifunzione di CustomUI per una barra multifunzione era rimossa durante il salvataggio di una cartella di lavoro su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="525c8-701">We fixed an issue where CustomUI XML for a custom ribbon tab was removed when saving a workbook to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="525c8-702">È stato risolto un problema per cui le cartelle di lavoro erano di sola lettura quando per il file era soltanto consigliata sola lettura.</span><span class="sxs-lookup"><span data-stu-id="525c8-702">We fixed an issue where workbooks were read-only when the file only had read-only recommended.</span></span>

- <span data-ttu-id="525c8-703">È stato risolto un problema per cui può verificarsi un errore o un blocco caricando una cartella di lavoro con più fogli in visualizzazione Anteprima interruzioni di pagina.</span><span class="sxs-lookup"><span data-stu-id="525c8-703">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>

- <span data-ttu-id="525c8-704">È stato risolto un problema per cui le linee principali della griglia dei grafici radar non potevano essere formattate correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-704">We fixed an issue where the major gridlines of radar charts could not be formatted correctly.</span></span>


- <span data-ttu-id="525c8-705">È stato risolto un problema per cui la cancellazione di un filtro dati avanzato faceva perdere la formattazione della tabella.</span><span class="sxs-lookup"><span data-stu-id="525c8-705">We fixed an issue where clearing an advanced data filter could lose table formatting.</span></span>


- <span data-ttu-id="525c8-706">È stato risolto un problema in cui il percorso completo di un documento PDF incorporato viene visualizzato nella didascalia del documento, anziché solo nel nome del file.</span><span class="sxs-lookup"><span data-stu-id="525c8-706">We fixed an issue where the full path of an embedded PDF document would show in the document caption rather than just the filename.</span></span>


- <span data-ttu-id="525c8-707">È stato risolto un problema per cui dopo aver disabilitato il connettore Cloud di Wolfram e aver salvato e riaperto una cartella di lavoro di Excel, poteva verificarsi un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="525c8-707">We fixed an issue where after disabling the Wolfram cloud connector and then saving and re-opening an Excel workbook, could result in a crash.</span></span>


- <span data-ttu-id="525c8-708">È stato risolto un problema per cui all'avvio di Excel con il componente aggiuntivo Risolutore poteva comportare un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="525c8-708">We fixed an issue where booting Excel with the Solver add-in enabled would result in a crash.</span></span>


### <a name="outlook"></a><span data-ttu-id="525c8-709">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-709">Outlook</span></span>

- <span data-ttu-id="525c8-710">È stato risolto un problema per cui Outlook si bloccava se erano presenti più di 130 destinatari nella riga "a" e sono state migliorate anche le prestazioni di rendering del testo.</span><span class="sxs-lookup"><span data-stu-id="525c8-710">We fixed an issue where Outlook would hang if there were over 130 recipients on the 'To' line and we also improved the performance of rendering the text.</span></span>


- <span data-ttu-id="525c8-711">È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante immesso dall'IME quando si usavano più monitor con risoluzioni diverse.</span><span class="sxs-lookup"><span data-stu-id="525c8-711">We fixed an issue where the Input Method Editor (IME) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>


- <span data-ttu-id="525c8-712">È stato risolto un problema relativo alla “barra da fare” in cui gli eventi con più di due giorni mostravano la stessa ora di fine per tutti i giorni successivi.</span><span class="sxs-lookup"><span data-stu-id="525c8-712">We fixed an issue in the 'To Do Bar' where events that spanned more than two days, displayed the same end time for all subsequent days.</span></span>


- <span data-ttu-id="525c8-713">È stato risolto un problema a causa del quale gli utenti visualizzavano la data di creazione degli  allegati copiati nel file system tramite il trascinamento fissata all’1 gennaio 4501.</span><span class="sxs-lookup"><span data-stu-id="525c8-713">Addresses an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="525c8-714">È stato risolto un problema per cui gli utenti non riuscivano a usare le azioni "Invia come" e "Invia per conto di" di una lista di distribuzione.</span><span class="sxs-lookup"><span data-stu-id="525c8-714">We fixed an issue where users were unable to 'Send As' or 'Send on behalf' of a distribution list.</span></span>


- <span data-ttu-id="525c8-715">È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un responsabile.</span><span class="sxs-lookup"><span data-stu-id="525c8-715">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="525c8-716">È stato risolto un problema per cui gli utenti visualizzavano l'errore seguente alla chiusura di un appuntamento salvato in precedenza: "Impossibile salvare l'elemento. L'elemento è stato modificato da un altro utente o in un'altra finestra.</span><span class="sxs-lookup"><span data-stu-id="525c8-716">We fixed an issue that caused users to see the following error when closing an appointment that was previously saved "The item cannot be saved because it was changed by another user or in another window.</span></span> <span data-ttu-id="525c8-717">Creare una copia dell'elemento nella cartella predefinita?"</span><span class="sxs-lookup"><span data-stu-id="525c8-717">Do you want to make a copy in the default folder for the item?"</span></span>


- <span data-ttu-id="525c8-718">È stato risolto un problema per cui l'opzione Consenti inoltro non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="525c8-718">Addresses an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="525c8-719">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive dall'esterno del tenant al computer locale selezionando l'opzione "Salva" nella finestra di dialogo relativa alla sicurezza.</span><span class="sxs-lookup"><span data-stu-id="525c8-719">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="525c8-720">È stato risolto un problema che causava l'interruzione dell'aggiornamento dell'elenco dei messaggi degli utenti di Outlook per alcuni minuti dopo aver usato calendari condivisi.</span><span class="sxs-lookup"><span data-stu-id="525c8-720">We fixed an issue that caused users of Outlook to see their message list stop updating for several minutes after using shared calendars.</span></span>


- <span data-ttu-id="525c8-721">È stato risolto un problema che impediva la visualizzazione degli orari esatti nei promemoria del calendario per le riunioni da tenersi in meno di una settimana.</span><span class="sxs-lookup"><span data-stu-id="525c8-721">We fixed an issue that prevented calendar reminders from showing exact times for meetings coming up in less than a week.</span></span> 


- <span data-ttu-id="525c8-722">È stato risolto un problema per cui l'inserimento di un'immagine in linea in un messaggio, e il successivo salvataggio del messaggio come bozza, comportava un ridimensionamento dell'immagine.</span><span class="sxs-lookup"><span data-stu-id="525c8-722">We fixed an issue where inserting an image inline in a message, then saving the message as a draft would result in a resizing of the image.</span></span>


- <span data-ttu-id="525c8-723">È stato risolto un problema che causava il cambiamento del corpo di un messaggio NDR da Unicode a ASCII dopo aver modificato l'oggetto.</span><span class="sxs-lookup"><span data-stu-id="525c8-723">We fixed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>


- <span data-ttu-id="525c8-724">È stato risolto un problema per cui le date nel mini calendario non venivano visualizzate in grassetto per gli utenti in Giappone.</span><span class="sxs-lookup"><span data-stu-id="525c8-724">We fixed an issue where dates in the mini calendar failed to display in bold for users in Japan.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-725">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-725">PowerPoint</span></span>

- <span data-ttu-id="525c8-726">È stato risolto un problema per cui l'indicatore di colore di presenza di un utente non si aggiornava nella raccolta condivisa durante una sessione di creazione condivisa in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="525c8-726">We fixed an issue where a user's presence color indicator was not getting refreshed in the co-authoring gallery during a live co-authoring session.</span></span>


- <span data-ttu-id="525c8-727">È stato risolto un problema per cui quando si incollava l’HTML in un'area di testo su una diapositiva questo veniva invece incollato in una casella di testo creata nella parte superiore della diapositiva.</span><span class="sxs-lookup"><span data-stu-id="525c8-727">We fixed an issue where pasting HTML to a text area on a slide would instead get pasted into a text box created at the top of the slide.</span></span>


- <span data-ttu-id="525c8-728">È stato risolto un problema per cui selezionare tutte le diapositive nella visualizzazione relatore, uscire dalla visualizzazione relatore con ALT + TAB e tornare alla presentazione e fare clic su "fine presentazione" comportava un'eccezione non gestita.</span><span class="sxs-lookup"><span data-stu-id="525c8-728">We fixed an issue where selecting all slides in Presenter View, then exiting Presenter View using Alt+Tab and returning to the slide show and clicking 'End Show' would result in an unhandled exception.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-729">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-729">Project</span></span>

- <span data-ttu-id="525c8-730">È stato risolto un problema per cui non era possibile salvare un file PDF/XPS da Project a una raccolta documenti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-730">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="525c8-731">È stato risolto un problema per cui non era possibile aprire progetti nel client desktop di Project da Project Web App se l'URL terminava in ". com".</span><span class="sxs-lookup"><span data-stu-id="525c8-731">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="525c8-732">È stato risolto un problema per cui Project potrebbe arrestarsi in modo anomalo all'apertura di alcuni file XML.</span><span class="sxs-lookup"><span data-stu-id="525c8-732">We fixed an issue where Project may crash when opening certain XML files.</span></span>


- <span data-ttu-id="525c8-733">È stato risolto un problema per cui non era possibile aprire progetti nel client Project Desktop da Project Web App se l'URL terminava in ". com".</span><span class="sxs-lookup"><span data-stu-id="525c8-733">We fixed an issue where projects couldn't be opened in the Project desktop client from the Project Web App if the URL ended in '.com'.</span></span>


- <span data-ttu-id="525c8-734">È stato risolto un problema per cui, incollando un'attività con più dipendenze, non tutte le dipendenze vengono copiate correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-734">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="525c8-735">È stato risolto un problema per cui l'attività selezionata nella finestra di dialogo Assegna risorse non è la stessa selezionata nella visualizzazione Bacheca attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-735">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="525c8-736">È stato risolto un problema per cui non era possibile eseguire l'evento ProjectBeforeTaskChange quando era apportata una modifica all'attività di riepilogo del progetto, sia inizio progetto che campo delle attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-736">We fixed an issue where the ProjectBeforeTaskChange event didn't fire when there was a change to the project summary task, either the project start/task field.</span></span>


- <span data-ttu-id="525c8-737">È stato risolto un problema per cui, se le attività a durata fissa sono al 100% complete ma il completamento effettivo non è specificato, l'attività % di completamento era visualizzata come inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="525c8-737">We fixed an issue where if Fixed Duration tasks are at 100% complete but the Actual Finish is not specified, the Task % Complete would display as less than 100%.</span></span>

- <span data-ttu-id="525c8-738">È stato risolto un problema per cui una reimpostazione o aggiornamento di una linea di base poteva cambiare il costo del budget o le risorse lavoro a scala cronologica e la linea di base rifletteva valori di budget non corretti.</span><span class="sxs-lookup"><span data-stu-id="525c8-738">We fixed an issue where a baseline reset or update could change time-phased budget cost/work resources and the baseline could reflect incorrect budget values.</span></span>


- <span data-ttu-id="525c8-739">È stato risolto un problema per cui i collegamenti di Project Planner negli ambienti Government Community Cloud erano stati disabilitati.</span><span class="sxs-lookup"><span data-stu-id="525c8-739">We fixed an issue where Project Planner links in Government Community Cloud environments had been disabled.</span></span>


- <span data-ttu-id="525c8-740">È stato risolto un problema per cui non era possibile aprire un file di Project da una raccolta documenti di SharePoint se la raccolta era in modalità moderna.</span><span class="sxs-lookup"><span data-stu-id="525c8-740">We fixed an issue where you couldn't open a Project file from a SharePoint document library if the library was in modern mode.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-741">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-741">Word</span></span>

- <span data-ttu-id="525c8-742">È stato risolto un problema per cui la possibilità di cancellare la formattazione nel riquadro commenti con il pulsante Cancella formattazione sulla barra multifunzione di Office non funzionava.</span><span class="sxs-lookup"><span data-stu-id="525c8-742">We fixed an issue where the ability to clear formatting within the Comments pane via the Clear Formatting button in the Office Ribbon was not working.</span></span>


- <span data-ttu-id="525c8-743">È stato risolto un problema per cui il testo inserito in un file SVG (Scalable Vector Graphics) era illeggibile dopo averlo inserito in un file di Word, Excel o PowerPoint, salvando e chiudendo il file e successivamente riaprendo il file.</span><span class="sxs-lookup"><span data-stu-id="525c8-743">We fixed an issue where text inserted in a Scalable Vector Graphic (SVG) was illegible after inserting it in a Word, Excel, or PowerPoint file, saving and closing the file, and then re-opening the file.</span></span>


- <span data-ttu-id="525c8-744">È stato risolto un problema per cui si modificavano le dimensioni di una tabella quando il righello non veniva visualizzato e le altre applicazioni eseguite in background iniziavano a lampeggiare.</span><span class="sxs-lookup"><span data-stu-id="525c8-744">We fixed an issue where changing the size of a table when the ruler is not displayed caused other applications running in the background to start flashing.</span></span>


- <span data-ttu-id="525c8-745">È stato risolto un problema per cui, in modalità di creazione condivisa, le risposte ai commenti non venivano talvolta visualizzate nel riquadro commenti ma erano visibili nel riquadro revisioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-745">We fixed an issue where in co-authoring mode, comment replies would sometimes not show up in the comments pane but would be visible in the revisions pane.</span></span>


- <span data-ttu-id="525c8-746">È stato risolto un problema durante la modalità di creazione condivisa quando si verifica un conflitto di Unione e l'utente ha già scelto di ignorare le modifiche, ma non veniva più visualizzata l'opzione per salvare o annullare le modifiche.</span><span class="sxs-lookup"><span data-stu-id="525c8-746">We fixed an issue during co-authoring mode when there is a merge conflict and the user has already chosen to discard changes, we no longer display the option to save or discard changes.</span></span>


- <span data-ttu-id="525c8-747">È stato risolto un problema per cui il rendering del colore dei collegamenti ipertestuali HTML non veniva eseguito correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-747">We fixed an issue where the HTML hyperlink color was not being rendered correctly.</span></span>


- <span data-ttu-id="525c8-748">È stato risolto un problema per cui, se Word includeva un elenco di più di 50 documenti aperti di frequente, dopo il salvataggio e l'apertura di un documento veniva visualizzata la cronologia delle revisioni, anche se non erano state apportate revisioni al documento.</span><span class="sxs-lookup"><span data-stu-id="525c8-748">We fixed an issue where if Word had a list of more than 50 frequently opened documents, then after saving and opening a document, a revision history would be displayed even though no revisions were made to that document.</span></span>


- <span data-ttu-id="525c8-749">È stato risolto un problema relativo al salvataggio automatico durante la creazione condivisa.</span><span class="sxs-lookup"><span data-stu-id="525c8-749">We fixed in issue with autosave during coauthoring.</span></span>


- <span data-ttu-id="525c8-750">È stato risolto un problema per cui, quando si provava a salvare un file contenente una macro con un nuovo nome, il file veniva salvato con estensione .docx e il nome file “WRO0004.docx”, indipendentemente dall'immissione dell'utente, rendeva il documento inutilizzabile.</span><span class="sxs-lookup"><span data-stu-id="525c8-750">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with a .docx extension and the filename 'WRO0004.docx', regardless of what the user entered, rendering the document unusable.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-751">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-751">Office Suite</span></span>

- <span data-ttu-id="525c8-752">Un problema di tempi poteva causare un arresto anomalo durante la chiusura dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="525c8-752">A timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="525c8-753">Il problema è stato corretto verificando che il servizio calcolasse correttamente i prodotti aggiunti.</span><span class="sxs-lookup"><span data-stu-id="525c8-753">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="525c8-754">I nuovi prodotti aggiunti sono stati filtrati (verificando che esistano anche nella nuova configurazione) e aggiunti alla fine degli ID di rilascio prodotti esistenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-754">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-09"></a><span data-ttu-id="525c8-756">Versione 2006: 9 luglio</span><span class="sxs-lookup"><span data-stu-id="525c8-756">Version 2006: July 09</span></span>
<span data-ttu-id="525c8-757">*Versione 2006 (Build 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="525c8-757">*Version 2006 (Build 13001.20384)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-759">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-759">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-760">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-760">Excel</span></span>

- <span data-ttu-id="525c8-761">**Creare una connessione PDF:** connettersi a, importare, aggiornare i dati da un file PDF.</span><span class="sxs-lookup"><span data-stu-id="525c8-761">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="525c8-762">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-762">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="525c8-763">**Creare variabili da usare nelle formule:** migliorare le prestazioni, la leggibilità e la compatibilità con la funzione LET.</span><span class="sxs-lookup"><span data-stu-id="525c8-763">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="525c8-764">Questa funzione consente di creare variabili denominate nelle formule nuove o preesistenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-764">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="525c8-765">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-765">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="525c8-766">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="525c8-766">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

- <span data-ttu-id="525c8-767">**Scelte rapide da tastiera in Excel:** scelte rapide da tastiera aggiornate per Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-767">**Keyboard shortcuts in Excel:** Updated keyboard shortcuts for Excel</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-768">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-768">Outlook</span></span>

- <span data-ttu-id="525c8-769">**Creare sondaggi in Outlook con Sondaggio rapido:** Creare facilmente un sondaggio, raccogliere voti e visualizzare i risultati in un email [Altre informazioni](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="525c8-769">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="525c8-770">**Mantenere la qualità elevata delle immagini quando inserite in un messaggio di posta elettronica:** è disponibile una nuova opzione di Outlook per limitare la compressione quando si inviano immagini come parte del contenuto del messaggio di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="525c8-770">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-773">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-773">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-774">Accesso</span><span class="sxs-lookup"><span data-stu-id="525c8-774">Access</span></span>

- <span data-ttu-id="525c8-775">Questo problema è stato risolto e dovrebbe essere possibile inserire correttamente tabelle SQL collegate che includano un campo identità, ad esempio numerazione automatica, in Access.</span><span class="sxs-lookup"><span data-stu-id="525c8-775">This issue is resolved, and you should expect to be able to successfully insert linked SQL tables that include an identity (e.g. autonumber) field into Access.</span></span>

### <a name="excel"></a><span data-ttu-id="525c8-776">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-776">Excel</span></span>

- <span data-ttu-id="525c8-777">È stato risolto un arresto anomalo che può verificarsi quando si cerca di creare una connessione dati, se l’utente è uscito dal proprio account.</span><span class="sxs-lookup"><span data-stu-id="525c8-777">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-778">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-778">Outlook</span></span>

- <span data-ttu-id="525c8-779">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="525c8-779">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="525c8-780">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="525c8-780">Office Suite</span></span>

- <span data-ttu-id="525c8-781">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="525c8-781">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="525c8-782">l'host di Office si arresta in modo anomalo in Windows, quando viene attivato un componente aggiuntivo mentre il valore del registro di sistema TabProcGrowth è di tipo REG_SZ e con valore "0".</span><span class="sxs-lookup"><span data-stu-id="525c8-782">he office host was crashing in windows, when an add-in is being activated while the registry TabProcGrowth value is REG_SZ type and with value "0".</span></span>  <span data-ttu-id="525c8-783">Il valore del registro di sistema TabProcGrowth può seguire uno dei quattro percorsi seguenti: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main Questa modifica può risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="525c8-783">That registry TabProcGrowth value can be under any one of 4 paths: HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main HKEY_CURRENT_USER\Software\Policies\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINE\Software\Microsoft\Internet Explorer\Main HKEY_LOCAL_MACHINER\Software\Policies\Microsoft\Internet Explorer\Main This change would fix this issue.</span></span>


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2006-june-25"></a><span data-ttu-id="525c8-785">Versione 2006: 25 giugno</span><span class="sxs-lookup"><span data-stu-id="525c8-785">Version 2006: June 25</span></span>
<span data-ttu-id="525c8-786">*Versione 2006 (Build 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="525c8-786">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-788">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-788">Feature updates</span></span>
### <a name="visio"></a><span data-ttu-id="525c8-789">Visio</span><span class="sxs-lookup"><span data-stu-id="525c8-789">Visio</span></span>

- <span data-ttu-id="525c8-790">**Creare impeccabili diagrammi di Visio in Excel:** è possibile creare un diagramma di flussi o un organigramma sulla base di dati inseriti in un foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="525c8-790">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart based on data in a worksheet.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-793">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-793">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-794">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-794">Access</span></span>

- <span data-ttu-id="525c8-795">Questo problema è ora risolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-795">This problem is now resolved.</span></span> <span data-ttu-id="525c8-796">Comunicare al team se si verificano altri problemi durante il processo.</span><span class="sxs-lookup"><span data-stu-id="525c8-796">Please let the team know if you experience more issues with this process.</span></span>


### <a name="outlook"></a><span data-ttu-id="525c8-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-797">Outlook</span></span>

- <span data-ttu-id="525c8-798"><span style="display:inline !important;">Risolve un problema a causa del quale gli utenti visualizzavano <span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">la data di creazione di&nbsp; allegati copiati nel file system tramite il trascinamento &nbsp;fissata all’1 gennaio 4501.</span></span><span class="sxs-lookup"><span data-stu-id="525c8-798"><span style="display:inline !important;">Addresses an issue that caused users to see<span>&nbsp;</span></span><span style="box-sizing:border-box;font-family:Calibri, sans-serif;font-size:14.6667px;display:inline !important;">the creation date of&nbsp; attachments that they copied to their file system via drag and drop getting&nbsp; set to January 1, 4501.</span></span></span><br>


- <span data-ttu-id="525c8-799"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Risolve un problema a causa del quale gli utenti dei miglioramenti del Calendario condiviso visualizzavano errori di calendario.</span></span><span class="sxs-lookup"><span data-stu-id="525c8-799"><span style="font-family:&quot;Segoe UI&quot;, system-ui, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, sans-serif;display:inline !important;">Addresses an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span></span><br>


- <span data-ttu-id="525c8-800"><span style="display:inline !important;">Risolve un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.</span></span><span class="sxs-lookup"><span data-stu-id="525c8-800"><span style="display:inline !important;">Addresses an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span></span><br>


- <span data-ttu-id="525c8-801"><span style="display:inline !important;">Risolve un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.</span></span><span class="sxs-lookup"><span data-stu-id="525c8-801"><span style="display:inline !important;">Addresses an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span></span><br>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2006-june-18"></a><span data-ttu-id="525c8-803">Versione 2006: 18 giugno</span><span class="sxs-lookup"><span data-stu-id="525c8-803">Version 2006: June 18</span></span>
<span data-ttu-id="525c8-804">*Versione 2006 (Build 13001.20198)*</span><span class="sxs-lookup"><span data-stu-id="525c8-804">*Version 2006 (Build 13001.20198)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-806">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-806">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-807">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-807">Excel</span></span>



- <span data-ttu-id="525c8-808">**Salva in Cartelle aggiunte:** le Cartelle aggiunte semplificano il salvataggio dei file di Office Abbiamo ricevuto feedback secondo cui gli utenti vogliono maggior controllo sulle cartelle disponibili al momento del salvataggio di un nuovo file.</span><span class="sxs-lookup"><span data-stu-id="525c8-808">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="525c8-809">Siamo felici di offrire una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva.</span><span class="sxs-lookup"><span data-stu-id="525c8-809">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="525c8-810">Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-810">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="525c8-811">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="525c8-811">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-812">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-812">PowerPoint</span></span>

- <span data-ttu-id="525c8-813">**Salva in Cartelle aggiunte:** le Cartelle aggiunte semplificano il salvataggio dei file di Office Abbiamo ricevuto feedback secondo cui gli utenti vogliono maggior controllo sulle cartelle disponibili al momento del salvataggio di un nuovo file.</span><span class="sxs-lookup"><span data-stu-id="525c8-813">**Save to Pinned Folders:** Pin your folders makes saving Office files easier We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="525c8-814">Siamo felici di offrire una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva.</span><span class="sxs-lookup"><span data-stu-id="525c8-814">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="525c8-815">Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-815">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span><br /><span data-ttu-id="525c8-816">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="525c8-816">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="word"></a><span data-ttu-id="525c8-817">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-817">Word</span></span>

- <span data-ttu-id="525c8-818">**Salva in Cartelle aggiunte:** le Cartelle aggiunte semplificano il salvataggio dei file di OfficeAbbiamo ricevuto feedback secondo cui gli utenti vogliono maggior controllo sulle cartelle disponibili al momento del salvataggio di un nuovo file.</span><span class="sxs-lookup"><span data-stu-id="525c8-818">**Save to Pinned Folders:** Pin your folders makes saving Office files easierWe received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="525c8-819">Siamo felici di offrire una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva.</span><span class="sxs-lookup"><span data-stu-id="525c8-819">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="525c8-820">Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-820">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> <br /><span data-ttu-id="525c8-821">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="525c8-821">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-824">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-824">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-825">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-825">Excel</span></span>

- <span data-ttu-id="525c8-826">È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="525c8-826">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-827">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-827">Outlook</span></span>

- <span data-ttu-id="525c8-828">È stato risolto un problema a causa del quale CTRL+clic smetteva di funzionare quando le impostazioni del cloud erano abilitate.</span><span class="sxs-lookup"><span data-stu-id="525c8-828">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-829">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-829">Project</span></span>

- <span data-ttu-id="525c8-830">È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="525c8-830">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2006-june-11"></a><span data-ttu-id="525c8-832">Versione 2006: 11 giugno</span><span class="sxs-lookup"><span data-stu-id="525c8-832">Version 2006: June 11</span></span>
<span data-ttu-id="525c8-833">*Versione 2006 (Build 13001.20144)*</span><span class="sxs-lookup"><span data-stu-id="525c8-833">*Version 2006 (Build 13001.20144)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-835">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-835">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="525c8-836">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-836">PowerPoint</span></span>

- <span data-ttu-id="525c8-837">**Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida.</span><span class="sxs-lookup"><span data-stu-id="525c8-837">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="525c8-838">I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.</span><span class="sxs-lookup"><span data-stu-id="525c8-838">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-839">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-839">Word</span></span>

- <span data-ttu-id="525c8-840">**Mantenere il testo nei vettori:** ora è possibile mantenere il testo nelle mappe, nei grafici e in altri vettori SVG al momento della conversione di questi oggetti in Excel, Word e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-840">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-843">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-843">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-844">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-844">Excel</span></span>

- <span data-ttu-id="525c8-845">È stato risolto un problema che causava l’arresto occasionale di Excel durante l'attivazione di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="525c8-845">We fixed an issue where Excel would occasionally shut down when engaging OneDrive.</span></span>

- <span data-ttu-id="525c8-846">È stato risolto un problema per cui i valori personalizzati sull'asse del grafico non venivano applicati correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-846">We fixed an issue where custom values on the chart axis would not get applied correctly.</span></span>

- <span data-ttu-id="525c8-847">È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.</span><span class="sxs-lookup"><span data-stu-id="525c8-847">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="525c8-848">È stato risolto un problema che causava la duplicazione dei nomi delle stampanti nell'elenco delle stampanti disponibili.</span><span class="sxs-lookup"><span data-stu-id="525c8-848">We fixed an issue that caused printer names to be duplicated in the list of available printers.</span></span>

- <span data-ttu-id="525c8-849">È stato risolto un problema che generava un miglioramento delle prestazioni quando gli utenti eliminavano le colonne unite insieme.</span><span class="sxs-lookup"><span data-stu-id="525c8-849">We fixed an issue that resulted in improved performance time for users when they deleted merged columns.</span></span>

- <span data-ttu-id="525c8-850">È stato risolto un problema per cui compariva il messaggio di errore "La cartella di lavoro è attualmente consultata da un altro utente e non può essere chiusa", perché i componenti aggiuntivi erano caricati in ordine alfabetico invece che secondo un ordine specificato dall'utente.</span><span class="sxs-lookup"><span data-stu-id="525c8-850">We fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="525c8-851">È stato risolto un problema di danneggiamento della memoria connesso con la gestione dei caratteri tra Excel e alcune applicazioni di assistive technology di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-851">We fixed an issue where memory was being corrupted when managing fonts between Excel and some third party assistive technology applications.</span></span>

- <span data-ttu-id="525c8-852">È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="525c8-852">We fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="525c8-853">È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappata invece che indirizzi universali.</span><span class="sxs-lookup"><span data-stu-id="525c8-853">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="525c8-854">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti per lo scorrimento CTRL+MAIUSC+Freccia, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="525c8-854">We fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window was shared through Teams.</span></span>

- <span data-ttu-id="525c8-855">È stato risolto un problema che causava l’arresto anomalo di Excel quando i componenti aggiuntivi richiedevano elementi host su un foglio di lavoro contenente forme con blocchi Nessuna selezione.</span><span class="sxs-lookup"><span data-stu-id="525c8-855">We fixed an issue where Excel would crash when Add-ins ask for Host Items on worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="525c8-856">È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo nel tentativo di inserire tabelle pivot in un foglio grafico.</span><span class="sxs-lookup"><span data-stu-id="525c8-856">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-857">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-857">Outlook</span></span>

- <span data-ttu-id="525c8-858">È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante inserito attraverso l’IME, quando venivano usati più monitor con risoluzioni diverse.</span><span class="sxs-lookup"><span data-stu-id="525c8-858">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="525c8-859">È stato risolto un problema per cui la visualizzazione di un modello durante la composizione di un nuovo messaggio di posta elettronica provocava un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="525c8-859">We fixed an issue where viewing a template when composing a new email message would result in a crash.</span></span>

- <span data-ttu-id="525c8-860">È stato risolto un problema per cui gli utenti non riuscivano a usare le cartelle pubbliche di Exchange 2010 dopo la versione 1911 di Outlook.</span><span class="sxs-lookup"><span data-stu-id="525c8-860">We fixed an issue where users were unable to Exchange 2010 public folders after Outlook version 1911.</span></span>

- <span data-ttu-id="525c8-861">È stato risolto un problema per cui il pulsante Categorizza per i calendari di gruppo sulla barra multifunzione di Office era disabilitato.</span><span class="sxs-lookup"><span data-stu-id="525c8-861">We fixed an issue where the Categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="525c8-862">È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="525c8-862">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="525c8-863">È stato risolto un problema che causava l'arresto anomalo di Outlook per alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="525c8-863">Addressed an issue that caused Outlook to crash on some Windows builds.</span></span>

- <span data-ttu-id="525c8-864">È stato risolto un problema che impediva agli utenti di condividere un calendario con un utente guest.</span><span class="sxs-lookup"><span data-stu-id="525c8-864">We fixed an issue where users were unable to share a calendar with a guest user.</span></span>

- <span data-ttu-id="525c8-865">È stato risolto un problema per cui gli utenti vedevano elementi del calendario che duravano oltre la mezzanotte come Eventi a giornata intera.</span><span class="sxs-lookup"><span data-stu-id="525c8-865">We fixed an issue where users saw calendar items that spanned the midnight threshold as All day events.</span></span>

- <span data-ttu-id="525c8-866">È stato risolto un problema a causa del quale nell’archivio online scompariva l'elenco a discesa nelle proprietà della cartella per gli utenti che usavano monitor con valori DPI elevati.</span><span class="sxs-lookup"><span data-stu-id="525c8-866">We fixed an issue that resulted in the Online Archive dropdown in folder properties to be missing for users on high DPI monitors.</span></span>

- <span data-ttu-id="525c8-867">È stato risolto un problema a causa del quale l’evento Folder.BeforeItemMove non si attivava correttamente quando un utente spostava elementi tra le cartelle.</span><span class="sxs-lookup"><span data-stu-id="525c8-867">We fixed an issue where the Folder.BeforeItemMove event didn't fire correctly when a user moved items between folders.</span></span>

- <span data-ttu-id="525c8-868">È stato risolto un problema relativo all'arresto anomalo di Outlook quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo sulla barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="525c8-868">We fixed an issue where Outlook crashed when two add-ins added a button to the same group in the ribbon.</span></span>

- <span data-ttu-id="525c8-869">È stato risolto un problema che causava l’arresto anomalo di Outlook quando l’utente inseriva collegamenti ipertestuali nei messaggi di posta elettronica con testo normale.</span><span class="sxs-lookup"><span data-stu-id="525c8-869">We fixed an issue that caused users to experience a crash in Outlook when working with hyperlinks in Plain Text emails.</span></span>

- <span data-ttu-id="525c8-870">È stato risolto un problema per cui Outlook non riusciva ad analizzare i nomi di file lunghi codificati con RFC2231.</span><span class="sxs-lookup"><span data-stu-id="525c8-870">We fixed an issue that caused Outlook to be unable to parse long file names encoded with RFC2231.</span></span>

- <span data-ttu-id="525c8-871">È stato risolto un problema che provocava blocchi intermittenti di Outlook dovuti alle utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="525c8-871">We fixed an issue that was causing Outlook users to experience intermittent hangs when using screen readers.</span></span>

- <span data-ttu-id="525c8-872">È stato risolto un problema che causava l'arresto anomalo degli utenti con contatti in conflitto in Outlook.</span><span class="sxs-lookup"><span data-stu-id="525c8-872">We fixed an issue that would cause users with conflicting contacts to experience crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-873">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-873">PowerPoint</span></span>

- <span data-ttu-id="525c8-874">È stato risolto un problema con l'apertura di file configurati dal server con l'autenticazione basata su moduli.</span><span class="sxs-lookup"><span data-stu-id="525c8-874">We fixed an issue with opening server-configured files with forms-based authentication.</span></span>

- <span data-ttu-id="525c8-875">È stato risolto un problema per cui i file di PowerPoint con grafici o cartelle di lavoro incorporati potevano causare errori durante il salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="525c8-875">We fixed an issue where PowerPoint files with embedded charts / workbooks could result in failures when saving the file.</span></span>

- <span data-ttu-id="525c8-876">È stato risolto un problema per cui lo zoom avanti e indietro dall’area della presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-876">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="525c8-877">È stato risolto un problema per cui le diapositive non erano centrate dopo l’ingrandimento con la rotellina del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-877">We fixed an issue where slides were not centered after zooming using the mouse wheel.</span></span>

- <span data-ttu-id="525c8-878">È stato risolto un problema per cui le scelte rapide da tastiera e il controllo ortografico non funzionavano come previsto con l’uso di una tastiera inglese svizzera (QWERTZ).</span><span class="sxs-lookup"><span data-stu-id="525c8-878">We fixed an issue where keyboard shortcuts and spell check wouldn’t function as expected when using an English Switzerland (QWERTZ) keyboard.</span></span>

- <span data-ttu-id="525c8-879">È stato risolto un problema per cui un riquadro commenti chiuso dall'utente veniva riaperto automaticamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-879">We fixed an issue where a Comment pane that had been closed by the user would re-open automatically.</span></span>

- <span data-ttu-id="525c8-880">È stato risolto un problema per cui l'editor diapositive si sovrapponeva da una diapositiva a quella successiva.</span><span class="sxs-lookup"><span data-stu-id="525c8-880">We fixed an issue where the slide editor from one slide would overlap on to the next slide.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-881">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-881">Project</span></span>

- <span data-ttu-id="525c8-882">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-882">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="525c8-883">È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="525c8-883">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="525c8-884">È stato risolto un problema per cui Project si arrestava in modo anomalo dopo aver fatto clic su Opzioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-884">We fixed an issue where Project would crash after clicking on Options.</span></span>

- <span data-ttu-id="525c8-885">Abbiamo risolto un problema che impediva l'eliminazione o la riassegnazione di attività isolate dopo l'eliminazione del piano padre.</span><span class="sxs-lookup"><span data-stu-id="525c8-885">We fixed an issue that prevented orphaned tasks from being deleted or re-assigned after their parent plan was deleted.</span></span>

### <a name="visio"></a><span data-ttu-id="525c8-886">Visio</span><span class="sxs-lookup"><span data-stu-id="525c8-886">Visio</span></span>

- <span data-ttu-id="525c8-887">C’è stata una regressione nel codice dipendente che è state corretta.</span><span class="sxs-lookup"><span data-stu-id="525c8-887">There was regression in dependent code which has been fixed.</span></span> <span data-ttu-id="525c8-888">Ora le immagini sono sottoposte a rendering tramite i servizi Visio in esecuzione su SharePoint OnPrem.</span><span class="sxs-lookup"><span data-stu-id="525c8-888">Now, the images are getting rendered in Visio services running on SharePoint Onprem.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-889">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-889">Word</span></span>

- <span data-ttu-id="525c8-890">È stato risolto un problema per cui i timbri data/ora nei riquadri dei commenti non erano basati sull'ora locale del sistema.</span><span class="sxs-lookup"><span data-stu-id="525c8-890">We fixed an issue where timestamps in Comment panes were not based on the system locale time.</span></span>

- <span data-ttu-id="525c8-891">È stato risolto un problema durante l'apertura di documenti di Word tramite consegna di documenti personalizzati (aspx) con URL contenente un componente di query.</span><span class="sxs-lookup"><span data-stu-id="525c8-891">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="525c8-892">È stato risolto un problema per cui non era possibile visualizzare il testo copiato e incollato in un riquadro dei commenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-892">We fixed an issue where copy and pasting text to a comment pane would not be displayed.</span></span>

- <span data-ttu-id="525c8-893">È stato risolto un problema per cui i collegamenti ipertestuali nei commenti non funzionavano.</span><span class="sxs-lookup"><span data-stu-id="525c8-893">We fixed an issue where hyperlinks in comments weren’t working.</span></span>

- <span data-ttu-id="525c8-894">È stato risolto un problema per cui lo zoom avanti e indietro dall’area della presentazione generava uno spazio vuoto tra il riquadro di selezione con lo zoom e il puntatore del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-894">We fixed an issue where zooming in and out from the presentation area resulted in a gap between the zoomed selection marquee and the mouse pointer.</span></span>

- <span data-ttu-id="525c8-895">È stato risolto un problema per cui i commenti non erano sincronizzati tra l'app web e l'applicazione desktop.</span><span class="sxs-lookup"><span data-stu-id="525c8-895">We fixed an issue where comments between the web app and the desktop application were not in sync.</span></span>

- <span data-ttu-id="525c8-896">È stato risolto un problema per cui le bolle di suggerimenti per i commenti apparivano sfocate con lo zoom al 100%.</span><span class="sxs-lookup"><span data-stu-id="525c8-896">We fixed an issue where comment hint bubbles appeared blurry at 100% zoom.</span></span>

- <span data-ttu-id="525c8-897">È stato risolto un problema per cui non era possibile aggiungere un nuovo commento in un documento vuoto.</span><span class="sxs-lookup"><span data-stu-id="525c8-897">We fixed an issue where adding a new comment on a blank document wouldn't do anything.</span></span>

- <span data-ttu-id="525c8-898">È stato risolto un problema per cui incollare HTML in WordMail per il Calendario non funzionava.</span><span class="sxs-lookup"><span data-stu-id="525c8-898">We fixed an issue where pasting HTML into WordMail for Calendar wasn’t working.</span></span>

- <span data-ttu-id="525c8-899">È stato risolto un problema per cui la risposta a un commento in una sessione condivisa in alcuni casi causava il blocco di Word.</span><span class="sxs-lookup"><span data-stu-id="525c8-899">We fixed an issue where replying to a comment in a co-authored session could sometimes cause Word to freeze.</span></span>

- <span data-ttu-id="525c8-900">È stato risolto un problema per cui l'inserimento o l'aggiornamento dell’indice in un documento contenente più di cento voci comportava l'arresto anomalo dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-900">We fixed an issue where inserting or updating an Index in a document containing more than a hundred entries would result in the application crashing.</span></span>

- <span data-ttu-id="525c8-901">È stato risolto un problema per cui l'abilitazione di Word 2007 e in seguito dei documenti e dei modelli binari causava il fallimento di alcuni casi di creazione condivisa.</span><span class="sxs-lookup"><span data-stu-id="525c8-901">We fixed an issue where enabling policy Word 2007 and later Binary Documents and Templates would cause some co-authoring cases to fail.</span></span>

- <span data-ttu-id="525c8-902">È stato risolto un problema per cui i file con valori XML personalizzati si aprivano in modo estremamente lento.</span><span class="sxs-lookup"><span data-stu-id="525c8-902">We fixed an issue where files with custom xml values opened extremely slowly.</span></span>

- <span data-ttu-id="525c8-903">È stato risolto un problema per cui i file con lunghi nomi di percorso, oltre 32K, non si aprivano e non veniva visualizzato un messaggio di errore appropriato.</span><span class="sxs-lookup"><span data-stu-id="525c8-903">We fixed an issue where files with long path names (greater than 32K) would not open and an appropriate error message was not being displayed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="525c8-904">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-904">Office Suite</span></span>

- <span data-ttu-id="525c8-905">Abbiamo esaminato e risolto il problema per cui una distribuzione di Office 365 ProPlus tramite InTune veniva sospesa dopo un arresto del sistema operativo.</span><span class="sxs-lookup"><span data-stu-id="525c8-905">We have investigated and resolved the issue where an Office 365 ProPlus deployment via InTune is paused after an OS shutdown.</span></span>

- <span data-ttu-id="525c8-906">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA contenenti riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso venivano visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="525c8-906">We fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="525c8-907">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="525c8-907">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-june-08"></a><span data-ttu-id="525c8-909">Versione 2005: 08 giugno</span><span class="sxs-lookup"><span data-stu-id="525c8-909">Version 2005: June 08</span></span>
<span data-ttu-id="525c8-910">*Versione 2005 (Build 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="525c8-910">*Version 2005 (Build 12827.20336)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-912">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-912">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="525c8-913">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-913">PowerPoint</span></span>

- <span data-ttu-id="525c8-914">È stato risolto un problema con la finestra di dialogo Sostituisci caratteri, in cui il menu a discesa Sostituisci carattere mostrava solo i tipi di carattere all'interno della presentazione anziché quelli installati nel sistema.</span><span class="sxs-lookup"><span data-stu-id="525c8-914">We have fixed an issue with replace fonts dialog where replace font dropdown only shows fonts within the presentation instead of fonts installed on the system.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-june-04"></a><span data-ttu-id="525c8-916">Versione 2005: 04 giugno</span><span class="sxs-lookup"><span data-stu-id="525c8-916">Version 2005: June 04</span></span>
<span data-ttu-id="525c8-917">*Versione 2005 (Build 12827.20320)*</span><span class="sxs-lookup"><span data-stu-id="525c8-917">*Version 2005 (Build 12827.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-919">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-919">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="525c8-920">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-920">Access</span></span>

- <span data-ttu-id="525c8-921">**Rimani al passo con i tempi! La tipologia di dati con data/ora estesa offre una maggiore precisione:** introducendo un tipo di dati nuovo e migliorato.</span><span class="sxs-lookup"><span data-stu-id="525c8-921">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span>  <span data-ttu-id="525c8-922">Per migliorare la compatibilità della sintassi con SQL e per aumentare l'accuratezza e il livello di dettaglio nei record che includono date e ore, il tipo di dati DateTime2 viene implementato in Access.</span><span class="sxs-lookup"><span data-stu-id="525c8-922">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="525c8-923">Questa tipologia aggiuntiva di dati data/ora includerà un intervallo di date più ampio (da 0001-01-01 a 9999-12-31), con precisione temporale più specifica (nanosecondi, anziché secondi), per cui sarà possibile fornire ed eseguire calcoli.</span><span class="sxs-lookup"><span data-stu-id="525c8-923">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="525c8-924">Per abilitare, selezionare Nuovo campo > Data e ora estesa.</span><span class="sxs-lookup"><span data-stu-id="525c8-924">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="525c8-925">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-925">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="525c8-926">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-926">Excel</span></span>

- <span data-ttu-id="525c8-927">**Creare tabelle pivot da set di documenti in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di documenti archiviati in Power BI in pochi click.</span><span class="sxs-lookup"><span data-stu-id="525c8-927">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="525c8-928"> Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI.</span><span class="sxs-lookup"><span data-stu-id="525c8-928">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="525c8-929">Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI.</span><span class="sxs-lookup"><span data-stu-id="525c8-929">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-930">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-930">Outlook</span></span>

- <span data-ttu-id="525c8-931">**Opzione per riaprire rapidamente gli elementi dalla sessione Outlook precedente:** è stata aggiunta un'opzione per riaprire rapidamente gli elementi da una sessione di Outlook precedente.</span><span class="sxs-lookup"><span data-stu-id="525c8-931">**Option to quickly reopen items from previous Outlook session:** We added an option to quickly reopen items from a previous Outlook session.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-934">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-934">Resolved issues</span></span>
### <a name="powerpoint"></a><span data-ttu-id="525c8-935">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-935">PowerPoint</span></span>

- <span data-ttu-id="525c8-936">Ciò risolve un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-936">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-937">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="525c8-937">Office Suite</span></span>

- <span data-ttu-id="525c8-938">È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-938">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-may-29"></a><span data-ttu-id="525c8-940">Versione 2005: 29 maggio</span><span class="sxs-lookup"><span data-stu-id="525c8-940">Version 2005: May 29</span></span>
<span data-ttu-id="525c8-941">*Versione 2005 (Build 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="525c8-941">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-943">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-943">Feature updates</span></span>

### <a name="excel"></a><span data-ttu-id="525c8-944">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-944">Excel</span></span>

- <span data-ttu-id="525c8-945">**Visualizzazione foglio:** è possibile ordinare e filtrare mentre si collabora con altri utenti nella versione desktop di Excel.</span><span class="sxs-lookup"><span data-stu-id="525c8-945">**Sheet View:** Sort/filter while collaborating with others in Excel desktop.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-946">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-946">Outlook</span></span>

- <span data-ttu-id="525c8-947">**Altri pulsanti aggiunti agli avvisi popup di Outlook:** i pulsanti di azione rapida sono ora visualizzati negli avvisi popup di Outlook quando si esegue Outlook in Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-947">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-950">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-950">Resolved issues</span></span>



### <a name="outlook"></a><span data-ttu-id="525c8-951">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-951">Outlook</span></span>

- <span data-ttu-id="525c8-952">È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso  Stato dell’antivirus: non valido.</span><span class="sxs-lookup"><span data-stu-id="525c8-952">Addressed an issue that caused users of Windows 10 server versions to see the warning  Antivirus status: Invalid.</span></span> <span data-ttu-id="525c8-953">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato installato correttamente l’antivirus.</span><span class="sxs-lookup"><span data-stu-id="525c8-953">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="525c8-954">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="525c8-954">Office Suite</span></span>

- <span data-ttu-id="525c8-955">L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="525c8-955">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="525c8-956">La modifica potrebbe risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="525c8-956">This change would fix this issue.</span></span>


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-may-21"></a><span data-ttu-id="525c8-958">Versione 2005: 21 maggio</span><span class="sxs-lookup"><span data-stu-id="525c8-958">Version 2005: May 21</span></span>
<span data-ttu-id="525c8-959">*Versione 2005 (Build 12827.20210)*</span><span class="sxs-lookup"><span data-stu-id="525c8-959">*Version 2005 (Build 12827.20210)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-963">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-963">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-964">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-964">Excel</span></span>

- <span data-ttu-id="525c8-965">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="525c8-965">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="525c8-966">In alcuni casi, se si fa clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro verrà nascosta.</span><span class="sxs-lookup"><span data-stu-id="525c8-966">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


### <a name="outlook"></a><span data-ttu-id="525c8-967">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-967">Outlook</span></span>

- <span data-ttu-id="525c8-968">È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.</span><span class="sxs-lookup"><span data-stu-id="525c8-968">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="525c8-969">È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.</span><span class="sxs-lookup"><span data-stu-id="525c8-969">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2005-may-14"></a><span data-ttu-id="525c8-971">Versione 2005: 14 maggio</span><span class="sxs-lookup"><span data-stu-id="525c8-971">Version 2005: May 14</span></span>
<span data-ttu-id="525c8-972">*Versione 2005 (Build 12827.20160)*</span><span class="sxs-lookup"><span data-stu-id="525c8-972">*Version 2005 (Build 12827.20160)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-974">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-974">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-975">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-975">Excel</span></span>

- <span data-ttu-id="525c8-976">**Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.</span><span class="sxs-lookup"><span data-stu-id="525c8-976">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-977">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-977">PowerPoint</span></span>

- <span data-ttu-id="525c8-978">**Non c'è bisogno del clicker grazie agli auricolari:** i Surface Earbuds permettono di controllare le presentazioni di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-978">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="525c8-979">Importante: per usare i gesti per controllare le presentazioni è necessario associare gli auricolari Surface Earbuds nell'app Surface Audio per Windows 10.</span><span class="sxs-lookup"><span data-stu-id="525c8-979">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="525c8-980">Le istruzioni per iniziare a usare l'app Surface Audio in Windows 10 sono disponibili qui.</span><span class="sxs-lookup"><span data-stu-id="525c8-980">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="525c8-981">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-981">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

- <span data-ttu-id="525c8-982">**Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.</span><span class="sxs-lookup"><span data-stu-id="525c8-982">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-983">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-983">Word</span></span>

- <span data-ttu-id="525c8-984">**Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.</span><span class="sxs-lookup"><span data-stu-id="525c8-984">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-987">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-987">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="525c8-988">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-988">Excel</span></span>

- <span data-ttu-id="525c8-989">Sono state aumentate le dimensioni dei controlli per la modifica del riferimento di cella nella finestra di dialogo Barre di errore personalizzate usata con i grafici.</span><span class="sxs-lookup"><span data-stu-id="525c8-989">Increased the size of the cell reference edit controls on the Custom Error Bars dialog used with charts.</span></span>

- <span data-ttu-id="525c8-990">È stato risolto un problema di rendering dei valori in un asse data nella tabella dati del grafico.</span><span class="sxs-lookup"><span data-stu-id="525c8-990">Fixed an issue where chart data table could render values in a date axis incorrectly.</span></span>

- <span data-ttu-id="525c8-991">È stato risolto un problema che impediva la disabilitazione delle interruzioni di pagina dopo il passaggio a Layout di pagina o Anteprima interruzioni di pagina.</span><span class="sxs-lookup"><span data-stu-id="525c8-991">Fixed an issue where page breaks could not be disabled after going into Page Layout or Page Break Preview.</span></span>

- <span data-ttu-id="525c8-992">È stato risolto un problema di perdita degli stili di linea del grafico dopo aver nascosto e visualizzato le colonne con i dati della serie.</span><span class="sxs-lookup"><span data-stu-id="525c8-992">Fixed an issue where chart line styles could be lost after hiding and unhiding columns with series data.</span></span>

- <span data-ttu-id="525c8-993">È stato risolto un problema per cui l'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="525c8-993">Fixed an issue where inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="525c8-994">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="525c8-994">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="525c8-995">È stato risolto un problema per cui il collegamento esterno non funzionava dopo la riapertura del file se il percorso del file è troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="525c8-995">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="525c8-996">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="525c8-996">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="525c8-997">Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="525c8-997">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="525c8-998">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="525c8-998">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="525c8-999">Questa modifica risolve un problema per cui le informazioni con formattazione condizionale non venivano salvate correttamente nei file XLSB.</span><span class="sxs-lookup"><span data-stu-id="525c8-999">This change fixes an issue where conditional formatting (CF) information was not being saved to XLSB files correctly.</span></span>

- <span data-ttu-id="525c8-1000">Questa modifica consente di risolvere un problema per cui il valore R quadrato per una linea di tendenza (nel caso di intercetta y forzata), non era corretto, anche se la funzione REGR.LIN restituiva il valore corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1000">This change fixes an issue where the chart trendline R-Squared value (in the forced y-intercept case) was incorrect even though the LINEST function returns the correct value.</span></span>

- <span data-ttu-id="525c8-1001">Questa modifica risolve un problema per cui il formato della linea di tendenza del grafico personalizzata non sempre veniva salvato.</span><span class="sxs-lookup"><span data-stu-id="525c8-1001">This change fixes an issue where customized chart trendline formatting was not always being saved.</span></span>

- <span data-ttu-id="525c8-1002">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità legacy "cartella di lavoro condivisa".</span><span class="sxs-lookup"><span data-stu-id="525c8-1002">A crash could occur when trying to list changes on a new sheet for a workbook using legacy"Shared Workbook" mode.</span></span>

- <span data-ttu-id="525c8-1003">È stato risolto il problema che poteva impedire il salvataggio della formattazione personalizzata dei grafici pivot quando era abilitata l'opzione "Inverti se negativo".</span><span class="sxs-lookup"><span data-stu-id="525c8-1003">Fixed the issue where custom formatting in Pivot charts may not be saved when the "Invert if negative" option was enabled.</span></span>

- <span data-ttu-id="525c8-1004">È stato risolto un problema per cui non veniva salvata la formattazione personalizzata per un singolo punto dati in un grafico pivot se era stata selezionata l'opzione "Inverti se negativo".</span><span class="sxs-lookup"><span data-stu-id="525c8-1004">Fixed an issue where custom formatting for a single data point in a Pivot chart was not saved if the "Invert if negative" option was selected.</span></span>

- <span data-ttu-id="525c8-1005">Questa modifica risolve un problema per cui il carattere "@" caricato in un file CSV comportava la conversione della stringa dopo il carattere "@" in una formula.</span><span class="sxs-lookup"><span data-stu-id="525c8-1005">This change fixes an issue where the '@' character uploaded in a CSV file, would result in the string after the '@' character to be converted to a formula.</span></span>

- <span data-ttu-id="525c8-1006">È stato risolto un problema per cui i valori decimali della funzione sequenza non venivano arrotondati correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1006">Fixed an issue where decimal values in the SEQUENCE function were not rounded correctly.</span></span>

### <a name="onenote"></a><span data-ttu-id="525c8-1007">OneNote</span><span class="sxs-lookup"><span data-stu-id="525c8-1007">OneNote</span></span>

- <span data-ttu-id="525c8-1008">È stato risolto un problema per cui le interruzioni di riga venivano archiviate come schede verticali.</span><span class="sxs-lookup"><span data-stu-id="525c8-1008">Fixed an issue where line breaks were being stored as vertical tabs.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1009">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1009">Outlook</span></span>

- <span data-ttu-id="525c8-1010">Risolve un problema che impediva agli utenti di aggiungere un gruppo di contatti personale come partecipante alla riunione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1010">Addresses an issue that caused users to be unable to add a Personal Contact Group as a Meeting attendee.</span></span>

- <span data-ttu-id="525c8-1011">È stato risolto un problema per cui il pulsante categorizza per i calendari di gruppo sulla barra multifunzione di Office era disabilitato.</span><span class="sxs-lookup"><span data-stu-id="525c8-1011">Fixed an issue where the categorize button for group calendars in the Office Ribbon was disabled.</span></span>

- <span data-ttu-id="525c8-1012">È stato risolto un problema che causava l'arresto anomalo di Outlook all'apertura di file con estensione msg o oft salvati in locale dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="525c8-1012">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="525c8-1013">È stato risolto un problema per cui i clienti aziendali con cartelle di gruppo non implementate o non funzionanti visualizzavano il messaggio "Outlook non risponde".</span><span class="sxs-lookup"><span data-stu-id="525c8-1013">Fixed an issue where enterprise customers with group folders not implemented or not working, would result in Outlook displaying a "not responding" message.</span></span>

- <span data-ttu-id="525c8-1014">È stato risolto un problema che impediva il caricamento dei collegamenti sicuri molto lunghi su cui gli utenti facevano clic nel client desktop di Outlook a causa di un troncamento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1014">Addressed an issue that caused very long safelinks that users clicked on in the Outlook Desktop client to fail to load due to truncation.</span></span>

- <span data-ttu-id="525c8-1015">È stato risolto un problema per cui le cartelle di Outlook con nomi contenenti caratteri del set di caratteri a due byte (DBCS) talvolta scomparivano durante la sincronizzazione con il server.</span><span class="sxs-lookup"><span data-stu-id="525c8-1015">Fixed an issue where Outlook folders with names containing DBCS (Double Byte Character Set) characters would intermittently disappear when synchronizing with the server.</span></span> <span data-ttu-id="525c8-1016">Questo succedeva con Outlook configurato con un account IMAP ed eseguito in un sistema con le impostazioni locali impostate su giapponese.</span><span class="sxs-lookup"><span data-stu-id="525c8-1016">For this to happen, Outlook had to be configured with an IMAP account and running on a system with the locale set to Japanese.</span></span>

- <span data-ttu-id="525c8-1017">È stato risolto un problema per cui le regole di eliminazione create per le cassette postali diverse da quella principale dell'utente non erano più valide.</span><span class="sxs-lookup"><span data-stu-id="525c8-1017">Addressed an issue that caused delete rules created for mailboxes other than the user's primary mailbox to become invalid.</span></span>

- <span data-ttu-id="525c8-1018">È stato risolto un problema che causava la perdita di allegati quando si inoltrava un messaggio crittografato.</span><span class="sxs-lookup"><span data-stu-id="525c8-1018">Addressed an issue that caused attachments to get dropped when forwarding an encrypted message.</span></span>

- <span data-ttu-id="525c8-1019">È stato risolto un problema che impediva la visualizzazione in Assistente Pianificazione dell'oggetto delle riunioni pianificate tra più di 2 mesi.</span><span class="sxs-lookup"><span data-stu-id="525c8-1019">Addressed an issue that caused meetings that are more than 2 months away to fail to display a meeting subject in the Scheduling Assistant.</span></span>

- <span data-ttu-id="525c8-1020">È stato risolto un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1020">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="525c8-1021">È stata aggiunta la funzionalità della configurazione di firma predefinita S/MIME tramite criteri di gruppo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1021">Added the ability to enforce S/MIME default signing configuration via group policy.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1022">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1022">PowerPoint</span></span>

- <span data-ttu-id="525c8-1023">È stato risolto un problema per cui, se un utente creava un commento senza pubblicarlo e chiudeva il riquadro Commenti, quindi apriva una nuova finestra, si spostava tra più diapositive, chiudeva la finestra e infine riapriva il riquadro Commenti nella presentazione originale, i commenti bozza non erano disponibili.</span><span class="sxs-lookup"><span data-stu-id="525c8-1023">Fixed an issue where if a user created a comment without posting it and closed the Comments pane, then opened a new window, navigated through multiple slides and, closed the window, and finally re-opened the Comments pane in the original presentation, the draft comments would not be available.</span></span>

- <span data-ttu-id="525c8-1024">È stato risolto un problema per cui, posizionando il puntatore del mouse sul simbolo dell'asterisco (\*), non venivano mostrati il nome utente dell'ultima persona ad aggiornare il documento e la data della modifica.</span><span class="sxs-lookup"><span data-stu-id="525c8-1024">Fixed an issue where hovering over the asterisk (\*) symbol did not display the user name and date of the last person to update the document.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-1025">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1025">Project</span></span>

- <span data-ttu-id="525c8-1026">Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1026">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="525c8-1027">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si cambia il campo Stato bacheca in un progetto connesso a un elenco attività di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-1027">Fixed an issue where Project may crash when changing the board status field on a project that is connected to a SharePoint task list.</span></span>

- <span data-ttu-id="525c8-1028">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1028">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="525c8-1029">È stato risolto un problema per cui se Project era connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies aveva esito negativo quando veniva aggiunto un elemento Lag.</span><span class="sxs-lookup"><span data-stu-id="525c8-1029">Fixed an issue where if Project is connected to Project Web App and the decimal separator is a comma, TaskDependencies Add method fails when Lag is added.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-1030">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1030">Word</span></span>

- <span data-ttu-id="525c8-1031">È stato risolto un problema per cui l'inserimento di commenti in un documento in modalità di collaborazione non sempre funzionava.</span><span class="sxs-lookup"><span data-stu-id="525c8-1031">Fixed an issue where inserting comments on a document in collaboration mode would not always work.</span></span>

- <span data-ttu-id="525c8-1032">Questo cambiamento risolve un problema per cui la scheda Persone lampeggiava se veniva selezionata la menzione con @.</span><span class="sxs-lookup"><span data-stu-id="525c8-1032">This change fixes an issue where the People card would flash if the @ mention was clicked.</span></span>

- <span data-ttu-id="525c8-1033">Abilitando l'opzione "Mostra segnalibri", i segnalibri non venivano visualizzati.</span><span class="sxs-lookup"><span data-stu-id="525c8-1033">Enabling the option "Show bookmarks" would not display bookmarks.</span></span> <span data-ttu-id="525c8-1034">Questo problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1034">This has been fixed.</span></span>

- <span data-ttu-id="525c8-1035">È stata risolto il problema per cui alla chiusura di un documento con commenti in bozza veniva chiesto di confermare la chiusura del documento senza salvare la bozza.</span><span class="sxs-lookup"><span data-stu-id="525c8-1035">Fixed the issue where closing a document with draft comments would prompt the user if they wanted to close the document without saving the draft comments.</span></span> <span data-ttu-id="525c8-1036">Annullando il messaggio, il documento veniva chiuso invece di rimanere aperto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1036">Cancelling the prompt would close the document rather than leaving it open.</span></span>

- <span data-ttu-id="525c8-1037">È stato risolto un problema di copia e incolla di intestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1037">We fixed an issue in copying and pasting headings.</span></span>

- <span data-ttu-id="525c8-1038">È stato risolto un problema per cui durante la traduzione di un commento pubblicato veniva visualizzato l'errore ‘L'inserimento del testo tradotto non è riuscito’.</span><span class="sxs-lookup"><span data-stu-id="525c8-1038">Fixed an issue where translating a posted comment would result in the error 'Inserting translated text failed'.</span></span>

- <span data-ttu-id="525c8-1039">Questa modifica risolve un problema per cui il testo con collegamenti ipertestuali poteva non essere visualizzato se era abilitata l'opzione: "Mostra codici di campo anziché i relativi valori".</span><span class="sxs-lookup"><span data-stu-id="525c8-1039">This change fixes an issue where text with hyperlinks may not display if the option: "Show field codes instead of their values" was enabled.</span></span>

- <span data-ttu-id="525c8-1040">In visualizzazione Web/Strumento di lettura immersiva, la selezione di un suggerimento determinava lo scorrimento verso l'alto anche se era già visualizzato.</span><span class="sxs-lookup"><span data-stu-id="525c8-1040">In Web View/Immersive reader, clicking on a hint would scroll to the top even though it was already in view.</span></span> <span data-ttu-id="525c8-1041">Questo problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1041">This has been fixed.</span></span>

- <span data-ttu-id="525c8-1042">È stato risolto un problema per cui, quando si provava a salvare un file contenente una macro con un nuovo nome, il file veniva salvato con estensione docx e il nome file WRO0004.docx, indipendentemente dall'immissione dell'utente, rendendo il documento inutilizzabile.</span><span class="sxs-lookup"><span data-stu-id="525c8-1042">We fixed an issue that, when attempting to save a file containing a macro under a new name, would cause it to be saved with .docx extension and the filename WRO0004.docx, regardless of what the user entered, rendering the document unusable.</span></span>

### <a name="office-suite"></a><span data-ttu-id="525c8-1043">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1043">Office Suite</span></span>

- <span data-ttu-id="525c8-1044">Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1044">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span>  <span data-ttu-id="525c8-1045">In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="525c8-1045">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span>  <span data-ttu-id="525c8-1046">Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="525c8-1046">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="525c8-1047">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="525c8-1047">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="525c8-1048">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1048">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-11"></a><span data-ttu-id="525c8-1050">Versione 2004: 11 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1050">Version 2004: May 11</span></span>
<span data-ttu-id="525c8-1051">*Versione 2004 (Build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1051">*Version 2004 (Build 12730.20270)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1053">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1053">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1054">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1054">Excel</span></span>

- <span data-ttu-id="525c8-1055">**Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1055">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1056">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1056">Outlook</span></span>

- <span data-ttu-id="525c8-1057">**Collegamenti migliorati nei messaggi di posta elettronica:** quando si include un collegamento a un file, il nome del file sostituisce l'URL.</span><span class="sxs-lookup"><span data-stu-id="525c8-1057">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="525c8-1058">È possibile modificare le autorizzazioni per consentire l'accesso a tutti i destinatari.</span><span class="sxs-lookup"><span data-stu-id="525c8-1058">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="525c8-1059">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1059">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="525c8-1060">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="525c8-1060">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>

- <span data-ttu-id="525c8-1061">**Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1061">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1062">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1062">PowerPoint</span></span>

- <span data-ttu-id="525c8-1063">**Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1063">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>  [<span data-ttu-id="525c8-1064">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1064">Learn more</span></span>](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)

### <a name="word"></a><span data-ttu-id="525c8-1065">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1065">Word</span></span>

- <span data-ttu-id="525c8-1066">**Raccontare le storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate, un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1066">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1069">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1069">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1070">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1070">Outlook</span></span>

- <span data-ttu-id="525c8-1071">È stato risolto un problema che causava un arresto anomalo quando venivano visualizzati avvisi popup.</span><span class="sxs-lookup"><span data-stu-id="525c8-1071">Addressed an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-2004-may-04"></a><span data-ttu-id="525c8-1073">Versione 2004: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1073">Version 2004: May 04</span></span>
<span data-ttu-id="525c8-1074">*Versione 2004 (Build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1074">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1076">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1076">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1077">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1077">Outlook</span></span>

- <span data-ttu-id="525c8-1078">**Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai.</span><span class="sxs-lookup"><span data-stu-id="525c8-1078">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="525c8-1079">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1079">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="525c8-1080">**Notifica di evento imprevisto per gli amministratori IT:** gli amministratori globali dei tenant di Microsoft 365 e gli amministratori delle app di Office verranno avvisati degli eventi imprevisti di Outlook e Office 365 Exchange che interessano gli utenti tramite una nuova notifica nel riquadro a destra in Outlook per Windows.</span><span class="sxs-lookup"><span data-stu-id="525c8-1080">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="525c8-1081">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1081">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1084">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1084">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="525c8-1085">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1085">Office Suite</span></span>

- <span data-ttu-id="525c8-1086">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1086">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="525c8-1088">Versione 2004: 29 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1088">Version 2004: April 29</span></span>
<span data-ttu-id="525c8-1089">*Versione 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1089">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1091">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1091">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1092">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1092">Outlook</span></span>

- <span data-ttu-id="525c8-1093">**Protezione dei dati nel gruppo:** l'etichetta di riservatezza che si sceglie quando si crea un gruppo viene applicata ai messaggi di posta elettronica, ai documenti e ai siti del team del gruppo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1093">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1096">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1096">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1097">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1097">Outlook</span></span>

- <span data-ttu-id="525c8-1098">È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="525c8-1098">Addresses an issue that caused Outlook to crash on some builds of Windows.</span></span>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2004-april-25"></a><span data-ttu-id="525c8-1100">Versione 2004: 25 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1100">Version 2004: April 25</span></span>
<span data-ttu-id="525c8-1101">*Versione 2004 (Build 12730.20206)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1101">*Version 2004 (Build 12730.20206)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1103">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1103">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1104">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1104">Outlook</span></span>

- <span data-ttu-id="525c8-1105">È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="525c8-1105">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-1106">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1106">Project</span></span>

- <span data-ttu-id="525c8-1107">È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.</span><span class="sxs-lookup"><span data-stu-id="525c8-1107">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-1108">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1108">Office Suite</span></span>

- <span data-ttu-id="525c8-1109">Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1109">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2004-april-21"></a><span data-ttu-id="525c8-1111">Versione 2004: 21 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1111">Version 2004: April 21</span></span>
<span data-ttu-id="525c8-1112">*Versione 2004 (Build 12730.20182)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1112">*Version 2004 (Build 12730.20182)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1114">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1114">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1115">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1115">Outlook</span></span>

- <span data-ttu-id="525c8-1116">Risolve un problema che ha causato il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="525c8-1116">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="525c8-1117">Risolve un problema che causava un blocco uscendo da Outlook.</span><span class="sxs-lookup"><span data-stu-id="525c8-1117">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2004-april-15"></a><span data-ttu-id="525c8-1119">Versione 2004: 15 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1119">Version 2004: April 15</span></span>
<span data-ttu-id="525c8-1120">*Versione 2004 (Build 12730.20150)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1120">*Version 2004 (Build 12730.20150)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1122">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1122">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1123">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1123">Excel</span></span>

- <span data-ttu-id="525c8-1124">**Il supporto per il connettore Facebook sta per terminare:** a partire dal 2020 aprile, Excel non supporterà più connessioni dati esterne che usano il connettore Facebook.</span><span class="sxs-lookup"><span data-stu-id="525c8-1124">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1125">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1125">Outlook</span></span>

- <span data-ttu-id="525c8-1126">**Nuova opzione per disabilitare i suggerimenti di @menzioni durante la composizione dei messaggi di posta elettronica in Outlook:** si trovano i suggerimenti per la selezione delle menzioni più fastidiosi che utili?</span><span class="sxs-lookup"><span data-stu-id="525c8-1126">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="525c8-1127">Ora è possibile disattivarli.</span><span class="sxs-lookup"><span data-stu-id="525c8-1127">Now you can turn it off if you prefer.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1128">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1128">PowerPoint</span></span>

- <span data-ttu-id="525c8-1129">**Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1129">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1130">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1130">Word</span></span>

- <span data-ttu-id="525c8-1131">**Annotare la copia privata:** è possibile creare note scritte a mano visibili solo a se stessi creando una copia privata di un documento condiviso.</span><span class="sxs-lookup"><span data-stu-id="525c8-1131">**Annotate your private copy:** Create hand written notes for your eyes by making a private copy of a shared document.</span></span> <span data-ttu-id="525c8-1132">Passare alla Visualizza > Crea una copia privata per iniziare.</span><span class="sxs-lookup"><span data-stu-id="525c8-1132">Go to View > Create a Private Copy to get started.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1135">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1135">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-1136">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-1136">Access</span></span>

- <span data-ttu-id="525c8-1137">Sono stati risolti problemi relativi al ridimensionamento e all'aggiornamento di tabelle nel riquadro attività.</span><span class="sxs-lookup"><span data-stu-id="525c8-1137">Fixed issues with resizing and refreshing tables in the task pane.</span></span>

- <span data-ttu-id="525c8-1138">È stato risolto un problema per cui nell'interfaccia utente delle versioni internazionali di Access venivano visualizzate stringhe in inglese.</span><span class="sxs-lookup"><span data-stu-id="525c8-1138">Fixed an issue where international versions of Access were displaying English strings in the user interface.</span></span>

### <a name="excel"></a><span data-ttu-id="525c8-1139">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1139">Excel</span></span>

- <span data-ttu-id="525c8-1140">È stato risolto un problema per cui, selezionando un intervallo di celle in un foglio, veniva selezionata una singola cella.</span><span class="sxs-lookup"><span data-stu-id="525c8-1140">Fixed an issue where selecting a range of cells on a sheet would result in the selection of a single cell.</span></span>

- <span data-ttu-id="525c8-1141">Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1141">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="525c8-1142">È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="525c8-1142">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="525c8-1143">Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1143">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="525c8-1144">È stato risolto un problema di prestazioni che talvolta gli utenti sperimentavano quando modificavano un intervallo di celle elevato a livello di programmazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1144">Fixed a performance issue that users may have experienced when programmatically editing a large range of cells.</span></span>

- <span data-ttu-id="525c8-1145">È stato risolto un problema di prestazioni che si verificava durante l'apertura di file CSV in ambiente giapponese.</span><span class="sxs-lookup"><span data-stu-id="525c8-1145">Fixed a performance issue that occurred when opening csv files with Japanese environments.</span></span>

- <span data-ttu-id="525c8-1146">È stato risolto un problema per cui, inserendo un modello di grafico definito dall'utente come predefinito, veniva salvato come istogramma.</span><span class="sxs-lookup"><span data-stu-id="525c8-1146">Fixed an issue where inserting a user defined chart template as default would result in saving it as a column chart.</span></span>

- <span data-ttu-id="525c8-1147">È stato risolto un problema per cui le etichette dati apparivano vuote quando le celle di dati sottostanti non avevano una didascalia.</span><span class="sxs-lookup"><span data-stu-id="525c8-1147">Fixed an issue where Data labels on charts would display as blank when the underlying data cells did not have a caption.</span></span>

- <span data-ttu-id="525c8-1148">È stato risolto un problema per cui Excel poteva smettere di rispondere riducendo le dimensioni di un grafico con alcuni intervalli dell'asse x.</span><span class="sxs-lookup"><span data-stu-id="525c8-1148">Fixed an issue which could cause Excel to stop responding when reducing the size of a chart with some x-axis ranges.</span></span>

- <span data-ttu-id="525c8-1149">È stato risolto un problema per cui, durante la condivisione/creazione in modalità condivisa di un foglio di Excel con lo stile di riferimento R1C1 abilitato, passando il mouse sull'icona di presenza utente non compariva il riferimento di cella attivo in modalità R1C1.</span><span class="sxs-lookup"><span data-stu-id="525c8-1149">Fixed an issue where an Excel sheet with R1C1 cell referencing enabled and is being co-authored / shared, hovering over the user presence icon does not display the active cell reference in R1C1 mode.</span></span>

- <span data-ttu-id="525c8-1150">Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1150">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1151">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1151">Outlook</span></span>

- <span data-ttu-id="525c8-1152">Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1152">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="525c8-1153">Questa modifica risolve un problema per cui le ultime modifiche apportate alle bozze di messaggi di posta elettronica non venivano aggiornate.</span><span class="sxs-lookup"><span data-stu-id="525c8-1153">This change fixes an issue where the latest changes to draft emails were not being updated.</span></span>

- <span data-ttu-id="525c8-1154">È stato risolto un problema per cui fare clic con il pulsante destro del mouse su un file e scegliere "Invia a" non funzionava.</span><span class="sxs-lookup"><span data-stu-id="525c8-1154">Fixed an issue where right-mouse clicking on a file and using 'Send to' would not work.</span></span>

- <span data-ttu-id="525c8-1155">È stato risolto un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="525c8-1155">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="525c8-1156">È stato risolto un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="525c8-1156">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="525c8-1157">È stato risolto un problema che causava la mancata attivazione di alcuni promemoria cambiando il fuso orario in un computer.</span><span class="sxs-lookup"><span data-stu-id="525c8-1157">Addressed an issue that caused some reminders to fail to fire when changing the timezone on a machine.</span></span>

- <span data-ttu-id="525c8-1158">È stato risolto un problema che causava l'arresto anomalo provando a visualizzare le proprietà di un modulo dell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1158">Addressed an issue that caused users to experience a crash when attempting to view the properties of an Organizational Form.</span></span>

- <span data-ttu-id="525c8-1159">È stato risolto un problema per cui, se un utente aveva personalizzato il percorso di ricerca per la Rubrica, l'ambito di risoluzione dei nomi di Outlook era limitato al percorso personalizzato e non includeva l'elenco indirizzi globale.</span><span class="sxs-lookup"><span data-stu-id="525c8-1159">Fixed an issue where if a user had a customized the search path for the Address book, Outlook's name resolution scope would be limited to the customized path rather than including the Global Address List (GAL).</span></span>

- <span data-ttu-id="525c8-1160">È stato risolto un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="525c8-1160">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="525c8-1161">È stato risolto un problema che impediva agli utenti di aggiungere una firma rispondendo a un messaggio protetto con Digital Rights Management da una finestra Inspector quando l'utente non ha l'autorizzazione di proprietario per il messaggio a cui sta rispondendo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1161">Addressed an issue that caused users to be unable to add a signature when replying to a digitally rights managed message from an inspector window when the user does not have Owner permission on the message being replied to.</span></span>

- <span data-ttu-id="525c8-1162">È stato risolto un problema che impediva agli utenti di aggiungere altri allegati da un percorso Web a una riunione creata in precedenza.</span><span class="sxs-lookup"><span data-stu-id="525c8-1162">Addressed an issue that caused users to be unable to add additional attachments from a web location to a previously created meeting.</span></span>

- <span data-ttu-id="525c8-1163">È stato risolto un problema per la cui i dati relativi all'ultima modifica di un file venivano aggiornati quando si aggiungeva un allegato a un messaggio di posta elettronica o si salvava un allegato da un messaggio di posta elettronica trascinandolo, anziché tramite un menu.</span><span class="sxs-lookup"><span data-stu-id="525c8-1163">Addressed an issue that caused the "Last Modified" date on a file to be updated when adding an attachment to a mail or saving an attachment from a mail by dragging and dropping it (as opposed to via a menu).</span></span>

- <span data-ttu-id="525c8-1164">È stato risolto un problema per cui nel riquadro Trova espanso premendo INVIO non si avviava la ricerca, ma era necessario fare clic sul pulsante Cerca.</span><span class="sxs-lookup"><span data-stu-id="525c8-1164">Addressed an issue that caused hitting enter in the expanded find pane to fail to start a search, requiring instead that users click on the search button.</span></span>

- <span data-ttu-id="525c8-1165">È stato risolto un problema per cui, all'interno di un set di risultati della ricerca restituiti, l'ordinamento dei risultati in base alla categoria non mostrava i colori delle categorie.</span><span class="sxs-lookup"><span data-stu-id="525c8-1165">Fixed an issue where within a set of returned search results, sorting the results by Categories would not display the Category colors.</span></span>

- <span data-ttu-id="525c8-1166">È stato risolto un problema per cui la ricerca non mostrava informazioni sugli utenti quando l'opzione "Mostra fotografie dell'utente quando disponibili" era disabilitata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1166">Fixed an issue where search shows no information about users when the option to "Show user photographs when available" is disabled.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-1167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1167">PowerPoint</span></span>

- <span data-ttu-id="525c8-1168">Questa modifica risolve un errore che poteva causare un errore nel salvataggio dei file di PowerPoint contenenti emoji.</span><span class="sxs-lookup"><span data-stu-id="525c8-1168">This change fixes an error that could cause PowerPoint files containing emojis to fail when saving.</span></span>

- <span data-ttu-id="525c8-1169">Questa modifica risolve un problema per cui, nel rendering di un grafico di Excel legacy incorporato come oggetto OLE in PowerPoint o Word, non sempre veniva visualizzato il titolo del grafico.</span><span class="sxs-lookup"><span data-stu-id="525c8-1169">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="525c8-1170">È stato risolto un problema per cui la formattazione di un testo copiato da Excel a PowerPoint poteva essere modificata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1170">We have fixed an issue when copying text from Excel to PowerPoint might change its formatting.</span></span>

- <span data-ttu-id="525c8-1171">Questa modifica risolve un problema per cui la ricerca di caratteri speciali con l'opzione "Solo parole intere" non funzionava come previsto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1171">This change fixes an issue where finding special characters using 'find whole words only' did not always work as expected.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-1172">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1172">Project</span></span>

- <span data-ttu-id="525c8-1173">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1173">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="525c8-1174">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="525c8-1174">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="525c8-1175">È stato risolto un problema per cui l'evento "ProjectBeforeTaskChange" di Visual Basic, Applications Edition (VBA) non veniva attivato quando un utente faceva clic sul pulsante "Disattiva" disponibile nella barra multifunzione Attività nel gruppo Programmazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1175">Fixed an issue where the 'ProjectBeforeTaskChange' Visual Basic Applications (VBA) event did not fire when a user clicked the “Inactivate” button found on the Tasks Ribbon within the Scheduling grouping.</span></span>

- <span data-ttu-id="525c8-1176">Impostando i dettagli su predecessore o successore da una visualizzazione di tipo modulo, l'evento ProjectBeforeTaskChange Visual Basic Applications (VBA) non sempre acquisiva le modifiche.</span><span class="sxs-lookup"><span data-stu-id="525c8-1176">If you set predecessor or successor details from within a Form type view, the ProjectBeforeTaskChange Visual Basic Applications (VBA) event didn't always capture the changes.</span></span> <span data-ttu-id="525c8-1177">Ad esempio, eliminando una dipendenza e facendo clic su OK nel modulo, l'evento non veniva attivato.</span><span class="sxs-lookup"><span data-stu-id="525c8-1177">For example, if you deleted a dependency and clicked OK on the form, the event did not fire.</span></span> <span data-ttu-id="525c8-1178">Questo comportamento è stato corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1178">This behavior has been fixed.</span></span>

- <span data-ttu-id="525c8-1179">È stato risolto un problema per cui i valori più recenti per il costo effettivo del lavoro eseguito (ACWP) non venivano visualizzati dopo avere apportato una modifica, ad esempio dopo aver cambiato la data.</span><span class="sxs-lookup"><span data-stu-id="525c8-1179">Fixed an issue where the latest values for the Actual Cost of Work Performed (ACWP) would not be displayed after making a change, such as a date change.</span></span>

- <span data-ttu-id="525c8-1180">È stato risolto un problema per cui, aprendo un progetto dal menu Usati di recente (MRU), il file di progetto veniva aperto con accesso in lettura/scrittura.</span><span class="sxs-lookup"><span data-stu-id="525c8-1180">Fixed an issue where opening a project using the Most Recently Used (MRU) menu opened the project file with Read/Write access.</span></span>

- <span data-ttu-id="525c8-1181">Questa modifica risolve un problema per cui, creando un'attività manuale con una data e un'ora di inizio, ma non una durata, l'attività veniva visualizzata con un orario non corretto nella sequenza temporale.</span><span class="sxs-lookup"><span data-stu-id="525c8-1181">This change fixes an issue where if you created a manual task with a start date and a time (but no duration), it would be displayed with an incorrect time on the timeline.</span></span>

- <span data-ttu-id="525c8-1182">È stato risolto un problema per cui la stampa di una sequenza temporale usando un calendario Hijri comportava l'omissione o la duplicazione di un mese nella visualizzazione stampa.</span><span class="sxs-lookup"><span data-stu-id="525c8-1182">Fixed an issue where printing a timeline using a Hijri calendar would result in a month being skipped or duplicated in the print view.</span></span>

- <span data-ttu-id="525c8-1183">Questa modifica risolve un problema relativo all'uso di Pianificazione team con oggetti GDI, che poteva comportare la sovrassegnazione di oggetti GDI e di conseguenza condizioni di memoria insufficiente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1183">This change addresses an issue where working in Team Planner with GDI objects, could result in the over allocation of GDI objects and create low memory conditions.</span></span>

- <span data-ttu-id="525c8-1184">È stato risolto un problema per cui, eseguendo "CustomFieldValueListGetItem" quando non esiste una tabella di ricerca per il campo personalizzato, viene creata una tabella di ricerca vuota anche se non dovrebbe esserlo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1184">Fixed an issue where if CustomFieldValueListGetItem' is executed and a lookup table for the custom field doesn't exist, an empty lookup table is created even though it should not be.</span></span>

- <span data-ttu-id="525c8-1185">Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1185">WhenPredecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired</span></span>

- <span data-ttu-id="525c8-1186">È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1186">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1187">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1187">Word</span></span>

- <span data-ttu-id="525c8-1188">Questa modifica risolve un problema per cui, posizionando il cursore su un suggerimento, non veniva evidenziata la relativa scheda.</span><span class="sxs-lookup"><span data-stu-id="525c8-1188">This change fixes an issue where hovering a cursor over a hint would not highlight its card.</span></span>

- <span data-ttu-id="525c8-1189">Questa modifica risolve un problema per cui selezionando più pagine selezionata nel menu Visualizza, il riquadro Commenti poteva apparire vuoto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1189">This change fixes an issue with multiple pages selected from the View menu, where the comments pane could be displayed as blank.</span></span>

- <span data-ttu-id="525c8-1190">È stato risolto un problema per cui la funzionalità di invio commenti era disabilitata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1190">Fixed an issue where the functionality to post comments was disabled.</span></span>

- <span data-ttu-id="525c8-1191">Questa modifica risolve un problema che causava la scomparsa temporanea del testo nelle forme raggruppate usando lo strumento di selezione Lazo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1191">This change fixes an issue that would cause the text in grouped shapes to disappear temporarily when using the Lasso selection tool.</span></span>

- <span data-ttu-id="525c8-1192">Questa modifica risolve i ritardi nell'elaborazione di immagini con informazioni sul protocollo non valide o in formato non corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1192">This change addresses delays when processing images with malformed or invalid protocol information.</span></span>

- <span data-ttu-id="525c8-1193">Questa modifica risolve un problema per cui, nel rendering di un grafico di Excel legacy incorporato come oggetto OLE in PowerPoint o Word, non sempre veniva visualizzato il titolo del grafico.</span><span class="sxs-lookup"><span data-stu-id="525c8-1193">This change fixes an issue where the rendering of a legacy Excel chart embedded as an OLE object in PowerPoint or Word may not always display the chart title.</span></span>

- <span data-ttu-id="525c8-1194">Questa modifica risolve un problema che impediva all'account manager di inviare messaggi, causando un blocco nelle applicazioni di terze parti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1194">This change addresses an issue where the account manager would not dispatch messages resulting in a hang with third party applications.</span></span>

- <span data-ttu-id="525c8-1195">Questa modifica risolve un problema della visualizzazione a due pagine per cui, creando un commento, l'ancoraggio del commento non sempre era visibile.</span><span class="sxs-lookup"><span data-stu-id="525c8-1195">This change fixes an issue in two page view, when creating a comment, the comment anchor did not always come into view.</span></span>

- <span data-ttu-id="525c8-1196">È stato risolto un problema per cui digitando o modificando un commento e usando la combinazione di tasti CTRL+A veniva selezionato il testo nell'area di disegno anziché nella scheda del commento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1196">Fixed an issue when typing or editing a comment and using Ctrl+A would result in selecting text in the canvas instead of selecting text just within the comment card.</span></span>

- <span data-ttu-id="525c8-1197">È stato risolto un problema per cui, in un paragrafo il cui stile è un predecessore di uno stile collegato a un elenco, la numerazione dell'elenco poteva andare persa.</span><span class="sxs-lookup"><span data-stu-id="525c8-1197">Fixed an issue where if a paragraph whose style is an ancestor of a style linked to a list, then the numbering of that list could be lost.</span></span>

- <span data-ttu-id="525c8-1198">Questa modifica risolve un problema per cui il Sommario veniva aggiornato con stili del titolo non presenti nel documento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1198">This change fixes an issue where the Table of Contents would get updated with heading styles which were not present in the document.</span></span>

- <span data-ttu-id="525c8-1199">È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.</span><span class="sxs-lookup"><span data-stu-id="525c8-1199">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="525c8-1200">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="525c8-1200">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="525c8-1201">È stato risolto un problema per cui le firme digitali salvate nei documenti di Word venivano rimosse al momento dell'invio dei documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1201">Fixed an issue where digital signatures saved in Word documents would be removed when mailing the documents.</span></span>

- <span data-ttu-id="525c8-1202">È stato risolto un problema per cui quando si contrassegnavano le revisioni contenenti delle equazioni si verificava un errore durante il salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="525c8-1202">Fixed an issue where marking revisions involving equations could result in a failure when saving the file.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-14"></a><span data-ttu-id="525c8-1204">Versione 2003: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1204">Version 2003: April 14</span></span>
<span data-ttu-id="525c8-1205">*Versione 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1205">*Version 2003 (Build 12624.20466)*</span></span>

<span data-ttu-id="525c8-1206">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="525c8-1206">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

- <span data-ttu-id="525c8-1208">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1208">Various bugs and performance fixes.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-april-09"></a><span data-ttu-id="525c8-1210">Versione 2003: 9 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1210">Version 2003: April 09</span></span>
<span data-ttu-id="525c8-1211">*Versione 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1211">*Version 2003 (Build 12624.20442)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1213">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1213">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1214">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1214">Excel</span></span>

- <span data-ttu-id="525c8-1215">**Selezione di contenuti Premium di M365:** dare vita ai propri documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1215">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="525c8-1216">Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="525c8-1216">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1217">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1217">Outlook</span></span>

- <span data-ttu-id="525c8-1218">**Selezione di contenuti Premium di M365:** dare vita ai propri documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1218">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="525c8-1219">Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="525c8-1219">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1220">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1220">PowerPoint</span></span>

- <span data-ttu-id="525c8-1221">**Selezione di contenuti Premium di M365:** dare vita ai propri documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1221">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="525c8-1222">Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="525c8-1222">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1223">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1223">Word</span></span>

- <span data-ttu-id="525c8-1224">**Selezione di contenuti Premium di M365:** dare vita ai propri documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1224">**M365 Premium Content Picker:** Bring your documents to life!</span></span> <span data-ttu-id="525c8-1225">Esplora migliaia di immagini di archivio, icone e adesivi gratuiti [Altre informazioni](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span><span class="sxs-lookup"><span data-stu-id="525c8-1225">Explore 1000’s of royalty free stock images, icons and stickers [Learn more](https://support.office.com/article/3c51edf4-22e1-460a-b372-9329a8724344)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-april-03"></a><span data-ttu-id="525c8-1229">Versione 2003: 3 aprile</span><span class="sxs-lookup"><span data-stu-id="525c8-1229">Version 2003: April 03</span></span>
<span data-ttu-id="525c8-1230">*Versione 2003 (Build 12624.20410)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1230">*Version 2003 (Build 12624.20410)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1232">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1232">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1233">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1233">Excel</span></span>

- <span data-ttu-id="525c8-1234">L'uso di Application.Evaluate di VBA talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1234">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1235">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1235">Outlook</span></span>

- <span data-ttu-id="525c8-1236">È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-1236">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="525c8-1237">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1237">Project</span></span>

- <span data-ttu-id="525c8-1238">Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1238">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChangeevent is fired.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1239">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1239">Word</span></span>

- <span data-ttu-id="525c8-1240">È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-1240">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="525c8-1242">Versione 2003: 31 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1242">Version 2003: March 31</span></span>
<span data-ttu-id="525c8-1243">*Versione 2003 (Build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1243">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1245">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1245">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="525c8-1246">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-1246">Access</span></span>

- <span data-ttu-id="525c8-1247">**Riquadro attività Aggiungi tabelle:** il nuovo riquadro attività Aggiungi tabelle è finalmente disponibile.</span><span class="sxs-lookup"><span data-stu-id="525c8-1247">**"Add Tables" Task Pane:** Access's new "Add Tables" Task Pane is finally here!</span></span> <span data-ttu-id="525c8-1248">Questa funzionalità consente la selezione/selezione multipla più semplice delle tabelle che si vogliono aggiungere/rimuovere nell'intervallo di query, senza passare alla finestra di dialogo "Mostra tabelle" per le query e per la visualizzazione relazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1248">This feature allows you to easily select/multi-select which tables they'd like to add/remove into a query window, without navigating to the "Show Tables" dialog for queries and for relationship view.</span></span> <span data-ttu-id="525c8-1249">Include anche una nuova scheda "collegamenti" per visualizzare le tabelle collegate, una casella di ricerca per filtrare l'elenco corrente, la funzionalità "trascinamento della selezione" e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="525c8-1249">This also includes a new "links" tab to display linked tables, a search box to filter the current list, "drag and drop" behavior, and more!</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1252">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1252">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="525c8-1253">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1253">Project</span></span>

- <span data-ttu-id="525c8-1254"><span style="display:inline !important;">È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione di protezione del lavoro effettivo.</span></span><span class="sxs-lookup"><span data-stu-id="525c8-1254"><span style="display:inline !important;">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span></span><br>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-march-25"></a><span data-ttu-id="525c8-1256">Versione 2003: 25 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1256">Version 2003: March 25</span></span>
<span data-ttu-id="525c8-1257">*Versione 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1257">*Version 2003 (Build 12624.20320)*</span></span>

- <span data-ttu-id="525c8-1258">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1258">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-23"></a><span data-ttu-id="525c8-1259">Versione 2003: 23 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1259">Version 2003: March 23</span></span>
<span data-ttu-id="525c8-1260">*Versione 2003 (Build 12624.20296)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1260">*Version 2003 (Build 12624.20296)*</span></span>

- <span data-ttu-id="525c8-1261">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1261">Various bugs and performance fixes.</span></span>

## <a name="version-2003-march-21"></a><span data-ttu-id="525c8-1262">Versione 2003: 21 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1262">Version 2003: March 21</span></span>
<span data-ttu-id="525c8-1263">*Versione 2003 (Build 12624.20276)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1263">*Version 2003 (Build 12624.20276)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1265">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1265">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1266">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1266">Outlook</span></span>

- <span data-ttu-id="525c8-1267">**Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online.</span><span class="sxs-lookup"><span data-stu-id="525c8-1267">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="525c8-1268">Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.</span><span class="sxs-lookup"><span data-stu-id="525c8-1268">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="525c8-1269">**Aggiornamento visivo del calendario:** l'anno scorso abbiamo presentato un'esperienza di posta elettronica rinnovata e quest'anno è il turno del calendario.</span><span class="sxs-lookup"><span data-stu-id="525c8-1269">**Calendar visual refresh:** Last year, we brought you a refreshed mail experience, and, this year, it is the calendar’s turn to get a facelift!</span></span> <span data-ttu-id="525c8-1270">Gli aggiornamenti sono innovativi ma familiari, in modo che gli utenti esperti di Outlook siano subito più produttivi.</span><span class="sxs-lookup"><span data-stu-id="525c8-1270">The updates are fresh but familiar so, as a seasoned Outlook user, you can jump in and be more productive right away.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1271">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1271">PowerPoint</span></span>

- <span data-ttu-id="525c8-1272">**Aggiornamento delle diapositive durante la presentazione:** è possibile aggiornare le diapositive modificate da altri autori durante la presentazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1272">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

## <a name="version-2003-march-16"></a><span data-ttu-id="525c8-1274">Versione 2003: 16 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1274">Version 2003: March 16</span></span>
<span data-ttu-id="525c8-1275">*Versione 2003 (Build 12624.20224)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1275">*Version 2003 (Build 12624.20224)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1277">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1277">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1278">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1278">Excel</span></span>

- <span data-ttu-id="525c8-1279">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="525c8-1279">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1280">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1280">Outlook</span></span>

- <span data-ttu-id="525c8-1281">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="525c8-1281">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1282">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1282">PowerPoint</span></span>

- <span data-ttu-id="525c8-1283">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="525c8-1283">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1284">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1284">Word</span></span>

- <span data-ttu-id="525c8-1285">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="525c8-1285">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span>

### <a name="office-suite"></a><span data-ttu-id="525c8-1286">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1286">Office Suite</span></span>

- <span data-ttu-id="525c8-1287">**Riquadri a schede:** ora è possibile passare da un riquadro all'altro usando un'interfaccia a schede sul lato destro dell'app.</span><span class="sxs-lookup"><span data-stu-id="525c8-1287">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="525c8-1288">L'interfaccia utente sarà visibile solo se sono presenti almeno due riquadri.</span><span class="sxs-lookup"><span data-stu-id="525c8-1288">The UI will only be visible when you have 2+ panes open.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1291">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1291">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1292">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1292">Excel</span></span>

- <span data-ttu-id="525c8-1293">È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.</span><span class="sxs-lookup"><span data-stu-id="525c8-1293">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1294">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1294">Outlook</span></span>

- <span data-ttu-id="525c8-1295">È stato risolto un problema che causava la visualizzazione del processo di Outlook in esecuzione in Gestione attività dopo la chiusura.</span><span class="sxs-lookup"><span data-stu-id="525c8-1295">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-march-10"></a><span data-ttu-id="525c8-1297">Versione 2003: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1297">Version 2003: March 10</span></span>
<span data-ttu-id="525c8-1298">*Versione 2003 (Build 12624.20176)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1298">*Version 2003 (Build 12624.20176)*</span></span>

<span data-ttu-id="525c8-1299">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="525c8-1299">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)
### <a name="feature-updates"></a><span data-ttu-id="525c8-1301">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1301">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1302">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1302">Excel</span></span>
- <span data-ttu-id="525c8-1303">**Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="525c8-1303">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="525c8-1304">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1304">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="powerpoint"></a><span data-ttu-id="525c8-1305">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1305">PowerPoint</span></span>
- <span data-ttu-id="525c8-1306">**Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="525c8-1306">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="525c8-1307">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1307">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)

### <a name="word"></a><span data-ttu-id="525c8-1308">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1308">Word</span></span>
- <span data-ttu-id="525c8-1309">**Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="525c8-1309">**Sensitivity labels**: You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span> [<span data-ttu-id="525c8-1310">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="525c8-1310">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/encryption-sensitivity-labels?view=o365-worldwide#let-users-assign-permissions&preserve-view=true)
</br>

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1311">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1311">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1312">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1312">Excel</span></span>

- <span data-ttu-id="525c8-1313">È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.</span><span class="sxs-lookup"><span data-stu-id="525c8-1313">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="525c8-1314">È stato risolto un problema riscontrato dagli utenti quando rinominavano le misure delle tabelle pivot.</span><span class="sxs-lookup"><span data-stu-id="525c8-1314">Fixed an issue that users may have experienced when renaming pivot table measures.</span></span>

- <span data-ttu-id="525c8-1315">È stato risolto un problema per cui il testo in un filtro dati non veniva ridimensionato correttamente nell'anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="525c8-1315">Fixed an issue where text in a slicer isn't scaled properly in Print Preview.</span></span>

- <span data-ttu-id="525c8-1316">È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1316">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="525c8-1317">È stato risolto un problema che causava il lampeggio dell’interfaccia utente durante l'esecuzione di una macro che interagiva con la barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1317">Fixed an issue that caused the UI to flash when users executed a macro that interacted with the ribbon.</span></span>

- <span data-ttu-id="525c8-1318">È stato risolto un problema per cui i file CSV venivano caricati erroneamente quando la prima parola nel file era TABLE.</span><span class="sxs-lookup"><span data-stu-id="525c8-1318">Fixed an issue where CSV files were loaded incorrectly when the first word in the file was TABLE.</span></span>

- <span data-ttu-id="525c8-1319">È stato risolto un problema per cui gli utenti potevano riscontrare arresti anomali durante il passaggio da una cartella di lavoro a un’altra con un livello di zoom diverso.</span><span class="sxs-lookup"><span data-stu-id="525c8-1319">Fixed an issue where users may have experienced crashes when switching between two workbooks that had different zoom levels.</span></span>

- <span data-ttu-id="525c8-1320">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1320">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="525c8-1321">La modifica risolve un errore di run-time nel modello a oggetti e l'arresto anomalo dell'app (Excel, Word) che si verificano quando i componenti aggiuntivi chiedono elementi host nei documenti/fogli di lavoro che contengono forme con blocchi noSelect.</span><span class="sxs-lookup"><span data-stu-id="525c8-1321">This change addresses a run-time error in the object model and potential crash of the App (Excel, Word) when Add-ins ask for Host Items on documents/worksheets that contain shapes with noSelect locks.</span></span>

- <span data-ttu-id="525c8-1322">Risolve un problema che causava un arresto anomalo di Outlook sincronizzando le impostazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1322">Addresses an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>



### <a name="outlook"></a><span data-ttu-id="525c8-1323">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1323">Outlook</span></span>

- <span data-ttu-id="525c8-1324">È stato risolto un problema per cui una regola creata in Outlook Web Access veniva cancellata nel server Exchange generando un conflitto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1324">Fixed an issue where creating a rule with Outlook Web Access did not persist to the Exchange server and resulted in a conflict.</span></span>

- <span data-ttu-id="525c8-1325">È stato risolto un problema che causava un arresto anomalo di Outlook sincronizzando le impostazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1325">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

- <span data-ttu-id="525c8-1326">È stato risolto un problema per cui nella modalità scura di Outlook non veniva visualizzato l'elenco a discesa nel campo "Da:".</span><span class="sxs-lookup"><span data-stu-id="525c8-1326">Fixed an issue with Outlook in dark mode would not display the drop down list in the 'From:' field.</span></span>

- <span data-ttu-id="525c8-1327">È stato risolto un problema per cui Outlook generava in modo inatteso l'output di registrazione in alcuni scenari, anche quando la registrazione era disattivata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1327">Addressed an issue that caused Outlook to unexpectedly generate logging output in some scenarios, even when logging was turned off.</span></span>

- <span data-ttu-id="525c8-1328">È stato risolto un problema che impediva agli utenti di aprire messaggi di cartelle pubbliche quando Outlook era rimasto in esecuzione durante la notte.</span><span class="sxs-lookup"><span data-stu-id="525c8-1328">Addressed an issue that caused users to be unable to open public folder messages when Outlook was left running overnight.</span></span>

- <span data-ttu-id="525c8-1329">È stata risolta una race condition in cui i pulsanti "Consenti" e "Nega" nella pagina delle autorizzazioni venivano disabilitati durante il flusso di lavoro di autenticazione per l'aggiunta di un account Gmail.</span><span class="sxs-lookup"><span data-stu-id="525c8-1329">Fixed a race condition where the 'Allow' and 'Deny' buttons on the permissions page are disabled during the authentication workflow of adding a Gmail account.</span></span>

- <span data-ttu-id="525c8-1330">È stato risolto un problema per cui gli utenti perdevano l'accesso alla finestra di dialogo delle autorizzazioni del calendario &quot;Opzioni disponibilità&quot;.</span><span class="sxs-lookup"><span data-stu-id="525c8-1330">Addressed an issue that caused users to lose access to the &quot;Free Busy Options&quot; calendar permissions dialog.</span></span>

- <span data-ttu-id="525c8-1331">È stato risolto un problema per cui veniva visualizzato l'avviso &quot;Si è verificato un problema con l'apertura di questo elemento&quot; quando si aprivano le istanze di riunioni ricorrenti inviate da un fuso orario diverso.</span><span class="sxs-lookup"><span data-stu-id="525c8-1331">Fixed an issue that may result in the alert: &quot;Sorry we're having trouble opening this item&quot; when opening some recurring meeting instances sent from a different time zone.</span></span>

- <span data-ttu-id="525c8-1332">È stato risolto un problema a causa del quale gli utenti potrebbero non essere in grado di riaprire un file .msg dopo aver trascinato un allegato da quel messaggio.</span><span class="sxs-lookup"><span data-stu-id="525c8-1332">Addressed an issue that could cause users to be unable to reopen a .msg file after dragging and dropping an attachment from that message.</span></span>

- <span data-ttu-id="525c8-1333">È stato risolto un problema a causa del quale, dopo aver caricato un allegato da Outlook a OneDrive, il nome file potrebbe cambiare se il nome dell'allegato contiene delle parentesi.</span><span class="sxs-lookup"><span data-stu-id="525c8-1333">Fixed an issue where after uploading a file attachment from Outlook to OneDrive could result in the file name being changed if the attachment's name contained parenthesis.</span></span>

- <span data-ttu-id="525c8-1334">È stato risolto un problema che impediva agli utenti di allegare un file al messaggio di posta elettronica tramite Esplora file se il file era aperto in un'altra applicazione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1334">Addressed an issue that caused users to be unable to attach a file to their mail message via the file explorer when that file was open in another application.</span></span>

- <span data-ttu-id="525c8-1335">È stato risolto un problema che causava un arresto anomalo di Outlook sincronizzando le impostazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1335">Addressed an issue that caused Outlook users to experience a crash when synchronizing settings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="525c8-1336">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1336">PowerPoint</span></span>

- <span data-ttu-id="525c8-1337">È stato risolto un problema per cui le anteprime consigliate lampeggiavano durante il passaggio del mouse su di esse.</span><span class="sxs-lookup"><span data-stu-id="525c8-1337">Fixed an issue where the recommended thumbnails flash when hovering your mouse over the thumbnails.</span></span> <span data-ttu-id="525c8-1338">In alcuni casi questo causava un arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-1338">In some cases this could cause PowerPoint to crash.</span></span>

- <span data-ttu-id="525c8-1339">È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.</span><span class="sxs-lookup"><span data-stu-id="525c8-1339">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="525c8-1340">È stato risolto un problema che causava un errore durante il salvataggio di un documento in PowerPoint o Word se il documento conteneva un grafico di Excel.</span><span class="sxs-lookup"><span data-stu-id="525c8-1340">Fixed an issue that could result in a failure to save a document in PowerPoint or Word containing an Excel chart.</span></span>



### <a name="project"></a><span data-ttu-id="525c8-1341">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1341">Project</span></span>

- <span data-ttu-id="525c8-1342">È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1342">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="525c8-1343">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="525c8-1343">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="525c8-1344">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1344">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

### <a name="visio"></a><span data-ttu-id="525c8-1345">Visio</span><span class="sxs-lookup"><span data-stu-id="525c8-1345">Visio</span></span>

- <span data-ttu-id="525c8-1346">Nel riquadro Informazioni forma, la sezione Proprietà forma mostrava dettagli incoerenti quando il file veniva aperto nella versione desktop di Visio.</span><span class="sxs-lookup"><span data-stu-id="525c8-1346">Shape info pane was showing inconsistent details under Shape Data section, with respect to the file when opened in Visio Desktop.</span></span> <span data-ttu-id="525c8-1347">Ora il problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1347">It has now been fixed.</span></span>

- <span data-ttu-id="525c8-1348">Nelle versioni precedenti al 2016, le bitmap importate non venivano visualizzate a causa di alcuni controlli di sicurezza.</span><span class="sxs-lookup"><span data-stu-id="525c8-1348">Bitmaps imported in versions before 2016 were not being rendered due to some security checks.</span></span> <span data-ttu-id="525c8-1349">Questo problema è stato risolto nell'abbonamento di Visio.</span><span class="sxs-lookup"><span data-stu-id="525c8-1349">We have fixed this issue in Visio Subscription.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1350">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1350">Word</span></span>

- <span data-ttu-id="525c8-1351">È stato risolto un problema per cui le schede di commento non venivano sempre evidenziate quando si passava il puntatore del mouse su di esse.</span><span class="sxs-lookup"><span data-stu-id="525c8-1351">Fixed an issue where comment cards don't always get highlighted when a mouse pointer hovers over the comment card.</span></span>

- <span data-ttu-id="525c8-1352">È stato risolto un problema per cui spostandosi tramite TAB in una scheda commento, lo stato attivo sulla casella di modifica del commento non era visibile.</span><span class="sxs-lookup"><span data-stu-id="525c8-1352">Fixed an issue that when tabbing through a comment card, the focus on the comment edit box would not be visible.</span></span>

- <span data-ttu-id="525c8-1353">È stato risolto un problema estetico per cui il pulsante OK nella finestra di dialogo File\Opzioni veniva visualizzato come disattivato, anche se questo non influiva sulla funzionalità.</span><span class="sxs-lookup"><span data-stu-id="525c8-1353">Fixed a cosmetic issue where the 'OK' button on the File \ Options dialog displayed as being grayed out but functionality was not impacted.</span></span>

- <span data-ttu-id="525c8-1354">Durante una sessione di creazione condivisa di documenti attiva, l'aggiunta diretta di un'immagine in una scheda di commento può comportare l'aggiunta di un contrassegno.</span><span class="sxs-lookup"><span data-stu-id="525c8-1354">During an active document co-authoring session, adding an image directly in to a comment card may result in the addition of a tag.</span></span> <span data-ttu-id="525c8-1355">Questo problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1355">This issue has been fixed.</span></span>

- <span data-ttu-id="525c8-1356">Se veniva inserito un controllo in un'equazione, ad esempio un controllo contenuto testo, il salvataggio e l'apertura del file comportavano un errore di contenuto illeggibile.</span><span class="sxs-lookup"><span data-stu-id="525c8-1356">Inserting a control (such as a Text Content Control) in an equation then saving and opening the file results in an un-readable content error.</span></span>

- <span data-ttu-id="525c8-1357">È stato risolto un problema per cui non era possibile salvare un file protetto in precedenza da password, in uno spazio di archiviazione cloud.</span><span class="sxs-lookup"><span data-stu-id="525c8-1357">Fixed an issue where saving a previously password protected file to a cloud storage would not work.</span></span>

- <span data-ttu-id="525c8-1358">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="525c8-1358">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>




### <a name="office-suite"></a><span data-ttu-id="525c8-1359">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1359">Office Suite</span></span>

- <span data-ttu-id="525c8-1360">Se si usavano proprietà di scelta multipla, ricerca o metadati gestiti con documenti di Word, Excel o PowerPoint e si eseguiva il salvataggio in una raccolta documenti di SharePoint, queste proprietà erano limitate a 255 caratteri.</span><span class="sxs-lookup"><span data-stu-id="525c8-1360">When using Multichoice/Lookup/Managed-metadata properties with Word/Excel/PowerPoint documents and saving to a SharePoint Document Library, these properties were previously limited to 255 characters.</span></span> <span data-ttu-id="525c8-1361">Quando queste proprietà superavano i 255 caratteri, non era possibile salvare i documenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1361">When these properties exceeded 255 characters, such documents could not be saved.</span></span> <span data-ttu-id="525c8-1362">Con questa modifica, il limite è stato aumentato a 2048 caratteri.</span><span class="sxs-lookup"><span data-stu-id="525c8-1362">With this change, this limit has been increased to 2048 characters.</span></span>

- <span data-ttu-id="525c8-1363">È stato risolto un problema con Word/Excel/PowerPoint per cui il nome dell'entità utente (UPN) non distingueva più tra maiuscole e minuscole, causando la visualizzazione di un numero inferiore di errori durante l'uso dei file in SharePoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-1363">Fixed an issue Word/Excel/PowerPoint where the User Principal Name (UPN) is no longer case sensitive resulting in less failures when working with files on SharePoint.</span></span>

- <span data-ttu-id="525c8-1364">È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.</span><span class="sxs-lookup"><span data-stu-id="525c8-1364">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>


[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2002-march-05"></a><span data-ttu-id="525c8-1366">Versione 2002: 5 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1366">Version 2002: March 05</span></span>
<span data-ttu-id="525c8-1367">*Versione 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1367">*Version 2002 (Build 12527.20278)*</span></span>

- <span data-ttu-id="525c8-1368">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1368">Various bugs and performance fixes.</span></span>


## <a name="version-2002-march-04"></a><span data-ttu-id="525c8-1369">Versione 2002: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1369">Version 2002: March 04</span></span>
<span data-ttu-id="525c8-1370">*Versione 2002 (Build 12527.20264)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1370">*Version 2002 (Build 12527.20264)*</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1372">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1372">Resolved issues</span></span>

### <a name="project"></a><span data-ttu-id="525c8-1373">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1373">Project</span></span>
- <span data-ttu-id="525c8-1374">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1374">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-1375">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1375">Office Suite</span></span>
- <span data-ttu-id="525c8-1376">È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.</span><span class="sxs-lookup"><span data-stu-id="525c8-1376">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="525c8-1378">Versione 2002: 1 marzo</span><span class="sxs-lookup"><span data-stu-id="525c8-1378">Version 2002: March 01</span></span>
<span data-ttu-id="525c8-1379">*Versione 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1379">*Version 2002 (Build 12527.20242)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1380">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1380">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1381">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1381">Outlook</span></span>

- <span data-ttu-id="525c8-1382">È stato risolto un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="525c8-1382">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-24"></a><span data-ttu-id="525c8-1384">Versione 2002: 24 febbraio</span><span class="sxs-lookup"><span data-stu-id="525c8-1384">Version 2002: February 24</span></span>
<span data-ttu-id="525c8-1385">*Versione 2002 (Build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1385">*Version 2002 (Build 12527.20194)*</span></span>

- <span data-ttu-id="525c8-1386">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1386">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-22"></a><span data-ttu-id="525c8-1387">Versione 2002: 22 febbraio</span><span class="sxs-lookup"><span data-stu-id="525c8-1387">Version 2002: February 22</span></span>
<span data-ttu-id="525c8-1388">*Versione 2002 (Build 12527.20186)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1388">*Version 2002 (Build 12527.20186)*</span></span>

- <span data-ttu-id="525c8-1389">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1389">Various bugs and performance fixes.</span></span>

## <a name="version-2002-february-21"></a><span data-ttu-id="525c8-1390">Versione 2002: 21 febbraio</span><span class="sxs-lookup"><span data-stu-id="525c8-1390">Version 2002: February 21</span></span>
<span data-ttu-id="525c8-1391">*Versione 2002 (Build 12527.20174)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1391">*Version 2002 (Build 12527.20174)*</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1393">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1393">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="525c8-1394">Accesso</span><span class="sxs-lookup"><span data-stu-id="525c8-1394">Access</span></span>

- <span data-ttu-id="525c8-1395">**Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla.</span><span class="sxs-lookup"><span data-stu-id="525c8-1395">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="525c8-1396">Cercare e sostituire il testo nella visualizzazione SQL.</span><span class="sxs-lookup"><span data-stu-id="525c8-1396">Search and replace text in SQL View.</span></span> <span data-ttu-id="525c8-1397">Selezionare più tabelle nella finestra Relazioni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1397">Select multiple tables in the Relationships window.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1398">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1398">Outlook</span></span>

- <span data-ttu-id="525c8-1399">**Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web?</span><span class="sxs-lookup"><span data-stu-id="525c8-1399">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="525c8-1400">Outlook ora consente di rimanere connessi in scenari di questo tipo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1400">Outlook now detects this and helps you get connected.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1403">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1403">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="525c8-1404">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1404">Excel</span></span>

- <div style="box-sizing:border-box;"><span data-ttu-id="525c8-1405">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto..&nbsp;<span style="display:inline !important;"></span></span><span class="sxs-lookup"><span data-stu-id="525c8-1405">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.&nbsp;<span style="display:inline !important;"></span></span></span><br>


### <a name="outlook"></a><span data-ttu-id="525c8-1406">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1406">Outlook</span></span>

- <span data-ttu-id="525c8-1407">Risolto un problema per cui la virgola nel campo Luogo della riunione cambiava in punto e virgola.</span><span class="sxs-lookup"><span data-stu-id="525c8-1407">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>


- <span data-ttu-id="525c8-1408">Risolto un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.</span><span class="sxs-lookup"><span data-stu-id="525c8-1408">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>


- <span data-ttu-id="525c8-1409">Risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="525c8-1409">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.&nbsp;</span></span>


- <span data-ttu-id="525c8-1410">Risolto un problema per cui gli utenti con il tema Nero visualizzavano l'elenco a discesa &quot;Da&quot; con il testo bianco su sfondo bianco.</span><span class="sxs-lookup"><span data-stu-id="525c8-1410">Addresses an issue that caused users with Black Theme to see the &quot;From&quot; dropdown show white text on a white background.</span></span>


- <span data-ttu-id="525c8-1411"><span style="display:inline !important;">Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.</span></span><span class="sxs-lookup"><span data-stu-id="525c8-1411"><span style="display:inline !important;">This change restores the ability to view multi-line subjects in the message header.</span></span></span><br>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-18"></a><span data-ttu-id="525c8-1413">Versione 2002: 18 febbraio</span><span class="sxs-lookup"><span data-stu-id="525c8-1413">Version 2002: February 18</span></span>
<span data-ttu-id="525c8-1414">*Versione 2002 (Build 12527.20138)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1414">*Version 2002 (Build 12527.20138)*</span></span>

## <a name="version-2002-february-11"></a><span data-ttu-id="525c8-1415">Versione 2002: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="525c8-1415">Version 2002: February 11</span></span>
<span data-ttu-id="525c8-1416">*Versione 2002 (Build 12527.20092)*</span><span class="sxs-lookup"><span data-stu-id="525c8-1416">*Version 2002 (Build 12527.20092)*</span></span>

<span data-ttu-id="525c8-1417">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="525c8-1417">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="525c8-1419">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="525c8-1419">Feature updates</span></span>
### <a name="outlook"></a><span data-ttu-id="525c8-1420">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1420">Outlook</span></span>

- <span data-ttu-id="525c8-1421">**Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1421">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="525c8-1422">I messaggi trascinati verranno condivisi con tutti i membri del gruppo.</span><span class="sxs-lookup"><span data-stu-id="525c8-1422">Messages you drag will be shared with all group members.</span></span>

### <a name="word"></a><span data-ttu-id="525c8-1423">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1423">Word</span></span>

- <span data-ttu-id="525c8-1424">**Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.</span><span class="sxs-lookup"><span data-stu-id="525c8-1424">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="525c8-1425">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1425">Office Suite</span></span>

- <span data-ttu-id="525c8-1426">**Icone delle barre di stato più chiare:** ora le icone della barra di stato sono più facili da vedere.</span><span class="sxs-lookup"><span data-stu-id="525c8-1426">**Clearer status bar icons:** Status bar icons are now easier to see.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="525c8-1429">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="525c8-1429">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="525c8-1430">Access</span><span class="sxs-lookup"><span data-stu-id="525c8-1430">Access</span></span>

- <span data-ttu-id="525c8-1431">I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database.</span><span class="sxs-lookup"><span data-stu-id="525c8-1431">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="525c8-1432">Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.</span><span class="sxs-lookup"><span data-stu-id="525c8-1432">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="525c8-1433">Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB.</span><span class="sxs-lookup"><span data-stu-id="525c8-1433">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="525c8-1434">L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.</span><span class="sxs-lookup"><span data-stu-id="525c8-1434">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="525c8-1435">Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="525c8-1435">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="525c8-1436">Excel</span><span class="sxs-lookup"><span data-stu-id="525c8-1436">Excel</span></span>

- <span data-ttu-id="525c8-1437">È stato risolto un problema i comandi di commento nel menu di scelta rapida non venivano visualizzati.</span><span class="sxs-lookup"><span data-stu-id="525c8-1437">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>


- <span data-ttu-id="525c8-1438">È stato risolto un problema che causava arresti anomali convertendo il testo in colonne con celle con una matrice con espansione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1438">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


- <span data-ttu-id="525c8-1439">È stato risolto un problema relativo all'arresto anomalo di Excel quando si usa Testo in colonne con matrici dinamiche.</span><span class="sxs-lookup"><span data-stu-id="525c8-1439">Fixed an issue where Excel would crash when using Text To Columns with dynamic arrays.</span></span>

### <a name="outlook"></a><span data-ttu-id="525c8-1440">Outlook</span><span class="sxs-lookup"><span data-stu-id="525c8-1440">Outlook</span></span>

- <span data-ttu-id="525c8-1441">È stato risolto un problema per cui scorrendo il calendario con la visualizzazione per mese, non è possibile visualizzare gli eventi del calendario precedente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1441">Fixed an issue where scrolling in calendar with month view, fails to show previous calendar events.</span></span>

- <span data-ttu-id="525c8-1442">Le cartelle salvate in "Preferiti" nel riquadro di spostamento a sinistra scomparivano in modo intermittente.</span><span class="sxs-lookup"><span data-stu-id="525c8-1442">Folders saved in 'Favorites' in the left navigation pane may intermittently disappear.</span></span>


- <span data-ttu-id="525c8-1443">È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="525c8-1443">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="525c8-1444">È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.</span><span class="sxs-lookup"><span data-stu-id="525c8-1444">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="525c8-1445">È stato risolto un problema che causava un arresto anomalo annullando la configurazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="525c8-1445">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>


- <span data-ttu-id="525c8-1446">È stato risolto un problema per cui i messaggi di posta elettronica in scadenza in base ai criteri di conservazione visualizzavano due etichette.</span><span class="sxs-lookup"><span data-stu-id="525c8-1446">Fixed an issue where emails expiring based on a retention policy would display two labels.</span></span> <span data-ttu-id="525c8-1447">Una indicava che la posta sarebbe scaduta entro un giorno e l'altra entro due giorni.</span><span class="sxs-lookup"><span data-stu-id="525c8-1447">One showing that the mail will expire in one day and another displaying that it will expire in two days.</span></span>


- <span data-ttu-id="525c8-1448">È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="525c8-1448">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="525c8-1449">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="525c8-1449">PowerPoint</span></span>

- <span data-ttu-id="525c8-1450">È stato risolto un problema per cui l'input penna non era corretto o non veniva eseguito durante le animazioni dell'input penna di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-1450">Fixed an issue where Ink may not render completely or get skipped when used in a PowerPoint ink animations.</span></span>

- <span data-ttu-id="525c8-1451">È stato risolto un problema per cui, dopo aver chiuso un file, PowerPoint non lo rimuove immediatamente dalla raccolta presentazioni se sono in esecuzione gestori di eventi.</span><span class="sxs-lookup"><span data-stu-id="525c8-1451">Fixed an issue where After closing a file, PowerPoint does not immediately remove it from the Presentations collection if there are any event handlers running.</span></span> <span data-ttu-id="525c8-1452">Di conseguenza, il numero di presentazioni aperte riportate dal modello a oggetti non è corretto e viene impedita la chiusura di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="525c8-1452">Hence the number of open presentations reported by the object model is incorrect, and shutdown of PowerPoint is prevented.</span></span>


- <span data-ttu-id="525c8-1453">È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.</span><span class="sxs-lookup"><span data-stu-id="525c8-1453">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>


### <a name="project"></a><span data-ttu-id="525c8-1454">Project</span><span class="sxs-lookup"><span data-stu-id="525c8-1454">Project</span></span>

- <span data-ttu-id="525c8-1455">È stato risolto un problema per cui il 100% delle attività di tipo durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.</span><span class="sxs-lookup"><span data-stu-id="525c8-1455">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="525c8-1456">Word</span><span class="sxs-lookup"><span data-stu-id="525c8-1456">Word</span></span>

- <span data-ttu-id="525c8-1457">L'aggiornamento e lo scorrimento di un sommario possono talvolta visualizzare un'area grigia sul documento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1457">Updating and scrolling through a table of contents may sometimes display a gray area over the document.</span></span>


- <span data-ttu-id="525c8-1458">È stato risolto un problema per cui l'utilizzo di "Sfoglia" per salvare un file non funzionava se un commento veniva scritto ma non pubblicato e l'utente provava a salvare il file.</span><span class="sxs-lookup"><span data-stu-id="525c8-1458">Fixed an issue where using 'Browse' to save a file did not work if a comment was written but not posted and the user tried to save the file.</span></span>


- <span data-ttu-id="525c8-1459">È stato risolto un problema per cui, quando ci si spostava tra le schede commento, talvolta il commento inizialmente selezionato veniva visualizzato con un'evidenziazione della selezione.</span><span class="sxs-lookup"><span data-stu-id="525c8-1459">Fixed an issue where going back and forth between comment cards would sometimes display the initially selected comment with a selection highlight.</span></span>


- <span data-ttu-id="525c8-1460">È stato risolto un problema per cui la formattazione in corsivo veniva persa dopo aver modificato un commento, applicato il corsivo al testo e postato il commento.</span><span class="sxs-lookup"><span data-stu-id="525c8-1460">Fixed an issue where italics formatting is lost after editing a comment, italicizing the text and then posting it.</span></span>


- <span data-ttu-id="525c8-1461">È stato risolto un problema per cui l'indicatore del commento non era visibile in modalità di lettura con colore di pagina Inverso.</span><span class="sxs-lookup"><span data-stu-id="525c8-1461">Fixed an issue where comment hint was not visible in read mode with Inverse page color.</span></span>


- <span data-ttu-id="525c8-1462">È stato risolto un problema per cui, se un documento è stato creato in modo condiviso, la versione bozza di un commento radice potrebbe non essere mantenuta.</span><span class="sxs-lookup"><span data-stu-id="525c8-1462">Fixed an issue where if a document is being coauthored, the draft version of a root comment may not be preserved.</span></span>


- <span data-ttu-id="525c8-1463">Con SlideTrack abilitato e il riquadro commenti chiuso, CTRL + ALT + M potrebbe non aprire il riquadro commenti.</span><span class="sxs-lookup"><span data-stu-id="525c8-1463">With SlideTrack enabled and the comments pane closed, Ctrl+Alt+M may not open the comments pane.</span></span>


- <span data-ttu-id="525c8-1464">È stato risolto un problema per cui quando si aggiungeva una @menzione in una tabella poteva venire generato il messaggio di errore: "una tabella in questo documento è stata danneggiata".</span><span class="sxs-lookup"><span data-stu-id="525c8-1464">Fixed an issue when adding @mention in a table could generate the error message: 'A table in this document has become corrupted'.</span></span>


- <span data-ttu-id="525c8-1465">È stato risolto un problema per cui nel menu di scelta rapida dei commenti non venivano visualizzati i comandi per i commenti (Modifica commento, Rispondi a commento, Elimina commento, Risolvi commento).</span><span class="sxs-lookup"><span data-stu-id="525c8-1465">Fixed an issue where comment commands (Edit comment, Reply to comment, Delete comment, Resolve comment) in the comments context menu were not being displayed.</span></span>


### <a name="office-suite"></a><span data-ttu-id="525c8-1466">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="525c8-1466">Office Suite</span></span>

- <span data-ttu-id="525c8-1467">È stato risolto un problema che potrebbe aver causato l'installazione errata del pacchetto di strumenti di correzione norvegese Nynorsk (nn-no).</span><span class="sxs-lookup"><span data-stu-id="525c8-1467">Resolves an issue that may have caused Norway Nynorsk (nn-no) proofing tools package to be installed incorrectly.</span></span>


- <span data-ttu-id="525c8-1468">Questo cambiamento affronta i problemi segnalati con le schede grafiche che utilizzano le GPU integrate Intel.</span><span class="sxs-lookup"><span data-stu-id="525c8-1468">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

