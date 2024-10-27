# Frontend de mi TFG Gestor Económico de gastos

Este Trabajo Fin de Grado tiene como finalidad el desarrollo de una aplicación web 
que permite gestionar de manera eficiente los gastos económicos de usuarios individuales, 
familias y pequeñas empresas. La necesidad de herramientas accesibles y personalizables 
en la gestión financiera ha motivado este proyecto, cuyo dominio de aplicación se centra 
en proporcionar una solución intuitiva y accesible para registrar, categorizar y analizar 
gastos e ingresos. 

La aplicación se distingue por sus aportaciones en diseño, seguridad y 
funcionalidades clave, como la posibilidad de crear presupuestos y generar gráficas 
detalladas. Entre sus características principales, destaca una interfaz amigable que facilita 
la interacción del usuario, así como mecanismos de seguridad robustos para proteger la 
información financiera. Además, la herramienta ofrece opciones avanzadas para 
personalizar la categorización de los gastos e ingresos, permitiendo un análisis más 
detallado y adaptado a las necesidades específicas de cada usuario. 

Para el desarrollo de este TFG, se ha seleccionado una metodología incremental e 
iterativa. Este enfoque divide el proyecto en etapas, agregando funcionalidad de manera 
progresiva, y permite revisiones constantes y mejoras continuas a lo largo del proceso. Las 
tecnologías principales utilizadas incluyen React y Express.js (un framework JavaScript 
basado en Node.js) para el desarrollo del frontend y backend respectivamente, junto con 
MySQL para la gestión de la base de datos. 

# Guía de instalación 
Para la correcta instalación y ejecución de la aplicación desarrollada, es 
necesario seguir los siguientes pasos detallados: 
1. Estructura del Proyecto: Una vez descargado el proyecto, se observarán 
dos carpetas principales en su interior: una denominada frontend y otra 
backend. Estas carpetas contienen los componentes esenciales del 
proyecto para la interfaz de usuario y la lógica del servidor, 
respectivamente. En cada carpeta deberá instalar los módulos mediante 
el comando npm install.

2. Configuración del Backend: Desde un terminal, diríjase a la dirección 
donde se encuentra la carpeta backend. Una vez dentro, se debe ejecutar 
el siguiente comando para iniciar el servidor: nodemon app. Este 
comando asegurará que el servidor se mantenga activo y que cualquier 
cambio realizado en el código se refleje de inmediato sin necesidad de 
reiniciar manualmente el servidor.

3. Configuración del Frontend: En otro terminal, diríjase a la dirección 
donde se encuentra la carpeta frontend. Dentro de esta carpeta, ejecute 
el comando npm start. Este comando iniciará la aplicación de frontend, 
abriendo automáticamente una ventana en su navegador web que 
mostrará la aplicación en ejecución.

4. Configuración de la Base de Datos: Dentro de la carpeta backend del 
proyecto, encontrará un archivo de script SQL (ScriptTFGRocio.sql) que 
contiene todas las instrucciones necesarias para crear las tablas 
requeridas en la base de datos. Este script deberá ser ejecutado en 
MySQL Workbench, una herramienta que debe estar previamente 
instalada en su sistema. Para ello, abra MySQL Workbench, conecte a su 
instancia de base de datos y ejecute el script proporcionado. Esto creará 
las tablas necesarias para el correcto funcionamiento de la aplicación.

5. Acceso a la Aplicación: Una vez que el backend y el frontend estén en 
ejecución y la base de datos esté configurada, puede acceder a la 
aplicación abriendo un navegador web y dirigiéndose a la siguiente URL: 
http://localhost:3000/. Aquí encontrará la pantalla de inicio de sesión de 
la aplicación, desde la cual podrá acceder a todas las funcionalidades 
implementadas.
