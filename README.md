# Ecommerce-TrabajoFinal

Este proyecto es un e-commerce desarrollado con el stack MERN (MongoDB, Express, React y Node.js). El sistema permite a los usuarios navegar por categorías de productos, ver detalles, agregar productos al carrito y procesar compras. Además, los administradores pueden gestionar productos, categorías y órdenes.

Scripts disponibles: Para ejecutar la aplicación, se usa:

npm start: Esto inicia la aplicación en modo de desarrollo. Una vez iniciado, puedes acceder desde el navegador en http://localhost:3000. Los cambios que hagas se reflejan automáticamente, y los errores de lint aparecen en la consola.
Descripción del proyecto: El e-commerce tiene dos partes principales:

Frontend: Está desarrollado en React y ofrece una interfaz interactiva para realizar compras, agregar productos al carrito y explorar las categorías.
Backend: Utiliza Node.js y Express para manejar la lógica del servidor, incluyendo la gestión de productos, categorías y órdenes. También implementa JWT para autenticar usuarios y controlar el acceso administrativo.
Funciones principales:

Navegar por categorías.
Ver detalles de productos.
Agregar productos al carrito y completar la compra.
Gestión de productos, categorías y usuarios con autenticación basada en JWT.
Tecnologías utilizadas:

Frontend: React, APIs (para estado y comunicación), HTML, CSS y JavaScript.
Backend: Node.js, Express y JWT.
Base de datos: MongoDB con Mongoose.
Control de versiones: Git y GitHub.
Configuración:

Backend:

Navega al directorio del backend: cd backend.
Instala las dependencias con: npm install.
Frontend:

Ve al directorio del frontend: cd frontend.
Instala las dependencias con: npm install.
Estructura de la base de datos:

Usuarios: Guarda información de los usuarios, incluidas las credenciales de autenticación.
Productos: Almacena los productos disponibles para la venta.
Categorías: Contiene las categorías de los productos.
Carrito: Administra los productos agregados por los usuarios.
Órdenes: Registra la información de las compras realizadas.