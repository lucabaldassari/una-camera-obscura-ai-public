# Sintesi comparata - test embedded Pionta / Scuola per Abitare

Data: 2026-05-08
Fonte: `memory/ai_cowork/2026.05.08_I_test_embedded_risposte.docx`
Tema: comunicazione evento Pionta 17 maggio 2026 e verifica protocollo multi-AI con pacchetto embedded.

## Stato di lettura dichiarato

Ho letto:
- `memory/TASKS.md`
- `memory/AI_SYNC_LOG.md`
- `memory/ai_cowork/2026.05.08_I_test_embedded_risposte.docx`, contenente risposte di Mistral/Le Chat, DeepSeek, Qwen e Gemini.

Non ho riletto in questa passata:
- link condivisi esterni Gemini/DeepSeek/Mistral;
- repo GitHub privato;
- immagini della locandina;
- chat precedenti non gia sintetizzate nei file di memoria.

Limite della sintesi: lavoro sulle risposte raccolte nel DOCX e sul contesto operativo gia registrato nei file locali.

## Esito rapido

Il test embedded e riuscito meglio del test repo-token: non ha risolto il problema strutturale dell'accesso condiviso, ma ha prodotto quattro risposte comparabili, tutte con stato di lettura dichiarato e tutte basate sullo stesso contesto.

Conclusione: per Gemini, DeepSeek, Qwen, Mistral e altre AI cloud senza accesso affidabile al filesystem/repo privato, il pacchetto embedded e al momento il ponte piu stabile. Va trattato come una fotografia versionata del contesto, non come memoria viva.

## Convergenze forti

Le quattro risposte convergono su questi punti:

- La distinzione locale/nazionale regge, ma e fragile se non viene segnalata con precisione.
- L'evento Pionta deve restare comunicato come prova aperta / test pratico, non come lancio del progetto.
- Scuola per Abitare va nominata, ma non deve diventare il motore narrativo della comunicazione locale.
- Non comunicare ora viaggio futuro, crowdfunding, tappe, Casa della Paesologia come partner o prospettiva strutturata.
- Il post-evento deve essere sobrio: 3-5 foto buone, due righe descrittive, nessuna richiesta implicita di riconoscimento.
- Serve preparare il pubblico al fatto che l'esperienza e lenta, buia, con capienza ridotta e ingresso in pochi per volta.

## Divergenze utili

Le differenze principali non sono contraddizioni, ma scelte di tono:

- DeepSeek preferisce dire che l'occasione "dialoga con" Scuola per Abitare, per evitare che il frame nazionale inglobi la prova locale.
- Gemini accetta una formula piu esplicita: "parte della cornice di Sensibili Presenze e del weekend nazionale della Scuola per Abitare".
- Qwen propone un ponte sobrio: un post social che colleghi i due piani senza caricare la locandina.
- Mistral insiste sulla necessita di definire meglio Sensibili Presenze e Saione Mob nei pacchetti futuri.

Decisione interpretativa Codex: dato che Luca e stato inserito nel calendario della Scuola per Abitare, non bisogna fingere che il legame sia solo laterale. La formula piu equilibrata e: l'evento resta localmente dentro Sensibili Presenze / Saione Mob, ed e inserito anche nel Primo Weekend Nazionale della Scuola per Abitare.

## Contributi da non perdere

DeepSeek: le immagini della camera obscura possono risultare visivamente ambigue. Foto buie, capovolte o poco leggibili vanno accompagnate da didascalie essenziali, altrimenti possono sembrare errori.

Gemini: rischio "sindrome del cantiere". Se emergono problemi tecnici, il frame nazionale puo far sembrare fallimento cio che e normale sperimentazione. Serve dichiarare il carattere di prova.

Gemini: serve un piccolo "manuale d'uso" implicito per il pubblico: esperienza lenta, ingresso in pochi per volta, attesa possibile.

Qwen: rischio "doppia attesa". Scuola per Abitare si aspetta visibilita, il contesto locale si aspetta una prova concreta. Serve una timeline minima per chi vede cosa e quando.

Qwen: ogni pacchetto embedded dovrebbe avere una riga di versioning umano: data, ultimo cambiamento, domande aperte attuali.

Mistral: nei pacchetti futuri serve un glossario minimo per i contesti locali, altrimenti le AI esterne leggono parole come Sensibili Presenze e Saione Mob senza sapere che peso hanno.

## Proposta operativa per Pionta

Locandina: tenere il frame Sensibili Presenze / Saione Mob, senza trasformarla in locandina Scuola per Abitare. Il riferimento nazionale puo vivere nel testo di accompagnamento o in un post separato.

Testo breve pre-evento possibile:

> Domenica 17 maggio, al Parco del Pionta, Una Camera Obscura a Pedali sara in prova aperta dentro Sensibili Presenze / Saione Mob: montaggio, luce, ingresso nel buio, visione del parco capovolto. L'appuntamento e inserito anche nel Primo Weekend Nazionale della Scuola per Abitare. Ingresso libero, 14:00-18:00. Capienza ridotta: si entra in pochi per volta.

Post-evento / invio a Scuola per Abitare:

- 3-5 foto: esterno dispositivo, ingresso, interno/proiezione se leggibile, relazione con parco, dettaglio operativo.
- Didascalie minime, soprattutto per le immagini interne.
- Due righe descrittive, non manifesto.

Esempio:

> Ecco alcune immagini della prova al Pionta. La camera obscura e stata montata e attraversata come spazio buio di osservazione: poche persone per volta, il parco capovolto, la luce come verifica concreta. Se possono essere utili al racconto del Weekend, usale pure.

## Esito sul protocollo multi-AI

Il test dice tre cose:

1. Il repo privato e utile per Codex/Cowork/Claude se hanno accesso, ma non e ancora un ponte universale.
2. Il pacchetto embedded funziona per AI cloud, ma va considerato una versione congelata del contesto.
3. La sintesi di Codex resta un atto interpretativo: deve dichiarare cosa integra, cosa lascia sospeso e cosa trasforma in decisione.

Correzioni consigliate ai prossimi pacchetti embedded:

- aggiungere `CONTEXT_VERSION`: data, cosa e cambiato dall'ultima versione, domande aperte;
- aggiungere glossario minimo dei contesti locali;
- aggiungere esempi di output atteso, quando serve omogeneita;
- aggiungere una riga sulla qualita visiva attesa delle immagini;
- chiedere sempre stato di lettura dichiarato;
- distinguere tra parere critico, proposta testuale, decisione operativa.

## AI Log

| Data | AI | Azione | Note |
|------|----|--------|------|
| 2026-05-08T18:45+02:00 | Mistral / Le Chat | risposta | Letto pacchetto embedded; evidenziati glossario, esempi output, chiarimento Sensibili Presenze/Saione Mob. |
| 2026-05-08T16:20+02:00 | DeepSeek | risposta | Letto pacchetto embedded; evidenziati rischio osmosi Scuola per Abitare, gestione foto buie/capovolte. |
| 2026-05-08T16:20+02:00 | Qwen3.6 | risposta | Letto pacchetto embedded; evidenziati doppia attesa, timeline visibilita, versioning umano. |
| 2026-05-08T16:20+02:00 | Gemini 3 Flash | risposta | Letto pacchetto embedded; evidenziati beta test, sindrome del cantiere, esperienza lenta/poche persone. |
| 2026-05-08T19:05+02:00 | Codex | sintesi | Creata sintesi comparata e proposta operativa Pionta + correzioni protocollo embedded. |
