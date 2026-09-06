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

Programmazione e test: Argent77

Traduzione in portoghese brasiliano: Felipe

Traduzione in spagnolo: ElGamerViejuno

Traduzione in cinese semplificato: MephistoSatanDevil

Traduzione in francese: Deratiseur


Licenza
~~~~~~~

La mod "DLC Merger" è distribuita con licenza "Creative Commons Attribution-ShareAlike 4.0 International License"
(http://creativecommons.org/licenses/by-sa/4.0/).


Cronologia delle versioni
~~~~~~~~~~~~~~~~~~~~~~~~

2.1
- Aggiornata la traduzione in cinese semplificato
- Il componente principale applica automaticamente la correzione della selezione della lingua in Siege of Dragonspear
  (vedi la nota nel readme)
- Le opzioni di integrazione personalizzate sono disponibili per tutti i giochi EE

2.0
- Aggiunta la traduzione in francese (grazie a Deratiseur)
- Aggiunto il componente "Correzione della selezione della lingua in Siege of Dragonspear"

1.8
- Aggiunto un controllo della presenza di "unzip" su Linux e macOS
- Risolto un problema che impediva l'installazione della mod su Linux nei file system che distinguono maiuscole e minuscole

1.7
- Aggiornata la traduzione in cinese semplificato
- Migliorata la gestione degli errori quando il file DLC integrato non viene rinominato correttamente

1.6
- Aggiunta la traduzione in cinese semplificato (grazie a MephistoSatanDevil)

1.5
- Aggiunta la traduzione in spagnolo (grazie a ElGamerViejuno)
- Corretto un refuso nella traduzione in portoghese brasiliano

1.4
- Aggiunta la traduzione in portoghese brasiliano (grazie a Felipe)
- Aggiunte le etichette dei componenti per Project Infinity
- Migliorati il rilevamento e la gestione degli archivi DLC non validi

1.3
- Aggiunta la traduzione in tedesco
- Aggiunti i metadati per Project Infinity
- Aggiunte le informazioni SUPPORT di WeiDU
- Risolti potenziali problemi di visualizzazione dei nomi dei componenti in WeiDU.log e Project Infinity
- Migliorata la descrizione dei componenti (grazie ad ALIEN)

1.2
- Rimosse dal readme le informazioni su EET e Fixpack, perché non più necessarie

1.1
- Aggiunte al readme le informazioni su EET e Fixpack

1.0
- Prima versione
