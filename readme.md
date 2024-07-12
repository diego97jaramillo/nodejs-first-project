Acá tienes las respuestas del punto 8.

1. ¿Qué es el filesystem (fs) en Node.js y para qué se utiliza?
es un modulo que esta diseñado especificamente para la manipulacion de archivos, por eso mediante el filesystem es que podemos leer y escribir archivos

2. ¿Qué es un middleware en Express y cuál es su propósito?
es una funcion que tiene accesos a ambos objetos(el request y response), con estos la funcion puede modificar su contenido, además tiene la capacidad de invocar la siguiente funcion middleware o terminar el ciclo. el proposito como bien se hablaba es el control de flujo de la informacion segun lo que se vaya encontrando en los objetos.


3. ¿Qué es un endpoint en una API RESTful y cuál es su función?
muestran la localizacion de los recursos, y normalmente tiene la funcion de responder la informacion segun lo requisitos predeterminados que ellos deben recibir

4. ¿Qué son los verbos HTTP y cuáles son los más comunes?

los más comunes son: get, post, put, delete, patch.
los verbos son los diferentes metodos que se envia en la peticion para que el servidor sepa que hacer y responda con la informacion solicitada


5. ¿Qué es JSON y por qué es utilizado en las API RESTful?
es un documento que su composicion tiene una denotacion especifa(objetos), es muy utilizado para poder enviar informacion mediante el cuerpo de la petición, y así permitir que las tecnologias se comuniquen entre ellas.

6. En lo que respecta al envio de datos a lo largo de los verbos http responde:
    ¿Qué es el body de una petición?
    el body es el contenido que se envía en la petición

    ¿Qué es el body de una respuesta?
    es el contenido el cual nos devuelve el servido en la respuesta

    ¿Qué es el query de una petición?
    normalmente son usados con el metodo get y son parametros que se envian segun la actividad del usuario y estos permiten tener unas respuestas especificas del contenido

    ¿Qué es el params de una petición?
    son las indicaciones que se envían segun la actividad del cliente, estos pueden variar segun el metodo que se este enviando en la peticion

7. En lo que respecta al verbo POST responde:
    ¿Qué es un verbo POST y cuál es su propósito?
    un metodo que se utiliza para enviar datos al servidor para crear un nuevo recurso.

    ¿Cuándo se utiliza un verbo POST?
    cuando se quiere añadir un nuevo dato a la base de datos

    ¿En qué se diferencia un verbo POST de los otros verbos HTTP como GET, PUT y DELETE?
    este altera el estado del recurso, al agregarle nuevos datos, los otros metodos necesitan que los datos sean existentes en la base de datos

    ¿Como se envian datos en un verbo POST?
    mediante el cuerpo de la peticion

8. En lo que respecta al verbo GET responde:
    ¿Qué es un verbo GET y cuál es su propósito?
    es el metodo para llamar todos los datos existentes en la base de datos

    ¿Cuándo se utiliza un verbo GET?
    cuando quieres ver los datos que tienes almacenados

    ¿En qué se diferencia un verbo GET de los otros verbos HTTP como POST, PUT y DELETE?
    este no modifica el estado del recurso

9. En lo que respecta al verbo PUT responde:
    ¿Qué es un verbo PUT y cuál es su propósito?
    es el metodo que se utiliza para cambiar la informacion de un dato existente en la base de datos

    ¿Cuándo se utiliza un verbo PUT?
    cuando se quiere cambiar la informacion que ya se tiene almacenado

    ¿En qué se diferencia un verbo PUT de los otros verbos HTTP como POST, GET y DELETE?
    este tiene como requisito que el elemento este ya creado pero este sí requiere informacion en el cuerpo de la petición

10. En lo que respecta al verbo DELETE responde:
    ¿Qué es un verbo DELETE y cuál es su propósito?
    es un metodo para eliminar datos de la base de datos, segun un atributo espeficos

    ¿Cuándo se utiliza un verbo DELETE?
    cuando quieres borrar un dato de la base de datos


    ¿En qué se diferencia un verbo DELETE de los otros verbos HTTP como POST, GET y PUT?
    tiene diferencias respecto a cada verbo pero la principal diferencia es que modifica el estado del recurso(datos) pero no contiene cuerpo. pues su funcion es eliminar el dato

11. ¿Qué es un status code y cuáles son los más comunes?
los status code son codigos estipulados que se van a enviar según el resultado de la peticion, hay codigos tanto de exito como de fracaso.


12. ¿Cuales son los status code mas comunes para el verbo POST?

201 Created: La solicitud ha sido exitosa y se ha creado un nuevo recurso.
200 OK: La solicitud ha sido exitosa y el servidor ha enviado una respuesta con el recurso modificado.
400 Bad Request: La solicitud no se pudo entender o era incorrecta.
401 Unauthorized: La solicitud requiere autenticación del usuario.
403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
404 Not Found: No se ha encontrado el recurso solicitado.
409 Conflict: Conflicto con el estado actual del recurso.


13. ¿Cuales son los status code mas comunes para el verbo GET?

200 OK: La solicitud ha sido exitosa y el servidor ha enviado el recurso solicitado.
304 Not Modified: El recurso no ha sido modificado desde la última solicitud.
400 Bad Request: La solicitud no se pudo entender o era incorrecta.
401 Unauthorized: La solicitud requiere autenticación del usuario.
403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
404 Not Found: No se ha encontrado el recurso solicitado.


14. ¿Cuales son los status code mas comunes para el verbo PUT?

200 OK: La solicitud ha sido exitosa y el servidor ha enviado una respuesta con el recurso modificado.
204 No Content: La solicitud ha sido exitosa, pero no se devuelve contenido en la respuesta.
201 Created: La solicitud ha sido exitosa y se ha creado un nuevo recurso.
400 Bad Request: La solicitud no se pudo entender o era incorrecta.
401 Unauthorized: La solicitud requiere autenticación del usuario.
403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
404 Not Found: No se ha encontrado el recurso solicitado.


15. ¿Cuales son los status code mas comunes para el verbo DELETE?

200 OK: La solicitud ha sido exitosa y el recurso ha sido eliminado.
204 No Content: La solicitud ha sido exitosa y no se devuelve contenido en la respuesta.
400 Bad Request: La solicitud no se pudo entender o era incorrecta.
401 Unauthorized: La solicitud requiere autenticación del usuario.
403 Forbidden: El servidor entiende la solicitud, pero se niega a autorizarla.
404 Not Found: No se ha encontrado el recurso solicitado

