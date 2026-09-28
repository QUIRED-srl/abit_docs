# ABIT Docs

Documentazione statica delle integrazioni ABIT, pubblicata con GitHub Pages.

- Sito: <https://docs.abit.quired.it/>
- Documentazione PMS: <https://docs.abit.quired.it/integrazioni/pms/>
- Swagger: <https://docs.abit.quired.it/integrazioni/swagger/>

GitHub Pages pubblica direttamente la cartella `/docs` del branch `main`.

## Aggiornamento Swagger (ABIT-CR-12)

Il file `docs/integrazioni/swagger/swagger.yaml` è allineato allo snapshot
`docs/swagger-cr12.yaml` del repository ABIT (surface #28–#34).
Dopo il merge delle PR di implementazione su `development`, rigenerare e
risincronizzare con `./scripts/sync-abit-docs-swagger.sh` da ABIT.
