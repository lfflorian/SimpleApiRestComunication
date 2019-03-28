# Simple Api Rest Comunication 

## Descripcion 

Modulo para realizar comunicaciones HTTP con API REST de manera simple con un solo metodo

## Metodos

**SendData**

Metodo utilizado para realizar las peticiones a una api rest

Parmetros
- url : Ruta de la Api Rest a consumir
- data : Los datos a enviar en una cadena de texto
- Headers : Coleccion de valores a enviar en el Header de la petición
- Method : Metodo a invocar en la api Rest (Se selecciona en el enum de Method)
- ContentType : El tipo de contenido a enviar

**GetResponseData**

Metodo para extraer los datos de la respuesta usando el metodo *SendData*

Parametros
- Response : Respuesta obtenida del metodo *SendData*

**Method**

enumerados utilizado para seleccionar el metodo a invocar

## Referencia

Las solicitudes son enviadas con los metodos que provee la biblioteca System.Net.Http
