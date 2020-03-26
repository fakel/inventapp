# Inventapp
Aplicación para administrar inventario de bienes de Laboratoria

# Vistas
![Diagrama App](images/Inventario.svg?sanitize=true)

# Historias de Usuario

* Al ingresar a la aplicación desde mi dispositivo móvil debo autenticarme con mi correo Gmail de dominio ```@laboratoria.la```
* Al estar autenticado, debo poder ver dos opciones, ```Agregar``` y ```Consultar```
* Cuando voy a agregar un bien al inventario, debo poder agregar un número indefinido de características con valores completamente personalizables
    * Opcional: debe ser posible incluir una foto del bien
* Una vez guardada la información del bien se me ha de mostrar un código QR asociado al identificador del bien y su ID. También debe permitirme imprimir el QR con el ID.
* Cuando voy a consultar un código de bien debe activar la cámara de mi dispositivo y debe detectar automáticamente el código QR a la vista
* Si el código coincide con algún bien, la información de este debe ser mostrado
    * Opcional: si existe una foto del bien almacenada, se debe mostrar
* En la vista de consulta, si deseo repetir la consulta para otro bien, debo poder limpiar la vista actual y volver a ofrecer el "scanner"

# Requerimientos técnicos

* La consulta y almacenamiento de datos sólo debe ser posible para usuarios autenticados con correo Gmail de dominio @laboratoria.la
* Se desea que la aplicación sea una PWA orientada a dispositivos móviles
* Se espera que la aplicación sea desarrollada con alguna de las siguientes herramientas: React, Angular, Vue
* Se solicita que los "test" tengan una cobertura mínima de 70%
* Son aceptables el uso de Firebase ó NodeJS+Express+Mongo
