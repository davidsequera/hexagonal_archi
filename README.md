# Taller de Arquitectura de Software - Laboratorio 2

## Pontificia Universidad Javeriana
### Integrantes:
- Mario Alejandro Ortiz
- David Alejandro Sequera
- David Mateo Henao
### Fecha de entrega: 15/11/2023
### Bogotá D.C.

---

## Descripción

Este taller de Arquitectura de Software tiene como objetivo principal familiarizar a los estudiantes con la implementación de un proyecto utilizando diversas tecnologías y herramientas fundamentales en el desarrollo de aplicaciones modernas. A lo largo del laboratorio, se abordan conceptos clave como JDK 11, Spring Boot, bases de datos (MongoDB y MariaDB), REST, CLI, Swagger 3 y Lombok, explorando su utilidad y aplicación en la construcción de sistemas robustos.

---

## Marco Conceptual

A continuación, se detallan algunos de los conceptos fundamentales abordados en este taller:

- **JDK 11:** Versión de la plataforma Java SE de código abierto, esencial para la implementación del proyecto.
- **Spring Boot:** Framework web de Java, proporcionando herramientas útiles para desarrolladores enfocados en aplicaciones web y microservicios.
- **MongoDB:** Base de datos de documentos altamente escalable y flexible, con un modelo de consultas e indexación avanzado.
- **MariaDB:** Importante base de datos relacional de código abierto, desarrollada por los creadores originales de MySQL.
- **REST:** Interfaz para conectar sistemas basados en el protocolo HTTP, permitiendo la manipulación de datos en formatos específicos como XML y JSON.
- **CLI:** Interfaz de usuario de computadora basada en texto que permite la interacción con programas y sistemas operativos mediante comandos.
- **Swagger 3:** Herramienta de visualización para analizar la especificación OpenAPI y generar una consola de API para facilitar la comprensión y ejecución de las mismas.
- **Lombok:** Librería que simplifica la visualización de información en páginas HTML, utilizada en proyectos Spring con arquitectura MVC y para crear plantillas bajo estándares de XML/XHTML/HTML5.

---

## Diseño y Procedimiento

### 1. Instalación de Bases de Datos
- **MariaDB en Puerto 3307:** Instalar y configurar MariaDB para ejecutarse en el puerto 3307.
- **MongoDB en Puerto 27017:** Descargar e instalar MongoDB, configurándolo para utilizar el puerto 27017.

### 2. Ejecución de Scripts en Bases de Datos
- Asegurar el funcionamiento de MariaDB y MongoDB.
- Ejecutar los scripts proporcionados en las bases de datos correspondientes.

### 3. Configuración de Adaptador REST y Swagger
- Verificar la correcta configuración del adaptador REST para su ejecución en el puerto 3000.
- Confirmar la disponibilidad de Swagger en http://localhost:3000/swagger-ui.html.

### 4. Configuración de SpringApplication y Lombok en IDEs
- Configurar y ejecutar dos instancias de SpringApplication, cada una asociada con un adaptador de entrada diferente.
- Configurar Lombok en los Entornos de Desarrollo Integrados (IDEs) utilizados (por ejemplo, IntelliJ IDEA, Eclipse).

### 5. Hacer Fork al Repositorio
- Realizar una copia (fork) del repositorio proporcionado para trabajar en una versión propia del proyecto, evitando editar el repositorio original.

---

## Aspectos Destacados

### 1. Configuración del Entorno
La correcta instalación y configuración de las bases de datos en puertos específicos es crucial para el funcionamiento del sistema.

### 2. Diversidad de Tecnologías
El uso de diferentes adaptadores y múltiples instancias de SpringApplication resalta una arquitectura modular que potencia la flexibilidad y escalabilidad del sistema.

### 3. Documentación y Testing
La presencia de Swagger subraya la importancia de documentar la API, facilitando su comprensión y fomentando buenas prácticas de desarrollo. La ejecución de scripts en bases de datos resalta la necesidad de pruebas y verificación de la consistencia de los datos.

### 4. Configuración de IDEs
La configuración de Lombok en los Entornos de Desarrollo Integrados enfatiza la importancia de herramientas que mejoren la productividad y reduzcan la complejidad del código, impactando positivamente en la eficiencia del desarrollo.

### 5. Colaboración y Control de Versiones
La opción de hacer Fork al repositorio y la advertencia sobre la edición del repositorio original resaltan la importancia de una buena gestión de versiones y la posibilidad de colaborar en proyectos sin afectar la versión principal.

---

## Lecciones Aprendidas

### 1. Configuración Estandarizada
Establecer estándares para la configuración de bases de datos, adaptadores y entornos de desarrollo facilita la colaboración y garantiza la ejecución coherente del proyecto en diversos entornos.

### 2. Documentación Clara y Accesible
La documentación clara y completa, especialmente en proyectos con varias tecnologías, agiliza la comprensión del sistema y acelera el proceso de desarrollo.

### 3. Pruebas y Verificación
La ejecución de pruebas y la verificación de la integridad de los datos son fundamentales para asegurar la calidad del software y prevenir problemas futuros.

### 4. Flexibilidad y Modularidad
El enfoque de diseño flexible y modular permite adaptar el sistema a cambios y agregar nuevas funcionalidades de manera eficiente.

### 5. Gestión de Repositorios
El uso adecuado de sistemas de control de versiones como Git, incluyendo conceptos como Forking y Pull Requests, es esencial para una colaboración efectiva en proyectos de desarrollo de software.

---

## Referencias
- [JDK 11](https://openjdk.org/projects/jdk/11/)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [MongoDB](https://www.mongodb.com/es/what-is-mongodb)
- [MariaDB](https://mariadb.org/)
- [REST](https://openwebinars.net/blog/que-es-rest-conoce-su-potencia/)
- [CLI](https://www.hostinger.co/tutoriales/que-es-cli)
- [Swagger](https://swagger.io/)
- [Lombok](https://projectlombok.org/)

Este taller proporciona una comprensión integral de conceptos clave en el desarrollo de software moderno, destacando la importancia de la configuración, documentación, pruebas y colaboración en la creación de sistemas robustos y escalables.