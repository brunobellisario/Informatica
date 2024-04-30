# Corso di Informatica e Programmazione R per le Scienze Biologiche
# Università degli Studi della Tuscia, Dipartimento di Scienze Ecologiche e Biologiche

Nell’ultimo decennio, i progressi tecnici e tecnologici hanno dato il via ad una vera e propria rivoluzione in ambito scientifico, grazie alle incrementate capacità di ottenere enormi quantità di dati ad una velocità e risoluzione prima d’ora impensabili. Questa ‘big-data revolution’ rende essenziale la conoscenza di adeguati strumenti informatici ed analitici in grado di utilizzare tale mole di informazioni. In tale contesto, la conoscenza dei linguaggi di programmazione rappresenta un must nel portfolio di qualsiasi ricercatore.

In questo corso esploreremo le basi di uno dei linguaggi maggiormente utilizzati per la gestione ed analisi dati in ambito biologico ed ecologico, R. Il corso si dividerà in lezioni teorico/pratiche, affiancando allo studio di R richiami di statistica di base e cenni di statistica avanzata.

Scopo ultimo del corso sarà di fornire agli studenti un adeguato background nella programmazione ed analisi dati, propedeutico al proprio corso di studi.

Questo corso di base di programmazione con R nasce per accompagnare un principiante nella programmazione, dalle basi del linguaggio di programmazione (uno dei più conosciuti e utilizzati nel campo dell'analisi dati) fino all'utilizzo della statistica descrittiva.

Al termine di questo corso lo studente sarà in grado di creare, importare, manipolare e gestire dei dataset. Il corso parte dall'impostazione dell'ambiente di lavoro: vedremo come scaricare, installare e utilizzare alcuni dei più importanti strumenti per l'utilizzo di R, come RStudio.

Passeremo poi alla creazione degli oggetti: R si basa su alcune strutture che è necessario conoscere, come vettori, matrici, liste e dataframe. Una volta che avremo capito come creare e manipolare queste strutture dati, estrarne degli elementi e salvarle in locale sul computer, passeremo all'utilizzo di loop e alla creazione di funzioni.

Nella sezione successiva vedremo una serie argomenti utili: come impostare una cartella di lavoro, come installare e richiamare un pacchetto, come ottenere delle informazioni sui dati, dove trovare dei dataset per i test e ottenere aiuto su una funzione.

Quando si analizzano dei dati ci si imbatte prima o poi nei dataframe cosiddetti casi x variabili. Vedremo quindi come importare un dataframe dal computer, o da internet, su R. Esistono molte funzioni adatte allo scopo e molti pacchetti che ci sono utili per importare dei dati che sono in alcuni formati particolari, come ad esempio i formati per Excel, il .csv, il .txt o il JSON.

Vedremo poi come manipolare i dati, creare nuove variabili, aggregare i dati, ordinarli in maniera orizzontale e longitudinale, unire due dataset. Per fare questo utilizzeremo alcuni pacchetti e funzioni specifiche, come dplyr, tidyr o reshape2. Vedremo anche brevemente come interfacciarci a un database e utilizzare altri pacchetti per snellire la gestione di dataset un po' più grandi.

R è un linguaggio molto importante anche nell'ambito della statistica. Impareremo quindi alcune delle funzioni di base, come calcolo delle medie per riga o per colonna, e le funzioni statistiche più comuni nell'ambito della statistica descrittiva, come media, mediana, moda, la deviazione standard, la visualizzazione della distribuzione e altro ancora.

Quando si parla di analisi dati, ci troveremo spesso a creare dei grafici per spiegare i nostri dati e le nostre analisi. Per questo motivo dedichiamo una sezione del corso a vedere come creare dei grafici sia con le funzioni della libreria di base, sia con il pacchetto ggplot2.  

Nelle ultime lezioni del corso vedremo come creare ed esportare dei report e delle slide, riepiloghiamo gli argomenti visti e le funzioni utilizzate, e vediamo il materiale di supporto. 
_____

# Programma del corso
(suscettible a variazioni)

Lezione 1: Introduzione ai sistemi operativi <br>
Lezione 2: Introduzione ai linguaggi di programmazione <br>
Lezione 3: Introduzione a R<br>
Lezione 4: Installazione e risoluzione alle problematiche più comuni in R<br>
Lezione 5: Tipologie di dati in R<br>
Lezione 6: Introduzione alle principali libraries per la manipolazione dei dati I<br>
Lezione 7: Introduzione alle principali libraries per la manipolazione dei dati II<br>
Lezione 8: Esercitazione<br>
Lezione 9: Funzioni e programmazione iterativa<br>
Lezione 10: BigData analysis: concetti ed esempi pratici<br>
Lezione 11: Shell scripting e bash<br>
Lezione 12: Progetto di gruppo II e considerazioni finali
_____

# Installare R ed RStudio

Per iniziare con R, devi acquisire la tua copia. Questa appendice ti mostrerà come scaricare R e RStudio, un'applicazione software che semplifica l'utilizzo di R.
Sia R che RStudio sono gratuiti e facili da scaricare.

R è gestito da un team internazionale di sviluppatori che rendono il linguaggio disponibile attraverso la pagina web di [The Comprehensive R Archive Network](https://cran.r-project.org). La parte superiore della pagina Web fornisce tre collegamenti per scaricare R. Segui il collegamento che descrive il tuo sistema operativo: Windows, Mac o Linux.

# A.1.1 Windows

Per installare R su Windows, fare clic sul collegamento "Scarica R per Windows". Quindi fare clic sul collegamento "base". Successivamente, fai clic sul primo collegamento nella parte superiore della nuova pagina. Questo collegamento dovrebbe dire qualcosa come "Scarica R 3.0.3 per Windows", tranne per il fatto che la 3.0.3 verrà sostituita dalla versione più recente di R. Il collegamento scarica un programma di installazione, che installa la versione più aggiornata di R per Windows. Esegui questo programma e segui la procedura guidata di installazione visualizzata. La procedura guidata installerà R nelle cartelle dei file di programma e inserirà un collegamento nel menu Start. Tieni presente che dovrai disporre di tutti i privilegi di amministrazione appropriati per installare il nuovo software sul tuo computer.

# A.1.2 Mac

Per installare R su Mac, fare clic sul collegamento "Scarica R per Mac". Successivamente, fare clic sul collegamento al pacchetto R-3.0.3 (o sul collegamento al pacchetto per la versione più recente di R). Verrà scaricato un programma di installazione che ti guiderà attraverso il processo di installazione, che è molto semplice. Il programma di installazione ti consente di personalizzare la tua installazione, ma le impostazioni predefinite saranno adatte alla maggior parte degli utenti. Non ho mai trovato un motivo per cambiarli. Se il tuo computer richiede una password prima di installare nuovi programmi, ne avrai bisogno qui.

# IMPORTANTE. 
Con l'avvento dei più moderni processori Apple Silicon Mx, l'installer per Mac OS è suddiviso in new and old version, queste ultime equipaggiate da processori Intel.
Per conoscere il processore che monta il tuo Mac basta andare in alto a sinistra e premere l'icona della "mela" e poi "INformazioni su questo Mac".

# A.1.3 Linux

R è preinstallato su molti sistemi Linux, ma ti consiglio di aggiornare, nel caso, alla versione più recente. Il sito Web CRAN fornisce file per creare R dal sorgente su sistemi Debian, Redhat, SUSE e Ubuntu sotto il collegamento "Scarica R per Linux". Fare clic sul collegamento e quindi seguire il percorso della directory fino alla versione di Linux su cui si desidera installare. L'esatta procedura di installazione varierà a seconda del sistema Linux utilizzato. CRAN guida il processo raggruppando ogni serie di file sorgente con documentazione o file README che spiegano come installare sul tuo sistema.

# A. 2 RStudio

RStudio è un ambiente di sviluppo integrato (IDE) per R, un linguaggio di programmazione per il calcolo statistico e la grafica. È disponibile in due formati: RStudio Desktop è una normale applicazione desktop mentre RStudio Server viene eseguito su un server remoto e consente di accedere a RStudio utilizzando un browser web.
Puoi scaricarlo gratuitamente [qui](https://www.rstudio.com/products/rstudio/download/#download). Scorri verso il basso e scegli il programma di installazione adatto al tuo sistema operativo.

# Informazioni utili

Ricordiamo che per l'utilizzo di RStudio è **OBBLIGATORIO** avere R prima installato sul proprio PC.

