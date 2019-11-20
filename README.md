Analisis y Visualizacion de Datos - Mentorias Diplomatura en Ciencia de Datos 2019
==================================================================================

Pagina
------

http://diplodatos.famaf.unc.edu.ar/


Repositorio
-----------

https://github.com/diplodatos2019mentoria/Analisis_Visualizacion_Datos

-------------------------------------------------------------------------------

Instalación
-----------

1. Se necesita el siguiente software:

    - Git
    - Pip
    - Python 3.6 o posterior
    - Miniconda

    En un sistema basado en Debian (como Ubuntu), se puede hacer:

        $ sudo apt-get install git python-pip python3

    Para instalar Miniconda seguir las [intrucciones de su pagina oficial](https://docs.conda.io/en/latest/miniconda.html#installing).

2. Bajar el código:

        $ git clone https://github.com/diplodatos2019mentoria/Analisis_Visualizacion_Datos.git


Entorno Virtual
---------------

1. Para crear y activar nuestro virtualenv:

        $ conda create --name dd19-ayv python=3.6
        $ conda activate dd19-ayv

1. Instalar dependencias:

        $ cd Analisis_Visualizacion_Datos
        $ pip install -r requirements.txt
