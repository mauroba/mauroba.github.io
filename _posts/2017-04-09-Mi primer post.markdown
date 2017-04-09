---
title:  "¡Mi primer post!"
comments: false
date:   2017-04-09 17:00:00
categories: [Programación]
tags: [Jekyll]
excerpt: Quería escribir un blog, pero <strong>no solo el contenido</strong>. No quería caer en servicios que te dejan todo listo, son dueños de toda tu informaicón y pierdes todo si dejan de existir, pero quería que sea gratis. Aquí les cuento <strong>cómo lo hice</strong>.
---
Primero quiero agradecer a [Gervasio Marchand](https://g3rv4.com/), programador, ingeniero, nerd y amigo. No necesariamente en ese orden. :P Él despertó mi interés en este emprenidmiento y algunos de sus posts fueron de gran ayuda.

En este post __no encontrarán__ los detalles de _cómo lo hice_, sino que una suerte de resumen, ya que se tornaría un post aburrido de leer. Tengo pensado crear un par de posts más con guías de los puntos que fueron más complicados.

## ¿Qué buscaba?

_Cortito y al pie_: un blog del que tuviera el control.

Esto implica que tengo el código fuente, lo modifico a gusto, no tengo las restricciones que imponen los servicios de blog gratuitos, tengo una copia local de todo el sitio y no importa si el lugar de hosting deja de existir.

## Busquemos un dominio.

Ya tengo un dominio pago: [www.seveloquedigo.com](www.seveloquedigo.com) (dedicado al humor) y no quería pagar dos. En un futuro, si todo va bien, veré esta posibilidad, pero por ahora soy mi único lector. jaja.

Si quieren tener una idea, cuesta 14 USD al año, en realidad no es un servicio caro.

En este punto debo agradecer a los dominios gratuitos. Si como yo, no sabías que existen, te estarás preguntando ¿dónde está el truco?. La idea es no profundizar en esto, pero aquí hay algunos puntos a tener en cuenta:
* Solo permiten registros de un año de duración
* La opción de renovación, aunque es gratuita puede realizarse solo desde las dos semanas anteriores a su vencimiento
* Seguramente no seas dueño del dominio
* No son extensiones conocidas como (.com .es . net) y cada vez más gente conoce que ha sido un registro gratuito, afectando la imagen del producto que quieres compartir.

Luego de un rato, me decidí por el dominio tk, ofrecido por el servicio [freenom](http://www.freenom.com/es/freeandpaiddomains.html)

## Servidor de nombre DNS

Freenom, adicionalmente ofrece un servicio gratuito de servidor DNS. Esto ayudó a que me decidiera por esta empresa, ya que otras ofrecen una simple redirección.

## ¿Qué pasa con el hosting?

Un hosting anda por alrededor de 70 USD al año. Pero esto es un hobby, así que seguí investigando.

Finalmente encontré que [GitHub](https://github.com/), el ya conocido sitio para desarrolladores, ahora ofrece un servicio llamado [Github-Pages](https://pages.github.com/) que permite utilizar uno de tus repositiorios como Website (se traduce en _hosting gratuito_).

Esto es una genialidad, tu sitio web tiene a su disposición todas las herramientas ofrecidas para tus códigos: control de versiones, merge, sincronización local, pull, push, etc.

Pero no basta con un hosting, ¿cómo diseñaría y mantendría un blog sobre github-pages? Yo soy un futuro ingeniero eléctrico con una pasión escondida hacia la programación, pero no soy realmente un desarrollador.

Ahí surgió la posibilidad de usar [Jekyll](http://jekyllrb.com/)

## ¿Jekyll?

Si aún no lo hicieron, sigan el enlace anterior y lean la home. Es un _generador estático diseñado para blogs_. ¿Qué es lo que me gustó más de él? La posibilidad de sentirme en la matrix.

Suena gracioso pero es verdad. No es para cualquier usuario final, los post se escriben en consola o en un editor de textos. Te olvidas de los frustrantes formatos automáticos que aparecen y desaparecen cuando quieren en los servicios de blogs online. Es un poco como escribir en Latex.

Así que me decidí por Jekyll. Busqué un template entre los muchos que hay en la web y lo cloné en mi repositorio de GitHub.

Luego manos a la obra, a modificarlo a gusto.

¡Nos leemos en la próxima!
