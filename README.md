En el archivo .env se encuentran las variables, modificarlo al gusto de cada uno.

Para habilitar la interfaz al español, levantar los contenedores y ejecutar el siguiente comando para sobreescribir el archivo de los lenguajes:
docker cp ./locales.inc.php zabbix-web:/usr/share/zabbix/include/locales.inc.php

Una vez cambiado, reiniciamos los contenedores:
docker-compose restart
