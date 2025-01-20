# Foro Hub - Backend Challenge

'Foro Hub' es una aplicación back-end desarrollada con Java y Spring; ofrece una API REST con operaciones CRUD para la gestión de un foro de discusión.

![ForoHub icon](assets/Badge-Spring.png "ForoHub icon")

## Organización del código
El proyecto utiliza Java junto con su framework Spring, Maven/Gradle para gestionar dependencias y MySQL para manejo de bases de datos y persistencia. Está organizado en distintos paquetes:

- **`com.example.foro.models`**: Contiene las clases de modelo que definen la estructura de los datos y su relación con la base de datos.
    - `Usuarios.java`: Define los atributos y relaciones de los usuarios.
    - `Topicos.java`: Define los atributos y relaciones de los tópicos del foro.
    - `Respuestas.java`: Define los atributos y relaciones de las respuestas a los tópicos.

- **`com.example.foro.repository`**: Interfaces de repositorio para interactuar con la base de datos.
    - `UsuarioRepository.java`: Consultas relacionadas con los usuarios.
    - `TopicoRepository.java`: Consultas relacionadas con los tópicos.
    - `RespuestaRepository.java`: Consultas relacionadas con las respuestas.

- **`com.example.foro.service`**: Clases de servicio que implementan la lógica del negocio.
    - `UsuarioService.java`: Lógica de negocio relacionada con los usuarios.
    - `TopicoService.java`: Lógica de negocio relacionada con los tópicos.
    - `RespuestaService.java`: Lógica de negocio relacionada con las respuestas.

- **`com.example.foro.controller`**: Clases controlador que manejan las solicitudes y respuestas de la API REST.
    - `UsuarioController.java`: Endpoints relacionados con los usuarios.
    - `TopicoController.java`: Endpoints relacionados con los tópicos.
    - `RespuestaController.java`: Endpoints relacionados con las respuestas.

El proyecto cuenta con:
- Seguridad mediante API Key, Spring Security y JWT.
- Migraciones de base de datos configuradas con Flyway.
- Documentación de la API generada automáticamente con Springdoc OpenAPI.
- Persistencia de datos gestionada con Spring Data JPA.

## Tecnologías utilizadas
- Java SE 17 o superior
- Maven/Gradle
- Spring Boot 3.x
- Spring Security
- JWT
- Flyway
- MySQL

## Estado del proyecto
Finalizado.

## Autor:
**Brian Sabio**

## Licencia
MIT License

