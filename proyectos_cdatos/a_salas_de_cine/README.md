<h2><b>Análisis exploratorio de cines en Argentina</b></h2>
<p>Este repositorio contiene un cuaderno de Jupyter que realiza un análisis exploratorio de datos sobre las salas de cine en Argentina. El objetivo principal de este proyecto es obtener información sobre la distribución, características y relaciones en la industria cinematográfica del país, además de demostrar las habilidades del autor en el análisis de datos.</p>
<br>
<h3><b>Tabla de contenidos</b></h3>
<ol>
 <li><u>Introducción</u></li>
 <li><u>Fuentes de datos</u></li>
 <li><u>Descripción general del cuaderno</u></li>
 <li><u>Dependencias</u></li>
 <li><u>Uso</u></li>
 <li><u>Licencia</u></li>
</ol>
<br>
<h3><b>Introducción</b></h3>
<p>En este proyecto se realiza el análisis a un <a href='https://datos.gob.ar/dataset/cultura-mapa-cultural-espacios-culturales/archivo/cultura_f7a8edb8-9208-41b0-8f19-d72811dcea97'>dataset de cines</a> en Argentina, que incluye datos como nombres, direcciones, localidades, provincias, número de pantallas y capacidad de asientos. El objetivo es explorar varios aspectos, como la distribución geográfica de los cines, la concentración de cines en diferentes provincias, la correlación entre el número de pantallas y la capacidad de asientos, y la identificación de las ciudades con la mayor cantidad de asientos de cine.</p>
<br>
<h3><b>Fuentes de datos</b></h3>
<p>El conjunto de datos utilizado en este análisis se obtuvo de la sección "<a href='https://datos.gob.ar/dataset/cultura-mapa-cultural-espacios-culturales'>Mapa de la Cultura: Espacios Culturales</a>" del sitio web "<a href='https://datos.cultura.gob.ar/'>Datos abiertos de cultura</a>". Estos datos son mantenidos por el <a href='https://www.sinca.gob.ar/'>Sistema de Información Cultural de la Argentina (SInCA)</a> bajo el Ministerio de Cultura de la Nación. El dataset representa espacios culturales georreferenciados en donde se llevan a cabo actividades culturales regulares, incluyendo las salas de cine. Estos datos proporcionan información muy útil para comprender la industria cinematográfica y otros espacios culturales en Argentina.</p>
<br>
<h3><b>Descripción general del cuaderno</b></h3>
<p>El cuaderno se divide en varios capítulos, cada uno de los cuales se centra en un aspecto específico del análisis. La siguiente es una descripción general de los capítulos cubiertos:</p>
<ol>
<li>Preprocesamiento: este capítulo se enfoca en la importación y preprocesamiento del conjunto de datos de cines, para asegurar la calidad de los datos y preparar su análisis.</li>
<li>Exploración fundamental de los datos: este capítulo explora información clave, como las localidades con la mayor cantidad de cines y las provincias con el promedio más alto de pantallas por cine, y también crea visualizaciones para mostrar la distribución de los cines en todo el país.</li>
<li>Exploración avanzada de datos: este capítulo profundiza en los datos mediante el análisis de la correlación entre el número de pantallas y la capacidad de asientos, la identificación de ciudades con alta concentración de cines y la exploración de la relación entre el número de cines y las visualizaciones en una provincia.</li>
<li>Aprendizaje automático: este capítulo aborda la aplicación de técnicas de aprendizaje automático, incluyendo la predicción del número de pantallas y la agrupación de cines en función de sus ubicaciones.</li>
<li>Visualizaciones: este capítulo presenta varias visualizaciones, como histogramas, diagramas de dispersión, gráficos de barras, diagramas de caja y mapas de calor, para mejorar la comprensión de los datos.</li>
</ol>
<br>
<h3><b>Dependencias</b></h3>
El cuaderno de Jupyter requiere las siguientes dependencias:
<ul>
<li> Python 3.9.x</li>
<li> Jupyter Notebook</li>
<li> Pandas</li>
<li> NumPy</li>
<li> Matplotlib</li>
<li> Seaborn</li>
<li> Scikit-learn</li>
</ul>
<p>Para instalar las dependencias, se recomienda utilizar el gestor de paquetes [pip](https://pip.pypa.io/). Se instalar las dependencias ejecutando los siguientes comando:</p>

    pip install pandas

    pip install numpy
    
    pip install matplotlib
    
    pip install seaborn
    
    pip install scikit-learn


<em> Asegurarse de tener Python 3.9.x y Jupyter Notebook instalados antes de ejecutar los comandos.</em>
<br>
<br>
<h3><b>Uso</b></h3>
<p>Para utilizar el cuaderno de Jupyter, se debe seguir estos pasos:</p>
<li> Copiar o descargar el repositorio en la computadora local.</li>
<li>Asegúrarse de tener todas las dependencias instaladas (ver la sección de dependencias).</li>
<li>Abrir Jupyter Notebook en tu entorno de desarrollo preferido.</li>
<li>Navegar hasta la ubicación del archivo `analisis_exploratorio_cines_arg.ipynb` y abrirlo.</li>
<li>Ejecutar las celdas del cuaderno (<em>combinación de teclas alt + enter</em>) en secuencia para obtener los resultados y las visualizaciones.</li>
<br>
<h3><b>Licencia</b></h3>
<p>Este proyecto está bajo la licencia <a href='https://creativecommons.org/licenses/by-nc/4.0/'>Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)</a>. Esto significa que se puede compartir y adaptar libremente el contenido de este proyecto para fines no comerciales, siempre y cuando se de el crédito apropiado al autor y se proporcione un enlace a la licencia.</p>
