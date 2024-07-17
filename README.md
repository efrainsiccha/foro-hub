# 🌟 ForoHub 🌟

¡Bienvenido a ForoHub!, una API que permite realizar diferentes solicitudes REST:
* Iniciar Sesion
* Registrar un topico
* Actualizar un Topico
* Eliminar un topico
* Listar topicos

## 🚀 Servidores
La API se despliega localmente en:
* Base URL: http://localhost:8080

##  Autorización
La API requiere autorización mediante tokens JWT para acceder a ciertas funciones.

## ✅ Tecnologías Utilizadas
- Java 🔧
- Maven 🔧
- Spring Boot 🔧
- Spring Data JPA 🔧
- MySQL 🔧
- JWT (JSON Web Tokens) 🔧

## 🌟 Endpoints
### Tópicos (`topico-controller`)

- **Actualizar un tópico**
    - `PUT /topico/{id}`
    - Body: `DatosActualizarTopico`

- **Crear un nuevo tópico**
    - `POST /topico`
    - Body: `DatosRegistroTopico`

- **Listar todos los tópicos**
    - `GET /topico`
    - Respuesta: `List<PageDatosListadoTopico>`

- **Listar un topico por "ID"**
    - `GET /topico/{id}`
    - Respuesta: `PageDatosListadoTopico`

- **Eliminar un tópico (lógico)**
    - `DELETE /topico/{id}`

### Autenticación (`autenticacion-controller`)

- **Iniciar sesión (login)**
    - `POST /login`
    - Body: `DatosAutenticacionUsuario`
    - Respuesta: `DatosJWTtoken`

¡Gracias por utilizar ForoHub! Espero que te sea útil y que tengas una excelente experiencia. ¡Feliz ForHub! 🚀✨
