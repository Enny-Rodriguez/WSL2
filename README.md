# WSL2
## ARQUITECTURA

###  cómo funciona la versión 2 del subsistema que permite ejecutar aplicaciones de Linux en Windows y como tiene acceso al sistema de archivos de Windows.

WSL 2 es una nueva versión de la arquitectura del Subsistema de Windows para Linux que permite que el Subsistema de Windows para Linux ejecute archivos binarios de ELF64 de Linux en Windows. Sus principales objetivos son aumentar el rendimiento del sistema de archivos y agregar compatibilidad completa con las llamadas del sistema.

Esta nueva arquitectura cambia el modo en que estos archivos binarios de Linux interactúan con Windows y con el hardware del equipo, pero proporciona la misma experiencia de usuario que en WSL 1 (la versión disponible de forma general actualmente).

Las distribuciones de Linux individuales se pueden ejecutar con la arquitectura de WSL 1 o WSL 2. Cada distribución se puede actualizar o degradar en cualquier momento, y puedes ejecutar distribuciones de WSL 1 y WSL 2 en paralelo. WSL 2 usa una arquitectura completamente nueva que aprovecha las ventajas de un kernel de Linux real.

![](imagen.png)

## VENTAJAS

### ventajas WSL frente a otros sistemas de virtualización como las maquinas virtuales. 

WSL necesita menos recursos (CPU, memoria y almacenamiento) que una máquina virtual completa. Asimismo, WSL también te permite ejecutar aplicaciones y herramientas de línea de comandos de Linux junto con la línea de comandos de Windows, aplicaciones de escritorio y de Store, así como la posibilidad de acceder a los archivos de Windows desde Linux. Esto te permite usar las aplicaciones de Windows y las herramientas de línea de comandos de Linux en el mismo conjunto de archivos, si así lo deseas.

## INSTALACION

### servicios de Windows que deben habilitarse para la correcta ejecución de WSL2.

Para la correcta ejecucion del servicios de Windows que deben habilitarse para la correcta ejecución de WSL2.


![](/ima/1.PNG)

Se procede hacer la intalacion de WSL2, dando continuacion a cada uno de los pasos a seguir.


![](/ima/3.PNG.jpg)

Acpetamos el permiso que  windows instale esta aplicasion dandole YES.

![](/ima/4.PNG.jpg)

A continuacion comienza la instalacion del programa, tardara unos minutos.

![](/ima/5.PNG.jpg)

Cuando termino la intalacion wsl2, damos final.

![](/ima/6.PNG.jpg)

Entramos a windows powershell y lo ejecutamos como administrador

![](/ima/7.PNG.jpg)

Ejecutamos el codigo (wls --set-default-version 2

![](/ima/8.png.jpg)

![](/ima/9.png.jpg)

![](/ima/10.png.jpg)

![](/ima/11.png.jpg)

![](/ima/12.png.jpg)

![](/ima/13.png.jpg)


holaaa