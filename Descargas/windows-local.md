## Descarga Local- Windows

  1.  Asegúrate de tener Python 3.6 o superior instalado en tu computadora. Puedes descargarlo desde el sitio web oficial de Python (https://www.python.org/downloads/)

  2.  Abre la línea de comandos de Windows (cmd) como administrador y ejecuta el siguiente comando para instalar pip:

<pre><code>python -m ensurepip --upgrade</code></pre>

  3.  Utiliza pip para instalar virtualenv:
  
<pre><code>pip install virtualenv</code></pre>

  4.  Crea una carpeta para alojar tu entorno virtual de Airflow. Por ejemplo, si quieres crear una carpeta llamada "airflow_env" en la unidad C, ejecutarías el siguiente comando:
  
<pre><code>virtualenv c:\airflow_env</code></pre>
 
  5.  Activa tu entorno virtual ejecutando el siguiente comando:

<pre><code>c:\airflow_env\Scripts\activate.bat</code></pre>

  6.  Utiliza pip para instalar Airflow:

<pre><code>pip install apache-airflow</code></pre>

  7.  Puede ser que también necesites instalar esta otra librería, en caso de que devuelva un error la consola:

<pre><code>pip install psutil</code></pre>

  8.  Inicializa la base de datos de Airflow:

<pre><code>airflow initdb</code></pre>

  9.  Inicia el servidor de Airflow:

<pre><code>airflow webserver -p 8080</code></pre>

  10. Abre tu navegador web y dirígete a la siguiente dirección:

<pre><code>http://localhost:8080</code></pre>



