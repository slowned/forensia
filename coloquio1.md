**PGP**: es un criptosistema hibrido que combina tecnicas de criptografia simetrica y criptografia asimetrica,
esta combinacion permite aprvechar lo mejor de cada una.
    * El cifraddo simetrico es mas rapido que el asimetrico o de clave publica.
    * El asimetrico proporciona una solucion al programa de la distribucion de claves en forma segura y garantiza el no repudio de los datos y la no suplantacion.

## Cifrado asimetrico
    1. Ana redacta un mensaje.
    2. Ana cifra el mensaje con la **clave publica** de david.
    3. Ana enia el mensaje cifado a david.
    4. David recie el mensaje cigrado y lo descifra con su **clave privada**.
    5. David puede leer el mensaje original qu le envio Ana.
    
## Cifrado cimetrico
    1. David redacta un mensaje.
    2. David firma digitalmente el mensaje con su **clave pivada**.
    3. David envia el mensaje.
    4. Ana recibe el mensaje firmado y comprueba su auenticidad usando la **clave publica** de David.
    5. Ana ya puede leer el mensaje con total seguridad de que ha sido David el remitente.


## Introduccion a la forensia digital
* El analisis forense es un sistema informatico es una ciencia moderna que permite recontruir lo que ha sucedido en un sistema tras un incidente de seguridad.
* Puede determinar quien, desde, donde, como, cuando y que acciones ha llevado a cabo un intruso en los sistemas afectados por un incidente de seguridad.

## Que es la evidencia digital? 
* La evidencia digital es informacion y datos valor investigativo que es guardada en o transmitida por un dispositivo electronico.
    * Suele ser latente en el mismo sentido en que las huellas digitales y el ADN.
    * Pude trascender fronteras con facilidad y rapidez, no es lo mismo por ejemeplo llevar cajas con documentos en el banco de aca a China que enviar un archivo via Dropbox.
    * Es fragil  puede ser fracilmente alterada, daniada o destruidad, por examincion o manejo inapropiado.
    * En algunos casos puede llegar a ser time-sensitive.

* Cuando se trabaja con evidencia digital hay principios de forensia general y procedural que deban ser aplicados:
    * Las acciones tomadas para recolectar y asegurar la evidencia digital no debe cambiarla ni modificarla en ningun sentido. (Hashinh y Cadena de custodia)
    * Las personas que diriajan la eaminacion de la envidencia digital debe estar entrenadas en el campo.
    * La actividad relacionada debe ser documentada en su totalidad, ya sea la incautacion, la eaaminacion, el almacenamiento o la transgerencia de la evidencia digital.

## Etapas del proceso forense:
1. Recoleccion/Adquisicion
1. Examinacion
1. Analisis
1. Reporte

## Triangulo de la CIA/ CID
* **Confidencialidad** que solo el que tenga acceso a la informacion lo pueda acceder.
* **Integridad** que la informacion no pueda ser modificada sin ser detectado.
* **Disponibilidad** que aquel que tiene acceso ala informacion siempre tenga la posibilidad de hacerlo.

Aplicando estos 3 conceptos tenemos **seguridad**

### Incidentedes e seguridad
* Ataques de denegacion de servicio.
* Extorsion.
* Posesion de pornografia infantil.
* Envio de correos electronicos ofensivos.
* Fuga de informacion confidencial dentro de la organizacion en la cual esta involucrado algun sistema informatico de nuestra organizacion.

> A finales de Julio de 2015 salto el escandalo del roo de la base de datos de todos los clientes
> de la web de contactos Ashley Madison (web para infieles.)
> **Vulnerabilidad:** los datos de los usuarios del sito **Ashley Madision** no estan adecuadamente protegidos, ya sea porque la red de la empresa
> no tiene la suficientes medidas de seguridad, la infraestructura no esta actualizada o el software tenga algun problema.
> **Amenaza:** que alguien robe satos de esa red y los publique.
> **Incidente:** fines de julio de 2015, el grupo Impact Team hace publico un listado con mas de 10GB de informacion de los clientes del siteo.

* Cuando la confidencialidad de los datos se pierde es imposible volver atras
> **Vulnerabilidad:** La máquina del usuario no tenga filtros correctamente configurados como ser
> antimalware o filtros de navegación, no existan backups de los datos del usuario, o incluso que el
> usuario tenga más accesos de los necesarios a distintos archivos.
> **Amenaza:**  que se ejecute un archivo malicioso en el equipo ocasionando la perdida de la
> información
> **Incidente:** El usuario de la terminal recibió un correo electrónico con un adjunto, lo abrió y resultó
> que era un crytpo ransomware ocasionando la pérdida de acceso a todos los datos del usuarios.

### Conceptos relacionados
* Una **vulnerabilidad** es una debilidad en un activo.
* Una **amenaza** es una violacion potencial de la seguridad.
* Las **amenazas** sacan ventaja de las **vulnerailidades**.

### Tipos de Amenazas
* **Naturales** (Incendios, terremotos, inundaciones)
* **Humanas** (Malicionas, No maliciosas)

### Motivos para investigar un incidente
* Finalidad, reconstruir lo sucedido, tenemos distintos motivos que pueden justificar y dependiendo de el motivo son los recaudos que hay quet tomar:
    1. **Legales:** cuando el requerimiento es requerido por un proceso de altun tipo, como un proceso jdicial, que requiere la consevacion de la validez de las evidencias.
    1. **No legal:** cuando la necesidad de averiguar que ocurrio obedece a motivos no legales, como ser necesidad de recuperar un sericio daniado o conocer el alcance de un malware.

### Destinataios de los ataques
* **General**: para distribuir entre el publico en general. Por ejemplo para ataques de DDoS.
* **Orientado**: con un poposito especifico. Por ejemplo troyanos bancarios.

