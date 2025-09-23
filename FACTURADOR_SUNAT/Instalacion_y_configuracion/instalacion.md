**INSTALACIÓN DE FACTURADOR SUNAT**
1. Se desinstaló las versiones que tenía de JAVA para evitar conflictos.
2. Descargué el jdk de java verion 8 en la página de Oracle, este es el [link](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)
3. Luego de instalado eljava se ubica los archivos en C:\Program Files\Java dos carpetas el jdk y el jre.
4. Se copia la ubicación del jre "C:\Program Files\Java\jre1.8.0_202"
5. Luego me dirijo hacia variables de entorno del sistema y modifico el JAVA_HOME y pego la ubicación del jre.
6. Modifico el path en variables del sistema agregando %JAVA_HOME%/bin y una vez hecho le dí en aceptar.
7. En esta [página](https://cpe.sunat.gob.pe/sites/default/files/inline-files/Instaladores%20del%20Sistema%20Facturador%20SUNAT_V-2.1%20%281%29.pdf) descargué el facturador SUNAT y luego de descomprimido lo moví al disco F de mi máquina "F:\PRACTICAS\SFS_v-2.1".
8. Luego presioné doble click en "EjecutarSFS.bat" y se abre un cmd eso quiere decir que se está ejecutando bien sin problemas.
9. Dejando el cmd abierto, desde la ubicación donde está el programa se presiona doble click en "abrirBandeja.bat".
10. Se abre una pagina en el explorador desde el localhost http://localhost:9000/# ese vendría siendo a pagina del facturador SUNAT.