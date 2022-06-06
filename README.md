# IsisAteneaJuarezGuzman
Evaluación Tecnica SalesForce

**Ejercicio 1**

Se realizó la instalacion de los componenetes

**Ejercicio 2**

1.	¿Qué es un servidor HTTP? 

  Es el encargado del acceso de los usuarios a los archivos o rutas de nuestros sitios usando el protocolo HTTP

2.	¿Qué son los verbos HTTP? Mencionar los más conocidos
  
  Post, Get, Put, Delete, Patch

3.	¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers? 
  
  El request es la petición que se le enviaría al servicio, el respose es la respuesta que devuelve el servicio, los headers son los cabeceros y en esos se envía información del la pagina a servidor mediante la url

4.	¿Qué es un queryString? (En el contexto de una url)
  
  Cuando se envía una petición mediante la url se puede especificar el método a consultar y enviar los parámetros que reciba el método al que estamos apuntando

5.	¿Qué es el responseCode? ¿Qué significado tiene los posibles valores devueltos?
  Es una serie de 3 números donde de manera simplificada nos indica los estados de las respuestas se agrupan en 5 categorías y el más común es el 404  not found 

6.	¿Cómo se envía la data en un Get y cómo en un POST? 
  
  Cuando se envía mediante un Get los datos son visibles para el usuario y se envían mediante la url, y cuando se envían mediante el Post no son visibles para el usuario y estos se envían mediante una clase o un método que no es visible para el usuario

7.	¿Qué verbo http utiliza el navegador cuando accedemos a una página?
  
  Get

8.	Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles.
  
  JSON es una estructura de texto independiente del lenguaje de programación lo cual sirve para comunicarse entre plataformas que no compartan el mismo lenguaje 
  {
     “nombre” : “Isis Atenea”,
     “edad” : 30 ,
     “fechaNacimiento”[
         “dia”:22,
         “mes”:05
         “anio”:1992
       ]
  }
  
  XML es un lenguaje de código abierto que describe el sentido de los datos para la representación de documentos
  <candidata>
     <nombre>Isis Atenea </nombre>
     <edad>30</edad>
     <fechaNacimiento>22051992</fechaNacimiento>
  </candidata>

9.	Explicar brevemente el estándar SOAP
  
  Es el protocolo que define como dos objetos de diferentes procesos se comunican entre si por medio del intercambio de datos XML, este a su vez se puede utilizar para generar protocolos más complejos

10.	Explicar brevemente el estándar REST Full
 
 Funciona para compartir información tanto de salida como, de entrada, este trabaja sobre el protocolo HTTP con los principales métodos Get, Post, Put, Delete

11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?
  
  Los headers son los que trasmiten la información sobre el navegador del cliente de la página solicitada, el key content type describe el formato del tipo del archivo 
 
 **Ejecicio 3**
 
