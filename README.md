# ProContacto-RRHH-practicas

PATH IMG PRO CONTACTO

## EVALUACION PRACTICA
----------------
### EJERCICIO 1
----------------
#### Instalacion del ambiente

PATH IMG VISUAL STUDIO CODE

PATH IMG GIT Y GIT BASH

----------------
### EJERCICIO 2
----------------

1.¿Qué es un servidor HTTP? 
Se puede definir desde 2 perspectivas; Hardware, Software.
Desde la primera, se puede representar como una computadora que almacena,
los archivos que forman parte de una aplicación web.
En términos de software, se compone por partes o funciones que representan el control
que tiene un usuario sobre dichos archivos y datos a través de direcciones web (URLs).

2.¿Qué son los verbos HTTP? Mencionar los más conocidos
GET, HEAD, POST, PUT, DELETE.

3.¿Qué es un request y un response en una comunicación HTTP?
En el entorno de comunicación de HTTP, es una estructura de mensajes de datos intercambiables 
entre cliente-servidor, dividido en request y repsonse.
Request es una petición enviada por el cliente al servidor, siendo el response la acción ejecutada 
y devuelta por el servidor. 
¿Qué son los headers? 
Fundamentalmente forman parte de un HTTP request/response transmitiendo información sobre el 
browser del cliente, la página, servidor, etc.
4.¿Qué es un queryString? (En el contexto de una url)
Son la forma de búsqueda por medio de variables, que las aplicaciones web dinámicas usan 
para realizar consultas a bases de datos y recursos por medio de un GET, por ejemplo.

5.¿Qué es el responseCode? En lo que a un ResponseMessage se refiere, el ResponseCode forma parte del mensaje 
indicando el estado de la solicitud.
¿Qué significado tiene los posibles valores devueltos? Las respuestas pueden ser;
De información, satisfacción, redirección, error de clientes y error de servidores.

6.¿Cómo se envía la data en un Get y cómo en un POST? 
GET es menos seguro comparado con POST, ya que la data es enviada como parte del URL, por lo tanto, 
se guarda en el historial. POST es ligeramente mas seguro porque los parámetros no se guardan en el navegador.

7.¿Qué verbo http utiliza el navegador cuando accedemos a una página?
La información visual que presenta un sitio web se transmite a través del método GET, 
E.g. layout.css, image.png, page.html, etc.

8.Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de estructuras posibles. 
Ambos fueron diseñados para transmitir datos, con la diferencia de que el propósito de XML no es mostrar la información, 
solo transmitirla, se deriva de SGML y es un Markup language. La sintaxis de JSON está basada en JavaScript.

9.Explicar brevemente el estándar SOAP
Definiría que SOAP es un protocolo (como su nombre lo indica) ya que este solo funciona con XML.

10.Explicar brevemente el estándar REST Full
En lo que a una RESTful API se refiere, se puede decir que es una aplicación basada en patrones arquitectónicos 
y a diferencia de SOAP, trabaja con texto, XML, HTML y JSON.

11.¿Qué son los headers en un request? Un header contiene información sobre los puntos de comunicación, del usuario como:
* Host
* Usuario (Browser, OS type, verison)
* Lenguaje
* Codificación
* Conexión

¿Para qué se utiliza el key Content-type en un header?
El key-content es un header de representación e indica el tipo original de datos del recurso. 
En un request como “POST”, el cliente señala al servidor que tipo de datos están siendo enviados.

------------
### EJERCICIO 3 
------------

1.Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

PATH SCREENSHOT

2.Realizar un request POST a la URL anterior, y con body:

PATH SCREENSHOT

3.Realizar nuevamente un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json

PATH SCREENSHOT

------------
### EJERCICIO 4 
------------

Compartir la URL del perfil público de Trailhead en una liga dentro del Readme.

------------
### EJERCICIO 5
------------

