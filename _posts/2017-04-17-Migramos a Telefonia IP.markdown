---
title:  "Migramos a telefonía IP ¿Pero cómo?"
comments: true
hidden: false
image: "1896_tel.png"
date: 2017-04-26 23:00:00
categories: [Telefonía, Opinión]
tags: [Telefonía]
keywords: [Cisco, CUCM, CallManager, Telefonía IP]
excerpt: Llega el momento en que nos preguntamos si valdrá la pena migrar hacia la telefonía IP. Les contaré cómo lo hicimos nosotros y algunos detalles que viene bien ir pensando.
---
![](/images/posts/1896_tel.png)
<!-- <img src="/images/posts/1896_telephone.jpg" style="float: right;"  width="300">-->
Llega el momento en que nos preguntamos si valdrá la pena migrar hacia la telefonía IP.

--- ¿Lo vale?  
--- ¡Claro que si!  

Bueno, así la quieren vender, pero todos sabemos que nunca es tan fácil, que aparece una comezón interior que nos tira para atrás... susurrando. Así que pienso que lo mejor sería que les cuente cómo nos decidimos por esta tecnología.

Solo un poco, porque es un tema que da para hablar mucho.

## Un poco de contexto
En mi lugar de trabajo migramos toda nuestra plataforma telefónica, la cual **no** es grande comparada a empresas del primer mundo _pero sí para nuestro paisito_. Quizás estamos por los **2000** teléfonos dispersos en **más de 100 locales** por todo el Uruguay. Esto es con la complejidad y mezcla de servicios que conlleva.

Contamos con una plataforma propietaria marca CISCO, con todas las ventajas y desventajas frente a una solución de software libre. ¿Propietaria! Este punto sería tema para profundizar en otra entrada del blog, que además tiene mucho debate por detrás.

Así que quedémonos con lo que nos ofreció a nosotros:
* Estabilidad
* Uniformidad y homogeneidad (mezclar teléfonos de otras marcas se puede, pero se pierden funcionalidades)
* Soporte y garantía (CISCO es una de las empresas líderes actualmente)
* Simplicidad en la administración (no solo técnicos especializados pueden participar en la operativa)
* Features propietarias sumadas a la mayoría de las features estándar
* Aseguramiento de un umbral de calidad

Pero no duden de lo que les dije, en el mundo de la tecnología se necesita investigar, hay que tener precauciones antes de optar por cualquier solución.

Hay detalles que es bueno tomar en cuenta antes de saltar a la piscina:
* ¿Qué empresa de plaza te puede dar Soporte? Es muy conveniente tener soporte local.
* ¿La empresa de soporte conoce la solución que ofrece? ¿Existen certificaciones y las cumple?
* ¿El fabricante también cuenta con garantía y soporte?
* ¿Cuál es la permanencia y el plan de ruta del fabricante?
* ¿Qué servicios se espera cubrir ahora y qué visión tengo?
* ¿Tiene opciones de integrarse con centrales de terceros? ¿Maneja los estándares?
* ¿Qué tipo de teléfonos puede utilizar y qué grado de servicios pueden manejar?

Este punteo no es exhaustivo, pero realizado con cuidado va a contribuir en varias cosas. Definirá si migrarás a una solución que simplemente sustituya los teléfonos y la central analógica, o si contarás con una plataforma que pueda crecer y adaptarse, integrándose a servicios como Contact Center y además con menos dolores de cabeza a la hora de atender incidentes.

El universo de usuarios es parte del contexto. No está demás decirles que nuestros usuarios, como todos, son _bichos de costumbre_, por lo que **tocar sus cosas** no es bien visto.

## Cuándo tomar la decisión
Ahora. Puede sonar a marketing, pero basta dar un vistazo en la vuelta para darnos cuenta de que el mundo se está moviendo (como dice Roland Deschain) hacia las redes de datos, y los servicios de telefonía van inmersos en ellas.

¿Qué mejor ejemplo que la _eliminación de los troncales E1_ por parte del _proveedor de servicios de telefonía pública_ (ANTEL en nuestro caso)?

## Qué hay del retorno de la inversión
Los teléfonos IP son más caros, y esto en principio es desalentador. No solo tuvimos que cambiar la central, comprar servidores y software sino que además cada teléfono IP sale 4 veces más caro que un teléfono analógico.

