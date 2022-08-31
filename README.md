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

![](/ima/1.PNG1)
![](/ima/2.png)
![](/ima/3.png)
![](/ima/4.png)
![](/ima/5.png)
![](/ima/6.png)
![](/ima/7.1.png)
![](/ima/8.png)
![](/ima/9.png)
![](/ima/10.png)
![](/ima/11.png)
![](/ima/12.png)
![](/ima/13.png)


holaaa