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
ms.openlocfilehash: 6b50195e2e84292b0b4b1e259254592f2c4a591b
ms.sourcegitcommit: 568fdf9ae96367ef3a4f601128df80944dd265a7
ms.translationtype: HT
ms.contentlocale: it-IT
ms.lasthandoff: 02/10/2021
ms.locfileid: "50173655"
---
# <a name="release-notes-for-semi-annual-enterprise-channel"></a><span data-ttu-id="70b41-103">Note sulla versione del Canale Enterprise semestrale</span><span class="sxs-lookup"><span data-stu-id="70b41-103">Release notes for Semi-Annual Enterprise Channel</span></span>

<span data-ttu-id="70b41-104">Queste note sulla versione forniscono informazioni sulle nuove funzionalità e sugli aggiornamenti non relativi alla sicurezza inclusi negli aggiornamenti del Canale Enterprise semestrale per Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business e delle versioni in abbonamento delle app desktop per Project e Visio.</span><span class="sxs-lookup"><span data-stu-id="70b41-104">These release notes provide information about new features and non-security updates that are included in Semi-Annual Enterprise Channel updates for Microsoft 365 Apps for enterprise, Microsoft 365 Apps for business, and the subscription versions of the desktop apps for Project and Visio.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="70b41-105">Apporteremo alcune modifiche ai canali di aggiornamento per Microsoft 365 Apps, tra cui l'aggiunta di un nuovo canale di aggiornamento (Monthly Enterprise Channel) e la modifica dei nomi dei canali di aggiornamento già presenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-105">We’re making some changes to the update channels for Microsoft 365 Apps, including adding a new update channel (Monthly Enterprise Channel) and changing the names of the existing update channels.</span></span> <span data-ttu-id="70b41-106">Leggere [questo articolo](https://go.microsoft.com/fwlink/p/?linkid=2127441) per altre informazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-106">To learn more, [read this article](https://go.microsoft.com/fwlink/p/?linkid=2127441).</span></span>

> [!NOTE]
>
>- <span data-ttu-id="70b41-107">OneNote 2016 sarà ora incluso per impostazione predefinita quando un utente del Canale Enterprise scarica e installa Microsoft 365 Apps in Windows 10 dal portale di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-107">OneNote 2016 will now be included by default when a user on the Semi-Annual Enterprise Channel downloads and installs Microsoft 365 Apps on Windows 10 from the Office Portal.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2008-february-09"></a><span data-ttu-id="70b41-109">Versione 2008: 9 febbraio</span><span class="sxs-lookup"><span data-stu-id="70b41-109">Version 2008: February 09</span></span>
<span data-ttu-id="70b41-110">*Versione 2008 (Build 13127.21216)*</span><span class="sxs-lookup"><span data-stu-id="70b41-110">*Version 2008 (Build 13127.21216)*</span></span>

<span data-ttu-id="70b41-111">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-111">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-113">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-113">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-114">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-114">Excel</span></span>

- <span data-ttu-id="70b41-115">È stato risolto un problema che causava la chiusura imprevista di Excel quando si aprivano file UNC con attributi di file non validi (ora di creazione, ora di modifica e così via).</span><span class="sxs-lookup"><span data-stu-id="70b41-115">Fixed an issue where Excel would close unexpectedly when opening UNC files that have invalid file attributes (creation time, modified time, etc.)</span></span>


- <span data-ttu-id="70b41-116">È stato risolto un problema per cui le impostazioni dei separatori decimali e delle migliaia non venivano trasferite quando si copiava un grafico da Excel e lo si incollava in Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-116">We fixed an issue where decimal and thousands separators settings would not carry over when copying a chart from Excel and pasting into Word or PowerPoint.</span></span>


- <span data-ttu-id="70b41-117">È stato risolto un problema per cui le prestazioni di esecuzione di una macro relativa alla formattazione dell'intervallo di una Tabella pivot peggioravano ogni volta che la macro veniva eseguita.</span><span class="sxs-lookup"><span data-stu-id="70b41-117">We fixed an issue where the performance of running a macro involving PivotTable range formatting would get worse each time the macro is run.</span></span>


- <span data-ttu-id="70b41-118">È stato risolto un problema per cui le regole di formattazione condizionale venivano eliminate durante la copia o lo spostamento dei fogli in un'altra cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-118">We fixed an issue where conditional formatting rules were dropped when copying or moving sheets to another workbook.</span></span>


- <span data-ttu-id="70b41-119">È stato risolto un problema per cui gli utenti non potevano applicare etichette di riservatezza ai file Excel quando la schermata Start all'avvio dell'app era disabilitata.</span><span class="sxs-lookup"><span data-stu-id="70b41-119">We fixed an issue where users were unable to apply sensitivity labels to Excel files when the start screen on app boot was disabled.</span></span>


- <span data-ttu-id="70b41-120">È stato risolto un problema durante l'apertura di un file cloud dalla cartella di sincronizzazione OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-120">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="outlook"></a><span data-ttu-id="70b41-121">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-121">Outlook</span></span>

- <span data-ttu-id="70b41-122">È stato risolto un problema che causava talvolta l'arresto di Outlook quando si aggiungevano o si salvano allegati.</span><span class="sxs-lookup"><span data-stu-id="70b41-122">Addressed an issue which caused Outlook to stop working sporadically when adding or saving attachments.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="70b41-123">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-123">PowerPoint</span></span>

- <span data-ttu-id="70b41-124">È stato risolto un problema per cui il comando dimensioni del carattere, quando veniva aggiunto alla barra, eseguiva il completamento automatico alle dimensioni del carattere definite più vicine durante l'aggiornamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-124">We have fixed an issue where font size command, added in QAT, auto completes to the nearest defined font size while updating it.</span></span>


- <span data-ttu-id="70b41-125">È stato risolto un problema per cui copia e incolla di una diapositiva con l'opzione "Mantieni formattazione sorgente" a volte copiava in modo imprevisto su un nuovo schema diapositiva</span><span class="sxs-lookup"><span data-stu-id="70b41-125">Fixed an issue where copy and paste of a slide with 'keep source formatting' option would sometimes copy over a new slide master unexpectedly</span></span>


### <a name="word"></a><span data-ttu-id="70b41-126">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-126">Word</span></span>

- <span data-ttu-id="70b41-127">È stato risolto un problema relativo al rilevamento delle modifiche per cui talvolta, all'apertura di un documento di Word, veniva visualizzata una finestra di errore.</span><span class="sxs-lookup"><span data-stu-id="70b41-127">We fixed an issue in Track Changes which sometimes opening Word document might display error dialog.</span></span>


- <span data-ttu-id="70b41-128">È stato risolto un problema durante l'apertura di un file cloud dalla cartella di sincronizzazione OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-128">We fixed an issue in opening cloud file from OneDrive sync folder.</span></span>


### <a name="office-suite"></a><span data-ttu-id="70b41-129">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-129">Office Suite</span></span>

- <span data-ttu-id="70b41-130">È stato risolto un problema che impediva l'apertura corretta di un file in Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-130">Fixed an issue that prevented successful open of a file in Office.</span></span>


- <span data-ttu-id="70b41-131">È stato risolto un problema per cui i documenti che contenevano contorni a Mano libera applicati ai connettori tramite Copia formato potevano essere danneggiati.</span><span class="sxs-lookup"><span data-stu-id="70b41-131">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-february-09"></a><span data-ttu-id="70b41-133">Versione 2002: 9 febbraio</span><span class="sxs-lookup"><span data-stu-id="70b41-133">Version 2002: February 09</span></span>
<span data-ttu-id="70b41-134">*Versione 2002 (build 12527.21594)*</span><span class="sxs-lookup"><span data-stu-id="70b41-134">*Version 2002 (Build 12527.21594)*</span></span>

<span data-ttu-id="70b41-135">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-135">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-137">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-137">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="70b41-138">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-138">Office Suite</span></span>

- <span data-ttu-id="70b41-139">È stato risolto un problema per cui i documenti che contenevano contorni a Mano libera applicati ai connettori tramite Copia formato potevano essere danneggiati.</span><span class="sxs-lookup"><span data-stu-id="70b41-139">Fixed an issue where documents containing Sketched outlines applied to connectors via Format Painter could become corrupted.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-09"></a><span data-ttu-id="70b41-141">Versione 1908: 9 febbraio</span><span class="sxs-lookup"><span data-stu-id="70b41-141">Version 1908: February 09</span></span>
<span data-ttu-id="70b41-142">*Versione 1908 (Build 11929.21008)*</span><span class="sxs-lookup"><span data-stu-id="70b41-142">*Version 1908 (Build 11929.21008)*</span></span>

<span data-ttu-id="70b41-143">Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-143">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2008-january-12"></a><span data-ttu-id="70b41-144">Versione 2008: 12 gennaio</span><span class="sxs-lookup"><span data-stu-id="70b41-144">Version 2008: January 12</span></span>
<span data-ttu-id="70b41-145">*Versione 2008 (Build 13127.21064)*</span><span class="sxs-lookup"><span data-stu-id="70b41-145">*Version 2008 (Build 13127.21064)*</span></span>

<span data-ttu-id="70b41-146">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-146">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="70b41-148">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="70b41-148">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="70b41-149">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-149">Access</span></span>

- <span data-ttu-id="70b41-150">**Aumentare la produttività in Progettazione query, nella visualizzazione SQL e nella finestra Relazioni:** fare clic con il pulsante destro del mouse su una tabella per aprirla, progettarla, ridimensionarla e nasconderla.</span><span class="sxs-lookup"><span data-stu-id="70b41-150">**Be more productive working in Query Designer, SQL view, and the Relationships window:** Right-click a table to open, design, size, and hide it.</span></span> <span data-ttu-id="70b41-151">Cercare e sostituire il testo nella visualizzazione SQL.</span><span class="sxs-lookup"><span data-stu-id="70b41-151">Search and replace text in SQL View.</span></span> <span data-ttu-id="70b41-152">Selezionare più tabelle nella finestra Relazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-152">Select multiple tables in the Relationships window.</span></span>

