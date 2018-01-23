# Curso de Introduccion a Python 3

Este es un curso de introduccion a la programacion usando Python 3 en el marco del procesamiento de una imagen del disco de escombros alrededor de Fomalhaut para encontrar el exoplaneta Fomalhaut b. Este curso esta diseñado para estudiantes de ultimos años de colegio, o estudiantes universitarios/profesionales sin experiencia en programacion.

El material de este notebook fue recopilado para Clubes de Ciencia Colombia 2017 por Luis Henry Quiroga (GitHub: [lhquirogan](https://github.com/lhquirogan/)) y Germán Chaparro (GitHub: [saint-germain](https://github.com/saint-germain/)).

## Contenidos

1. [Introduccion a Python](1_Introduccion)

2. [Python Intermedio](2_Intermedio)

3. [Python Avanzado](3_Avanzado)

4. [Proyectos](Proyectos)

Para un primer curso intensivo de 4-5 días es suficiente con las secciones 1-2. La seccion "Python Avanzado" contiene tutoriales de Numpy y Matplotlib (que son avanzados para alguien que apenas esta empezando a programar).

Hay varias maneras de explorar este curso:

### Usando mybinder.org sobre este repositorio 

Haciendo clic en el siguiente boton se pueden correr todos los notebooks del curso directamente a traves de mybinder.org, que genera una maquina virtual en la nube en donde se puede interactuar con los notebooks (excepto el 1.4 y 1.5, que tienen una version modificada hecha para correr en Binder, [1.4a](1_Introduccion/04a.%20Tortugas-en-Binder.ipynb) y [1.5a](1_Introduccion/05a.%20Range%20-%20iteradores-en-Binder.ipynb)). Este enlace funciona sobre el repositorio original del curso en https://github.com/saint-germain/Python3Espanol.

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/saint-germain/Python3Espanol/master)

### Corriendo localmente este repositorio (recomendado)

 - Descarga este repositorio en este [enlace](https://github.com/saint-germain/Python3Espanol/archive/master.zip). 
 - Instala [Anaconda](https://www.anaconda.com/download/) completo o [Miniconda](https://conda.io/miniconda.html) con minimo las librerias `jupyter numpy matplotlib astropy` (ver abajo para Windows).
 - Corre localmente los notebooks en este directorio.

#### Para instalar Anaconda en Windows:

1. Verificar si tu sistema es 32 o 64 bits: http://es.ccm.net/faq/9548-como-saber-si-mi-windows-es-de-32-o-64-bits

2. Descargar y ejecutar la el instalador para Windows correspondiente a 32 o 64 bits según lo que diga la verificación anterior. Es importante que la versión de Python que necesitamos es la 3.6 https://www.continuum.io/downloads#windows

3. Abrir Jupyter Notebook en la carpeta correspondiente del menú Inicio y buscar la ubicación del repositorio (descomprimido) desde el navegador

4. Desde el navegador, abrir el Notebook (.ipynb) que se quiera estudiar.
