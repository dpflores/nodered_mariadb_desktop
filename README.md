# Nodered en docker 

Este archivo crea un contenedor de nodered  con una base de datos mariadb (desktop) y php para ver los datos. 
 
Para que el folder de data de nodered y de mariadbse pueda utilizar, ejecutar en la terminal

```

mkdir nodered-data
mkdir mariadb-data

sudo chown -R 1000:1000 nodered-data
sudo chown -R 1000:1000 mariadb-data
```

luego, ejecutar levantar los servicios

```
docker compose up
```


En phpmyadmin, ingresamos con el user crado y la contraseña de secrets