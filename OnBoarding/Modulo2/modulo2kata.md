Crea un entorno virtual mediante venv

* Ejecutar en su terminal: python3 -m venv env o bien python -m venv env

python -m venv C:\Users\JMLS15\Desktop\LAUNCHX\EntornoVirtual env

INSERT IMAGE 1

* Ejecuta el comando para activar el entorno virtual: source env/bin/activate

C:\Users\JMLS15\Desktop\LAUNCHX\EntornoVirtual\Scripts\activate

INSERT IMAGE 2

Instalar una biblioteca

* Ejecuta el comando pip freeze para ver las bibliotecas instaladas en tu entorno:

pip freeze

* Ejecuta el comando pip install para instalar una biblioteca:

pip install python-dateutil

* Un gran mensaje de salida de texto dice que está instalando tu biblioteca, y debe terminar con la siguiente oración:

Successfully installed python-dateutil-2.8.2 six-1.16.0

* Vuelve a ejecutar pip freeze para ver cómo ha cambiado tu lista de bibliotecas:

pip freeze

* Ahora deberías ver la siguiente lista:

python-dateutil==2.8.2
six==1.16.0

INSERT IMAGE 3

Desactivar un entorno virtual

deactivate

INSERT IMAGE 4