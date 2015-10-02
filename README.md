# Segundo-Parcial

Variables Estáticas

Las variables estáticas o de clase son propias únicamente de la clase y no de los objetos que puedan crearse de la misma, por lo tanto sus valores son compartidos por todos los objetos de la clase y precedidas de un static. Para invocar una variable estática no se necesita crear un objeto de la clase en la que se define, basta con escribir su nombre si se llama desde la clase que está definido o si se invoca desde una clase distinta debe anteponerse su nombre, el de la clase en la clase en la que se encuentra seguido de un punto (.). 


Ciclos de vida de las variables:

•	Variables Estáticas: se crean cuando la clase se usa por primera vez, se inicializan por defecto y suelen existir para el resto del programa; siempre y cuando que no se encuentre cargado.
•	Variables de Instancia: se crean cuando se crea el objeto que las contiene y se destruyen cuando el recolector de basura no encuentra referencias activas para el objeto. 
•	Variables Locales: se crean en la sentencia en la que están definidas, no se inicializan por defecto, contienen datos imprevisibles y se destruyen al salir del bloque; en la última llave.


Memoria Dinámica:

Se refiere a la memoria que no puede ser definida puesto que no se conoce o no se tiene idea del número de la variable a considerarse. De igual forma dicha memoria permite solicitar memoria en tiempo de ejecución, por lo que cuanta mas memoria se necesite más se le solicita al sistema operativo. El distema operativo maneja la memoria gracias al uso de punteros, por ende el proceso nos impide conocer el tamaño de la memoria necesaria en el momento de compilar.
Cuando es creado un programa en el que se necesita utilizar memoria dinámica el sistema operativo divide el programa en cuatro partes: texto, datos, pila y heap. En la última parte es donde queda la memoria libre para poder utilizarla de forma dinámica. 


Clase:

Es una plantilla para la creación de objetos de datos según un modelo predefinido. Las clases son utilizadas para representar entidades o conceptos. Cada clase es un modelo que define un conjunto de variables y métodos apropiados para operar con dichos datos. Cada objeto creado a partir de la clase se denomina instancia de la clase. 

Objeto:

Es una entidad que consta de un estado y un comportamiento, que a su vez consta respectivamente de datos almacenados y de tareas realizables durante el tiempo de ejecución. Puede ser creado instanciando una clase o mediante escritura directa de código. 


Instanciación: 

Una instancia se refiere a una realización específica de una clase o prototipo determinado. Un programa se instancia cuando se ejecuta un programa en un computador; en lenguajes que crean objetos a partir de clases dicho objeto es una instancia de una clase.


Herencia:

Es le mecanismo mas utilizado para alcanzar algunos de los objetivos mas preciados en el desarrollo de software como son la reutilización y la extensibilidad. A partir de ella se pueden crear nuevas clases partiendo de una clase o de una jerarquía de clases preexistentes evitando así el rediseño, la modificación y verificación de la parte ya implementada,


Sobrecarga: 

Es la capacidad de un lenguaje de programación que permite nombrar con el mismo identificador diferentes variables u operaciones. De igual forma se refiere a la posibilidad de tener dos o mas funciones con el mismo nombre pero funcionalidad diferente. 


Ensombrecimiento: 

Se produce cuando un ámbito de validez se define una variable con nombre idéntico a otra válida en un ámbito superior. 

