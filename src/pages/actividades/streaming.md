```markdown
---
layout: ../../components/MarkdownPost.astro
title: "Ejercicio Streaming"
categoria: "modelo-er"
description: "Modelo E-R para la plataforma de streaming de la Universidad El Bosque."
author: 
  name: "José Antonio Espin"
  url: "/github-foto.jpg"
image:
  url: "/ejercicio-streaming.png"
  alt: "Diagrama Entidad-Relación de la plataforma de Streaming"
tags: ["modelo-er", "bases-de-datos", "diagrama"]
pubDate: 'Feb 2026'
---

## Contexto del ejercicio

La Universidad El Bosque desea lanzar una plataforma de streaming en la cual cada estudiante tenga acceso a contenido como series, películas, documentales y videos.

El sistema debe almacenar la información sobre:

- Tipos de contenido: series, películas, documentales, videos.
- Productores y año de lanzamiento.
- Categorías a las que pertenece cada contenido.
- Usuarios de la plataforma con sus gustos y categorías más vistas.
- Información personal del usuario, historial de búsquedas e historial de videos vistos.

## Diagrama del modelo

![Diagrama Streaming](/ejercicio-streaming.png)

## Conclusiones

El modelo permite representar correctamente la relación entre usuarios y contenido, así como el seguimiento del comportamiento mediante historiales, lo que facilita en el futuro el desarrollo de funcionalidades como recomendaciones personalizadas.
```

---