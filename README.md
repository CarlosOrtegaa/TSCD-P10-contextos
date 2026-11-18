# TSCD - Práctica 10: contextos de GitHub Actions

Proyecto de la práctica de Tecnologías de Servicios para Ciencia de Datos (ULPGC).

El workflow `.github/workflows/contextos.yml` utiliza los contextos `github`, `inputs`, `env`, `vars`, `runner`, `matrix`, `needs` y `steps`. Se ejecuta mediante `push`, `pull_request` o manualmente (`workflow_dispatch`). No imprime secretos.

En GitHub > Actions > P10 - Contextos de GitHub Actions puede lanzarse manualmente en modo `resumen` o `detallado`. El job `informe` genera el artefacto `diagnostico-contextos` cuando está habilitado.
