# Demo- Peticiones GET/POST/DELETE a una base de datos MySQL
Demo de habilidades Backend con APP engine subido a Google Cloud, para generar peticiones GET/POST/DELETE a una base de datos MySQL en este caso mediante POSTMAN.

## REQUISITOS
Con el fin de poder generar peticiones a la base de datos  es necesario contar con un gestor de peticiones a  APIs de terceros , en este caso:

- [POSTMAN](https://www.postman.com/downloads/).

## CÓMO HACER PETICIONES 

-Una vez instalado POSTMAN y creada una cuenta podremos generar las diferentes peticiones posibles dentro del proyecto, estas son:

### Peticiones GET 

- Seleccionar el método GET

![Imgur](https://i.imgur.com/V6cLJO5.png)

- Completar el campo para la URL copiando el siguiente link https://springgcp-345817.rj.r.appspot.com/usuarios

![Imgur](https://i.imgur.com/g3nr36y.png)

- Clickear en el botón SEND.

![Imgur](https://i.imgur.com/1EYCNT7.png)

Abajo en la pestaña de Body aparecerá un arreglo con los Usuarios creados en  la Base de datos.

![Imgur](https://i.imgur.com/v7QuJ3w.png)

Además, podemos obtener cada Usuario registrado en la Base de datos agregando una barra "/" mas el ID del Usuario, por ejemplo :

- https://springgcp-345817.rj.r.appspot.com/usuarios/1

Esto nos devolverá el Usuario con el ID 1 .

### Peticiones POST

- Seleccionar el método POST

![Imgur](https://i.imgur.com/d5T3imS.png)

- Completar el campo para la URL copiando el siguiente link https://springgcp-345817.rj.r.appspot.com/usuarios

![Imgur](https://i.imgur.com/zt6GhQw.png)

- Seleccionar la opción "Body" en el campo inferior

![Imgur](https://i.imgur.com/sewylMs.png)

- Tildar la opción "raw"

![Imgur](https://i.imgur.com/BT2MGXX.png)

- Seleccionar el tipo de archivo "JSON"

![Imgur](https://i.imgur.com/xqkm1Ui.png)

- Completar el campo inferior con los datos necesarios para cargar un nuevo usuario a la base de datos

![Imgur](https://i.imgur.com/gWDppRn.png)

- Clickear en el botón SEND

![Imgur](https://i.imgur.com/EqG1k0Q.png)

Nos devolverá el usuario ya creado con un ID.

![Imgur](https://i.imgur.com/lhWabjs.png)

### Peticiones DELETE ( No permitidas )







