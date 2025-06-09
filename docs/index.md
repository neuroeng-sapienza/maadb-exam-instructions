# Istruzioni per gli studenti che sostengono l'esame di MAADB

## Checklist
<!-- omit from toc -->

- [ ] So quando entrare in aula e come individuare la mia postazione di lavoro
- [ ] So cosa posso tenere con me durante l'esame
- [ ] So che tra l'inizio della prova e la consegna non potrò lasciare la postazione
- [ ] So che per avviare e poi per consegnare ciascuna prova dovrò eseguire uno script
  (file `.sh`), e so in che cartella si trova ciascuno di questi script
- [ ] So utilizzare il notebook di verifica formale `check_exam.mlx` in Matlab
- [ ] Sono consapevole allo scadere del tempo di ciascuna prova il contenuto della
  cartella `esame` verrà prelevato da remoto e che non saranno valutati eventuali file
  non ancora salvati
- [ ] So che se dovessi decidere di ritirarmi dall'esame dovrò indicarlo chiaramente

<!-- BUG? The syle for level 1 and level 2 TOC entries is the same
          If Header 1 is excluded, then the layout of the TOC is mostly flat (Headers 2 and 3)
  -->
<!-- ## Sommario  -->
<!-- omit from toc -->

<!-- - [Istruzioni per gli studenti che sostengono l'esame di MAADB](#istruzioni-per-gli-studenti-che-sostengono-lesame-di-maadb)
  - [Struttura dell'esame](#struttura-dellesame)
    - [Punteggio](#punteggio)
  - [Le istruzioni in breve](#le-istruzioni-in-breve) -->

## Struttura dell'esame

L'esame si compone di tre prove:

1. problemi in ambiente Matlab (da svolgersi nella Parte 1)
2. quesiti a risposta chiusa (da svolgersi nella Parte 2)
3. quesito a risposta aperta (da svolgersi nella Parte 2)

Le prove sono svolte in sequenza con una breve pausa tra la Parte 1 e la Parte 2:

La durata della Parte 1 è di 90 minuti.

La durata della Parte 2 è di 120 minuti, di cui si possono utilizzare al massimo 60
minuti per i quesiti a risposta chiusa.

### Punteggio

| Prova                          | Punteggio massimo |
|--------------------------------|-------------------|
| Problemi in Matlab             | 12/30             |
| Quesiti a risposta chiusa      | 16/30             |
| Quesito a risposta aperta      | 4/30              |
| **Totale**                     | **32/30**         |

Riceverà la lode chi otterrà un punteggio non inferiore a 31/30.

Maggiori dettagli sono riportati nelle sezioni dedicate a ciascuna prova.

## Le istruzioni in breve

In estrema sintesi, l'esame prevede che gli studenti seguano questa procedura:

1. Arrivare in aula in anticipo rispetto all'orario di inizio dell'esame, per consentire
   di completare le operazioni preliminari. Portare con sé un documento di identità.
2. Individuare la propria postazione di lavoro nell'elenco proiettato sugli schermi
   dell'aula. Tenere con sé solo un documento di identità e altri oggetti strettamente
   necessari (penna e acqua), mentre tutti gli altri oggetti devono essere riposti fuori dalla portata.
3. Inserire la propria matricola nella maschera di identificazione presente sulla app
   `Exam helper`.
4. Ascoltare le istruzioni e attendere la distribuzione dei file nella cartella `esame` presente sul desktop.
   Entrare nella sottocartella `MAADB_Part1`.
5. Eseguire (doppio click) lo script `avvia-problemi.sh`, che a sua volta avvierà il Matlab.
   Svolgere i problemi, assistendosi con il tool di verifica formale `check_exam.mlx`.
6. Completato lo svolgimento dei problemi, salvare i file e chiudere il Matlab. Eseguire
   (doppio click) il file `consegna-problemi.sh` per consegnare lo svolgimento.
7. Dopo la pausa, ripetere i punti precedenti per la Parte 2 dell'esame:

    1. entrare nella sottocartella `MAADB_Part2`
    2. eseguire lo script `avvia-rchiusa.sh` per aprire i file dei quesiti a risposta
       chiusa e lo script `consegna.rchiusa.sh` per consegnare le risposte
    3. eseguire lo script `avvia-raperta.sh` per aprire i file del quesito a risposta
       aperta e lo script `consegna-raperta.sh` per consegnare le risposte

8. Al termine dell'esame, lasciare l'aula in silenzio oppure, se mancano meno di 10
   minuti allo scadere del tempo, attendere alla propria postazione.

Nelle sezioni successive sono fornite istruzioni estremamente dettagliate sulle operazioni e indicazioni per la risoluzione di eventuali problemi tecnici:

- Le fasi dell'esame ([vai alla sezione](./exam-phases.md))
- Le risorse (cartelle di rete e software) che verranno impiegate durante lo svolgimento dell'esame ([vai alla sezione](./os-and-software.md))
- Un'appendice con le istruzioni per la risoluzione di problemi tecnici ([vai alla sezione](./troubleshooting.md))

Queste informazioni sono pensate consentire, a chi lo vuole, di avere un'idea quanto più
chiara possibile di come si svolgerà l'esame in modo da poterlo affrontare con serenità, ma **non sono indispensabili** per sostenere l'esame (è sempre possibile chiedere assistenza durante lo svolgimento).

Tuttavia, **si raccomanda di leggere** almeno le [istruzioni sulle operazioni preliminari](./exam-phases.md#operazioni-preliminari), in modo da non dover ritardare l'inizio del proprio esame attendendo di assistenza su questioni risolvibili in autonomia.

<!-- 
  - [Operazioni preliminari](#operazioni-preliminari)
    - [La convocazione](#la-convocazione)
    - [La postazione di lavoro](#la-postazione-di-lavoro)
    - [Identificazione studente](#identificazione-studente)
  - [Parte 1: Problemi in ambiente Matlab](#parte-1-problemi-in-ambiente-matlab)
    - [Startup](#startup)
    - [Exam checker](#exam-checker)
    - [Indicazioni per lo svolgimento dei problemi (?)](#indicazioni-per-lo-svolgimento-dei-problemi-)
    - [Punteggio](#punteggio-1)
    - [Tempo](#tempo)
  - [Parte 2: Quesiti](#parte-2-quesiti)
    - [Quesiti a risposta chiusa](#quesiti-a-risposta-chiusa)
    - [Quesiti a risposta aperta](#quesiti-a-risposta-aperta)
  - [Conclusione dell'esame](#conclusione-dellesame)
  - [Risorse per lo svolgimento dell'esame](#risorse-per-lo-svolgimento-dellesame)
    - [La cartella condivisa 'esami'](#la-cartella-condivisa-esami)
    - [Le applicazioni da utilizzare](#le-applicazioni-da-utilizzare)
      - [Matlab](#matlab)
      - [Geany (editor di testo)](#geany-editor-di-testo)
      - [xPDF (visualizzatore di file pdf)](#xpdf-visualizzatore-di-file-pdf)
      - [galculator (calcolatrice)](#galculator-calcolatrice)
  - [Appendice - Risoluzione problemi tecnici](#appendice---risoluzione-problemi-tecnici)
    - [Creazione manuale file di svogimento da template](#creazione-manuale-file-di-svogimento-da-template)
    - [Malfunzionamento dello script avvia-problemi.sh](#malfunzionamento-dello-script-avvia-problemish)
      - [1. Avvio Matlab](#1-avvio-matlab)
      - [2. Impostazione della cartella di lavoro](#2-impostazione-della-cartella-di-lavoro)
      - [3. Configurazione del toolbox di verifica formale](#3-configurazione-del-toolbox-di-verifica-formale)
    - [Malfunzionamento dello script avvia-rchiusa.sh e/o avvia-raperta.sh](#malfunzionamento-dello-script-avvia-rchiusash-eo-avvia-rapertash)
    - [Malfunzionamento degli scritpt di consegna](#malfunzionamento-degli-scritpt-di-consegna)
    - [Come aprire manualmente i file pdf](#come-aprire-manualmente-i-file-pdf)
    - [Come aprire manualmente i file txt](#come-aprire-manualmente-i-file-txt)
  - [Struttura della cartella 'esame'](#struttura-della-cartella-esame) -->
