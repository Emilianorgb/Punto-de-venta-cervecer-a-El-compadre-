Sistema de Gestión para la Cervecería "El Compadre"

Introducción

La administración eficiente de un bar o cervecería requiere controlar múltiples procesos de forma simultánea, como la gestión de clientes, empleados, productos, inventario, compras, ventas, mesas y pagos. Cuando estas actividades se realizan de manera manual o mediante herramientas independientes, es común que se presenten errores en el registro de información, pérdidas de inventario, retrasos en la atención al cliente y dificultades para generar reportes que apoyen la toma de decisiones.

Planteamiento del Problema

Actualmente, muchos bares y cervecerías administran sus operaciones utilizando registros manuales o aplicaciones que no están integradas entre sí. Esta situación ocasiona problemas como:

-Errores en el registro de ventas.
-Pérdida o duplicidad de información.
-Descontrol del inventario.
-Dificultad para conocer la disponibilidad de productos.
-Retrasos en la asignación de mesas.
-Falta de control sobre los pagos realizados.
-Escasa generación de reportes para la administración del negocio.

Estas limitaciones afectan la productividad del establecimiento y dificultan la toma de decisiones oportunas.

Con el propósito de optimizar la operación del establecimiento, se propone desarrollar un Sistema de Gestión para Bar y Cervecería que centralice toda la información en una única plataforma, permitiendo automatizar los procesos administrativos y operativos mediante una interfaz gráfica intuitiva y una base de datos relacional.

Justificación

El desarrollo de un sistema informático permitirá automatizar las actividades principales del negocio, reduciendo errores humanos y mejorando el control de la información.

Además, facilitará el seguimiento de las ventas, el control del inventario, la administración de clientes y proveedores, así como la generación de reportes que apoyen la toma de decisiones del administrador.

La implementación de este sistema contribuirá a mejorar la eficiencia operativa, optimizar los tiempos de atención y proporcionar una administración más organizada y segura.

🎯 Objetivo General

Desarrollar un sistema de gestión para un bar y cervecería que permita administrar de manera eficiente los procesos de ventas, compras, inventario, clientes, empleados, proveedores, mesas y pagos, utilizando una arquitectura Modelo-Vista-Controlador (MVC), una base de datos MySQL y una interfaz gráfica intuitiva.

🎯 Objetivos Específicos

-Diseñar una base de datos relacional que garantice la integridad de la información.
-Implementar un sistema de autenticación para el acceso de los usuarios.
-Administrar la información de clientes, empleados y proveedores.
-Gestionar el catálogo de productos y sus categorías.
-Controlar las existencias del inventario.
-Registrar compras realizadas a proveedores.
-Registrar ventas efectuadas a los clientes.
-Gestionar la ocupación de las mesas.
-Registrar los pagos asociados a las ventas y compras.
-Generar reportes para apoyar la toma de decisiones.
-Desarrollar una interfaz gráfica intuitiva y fácil de utilizar.

Funcionalidades

- 🔐 Inicio de sesión de usuarios.
- 👥 Gestión de clientes.
- 👨‍💼 Gestión de empleados.
- 🚚 Gestión de proveedores.
- 🍺 Administración de productos.
- 📦 Control de inventario.
- 🛒 Registro de compras.
- 💳 Registro de ventas.
- 🪑 Administración de mesas.
- 💵 Registro de pagos.
- 📊 Generación de reportes.


Tecnologías Utilizadas

- Lenguaje:** Java
- Arquitectura: Modelo - Vista - Controlador (MVC)
- Base de Datos: MySQL
- IDE:** IntelliJ IDEA
- Conectividad: JDBC
- Control de Versiones: Git y GitHub

Estructura del Proyecto

src

├── controller

├── model

│        ├── dao

│        ├── entities

│        └── connection

├── view

├── service

└── utils

Roles del Sistema

Administrador
- Gestiona usuarios y permisos.
- Administra la información del sistema.
- Consulta reportes.

Mesero
- Registra pedidos y ventas.
- Gestiona las mesas.
- Registra pagos.

Encargado de Inventario
- Administra productos.
- Gestiona proveedores.
- Controla el inventario.
- Registra compras.

Licencia

Este proyecto fue desarrollado con fines académicos y de aprendizaje.
