~~~txt
Python Notes



Administrar alias de ejecución de aplicaciones
Windows Logo + I
Aplicaciones
Aplicaciones y características
Alias de ejecución de aplicaciones
Instalador de aplicación python.exe    Desactivado
Instalador de aplicación python3.exe   Desactivado
Instalador de aplicación python3.7.exe Desactivado



Download Link
https://www.python.org/downloads/windows/
python-3.11.1-amd64.exe



python --version
Python 3.11.1



python --version --version
Python 3.11.1 (tags/v3.11.1:a7a450f, Dec  6 2022, 19:58:39) [MSC v.1934 64 bit (AMD64)]



where python
C:\Program Files\Python311\python.exe



pip --version
pip 22.3.1 from C:\Program Files\Python311\Lib\site-packages\pip (python 3.11)



where pip
C:\Program Files\Python311\Scripts\pip.exe



python -m pip --version
pip 22.3.1 from C:\Program Files\Python311\Lib\site-packages\pip (python 3.11)



python -m pip list
Package    Version
---------- -------
pip        22.3.1
setuptools 65.5.0

[notice] A new release of pip available: 22.3.1 -> 23.0.1
[notice] To update, run: python.exe -m pip install --upgrade pip



Git Bash
Ejecutar como administrador
python -m pip --version
python -m pip list
python -m pip install --upgrade pip
python -m pip --version
python -m pip list



python -m venv venv
rm -r venv



python -m venv venv
source venv/Scripts/activate
deactivate



python -m venv venv
source venv/Scripts/activate
python -m pip --version
python -m pip list
python -m pip install --upgrade pip
python -m pip --version
python -m pip list
deactivate



import platform

python_version: str = platform.python_version()
f_python_version: str = f'Python version: {python_version}'
print(f_python_version)

Python version: 3.11.2



import sys

python_version: str = sys.version
print(python_version)

3.11.2 (main, May 30 2023, 17:45:26) [GCC 12.2.0]
~~~
