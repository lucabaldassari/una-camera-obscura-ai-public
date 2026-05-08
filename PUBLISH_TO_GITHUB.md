# Come pubblicare il mirror

Il connettore GitHub disponibile a Codex puo scrivere file in un repository gia esistente, ma in questa sessione non puo creare un repository nuovo.

## Passaggio richiesto a Luca

Creare su GitHub un repository pubblico vuoto, suggerito:

`lucabaldassari/una-camera-obscura-ai-public`

Impostazioni consigliate:

- Visibility: Public
- README: non necessario
- .gitignore: non necessario
- License: nessuna per ora

Dopo averlo creato, scrivere a Codex:

`repo pubblico creato: lucabaldassari/una-camera-obscura-ai-public`

A quel punto Codex puo caricare i file da `memory_public_ai_mirror` tramite connettore GitHub.

## Test successivo

Dare alle AI cloud il link pubblico a `AI_PACKET_CURRENT.md` e chiedere di rispondere rispettando il marker `AI_MIRROR_TEST`.

## AI Log

| Data | AI | Azione | Note |
|------|----|--------|------|
| 2026-05-08T20:10+02:00 | Codex | creato | Istruzioni operative per pubblicare il mirror. |
