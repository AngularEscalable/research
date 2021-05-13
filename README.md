# Research

Aplicación web para buscar información sobre librerías y herramientas de desarrollo

## Objetivos

- Programar con la última tecnología Angular
- Probar herramientas _no tan comunes todavía_
- Explorar opciones de tu interés

## Requerimientos técnicos

- Usar un mono repositorio multi proyecto (una app y múltiples librerías) con NX
- Emplear el patrón _Container presenter_ y la detección de cambios _OnPush_
- Usar capacidades observables del router.
- Implementar uno propio o usar un gestor de estado observable.
- Usar formularios reactivos con validaciones y controles personalizados.
- Extraer responsabilidad común a directivas, templates, pipes e interceptores

## Funcionalidad esperada

Consultar un tema, un paquete o un repositorio en GitHub, npm y StackOverflow.

Usar las APIs de

[GitHub](https://docs.github.com/en/rest)
[NpmJS](https://github.com/npm/registry/blob/master/docs/download-counts.md)
[StackOverflow](https://api.stackexchange.com/docs)

Ejemplos de uso de API:
curl 'https://api.github.com/search/repositories?q=angular&per_page=10'
curl 'https://registry.npmjs.org/-/v1/search?text=angular&size=5'
curl 'https://api.npmjs.org/downloads/point/last-week/@angular/cli'
curl 'https://api.npmjs.org/downloads/point/last-month/@angular/cli'
curl 'https://api.stackexchange.com/2.2/questions?order=desc&sort=activity&tagged=angular&site=stackoverflow'

Permitir búsquedas específicas por rangos de fechas

Permitir ordenar la respuesta por algún criterio

> Muestra la información que te parezca más adecuada

> Usa el framework CSS que prefieras.

## Sugerencias

Instalar las extensiones recomendadas en .vscode\extensions.json
