# sofkaejercicio1agosto4
EJERCICIO 1 - Saucedemo
## VERSIÓN 1.0
## Descripción
Este proyecto contiene pruebas funcionales automatizadas para el flujo de compra en la página [SauceDemo](https://www.saucedemo.com/), utilizando Serenity BDD y WebDriverManager para la gestión de los navegadores.

## Prerrequisitos

- JDK 11 o Superior 
- Maven
- IDE compatible (Pruebas realizadas en Eclipse)
- Chrome versión 114.

## Ejecución

1. Clonar el repositorio instalado
2. Abrir el repositorio con el Eclipse (en este caso)
3. Importar el repositorio File - Import - Maven - Existing Maven Projects
4. Actualizar dependencias en caso de ser necesario (Click derecho sobre el proyecto en Eclipse y luego Maven - Update Project)
5. Para ejecutar las pruebas: click derecho sobre el proyecto en Eclipse y luego Run As - Maven Test

El reporte de las pruebas se encontrará en el directorio del proyecto (target/surefire-reports)

## VERSIÓN 2.0

## Requisitos

- Node.js
- npm (Node Package Manager)
- Cypress

## Instalación

1. Clonar o descargar este repositorio (nuevo zip file)
2. Navegar al directorio del proyecto: cd saucedemo-test
3. Instala las dependencias con npm install

## Ejecución de las pruebas
1. npx cypress open

## Beneficios
1. No necesita una versión específica de Chrome para funcionar.
2. Menos archivos creados
3. Menos configuración para ejecutar.

## Datos extra configuración
Configuración adicional para Chrome (En caso de ser necesario):
1. Deshabilitar la caché del navegador y ejecutar Cypress en modo sin cabeza (headless):
npx cypress run --browser chrome --headless --config video=false,chromeWebSecurity=false

## Comentario extra
1. Se añade EVIDENCIA de que tanto las pruebas con Selenium como las de Cypress SÍ FUNCIONAN
2. Para las pruebas de Selenium es requerido CHROME VERSIÓN 114 o inferiores. 
