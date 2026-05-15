---
layout: ../../components/MarkdownPost.astro
title: "Taller MER 4"
categoria: "modelado"
author: 
  name: "José Antonio Espin Molina"
  url: "/github-foto.jpg"
image:
  url: "/LosCobos.png"
  alt: "Ejercicio Los Cobos"
tags: ["modelado", "bases-de-datos"]
pubDate: 'Mar 17, 2025'
likes: '0'
comments: '0'
---

## Ejercicio de modelado entidad-relación 17 de Marzo

Realizado por: José Antonio Espin Molina

---

### Taller Los Cobos

Sistema para reparación de vehículos en estacionamiento de la Universidad El Bosque.

**Proceso de servicio:**
1. Registro de propietario y vehículo
2. Asignación de técnico principal
3. Técnico solicita especialistas si es necesario
4. Registro de componentes en orden de trabajo
5. Generación de factura con desglose de componentes
6. Aplicación de impuesto 21% y conversión USD/EUR

**Categorías de componentes:**
- Aceites (densidad)
- Filtros (tipo)
- Baterías (amperaje, voltaje)
- Neumáticos (ancho, perfil, diámetro)

![LosCobos](/LosCobos.png)

---

### Soluciones Innova

Empresa de servicios tecnológicos que moderniza su sistema de gestión.

**Especificaciones:**
- Clientes corporativos con NIT y múltiples teléfonos
- Servicios contratables a precio definido por gerente
- Gerentes de proyecto con salario y rango profesional
- Equipos de proyecto formados por gerentes
- Relación superior-subordinado en jerarquía

![SolucionesInnova](/SolucionesInnova.png)

---

### Metro de Bogotá

Gestión operativa del sistema de Metro.

**Requisitos:**
- Líneas compuestas por estaciones en orden secuencial
- Estaciones pueden pertenecer a múltiples líneas
- Cada estación tiene múltiples accesos
- Cada línea tiene flota de trenes asignada
- Cantidad de trenes: mínimo = estaciones, máximo = 2×estaciones
- Patios de mantenimiento para cada tren

![Metro](/Metro.png)

---

### La Facultad - Discoteca

Base de datos para gestión de catálogo musical de taberna.

**Almacenamiento:**
- **Grabaciones:** título, género, cantidad de canciones, notas
- **Formatos:** CD, vinilo, digital con estado de conservación
- **Artistas:** nombre, biografía, grabaciones participadas
- **Productoras:** nombre, dirección, ID compañía

![Productora](/Productora.png)