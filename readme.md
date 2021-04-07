# Postman Payku API Collection

## Tabla de Contenido
* [Introducción](#introducción)
* [Importar Archivos a la Aplicacion](#importar-archivos-a-la-aplicación)
* [Validar Autorizacion con Tokens](#validar-autorización-con-tokens-personales)
* [Modificar Datos para POST y PUT](#modificar-datos-para-post-y-put)
* [Modificar Datos Especificos GET y DEL](#modificar-datos-especificos-get-y-del)

------------

## Introducción.
En Payku te ofrecemos una colección en Postman la cual te permite trabajar a través de una extensión en el navegador o como aplicación desde tu sistema, para un uso rápido y fácil de nuestras API REST, ideal tanto para desarrolladores como usuarios.

De igual forma proporcionamos un entorno personalizado, que se puede importar cómodamente para aplicar modificaciones y usarlo con sus tokens publicos y privados.
Para obtener más información acerca de la documentación Payku puede ingresar a <a href="https://docs.payku.cl/" target="_blank">Documentación</a>.

------------

## Importar Archivos a la Aplicación.
1. Descarga los archivos **JSON** de las colecciones Payku API. Podrá obtener esos archivos descargando este repositorio.

2. Una vez descargado los archivos, abra la aplicación Postman y diríjase a la pestaña (**Workspaces**) en la parte superior izquierda.
![](https://github.com/Paykucl/doc-apirest-postman/blob/master/img/imagen1.png?raw=true)

3. Importe la colección y ambiente a la aplicación Postman haciendo clic izquierdo en el (**Import**) ubicado en la parte superior izquierda y luego clic en (**Upload Files**) en la ventana emergente, posteriormente seleccione los archivos descargados.
![](https://github.com/Paykucl/doc-apirest-postman/blob/master/img/imagen2.png?raw=true)

Una vez realizado el proceso contará con los archivos JSON de la colección en su aplicación los cuales tendrán diferentes folders y request que podrá modificar cómodamente.

------------

## Validar Autorización con Tokens Personales.
1. Una vez contamos con los tokens de integración creados en la plataforma Payku luego de su registro, procedemos a ingresar en el ambiente de la colección.

2. Nos ubicaremos en la parte izquierda de la aplicación haciendo clic izquierdo en (**Enviroments**), seleccionaremos la carpeta de (**Payku API**). A continuación reemplacé las variables token_pub y token_priv con los tokens público y privado respectivamente y haremos clic izquierdo en (**Save**).
![](https://github.com/Paykucl/doc-apirest-postman/blob/master/img/imagen3.png?raw=true)

Realizado este proceso la aplicación Postman generara automáticamente la autorización en todos los folders y request de la colección.

------------

## Modificar Datos para POST y PUT.
1. Ya con la autorización registrada ingresamos en cualquier request (**POST**) ubicados en los folders de la colección. Para acceder hacemos clic izquierdo en (**Collections**) ubicado en la parte izquierda de la aplicación y luego desplegamos el folder al cual queremos ingresar en el icono ( **\/** ) con clic izquierdo y seleccionamos el request deseado.
![](https://github.com/Paykucl/doc-apirest-postman/blob/master/img/imagen4.png?raw=true)

2. Una vez seleccionado el (**POST**) deseado hacemos clic izquierdo en (**Pre-request Script**) ubicado en la parte central de la aplicación y tendremos acceso al cuerpo modificable. Una vez modificado los datos hacemos clic izquierdo en (Save) y luego en (Send) para transmitir los datos.
![](https://github.com/Paykucl/doc-apirest-postman/blob/master/img/imagen5.png?raw=true)

------------

## Modificar Datos Especificos GET y DELETE.
1. En este proceso ingresaremos en un request (**GET**) de obtención específica o (**DELETE**), luego cambiamos el (**Código ID**) valido para la solicitud que se desea obtener según el request seleccionado.
2. Copie el (**ID**) valido de la solicitud requerida y luego se pegara en la barra url a partir del ( **/** ) como se muestra en el ejemplo 1 y 2. Finalmente haremos clic izquierdo en (**Save**) y posteriormente en (**Send**).
![](https://github.com/Paykucl/doc-apirest-postman/blob/master/img/imagen6.png?raw=true)

------------

Para mayor información sobre la aplicación Postman también puede acceder a su documentación ingresando en <a href="https://learning.postman.com/docs/getting-started/introduction/" target="_blank">Doc Postman</a>.

<div align="right">
  <small><a href="#tabla-de-contenido">🡡 volver al inicio</a></small>
</div>