- <span data-ttu-id="70b41-153">**Aggiungere tabelle con meno clic**: usare il riquadro attività Aggiungere tabelle, che resta aperto mentre si lavora, per aggiungere tabelle a relazioni e query.</span><span class="sxs-lookup"><span data-stu-id="70b41-153">**Add tables with fewer clicks:** Use the Add Tables task pane, which stays open while you work, to add tables to relationships and queries.</span></span> [<span data-ttu-id="70b41-154">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-154">Learn more</span></span>](https://support.office.com/article/56eb7df2-8a52-4e90-a7e0-8f891a5c56bd)

### <a name="excel"></a><span data-ttu-id="70b41-155">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-155">Excel</span></span>

- <span data-ttu-id="70b41-156">**Le tue funzioni Excel preferite sono diventate più veloci:** le funzioni SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS e MINIFS sono più veloci che mai.</span><span class="sxs-lookup"><span data-stu-id="70b41-156">**Your favorite Excel functions just got faster:** The SUMIFS, AVERAGEIFS, COUNTIFS, MAXIFS, and MINIFS functions are much faster than ever before.</span></span> <span data-ttu-id="70b41-157">Passa alla riga inferiore più rapidamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-157">Get to the bottom line more quickly.</span></span> <span data-ttu-id="70b41-158">Provane una ora.</span><span class="sxs-lookup"><span data-stu-id="70b41-158">Try one now.</span></span>

- <span data-ttu-id="70b41-159">**Miglioramenti di RealTimeData (RTD):** in Office 365 versione 2002 canale mensile e successiva, la funzione RealTimeData (RTD) di Excel è molto più veloce rispetto a Excel 2010 per il calcolo dei dati nel foglio di calcolo.</span><span class="sxs-lookup"><span data-stu-id="70b41-159">**Realtimedata (RTD) improvements:** In Office 365 version 2002 monthly channel and later, Excel's RealTimeData (RTD) function is much faster than Excel 2010 calculating data in the spreadsheet.</span></span> <span data-ttu-id="70b41-160">Sono stati rimossi i colli di bottiglia nelle strutture di memoria e di dati sottostanti oltre a renderlo thread-safe per consentirne il calcolo su tutti i thread disponibili di ricalcolo multithread (MTR).</span><span class="sxs-lookup"><span data-stu-id="70b41-160">We removed bottlenecks in its underlying memory and data structures as well as made it thread-safe to allow  it to be calculated on all available threads of Multithreaded recalculation (MTR).</span></span>

- <span data-ttu-id="70b41-161">**Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate.</span><span class="sxs-lookup"><span data-stu-id="70b41-161">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="70b41-162">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-162">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="70b41-163">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-163">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="70b41-164">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="70b41-164">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="70b41-165">**Creare tabelle pivot da set di documenti in Power BI all'interno di Excel:** è possibile creare tabelle pivot in Excel connesse ai set di documenti archiviati in Power BI in pochi click.</span><span class="sxs-lookup"><span data-stu-id="70b41-165">**Create PivotTables from Datasets in Power BI within Excel:** You can create PivotTables in Excel that are connected to datasets stored in Power BI with a few clicks.</span></span> <span data-ttu-id="70b41-166"> Questa operazione consente di sfruttare al meglio sia le tabelle pivot che Power BI.</span><span class="sxs-lookup"><span data-stu-id="70b41-166">Doing this allows you get the best of both PivotTables and Power BI.</span></span> <span data-ttu-id="70b41-167">Calcola, riepiloga e analizza i tuoi dati con le tabelle pivot dai set di dati sicuri di Power BI.</span><span class="sxs-lookup"><span data-stu-id="70b41-167">Calculate, summarize, and analyze your data with PivotTables from your secure Power BI datasets.</span></span> [<span data-ttu-id="70b41-168">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-168">Learn more</span></span>](https://support.office.com/article/31444a04-9c38-4dd7-9a45-22848c666884)<br /><span data-ttu-id="70b41-169">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="70b41-169">See details in [blog post](https://blog-insider.office.com/2020/06/11/use-power-bi-data-in-excel/)</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-170">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-170">Outlook</span></span>

- <span data-ttu-id="70b41-171">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-171">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="70b41-172">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="70b41-172">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="70b41-173">**Aggiornamento del calendario:** aggiornamenti visivi che rendono il calendario più facile da analizzare.</span><span class="sxs-lookup"><span data-stu-id="70b41-173">**Calendar gets a makeover:** See visual updates that make your calendar easier to scan.</span></span> [<span data-ttu-id="70b41-174">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-174">Learn more</span></span>](https://support.office.com/article/1c04e438-d84a-44fc-a404-170c9007e65c)<br /><span data-ttu-id="70b41-175">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span><span class="sxs-lookup"><span data-stu-id="70b41-175">See details in [blog post](https://blog-insider.office.com/2020/03/13/outlooks-calendar-gets-a-refresh/)</span></span>

- <span data-ttu-id="70b41-176">**Gli aggiornamenti dei calendari condivisi sono più veloci:** Outlook può aggiornare i calendari condivisi in Office 365 usando l'API REST.</span><span class="sxs-lookup"><span data-stu-id="70b41-176">**Shared calendar updates just got faster:** For shared calendars in Office 365, Outlook can update these calendars using the REST API.</span></span> <span data-ttu-id="70b41-177">Attivare l'anteprima per aggiornamenti più rapidi e affidabili ai calendari condivisi.</span><span class="sxs-lookup"><span data-stu-id="70b41-177">Turn on the preview for faster and more reliable updates to shared calendars.</span></span>

- <span data-ttu-id="70b41-178">**Trascinamento dei messaggi di posta elettronica in un gruppo di cui si è proprietari:** è possibile spostare e copiare messaggi e conversazioni trascinandoli dalla Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-178">**Drag email to a group you own:** Move and copy messages and conversations by dragging them from your inbox.</span></span> <span data-ttu-id="70b41-179">I messaggi trascinati verranno condivisi con tutti i membri del gruppo.</span><span class="sxs-lookup"><span data-stu-id="70b41-179">Messages you drag will be shared with all group members.</span></span><br /><span data-ttu-id="70b41-180">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span><span class="sxs-lookup"><span data-stu-id="70b41-180">See details in [blog post](https://blog-insider.office.com/2020/03/02/drag-messages-from-your-personal-inbox-to-the-group-mailbox/)</span></span>

- <span data-ttu-id="70b41-181">**Partecipare alle riunioni senza uscire dalla Posta in arrivo:** non è necessario passare al Calendario per partecipare alle riunioni online.</span><span class="sxs-lookup"><span data-stu-id="70b41-181">**Join meetings without leaving your inbox:** No need to switch to your calendar to join online meetings.</span></span> <span data-ttu-id="70b41-182">Con il Calendario aggiunto al riquadro Da fare, si può partecipare qualsiasi riunione con un semplice clic del mouse.</span><span class="sxs-lookup"><span data-stu-id="70b41-182">With the Calendar pinned to the To-Do pane, join any meeting with just one click.</span></span> [<span data-ttu-id="70b41-183">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-183">Learn more</span></span>](https://support.office.com/article/d8baa9d5-0645-41b8-9f36-b498a6c36064 )

- <span data-ttu-id="70b41-184">**Nuova esperienza per le reti Wi-Fi captive:** è mai capitato di connettersi a una rete Wi-Fi che richiede di accedere con una pagina Web?</span><span class="sxs-lookup"><span data-stu-id="70b41-184">**New experience for captive wifi networks:** Have you ever joined a wifi network that required a web page to sign in with?</span></span> <span data-ttu-id="70b41-185">Outlook ora consente di rimanere connessi in scenari di questo tipo.</span><span class="sxs-lookup"><span data-stu-id="70b41-185">Outlook now detects this and helps you get connected.</span></span><br /><span data-ttu-id="70b41-186">Vedere i dettagli nel [post di blog](https://insider.office.com/it-IT/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span><span class="sxs-lookup"><span data-stu-id="70b41-186">See details in [blog post](https://insider.office.com/it-IT/blog/outlook-on-public-wi-fi-networks-just-got-easier)</span></span>

- <span data-ttu-id="70b41-187">**Suggerimenti di posta elettronica per cercare una persona:** quando si digita il nome di una persona nella casella di ricerca, i messaggi di posta elettronica più importanti saranno inclusi nei suggerimenti di ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-187">**Get email suggestions when you search for a person:** When you type a person’s name in the Search box, the most relevant email messages will be included with your search suggestions.</span></span> [<span data-ttu-id="70b41-188">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-188">Learn more</span></span>](https://support.office.com/article/d824d1e9-a255-4c8a-8553-276fb895a8da)

- <span data-ttu-id="70b41-189">**Risultati migliori in un batter d'occhio:** l'esperienza di ricerca è stata aggiornata in modo da renderla più intelligente, più rapida e più affidabile che mai.</span><span class="sxs-lookup"><span data-stu-id="70b41-189">**Better results—in a jiffy:** We've updated the Search experience to make it smarter, faster, and more reliable than ever.</span></span> [<span data-ttu-id="70b41-190">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-190">Learn more</span></span>](https://support.office.com/article/96fee452-80cd-492d-a35c-5c37584b416b)

### <a name="powerpoint"></a><span data-ttu-id="70b41-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-191">PowerPoint</span></span>

- <span data-ttu-id="70b41-192">**GIF in un batter d'occhio:** una diapositiva, un frame.</span><span class="sxs-lookup"><span data-stu-id="70b41-192">**GIFs in a jiffy:** One slide, one frame.</span></span> <span data-ttu-id="70b41-193">Crea facilmente GIF a ripetizione continua in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-193">Easily create looping GIFs in PowerPoint.</span></span> [<span data-ttu-id="70b41-194">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-194">Learn more</span></span>](https://support.office.com/article/a598753e-92de-4f1b-8393-714db4d334b4)<br /><span data-ttu-id="70b41-195">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="70b41-195">See details in [blog post](https://blog-insider.office.com/2019/12/30/create-animated-gifs-using-powerpoint/)</span></span>

- <span data-ttu-id="70b41-196">**Collegamento a una diapositiva:** è possibile chiedere a un collega di contribuire a una presentazione e indirizzalo direttamente alla diapositiva per la quale serve assistenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-196">**Link to a slide:** Ask a colleague to contribute to your slide deck, and start them directly on the slide you need help with.</span></span> [<span data-ttu-id="70b41-197">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-197">Learn more</span></span>](https://support.office.com/article/4f5f3d5e-1674-4742-8cf1-9623050c19ef)<br /><span data-ttu-id="70b41-198">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span><span class="sxs-lookup"><span data-stu-id="70b41-198">See details in [blog post](https://blog-insider.office.com/2020/02/12/share-a-link-to-a-specific-slide/)</span></span>

- <span data-ttu-id="70b41-199">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-199">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="70b41-200">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="70b41-200">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="70b41-201">**Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate.</span><span class="sxs-lookup"><span data-stu-id="70b41-201">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="70b41-202">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-202">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="70b41-203">**Diagrammi migliori:** connettori più efficienti e un processo di conversione dell'input penna più fluido consentono di dare forma alle idee più facilmente.</span><span class="sxs-lookup"><span data-stu-id="70b41-203">**Better diagrams:** With better connectors and a smoother ink conversion process you can ink your ideas more confidently.</span></span> [<span data-ttu-id="70b41-204">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-204">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)

- <span data-ttu-id="70b41-205">**Prestazioni di video Stream migliorate in PowerPoint:** sono stati apportati miglioramenti alle prestazioni di riproduzione dei video di Microsoft Stream per ridurre al minimo i tempi di caricamento dei video e creare un'esperienza di visualizzazione fluida.</span><span class="sxs-lookup"><span data-stu-id="70b41-205">**Improved Stream video performance in PowerPoint:** We’ve made improvements to the playback performance of Microsoft Stream videos to minimize video loading time and create a smooth viewing experience.</span></span> <span data-ttu-id="70b41-206">I video aziendali su Microsoft Stream consentono di creare presentazioni migliori.</span><span class="sxs-lookup"><span data-stu-id="70b41-206">Use your corporate videos from Microsoft Stream to create better presentations.</span></span>

- <span data-ttu-id="70b41-207">**Ottenere l'attenzione tramite \@menzioni:** è possibile usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="70b41-207">**Get their attention with \@mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="70b41-208">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-208">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="70b41-209">**Sincronizzazione delle modifiche durante la presentazione:** è possibile sincronizzare le modifiche in qualsiasi momento vengano apportate, anche in modalità presentazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-209">**Synchronize changes while you are presenting:** Synchronize changes whenever they are made even when the presentation is in slide show mode.</span></span> [<span data-ttu-id="70b41-210">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-210">Learn more</span></span>](https://support.office.com/article/5a2921a9-97d4-436b-b0cd-295dfe2236bb)<br /><span data-ttu-id="70b41-211">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span><span class="sxs-lookup"><span data-stu-id="70b41-211">See details in [blog post](https://blog-insider.office.com/2020/04/08/synchronize-changes-while-presenting/)</span></span>

- <span data-ttu-id="70b41-212">**Commenti:** la nuova esperienza di commento in PowerPoint consente di individuare e aggiungere i commenti ai documenti in modo semplice e rapido.</span><span class="sxs-lookup"><span data-stu-id="70b41-212">**Comments:** The new commenting experience in PowerPoint allows you to quickly and easily discover and add comments to your documents.</span></span> <span data-ttu-id="70b41-213">È possibile modernizzare i flussi di lavoro di collaborazione con nuove funzionalità, come l'ancoraggio di commenti, la risoluzione, le attività, le notifiche di menzione migliorate e molto altro.</span><span class="sxs-lookup"><span data-stu-id="70b41-213">Modernize your collaboration workflows with new features like comment anchoring, resolve, tasks, improved mention notifications, and much more.</span></span> [<span data-ttu-id="70b41-214">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-214">Learn more</span></span>](https://support.office.com/article/c0aa37bb-82cb-414c-872d-178946ff60ec)

### <a name="word"></a><span data-ttu-id="70b41-215">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-215">Word</span></span>

- <span data-ttu-id="70b41-216">**Lazo dell'input penna:** lo strumento Lazo della scheda Disegno consente di selezionare gli oggetti disegnati con l'input penna.</span><span class="sxs-lookup"><span data-stu-id="70b41-216">**Lasso your ink:** The Lasso tool on the Draw tab helps you select objects drawn with ink.</span></span> <span data-ttu-id="70b41-217">È possibile selezionare singoli tratti o parole intere.</span><span class="sxs-lookup"><span data-stu-id="70b41-217">Select individual strokes, or whole words.</span></span> [<span data-ttu-id="70b41-218">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-218">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="70b41-219">**Selezionare il colore perfetto:** usare i codici colore esadecimali per scegliere esattamente il colore desiderato per il tipo di carattere, l’evidenziatore del testo e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-219">**Pick the perfect color:** Use hex color codes to choose exactly the color you want for your font, text highlight, and more.</span></span><br /><span data-ttu-id="70b41-220">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span><span class="sxs-lookup"><span data-stu-id="70b41-220">See details in [blog post](https://blog-insider.office.com/2020/02/19/hex-color-values-in-color-picker/)</span></span>

- <span data-ttu-id="70b41-221">**Grafici a mappa migliorati:** i grafici a mappa sono stati migliorati integrandoli con i tipi di dati geografici di Excel, che possono rivelare informazioni dettagliate sulle posizioni mappate.</span><span class="sxs-lookup"><span data-stu-id="70b41-221">**Improved map charts:** We've made map charts better by integrating them with Excel's Geographic Data Types, which can reveal rich information about your mapped locations.</span></span> [<span data-ttu-id="70b41-222">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-222">Learn more</span></span>](https://support.office.com/article/f2cfed55-d622-42cd-8ec9-ec8a358b593b)

- <span data-ttu-id="70b41-223">**Conferma dell'azione nelle utilità per la lettura dello schermo:** la conferma dell'azione rappresenta un requisito importante per l'accessibilità.</span><span class="sxs-lookup"><span data-stu-id="70b41-223">**Confirmation of action in screen readers:** Confirmation of action is an important accessibility requirement.</span></span> <span data-ttu-id="70b41-224">Con l'introduzione di una nuova API di notifica di Windows, è ora possibile avvisare gli utenti delle utilità per la lettura dello schermo della riuscita delle azioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-224">With the introduction of a new Notification API from Windows, we are now able to alert screen reader users about the success of their actions.</span></span> <span data-ttu-id="70b41-225">I comandi taglia, copia, incolla, grassetto, corsivo, sottolineato, annulla, ripristina, correzione automatica e maiuscole automatiche ora sono tutti annunciati agli utenti dell'Assistente vocale in Win32 Word.</span><span class="sxs-lookup"><span data-stu-id="70b41-225">Cut, copy, paste, bold, italic, underline, undo, redo, auto corrections, and auto-capitalizations are now all announced to Narrator users in Win32 Word.</span></span> <span data-ttu-id="70b41-226">Per abilitare questa funzionalità, attivare l'Assistente vocale premendo il tasto Windows + CTRL + INVIO.</span><span class="sxs-lookup"><span data-stu-id="70b41-226">To enable this feature, turn on Narrator by pressing windows + ctrl + enter.</span></span><br /><span data-ttu-id="70b41-227">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="70b41-227">See details in [blog post](https://blog-insider.office.com/2020/06/05/confirmation-of-action-in-word-for-windows/)</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-228">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-228">Office Suite</span></span>

- <span data-ttu-id="70b41-229">**Etichette di riservatezza**: è ora possibile applicare un'etichetta di riservatezza configurata dall'organizzazione per richiedere autorizzazioni personalizzate.</span><span class="sxs-lookup"><span data-stu-id="70b41-229">**Sensitivity labels:** You can now apply a sensitivity label that your organization has configured to prompt you for custom permissions.</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-232">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-232">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="70b41-233">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-233">Access</span></span>

- <span data-ttu-id="70b41-234">È stato risolto un problema che causava la chiusura imprevista dell'applicazione durante l'uso della finestra Zoom.</span><span class="sxs-lookup"><span data-stu-id="70b41-234">Fixed an issue where the application would  close unexpectedly when using Zoom window.</span></span>


- <span data-ttu-id="70b41-235">Questa correzione risolve un problema per cui il tentativo di eseguire determinate query generava il messaggio di errore 'La query è troppo complessa'.</span><span class="sxs-lookup"><span data-stu-id="70b41-235">This fix addresses the issue where trying to run certain queries have previously produced the error message 'Query is too complex'.</span></span>


- <span data-ttu-id="70b41-236">Questa modifica risolve un problema che poteva causare la chiusura imprevista di Access durante l'avvio della casella di Zoom (MAIUSC + F2) per la modifica del testo.</span><span class="sxs-lookup"><span data-stu-id="70b41-236">This change fixes an issue that could cause Access to to close unexpectedly when launching the Zoom box (Shift + F2) to edit text.</span></span>


- <span data-ttu-id="70b41-237">È stato risolto un problema relativo all'inserimento di tabelle SQL collegate che includono un campo identità, ad esempio numerazione automatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-237">Resolved an issue with inserting linked SQL tables that include an identity (e.g. autonumber) field.</span></span>


- <span data-ttu-id="70b41-238">È stato risolto un problema relativo all'esecuzione di una query che richiedeva circa due volte il tempo necessario per il completamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-238">We fixed an issue where query execution was taking approximately twice as long to complete than expected.</span></span>


- <span data-ttu-id="70b41-239">È stato risolto un problema per cui ora è possibile usare il tipo di dato data/ora esteso nel codice senza subire alcun arresto anomalo dell'app.</span><span class="sxs-lookup"><span data-stu-id="70b41-239">Fixed an issue to be able to call the Date/Time Extended data type into your code without experiencing any issues in your app.</span></span>


- <span data-ttu-id="70b41-240">È stato risolto un problema che consente ora di tornare alla versione di Access più aggiornata e usare DAO/VBA per gestire e modificare un tipo di dati decimale.</span><span class="sxs-lookup"><span data-stu-id="70b41-240">Fixed an issue so you can now revert back to your most updated Access version, and use DAO/VBA to manage and edit a decimal data type.</span></span>


- <span data-ttu-id="70b41-241">È stato risolto un problema durante il tentativo di utilizzo del generatore DSN ODBC</span><span class="sxs-lookup"><span data-stu-id="70b41-241">We fixed an error issue when trying to use ODBC DSN builder</span></span>


- <span data-ttu-id="70b41-242">Questo problema è stato risolto. ora è possibile usare il driver ODBC all'esterno delle applicazioni a portata di clic di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-242">This issue has been resolved - you can now use our ODBC driver outside of Office's Click-to-Run applications.</span></span>


### <a name="excel"></a><span data-ttu-id="70b41-243">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-243">Excel</span></span>

- <span data-ttu-id="70b41-244">È possibile che si sia verificata la classificazione automatica dei documenti per le cartelle di lavoro in modalità di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="70b41-244">Automatic document classification may have occurred for workbooks that were in read-only mode.</span></span>


- <span data-ttu-id="70b41-245">È stato risolto un problema che può verificarsi quando si cerca di creare una connessione dati, se l’utente si è disconnesso dal proprio account.</span><span class="sxs-lookup"><span data-stu-id="70b41-245">Fixed an issue that could happen when trying to create a data connection if you have signed out from your account.</span></span>


- <span data-ttu-id="70b41-246">È stato corretto un bug relativo alle API PivotDateFilter, per cui le condizioni di filtro "prima" e "dopo" erano invertite.</span><span class="sxs-lookup"><span data-stu-id="70b41-246">Fixed a bug with PivotDateFilter APIs in which 'Before' and 'After' filter conditions were reversed.</span></span>


- <span data-ttu-id="70b41-247">È stato risolto un problema per cui Excel poteva chiudersi inaspettatamente nel tentativo di inserire tabelle pivot in un foglio grafico.</span><span class="sxs-lookup"><span data-stu-id="70b41-247">Addressed an issue where Excel may close unexpectedly when attempting to insert PivotTables into a chart sheet.</span></span>


- <span data-ttu-id="70b41-248">È stato risolto un problema per cui non era possibile modificare le tabelle pivot e le cartelle di lavoro non potevano essere salvate se venivano esportate dal piano del progetto.</span><span class="sxs-lookup"><span data-stu-id="70b41-248">Fixed an issue where pivot tables could not be edited and workbooks could not be saved if they were exported from Project plan.</span></span>


- <span data-ttu-id="70b41-249">È possibile che si verifichi un errore quando si prova a salvare un file che contiene una formula usando la funzione LET().</span><span class="sxs-lookup"><span data-stu-id="70b41-249">An error could occur when trying to save a file that contains a formula using the LET() function.</span></span>


- <span data-ttu-id="70b41-250">È stato risolto un problema in cui, in alcuni casi, erano visualizzate più barre dei messaggi quando un file era aperto in modalità di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="70b41-250">We fixed an issue where in some cases, multiple message bars were appearing when a file was opened in read-only mode.</span></span>


- <span data-ttu-id="70b41-251">È stato risolto un problema per cui i subtotali della struttura potevano non funzionare più quando erano presenti molti valori di intestazione di colonna duplicati.</span><span class="sxs-lookup"><span data-stu-id="70b41-251">We fixed an issue where outline sub-totals could stop working when there were many duplicate column header values.</span></span>


- <span data-ttu-id="70b41-252">È stato risolto un problema che consente di aggiornare i dati della tabella pivot quando si aprono i dati di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="70b41-252">Fixed an issue where read-only books would no longer refresh pivot table data when opened.</span></span>


- <span data-ttu-id="70b41-253">Questa modifica corregge il problema seguente: l'icona "Inserisci oggetto" di Excel non viene visualizzata quando si inserisce un file dalla cartella di sincronizzazione locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-253">This change provides a fix for the following issue: Excel "Insert Object" does not show correct icon when inserts a file from OneDrive local sync folder.</span></span>


- <span data-ttu-id="70b41-254">È stato risolto un problema per cui Excel smetteva di funzionare quando era presente un aggiornamento di un oggetto Criteri di gruppo, ad esempio, tramite aggiornamento remoto dei criteri di gruppo, durante il ricalcolo multithread.</span><span class="sxs-lookup"><span data-stu-id="70b41-254">We fixed an issue where Excel would stop working when there is a Group Policy Object update (e.g. via Remote Group Policy Refresh) during multithreaded recalc.</span></span>


- <span data-ttu-id="70b41-255">È stato risolto un problema per cui Excel smetteva di funzionare quando gli utenti usavano la funzione subtotale su più di 255 colonne.</span><span class="sxs-lookup"><span data-stu-id="70b41-255">We fixed an issue where Excel would stop working when users use the subtotal function on more than 255 columns.</span></span>


- <span data-ttu-id="70b41-256">È stata migliorata la crenatura del testo in PowerPoint quando il contenuto viene copiato da Excel e incollato in PowerPoint con l'opzione Incorpora.</span><span class="sxs-lookup"><span data-stu-id="70b41-256">Improved text kerning in PowerPoint when when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="70b41-257">È stato risolto un problema che impediva il passaggio dall'anteprima della tabella all'editor di Query in PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="70b41-257">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="70b41-258">È stato risolto un problema per cui un utente non era in grado di aprire un file atomsvc (UTF8 + BOM) direttamente da SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-258">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="70b41-259">È stato risolto un problema per cui i clienti ricevono una notifica errata su una nuova versione del file durante la creazione condivisa.</span><span class="sxs-lookup"><span data-stu-id="70b41-259">Fixed an issue where customers would incorrectly get notified about a new version of the file when coauthoring.</span></span>


- <span data-ttu-id="70b41-260">È stato risolto un problema che causava l'avanzamento di caratteri extra durante l'uso di IME nella modalità di sovrascrittura.</span><span class="sxs-lookup"><span data-stu-id="70b41-260">Fixed an editing issue where using IME with Overwrite mode would incorrectly advance extra characters.</span></span>


- <span data-ttu-id="70b41-261">È stato risolto un problema quando si usano dati in tempo reale i combinazione con la funzionalità di ricalcolo multithread.</span><span class="sxs-lookup"><span data-stu-id="70b41-261">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality.</span></span>


- <span data-ttu-id="70b41-262">Corregge un problema per cui Excel non si avvia o si arresta in modo imprevisto se sono in uso determinate impostazioni di protezione da exploit di Sicurezza di Windows (SimExec, CallerCheck)</span><span class="sxs-lookup"><span data-stu-id="70b41-262">Fixes an issue where Excel would fail to launch or crash unexpectedly if certain Windows Security exploit protection settings (SimExec, CallerCheck) are in use</span></span>


- <span data-ttu-id="70b41-263">È stato risolto un problema che causava l'arresto anomalo di Excel in determinate circostanze quando si usa Copia formato.</span><span class="sxs-lookup"><span data-stu-id="70b41-263">Fixed an issue where Excel could close unexpectedly in certain circumstances when using the Format Painter.</span></span>


- <span data-ttu-id="70b41-264">È stato risolto un problema che impediva agli utenti di modificare un filtro della tabella pivot perché era configurato su un valore non più presente nel database Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="70b41-264">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


- <span data-ttu-id="70b41-265">È stato risolto un problema per cui Excel poteva arrestarsi in modo anomalo quando si usa la funzionalità Analisi rapida dopo aver bloccato la riga superiore del foglio.</span><span class="sxs-lookup"><span data-stu-id="70b41-265">Fixed an issue where Excel could close unexpectedly when using the Quick Analysis after freezing the top row of the sheet.</span></span>


- <span data-ttu-id="70b41-266">È stato risolto un problema per cui alcune funzioni avrebbero avuto un risultato errato dopo il caricamento di una cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-266">We fixed an issue where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="70b41-267">È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto, correlato ai riferimenti del componente aggiuntivo XLAM e agli intervalli denominati.</span><span class="sxs-lookup"><span data-stu-id="70b41-267">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="70b41-268">È stato risolto un problema relativo all'uso di una macro per impostare la proprietà FormulaR1C1 per un intervallo. I riferimenti di cella era corretto se un foglio grafico era il foglio attivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-268">We fixed an issue where using a macro to set the FormulaR1C1 property for a range, the cell references would be incorrect if a chart sheet was the active sheet.</span></span>


- <span data-ttu-id="70b41-269">È stato risolto un problema che causava la visualizzazione del messaggio "Excel ha esaurito le risorse durante il tentativo di calcolare una o più formule".</span><span class="sxs-lookup"><span data-stu-id="70b41-269">Fixed an issue which could cause an error that "Excel ran out of resources while attempting to calculate one or more formulas".</span></span>


- <span data-ttu-id="70b41-270">È stato risolto un problema per cui, quando si selezionava lo spagnolo come lingua di Office, gli elenchi di convalida dei dati non mostravano tutti gli elementi.</span><span class="sxs-lookup"><span data-stu-id="70b41-270">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="70b41-271">È stato risolto un problema che poteva causare un blocco durante l'aggiornamento delle tabelle pivot OLAP.</span><span class="sxs-lookup"><span data-stu-id="70b41-271">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="70b41-272">È stato risolto un problema a causa del quale la personalizzazione CustomUI XML per la scheda della barra multifunzione era rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-272">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>


- <span data-ttu-id="70b41-273">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="70b41-273">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>


- <span data-ttu-id="70b41-274">È stato risolto un problema per cui, in alcuni casi, se si faceva clic su un collegamento ipertestuale a una posizione nella stessa cartella di lavoro, la cartella di lavoro veniva nascosta.</span><span class="sxs-lookup"><span data-stu-id="70b41-274">Fixed an issue where in some cases, clicking a hyperlink to a place within the same workbook will cause the workbook to be hidden.</span></span>


- <span data-ttu-id="70b41-275">Application.Evaluate (VBA) talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="70b41-275">Application.Evaluate (VBA) was not working for User-defined functions in some cases.</span></span>


- <span data-ttu-id="70b41-276">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="70b41-276">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


- <span data-ttu-id="70b41-277">È stato risolto un problema che in alcuni casi causava la chiusura imprevista di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="70b41-277">Fixed an issue which would cause Excel to close unexpectedly in some cases after copying a sheet containing a PivotTable.</span></span>


- <span data-ttu-id="70b41-278">È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file se il percorso del file è troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="70b41-278">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>


- <span data-ttu-id="70b41-279">È stato risolto un problema legato all'uso dei dati in tempo reale in combinazione con la funzionalità di ricalcolo multithread, che causava la chiusura imprevista dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-279">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="70b41-280">È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento se la cartella di lavoro di origine era chiusa.</span><span class="sxs-lookup"><span data-stu-id="70b41-280">Addressed an issue where external links don't update on fill if the source book is closed.</span></span>


- <span data-ttu-id="70b41-281">È stato risolto un problema che poteva generare un avviso su una cartella di lavoro danneggiata se conteneva formule con SE.NON.DISP.().</span><span class="sxs-lookup"><span data-stu-id="70b41-281">Fixed an issue that could cause a warning about a corrupt workbook if it contained formulas using IFNA().</span></span>


- <span data-ttu-id="70b41-282">È stato risolto un problema per cui ora Power Pivot riconosce il delimitatore di tabulazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-282">We fixed an issue where Power Pivot will now successfully recognize tab delimiter.</span></span>


### <a name="onenote"></a><span data-ttu-id="70b41-283">OneNote</span><span class="sxs-lookup"><span data-stu-id="70b41-283">OneNote</span></span>

- <span data-ttu-id="70b41-284">Informazioni per gli utenti tramite la Barra informazioni sulle rettifiche temporanee in Microsoft OneNote che consentono di migliorare la sincronizzazione e la disponibilità dei servizi durante i picchi di utilizzo in tutto il mondo.</span><span class="sxs-lookup"><span data-stu-id="70b41-284">Inform users through the InfoBar about temporary adjustments in Microsoft OneNote that will help improve sync and service availability during high worldwide usage.</span></span>


- <span data-ttu-id="70b41-285">Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-285">Improved sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>


- <span data-ttu-id="70b41-286">È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.</span><span class="sxs-lookup"><span data-stu-id="70b41-286">Improved detection of co-authoring status to reduce resource utilization.</span></span>


- <span data-ttu-id="70b41-287">Miglioramento della sincronizzazione e della stabilità del servizio modificando temporaneamente la frequenza con cui vengono create le cronologie delle versioni delle pagine.</span><span class="sxs-lookup"><span data-stu-id="70b41-287">Improved sync and service stability by temporarily altering how frequently page version histories are created.</span></span>


- <span data-ttu-id="70b41-288">Miglioramento della sincronizzazione e della stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-288">Improved sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="70b41-289">Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.</span><span class="sxs-lookup"><span data-stu-id="70b41-289">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>


- <span data-ttu-id="70b41-290">Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-290">Improved sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="70b41-291">I blocchi appunti locali non vengono interessati da questa operazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-291">Local notebooks are not impacted by this measure.</span></span>


- <span data-ttu-id="70b41-292">Miglioramento della sincronizzazione e della stabilità del servizio disabilitando temporaneamente lo spostamento delle pagine nel Cestino.</span><span class="sxs-lookup"><span data-stu-id="70b41-292">Improved sync and service stability by temporarily disabling moving pages into the recycle bin.</span></span> <span data-ttu-id="70b41-293">Agli utenti che vogliono eliminare una pagina verrà mostrata una finestra di dialogo in cui viene chiesto se si vuole eliminare la pagina definitivamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-293">Users who want to delete a page will instead be shown a dialog asking if they'd want to permanently delete the page.</span></span>


- <span data-ttu-id="70b41-294">È stato risolto un problema per cui il menu del controllo ortografico non veniva caricato.</span><span class="sxs-lookup"><span data-stu-id="70b41-294">We fixed an issue where the spelling menu was not loading.</span></span>


### <a name="outlook"></a><span data-ttu-id="70b41-295">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-295">Outlook</span></span>

- <span data-ttu-id="70b41-296">È stato risolto un problema per cui le esperienze connesse facoltative bloccavano il caricamento dei componenti web aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-296">We fixed an issue where optional connected experiences blocked web add-ins from loading.</span></span>  <span data-ttu-id="70b41-297">Altri dettagli:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span><span class="sxs-lookup"><span data-stu-id="70b41-297">See more detail here:  https://developer.microsoft.com/en-us/office/blogs/outlook-add-ins-and-optional-connected-experiences/</span></span>


- <span data-ttu-id="70b41-298">È stato risolto un problema per cui gli utenti ora possono disabilitare IRM (Information Rights Management) per Outlook senza doverlo disabilitare per il resto delle applicazioni di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-298">We fixed an issue where users can now disable IRM (Information Rights Management) for Outlook without having to disable it for the rest of the Office applications.</span></span>


- <span data-ttu-id="70b41-299">È stato risolto un problema che impediva agli utenti di concedere le autorizzazioni di Editor ai delegati.</span><span class="sxs-lookup"><span data-stu-id="70b41-299">We fixed an issue that caused users to be unable to grant Editor permission to their delegates.</span></span>


- <span data-ttu-id="70b41-300">È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto se gli utenti selezionavano un risultato della ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-300">We fixed an issue that caused users to experience the application to terminate unexpectedly when selecting a search result.</span></span>


- <span data-ttu-id="70b41-301">Risolve un problema che faceva sì che gli utenti che tentavano di creare una convocazione di riunione da un account secondario aggiunto al loro profilo non vedessero uno spazio da: campo al posto del loro indirizzo e-mail.</span><span class="sxs-lookup"><span data-stu-id="70b41-301">Fixes an issue that caused users who attempted to create a meeting request from a secondary account added to their profile to not see a blank From: field instead of their email address.</span></span>


- <span data-ttu-id="70b41-302">Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.</span><span class="sxs-lookup"><span data-stu-id="70b41-302">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


- <span data-ttu-id="70b41-303">È stato risolto un problema che causava il mancato retrazione delle riunioni dal calendario di un responsabile in alcuni casi.</span><span class="sxs-lookup"><span data-stu-id="70b41-303">Addressed an issue that caused meetings to fail to be removed from a manager's calendar when declined by a delegate in some circumstances.</span></span>


- <span data-ttu-id="70b41-304">È stato risolto un problema che impediva ad alcuni utenti della funzionalità Miglioramenti dei Calendar - Calendario di Outlook condivisi di visualizzare un calendario condiviso appena aggiunto.</span><span class="sxs-lookup"><span data-stu-id="70b41-304">Addressed an issue that prevented some users of the Shared Calendar Improvements feature from being able to view a newly-added shared calendar.</span></span>


- <span data-ttu-id="70b41-305">Risolve un problema che impediva agli utenti di chiudere i calendari condivisi facendo clic sulla "X" nell'angolo.</span><span class="sxs-lookup"><span data-stu-id="70b41-305">Addresses an issue that caused users to be unable to close shared calendars by clicking on the "X" in the corner.</span></span>


- <span data-ttu-id="70b41-306">È stato risolto un problema per cui l'impostazione "Attiva miglioramenti calendari condivisi " talvolta non veniva applicata ai calendari condivisi esistenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-306">Addresses an issue that caused the "Turn on shared calendar improvements" setting to sometimes fail to apply to existing shared calendars.</span></span>


- <span data-ttu-id="70b41-307">È stato risolto un problema per cui le ricerche nei calendari di gruppo non restituivano alcun risultato.</span><span class="sxs-lookup"><span data-stu-id="70b41-307">We fixed an issue that caused searches in Group calendars fail to return any results.</span></span>


- <span data-ttu-id="70b41-308">Risolve un problema che faceva sì che gli utenti sperimentassero occasionalmente delle chiusure impreviste durante l’interazione con gli allegati cloud.</span><span class="sxs-lookup"><span data-stu-id="70b41-308">Fixes an issue that caused users to experience occasional closures when interacting with Cloud attachments.</span></span>


- <span data-ttu-id="70b41-309">È stato risolto un problema che causava la chiusura anomala di CLP cambiando l'indirizzo Da in una risposta da un contesto protetto a uno non protetto.</span><span class="sxs-lookup"><span data-stu-id="70b41-309">Addressed an issue that caused users of CLP to experience an issue when switching the from address on a reply from a protected context to an unprotected one.</span></span>


- <span data-ttu-id="70b41-310">È stato risolto un problema per cui, all'apertura di un allegato cloud, gli utenti visualizzavano un messaggio di errore nella pagina Safelinks anziché il documento che stavano provando ad aprire.</span><span class="sxs-lookup"><span data-stu-id="70b41-310">Addresses an issue that caused users to see an error on the safelinks page instead of the document they were trying to open when opening a cloud attachment.</span></span>


- <span data-ttu-id="70b41-311">È stato risolto un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="70b41-311">Addressed an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>


- <span data-ttu-id="70b41-312">È stato risolto un problema relativo all'evento di controllo CLP per l'etichetta di risposta/inoltra.</span><span class="sxs-lookup"><span data-stu-id="70b41-312">Addressed an issue with the clp auditing event for the reply/forward label.</span></span>


- <span data-ttu-id="70b41-313">È stato risolto un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="70b41-313">Addressed an issue that caused the width of the folder pane to change unexpectedly.</span></span>


- <span data-ttu-id="70b41-314">È stato risolto un problema per cui il campo A: era vuoto quando si inviava una relazione sullo stato di un’attività.</span><span class="sxs-lookup"><span data-stu-id="70b41-314">We fixed an issue that caused the To: field to be empty when sending a status report on a Task.</span></span>


- <span data-ttu-id="70b41-315">È stato risolto un problema che causava l'interruzione dell'evento MailItem.BeforeAttachmentAdd.</span><span class="sxs-lookup"><span data-stu-id="70b41-315">We fixed an issue that caused the MailItem.BeforeAttachmentAdd event to be broken.</span></span>


- <span data-ttu-id="70b41-316">È stato risolto un problema a causa del quale gli utenti visualizzavano la data di creazione degli allegati copiati nel file system tramite il trascinamento fissata all’1 gennaio 4501.</span><span class="sxs-lookup"><span data-stu-id="70b41-316">Addressed an issue that caused users to see the creation date of  attachments that they copied to their file system via drag and drop getting  set to January 1, 4501.</span></span>


- <span data-ttu-id="70b41-317">È stato risolto un problema che causava la visualizzazione errata dei nomi file degli utenti di alcuni set di caratteri durante l'aggiunta di un collegamento Smart a un file di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-317">Addressed an issue that caused users of some character sets to see file names display incorrectly when adding a Smart Link to a SharePoint file.</span></span>


- <span data-ttu-id="70b41-318">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'aggiornamento delle regole in Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-318">Addressed an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>


- <span data-ttu-id="70b41-319">È stato risolto un problema che causava il mancato recupero di suggerimenti per la ricerca da parte di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-319">Addressed an issue that caused Outlook to fail to retrieve search suggestions.</span></span>


- <span data-ttu-id="70b41-320">È stato risolto un problema a causa del quale gli utenti dei miglioramenti del Calendario di Outlook condivisi visualizzavano errori di Calendario di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-320">Addressed an issue that caused users of the Shared Calendar improvements to see calendar failures.</span></span>


- <span data-ttu-id="70b41-321">È stato risolto un problema che causava blocchi o arresti intermittenti in alcune situazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-321">Addressed an issue that caused users to experience intermittent hangs and closures in some scenarios.</span></span>


- <span data-ttu-id="70b41-322">È stato risolto un problema che causava problemi per gli utenti quando si cancellano 4 o più messaggi di posta elettronica da un account POP quando l'opzione "Scarica solo intestazioni" è selezionata.</span><span class="sxs-lookup"><span data-stu-id="70b41-322">Addressed an issue which caused users to experience an issue when deleting 4 or more emails from a POP account with the "Download Headers Only" option selected.</span></span>


- <span data-ttu-id="70b41-323">È stato risolto un problema che provocava errori intermittenti quando i delegati aprivano cartelle condivise in altre cassette postali.</span><span class="sxs-lookup"><span data-stu-id="70b41-323">Addressed an issue that caused delegates to see intermittent failures when opening shared folders in another mailbox.</span></span>


- <span data-ttu-id="70b41-324">È stato risolto un problema che ha causato l'invio di messaggi di posta elettronica generati automaticamente con un corpo vuoto quando la riga dell'oggetto è vuota.</span><span class="sxs-lookup"><span data-stu-id="70b41-324">Addressed an issue that caused some automatically generated emails to be sent with a blank body when the subject line is blank.</span></span>


- <span data-ttu-id="70b41-325">Risolto un problema per cui l'opzione "Consenti inoltro" non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="70b41-325">Addressed an issue that caused the "Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>


- <span data-ttu-id="70b41-326">È stato risolto un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un manager.</span><span class="sxs-lookup"><span data-stu-id="70b41-326">Addressed an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>


- <span data-ttu-id="70b41-327">È stato risolto un problema che causava un problema nelle applicazioni MAPI di terza parte.</span><span class="sxs-lookup"><span data-stu-id="70b41-327">Addressed an issue that caused users to experience an issue in third party MAPI applications.</span></span>


- <span data-ttu-id="70b41-328">È stato risolto un problema che causava la chiusura imprevista di Outlook aprendo file .msg o .oft salvati in locale dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="70b41-328">Addressed an issue that caused Outlook to close unexpectedly when opening .msg or .oft files that were saved locally after a Windows update.</span></span>


- <span data-ttu-id="70b41-329">È stato risolto un problema che causava la chiusura imprevista di Outlook in alcune build di Windows.</span><span class="sxs-lookup"><span data-stu-id="70b41-329">Addressed an issue that caused Outlook to close unexpectedly on some builds of Windows.</span></span>


- <span data-ttu-id="70b41-330">È stato risolto un problema che mostrava agli utenti di Windows 10 l’avviso "Stato dell’antivirus: non valido".</span><span class="sxs-lookup"><span data-stu-id="70b41-330">Addressed an issue that caused users of Windows 10 server versions to see the warning "Antivirus status: Invalid.</span></span> <span data-ttu-id="70b41-331">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun antivirus, anche se è stato installato correttamente l’antivirus.</span><span class="sxs-lookup"><span data-stu-id="70b41-331">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus correctly installed.</span></span>


- <span data-ttu-id="70b41-332">È stato risolto un problema che causava la chiusura imprevista, da parte di alcuni utenti, dell'applicazione per l'invio di messaggi di posta elettronica di Outlook da applicazioni diverse da Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-332">We fixed an issue that was causing some users to experience the application to close unexpectedly when sending Outlook mail from applications other than Outlook.</span></span>


- <span data-ttu-id="70b41-333">È stato risolto un problema relativo al caricamento degli allegati.</span><span class="sxs-lookup"><span data-stu-id="70b41-333">Addresses a performance issue with attachment upload.</span></span>


- <span data-ttu-id="70b41-334">È stato risolto un problema a causa del quale gli utenti si vedevano richiedere continuamente da Outlook di eseguire lo strumento Manutenzione Posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-334">Addressed an issue that caused users to see Outlook continuously prompt them to run the Inbox Repair tool.</span></span>


- <span data-ttu-id="70b41-335">È stato risolto un problema che causava un problema quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="70b41-335">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="70b41-336">È stato risolto un problema che impediva agli utenti di salvare gli allegati di OneDrive fuori dal tenant nel computer locale nel selezionare l'opzione "Salva" nella finestra di dialogo sicurezza.</span><span class="sxs-lookup"><span data-stu-id="70b41-336">Addressed an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>


- <span data-ttu-id="70b41-337">È stato risolto un problema per cui le intestazioni dei messaggi in cinese erano incomprensibili in caso di risposta o inoltro.</span><span class="sxs-lookup"><span data-stu-id="70b41-337">We fixed an issue that caused the headers of Chinese messages to get garbled when replying or forwarding.</span></span>


- <span data-ttu-id="70b41-338">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente Pianificazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-338">Addressed an issue that caused the Scheduling Assistant page to fail to display.</span></span>


- <span data-ttu-id="70b41-339">È stato risolto un problema che causava la mancata visualizzazione della pagina Assistente pianificazione da parte di alcuni utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-339">Addressed an issue that caused some users to see the Scheduling Assistant page fail to display.</span></span>


- <span data-ttu-id="70b41-340">È stato risolto un problema che causava la riduzione delle prestazioni durante lo spostamento di più elementi di posta tra le cartelle in modalità online.</span><span class="sxs-lookup"><span data-stu-id="70b41-340">We fixed an issue that caused users to experience degraded performance when moving multiple mail items between folders in online mode.</span></span>


- <span data-ttu-id="70b41-341">È stata aggiunta una chiave di registro che consente ai clienti di disabilitare l'inclusione filetime per gli allegati nelle operazioni IDataObject (ad esempio trascinamento, appunti).</span><span class="sxs-lookup"><span data-stu-id="70b41-341">We added a regkey that allows customers to disable filetime inclusion for attachments in IDataObject operations (i.e. drag drop, clipboard).</span></span> <span data-ttu-id="70b41-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject 0 = filetimes sono esclusi 1 = (impostazione predefinita) filetimes sono inclusi</span><span class="sxs-lookup"><span data-stu-id="70b41-342">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Attachments REG_DWORD IncludeFileTimesInDataObject  0 = filetimes are excluded  1 = (default) filetimes are included</span></span>


- <span data-ttu-id="70b41-343">È stato risolto un problema che causava la scomparsa delle immagini in linea quando si rispondeva a un messaggio con un'etichetta di protezione da Azure Information Protection.</span><span class="sxs-lookup"><span data-stu-id="70b41-343">We fixed an issue that caused inline images to disappear when replying to a message with a protection label from Azure Information Protection.</span></span>


- <span data-ttu-id="70b41-344">È stato risolto un problema che causava la visualizzazione del nome utente come numero di telefono durante l'invio di un messaggio vocale protetto di Azure, impedendo agli utenti di Outlook Desktop di aprire i messaggi vocali provenienti da utenti esterni.</span><span class="sxs-lookup"><span data-stu-id="70b41-344">We fixed an issue that caused the user name to be displayed as a phone number when sending an Azure Protected Voicemail, causing Outlook Desktop users to be unable to open voicemails from external users.</span></span>


- <span data-ttu-id="70b41-345">È stato risolto un problema per cui l'impostazione della configurazione di OME aggiungeva allegati estranei all'elemento di posta. Questo costringeva Outlook a crittografare il messaggio anche se l'opzione DecryptAttachmentsForEncryptOnly era impostata sul lato servizio.</span><span class="sxs-lookup"><span data-stu-id="70b41-345">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though the DecryptAttachmentsForEncryptOnly option was setup on the service side.</span></span>


- <span data-ttu-id="70b41-346">È stato risolto un problema per cui le opzioni Solo crittografa e Non inoltrare continuavano a essere abilitate in alcuni scenari, nonostante fossero disabilitate dai criteri.</span><span class="sxs-lookup"><span data-stu-id="70b41-346">We fixed an issue that caused the Encrypt Only and Do Not Forward options to continue to be enabled in some scenarios despite being disabled by policy.</span></span>


- <span data-ttu-id="70b41-347">È stato risolto un problema che causava la perdita del formato SmartLink quando un file veniva salvato nelle bozze.</span><span class="sxs-lookup"><span data-stu-id="70b41-347">We fixed an issue that caused SmartLinks to lose their formatting when saved to drafts.</span></span>


- <span data-ttu-id="70b41-348">È stato risolto un problema che consente agli utenti di personalizzare il testo di giustificazione quando si sovrascrive un criterio.</span><span class="sxs-lookup"><span data-stu-id="70b41-348">We fixed an issue to provide a user a way to customize justification text when overriding a policy.</span></span>


- <span data-ttu-id="70b41-349">È stato risolto un problema per cui, salvando in formato OTF, i caratteri in cinese venivano trasformati in punti interrogativi.</span><span class="sxs-lookup"><span data-stu-id="70b41-349">We fixed an issue that caused Chinese characters to get changed to question marks when saving as an OFT file.</span></span>


- <span data-ttu-id="70b41-350">È stato risolto un problema che causava occasionalmente chiusure impreviste per gli utenti durante il recupero delle informazioni personali.</span><span class="sxs-lookup"><span data-stu-id="70b41-350">Addressed an issue that caused users to occasionally experience unexpected closures when retrieving persona information.</span></span>


- <span data-ttu-id="70b41-351">Questo risolve un problema che causava occasionalmente agli utenti delle chiusure dell'applicazione durante la modifica dei destinatari.</span><span class="sxs-lookup"><span data-stu-id="70b41-351">This fixes an issue that caused users to experience occasional application closures when editing recipients.</span></span>


- <span data-ttu-id="70b41-352">Risolve un problema che consente agli utenti di visualizzare anomalie durante l'uso della visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="70b41-352">Fixes an issue that caused users to see anomalies when using the compact view.</span></span>


- <span data-ttu-id="70b41-353">È stato risolto un problema che causava agli utenti di Outlook la comparsa di errori connessi con lo spostamento in modalità di visualizzazione compatta.</span><span class="sxs-lookup"><span data-stu-id="70b41-353">Addressed an issue that caused outlook users to see issues with navigation in compact views.</span></span>


- <span data-ttu-id="70b41-354">È stato risolto un problema che causava il mancato recapito del menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="70b41-354">Addressed an issue that caused the right-click context menu to fail to appear in the search controls.</span></span>


- <span data-ttu-id="70b41-355">È stato risolto un problema che causava la ricezione dell'errore seguente quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio, "Alcuni dei file in questa pagina Web non sono nella posizione prevista.</span><span class="sxs-lookup"><span data-stu-id="70b41-355">Addresses an issue that caused users to receive the following error when replying to or composing new email, "Some of the files in this web page aren't in the expected location.</span></span> <span data-ttu-id="70b41-356">Scaricarli comunque?</span><span class="sxs-lookup"><span data-stu-id="70b41-356">Do you want to download them anyway?</span></span> <span data-ttu-id="70b41-357">Se si è sicuri che la pagina Web sia una fonte attendibile, fare clic su Sì"</span><span class="sxs-lookup"><span data-stu-id="70b41-357">If you’re sure the Web page is from a trusted source, click Yes"</span></span>


- <span data-ttu-id="70b41-358">Risolve un problema che causava un blocco uscendo da Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-358">Addresses an issue that caused users to experience a hang while exiting Outlook.</span></span>


- <span data-ttu-id="70b41-359">È stato risolto un problema a causa del quale la ricerca di una caratteristica in Suggerisci una caratteristica non restituiva alcun risultato e non era possibile per l’utente suggerire un’idea per una nuova caratteristica.</span><span class="sxs-lookup"><span data-stu-id="70b41-359">Addressed an issue that caused searching for a feature in Suggest a Feature to return no results and leave the user with no option to submit a new feature idea.</span></span>


- <span data-ttu-id="70b41-360">È stato risolto un problema che causava problemi di formattazione negli avvisi di notifica degli eventi imprevisti.</span><span class="sxs-lookup"><span data-stu-id="70b41-360">Addressed an issue that caused formatting problems in incident notification alerts.</span></span>


- <span data-ttu-id="70b41-361">È stato risolto un problema che causava un arresto anomalo quando venivano inviati feedback tramite una notifica amministratore.</span><span class="sxs-lookup"><span data-stu-id="70b41-361">Addressed an issue that caused users to experience sudden closures when submitting feedback from an Admin Notification.</span></span>


- <span data-ttu-id="70b41-362">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="70b41-362">We fixed an issue for copy and paste SVG image.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="70b41-363">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-363">PowerPoint</span></span>

- <span data-ttu-id="70b41-364">Questa modifica risolve un problema della funzionalità Esporta in GIF animata per cui, facendo clic sul pulsante Esporta, l'esportazione non veniva eseguita.</span><span class="sxs-lookup"><span data-stu-id="70b41-364">This change addresses an issue with Export to Animated GIF feature where clicking on Export button was not exporting.</span></span>


- <span data-ttu-id="70b41-365">È stato risolto un problema per cui il componente aggiuntivo per i contenuti di Microsoft Forms non veniva eseguito dopo l'inserimento finché l'utente non faceva clic su un'altra diapositiva per visualizzarlo.</span><span class="sxs-lookup"><span data-stu-id="70b41-365">We have fixed an issue where Forms content add-in doesn't render after insertion until user click to another slide to make it show.</span></span>


- <span data-ttu-id="70b41-366">Correzione di sicurezza che risolve un problema che disabilitava le protezioni IRM aprendo un file di PowerPoint nella modalità Visualizzazione protetta.</span><span class="sxs-lookup"><span data-stu-id="70b41-366">Security fix to address an issue that disabled IRM protections when opening a PowerPoint file in Protected View.</span></span>


- <span data-ttu-id="70b41-367">È stato risolto un problema di VBA in cui Slide.Shapes.AddMediaObject2 si chiudeva in modo imprevisto con formati video legacy (MPG-1,Mpeg-2).</span><span class="sxs-lookup"><span data-stu-id="70b41-367">We have fixed a VBA issue where Slide.Shapes.AddMediaObject2 would unexpectedly close with legacy video formats (MPG-1,Mpeg-2).</span></span>


- <span data-ttu-id="70b41-368">È stato risolto un problema per cui il grafico di Excel collegato veniva modificato in modo errato nel foglio di Excel quando l'utente modificava il percorso di origine in una cartella locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-368">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


- <span data-ttu-id="70b41-369">È stato risolto un arresto anomalo che si verifica quando gli utenti hanno commenti sia moderni che legacy in un file, provocando così un aggiornamento dei commenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-369">Fixed an issue when users have both modern and legacy comments in a file, thus triggering an upgrade on the comments.</span></span>


- <span data-ttu-id="70b41-370">È stato risolto un problema relativo al riquadro dei suggerimenti che poteva causare la chiusura imprevista dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-370">We have fixed an issue with suggestion pane that may cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="70b41-371">È stato risolto un problema nella finestra di dialogo Impostazioni azione che causava la chiusura imprevista dell'app PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-371">We have fixed an issue in Action Settings dialog which was causing the PowerPoint app to close unexpectedly.</span></span>


- <span data-ttu-id="70b41-372">È stato risolto un problema di PowerPoint che causava la chiusura imprevista dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-372">We have fixed an issue with PowerPoint app that may cause it to close unexpectedly.</span></span>


- <span data-ttu-id="70b41-373">È stato risolto un problema per cui la funzionalità “Bentornato.</span><span class="sxs-lookup"><span data-stu-id="70b41-373">We fixed an issue due to which the feature ‘Welcome back!</span></span> <span data-ttu-id="70b41-374">Riprendi da dove hai lasciato in ufficio” non funzionava in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-374">Pick up where you left off in the office' was not working in the PowerPoint .</span></span>


- <span data-ttu-id="70b41-375">È stato risolto un problema per cui i file PowerPoint danneggiati non venivano aperti correttamente, anche dopo aver effettuato un'operazione di ripristino del documento.</span><span class="sxs-lookup"><span data-stu-id="70b41-375">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="70b41-376">È stato risolto un problema per cui i file PowerPoint danneggiati non venivano aperti correttamente, anche dopo aver effettuato un'operazione di ripristino del documento.</span><span class="sxs-lookup"><span data-stu-id="70b41-376">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


- <span data-ttu-id="70b41-377">È stato risolto un problema per cui la presentazione nella modalità di visualizzazione protetta non funzionava.</span><span class="sxs-lookup"><span data-stu-id="70b41-377">We fixed an issue where Slideshow in protected view was not working.</span></span>


### <a name="project"></a><span data-ttu-id="70b41-378">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-378">Project</span></span>

- <span data-ttu-id="70b41-379">È stato risolto un problema per cui l'attività selezionata nella finestra di dialogo Assegna risorse non è la stessa selezionata nella visualizzazione Bacheca attività.</span><span class="sxs-lookup"><span data-stu-id="70b41-379">Fixed an issue where the task selected in the assign resources dialog isn't the same as the task selected in the task board view.</span></span>


- <span data-ttu-id="70b41-380">È stato risolto un problema per cui, se una risorsa aveva più di una tabella tariffe definita, il costo residuo non sempre veniva calcolato correttamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-380">Fixed an issue where if a resource had more than one cost rate table defined, remaining cost was not always calculated correctly.</span></span>


- <span data-ttu-id="70b41-381">È stato risolto un problema per cui la data di fine del progetto non viene aggiornata per i progetti collegati all'elenco attività di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-381">Fixed an issue where the Project finish date isn't getting updated for projects connected to SharePoint tasks list.</span></span>


- <span data-ttu-id="70b41-382">È stato risolto un problema per cui se si usava Project connesso a Project Web App e il separatore decimale era una virgola, il metodo Add di TaskDependencies poteva non funzionare quando veniva aggiunto un elemento lag a una dipendenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-382">Fixed an issue where if you are using Project connected to Project Web App and the decimal separator is a comma, the TaskDependencies Add method fails when you try to add lag to a dependency.</span></span>


- <span data-ttu-id="70b41-383">È stato risolto un problema per cui la percentuale di completamento dell'attività si modificava erroneamente in un valore inferiore al 100% dopo che l'attività era stata contrassegnata come completata.</span><span class="sxs-lookup"><span data-stu-id="70b41-383">Fixed an issue where task percent complete was incorrectly changing to a value less than 100% complete after it was marked complete.</span></span>


- <span data-ttu-id="70b41-384">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="70b41-384">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>


- <span data-ttu-id="70b41-385">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-385">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>


- <span data-ttu-id="70b41-386">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.</span><span class="sxs-lookup"><span data-stu-id="70b41-386">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>


- <span data-ttu-id="70b41-387">È stato risolto un problema per cui, quando i dati predecessore/successore venivano modificati in una Visualizzazione maschera, veniva generato un evento ProjectBeforeTaskChange aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-387">Fixed an issue when Predecessor/Successor data is edited within a Form view, an extra ProjectBeforeTaskChange event is fired.</span></span>


- <span data-ttu-id="70b41-388">È stato risolto un problema che causava l'arresto anomalo di Project quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-388">Fixed an issue where Project may close unexpectedly when saving projects created with older versions of Project.</span></span>


- <span data-ttu-id="70b41-389">È stato risolto un problema per cui l'utente non poteva immettere il lavoro previsto rapportato alla scala cronologica quando era attivata l'opzione per proteggere il lavoro effettivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-389">Fixed an issue where the user couldn't enter time-phased Baseline Work when the setting to protect actual work is on.</span></span>


- <span data-ttu-id="70b41-390">È stato risolto un problema per cui non era possibile salvare un file PDF/XPS da Project a una raccolta documenti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-390">Fixed an issue where you couldn't save a PDF/XPS from Project to a SharePoint document library.</span></span>


- <span data-ttu-id="70b41-391">È stato risolto un problema per cui, incollando un'attività con più dipendenze, non tutte le dipendenze vengono copiate correttamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-391">Fixed an issue where if you paste a task that has multiple dependencies, not all dependencies are copied correctly.</span></span>


- <span data-ttu-id="70b41-392">È stato risolto un problema per cui non era possibile aprire progetti nel client Project Desktop da Project Web App se l'URL terminava in ". com".</span><span class="sxs-lookup"><span data-stu-id="70b41-392">Fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App if the URL ended in .com.</span></span>


- <span data-ttu-id="70b41-393">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non si attivava quando era apportata una modifica all'attività di riepilogo del progetto, sia che si trattasse dell’avvio del progetto che del campo attività.</span><span class="sxs-lookup"><span data-stu-id="70b41-393">Fixed an issue where the ProjectBeforeTaskChange event doesn't fire when there is a change to the project summary task - either the project start/task field.</span></span>


- <span data-ttu-id="70b41-394">È stato risolto un problema per cui un'attività contrassegnata come completa al 100% veniva erroneamente indicata con un completamento inferiore al 100%.</span><span class="sxs-lookup"><span data-stu-id="70b41-394">Fixed an issue where a task that is marked 100% complete is wrongly changing to be less than 100% complete.</span></span>


- <span data-ttu-id="70b41-395">È stato risolto un problema per cui Project poteva chiudersi in modo imprevisto all'apertura di file in cui i profili delle risorse erano specificati in un certo modo.</span><span class="sxs-lookup"><span data-stu-id="70b41-395">Fixed an issue where Project may terminate unexpectedly on opening files where resource contours were specified in a certain manner.</span></span>


### <a name="skype"></a><span data-ttu-id="70b41-396">Skype</span><span class="sxs-lookup"><span data-stu-id="70b41-396">Skype</span></span>

- <span data-ttu-id="70b41-397">Il tono della pelle dell’emoticon che balla modificato su un colorito neutro.</span><span class="sxs-lookup"><span data-stu-id="70b41-397">Changed dancing emoticon skin tone to neutral color.</span></span>


- <span data-ttu-id="70b41-398">Quando a un utente viene assegnato un criterio che sposta su Solo Teams, è comunque possibile usare il componente aggiuntivo di Outlook Skype for Business per pianificare le riunioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-398">When a user is given a policy that moves them to Teams Only, they were still able to use the Skype for Business Outlook add-in to schedule meetings.</span></span> <span data-ttu-id="70b41-399">In seguito all'aggiornamento, non sarà più possibile pianificare le riunioni con Skype for Business dopo che il cliente avrà letto il criterio che indica che l'utente è Solo Teams e partecipa alla riunione con modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="70b41-399">After this update, you will no longer be able to schedule Skype for Business meetings after the client reads the policy indicating the user is Teams Only, and enters meeting join only mode.</span></span> <span data-ttu-id="70b41-400">Inoltre, il componente aggiuntivo di Outlook Skype for Business non verrà attivato durante l'avvio se vede che il client Skype for Business è in modalità di partecipazione singola.</span><span class="sxs-lookup"><span data-stu-id="70b41-400">Additionally the Skype for Business Outlook Add-in will not activate itself while starting up if it sees the Skype for Business client is in meeting join only mode.</span></span>


- <span data-ttu-id="70b41-401">Risolve un problema per cui il certificato TLS-DSK degli utenti non veniva rinnovato nel momento previsto, e veniva invece rinnovato solo quando restavano 12 ore di validità.</span><span class="sxs-lookup"><span data-stu-id="70b41-401">Fixes an issue where a user's TLS-DSK certificate would not renew at the expected time, instead only renewing when less than 12 hours remain on its validity.</span></span>


- <span data-ttu-id="70b41-402">Risolve un problema per cui l'interfaccia utente di Skype for Business risulta vuota dopo l'accesso quando Office non è ancora concesso in licenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-402">Fixes an issue where the Skype for Business UI shows as blank after signing in when Office is not yet licensed.</span></span>


### <a name="visio"></a><span data-ttu-id="70b41-403">Visio</span><span class="sxs-lookup"><span data-stu-id="70b41-403">Visio</span></span>

- <span data-ttu-id="70b41-404">È stato risolto un problema che causava la chiusura imprevista dell'anteprima in tempo reale durante l'allineamento del testo.</span><span class="sxs-lookup"><span data-stu-id="70b41-404">We fixed an issue that caused the Live preview to close unexpectedly on text alignment.</span></span>


- <span data-ttu-id="70b41-405">È stato risolto un problema per cui gli utenti potevano creare linee rette usando i connettori in Visio per Office 365 sia per gli stencil di Visio personalizzati che per modelli predefiniti.</span><span class="sxs-lookup"><span data-stu-id="70b41-405">We fixed an issue where users will be able to create straight lines using connectors in Visio for Office 365 for both custom Visio stencils and in-built templates.</span></span>


### <a name="word"></a><span data-ttu-id="70b41-406">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-406">Word</span></span>

- <span data-ttu-id="70b41-407">È stato risolto un problema durante l'apertura di documenti di Word tramite consegna di documenti personalizzati (aspx) con URL contenente un componente di query.</span><span class="sxs-lookup"><span data-stu-id="70b41-407">Resolved an issue opening Word documents from custom document delivery (aspx) when the URL contains a query component.</span></span>


- <span data-ttu-id="70b41-408">Questa modifica consente di risolvere un problema in cui le applicazioni di Office possono bloccarsi in uno stato di errore di salvataggio silenzioso dopo una sessione di creazione condivisa precedente.</span><span class="sxs-lookup"><span data-stu-id="70b41-408">This change fixes an issue where Office applications can get stuck in a silent Save failure state after a previous coauthoring session.</span></span>


- <span data-ttu-id="70b41-409">È stato risolto un problema che causava un arresto anomalo quando gli utenti rispondevano a un messaggio di posta elettronica o componevano un nuovo messaggio.</span><span class="sxs-lookup"><span data-stu-id="70b41-409">Addresses an issue that caused users to experience an issue when replying to or composing new email.</span></span>


- <span data-ttu-id="70b41-410">È stato risolto un problema che causava un problema quando si usava il pulsante "X" del mouse.</span><span class="sxs-lookup"><span data-stu-id="70b41-410">Addressed an issue that caused users to occasionally experience an issue when using the "X" button on their mouse.</span></span>


- <span data-ttu-id="70b41-411">Risolve un problema che causava l'arresto anomalo quando venivano aperti alcuni messaggi di posta elettronica molto grandi.</span><span class="sxs-lookup"><span data-stu-id="70b41-411">Fixes an issue that caused users to experience an issue when opening certain very large emails.</span></span>


- <span data-ttu-id="70b41-412">È stato risolto un problema per cui le intestazioni con numeri incollate avevano un rientro aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-412">We fixed an issue where pasted numbered headings showed an additional indent.</span></span>


- <span data-ttu-id="70b41-413">È stato risolto un problema relativo al comando copia e incolla immagine SVG.</span><span class="sxs-lookup"><span data-stu-id="70b41-413">We fixed an issue for copy and paste SVG image.</span></span>


- <span data-ttu-id="70b41-414">È stato risolto un problema per cui l'utente poteva perdere il contenuto quando ridimensionava una forma.</span><span class="sxs-lookup"><span data-stu-id="70b41-414">We fixed an issue where the user might lose content when resize a shape.</span></span>


- <span data-ttu-id="70b41-415">È stato risolto un problema che causava l'arresto anomalo all'apertura dei documenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-415">We fixed an issue which user might experience issues when opening a document.</span></span>


- <span data-ttu-id="70b41-416">È stato risolto un problema per cui i collegamenti lunghi non venivano mandati a capo quando un documento veniva salvato in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="70b41-416">We fixed an issue where long links were not being wrapped when saving document to HTML format.</span></span>


- <span data-ttu-id="70b41-417">È stato risolto un problema per cui gli stili di base non venivano aggiornati con lo stile normale.</span><span class="sxs-lookup"><span data-stu-id="70b41-417">We fixed an issue which the base styles are not updated with Normal style.</span></span>


- <span data-ttu-id="70b41-418">Risolve un bug delle estensioni di commento, per cui le risposte di commento avevano la stessa estensione del commento padre.</span><span class="sxs-lookup"><span data-stu-id="70b41-418">FIxes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


- <span data-ttu-id="70b41-419">È stato risolto un problema per cui se si risponde a un commento padre che contiene estensioni sconosciute in un elenco di estensioni, la risposta avrà le stesse estensioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-419">We fixed an issue where if you reply to a parent comment that has unknown extensions in an extension list, the reply will get those same extensions.</span></span>


- <span data-ttu-id="70b41-420">Risolve un problema che può aver causato la chiusura imprevista dell'applicazione all'esecuzione.</span><span class="sxs-lookup"><span data-stu-id="70b41-420">Resolved an issue that may have caused the application to close unexpectedly when booting.</span></span>


- <span data-ttu-id="70b41-421">È stato risolto un problema relativo ai messaggi di Outlook configurati come "Non inoltrare".</span><span class="sxs-lookup"><span data-stu-id="70b41-421">We fixed an issue with Outlook with message set to Do not forward.</span></span>


- <span data-ttu-id="70b41-422">È stato risolto un problema con la finestra di dialogo raccolta Stili.</span><span class="sxs-lookup"><span data-stu-id="70b41-422">We fixed an issue with Style Gallery dialog.</span></span>


- <span data-ttu-id="70b41-423">È stato risolto un problema per cui la macro AutoOpen veniva eseguita prima di AutoExec</span><span class="sxs-lookup"><span data-stu-id="70b41-423">We fixed an issue where macro AutoOpen runs before AutoExec</span></span>


### <a name="office-suite"></a><span data-ttu-id="70b41-424">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-424">Office Suite</span></span>

- <span data-ttu-id="70b41-425">È stato risolto un problema del vecchio pannello Condividi basato su servizi non online, che causava la chiusura imprevista dell'applicazione quando si chiudeva un documento mentre il riquadro Condividi era aperto. </span><span class="sxs-lookup"><span data-stu-id="70b41-425">Fixed an issue for the old, non-web service based Share pane, where upon closing the document while the Share pane is open could cause the application to close unexpectedly.</span></span>


- <span data-ttu-id="70b41-426">È stato risolto un problema che poteva causare la chiusura imprevista dell'applicazione durante la chiusura dei file di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-426">Fixed a timing issue that could cause the application to close unexpectedly when closing office files.</span></span>


- <span data-ttu-id="70b41-427">È stato risolto un problema che impediva agli utenti di importare elenchi SPO quando ADAL era disabilitato.</span><span class="sxs-lookup"><span data-stu-id="70b41-427">Addresses an issue that prevented users from importing SPO Lists when ADAL was disabled.</span></span>


- <span data-ttu-id="70b41-428">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="70b41-428">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="70b41-429">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="70b41-429">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>


- <span data-ttu-id="70b41-430">È stato risolto il tasso di errore di ValidateInstall impostando la convalida di installazione di Bing per impostazione predefinita su true e considerando il risultato positivo di MSI come un’operazione riuscita di installazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-430">We have resolved the ValidateInstall fail rate issue by setting the Bing Addon install validation to true by default and considering the MSI return success as an install success.</span></span>


- <span data-ttu-id="70b41-431">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="70b41-431">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>


- <span data-ttu-id="70b41-432">È stato risolto un problema a portata di clic che causava un errore nell'aggiornamento durante il tentativo di creare collegamenti simbolici reali.</span><span class="sxs-lookup"><span data-stu-id="70b41-432">Fixed a Click-to-Run issue which was resulting in update failure when trying to hard link symbolic links.</span></span>


- <span data-ttu-id="70b41-433">È stato risolto un problema per i clienti commerciali che usano System Center Configuration Manager o altri strumenti di gestione per l'aggiornamento di Office tramite Prevenzione della perdita di dati degli endpoint di Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="70b41-433">Addressed an issue for commercial customers who leverage System Center Configuration Manager or other management tool for the Office Update using Microsoft 365 Endpoint data loss prevention.</span></span>


- <span data-ttu-id="70b41-434">È stato risolto un problema che causava la visualizzazione di un messaggio di runtime, anche se la transizione al prodotto completo era stata completata.</span><span class="sxs-lookup"><span data-stu-id="70b41-434">Fixed an issue that caused a runtime message to show even though the transition to the full product is complete.</span></span> <span data-ttu-id="70b41-435">Il problema è stato corretto verificando che il servizio calcolasse correttamente i prodotti aggiunti.</span><span class="sxs-lookup"><span data-stu-id="70b41-435">The fix for this issue was to ensure the service properly computed added products.</span></span> <span data-ttu-id="70b41-436">I nuovi prodotti aggiunti sono stati filtrati (verificando che esistano anche nella nuova configurazione) e aggiunti alla fine degli ID di rilascio prodotti esistenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-436">We filtered out the newly added products (ensuring that they exist in the new configuration as well) and added them to the end of existing Product release IDs.</span></span>


- <span data-ttu-id="70b41-437">È stato risolto un problema per cui gli elementi o il contenuto dell'interfaccia utente non erano visualizzati dagli utenti in determinate condizioni, in particolare con l’entrata e l’uscita dalla visualizzazione Relatore o l'utilizzo di più monitor.</span><span class="sxs-lookup"><span data-stu-id="70b41-437">We fixed an issue where users were seeing the UI elements or content not being displayed under certain conditions, in particular with coming in and out of Presenter View or using multiple monitors.</span></span>


- <span data-ttu-id="70b41-438">Questa modifica risolve un problema legato all'apertura di file contenenti diagrammi legacy.</span><span class="sxs-lookup"><span data-stu-id="70b41-438">This change addresses an issue related to opening files containing legacy diagrams.</span></span>


- <span data-ttu-id="70b41-439">Questa modifica corregge un problema con il proxy di fallback SVG che causa la violazione dell'accesso.</span><span class="sxs-lookup"><span data-stu-id="70b41-439">This change addresses an issue with SVG fallback proxy resulting in access violations.</span></span>


- <span data-ttu-id="70b41-440">È stato risolto un problema che causava un utilizzo elevato della CPU in modalità inattiva con GIF/modelli animati 3D</span><span class="sxs-lookup"><span data-stu-id="70b41-440">Fixes high CPU usage on idle with GIF/animated model3D</span></span>


- <span data-ttu-id="70b41-441">Questa modifica risolve potenziali blocchi che si verificano durante il caricamento e la riproduzione di contenuti animati, ad esempio GIF o modelli 3D.</span><span class="sxs-lookup"><span data-stu-id="70b41-441">This change addresses potential hangs when loading and playing animated content such as GIFs or 3D models.</span></span>


- <span data-ttu-id="70b41-442">Questa modifica risolve un problema all'avvio delle app di Office dovuto al mancato caricamento del file d2d1.dll.</span><span class="sxs-lookup"><span data-stu-id="70b41-442">This change addresses a issue when launching Office apps due to failing to load d2d1.dll.</span></span>


- <span data-ttu-id="70b41-443">L'host di Office si chiudeva in modo imprevisto in Windows, quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema HKEY_CURRENT_USER \Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="70b41-443">The office host was  close unexpectedly in windows, when an add-in is being activated while the registry key HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="70b41-444">La modifica può risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="70b41-444">This change would fix this issue.</span></span>


- <span data-ttu-id="70b41-445">Risolve un problema relativo al malfunzionamento della API di messaggistica per i componenti aggiuntivi di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-445">Fix an issue that the Messaging API for Office Add-ins is not working.</span></span>

- <span data-ttu-id="70b41-446">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-446">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>


- <span data-ttu-id="70b41-447">Questo aggiornamento consente di risolvere un problema di Microsoft Office per il quale i progetti di Visual Basic, Applications Edition con riferimenti che dovrebbero poter essere trovati cercando i percorsi specificati nella variabile di ambiente PATH potrebbero non essere individuati correttamente in fase di esecuzione, generando errori in fase di esecuzione VBA.</span><span class="sxs-lookup"><span data-stu-id="70b41-447">This update fixes an issue in Microsoft Office where Visual Basic for Applications projects with references that are expected to be found by searching locations specified in the PATH environment variable may not be found properly at runtime, leading to VBA runtime errors.</span></span>

- <span data-ttu-id="70b41-448">Questa correzione risolve un errore che si verificava quando si limitava l'accesso e la protezione dei file con una password, contemporaneamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-448">This fix resolves an error which occurs preventing both restricting access and protecting files with a password simultaneously.</span></span>

- <span data-ttu-id="70b41-449">È stato risolto un problema che può aver causato un arresto anomalo durante il trascinamento del contenuto dall'app.</span><span class="sxs-lookup"><span data-stu-id="70b41-449">Resolved an issue that may have caused an unexpected closure when dragging some content from the app.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-january-12"></a><span data-ttu-id="70b41-451">Versione 2002: 12 gennaio</span><span class="sxs-lookup"><span data-stu-id="70b41-451">Version 2002: January 12</span></span>
<span data-ttu-id="70b41-452">*Versione 2002 (Build 12527.21504)*</span><span class="sxs-lookup"><span data-stu-id="70b41-452">*Version 2002 (Build 12527.21504)*</span></span>

<span data-ttu-id="70b41-453">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-453">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-455">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-455">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-456">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-456">Excel</span></span>

- <span data-ttu-id="70b41-457">È stato risolto un problema legato all'uso dei dati in tempo reale in combinazione con la funzionalità di ricalcolo multithread, che causava la chiusura imprevista dell'applicazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-457">Fixed an issue when using real time data in conjunction with multithreaded recalc functionality could cause the application to close unexpectedly.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="70b41-458">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-458">PowerPoint</span></span>

- <span data-ttu-id="70b41-459">È stato risolto un problema per cui i file PowerPoint danneggiati non venivano aperti correttamente, anche dopo aver effettuato un'operazione di ripristino del documento.</span><span class="sxs-lookup"><span data-stu-id="70b41-459">Fixed an issue where some corrupt PowerPoint files were not opening correctly, even after a document repair operation.</span></span>


### <a name="word"></a><span data-ttu-id="70b41-460">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-460">Word</span></span>

- <span data-ttu-id="70b41-461">Risolve un bug delle estensioni di commento, per cui le risposte di commento avevano la stessa estensione del commento padre.</span><span class="sxs-lookup"><span data-stu-id="70b41-461">Fixes a bug with comment extensions where the comment reply would have the same extension as the parent comment.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-12"></a><span data-ttu-id="70b41-463">Versione 1908: 12 gennaio</span><span class="sxs-lookup"><span data-stu-id="70b41-463">Version 1908: January 12</span></span>
<span data-ttu-id="70b41-464">*Versione 1908 (Build 11929.20994)*</span><span class="sxs-lookup"><span data-stu-id="70b41-464">*Version 1908 (Build 11929.20994)*</span></span>

<span data-ttu-id="70b41-465">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-465">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-467">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-467">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="70b41-468">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-468">Office Suite</span></span>

- <span data-ttu-id="70b41-469">Questa modifica risolve un problema legato all'apertura di file contenenti diagrammi legacy.</span><span class="sxs-lookup"><span data-stu-id="70b41-469">This change addresses an issue related to opening files containing legacy diagrams.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-december-08"></a><span data-ttu-id="70b41-471">Versione 2002: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="70b41-471">Version 2002: December 08</span></span>
<span data-ttu-id="70b41-472">*Versione 2002 (Build 12527.21416)*</span><span class="sxs-lookup"><span data-stu-id="70b41-472">*Version 2002 (Build 12527.21416)*</span></span>

<span data-ttu-id="70b41-473">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-473">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-475">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-475">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-476">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-476">Excel</span></span>

- <span data-ttu-id="70b41-477">Crenatura del testo migliorata in PowerPoint quando il contenuto viene copiato da Excel e incollato in PowerPoint con l'opzione di incorporamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-477">Improved text kerning in PowerPoint when content is copied from Excel and pasted into PowerPoint with the Embed option.</span></span>


- <span data-ttu-id="70b41-478">È stato risolto un problema per cui Excel si arrestava durante il ricalcolo.</span><span class="sxs-lookup"><span data-stu-id="70b41-478">We fixed an issue where Excel would stop working during recalc.</span></span>


- <span data-ttu-id="70b41-479">È stato risolto un problema per cui un utente non poteva aprire il file atomsvc (UTF8 + BOM) direttamente da SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-479">We fixed an issue where a user was unable to open atomsvc (UTF8+BOM) file from SharePoint, directly.</span></span>


- <span data-ttu-id="70b41-480">È stato risolto un problema che impediva il passaggio dall'anteprima della tabella e dall'editor di query in PowerPivot.</span><span class="sxs-lookup"><span data-stu-id="70b41-480">Fixed an issue that would prevent switching from Table Preview and the Query Editor in PowerPivot.</span></span>


- <span data-ttu-id="70b41-481">Prestazioni migliorate per i file che utilizzano le funzioni rilasciate più di recente.</span><span class="sxs-lookup"><span data-stu-id="70b41-481">Improved performance for files that are using many of the more recently released functions.</span></span>


### <a name="outlook"></a><span data-ttu-id="70b41-482">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-482">Outlook</span></span>

- <span data-ttu-id="70b41-483">È stato risolto un problema per cui l'impostazione della configurazione di OME aggiungeva allegati estranei all'elemento di posta che imponevano a Outlook di crittografare il messaggio anche se l'opzione DecryptAttachmentsForEncryptOnly era impostata sul lato del servizio.</span><span class="sxs-lookup"><span data-stu-id="70b41-483">We fixed an issue where setting up OME Configuration was adding an extraneous attachments on the mail item which was forcing Outlook to Encrypt the message even though DecryptAttachmentsForEncryptOnly option is setup on the service side.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="70b41-484">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-484">PowerPoint</span></span>

- <span data-ttu-id="70b41-485">È stato risolto un problema per cui il grafico di Excel collegato viene modificato in modo errato nel foglio di Excel quando l'utente modifica il percorso di origine in una cartella locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-485">We fixed an issue where linked excel chart incorrectly changes to excel sheet when user changes the source path to local OneDrive folder.</span></span>


### <a name="project"></a><span data-ttu-id="70b41-486">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-486">Project</span></span>

- <span data-ttu-id="70b41-487">È stato risolto un problema per cui non era possibile aprire progetti nel client desktop di Project da Project Web App se l'URL terminava in .com.</span><span class="sxs-lookup"><span data-stu-id="70b41-487">We fixed an issue where projects couldn't be opened in the Project desktop client from Project Web App is the URL ended in .com.</span></span>



[//]: # (NON RIMUOVERE I DETTAGLI DI FINE CONTENUTO)

## <a name="version-1908-december-08"></a><span data-ttu-id="70b41-489">Versione 1908: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="70b41-489">Version 1908: December 08</span></span>
<span data-ttu-id="70b41-490">*Versione 1908 (Build 11929.20984)*</span><span class="sxs-lookup"><span data-stu-id="70b41-490">*Version 1908 (Build 11929.20984)*</span></span>

<span data-ttu-id="70b41-491">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-491">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-november-10"></a><span data-ttu-id="70b41-492">Versione 2002: 10 novembre</span><span class="sxs-lookup"><span data-stu-id="70b41-492">Version 2002: November 10</span></span>
<span data-ttu-id="70b41-493">*Versione 2002 (Build 12527.21330)*</span><span class="sxs-lookup"><span data-stu-id="70b41-493">*Version 2002 (Build 12527.21330)*</span></span>

<span data-ttu-id="70b41-494">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-494">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-496">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-496">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-497">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-497">Excel</span></span>

- <span data-ttu-id="70b41-498">È stato risolto un problema per cui, quando si selezionava lo spagnolo come lingua di Office, gli elenchi di convalida dei dati non mostravano tutti gli elementi.</span><span class="sxs-lookup"><span data-stu-id="70b41-498">Fixed an issue when the Office language was set to Spanish, in which data validation lists may not show all the items in the list.</span></span>


- <span data-ttu-id="70b41-499">È stato risolto un problema che poteva causare un blocco durante l'aggiornamento delle tabelle pivot OLAP.</span><span class="sxs-lookup"><span data-stu-id="70b41-499">We fixed an issue which could cause a hang when refreshing OLAP PivotTables.</span></span>


- <span data-ttu-id="70b41-500">È stato risolto un errore per cui alcune funzioni avrebbero avuto un risultato errato dopo il caricamento di una cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-500">Fixed a bug where certain functions would have an incorrect result after loading a workbook.</span></span>


- <span data-ttu-id="70b41-501">È stato risolto un problema per cui l'applicazione si chiudeva in modo imprevisto, correlato ai riferimenti del componente aggiuntivo XLAM e agli intervalli denominati.</span><span class="sxs-lookup"><span data-stu-id="70b41-501">We fixed an issue where the application would terminate unexpectedly which was related to XLAM add-in references and named ranges.</span></span>


- <span data-ttu-id="70b41-502">È stato risolto un problema per cui l'esecuzione della macro del filtro avanzato riportava erroneamente errori.</span><span class="sxs-lookup"><span data-stu-id="70b41-502">Fixed an issue where running the advanced filter macro would incorrectly report errors.</span></span>


### <a name="outlook"></a><span data-ttu-id="70b41-503">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-503">Outlook</span></span>

- <span data-ttu-id="70b41-504">È stato risolto un problema che causava la disabilitazione imprevista dei componenti aggiuntivi interni quando venivano disabilitate le esperienze connesse facoltative.</span><span class="sxs-lookup"><span data-stu-id="70b41-504">We fixed an issue that caused internal add-ins to be unexpectedly disabled when optional connected experiences were disabled.</span></span>


- <span data-ttu-id="70b41-505">È stato risolto un problema che impediva agli utenti di inviare un messaggio di posta elettronica per conto di una lista di distribuzione nascosta dall'elenco indirizzi globale.</span><span class="sxs-lookup"><span data-stu-id="70b41-505">We fixed an issue that caused users to be unable to send as or on behalf of a Distribution List that was hidden from the Global Address List.</span></span>



[//]: # (NON RIMUOVERE FINE DEL CONTENUTO BUG)

## <a name="version-1908-november-10"></a><span data-ttu-id="70b41-507">Versione 1908: 10 novembre</span><span class="sxs-lookup"><span data-stu-id="70b41-507">Version 1908: November 10</span></span>
<span data-ttu-id="70b41-508">*Versione 1908 (Build 11929.20974)*</span><span class="sxs-lookup"><span data-stu-id="70b41-508">*Version 1908 (Build 11929.20974)*</span></span>

<span data-ttu-id="70b41-509">Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-509">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-october-13"></a><span data-ttu-id="70b41-510">Versione 2002: 13 ottobre</span><span class="sxs-lookup"><span data-stu-id="70b41-510">Version 2002: October 13</span></span>
<span data-ttu-id="70b41-511">*Versione 2002 (Build 12527.21236)*</span><span class="sxs-lookup"><span data-stu-id="70b41-511">*Version 2002 (Build 12527.21236)*</span></span>

<span data-ttu-id="70b41-512">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-512">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-514">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-514">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="70b41-515">Accesso</span><span class="sxs-lookup"><span data-stu-id="70b41-515">Access</span></span>

- <span data-ttu-id="70b41-516">Nella versione a 64 bit di Access non dovrebbe più essere visualizzato il messaggio "La query è troppo complessa" né verificarsi un errore di risorse di sistema insufficienti, purché si sia conformi alle linee guida e ai requisiti per i database di Access.</span><span class="sxs-lookup"><span data-stu-id="70b41-516">You should no longer receive a "Query is too complex" or a system resource exceeded error on your 64-bit version of Access, as long as you are meeting Access database guidelines and requirements.</span></span>


- <span data-ttu-id="70b41-517">Quando si decide di usare la funzionalità di filtro dopo Progettazione query, il database non dovrebbe più arrestarsi in modo anomalo.</span><span class="sxs-lookup"><span data-stu-id="70b41-517">Once you decide to use our filter feature after our query designer, your database should no longer crash.</span></span> <span data-ttu-id="70b41-518">Controllare di conseguenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-518">Please check accordingly.</span></span>


### <a name="excel"></a><span data-ttu-id="70b41-519">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-519">Excel</span></span>

- <span data-ttu-id="70b41-520">È stato risolto un problema che impediva agli utenti di modificare un filtro della tabella pivot perché era configurato su un valore non più presente nel database Analysis Services.</span><span class="sxs-lookup"><span data-stu-id="70b41-520">We fixed an issue where users could not modify a PivotTable filter because it was set to a value that was no longer present in an Analysis Services database.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="70b41-521">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-521">PowerPoint</span></span>

- <span data-ttu-id="70b41-522">Le nuove presentazioni create da un modello potevano ereditare un'impostazione che impediva un'esperienza di creazione condivisa soddisfacente.</span><span class="sxs-lookup"><span data-stu-id="70b41-522">New presentations created from a template could inherit a setting that prevented  a good co-authoring experience.</span></span> <span data-ttu-id="70b41-523">Questa correzione garantisce che l'opzione sia deselezionata in questo caso.</span><span class="sxs-lookup"><span data-stu-id="70b41-523">This fix ensures that the setting is cleared in this case.</span></span>


### <a name="word"></a><span data-ttu-id="70b41-524">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-524">Word</span></span>

- <span data-ttu-id="70b41-525">È stato risolto un problema per cui, aprendo documenti con interruzioni di pagina e colonne, l'utente poteva visualizzare il messaggio di errore "È stato superato il numero massimo di pagine supportate da Microsoft Word oppure il documento è danneggiato"</span><span class="sxs-lookup"><span data-stu-id="70b41-525">We fixed an issue which when opening documents with page breaks and columns, user might encountered an error message, " You have exceeded the maximum number of pages allowed by Microsoft Word supported, or the document may be damaged"</span></span>


### <a name="office-suite"></a><span data-ttu-id="70b41-526">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-526">Office Suite</span></span>

- <span data-ttu-id="70b41-527">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="70b41-527">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="70b41-528">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="70b41-528">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-october-13"></a><span data-ttu-id="70b41-530">Versione 1908: 13 ottobre</span><span class="sxs-lookup"><span data-stu-id="70b41-530">Version 1908: October 13</span></span>
<span data-ttu-id="70b41-531">*Versione 1908 (Build 11929.20966)*</span><span class="sxs-lookup"><span data-stu-id="70b41-531">*Version 1908 (Build 11929.20966)*</span></span>

<span data-ttu-id="70b41-532">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-532">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-534">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-534">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="70b41-535">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-535">Office Suite</span></span>

- <span data-ttu-id="70b41-536">Quando l'utente stampa qualsiasi documento/file su stampanti a getto d'inchiostro da Office e l'inchiostro è quasi esaurito, i messaggi "Toner scarso" o "Nessun toner" sono mostrati anche se la stampante non ha alcun toner.</span><span class="sxs-lookup"><span data-stu-id="70b41-536">When the user prints any document/file on inkjet printers from Office and printer's ink is low, "Toner Low" or "No Toner" message will show, even though inkjet printers don't have toners.</span></span> <span data-ttu-id="70b41-537">I messaggi sono stati modificati su "Toner/inchiostro scarso" e "Nessun toner/inchiostro".</span><span class="sxs-lookup"><span data-stu-id="70b41-537">Changing message to display "Toner/ink Low" & "No toner/ink".</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-september-08"></a><span data-ttu-id="70b41-539">Versione 2002: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="70b41-539">Version 2002: September 08</span></span>
<span data-ttu-id="70b41-540">*Versione 2002 (Build 12527,21104)*</span><span class="sxs-lookup"><span data-stu-id="70b41-540">*Version 2002 (Build 12527.21104)*</span></span>

<span data-ttu-id="70b41-541">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-541">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-543">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-543">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-544">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-544">Excel</span></span>

- <span data-ttu-id="70b41-545">Questo risolve un problema in cui le connessioni create dal provider di dati SQL nelle versioni precedenti di Office imposterebbero le proprietà della tabella interna in modo diverso da Office 365.</span><span class="sxs-lookup"><span data-stu-id="70b41-545">This addresses an issue where connections created by the SQL data provider in older versions of Office would set internal table properties differently from Office 365.</span></span> <span data-ttu-id="70b41-546">Ciò ha causato la disabilitazione dell'elenco a discesa Anteprima tabella/Editor di query per i file con connessioni create nelle versioni precedenti di Office quando sono stati aperti utilizzando Office 365.</span><span class="sxs-lookup"><span data-stu-id="70b41-546">This caused the Table Preview / Query Editor dropdown to be disabled for files with connections created in older versions of Office when they were opened using Office 365.</span></span>


- <span data-ttu-id="70b41-547">È stato risolto un problema per cui l’input penna poteva far sì che Excel smettesse di rispondere.</span><span class="sxs-lookup"><span data-stu-id="70b41-547">Resolved an issue where inking could cause Excel to become unresponsive.</span></span>


### <a name="outlook"></a><span data-ttu-id="70b41-548">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-548">Outlook</span></span>

- <span data-ttu-id="70b41-549">Risolve un problema che impediva agli utenti di connettersi alle cartelle pubbliche dopo l'aggiunta di una cassetta postale condivisa.</span><span class="sxs-lookup"><span data-stu-id="70b41-549">Fixes an issue that caused users to be unable to connect to Public Folders after adding a shared mailbox.</span></span>


### <a name="office-suite"></a><span data-ttu-id="70b41-550">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-550">Office Suite</span></span>

- <span data-ttu-id="70b41-551">Questa modifica risolve un problema con la finestra di dialogo Comprimi immagine, che non mantiene determinate impostazioni dell'utente.</span><span class="sxs-lookup"><span data-stu-id="70b41-551">This change addresses an issue with the Compress Picture dialog not retaining certain user settings.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-september-08"></a><span data-ttu-id="70b41-553">Versione 1908: 8 settembre</span><span class="sxs-lookup"><span data-stu-id="70b41-553">Version 1908: September 08</span></span>
<span data-ttu-id="70b41-554">*Versione 1908 (Build 11929.20946)*</span><span class="sxs-lookup"><span data-stu-id="70b41-554">*Version 1908 (Build 11929.20946)*</span></span>

<span data-ttu-id="70b41-555">Gli aggiornamenti della sicurezza sono elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-555">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-2002-august-11"></a><span data-ttu-id="70b41-556">Versione 2002: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="70b41-556">Version 2002: August 11</span></span>
<span data-ttu-id="70b41-557">*Versione 2002 (Build 12527.20988)*</span><span class="sxs-lookup"><span data-stu-id="70b41-557">*Version 2002 (Build 12527.20988)*</span></span>

<span data-ttu-id="70b41-558">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-558">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-560">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-560">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-561">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-561">Excel</span></span>

- <span data-ttu-id="70b41-562">È stato risolto un problema che impediva di modificare i file aperti in modalità "Consigliata sola lettura".</span><span class="sxs-lookup"><span data-stu-id="70b41-562">Fixed an issue which prevented the ability to switch to editing for files that opened as "read-only recommended".</span></span>

### <a name="onenote"></a><span data-ttu-id="70b41-563">OneNote</span><span class="sxs-lookup"><span data-stu-id="70b41-563">OneNote</span></span>

- <span data-ttu-id="70b41-564">Sono state rimosse le chiamate di identità ridondanti per ridurre l'utilizzo delle risorse</span><span class="sxs-lookup"><span data-stu-id="70b41-564">Removed redundant identity calls to reduce resource utilization</span></span>

- <span data-ttu-id="70b41-565">È stato migliorato il rilevamento dello stato di collaborazione ai file per ridurre l’utilizzo delle risorse.</span><span class="sxs-lookup"><span data-stu-id="70b41-565">Improved detection of co-authoring status to reduce resource utilization.</span></span>

- <span data-ttu-id="70b41-566">Sono state migliorate la funzionalità di rilevamento di errori e la qualità dell'esperienza di sincronizzazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-566">Improved capability for detecting errors and the quality of the sync experience.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-567">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-567">Outlook</span></span>

- <span data-ttu-id="70b41-568">È stato risolto un problema che causava un notevole problema di prestazioni durante l'avvio di Outlook per alcuni tenant.</span><span class="sxs-lookup"><span data-stu-id="70b41-568">Addressed an issue that caused a significant performance issue when starting Outlook for some tenants.</span></span>

### <a name="skype"></a><span data-ttu-id="70b41-569">Skype</span><span class="sxs-lookup"><span data-stu-id="70b41-569">Skype</span></span>

- <span data-ttu-id="70b41-570">È stato risolto un problema che causava un errore di avvio della condivisione dello schermo quando un client Skype for Business a 32 bit era in uso per diversi giorni.</span><span class="sxs-lookup"><span data-stu-id="70b41-570">Fixed an issue where starting a screen share can fail on a 32-bit Skype for Business client after it has been running for several days.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-571">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-571">Office Suite</span></span>

- <span data-ttu-id="70b41-572">È stato risolto un problema per cui, se il salvataggio automatico era disattivato con i criteri di gruppo, quando si aprivano alcuni documenti per visualizzare il contenuto più recente sul server bisognava fare clic su "Aggiornamenti disponibili".</span><span class="sxs-lookup"><span data-stu-id="70b41-572">Fixed an issue where if AutoSave is turned off through group policy, some documents might not show the latest server contents on open until the user clicks on 'Updates available'.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-august-11"></a><span data-ttu-id="70b41-574">Versione 1908: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="70b41-574">Version 1908: August 11</span></span>
<span data-ttu-id="70b41-575">*Versione 1908 (Build 11929.20934)*</span><span class="sxs-lookup"><span data-stu-id="70b41-575">*Version 1908 (Build 11929.20934)*</span></span>

<span data-ttu-id="70b41-576">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-576">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1902-august-11"></a><span data-ttu-id="70b41-577">Versione 1902: 11 agosto</span><span class="sxs-lookup"><span data-stu-id="70b41-577">Version 1902: August 11</span></span>
<span data-ttu-id="70b41-578">*Versione 1902 (Build 11328.20644)*</span><span class="sxs-lookup"><span data-stu-id="70b41-578">*Version 1902 (Build 11328.20644)*</span></span>

<span data-ttu-id="70b41-579">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-579">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-2002-july-14"></a><span data-ttu-id="70b41-582">Versione 2002: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="70b41-582">Version 2002: July 14</span></span>
<span data-ttu-id="70b41-583">*Versione 2002 (Build 12527.20880)*</span><span class="sxs-lookup"><span data-stu-id="70b41-583">*Version 2002 (Build 12527.20880)*</span></span>

<span data-ttu-id="70b41-584">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-584">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="70b41-586">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="70b41-586">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="70b41-587">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-587">Access</span></span>

- <span data-ttu-id="70b41-588">**Trovare velocemente le tabelle collegate:** la nostra nuova casella di ricerca rende molto più facile trovare le tabelle collegate.</span><span class="sxs-lookup"><span data-stu-id="70b41-588">**Find linked tables fast:** Our new search box makes finding linked tables a breeze.</span></span> [<span data-ttu-id="70b41-589">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-589">Learn more</span></span>](https://support.office.com/article/1d9346d6-953d-4f85-a9ce-4caec2262797)

### <a name="excel"></a><span data-ttu-id="70b41-590">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-590">Excel</span></span>

- <span data-ttu-id="70b41-591">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="70b41-591">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="70b41-592">**Componente aggiuntivo Visualizzatore dati:** creazione rapida di diagrammi di flusso di Visio da Excel.</span><span class="sxs-lookup"><span data-stu-id="70b41-592">**Data visualizer add-in:** Quickly create Visio flowcharts from Excel.</span></span> [<span data-ttu-id="70b41-593">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-593">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="70b41-594">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="70b41-594">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="70b41-595">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-595">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="70b41-596">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="70b41-596">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="70b41-597">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-597">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="70b41-598">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-598">Find them at Insert > Icons.</span></span> [<span data-ttu-id="70b41-599">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-599">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="70b41-600">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="70b41-600">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="70b41-601">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="70b41-601">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="70b41-602">**Concentrarsi su ciò che resta da fare:** selezionare Risolvi per comprimere i commenti e far risaltare quelli ancora non risolti.</span><span class="sxs-lookup"><span data-stu-id="70b41-602">**Focus on what's left to do:** Select Resolve to collapse comments and make open items stand out.</span></span>

- <span data-ttu-id="70b41-603">**Digitare una formula che restituisce più valori:** è possibile digitare rapidamente una formula che restituisce più valori, che si estenderanno automaticamente nelle celle adiacenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-603">**Type a formula that returns multiple values:** Quickly type a formula that returns multiple values, and they'll automatically spill into the neighboring cells.</span></span> [<span data-ttu-id="70b41-604">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-604">Learn more</span></span>](https://support.office.com/article/5c2c9cbb-def8-409a-b380-2fbf91b20aa3)<br /><span data-ttu-id="70b41-605">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span><span class="sxs-lookup"><span data-stu-id="70b41-605">See details in [blog post](https://blog-insider.office.com/2019/06/13/dynamic-arrays-and-new-functions-in-excel/)</span></span>

- <span data-ttu-id="70b41-606">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="70b41-606">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="70b41-607">**Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella cartella di lavoro, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="70b41-607">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your workbook.</span></span> [<span data-ttu-id="70b41-608">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-608">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="70b41-609">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="70b41-609">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="70b41-610">**Trovare gli elementi cercati:** è possibile cercare comandi, persone, file, foto, notizie e molto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-610">**Find what you're looking for:** Search for commands, people, files, photos, web articles, and more.</span></span> [<span data-ttu-id="70b41-611">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-611">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="70b41-612">**Sei potenti funzioni:** sono state aggiunte sei nuove funzioni per potenziare i fogli di calcolo, ovvero FILTRO, DATI.ORDINA, DATI.ORDINA.PER, UNICI, SEQUENZA e MATR.CASUALE.</span><span class="sxs-lookup"><span data-stu-id="70b41-612">**Six powerful functions:** We’ve added six new functions to supercharge your spreadsheets: FILTER, SORT, SORTBY, UNIQUE, SEQUENCE and RANDARRAY.</span></span> [<span data-ttu-id="70b41-613">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-613">Learn more</span></span>](https://support.office.com/article/003df6c7-1dcb-4388-8e2e-0fe77a0887bc)

- <span data-ttu-id="70b41-614">**Cercare a sinistra, cercare a destra... ecco CERCA.X:** Riga per riga, per trovare tutto il necessario in una tabella o in un intervallo con CERCA.X.</span><span class="sxs-lookup"><span data-stu-id="70b41-614">**Look left, look right… XLOOKUP is here!:** Row by row, find anything you need in a table or range with XLOOKUP.</span></span> [<span data-ttu-id="70b41-615">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-615">Learn more</span></span>](https://support.office.com/article/b7fd680e-6d10-43e6-84f9-88eae8bf5929)<br /><span data-ttu-id="70b41-616">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span><span class="sxs-lookup"><span data-stu-id="70b41-616">See details in [blog post](https://blog-insider.office.com/2019/08/29/announcing-xlookup/)</span></span>

- <span data-ttu-id="70b41-617">**Gestire al meglio le cartelle di lavoro di grandi dimensioni:** celle, formule, grafici, tabelle... ottenere un’istantanea della cartella di lavoro con l’opzione Statistiche cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-617">**Tame your big workbook:** Cells, formulas, charts, tables... get a snapshot of your workbook with Workbook Statistics.</span></span>

- <span data-ttu-id="70b41-618">**Leggere e rispondere all'istante:** rispondere ai commenti e alle menzioni direttamente dalla posta elettronica senza aprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-618">**Read and reply on the fly:** Respond to comments and mentions right from email without opening the workbook.</span></span>

- <span data-ttu-id="70b41-619">**Ottenere l'attenzione tramite \@menzioni:** usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="70b41-619">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="70b41-620">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-620">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

### <a name="outlook"></a><span data-ttu-id="70b41-621">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-621">Outlook</span></span>

- <span data-ttu-id="70b41-622">**Possibilità di visualizzare più messaggi sullo schermo:** Selezionare Visualizza > Usa spazio più stretto per regolare la spaziatura tra i messaggi.</span><span class="sxs-lookup"><span data-stu-id="70b41-622">**Fit more messages on the screen:** Select View > Use Tighter Spacing to adjust spacing between messages.</span></span> [<span data-ttu-id="70b41-623">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-623">Learn more</span></span>](https://support.office.com/article/7aedcfaf-03de-49ad-9bf8-8730134f1f3b)

- <span data-ttu-id="70b41-624">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-624">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="70b41-625">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-625">Find them at Insert > Icons.</span></span> [<span data-ttu-id="70b41-626">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-626">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="70b41-627">**Aggiunta della funzionalità Input penna:** è possibile scarabocchiare sopra le immagini o aggiungere un'area di disegno per inviare idee con l'input penna.</span><span class="sxs-lookup"><span data-stu-id="70b41-627">**Let me draw it out:** Scribble on top of pictures or add a Drawing Canvas to send your thoughts with ink.</span></span> [<span data-ttu-id="70b41-628">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-628">Learn more</span></span>](https://support.office.com/article/3e928cae-7eb5-4c3f-8c60-28eb85afb7d5)

- <span data-ttu-id="70b41-629">**Suggerimenti per il luogo delle riunioni:** è sufficiente iniziare a scrivere nella riga Luogo durante la pianificazione di appuntamenti e riunioni e Outlook suggerirà sale, indirizzi e altri luoghi recenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-629">**Get location suggestions:** Start typing in Location when scheduling appointments and meetings, and Outlook will suggest rooms, addresses and other recent places.</span></span> [<span data-ttu-id="70b41-630">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-630">Learn more</span></span>](https://support.office.com/article/1d8631be-611a-4e3d-9109-b153e4622d53)<br /><span data-ttu-id="70b41-631">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span><span class="sxs-lookup"><span data-stu-id="70b41-631">See details in [blog post](https://blog-insider.office.com/2019/07/08/location-suggestions-in-outlook-for-windows/)</span></span>

- <span data-ttu-id="70b41-632">**Protezione avanzata dalle minacce:** con Office 365 Advanced Threat Protection, si è protetti dalle minacce tramite collegamenti ipertestuali negli oggetti di posta elettronica, messaggi allegati, messaggi firmati, percorsi di rete e così via.</span><span class="sxs-lookup"><span data-stu-id="70b41-632">**Advanced protection against attack:** With Office 365 Advanced Threat Protection, you're protected against attacks through hyperlinks within email subjects, attached messages, signed messages, network paths, and so on.</span></span>

- <span data-ttu-id="70b41-633">**Il menu Inserisci collegamento in Outlook inserisce un collegamento con l'autorizzazione definita dall'amministratore tenant:** un collegamento dall'elenco dei file usati di recenti in Inserisci collegamento in Outlook inseriva un collegamento che funzionava solo per gli utenti che avevano già le relative autorizzazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-633">**Insert Link Menu in Outlook will insert a link with permission defined by tenant admin:** A link from the Insert Link MRU in Outlook would insert a link that only worked for users who already had permissions to it.</span></span> <span data-ttu-id="70b41-634">Questo causava spesso uno scambio di messaggi tra gli utenti per richiedere l'accesso a un documento.</span><span class="sxs-lookup"><span data-stu-id="70b41-634">This often caused back and forth emails between users asking to be granted access to a document.</span></span> <span data-ttu-id="70b41-635">Questa esperienza è stata aggiornata in modo tale che il collegamento venga inserito con l'autorizzazione predefinita impostata dall'amministratore tenant. Per MSIT si tratta dell’opzione "L’organizzazione può modificare", pertanto tutti gli utenti interni che riceveranno un collegamento condiviso in questo modo saranno in grado di accedervi.</span><span class="sxs-lookup"><span data-stu-id="70b41-635">We've updated this experience so now the link is inserted with the default permission set by the tenant admin. For MSIT this is "organization can edit" so all internal users who receive a link shared this way will be able to access it.</span></span>

- <span data-ttu-id="70b41-636">**Vedere i messaggi sotto una luce diversa:** usare il pulsante Sole/Luna per utilizzare lo sfondo chiaro o lo sfondo scuro nel riquadro di lettura.</span><span class="sxs-lookup"><span data-stu-id="70b41-636">**See your messages in a different light:** Use the Sun/Moon button to switch between light and dark backgrounds in the reading pane.</span></span> [<span data-ttu-id="70b41-637">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-637">Learn more</span></span>](https://support.office.com/article/3e2446e0-9a7b-4189-9af9-57fb94d02ae3)

- <span data-ttu-id="70b41-638">**I messaggi di phishing sono facilmente individuabili:** la posta indesiderata e i messaggi di phishing hanno un aspetto diverso, in modo da poterli identificare e rimuovere facilmente dalla posta in arrivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-638">**Phishing mails are easy to spot:** Spam and phishing messages have a different look and feel so you can easily identify and eliminate them from your inbox.</span></span>

- <span data-ttu-id="70b41-p159">**Tutte le opzioni di crittografia in un'unica posizione:** basta passare a Opzioni > Crittografa per scegliere come proteggere il messaggio di posta elettronica. [Altre informazioni](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span><span class="sxs-lookup"><span data-stu-id="70b41-p159">**All your encryption options in one place:** Just go to Options > Encrypt to choose how to secure your email message. [Learn more](https://support.office.com/article/373339cb-bf1a-4509-b296-802a39d801dc)</span></span>

- <span data-ttu-id="70b41-641">**Cercare testo contenente errori di ortografia o di digitazione:** Outlook troverà il testo cercato anche quando l'ortografia non è corretta.</span><span class="sxs-lookup"><span data-stu-id="70b41-641">**Search with spelling woes or typos:** Outlook will find what you're looking for even when your spelling doesn't match.</span></span>

- <span data-ttu-id="70b41-642">**Connessione della rete LinkedIn a Outlook:** connessione sicura degli account LinkedIn all'account Microsoft per visualizzare le informazioni dei profili LinkedIn direttamente nella scheda Utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-642">**Connect your LinkedIn network with Outlook:** Securely connect your LinkedIn account with your Microsoft account to see information from LinkedIn profiles directly in the People card.</span></span> [<span data-ttu-id="70b41-643">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-643">Learn more</span></span>](https://support.office.com/article/98253fdc-a3c2-47e4-8852-ebb4fbed0bc5)

- <span data-ttu-id="70b41-644">**Visualizza i messaggi rilevanti nei risultati della ricerca:** Outlook analizza i termini di ricerca e visualizza i messaggi di posta elettronica più importanti nella parte superiore dei risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-644">**See relevant messages in your search results:** Outlook analyzes search terms and shows the most relevant email messages at the top of your search results.</span></span> <span data-ttu-id="70b41-645">I risultati saranno ordinati anche per data nella sezione Risultati principali.</span><span class="sxs-lookup"><span data-stu-id="70b41-645">You'll also see all results sorted by date in the Top Results section.</span></span> [<span data-ttu-id="70b41-646">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-646">Learn more</span></span>](https://support.office.com/article/67656bfc-4294-4dea-8422-de6382c49317)

### <a name="powerpoint"></a><span data-ttu-id="70b41-647">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-647">PowerPoint</span></span>

- <span data-ttu-id="70b41-p162">**La formattazione dei calcoli diventa automatica:** le espressioni matematiche scritte a mano vengono convertite in caratteri standard. Per iniziare, basta selezionare le note scritte a mano e scegliere Da input penna a testo matematico. [Altre informazioni](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span><span class="sxs-lookup"><span data-stu-id="70b41-p162">**You compute, we format:** We change hand-drawn math expressions into standard characters. Just choose Ink to Math and select your handwritten notes to get started. [Learn more](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)</span></span>

- <span data-ttu-id="70b41-651">**Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-651">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="70b41-652">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-652">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="70b41-653">**Input penna per diapositive meravigliose:** è possibile convertire l'input penna in forme e testo standard e quindi ottenere idee di progettazione delle diapositive intelligenti da PowerPoint Designer.</span><span class="sxs-lookup"><span data-stu-id="70b41-653">**Ink a splendid slide:** Convert your ink to standard shapes and text, then get smart slide-design ideas from PowerPoint Designer.</span></span> [<span data-ttu-id="70b41-654">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-654">Learn more</span></span>](https://support.office.com/article/53c77d7b-dc40-45c2-b684-81415eac0617)

- <span data-ttu-id="70b41-655">**Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nella presentazione, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="70b41-655">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your presentation.</span></span> [<span data-ttu-id="70b41-656">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-656">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="70b41-657">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="70b41-657">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="70b41-658">**Replay immediato:** applicare un'animazione di riproduzione per ripetere la sequenza di disegno con l'input penna durante la presentazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-658">**Ink-stant replay:** When inking on your slides, apply a replay animation to replay the actual drawing of your ink during your slide show.</span></span> [<span data-ttu-id="70b41-659">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-659">Learn more</span></span>](https://support.office.com/article/fa4f044f-810b-43fe-b774-da04a0b37496)<br /><span data-ttu-id="70b41-660">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span><span class="sxs-lookup"><span data-stu-id="70b41-660">See details in [blog post](https://blog-insider.office.com/2019/07/02/be-more-expressive-in-your-presentations-by-using-ink-replay-in-powerpoint/)</span></span>

- <span data-ttu-id="70b41-661">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="70b41-661">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span>

- <span data-ttu-id="70b41-662">**Salvare un'illustrazione in formato SVG:** è possibile salvare un grafico, una forma o un'altra illustrazione in formato SVG (Scalable Vector Graphic), che può essere ridimensionato senza perdita di qualità dell'immagine.</span><span class="sxs-lookup"><span data-stu-id="70b41-662">**Save an illustration as SVG:** Save a chart, shape, or other illustration as a scalable vector graphic, which can be resized with no loss of image quality.</span></span> [<span data-ttu-id="70b41-663">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-663">Learn more</span></span>](https://support.office.com/article/3c4f9ca4-945a-4c33-af91-d10e4e3ea715)

- <span data-ttu-id="70b41-664">**Stampa dei numeri delle diapositive negli stampati:** i numeri delle diapositive vengono inclusi automaticamente negli stampati.</span><span class="sxs-lookup"><span data-stu-id="70b41-664">**Print slide numbers on handouts:** Slide numbers are included on your handouts automatically.</span></span> <span data-ttu-id="70b41-665">Lasciarli attivati o disattivarli è a discrezione dell'utente.</span><span class="sxs-lookup"><span data-stu-id="70b41-665">Leave them on, turn them off, it's all up to you.</span></span> [<span data-ttu-id="70b41-666">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-666">Learn more</span></span>](https://support.office.com/article/194d4320-aa03-478b-9300-df25f0d15dc4)

- <span data-ttu-id="70b41-667">**Trovare e correggere titoli di diapositive mancanti:** i titoli delle diapositive ottimizzano la presentazione e rendono le diapositive accessibili per tutti gli utenti, anche con diverse abilità.</span><span class="sxs-lookup"><span data-stu-id="70b41-667">**Find and fix missing slide titles:** Slide titles add punch to your pitch and make your slides accessible to users of all abilities.</span></span> <span data-ttu-id="70b41-668">L’opzione Verifica accessibilità mostra dove mancano i titoli in modo da aggiungerli in pochi secondi.</span><span class="sxs-lookup"><span data-stu-id="70b41-668">Accessibility Checker shows you where titles are missing so you can add them in a snap.</span></span> [<span data-ttu-id="70b41-669">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-669">Learn more</span></span>](https://support.office.com/article/c5286802-495a-4b47-a8ae-212fb8a7dc74)

- <span data-ttu-id="70b41-670">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="70b41-670">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="70b41-671">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="70b41-671">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="70b41-672">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-672">**More icons to match your mood:** We've added more than 300 new icons.</span></span> <span data-ttu-id="70b41-673">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-673">Find them at Insert > Icons.</span></span> [<span data-ttu-id="70b41-674">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-674">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)

- <span data-ttu-id="70b41-675">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="70b41-675">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span><br /><span data-ttu-id="70b41-676">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="70b41-676">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="70b41-677">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="70b41-677">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="70b41-678">**Collaborazione in tempo reale veloce in PowerPoint:** è possibile collaborare in tempo reale rapidamente in PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-678">**Fast real-time collaboration in PowerPoint:** Fast real-time collaboration in PowerPoint</span></span>

- <span data-ttu-id="70b41-679">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="70b41-679">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span>

- <span data-ttu-id="70b41-680">**Nuovi strumenti di correzione:** niente più preoccupazione per le parole.</span><span class="sxs-lookup"><span data-stu-id="70b41-680">**New proofreading tools:** Don't stress about your words.</span></span> <span data-ttu-id="70b41-681">PowerPoint offre suggerimenti relativi a grammatica e ortografia.</span><span class="sxs-lookup"><span data-stu-id="70b41-681">PowerPoint now provides grammar and writing suggestions.</span></span> [<span data-ttu-id="70b41-682">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-682">Learn more</span></span>](https://support.office.com/article/91ecbe1b-d021-4e9e-a82e-abc4cd7163d7)

- <span data-ttu-id="70b41-683">**Sottotitoli e sottotitoli in tempo reale:** le parole del relatore vengono visualizzate automaticamente sullo schermo come sottotitoli o tradotti in sottotitoli nella lingua scelta.</span><span class="sxs-lookup"><span data-stu-id="70b41-683">**Live captions and subtitles:** The presenter’s words are automatically shown on screen as captions or translated into subtitles in the language of your choice.</span></span> [<span data-ttu-id="70b41-684">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-684">Learn more</span></span>](https://support.office.com/article/68d20e49-aec3-456a-939d-34a79e8ddd5f)

- <span data-ttu-id="70b41-685">**Ottimizzazione della presentazione per tutti:** Verifica accessibilità consente di organizzare gli oggetti nelle diapositive tenendo in considerazione le utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="70b41-685">**Optimize your presentation for all:** Accessibility Checker helps you arrange objects on your slides with screen readers in mind.</span></span><br /><span data-ttu-id="70b41-686">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span><span class="sxs-lookup"><span data-stu-id="70b41-686">See details in [blog post](https://blog-insider.office.com/2019/10/15/reach-more-people-by-making-your-powerpoint-slides-work-with-a-screen-reader/)</span></span>

- <span data-ttu-id="70b41-687">**Perché reinventare quando è possibile riutilizzare?:** per risparmiare tempo, è possibile riutilizzare le diapositive create personalmente o condivise da altri utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-687">**Why reinvent when you can re-use?:** Save time by re-using slides that you created or that others have shared with you.</span></span> [<span data-ttu-id="70b41-688">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-688">Learn more</span></span>](https://support.office.com/article/4772661f-ced0-446b-bb28-878dfa8c23f1)

### <a name="visio"></a><span data-ttu-id="70b41-689">Visio</span><span class="sxs-lookup"><span data-stu-id="70b41-689">Visio</span></span>

- <span data-ttu-id="70b41-690">**Creare diagrammi di Visio chiari in Excel:** è possibile creare un diagramma di flussi o un organigramma inserendo i dati in un foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-690">**Make polished Visio diagrams in Excel:** Create a flow chart or organizational chart by putting data on a worksheet.</span></span> [<span data-ttu-id="70b41-691">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-691">Learn more</span></span>](https://support.office.com/article/bee3b5aa-aaaf-4401-acc6-276b711c763c)

- <span data-ttu-id="70b41-692">**Analisi della scena del crimine:** è possibile usare i nuovi stencil Prova, Interni ed Esterni nel modello di indagine della scena del crimine per ricreare in dettaglio le scene del crimine.</span><span class="sxs-lookup"><span data-stu-id="70b41-692">**Back to the scene of the crime:** Use new Evidence, Indoor, and Outdoor stencils in the Crime Scene Investigation template to recreate crime scenes in detail.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-693">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-693">Word</span></span>

- <span data-ttu-id="70b41-694">**Un'esperienza video più sicura:** i miglioramenti della sicurezza offrono un'esperienza video online più sicura.</span><span class="sxs-lookup"><span data-stu-id="70b41-694">**A more secure video experience:** Security enhancements mean a safer online video experience for you.</span></span> [<span data-ttu-id="70b41-695">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-695">Learn more</span></span>](https://support.office.com/article/bf11b812-0243-4f53-a1f9-432fbf7ace2c)

- <span data-ttu-id="70b41-696">**Creare PDF più accessibili:** quando si crea un file PDF, la funzione Verifica accessibilità indica i problemi di accessibilità da correggere prima di salvare.</span><span class="sxs-lookup"><span data-stu-id="70b41-696">**Create more accessible PDFs:** Create a PDF and the accessibility checker will point out accessibility issues to fix before you save.</span></span> [<span data-ttu-id="70b41-697">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-697">Learn more</span></span>](https://support.office.com/article/064625e0-56ea-4e16-ad71-3aa33bb4b7ed)<br /><span data-ttu-id="70b41-698">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span><span class="sxs-lookup"><span data-stu-id="70b41-698">See details in [blog post](https://blog-insider.office.com/2019/08/13/accessible-pdfs-made-easier/)</span></span>

- <span data-ttu-id="70b41-699">**Condivisione dei file più rapida:** è possibile condividere i documenti direttamente dall'elenco degli ultimi file usati senza dover aprire il file.</span><span class="sxs-lookup"><span data-stu-id="70b41-699">**Faster file sharing:** Share your documents right from the recently used list without having to open the file.</span></span>

- <span data-ttu-id="70b41-700">**Altre icone che corrispondono al proprio umore:** sono state aggiunte più di 300 nuove icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-700">**More icons to match your mood:** We've added over 300 new icons.</span></span> <span data-ttu-id="70b41-701">Per scoprirle, scegliere Inserisci > Icone.</span><span class="sxs-lookup"><span data-stu-id="70b41-701">Find them at Insert > Icons.</span></span> [<span data-ttu-id="70b41-702">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-702">Learn more</span></span>](https://support.office.com/article/3b179567-785e-42ac-8544-ec4ee5ebf1c8)<br /><span data-ttu-id="70b41-703">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span><span class="sxs-lookup"><span data-stu-id="70b41-703">See details in [blog post](https://blog-insider.office.com/2019/04/24/your-feedback-in-action-new-insertable-icons/)</span></span>

- <span data-ttu-id="70b41-704">**Cancellare con precisione:** è possibile scegliere tra due dimensioni della gomma per correggere le piccole imperfezioni dell'input penna.</span><span class="sxs-lookup"><span data-stu-id="70b41-704">**Erase with precision:** Choose from two eraser sizes to fix small inking imperfections.</span></span> [<span data-ttu-id="70b41-705">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-705">Learn more</span></span>](https://support.office.com/article/6d76c674-7f4b-414d-b67f-b3ffef6ccf53)

- <span data-ttu-id="70b41-706">**Convertire i file per migliorare l'accessibilità:** aggiornare i file al formato moderno per renderli più accessibili per tutti.</span><span class="sxs-lookup"><span data-stu-id="70b41-706">**Convert files to improve accessibility:** Upgrade your files to the modern format to make them more accessible for everyone.</span></span><br /><span data-ttu-id="70b41-707">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span><span class="sxs-lookup"><span data-stu-id="70b41-707">See details in [blog post](https://blog-insider.office.com/2019/10/07/take-full-advantage-of-accessibility-in-office-documents/)</span></span>

- <span data-ttu-id="70b41-708">**Creare schizzi**: è possibile conferire un aspetto informale alle forme di Office incluse nel documento, in modo che sembrino disegnate a mano.</span><span class="sxs-lookup"><span data-stu-id="70b41-708">**Sketch it out:** Give a casual, hand-drawn look to Office shapes in your document.</span></span> [<span data-ttu-id="70b41-709">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-709">Learn more</span></span>](https://support.office.com/article/ec2e4491-d3bf-4266-beac-f6298fdfde9f)<br /><span data-ttu-id="70b41-710">Vedere i dettagli nel [post di blog](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span><span class="sxs-lookup"><span data-stu-id="70b41-710">See details in [blog post](https://blog-insider.office.com/2019/07/03/sketchy-shapes-for-word-powerpoint-and-excel/)</span></span>

- <span data-ttu-id="70b41-711">**Trovare gli elementi cercati:** è possibile usare la casella di ricerca per eseguire ricerche relative a testo, comandi, guida e tanto altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-711">**Find what you're looking for:** Use the search box to find text, commands, help, and more.</span></span> [<span data-ttu-id="70b41-712">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-712">Learn more</span></span>](https://support.office.com/article/2457d4d8-48a8-4ad4-ab89-5a0657aa8446)

- <span data-ttu-id="70b41-713">**Possibilità di scegliere dove aprire i collegamenti:** è possibile scegliere come aprire i collegamenti a documenti di Office, ovvero nel browser o nell'app.</span><span class="sxs-lookup"><span data-stu-id="70b41-713">**No more bouncing to the browser:** You decide how links to Office documents open: in the browser or in the app.</span></span> [<span data-ttu-id="70b41-714">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-714">Learn more</span></span>](https://support.office.com/article/fe241745-9e05-4142-9ba8-1bb1dc044773)

- <span data-ttu-id="70b41-715">**Editor per curriculum unito all’Assistente curriculum LinkedIn:** l’editor per il curriculum offre una selezione di controlli grammaticali e stilistici appositamente studiati per i curriculum, per rendere la scrittura più precisa e professionale.</span><span class="sxs-lookup"><span data-stu-id="70b41-715">**Editor for Resume joins LinkedIn Resume Assistant:** Editor for Resume offers a selection of grammar and style checks specially tailored for resumes, to make your writing more precise and professional.</span></span>

- <span data-ttu-id="70b41-716">**Gli altri utenti possono visualizzare rapidamente le modifiche:** i miglioramenti della creazione condivisa indicano che i collaboratori possono visualizzare le modifiche in modo più veloce che mai.</span><span class="sxs-lookup"><span data-stu-id="70b41-716">**Others see your changes quickly:** Co-authoring improvements mean your collaborators can see your changes faster than ever before.</span></span>

- <span data-ttu-id="70b41-717">**Risoluzione di un problema di danneggiamento di un documento causato dall'unione di oggetti 3D:** è stato risolto un problema di danneggiamento di un documento causato dall'unione di oggetti 3D.</span><span class="sxs-lookup"><span data-stu-id="70b41-717">**Fixed a document corruption issue caused by merge of 3D objects.:** Fixed a document corruption issue caused by merge of 3D objects.</span></span>

- <span data-ttu-id="70b41-718">**Miglioramenti alla creazione condivisa:** prestazioni migliorate per la creazione condivisa nei documenti di Word con revisioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-718">**Coauthoring improvements:** Improved Word performance when coauthoring in documents with tracked changes.</span></span>

- <span data-ttu-id="70b41-719">**Miglioramenti alla creazione condivisa:** maggiore affidabilità durante la creazione condivisa.</span><span class="sxs-lookup"><span data-stu-id="70b41-719">**Coauthoring improvements:** Improved reliability when coauthoring.</span></span>

- <span data-ttu-id="70b41-720">**Collaborare con colori vivaci:** i commenti e le modifiche sono contraddistinti da colori associati ai vari collaboratori, in modo che risulti facile identificarli.</span><span class="sxs-lookup"><span data-stu-id="70b41-720">**Collaborate in living color:** Comments and changes are color coded by contributor so it's easy to see who's who among your collaborators.</span></span>

- <span data-ttu-id="70b41-721">**Modificare i documenti con attivazione macro in modo collaborativo:** è possibile salvare i file docm su OneDrive for Business e modificarli con i collaboratori in tempo reale.</span><span class="sxs-lookup"><span data-stu-id="70b41-721">**Edit macro-enabled docs collaboratively:** Save your docm files on OneDrive for Business and edit with your collaborators in real time.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-722">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-722">Office Suite</span></span>

- <span data-ttu-id="70b41-723">**Convertire l'input penna a mano libera in forme, testo o equazioni matematiche in PowerPoint per Office 365:** è possibile passare dall'input penna a mano libera al testo, a un'espressione matematica o alle forme di Office, con un paio di tratti.</span><span class="sxs-lookup"><span data-stu-id="70b41-723">**Change handwritten ink to shapes, text, or math in PowerPoint for Office 365:** Go from free-form ink to Office shapes, text, or a mathematical expression in a couple of strokes.</span></span> [<span data-ttu-id="70b41-724">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-724">Learn more</span></span>](https://support.office.com/article/0740dec3-6291-4c1f-8baa-011d18449919)


[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-727">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-727">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="70b41-728">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-728">Access</span></span>

- <span data-ttu-id="70b41-729">Questo aggiornamento consente di risolvere un problema relativo all'uso di un oggetto ADODB.</span><span class="sxs-lookup"><span data-stu-id="70b41-729">This update fixes an issue where using an ADODB.</span></span> <span data-ttu-id="70b41-730">L'oggetto Recorder nel codice VB potrebbe erroneamente segnalare un errore.</span><span class="sxs-lookup"><span data-stu-id="70b41-730">Recorder object in VB code may incorrectly report an error.</span></span>

- <span data-ttu-id="70b41-731">I modelli di Access non dovrebbero più causare errori nelle colonne degli allegato all'interno di un database.</span><span class="sxs-lookup"><span data-stu-id="70b41-731">Access templates should no longer cause attachment columns to fail within a database.</span></span> <span data-ttu-id="70b41-732">Dopo aver creato un'istanza di un modello, si dovrebbe essere in grado di aggiungere un campo degli allegati al database.</span><span class="sxs-lookup"><span data-stu-id="70b41-732">After instantiating a template, you should now be able to add an attachment field to your database.</span></span>

- <span data-ttu-id="70b41-733">Questo aggiornamento risolve un problema in Microsoft Access che causava un errore d'identificazione della colonna Identity in una tabella di SQL Server collegata e la segnalazione di righe eliminate in modo non corretto.</span><span class="sxs-lookup"><span data-stu-id="70b41-733">This update fixes an issue that can cause Microsoft Access to fail to identify an Identity Column in a linked SQL Server table, which can cause rows to be reported as deleted incorrectly.</span></span>

- <span data-ttu-id="70b41-734">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo “Query danneggiata” quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="70b41-734">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="70b41-735">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-735">Excel</span></span>

- <span data-ttu-id="70b41-736">Velocizzato il caricamento dei file disponibili nella cartella locale di OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-736">Speed up loading of files that are available on local OneDrive folder.</span></span>

- <span data-ttu-id="70b41-737">È stato risolto un problema per cui a volte le funzioni VALORE.CUBO restituivano un risultato non corretto.</span><span class="sxs-lookup"><span data-stu-id="70b41-737">Fixed an issue where CUBEVALUE functions would sometimes return an incorrect result.</span></span>

- <span data-ttu-id="70b41-738">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="70b41-738">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="70b41-739">In alcuni casi, Excel si arrestava in modo anomalo alla riapertura di una cartella di lavoro incorporata in Word o PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-739">Excel would crash in certain cases when re-opening a workbook embedded in Word or PowerPoint.</span></span>

- <span data-ttu-id="70b41-740">È stato risolto un problema che impediva la visualizzazione dei comandi di commento nel menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="70b41-740">Fixed an issue where comment commands in the context menu were not being displayed.</span></span>

- <span data-ttu-id="70b41-741">Tramite il menu di scelta rapida predefinito per i grafici pivot ora è possibile abilitare l'opzione Mostra dettagli.</span><span class="sxs-lookup"><span data-stu-id="70b41-741">We fixed the right click menu for Pivot Charts to enable the option to Show Details.</span></span>

- <span data-ttu-id="70b41-742">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="70b41-742">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="70b41-743">È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-743">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="70b41-744">Durante il salvataggio in formato CSV, in alcuni casi Excel univa tutte le colonne in una singola colonna.</span><span class="sxs-lookup"><span data-stu-id="70b41-744">When saving as a CSV file, Excel could merge all columns into a single column in some cases.</span></span>

- <span data-ttu-id="70b41-745">L'uso di Range.ClearContents in un intervallo in un foglio protetto poteva richiedere più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-745">Using Range.ClearContents on a range in a protected sheet could take longer than expected.</span></span>

- <span data-ttu-id="70b41-746">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-746">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="70b41-747">Le macro VBA che interagiscono con la barra multifunzione possono essere eseguite con ScreenUpdating inaspettatamente impostato su True.</span><span class="sxs-lookup"><span data-stu-id="70b41-747">VBA macros that interact with the ribbon may run with ScreenUpdating set to True unexpectedly.</span></span>

- <span data-ttu-id="70b41-748">È stato risolto un problema che in alcuni casi causava il blocco anomalo di Excel dopo aver copiato un foglio di calcolo contenente una tabella pivot.</span><span class="sxs-lookup"><span data-stu-id="70b41-748">Fixed an issue which would cause Excel to crash in some cases after copying a sheet containing a PivotTable.</span></span>

- <span data-ttu-id="70b41-749">In alcuni casi, l'apertura di file CSV impiega più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-749">Opening CSV files was taking longer than expected in some circumstances.</span></span>

- <span data-ttu-id="70b41-750">In alcuni casi, Excel potrebbe arrestarsi in modo anomalo quando si passa da una cartella di lavoro a un'altra con livelli di zoom diversi.</span><span class="sxs-lookup"><span data-stu-id="70b41-750">Excel may crash in some circumstances when switching between workbooks with different zoom levels.</span></span>

- <span data-ttu-id="70b41-751">È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-751">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="70b41-752">I dati copiati da una colonna filtrata in base al colore a volte non vengono incollati correttamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-752">Data copied from a column filtered by color sometimes would not paste properly.</span></span>

- <span data-ttu-id="70b41-753">Aprire una cartella di lavoro con riferimenti a molte altre cartelle di lavoro, in particolare con finestre nascoste, risulta un'operazione piuttosto lenta.</span><span class="sxs-lookup"><span data-stu-id="70b41-753">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="70b41-754">È stato risolto un problema per cui i collegamenti esterni non venivano aggiornati durante il riempimento (copia in basso o tra fogli di lavoro) se la cartella di lavoro di origine era& chiusa.</span><span class="sxs-lookup"><span data-stu-id="70b41-754">Addressed an issue where external links don't update on fill (fill down, fill across, etc.) if the source book is& closed.</span></span>

- <span data-ttu-id="70b41-755">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="70b41-755">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="70b41-756">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="70b41-756">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="70b41-757">Risolve un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambia in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="70b41-757">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="70b41-758">È stato risolto un problema per cui la personalizzazione CustomUI XML per la scheda della barra multifunzione veniva rimossa durante il salvataggio su SharePoint/OneDrive.</span><span class="sxs-lookup"><span data-stu-id="70b41-758">Fixed an issue which caused CustomUI XML for a custom ribbon tab to be removed when saving to SharePoint/OneDrive.</span></span>

- <span data-ttu-id="70b41-759">Sono state migliorate le prestazioni associate all'eliminazione di colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="70b41-759">Improved performance when deleting columns with merged cells.</span></span>

- <span data-ttu-id="70b41-760">È stato risolto un problema che causava la ripetizione dei nomi delle stampanti nell'elenco all'interno della finestra di dialogo Stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-760">Fixed an issue where printer names could be repeated in the list of printers in the Print dialog.</span></span>

- <span data-ttu-id="70b41-761">È stato risolto un problema relativo al mancato funzionamento del collegamento esterno in seguito alla riapertura del file in caso di percorso del file troppo lungo.</span><span class="sxs-lookup"><span data-stu-id="70b41-761">Fixed an issue where the external link stops working after the file is reopened if the file path is too long.</span></span>

- <span data-ttu-id="70b41-762">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-762">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="70b41-763">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="70b41-763">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="70b41-764">L'inserimento di una colonna in un elenco filtrato richiedeva più tempo del previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-764">Inserting a column in a filtered list would take longer than expected.</span></span>

- <span data-ttu-id="70b41-765">È stato risolto un problema per cui alcuni collegamenti a grafici copiati e incollati usavano indirizzi di unità mappata invece che indirizzi universali.</span><span class="sxs-lookup"><span data-stu-id="70b41-765">We fixed an issue where some copy and pasted chart links used mapped drive addresses rather than universal addresses.</span></span>

- <span data-ttu-id="70b41-766">È stato risolto un problema per cui veniva visualizzato il messaggio di errore "Questa cartella di lavoro non può essere chiusa in quanto esiste un'altra cartella di lavoro che fa riferimento ad essa", perché i componenti aggiuntivi venivano caricati in ordine alfabetico anziché in un ordine specificato dall'utente.</span><span class="sxs-lookup"><span data-stu-id="70b41-766">Fixed an issue where the error message “This workbook is currently referenced by another and cannot be closed” would appear because add-ins were being loaded in alphabetical order rather than in a user specified order.</span></span>

- <span data-ttu-id="70b41-767">È stato risolto un problema per cui una cartella di lavoro poteva venire nascosta dopo aver fatto clic su un collegamento ipertestuale a un punto in una cartella di lavoro già aperta.</span><span class="sxs-lookup"><span data-stu-id="70b41-767">Fixed an issue where a workbook could become hidden when clicking a hyperlink to a spot within an already opened workbook.</span></span>

- <span data-ttu-id="70b41-768">Aprire una cartella di lavoro con riferimenti a molte altre cartelle di lavoro, in particolare con finestre nascoste, risulta un'operazione piuttosto lenta.</span><span class="sxs-lookup"><span data-stu-id="70b41-768">Opening a workbook with references to numerous other workbooks, especially with hidden windows, would be slower than expected.</span></span>

- <span data-ttu-id="70b41-769">L'uso di Application.Evaluate di VBA talvolta non funzionava per le funzioni definite dall'utente.</span><span class="sxs-lookup"><span data-stu-id="70b41-769">Using VBA's Application.Evaluate was not working for User-defined functions in some cases.</span></span>

- <span data-ttu-id="70b41-770">È stato risolto un problema che alcuni utenti potrebbero aver riscontrato con oggetti incorporati e collegati (OLE).</span><span class="sxs-lookup"><span data-stu-id="70b41-770">Fixed an issue that some users may have experienced with embedded and linked objects (OLE).</span></span>

- <span data-ttu-id="70b41-771">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-771">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="70b41-772">Questo aggiornamento risolve un problema per cui nella barra della formula veniva visualizzato del testo in un carattere diverso da quello previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-772">This update fixes an issue that caused the formula bar to display text in a different font than expected.</span></span>

- <span data-ttu-id="70b41-773">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-773">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="70b41-774">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="70b41-774">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="70b41-775">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="70b41-775">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="70b41-776">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="70b41-776">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="70b41-777">La funzionalità Testo in colonne può non funzionare per alcune localizzazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-777">Text to Column functionality may fail for some localizations.</span></span>

- <span data-ttu-id="70b41-778">Risolve un problema di prestazioni durante la creazione di grafici dai modelli.</span><span class="sxs-lookup"><span data-stu-id="70b41-778">Addresses a performance issue when creating charts from templates.</span></span>

- <span data-ttu-id="70b41-779">È stato risolto un problema che causava arresti anomali durante la conversione del testo in colonne con celle dotate di una matrice con espansione.</span><span class="sxs-lookup"><span data-stu-id="70b41-779">Fixed an issue that caused some users to experience crashes when converting text to columns with cells that have a spilling array.</span></span>

- <span data-ttu-id="70b41-780">Se si usa un Range.Value e un Range.Value2 (VBA), le formule vengono immesse come matrici dinamiche.</span><span class="sxs-lookup"><span data-stu-id="70b41-780">Using a Range.Value and Range.Value2 (VBA) would cause formulas to be entered as dynamic arrays.</span></span>

- <span data-ttu-id="70b41-781">È stato risolto un problema per cui un simbolo @ che avvia una formula veniva considerato come operatore di intersezione implicito.</span><span class="sxs-lookup"><span data-stu-id="70b41-781">Fixed an issue where an @ symbol starting a formula would be considered an implicit intersection operator.</span></span>

- <span data-ttu-id="70b41-782">È stato risolto un problema per cui i fogli di lavoro contenenti più formule con nomi definiti richiedevano tempi più lunghi per il salvataggio dei file.</span><span class="sxs-lookup"><span data-stu-id="70b41-782">We fixed an issue where worksheets containing multiple formulas with defined names was resulting in longer times when saving files.</span></span>

- <span data-ttu-id="70b41-783">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="70b41-783">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="70b41-784">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="70b41-784">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

### <a name="onenote"></a><span data-ttu-id="70b41-785">OneNote</span><span class="sxs-lookup"><span data-stu-id="70b41-785">OneNote</span></span>

- <span data-ttu-id="70b41-786">Migliora la sincronizzazione e la stabilità del servizio modificando temporaneamente la frequenza di sincronizzazione in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-786">Improve sync and service stability by temporarily adjusting sync frequency in OneNote 2016.</span></span>

- <span data-ttu-id="70b41-787">Migliora la sincronizzazione e la stabilità del servizio rimandando temporaneamente il download di immagini e file incorporati in blocchi appunti online finché l'utente esplora la pagina in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-787">Improve sync and service stability by temporarily deferring the downloading of embedded files and images in online notebooks until the user navigates to the page in OneNote 2016.</span></span>

- <span data-ttu-id="70b41-788">Migliora la sincronizzazione e la stabilità del servizio disabilitando temporaneamente il cestino in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-788">Improve sync and service stability by temporarily disabling the recycle bin in OneNote 2016.</span></span> <span data-ttu-id="70b41-789">Quando un utente prova a eliminare dati che normalmente verrebbero spostati nel cestino, all'utente verrà chiesto se vuole mantenere o eliminare definitamente il file.</span><span class="sxs-lookup"><span data-stu-id="70b41-789">When a user tries to delete data that would normally be sent to the recycle bin, users will be asked if they would prefer to keep or permanently delete the data.</span></span>

- <span data-ttu-id="70b41-790">Migliora la sincronizzazione e la stabilità del servizio riducendo temporaneamente il numero e la frequenza di sincronizzazione delle pagine della cronologia versioni di OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-790">Improve sync and service stability by temporarily reducing the number and sync frequency of version history pages in OneNote 2016.</span></span>

- <span data-ttu-id="70b41-791">Visualizza una notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="70b41-791">Display a notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

- <span data-ttu-id="70b41-792">Migliora la sincronizzazione e la stabilità del servizio riducendo temporaneamente a 50 MB la dimensione massima consentita per i nuovi allegati incorporati in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-792">Improve sync and service stability by temporarily reducing the maximum allowable size of new embedded attachments to 50MB in OneNote 2016.</span></span> <span data-ttu-id="70b41-793">Per i file che superano questo limite, gli utenti avranno la possibilità di caricare il file in OneDrive e inserire un collegamento in OneNote.</span><span class="sxs-lookup"><span data-stu-id="70b41-793">For files that exceed this limit, users will have the option of uploading the file to OneDrive and inserting a link into OneNote.</span></span>

- <span data-ttu-id="70b41-794">Migliora la sincronizzazione e la stabilità del servizio disabilitando temporaneamente la registrazione dei video in-app in OneNote 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-794">Improve sync and service stability by temporarily disabling in-app video recording in OneNote 2016.</span></span> <span data-ttu-id="70b41-795">I blocchi appunti locali non vengono interessati da questa operazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-795">Local notebooks are not impacted by this measure.</span></span>

- <span data-ttu-id="70b41-796">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="70b41-796">Localises the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-797">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-797">Outlook</span></span>

- <span data-ttu-id="70b41-798">È stato risolto un problema per cui la finestra IME (Input Method Editor) si sovrapponeva al testo sottostante inserito attraverso l’IME, quando venivano usati più monitor con risoluzioni diverse.</span><span class="sxs-lookup"><span data-stu-id="70b41-798">We fixed an issue where the IME (Input Method Editor) window would overlap the underlying text being entered via the IME when using multiple monitors with different resolutions.</span></span>

- <span data-ttu-id="70b41-799">Risolve un problema per cui gli utenti visualizzavano arresti anomali occasionali in Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-799">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="70b41-800">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="70b41-800">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="70b41-801">Risolve un problema che causava l'accesso dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto. </span><span class="sxs-lookup"><span data-stu-id="70b41-801">Addresses an issue that caused web add ins to access Digital Rights Managed messages.</span></span>

- <span data-ttu-id="70b41-802">Risolve un problema per cui appuntamenti o riunioni ricorrenti venivano visualizzati all’orario sbagliato quando era necessario cambiare la definizione del fuso orario.</span><span class="sxs-lookup"><span data-stu-id="70b41-802">Addresses an issue that caused recurring appointments or meetings to be displayed at the wrong time when approaching a timezone definition change.</span></span>

- <span data-ttu-id="70b41-803">Quando si usa il fuso orario di Brasilia nell'anno 2019, le riunioni e gli appuntamenti ricorrenti vengono visualizzati nella fascia oraria sbagliata per l'anno 2020.</span><span class="sxs-lookup"><span data-stu-id="70b41-803">When using the Brazilia time zone in the year 2019, recurring meetings and appointments are displayed in the wrong timeslot for the year 2020.</span></span> <span data-ttu-id="70b41-804">Questa modifica è rilevante per i client configurati per il fuso orario di Brasilia o per le riunioni e gli appuntamenti impostati in tale fuso orario.</span><span class="sxs-lookup"><span data-stu-id="70b41-804">This change is relevant for clients set in the Brazilia time zone or for meetings and appointments set in that time zone.</span></span><br><br><span data-ttu-id="70b41-805">Questa modifica consente a Outlook di ignorare determinate impostazioni del fuso orario usate da Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-805">This change allows Outlook to override certain time zone settings used by Outlook.</span></span> <span data-ttu-id="70b41-806">Per poter ignorare un fuso orario è necessario impostare una chiave del Registro di sistema per l'utente corrente.</span><span class="sxs-lookup"><span data-stu-id="70b41-806">In order to invoke a time zone override you must set a registry key for the current user.</span></span> <span data-ttu-id="70b41-807">Il nome della chiave del Registro di sistema deve corrispondere al nome interno del fuso orario.</span><span class="sxs-lookup"><span data-stu-id="70b41-807">The registry key name must match the internal name of the time zone.</span></span> <span data-ttu-id="70b41-808">Il valore indica l’anno della regola del fuso orario da usare al posto dell'anno effettivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-808">The value indicates the time zone rule's year to be used in place of the effective year.</span></span> <span data-ttu-id="70b41-809">Ad esempio, il seguente valore di override della chiave del Registro di sistema userà la regola del fuso orario di Brasilia per l'anno 2020 come regola effettiva.</span><span class="sxs-lookup"><span data-stu-id="70b41-809">For example, the following registry key override value will use the Brazilia time zone rule for the year 2020 as the effective rule.</span></span> <span data-ttu-id="70b41-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span><span class="sxs-lookup"><span data-stu-id="70b41-810">HKEY_CURRENT_USER\Software\Microsoft\Office\16.0\Outlook\TimeZoneOverride]"E.</span></span> <span data-ttu-id="70b41-811">South America Standard Time"=dword:000007e4.</span><span class="sxs-lookup"><span data-stu-id="70b41-811">South America Standard Time"=dword:000007e4.</span></span>

- <span data-ttu-id="70b41-812">Risolve un problema che causava la modifica imprevista del campo della sede nelle riunioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-812">Addresses an issue that caused users to see the location field in meetings change unexpectedly.</span></span>

- <span data-ttu-id="70b41-813">Risolve un problema che causava l'aggiornamento imprevisto del campo Sede nelle riunioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-813">Addresses an issue that caused the Location field in meetings to get updated unexpectedly.</span></span>

- <span data-ttu-id="70b41-814">Risolve un problema per cui la sede di una riunione veniva inaspettatamente aggiunta di nuovo alla riunione dopo averla cancellata.</span><span class="sxs-lookup"><span data-stu-id="70b41-814">Addresses an issue that caused the location of a meeting to get added back to the meeting unexpectedly after clearing it.</span></span>

- <span data-ttu-id="70b41-815">Risolve un problema per cui la virgola nel campo Sede della riunione cambiava in punto e virgola.</span><span class="sxs-lookup"><span data-stu-id="70b41-815">Addresses an issue that caused commas in the location field of a meeting to turn into semicolons.</span></span>

- <span data-ttu-id="70b41-816">Consente di partecipare a una riunione di Teams direttamente tramite il client nativo di Teams.</span><span class="sxs-lookup"><span data-stu-id="70b41-816">Enables joining a Teams meeting directly through the native Teams client.</span></span>

- <span data-ttu-id="70b41-817">Risolve un problema relativo all'aggiunta di allegati agli elementi del calendario per utenti con cassette postali sui server di Exchange 2010.</span><span class="sxs-lookup"><span data-stu-id="70b41-817">Addresses an issue that caused users with mailboxes on Exchange 2010 servers to experience issues when adding attachments to calendar items.</span></span>

- <span data-ttu-id="70b41-818">Risolve un problema relativo alla risposta a messaggi con firma digitale.</span><span class="sxs-lookup"><span data-stu-id="70b41-818">Addresses an issue that caused users to experience issues when replying to digitally signed messages.</span></span>

- <span data-ttu-id="70b41-819">Risolve un problema che impediva agli utenti di aprire alcune istanze di elementi ricorrenti del calendario.</span><span class="sxs-lookup"><span data-stu-id="70b41-819">Addresses an issue that caused users to be unable to open some instances of recurring calendar items.</span></span>

- <span data-ttu-id="70b41-820">Risolve un problema che causava l'espansione improvvisa dell'intestazione del gruppo in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="70b41-820">Addresses an issue that caused the Group header to expand unexpectedly in some scenarios.</span></span>

- <span data-ttu-id="70b41-821">Risolve un problema che causava il cambiamento inatteso della larghezza del riquadro delle cartelle.</span><span class="sxs-lookup"><span data-stu-id="70b41-821">Addresses an issue that caused the width of the folder pane to change unexpectedly.</span></span>

- <span data-ttu-id="70b41-822">Risolve un problema per cui Outlook non riusciva ad abilitare i Criteri predefiniti di prevenzione della perdita dei dati per gli utenti che avevano pagato il servizio nell’ambito del piano M365 Business Plus.</span><span class="sxs-lookup"><span data-stu-id="70b41-822">Addresses an issue where Outlook failed to enable Data Loss Protection policy tips people for users who had paid for the service who are on M365 Business Plus plans.</span></span>

- <span data-ttu-id="70b41-823">Risolve un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="70b41-823">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="70b41-824">Risolve un problema per cui si verificava un arresto anomalo quando si visualizzava lo stesso elemento in più finestre.</span><span class="sxs-lookup"><span data-stu-id="70b41-824">Addresses an issue that could result in a crash when viewing the same item in multiple windows.</span></span>

- <span data-ttu-id="70b41-825">Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'aggiornamento delle regole in Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-825">Addresses an issue that caused users to see the "The rules on this computer do not match the rules on Microsoft Exchange" message when updating their rules in Outlook.</span></span>

- <span data-ttu-id="70b41-826">Risolve un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="70b41-826">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="70b41-827">Risolve un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="70b41-827">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="70b41-828">Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="70b41-828">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="70b41-829">Risolve un problema per cui, in alcuni scenari, l'opzione per disabilitare l'evidenziazione degli elementi contrassegnati non veniva rispettata.</span><span class="sxs-lookup"><span data-stu-id="70b41-829">Addresses an issue that caused the option to disable flagged item highlighting to fail to be respected in some scenarios.</span></span>

- <span data-ttu-id="70b41-830">Risolve un problema che causava l'invio imprevisto di messaggi di posta elettronica quando gli utenti premevano il tasto “S” dopo aver chiuso il riquadro Verifica accessibilità.</span><span class="sxs-lookup"><span data-stu-id="70b41-830">Addresses an issue that caused users to see mails unexpectedly send when pressing the "S" key after closing the accessibility checker pane.</span></span>

- <span data-ttu-id="70b41-831">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="70b41-831">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="70b41-832">Risolve un problema che causava un arresto anomalo annullando la configurazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="70b41-832">Addresses an issue that caused users to experience a crash when canceling account setup.</span></span>

- <span data-ttu-id="70b41-833">Risolve un problema per cui Outlook sincronizzava in modo imprevisto tutta la posta elettronica anche quando il dispositivo di scorrimento di sincronizzazione era impostato su un valore inferiore.</span><span class="sxs-lookup"><span data-stu-id="70b41-833">Addresses an issue that caused Outlook to unexpectedly sync all mail even when the sync slider is set to a smaller setting.</span></span>

- <span data-ttu-id="70b41-834">Risolve un problema per cui gli utenti con il tema Nero visualizzavano l'elenco a discesa "Da" con il testo bianco su sfondo bianco.</span><span class="sxs-lookup"><span data-stu-id="70b41-834">Addresses an issue that caused users with Black Theme to see the "From" dropdown show white text on a white background.</span></span>

- <span data-ttu-id="70b41-835">Risolve un problema che causava un arresto anomalo durante la creazione del profilo.</span><span class="sxs-lookup"><span data-stu-id="70b41-835">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="70b41-836">Risolve un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante “OK” quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="70b41-836">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="70b41-837">Risolve un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante “OK” quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="70b41-837">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="70b41-838">Risolve un problema per cui le applicazioni di terze parti non riuscivano a inviare messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="70b41-838">Addresses an issue that caused third party applications to be unable to send email.</span></span>

- <span data-ttu-id="70b41-839">Risolve un problema che causava la scomparsa occasionale delle categorie dai messaggi di posta elettronica.</span><span class="sxs-lookup"><span data-stu-id="70b41-839">Addresses an issue that caused categories to occasionally disappear from email messages.</span></span>

- <span data-ttu-id="70b41-840">Risolve un problema che restituiva agli utenti di Outlook sui sistemi operativi del server l'errore: "Stato antivirus: non valido.</span><span class="sxs-lookup"><span data-stu-id="70b41-840">Addresses an issue that caused Outlook users on server operating systems to see the error, "Antivirus status: Invalid.</span></span> <span data-ttu-id="70b41-841">Questa versione di Windows supporta il rilevamento dei programmi antivirus, ma non è stato trovato alcun programma antivirus”, anche se l’antivirus è stato configurato in modo appropriato.</span><span class="sxs-lookup"><span data-stu-id="70b41-841">This version of Windows supports antivirus detection, but no antivirus was found" despite having anti virus properly configured.</span></span>

- <span data-ttu-id="70b41-842">Risolve un problema per cui i delegati vedevano gerarchie di cartelle diverse su computer diversi per le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="70b41-842">Addresses an issue that caused delegates to see different folder hierarchies on different machines for shared mailboxes.</span></span>

- <span data-ttu-id="70b41-843">Risolve un problema per cui i delegati ricevevano un messaggio di errore modificando un appuntamento del calendario esistente nel calendario di un responsabile.</span><span class="sxs-lookup"><span data-stu-id="70b41-843">Addresses an issue that caused delegates to receive an error when editing an existing calendar appointment on a manager's calendar.</span></span>

- <span data-ttu-id="70b41-844">Risolve un problema che impediva agli utenti con l'impostazione errata dell'emulazione del browser di completare la richiesta di autenticazione di Gmail.</span><span class="sxs-lookup"><span data-stu-id="70b41-844">Addresses an issue that caused users with the incorrect browser emulation setting when to be unable to complete the authentication prompt for Gmail.</span></span>

- <span data-ttu-id="70b41-845">Risolve un problema per cui l'opzione “Consenti inoltro” non era presente tra le opzioni di risposta in una riunione nel calendario condiviso, se la cartella di download condivisa NON era selezionata.</span><span class="sxs-lookup"><span data-stu-id="70b41-845">Addresses an issue that caused the " Allow Forwarding" option to be missing from shared calendar meeting "Response Options" when Download Shared folder was NOT checked.</span></span>

- <span data-ttu-id="70b41-846">Risolve un problema che causava un arresto anomalo quando si cercava di aprire file .msg e .oft dopo un aggiornamento di Windows.</span><span class="sxs-lookup"><span data-stu-id="70b41-846">Addresses an issue that caused users to experience a crash when trying to open .msg and .oft files after a Windows update.</span></span>

- <span data-ttu-id="70b41-847">Risolve un problema che causava un arresto anomalo occasionale quando veniva usato il pulsante X del mouse.</span><span class="sxs-lookup"><span data-stu-id="70b41-847">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="70b41-848">Risolve un problema che causava un arresto anomalo quando venivano selezionati alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-848">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="70b41-849">Risolve un problema che causava l'assenza del pulsante Salva nel cloud in Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="70b41-849">Addresses an issue that caused the Save to Cloud button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="70b41-850">Questa modifica ripristina la possibilità di visualizzare oggetti multilinea nell'intestazione del messaggio.</span><span class="sxs-lookup"><span data-stu-id="70b41-850">This change restores the ability to view multi-line subjects in the message header.</span></span>

- <span data-ttu-id="70b41-851">Risolve un problema che causava un arresto anomalo quando due componenti aggiuntivi aggiungevano un pulsante allo stesso gruppo della barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="70b41-851">Addresses an issue that caused users to experience a crash when two add-ins add a button to the same ribbon group.</span></span>

- <span data-ttu-id="70b41-852">Risolve un problema che causava la mancata aggiunta di collegamenti ai messaggi di posta elettronica con l'autorizzazione predefinita del tenant corretta quando questa era configurata su "chiunque".</span><span class="sxs-lookup"><span data-stu-id="70b41-852">Addresses an issue that caused links to fail to be added to emails with the correct tenant default permission when the tenant default permission is configured as "anyone".</span></span>

- <span data-ttu-id="70b41-853">Risolve un problema che impediva agli utenti di inviare messaggi di posta elettronica a una lista di distribuzione personale.</span><span class="sxs-lookup"><span data-stu-id="70b41-853">Addresses an issue that caused users to be unable to address emails to a Personal Distribution List.</span></span>

- <span data-ttu-id="70b41-854">Risolve un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-854">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="70b41-855">È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="70b41-855">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="70b41-856">È stato risolto un problema che poteva impedire il salvataggio di file in una posizione WebDAV.</span><span class="sxs-lookup"><span data-stu-id="70b41-856">We fixed an issue which could have prevented files from being saved to a WebDAV location.</span></span>

- <span data-ttu-id="70b41-857">Risolve un problema che impediva agli utenti di salvare gli allegati di OneDrive dall'esterno del tenant al computer locale selezionando l'opzione "Salva" nella finestra di dialogo relativa alla sicurezza.</span><span class="sxs-lookup"><span data-stu-id="70b41-857">Addresses an issue that caused users to be unable to save OneDrive attachments from outside their tenant to their local computer when selecting the "Save" option on the security dialog.</span></span>

- <span data-ttu-id="70b41-858">Risolve un problema per cui il corpo di un messaggio NDR passava da Unicode a ASCII dopo aver modificato l'oggetto.</span><span class="sxs-lookup"><span data-stu-id="70b41-858">Addresses an issue that caused the body of an NDR message to change from Unicode to ASCII after editing the subject.</span></span>

- <span data-ttu-id="70b41-859">Risolve un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-859">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="70b41-860">È stato risolto un problema per cui gli utenti vedevano i messaggi di posta elettronica inviati a un indirizzo che in alcuni casi non corrispondeva all'indirizzo SMTP visualizzato.</span><span class="sxs-lookup"><span data-stu-id="70b41-860">Addresses an issue that caused users to see emails sent to an address that did not match the displayed SMTP address in some circumstances.</span></span>

- <span data-ttu-id="70b41-861">Risolve un problema che causava l’errato allineamento della casella di ricerca in modalità dpi elevato.</span><span class="sxs-lookup"><span data-stu-id="70b41-861">Addresses an issue that caused the search box to be improperly aligned in high dpi mode.</span></span>

- <span data-ttu-id="70b41-862">Risolve un problema che causava il blocco di Outlook durante il recupero delle impostazioni del cloud.</span><span class="sxs-lookup"><span data-stu-id="70b41-862">Addresses an issue that caused users to experience hangs in Outlook when retrieving Cloud Settings.</span></span>

- <span data-ttu-id="70b41-863">Risolve un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-863">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="70b41-864">Risolve un problema per cui gli utenti visualizzavano arresti anomali occasionali in Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-864">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

- <span data-ttu-id="70b41-865">Risolve un problema che causava arresti anomali quando gli utenti rinominavano una firma.</span><span class="sxs-lookup"><span data-stu-id="70b41-865">Addresses an issue that caused users to experience crashes when renaming a signature.</span></span>

- <span data-ttu-id="70b41-866">Risolve un problema che causava un arresto anomalo durante la creazione del profilo.</span><span class="sxs-lookup"><span data-stu-id="70b41-866">Addresses an issue that caused users to experience a crash during profile creation.</span></span>

- <span data-ttu-id="70b41-867">Risolve un problema per cui gli utenti visualizzavano arresti anomali occasionali in Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-867">Addresses an issue that caused users to see occasional crashes in Outlook.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="70b41-868">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-868">PowerPoint</span></span>

- <span data-ttu-id="70b41-869">È stato risolto un problema che potrebbe aver causato un arresto anomalo durante l’utilizzo del menu di scelta rapida nei commenti PPT legacy.</span><span class="sxs-lookup"><span data-stu-id="70b41-869">Addressed an issue that may have caused a crash when using context menu in legacy PPT comments.</span></span>

- <span data-ttu-id="70b41-870">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="70b41-870">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="70b41-871">Risolve un problema relativo all'inoltro della messaggistica corretta per gli utenti che aprono una copia di un file con commenti migliorati.</span><span class="sxs-lookup"><span data-stu-id="70b41-871">Fixes an issue to relay correct messaging for users who open a copy of a file that has improved comments.</span></span>

### <a name="project"></a><span data-ttu-id="70b41-872">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-872">Project</span></span>

- <span data-ttu-id="70b41-873">È stato risolto un problema per cui le date delle attività di riepilogo non sempre venivano calcolate correttamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-873">Fixed an issue where summary task dates weren't always getting calculated correctly.</span></span>

- <span data-ttu-id="70b41-874">È stato risolto un problema per cui l'evento OnUndoOrRedo non veniva lanciato senza prima eseguire il metodo OpenUndoTransaction.</span><span class="sxs-lookup"><span data-stu-id="70b41-874">Fixed an issue where the OnUndoOrRedo event doesn't fire without first running the OpenUndoTransaction method.</span></span>

- <span data-ttu-id="70b41-875">È stato risolto un problema per cui l'evento ProjectBeforeTaskChange non rileva quando un'attività è stata attivata o disattivata tramite il pulsante Disattiva.</span><span class="sxs-lookup"><span data-stu-id="70b41-875">Fixed an issue where the ProjectBeforeTaskChange event does not detect when a task has been inactivated/activated via the Inactivate button.</span></span>

- <span data-ttu-id="70b41-876">È stato risolto un problema per cui Project può arrestarsi in modo anomalo quando si salvano progetti creati con versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-876">Fixed an issue where Project may crash when saving projects created with older versions of Project.</span></span>

- <span data-ttu-id="70b41-877">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura</span><span class="sxs-lookup"><span data-stu-id="70b41-877">Identified an issue where users could get several messages when opening a read-only project</span></span>

- <span data-ttu-id="70b41-878">È stato risolto un problema per cui il 100% delle attività di tipo a durata fissa poteva avere il valore di percentuale di completamento calcolato erroneamente a meno del 100%.</span><span class="sxs-lookup"><span data-stu-id="70b41-878">Fixed an issue where 100% tasks of type fixed duration may wrongly have their % complete calculated at less than 100% complete.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-879">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-879">Word</span></span>

- <span data-ttu-id="70b41-880">Risolve un problema che causava un arresto anomalo occasionale quando veniva usato il pulsante X del mouse.</span><span class="sxs-lookup"><span data-stu-id="70b41-880">Addresses an issue that caused users to occasionally experience a crash when using the X button on the mouse.</span></span>

- <span data-ttu-id="70b41-881">È stato risolto un problema per cui l'allineamento delle parole in un documento veniva modificato se si provava a modificare il documento dopo la stampa con Quick Print.</span><span class="sxs-lookup"><span data-stu-id="70b41-881">We fixed an issue which alignment of word in document gets scrambled when tried to edit after printing using Quick Print.</span></span>

- <span data-ttu-id="70b41-882">È stato risolto un problema relativo all'adattamento del testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="70b41-882">We fixed an issue with fit text in a table.</span></span>

- <span data-ttu-id="70b41-883">È stato risolto un problema per cui le righe orizzontali inserite non sono più brevi e centrate.</span><span class="sxs-lookup"><span data-stu-id="70b41-883">We fixed an issue where inserting horizontal lines are not shorter and centered.</span></span>

- <span data-ttu-id="70b41-884">Gestione blocchi predefiniti potrebbe visualizzare un avviso non valido: "Sono stati modificati gli stili, i blocchi predefiniti".</span><span class="sxs-lookup"><span data-stu-id="70b41-884">Building blocks organizer may display an invalid alert: "You have modified styles, building blocks".</span></span>

- <span data-ttu-id="70b41-885">È stato risolto un problema relativo alla creazione condivisa abilitando il criterio FileBlick\Word2007Files.</span><span class="sxs-lookup"><span data-stu-id="70b41-885">We fixed an issue in coautthoring if we enable policy FileBlick\Word2007Files.</span></span>

- <span data-ttu-id="70b41-886">È stato risolto un problema per cui le parti rapide di Word non funzionavano aggiungendo un campo di ricerca rinominato.</span><span class="sxs-lookup"><span data-stu-id="70b41-886">We fixed an issue which Word QuickPart doesn't work when adding lookup field that has been renamed.</span></span>

- <span data-ttu-id="70b41-887">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="70b41-887">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="70b41-888">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="70b41-888">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="70b41-889">Questo aggiornamento consente di risolvere un problema di Microsoft Word per il quale un testo più lungo di 255 caratteri inserito durante l'applicazione di un'etichetta di riservatezza non può essere identificato e rimosso in seguito modificando o rimuovendo l'etichetta se il criterio di etichetta applica un'intestazione, un piè di pagina o una filigrana.</span><span class="sxs-lookup"><span data-stu-id="70b41-889">This update fixes a problem in Microsoft Word where text longer than 255 characters inserted while applying a sensitivity label could not subsequently be identified and removed by changing or removing the label if the label policy applied a header or footer or watermark.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-890">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-890">Office Suite</span></span>

- <span data-ttu-id="70b41-891">È stato risolto un problema per cui gli utenti riscontravano un utilizzo eccessivo della rete e della CPU durante la creazione condivisa in file di PowerPoint di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-891">Fixed an issue where users can experience excessive network and CPU usage while coauthoring on large PowerPoint files.</span></span>

- <span data-ttu-id="70b41-892">Si tratta di una soluzione per il blocco della rete da parte dell'app di Project quando il file viene memorizzato nella cache del client.</span><span class="sxs-lookup"><span data-stu-id="70b41-892">This is a fix to address that Project app should not block network when the file is cached in the client.</span></span>


- <span data-ttu-id="70b41-893">Il problema è stato risolto aggiornando i nomi dei canali nella visualizzazione backstage ai nuovi nomi dei canali nel fork 2020 gennaio.</span><span class="sxs-lookup"><span data-stu-id="70b41-893">We resolved this issue by updating the channel names in the backstage to the new channel names in the January 2020 Fork.</span></span>

- <span data-ttu-id="70b41-894">Il problema è stato risolto e in futuro, se un dispositivo viene gestito da criteri, non chiamerà l'API DMS Audience.</span><span class="sxs-lookup"><span data-stu-id="70b41-894">We have fixed this issue and going forward, if a device is policy-managed, it will not call the DMS Audience API.</span></span>

- <span data-ttu-id="70b41-895">È stato risolto il problema relativo alla rimozione incompleta nell'ambito dell'aggiunta e della rimozione di app in una singola operazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-895">We have resolved the issue where there is an incomplete removal when adding and removing apps in a single transaction.</span></span>

- <span data-ttu-id="70b41-896">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-896">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="70b41-897">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="70b41-897">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="70b41-898">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-898">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="70b41-899">È stata rilasciata una nuova AppV51 per risolvere una regressione nell’AppV51 precedente. </span><span class="sxs-lookup"><span data-stu-id="70b41-899">We backported a new AppV51 drop to fix a regression in previous AppV51.</span></span>

- <span data-ttu-id="70b41-900">Il problema è stato risolto quando un'operazione interna genera un'eccezione in caso di errore anziché registrare e continuare.</span><span class="sxs-lookup"><span data-stu-id="70b41-900">We have resolved the issue where an internal operation was throwing an exception on failure instead of logging and continuing on.</span></span> <span data-ttu-id="70b41-901">Gli utenti interessati non riscontreranno più il blocco della ricezione degli aggiornamenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-901">The affected users will not be blocked from receiving updates anymore.</span></span>

- <span data-ttu-id="70b41-902">Il team ha aggiunto il supporto client per la creazione di report di telemetria sui domini CDN di Office nell'anteprima aziendale semestrale.</span><span class="sxs-lookup"><span data-stu-id="70b41-902">Our team has added client support for reporting telemetry on the Office CDN domains in Semi-Annual Enterprise Preview.</span></span>

- <span data-ttu-id="70b41-903">Questa modifica risolve i problemi con gli adattatori grafici che sfruttano la GPU integrata Intel.</span><span class="sxs-lookup"><span data-stu-id="70b41-903">This change addresses reported problems with graphics adaptors that leverage the Intel Integrated GPU.</span></span>

- <span data-ttu-id="70b41-904">Ciò assicura che la struttura disegnata funzioni correttamente nella barra multifunzione.</span><span class="sxs-lookup"><span data-stu-id="70b41-904">This change ensures Sketched outline works properly in the ribbon.</span></span>

- <span data-ttu-id="70b41-905">È stato risolto un problema che si verificava durante l'apertura di file da posizioni locali con alcune configurazioni proxy specifiche.</span><span class="sxs-lookup"><span data-stu-id="70b41-905">Fixed an issue while opening files from on-prem locations with some specific proxy configurations.</span></span>

- <span data-ttu-id="70b41-906">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-906">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="70b41-907">È stato risolto un problema che causa l'arresto anomalo durante le sessioni di handoff di Office ed è stata migliorata l'affidabilità dell'esperienza utente.</span><span class="sxs-lookup"><span data-stu-id="70b41-907">Fixed an issue that eliminates crashes during Office handoff sessions and improved reliability in the user experience.</span></span>

- <span data-ttu-id="70b41-908">Questo bug aggiorna l'endpoint url di Enhanced Configuration Service (ECS).</span><span class="sxs-lookup"><span data-stu-id="70b41-908">This bug updates the enhanced configuration service (ECS) url endpoint.</span></span> <span data-ttu-id="70b41-909">Richiamare questo nuovo endpoint ha un tasso di successo maggiore per recuperare dati dall'ECS.</span><span class="sxs-lookup"><span data-stu-id="70b41-909">Calling this newer endpoint has a higher success rate for fetching from ECS.</span></span>

- <span data-ttu-id="70b41-910">Questo aggiornamento consente di risolvere un problema per cui Microsoft Outlook non visualizza l'etichetta di riservatezza corrente durante la visualizzazione o la creazione di messaggi.</span><span class="sxs-lookup"><span data-stu-id="70b41-910">This update fixes an issue with Microsoft Outlook not displaying the current sensitivity label when viewing or composing messages.</span></span>

- <span data-ttu-id="70b41-911">È stato risolto un problema per cui quando più documenti venivano aperti in Word/Excel/PowerPoint dalla stessa raccolta di SharePoint, solo il primo veniva analizzato per la conformità dei criteri.</span><span class="sxs-lookup"><span data-stu-id="70b41-911">Fixes an issue when multiple documents are open in Word/Excel/PowerPoint from the same SharePoint library, only the first document opened will be scanned for Policy compliance.</span></span>

- <span data-ttu-id="70b41-912">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="70b41-912">To protect Office customers’ security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="70b41-913">L'host di Office si chiudeva in modo anomalo in Windows quando veniva attivato un componente aggiuntivo mentre la chiave del registro di sistema  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth era impostata su zero.</span><span class="sxs-lookup"><span data-stu-id="70b41-913">The office host was closing in windows, when an add-in is being activated while the registry key  HKEY_CURRENT_USER\Software\Microsoft\Internet Explorer\Main\TabProcGrowth is set to zero.</span></span> <span data-ttu-id="70b41-914">La modifica può risolvere il problema.</span><span class="sxs-lookup"><span data-stu-id="70b41-914">This change would fix this issue.</span></span>

- <span data-ttu-id="70b41-915">È stato risolto il problema per cui Access e Publisher potevano non venire avviati correttamente a seconda delle lingue installate.</span><span class="sxs-lookup"><span data-stu-id="70b41-915">Resolved the issue where Access and Publisher might not boot correctly depending on which languages were installed.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)





[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-july-14"></a><span data-ttu-id="70b41-918">Versione 1908: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="70b41-918">Version 1908: July 14</span></span>
<span data-ttu-id="70b41-919">*Versione 1908 (Build 11929.20904)*</span><span class="sxs-lookup"><span data-stu-id="70b41-919">*Version 1908 (Build 11929.20904)*</span></span>

<span data-ttu-id="70b41-920">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-920">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-922">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-922">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="70b41-923">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-923">Access</span></span>

- <span data-ttu-id="70b41-924">Questo aggiornamento risolve un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.</span><span class="sxs-lookup"><span data-stu-id="70b41-924">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="70b41-925">Questo aggiornamento risolve un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.</span><span class="sxs-lookup"><span data-stu-id="70b41-925">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="70b41-926">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo “Query danneggiata” quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="70b41-926">This update fixes an issue in Microsoft Access that may cause the error "Query is Corrupt" when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="70b41-927">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-927">Excel</span></span>

- <span data-ttu-id="70b41-928">Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt-G.</span><span class="sxs-lookup"><span data-stu-id="70b41-928">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="70b41-929">È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.</span><span class="sxs-lookup"><span data-stu-id="70b41-929">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="70b41-930">È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-930">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="70b41-931">Questo aggiornamento risolve un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-931">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="70b41-932">Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal cubo.</span><span class="sxs-lookup"><span data-stu-id="70b41-932">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="70b41-933">Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.</span><span class="sxs-lookup"><span data-stu-id="70b41-933">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="70b41-934">È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie</span><span class="sxs-lookup"><span data-stu-id="70b41-934">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection</span></span>

- <span data-ttu-id="70b41-935">Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.</span><span class="sxs-lookup"><span data-stu-id="70b41-935">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="70b41-936">È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.</span><span class="sxs-lookup"><span data-stu-id="70b41-936">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="70b41-937">È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-937">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="70b41-938">È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.</span><span class="sxs-lookup"><span data-stu-id="70b41-938">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="70b41-939">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="70b41-939">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="70b41-940">È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-940">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="70b41-941">È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.</span><span class="sxs-lookup"><span data-stu-id="70b41-941">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="70b41-942">È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-942">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="70b41-943">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="70b41-943">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="70b41-944">È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.</span><span class="sxs-lookup"><span data-stu-id="70b41-944">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="70b41-945">È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.</span><span class="sxs-lookup"><span data-stu-id="70b41-945">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>

- <span data-ttu-id="70b41-946">È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="70b41-946">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="70b41-947">È stato risolto un problema in VBA per cui la scrittura di valori in un intervallo era più lenta del previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-947">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="70b41-948">Risolve un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambia in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="70b41-948">Addresses an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="70b41-949">Per le cartelle di lavoro salvate con una firma digitale in Excel 2016 la firma poteva essere invalidata con l’apertura nell’attuale versione di Excel.</span><span class="sxs-lookup"><span data-stu-id="70b41-949">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>

- <span data-ttu-id="70b41-950">È stato risolto un problema che causava il rallentamento delle prestazioni quando si eliminavano colonne contenenti celle unite.</span><span class="sxs-lookup"><span data-stu-id="70b41-950">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="70b41-951">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-951">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

- <span data-ttu-id="70b41-952">Quando si copiavano dati filtrati in base al colore in una colonna di larghezza differente, i valori non venivano incollati.</span><span class="sxs-lookup"><span data-stu-id="70b41-952">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

- <span data-ttu-id="70b41-953">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="70b41-953">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="70b41-954">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-954">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="70b41-955">È stato risolto un problema per cui il foglio di lavoro veniva nascosto nel momento in cui si faceva clic su un collegamento ipertestuale con segnalibro all’interno dello stesso foglio di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-955">Fixed an issue where clicking a bookmarked hyperlink within the same workbook would cause the workbook to be hidden.</span></span>

- <span data-ttu-id="70b41-956">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "Cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="70b41-956">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

- <span data-ttu-id="70b41-957">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><span class="sxs-lookup"><span data-stu-id="70b41-957">Text to Column functionality may fail for some locales.</span></span>

- <span data-ttu-id="70b41-958">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="70b41-958">Users may encounter an error when accessing a hidden named range.</span></span>

- <span data-ttu-id="70b41-959">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-959">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="70b41-960">È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.</span><span class="sxs-lookup"><span data-stu-id="70b41-960">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>

- <span data-ttu-id="70b41-961">Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-961">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="70b41-962">Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="70b41-962">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="70b41-963">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="70b41-963">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="70b41-964">È stato risolto un problema per cui la funzione Cerca restituiva un errore.</span><span class="sxs-lookup"><span data-stu-id="70b41-964">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="70b41-965">È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.</span><span class="sxs-lookup"><span data-stu-id="70b41-965">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="70b41-966">È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.</span><span class="sxs-lookup"><span data-stu-id="70b41-966">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>

- <span data-ttu-id="70b41-967">Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.</span><span class="sxs-lookup"><span data-stu-id="70b41-967">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="70b41-968">È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.</span><span class="sxs-lookup"><span data-stu-id="70b41-968">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="70b41-969">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="70b41-969">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="70b41-970">Sono state notevolmente migliorate le prestazioni del filtro per colore.</span><span class="sxs-lookup"><span data-stu-id="70b41-970">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="70b41-971">È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-971">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="70b41-972">Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-972">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="70b41-973">È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.</span><span class="sxs-lookup"><span data-stu-id="70b41-973">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="70b41-974">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="70b41-974">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="70b41-975">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-975">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-976">Questo aggiornamento corregge un errore in cui il caricamento dei documenti di Office in OneDrive for Business potrebbe avere esito negativo con il messaggio "Caricamento non riuscito".</span><span class="sxs-lookup"><span data-stu-id="70b41-976">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="70b41-977">È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.</span><span class="sxs-lookup"><span data-stu-id="70b41-977">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span> 

### <a name="onenote"></a><span data-ttu-id="70b41-978">OneNote</span><span class="sxs-lookup"><span data-stu-id="70b41-978">OneNote</span></span>

- <span data-ttu-id="70b41-979">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="70b41-979">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-980">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-980">Outlook</span></span>

- <span data-ttu-id="70b41-981">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-981">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-982">È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-982">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="70b41-983">Risolve un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.</span><span class="sxs-lookup"><span data-stu-id="70b41-983">Addresses an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="70b41-984">Risolve un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="70b41-984">Addresses an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="70b41-985">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="70b41-985">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="70b41-986">Risolve un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-986">Addresses an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="70b41-987">Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="70b41-987">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="70b41-988">Risolve un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.</span><span class="sxs-lookup"><span data-stu-id="70b41-988">Addresses an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="70b41-989">Risolve un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="70b41-989">Addresses an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="70b41-990">Risolve un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="70b41-990">Addresses an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="70b41-991">Risolve un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="70b41-991">Addresses an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="70b41-992">Risolve un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="70b41-992">Addresses an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="70b41-993">Risolve un problema che causava la visualizzazione del messaggio “Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange” all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="70b41-993">Addresses an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="70b41-994">Risolve un problema che causava un arresto anomalo di Outlook durante l'interazione con determinati collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="70b41-994">Addresses an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="70b41-995">Risolve un problema che causava ambiguità per i responsabili circa il fatto che un delegato avesse già risposto o meno a una determinata convocazione di riunione.</span><span class="sxs-lookup"><span data-stu-id="70b41-995">Addresses an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="70b41-996">Risolve un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-996">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="70b41-997">Risolve un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante “OK” quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="70b41-997">Addresses an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="70b41-998">Questa modifica consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN.</span><span class="sxs-lookup"><span data-stu-id="70b41-998">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="70b41-999">Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.</span><span class="sxs-lookup"><span data-stu-id="70b41-999">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="70b41-1000">Risolve un problema che causava il malfunzionamento della ricerca in Gruppi moderni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1000">Addresses an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="70b41-1001">Risolve un problema che bloccava gli utenti di Outlook nello stato "Password necessaria" in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="70b41-1001">Addresses an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="70b41-1002">Risolve un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1002">Addresses an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="70b41-1003">Risolve un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1003">Addresses an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="70b41-1004">Risolve un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1004">Addresses an issue that caused users to experience a hang at the "Loading Profile" screen when Outlook is starting up.</span></span>

- <span data-ttu-id="70b41-1005">Risolve un problema che causava un arresto anomalo quando venivano selezionati alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-1005">Addresses an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="70b41-1006">Risolve un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="70b41-1006">Addresses an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="70b41-1007">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1007">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="70b41-1008">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1008">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="70b41-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = default 1 = verrà mostrato solo il NomeCriterio nel testo dei criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1009">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration 0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

- <span data-ttu-id="70b41-1010">Risolve un problema che causava un arresto anomalo durante la chiusura di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1010">Addresses an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="70b41-1011">Risolve un problema che causava la visualizzazione di un elenco sale vuoto in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="70b41-1011">Addresses an issue that caused customers to see an empty room list in some scenarios.</span></span>

- <span data-ttu-id="70b41-1012">Risolve un problema che causava arresti anomali intermittenti cambiando visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1012">Addresses an issue that caused users to see intermittent crashes when changing views.</span></span>

- <span data-ttu-id="70b41-1013">È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.</span><span class="sxs-lookup"><span data-stu-id="70b41-1013">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>

- <span data-ttu-id="70b41-1014">Risolve un problema che causa l'arresto anomalo quando si visualizzano più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="70b41-1014">Addresses an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="70b41-1015">Qui è disponibile il singolo [articolo della Knowledge Base in cui è stato documentato per le versioni precedenti](https://support.microsoft.com/it-IT/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen).</span><span class="sxs-lookup"><span data-stu-id="70b41-1015">Here's the individual [KB where this was documented for previous versions](https://support.microsoft.com/it-IT/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen)</span></span>

- <span data-ttu-id="70b41-1016">Risolve un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="70b41-1016">Corrects an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="70b41-1017">Risolve un problema che causava la mancata visualizzazione di Suggerimenti per i criteri usando un mittente alternativo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1017">Addresses an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="70b41-1018">Risolve un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.</span><span class="sxs-lookup"><span data-stu-id="70b41-1018">Addresses an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="70b41-1019">È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.</span><span class="sxs-lookup"><span data-stu-id="70b41-1019">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="70b41-1020">Risolve un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo "Conversazione non effettuata".</span><span class="sxs-lookup"><span data-stu-id="70b41-1020">Addresses an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="70b41-1021">Risolve un problema per cui alcuni utenti visualizzavano cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="70b41-1021">Addresses an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="70b41-1022">Risolve un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1022">Addresses an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

- <span data-ttu-id="70b41-1023">Risolve un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1023">Addresses an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="70b41-1024">Risolve un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1024">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="70b41-1025">Risolve un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1025">Addresses an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="70b41-1026">Risolve un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1026">Addresses an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="70b41-1027">Risolve un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-1027">Addresses an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="70b41-1028">Risolve un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1028">Addresses an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="70b41-1029">Risolve un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1029">Addresses an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="70b41-1030">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1030">PowerPoint</span></span>

- <span data-ttu-id="70b41-1031">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1031">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-1032">Questa modifica ripristina il nome accessibile per i controlli video di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1032">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="70b41-1033">È stato risolto un problema che impediva l'avvio di alcune animazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1033">We fixed an issue which could prevent some animations from starting</span></span>

- <span data-ttu-id="70b41-1034">È stato risolto un problema che causava la creazione di schemi duplicati quando si copiava una diapositiva da una presentazione a un'altra.</span><span class="sxs-lookup"><span data-stu-id="70b41-1034">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span><br>

- <span data-ttu-id="70b41-1035">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1035">Improved a copy-paste scenario: Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>

- <span data-ttu-id="70b41-1036">È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.</span><span class="sxs-lookup"><span data-stu-id="70b41-1036">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

- <span data-ttu-id="70b41-1037">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1037">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

- <span data-ttu-id="70b41-1038">È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1038">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="70b41-1039">Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti poteva causare l'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1039">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="70b41-1040">È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1040">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="70b41-1041">È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1041">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>

- <span data-ttu-id="70b41-1042">È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1042">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

- <span data-ttu-id="70b41-1043">È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.</span><span class="sxs-lookup"><span data-stu-id="70b41-1043">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="70b41-1044">Impedisce un errore in PowerPoint quando si prova a presentare online.</span><span class="sxs-lookup"><span data-stu-id="70b41-1044">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

### <a name="project"></a><span data-ttu-id="70b41-1045">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-1045">Project</span></span>

- <span data-ttu-id="70b41-1046">È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1046">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="70b41-1047">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="70b41-1047">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="70b41-1048">Il comando Livella tutte non risolve correttamente una sovrassegnazione della risorsa.</span><span class="sxs-lookup"><span data-stu-id="70b41-1048">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="70b41-1049">In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1049">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

- <span data-ttu-id="70b41-1050">È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.</span><span class="sxs-lookup"><span data-stu-id="70b41-1050">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="skype"></a><span data-ttu-id="70b41-1051">Skype</span><span class="sxs-lookup"><span data-stu-id="70b41-1051">Skype</span></span>

- <span data-ttu-id="70b41-1052">È stato risolto un problema relativo al nome titolo per la conversazione su schede mentre erano in corso più conversazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1052">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="visio"></a><span data-ttu-id="70b41-1053">Visio</span><span class="sxs-lookup"><span data-stu-id="70b41-1053">Visio</span></span>

- <span data-ttu-id="70b41-1054">L'esportazione in SVG da Visio non funzionava per numerose forme.</span><span class="sxs-lookup"><span data-stu-id="70b41-1054">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-1055">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1055">Word</span></span>

- <span data-ttu-id="70b41-1056">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1056">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-1057">È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet</span><span class="sxs-lookup"><span data-stu-id="70b41-1057">We fixed an issue which could have caused scaling issues when printing to Deskjet printers</span></span>

- <span data-ttu-id="70b41-1058">È stato risolto un problema relativo all’adattamento del testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="70b41-1058">We fixed an issue in Fit Text in Table.</span></span>

- <span data-ttu-id="70b41-1059">È stato risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.</span><span class="sxs-lookup"><span data-stu-id="70b41-1059">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="70b41-1060">È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="70b41-1060">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>

- <span data-ttu-id="70b41-1061">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="70b41-1061">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="70b41-1062">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1062">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

- <span data-ttu-id="70b41-1063">Risolve diversi problemi che causavano il blocco dell'app durante la chiusura.</span><span class="sxs-lookup"><span data-stu-id="70b41-1063">Fixes various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="70b41-1064">Sono stati risolti anche alcuni arresti anomali correlati ai componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1064">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-1065">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1065">Office Suite</span></span>

- <span data-ttu-id="70b41-1066">Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1066">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="70b41-1067">È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-1067">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="70b41-1068">È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1068">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="70b41-1069">Si tratta di una correzione per un problema che causava un arresto anomalo all'apertura di un file.</span><span class="sxs-lookup"><span data-stu-id="70b41-1069">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="70b41-1070">In alcuni casi, un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica, comportando una perdita di dati.</span><span class="sxs-lookup"><span data-stu-id="70b41-1070">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="70b41-1071">È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1071">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="70b41-1072">Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="70b41-1072">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="70b41-1073">Risolve un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1073">Fixes a crash in Word by moving away from a deprecated API.</span></span>

- <span data-ttu-id="70b41-1074">È in corso la risoluzione di un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1074">Fixing an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

- <span data-ttu-id="70b41-1075">È stato risolto un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1075">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="70b41-1076">È stato risolto un bug per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.</span><span class="sxs-lookup"><span data-stu-id="70b41-1076">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="70b41-1077">Migliora l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.</span><span class="sxs-lookup"><span data-stu-id="70b41-1077">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="70b41-1078">I nomi dei canali per i fork gennaio e luglio 2019 sono stati aggiornati ai nuovi nomi di canale.</span><span class="sxs-lookup"><span data-stu-id="70b41-1078">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="70b41-1079">Risolve un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1079">Corrects an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="70b41-1080">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1080">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="70b41-1081">In alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1081">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="70b41-1082">Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-1082">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="70b41-1083">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="70b41-1083">Resolves an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="70b41-1084">Risolve un problema per cui, in alcuni casi, un aggiornamento non veniva applicato se l'utente non era un amministratore e non era disponibile la connettività di rete per l'account di sistema.</span><span class="sxs-lookup"><span data-stu-id="70b41-1084">Resolves an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="70b41-1085">È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1085">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="70b41-1086">In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.</span><span class="sxs-lookup"><span data-stu-id="70b41-1086">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="70b41-1087">È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1087">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="70b41-1088">Risolvere problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1088">Address issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="70b41-1089">Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1089">This change addresses correctly rendering images after opening a corrupted file.</span></span>

- <span data-ttu-id="70b41-1090">Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span><span class="sxs-lookup"><span data-stu-id="70b41-1090">This change addresses slow rendering of some scatter charts with markers.</span></span>

- <span data-ttu-id="70b41-1091">È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo</span><span class="sxs-lookup"><span data-stu-id="70b41-1091">We fixed an issue where large tree views could result in a crash</span></span>

- <span data-ttu-id="70b41-1092">Questo aggiornamento risolve un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati al caricamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1092">This update fixes an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

- <span data-ttu-id="70b41-1093">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="70b41-1093">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>

- <span data-ttu-id="70b41-1094">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="70b41-1094">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-july-14"></a><span data-ttu-id="70b41-1096">Versione 1902: 14 luglio</span><span class="sxs-lookup"><span data-stu-id="70b41-1096">Version 1902: July 14</span></span>
<span data-ttu-id="70b41-1097">*Versione 1902 (Build 11328.20624)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1097">*Version 1902 (Build 11328.20624)*</span></span>

<span data-ttu-id="70b41-1098">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1098">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

## <a name="version-1908-june-09"></a><span data-ttu-id="70b41-1099">Versione 1908: 09 giugno</span><span class="sxs-lookup"><span data-stu-id="70b41-1099">Version 1908: June 09</span></span>
<span data-ttu-id="70b41-1100">*Versione 1908 (Build 11929.20838)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1100">*Version 1908 (Build 11929.20838)*</span></span>

<span data-ttu-id="70b41-1101">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1101">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1103">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1103">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1104">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1104">Excel</span></span>

- <span data-ttu-id="70b41-1105">È stato risolto un problema per cui Excel smetteva di funzionare dopo avere premuto i tasti CTRL+MAIUSC+Freccia per scorrere, quando la finestra di Excel era condivisa attraverso Teams.</span><span class="sxs-lookup"><span data-stu-id="70b41-1105">Fixed an issue where Excel could become unresponsive after using Ctrl+Shift+Arrow keys to scroll when the Excel window is shared through Teams.</span></span>

- <span data-ttu-id="70b41-1106">È stato risolto un problema relativo al ridimensionamento delle caselle di controllo nei controlli modulo al momento della stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-1106">Fixed a problem with the scaling of checkboxes in form controls when printed.</span></span>

- <span data-ttu-id="70b41-1107">Possibile arresto anomalo durante il tentativo di elencare le modifiche in un nuovo foglio di una cartella di lavoro usando la modalità "cartella di lavoro condivisa" legacy.</span><span class="sxs-lookup"><span data-stu-id="70b41-1107">A crash could occur when trying to list changes on a new sheet for a workbook using legacy "Shared Workbook" mode.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-1108">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1108">Outlook</span></span>

- <span data-ttu-id="70b41-1109">È stato risolto un problema che causava il troncamento del corpo del messaggio durante l'inoltro di messaggi HTML di grandi dimensioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1109">Addressed an issue that caused users to see message body truncation when forwarding large HTML messages.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-1110">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1110">Office Suite</span></span>

- <span data-ttu-id="70b41-1111">I nomi dei canali sono stati aggiornati per i fork gennaio e luglio 2019 ai nuovi nomi di canale.</span><span class="sxs-lookup"><span data-stu-id="70b41-1111">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-june-09"></a><span data-ttu-id="70b41-1113">Versione 1902: 09 giugno</span><span class="sxs-lookup"><span data-stu-id="70b41-1113">Version 1902: June 09</span></span>
<span data-ttu-id="70b41-1114">*Versione 1902 (Build 11328.20602)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1114">*Version 1902 (Build 11328.20602)*</span></span>

<span data-ttu-id="70b41-1115">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1115">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1117">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1117">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="70b41-1118">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1118">Office Suite</span></span>

- <span data-ttu-id="70b41-1119">I nomi dei canali sono stati aggiornati per i fork gennaio e luglio 2019 ai nuovi nomi di canale.</span><span class="sxs-lookup"><span data-stu-id="70b41-1119">We have updated the channel names for the January and July 2019 forks to the new channel names.</span></span>

- <span data-ttu-id="70b41-1120">Sono stati rimossi riferimenti obsoleti dai file di base che stavano interrompendo la build C2R.</span><span class="sxs-lookup"><span data-stu-id="70b41-1120">We removed obsolete references from the baseline files that were breaking the C2R Build.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-may-12"></a><span data-ttu-id="70b41-1122">Versione 1908: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="70b41-1122">Version 1908: May 12</span></span>
<span data-ttu-id="70b41-1123">*Versione 1908 (Build 11929.20776)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1123">*Version 1908 (Build 11929.20776)*</span></span>

<span data-ttu-id="70b41-1124">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1124">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1126">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1126">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1127">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1127">Excel</span></span>

- <span data-ttu-id="70b41-1128">Quando si copiavano dati filtrati in base al colore in una colonna di larghezza differente, i valori non venivano incollati.</span><span class="sxs-lookup"><span data-stu-id="70b41-1128">When copying data filtered by color to a column with a different width, the values would not be pasted.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-1129">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1129">Outlook</span></span>

- <span data-ttu-id="70b41-1130">È stato risolto un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento recente di Windows.</span><span class="sxs-lookup"><span data-stu-id="70b41-1130">Addressed an issue that caused users to experience a crash when opening msg and .oft files after applying a recent Windows update.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-1131">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1131">Word</span></span>

- <span data-ttu-id="70b41-1132">È stato risolto un problema che si verificava unendo due documenti in uno.</span><span class="sxs-lookup"><span data-stu-id="70b41-1132">We fixed an issue when merging 2 documents into one document.</span></span>

- <span data-ttu-id="70b41-1133">È stato risolto un problema con la funzionalità Confronta per i documenti protetti per la modifica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1133">Fixed an issue with Compare feature for documents that were protected for editing.</span></span>

[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-1902-may-12"></a><span data-ttu-id="70b41-1135">Versione 1902: 12 maggio</span><span class="sxs-lookup"><span data-stu-id="70b41-1135">Version 1902: May 12</span></span>
<span data-ttu-id="70b41-1136">*Versione 1902 (Build 11328.20586)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1136">*Version 1902 (Build 11328.20586)*</span></span>

<span data-ttu-id="70b41-1137">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1137">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1139">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1139">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="70b41-1140">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1140">Outlook</span></span>

- <span data-ttu-id="70b41-1141">È stato risolto un problema che causava un arresto anomalo durante l'apertura di file .msg e .oft dopo un aggiornamento di Windows recente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1141">Addressed an issue that caused users to experience a crash when opening .msg and .oft files after applying a recent Windows update.</span></span>

- <span data-ttu-id="70b41-1142">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1142">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="70b41-1143">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1143">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="70b41-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="70b41-1144">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="70b41-1145">0 = Predefinito.</span><span class="sxs-lookup"><span data-stu-id="70b41-1145">0 = Default.</span></span>  <span data-ttu-id="70b41-1146">1 = Verrà visualizzato solo il NomeCriterio nel testo dei criteri di conservazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1146">1 = we will only show the PolicyName for Retention policy text.</span></span>


[//]: # (NON RIMUOVERE FINE DEL CONTENUTO DEI BUG)

## <a name="version-1908-may-04"></a><span data-ttu-id="70b41-1148">Versione 1908: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="70b41-1148">Version 1908: May 04</span></span>
<span data-ttu-id="70b41-1149">*Versione 1908 (build 11929.20752)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1149">*Version 1908 (Build 11929.20752)*</span></span>

<span data-ttu-id="70b41-1150">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1150">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1151">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1151">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="70b41-1152">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1152">Outlook</span></span>

- <span data-ttu-id="70b41-1153">È stato risolto un problema che causava un arresto anomalo selezionando alcuni risultati della ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-1153">Addressed an issue that caused users to experience a crash when selecting certain search results.</span></span>

- <span data-ttu-id="70b41-1154">È stato risolto un problema che causava l'assenza del pulsante "Salva nel cloud" da Strumenti allegati.</span><span class="sxs-lookup"><span data-stu-id="70b41-1154">Addressed an issue that caused the "Save to Cloud" button to be missing from Attachment Tools.</span></span>

- <span data-ttu-id="70b41-1155">Per impostazione predefinita, le etichette dei criteri di conservazione visualizzano il periodo di conservazione tra parentesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1155">By default, retention policy labels display the retention time period in parenthesis.</span></span> <span data-ttu-id="70b41-1156">Questa operazione fornisce una chiave del registro di sistema che consente agli amministratori di specificare che solo il nome del criterio deve essere visualizzato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1156">This provides a registry key to allow administrators to specify that only the policy name should be displayed.</span></span> <span data-ttu-id="70b41-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span><span class="sxs-lookup"><span data-stu-id="70b41-1157">HKCU\SOFTWARE\Microsoft\Office\16.0\Outlook\Preferences\HideRetentionPolicyDuration.</span></span> <span data-ttu-id="70b41-1158">0 = predefinito 1 = verrà visualizzato solo il NomeCriterio per il testo del criterio di conservazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1158">0 = Default 1 = we will only show the PolicyName for Retention policy text.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-1159">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1159">Office Suite</span></span>

- <span data-ttu-id="70b41-1160">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1160">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1902-may-04"></a><span data-ttu-id="70b41-1161">Versione 1902: 4 marzo</span><span class="sxs-lookup"><span data-stu-id="70b41-1161">Version 1902: May 04</span></span>
<span data-ttu-id="70b41-1162">*Versione 1902 (build 11328.20572)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1162">*Version 1902 (Build 11328.20572)*</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1163">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1163">Resolved issues</span></span>
### <a name="office-suite"></a><span data-ttu-id="70b41-1164">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1164">Office Suite</span></span>

- <span data-ttu-id="70b41-1165">È stato risolto un problema di Visual Basic, Applications Edition in Microsoft Office per cui alcuni progetti VBA che contengono riferimenti a librerie di codice con caratteri DBCS nel nome o nel percorso vengono visualizzati dall'applicazione di Office come danneggiati durante il caricamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1165">Fixed an issue in Visual Basic for Applications in Microsoft Office where certain VBA projects that contain references to code libraries with DBCS characters in the library name or library path would be viewed by the Office application as corrupt on load.</span></span>

## <a name="version-1908-april-26"></a><span data-ttu-id="70b41-1166">Versione 1908: 26 aprile</span><span class="sxs-lookup"><span data-stu-id="70b41-1166">Version 1908: April 26</span></span>
<span data-ttu-id="70b41-1167">*Versione 1908 (Build 11929.20736)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1167">*Version 1908 (Build 11929.20736)*</span></span>

<span data-ttu-id="70b41-1168">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1168">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1169">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1169">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1170">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1170">Excel</span></span>

- <span data-ttu-id="70b41-1171">È stato risolto un problema di prestazioni che può essere stato riscontrato dagli utenti nell’utilizzo di una macro VBA per eliminare il contenuto di un intervallo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1171">Fixed a performance issue that users may have experienced when using a VBA macro to clear the contents of a range.</span></span>

- <span data-ttu-id="70b41-1172">È stato risolto un problema in VBA per cui scrivere valori in un intervallo era più lento del previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1172">Fixed an issue with VBA in which writing values to a range would be slower than expected.</span></span>

- <span data-ttu-id="70b41-1173">È stato risolto un problema per cui la proprietà "Intersezione valore" sull'asse di un grafico cambiava in modo imprevisto in caso di salvataggio e riapertura di un file.</span><span class="sxs-lookup"><span data-stu-id="70b41-1173">Addressed an issue where the "Value Crosses At" property on chart axis unexpectedly changes when saving and re-opening a file.</span></span>

- <span data-ttu-id="70b41-1174">Quando si aprivano nella versione corrente di Excel le cartelle di lavoro salvate con una firma digitale in Excel 2016, la firma poteva essere invalidata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1174">Workbooks saved with a digital signature in Excel 2016 could have the signature invalidated upon opening in the current version of Excel.</span></span>


### <a name="onenote"></a><span data-ttu-id="70b41-1175">OneNote</span><span class="sxs-lookup"><span data-stu-id="70b41-1175">OneNote</span></span>

- <span data-ttu-id="70b41-1176">Localizza la notifica che consente all'utente di leggere altre informazioni sulle misure temporanee applicate nell'esperienza utente di OneNote per migliorare la sincronizzazione e la stabilità del servizio.</span><span class="sxs-lookup"><span data-stu-id="70b41-1176">Localizes the notification that allows the user to learn more about temporary measures being enacted in the OneNote user experience to improve sync and service stability.</span></span>


## <a name="version-1908-april-14"></a><span data-ttu-id="70b41-1177">Versione 1908: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="70b41-1177">Version 1908: April 14</span></span>
<span data-ttu-id="70b41-1178">*Versione 1908 (Build 11929.20708)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1178">*Version 1908 (Build 11929.20708)*</span></span>

<span data-ttu-id="70b41-1179">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1179">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1181">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1181">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1182">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1182">Excel</span></span>

- <span data-ttu-id="70b41-1183">È stato risolto un problema che causava il rallentamento delle prestazioni quando si eliminavano colonne contenenti celle unite.</span><span class="sxs-lookup"><span data-stu-id="70b41-1183">Fixed an issue which led to slow performance when deleting columns that contain merged cells.</span></span>

- <span data-ttu-id="70b41-1184">È stato risolto un problema relativo al ridimensionamento del testo nei controlli modulo in visualizzazione Anteprima di stampa.</span><span class="sxs-lookup"><span data-stu-id="70b41-1184">Fixed a problem with scaling of text in form controls when displayed in Print Preview.</span></span>

### <a name="skype"></a><span data-ttu-id="70b41-1185">Skype</span><span class="sxs-lookup"><span data-stu-id="70b41-1185">Skype</span></span>

- <span data-ttu-id="70b41-1186">È stato risolto un problema relativo al nome titolo per la conversazione su schede mentre erano in corso più conversazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1186">Fixed title name for the tabbed conversation while more than one conversation is going on.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-1187">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1187">Outlook</span></span>

- <span data-ttu-id="70b41-1188">È stato risolto un problema che causava un arresto anomalo durante l'arresto di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1188">Addressed an issue that caused users to experience a crash when shutting down Outlook.</span></span>

- <span data-ttu-id="70b41-1189">È stato risolto un problema che causava la visualizzazione di un elenco sale vuoto in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="70b41-1189">Addressed an issue that caused customers to see an empty room list in some scenarios.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="70b41-1190">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1190">PowerPoint</span></span>

- <span data-ttu-id="70b41-1191">È stato risolto un problema con l'evidenziatore: i testi bianchi con colori di evidenziazione scuri vengono stampati come neri in gradazioni di grigio.</span><span class="sxs-lookup"><span data-stu-id="70b41-1191">Fixed an issue with highlighter : White texts with dark highlighter colors are printed as black in Grayscale.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-1192">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1192">Word</span></span>

- <span data-ttu-id="70b41-1193">È stato risolto un problema relativo ad Adatta testo in una tabella.</span><span class="sxs-lookup"><span data-stu-id="70b41-1193">Fixed an issue in Fit Text in Table.</span></span>


## <a name="version-1902-april-14"></a><span data-ttu-id="70b41-1194">Versione 1902: 14 aprile</span><span class="sxs-lookup"><span data-stu-id="70b41-1194">Version 1902: April 14</span></span>
<span data-ttu-id="70b41-1195">*Versione 1902 (Build 11328.20564)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1195">*Version 1902 (Build 11328.20564)*</span></span>

<span data-ttu-id="70b41-1196">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1196">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-march-10"></a><span data-ttu-id="70b41-1198">Versione 1908: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="70b41-1198">Version 1908: March 10</span></span>
<span data-ttu-id="70b41-1199">*Versione 1908 (Build 11929.20648)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1199">*Version 1908 (Build 11929.20648)*</span></span>

<span data-ttu-id="70b41-1200">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1200">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1202">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1202">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1203">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1203">Excel</span></span>

- <span data-ttu-id="70b41-1204">È stato risolto un problema per cui alcuni utenti potrebbero aver riscontrato la presenza di più finestre pop-up quando nella cartella di lavoro erano presenti collegamenti esterni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1204">Fixed an issue where some users may have experienced multiple pop-up windows when external links were present in the workbook.</span></span>


- <span data-ttu-id="70b41-1205">La funzionalità Testo in colonne può non essere disponibile per alcune impostazioni locali.</span><span class="sxs-lookup"><span data-stu-id="70b41-1205">Text to Column functionality may fail for some locales.</span></span>


- <span data-ttu-id="70b41-1206">È possibile che venga visualizzato un errore durante l'accesso a un intervallo denominato nascosto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1206">Users may encounter an error when accessing a hidden named range.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="70b41-1207">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1207">PowerPoint</span></span>

- <span data-ttu-id="70b41-1208">È stato risolto un problema correlato al metodo Shape.Paste: quando l'utente copia e incolla la forma usando il metodo Shape.Paste modifica la selezione nella forma incollata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1208">We fixed an issue with Shape.Paste method: when user copies and paste the shape using Shape.Paste method it changes the selection to the pasted shape.</span></span>


### <a name="word"></a><span data-ttu-id="70b41-1209">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1209">Word</span></span>

- <span data-ttu-id="70b41-1210">È stato risolto un problema per cui, in alcuni casi, il salvataggio di un file esistente comportava sempre la visualizzazione della finestra di dialogo Salva con nome e l’effettivo mancato salvataggio del file.</span><span class="sxs-lookup"><span data-stu-id="70b41-1210">We fixed an issue where in some cases, saving an existing file always causes the Save As dialog and the file never actually saves.</span></span>


### <a name="office-suite"></a><span data-ttu-id="70b41-1211">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1211">Office Suite</span></span>

- <span data-ttu-id="70b41-1212">Questa modifica risolve il rallentamento del rendering di alcuni grafici a dispersione con marcatori.</span><span class="sxs-lookup"><span data-stu-id="70b41-1212">This change addresses slow rendering of some scatter charts with markers.</span></span>

## <a name="version-1902-march-10"></a><span data-ttu-id="70b41-1213">Versione 1902: 10 marzo</span><span class="sxs-lookup"><span data-stu-id="70b41-1213">Version 1902: March 10</span></span>
<span data-ttu-id="70b41-1214">*Versione 1902 (Build 11328.20554)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1214">*Version 1902 (Build 11328.20554)*</span></span>

<span data-ttu-id="70b41-1215">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1215">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-february-11"></a><span data-ttu-id="70b41-1217">Versione 1908: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="70b41-1217">Version 1908: February 11</span></span>
<span data-ttu-id="70b41-1218">*Versione 1908 (Build 11929.20606)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1218">*Version 1908 (Build 11929.20606)*</span></span>

<span data-ttu-id="70b41-1219">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1219">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1221">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1221">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1222">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1222">Excel</span></span>

- <span data-ttu-id="70b41-1223">Questo aggiornamento risolve un problema che causava un errore ogni volta che si usava VBA per aggiungere un'immagine all'intestazione o al piè di pagina di un grafico.</span><span class="sxs-lookup"><span data-stu-id="70b41-1223">This update fixes an issue that caused an error to occur whenever VBA was used to add an image to the header/footer of a chart.</span></span>

- <span data-ttu-id="70b41-1224">È stato risolto un problema per cui il bordo di un controllo casella di gruppo non era visibile nell'anteprima di stampa o stampato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1224">Fixed an issue where the border of a Group Box control wasn't visible in print preview or when printed.</span></span>

- <span data-ttu-id="70b41-1225">È possibile che venga visualizzato un errore durante il salvataggio delle modifiche quando si usano alcuni set di caratteri non inglesi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1225">Users may encounter an error when saving changes while using some non-English character sets.</span></span>

- <span data-ttu-id="70b41-1226">È stato risolto un problema per cui le dimensioni del file delle immagini nelle intestazioni dei grafici aumentava quando la cartella di lavoro contenente il grafico veniva salvata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1226">Fixed an issue where the file size of images in chart headers increased when the workbook containing the chart was saved.</span></span>


- <span data-ttu-id="70b41-1227">È stato risolto un problema che causa il danneggiamento dei caratteri DBCS nei libri a cui viene fatto riferimento incrociato, mantenendo gli intervalli di selezione sincronizzati con il libro oggetto del riferimento incrociato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1227">Fixed an issue that causes corruption of DBCS characters in cross referenced books by keeping the selection ranges in sync with the cross referenced book.</span></span>

- <span data-ttu-id="70b41-1228">È stato risolto un problema per cui i controlli delle caselle di controllo potevano ridursi quando veniva usato l'adattamento automatico per regolare l'altezza delle righe.</span><span class="sxs-lookup"><span data-stu-id="70b41-1228">Resolved an issue that could cause check box controls to shrink when using autofit to adjust row height.</span></span>


### <a name="outlook"></a><span data-ttu-id="70b41-1229">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1229">Outlook</span></span>

- <span data-ttu-id="70b41-1230">È stato risolto un problema che causava un arresto anomalo specificando un indirizzo Da non valido.</span><span class="sxs-lookup"><span data-stu-id="70b41-1230">Addressed an issue that caused users to experience a crash when specifying an invalid From address.</span></span>

- <span data-ttu-id="70b41-1231">È stato risolto un problema che causava errori di sincronizzazione durante l'elaborazione di messaggi di conflitto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1231">Addressed an issue that caused users to experience sync failures when processing conflict messages.</span></span>

- <span data-ttu-id="70b41-1232">È stato risolto un problema che causava il blocco della schermata di caricamento del profilo durante l'avvio di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1232">Addressed an issue that caused users to experience a hang at the Loading Profile screen when Outlook is starting up.</span></span>

- <span data-ttu-id="70b41-1233">È stato risolto un problema che causava arresti anomali intermittenti cambiando visualizzazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1233">Addressed an issue that caused users to see intermittent crashes when changing views.</span></span>


- <span data-ttu-id="70b41-1234">È stato risolto un problema che causava l'arresto anomalo visualizzando più di 30 calendari in un ambiente Citrix.</span><span class="sxs-lookup"><span data-stu-id="70b41-1234">Addressed an issue that caused users to experience a crash when viewing more than 30 calendars in a Citrix environment.</span></span> <span data-ttu-id="70b41-1235">[Qui](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) è disponibile il singolo articolo della Knowledge Basa in cui è stato documentato per le versioni precedenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1235">[Here](https://support.microsoft.com/help/3141476/outlook-may-crash-when-you-view-more-than-30-calendars-in-a-calen) is the individual KB where this was documented for previous versions.</span></span>

- <span data-ttu-id="70b41-1236">È stato risolto un problema nella sincronizzazione delle cartelle del calendario condiviso con l'OST, che causava errori di autorizzazione quando gli utenti provavano a interagire con queste cartelle.</span><span class="sxs-lookup"><span data-stu-id="70b41-1236">Addresses an issue that caused users to have problems problems with shared calendar folders syncing to the OST, resulting in permission errors when they try to interact with these folders.</span></span>


### <a name="powerpoint"></a><span data-ttu-id="70b41-1237">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1237">PowerPoint</span></span>

- <span data-ttu-id="70b41-1238">È stato migliorato uno scenario di copia e incolla: copiare la forma in una diapositiva di PowerPoint e incollarla in un'altra diapositiva in un ciclo poteva non riuscire e generare un'eccezione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1238">Improved a copy-paste scenario Copying the Shape in powerpoint slide and paste it in other slide in a loop might fail with exception.</span></span>


- <span data-ttu-id="70b41-1239">È stato risolto un problema che causava prestazioni più lente tra gli utenti della collaborazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1239">Fixed an issue that was causing slower performance between collaboration users.</span></span>

- <span data-ttu-id="70b41-1240">È stato risolto un problema che può verificarsi quando un file aperto in modo incrementale contiene una diapositiva con più di un flusso di elementi multimediali incorporato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1240">Fixed an issue that can occur when a file being opened incrementally contains a slide with more than one embedded media stream.</span></span>

- <span data-ttu-id="70b41-1241">È stato risolto un problema per cui la barra dei messaggi Avviso di sicurezza poteva non essere visualizzata per i componenti aggiuntivi non attendibili al primo avvio di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1241">We fixed an issue where security warning message bar may not appear for untrusted add-ins on first launch of PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="70b41-1242">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-1242">Project</span></span>

- <span data-ttu-id="70b41-1243">È stato risolto un problema per cui il lavoro effettivo potrebbe essere diverso tra la scheda attività e il piano di progetto perché i calendari delle risorse non vengono aggiornati quando il calendario di base cambia.</span><span class="sxs-lookup"><span data-stu-id="70b41-1243">Fixed an issue where actual work may be different between the timesheet and project plan due to resource calendars not being updated when the base calendar changes.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-1244">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1244">Word</span></span>

- <span data-ttu-id="70b41-1245">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1245">Fixed a crash in Word by moving away from a deprecated API.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-1246">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1246">Office Suite</span></span>

- <span data-ttu-id="70b41-1247">Questa modifica riguarda il rendering corretto delle immagini dopo l'apertura di un file danneggiato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1247">This change addresses correctly rendering images after opening a corrupted file.</span></span>



[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-february-11"></a><span data-ttu-id="70b41-1249">Versione 1902: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="70b41-1249">Version 1902: February 11</span></span>
<span data-ttu-id="70b41-1250">*Versione 1902 (Build 11328.20526)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1250">*Version 1902 (Build 11328.20526)*</span></span>

<span data-ttu-id="70b41-1251">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1251">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1253">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1253">Resolved issues</span></span>
### <a name="outlook"></a><span data-ttu-id="70b41-1254">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1254">Outlook</span></span>

- <span data-ttu-id="70b41-1255">Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1255">Addresses an issue that caused users to encounter encryption algorithm is not supported errors when sending an encrypted email.</span></span>


### <a name="word"></a><span data-ttu-id="70b41-1256">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1256">Word</span></span>

- <span data-ttu-id="70b41-1257">È stato risolto un arresto anomalo di Word abbandonando un'API deprecata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1257">Fixed a crash in Word by moving away from a deprecated API.</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

## <a name="version-1808-february-11"></a><span data-ttu-id="70b41-1260">Versione 1808: 11 febbraio</span><span class="sxs-lookup"><span data-stu-id="70b41-1260">Version 1808: February 11</span></span>
<span data-ttu-id="70b41-1261">*Versione 1808 (Build 10730.20438)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1261">*Version 1808 (Build 10730.20438)*</span></span>

<span data-ttu-id="70b41-1262">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1262">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1908-january-14"></a><span data-ttu-id="70b41-1264">Versione 1908: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="70b41-1264">Version 1908: January 14</span></span>
<span data-ttu-id="70b41-1265">*Versione 1908 (Build 11929.20562)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1265">*Version 1908 (Build 11929.20562)*</span></span>

<span data-ttu-id="70b41-1266">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1266">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT START)

### <a name="feature-updates"></a><span data-ttu-id="70b41-1268">Aggiornamenti delle funzionalità</span><span class="sxs-lookup"><span data-stu-id="70b41-1268">Feature updates</span></span>
### <a name="access"></a><span data-ttu-id="70b41-1269">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-1269">Access</span></span>

- <span data-ttu-id="70b41-1270">**Monitorare gli oggetti di database:** visualizzare chiaramente la scheda attiva, trascinare facilmente le schede per disporle in modo diverso e chiudere gli oggetti di database con un solo clic.</span><span class="sxs-lookup"><span data-stu-id="70b41-1270">**Keep tabs on your database objects:** Clearly see the active tab, easily drag tabs to rearrange them, and close database objects with just one click.</span></span>

- <span data-ttu-id="70b41-1271">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1271">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="70b41-1272">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1272">Switching between them has never been easier.</span></span> [<span data-ttu-id="70b41-1273">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1273">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="70b41-1274">**Zoom con più spazio:** ingrandire la casella Zoom e cambiare il tipo di carattere. Tutte le modifiche verranno mantenute.</span><span class="sxs-lookup"><span data-stu-id="70b41-1274">**Zoom with more room:** Make the Zoom box bigger, change the font, and Zoom remembers it all.</span></span> [<span data-ttu-id="70b41-1275">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1275">Learn more</span></span>](https://support.office.com/article/9a62d165-67f8-4790-bad8-a2c2e83dcedf)

### <a name="excel"></a><span data-ttu-id="70b41-1276">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1276">Excel</span></span>

- <span data-ttu-id="70b41-1277">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1277">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="70b41-1278">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1278">Switching between them has never been easier.</span></span> [<span data-ttu-id="70b41-1279">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1279">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="70b41-1280">**Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1280">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="70b41-1281">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-1281">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="70b41-1282">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1282">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="70b41-1283">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="70b41-1283">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="70b41-1284">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="70b41-1284">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="70b41-1285">**Fogli di lavoro animati:** è possibile inserire grafici 3D animati per visualizzare cuori pulsanti, pianeti in orbita e la furia di un T-Rex nella cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-1285">**Watch your worksheet come alive:** Insert animated 3D graphics to see hearts beat, planets orbit, and T-Rex rampage through the workbook.</span></span> [<span data-ttu-id="70b41-1286">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1286">Learn more</span></span>](https://support.office.com/article/6f08009a-3da5-400d-a706-8e23f304cd72)

- <span data-ttu-id="70b41-p211">**Scoprire di più sui dati:** il nuovo pulsante Idee cerca modelli nei dati e li usa per creare suggerimenti intelligenti e personalizzati. [Altre informazioni](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span><span class="sxs-lookup"><span data-stu-id="70b41-p211">**Discover more about your data:** The new Ideas button looks for patterns in your data, and uses them to create intelligent, personalized suggestions. [Learn more](https://support.office.com/article/3223aab8-f543-4fda-85ed-76bb0295ffc4)</span></span>

- <span data-ttu-id="70b41-1289">**La collaborazione è stata semplificata:** i miglioramenti apportati alla creazione condivisa indicano che, quando si usa la formattazione condizionale, gli stili cella e così via, le modifiche vengono unite perfettamente con quelle dei propri collaboratori.</span><span class="sxs-lookup"><span data-stu-id="70b41-1289">**Collaboration just got easier:** Co-authoring improvements mean that when working with conditional formatting, cell styles, and more, your changes are merged seamlessly with those of your collaborators.</span></span>

- <span data-ttu-id="70b41-1290">**Unione di tabelle in colonne simili:** Recupera e trasforma (Power Query) ora include una logica di corrispondenza del testo approssimativa (denominata anche corrispondenza fuzzy) durante il confronto di colonne per unire le tabelle.</span><span class="sxs-lookup"><span data-stu-id="70b41-1290">**Join tables on similar columns:** Get & Transform (Power Query) now features approximate text matching logic (also called fuzzy matching) when comparing columns for merging tables.</span></span> [<span data-ttu-id="70b41-1291">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1291">Learn more</span></span>](https://support.office.com/article/ffdd5082-c0c8-4c8e-a794-bd3962b90649)

- <span data-ttu-id="70b41-1292">**Codice rapido con i miglioramenti di Power Query:** è possibile completare rapidamente il codice con il completamento automatico e i colori della sintassi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1292">**Code quickly with Power Query enhancements:** Get to code completion quickly with auto-complete and syntax coloring.</span></span> <span data-ttu-id="70b41-1293">Semplice individuazione di funzioni, colonne e parametri.</span><span class="sxs-lookup"><span data-stu-id="70b41-1293">Easily discover functions, columns, and parameters, too.</span></span>

- <span data-ttu-id="70b41-1294">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1294">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="70b41-1295">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="70b41-1295">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="70b41-1296">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1296">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="outlook"></a><span data-ttu-id="70b41-1297">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1297">Outlook</span></span>

- <span data-ttu-id="70b41-1298">**Aggiornamento dell'esperienza utente di Outlook:** è finalmente accessibile a tutti un'esperienza semplificata, in precedenza disponibile in anteprima con Prossimamente, progettata per consentire all'utente di concentrarsi sugli aspetti più importanti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1298">**We’ve updated the Outlook user experience for you:** A simplified experience, previously available for preview with Coming Soon, designed to help you focus on what matters most.</span></span> [<span data-ttu-id="70b41-1299">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1299">Learn more</span></span>](https://support.office.com/article/db503157-1b45-45d5-af52-e9c978cd8bed)

- <span data-ttu-id="70b41-1300">**Barra multifunzione semplificata e personalizzabile:** un'unica riga essenziale riunisce i pulsanti usati di frequente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1300">**A simplified ribbon that's customizable, too:** Enjoy a streamlined, single row of the most frequently used buttons.</span></span> <span data-ttu-id="70b41-1301">In questo modo è possibile passare facilmente dalla visualizzazione classica a quella semplificata e aggiungere/rimuovere comandi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1301">Easily switch between classic and Simplified views, and pin/unpin commands.</span></span> [<span data-ttu-id="70b41-1302">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1302">Learn more</span></span>](https://support.office.com/article/44bef9c3-295d-4092-b7f0-f471fa629a98)

- <span data-ttu-id="70b41-1303">**Continuare a lavorare durante lo spostamento di messaggi:** ora Outlook sposta i messaggi in background, di conseguenza è possibile continuare a lavorare durante lo spostamento di grandi quantità di messaggi tra le cartelle.</span><span class="sxs-lookup"><span data-stu-id="70b41-1303">**Keep working while moving messages:** Outlook now moves messages in the background, so you can keep working while moving lots of messages between folders.</span></span>

- <span data-ttu-id="70b41-1304">**Avere un momento di respiro tra una riunione e l'altra:** dare ai partecipanti il tempo di riprendere fiato o di viaggiare da una località all'altra impostando le riunioni in modo che terminino per impostazione predefinita 5-10 minuti in anticipo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1304">**Build in time between back-to-back meetings:** Give attendees time to catch their breath or travel between locations by setting meetings to end 5-10 minutes early by default.</span></span>

- <span data-ttu-id="70b41-1305">**Selezione dell'azione preferita:** le azioni Contrassegna e Elimina non vengono usate,</span><span class="sxs-lookup"><span data-stu-id="70b41-1305">**Pick your favorite action:** Don't use Flag and Delete?</span></span> <span data-ttu-id="70b41-1306">ma si preferisce usare Archivia o Segna come già letto?</span><span class="sxs-lookup"><span data-stu-id="70b41-1306">How about Archive or Mark as Read?</span></span> <span data-ttu-id="70b41-1307">È possibile personalizzare il menu Azioni rapide con i comandi usati più di frequente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1307">Customize the quick action menu with the commands you use most.</span></span>

- <span data-ttu-id="70b41-p218">**Utilizzo di meme:** quando testo o immagini statiche non bastano, si può usare una GIF animata per esprimere il proprio pensiero. [Altre informazioni](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span><span class="sxs-lookup"><span data-stu-id="70b41-p218">**They'll see what you meme:** When text or static images just won't do, use an animated GIF to make your point. [Learn more](https://support.office.com/article/114bb251-861f-41cd-b20f-7e7289630c5b)</span></span>

- <span data-ttu-id="70b41-1310">**Un modo più rapido per aggiungere account:** grazie ai miglioramenti per la configurazione dell'account, l'aggiunta di account di Outlook.com e Gmail che utilizzano l'autenticazione a 2 fattori in Outlook è più facile che mai.</span><span class="sxs-lookup"><span data-stu-id="70b41-1310">**A quicker way to add accounts:** Thanks to account setup improvements, it's easier than ever to add Outlook.com and Gmail accounts that use 2-factor authentication to Outlook.</span></span> [<span data-ttu-id="70b41-1311">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1311">Learn more</span></span>](https://support.office.com/article/70191667-9c52-4581-990e-e30318c2c081)

- <span data-ttu-id="70b41-1312">**Addio ai limiti per la sincronizzazione:** con i miglioramenti di Outlook non esiste più il limite di cartelle e quindi è possibile sincronizzare le cassette postali condivise.</span><span class="sxs-lookup"><span data-stu-id="70b41-1312">**Say goodbye to sync limits:** Outlook improvements mean the folder limit is gone so go ahead and synchronize your shared mailboxes.</span></span>

- <span data-ttu-id="70b41-1313">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1313">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="70b41-1314">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="70b41-1314">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="70b41-1315">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1315">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="powerpoint"></a><span data-ttu-id="70b41-1316">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1316">PowerPoint</span></span>

- <span data-ttu-id="70b41-1317">**Spostamento di forme migliorato:** assegnare un nome alle forme per un maggiore controllo sul modo in cui effettuano il morphing.</span><span class="sxs-lookup"><span data-stu-id="70b41-1317">**Better shapeshifting:** Name your shapes for more control over how they morph.</span></span> [<span data-ttu-id="70b41-1318">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1318">Learn more</span></span>](https://support.office.com/article/bc7f48ff-f152-4ee8-9081-d3121788024f)

- <span data-ttu-id="70b41-1319">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="70b41-1319">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="70b41-1320">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="70b41-1320">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="70b41-1321">**Aumentare l'efficacia del contenuto:** rendere accessibili le presentazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1321">**Increase the reach of your content:** Need to make your presentations accessible?</span></span> <span data-ttu-id="70b41-1322">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-1322">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="70b41-1323">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1323">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="70b41-1324">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1324">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="70b41-1325">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1325">Switching between them has never been easier.</span></span> [<span data-ttu-id="70b41-1326">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1326">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="70b41-1327">**Una nuova casa per i video online:** è possibile salvare un video in Microsoft Stream per consentire a tutti gli utenti dell'organizzazione di visualizzarlo,</span><span class="sxs-lookup"><span data-stu-id="70b41-1327">**Online videos have a new home:** Save a video to Microsoft Stream so anyone in your organization can see it.</span></span> <span data-ttu-id="70b41-1328">nonché inserire il collegamento del video e ottenere una presentazione multimediale di dimensioni notevolmente ridotte rispetto a quelle del file.</span><span class="sxs-lookup"><span data-stu-id="70b41-1328">Insert the video link and enjoy a multimedia presentation at a fraction of the file size.</span></span> [<span data-ttu-id="70b41-1329">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1329">Learn more</span></span>](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)

- <span data-ttu-id="70b41-1330">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1330">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="70b41-p226">**Fare domande al pubblico con un test o un sondaggio:** inserire un test o un sondaggio in una diapositiva. Office raccoglie e archivia le risposte. [Ulteriori informazioni](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span><span class="sxs-lookup"><span data-stu-id="70b41-p226">**Ask your audience with a quiz or survey:** Put a quiz or survey on a slide. Office collects and stores the responses for you. [Learn more](https://support.office.com/article/1a316f81-9ea7-4bc2-bda0-024c0d780df1)</span></span>

- <span data-ttu-id="70b41-p227">**Inserire un video online è più facile che mai:** se si vuole inserire un video da Vimeo o YouTube nella diapositiva, basta il collegamento alla pagina del video. [Altre informazioni](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span><span class="sxs-lookup"><span data-stu-id="70b41-p227">**Inserting an online video is easier than ever:** Want to put a video from Vimeo or YouTube on your slide? The video page link is all you need. [Learn more](https://support.office.com/article/8340ec69-4cee-4fe1-ab96-4849154bc6db)</span></span>

- <span data-ttu-id="70b41-1337">**Cercare è più facile:** abbiamo aggiunto la ricerca per inserire icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1337">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="70b41-1338">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="70b41-1338">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="70b41-1339">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1339">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="project"></a><span data-ttu-id="70b41-1340">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-1340">Project</span></span>

- <span data-ttu-id="70b41-1341">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1341">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="70b41-1342">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1342">Switching between them has never been easier.</span></span> [<span data-ttu-id="70b41-1343">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1343">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

### <a name="visio"></a><span data-ttu-id="70b41-1344">Visio</span><span class="sxs-lookup"><span data-stu-id="70b41-1344">Visio</span></span>

- <span data-ttu-id="70b41-1345">**Esportazione dei diagrammi di processo in Word:** è possibile aggiungere automaticamente il contenuto dei diagrammi, come forme e metadati, a un documento Word.</span><span class="sxs-lookup"><span data-stu-id="70b41-1345">**Export process diagrams to Word:** Automatically add diagram content, such as shapes and metadata, to a Word document.</span></span> <span data-ttu-id="70b41-1346">Quindi, personalizzare il documento per creare linee guida di processi e manuali operativi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1346">Then customize the document to create process guidelines and operation manuals.</span></span> [<span data-ttu-id="70b41-1347">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1347">Learn more</span></span>](https://support.office.com/article/48073f4f-c6d4-4cc0-b9ae-3cb65e2ee158)

- <span data-ttu-id="70b41-1348">**Maggiore controllo sui diagrammi di flusso di dati:** i nuovi fantastici layout per i diagrammi di flusso del Visualizzatore dati sono chiari, nitidi e facili da capire.</span><span class="sxs-lookup"><span data-stu-id="70b41-1348">**Double-take on data flowcharts:** Gorgeous new layouts for Data Visualizer flowcharts are clean, crisp, and easy to understand.</span></span> <span data-ttu-id="70b41-1349">Fare clic sulla scheda Progettazione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1349">Click the Design tab for options.</span></span>

- <span data-ttu-id="70b41-1350">**Stencil di Azure incorporati:** per progettare un'applicazione cloud o pianificare un'architettura è possibile scegliere tra decine di stencil di Azure.</span><span class="sxs-lookup"><span data-stu-id="70b41-1350">**Azure stencils built right in:** Design a cloud app or plan an architecture using dozens of Azure stencils.</span></span> [<span data-ttu-id="70b41-1351">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1351">Learn more</span></span>](https://support.office.com/article/efbb25e7-c80e-42e1-b1ad-7ef630ff01b7)

- <span data-ttu-id="70b41-p233">**Addio ai collegamenti interrotti di Excel:** impossibile trovare la cartella di lavoro di Excel collegata al diagramma del Visualizzatore dati? Collegarla di nuovo per riprendere l’attività. [Altre informazioni](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span><span class="sxs-lookup"><span data-stu-id="70b41-p233">**Say goodbye to broken Excel links:** Can't find the Excel workbook linked to your Data Visualizer diagram? Relink it, and you're back in business. [Learn more](https://support.office.com/article/17211b46-d144-4ca2-9ea7-b0f48f0ae0a6)</span></span>

- <span data-ttu-id="70b41-1355">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1355">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="70b41-1356">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1356">Switching between them has never been easier.</span></span> [<span data-ttu-id="70b41-1357">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1357">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="70b41-1358">**Esportare elementi visivi di Visio da Power BI:** gli oggetti visivi di Visio per Power BI vengono ora visualizzati correttamente quando si esportano i report di Power BI come PDF, file di PowerPoint e altro ancora.</span><span class="sxs-lookup"><span data-stu-id="70b41-1358">**Export Visio visuals from Power BI:** Visio Visual for Power BI will now display properly when you export Power BI reports as PDFs, PowerPoint files, and more.</span></span> [<span data-ttu-id="70b41-1359">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1359">Learn more</span></span>](https://support.office.com/article/4f09be62-f436-45c2-93b0-4a0f66b1f5a7)

### <a name="word"></a><span data-ttu-id="70b41-1360">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1360">Word</span></span>

- <span data-ttu-id="70b41-1361">**La modalità Strumenti di apprendimento dispone di ulteriore supporto per più colori della pagina:** in Strumenti di apprendimento in Word è stato aggiunto il supporto per altri colori del tema della pagina, per poter modificare il colore di sfondo della pagina.</span><span class="sxs-lookup"><span data-stu-id="70b41-1361">**Learning Tools mode has additional support for more page colors:** Learning Tools in Word adds support for more page theme colors, which allows the changing of the background color of the page.</span></span> <span data-ttu-id="70b41-1362">Molti utenti hanno difficoltà a leggere con uno sfondo completamente bianco o completamente nero, quindi è stata ampliata la scelta dei colori disponibili in Word su PC e Mac.</span><span class="sxs-lookup"><span data-stu-id="70b41-1362">Many people have challenges reading with an all-white or all-black background, so we’ve expanded the choice of colors in Word on PC and Mac.</span></span>

- <span data-ttu-id="70b41-p237">**Modifica semplificata con Editor input penna:** con un solo tratto della penna, si possono dividere o unire le parole, aggiungere una nuova riga o inserire parole. [Ulteriori informazioni](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span><span class="sxs-lookup"><span data-stu-id="70b41-p237">**Editing comes naturally with Ink Editor:** With a single stroke, split or join words, add a new line, or insert words using your pen. [Learn more](https://support.office.com/article/7edbcf8e-0004-484d-9b62-501a31c23ee9)</span></span>

- <span data-ttu-id="70b41-p238">**Trasformare il documento da statico a sorprendente:** trasformare il documento in una pagina web interattiva, facile da condividere che si adatta perfettamente a qualsiasi dispositivo. [Altre informazioni](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span><span class="sxs-lookup"><span data-stu-id="70b41-p238">**Take your doc from static to stunning:** Transform your document into an interactive, easy-to-share web page that looks great on any device. [Learn more](https://support.office.com/article/65912b2d-8b81-41e1-ac52-c20a65ce8ecf)</span></span>

- <span data-ttu-id="70b41-1367">**Aumentare l'efficacia del contenuto:** rendere accessibili i documenti</span><span class="sxs-lookup"><span data-stu-id="70b41-1367">**Increase the reach of your content:** Need to make your documents accessible?</span></span> <span data-ttu-id="70b41-1368">Consentire allo strumento di verifica accessibilità di tenerli sotto controllo senza intralciare il lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-1368">Let the accessibility checker keep an eye on it for you, without getting in the way.</span></span> <span data-ttu-id="70b41-1369">Per provare, fare clic su Revisione > Verifica accessibilità. Se verranno trovati elementi da consultare, verrà visualizzato un avviso nella barra di stato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1369">Try it by clicking Review > Check Accessibility – we’ll tell you when we find something you need to look at in the status bar.</span></span>

- <span data-ttu-id="70b41-1370">**Ricerca rapida del file:** Come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="70b41-1370">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="70b41-1371">È sufficiente digitare nella casella di ricerca su File > Home page per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="70b41-1371">Just type in the Search box on the File > Home page to find the file you're looking for.</span></span>

- <span data-ttu-id="70b41-1372">**Passaggio semplificato:** la nuova interfaccia di Gestione account consente di visualizzare tutti gli account aziendali e personali di Office 365 in un'unica posizione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1372">**Switch seamlessly:** The new account manager shows all of your Office 365 work and personal accounts in one place.</span></span> <span data-ttu-id="70b41-1373">Passare da uno all’altro non è mai stato così facile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1373">Switching between them has never been easier.</span></span> [<span data-ttu-id="70b41-1374">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1374">Learn more</span></span>](https://support.office.com/article/d17de17e-9f26-4dae-bd08-d7b8f46eb0b9)

- <span data-ttu-id="70b41-p242">**Migliorare la comprensione con Focus su riga:** spostarsi in un documento riga per riga senza distrazioni. Modificare lo stato attivo per rendere visibili una, tre o cinque righe alla volta. [Altre informazioni](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span><span class="sxs-lookup"><span data-stu-id="70b41-p242">**Improve comprehension with Line Focus:** Move through a document line by line without distractions. Adjust the focus to put one, three, or five lines in view at a time. [Learn more](https://support.office.com/article/a857949f-c91e-4c97-977c-a4efcaf9b3c1)</span></span>

- <span data-ttu-id="70b41-1378">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1378">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="70b41-1379">**Ottenere l'attenzione tramite \@menzioni:** usare le @menzioni nei commenti per informare i collaboratori quando c'è bisogno del loro input.</span><span class="sxs-lookup"><span data-stu-id="70b41-1379">**Get Their Attention with \@Mentions:** Use @mentions in comments to let co-workers know when you need their input.</span></span> [<span data-ttu-id="70b41-1380">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1380">Learn more</span></span>](https://support.office.com/article/644bf689-31a0-4977-a4fb-afe01820c1fd)

- <span data-ttu-id="70b41-1381">**Cercare è più facile:** abbiamo aggiunto la funzionalità di ricerca in Inserisci icone per trovare più facilmente l'icona desiderata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1381">**Search and enjoy:** We've added Search to Insert Icons to make it easy to find the icon you want.</span></span> <span data-ttu-id="70b41-1382">E quando si seleziona, il pulsante Inserisci indica quante icone sono selezionate.</span><span class="sxs-lookup"><span data-stu-id="70b41-1382">And when you're selecting, the Insert button tells you how many you've picked.</span></span> [<span data-ttu-id="70b41-1383">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1383">Learn more</span></span>](https://support.office.com/article/e2459f17-3996-4795-996e-b9a13486fa79)

### <a name="office-suite"></a><span data-ttu-id="70b41-1384">Famiglia di prodotti Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1384">Office Suite</span></span>

- <span data-ttu-id="70b41-1385">**Ricerca rapida del file:** come cercare un file utilizzato di recente?</span><span class="sxs-lookup"><span data-stu-id="70b41-1385">**Find that file fast:** Looking for a file you worked on recently?</span></span> <span data-ttu-id="70b41-1386">È sufficiente digitare nella casella di ricerca su File > Apri per trovare il file che si sta cercando.</span><span class="sxs-lookup"><span data-stu-id="70b41-1386">Just type in the Search box on the File > Open tab to find the file you're looking for.</span></span>

- <span data-ttu-id="70b41-1387">**Salvare le modifiche non appena vengono apportate:** caricare i file in OneDrive per assicurarsi che tutti gli aggiornamenti vengano salvati automaticamente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1387">**Save your changes as they happen:** Upload your file to OneDrive to make sure all your updates are saved automatically.</span></span>

- <span data-ttu-id="70b41-1388">**Controlli della privacy:** Controlli nuovi, aggiornati e migliorati per dati di diagnostica ed esperienze connesse.</span><span class="sxs-lookup"><span data-stu-id="70b41-1388">**Privacy controls:** New, updated, and improved controls for diagnostic data and connected experiences.</span></span> [<span data-ttu-id="70b41-1389">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1389">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/privacy/overview-privacy-controls?toc=/deployoffice/toc.json)

- <span data-ttu-id="70b41-1390">**Le icone di Office hanno un nuovo aspetto:** le icone di Office sono state riprogettate per riflettere l'esperienza semplice potente e intelligente di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-1390">**Office icons have a new look:** The Office icons have been redesigned to reflect simple, powerful, and intelligent Office experiences.</span></span>

- <span data-ttu-id="70b41-1391">**Installazione di Microsoft Teams:** Microsoft Teams viene installato per impostazione predefinita nelle installazioni esistenti di Office 365 ProPlus.</span><span class="sxs-lookup"><span data-stu-id="70b41-1391">**Installation of Microsoft Teams:** Microsoft Teams is installed by default for existing installations of Office 365 ProPlus.</span></span> [<span data-ttu-id="70b41-1392">Altre informazioni</span><span class="sxs-lookup"><span data-stu-id="70b41-1392">Learn more</span></span>](https://docs.microsoft.com/DeployOffice/teams-install)

[//]: # (DO NOT REMOVE FEATUREDETAILS CONTENT END)

<br/>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1395">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1395">Resolved issues</span></span>
### <a name="access"></a><span data-ttu-id="70b41-1396">Access</span><span class="sxs-lookup"><span data-stu-id="70b41-1396">Access</span></span>

- <span data-ttu-id="70b41-1397">Questo aggiornamento risolve un problema per cui aggregazioni come Somma potevano troncare il risultato in un valore intero.</span><span class="sxs-lookup"><span data-stu-id="70b41-1397">This update fixes an issue where aggregate like Sum may truncate the result to an integer value.</span></span>

- <span data-ttu-id="70b41-1398">Questo aggiornamento risolve un problema per cui una query di unione con riferimenti a tabelle remote, ad esempio tabelle di SQL Server, causava la chiusura e il riavvio di Access.</span><span class="sxs-lookup"><span data-stu-id="70b41-1398">This update fixes an issue where a Union query that includes references to remote tables (e.g. SQL Server tables) may cause Access to close and restart.</span></span>

- <span data-ttu-id="70b41-1399">Questo aggiornamento risolve un problema di Microsoft Access, che potrebbe causare un errore di tipo &quot;Query danneggiata&quot; quando si esegue una query di aggiornamento o se si usa un'istruzione UPDATE in SQL.</span><span class="sxs-lookup"><span data-stu-id="70b41-1399">This update fixes an issue in Microsoft Access that may cause the error &quot;Query is Corrupt&quot; when an Update Query is run, or an UPDATE statement is used in SQL.</span></span>

### <a name="excel"></a><span data-ttu-id="70b41-1400">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1400">Excel</span></span>

- <span data-ttu-id="70b41-1401">Suggerimento tasto di scelta olandese per il titolo del documento è stato modificato in Alt-G.</span><span class="sxs-lookup"><span data-stu-id="70b41-1401">Dutch keytip for document title has been changed to Alt-G.</span></span>

- <span data-ttu-id="70b41-1402">È stato risolto un problema in Excel in cui le macro assegnate alle forme o ai controlli modulo possono visualizzare un messaggio di errore non corretto oppure possono funzionare su intervalli di destinazione non corretti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1402">Fixed an issue in Excel where macros assigned to shapes or form controls may show incorrect error message, or may work on incorrect target ranges.</span></span>

- <span data-ttu-id="70b41-1403">È stato risolto un problema nell'opzione Trova e sostituisci per cui lo stato attivo veniva spostato nella finestra di dialogo dopo l'individuazione della prima occorrenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1403">Resolved an issue with Find and Replace that change where the focus was in the dialog after finding the first item.</span></span>

- <span data-ttu-id="70b41-1404">Questo aggiornamento risolve un problema per cui è stato modificato il modo in cui una tabella pivot viene ordinata e aggiornata durante una sessione di creazione condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1404">This fixes an issue where changing the way a PivotTable is sorted and refreshing it while in a coauthoring session with other users could trigger a crash.</span></span>

- <span data-ttu-id="70b41-1405">Abbiamo risolto un problema per cui il filtro per una tabella pivot OLAP era stato impostato su un valore rimosso dal cubo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1405">We fixed a problem when the filter for an OLAP PivotTable was set to a value that had been removed from the cube.</span></span>

- <span data-ttu-id="70b41-1406">Correzione per risolvere un problema relativo ai colori usati nelle anteprime quando si inseriscono grafici usando modelli di grafico.</span><span class="sxs-lookup"><span data-stu-id="70b41-1406">Fix to correct colors used in previews when inserting charts using chart templates.</span></span>

- <span data-ttu-id="70b41-1407">È stato risolto un problema che poteva causare il rendering non corretto dei grafici a linee o a dispersione modificando la raccolta serie.</span><span class="sxs-lookup"><span data-stu-id="70b41-1407">We fixed an issue which could have caused scatter line charts from rendering properly when changing the series collection.</span></span>

- <span data-ttu-id="70b41-1408">È stato risolto un problema che impediva la sincronizzazione dei grafici a cascata e a imbuto con le tabelle in seguito all'inserimento o all'eliminazione di celle.</span><span class="sxs-lookup"><span data-stu-id="70b41-1408">Resolved an issue that caused Waterfall and Funnel charts to get out of sync with tables when cells were inserted or deleted.</span></span>

- <span data-ttu-id="70b41-1409">È stato risolto un problema di conflitto di unione in Excel che potrebbe comportare la richiesta di riaprire la cartella di lavoro.</span><span class="sxs-lookup"><span data-stu-id="70b41-1409">Fixed a merge conflict issue in Excel that would result in users being prompted to reopen workbook to pick up the changes.</span></span>

- <span data-ttu-id="70b41-1410">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1410">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="70b41-1411">È stato risolto un problema che causava un errore in fase di esecuzione della macro attivando la riduzione delle finestre.</span><span class="sxs-lookup"><span data-stu-id="70b41-1411">Resolved an issue that caused a macro run-time error activating minimized windows.</span></span>

- <span data-ttu-id="70b41-1412">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1412">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

- <span data-ttu-id="70b41-1413">È stato risolto un problema a causa del quale le operazioni di taglia e incolla accanto a una tabella non funzionano quando si lavora in modalità condivisa con altri utenti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1413">Resolved an issue that caused cut and paste operations next to a table to fail when co-authoring with others.</span></span>

- <span data-ttu-id="70b41-1414">È stato risolto un problema che causava interruzioni della creazione condivisa quando si modificavano le proprietà personalizzate durante l'esecuzione delle macro.</span><span class="sxs-lookup"><span data-stu-id="70b41-1414">Resolved an issue that caused co-authoring interruptions when changing custom properties with running macros.</span></span>

- <span data-ttu-id="70b41-1415">È stato riscontrato un problema che impedisce di selezionare elementi da una casella combinata di un modulo di WPF (Windows Presentation Foundation) aperto tramite un componente aggiuntivo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1415">There was a problem in which you would be unable to select items from combo box of a WPF (Windows Presentation Foundation) form that was opened by an add-in.</span></span>

- <span data-ttu-id="70b41-1416">È stato risolto un problema che poteva causare un arresto anomalo durante la ricerca di file recenti in assenza di cartelle di lavoro aperte.</span><span class="sxs-lookup"><span data-stu-id="70b41-1416">Resolved an issue that may have caused a crash when searching for recent files while no workbook is open.</span></span>

- <span data-ttu-id="70b41-1417">Problema di prestazioni relativo alle funzioni asincrone definite dall'utente che causava l'esecuzione sincrona di tali funzioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1417">Performance issue with Asynchronous User-Defined Functions that was causing them to be run Synchronously.</span></span>

- <span data-ttu-id="70b41-1418">Sono state notevolmente migliorate le prestazioni di eliminazione delle colonne con celle unite.</span><span class="sxs-lookup"><span data-stu-id="70b41-1418">Significant improvements to the performance of deleting columns with merged cells.</span></span>

- <span data-ttu-id="70b41-1419">È stato risolto un problema per cui selezionare una cella dopo lo scorrimento poteva comportare la selezione della cella sbagliata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1419">Resolved an issue where selecting a cell after scrolling could result in the wrong cell being selected.</span></span>

- <span data-ttu-id="70b41-1420">È stato risolto un problema per cui la funzione Cerca restituiva un errore.</span><span class="sxs-lookup"><span data-stu-id="70b41-1420">Resolved an issue where the Lookup function may return an error.</span></span>

- <span data-ttu-id="70b41-1421">È stato risolto un problema per cui le cartelle di lavoro create in versioni precedenti di Office potevano causare il blocco di Excel se aperte nelle versioni correnti di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-1421">Resolved an issue where workbooks created in earlier versions of Office could cause Excel to hang when opened in current versions of Office.</span></span>

- <span data-ttu-id="70b41-1422">Problema di prestazioni lente quando si fa clic sul pulsante Colore carattere in un file con formattazione condizionale estesa.</span><span class="sxs-lookup"><span data-stu-id="70b41-1422">Issue with slow performance on clicking on the Font Color button when a file has extensive conditional formatting.</span></span>

- <span data-ttu-id="70b41-1423">È stato risolto un problema per cui l'area di stampa in anteprima di stampa non risultava corretta.</span><span class="sxs-lookup"><span data-stu-id="70b41-1423">We fixed an issue where the print area in print preview was not correct.</span></span>

- <span data-ttu-id="70b41-1424">Potrebbero verificarsi problemi in Excel durante la modifica di un file protetto da una condivisione di rete non attendibile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1424">Excel may have issues when editing a protected file from an untrusted network share.</span></span>

- <span data-ttu-id="70b41-1425">Sono state notevolmente migliorate le prestazioni del filtro per colore.</span><span class="sxs-lookup"><span data-stu-id="70b41-1425">We have significantly improved the performance of filtering by color.</span></span>

- <span data-ttu-id="70b41-1426">È stato risolto un problema che non consentiva di incollare collegamenti ipertestuali in alcuni fogli protetti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1426">Resolved an issue that prevented Hyperlinks from being pasted in some protected sheets.</span></span>

- <span data-ttu-id="70b41-1427">Sono stati abilitati più di 16 componenti aggiuntivi da visualizzare durante l'esplorazione in Gestione componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1427">Enabled more than 16 add-ins to show when browsing in the add-in manager.</span></span>

- <span data-ttu-id="70b41-1428">La modifica aggira un problema con alcuni driver di grafica Intel sfruttando il rendering del software.</span><span class="sxs-lookup"><span data-stu-id="70b41-1428">This change circumvents a problem with certain Intel graphics drivers by leveraging software rendering.</span></span>

- <span data-ttu-id="70b41-1429">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1429">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-1430">Questo aggiornamento corregge un errore in cui il caricamento dei documenti di Office in OneDrive for Business potrebbe avere esito negativo con il messaggio "Caricamento non riuscito".</span><span class="sxs-lookup"><span data-stu-id="70b41-1430">This update fixes an error where Office documents may fail to upload to OneDrive for Business with the message "Upload Failed".</span></span>

- <span data-ttu-id="70b41-1431">È stato corretto un problema nella funzionalità Idee di Excel che provocava un errore durante il caricamento del componente aggiuntivo facendo clic sul pulsante Idee nel client Win32.</span><span class="sxs-lookup"><span data-stu-id="70b41-1431">Fix issue in Excel Ideas feature, error when loading the add-in by clicking the Ideas button in Win32 client.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-1432">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1432">Outlook</span></span>

- <span data-ttu-id="70b41-1433">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1433">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-1434">È stato risolto un problema per cui gli utenti che hanno eseguito l'aggiornamento della cassetta postale dall'autenticazione di base a quella moderna si sono ritrovati con l'account errato associato al proprio profilo Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1434">Fixed an issue where users having their mailbox upgraded from basic to modern authentication were ending up with the wrong account associated with their Outlook profile.</span></span>

- <span data-ttu-id="70b41-1435">È stato risolto un problema che causava l'accesso indesiderato dei componenti aggiuntivi Web ai messaggi con contenuto digitale protetto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1435">Addressed an issue that caused web add ins to access Digital Rights Managed messages when they should not.</span></span>

- <span data-ttu-id="70b41-1436">È stato corretto un problema che causava la mancata visualizzazione degli URL al passaggio del mouse per alcuni collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="70b41-1436">Addressed an issue that caused the simple-hover URLs to fail to display for some safelinks.</span></span>

- <span data-ttu-id="70b41-1437">È stata aggiornata la logica di blocco degli allegati in Outlook in modo da bloccare anche gli allegati Python.</span><span class="sxs-lookup"><span data-stu-id="70b41-1437">This updates the attachment blocking logic in Outlook to also block python attachments.</span></span>

- <span data-ttu-id="70b41-1438">È stato risolto un problema a causa del quale un sottoinsieme di utenti POP3 visualizza tutti i messaggi di posta elettronica formattati in testo normale, indipendentemente dalle impostazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1438">Addressed an issue that caused a subset of POP3 users to see all of their emails formatted at plain text, regardless of settings.</span></span> <span data-ttu-id="70b41-1439">Questa correzione ripristina la visualizzazione dei messaggi in formato HTML.</span><span class="sxs-lookup"><span data-stu-id="70b41-1439">This fix will restore the view of the HTML formatted messages.</span></span>

- <span data-ttu-id="70b41-1440">È stato risolto un problema che causava un errore di autorizzazione degli utenti durante la copia di elementi dal calendario principale a un calendario di gruppo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1440">Addressed an issue that caused users to experience a permission error when copying items from their primary calendar to a group calendar.</span></span>

- <span data-ttu-id="70b41-1441">È stato risolto un problema che impediva agli utenti di accedere ai suggerimenti per la posizione con un'utilità per la lettura dello schermo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1441">Addressed an issue that caused users to be unable to access location suggestions via a screen reader.</span></span>

- <span data-ttu-id="70b41-1442">È stato risolto un problema che causava un considerevole ritardo nell'interazione con le cartelle delle cassette postali degli utenti usando le scelte rapide da tastiera.</span><span class="sxs-lookup"><span data-stu-id="70b41-1442">Addressed an issue that caused users to see a noticeable delay when interacting with their mailbox folders through keyboard shortcuts.</span></span>

- <span data-ttu-id="70b41-1443">È stato risolto un problema che causava una perdita di memoria in caso di sessioni di Outlook molto lunghe.</span><span class="sxs-lookup"><span data-stu-id="70b41-1443">Addressed an issue that caused a memory leak for very long Outlook sessions.</span></span>

- <span data-ttu-id="70b41-1444">È stato risolto un problema che causava la visualizzazione del messaggio "Le regole impostate in questo computer non corrispondono alle regole impostate in Microsoft Exchange" all'apertura della finestra di dialogo Regole.</span><span class="sxs-lookup"><span data-stu-id="70b41-1444">Addressed an issue that caused users to see a "The rules on this computer do not match the rules on Microsoft Exchange" prompt when opening the Rules dialog.</span></span>

- <span data-ttu-id="70b41-1445">È stato risolto un problema che causava un arresto anomalo di Outlook durante l'interazione con determinati collegamenti sicuri.</span><span class="sxs-lookup"><span data-stu-id="70b41-1445">Addressed an issue that would cause users to experience a crash in Outlook when interacting with certain safelinks.</span></span>

- <span data-ttu-id="70b41-1446">È stato risolto un problema che causava ambiguità per i responsabili circa il fatto che un delegato abbia già risposto o meno a una determinata convocazione di riunione.</span><span class="sxs-lookup"><span data-stu-id="70b41-1446">Addressed an issue that caused ambiguity for managers around whether or not a delegate had already responded to a given meeting request.</span></span>

- <span data-ttu-id="70b41-1447">È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1447">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="70b41-1448">È stato risolto un problema che causava la visualizzazione di una finestra di messaggio vuota con un pulsante "OK" quando si provava a contattare il supporto dal contesto di creazione dell'account.</span><span class="sxs-lookup"><span data-stu-id="70b41-1448">Addressed an issue that caused users to see an empty message box with an "OK" button when trying to contact support from the Account Creation context.</span></span>

- <span data-ttu-id="70b41-1449">Questa modifica consente agli amministratori di abilitare un criterio per preferire l'account di posta elettronica fornito nelle richieste di autenticazione del servizio di individuazione automatica rispetto all'UPN.</span><span class="sxs-lookup"><span data-stu-id="70b41-1449">This change allows administrators to enable a policy to prefer the provided account email in AutoDiscover auth prompts over the UPN.</span></span> <span data-ttu-id="70b41-1450">Per impostazione predefinita, Individuazione automatica preferisce l'UPN dell'account, se disponibile.</span><span class="sxs-lookup"><span data-stu-id="70b41-1450">By default, AutoDiscover prefers the account UPN, when available.</span></span>

- <span data-ttu-id="70b41-1451">È stato risolto un problema che causava il malfunzionamento della ricerca nei gruppi moderni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1451">Addressed an issue that caused users to see search failing against Modern Groups.</span></span>

- <span data-ttu-id="70b41-1452">È stato risolto un problema che causava agli utenti di Outlook di rimanere bloccati nello stato "Password necessaria" in alcuni scenari.</span><span class="sxs-lookup"><span data-stu-id="70b41-1452">Addressed an issue that caused Outlook users to get stuck in the "Needs Password" state in certain scenarios.</span></span>

- <span data-ttu-id="70b41-1453">È stato risolto un problema che causava la visualizzazione delle sale consigliate per le riunioni in orari al di fuori della disponibilità della sala.</span><span class="sxs-lookup"><span data-stu-id="70b41-1453">Addressed an issue that caused users to see room suggestions for meetings that occurred outside of that room's availability hours.</span></span>

- <span data-ttu-id="70b41-1454">È stato risolto un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1454">Addressed an issue that caused users to encounter "encryption algorithm is not supported" errors when sending an encrypted email.</span></span>

- <span data-ttu-id="70b41-1455">È stato risolto un problema per gli utenti non inglesi per cui la riga dell'oggetto di un messaggio di posta elettronica era incredibilmente piccola.</span><span class="sxs-lookup"><span data-stu-id="70b41-1455">Addressed an issue for non-English users where the subject line in a mail would be incredibly small.</span></span>

- <span data-ttu-id="70b41-1456">È stato risolto un problema per cui venivano visualizzate cartelle speciali duplicate create durante l'aggiunta di un account di Exchange secondario.</span><span class="sxs-lookup"><span data-stu-id="70b41-1456">Addressed an issue that caused some users to see duplicate special folders created when adding a secondary Exchange account.</span></span>

- <span data-ttu-id="70b41-1457">È stato risolto un problema che causava l'arresto anomalo provando a creare una regola da un messaggio di tipo "Conversazione non effettuata".</span><span class="sxs-lookup"><span data-stu-id="70b41-1457">Addressed an issue that caused users to experience a crash when attempting to create a rule from a "Missed Conversation" message.</span></span>

- <span data-ttu-id="70b41-1458">È stato risolto un problema relativo alla selezione dell'algoritmo SMIME.</span><span class="sxs-lookup"><span data-stu-id="70b41-1458">Corrected an issue with SMIME algorithm selection.</span></span>

- <span data-ttu-id="70b41-1459">È stato risolto un problema che causava la mancata visualizzazione dei suggerimenti per i criteri quando si usava un mittente alternativo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1459">Addressed an issue that caused Policy Tips to fail to display when using an alternate sender.</span></span>

- <span data-ttu-id="70b41-1460">È stato risolto un problema per cui gli utenti notavano una perdita di memoria nel processo di Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1460">Addressed an issue that caused users to observe a memory leak in the Outlook process.</span></span>

- <span data-ttu-id="70b41-1461">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1461">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

- <span data-ttu-id="70b41-1462">È stato risolto un problema a causa del quale non era talvolta possibile eseguire la ricerca della cartella corrente.</span><span class="sxs-lookup"><span data-stu-id="70b41-1462">Addressed an issue that caused current folder search to intermittently fail.</span></span>

- <span data-ttu-id="70b41-1463">È stato risolto un problema che causava la visualizzazione di errori di autenticazione per alcuni utenti quando provavano a recuperare le impostazioni del cloud per Outlook.</span><span class="sxs-lookup"><span data-stu-id="70b41-1463">Addressed an issue that caused some users to encounter authentication errors when trying to retrieve their cloud settings for Outlook.</span></span>

- <span data-ttu-id="70b41-1464">È stato risolto un problema che causava il blocco dell'esperienza di Feedback sulla ricerca.</span><span class="sxs-lookup"><span data-stu-id="70b41-1464">Addressed an issue that caused a hang in the Search Feedback experience.</span></span>

- <span data-ttu-id="70b41-1465">È stato risolto un problema che causava un arresto anomalo durante l'elaborazione delle risposte del servizio di individuazione automatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1465">Addressed an issue that caused users to experience a crash when processing some AutoDiscover responses.</span></span>

- <span data-ttu-id="70b41-1466">È stato risolto un problema che causava arresti anomali intermittenti quando si aggiornavano le informazioni sulla presenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1466">Addressed an issue that caused users to experience intermittent crashes when updating presence information.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="70b41-1467">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1467">PowerPoint</span></span>

- <span data-ttu-id="70b41-1468">È stato risolto un problema per cui alcuni componenti aggiuntivi generavano errori imprevisti attorno alle forme nei grafici.</span><span class="sxs-lookup"><span data-stu-id="70b41-1468">Fixed an issue where some add-ins would throw unexpected errors around shapes in charts.</span></span>

- <span data-ttu-id="70b41-1469">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1469">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-1470">Questa modifica ripristina il nome accessibile per i controlli video di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1470">This change restores the accessible name for PowerPoint video controls.</span></span>

- <span data-ttu-id="70b41-1471">È stato risolto un problema che impediva l'avvio di alcune animazioni.</span><span class="sxs-lookup"><span data-stu-id="70b41-1471">We fixed an issue which could prevent some animations from starting.</span></span>

- <span data-ttu-id="70b41-1472">Abbiamo risolto un problema che provoca la creazione di schemi duplicati quando si copia una diapositiva da una presentazione a un'altra.</span><span class="sxs-lookup"><span data-stu-id="70b41-1472">We fixed an issue when copying a slide from one presentation to another might create duplicate masters.</span></span>

- <span data-ttu-id="70b41-1473">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata</span><span class="sxs-lookup"><span data-stu-id="70b41-1473">Files with new modern comments will show a yellow warning if opened in unsupported version</span></span>

- <span data-ttu-id="70b41-1474">Correzione per l'affidabilità: è stato risolto un problema per cui il componente aggiuntivo di terze parti poteva causare l'arresto anomalo di PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1474">Reliability fix: Fixed an issue where third party add-in might crash PowerPoint.</span></span>

- <span data-ttu-id="70b41-1475">È stato risolto un problema per cui i caratteri katakana ridotti non ruotavano correttamente nelle caselle di testo verticali in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1475">Fixed an issue where half-width katakana characters were not rotating properly when in vertical text boxes in PowerPoint.</span></span>

### <a name="project"></a><span data-ttu-id="70b41-1476">Project</span><span class="sxs-lookup"><span data-stu-id="70b41-1476">Project</span></span>

- <span data-ttu-id="70b41-1477">È stato risolto un problema per consentire agli utenti di Windows 7 di aprire i progetti da Project Web App e dai siti di SharePoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1477">Fixed an issue to enable users on Windows 7 to be able to open projects from Project Web App and SharePoint sites.</span></span>

- <span data-ttu-id="70b41-1478">È stato rilevato un problema per cui gli utenti visualizzavano diversi messaggi quando aprivano un progetto di sola lettura.</span><span class="sxs-lookup"><span data-stu-id="70b41-1478">Identified an issue where users could get several messages when opening a read-only project.</span></span>

- <span data-ttu-id="70b41-1479">Il comando Livella tutte non risolve correttamente una sovrassegnazione della risorsa.</span><span class="sxs-lookup"><span data-stu-id="70b41-1479">Level All command doesn't properly resolve a resource overallocation.</span></span>

- <span data-ttu-id="70b41-1480">In caso di un'assegnazione con nessun lavoro su un'attività, non era possibile contrassegnare l'attività come completata e veniva visualizzata sempre al 99% del completamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1480">An assignment with zero work on a task, the task may be unable to be marked complete and will always show up at 99%.</span></span>

### <a name="visio"></a><span data-ttu-id="70b41-1481">Visio</span><span class="sxs-lookup"><span data-stu-id="70b41-1481">Visio</span></span>

- <span data-ttu-id="70b41-1482">L'esportazione in SVG da Visio non funzionava per numerose forme.</span><span class="sxs-lookup"><span data-stu-id="70b41-1482">Export as SVG from Visio was failing for a variety of shapes.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-1483">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1483">Word</span></span>

- <span data-ttu-id="70b41-1484">Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.</span><span class="sxs-lookup"><span data-stu-id="70b41-1484">This change will lead to performance improvements in opening documents using Word.</span></span>

- <span data-ttu-id="70b41-1485">I collegamenti di immagini cid: dai messaggi di Outlook ora possono essere interrotti quando richiesto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1485">The links of cid: images from Outlook messages can now be successfully broken when requested.</span></span>

- <span data-ttu-id="70b41-1486">È stato risolto un problema che poteva causare problemi di ridimensionamento durante la stampa su stampanti Deskjet.</span><span class="sxs-lookup"><span data-stu-id="70b41-1486">We fixed an issue which could have caused scaling issues when printing to Deskjet printers.</span></span>

- <span data-ttu-id="70b41-1487">Abbiamo risolto un problema relativo alle revisioni che a volte generavano un ciclo infinito.</span><span class="sxs-lookup"><span data-stu-id="70b41-1487">We fixed an issue in track changes that sometimes go into infinite loop.</span></span>

- <span data-ttu-id="70b41-1488">Sono stati risolti diversi problemi che causavano il blocco dell'app durante la chiusura.</span><span class="sxs-lookup"><span data-stu-id="70b41-1488">Fixed various issues where the app may hang on shutdown.</span></span> <span data-ttu-id="70b41-1489">Sono stati risolti anche alcuni arresti anomali correlati ai componenti aggiuntivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1489">Also fixes certain add-in related crashes.</span></span>

### <a name="office-suite"></a><span data-ttu-id="70b41-1490">Applicazioni Office</span><span class="sxs-lookup"><span data-stu-id="70b41-1490">Office Suite</span></span>

- <span data-ttu-id="70b41-1491">Risolto un problema di scorretta identificazione del nome della nuova era "Reiwa" in caratteri Hiragana e Kanji come espressione con errori di ortografia o grammatica.</span><span class="sxs-lookup"><span data-stu-id="70b41-1491">Fixed an issue of incorrectly identifying the new era name “Reiwa” in Hiragana and Kanji as a misspelled or ungrammatical expression.</span></span>

- <span data-ttu-id="70b41-1492">È stato risolto un problema che causava la visualizzazione del messaggio: "C'è un problema che impedisce la condivisione di questo elemento" quando si provava a condividere i file archiviati in SharePoint 2016.</span><span class="sxs-lookup"><span data-stu-id="70b41-1492">Fixed an issue which caused users to get this message "Sorry, something is preventing us from sharing this" when trying to share files stored on SharePoint 2016.</span></span>

- <span data-ttu-id="70b41-1493">È stato risolto un problema che potrebbe causare la perdita di dati in sessioni che implicano sia la creazione condivisa che la modifica offline in PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1493">Fixed issue that could cause data loss in sessions that involved both coauthoring and offline editing in PowerPoint.</span></span>

- <span data-ttu-id="70b41-1494">Si tratta di una correzione per un problema che causava un arresto anomalo all'apertura di un file.</span><span class="sxs-lookup"><span data-stu-id="70b41-1494">This is a fix for a crash that users could hit on opening a file.</span></span>

- <span data-ttu-id="70b41-1495">Può causare un errore in PowerPoint quando si prova a presentare online.</span><span class="sxs-lookup"><span data-stu-id="70b41-1495">Prevents PowerPoint users from running into error when trying to Present Online.</span></span>

- <span data-ttu-id="70b41-1496">In alcuni casi, un file di SharePoint supportato dal motore di sincronizzazione poteva mostrare "Salvato" senza avere effettivamente salvato alcuna modifica, comportando una perdita di dati.</span><span class="sxs-lookup"><span data-stu-id="70b41-1496">In some instances, a sync-engine backed sharepoint file could show 'Saved' but not have actually saved any changes, resulting in data loss.</span></span>

- <span data-ttu-id="70b41-1497">È stato risolto un problema per cui gli utenti non potevano salvare documenti di Word, Excel e PowerPoint.</span><span class="sxs-lookup"><span data-stu-id="70b41-1497">Resolved an issue where users may be unable to save Word, Excel, and PowerPoint documents.</span></span> <span data-ttu-id="70b41-1498">Questo problema interessa gli utenti che creano un nuovo file e visualizzano la finestra di dialogo "Salva con nome" dopo aver fatto clic sull'icona Salva o aver premuto CTRL+S.</span><span class="sxs-lookup"><span data-stu-id="70b41-1498">This issue affects users that create a new file and bring up the "Save as Dialog" option after clicking on the Save icon or pressing Ctrl + S.</span></span>

- <span data-ttu-id="70b41-1499">È stato risolto un problema di prestazioni in Windows 7 per cui la raccolta Inserisci forme sulla barra multifunzione in tutte le app veniva visualizzata dopo circa 4 secondi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1499">Fixed a perf issue on Win7 where the insert shapes gallery from the ribbon in all apps took approximately 4 seconds to appear.</span></span>

- <span data-ttu-id="70b41-1500">È stato risolto un bug per cui le informazioni sull'accessibilità non venivano visualizzate nell'area informazioni della visualizzazione backstage.</span><span class="sxs-lookup"><span data-stu-id="70b41-1500">Fixed a bug where accessibility information was not being displayed in the Info Place slab of the backstage.</span></span>

- <span data-ttu-id="70b41-1501">Migliora l'affidabilità del processo di aggiornamento di Office rispetto all'integrità del Registro di sistema.</span><span class="sxs-lookup"><span data-stu-id="70b41-1501">Improves reliability of the Office update process concerning registry integrity.</span></span>

- <span data-ttu-id="70b41-1502">È stato risolto un problema per cui gli aggiornamenti di Office potrebbero inaspettatamente scaricare file dalla rete CDN di Office anziché dall'origine prevista, ad esempio una condivisione locale o di rete o la posizione specificata da Configuration Manager.</span><span class="sxs-lookup"><span data-stu-id="70b41-1502">Resolved an issue where Office updates may have unexpectedly downloaded files from the Office CDN instead of the intended source, such as a local or network share, or Configuration Manager-provided location.</span></span>

- <span data-ttu-id="70b41-1503">È stato risolto un problema per cui i messaggi di aggiornamento di Office vengono visualizzati in una lingua diversa dal previsto.</span><span class="sxs-lookup"><span data-stu-id="70b41-1503">Fixed an issue where Office update messages appear in a different language than expected.</span></span> <span data-ttu-id="70b41-1504">In futuro, i messaggi di aggiornamento di Office corrisponderanno correttamente alla lingua di visualizzazione di Windows.</span><span class="sxs-lookup"><span data-stu-id="70b41-1504">Going forward, Office update messages will correctly match the Windows display language.</span></span>

- <span data-ttu-id="70b41-1505">È stato risolto un problema per cui, in alcuni casi, un aggiornamento non viene applicato se l'utente non è un amministratore e l'account di sistema non dispone della connettività di rete.</span><span class="sxs-lookup"><span data-stu-id="70b41-1505">Resolved an issue where an update would not apply in certain cases where the user is not an administrator and the System account did not have network connectivity.</span></span>

- <span data-ttu-id="70b41-1506">In alcuni casi, i tasti di scelta rapida di Office scompaiono dopo un aggiornamento.</span><span class="sxs-lookup"><span data-stu-id="70b41-1506">In certain circumstances, Office shortcuts may disappear following an update.</span></span> <span data-ttu-id="70b41-1507">Questo aggiornamento migliora l'affidabilità durante la pubblicazione dei tasti scelta rapida di Office.</span><span class="sxs-lookup"><span data-stu-id="70b41-1507">This update improves reliability when publishing of Office shortcuts.</span></span>

- <span data-ttu-id="70b41-1508">È stato risolto un problema per cui gli aggiornamenti potrebbero essere stati bloccati in modo imprevisto sulle reti a consumo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1508">Corrected an issue where updates may have been unexpectedly blocked on metered networks.</span></span>

- <span data-ttu-id="70b41-1509">È stato risolto un bug nell'impostazione della scadenza degli aggiornamenti in ODT e Criteri di gruppo, per cui la data di scadenza relativa funziona solo la prima volta che viene impostata. La correzione abilita la scadenza relativa per gli aggiornamenti successivi.</span><span class="sxs-lookup"><span data-stu-id="70b41-1509">Fix to bug in ODT and GPO Update Deadline setting where relative deadline only works the first time it is set, the fix enables the relative deadline for subsequent updates.</span></span>

- <span data-ttu-id="70b41-1510">È stata migliorata l'affidabilità durante il download degli aggiornamenti di Office quando si riprendono download che potrebbero essere stati interrotti in precedenza.</span><span class="sxs-lookup"><span data-stu-id="70b41-1510">Improved reliability when downloading Office updates by resuming downloads which may have been previously interrupted.</span></span>

- <span data-ttu-id="70b41-1511">Sono stati risolti dei problemi relativi alla proprietà di adattamento automatico della Casella di testo/Forma nei plug-in di terze parti.</span><span class="sxs-lookup"><span data-stu-id="70b41-1511">Addressed issues related to Textbox/Shape Autofit property in third-party plug-ins.</span></span>

- <span data-ttu-id="70b41-1512">È stato risolto un problema per cui visualizzazioni ampie degli alberi potrebbero comportare un arresto anomalo.</span><span class="sxs-lookup"><span data-stu-id="70b41-1512">We fixed an issue where large tree views could result in a crash.</span></span>

- <span data-ttu-id="70b41-1513">Per proteggere la sicurezza dei clienti di Office, gli aggiornamenti di Microsoft Office sono ora firmati esclusivamente con l'algoritmo SHA-2.</span><span class="sxs-lookup"><span data-stu-id="70b41-1513">To protect Office customers' security, Microsoft Office updates are now signed using the SHA-2 algorithm exclusively.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1902-january-14"></a><span data-ttu-id="70b41-1515">Versione 1902: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="70b41-1515">Version 1902: January 14</span></span>
<span data-ttu-id="70b41-1516">*Versione 1902 (build 11328.20512)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1516">*Version 1902 (Build 11328.20512)*</span></span>

<span data-ttu-id="70b41-1517">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1517">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

### <a name="resolved-issues"></a><span data-ttu-id="70b41-1519">Problemi risolti</span><span class="sxs-lookup"><span data-stu-id="70b41-1519">Resolved issues</span></span>
### <a name="excel"></a><span data-ttu-id="70b41-1520">Excel</span><span class="sxs-lookup"><span data-stu-id="70b41-1520">Excel</span></span>

- <span data-ttu-id="70b41-1521">È stato risolto un problema di mancato caricamento della personalizzazione della barra multifunzione all'apertura di una cartella di lavoro incorporata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1521">Resolved an issue with ribbon customization not loading when opening embedded workbook.</span></span>

### <a name="outlook"></a><span data-ttu-id="70b41-1522">Outlook</span><span class="sxs-lookup"><span data-stu-id="70b41-1522">Outlook</span></span>

- <span data-ttu-id="70b41-1523">Risolve un problema che causava la visualizzazione di errori del tipo "Algoritmo di crittografia non supportato" quando veniva inviato un messaggio di posta elettronica crittografato.</span><span class="sxs-lookup"><span data-stu-id="70b41-1523">Addresses an issue that caused users to encounter "encryption algorithm is not supporte" errors when sending an encrypted email.</span></span>

### <a name="powerpoint"></a><span data-ttu-id="70b41-1524">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="70b41-1524">PowerPoint</span></span>

- <span data-ttu-id="70b41-1525">I file con nuovi commenti moderni mostreranno un avviso di colore giallo se aperti in una versione non supportata.</span><span class="sxs-lookup"><span data-stu-id="70b41-1525">Files with new modern comments will show a yellow warning if opened in unsupported version.</span></span>

### <a name="word"></a><span data-ttu-id="70b41-1526">Word</span><span class="sxs-lookup"><span data-stu-id="70b41-1526">Word</span></span>

- <span data-ttu-id="70b41-1527">Questa modifica porterà miglioramenti delle prestazioni nell'apertura di documenti tramite Word.</span><span class="sxs-lookup"><span data-stu-id="70b41-1527">This change will lead to performance improvements in opening documents using Word.</span></span>


[//]: # (DO NOT REMOVE BUGDETAILS CONTENT END)

## <a name="version-1808-january-14"></a><span data-ttu-id="70b41-1529">Versione 1808: 14 gennaio</span><span class="sxs-lookup"><span data-stu-id="70b41-1529">Version 1808: January 14</span></span>
<span data-ttu-id="70b41-1530">*Versione 1808 (build 10730.20432)*</span><span class="sxs-lookup"><span data-stu-id="70b41-1530">*Version 1808 (Build 10730.20432)*</span></span>

<span data-ttu-id="70b41-1531">Aggiornamenti della sicurezza elencati [qui](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span><span class="sxs-lookup"><span data-stu-id="70b41-1531">Security updates listed [here](https://docs.microsoft.com/officeupdates/microsoft365-apps-security-updates)</span></span>

[//]: # (DO NOT REMOVE BUGDETAILS CONTENT START)

> [!NOTE]
> <span data-ttu-id="70b41-1533">Se si ha bisogno di assistenza per un problema relativo all'utilizzo di Office, è consigliabile pubblicare una domanda sul [forum della community Microsoft](https://answers.microsoft.com/) o nella [community IT](https://techcommunity.microsoft.com/) oppure è possibile contattare il [supporto tecnico](https://support.microsoft.com/contactus).</span><span class="sxs-lookup"><span data-stu-id="70b41-1533">If you need help with an issue with using Office, we recommend that you post your question on [Microsoft's Answers forum](https://answers.microsoft.com/) or [Tech Community](https://techcommunity.microsoft.com/), or you can contact [support](https://support.microsoft.com/contactus).</span></span>


[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT START)
[//]: # (|Win32|DC|Production| |16.0.13127.21216|version-2008-february-09|)
[//]: # (|Win32|DC|Production| |16.0.13127.21064|version-2008-january-12|)
[//]: # (|Win32|DC|Production| |16.0.12527.21416|version-2002-december-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.21330|version-2002-november-10|)
[//]: # (|Win32|DC|Production| |16.0.12527.21236|version-2002-october-13|)
[//]: # (|Win32|DC|Production| |16.0.12527.21104|version-2002-september-08|)
[//]: # (|Win32|DC|Production| |16.0.12527.20988|version-2002-august-11|)
[//]: # (|Win32|DC|Production| |16.0.12527.20880|version-2002-july-14|)
[//]: # (DO NOT MODIFY ADMIN CENTER METADATA CONTENT END)
