# ABIT Docs

Documentazione statica delle integrazioni ABIT, pubblicata con GitHub Pages.

- Sito: <https://docs.abit.quired.it/>
- Documentazione PMS: <https://docs.abit.quired.it/integrazioni/pms/>
- Swagger: <https://docs.abit.quired.it/integrazioni/swagger/>

GitHub Pages pubblica direttamente la cartella `/docs` del branch `main`.

## Aggiornamento Swagger (ABIT-CR-12)

Il file `docs/integrazioni/swagger/swagger.yaml` è una copia di
`docs/swagger.yaml` del branch `development` del repository ABIT.
A ogni modifica delle API, rigenerarlo in ABIT (`php artisan swagger:generate`)
e risincronizzarlo con `./scripts/sync-abit-docs-swagger.sh`.
