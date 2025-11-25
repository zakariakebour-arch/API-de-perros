# API-de-perros
Mi primera experiencia creando una pequeña aplicación web que consume la API pública TheDogAPI. Muestra información de distintas razas de perros y sus imágenes, organizadas dinámicamente con JavaScript. Un proyecto sencillo para aprender a trabajar con APIs, DOM y estructura básica de frontend
Este es mi primer proyecto práctico usando HTML, CSS y JavaScript para consumir una API real.
La aplicación obtiene datos desde TheDogAPI y muestra información de distintas razas de perros, incluyendo imágenes, peso, altura, temperamento y esperanza de vida.

Características

Consumo de la API pública TheDogAPI

Generación dinámica de elementos HTML con JavaScript

Manejo de imágenes provenientes de la API

Diseño simple usando CSS Grid

Fallback automático si una raza no tiene imagen (placeholder)

Primer contacto con interacción frontend + APIs

Estructura del proyecto
/
│── index.html          # Archivo principal
│── static/             # Carpeta opcional para imágenes locales si se usan
│── README.md           # Este archivo

🖼️ Vista previa (Descripción)

La página genera automáticamente una cuadrícula de tarjetas, cada una mostrando:

ID

Nombre de la raza

Temperamento

Peso

Altura

Promedio de vida

Imagen desde la API

API utilizada

TheDogAPI
https://api.thedogapi.com/v1/breeds
