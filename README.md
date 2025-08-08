# 📚 API REST – Gestión de Libros

Proyecto personal que implementa una **API REST** para la gestión de libros (*Books*), desarrollada con **Node.js**, **Express** y **MongoDB**, utilizando **Mongoose** para la modelación de datos y **Docker** para la contenedorización del entorno.

Permite realizar operaciones CRUD completas (crear, leer, actualizar y eliminar) con validaciones, manejo de errores y una arquitectura modular.

---

## 🚀 Tecnologías Utilizadas

- **Node.js** – Entorno de ejecución de JavaScript.
- **Express** – Framework para crear aplicaciones y APIs.
- **MongoDB** – Base de datos NoSQL.
- **Mongoose** – Modelado de datos para MongoDB.
- **Docker** – Contenerización de la base de datos.
- **dotenv** – Gestión de variables de entorno.
- **body-parser** – Parseo de cuerpos de solicitud.

---

## 📚 Endpoints Disponibles

| Método  | Endpoint      | Descripción                 |
|---------|--------------|-----------------------------|
| GET     | `/books`     | Obtener todos los libros    |
| GET     | `/books/:id` | Obtener un libro por ID     |
| POST    | `/books`     | Crear un nuevo libro        |
| PUT     | `/books/:id` | Actualizar libro completo   |
| PATCH   | `/books/:id` | Actualizar libro parcial    |
| DELETE  | `/books/:id` | Eliminar un libro           |
