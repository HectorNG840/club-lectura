# Plataforma de Club de Lectura - TFM

Repositorio correspondiente al Trabajo Final de Máster del Máster de Desarrollo de Sitios y Aplicaciones Web de la UOC.
Este proyecto contiene el prototipo y la arquitectura base de una plataforma literaria interaciva, dividida en cliente (Angular) y servidor (Node.js).

## Tecnologías utilizadas
* **Front-end:** Angular, SCSS (Arquitectura ITCSS y metodología BEM).
* **Back-end:** Node.js, Express.
* **Base de datos:** MariaDB.

## Requisitos previos
Para poder ejecutar el proyecto en local, es necesario tener instalado:
* [Node.js](https://nodejs.org/es) (Versión 18 o superior)
* [Angular CLI](https://v17.angular.io/docs) (`npm install -g @angular/cli`)
* Servidor local de bases de datos MariaDB.

## Intrucciones de Instalación y Ejecución

El proyecto está dividido en dos carpetas, una correspondiente al Front-end y la otra al Back-end. Se deben abrir dos terminales distintas para ejecutar ambas partes del proyecto.

## 1. Configuración del Back-end (Servidor)
1. Abre una terminal y sitúate en la carpeta del servidor:
    cd backend-club-lectura

2. Instala las dependencias del proyecto:
    ```bash
    npm install
    ```

3. Variables de entorno:
   * Copia el archivo de ejemplo `.env.example` y renómbralo a `.env`.
   * Abre el archivo `.env` e introduce tus credenciales locales de MariaDB (usuario, contraseña y base de datos).

4. Arranca el servidor:
    ```bash
    node src/index.js
    ```


### 2. Configuración del Front-end (Cliente)
1. Abre una nueva terminal y sitúate en la carpeta del cliente:
    ```bash
    cd frontend-club-lectura
    ```

2. Instala las dependencias del proyecto:
    ```bash
    npm install
    ```

3. Levanta el servidor de desarrollo de Angular:
    ```bash
    ng serve
    ```

4. Abre tu navegador y accede a `http://localhost:4200/`.