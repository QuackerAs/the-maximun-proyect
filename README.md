# Manual de Usuario - Proyecto MasterBread

Bienvenido al proyecto MasterBread. Esta es una versión beta y necesitarás seguir estos pasos para configurar el entorno de desarrollo:

## Requisitos Previos
- Visual Studio Code
- Node.js
- MySQL Workbench
- Postman

## Pasos de Instalación

1. **Configuración del Proyecto**
  - Abrir la carpeta "menu operaciones" en VS Code
  - Navegar a la carpeta "server" desde la terminal

2. **Instalación de Dependencias**
  - Ejecutar `npm i` para instalar todas las dependencias

3. **Configuración de Base de Datos**
  - Abrir MySQL Workbench
  - Localizar los archivos SQL en la carpeta `server/database`
  - Ejecutar los scripts para crear la base de datos "masterbread"

4. **Configuración de Usuario**
  - Usar Postman para crear un usuario nuevo, o
  - Añadir usuario desde el archivo "datos ficticios" en la carpeta database

5. **Iniciar el Proyecto**
  - dirigete a la carpeta server desde el cmd `cd server`
  - Ejecutar `npm run dev` para iniciar el servidor
  - Abrir el archivo `index.html` con Live Server

## Funcionalidades Disponibles
- Inicio de sesión
- Recuperación de contraseña (requiere email válido)
- Acceso al menú principal de MasterBread

**Nota**: Para acceso completo al servidor, contactar al administrador para obtener los archivos de configuración necesarios.

¡Gracias por ser parte de nuestros beta testers! Para cualquier consulta o problema, no dudes en contactarnos.
