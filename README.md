# EJERCICIO

Pruebas de calidad y automatización

# AUTOMATIZACION

# REQUISITOS PREVIOS

- Contar con una versión de Node.js superior a la 20 instalada en el sistema.
  npm install

- Instalar Cypress. Para ello, abre una terminal en la carpeta EJERCICIOS y ejecuta el siguiente comando:

npm install cypress --save-dev

# ESTRUCTURA DEL PROYECTO

En el directorio e2e se encuentran dos subcarpetas, correspondientes a las soluciones de los ejercicio 1 y 2.
Dentro del directorio fixtures están mapeados los componentes de la página web, los cuales se utilizan como referencia en ambos ejercicios.

# EJECUCIÓN POR CONSOLA

1.- Para ejecutar todas las pruebas sin necesidad de abrir el navegador, ejecuta el siguiente comando:
npx cypress run

# EJECUCIÓN POR NAVEGADOR

1.- Abre una terminal y ejecuta el siguiente comando para iniciar Cypress:
npx cypress open

2.- Selecciona la opción E2E Testing y haz clic en Configured.

3.- Se abrirá una ventana donde deberás elegir el navegador. Selecciona Chrome y presiona el botón Start E2E Testing in Chrome.

4.- En la pantalla llamada SPECS, elige el archivo que deseas ejecutar:

Ejercicio 1: navega a la carpeta EJERCICIO1 y selecciona el archivo flujoCompra.cy.js para iniciar el test runner.

Ejercicio 2: navega a la carpeta EJERCICIO2 y selecciona el archivo registro.cy.js para ejecutar sus pruebas.

# CONCLUSIONES

Las conclusiones se encuentran documentadas en el archivo Conclusiones.txt dentro del proyecto.
