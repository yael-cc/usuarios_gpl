# Cuevas Cruz Luis Angel Yael
## Desarrollo de Servicios Web
## Docente: M.C. Israel Arjona Vizcaíno

# Proyecto Base - GraphQL con Apollo Server

Este proyecto es una base para implementar un servidor GraphQL utilizando Apollo Server. Incluye la configuración básica de esquemas, resolvers y el servidor.

## Estructura del Proyecto

- **index.js**: Archivo principal que configura y arranca el servidor Apollo.
- **schemas/typeDefs.js**: Contiene la definición de los esquemas GraphQL.
- **controllers/userController.js**: Contiene los resolvers para manejar las operaciones definidas en los esquemas.

## Endpoints GraphQL

### Consultas (Queries)

- **getUsers**: Obtiene una lista de todos los usuarios.
- **getUser(id: ID!)**: Obtiene un usuario específico por su ID.

### Mutaciones (Mutations)

- **createUser(name: String!, email: String!)**: Crea un nuevo usuario.
- **updateUser(id: ID!, name: String, email: String)**: Actualiza un usuario existente.
- **deleteUser(id: ID!)**: Elimina un usuario existente.