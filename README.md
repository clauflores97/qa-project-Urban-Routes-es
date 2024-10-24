
# qa-project-Urban-Routes-es
# Pruebas Automatizadas para Urban Routes
## Claudia Dinora Flores Cruz, cohorte 14
En este proyecto se utilizaron las técnicas estudiadas en el sprint 8. Para el orden y mejoramiento del código se utilizó principalmente el model POM, en el que la página web se convierte en una clase, se identifican todos los elementos de la página que se convierten en los atributos de clase y cada una de las iteracciones que se realiza con un elemento de página se vuelve un método. POM sólamente reqiere que se defina los elementos necesarios para la realización de pruebas.

## Técnologías y Técnicas usadas
Selenium es un controlador de navegador. Con ella se puede emular las acciones de un usuario mediante codigo. Selenium convierte los elementos de una pagina web en atributos mediante los localizadores de esos elementos. Mediante DevTools que te permite inspeccionar los elementos de la pagina, se pueden extraer los localizadores particulares de cada elemento necesario para la prueba automatizada. En este proyecto se usaron los metodos setup_class() y teardown_class() como ejemplos de hooks. Con ellos se pudo inicializar el controlador de navegador y cerrarlo para todas las pruebas en conjunto en vez de tener que hacerlo para cada prueba individual.

## Instrucciones para ejecutar las pruebas
1. Crear archivos principales: data.py, main.py, UrbanRoutesPage.py, helpers.py.
2. Crear las variables necesarias en el archivo data.
3. Crear el archivo helper que es de apoyo para recuperar el código sms necesario para realizar pruebas.
4. Crear dentro de UrbanRoutesPage los atributos de clase necesarios para ejecutar pruebas con sus respectivos localizadores únicos y crear los métodos también.
5. Importar los archivos data, helpers al archivo UrbanRoutesPage.
6. En el archivo main, escribir las pruebas necesarias para el procedimiento solicitado, utilizando los metodos del archivo UrbanRoutesPage. 
