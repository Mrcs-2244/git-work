# git-work - Repositorio colavorativo Git

Repositorio de practica del flujo colaborativo (fork, issue, rama, PR, conflicto, etiqueta y realease)

## Indice

- [Entorno e instalación](#entorno-e-instalacion)
- [Configuración](#configuracion)
- [Comprobación](#comprobacion)
- [Problemas encontrados y solución](#problemas-encontrados-y-solucion)
- [Repositorio remoto](#repositorio-remoto)

## Entorno e instalación
- Entorno de desarrollo: GNU/Linux (Ubuntu).
- Usuari principal (user1): Marcos Rodriguez Hernandez ('~/dpl/ae1')
- Colaborardor simulado (user2): user2 ('~/dpl/ae1-user2')
- Herramientas usadas Git y GitHub CLI ('gh')

## Configuración
- Configuración de pipeline CI con GitHub Actions (.github/workflows/ci.yml) y MkDocs
- Gestión de issues y ramas de funcionalidad:
- Issue #1 y PR #2 para personalización de textos
- Issue #3 y PR #4 para personalización del estilo del botón

## Comprobación
- Versión final etiquetada con tag anotado: 0.1.0
- Release publicada en GitHub: v0.1.0 - Lanzamiento inicial
- Ejecución de pipeline de CI/CD validada correctamente en verde
- Evidencias detalladas registradas en comprobaciones.txt

## Problemas encontrados y solución
- Conflicto de fusión en `css/cover.css`: Conflicto generado entre las ramas fix-button-style (botón lila) y green-button (botón verde). Resuelto manualmente manteniendo el color verde de fondo, mejorando el contraste a blanco y añadiendo sombra con box-shadow
- Fallo en GitHub Actions (CI): Error provocado por texto markdown residual e indentación errónea en ci.yml, además de advertencias de enlaces en modo estricto en MkDocs. Resuelto corrigiendo la sangría del YAML y el enlace en docs/index.md

## Repositorio remoto
- Repositorio: https://github.com/Mrcs-2244/git-work
- Release 0.1.0: https://github.com/Mrcs-2244/git-work/releases/tag/0.1.0

