DLC Merger
~~~~~~~~~~

Versione:    2.1
Autore:      Argent77

Download:    https://github.com/Argent77/A7-DlcMerger/releases
Discussione: https://forums.beamdog.com/discussion/71305


Panoramica
~~~~~~~~~~

I giochi in versione Enhanced Edition consentono di aggiungere o modificare contenuti tramite archivi DLC autonomi.
L'esempio più noto è l'espansione "Siege of Dragonspear", distribuita come archivio DLC sulle piattaforme GOG e Steam.

Questo metodo di distribuzione limita però la possibilità di modificare il gioco: non è facile accedere ai file
contenuti negli archivi DLC o modificarli ulteriormente senza ricreare l'intero DLC. Questa mod cerca di superare
tale limite integrando i DLC nel gioco principale. Offre tre opzioni: integrare "Siege of Dragonspear" in BG:EE,
integrare un archivio DLC specificato dall'utente oppure integrare tutti i DLC trovati nei percorsi di ricerca del gioco.

"DLC Merger" è un'alternativa a "modmerge", uno strumento realizzato da uno sviluppatore di Beamdog che era l'unico
modo per rendere Siege of Dragonspear modificabile tramite mod. DLC Merger è indipendente dalla piattaforma e si
inserisce senza difficoltà nella sequenza di installazione delle altre mod WeiDU. Consente di integrare qualsiasi
archivio DLC e offre la possibilità di annullare l'intera operazione di integrazione.


Installazione
~~~~~~~~~~~~~

Questa è una mod WeiDU, quindi è molto semplice da installare. Estrai l'archivio scaricato nella cartella del gioco
ed esegui "setup-DlcMerger.exe". Segui le istruzioni per integrare gli archivi DLC desiderati.


Componenti
~~~~~~~~~~

Questa mod offre tre opzioni per integrare gli archivi DLC nel gioco:

1. Integra "Siege of Dragonspear" in BG:EE (sono richiesti BG:EE e il DLC SoD)

Integra "Siege of Dragonspear" in Baldur's Gate: Enhanced Edition a partire da una qualsiasi delle cartelle
supportate per i DLC.

2. Integra un archivio DLC specificato dall'utente (è richiesto un gioco in versione Enhanced Edition)

Integra un singolo archivio DLC nel gioco. La mod chiede il nome dell'archivio, che può trovarsi in uno qualsiasi
dei percorsi supportati per i DLC. I percorsi vengono esaminati nel seguente ordine:
- Cartella del gioco in Documenti
- Cartella di installazione del gioco
- Sottocartella "dlc" nella cartella di installazione
- Sottocartella "workshop" nella cartella di installazione (richiede file DLC con estensione .mod)

3. Integra tutti gli archivi DLC disponibili (sono richiesti un gioco in versione Enhanced Edition e il programma
   di installazione WeiDU a 64 bit)

Questa opzione cerca gli archivi DLC disponibili in tutti i percorsi supportati dal gioco. I DLC vengono integrati
nello stesso ordine in cui sarebbero caricati dal gioco, in modo che possano sovrascrivere i file di altri DLC
senza causare problemi. Per ragioni tecniche, al momento questa operazione riesce soltanto se la mod viene avviata
con un programma di installazione WeiDU a 64 bit.

IMPORTANTE: al momento WeiDU non riesce a completare l'operazione se il percorso dell'archivio DLC contiene spazi.
Il problema riguarda i DLC nella cartella del gioco in Documenti o gli archivi DLC il cui nome contiene spazi.
Per aggirarlo, sposta gli archivi DLC nella cartella di installazione o in una delle sue sottocartelle "dlc" o
"workshop" e assicurati che i nomi dei file non contengano spazi.


4. Correzione della selezione della lingua in "Siege of Dragonspear" (richiede il DLC SoD già integrato)

Questo componente facoltativo può essere necessario con la patch 2.7 del gioco per ripristinare la selezione
della lingua nella campagna SoD.

Va installato subito dopo aver integrato Siege of Dragonspear, per evitare problemi di compatibilità.

Nota: il componente principale della mod applica già questa correzione. Tuttavia, per ragioni tecniche,
      l'operazione viene saltata se la mod viene avviata con un eseguibile di installazione per Windows a 32 bit.
      In tal caso, esegui nuovamente il programma di installazione della mod per installare la correzione manualmente.


Riconoscimenti
~~~~~~~~~~~~~~

Coding and testing: Argent77

Brazilian Portuguese translation: Felipe

Spanish translation: ElGamerViejuno

Simplified Chinese translation: MephistoSatanDevil

French translation: Deratiseur

Italian translation: Sauler


Licenza
~~~~~~~

La mod "DLC Merger" è distribuita con licenza "Creative Commons Attribution-ShareAlike 4.0 International License"
(http://creativecommons.org/licenses/by-sa/4.0/).


Cronologia delle versioni
~~~~~~~~~~~~~~~~~~~~~~~~~

2.1
- Updated Simplified Chinese translation
- Siege of Dragonspear language selection fix will be automatically applied by the main component (see note in readme)
- Custom merge options are available to all EE games

2.0
- Added French translation (thanks Deratiseur)
- Added new component "Siege of Dragonspear language selection fix"

1.8
- Added check for "unzip" presence on Linux and macOS platforms
- Fixed issue that prevented the mod from installing on case-sensitive filesystems on Linux

1.7
- Updated Simplified Chinese translation
- Improved error handling if merged DLC file wasn't properly renamed

1.6
- Added Simplified Chinese translation (thanks MephistoSatanDevil)

1.5
- Added Spanish translation (thanks ElGamerViejuno)
- Fixed typo in Brazilian Portuguese translation

1.4
- Added Brazilian Portuguese translation (thanks Felipe)
- Added component labels for Project Infinity
- Improved detection and handling of invalid DLC archives

1.3
- Added German translation
- Added Project Infinity metadata
- Added WeiDU SUPPORT information
- Fixed potential display issues with component names in WeiDU.log and Project Infinity
- Improved description of components (thanks ALIEN)

1.2
- Removed information regarding EET and Fixpack from readme because it's not needed anymore

1.1
- Added information regarding EET and Fixpack to readme

1.0
- Initial release
