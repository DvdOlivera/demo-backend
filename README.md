# Demo- Peticiones GET/POST/DELETE a una base de datos MySQL
Demo de habilidades Backend con APP engine subido a Google Cloud, para generar peticiones GET/POST/DELETE a una base de datos MySQL en este caso mediante POSTMAN.

## REQUISITOS
Con el fin de poder generar peticiones a la base de datos  es necesario contar con un gestor de peticiones a  APIs de terceros , en este caso:

- [POSTMAN](https://www.postman.com/downloads/).

## CÓMO HACER PETICIONES 

-Una vez instalado POSTMAN y creada una cuenta podremos generar las diferentes peticiones posibles dentro del proyecto, estas son:

### Peticiones GET 

- Seleccionar el método GET

[Imgur](https://i.imgur.com/V6cLJO5.png)

- Completar el campo para la URL copiando el siguiente link https://springgcp-345817.rj.r.appspot.com/usuarios

- Clickear en el botón SEND.

Abajo en la pestaña de Body aparecerá un arreglo con los Usuarios creados en  la Base de datos.

Además, podemos obtener cada Usuario registrado en la Base de datos agregando una barra "/" mas el ID del Usuario, por ejemplo :

- https://springgcp-345817.rj.r.appspot.com/usuarios/1

Esto nos devolverá el Usuario con el ID 1 .

### Peticiones POST

- Seleccionar el método POST

- Completar el campo para la URL copiando el siguiente link https://springgcp-345817.rj.r.appspot.com/usuarios

- Seleccionar la opción "Body" en el campo inferior

- Tildar la opción "raw"

- Seleccionar el tipo de archivo "JSON"

- Completar el campo inferior con los datos necesarios para cargar un nuevo usuario a la base de datos

- Clickear en el botón SEND

Nos devolverá el usuario ya creado con un ID.

### Peticiones DELETE ( No permitidas )