Pero aparecen nuevos temas en la mesa:
* **ya no debemos mantener dos infraestructuras de cableado diferentes** (datos y teléfonos),
* no solo contamos con un **único plan de numeración** en todo el país, sino que además un único cluster de servidores en _alta disponibilidad geográfica_ oficia de central telefónica para todos los internos.
* **No tenemos que realizar un nuevo cableado** telefónico por cada **nuevo interno** que se necesite.
* **No más horas** de trabajo dedicadas a **traslados**, ya que basta con enchufar el teléfono en el puesto de datos de la nueva oficina.
* ya ni siquiera es necesario cerrar un túnel VPN entre la casa y la empresa para contar con el número de interno **de forma segura**.

Como ven, la caída en horas de administración y de trabajo en cableado (tedioso para mí por lo menos) inclina la balanza a favor.

Si a todo esto le sumamos el costo cero de cualquier llamada entre internos de todo el país...

¿Y les conté qué bonitos son los teléfonos? :smile:

### Además, no todo es dinero
Tendremos servicios mas _a la mano:_
* Videollamadas
* Buzón de voz integrado a la casilla de mails
* Presencia ("ocupado", "en reunión", "salí a almorzar", etc.), que además se puede integrar a servicios como Exchange y mensajería instantánea.
* Integración con Active Directory.
* Movilidad

## Fidelización
Rápidamente, los teléfonos IP facilitan la fidelización del usuario al ofrecer características como el registro de llamadas, mensajes en pantalla, duración de la llamada, posibilidades de conferencias, captura y transferencia de forma amigable.

¡Pero no hay que descansarse! Si nosotros mismos no promovemos su uso, si no les ofrecemos servicios diferenciadores a los usuarios, todo se traducirá a "no toques mi viejo y querido teléfono por favor"; o incluso **sin el "por favor"**.

Como dice el refrán "mas vale usuario contento que cien volando".

## Manos a la obra
Listo, compremos todo:
* 1000 teléfonos = 180.000,00 USD
* ...

¡Espera! Ya arrancamos mal.

En general, no es fácil promover este tipo de emprendimientos yendo a _todo por el todo_. Las empresas por lo general ya tienen un montón de proyectos que les son más redituables, que ofrecen una ganancia directa y a corto plazo. Esto le quita prioridad a proyectos de este tipo.

Comenzar por un **piloto** es lo ideal. Esto permite comenzar con una inversión más pequeña, con un plan más pensado, y además adaptado no solo a las necesidades de la empresa sino que a las características de los empleados. Nosotros comenzamos nuestro piloto dentro del área de TI, pero no tiene por qué ser su caso; lo mejor es _cranearlo_ un poco.

Claro que llevará varios años de trabajo, pero será un **rato ameno**.

Decidimos comenzar con el área de TI, entre otras cosas, porque:
* Son usuarios a los que les gusta la tecnología
* Están acostumbrados a ambientes de prueba, con todo lo que esto implica (no molestarse por mal funcionamiento es uno de los puntos a favor)
* Pueden aprovechar nuevos servicios de forma más rápida
* ¡Los tenemos cerca! Porque no sé si les dije, pero nuestra área de Comunicaciones, se encuentra en el sector informático.

El último punto fue vital, o por lo menos eso creo yo.

## ¿Dónde comienza todo?
Si nos apuramos, tenemos dos lugares desde donde plantar la semilla: la gente de "Teléfonos" o la gente de "Redes de datos".

Lo primero que uno podría pensar es: "La gente de teléfonos". Está clarísimo, ellos los manejan hoy. Pero... ¿esto no sería un error? Para administrar de forma inteligente el servicio en general, se necesitan conocimientos sobre el tema. De forma rápida puedo enumerar algunos: protocolos, codecs, QoS, ruteo, VLANs, puertos, direccionamiento; todo muy lejos de la conmutación de circuitos y muy cerca de la conmutación de paquetes.

Pero el conocimiento del personal de Teléfonos no deja de ser valioso. Debemos notar que tienen una cantidad importante de trabajo sobre el cableado, plan de numeración y un gran acercamiento al usuario. Esto les va a dar para pensar un rato... En nuestro caso, incluirlos al grupo fue lo mejor que pudimos hacer.

## Y da para más... pero no hoy.
¡Se extendió el post! Y con un montón de otras cosas para contar. Los invito a compartirlo si les resultó interesante e incluso a dejarme su opinión.

Por el momento no he creado una sección de subscripción, pero están invitados a seguirme en twitter.
> **EDIT** \\
> Ya incorporé la sección **¡Entérate de nuevos artículos!** que podrán encontrar en el menú del sitio. Ahí tienen la posibilidad de **Subscribirse** a la lista de correo y así recibir las notificaciones de nuevos artículos.

¡Hasta la próxima!
