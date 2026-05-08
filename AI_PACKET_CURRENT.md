# AI Packet Current v0.2 - Public Selective Mirror Test

MIRROR_VERSION: v0.2
MIRROR_LAST_SYNC: 2026-05-08T23:58+02:00
CONTEXT_VERSION: 2026-05-08T23:58+02:00
SOURCE_OF_TRUTH: private local project memory, filtered by Codex
TASK_TYPE: technical protocol test
LANGUAGE: Italian
TASK_SCOPE: evaluate whether this public selective mirror can reduce manual copy/paste between AI systems

## Istruzioni per la AI che legge

Rispondi in italiano.

Prima di rispondere, dichiara sempre:

- Ho letto: [elenco file/link effettivamente letti]
- Non ho letto: [file/link non accessibili]
- Limite della risposta: [cosa puoi valutare e cosa no]

Usa questo marker:

`[AI_MIRROR_TEST 2026-05-08 | AGENTE=nome-AI | AZIONE=valutazione | TEMA=mirror-pubblico-selettivo-v0.2 | ESITO=parere-critico]`

Non inventare dati mancanti. Se manca qualcosa, scrivi `[DATO MANCANTE]`.

Se non riesci a leggere i file secondari, rispondi comunque basandoti solo su questo file e dichiaralo.

Se non riesci a verificare `CONTEXT_VERSION.md` o se pensi che il contesto sia vecchio, inserisci questa nota: `[CONTESTO POTENZIALMENTE OBSOLETO]`.

Non proporre modifiche al repository come se potessi applicarle direttamente. Puoi proporre cambiamenti, rischi, priorita e una struttura migliore.

## Perche esiste questo pacchetto

Luca sta costruendo un metodo per far lavorare piu AI su uno stesso progetto senza dover fare continuamente copia/incolla tra chat diverse.

Il problema tecnico emerso nei test: molte AI cloud non riescono a leggere repository GitHub privati con token. Il pacchetto embedded funziona, ma richiede comunque passaggi manuali. Il mirror pubblico selettivo e una prova pragmatica: pochi file markdown, senza dati sensibili, leggibili via URL pubblico.

Questo non e un sistema multi-agent automatico. E un protocollo low-tech, umano-centrico, dove Luca resta il punto di decisione e Codex mantiene lo snapshot pubblico.

## Contesto del progetto

Il progetto di riferimento e Una Camera Obscura a Pedali: una camera obscura mobile, trasportabile in bicicletta, usata come dispositivo artistico, fotografico e relazionale.

La camera obscura permette di entrare nel buio e vedere il paesaggio capovolto. Il progetto lavora su lentezza, sguardo, relazione con i luoghi, pratiche fotografiche povere e sostenibili, incontro con persone e comunita.

Il caso test attuale e l'evento/prova del 17 maggio 2026 al Parco del Pionta, Arezzo. La prova sta nel contesto locale Sensibili Presenze / Saione Mob ed e collegata anche al Primo Weekend Nazionale della Scuola per Abitare.

Questa prova non e il lancio del viaggio futuro e non e parte della raccolta fondi. Serve soprattutto a verificare montaggio, uso pubblico, gestione di un ingresso in pochi per volta, relazione con lo spazio e comunicazione essenziale.

## Glossario minimo

- Una Camera Obscura a Pedali: progetto artistico-fotografico di Luca Baldassari; camera obscura mobile legata a bicicletta, lentezza, fotografia stenopeica, pratiche relazionali.
- Camera obscura: spazio buio in cui l'immagine esterna entra attraverso un foro o lente e appare capovolta all'interno.
- Sensibili Presenze: contenitore/progetto di Electra APS nel quale rientra l'evento locale al Pionta.
- Saione Mob: contesto/iniziativa locale dentro cui si colloca l'appuntamento al Parco del Pionta.
- Scuola per Abitare: rete/cornice nazionale del Primo Weekend Nazionale della Scuola per Abitare; e importante come prospettiva e rete, ma non deve schiacciare la dimensione locale della prova.
- Mirror pubblico selettivo: esportazione pubblica filtrata della memoria privata. Serve a dare alle AI cloud un contesto comune. Non e la fonte di verita.

