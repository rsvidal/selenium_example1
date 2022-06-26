# Todomvc

Este repo está construido con [Gradle](https://gradle.org/), [JUnit 5](http://junit.org/junit5/), [Selenium](http://www.seleniumhq.org/) y el código está realizado en Java.

Al ejecutar la tarea de test de Gradle, Selenium levantará un Chrome usando el Chromedriver (que viene incluido en este proyecto) y realizará los siguientes test sobre la página web de [todomvc.com](http://todomvc.com/examples/vanillajs/):

* El título es el correcto
* Crear una tarea
* Borrar una tarea
* Editar una tarea
* Filtrar las tareas
* Completar una tarea
* Borrar las tareas completadas

![Todomvc Tests](./todomvc-tests.gif)

## Notas de Rafael San Vidal Hidalgo

[Tutorial Selenium en Jenkins](https://www.adictosaltrabajo.com/tutoriales/testing-funcional-con-selenium-en-jenkins/)
Nota: Desde este proyecto se puede emplear Gradle Wrapper, sin necesidad de tener que instalar 'Gradle'

[Tutorial Selenium](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/tutorial-de-selenium-webdriver)
Nota: Este tutorial crea un proyecto Python. Para ello me he descargado pip e instalado selenium usando pip

1. Descarga de pip: python.exe get-pip.py (ubicado en proyectos_Python)
2. instalación de Selenium: pip install selenium
