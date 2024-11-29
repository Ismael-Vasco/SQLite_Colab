# Sistema de Registro de Donantes de Sangre

Este proyecto permite registrar, buscar, actualizar y eliminar información de donantes de sangre en una base de datos SQLite. Los donantes pueden ser registrados con sus datos personales, tipo de sangre, ubicación y contacto. La aplicación facilita encontrar un donante de sangre según su tipo de sangre y ubicación, además de gestionar la información a través de funciones CRUD (Crear, Leer, Actualizar, Eliminar).

## Características

- **Registrar Donantes**: Permite agregar nuevos donantes a la base de datos.
- **Buscar Donante**: Permite buscar un donante por su cédula.
- **Actualizar Datos**: Permite actualizar los datos de un donante.
- **Eliminar Donante**: Permite eliminar un donante de la base de datos.
- **Interfaz en consola**: Interfaz de usuario basada en texto para interactuar con el sistema.

## Tecnologías

- Python 3
- SQLite (base de datos)

## Requisitos

Para ejecutar este proyecto, necesitas tener instalado Python 3.x y las librerías estándar de Python.

## Instalación

1. Clona o descarga este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/donantes_sangre.git

Estructura de la tabla donantes_sangre:
Columna	Tipo de dato
id	INTEGER
nombre	TEXT
apellido	TEXT
cedula	INTEGER
tipo_sangre	TEXT
ubicacion	TEXT
contacto	INTEGER
