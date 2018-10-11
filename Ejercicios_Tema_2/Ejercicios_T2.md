# EJERCICIOS TEMA 2

## EJERCICIO 1
### Descargar y ejecutar las pruebas del alguno de los proyectos anteriores, y si sale todo bien, hacer un pull request a alguno de esos proyectos con test adicionales, si es que faltan (en el momento que se lea este tema).

![ejercicio1](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejercicio1.png?raw=true)

## EJERCICIO 2
### Para la aplicacion que se está haciendo, escribir una serie de aserciones y probar que efectivamente no fallan. Añadir test para una funcionalidad, probar que falla y escribir el código para que no lo haga (vamos, lo que viene siendo un TDD).

En mi clase Partidos,la cual creará un objeto partido, el cual está compuesto por los siguientes atributos: id_partido, jornada, equipo_local, equipo_visitante, fecha, hora, lugar, canalTV. 

Se han creado funciones para comprobar que dicho objeto partido este compuesto por dichos atributos mencionados anteriormente. En el caso de que alguno de esos atributos no este expresado o no este expresado de forma correcta (que sea un string, un tipo fecha...), al pasar el test, en el cual están los `assert`, el test fallará. 

Funciones de la Clase.

![ejercicio2.1](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejericio2.1.png?raw=true)

Funciones del Test.

![ejercicio2.2](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejercicio2.2.png?raw=true)

Test pasado.

![ejercicio2.3](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejercicio2.3.png?raw=true)

Test no pasado por falta de un atributo en el objeto partido.

![ejercicio2.4](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejercicio2.4.png?raw=true)

## EJERCICIO 3
### Crear algún conjunto de scripts de test, usando tu lenguaje favorito, y ejecutarlos desde el marco de test más adecuado (o el que más te guste) para ese lenguaje.

Como se puede comprobar en las capturas del ejercicio 2, se observa que ya se ha creado el conjunto de script de test para comprobar que todos los campos del objeto partido sean correctos. Tambien se ha hecho una ejecución en la que se muestra cuando pasa el test y cuando no. El marco que se usa para ello es `pytest`. 

## EJERCICIO 4
### Instalar alguno de los entornos virtuales de node.js (o de cualquier otro lenguaje con el que se esté familiarizado) y, con ellos, instalar la última versión existente, la versión minor mas actual de la 4.x y lo mismo para la 0.11 o alguna impar (de desarrollo).

En mi caso, ya que estoy trabajando con `Python` en mi proyecto, el entorno vitual elegindo es `Virtualenv`.

Su instalación se ha realizado con el siguiente comando:

`sudo pip install virtualenv` 

Cuya versión es la que aparece en la captura siguiente:

![ejercicio4](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejercicio4.png?raw=true)

Dicha versión soporta lo que se describe en el siguiente enlace: 
[Versiones virtualenv](https://virtualenv.pypa.io/en/latest/changes/#id1)


## EJERCICIO 5
### Como ejercicio, algo ligeramente diferente: una web para calificar las empresas en las que hace prácticas los alumnos.
### Las acciones serían:
### - Crear empresa.
### - Listar calificaciones para cada empresa.
### - Crear calificacion y añadirla (comprando que la persona no lo haya añadido).
### - Borrar calificación (si se arrepiente o te denunca la empresa o algo).
### - Crear un repositorio en Github para la librería y crear un pequeño programa que use algunas de sus funcionalidades.
### Si se quiere hacer con cualquier otra aplicación, también es válido. 


## EJERCICIO 6
### Ejecutar el programa en diferentes versiones del lenguaje. ¿Funciona en todas ellas?

## EJERCICIO 7
### Crear una descripción del módulo usando package.json. En caso de que se trate de otro lenguaje, usar el método correspondiente.

En mi caso, al estar utilizando el lenguaje `Python`, existe un forma para descargar e instalar los paquetes necesarios para el proyecto. Crear un archivo de texto denominado `requirements.txt` en el cual se anotan los paquetes para que `pip` se encargue de instalarlos de forma automatica. En la siguiente captura se muestra el archivo `requirements.txt` el cual estoy usando para mi proyecto. 

![requirements](https://github.com/JaviMancilla/Ejercicios_IV_18-19/blob/master/Ejercicios_Tema_2/Imagenes_T2/ejercicio7.png?raw=true)

## EJERCICIO 8
### Automatizar con `grunt`, `gulp` u otra herramienta de gestión de tareas en Node la generación de documentación de la librería que se cree usando `docco` u otro sistema similar de generación de documentación. Previamente, por supuesto, habrá que documentar tal librería.

## EJERCICIO 9
### Haced los dos primeros pasos antes de pasar al tercero.

