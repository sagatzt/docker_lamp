# docker_lamp
### docker-compose 
El composed se compone de:
1. www-php: es una imagen __no oficial__ de php con apache
2. mysql: versión oficial 8.0.25
3. phpmyadmin/phpmyadmin: versión oficial

Para lanzarlo: $ docker-compose up -d

### notas
Por algún motivo, no consigo que haga el volcado automático del archivo .sql que se encuentra en /dump cuando se genera la imagen de docker-compose. ¿¿??
