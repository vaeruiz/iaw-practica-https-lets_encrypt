# HTTPS con Let’s Encrypt y Certbot

Instalando una aplicación web y añadiendo un certificado HTTPS.

## Preparando la máquina

Necesitamos una máuina con al menos 2GB de RAM y con los puertos HTTP(80) y HTTPS(443) abiertos.

## Preparando nuestro dominio

Ahora vamos a crear nuestro nombre de dominio, para ello tendremos que ir a la página [Freenom](https://www.freenom.com/es/index.html?lang=es), nos registramos en su página e iniciamos sesión, cuando estemos logueados vamos a Servicios>Registrar nuevo dominio. Se nos abrirá una nueva página en la que ingresaremos el nombre de dominio que queremos crear y pulsaremos el botón para comprobar la disponibilidad.

Si está libre, podremos elegir una lista de dominios, cuando seleccionemos el que queremos, en la parte superior saldrá que tenemos un doominio añadido junto con un botón llamado checkout, le damos y pasamos a la pantalla de "compra". Sobre el tiempo que estará el dominio disponible, seleccionamos 1 mes ya que esto es una prueba. 

Le damos a continuar, en la pantalla de confirmación aceptamos los términos y condiciones de uso, y le damos a completar encargo.

Cuando termine este proceso, volvemos a la ventana de servicios y vamos a Mis dominios, dentro veremos que ya podemos utilizar el dominio que hemos reservado antes, vamos a sus opciones (botón Manage Domain), una vez dentro vamos a la sección Manage Freenom DNS.

En la nueva página que se nos abre, deberemos de crear 2 registros DNS de tipo A que apunten a nuestra máquina de Amazon, en mi caso los registros han quedado de la siguiente manera.

![Imagen de demostracion 1](/capturas/captura1.png)
