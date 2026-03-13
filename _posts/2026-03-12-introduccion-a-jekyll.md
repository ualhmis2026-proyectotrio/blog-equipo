---
layout: post
title: "Introducción a Jekyll: El motor detrás de los sitios estáticos"
date: 2026-03-12
author: Jesus Montoya Ripoll
---

# Introducción a Jekyll: ¿Qué es y cómo funciona?

En el desarrollo web moderno, no siempre es necesario contar con una base de datos compleja o un servidor que genere contenido en tiempo real. Aquí es donde entran los **Generadores de Sitios Estáticos (SSG)**, y Jekyll es, sin duda, uno de los más populares y potentes.

## ¿Qué es Jekyll?

Jekyll es un generador de sitios estáticos sencillo, diseñado para blogs y proyectos de documentación. Su concepto es simple: tú le entregas texto escrito en **Markdown**, una serie de plantillas y hojas de estilo (CSS), y Jekyll lo "cocina" todo para transformarlo en un sitio web compuesto exclusivamente por archivos HTML, CSS y JS listos para ser servidos.



## ¿Cómo funciona el proceso?

A diferencia de sistemas como WordPress, que consultan una base de datos cada vez que alguien visita una página, Jekyll funciona de la siguiente manera:

1.  **Contenido:** Escribes tus entradas en archivos de texto plano (Markdown).
2.  **Lógica:** Usas **Liquid**, un lenguaje de plantillas que permite insertar contenido dinámico (como listas de posts o fechas) dentro del HTML.
3.  **Construcción:** Al ejecutar Jekyll, este procesa todos los archivos y genera una carpeta llamada `_site` con la web final.
4.  **Servido:** Esos archivos finales se suben a un servidor (como GitHub Pages) que simplemente los muestra al usuario.

## Ventajas de usar Jekyll

* **Velocidad extrema:** Como el servidor no tiene que procesar código ni consultar bases de datos, la carga es casi instantánea.
* **Seguridad:** Al no haber bases de datos ni scripts de servidor (como PHP), las vulnerabilidades más comunes desaparecen.
* **Alojamiento gratuito:** Plataformas como GitHub Pages ofrecen alojamiento gratuito para sitios de Jekyll, integrándose perfectamente con el control de versiones.
* **Simplicidad:** No necesitas un panel de administración complejo; tu editor de código (como VS Code) es tu herramienta de gestión.

## Estructura básica de un proyecto Jekyll

Para entender Jekyll, hay que conocer sus carpetas principales:

* **`_config.yml`:** El centro de mandos donde se define el título, la descripción y los ajustes del sitio.
* **`_posts/`:** Donde viven tus archivos Markdown de las entradas del blog.
* **`_layouts/`:** Contiene las plantillas que definen cómo se verá el contenido (por ejemplo, el diseño de un post frente al de la página principal).
* **`_includes/`:** Fragmentos de código reutilizables, como el pie de página o el menú de navegación.

## Conclusión

Jekyll es la herramienta ideal para desarrolladores que buscan control total, rendimiento y simplicidad. Al eliminar la necesidad de un backend complejo, nos permite centrarnos en lo que realmente importa: el contenido y la experiencia del usuario.