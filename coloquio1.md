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

* Cuando la confidencialidad e los datos se pierde es imposible volver atras
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


