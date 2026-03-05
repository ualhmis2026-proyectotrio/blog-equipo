---
layout: page
title: "Contacto"
---

<style>
  .contenedor-contacto {
    max-width: 600px;
    margin: 40px auto;
    background: #ffffff;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.1);
    border: 1px solid #eaeaea;
  }
  .contenedor-contacto p {
    text-align: center;
    color: #555;
    margin-bottom: 25px;
  }
  .contenedor-contacto label {
    font-weight: 600;
    color: #333;
    display: block;
    margin-bottom: 8px;
    margin-top: 15px;
  }
  .contenedor-contacto input[type="text"],
  .contenedor-contacto input[type="email"],
  .contenedor-contacto textarea {
    width: 100%;
    padding: 12px;
    border: 1px solid #ccc;
    border-radius: 8px;
    box-sizing: border-box;
    font-family: inherit;
    font-size: 15px;
    transition: all 0.3s ease;
  }
  .contenedor-contacto input:focus,
  .contenedor-contacto textarea:focus {
    border-color: #2a7ae2;
    outline: none;
    box-shadow: 0 0 8px rgba(42, 122, 226, 0.3);
  }
  .boton-enviar {
    background-color: #2a7ae2;
    color: white;
    padding: 14px 20px;
    margin-top: 25px;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    font-size: 16px;
    font-weight: bold;
    width: 100%;
    transition: background-color 0.3s ease, transform 0.1s ease;
  }
  .boton-enviar:hover {
    background-color: #1c5baf;
  }
  .boton-enviar:active {
    transform: scale(0.98);
  }
</style>

<div class="contenedor-contacto">
  <h2>¡Escríbenos! 🚀</h2>
  <p>¿Tienes alguna duda o sugerencia sobre nuestro proyecto en la UAL? Rellena el formulario y te contestaremos lo antes posible.</p>
  
  <form action="https://formspree.io/f/xzdjpkja" method="POST">
    
    <label for="nombre">Nombre y Apellidos:</label>
    <input type="text" id="nombre" name="nombre" placeholder="Ej: Ada Lovelace" required>
    
    <label for="correo">Correo electrónico:</label>
    <input type="email" id="correo" name="email" placeholder="tu_correo@ual.es" required>

    <label for="asunto">Asunto:</label>
    <input type="text" id="asunto" name="asunto" placeholder="¿De qué trata tu mensaje?" required>
    
    <label for="mensaje">Mensaje:</label>
    <textarea id="mensaje" name="mensaje" rows="5" placeholder="Escribe aquí todos los detalles..." required></textarea>
    
    <button type="submit" class="boton-enviar">Enviar Mensaje</button>
  </form>
</div>