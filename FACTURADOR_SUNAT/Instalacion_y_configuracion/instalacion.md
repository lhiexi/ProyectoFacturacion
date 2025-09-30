**INSTALACIÓN DE FACTURADOR SUNAT**
1. Se desinstalaron las versiones previas de JAVA para evitar conflictos.

2. Se descargó el jdk de Java versión 8 en la página de Oracle, cuyo link es: [https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html].

3. Luego de instalar el Java, se ubican los archivos en “C:\Program Files\Java”, donde deben estar las dos carpetas: jdk y jre.
 
4. Se copia la ubicación del jdk  "C:\Program Files\Java\jdk1.8.0_202".

5. En la biblioteca de archivos, se da click derecho en Este equipo y se presiona la opción Propiedades.
 
6. De la ventana de Configuración que se abre se dirige a Configuración avanzada del sistema.
 
7. Se presiona la opción Variables de entorno.
 
5. Posteriormente, se modifica la variable JAVA_HOME pegando la ubicación del jdk.
 
6. Se modifica el path en variables del sistema agregando %JAVA_HOME%/bin, y una vez hecho, se presiona en aceptar.
 
7. En esta página [https://cpe.sunat.gob.pe/sites/default/files/inline-files/Instaladores%20del%20Sistema%20Facturador%20SUNAT_V-2.1%20%281%29.pdf] se descargó el Facturador SUNAT, y luego de descomprimido, se movió al disco F "F:\PRACTICAS\SFS_v-2.1".
 
8. Luego, se presionó doble click en "EjecutarSFS.bat" y se abre un cmd, lo que indica que se está ejecutando correctamente sin problemas.
 
9. Dejando el cmd abierto, desde la ubicación donde está el programa se presiona doble click en "abrirBandeja.bat".

10. Se abre una página en el explorador desde el localhost [http://localhost:9000/#], la cual es la página del Facturador SUNAT.
  
