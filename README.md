# TP Backend TTADS 2021

## 1 - Enunciado

El sistema a desarrollar será una mini red social donde los usuarios podrán compartir publicaciones con imágenes, las cuales podrán ser comentadas y reaccionadas por otros usuarios. Los usuarios podrán relacionarse o conectarse con otros usuarios mediantes grupos de amistad. Los usuarios tendrán el control de quien puede ver, comentar o reaccionar a sus publicaciones.

## 2 - Funcionalidades

* Registro de usuarios (propio o con Google Sign-in)
* Autenticacion con JWT.
* Cambio de contraseña (excepto usuarios registrados con Google)
* Realización de publicaciones, comentarios y reacciones por parte de los usuarios.
* Envío de solicitudes de amistad.
* Bloqueo de usuarios
* Envío de emails.

## 3 - Checklist

|Requerimiento funcional|cant. mín.<br>1 o 2 integ|cant. máx.<br>3 o 4 integ|Detalle/Listado de casos|Cumple|
|:-|-:|-:|:-|-|
|ABMC simple|1 x integ|1 x integ|Roles, Países, Usuarios|
|ABMC dependiente|1|2|Solicitudes, Publicaciones, Comentarios|
|Listado simple|1|1|Listado de usuarios registrados/bloqueados, Listado de países|
|Listado complejo obligatorio|1|2|Listado de comentarios por usuario, Listado de publicaciones con más comentarios/reacciones, Listado de publicaciones por rango de fecha|
|Listado adicional con filtro|0|0|
|Detalle básico|1(*)|2(*)|
|Detalle parametrizable|0|0|
|Otros|0|0|

## 3 - Modelo de dominio

https://drive.google.com/file/d/1cEl-ZKg6NjoHgEPn3z_RY9fGMgrWkCgq/view?usp=sharing

## 4 - Integrantes

|Apellido y Nombre|Legajo|
|:-|-|
|Berón, Fernando|31836|
|Tabasso, Nahuel|43204|
