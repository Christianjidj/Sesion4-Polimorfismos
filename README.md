# Sesion4-Polimorfismos
5/26/5


¿Cuál es la diferencia entre polimorfismo en tiempo de compilación y en tiempo de ejecución?
La desicions se temoa antes de ejecutar el programa en el paso de compilación, pero en el polimorfismo de ejecucion la desicion no es tomada hasta ya en el .exe.

¿Para qué sirve la palabra virtual?
Para decir a C++ que falta por definir la clase del objeto creado con herencia. Se decidira que versión del metodo se usara al conocer la clase del objeto.

¿Qué ventaja tiene usar override?
Te permite sobreescribir lo que se encuentre previamente en un metodo. 

¿Por qué una clase con un método = 0 se considera abstracta?
Porque es como dejar el metodo vacio, sin nada mas que el tipo de retorno. Es como un boceto.

¿Por qué se recomienda usar destructor virtual en clases base?
Porque de esta manera puedes destruir cualquier objeto que tenga herencia de tu clase con el destructor virtual de manera simple. Delete puntero de obj, y eliminas por completo el objeto, no nomas la parte de la clase madre.

¿Qué significa que un puntero de clase base apunte a un objeto derivado?
Significa que un objeto derivado es de clase base + algo, si tienes una clase de animal y una clase hija perro, perro sigue siendo un animal, pero con detalles extras mas especificos.

<img width="1547" height="875" alt="image" src="https://github.com/user-attachments/assets/2091ca00-9580-42b3-a0db-4b6c99ca73c7" />



