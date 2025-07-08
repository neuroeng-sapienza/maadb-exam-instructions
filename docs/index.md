# Istruzioni per gli studenti che sostengono l'esame di Metodi Avanzati di Analisi dei Dati Biomedici (MAADB)

## Checklist (verificare con cura)
<!-- omit from toc -->
La seguente lista contiene le informazioni che è essenziale conoscere dopo aver
letto questo documento o, in caso di dubbi, chiedendo chiarimenti ai docenti
prima dell'inizio dell'esame.

- [ ] So quando entrare in aula e come individuare la mia postazione di lavoro
- [ ] So cosa posso tenere con me durante l'esame
- [ ] So che tra l'inizio della prova e la consegna non potrò lasciare la postazione
<!-- - [ ] So che per avviare e poi per consegnare ciascuna prova dovrò eseguire uno script
  (file `.sh`), e so in che cartella si trova ciascuno di questi script -->
- [ ] So che per avviare e poi consegnare ciascuna prova dovrò cliccare un pulsante
      nell'applicazione _Exam helper_
- [ ] So utilizzare il _live script_ di verifica formale `check_exam.mlx` in Matlab
- [ ] So che se nell'editor di testo Geany il nome del file viene visualizzato in rosso,
      allora le modifiche non sono state ancora salvate
- [ ] So come misurare il numero di caratteri in un brano di testo nell'editor Geany
- [ ] Sono consapevole che allo scadere del tempo di ciascuna prova il contenuto della
  cartella `esame` verrà prelevato da remoto e che **non saranno valutati eventuali file
  non ancora salvati**
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

La durata della Parte 2 è di 120 minuti, di cui si possono utilizzare al massimo
i primi 60 minuti per i quesiti a risposta chiusa.

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

- **Operazioni preliminari**

    1. Portare con sé un documento di identità.
    2. Entrare in aula con 10 minuti di anticipo rispetto all'orario di inizio
       dell'esame, per consentire di completare in tempo le operazioni
       preliminari.
    3. Individuare la propria postazione di lavoro nell'elenco proiettato sugli
       schermi dell'aula. Tenere con sé solo un documento di identità e altri
       oggetti strettamente necessari (penna e acqua), mentre tutti gli altri
       oggetti devono essere riposti nello zaino/borsa fuori dalla portata.
    4. Inserire la propria matricola nella maschera di identificazione presente sulla app
       _Exam helper_. **Non** avviare manualmente il Matlab.

- **Parte 1: Problemi in ambiente Matlab**

    1. Ascoltare le istruzioni e attendere che i file dell'esame vengano
       caricati nella cartella condivsa. La schermata dell'applicazione `Exam
       helper` si aggiornerà automaticamente.
    2. Avviare la prova cliccando sul pulsante "_Avvia Problemi in Matlab_".
       **Pazientare qualche secondo** mentre il Matlab si avvia. I file dell'esame
       saranno già aperti nell'editor.
    3. Svolgere i problemi, assistendosi con il tool di verifica formale `check_exam.mlx`.
    4. Completato lo svolgimento dei problemi, salvare i file e chiudere il Matlab.
       Cliccare sul pulsante "_Consegna Problemi in Matlab_" per consegnare lo svolgimento.

- **Parte 2: Quesiti**

    1. Attendere la distribuzione dei file dei quesiti.
    2. Avviare i quesiti a risposta chiusa cliccando sul pulsante "_Avvia
       Quesiti a Risposta Chiusa_". Pazientare qualche secondo mentre i file vengono
       aperti.
    3. Rispondere ai quesiti a risposta chiusa e cliccare sul pulsante "_Consegna
       quesiti a risposta chiusa_" per consegnare le risposte.
    4. Avviare il quesito a risposta aperta cliccando sul pulsante "_Avvia
       quesito a risposta aperta_". Pazientare qualche istante mentre il file viene
       aperto.
    5. Rispondere al quesito a risposta aperta e cliccare sul pulsante "_Consegna
       quesito a risposta aperta_" per consegnare le risposte.

- **Conclusione dell'esame**  
  Una volta consegnati tutti i file:
    <!-- markdownlint-disable MD007 -->
    - se mancano più di 10 minuti allo scadere del tempo, lasciare l'aula in silenzio
    - altrimenti, attendere alla propria postazione che tutti i partecipanti
      abbiano consegnato.
    <!-- markdownlint-enable MD007 -->

## Approfondimenti

Nelle pagine di approfondimento sono fornite istruzioni dettagliate sulle
operazioni e indicazioni per la risoluzione di eventuali problemi tecnici.
Queste informazioni sono pensate consentire, a chi lo vuole, di avere un'idea
quanto più possibile chiara di come si svolgerà l'esame in modo da poterlo
affrontare con serenità.

Le pagine di approfondimento **non sono indispensabili** per sostenere l'esame
(è sempre possibile chiedere assistenza durante lo svolgimento). Tuttavia, **si
raccomanda di leggere** almeno le [istruzioni sulle operazioni
preliminari](./exam-phases.md#operazioni-preliminari), così da essere preparati
sulle prime azioni da fare e non dover ritardare l'inizio del proprio esame
attendendo assistenza su problemi risolvibili in autonomia.

Le pagine di approfondimento riguardano:

- Le fasi dell'esame ([vai alla pagina](./exam-phases.md))
- Le risorse (cartelle di rete e software) che verranno impiegate durante lo
  svolgimento dell'esame ([vai alla pagina](./os-and-software.md))
- Un'appendice con le istruzioni per la risoluzione di problemi tecnici ([vai
  alla pagina](./troubleshooting.md))

## FAQ

<!-- markdownlint-disable MD036 -->

**Ho consegnato un file ma avevo dimenticato di salvare le ultime modifiche. Posso correggere?**

Una volta consegnato un file, non è più possibile modificarlo, se non con una procedura eccezionale (che richiede motivazioni eccezioniali).

Si raccomanda di:

1. salvare frequentemente le modifiche durante lo svolgimento dell'esame per evitare di perdere il lavoro fatto
2. chiudere l'editor (_Matlab_ o _Geany_) prima della consegna di una parte dell'esame, per assicurarsi che non ci siano modifiche non salvate.

**Improvvisamente il _live script_ `check_exam.mlx` ha smesso di funzionare e mostra un messaggio di errore**

Se il _live script_ di verifica formale `check_exam.mlx` mostra un messaggio di errore, è probabile che le sue variabili interne siano state cancellate da un `clear all` eseguito in precedenza.

In questo caso, è sufficiente eseguire il _live script_ per intero, cliccando sul pulsante "Run" (icona con la freccia verde) nella barra degli strumenti di Matlab.

**La pagina di conferma della consegna dei quesiti a risposta aperta mostra solo una riga di testo**

Si tratta di un problema noto, in via di risoluzione. _Tutto_ il testo è presente su una singola riga, ed è possibile leggerlo usando la barra di scorrimento orizzontale. Il file consegnato è comunque salveto correttamente.

**Posso utilizzare la mia calcolatrice?**

No, l'uso della calcolatrice non è consentito. Per i calcoli possono essere utilizzati il Matlab (durante la Parte 1) o l'applicazione [_galculator_](./os-and-software.md#galculator-calcolatrice).

<!-- markdownlint-disable MD036 -->
