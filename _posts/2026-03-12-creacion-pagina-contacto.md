---
layout: post
title: "Creación de una página de contacto en el blog"
date: 2026-03-12
author: David Ureña Arróniz
---

Para que los lectores puedan comunicarse con nosotros, es fundamental implementar un formulario de contacto en el blog. En este pequeño tutorial veremos cómo estructurarlo utilizando **HTML** y **CSS** puro.

## 🛠️ Estructura básica en HTML

El primer paso es crear el esqueleto de nuestro formulario utilizando etiquetas HTML. Necesitaremos campos básicos para el nombre, el correo electrónico y el mensaje del usuario.

```html
<form action="#" method="POST">
  <label for="nombre">Nombre:</label>
  <input type="text" id="nombre" name="nombre" required>

  <label for="email">Correo electrónico:</label>
  <input type="email" id="email" name="email" required>

  <label for="mensaje">Mensaje:</label>
  <textarea id="mensaje" name="mensaje" required></textarea>

  <button type="submit">Enviar</button>
</form>
```

## 🎨 Estilos básicos con CSS

Para que nuestro formulario sea atractivo y no parezca sacado de los años 90, debemos aplicar algo de CSS. Podemos darle márgenes, espaciados y un diseño más limpio en nuestro archivo de estilos:

```css
form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
}

input, textarea {
  margin-bottom: 15px;
  padding: 8px;
  border: 1px solid #ccc;
  border-radius: 4px;
}

button {
  padding: 10px;
  background-color: #0056b3;
  color: white;
  border: none;
  cursor: pointer;
}
```

## 🚀 Integración en nuestro proyecto Jekyll

Al trabajar con Jekyll, podemos guardar el código HTML directamente dentro de un archivo Markdown (por ejemplo, en `contacto.md`). Jekyll se encargará de procesarlo y aplicarle el diseño base (`layout: default`) del resto de la página web.

## Conclusión

Añadir un formulario de contacto mejora enormemente la interacción con los visitantes del sitio. Con unas pocas líneas de HTML y CSS, logramos tener una vía de comunicación directa, profesional y totalmente integrada en nuestro blog estático.