# Análisis de redes con tcpdump

Información sobre tcpdump y usos varios.

Comencemos con las referencias que voy a seguir, he encontrado este [primer enlace](https://www.tcpdump.org/), aunque también me gustaría dar una breve explicación de lo que es tcpdump y en que nos puede ayudar.

> Tcpdump es una herramienta para línea de comandos **cuya utilidad principal es analizar el tráfico que circula por la red.**
>
> Permite al usuario capturar y mostrar en tiempo real los paquetes transmitidos y recibidos por la red a la cual el ordenador está conectado. Fue escrito por Van Jacobson, Craig Leres, y Steven McCanne mientras trabajaban en el Grupo de Investigación de Red del Laboratorio Lawrence Berkeley. Más tarde el programa fue ampliado por Andrew Tridgell.
>
> Tcpdump funciona en la mayoría de los sistemas operativos UNIX: Linux, Solaris, BSD, Mac OS X, HP-UX y AIX entre otros. En esos sistemas, **tcpdump hace uso de la biblioteca libpcap** para capturar los paquetes que circulan por la red.
> Existe una adaptación de tcpdump para los sistemas Microsoft Windows llamada WinDump y que hace uso de la biblioteca Winpcap.
>
> En UNIX y otros sistemas operativos **es necesario tener privilegios de administrador (root)** para utilizar tcpdump.
>
> El usuario puede aplicar varios filtros para que la salida sea más depurada. Un filtro es una expresión que va detrás de las opciones y que nos permite seleccionar los paquetes que estamos buscando. En ausencia de filtros tcpdump volcará todo el tráfico que vea el adaptador de red seleccionado.

Bueno, ya tenemos las primeras especificaciones y nos puede ir aclarando su uso y características. En resumen, podríamos pensar que estamos ante un software que captura toda la comunicación que se realiza en la red. Un ejemplo real podría ser como el control de pasajeros de un aeropuerto, todas las personas que van y vienen pasan por un control donde los registran, registran sus equipajes, y queda rastro del origen y destino, ese control podría ser perfectamente el tcpdump, captura todos los datos que circulan por la red y quedan registrados.

Voy a seccionar este documento en varias secciones y ejercicios prácticos que deseo realizar y que iré incluyendo y ofreciendo las conclusiones que yo extraigo.

Soy usuario de Linux, por lo tanto, todos los ejercicios estarán basados en sistema Linux.

[1 - Instalación](tcpdump-ex-001.md)