# Proyecto de Gestión de Productos con SQLite en Python

Este es un proyecto básico en Python que utiliza SQLite para gestionar una base de datos de productos. El script realiza operaciones de creación de base de datos, inserción, lectura, actualización y eliminación de registros. Además, también incluye la capacidad de insertar datos en lotes.

## Requisitos

Para ejecutar este proyecto, necesitarás tener Python instalado en tu sistema. Este proyecto utiliza la biblioteca `sqlite3` que está incluida en la instalación estándar de Python.

## Funcionalidades

El script realiza las siguientes operaciones con la base de datos:

1. **Crear una base de datos y tabla de productos**:
   - Se crea una tabla llamada `productos` si no existe, con las siguientes columnas:
     - `id`: un identificador único que se autoincrementa.
     - `titulo`: un título del producto.
     - `descripcion`: descripción detallada del producto.
     - `precio`: el precio del producto.

2. **Insertar un producto**:
   - Se inserta un producto individual en la base de datos.

3. **Leer productos**:
   - Se leen y muestran todos los productos.
   - También es posible leer solo un dato específico (por ejemplo, los títulos de los productos).

4. **Borrar productos**:
   - Se borra todos los productos de la base de datos.

5. **Actualizar productos**:
   - Se actualiza el precio de los productos en función de una condición específica (por ejemplo, actualizar productos con un precio de 700 a 735).

6. **Insertar múltiples productos**:
   - Se insertan varios productos a la vez utilizando una lista de tuplas con datos de productos.

7. **Cerrar la conexión**:
   - Se cierra la conexión con la base de datos después de realizar todas las operaciones.

## Instrucciones de uso

### 1. Clonar o descargar el repositorio

Si deseas trabajar con este proyecto en tu computadora, clona o descarga el repositorio en tu máquina.

```bash
git clone https://github.com/usuario/proyecto-sqlite-python.git
cd proyecto-sqlite-python

https://ghttps://github.com/user-attachments/assets/974d65b2-803b-4e80-b5c3-e8f82d1cbc9dithub.com/user-attachments/assets/974d65b2-803b-4e80-b5c3-e8f82d1cbc9d
