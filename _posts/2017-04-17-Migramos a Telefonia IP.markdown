---
title:  "Migramos a telefonía IP ¿Cómo llegamos hasta aquí?"
comments: true
hidden: true
date: 2017-04-17 09:00:00
categories: #[Telefonía, Opinión]
tags: #[Telefonía]
keywords: [Cisco, CUCM, CallManager, Telefonía IP]
excerpt: Llega el momento en que nos preguntamos si valdrá la pena migrar hacia la telefonía IP.
---
Llega el momento en que nos preguntamos si valdrá la pena migrar hacia la telefonía IP.

--- ¿Lo vale?  
--- ¡Claro que si!  
--- Fin.  

Este pudo ser el resumen, pero todos sabemos que nunca es tan fácil, que aparece esa comezón interior que nos tira para atrás susurrando "cuidado". Así que pienso que lo mejor sería que les cuente, un poco por arriba, cómo nos decidimos por esta tecnología.

## Un poco de contexto
En mi lugar de trabajo migramos toda nuestra plataforma telefónica, la cual **no** es grande comparada a empresas del primer mundo **pero sí** para nuestro _paisito_. Quizás estamos por los **2000** teléfonos dispersos en **más de 100 locales** por todo el Uruguay. Esto con la complejidad y mezcla de servicios que conlleva.  

Contamos con una plataforma propietaria marca CISCO, tanto en servidores (CUCM) como en teléfonos, con todas las ventajas y desventajas frente a una solución de software libre. Este punto sería tema para profundizar en otra entrada del blog, que además tiene mucho debate por detrás. Así que quedémonos con lo que nos ofreció a nosotros esta solución:
* Estabilidad
* Uniformidad y homogeneidad
* Soporte y garantía
* Simplicidad en la administración (no solo técnicos especializados pueden participar en la operativa)
* Features propietarias sumadas a la mayoría de las features estándar
* Aseguramiento de un umbral de calidad

Hay que indagar un poco antes de optar por alguna solución:
* ¿Qué empresa de plaza te puede dar Soporte?
* ¿Es un partner o un distribuidor?
* ¿Conoce la solución?
* ¿El fabricante cuenta con garantía y soporte?
* ¿Cuál es la permanencia y el roadmap del fabricante?
* ¿Qué servicios espero dar ahora y qué visión tengo a futuro?
* ¿Tiene opciones de integrarse con centrales de terceros? ¿Maneja los estándares?
* ¿Qué tipo de teléfonos puede utilizar y qué grado de servicios pueden manejar?

Este punteo no es exhaustivo, pero realizado con cuidado puede definir si migrarás a una solución que simplemente sustituya los teléfonos y central analógica, o si contarás con una plataforma que pueda crecer y adaptarse, integrándose a servicios de Contact Center y además con menos dolores de cabeza a la hora de atender incidentes.

## Cuándo tomar la decisión
Quizás el momento sea ahora (en realidad pienso que el mejor momento fue hace unos años). Puede sonar a marketing, pero basta dar un vistazo en la vuelta para darnos cuenta de que el mundo se está moviendo (como dice Roland Deschain) hacia las redes de datos, y los servicios de telefonía van inmersos en ellas.

Qué mejores ejemplos que la _eliminación de los troncales E1_ por parte del _proveedor de servicios de telefonía pública_ (ANTEL en nuestro caso), la _integración de páginas web_ al mundo de las _llamadas de voz_ (webRTC) y el *teletrabajo* (trabajo en casa). En el último de los ejemplos ya ni siquiera es necesario cerrar un túnel VPN entre la casa y la empresa para contar con el número de interno **de forma segura**.

## Qué hay del retorno de la inversión
El ROI no es fácil de ver o calcular sin conocer cada realidad, pero les doy unos puntos a tener en cuenta basados en mi experiencia.

Los teléfonos IP son más caros, y esto en principio es desalentador. No solo tuvimos que cambiar la central, comprar servidores y software sino que además cada teléfono IP sale 4 veces más caro que un teléfono analógico.

Pero:
* **ya debemos mantener dos infraestructuras de cableado diferentes** (datos y teléfonos); mantenemos solamente el cableado destinado a la red de datos.
* no solo contamos con un **único plan de numeración** en todo el país, sino que además un único cluster de servidores en _alta disponibilidad geográfica_ oficia de central telefónica para todos los internos.
* **No tenemos que realizar un nuevo cableado** telefónico por cada **nuevo interno** que se solicite.
* **No más horas** de trabajo dedicadas a **traslados**, ya que basta con enchufar el teléfono en el puesto de datos de la nueva oficina. Los traslados no necesitan trabajo adicional incluso si son entre departamentos, basta con tener un puesto de red.

Como ven, la caída en horas de administración y de trabajo en cableado (tedioso para mí por lo menos) inclina la balanza a favor.

Si a todo esto le sumamos el costo cero de cualquier llamada entre internos de todo el país, podemos ir tranquilizando nuestros temores.

### No todo es sobre el dinero
Adicionalmente aparecen servicios:
* Buzón de voz integrado a la casilla de mails
* Presencia ("ocupado", "en reunión", "salí a almorzar", etc.), que además se puede integrar a servicios como Exchange y mensajería instantánea.
* Integración con Active Directory.
* Videollamadas
* Movilidad

## Fidelización
Rápidamente, los teléfonos IP facilitan la fidelización del usuario al ofrecer características como el registro de llamadas, mensajes en pantalla, duración de la llamada, posibilidades de conferencias, captura y transferencia de forma más amigable.
