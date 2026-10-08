Ejercicios del TP5:

1) Hacer un programa en lenguaje C que permita manejar a través de 2 hilos distintos la impresión de dos frases:
a) “Primero aprendo lenguaje C” (hilo 1)
b) “Segundo tratare de aprender Semáforos” (Hilo 2)
Como en la realidad no sabemos qué hilo se va a ejecutar primero, debemos sincronizar a través de un semáforo que primero se ejecute el punto a y luego el b
Nota: Identificar cual es la sección crítica.
2) Hacer un programa en lenguaje C que permita manejar a través de 2 hilos distintos una variable llamada “contador“ inicializada en 0 compartida por ambos hilos, en uno de esos hilo de ejecución esa variable se incrementa, y por el otro hilo se decrementa, si hacemos por ejemplo 10000 iteraciones en los dos hilos sobre esa misma variable contador, y ejecutamos nuestro programa varias veces podremos observar que rara vez esa variable queda en 0 como quisiéramos que ocurra. Para que esto suceda debemos sincronizar a través de un semáforo la ejecución de estos hilos para que dicha variable siempre quede en 0.
Nota: Identificar cual es la sección crítica.
3) Escriba una rutina en lenguaje C, donde se crean dos hilos, estos serán lanzados en paralelo. Implemente un semáforo para ambos procesos, donde se garantice la exclusión mutua entre ambos procesos.
Nota: Identificar cual es la sección crítica.
4) Hacer un scripts que informe:
a) Total de memoria del sistema
b) Total de memoria usada
c) Total de memoria libre
d) Dejar el informe en un archivo llamado “Informe de RAM”
Usar comando free para resolverlo
5) Hacer un scripts que informe:
a) Los procesos esperando por CPU
b) El número de procesos en estado dormido
c) Si dichos proceso están usando memoria swap
d) La cantidad de memoria intercambiada desde el disco
e) La cantidad de memoria intercambiada hacia el disco.
6) Hacer un scripts que permita indicarle por parámetro si quiero habilitar o deshabilitar la memoria swap
7) Hacer un scripts que permita tomar la decisión de cambiar los niveles de intercambio entre la memoria swap y la RAM, en este caso el scripts me debe solicitar al ejecutarlo:
- 0% de nivel de intercambio.
- 50% de nivel de intercambio.
- 100% de nivel de intercambio.
Tener en cuenta que si el sistema operativo se reinicia debe volver a los valores por defecto.
8) Hacer un scripts que permita chequear cada 5 segundos el estado de la memoria libre, en caso que la misma llegue a un determinado valor ingresado como parámetro al ejecutar el scripts, dispare una alerta en el servidor (En este caso un mensaje por pantalla).
9) Escribir un scripts que deje en un archivo de nombre “mem-actual” el estado de la memoria actual, y en un archivo de nombre “mem-limpia” el estado luego de ejecutar el comando de liberación de memoria. El scripts me debe solicitar al ejecutarlo que tipo de nivel de liberación quiero hacer al ejecutar el comando que corresponde a tal fin. A continuación se especifican los valores a pasarle al comando de liberación de memoria:
0: No liberará absolutamente nada de nuestra memoria cache.
1: Forzamos a nuestro kernel a liberar la pagecache.
2: Forzando a nuestro kernel a liberar los inodos y dentries.
3: Forzando a nuestro kernel a liberar la pagecache, los inodos y las dentries.
10) Programe un scripts que identifique si en servidores Linux se encuentra instalado el comando “dmidecode”, en caso de estar instalado me determine la cantidad máxima de memoria física que puedo instalar en ese servidor, y el tamaño máximo del módulo de memoria que puedo que acepta dicho servidor. En caso de no estar instalado correr el comando necesario para hacerlo y determinar lo solicitado anteriormente.
