---
layout: post
title: "Cómo configurar un entorno de desarrollo local con Visual Studio Code"
date: 2026-03-12
author: Jesus Montoya Ripoll
---

# Guía de configuración de Visual Studio Code para Desarrollo Web

Visual Studio Code (VS Code) se ha consolidado como el editor de código preferido por la comunidad de desarrollo gracias a su flexibilidad y potencia. En este tutorial, aprenderás a configurar un entorno de desarrollo profesional desde cero.

## 1. Instalación y Primeros Pasos

El primer paso es descargar el instalador oficial desde [code.visualstudio.com](https://code.visualstudio.com/). 

**Recomendación:** Durante la instalación en Windows, asegúrate de marcar las casillas **"Agregar la acción 'Abrir con Code'"** al menú contextual de archivos y carpetas. Esto te permitirá abrir cualquier proyecto haciendo clic derecho sobre la carpeta.

## 2. Extensiones Imprescindibles

La verdadera potencia de VS Code reside en sus extensiones. Para un flujo de trabajo de desarrollo web moderno (HTML, CSS, JS, Markdown), te recomendamos las siguientes:

* **Live Server:** Abre un servidor local de desarrollo con recarga automática. Al guardar tus cambios, el navegador se actualiza instantáneamente.
* **Prettier - Code Formatter:** Mantiene tu código limpio y bien indentado automáticamente.
* **ESLint:** Te ayuda a encontrar errores en tu código JavaScript mientras escribes.
* **Auto Close Tag / Auto Rename Tag:** Automatiza la gestión de etiquetas HTML, ahorrando tiempo y evitando errores de sintaxis.
* **Material Icon Theme:** Mejora la apariencia visual del explorador de archivos con iconos específicos para cada lenguaje.



## 3. Configuración del Editor (Settings)

Puedes personalizar el comportamiento del editor presionando `Ctrl + ,` (Windows/Linux). Algunas configuraciones recomendadas son:

1.  **Format on Save:** Actívalo para que Prettier ordene tu código cada vez que guardes el archivo.
2.  **Word Wrap:** Cámbialo a `on` para que las líneas de código largas se ajusten al ancho de tu pantalla sin necesidad de hacer scroll horizontal.

## 4. Dominando la Terminal Integrada

No necesitas salir del editor para ejecutar comandos de Git o servidores locales. 
* Abre la terminal con el atajo `Ctrl + ñ` (o `Ctrl + ~`).
* Puedes tener varias pestañas de terminal abiertas simultáneamente para gestionar diferentes procesos, como la ejecución de un generador estático (Jekyll/Hugo) y el control de versiones.

## 5. Control de Versiones con Git

VS Code tiene una de las mejores integraciones visuales para Git:
* En el icono de **Source Control**, puedes ver qué archivos has modificado.
* Puedes hacer "Stage" (preparar), "Commit" (confirmar) y "Push" (publicar) sin escribir una sola línea de comandos.
* La barra de estado inferior te indica siempre en qué rama estás trabajando, evitando errores comunes de despliegue.

## 6. Atajos de Teclado Esenciales

Para aumentar tu productividad, memoriza estos comandos:
* `Ctrl + P`: Buscar y abrir cualquier archivo rápidamente.
* `Ctrl + Shift + P`: Abrir la paleta de comandos (para acceder a todas las funciones del editor).
* `Ctrl + D`: Seleccionar la siguiente coincidencia de la palabra actual (ideal para renombrar variables).

## Conclusión

Una buena configuración de tu entorno local es la base de un desarrollo eficiente. Con estas herramientas y ajustes, tendrás un flujo de trabajo optimizado, profesional y escalable para cualquier proyecto web.