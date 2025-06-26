# Estructura de Base de Datos en MongoDB

## Nivel 1

## Proyecto: Óptica “Cul d'Ampolla”

Este proyecto consiste en el diseño de la estructura de base de datos para informatizar la gestión de una óptica, utilizando MongoDB como sistema de base de datos NoSQL.

---

## 🏢 Descripción del problema

La óptica "Cul d'Ampolla" desea informatizar la gestión de sus clientes/as, gafas, proveedores/as, empleados/as y ventas.

---

## 📦 Requisitos de la base de datos

### 🛍️ Proveedores

Cada gafa debe estar relacionada con un proveedor. Se debe almacenar:

- Nombre
- Dirección completa: calle, número, piso, puerta, ciudad, código postal y país
- Teléfono
- Fax
- NIF

### 👓 Gafas

De cada gafa se debe registrar:

- Marca
- Graduación de cada vidrio
- Tipo de montura (flotante, pasta o metálica)
- Color de la montura
- Color de cada vidrio
- Precio
- Relación con su proveedor

### 👥 Clientes

Se desea almacenar:

- Nombre completo
- Dirección postal
- Teléfono
- Correo electrónico
- Fecha de registro
- Cliente/a que lo/a ha recomendado (opcional)

### 👨‍💼 Empleados

Se registran como responsables de las ventas:

- Nombre y otros datos de contacto

### 🧾 Ventas

Cada venta debe guardar:

- Empleado/a que realizó la venta
- Cliente/a que compró
- Gafa vendida
- Fecha y hora de la venta

---

## 🧪 Ejercicios

### ✅ Ejercicio 1 - Interfaz cliente

Diseñar la base de datos desde la **perspectiva de un/a cliente/a** que interactúa con la interfaz gráfica.

### ✅ Ejercicio 2 - Interfaz gafas

Diseñar la base de datos desde la **perspectiva de una gafa**.

---

## 🛠️ Herramientas

- MongoDB
- MongoDB Compass / Terminal
- JSON
- Git / GitHub
