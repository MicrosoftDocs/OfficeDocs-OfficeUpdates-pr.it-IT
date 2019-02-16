---
<span data-ttu-id="59d4d-101">title: "note sulla versione per Office insiders" ms. Author: andrewmo Author: Mikho Manager: andrewmo ms. Date: 2/15/2019 ms. audience: Win32 Fast ms. Topic: Reference ms. Service: O365-ProPlus-localization_priority: Critical ms. Collection: RelNotes_ProPlus Description: "fornisce agli addetti ai lavori un pubblico veloce con l'elenco più recente di nuove funzionalità chiave, correzioni o problemi noti</span><span class="sxs-lookup"><span data-stu-id="59d4d-101">title: "Release Notes for Office Insiders" ms.author: andrewmo author: mikho manager: andrewmo ms.date: 2/15/2019 ms.audience: Win32 Fast ms.topic: reference ms.service: o365-proplus- localization_priority: Critical ms.collection: RelNotes_ProPlus description: "Provides Insiders Fast audience with the latest list of key new features, fixes or known issues</span></span>
---

# <a name="release-notes-for-office-insiders"></a><span data-ttu-id="59d4d-102">Note sulla versione per gli addetti ai lavori di Office</span><span class="sxs-lookup"><span data-stu-id="59d4d-102">Release Notes for Office Insiders</span></span>

<span data-ttu-id="59d4d-p101">In questo articolo sono contenute le note sulla versione per le build inSider di Word, Excel, PowerPoint, Outlook, Access e Project per Windows desktop. Ogni settimana, verranno evidenziate le nuove funzionalità, le correzioni importanti e gli eventuali problemi significativi che è necessario conoscere. Si noti che spesso si tirano fuori le caratteristiche (e talvolta anche le correzioni) agli addetti ai lavori in un periodo di tempo. In questo modo, è possibile garantire che le operazioni funzionino senza problemi prima di rilasciare la funzionalità a un gruppo di destinatari più ampio. Quindi, se non vedi qualcosa descritto in basso, non preoccuparti di averlo alla fine.</span><span class="sxs-lookup"><span data-stu-id="59d4d-p101">This article contains release notes for Insider builds of Word, Excel, PowerPoint, Outlook, Access, and Project for Windows desktop. Every week, we’ll highlight interesting new features, important fixes, and any significant issues we want you to know about. Note that we often roll out features (and sometimes even fixes) to Insiders over a period of time. This allows us to ensure that things are working smoothly before releasing the feature to a wider audience. So, if you don’t see something described below, don't worry you'll get it eventually.</span></span>  

## <a name="february-12-2019-version-1902-build-1133020014"></a><span data-ttu-id="59d4d-108">Febbraio 12 2019 versione 1902 (Build 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="59d4d-108">February 12 2019 Version 1902 (build 11330.20014)</span></span>

## <a name="whats-new"></a><span data-ttu-id="59d4d-109">Novità:</span><span class="sxs-lookup"><span data-stu-id="59d4d-109">What's New:</span></span>

### <a name="powerpoint"></a><span data-ttu-id="59d4d-110">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="59d4d-110">PowerPoint</span></span>


### <a name="morph-transition-enhancements---morph-by-name"></a><span data-ttu-id="59d4d-111">Miglioramenti alla transizione del Morph-Morph per nome</span><span class="sxs-lookup"><span data-stu-id="59d4d-111">Morph Transition Enhancements - Morph by Name</span></span>

<span data-ttu-id="59d4d-112">Specificare le forme che si desidera morph</span><span class="sxs-lookup"><span data-stu-id="59d4d-112">Specify the shapes you want to morph</span></span>

#### <a name="getting-started"></a><span data-ttu-id="59d4d-113">Guida introduttiva:</span><span class="sxs-lookup"><span data-stu-id="59d4d-113">Getting Started:</span></span>