1.	Lead: Representa un prospecto o cliente potencial.
2.	Account: Representa una cuenta individual, la cual puede ser una organización o persona relacionada con el negocio, i.e. clientes, competición y/o compañeros.
3.	Contact.: Representa a un contacto, el cual puede ser una persona asociada a una cuenta.
4.	Opportunity: Representa una apertura para una venta o trato pendiente.
5.	Product: Representa un producto que vende la compañía.
6.	PriceBook: Es el catálogo que contiene los productos que vende la organización.
7.	Quote: Es un objeto que representa y muestra los precios proupestos de un producto o servicio. 
8.	Asset: Representa un item de valor comercial, como un producto venta de la compañía o competencia, que el cliente ha adquirido e instalado.
9.	Case: Representa un caso, basado en el requerimiento de un cliente.
10.	Article: Es una selección de categorías de datos que representa y clasifica los artículos. Todo Salesforce Knowledge pude ser categorizado.

PATH SCREENSHOT 

------------
### EJERCICIO 6
------------

A.	Consultar tu ID haciendo un GET con POSTMAN a este WS:
PATH SCREENSHOT

B.	Agregar un campo al objeto Contact llamado idprocontacto de tipo texto de 255 caracteres. 
PATH SCREENSHOT

------------
### EJERCICIO 7
------------

#### Soluciones de Salesforce

A.	¿Qué es Salesforce? Es la plataforma CRM #1 que ofrece servicio de marketing, ventas entre otros servicios técnicos similares.

B.	¿Qué es Sales Cloud? Es un servicio de productos completamente personalizable que vincula información del cliente a la plataforma integrada.

C.	¿Qué es Service Cloud? Es una función o propiedad de Salesforce que permite al usuario automatizar procesos de servicio  
con el fin de brindar apoyo a agentes dirigidos a la clientela.

D.	¿Qué es Health Cloud? Este servicio integra el poder de la tecnología en la nube para crear un ambiente que usa una terminología específica 
para permitir de forma amigable el acceso a información.

E.	¿Qué es Marketing Cloud? Este servicio o herramienta recopila datos relevantes y los gestiona adecuadamente para lanzar una serie 
de campañas organizadas a medida considerando el retorno reciproco de la inversión.

#### Funcionalidades de Salesforce

A.	¿Qué es un RecordType?Te permite crear distintos diseños en el mismo entorno donde se crean diferentes procesos de negocios.

B.	¿Qué es un ReportType?Es un template que define los campos y objetos que estarán disponibles en el reporte que se va a crear.

C.	¿Qué es un Page Layout?Este permite personalizar el diseño y organización de los detalles y edición de páginas y registros en Salesforce.

D.	¿Qué es un Compact Layout? Muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, 
Lightning Experience y en las integraciones de Outlook y Gmail.

E.	¿Qué es un Perfil?Un perfil define a que tipo de datos y objetos un usuario tiene acceso y  como pueden hacer uso de la información en la aplicación.

F.	¿Qué es un Rol? Están definidos de tal manera que se incrementa la visibilidad que tiene un usuario sobre la información. 

G.	¿Qué es un Validation Rule?Verifica que los datos que ingresa el usuario en un registro coincida con los estándares 
especificados antes del guardado del registro.

H.	¿Qué diferencia hay entre una relación Master Detail y Lookup?La relación Lookup de Salesforce no tiene relación con otros registros. 

No depende de ningún otro objeto, mientras que Master-Detail si se asocia con otros registros. Por otro lado, la relación lookup es solo una referencia. 

Puede estar vacia o ser NULL. En la base de datos, podemos extraer los datos de un campo en particular basándose en las Keys de referencia.

I.	¿Qué es un Sandbox?Es una copia de mi organización, separada en un entorno diferente que puede ser usado para distintos propósitos, como testing o traning.

J.	¿Qué es un ChangeSet? Es usado para enviar personalizaiones de una organización Salesforce a otra. Por ejemplo, se puede crear y testear un nuevo objeto 
en Sandbox org, enviarlo al production org usando un ChangeSet

K.	¿Para qué sirve el import Wizard de Salesforce?Es una manera fácil de importar datos de múltiples estándares de objetos Salesforce, por ejemplo, 
contactos, cuentas, contactos, soluciones, miembros de campañas y cuentas personales. También se puede importar información de objetos personalizados 
con un máximo de 50,000 a la vez.
L.	¿Para qué sirve la funcionalidad Web to Lead? Es el proceso de usar un sitio web como fuente de captura de información para el visitante
 con el fin de almacenar dicha información como un nuevo hilo.
 
