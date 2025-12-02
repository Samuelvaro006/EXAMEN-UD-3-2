# Migración de un wordpress a un hosting 

## Paso 1
Lo primero que debemos hacer, es instalar wordpress y trabajar de manera local. Una vez lo tengamos listo, tenemos que buscar una página de hosting, como hicimos en clase, o una de pago. (En mi caso nombraré a atwebpages).

## Paso 2 
Lo segundo que haremos será crear un subdominio dentro del hosting, y dentro de ese dominio, subiremos los archivos del cms al subdominio, es como si subimos algo que estaba en local a la nube. 

## Paso 3
Como en local ya creamos una base de datos, ahora toca crearla desde el propio hosting, como hicimos en clase. 
Luego, tenemos que cambiar dentro del config.php en el fichero de wordpress. Hay que cambiar la definición de las bases de datos, y poner las credenciales que hemos creado en el hosting, para que en vez de coger la base de datos que tenemos en local, usar la base de datos del hosting. 


## Paso 4
 Es importante guardar todo , una vez esté todo listo, si nos vamos al navegador y ponemos el nombre que hemos asignado, debería de salir nuestro wordpress. 

# COSAS A RECALCAR
Tenemos que saber que tenemos dos Wordpress, uno en **local** y otro en el **host**, por lo que para hacer desarrollo trabajaremos con el local, para que no haya fallos, y en el host no haremos nada de pruebas y solo publicaremos las versiones finales. 