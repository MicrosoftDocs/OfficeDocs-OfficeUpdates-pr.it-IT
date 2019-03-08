---
title: "note sulla versione per Office insiders" ms. Author: andrewmo Author: Mikho Manager: andrewmo ms. Date: 3/07/2019 ms. audience: Win32 Fast ms. Topic: Reference ms. Service: O365-ProPlus-localization_priority: Critical ms. Collection: RelNotes_ProPlus Description: "fornisce agli addetti ai lavori un pubblico veloce con l'elenco più recente di nuove funzionalità chiave, correzioni o problemi noti
---

# <a name="release-notes-for-office-insiders"></a>Note sulla versione per gli addetti ai lavori di Office

In questo articolo sono contenute le note sulla versione per le build inSider di Word, Excel, PowerPoint, Outlook, Access e Project per Windows desktop. Ogni settimana, verranno evidenziate le nuove funzionalità, le correzioni importanti e gli eventuali problemi significativi che è necessario conoscere. Si noti che spesso si tirano fuori le caratteristiche (e talvolta anche le correzioni) agli addetti ai lavori in un periodo di tempo. Ciò consente di assicurare che tutto funzioni correttamente prima di rilasciare la funzione ad un pubblico più ampio. Pertanto, anche se al momento non fossero disponibili descrizioni, prima o poi lo saranno.  

> [!NOTE]
> - Le note sulla versione sono registrate settimanalmente e possono essere una compilazione di più compilazioni. 
> - La data di pubblicazione delle note sulla versione potrebbe non corrispondere alla data di rilascio effettiva.

## <a name="march-1-2019"></a>1 marzo 2019 
Versione 1903 (Build 11414,20014)


## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema di crash che si è verificato quando si preme ' ESC ' quando si è in opzioni
- È stato risolto un problema con copia & incolla da Word a PowerPoint online

### <a name="excel"></a>Excel
- È stato risolto un problema a causa del quale la copia di una cella in Excel ha causato un utilizzo elevato della CPU quando è stato aperto un documento protetto

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema con le dimensioni dell'immagine della diapositiva quando si utilizza @Mentions in PowerPoint

### <a name="outlook"></a>Outlook
- È stato risolto un problema a causa del quale la ricerca di Outlook non ha rispettato l'ordinamento cronologico selezionato
- È stato risolto un problema a causa del quale il pulsante "Apri questa attività" della barra multifunzione del flusso di lavoro non rispondeva a determinate e-mail
- È stato risolto un problema a causa del quale Outlook non è stato chiaro nelle sale locali dopo che gli utenti hanno selezionato una sala disponibile in room Finder

### <a name="access"></a>Access
- È stato aggiornato il testo del messaggio che ha mostrato quando si confermano le tabelle di ricollegamento con un'origine dati
- È stata corretta la finestra di dialogo di importazione/esportazione salvata con testo bianco su sfondo bianco in tema scuro
- È stato risolto un problema a causa del quale gli utenti non sono stati in grado di impostare la proprietà del controllo visualizzazione per un campo Sì/No su TextBox nella struttura della tabella

### <a name="project"></a>Project
- Varie correzioni per la stabilità e le prestazioni

</BR></BR>



## <a name="february-15-2019"></a>15 febbraio 2019 
Versione 1903 (Build 11310,20016)

## <a name="whats-new"></a>Novità:

### <a name="powerpoint"></a>PowerPoint


### <a name="morph-transition-enhancements---morph-by-name"></a>Miglioramenti alla transizione del Morph-Morph per nome

Specificare le forme che si desidera morph

#### <a name="getting-started"></a>Guida introduttiva:

- Per ottenere morph per il trattamento di due oggetti come lo stesso oggetto, l'utente può rinominare le forme utilizzando il riquadro di selezione.
- Il nome deve essere precostituito da "!!" (due punti esclamativi) per Morph per utilizzarlo per ignorare il comportamento predefinito di corrispondenza, ad esempio "! Nome
- Gli utenti possono continuare a rinominare forme con qualsiasi nome che non inizia con "!!" senza preoccuparsi che cambierà la modalità di funzionamento di morph

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Inserire una forma in una diapositiva, diciamo rettangolo
- Creare una nuova diapositiva
- Inserire una forma diversa nella seconda diapositiva, diciamo triangolo
- Aprire SelectionPane, rinominare il rettangolo nella diapositiva 1 in "!! Shape "e Rinomina il triangolo nella diapositiva 2 in"! forma
- Applicare morph sulla diapositiva 2nd

</BR>

### <a name="morph-transition-enhancements---smartart"></a>Miglioramenti alla transizione di morph-SmartArt

Morph SmartArt con transizioni più fluide

#### <a name="getting-started"></a>Guida introduttiva:

Utilizzare morph nello stesso modo in cui si farebbe con SmartArt

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Inserire un SmartArt in una diapositiva
- Duplica la diapositiva
- Ridimensiona/cambia/sposta l'SmartArt sulla diapositiva duplicata
- Applicazione del morph sulla diapositiva duplicata

</BR>

### <a name="morph-transition-enhancements---tables"></a>Miglioramenti alla transizione del morph-tabelle

