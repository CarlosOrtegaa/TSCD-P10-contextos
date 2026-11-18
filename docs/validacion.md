# Validación de la práctica 10

La ejecución de GitHub Actions por `push` se completó con éxito el 18/11/2026.

- Ejecución verificada: https://github.com/CarlosOrtegaa/TSCD-P10-contextos/actions/runs/44288281831
- Jobs: Preparar diagnóstico; Comprobar contextos (estado); Comprobar contextos (metadata); Guardar informe seguro.
- Artefacto: `diagnostico-contextos`.
- Campos seguros que muestra el pipeline: evento, rama, repositorio, runner, modo y etiqueta no sensible.
- El workflow no imprime el contexto completo ni las credenciales, tokens o secretos.

El evento `workflow_dispatch` permite cambiar `modo` y `generar_informe`. Para verificar específicamente ese disparador hay que utilizar el botón **Run workflow** de GitHub > Actions; la ejecución por `push` no sustituye esa prueba.