M.	¿Para qué sirve la funcionalidad Web to Case? Permite a los clientes presentar peticiones en un sitio web, usando un formato especial y personalizable.

N.	¿Para qué sirve la funcionalidad Omnichannel? Es una herramienta integrada ya sea en Sales, o la consola de servicio, que una vez activa 
y configurada, transmite la información a los usuarios vinculados en tiempo real.

O.	¿Para qué sirve la funcionalidad Chatter? Es una aplicación en tiempo real de Salesforce que te permite trabajar, hablar 
y compartir información entre colaboradores.

#### Conceptos generales

  A.	¿Qué significa SaaS? Software as a service. Es una forma de compartir aplicaciones a través de la WEB como servicio, en vez de instalar 
  y dar mantenimiento a software.
  
  B.	¿Salesforce es Saas? Si, aunque también se le pude llamar Web-Based software.
  
  C.	¿Qué significa que una solución sea Cloud? Es el acceso remoto a software, archivos y procesamiento de datos a través de la WEB sin necesidad de instalar 
  aplicaciones, básicamente un pool de recursos.
  
  D.	¿Qué significa que una solución sea On-Premise? Se refiere al tipo de instalación de una solución de software. La instalación se lleva a cabo dentro del servidor 
  y la infraestructura de la empresa. En este caso la empresa es la responsable de la seguridad, disponibilidad y gestión del software.
  
  E.	¿Qué es un pipeline de ventas? Es una herramienta de gestión que se usa para observar las etapas de ventas con ciclos medios o largos.
  
  F.	¿Qué es un funnel de ventas? Es la estrategia de planeación que establece procesos para ponerse en contacto con los diferentes usuarios.
  
  G.	¿Qué significa Customer Experience? Es una disciplina estratégica muy importante y valorada en una compañía. No se trata tanto de convencer a una persona 
  de que compre un producto o un servicio sino de generar una relación entre consumidor y marca.
  
  H.	¿Qué significa omnicanalidad? Es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de canales como email, 
  redes sociales, sitio web, etc.
  
  I.	¿Qué significa que un negocio sea B2B? Business to Business, es toda empresa que vende a otras empresas. En este caso particular se refiere a un comercio electrónico 
  que en lugar de vender al consumidor final vende a otras empresas.
  
  J.	¿Qué significa que un negocio sea B2C? Business to Consumer es una estrategia de marketing como B2B, con la diferencia de que la publicidad siempre va 
  dirigida al consumidor final.
  
  K.	¿Qué es un KPI? Es un valor medible que demuestra como una compañía alcanza los objetivos clave de forma efectiva. Las empresas lo usan para evaluar el éxito de una tarea.
  
  L.	¿Qué es una API y en qué se diferencia de una Rest API? Un API por si misma, es un conjunto de funciones y procedimientos que permiten a una aplicación, 
  acceder a otra aplicación. Una Rest API es una arquitectura diseñada para el funcionamiento de aplicaciones en la red.
  
  M.	¿Qué es un Proceso Batch? Es la ejecución de una serie de operaciones manuales y automáticas mediante la cual los fabricantes llevan adelante recetas de producción.
  
  N.	¿Qué es Kanban? Es un sistema visual para gestionar el trabajo a medida que avanza en un proceso. Visualiza el flujo del trabajo como también el trabajo real que pasa por   este proceso.
  
  O.	¿Qué es un ERP?  Enterprise Resource Planning, se refiere a un tipo de software que usan las organizaciones para gestionar actividades del negocio día a día. 
  Dichas actividades pueden ser, contabilidad, gestión de proyectos, gestión de riesgo, cumplimiento, entre otras.
  
  P.	¿Salesforce es un ERP? No es un sistema ERP porque no maneja o gestiona información o datos transaccionales. Si bien puede acceder al historial de pedidos o facturas, 
  el proceso es mediante un ERP ajeno a Salesforce.