- <span data-ttu-id="59d4d-114">Per ottenere morph per il trattamento di due oggetti come lo stesso oggetto, l'utente può rinominare le forme utilizzando il riquadro di selezione.</span><span class="sxs-lookup"><span data-stu-id="59d4d-114">To get Morph to treat two objects as the same object, the user can rename the shapes using the Selection Pane.</span></span>
- <span data-ttu-id="59d4d-p102">Il nome deve essere precostituito da "!!" (due punti esclamativi) per Morph per utilizzarlo per ignorare il comportamento predefinito di corrispondenza, ad esempio "! Nome</span><span class="sxs-lookup"><span data-stu-id="59d4d-p102">The name must be prefaced with “!!” (two exclamation points) for Morph to use it to override our default matching behavior, e.g. “!!Name”</span></span>
- <span data-ttu-id="59d4d-p103">Gli utenti possono continuare a rinominare forme con qualsiasi nome che non inizia con "!!" senza preoccuparsi che cambierà la modalità di funzionamento di morph</span><span class="sxs-lookup"><span data-stu-id="59d4d-p103">Users can continue to rename shapes with any name that doesn’t start with “!!” without worrying that it will change the way Morph works</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="59d4d-119">Scenari da provare:</span><span class="sxs-lookup"><span data-stu-id="59d4d-119">Scenarios to Try:</span></span>

- <span data-ttu-id="59d4d-120">Inserire una forma in una diapositiva, diciamo rettangolo</span><span class="sxs-lookup"><span data-stu-id="59d4d-120">Insert a Shape in a slide, let's say Rectangle</span></span>
- <span data-ttu-id="59d4d-121">Creare una nuova diapositiva</span><span class="sxs-lookup"><span data-stu-id="59d4d-121">Create a new slide</span></span>
- <span data-ttu-id="59d4d-122">Inserire una forma diversa nella seconda diapositiva, diciamo triangolo</span><span class="sxs-lookup"><span data-stu-id="59d4d-122">Insert a different shape in the 2nd slide, let's say Triangle</span></span>
- <span data-ttu-id="59d4d-123">Aprire SelectionPane, rinominare il rettangolo nella diapositiva 1 in "!! Shape "e Rinomina il triangolo nella diapositiva 2 in"! forma</span><span class="sxs-lookup"><span data-stu-id="59d4d-123">Open SelectionPane, rename the Rectangle in slide 1 to "!!shape", and rename the Triangle in slide 2 to "!!shape"</span></span>
- <span data-ttu-id="59d4d-124">Applicare morph sulla diapositiva 2nd</span><span class="sxs-lookup"><span data-stu-id="59d4d-124">Apply Morph on the 2nd slide</span></span>

</BR>

### <a name="morph-transition-enhancements---smartart"></a><span data-ttu-id="59d4d-125">Miglioramenti alla transizione di morph-SmartArt</span><span class="sxs-lookup"><span data-stu-id="59d4d-125">Morph Transition Enhancements - SmartArt</span></span>

<span data-ttu-id="59d4d-126">Morph SmartArt con transizioni più fluide</span><span class="sxs-lookup"><span data-stu-id="59d4d-126">SmartArt morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="59d4d-127">Guida introduttiva:</span><span class="sxs-lookup"><span data-stu-id="59d4d-127">Getting Started:</span></span>

<span data-ttu-id="59d4d-128">Utilizzare morph nello stesso modo in cui si farebbe con SmartArt</span><span class="sxs-lookup"><span data-stu-id="59d4d-128">Use Morph the same way you would with SmartArt</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="59d4d-129">Scenari da provare:</span><span class="sxs-lookup"><span data-stu-id="59d4d-129">Scenarios to Try:</span></span>

