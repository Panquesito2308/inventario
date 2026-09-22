# Sistema de Inventario para Abarrotera

Este proyecto consiste en un sistema básico de inventario para una abarrotera.
El sistema permite almacenar información básica de cada producto, como:

- Nombre del producto
- Cantidad disponible

## Tecnologías utilizadas
El proyecto fue desarrollado utilizando las siguientes tecnologías:

- HTML
- CSS
- PHP 8.2.12
- MySQL
- PDO (PHP Data Objects)

## Requisitos
Para ejecutar el proyecto de manera local es necesario contar con alguno de los siguientes entornos:
- XAMPP
- Laragon

Estos permiten utilizar Apache como servidor web y MySQL como gestor de base de datos.

### Descargar el proyecto

Descarga o copiar la carpetas en tu computadora.

Si utilizas XAMPP, coloca la carpeta del proyecto dentro de:
C:\xampp\htdocs\

Por ejemplo:
C:\xampp\htdocs\inventario\
Si utilizas Laragon, coloca el proyecto dentro de la carpeta correspondiente

### Crear la base de datos

Inicia Apache y MySQL desde XAMPP o Laragon.
Posteriormente, accede a phpMyAdmin y crea una base de datos con el siguiente nombre:

CREATE DATABASE inventario;

Después, selecciona la base de datos agregando al inicio del script SQL:
USE inventario;

Finalmente, ejecuta el resto del script SQL correspondiente al proyecto para crear las tablas necesarias.

### Ejecutar el proyecto

Con Apache y MySQL encendidos, abre tu navegador y accede a:
http://localhost/inventario/index.php
Si todo está configurado correctamente, se mostrará el sistema de inventario.
