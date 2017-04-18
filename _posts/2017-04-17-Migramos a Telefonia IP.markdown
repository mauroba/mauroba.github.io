---
title:  "Migramos a telefonía IP ¿Cómo llegamos hasta aquí?"
comments: true
hidden: true
date: 2017-04-17 09:00:00
categories: [Telefonía, Opinión]
tags: [Telefonía]
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

No tengo por qué decirles la gran contra ($$$). :laughing: No es tan así, pero ojo, esto es cuestión de costo-beneficio. Con qué servicios quieres contar, de qué forma y a qué costo; el costo no necesariamente cae en el dinero. Hay que indagar un poco antes de optar por alguna solución:
* ¿Qué empresa de plaza te puede dar Soporte?
* ¿Es un partner o un distribuidor?
* ¿Conoce la solución?
* ¿El fabricante cuenta con garantía y soporte?
* ¿Cuál es la permanencia y el roadmap del fabricante?
* ¿Qué servicios espero dar ahora y qué visión tengo a futuro?
* ¿Tiene opciones de integrarse con centrales de terceros? ¿Maneja los estándares?
* ¿Qué tipo de teléfonos puede utilizar y qué grado de servicios pueden manejar?
* Y massss...

Este estudio de factibilidad puede definir si migrarás a una solución que simplemente sustituya los teléfonos y central analógica o si contarás con una plataforma que pueda crecer y adaptarse, agregando incluso servicios de Contact Center, voicemail, etc.

## Cuándo tomar la decisión
Quizás el momento sea ahora (en realidad pienso que el mejor momento fue hace unos años). Puede sonar a marketing, pero basta dar un vistazo en la vuelta para darnos cuenta de que el mundo se está moviendo (como dice Roland Deschain) hacia las redes de datos, y los servicios de telefonía van inmersos en ellas.

Qué mejores ejemplos que la _eliminación de los troncales E1_ por parte del _proveedor de servicios de telefonía pública_ (ANTEL en nuestro caso), la _integración de páginas web_ al mundo de las _llamadas de voz_ (webRTC) y el *teletrabajo* (trabajo en casa). En el último de los ejemplos ya ni siquiera es necesario cerrar un túnel VPN entre la casa y la empresa para contar con el número de interno.

## Qué hay del retorno de la inversión
El ROI no es fácil de ver o calcular sin conocer cada realidad, pero les doy unos puntos a tener en cuenta basados en mi experiencia.

Los teléfonos IP son más caros, y esto en principio es desalentador. No solo tuvimos que cambiar la central, comprar servidores y software sino que además cada teléfono IP sale 4 veces más caro que un teléfono analógico.

Pero:
* **ya no contamos con dos infraestructuras de cableado diferentes** para **datos** y **teléfonos**; mantenemos solamente la red cableada destinada a los datos.
* no solo contamos con un **único plan de numeración** en todo el país, sino que además un único cluster de servidores en alta disponibilidad geográfica ofician de central telefónica para todos los internos.
* **No tenemos que realizar un nuevo cableado** telefónico por cada **nuevo interno** que se solicite.
* Nos **olvidamos** de los teléfonos en **paralelo**.
* **No más horas** de trabajo perdidas en **traslados**, ya que basta con enchufar el teléfono en el puesto de datos de la nueva oficina.
* Podemos optar por qué canal salen las llamadas de cualquier parte del país.

Como ven, la caída en horas de Administración y de trabajo en cableado (tedioso para mí por lo menos) inclina la balanza.

Adicionalmente aparecen servicios como los siguientes:
* Los teléfonos IP logran fidelización del usuario al ofrecer características como el registro de llamadas, pantallas que te indican si hay llamadas para capturar, quién llama a quién, botones con features configurables para cada caso, etc.
* Buzón de voz capaz de leer la casilla de mails.
* Se aprovecha la presencia ("ocupado", "en reunión", "salí a almorzar", etc.), que además se puede integrar a servicios como Exchange y mensajería instantánea.
* Integración con Active Directory.
* Videollamadas
* Movilidad

Si a todo esto le sumamos el costo cero de cualquier llamada entre internos de todo el país, podemos ir tranquilizando nuestros temores.
