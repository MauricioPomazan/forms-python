# Forms-Python
Formulario alta persona y visualizacion personas cargadas

Reliazamos el tutorial de djangogirls y con la base del tutotial. 
Se realizo un formulario para cargas de personas las cuales quedan almecenadas en una base de datos db.sqlite.
Se realizaron algunas limitaciones al formulario para que el usuario no pueda ingresar numeros en los casilleros de nombre y apellido.
Se colocaron alertas cuando el formulario haya sido completado con exito.

Una ves cargado el formulario la informacion se vera reflejada en la tabla ubicada debajo del formulario.

Las tecnologias que se utilizaron son:

Python,
Django, 
HTML,
CSS,
Bootstrap,
JavaScrip.

Requisitos para el funcionamiento de la app:

Tener instalado python (en este caso se utilizo la version 3.6.8) y django que sea compatible con la version.
Una ves realizada la instalacion de python (https://www.python.org/downloads/windows/)
Comprobamos que se alla instalado usando el cmd colocando el comando           "python --version"
Se recomienda utilizar Visual studio code como editor de codigo.



Configuramos un entorno virtual y luego instalamos django

 mkdir djangogirls

 cd djangogirls

python -m venv myvenv

Con eso creamos el entorno virtual




Instalacion Django:

Activamos entorno virtual:

myvenv\Scripts\activate



Antes de instlar Django, debemos asegurarnos que tenemos la última versión de pip, el software que utilizamos para instalar Django:

python -m pip install --upgrade pip



Primero crea un archivo requirements.txt dentro de tu directorio djangogirls, usando el editor de código que instalaste previamente,
Dentro del fichero djangogirls/requirements.txt deberías tener el siguiente texto:

Django~=3.2.10

Ahora, ejecuta pip install -r requirements.txt para instalar Django.

Una vez que la instalacion se alla realizado con exito.

 Dentro de la carpeta forms_python2, abre la carpeta djangogirls2 en visual studio code, ve a la terminal del editor y coloca los comandos:
 
 myvenv\Scripts\activate (este es en el caso de que el entorno virtaul no este activado)
 
 Ejemplo:
 
 C:\Users\Name\djangogirls> myvenv\Scripts\activate
 
 (myvenv) C:\Users\Name\djangogirls>
 
 Si el entorno virtual esta activado procede a levantar el servidor con el comando:
 
 python manage.py runserver
 



