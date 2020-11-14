---
title: Note sulla versione per i rilasci del Canale Enterprise semestrale (Anteprima) nel 2020
ms.author: anankani
author: andymosten
manager: anankani
ms.audience: ITPro
ms.topic: reference
ms.service: o365-proplus-itpro
localization_priority: Critical
ms.collection: RelNotes_ProPlus
description: Informazioni per i professionisti IT con le note sulla versione per i rilasci del Canale semestrale (mirato) per Microsoft 365 Apps nel 2020
ms.openlocfilehash: e448b5e1d0ea334401c9bd9c91291376f6579367
ms.sourcegitcommit: 8e74984d0c36475374c34e76ed29c5d1ad81d971
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 11/10/2020
ms.locfileid: "48990055"
---
# <a name="release-notes-for-semi-annual-enterprise-channel-preview-releases-in-2020"></a><span data-ttu-id="9ccd6-103">Note sulla versione per i rilasci del Canale Enterprise semestrale (Anteprima) nel 2020</span><span class="sxs-lookup"><span data-stu-id="9ccd6-103">Release notes for Semi-Annual Enterprise Channel (Preview) releases in 2020</span></span>

<span data-ttu-id="9ccd6-104">Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale Enterprise semestrale (Anteprima) del 2020 per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel (Preview) updates in 2020 for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="9ccd6-p101">Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Canale Enterprise mensile) e la modifica dei nomi dei canali di aggiornamento già presenti. Per ulteriori informazioni, [leggere questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span><span class="sxs-lookup"><span data-stu-id="9ccd6-p101">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels. To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>


## <a name="version-2008-november-10"></a><span data-ttu-id="9ccd6-107">Versione 2008: 10 novembre</span><span class="sxs-lookup"><span data-stu-id="9ccd6-107">Version 2008: November 10</span></span>
<span data-ttu-id="9ccd6-108">*La versione prevista è la numero 2008 (Build 13127.20760).*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-108">*Version 2008 (Build 13127.20760)*</span></span>

<span data-ttu-id="9ccd6-109">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-109">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-111">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-111">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9ccd6-112">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-112">Excel</span></span>

- <span data-ttu-id="9ccd6-113">È stato risolto un problema per cui alcune funzioni avrebbero avuto un risultato errato dopo il caricamento di una cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-113">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="9ccd6-114">È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto, correlato ai riferimenti del componente aggiuntivo XLAM e agli intervalli denominati.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-114">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="9ccd6-115">È stato risolto un problema relativo all'uso di una macro per impostare la proprietà FormulaR1C1 per un intervallo. I riferimenti di cella erano errati se un foglio grafico era il foglio attivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-115">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="9ccd6-116">È stato risolto un problema che causava la visualizzazione del messaggio "Excel ha esaurito le risorse durante il tentativo di calcolare una o più formule".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-116">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="9ccd6-117">È stato risolto un problema per cui, quando si selezionava lo spagnolo come lingua di Office, gli elenchi di convalida dei dati non mostravano tutti gli elementi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-117">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="9ccd6-118">È stato risolto un problema che poteva causare un blocco durante l'aggiornamento delle tabelle pivot OLAP.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-118">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-119">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-119">Outlook</span></span>

- <span data-ttu-id="9ccd6-120">È stato risolto un problema per cui gli utenti ora possono disabilitare IRM (Information Rights Management) per Outlook senza doverlo disabilitare per il resto delle applicazioni di Office.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-120">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="9ccd6-121">È stato risolto un problema che impediva agli utenti di concedere le autorizzazioni di Editor ai delegati.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-121">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="9ccd6-122">È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto se gli utenti selezionavano un risultato della ricerca.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-122">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="9ccd6-123">È stato risolto un problema per cui le ricerche nei calendari di gruppo non restituivano alcun risultato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-123">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="9ccd6-124">È stato risolto un problema che provocava errori intermittenti quando i delegati aprivano cartelle condivise in altre cassette postali.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-124">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="9ccd6-125">È stato risolto un problema che ha causato l'invio di messaggi di posta elettronica generati automaticamente con un corpo vuoto quando la riga dell'oggetto è vuota.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-125">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="9ccd6-126">È stato risolto un problema per cui le intestazioni dei messaggi in cinese erano incomprensibili in caso di risposta o inoltro.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-126">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>

- <span data-ttu-id="9ccd6-127">È stato risolto un problema per cui le esperienze connesse facoltative bloccavano il caricamento dei componenti aggiuntivi Web.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-127">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <br /><span data-ttu-id="9ccd6-128">Vedere i dettagli nel [post di blog](https://developer.microsoft.com/it-IT/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-128">See details in [blog post](https://developer.microsoft.com/it-IT/office/blogs/outlook-add-ins-and-optional-connected-experiences/)</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9ccd6-129">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-129">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-130">È stato risolto un problema per cui il componente aggiuntivo per i contenuti Forms non veniva eseguito dopo l'inserimento finché l'utente non faceva clic su un'altra diapositiva per visualizzarlo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-130">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9ccd6-131">Famiglia di prodotti di Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-131">Office Suite</span></span>

- <span data-ttu-id="9ccd6-132">È stato risolto un problema per i clienti commerciali che usano System Center Configuration Manager o altri strumenti di gestione per l'aggiornamento di Office tramite Prevenzione della perdita di dati degli endpoint di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-132">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>

- <span data-ttu-id="9ccd6-133">Risolve un problema relativo al non funzionamento dell'API di messaggistica per i componenti aggiuntivi di Office.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-133">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO BUG)

## <a name="version-2008-october-13"></a><span data-ttu-id="9ccd6-135">Versione 2008: 13 ottobre</span><span class="sxs-lookup"><span data-stu-id="9ccd6-135">Version 2008: October 13</span></span>
<span data-ttu-id="9ccd6-136">*Versione 2008 (Build 13127.20638)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-136">*Version 2008 (Build 13127.20638)*</span></span>

<span data-ttu-id="9ccd6-137">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-139">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-139">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-140">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-140">Excel</span></span>

- <span data-ttu-id="9ccd6-141">È stato corretto un bug relativo alle API PivotDateFilter, per cui le condizioni di filtro "prima" e "dopo" erano invertite.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-141">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="9ccd6-142">È stato risolto un problema che impediva agli utenti di modificare un filtro della tabella pivot perché era configurato su un valore non più presente nel database Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-142">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="9ccd6-143">È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo quando si utilizzava l'Analisi rapida dopo aver bloccato la riga superiore del foglio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-143">Fixed an issue where Excel could crash when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="9ccd6-144">È stato risolto un problema che poteva generare un avviso su una cartella di lavoro danneggiata se conteneva formule utilizzando IFNA ().</span><span class="sxs-lookup"><span data-stu-id="9ccd6-144">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


### <a name="outlook"></a><span data-ttu-id="9ccd6-145">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-145">Outlook</span></span>

- <span data-ttu-id="9ccd6-146">Risolve un problema che impediva agli utenti di chiudere i calendari condivisi facendo clic sulla "X" nell'angolo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-146">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="9ccd6-147">È stato risolto un problema per cui l'impostazione "Attiva miglioramenti calendari condivisi " talvolta non veniva applicata ai calendari condivisi esistenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-147">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="9ccd6-148">È stato risolto un problema per cui, all'apertura di un allegato cloud, gli utenti visualizzavano un messaggio di errore nella pagina Safelinks anziché il documento che stavano provando ad aprire.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-148">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="9ccd6-149">Risolve un problema relativo alle prestazioni con il caricamento degli allegati.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-149">Addresses a performance issue with attachment upload.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9ccd6-150">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-150">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-151">Questa modifica risolve un problema della funzionalità Esporta in GIF animata per cui, facendo clic sul pulsante Esporta, l'esportazione non veniva eseguita.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-151">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="9ccd6-152">Correzione di sicurezza che risolve un problema che disabilitava le protezioni IRM aprendo un file di PowerPoint in Visualizzazione protetta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-152">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>

- <span data-ttu-id="9ccd6-153">È stato risolto un problema nella finestra di dialogo Impostazioni azione che causava un arresto anomalo dell'app PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-153">We have fixed an issue in Action Settings dialog which was causing a crash in PowerPoint app.</span></span>

### <a name="visio"></a><span data-ttu-id="9ccd6-154">Visio</span><span class="sxs-lookup"><span data-stu-id="9ccd6-154">Visio</span></span>

- <span data-ttu-id="9ccd6-155">È stato risolto un problema che causava l'arresto anomalo dell'anteprima live durante l'allineamento del testo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-155">We fixed an issue that caused the Live preview to crash on text alignment.</span></span>


### <a name="word"></a><span data-ttu-id="9ccd6-156">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-156">Word</span></span>

- <span data-ttu-id="9ccd6-157">È stato risolto un problema che causava l'arresto anomalo all'apertura di alcuni messaggi di posta elettronica molto grandi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-157">Fixes an issue that caused users to experience a crash when opening certain very large emails.</span></span>


- <span data-ttu-id="9ccd6-158">È stato risolto un problema per cui poteva verificarsi un arresto anomalo all'apertura di un documento.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-158">We fixed an issue which user might experience crash when opening a document.</span></span>


- <span data-ttu-id="9ccd6-159">È stato risolto un problema che poteva causare un arresto anomalo all'avvio di Word.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-159">Resolved an issue that may have caused a crash when booting Word.</span></span>


- <span data-ttu-id="9ccd6-160">È stato risolto un problema con la finestra di dialogo raccolta Stili.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-160">We fixed an issue with Style Gallery dialog.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9ccd6-161">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-161">Office Suite</span></span>

- <span data-ttu-id="9ccd6-162">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-162">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="9ccd6-163">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-163">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="9ccd6-164">È stato risolto un problema che causava un utilizzo elevato della CPU in modalità inattiva con GIF/modelli animati 3D</span><span class="sxs-lookup"><span data-stu-id="9ccd6-164">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="9ccd6-165">Questa modifica risolve il problema dell'arresto anomalo all'avvio delle app Office dovuto al mancato caricamento del file d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-165">This change addresses a crash when launching Office apps due to failing to load d2d1.dll.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-september-08"></a><span data-ttu-id="9ccd6-167">Versione 2008: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="9ccd6-167">Version 2008: September 08</span></span>
<span data-ttu-id="9ccd6-168">*Versione 2008 (Build 13127.20408)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-168">*Version 2008 (Build 13127.20408)*</span></span>

<span data-ttu-id="9ccd6-169">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-169">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9ccd6-171">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="9ccd6-171">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9ccd6-172">Accesso</span><span class="sxs-lookup"><span data-stu-id="9ccd6-172">Access</span></span>

- <span data-ttu-id="9ccd6-173">**Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-173">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="9ccd6-174">Cercare e sostituire il testo nella visualizzazione SQL.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-174">Search and replace text in SQL View.</span></span> <span data-ttu-id="9ccd6-175">Selezionare più tabelle nella finestra Relazioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-175">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="9ccd6-176">**Aggiungere tabelle con meno clic** : usare il riquadro attività Aggiungere tabelle, che resta aperto mentre si lavora, per aggiungere tabelle a relazioni e query.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-176">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="9ccd6-177">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-177">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="9ccd6-178">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-178">Excel</span></span>

- <span data-ttu-id="9ccd6-179">**Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-179">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="9ccd6-180">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-180">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="9ccd6-181">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-181">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9ccd6-182">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-182">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9ccd6-183">**Creare tabelle pivot da set di documenti in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di documenti archiviati in Power BI in pochi click.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-183">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="9ccd6-184"> Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-184">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="9ccd6-185">Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-185">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="9ccd6-186">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-186">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="9ccd6-187">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-187">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

- <span data-ttu-id="9ccd6-188">**Le tue funzioni Excel preferite sono diventate più veloci:** le funzioni SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS e MINIFS sono più veloci che mai.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-188">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="9ccd6-189">Passa alla riga inferiore più rapidamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-189">Get to the bottom line more quickly.</span></span> <span data-ttu-id="9ccd6-190">Provane una ora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-190">Try one now.</span></span>

- <span data-ttu-id="9ccd6-191">**Miglioramenti di RealTimeData (RTD):** in Office 365 versione 2002 canale mensile e successiva, la funzione RealTimeData (RTD) di Excel è molto più veloce rispetto a Excel 2010 per il calcolo dei dati nel foglio di calcolo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-191">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="9ccd6-192">Sono stati rimossi i colli di bottiglia nelle strutture di memoria e di dati sottostanti oltre a renderlo thread-safe per consentirne il calcolo su tutti i thread disponibili di ricalcolo multithread (MTR).</span><span class="sxs-lookup"><span data-stu-id="9ccd6-192">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-193">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-193">Outlook</span></span>

- <span data-ttu-id="9ccd6-194">**Gli aggiornamenti dei calendari condivisi sono più veloci:** Outlook può aggiornare i calendari condivisi in Office 365 usando l'API REST.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-194">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="9ccd6-195">Attivare l'anteprima per aggiornamenti più rapidi e affidabili ai calendari condivisi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-195">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="9ccd6-196">**Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-196">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="9ccd6-197">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-197">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

- <span data-ttu-id="9ccd6-198">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-198">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9ccd6-199">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-199">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9ccd6-200">**Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-200">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="9ccd6-201">I messaggi trascinati verranno condivisi con tutti i membri del gruppo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-201">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="9ccd6-202">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-202">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="9ccd6-203">**Aggiornamento del calendario:** aggiornamenti visivi che rendono il calendario più facile da analizzare.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-203">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="9ccd6-204">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-204">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="9ccd6-205">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-205">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="9ccd6-206">**Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-206">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="9ccd6-207">Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-207">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span>

- <span data-ttu-id="9ccd6-208">**Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web?</span><span class="sxs-lookup"><span data-stu-id="9ccd6-208">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="9ccd6-209">Outlook ora consente di rimanere connessi in scenari di questo tipo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-209">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="9ccd6-210">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-210">See details in [blog post](https://insider.office.com/it-IT/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="9ccd6-211">**Suggerimenti di posta elettronica per cercare una persona:** quando si digita il nome di una persona nella casella di ricerca, i messaggi di posta elettronica più importanti saranno inclusi nei suggerimenti di ricerca.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-211">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="9ccd6-212">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-212">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

### <a name="powerpoint"></a><span data-ttu-id="9ccd6-213">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-213">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-214">**Ottenere l'attenzione tramite \@menzioni:** è possibile usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-214">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="9ccd6-215">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-215">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="9ccd6-216">**Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-216">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="9ccd6-217">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-217">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="9ccd6-218">**GIF in un batter d'occhio:** una diapositiva, un frame.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-218">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="9ccd6-219">Crea facilmente GIF a ripetizione continua in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-219">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="9ccd6-220">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-220">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="9ccd6-221">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-221">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="9ccd6-222">**Diagrammi migliori:** connettori più efficienti e un processo di conversione dell'input penna più fluido consentono di dare forma alle idee più facilmente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-222">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="9ccd6-223">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-223">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="9ccd6-224">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-224">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9ccd6-225">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-225">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9ccd6-226">**Commenti:** la nuova esperienza di commento in PowerPoint consente di individuare e aggiungere i commenti ai documenti in modo semplice e rapido.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-226">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="9ccd6-227">È possibile modernizzare i flussi di lavoro di collaborazione con nuove funzionalità, come l'ancoraggio di commenti, la risoluzione, le attività, le notifiche di menzione migliorate e molto altro.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-227">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="9ccd6-228">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-228">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

- <span data-ttu-id="9ccd6-229">**Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-229">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="9ccd6-230">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-230">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="9ccd6-231">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-231">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="9ccd6-232">**Collegamento a una diapositiva:** è possibile chiedere a un collega di contribuire a una presentazione e indirizzalo direttamente alla diapositiva per la quale serve assistenza.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-232">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="9ccd6-233">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-233">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="9ccd6-234">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-234">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="9ccd6-235">**Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-235">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="9ccd6-236">I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-236">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>


### <a name="word"></a><span data-ttu-id="9ccd6-237">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-237">Word</span></span>

- <span data-ttu-id="9ccd6-238">**Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-238">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="9ccd6-239">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-239">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="9ccd6-240">**Lazo dell'input penna:** lo strumento Lazo della scheda Disegno consente di selezionare gli oggetti disegnati con l'input penna.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-240">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="9ccd6-241">È possibile selezionare singoli tratti o parole intere.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-241">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="9ccd6-242">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-242">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="9ccd6-243">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-243">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="9ccd6-244">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-244">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="9ccd6-245">**Conferma dell'azione nelle utilità per la lettura dello schermo:** la conferma dell'azione rappresenta un requisito importante per l'accessibilità.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-245">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="9ccd6-246">Con l'introduzione di una nuova API di notifica di Windows, è ora possibile avvisare gli utenti delle utilità per la lettura dello schermo della riuscita delle azioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-246">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="9ccd6-247">I comandi taglia, copia, incolla, grassetto, corsivo, sottolineato, annulla, ripristina, correzione automatica e maiuscole automatiche ora sono tutti annunciati agli utenti dell'Assistente vocale in Win32 Word.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-247">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="9ccd6-248">Per abilitare questa funzionalità, attivare l'Assistente vocale premendo il tasto Windows + CTRL + INVIO.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-248">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="9ccd6-249">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-249">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-250">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-250">Office Suite</span></span>

- <span data-ttu-id="9ccd6-251">**Etichette di riservatezza** : è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-251">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-254">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-254">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9ccd6-255">Access</span><span class="sxs-lookup"><span data-stu-id="9ccd6-255">Access</span></span>

- <span data-ttu-id="9ccd6-256">È stato risolto un problema relativo all'inserimento di tabelle SQL collegate che includono un campo identità, ad esempio numerazione automatica.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-256">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>

- <span data-ttu-id="9ccd6-257">È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-257">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>

- <span data-ttu-id="9ccd6-258">È stato risolto un problema per cui ora è possibile usare il tipo di dati data/ora esteso nel codice senza subire alcun arresto anomalo dell'app.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-258">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any crash in your app.</span></span>

- <span data-ttu-id="9ccd6-259">È stato risolto un problema che consente ora di tornare alla versione di Access più aggiornata e usare DAO/VBA per gestire e modificare un tipo di dati decimale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-259">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>

- <span data-ttu-id="9ccd6-260">Questa correzione risolve il problema per cui il tentativo di eseguire determinate query in precedenza generava il messaggio di errore 'La query è troppo complessa.'</span><span class="sxs-lookup"><span data-stu-id="9ccd6-260">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>

- <span data-ttu-id="9ccd6-261">Il problema è ora risolto per Access, ma analizzeremo le nostre altre interfacce per garantire che il problema non persista.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-261">Access has fixed this current issue, but will be investigating our additional interfaces to ensure that this problem does not persist.</span></span> <span data-ttu-id="9ccd6-262">Il team notificherà i prossimi aggiornamenti; apprezziamo la vostra pazienza.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-262">The team will inform you with future updates; we appreciate your patience.</span></span>

- <span data-ttu-id="9ccd6-263">Questo problema è stato risolto. ora è possibile usare il driver ODBC all'esterno delle applicazioni a portata di clic di Office.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-263">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>

### <a name="excel"></a><span data-ttu-id="9ccd6-264">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-264">Excel</span></span>

- <span data-ttu-id="9ccd6-265">È possibile che si sia verificata la classificazione automatica dei documenti per le cartelle di lavoro in modalità di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-265">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>

- <span data-ttu-id="9ccd6-266">È stato risolto un problema che provocava un arresto anomalo quando si provava a creare una connessione dati dopo aver disconnesso il proprio account.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-266">Fixed a crash that could happen when trying to create a data connection if you have signed out from your account.</span></span>

- <span data-ttu-id="9ccd6-267">È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo nel tentativo di inserire tabelle pivot in un foglio grafico.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-267">Addressed an issue where Excel may crash when attempting to insert PivotTables into a chart sheet.</span></span>

- <span data-ttu-id="9ccd6-268">È possibile che si verifichi un errore quando si prova a salvare un file che contiene una formula usando la funzione LET().</span><span class="sxs-lookup"><span data-stu-id="9ccd6-268">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>

- <span data-ttu-id="9ccd6-269">È stato risolto un problema per cui Excel potrebbe arrestarsi in modo anomalo in determinate circostanze quando si usa Copia formato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-269">Fixed an issue where Excel could crash in certain circumstances when using the Format Painter.</span></span>

- <span data-ttu-id="9ccd6-270">È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-270">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="9ccd6-271">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-271">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="9ccd6-272">È stato risolto un problema per cui, in alcuni casi, se si faceva clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro veniva nascosta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-272">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>

- <span data-ttu-id="9ccd6-273">È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-273">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="9ccd6-274">Application.Evaluate (VBA) in alcuni casi non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-274">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="9ccd6-275">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-275">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="9ccd6-276">È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-276">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="9ccd6-277">Questo risolve un problema in cui le connessioni create dal provider di dati SQL nelle versioni precedenti di Office imposterebbero le proprietà della tabella interna in modo diverso da Office 365.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-277">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="9ccd6-278">Ciò ha causato la disabilitazione dell'elenco a discesa Anteprima tabella/Editor di query per i file con connessioni create nelle versioni precedenti di Office quando sono stati aperti utilizzando Office 365.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-278">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>

- <span data-ttu-id="9ccd6-279">È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-279">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>

- <span data-ttu-id="9ccd6-280">È stato risolto un problema per cui l’input penna poteva far sì che Excel smettesse di rispondere.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-280">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>

### <a name="onenote"></a><span data-ttu-id="9ccd6-281">OneNote</span><span class="sxs-lookup"><span data-stu-id="9ccd6-281">OneNote</span></span>

- <span data-ttu-id="9ccd6-282">Informazioni per gli utenti tramite la Barra informazioni sulle rettifiche temporanee in Microsoft OneNote che consentono di migliorare la sincronizzazione e la disponibilità dei servizi durante i picchi di utilizzo in tutto il mondo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-282">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>

- <span data-ttu-id="9ccd6-283">Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-283">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="9ccd6-284">È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-284">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="9ccd6-285">Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-285">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="9ccd6-286">Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-286">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="9ccd6-287">Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-287">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="9ccd6-288">I blocchi appunti locali non vengono interessati da questa operazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-288">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="9ccd6-289">Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza con cui vengono create le cronologie delle versioni delle pagine.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-289">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>

- <span data-ttu-id="9ccd6-290">Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente lo spostamento delle pagine nel Cestino.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-290">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="9ccd6-291">Agli utenti che vogliono eliminare una pagina verrà mostrata una finestra di dialogo in cui viene chiesto se si vuole eliminare la pagina definitivamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-291">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-292">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-292">Outlook</span></span>

- <span data-ttu-id="9ccd6-293">Risolve un problema che faceva sì che gli utenti che tentavano di creare una convocazione di riunione da un account secondario aggiunto al loro profilo non vedessero uno spazio da: campo al posto del loro indirizzo e-mail.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-293">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>

- <span data-ttu-id="9ccd6-294">Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-294">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>

- <span data-ttu-id="9ccd6-295">È stato risolto un problema che causava il mancato retrazione delle riunioni dal calendario di un responsabile in alcuni casi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-295">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>

- <span data-ttu-id="9ccd6-296">È stato risolto un problema che impediva ad alcuni utenti della funzionalità Miglioramenti dei Calendar - Calendario di Outlook condivisi di visualizzare un calendario condiviso appena aggiunto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-296">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>

- <span data-ttu-id="9ccd6-297">Risolve un problema che faceva sì che gli utenti sperimentassero occasionalmente degli arresti anomali durante l’interazione con gli allegati cloud.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-297">Fixes an issue that caused users to experience occasional crashes when interacting with Cloud attachments.</span></span>

- <span data-ttu-id="9ccd6-298">È stato risolto un problema che causava l'arresto anomalo di CLP cambiando l'indirizzo Da in una risposta da un contesto protetto a uno non protetto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-298">Addressed an issue that caused users of CLP to experience a crash when switching the from address on a reply from a protected context to an unprotected one.</span></span>

- <span data-ttu-id="9ccd6-299">È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-299">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="9ccd6-300">È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-300">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>

- <span data-ttu-id="9ccd6-301">È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-301">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="9ccd6-302">È stato risolto un problema a causa del quale gli utenti visualizzavano la data di creazione degli allegati copiati nel file system tramite il trascinamento fissata all’1 gennaio 4501.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-302">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>

- <span data-ttu-id="9ccd6-303">È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-303">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>

- <span data-ttu-id="9ccd6-304">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'aggiornamento delle regole in Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-304">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="9ccd6-305">È stato risolto un problema che causava il mancato recupero di suggerimenti per la ricerca da parte di Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-305">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>

- <span data-ttu-id="9ccd6-306">È stato risolto un problema a causa del quale gli utenti dei miglioramenti del Calendario di Outlook condivisi visualizzavano errori di Calendario di Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-306">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>

- <span data-ttu-id="9ccd6-307">È stato risolto un problema che causava blocchi o arresti intermittenti in alcune situazioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-307">Addressed an issue that caused users to experience intermittent hangs and crashes in some scenarios.</span></span>

- <span data-ttu-id="9ccd6-308">È stato risolto un problema che causava l'arresto anomalo di quattro o più messaggi di posta elettronica da un account POP con l'opzione "solo intestazioni di download" selezionata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-308">Addressed an issue which caused users to experience a crash when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>

- <span data-ttu-id="9ccd6-309">Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-309">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="9ccd6-310">È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un manager.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-310">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="9ccd6-311">È stato risolto un problema che causava arresti anomali nelle applicazioni MAPI di terze parti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-311">Addressed an issue that caused users to experience crashes in third party MAPI applications.</span></span>

- <span data-ttu-id="9ccd6-312">È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-312">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="9ccd6-313">È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-313">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="9ccd6-314">È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso "Stato dell’antivirus: non valido".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-314">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="9ccd6-315">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato installato correttamente l’antivirus.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-315">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>

- <span data-ttu-id="9ccd6-316">È stato risolto un problema che causava l'arresto anomalo di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-316">Addressed an issue that caused Outlook to crash when opening .msg or .oft files that were saved locally after a Windows update.</span></span>

- <span data-ttu-id="9ccd6-317">È stato risolto un problema che causava l'arresto anomalo di Outlook in alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-317">Addressed an issue that caused Outlook to crash on some builds of Windows.</span></span>

- <span data-ttu-id="9ccd6-318">È stato risolto un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-318">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>

- <span data-ttu-id="9ccd6-319">È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-319">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="9ccd6-320">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-320">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="9ccd6-321">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-321">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>

- <span data-ttu-id="9ccd6-322">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente pianificazione da parte di alcuni utenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-322">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>

- <span data-ttu-id="9ccd6-323">È stato risolto un problema che causava occasionalmente l’arresto anomalo degli utenti durante il recupero delle informazioni personali.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-323">Addressed an issue that caused users to occasionally crash when retrieving persona information.</span></span>

- <span data-ttu-id="9ccd6-324">Questo risolve un problema che causava agli utenti degli arresti anomali occasionali durante la modifica dei destinatari.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-324">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="9ccd6-325">Risolve un problema che consente agli utenti di visualizzare anomalie durante l'uso della visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-325">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>

- <span data-ttu-id="9ccd6-326">È stato risolto un problema che causava agli utenti di Outlook la comparsa di errori connessi con lo spostamento in modalità di visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-326">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>

- <span data-ttu-id="9ccd6-327">È stato risolto un problema che causava il mancato recapito del menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-327">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>

- <span data-ttu-id="9ccd6-328">È stato risolto un problema che causava la ricezione dell'errore seguente quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio, "Alcuni dei file in questa pagina Web non sono nella posizione prevista.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-328">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="9ccd6-329">Scaricarli comunque?</span><span class="sxs-lookup"><span data-stu-id="9ccd6-329">Do you want to download them anyway?</span></span> <span data-ttu-id="9ccd6-330">Se si è sicuri che la pagina Web sia una fonte attendibile, fare clic su Sì"</span><span class="sxs-lookup"><span data-stu-id="9ccd6-330">If you’re sure the Web page is from a trusted source, click Yes"</span></span>

- <span data-ttu-id="9ccd6-331">Risolve un problema che causava un blocco uscendo da Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-331">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>

- <span data-ttu-id="9ccd6-332">È stato risolto un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-332">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>

- <span data-ttu-id="9ccd6-333">È stato risolto un problema che causava problemi di formattazione negli avvisi di notifica degli eventi imprevisti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-333">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>

- <span data-ttu-id="9ccd6-334">È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una Notifica amministratore.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-334">Addressed an issue that caused users to experience a crash when submitting feedback from an Admin Notification.</span></span>

- <span data-ttu-id="9ccd6-335">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-335">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="9ccd6-336">Questo risolve un problema che causava agli utenti degli arresti anomali occasionali durante la modifica dei destinatari.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-336">This fixes an issue that caused users to experience occasional crashes when editing recipients.</span></span>

- <span data-ttu-id="9ccd6-337">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-337">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9ccd6-338">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-338">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-339">È stato risolto un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-339">Fixed a crash when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>

- <span data-ttu-id="9ccd6-340">È stato risolto un problema relativo all'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-340">We have fixed a crash issue with PowerPoint app.</span></span>

- <span data-ttu-id="9ccd6-341">È stato risolto un problema relativo all'arresto anomalo del riquadro suggerimenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-341">We have fixed a crash issue with suggestion pane.</span></span>

### <a name="project"></a><span data-ttu-id="9ccd6-342">Project</span><span class="sxs-lookup"><span data-stu-id="9ccd6-342">Project</span></span>

- <span data-ttu-id="9ccd6-343">È stato risolto un problema per cui, quando i dati predecessore/successore venivano modificati in una visualizzazione Maschera, veniva generato un evento ProjectBeforeTaskChange aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-343">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>

- <span data-ttu-id="9ccd6-344">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-344">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="9ccd6-345">È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-345">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>

- <span data-ttu-id="9ccd6-346">È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-346">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>

- <span data-ttu-id="9ccd6-347">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-347">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="9ccd6-348">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-348">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="9ccd6-349">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-349">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="9ccd6-350">È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-350">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>

- <span data-ttu-id="9ccd6-351">È stato risolto un problema per cui non era possibile aprire progetti nel client Project per desktop da Project Web App con gli URL con suffisso .com.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-351">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>

- <span data-ttu-id="9ccd6-352">È stato risolto un problema per cui, incollando un'attività con più dipendenze, non tutte le dipendenze vengono copiate correttamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-352">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>

- <span data-ttu-id="9ccd6-353">È stato risolto un problema per cui non era possibile salvare un file PDF/XPS da Project a una raccolta documenti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-353">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>

- <span data-ttu-id="9ccd6-354">È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-354">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>

- <span data-ttu-id="9ccd6-355">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-355">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>

- <span data-ttu-id="9ccd6-356">È stato risolto un problema per cui, se una risorsa aveva più di una tabella tariffe definita, il costo residuo non sempre veniva calcolato correttamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-356">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>

- <span data-ttu-id="9ccd6-357">È stato risolto un problema per cui la data di fine del progetto non viene aggiornata per i progetti collegati all'elenco attività di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-357">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>

- <span data-ttu-id="9ccd6-358">È stato risolto un problema per cui l'attività selezionata nella finestra di dialogo Assegna risorse non è la stessa selezionata nella visualizzazione Bacheca attività.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-358">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>

- <span data-ttu-id="9ccd6-359">È stato risolto un problema che impediva l’apertura di un progetto che aveva ottenuto uno stato non valido.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-359">Fixed an issue where a project that had gotten into a bad state could not be opened.</span></span>

### <a name="skype"></a><span data-ttu-id="9ccd6-360">Skype</span><span class="sxs-lookup"><span data-stu-id="9ccd6-360">Skype</span></span>

- <span data-ttu-id="9ccd6-361">Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-361">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="9ccd6-362">In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-362">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="9ccd6-363">Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-363">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>

- <span data-ttu-id="9ccd6-364">Il tono della pelle dell’emoticon che balla modificato su un colorito neutro.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-364">Changed dancing emoticon skin tone to neutral color.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-365">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-365">Word</span></span>

- <span data-ttu-id="9ccd6-366">È stato risolto un problema durante l'apertura di documenti di Word tramite consegna di documenti personalizzati (aspx) con URL contenente un componente di query.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-366">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>

- <span data-ttu-id="9ccd6-367">Questa modifica consente di risolvere un problema in cui le applicazioni di Office possono bloccarsi in uno stato di errore di salvataggio silenzioso dopo una sessione di creazione condivisa precedente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-367">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>

- <span data-ttu-id="9ccd6-368">È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-368">Addresses an issue that caused users to experience a crash when replying to or composing new email.</span></span>

- <span data-ttu-id="9ccd6-369">È stato risolto un problema che causava un arresto anomalo quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-369">Addressed an issue that caused users to occasionally experience a crash when using the "X" button on their mouse.</span></span>

- <span data-ttu-id="9ccd6-370">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-370">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="9ccd6-371">È stato risolto un problema per cui l'utente poteva perdere il contenuto quando ridimensionava una forma.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-371">We fixed an issue where the user might lose content when resize a shape.</span></span>

- <span data-ttu-id="9ccd6-372">È stato risolto un problema per cui gli stili di base non venivano aggiornati con lo stile normale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-372">We fixed an issue which the base styles are not updated with Normal style.</span></span>

- <span data-ttu-id="9ccd6-373">È stato risolto un problema per cui la macro AutoOpen veniva eseguita prima di AutoExec.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-373">We fixed an issue where macro AutoOpen runs before AutoExec.</span></span>

- <span data-ttu-id="9ccd6-374">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-374">We fixed an issue for copy and paste SVG image.</span></span>

- <span data-ttu-id="9ccd6-375">È stato risolto un problema che può aver causato un arresto anomalo durante il trascinamento del contenuto dall'app.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-375">Resolved an issue that may have caused a crash when dragging some content from the app.</span></span>


### <a name="office-suite"></a><span data-ttu-id="9ccd6-376">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-376">Office Suite</span></span>

- <span data-ttu-id="9ccd6-377">Per il riquadro Condividi basato su servizi non Web precedente, dopo aver chiuso il documento mentre il riquadro Condividi è aperto potrebbe verificarsi un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-377">For the old, non-web service based Share pane, upon closing the document while the Share pane is open could cause a crash.</span></span> <span data-ttu-id="9ccd6-378">Questo problema è stato risolto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-378">This is now fixed.</span></span>

- <span data-ttu-id="9ccd6-379">È stato risolto un problema di tempistiche che poteva causare un arresto anomalo durante la chiusura dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-379">Fixed a timing issue could cause a crash when closing office files</span></span>

- <span data-ttu-id="9ccd6-380">È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-380">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>

- <span data-ttu-id="9ccd6-381">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="9ccd6-381">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="9ccd6-382">È stato risolto un problema a portata di clic che causava un errore nell'aggiornamento durante il tentativo di creare collegamenti simbolici reali.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-382">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>

- <span data-ttu-id="9ccd6-383">È stato risolto un problema che causava la visualizzazione di un messaggio di runtime, anche se la transizione al prodotto completo era stata completata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-383">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="9ccd6-384">Il problema è stato corretto verificando che il servizio calcolasse correttamente i prodotti aggiunti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-384">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="9ccd6-385">I nuovi prodotti aggiunti sono stati filtrati (verificando che esistano anche nella nuova configurazione) e aggiunti alla fine degli ID di rilascio prodotti esistenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-385">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>

- <span data-ttu-id="9ccd6-386">È stato risolto un problema per cui gli elementi o il contenuto dell'interfaccia utente non erano visualizzati dagli utenti in determinate condizioni, in particolare con l’entrata e l’uscita dalla visualizzazione Relatore o l'utilizzo di più monitor.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-386">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>

- <span data-ttu-id="9ccd6-387">Questa modifica risolve potenziali blocchi che si verificano durante il caricamento e la riproduzione di contenuti animati, ad esempio GIF o modelli 3D.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-387">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>

- <span data-ttu-id="9ccd6-388">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-388">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>

- <span data-ttu-id="9ccd6-389">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-389">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="9ccd6-390">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-390">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="9ccd6-391">Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-391">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="9ccd6-392">È stato risolto un problema di arresto imprevisto con l'host di Office in Windows, per cui un componente aggiuntivo viene attivato quando il valore del registro TabProcGrowth è di tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-392">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>

- <span data-ttu-id="9ccd6-393">L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-393">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="9ccd6-394">La modifica potrebbe risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-394">This change would fix this issue.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-august-11"></a><span data-ttu-id="9ccd6-396">Versione 2002: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="9ccd6-396">Version 2002: August 11</span></span>
<span data-ttu-id="9ccd6-397">*Versione 2002 (Build 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-397">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="9ccd6-398">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-398">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-400">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-400">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-401">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-401">Excel</span></span>

- <span data-ttu-id="9ccd6-402">È stato risolto un problema che impediva di modificare i file aperti in modalità "Consigliata sola lettura".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-402">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="9ccd6-403">OneNote</span><span class="sxs-lookup"><span data-stu-id="9ccd6-403">OneNote</span></span>

- <span data-ttu-id="9ccd6-404">Sono state rimosse le chiamate di identità ridondanti per ridurre l'utilizzo delle risorse</span><span class="sxs-lookup"><span data-stu-id="9ccd6-404">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="9ccd6-405">È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-405">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="9ccd6-406">Sono state migliorate la funzionalità di rilevamento di errori e la qualità dell'esperienza di sincronizzazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-406">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-407">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-407">Outlook</span></span>

- <span data-ttu-id="9ccd6-408">È stato risolto un problema che causava un notevole problema di prestazioni durante l'avvio di Outlook per alcuni tenant.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-408">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="9ccd6-409">Skype</span><span class="sxs-lookup"><span data-stu-id="9ccd6-409">Skype</span></span>

- <span data-ttu-id="9ccd6-410">È stato risolto un problema che causava un errore di avvio della condivisione dello schermo quando un client Skype for Business a 32 bit era in uso per diversi giorni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-410">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-411">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-411">Office Suite</span></span>

- <span data-ttu-id="9ccd6-412">È stato risolto un problema per cui, se il salvataggio automatico era disattivato con i criteri di gruppo, quando si aprivano alcuni documenti per visualizzare il contenuto più recente sul server bisognava fare clic su "Aggiornamenti disponibili".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-412">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="9ccd6-414">Versione 2002: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="9ccd6-414">Version 2002: July 14</span></span>
<span data-ttu-id="9ccd6-415">*Versione 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-415">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="9ccd6-416">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-416">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-418">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-418">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-419">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-419">Excel</span></span>

- <span data-ttu-id="9ccd6-420">Velocizzato il caricamento dei file disponibili nella cartella locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-420">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="9ccd6-421">È stato risolto un problema per cui il codice XML CustomUI per una scheda della barra multifunzione personalizzata veniva rimosso salvando in SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-421">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="9ccd6-422">È stato risolto un problema per cui veniva visualizzato il messaggio di errore "Questa cartella di lavoro non può essere chiusa in quanto esiste un'altra cartella di lavoro che fa riferimento ad essa", perché i componenti aggiuntivi venivano caricati in ordine alfabetico anziché in un ordine specificato dall'utente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-422">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="9ccd6-423">È stato risolto un problema per cui una cartella di lavoro poteva essere impostata come nascosta facendo clic su un collegamento ipertestuale a un punto una cartella di lavoro già aperta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-423">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="9ccd6-424">È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappati anziché indirizzi universali.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-424">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="9ccd6-425">Sono state migliorate le prestazioni associate all'eliminazione di colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-425">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="9ccd6-426">È stato risolto un problema che causava la ripetizione dei nomi delle stampanti nell'elenco all'interno della finestra di dialogo Stampa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-426">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="9ccd6-427">È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-427">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>


### <a name="outlook"></a><span data-ttu-id="9ccd6-428">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-428">Outlook</span></span>

- <span data-ttu-id="9ccd6-429">È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante inserito attraverso l’IME, quando venivano usati più monitor con risoluzioni diverse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-429">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="9ccd6-430">È stato risolto un problema per cui appuntamenti o riunioni ricorrenti venivano visualizzati al momento sbagliato avvicinandosi al momento di cambiare la definizione del fuso orario.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-430">Addressed an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="9ccd6-431">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'aggiornamento delle regole in Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-431">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="9ccd6-432">Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-432">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="9ccd6-433">È stato risolto un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-433">Addressed an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="9ccd6-434">È stato risolto un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-434">Addressed an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="9ccd6-435">È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un responsabile.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-435">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="9ccd6-436">È stato risolto un problema per cui il corpo di un messaggio NDR passava da Unicode a ASCII dopo aver modificato l'oggetto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-436">Addressed an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="9ccd6-437">È stato risolto un problema che causava un arresto anomalo quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo della barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-437">Addressed an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="9ccd6-438">È stato risolto un problema che impediva agli utenti di inviare messaggi di posta elettronica a una lista di distribuzione personale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-438">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="9ccd6-439">È stato risolto un problema che causava la mancata aggiunta di collegamenti ai messaggi di posta elettronica con l'autorizzazione predefinita del tenant corretta quando questa era configurata su "chiunque".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-439">Addressed an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as"anyone".</span></span>

- <span data-ttu-id="9ccd6-440">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-440">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-441">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-441">Word</span></span>

- <span data-ttu-id="9ccd6-442">È stato risolto un problema relativo alla creazione condivisa abilitando il criterio FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-442">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="9ccd6-443">È stato risolto un problema per cui le parti rapide di Word non funzionavano aggiungendo un campo di ricerca rinominato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-443">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-444">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-444">Office Suite</span></span>

- <span data-ttu-id="9ccd6-445">È stato risolto un problema per cui gli utenti riscontravano un utilizzo eccessivo della rete e della CPU durante la creazione condivisa in file di PowerPoint di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-445">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="9ccd6-446">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="9ccd6-446">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="9ccd6-447">È stato risolto un problema di arresto imprevisto con l'host di Office in Windows, per cui un componente aggiuntivo viene attivato quando il valore del registro TabProcGrowth è di tipo REG_SZ.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-447">Addressed a crash issue with the office host in windows, when an add-in is activated while the registry TabProcGrowth value is REG_SZ type.</span></span>


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO BUG)

## <a name="version-2002-june-09"></a><span data-ttu-id="9ccd6-449">Versione 2002: giugno 09</span><span class="sxs-lookup"><span data-stu-id="9ccd6-449">Version 2002: June 09</span></span>
<span data-ttu-id="9ccd6-450">*Versione 2002 (Build 12527.20720)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-450">*Version 2002 (Build 12527.20720)*</span></span>

<span data-ttu-id="9ccd6-451">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-451">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-453">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-453">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-454">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-454">Excel</span></span>

- <span data-ttu-id="9ccd6-455">È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-455">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="9ccd6-456">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-456">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="9ccd6-457">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-457">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="9ccd6-458">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-458">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="9ccd6-459">L'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-459">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="9ccd6-460">È stato risolto un problema per cui un simbolo @ che avvia una formula verrebbe considerato come operatore di intersezione implicito.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-460">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-461">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-461">Outlook</span></span>

- <span data-ttu-id="9ccd6-462">Consente di partecipare a una riunione di Teams direttamente tramite il client nativo teams.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-462">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="9ccd6-463">È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-463">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="9ccd6-464">È stato risolto un problema che causava l'installazione errata dell'emulazione del browser nell'ambito del mancato completamento della richiesta di autenticazione di Gmail.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-464">Addressed an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="9ccd6-465">È stato risolto un problema che restituiva agli utenti di Outlook sui sistemi operativi del server l'errore "stato antivirus: non valido.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-465">Addressed an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="9ccd6-466">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato configurato in modo appropriato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-466">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-467">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-467">Word</span></span>

- <span data-ttu-id="9ccd6-468">È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-468">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-469">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-469">Office Suite</span></span>

- <span data-ttu-id="9ccd6-470">Il problema è stato risolto aggiornando i nomi dei canali nella visualizzazione backstage ai nuovi nomi dei canali nel fork 2020 gennaio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-470">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="9ccd6-471">Il problema è stato risolto e in futuro, se un dispositivo viene gestito da criteri, non chiamerà l'API DMS Audience.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-471">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="9ccd6-472">È stato risolto il problema relativo alla rimozione incompleta nell'ambito dell'aggiunta e della rimozione di app in una singola operazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-472">Resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="9ccd6-473">L'host di Office si arrestava in modo anomalo in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-473">The office host was crashing in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="9ccd6-474">La modifica potrebbe risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-474">This change would fix this issue.</span></span>


[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-2002-may-12"></a><span data-ttu-id="9ccd6-476">Versione 2002: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="9ccd6-476">Version 2002: May 12</span></span>
<span data-ttu-id="9ccd6-477">*Versione 2002 (Build 12527.20612)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-477">*Version 2002 (Build 12527.20612)*</span></span>

<span data-ttu-id="9ccd6-478">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-478">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-480">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-480">Resolved issues</span></span>

### <a name="excel"></a><span data-ttu-id="9ccd6-481">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-481">Excel</span></span>

- <span data-ttu-id="9ccd6-482">Aprire una cartella di lavoro con riferimenti a molte altre cartelle di lavoro, in particolare con finestre nascoste, risulterebbe un'operazione piuttosto lenta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-482">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="9ccd6-483">In alcuni casi, l'apertura di file CSV impiega più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-483">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="9ccd6-484">In alcuni casi, Excel potrebbe arrestarsi in modo anomalo quando si passa da una cartella di lavoro a un'altra con livelli di zoom diversi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-484">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="9ccd6-485">È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-485">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="9ccd6-486">I dati copiati da una colonna filtrata in base al colore a volte non vengono incollati correttamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-486">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="9ccd6-487">È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-487">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="9ccd6-488">Aprendo nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-488">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="9ccd6-489">È stato risolto un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambiava in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-489">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="9ccd6-490">Se si usa un Range.Value e un Range.Value2 (VBA), le formule vengono immesse come matrici dinamiche.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-490">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

### <a name="onenote"></a><span data-ttu-id="9ccd6-491">OneNote</span><span class="sxs-lookup"><span data-stu-id="9ccd6-491">OneNote</span></span>

- <span data-ttu-id="9ccd6-492">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-492">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="9ccd6-493">Visualizza una notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-493">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="9ccd6-494">Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente il numero e la frequenza di sincronizzazione delle pagine della cronologia versioni di OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-494">Improved sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="9ccd6-495">Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente il cestino in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-495">Improved sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="9ccd6-496">Quando un utente prova a eliminare dati che normalmente verrebbero spostati nel cestino, all'utente verrà chiesto se vuole mantenere o eliminare definitamente il file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-496">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="9ccd6-497">Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-497">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="9ccd6-498">Miglioramento della sincronizzazione e della stabilità del servizio rimandando temporaneamente il download di immagini e file incorporati in blocchi appunti online finché l'utente esplora la pagina in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-498">Improved sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="9ccd6-499">Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-499">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="9ccd6-500">I blocchi appunti locali non vengono interessati da questa operazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-500">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="9ccd6-501">Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-501">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="9ccd6-502">Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-502">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-503">Outlook</span></span>

- <span data-ttu-id="9ccd6-504">È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-504">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="9ccd6-505">È stato risolto un problema che causava un arresto anomalo quando si cerca di aprire file .msg e .oft dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-505">Addressed an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="9ccd6-506">È stato risolto un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-506">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="9ccd6-507">Questo aggiornamento consente di risolvere un problema di Microsoft Outlook che non visualizza l'etichetta di riservatezza corrente durante la visualizzazione o la creazione di messaggi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-507">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="9ccd6-508">È stato risolto un problema che impediva agli utenti di inviare messaggi di posta elettronica a una lista di distribuzione personale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-508">Addressed an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9ccd6-509">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-509">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-510">È stato risolto un problema relativo all'inoltro della messaggistica corretta per gli utenti che aprono una copia di un file con commenti migliorati.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-510">Fixed an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-511">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-511">Word</span></span>

- <span data-ttu-id="9ccd6-512">È stato risolto il problema per cui Access e Publisher potrebbero non essere avviati correttamente a seconda delle lingue installate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-512">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>

- <span data-ttu-id="9ccd6-513">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-513">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="9ccd6-514">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-514">We fixed an issue when merging 2 documents into one document.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-515">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-515">Office Suite</span></span>

- <span data-ttu-id="9ccd6-516">Si tratta di una soluzione per il blocco della rete da parte dell'app di Project quando il file viene memorizzato nella cache del client.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-516">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>

- <span data-ttu-id="9ccd6-517">Il problema è stato risolto quando un'operazione interna genera un'eccezione in caso di errore anziché registrare e continuare.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-517">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="9ccd6-518">Gli utenti interessati non riscontreranno più il blocco della ricezione degli aggiornamenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-518">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="9ccd6-519">Ciò assicura che la struttura disegnata funzioni correttamente nella barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-519">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="9ccd6-520">È stato risolto un problema che si verificava durante l'apertura di file da posizioni locali con alcune configurazioni proxy specifiche.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-520">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="9ccd6-521">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-521">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="9ccd6-522">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-522">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="9ccd6-523">Questo aggiornamento consente di risolvere un problema di Microsoft Word per il quale un testo più lungo di 255 caratteri inserito durante l'applicazione di un'etichetta di riservatezza non può essere identificato e rimosso in seguito modificando o rimuovendo l'etichetta se il criterio di etichetta applica un'intestazione, un piè di pagina o una filigrana.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-523">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

- <span data-ttu-id="9ccd6-524">È stato risolto un problema che causa l'arresto anomalo durante le sessioni di handoff di Office ed è stata migliorata l'affidabilità dell'esperienza utente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-524">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>  

- <span data-ttu-id="9ccd6-525">Questo bug aggiorna l'endpoint url di Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="9ccd6-525">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="9ccd6-526">Richiamare questo nuovo endpoint ha un tasso di successo maggiore per recuperare dati dall'ECS.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-526">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-2002-april-14"></a><span data-ttu-id="9ccd6-528">Versione 2002: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="9ccd6-528">Version 2002: April 14</span></span>
<span data-ttu-id="9ccd6-529">*Versione 2002 (Build 12527.20442)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-529">*Version 2002 (Build 12527.20442)*</span></span>

<span data-ttu-id="9ccd6-530">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-530">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


### <a name="feature-updates"></a><span data-ttu-id="9ccd6-531">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="9ccd6-531">Feature updates</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-532">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-532">Excel</span></span>

- <span data-ttu-id="9ccd6-533">**Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-533">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="9ccd6-534">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-534">Learn more</span></span>](https://support.microsoft.com/en-us/office/new-array-functions-003df6c7-1dcb-4388-8e2e-0fe77a0887bc?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="9ccd6-535">**Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-535">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span>  [<span data-ttu-id="9ccd6-536">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-536">Learn more</span></span>](https://support.microsoft.com/en-us/office/easier-array-formulas-5c2c9cbb-def8-409a-b380-2fbf91b20aa3?ui=en-us&rs=en-us&ad=us)
- <span data-ttu-id="9ccd6-537">**Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-537">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span>  <span data-ttu-id="9ccd6-538">
  [Altre informazioni](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-538">[Learn more](https://support.office.com/en-us/article/xlookup-function-b7fd680e-6d10-43e6-84f9-88eae8bf5929?ui=en-US&rs=en-US&ad=US)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-540">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-540">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-541">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-541">Excel</span></span>

- <span data-ttu-id="9ccd6-542">In alcuni casi, Excel si arrestava in modo anomalo alla riapertura di una cartella di lavoro incorporata in Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-542">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="9ccd6-543">Durante il salvataggio in formato CSV, in alcuni casi Excel univa tutte le colonne in una singola colonna.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-543">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="9ccd6-544">L'uso di Range.ClearContents in un intervallo in un foglio protetto poteva richiedere più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-544">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="9ccd6-545">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-545">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="9ccd6-546">Le macro VBA che interagiscono con la barra multifunzione possono essere eseguite con ScreenUpdating inaspettatamente impostato su True.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-546">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="9ccd6-547">È stato risolto un problema per cui i collegamenti esterni non vengono aggiornati durante il riempimento (copia in basso o tra fogli di lavoro) se la cartella di lavoro di origine è chiusa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-547">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is closed.</span></span>

- <span data-ttu-id="9ccd6-548">L'uso di Application.Evaluate di VBA talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-548">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="9ccd6-549">È stato risolto un problema di prestazioni durante la creazione di grafici dai modelli.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-549">Addressed a performance issue when creating charts from templates.</span></span>


### <a name="outlook"></a><span data-ttu-id="9ccd6-550">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-550">Outlook</span></span>

- <span data-ttu-id="9ccd6-551">È stato risolto un problema che causava l'espansione improvvisa dell'intestazione del gruppo in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-551">Addressed an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="9ccd6-552">È stato risolto un problema che causava un arresto anomalo selezionando alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-552">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="9ccd6-553">È stato risolto un problema che causava un arresto anomalo usando il pulsante X del mouse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-553">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="9ccd6-554">È stato risolto un problema che causava l'assenza del pulsante Salva nel cloud da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-554">Addressed an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9ccd6-555">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-555">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-556">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-556">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


### <a name="project"></a><span data-ttu-id="9ccd6-557">Project</span><span class="sxs-lookup"><span data-stu-id="9ccd6-557">Project</span></span>

- <span data-ttu-id="9ccd6-558">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-558">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="9ccd6-559">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-559">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-560">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-560">Word</span></span>

- <span data-ttu-id="9ccd6-561">È stato risolto un problema che causava un arresto anomalo usando il pulsante X del mouse.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-561">Addressed an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="9ccd6-562">È stato risolto un problema relativo all'adattamento del testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-562">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="9ccd6-563">È stato risolto un problema per cui le righe orizzontali inserite non sono più brevi e centrate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-563">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-march-10"></a><span data-ttu-id="9ccd6-565">Versione 2002: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="9ccd6-565">Version 2002: March 10</span></span>
<span data-ttu-id="9ccd6-566">*Versione 2002 (Build 12527.20278)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-566">*Version 2002 (Build 12527.20278)*</span></span>

<span data-ttu-id="9ccd6-567">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-567">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="9ccd6-569">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="9ccd6-569">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="9ccd6-570">Access</span><span class="sxs-lookup"><span data-stu-id="9ccd6-570">Access</span></span>

- <span data-ttu-id="9ccd6-571">**Trovare velocemente le tabelle collegate:** la nostra nuova casella di ricerca rende molto più facile trovare le tabelle collegate.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-571">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="9ccd6-572">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-572">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="9ccd6-573">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-573">Excel</span></span>

- <span data-ttu-id="9ccd6-574">**Ottenere l'attenzione tramite \@menzioni:** è possibile usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-574">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="9ccd6-575">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-575">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="9ccd6-576">**Trovare gli elementi cercati:** è possibile cercare comandi, persone, file, foto, notizie e molto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-576">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="9ccd6-577">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-577">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)


- <span data-ttu-id="9ccd6-578">**Creare schizzi** : è possibile conferire un aspetto informale alle forme di Office incluse nella cartella di lavoro, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-578">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="9ccd6-579">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-579">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="9ccd6-580">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-580">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="9ccd6-581">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-581">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="9ccd6-582">**Concentrarsi su ciò che resta da fare:** selezionare Risolvi per comprimere i commenti e far risaltare quelli ancora non risolti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-582">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="9ccd6-583">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-583">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="9ccd6-584">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-584">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="9ccd6-585">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-585">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="9ccd6-586">**Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-586">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="9ccd6-587">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-587">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="9ccd6-588">**Leggere e rispondere all'istante:** è possibile rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-588">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="9ccd6-589">**Ottenere le statistiche sulla cartella di lavoro:** le statistiche della cartella di lavoro forniscono una panoramica del contenuto di una cartella di lavoro, per facilitarne la ricerca.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-589">**Get stats on your workbook:** Workbook Statistics provides an overview of the content of a workbook, to help you more easily discover its contents.</span></span>

- <span data-ttu-id="9ccd6-590">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-590">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9ccd6-591">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-591">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9ccd6-592">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-592">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="outlook"></a><span data-ttu-id="9ccd6-593">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-593">Outlook</span></span>

- <span data-ttu-id="9ccd6-594">**Connessione della rete LinkedIn a Outlook:** connessione sicura degli account LinkedIn all'account Microsoft per visualizzare le informazioni dei profili LinkedIn direttamente nella scheda Utenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-594">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="9ccd6-595">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-595">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="9ccd6-p156">**Tutte le opzioni di crittografia in un'unica posizione:** basta passare a Opzioni > Crittografa per scegliere come proteggere il messaggio di posta elettronica. [Altre informazioni](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-p156">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="9ccd6-598">**Il menu Inserisci collegamento in Outlook inserisce un collegamento con l'autorizzazione definita dall'amministratore tenant:** un collegamento dall'elenco dei file usati di recenti in Inserisci collegamento in Outlook inseriva un collegamento che funzionava solo per gli utenti che avevano già le relative autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-598">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="9ccd6-599">Questo causava spesso uno scambio di messaggi tra gli utenti per richiedere l'accesso a un documento.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-599">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="9ccd6-600">Questa esperienza è stata aggiornata in modo tale che il collegamento venga inserito con l'autorizzazione predefinita impostata dall'amministratore tenant. Per MSIT si tratta dell’opzione "L’organizzazione può modificare", pertanto tutti gli utenti interni che riceveranno un collegamento condiviso in questo modo saranno in grado di accedervi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-600">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="9ccd6-601">**Cercare testo contenente errori di ortografia o di digitazione:** Outlook troverà il testo cercato anche quando l'ortografia non è corretta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-601">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="9ccd6-602">**I messaggi di phishing sono facilmente individuabili:** la posta indesiderata e i messaggi di phishing hanno un aspetto diverso, in modo da poterli identificare e rimuovere facilmente dalla posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-602">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="9ccd6-603">**Protezione avanzata dalle minacce:** con Office 365 Advanced Threat Protection, si è protetti dalle minacce tramite collegamenti ipertestuali negli oggetti di posta elettronica, messaggi allegati, messaggi firmati, percorsi di rete e così via.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-603">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="9ccd6-604">**Aggiunta della funzionalità Input penna:** è possibile scarabocchiare sopra le immagini o aggiungere un'area di disegno per inviare idee con l'input penna.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-604">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="9ccd6-605">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-605">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="9ccd6-606">**Visualizza i messaggi rilevanti nei risultati della ricerca:** Outlook analizza i termini di ricerca e visualizza i messaggi di posta elettronica più importanti nella parte superiore dei risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-606">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="9ccd6-607">I risultati saranno ordinati anche per data nella sezione Risultati principali.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-607">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="9ccd6-608">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-608">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

- <span data-ttu-id="9ccd6-609">**Suggerimenti per il luogo delle riunioni:** è sufficiente iniziare a scrivere nella riga Luogo durante la pianificazione di appuntamenti e riunioni e Outlook suggerirà sale, indirizzi e altri luoghi recenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-609">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="9ccd6-610">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-610">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)

- <span data-ttu-id="9ccd6-611">**Possibilità di visualizzare più messaggi sullo schermo:** Selezionare Visualizza > Usa spazio più stretto per regolare la spaziatura tra i messaggi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-611">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="9ccd6-612">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-612">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="9ccd6-613">**Vedere i messaggi sotto una luce diversa:** usare il pulsante Sole/Luna per utilizzare lo sfondo chiaro o lo sfondo scuro nel riquadro di lettura.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-613">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="9ccd6-614">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-614">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="9ccd6-615">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-615">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9ccd6-616">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-616">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9ccd6-617">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-617">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="powerpoint"></a><span data-ttu-id="9ccd6-618">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-618">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-619">**Collaborazione in tempo reale veloce in PowerPoint:** è possibile collaborare in tempo reale rapidamente in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-619">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="9ccd6-620">**Nuovi strumenti di correzione:** niente più preoccupazione per le parole.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-620">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="9ccd6-621">PowerPoint offre suggerimenti relativi a grammatica e ortografia.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-621">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="9ccd6-622">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-622">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="9ccd6-623">**Sottotitoli e sottotitoli in tempo reale:** le parole del relatore vengono visualizzate automaticamente sullo schermo come sottotitoli o tradotti in sottotitoli nella lingua scelta.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-623">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="9ccd6-624">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-624">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="9ccd6-p166">**La formattazione dei calcoli diventa automatica:** le espressioni matematiche scritte a mano vengono convertite in caratteri standard. Per iniziare, basta selezionare le note scritte a mano e scegliere Da input penna a testo matematico. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-p166">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="9ccd6-628">**Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-628">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="9ccd6-629">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-629">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="9ccd6-630">**Trovare e correggere titoli di diapositive mancanti:** i titoli delle diapositive ottimizzano la presentazione e rendono le diapositive accessibili per tutti gli utenti, anche con diverse abilità.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-630">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="9ccd6-631">L’opzione Verifica accessibilità mostra dove mancano i titoli in modo da aggiungerli in pochi secondi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-631">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="9ccd6-632">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-632">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="9ccd6-633">**Creare schizzi** : è possibile conferire un aspetto informale alle forme di Office incluse nella presentazione, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-633">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="9ccd6-634">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-634">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="9ccd6-635">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-635">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="9ccd6-636">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-636">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="9ccd6-637">**Salvare un'illustrazione in formato SVG:** è possibile salvare un grafico, una forma o un'altra illustrazione in formato SVG (Scalable Vector Graphic), che può essere ridimensionato senza perdita di qualità dell'immagine.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-637">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="9ccd6-638">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-638">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="9ccd6-639">**Stampa dei numeri delle diapositive negli stampati:** i numeri delle diapositive vengono inclusi automaticamente negli stampati.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-639">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="9ccd6-640">Lasciarli attivati o disattivarli è a discrezione dell'utente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-640">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="9ccd6-641">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-641">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="9ccd6-642">**Replay immediato:** applicare un'animazione di riproduzione per ripetere la sequenza di disegno con l'input penna durante la presentazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-642">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="9ccd6-643">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-643">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)

- <span data-ttu-id="9ccd6-644">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-644">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span>

- <span data-ttu-id="9ccd6-645">**Ottimizzazione della presentazione per tutti:** l’opzione Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-645">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span>

- <span data-ttu-id="9ccd6-646">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-646">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="9ccd6-647">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-647">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="9ccd6-648">**Perché reinventare quando è possibile riutilizzare?:** per risparmiare tempo, è possibile riutilizzare le diapositive create personalmente o condivise da altri utenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-648">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="9ccd6-649">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-649">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

- <span data-ttu-id="9ccd6-650">**Convertire l'input penna a mano libera in forme, testo o equazioni matematiche in PowerPoint per Office 365:** è possibile passare dall'input penna a mano libera al testo, a un'espressione matematica o alle forme di Office, con un paio di tratti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-650">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="9ccd6-651">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-651">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="9ccd6-652">**Input penna per diapositive meravigliose:** è possibile convertire l'input penna in forme e testo standard e quindi ottenere idee di progettazione delle diapositive intelligenti da PowerPoint Designer.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-652">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="9ccd6-653">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-653">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="9ccd6-654">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-654">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9ccd6-655">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-655">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9ccd6-656">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-656">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

### <a name="visio"></a><span data-ttu-id="9ccd6-657">Visio</span><span class="sxs-lookup"><span data-stu-id="9ccd6-657">Visio</span></span>

- <span data-ttu-id="9ccd6-658">**Analisi della scena del crimine:** è possibile usare i nuovi stencil Prova, Interni ed Esterni nel modello di indagine della scena del crimine per ricreare in dettaglio le scene del crimine.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-658">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

- <span data-ttu-id="9ccd6-659">**Creare diagrammi di Visio chiari in Excel:** è possibile creare un diagramma di flussi o un organigramma inserendo i dati in un foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-659">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="9ccd6-660">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-660">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

### <a name="word"></a><span data-ttu-id="9ccd6-661">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-661">Word</span></span>

- <span data-ttu-id="9ccd6-662">**Editor per curriculum unito all’Assistente curriculum LinkedIn:** l’editor per il curriculum offre una selezione di controlli grammaticali e stilistici appositamente studiati per i curriculum, per rendere la scrittura più precisa e professionale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-662">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="9ccd6-663">**Risoluzione di un problema di danneggiamento di un documento causato dall'unione di oggetti 3D:** è stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-663">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="9ccd6-664">**Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-664">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="9ccd6-665">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-665">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="9ccd6-666">**Collaborare con colori vivaci:** i commenti e le modifiche sono contraddistinti da colori associati ai vari collaboratori, in modo che risulti facile identificarli.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-666">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="9ccd6-667">**Modificare i documenti con attivazione macro in modo collaborativo:** è possibile salvare i file docm su OneDrive for Business e modificarli con i collaboratori in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-667">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

- <span data-ttu-id="9ccd6-668">**Miglioramenti alla creazione condivisa** : prestazioni migliorate per la creazione condivisa nei documenti di Word con revisioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-668">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="9ccd6-669">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-669">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="9ccd6-670">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-670">Find them at Insert > Icons.</span></span> [<span data-ttu-id="9ccd6-671">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-671">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="9ccd6-672">**Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-672">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="9ccd6-673">**Creare schizzi** : è possibile conferire un aspetto informale alle forme di Office incluse nel documento, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-673">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="9ccd6-674">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-674">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)

- <span data-ttu-id="9ccd6-675">**Cancellare con precisione:** è possibile scegliere tra due dimensioni della gomma per correggere le piccole imperfezioni dell'input penna.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-675">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="9ccd6-676">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-676">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="9ccd6-677">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="9ccd6-678">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-678">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="9ccd6-679">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-679">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="9ccd6-680">**Miglioramenti alla creazione condivisa:** affidabilità migliore durante la creazione condivisa.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-680">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="9ccd6-681">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-681">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="9ccd6-682">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-682">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)

- <span data-ttu-id="9ccd6-683">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-683">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span>

- <span data-ttu-id="9ccd6-684">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-684">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="9ccd6-685">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="9ccd6-685">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)





[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-688">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-688">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="9ccd6-689">Access</span><span class="sxs-lookup"><span data-stu-id="9ccd6-689">Access</span></span>

- <span data-ttu-id="9ccd6-690">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo “Query danneggiata” quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-690">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

- <span data-ttu-id="9ccd6-691">Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-691">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="9ccd6-692">Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-692">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="9ccd6-693">L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-693">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="9ccd6-694">I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-694">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="9ccd6-695">Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-695">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

### <a name="excel"></a><span data-ttu-id="9ccd6-696">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-696">Excel</span></span>

- <span data-ttu-id="9ccd6-697">È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-697">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="9ccd6-698">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-698">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="9ccd6-699">È stato risolto un problema che causava arresti anomali durante la conversione del testo in colonne con celle dotate di una matrice con espansione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-699">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="9ccd6-700">Questo aggiornamento risolve un problema per cui la barra della formula causava la visualizzazione del testo in un carattere diverso da quello previsto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-700">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="9ccd6-701">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-701">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="9ccd6-702">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-702">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="9ccd6-703">È possibile che gli utenti possano visualizzare un errore durante il salvataggio delle modifiche, quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-703">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="9ccd6-704">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-704">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="9ccd6-705">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-705">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="9ccd6-706">La funzionalità Testo in colonne può non funzionare per alcune localizzazioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-706">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="9ccd6-707">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-707">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="9ccd6-708">È possibile che gli utenti possano visualizzare un errore durante il salvataggio delle modifiche, quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-708">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="9ccd6-709">È stato risolto un problema che alcuni utenti potrebbero aver riscontrato con oggetti incorporati e collegati (OLE).</span><span class="sxs-lookup"><span data-stu-id="9ccd6-709">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="9ccd6-710">Tramite il menu di scelta rapida predefinito per i grafici pivot ora è possibile abilitare l'opzione Mostra dettagli.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-710">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="9ccd6-711">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-711">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="9ccd6-712">È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-712">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="9ccd6-713">È stato risolto un problema che impediva la visualizzazione dei comandi di commento nel menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-713">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="9ccd6-714">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-714">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="9ccd6-715">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-715">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-716">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-716">Outlook</span></span>

- <span data-ttu-id="9ccd6-717">È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-717">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="9ccd6-718">È stato risolto un problema che causava agli utenti un blocco in Outlook durante il recupero delle impostazioni del cloud.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-718">Addressed an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="9ccd6-719">È stato risolto un problema che causava l’errato allineamento della casella di ricerca in modalità dpi elevato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-719">Addressed an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="9ccd6-720">È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-720">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="9ccd6-721">È stato risolto un problema per cui gli utenti vedevano i messaggi di posta elettronica inviati a un indirizzo che in alcuni casi non corrispondeva all'indirizzo SMTP visualizzato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-721">Addressed an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="9ccd6-722">Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-722">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="9ccd6-723">È stato risolto un problema che poteva impedire il salvataggio di file in una posizione WebDAV.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-723">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="9ccd6-724">È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-724">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="9ccd6-725">È stato risolto un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-725">Addressed an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="9ccd6-726">È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante "OK" quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-726">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="9ccd6-727">È stato risolto un problema che causava un arresto anomalo durante la creazione del profilo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-727">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="9ccd6-728">È stato risolto un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-728">Addressed an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="9ccd6-729">È stato risolto un problema per cui gli utenti con Tema Nero visualizzavano l'elenco a discesa “Da” con il testo bianco su sfondo bianco.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-729">Addressed an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="9ccd6-730">È stato risolto un problema che causava un arresto anomalo annullando la configurazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-730">Addressed an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="9ccd6-731">È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-731">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="9ccd6-732">È stato risolto un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-732">Addressed an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="9ccd6-733">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-733">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="9ccd6-734">È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-734">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="9ccd6-735">È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-735">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="9ccd6-736">È stato risolto un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-736">Addressed an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="9ccd6-737">È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-737">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="9ccd6-738">È stato risolto un problema che impediva agli utenti di aprire alcune istanze di elementi ricorrenti del calendario.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-738">Addressed an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="9ccd6-739">È stato risolto un problema che interessava le cassette postali sui server di Exchange 2010 durante l'aggiunta di allegati agli elementi del calendario da parte degli utenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-739">Addressed an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="9ccd6-740">È stato risolto un problema che si verificava agli utenti durante la risposta a messaggi con firma digitale.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-740">Addressed an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="9ccd6-741">È stato risolto un problema che causava l'aggiornamento imprevisto del campo Sede nelle riunioni.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-741">Addressed an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="9ccd6-742">È stato risolto un problema per cui la virgola nel campo Sede della riunione cambiava in punto e virgola.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-742">Addressed an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="9ccd6-743">È stato risolto un problema per cui la sede di una riunione veniva inaspettatamente aggiunta di nuovo alla riunione dopo che era stata cancellata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-743">Addressed an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="9ccd6-744">Sono stati risolti i problemi relativi alle riunioni e appuntamenti impostati nel fuso orario di Brasilia.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-744">Addressed issues relating to meetings and appointments set in the Brazilia time zone.</span></span>

- <span data-ttu-id="9ccd6-745">È stato risolto un problema che causava l'invio imprevisto di messaggi di posta elettronica quando gli utenti premevano il tasto “S” dopo aver chiuso il riquadro Verifica accessibilità.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-745">Addressed an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="9ccd6-746">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-746">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="9ccd6-747">È stato risolto un problema che causava l'accesso dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-747">Addressed an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="9ccd6-748">È stato risolto un problema che causava un arresto anomalo durante la creazione del profilo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-748">Addressed an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="9ccd6-749">È stato risolto un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-749">Addressed an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9ccd6-750">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-750">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-751">È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-751">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="9ccd6-752">È stato risolto un problema che potrebbe aver causato un arresto anomalo durante l’utilizzo del menu di scelta rapida nei commenti PPT legacy.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-752">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

### <a name="project"></a><span data-ttu-id="9ccd6-753">Progetto</span><span class="sxs-lookup"><span data-stu-id="9ccd6-753">Project</span></span>

- <span data-ttu-id="9ccd6-754">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-754">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="9ccd6-755">È stato risolto un problema per cui il 100% delle attività di tipo a durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-755">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

- <span data-ttu-id="9ccd6-756">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-756">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="9ccd6-757">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-757">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-758">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-758">Word</span></span>

- <span data-ttu-id="9ccd6-759">È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-759">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="9ccd6-760">Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: "Sono stati modificati gli stili, i blocchi predefiniti".</span><span class="sxs-lookup"><span data-stu-id="9ccd6-760">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-761">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-761">Office Suite</span></span>

- <span data-ttu-id="9ccd6-762">Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-762">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="9ccd6-763">Questa modifica risolve i problemi con gli adattatori grafici che sfruttano la GPU integrata Intel.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-763">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="9ccd6-764">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-764">Fixed a bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="9ccd6-765">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-765">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="9ccd6-766">È stato risolto un problema per cui l’apertura di più documenti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint comportava la conseguente analisi solo del primo documento per la conformità dei criteri.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-766">Fixed an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

[//]: # (NON RIMUOVERE I DETTAGLI DEL BUG DI FINE CONTENUTO)

## <a name="version-1908-february-11"></a><span data-ttu-id="9ccd6-768">Versione 1908: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="9ccd6-768">Version 1908: February 11</span></span>
<span data-ttu-id="9ccd6-769">*Versione 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-769">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="9ccd6-770">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-770">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-772">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-772">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-773">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-773">Excel</span></span>

- <span data-ttu-id="9ccd6-774">Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-774">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="9ccd6-775">È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-775">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="9ccd6-776">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-776">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="9ccd6-777">È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-777">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="9ccd6-778">È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-778">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="9ccd6-779">È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-779">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="9ccd6-780">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-780">Outlook</span></span>

- <span data-ttu-id="9ccd6-781">È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-781">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="9ccd6-782">È stato risolto un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-782">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="9ccd6-783">È stato risolto un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-783">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="9ccd6-784">È stato risolto un problema che causava arresti anomali intermittenti cambiando visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-784">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="9ccd6-785">È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-785">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="9ccd6-786">[Qui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) è disponibile il singolo articolo della Knowledge Basa in cui è stato documentato per le versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-786">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="9ccd6-787">È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-787">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="9ccd6-788">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-788">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-789">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-789">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="9ccd6-790">È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-790">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="9ccd6-791">È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-791">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="9ccd6-792">È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-792">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="9ccd6-793">Project</span><span class="sxs-lookup"><span data-stu-id="9ccd6-793">Project</span></span>

- <span data-ttu-id="9ccd6-794">È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-794">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="9ccd6-795">Word</span><span class="sxs-lookup"><span data-stu-id="9ccd6-795">Word</span></span>

- <span data-ttu-id="9ccd6-796">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-796">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-797">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-797">Office Suite</span></span>

- <span data-ttu-id="9ccd6-798">Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-798">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="9ccd6-800">Versione 1908: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="9ccd6-800">Version 1908: January 14</span></span>
<span data-ttu-id="9ccd6-801">*Versione 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="9ccd6-801">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="9ccd6-802">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="9ccd6-802">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="9ccd6-804">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="9ccd6-804">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="9ccd6-805">Excel</span><span class="sxs-lookup"><span data-stu-id="9ccd6-805">Excel</span></span>

- <span data-ttu-id="9ccd6-806">Il Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt+G.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-806">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="9ccd6-807">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-807">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="9ccd6-808">È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-808">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

### <a name="outlook"></a><span data-ttu-id="9ccd6-809">Outlook</span><span class="sxs-lookup"><span data-stu-id="9ccd6-809">Outlook</span></span>

- <span data-ttu-id="9ccd6-810">È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-810">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="9ccd6-811">È stato risolto un problema che causava la mancata visualizzazione dei suggerimenti per i criteri quando si usava un mittente alternativo.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-811">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="9ccd6-812">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-812">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="9ccd6-813">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="9ccd6-813">PowerPoint</span></span>

- <span data-ttu-id="9ccd6-814">È stato risolto un problema che causava la creazione di schemi duplicati quando si copiava una diapositiva da una presentazione a un'altra.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-814">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>
- <span data-ttu-id="9ccd6-815">Per i file con nuovi commenti moderni viene visualizzato un avviso di colore giallo se vengono aperti in una versione non supportata</span><span class="sxs-lookup"><span data-stu-id="9ccd6-815">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

### <a name="office-suite"></a><span data-ttu-id="9ccd6-816">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="9ccd6-816">Office Suite</span></span>

- <span data-ttu-id="9ccd6-817">È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-817">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="9ccd6-818">In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-818">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="9ccd6-819">È stato risolto un problema per cui, in alcuni casi, un aggiornamento non veniva applicato se l'utente non era un amministratore e non era disponibile la connettività di rete per l'account di sistema.</span><span class="sxs-lookup"><span data-stu-id="9ccd6-819">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

> [!NOTE]
> <span data-ttu-id="9ccd6-821">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="9ccd6-821">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (NON MODIFICARE IL CONTENUTO DEI METADATI DELL'INTERFACCIA DI AMMINISTRAZIONE)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.13127.20760|versione-2008-novembre-10|)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.13127.20638|versione-2008-ottobre-13|)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.13127.20408|versione-2008-settembre-08|)
[//]: # (|Win32|FRDC|Partecipanti al programma Office Insider| |16.0.12527.20988|versione-2002-agosto-11|)
[//]: # (| Win32 | FRDC | Partecipanti al programma Office Insider | | 16.0.12527.20880 | versione-2002-luglio-14 |)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