1.- ![1 - GET](https://user-images.githubusercontent.com/106858116/171985835-a644a5c8-2f19-4747-9ce5-29d1704752cc.png)

2.- ![2 - POST](https://user-images.githubusercontent.com/106858116/171985888-b523341d-166c-4b6b-bdd3-b48064ec5fd6.png)

3.- ![3 - RAW](https://user-images.githubusercontent.com/106858116/171985910-e36c4806-5ba7-4398-89c2-4d6eff071746.png)

¿Qué diferencias se observan entre las llamadas el punto 1 y 3?

  La diferencia es que se agrego un registro nuevo después de realizar el punto 2 es decir cuando se envío la petición en POST 

**Ejercicio 4**

URL --> https://trailblazer.me/id/ijuarezguzman

**Ejercicio 5**

1.	Lead -- >  Se refiere a un cliente o prospecto a adquirir un servio
2.	Account -- > Es el nombre de la compañía o consumidor de salesforce y almacena datos referentes a la misma
3.	Contact -- > Son los datos de las personas relacionadas a la cuenta (Account)  
4.	Opportunity -- > Es el encargado de realizar el seguimiento de las ventas y tratos pendientes 
5.	Product -- > Es cualquier cosa que venda la organización puede ser un servicio o un articulo
6.	PriceBook -- > Es el concentrado de productos y/o servicios que ofrece la organización 
7.	Quote -- > Es un registro que contiene los precios y propuestas con los productos o servicio 
8.	Asset -- > Es el producto especifico que tiene el cliente 
9.	Case -- > Es la descripción de un problema que tiene el cliente para poder brindarle el seguimiento correspondiente
10.	Article -- > Es la descripción especifica de los productos y/o servicios y este en conjunto generan una base de conocimientos

![Diagrama](https://user-images.githubusercontent.com/106858116/171986021-150dc789-836f-48af-99e7-65f53c054f5b.png)

**Ejercicio 6**

Soluciones de Salesforce
A.	¿Qué es Salesforce?

Es un sistema de CRM que permite personalizar los sistemas para cada empresa que los contraté sin la necesidad de generar grandes bloques de código

B.	¿Qué es Sales Cloud?

Es un software especializado en ventas que permite al cliente tener su información almacenada en la nube

C.	¿Qué es Service Cloud?

Es una plataforma de atención al cliente completamente digital que permite al cliente conocer a sus clientes y usuarios de manera completa

D.	¿Qué es Health Cloud?

Es 

E.	¿Qué es Marketing Cloud?

Es un software especializado en el para tener amplio conocimiento del cliente y sus necesidades, así como actualizar las campañas nuevas que se vayan generado
Funcionalidades de Salesforce
A.	¿Qué es un RecordType?

Permite definir los procesos de un negocio con múltiples propósitos dependiendo lo solicitado por el usuario

B.	¿Qué es un ReportType?

Es un reporte que se genera con los datos especificados por el usuario que puede contener información de distintas tablas relacionadas

C.	¿Qué es un Page Layout?

Es el diseño de la página en la cual podemos diseñar la página para el cliente con diferentes funcionalidades y esta solo es accesible si se cuenta con los permisos necesarios

D.	¿Qué es un Compact Layout?

Es un diseño compacto de nuestra página el cual puede ser mostrado en el celular o en apis dentro de otras paginas

E.	¿Qué es un Perfil?

Son las características de un usuario sus permisos y acciones que puede o no realizar dentro de la plataforma

F.	¿Qué es un Rol?

Se entiende como la categoría donde se encuentra clasificado un usuario o su perfil

G.	¿Qué es un Validation Rule?

Es una regla que no permite continuar con un proceso si no cumple con las especificaciones que esta regla tenga definidas

H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?

Master Detail tiene una dependencia directa entre los objetos mientras que Lookup no necesariamente deben tener relación los objetos

I.	¿Qué es un Sandbox?

Es una copia del sistema que se encuentra en producción

J.	¿Qué es un ChangeSet?

Es un conjunto de modificaciones o cambios dentro de la aplicación que se envían para realizar pruebas en un objeto aislado

K.	¿Para qué sirve el import Wizard de Salesforce?

Para importar registros de manera dinámica sin necesidad de ingresar registro por registro

L.	¿Para qué sirve la funcionalidad Web to Lead?

Para crear formularios y registrar información sin la necesidad de escribir código

M.	¿Para qué sirve la funcionalidad Web to Case?

Permite crear contenedores con formularios para insertarlos en su página web y enviar los datos a la plataforma de salesforce

N.	¿Para qué sirve la funcionalidad Omnichannel?

Para administrar todo tipo de contacto del cliente con una plataforma para enviarlos a agentes más capacitados para dar solución a su problemática 

O.	¿Para qué sirve la funcionalidad Chatter?

Para permitir a los usuarios comunicarse en tiempo real y solucionar dudas junto con otros usuarios y esto motiva a los usuarios para trabajar de manera eficiente 
Conceptos generales
A.	¿Qué significa SaaS?

Software as a Service -- > Software como un servicio 

B.	¿Salesforce es Saas?

Es la manera en que se entrega el sistema al cliente para que este funcione a medida de las necesidades del cliente, el Saas es el encargado de dar mantenimiento diario a la aplicacion 

C.	¿Qué significa que una solución sea Cloud?

Que permite el acceso remoto al sistema es decir no se encuentra acoplado a una sola maquina

D.	¿Qué significa que una solución sea On-Premise?

Que esta solución necesita de un servidor físico sobre el cual se dará mantenimiento y se instalará el CRM

E.	¿Qué es un pipeline de ventas?

Es la manera en que se gestionan los clientes donde se registraran únicamente los datos importantes para el proceso de la venta


F.	¿Qué es un funnel de ventas?

Es el encargado de presentar la información sobre porcentaje de perdidas existente en cada parte del proceso que lleva el cliente dentro de la página de ventas.

G.	¿Qué significa Customer Experience?

Se refiere a la manera en que el usuario interactúa con la plataforma, es decir la imagen que tiene de la empresa y esta puede ser buena o mala dependiendo de la misma plataforma

H.	¿Qué significa omnicanalidad?

Es la manera de interactuar o captar al cliente mediante diferentes medios (mensajes, llamadas, redes sociales, correos, etc)

I.	¿Qué significa que un negocio sea B2B? ¿Qué significa que un negocio sea B2C? ¿Qué es un KPI?

B2B -- > Business to Busines son negocios entre empresas 
B2C -- > Business to Consumer es la relación de negocio entre una empresa y un usuario que no es una empresa
KPI -- > Key Performance Indicator se refiere a la manera de medir los procesos internos de una empresa y medir si se están cumpliendo los objetivos que la empresa tenga en un cierto periodo de tiempo 

J.	¿Qué es una API y en qué se diferencia de una Rest API?

Es una aplicación de software que permite la comunicación con otras mediante protocolos y se diferencia de una Rest API que la API es de aplicación a aplicación mientras que las API Rest se relacionan de Cliente a Servidor

K.	¿Qué es un Proceso Batch?

Es un proceso que al ejecutarlo presenta un ticket, y este no se realiza en línea para así no detener la operación este se realiza de manera automática y al finalizar actualiza el estatus del ticket del proceso, se usa para procesos complejos que toman un poco más de tiempo.

L.	¿Qué es Kanban?

Es un tipo de metodología que es basada en la filosofía centrada en la mejora continua, donde las tareas se “extraen” de una lista de acciones pendientes en un flujo de trabajo constante, esta implementa los tableros Kanban que permiten ver el avance del proyecto

M.	¿Qué es un ERP? 

Se refiere a la planificación de recursos empresariales es decir los datos de las transacciones compartidos por las diversas fuentes de una organización, elimina la duplicación de los datos y proporciona una integridad de datos con una única fuente de confianza.

N.	¿Salesforce es un ERP?

Si


**Ejercicio 7**

![Trigger](https://user-images.githubusercontent.com/106858116/172105901-102dddbc-cd44-47b1-9e5d-56d8786614a8.png)


Agradezco su atencion :)