- <span data-ttu-id="59d4d-130">Inserire un SmartArt in una diapositiva</span><span class="sxs-lookup"><span data-stu-id="59d4d-130">Insert a SmartArt in a slide</span></span>
- <span data-ttu-id="59d4d-131">Duplica la diapositiva</span><span class="sxs-lookup"><span data-stu-id="59d4d-131">Duplicate the Slide</span></span>
- <span data-ttu-id="59d4d-132">Ridimensiona/cambia/sposta l'SmartArt sulla diapositiva duplicata</span><span class="sxs-lookup"><span data-stu-id="59d4d-132">Resize/Change/Move the SmartArt on the duplicated slide</span></span>
- <span data-ttu-id="59d4d-133">Applicazione del morph sulla diapositiva duplicata</span><span class="sxs-lookup"><span data-stu-id="59d4d-133">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="morph-transition-enhancements---tables"></a><span data-ttu-id="59d4d-134">Miglioramenti alla transizione del morph-tabelle</span><span class="sxs-lookup"><span data-stu-id="59d4d-134">Morph Transition Enhancements - Tables</span></span>

<span data-ttu-id="59d4d-135">Le tabelle si trasformano con transizioni più fluide</span><span class="sxs-lookup"><span data-stu-id="59d4d-135">Tables morph with smoother transitions</span></span>

#### <a name="getting-started"></a><span data-ttu-id="59d4d-136">Guida introduttiva:</span><span class="sxs-lookup"><span data-stu-id="59d4d-136">Getting Started:</span></span>
<span data-ttu-id="59d4d-137">Utilizzare morph nello stesso modo in cui si utilizzano le tabelle</span><span class="sxs-lookup"><span data-stu-id="59d4d-137">Use Morph the same way you would with tables</span></span>

#### <a name="scenarios-to-try"></a><span data-ttu-id="59d4d-138">Scenari da provare:</span><span class="sxs-lookup"><span data-stu-id="59d4d-138">Scenarios to Try:</span></span>

- <span data-ttu-id="59d4d-139">Inserire una tabella in una diapositiva</span><span class="sxs-lookup"><span data-stu-id="59d4d-139">Insert a Table in a slide</span></span>
- <span data-ttu-id="59d4d-140">Duplica la diapositiva</span><span class="sxs-lookup"><span data-stu-id="59d4d-140">Duplicate the slide</span></span>
- <span data-ttu-id="59d4d-141">Ridimensiona/cambia/sposta la tabella sulla diapositiva duplicata</span><span class="sxs-lookup"><span data-stu-id="59d4d-141">Resize/Change/Move the Table on the duplicated slide</span></span>
- <span data-ttu-id="59d4d-142">Applicazione del morph sulla diapositiva duplicata</span><span class="sxs-lookup"><span data-stu-id="59d4d-142">Apply Morph on the duplicated slide</span></span>

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a><span data-ttu-id="59d4d-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span><span class="sxs-lookup"><span data-stu-id="59d4d-143">Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio</span></span>

### <a name="seamlessly-switch-between-accounts"></a><span data-ttu-id="59d4d-144">Passare senza problemi tra gli account</span><span class="sxs-lookup"><span data-stu-id="59d4d-144">Seamlessly Switch Between Accounts</span></span>

<span data-ttu-id="59d4d-p104">Il nuovo account Manager Visualizza tutti gli account personali e di lavoro in un'unica posizione, nonché il controllo del passaggio tra di essi. Questa esperienza aggiornata rende chiaro come è stato effettuato l'accesso e ora è possibile alternare tra lavoro e account personali senza dover prima disconnettersi o gestire le finestre di dialogo complesse.</span><span class="sxs-lookup"><span data-stu-id="59d4d-p104">The new account manager shows all of your work and personal accounts in one place, and puts you in control of switching between them. This updated experience makes it clear how you're logged in, and now you can toggle between work and personal accounts without having to sign out first or deal with complex dialogs.</span></span>



