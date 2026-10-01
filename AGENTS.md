# AGENTS.md — Guida operativa per agenti (.github)

Questo file è l'unica fonte di istruzioni per agenti e contributori su questo repo. `CLAUDE.md` e `GEMINI.md` rimandano qui.

## 1. Contesto

- È il repo speciale `.github` dell'organizzazione `recupera-organizzazione`: i file qui valgono per tutti i repo dell'organizzazione che non li definiscono da soli.
- Usi previsti: `profile/README.md` (pagina pubblica dell'organizzazione), file comuni come `CONTRIBUTING.md`, `SECURITY.md`, template di issue/PR, workflow riusabili.
- Al momento il repo è vuoto (nessun commit).

## 2. Regole di lavoro

1. **Impatto ampio:** ogni file qui si applica a tutti i repo dell'organizzazione (`recupera-dashboard`, `recupera-prenotazioni`, `recupera-test-server`). Verifica che sia coerente con l'`AGENTS.md` di ciascuno.
2. **Niente istruzioni per agenti duplicate:** non aggiungere `copilot-instructions.md` o simili; le regole dei progetti stanno negli `AGENTS.md` dei singoli repo.
3. **Contenuti pubblici:** `profile/README.md` è visibile a tutti; niente segreti, dati personali o informazioni interne.
4. **Lingua:** italiano.
5. **Git:** modifica i file, ma `commit`/`push`/PR solo su richiesta esplicita dell'utente.