## Decisioni gia prese

- La fonte di verita resta la memoria privata locale del progetto.
- Il mirror pubblico e solo uno snapshot filtrato e pubblicabile.
- Il mirror non deve diventare un secondo archivio vivo da mantenere manualmente.
- Il file principale da dare alle AI e `AI_PACKET_CURRENT.md`.
- I file secondari sono utili, ma opzionali: il pacchetto principale deve essere abbastanza autosufficiente.
- Ogni AI deve dichiarare cosa ha letto, cosa non ha letto e quali limiti ha la risposta.
- La sintesi finale resta un atto interpretativo, non una somma neutra delle risposte AI.
- Per Pionta: tenere separati livello locale e livello nazionale; non comunicare ora viaggio futuro, crowdfunding, tappe o partnership non consolidate.

## Cosa e stato omesso intenzionalmente

Questo mirror non contiene:

- token, credenziali o dettagli di accesso;
- numeri di telefono, email private o dati personali non necessari;
- budget dettagliati, documenti economici o contrattuali;
- file DOCX, PDF, immagini, archivi fotografici;
- logistica minuta non pubblica;
- bozze private non filtrate;
- contenuti completi delle chat con altre AI.

Queste omissioni sono volute: servono a rendere il pacchetto pubblicabile e sicuro, anche se riducono parte del contesto implicito.

## File secondari opzionali

Se puoi navigare il repository o seguire link relativi, leggi anche:

- `README.md`
- `CONTEXT_VERSION.md`
- `DECISIONS_PUBLIC.md`
- `QUESTIONS_PUBLIC.md`
- `AI_SYNC_PUBLIC.md`
- `PROTOCOL_RATIONALE.md`
- `AI_HANDOFF_TEMPLATE.md`
- `ai_cowork/SINTESI/2026-05-08_sintesi-test-embedded-pionta-spa.md`
- `ai_cowork/SINTESI/2026-05-08_sintesi-test-copiaincolla-soluzioni-tecniche.md`
- `ai_cowork/SINTESI/2026-05-08_sintesi-test-copiaincolla-protocollo-multi-ai.md`
- `ai_cowork/SINTESI/2026-05-08_sintesi-test-mirror-pubblico-risposte.md`

Se non puoi leggerli, non e un problema: rispondi solo su questo pacchetto e dichiaralo.

## Domande del test v0.2

1. Questo pacchetto v0.2 e abbastanza autosufficiente per lavorare senza copia/incolla lungo?
2. Quali informazioni mancano davvero, senza chiedere dati privati o non pubblicabili?
3. Il mirror pubblico selettivo riduce il lavoro manuale di Luca o rischia ancora di creare manutenzione?
4. La struttura minima dovrebbe restare multi-file o diventare una pagina unica tipo GitHub Pages?
5. Cosa dovrebbe fare Codex ogni volta che rigenera il mirror?
6. Cosa dovrebbe fare Luca con meno passaggi manuali possibile?

## Output atteso

Massimo 700 parole.

Struttura:

1. Stato di lettura dichiarato
2. Valutazione della v0.2
3. Rischi principali
4. Struttura minima consigliata
5. Prossimo test pratico
6. Frase conclusiva netta: procedere / non procedere / procedere con condizioni

## Criteri di successo del test

Il mirror v0.2 funziona se:

- l'AI riesce a leggere almeno questo file;
- dichiara correttamente cosa ha letto e cosa no;
- non inventa dati mancanti;
- capisce che il mirror non e la fonte di verita;
- propone miglioramenti concreti senza chiedere di esporre dati privati;
- riduce il copia/incolla a un link + una domanda precisa.

## AI Log

| Data | AI | Azione | Note |
|------|----|--------|------|
| 2026-05-08T20:10+02:00 | Codex | creato | Primo pacchetto pubblico corrente per test mirror. |
| 2026-05-08T23:58+02:00 | Codex | aggiornato | v0.2 resa piu autosufficiente dopo test con Gemini, Qwen, DeepSeek e Mistral. |
