1.¿qué diferencia hay entre ambas?



\-Apache: incluye el servidor web Apache preconfigurado junto con PHP. Está lista para recibir y contestar peticiones web de forma autónoma.



\-fpm: incluye únicamente el motor de PHP optimizado. Para funcionar como página web, requiere obligatoriamente estar conectada a un servidor web independiente (como Nginx u otro contenedor) que reciba las peticiones HTTP de los usuarios y se las pase al contenedor FPM para procesarlas.



2.¿qué significa php8.3?



Dentro de ese contenedor tiene instalada específicamente la versión 8.3 del lenguaje de programación PHP para ejecutar el código de WordPress.



3.¿por qué no conviene usar latest?



Apunta siempre a la última versión publicada y cambia con el tiempo. Si en el futuro se publica una actualización mayor de WordPress o PHP que incluye cambios incompatibles, tu entorno podría actualizarse automáticamente al reconstruir o descargar la imagen, rompiendo tu sistema en producción.

