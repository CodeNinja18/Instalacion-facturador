GUIA DE INSTALACION DEL FACTURADOR:

PASO 1: Para comenzar la instalacion debemos instalar LARAGON
![image](https://github.com/CodeNinja18/Instalacion-facturador/assets/131321652/8a319bc9-3453-4034-9691-70489772dbaf)

PASO 2: ahora comenzaremos con la configuracion y escogeremos PHP tambien añadiremos las extensiones

PASO 3: Ahora debemos ingresar a la terminal desde LARAGON y clonar nuestro repositorio

PASO 4: Debemos actualizarer Composer con update composer, esto puede tarder unos minutos.

PASO 5: una vez que haya terminado de cargar escribiremos un par de comandos mas

Paso 6: Crearemos una base de datos y lo conectamos a Laragon, luego ingresaremos al gestor de archivo y elegiremos nuestra carpeta

Paso 7: ahora ingresaremos los siguientes codigos: php artisan key:generate, composer dump-autoload, php artisan migrate --seed y luego php artisan storage:link

Paso 8: Por ultimo cerramos Laragon y lo volvemos abrir para tener los cambios y tendremos instalado el facturador