> Acualmente cuan do el ataque del malware perdura en el tiempo el termino de moda es APT (Advanced Persistent Threat o "amenaa persistente aanzada").
> Ejemplos: Carbanak y Puerto de Belgica.

### Fuentes de informacion
las fuentes de informacion que se utilizan para realizar un analisis forense son diversas:
* Correos electronicos.
* Logs de los Firewall
* IDS / IPS.
* Logs de los sistemas/ aplicaciones involucradas.
* Entrevistas con los responsables de seguridad de los sistemas.

#### Archivos de log
El proposito principal de los archivos e log es registrar eventos significativos o interesantes, se pueden usar para:
    * Troubleshooting en general
    * Correlacion de eventos
    * Deteccion de intrusiones
    * Manejo de incidentes

#### Firewall
Un firewall es un sistema utilizado en una red o en un gost con el objeto e controlar las comunicaciones, permitiendolas o prohibiendolas segun las politicas que se hayan definio
en la organizacion o el criterio del usuario que lo implementa.

#### Metadatos 
Se pueden definir a los metadatos como los "datos sobre los datos". Los metadatos permiten ayudar a la identificacion, descripcion, clasificacion y localizacion de un recurso. En
los sistemas operativos, estos metadatos se guardan junto a los archivos.
> mactime: fecha de creacion, acceso y modificacion de un archivo.
> dato de gps.
> tipo de archivo.
> autor.
> cuando fue creado, modificado.

#### Datos residuales
Cuando un usuario borra un archivo, el SO no borra literalmente el archivo, sino que lo marca como espacio disponible.
El contenido del archivo se mantiene hasta que este sea sbreescrito. De modo que estos datos pueden ser encontrados y aaccedidos por los ferenses utilizando las herramientas adecuadas.

#### IDS/IPS
La deteccion de instrusiones (IDS) es el arte de detectar actividad sospechosa, incorrecta o inapropiada. Los sistemsa de preencion de instrusiones (IPS) son mecanismos de defensa
proactivos dise;ados para detectar actividad maliciosa y detener intrusiones, bloqueando dicha actividad "ofensiva" automaticamente antes de que esta realice algun da;o.


#### Sistema de archivos
* Es el componente del SO encagado e administrar y facilitar el uso de las memorias perisfericas (secundarias, terciarias).
* Sus principales funciones son la asisgnacion de espacio a los archivos, la dministracion del espacio libre y del acceso a los datos resguardados.
* EStructuran la informacion guardada en un dispositivo de almacenamiento de datos o unidad de almacenamiendo, que luego sera representada textual o graficamente por un gestor de archivos.
* La mayoria de los SO manejan multiples sistemas de archivos.

####  Esteganografia
* Es la disciplin en la que se estudian y aplican tecnicas que permiten el ocultamiento e objetos o mensajes, dentro de otros llamados portadores, de manera que no se perciba su existencia.
* En termino informatico se refiere a la informacion o a veces incluso a un archivo que se encuentra oculto dentro de otro.
* Normalmente el contenedor es algun archivo del tipo multimedia. como una imagen digital, un video o un audio.

#### Criptografia
* Es la ciencia que consiste en transformar un mensaje legible en otro que no lo es (solo el emesor y el destinatario conocen como leerlo), para despues devolverlo a su forma original,
sin que nadie que vea el mensaje cifrado sea capaz de entenderlo.
* Se utiliza para:
    * Autentificar la identidad de usuarios
    * Autentigicar y proteger el sigilo de comunicaciones personales y de transacciones comerciales y bancarias
    * Protege la integridad de transferencias electronicas de fondos

#### Hashing
Es el proceso utilizado para generar una idenficacion unica o "fingerprint" digital de una entrada. Ej: una imagen de disco.
* Cuando se utiliza una funcion de hash segura, dos entradas no pueden generar el mismo hash.

#### Hashing en la forensia digital
* Gracias a sus propiedades , las funciones de hash son utilizadas para comprobar que una evidencia no ha sido alterada durante la investigacion.
* Si un bit de la imagen es alterado, su hash sera distinto al original.

#### Encoding
>  Ejemplo HOLA CLASE
>  BASE64: SE9MQSBDTEFTRQ==
>  HEXA: x48x4fx4cx41x20x43x4cx41x53x45
>  Atbahs: SLOZ XOZHV
>  ROT13: UBYN PYNFR
>  URL Encode: HOLA%20CLASE

#### La Cadena De Custodia
Es uno de los protocolos de actuacion que ha se seguirse con respecto a una prueba durante su periodo de vida o e validez, desde que esta se consigue o genera, hasta que se destruye, o deja de ser necesaria. Este protocolo debe controlar donde y como se ha obtenido la prueba, que se ha hecho con ella y cuando, quien ha tenido acceso a la misma, donde se encuentra esta en todo momento y quien la tiene y, en caso de su destruccion, por la causa que sea, como se ha destruido, cuando, quien, donde y el porque.
 * Se utiliza para documentar informacion vital sobre la evidencia adquirida.
 * La ocumentacion esencial para la evidencia digital:
    * Fecha y hora de la adquisicion.
    * De donde se ha entraido la informacion (serial y modelo del dispositivo).
    * Que metodo ha sido utilizado para extraer la imagen?.
    * Hash de la evidencia y cual funcion fue utilizada para generarla (md5,sha1,etc).
    * Personas involucradas en la transferencia.

* La cadena debe cumplirse para que la evidencia sea valida.
* Debe ser actualiada cada vez que la evidencia es transferida.
* Toda copia de la evidencia deber tener un formulario de "copia de evidencia".







































































