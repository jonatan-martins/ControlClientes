# ControlClientes

## Descripción

Este proyecto es una aplicación de control de clientes que utiliza el patrón de diseño MVC (Modelo-Vista-Controlador) para gestionar clientes y sus datos. La aplicación se conecta a una base de datos MySQL para recuperar y almacenar información de clientes, y utiliza JSP para la capa de presentación.

## Estructura del Proyecto

1. **Capa de Presentación**: Utiliza JSP y Bootstrap para la interfaz de usuario.
2. **Capa de Controlador**: Implementada con `ServletControlador`, que maneja las solicitudes del usuario y las respuestas.
3. **Capa de Datos**: Implementada con `ClienteDaoJDBC` para interactuar con la base de datos.
4. **Capa de Modelo**: Representada por la clase `Cliente`.

## Requisitos

- Java 8+
- Apache Maven
- MySQL

## Instalación

1. Clona este repositorio:
   git clone https://github.com/jonatan-martins/ControlClientes.git

2. Configura la base de datos MySQL con el script proporcionado en el directorio /sql.
3. Configura las credenciales de la base de datos en la clase Conexion.java.
4. Compila y ejecuta el proyecto con Maven:
    mvn clean install
    mvn tomcat7:run

## Proposito del proyecto
Este proyecto ha sido realizado como parte de un curso de programación en Java, en el cual se requería desarrollar una aplicación utilizando el patrón de diseño MVC. El curso se centra en enseñar buenas prácticas de desarrollo, incluyendo el uso de Servlets, JSP, y la conexión a bases de datos.

URL al curso: https://www.udemy.com/course/universidad-java-especialista-en-java-desde-cero-a-master

## Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.
   
