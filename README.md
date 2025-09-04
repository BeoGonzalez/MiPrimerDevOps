# Mi Primer DevOps

## Propósito del proyecto

Consiste en una práctica para la prueba que se va a realizar el día 12 de septiembre que 
tiene que contener lo pedido en el documento "evaluación formativa devops.docx".
--------------------------------------------------------------------------------------------

1. Repositorio en GitHub
- [x] Crear un repositorio público llamado MiPrimerDevOps.
- [x] Inicializarlo con un archivo README.md que explique el propósito del proyecto.
--------------------------------------------------------------------------------------------

2. Ramas y commits
1. Crear al menos una rama adicional siguiendo el flujo de ramas visto en clase
> ejemplo: feature/docs o feature/config.
2. [x] Hacer mínimo 5 commits significativos
--------------------------------------------------------------------------------------------

3. Archivos de información
3. [ ] Crear al menos tres archivos de documentación en formato Markdown (.md),
por ejemplo:
1. - [x] README.md → descripción general del proyecto.
2. - [x] CONTRIBUTING.md → reglas para contribuir. [Guía de convivencia](CONTRIBUTING.md)
3. - [ ] CHANGELOG.md → registro de cambios.
4. - [x] LICENSE.md → licencia del proyecto.
--------------------------------------------------------------------------------------------

4. GitHub Actions
- [x] Configurar un workflow de GitHub Actions en .github/workflows/.
- [x] El workflow debe contener al menos un gatillador (trigger), como:
- [x] on: push (cada vez que se suben cambios), o
- [x] on: pull_request (cuando se hace un PR).
- [ ] El workflow debe validar los archivos Markdown usando la acción:
▪ DavidAnson/markdownlint-cli2-action@v20
- [ ] El pipeline debe utilizar el archivo .markdownlint.json que será entregado por el
profesor.
- El pipeline debe fallar si algún archivo .md no cumple las reglas.
--------------------------------------------------------------------------------------------

5. Entregable
- Link del repositorio en GitHub.
- Debe poder verificarse:
- Los 5 commits en el historial.
- Los 2 archivos de documentación.
- El workflow ejecutado en la pestaña Actions, con resultados de la validación
de Markdown.
--------------------------------------------------------------------------------------------
