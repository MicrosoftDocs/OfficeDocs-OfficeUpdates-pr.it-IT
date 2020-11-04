---
title: Note sulla versione per i rilasci del Canale corrente nel 2020
ms.author: anankani
author: anankani
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per professionisti IT con le note sulle versioni per i rilasci del Canale mensile per Microsoft 365 Apps nel 2020
ms.openlocfilehash: d47124846cd605174e6ca23e26cd0e61bb5cf779
ms.sourcegitcommit: d03cdba884e24c4122db59bd06176ae5273d16e4
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/04/2020
ms.locfileid: "48878920"
---
# <a name="release-notes-for-current-channel-releases-in-2020"></a><span data-ttu-id="f89c9-103">Note sulla versione per i rilasci del Canale corrente nel 2020</span><span class="sxs-lookup"><span data-stu-id="f89c9-103">Release notes for Current Channel releases in 2020</span></span>

<span data-ttu-id="f89c9-104">Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale corrente (mirato) nel 2020 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-104">These release notes provide information about new features and non-security updates that are included in Current Channel updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="f89c9-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="f89c9-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

 > [!NOTE]
>
>- <span data-ttu-id="f89c9-107">Spesso distribuiamo le funzionalità (e a volte anche le correzioni) quando sono correnti per un periodo di tempo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-107">We often roll out features (and sometimes even fixes) to Current over a period of time.</span></span>  <span data-ttu-id="f89c9-108">Se non si vede subito un elemento descritto di seguito, è possibile aspettarselo al più presto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-108">If you don’t see something described below right away, you can expect it soon.</span></span> [<span data-ttu-id="f89c9-109">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-109">Learn more</span></span>](https://support.office.com/article/when-do-i-get-the-newest-features-in-for-office-365-da36192c-58b9-4bc9-8d51-bb6eed468516)
>- <span data-ttu-id="f89c9-110">Le funzionalità di Microsoft Teams potrebbero essere diverse da quelle rilasciate dall'ultima versione corrente, in quanto hanno una cadenza di rilascio più frequente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-110">Microsoft Teams features may differ from the latest Current Channel released as they have a more frequent release cadence.</span></span>




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2010-october-27"></a><span data-ttu-id="f89c9-113">Versione 2010: 27 ottobre</span><span class="sxs-lookup"><span data-stu-id="f89c9-113">Version 2010: October 27</span></span>
<span data-ttu-id="f89c9-114">*Versione 2010 (Build 13328.20292)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-114">*Version 2010 (Build 13328.20292)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-116">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-116">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-117">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-117">Access</span></span>

- <span data-ttu-id="f89c9-118">**Rimani al passo con i tempi! La tipologia di dati con data/ora estesa offre una maggiore precisione:** introducendo un tipo di dati nuovo e migliorato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-118">**Keep up with the times! The Date/Time Extended data type has better precision.:** Introducing a new and improved data type.</span></span> <span data-ttu-id="f89c9-119">Per migliorare la compatibilità della sintassi con SQL e per aumentare l'accuratezza e il livello di dettaglio nei record che includono date e ore, il tipo di dati DateTime2 viene implementato in Access.</span><span class="sxs-lookup"><span data-stu-id="f89c9-119">To enhance syntax compatibility with SQL, and to increase accuracy and level of detail in records that include dates and times, we’re implementing the DateTime2 data type into Access.</span></span> <span data-ttu-id="f89c9-120">Questa tipologia aggiuntiva di dati data/ora includerà un intervallo di date più ampio (da 0001-01-01 a 9999-12-31), con precisione temporale più specifica (nanosecondi, anziché secondi), per cui sarà possibile fornire ed eseguire calcoli.</span><span class="sxs-lookup"><span data-stu-id="f89c9-120">This additional date & time data type will include a larger date range (0001-01-01 through 9999-12-31), with higher-specified time precision (nanoseconds, rather than seconds) that you will be able to provide and perform calculations on.</span></span> <span data-ttu-id="f89c9-121">Per abilitare, selezionare Nuovo campo > Data e ora estesa.</span><span class="sxs-lookup"><span data-stu-id="f89c9-121">To enable, select New field > Date & Time Extended.</span></span> [<span data-ttu-id="f89c9-122">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-122">Learn more</span></span>](https://support.office.com/article/708c32da-a052-4cc2-9850-9851042e0024)

### <a name="excel"></a><span data-ttu-id="f89c9-123">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-123">Excel</span></span>

- <span data-ttu-id="f89c9-124">**Creare tipi di dati con Power Query:** è possibile creare tipi di dati complessi con Power Query da qualsiasi origine dati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-124">**Create Data Types with Power Query:** Create rich data types with Power Query from any data source.</span></span> [<span data-ttu-id="f89c9-125">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-125">Learn more</span></span>](https://support.office.com/article/a465a3b7-3d37-4eb1-a59c-bd3163315308)<br /><span data-ttu-id="f89c9-126">Vedere i dettagli nel [post di blog](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span><span class="sxs-lookup"><span data-stu-id="f89c9-126">See details in [blog post](https://techcommunity.microsoft.com/t5/excel-blog/announcing-power-query-data-types/ba-p/1782903)</span></span>

- <span data-ttu-id="f89c9-127">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-127">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="f89c9-128">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-128">No conversion required.</span></span><br /><span data-ttu-id="f89c9-129">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="f89c9-129">See details in [blog post](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="f89c9-130">**Apportare modifiche rapide con la penna azione:** la penna azione consente di scrivere a mano direttamente nelle celle, annotando con l'input penna dati che verranno convertiti automaticamente in dati di Excel.</span><span class="sxs-lookup"><span data-stu-id="f89c9-130">**Make quick edits using the action pen:** With the action pen, you can write by hand directly in the cells, jot down data with ink that gets automatically converted to Excel data.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-131">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-131">Outlook</span></span>

- <span data-ttu-id="f89c9-132">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-132">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="f89c9-133">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-133">No conversion required.</span></span><br /><span data-ttu-id="f89c9-134">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="f89c9-134">See details in [blog post](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span></span>

- <span data-ttu-id="f89c9-135">**Il controllo grammaticale è tornato:** Outlook contrassegna gli errori grammaticali durante la digitazione e l'utente può applicare i suggerimenti con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="f89c9-135">**Grammar checking's got your back:** Outlook marks grammar errors as you type, so you can apply suggestions with a single click.</span></span> [<span data-ttu-id="f89c9-136">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-136">Learn more</span></span>](https://support.office.com/article/ddbadc42-4637-451d-b3f4-ecf295036fa9)<br /><span data-ttu-id="f89c9-137">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/grammar-and-style-suggestions-available-in-outlook)</span><span class="sxs-lookup"><span data-stu-id="f89c9-137">See details in [blog post](https://insider.office.com/it-IT/blog/grammar-and-style-suggestions-available-in-outlook)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-138">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-138">PowerPoint</span></span>

- <span data-ttu-id="f89c9-139">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-139">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="f89c9-140">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-140">No conversion required.</span></span><br /><span data-ttu-id="f89c9-141">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="f89c9-141">See details in [blog post](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span></span>

### <a name="teams"></a><span data-ttu-id="f89c9-142">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-142">Teams</span></span>

- <span data-ttu-id="f89c9-143">**Modelli in Microsoft Teams:** l'ampia varietà di modelli personalizzabili velocizza la creazione dei nuovi team.</span><span class="sxs-lookup"><span data-stu-id="f89c9-143">**Templates in Microsoft Teams:** With Templates in Teams, users can choose from a variety of customizable templates when creating a new team, helping them get started quickly.</span></span> <span data-ttu-id="f89c9-144">I professionisti IT possono anche creare nuovi modelli personalizzati per la propria organizzazione, in modo da standardizzare le strutture dei team, evidenziare le app pertinenti e applicare le procedure consigliate.</span><span class="sxs-lookup"><span data-stu-id="f89c9-144">IT professionals can also create new custom templates for their organization, allowing them to standardize team structures, surface relevant apps, and scale best practices.</span></span>

- <span data-ttu-id="f89c9-145">**Post fissati:** questa funzionalità consente agli utenti di fissare qualsiasi messaggio di un canale al riquadro informazioni del canale per porlo in evidenza.</span><span class="sxs-lookup"><span data-stu-id="f89c9-145">**Pinned Posts:** This feature allows users to "pin" any message in a channel to the channel info pane for all members of the channel to see.</span></span> <span data-ttu-id="f89c9-146">Tutti i membri che hanno accesso al canale potranno vedere i messaggi fissati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-146">Any members who have access to the channel will be able to see pinned messages.</span></span> <span data-ttu-id="f89c9-147">Tutti i membri di un canale potranno fissare qualsiasi messaggio, a meno che la funzionalità non sia disattivata tramite le impostazioni di moderazione del canale stesso.</span><span class="sxs-lookup"><span data-stu-id="f89c9-147">Any member of a channel will be able to pin any message (unless turned off via channel moderation settings).</span></span>

- <span data-ttu-id="f89c9-148">**Invio al catalogo delle app:** nell'angolo in basso a sinistra dello schermo ora è presente un collegamento Invia al catalogo app.</span><span class="sxs-lookup"><span data-stu-id="f89c9-148">**Submit to app catalog:** You’ll see a Submit to app catalog link on the lower left of this screen.</span></span> <span data-ttu-id="f89c9-149">Si tratta di un altro punto da cui è possibile inviare app per l'approvazione in aggiunta a Visual Studio e App Studio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-149">In addition to App Studio and Visual Studio, it’s another place where you can submit apps for approval.</span></span>

- <span data-ttu-id="f89c9-150">**Usare FreeHand di Invision verso lavagna nell'esperienza di riunione spuntata:** ora è possibile usare l'app FreeHand di Invision per aprire una lavagna in qualsiasi riunione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-150">**Use Freehand by Invision to whiteboard in the popped out meeting experience:** You can now use the Freehand by Invision app to whiteboard in any meeting you take in the popped out meeting experience.</span></span> <span data-ttu-id="f89c9-151">Iniziare il brainstorming è facile, selezionando l'app FreeHand dal pannello di condivisione del contenuto, installandola e avviando la sessione di lavagna con i colleghi.</span><span class="sxs-lookup"><span data-stu-id="f89c9-151">Seamlessly start brainstorming by selecting the Freehand app from the share content tray and, installing it, and starting the whiteboarding session with your colleagues!</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-152">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-152">Word</span></span>

- <span data-ttu-id="f89c9-153">**Inserire le foto dell'iPhone direttamente in Office:** le immagini HEIC ora si inseriscono facilmente dal proprio telefono in Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-153">**Insert your iPhone photos directly into Office:** HEIC pictures from your phone now insert seamlessly into Office.</span></span> <span data-ttu-id="f89c9-154">Non è richiesta alcuna conversione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-154">No conversion required.</span></span><br /><span data-ttu-id="f89c9-155">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span><span class="sxs-lookup"><span data-stu-id="f89c9-155">See details in [blog post](https://insider.office.com/it-IT/blog/insert-apple-photos-into-office-easily)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-158">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-158">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-159">Accesso</span><span class="sxs-lookup"><span data-stu-id="f89c9-159">Access</span></span>

- <span data-ttu-id="f89c9-160">È stato risolto un problema per cui l'uso di DAO da applicazioni non di Office causava la chiusura imprevista dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-160">We fixed an issue when using DAO from non-Office applications would cause the application to close unexpectedly.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-161">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-161">Outlook</span></span>

- <span data-ttu-id="f89c9-162">È stato risolto un problema per cui le intestazioni dei messaggi in cinese erano illeggibili in caso di risposta o inoltro.</span><span class="sxs-lookup"><span data-stu-id="f89c9-162">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


- <span data-ttu-id="f89c9-163">È stato risolto un problema per cui, salvando in formato OTF, i caratteri in cinese venivano trasformati in punti interrogativi.</span><span class="sxs-lookup"><span data-stu-id="f89c9-163">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="f89c9-164">È stato risolto un problema che causava la creazione da parte di Outlook di una firma vuota secondaria per gli utenti che avevano abilitato le impostazioni cloud.</span><span class="sxs-lookup"><span data-stu-id="f89c9-164">We fixed an issue that caused Outlook to create a second empty signature for people who had cloud settings enabled.</span></span>


- <span data-ttu-id="f89c9-165">È stato risolto un problema per cui le impostazioni cloud non risultavano attivate per gli utenti per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="f89c9-165">We fixed a n issue that caused Cloud Settings not to be turned on for users by default.</span></span>


- <span data-ttu-id="f89c9-166">È stato risolto un problema per cui le modifiche alla firma di un utente non venivano salvate.</span><span class="sxs-lookup"><span data-stu-id="f89c9-166">We fixed an issue that caused changes to a user's signature to fail to save.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-167">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-167">PowerPoint</span></span>

- <span data-ttu-id="f89c9-168">Si tratta della correzione di un problema che causava la visualizzazione della richiesta di salvataggio a ciclo continuo durante la chiusura di un documento se era presente un componente aggiuntivo per l’ascolto dell’evento PresentationBeforeClose e il controllo della proprietà Presentation.Saved come parte del gestore dell'evento.</span><span class="sxs-lookup"><span data-stu-id="f89c9-168">This is a fix for an issue where the save prompt shows in a loop when closing the document when there is an add-in that listens to PresentationBeforeClose event and checks Presentation.Saved property as a part of the event handler.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-169">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-169">Project</span></span>

- <span data-ttu-id="f89c9-170">È stato risolto un problema per cui, salvando un progetto da PWA a un file MPP locale, veniva generato l'evento ProjectBeforeTaskChangeEvent per dati che in realtà l'utente non aveva modificato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-170">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="f89c9-171">È stato risolto un problema per cui Project poteva chiudersi in modo imprevisto all'apertura di file in cui i profili delle risorse erano specificati in un certo modo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-171">Fixed an issue where Project may terminate unexpectedly when opening files where resource contours were specified in a certain manner.</span></span>


- <span data-ttu-id="f89c9-172">È stato risolto un problema per cui, salvando un progetto da PWA a un file MPP locale, veniva generato l'evento ProjectBeforeTaskChangeEvent per dati che in realtà l'utente non aveva modificato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-172">Fixed an issue where when you save a project from PWA to a local mpp file, the ProjectBeforeTaskChangeEvent fires for data that wasn't actually changed by the user.</span></span>


- <span data-ttu-id="f89c9-173">È stato risolto un problema per cui il valore di NewVal nell'evento ProjectBeforeTaskChange non aveva il valore corretto modificando un intervallo all'interno di una visualizzazione Maschera attività - Tipo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-173">Fixed an issue where the NewVal in the ProjectBeforeTaskChange event doesn't have the correct value if a lag is changed within a Task Form type view.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-174">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-174">Office Suite</span></span>

- <span data-ttu-id="f89c9-175">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="f89c9-175">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="f89c9-176">I messaggi sono stati modificati in "Toner o inchiostro insufficiente" e "Toner o inchiostro esaurito".</span><span class="sxs-lookup"><span data-stu-id="f89c9-176">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>

- <span data-ttu-id="f89c9-177">È stato risolto un problema per i clienti commerciali che usano System Center Configuration Manager o altri strumenti di gestione per l'aggiornamento di Office tramite Prevenzione della perdita di dati degli endpoint di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="f89c9-177">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-21"></a><span data-ttu-id="f89c9-179">Versione 2009: 21 ottobre</span><span class="sxs-lookup"><span data-stu-id="f89c9-179">Version 2009: October 21</span></span>
<span data-ttu-id="f89c9-180">*Versione 2009 (Build 13231.20418)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-180">*Version 2009 (Build 13231.20418)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-182">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-182">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f89c9-183">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-183">Outlook</span></span>

- <span data-ttu-id="f89c9-184">È stato risolto un problema che impediva agli utenti di concedere le autorizzazioni di Editor ai delegati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-184">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="f89c9-185">È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto se gli utenti selezionavano un risultato della ricerca.</span><span class="sxs-lookup"><span data-stu-id="f89c9-185">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="f89c9-186">È stato risolto un problema per cui le intestazioni dei messaggi in cinese erano illeggibili in caso di risposta o inoltro.</span><span class="sxs-lookup"><span data-stu-id="f89c9-186">We fixed an issue that caused the headers of Chinese messages to be unreadable when replying or forwarding.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-187">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-187">PowerPoint</span></span>

- <span data-ttu-id="f89c9-188">È stato risolto un problema per cui il componente aggiuntivo per i contenuti Forms non veniva eseguito dopo l'inserimento finché l'utente non faceva clic su un'altra diapositiva per visualizzarlo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-188">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>



[//]: # (NON RIMUOVERE FINE DE CONTENUTO DEI BUG)

## <a name="version-2009-october-13"></a><span data-ttu-id="f89c9-190">Versione 2009: 13 ottobre</span><span class="sxs-lookup"><span data-stu-id="f89c9-190">Version 2009: October 13</span></span>
<span data-ttu-id="f89c9-191">*Versione 2009 (Build 13231.20390)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-191">*Version 2009 (Build 13231.20390)*</span></span>

<span data-ttu-id="f89c9-192">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-192">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-194">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-194">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="f89c9-195">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-195">Project</span></span>

- <span data-ttu-id="f89c9-196">È stato risolto un problema per cui Project poteva bloccarsi all'apertura di file in cui i profili delle risorse erano specificati in un certo modo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-196">Fixed an issue where Project may crash on opening files where resource contours were specified in a certain manner.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-october-08"></a><span data-ttu-id="f89c9-198">Versione 2009: 8 ottobre</span><span class="sxs-lookup"><span data-stu-id="f89c9-198">Version 2009: October 08</span></span>
<span data-ttu-id="f89c9-199">*Versione 2009 (Build 13231.20368)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-199">*Version 2009 (Build 13231.20368)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-201">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-201">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f89c9-202">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-202">Outlook</span></span>

- <span data-ttu-id="f89c9-203">Risolve un problema che impediva di restituire i risultati delle ricerche eseguite su calendari condivisi con memorizzati nella cache.</span><span class="sxs-lookup"><span data-stu-id="f89c9-203">Addresses an issue that caused Search to return no results when searching uncached shared calendars.</span></span>


- <span data-ttu-id="f89c9-204">Risolve un problema che causava, in certe circostanze, l'avvio inatteso di Outlook in modalità offline.</span><span class="sxs-lookup"><span data-stu-id="f89c9-204">Addresses an issue that caused some users to observe Outlook unexpectedly starting in an offline state.</span></span>


- <span data-ttu-id="f89c9-205">Risolve un problema che provocava errori intermittenti quando i delegati aprivano cartelle condivise in altre cassette postali.</span><span class="sxs-lookup"><span data-stu-id="f89c9-205">Addresses an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-206">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-206">PowerPoint</span></span>

- <span data-ttu-id="f89c9-207">Correzione di sicurezza che risolve un problema che disabilitava le protezioni IRM quando si apriva un file PowerPoint nella modalità Visualizzazione protetta.</span><span class="sxs-lookup"><span data-stu-id="f89c9-207">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-208">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-208">Office Suite</span></span>

- <span data-ttu-id="f89c9-209">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="f89c9-209">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="f89c9-210">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="f89c9-210">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2009-september-28"></a><span data-ttu-id="f89c9-212">Versione 2009: 28 settembre</span><span class="sxs-lookup"><span data-stu-id="f89c9-212">Version 2009: September 28</span></span>
<span data-ttu-id="f89c9-213">*Versione 2009 (Build 13231.20262)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-213">*Version 2009 (Build 13231.20262)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-215">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-215">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-216">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-216">Excel</span></span>

- <span data-ttu-id="f89c9-217">**Salvataggio delle forme come immagini:** con pochi clic del mouse è possibile salvare una forma, un'icona o un altro oggetto come file di immagine, così da poterlo riutilizzare altrove.</span><span class="sxs-lookup"><span data-stu-id="f89c9-217">**Save shapes as pictures:** In just a few clicks, save a shape, icon, or other object as a picture file so you can reuse it elsewhere.</span></span> [<span data-ttu-id="f89c9-218">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-218">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="f89c9-219">**Accedere ai dati dell'organizzazione da Power BI usando i tipi di dati:** i tipi di dati di Excel di Power BI sono ora distribuiti ai partecipanti al programma Office Insider nelle organizzazioni con Office 365 E5/A5 o Microsoft 365 E5/A5.</span><span class="sxs-lookup"><span data-stu-id="f89c9-219">**Get Organization Data from Power BI using Data Types:** Excel data types from Power BI are now rolling out to Insiders in organizations with Office 365 E5/A5 or Microsoft 365 E5/A5.</span></span> <span data-ttu-id="f89c9-220">Ottenere le informazioni necessarie e aggiornarle con facilità è fondamentale per molti flussi di lavoro quotidiani.</span><span class="sxs-lookup"><span data-stu-id="f89c9-220">Getting the information you need and easily refreshing it is critical to many everyday workflows.</span></span> <span data-ttu-id="f89c9-221">In Excel è possibile accedere alle informazioni della società o dell'organizzazione da Power BI come tipo di dati, in modo da espandere la tua capacità di inserire informazioni collegate nei fogli di calcolo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-221">We’re giving you access to your company or organization information from Power BI as a data type in Excel, which expands your ability to bring in linked information in your spreadsheets.</span></span> [<span data-ttu-id="f89c9-222">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-222">Learn more</span></span>](https://support.office.com/article/cd8938ce-f963-444d-b82a-7140848241e9)<br /><span data-ttu-id="f89c9-223">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-223">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="f89c9-224">**Creare variabili da usare nelle formule:** migliorare le prestazioni, la leggibilità e la compatibilità con la funzione LET.</span><span class="sxs-lookup"><span data-stu-id="f89c9-224">**Create variables to use in formulas:** Improve performance, readability, and composability with the LET function.</span></span> <span data-ttu-id="f89c9-225">Questa funzione consente di creare variabili denominate nelle formule nuove o preesistenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-225">This function allows you to create named variables in new or pre-existing formulas.</span></span> [<span data-ttu-id="f89c9-226">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-226">Learn more</span></span>](https://support.office.com/article/34842dd8-b92b-4d3f-b325-b8b8f9908999)<br /><span data-ttu-id="f89c9-227">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-227">See details in [blog post](https://blog-insider.office.com/2020/06/01/let-names-in-formulas-for-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-228">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-228">Outlook</span></span>

- <span data-ttu-id="f89c9-229">**Espansione automatica della ricerca nell'archivio online:** Si può abilitare l'espansione automatica della ricerca nell'archivio online</span><span class="sxs-lookup"><span data-stu-id="f89c9-229">**Auto-Expanding Online Archive Search:** Enabling auto-expanding Online Archive Search</span></span>

- <span data-ttu-id="f89c9-230">**Nuova scheda del profilo per Outlook:** La nuova scheda del profilo di Outlook include una migliore visualizzazione Organizzazione e abbina lo stile della scheda di Outlook sul web.</span><span class="sxs-lookup"><span data-stu-id="f89c9-230">**New profile card for Outlook:** New profile card for Outlook including a better Organization view and matches the card style of Outlook Web.</span></span>

### <a name="teams"></a><span data-ttu-id="f89c9-231">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-231">Teams</span></span>

- <span data-ttu-id="f89c9-232">**Condividere file in Microsoft Teams:** [Altre informazioni](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span><span class="sxs-lookup"><span data-stu-id="f89c9-232">**Sharing files in Microsoft Teams:** [Learn more](https://docs.microsoft.com/MicrosoftTeams/sharing-files-in-teams)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-235">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-235">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f89c9-236">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-236">Outlook</span></span>

- <span data-ttu-id="f89c9-237">Risolve un problema che causa l'invio con il corpo vuoto di alcuni messaggi di posta elettronica generati automaticamente, quando la riga dell'oggetto è vuota. </span><span class="sxs-lookup"><span data-stu-id="f89c9-237">Addresses an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-238">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-238">PowerPoint</span></span>

- <span data-ttu-id="f89c9-239">È stato risolto un problema che causava il rallentamento della creazione condivisa di file contenenti un numero elevato di determinati tipi di oggetto dati (E2o).</span><span class="sxs-lookup"><span data-stu-id="f89c9-239">Fixed an issue causing slow coauthoring on files containing large numbers of a certain data object type (E2o).</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-240">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-240">Project</span></span>

- <span data-ttu-id="f89c9-241">È stato risolto un problema per cui, se si ha un codice di evento in esecuzione e si prova a modificare la visualizzazione di un modulo attività, facendo clic sul pulsante OK le modifiche potrebbero non essere inserite.</span><span class="sxs-lookup"><span data-stu-id="f89c9-241">Fixed an issue where if you have eventing code running and try to make changes through a Task Form view, clicking the OK button may not commit the changes.</span></span>


### <a name="word"></a><span data-ttu-id="f89c9-242">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-242">Word</span></span>

- <span data-ttu-id="f89c9-243">È stato risolto un problema con la finestra di dialogo raccolta Stili.</span><span class="sxs-lookup"><span data-stu-id="f89c9-243">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-244">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-244">Office Suite</span></span>

- <span data-ttu-id="f89c9-245">Questa modifica risolve un problema della funzionalità Esporta come GIF animata, per cui l'esportazione non viene eseguita quando si fa clic sul pulsante Esporta.</span><span class="sxs-lookup"><span data-stu-id="f89c9-245">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="f89c9-246">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-246">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-22"></a><span data-ttu-id="f89c9-248">Versione 2008: 22 settembre</span><span class="sxs-lookup"><span data-stu-id="f89c9-248">Version 2008: September 22</span></span>
<span data-ttu-id="f89c9-249">*Versione 2008 (Build 13127.20508)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-249">*Version 2008 (Build 13127.20508)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-251">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-251">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-252">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-252">Excel</span></span>

- <span data-ttu-id="f89c9-253">È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo quando si utilizzava l'Analisi rapida dopo aver bloccato la riga superiore del foglio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-253">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="f89c9-254">È stato risolto un problema che poteva generare un avviso su una cartella di lavoro danneggiata se conteneva formule utilizzando IFNA ().</span><span class="sxs-lookup"><span data-stu-id="f89c9-254">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-255">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-255">Outlook</span></span>

- <span data-ttu-id="f89c9-256">Risolve un problema che impediva agli utenti di chiudere i calendari condivisi facendo clic sulla "X" nell'angolo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-256">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="f89c9-257">Risolve un problema relativo alle prestazioni con il caricamento degli allegati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-257">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-258">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-258">PowerPoint</span></span>

- <span data-ttu-id="f89c9-259">È stato risolto un problema che causava l'arresto anomalo dell'app PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-259">We have fixed an issue which was causing the crash in PowerPoint app.</span></span>


### <a name="visio"></a><span data-ttu-id="f89c9-260">Visio</span><span class="sxs-lookup"><span data-stu-id="f89c9-260">Visio</span></span>

- <span data-ttu-id="f89c9-261">L'anteprima dinamica si arresta in modo anomalo sull'allineamento del testo segnalato dai clienti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-261">Live preview crashes on text alignment reported by customers.</span></span> <span data-ttu-id="f89c9-262">Arresto anomalo di maggior impatto della fork di repository di luglio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-262">Top hitting crash of July fork.</span></span>


### <a name="word"></a><span data-ttu-id="f89c9-263">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-263">Word</span></span>

- <span data-ttu-id="f89c9-264">È stato risolto un problema con la finestra di dialogo raccolta Stili.</span><span class="sxs-lookup"><span data-stu-id="f89c9-264">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-265">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-265">Office Suite</span></span>

- <span data-ttu-id="f89c9-266">Risolve l'utilizzo elevato della CPU in modalità inattiva con GIF/modelli animati 3D</span><span class="sxs-lookup"><span data-stu-id="f89c9-266">Fixes high CPU usage on idle with GIF/animated model3D</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2008-september-09"></a><span data-ttu-id="f89c9-268">Versione 2008: 9 settembre</span><span class="sxs-lookup"><span data-stu-id="f89c9-268">Version 2008: September 09</span></span>
<span data-ttu-id="f89c9-269">*Versione 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-269">*Version 2008 (Build 13127.20408)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-271">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-271">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-272">Accesso</span><span class="sxs-lookup"><span data-stu-id="f89c9-272">Access</span></span>

- <span data-ttu-id="f89c9-273">Questa modifica risolve un problema che poteva causare l'arresto anomalo di Access durante l'avvio della casella di Zoom (MAIUSC + F2) per la modifica del testo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-273">This change fixes an issue that could cause Access to crash when launching the Zoom box (Shift + F2) to edit text.</span></span>


### <a name="excel"></a><span data-ttu-id="f89c9-274">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-274">Excel</span></span>

- <span data-ttu-id="f89c9-275">È stato risolto un problema per cui Excel potrebbe arrestarsi in modo anomalo in determinate circostanze quando si usa Copia formato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-275">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>


### <a name="word"></a><span data-ttu-id="f89c9-276">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-276">Word</span></span>

- <span data-ttu-id="f89c9-277">È stato risolto un problema per cui l'utente poteva perdere il contenuto quando ridimensionava una forma.</span><span class="sxs-lookup"><span data-stu-id="f89c9-277">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="f89c9-278">È stato risolto un problema per cui gli stili di base non vengono aggiornati con lo stile normale.</span><span class="sxs-lookup"><span data-stu-id="f89c9-278">We fixed an issue which the base styles are not updated with Normal style.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-279">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-279">Office Suite</span></span>

- <span data-ttu-id="f89c9-280">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-280">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2008-august-31"></a><span data-ttu-id="f89c9-282">Versione 2008: 31 agosto</span><span class="sxs-lookup"><span data-stu-id="f89c9-282">Version 2008: August 31</span></span>
<span data-ttu-id="f89c9-283">*Versione 2008 (Build 13127.20296)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-283">*Version 2008 (Build 13127.20296)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-285">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-285">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-286">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-286">Excel</span></span>

- <span data-ttu-id="f89c9-287">**Salvare in cartelle aggiunte:** aggiungere le cartelle semplifica il salvataggio dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-287">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="f89c9-288">Abbiamo ricevuto feedback per cui gli utenti desiderano un maggiore controllo sulle cartelle disponibili per il salvataggio di un nuovo file.</span><span class="sxs-lookup"><span data-stu-id="f89c9-288">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="f89c9-289">Siamo entusiasti di offrirti una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva.</span><span class="sxs-lookup"><span data-stu-id="f89c9-289">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="f89c9-290">Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-290">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="f89c9-291">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-291">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="f89c9-292">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-292">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-293">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-293">Outlook</span></span>

- <span data-ttu-id="f89c9-294">**Collegamenti migliorati nei messaggi di posta elettronica:** quando si include un collegamento a un file, il nome del file sostituisce l'URL.</span><span class="sxs-lookup"><span data-stu-id="f89c9-294">**Improved links in email:** When you include a link to a file, the file name replaces the URL.</span></span> <span data-ttu-id="f89c9-295">È possibile modificare le autorizzazioni per consentire l'accesso a tutti i destinatari.</span><span class="sxs-lookup"><span data-stu-id="f89c9-295">You can change permissions so all recipients have access.</span></span> [<span data-ttu-id="f89c9-296">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-296">Learn more</span></span>](https://support.office.com/article/02040f47-bd56-4806-8311-fc913fed54c0)<br /><span data-ttu-id="f89c9-297">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-297">See details in [blog post](https://blog-insider.office.com/2020/04/20/automatically-shorten-links-onedrive-sharepoint/)</span></span>



### <a name="powerpoint"></a><span data-ttu-id="f89c9-298">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-298">PowerPoint</span></span>

- <span data-ttu-id="f89c9-299">**Salvare in cartelle aggiunte:** aggiungere le cartelle semplifica il salvataggio dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-299">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="f89c9-300">Abbiamo ricevuto feedback per cui gli utenti desiderano un maggiore controllo sulle cartelle disponibili per il salvataggio di un nuovo file.</span><span class="sxs-lookup"><span data-stu-id="f89c9-300">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="f89c9-301">Siamo entusiasti di offrirti una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva.</span><span class="sxs-lookup"><span data-stu-id="f89c9-301">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="f89c9-302">Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-302">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="f89c9-303">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-303">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="f89c9-304">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-304">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="teams"></a><span data-ttu-id="f89c9-305">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-305">Teams</span></span>

- <span data-ttu-id="f89c9-306">**Unione chiamate:** la funzione Unisci chiamate consente agli utenti finali di unire le chiamate 1-1 con altre chiamate 1-1 o altre chiamate di gruppo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-306">**Call Merge:** Call Merge gives end users the capability to merge their active unheld 1-1 call into another 1-1 call or another group call.</span></span> <span data-ttu-id="f89c9-307">Si applica alle chiamate VOIP di Teams e alle chiamate PSTN.</span><span class="sxs-lookup"><span data-stu-id="f89c9-307">This applies to Teams VOIP calls and PSTN calls.</span></span>

- <span data-ttu-id="f89c9-308">**Gli amministratori possono configurare la presenza basata sui turni (turno iniziato, turno iniziato) per i loro operatori sul campo:** gli amministratori possono configurare gli operatori sul campo in modo da avere lo stato di presenza basato sul turno: Turno iniziato, Occupato (può essere attivato quando si inizia il turno), Turno iniziato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-308">**Admins can configure shift-based presence (On shift, Off shift) for their Firstline workers:** Admins can configure their firstline workers to have shift-based presence states: On shift, Busy (can be toggled when on shift), and Off shift.</span></span>

- <span data-ttu-id="f89c9-309">**Comunicazione orale con Cortana in Teams:** le abilità di comunicazione orale di Cortana nell’app per dispositivi di Teams consente agli utenti di eseguire attività di riunione, comunicazione e collaborazione usando il solo linguaggio naturale orale.</span><span class="sxs-lookup"><span data-stu-id="f89c9-309">**Cortana voice skills in Teams:** Cortana voice skills in Teams mobile app help users perform meeting, communication and collaboration tasks simply using spoken natural language.</span></span> <span data-ttu-id="f89c9-310">Ora è possono parlare con Cortana facendo clic sul pulsante del microfono nell’app di Teams e fare richieste come “Chiama Megan” o “Invia un messaggio alla prossima riunione” se è necessario contattare gli altri quando si fanno i lavori o domestici o si sta portando fuori il cane, o in generale quando si è di corsa.</span><span class="sxs-lookup"><span data-stu-id="f89c9-310">Users can speak to Cortana by clicking on the microphone button in Teams app and make requests like “Call Megan” or “Send a message to my next meeting” if they need to connect with someone while juggling household chores or walking the dog or generally on the go.</span></span> <span data-ttu-id="f89c9-311">Gli utenti possono partecipare alle riunioni semplicemente dicendo “Partecipa alla prossima riunione”, o controllare il calendario chiedendo “cosa c’è da fare stamattina”.</span><span class="sxs-lookup"><span data-stu-id="f89c9-311">Users can join meetings simply by saying “Join my next meeting” or check their calendar by asking “what do I have this morning”.</span></span> <span data-ttu-id="f89c9-312">Durante una riunione o una chiamata, si può invocare Cortana dal menu di overflow nella pagina della riunione ed eseguire operazioni tipiche delle riunioni, come aggiungere persone in base a nome o numero (“Aggiungi Megan alla chiamata”), visualizzare presentazioni (“presenta il rendiconto trimestrale”) o spostarsi tra le diapositive (“Vai alla diapositiva dell’appendice”).</span><span class="sxs-lookup"><span data-stu-id="f89c9-312">Once in a meeting or a call, they can invoke Cortana from the overflow menu in the meeting stage and perform typical in-meeting tasks like adding people by name or number (“Add Megan to the call”), deck presentation (“present the quarterly review deck”) or navigating slides (“Go to the appendix slide”).</span></span> <span data-ttu-id="f89c9-313">La funzionalità consente anche di trovare e condividere file, ricercare, e spostarsi in generale nell’app di Teams (“Apri la mia chat con John; Vai alle mie attività non lette; Vai alle mie citazioni, ecc.).</span><span class="sxs-lookup"><span data-stu-id="f89c9-313">Other things that the feature supports are finding and sharing files, search, and generally navigating within the Teams app (“Open my chat with John, Go to my unread activity, Go to my mentions etc.).</span></span> <span data-ttu-id="f89c9-314">Cortana in Teams soddisfa gli stessi criteri di riservatezza, sicurezza e conformità validi per i servizi per le organizzazioni di Cortana, come descritto nelle [Condizioni dei servizi online (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span><span class="sxs-lookup"><span data-stu-id="f89c9-314">Cortana in Teams meets the same enterprise-level privacy, security, and compliance promises for Cortana enterprise services, as reflected in the [Online Services Terms (OST)](https://www.microsoft.com/licensing/product-licensing/products).</span></span>

- <span data-ttu-id="f89c9-315">**Ampliamento della chat di gruppo:** ora Team può supportare 250 partecipanti nelle chat di gruppo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-315">**Group chat increase:** Teams added the ability to now have 250 participants in a group chat.</span></span>

- <span data-ttu-id="f89c9-316">**Tag basate sui turni:** con questa funzionalità, alle persone sono assegnate automaticamente dei tag che corrispondono al loro orario e al nome del gruppo del turno nell’ [app Shifts](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span><span class="sxs-lookup"><span data-stu-id="f89c9-316">**Tagging by Shift:** With this feature, people are automatically assigned tags that match their schedule and shift group name in the [Shifts app](https://support.microsoft.com/office/get-started-in-shifts-5f3e30d8-1821-4904-be26-c3cd25a497d6#bkmk_openshiftsappdesktop) in Teams.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-317">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-317">Word</span></span>

- <span data-ttu-id="f89c9-318">**Salvare in cartelle aggiunte:** aggiungere le cartelle semplifica il salvataggio dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-318">**Save to Pinned Folders:** Pin your folders makes saving Office files easier.</span></span> <span data-ttu-id="f89c9-319">Abbiamo ricevuto feedback per cui gli utenti desiderano un maggiore controllo sulle cartelle disponibili per il salvataggio di un nuovo file.</span><span class="sxs-lookup"><span data-stu-id="f89c9-319">We received feedback that users want more control over the folders available when a new file is saved.</span></span> <span data-ttu-id="f89c9-320">Siamo entusiasti di offrirti una nuova funzionalità: l’aggiunta di cartelle nella finestra di dialogo Salva.</span><span class="sxs-lookup"><span data-stu-id="f89c9-320">We're excited to bring a new capability to you: pin your folders in the Save dialog.</span></span> <span data-ttu-id="f89c9-321">Con questa nuova funzionalità sarà più facile salvare i file di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-321">This new capability will make saving your Word, Excel, and PowerPoint files easier.</span></span> [<span data-ttu-id="f89c9-322">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-322">Learn more</span></span>](https://support.office.com/article/d030c796-2aaa-4c3f-b8fa-6a464531722a)<br /><span data-ttu-id="f89c9-323">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-323">See details in [blog post](https://blog-insider.office.com/2020/05/18/pin-your-folders-makes-saving-office-files-easier/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-324">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-324">Office Suite</span></span>

- <span data-ttu-id="f89c9-325">**Riquadri a schede:** ora è possibile passare da un riquadro all'altro usando un'interfaccia a schede sul lato destro dell'app.</span><span class="sxs-lookup"><span data-stu-id="f89c9-325">**Tabbed Panes:** Now you can switch between multiple panes using a tab UI on the right hand side of the app.</span></span> <span data-ttu-id="f89c9-326">L'interfaccia utente sarà visibile solo se sono presenti almeno due riquadri.</span><span class="sxs-lookup"><span data-stu-id="f89c9-326">The UI will only be visible when you have 2+ panes open.</span></span><br /><span data-ttu-id="f89c9-327">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-327">See details in [blog post](https://blog-insider.office.com/2020/02/20/improved-pane-management/)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-330">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-330">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-331">Accesso</span><span class="sxs-lookup"><span data-stu-id="f89c9-331">Access</span></span>

- <span data-ttu-id="f89c9-332">Questo problema è stato risolto. ora è possibile usare il driver ODBC all'esterno delle applicazioni a portata di clic di Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-332">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-333">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-333">Outlook</span></span>

- <span data-ttu-id="f89c9-334">Risolve un problema che faceva sì che gli utenti che tentavano di creare una convocazione di riunione da un account secondario aggiunto al loro profilo non vedessero uno spazio da: campo al posto del loro indirizzo e-mail.</span><span class="sxs-lookup"><span data-stu-id="f89c9-334">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="f89c9-335">Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.</span><span class="sxs-lookup"><span data-stu-id="f89c9-335">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="f89c9-336">È stato risolto un problema che causava il mancato retrazione delle riunioni dal calendario di un responsabile in alcuni casi.</span><span class="sxs-lookup"><span data-stu-id="f89c9-336">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="f89c9-337">È stato risolto un problema che impediva ad alcuni utenti della funzionalità Miglioramenti dei Calendar - Calendario di Outlook condivisi di visualizzare un calendario condiviso appena aggiunto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-337">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="f89c9-338">Risolve un problema che faceva sì che gli utenti sperimentassero occasionalmente degli arresti anomali durante l’interazione con gli allegati cloud.</span><span class="sxs-lookup"><span data-stu-id="f89c9-338">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="f89c9-339">È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-339">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="f89c9-340">È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-340">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="f89c9-341">È stato risolto un problema che causava l'arresto anomalo di quattro o più messaggi di posta elettronica da un account POP con l'opzione "solo intestazioni di download" selezionata.</span><span class="sxs-lookup"><span data-stu-id="f89c9-341">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="f89c9-342">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione da parte di alcuni utenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-342">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="f89c9-343">Questo risolve un problema che causava agli utenti degli arresti anomali occasionali durante la modifica dei destinatari.</span><span class="sxs-lookup"><span data-stu-id="f89c9-343">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="f89c9-344">Risolve un problema che consente agli utenti di visualizzare anomalie durante l'uso della visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="f89c9-344">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="f89c9-345">È stato risolto un problema che causava il mancato recapito del menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="f89c9-345">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="f89c9-346">È stato risolto un problema che causava la ricezione dell'errore seguente quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio, "Alcuni dei file in questa pagina Web non sono nella posizione prevista.</span><span class="sxs-lookup"><span data-stu-id="f89c9-346">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="f89c9-347">Scaricarli comunque?</span><span class="sxs-lookup"><span data-stu-id="f89c9-347">Do you want to download them anyway?</span></span> <span data-ttu-id="f89c9-348">Se si è sicuri che la pagina Web sia una fonte attendibile, fare clic su Sì"</span><span class="sxs-lookup"><span data-stu-id="f89c9-348">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-349">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-349">Project</span></span>

- <span data-ttu-id="f89c9-350">È stato risolto un problema per cui la data di fine del progetto non viene aggiornata per i progetti collegati all'elenco attività di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-350">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="f89c9-351">È stato risolto un problema per cui, se una risorsa aveva più di una tabella tariffe definita, il costo residuo non sempre veniva calcolato correttamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-351">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

### <a name="skype"></a><span data-ttu-id="f89c9-352">Skype</span><span class="sxs-lookup"><span data-stu-id="f89c9-352">Skype</span></span>

- <span data-ttu-id="f89c9-353">Il tono della pelle dell’emoticon che balla modificato su un colorito neutro.</span><span class="sxs-lookup"><span data-stu-id="f89c9-353">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-354">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-354">Word</span></span>

- <span data-ttu-id="f89c9-355">Questa modifica consente di risolvere un problema in cui le applicazioni di Office possono bloccarsi in uno stato di errore di salvataggio silenzioso dopo una sessione di creazione condivisa precedente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-355">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="f89c9-356">È stato risolto un problema per cui la macro AutoOpen veniva eseguita prima di AutoExec</span><span class="sxs-lookup"><span data-stu-id="f89c9-356">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2007-august-25"></a><span data-ttu-id="f89c9-358">Versione 2007: 25 agosto</span><span class="sxs-lookup"><span data-stu-id="f89c9-358">Version 2007: August 25</span></span>
<span data-ttu-id="f89c9-359">*Versione 2007 (Build 13029.20460)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-359">*Version 2007 (Build 13029.20460)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-361">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-361">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-362">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-362">Excel</span></span>

- <span data-ttu-id="f89c9-363">È possibile che si verifichi un errore quando si prova a salvare un file che contiene una formula usando la funzione LET().</span><span class="sxs-lookup"><span data-stu-id="f89c9-363">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-364">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-364">Outlook</span></span>

- <span data-ttu-id="f89c9-365">È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-365">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="f89c9-366">È stato risolto un problema che causava agli utenti di Outlook la comparsa di errori connessi con lo spostamento in modalità di visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="f89c9-366">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-367">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-367">PowerPoint</span></span>

- <span data-ttu-id="f89c9-368">È stato risolto un problema relativo all'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-368">We have fixed a crash issue with PowerPoint app.</span></span>


### <a name="word"></a><span data-ttu-id="f89c9-369">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-369">Word</span></span>

- <span data-ttu-id="f89c9-370">È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio o componevano un nuovo messaggio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-370">Addresses an issue that caused users to experience a crash when replying to or composing new mail.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-371">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-371">Office Suite</span></span>

- <span data-ttu-id="f89c9-372">Per il riquadro Condividi basato su servizi non Web precedente, dopo aver chiuso il documento mentre il riquadro Condividi è aperto potrebbe verificarsi un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-372">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="f89c9-373">Questo problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-373">This is now fixed.</span></span>


- <span data-ttu-id="f89c9-374">È stato risolto un problema per cui gli elementi o il contenuto dell'interfaccia utente non erano visualizzati dagli utenti in determinate condizioni, in particolare con l’entrata e l’uscita dalla visualizzazione Relatore o l'utilizzo di più monitor.</span><span class="sxs-lookup"><span data-stu-id="f89c9-374">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2007-august-11"></a><span data-ttu-id="f89c9-376">Versione 2007: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="f89c9-376">Version 2007: August 11</span></span>
<span data-ttu-id="f89c9-377">*Versione 2007 (Build 13029.20344)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-377">*Version 2007 (Build 13029.20344)*</span></span>

<span data-ttu-id="f89c9-378">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-378">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-380">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-380">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f89c9-381">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-381">Outlook</span></span>

- <span data-ttu-id="f89c9-382">È stato risolto un problema che causava il mancato recupero di suggerimenti per la ricerca da parte di Outlook.</span><span class="sxs-lookup"><span data-stu-id="f89c9-382">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="f89c9-383">È stato risolto un problema che causava occasionalmente l’arresto anomalo degli utenti durante il recupero delle informazioni personali.</span><span class="sxs-lookup"><span data-stu-id="f89c9-383">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-384">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-384">Project</span></span>

- <span data-ttu-id="f89c9-385">È stato risolto un problema che impediva l’apertura di un progetto che aveva ottenuto uno stato non valido.</span><span class="sxs-lookup"><span data-stu-id="f89c9-385">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2007-july-30"></a><span data-ttu-id="f89c9-387">Versione 2007: 30 luglio</span><span class="sxs-lookup"><span data-stu-id="f89c9-387">Version 2007: July 30</span></span>
<span data-ttu-id="f89c9-388">*Versione 2007 (Build 13029.20308)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-388">*Version 2007 (Build 13029.20308)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-390">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-390">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-391">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-391">Excel</span></span>

- <span data-ttu-id="f89c9-392">**Creare una connessione PDF:** connettersi a, importare, aggiornare i dati da un file PDF.</span><span class="sxs-lookup"><span data-stu-id="f89c9-392">**Make a PDF connection:** Connect to, import, refresh data from a PDF.</span></span> [<span data-ttu-id="f89c9-393">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-393">Learn more</span></span>](https://support.office.com/article/be4330b3-5356-486c-a168-b68e9e616f5a)

- <span data-ttu-id="f89c9-394">**Filtrare e ordinare senza interrompere le altre persone:** È ora possibile ordinare e filtrare i file di Excel mentre si collabora con altre persone con la Visualizzazione foglio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-394">**Filter and sort without disrupting others:** You can now sort and filter your Excel file while collaborating with others with Sheet View.</span></span> <span data-ttu-id="f89c9-395">Questa nuova caratteristica fa in modo che gli ordinamenti e i filtri di altri utenti non abbiano alcun impatto durante la creazione condivisa del documento.</span><span class="sxs-lookup"><span data-stu-id="f89c9-395">This new feature prevents you from being impacted by other user’s sorts and filters while coauthoring the document.</span></span> [<span data-ttu-id="f89c9-396">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-396">Learn more</span></span>](https://support.office.com/article/0eea3dc5-d7d1-44c5-a953-25ebfbd6c1a6)

- <span data-ttu-id="f89c9-397">**Applicare automaticamente o consigliare etichette di riservatezza:** Office può consigliare o applicare automaticamente un'etichetta di riservatezza in base al contenuto sensibile rilevato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-397">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="f89c9-398">**Creare tabelle pivot da set di documenti in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di documenti archiviati in Power BI in pochi click.</span><span class="sxs-lookup"><span data-stu-id="f89c9-398">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="f89c9-399"> Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI.</span><span class="sxs-lookup"><span data-stu-id="f89c9-399">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="f89c9-400">Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI.</span><span class="sxs-lookup"><span data-stu-id="f89c9-400">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="f89c9-401">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-401">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="f89c9-402">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-402">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-403">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-403">Outlook</span></span>

- <span data-ttu-id="f89c9-404">**Creare sondaggi in Outlook con Sondaggio rapido:** Creare facilmente un sondaggio, raccogliere voti e visualizzare i risultati in un email [Altre informazioni](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span><span class="sxs-lookup"><span data-stu-id="f89c9-404">**Create polls in Outlook with Quick Poll:** Easily create a poll, collect votes, and view results within an email [Learn more](https://support.office.com/article/46893563-ab12-4bd0-aff7-26f5a488fea0)</span></span>

- <span data-ttu-id="f89c9-405">**Mantenere la qualità elevata delle immagini quando inserite in un messaggio di posta elettronica:** è disponibile una nuova opzione di Outlook per limitare la compressione quando si inviano immagini come parte del contenuto del messaggio di posta elettronica</span><span class="sxs-lookup"><span data-stu-id="f89c9-405">**Keep your pictures high fidelity when sending them as part of an email:** A new Outlook setting is available to limit picture compression when you send pictures as part of the email contents</span></span>

- <span data-ttu-id="f89c9-406">**Riaprire rapidamente gli elementi dalla sessione precedente:** è stata aggiunta un'opzione per riaprire rapidamente gli elementi da una sessione di Outlook precedente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-406">**Quickly reopen items from previous session:** We added an option to quickly reopen items from a previous Outlook session.</span></span> <span data-ttu-id="f89c9-407">Se Outlook si arresta in modo anomalo o lo chiudi, è possibile rilanciare rapidamente gli elementi quando si riapre l'app.</span><span class="sxs-lookup"><span data-stu-id="f89c9-407">Whether Outlook crashes or you close it, you’ll now be able to quickly relaunch items when you reopen the app.</span></span> <span data-ttu-id="f89c9-408">Questa funzionalità è attivata per impostazione predefinita.</span><span class="sxs-lookup"><span data-stu-id="f89c9-408">This feature is on by default.</span></span> <span data-ttu-id="f89c9-409">Per disattivarla, vai a Opzioni > Generale > Opzioni di avvio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-409">To turn it off, go to Options > General > Start up Options.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-410">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-410">PowerPoint</span></span>

- <span data-ttu-id="f89c9-411">**Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-411">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

### <a name="teams"></a><span data-ttu-id="f89c9-412">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-412">Teams</span></span>

- <span data-ttu-id="f89c9-413">**Nuove impostazioni di notifica semplificate:** ora gli utenti possono gestire le impostazioni delle notifiche in modo più semplice con funzionalità avanzate.</span><span class="sxs-lookup"><span data-stu-id="f89c9-413">**New simplified notification settings:** Users can now manage their notifications settings in a more simplified manner with enhanced functionalities.</span></span>

- <span data-ttu-id="f89c9-414">**Le notifiche native di Windows sono ora supportate in Teams:** ora gli utenti possono selezionare la loro modalità preferita per la ricezione delle notifiche, tramite Teams con banner o banner nativi di Windows.</span><span class="sxs-lookup"><span data-stu-id="f89c9-414">**Windows Native Notification are now Supported on Teams:** Users can now select their preferred means of notification delivery, either through teams built in banners or the windows native banners.</span></span>

- <span data-ttu-id="f89c9-415">**Riquadro informazioni del canale:** quando si seleziona l'icona "Informazioni del canale" nell'intestazione del canale, si apre un riquadro dove si vede un riepilogo delle informazioni del canale, tra cui la descrizione del canale, un elenco di collaboratori e membri recenti e la nuova home page per i messaggi di sistema.</span><span class="sxs-lookup"><span data-stu-id="f89c9-415">**Channel Info Pane:** When selecting on the "Channel info" icon in the channel header, a pane will open where you will see a summary of channel information including the channel description, a list of recent contributors and members, as well as the new home for system messages.</span></span>

- <span data-ttu-id="f89c9-416">**Disattivare le anteprime per le notifiche della chat:** gli utenti possono modificare le impostazioni e gestire le anteprime per gli avvisi popup delle notifiche della chat.</span><span class="sxs-lookup"><span data-stu-id="f89c9-416">**Turn off previews for your chat notifications:** Users can change settings and manage previews for their chat notification toasts.</span></span>

- <span data-ttu-id="f89c9-417">**Risposte suggerite:** è stata aggiunta la possibilità per gli utenti di Teams di avere una risposta consigliata alle proprie conversazioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-417">**Suggested replies:** We added the ability for Teams users to have a suggested reply to their conversations.</span></span> <span data-ttu-id="f89c9-418">Questi suggerimenti, se sono abilitati, verranno visualizzati nella parte inferiore di un messaggio di chat.</span><span class="sxs-lookup"><span data-stu-id="f89c9-418">These suggestions will appear at the bottom of a chat message if they are enabled.</span></span> <span data-ttu-id="f89c9-419">Con questi suggerimenti le risposte ai messaggi diventano rapide e semplici.</span><span class="sxs-lookup"><span data-stu-id="f89c9-419">They make replying to messages quick and easy!</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-420">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-420">Word</span></span>

- <span data-ttu-id="f89c9-421">**Applicare automaticamente o consigliare etichette sulla riservatezza:** Office può consigliare o applicare automaticamente un'etichetta sulla riservatezza in base al contenuto sensibile rilevato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-421">**Auto-apply or recommend sensitivity labels:** Office can recommend or automatically apply a sensitivity label based on the sensitive content detected.</span></span>

- <span data-ttu-id="f89c9-422">**Mantenere il testo nei vettori:** ora è possibile mantenere il testo nelle mappe, nei grafici e in altri vettori SVG al momento della conversione di questi oggetti in Excel, Word e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-422">**Retain text in vectors:** Now you can retain the text in maps, charts, and other SVG vectors when converting these objects in Excel, Word, and PowerPoint.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-425">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-425">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-426">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-426">Access</span></span>

- <span data-ttu-id="f89c9-427">Questa correzione risolve il problema per cui il tentativo di eseguire determinate query in precedenza generava il messaggio di errore 'La query è troppo complessa'.</span><span class="sxs-lookup"><span data-stu-id="f89c9-427">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex".</span></span>

### <a name="excel"></a><span data-ttu-id="f89c9-428">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-428">Excel</span></span>

- <span data-ttu-id="f89c9-429">È stato risolto un problema per cui poteva verificarsi un errore o un blocco caricando una cartella di lavoro con più fogli in visualizzazione anteprima interruzioni di pagina.</span><span class="sxs-lookup"><span data-stu-id="f89c9-429">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-430">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-430">Outlook</span></span>

- <span data-ttu-id="f89c9-431">È stato risolto un problema che causava l'arresto anomalo di CLP cambiando l'indirizzo Da in una risposta da un contesto protetto a uno non protetto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-431">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="f89c9-432">Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="f89c9-432">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="f89c9-433">È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un manager.</span><span class="sxs-lookup"><span data-stu-id="f89c9-433">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="f89c9-434">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f89c9-434">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="f89c9-435">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-435">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="f89c9-436">È stato risolto un problema che causava problemi di formattazione negli avvisi di notifica degli eventi imprevisti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-436">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

### <a name="project"></a><span data-ttu-id="f89c9-437">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-437">Project</span></span>

- <span data-ttu-id="f89c9-438">È stato risolto un problema per cui l'attività selezionata nella finestra di dialogo Assegna risorse non è la stessa selezionata nella visualizzazione Bacheca attività.</span><span class="sxs-lookup"><span data-stu-id="f89c9-438">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="f89c9-439">È stato risolto un problema per cui, incollando un'attività con più dipendenze, non tutte le dipendenze vengono copiate correttamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-439">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="f89c9-440">È stato risolto un problema per cui non era possibile salvare un file PDF/XPS da Project a una raccolta documenti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-440">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-441">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-441">Office Suite</span></span>

- <span data-ttu-id="f89c9-442">È stato risolto un problema che causava la visualizzazione di un messaggio di runtime, anche se la transizione al prodotto completo era stata completata.</span><span class="sxs-lookup"><span data-stu-id="f89c9-442">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="f89c9-443">Il problema è stato corretto verificando che il servizio calcolasse correttamente i prodotti aggiunti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-443">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="f89c9-444">I nuovi prodotti aggiunti sono stati filtrati (verificando che esistano anche nella nuova configurazione) e aggiunti alla fine degli ID di rilascio prodotti esistenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-444">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-july-28"></a><span data-ttu-id="f89c9-446">Versione 2006: 28 luglio</span><span class="sxs-lookup"><span data-stu-id="f89c9-446">Version 2006: July 28</span></span>
<span data-ttu-id="f89c9-447">*Versione 2006 (Build 13001.20498)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-447">*Version 2006 (Build 13001.20498)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-449">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-449">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-450">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-450">Excel</span></span>

- <span data-ttu-id="f89c9-451">È stato risolto un problema per cui poteva verificarsi un errore o un blocco caricando una cartella di lavoro con più fogli in visualizzazione anteprima interruzioni di pagina.</span><span class="sxs-lookup"><span data-stu-id="f89c9-451">Fixed an issue where an error or hang may occur when loading a workbook with with multiple sheets in page break preview.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-452">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-452">Outlook</span></span>

- <span data-ttu-id="f89c9-453">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="f89c9-453">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="word"></a><span data-ttu-id="f89c9-454">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-454">Word</span></span>

- <span data-ttu-id="f89c9-455">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="f89c9-455">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-456">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-456">Office Suite</span></span>

- <span data-ttu-id="f89c9-457">Un problema di tempi poteva causare un arresto anomalo durante la chiusura dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="f89c9-457">A timing issue could cause a crash when closing office files.</span></span>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2006-july-14"></a><span data-ttu-id="f89c9-459">Versione 2006: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="f89c9-459">Version 2006: July 14</span></span>
<span data-ttu-id="f89c9-460">*Versione 2006 (Build 13001.20384)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-460">*Version 2006 (Build 13001.20384)*</span></span>

<span data-ttu-id="f89c9-461">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-461">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-463">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-463">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-464">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-464">Access</span></span>

- <span data-ttu-id="f89c9-465">È stato risolto un problema relativo all'inserimento di tabelle SQL collegate che includono un campo identità, ad esempio numerazione automatica.</span><span class="sxs-lookup"><span data-stu-id="f89c9-465">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

### <a name="excel"></a><span data-ttu-id="f89c9-466">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-466">Excel</span></span>

- <span data-ttu-id="f89c9-467">È possibile che si sia verificata la classificazione automatica dei documenti per le cartelle di lavoro in modalità di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="f89c9-467">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="f89c9-468">È stato risolto un arresto anomalo che può verificarsi quando si cerca di creare una connessione dati, se l’utente si è disconnesso dal proprio account.</span><span class="sxs-lookup"><span data-stu-id="f89c9-468">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

### <a name="onenote"></a><span data-ttu-id="f89c9-469">OneNote</span><span class="sxs-lookup"><span data-stu-id="f89c9-469">OneNote</span></span>

- <span data-ttu-id="f89c9-470">Miglioramento del rilevamento dello stato di creazione condivisa per ridurre l’utilizzo delle risorse.</span><span class="sxs-lookup"><span data-stu-id="f89c9-470">Improve detection of co-authoring status to reduce resource utilization.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-471">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-471">Outlook</span></span>

- <span data-ttu-id="f89c9-472">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="f89c9-472">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-473">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-473">Office Suite</span></span>

- <span data-ttu-id="f89c9-474">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="f89c9-474">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="f89c9-475">È stato risolto un problema di arresto imprevisto con l'host di Office in Windows, per cui un componente aggiuntivo viene attivato quando il valore del registro TabProcGrowth è di tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="f89c9-475">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2006-june-30"></a><span data-ttu-id="f89c9-477">Versione 2006: 30 giugno</span><span class="sxs-lookup"><span data-stu-id="f89c9-477">Version 2006: June 30</span></span>
<span data-ttu-id="f89c9-478">*Versione 2006 (Build 13001.20266)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-478">*Version 2006 (Build 13001.20266)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-480">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-480">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-481">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-481">Excel</span></span>

- <span data-ttu-id="f89c9-482">**Nomi file più lunghi:** Excel per Windowsdesktop ora supporta file di OneDrive/SharePoint con nomi e percorsi lunghi fino a 400 caratteri.</span><span class="sxs-lookup"><span data-stu-id="f89c9-482">**Longer file names:** Excel for Windows desktop now supports OneDrive/SharePoint files with names and paths of up to 400 characters.</span></span>

- <span data-ttu-id="f89c9-483">**Miglioramenti di RealTimeData (RTD):** in Office 365 versione 2002 canale mensile e successiva, la funzione RealTimeData (RTD) di Excel è molto più veloce rispetto a Excel 2010 per il calcolo dei dati nel foglio di calcolo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-483">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="f89c9-484">Sono stati rimossi i colli di bottiglia nelle strutture di memoria e di dati sottostanti oltre a renderlo thread-safe per consentirne il calcolo su tutti i thread disponibili di ricalcolo multithread (MTR).</span><span class="sxs-lookup"><span data-stu-id="f89c9-484">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-485">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-485">Outlook</span></span>

- <span data-ttu-id="f89c9-486">**Nuova opzione per disabilitare i suggerimenti di @menzioni durante la composizione dei messaggi di posta elettronica in Outlook:** si trovano i suggerimenti per la selezione delle menzioni più fastidiosi che utili?</span><span class="sxs-lookup"><span data-stu-id="f89c9-486">**New option to disable @ mention suggestions when composing mail in Outlook:** Do you find the @ mention picker more annoying than useful?</span></span> <span data-ttu-id="f89c9-487">Ora è possibile disattivarli.</span><span class="sxs-lookup"><span data-stu-id="f89c9-487">Now you can turn it off if you prefer.</span></span><br /><span data-ttu-id="f89c9-488">Vedere i dettagli nel [post del blog](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-488">See details in [blog post](https://blog-insider.office.com/2020/03/26/feedback-in-action-disable-mentions/)</span></span>

- <span data-ttu-id="f89c9-489">**Notifica di evento imprevisto per gli amministratori IT:** gli amministratori globali dei tenant di Microsoft 365 e gli amministratori delle app di Office verranno avvisati degli eventi imprevisti di Outlook e Office 365 Exchange che interessano gli utenti tramite una nuova notifica nel riquadro a destra in Outlook per Windows.</span><span class="sxs-lookup"><span data-stu-id="f89c9-489">**Incident Notification for IT Admins:** Microsoft 365 tenant global administrators and Office Apps Administrators will be notified about Outlook and O365 Exchange incidents affecting their users with a new right-side panel notification in Outlook for Windows.</span></span> [<span data-ttu-id="f89c9-490">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-490">Learn more</span></span>](https://support.office.com/article/46c07f08-1277-41ce-b353-4e205e9da333)

- <span data-ttu-id="f89c9-491">**Altri pulsanti aggiunti agli avvisi popup di Outlook:** i pulsanti di azione rapida sono ora visualizzati negli avvisi popup di Outlook quando si esegue Outlook in Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f89c9-491">**Additional buttons added to Outlook toast notifications:** Quick Action buttons now appear in Outlook toast notifications when running Outlook on Windows 10</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-492">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-492">PowerPoint</span></span>

- <span data-ttu-id="f89c9-493">**Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida.</span><span class="sxs-lookup"><span data-stu-id="f89c9-493">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="f89c9-494">I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.</span><span class="sxs-lookup"><span data-stu-id="f89c9-494">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

### <a name="teams"></a><span data-ttu-id="f89c9-495">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-495">Teams</span></span>

- <span data-ttu-id="f89c9-496">**I numeri di telefono dei partecipanti PSTN non sono visibili dagli utenti esterni:** Per i clienti con la funzionalità di audioconferenza abilitata per le riunioni di Teams, mascheriamo il numero di telefono dei partecipanti PSTN per gli utenti che sono esterni all'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-496">**PSTN participant phone numbers are masked from external users:** For customers with Audio Conferencing enabled for their Teams meetings, we will mask the PSTN participant's phone number to users who have joined from outside of your organization.</span></span>

- <span data-ttu-id="f89c9-497">**Un modo semplificato per gestire le impostazioni di notifica del canale:** Usando l’elenco dei team e dei canali oppure l'intestazione del canale, gli utenti possono gestire rapidamente le impostazioni di notifica attivando o disattivando tutte le attività con un solo clic, oppure esplorando le personalizzazioni per configurarle come necessario.</span><span class="sxs-lookup"><span data-stu-id="f89c9-497">**Simplified way to manage your channel notification settings:** Through the teams and channels list or from the channel header, the users can quickly manage their notification settings by turning all activity on or off with a single click or diving deep into custom to set their preferred permutations.</span></span>

- <span data-ttu-id="f89c9-498">**Walkie talkie:** comunicazione vocale istantanea con tecnologia push-to-talk.</span><span class="sxs-lookup"><span data-stu-id="f89c9-498">**Walkie Talkie:** Instant voice communication using push-to-talk.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-499">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-499">Word</span></span>

- <span data-ttu-id="f89c9-500">**Conferma dell'azione nelle utilità per la lettura dello schermo:** la conferma dell'azione rappresenta un requisito importante per l'accessibilità.</span><span class="sxs-lookup"><span data-stu-id="f89c9-500">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="f89c9-501">Con l'introduzione di una nuova API di notifica di Windows, è ora possibile avvisare gli utenti delle utilità per la lettura dello schermo della riuscita delle azioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-501">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="f89c9-502">I comandi taglia, copia, incolla, grassetto, corsivo, sottolineato, annulla, ripristina, correzione automatica e maiuscole automatiche ora sono tutti annunciati agli utenti dell'Assistente vocale in Win32 Word.</span><span class="sxs-lookup"><span data-stu-id="f89c9-502">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="f89c9-503">Per abilitare questa funzionalità, attivare l'Assistente vocale premendo il tasto Windows + CTRL + INVIO.</span><span class="sxs-lookup"><span data-stu-id="f89c9-503">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-506">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-506">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-507">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-507">Access</span></span>

- <span data-ttu-id="f89c9-508">È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.</span><span class="sxs-lookup"><span data-stu-id="f89c9-508">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


### <a name="excel"></a><span data-ttu-id="f89c9-509">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-509">Excel</span></span>

- <span data-ttu-id="f89c9-510">È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f89c9-510">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-511">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-511">Outlook</span></span>

- <span data-ttu-id="f89c9-512">È stato risolto un problema a causa del quale gli utenti visualizzavano la data di creazione degli allegati copiati nel file system tramite il trascinamento fissata all’1 gennaio 4501.</span><span class="sxs-lookup"><span data-stu-id="f89c9-512">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>

- <span data-ttu-id="f89c9-513">È stato risolto un problema a causa del quale gli utenti dei miglioramenti del Calendario di Outlook condivisi visualizzavano errori di Calendario di Outlook.</span><span class="sxs-lookup"><span data-stu-id="f89c9-513">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="f89c9-514">È stato risolto un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-514">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="f89c9-515">È stato risolto un problema a causa del quale CTRL+clic smetteva di funzionare quando le impostazioni del cloud erano abilitate.</span><span class="sxs-lookup"><span data-stu-id="f89c9-515">Addressed an issue that caused Ctrl+click to stop working when cloud settings were enabled.</span></span>


- <span data-ttu-id="f89c9-516">È stato risolto un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.</span><span class="sxs-lookup"><span data-stu-id="f89c9-516">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-517">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-517">Project</span></span>

- <span data-ttu-id="f89c9-518">È stato risolto un problema per cui non era possibile aprire progetti nel client Project Desktop da Project Web App se l'URL terminava in ". com".</span><span class="sxs-lookup"><span data-stu-id="f89c9-518">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="f89c9-519">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.</span><span class="sxs-lookup"><span data-stu-id="f89c9-519">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="f89c9-520">È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="f89c9-520">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


### <a name="word"></a><span data-ttu-id="f89c9-521">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-521">Word</span></span>

- <span data-ttu-id="f89c9-522">È stato risolto un problema durante l'apertura di documenti di Word tramite consegna di documenti personalizzati (aspx) con URL contenente un componente di query.</span><span class="sxs-lookup"><span data-stu-id="f89c9-522">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-24"></a><span data-ttu-id="f89c9-524">Versione 2005: 24 giugno</span><span class="sxs-lookup"><span data-stu-id="f89c9-524">Version 2005: June 24</span></span>
<span data-ttu-id="f89c9-525">*Versione 2005 (Build 12827.20470)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-525">*Version 2005 (Build 12827.20470)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-527">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-527">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-528">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-528">Access</span></span>

- <span data-ttu-id="f89c9-529">Il problema è stato risolto; ora è possibile usare il tipo di dati data/ora esteso nel codice senza subire alcun arresto anomalo dell'app.</span><span class="sxs-lookup"><span data-stu-id="f89c9-529">This bug has now been fixed; you should be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span> <span data-ttu-id="f89c9-530">Si prega di contattare il team se si riscontrano altri problemi.</span><span class="sxs-lookup"><span data-stu-id="f89c9-530">Please let the team know if you encounter further issues.</span></span>


- <span data-ttu-id="f89c9-531">Il problema è stato risolto; ora è possibile tornare alla versione di Access più aggiornata e usare DAO/VBA per gestire e modificare un tipo di dati decimale.</span><span class="sxs-lookup"><span data-stu-id="f89c9-531">This issue has now been fixed; you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span> <span data-ttu-id="f89c9-532">Contattare il team di Access se si riscontrano altri problemi con l'uso del tipo di dati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-532">Please let the Access team know if you encounter any further issues with using our data type.</span></span>


### <a name="excel"></a><span data-ttu-id="f89c9-533">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-533">Excel</span></span>

- <span data-ttu-id="f89c9-534">È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="f89c9-534">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>





### <a name="outlook"></a><span data-ttu-id="f89c9-535">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-535">Outlook</span></span>

- <span data-ttu-id="f89c9-536">È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="f89c9-536">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="f89c9-537">È stato risolto un problema a causa del quale gli utenti visualizzavano la data di creazione degli allegati copiati nel file system tramite il trascinamento fissata all’1 gennaio 4501.</span><span class="sxs-lookup"><span data-stu-id="f89c9-537">Addressed an issue that caused users to see the creation date of attachments that they copied to their file system via drag and drop getting set to January 1, 4501.</span></span>


- <span data-ttu-id="f89c9-538">È stato risolto un problema che causava la visualizzazione del messaggio &quot;Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange&quot; all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="f89c9-538">Addressed an issue that caused users to see the &quot;The rules on this computer do not match the rules on Microsoft Exchange&quot; message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="f89c9-539">È stato risolto un problema a causa del quale gli utenti dei miglioramenti del Calendario di Outlook condivisi visualizzavano errori di Calendario di Outlook.</span><span class="sxs-lookup"><span data-stu-id="f89c9-539">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="f89c9-540">È stato risolto un problema che causava blocchi o arresti intermittenti in alcune situazioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-540">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>


- <span data-ttu-id="f89c9-541">È stato risolto un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-541">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="f89c9-542">È stato risolto un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.</span><span class="sxs-lookup"><span data-stu-id="f89c9-542">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="f89c9-543">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-543">PowerPoint</span></span>

- <span data-ttu-id="f89c9-544">È stato risolto un problema relativo all'arresto anomalo del riquadro suggerimenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-544">We have fixed a crash issue with suggestion pane.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-545">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-545">Project</span></span>

- <span data-ttu-id="f89c9-546">È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="f89c9-546">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-547">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-547">Word</span></span>

- <span data-ttu-id="f89c9-548">È stato risolto un problema che può aver causato un arresto anomalo durante il trascinamento del contenuto dall'app.</span><span class="sxs-lookup"><span data-stu-id="f89c9-548">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-549">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-549">Office Suite</span></span>

- <span data-ttu-id="f89c9-550">Questa modifica risolve potenziali blocchi che si verificano durante il caricamento e la riproduzione di contenuti animati, ad esempio GIF o modelli 3D.</span><span class="sxs-lookup"><span data-stu-id="f89c9-550">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>




[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-09"></a><span data-ttu-id="f89c9-552">Versione 2005: 09 giugno</span><span class="sxs-lookup"><span data-stu-id="f89c9-552">Version 2005: June 09</span></span>
<span data-ttu-id="f89c9-553">*Versione 2005 (Build 12827.20336)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-553">*Version 2005 (Build 12827.20336)*</span></span>

<span data-ttu-id="f89c9-554">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-554">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="feature-updates"></a><span data-ttu-id="f89c9-555">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-555">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-556">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-556">Excel</span></span>

- <span data-ttu-id="f89c9-557">**Lazo e gomma nella casella degli strumenti input penna:** quando si usano gli strumenti di disegno, il lazo e la gomma sono ora disponibili nella casella degli strumenti input penna.</span><span class="sxs-lookup"><span data-stu-id="f89c9-557">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-558">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-558">PowerPoint</span></span>

- <span data-ttu-id="f89c9-559">**Lazo e gomma nella casella degli strumenti input penna:** quando si usano gli strumenti di disegno, il lazo e la gomma sono ora disponibili nella casella degli strumenti input penna.</span><span class="sxs-lookup"><span data-stu-id="f89c9-559">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-560">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-560">Word</span></span>

- <span data-ttu-id="f89c9-561">**Lazo e gomma nella casella degli strumenti input penna:** quando si usano gli strumenti di disegno, il lazo e la gomma sono ora disponibili nella casella degli strumenti input penna.</span><span class="sxs-lookup"><span data-stu-id="f89c9-561">**Lasso and eraser in Ink Toolbox:** When using the drawing tools, the lasso and the eraser are now available in the Ink Toolbox.</span></span>




[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-564">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-564">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-565">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-565">Excel</span></span>

- <span data-ttu-id="f89c9-566">È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo nel tentativo di inserire tabelle pivot in un foglio grafico.</span><span class="sxs-lookup"><span data-stu-id="f89c9-566">Addresses an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-567">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-567">PowerPoint</span></span>

- <span data-ttu-id="f89c9-568">Ciò risolve un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-568">This fixes a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

### <a name="project"></a><span data-ttu-id="f89c9-569">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-569">Project</span></span>

- <span data-ttu-id="f89c9-570">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.</span><span class="sxs-lookup"><span data-stu-id="f89c9-570">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-571">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-571">Office Suite</span></span>

- <span data-ttu-id="f89c9-572">È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-572">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2005-june-02"></a><span data-ttu-id="f89c9-574">Versione 2005: 02 giugno</span><span class="sxs-lookup"><span data-stu-id="f89c9-574">Version 2005: June 02</span></span>
<span data-ttu-id="f89c9-575">*Versione 2005 (Build 12827.20268)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-575">*Version 2005 (Build 12827.20268)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-577">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-577">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-578">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-578">Excel</span></span>

- <span data-ttu-id="f89c9-579">**Uso automatico dei nuovi tipi di dati** : quando si digita un valore di dati che assomiglia a un'azione o a una posizione geografica, Excel offre la possibilità di convertirlo nel tipo di dati connesso: Azioni o Dati geografici.</span><span class="sxs-lookup"><span data-stu-id="f89c9-579">**Automatically use new data types:** When you type a data value that resembles a stock or a geographic location, Excel offers to convert it to the right connected data type - Stocks or Geography.</span></span> [<span data-ttu-id="f89c9-580">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-580">Learn more</span></span>](https://support.office.com/article/61a33056-9935-484f-8ac8-f1a89e210877)

- <span data-ttu-id="f89c9-581">**Racconta le tue storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate per dare un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-581">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-582">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-582">Outlook</span></span>

- <span data-ttu-id="f89c9-583">**Protezione dei dati nel gruppo:** l'etichetta di riservatezza che si sceglie quando si crea un gruppo viene applicata ai messaggi di posta elettronica, ai documenti e ai siti del team del gruppo</span><span class="sxs-lookup"><span data-stu-id="f89c9-583">**Help protect data in your group:** The Sensitivity label you choose when creating a group is applied to group email, documents, and team sites</span></span>

- <span data-ttu-id="f89c9-584">**Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai.</span><span class="sxs-lookup"><span data-stu-id="f89c9-584">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="f89c9-585">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-585">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="f89c9-586">**Racconta le tue storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate per dare un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-586">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>

- <span data-ttu-id="f89c9-587">**Aggiornamento del calendario:** aggiornamenti visivi che rendono il calendario più facile da analizzare.</span><span class="sxs-lookup"><span data-stu-id="f89c9-587">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="f89c9-588">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-588">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="f89c9-589">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-589">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-590">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-590">PowerPoint</span></span>

- <span data-ttu-id="f89c9-591">**Racconta le tue storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate per dare un tocco di eleganza ai documenti [Maggiori informazioni](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span><span class="sxs-lookup"><span data-stu-id="f89c9-591">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier [Learn more](https://support.office.com/article/3a04f755-25a9-42c4-8cc1-1da4148aef01)</span></span>

- <span data-ttu-id="f89c9-592">**Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-592">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="f89c9-593">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-593">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="f89c9-594">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="f89c9-594">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="f89c9-595">**Non c'è bisogno del clicker grazie agli auricolari:** i Surface Earbuds permettono di controllare le presentazioni di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-595">**No need for a clicker: your earbuds have you covered:** Use your Surface Earbuds to control your PowerPoint presentations.</span></span> <span data-ttu-id="f89c9-596">Come funziona: una volta accoppiati, è necessario abilitare la funzionalità in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-596">How it works:  Once paired, you'll need to enable the feature in PowerPoint.</span></span> <span data-ttu-id="f89c9-597">Avviare una presentazione premendo F5 o selezionando >Presentazione > Dall'inizio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-597">Start a presentation by pressing F5 or selecting Slide Show > From Beginning.</span></span>  <span data-ttu-id="f89c9-598">In Presentazione, fare clic destro sulla diapositiva e, in Impostazioni Surface Earbuds, scegliere Usa gesti per controllare la presentazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-598">In Slide Show, right click on the slide and under Surface Earbuds Settings choose Use Gestures to Control Presentation.</span></span>  <span data-ttu-id="f89c9-599">Questa opzione verrà memorizzata per tutte le presentazioni future.</span><span class="sxs-lookup"><span data-stu-id="f89c9-599">This setting will be remembered for all future presentations.</span></span> <span data-ttu-id="f89c9-600">Ora è possibile scorrere rapidamente in avanti e indietro sull'auricolare sinistro per spostarsi tra le presentazioni nella modalità Presentazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-600">You can now can swipe forward and backward on the left earbud to navigate your presentations in Slide Show mode.</span></span>  <span data-ttu-id="f89c9-601">Fare clic due volte per riprodurre o sospendere i video incorporati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-601">Double tap to play or pause embedded videos.</span></span>  <span data-ttu-id="f89c9-602">Importante: per usare i gesti per controllare le presentazioni è necessario associare gli auricolari Surface Earbuds nell'app Surface Audio per Windows 10.</span><span class="sxs-lookup"><span data-stu-id="f89c9-602">Important: You must pair your Surface Earbuds in the Surface Audio app for Windows 10 in order to use gestures to control presentations.</span></span> <span data-ttu-id="f89c9-603">Le istruzioni per iniziare a usare l'app Surface Audio in Windows 10 sono disponibili qui.</span><span class="sxs-lookup"><span data-stu-id="f89c9-603">Instructions for getting started with the Surface Audio app on Windows 10 are available here.</span></span> [<span data-ttu-id="f89c9-604">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-604">Learn more</span></span>](https://support.office.com/article/6319a6f3-ad69-44e6-a8ff-e79676423e4a)

### <a name="teams"></a><span data-ttu-id="f89c9-605">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-605">Teams</span></span>

- <span data-ttu-id="f89c9-606">**Modifica del layout video delle riunioni di Teams:** presto, il numero di partecipanti che saranno visibili simultaneamente durante le riunioni di Teams passerà da 4 a 9.</span><span class="sxs-lookup"><span data-stu-id="f89c9-606">**Changes to video layout in Teams meetings:** Soon, the number of participants that can be viewed simultaneously during a Teams meeting will increase from 4 to 9.</span></span>

- <span data-ttu-id="f89c9-607">**Inclusione dell'audio di sistema negli eventi in tempo reale:** relatori e produttori di eventi in tempo reale possono ora includere l'audio del sistema quando condividono una schermata del desktop o di una finestra durante eventi dal vivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-607">**Include system audio in live events:** Presenters and producers in live events can now include system audio when sharing a desktop or window screen during the live event.</span></span> <span data-ttu-id="f89c9-608">Ciò consentirà agli utenti di sentire qualsiasi parte del contenuto audio che viene condiviso.</span><span class="sxs-lookup"><span data-stu-id="f89c9-608">This will allow your users to hear any audio part of the content you are sharing.</span></span>

- <span data-ttu-id="f89c9-609">**Gli organizzatori possono modificare le impostazioni della sala d'attesa per i partecipanti telefonici:** questa impostazione consente di controllare se le persone che effettuano l'accesso tramite telefono si uniscono direttamente alla riunione oppure aspettano in sala d'attesa, indipendentemente dall'impostazione Ammetti automaticamente le persone.</span><span class="sxs-lookup"><span data-stu-id="f89c9-609">**Enable organizers to change lobby settings for dial-in participants:** This setting controls whether people who dial in by phone join the meeting directly or wait in the lobby regardless of the Automatically admit people setting.</span></span>

- <span data-ttu-id="f89c9-610">**Alzata di mano durante le riunioni:** Ora gli utenti possono sollevare la mano virtuale durante le riunioni!</span><span class="sxs-lookup"><span data-stu-id="f89c9-610">**Raise Your Hand in Meetings:** Users can now raise a virtual hand in a meeting!</span></span> <span data-ttu-id="f89c9-611">Gli altri partecipanti vedono la mano alzata accanto al nome dell'utente nella sala della riunione e al suo nome nel gruppo di partecipanti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-611">Other participants will see your raised hand next to your name in the meeting stage and next to your name in the roster.</span></span>

- <span data-ttu-id="f89c9-612">**Personalizzazione degli sfondi delle videoconferenze:** quando si tengono videoriunioni, ora è possibile scegliere tra differenti sfondi statici.</span><span class="sxs-lookup"><span data-stu-id="f89c9-612">**Customize meeting video backgrounds:** When you are meeting with video, you now have the choice of different static background images to use.</span></span> <span data-ttu-id="f89c9-613">L’immagine di sfondo viene mostrata al posto dello sfondo effettivo del luogo in cui ci si trova.</span><span class="sxs-lookup"><span data-stu-id="f89c9-613">This will let you show this image and not the actual background of where you are sitting.</span></span>

- <span data-ttu-id="f89c9-614">**Aggiungere altre persone alla chat:** è ora possibile aggiungere fino a 350 persone a un singolo thread di chat.</span><span class="sxs-lookup"><span data-stu-id="f89c9-614">**Add more people to chat:** We made it possible to now add up to 350 people to a single chat thread.</span></span>

- <span data-ttu-id="f89c9-615">**Icona delle impostazioni nel feed della attività:** gli utenti possono ora accedere direttamente alle impostazioni del feed delle attività e delle notifiche tramite la barra sinistra del feed, usando l’icona dell’ingranaggio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-615">**Settings Gear on your Activity Feed:** Users can now directly access activity feed and notification setting from the feed left rail by the means of a settings gear.</span></span>

- <span data-ttu-id="f89c9-616">**Accedere facilmente alle opzioni della riunione all’interno di una riunione di Teams in corso:** stiamo consentendo agli organizzatori di riunioni di modificare rapidamente e facilmente le impostazioni del relatore e della lobby dopo che una riunione di Teams è iniziata, fornendo un collegamento accessibile direttamente nel riquadro Partecipanti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-616">**Easily access meeting options from within a Teams meeting in progress:** We are making it easier for meeting organizers to quickly and easily change their presenter and lobby settings once a Teams meeting starts by providing an easy to access link directly in the participants pane.</span></span> <span data-ttu-id="f89c9-617">Questa nuova funzionalità sarà disponibile sia per le riunioni pianificate che quelle immediate.</span><span class="sxs-lookup"><span data-stu-id="f89c9-617">This new functionality will be present for both scheduled and “Meet Now” meetings.</span></span>

- <span data-ttu-id="f89c9-618">**Analisi per team e canali:** oltre ai dati analitici dei team, ora è possibile consultare le metriche e i dati analitici per i canali.</span><span class="sxs-lookup"><span data-stu-id="f89c9-618">**Team and channel analytics:** In addition to team analytics, now you can also view channel level metrics and insights.</span></span> <span data-ttu-id="f89c9-619">Abbiamo anche esteso il periodo a 90 giorni. Ora è possibile analizzare i dati per periodi più lunghi.</span><span class="sxs-lookup"><span data-stu-id="f89c9-619">We've also enhanced the time period to 90 days so you can analyze data for longer periods.</span></span> <span data-ttu-id="f89c9-620">Oltre a questo, questa versione include anche nuove metriche e grafici per il conteggio di post, risposte e riunioni dei team o dei canali.</span><span class="sxs-lookup"><span data-stu-id="f89c9-620">Apart from that, this release also includes new metrics and charts around count of posts, replies and meetings for a team or channel.</span></span>

- <span data-ttu-id="f89c9-621">**Annunci di ingresso/uscita:** abbiamo aggiunto una funzionalità che consente agli organizzatori di attivare o disattivare gli annunci di ingresso e uscta per le riunioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-621">**Entry/exit announcements:** We added this feature that lets meeting organizers have the ability to turn on or off entry and exit announcements for a meeting.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-622">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-622">Word</span></span>

- <span data-ttu-id="f89c9-623">**Decodifica degli acronimi senza uscire da Word:** quando viene rilevato un acronimo, Word prova a definirlo in base a come viene usato da altri utenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-623">**Decode acronyms without leaving Word:** When you encounter an acronym, Word will try to define it based on how others use it.</span></span>

- <span data-ttu-id="f89c9-624">**Racconta le tue storie con GIF animate:** Nell’editor di Office sono ora supportate le GIF animate per dare un tocco di eleganza ai documenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-624">**Tell your stories with animated GIFs:** Animated GIFs are now supported in the Office editor - your documents just got snazzier</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-627">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-627">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="f89c9-628">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-628">Excel</span></span>

- <span data-ttu-id="f89c9-629">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="f89c9-629">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="f89c9-630">In alcuni casi, se si fa clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro verrà nascosta.</span><span class="sxs-lookup"><span data-stu-id="f89c9-630">In some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-631">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-631">Outlook</span></span>

- <span data-ttu-id="f89c9-632">È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.</span><span class="sxs-lookup"><span data-stu-id="f89c9-632">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="f89c9-633">È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso "Stato dell’antivirus: non valido".</span><span class="sxs-lookup"><span data-stu-id="f89c9-633">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid".</span></span> <span data-ttu-id="f89c9-634">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se l'antivirus è stato installato correttamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-634">This version of Windows supports antivirus detection, but no antivirus was found despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="f89c9-635">È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.</span><span class="sxs-lookup"><span data-stu-id="f89c9-635">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

### <a name="skype"></a><span data-ttu-id="f89c9-636">Skype</span><span class="sxs-lookup"><span data-stu-id="f89c9-636">Skype</span></span>

- <span data-ttu-id="f89c9-637">Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-637">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="f89c9-638">In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="f89c9-638">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="f89c9-639">Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="f89c9-639">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-640">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-640">Office Suite</span></span>

- <span data-ttu-id="f89c9-641">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="f89c9-641">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="f89c9-642">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="f89c9-642">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="f89c9-643">L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="f89c9-643">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="f89c9-644">La modifica potrebbe risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="f89c9-644">This change would fix this issue.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-21"></a><span data-ttu-id="f89c9-646">Versione 2004: 21 maggio</span><span class="sxs-lookup"><span data-stu-id="f89c9-646">Version 2004: May 21</span></span>
<span data-ttu-id="f89c9-647">*Versione 2004 (Build 12730.20352)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-647">*Version 2004 (Build 12730.20352)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-649">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-649">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-650">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-650">Excel</span></span>

- <span data-ttu-id="f89c9-651">È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-651">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-652">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-652">Outlook</span></span>

- <span data-ttu-id="f89c9-653">È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.</span><span class="sxs-lookup"><span data-stu-id="f89c9-653">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-654">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-654">Office Suite</span></span>

- <span data-ttu-id="f89c9-655">È stato risolto un problema che provocava errori occasionali di aggiornamento per le build più recenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-655">Fixed a Click-to-Run issue which was resulting in occasional update failures to the latest builds.</span></span>

- <span data-ttu-id="f89c9-656">È stato risolto un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="f89c9-656">Fixed an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-12"></a><span data-ttu-id="f89c9-658">Versione 2004: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="f89c9-658">Version 2004: May 12</span></span>
<span data-ttu-id="f89c9-659">*Versione 2004 (Build 12730.20270)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-659">*Version 2004 (Build 12730.20270)*</span></span>

<span data-ttu-id="f89c9-660">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-660">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-662">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-662">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f89c9-663">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-663">Outlook</span></span>

- <span data-ttu-id="f89c9-664">È stato risolto un problema che causava un arresto anomalo quando vengono visualizzate notifiche popup.</span><span class="sxs-lookup"><span data-stu-id="f89c9-664">Addresses an issue that caused users to experience a crash when displaying toast notifications.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-may-04"></a><span data-ttu-id="f89c9-666">Versione 2004: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="f89c9-666">Version 2004: May 04</span></span>
<span data-ttu-id="f89c9-667">*Versione 2004 (Build 12730.20250)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-667">*Version 2004 (Build 12730.20250)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-669">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-669">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="f89c9-670">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-670">Office Suite</span></span>

- <span data-ttu-id="f89c9-671">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="f89c9-671">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2004-april-29"></a><span data-ttu-id="f89c9-673">Versione 2004: 29 aprile</span><span class="sxs-lookup"><span data-stu-id="f89c9-673">Version 2004: April 29</span></span>
<span data-ttu-id="f89c9-674">*Versione 2004 (Build 12730.20236)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-674">*Version 2004 (Build 12730.20236)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-676">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-676">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-677">Accesso</span><span class="sxs-lookup"><span data-stu-id="f89c9-677">Access</span></span>

- <span data-ttu-id="f89c9-678">**Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla.</span><span class="sxs-lookup"><span data-stu-id="f89c9-678">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="f89c9-679">Cercare e sostituire il testo nella visualizzazione SQL.</span><span class="sxs-lookup"><span data-stu-id="f89c9-679">Search and replace text in SQL View.</span></span> <span data-ttu-id="f89c9-680">Selezionare più tabelle nella finestra Relazioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-680">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="f89c9-681">**Aggiungere tabelle con meno clic** : usare il riquadro attività Aggiungere tabelle, che resta aperto mentre si lavora, per aggiungere tabelle a relazioni e query.</span><span class="sxs-lookup"><span data-stu-id="f89c9-681">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="f89c9-682">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-682">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)


### <a name="excel"></a><span data-ttu-id="f89c9-683">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-683">Excel</span></span>

- <span data-ttu-id="f89c9-684">**Il supporto per il connettore Facebook sta per terminare:** a partire dall'aprile del 2020, Excel non supporterà più connessioni dati esterne che usano il connettore Facebook.</span><span class="sxs-lookup"><span data-stu-id="f89c9-684">**Facebook connector support is ending:** Starting in April 2020, Excel will no longer support external data connections that use the Facebook connector.</span></span>

- <span data-ttu-id="f89c9-685">**Dubbi? Chiedi a Excel:** ora Excel Ideas consente di rivolgere domande sui propri dati, senza sprecare tempo per scrivere formule (disponibile solo in inglese).</span><span class="sxs-lookup"><span data-stu-id="f89c9-685">**Have a question? Ask Excel:** Now Excel Ideas allows you to ask questions about your data - no need to spend time writing formulas (available in English only).</span></span> [<span data-ttu-id="f89c9-686">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-686">Learn more</span></span>](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)

- <span data-ttu-id="f89c9-687">**Nuove immagini per dare vita alle cartelle di lavoro:** migliaia di immagini, icone e adesivi gratuiti da usare nelle cartelle di lavoro.</span><span class="sxs-lookup"><span data-stu-id="f89c9-687">**New images to bring your workbooks to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your workbooks.</span></span> <span data-ttu-id="f89c9-688">Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-688">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="f89c9-689">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-689">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="outlook"></a><span data-ttu-id="f89c9-690">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-690">Outlook</span></span>

- <span data-ttu-id="f89c9-691">**Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online.</span><span class="sxs-lookup"><span data-stu-id="f89c9-691">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="f89c9-692">Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.</span><span class="sxs-lookup"><span data-stu-id="f89c9-692">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="f89c9-693">**Nuove immagini per dare vita ai messaggi:** migliaia di immagini, icone e adesivi gratuiti da usare nei messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="f89c9-693">**New images to bring your messages to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your email messages.</span></span> <span data-ttu-id="f89c9-694">Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-694">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="f89c9-695">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-695">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

- <span data-ttu-id="f89c9-696">**Supporto suggerimenti per il luogo di una riunione ricorrente:** cercare sale riunioni con la pianificazione di riunioni ricorrenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-696">**Location suggestion support for recurring meeting:** Search for conference rooms with scheduling recurring meetings.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-697">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-697">PowerPoint</span></span>

- <span data-ttu-id="f89c9-698">**Aggiornamento delle diapositive durante la presentazione:** è possibile aggiornare le diapositive modificate da altri autori durante la presentazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-698">**Update slides during slide show:** Update slides changed by other authors during your presentation.</span></span>

- <span data-ttu-id="f89c9-699">**Nuove immagini per dare vita alle diapositive:** migliaia di immagini, icone e adesivi gratuiti da usare nelle diapositive.</span><span class="sxs-lookup"><span data-stu-id="f89c9-699">**New images to bring your slides to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your presentations.</span></span> <span data-ttu-id="f89c9-700">Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-700">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="f89c9-701">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-701">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)

### <a name="teams"></a><span data-ttu-id="f89c9-702">Teams</span><span class="sxs-lookup"><span data-stu-id="f89c9-702">Teams</span></span>

- <span data-ttu-id="f89c9-703">**Miglioramenti al calendario di Teams:** fare clic con il pulsante destro del mouse su un elemento del calendario per visualizzare le opzioni per le conferme di partecipazione, avviare una chat con i partecipanti alla riunione o partecipare rapidamente a una riunione quando inizia.</span><span class="sxs-lookup"><span data-stu-id="f89c9-703">**Improvements to the Teams calendar:** Right-click an item in your calendar to pull up RSVP options, start a chat with meeting participants, or quickly join a meeting when it starts.</span></span> <span data-ttu-id="f89c9-704">Sono stati apportati miglioramenti anche al modulo di pianificazione eventi.</span><span class="sxs-lookup"><span data-stu-id="f89c9-704">We've also made improvements to the event scheduling form.</span></span>

- <span data-ttu-id="f89c9-705">**Tag:** creare tag e assegnarli alle persone, in modo da poter @menzionare un gruppo, un ruolo, un reparto e così via. I proprietari del team possono provarli autonomamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-705">**Tag, you're it!:** Create tags and assign people to them so you can @mention a group, role, department, etc. Team owners, try it out for yourselves.</span></span> <span data-ttu-id="f89c9-706">Passare a un team, selezionare Altre opzioni, Gestisci tag.</span><span class="sxs-lookup"><span data-stu-id="f89c9-706">Go to a team, select More options, Manage tags.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-707">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-707">Word</span></span>

- <span data-ttu-id="f89c9-708">**Strumenti a portata di mano:** nella casella degli strumenti di disegno c'è la penna intelligente che consente di aggiungere gesti di input penna al testo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-708">**Keep your tools handy:** In your drawing toolbox, find the intelligent pen that allows you to add ink gestures to text.</span></span> [<span data-ttu-id="f89c9-709">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-709">Learn more</span></span>](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)

- <span data-ttu-id="f89c9-710">**Nuove immagini per dare vita ai documenti:** migliaia di immagini, icone e adesivi gratuiti da usare nei documenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-710">**New images to bring your documents to life:** Thousands of royalty-free stock images, icons, and stickers you can use in your documents.</span></span> <span data-ttu-id="f89c9-711">Per iniziare, selezionare Inserisci > Immagini > Immagini di archivio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-711">Go to Insert > Pictures > Stock Images to get started.</span></span> [<span data-ttu-id="f89c9-712">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-712">Learn more</span></span>](https://support.office.com/article/c7b78cdf-2503-4993-8664-851085c30fce)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-715">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-715">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-716">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-716">Excel</span></span>

- <span data-ttu-id="f89c9-717">Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.</span><span class="sxs-lookup"><span data-stu-id="f89c9-717">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="f89c9-718">È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="f89c9-718">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="f89c9-719">Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-719">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-720">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-720">Outlook</span></span>

- <span data-ttu-id="f89c9-721">È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="f89c9-721">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="f89c9-722">È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="f89c9-722">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="f89c9-723">È stato risolto un problema che causava l'arresto anomalo di Outlook all'apertura di file con estensione msg o oft salvati in locale dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="f89c9-723">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="f89c9-724">È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="f89c9-724">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>


- <span data-ttu-id="f89c9-725">È stato risolto un problema che causava un blocco durante la chiusura di Outlook.</span><span class="sxs-lookup"><span data-stu-id="f89c9-725">Addressed an issue that caused users to experience a hang while exiting Outlook.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-726">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-726">Project</span></span>

- <span data-ttu-id="f89c9-727">Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-727">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="f89c9-728">È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.</span><span class="sxs-lookup"><span data-stu-id="f89c9-728">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-729">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-729">Office Suite</span></span>

- <span data-ttu-id="f89c9-730">È stato risolto un errore che impedisce di limitare e proteggere i file con una password contemporaneamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-730">Resolved an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>



[//]: # (NON RIMUOVERE FINE CONTENUTO DETTAGLI DEI BUG)

## <a name="version-2003-april-15"></a><span data-ttu-id="f89c9-732">Versione 2003: 15 aprile</span><span class="sxs-lookup"><span data-stu-id="f89c9-732">Version 2003: April 15</span></span>
<span data-ttu-id="f89c9-733">*Versione 2003 (Build 12624.20466)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-733">*Version 2003 (Build 12624.20466)*</span></span>
* <span data-ttu-id="f89c9-734">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-734">Various bugs and performance fixes.</span></span>

## <a name="version-2003-april-14"></a><span data-ttu-id="f89c9-735">Versione 2003: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="f89c9-735">Version 2003: April 14</span></span>
<span data-ttu-id="f89c9-736">*Versione 2003 (Build 12624.20442)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-736">*Version 2003 (Build 12624.20442)*</span></span>

<span data-ttu-id="f89c9-737">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-737">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-739">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-739">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-740">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-740">Excel</span></span>

- <span data-ttu-id="f89c9-741">Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-741">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-742">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-742">Outlook</span></span>

- <span data-ttu-id="f89c9-743">È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="f89c9-743">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

### <a name="project"></a><span data-ttu-id="f89c9-744">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-744">Project</span></span>

- <span data-ttu-id="f89c9-745">Quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un ProjectBeforeTaskChangeevent aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-745">When Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-746">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-746">Word</span></span>

- <span data-ttu-id="f89c9-747">È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="f89c9-747">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2003-march-31"></a><span data-ttu-id="f89c9-749">Versione 2003: 31 marzo</span><span class="sxs-lookup"><span data-stu-id="f89c9-749">Version 2003: March 31</span></span>
<span data-ttu-id="f89c9-750">*Versione 2003 (Build 12624.20382)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-750">*Version 2003 (Build 12624.20382)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-752">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-752">Resolved issues</span></span>
### <a name="onenote"></a><span data-ttu-id="f89c9-753">OneNote</span><span class="sxs-lookup"><span data-stu-id="f89c9-753">OneNote</span></span>

- <span data-ttu-id="f89c9-754">Informazioni per gli utenti tramite la Barra informazioni sulle rettifiche temporanee in Microsoft OneNote che consentono di migliorare la sincronizzazione e la disponibilità dei servizi durante i picchi di utilizzo in tutto il mondo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-754">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

### <a name="project"></a><span data-ttu-id="f89c9-755">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-755">Project</span></span>

- <span data-ttu-id="f89c9-756">È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-756">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO DEI BUG)

## <a name="version-2003-march-25"></a><span data-ttu-id="f89c9-758">Versione 2003: 25 marzo</span><span class="sxs-lookup"><span data-stu-id="f89c9-758">Version 2003: March 25</span></span>
<span data-ttu-id="f89c9-759">*Versione 2003 (Build 12624.20320)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-759">*Version 2003 (Build 12624.20320)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-761">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-761">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-762">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-762">Excel</span></span>

- <span data-ttu-id="f89c9-763">**Le tue funzioni Excel preferite sono diventate più veloci:** le funzioni SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS e MINIFS sono più veloci che mai.</span><span class="sxs-lookup"><span data-stu-id="f89c9-763">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="f89c9-764">Passa alla riga inferiore più rapidamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-764">Get to the bottom line more quickly.</span></span> <span data-ttu-id="f89c9-765">Provane una ora.</span><span class="sxs-lookup"><span data-stu-id="f89c9-765">Try one now.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-766">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-766">Outlook</span></span>

- <span data-ttu-id="f89c9-767">**Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-767">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="f89c9-768">I messaggi trascinati verranno condivisi con tutti i membri del gruppo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-768">Messages you drag will be shared with all group members.</span></span>

- <span data-ttu-id="f89c9-769">**Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web?</span><span class="sxs-lookup"><span data-stu-id="f89c9-769">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="f89c9-770">Outlook ora consente di rimanere connessi in scenari di questo tipo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-770">Outlook now detects this and helps you get connected.</span></span>

###<a name="powerpoint"></a><span data-ttu-id="f89c9-771">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-771">PowerPoint</span></span>

- <span data-ttu-id="f89c9-772">**Commenti:** la nuova esperienza di commento in PowerPoint consente di individuare e aggiungere i commenti ai documenti in modo semplice e rapido.</span><span class="sxs-lookup"><span data-stu-id="f89c9-772">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="f89c9-773">Modernizzare i flussi di lavoro di collaborazione con le nuove funzionalità, ad esempio l'ancoraggio di commenti, la risoluzione, le attività, le notifiche di menzione migliorate e molto altro.</span><span class="sxs-lookup"><span data-stu-id="f89c9-773">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-774">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-774">Word</span></span>

- <span data-ttu-id="f89c9-775">**Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.</span><span class="sxs-lookup"><span data-stu-id="f89c9-775">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-776">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-776">Office Suite</span></span>

- <span data-ttu-id="f89c9-777">**Etichette di riservatezza** : è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="f89c9-777">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-780">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-780">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-781">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-781">Excel</span></span>

- <span data-ttu-id="f89c9-782">In alcuni casi, Excel si arrestava in modo anomalo alla riapertura di una cartella di lavoro incorporata in Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-782">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="f89c9-783">È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.</span><span class="sxs-lookup"><span data-stu-id="f89c9-783">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="f89c9-784">È stato risolto un problema di prestazioni durante la creazione di grafici dai modelli.</span><span class="sxs-lookup"><span data-stu-id="f89c9-784">Addressed a performance issue when creating charts from templates.</span></span>

### <a name="onenote"></a><span data-ttu-id="f89c9-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="f89c9-785">OneNote</span></span>

- <span data-ttu-id="f89c9-786">Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-786">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB.</span></span> <span data-ttu-id="f89c9-787">Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.</span><span class="sxs-lookup"><span data-stu-id="f89c9-787">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="f89c9-788">Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="f89c9-788">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-789">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-789">Outlook</span></span>

- <span data-ttu-id="f89c9-790">È stato risolto un problema che causava la visualizzazione del processo di Outlook in esecuzione in Gestione attività dopo la chiusura.</span><span class="sxs-lookup"><span data-stu-id="f89c9-790">Addressed an issue that caused users to see the Outlook process lingering in task manager after exiting.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-791">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-791">PowerPoint</span></span>

- <span data-ttu-id="f89c9-792">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-792">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-793">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-793">Project</span></span>

- <span data-ttu-id="f89c9-794">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.</span><span class="sxs-lookup"><span data-stu-id="f89c9-794">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="f89c9-795">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="f89c9-795">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="f89c9-796">È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.</span><span class="sxs-lookup"><span data-stu-id="f89c9-796">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="f89c9-797">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="f89c9-797">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a><span data-ttu-id="f89c9-799">Versione 2002: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="f89c9-799">Version 2002: March 10</span></span>
<span data-ttu-id="f89c9-800">*Versione 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-800">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="f89c9-801">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-801">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-803">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-803">Feature updates</span></span>
### <a name="powerpoint"></a><span data-ttu-id="f89c9-804">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-804">PowerPoint</span></span>

- <span data-ttu-id="f89c9-805">**Collegamento a una diapositiva:** è possibile chiedere a un collega di contribuire a una presentazione e indirizzalo direttamente alla diapositiva per la quale serve assistenza.</span><span class="sxs-lookup"><span data-stu-id="f89c9-805">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-808">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-808">Resolved issues</span></span>
### <a name="project"></a><span data-ttu-id="f89c9-809">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-809">Project</span></span>

- <span data-ttu-id="f89c9-810">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="f89c9-810">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-01"></a><span data-ttu-id="f89c9-812">Versione 2002: 1 marzo</span><span class="sxs-lookup"><span data-stu-id="f89c9-812">Version 2002: March 01</span></span>
<span data-ttu-id="f89c9-813">*Versione 2002 (Build 12527.20242)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-813">*Version 2002 (Build 12527.20242)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-815">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-815">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="f89c9-816">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-816">Outlook</span></span>

- <span data-ttu-id="f89c9-817">È stato risolto un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="f89c9-817">Addresses an issue that caused third party applications to be unable to send email.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-25"></a><span data-ttu-id="f89c9-819">Versione 2002: 25 febbraio</span><span class="sxs-lookup"><span data-stu-id="f89c9-819">Version 2002: February 25</span></span>
<span data-ttu-id="f89c9-820">*Versione 2002 (Build 12527.20194)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-820">*Version 2002 (Build 12527.20194)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-822">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-822">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-823">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-823">Excel</span></span>

- <span data-ttu-id="f89c9-824">**Statistiche della cartella di lavoro:** Celle, formule, grafici, tabelle... Li contiamo noi al tuo posto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-824">**Workbook Statistics:** Cells, formulas, charts, tables... We count them so you don't have to.</span></span>

- <span data-ttu-id="f89c9-825">**Profiling dei dati nell'editor di query:** Ottenere un'analisi a colpo d'occhio dei dati nelle colonne, identificare gli errori e i valori vuoti, vedere gli istogrammi di distribuzione e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="f89c9-825">**Data Profiling in Query Editor:** Get at-a-glance analysis of the data in your columns, identify error and empty values, see distribution histograms and more.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-828">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-828">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-829">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-829">Excel</span></span>

- <span data-ttu-id="f89c9-830">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-830">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-831">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-831">Outlook</span></span>

- <span data-ttu-id="f89c9-832">Risolto un problema per cui la virgola nel campo Luogo della riunione cambiava in punto e virgola.</span><span class="sxs-lookup"><span data-stu-id="f89c9-832">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="f89c9-833">Risolto un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.</span><span class="sxs-lookup"><span data-stu-id="f89c9-833">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="f89c9-834">È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.</span><span class="sxs-lookup"><span data-stu-id="f89c9-834">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="f89c9-835">Risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.</span><span class="sxs-lookup"><span data-stu-id="f89c9-835">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>


- <span data-ttu-id="f89c9-836">Risolto un problema per cui gli utenti con il tema Nero visualizzavano l'elenco a discesa "Da" con il testo bianco su sfondo bianco.</span><span class="sxs-lookup"><span data-stu-id="f89c9-836">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>


- <span data-ttu-id="f89c9-837">Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.</span><span class="sxs-lookup"><span data-stu-id="f89c9-837">This change restores the ability to view multi-line subjects in the message header.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-february-19"></a><span data-ttu-id="f89c9-839">Versione 2001: 19 febbraio</span><span class="sxs-lookup"><span data-stu-id="f89c9-839">Version 2001: February 19</span></span>
<span data-ttu-id="f89c9-840">*Versione 2001 (Build 12430.20288)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-840">*Version 2001 (Build 12430.20288)*</span></span>
* <span data-ttu-id="f89c9-841">Diverse correzioni di bug e miglioramenti delle prestazioni.</span><span class="sxs-lookup"><span data-stu-id="f89c9-841">Various bugs and performance fixes.</span></span>

## <a name="version-2001-february-11"></a><span data-ttu-id="f89c9-842">Versione 2001: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="f89c9-842">Version 2001: February 11</span></span>
<span data-ttu-id="f89c9-843">*Versione 2001 (Build 12430.20264)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-843">*Version 2001 (Build 12430.20264)*</span></span>

<span data-ttu-id="f89c9-844">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-844">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-846">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-846">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-847">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-847">Access</span></span>

- <span data-ttu-id="f89c9-848">I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database.</span><span class="sxs-lookup"><span data-stu-id="f89c9-848">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="f89c9-849">Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.</span><span class="sxs-lookup"><span data-stu-id="f89c9-849">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="f89c9-850">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-850">Excel</span></span>

- <span data-ttu-id="f89c9-851">È stato risolto un problema i comandi di commento nel menu di scelta rapida non venivano visualizzati.</span><span class="sxs-lookup"><span data-stu-id="f89c9-851">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="f89c9-852">È stato risolto un problema che causava arresti anomali convertendo il testo in colonne con celle con una matrice con espansione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-852">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-853">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-853">Outlook</span></span>

- <span data-ttu-id="f89c9-854">Risolve un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="f89c9-854">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>


- <span data-ttu-id="f89c9-855">Risolve un problema che causava un arresto anomalo annullando la configurazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="f89c9-855">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>


### <a name="project"></a><span data-ttu-id="f89c9-856">Project</span><span class="sxs-lookup"><span data-stu-id="f89c9-856">Project</span></span>

- <span data-ttu-id="f89c9-857">È stato risolto un problema per cui il 100% delle attività di tipo durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.</span><span class="sxs-lookup"><span data-stu-id="f89c9-857">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>


### <a name="office-suite"></a><span data-ttu-id="f89c9-858">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-858">Office Suite</span></span>

- <span data-ttu-id="f89c9-859">Questo cambiamento affronta i problemi segnalati con le schede grafiche che utilizzano le GPU integrate Intel.</span><span class="sxs-lookup"><span data-stu-id="f89c9-859">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2001-january-30"></a><span data-ttu-id="f89c9-861">Versione 2001: 30 gennaio</span><span class="sxs-lookup"><span data-stu-id="f89c9-861">Version 2001: January 30</span></span>
<span data-ttu-id="f89c9-862">*Versione 2001 (build 12430.20184)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-862">*Version 2001 (Build 12430.20184)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-864">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-864">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-865">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-865">Excel</span></span>

- <span data-ttu-id="f89c9-866">**Leggere e rispondere all'istante:** Rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="f89c9-866">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="f89c9-867">**Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X.</span><span class="sxs-lookup"><span data-stu-id="f89c9-867">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="f89c9-868">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-868">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)

### <a name="outlook"></a><span data-ttu-id="f89c9-869">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-869">Outlook</span></span>

- <span data-ttu-id="f89c9-870">**Impostazioni avanzate della posta elettronica del gruppo:** questa funzionalità consente a gruppi di utenti di personalizzare i messaggi di posta elettronica o gli eventi da ricevere/seguire nella Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-870">**Advanced group email settings:** This feature helps groups users to customize which emails or events to receive/follow in their inbox.</span></span>

- <span data-ttu-id="f89c9-871">**Criteri di denominazione dei gruppi:** i criteri di denominazione dei gruppi consentono all'amministratore IT di standardizzare e gestire i nomi dei gruppi creati dagli utenti nell'organizzazione.</span><span class="sxs-lookup"><span data-stu-id="f89c9-871">**Groups Naming policy:** A group naming policy enables the IT admin to standardize and manage the names of groups created by users in the organization.</span></span> <span data-ttu-id="f89c9-872">L'amministratore può richiedere l'aggiunta di un prefisso e un suffisso specifici al nome per un gruppo al momento della creazione e può impedire l'utilizzo di parole specifiche.</span><span class="sxs-lookup"><span data-stu-id="f89c9-872">The admin can require a specific prefix and suffix be added to the name for a group when it's created, and can block specific words from being used.</span></span> <span data-ttu-id="f89c9-873">Questo consente di ridurre al minimo l'uso di parole inappropriate nei nomi dei gruppi e di gestire la rappresentazione dei gruppi nella directory.</span><span class="sxs-lookup"><span data-stu-id="f89c9-873">This helps minimize the use of inappropriate words in group names as well as IT manage the representation of groups in their directory.</span></span> <span data-ttu-id="f89c9-874">I criteri di denominazione, inoltre, consentono alle organizzazioni che distribuiscono siti del team di categorizzarli in base al reparto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-874">Naming Policy also helps organizations that deploy team sites to categorize them based on department.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-875">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-875">Word</span></span>

- <span data-ttu-id="f89c9-876">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="f89c9-876">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="f89c9-877">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-877">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="f89c9-878">**Lazo dell'input penna:** lo strumento Lazo della scheda Disegno consente di selezionare gli oggetti disegnati con l'input penna.</span><span class="sxs-lookup"><span data-stu-id="f89c9-878">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="f89c9-879">È possibile selezionare singoli tratti o parole intere.</span><span class="sxs-lookup"><span data-stu-id="f89c9-879">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="f89c9-880">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-880">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)






[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-883">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-883">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-884">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-884">Access</span></span>

- <span data-ttu-id="f89c9-885">Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB.</span><span class="sxs-lookup"><span data-stu-id="f89c9-885">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="f89c9-886">L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.</span><span class="sxs-lookup"><span data-stu-id="f89c9-886">Recorder object in VB code may incorrectly report an error.</span></span>


- <span data-ttu-id="f89c9-887">Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-887">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>


### <a name="excel"></a><span data-ttu-id="f89c9-888">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-888">Excel</span></span>

- <span data-ttu-id="f89c9-889">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="f89c9-889">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


### <a name="outlook"></a><span data-ttu-id="f89c9-890">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-890">Outlook</span></span>

- <span data-ttu-id="f89c9-891">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="f89c9-891">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-22"></a><span data-ttu-id="f89c9-893">Versione 1912: 22 gennaio</span><span class="sxs-lookup"><span data-stu-id="f89c9-893">Version 1912: January 22</span></span>
<span data-ttu-id="f89c9-894">*Versione 1912 (Build 12325.20344)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-894">*Version 1912 (Build 12325.20344)*</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-896">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-896">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="f89c9-897">Access</span><span class="sxs-lookup"><span data-stu-id="f89c9-897">Access</span></span>

- <span data-ttu-id="f89c9-898">Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="f89c9-898">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1912-january-14"></a><span data-ttu-id="f89c9-900">Versione 1912: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="f89c9-900">Version 1912: January 14</span></span>
<span data-ttu-id="f89c9-901">*Versione 1912 (Build 12325.20298)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-901">*Version 1912 (Build 12325.20298)*</span></span>

<span data-ttu-id="f89c9-902">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="f89c9-902">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1912-january-08"></a><span data-ttu-id="f89c9-903">Versione 1912: 8 gennaio</span><span class="sxs-lookup"><span data-stu-id="f89c9-903">Version 1912: January 08</span></span>
<span data-ttu-id="f89c9-904">*Versione 1912 (Build 12325.20288)*</span><span class="sxs-lookup"><span data-stu-id="f89c9-904">*Version 1912 (Build 12325.20288)*</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="f89c9-906">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="f89c9-906">Feature updates</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-907">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-907">Outlook</span></span>

- <span data-ttu-id="f89c9-908">**Invio di messaggi accessibili a chi ne ha bisogno:** in Outlook viene visualizzato un suggerimento per i messaggi che consente di assicurarne l'accessibilità dei contenuti durante l'invio a un utente che preferisce contenuti accessibili</span><span class="sxs-lookup"><span data-stu-id="f89c9-908">**Send accessible mail to those who need it most:** Outlook will display a mail tip to help you ensure that your content is accessible when sending to a user who prefers accessible content</span></span>

### <a name="powerpoint"></a><span data-ttu-id="f89c9-909">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="f89c9-909">PowerPoint</span></span>

- <span data-ttu-id="f89c9-910">**Ottimizzazione della presentazione per tutti:** Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="f89c9-910">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="f89c9-911">**GIF in un batter d'occhio:** una diapositiva, un frame.</span><span class="sxs-lookup"><span data-stu-id="f89c9-911">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="f89c9-912">Crea facilmente GIF a ripetizione continua in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="f89c9-912">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="f89c9-913">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="f89c9-913">Learn more</span></span>](https://support.office.com/it-IT/article/a598753e-92de-4f1b-8393-714db4d334b4)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="f89c9-916">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="f89c9-916">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="f89c9-917">Excel</span><span class="sxs-lookup"><span data-stu-id="f89c9-917">Excel</span></span>

- <span data-ttu-id="f89c9-918">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="f89c9-918">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

### <a name="outlook"></a><span data-ttu-id="f89c9-919">Outlook</span><span class="sxs-lookup"><span data-stu-id="f89c9-919">Outlook</span></span>

- <span data-ttu-id="f89c9-920">È stato risolto un problema per cui il luogo di una riunione veniva inaspettatamente aggiunto di nuovo alla riunione dopo che era stato cancellato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-920">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="f89c9-921">È stato risolto un problema che causava un considerevole ritardo quando si interagiva con le cartelle delle cassette postali degli utenti usando i tasti di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="f89c9-921">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="f89c9-922">È stato risolto un problema per cui gli utenti vedevano i messaggi di posta elettronica inviati a un indirizzo che in alcuni casi non corrispondeva all'indirizzo SMTP visualizzato.</span><span class="sxs-lookup"><span data-stu-id="f89c9-922">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="f89c9-923">È stato risolto un problema che causava blocchi utente in Outlook durante il recupero delle impostazioni del cloud.</span><span class="sxs-lookup"><span data-stu-id="f89c9-923">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

### <a name="word"></a><span data-ttu-id="f89c9-924">Word</span><span class="sxs-lookup"><span data-stu-id="f89c9-924">Word</span></span>

- <span data-ttu-id="f89c9-925">Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: "Sono stati modificati gli stili, i blocchi predefiniti".</span><span class="sxs-lookup"><span data-stu-id="f89c9-925">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="f89c9-926">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="f89c9-926">Office Suite</span></span>

- <span data-ttu-id="f89c9-927">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="f89c9-927">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> <span data-ttu-id="f89c9-929">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="f89c9-929">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>

[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|CC|Production| |16.0.13328.20292|version-2010-october-27|)
[//]: # (|Win32|CC|Production| |16.0.13231.20418|version-2009-october-21|)
[//]: # (|Win32|CC|Production| |16.0.13231.20390|version-2009-october-13|)
[//]: # (|Win32|CC|Production| |16.0.13231.20368|version-2009-ottobre-08|)
[//]: # (|Win32|CC|Production| |16.0.13231.20262|version-2009-settembre-28|)
[//]: # (|Win32|CC|Production| |16.0.13127.20508|versione-2008-settembre-22|)
[//]: # (|Win32|CC|Production| |16.0.13127.20408|versione-2008-settembre-09|)
[//]: # (|Win32|CC|Production| |16.0.13127.20296|version-2008-august-31|)
[//]: # (|Win32|CC|Production| |16.0.13029.20460|version-2007-august-25|)
[//]: # (|Win32|CC|Production| |16.0.13029.20344|version-2007-august-11|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
