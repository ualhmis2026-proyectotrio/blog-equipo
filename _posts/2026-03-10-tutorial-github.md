---
layout: post
title: "Introducción a GitHub"
date: 2026-03-10
author: Carmen María Peña Sevilla
---

# Introducción a GitHub

GitHub es una plataforma online que permite almacenar proyectos de software y trabajar en equipo utilizando el sistema de control de versiones Git. Es una de las herramientas más utilizadas en el desarrollo de software moderno.

## ¿Qué es Git?

Git es un sistema de control de versiones que permite guardar diferentes versiones de un proyecto y realizar un seguimiento de los cambios en el código. Gracias a Git, los desarrolladores pueden trabajar en equipo sin perder información ni sobrescribir el trabajo de otros.

## ¿Qué es GitHub?

GitHub es un servicio en la nube que permite almacenar repositorios de Git. Además de guardar el código, GitHub facilita la colaboración entre desarrolladores mediante herramientas como Pull Requests, Issues y gestión de ramas.

## Comandos básicos de Git

Algunos de los comandos más utilizados cuando trabajamos con Git y GitHub son:

### Clonar un repositorio

Este comando descarga un repositorio de GitHub a tu ordenador.

git clone https://github.com/usuario/repositorio.git

### Ver el estado de los archivos

Permite ver qué archivos han sido modificados o añadidos.

git status

### Añadir archivos al commit

Añade los cambios al área de preparación.

git add 

### Crear un commit

Guarda los cambios realizados en el repositorio local.

git commit -m "mensaje del commit"

### Subir cambios a GitHub

Envía los cambios al repositorio remoto.

git push origin main

### Crear una nueva rama

Permite trabajar en una funcionalidad sin modificar la rama principal.

git checkout -b nueva-rama


## Flujo de trabajo básico con GitHub

Un flujo de trabajo típico en GitHub suele seguir estos pasos:

1. Clonar el repositorio.
2. Crear una nueva rama.
3. Realizar cambios en los archivos.
4. Añadir los cambios con `git add`.
5. Crear un commit con `git commit`.
6. Subir los cambios con `git push`.
7. Crear un Pull Request para integrar los cambios en la rama principal.

## Conclusión

GitHub es una herramienta fundamental en el desarrollo de software actual, ya que permite trabajar de forma organizada, mantener el control de los cambios y colaborar fácilmente con otros desarrolladores en un mismo proyecto.
