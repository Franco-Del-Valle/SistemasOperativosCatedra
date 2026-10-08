Ejercicios del TP3 (Scripts):

1- Guardar las variables de entorno HOSTNAME, HOME, LOGNAME Y PATH en un archivo de nombre var-set ordenado por nombre de variable.
2- Implementar un script que cambie los permisos de todos los ejercicios (scripts) de la practica 2 que se encuentran en …/practicas/tp2/ para que puedan ser ejecutados por otros y modificados por el grupo, el resto de los permisos quedan igual.
3- Recorrer el directorio …/practicas/tp1/ y encontrar los archivos ordinarios que tengan permiso igual a 644. De dichos archivos guardar solo los nombres en un archivo de nombre “perm644”.
4- Usando el comando find, generar un scrip que al pasarle un directorio cualquiera pasado como parámetro:
a) Guarde en el archivo name los nombres de archivos que comienzan con la letra a.
b) Guarde en el archivo extend los nombres de archivos que tienen extensión .txt
c) Guarde en el archivo perm los nombre de archivos que tienen permisos iguales a 644
d) Guarde en el archivo tam los nombres de archivos que tienen tamaño mayor a 1K
5- Usando una estructura repetitiva recorrer un directorio cualquiera pasado por parámetro y determinar que archivos fueron modificados (Comnado stat) en un mes determinado. Dicho mes también pasarlo por parámetro.
6- Hacer un informe de un directorio cualquiera pasado por parámetro que indique:
a) Que archivos han sido modificados en los últimos 30 minutos
b) Que archivos han sido accedidos en los últimos 60 minutos.
c) Que archivos han sido modificados en los últimos 5 dias
d) Que archivos han sido modificados hace más de 10 dias
7- Hacer un script que al ejecutarse pida al usuario 2 números y después presente la suma, resta, producto y división de los mismos
8- Compruebe si un directorio cualquiera pasado como argumento existe, en tal caso contabilizar la cantidad de archivos y directorios, guardar ambos contadores en un archivo.
Usar una estructura repetitiva para resolverlo.
9- Muestre los números naturales del 1-20
10- Hacer un script que visualice un menú de tres opciones, la primera borra un fichero
cualquiera, la segunda visualiza un fichero, la tercera copia un archivo al directorio actual y la cuarta sale del script.
11- Hacer un script que pida continuamente una palabra clave, si la palabra introducida es “secreto” que nos muestre un mensaje de Bienvenida.
12- Hacer un script que compare dos cadenas de caracteres introducidas como parámetro, previamente comprobar si el número de parámetros es correcto. Dejar un mensaje en pantalla que diga cadenas correctas o incorrectas.
13- Hacer un script que evalúe el tamaño de 2 directorios cualesquiera pasado por parámetro y determine cuál de ellos tiene mayor tamaño.
14- Hacer un script que elimine una cadena de caracteres cualquiera, de un archivo ordinario pasado por parámetro. Genere un archivo nuevo como salida, y cambie los permisos a este archivo para que solo lo pueda leer y escribir el dueño. Chequear que se pase el parámetro y que el mismo sea un archivo ordinario.
15- Hacer un script que lea por parámetro el directorio tp2 (solo los ejercicios de script), a cada archivo leído cambiarle la palabra bash por sh, y guardar el archivo modificado en un directorio llamado “scripts-sh” dentro de tp3.
16- Hacer un script que lea un archivo por parámetro y borre un rango de líneas del mismo. Chequear que el archivo pasado por parámetro sea de tipo ordinario.
17- Hacer un script que acepte un fichero como parámetro, comprobar si este existe, en caso que si exista convertir todas sus letras minúsculas en mayúsculas en lo que respecta al contenido del mismo.
18- Hacer un scripts que al pasarle un directorio cualquiera que contenga archivos ordinarios, le borre a cada uno de los archivos las líneas 2 a 5, el nuevo archivo de salida se debe llamar igual que el original con el agregado al final del nombre “-m”, los archivos nuevos dejarlos en un directorio de nombre “ar-modificados”
19- Hacer un scripts que al pasarle un directorio cualquiera que contenga archivos ordinarios, le inserte 3 espacios en blanco al principio de cada línea.
20- Escribir un script que copie todos los archivos ejecutables de la carpeta “tp2” a una carpeta llamada “execu” y los no ejecutables a una carpeta llamada “no-execu”, ademas generar un listado con los nombres de los archivos copiados.
