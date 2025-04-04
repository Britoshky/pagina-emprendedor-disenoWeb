# 📄 Estructura HTML ideal para el proyecto

Este archivo describe la estructura base del archivo `index.html` que usaremos en este proyecto. La página está dividida en **5 partes**, cada una con una responsabilidad distinta dentro del HTML.

---

## 🧩 Parte 1: `<head>` y configuración general

Esta sección contiene la **configuración inicial del documento HTML**, enfocada en accesibilidad, compatibilidad con dispositivos móviles y posicionamiento en buscadores (SEO).

### Incluye:
- `<!DOCTYPE html>`: define que estamos usando HTML5.
- `<html lang="es">`: define el idioma del documento para navegadores y lectores de pantalla.
- `<meta charset="UTF-8">`: establece la codificación de caracteres.
- `<meta name="viewport">`: hace que el sitio sea responsive.
- `<meta name="description">`, `<meta name="keywords">`, `<meta name="author">`: importantes para SEO.
- `<title>`: título de la pestaña del navegador.
- `<link rel="icon">`: icono de la pestaña.
- Opcional: tipografías de Google Fonts, enlace a hoja de estilos CSS (cuando se agregue).

---

## 🧩 Parte 2: `<nav>` - Barra de navegación principal

Contiene el menú que permite al usuario desplazarse por las diferentes secciones del sitio.

### Incluye:
- Etiqueta `<nav>` con `role="navigation"` para accesibilidad.
- Lista `<ul>` con enlaces `<a>` que apuntan a secciones como `#inicio`, `#servicios`, `#contacto`, etc.
- Este menú puede ir fijo en la parte superior o adaptarse a diseño responsive más adelante.

---

## 🧩 Parte 3: `<header>` - Encabezado del sitio

Sección visual destacada que suele ser lo primero que ve el usuario al entrar.

### Incluye:
- Título principal con `<h1>` (único por documento).
- Texto de bienvenida, descripción del propósito del sitio.
- Opcionalmente, una imagen representativa o banner (`<img>` con atributo `alt`).

---

## 🧩 Parte 4: `<main>` - Contenido principal

Contiene las secciones centrales de la página web. Esta parte puede dividirse en subsecciones para distintos bloques de contenido.

### Incluye:
- `<main>` como contenedor principal.
- `<section id="inicio">`: puede mostrar quiénes somos o qué es el sitio.
- `<section id="servicios">`: lista de servicios, características o ventajas del producto o proyecto.
- Opcionalmente, una tercera sección con testimonios, preguntas frecuentes u otros elementos.

---

## 🧩 Parte 5: `<footer>` - Pie de página

Contiene la información final del sitio, accesible desde cualquier parte de la página.

### Incluye:
- Información de contacto o correo electrónico.
- Enlaces adicionales como política de privacidad, términos de uso, etc.
- Redes sociales si aplica.
- Derechos reservados y año actual.
- Etiqueta `<footer>` para semántica clara.

---

## ✅ Buenas prácticas generales

- Usar etiquetas semánticas (`<header>`, `<section>`, `<nav>`, `<main>`, `<footer>`, etc.)
- Solo un `<h1>` por documento.
- Todos los textos deben estar bien organizados y estructurados.
- Imágenes deben incluir `alt` descriptivo.
- Asegurarse que cada sección tenga sentido tanto visual como estructuralmente.

---

Con esta guía, cada integrante podrá trabajar su parte sabiendo cuál es su estructura y propósito, manteniendo una base profesional desde el comienzo del proyecto.

