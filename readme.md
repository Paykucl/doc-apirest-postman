## -Postman Payku API Collection-

#### Introducción:
-En Payku ahora te ofrecemos una colección en Postman el cual te permite trabajar a través de una extensión en el navegador o como aplicación desde tu sistema, para un uso rápido y fácil de nuestras API REST, ideal tanto para desarrolladores como usuarios.
-De igual forma proporcionamos un entorno personalizado, que se puede importar cómodamente para aplicar modificaciones y usarlo con sus claves secretas.
Para obtener más información acerca de la documentación Payku puede ingresar a [Documentación](https://docs.payku.cl/ "Documentación").

------------

#### Importar Archivos a la Aplicación:
1. Descarga los archivos **JSON** de las colecciones Payku API. Puedes obtener esos archivos {aqui}.

2. Una vez descargado los archivos, abra la aplicación Postman y diríjase a la pestaña (**Workspaces**) en la parte superior izquierda.
//imagen.1 -> entrar a workspaces

3. Importe la colección y ambiente a la aplicación Postman haciendo click izquierdo en el (**Import**) ubicado en la parte superior izquierda y luego click en (**Upload Files**) en la página emergente, posteriormente seleccione los archivos descargados.
//imagen.2 -> click a import

-Una vez realizado el proceso contará con los archivos JSON de la colección en su aplicación los cuales tendrán diferentes folders y request que podrá modificar cómodamente.

------------

#### Validar Autorización con Tokens Personales:
1. Una vez contamos con los tokens de integración facilitados por Payku desde su registro, procedemos a ingresar en el ambiente de la colección.

2. Nos ubicaremos en la parte izquierda de la aplicación haciendo click izquierdo en (**Enviroments**) y luego click izquierdo en el folder de (**Payku API**). Posterior a esto copiaremos los tokens en las variables prediseñadas, correspondiendo una al token público y una al token privado y daremos click izquierdo en (**Save**).
//imagen.3 -> cambio de token

-Realizado este proceso la aplicación Postman rellenara de forma automática la autorización en todos los folders y request de la colección.

------------

#### Modificar Datos para Crear/Generar/Insertar:
1. Ya con la autorización registrada ingresamos en cualquier request (**Post**) ubicados en los folders de la colección. Para acceder hacemos click izquierdo en (**Collections**) ubicado en la parte izquierda de la aplicación y luego desplegamos el folder al cual queremos ingresar en el icono ( **\/** ) con click izquierdo y seleccionamos el request deseado.
//imagen.4 -> selección post

2. Una vez seleccionado el (**Post**) deseado hacemos click izquierdo en (**Pre-request Script**) ubicado en la parte central de la aplicación y tendremos acceso al cuerpo modificable. Una vez modificado los datos hacemos click izquierdo en (Save) y luego en (Send) para transmitir los datos.
//imagen.5 -> modificar información

------------

#### Obtener Datos en un Proceso Especifico:
1. En este proceso ingresaremos en un request (**Get**) de obtención específica, luego cambiamos el (**Código ID**) valido para la solicitud que se desea obtener según el request seleccionado.
2. Copiará el (**ID**) valido de la solicitud requerida y luego se pegara en la barra url a partir del ( **/** ) como se muestra en el ejemplo 1 y 2. Finalmente hacemos click izquierdo en (**Save**) y luego en (**Send**).
//imagen.6 -> obtener datos

------------

-Para mayor información sobre la aplicación Postman también puede acceder a su documentación ingresando en [Doc Postman](https://learning.postman.com/docs/getting-started/introduction/ "Doc Postman").