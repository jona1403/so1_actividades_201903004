Universidad de San Carlos de Guatemala

Facultad de Ingeniería

Escuela de Ciencias y Sistemas

Sistemas Operativos 1

Sección A

Nombre: Jonathan Alexander Alvarado Fernándedz

Carné: 201903004

Tipos de kernel y sus diferencias:

Kernel Monolitico: Un kernel monolítico es un tipo de kernel que tiene todas las funcionalidades necesarias para que el sistema operativo funcione correctamente, incluyendo el control de dispositivos, la gestión de la memoria, la gestión de procesos y el manejo de archivos. Este tipo de kernel es conocido por ser extenso y complejo, y suele ser utilizado en sistemas operativos de escritorio.

Kernel Modular: Un kernel modular es un tipo de kernel que se subdivide en módulos independientes, cada uno de los cuales está encargado de realizar una tarea específica. Esto permite mayor flexibilidad y facilidad para actualizar o cambiar algunas funciones del sistema. Este tipo de kernel se utiliza a menudo en sistemas operativos en tiempo real o en servidores.

Micro Kernel: Un microkernel es un tipo de kernel que solo incluye las funciones esenciales necesarias para el funcionamiento del sistema operativo, como el manejo de la memoria y el control de procesos. El resto de las funciones se implementan en aplicaciones fuera del kernel, lo que proporciona una mayor seguridad y estabilidad del sistema. Este tipo de kernel se utiliza comúnmente en sistemas operativos distribuidos y en sistemas embebidos.

Kernel Hibrido: Un kernel híbrido es una mezcla de varios tipos de kernel, puede incluir características de un kernel monolítico, como un gran conjunto de funciones incorporadas, y características de un kernel modular, como la capacidad de cargar y descargar módulos de manera dinámica. El objetivo de un kernel híbrido es combinar las ventajas de los diferentes tipos de kernel para lograr un equilibrio entre complejidad, rendimiento y flexibilidad.

User vs kernel mode:

dentro de un sistema operativo existen dos modos de operación, los cuales son el modo de usuario y el modo kernel.

El modo de usuario es una forma en la que el sistema operativo brinda un conjunto limitado de funciones y privilegios al proceso en ejecución. En este modo, los procesos no tienen acceso directo a la memoria del sistema ni a los recursos del hardware, lo que ayuda a proteger el sistema de errores o fallos en el código del proceso.

En el modo de kernel, el sistema operativo proporciona acceso completo a todos los recursos del sistema, incluyendo la memoria y los dispositivos de hardware. En este modo, los procesos tienen acceso a todas las funciones y privilegios del sistema operativo, y pueden realizar tareas críticas como la gestión de memoria, el control de procesos y el manejo de dispositivos.