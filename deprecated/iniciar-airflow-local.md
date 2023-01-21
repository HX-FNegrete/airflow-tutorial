## Iniciar airflow local

  1.  Después de instalar Airflow, es recomendable inicializar la base de datos
  para que Airflow pueda almacenar información sobre tus flujos de trabajo, 
  programaciones, y ejecuciones. Inicializa la base de datos de Airflow:

<pre><code>airflow db init</code></pre>

  2. Ten en cuenta que si ya has inicializado la base de datos anteriormente, 
  intentar inicializarla nuevamente generará un error, en ese caso si deseas 
  resetear la base de datos debes utilizar el comando:

<pre><code>airflow db reset</code></pre>

Una vez que la base de datos esté inicializada, puedes comenzar a crear y programar 
tus flujos de trabajo, y utilizar la interfaz web de Airflow para monitorear el progreso de tus ejecuciones.  
  
  
  3.  Inicia el servidor de Airflow:

<pre><code>airflow webserver -p 8080</code></pre>

  4. Abre tu navegador web y dirígete a la siguiente dirección:

<pre><code>http://localhost:8080</code></pre> 
  
