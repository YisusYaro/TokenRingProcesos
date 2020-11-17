# TokenRingProcesos
Programa concurrente usando paso de mensajes que hace circular un token (mensaje cualquiera) de manera infinita en un anillo de procesos usando MPJ.

#Compilar (Windows variable global activada):

 javac -cp .;%MPJ_HOME%/lib/mpj.jar TokenRingProcesos.java
 
#Ejecutrar (Windows usando cywing):

 mpjrun.bat -np 2 TokenRingProcesos
