## 4. Caso práctico


## a) Actualizar el sistema

Para actualizar el sistema, se puede usar el comando `yum update` o `dnf update`, que buscarán e instalarán las últimas versiones de los paquetes instalados en el sistema. Es recomendable ejecutar este comando periódicamente para mantener el sistema seguro y actualizado.

## b) Buscar paquetes

Para buscar paquetes disponibles en los repositorios habilitados, se puede usar el comando `yum search` o `dnf search`, seguido de una palabra clave o una expresión regular. Por ejemplo, para buscar paquetes relacionados con el editor de texto vim, se puede usar el comando `yum search vim` o `dnf search vim`, que mostrarán una lista de paquetes que coinciden con la búsqueda.

## c) Instalar alguno

Para instalar un paquete, se puede usar el comando `yum install` o `dnf install`, seguido del nombre o la ruta del paquete. Por ejemplo, para instalar el paquete `vim-enhanced`, que proporciona una versión mejorada del editor de texto vim, se puede usar el comando `yum install vim-enhanced` o `dnf install vim-enhanced`, que resolverán las dependencias e instalarán el paquete y sus componentes.

## d) Comprobar que se ha instalado

Para comprobar que se ha instalado un paquete, se puede usar el comando `yum info` o `dnf info`, seguido del nombre del paquete. Por ejemplo, para comprobar que se ha instalado el paquete `vim-enhanced`, se puede usar el comando `yum info vim-enhanced` o `dnf info vim-enhanced`, que mostrarán información detallada sobre el paquete, como su versión, su tamaño, su descripción y su estado.

## e) Desinstalar el paquete

Para desinstalar un paquete, se puede usar el comando `yum remove` o `dnf remove`, seguido del nombre del paquete. Por ejemplo, para desinstalar el paquete `vim-enhanced`, se puede usar el comando `yum remove vim-enhanced` o `dnf remove vim-enhanced`, que eliminarán el paquete y sus componentes, así como los paquetes que dependan de él y que no sean necesarios para el sistema.


[![Volver al README](img/seccion.png)](../paquetesrpm/README.md)
