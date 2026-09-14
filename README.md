# Biblioteca Digital UNTEC

Proyecto final del Módulo 5: Desarrollo de aplicaciones web dinámicas en Java.

## Descripción

Aplicación web para gestionar el catálogo y los préstamos de una biblioteca digital. Permite iniciar sesión, consultar libros, agregar, editar y eliminar libros, registrar préstamos y realizar devoluciones.

## Tecnologías utilizadas

- Java EE
- JSP
- Servlets
- JSTL
- JDBC
- MySQL
- Apache Tomcat 9
- Eclipse Enterprise
- HTML y CSS
- Patrón MVC
- Patrón DAO
- Patrón Singleton

## Requisitos

- Java JDK 8 o superior
- Eclipse IDE for Enterprise Java and Web Developers
- Apache Tomcat 9
- MySQL Server 8
- MySQL Workbench

## Base de datos

Nombre de la base de datos:

`biblioteca_untec`

La aplicación utiliza tres tablas:

- `usuarios`
- `libros`
- `prestamos`

Usuario de conexión:

- Usuario: `biblioteca_user`
- Clave: `Biblioteca123!`

## Acceso a la aplicación

Usuario de prueba:

- Correo: `admin@untec.cl`
- Contraseña: `1234`

Dirección local:

`http://localhost:8080/BibliotecaDigitalUNTEC/`

## Funciones principales

- Inicio y cierre de sesión.
- Listado de libros.
- Registro de nuevos libros.
- Modificación y eliminación de libros.
- Registro de préstamos.
- Devolución de libros.
- Eliminación de préstamos.
- Actualización automática del estado de disponibilidad.

## Organización MVC

- Modelo: clases Libro, Usuario y Prestamo.
- Vista: archivos JSP, HTML, CSS y JSTL.
- Controlador: LoginServlet, LibroServlet, PrestamoServlet y LogoutServlet.
- Acceso a datos: LibroDAO, UsuarioDAO y PrestamoDAO.
- Conexión: ConexionBD mediante JDBC y patrón Singleton.

## Ejecución

1. Importar el proyecto en Eclipse.
2. Configurar Apache Tomcat 9.
3. Crear la base de datos `biblioteca_untec` en MySQL.
4. Comprobar los datos de conexión en `ConexionBD.java`.
5. Agregar el proyecto al servidor.
6. Ejecutar con Run As - Run on Server.
7. Abrir la dirección local en el navegador.

## Autora

Rocío Maldonado