#### <a name="scenarios-to-try"></a><span data-ttu-id="59d4d-147">Scenari da provare:</span><span class="sxs-lookup"><span data-stu-id="59d4d-147">Scenarios to Try:</span></span>
- <span data-ttu-id="59d4d-148">Passare da un account all'altra</span><span class="sxs-lookup"><span data-stu-id="59d4d-148">Switch between accounts</span></span>
- <span data-ttu-id="59d4d-149">Aggiungere un nuovo account [Nota: si consiglia di accedere prima a file | Account | Servizi connessi e rimuovere tutti i servizi personali connessi a account di lavoro o viceversa]</span><span class="sxs-lookup"><span data-stu-id="59d4d-149">Add a new account [Note: you may want to first go to File | Account | Connected Services and remove any personal services connected to work accounts or vice versa]</span></span>
- <span data-ttu-id="59d4d-150">DisConnettersi da un account</span><span class="sxs-lookup"><span data-stu-id="59d4d-150">Sign out from an account</span></span>
</BR>

## <a name="notable-fixes"></a><span data-ttu-id="59d4d-151">Correzioni importanti:</span><span class="sxs-lookup"><span data-stu-id="59d4d-151">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="59d4d-152">Word</span><span class="sxs-lookup"><span data-stu-id="59d4d-152">Word</span></span> 
- <span data-ttu-id="59d4d-153">È stato risolto un problema con l'anteprima di contesto per le tabelle & immagini</span><span class="sxs-lookup"><span data-stu-id="59d4d-153">We fixed an issue with context preview for tables & images</span></span>

### <a name="excel"></a><span data-ttu-id="59d4d-154">Excel</span><span class="sxs-lookup"><span data-stu-id="59d4d-154">Excel</span></span>
- <span data-ttu-id="59d4d-155">È stato risolto un problema a causa del quale il testo nel campo di ricerca filtro automatico è bianco nel tema nero</span><span class="sxs-lookup"><span data-stu-id="59d4d-155">We fixed an issue where text in autofilter Search field is white in Black theme</span></span>
- <span data-ttu-id="59d4d-156">È stato risolto un problema dell'interfaccia utente di consenso con nuovo componente aggiuntivo di Office</span><span class="sxs-lookup"><span data-stu-id="59d4d-156">We fixed a consent UI issue with New Office Add-in</span></span>

### <a name="powerpoint"></a><span data-ttu-id="59d4d-157">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="59d4d-157">PowerPoint</span></span>
- <span data-ttu-id="59d4d-158">È stato risolto un problema con l'estensione automatica della visualizzazione quando si presentano presentazioni su laptop o tablet.</span><span class="sxs-lookup"><span data-stu-id="59d4d-158">We fixed an issue with automatically extending display when presenting SlideShows on laptops or tablets.</span></span>

### <a name="outlook"></a><span data-ttu-id="59d4d-159">Outlook</span><span class="sxs-lookup"><span data-stu-id="59d4d-159">Outlook</span></span>
- <span data-ttu-id="59d4d-160">È stato risolto un problema con la visualizzazione del pulsante Invia a OneNote</span><span class="sxs-lookup"><span data-stu-id="59d4d-160">We fixed an issue with the Send to OneNote button display</span></span>

### <a name="access"></a><span data-ttu-id="59d4d-161">Access</span><span class="sxs-lookup"><span data-stu-id="59d4d-161">Access</span></span>
- <span data-ttu-id="59d4d-162">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-162">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="59d4d-163">Project</span><span class="sxs-lookup"><span data-stu-id="59d4d-163">Project</span></span>
- <span data-ttu-id="59d4d-164">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-164">Various performance and stability fixes</span></span>


</BR></BR>
## <a name="february-9-2019-version-1902-build-1133020014"></a><span data-ttu-id="59d4d-165">Febbraio 9 2019 versione 1902 (Build 11330,20014)</span><span class="sxs-lookup"><span data-stu-id="59d4d-165">February 9 2019 Version 1902 (build 11330.20014)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="59d4d-166">Correzioni importanti:</span><span class="sxs-lookup"><span data-stu-id="59d4d-166">Notable Fixes:</span></span>

