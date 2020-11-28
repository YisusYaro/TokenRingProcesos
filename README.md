# TokenRingProcesos
Programa concurrente usando paso de mensajes que hace circular un token (mensaje cualquiera) de manera infinita en un anillo de procesos usando MPJ.

### Requisitos:

 Instalación correcta de MPJ.

### Compilar (Windows variable global activada):
  ```bash
  javac -cp .;%MPJ_HOME%/lib/mpj.jar TokenRingProcesos.java
  ```
 
### Ejecutar (Windows usando cywing):
  ```bash
  mpjrun.bat -np n TokenRingProcesos
  ```
 