Le tabelle si trasformano con transizioni più fluide

#### <a name="getting-started"></a>Guida introduttiva:
Utilizzare morph nello stesso modo in cui si utilizzano le tabelle

#### <a name="scenarios-to-try"></a>Scenari da provare:

- Inserire una tabella in una diapositiva
- Duplica la diapositiva
- Ridimensiona/cambia/sposta la tabella sulla diapositiva duplicata
- Applicazione del morph sulla diapositiva duplicata

</BR>

### <a name="word-excel-powerpoint-onenote-access-project-publisher--visio"></a>Word, Excel, PowerPoint, OneNote, Access, Project, Publisher & Visio

### <a name="seamlessly-switch-between-accounts"></a>Passare senza problemi tra gli account

Il nuovo account Manager Visualizza tutti gli account personali e di lavoro in un'unica posizione, nonché il controllo del passaggio tra di essi. Questa esperienza aggiornata rende chiaro come è stato effettuato l'accesso e ora è possibile alternare tra lavoro e account personali senza dover prima disconnettersi o gestire le finestre di dialogo complesse.


![MeMock. png](Images/MeMock.png)

#### <a name="scenarios-to-try"></a>Scenari da provare:
- Passare da un account all'altra
- Aggiungere un nuovo account [Nota: si consiglia di accedere prima a file | Account | Servizi connessi e rimuovere tutti i servizi personali connessi a account di lavoro o viceversa]
- DisConnettersi da un account
</BR>

## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema con l'anteprima di contesto per le tabelle & immagini

### <a name="excel"></a>Excel
- È stato risolto un problema a causa del quale il testo nel campo di ricerca filtro automatico è bianco nel tema nero
- È stato risolto un problema dell'interfaccia utente di consenso con nuovo componente aggiuntivo di Office

### <a name="powerpoint"></a>PowerPoint
- È stato risolto un problema con l'estensione automatica della visualizzazione quando si presentano presentazioni su laptop o tablet.

### <a name="outlook"></a>Outlook
- È stato risolto un problema con la visualizzazione del pulsante Invia a OneNote

### <a name="access"></a>Access
- Varie correzioni per la stabilità e le prestazioni

### <a name="project"></a>Project
- Varie correzioni per la stabilità e le prestazioni


</BR></BR>
## <a name="february-11-2019"></a>11 febbraio 2019
Versione 1903 (Build 11330,20014)


## <a name="notable-fixes"></a>Correzioni importanti:

### <a name="word"></a>Word 
- È stato risolto un problema a causa del quale non è stato possibile applicare alcuni stili personalizzati a Word online
- Sono stati risolti i problemi di anteprima dei conTesti con oggetti Rich in Word
- È stato risolto un problema a causa del quale gli elenchi di incollatura potrebbero causare un arresto anomalo di Word

### <a name="excel"></a>Excel
- È stato risolto un problema a causa del quale gli spazi accodati dopo i formati dei numeri non vengono più visualizzati quando non è presente alcun simbolo di valuta
- È stato risolto un problema relativo al rilevamento automatico delle scorte

### <a name="powerpoint"></a>PowerPoint
- Varie correzioni per la stabilità e le prestazioni

### <a name="outlook"></a>Outlook
- Varie correzioni per la stabilità e le prestazioni

### <a name="access"></a>Access
- Varie correzioni per la stabilità e le prestazioni

### <a name="project"></a>Project
- Varie correzioni per la stabilità e le prestazioni

</BR></BR>


## <a name="february-1-2019"></a>2019 febbraio 1 
Versione 1902 (Build 11326,20000)


## <a name="notable-fixes"></a>Correzioni importanti

### <a name="word"></a>Word 
- È stato risolto un problema con il ridimensionamento delle celle in una tabella Excel incorporata
- È stato risolto un problema relativo alla copia/incolla delle forme in un'area di disegno

### <a name="excel"></a>Excel
- È stato risolto un problema relativo all'apertura di file da Excel Web App
- È stato risolto un problema a causa del quale è stato salvato un file CSV. XLSX si è verificato un errore a causa della dimensione del nome di file
- Il menu di scelta rapida è stato risolto per visualizzare le opzioni di menu di scelta rapida.

### <a name="powerpoint"></a>PowerPoint
- È stato corretto un oggetto rilasciato in cui gli utenti non sono stati in grado di utilizzare la combinazione di tasti CTRL + ALT + 7/Ctrl + Alt + 8 per immettere le parentesi quadre
- È stato risolto un problema a causa del quale l'inserimento di un video locale nel PPT ridurrebbe lo spazio su disco dell'unità' C'
- È stato risolto il pulsante pubblica su Microsoft Stream che non è stato visualizzato ad alcuni utenti

### <a name="outlook"></a>Outlook
- È stato risolto un problema a causa del quale la visualizzazione attività nel calendario non indicava correttamente l'oggetto dell'attività.

### <a name="access"></a>Access
- È stato risolto un problema di scalabilità con i grafici

### <a name="project"></a>Project
- Varie correzioni per la stabilità e le prestazioni
