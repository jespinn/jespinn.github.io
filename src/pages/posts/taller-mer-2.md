---
layout: ../../components/MarkdownPost.astro
title: "Taller MER 2"
categoria: "modelado"
author: 
  name: "José Antonio Espin Molina"
  url: "/github-foto.jpg"
image:
  url: "/Transporte.png"
  alt: "Ejercicio Transporte"
tags: ["modelado", "bases-de-datos"]
pubDate: 'Feb 24, 2025'
likes: '0'
comments: '0'
---

## Ejercicio de modelado entidad-relación 24 de Febrero

Realizado por: José Antonio Espin Molina

---

### Transporte

Informatizar la gestión de una empresa de transportes que reparte paquetes por toda Colombia.

**Entidades:**
- **Conductores:** cédula, nombre, teléfono, dirección, salario, ciudad
- **Paquetes:** código, descripción, destinatario, dirección destino
- **Ciudades:** código, nombre
- **Camiones:** matrícula, modelo, tipo, potencia

**Relaciones:**
- Un conductor distribuye muchos paquetes (1:N)
- Un paquete llega a una ciudad (N:1)
- Un conductor puede conducir diferentes camiones (N:M)

![Transporte](/Transporte.png)

---

### Bienes Raíces

Seguimiento de casas en venta y clientes que buscan comprar.

**Entidades:**
- **Agentes:** nombre, cédula, género, fecha nacimiento, ventas mes, código
- **Casas:** precio, dirección, propietario, características
- **Clientes:** preferencias, rango precios

![BienesRaices](/BienesRaices.png)

---

### Proveedor

Sistema de proveedores, clientes y pedidos.

**Tablas:**
- Proveedor (SName, ItemName, Price)
- Cliente (CName, Address)
- Pedido (CName, SName, ItemName, Qty)
- Elemento (ItemName, Description)

![Proovedor](/Proveedor.png)

---

### Biblioteca Avanzada

Diseño conceptual de operaciones de biblioteca comunitaria.

**Características:**
- Libros, CD, cintas que se prestan a usuarios
- Usuarios con número de cuenta, dirección, teléfono, fecha nacimiento
- Penalizaciones por atrasos
- Patrocinadores para menores de edad

![Biblioteca](/Biblioteca2.png)

---

### Supermercado

Sistema de apoyo a decisión para análisis de ventas.

**Estructura:**
- Geografía: región → estado → ciudad
- Tiempo: días, meses, años
- Productos: nombre, categoría

![Supermercado](/Supermercado.png)