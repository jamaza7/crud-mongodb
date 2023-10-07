### CRUD with MONGODB

Gestión de datos con CRUD utilizando el stack MERN 🔄

## Authores

- [@Jordy Maza](https://github.com/jamaza7)
- [@David Culqui](https://www.github.com/)

## Tabla de Contenidos

- [Instalación](#instalación)
- [Configuracion](#Configuración)
  - [Ejemplos](#ejemplos)
- [---](#configuración)
- [Créditos](#créditos)
- [Licencia](#licencia)

## Instalación

## Installation

Clonar el proyecto

```bash
  git clone https://github.com/jamaza7/crud-mongodb.git

```

Instalacion del proyecto via npm

```bash
  cd crud-mongodb
  npm install

```

## Configuración

Para configurar la conexión a la base de datos MongoDB asegurese de tener una cuenta en [MongoDB Atlas](https://www.mongodb.com/atlas/database) , siga estos pasos:

1. Despues de crear una cuenta en mongodb atlas, debera crear un nuevo proyecto
   ![Mongodb](src/assets/images/create_database_atlas.png)

2. Siguiente paso se procede a conectar la base de datos ![conectar](src/assets/images/conectar.png)

3. Se crea un usuario, contraseña y ip de la base de datos ![usario_password](src/assets/images/username_password.png)
   ![usario_password](src/assets/images/ip.png)

4. En el archivo `.env.example` configure las variables de entorno:

   ```env
   // env.example
    PORT=4000
    MONGODB_URI=mongodb+srv://jamaza:WM3OBQQtvUzMzugz@cluster0.9mjhgh2.mongodb.net/mern-tasks
    TOKEN_SECRET=mysecret
    FRONTEND_URL=http://localhost:5173

     // Otras opciones de configuración
   ;
   ```

### Ejemplos

Ejemplos de uso...

## ---

Instrucciones de configuración...

## Contribución

Instrucciones para contribuir...

## Créditos

Agradecimientos...

## Licencia

Este proyecto está bajo la Licencia XYZ. Consulta el archivo [LICENSE](LICENSE) para más detalles.
