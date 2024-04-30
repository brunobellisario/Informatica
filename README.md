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
# Installing R and RStudio

To get started with R, you need to acquire your own copy. This appendix will show you how to download R as well as RStudio, a software application that makes R easier to use.
Both R and RStudio are free and easy to download.

# How to Download and Install R

R is maintained by an international team of developers who make the language available through the web page of [The Comprehensive R Archive Network](https://cran.r-project.org). The top of the web page provides three links for downloading R. Follow the link that describes your operating system: Windows, Mac, or Linux.

# A.1.1 Windows

To install R on Windows, click the “Download R for Windows” link. Then click the “base” link. Next, click the first link at the top of the new page. This link should say something like “Download R 3.0.3 for Windows,” except the 3.0.3 will be replaced by the most current version of R. The link downloads an installer program, which installs the most up-to-date version of R for Windows. Run this program and step through the installation wizard that appears. The wizard will install R into your program files folders and place a shortcut in your Start menu. Note that you’ll need to have all of the appropriate administration privileges to install new software on your machine.

# A.1.2 Mac

To install R on a Mac, click the “Download R for Mac” link. Next, click on the R-3.0.3 package link (or the package link for the most current release of R). An installer will download to guide you through the installation process, which is very easy. The installer lets you customize your installation, but the defaults will be suitable for most users. I’ve never found a reason to change them. If your computer requires a password before installing new progams, you’ll need it here.

# A.1.3 Linux

R comes preinstalled on many Linux systems, but you’ll want the newest version of R if yours is out of date. The CRAN website provides files to build R from source on Debian, Redhat, SUSE, and Ubuntu systems under the link “Download R for Linux.” Click the link and then follow the directory trail to the version of Linux you wish to install on. The exact installation procedure will vary depending on the Linux system you use. CRAN guides the process by grouping each set of source files with documentation or README files that explain how to install on your system.

# A. 2 RStudio

RStudio is an Integrated Development Environment (IDE) for R, a programming language for statistical computing and graphics. It is available in two formats: RStudio Desktop is a regular desktop application while RStudio Server runs on a remote server and allows accessing RStudio using a web browser.
You can download it for free [here](https://www.rstudio.com/products/rstudio/download/#download). Scroll down and choose the installer that fits your OS.

# Useful infos

Please, remember that for the use of RStudio is MANDATORY to have R first installed on your PC.

