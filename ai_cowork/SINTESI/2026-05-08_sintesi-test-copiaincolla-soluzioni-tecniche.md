# Sintesi tecnica - test copia/incolla multi-AI

Data: 2026-05-08
Fonte: `memory/ai_cowork/2026.05.08_II_test_copiaincolla_risposte.docx`
Tema: come far lavorare piu AI sullo stesso progetto riducendo il copia/incolla manuale.

## Stato di lettura dichiarato

Ho letto:
- `memory/TASKS.md`
- `memory/ai_cowork/2026.05.08_II_test_copiaincolla_risposte.docx`, contenente risposte di Gemini, Qwen, DeepSeek e Mistral.

Non ho riletto in questa passata:
- il repo GitHub privato;
- il file integrale `AI_COLLABORATION_BRIEF.md`;
- le risposte esterne nei link condivisi.

Limite: questa sintesi valuta le proposte tecniche emerse nel DOCX e le confronta con il sistema gia impostato.

## Esito rapido

Le risposte confermano che il pacchetto embedded e il metodo piu robusto nel breve periodo, ma non risolvono davvero il problema che interessa a Luca: evitare che lui diventi il router manuale tra AI.

Il punto tecnico non ancora sfruttato abbastanza e questo: creare un ponte pubblico ma selettivo, non un repo privato con token. Le AI cloud leggono molto piu facilmente contenuti pubblici/non autenticati che contenuti privati protetti.

## Cosa converge

- Single Source of Truth: serve un documento sorgente unico.
- Markdown: resta il formato migliore come lingua franca.
- Stato di lettura dichiarato: indispensabile.
- Marker/AI Log: indispensabili per capire chi ha fatto cosa.
- Pacchetto embedded: funziona, ma e statico.
- Micro-compiti: meglio una domanda precisa che una richiesta generica.
- Confini di competenza: l'AI deve sapere cosa puo decidere e cosa deve solo proporre.

## Cosa manca nelle risposte

Le AI propongono bene la disciplina del processo, ma quasi nessuna affronta il collo di bottiglia tecnico fino in fondo.

Il limite non e solo organizzativo. E di accesso:
- repo privato: buono per versioning, fragile per AI cloud;
- token: non usabile in molte chat AI;
- link condivisi: non sempre leggibili;
- copia/incolla: funziona sempre, ma scarica tutto su Luca;
- pacchetto embedded: riduce il rumore, ma va rigenerato a mano.

## Soluzione tecnica piu promettente

Creare un mirror pubblico selettivo, senza materiali sensibili, pensato solo per le AI.

Possibili forme:

1. Repo GitHub pubblico separato
   - contiene solo file markdown puliti;
   - nessun dato sensibile, nessun PDF pesante, nessuna immagine privata;
   - URL leggibili senza token;
   - versionamento chiaro.

2. GitHub Pages / pagina statica
   - stesso contenuto del repo pubblico, ma letto come sito web;
   - spesso piu accessibile alle AI cloud rispetto al raw GitHub privato;
   - utile se serve dare un solo link.

3. Gist pubblico temporaneo
   - buono per test rapidi;
   - meno adatto come memoria stabile.

4. Google Drive / Google Docs
   - utile soprattutto per Gemini;
   - meno universale per DeepSeek, Qwen, Mistral;
   - rischia di diventare un secondo archivio parallelo.

5. Notion / Zapier / LangChain / API
   - possibili, ma per ora sproporzionati;
   - hanno senso solo se il flusso multi-AI diventa frequente e ripetitivo.

## Proposta Codex

Per ora non passerei a LangChain o Zapier. Prima farei un test piu semplice:

- mantenere il repo privato come memoria ponte completa/selettiva;
- creare un `public_ai_packet` o repo pubblico separato con solo:
  - `README.md`
  - `CONTEXT_VERSION.md`
  - `AI_PACKET_CURRENT.md`
  - `DECISIONS_PUBLIC.md`
  - `QUESTIONS_PUBLIC.md`
  - `ai_cowork/SINTESI/*.md`
- ogni volta Codex genera/aggiorna il pacchetto pubblico da file locali, togliendo materiali sensibili;
- Luca passa alle AI cloud un solo link pubblico e una domanda precisa.

Questa e la soluzione piu vicina all'obiettivo: meno copia/incolla, accesso piu universale, controllo dei dati.

## Criterio pratico

Se il compito e piccolo: copia/incolla resta piu veloce.

Se il compito coinvolge 3 o piu AI, o deve produrre memoria riutilizzabile: conviene generare un pacchetto pubblico versionato.

Se il compito e ricorrente e strutturale: allora si valuta un sistema semi-automatizzato piu complesso.

## AI Log

| Data | AI | Azione | Note |
|------|----|--------|------|
| 2026-05-08 | Gemini | risposta | Conferma SSOT, marker, stato lettura, AI Log e markdown. |
| 2026-05-08 | Qwen | risposta | Propone CONTEXT_VERSION, handoff packet, micro-decisioni, NEXT_ACTIONS. |
| 2026-05-08 | DeepSeek | risposta | Conferma pacchetto embedded e dialogo a staffetta; sottolinea che Luca resta ponte umano. |
| 2026-05-08 | Mistral | risposta | Propone hub & spoke, micro-scoping, strumenti come Notion, GitHub Issues, LangChain. |
| 2026-05-08T19:35+02:00 | Codex | sintesi | Individuata soluzione tecnica piu promettente: mirror pubblico selettivo / AI packet pubblico versionato. |
