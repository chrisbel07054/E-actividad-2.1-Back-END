## Requisitos e instalación:
## Requisitos: Node.JS y MongoDB

## Descarga del Proyecto: El proyecto se descarga desde nuestro repositorio, desde la rama Main, luego se extrae el contenido a partir de Git Clone o GitHub Desktop

### Variables: Deben agregar 2 archivos en especifico que poseerán las variables de entorno de nuestro sistema: "env" para la carpeta del Back-End y ".env.local" para la carpeta del Front-End, con la opción de copiar las variables de entorno que proporcionaremos desde el Figma

4- Inicio: Deberán acceder a las carpetas de nuestros proyectos con la terminal de su preferencia, ejecutan la carpeta del Back-End desde un terminal o editor de tu preferencia, mientras que la del Front-End en otro Terminal, ejecutan los comandos "npm install" para las instalación de dependencias desde ambas terminales, luego ejecutan ambos terminales con "npm run start"(Back-End), "npm run dev“(Front-End) se dirigen hacía el localhost:3000 y ahi encontraran la pagina web iniciada.

Además, si lo deseas, puedes importar los datos JSON que dejamos en Documentos, a la Base de Datos del Sistema con MongoDB u Compass

Instrucciones Detalladas
Paso 1

# Descarga el repositorio o clonalo (https://github.com/LuisiCarre19/E-actividad-2.1-FrontEndII)

`git clone https://github.com/LuisiCarre19/E-actividad-2.1-FrontEndII`
Paso 2

### Ubicate en la carpeta clonada o descargada

Cambia a la rama main

cd Proyecto_FrontEnd_II
git checkout main
Paso 3

Abre la carpeta con tu editor de código de preferencia
Abre 2 consolas del editor, una para el FrontEnd y otra para el BackEnd
Paso 4

En una de las consolas ubicate en la ruta del FrontEnd

Ejecuta el comando npm i (Instala todas las dependencias necesarias)

cd FrontEnd
npm i
Paso 5

Crea el archivo .env.local para las rutas del FrontEnd ubicalo en la carpeta FrontEnd
Paso 6

Ejecuta el comando npm run dev (Inicia el servidor de front-end)

npm run dev
Paso 7

En una de las consolas ubicate en la ruta del BackEnd

Ejecuta el comando npm i (Instala todas las dependencias necesarias)

cd BackEnd
npm i
Paso 8

Crea el archivo .env para las configuraciones del backend ubicalo en la carpeta BackEnd
Paso 9

Ejecuta el comando npm run start (Inicia el servidor del back-end)

npm run start
Paso 10

Abre tu Navegador y coloca http://localhost:3000

http://localhost:3000
Fin

Equipo Desarrollador y Motivo del Desarrollo:
Chrisbel Briceño
Gustavo Mendez 
Luisiana Carreño 
