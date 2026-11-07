---
title: "Lección 12 - Despliega el sitio con GitHub Pages"
description: "Usa la aplicación GitHub Copilot para configurar un flujo de trabajo de Pages, revisar su solicitud de incorporación de cambios y comprobar Space Quiz en directo."
authors:
  - jamesmontemagno
lastUpdated: 2026-10-12
---

Dale a Space Quiz un hogar público desplegándolo con GitHub Pages. Copilot puede preparar el flujo de trabajo y guiar el despliegue, pero tú eres responsable de revisar los cambios y confirmar que el sitio está disponible.

En esta lección, aprenderás a:

- pedir a Copilot que configure un despliegue de GitHub Pages.
- revisar el flujo de trabajo y la solicitud de incorporación de cambios antes de combinarla.
- seguir el despliegue y comprobar el sitio publicado.

## Escenario

Space Quiz ya está en un repositorio de GitHub, pero la gente necesita una forma sencilla de probarlo. Publicar el sitio de un solo archivo con GitHub Pages permite acceder a él desde una URL pública sin añadir un servidor ni una dependencia de ejecución.

## Pide a Copilot que despliegue el sitio

En la sesión de la aplicación Copilot para `space-quiz`, envía este mensaje:

```plaintext
Enable GitHub Pages for this repository. Create a GitHub Actions workflow that builds the website if needed and deploys it to GitHub Pages. Add a README describing the app and how to run it locally if one does not already exist. Create a pull request with these changes and merge it after required checks pass. Monitor the deployment until it succeeds, then report the final URL of the live website. If you lack permission to enable Pages or merge, tell me exactly what I need to approve or do; do not report success until the site is live.
```

![Diagrama de tres etapas: una solicitud de incorporación de cambios de space-quiz combinada; una ejecución correcta de GitHub Actions Deploy website con los pasos Build website, Upload artifact y Deploy to Pages; y Space Quiz en directo en yourname.github.io/space-quiz/.](../../../_images/first-steps-app-pages-deploy.svg)

> [!WARNING]
> Este mensaje pide al agente que cree y combine una solicitud de incorporación de cambios y cambie la configuración de Pages del repositorio. Revisa la diferencia, los permisos de despliegue y cualquier solicitud de aprobación de GitHub antes de continuar.

## Revisa el flujo de trabajo y comprueba el despliegue

1. Confirma que el archivo README solo se añade si el repositorio aún no tiene uno.
2. Revisa los cambios de la solicitud de incorporación de cambios, incluidos los pasos de compilación y despliegue del flujo de trabajo.
3. Combina los cambios únicamente cuando se superen las comprobaciones obligatorias de la solicitud de incorporación de cambios.
4. Sigue la ejecución de despliegue de GitHub Actions hasta que se complete correctamente.
5. Abre la URL indicada y confirma que se carga Space Quiz.

Si el agente no puede habilitar Pages ni combinar la solicitud de incorporación de cambios, sigue las instrucciones concretas que te proporcione. No des la tarea por terminada hasta que el despliegue se complete correctamente y el sitio esté disponible.

## Resumen y siguientes pasos

Space Quiz ya está disponible como sitio web y has comprobado el despliegue en lugar de confiar en el informe del agente. Continúa con la [Lección 13: Repaso y siguientes pasos][next-lesson].

[next-lesson]: ../13-review/
