---
layout: ../../components/MarkdownPost.astro
title: "Taller MER 1"
categoria: "modelado"
author: 
  name: "José Antonio Espin Molina"
  url: "/github-foto.jpg"
image:
  url: "/Aviacion.png"
  alt: "Ejercicio Aviación"
tags: ["modelado", "bases-de-datos"]
pubDate: 'Feb 09, 2025'
likes: '0'
comments: '0'
---

## Ejercicio de modelado entidad-relación 19 de Febrero

Realizado por: José Antonio Espin Molina

---

### Aviación

Una aerolínea requiere una base de datos relacional para registrar sus operaciones.

**Características:**
- Tres recursos principales: Aviones, pilotos y tripulación
- Los aviones tienen código, tipo y base de retorno
- Los pilotos tienen código, nombre y horas de vuelo
- Los miembros de tripulación tienen código, nombre y teléfonos
- Los vuelos van desde origen a destino a hora concreta

![Aviacion](/Aviacion.png)

---

### Biblioteca

Diseño E/R para gestionar datos de una biblioteca.

**Requisitos:**
- Socios con código, cédula, dirección, teléfono, nombre y apellidos
- Libros con título, año de escritura, autor(es), año de edición, editorial e ISBN
- Indicar si un libro está dañado o no

![Biblioteca](/Biblioteca.png)

---

### Streaming

Plataforma de streaming de la Universidad El Bosque para estudiantes.

**Sistema debe almacenar:**
- Tipos de contenido: series, películas, documentales, videos
- Productores y año de lanzamiento
- Categorías
- Usuarios con gustos e historial de vistas
- Historial de búsquedas

![Plataforma](/Plataforma.png)