### <a name="word"></a><span data-ttu-id="59d4d-167">Word</span><span class="sxs-lookup"><span data-stu-id="59d4d-167">Word</span></span> 
- <span data-ttu-id="59d4d-168">È stato risolto un problema a causa del quale non è stato possibile applicare alcuni stili personalizzati a Word online</span><span class="sxs-lookup"><span data-stu-id="59d4d-168">We fixed an issue where some customized styles could not be applied to word online</span></span>
- <span data-ttu-id="59d4d-169">Sono stati risolti i problemi di anteprima dei conTesti con oggetti Rich in Word</span><span class="sxs-lookup"><span data-stu-id="59d4d-169">We fixed Context Preview issues with rich objects in Word</span></span>
- <span data-ttu-id="59d4d-170">È stato risolto un problema a causa del quale gli elenchi di incollatura potrebbero causare un arresto anomalo di Word</span><span class="sxs-lookup"><span data-stu-id="59d4d-170">We fixed an issue where pasting lists  would result in Word crashing</span></span>

### <a name="excel"></a><span data-ttu-id="59d4d-171">Excel</span><span class="sxs-lookup"><span data-stu-id="59d4d-171">Excel</span></span>
- <span data-ttu-id="59d4d-172">È stato risolto un problema a causa del quale gli spazi accodati dopo i formati dei numeri non vengono più visualizzati quando non è presente alcun simbolo di valuta</span><span class="sxs-lookup"><span data-stu-id="59d4d-172">We fixed an issue where appended spaces after number formats are no longer showing when there is no currency symbol</span></span>
- <span data-ttu-id="59d4d-173">È stato risolto un problema relativo al rilevamento automatico delle scorte</span><span class="sxs-lookup"><span data-stu-id="59d4d-173">We fixed an issue with auto detect for stocks</span></span>

### <a name="powerpoint"></a><span data-ttu-id="59d4d-174">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="59d4d-174">PowerPoint</span></span>
- <span data-ttu-id="59d4d-175">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-175">Various performance and stability fixes</span></span>

### <a name="outlook"></a><span data-ttu-id="59d4d-176">Outlook</span><span class="sxs-lookup"><span data-stu-id="59d4d-176">Outlook</span></span>
- <span data-ttu-id="59d4d-177">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-177">Various performance and stability fixes</span></span>

### <a name="access"></a><span data-ttu-id="59d4d-178">Access</span><span class="sxs-lookup"><span data-stu-id="59d4d-178">Access</span></span>
- <span data-ttu-id="59d4d-179">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-179">Various performance and stability fixes</span></span>

### <a name="project"></a><span data-ttu-id="59d4d-180">Project</span><span class="sxs-lookup"><span data-stu-id="59d4d-180">Project</span></span>
- <span data-ttu-id="59d4d-181">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-181">Various performance and stability fixes</span></span>

</BR></BR>


## <a name="january-30-2019-version-1902-build-1132620000"></a><span data-ttu-id="59d4d-182">Gennaio 30, 2019 versione 1902 (Build 11326,20000)</span><span class="sxs-lookup"><span data-stu-id="59d4d-182">January 30, 2019 Version 1902 (build 11326.20000)</span></span>


## <a name="notable-fixes"></a><span data-ttu-id="59d4d-183">Correzioni importanti</span><span class="sxs-lookup"><span data-stu-id="59d4d-183">Notable Fixes</span></span>

### <a name="word"></a><span data-ttu-id="59d4d-184">Word</span><span class="sxs-lookup"><span data-stu-id="59d4d-184">Word</span></span> 
- <span data-ttu-id="59d4d-185">È stato risolto un problema con il ridimensionamento delle celle in una tabella Excel incorporata</span><span class="sxs-lookup"><span data-stu-id="59d4d-185">We fixed an issue with resizing cells in an embedded Excel table</span></span>
- <span data-ttu-id="59d4d-186">È stato risolto un problema relativo alla copia/incolla delle forme in un'area di disegno</span><span class="sxs-lookup"><span data-stu-id="59d4d-186">We fixed an issue with copy/paste of shapes in a Drawing Canvas</span></span>

