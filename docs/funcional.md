# Especificación Funcional — Lista de la Compra

## Pantallas principales

1. **Login** — email + contraseña

2. **Lista principal** — tabs: Todos / Mercadona / Ahorramás / ALDI

3. **Producto en lista** — nombre, supermercado asignado, estado

4. **Añadir producto** — formulario mínimo

## Estados de un producto

| Estado | Descripción |
| - | - |
| FALTA | Producto identificado como necesario |
| ASIGNADO | Asignado a un supermercado concreto |
| COMPRADO | Ya se ha comprado (desaparece de la lista activa) |


## Usuarios

- Registro con email y contraseña (Firebase Auth)

- Un administrador (gestiona usuarios)

- Varios miembros de familia (editan la lista)

## Sincronización

- Firebase Realtime Database → cambios visibles en segundos

- Sin necesidad de recargar la página

## Productos recurrentes (ejemplos reales de tickets)

| Producto | Supermercado habitual |
| - | - |
| Leche Entera P6 | Mercadona |
| Queso Gouda Lonchas | Mercadona / ALDI |
| Aceite Virgen 3L | Mercadona |
| Huevos Grandes L (12u) | Mercadona / Ahorramás |
| Salmón Ahumado | Mercadona |
| Pechuga de Pollo | Ahorramás |
| Carne Picada Mixta | Ahorramás |
| Jamón Cocido Lonchas | ALDI |
| Bacon en Lonchas | ALDI |
| Lentils (snacks) | Mercadona |


