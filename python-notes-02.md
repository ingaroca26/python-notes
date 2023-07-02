# Python Notes

<br>

~~~text
Windows Logo + I
Aplicaciones
Aplicaciones y características
Alias de ejecución de aplicaciones
Instalador de aplicación python.exe    Desactivado
Instalador de aplicación python3.exe   Desactivado
Instalador de aplicación python3.7.exe Desactivado
~~~

<br>

~~~text
https://www.python.org/downloads/windows/
python-3.11.1-amd64.exe
~~~

<br>

~~~sh
python --version
~~~

~~~text
Python 3.11.1
~~~

<br>

~~~sh
python --version --version
~~~

~~~text
Python 3.11.1 (tags/v3.11.1:a7a450f, Dec  6 2022, 19:58:39) [MSC v.1934 64 bit (AMD64)]
~~~

<br>

~~~sh
where python
~~~

~~~text
C:\Program Files\Python311\python.exe
~~~

<br>

~~~sh
pip --version
~~~

~~~text
pip 22.3.1 from C:\Program Files\Python311\Lib\site-packages\pip (python 3.11)
~~~

<br>

~~~sh
where pip
~~~

~~~text
C:\Program Files\Python311\Scripts\pip.exe
~~~

<br>

~~~sh
python -m pip --version
~~~

~~~text
pip 22.3.1 from C:\Program Files\Python311\Lib\site-packages\pip (python 3.11)
~~~

<br>

~~~sh
python -m pip list
~~~

~~~text
Package    Version
---------- -------
pip        22.3.1
setuptools 65.5.0

[notice] A new release of pip available: 22.3.1 -> 23.0.1
[notice] To update, run: python.exe -m pip install --upgrade pip
~~~

<br>

~~~text
Git Bash
Ejecutar como administrador
~~~

~~~sh
python -m pip --version
~~~

~~~sh
python -m pip list
~~~

~~~sh
python -m pip install --upgrade pip
~~~

~~~sh
python -m pip --version
~~~

~~~sh
python -m pip list
~~~

<br>

~~~sh
python -m venv venv
~~~

~~~sh
rm -r venv
~~~

<br>

~~~sh
python -m venv venv
~~~

~~~sh
source venv/Scripts/activate
~~~

~~~sh
deactivate
~~~

<br>

~~~sh
python -m venv venv
~~~

~~~sh
source venv/Scripts/activate
~~~

~~~sh
python -m pip --version
~~~

~~~sh
python -m pip list
~~~

~~~sh
python -m pip install --upgrade pip
~~~

~~~sh
python -m pip --version
~~~

~~~sh
python -m pip list
~~~

~~~sh
deactivate
~~~

<br>

~~~python
import platform

python_version: str = platform.python_version()
f_python_version: str = f'Python version: {python_version}'
print(f_python_version)

~~~

~~~text
Python version: 3.11.2
~~~

<br>

~~~python
import sys

python_version: str = sys.version
print(python_version)

~~~

~~~text
3.11.2 (main, May 30 2023, 17:45:26) [GCC 12.2.0]
~~~
