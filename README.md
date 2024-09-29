# 🍼 Banco de Leche Materna - Backend

Este es el **backend** del sistema de gestión para el Banco de Leche Materna, diseñado para administrar información sobre donantes, neonatos y leche materna de manera eficiente y segura. 🚀

## ✨ Características Principales

- 👥 **Gestión de Donantes**: CRUD completo para la información de donantes.
- 🍼 **Control de Leche Materna**: Registro y seguimiento del inventario de leche donada.
- 👶 **Gestión de Neonatos**: Administración de la información de los neonatos beneficiados.
- 🔐 **Autenticación y Autorización**: Seguridad mediante JWT.
- ✅ **Validación de Datos**: Validación robusta usando `express-validator`.

## 🛠️ Tecnologías Utilizadas

- 🟢 **Node.js**: Plataforma para ejecutar JavaScript en el servidor.
- ⚡ **Express**: Framework para crear aplicaciones web.
- 🍃 **MongoDB**: Base de datos NoSQL para el almacenamiento de la información.
- 🎛️ **Mongoose**: ODM para MongoDB.
- 🔑 **JWT (JSON Web Token)**: Autenticación y autorización seguras.
- 🌍 **dotenv**: Manejo de variables de entorno.

## ⚙️ Requisitos Previos

Antes de comenzar, asegúrate de tener lo siguiente instalado:

- [🟢 Node.js](https://nodejs.org/) v14.0.0 o superior.
- [🍃 MongoDB](https://www.mongodb.com/) v4.4.0 o superior.
- [🐙 Git](https://git-scm.com/).

## 🚀 Instalación y Configuración

Sigue estos pasos para instalar y configurar el proyecto:

1. Clona el repositorio: 
    ```bash
    git clone https://github.com/Raziel-jm-code/banco_de_leche-backend.git
    ```

2. Navega al directorio del proyecto:
    ```bash
    cd banco_de_leche-backend
    ```

3. Instala las dependencias:
    ```bash
    npm install
    ```

4. Crea un archivo `.env` con las siguientes variables de entorno:
    ```env
    PORT=3000
    MONGODB_URI=mongodb://localhost:27017/banco_de_leche
    JWT_SECRET=tu_secreto_para_jwt
    ```

## 🏃 Ejecución del Proyecto

Para iniciar el servidor en modo de desarrollo, utiliza el comando:

```bash
npm run dev
```
El servidor estará disponible en [http://localhost:3000](http://localhost:3000). 🎉

## 📜 Scripts Disponibles
- `npm run dev`: Inicia el servidor en modo desarrollo.
- `npm start`: Inicia el servidor en modo producción.

## 📝 Funcionalidades del Sistema
- 👥 **Gestión de Donantes**: Operaciones CRUD sobre la información de donantes.
- 🍼 **Registro de Leche Materna**: Seguimiento de la leche materna donada.
- 👶 **Administración de Neonatos**: Información detallada de los neonatos.
- 🔐 **Autenticación de Usuarios**: Seguridad mediante JWT.
- ✅ **Validación de Datos**: Uso de `express-validator` para validar los datos de entrada.

## 🤝 Contribuciones
¡Tus contribuciones son bienvenidas! 💡 Sigue estos pasos para contribuir:

1. Haz un fork del repositorio.
2. Crea una nueva rama:
    ```bash
    git checkout -b nueva-funcionalidad
    ```
3. Realiza los cambios y confirma los commits:
    ```bash
    git commit -m 'Añadir nueva funcionalidad'
    ```
4. Empuja los cambios:
    ```bash
    git push origin nueva-funcionalidad
    ```
5. Crea un Pull Request y espera la revisión. 🔍

## 📬 Contacto
Si tienes alguna pregunta o sugerencia, puedes contactarnos:

- **Raziel Jiménez Mendoza**: [2173072772@correo.ler.uam.mx](mailto:2173072772@correo.ler.uam.mx)
- **Raúl Estrada Gregorio**: [2173072656@correo.ler.uam.mx](mailto:2173072656@correo.ler.uam.mx)