### <a name="excel"></a><span data-ttu-id="59d4d-187">Excel</span><span class="sxs-lookup"><span data-stu-id="59d4d-187">Excel</span></span>
- <span data-ttu-id="59d4d-188">È stato risolto un problema relativo all'apertura di file da Excel Web App</span><span class="sxs-lookup"><span data-stu-id="59d4d-188">We fixed an issue with opening files from the Excel Web app</span></span>
- <span data-ttu-id="59d4d-189">È stato risolto un problema a causa del quale è stato salvato un file CSV. XLSX si è verificato un errore a causa della dimensione del nome di file</span><span class="sxs-lookup"><span data-stu-id="59d4d-189">We fixed an issue where saving a CSV file as .XLSX was failing due to file name size</span></span>
- <span data-ttu-id="59d4d-190">Il menu di scelta rapida è stato risolto per visualizzare le opzioni di menu di scelta rapida.</span><span class="sxs-lookup"><span data-stu-id="59d4d-190">We fixed the context menu to display the context menu options</span></span>

### <a name="powerpoint"></a><span data-ttu-id="59d4d-191">PowerPoint</span><span class="sxs-lookup"><span data-stu-id="59d4d-191">PowerPoint</span></span>
- <span data-ttu-id="59d4d-192">È stato corretto un oggetto rilasciato in cui gli utenti non sono stati in grado di utilizzare la combinazione di tasti CTRL + ALT + 7/Ctrl + Alt + 8 per immettere le parentesi quadre</span><span class="sxs-lookup"><span data-stu-id="59d4d-192">We fixed an issued where users were unable to use the keyboard shortcut ctrl+alt+7/ctrl+alt+8 to enter square brackets</span></span>
- <span data-ttu-id="59d4d-193">È stato risolto un problema a causa del quale l'inserimento di un video locale nel PPT ridurrebbe lo spazio su disco dell'unità' C'</span><span class="sxs-lookup"><span data-stu-id="59d4d-193">We fixed an issue where inserting a local video into the PPT would reduce the ‘C’ drive disk space</span></span>
- <span data-ttu-id="59d4d-194">È stato risolto il pulsante pubblica su Microsoft Stream che non è stato visualizzato ad alcuni utenti</span><span class="sxs-lookup"><span data-stu-id="59d4d-194">We fixed the Publish to Microsoft Stream button which was not displaying to some users</span></span>

### <a name="outlook"></a><span data-ttu-id="59d4d-195">Outlook</span><span class="sxs-lookup"><span data-stu-id="59d4d-195">Outlook</span></span>
- <span data-ttu-id="59d4d-196">È stato risolto un problema a causa del quale la visualizzazione attività nel calendario non indicava correttamente l'oggetto dell'attività.</span><span class="sxs-lookup"><span data-stu-id="59d4d-196">We fixed an issue where the task view in calendar was  not correctly showing the task subject</span></span>

### <a name="access"></a><span data-ttu-id="59d4d-197">Access</span><span class="sxs-lookup"><span data-stu-id="59d4d-197">Access</span></span>
- <span data-ttu-id="59d4d-198">È stato risolto un problema di scalabilità con i grafici</span><span class="sxs-lookup"><span data-stu-id="59d4d-198">We fixed a scaling issue with charts</span></span>

### <a name="project"></a><span data-ttu-id="59d4d-199">Project</span><span class="sxs-lookup"><span data-stu-id="59d4d-199">Project</span></span>
- <span data-ttu-id="59d4d-200">Varie correzioni per la stabilità e le prestazioni</span><span class="sxs-lookup"><span data-stu-id="59d4d-200">Various performance and stability fixes</span></span>
